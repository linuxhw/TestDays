Pop!_OS 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 3159

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| System76      | Oryx Pro                    | [07e4e6a0a8](https://linux-hardware.org/?probe=07e4e6a0a8) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [14df5ebb53](https://linux-hardware.org/?probe=14df5ebb53) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [00ee13cdb6](https://linux-hardware.org/?probe=00ee13cdb6) | Jan 01, 2024 |
| Apple         | MacBookPro7,1               | [9181cf5581](https://linux-hardware.org/?probe=9181cf5581) | Jan 01, 2024 |
| MSI           | P65 Creator 9SE             | [2e5c1a6b06](https://linux-hardware.org/?probe=2e5c1a6b06) | Jan 01, 2024 |
| Lenovo        | ThinkPad P50 20EQS3YS00     | [34294e5b8b](https://linux-hardware.org/?probe=34294e5b8b) | Dec 31, 2023 |
| Apple         | MacBookPro10,2              | [386449d6f7](https://linux-hardware.org/?probe=386449d6f7) | Dec 31, 2023 |
| Dell          | Latitude 7480               | [9872ef6241](https://linux-hardware.org/?probe=9872ef6241) | Dec 31, 2023 |
| Dell          | Latitude 7480               | [527544c2de](https://linux-hardware.org/?probe=527544c2de) | Dec 31, 2023 |
| Google        | Delbin                      | [51a51a978d](https://linux-hardware.org/?probe=51a51a978d) | Dec 31, 2023 |
| Lenovo        | Y50-70 20378                | [ff5e2959f8](https://linux-hardware.org/?probe=ff5e2959f8) | Dec 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b94c50cb10](https://linux-hardware.org/?probe=b94c50cb10) | Dec 30, 2023 |
| Acer          | Nitro AN515-58              | [a0039ef79d](https://linux-hardware.org/?probe=a0039ef79d) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [f48ada0e7b](https://linux-hardware.org/?probe=f48ada0e7b) | Dec 30, 2023 |
| Metabox       | Alpha-X NH58HP              | [983844e1c8](https://linux-hardware.org/?probe=983844e1c8) | Dec 30, 2023 |
| Acer          | SF314-71-50E8               | [a2704f17ea](https://linux-hardware.org/?probe=a2704f17ea) | Dec 29, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [bbe4e7af60](https://linux-hardware.org/?probe=bbe4e7af60) | Dec 29, 2023 |
| Lenovo        | B490 37722KP                | [194971e987](https://linux-hardware.org/?probe=194971e987) | Dec 29, 2023 |
| Lenovo        | ThinkPad L590 20Q8S0QB00    | [21c14a621b](https://linux-hardware.org/?probe=21c14a621b) | Dec 29, 2023 |
| ASUSTek       | G73Jh                       | [05dc836501](https://linux-hardware.org/?probe=05dc836501) | Dec 28, 2023 |
| Notebook      | NL40_50CU                   | [a91c55ef9f](https://linux-hardware.org/?probe=a91c55ef9f) | Dec 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [2e6989112a](https://linux-hardware.org/?probe=2e6989112a) | Dec 28, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | [0f8be1187e](https://linux-hardware.org/?probe=0f8be1187e) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a5c652bcef](https://linux-hardware.org/?probe=a5c652bcef) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [02799d9fc9](https://linux-hardware.org/?probe=02799d9fc9) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [341b25443b](https://linux-hardware.org/?probe=341b25443b) | Dec 28, 2023 |
| ASUSTek       | K75VM                       | [4f1fddffba](https://linux-hardware.org/?probe=4f1fddffba) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | [72e733aa23](https://linux-hardware.org/?probe=72e733aa23) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | [f7d4fcd885](https://linux-hardware.org/?probe=f7d4fcd885) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | [865ecc4a8b](https://linux-hardware.org/?probe=865ecc4a8b) | Dec 27, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [8017d1c054](https://linux-hardware.org/?probe=8017d1c054) | Dec 27, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [db50c73272](https://linux-hardware.org/?probe=db50c73272) | Dec 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [34060a7062](https://linux-hardware.org/?probe=34060a7062) | Dec 26, 2023 |
| Dell          | Latitude E6520              | [634e14ff4c](https://linux-hardware.org/?probe=634e14ff4c) | Dec 25, 2023 |
| MicroByte     | ezbook                      | [a03eec4fc7](https://linux-hardware.org/?probe=a03eec4fc7) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | [f385a26e94](https://linux-hardware.org/?probe=f385a26e94) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | [744adae48d](https://linux-hardware.org/?probe=744adae48d) | Dec 25, 2023 |
| HP            | 255 G8 Notebook PC          | [1f14807c5e](https://linux-hardware.org/?probe=1f14807c5e) | Dec 25, 2023 |
| Lenovo        | ThinkPad T540p 20BFS0620... | [5cceadde0c](https://linux-hardware.org/?probe=5cceadde0c) | Dec 25, 2023 |
| PC Special... | N150CU                      | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| PC Special... | GK7NP5R                     | [1d97edcad7](https://linux-hardware.org/?probe=1d97edcad7) | Dec 23, 2023 |
| System76      | Serval WS                   | [92d124a8aa](https://linux-hardware.org/?probe=92d124a8aa) | Dec 23, 2023 |
| System76      | Gazelle                     | [6671df79bd](https://linux-hardware.org/?probe=6671df79bd) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [f5f4795192](https://linux-hardware.org/?probe=f5f4795192) | Dec 22, 2023 |
| Dell          | Latitude E6430s             | [2b580a7725](https://linux-hardware.org/?probe=2b580a7725) | Dec 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [1e223a9ea1](https://linux-hardware.org/?probe=1e223a9ea1) | Dec 21, 2023 |
| DEXP          | Atlas M15-I3W302            | [176dd6f77a](https://linux-hardware.org/?probe=176dd6f77a) | Dec 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ff06842733](https://linux-hardware.org/?probe=ff06842733) | Dec 20, 2023 |
| Dell          | Precision 5680              | [b8b5bc0292](https://linux-hardware.org/?probe=b8b5bc0292) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [00b16e835d](https://linux-hardware.org/?probe=00b16e835d) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [0b6e9c4c26](https://linux-hardware.org/?probe=0b6e9c4c26) | Dec 20, 2023 |
| Apple         | MacBookPro8,1               | [24ff90d774](https://linux-hardware.org/?probe=24ff90d774) | Dec 20, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | [5eca78aa43](https://linux-hardware.org/?probe=5eca78aa43) | Dec 19, 2023 |
| Dell          | Latitude E5270              | [c25a5b1bc7](https://linux-hardware.org/?probe=c25a5b1bc7) | Dec 19, 2023 |
| System76      | Pangolin                    | [a0cf57c6d1](https://linux-hardware.org/?probe=a0cf57c6d1) | Dec 19, 2023 |
| HP            | Dev One Notebook PC         | [b10cd89445](https://linux-hardware.org/?probe=b10cd89445) | Dec 19, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [e7ed0c7c8a](https://linux-hardware.org/?probe=e7ed0c7c8a) | Dec 18, 2023 |
| HP            | Dev One Notebook PC         | [3c5fc22ea0](https://linux-hardware.org/?probe=3c5fc22ea0) | Dec 17, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [f8cfc75a8a](https://linux-hardware.org/?probe=f8cfc75a8a) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [6e359357d4](https://linux-hardware.org/?probe=6e359357d4) | Dec 17, 2023 |
| HP            | ProBook 4535s               | [80aa5bd12b](https://linux-hardware.org/?probe=80aa5bd12b) | Dec 17, 2023 |
| Dell          | Latitude E7450              | [f429af38c1](https://linux-hardware.org/?probe=f429af38c1) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [801f62b573](https://linux-hardware.org/?probe=801f62b573) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [d16bd87505](https://linux-hardware.org/?probe=d16bd87505) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [7f32922e8f](https://linux-hardware.org/?probe=7f32922e8f) | Dec 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | [b90524a691](https://linux-hardware.org/?probe=b90524a691) | Dec 16, 2023 |
| Dell          | Inspiron 14 5420            | [ef0c78ce49](https://linux-hardware.org/?probe=ef0c78ce49) | Dec 16, 2023 |
| Dell          | XPS 15 9530                 | [c35aa056cf](https://linux-hardware.org/?probe=c35aa056cf) | Dec 16, 2023 |
| Apple         | MacBookAir7,2               | [d227968843](https://linux-hardware.org/?probe=d227968843) | Dec 16, 2023 |
| Toshiba       | TECRA Z50-A                 | [8717000b31](https://linux-hardware.org/?probe=8717000b31) | Dec 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [10f1017f04](https://linux-hardware.org/?probe=10f1017f04) | Dec 16, 2023 |
| realme        | RMNBXXXX                    | [c5e74761c7](https://linux-hardware.org/?probe=c5e74761c7) | Dec 15, 2023 |
| HP            | Laptop 15s-eq0xxx           | [cee2ad1e7c](https://linux-hardware.org/?probe=cee2ad1e7c) | Dec 15, 2023 |
| Toshiba       | IS 1413G                    | [09d89c7989](https://linux-hardware.org/?probe=09d89c7989) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4919d10355](https://linux-hardware.org/?probe=4919d10355) | Dec 14, 2023 |
| Samsung       | 300E5E/300E4E/300E5V/300... | [e7d5f85bea](https://linux-hardware.org/?probe=e7d5f85bea) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Apple         | MacBookPro11,1              | [539d1d09fe](https://linux-hardware.org/?probe=539d1d09fe) | Dec 11, 2023 |
| System76      | Lemur Pro                   | [05062ae2dd](https://linux-hardware.org/?probe=05062ae2dd) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | [832dd09409](https://linux-hardware.org/?probe=832dd09409) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | [b17b809ccf](https://linux-hardware.org/?probe=b17b809ccf) | Dec 10, 2023 |
| Acer          | Aspire A515-57              | [1adc377142](https://linux-hardware.org/?probe=1adc377142) | Dec 10, 2023 |
| ASUSTek       | X542URR                     | [3e42bedcd3](https://linux-hardware.org/?probe=3e42bedcd3) | Dec 10, 2023 |
| ASUSTek       | X550JK                      | [06e9cf1c8d](https://linux-hardware.org/?probe=06e9cf1c8d) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [296e90c442](https://linux-hardware.org/?probe=296e90c442) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [cea0431bcb](https://linux-hardware.org/?probe=cea0431bcb) | Dec 09, 2023 |
| Razer         | Blade                       | [bf9ad5f7df](https://linux-hardware.org/?probe=bf9ad5f7df) | Dec 09, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [e7d15edec4](https://linux-hardware.org/?probe=e7d15edec4) | Dec 09, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| ASUSTek       | G53SX                       | [6d01f19f82](https://linux-hardware.org/?probe=6d01f19f82) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | [944218c6ec](https://linux-hardware.org/?probe=944218c6ec) | Dec 08, 2023 |
| Dell          | Inspiron 1525               | [0ee42c0440](https://linux-hardware.org/?probe=0ee42c0440) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | [2499101d89](https://linux-hardware.org/?probe=2499101d89) | Dec 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | [87477ed836](https://linux-hardware.org/?probe=87477ed836) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [13080ba71b](https://linux-hardware.org/?probe=13080ba71b) | Dec 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [0d809d54ad](https://linux-hardware.org/?probe=0d809d54ad) | Dec 06, 2023 |
| HP            | ProBook 640 G5              | [419da197bb](https://linux-hardware.org/?probe=419da197bb) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | [745d537d97](https://linux-hardware.org/?probe=745d537d97) | Dec 05, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [48a8d668d9](https://linux-hardware.org/?probe=48a8d668d9) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2ace6b74e5](https://linux-hardware.org/?probe=2ace6b74e5) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | [b3bc756e27](https://linux-hardware.org/?probe=b3bc756e27) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | [9af224bc40](https://linux-hardware.org/?probe=9af224bc40) | Dec 04, 2023 |
| Acer          | Aspire A515-44G             | [7e41d52591](https://linux-hardware.org/?probe=7e41d52591) | Dec 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a63677b9e1](https://linux-hardware.org/?probe=a63677b9e1) | Dec 03, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [1b6b67ba62](https://linux-hardware.org/?probe=1b6b67ba62) | Dec 03, 2023 |
| MSI           | Modern 14 B4MW              | [69c3f996db](https://linux-hardware.org/?probe=69c3f996db) | Dec 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [5568b58564](https://linux-hardware.org/?probe=5568b58564) | Dec 02, 2023 |
| Dell          | Latitude E7240              | [e5ac912c4c](https://linux-hardware.org/?probe=e5ac912c4c) | Dec 02, 2023 |
| Notebook      | NJ50_70CU                   | [613d0fb4a0](https://linux-hardware.org/?probe=613d0fb4a0) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Dell          | Latitude E6420              | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [ea481bfb9d](https://linux-hardware.org/?probe=ea481bfb9d) | Dec 01, 2023 |
| HP            | 15 Notebook PC              | [b431f0a398](https://linux-hardware.org/?probe=b431f0a398) | Dec 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [863d4d2b8f](https://linux-hardware.org/?probe=863d4d2b8f) | Nov 30, 2023 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | [e52dad2488](https://linux-hardware.org/?probe=e52dad2488) | Nov 30, 2023 |
| Acer          | Aspire A314-22              | [d91455d676](https://linux-hardware.org/?probe=d91455d676) | Nov 30, 2023 |
| Apple         | MacBookPro11,1              | [21a183f050](https://linux-hardware.org/?probe=21a183f050) | Nov 30, 2023 |
| HP            | Victus by Gaming Laptop ... | [2f5a407d09](https://linux-hardware.org/?probe=2f5a407d09) | Nov 29, 2023 |
| Dell          | Latitude 5420               | [56ad64e87a](https://linux-hardware.org/?probe=56ad64e87a) | Nov 29, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | [f7d5f758c6](https://linux-hardware.org/?probe=f7d5f758c6) | Nov 29, 2023 |
| Dell          | Precision 3550              | [935b0dba56](https://linux-hardware.org/?probe=935b0dba56) | Nov 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [3531e02313](https://linux-hardware.org/?probe=3531e02313) | Nov 27, 2023 |
| Dell          | Precision M4700             | [e63ddd94ec](https://linux-hardware.org/?probe=e63ddd94ec) | Nov 27, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [abbb97fea2](https://linux-hardware.org/?probe=abbb97fea2) | Nov 27, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [0bc55c4101](https://linux-hardware.org/?probe=0bc55c4101) | Nov 27, 2023 |
| Apple         | MacBookPro8,1               | [b305057bc5](https://linux-hardware.org/?probe=b305057bc5) | Nov 27, 2023 |
| ASUSTek       | GL553VW                     | [dba63ed53c](https://linux-hardware.org/?probe=dba63ed53c) | Nov 26, 2023 |
| HP            | ProBook 4540s               | [6f65f2ceeb](https://linux-hardware.org/?probe=6f65f2ceeb) | Nov 26, 2023 |
| HP            | Pavilion 14                 | [af5d0c670a](https://linux-hardware.org/?probe=af5d0c670a) | Nov 26, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6007599bc5](https://linux-hardware.org/?probe=6007599bc5) | Nov 25, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [a2fbff15e7](https://linux-hardware.org/?probe=a2fbff15e7) | Nov 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [6f3cf47d7d](https://linux-hardware.org/?probe=6f3cf47d7d) | Nov 25, 2023 |
| Dell          | Studio XPS 1640             | [3b9a32eb3f](https://linux-hardware.org/?probe=3b9a32eb3f) | Nov 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [4515ea6be6](https://linux-hardware.org/?probe=4515ea6be6) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [4e7c1f967f](https://linux-hardware.org/?probe=4e7c1f967f) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [a886bd351a](https://linux-hardware.org/?probe=a886bd351a) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [386171f14d](https://linux-hardware.org/?probe=386171f14d) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [ac1dfd9609](https://linux-hardware.org/?probe=ac1dfd9609) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2c505c0b1e](https://linux-hardware.org/?probe=2c505c0b1e) | Nov 24, 2023 |
| Acer          | Swift SF314-41              | [23f539995b](https://linux-hardware.org/?probe=23f539995b) | Nov 24, 2023 |
| Dell          | Inspiron 1750               | [4d256b493c](https://linux-hardware.org/?probe=4d256b493c) | Nov 23, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [2127112b3a](https://linux-hardware.org/?probe=2127112b3a) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8416c7e558](https://linux-hardware.org/?probe=8416c7e558) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9aada56395](https://linux-hardware.org/?probe=9aada56395) | Nov 23, 2023 |
| Acer          | Aspire 5733                 | [7b6e215012](https://linux-hardware.org/?probe=7b6e215012) | Nov 22, 2023 |
| Acer          | Aspire A515-51              | [b8a36c00e8](https://linux-hardware.org/?probe=b8a36c00e8) | Nov 22, 2023 |
| Dell          | XPS 15 9530                 | [2720b6f6d4](https://linux-hardware.org/?probe=2720b6f6d4) | Nov 22, 2023 |
| MSI           | Prestige 15 A10SC           | [e1abb4721b](https://linux-hardware.org/?probe=e1abb4721b) | Nov 21, 2023 |
| Dell          | Inspiron 5547               | [d679a12a36](https://linux-hardware.org/?probe=d679a12a36) | Nov 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | [03d7d46dd0](https://linux-hardware.org/?probe=03d7d46dd0) | Nov 21, 2023 |
| Samsung       | RC530/RC730                 | [8d328f4394](https://linux-hardware.org/?probe=8d328f4394) | Nov 21, 2023 |
| Acer          | Aspire 5733                 | [348094cd98](https://linux-hardware.org/?probe=348094cd98) | Nov 21, 2023 |
| Lenovo        | ThinkPad Helix 3701CTO      | [f200cae4b1](https://linux-hardware.org/?probe=f200cae4b1) | Nov 20, 2023 |
| Dell          | Latitude E6330              | [3c6e547f2a](https://linux-hardware.org/?probe=3c6e547f2a) | Nov 19, 2023 |
| Notebook      | NS5x_NS7xPU                 | [7e047fc166](https://linux-hardware.org/?probe=7e047fc166) | Nov 19, 2023 |
| MSI           | GE76 Raider 11UE            | [9d0a216d82](https://linux-hardware.org/?probe=9d0a216d82) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [91f7d584f3](https://linux-hardware.org/?probe=91f7d584f3) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ef77e621d0](https://linux-hardware.org/?probe=ef77e621d0) | Nov 19, 2023 |
| MSI           | Cyborg 15 A12VF             | [fc41df67a4](https://linux-hardware.org/?probe=fc41df67a4) | Nov 19, 2023 |
| HP            | Victus by Gaming Laptop ... | [d086db0563](https://linux-hardware.org/?probe=d086db0563) | Nov 18, 2023 |
| Dell          | XPS 13 7390                 | [4735287055](https://linux-hardware.org/?probe=4735287055) | Nov 18, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| HP            | 250 G8 Notebook PC          | [a6d12193c7](https://linux-hardware.org/?probe=a6d12193c7) | Nov 17, 2023 |
| Dell          | Precision 5680              | [a2957d2ece](https://linux-hardware.org/?probe=a2957d2ece) | Nov 16, 2023 |
| Dell          | Precision 5680              | [2c6c6027a6](https://linux-hardware.org/?probe=2c6c6027a6) | Nov 16, 2023 |
| MSI           | Katana GF66 11UE            | [07a03ff43b](https://linux-hardware.org/?probe=07a03ff43b) | Nov 16, 2023 |
| Lenovo        | ThinkPad E550 20DF001HAU    | [44968b500c](https://linux-hardware.org/?probe=44968b500c) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fade86e55e](https://linux-hardware.org/?probe=fade86e55e) | Nov 16, 2023 |
| Apple         | MacBookPro8,1               | [68dbf5814b](https://linux-hardware.org/?probe=68dbf5814b) | Nov 15, 2023 |
| Notebook      | PA70Hx                      | [14799f850b](https://linux-hardware.org/?probe=14799f850b) | Nov 15, 2023 |
| HP            | ProBook 4540s               | [48705484f5](https://linux-hardware.org/?probe=48705484f5) | Nov 15, 2023 |
| Dell          | XPS 9320                    | [f0435ea4b7](https://linux-hardware.org/?probe=f0435ea4b7) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [386519f50c](https://linux-hardware.org/?probe=386519f50c) | Nov 15, 2023 |
| Acer          | Aspire V3-471G              | [f027c1d470](https://linux-hardware.org/?probe=f027c1d470) | Nov 14, 2023 |
| Dell          | XPS 15 7590                 | [da50e3550f](https://linux-hardware.org/?probe=da50e3550f) | Nov 14, 2023 |
| HP            | ProBook 4540s               | [f8e4ef7043](https://linux-hardware.org/?probe=f8e4ef7043) | Nov 14, 2023 |
| MSI           | Cyborg 15 A12VF             | [3cd966cd6a](https://linux-hardware.org/?probe=3cd966cd6a) | Nov 14, 2023 |
| System76      | Adder WS                    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| ASUSTek       | X55U                        | [04a09add31](https://linux-hardware.org/?probe=04a09add31) | Nov 13, 2023 |
| Dell          | Precision 7720              | [1f358e68ee](https://linux-hardware.org/?probe=1f358e68ee) | Nov 13, 2023 |
| Dell          | Precision 7720              | [facdc5c2a4](https://linux-hardware.org/?probe=facdc5c2a4) | Nov 13, 2023 |
| MSI           | GT70                        | [e2c0bb5bfe](https://linux-hardware.org/?probe=e2c0bb5bfe) | Nov 13, 2023 |
| HP            | Laptop 14-dq2xxx            | [e384b513f0](https://linux-hardware.org/?probe=e384b513f0) | Nov 13, 2023 |
| Unknown       | Unknown                     | [f9ee628d93](https://linux-hardware.org/?probe=f9ee628d93) | Nov 13, 2023 |
| System76      | Lemur Pro                   | [35e6e1214c](https://linux-hardware.org/?probe=35e6e1214c) | Nov 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b9ad1f18d8](https://linux-hardware.org/?probe=b9ad1f18d8) | Nov 12, 2023 |
| MSI           | Delta 15 A5EFK              | [091eaf746f](https://linux-hardware.org/?probe=091eaf746f) | Nov 12, 2023 |
| Google        | Edgar                       | [838bd73737](https://linux-hardware.org/?probe=838bd73737) | Nov 12, 2023 |
| Google        | Edgar                       | [42f8059f62](https://linux-hardware.org/?probe=42f8059f62) | Nov 11, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [1946d2a10c](https://linux-hardware.org/?probe=1946d2a10c) | Nov 11, 2023 |
| HP            | G42                         | [8a331f427d](https://linux-hardware.org/?probe=8a331f427d) | Nov 11, 2023 |
| Dell          | Inspiron 1525               | [d9b24edac8](https://linux-hardware.org/?probe=d9b24edac8) | Nov 11, 2023 |
| Dell          | Latitude E5420              | [ac31e56717](https://linux-hardware.org/?probe=ac31e56717) | Nov 11, 2023 |
| Notebook      | PA70Hx                      | [f22d74d5eb](https://linux-hardware.org/?probe=f22d74d5eb) | Nov 11, 2023 |
| HP            | Pavilion g7                 | [f963761c30](https://linux-hardware.org/?probe=f963761c30) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [0cacf99f8a](https://linux-hardware.org/?probe=0cacf99f8a) | Nov 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [93d7b2bcdc](https://linux-hardware.org/?probe=93d7b2bcdc) | Nov 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [0bb1ba6267](https://linux-hardware.org/?probe=0bb1ba6267) | Nov 09, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [03b4295585](https://linux-hardware.org/?probe=03b4295585) | Nov 09, 2023 |
| Dell          | Inspiron 1525               | [ab3577cc31](https://linux-hardware.org/?probe=ab3577cc31) | Nov 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b221326a48](https://linux-hardware.org/?probe=b221326a48) | Nov 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [c048c3b791](https://linux-hardware.org/?probe=c048c3b791) | Nov 09, 2023 |
| HP            | G42                         | [f440217af5](https://linux-hardware.org/?probe=f440217af5) | Nov 09, 2023 |
| Dell          | Precision 5520              | [1166f1d95d](https://linux-hardware.org/?probe=1166f1d95d) | Nov 08, 2023 |
| Dell          | Latitude E7270              | [0410c1ba06](https://linux-hardware.org/?probe=0410c1ba06) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [d2ce7f8ca6](https://linux-hardware.org/?probe=d2ce7f8ca6) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [e4f3bd771d](https://linux-hardware.org/?probe=e4f3bd771d) | Nov 08, 2023 |
| HONOR         | NBR-WAX9                    | [173692c48a](https://linux-hardware.org/?probe=173692c48a) | Nov 08, 2023 |
| Acer          | Aspire A517-51              | [9b0700130f](https://linux-hardware.org/?probe=9b0700130f) | Nov 08, 2023 |
| System76      | Lemur Pro                   | [92d1345459](https://linux-hardware.org/?probe=92d1345459) | Nov 07, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c28217d1ed](https://linux-hardware.org/?probe=c28217d1ed) | Nov 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9755c6bf31](https://linux-hardware.org/?probe=9755c6bf31) | Nov 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c2ae66ef2b](https://linux-hardware.org/?probe=c2ae66ef2b) | Nov 06, 2023 |
| Dell          | Vostro 5402                 | [2716ef5f71](https://linux-hardware.org/?probe=2716ef5f71) | Nov 06, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [7cc876dcfa](https://linux-hardware.org/?probe=7cc876dcfa) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [290be8911e](https://linux-hardware.org/?probe=290be8911e) | Nov 06, 2023 |
| Acer          | Aspire 5750G                | [a782c6c087](https://linux-hardware.org/?probe=a782c6c087) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| MSI           | Cyborg 15 A12VF             | [be39067306](https://linux-hardware.org/?probe=be39067306) | Nov 05, 2023 |
| ASUSTek       | G53SX                       | [7834b537a1](https://linux-hardware.org/?probe=7834b537a1) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Google        | Taeko                       | [d148b001d9](https://linux-hardware.org/?probe=d148b001d9) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| System76      | Lemur Pro                   | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [cfdf343144](https://linux-hardware.org/?probe=cfdf343144) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [237bd5cfb2](https://linux-hardware.org/?probe=237bd5cfb2) | Nov 04, 2023 |
| System76      | Lemur Pro                   | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| System76      | Oryx Pro                    | [ea89273272](https://linux-hardware.org/?probe=ea89273272) | Nov 04, 2023 |
| HP            | 655                         | [8cf9aa61c7](https://linux-hardware.org/?probe=8cf9aa61c7) | Nov 04, 2023 |
| Apple         | MacBookAir6,2               | [f8507f333d](https://linux-hardware.org/?probe=f8507f333d) | Nov 04, 2023 |
| MSI           | Bravo 15 C7VE               | [5db0e7314a](https://linux-hardware.org/?probe=5db0e7314a) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [972ef88623](https://linux-hardware.org/?probe=972ef88623) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [927b50091e](https://linux-hardware.org/?probe=927b50091e) | Nov 04, 2023 |
| System76      | Oryx Pro                    | [1704acc89b](https://linux-hardware.org/?probe=1704acc89b) | Nov 03, 2023 |
| Lenovo        | ThinkPad T420s 417032U      | [76247c39f4](https://linux-hardware.org/?probe=76247c39f4) | Nov 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3a8d337535](https://linux-hardware.org/?probe=3a8d337535) | Nov 03, 2023 |
| HP            | ProBook 6450b               | [75ad2cf5f8](https://linux-hardware.org/?probe=75ad2cf5f8) | Nov 02, 2023 |
| MSI           | Prestige 14Evo A11M         | [12414485a5](https://linux-hardware.org/?probe=12414485a5) | Nov 02, 2023 |
| Apple         | MacBookPro14,1              | [7d93bb6f25](https://linux-hardware.org/?probe=7d93bb6f25) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | [200e3255d9](https://linux-hardware.org/?probe=200e3255d9) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | [43a84b57f0](https://linux-hardware.org/?probe=43a84b57f0) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [dba91e5612](https://linux-hardware.org/?probe=dba91e5612) | Nov 01, 2023 |
| HP            | ENVY 15                     | [74dae44745](https://linux-hardware.org/?probe=74dae44745) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [c1e44a55c8](https://linux-hardware.org/?probe=c1e44a55c8) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [84ca0a285d](https://linux-hardware.org/?probe=84ca0a285d) | Nov 01, 2023 |
| Dell          | XPS 15 9520                 | [6b6da0ca4a](https://linux-hardware.org/?probe=6b6da0ca4a) | Nov 01, 2023 |
| System76      | Lemur Pro                   | [847ae1ea8d](https://linux-hardware.org/?probe=847ae1ea8d) | Nov 01, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [643c7ccd9b](https://linux-hardware.org/?probe=643c7ccd9b) | Nov 01, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [f08e4e21a0](https://linux-hardware.org/?probe=f08e4e21a0) | Nov 01, 2023 |
| HUAWEI        | CREF-XX                     | [a10aa3c3e5](https://linux-hardware.org/?probe=a10aa3c3e5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | [cb013304f5](https://linux-hardware.org/?probe=cb013304f5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | [d6ac483e43](https://linux-hardware.org/?probe=d6ac483e43) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | [ee528fce07](https://linux-hardware.org/?probe=ee528fce07) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | [4e0042e20c](https://linux-hardware.org/?probe=4e0042e20c) | Oct 31, 2023 |
| Acer          | Aspire E5-553G              | [7c76f143a4](https://linux-hardware.org/?probe=7c76f143a4) | Oct 31, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [56f24de5ff](https://linux-hardware.org/?probe=56f24de5ff) | Oct 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [81a7cabe4f](https://linux-hardware.org/?probe=81a7cabe4f) | Oct 30, 2023 |
| HP            | Dev One Notebook PC         | [d5ace42b13](https://linux-hardware.org/?probe=d5ace42b13) | Oct 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [d51c491524](https://linux-hardware.org/?probe=d51c491524) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| System76      | Adder WS                    | [57478f4561](https://linux-hardware.org/?probe=57478f4561) | Oct 30, 2023 |
| System76      | Adder WS                    | [a10fcac3f4](https://linux-hardware.org/?probe=a10fcac3f4) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [5863bd6189](https://linux-hardware.org/?probe=5863bd6189) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [7301c9b3df](https://linux-hardware.org/?probe=7301c9b3df) | Oct 29, 2023 |
| Apple         | MacBookPro5,5               | [2815a5477f](https://linux-hardware.org/?probe=2815a5477f) | Oct 29, 2023 |
| SLIMBOOK      | TITAN                       | [8697e4de09](https://linux-hardware.org/?probe=8697e4de09) | Oct 29, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [c90dd43290](https://linux-hardware.org/?probe=c90dd43290) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d621a72336](https://linux-hardware.org/?probe=d621a72336) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [57e3abc23d](https://linux-hardware.org/?probe=57e3abc23d) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0f9adbc34d](https://linux-hardware.org/?probe=0f9adbc34d) | Oct 28, 2023 |
| Maibenben     | MaiBook X series            | [63e0cb487a](https://linux-hardware.org/?probe=63e0cb487a) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| Lenovo        | Z50-70 20354                | [2e5ee0032d](https://linux-hardware.org/?probe=2e5ee0032d) | Oct 27, 2023 |
| System76      | Lemur Pro                   | [e5b2c76907](https://linux-hardware.org/?probe=e5b2c76907) | Oct 27, 2023 |
| Samsung       | 550XCJ/550XCR               | [9d34ff8710](https://linux-hardware.org/?probe=9d34ff8710) | Oct 27, 2023 |
| System76      | Darter Pro                  | [9dcbc85a23](https://linux-hardware.org/?probe=9dcbc85a23) | Oct 27, 2023 |
| HP            | OMEN LAPTOP - 15-EK0013D... | [0c582fd597](https://linux-hardware.org/?probe=0c582fd597) | Oct 27, 2023 |
| Acer          | Aspire A315-42G             | [114e1e6d66](https://linux-hardware.org/?probe=114e1e6d66) | Oct 27, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f0641b8822](https://linux-hardware.org/?probe=f0641b8822) | Oct 26, 2023 |
| Haier         | U1520SD                     | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Dell          | Latitude E6530              | [ec57b86fe6](https://linux-hardware.org/?probe=ec57b86fe6) | Oct 26, 2023 |
| Acer          | Aspire VN7-793G             | [e4a7d4f368](https://linux-hardware.org/?probe=e4a7d4f368) | Oct 26, 2023 |
| Panasonic     | CF-31SBM08DM                | [820f042ba6](https://linux-hardware.org/?probe=820f042ba6) | Oct 26, 2023 |
| Haier         | U1520SD                     | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Dell          | Inspiron 3442               | [7fc2a154e5](https://linux-hardware.org/?probe=7fc2a154e5) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [9a4561dabf](https://linux-hardware.org/?probe=9a4561dabf) | Oct 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [ecde45a506](https://linux-hardware.org/?probe=ecde45a506) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Dell          | Latitude E7240              | [6fead70e93](https://linux-hardware.org/?probe=6fead70e93) | Oct 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [47fdb21256](https://linux-hardware.org/?probe=47fdb21256) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | [7e9d761b35](https://linux-hardware.org/?probe=7e9d761b35) | Oct 23, 2023 |
| MSI           | Sword 15 A11UD              | [d07a7c777c](https://linux-hardware.org/?probe=d07a7c777c) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | [73c1b49eab](https://linux-hardware.org/?probe=73c1b49eab) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | [b6169d3a96](https://linux-hardware.org/?probe=b6169d3a96) | Oct 23, 2023 |
| ASUSTek       | G750JW                      | [9bafdb8250](https://linux-hardware.org/?probe=9bafdb8250) | Oct 22, 2023 |
| Dell          | Latitude 5520               | [f5664b02d2](https://linux-hardware.org/?probe=f5664b02d2) | Oct 22, 2023 |
| Toshiba       | Satellite C70D-B            | [7f1637fdb9](https://linux-hardware.org/?probe=7f1637fdb9) | Oct 22, 2023 |
| ASUSTek       | G53SX                       | [d19756d24b](https://linux-hardware.org/?probe=d19756d24b) | Oct 22, 2023 |
| Acer          | Aspire A315-23              | [14ed4adf6c](https://linux-hardware.org/?probe=14ed4adf6c) | Oct 22, 2023 |
| EUROCOM       | Tornado F5                  | [3056eeecf5](https://linux-hardware.org/?probe=3056eeecf5) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | [010dd78352](https://linux-hardware.org/?probe=010dd78352) | Oct 21, 2023 |
| EUROCOM       | Tornado F5                  | [25b7095754](https://linux-hardware.org/?probe=25b7095754) | Oct 21, 2023 |
| MSI           | Cyborg 15 A12VF             | [b1a3bf1a75](https://linux-hardware.org/?probe=b1a3bf1a75) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [97d1264314](https://linux-hardware.org/?probe=97d1264314) | Oct 21, 2023 |
| HONOR         | NBR-WAX9                    | [5966a36809](https://linux-hardware.org/?probe=5966a36809) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [148be53a91](https://linux-hardware.org/?probe=148be53a91) | Oct 20, 2023 |
| Toshiba       | Satellite C70D-B            | [793d71f1d2](https://linux-hardware.org/?probe=793d71f1d2) | Oct 20, 2023 |
| Lenovo        | Y50-70 20378                | [e51b067a88](https://linux-hardware.org/?probe=e51b067a88) | Oct 20, 2023 |
| Acer          | Swift SFX14-51G             | [2adde1171a](https://linux-hardware.org/?probe=2adde1171a) | Oct 20, 2023 |
| ASUSTek       | X551MA                      | [6ee41b351a](https://linux-hardware.org/?probe=6ee41b351a) | Oct 20, 2023 |
| Acer          | Aspire 5253                 | [871f28b131](https://linux-hardware.org/?probe=871f28b131) | Oct 20, 2023 |
| Dell          | Latitude 5520               | [281fdb7e86](https://linux-hardware.org/?probe=281fdb7e86) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [36613b2f1f](https://linux-hardware.org/?probe=36613b2f1f) | Oct 19, 2023 |
| MSI           | Cyborg 15 A12VF             | [7fab57f39a](https://linux-hardware.org/?probe=7fab57f39a) | Oct 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [4312e9a007](https://linux-hardware.org/?probe=4312e9a007) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [2f2d05a226](https://linux-hardware.org/?probe=2f2d05a226) | Oct 19, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | [b2cba37968](https://linux-hardware.org/?probe=b2cba37968) | Oct 19, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | [cd80438b02](https://linux-hardware.org/?probe=cd80438b02) | Oct 19, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [315376a82a](https://linux-hardware.org/?probe=315376a82a) | Oct 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| System76      | Gazelle                     | [061012cdb0](https://linux-hardware.org/?probe=061012cdb0) | Oct 17, 2023 |
| Apple         | MacBookPro11,1              | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| HP            | 250 G4                      | [a45d8a13df](https://linux-hardware.org/?probe=a45d8a13df) | Oct 16, 2023 |
| HP            | Laptop 15-dw4xxx            | [44ba7f4015](https://linux-hardware.org/?probe=44ba7f4015) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| ASUSTek       | N551ZU                      | [e56a6c7957](https://linux-hardware.org/?probe=e56a6c7957) | Oct 16, 2023 |
| HP            | ProBook 4730s               | [42a7295a49](https://linux-hardware.org/?probe=42a7295a49) | Oct 15, 2023 |
| MECHREVO      | WUJIE14 PRO                 | [40cfeec2b2](https://linux-hardware.org/?probe=40cfeec2b2) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [7a732e8a25](https://linux-hardware.org/?probe=7a732e8a25) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [22b5b65e16](https://linux-hardware.org/?probe=22b5b65e16) | Oct 15, 2023 |
| System76      | Lemur Pro                   | [f969d7a459](https://linux-hardware.org/?probe=f969d7a459) | Oct 15, 2023 |
| Acer          | Aspire A314-23P             | [142bc36a3f](https://linux-hardware.org/?probe=142bc36a3f) | Oct 14, 2023 |
| Notebook      | P9XXEN_EF_ED                | [89eae06fc2](https://linux-hardware.org/?probe=89eae06fc2) | Oct 13, 2023 |
| Acer          | Aspire E1-571               | [94754c98ce](https://linux-hardware.org/?probe=94754c98ce) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| Dell          | Inspiron 16 7610            | [ee849775df](https://linux-hardware.org/?probe=ee849775df) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| Gateway       | NE570                       | [533fec5226](https://linux-hardware.org/?probe=533fec5226) | Oct 11, 2023 |
| Acer          | Predator PH315-54           | [552e952ebe](https://linux-hardware.org/?probe=552e952ebe) | Oct 11, 2023 |
| Acer          | Aspire A515-44G             | [58d145f207](https://linux-hardware.org/?probe=58d145f207) | Oct 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [7d7f268cec](https://linux-hardware.org/?probe=7d7f268cec) | Oct 11, 2023 |
| Dell          | Inspiron 15 3525            | [66bd7ea744](https://linux-hardware.org/?probe=66bd7ea744) | Oct 10, 2023 |
| Lenovo        | ThinkPad P1 20MES05502      | [869264ad64](https://linux-hardware.org/?probe=869264ad64) | Oct 10, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [5d606c8b1c](https://linux-hardware.org/?probe=5d606c8b1c) | Oct 10, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6591296a12](https://linux-hardware.org/?probe=6591296a12) | Oct 10, 2023 |
| Gigabyte      | AORUS 17H BXF               | [4fcbae7a75](https://linux-hardware.org/?probe=4fcbae7a75) | Oct 10, 2023 |
| System76      | Darter Pro                  | [71e1a67b2a](https://linux-hardware.org/?probe=71e1a67b2a) | Oct 10, 2023 |
| Razer         | Blade                       | [22de5dfe50](https://linux-hardware.org/?probe=22de5dfe50) | Oct 09, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | [420f5d5de9](https://linux-hardware.org/?probe=420f5d5de9) | Oct 09, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [63cbb26f44](https://linux-hardware.org/?probe=63cbb26f44) | Oct 08, 2023 |
| Dell          | Inspiron 7375               | [3b54f5530b](https://linux-hardware.org/?probe=3b54f5530b) | Oct 08, 2023 |
| System76      | Serval WS                   | [509cc872ee](https://linux-hardware.org/?probe=509cc872ee) | Oct 07, 2023 |
| Alienware     | m15 R7                      | [7bd2b6300f](https://linux-hardware.org/?probe=7bd2b6300f) | Oct 07, 2023 |
| HP            | EliteBook 850 G3            | [f773c3004e](https://linux-hardware.org/?probe=f773c3004e) | Oct 07, 2023 |
| HP            | ProBook 6450b               | [70e33902c1](https://linux-hardware.org/?probe=70e33902c1) | Oct 07, 2023 |
| HP            | ProBook 6450b               | [ddd8417a28](https://linux-hardware.org/?probe=ddd8417a28) | Oct 07, 2023 |
| MSI           | GE62 2QF                    | [cd73adb01d](https://linux-hardware.org/?probe=cd73adb01d) | Oct 07, 2023 |
| HP            | Laptop 15-db1xxx            | [687a37a00f](https://linux-hardware.org/?probe=687a37a00f) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | [f4c0266602](https://linux-hardware.org/?probe=f4c0266602) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | [8978850a77](https://linux-hardware.org/?probe=8978850a77) | Oct 06, 2023 |
| System76      | Serval WS                   | [f8e3cd9fd0](https://linux-hardware.org/?probe=f8e3cd9fd0) | Oct 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [b6caf35101](https://linux-hardware.org/?probe=b6caf35101) | Oct 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3e6f44ce5c](https://linux-hardware.org/?probe=3e6f44ce5c) | Oct 05, 2023 |
| Google        | Morphius                    | [735ed70d9c](https://linux-hardware.org/?probe=735ed70d9c) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [34ff66e3a9](https://linux-hardware.org/?probe=34ff66e3a9) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [314a6f2edf](https://linux-hardware.org/?probe=314a6f2edf) | Oct 05, 2023 |
| Dell          | Inspiron 5490               | [5ab40107ce](https://linux-hardware.org/?probe=5ab40107ce) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [234f939987](https://linux-hardware.org/?probe=234f939987) | Oct 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [1dcdef2d17](https://linux-hardware.org/?probe=1dcdef2d17) | Oct 04, 2023 |
| Dell          | Latitude 7400               | [bd6eee3b51](https://linux-hardware.org/?probe=bd6eee3b51) | Oct 03, 2023 |
| Apple         | MacBookAir6,2               | [23c850d9d3](https://linux-hardware.org/?probe=23c850d9d3) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| MSI           | GF65 Thin 9SEXR             | [1d315fb87d](https://linux-hardware.org/?probe=1d315fb87d) | Oct 02, 2023 |
| Dell          | Inspiron 5437               | [a348906862](https://linux-hardware.org/?probe=a348906862) | Oct 02, 2023 |
| Dell          | Inspiron 3543               | [1c681f7a14](https://linux-hardware.org/?probe=1c681f7a14) | Oct 02, 2023 |
| ASUSTek       | G74Sx                       | [2e57173dd9](https://linux-hardware.org/?probe=2e57173dd9) | Oct 02, 2023 |
| System76      | Lemur Pro                   | [8486fb3080](https://linux-hardware.org/?probe=8486fb3080) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [3bb0e0c792](https://linux-hardware.org/?probe=3bb0e0c792) | Oct 01, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| HP            | 250 G4                      | [30947c6039](https://linux-hardware.org/?probe=30947c6039) | Oct 01, 2023 |
| MSI           | Cyborg 15 A12VF             | [5f76307503](https://linux-hardware.org/?probe=5f76307503) | Oct 01, 2023 |
| Dell          | Latitude E7440              | [8e74ff2f99](https://linux-hardware.org/?probe=8e74ff2f99) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [12d98aba86](https://linux-hardware.org/?probe=12d98aba86) | Oct 01, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [8fabc36e1c](https://linux-hardware.org/?probe=8fabc36e1c) | Oct 01, 2023 |
| Apple         | MacBookPro7,1               | [c69ebf2472](https://linux-hardware.org/?probe=c69ebf2472) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| Positivo      | C14CR01                     | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| System76      | Darter Pro                  | [d8b78103d5](https://linux-hardware.org/?probe=d8b78103d5) | Sep 29, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire E5-575G              | [109490039d](https://linux-hardware.org/?probe=109490039d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| Toshiba       | Satellite P775              | [7269165fd9](https://linux-hardware.org/?probe=7269165fd9) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| System76      | Oryx Pro                    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Acer          | Aspire VN7-791G             | [0cfe515d00](https://linux-hardware.org/?probe=0cfe515d00) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [7c13a64c8a](https://linux-hardware.org/?probe=7c13a64c8a) | Sep 27, 2023 |
| Dell          | Latitude 5480               | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| System76      | Lemur Pro                   | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [d9665a6ffd](https://linux-hardware.org/?probe=d9665a6ffd) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | [5fa9f0dde2](https://linux-hardware.org/?probe=5fa9f0dde2) | Sep 26, 2023 |
| HUAWEI        | NbDE-WXX9                   | [b3990570ee](https://linux-hardware.org/?probe=b3990570ee) | Sep 25, 2023 |
| HP            | 250 G4                      | [6e475cbb1f](https://linux-hardware.org/?probe=6e475cbb1f) | Sep 25, 2023 |
| HP            | 250 G4                      | [9543354fea](https://linux-hardware.org/?probe=9543354fea) | Sep 25, 2023 |
| Acer          | Swift SFX14-41G             | [ae755aa7e3](https://linux-hardware.org/?probe=ae755aa7e3) | Sep 25, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [cb2b1325cc](https://linux-hardware.org/?probe=cb2b1325cc) | Sep 25, 2023 |
| MSI           | Cyborg 15 A12VF             | [f934062b23](https://linux-hardware.org/?probe=f934062b23) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7d18eb441e](https://linux-hardware.org/?probe=7d18eb441e) | Sep 24, 2023 |
| Fujitsu       | LIFEBOOK A557               | [e66c8c9ca7](https://linux-hardware.org/?probe=e66c8c9ca7) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [dfe5d4faaa](https://linux-hardware.org/?probe=dfe5d4faaa) | Sep 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8318fdeb5b](https://linux-hardware.org/?probe=8318fdeb5b) | Sep 24, 2023 |
| Dell          | System XPS L502X            | [22d93fe76c](https://linux-hardware.org/?probe=22d93fe76c) | Sep 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [7aa2ea2853](https://linux-hardware.org/?probe=7aa2ea2853) | Sep 24, 2023 |
| Dell          | System XPS L502X            | [a1d4f683c1](https://linux-hardware.org/?probe=a1d4f683c1) | Sep 24, 2023 |
| Acer          | Swift SFX14-41G             | [7980181fcb](https://linux-hardware.org/?probe=7980181fcb) | Sep 24, 2023 |
| Dell          | XPS 15 9520                 | [b358b656c6](https://linux-hardware.org/?probe=b358b656c6) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| HP            | 250 G4                      | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| System76      | Gazelle                     | [2e31a65d58](https://linux-hardware.org/?probe=2e31a65d58) | Sep 23, 2023 |
| HP            | Laptop 15-db1xxx            | [8b16720f22](https://linux-hardware.org/?probe=8b16720f22) | Sep 23, 2023 |
| Dell          | Vostro 5481                 | [c416e12adb](https://linux-hardware.org/?probe=c416e12adb) | Sep 22, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [2a6c2ef738](https://linux-hardware.org/?probe=2a6c2ef738) | Sep 22, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [726a5f4cf5](https://linux-hardware.org/?probe=726a5f4cf5) | Sep 22, 2023 |
| HUAWEI        | KPL-W0X                     | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| HP            | Laptop 15-db1xxx            | [504ed03ead](https://linux-hardware.org/?probe=504ed03ead) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Notebook      | NH50_70RH                   | [57070abf3c](https://linux-hardware.org/?probe=57070abf3c) | Sep 21, 2023 |
| System76      | Darter Pro                  | [3266f46a3b](https://linux-hardware.org/?probe=3266f46a3b) | Sep 20, 2023 |
| Dell          | Precision 5680              | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [cbc4ec2df0](https://linux-hardware.org/?probe=cbc4ec2df0) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a8b35a2b8f](https://linux-hardware.org/?probe=a8b35a2b8f) | Sep 19, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| Framework     | Laptop                      | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| HP            | Pavilion 15                 | [eb15fe383c](https://linux-hardware.org/?probe=eb15fe383c) | Sep 18, 2023 |
| HP            | Pavilion 15                 | [fb86634643](https://linux-hardware.org/?probe=fb86634643) | Sep 18, 2023 |
| HP            | Dev One Notebook PC         | [2606a8d1c1](https://linux-hardware.org/?probe=2606a8d1c1) | Sep 17, 2023 |
| HONOR         | BMH-WCX9                    | [96a8945a17](https://linux-hardware.org/?probe=96a8945a17) | Sep 17, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [797e19424f](https://linux-hardware.org/?probe=797e19424f) | Sep 16, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [35bc7480cb](https://linux-hardware.org/?probe=35bc7480cb) | Sep 15, 2023 |
| Unknown       | Unknown                     | [ae1fde8210](https://linux-hardware.org/?probe=ae1fde8210) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [98dbf213e7](https://linux-hardware.org/?probe=98dbf213e7) | Sep 15, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [5150bae6bd](https://linux-hardware.org/?probe=5150bae6bd) | Sep 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [175e57d54f](https://linux-hardware.org/?probe=175e57d54f) | Sep 15, 2023 |
| Digibras      | CL341                       | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [4f6e19f508](https://linux-hardware.org/?probe=4f6e19f508) | Sep 14, 2023 |
| ASUSTek       | X556URK                     | [0996de9eac](https://linux-hardware.org/?probe=0996de9eac) | Sep 14, 2023 |
| Dell          | Latitude 7440               | [cd8e3aa6ed](https://linux-hardware.org/?probe=cd8e3aa6ed) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| System76      | Pangolin                    | [c3803d0977](https://linux-hardware.org/?probe=c3803d0977) | Sep 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [ef5a6433f3](https://linux-hardware.org/?probe=ef5a6433f3) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | [c159157024](https://linux-hardware.org/?probe=c159157024) | Sep 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | [8f9ada75e9](https://linux-hardware.org/?probe=8f9ada75e9) | Sep 11, 2023 |
| Dell          | Latitude E7250              | [44983ff513](https://linux-hardware.org/?probe=44983ff513) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [1b2d76894b](https://linux-hardware.org/?probe=1b2d76894b) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5fc227a0e8](https://linux-hardware.org/?probe=5fc227a0e8) | Sep 08, 2023 |
| Dell          | Vostro 5502                 | [a131efa36e](https://linux-hardware.org/?probe=a131efa36e) | Sep 08, 2023 |
| HP            | Laptop 14-dk0xxx            | [57b82728d8](https://linux-hardware.org/?probe=57b82728d8) | Sep 08, 2023 |
| HP            | EliteBook 745 G5            | [05d61b5c23](https://linux-hardware.org/?probe=05d61b5c23) | Sep 08, 2023 |
| MSI           | P65 Creator 8RD             | [3eab920cfc](https://linux-hardware.org/?probe=3eab920cfc) | Sep 07, 2023 |
| HP            | Laptop 15-dy2xxx            | [eae373ebd4](https://linux-hardware.org/?probe=eae373ebd4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| HP            | EliteBook 8760w             | [d061b57b29](https://linux-hardware.org/?probe=d061b57b29) | Sep 07, 2023 |
| Alienware     | m15 R7                      | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| Apple         | MacBookPro11,3              | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | [611bb4fe1a](https://linux-hardware.org/?probe=611bb4fe1a) | Sep 06, 2023 |
| Acer          | Swift SFX14-41G             | [38f9d1abd9](https://linux-hardware.org/?probe=38f9d1abd9) | Sep 05, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [27575898fe](https://linux-hardware.org/?probe=27575898fe) | Sep 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Apple         | MacBookPro10,1              | [11c016fb1b](https://linux-hardware.org/?probe=11c016fb1b) | Sep 05, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| System76      | Lemur Pro                   | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [68e90ee0cb](https://linux-hardware.org/?probe=68e90ee0cb) | Sep 04, 2023 |
| ASUSTek       | K53E                        | [5604fe515d](https://linux-hardware.org/?probe=5604fe515d) | Sep 04, 2023 |
| Dell          | XPS 17 9700                 | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [515e1f4bce](https://linux-hardware.org/?probe=515e1f4bce) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| Acer          | Swift SFX14-41G             | [67f553625a](https://linux-hardware.org/?probe=67f553625a) | Sep 01, 2023 |
| Dell          | Latitude E7470              | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [1213d3bf46](https://linux-hardware.org/?probe=1213d3bf46) | Aug 31, 2023 |
| Acer          | Aspire E5-551G              | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [3b890e064f](https://linux-hardware.org/?probe=3b890e064f) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| Google        | Kefka                       | [284517c2b3](https://linux-hardware.org/?probe=284517c2b3) | Aug 31, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Google        | Kefka                       | [a018ae3fb5](https://linux-hardware.org/?probe=a018ae3fb5) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [90a72df8ef](https://linux-hardware.org/?probe=90a72df8ef) | Aug 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [481b37b0fc](https://linux-hardware.org/?probe=481b37b0fc) | Aug 29, 2023 |
| Dell          | Latitude 5330               | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [2f669d797f](https://linux-hardware.org/?probe=2f669d797f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [39f2feeed5](https://linux-hardware.org/?probe=39f2feeed5) | Aug 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | [ef97f75590](https://linux-hardware.org/?probe=ef97f75590) | Aug 28, 2023 |
| Dell          | Precision 5510              | [c6d08d9c28](https://linux-hardware.org/?probe=c6d08d9c28) | Aug 27, 2023 |
| HP            | EliteBook 865 16 inch G9... | [b07775a194](https://linux-hardware.org/?probe=b07775a194) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Precision M4600             | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Apple         | MacBookPro8,2               | [9e0b5b0b7e](https://linux-hardware.org/?probe=9e0b5b0b7e) | Aug 26, 2023 |
| Dell          | Precision M6800             | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| HP            | ProBook 4730s               | [32f610b810](https://linux-hardware.org/?probe=32f610b810) | Aug 26, 2023 |
| Google        | Kasumi                      | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| System76      | Gazelle                     | [b3fb438915](https://linux-hardware.org/?probe=b3fb438915) | Aug 25, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [e2e304c9eb](https://linux-hardware.org/?probe=e2e304c9eb) | Aug 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | [34fc2a5f83](https://linux-hardware.org/?probe=34fc2a5f83) | Aug 24, 2023 |
| Dell          | Latitude E7240              | [cb61859037](https://linux-hardware.org/?probe=cb61859037) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Dell          | Latitude 7430               | [7daf0301c5](https://linux-hardware.org/?probe=7daf0301c5) | Aug 24, 2023 |
| Toshiba       | Satellite L655              | [18df557333](https://linux-hardware.org/?probe=18df557333) | Aug 24, 2023 |
| HP            | Pavilion Notebook           | [b0ca2ee250](https://linux-hardware.org/?probe=b0ca2ee250) | Aug 23, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [50f079ae44](https://linux-hardware.org/?probe=50f079ae44) | Aug 23, 2023 |
| Dell          | XPS 13 9310                 | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| Samsung       | 750TDA                      | [7b1ec96afa](https://linux-hardware.org/?probe=7b1ec96afa) | Aug 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [4cd19df49e](https://linux-hardware.org/?probe=4cd19df49e) | Aug 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [fdd24243bf](https://linux-hardware.org/?probe=fdd24243bf) | Aug 22, 2023 |
| Acer          | Aspire A715-75G             | [54794fb9e8](https://linux-hardware.org/?probe=54794fb9e8) | Aug 22, 2023 |
| HP            | ProBook 4730s               | [5b4d88bc67](https://linux-hardware.org/?probe=5b4d88bc67) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| System76      | Oryx Pro                    | [b7e0bd11e5](https://linux-hardware.org/?probe=b7e0bd11e5) | Aug 20, 2023 |
| Dell          | Precision 5520              | [42587aac96](https://linux-hardware.org/?probe=42587aac96) | Aug 20, 2023 |
| Dell          | Precision 5520              | [bec735d800](https://linux-hardware.org/?probe=bec735d800) | Aug 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR    | [5d063a6e59](https://linux-hardware.org/?probe=5d063a6e59) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [a1ab007f7f](https://linux-hardware.org/?probe=a1ab007f7f) | Aug 18, 2023 |
| ASUSTek       | U38N                        | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| HP            | EliteBook 850 G3            | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| Dell          | XPS 13 9310                 | [680fae2274](https://linux-hardware.org/?probe=680fae2274) | Aug 17, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [43fd1aad67](https://linux-hardware.org/?probe=43fd1aad67) | Aug 17, 2023 |
| System76      | Lemur Pro                   | [af3b387574](https://linux-hardware.org/?probe=af3b387574) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Apple         | MacBookAir6,2               | [431ac1b880](https://linux-hardware.org/?probe=431ac1b880) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| System76      | Galago Pro                  | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Apple         | MacBookPro9,2               | [61ff7ac5f1](https://linux-hardware.org/?probe=61ff7ac5f1) | Aug 14, 2023 |
| Apple         | MacBookPro16,1              | [18b513f5f0](https://linux-hardware.org/?probe=18b513f5f0) | Aug 14, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1f27d0f994](https://linux-hardware.org/?probe=1f27d0f994) | Aug 14, 2023 |
| HP            | ProBook 4540s               | [84dbf6b759](https://linux-hardware.org/?probe=84dbf6b759) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| GPU Compan... | GWNR71517                   | [a38cee5cc9](https://linux-hardware.org/?probe=a38cee5cc9) | Aug 12, 2023 |
| Acer          | Aspire ES1-520              | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| Dell          | G7 7588                     | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [f46a14b981](https://linux-hardware.org/?probe=f46a14b981) | Aug 12, 2023 |
| HP            | EliteBook 820 G3            | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [0d45e9e048](https://linux-hardware.org/?probe=0d45e9e048) | Aug 12, 2023 |
| Dell          | Precision M4600             | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [361e073b5c](https://linux-hardware.org/?probe=361e073b5c) | Aug 11, 2023 |
| Acer          | Nitro AN715-51              | [ea972c8686](https://linux-hardware.org/?probe=ea972c8686) | Aug 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e22f71b79d](https://linux-hardware.org/?probe=e22f71b79d) | Aug 11, 2023 |
| ASUSTek       | X751LD                      | [e98d8d116d](https://linux-hardware.org/?probe=e98d8d116d) | Aug 10, 2023 |
| Apple         | MacBookAir5,2               | [7f91d6f9d8](https://linux-hardware.org/?probe=7f91d6f9d8) | Aug 10, 2023 |
| Acer          | Nitro AN517-55              | [b77ff095f8](https://linux-hardware.org/?probe=b77ff095f8) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [5c854bed9f](https://linux-hardware.org/?probe=5c854bed9f) | Aug 09, 2023 |
| HP            | ProBook 4330s               | [d23ce497d2](https://linux-hardware.org/?probe=d23ce497d2) | Aug 09, 2023 |
| System76      | Darter Pro                  | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| MSI           | Cyborg 15 A12VF             | [b041192310](https://linux-hardware.org/?probe=b041192310) | Aug 09, 2023 |
| Alienware     | 14                          | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| HP            | Victus by 15.6 inch Gami... | [67f88ab571](https://linux-hardware.org/?probe=67f88ab571) | Aug 08, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [afa081b440](https://linux-hardware.org/?probe=afa081b440) | Aug 08, 2023 |
| Acer          | Ferrari One 200             | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | [00b169d241](https://linux-hardware.org/?probe=00b169d241) | Aug 08, 2023 |
| Apple         | MacBookPro11,3              | [c415fd317b](https://linux-hardware.org/?probe=c415fd317b) | Aug 08, 2023 |
| Apple         | MacBookPro10,1              | [5e0c7f7bfc](https://linux-hardware.org/?probe=5e0c7f7bfc) | Aug 08, 2023 |
| Acer          | Aspire A715-75G             | [57f1225daf](https://linux-hardware.org/?probe=57f1225daf) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| System76      | Oryx Pro                    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| MSI           | Cyborg 15 A12VF             | [5fe9a17769](https://linux-hardware.org/?probe=5fe9a17769) | Aug 07, 2023 |
| MSI           | GP72 7RDX                   | [43eb53850c](https://linux-hardware.org/?probe=43eb53850c) | Aug 06, 2023 |
| Clevo         | W150HRM                     | [1ddcfcbecc](https://linux-hardware.org/?probe=1ddcfcbecc) | Aug 06, 2023 |
| Apple         | MacBookPro9,2               | [16936ef482](https://linux-hardware.org/?probe=16936ef482) | Aug 06, 2023 |
| MSI           | GP72 7RDX                   | [6d2bc8aa9e](https://linux-hardware.org/?probe=6d2bc8aa9e) | Aug 06, 2023 |
| Timi          | RedmiBook Pro 15S           | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| Notebook      | 1745                        | [3561a5dbbe](https://linux-hardware.org/?probe=3561a5dbbe) | Aug 06, 2023 |
| HP            | Pavilion dm4                | [521b8518ed](https://linux-hardware.org/?probe=521b8518ed) | Aug 06, 2023 |
| Dell          | Latitude 5430               | [f63444b0be](https://linux-hardware.org/?probe=f63444b0be) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [7d17fc9ff6](https://linux-hardware.org/?probe=7d17fc9ff6) | Aug 05, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| HP            | ProBook 650 G1              | [286cc8b0dd](https://linux-hardware.org/?probe=286cc8b0dd) | Aug 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0GY0R    | [4d618e08b3](https://linux-hardware.org/?probe=4d618e08b3) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| Dell          | XPS 13 9370                 | [cf49ff3004](https://linux-hardware.org/?probe=cf49ff3004) | Aug 03, 2023 |
| Dell          | Latitude E7240              | [ec5ec88e59](https://linux-hardware.org/?probe=ec5ec88e59) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [99ccd043cb](https://linux-hardware.org/?probe=99ccd043cb) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d4e267a214](https://linux-hardware.org/?probe=d4e267a214) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| Apple         | MacBookPro11,3              | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [0a3c5e5c4d](https://linux-hardware.org/?probe=0a3c5e5c4d) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [9f852ea211](https://linux-hardware.org/?probe=9f852ea211) | Aug 02, 2023 |
| ASUSTek       | GL502VSK                    | [0ed7feaa05](https://linux-hardware.org/?probe=0ed7feaa05) | Aug 01, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3500               | [df5211a816](https://linux-hardware.org/?probe=df5211a816) | Aug 01, 2023 |
| Dell          | Latitude 5490               | [e24a9f877c](https://linux-hardware.org/?probe=e24a9f877c) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| MSI           | Katana GF66 12UC            | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| ASUSTek       | K95VM                       | [1ec08c4cf9](https://linux-hardware.org/?probe=1ec08c4cf9) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Dell          | Latitude E7440              | [7509a5f756](https://linux-hardware.org/?probe=7509a5f756) | Jul 30, 2023 |
| System76      | Darter Pro                  | [0220d19f38](https://linux-hardware.org/?probe=0220d19f38) | Jul 30, 2023 |
| Dell          | Latitude E7240              | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| HP            | Pavilion 11 x360 PC         | [d693783e7a](https://linux-hardware.org/?probe=d693783e7a) | Jul 29, 2023 |
| Unknown       | Unknown                     | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [59f0eb6b57](https://linux-hardware.org/?probe=59f0eb6b57) | Jul 28, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [cb2f78abf0](https://linux-hardware.org/?probe=cb2f78abf0) | Jul 28, 2023 |
| Dell          | Precision 3550              | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| System76      | Oryx Pro                    | [0ad8c1d8a7](https://linux-hardware.org/?probe=0ad8c1d8a7) | Jul 28, 2023 |
| Acer          | Aspire A315-42G             | [0e3aa83494](https://linux-hardware.org/?probe=0e3aa83494) | Jul 28, 2023 |
| HP            | EliteBook 840 G3            | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Dell          | G15 5520                    | [7a5b503737](https://linux-hardware.org/?probe=7a5b503737) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| Dell          | Latitude E7440              | [619c6e4b99](https://linux-hardware.org/?probe=619c6e4b99) | Jul 27, 2023 |
| Samsung       | 300E5M/300E5L               | [23b23d59aa](https://linux-hardware.org/?probe=23b23d59aa) | Jul 27, 2023 |
| HP            | Dev One Notebook PC         | [b54bb52258](https://linux-hardware.org/?probe=b54bb52258) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Acer          | Nitro AN515-55              | [00e9bb8973](https://linux-hardware.org/?probe=00e9bb8973) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [22b2519a90](https://linux-hardware.org/?probe=22b2519a90) | Jul 26, 2023 |
| Acer          | Aspire A515-56              | [7e0e30c1cf](https://linux-hardware.org/?probe=7e0e30c1cf) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [b583a1fbee](https://linux-hardware.org/?probe=b583a1fbee) | Jul 26, 2023 |
| Dell          | Inspiron 5548               | [3d3696e8fa](https://linux-hardware.org/?probe=3d3696e8fa) | Jul 25, 2023 |
| HP            | Laptop 14-bs0xx             | [e074ee90be](https://linux-hardware.org/?probe=e074ee90be) | Jul 25, 2023 |
| MSI           | GF63 Thin 10SCXR            | [b34b7fa5fb](https://linux-hardware.org/?probe=b34b7fa5fb) | Jul 25, 2023 |
| Dell          | Inspiron 5490               | [25f155c61a](https://linux-hardware.org/?probe=25f155c61a) | Jul 24, 2023 |
| Dell          | Inspiron 5490               | [6b80b41fee](https://linux-hardware.org/?probe=6b80b41fee) | Jul 24, 2023 |
| Dell          | XPS 15 7590                 | [fa64a82283](https://linux-hardware.org/?probe=fa64a82283) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [88cfdb061d](https://linux-hardware.org/?probe=88cfdb061d) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [53bab7ac5e](https://linux-hardware.org/?probe=53bab7ac5e) | Jul 24, 2023 |
| Apple         | MacBookPro5,5               | [b2b0895194](https://linux-hardware.org/?probe=b2b0895194) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| Apple         | MacBookPro8,1               | [2cd0946aba](https://linux-hardware.org/?probe=2cd0946aba) | Jul 23, 2023 |
| Sony          | SVF1521A6EW                 | [3c39100c6f](https://linux-hardware.org/?probe=3c39100c6f) | Jul 23, 2023 |
| PC Special... | Standard                    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Google        | Snappy                      | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Dell          | Latitude 3500               | [0755576e96](https://linux-hardware.org/?probe=0755576e96) | Jul 22, 2023 |
| Dell          | Latitude E6430s             | [8e74e2a524](https://linux-hardware.org/?probe=8e74e2a524) | Jul 22, 2023 |
| Dell          | Vostro 3560                 | [05acc63d53](https://linux-hardware.org/?probe=05acc63d53) | Jul 22, 2023 |
| Dell          | Latitude 5410               | [82217114b4](https://linux-hardware.org/?probe=82217114b4) | Jul 21, 2023 |
| Dell          | Latitude 5520               | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| Dell          | Precision 7530              | [0d2e753768](https://linux-hardware.org/?probe=0d2e753768) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Dell          | Latitude E5270              | [9ea13fdc27](https://linux-hardware.org/?probe=9ea13fdc27) | Jul 20, 2023 |
| HP            | Laptop 15-da0xxx            | [6e17b916ee](https://linux-hardware.org/?probe=6e17b916ee) | Jul 20, 2023 |
| Acer          | Extensa 5635ZG              | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Toshiba       | Satellite L750              | [662f89dcc3](https://linux-hardware.org/?probe=662f89dcc3) | Jul 20, 2023 |
| Dell          | XPS 13 9360                 | [ac1a8eea0e](https://linux-hardware.org/?probe=ac1a8eea0e) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| Schenker      | XMG NEO (CML/E20)           | [9f99e57705](https://linux-hardware.org/?probe=9f99e57705) | Jul 19, 2023 |
| ASUSTek       | K53E                        | [7fddec038e](https://linux-hardware.org/?probe=7fddec038e) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| Notebook      | NH5x_7xDPx                  | [098f2f58c7](https://linux-hardware.org/?probe=098f2f58c7) | Jul 18, 2023 |
| Apple         | MacBookPro16,1              | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| ASRock        | Z77 Performance             | [585aaad9ad](https://linux-hardware.org/?probe=585aaad9ad) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| HP            | 635                         | [500e11147e](https://linux-hardware.org/?probe=500e11147e) | Jul 18, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1426cda0a7](https://linux-hardware.org/?probe=1426cda0a7) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [0bbd5c68bb](https://linux-hardware.org/?probe=0bbd5c68bb) | Jul 17, 2023 |
| Dell          | Precision M6800             | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| Lenovo        | ThinkPad X390 20Q1S67S00    | [be43004463](https://linux-hardware.org/?probe=be43004463) | Jul 17, 2023 |
| System76      | Serval WS                   | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [437209972c](https://linux-hardware.org/?probe=437209972c) | Jul 15, 2023 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [91dbb2c969](https://linux-hardware.org/?probe=91dbb2c969) | Jul 15, 2023 |
| Dell          | G15 5510                    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| System76      | Pangolin                    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | ENVY 15                     | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [e53c63af42](https://linux-hardware.org/?probe=e53c63af42) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | [fb022ada73](https://linux-hardware.org/?probe=fb022ada73) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| HP            | Compaq CQ58                 | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | [c82bb58705](https://linux-hardware.org/?probe=c82bb58705) | Jul 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [5a675551df](https://linux-hardware.org/?probe=5a675551df) | Jul 13, 2023 |
| Dell          | G3 3590                     | [089bfa3da7](https://linux-hardware.org/?probe=089bfa3da7) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | [d4910e3f43](https://linux-hardware.org/?probe=d4910e3f43) | Jul 13, 2023 |
| Acer          | Swift SF314-42              | [7a9624e7cc](https://linux-hardware.org/?probe=7a9624e7cc) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| HP            | Laptop 17-cp0xxx            | [801537f1d4](https://linux-hardware.org/?probe=801537f1d4) | Jul 12, 2023 |
| Apple         | MacBookPro6,2               | [20e2180dc1](https://linux-hardware.org/?probe=20e2180dc1) | Jul 12, 2023 |
| MSI           | Cyborg 15 A12VF             | [2c4a8d9d63](https://linux-hardware.org/?probe=2c4a8d9d63) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| HP            | EliteBook 850 G6            | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Apple         | MacBookAir7,2               | [1453f984c9](https://linux-hardware.org/?probe=1453f984c9) | Jul 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5a7dbc5d7c](https://linux-hardware.org/?probe=5a7dbc5d7c) | Jul 10, 2023 |
| Apple         | MacBookPro6,2               | [293ddc3253](https://linux-hardware.org/?probe=293ddc3253) | Jul 10, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Toshiba       | IS 1413G                    | [cf96aafbc0](https://linux-hardware.org/?probe=cf96aafbc0) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [1f88a40c05](https://linux-hardware.org/?probe=1f88a40c05) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [e1f22afb69](https://linux-hardware.org/?probe=e1f22afb69) | Jul 08, 2023 |
| MSI           | Cyborg 15 A12VF             | [a34d0d8290](https://linux-hardware.org/?probe=a34d0d8290) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| Acer          | Nitro AN515-57              | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| ASUSTek       | N55SL                       | [1223d8b536](https://linux-hardware.org/?probe=1223d8b536) | Jul 07, 2023 |
| MSI           | GS66 Stealth 10SE           | [e689bf355c](https://linux-hardware.org/?probe=e689bf355c) | Jul 07, 2023 |
| Panasonic     | FZ55-1                      | [4d12f02737](https://linux-hardware.org/?probe=4d12f02737) | Jul 07, 2023 |
| Dell          | Inspiron 3501               | [e657049abf](https://linux-hardware.org/?probe=e657049abf) | Jul 06, 2023 |
| Toshiba       | IS 1413G                    | [f2a99b72dc](https://linux-hardware.org/?probe=f2a99b72dc) | Jul 06, 2023 |
| Acer          | Predator PT515-51           | [9971e8a3da](https://linux-hardware.org/?probe=9971e8a3da) | Jul 05, 2023 |
| HP            | Laptop 15-da0xxx            | [f634e3942a](https://linux-hardware.org/?probe=f634e3942a) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| Dell          | XPS 17 9720                 | [a99946b8f0](https://linux-hardware.org/?probe=a99946b8f0) | Jul 04, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [09dffdde54](https://linux-hardware.org/?probe=09dffdde54) | Jul 04, 2023 |
| MSI           | Cyborg 15 A12VF             | [156f923a72](https://linux-hardware.org/?probe=156f923a72) | Jul 04, 2023 |
| Acer          | Aspire E1-470G              | [db4125a1c5](https://linux-hardware.org/?probe=db4125a1c5) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [dda9b242fd](https://linux-hardware.org/?probe=dda9b242fd) | Jul 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [e8ff92b585](https://linux-hardware.org/?probe=e8ff92b585) | Jul 03, 2023 |
| Acer          | Aspire A515-52              | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| Dell          | Precision 7510              | [46b90e25b0](https://linux-hardware.org/?probe=46b90e25b0) | Jul 02, 2023 |
| MSI           | GT72VR 6RD                  | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6ee8b4e949](https://linux-hardware.org/?probe=6ee8b4e949) | Jul 01, 2023 |
| Dell          | Latitude 3500               | [8293ebc591](https://linux-hardware.org/?probe=8293ebc591) | Jul 01, 2023 |
| Toshiba       | IS 1413G                    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| Teclast       | F7 Plus                     | [cebd3b027c](https://linux-hardware.org/?probe=cebd3b027c) | Jun 30, 2023 |
| Dell          | XPS 13 9370                 | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| Positivo      | Mobile                      | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [568380fd59](https://linux-hardware.org/?probe=568380fd59) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | [54013b2dfd](https://linux-hardware.org/?probe=54013b2dfd) | Jun 30, 2023 |
| Positivo      | H14CU02                     | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| MSI           | GE70 2PL                    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| Acer          | Aspire A315-21              | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Dell          | Precision M6800             | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| Apple         | MacBookAir6,1               | [6b44c8513d](https://linux-hardware.org/?probe=6b44c8513d) | Jun 26, 2023 |
| Dell          | Precision M6800             | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| HP            | Notebook                    | [ea00ce6c5b](https://linux-hardware.org/?probe=ea00ce6c5b) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| HP            | ENVY NOTEBOOK PC            | [8bd62ffdf1](https://linux-hardware.org/?probe=8bd62ffdf1) | Jun 25, 2023 |
| Acer          | Swift SF314-512             | [12f361cd8c](https://linux-hardware.org/?probe=12f361cd8c) | Jun 24, 2023 |
| System76      | Oryx Pro                    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [737204f453](https://linux-hardware.org/?probe=737204f453) | Jun 24, 2023 |
| MSI           | Cyborg 15 A12VF             | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| ASUSTek       | X551MA                      | [5b2b7d4a7f](https://linux-hardware.org/?probe=5b2b7d4a7f) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| HP            | Notebook                    | [35b8a2a187](https://linux-hardware.org/?probe=35b8a2a187) | Jun 22, 2023 |
| Lenovo        | B5400 80B6QB0               | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| Dell          | Inspiron 5567               | [8634954b1c](https://linux-hardware.org/?probe=8634954b1c) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [b255195205](https://linux-hardware.org/?probe=b255195205) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Latitude E7240              | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [383aed9129](https://linux-hardware.org/?probe=383aed9129) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | [3996492e80](https://linux-hardware.org/?probe=3996492e80) | Jun 20, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| System76      | Lemur Pro                   | [5074769fee](https://linux-hardware.org/?probe=5074769fee) | Jun 19, 2023 |
| Dell          | Latitude 7430               | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | Laptop 15-dy2xxx            | [0699537327](https://linux-hardware.org/?probe=0699537327) | Jun 19, 2023 |
| MSI           | Raider GE66 12UGS           | [73b20b76a3](https://linux-hardware.org/?probe=73b20b76a3) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Acer          | Aspire 5750G                | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [ae0a1a134a](https://linux-hardware.org/?probe=ae0a1a134a) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| Avell High... | A70 HYB                     | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| System76      | Gazelle                     | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| HP            | Laptop 14-dk0xxx            | [1e6fdd560b](https://linux-hardware.org/?probe=1e6fdd560b) | Jun 14, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [667f0a20c1](https://linux-hardware.org/?probe=667f0a20c1) | Jun 14, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| System76      | Gazelle                     | [117f199b15](https://linux-hardware.org/?probe=117f199b15) | Jun 14, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| TUXEDO        | Unknown                     | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| Dell          | Latitude E7470              | [1253de4554](https://linux-hardware.org/?probe=1253de4554) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| Toshiba       | Satellite P55t-B            | [efc0f87778](https://linux-hardware.org/?probe=efc0f87778) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | [4160d59c4f](https://linux-hardware.org/?probe=4160d59c4f) | Jun 10, 2023 |
| Acer          | Aspire 7750                 | [b0daafa057](https://linux-hardware.org/?probe=b0daafa057) | Jun 09, 2023 |
| Dell          | Latitude E7240              | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| Dell          | Latitude E6420              | [d408418ddd](https://linux-hardware.org/?probe=d408418ddd) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | [975246674d](https://linux-hardware.org/?probe=975246674d) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | [348173e172](https://linux-hardware.org/?probe=348173e172) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| HP            | Pavilion dv7                | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| Machcreato... | 14                          | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| Dell          | Latitude E6420              | [620ca905d2](https://linux-hardware.org/?probe=620ca905d2) | Jun 07, 2023 |
| Machcreato... | 14                          | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | [2834fee64f](https://linux-hardware.org/?probe=2834fee64f) | Jun 06, 2023 |
| HP            | Laptop 14-cf2xxx            | [e6bf4ead0a](https://linux-hardware.org/?probe=e6bf4ead0a) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Apple         | MacBookAir4,2               | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| HP            | 15 Notebook PC              | [7c76016c9d](https://linux-hardware.org/?probe=7c76016c9d) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | [5dd18339de](https://linux-hardware.org/?probe=5dd18339de) | Jun 05, 2023 |
| Dell          | Inspiron 5437               | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Dell          | Inspiron 7472               | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| System76      | Oryx Pro                    | [b3b398ba61](https://linux-hardware.org/?probe=b3b398ba61) | Jun 03, 2023 |
| MSI           | Prestige 16 A12UD           | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Acer          | Predator PH517-51           | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| System76      | Adder WS                    | [5cfa553a01](https://linux-hardware.org/?probe=5cfa553a01) | May 31, 2023 |
| Toshiba       | IS 1413G                    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | Predator PH517-51           | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [907448944d](https://linux-hardware.org/?probe=907448944d) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [83f869ee2a](https://linux-hardware.org/?probe=83f869ee2a) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [23af21bb34](https://linux-hardware.org/?probe=23af21bb34) | May 30, 2023 |
| Toshiba       | Satellite P755              | [5dc8f46db5](https://linux-hardware.org/?probe=5dc8f46db5) | May 29, 2023 |
| Avell High... | A70 MOB                     | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| Dell          | XPS 15 9510                 | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| Apple         | MacBookAir5,1               | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| System76      | Adder WS                    | [d6de84e0c6](https://linux-hardware.org/?probe=d6de84e0c6) | May 28, 2023 |
| System76      | Adder WS                    | [5624c5b0e8](https://linux-hardware.org/?probe=5624c5b0e8) | May 28, 2023 |
| System76      | Adder WS                    | [2522fb534f](https://linux-hardware.org/?probe=2522fb534f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| Lenovo        | Yoga 700-11ISK 80QE         | [149dfccfe7](https://linux-hardware.org/?probe=149dfccfe7) | May 27, 2023 |
| Google        | Kohaku                      | [2b46417afd](https://linux-hardware.org/?probe=2b46417afd) | May 27, 2023 |
| Dell          | Inspiron 7520               | [07b70ac9e5](https://linux-hardware.org/?probe=07b70ac9e5) | May 27, 2023 |
| System76      | Galago Pro                  | [51cc594a01](https://linux-hardware.org/?probe=51cc594a01) | May 27, 2023 |
| Apple         | MacBookPro15,1              | [8d5c73bd4d](https://linux-hardware.org/?probe=8d5c73bd4d) | May 27, 2023 |
| Dell          | XPS 15 9570                 | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| ASUSTek       | X555LN                      | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | XPS 15 9570                 | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [a12e26f683](https://linux-hardware.org/?probe=a12e26f683) | May 26, 2023 |
| Dell          | Inspiron 7520               | [6d237fdf95](https://linux-hardware.org/?probe=6d237fdf95) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| ASUSTek       | X502CA                      | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| MSI           | Alpha 15 A3DDK              | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Apple         | MacBookPro6,1               | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Lenovo        | IdeaPad Y560                | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| Dell          | Precision 5470              | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| Dell          | G15 5511                    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Apple         | MacBookPro6,1               | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| HP            | Spectre Pro x360 G1         | [90df3b7bfa](https://linux-hardware.org/?probe=90df3b7bfa) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | [0f0ad128aa](https://linux-hardware.org/?probe=0f0ad128aa) | May 23, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| HP            | Laptop 14-dq0xxx            | [77ccb1431b](https://linux-hardware.org/?probe=77ccb1431b) | May 23, 2023 |
| Lenovo        | Unknown                     | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | X550CC                      | [8226c82b49](https://linux-hardware.org/?probe=8226c82b49) | May 21, 2023 |
| ASUSTek       | X550CC                      | [6a8e6201be](https://linux-hardware.org/?probe=6a8e6201be) | May 21, 2023 |
| Lenovo        | Unknown                     | [1288108e10](https://linux-hardware.org/?probe=1288108e10) | May 21, 2023 |
| Lenovo        | ThinkPad T440p              | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro5,3               | [0df526f042](https://linux-hardware.org/?probe=0df526f042) | May 21, 2023 |
| Dell          | G15 5511                    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| HP            | EliteBook 840 G5            | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| Toshiba       | Satellite L855D             | [5be0280c53](https://linux-hardware.org/?probe=5be0280c53) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| Acer          | Aspire E5-575               | [fb1832d859](https://linux-hardware.org/?probe=fb1832d859) | May 20, 2023 |
| Toshiba       | IS 1413G                    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [51f87ac309](https://linux-hardware.org/?probe=51f87ac309) | May 20, 2023 |
| HP            | Pavilion dv6                | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [d51c5680e8](https://linux-hardware.org/?probe=d51c5680e8) | May 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [08df098150](https://linux-hardware.org/?probe=08df098150) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Reliance C... | R141TL5                     | [a21525c003](https://linux-hardware.org/?probe=a21525c003) | May 18, 2023 |
| Dell          | Inspiron 5559               | [620177b4fa](https://linux-hardware.org/?probe=620177b4fa) | May 17, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.2.6-76060206-generic   | 469       | 19.14%  |
| 5.19.0-76051900-generic  | 274       | 11.18%  |
| 6.0.12-76060006-generic  | 266       | 10.86%  |
| 5.17.5-76051705-generic  | 233       | 9.51%   |
| 6.4.6-76060406-generic   | 184       | 7.51%   |
| 6.0.6-76060006-generic   | 164       | 6.69%   |
| 6.5.6-76060506-generic   | 155       | 6.33%   |
| 5.18.10-76051810-generic | 118       | 4.82%   |
| 5.17.15-76051715-generic | 105       | 4.29%   |
| 6.2.0-76060200-generic   | 77        | 3.14%   |
| 5.16.19-76051619-generic | 73        | 2.98%   |
| 6.5.4-76060504-generic   | 65        | 2.65%   |
| 6.0.2-76060002-generic   | 59        | 2.41%   |
| 6.1.11-76060111-generic  | 54        | 2.2%    |
| 6.6.6-76060606-generic   | 41        | 1.67%   |
| 6.0.3-76060003-generic   | 24        | 0.98%   |
| 5.19.16-76051916-generic | 21        | 0.86%   |
| 6.5.7-060507-generic     | 3         | 0.12%   |
| 6.4.0-060400-generic     | 2         | 0.08%   |
| 6.3.7-060307-generic     | 2         | 0.08%   |
| 6.2.11-060211-generic    | 2         | 0.08%   |
| 6.1.0-1006-oem           | 2         | 0.08%   |
| 5.17.5-051705-generic    | 2         | 0.08%   |
| 5.16.15-76051615-generic | 2         | 0.08%   |
| 6.5.8-x64v1-xanmod1      | 1         | 0.04%   |
| 6.5.5-x64v3-xanmod1      | 1         | 0.04%   |
| 6.5.12-x64v3-xanmod1     | 1         | 0.04%   |
| 6.5.10-x64v2-xanmod1     | 1         | 0.04%   |
| 6.5.0-rc2                | 1         | 0.04%   |
| 6.4.5-x64v2-xanmod1      | 1         | 0.04%   |
| 6.4.3-060403-generic     | 1         | 0.04%   |
| 6.4.12-2-liquorix-amd64  | 1         | 0.04%   |
| 6.3.9-x64v3-xanmod1      | 1         | 0.04%   |
| 6.3.9-060309-generic     | 1         | 0.04%   |
| 6.3.4-060304-generic     | 1         | 0.04%   |
| 6.3.2-060302-generic     | 1         | 0.04%   |
| 6.3.0-060300-generic     | 1         | 0.04%   |
| 6.2.9-1-liquorix-amd64   | 1         | 0.04%   |
| 6.2.6-060206-generic     | 1         | 0.04%   |
| 6.2.16-060216-generic    | 1         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.6   | 470       | 19.2%   |
| 5.19.0  | 277       | 11.32%  |
| 6.0.12  | 266       | 10.87%  |
| 5.17.5  | 236       | 9.64%   |
| 6.4.6   | 184       | 7.52%   |
| 6.0.6   | 164       | 6.7%    |
| 6.5.6   | 155       | 6.33%   |
| 5.18.10 | 118       | 4.82%   |
| 5.17.15 | 105       | 4.29%   |
| 6.2.0   | 77        | 3.15%   |
| 5.16.19 | 73        | 2.98%   |
| 6.5.4   | 65        | 2.66%   |
| 6.0.2   | 60        | 2.45%   |
| 6.1.11  | 54        | 2.21%   |
| 6.6.6   | 41        | 1.67%   |
| 6.0.3   | 24        | 0.98%   |
| 5.19.16 | 21        | 0.86%   |
| 6.5.7   | 3         | 0.12%   |
| 6.4.0   | 2         | 0.08%   |
| 6.3.9   | 2         | 0.08%   |
| 6.3.7   | 2         | 0.08%   |
| 6.2.11  | 2         | 0.08%   |
| 6.1.9   | 2         | 0.08%   |
| 6.1.0   | 2         | 0.08%   |
| 6.0.9   | 2         | 0.08%   |
| 6.0.0   | 2         | 0.08%   |
| 5.17.0  | 2         | 0.08%   |
| 5.16.15 | 2         | 0.08%   |
| 5.15.0  | 2         | 0.08%   |
| 6.5.8   | 1         | 0.04%   |
| 6.5.5   | 1         | 0.04%   |
| 6.5.12  | 1         | 0.04%   |
| 6.5.10  | 1         | 0.04%   |
| 6.5.0   | 1         | 0.04%   |
| 6.4.5   | 1         | 0.04%   |
| 6.4.3   | 1         | 0.04%   |
| 6.4.12  | 1         | 0.04%   |
| 6.3.4   | 1         | 0.04%   |
| 6.3.2   | 1         | 0.04%   |
| 6.3.0   | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 548       | 22.72%  |
| 6.0     | 499       | 20.69%  |
| 5.17    | 340       | 14.1%   |
| 5.19    | 300       | 12.44%  |
| 6.5     | 226       | 9.37%   |
| 6.4     | 188       | 7.79%   |
| 5.18    | 122       | 5.06%   |
| 5.16    | 76        | 3.15%   |
| 6.1     | 61        | 2.53%   |
| 6.6     | 41        | 1.7%    |
| 6.3     | 7         | 0.29%   |
| 5.15    | 4         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2213      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 2156      | 97.29%  |
| KDE5            | 19        | 0.86%   |
| Unknown         | 17        | 0.77%   |
| X-Cinnamon      | 7         | 0.32%   |
| GNOME Flashback | 5         | 0.23%   |
| Unity           | 4         | 0.18%   |
| MATE            | 2         | 0.09%   |
| LXQt            | 2         | 0.09%   |
| XFCE            | 1         | 0.05%   |
| i3              | 1         | 0.05%   |
| Cinnamon        | 1         | 0.05%   |
| awesome         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2107      | 94.61%  |
| Wayland | 106       | 4.76%   |
| Unknown | 11        | 0.49%   |
| Tty     | 3         | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1571      | 70.29%  |
| GDM3    | 655       | 29.31%  |
| GDM     | 5         | 0.22%   |
| SDDM    | 3         | 0.13%   |
| LightDM | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1326      | 59.6%   |
| en_GB   | 139       | 6.25%   |
| pt_BR   | 127       | 5.71%   |
| de_DE   | 91        | 4.09%   |
| C       | 66        | 2.97%   |
| it_IT   | 50        | 2.25%   |
| en_AU   | 47        | 2.11%   |
| fr_FR   | 44        | 1.98%   |
| en_CA   | 33        | 1.48%   |
| es_ES   | 32        | 1.44%   |
| ru_RU   | 28        | 1.26%   |
| pl_PL   | 22        | 0.99%   |
| nb_NO   | 17        | 0.76%   |
| Unknown | 16        | 0.72%   |
| pt_PT   | 15        | 0.67%   |
| tr_TR   | 12        | 0.54%   |
| en_NZ   | 12        | 0.54%   |
| sv_SE   | 11        | 0.49%   |
| en_IN   | 11        | 0.49%   |
| en_IE   | 10        | 0.45%   |
| fi_FI   | 9         | 0.4%    |
| es_MX   | 9         | 0.4%    |
| nl_NL   | 8         | 0.36%   |
| de_CH   | 8         | 0.36%   |
| fr_CA   | 6         | 0.27%   |
| en_ZA   | 6         | 0.27%   |
| cs_CZ   | 6         | 0.27%   |
| es_CO   | 5         | 0.22%   |
| es_CL   | 5         | 0.22%   |
| es_AR   | 5         | 0.22%   |
| en_DK   | 5         | 0.22%   |
| da_DK   | 5         | 0.22%   |
| hu_HU   | 3         | 0.13%   |
| de_AT   | 3         | 0.13%   |
| fr_CH   | 2         | 0.09%   |
| fr_BE   | 2         | 0.09%   |
| en_SG   | 2         | 0.09%   |
| en_PH   | 2         | 0.09%   |
| en_IL   | 2         | 0.09%   |
| en_AG   | 2         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1590      | 71.17%  |
| EFI  | 644       | 28.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2104      | 94.69%  |
| Btrfs   | 72        | 3.24%   |
| Overlay | 39        | 1.76%   |
| Xfs     | 6         | 0.27%   |
| Zfs     | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1555      | 69.57%  |
| GPT     | 644       | 28.81%  |
| MBR     | 36        | 1.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2150      | 96.89%  |
| Yes       | 69        | 3.11%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1993      | 89.57%  |
| Yes       | 232       | 10.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 460       | 20.79%  |
| Dell                   | 354       | 16%     |
| Hewlett-Packard        | 308       | 13.92%  |
| ASUSTek Computer       | 271       | 12.25%  |
| Acer                   | 158       | 7.14%   |
| Apple                  | 155       | 7%      |
| MSI                    | 83        | 3.75%   |
| System76               | 77        | 3.48%   |
| Toshiba                | 40        | 1.81%   |
| Samsung Electronics    | 35        | 1.58%   |
| HUAWEI                 | 30        | 1.36%   |
| Google                 | 21        | 0.95%   |
| Notebook               | 19        | 0.86%   |
| Alienware              | 16        | 0.72%   |
| Razer                  | 11        | 0.5%    |
| Fujitsu                | 11        | 0.5%    |
| Sony                   | 10        | 0.45%   |
| GPU Company            | 10        | 0.45%   |
| Gigabyte Technology    | 10        | 0.45%   |
| Framework              | 9         | 0.41%   |
| Timi                   | 8         | 0.36%   |
| Positivo               | 8         | 0.36%   |
| Unknown                | 8         | 0.36%   |
| HONOR                  | 7         | 0.32%   |
| PC Specialist          | 6         | 0.27%   |
| Avell High Performance | 6         | 0.27%   |
| TUXEDO                 | 4         | 0.18%   |
| Schenker               | 4         | 0.18%   |
| Clevo                  | 4         | 0.18%   |
| Panasonic              | 3         | 0.14%   |
| Medion                 | 3         | 0.14%   |
| LG Electronics         | 3         | 0.14%   |
| GPD                    | 3         | 0.14%   |
| Valve                  | 2         | 0.09%   |
| realme                 | 2         | 0.09%   |
| Packard Bell           | 2         | 0.09%   |
| OriginPC               | 2         | 0.09%   |
| Maibenben              | 2         | 0.09%   |
| Haier                  | 2         | 0.09%   |
| Gateway                | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| System76 Oryx Pro                   | 19        | 0.86%   |
| System76 Lemur Pro                  | 16        | 0.72%   |
| Apple MacBookAir7,2                 | 15        | 0.68%   |
| Unknown                             | 15        | 0.68%   |
| System76 Gazelle                    | 13        | 0.59%   |
| HP Dev One Notebook PC              | 13        | 0.59%   |
| Apple MacBookPro12,1                | 12        | 0.54%   |
| Apple MacBookAir6,2                 | 12        | 0.54%   |
| Apple MacBookPro8,1                 | 11        | 0.5%    |
| Apple MacBookPro9,2                 | 10        | 0.45%   |
| Apple MacBookPro11,3                | 9         | 0.41%   |
| System76 Darter Pro                 | 8         | 0.36%   |
| Dell XPS 15 9520                    | 8         | 0.36%   |
| Apple MacBookPro7,1                 | 8         | 0.36%   |
| System76 Galago Pro                 | 7         | 0.32%   |
| Lenovo Legion 5 15ACH6H 82JU        | 7         | 0.32%   |
| Lenovo IdeaPad S145-15API 81V7      | 7         | 0.32%   |
| Lenovo IdeaPad Gaming 3 15IAH7 82S9 | 7         | 0.32%   |
| Dell XPS 15 7590                    | 7         | 0.32%   |
| System76 Pangolin                   | 6         | 0.27%   |
| Lenovo IdeaPad 3 15ALC6 82MF        | 6         | 0.27%   |
| HP Pavilion 15                      | 6         | 0.27%   |
| HP Notebook                         | 6         | 0.27%   |
| Dell XPS 15 9570                    | 6         | 0.27%   |
| Dell XPS 13 9310                    | 6         | 0.27%   |
| Dell Latitude E7240                 | 6         | 0.27%   |
| Apple MacBookPro11,1                | 6         | 0.27%   |
| Acer Aspire A515-45                 | 6         | 0.27%   |
| Razer Blade                         | 5         | 0.23%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN    | 5         | 0.23%   |
| Lenovo IdeaPad 330-15IKB 81FE       | 5         | 0.23%   |
| Lenovo IdeaPad 330-15IKB 81DE       | 5         | 0.23%   |
| HP Victus by Laptop 16-e0xxx        | 5         | 0.23%   |
| HP EliteBook 840 G5                 | 5         | 0.23%   |
| Framework Laptop                    | 5         | 0.23%   |
| Dell XPS 13 9370                    | 5         | 0.23%   |
| Dell XPS 13 9360                    | 5         | 0.23%   |
| Dell Latitude E7270                 | 5         | 0.23%   |
| ASUS N550JV                         | 5         | 0.23%   |
| Apple MacBookPro10,1                | 5         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 204       | 9.22%   |
| Lenovo IdeaPad     | 124       | 5.6%    |
| Acer Aspire        | 99        | 4.47%   |
| Dell Latitude      | 93        | 4.2%    |
| Dell Inspiron      | 92        | 4.16%   |
| Dell XPS           | 75        | 3.39%   |
| HP Pavilion        | 59        | 2.67%   |
| ASUS VivoBook      | 57        | 2.58%   |
| Lenovo Legion      | 51        | 2.3%    |
| ASUS ROG           | 51        | 2.3%    |
| HP Laptop          | 49        | 2.21%   |
| HP EliteBook       | 49        | 2.21%   |
| Dell Precision     | 40        | 1.81%   |
| HP ProBook         | 36        | 1.63%   |
| Toshiba Satellite  | 33        | 1.49%   |
| ASUS ASUS          | 33        | 1.49%   |
| Acer Swift         | 24        | 1.08%   |
| HP ZBook           | 23        | 1.04%   |
| Apple MacBookPro11 | 23        | 1.04%   |
| ASUS Zenbook       | 22        | 0.99%   |
| System76 Oryx      | 19        | 0.86%   |
| Dell Vostro        | 19        | 0.86%   |
| Acer Nitro         | 19        | 0.86%   |
| System76 Lemur     | 16        | 0.72%   |
| Lenovo ThinkBook   | 16        | 0.72%   |
| HP OMEN            | 15        | 0.68%   |
| Apple MacBookAir7  | 15        | 0.68%   |
| Unknown            | 15        | 0.68%   |
| Apple MacBookPro8  | 14        | 0.63%   |
| System76 Gazelle   | 13        | 0.59%   |
| Lenovo Yoga        | 13        | 0.59%   |
| HP ENVY            | 13        | 0.59%   |
| HP Dev             | 13        | 0.59%   |
| Apple MacBookAir6  | 13        | 0.59%   |
| Apple MacBookPro12 | 12        | 0.54%   |
| Razer Blade        | 11        | 0.5%    |
| Dell G15           | 11        | 0.5%    |
| Apple MacBookPro9  | 11        | 0.5%    |
| Apple MacBookPro5  | 11        | 0.5%    |
| HP Victus          | 9         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 340       | 15.36%  |
| 2022    | 259       | 11.7%   |
| 2020    | 241       | 10.89%  |
| 2019    | 189       | 8.54%   |
| 2018    | 176       | 7.95%   |
| 2013    | 140       | 6.33%   |
| 2012    | 116       | 5.24%   |
| 2011    | 109       | 4.93%   |
| 2016    | 108       | 4.88%   |
| 2017    | 107       | 4.84%   |
| 2015    | 101       | 4.56%   |
| 2014    | 98        | 4.43%   |
| 2023    | 81        | 3.66%   |
| 2010    | 57        | 2.58%   |
| 2009    | 46        | 2.08%   |
| 2008    | 22        | 0.99%   |
| 2007    | 21        | 0.95%   |
| 2006    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2213      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2213      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2132      | 96.34%  |
| Yes  | 81        | 3.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 625       | 28.03%  |
| 16.01-24.0  | 536       | 24.04%  |
| 8.01-16.0   | 425       | 19.06%  |
| 32.01-64.0  | 265       | 11.88%  |
| 3.01-4.0    | 255       | 11.43%  |
| 64.01-256.0 | 64        | 2.87%   |
| 24.01-32.0  | 45        | 2.02%   |
| 1.01-2.0    | 9         | 0.4%    |
| 2.01-3.0    | 6         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 781       | 32.72%  |
| 2.01-3.0   | 638       | 26.73%  |
| 3.01-4.0   | 514       | 21.53%  |
| 8.01-16.0  | 215       | 9.01%   |
| 1.01-2.0   | 193       | 8.09%   |
| 16.01-24.0 | 36        | 1.51%   |
| 24.01-32.0 | 8         | 0.34%   |
| 0.51-1.0   | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1617      | 72.22%  |
| 2      | 535       | 23.89%  |
| 3      | 71        | 3.17%   |
| 0      | 9         | 0.4%    |
| 4      | 5         | 0.22%   |
| 7      | 1         | 0.04%   |
| 5      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1745      | 78.71%  |
| Yes       | 472       | 21.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1662      | 74.66%  |
| No        | 564       | 25.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2190      | 98.96%  |
| No        | 23        | 1.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1906      | 85.7%   |
| No        | 318       | 14.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 596       | 26.81%  |
| Brazil       | 185       | 8.32%   |
| Germany      | 135       | 6.07%   |
| UK           | 93        | 4.18%   |
| Italy        | 91        | 4.09%   |
| India        | 84        | 3.78%   |
| Canada       | 83        | 3.73%   |
| France       | 64        | 2.88%   |
| Australia    | 61        | 2.74%   |
| Russia       | 49        | 2.2%    |
| Spain        | 41        | 1.84%   |
| Netherlands  | 41        | 1.84%   |
| Poland       | 36        | 1.62%   |
| Norway       | 34        | 1.53%   |
| Sweden       | 33        | 1.48%   |
| Turkey       | 30        | 1.35%   |
| Portugal     | 30        | 1.35%   |
| Mexico       | 30        | 1.35%   |
| Czechia      | 26        | 1.17%   |
| Indonesia    | 21        | 0.94%   |
| Philippines  | 20        | 0.9%    |
| New Zealand  | 20        | 0.9%    |
| Switzerland  | 19        | 0.85%   |
| Denmark      | 19        | 0.85%   |
| Finland      | 18        | 0.81%   |
| Romania      | 17        | 0.76%   |
| Serbia       | 16        | 0.72%   |
| Argentina    | 16        | 0.72%   |
| Greece       | 14        | 0.63%   |
| Thailand     | 13        | 0.58%   |
| Chile        | 13        | 0.58%   |
| Bulgaria     | 13        | 0.58%   |
| Belgium      | 13        | 0.58%   |
| Hungary      | 12        | 0.54%   |
| Austria      | 11        | 0.49%   |
| South Africa | 10        | 0.45%   |
| Ireland      | 10        | 0.45%   |
| Colombia     | 9         | 0.4%    |
| Malaysia     | 8         | 0.36%   |
| Vietnam      | 7         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 20        | 0.87%   |
| Oslo           | 17        | 0.74%   |
| Melbourne      | 16        | 0.69%   |
| Brisbane       | 16        | 0.69%   |
| Warsaw         | 15        | 0.65%   |
| Milan          | 15        | 0.65%   |
| Istanbul       | 15        | 0.65%   |
| Sydney         | 14        | 0.61%   |
| Helsinki       | 14        | 0.61%   |
| Bengaluru      | 14        | 0.61%   |
| Prague         | 12        | 0.52%   |
| New York       | 12        | 0.52%   |
| Moscow         | 12        | 0.52%   |
| Madrid         | 12        | 0.52%   |
| Chicago        | 12        | 0.52%   |
| Berlin         | 12        | 0.52%   |
| Rio de Janeiro | 11        | 0.48%   |
| Denver         | 10        | 0.43%   |
| Auckland       | 10        | 0.43%   |
| Stockholm      | 9         | 0.39%   |
| Sofia          | 9         | 0.39%   |
| Seattle        | 9         | 0.39%   |
| Munich         | 9         | 0.39%   |
| London         | 9         | 0.39%   |
| Lisbon         | 9         | 0.39%   |
| Belgrade       | 9         | 0.39%   |
| Vienna         | 8         | 0.35%   |
| St Petersburg  | 8         | 0.35%   |
| Rome           | 8         | 0.35%   |
| Paris          | 8         | 0.35%   |
| Mumbai         | 8         | 0.35%   |
| Hamburg        | 8         | 0.35%   |
| Calgary        | 8         | 0.35%   |
| Singapore      | 7         | 0.3%    |
| Salt Lake City | 7         | 0.3%    |
| Minneapolis    | 7         | 0.3%    |
| Los Angeles    | 7         | 0.3%    |
| Leipzig        | 7         | 0.3%    |
| Edmonton       | 7         | 0.3%    |
| Dallas         | 7         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 545       | 721    | 19.42%  |
| SanDisk                        | 240       | 300    | 8.55%   |
| WDC                            | 239       | 272    | 8.52%   |
| Seagate                        | 183       | 212    | 6.52%   |
| SK hynix                       | 163       | 186    | 5.81%   |
| Toshiba                        | 147       | 174    | 5.24%   |
| Kingston                       | 145       | 167    | 5.17%   |
| Micron Technology              | 128       | 146    | 4.56%   |
| Unknown                        | 97        | 116    | 3.46%   |
| Intel                          | 96        | 112    | 3.42%   |
| Crucial                        | 89        | 101    | 3.17%   |
| Apple                          | 86        | 95     | 3.06%   |
| HGST                           | 59        | 66     | 2.1%    |
| KIOXIA                         | 48        | 51     | 1.71%   |
| Micron/Crucial Technology      | 32        | 39     | 1.14%   |
| Hitachi                        | 31        | 36     | 1.1%    |
| A-DATA Technology              | 30        | 37     | 1.07%   |
| Phison                         | 28        | 31     | 1%      |
| China                          | 28        | 34     | 1%      |
| Phison Electronics             | 25        | 28     | 0.89%   |
| PNY                            | 24        | 31     | 0.86%   |
| Silicon Motion                 | 20        | 23     | 0.71%   |
| Kingston Technology Company    | 20        | 21     | 0.71%   |
| Unknown                        | 15        | 19     | 0.53%   |
| Intenso                        | 13        | 18     | 0.46%   |
| LITEON                         | 12        | 13     | 0.43%   |
| KingSpec                       | 12        | 13     | 0.43%   |
| Netac                          | 11        | 11     | 0.39%   |
| LITEONIT                       | 11        | 20     | 0.39%   |
| ADATA Technology               | 10        | 10     | 0.36%   |
| Union Memory (Shenzhen)        | 9         | 12     | 0.32%   |
| Transcend                      | 9         | 10     | 0.32%   |
| Team                           | 9         | 9      | 0.32%   |
| Solid State Storage Technology | 9         | 9      | 0.32%   |
| Solid State Storage            | 9         | 10     | 0.32%   |
| SPCC                           | 8         | 8      | 0.29%   |
| JMicron Technology             | 7         | 8      | 0.25%   |
| Patriot                        | 6         | 8      | 0.21%   |
| Lexar                          | 6         | 7      | 0.21%   |
| SSSTC                          | 5         | 5      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 66        | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 45        | 1.54%   |
| Kingston SA400S37240G 240GB SSD                     | 36        | 1.23%   |
| Seagate ST1000LM035-1RK172 1TB                      | 32        | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 22        | 0.75%   |
| HGST HTS721010A9E630 1TB                            | 21        | 0.72%   |
| Toshiba MQ04ABF100 1TB                              | 20        | 0.68%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 20        | 0.68%   |
| SanDisk NVMe SSD Drive 1TB                          | 20        | 0.68%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 19        | 0.65%   |
| Intel SSD 660P Series 1TB                           | 19        | 0.65%   |
| Apple SSD SM0128G 121GB                             | 19        | 0.65%   |
| Unknown MMC Card  32GB                              | 18        | 0.62%   |
| Crucial CT240BX500SSD1 240GB                        | 18        | 0.62%   |
| Toshiba MQ01ABD100 1TB                              | 17        | 0.58%   |
| Samsung NVMe SSD Drive 512GB                        | 17        | 0.58%   |
| Unknown MMC Card  64GB                              | 16        | 0.55%   |
| Kingston SA400S37480G 480GB SSD                     | 16        | 0.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 15        | 0.51%   |
| Unknown                                             | 15        | 0.51%   |
| SK hynix NVMe SSD Drive 512GB                       | 14        | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 14        | 0.48%   |
| WDC WD10SPZX-24Z10 1TB                              | 13        | 0.44%   |
| Unknown MMC Card  128GB                             | 12        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                        | 12        | 0.41%   |
| Intel SSDPEKNU512GZ 512GB                           | 12        | 0.41%   |
| Seagate ST1000LM049-2GH172 1TB                      | 11        | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB                        | 11        | 0.38%   |
| Samsung SSD 850 EVO 500GB                           | 11        | 0.38%   |
| Phison E12 NVMe Controller 1TB                      | 11        | 0.38%   |
| Kingston SA400S37120G 120GB SSD                     | 11        | 0.38%   |
| Unknown MMC Card  16GB                              | 10        | 0.34%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB     | 10        | 0.34%   |
| Sandisk WD Black SN850 1024GB                       | 10        | 0.34%   |
| SanDisk NVMe SSD Drive 256GB                        | 10        | 0.34%   |
| Samsung SSD 980 PRO 1TB                             | 10        | 0.34%   |
| Samsung SSD 870 EVO 500GB                           | 10        | 0.34%   |
| Samsung SSD 860 EVO 500GB                           | 10        | 0.34%   |
| Samsung NVMe SSD Drive 1TB                          | 10        | 0.34%   |
| Micron 2450_MTFDKBA512TFK 512GB                     | 10        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 177       | 205    | 34.64%  |
| WDC                 | 124       | 144    | 24.27%  |
| Toshiba             | 88        | 102    | 17.22%  |
| HGST                | 59        | 66     | 11.55%  |
| Hitachi             | 31        | 36     | 6.07%   |
| Unknown             | 7         | 7      | 1.37%   |
| Samsung Electronics | 7         | 7      | 1.37%   |
| Fujitsu             | 4         | 4      | 0.78%   |
| Apple               | 3         | 4      | 0.59%   |
| StoreJet            | 2         | 2      | 0.39%   |
| SABRENT             | 2         | 3      | 0.39%   |
| Intenso             | 2         | 6      | 0.39%   |
| External            | 2         | 2      | 0.39%   |
| USB3.0              | 1         | 1      | 0.2%    |
| HGST HDN            | 1         | 1      | 0.2%    |
| Asm                 | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 163       | 206    | 19.52%  |
| Kingston            | 104       | 115    | 12.46%  |
| SanDisk             | 81        | 99     | 9.7%    |
| Crucial             | 78        | 90     | 9.34%   |
| Apple               | 71        | 78     | 8.5%    |
| WDC                 | 47        | 53     | 5.63%   |
| China               | 28        | 34     | 3.35%   |
| Micron Technology   | 23        | 26     | 2.75%   |
| PNY                 | 22        | 29     | 2.63%   |
| SK hynix            | 21        | 22     | 2.51%   |
| Toshiba             | 19        | 19     | 2.28%   |
| A-DATA Technology   | 13        | 16     | 1.56%   |
| KingSpec            | 12        | 13     | 1.44%   |
| Intel               | 12        | 13     | 1.44%   |
| LITEONIT            | 11        | 20     | 1.32%   |
| LITEON              | 10        | 11     | 1.2%    |
| Netac               | 8         | 8      | 0.96%   |
| Intenso             | 8         | 8      | 0.96%   |
| Transcend           | 7         | 8      | 0.84%   |
| SPCC                | 6         | 6      | 0.72%   |
| Patriot             | 5         | 7      | 0.6%    |
| JMicron Technology  | 5         | 6      | 0.6%    |
| Hewlett-Packard     | 4         | 4      | 0.48%   |
| Apacer              | 4         | 8      | 0.48%   |
| Team                | 3         | 3      | 0.36%   |
| MyDigitalSSD        | 3         | 3      | 0.36%   |
| Lexar               | 3         | 4      | 0.36%   |
| Fanxiang            | 3         | 3      | 0.36%   |
| Dogfish             | 3         | 4      | 0.36%   |
| Wibtek              | 2         | 4      | 0.24%   |
| Teclast             | 2         | 2      | 0.24%   |
| PHD 3.0             | 2         | 2      | 0.24%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.24%   |
| KingDian            | 2         | 2      | 0.24%   |
| Inland              | 2         | 2      | 0.24%   |
| Hikvision           | 2         | 2      | 0.24%   |
| GOODRAM             | 2         | 2      | 0.24%   |
| Unknown             | 2         | 2      | 0.24%   |
| XSTAR               | 1         | 1      | 0.12%   |
| W800S               | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1196      | 1616   | 46.16%  |
| SSD     | 769       | 979    | 29.68%  |
| HDD     | 491       | 591    | 18.95%  |
| MMC     | 92        | 108    | 3.55%   |
| Unknown | 43        | 56     | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1195      | 1613   | 47.69%  |
| SATA | 1119      | 1495   | 44.65%  |
| SAS  | 100       | 134    | 3.99%   |
| MMC  | 92        | 108    | 3.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 782       | 1010   | 62.36%  |
| 0.51-1.0   | 399       | 466    | 31.82%  |
| 1.01-2.0   | 60        | 71     | 4.78%   |
| 3.01-4.0   | 7         | 13     | 0.56%   |
| 4.01-10.0  | 5         | 9      | 0.4%    |
| 2.01-3.0   | 1         | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 710       | 31.24%  |
| 251-500        | 664       | 29.21%  |
| 501-1000       | 485       | 21.34%  |
| 1001-2000      | 155       | 6.82%   |
| 51-100         | 75        | 3.3%    |
| 1-20           | 51        | 2.24%   |
| 2001-3000      | 43        | 1.89%   |
| More than 3000 | 41        | 1.8%    |
| 21-50          | 33        | 1.45%   |
| Unknown        | 16        | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 730       | 30.91%  |
| 21-50          | 568       | 24.05%  |
| 101-250        | 359       | 15.2%   |
| 51-100         | 328       | 13.89%  |
| 251-500        | 215       | 9.1%    |
| 501-1000       | 100       | 4.23%   |
| 1001-2000      | 27        | 1.14%   |
| Unknown        | 16        | 0.68%   |
| More than 3000 | 12        | 0.51%   |
| 2001-3000      | 7         | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1024GB               | 3         | 3      | 5.56%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 2      | 3.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2      | 3.7%    |
| HGST HTS725050A7E630 500GB                          | 2         | 3      | 3.7%    |
| WDC WDS480G2G0B-00EPW0 480GB SSD                    | 1         | 1      | 1.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1      | 1.85%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 1      | 1.85%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 1      | 1.85%   |
| WDC WD3200BEKX-75B7WT0 320GB                        | 1         | 1      | 1.85%   |
| WDC WD3200BEKT-60PVMT0 320GB                        | 1         | 1      | 1.85%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 1      | 1.85%   |
| WDC WD10SPZX-22Z10T0 1TB                            | 1         | 1      | 1.85%   |
| WDC WD10SPZX-16Z10T0 1TB                            | 1         | 1      | 1.85%   |
| WDC WD10JPVX-60JC3T1 1TB                            | 1         | 1      | 1.85%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 1.85%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB                | 1         | 1      | 1.85%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 1      | 1.85%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 1      | 1.85%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 1.85%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 1.85%   |
| Toshiba MK7559GSXP 752GB                            | 1         | 1      | 1.85%   |
| Toshiba MK3252GSX 320GB                             | 1         | 1      | 1.85%   |
| Team TM8FP4004T 4TB                                 | 1         | 1      | 1.85%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 1         | 1      | 1.85%   |
| SK hynix HFS512G39TND-N210A 512GB SSD               | 1         | 1      | 1.85%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 1.85%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 1      | 1.85%   |
| Silicon Motion 1TB PCS PCIe M.2 SSD                 | 1         | 1      | 1.85%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 1.85%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 1.85%   |
| Seagate ST500LM030-2E717D 500GB                     | 1         | 1      | 1.85%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 1.85%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 980 PRO 500GB               | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 970 EVO Plus 1TB            | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 850 EVO 500GB               | 1         | 1      | 1.85%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 1.85%   |
| LITEON CL1-8D512 512GB                              | 1         | 1      | 1.85%   |
| Lexar 1TB SSD                                       | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 12     | 22.22%  |
| Seagate             | 9         | 9      | 16.67%  |
| SK hynix            | 7         | 7      | 12.96%  |
| Toshiba             | 6         | 6      | 11.11%  |
| HGST                | 5         | 6      | 9.26%   |
| Samsung Electronics | 4         | 4      | 7.41%   |
| Team                | 1         | 1      | 1.85%   |
| Silicon Motion      | 1         | 1      | 1.85%   |
| Micron Technology   | 1         | 1      | 1.85%   |
| LITEON              | 1         | 1      | 1.85%   |
| Lexar               | 1         | 1      | 1.85%   |
| Leven               | 1         | 1      | 1.85%   |
| Kingston            | 1         | 1      | 1.85%   |
| Intel               | 1         | 1      | 1.85%   |
| Hitachi             | 1         | 3      | 1.85%   |
| Crucial             | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 9      | 33.33%  |
| WDC     | 8         | 8      | 29.63%  |
| HGST    | 5         | 6      | 18.52%  |
| Toshiba | 4         | 4      | 14.81%  |
| Hitachi | 1         | 3      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 30     | 50%     |
| NVMe | 14        | 14     | 25.93%  |
| SSD  | 13        | 13     | 24.07%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 50%     |
| Intenso JAJP600M1TB               | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Intenso             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1628      | 2436   | 69.69%  |
| Works    | 652       | 855    | 27.91%  |
| Malfunc  | 54        | 57     | 2.31%   |
| Failed   | 2         | 2      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1280      | 44.49%  |
| Samsung Electronics                     | 434       | 15.09%  |
| AMD                                     | 268       | 9.32%   |
| SanDisk                                 | 218       | 7.58%   |
| SK hynix                                | 142       | 4.94%   |
| Micron Technology                       | 104       | 3.61%   |
| Kingston Technology Company             | 60        | 2.09%   |
| Phison Electronics                      | 58        | 2.02%   |
| Toshiba America Info Systems            | 45        | 1.56%   |
| KIOXIA                                  | 45        | 1.56%   |
| Micron/Crucial Technology               | 40        | 1.39%   |
| Nvidia                                  | 34        | 1.18%   |
| Silicon Motion                          | 27        | 0.94%   |
| ADATA Technology                        | 26        | 0.9%    |
| Solid State Storage Technology          | 23        | 0.8%    |
| Marvell Technology Group                | 13        | 0.45%   |
| Apple                                   | 12        | 0.42%   |
| Union Memory (Shenzhen)                 | 11        | 0.38%   |
| Shenzhen Longsys Electronics            | 8         | 0.28%   |
| Realtek Semiconductor                   | 6         | 0.21%   |
| MAXIO Technology (Hangzhou)             | 5         | 0.17%   |
| Yangtze Memory Technologies             | 3         | 0.1%    |
| INNOGRIT                                | 3         | 0.1%    |
| Transcend                               | 2         | 0.07%   |
| Seagate Technology                      | 2         | 0.07%   |
| Lite-On Technology                      | 2         | 0.07%   |
| Solidigm                                | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |
| O2 Micro                                | 1         | 0.03%   |
| Netac Technology                        | 1         | 0.03%   |
| Hosin Global Electronics                | 1         | 0.03%   |
| ASMedia Technology                      | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 258       | 8.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 162       | 5.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 145       | 4.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 125       | 4.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 109       | 3.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 106       | 3.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 103       | 3.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 101       | 3.36%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 86        | 2.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 71        | 2.36%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 70        | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 67        | 2.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 61        | 2.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 54        | 1.8%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 51        | 1.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 38        | 1.27%   |
| Intel SSD 660P Series                                                          | 38        | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 37        | 1.23%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 37        | 1.23%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 36        | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                          | 34        | 1.13%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 33        | 1.1%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 32        | 1.07%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 30        | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 30        | 1%      |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 29        | 0.97%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 29        | 0.97%   |
| Intel Tiger Lake-LP SATA Controller                                            | 29        | 0.97%   |
| Phison E12 NVMe Controller                                                     | 27        | 0.9%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 26        | 0.87%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 25        | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 25        | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 24        | 0.8%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 23        | 0.77%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 22        | 0.73%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 21        | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 21        | 0.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 20        | 0.67%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 20        | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 20        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1347      | 47.53%  |
| NVMe | 1191      | 42.03%  |
| RAID | 254       | 8.96%   |
| IDE  | 42        | 1.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1696      | 76.64%  |
| AMD    | 517       | 23.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 46        | 2.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 45        | 2.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 41        | 1.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 39        | 1.76%   |
| Intel 12th Gen Core i7-12700H                 | 36        | 1.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 35        | 1.58%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 1.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 32        | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 30        | 1.36%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 1.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 29        | 1.31%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 1.26%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 28        | 1.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 28        | 1.26%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 24        | 1.08%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 24        | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 23        | 1.04%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 22        | 0.99%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 19        | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 18        | 0.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 0.81%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 18        | 0.81%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 17        | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 17        | 0.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 17        | 0.77%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.77%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 16        | 0.72%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 16        | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 15        | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.63%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 14        | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 14        | 0.63%   |
| Intel 12th Gen Core i7-1260P                  | 14        | 0.63%   |
| Intel 12th Gen Core i5-12500H                 | 14        | 0.63%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 14        | 0.63%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 13        | 0.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 13        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 541       | 24.45%  |
| Intel Core i5           | 484       | 21.87%  |
| Other                   | 382       | 17.26%  |
| AMD Ryzen 7             | 172       | 7.77%   |
| AMD Ryzen 5             | 154       | 6.96%   |
| Intel Core i3           | 108       | 4.88%   |
| Intel Celeron           | 69        | 3.12%   |
| Intel Core 2 Duo        | 59        | 2.67%   |
| AMD Ryzen 9             | 37        | 1.67%   |
| AMD Ryzen 7 PRO         | 34        | 1.54%   |
| AMD Ryzen 3             | 20        | 0.9%    |
| Intel Pentium           | 18        | 0.81%   |
| AMD A8                  | 16        | 0.72%   |
| AMD A10                 | 16        | 0.72%   |
| AMD A6                  | 14        | 0.63%   |
| Intel Core i9           | 12        | 0.54%   |
| Intel Xeon              | 7         | 0.32%   |
| Intel Pentium Dual-Core | 7         | 0.32%   |
| AMD Ryzen 5 PRO         | 7         | 0.32%   |
| Intel Pentium Silver    | 5         | 0.23%   |
| AMD E1                  | 5         | 0.23%   |
| AMD E                   | 5         | 0.23%   |
| AMD Athlon              | 5         | 0.23%   |
| AMD A4                  | 5         | 0.23%   |
| AMD E2                  | 4         | 0.18%   |
| AMD Athlon X2           | 3         | 0.14%   |
| Intel Genuine           | 2         | 0.09%   |
| Intel Core m5           | 2         | 0.09%   |
| Intel Core M            | 2         | 0.09%   |
| Intel Core 2            | 2         | 0.09%   |
| Intel Atom              | 2         | 0.09%   |
| AMD Ryzen 3 PRO         | 2         | 0.09%   |
| AMD Phenom II           | 2         | 0.09%   |
| AMD FX                  | 2         | 0.09%   |
| AMD A12                 | 2         | 0.09%   |
| Intel Pentium Gold      | 1         | 0.05%   |
| Intel Pentium Dual      | 1         | 0.05%   |
| Intel Core m3           | 1         | 0.05%   |
| Intel Core 2 Quad       | 1         | 0.05%   |
| AMD Turion II           | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 759       | 34.3%   |
| 4      | 730       | 32.99%  |
| 8      | 305       | 13.78%  |
| 6      | 244       | 11.03%  |
| 14     | 76        | 3.43%   |
| 12     | 38        | 1.72%   |
| 10     | 35        | 1.58%   |
| 16     | 11        | 0.5%    |
| 24     | 8         | 0.36%   |
| 1      | 6         | 0.27%   |
| 3      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2213      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1938      | 87.49%  |
| 1      | 277       | 12.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2213      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1766      | 78.7%   |
| 0x0a50000c | 39        | 1.74%   |
| 0x806c1    | 36        | 1.6%    |
| 0x906a3    | 23        | 1.02%   |
| 0x806d1    | 23        | 1.02%   |
| 0xa0652    | 20        | 0.89%   |
| 0x806ea    | 20        | 0.89%   |
| 0x08608103 | 20        | 0.89%   |
| 0x806ec    | 19        | 0.85%   |
| 0x08600106 | 19        | 0.85%   |
| 0x906ea    | 17        | 0.76%   |
| 0x306a9    | 16        | 0.71%   |
| 0x0a404102 | 15        | 0.67%   |
| 0x406e3    | 13        | 0.58%   |
| 0x0a50000d | 13        | 0.58%   |
| 0x0a404101 | 13        | 0.58%   |
| 0x806e9    | 12        | 0.53%   |
| 0x08108109 | 12        | 0.53%   |
| 0x40651    | 11        | 0.49%   |
| 0x08600104 | 10        | 0.45%   |
| 0x906a4    | 9         | 0.4%    |
| 0x306d4    | 8         | 0.36%   |
| 0x206a7    | 8         | 0.36%   |
| 0x1067a    | 8         | 0.36%   |
| 0x906e9    | 7         | 0.31%   |
| 0x706e5    | 7         | 0.31%   |
| 0x506e3    | 7         | 0.31%   |
| 0x306c3    | 7         | 0.31%   |
| 0x08108102 | 7         | 0.31%   |
| 0x0a704103 | 6         | 0.27%   |
| 0x08600103 | 6         | 0.27%   |
| 0x806eb    | 5         | 0.22%   |
| 0x706a8    | 4         | 0.18%   |
| 0x0a601203 | 4         | 0.18%   |
| 0x906c0    | 3         | 0.13%   |
| 0x806c2    | 3         | 0.13%   |
| 0x08608102 | 3         | 0.13%   |
| 0xa0660    | 2         | 0.09%   |
| 0x906ed    | 2         | 0.09%   |
| 0x0a704101 | 2         | 0.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 415       | 18.69%  |
| Unknown          | 265       | 11.93%  |
| Haswell          | 179       | 8.06%   |
| TigerLake        | 136       | 6.12%   |
| Zen 3            | 130       | 5.85%   |
| SandyBridge      | 129       | 5.81%   |
| IvyBridge        | 110       | 4.95%   |
| Skylake          | 104       | 4.68%   |
| Broadwell        | 90        | 4.05%   |
| Alderlake Hybrid | 84        | 3.78%   |
| CometLake        | 79        | 3.56%   |
| Zen+             | 78        | 3.51%   |
| Zen 2            | 76        | 3.42%   |
| Penryn           | 63        | 2.84%   |
| IceLake          | 59        | 2.66%   |
| Westmere         | 43        | 1.94%   |
| Goldmont plus    | 32        | 1.44%   |
| Silvermont       | 27        | 1.22%   |
| Excavator        | 22        | 0.99%   |
| Zen              | 17        | 0.77%   |
| Puma             | 17        | 0.77%   |
| Piledriver       | 13        | 0.59%   |
| Core             | 9         | 0.41%   |
| K10 Llano        | 8         | 0.36%   |
| Bobcat           | 8         | 0.36%   |
| Goldmont         | 6         | 0.27%   |
| Steamroller      | 5         | 0.23%   |
| Nehalem          | 4         | 0.18%   |
| Tremont          | 3         | 0.14%   |
| K8 Hammer        | 3         | 0.14%   |
| K10              | 3         | 0.14%   |
| Jaguar           | 3         | 0.14%   |
| K8 & K10 hybrid  | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1560      | 52.67%  |
| Nvidia | 802       | 27.08%  |
| AMD    | 600       | 20.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 126       | 4.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 114       | 3.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 107       | 3.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 103       | 3.4%    |
| Intel UHD Graphics 620                                                                | 97        | 3.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 91        | 3.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 87        | 2.87%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 83        | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 77        | 2.54%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 75        | 2.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 69        | 2.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 65        | 2.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 60        | 1.98%   |
| Intel HD Graphics 5500                                                                | 60        | 1.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 60        | 1.98%   |
| Intel HD Graphics 620                                                                 | 59        | 1.95%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 58        | 1.92%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 57        | 1.88%   |
| AMD Lucienne                                                                          | 57        | 1.88%   |
| AMD Rembrandt [Radeon 680M]                                                           | 53        | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 49        | 1.62%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 48        | 1.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 48        | 1.59%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 42        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                   | 36        | 1.19%   |
| Intel HD Graphics 630                                                                 | 34        | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 29        | 0.96%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 27        | 0.89%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 25        | 0.83%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 24        | 0.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 24        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 23        | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 23        | 0.76%   |
| Intel HD Graphics 530                                                                 | 23        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 21        | 0.69%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 20        | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 19        | 0.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 18        | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 16        | 0.53%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 16        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 963       | 43.32%  |
| Intel + Nvidia     | 524       | 23.57%  |
| 1 x AMD            | 342       | 15.38%  |
| AMD + Nvidia       | 145       | 6.52%   |
| 1 x Nvidia         | 125       | 5.62%   |
| Intel + AMD        | 68        | 3.06%   |
| 2 x AMD            | 46        | 2.07%   |
| 2 x Nvidia         | 4         | 0.18%   |
| Other              | 3         | 0.13%   |
| Intel + 2 x Nvidia | 2         | 0.09%   |
| 2 x Intel          | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1573      | 70.47%  |
| Proprietary | 628       | 28.14%  |
| Unknown     | 31        | 1.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1941      | 86.96%  |
| 0.01-0.5   | 105       | 4.7%    |
| 1.01-2.0   | 56        | 2.51%   |
| 3.01-4.0   | 42        | 1.88%   |
| 7.01-8.0   | 31        | 1.39%   |
| 5.01-6.0   | 31        | 1.39%   |
| 0.51-1.0   | 17        | 0.76%   |
| 8.01-16.0  | 6         | 0.27%   |
| 2.01-3.0   | 3         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 474       | 18.12%  |
| BOE                     | 408       | 15.6%   |
| Chimei Innolux          | 376       | 14.37%  |
| LG Display              | 314       | 12%     |
| Samsung Electronics     | 202       | 7.72%   |
| Apple                   | 129       | 4.93%   |
| Dell                    | 90        | 3.44%   |
| Sharp                   | 89        | 3.4%    |
| Goldstar                | 74        | 2.83%   |
| PANDA                   | 61        | 2.33%   |
| Lenovo                  | 39        | 1.49%   |
| InfoVision              | 34        | 1.3%    |
| Chi Mei Optoelectronics | 29        | 1.11%   |
| CSO                     | 28        | 1.07%   |
| Acer                    | 28        | 1.07%   |
| Hewlett-Packard         | 24        | 0.92%   |
| AOC                     | 21        | 0.8%    |
| Philips                 | 19        | 0.73%   |
| ASUSTek Computer        | 18        | 0.69%   |
| BenQ                    | 14        | 0.54%   |
| Ancor Communications    | 13        | 0.5%    |
| Iiyama                  | 11        | 0.42%   |
| TMX                     | 10        | 0.38%   |
| ViewSonic               | 8         | 0.31%   |
| MSI                     | 7         | 0.27%   |
| Panasonic               | 6         | 0.23%   |
| NEC Computers           | 5         | 0.19%   |
| HKC                     | 5         | 0.19%   |
| Vestel Elektronik       | 4         | 0.15%   |
| Sony                    | 4         | 0.15%   |
| Vizio                   | 3         | 0.11%   |
| TCL                     | 3         | 0.11%   |
| RTK                     | 3         | 0.11%   |
| JDI                     | 3         | 0.11%   |
| HUAWEI                  | 3         | 0.11%   |
| Hitachi                 | 3         | 0.11%   |
| Gigabyte Technology     | 3         | 0.11%   |
| Unknown                 | 2         | 0.08%   |
| Toshiba                 | 2         | 0.08%   |
| Sceptre Tech            | 2         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 26        | 0.98%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 25        | 0.95%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 22        | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 21        | 0.79%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 20        | 0.76%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 18        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 14        | 0.53%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 13        | 0.49%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 13        | 0.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 13        | 0.49%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 13        | 0.49%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 12        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 12        | 0.45%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 12        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 11        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 11        | 0.42%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 11        | 0.42%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 10        | 0.38%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 10        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 9         | 0.34%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.34%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 9         | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 8         | 0.3%    |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 8         | 0.3%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 8         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 7         | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 7         | 0.26%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 7         | 0.26%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                 | 7         | 0.26%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 7         | 0.26%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 7         | 0.26%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                | 7         | 0.26%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                  | 7         | 0.26%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 7         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1201      | 48.96%  |
| 1366x768 (WXGA)    | 490       | 19.98%  |
| 3840x2160 (4K)     | 117       | 4.77%   |
| 2560x1440 (QHD)    | 103       | 4.2%    |
| 1600x900 (HD+)     | 80        | 3.26%   |
| 1920x1200 (WUXGA)  | 79        | 3.22%   |
| 2560x1600          | 68        | 2.77%   |
| 2880x1800          | 48        | 1.96%   |
| 1440x900 (WXGA+)   | 46        | 1.88%   |
| 1280x800 (WXGA)    | 46        | 1.88%   |
| 3440x1440          | 20        | 0.82%   |
| 2560x1080          | 20        | 0.82%   |
| 3840x2400          | 19        | 0.77%   |
| 3072x1920          | 12        | 0.49%   |
| 1680x1050 (WSXGA+) | 12        | 0.49%   |
| 2160x1440          | 10        | 0.41%   |
| 1280x1024 (SXGA)   | 9         | 0.37%   |
| 2256x1504          | 8         | 0.33%   |
| 3200x1800 (QHD+)   | 7         | 0.29%   |
| 1360x768           | 6         | 0.24%   |
| 3840x1080          | 5         | 0.2%    |
| 3456x2160          | 5         | 0.2%    |
| 3200x2000          | 5         | 0.2%    |
| 2240x1400          | 4         | 0.16%   |
| 1920x1280          | 4         | 0.16%   |
| 3840x1100          | 3         | 0.12%   |
| 2880x1620          | 3         | 0.12%   |
| 1920x540           | 3         | 0.12%   |
| 1280x720 (HD)      | 3         | 0.12%   |
| 800x1280           | 2         | 0.08%   |
| 3000x2000          | 2         | 0.08%   |
| 2520x1680          | 2         | 0.08%   |
| 2304x1440          | 2         | 0.08%   |
| 3840x1200          | 1         | 0.04%   |
| 3120x2080          | 1         | 0.04%   |
| 2560x1700          | 1         | 0.04%   |
| 1920x515           | 1         | 0.04%   |
| 1600x2560          | 1         | 0.04%   |
| 1600x1200          | 1         | 0.04%   |
| 1400x1050          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1042      | 39.89%  |
| 13      | 418       | 16%     |
| 14      | 310       | 11.87%  |
| 17      | 170       | 6.51%   |
| 27      | 105       | 4.02%   |
| 16      | 90        | 3.45%   |
| 24      | 85        | 3.25%   |
| 23      | 63        | 2.41%   |
| 12      | 48        | 1.84%   |
| 21      | 46        | 1.76%   |
| 31      | 36        | 1.38%   |
| 34      | 34        | 1.3%    |
| 11      | 29        | 1.11%   |
| 19      | 16        | 0.61%   |
| 18      | 14        | 0.54%   |
| 32      | 13        | 0.5%    |
| Unknown | 11        | 0.42%   |
| 84      | 10        | 0.38%   |
| 40      | 10        | 0.38%   |
| 22      | 9         | 0.34%   |
| 20      | 6         | 0.23%   |
| 72      | 5         | 0.19%   |
| 48      | 5         | 0.19%   |
| 35      | 5         | 0.19%   |
| 54      | 4         | 0.15%   |
| 28      | 4         | 0.15%   |
| 49      | 3         | 0.11%   |
| 29      | 3         | 0.11%   |
| 33      | 2         | 0.08%   |
| 26      | 2         | 0.08%   |
| 25      | 2         | 0.08%   |
| 74      | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 43      | 1         | 0.04%   |
| 42      | 1         | 0.04%   |
| 39      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1616      | 62.42%  |
| 201-300     | 294       | 11.36%  |
| 501-600     | 227       | 8.77%   |
| 351-400     | 199       | 7.69%   |
| 401-500     | 82        | 3.17%   |
| 601-700     | 58        | 2.24%   |
| 701-800     | 49        | 1.89%   |
| 801-900     | 16        | 0.62%   |
| 1501-2000   | 16        | 0.62%   |
| 1001-1500   | 16        | 0.62%   |
| Unknown     | 11        | 0.42%   |
| 901-1000    | 2         | 0.08%   |
| 1-100       | 2         | 0.08%   |
| 101-200     | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1847      | 80.3%   |
| 16/10   | 350       | 15.22%  |
| 21/9    | 43        | 1.87%   |
| 3/2     | 30        | 1.3%    |
| 5/4     | 10        | 0.43%   |
| 32/9    | 6         | 0.26%   |
| 3.40    | 3         | 0.13%   |
| Unknown | 3         | 0.13%   |
| 4/3     | 2         | 0.09%   |
| 6/5     | 1         | 0.04%   |
| 3.73    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 0.67    | 1         | 0.04%   |
| 0.63    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1045      | 40.05%  |
| 81-90          | 570       | 21.85%  |
| 201-250        | 169       | 6.48%   |
| 121-130        | 157       | 6.02%   |
| 71-80          | 145       | 5.56%   |
| 301-350        | 107       | 4.1%    |
| 351-500        | 92        | 3.53%   |
| 111-120        | 83        | 3.18%   |
| 61-70          | 46        | 1.76%   |
| 151-200        | 34        | 1.3%    |
| 51-60          | 32        | 1.23%   |
| 251-300        | 26        | 1%      |
| More than 1000 | 25        | 0.96%   |
| 501-1000       | 21        | 0.8%    |
| 141-150        | 17        | 0.65%   |
| 131-140        | 13        | 0.5%    |
| 91-100         | 13        | 0.5%    |
| Unknown        | 11        | 0.42%   |
| 1-40           | 3         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1193      | 46.58%  |
| 101-120       | 602       | 23.51%  |
| 51-100        | 335       | 13.08%  |
| 161-240       | 275       | 10.74%  |
| More than 240 | 119       | 4.65%   |
| 1-50          | 26        | 1.02%   |
| Unknown       | 11        | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1745      | 77.45%  |
| 2     | 394       | 17.49%  |
| 3     | 59        | 2.62%   |
| 0     | 52        | 2.31%   |
| 4     | 3         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1206      | 34.68%  |
| Intel                             | 1170      | 33.64%  |
| Qualcomm Atheros                  | 381       | 10.95%  |
| Broadcom                          | 208       | 5.98%   |
| MediaTek                          | 126       | 3.62%   |
| Broadcom Limited                  | 78        | 2.24%   |
| ASIX Electronics                  | 37        | 1.06%   |
| Samsung Electronics               | 20        | 0.58%   |
| Ralink                            | 20        | 0.58%   |
| Nvidia                            | 20        | 0.58%   |
| TP-Link                           | 18        | 0.52%   |
| Marvell Technology Group          | 18        | 0.52%   |
| DisplayLink                       | 16        | 0.46%   |
| Dell                              | 16        | 0.46%   |
| Xiaomi                            | 14        | 0.4%    |
| Qualcomm                          | 14        | 0.4%    |
| Ralink Technology                 | 12        | 0.35%   |
| Sierra Wireless                   | 10        | 0.29%   |
| Lenovo                            | 10        | 0.29%   |
| JMicron Technology                | 8         | 0.23%   |
| Hewlett-Packard                   | 8         | 0.23%   |
| ASUSTek Computer                  | 8         | 0.23%   |
| OPPO Electronics                  | 7         | 0.2%    |
| OnePlus Technology (Shenzhen)     | 5         | 0.14%   |
| NetGear                           | 5         | 0.14%   |
| Google                            | 5         | 0.14%   |
| Ericsson Business Mobile Networks | 5         | 0.14%   |
| Motorola PCS                      | 4         | 0.12%   |
| Qualcomm Atheros Communications   | 3         | 0.09%   |
| Huawei Technologies               | 3         | 0.09%   |
| Fibocom                           | 3         | 0.09%   |
| Edimax Technology                 | 3         | 0.09%   |
| Linksys                           | 2         | 0.06%   |
| D-Link                            | 2         | 0.06%   |
| Arduino SA                        | 2         | 0.06%   |
| Apple                             | 2         | 0.06%   |
| ZyDAS                             | 1         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| U-Blox                            | 1         | 0.03%   |
| Shenzhen Goodix Technology        | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 746       | 18.1%   |
| Intel Wi-Fi 6 AX200                                                  | 139       | 3.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 123       | 2.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 116       | 2.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 106       | 2.57%   |
| Intel Wi-Fi 6 AX201                                                  | 104       | 2.52%   |
| Intel Wireless 8265 / 8275                                           | 101       | 2.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 77        | 1.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 72        | 1.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 72        | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 68        | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 65        | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 61        | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 59        | 1.43%   |
| Intel Wireless 8260                                                  | 57        | 1.38%   |
| Intel Wireless 7265                                                  | 53        | 1.29%   |
| Intel Wireless 7260                                                  | 53        | 1.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 53        | 1.29%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 50        | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 47        | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 43        | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 39        | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                | 38        | 0.92%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 38        | 0.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 37        | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                    | 37        | 0.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 37        | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 37        | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 36        | 0.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 35        | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 32        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                        | 31        | 0.75%   |
| Intel Ethernet Connection I219-LM                                    | 30        | 0.73%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 29        | 0.7%    |
| Broadcom BCM43142 802.11b/g/n                                        | 28        | 0.68%   |
| Intel Ethernet Connection I217-LM                                    | 27        | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 27        | 0.66%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 27        | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 25        | 0.61%   |
| Intel Wireless-AC 9260                                               | 23        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1134      | 49.01%  |
| Realtek Semiconductor                 | 362       | 15.64%  |
| Qualcomm Atheros                      | 326       | 14.09%  |
| Broadcom                              | 180       | 7.78%   |
| MediaTek                              | 125       | 5.4%    |
| Broadcom Limited                      | 68        | 2.94%   |
| Ralink                                | 20        | 0.86%   |
| TP-Link                               | 15        | 0.65%   |
| Dell                                  | 15        | 0.65%   |
| Qualcomm                              | 13        | 0.56%   |
| Ralink Technology                     | 12        | 0.52%   |
| Sierra Wireless                       | 10        | 0.43%   |
| ASUSTek Computer                      | 6         | 0.26%   |
| NetGear                               | 5         | 0.22%   |
| Hewlett-Packard                       | 4         | 0.17%   |
| Qualcomm Atheros Communications       | 3         | 0.13%   |
| Fibocom                               | 3         | 0.13%   |
| Edimax Technology                     | 3         | 0.13%   |
| Linksys                               | 2         | 0.09%   |
| D-Link                                | 2         | 0.09%   |
| ZyDAS                                 | 1         | 0.04%   |
| Ericsson Business Mobile Networks     | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| Arduino SA                            | 1         | 0.04%   |
| Accton Technology                     | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 139       | 5.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 106       | 4.56%   |
| Intel Wi-Fi 6 AX201                                                  | 104       | 4.47%   |
| Intel Wireless 8265 / 8275                                           | 101       | 4.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 77        | 3.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 72        | 3.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 72        | 3.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 68        | 2.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 65        | 2.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 61        | 2.62%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 59        | 2.54%   |
| Intel Wireless 8260                                                  | 57        | 2.45%   |
| Intel Wireless 7265                                                  | 53        | 2.28%   |
| Intel Wireless 7260                                                  | 53        | 2.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 50        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 47        | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 43        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 39        | 1.68%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 38        | 1.63%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 37        | 1.59%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 37        | 1.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 37        | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 36        | 1.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 35        | 1.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 32        | 1.38%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 29        | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                        | 28        | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 27        | 1.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 27        | 1.16%   |
| Intel Wireless-AC 9260                                               | 23        | 0.99%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 20        | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 19        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 17        | 0.73%   |
| Intel Centrino Ultimate-N 6300                                       | 17        | 0.73%   |
| Intel Centrino Advanced-N 6235                                       | 17        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 16        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 16        | 0.69%   |
| Intel Wireless 3160                                                  | 16        | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 16        | 0.69%   |
| Realtek 802.11ac NIC                                                 | 15        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 1048      | 60.06%  |
| Intel                         | 352       | 20.17%  |
| Qualcomm Atheros              | 92        | 5.27%   |
| Broadcom                      | 74        | 4.24%   |
| ASIX Electronics              | 37        | 2.12%   |
| Nvidia                        | 20        | 1.15%   |
| Marvell Technology Group      | 18        | 1.03%   |
| DisplayLink                   | 16        | 0.92%   |
| Xiaomi                        | 14        | 0.8%    |
| Samsung Electronics           | 11        | 0.63%   |
| Lenovo                        | 10        | 0.57%   |
| Broadcom Limited              | 10        | 0.57%   |
| JMicron Technology            | 8         | 0.46%   |
| OPPO Electronics              | 7         | 0.4%    |
| OnePlus Technology (Shenzhen) | 5         | 0.29%   |
| Google                        | 5         | 0.29%   |
| TP-Link                       | 3         | 0.17%   |
| Motorola PCS                  | 3         | 0.17%   |
| Hewlett-Packard               | 3         | 0.17%   |
| Huawei Technologies           | 2         | 0.11%   |
| ASUSTek Computer              | 2         | 0.11%   |
| Apple                         | 2         | 0.11%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.06%   |
| Qualcomm                      | 1         | 0.06%   |
| ICS Advent                    | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 746       | 42.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 123       | 6.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 116       | 6.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53        | 2.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 38        | 2.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 2.09%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 30        | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 27        | 1.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 25        | 1.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 19        | 1.07%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 1.07%   |
| Nvidia MCP79 Ethernet                                             | 18        | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 14        | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13        | 0.73%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 13        | 0.73%   |
| Intel Ethernet Connection (13) I219-V                             | 12        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 11        | 0.62%   |
| Intel Ethernet Connection (16) I219-V                             | 11        | 0.62%   |
| Realtek Killer E3000 2.5GbE Controller                            | 10        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 10        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.45%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 8         | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 7         | 0.4%    |
| Intel Ethernet Connection I219-V                                  | 7         | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 7         | 0.4%    |
| Intel Ethernet Connection (16) I219-LM                            | 7         | 0.4%    |
| Intel Ethernet Connection (13) I219-LM                            | 7         | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2191      | 56.63%  |
| Ethernet | 1654      | 42.75%  |
| Modem    | 20        | 0.52%   |
| Unknown  | 4         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1864      | 79.49%  |
| Ethernet | 481       | 20.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1487      | 67.19%  |
| 1     | 694       | 31.36%  |
| 0     | 22        | 0.99%   |
| 3     | 10        | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1562      | 69.67%  |
| Yes  | 680       | 30.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1000      | 52.06%  |
| Realtek Semiconductor           | 207       | 10.78%  |
| Qualcomm Atheros Communications | 158       | 8.22%   |
| Apple                           | 134       | 6.98%   |
| IMC Networks                    | 113       | 5.88%   |
| Foxconn / Hon Hai               | 86        | 4.48%   |
| Lite-On Technology              | 69        | 3.59%   |
| Broadcom                        | 45        | 2.34%   |
| Dell                            | 19        | 0.99%   |
| Realtek                         | 13        | 0.68%   |
| Cambridge Silicon Radio         | 13        | 0.68%   |
| Toshiba                         | 12        | 0.62%   |
| MediaTek                        | 9         | 0.47%   |
| Hewlett-Packard                 | 9         | 0.47%   |
| Ralink                          | 8         | 0.42%   |
| Foxconn International           | 4         | 0.21%   |
| ASUSTek Computer                | 4         | 0.21%   |
| Opticis                         | 3         | 0.16%   |
| USI                             | 2         | 0.1%    |
| TP-Link                         | 2         | 0.1%    |
| Taiyo Yuden                     | 2         | 0.1%    |
| Smart Modular Technologies      | 2         | 0.1%    |
| Ralink Technology               | 2         | 0.1%    |
| Fujitsu                         | 2         | 0.1%    |
| Micro Star International        | 1         | 0.05%   |
| Integrated System Solution      | 1         | 0.05%   |
| Actions                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 351       | 18.26%  |
| Intel Bluetooth wireless interface                  | 280       | 14.57%  |
| Realtek Bluetooth Radio                             | 149       | 7.75%   |
| Intel AX200 Bluetooth                               | 136       | 7.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 121       | 6.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 88        | 4.58%   |
| Apple Bluetooth Host Controller                     | 73        | 3.8%    |
| Apple Bluetooth USB Host Controller                 | 50        | 2.6%    |
| IMC Networks Wireless_Device                        | 49        | 2.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 40        | 2.08%   |
| Intel AX210 Bluetooth                               | 35        | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 24        | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 24        | 1.25%   |
| IMC Networks Bluetooth Radio                        | 23        | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 20        | 1.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 19        | 0.99%   |
| IMC Networks Bluetooth Device                       | 19        | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 17        | 0.88%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 16        | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 0.78%   |
| Lite-On Wireless_Device                             | 15        | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 15        | 0.78%   |
| Lite-On Bluetooth Device                            | 14        | 0.73%   |
| Realtek Bluetooth Radio                             | 13        | 0.68%   |
| Foxconn / Hon Hai Bluetooth Adapter                 | 13        | 0.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 0.62%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.52%   |
| MediaTek Wireless_Device                            | 9         | 0.47%   |
| Broadcom BCM2045B (BDC-2.1)                         | 9         | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.42%   |
| Ralink RT3290 Bluetooth                             | 8         | 0.42%   |
| Lite-On Bluetooth Radio                             | 7         | 0.36%   |
| Dell DW375 Bluetooth Module                         | 7         | 0.36%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.31%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 6         | 0.31%   |
| IMC Networks Bluetooth USB Host Controller          | 6         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1657      | 56.09%  |
| AMD                                             | 550       | 18.62%  |
| Nvidia                                          | 528       | 17.87%  |
| C-Media Electronics                             | 23        | 0.78%   |
| Logitech                                        | 19        | 0.64%   |
| GN Netcom                                       | 15        | 0.51%   |
| Lenovo                                          | 14        | 0.47%   |
| Generalplus Technology                          | 13        | 0.44%   |
| Realtek Semiconductor                           | 12        | 0.41%   |
| Kingston Technology                             | 12        | 0.41%   |
| JMTek                                           | 10        | 0.34%   |
| Sony                                            | 9         | 0.3%    |
| Apple                                           | 9         | 0.3%    |
| Hewlett-Packard                                 | 8         | 0.27%   |
| Texas Instruments                               | 7         | 0.24%   |
| Plantronics                                     | 7         | 0.24%   |
| Focusrite-Novation                              | 6         | 0.2%    |
| SteelSeries ApS                                 | 5         | 0.17%   |
| Razer USA                                       | 5         | 0.17%   |
| Corsair                                         | 5         | 0.17%   |
| ASUSTek Computer                                | 4         | 0.14%   |
| DSEA A/S                                        | 3         | 0.1%    |
| Turtle Beach                                    | 2         | 0.07%   |
| TerraTec Electronic                             | 2         | 0.07%   |
| Sennheiser Communications                       | 2         | 0.07%   |
| Samson Technologies                             | 2         | 0.07%   |
| FiiO Electronics Technology                     | 2         | 0.07%   |
| Yamaha                                          | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.03%   |
| STMicroelectronics                              | 1         | 0.03%   |
| Samsung Electronics                             | 1         | 0.03%   |
| Reloop                                          | 1         | 0.03%   |
| Pioneer DJ                                      | 1         | 0.03%   |
| ONN                                             | 1         | 0.03%   |
| Nordic Semiconductor ASA                        | 1         | 0.03%   |
| No brand                                        | 1         | 0.03%   |
| Midiplus                                        | 1         | 0.03%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.03%   |
| iConnectivity                                   | 1         | 0.03%   |
| GYROCOM C&C                                     | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 418       | 11.45%  |
| Intel Sunrise Point-LP HD Audio                                            | 237       | 6.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 214       | 5.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 136       | 3.73%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 132       | 3.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 126       | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 113       | 3.1%    |
| Nvidia Audio device                                                        | 103       | 2.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 102       | 2.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 92        | 2.52%   |
| Intel Broadwell-U Audio Controller                                         | 90        | 2.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 88        | 2.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 88        | 2.41%   |
| Intel 8 Series HD Audio Controller                                         | 87        | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 82        | 2.25%   |
| Intel Comet Lake PCH cAVS                                                  | 70        | 1.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 64        | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 63        | 1.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 61        | 1.67%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 60        | 1.64%   |
| Nvidia GA106 High Definition Audio Controller                              | 58        | 1.59%   |
| Intel Comet Lake PCH-LP cAVS                                               | 58        | 1.59%   |
| Nvidia GA104 High Definition Audio Controller                              | 54        | 1.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 51        | 1.4%    |
| AMD FCH Azalia Controller                                                  | 50        | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 47        | 1.29%   |
| Nvidia TU106 High Definition Audio Controller                              | 43        | 1.18%   |
| Intel CM238 HD Audio Controller                                            | 43        | 1.18%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 32        | 0.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 31        | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 31        | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 26        | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 25        | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 24        | 0.66%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 24        | 0.66%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 22        | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                            | 21        | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 21        | 0.58%   |
| Nvidia MCP79 High Definition Audio                                         | 20        | 0.55%   |
| Nvidia GK107 HDMI Audio Controller                                         | 20        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 250       | 29.17%  |
| SK hynix                                | 203       | 23.69%  |
| Micron Technology                       | 136       | 15.87%  |
| Kingston                                | 55        | 6.42%   |
| Crucial                                 | 45        | 5.25%   |
| Unknown                                 | 18        | 2.1%    |
| Unknown                                 | 17        | 1.98%   |
| A-DATA Technology                       | 15        | 1.75%   |
| Smart                                   | 13        | 1.52%   |
| Corsair                                 | 12        | 1.4%    |
| Ramaxel Technology                      | 11        | 1.28%   |
| Neo Forza                               | 9         | 1.05%   |
| Goldkey                                 | 9         | 1.05%   |
| G.Skill                                 | 9         | 1.05%   |
| Team                                    | 8         | 0.93%   |
| Elpida                                  | 7         | 0.82%   |
| Unknown (ABCD)                          | 5         | 0.58%   |
| PNY                                     | 4         | 0.47%   |
| Transcend                               | 3         | 0.35%   |
| Nanya Technology                        | 3         | 0.35%   |
| GSkill                                  | 3         | 0.35%   |
| Timetec                                 | 2         | 0.23%   |
| Teikon                                  | 2         | 0.23%   |
| Smart Brazil                            | 2         | 0.23%   |
| Gold Key                                | 2         | 0.23%   |
| ChangXin Memory                         | 2         | 0.23%   |
| Avant                                   | 2         | 0.23%   |
| Wilk                                    | 1         | 0.12%   |
| Unknown (8A02)                          | 1         | 0.12%   |
| Unknown (0x0CAB)                        | 1         | 0.12%   |
| Unknown (09B6)                          | 1         | 0.12%   |
| Unknown (09A4)                          | 1         | 0.12%   |
| Silicon Power Computer & Communications | 1         | 0.12%   |
| Kllisre                                 | 1         | 0.12%   |
| HT Micron                               | 1         | 0.12%   |
| CSX                                     | 1         | 0.12%   |
| Apacer                                  | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 21        | 2.34%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 2.12%   |
| Unknown                                                          | 17        | 1.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 1.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 1.56%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 13        | 1.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.11%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 10        | 1.11%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.11%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1%      |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 1%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 1%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 0.89%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 8         | 0.89%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 8         | 0.89%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 7         | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 7         | 0.78%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.78%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.78%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 6         | 0.67%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.67%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.67%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.67%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 6         | 0.67%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.67%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.56%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.56%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 5         | 0.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.56%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 5         | 0.56%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 5         | 0.56%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 5         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.56%   |
| Goldkey RAM GKE800SO102408-2666A 8GB SODIMM DDR4 2667MT/s        | 5         | 0.56%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 4         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 452       | 62.17%  |
| DDR3   | 110       | 15.13%  |
| DDR5   | 58        | 7.98%   |
| LPDDR4 | 42        | 5.78%   |
| LPDDR5 | 36        | 4.95%   |
| LPDDR3 | 22        | 3.03%   |
| SDRAM  | 4         | 0.55%   |
| DDR2   | 3         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 622       | 83.6%   |
| Row Of Chips | 114       | 15.32%  |
| Chip         | 4         | 0.54%   |
| Unknown      | 3         | 0.4%    |
| DIMM         | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 358       | 45.49%  |
| 16384 | 177       | 22.49%  |
| 4096  | 160       | 20.33%  |
| 32768 | 51        | 6.48%   |
| 2048  | 36        | 4.57%   |
| 1024  | 5         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 259       | 33.25%  |
| 2667  | 159       | 20.41%  |
| 1600  | 80        | 10.27%  |
| 2400  | 49        | 6.29%   |
| 4800  | 48        | 6.16%   |
| 2133  | 36        | 4.62%   |
| 6400  | 35        | 4.49%   |
| 4267  | 24        | 3.08%   |
| 1867  | 12        | 1.54%   |
| 5600  | 10        | 1.28%   |
| 1334  | 10        | 1.28%   |
| 3266  | 9         | 1.16%   |
| 8400  | 8         | 1.03%   |
| 1333  | 8         | 1.03%   |
| 1067  | 7         | 0.9%    |
| 4266  | 6         | 0.77%   |
| 3733  | 4         | 0.51%   |
| 800   | 3         | 0.39%   |
| 4199  | 2         | 0.26%   |
| 2933  | 2         | 0.26%   |
| 2048  | 2         | 0.26%   |
| 5500  | 1         | 0.13%   |
| 5200  | 1         | 0.13%   |
| 3000  | 1         | 0.13%   |
| 1200  | 1         | 0.13%   |
| 1066  | 1         | 0.13%   |
| 666   | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 25%     |
| Canon               | 3         | 25%     |
| Xerox               | 1         | 8.33%   |
| Seiko Epson         | 1         | 8.33%   |
| Samsung Electronics | 1         | 8.33%   |
| ICS Advent          | 1         | 8.33%   |
| Dymo-CoStar         | 1         | 8.33%   |
| Brother Industries  | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon PIXMA MX920 Series        | 2         | 16.67%  |
| Xerox B215                      | 1         | 8.33%   |
| Seiko Epson L382 Series         | 1         | 8.33%   |
| Samsung M2020 Series            | 1         | 8.33%   |
| ICS Advent Parallel Adapter     | 1         | 8.33%   |
| HP OfficeJet 3830 series        | 1         | 8.33%   |
| HP Ink Tank Wireless 410 series | 1         | 8.33%   |
| HP Color LaserJet CP2025dn      | 1         | 8.33%   |
| Dymo-CoStar LabelWriter 450     | 1         | 8.33%   |
| Canon E400 series               | 1         | 8.33%   |
| Brother HL-L2370DW series       | 1         | 8.33%   |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 441       | 21.86%  |
| IMC Networks                           | 218       | 10.81%  |
| Microdia                               | 192       | 9.52%   |
| Bison Electronics                      | 167       | 8.28%   |
| Realtek Semiconductor                  | 156       | 7.73%   |
| Quanta                                 | 130       | 6.45%   |
| Sunplus Innovation Technology          | 101       | 5.01%   |
| Apple                                  | 94        | 4.66%   |
| Luxvisions Innotech Limited            | 66        | 3.27%   |
| Acer                                   | 65        | 3.22%   |
| Cheng Uei Precision Industry (Foxlink) | 55        | 2.73%   |
| Syntek                                 | 50        | 2.48%   |
| Lite-On Technology                     | 41        | 2.03%   |
| Suyin                                  | 29        | 1.44%   |
| Sonix Technology                       | 28        | 1.39%   |
| Logitech                               | 25        | 1.24%   |
| Silicon Motion                         | 23        | 1.14%   |
| SunplusIT                              | 16        | 0.79%   |
| Samsung Electronics                    | 15        | 0.74%   |
| Alcor Micro                            | 12        | 0.59%   |
| Z-Star Microelectronics                | 8         | 0.4%    |
| Ricoh                                  | 6         | 0.3%    |
| Primax Electronics                     | 6         | 0.3%    |
| Microsoft                              | 6         | 0.3%    |
| Razer USA                              | 5         | 0.25%   |
| Shinetech                              | 4         | 0.2%    |
| Lenovo                                 | 4         | 0.2%    |
| icSpring                               | 4         | 0.2%    |
| Generalplus Technology                 | 4         | 0.2%    |
| ALi                                    | 4         | 0.2%    |
| Tobii Technology AB                    | 3         | 0.15%   |
| Importek                               | 3         | 0.15%   |
| HRY                                    | 3         | 0.15%   |
| AVerMedia Technologies                 | 3         | 0.15%   |
| Y Media                                | 2         | 0.1%    |
| OmniVision Technologies                | 2         | 0.1%    |
| Intel                                  | 2         | 0.1%    |
| Goodong                                | 2         | 0.1%    |
| Trust                                  | 1         | 0.05%   |
| Tripath Technology                     | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 105       | 5.18%   |
| Chicony Integrated Camera                           | 105       | 5.18%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 77        | 3.8%    |
| Realtek Integrated_Webcam_HD                        | 64        | 3.16%   |
| IMC Networks Integrated Camera                      | 55        | 2.71%   |
| Chicony HD Webcam                                   | 45        | 2.22%   |
| Bison Integrated Camera                             | 44        | 2.17%   |
| Acer BisonCam,NB Pro                                | 40        | 1.97%   |
| Syntek Integrated Camera                            | 38        | 1.87%   |
| Chicony USB2.0 Camera                               | 36        | 1.78%   |
| Sunplus Integrated_Webcam_HD                        | 35        | 1.73%   |
| Bison HD Webcam                                     | 34        | 1.68%   |
| Apple Built-in iSight                               | 29        | 1.43%   |
| Quanta HD User Facing                               | 28        | 1.38%   |
| Apple FaceTime HD Camera                            | 26        | 1.28%   |
| Quanta HP HD Camera                                 | 22        | 1.09%   |
| Chicony HP HD Camera                                | 22        | 1.09%   |
| Apple iPhone 5/5C/5S/6/SE                           | 22        | 1.09%   |
| Sonix USB2.0 HD UVC WebCam                          | 20        | 0.99%   |
| Realtek USB camera                                  | 20        | 0.99%   |
| Chicony HD User Facing                              | 19        | 0.94%   |
| Lite-On Integrated Camera                           | 18        | 0.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 18        | 0.89%   |
| Quanta HP TrueVision HD Camera                      | 17        | 0.84%   |
| Microdia Integrated Webcam                          | 16        | 0.79%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 16        | 0.79%   |
| Bison SunplusIT Integrated Camera                   | 16        | 0.79%   |
| Samsung Galaxy series, misc. (MTP mode)             | 15        | 0.74%   |
| Chicony USB2.0 VGA UVC WebCam                       | 14        | 0.69%   |
| Chicony HP Truevision HD camera                     | 14        | 0.69%   |
| Realtek Integrated Webcam                           | 13        | 0.64%   |
| Luxvisions Innotech Limited Integrated Camera       | 13        | 0.64%   |
| Luxvisions Innotech Limited HP HD Camera            | 13        | 0.64%   |
| Chicony USB 2.0 Camera                              | 13        | 0.64%   |
| Chicony Integrated IR Camera                        | 13        | 0.64%   |
| Chicony Integrated Camera (1280x720@30)             | 13        | 0.64%   |
| Bison Lenovo EasyCamera                             | 13        | 0.64%   |
| Chicony HP Wide Vision HD Camera                    | 12        | 0.59%   |
| Quanta ACER HD User Facing                          | 11        | 0.54%   |
| Apple FaceTime HD Camera (Built-in)                 | 11        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 136       | 35.7%   |
| Validity Sensors                   | 105       | 27.56%  |
| Shenzhen Goodix Technology         | 67        | 17.59%  |
| Elan Microelectronics              | 22        | 5.77%   |
| Upek                               | 16        | 4.2%    |
| LighTuning Technology              | 14        | 3.67%   |
| AuthenTec                          | 8         | 2.1%    |
| Realtek USB2.0 Finger Print Bridge | 5         | 1.31%   |
| Focal-systems.Corp                 | 5         | 1.31%   |
| HOLTEK                             | 3         | 0.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 38        | 9.97%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 37        | 9.71%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 6.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 6.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 4.99%   |
| Shenzhen Goodix FingerPrint                                                | 16        | 4.2%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 14        | 3.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 3.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 3.41%   |
| Elan ELAN:ARM-M4                                                           | 12        | 3.15%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 11        | 2.89%   |
| Synaptics WBDI Device                                                      | 11        | 2.89%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.62%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.1%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 2.1%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 1.84%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 1.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.57%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.57%   |
| Synaptics UWP WBDI Device                                                  | 6         | 1.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.57%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 1.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.57%   |
| Unknown                                                                    | 6         | 1.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.31%   |
| Synaptics TouchPad                                                         | 5         | 1.31%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 1.31%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 1.31%   |
| Validity Sensors VFS491                                                    | 4         | 1.05%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 1.05%   |
| Synaptics  WBDI                                                            | 4         | 1.05%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.05%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.79%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 0.79%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.79%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.52%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.52%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 74        | 54.81%  |
| Alcor Micro           | 40        | 29.63%  |
| O2 Micro              | 9         | 6.67%   |
| Lenovo                | 5         | 3.7%    |
| Upek                  | 4         | 2.96%   |
| OmniKey               | 1         | 0.74%   |
| Gemalto (was Gemplus) | 1         | 0.74%   |
| Clay Logic            | 1         | 0.74%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 40        | 29.63%  |
| Broadcom 58200                                                               | 24        | 17.78%  |
| Broadcom 5880                                                                | 21        | 15.56%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 12.59%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 8.15%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 5.93%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.7%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.96%   |
| OmniKey CardMan 4321                                                         | 1         | 0.74%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.74%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.74%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.74%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.74%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1319      | 58.47%  |
| 1     | 746       | 33.07%  |
| 2     | 166       | 7.36%   |
| 3     | 21        | 0.93%   |
| 4     | 3         | 0.13%   |
| 6     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 369       | 32.83%  |
| Multimedia controller    | 184       | 16.37%  |
| Graphics card            | 132       | 11.74%  |
| Chipcard                 | 128       | 11.39%  |
| Net/wireless             | 119       | 10.59%  |
| Bluetooth                | 59        | 5.25%   |
| Camera                   | 52        | 4.63%   |
| Sound                    | 17        | 1.51%   |
| Net/ethernet             | 14        | 1.25%   |
| Storage                  | 12        | 1.07%   |
| Network                  | 10        | 0.89%   |
| Card reader              | 9         | 0.8%    |
| Modem                    | 8         | 0.71%   |
| Communication controller | 8         | 0.71%   |
| Storage/ide              | 2         | 0.18%   |
| Storage/nvme             | 1         | 0.09%   |

