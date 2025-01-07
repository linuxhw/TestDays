Linux in Belgium - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Belgium.

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

Total: 2020

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Swift SFG14-72              | [d07bf77aa4](https://linux-hardware.org/?probe=d07bf77aa4) | Jan 06, 2025 |
| HP            | Pavilion Notebook           | [eb8cc11cc5](https://linux-hardware.org/?probe=eb8cc11cc5) | Jan 05, 2025 |
| HP            | Pavilion Notebook           | [41e590e617](https://linux-hardware.org/?probe=41e590e617) | Jan 03, 2025 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [d3d4e90cf3](https://linux-hardware.org/?probe=d3d4e90cf3) | Jan 03, 2025 |
| Lenovo        | ThinkPad E570 20H50070FR    | [cad0007adb](https://linux-hardware.org/?probe=cad0007adb) | Jan 02, 2025 |
| HUAWEI        | BOD-WXX9                    | [a65202783f](https://linux-hardware.org/?probe=a65202783f) | Jan 02, 2025 |
| HP            | G72                         | [376d1a0575](https://linux-hardware.org/?probe=376d1a0575) | Jan 01, 2025 |
| Lenovo        | ThinkPad E570 20H50070FR    | [5369e3db69](https://linux-hardware.org/?probe=5369e3db69) | Jan 01, 2025 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [b86a475528](https://linux-hardware.org/?probe=b86a475528) | Dec 31, 2024 |
| Lenovo        | ThinkPad T500 2241WKY       | [7b16eb5229](https://linux-hardware.org/?probe=7b16eb5229) | Dec 30, 2024 |
| VALE          | Notebook Slim S132          | [3275a28486](https://linux-hardware.org/?probe=3275a28486) | Dec 30, 2024 |
| HP            | ZBook Power 15.6 inch G8... | [f521839f9a](https://linux-hardware.org/?probe=f521839f9a) | Dec 29, 2024 |
| Dell          | XPS 15 9570                 | [ec780ef825](https://linux-hardware.org/?probe=ec780ef825) | Dec 29, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [e08182adc8](https://linux-hardware.org/?probe=e08182adc8) | Dec 29, 2024 |
| ASUSTek       | GL552VW                     | [dcb25941f6](https://linux-hardware.org/?probe=dcb25941f6) | Dec 27, 2024 |
| Medion        | ERAZER X7853 MD60603        | [9c5d2630f6](https://linux-hardware.org/?probe=9c5d2630f6) | Dec 27, 2024 |
| Lenovo        | G50-80 80E5                 | [fc91ff6b9f](https://linux-hardware.org/?probe=fc91ff6b9f) | Dec 27, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [2b5056fe92](https://linux-hardware.org/?probe=2b5056fe92) | Dec 27, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [bc55a24f5d](https://linux-hardware.org/?probe=bc55a24f5d) | Dec 27, 2024 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [306fb82bd7](https://linux-hardware.org/?probe=306fb82bd7) | Dec 26, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [00b72da4db](https://linux-hardware.org/?probe=00b72da4db) | Dec 25, 2024 |
| Samsung       | P480                        | [20507489a2](https://linux-hardware.org/?probe=20507489a2) | Dec 22, 2024 |
| HP            | ZBook Fury 16 G9 Mobile ... | [bb06bc1384](https://linux-hardware.org/?probe=bb06bc1384) | Dec 22, 2024 |
| MSI           | Alpha 17 C7VG               | [e84308bf47](https://linux-hardware.org/?probe=e84308bf47) | Dec 22, 2024 |
| MSI           | Alpha 17 C7VG               | [c3c778482b](https://linux-hardware.org/?probe=c3c778482b) | Dec 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d2b19da7f2](https://linux-hardware.org/?probe=d2b19da7f2) | Dec 18, 2024 |
| Lenovo        | ThinkPad T560 20FH0023MB    | [b073c6e731](https://linux-hardware.org/?probe=b073c6e731) | Dec 15, 2024 |
| HP            | Victus by Gaming Laptop ... | [3f73630b78](https://linux-hardware.org/?probe=3f73630b78) | Dec 15, 2024 |
| HP            | Pavilion 17                 | [4cea084a27](https://linux-hardware.org/?probe=4cea084a27) | Dec 15, 2024 |
| Lenovo        | ThinkPad T470 20HD0001MB    | [8858dce58d](https://linux-hardware.org/?probe=8858dce58d) | Dec 14, 2024 |
| Dell          | Latitude E7470              | [34f407dadd](https://linux-hardware.org/?probe=34f407dadd) | Dec 13, 2024 |
| HP            | Pavilion 17                 | [419cf21120](https://linux-hardware.org/?probe=419cf21120) | Dec 13, 2024 |
| HP            | EliteBook 835 13 inch G1... | [501650199f](https://linux-hardware.org/?probe=501650199f) | Dec 12, 2024 |
| ASUSTek       | X705NA                      | [e32ba5f9f3](https://linux-hardware.org/?probe=e32ba5f9f3) | Dec 12, 2024 |
| Lenovo        | ThinkPad T470 20HD0001MB    | [e975663b16](https://linux-hardware.org/?probe=e975663b16) | Dec 12, 2024 |
| Fujitsu       | CELSIUS H760                | [a25c3d32d9](https://linux-hardware.org/?probe=a25c3d32d9) | Dec 12, 2024 |
| Dell          | Latitude 5530               | [227f39046c](https://linux-hardware.org/?probe=227f39046c) | Dec 08, 2024 |
| Dell          | Latitude 5530               | [85b8689d79](https://linux-hardware.org/?probe=85b8689d79) | Dec 08, 2024 |
| Unknown       | AX16                        | [786a7ec53a](https://linux-hardware.org/?probe=786a7ec53a) | Dec 06, 2024 |
| Apple         | MacBookPro5,3               | [afe0f7a23b](https://linux-hardware.org/?probe=afe0f7a23b) | Dec 06, 2024 |
| Google        | Marasov                     | [cd94c505e9](https://linux-hardware.org/?probe=cd94c505e9) | Dec 05, 2024 |
| HP            | Pavilion dv7                | [8d22c82b8d](https://linux-hardware.org/?probe=8d22c82b8d) | Dec 04, 2024 |
| Sony          | VGN-FW51ZF_H                | [946eceac16](https://linux-hardware.org/?probe=946eceac16) | Dec 04, 2024 |
| Dell          | Latitude E7470              | [3d27c262dc](https://linux-hardware.org/?probe=3d27c262dc) | Dec 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b53e3ffba0](https://linux-hardware.org/?probe=b53e3ffba0) | Dec 03, 2024 |
| Dell          | Precision M6700             | [9b4c2350ab](https://linux-hardware.org/?probe=9b4c2350ab) | Dec 03, 2024 |
| Clevo         | W270HU                      | [ea4b13cd90](https://linux-hardware.org/?probe=ea4b13cd90) | Dec 02, 2024 |
| Acer          | Aspire A315-22              | [5b6d7f1853](https://linux-hardware.org/?probe=5b6d7f1853) | Nov 30, 2024 |
| HP            | Pavilion dv7                | [1ae9d9a604](https://linux-hardware.org/?probe=1ae9d9a604) | Nov 29, 2024 |
| Apple         | MacBookPro11,1              | [92dd553051](https://linux-hardware.org/?probe=92dd553051) | Nov 28, 2024 |
| ASUSTek       | K55A                        | [1cf283b131](https://linux-hardware.org/?probe=1cf283b131) | Nov 28, 2024 |
| Apple         | MacBookPro5,3               | [f8e03fed09](https://linux-hardware.org/?probe=f8e03fed09) | Nov 25, 2024 |
| Lenovo        | G50-80 80E5                 | [25e30e94f0](https://linux-hardware.org/?probe=25e30e94f0) | Nov 25, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [963aca3a61](https://linux-hardware.org/?probe=963aca3a61) | Nov 22, 2024 |
| ASUSTek       | 1005HA                      | [39603774e5](https://linux-hardware.org/?probe=39603774e5) | Nov 20, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [80772fe50c](https://linux-hardware.org/?probe=80772fe50c) | Nov 19, 2024 |
| Clevo         | W270HU                      | [1b9d20b809](https://linux-hardware.org/?probe=1b9d20b809) | Nov 19, 2024 |
| HP            | Pavilion Notebook           | [e07129b7d0](https://linux-hardware.org/?probe=e07129b7d0) | Nov 18, 2024 |
| Dell          | G16 7630                    | [15e93a0146](https://linux-hardware.org/?probe=15e93a0146) | Nov 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a8f5f86a85](https://linux-hardware.org/?probe=a8f5f86a85) | Nov 14, 2024 |
| Sony          | SVE1513G1EB                 | [71f5a2a25f](https://linux-hardware.org/?probe=71f5a2a25f) | Nov 13, 2024 |
| Sony          | VPCEA3S1E                   | [dc4bf023a2](https://linux-hardware.org/?probe=dc4bf023a2) | Nov 11, 2024 |
| MSI           | GS60 2QE                    | [f6cceaf60f](https://linux-hardware.org/?probe=f6cceaf60f) | Nov 11, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [bb9f5ddcc6](https://linux-hardware.org/?probe=bb9f5ddcc6) | Nov 11, 2024 |
| ASUSTek       | GL552VW                     | [748450069e](https://linux-hardware.org/?probe=748450069e) | Nov 10, 2024 |
| ASUSTek       | X550CA                      | [9de1e927a9](https://linux-hardware.org/?probe=9de1e927a9) | Nov 07, 2024 |
| Gigabyte      | AERO 15XV8                  | [ad28b2f598](https://linux-hardware.org/?probe=ad28b2f598) | Nov 07, 2024 |
| Lenovo        | Legion Slim 5 16ARP9 83E... | [cdbdaae023](https://linux-hardware.org/?probe=cdbdaae023) | Nov 06, 2024 |
| HP            | Pavilion Notebook           | [41cef70a32](https://linux-hardware.org/?probe=41cef70a32) | Oct 31, 2024 |
| Gigabyte      | AERO 15XV8                  | [10526455a3](https://linux-hardware.org/?probe=10526455a3) | Oct 31, 2024 |
| Lenovo        | ThinkPad E570 20H50070FR    | [4824bbad46](https://linux-hardware.org/?probe=4824bbad46) | Oct 31, 2024 |
| Dell          | Latitude E5500              | [f93b362839](https://linux-hardware.org/?probe=f93b362839) | Oct 31, 2024 |
| Dell          | Inspiron 7720               | [f308c7c570](https://linux-hardware.org/?probe=f308c7c570) | Oct 30, 2024 |
| Lenovo        | ThinkPad T450 20AUQWER09    | [121126e862](https://linux-hardware.org/?probe=121126e862) | Oct 27, 2024 |
| Lenovo        | ThinkPad T450 20AUQWER09    | [15aea43010](https://linux-hardware.org/?probe=15aea43010) | Oct 27, 2024 |
| ASUSTek       | ZenBook UX434FAC_UX433FA... | [d545472680](https://linux-hardware.org/?probe=d545472680) | Oct 26, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [5a786be98f](https://linux-hardware.org/?probe=5a786be98f) | Oct 25, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [6ddbc76ba2](https://linux-hardware.org/?probe=6ddbc76ba2) | Oct 25, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [e63c2ce069](https://linux-hardware.org/?probe=e63c2ce069) | Oct 24, 2024 |
| HP            | Pavilion 17                 | [fe2ac723ed](https://linux-hardware.org/?probe=fe2ac723ed) | Oct 23, 2024 |
| ASUSTek       | N61Vg                       | [751bf5f70d](https://linux-hardware.org/?probe=751bf5f70d) | Oct 21, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3795fe9a2b](https://linux-hardware.org/?probe=3795fe9a2b) | Oct 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [90de471428](https://linux-hardware.org/?probe=90de471428) | Oct 20, 2024 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [674a976e7b](https://linux-hardware.org/?probe=674a976e7b) | Oct 19, 2024 |
| HP            | ProBook 650 G4              | [2b82d1ddab](https://linux-hardware.org/?probe=2b82d1ddab) | Oct 18, 2024 |
| HP            | ProBook 650 G4              | [b0d567acfc](https://linux-hardware.org/?probe=b0d567acfc) | Oct 18, 2024 |
| ASRock        | X570 Taichi                 | [37085cd851](https://linux-hardware.org/?probe=37085cd851) | Oct 14, 2024 |
| HP            | ProBook 4740s               | [47465e7165](https://linux-hardware.org/?probe=47465e7165) | Oct 14, 2024 |
| HP            | ProBook 4740s               | [41a6bd612d](https://linux-hardware.org/?probe=41a6bd612d) | Oct 14, 2024 |
| Apple         | MacBookPro6,2               | [302e89b37e](https://linux-hardware.org/?probe=302e89b37e) | Oct 12, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [dcf7dcbdc0](https://linux-hardware.org/?probe=dcf7dcbdc0) | Oct 11, 2024 |
| Dell          | Latitude D630               | [ef1d491182](https://linux-hardware.org/?probe=ef1d491182) | Oct 08, 2024 |
| HP            | EliteBook 820 G1            | [c14b9319d4](https://linux-hardware.org/?probe=c14b9319d4) | Oct 05, 2024 |
| Lenovo        | Legion 5 15IMH05 82AU       | [c263b0d128](https://linux-hardware.org/?probe=c263b0d128) | Oct 02, 2024 |
| Lenovo        | Legion 5 15IMH05 82AU       | [6e28788eb8](https://linux-hardware.org/?probe=6e28788eb8) | Oct 02, 2024 |
| HP            | EliteBook 850 G5            | [fb275667e9](https://linux-hardware.org/?probe=fb275667e9) | Oct 01, 2024 |
| HP            | ProBook 470 G0              | [850a898da0](https://linux-hardware.org/?probe=850a898da0) | Oct 01, 2024 |
| Medion        | P6670 MD99960               | [b4528ac515](https://linux-hardware.org/?probe=b4528ac515) | Oct 01, 2024 |
| Sony          | SVE1512G4E                  | [ed463dbd08](https://linux-hardware.org/?probe=ed463dbd08) | Sep 30, 2024 |
| Apple         | MacBookPro14,3              | [d159b869bf](https://linux-hardware.org/?probe=d159b869bf) | Sep 29, 2024 |
| Apple         | MacBookPro14,3              | [0f3ef459af](https://linux-hardware.org/?probe=0f3ef459af) | Sep 29, 2024 |
| HP            | 15                          | [6c9df8c1e4](https://linux-hardware.org/?probe=6c9df8c1e4) | Sep 27, 2024 |
| HP            | Pavilion dv7                | [13f04d7403](https://linux-hardware.org/?probe=13f04d7403) | Sep 25, 2024 |
| HP            | ProBook 650 G8 Notebook ... | [413217c3d1](https://linux-hardware.org/?probe=413217c3d1) | Sep 25, 2024 |
| HP            | ProBook 650 G4              | [d008194d26](https://linux-hardware.org/?probe=d008194d26) | Sep 24, 2024 |
| Fujitsu       | LIFEBOOK E557               | [a77bf3ac11](https://linux-hardware.org/?probe=a77bf3ac11) | Sep 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c2587deab9](https://linux-hardware.org/?probe=c2587deab9) | Sep 24, 2024 |
| Dell          | Latitude E5430 non-vPro     | [48b01e248b](https://linux-hardware.org/?probe=48b01e248b) | Sep 22, 2024 |
| HP            | ProBook 650 G8 Notebook ... | [9d05a2b904](https://linux-hardware.org/?probe=9d05a2b904) | Sep 19, 2024 |
| ASUSTek       | N61Vg                       | [456f9b3749](https://linux-hardware.org/?probe=456f9b3749) | Sep 19, 2024 |
| ASUSTek       | K56CB                       | [8341a2762f](https://linux-hardware.org/?probe=8341a2762f) | Sep 18, 2024 |
| Dell          | Precision 7750              | [76a7f20266](https://linux-hardware.org/?probe=76a7f20266) | Sep 18, 2024 |
| MSI           | Thin GF63 12VF              | [22a5a00d36](https://linux-hardware.org/?probe=22a5a00d36) | Sep 17, 2024 |
| Apple         | MacBookPro14,1              | [1b50a503f5](https://linux-hardware.org/?probe=1b50a503f5) | Sep 13, 2024 |
| Apple         | MacBookPro14,1              | [6a82b07a2f](https://linux-hardware.org/?probe=6a82b07a2f) | Sep 13, 2024 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | [e40fd2534b](https://linux-hardware.org/?probe=e40fd2534b) | Sep 12, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [fa1b825886](https://linux-hardware.org/?probe=fa1b825886) | Sep 10, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [9f2adb4d94](https://linux-hardware.org/?probe=9f2adb4d94) | Sep 10, 2024 |
| MSI           | Thin GF63 12VF              | [d02b62db7a](https://linux-hardware.org/?probe=d02b62db7a) | Sep 09, 2024 |
| HP            | EliteBook 8570w             | [162e18416c](https://linux-hardware.org/?probe=162e18416c) | Sep 07, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [7551201f10](https://linux-hardware.org/?probe=7551201f10) | Sep 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [de9377b87f](https://linux-hardware.org/?probe=de9377b87f) | Sep 07, 2024 |
| Unknown       | Unknown                     | [a628595aaa](https://linux-hardware.org/?probe=a628595aaa) | Sep 04, 2024 |
| Lenovo        | ThinkPad L460 20FVS0PA1H    | [1a67ec8391](https://linux-hardware.org/?probe=1a67ec8391) | Sep 03, 2024 |
| Dell          | Vostro 16 5635              | [fc6900819a](https://linux-hardware.org/?probe=fc6900819a) | Aug 31, 2024 |
| Lenovo        | IdeaPad Slim 3 16ABR8 82... | [5d9d907b7a](https://linux-hardware.org/?probe=5d9d907b7a) | Aug 31, 2024 |
| Dell          | Vostro 16 5635              | [1eaac7d5c1](https://linux-hardware.org/?probe=1eaac7d5c1) | Aug 31, 2024 |
| Lenovo        | ThinkBook 14 G7 IML 21MR    | [6c7ce653e0](https://linux-hardware.org/?probe=6c7ce653e0) | Aug 30, 2024 |
| Lenovo        | ThinkPad L460 20FVS0PA1H    | [be660ad979](https://linux-hardware.org/?probe=be660ad979) | Aug 28, 2024 |
| Alienware     | x16 R2                      | [86c9bae75b](https://linux-hardware.org/?probe=86c9bae75b) | Aug 28, 2024 |
| ASUSTek       | X540SAA                     | [5818df112a](https://linux-hardware.org/?probe=5818df112a) | Aug 27, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [390c79d9e7](https://linux-hardware.org/?probe=390c79d9e7) | Aug 27, 2024 |
| Lenovo        | ThinkPad E485 20KU001HMH    | [f6715c95be](https://linux-hardware.org/?probe=f6715c95be) | Aug 27, 2024 |
| Acer          | Aspire E5-772               | [6696b97dd5](https://linux-hardware.org/?probe=6696b97dd5) | Aug 25, 2024 |
| Dell          | Latitude 5421               | [f1bb1223a1](https://linux-hardware.org/?probe=f1bb1223a1) | Aug 23, 2024 |
| Dell          | Precision M6400             | [5d1c43bde3](https://linux-hardware.org/?probe=5d1c43bde3) | Aug 21, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [50747463cb](https://linux-hardware.org/?probe=50747463cb) | Aug 21, 2024 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [add09e061b](https://linux-hardware.org/?probe=add09e061b) | Aug 21, 2024 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | [ad00735fac](https://linux-hardware.org/?probe=ad00735fac) | Aug 21, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | [52798501c0](https://linux-hardware.org/?probe=52798501c0) | Aug 19, 2024 |
| Apple         | MacBookPro8,2               | [71bae1f3f6](https://linux-hardware.org/?probe=71bae1f3f6) | Aug 16, 2024 |
| Apple         | MacBookPro8,2               | [acd6239144](https://linux-hardware.org/?probe=acd6239144) | Aug 16, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2ffa4f7ffc](https://linux-hardware.org/?probe=2ffa4f7ffc) | Aug 15, 2024 |
| Dell          | Precision M6400             | [78ae4c43fc](https://linux-hardware.org/?probe=78ae4c43fc) | Aug 15, 2024 |
| Dell          | Precision M6400             | [617bff8e48](https://linux-hardware.org/?probe=617bff8e48) | Aug 15, 2024 |
| HP            | Victus by Gaming Laptop ... | [36caa8a819](https://linux-hardware.org/?probe=36caa8a819) | Aug 14, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [5e9f9c2509](https://linux-hardware.org/?probe=5e9f9c2509) | Aug 14, 2024 |
| Acer          | Okinawa                     | [28bf3b601b](https://linux-hardware.org/?probe=28bf3b601b) | Aug 13, 2024 |
| HP            | Pavilion dv6                | [032f5f2535](https://linux-hardware.org/?probe=032f5f2535) | Aug 12, 2024 |
| Dell          | Latitude 5440               | [c35ec9c7e2](https://linux-hardware.org/?probe=c35ec9c7e2) | Aug 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [5a176dd34d](https://linux-hardware.org/?probe=5a176dd34d) | Aug 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [7af09b87a2](https://linux-hardware.org/?probe=7af09b87a2) | Aug 11, 2024 |
| Sony          | SVE14A25CFP                 | [35a1034271](https://linux-hardware.org/?probe=35a1034271) | Aug 11, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [4bc5b1dcaa](https://linux-hardware.org/?probe=4bc5b1dcaa) | Aug 10, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | [b006c903a5](https://linux-hardware.org/?probe=b006c903a5) | Aug 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [639d113f31](https://linux-hardware.org/?probe=639d113f31) | Aug 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [1ec165f5ac](https://linux-hardware.org/?probe=1ec165f5ac) | Aug 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [e2177bb6ea](https://linux-hardware.org/?probe=e2177bb6ea) | Aug 09, 2024 |
| Google        | Eve                         | [1f63b4fb2a](https://linux-hardware.org/?probe=1f63b4fb2a) | Aug 08, 2024 |
| Dell          | Latitude E6540              | [f42bc0d88a](https://linux-hardware.org/?probe=f42bc0d88a) | Aug 08, 2024 |
| Dell          | XPS 15 9500                 | [513068ed61](https://linux-hardware.org/?probe=513068ed61) | Aug 06, 2024 |
| Dell          | XPS 15 9500                 | [20a337d707](https://linux-hardware.org/?probe=20a337d707) | Aug 06, 2024 |
| Dell          | Latitude E7250              | [7b85835719](https://linux-hardware.org/?probe=7b85835719) | Aug 05, 2024 |
| HP            | ProBook 650 G4              | [1ce90c0f15](https://linux-hardware.org/?probe=1ce90c0f15) | Aug 05, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [def6acf8d0](https://linux-hardware.org/?probe=def6acf8d0) | Aug 04, 2024 |
| Acer          | Aspire E5-523G              | [dcae9fea91](https://linux-hardware.org/?probe=dcae9fea91) | Aug 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [4c9e72060a](https://linux-hardware.org/?probe=4c9e72060a) | Aug 01, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [b1a07486dd](https://linux-hardware.org/?probe=b1a07486dd) | Jul 31, 2024 |
| HP            | Pavilion Laptop 15-cw0xx... | [ce44067016](https://linux-hardware.org/?probe=ce44067016) | Jul 30, 2024 |
| HP            | Pavilion Laptop 13-an0xx... | [1b74560bae](https://linux-hardware.org/?probe=1b74560bae) | Jul 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [a7bb61f1ae](https://linux-hardware.org/?probe=a7bb61f1ae) | Jul 30, 2024 |
| Packard Be... | ENLE11BZ                    | [ecf5210a02](https://linux-hardware.org/?probe=ecf5210a02) | Jul 30, 2024 |
| HP            | ProBook 4530s               | [e89d3446a9](https://linux-hardware.org/?probe=e89d3446a9) | Jul 30, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H5S... | [fa1e2278d3](https://linux-hardware.org/?probe=fa1e2278d3) | Jul 29, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [1a0d405698](https://linux-hardware.org/?probe=1a0d405698) | Jul 29, 2024 |
| Notebook      | NLx0AU                      | [02f0e44fba](https://linux-hardware.org/?probe=02f0e44fba) | Jul 27, 2024 |
| Notebook      | NLx0AU                      | [f8000b45bb](https://linux-hardware.org/?probe=f8000b45bb) | Jul 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [a014cb10c6](https://linux-hardware.org/?probe=a014cb10c6) | Jul 25, 2024 |
| Dell          | Precision 7520              | [ab03c13aca](https://linux-hardware.org/?probe=ab03c13aca) | Jul 23, 2024 |
| Acer          | Aspire E5-575G              | [646e4a01d6](https://linux-hardware.org/?probe=646e4a01d6) | Jul 23, 2024 |
| HP            | ENVY dv6                    | [90cb34453c](https://linux-hardware.org/?probe=90cb34453c) | Jul 23, 2024 |
| Dell          | Latitude E6440              | [3440c7ee39](https://linux-hardware.org/?probe=3440c7ee39) | Jul 22, 2024 |
| Toshiba       | Satellite C50D-B            | [7b005551ad](https://linux-hardware.org/?probe=7b005551ad) | Jul 22, 2024 |
| HP            | ProBook 650 G4              | [2d093d58c6](https://linux-hardware.org/?probe=2d093d58c6) | Jul 21, 2024 |
| Dell          | Latitude E7440              | [0a7920c250](https://linux-hardware.org/?probe=0a7920c250) | Jul 21, 2024 |
| Valve         | Jupiter                     | [267ae5ae8a](https://linux-hardware.org/?probe=267ae5ae8a) | Jul 20, 2024 |
| Lenovo        | ThinkPad L390 20NSS1YV0B    | [73eae6f5a3](https://linux-hardware.org/?probe=73eae6f5a3) | Jul 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [59cab2e35c](https://linux-hardware.org/?probe=59cab2e35c) | Jul 18, 2024 |
| ASUSTek       | K55A                        | [2b7adf6752](https://linux-hardware.org/?probe=2b7adf6752) | Jul 18, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [e13a1e9bf1](https://linux-hardware.org/?probe=e13a1e9bf1) | Jul 18, 2024 |
| HP            | Pavilion Laptop 15-cs3xx... | [0f2a848d99](https://linux-hardware.org/?probe=0f2a848d99) | Jul 16, 2024 |
| Medion        | WIM2210                     | [0fc93b06b8](https://linux-hardware.org/?probe=0fc93b06b8) | Jul 16, 2024 |
| HP            | ProBook 470 G2              | [f46fe1fad0](https://linux-hardware.org/?probe=f46fe1fad0) | Jul 12, 2024 |
| Lenovo        | ThinkPad T440s 20ARS0NF0... | [051332a92e](https://linux-hardware.org/?probe=051332a92e) | Jul 04, 2024 |
| Dell          | XPS 13 9360                 | [7f932bad17](https://linux-hardware.org/?probe=7f932bad17) | Jul 04, 2024 |
| HP            | Pavilion 17                 | [ebeec13e1e](https://linux-hardware.org/?probe=ebeec13e1e) | Jul 03, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | [250703f607](https://linux-hardware.org/?probe=250703f607) | Jul 01, 2024 |
| HP            | Pavilion 17                 | [bafde5e27f](https://linux-hardware.org/?probe=bafde5e27f) | Jul 01, 2024 |
| Dell          | XPS 15 9560                 | [35e993f1fc](https://linux-hardware.org/?probe=35e993f1fc) | Jun 26, 2024 |
| Dell          | Studio 1749                 | [960cc11693](https://linux-hardware.org/?probe=960cc11693) | Jun 26, 2024 |
| Dell          | Latitude E5410              | [3d0605a450](https://linux-hardware.org/?probe=3d0605a450) | Jun 21, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [390feb9ba1](https://linux-hardware.org/?probe=390feb9ba1) | Jun 18, 2024 |
| PC Special... | NH5x_7xDPx                  | [c264f3cd40](https://linux-hardware.org/?probe=c264f3cd40) | Jun 16, 2024 |
| HP            | Notebook                    | [c5941ed7a8](https://linux-hardware.org/?probe=c5941ed7a8) | Jun 15, 2024 |
| HP            | Notebook                    | [da725874dd](https://linux-hardware.org/?probe=da725874dd) | Jun 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7d54502555](https://linux-hardware.org/?probe=7d54502555) | Jun 14, 2024 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [a89f829484](https://linux-hardware.org/?probe=a89f829484) | Jun 11, 2024 |
| HP            | ZBook Power G7 Mobile Wo... | [165b297c4a](https://linux-hardware.org/?probe=165b297c4a) | Jun 11, 2024 |
| Dell          | Precision M4800             | [24cd1eb79e](https://linux-hardware.org/?probe=24cd1eb79e) | Jun 11, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [5a2b97b0f3](https://linux-hardware.org/?probe=5a2b97b0f3) | Jun 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c4ce90425e](https://linux-hardware.org/?probe=c4ce90425e) | Jun 10, 2024 |
| Sony          | VPCEH1M1E                   | [66dfe52593](https://linux-hardware.org/?probe=66dfe52593) | Jun 08, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [d9ab37fa2b](https://linux-hardware.org/?probe=d9ab37fa2b) | Jun 06, 2024 |
| Dell          | Latitude E5410              | [4ea1350893](https://linux-hardware.org/?probe=4ea1350893) | Jun 05, 2024 |
| Dell          | Latitude 5550               | [789afc9e2f](https://linux-hardware.org/?probe=789afc9e2f) | Jun 04, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [a2291158ce](https://linux-hardware.org/?probe=a2291158ce) | Jun 02, 2024 |
| Sony          | VPCEH1M1E                   | [ec324480de](https://linux-hardware.org/?probe=ec324480de) | Jun 01, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [3c7d1c84a3](https://linux-hardware.org/?probe=3c7d1c84a3) | May 31, 2024 |
| Dell          | Latitude E6410              | [43d3671623](https://linux-hardware.org/?probe=43d3671623) | May 30, 2024 |
| HP            | 620                         | [fc744613bf](https://linux-hardware.org/?probe=fc744613bf) | May 30, 2024 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [e63220aa5e](https://linux-hardware.org/?probe=e63220aa5e) | May 27, 2024 |
| Dell          | Studio XPS 1645             | [e9eb7685bd](https://linux-hardware.org/?probe=e9eb7685bd) | May 27, 2024 |
| ASUSTek       | GL552VW                     | [1349b1dc80](https://linux-hardware.org/?probe=1349b1dc80) | May 26, 2024 |
| Dell          | Studio XPS 1645             | [d4926c0589](https://linux-hardware.org/?probe=d4926c0589) | May 26, 2024 |
| Apple         | MacBookPro11,2              | [dfbe54a60a](https://linux-hardware.org/?probe=dfbe54a60a) | May 26, 2024 |
| HP            | Laptop 15s-eq2xxx           | [79319b692a](https://linux-hardware.org/?probe=79319b692a) | May 26, 2024 |
| Dell          | Latitude E6400              | [a7d3b75e98](https://linux-hardware.org/?probe=a7d3b75e98) | May 25, 2024 |
| Dell          | Latitude E6400              | [bb208f175d](https://linux-hardware.org/?probe=bb208f175d) | May 24, 2024 |
| ASUSTek       | K55A                        | [b5e25bbe88](https://linux-hardware.org/?probe=b5e25bbe88) | May 24, 2024 |
| HP            | Pavilion 17                 | [e9e2dfb42e](https://linux-hardware.org/?probe=e9e2dfb42e) | May 22, 2024 |
| Dell          | Latitude 7480               | [b376ae7bb3](https://linux-hardware.org/?probe=b376ae7bb3) | May 21, 2024 |
| Acer          | Aspire M5-481T              | [fb89268b87](https://linux-hardware.org/?probe=fb89268b87) | May 21, 2024 |
| Dell          | Latitude 7480               | [8ac7a3af71](https://linux-hardware.org/?probe=8ac7a3af71) | May 20, 2024 |
| MSI           | Vector GP78HX 13VI          | [c927e894f5](https://linux-hardware.org/?probe=c927e894f5) | May 18, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [c3fc9de1ae](https://linux-hardware.org/?probe=c3fc9de1ae) | May 16, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [817b90e6cf](https://linux-hardware.org/?probe=817b90e6cf) | May 15, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | [60a691a363](https://linux-hardware.org/?probe=60a691a363) | May 15, 2024 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [2d841dfa43](https://linux-hardware.org/?probe=2d841dfa43) | May 14, 2024 |
| Lenovo        | E50-80 80J2                 | [a7568cbcc1](https://linux-hardware.org/?probe=a7568cbcc1) | May 13, 2024 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [0df4b475b4](https://linux-hardware.org/?probe=0df4b475b4) | May 12, 2024 |
| Sony          | SVE1511G1EB                 | [203f8f98e2](https://linux-hardware.org/?probe=203f8f98e2) | May 11, 2024 |
| Fujitsu       | LIFEBOOK E754               | [1240b3da0c](https://linux-hardware.org/?probe=1240b3da0c) | May 09, 2024 |
| Fujitsu       | LIFEBOOK U7510              | [a52ed98e85](https://linux-hardware.org/?probe=a52ed98e85) | May 07, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [39fdd434dd](https://linux-hardware.org/?probe=39fdd434dd) | May 06, 2024 |
| PC Special... | NH5x_7xDPx                  | [35a25ffdfd](https://linux-hardware.org/?probe=35a25ffdfd) | May 06, 2024 |
| Samsung       | R780                        | [5a838d44cd](https://linux-hardware.org/?probe=5a838d44cd) | May 04, 2024 |
| Acer          | Aspire E1-771               | [ef44b13882](https://linux-hardware.org/?probe=ef44b13882) | May 03, 2024 |
| Dell          | Latitude E5250              | [e98282af47](https://linux-hardware.org/?probe=e98282af47) | May 02, 2024 |
| HP            | ProBook 470 G5              | [8ba873e85d](https://linux-hardware.org/?probe=8ba873e85d) | Apr 30, 2024 |
| HP            | ProBook 450 G1              | [9c5d161110](https://linux-hardware.org/?probe=9c5d161110) | Apr 28, 2024 |
| Dell          | Latitude E7450              | [eb354c66fa](https://linux-hardware.org/?probe=eb354c66fa) | Apr 27, 2024 |
| Alienware     | 17 R5                       | [519ea8e910](https://linux-hardware.org/?probe=519ea8e910) | Apr 27, 2024 |
| Notebook      | P15SM-A/SM1-A               | [76d49d1637](https://linux-hardware.org/?probe=76d49d1637) | Apr 22, 2024 |
| Apple         | MacBookPro16,1              | [af2c346bb9](https://linux-hardware.org/?probe=af2c346bb9) | Apr 20, 2024 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [d7337f7684](https://linux-hardware.org/?probe=d7337f7684) | Apr 17, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | [b21773434d](https://linux-hardware.org/?probe=b21773434d) | Apr 12, 2024 |
| MSI           | Titan GT77HX 13VI           | [81cf9688bd](https://linux-hardware.org/?probe=81cf9688bd) | Apr 08, 2024 |
| ASUSTek       | X541UA                      | [0cbeeec8f8](https://linux-hardware.org/?probe=0cbeeec8f8) | Apr 06, 2024 |
| Notebook      | NL40_50CU                   | [c356d14430](https://linux-hardware.org/?probe=c356d14430) | Apr 03, 2024 |
| HP            | ZBook Fury 16 G9 Mobile ... | [10ff3b22cf](https://linux-hardware.org/?probe=10ff3b22cf) | Apr 03, 2024 |
| HP            | ZBook Fury 16 G9 Mobile ... | [896bd3d75a](https://linux-hardware.org/?probe=896bd3d75a) | Apr 03, 2024 |
| MSI           | Titan GT77HX 13VI           | [c6da8fe194](https://linux-hardware.org/?probe=c6da8fe194) | Apr 02, 2024 |
| Alienware     | x14                         | [8ae209f28d](https://linux-hardware.org/?probe=8ae209f28d) | Apr 02, 2024 |
| HP            | ZBook Studio 16 inch G9 ... | [df89cb1a75](https://linux-hardware.org/?probe=df89cb1a75) | Mar 31, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [9577fddfae](https://linux-hardware.org/?probe=9577fddfae) | Mar 30, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | [af9f697c2d](https://linux-hardware.org/?probe=af9f697c2d) | Mar 29, 2024 |
| Dell          | Latitude E6230              | [33eeb1b3a8](https://linux-hardware.org/?probe=33eeb1b3a8) | Mar 24, 2024 |
| Acer          | Extensa 5230                | [790672cb92](https://linux-hardware.org/?probe=790672cb92) | Mar 22, 2024 |
| Dell          | Latitude 5510               | [eda5c51b5e](https://linux-hardware.org/?probe=eda5c51b5e) | Mar 20, 2024 |
| Acer          | Aspire ES1-111              | [429ee44acd](https://linux-hardware.org/?probe=429ee44acd) | Mar 20, 2024 |
| Toshiba       | Satellite C70D-A            | [11c353f181](https://linux-hardware.org/?probe=11c353f181) | Mar 18, 2024 |
| HP            | ProBook 650 G3              | [546158e937](https://linux-hardware.org/?probe=546158e937) | Mar 18, 2024 |
| Dell          | Latitude E6230              | [2991ee40ab](https://linux-hardware.org/?probe=2991ee40ab) | Mar 16, 2024 |
| Lenovo        | ThinkPad T560 20FHS0DN00    | [8559c82719](https://linux-hardware.org/?probe=8559c82719) | Mar 16, 2024 |
| Lenovo        | ThinkPad T490 20N3S3FX00    | [819d84d41f](https://linux-hardware.org/?probe=819d84d41f) | Mar 16, 2024 |
| Sony          | VPCEB3L1E                   | [9a422c9ac3](https://linux-hardware.org/?probe=9a422c9ac3) | Mar 13, 2024 |
| HP            | 620                         | [b5df7d8db3](https://linux-hardware.org/?probe=b5df7d8db3) | Mar 12, 2024 |
| Schenker      | KEY (E23)                   | [f555bec75a](https://linux-hardware.org/?probe=f555bec75a) | Mar 12, 2024 |
| MSI           | Alpha 17 C7VF               | [d22dedc33d](https://linux-hardware.org/?probe=d22dedc33d) | Mar 12, 2024 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [d95bf9ddf2](https://linux-hardware.org/?probe=d95bf9ddf2) | Mar 11, 2024 |
| Valve         | Jupiter                     | [19c2d88d48](https://linux-hardware.org/?probe=19c2d88d48) | Mar 11, 2024 |
| HP            | Unknown                     | [cd14ad3a78](https://linux-hardware.org/?probe=cd14ad3a78) | Mar 11, 2024 |
| Fujitsu       | LIFEBOOK U7510              | [b78e24d0f3](https://linux-hardware.org/?probe=b78e24d0f3) | Mar 11, 2024 |
| HP            | ProBook 650 G1              | [cf7b0b9e86](https://linux-hardware.org/?probe=cf7b0b9e86) | Mar 08, 2024 |
| Notebook      | W54_55_94_95_97AU,AUQ       | [b16fb5307b](https://linux-hardware.org/?probe=b16fb5307b) | Mar 07, 2024 |
| Lenovo        | ThinkPad T60 8744HDG        | [95634ccb20](https://linux-hardware.org/?probe=95634ccb20) | Mar 06, 2024 |
| HP            | Laptop 15s-eq1xxx           | [42b75630c2](https://linux-hardware.org/?probe=42b75630c2) | Mar 05, 2024 |
| ASUSTek       | X551CA                      | [f47713c088](https://linux-hardware.org/?probe=f47713c088) | Mar 04, 2024 |
| Toshiba       | Satellite C855-1V3          | [e7dcf2bbb4](https://linux-hardware.org/?probe=e7dcf2bbb4) | Mar 01, 2024 |
| Dell          | Latitude E5520m             | [2375f9c13c](https://linux-hardware.org/?probe=2375f9c13c) | Feb 29, 2024 |
| ASUSTek       | K55A                        | [f4c8beefee](https://linux-hardware.org/?probe=f4c8beefee) | Feb 28, 2024 |
| Dell          | Latitude E6430              | [8d0f028ba1](https://linux-hardware.org/?probe=8d0f028ba1) | Feb 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [902cf010e5](https://linux-hardware.org/?probe=902cf010e5) | Feb 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [f803f67bd8](https://linux-hardware.org/?probe=f803f67bd8) | Feb 28, 2024 |
| Dell          | Latitude E6520              | [ddcde00351](https://linux-hardware.org/?probe=ddcde00351) | Feb 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [fd7cecbb27](https://linux-hardware.org/?probe=fd7cecbb27) | Feb 26, 2024 |
| TUXEDO        | Sirius 16 Gen1              | [76659ee758](https://linux-hardware.org/?probe=76659ee758) | Feb 25, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [6983281b83](https://linux-hardware.org/?probe=6983281b83) | Feb 23, 2024 |
| Dell          | Inspiron 15-3567            | [d1939367e4](https://linux-hardware.org/?probe=d1939367e4) | Feb 22, 2024 |
| MSI           | GF63 Thin 9SC               | [15dc9ca9eb](https://linux-hardware.org/?probe=15dc9ca9eb) | Feb 21, 2024 |
| HP            | ProBook 450 G8              | [d3738f661f](https://linux-hardware.org/?probe=d3738f661f) | Feb 21, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [1e64feccdb](https://linux-hardware.org/?probe=1e64feccdb) | Feb 21, 2024 |
| MSI           | GF63 Thin 9SC               | [f5eeab1f59](https://linux-hardware.org/?probe=f5eeab1f59) | Feb 20, 2024 |
| ASUSTek       | K55A                        | [d3b37dc96a](https://linux-hardware.org/?probe=d3b37dc96a) | Feb 20, 2024 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [4e55af71ff](https://linux-hardware.org/?probe=4e55af71ff) | Feb 20, 2024 |
| Acer          | Aspire A315-51              | [3e89cd8ab4](https://linux-hardware.org/?probe=3e89cd8ab4) | Feb 19, 2024 |
| HUAWEI        | HKD-WXX                     | [797bff6dba](https://linux-hardware.org/?probe=797bff6dba) | Feb 19, 2024 |
| HP            | ProBook 450 G8              | [3cffa51632](https://linux-hardware.org/?probe=3cffa51632) | Feb 19, 2024 |
| Medion        | Akoya THE TOUCH 10          | [55af4d803a](https://linux-hardware.org/?probe=55af4d803a) | Feb 19, 2024 |
| HP            | Laptop 15s-eq2xxx           | [63c3d36c4b](https://linux-hardware.org/?probe=63c3d36c4b) | Feb 19, 2024 |
| Dell          | Latitude E7240              | [4572babdfc](https://linux-hardware.org/?probe=4572babdfc) | Feb 18, 2024 |
| Acer          | Swift SF314-54              | [a08666a01c](https://linux-hardware.org/?probe=a08666a01c) | Feb 18, 2024 |
| Lenovo        | Z50-70 20354                | [5f3d1618fe](https://linux-hardware.org/?probe=5f3d1618fe) | Feb 17, 2024 |
| MSI           | GE72 6QC                    | [bf8edb1354](https://linux-hardware.org/?probe=bf8edb1354) | Feb 17, 2024 |
| HP            | EliteBook 850 G1            | [4cc22792a8](https://linux-hardware.org/?probe=4cc22792a8) | Feb 13, 2024 |
| Sony          | SVE14A25CFP                 | [82b1cf235d](https://linux-hardware.org/?probe=82b1cf235d) | Feb 08, 2024 |
| HP            | ProBook 450 15.6 inch G1... | [be25a7ff5b](https://linux-hardware.org/?probe=be25a7ff5b) | Feb 07, 2024 |
| HP            | Laptop 15s-eq2xxx           | [9b1ea3c33b](https://linux-hardware.org/?probe=9b1ea3c33b) | Feb 06, 2024 |
| HP            | ENVY 15                     | [d5d64bff23](https://linux-hardware.org/?probe=d5d64bff23) | Feb 06, 2024 |
| Dell          | Precision 5510              | [09ac1961f1](https://linux-hardware.org/?probe=09ac1961f1) | Feb 05, 2024 |
| Dell          | G5 5590                     | [36847d8517](https://linux-hardware.org/?probe=36847d8517) | Feb 04, 2024 |
| HP            | EliteBook 830 G5            | [0321b2bca6](https://linux-hardware.org/?probe=0321b2bca6) | Feb 04, 2024 |
| Dell          | Latitude E5500              | [c24ebcbbd1](https://linux-hardware.org/?probe=c24ebcbbd1) | Feb 04, 2024 |
| ASUSTek       | X556UQK                     | [24b1509f61](https://linux-hardware.org/?probe=24b1509f61) | Feb 02, 2024 |
| Toshiba       | Portable PC                 | [5c293a3c24](https://linux-hardware.org/?probe=5c293a3c24) | Jan 30, 2024 |
| Dell          | Latitude 5510               | [4abbee3451](https://linux-hardware.org/?probe=4abbee3451) | Jan 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [bc4c195cfe](https://linux-hardware.org/?probe=bc4c195cfe) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [746b28ec9b](https://linux-hardware.org/?probe=746b28ec9b) | Jan 28, 2024 |
| ASUSTek       | K55A                        | [49e26738de](https://linux-hardware.org/?probe=49e26738de) | Jan 28, 2024 |
| HP            | EliteBook 850 G7 Noteboo... | [7f749dfabf](https://linux-hardware.org/?probe=7f749dfabf) | Jan 26, 2024 |
| HP            | Compaq 6530b (GW688AV)      | [aa8bc496ed](https://linux-hardware.org/?probe=aa8bc496ed) | Jan 24, 2024 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [c55c6dc13f](https://linux-hardware.org/?probe=c55c6dc13f) | Jan 24, 2024 |
| HP            | Notebook                    | [8359e2a5dd](https://linux-hardware.org/?probe=8359e2a5dd) | Jan 22, 2024 |
| Samsung       | R530/R730/R540              | [d781965459](https://linux-hardware.org/?probe=d781965459) | Jan 21, 2024 |
| Toshiba       | Satellite C70D-A            | [f71a7005de](https://linux-hardware.org/?probe=f71a7005de) | Jan 18, 2024 |
| HP            | ZBook Studio 16 inch G9 ... | [e736cc5c9a](https://linux-hardware.org/?probe=e736cc5c9a) | Jan 18, 2024 |
| HP            | ProBook 650 G2              | [4374ba78cb](https://linux-hardware.org/?probe=4374ba78cb) | Jan 18, 2024 |
| HP            | ProBook 650 G1              | [58cacbd716](https://linux-hardware.org/?probe=58cacbd716) | Jan 16, 2024 |
| Lenovo        | ThinkPad E580 20KS007PMB    | [7284cabc43](https://linux-hardware.org/?probe=7284cabc43) | Jan 13, 2024 |
| Acer          | Nitro AN517-41              | [3f38b8085c](https://linux-hardware.org/?probe=3f38b8085c) | Jan 12, 2024 |
| Acer          | Aspire E1-570G              | [2bb5dcf476](https://linux-hardware.org/?probe=2bb5dcf476) | Jan 10, 2024 |
| Acer          | Aspire E1-570G              | [3c08b1958e](https://linux-hardware.org/?probe=3c08b1958e) | Jan 07, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [b02f06751f](https://linux-hardware.org/?probe=b02f06751f) | Jan 07, 2024 |
| HP            | Pavilion Notebook           | [cb3075eea0](https://linux-hardware.org/?probe=cb3075eea0) | Jan 05, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [d8162d1873](https://linux-hardware.org/?probe=d8162d1873) | Jan 04, 2024 |
| ASUSTek       | K55A                        | [c40aec3f95](https://linux-hardware.org/?probe=c40aec3f95) | Jan 04, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | [32f3a44b1c](https://linux-hardware.org/?probe=32f3a44b1c) | Jan 03, 2024 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [7fbbe32bb5](https://linux-hardware.org/?probe=7fbbe32bb5) | Jan 02, 2024 |
| Apple         | MacBookAir4,2               | [7ebd4a00e7](https://linux-hardware.org/?probe=7ebd4a00e7) | Dec 31, 2023 |
| Apple         | MacBookAir7,2               | [b25bae6ded](https://linux-hardware.org/?probe=b25bae6ded) | Dec 31, 2023 |
| Unknown       | Unknown                     | [764c59c56e](https://linux-hardware.org/?probe=764c59c56e) | Dec 31, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [a37bbce8de](https://linux-hardware.org/?probe=a37bbce8de) | Dec 31, 2023 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [86a499d322](https://linux-hardware.org/?probe=86a499d322) | Dec 30, 2023 |
| HP            | ENVY Laptop 13-aq1xxx       | [44df1c7cc6](https://linux-hardware.org/?probe=44df1c7cc6) | Dec 28, 2023 |
| Dell          | Latitude 5510               | [ebe9c1f033](https://linux-hardware.org/?probe=ebe9c1f033) | Dec 28, 2023 |
| Dell          | Latitude E6530              | [bd56df50f6](https://linux-hardware.org/?probe=bd56df50f6) | Dec 26, 2023 |
| Unknown       | Unknown                     | [ef80f96d40](https://linux-hardware.org/?probe=ef80f96d40) | Dec 23, 2023 |
| Danew         | Dbook 131                   | [a3880bd02c](https://linux-hardware.org/?probe=a3880bd02c) | Dec 23, 2023 |
| Danew         | Dbook 131                   | [0568c9bdbf](https://linux-hardware.org/?probe=0568c9bdbf) | Dec 22, 2023 |
| HP            | EliteBook 850 G3            | [1265cfb294](https://linux-hardware.org/?probe=1265cfb294) | Dec 21, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | [6e4bcb9311](https://linux-hardware.org/?probe=6e4bcb9311) | Dec 21, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [f7cd6db92f](https://linux-hardware.org/?probe=f7cd6db92f) | Dec 20, 2023 |
| HP            | EliteBook 850 G3            | [6067c56124](https://linux-hardware.org/?probe=6067c56124) | Dec 19, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [780a4cf454](https://linux-hardware.org/?probe=780a4cf454) | Dec 18, 2023 |
| Acer          | Aspire 1810TZ               | [b935091ecd](https://linux-hardware.org/?probe=b935091ecd) | Dec 17, 2023 |
| Acer          | Aspire 1810TZ               | [14b5a5a3ca](https://linux-hardware.org/?probe=14b5a5a3ca) | Dec 17, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [b5fefd59fe](https://linux-hardware.org/?probe=b5fefd59fe) | Dec 15, 2023 |
| HP            | Laptop 14s-fq0xxx           | [2c8846a637](https://linux-hardware.org/?probe=2c8846a637) | Dec 12, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [f24c11f324](https://linux-hardware.org/?probe=f24c11f324) | Dec 11, 2023 |
| MSI           | GF63 Thin 11UC              | [78562df77d](https://linux-hardware.org/?probe=78562df77d) | Dec 11, 2023 |
| HP            | ProBook 650 G2              | [96ea36be06](https://linux-hardware.org/?probe=96ea36be06) | Dec 10, 2023 |
| Unknown       | NY-02                       | [d894eced77](https://linux-hardware.org/?probe=d894eced77) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cf832dba27](https://linux-hardware.org/?probe=cf832dba27) | Dec 08, 2023 |
| Unknown       | NY-02                       | [8d1cd2ab24](https://linux-hardware.org/?probe=8d1cd2ab24) | Dec 07, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [b118593b9d](https://linux-hardware.org/?probe=b118593b9d) | Dec 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [d4ece1c445](https://linux-hardware.org/?probe=d4ece1c445) | Dec 06, 2023 |
| Apple         | MacBookPro6,2               | [ee4cab6d84](https://linux-hardware.org/?probe=ee4cab6d84) | Dec 06, 2023 |
| Apple         | MacBookPro6,2               | [a47e6e3616](https://linux-hardware.org/?probe=a47e6e3616) | Dec 05, 2023 |
| ASUSTek       | X550CA                      | [a0912ee339](https://linux-hardware.org/?probe=a0912ee339) | Dec 05, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | [a8c094f376](https://linux-hardware.org/?probe=a8c094f376) | Dec 04, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | [856a01d874](https://linux-hardware.org/?probe=856a01d874) | Dec 02, 2023 |
| ASUSTek       | X550CA                      | [8ed2e1621c](https://linux-hardware.org/?probe=8ed2e1621c) | Nov 29, 2023 |
| HP            | ProBook 450 G3              | [0d6a4cd900](https://linux-hardware.org/?probe=0d6a4cd900) | Nov 28, 2023 |
| HP            | Elite x2 1012 G1            | [1fda4e1f6d](https://linux-hardware.org/?probe=1fda4e1f6d) | Nov 28, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [f8cdbfddcd](https://linux-hardware.org/?probe=f8cdbfddcd) | Nov 27, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [6418e60f5a](https://linux-hardware.org/?probe=6418e60f5a) | Nov 27, 2023 |
| HP            | EliteBook 850 G6            | [597c5faf3a](https://linux-hardware.org/?probe=597c5faf3a) | Nov 27, 2023 |
| HP            | ProBook 650 G1              | [22a88185d6](https://linux-hardware.org/?probe=22a88185d6) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [f8eb14af89](https://linux-hardware.org/?probe=f8eb14af89) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [9d5752b2d8](https://linux-hardware.org/?probe=9d5752b2d8) | Nov 24, 2023 |
| Acer          | Aspire E5-575               | [1ad50e2862](https://linux-hardware.org/?probe=1ad50e2862) | Nov 23, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [8cf21a227b](https://linux-hardware.org/?probe=8cf21a227b) | Nov 22, 2023 |
| MSI           | Prestige 15 A10SC           | [e1abb4721b](https://linux-hardware.org/?probe=e1abb4721b) | Nov 21, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21HK... | [2fe5c073ce](https://linux-hardware.org/?probe=2fe5c073ce) | Nov 19, 2023 |
| Lenovo        | ThinkPad E520 11437UG       | [422931d9a6](https://linux-hardware.org/?probe=422931d9a6) | Nov 19, 2023 |
| HP            | Pavilion 17                 | [00c2d45d1d](https://linux-hardware.org/?probe=00c2d45d1d) | Nov 19, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21HK... | [fd99bf5f2a](https://linux-hardware.org/?probe=fd99bf5f2a) | Nov 18, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [43e84fe856](https://linux-hardware.org/?probe=43e84fe856) | Nov 17, 2023 |
| Lenovo        | B70-80 80MR                 | [84f08f46f0](https://linux-hardware.org/?probe=84f08f46f0) | Nov 15, 2023 |
| Notebook      | NS5x_NS7xPU                 | [c26f7106c6](https://linux-hardware.org/?probe=c26f7106c6) | Nov 15, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [1f783e1865](https://linux-hardware.org/?probe=1f783e1865) | Nov 14, 2023 |
| Lenovo        | ThinkPad X250 20CLS2P703    | [b15506a2b9](https://linux-hardware.org/?probe=b15506a2b9) | Nov 14, 2023 |
| Dell          | XPS 15 9560                 | [b806051ada](https://linux-hardware.org/?probe=b806051ada) | Nov 14, 2023 |
| ASUSTek       | X540SAA                     | [1c5e9077a8](https://linux-hardware.org/?probe=1c5e9077a8) | Nov 12, 2023 |
| Apple         | MacBookAir6,2               | [3595c8f9d1](https://linux-hardware.org/?probe=3595c8f9d1) | Nov 12, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [6885ccb289](https://linux-hardware.org/?probe=6885ccb289) | Nov 11, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [8bdbf5b0d9](https://linux-hardware.org/?probe=8bdbf5b0d9) | Nov 11, 2023 |
| Lenovo        | ThinkPad P50s 20FL000EMS    | [81d1c107cc](https://linux-hardware.org/?probe=81d1c107cc) | Nov 11, 2023 |
| Notebook      | NS5x_NS7xPU                 | [4b53c4e9da](https://linux-hardware.org/?probe=4b53c4e9da) | Nov 10, 2023 |
| Fujitsu Si... | LIFEBOOK S7220              | [52f980a58c](https://linux-hardware.org/?probe=52f980a58c) | Nov 09, 2023 |
| PEAQ          | PNB C1014-I1B1 MD99447      | [33d5a0aa8c](https://linux-hardware.org/?probe=33d5a0aa8c) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [cc75144dea](https://linux-hardware.org/?probe=cc75144dea) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [598b5837e5](https://linux-hardware.org/?probe=598b5837e5) | Nov 07, 2023 |
| Dell          | Latitude 5590               | [0290e5fd1a](https://linux-hardware.org/?probe=0290e5fd1a) | Nov 06, 2023 |
| HP            | ProBook 650 G1              | [e56fc59b28](https://linux-hardware.org/?probe=e56fc59b28) | Nov 06, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [5e5e97717a](https://linux-hardware.org/?probe=5e5e97717a) | Nov 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [ebf86ce161](https://linux-hardware.org/?probe=ebf86ce161) | Nov 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [5eada91f48](https://linux-hardware.org/?probe=5eada91f48) | Nov 04, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| HP            | Pavilion dv6                | [e57ba14bc9](https://linux-hardware.org/?probe=e57ba14bc9) | Nov 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [826dc000ff](https://linux-hardware.org/?probe=826dc000ff) | Nov 01, 2023 |
| HP            | Pavilion dv6                | [031a3670bd](https://linux-hardware.org/?probe=031a3670bd) | Nov 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [7c07fc9bbe](https://linux-hardware.org/?probe=7c07fc9bbe) | Oct 31, 2023 |
| Dell          | XPS 15 9570                 | [17de10e607](https://linux-hardware.org/?probe=17de10e607) | Oct 29, 2023 |
| Notebook      | NS50_70MU                   | [ad21a28397](https://linux-hardware.org/?probe=ad21a28397) | Oct 28, 2023 |
| Notebook      | NS50_70MU                   | [166a51fa8d](https://linux-hardware.org/?probe=166a51fa8d) | Oct 27, 2023 |
| HP            | Pavilion 17                 | [9eb519ce8c](https://linux-hardware.org/?probe=9eb519ce8c) | Oct 26, 2023 |
| HP            | Pavilion 17                 | [9b004ab742](https://linux-hardware.org/?probe=9b004ab742) | Oct 26, 2023 |
| Acer          | Aspire A315-58              | [0d52b12158](https://linux-hardware.org/?probe=0d52b12158) | Oct 25, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [274089a92c](https://linux-hardware.org/?probe=274089a92c) | Oct 24, 2023 |
| EUROCOM       | Tornado F5                  | [3056eeecf5](https://linux-hardware.org/?probe=3056eeecf5) | Oct 21, 2023 |
| EUROCOM       | Tornado F5                  | [25b7095754](https://linux-hardware.org/?probe=25b7095754) | Oct 21, 2023 |
| HP            | ZBook 17 G3                 | [f8330df761](https://linux-hardware.org/?probe=f8330df761) | Oct 20, 2023 |
| Dell          | Precision 7720              | [574a292adb](https://linux-hardware.org/?probe=574a292adb) | Oct 14, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [ef43db2db3](https://linux-hardware.org/?probe=ef43db2db3) | Oct 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [86ca92698e](https://linux-hardware.org/?probe=86ca92698e) | Oct 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [fb98eb2395](https://linux-hardware.org/?probe=fb98eb2395) | Oct 11, 2023 |
| Apple         | MacBookPro12,1              | [9de05646a3](https://linux-hardware.org/?probe=9de05646a3) | Oct 10, 2023 |
| Acer          | Aspire ES1-520              | [d7418fb673](https://linux-hardware.org/?probe=d7418fb673) | Oct 10, 2023 |
| Dell          | XPS 15 9560                 | [598f31dfeb](https://linux-hardware.org/?probe=598f31dfeb) | Oct 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f95efe1e80](https://linux-hardware.org/?probe=f95efe1e80) | Oct 09, 2023 |
| Dell          | XPS 15 9530                 | [1423f1793b](https://linux-hardware.org/?probe=1423f1793b) | Oct 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [fc37084670](https://linux-hardware.org/?probe=fc37084670) | Oct 05, 2023 |
| Dell          | Latitude E6530              | [a426b30b67](https://linux-hardware.org/?probe=a426b30b67) | Oct 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [b2f26d1c00](https://linux-hardware.org/?probe=b2f26d1c00) | Oct 04, 2023 |
| MSI           | GF63 Thin 9SC               | [3670f5ea70](https://linux-hardware.org/?probe=3670f5ea70) | Oct 02, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [40f87e9874](https://linux-hardware.org/?probe=40f87e9874) | Oct 02, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [8cb6a92a75](https://linux-hardware.org/?probe=8cb6a92a75) | Oct 01, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [bb5a34d03f](https://linux-hardware.org/?probe=bb5a34d03f) | Oct 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [951a03d2ad](https://linux-hardware.org/?probe=951a03d2ad) | Sep 30, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [a343a1c573](https://linux-hardware.org/?probe=a343a1c573) | Sep 30, 2023 |
| Dell          | Precision 5480              | [5d157102ea](https://linux-hardware.org/?probe=5d157102ea) | Sep 29, 2023 |
| Packard Be... | EasyNote TK36               | [1e8f79c726](https://linux-hardware.org/?probe=1e8f79c726) | Sep 29, 2023 |
| Alienware     | x14                         | [048d5f6f2a](https://linux-hardware.org/?probe=048d5f6f2a) | Sep 28, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [0f2958c5a1](https://linux-hardware.org/?probe=0f2958c5a1) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| Lenovo        | ThinkPad T420 4236EV9       | [d621ecd81f](https://linux-hardware.org/?probe=d621ecd81f) | Sep 26, 2023 |
| Acer          | Nitro AN515-58              | [0c17f26ed8](https://linux-hardware.org/?probe=0c17f26ed8) | Sep 25, 2023 |
| Dell          | XPS 13 9305                 | [7c0b883934](https://linux-hardware.org/?probe=7c0b883934) | Sep 24, 2023 |
| ASUSTek       | K50IJ                       | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [b96887841e](https://linux-hardware.org/?probe=b96887841e) | Sep 23, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [535d4769c8](https://linux-hardware.org/?probe=535d4769c8) | Sep 22, 2023 |
| Acer          | Aspire VN7-571G             | [0314ce541e](https://linux-hardware.org/?probe=0314ce541e) | Sep 22, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0NF0... | [54aa39a845](https://linux-hardware.org/?probe=54aa39a845) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [47e95a92cc](https://linux-hardware.org/?probe=47e95a92cc) | Sep 17, 2023 |
| Acer          | Nitro AN517-52              | [5fe7196179](https://linux-hardware.org/?probe=5fe7196179) | Sep 17, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [e1ac878fa3](https://linux-hardware.org/?probe=e1ac878fa3) | Sep 15, 2023 |
| Dell          | Latitude 5501               | [1608104990](https://linux-hardware.org/?probe=1608104990) | Sep 14, 2023 |
| MSI           | Modern 14 A10M              | [c78162f5fd](https://linux-hardware.org/?probe=c78162f5fd) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | [45261be082](https://linux-hardware.org/?probe=45261be082) | Sep 10, 2023 |
| HP            | 620                         | [6fd1497e1a](https://linux-hardware.org/?probe=6fd1497e1a) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | [4dfd50fada](https://linux-hardware.org/?probe=4dfd50fada) | Sep 10, 2023 |
| HP            | Laptop 15-db0xxx            | [b65fb1e357](https://linux-hardware.org/?probe=b65fb1e357) | Sep 09, 2023 |
| Dell          | XPS 15 9500                 | [3747ee0c29](https://linux-hardware.org/?probe=3747ee0c29) | Sep 04, 2023 |
| Toshiba       | Satellite C70D-A            | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| ASUSTek       | K73SV                       | [7d3f9fa0e5](https://linux-hardware.org/?probe=7d3f9fa0e5) | Sep 04, 2023 |
| Acer          | Aspire 7741                 | [0b3868c6bc](https://linux-hardware.org/?probe=0b3868c6bc) | Sep 04, 2023 |
| Acer          | TravelMate 8372             | [709e81e4a0](https://linux-hardware.org/?probe=709e81e4a0) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| Acer          | TravelMate 5760G            | [1a0a1749fc](https://linux-hardware.org/?probe=1a0a1749fc) | Sep 01, 2023 |
| ASUSTek       | X75VC                       | [4a2115b7ae](https://linux-hardware.org/?probe=4a2115b7ae) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [6cd62bfac4](https://linux-hardware.org/?probe=6cd62bfac4) | Aug 31, 2023 |
| Acer          | Aspire 7560                 | [4cb158cafc](https://linux-hardware.org/?probe=4cb158cafc) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5fddb9cc18](https://linux-hardware.org/?probe=5fddb9cc18) | Aug 28, 2023 |
| Acer          | Aspire V5-573G              | [1afaed6ffa](https://linux-hardware.org/?probe=1afaed6ffa) | Aug 28, 2023 |
| Dell          | Studio 1735                 | [5932ab2004](https://linux-hardware.org/?probe=5932ab2004) | Aug 25, 2023 |
| ASUSTek       | K73SV                       | [d366a928cc](https://linux-hardware.org/?probe=d366a928cc) | Aug 24, 2023 |
| ASUSTek       | X756UQ                      | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | [659ac11761](https://linux-hardware.org/?probe=659ac11761) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d0d3c76bb8](https://linux-hardware.org/?probe=d0d3c76bb8) | Aug 17, 2023 |
| MSI           | Katana GF66 11UC            | [927eacb30f](https://linux-hardware.org/?probe=927eacb30f) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [4c4e9222ce](https://linux-hardware.org/?probe=4c4e9222ce) | Aug 16, 2023 |
| Medion        | Akoya THE TOUCH 10          | [488c1edd8d](https://linux-hardware.org/?probe=488c1edd8d) | Aug 13, 2023 |
| Medion        | Akoya THE TOUCH 10          | [d45603bb4e](https://linux-hardware.org/?probe=d45603bb4e) | Aug 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [5e64d2b59e](https://linux-hardware.org/?probe=5e64d2b59e) | Aug 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [db2732f0e8](https://linux-hardware.org/?probe=db2732f0e8) | Aug 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [deeafc23f9](https://linux-hardware.org/?probe=deeafc23f9) | Aug 03, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [8da287a76b](https://linux-hardware.org/?probe=8da287a76b) | Aug 01, 2023 |
| HP            | 620                         | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [c74f4bde19](https://linux-hardware.org/?probe=c74f4bde19) | Aug 01, 2023 |
| Valve         | Jupiter                     | [6eb487950f](https://linux-hardware.org/?probe=6eb487950f) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [93d193bdbc](https://linux-hardware.org/?probe=93d193bdbc) | Aug 01, 2023 |
| Lenovo        | WEI6 15 ITL 82F2            | [d30f44ebbb](https://linux-hardware.org/?probe=d30f44ebbb) | Jul 30, 2023 |
| HP            | 530                         | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| ASUSTek       | K50IJ                       | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Apple         | MacBookPro10,1              | [c3ec46f79e](https://linux-hardware.org/?probe=c3ec46f79e) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [e2cf7ed35f](https://linux-hardware.org/?probe=e2cf7ed35f) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7843df6b43](https://linux-hardware.org/?probe=7843df6b43) | Jul 19, 2023 |
| ASUSTek       | X756UQ                      | [be24f941c7](https://linux-hardware.org/?probe=be24f941c7) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | [f0f2c5a6a7](https://linux-hardware.org/?probe=f0f2c5a6a7) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | [6070a533c5](https://linux-hardware.org/?probe=6070a533c5) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [0d54b47098](https://linux-hardware.org/?probe=0d54b47098) | Jul 12, 2023 |
| HP            | EliteBook 840 G5            | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | [8f40997f5f](https://linux-hardware.org/?probe=8f40997f5f) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | [7d19e6a8f5](https://linux-hardware.org/?probe=7d19e6a8f5) | Jul 10, 2023 |
| Dell          | Precision M4800             | [ef29f43a6f](https://linux-hardware.org/?probe=ef29f43a6f) | Jul 09, 2023 |
| HP            | 620                         | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [b4d926a4bc](https://linux-hardware.org/?probe=b4d926a4bc) | Jul 08, 2023 |
| Dell          | Latitude 3380               | [b4403e7b15](https://linux-hardware.org/?probe=b4403e7b15) | Jul 07, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [31d5e724ba](https://linux-hardware.org/?probe=31d5e724ba) | Jul 07, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [84b5d3ce3c](https://linux-hardware.org/?probe=84b5d3ce3c) | Jul 06, 2023 |
| Dell          | Precision 7520              | [1bffd04c84](https://linux-hardware.org/?probe=1bffd04c84) | Jul 05, 2023 |
| Apple         | MacBook8,1                  | [d27490cbe0](https://linux-hardware.org/?probe=d27490cbe0) | Jul 04, 2023 |
| HP            | EliteBook 820 G1            | [5b1b409a2f](https://linux-hardware.org/?probe=5b1b409a2f) | Jul 04, 2023 |
| Apple         | MacBook8,1                  | [06ac15dcca](https://linux-hardware.org/?probe=06ac15dcca) | Jul 04, 2023 |
| Dell          | Precision 5560              | [5f8f3c917f](https://linux-hardware.org/?probe=5f8f3c917f) | Jul 04, 2023 |
| ASUSTek       | X556UQK                     | [b4560fc1c1](https://linux-hardware.org/?probe=b4560fc1c1) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [6df0ae15e1](https://linux-hardware.org/?probe=6df0ae15e1) | Jul 01, 2023 |
| Acer          | Aspire 7715Z                | [b288a09d6e](https://linux-hardware.org/?probe=b288a09d6e) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| HP            | EliteBook 8460p             | [d4a008aefb](https://linux-hardware.org/?probe=d4a008aefb) | Jun 30, 2023 |
| Dell          | Latitude 5440               | [7868400967](https://linux-hardware.org/?probe=7868400967) | Jun 30, 2023 |
| VALE          | Notebook Slim S132          | [3e381e10f7](https://linux-hardware.org/?probe=3e381e10f7) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [39f7adb927](https://linux-hardware.org/?probe=39f7adb927) | Jun 30, 2023 |
| MSI           | Modern 14 A10M              | [fcc6786de6](https://linux-hardware.org/?probe=fcc6786de6) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [99efa1a1c5](https://linux-hardware.org/?probe=99efa1a1c5) | Jun 24, 2023 |
| Acer          | Aspire A515-55              | [bf6de06fb9](https://linux-hardware.org/?probe=bf6de06fb9) | Jun 23, 2023 |
| Emdoor        | AG958                       | [3574f89b15](https://linux-hardware.org/?probe=3574f89b15) | Jun 21, 2023 |
| Acer          | Aspire F5-771G              | [034d235f5c](https://linux-hardware.org/?probe=034d235f5c) | Jun 19, 2023 |
| ASUSTek       | X555LJ                      | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| ASUSTek       | X556UQK                     | [50c975ae08](https://linux-hardware.org/?probe=50c975ae08) | Jun 13, 2023 |
| Emdoor        | AG958                       | [1688cc07b6](https://linux-hardware.org/?probe=1688cc07b6) | Jun 11, 2023 |
| ASUSTek       | X540SAA                     | [ea61fdd09a](https://linux-hardware.org/?probe=ea61fdd09a) | Jun 11, 2023 |
| MSI           | Modern 14 A10M              | [7d5fc6a209](https://linux-hardware.org/?probe=7d5fc6a209) | Jun 11, 2023 |
| Notebook      | NS50_70MU                   | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| Medion        | Akoya E7226                 | [b46a96183b](https://linux-hardware.org/?probe=b46a96183b) | Jun 10, 2023 |
| Dell          | Latitude 5530               | [a302ecd3cd](https://linux-hardware.org/?probe=a302ecd3cd) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| HP            | Pavilion Notebook           | [3fb05bfb0b](https://linux-hardware.org/?probe=3fb05bfb0b) | May 31, 2023 |
| Dell          | Latitude 5510               | [78bd1ae0e0](https://linux-hardware.org/?probe=78bd1ae0e0) | May 31, 2023 |
| Dell          | Latitude 7390               | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S6P801    | [8ec80f5e43](https://linux-hardware.org/?probe=8ec80f5e43) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [1aa973f6bc](https://linux-hardware.org/?probe=1aa973f6bc) | May 28, 2023 |
| Apple         | MacBookPro14,3              | [fd8a08639d](https://linux-hardware.org/?probe=fd8a08639d) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Lenovo        | V130-15IGM 81HL             | [76a357994a](https://linux-hardware.org/?probe=76a357994a) | May 27, 2023 |
| Dell          | Latitude 7390               | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| Lenovo        | V130-15IGM 81HL             | [5a4cf4d2e3](https://linux-hardware.org/?probe=5a4cf4d2e3) | May 23, 2023 |
| Acer          | Aspire E5-771G              | [0dadbeca5b](https://linux-hardware.org/?probe=0dadbeca5b) | May 19, 2023 |
| Valve         | Jupiter                     | [0de060a93f](https://linux-hardware.org/?probe=0de060a93f) | May 18, 2023 |
| MSI           | GS70 2PC Stealth            | [254f42a469](https://linux-hardware.org/?probe=254f42a469) | May 18, 2023 |
| HP            | 620                         | [6b688ce696](https://linux-hardware.org/?probe=6b688ce696) | May 17, 2023 |
| HP            | Pavilion dv6                | [1b931dc36f](https://linux-hardware.org/?probe=1b931dc36f) | May 17, 2023 |
| Emdoor        | AG958                       | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HP            | EliteBook 8470p             | [f97e4e7fc1](https://linux-hardware.org/?probe=f97e4e7fc1) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| ASUSTek       | UX410UAK                    | [d68a2bc7c0](https://linux-hardware.org/?probe=d68a2bc7c0) | May 10, 2023 |
| MSI           | Katana 17 B12UCXK           | [15b9d97c10](https://linux-hardware.org/?probe=15b9d97c10) | May 09, 2023 |
| HP            | EliteBook 8740w             | [29d129229b](https://linux-hardware.org/?probe=29d129229b) | May 08, 2023 |
| HP            | Laptop 17-cn2xxx            | [ddf0cb8a28](https://linux-hardware.org/?probe=ddf0cb8a28) | May 08, 2023 |
| Dell          | Latitude 7390               | [dc5c96e431](https://linux-hardware.org/?probe=dc5c96e431) | May 08, 2023 |
| MSI           | CR61 3M                     | [f41852fa6e](https://linux-hardware.org/?probe=f41852fa6e) | May 07, 2023 |
| MSI           | CR61 3M                     | [7b5d49d859](https://linux-hardware.org/?probe=7b5d49d859) | May 07, 2023 |
| MSI           | GS70 2PC Stealth            | [370f9304b6](https://linux-hardware.org/?probe=370f9304b6) | May 07, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [b0464a0b99](https://linux-hardware.org/?probe=b0464a0b99) | May 06, 2023 |
| Notebook      | NS5x_NS7xPU                 | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [7bb2ae638b](https://linux-hardware.org/?probe=7bb2ae638b) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [bd0458e8a9](https://linux-hardware.org/?probe=bd0458e8a9) | May 01, 2023 |
| Medion        | P6630                       | [93abad41dd](https://linux-hardware.org/?probe=93abad41dd) | Apr 30, 2023 |
| Dell          | Latitude 5521               | [1629b4efc4](https://linux-hardware.org/?probe=1629b4efc4) | Apr 30, 2023 |
| Lenovo        | V130-15IGM 81HL             | [ff24454021](https://linux-hardware.org/?probe=ff24454021) | Apr 29, 2023 |
| Lenovo        | V130-15IGM 81HL             | [9081fc703d](https://linux-hardware.org/?probe=9081fc703d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S56G00    | [8da21e9a17](https://linux-hardware.org/?probe=8da21e9a17) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| Dell          | Latitude E6440              | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| Acer          | Aspire E5-576G              | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | [2e542c241d](https://linux-hardware.org/?probe=2e542c241d) | Apr 25, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Emdoor        | AG958                       | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| Acer          | Nitro AN515-58              | [60251e08f5](https://linux-hardware.org/?probe=60251e08f5) | Apr 22, 2023 |
| Dell          | Latitude E6330              | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | [d342e4d24c](https://linux-hardware.org/?probe=d342e4d24c) | Apr 22, 2023 |
| Emdoor        | AG958                       | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| HP            | Laptop 17-cn2xxx            | [5b77cc21f4](https://linux-hardware.org/?probe=5b77cc21f4) | Apr 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [efdcb6b99e](https://linux-hardware.org/?probe=efdcb6b99e) | Apr 18, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [38aeb226af](https://linux-hardware.org/?probe=38aeb226af) | Apr 17, 2023 |
| Dell          | XPS 15 9500                 | [1a55ffc593](https://linux-hardware.org/?probe=1a55ffc593) | Apr 17, 2023 |
| Dell          | Latitude 5420               | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [f44bbda528](https://linux-hardware.org/?probe=f44bbda528) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | [b87471108a](https://linux-hardware.org/?probe=b87471108a) | Apr 14, 2023 |
| Lenovo        | ThinkPad X250 20CLS29J05    | [60c50f0a10](https://linux-hardware.org/?probe=60c50f0a10) | Apr 13, 2023 |
| MSI           | Vector GP76 12UHSO          | [6037aee790](https://linux-hardware.org/?probe=6037aee790) | Apr 11, 2023 |
| Sony          | SVE1713A1EW                 | [402fae93d5](https://linux-hardware.org/?probe=402fae93d5) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b220308aa1](https://linux-hardware.org/?probe=b220308aa1) | Apr 06, 2023 |
| HP            | 620                         | [ad46cdbb0d](https://linux-hardware.org/?probe=ad46cdbb0d) | Apr 06, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | [d9d2e73619](https://linux-hardware.org/?probe=d9d2e73619) | Apr 05, 2023 |
| Dell          | Vostro 15 3515              | [95a98c59b1](https://linux-hardware.org/?probe=95a98c59b1) | Apr 03, 2023 |
| Clevo         | P170HMx                     | [c963b350fc](https://linux-hardware.org/?probe=c963b350fc) | Apr 03, 2023 |
| AZW           | Speed S                     | [52292a4968](https://linux-hardware.org/?probe=52292a4968) | Apr 02, 2023 |
| HP            | Pavilion g7                 | [7820d2ca67](https://linux-hardware.org/?probe=7820d2ca67) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| HP            | Compaq 6730b (GB987ET#UU... | [6c6ceb9bc3](https://linux-hardware.org/?probe=6c6ceb9bc3) | Mar 31, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [c73c5374a4](https://linux-hardware.org/?probe=c73c5374a4) | Mar 30, 2023 |
| Medion        | P8614                       | [a66fe7042e](https://linux-hardware.org/?probe=a66fe7042e) | Mar 29, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| MSI           | GT70                        | [8b00b28b12](https://linux-hardware.org/?probe=8b00b28b12) | Mar 26, 2023 |
| Medion        | P7624                       | [fe5c568f41](https://linux-hardware.org/?probe=fe5c568f41) | Mar 26, 2023 |
| Medion        | P7624                       | [778f5948f1](https://linux-hardware.org/?probe=778f5948f1) | Mar 26, 2023 |
| Dell          | Latitude E6330              | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Alienware     | m17 R3                      | [6c62c223ed](https://linux-hardware.org/?probe=6c62c223ed) | Mar 21, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [7622701d31](https://linux-hardware.org/?probe=7622701d31) | Mar 21, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| HP            | Pavilion g7                 | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [837ed83646](https://linux-hardware.org/?probe=837ed83646) | Mar 18, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | [1825764856](https://linux-hardware.org/?probe=1825764856) | Mar 17, 2023 |
| ASUSTek       | K72Jr                       | [cde6fff1ad](https://linux-hardware.org/?probe=cde6fff1ad) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | [2c01c1fd0e](https://linux-hardware.org/?probe=2c01c1fd0e) | Mar 11, 2023 |
| Medion        | Akoya E1318T                | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| ASUSTek       | K52F                        | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| ASUSTek       | K50IJ                       | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| MSI           | GT60 2OC/2OD                | [72eed5b458](https://linux-hardware.org/?probe=72eed5b458) | Mar 08, 2023 |
| MSI           | GT60 2OC/2OD                | [d595ae284e](https://linux-hardware.org/?probe=d595ae284e) | Mar 07, 2023 |
| Alienware     | x14                         | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Acer          | Aspire 6530G                | [a4077c8432](https://linux-hardware.org/?probe=a4077c8432) | Mar 05, 2023 |
| Toshiba       | Satellite C855-112          | [8635f2eecd](https://linux-hardware.org/?probe=8635f2eecd) | Mar 05, 2023 |
| HP            | 620                         | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| ASUSTek       | F70SL                       | [5870cf8326](https://linux-hardware.org/?probe=5870cf8326) | Mar 01, 2023 |
| Dell          | Latitude 5530               | [b1d7964fc7](https://linux-hardware.org/?probe=b1d7964fc7) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| HP            | EliteBook 8540w             | [057c307bf5](https://linux-hardware.org/?probe=057c307bf5) | Feb 28, 2023 |
| Apple         | MacBookPro15,4              | [41330b2783](https://linux-hardware.org/?probe=41330b2783) | Feb 26, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7e5789e02b](https://linux-hardware.org/?probe=7e5789e02b) | Feb 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [da5050e2f8](https://linux-hardware.org/?probe=da5050e2f8) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| TUXEDO        | Aura 15 Gen2                | [9eca2efc88](https://linux-hardware.org/?probe=9eca2efc88) | Feb 19, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| ASUSTek       | K50IJ                       | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Acer          | Aspire V3-771               | [caeb6bc93f](https://linux-hardware.org/?probe=caeb6bc93f) | Feb 17, 2023 |
| Alienware     | 17 R2                       | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| Dell          | XPS 15 9560                 | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| Packard Be... | DOT S                       | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| Dell          | Latitude E6330              | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Valve         | Jupiter                     | [9c458e5a66](https://linux-hardware.org/?probe=9c458e5a66) | Feb 11, 2023 |
| Acer          | Aspire V5-122               | [99fd12250b](https://linux-hardware.org/?probe=99fd12250b) | Feb 10, 2023 |
| Teclast       | F15S                        | [951ded8432](https://linux-hardware.org/?probe=951ded8432) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Valve         | Jupiter                     | [870ba1caa7](https://linux-hardware.org/?probe=870ba1caa7) | Feb 07, 2023 |
| Sony          | VGN-Z31XN_B                 | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| Medion        | P6624                       | [5a31124376](https://linux-hardware.org/?probe=5a31124376) | Feb 06, 2023 |
| ASUSTek       | GL703VD                     | [62e1e79469](https://linux-hardware.org/?probe=62e1e79469) | Feb 03, 2023 |
| Dell          | Precision 7550              | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [72bdb7165c](https://linux-hardware.org/?probe=72bdb7165c) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| Apple         | MacBookAir6,2               | [2261a77abb](https://linux-hardware.org/?probe=2261a77abb) | Feb 01, 2023 |
| Google        | Pantheon                    | [12e0b96dd1](https://linux-hardware.org/?probe=12e0b96dd1) | Feb 01, 2023 |
| ASUSTek       | K50IJ                       | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [f6be582448](https://linux-hardware.org/?probe=f6be582448) | Jan 30, 2023 |
| Lenovo        | S21e-20 80M4                | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| Acer          | Peppy                       | [9a16262be8](https://linux-hardware.org/?probe=9a16262be8) | Jan 27, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [77a6b88d58](https://linux-hardware.org/?probe=77a6b88d58) | Jan 27, 2023 |
| Dell          | Latitude E6410              | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2c8424ac3d](https://linux-hardware.org/?probe=2c8424ac3d) | Jan 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Medion        | P6624                       | [344d427f44](https://linux-hardware.org/?probe=344d427f44) | Jan 20, 2023 |
| Dell          | Latitude 5320               | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Acer          | Aspire VN7-591G             | [9476823c0b](https://linux-hardware.org/?probe=9476823c0b) | Jan 19, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| MSI           | Katana GF76 11UC            | [8c0b32cf24](https://linux-hardware.org/?probe=8c0b32cf24) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Acer          | Aspire V3-571G              | [e3b9b73877](https://linux-hardware.org/?probe=e3b9b73877) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f59adc6dcd](https://linux-hardware.org/?probe=f59adc6dcd) | Jan 13, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | [10c4bcf564](https://linux-hardware.org/?probe=10c4bcf564) | Jan 12, 2023 |
| HP            | Pavilion dv6000 (RY604EA... | [a8ec5eb86a](https://linux-hardware.org/?probe=a8ec5eb86a) | Jan 11, 2023 |
| Acer          | Aspire 7560                 | [58cd9d7ad2](https://linux-hardware.org/?probe=58cd9d7ad2) | Jan 09, 2023 |
| Dell          | XPS L521X                   | [2930493243](https://linux-hardware.org/?probe=2930493243) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [0f1543c21d](https://linux-hardware.org/?probe=0f1543c21d) | Jan 09, 2023 |
| Notebook      | P7xxDM3(-G)                 | [7cafa98138](https://linux-hardware.org/?probe=7cafa98138) | Jan 08, 2023 |
| HP            | Laptop 15s-eq2xxx           | [d1eaa576e7](https://linux-hardware.org/?probe=d1eaa576e7) | Jan 07, 2023 |
| HP            | Laptop 15-db0xxx            | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| Medion        | S4214                       | [58131e715e](https://linux-hardware.org/?probe=58131e715e) | Jan 06, 2023 |
| HP            | Pavilion g7                 | [9f029a8cdb](https://linux-hardware.org/?probe=9f029a8cdb) | Jan 06, 2023 |
| MSI           | Raider GE67HX 12UGS         | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| Dell          | System XPS L702X            | [7030c340cc](https://linux-hardware.org/?probe=7030c340cc) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0A    | [82168627b7](https://linux-hardware.org/?probe=82168627b7) | Dec 31, 2022 |
| MSI           | Raider GE67HX 12UGS         | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| HP            | Notebook                    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Dell          | Latitude 5580               | [7c006e8c6d](https://linux-hardware.org/?probe=7c006e8c6d) | Dec 28, 2022 |
| Notebook      | N7x0WU                      | [9eee40dd50](https://linux-hardware.org/?probe=9eee40dd50) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Valve         | Jupiter                     | [e9811949dd](https://linux-hardware.org/?probe=e9811949dd) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| MSI           | Raider GE67HX 12UGS         | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | Pavilion g7                 | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Sony          | SVS1311N9ES                 | [5c1a4bed5b](https://linux-hardware.org/?probe=5c1a4bed5b) | Dec 24, 2022 |
| ASUSTek       | K53SC                       | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a2d763d722](https://linux-hardware.org/?probe=a2d763d722) | Dec 21, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| Valve         | Jupiter                     | [2f061a6d8d](https://linux-hardware.org/?probe=2f061a6d8d) | Dec 20, 2022 |
| Packard Be... | EasyNote TR85               | [6c56016ed0](https://linux-hardware.org/?probe=6c56016ed0) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | [abd93a5cca](https://linux-hardware.org/?probe=abd93a5cca) | Dec 19, 2022 |
| HP            | ProBook 6570b               | [4deb8fc518](https://linux-hardware.org/?probe=4deb8fc518) | Dec 19, 2022 |
| Valve         | Jupiter                     | [9c513daaf3](https://linux-hardware.org/?probe=9c513daaf3) | Dec 17, 2022 |
| Medion        | WIM2210                     | [d1a64f7b3b](https://linux-hardware.org/?probe=d1a64f7b3b) | Dec 17, 2022 |
| Lenovo        | B70-80 80MR                 | [c17bee3b4a](https://linux-hardware.org/?probe=c17bee3b4a) | Dec 17, 2022 |
| Lenovo        | ThinkPad T570 20H9S04C00    | [f3093ba13c](https://linux-hardware.org/?probe=f3093ba13c) | Dec 16, 2022 |
| Valve         | Jupiter                     | [26aae3342c](https://linux-hardware.org/?probe=26aae3342c) | Dec 16, 2022 |
| Acer          | Aspire A515-57              | [4e9bbbaa1f](https://linux-hardware.org/?probe=4e9bbbaa1f) | Dec 16, 2022 |
| Dell          | Inspiron 5567               | [1398958777](https://linux-hardware.org/?probe=1398958777) | Dec 14, 2022 |
| Apple         | MacBookPro9,2               | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| ASUSTek       | X75VC                       | [45efd7615d](https://linux-hardware.org/?probe=45efd7615d) | Dec 12, 2022 |
| Lenovo        | ThinkPad T430 2349L26       | [9d0bcbdc75](https://linux-hardware.org/?probe=9d0bcbdc75) | Dec 11, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| Lenovo        | ThinkPad T520 4243CJ2       | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| HP            | Pavilion Laptop             | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [6dbc014a04](https://linux-hardware.org/?probe=6dbc014a04) | Dec 03, 2022 |
| HP            | ProBook 6550b               | [564bf050f2](https://linux-hardware.org/?probe=564bf050f2) | Dec 02, 2022 |
| Dell          | G3 3779                     | [1cf1d8aa20](https://linux-hardware.org/?probe=1cf1d8aa20) | Nov 26, 2022 |
| Dell          | G3 3779                     | [4bc02c1721](https://linux-hardware.org/?probe=4bc02c1721) | Nov 26, 2022 |
| Acer          | NC-ES1-512-C3AH             | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [dfd1c98a18](https://linux-hardware.org/?probe=dfd1c98a18) | Nov 20, 2022 |
| HP            | Pavilion dv6                | [a7ca712256](https://linux-hardware.org/?probe=a7ca712256) | Nov 19, 2022 |
| HP            | Pavilion dv6                | [571dc553f9](https://linux-hardware.org/?probe=571dc553f9) | Nov 19, 2022 |
| Dell          | Latitude 5530               | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [7c8d905b3d](https://linux-hardware.org/?probe=7c8d905b3d) | Nov 17, 2022 |
| Dell          | Precision 7560              | [0ee8814502](https://linux-hardware.org/?probe=0ee8814502) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| Apple         | MacBookPro5,5               | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| HP            | EliteBook 850 G5            | [331a1db69d](https://linux-hardware.org/?probe=331a1db69d) | Nov 11, 2022 |
| HP            | Pavilion 15                 | [d703e1c63c](https://linux-hardware.org/?probe=d703e1c63c) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| Acer          | Aspire 1825PTZ              | [c2dc801a81](https://linux-hardware.org/?probe=c2dc801a81) | Nov 09, 2022 |
| Acer          | Aspire 7741                 | [9fda4c3798](https://linux-hardware.org/?probe=9fda4c3798) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| HP            | EliteBook 830 G5            | [25756ad3c1](https://linux-hardware.org/?probe=25756ad3c1) | Nov 07, 2022 |
| HP            | Pavilion 17                 | [958de69d5b](https://linux-hardware.org/?probe=958de69d5b) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| HP            | Pavilion 17                 | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| TUXEDO        | Aura 15 Gen2                | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| ASUSTek       | GL703VD                     | [3e8fbc43d7](https://linux-hardware.org/?probe=3e8fbc43d7) | Nov 04, 2022 |
| Dell          | Latitude 5580               | [92545fb976](https://linux-hardware.org/?probe=92545fb976) | Nov 02, 2022 |
| Dell          | Precision 7550              | [2065f4ab5f](https://linux-hardware.org/?probe=2065f4ab5f) | Nov 02, 2022 |
| HP            | ProBook 470 G5              | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| PC Special... | Recoil II                   | [9ec5a6ef20](https://linux-hardware.org/?probe=9ec5a6ef20) | Oct 27, 2022 |
| PC Special... | Recoil II                   | [38ec5a7708](https://linux-hardware.org/?probe=38ec5a7708) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [0e12d15b78](https://linux-hardware.org/?probe=0e12d15b78) | Oct 24, 2022 |
| Acer          | Aspire E5-521               | [a7bffc7d13](https://linux-hardware.org/?probe=a7bffc7d13) | Oct 22, 2022 |
| Valve         | Jupiter                     | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| Lenovo        | ThinkPad E590 20NB002BMB    | [4b272ef951](https://linux-hardware.org/?probe=4b272ef951) | Oct 20, 2022 |
| TUXEDO        | Aura 15 Gen2                | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| MSI           | GE70 2PE                    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Dell          | Latitude 3380               | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| HP            | ProBook 450 G6              | [fda3302752](https://linux-hardware.org/?probe=fda3302752) | Oct 16, 2022 |
| HP            | EliteBook 8570w             | [76f457f2aa](https://linux-hardware.org/?probe=76f457f2aa) | Oct 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Dell          | XPS 13 9305                 | [0bc0bf85be](https://linux-hardware.org/?probe=0bc0bf85be) | Oct 14, 2022 |
| Dell          | Latitude E6330              | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Dell          | Precision M3800             | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| Notebook      | NS5x_NS7xPU                 | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| Dell          | Latitude 5530               | [9453558076](https://linux-hardware.org/?probe=9453558076) | Oct 12, 2022 |
| ASUSTek       | X756UVK                     | [8d2e9a5e1e](https://linux-hardware.org/?probe=8d2e9a5e1e) | Oct 12, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [24d18c0f7f](https://linux-hardware.org/?probe=24d18c0f7f) | Oct 09, 2022 |
| Valve         | Jupiter                     | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| HP            | EliteBook 745 G6            | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| HP            | EliteBook 840 14 inch G9... | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| Gigabyte      | Spring Peak                 | [45794008e2](https://linux-hardware.org/?probe=45794008e2) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| ASUSTek       | X756UQ                      | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | ProBook 470 G5              | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| Notebook      | W330SU2                     | [a5d5500584](https://linux-hardware.org/?probe=a5d5500584) | Oct 01, 2022 |
| Dell          | Latitude 5530               | [43874dad6d](https://linux-hardware.org/?probe=43874dad6d) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| HP            | EliteBook 6930p             | [56e5d25094](https://linux-hardware.org/?probe=56e5d25094) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| Razer         | Blade                       | [63a4e5f829](https://linux-hardware.org/?probe=63a4e5f829) | Sep 29, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Apple         | MacBookAir6,2               | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Lenovo        | G50-45 80E3                 | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| Lenovo        | B570e 476025G               | [ab67a90ba7](https://linux-hardware.org/?probe=ab67a90ba7) | Sep 20, 2022 |
| HP            | ProBook 470 G5              | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| HP            | Pavilion Notebook           | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude 5520               | [3e023f86c9](https://linux-hardware.org/?probe=3e023f86c9) | Sep 17, 2022 |
| ASUSTek       | UX32VD                      | [324cafa8d2](https://linux-hardware.org/?probe=324cafa8d2) | Sep 17, 2022 |
| Dell          | Precision 7720              | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| Acer          | Aspire 7551                 | [916aa5cc5d](https://linux-hardware.org/?probe=916aa5cc5d) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | [3f97043d7a](https://linux-hardware.org/?probe=3f97043d7a) | Sep 14, 2022 |
| Sony          | SVE1712L1EW                 | [18400c7a0d](https://linux-hardware.org/?probe=18400c7a0d) | Sep 13, 2022 |
| Dell          | Inspiron 15-3567            | [f062dd3ff8](https://linux-hardware.org/?probe=f062dd3ff8) | Sep 12, 2022 |
| ASUSTek       | UX32VD                      | [6a6e7e4207](https://linux-hardware.org/?probe=6a6e7e4207) | Sep 12, 2022 |
| Sony          | SVE1712L1EW                 | [6a797dc1cf](https://linux-hardware.org/?probe=6a797dc1cf) | Sep 12, 2022 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [8d76919c1a](https://linux-hardware.org/?probe=8d76919c1a) | Sep 11, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [603514ef84](https://linux-hardware.org/?probe=603514ef84) | Sep 09, 2022 |
| HP            | Laptop 15-dw0xxx            | [90908282f2](https://linux-hardware.org/?probe=90908282f2) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| Notebook      | NL40_50CU                   | [af0da080ec](https://linux-hardware.org/?probe=af0da080ec) | Sep 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| Lenovo        | ThinkPad P1 20MDS0FC00      | [dcdde00f17](https://linux-hardware.org/?probe=dcdde00f17) | Aug 29, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| Dell          | Latitude 5511               | [22c835a93a](https://linux-hardware.org/?probe=22c835a93a) | Aug 25, 2022 |
| Apple         | MacBookAir6,2               | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Dell          | Vostro 3360                 | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Dell          | XPS 15 9560                 | [d1fb1214f6](https://linux-hardware.org/?probe=d1fb1214f6) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | [fc1a1cd41f](https://linux-hardware.org/?probe=fc1a1cd41f) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| ASUSTek       | X756UQ                      | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | Laptop 15-bs0xx             | [3e63b30226](https://linux-hardware.org/?probe=3e63b30226) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| Dell          | Latitude D630               | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [882cec3541](https://linux-hardware.org/?probe=882cec3541) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Dell          | Latitude 5520               | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Acer          | Swift SF114-32              | [9e219bd7c2](https://linux-hardware.org/?probe=9e219bd7c2) | Jul 29, 2022 |
| Acer          | Aspire A315-51              | [e6f2cdc55e](https://linux-hardware.org/?probe=e6f2cdc55e) | Jul 29, 2022 |
| Dell          | Latitude 5590               | [ab7d6b9f02](https://linux-hardware.org/?probe=ab7d6b9f02) | Jul 28, 2022 |
| Dell          | Latitude E6430s             | [356556d83a](https://linux-hardware.org/?probe=356556d83a) | Jul 28, 2022 |
| Dell          | Latitude D630               | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [910067609e](https://linux-hardware.org/?probe=910067609e) | Jul 27, 2022 |
| Toshiba       | Satellite C870D-116         | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| Sony          | VGN-Z31XN_B                 | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| Panasonic     | FZ55-2                      | [a190a7d890](https://linux-hardware.org/?probe=a190a7d890) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| MSI           | Vector GP76 12UH            | [7ac84940b8](https://linux-hardware.org/?probe=7ac84940b8) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Valve         | Jupiter                     | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Lenovo        | ThinkPad E580 20KSS0GK01    | [b2d902cbc6](https://linux-hardware.org/?probe=b2d902cbc6) | Jul 21, 2022 |
| HP            | EliteBook 8570p             | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| Acer          | Aspire A515-54              | [bffac60888](https://linux-hardware.org/?probe=bffac60888) | Jul 16, 2022 |
| Acer          | Aspire A515-54              | [d52eabbac8](https://linux-hardware.org/?probe=d52eabbac8) | Jul 16, 2022 |
| HP            | ProBook 650 G5              | [471b64a407](https://linux-hardware.org/?probe=471b64a407) | Jul 16, 2022 |
| Sony          | SVE1513H1EW                 | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Sony          | VGN-Z31XN_B                 | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| Dell          | XPS 13 9360                 | [b08ab62885](https://linux-hardware.org/?probe=b08ab62885) | Jul 06, 2022 |
| NEC Comput... | NEC Versa M370              | [d4dbd6878c](https://linux-hardware.org/?probe=d4dbd6878c) | Jul 04, 2022 |
| Lenovo        | G50-45 80E3                 | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| HP            | Pavilion dm1                | [927f5b38e0](https://linux-hardware.org/?probe=927f5b38e0) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [90a56ffa69](https://linux-hardware.org/?probe=90a56ffa69) | Jun 27, 2022 |
| ASUSTek       | X555LJ                      | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Dell          | Latitude E6330              | [969981b8cb](https://linux-hardware.org/?probe=969981b8cb) | Jun 25, 2022 |
| ASUSTek       | GL502VMK                    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| HP            | ProBook 470 G5              | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| Unknown       | Unknown                     | [812caba8bf](https://linux-hardware.org/?probe=812caba8bf) | Jun 16, 2022 |
| Apple         | MacBookPro14,1              | [4b6c230717](https://linux-hardware.org/?probe=4b6c230717) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| HP            | Compaq 8710w                | [666f2ebcf0](https://linux-hardware.org/?probe=666f2ebcf0) | Jun 08, 2022 |
| Apple         | MacBookPro10,1              | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| HP            | ProBook 470 G1              | [ea56369709](https://linux-hardware.org/?probe=ea56369709) | Jun 03, 2022 |
| Samsung       | 750XED                      | [1a900ee340](https://linux-hardware.org/?probe=1a900ee340) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| Toshiba       | Satellite C70D-A            | [70313d6ed4](https://linux-hardware.org/?probe=70313d6ed4) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | [820a9fb182](https://linux-hardware.org/?probe=820a9fb182) | May 30, 2022 |
| SLIMBOOK      | TITAN                       | [1029a819d7](https://linux-hardware.org/?probe=1029a819d7) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | [c4e27f4d19](https://linux-hardware.org/?probe=c4e27f4d19) | May 29, 2022 |
| HP            | Pavilion 17                 | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | [475315dc10](https://linux-hardware.org/?probe=475315dc10) | May 28, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [397d64e10c](https://linux-hardware.org/?probe=397d64e10c) | May 27, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [a74cc1410a](https://linux-hardware.org/?probe=a74cc1410a) | May 27, 2022 |
| HP            | Pavilion g6                 | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| HP            | OMEN by Laptop              | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| ASUSTek       | X756UQ                      | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Medion        | P6624                       | [ed8bd28269](https://linux-hardware.org/?probe=ed8bd28269) | May 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [a0597ba198](https://linux-hardware.org/?probe=a0597ba198) | May 20, 2022 |
| HP            | ProBook 470 G2              | [9d14cc23ca](https://linux-hardware.org/?probe=9d14cc23ca) | May 20, 2022 |
| HP            | ProBook 470 G2              | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | ProBook 470 G2              | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| ASUSTek       | GL552VW                     | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | [0f8829e460](https://linux-hardware.org/?probe=0f8829e460) | May 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS4X50... | [0fb588c686](https://linux-hardware.org/?probe=0fb588c686) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | [83b27998e5](https://linux-hardware.org/?probe=83b27998e5) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3f84f4220e](https://linux-hardware.org/?probe=3f84f4220e) | May 14, 2022 |
| Sony          | VPCEH1M0E                   | [eefe7eee06](https://linux-hardware.org/?probe=eefe7eee06) | May 13, 2022 |
| HP            | ProBook 470 G1              | [06030eee20](https://linux-hardware.org/?probe=06030eee20) | May 13, 2022 |
| MSI           | GF63 Thin 9SC               | [a6f5c6215d](https://linux-hardware.org/?probe=a6f5c6215d) | May 11, 2022 |
| Dell          | XPS 13 9305                 | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [8080b9becd](https://linux-hardware.org/?probe=8080b9becd) | May 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [1d84f1a74a](https://linux-hardware.org/?probe=1d84f1a74a) | May 07, 2022 |
| Dell          | Latitude E6330              | [cbfc4e6f78](https://linux-hardware.org/?probe=cbfc4e6f78) | May 07, 2022 |
| Lenovo        | ThinkPad X280 20KES94F05    | [16b4cbc9fb](https://linux-hardware.org/?probe=16b4cbc9fb) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [a7396f278d](https://linux-hardware.org/?probe=a7396f278d) | May 02, 2022 |
| Dell          | XPS 15 9570                 | [01a95b61fe](https://linux-hardware.org/?probe=01a95b61fe) | May 02, 2022 |
| ASUSTek       | X550LD                      | [5625deb6aa](https://linux-hardware.org/?probe=5625deb6aa) | May 01, 2022 |
| ASUSTek       | X756UQ                      | [130944084d](https://linux-hardware.org/?probe=130944084d) | May 01, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [0e0d0dd3aa](https://linux-hardware.org/?probe=0e0d0dd3aa) | Apr 30, 2022 |
| ASUSTek       | X756UQ                      | [2543d87831](https://linux-hardware.org/?probe=2543d87831) | Apr 30, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [21fcbc1850](https://linux-hardware.org/?probe=21fcbc1850) | Apr 27, 2022 |
| Dell          | XPS 13 9305                 | [edf60be002](https://linux-hardware.org/?probe=edf60be002) | Apr 26, 2022 |
| BLAUPUNKT     | Discovery 1011WI            | [c20b87673e](https://linux-hardware.org/?probe=c20b87673e) | Apr 24, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | [762843e768](https://linux-hardware.org/?probe=762843e768) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | [11ec4d291b](https://linux-hardware.org/?probe=11ec4d291b) | Apr 23, 2022 |
| Fujitsu       | LIFEBOOK E744               | [ca56dc9824](https://linux-hardware.org/?probe=ca56dc9824) | Apr 21, 2022 |
| ASUSTek       | GL502VMK                    | [cc5ed34db8](https://linux-hardware.org/?probe=cc5ed34db8) | Apr 21, 2022 |
| Lenovo        | ThinkPad T520 4243AP1       | [7723ab4bd9](https://linux-hardware.org/?probe=7723ab4bd9) | Apr 19, 2022 |
| MSI           | GL65 Leopard 10SER          | [2bdfe0279e](https://linux-hardware.org/?probe=2bdfe0279e) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440s 20ARS1940... | [a7fbe1af34](https://linux-hardware.org/?probe=a7fbe1af34) | Apr 18, 2022 |
| ASUSTek       | G752VSK                     | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | [7b1d2ec5a1](https://linux-hardware.org/?probe=7b1d2ec5a1) | Apr 17, 2022 |
| Acer          | Aspire 5735                 | [e43434e15c](https://linux-hardware.org/?probe=e43434e15c) | Apr 15, 2022 |
| Dell          | Inspiron 15-3567            | [4639b09a3e](https://linux-hardware.org/?probe=4639b09a3e) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [b80dc08588](https://linux-hardware.org/?probe=b80dc08588) | Apr 14, 2022 |
| Dell          | Latitude 5591               | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [5aafaf0890](https://linux-hardware.org/?probe=5aafaf0890) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [983dbbf9e8](https://linux-hardware.org/?probe=983dbbf9e8) | Apr 13, 2022 |
| Acer          | Aspire 7745G                | [7ea9773813](https://linux-hardware.org/?probe=7ea9773813) | Apr 12, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [09f8f09862](https://linux-hardware.org/?probe=09f8f09862) | Apr 11, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [da1cd5bf6e](https://linux-hardware.org/?probe=da1cd5bf6e) | Apr 11, 2022 |
| Google        | Akali 360                   | [dccccb359b](https://linux-hardware.org/?probe=dccccb359b) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2ce1788c33](https://linux-hardware.org/?probe=2ce1788c33) | Apr 11, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [01f57dd952](https://linux-hardware.org/?probe=01f57dd952) | Apr 10, 2022 |
| HP            | ProBook 470 G2              | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Dell          | Latitude E6430              | [dd09c863c8](https://linux-hardware.org/?probe=dd09c863c8) | Apr 08, 2022 |
| HP            | ProBook 430 G1              | [8bcbe236a7](https://linux-hardware.org/?probe=8bcbe236a7) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [af324f356f](https://linux-hardware.org/?probe=af324f356f) | Apr 07, 2022 |
| HP            | ZBook 15 G3                 | [27bddd0a9c](https://linux-hardware.org/?probe=27bddd0a9c) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [fc358abe4b](https://linux-hardware.org/?probe=fc358abe4b) | Apr 06, 2022 |
| HP            | 470 G7 Notebook PC          | [34fc91d9ac](https://linux-hardware.org/?probe=34fc91d9ac) | Apr 06, 2022 |
| Dell          | Latitude 5410               | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| Dell          | XPS 13 7390                 | [8c4011afa9](https://linux-hardware.org/?probe=8c4011afa9) | Apr 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [94a9015090](https://linux-hardware.org/?probe=94a9015090) | Apr 03, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| ASUSTek       | X540LA                      | [732406d8b0](https://linux-hardware.org/?probe=732406d8b0) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [086261ecef](https://linux-hardware.org/?probe=086261ecef) | Apr 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [4731581e9b](https://linux-hardware.org/?probe=4731581e9b) | Mar 31, 2022 |
| HP            | ZBook Studio G4             | [d5ec5c3e8e](https://linux-hardware.org/?probe=d5ec5c3e8e) | Mar 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Medion        | Crawler E25                 | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belgium/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 162       | 10.89%  |
| Ubuntu 22.04                 | 97        | 6.52%   |
| Ubuntu 18.04                 | 82        | 5.51%   |
| Zorin 16                     | 35        | 2.35%   |
| Debian 12                    | 35        | 2.35%   |
| Arch Rolling                 | 34        | 2.28%   |
| ArcoLinux Rolling            | 33        | 2.22%   |
| Ubuntu 24.04                 | 27        | 1.81%   |
| Debian 11                    | 26        | 1.75%   |
| OpenMandriva 4.3             | 24        | 1.61%   |
| Manjaro                      | 22        | 1.48%   |
| Linux Mint 20.3              | 22        | 1.48%   |
| Pop!_OS 22.04                | 20        | 1.34%   |
| OpenMandriva 4.2             | 20        | 1.34%   |
| openSUSE Tumbleweed-XXXXXXXX | 18        | 1.21%   |
| Linux Mint 20.1              | 18        | 1.21%   |
| Fedora 36                    | 18        | 1.21%   |
| Fedora 38                    | 17        | 1.14%   |
| Xubuntu 20.04                | 16        | 1.08%   |
| Ubuntu 19.10                 | 16        | 1.08%   |
| Arch                         | 16        | 1.08%   |
| Zorin 17                     | 14        | 0.94%   |
| Linux Mint 20                | 14        | 0.94%   |
| Fedora 40                    | 14        | 0.94%   |
| OpenMandriva 24.07           | 13        | 0.87%   |
| OpenMandriva 23.01           | 13        | 0.87%   |
| Linux Mint 19.3              | 13        | 0.87%   |
| Fedora 39                    | 13        | 0.87%   |
| OpenMandriva 23.03           | 12        | 0.81%   |
| Ubuntu 20.10                 | 11        | 0.74%   |
| Pop!_OS 21.04                | 11        | 0.74%   |
| Pop!_OS 20.04                | 11        | 0.74%   |
| Linux Mint 21.3              | 11        | 0.74%   |
| Linux Mint 21.1              | 11        | 0.74%   |
| KDE neon 20.04               | 11        | 0.74%   |
| Ubuntu 21.04                 | 10        | 0.67%   |
| Ubuntu 19.04                 | 10        | 0.67%   |
| Linux Mint 21                | 10        | 0.67%   |
| Linux Mint 20.2              | 10        | 0.67%   |
| Fedora 37                    | 10        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 433       | 31.2%   |
| Linux Mint    | 128       | 9.22%   |
| OpenMandriva  | 104       | 7.49%   |
| Fedora        | 104       | 7.49%   |
| Debian        | 81        | 5.84%   |
| Zorin         | 56        | 4.03%   |
| Arch          | 49        | 3.53%   |
| Pop!_OS       | 47        | 3.39%   |
| Manjaro       | 43        | 3.1%    |
| Kubuntu       | 36        | 2.59%   |
| Xubuntu       | 34        | 2.45%   |
| ArcoLinux     | 34        | 2.45%   |
| openSUSE      | 27        | 1.95%   |
| ROSA          | 19        | 1.37%   |
| KDE neon      | 16        | 1.15%   |
| Lubuntu       | 15        | 1.08%   |
| Elementary    | 15        | 1.08%   |
| Ubuntu Unity  | 14        | 1.01%   |
| Ubuntu MATE   | 10        | 0.72%   |
| SteamOS       | 10        | 0.72%   |
| Gentoo        | 10        | 0.72%   |
| Kali          | 8         | 0.58%   |
| Endless       | 8         | 0.58%   |
| LMDE          | 7         | 0.5%    |
| MX            | 6         | 0.43%   |
| EndeavourOS   | 5         | 0.36%   |
| Clear Linux   | 5         | 0.36%   |
| CentOS        | 5         | 0.36%   |
| BlackPanther  | 5         | 0.36%   |
| Ubuntu Budgie | 4         | 0.29%   |
| Nobara        | 4         | 0.29%   |
| Garuda Linux  | 4         | 0.29%   |
| NixOS         | 3         | 0.22%   |
| LinuxFX       | 3         | 0.22%   |
| Bazzite       | 3         | 0.22%   |
| Vanilla       | 2         | 0.14%   |
| Ultramarine   | 2         | 0.14%   |
| Rocky Linux   | 2         | 0.14%   |
| Parrot        | 2         | 0.14%   |
| AlmaLinux     | 2         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 22        | 1.34%   |
| 5.10.14-desktop-1omv4002 | 19        | 1.16%   |
| 5.4.0-42-generic         | 17        | 1.03%   |
| 5.4.0-58-generic         | 16        | 0.97%   |
| 5.3.0-42-generic         | 15        | 0.91%   |
| 5.4.0-48-generic         | 13        | 0.79%   |
| 6.2.6-desktop-1omv2390   | 12        | 0.73%   |
| 6.10.0-desktop-1omv2490  | 12        | 0.73%   |
| 6.1.1-desktop-1omv2290   | 11        | 0.67%   |
| 6.1.0-18-amd64           | 11        | 0.67%   |
| 5.4.0-66-generic         | 11        | 0.67%   |
| 5.15.0-56-generic        | 11        | 0.67%   |
| 5.15.0-48-generic        | 11        | 0.67%   |
| 5.4.0-29-generic         | 10        | 0.61%   |
| 5.3.0-46-generic         | 10        | 0.61%   |
| 5.15.0-58-generic        | 10        | 0.61%   |
| 5.15.0-46-generic        | 10        | 0.61%   |
| 6.8.0-41-generic         | 9         | 0.55%   |
| 5.8.0-43-generic         | 9         | 0.55%   |
| 5.15.0-52-generic        | 9         | 0.55%   |
| 5.11.0-43-generic        | 9         | 0.55%   |
| 5.10.0-21-amd64          | 9         | 0.55%   |
| 6.2.0-26-generic         | 8         | 0.49%   |
| 5.4.0-74-generic         | 8         | 0.49%   |
| 5.15.0-91-generic        | 8         | 0.49%   |
| 5.13.0-39-generic        | 8         | 0.49%   |
| 6.5.0-14-generic         | 7         | 0.43%   |
| 6.4.11-desktop-1omv2390  | 7         | 0.43%   |
| 5.4.0-65-generic         | 7         | 0.43%   |
| 5.4.0-52-generic         | 7         | 0.43%   |
| 5.4.0-40-generic         | 7         | 0.43%   |
| 5.4.0-26-generic         | 7         | 0.43%   |
| 5.15.0-47-generic        | 7         | 0.43%   |
| 5.13.0-28-generic        | 7         | 0.43%   |
| 5.11.0-7620-generic      | 7         | 0.43%   |
| 5.11.0-38-generic        | 7         | 0.43%   |
| 5.10.0-20-amd64          | 7         | 0.43%   |
| 5.0.0-29-generic         | 7         | 0.43%   |
| 6.8.0-40-generic         | 6         | 0.37%   |
| 6.6.2-desktop-1omv2390   | 6         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 201       | 13%     |
| 5.15.0  | 145       | 9.38%   |
| 5.11.0  | 70        | 4.53%   |
| 5.13.0  | 61        | 3.95%   |
| 5.8.0   | 58        | 3.75%   |
| 4.15.0  | 58        | 3.75%   |
| 6.8.0   | 51        | 3.3%    |
| 5.3.0   | 49        | 3.17%   |
| 6.5.0   | 42        | 2.72%   |
| 6.1.0   | 40        | 2.59%   |
| 5.10.0  | 39        | 2.52%   |
| 6.2.0   | 33        | 2.13%   |
| 5.19.0  | 33        | 2.13%   |
| 5.0.0   | 30        | 1.94%   |
| 5.16.7  | 22        | 1.42%   |
| 4.18.0  | 22        | 1.42%   |
| 5.10.14 | 19        | 1.23%   |
| 6.2.6   | 13        | 0.84%   |
| 6.10.0  | 12        | 0.78%   |
| 6.1.1   | 11        | 0.71%   |
| 6.9.3   | 7         | 0.45%   |
| 6.4.11  | 7         | 0.45%   |
| 6.6.2   | 6         | 0.39%   |
| 5.17.5  | 6         | 0.39%   |
| 4.9.20  | 6         | 0.39%   |
| 4.19.0  | 6         | 0.39%   |
| 6.12.1  | 5         | 0.32%   |
| 6.0.0   | 5         | 0.32%   |
| 5.18.12 | 5         | 0.32%   |
| 5.14.0  | 5         | 0.32%   |
| 4.18.16 | 5         | 0.32%   |
| 6.9.12  | 4         | 0.26%   |
| 6.5.9   | 4         | 0.26%   |
| 6.5.5   | 4         | 0.26%   |
| 6.5.12  | 4         | 0.26%   |
| 6.2.9   | 4         | 0.26%   |
| 6.2.8   | 4         | 0.26%   |
| 6.2.11  | 4         | 0.26%   |
| 6.0.12  | 4         | 0.26%   |
| 5.18.0  | 4         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 219       | 14.42%  |
| 5.15    | 167       | 10.99%  |
| 5.11    | 79        | 5.2%    |
| 5.10    | 73        | 4.81%   |
| 5.8     | 71        | 4.67%   |
| 5.13    | 70        | 4.61%   |
| 6.1     | 68        | 4.48%   |
| 6.2     | 66        | 4.34%   |
| 6.5     | 65        | 4.28%   |
| 6.8     | 64        | 4.21%   |
| 4.15    | 58        | 3.82%   |
| 5.3     | 55        | 3.62%   |
| 5.19    | 46        | 3.03%   |
| 5.16    | 40        | 2.63%   |
| 5.0     | 32        | 2.11%   |
| 4.18    | 28        | 1.84%   |
| 6.6     | 25        | 1.65%   |
| 6.9     | 24        | 1.58%   |
| 6.10    | 23        | 1.51%   |
| 6.0     | 22        | 1.45%   |
| 5.18    | 22        | 1.45%   |
| 5.17    | 22        | 1.45%   |
| 6.4     | 21        | 1.38%   |
| 5.14    | 19        | 1.25%   |
| 6.11    | 15        | 0.99%   |
| 5.12    | 15        | 0.99%   |
| 4.9     | 15        | 0.99%   |
| 6.3     | 13        | 0.86%   |
| 5.6     | 12        | 0.79%   |
| 6.7     | 11        | 0.72%   |
| 6.12    | 10        | 0.66%   |
| 5.9     | 10        | 0.66%   |
| 4.19    | 10        | 0.66%   |
| 5.7     | 8         | 0.53%   |
| 5.5     | 5         | 0.33%   |
| 4.4     | 4         | 0.26%   |
| 5.1     | 3         | 0.2%    |
| 5.2     | 2         | 0.13%   |
| 4.17    | 2         | 0.13%   |
| 4.1     | 2         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1295      | 97.52%  |
| i686    | 32        | 2.41%   |
| aarch64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 615       | 43.56%  |
| KDE5             | 217       | 15.37%  |
| Unknown          | 149       | 10.55%  |
| XFCE             | 115       | 8.14%   |
| X-Cinnamon       | 102       | 7.22%   |
| MATE             | 38        | 2.69%   |
| LXQt             | 27        | 1.91%   |
| KDE              | 22        | 1.56%   |
| KDE6             | 16        | 1.13%   |
| Pantheon         | 15        | 1.06%   |
| Unity            | 14        | 0.99%   |
| KDE4             | 12        | 0.85%   |
| i3               | 12        | 0.85%   |
| Cinnamon         | 11        | 0.78%   |
| Budgie           | 10        | 0.71%   |
| sway             | 5         | 0.35%   |
| Hyprland         | 5         | 0.35%   |
| Openbox          | 3         | 0.21%   |
| LXDE             | 3         | 0.21%   |
| GNOME Flashback  | 3         | 0.21%   |
| awesome          | 3         | 0.21%   |
| qtile            | 2         | 0.14%   |
| LeftWM           | 2         | 0.14%   |
| bspwm            | 2         | 0.14%   |
| xmonad           | 1         | 0.07%   |
| UKUI             | 1         | 0.07%   |
| Trinity          | 1         | 0.07%   |
| spectrwm         | 1         | 0.07%   |
| lightdm-xsession | 1         | 0.07%   |
| icewm            | 1         | 0.07%   |
| GNOME Classic    | 1         | 0.07%   |
| Enlightenment    | 1         | 0.07%   |
| Deepin           | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 972       | 70.49%  |
| Wayland | 322       | 23.35%  |
| Unknown | 73        | 5.29%   |
| Tty     | 12        | 0.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 612       | 43.5%   |
| SDDM    | 239       | 16.99%  |
| GDM3    | 199       | 14.14%  |
| GDM     | 160       | 11.37%  |
| LightDM | 146       | 10.38%  |
| TDM     | 37        | 2.63%   |
| KDM     | 11        | 0.78%   |
| XDM     | 2         | 0.14%   |
| SLiM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 513       | 37.36%  |
| fr_BE      | 224       | 16.31%  |
| nl_BE      | 189       | 13.77%  |
| Unknown    | 121       | 8.81%   |
| en_GB      | 81        | 5.9%    |
| fr_FR      | 73        | 5.32%   |
| nl_NL      | 68        | 4.95%   |
| C          | 24        | 1.75%   |
| de_DE      | 16        | 1.17%   |
| pl_PL      | 8         | 0.58%   |
| de_BE      | 7         | 0.51%   |
| ru_RU      | 5         | 0.36%   |
| en_IE      | 5         | 0.36%   |
| ro_RO      | 4         | 0.29%   |
| es_ES      | 4         | 0.29%   |
| POSIX      | 3         | 0.22%   |
| uk_UA      | 2         | 0.15%   |
| tr_TR      | 2         | 0.15%   |
| pt_PT      | 2         | 0.15%   |
| it_IT      | 2         | 0.15%   |
| en_DK      | 2         | 0.15%   |
| en_CA      | 2         | 0.15%   |
| en_BE      | 2         | 0.15%   |
| C.UTF8     | 2         | 0.15%   |
| tt_RU      | 1         | 0.07%   |
| pt_BR      | 1         | 0.07%   |
| pl_PL.UTF8 | 1         | 0.07%   |
| nl_BE.UTF8 | 1         | 0.07%   |
| nl_AW      | 1         | 0.07%   |
| ku_TR      | 1         | 0.07%   |
| it_CH      | 1         | 0.07%   |
| fr_CH      | 1         | 0.07%   |
| en_ZA      | 1         | 0.07%   |
| en_US.UTF8 | 1         | 0.07%   |
| en_IN      | 1         | 0.07%   |
| bg_BG      | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 704       | 51.58%  |
| BIOS | 661       | 48.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 981       | 70.88%  |
| Btrfs   | 173       | 12.5%   |
| Overlay | 105       | 7.59%   |
| Tmpfs   | 65        | 4.7%    |
| Unknown | 32        | 2.31%   |
| Xfs     | 18        | 1.3%    |
| Zfs     | 8         | 0.58%   |
| Ext2    | 2         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 645       | 46.98%  |
| GPT     | 585       | 42.61%  |
| MBR     | 143       | 10.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1168      | 85.88%  |
| Yes       | 192       | 14.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 990       | 73.39%  |
| Yes       | 359       | 26.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 286       | 21.57%  |
| Lenovo              | 246       | 18.55%  |
| Dell                | 224       | 16.89%  |
| ASUSTek Computer    | 138       | 10.41%  |
| Acer                | 98        | 7.39%   |
| Apple               | 38        | 2.87%   |
| Toshiba             | 36        | 2.71%   |
| MSI                 | 36        | 2.71%   |
| Sony                | 34        | 2.56%   |
| Medion              | 32        | 2.41%   |
| Notebook            | 25        | 1.89%   |
| Packard Bell        | 18        | 1.36%   |
| TUXEDO              | 11        | 0.83%   |
| Samsung Electronics | 11        | 0.83%   |
| Valve               | 10        | 0.75%   |
| Unknown             | 10        | 0.75%   |
| Fujitsu             | 8         | 0.6%    |
| Alienware           | 6         | 0.45%   |
| PC Specialist       | 5         | 0.38%   |
| Google              | 5         | 0.38%   |
| Gigabyte Technology | 5         | 0.38%   |
| HUAWEI              | 4         | 0.3%    |
| Fujitsu Siemens     | 4         | 0.3%    |
| Clevo               | 4         | 0.3%    |
| Intel               | 3         | 0.23%   |
| VALE                | 2         | 0.15%   |
| Teclast             | 2         | 0.15%   |
| Schenker            | 2         | 0.15%   |
| Razer               | 2         | 0.15%   |
| Panasonic           | 2         | 0.15%   |
| YJKC                | 1         | 0.08%   |
| TrekStor            | 1         | 0.08%   |
| Timi                | 1         | 0.08%   |
| Standard            | 1         | 0.08%   |
| SLIMBOOK            | 1         | 0.08%   |
| PEAQ                | 1         | 0.08%   |
| NEC Computers       | 1         | 0.08%   |
| Inter Sales A/S     | 1         | 0.08%   |
| Hampoo              | 1         | 0.08%   |
| GPD                 | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 13        | 0.98%   |
| Valve Jupiter                            | 10        | 0.75%   |
| HP Pavilion Notebook                     | 9         | 0.68%   |
| HP Pavilion 17                           | 9         | 0.68%   |
| HP Pavilion g7                           | 7         | 0.53%   |
| HP Pavilion dv7                          | 7         | 0.53%   |
| HP EliteBook 850 G8 Notebook PC          | 7         | 0.53%   |
| HP ProBook 650 G1                        | 6         | 0.45%   |
| HP Pavilion dv6                          | 6         | 0.45%   |
| Dell Latitude 5530                       | 6         | 0.45%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5         | 5         | 0.38%   |
| HP ProBook 6570b                         | 5         | 0.38%   |
| HP Pavilion Laptop 15-eh1xxx             | 5         | 0.38%   |
| HP Pavilion Laptop 15-cw0xxx             | 5         | 0.38%   |
| HP Notebook                              | 5         | 0.38%   |
| Dell XPS 15 9560                         | 5         | 0.38%   |
| Dell XPS 13 7390                         | 5         | 0.38%   |
| Toshiba Satellite C660                   | 4         | 0.3%    |
| Lenovo ThinkPad L390 20NSS1YV0B          | 4         | 0.3%    |
| HP ProBook 470 G2                        | 4         | 0.3%    |
| HP Laptop 15-db0xxx                      | 4         | 0.3%    |
| Gigabyte Spring Peak                     | 4         | 0.3%    |
| Dell XPS 15 9570                         | 4         | 0.3%    |
| Dell XPS 15 9500                         | 4         | 0.3%    |
| Dell XPS 13 9370                         | 4         | 0.3%    |
| Dell XPS 13 9360                         | 4         | 0.3%    |
| Dell Precision M4800                     | 4         | 0.3%    |
| Dell Latitude E7440                      | 4         | 0.3%    |
| Dell Latitude E6540                      | 4         | 0.3%    |
| Dell Latitude 5520                       | 4         | 0.3%    |
| Dell Latitude 5510                       | 4         | 0.3%    |
| ASUS VivoBook_ASUSLaptop K3605ZU_K3605ZU | 4         | 0.3%    |
| ASUS ROG Strix G512LV_G512LV             | 4         | 0.3%    |
| Toshiba Satellite C70D-A                 | 3         | 0.23%   |
| MSI GF63 Thin 9SC                        | 3         | 0.23%   |
| Lenovo Y520-15IKBN 80WK                  | 3         | 0.23%   |
| Lenovo Legion 5 15ARH05 82B5             | 3         | 0.23%   |
| Lenovo IdeaPad 320-15ABR 80XS            | 3         | 0.23%   |
| HP ProBook 450 G8 Notebook PC            | 3         | 0.23%   |
| HP ProBook 445 G8 Notebook PC            | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 141       | 10.63%  |
| Dell Latitude         | 112       | 8.45%   |
| Acer Aspire           | 76        | 5.73%   |
| HP Pavilion           | 75        | 5.66%   |
| HP EliteBook          | 70        | 5.28%   |
| HP ProBook            | 59        | 4.45%   |
| Lenovo IdeaPad        | 48        | 3.62%   |
| Dell XPS              | 40        | 3.02%   |
| Toshiba Satellite     | 32        | 2.41%   |
| Dell Precision        | 25        | 1.89%   |
| Dell Inspiron         | 23        | 1.73%   |
| Lenovo Legion         | 22        | 1.66%   |
| HP Laptop             | 22        | 1.66%   |
| ASUS VivoBook         | 22        | 1.66%   |
| HP ZBook              | 16        | 1.21%   |
| Packard Bell EasyNote | 14        | 1.06%   |
| HP Compaq             | 14        | 1.06%   |
| ASUS ROG              | 13        | 0.98%   |
| Unknown               | 13        | 0.98%   |
| Valve Jupiter         | 10        | 0.75%   |
| Lenovo ThinkBook      | 8         | 0.6%    |
| Dell Vostro           | 8         | 0.6%    |
| Dell Studio           | 8         | 0.6%    |
| Medion Akoya          | 7         | 0.53%   |
| Acer Nitro            | 7         | 0.53%   |
| HP ENVY               | 6         | 0.45%   |
| Fujitsu LIFEBOOK      | 6         | 0.45%   |
| ASUS Zenbook          | 6         | 0.45%   |
| Acer Swift            | 6         | 0.45%   |
| MSI GF63              | 5         | 0.38%   |
| HP Notebook           | 5         | 0.38%   |
| ASUS ASUS             | 5         | 0.38%   |
| Apple MacBookPro5     | 5         | 0.38%   |
| MSI Vector            | 4         | 0.3%    |
| HP OMEN               | 4         | 0.3%    |
| Gigabyte Spring       | 4         | 0.3%    |
| Dell G3               | 4         | 0.3%    |
| Apple MacBookPro9     | 4         | 0.3%    |
| Apple MacBookPro14    | 4         | 0.3%    |
| Apple MacBookPro11    | 4         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 124       | 9.35%   |
| 2018    | 108       | 8.14%   |
| 2012    | 106       | 7.99%   |
| 2013    | 104       | 7.84%   |
| 2019    | 103       | 7.77%   |
| 2011    | 91        | 6.86%   |
| 2021    | 90        | 6.79%   |
| 2017    | 74        | 5.58%   |
| 2016    | 73        | 5.51%   |
| 2014    | 68        | 5.13%   |
| 2008    | 62        | 4.68%   |
| 2015    | 61        | 4.6%    |
| 2010    | 60        | 4.52%   |
| 2022    | 58        | 4.37%   |
| 2023    | 43        | 3.24%   |
| 2009    | 41        | 3.09%   |
| 2007    | 31        | 2.34%   |
| 2006    | 13        | 0.98%   |
| 2024    | 10        | 0.75%   |
| 2005    | 2         | 0.15%   |
| 2004    | 2         | 0.15%   |
| Unknown | 2         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1326      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1200      | 89.42%  |
| Enabled  | 142       | 10.58%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1319      | 99.47%  |
| Yes  | 7         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 353       | 26.01%  |
| 8.01-16.0   | 276       | 20.34%  |
| 16.01-24.0  | 249       | 18.35%  |
| 3.01-4.0    | 240       | 17.69%  |
| 32.01-64.0  | 119       | 8.77%   |
| 1.01-2.0    | 46        | 3.39%   |
| 24.01-32.0  | 25        | 1.84%   |
| 64.01-256.0 | 19        | 1.4%    |
| 2.01-3.0    | 16        | 1.18%   |
| 0.51-1.0    | 13        | 0.96%   |
| 0.01-0.5    | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 488       | 32.53%  |
| 2.01-3.0   | 357       | 23.8%   |
| 4.01-8.0   | 229       | 15.27%  |
| 3.01-4.0   | 211       | 14.07%  |
| 0.51-1.0   | 97        | 6.47%   |
| 8.01-16.0  | 88        | 5.87%   |
| 0.01-0.5   | 20        | 1.33%   |
| 24.01-32.0 | 5         | 0.33%   |
| 16.01-24.0 | 5         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 975       | 71.43%  |
| 2      | 336       | 24.62%  |
| 3      | 36        | 2.64%   |
| 0      | 9         | 0.66%   |
| 4      | 6         | 0.44%   |
| 5      | 2         | 0.15%   |
| 8      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 844       | 63.27%  |
| Yes       | 490       | 36.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1151      | 86.22%  |
| No        | 184       | 13.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1300      | 97.67%  |
| No        | 31        | 2.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1038      | 77.06%  |
| No        | 309       | 22.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Belgium | 1326      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Brussels       | 206       | 14.05%  |
| Antwerp        | 104       | 7.09%   |
| Ghent          | 59        | 4.02%   |
| Liège         | 46        | 3.14%   |
| Ixelles-Elsene | 30        | 2.05%   |
| Mechelen       | 19        | 1.3%    |
| Leuven         | 19        | 1.3%    |
| Turnhout       | 18        | 1.23%   |
| Bruges         | 17        | 1.16%   |
| Herentals      | 14        | 0.95%   |
| Hasselt        | 13        | 0.89%   |
| Sint-Truiden   | 12        | 0.82%   |
| Namur          | 12        | 0.82%   |
| Anderlecht     | 12        | 0.82%   |
| Aalst          | 12        | 0.82%   |
| Uccle          | 11        | 0.75%   |
| Mons           | 11        | 0.75%   |
| Edegem         | 11        | 0.75%   |
| Schaarbeek     | 10        | 0.68%   |
| Charleroi      | 9         | 0.61%   |
| Mouscron       | 8         | 0.55%   |
| La Louvière   | 8         | 0.55%   |
| Kortrijk       | 8         | 0.55%   |
| Jette          | 8         | 0.55%   |
| Heusden-Zolder | 8         | 0.55%   |
| Harelbeke      | 8         | 0.55%   |
| Etterbeek      | 8         | 0.55%   |
| Arlon          | 8         | 0.55%   |
| Wetteren       | 7         | 0.48%   |
| Seraing        | 7         | 0.48%   |
| Schoten        | 7         | 0.48%   |
| Kontich        | 7         | 0.48%   |
| Geel           | 7         | 0.48%   |
| Gavere         | 7         | 0.48%   |
| Brasschaat     | 7         | 0.48%   |
| Boom           | 7         | 0.48%   |
| Bilzen         | 7         | 0.48%   |
| Tournai        | 6         | 0.41%   |
| Overijse       | 6         | 0.41%   |
| Mortsel        | 6         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 349       | 509    | 21.14%  |
| Seagate                     | 172       | 239    | 10.42%  |
| WDC                         | 162       | 222    | 9.81%   |
| Toshiba                     | 123       | 155    | 7.45%   |
| SanDisk                     | 95        | 122    | 5.75%   |
| SK hynix                    | 88        | 110    | 5.33%   |
| Kingston                    | 80        | 105    | 4.85%   |
| Unknown                     | 69        | 82     | 4.18%   |
| Intel                       | 67        | 79     | 4.06%   |
| Micron Technology           | 56        | 67     | 3.39%   |
| Hitachi                     | 51        | 63     | 3.09%   |
| HGST                        | 47        | 64     | 2.85%   |
| Crucial                     | 42        | 54     | 2.54%   |
| Apple                       | 22        | 32     | 1.33%   |
| KIOXIA                      | 21        | 23     | 1.27%   |
| LITEON                      | 15        | 17     | 0.91%   |
| Fujitsu                     | 15        | 21     | 0.91%   |
| China                       | 12        | 14     | 0.73%   |
| LITEONIT                    | 10        | 14     | 0.61%   |
| Intenso                     | 10        | 11     | 0.61%   |
| Micron/Crucial Technology   | 9         | 12     | 0.55%   |
| Kingston Technology Company | 9         | 9      | 0.55%   |
| PNY                         | 7         | 8      | 0.42%   |
| A-DATA Technology           | 7         | 9      | 0.42%   |
| Transcend                   | 6         | 6      | 0.36%   |
| Phison                      | 6         | 6      | 0.36%   |
| Phison Electronics          | 5         | 7      | 0.3%    |
| GOODRAM                     | 5         | 7      | 0.3%    |
| Emtec                       | 5         | 5      | 0.3%    |
| SSSTC                       | 4         | 4      | 0.24%   |
| Silicon Motion              | 4         | 5      | 0.24%   |
| OCZ                         | 4         | 5      | 0.24%   |
| Corsair                     | 4         | 4      | 0.24%   |
| ASMT                        | 4         | 4      | 0.24%   |
| Union Memory (Shenzhen)     | 3         | 3      | 0.18%   |
| KingSpec                    | 3         | 4      | 0.18%   |
| JMicron Technology          | 3         | 5      | 0.18%   |
| Zheino                      | 2         | 2      | 0.12%   |
| Verbatim                    | 2         | 2      | 0.12%   |
| Union Memory                | 2         | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 21        | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 20        | 1.16%   |
| SanDisk NVMe SSD Drive 512GB                         | 20        | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 19        | 1.1%    |
| Samsung NVMe SSD Drive 512GB                         | 17        | 0.99%   |
| Samsung SSD 860 EVO 500GB                            | 16        | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 16        | 0.93%   |
| HGST HTS721010A9E630 1TB                             | 16        | 0.93%   |
| Toshiba MQ01ABD100 1TB                               | 14        | 0.81%   |
| Samsung SSD 850 EVO 250GB                            | 14        | 0.81%   |
| Samsung NVMe SSD Drive 1TB                           | 14        | 0.81%   |
| Unknown MMC Card  32GB                               | 13        | 0.76%   |
| Seagate ST9500325AS 500GB                            | 13        | 0.76%   |
| Samsung SSD 850 EVO 500GB                            | 13        | 0.76%   |
| Intel NVMe SSD Drive 512GB                           | 13        | 0.76%   |
| SK hynix NVMe SSD Drive 512GB                        | 12        | 0.7%    |
| Unknown MMC Card  128GB                              | 10        | 0.58%   |
| Samsung SSD 870 EVO 500GB                            | 10        | 0.58%   |
| HGST HTS725050A7E630 500GB                           | 10        | 0.58%   |
| Samsung SSD 860 EVO 1TB                              | 9         | 0.52%   |
| Kingston SA400S37120G 120GB SSD                      | 9         | 0.52%   |
| Seagate ST1000LM048-2E7172 1TB                       | 8         | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                     | 8         | 0.47%   |
| Hitachi HTS547550A9E384 500GB                        | 8         | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 7         | 0.41%   |
| Toshiba MQ04ABF100 1TB                               | 7         | 0.41%   |
| Seagate ST2000LM015-2E8174 2TB                       | 7         | 0.41%   |
| Seagate Expansion 1TB                                | 7         | 0.41%   |
| Kingston SA400S37240G 240GB SSD                      | 7         | 0.41%   |
| Intel SSD 660P Series 1024GB                         | 7         | 0.41%   |
| HGST HTS545050A7E680 500GB                           | 7         | 0.41%   |
| Toshiba MQ01ABF050 500GB                             | 6         | 0.35%   |
| Seagate ST500LT012-1DG142 500GB                      | 6         | 0.35%   |
| SanDisk NVMe SSD Drive 1TB                           | 6         | 0.35%   |
| Samsung SSD 870 EVO 1TB                              | 6         | 0.35%   |
| Samsung SSD 860 EVO 250GB                            | 6         | 0.35%   |
| Samsung NVMe SSD Drive 500GB                         | 6         | 0.35%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB              | 6         | 0.35%   |
| Kingston SV300S37A240G 240GB SSD                     | 6         | 0.35%   |
| Kingston SA400S37480G 480GB SSD                      | 6         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 162       | 224    | 32.99%  |
| WDC                 | 118       | 157    | 24.03%  |
| Toshiba             | 82        | 107    | 16.7%   |
| Hitachi             | 51        | 63     | 10.39%  |
| HGST                | 47        | 64     | 9.57%   |
| Fujitsu             | 14        | 19     | 2.85%   |
| Samsung Electronics | 8         | 10     | 1.63%   |
| ASMT                | 2         | 2      | 0.41%   |
| XrayDisk            | 1         | 1      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |
| TO Exter            | 1         | 1      | 0.2%    |
| LaCie               | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| Intenso             | 1         | 1      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 175       | 253    | 33.21%  |
| Kingston            | 56        | 70     | 10.63%  |
| SanDisk             | 42        | 59     | 7.97%   |
| Crucial             | 34        | 44     | 6.45%   |
| SK hynix            | 22        | 33     | 4.17%   |
| Intel               | 22        | 24     | 4.17%   |
| WDC                 | 21        | 31     | 3.98%   |
| Toshiba             | 16        | 19     | 3.04%   |
| Micron Technology   | 16        | 17     | 3.04%   |
| LITEON              | 14        | 16     | 2.66%   |
| China               | 12        | 14     | 2.28%   |
| Apple               | 12        | 17     | 2.28%   |
| LITEONIT            | 10        | 14     | 1.9%    |
| Intenso             | 8         | 9      | 1.52%   |
| PNY                 | 6         | 7      | 1.14%   |
| Transcend           | 5         | 5      | 0.95%   |
| GOODRAM             | 5         | 7      | 0.95%   |
| Emtec               | 5         | 5      | 0.95%   |
| A-DATA Technology   | 5         | 7      | 0.95%   |
| OCZ                 | 4         | 5      | 0.76%   |
| KingSpec            | 3         | 4      | 0.57%   |
| Zheino              | 2         | 2      | 0.38%   |
| Verbatim            | 2         | 2      | 0.38%   |
| SPCC                | 2         | 4      | 0.38%   |
| Reeinno             | 2         | 4      | 0.38%   |
| Phison              | 2         | 2      | 0.38%   |
| Patriot             | 2         | 2      | 0.38%   |
| Netac               | 2         | 2      | 0.38%   |
| Fujitsu             | 2         | 2      | 0.38%   |
| Corsair             | 2         | 2      | 0.38%   |
| Teclast             | 1         | 1      | 0.19%   |
| sobetter            | 1         | 1      | 0.19%   |
| Ramaxel Technology  | 1         | 1      | 0.19%   |
| Plextor             | 1         | 1      | 0.19%   |
| OWC                 | 1         | 2      | 0.19%   |
| Leven               | 1         | 1      | 0.19%   |
| INTEL SS            | 1         | 1      | 0.19%   |
| Innodisk            | 1         | 1      | 0.19%   |
| Indilinx            | 1         | 1      | 0.19%   |
| HEORIADY            | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 516       | 717    | 33.16%  |
| SSD     | 495       | 699    | 31.81%  |
| HDD     | 464       | 653    | 29.82%  |
| MMC     | 63        | 76     | 4.05%   |
| Unknown | 18        | 30     | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 841       | 1287   | 56.67%  |
| NVMe | 514       | 714    | 34.64%  |
| SAS  | 66        | 98     | 4.45%   |
| MMC  | 63        | 76     | 4.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 675       | 927    | 69.23%  |
| 0.51-1.0   | 255       | 368    | 26.15%  |
| 1.01-2.0   | 28        | 34     | 2.87%   |
| 3.01-4.0   | 6         | 12     | 0.62%   |
| 4.01-10.0  | 6         | 6      | 0.62%   |
| 10.01-20.0 | 3         | 3      | 0.31%   |
| 2.01-3.0   | 2         | 2      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 427       | 29.86%  |
| 251-500        | 367       | 25.66%  |
| 501-1000       | 189       | 13.22%  |
| 1-20           | 107       | 7.48%   |
| 1001-2000      | 92        | 6.43%   |
| 51-100         | 83        | 5.8%    |
| Unknown        | 49        | 3.43%   |
| 21-50          | 44        | 3.08%   |
| More than 3000 | 43        | 3.01%   |
| 2001-3000      | 29        | 2.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 561       | 37.47%  |
| 21-50          | 269       | 17.97%  |
| 101-250        | 221       | 14.76%  |
| 51-100         | 175       | 11.69%  |
| 251-500        | 109       | 7.28%   |
| 501-1000       | 62        | 4.14%   |
| Unknown        | 49        | 3.27%   |
| 1001-2000      | 29        | 1.94%   |
| 2001-3000      | 13        | 0.87%   |
| More than 3000 | 6         | 0.4%    |
| 0              | 3         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 4         | 4      | 3.92%   |
| Seagate ST320LT007-9ZV142 320GB                | 3         | 11     | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 3         | 8      | 2.94%   |
| Toshiba MQ01ABD075 752GB                       | 2         | 2      | 1.96%   |
| Seagate ST9750420AS 752GB                      | 2         | 2      | 1.96%   |
| Seagate ST9320423AS 320GB                      | 2         | 3      | 1.96%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 2      | 1.96%   |
| Hitachi HTS545050A7E380 500GB                  | 2         | 4      | 1.96%   |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 1.96%   |
| WDC WD3200BPVT-55JJ5T0 320GB                   | 1         | 1      | 0.98%   |
| WDC WD3200BPVT-22ZEST0 320GB                   | 1         | 1      | 0.98%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 1         | 1      | 0.98%   |
| WDC WD3200BEKT-60V5T1 320GB                    | 1         | 1      | 0.98%   |
| WDC WD3200BEKT-60PVMT0 320GB                   | 1         | 1      | 0.98%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 0.98%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 0.98%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 0.98%   |
| Toshiba MQ01ABD032 320GB                       | 1         | 1      | 0.98%   |
| Toshiba MK6476GSX 640GB                        | 1         | 1      | 0.98%   |
| Toshiba MK5075GSX 500GB                        | 1         | 1      | 0.98%   |
| Toshiba MK3265GSX 320GB                        | 1         | 1      | 0.98%   |
| Toshiba MK3263GSXN 320GB                       | 1         | 1      | 0.98%   |
| Toshiba MK2555GSX 250GB                        | 1         | 1      | 0.98%   |
| Toshiba MK1655GSX 160GB                        | 1         | 1      | 0.98%   |
| Toshiba KSG60ZSE512G SATA 512GB SSD            | 1         | 1      | 0.98%   |
| SK hynix SH920 mSATA 256GB SSD                 | 1         | 1      | 0.98%   |
| SK hynix SH920 2.5 7MM 256GB SSD               | 1         | 2      | 0.98%   |
| SK hynix SC401 SATA 512GB SSD                  | 1         | 3      | 0.98%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 2      | 0.98%   |
| SK hynix HFS256G32MND-2900A 256GB SSD          | 1         | 1      | 0.98%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD          | 1         | 1      | 0.98%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 0.98%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 0.98%   |
| Seagate ST9320325AS 320GB                      | 1         | 2      | 0.98%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 0.98%   |
| Seagate ST9120822AS 120GB                      | 1         | 1      | 0.98%   |
| Seagate ST9120821AS 120GB                      | 1         | 1      | 0.98%   |
| Seagate ST9100824AS 100GB                      | 1         | 3      | 0.98%   |
| Seagate ST750LM022 HN-M750MBB 752GB            | 1         | 1      | 0.98%   |
| Seagate ST500LM000-SSHD-8GB                    | 1         | 1      | 0.98%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 41     | 23.53%  |
| Toshiba             | 12        | 12     | 11.76%  |
| Hitachi             | 11        | 13     | 10.78%  |
| Intel               | 8         | 8      | 7.84%   |
| SK hynix            | 7         | 11     | 6.86%   |
| HGST                | 7         | 8      | 6.86%   |
| WDC                 | 6         | 6      | 5.88%   |
| Kingston            | 5         | 10     | 4.9%    |
| Fujitsu             | 5         | 9      | 4.9%    |
| Micron Technology   | 4         | 4      | 3.92%   |
| SanDisk             | 3         | 3      | 2.94%   |
| Samsung Electronics | 3         | 3      | 2.94%   |
| Crucial             | 2         | 2      | 1.96%   |
| OCZ                 | 1         | 1      | 0.98%   |
| LITEON              | 1         | 1      | 0.98%   |
| China               | 1         | 1      | 0.98%   |
| Apple               | 1         | 1      | 0.98%   |
| A-DATA Technology   | 1         | 1      | 0.98%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 41     | 36.36%  |
| Toshiba             | 11        | 11     | 16.67%  |
| Hitachi             | 11        | 13     | 16.67%  |
| HGST                | 7         | 8      | 10.61%  |
| WDC                 | 6         | 6      | 9.09%   |
| Fujitsu             | 5         | 9      | 7.58%   |
| Samsung Electronics | 2         | 2      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 66        | 90     | 64.71%  |
| SSD  | 32        | 40     | 31.37%  |
| NVMe | 4         | 5      | 3.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BUCT-63TWBY0 320GB                 | 1         | 1      | 33.33%  |
| Samsung Electronics MZVLW128HEGR-000L2 128GB | 1         | 2      | 33.33%  |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 2      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 774       | 1298   | 54.7%   |
| Works    | 538       | 738    | 38.02%  |
| Malfunc  | 100       | 135    | 7.07%   |
| Failed   | 3         | 4      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 911       | 57.69%  |
| Samsung Electronics                     | 181       | 11.46%  |
| AMD                                     | 125       | 7.92%   |
| SanDisk                                 | 73        | 4.62%   |
| SK hynix                                | 66        | 4.18%   |
| Micron Technology                       | 40        | 2.53%   |
| Kingston Technology Company             | 32        | 2.03%   |
| Toshiba America Info Systems            | 28        | 1.77%   |
| KIOXIA                                  | 20        | 1.27%   |
| Micron/Crucial Technology               | 18        | 1.14%   |
| Nvidia                                  | 13        | 0.82%   |
| Phison Electronics                      | 12        | 0.76%   |
| Union Memory (Shenzhen)                 | 8         | 0.51%   |
| Solid State Storage Technology          | 8         | 0.51%   |
| Apple                                   | 7         | 0.44%   |
| Seagate Technology                      | 6         | 0.38%   |
| Marvell Technology Group                | 6         | 0.38%   |
| Silicon Motion                          | 4         | 0.25%   |
| Silicon Image                           | 4         | 0.25%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.13%   |
| Shenzhen Longsys Electronics            | 2         | 0.13%   |
| Lite-On Technology                      | 2         | 0.13%   |
| Lenovo                                  | 2         | 0.13%   |
| ADATA Technology                        | 2         | 0.13%   |
| VIA Technologies                        | 1         | 0.06%   |
| Transcend                               | 1         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.06%   |
| INNOGRIT                                | 1         | 0.06%   |
| Biwin Storage Technology                | 1         | 0.06%   |
| ASMedia Technology                      | 1         | 0.06%   |
| Unknown                                 | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 114       | 6.7%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 105       | 6.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 99        | 5.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 82        | 4.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 80        | 4.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 76        | 4.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 58        | 3.41%   |
| Intel Volume Management Device NVMe RAID Controller                            | 44        | 2.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 41        | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 40        | 2.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 40        | 2.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 36        | 2.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 36        | 2.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 35        | 2.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 35        | 2.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 28        | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 27        | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 26        | 1.53%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 19        | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 18        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 18        | 1.06%   |
| Intel SSD 660P Series                                                          | 16        | 0.94%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 15        | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                            | 15        | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 15        | 0.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 14        | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 14        | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 14        | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 13        | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 13        | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 13        | 0.76%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 12        | 0.71%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 12        | 0.71%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 11        | 0.65%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 11        | 0.65%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 11        | 0.65%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 11        | 0.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 11        | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                          | 10        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 886       | 54.56%  |
| NVMe | 515       | 31.71%  |
| RAID | 137       | 8.44%   |
| IDE  | 86        | 5.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1094      | 82.5%   |
| AMD     | 231       | 17.42%  |
| Unknown | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 26        | 1.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 24        | 1.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 24        | 1.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 21        | 1.58%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 1.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 19        | 1.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 19        | 1.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 18        | 1.35%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 17        | 1.28%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 17        | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 15        | 1.13%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 14        | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 14        | 1.05%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 13        | 0.98%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 13        | 0.98%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 12        | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz       | 12        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 11        | 0.83%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 11        | 0.83%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 10        | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 10        | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 10        | 0.75%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 10        | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 0.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 10        | 0.75%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 10        | 0.75%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 10        | 0.75%   |
| AMD Custom APU 0405                     | 10        | 0.75%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 9         | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 9         | 0.68%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 9         | 0.68%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 9         | 0.68%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 9         | 0.68%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 9         | 0.68%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 8         | 0.6%    |
| Intel Core i7-8650U CPU @ 1.90GHz       | 8         | 0.6%    |
| Intel Core i7-10510U CPU @ 1.80GHz      | 8         | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz       | 8         | 0.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz       | 8         | 0.6%    |
| AMD Ryzen 7 5800H with Radeon Graphics  | 8         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 342       | 25.77%  |
| Intel Core i5           | 306       | 23.06%  |
| Other                   | 141       | 10.63%  |
| Intel Core i3           | 96        | 7.23%   |
| Intel Core 2 Duo        | 81        | 6.1%    |
| AMD Ryzen 7             | 46        | 3.47%   |
| AMD Ryzen 5             | 46        | 3.47%   |
| Intel Celeron           | 37        | 2.79%   |
| Intel Pentium           | 23        | 1.73%   |
| Intel Atom              | 17        | 1.28%   |
| AMD Ryzen 9             | 17        | 1.28%   |
| AMD Ryzen 7 PRO         | 17        | 1.28%   |
| AMD E1                  | 15        | 1.13%   |
| Intel Pentium Dual-Core | 11        | 0.83%   |
| AMD Ryzen 5 PRO         | 11        | 0.83%   |
| AMD A6                  | 10        | 0.75%   |
| Intel Core 2            | 9         | 0.68%   |
| AMD E                   | 9         | 0.68%   |
| AMD A4                  | 9         | 0.68%   |
| Intel Genuine           | 8         | 0.6%    |
| Intel Core i9           | 7         | 0.53%   |
| AMD A8                  | 7         | 0.53%   |
| Intel Pentium Silver    | 6         | 0.45%   |
| Intel Core              | 6         | 0.45%   |
| AMD Ryzen 3             | 6         | 0.45%   |
| Intel Pentium Dual      | 4         | 0.3%    |
| AMD Turion 64 X2 Mobile | 4         | 0.3%    |
| Intel Celeron M         | 3         | 0.23%   |
| AMD A12                 | 3         | 0.23%   |
| Intel Xeon              | 2         | 0.15%   |
| Intel Pentium 4         | 2         | 0.15%   |
| Intel Core m5           | 2         | 0.15%   |
| Intel Core M            | 2         | 0.15%   |
| Intel Core Duo          | 2         | 0.15%   |
| Intel Celeron Dual-Core | 2         | 0.15%   |
| AMD Athlon X2           | 2         | 0.15%   |
| AMD Athlon II           | 2         | 0.15%   |
| AMD Athlon              | 2         | 0.15%   |
| Intel Pentium M         | 1         | 0.08%   |
| Intel Mobile Pentium 4  | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 633       | 47.7%   |
| 4       | 399       | 30.07%  |
| 6       | 109       | 8.21%   |
| 8       | 99        | 7.46%   |
| 10      | 24        | 1.81%   |
| 1       | 20        | 1.51%   |
| 12      | 14        | 1.06%   |
| 14      | 12        | 0.9%    |
| 16      | 8         | 0.6%    |
| 24      | 5         | 0.38%   |
| Unknown | 4         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1326      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1037      | 78.03%  |
| 1       | 288       | 21.67%  |
| Unknown | 4         | 0.3%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1302      | 97.97%  |
| Unknown        | 14        | 1.05%   |
| 32-bit         | 12        | 0.9%    |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 511       | 36.76%  |
| 0x306a9    | 83        | 5.97%   |
| 0x206a7    | 65        | 4.68%   |
| 0x806ea    | 41        | 2.95%   |
| 0x806ec    | 39        | 2.81%   |
| 0x1067a    | 38        | 2.73%   |
| 0x40651    | 36        | 2.59%   |
| 0x306c3    | 34        | 2.45%   |
| 0x806c1    | 29        | 2.09%   |
| 0x906ea    | 28        | 2.01%   |
| 0x306d4    | 28        | 2.01%   |
| 0x20655    | 28        | 2.01%   |
| 0x406e3    | 27        | 1.94%   |
| 0x906e9    | 23        | 1.65%   |
| 0x806e9    | 23        | 1.65%   |
| 0xa0652    | 20        | 1.44%   |
| 0x6fd      | 20        | 1.44%   |
| 0x0a50000c | 17        | 1.22%   |
| 0x30678    | 16        | 1.15%   |
| 0x08600106 | 16        | 1.15%   |
| 0x10676    | 15        | 1.08%   |
| 0x08608103 | 14        | 1.01%   |
| 0x806eb    | 10        | 0.72%   |
| 0x07030105 | 10        | 0.72%   |
| 0x806d1    | 9         | 0.65%   |
| 0x0700010f | 9         | 0.65%   |
| 0x05000119 | 9         | 0.65%   |
| 0x906a4    | 8         | 0.58%   |
| 0x6f6      | 8         | 0.58%   |
| 0x506e3    | 8         | 0.58%   |
| 0x20652    | 8         | 0.58%   |
| 0x906a3    | 7         | 0.5%    |
| 0x08600103 | 7         | 0.5%    |
| 0x08108109 | 7         | 0.5%    |
| 0x6fb      | 6         | 0.43%   |
| 0x406c4    | 6         | 0.43%   |
| 0x08108102 | 6         | 0.43%   |
| 0x06006705 | 6         | 0.43%   |
| 0x706a1    | 5         | 0.36%   |
| 0x106e5    | 5         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 260       | 19.59%  |
| IvyBridge         | 115       | 8.67%   |
| Haswell           | 100       | 7.54%   |
| SandyBridge       | 91        | 6.86%   |
| Unknown           | 76        | 5.73%   |
| Penryn            | 72        | 5.43%   |
| Skylake           | 63        | 4.75%   |
| Westmere          | 53        | 3.99%   |
| TigerLake         | 52        | 3.92%   |
| Broadwell         | 46        | 3.47%   |
| Core              | 42        | 3.17%   |
| Alderlake Hybrid  | 40        | 3.01%   |
| Zen 3             | 39        | 2.94%   |
| CometLake         | 39        | 2.94%   |
| Zen 2             | 38        | 2.86%   |
| Silvermont        | 31        | 2.34%   |
| IceLake           | 19        | 1.43%   |
| Zen+              | 16        | 1.21%   |
| Bobcat            | 16        | 1.21%   |
| Puma              | 15        | 1.13%   |
| Goldmont plus     | 14        | 1.06%   |
| Excavator         | 14        | 1.06%   |
| Zen               | 12        | 0.9%    |
| Jaguar            | 12        | 0.9%    |
| Bonnell           | 10        | 0.75%   |
| P6                | 8         | 0.6%    |
| Nehalem           | 6         | 0.45%   |
| K8 Hammer         | 5         | 0.38%   |
| K8 & K10 hybrid   | 4         | 0.3%    |
| NetBurst          | 3         | 0.23%   |
| Meteorlake Hybrid | 3         | 0.23%   |
| K10 Llano         | 3         | 0.23%   |
| K10               | 3         | 0.23%   |
| Goldmont          | 3         | 0.23%   |
| Tremont           | 2         | 0.15%   |
| Piledriver        | 2         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 958       | 56.06%  |
| Nvidia                           | 420       | 24.58%  |
| AMD                              | 329       | 19.25%  |
| VIA Technologies                 | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 105       | 5.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 76        | 4.32%   |
| Intel UHD Graphics 620                                                                   | 53        | 3.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 51        | 2.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 51        | 2.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 48        | 2.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 45        | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 44        | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 42        | 2.39%   |
| Intel HD Graphics 5500                                                                   | 39        | 2.22%   |
| Intel HD Graphics 620                                                                    | 36        | 2.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 35        | 1.99%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 34        | 1.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 32        | 1.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 30        | 1.7%    |
| Intel HD Graphics 630                                                                    | 25        | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 1.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 1.31%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 22        | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 22        | 1.25%   |
| AMD Lucienne                                                                             | 22        | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 20        | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 20        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 0.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 0.97%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 16        | 0.91%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 15        | 0.85%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 14        | 0.8%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 13        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 0.74%   |
| AMD Barcelo                                                                              | 13        | 0.74%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 12        | 0.68%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 11        | 0.63%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 11        | 0.63%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 0.63%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 10        | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 10        | 0.57%   |
| Intel HD Graphics 530                                                                    | 10        | 0.57%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 10        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 603       | 45.2%   |
| Intel + Nvidia | 290       | 21.74%  |
| 1 x AMD        | 220       | 16.49%  |
| 1 x Nvidia     | 97        | 7.27%   |
| Intel + AMD    | 59        | 4.42%   |
| AMD + Nvidia   | 33        | 2.47%   |
| 2 x AMD        | 17        | 1.27%   |
| 2 x Intel      | 7         | 0.52%   |
| Other          | 4         | 0.3%    |
| 2 x Nvidia     | 2         | 0.15%   |
| 1 x VIA        | 1         | 0.07%   |
| 1 x SiS        | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1100      | 81.24%  |
| Proprietary | 207       | 15.29%  |
| Unknown     | 47        | 3.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 847       | 61.96%  |
| 0.01-0.5   | 178       | 13.02%  |
| 1.01-2.0   | 142       | 10.39%  |
| 0.51-1.0   | 92        | 6.73%   |
| 3.01-4.0   | 62        | 4.54%   |
| 7.01-8.0   | 21        | 1.54%   |
| 5.01-6.0   | 19        | 1.39%   |
| 2.01-3.0   | 5         | 0.37%   |
| 8.01-16.0  | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 335       | 22.04%  |
| LG Display              | 217       | 14.28%  |
| Samsung Electronics     | 179       | 11.78%  |
| Chimei Innolux          | 172       | 11.32%  |
| BOE                     | 163       | 10.72%  |
| Sharp                   | 48        | 3.16%   |
| Dell                    | 44        | 2.89%   |
| Chi Mei Optoelectronics | 38        | 2.5%    |
| Apple                   | 37        | 2.43%   |
| Lenovo                  | 30        | 1.97%   |
| Philips                 | 28        | 1.84%   |
| Hewlett-Packard         | 25        | 1.64%   |
| Iiyama                  | 24        | 1.58%   |
| Goldstar                | 21        | 1.38%   |
| PANDA                   | 13        | 0.86%   |
| CSO                     | 13        | 0.86%   |
| LG Philips              | 11        | 0.72%   |
| BenQ                    | 11        | 0.72%   |
| AOC                     | 10        | 0.66%   |
| InfoVision              | 9         | 0.59%   |
| Valve                   | 7         | 0.46%   |
| Sony                    | 7         | 0.46%   |
| Unknown                 | 6         | 0.39%   |
| Acer                    | 6         | 0.39%   |
| Seiko/Epson             | 5         | 0.33%   |
| Panasonic               | 5         | 0.33%   |
| Vestel Elektronik       | 4         | 0.26%   |
| Quanta Display          | 4         | 0.26%   |
| Medion                  | 4         | 0.26%   |
| ASUSTek Computer        | 4         | 0.26%   |
| TMX                     | 3         | 0.2%    |
| HannStar                | 3         | 0.2%    |
| Eizo                    | 3         | 0.2%    |
| Arnos Instruments       | 2         | 0.13%   |
| Analogix                | 2         | 0.13%   |
| ___                     | 1         | 0.07%   |
| WST                     | 1         | 0.07%   |
| ViewSonic               | 1         | 0.07%   |
| RGB                     | 1         | 0.07%   |
| Nvidia                  | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 21        | 1.36%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch      | 18        | 1.16%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 14        | 0.91%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 10        | 0.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 10        | 0.65%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 10        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 9         | 0.58%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 9         | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 8         | 0.52%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 8         | 0.52%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 7         | 0.45%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 7         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 7         | 0.45%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 7         | 0.45%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 7         | 0.45%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch      | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch          | 6         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 6         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 6         | 0.39%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch            | 6         | 0.39%   |
| AU Optronics LCD Monitor AUO149E 1600x900 382x214mm 17.2-inch             | 6         | 0.39%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 5         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 5         | 0.32%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 5         | 0.32%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 5         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 5         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 5         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 5         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch          | 5         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 5         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch  | 5         | 0.32%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                     | 5         | 0.32%   |
| AU Optronics LCD Monitor AUOA08B 1920x1080 344x193mm 15.5-inch            | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 5         | 0.32%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 5         | 0.32%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch     | 4         | 0.26%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 4         | 0.26%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch      | 4         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 622       | 43.5%   |
| 1366x768 (WXGA)    | 265       | 18.53%  |
| 1600x900 (HD+)     | 144       | 10.07%  |
| 3840x2160 (4K)     | 73        | 5.1%    |
| 2560x1440 (QHD)    | 59        | 4.13%   |
| 1920x1200 (WUXGA)  | 46        | 3.22%   |
| 1280x800 (WXGA)    | 44        | 3.08%   |
| 1440x900 (WXGA+)   | 34        | 2.38%   |
| 2560x1600          | 24        | 1.68%   |
| 1680x1050 (WSXGA+) | 15        | 1.05%   |
| 2880x1800          | 11        | 0.77%   |
| 1280x1024 (SXGA)   | 9         | 0.63%   |
| 800x1280           | 8         | 0.56%   |
| 3440x1440          | 7         | 0.49%   |
| 1024x600           | 7         | 0.49%   |
| 3840x2400          | 6         | 0.42%   |
| 3200x1800 (QHD+)   | 6         | 0.42%   |
| Unknown            | 6         | 0.42%   |
| 2880x1620          | 5         | 0.35%   |
| 1680x945           | 5         | 0.35%   |
| 1360x768           | 5         | 0.35%   |
| 3840x1080          | 3         | 0.21%   |
| 1024x768 (XGA)     | 3         | 0.21%   |
| 2560x1080          | 2         | 0.14%   |
| 1920x1280          | 2         | 0.14%   |
| 7680x2160          | 1         | 0.07%   |
| 6320x1800          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 3600x1080          | 1         | 0.07%   |
| 3520x1080          | 1         | 0.07%   |
| 3456x2160          | 1         | 0.07%   |
| 3200x1080          | 1         | 0.07%   |
| 3072x1920          | 1         | 0.07%   |
| 2880x1920          | 1         | 0.07%   |
| 2520x1680          | 1         | 0.07%   |
| 2400x1600          | 1         | 0.07%   |
| 2304x1440          | 1         | 0.07%   |
| 2256x1504          | 1         | 0.07%   |
| 2160x1440          | 1         | 0.07%   |
| 2048x1152          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 610       | 40.24%  |
| 17      | 204       | 13.46%  |
| 13      | 165       | 10.88%  |
| 14      | 126       | 8.31%   |
| 24      | 65        | 4.29%   |
| 27      | 61        | 4.02%   |
| 16      | 37        | 2.44%   |
| 23      | 33        | 2.18%   |
| Unknown | 31        | 2.04%   |
| 12      | 30        | 1.98%   |
| 21      | 25        | 1.65%   |
| 18      | 15        | 0.99%   |
| 31      | 13        | 0.86%   |
| 11      | 13        | 0.86%   |
| 10      | 11        | 0.73%   |
| 84      | 7         | 0.46%   |
| 22      | 7         | 0.46%   |
| 7       | 7         | 0.46%   |
| 54      | 6         | 0.4%    |
| 34      | 6         | 0.4%    |
| 72      | 5         | 0.33%   |
| 25      | 5         | 0.33%   |
| 19      | 5         | 0.33%   |
| 32      | 4         | 0.26%   |
| 20      | 4         | 0.26%   |
| 65      | 3         | 0.2%    |
| 40      | 3         | 0.2%    |
| 39      | 2         | 0.13%   |
| 35      | 2         | 0.13%   |
| 29      | 2         | 0.13%   |
| 3       | 2         | 0.13%   |
| 63      | 1         | 0.07%   |
| 52      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 43      | 1         | 0.07%   |
| 42      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |
| 28      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 809       | 53.86%  |
| 351-400     | 236       | 15.71%  |
| 201-300     | 155       | 10.32%  |
| 501-600     | 148       | 9.85%   |
| 401-500     | 48        | 3.2%    |
| Unknown     | 31        | 2.06%   |
| 601-700     | 23        | 1.53%   |
| 1501-2000   | 12        | 0.8%    |
| 1001-1500   | 12        | 0.8%    |
| 701-800     | 10        | 0.67%   |
| 801-900     | 8         | 0.53%   |
| 1-100       | 8         | 0.53%   |
| 901-1000    | 2         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1082      | 81.6%   |
| 16/10   | 183       | 13.8%   |
| Unknown | 21        | 1.58%   |
| 5/4     | 9         | 0.68%   |
| 21/9    | 9         | 0.68%   |
| 3/2     | 7         | 0.53%   |
| 0.67    | 7         | 0.53%   |
| 4/3     | 4         | 0.3%    |
| 6/5     | 2         | 0.15%   |
| 32/9    | 1         | 0.08%   |
| 3.73    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 609       | 40.41%  |
| 81-90          | 201       | 13.34%  |
| 121-130        | 173       | 11.48%  |
| 201-250        | 102       | 6.77%   |
| 71-80          | 89        | 5.91%   |
| 301-350        | 61        | 4.05%   |
| 111-120        | 34        | 2.26%   |
| 131-140        | 31        | 2.06%   |
| Unknown        | 31        | 2.06%   |
| 61-70          | 30        | 1.99%   |
| 351-500        | 29        | 1.92%   |
| More than 1000 | 23        | 1.53%   |
| 251-300        | 20        | 1.33%   |
| 151-200        | 17        | 1.13%   |
| 51-60          | 13        | 0.86%   |
| 141-150        | 13        | 0.86%   |
| 41-50          | 11        | 0.73%   |
| 1-40           | 8         | 0.53%   |
| 501-1000       | 8         | 0.53%   |
| 91-100         | 4         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 610       | 41.24%  |
| 101-120       | 404       | 27.32%  |
| 51-100        | 228       | 15.42%  |
| 161-240       | 141       | 9.53%   |
| More than 240 | 47        | 3.18%   |
| Unknown       | 31        | 2.1%    |
| 1-50          | 18        | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1077      | 78.9%   |
| 2     | 217       | 15.9%   |
| 0     | 40        | 2.93%   |
| 3     | 29        | 2.12%   |
| 4     | 2         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 764       | 35.45%  |
| Realtek Semiconductor             | 680       | 31.55%  |
| Qualcomm Atheros                  | 279       | 12.95%  |
| Broadcom                          | 135       | 6.26%   |
| MediaTek                          | 45        | 2.09%   |
| Broadcom Limited                  | 33        | 1.53%   |
| Marvell Technology Group          | 24        | 1.11%   |
| Ralink                            | 21        | 0.97%   |
| TP-Link                           | 15        | 0.7%    |
| DisplayLink                       | 14        | 0.65%   |
| ASIX Electronics                  | 14        | 0.65%   |
| Nvidia                            | 13        | 0.6%    |
| Dell                              | 11        | 0.51%   |
| Ralink Technology                 | 10        | 0.46%   |
| Lenovo                            | 9         | 0.42%   |
| Hewlett-Packard                   | 8         | 0.37%   |
| Ericsson Business Mobile Networks | 8         | 0.37%   |
| Sierra Wireless                   | 6         | 0.28%   |
| Qualcomm                          | 6         | 0.28%   |
| JMicron Technology                | 6         | 0.28%   |
| D-Link System                     | 6         | 0.28%   |
| Xiaomi                            | 5         | 0.23%   |
| Samsung Electronics               | 4         | 0.19%   |
| ASUSTek Computer                  | 4         | 0.19%   |
| ADMtek                            | 3         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.09%   |
| Qualcomm Technologies             | 2         | 0.09%   |
| Motorola PCS                      | 2         | 0.09%   |
| Microsoft                         | 2         | 0.09%   |
| Huawei Technologies               | 2         | 0.09%   |
| Fibocom                           | 2         | 0.09%   |
| Edimax Technology                 | 2         | 0.09%   |
| D-Link                            | 2         | 0.09%   |
| Attansic Technology               | 2         | 0.09%   |
| Apple                             | 2         | 0.09%   |
| Z-Com                             | 1         | 0.05%   |
| VIA Technologies                  | 1         | 0.05%   |
| Shenzhen Goodix Technology        | 1         | 0.05%   |
| Seeed Technology                  | 1         | 0.05%   |
| Panasonic (Matsushita)            | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 406       | 15.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 99        | 3.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 92        | 3.49%   |
| Intel Wi-Fi 6 AX200                                                    | 81        | 3.07%   |
| Intel Wireless 7260                                                    | 53        | 2.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 51        | 1.93%   |
| Intel Wireless 8265 / 8275                                             | 50        | 1.9%    |
| Intel Wireless 8260                                                    | 42        | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 42        | 1.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 38        | 1.44%   |
| Intel Wi-Fi 6 AX201                                                    | 38        | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 37        | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 37        | 1.4%    |
| Intel Wireless 7265                                                    | 37        | 1.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 35        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 33        | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 32        | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 29        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 28        | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 28        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 25        | 0.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 25        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 23        | 0.87%   |
| Intel Ethernet Connection I218-LM                                      | 23        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 22        | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 22        | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 21        | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 20        | 0.76%   |
| Intel WiFi Link 5100                                                   | 19        | 0.72%   |
| Intel Centrino Wireless-N 2230                                         | 19        | 0.72%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 18        | 0.68%   |
| Intel Ethernet Connection I219-LM                                      | 18        | 0.68%   |
| Intel Ethernet Connection (4) I219-V                                   | 18        | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 17        | 0.64%   |
| Intel Centrino Advanced-N 6200                                         | 17        | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                          | 17        | 0.64%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 16        | 0.61%   |
| Intel Ethernet Connection I217-LM                                      | 16        | 0.61%   |
| Intel Centrino Ultimate-N 6300                                         | 16        | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                                  | 15        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 729       | 53.56%  |
| Qualcomm Atheros                      | 237       | 17.41%  |
| Realtek Semiconductor                 | 161       | 11.83%  |
| Broadcom                              | 93        | 6.83%   |
| MediaTek                              | 35        | 2.57%   |
| Broadcom Limited                      | 22        | 1.62%   |
| Ralink                                | 21        | 1.54%   |
| TP-Link                               | 10        | 0.73%   |
| Ralink Technology                     | 10        | 0.73%   |
| Sierra Wireless                       | 6         | 0.44%   |
| Qualcomm                              | 6         | 0.44%   |
| D-Link System                         | 6         | 0.44%   |
| Dell                                  | 5         | 0.37%   |
| ASUSTek Computer                      | 4         | 0.29%   |
| Qualcomm Technologies                 | 2         | 0.15%   |
| Microsoft                             | 2         | 0.15%   |
| Hewlett-Packard                       | 2         | 0.15%   |
| Fibocom                               | 2         | 0.15%   |
| Edimax Technology                     | 2         | 0.15%   |
| D-Link                                | 2         | 0.15%   |
| Z-Com                                 | 1         | 0.07%   |
| Panasonic (Matsushita)                | 1         | 0.07%   |
| Belkin Components                     | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 81        | 5.92%   |
| Intel Wireless 7260                                            | 53        | 3.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 51        | 3.73%   |
| Intel Wireless 8265 / 8275                                     | 50        | 3.65%   |
| Intel Wireless 8260                                            | 42        | 3.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 38        | 2.78%   |
| Intel Wi-Fi 6 AX201                                            | 38        | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 37        | 2.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 37        | 2.7%    |
| Intel Wireless 7265                                            | 37        | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 35        | 2.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 33        | 2.41%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 32        | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 29        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 28        | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 28        | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 1.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 25        | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 23        | 1.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 22        | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 21        | 1.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 1.46%   |
| Intel WiFi Link 5100                                           | 19        | 1.39%   |
| Intel Centrino Wireless-N 2230                                 | 19        | 1.39%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 18        | 1.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 1.24%   |
| Intel Centrino Advanced-N 6200                                 | 17        | 1.24%   |
| Broadcom BCM43142 802.11b/g/n                                  | 17        | 1.24%   |
| Intel Centrino Ultimate-N 6300                                 | 16        | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 14        | 1.02%   |
| Intel Wireless 3165                                            | 14        | 1.02%   |
| Intel Centrino Advanced-N 6235                                 | 14        | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13        | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 13        | 0.95%   |
| Intel Wireless 3160                                            | 13        | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 13        | 0.95%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 11        | 0.8%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 11        | 0.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 10        | 0.73%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 10        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 619       | 50.7%   |
| Intel                            | 317       | 25.96%  |
| Qualcomm Atheros                 | 91        | 7.45%   |
| Broadcom                         | 57        | 4.67%   |
| Marvell Technology Group         | 24        | 1.97%   |
| DisplayLink                      | 14        | 1.15%   |
| ASIX Electronics                 | 14        | 1.15%   |
| Nvidia                           | 13        | 1.06%   |
| Broadcom Limited                 | 11        | 0.9%    |
| MediaTek                         | 10        | 0.82%   |
| Lenovo                           | 9         | 0.74%   |
| JMicron Technology               | 6         | 0.49%   |
| Hewlett-Packard                  | 6         | 0.49%   |
| Xiaomi                           | 5         | 0.41%   |
| TP-Link                          | 4         | 0.33%   |
| Samsung Electronics              | 4         | 0.33%   |
| ADMtek                           | 3         | 0.25%   |
| Silicon Integrated Systems [SiS] | 2         | 0.16%   |
| Motorola PCS                     | 2         | 0.16%   |
| Attansic Technology              | 2         | 0.16%   |
| Apple                            | 2         | 0.16%   |
| VIA Technologies                 | 1         | 0.08%   |
| OPPO Electronics                 | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| Huawei Technologies              | 1         | 0.08%   |
| Google                           | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 406       | 32.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 99        | 7.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 92        | 7.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 42        | 3.39%   |
| Intel Ethernet Connection I218-LM                                      | 23        | 1.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 22        | 1.77%   |
| Intel Ethernet Connection I219-LM                                      | 18        | 1.45%   |
| Intel Ethernet Connection (4) I219-V                                   | 18        | 1.45%   |
| Intel Ethernet Connection I217-LM                                      | 16        | 1.29%   |
| Intel Ethernet Connection (4) I219-LM                                  | 15        | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                      | 14        | 1.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 14        | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                                  | 14        | 1.13%   |
| Intel 82577LM Gigabit Network Connection                               | 14        | 1.13%   |
| Intel Ethernet Connection (6) I219-V                                   | 13        | 1.05%   |
| Intel 82567LM Gigabit Network Connection                               | 13        | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                          | 13        | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 10        | 0.81%   |
| Intel 82566MM Gigabit Network Connection                               | 10        | 0.81%   |
| Intel Ethernet Connection (6) I219-LM                                  | 9         | 0.73%   |
| Intel 82579V Gigabit Network Connection                                | 9         | 0.73%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 9         | 0.73%   |
| Intel Ethernet Connection I219-V                                       | 8         | 0.65%   |
| Intel Ethernet Connection I217-V                                       | 8         | 0.65%   |
| Intel Ethernet Connection (10) I219-LM                                 | 8         | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 8         | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 7         | 0.56%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 0.56%   |
| Intel Ethernet Connection (16) I219-LM                                 | 7         | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 7         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 6         | 0.48%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6         | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 6         | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 6         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.48%   |
| Intel Ethernet Connection (13) I219-LM                                 | 6         | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 0.48%   |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1301      | 52.48%  |
| Ethernet | 1151      | 46.43%  |
| Modem    | 23        | 0.93%   |
| Unknown  | 4         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1030      | 71.33%  |
| Ethernet | 414       | 28.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1022      | 76.78%  |
| 1     | 278       | 20.89%  |
| 3     | 16        | 1.2%    |
| 0     | 14        | 1.05%   |
| 4     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 891       | 64.8%   |
| Yes  | 484       | 35.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 539       | 51.38%  |
| Realtek Semiconductor           | 98        | 9.34%   |
| Qualcomm Atheros Communications | 68        | 6.48%   |
| IMC Networks                    | 57        | 5.43%   |
| Broadcom                        | 55        | 5.24%   |
| Foxconn / Hon Hai               | 53        | 5.05%   |
| Dell                            | 34        | 3.24%   |
| Lite-On Technology              | 30        | 2.86%   |
| Apple                           | 30        | 2.86%   |
| Hewlett-Packard                 | 25        | 2.38%   |
| Toshiba                         | 16        | 1.53%   |
| Ralink                          | 8         | 0.76%   |
| Cambridge Silicon Radio         | 8         | 0.76%   |
| ASUSTek Computer                | 7         | 0.67%   |
| Alps Electric                   | 5         | 0.48%   |
| MediaTek                        | 4         | 0.38%   |
| Foxconn International           | 4         | 0.38%   |
| Ralink Technology               | 3         | 0.29%   |
| USI                             | 2         | 0.19%   |
| Realtek                         | 1         | 0.1%    |
| Micro Star International        | 1         | 0.1%    |
| Belkin Components               | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 203       | 19.33%  |
| Intel AX201 Bluetooth                               | 98        | 9.33%   |
| Intel AX200 Bluetooth                               | 79        | 7.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 63        | 6%      |
| Realtek Bluetooth Radio                             | 51        | 4.86%   |
| Intel AX211 Bluetooth                               | 35        | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 29        | 2.76%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 28        | 2.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 20        | 1.9%    |
| IMC Networks Bluetooth Radio                        | 20        | 1.9%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 19        | 1.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 1.62%   |
| Foxconn / Hon Hai Bluetooth Device                  | 17        | 1.62%   |
| Apple Bluetooth Host Controller                     | 17        | 1.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 1.43%   |
| IMC Networks Wireless_Device                        | 14        | 1.33%   |
| IMC Networks Bluetooth Device                       | 14        | 1.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 13        | 1.24%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 13        | 1.24%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 1.14%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 1.05%   |
| Dell DW375 Bluetooth Module                         | 11        | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.95%   |
| Broadcom HP Portable SoftSailing                    | 10        | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.95%   |
| Apple Bluetooth USB Host Controller                 | 10        | 0.95%   |
| Intel AX210 Bluetooth                               | 9         | 0.86%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.86%   |
| Toshiba Bluetooth Device                            | 8         | 0.76%   |
| Ralink RT3290 Bluetooth                             | 8         | 0.76%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 8         | 0.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.67%   |
| Realtek RTL8821A Bluetooth                          | 6         | 0.57%   |
| Broadcom HP Portable Bumble Bee                     | 6         | 0.57%   |
| Realtek 802.11ac WLAN Adapter                       | 5         | 0.48%   |
| Lite-On Bluetooth Device                            | 5         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.48%   |
| Dell Wireless 370 Bluetooth Mini-card               | 5         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1075      | 62.94%  |
| AMD                                  | 278       | 16.28%  |
| Nvidia                               | 238       | 13.93%  |
| Realtek Semiconductor                | 14        | 0.82%   |
| GN Netcom                            | 13        | 0.76%   |
| Hewlett-Packard                      | 12        | 0.7%    |
| C-Media Electronics                  | 12        | 0.7%    |
| Plantronics                          | 7         | 0.41%   |
| Logitech                             | 7         | 0.41%   |
| Lenovo                               | 4         | 0.23%   |
| Corsair                              | 4         | 0.23%   |
| Kingston Technology                  | 3         | 0.18%   |
| Apple                                | 3         | 0.18%   |
| Texas Instruments                    | 2         | 0.12%   |
| SteelSeries ApS                      | 2         | 0.12%   |
| Sony                                 | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.12%   |
| Samson Technologies                  | 2         | 0.12%   |
| Roland                               | 2         | 0.12%   |
| Razer USA                            | 2         | 0.12%   |
| Generalplus Technology               | 2         | 0.12%   |
| Dell                                 | 2         | 0.12%   |
| VIA Technologies                     | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| Sennheiser electronic                | 1         | 0.06%   |
| Sennheiser Communications            | 1         | 0.06%   |
| RODE Microphones                     | 1         | 0.06%   |
| QinHeng Electronics                  | 1         | 0.06%   |
| Pioneer DJ                           | 1         | 0.06%   |
| Pioneer                              | 1         | 0.06%   |
| OPPO Electronics                     | 1         | 0.06%   |
| M-Audio                              | 1         | 0.06%   |
| JMTek                                | 1         | 0.06%   |
| Guillemot                            | 1         | 0.06%   |
| Focusrite-Novation                   | 1         | 0.06%   |
| FIFINE Microphones                   | 1         | 0.06%   |
| DSEA A/S                             | 1         | 0.06%   |
| Bose                                 | 1         | 0.06%   |
| Audio-Technica                       | 1         | 0.06%   |
| ASUSTek Computer                     | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 149       | 7.28%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 145       | 7.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 125       | 6.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 81        | 3.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 81        | 3.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 63        | 3.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 59        | 2.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 53        | 2.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 52        | 2.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 51        | 2.49%   |
| Intel 8 Series HD Audio Controller                                         | 51        | 2.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 50        | 2.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 48        | 2.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 46        | 2.25%   |
| Intel Broadwell-U Audio Controller                                         | 46        | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 43        | 2.1%    |
| AMD FCH Azalia Controller                                                  | 38        | 1.86%   |
| Intel Comet Lake PCH cAVS                                                  | 37        | 1.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 33        | 1.61%   |
| Intel CM238 HD Audio Controller                                            | 31        | 1.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 31        | 1.51%   |
| AMD Kabini HDMI/DP Audio                                                   | 31        | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 28        | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 1.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 26        | 1.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 25        | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24        | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                              | 23        | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 17        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 16        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                         | 16        | 0.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 15        | 0.73%   |
| Realtek Semiconductor USB Audio                                            | 14        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 14        | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 14        | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 14        | 0.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 14        | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 13        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 274       | 32.05%  |
| SK hynix            | 206       | 24.09%  |
| Micron Technology   | 105       | 12.28%  |
| Kingston            | 81        | 9.47%   |
| Unknown             | 42        | 4.91%   |
| Crucial             | 36        | 4.21%   |
| Elpida              | 26        | 3.04%   |
| Ramaxel Technology  | 20        | 2.34%   |
| Nanya Technology    | 14        | 1.64%   |
| Corsair             | 13        | 1.52%   |
| A-DATA Technology   | 12        | 1.4%    |
| Unknown (ABCD)      | 6         | 0.7%    |
| Unknown             | 5         | 0.58%   |
| G.Skill             | 3         | 0.35%   |
| Timetec             | 2         | 0.23%   |
| GOODRAM             | 2         | 0.23%   |
| Unknown (09D5)      | 1         | 0.12%   |
| Unifosa             | 1         | 0.12%   |
| TRS STAR            | 1         | 0.12%   |
| Transcend           | 1         | 0.12%   |
| Team                | 1         | 0.12%   |
| Patriot             | 1         | 0.12%   |
| A-DA                | 1         | 0.12%   |
| A Force             | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 12        | 1.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 1.2%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 1.09%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 10        | 1.09%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 9         | 0.98%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 9         | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 9         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 9         | 0.98%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 9         | 0.98%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 9         | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 8         | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 8         | 0.87%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 8         | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 8         | 0.87%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s               | 8         | 0.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 0.76%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 7         | 0.76%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 7         | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s    | 6         | 0.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 6         | 0.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.65%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 6         | 0.65%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 5         | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 5         | 0.55%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 5         | 0.55%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 5         | 0.55%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 5         | 0.55%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 5         | 0.55%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 5         | 0.55%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 0.55%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 0.55%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 0.55%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s              | 5         | 0.55%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                          | 5         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 5         | 0.55%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 5         | 0.55%   |
| Unknown                                                             | 5         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 4         | 0.44%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 4         | 0.44%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 4         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 357       | 47.66%  |
| DDR3    | 256       | 34.18%  |
| DDR2    | 31        | 4.14%   |
| LPDDR3  | 25        | 3.34%   |
| DDR5    | 25        | 3.34%   |
| LPDDR4  | 22        | 2.94%   |
| SDRAM   | 16        | 2.14%   |
| LPDDR5  | 13        | 1.74%   |
| Unknown | 4         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 679       | 90.41%  |
| Row Of Chips | 60        | 7.99%   |
| Chip         | 7         | 0.93%   |
| DIMM         | 3         | 0.4%    |
| Unknown      | 2         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 319       | 39.05%  |
| 4096  | 216       | 26.44%  |
| 16384 | 158       | 19.34%  |
| 2048  | 83        | 10.16%  |
| 32768 | 26        | 3.18%   |
| 1024  | 12        | 1.47%   |
| 8     | 2         | 0.24%   |
| 6144  | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 175       | 21.77%  |
| 3200    | 170       | 21.14%  |
| 2667    | 144       | 17.91%  |
| 2400    | 57        | 7.09%   |
| 2133    | 46        | 5.72%   |
| 1334    | 41        | 5.1%    |
| 1333    | 27        | 3.36%   |
| Unknown | 18        | 2.24%   |
| 667     | 16        | 1.99%   |
| 4800    | 15        | 1.87%   |
| 5600    | 12        | 1.49%   |
| 1067    | 11        | 1.37%   |
| 2048    | 10        | 1.24%   |
| 4267    | 9         | 1.12%   |
| 6400    | 8         | 1%      |
| 3266    | 8         | 1%      |
| 800     | 8         | 1%      |
| 975     | 6         | 0.75%   |
| 1867    | 5         | 0.62%   |
| 4199    | 4         | 0.5%    |
| 8400    | 3         | 0.37%   |
| 4266    | 3         | 0.37%   |
| 7500    | 2         | 0.25%   |
| 7467    | 2         | 0.25%   |
| 5500    | 1         | 0.12%   |
| 3000    | 1         | 0.12%   |
| 1066    | 1         | 0.12%   |
| 533     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 41.67%  |
| Samsung Electronics | 2         | 16.67%  |
| Canon               | 2         | 16.67%  |
| Brother Industries  | 2         | 16.67%  |
| Prolific Technology | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-472x Series       | 1         | 8.33%   |
| Samsung ML-1660 Series        | 1         | 8.33%   |
| Prolific PL2305 Parallel Port | 1         | 8.33%   |
| HP LaserJet CM1415fnw         | 1         | 8.33%   |
| HP LaserJet 1020              | 1         | 8.33%   |
| HP Deskjet F4500 series       | 1         | 8.33%   |
| HP DeskJet 4100 series        | 1         | 8.33%   |
| HP DeskJet 3700 series        | 1         | 8.33%   |
| Canon TS6300 series           | 1         | 8.33%   |
| Canon TS5100 series           | 1         | 8.33%   |
| Brother HL-L2350DW series     | 1         | 8.33%   |
| Brother DCP-L2530DW series    | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 3         | 42.86%  |
| Canon           | 3         | 42.86%  |
| Hewlett-Packard | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo]      | 2         | 28.57%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 14.29%  |
| HP scanjet 8270                                  | 1         | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20               | 1         | 14.29%  |
| Canon CanoScan 8800F                             | 1         | 14.29%  |
| Canon CanoScan 3200F                             | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 292       | 24.81%  |
| Microdia                               | 124       | 10.54%  |
| Realtek Semiconductor                  | 106       | 9.01%   |
| IMC Networks                           | 85        | 7.22%   |
| Bison Electronics                      | 78        | 6.63%   |
| Sunplus Innovation Technology          | 59        | 5.01%   |
| Quanta                                 | 54        | 4.59%   |
| Suyin                                  | 46        | 3.91%   |
| Lite-On Technology                     | 46        | 3.91%   |
| Cheng Uei Precision Industry (Foxlink) | 46        | 3.91%   |
| Syntek                                 | 34        | 2.89%   |
| Luxvisions Innotech Limited            | 30        | 2.55%   |
| Apple                                  | 23        | 1.95%   |
| Acer                                   | 22        | 1.87%   |
| Ricoh                                  | 18        | 1.53%   |
| Logitech                               | 15        | 1.27%   |
| Alcor Micro                            | 14        | 1.19%   |
| Sonix Technology                       | 9         | 0.76%   |
| Shinetech                              | 8         | 0.68%   |
| Samsung Electronics                    | 8         | 0.68%   |
| Silicon Motion                         | 6         | 0.51%   |
| Primax Electronics                     | 5         | 0.42%   |
| Lenovo                                 | 5         | 0.42%   |
| ALi                                    | 5         | 0.42%   |
| Z-Star Microelectronics                | 4         | 0.34%   |
| Importek                               | 4         | 0.34%   |
| Pixart Imaging                         | 3         | 0.25%   |
| icSpring                               | 3         | 0.25%   |
| OPPO Electronics                       | 2         | 0.17%   |
| Foxconn / Hon Hai                      | 2         | 0.17%   |
| DigiTech                               | 2         | 0.17%   |
| WaveRider Communications               | 1         | 0.08%   |
| Trust                                  | 1         | 0.08%   |
| SunplusIT                              | 1         | 0.08%   |
| STEREOLABS                             | 1         | 0.08%   |
| Shine-optics                           | 1         | 0.08%   |
| Panasonic (Matsushita)                 | 1         | 0.08%   |
| Novatek Microelectronics               | 1         | 0.08%   |
| Mustek Systems                         | 1         | 0.08%   |
| Microsoft                              | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 46        | 3.89%   |
| Realtek Integrated_Webcam_HD                                               | 43        | 3.64%   |
| Microdia Integrated_Webcam_HD                                              | 43        | 3.64%   |
| IMC Networks Integrated Camera                                             | 31        | 2.62%   |
| Microdia Integrated Webcam                                                 | 23        | 1.95%   |
| Syntek Integrated Camera                                                   | 22        | 1.86%   |
| Bison Integrated Camera                                                    | 22        | 1.86%   |
| Chicony HP HD Camera                                                       | 21        | 1.78%   |
| Chicony HD WebCam                                                          | 21        | 1.78%   |
| Quanta HP HD Camera                                                        | 20        | 1.69%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 20        | 1.69%   |
| Sunplus HD WebCam                                                          | 15        | 1.27%   |
| Chicony HP HD Webcam                                                       | 14        | 1.18%   |
| Lite-On Integrated Camera                                                  | 13        | 1.1%    |
| Chicony USB2.0 Camera                                                      | 13        | 1.1%    |
| Bison HD Webcam                                                            | 12        | 1.02%   |
| Lite-On HP HD Camera                                                       | 11        | 0.93%   |
| Chicony Integrated Camera (1280x720@30)                                    | 11        | 0.93%   |
| Acer BisonCam,NB Pro                                                       | 11        | 0.93%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 10        | 0.85%   |
| Lite-On HP HD Webcam                                                       | 10        | 0.85%   |
| Chicony USB2.0 HD UVC WebCam                                               | 10        | 0.85%   |
| Chicony TOSHIBA Web Camera - HD                                            | 10        | 0.85%   |
| Chicony EasyCamera                                                         | 10        | 0.85%   |
| Bison BisonCam, NB Pro                                                     | 10        | 0.85%   |
| Chicony USB 2.0 Camera                                                     | 9         | 0.76%   |
| Sunplus Integrated_Webcam_HD                                               | 8         | 0.68%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 8         | 0.68%   |
| Microdia Integrated_Webcam_FHD                                             | 8         | 0.68%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 8         | 0.68%   |
| Lite-On HP Wide Vision HD Camera                                           | 8         | 0.68%   |
| Chicony HP Wide Vision HD Camera                                           | 8         | 0.68%   |
| Chicony HP Truevision HD camera                                            | 8         | 0.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 7         | 0.59%   |
| Realtek USB2.0 HD UVC WebCam                                               | 7         | 0.59%   |
| Realtek USB Camera                                                         | 7         | 0.59%   |
| Luxvisions Innotech Limited Integrated Camera                              | 7         | 0.59%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 7         | 0.59%   |
| Chicony Integrated HP HD Webcam                                            | 7         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 7         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 105       | 39.03%  |
| Synaptics                          | 88        | 32.71%  |
| Shenzhen Goodix Technology         | 24        | 8.92%   |
| AuthenTec                          | 16        | 5.95%   |
| LighTuning Technology              | 12        | 4.46%   |
| Upek                               | 8         | 2.97%   |
| STMicroelectronics                 | 7         | 2.6%    |
| Elan Microelectronics              | 5         | 1.86%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 1.49%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 38        | 14.13%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 22        | 8.18%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 16        | 5.95%   |
| Shenzhen Goodix  Fingerprint Device                                        | 13        | 4.83%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 4.46%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 3.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 3.35%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 2.97%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 2.97%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 2.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 2.6%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.6%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 2.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.23%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 2.23%   |
| AuthenTec AES2810                                                          | 6         | 2.23%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 2.23%   |
| Validity Sensors VFS491                                                    | 5         | 1.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.86%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.86%   |
| Synaptics Prometheus Fingerprint Reader                                    | 5         | 1.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 1.86%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 1.49%   |
| Synaptics WBDI Device                                                      | 4         | 1.49%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1.49%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 1.49%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.49%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 1.12%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.12%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.12%   |
| Synaptics TouchPad                                                         | 3         | 1.12%   |
| LighTuning Fingerprint Reader                                              | 3         | 1.12%   |
| AuthenTec AES1600                                                          | 3         | 1.12%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.74%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.74%   |
| Synaptics WBDI                                                             | 2         | 0.74%   |
| Synaptics UWP WBDI                                                         | 2         | 0.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.74%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 90        | 44.78%  |
| Alcor Micro                       | 62        | 30.85%  |
| O2 Micro                          | 17        | 8.46%   |
| Lenovo                            | 10        | 4.98%   |
| VASCO Data Security International | 5         | 2.49%   |
| Realtek Semiconductor             | 5         | 2.49%   |
| OmniKey                           | 3         | 1.49%   |
| Upek                              | 2         | 1%      |
| Advanced Card Systems             | 2         | 1%      |
| SCM Microsystems                  | 1         | 0.5%    |
| Integrated Technology Express     | 1         | 0.5%    |
| Gemalto (was Gemplus)             | 1         | 0.5%    |
| Clay Logic                        | 1         | 0.5%    |
| Chicony Electronics               | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 60        | 29.85%  |
| Broadcom 58200                                                               | 32        | 15.92%  |
| Broadcom BCM5880 Secure Applications Processor                               | 28        | 13.93%  |
| Broadcom 5880                                                                | 19        | 9.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 14        | 6.97%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 5.47%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 4.98%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 2.49%   |
| VASCO Data Security International DIGIPASS 870                               | 4         | 1.99%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.49%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1%      |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1%      |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1%      |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.5%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.5%    |
| OmniKey CardMan 4321                                                         | 1         | 0.5%    |
| Integrated Technology Express SmartCard Reader                               | 1         | 0.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.5%    |
| Clay Logic Nitrokey Start                                                    | 1         | 0.5%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.5%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.5%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 771       | 55.83%  |
| 1     | 472       | 34.18%  |
| 2     | 112       | 8.11%   |
| 3     | 20        | 1.45%   |
| 4     | 3         | 0.22%   |
| 8     | 1         | 0.07%   |
| 6     | 1         | 0.07%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 264       | 35.82%  |
| Graphics card            | 145       | 19.67%  |
| Chipcard                 | 141       | 19.13%  |
| Net/wireless             | 56        | 7.6%    |
| Multimedia controller    | 35        | 4.75%   |
| Camera                   | 17        | 2.31%   |
| Storage                  | 15        | 2.04%   |
| Card reader              | 14        | 1.9%    |
| Bluetooth                | 14        | 1.9%    |
| Communication controller | 11        | 1.49%   |
| Net/ethernet             | 8         | 1.09%   |
| Sound                    | 4         | 0.54%   |
| Network                  | 4         | 0.54%   |
| Flash memory             | 4         | 0.54%   |
| Modem                    | 3         | 0.41%   |
| Unassigned class         | 1         | 0.14%   |
| Storage/ide              | 1         | 0.14%   |

