Debian - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 8766

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite C55-C             | [256b476a15](https://linux-hardware.org/?probe=256b476a15) | Dec 24, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [9eff3f535e](https://linux-hardware.org/?probe=9eff3f535e) | Dec 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ee7b7ce7cc](https://linux-hardware.org/?probe=ee7b7ce7cc) | Dec 24, 2023 |
| Toshiba       | Satellite A205              | [c3680bfd29](https://linux-hardware.org/?probe=c3680bfd29) | Dec 24, 2023 |
| HP            | Pavilion g7                 | [bbe3fb1914](https://linux-hardware.org/?probe=bbe3fb1914) | Dec 24, 2023 |
| IBM           | ThinkPad R50e 1842QDU       | [32a349ab97](https://linux-hardware.org/?probe=32a349ab97) | Dec 23, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | [c2681f33cc](https://linux-hardware.org/?probe=c2681f33cc) | Dec 23, 2023 |
| HP            | ProBook 655 G2              | [033325e722](https://linux-hardware.org/?probe=033325e722) | Dec 23, 2023 |
| AVITA         | NS14A6                      | [adf732b1b6](https://linux-hardware.org/?probe=adf732b1b6) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [8753b04999](https://linux-hardware.org/?probe=8753b04999) | Dec 23, 2023 |
| Google        | Reks                        | [52375a57c5](https://linux-hardware.org/?probe=52375a57c5) | Dec 22, 2023 |
| HP            | EliteBook 850 G3            | [5e8dc79e2c](https://linux-hardware.org/?probe=5e8dc79e2c) | Dec 22, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [a11f0a948c](https://linux-hardware.org/?probe=a11f0a948c) | Dec 22, 2023 |
| Irbis         | NB264                       | [8821679765](https://linux-hardware.org/?probe=8821679765) | Dec 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [5d41a0e0d5](https://linux-hardware.org/?probe=5d41a0e0d5) | Dec 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [ad67aeb103](https://linux-hardware.org/?probe=ad67aeb103) | Dec 22, 2023 |
| HP            | ENVY 15                     | [2997ffe5cf](https://linux-hardware.org/?probe=2997ffe5cf) | Dec 22, 2023 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [c6cefd749d](https://linux-hardware.org/?probe=c6cefd749d) | Dec 22, 2023 |
| Dell          | Inspiron 15 3515            | [cdff1cf322](https://linux-hardware.org/?probe=cdff1cf322) | Dec 22, 2023 |
| HP            | ENVY Notebook               | [ca2e6f9061](https://linux-hardware.org/?probe=ca2e6f9061) | Dec 22, 2023 |
| HP            | EliteBook 830 G5            | [aa3d919a29](https://linux-hardware.org/?probe=aa3d919a29) | Dec 22, 2023 |
| HONOR         | HYM-WXX                     | [1c225a853e](https://linux-hardware.org/?probe=1c225a853e) | Dec 21, 2023 |
| Lenovo        | ThinkPad T490 20N3S5GP12    | [093906d110](https://linux-hardware.org/?probe=093906d110) | Dec 21, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [2e9f8a97e5](https://linux-hardware.org/?probe=2e9f8a97e5) | Dec 21, 2023 |
| Google        | Reks                        | [9a6f15c5d9](https://linux-hardware.org/?probe=9a6f15c5d9) | Dec 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a102e5839d](https://linux-hardware.org/?probe=a102e5839d) | Dec 21, 2023 |
| Acer          | Swift SF314-54              | [edc5223b9b](https://linux-hardware.org/?probe=edc5223b9b) | Dec 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [1c3113c9b9](https://linux-hardware.org/?probe=1c3113c9b9) | Dec 20, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [2785a8b9c6](https://linux-hardware.org/?probe=2785a8b9c6) | Dec 20, 2023 |
| Dell          | XPS 15 7590                 | [74136911a0](https://linux-hardware.org/?probe=74136911a0) | Dec 20, 2023 |
| Apple         | MacBookAir6,2               | [ef17f12758](https://linux-hardware.org/?probe=ef17f12758) | Dec 20, 2023 |
| HP            | ENVY m6                     | [237331a1ba](https://linux-hardware.org/?probe=237331a1ba) | Dec 20, 2023 |
| Dynabook      | CS40L-HB                    | [da68e155cd](https://linux-hardware.org/?probe=da68e155cd) | Dec 20, 2023 |
| Clevo         | W240BU                      | [a0d883bb3d](https://linux-hardware.org/?probe=a0d883bb3d) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [54ed87ec87](https://linux-hardware.org/?probe=54ed87ec87) | Dec 20, 2023 |
| Dell          | G7 7790                     | [bcc6b4046b](https://linux-hardware.org/?probe=bcc6b4046b) | Dec 19, 2023 |
| DellInc.      | Venue 8 Pro 5830            | [d6408a26a1](https://linux-hardware.org/?probe=d6408a26a1) | Dec 19, 2023 |
| Acer          | Aspire AV15-52              | [daf4aa326d](https://linux-hardware.org/?probe=daf4aa326d) | Dec 19, 2023 |
| MSI           | Pulse 17 B13VGK             | [71d0660568](https://linux-hardware.org/?probe=71d0660568) | Dec 18, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [e94e9e0fd9](https://linux-hardware.org/?probe=e94e9e0fd9) | Dec 18, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | [020e3af833](https://linux-hardware.org/?probe=020e3af833) | Dec 18, 2023 |
| Gigabyte      | AORUS 17H BXF               | [ad8b646e5c](https://linux-hardware.org/?probe=ad8b646e5c) | Dec 18, 2023 |
| Dell          | Vostro 15 3515              | [baf5b47a47](https://linux-hardware.org/?probe=baf5b47a47) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [f47c731a09](https://linux-hardware.org/?probe=f47c731a09) | Dec 18, 2023 |
| Dell          | XPS 15 7590                 | [229df442f5](https://linux-hardware.org/?probe=229df442f5) | Dec 18, 2023 |
| Acer          | Swift SF314-71              | [5a5f20e49a](https://linux-hardware.org/?probe=5a5f20e49a) | Dec 18, 2023 |
| Apple         | MacBookPro13,2              | [dd9d263269](https://linux-hardware.org/?probe=dd9d263269) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5fae29f23f](https://linux-hardware.org/?probe=5fae29f23f) | Dec 18, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [f46bf3981f](https://linux-hardware.org/?probe=f46bf3981f) | Dec 18, 2023 |
| HP            | 15 Notebook PC              | [1293ea8b65](https://linux-hardware.org/?probe=1293ea8b65) | Dec 18, 2023 |
| Unknown       | Unknown                     | [81187bebc0](https://linux-hardware.org/?probe=81187bebc0) | Dec 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [709891824c](https://linux-hardware.org/?probe=709891824c) | Dec 18, 2023 |
| MSI           | Vector GP77 13VG            | [7b6b5a14f8](https://linux-hardware.org/?probe=7b6b5a14f8) | Dec 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | [94757e986e](https://linux-hardware.org/?probe=94757e986e) | Dec 18, 2023 |
| Panasonic     | FZ-M1CCA17E3                | [87024c17b5](https://linux-hardware.org/?probe=87024c17b5) | Dec 17, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [fd17674af7](https://linux-hardware.org/?probe=fd17674af7) | Dec 17, 2023 |
| MSI           | Cyborg 15 A12VF             | [af666cc67d](https://linux-hardware.org/?probe=af666cc67d) | Dec 17, 2023 |
| Panasonic     | FZ-M1CCA17E3                | [8f2a76eb09](https://linux-hardware.org/?probe=8f2a76eb09) | Dec 17, 2023 |
| Medion        | BEAST X30                   | [cec06735ba](https://linux-hardware.org/?probe=cec06735ba) | Dec 17, 2023 |
| ASUSTek       | 1215N                       | [9d204d6a41](https://linux-hardware.org/?probe=9d204d6a41) | Dec 17, 2023 |
| MSI           | Vector GP77 13VG            | [267679e074](https://linux-hardware.org/?probe=267679e074) | Dec 17, 2023 |
| Acer          | Swift SF314-43              | [7ff498fc83](https://linux-hardware.org/?probe=7ff498fc83) | Dec 17, 2023 |
| HP            | Compaq 6730s                | [628e8cf362](https://linux-hardware.org/?probe=628e8cf362) | Dec 17, 2023 |
| HP            | Compaq 6730s                | [774f3d4feb](https://linux-hardware.org/?probe=774f3d4feb) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b212e62ef7](https://linux-hardware.org/?probe=b212e62ef7) | Dec 17, 2023 |
| Samsung       | 760XDA                      | [53ab21d486](https://linux-hardware.org/?probe=53ab21d486) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [e0fa989ed0](https://linux-hardware.org/?probe=e0fa989ed0) | Dec 17, 2023 |
| Packard Be... | EasyNote TE11HC             | [a155267edc](https://linux-hardware.org/?probe=a155267edc) | Dec 17, 2023 |
| Alienware     | m18 R1                      | [a136406723](https://linux-hardware.org/?probe=a136406723) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [7162b25b98](https://linux-hardware.org/?probe=7162b25b98) | Dec 16, 2023 |
| PC Special... | N150CU                      | [92a4f7a5a4](https://linux-hardware.org/?probe=92a4f7a5a4) | Dec 16, 2023 |
| Dell          | XPS 13 9360                 | [0aa5382212](https://linux-hardware.org/?probe=0aa5382212) | Dec 16, 2023 |
| PC Special... | N150CU                      | [07686d110e](https://linux-hardware.org/?probe=07686d110e) | Dec 16, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [5f19b6ce4f](https://linux-hardware.org/?probe=5f19b6ce4f) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [314b3b98d7](https://linux-hardware.org/?probe=314b3b98d7) | Dec 16, 2023 |
| Dell          | Vostro 5490                 | [ca117be9d4](https://linux-hardware.org/?probe=ca117be9d4) | Dec 16, 2023 |
| Lenovo        | ThinkPad P1 20MDS02BGE      | [65eb962233](https://linux-hardware.org/?probe=65eb962233) | Dec 15, 2023 |
| HP            | EliteBook 745 G3            | [ec4a48125c](https://linux-hardware.org/?probe=ec4a48125c) | Dec 15, 2023 |
| HP            | EliteBook 745 G3            | [d43271b873](https://linux-hardware.org/?probe=d43271b873) | Dec 15, 2023 |
| Medion        | Akoya E7226                 | [a8677e8420](https://linux-hardware.org/?probe=a8677e8420) | Dec 15, 2023 |
| Medion        | Akoya E7226                 | [059918d809](https://linux-hardware.org/?probe=059918d809) | Dec 15, 2023 |
| Gigabyte      | AERO 15 KD                  | [ef9cf1d767](https://linux-hardware.org/?probe=ef9cf1d767) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [b4bcda5523](https://linux-hardware.org/?probe=b4bcda5523) | Dec 15, 2023 |
| Dell          | XPS 15 7590                 | [69e37f3d93](https://linux-hardware.org/?probe=69e37f3d93) | Dec 14, 2023 |
| ASUSTek       | K52Jc                       | [dfa5dc9cd9](https://linux-hardware.org/?probe=dfa5dc9cd9) | Dec 14, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [de24d459c5](https://linux-hardware.org/?probe=de24d459c5) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | [09a184f2e4](https://linux-hardware.org/?probe=09a184f2e4) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7232... | [d9de3edb6b](https://linux-hardware.org/?probe=d9de3edb6b) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7232... | [84f162f88f](https://linux-hardware.org/?probe=84f162f88f) | Dec 14, 2023 |
| Dell          | XPS 15 9570                 | [67a32f0dd0](https://linux-hardware.org/?probe=67a32f0dd0) | Dec 14, 2023 |
| Dell          | XPS 15 9570                 | [283dc2dab5](https://linux-hardware.org/?probe=283dc2dab5) | Dec 14, 2023 |
| Sony          | VPCEG18FG                   | [3cf20aa9ea](https://linux-hardware.org/?probe=3cf20aa9ea) | Dec 14, 2023 |
| HP            | ProBook 4540s               | [24875256cd](https://linux-hardware.org/?probe=24875256cd) | Dec 14, 2023 |
| Dell          | Inspiron 7560               | [83034fb404](https://linux-hardware.org/?probe=83034fb404) | Dec 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d2b1e67451](https://linux-hardware.org/?probe=d2b1e67451) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | [05c8fb1ded](https://linux-hardware.org/?probe=05c8fb1ded) | Dec 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [c4e3486e91](https://linux-hardware.org/?probe=c4e3486e91) | Dec 13, 2023 |
| Lenovo        | Flex 2 Pro-15               | [da278da4b6](https://linux-hardware.org/?probe=da278da4b6) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [68e68f1683](https://linux-hardware.org/?probe=68e68f1683) | Dec 13, 2023 |
| Acer          | Aspire R3-131T              | [5fc8de17bb](https://linux-hardware.org/?probe=5fc8de17bb) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | [cfa115323d](https://linux-hardware.org/?probe=cfa115323d) | Dec 13, 2023 |
| HP            | Pavilion g6                 | [920939b6c0](https://linux-hardware.org/?probe=920939b6c0) | Dec 13, 2023 |
| Dell          | Latitude 5424 Rugged        | [ce56e420fc](https://linux-hardware.org/?probe=ce56e420fc) | Dec 13, 2023 |
| ASUSTek       | X556UQK                     | [1ac3287ee1](https://linux-hardware.org/?probe=1ac3287ee1) | Dec 13, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [e28730f84d](https://linux-hardware.org/?probe=e28730f84d) | Dec 12, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [f90b33b7d5](https://linux-hardware.org/?probe=f90b33b7d5) | Dec 12, 2023 |
| Dell          | XPS 15 7590                 | [97ca767d40](https://linux-hardware.org/?probe=97ca767d40) | Dec 12, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [774925ed25](https://linux-hardware.org/?probe=774925ed25) | Dec 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 4 21J3C... | [e99a0bd1db](https://linux-hardware.org/?probe=e99a0bd1db) | Dec 12, 2023 |
| Positivo      | H14BT58                     | [74530bb40a](https://linux-hardware.org/?probe=74530bb40a) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [53ee047174](https://linux-hardware.org/?probe=53ee047174) | Dec 12, 2023 |
| Acer          | Aspire one                  | [fb1f2ccd2e](https://linux-hardware.org/?probe=fb1f2ccd2e) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [756283ec58](https://linux-hardware.org/?probe=756283ec58) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [c258c213e6](https://linux-hardware.org/?probe=c258c213e6) | Dec 12, 2023 |
| HP            | EliteBook 830 G5            | [a4bdf16134](https://linux-hardware.org/?probe=a4bdf16134) | Dec 12, 2023 |
| HP            | ProBook 455 G7              | [1bec383138](https://linux-hardware.org/?probe=1bec383138) | Dec 11, 2023 |
| Unknown       | Unknown                     | [79c6d70468](https://linux-hardware.org/?probe=79c6d70468) | Dec 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0d7abecf9b](https://linux-hardware.org/?probe=0d7abecf9b) | Dec 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [3dcb225ff4](https://linux-hardware.org/?probe=3dcb225ff4) | Dec 11, 2023 |
| HP            | Laptop 15-fd0xxx            | [f5b7104728](https://linux-hardware.org/?probe=f5b7104728) | Dec 11, 2023 |
| HP            | Laptop 14s-dy5xxx           | [bfe021294b](https://linux-hardware.org/?probe=bfe021294b) | Dec 11, 2023 |
| Google        | Electro                     | [503645df79](https://linux-hardware.org/?probe=503645df79) | Dec 11, 2023 |
| HP            | ProBook 450 G3              | [57a80d9d1b](https://linux-hardware.org/?probe=57a80d9d1b) | Dec 11, 2023 |
| Dell          | XPS 13 9370                 | [201fa157d6](https://linux-hardware.org/?probe=201fa157d6) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [324e195003](https://linux-hardware.org/?probe=324e195003) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f60e90cfd0](https://linux-hardware.org/?probe=f60e90cfd0) | Dec 10, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [bb7ea992e6](https://linux-hardware.org/?probe=bb7ea992e6) | Dec 09, 2023 |
| Lenovo        | ThinkPad T530 242922G       | [2b8062d3cc](https://linux-hardware.org/?probe=2b8062d3cc) | Dec 09, 2023 |
| Dell          | Latitude E7240              | [93f24d2411](https://linux-hardware.org/?probe=93f24d2411) | Dec 09, 2023 |
| HP            | EliteBook 830 G5            | [b2743fd826](https://linux-hardware.org/?probe=b2743fd826) | Dec 09, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [1435c0e9db](https://linux-hardware.org/?probe=1435c0e9db) | Dec 09, 2023 |
| Dell          | Latitude 7490               | [ad002286ac](https://linux-hardware.org/?probe=ad002286ac) | Dec 09, 2023 |
| Apple         | MacBookPro12,1              | [9d633902a0](https://linux-hardware.org/?probe=9d633902a0) | Dec 09, 2023 |
| HP            | Laptop 15-da0xxx            | [4106c6dbcf](https://linux-hardware.org/?probe=4106c6dbcf) | Dec 09, 2023 |
| ASUSTek       | X507UB                      | [f1a1ea60e6](https://linux-hardware.org/?probe=f1a1ea60e6) | Dec 09, 2023 |
| Dell          | Precision 3550              | [a3be7ab761](https://linux-hardware.org/?probe=a3be7ab761) | Dec 09, 2023 |
| Dell          | Vostro 15 3515              | [0257ed619f](https://linux-hardware.org/?probe=0257ed619f) | Dec 08, 2023 |
| Toshiba       | Satellite L50-A-19P         | [cd3314169e](https://linux-hardware.org/?probe=cd3314169e) | Dec 08, 2023 |
| HP            | G42                         | [f23e6ffe56](https://linux-hardware.org/?probe=f23e6ffe56) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | [b53080f09f](https://linux-hardware.org/?probe=b53080f09f) | Dec 08, 2023 |
| HONOR         | HYM-WXX                     | [b008f53987](https://linux-hardware.org/?probe=b008f53987) | Dec 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1502CBA    | [b46d0490b6](https://linux-hardware.org/?probe=b46d0490b6) | Dec 08, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ba71538aed](https://linux-hardware.org/?probe=ba71538aed) | Dec 08, 2023 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [0e2900b443](https://linux-hardware.org/?probe=0e2900b443) | Dec 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS8H800    | [49fbd4df76](https://linux-hardware.org/?probe=49fbd4df76) | Dec 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS8C000    | [bff5eac6db](https://linux-hardware.org/?probe=bff5eac6db) | Dec 08, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | [1229fd52f5](https://linux-hardware.org/?probe=1229fd52f5) | Dec 08, 2023 |
| HP            | G62                         | [c2f10412aa](https://linux-hardware.org/?probe=c2f10412aa) | Dec 07, 2023 |
| HP            | EliteBook 8470p             | [c723bcc62a](https://linux-hardware.org/?probe=c723bcc62a) | Dec 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e7fabdedad](https://linux-hardware.org/?probe=e7fabdedad) | Dec 07, 2023 |
| Acer          | Extensa 4210                | [4f8a82394a](https://linux-hardware.org/?probe=4f8a82394a) | Dec 07, 2023 |
| Aquarius      | NS585                       | [b6b0a78cfa](https://linux-hardware.org/?probe=b6b0a78cfa) | Dec 07, 2023 |
| MSI           | Prestige 15 A10SC           | [b1c3e47458](https://linux-hardware.org/?probe=b1c3e47458) | Dec 07, 2023 |
| Dell          | Precision 7550              | [11f63c8ba3](https://linux-hardware.org/?probe=11f63c8ba3) | Dec 07, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [256fbd42a6](https://linux-hardware.org/?probe=256fbd42a6) | Dec 06, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [21b8166e02](https://linux-hardware.org/?probe=21b8166e02) | Dec 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [b118593b9d](https://linux-hardware.org/?probe=b118593b9d) | Dec 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [d4ece1c445](https://linux-hardware.org/?probe=d4ece1c445) | Dec 06, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [280a9a93e6](https://linux-hardware.org/?probe=280a9a93e6) | Dec 06, 2023 |
| Dell          | Inspiron 1545               | [d54ba07f49](https://linux-hardware.org/?probe=d54ba07f49) | Dec 06, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [46bc5ee727](https://linux-hardware.org/?probe=46bc5ee727) | Dec 06, 2023 |
| HP            | ENVY Notebook               | [26a4295a68](https://linux-hardware.org/?probe=26a4295a68) | Dec 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0cb29ce493](https://linux-hardware.org/?probe=0cb29ce493) | Dec 05, 2023 |
| Acer          | Aspire A314-22              | [ce624b95df](https://linux-hardware.org/?probe=ce624b95df) | Dec 05, 2023 |
| ASUSTek       | P553UJ                      | [e5ed994bf9](https://linux-hardware.org/?probe=e5ed994bf9) | Dec 05, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [68784031ca](https://linux-hardware.org/?probe=68784031ca) | Dec 05, 2023 |
| HP            | EliteBook 840 G1            | [1b39d673f8](https://linux-hardware.org/?probe=1b39d673f8) | Dec 05, 2023 |
| ASUSTek       | ROG Strix G614JU_G614JU     | [68ec81b134](https://linux-hardware.org/?probe=68ec81b134) | Dec 04, 2023 |
| HP            | Spectre Notebook            | [95b8230b80](https://linux-hardware.org/?probe=95b8230b80) | Dec 04, 2023 |
| HUAWEI        | BOD-WXX9                    | [da8437565a](https://linux-hardware.org/?probe=da8437565a) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [de877c77b2](https://linux-hardware.org/?probe=de877c77b2) | Dec 04, 2023 |
| MSI           | Thin GF63 12VE              | [ada68f6d8a](https://linux-hardware.org/?probe=ada68f6d8a) | Dec 04, 2023 |
| Apple         | MacBookPro5,5               | [82dedf4be4](https://linux-hardware.org/?probe=82dedf4be4) | Dec 04, 2023 |
| MSI           | GF65 Thin 10SER             | [f382271478](https://linux-hardware.org/?probe=f382271478) | Dec 04, 2023 |
| Dell          | Inspiron 5567               | [03fe12170c](https://linux-hardware.org/?probe=03fe12170c) | Dec 04, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [969efab4b8](https://linux-hardware.org/?probe=969efab4b8) | Dec 04, 2023 |
| Acer          | Extensa 215-55              | [87616f0d71](https://linux-hardware.org/?probe=87616f0d71) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | [01485bc011](https://linux-hardware.org/?probe=01485bc011) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [23cf3c751a](https://linux-hardware.org/?probe=23cf3c751a) | Dec 04, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [890efb3114](https://linux-hardware.org/?probe=890efb3114) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [22b736c30d](https://linux-hardware.org/?probe=22b736c30d) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3f26c37883](https://linux-hardware.org/?probe=3f26c37883) | Dec 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | [592eb925fd](https://linux-hardware.org/?probe=592eb925fd) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [75603d3c20](https://linux-hardware.org/?probe=75603d3c20) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [7afcab06a4](https://linux-hardware.org/?probe=7afcab06a4) | Dec 04, 2023 |
| HUAWEI        | BOD-WXX9                    | [961b00cfbe](https://linux-hardware.org/?probe=961b00cfbe) | Dec 04, 2023 |
| Samsung       | R530/R730/R540              | [7c16c8b9ac](https://linux-hardware.org/?probe=7c16c8b9ac) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [bbd413d34b](https://linux-hardware.org/?probe=bbd413d34b) | Dec 03, 2023 |
| Lenovo        | V14-IIL 82C4                | [848e0dbd37](https://linux-hardware.org/?probe=848e0dbd37) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | [b8af3ee6d5](https://linux-hardware.org/?probe=b8af3ee6d5) | Dec 03, 2023 |
| Acer          | Unknown                     | [6555dd06ac](https://linux-hardware.org/?probe=6555dd06ac) | Dec 03, 2023 |
| Acer          | Aspire A315-24P             | [67efae847f](https://linux-hardware.org/?probe=67efae847f) | Dec 03, 2023 |
| HP            | 255 G8 Notebook PC          | [2afc97f78a](https://linux-hardware.org/?probe=2afc97f78a) | Dec 03, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [595fc0137d](https://linux-hardware.org/?probe=595fc0137d) | Dec 03, 2023 |
| Timi          | Mi Laptop Pro 15            | [41ef064705](https://linux-hardware.org/?probe=41ef064705) | Dec 03, 2023 |
| Timi          | Mi Laptop Pro 15            | [b14a847625](https://linux-hardware.org/?probe=b14a847625) | Dec 03, 2023 |
| Dell          | Precision M4800             | [ff01ff15f9](https://linux-hardware.org/?probe=ff01ff15f9) | Dec 03, 2023 |
| Jumper        | EZbook                      | [54cf2bf1d4](https://linux-hardware.org/?probe=54cf2bf1d4) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [3222457362](https://linux-hardware.org/?probe=3222457362) | Dec 03, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [744c430aa7](https://linux-hardware.org/?probe=744c430aa7) | Dec 02, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [1462381824](https://linux-hardware.org/?probe=1462381824) | Dec 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [0869816e7a](https://linux-hardware.org/?probe=0869816e7a) | Dec 02, 2023 |
| Apple         | MacBookPro12,1              | [138a63b91b](https://linux-hardware.org/?probe=138a63b91b) | Dec 02, 2023 |
| Lenovo        | Flex 2-14 20404             | [f366381075](https://linux-hardware.org/?probe=f366381075) | Dec 02, 2023 |
| Sony          | VPCEB46FX                   | [b331dc017f](https://linux-hardware.org/?probe=b331dc017f) | Dec 02, 2023 |
| Lenovo        | ThinkPad X220 4291OL3       | [d07f89fdd6](https://linux-hardware.org/?probe=d07f89fdd6) | Dec 02, 2023 |
| Sony          | VPCF11M1E                   | [f185cc14da](https://linux-hardware.org/?probe=f185cc14da) | Dec 01, 2023 |
| Dell          | Latitude 7440               | [b4179d70c3](https://linux-hardware.org/?probe=b4179d70c3) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d4a1f56f8d](https://linux-hardware.org/?probe=d4a1f56f8d) | Dec 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [fc30a356f0](https://linux-hardware.org/?probe=fc30a356f0) | Dec 01, 2023 |
| Toshiba       | Satellite L775              | [da7cc192f7](https://linux-hardware.org/?probe=da7cc192f7) | Dec 01, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [f17a1eb208](https://linux-hardware.org/?probe=f17a1eb208) | Dec 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H1C... | [7590036270](https://linux-hardware.org/?probe=7590036270) | Dec 01, 2023 |
| Lenovo        | G700 20251                  | [e4e63d5300](https://linux-hardware.org/?probe=e4e63d5300) | Nov 30, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [a828388299](https://linux-hardware.org/?probe=a828388299) | Nov 30, 2023 |
| Dell          | Inspiron 5570               | [6642e4462f](https://linux-hardware.org/?probe=6642e4462f) | Nov 30, 2023 |
| Lenovo        | ThinkPad T590 20N5S56P00    | [352fffb7a9](https://linux-hardware.org/?probe=352fffb7a9) | Nov 30, 2023 |
| Toshiba       | Satellite L455D             | [d08710e3d3](https://linux-hardware.org/?probe=d08710e3d3) | Nov 29, 2023 |
| Samsung       | RC530/RC730                 | [01aee620f1](https://linux-hardware.org/?probe=01aee620f1) | Nov 29, 2023 |
| HP            | Pavilion dv6                | [ddce26dd72](https://linux-hardware.org/?probe=ddce26dd72) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [1b7f8a15dd](https://linux-hardware.org/?probe=1b7f8a15dd) | Nov 29, 2023 |
| HP            | Laptop 15s-du0xxx           | [bf583ba008](https://linux-hardware.org/?probe=bf583ba008) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [ef2a2ab2a9](https://linux-hardware.org/?probe=ef2a2ab2a9) | Nov 29, 2023 |
| ASUSTek       | M50Vc                       | [0eba431c7a](https://linux-hardware.org/?probe=0eba431c7a) | Nov 29, 2023 |
| Acer          | Nitro AN515-55              | [6865be0fd7](https://linux-hardware.org/?probe=6865be0fd7) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [414132dc07](https://linux-hardware.org/?probe=414132dc07) | Nov 29, 2023 |
| Lenovo        | ThinkPad T520 4243VU3       | [6cbaf1893d](https://linux-hardware.org/?probe=6cbaf1893d) | Nov 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [66847c493b](https://linux-hardware.org/?probe=66847c493b) | Nov 29, 2023 |
| Dell          | Precision 7560              | [035f0d6f41](https://linux-hardware.org/?probe=035f0d6f41) | Nov 29, 2023 |
| HP            | ProBook 450 G3              | [0d6a4cd900](https://linux-hardware.org/?probe=0d6a4cd900) | Nov 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [b01d99f799](https://linux-hardware.org/?probe=b01d99f799) | Nov 28, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [6b10244910](https://linux-hardware.org/?probe=6b10244910) | Nov 28, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [413049d0f4](https://linux-hardware.org/?probe=413049d0f4) | Nov 28, 2023 |
| MSI           | Prestige 16Studio A13VF     | [4d8fb7dd05](https://linux-hardware.org/?probe=4d8fb7dd05) | Nov 28, 2023 |
| HP            | ZBook 15 G6                 | [1f87fc5fca](https://linux-hardware.org/?probe=1f87fc5fca) | Nov 28, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [93d9d89a9a](https://linux-hardware.org/?probe=93d9d89a9a) | Nov 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [3fe11b3243](https://linux-hardware.org/?probe=3fe11b3243) | Nov 27, 2023 |
| Lenovo        | Flex 2 Pro-15               | [7e7f94ca3b](https://linux-hardware.org/?probe=7e7f94ca3b) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | [705aa34dce](https://linux-hardware.org/?probe=705aa34dce) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | [569db41ca1](https://linux-hardware.org/?probe=569db41ca1) | Nov 27, 2023 |
| Daten Tecn... | DCM3A-4                     | [66b8d06d48](https://linux-hardware.org/?probe=66b8d06d48) | Nov 27, 2023 |
| Lenovo        | ThinkPad T490 20N3S2YS00    | [635d73bd44](https://linux-hardware.org/?probe=635d73bd44) | Nov 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [2715c8329f](https://linux-hardware.org/?probe=2715c8329f) | Nov 27, 2023 |
| Google        | Terra                       | [b21072bf0e](https://linux-hardware.org/?probe=b21072bf0e) | Nov 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [97e207d679](https://linux-hardware.org/?probe=97e207d679) | Nov 27, 2023 |
| Acer          | Aspire A515-56              | [419daf1e57](https://linux-hardware.org/?probe=419daf1e57) | Nov 27, 2023 |
| Lenovo        | ThinkPad X200 7458PN6       | [e37f4ef1d4](https://linux-hardware.org/?probe=e37f4ef1d4) | Nov 27, 2023 |
| HUAWEI        | BOM-WXX9                    | [13c14b2399](https://linux-hardware.org/?probe=13c14b2399) | Nov 27, 2023 |
| Unknown       | Unknown                     | [5cf9f0b3e1](https://linux-hardware.org/?probe=5cf9f0b3e1) | Nov 27, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [f18c7cb67b](https://linux-hardware.org/?probe=f18c7cb67b) | Nov 26, 2023 |
| HP            | Laptop 15s-fq2xxx           | [f0b4d1d85c](https://linux-hardware.org/?probe=f0b4d1d85c) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [332eec50ca](https://linux-hardware.org/?probe=332eec50ca) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | [9e05915f77](https://linux-hardware.org/?probe=9e05915f77) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | [ff1af2d7d2](https://linux-hardware.org/?probe=ff1af2d7d2) | Nov 26, 2023 |
| HP            | Laptop 15-dy2xxx            | [484699c792](https://linux-hardware.org/?probe=484699c792) | Nov 26, 2023 |
| Acer          | Swift SF314-42              | [bebbc2f6c4](https://linux-hardware.org/?probe=bebbc2f6c4) | Nov 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0f05f2568e](https://linux-hardware.org/?probe=0f05f2568e) | Nov 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [8cba28d4a5](https://linux-hardware.org/?probe=8cba28d4a5) | Nov 25, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [1e4a3ed089](https://linux-hardware.org/?probe=1e4a3ed089) | Nov 25, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [f740e978fc](https://linux-hardware.org/?probe=f740e978fc) | Nov 25, 2023 |
| HP            | EliteBook 735 G6            | [a0480513dd](https://linux-hardware.org/?probe=a0480513dd) | Nov 25, 2023 |
| HP            | EliteBook 2570p             | [e01ac99a92](https://linux-hardware.org/?probe=e01ac99a92) | Nov 25, 2023 |
| HP            | Laptop 15s-du0xxx           | [7e541895b2](https://linux-hardware.org/?probe=7e541895b2) | Nov 25, 2023 |
| HP            | Compaq 6730b (NB027EA#AK... | [3b3bf03eee](https://linux-hardware.org/?probe=3b3bf03eee) | Nov 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | [9620d48b2f](https://linux-hardware.org/?probe=9620d48b2f) | Nov 25, 2023 |
| Dell          | Latitude 3510               | [0ebe37e56d](https://linux-hardware.org/?probe=0ebe37e56d) | Nov 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [eb4379efae](https://linux-hardware.org/?probe=eb4379efae) | Nov 24, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [4b725b7022](https://linux-hardware.org/?probe=4b725b7022) | Nov 24, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [9a8395f2ac](https://linux-hardware.org/?probe=9a8395f2ac) | Nov 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [59a3d34f64](https://linux-hardware.org/?probe=59a3d34f64) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [499c7927dd](https://linux-hardware.org/?probe=499c7927dd) | Nov 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9102327ebf](https://linux-hardware.org/?probe=9102327ebf) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e5ad7dda0](https://linux-hardware.org/?probe=1e5ad7dda0) | Nov 23, 2023 |
| Samsung       | 270E5J/2570EJ               | [d6ab9c6df5](https://linux-hardware.org/?probe=d6ab9c6df5) | Nov 23, 2023 |
| Lenovo        | ThinkPad T460 20FMS57C00    | [adabeb3e91](https://linux-hardware.org/?probe=adabeb3e91) | Nov 23, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [b6496b25f7](https://linux-hardware.org/?probe=b6496b25f7) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [be47adc197](https://linux-hardware.org/?probe=be47adc197) | Nov 23, 2023 |
| Google        | Edgar                       | [12d8e1b6af](https://linux-hardware.org/?probe=12d8e1b6af) | Nov 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [0337023dbe](https://linux-hardware.org/?probe=0337023dbe) | Nov 22, 2023 |
| Dell          | XPS 13 9360                 | [ace74e0228](https://linux-hardware.org/?probe=ace74e0228) | Nov 22, 2023 |
| HP            | Laptop 15-dw1xxx            | [d05f324edf](https://linux-hardware.org/?probe=d05f324edf) | Nov 22, 2023 |
| Dell          | Precision M4600             | [864f0c5cfe](https://linux-hardware.org/?probe=864f0c5cfe) | Nov 22, 2023 |
| Lenovo        | ThinkPad P52 20MAS21905     | [ada7aab2dd](https://linux-hardware.org/?probe=ada7aab2dd) | Nov 22, 2023 |
| Lenovo        | G500 20236                  | [43a399828f](https://linux-hardware.org/?probe=43a399828f) | Nov 22, 2023 |
| Lenovo        | G500 20236                  | [b72fbdf43a](https://linux-hardware.org/?probe=b72fbdf43a) | Nov 22, 2023 |
| Dell          | Latitude E6400              | [adb43d89ab](https://linux-hardware.org/?probe=adb43d89ab) | Nov 22, 2023 |
| Dell          | Latitude 7440               | [fa13937043](https://linux-hardware.org/?probe=fa13937043) | Nov 22, 2023 |
| Dell          | Latitude E6400              | [96e98f8c80](https://linux-hardware.org/?probe=96e98f8c80) | Nov 22, 2023 |
| HP            | G62                         | [de2f290631](https://linux-hardware.org/?probe=de2f290631) | Nov 20, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [7c6999858f](https://linux-hardware.org/?probe=7c6999858f) | Nov 20, 2023 |
| Lenovo        | G580 2189                   | [3ec9fbcdea](https://linux-hardware.org/?probe=3ec9fbcdea) | Nov 20, 2023 |
| Dell          | Latitude 5401               | [b3698296b0](https://linux-hardware.org/?probe=b3698296b0) | Nov 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [a090e73dbf](https://linux-hardware.org/?probe=a090e73dbf) | Nov 20, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [e0d3e7cba3](https://linux-hardware.org/?probe=e0d3e7cba3) | Nov 19, 2023 |
| Lenovo        | G510 20238                  | [2567713f24](https://linux-hardware.org/?probe=2567713f24) | Nov 19, 2023 |
| Dell          | XPS 15 7590                 | [a40bc78bcf](https://linux-hardware.org/?probe=a40bc78bcf) | Nov 19, 2023 |
| Toshiba       | QOSMIO X70-A                | [4173fd74a2](https://linux-hardware.org/?probe=4173fd74a2) | Nov 19, 2023 |
| IBM           | ThinkPad T42 2374GB1        | [455a2c937b](https://linux-hardware.org/?probe=455a2c937b) | Nov 19, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [ebfe063207](https://linux-hardware.org/?probe=ebfe063207) | Nov 19, 2023 |
| HP            | ProBook 650 G1              | [80d502e7c1](https://linux-hardware.org/?probe=80d502e7c1) | Nov 19, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [65f7027c84](https://linux-hardware.org/?probe=65f7027c84) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [deea1f8184](https://linux-hardware.org/?probe=deea1f8184) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [08f1313c20](https://linux-hardware.org/?probe=08f1313c20) | Nov 19, 2023 |
| HP            | Laptop 15-da0xxx            | [fa116d20dc](https://linux-hardware.org/?probe=fa116d20dc) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [a566513a93](https://linux-hardware.org/?probe=a566513a93) | Nov 19, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [8ebb2df251](https://linux-hardware.org/?probe=8ebb2df251) | Nov 18, 2023 |
| MSI           | N6105                       | [647e6d71a4](https://linux-hardware.org/?probe=647e6d71a4) | Nov 18, 2023 |
| Lenovo        | G580 2189                   | [9a96aff4c7](https://linux-hardware.org/?probe=9a96aff4c7) | Nov 18, 2023 |
| HP            | Laptop 15-da0xxx            | [666f76f4e9](https://linux-hardware.org/?probe=666f76f4e9) | Nov 18, 2023 |
| Dell          | Latitude E6230              | [2a2d7c242e](https://linux-hardware.org/?probe=2a2d7c242e) | Nov 18, 2023 |
| HP            | Stream Notebook             | [5d318f7956](https://linux-hardware.org/?probe=5d318f7956) | Nov 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [0fcb08b949](https://linux-hardware.org/?probe=0fcb08b949) | Nov 18, 2023 |
| Toshiba       | Satellite L300              | [416018ed84](https://linux-hardware.org/?probe=416018ed84) | Nov 17, 2023 |
| Irbis         | NB120                       | [a90949861b](https://linux-hardware.org/?probe=a90949861b) | Nov 17, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [204303d116](https://linux-hardware.org/?probe=204303d116) | Nov 17, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [c8af1c096b](https://linux-hardware.org/?probe=c8af1c096b) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [026b13382d](https://linux-hardware.org/?probe=026b13382d) | Nov 17, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | [be914025c2](https://linux-hardware.org/?probe=be914025c2) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | [f61bc8d881](https://linux-hardware.org/?probe=f61bc8d881) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | [53dd735333](https://linux-hardware.org/?probe=53dd735333) | Nov 17, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [893762777e](https://linux-hardware.org/?probe=893762777e) | Nov 17, 2023 |
| MSI           | GS65 Stealth 9SD            | [b0eba2e921](https://linux-hardware.org/?probe=b0eba2e921) | Nov 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S55K00    | [ba85d81d10](https://linux-hardware.org/?probe=ba85d81d10) | Nov 16, 2023 |
| Schenker      | VIA 15 Pro                  | [604f785353](https://linux-hardware.org/?probe=604f785353) | Nov 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S55K00    | [b2c3886395](https://linux-hardware.org/?probe=b2c3886395) | Nov 16, 2023 |
| Acer          | Aspire V3-771               | [5b38f976c4](https://linux-hardware.org/?probe=5b38f976c4) | Nov 16, 2023 |
| MSI           | GS65 Stealth 9SD            | [0331447937](https://linux-hardware.org/?probe=0331447937) | Nov 16, 2023 |
| Dell          | Latitude 5530               | [4490ae8afe](https://linux-hardware.org/?probe=4490ae8afe) | Nov 16, 2023 |
| Lenovo        | G50-70 20351                | [7f136c3e39](https://linux-hardware.org/?probe=7f136c3e39) | Nov 16, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [e7e00bb090](https://linux-hardware.org/?probe=e7e00bb090) | Nov 16, 2023 |
| Dell          | Latitude 3320               | [19a9472e3c](https://linux-hardware.org/?probe=19a9472e3c) | Nov 16, 2023 |
| Dell          | Latitude 3320               | [285ad2f27a](https://linux-hardware.org/?probe=285ad2f27a) | Nov 16, 2023 |
| Acer          | Aspire A315-42              | [a21066a759](https://linux-hardware.org/?probe=a21066a759) | Nov 15, 2023 |
| Acer          | Aspire E1-572               | [c7c8df77be](https://linux-hardware.org/?probe=c7c8df77be) | Nov 15, 2023 |
| HP            | Laptop 15-da0xxx            | [3f0b4a0bfe](https://linux-hardware.org/?probe=3f0b4a0bfe) | Nov 15, 2023 |
| Acer          | Extensa 215-32              | [477b965e66](https://linux-hardware.org/?probe=477b965e66) | Nov 15, 2023 |
| Acer          | Aspire E5-576G              | [694833562c](https://linux-hardware.org/?probe=694833562c) | Nov 15, 2023 |
| HP            | Pavilion dv6                | [a7404738ed](https://linux-hardware.org/?probe=a7404738ed) | Nov 15, 2023 |
| Lenovo        | XiaoXinPro 16 IRH8 83AQ     | [1eb15d0477](https://linux-hardware.org/?probe=1eb15d0477) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [98dd1a4a4f](https://linux-hardware.org/?probe=98dd1a4a4f) | Nov 15, 2023 |
| Dell          | Inspiron 1545               | [fd459af24b](https://linux-hardware.org/?probe=fd459af24b) | Nov 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [049356e4bc](https://linux-hardware.org/?probe=049356e4bc) | Nov 15, 2023 |
| Lenovo        | ThinkPad X280 20KES5840A    | [8800b951d8](https://linux-hardware.org/?probe=8800b951d8) | Nov 14, 2023 |
| Phoenix/Si... | M730SR                      | [59e9d07293](https://linux-hardware.org/?probe=59e9d07293) | Nov 14, 2023 |
| TUXEDO        | Unknown                     | [e90f4e1799](https://linux-hardware.org/?probe=e90f4e1799) | Nov 14, 2023 |
| MSI           | Thin GF63 12HW              | [bdac7a70aa](https://linux-hardware.org/?probe=bdac7a70aa) | Nov 14, 2023 |
| Acer          | Extensa 2540                | [22e65d0a5b](https://linux-hardware.org/?probe=22e65d0a5b) | Nov 14, 2023 |
| Packard Be... | EasyNote TK81               | [a44fd2dc7a](https://linux-hardware.org/?probe=a44fd2dc7a) | Nov 14, 2023 |
| Acer          | Aspire A315-42              | [42d05f19a2](https://linux-hardware.org/?probe=42d05f19a2) | Nov 13, 2023 |
| Apple         | MacBookPro5,5               | [57e4a13fab](https://linux-hardware.org/?probe=57e4a13fab) | Nov 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [137d579104](https://linux-hardware.org/?probe=137d579104) | Nov 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [aacc7d1f61](https://linux-hardware.org/?probe=aacc7d1f61) | Nov 13, 2023 |
| Acer          | Aspire ES1-521              | [429add2d41](https://linux-hardware.org/?probe=429add2d41) | Nov 13, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | [2bc7d7c816](https://linux-hardware.org/?probe=2bc7d7c816) | Nov 13, 2023 |
| HP            | Presario CQ57               | [0d4999d483](https://linux-hardware.org/?probe=0d4999d483) | Nov 13, 2023 |
| HP            | Laptop 15-dy2xxx            | [189c917237](https://linux-hardware.org/?probe=189c917237) | Nov 13, 2023 |
| HP            | ZBook 15 G2                 | [960b3732b0](https://linux-hardware.org/?probe=960b3732b0) | Nov 13, 2023 |
| Toshiba       | Satellite L40               | [0d2accfed1](https://linux-hardware.org/?probe=0d2accfed1) | Nov 13, 2023 |
| Apple         | MacBookPro16,2              | [bbc6a54b40](https://linux-hardware.org/?probe=bbc6a54b40) | Nov 12, 2023 |
| Google        | Hanawl                      | [39b8f28b8e](https://linux-hardware.org/?probe=39b8f28b8e) | Nov 12, 2023 |
| Google        | Hana                        | [80ae861cdf](https://linux-hardware.org/?probe=80ae861cdf) | Nov 12, 2023 |
| Acer          | Aspire 5735                 | [539da3b61a](https://linux-hardware.org/?probe=539da3b61a) | Nov 12, 2023 |
| Google        | Akemi                       | [c0722184e7](https://linux-hardware.org/?probe=c0722184e7) | Nov 12, 2023 |
| Lenovo        | ThinkPad Edge E535 32607... | [f5bea4eb8b](https://linux-hardware.org/?probe=f5bea4eb8b) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [929afc7ae1](https://linux-hardware.org/?probe=929afc7ae1) | Nov 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [d3fd2f491d](https://linux-hardware.org/?probe=d3fd2f491d) | Nov 12, 2023 |
| HP            | EliteBook 2530p             | [4a9666ef8a](https://linux-hardware.org/?probe=4a9666ef8a) | Nov 12, 2023 |
| HP            | 15                          | [dbd704fdbb](https://linux-hardware.org/?probe=dbd704fdbb) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [daab2f9dc6](https://linux-hardware.org/?probe=daab2f9dc6) | Nov 11, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | [e713ed7256](https://linux-hardware.org/?probe=e713ed7256) | Nov 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | [4bf49cfb42](https://linux-hardware.org/?probe=4bf49cfb42) | Nov 11, 2023 |
| Timi          | Mi NoteBook Pro             | [f08c831e30](https://linux-hardware.org/?probe=f08c831e30) | Nov 11, 2023 |
| Apple         | MacBookPro8,1               | [3da6dfb4b3](https://linux-hardware.org/?probe=3da6dfb4b3) | Nov 11, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [de5f1aa77e](https://linux-hardware.org/?probe=de5f1aa77e) | Nov 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f4dc3b24c4](https://linux-hardware.org/?probe=f4dc3b24c4) | Nov 11, 2023 |
| HP            | Stream Notebook             | [f93159b053](https://linux-hardware.org/?probe=f93159b053) | Nov 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b88ecdebac](https://linux-hardware.org/?probe=b88ecdebac) | Nov 10, 2023 |
| Acer          | Aspire A315-54              | [a83ac39876](https://linux-hardware.org/?probe=a83ac39876) | Nov 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [518492850b](https://linux-hardware.org/?probe=518492850b) | Nov 10, 2023 |
| HP            | ProBook 4510s               | [9b83dea197](https://linux-hardware.org/?probe=9b83dea197) | Nov 10, 2023 |
| Aquarius      | NS585                       | [0f0c55bda1](https://linux-hardware.org/?probe=0f0c55bda1) | Nov 10, 2023 |
| Acer          | Aspire A315-23              | [95ea718240](https://linux-hardware.org/?probe=95ea718240) | Nov 10, 2023 |
| Lenovo        | ThinkPad T420 4180AZ8       | [089405c957](https://linux-hardware.org/?probe=089405c957) | Nov 09, 2023 |
| Apple         | MacBook2,1                  | [448165ceca](https://linux-hardware.org/?probe=448165ceca) | Nov 09, 2023 |
| ASUSTek       | S400CA                      | [0e5628865a](https://linux-hardware.org/?probe=0e5628865a) | Nov 09, 2023 |
| ASUSTek       | Vivobook Go E1504GA_E150... | [50b3f888e9](https://linux-hardware.org/?probe=50b3f888e9) | Nov 09, 2023 |
| ASUSTek       | Vivobook Go E1504GA_E150... | [a2c63a08f3](https://linux-hardware.org/?probe=a2c63a08f3) | Nov 09, 2023 |
| Acer          | Aspire A515-47              | [50a18dd494](https://linux-hardware.org/?probe=50a18dd494) | Nov 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [4b96ca83d1](https://linux-hardware.org/?probe=4b96ca83d1) | Nov 09, 2023 |
| Dell          | Latitude 5420               | [efa8caa859](https://linux-hardware.org/?probe=efa8caa859) | Nov 09, 2023 |
| HP            | Pavilion Notebook           | [c8c4c09226](https://linux-hardware.org/?probe=c8c4c09226) | Nov 08, 2023 |
| Dell          | Latitude E5430 non-vPro     | [39e2c7584e](https://linux-hardware.org/?probe=39e2c7584e) | Nov 08, 2023 |
| Acer          | Aspire F5-573G              | [afeda2ac5e](https://linux-hardware.org/?probe=afeda2ac5e) | Nov 08, 2023 |
| HP            | Stream Notebook PC 13       | [25387a2c6f](https://linux-hardware.org/?probe=25387a2c6f) | Nov 08, 2023 |
| Lenovo        | ThinkPad X121e 30515YG      | [4008ec0eb0](https://linux-hardware.org/?probe=4008ec0eb0) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [46458a043d](https://linux-hardware.org/?probe=46458a043d) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [52b0129f48](https://linux-hardware.org/?probe=52b0129f48) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [b05a5bff97](https://linux-hardware.org/?probe=b05a5bff97) | Nov 08, 2023 |
| MACHENIKE     | L16P                        | [c8e67672f3](https://linux-hardware.org/?probe=c8e67672f3) | Nov 08, 2023 |
| Samsung       | 767XCL                      | [beba8edd4f](https://linux-hardware.org/?probe=beba8edd4f) | Nov 08, 2023 |
| Apple         | MacBook5,1                  | [ed339d2cbb](https://linux-hardware.org/?probe=ed339d2cbb) | Nov 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [0fceea6321](https://linux-hardware.org/?probe=0fceea6321) | Nov 08, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b111aacb49](https://linux-hardware.org/?probe=b111aacb49) | Nov 08, 2023 |
| Acer          | Aspire A515-43              | [6e215a4ade](https://linux-hardware.org/?probe=6e215a4ade) | Nov 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [54b91fa265](https://linux-hardware.org/?probe=54b91fa265) | Nov 08, 2023 |
| Dell          | Latitude 5414               | [ad924833a5](https://linux-hardware.org/?probe=ad924833a5) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [696f32a866](https://linux-hardware.org/?probe=696f32a866) | Nov 08, 2023 |
| Apple         | MacBook5,2                  | [24a63b1a77](https://linux-hardware.org/?probe=24a63b1a77) | Nov 07, 2023 |
| Google        | Akemi                       | [e3010845ab](https://linux-hardware.org/?probe=e3010845ab) | Nov 07, 2023 |
| Apple         | MacBookAir7,1               | [dcbc2d171e](https://linux-hardware.org/?probe=dcbc2d171e) | Nov 07, 2023 |
| Aquarius      | NS585                       | [a5b5734657](https://linux-hardware.org/?probe=a5b5734657) | Nov 07, 2023 |
| Lenovo        | ThinkPad T470 20HES3JR02    | [4cdded6623](https://linux-hardware.org/?probe=4cdded6623) | Nov 07, 2023 |
| Aquarius      | NS585                       | [d9d5e97f89](https://linux-hardware.org/?probe=d9d5e97f89) | Nov 07, 2023 |
| Unknown       | Unknown                     | [988072756b](https://linux-hardware.org/?probe=988072756b) | Nov 07, 2023 |
| Aquarius      | NS585                       | [83a4894072](https://linux-hardware.org/?probe=83a4894072) | Nov 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [1d557ddec8](https://linux-hardware.org/?probe=1d557ddec8) | Nov 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [beca8ba507](https://linux-hardware.org/?probe=beca8ba507) | Nov 07, 2023 |
| ASUSTek       | X200CA                      | [a982252e30](https://linux-hardware.org/?probe=a982252e30) | Nov 07, 2023 |
| Lenovo        | ThinkPad T430 23475H2       | [3dcdf3830e](https://linux-hardware.org/?probe=3dcdf3830e) | Nov 07, 2023 |
| HP            | Pavilion Notebook           | [8cf5696a9e](https://linux-hardware.org/?probe=8cf5696a9e) | Nov 07, 2023 |
| MSI           | Modern 15 A10M              | [e1120cd270](https://linux-hardware.org/?probe=e1120cd270) | Nov 06, 2023 |
| MSI           | Sword 15 A12UGS             | [956c05cdfe](https://linux-hardware.org/?probe=956c05cdfe) | Nov 06, 2023 |
| HP            | EliteBook 8460p             | [cc6b66c576](https://linux-hardware.org/?probe=cc6b66c576) | Nov 06, 2023 |
| Aquarius      | NS585                       | [ddc8256647](https://linux-hardware.org/?probe=ddc8256647) | Nov 06, 2023 |
| Aquarius      | NS585                       | [2f4e49837d](https://linux-hardware.org/?probe=2f4e49837d) | Nov 06, 2023 |
| Aquarius      | NS585                       | [4fea63336a](https://linux-hardware.org/?probe=4fea63336a) | Nov 06, 2023 |
| HP            | 250 G7 Notebook PC          | [a2ad36d26c](https://linux-hardware.org/?probe=a2ad36d26c) | Nov 06, 2023 |
| Toshiba       | TECRA R950                  | [864877692e](https://linux-hardware.org/?probe=864877692e) | Nov 05, 2023 |
| ASUSTek       | X541NA                      | [f0399efc08](https://linux-hardware.org/?probe=f0399efc08) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [92ed6d25c3](https://linux-hardware.org/?probe=92ed6d25c3) | Nov 05, 2023 |
| HP            | Mini 210-3000               | [8b55a876a9](https://linux-hardware.org/?probe=8b55a876a9) | Nov 05, 2023 |
| Google        | Nami                        | [19c94b9484](https://linux-hardware.org/?probe=19c94b9484) | Nov 05, 2023 |
| HP            | Laptop 15-bw0xx             | [7d9395e4a7](https://linux-hardware.org/?probe=7d9395e4a7) | Nov 05, 2023 |
| HP            | EliteBook 840 G3            | [1bb894cf19](https://linux-hardware.org/?probe=1bb894cf19) | Nov 04, 2023 |
| HP            | Pavilion dv7                | [6a44cc2c3c](https://linux-hardware.org/?probe=6a44cc2c3c) | Nov 04, 2023 |
| Acer          | AO532h                      | [0b3d66b04a](https://linux-hardware.org/?probe=0b3d66b04a) | Nov 04, 2023 |
| Dell          | Inspiron 16 5620            | [04d425d450](https://linux-hardware.org/?probe=04d425d450) | Nov 04, 2023 |
| Google        | Bluebird                    | [55dbc11653](https://linux-hardware.org/?probe=55dbc11653) | Nov 04, 2023 |
| Google        | Bluebird                    | [9e12130a28](https://linux-hardware.org/?probe=9e12130a28) | Nov 04, 2023 |
| HP            | OMEN by Laptop 17-ck1xxx    | [bea6a6babf](https://linux-hardware.org/?probe=bea6a6babf) | Nov 04, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | [0767db36fe](https://linux-hardware.org/?probe=0767db36fe) | Nov 04, 2023 |
| Dell          | Precision 7560              | [54a8deb305](https://linux-hardware.org/?probe=54a8deb305) | Nov 04, 2023 |
| ASUSTek       | X551CA                      | [20bee22e0a](https://linux-hardware.org/?probe=20bee22e0a) | Nov 03, 2023 |
| Packard Be... | EasyNote TK87               | [3ff2e66179](https://linux-hardware.org/?probe=3ff2e66179) | Nov 03, 2023 |
| Dell          | Latitude E6420              | [43ccf36bf0](https://linux-hardware.org/?probe=43ccf36bf0) | Nov 03, 2023 |
| Google        | Enguarde                    | [bc6a541eb9](https://linux-hardware.org/?probe=bc6a541eb9) | Nov 03, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8b855ce4f4](https://linux-hardware.org/?probe=8b855ce4f4) | Nov 03, 2023 |
| Lenovo        | G500s 20245                 | [c4aa915297](https://linux-hardware.org/?probe=c4aa915297) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1bdfa38b3e](https://linux-hardware.org/?probe=1bdfa38b3e) | Nov 03, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| ASUSTek       | X205TA                      | [b29e9ebfbe](https://linux-hardware.org/?probe=b29e9ebfbe) | Nov 03, 2023 |
| HP            | 250 G7 Notebook PC          | [1889111d8a](https://linux-hardware.org/?probe=1889111d8a) | Nov 03, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [212105774f](https://linux-hardware.org/?probe=212105774f) | Nov 02, 2023 |
| ASUSTek       | G750JX                      | [9493bec7e6](https://linux-hardware.org/?probe=9493bec7e6) | Nov 02, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [7c06ac2664](https://linux-hardware.org/?probe=7c06ac2664) | Nov 02, 2023 |
| Dell          | Vostro 14-3468              | [33a984f9f8](https://linux-hardware.org/?probe=33a984f9f8) | Nov 02, 2023 |
| HP            | Pavilion g6                 | [8c9de8be4f](https://linux-hardware.org/?probe=8c9de8be4f) | Nov 02, 2023 |
| HP            | Pavilion g6                 | [c35f9a55aa](https://linux-hardware.org/?probe=c35f9a55aa) | Nov 02, 2023 |
| Google        | Nasher360                   | [0d1cc1b584](https://linux-hardware.org/?probe=0d1cc1b584) | Nov 02, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [df4f43ca44](https://linux-hardware.org/?probe=df4f43ca44) | Nov 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [bb5bbc3e51](https://linux-hardware.org/?probe=bb5bbc3e51) | Nov 01, 2023 |
| Acer          | TravelMate P215-52          | [b9c3643e62](https://linux-hardware.org/?probe=b9c3643e62) | Nov 01, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [ac563e5542](https://linux-hardware.org/?probe=ac563e5542) | Nov 01, 2023 |
| HP            | Laptop 15s-eq1xxx           | [075049b538](https://linux-hardware.org/?probe=075049b538) | Nov 01, 2023 |
| Dell          | Precision M4700             | [1d7e76c1d9](https://linux-hardware.org/?probe=1d7e76c1d9) | Nov 01, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [317aadad91](https://linux-hardware.org/?probe=317aadad91) | Nov 01, 2023 |
| Dell          | Vostro 5590                 | [300630cf8c](https://linux-hardware.org/?probe=300630cf8c) | Nov 01, 2023 |
| Dell          | Latitude 5480               | [1bf5aeba87](https://linux-hardware.org/?probe=1bf5aeba87) | Nov 01, 2023 |
| Toshiba       | Satellite L845              | [90e266bd8e](https://linux-hardware.org/?probe=90e266bd8e) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [2bdd27dc18](https://linux-hardware.org/?probe=2bdd27dc18) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [cb35a8d8f6](https://linux-hardware.org/?probe=cb35a8d8f6) | Oct 31, 2023 |
| HP            | 255 G8 Notebook PC          | [b9d1b13098](https://linux-hardware.org/?probe=b9d1b13098) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4ebd30711e](https://linux-hardware.org/?probe=4ebd30711e) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [a664733aaf](https://linux-hardware.org/?probe=a664733aaf) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [72131fb5de](https://linux-hardware.org/?probe=72131fb5de) | Oct 31, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [ea29ba4b58](https://linux-hardware.org/?probe=ea29ba4b58) | Oct 31, 2023 |
| VANT          | MOOVE3-15                   | [5fc04a6d0a](https://linux-hardware.org/?probe=5fc04a6d0a) | Oct 31, 2023 |
| Lenovo        | ThinkPad X230 2325T55       | [bb4d04c61d](https://linux-hardware.org/?probe=bb4d04c61d) | Oct 31, 2023 |
| Apple         | MacBookPro9,1               | [8f7c5b801b](https://linux-hardware.org/?probe=8f7c5b801b) | Oct 31, 2023 |
| Apple         | MacBookPro9,1               | [4e15275faa](https://linux-hardware.org/?probe=4e15275faa) | Oct 31, 2023 |
| HP            | Victus by Gaming Laptop ... | [0f4fa9169b](https://linux-hardware.org/?probe=0f4fa9169b) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [40ae523147](https://linux-hardware.org/?probe=40ae523147) | Oct 31, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [2f63bfb399](https://linux-hardware.org/?probe=2f63bfb399) | Oct 31, 2023 |
| VANT          | MOOVE3-15                   | [7e12621e6d](https://linux-hardware.org/?probe=7e12621e6d) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 14S           | [780e721e24](https://linux-hardware.org/?probe=780e721e24) | Oct 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [c4baf8a67b](https://linux-hardware.org/?probe=c4baf8a67b) | Oct 30, 2023 |
| THUNDEROBO... | 911AirD                     | [698adeeba7](https://linux-hardware.org/?probe=698adeeba7) | Oct 30, 2023 |
| Dell          | XPS 15 9520                 | [0fb7ced892](https://linux-hardware.org/?probe=0fb7ced892) | Oct 30, 2023 |
| Lenovo        | Flex 2 Pro-15               | [ff5f14115e](https://linux-hardware.org/?probe=ff5f14115e) | Oct 30, 2023 |
| Google        | Blooguard                   | [cd817fb666](https://linux-hardware.org/?probe=cd817fb666) | Oct 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [995b159589](https://linux-hardware.org/?probe=995b159589) | Oct 30, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [8b1fe7cf44](https://linux-hardware.org/?probe=8b1fe7cf44) | Oct 30, 2023 |
| Gigabyte      | A5 X1                       | [981be88a61](https://linux-hardware.org/?probe=981be88a61) | Oct 30, 2023 |
| HP            | EliteBook 840 G6            | [586f08e1dc](https://linux-hardware.org/?probe=586f08e1dc) | Oct 30, 2023 |
| Lenovo        | ThinkPad 25 20K70000GE      | [ce13c83c47](https://linux-hardware.org/?probe=ce13c83c47) | Oct 29, 2023 |
| Lenovo        | ThinkPad 25 20K70000GE      | [597958381f](https://linux-hardware.org/?probe=597958381f) | Oct 29, 2023 |
| HP            | Pavilion g6                 | [57441db309](https://linux-hardware.org/?probe=57441db309) | Oct 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [91f7b242b9](https://linux-hardware.org/?probe=91f7b242b9) | Oct 28, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [4aceca5660](https://linux-hardware.org/?probe=4aceca5660) | Oct 28, 2023 |
| Acer          | Aspire 4752                 | [ce321700bc](https://linux-hardware.org/?probe=ce321700bc) | Oct 28, 2023 |
| Toshiba       | TECRA R950                  | [afa984b0d3](https://linux-hardware.org/?probe=afa984b0d3) | Oct 28, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [dcd6988b7a](https://linux-hardware.org/?probe=dcd6988b7a) | Oct 28, 2023 |
| Acer          | Aspire A115-31              | [137821ca25](https://linux-hardware.org/?probe=137821ca25) | Oct 28, 2023 |
| TELECOMITA... | M7x0S                       | [feabc7e111](https://linux-hardware.org/?probe=feabc7e111) | Oct 28, 2023 |
| MSI           | WS63 7RK                    | [dcfa2c2f75](https://linux-hardware.org/?probe=dcfa2c2f75) | Oct 27, 2023 |
| Lenovo        | ThinkPad X230 2325SDE       | [cbdbd4a156](https://linux-hardware.org/?probe=cbdbd4a156) | Oct 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d8bfe77d00](https://linux-hardware.org/?probe=d8bfe77d00) | Oct 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [198bee98eb](https://linux-hardware.org/?probe=198bee98eb) | Oct 27, 2023 |
| Lenovo        | G50-70 20351                | [39e2fb6be6](https://linux-hardware.org/?probe=39e2fb6be6) | Oct 27, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [bdf8012e05](https://linux-hardware.org/?probe=bdf8012e05) | Oct 27, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [67b966e75c](https://linux-hardware.org/?probe=67b966e75c) | Oct 27, 2023 |
| Google        | Enguarde                    | [074b44ce16](https://linux-hardware.org/?probe=074b44ce16) | Oct 26, 2023 |
| Acer          | Aspire 5750G                | [afe742ceca](https://linux-hardware.org/?probe=afe742ceca) | Oct 26, 2023 |
| Dell          | Latitude 5414               | [78fb4f9907](https://linux-hardware.org/?probe=78fb4f9907) | Oct 26, 2023 |
| Medion        | Unknown                     | [ffcdfb3003](https://linux-hardware.org/?probe=ffcdfb3003) | Oct 26, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B4I... | [afce107e0d](https://linux-hardware.org/?probe=afce107e0d) | Oct 26, 2023 |
| HP            | ProBook 4530s               | [b86df6ad72](https://linux-hardware.org/?probe=b86df6ad72) | Oct 26, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [cc3370083d](https://linux-hardware.org/?probe=cc3370083d) | Oct 26, 2023 |
| Exo           | Smart Serie R               | [d68b300ca7](https://linux-hardware.org/?probe=d68b300ca7) | Oct 26, 2023 |
| Toshiba       | Satellite L455D             | [29337c2310](https://linux-hardware.org/?probe=29337c2310) | Oct 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [303c4197c7](https://linux-hardware.org/?probe=303c4197c7) | Oct 26, 2023 |
| HP            | Compaq 15                   | [83fab35dec](https://linux-hardware.org/?probe=83fab35dec) | Oct 26, 2023 |
| Dell          | Latitude 5414               | [692b53f9d9](https://linux-hardware.org/?probe=692b53f9d9) | Oct 26, 2023 |
| HP            | Compaq 15                   | [41ada9e77d](https://linux-hardware.org/?probe=41ada9e77d) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bd6ab7e486](https://linux-hardware.org/?probe=bd6ab7e486) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bfe12f37dc](https://linux-hardware.org/?probe=bfe12f37dc) | Oct 25, 2023 |
| HP            | 15                          | [629c50d53a](https://linux-hardware.org/?probe=629c50d53a) | Oct 25, 2023 |
| Acer          | Aspire 5750G                | [b726b22da1](https://linux-hardware.org/?probe=b726b22da1) | Oct 25, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [c66ebc8e70](https://linux-hardware.org/?probe=c66ebc8e70) | Oct 25, 2023 |
| Matsushita... | CF-30CTWAZBM                | [4211783dac](https://linux-hardware.org/?probe=4211783dac) | Oct 25, 2023 |
| Google        | Reks                        | [d397eae4e5](https://linux-hardware.org/?probe=d397eae4e5) | Oct 25, 2023 |
| Acer          | Aspire ES1-521              | [2df6fb3e2a](https://linux-hardware.org/?probe=2df6fb3e2a) | Oct 25, 2023 |
| MSI           | Katana GF76 11SC            | [b1a5449e72](https://linux-hardware.org/?probe=b1a5449e72) | Oct 25, 2023 |
| HP            | Victus by Gaming Laptop ... | [71a22f4706](https://linux-hardware.org/?probe=71a22f4706) | Oct 25, 2023 |
| HP            | Laptop 15-dw3xxx            | [8994962017](https://linux-hardware.org/?probe=8994962017) | Oct 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | [b270ca3670](https://linux-hardware.org/?probe=b270ca3670) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [1406d2f4d5](https://linux-hardware.org/?probe=1406d2f4d5) | Oct 24, 2023 |
| Medion        | Unknown                     | [fa168b5e75](https://linux-hardware.org/?probe=fa168b5e75) | Oct 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [56fa067caa](https://linux-hardware.org/?probe=56fa067caa) | Oct 24, 2023 |
| HP            | EliteBook 8740w             | [3669a01d21](https://linux-hardware.org/?probe=3669a01d21) | Oct 24, 2023 |
| Notebook      | P7xxDM(-G)                  | [bb211b2fb4](https://linux-hardware.org/?probe=bb211b2fb4) | Oct 24, 2023 |
| HP            | EliteBook 820 G1            | [0fb2b25961](https://linux-hardware.org/?probe=0fb2b25961) | Oct 24, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [dd704a643f](https://linux-hardware.org/?probe=dd704a643f) | Oct 24, 2023 |
| Acer          | Aspire 7750G                | [91006bdfa7](https://linux-hardware.org/?probe=91006bdfa7) | Oct 24, 2023 |
| Alienware     | m15 R6                      | [c6711f7b02](https://linux-hardware.org/?probe=c6711f7b02) | Oct 24, 2023 |
| ASUSTek       | G551JX                      | [db16c87fe8](https://linux-hardware.org/?probe=db16c87fe8) | Oct 24, 2023 |
| MSI           | GT62VR 6RD                  | [0d10c5251c](https://linux-hardware.org/?probe=0d10c5251c) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8754714bce](https://linux-hardware.org/?probe=8754714bce) | Oct 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [f4375f7115](https://linux-hardware.org/?probe=f4375f7115) | Oct 23, 2023 |
| Aquarius      | NS585                       | [3c793ad14b](https://linux-hardware.org/?probe=3c793ad14b) | Oct 23, 2023 |
| Aquarius      | NS585                       | [9e7366fb3a](https://linux-hardware.org/?probe=9e7366fb3a) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [c03a4ad29d](https://linux-hardware.org/?probe=c03a4ad29d) | Oct 23, 2023 |
| Timi          | Mi NoteBook Pro             | [470eb40837](https://linux-hardware.org/?probe=470eb40837) | Oct 23, 2023 |
| Acer          | Aspire E5-573               | [d83f4bf9ad](https://linux-hardware.org/?probe=d83f4bf9ad) | Oct 23, 2023 |
| HP            | Laptop 14s-dy5xxx           | [e873e5d24c](https://linux-hardware.org/?probe=e873e5d24c) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | [4d383aebdc](https://linux-hardware.org/?probe=4d383aebdc) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | [4cb151fdfe](https://linux-hardware.org/?probe=4cb151fdfe) | Oct 23, 2023 |
| Dell          | XPS 13 9300                 | [9d7ecc567c](https://linux-hardware.org/?probe=9d7ecc567c) | Oct 23, 2023 |
| Dell          | Precision 3571              | [a2ba806246](https://linux-hardware.org/?probe=a2ba806246) | Oct 22, 2023 |
| Dell          | Precision 3571              | [efedaee27d](https://linux-hardware.org/?probe=efedaee27d) | Oct 22, 2023 |
| Dell          | Inspiron 6000               | [be4108e195](https://linux-hardware.org/?probe=be4108e195) | Oct 22, 2023 |
| Dell          | XPS 15 9560                 | [c2c4d81d07](https://linux-hardware.org/?probe=c2c4d81d07) | Oct 22, 2023 |
| GPU Compan... | GWTC51427                   | [69b6cd7a6f](https://linux-hardware.org/?probe=69b6cd7a6f) | Oct 22, 2023 |
| Dell          | Vostro 14-3468              | [c9c6a8db9f](https://linux-hardware.org/?probe=c9c6a8db9f) | Oct 22, 2023 |
| Acer          | Swift SF314-42              | [e19b58f8be](https://linux-hardware.org/?probe=e19b58f8be) | Oct 21, 2023 |
| Lenovo        | V130-15IGM 81HL             | [fc8d54a39c](https://linux-hardware.org/?probe=fc8d54a39c) | Oct 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [5e57624ceb](https://linux-hardware.org/?probe=5e57624ceb) | Oct 21, 2023 |
| Packard Be... | EasyNote TE11HC             | [dc33bae348](https://linux-hardware.org/?probe=dc33bae348) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [f30ccc13f5](https://linux-hardware.org/?probe=f30ccc13f5) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d9a8c7946e](https://linux-hardware.org/?probe=d9a8c7946e) | Oct 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [5cac857cd9](https://linux-hardware.org/?probe=5cac857cd9) | Oct 20, 2023 |
| Lenovo        | V15-IIL 82C5                | [50f6d4cb01](https://linux-hardware.org/?probe=50f6d4cb01) | Oct 20, 2023 |
| MSI           | Alpha 17 B5EEK              | [125e76df80](https://linux-hardware.org/?probe=125e76df80) | Oct 20, 2023 |
| MSI           | Alpha 17 B5EEK              | [3a5c553fcb](https://linux-hardware.org/?probe=3a5c553fcb) | Oct 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [2147efec4e](https://linux-hardware.org/?probe=2147efec4e) | Oct 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [f35c9d006e](https://linux-hardware.org/?probe=f35c9d006e) | Oct 20, 2023 |
| Lenovo        | ThinkPad T470 20HES4VB00    | [423a16c64a](https://linux-hardware.org/?probe=423a16c64a) | Oct 20, 2023 |
| Dell          | G5 5505                     | [363d3c6d9c](https://linux-hardware.org/?probe=363d3c6d9c) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [64929e25f7](https://linux-hardware.org/?probe=64929e25f7) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [da8f06a8e0](https://linux-hardware.org/?probe=da8f06a8e0) | Oct 19, 2023 |
| Acer          | Aspire A315-34              | [1ec00092e6](https://linux-hardware.org/?probe=1ec00092e6) | Oct 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9c9781a7ee](https://linux-hardware.org/?probe=9c9781a7ee) | Oct 19, 2023 |
| Dell          | XPS 13 9380                 | [a108313537](https://linux-hardware.org/?probe=a108313537) | Oct 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a8e2b482f4](https://linux-hardware.org/?probe=a8e2b482f4) | Oct 19, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [81bfadb2d9](https://linux-hardware.org/?probe=81bfadb2d9) | Oct 18, 2023 |
| Dell          | Precision 7560              | [847d5dfd06](https://linux-hardware.org/?probe=847d5dfd06) | Oct 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [8762d7b263](https://linux-hardware.org/?probe=8762d7b263) | Oct 18, 2023 |
| Acer          | Aspire 5920G                | [5921ebc3f7](https://linux-hardware.org/?probe=5921ebc3f7) | Oct 18, 2023 |
| Acer          | Aspire 5920G                | [b6619c64fd](https://linux-hardware.org/?probe=b6619c64fd) | Oct 18, 2023 |
| Dell          | Latitude E6420              | [f703c6bd74](https://linux-hardware.org/?probe=f703c6bd74) | Oct 17, 2023 |
| Dell          | Latitude E6430              | [54d411b12d](https://linux-hardware.org/?probe=54d411b12d) | Oct 17, 2023 |
| Google        | Reks                        | [1053eb8fee](https://linux-hardware.org/?probe=1053eb8fee) | Oct 17, 2023 |
| Google        | Reks                        | [84b42b74a0](https://linux-hardware.org/?probe=84b42b74a0) | Oct 17, 2023 |
| HP            | ProBook 645 G1              | [d1eeca057f](https://linux-hardware.org/?probe=d1eeca057f) | Oct 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [f9a0ba2cba](https://linux-hardware.org/?probe=f9a0ba2cba) | Oct 17, 2023 |
| Unknown       | Unknown                     | [f776cdb186](https://linux-hardware.org/?probe=f776cdb186) | Oct 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [902d95cec2](https://linux-hardware.org/?probe=902d95cec2) | Oct 17, 2023 |
| HP            | EliteBook 820 G2            | [14f5dbdc5a](https://linux-hardware.org/?probe=14f5dbdc5a) | Oct 17, 2023 |
| Acer          | Aspire V3-771               | [e56b3d3602](https://linux-hardware.org/?probe=e56b3d3602) | Oct 17, 2023 |
| Acer          | Aspire 7750G                | [6c7f890049](https://linux-hardware.org/?probe=6c7f890049) | Oct 17, 2023 |
| Acer          | Aspire A515-54              | [a89d6c8f24](https://linux-hardware.org/?probe=a89d6c8f24) | Oct 17, 2023 |
| Dell          | Precision 7560              | [5d9dd29a22](https://linux-hardware.org/?probe=5d9dd29a22) | Oct 17, 2023 |
| Juana Mans... | SF20GM7                     | [ea7e37eb5d](https://linux-hardware.org/?probe=ea7e37eb5d) | Oct 17, 2023 |
| Google        | Reks                        | [7610580a91](https://linux-hardware.org/?probe=7610580a91) | Oct 16, 2023 |
| HP            | Laptop 15-fd0xxx            | [0e6cc9fc48](https://linux-hardware.org/?probe=0e6cc9fc48) | Oct 16, 2023 |
| Acer          | Aspire 7750G                | [2a2d5e2425](https://linux-hardware.org/?probe=2a2d5e2425) | Oct 16, 2023 |
| ASUSTek       | 1015PN                      | [b6cbd56a75](https://linux-hardware.org/?probe=b6cbd56a75) | Oct 16, 2023 |
| Apple         | MacBookPro8,1               | [abfce57204](https://linux-hardware.org/?probe=abfce57204) | Oct 16, 2023 |
| Lenovo        | ThinkPad E565 20EY000XUK    | [b7cf6113c4](https://linux-hardware.org/?probe=b7cf6113c4) | Oct 16, 2023 |
| HUAWEI        | HVY-WXX9                    | [57e0cf4149](https://linux-hardware.org/?probe=57e0cf4149) | Oct 16, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [2408be3605](https://linux-hardware.org/?probe=2408be3605) | Oct 16, 2023 |
| Dell          | Inspiron 5567               | [d632a645e1](https://linux-hardware.org/?probe=d632a645e1) | Oct 16, 2023 |
| MSI           | GF63 Thin 11SC              | [1072e8d802](https://linux-hardware.org/?probe=1072e8d802) | Oct 16, 2023 |
| HP            | 250 G8 Notebook PC          | [38c84587d8](https://linux-hardware.org/?probe=38c84587d8) | Oct 16, 2023 |
| Apple         | MacBookAir4,1               | [f63091b76b](https://linux-hardware.org/?probe=f63091b76b) | Oct 16, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | [33ce923fc9](https://linux-hardware.org/?probe=33ce923fc9) | Oct 15, 2023 |
| Apple         | MacBookPro6,2               | [1df7e29365](https://linux-hardware.org/?probe=1df7e29365) | Oct 15, 2023 |
| HP            | 15                          | [7cde663ae0](https://linux-hardware.org/?probe=7cde663ae0) | Oct 15, 2023 |
| Lenovo        | G50-70 20351                | [bdd8aeaf43](https://linux-hardware.org/?probe=bdd8aeaf43) | Oct 14, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [50ebc1407b](https://linux-hardware.org/?probe=50ebc1407b) | Oct 14, 2023 |
| HUAWEI        | KLVD-WXX9                   | [9d77b16e0b](https://linux-hardware.org/?probe=9d77b16e0b) | Oct 14, 2023 |
| Dell          | Inspiron 3501               | [a1ada382fa](https://linux-hardware.org/?probe=a1ada382fa) | Oct 14, 2023 |
| Dell          | Latitude 5400               | [26c8a94f7f](https://linux-hardware.org/?probe=26c8a94f7f) | Oct 14, 2023 |
| Fujitsu       | LIFEBOOK T5010              | [f35263745a](https://linux-hardware.org/?probe=f35263745a) | Oct 14, 2023 |
| Dell          | Latitude 5414               | [2984ae5140](https://linux-hardware.org/?probe=2984ae5140) | Oct 14, 2023 |
| Google        | Reks                        | [066e8305fe](https://linux-hardware.org/?probe=066e8305fe) | Oct 13, 2023 |
| Google        | Reks                        | [acb8eb7f44](https://linux-hardware.org/?probe=acb8eb7f44) | Oct 13, 2023 |
| Google        | Reks                        | [707eb71f31](https://linux-hardware.org/?probe=707eb71f31) | Oct 13, 2023 |
| Lenovo        | ThinkPad E550 20DF00F0GE    | [61c5a7e37a](https://linux-hardware.org/?probe=61c5a7e37a) | Oct 13, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [94e6d9d3cb](https://linux-hardware.org/?probe=94e6d9d3cb) | Oct 13, 2023 |
| Google        | Reks                        | [4bc10c8b6b](https://linux-hardware.org/?probe=4bc10c8b6b) | Oct 13, 2023 |
| Lenovo        | V17 G4 IRU 83A2             | [5298e96c35](https://linux-hardware.org/?probe=5298e96c35) | Oct 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7ee4351584](https://linux-hardware.org/?probe=7ee4351584) | Oct 13, 2023 |
| Apple         | MacBookPro9,2               | [27b7cf72ac](https://linux-hardware.org/?probe=27b7cf72ac) | Oct 13, 2023 |
| Dell          | Latitude E6520              | [30a511af92](https://linux-hardware.org/?probe=30a511af92) | Oct 13, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [02c3723dae](https://linux-hardware.org/?probe=02c3723dae) | Oct 12, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [d874291459](https://linux-hardware.org/?probe=d874291459) | Oct 12, 2023 |
| Toshiba       | Satellite L755              | [679e27a869](https://linux-hardware.org/?probe=679e27a869) | Oct 12, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b53da36041](https://linux-hardware.org/?probe=b53da36041) | Oct 12, 2023 |
| Google        | Reks                        | [20f8a11067](https://linux-hardware.org/?probe=20f8a11067) | Oct 12, 2023 |
| Google        | Reks                        | [4e35f7ebe4](https://linux-hardware.org/?probe=4e35f7ebe4) | Oct 12, 2023 |
| Google        | Reks                        | [41c6c948bb](https://linux-hardware.org/?probe=41c6c948bb) | Oct 12, 2023 |
| ASUSTek       | X541UJ                      | [c061e67481](https://linux-hardware.org/?probe=c061e67481) | Oct 12, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [24adbfd09a](https://linux-hardware.org/?probe=24adbfd09a) | Oct 11, 2023 |
| Google        | Reks                        | [1854f5e2fb](https://linux-hardware.org/?probe=1854f5e2fb) | Oct 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [9de2f282f8](https://linux-hardware.org/?probe=9de2f282f8) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [dc4ce65d14](https://linux-hardware.org/?probe=dc4ce65d14) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [c26fe51dd5](https://linux-hardware.org/?probe=c26fe51dd5) | Oct 11, 2023 |
| Google        | Reks                        | [f9857342ec](https://linux-hardware.org/?probe=f9857342ec) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [4a0728b60c](https://linux-hardware.org/?probe=4a0728b60c) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [63c9bedd9d](https://linux-hardware.org/?probe=63c9bedd9d) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [77fe4b27cf](https://linux-hardware.org/?probe=77fe4b27cf) | Oct 11, 2023 |
| Google        | Reks                        | [9b2d9c0f7c](https://linux-hardware.org/?probe=9b2d9c0f7c) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [a735df7685](https://linux-hardware.org/?probe=a735df7685) | Oct 11, 2023 |
| Google        | Reks                        | [e78d454248](https://linux-hardware.org/?probe=e78d454248) | Oct 11, 2023 |
| Google        | Reks                        | [e7c6590991](https://linux-hardware.org/?probe=e7c6590991) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [627ce99f24](https://linux-hardware.org/?probe=627ce99f24) | Oct 11, 2023 |
| Google        | Reks                        | [cc53305ade](https://linux-hardware.org/?probe=cc53305ade) | Oct 11, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [d957b0375b](https://linux-hardware.org/?probe=d957b0375b) | Oct 11, 2023 |
| Google        | Reks                        | [286fdb3692](https://linux-hardware.org/?probe=286fdb3692) | Oct 11, 2023 |
| ASUSTek       | X541UJ                      | [0cb7dbb73b](https://linux-hardware.org/?probe=0cb7dbb73b) | Oct 11, 2023 |
| HP            | Laptop 15-fc0xxx            | [670b2194c0](https://linux-hardware.org/?probe=670b2194c0) | Oct 11, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [cf3225396c](https://linux-hardware.org/?probe=cf3225396c) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | [f53b6f5e53](https://linux-hardware.org/?probe=f53b6f5e53) | Oct 11, 2023 |
| Prestigio     | Visconte Quad 3GK           | [5ffdb7e479](https://linux-hardware.org/?probe=5ffdb7e479) | Oct 11, 2023 |
| Google        | Reks                        | [4bd21164ba](https://linux-hardware.org/?probe=4bd21164ba) | Oct 10, 2023 |
| Google        | Reks                        | [e574b981ae](https://linux-hardware.org/?probe=e574b981ae) | Oct 10, 2023 |
| Google        | Reks                        | [5d44d0021b](https://linux-hardware.org/?probe=5d44d0021b) | Oct 10, 2023 |
| Google        | Reks                        | [a4300f1369](https://linux-hardware.org/?probe=a4300f1369) | Oct 10, 2023 |
| HP            | 15                          | [5dc6c32647](https://linux-hardware.org/?probe=5dc6c32647) | Oct 10, 2023 |
| Google        | Reks                        | [9b338e1cfb](https://linux-hardware.org/?probe=9b338e1cfb) | Oct 10, 2023 |
| Google        | Reks                        | [8c2146eff1](https://linux-hardware.org/?probe=8c2146eff1) | Oct 10, 2023 |
| Google        | Reks                        | [2d878f9b40](https://linux-hardware.org/?probe=2d878f9b40) | Oct 10, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [8ca2bf7fc9](https://linux-hardware.org/?probe=8ca2bf7fc9) | Oct 10, 2023 |
| Google        | Reks                        | [b206e1538b](https://linux-hardware.org/?probe=b206e1538b) | Oct 10, 2023 |
| Google        | Reks                        | [3cf1a391be](https://linux-hardware.org/?probe=3cf1a391be) | Oct 10, 2023 |
| Google        | Reks                        | [d694213be1](https://linux-hardware.org/?probe=d694213be1) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [f91905858e](https://linux-hardware.org/?probe=f91905858e) | Oct 10, 2023 |
| HUAWEI        | KLVL-WXXW                   | [3f6528d99d](https://linux-hardware.org/?probe=3f6528d99d) | Oct 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c1c56db09e](https://linux-hardware.org/?probe=c1c56db09e) | Oct 10, 2023 |
| Dell          | XPS 15 9570                 | [a40dbac784](https://linux-hardware.org/?probe=a40dbac784) | Oct 09, 2023 |
| ASUSTek       | N751JK                      | [855d2e95a7](https://linux-hardware.org/?probe=855d2e95a7) | Oct 09, 2023 |
| Dell          | XPS 15 9570                 | [d6aaf4c55d](https://linux-hardware.org/?probe=d6aaf4c55d) | Oct 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f95efe1e80](https://linux-hardware.org/?probe=f95efe1e80) | Oct 09, 2023 |
| Toshiba       | Satellite L755              | [74a043fcf5](https://linux-hardware.org/?probe=74a043fcf5) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [b3635689de](https://linux-hardware.org/?probe=b3635689de) | Oct 09, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [825a1ee4bb](https://linux-hardware.org/?probe=825a1ee4bb) | Oct 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6d2a6c2a6f](https://linux-hardware.org/?probe=6d2a6c2a6f) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3c54fe835e](https://linux-hardware.org/?probe=3c54fe835e) | Oct 09, 2023 |
| MSI           | Katana GF66 11UG            | [0816e0912b](https://linux-hardware.org/?probe=0816e0912b) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a41b75e081](https://linux-hardware.org/?probe=a41b75e081) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [ac6149e371](https://linux-hardware.org/?probe=ac6149e371) | Oct 08, 2023 |
| TUXEDO        | InfinityBook S 14 v5        | [7ad7f14fea](https://linux-hardware.org/?probe=7ad7f14fea) | Oct 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [e6ba7d9115](https://linux-hardware.org/?probe=e6ba7d9115) | Oct 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [91f26dd2c7](https://linux-hardware.org/?probe=91f26dd2c7) | Oct 08, 2023 |
| Acer          | Swift SF314-56G             | [2696a8d9c0](https://linux-hardware.org/?probe=2696a8d9c0) | Oct 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [8678e7aace](https://linux-hardware.org/?probe=8678e7aace) | Oct 08, 2023 |
| AXDIA Inte... | MYBOOK PRO 14 SE            | [344ed10ccd](https://linux-hardware.org/?probe=344ed10ccd) | Oct 07, 2023 |
| Lenovo        | Legion Y920-17IKB Laptop... | [881454bd02](https://linux-hardware.org/?probe=881454bd02) | Oct 07, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [a830045a2a](https://linux-hardware.org/?probe=a830045a2a) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | [cae6954f11](https://linux-hardware.org/?probe=cae6954f11) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S2LK0J    | [ca68af85fb](https://linux-hardware.org/?probe=ca68af85fb) | Oct 07, 2023 |
| ASUSTek       | T100TAS                     | [f6a5a046b6](https://linux-hardware.org/?probe=f6a5a046b6) | Oct 07, 2023 |
| ASUSTek       | T100TAS                     | [c7e6160070](https://linux-hardware.org/?probe=c7e6160070) | Oct 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [71bc4e1d3f](https://linux-hardware.org/?probe=71bc4e1d3f) | Oct 07, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [45be4f4f29](https://linux-hardware.org/?probe=45be4f4f29) | Oct 07, 2023 |
| Dell          | Latitude E6520              | [fea9ed801a](https://linux-hardware.org/?probe=fea9ed801a) | Oct 07, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [37eeaf5771](https://linux-hardware.org/?probe=37eeaf5771) | Oct 06, 2023 |
| Toshiba       | Satellite L755              | [63ad812f2f](https://linux-hardware.org/?probe=63ad812f2f) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [275c59d0de](https://linux-hardware.org/?probe=275c59d0de) | Oct 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [76449d7977](https://linux-hardware.org/?probe=76449d7977) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [212dd29010](https://linux-hardware.org/?probe=212dd29010) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [5928c10f4a](https://linux-hardware.org/?probe=5928c10f4a) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [3bc146338b](https://linux-hardware.org/?probe=3bc146338b) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [82b7f17c90](https://linux-hardware.org/?probe=82b7f17c90) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [5f740996ed](https://linux-hardware.org/?probe=5f740996ed) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [64ffddf53c](https://linux-hardware.org/?probe=64ffddf53c) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [26bb748122](https://linux-hardware.org/?probe=26bb748122) | Oct 06, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [a9fb0ad7d5](https://linux-hardware.org/?probe=a9fb0ad7d5) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [5f9cd4dfbe](https://linux-hardware.org/?probe=5f9cd4dfbe) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [7f948138a8](https://linux-hardware.org/?probe=7f948138a8) | Oct 06, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [9b11272e7a](https://linux-hardware.org/?probe=9b11272e7a) | Oct 06, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [aaa295fa26](https://linux-hardware.org/?probe=aaa295fa26) | Oct 06, 2023 |
| Dell          | Latitude 7275               | [f1892c721d](https://linux-hardware.org/?probe=f1892c721d) | Oct 06, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [1c741fc115](https://linux-hardware.org/?probe=1c741fc115) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [50fc69b25f](https://linux-hardware.org/?probe=50fc69b25f) | Oct 06, 2023 |
| Toshiba       | Satellite A205              | [7b78b2ea5b](https://linux-hardware.org/?probe=7b78b2ea5b) | Oct 06, 2023 |
| HP            | ZBook 14 G2                 | [e1b3f48f3c](https://linux-hardware.org/?probe=e1b3f48f3c) | Oct 05, 2023 |
| Exo           | Smart Serie L               | [812041d985](https://linux-hardware.org/?probe=812041d985) | Oct 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [fc37084670](https://linux-hardware.org/?probe=fc37084670) | Oct 05, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [763ef47e79](https://linux-hardware.org/?probe=763ef47e79) | Oct 05, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [1edb630be1](https://linux-hardware.org/?probe=1edb630be1) | Oct 05, 2023 |
| Dell          | Vostro 3490                 | [83f825d43e](https://linux-hardware.org/?probe=83f825d43e) | Oct 05, 2023 |
| Dell          | Latitude 7290               | [8822662fb7](https://linux-hardware.org/?probe=8822662fb7) | Oct 05, 2023 |
| Acer          | Aspire V5-531               | [555d578f86](https://linux-hardware.org/?probe=555d578f86) | Oct 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [8ba8fa3184](https://linux-hardware.org/?probe=8ba8fa3184) | Oct 05, 2023 |
| Acer          | Aspire A317-54              | [12732988d1](https://linux-hardware.org/?probe=12732988d1) | Oct 05, 2023 |
| HP            | EliteBook 735 G6            | [94ac6e4439](https://linux-hardware.org/?probe=94ac6e4439) | Oct 04, 2023 |
| Philco Inf... | EC10IS2                     | [f85315b46a](https://linux-hardware.org/?probe=f85315b46a) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [258d726766](https://linux-hardware.org/?probe=258d726766) | Oct 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [bf9ddbe725](https://linux-hardware.org/?probe=bf9ddbe725) | Oct 04, 2023 |
| Lenovo        | ThinkPad P51 20HJS0RE02     | [892c35359f](https://linux-hardware.org/?probe=892c35359f) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [03949619e9](https://linux-hardware.org/?probe=03949619e9) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [627e882ad2](https://linux-hardware.org/?probe=627e882ad2) | Oct 04, 2023 |
| HP            | ZBook 17 G4                 | [ead2e4611e](https://linux-hardware.org/?probe=ead2e4611e) | Oct 04, 2023 |
| Acer          | Swift SF314-43              | [36d6c2e275](https://linux-hardware.org/?probe=36d6c2e275) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [82820de211](https://linux-hardware.org/?probe=82820de211) | Oct 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [db7fa034a7](https://linux-hardware.org/?probe=db7fa034a7) | Oct 03, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [e80a668fc3](https://linux-hardware.org/?probe=e80a668fc3) | Oct 03, 2023 |
| Acer          | Aspire V5-531               | [b6a9eaaec5](https://linux-hardware.org/?probe=b6a9eaaec5) | Oct 03, 2023 |
| Unknown       | Unknown                     | [a6849f7516](https://linux-hardware.org/?probe=a6849f7516) | Oct 03, 2023 |
| Notebook      | W65_67SJ                    | [4de813ee21](https://linux-hardware.org/?probe=4de813ee21) | Oct 03, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [48ee75db0b](https://linux-hardware.org/?probe=48ee75db0b) | Oct 03, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [9c6c3cf92b](https://linux-hardware.org/?probe=9c6c3cf92b) | Oct 03, 2023 |
| Toshiba       | Satellite P75-A             | [10da36f2b7](https://linux-hardware.org/?probe=10da36f2b7) | Oct 03, 2023 |
| Lenovo        | ThinkPad E580 20KS003WUS    | [5aed5aaa9b](https://linux-hardware.org/?probe=5aed5aaa9b) | Oct 03, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | [fc95f3feef](https://linux-hardware.org/?probe=fc95f3feef) | Oct 03, 2023 |
| Lenovo        | ThinkPad T450 20BUA007SG    | [85af04a1cc](https://linux-hardware.org/?probe=85af04a1cc) | Oct 03, 2023 |
| Acer          | TravelMate P414-51          | [520fe0b494](https://linux-hardware.org/?probe=520fe0b494) | Oct 03, 2023 |
| Acer          | Swift SF314-56G             | [15b613a264](https://linux-hardware.org/?probe=15b613a264) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [3a8b2b229a](https://linux-hardware.org/?probe=3a8b2b229a) | Oct 03, 2023 |
| Dell          | Wyse 5470                   | [301b504179](https://linux-hardware.org/?probe=301b504179) | Oct 03, 2023 |
| Google        | Reks                        | [00fe240f8b](https://linux-hardware.org/?probe=00fe240f8b) | Oct 02, 2023 |
| Google        | Reks                        | [c4dc39039e](https://linux-hardware.org/?probe=c4dc39039e) | Oct 02, 2023 |
| Google        | Reks                        | [0d9a805f5a](https://linux-hardware.org/?probe=0d9a805f5a) | Oct 02, 2023 |
| Google        | Reks                        | [22c6ac7ba8](https://linux-hardware.org/?probe=22c6ac7ba8) | Oct 02, 2023 |
| Google        | Reks                        | [0db25d0a2f](https://linux-hardware.org/?probe=0db25d0a2f) | Oct 02, 2023 |
| Dell          | Vostro 3500                 | [8624a6479e](https://linux-hardware.org/?probe=8624a6479e) | Oct 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [9637400928](https://linux-hardware.org/?probe=9637400928) | Oct 02, 2023 |
| Compaq        | 420                         | [b327579e60](https://linux-hardware.org/?probe=b327579e60) | Oct 02, 2023 |
| VALE          | Notebook Classic C140       | [0516711124](https://linux-hardware.org/?probe=0516711124) | Oct 02, 2023 |
| Google        | Treeya                      | [b2251358a1](https://linux-hardware.org/?probe=b2251358a1) | Oct 02, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [cc181da4e1](https://linux-hardware.org/?probe=cc181da4e1) | Oct 02, 2023 |
| MSI           | GF63 Thin 9SC               | [3670f5ea70](https://linux-hardware.org/?probe=3670f5ea70) | Oct 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a3773ae099](https://linux-hardware.org/?probe=a3773ae099) | Oct 02, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [f35e389d78](https://linux-hardware.org/?probe=f35e389d78) | Oct 02, 2023 |
| IX1401        | Unknown                     | [8014a1028b](https://linux-hardware.org/?probe=8014a1028b) | Oct 02, 2023 |
| Dell          | Inspiron 5570               | [93e66c7d47](https://linux-hardware.org/?probe=93e66c7d47) | Oct 02, 2023 |
| Teclast       | F15Plus 2                   | [3779ac7003](https://linux-hardware.org/?probe=3779ac7003) | Oct 01, 2023 |
| HP            | Presario CQ57               | [e83f052dc8](https://linux-hardware.org/?probe=e83f052dc8) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480 20L6SA5Q2V    | [d9262b2225](https://linux-hardware.org/?probe=d9262b2225) | Oct 01, 2023 |
| HP            | Laptop 15-dw3xxx            | [6443df8957](https://linux-hardware.org/?probe=6443df8957) | Oct 01, 2023 |
| Acer          | Aspire E1-571               | [2e7aba6432](https://linux-hardware.org/?probe=2e7aba6432) | Oct 01, 2023 |
| Packard Be... | EasyNote LM98               | [8fdf8eee6c](https://linux-hardware.org/?probe=8fdf8eee6c) | Oct 01, 2023 |
| HP            | Laptop 14s-fq1xxx           | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| Acer          | AOA150                      | [969a729098](https://linux-hardware.org/?probe=969a729098) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | [d17d6d2b70](https://linux-hardware.org/?probe=d17d6d2b70) | Oct 01, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | [ed7bf5aee1](https://linux-hardware.org/?probe=ed7bf5aee1) | Oct 01, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [83d91ea2fe](https://linux-hardware.org/?probe=83d91ea2fe) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | [b2b359c659](https://linux-hardware.org/?probe=b2b359c659) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | [ccb9b4e795](https://linux-hardware.org/?probe=ccb9b4e795) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [e7dad368d2](https://linux-hardware.org/?probe=e7dad368d2) | Sep 30, 2023 |
| Dell          | Latitude 5410               | [8234abf02b](https://linux-hardware.org/?probe=8234abf02b) | Sep 30, 2023 |
| Lenovo        | ThinkPad X260 VB6R77903H    | [de3079ae33](https://linux-hardware.org/?probe=de3079ae33) | Sep 30, 2023 |
| IX1401        | Unknown                     | [c77c1d010e](https://linux-hardware.org/?probe=c77c1d010e) | Sep 30, 2023 |
| HP            | Pavilion dv5                | [0b1da8643f](https://linux-hardware.org/?probe=0b1da8643f) | Sep 30, 2023 |
| Alienware     | m15 R4                      | [a67899ed06](https://linux-hardware.org/?probe=a67899ed06) | Sep 30, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [703170e428](https://linux-hardware.org/?probe=703170e428) | Sep 30, 2023 |
| HP            | Notebook                    | [193ec8deb3](https://linux-hardware.org/?probe=193ec8deb3) | Sep 30, 2023 |
| HP            | ProBook 450 G1              | [1cbae5b56a](https://linux-hardware.org/?probe=1cbae5b56a) | Sep 29, 2023 |
| HP            | Pavilion dv9000 (GA359UA... | [cea70d5f75](https://linux-hardware.org/?probe=cea70d5f75) | Sep 29, 2023 |
| Dell          | Latitude 5410               | [61ddf0adf6](https://linux-hardware.org/?probe=61ddf0adf6) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | [0e12b69b96](https://linux-hardware.org/?probe=0e12b69b96) | Sep 29, 2023 |
| Lenovo        | ThinkPad T500 22439AG       | [e5a2cd9816](https://linux-hardware.org/?probe=e5a2cd9816) | Sep 29, 2023 |
| Lenovo        | ThinkPad E490 20N8000SRT    | [274b3b5210](https://linux-hardware.org/?probe=274b3b5210) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | [1fcc841148](https://linux-hardware.org/?probe=1fcc841148) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | [c25eeffab1](https://linux-hardware.org/?probe=c25eeffab1) | Sep 28, 2023 |
| Acer          | Acadia V1.35                | [c2074b2535](https://linux-hardware.org/?probe=c2074b2535) | Sep 28, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [3cb2bdba37](https://linux-hardware.org/?probe=3cb2bdba37) | Sep 27, 2023 |
| EUROCOM       | RACER 2.0                   | [4351733d37](https://linux-hardware.org/?probe=4351733d37) | Sep 27, 2023 |
| HP            | ElitePad 1000 G2            | [2668770971](https://linux-hardware.org/?probe=2668770971) | Sep 27, 2023 |
| Fujitsu       | LIFEBOOK E4512              | [08b39b38bd](https://linux-hardware.org/?probe=08b39b38bd) | Sep 27, 2023 |
| ASUSTek       | K50IJ                       | [8556633dad](https://linux-hardware.org/?probe=8556633dad) | Sep 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [1317c1f1a9](https://linux-hardware.org/?probe=1317c1f1a9) | Sep 27, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [1a472d3072](https://linux-hardware.org/?probe=1a472d3072) | Sep 27, 2023 |
| Dell          | Latitude E6530              | [40cdcd2545](https://linux-hardware.org/?probe=40cdcd2545) | Sep 27, 2023 |
| Acer          | Aspire 5951G                | [cae145acab](https://linux-hardware.org/?probe=cae145acab) | Sep 26, 2023 |
| Dell          | Vostro 14-3468              | [3fceb34932](https://linux-hardware.org/?probe=3fceb34932) | Sep 26, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [d406193722](https://linux-hardware.org/?probe=d406193722) | Sep 26, 2023 |
| Dell          | Vostro 14-3468              | [a027aae826](https://linux-hardware.org/?probe=a027aae826) | Sep 26, 2023 |
| Dell          | XPS 9315                    | [6fa1beb451](https://linux-hardware.org/?probe=6fa1beb451) | Sep 26, 2023 |
| Lenovo        | ThinkPad T420 4236EV9       | [d621ecd81f](https://linux-hardware.org/?probe=d621ecd81f) | Sep 26, 2023 |
| Lenovo        | ThinkPad L540 20AUS00N00    | [a8aee3f386](https://linux-hardware.org/?probe=a8aee3f386) | Sep 26, 2023 |
| Aquarius      | NS585                       | [ce1c1d6e56](https://linux-hardware.org/?probe=ce1c1d6e56) | Sep 26, 2023 |
| Acer          | Aspire A515-47              | [3c1e418bf0](https://linux-hardware.org/?probe=3c1e418bf0) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [9e9ff26362](https://linux-hardware.org/?probe=9e9ff26362) | Sep 26, 2023 |
| Acer          | Aspire A515-56              | [b047457fd1](https://linux-hardware.org/?probe=b047457fd1) | Sep 25, 2023 |
| Dell          | XPS 15 9560                 | [a524453c71](https://linux-hardware.org/?probe=a524453c71) | Sep 25, 2023 |
| Lenovo        | G710 20252                  | [d7926809d7](https://linux-hardware.org/?probe=d7926809d7) | Sep 25, 2023 |
| HP            | Presario CQ43               | [c206dc84ad](https://linux-hardware.org/?probe=c206dc84ad) | Sep 25, 2023 |
| Aquarius      | NS585                       | [e901467e39](https://linux-hardware.org/?probe=e901467e39) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [ab332c2dcb](https://linux-hardware.org/?probe=ab332c2dcb) | Sep 25, 2023 |
| Acer          | Aspire 5951G                | [4c50b8e9b0](https://linux-hardware.org/?probe=4c50b8e9b0) | Sep 25, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0CN0... | [9c0b702e21](https://linux-hardware.org/?probe=9c0b702e21) | Sep 24, 2023 |
| Dell          | XPS 15 9500                 | [fcff405070](https://linux-hardware.org/?probe=fcff405070) | Sep 24, 2023 |
| Dell          | XPS 15 9500                 | [5bedca0fe9](https://linux-hardware.org/?probe=5bedca0fe9) | Sep 24, 2023 |
| Valve         | Jupiter                     | [36fd2d4d96](https://linux-hardware.org/?probe=36fd2d4d96) | Sep 24, 2023 |
| Dell          | Latitude 5420               | [0e22f551b9](https://linux-hardware.org/?probe=0e22f551b9) | Sep 24, 2023 |
| HP            | 250 G8 Notebook PC          | [6b3c3ce703](https://linux-hardware.org/?probe=6b3c3ce703) | Sep 23, 2023 |
| HP            | 250 G4                      | [c9dac1b4d5](https://linux-hardware.org/?probe=c9dac1b4d5) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [42309ddc8c](https://linux-hardware.org/?probe=42309ddc8c) | Sep 23, 2023 |
| HP            | 250 G8 Notebook PC          | [e2dd7767f0](https://linux-hardware.org/?probe=e2dd7767f0) | Sep 23, 2023 |
| Dell          | Vostro 14-3468              | [0b6bdbbecb](https://linux-hardware.org/?probe=0b6bdbbecb) | Sep 23, 2023 |
| HP            | Compaq Presario CQ60        | [ae8071638f](https://linux-hardware.org/?probe=ae8071638f) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eb276947f2](https://linux-hardware.org/?probe=eb276947f2) | Sep 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [574c2193bb](https://linux-hardware.org/?probe=574c2193bb) | Sep 23, 2023 |
| Acer          | Nitro AN515-58              | [589716b973](https://linux-hardware.org/?probe=589716b973) | Sep 23, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B90... | [e273beb83a](https://linux-hardware.org/?probe=e273beb83a) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ad1b8126d2](https://linux-hardware.org/?probe=ad1b8126d2) | Sep 22, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B90... | [0d786ffd74](https://linux-hardware.org/?probe=0d786ffd74) | Sep 22, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1e9774c53c](https://linux-hardware.org/?probe=1e9774c53c) | Sep 22, 2023 |
| Dell          | Latitude 3320               | [cf413808cb](https://linux-hardware.org/?probe=cf413808cb) | Sep 22, 2023 |
| Dell          | Latitude 3320               | [bd39ee30ac](https://linux-hardware.org/?probe=bd39ee30ac) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e75a2a8b71](https://linux-hardware.org/?probe=e75a2a8b71) | Sep 22, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [c14178c7fa](https://linux-hardware.org/?probe=c14178c7fa) | Sep 22, 2023 |
| Samsung       | R505                        | [8aef37cda9](https://linux-hardware.org/?probe=8aef37cda9) | Sep 22, 2023 |
| ASUSTek       | X555LJ                      | [2edb781d68](https://linux-hardware.org/?probe=2edb781d68) | Sep 22, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [4bf358cd4f](https://linux-hardware.org/?probe=4bf358cd4f) | Sep 22, 2023 |
| HP            | EliteBook 840 G3            | [b6379ef77c](https://linux-hardware.org/?probe=b6379ef77c) | Sep 22, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [ea491d194f](https://linux-hardware.org/?probe=ea491d194f) | Sep 21, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e33bb92eb6](https://linux-hardware.org/?probe=e33bb92eb6) | Sep 21, 2023 |
| Lenovo        | V14 G3 IAP 82TS             | [2528381c0e](https://linux-hardware.org/?probe=2528381c0e) | Sep 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [f9430fd075](https://linux-hardware.org/?probe=f9430fd075) | Sep 21, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e337cc85e5](https://linux-hardware.org/?probe=e337cc85e5) | Sep 20, 2023 |
| Acer          | Aspire E1-531               | [f0173f0458](https://linux-hardware.org/?probe=f0173f0458) | Sep 20, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [228d31bf59](https://linux-hardware.org/?probe=228d31bf59) | Sep 20, 2023 |
| Dell          | XPS 13 9300                 | [49bb68e979](https://linux-hardware.org/?probe=49bb68e979) | Sep 20, 2023 |
| HP            | ProBook 450 G1              | [4e5ae95013](https://linux-hardware.org/?probe=4e5ae95013) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [c34d9b9514](https://linux-hardware.org/?probe=c34d9b9514) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [7ec3567855](https://linux-hardware.org/?probe=7ec3567855) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [676dd13401](https://linux-hardware.org/?probe=676dd13401) | Sep 20, 2023 |
| Dell          | Precision 5560              | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5662d8f95c](https://linux-hardware.org/?probe=5662d8f95c) | Sep 20, 2023 |
| Dell          | Precision 7550              | [75394df91f](https://linux-hardware.org/?probe=75394df91f) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | [963330511d](https://linux-hardware.org/?probe=963330511d) | Sep 19, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a5f79b33f4](https://linux-hardware.org/?probe=a5f79b33f4) | Sep 19, 2023 |
| Notebook      | P7xxDM3(-G)                 | [b302c7b008](https://linux-hardware.org/?probe=b302c7b008) | Sep 19, 2023 |
| Lenovo        | ThinkPad X61s 7666Y2X       | [177e40808d](https://linux-hardware.org/?probe=177e40808d) | Sep 19, 2023 |
| Notebook      | P7xxDM3(-G)                 | [ec386099b2](https://linux-hardware.org/?probe=ec386099b2) | Sep 19, 2023 |
| HP            | Laptop 17-cp0xxx            | [05e3350e1f](https://linux-hardware.org/?probe=05e3350e1f) | Sep 19, 2023 |
| Dell          | XPS 13 9360                 | [149f246bd7](https://linux-hardware.org/?probe=149f246bd7) | Sep 19, 2023 |
| Acer          | Aspire A515-56              | [db16273e72](https://linux-hardware.org/?probe=db16273e72) | Sep 19, 2023 |
| Intel Clie... | LAPBC710                    | [af446fcb4d](https://linux-hardware.org/?probe=af446fcb4d) | Sep 19, 2023 |
| Intel Clie... | LAPBC710                    | [eae124fa61](https://linux-hardware.org/?probe=eae124fa61) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | [5f8df7dfcb](https://linux-hardware.org/?probe=5f8df7dfcb) | Sep 19, 2023 |
| Dell          | Latitude E6430              | [d83d7bbfa8](https://linux-hardware.org/?probe=d83d7bbfa8) | Sep 18, 2023 |
| HP            | 15                          | [b016d5ee79](https://linux-hardware.org/?probe=b016d5ee79) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | [410df263b8](https://linux-hardware.org/?probe=410df263b8) | Sep 18, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [ebfe5ca0b0](https://linux-hardware.org/?probe=ebfe5ca0b0) | Sep 18, 2023 |
| Acer          | Extensa 215-32              | [6879449933](https://linux-hardware.org/?probe=6879449933) | Sep 18, 2023 |
| Aquarius      | NS585                       | [6ac8bd5909](https://linux-hardware.org/?probe=6ac8bd5909) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | [e14140ad96](https://linux-hardware.org/?probe=e14140ad96) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [dda4d7a910](https://linux-hardware.org/?probe=dda4d7a910) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [ee2d142228](https://linux-hardware.org/?probe=ee2d142228) | Sep 18, 2023 |
| Acer          | TravelMate P446-MG          | [08d9d6868b](https://linux-hardware.org/?probe=08d9d6868b) | Sep 17, 2023 |
| Google        | Droid                       | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| HP            | Compaq Mini 311-1100        | [8bdfb6307c](https://linux-hardware.org/?probe=8bdfb6307c) | Sep 17, 2023 |
| HP            | Laptop 15-dw3xxx            | [f84a480b09](https://linux-hardware.org/?probe=f84a480b09) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cda370cdc3](https://linux-hardware.org/?probe=cda370cdc3) | Sep 16, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [b7c1a0a0a0](https://linux-hardware.org/?probe=b7c1a0a0a0) | Sep 16, 2023 |
| Apple         | MacBookPro8,1               | [c3791ba730](https://linux-hardware.org/?probe=c3791ba730) | Sep 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [f5884967d0](https://linux-hardware.org/?probe=f5884967d0) | Sep 16, 2023 |
| Dell          | Latitude E5570              | [fd5ba4aa5a](https://linux-hardware.org/?probe=fd5ba4aa5a) | Sep 15, 2023 |
| Dell          | Precision 5570              | [8b3c21b110](https://linux-hardware.org/?probe=8b3c21b110) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [66b29aeb1d](https://linux-hardware.org/?probe=66b29aeb1d) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [3eb787f2ec](https://linux-hardware.org/?probe=3eb787f2ec) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [eaa723190d](https://linux-hardware.org/?probe=eaa723190d) | Sep 15, 2023 |
| ASUSTek       | X507UB                      | [ca19710375](https://linux-hardware.org/?probe=ca19710375) | Sep 15, 2023 |
| ASUSTek       | X751LN                      | [77ecc965aa](https://linux-hardware.org/?probe=77ecc965aa) | Sep 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffb2a765f](https://linux-hardware.org/?probe=0ffb2a765f) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [a3e1ac295c](https://linux-hardware.org/?probe=a3e1ac295c) | Sep 14, 2023 |
| ASUSTek       | P553UJ                      | [3463413300](https://linux-hardware.org/?probe=3463413300) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [6f4c4a4120](https://linux-hardware.org/?probe=6f4c4a4120) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d27fa5404b](https://linux-hardware.org/?probe=d27fa5404b) | Sep 14, 2023 |
| Dell          | Latitude 5440               | [93a296a628](https://linux-hardware.org/?probe=93a296a628) | Sep 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [033eca4030](https://linux-hardware.org/?probe=033eca4030) | Sep 14, 2023 |
| HP            | 245 G7 Notebook PC          | [ab68dea087](https://linux-hardware.org/?probe=ab68dea087) | Sep 14, 2023 |
| HP            | ProBook 6570b               | [fc5c01d215](https://linux-hardware.org/?probe=fc5c01d215) | Sep 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0cdeaab8be](https://linux-hardware.org/?probe=0cdeaab8be) | Sep 13, 2023 |
| MSI           | GS66 Stealth 11UG           | [304abac74b](https://linux-hardware.org/?probe=304abac74b) | Sep 13, 2023 |
| HP            | Stream Notebook PC 11       | [f4c5ae4297](https://linux-hardware.org/?probe=f4c5ae4297) | Sep 13, 2023 |
| Acer          | AOA150                      | [bc32c4814d](https://linux-hardware.org/?probe=bc32c4814d) | Sep 13, 2023 |
| Lenovo        | ThinkPad X230 232036U       | [58ec12094c](https://linux-hardware.org/?probe=58ec12094c) | Sep 13, 2023 |
| Google        | Cave                        | [74c8e00b23](https://linux-hardware.org/?probe=74c8e00b23) | Sep 13, 2023 |
| Dell          | Latitude E6430              | [79cf77c6ba](https://linux-hardware.org/?probe=79cf77c6ba) | Sep 12, 2023 |
| Dell          | Latitude E7470              | [4f2094dfef](https://linux-hardware.org/?probe=4f2094dfef) | Sep 12, 2023 |
| Toshiba       | Satellite L640              | [ac5a264fea](https://linux-hardware.org/?probe=ac5a264fea) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [be2af85bb7](https://linux-hardware.org/?probe=be2af85bb7) | Sep 12, 2023 |
| SLIMBOOK      | Essential15L                | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [0224dfd46f](https://linux-hardware.org/?probe=0224dfd46f) | Sep 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [52b50b0d68](https://linux-hardware.org/?probe=52b50b0d68) | Sep 11, 2023 |
| Google        | Enguarde                    | [4fd827adc5](https://linux-hardware.org/?probe=4fd827adc5) | Sep 11, 2023 |
| Google        | Enguarde                    | [b2b5b5f73b](https://linux-hardware.org/?probe=b2b5b5f73b) | Sep 11, 2023 |
| Lenovo        | ThinkPad L380 20M50013GE    | [e7778dd80d](https://linux-hardware.org/?probe=e7778dd80d) | Sep 11, 2023 |
| HP            | 250 G3                      | [162574954f](https://linux-hardware.org/?probe=162574954f) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [24e256ad9e](https://linux-hardware.org/?probe=24e256ad9e) | Sep 11, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [57e8f1b556](https://linux-hardware.org/?probe=57e8f1b556) | Sep 11, 2023 |
| Samsung       | 550XED                      | [69d754d35b](https://linux-hardware.org/?probe=69d754d35b) | Sep 11, 2023 |
| Samsung       | 550XED                      | [8187eca3e3](https://linux-hardware.org/?probe=8187eca3e3) | Sep 11, 2023 |
| Panasonic     | CF-19RHR3DPM                | [11484f2d00](https://linux-hardware.org/?probe=11484f2d00) | Sep 10, 2023 |
| ASUSTek       | G751JT                      | [4395b1ccb2](https://linux-hardware.org/?probe=4395b1ccb2) | Sep 10, 2023 |
| Dell          | Precision 5530              | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| ASUSTek       | X550VX                      | [b1b59ca70c](https://linux-hardware.org/?probe=b1b59ca70c) | Sep 10, 2023 |
| Acer          | Extensa 5220                | [c4ea757260](https://linux-hardware.org/?probe=c4ea757260) | Sep 10, 2023 |
| HP            | Unknown                     | [cb5704a65f](https://linux-hardware.org/?probe=cb5704a65f) | Sep 10, 2023 |
| Google        | Lillipup                    | [c3a892cdca](https://linux-hardware.org/?probe=c3a892cdca) | Sep 10, 2023 |
| HP            | ProBook 6570b               | [3ed768081c](https://linux-hardware.org/?probe=3ed768081c) | Sep 09, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [780a68ac11](https://linux-hardware.org/?probe=780a68ac11) | Sep 09, 2023 |
| Acer          | Aspire E1-531               | [91decda3c9](https://linux-hardware.org/?probe=91decda3c9) | Sep 09, 2023 |
| Dell          | Inspiron 7580               | [9705f02462](https://linux-hardware.org/?probe=9705f02462) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [3865278574](https://linux-hardware.org/?probe=3865278574) | Sep 09, 2023 |
| Acer          | Nitro AN515-55              | [3f247b15c6](https://linux-hardware.org/?probe=3f247b15c6) | Sep 09, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005QU... | [0a57a98442](https://linux-hardware.org/?probe=0a57a98442) | Sep 09, 2023 |
| Lenovo        | ThinkPad X395 20NMS0YG00    | [b3697e5a7e](https://linux-hardware.org/?probe=b3697e5a7e) | Sep 09, 2023 |
| Google        | Enguarde                    | [3ec3cf816b](https://linux-hardware.org/?probe=3ec3cf816b) | Sep 08, 2023 |
| Google        | Enguarde                    | [fa7b318083](https://linux-hardware.org/?probe=fa7b318083) | Sep 08, 2023 |
| Google        | Enguarde                    | [1621463a03](https://linux-hardware.org/?probe=1621463a03) | Sep 08, 2023 |
| Google        | Enguarde                    | [b54a785396](https://linux-hardware.org/?probe=b54a785396) | Sep 08, 2023 |
| Google        | Enguarde                    | [b35f66260b](https://linux-hardware.org/?probe=b35f66260b) | Sep 08, 2023 |
| Google        | Enguarde                    | [e754c23dd9](https://linux-hardware.org/?probe=e754c23dd9) | Sep 08, 2023 |
| Google        | Enguarde                    | [71e3d1a632](https://linux-hardware.org/?probe=71e3d1a632) | Sep 08, 2023 |
| Google        | Enguarde                    | [352198bb3c](https://linux-hardware.org/?probe=352198bb3c) | Sep 08, 2023 |
| Google        | Enguarde                    | [15edd97e90](https://linux-hardware.org/?probe=15edd97e90) | Sep 08, 2023 |
| Google        | Enguarde                    | [265336497a](https://linux-hardware.org/?probe=265336497a) | Sep 08, 2023 |
| Google        | Enguarde                    | [af54a959e3](https://linux-hardware.org/?probe=af54a959e3) | Sep 08, 2023 |
| Google        | Enguarde                    | [d102cf6258](https://linux-hardware.org/?probe=d102cf6258) | Sep 08, 2023 |
| Google        | Enguarde                    | [d6fd89750c](https://linux-hardware.org/?probe=d6fd89750c) | Sep 08, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [4e756a7c7d](https://linux-hardware.org/?probe=4e756a7c7d) | Sep 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e0899f8743](https://linux-hardware.org/?probe=e0899f8743) | Sep 08, 2023 |
| Dell          | Latitude 5530               | [ae835c8d8b](https://linux-hardware.org/?probe=ae835c8d8b) | Sep 08, 2023 |
| HP            | 250 G3                      | [51ef1d34d0](https://linux-hardware.org/?probe=51ef1d34d0) | Sep 08, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [c9d6171716](https://linux-hardware.org/?probe=c9d6171716) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [4695b758c9](https://linux-hardware.org/?probe=4695b758c9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | [e8a4fb3aea](https://linux-hardware.org/?probe=e8a4fb3aea) | Sep 08, 2023 |
| Dell          | Latitude E5550              | [90fc999e4a](https://linux-hardware.org/?probe=90fc999e4a) | Sep 08, 2023 |
| ASUSTek       | X507UB                      | [4604e73045](https://linux-hardware.org/?probe=4604e73045) | Sep 08, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [b05fdf4d62](https://linux-hardware.org/?probe=b05fdf4d62) | Sep 08, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [db6d9f2293](https://linux-hardware.org/?probe=db6d9f2293) | Sep 08, 2023 |
| Lenovo        | ThinkPad P43s 20RH001UMX    | [0fdff74089](https://linux-hardware.org/?probe=0fdff74089) | Sep 07, 2023 |
| Google        | Enguarde                    | [7718db84e9](https://linux-hardware.org/?probe=7718db84e9) | Sep 07, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | [9117a08473](https://linux-hardware.org/?probe=9117a08473) | Sep 07, 2023 |
| Google        | Enguarde                    | [8a82984679](https://linux-hardware.org/?probe=8a82984679) | Sep 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e2f9ce90d3](https://linux-hardware.org/?probe=e2f9ce90d3) | Sep 07, 2023 |
| ASUSTek       | N751JX                      | [8ece217753](https://linux-hardware.org/?probe=8ece217753) | Sep 06, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0468bc91fc](https://linux-hardware.org/?probe=0468bc91fc) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [50ecc5159c](https://linux-hardware.org/?probe=50ecc5159c) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [b34e0e7866](https://linux-hardware.org/?probe=b34e0e7866) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [9d5880bc6c](https://linux-hardware.org/?probe=9d5880bc6c) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | [6ffc334cf9](https://linux-hardware.org/?probe=6ffc334cf9) | Sep 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [03f6b3b62b](https://linux-hardware.org/?probe=03f6b3b62b) | Sep 06, 2023 |
| Toshiba       | Satellite A205              | [9a44e74608](https://linux-hardware.org/?probe=9a44e74608) | Sep 06, 2023 |
| Toshiba       | Satellite A205              | [a2b456886d](https://linux-hardware.org/?probe=a2b456886d) | Sep 05, 2023 |
| HP            | ZBook 15 G3                 | [faac131992](https://linux-hardware.org/?probe=faac131992) | Sep 05, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [1bcf7b95c6](https://linux-hardware.org/?probe=1bcf7b95c6) | Sep 05, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [75c15ac2e8](https://linux-hardware.org/?probe=75c15ac2e8) | Sep 05, 2023 |
| ASUSTek       | K53SD                       | [051fefc7ca](https://linux-hardware.org/?probe=051fefc7ca) | Sep 05, 2023 |
| Lenovo        | ThinkPad T520 4243WCR       | [181ef642cd](https://linux-hardware.org/?probe=181ef642cd) | Sep 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 3415      | 53.65%  |
| Debian 12                       | 1171      | 18.4%   |
| Debian 10                       | 855       | 13.43%  |
| Debian Testing                  | 357       | 5.61%   |
| Debian                          | 215       | 3.38%   |
| Debian 9                        | 146       | 2.29%   |
| Debian Unstable                 | 128       | 2.01%   |
| Debian 11-updates               | 27        | 0.42%   |
| Debian Testing/unstable         | 25        | 0.39%   |
| Debian 8                        | 11        | 0.17%   |
| Debian Sid                      | 5         | 0.08%   |
| Debian 23                       | 3         | 0.05%   |
| Debian 22                       | 3         | 0.05%   |
| Debian Testing-proposed-updates | 1         | 0.02%   |
| Debian 99                       | 1         | 0.02%   |
| Debian 6                        | 1         | 0.02%   |
| Debian 12-updates               | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 6054      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.10.0-8-amd64  | 586       | 8.41%   |
| 5.10.0-10-amd64 | 491       | 7.04%   |
| 6.1.0-13-amd64  | 302       | 4.33%   |
| 5.10.0-20-amd64 | 245       | 3.51%   |
| 5.10.0-21-amd64 | 242       | 3.47%   |
| 5.10.0-18-amd64 | 179       | 2.57%   |
| 6.1.0-9-amd64   | 175       | 2.51%   |
| 6.1.0-10-amd64  | 175       | 2.51%   |
| 5.10.0-9-amd64  | 173       | 2.48%   |
| 5.10.0-7-amd64  | 171       | 2.45%   |
| 5.10.0-16-amd64 | 167       | 2.4%    |
| 5.10.0-19-amd64 | 162       | 2.32%   |
| 5.10.0-13-amd64 | 151       | 2.17%   |
| 6.1.0-12-amd64  | 121       | 1.74%   |
| 5.10.0-23-amd64 | 107       | 1.53%   |
| 6.1.0-11-amd64  | 106       | 1.52%   |
| 5.10.0-11-amd64 | 105       | 1.51%   |
| 4.19.0-9-amd64  | 85        | 1.22%   |
| 4.19.0-6-amd64  | 82        | 1.18%   |
| 5.10.0-14-amd64 | 80        | 1.15%   |
| 5.10.0-17-amd64 | 74        | 1.06%   |
| 4.19.0-13-amd64 | 69        | 0.99%   |
| 4.19.0-8-amd64  | 68        | 0.98%   |
| 5.10.0-15-amd64 | 55        | 0.79%   |
| 4.19.0-16-amd64 | 53        | 0.76%   |
| 6.1.0-7-amd64   | 52        | 0.75%   |
| 6.1.0-4-amd64   | 52        | 0.75%   |
| 4.19.0-10-amd64 | 52        | 0.75%   |
| 5.15.0-2-amd64  | 51        | 0.73%   |
| 5.10.0-2-amd64  | 49        | 0.7%    |
| 4.19.0-12-amd64 | 47        | 0.67%   |
| 5.10.0-22-amd64 | 45        | 0.65%   |
| 4.19.0-14-amd64 | 42        | 0.6%    |
| 5.10.0-6-amd64  | 41        | 0.59%   |
| 5.10.0-12-amd64 | 40        | 0.57%   |
| 4.19.0-17-amd64 | 40        | 0.57%   |
| 4.9.0-8-amd64   | 39        | 0.56%   |
| 6.1.0-15-amd64  | 31        | 0.44%   |
| 5.18.0-2-amd64  | 31        | 0.44%   |
| 5.10.0-3-amd64  | 31        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 3203      | 49.11%  |
| 6.1.0    | 1148      | 17.6%   |
| 4.19.0   | 656       | 10.06%  |
| 6.0.0    | 149       | 2.28%   |
| 4.9.0    | 120       | 1.84%   |
| 5.18.0   | 108       | 1.66%   |
| 5.15.0   | 92        | 1.41%   |
| 5.9.0    | 74        | 1.13%   |
| 5.19.0   | 71        | 1.09%   |
| 6.5.0    | 69        | 1.06%   |
| 5.16.0   | 69        | 1.06%   |
| 5.4.0    | 64        | 0.98%   |
| 5.7.0    | 59        | 0.9%    |
| 5.8.0    | 56        | 0.86%   |
| 5.14.0   | 53        | 0.81%   |
| 5.6.0    | 45        | 0.69%   |
| 6.4.0    | 43        | 0.66%   |
| 5.17.0   | 39        | 0.6%    |
| 6.3.0    | 31        | 0.48%   |
| 5.10.10  | 28        | 0.43%   |
| 5.3.0    | 19        | 0.29%   |
| 5.5.0    | 16        | 0.25%   |
| 5.2.0    | 12        | 0.18%   |
| 4.18.0   | 12        | 0.18%   |
| 6.2.16   | 10        | 0.15%   |
| 3.16.0   | 9         | 0.14%   |
| 5.12.0   | 6         | 0.09%   |
| 6.6.0    | 4         | 0.06%   |
| 6.5.11   | 3         | 0.05%   |
| 6.4.3    | 3         | 0.05%   |
| 6.4.2    | 3         | 0.05%   |
| 6.3.4    | 3         | 0.05%   |
| 6.2.8    | 3         | 0.05%   |
| 6.1.15   | 3         | 0.05%   |
| 5.3.5    | 3         | 0.05%   |
| 5.17.5   | 3         | 0.05%   |
| 5.15.107 | 3         | 0.05%   |
| 5.13.19  | 3         | 0.05%   |
| 5.13.0   | 3         | 0.05%   |
| 5.11.0   | 3         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 3256      | 50.03%  |
| 6.1     | 1161      | 17.84%  |
| 4.19    | 660       | 10.14%  |
| 6.0     | 157       | 2.41%   |
| 4.9     | 123       | 1.89%   |
| 5.15    | 119       | 1.83%   |
| 5.18    | 113       | 1.74%   |
| 5.9     | 80        | 1.23%   |
| 6.5     | 79        | 1.21%   |
| 5.4     | 76        | 1.17%   |
| 5.19    | 76        | 1.17%   |
| 5.16    | 73        | 1.12%   |
| 5.7     | 62        | 0.95%   |
| 5.8     | 61        | 0.94%   |
| 5.14    | 58        | 0.89%   |
| 6.4     | 56        | 0.86%   |
| 5.6     | 49        | 0.75%   |
| 5.17    | 48        | 0.74%   |
| 6.3     | 39        | 0.6%    |
| 5.3     | 24        | 0.37%   |
| 5.5     | 19        | 0.29%   |
| 6.2     | 18        | 0.28%   |
| 5.2     | 18        | 0.28%   |
| 5.13    | 12        | 0.18%   |
| 4.18    | 12        | 0.18%   |
| 5.12    | 9         | 0.14%   |
| 5.11    | 9         | 0.14%   |
| 3.16    | 9         | 0.14%   |
| 6.6     | 6         | 0.09%   |
| 3.10    | 4         | 0.06%   |
| 5.1     | 3         | 0.05%   |
| 5.0     | 3         | 0.05%   |
| 4.17    | 2         | 0.03%   |
| 4.15    | 2         | 0.03%   |
| 4.14    | 2         | 0.03%   |
| 6       | 1         | 0.02%   |
| 5.4.104 | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 4.4     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5797      | 95.74%  |
| i686    | 241       | 3.98%   |
| armv7l  | 10        | 0.17%   |
| aarch64 | 6         | 0.1%    |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1768      | 28.42%  |
| Unknown           | 1335      | 21.46%  |
| KDE5              | 913       | 14.67%  |
| XFCE              | 810       | 13.02%  |
| MATE              | 264       | 4.24%   |
| X-Cinnamon        | 246       | 3.95%   |
| LXDE              | 200       | 3.21%   |
| Cinnamon          | 163       | 2.62%   |
| KDE               | 117       | 1.88%   |
| i3                | 112       | 1.8%    |
| LXQt              | 92        | 1.48%   |
| GNOME Flashback   | 43        | 0.69%   |
| lightdm-xsession  | 29        | 0.47%   |
| Budgie            | 19        | 0.31%   |
| Openbox           | 16        | 0.26%   |
| GNOME Classic     | 15        | 0.24%   |
| Trinity           | 14        | 0.23%   |
| awesome           | 6         | 0.1%    |
| sway              | 5         | 0.08%   |
| Enlightenment     | 5         | 0.08%   |
| Dwm               | 5         | 0.08%   |
| bspwm             | 5         | 0.08%   |
| ICEWM             | 4         | 0.06%   |
| fluxbox           | 4         | 0.06%   |
| x-session-manager | 3         | 0.05%   |
| Unity             | 3         | 0.05%   |
| GNUstep           | 3         | 0.05%   |
| Cutefish          | 3         | 0.05%   |
| BunsenLabs        | 3         | 0.05%   |
| xmonad            | 2         | 0.03%   |
| KDE4              | 2         | 0.03%   |
| default           | 2         | 0.03%   |
| Deepin            | 2         | 0.03%   |
| wmaker-common     | 1         | 0.02%   |
| TOS:GNOME         | 1         | 0.02%   |
| qtile             | 1         | 0.02%   |
| Pantheon          | 1         | 0.02%   |
| mwm               | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 3421      | 55.24%  |
| Wayland     | 1459      | 23.56%  |
| Unknown     | 1062      | 17.15%  |
| Tty         | 246       | 3.97%   |
| Unspecified | 4         | 0.06%   |
| Web         | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2305      | 37.03%  |
| LightDM | 1095      | 17.59%  |
| GDM     | 1016      | 16.32%  |
| SDDM    | 810       | 13.01%  |
| GDM3    | 590       | 9.48%   |
| TDM     | 310       | 4.98%   |
| NODM    | 34        | 0.55%   |
| XDM     | 23        | 0.37%   |
| SLiM    | 14        | 0.22%   |
| LXDM    | 10        | 0.16%   |
| KDM     | 8         | 0.13%   |
| Ly      | 4         | 0.06%   |
| GREETD  | 3         | 0.05%   |
| WDM     | 1         | 0.02%   |
| SU      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1996      | 32.44%  |
| Unknown | 1045      | 16.98%  |
| de_DE   | 411       | 6.68%   |
| ru_RU   | 400       | 6.5%    |
| fr_FR   | 331       | 5.38%   |
| en_GB   | 287       | 4.66%   |
| pt_BR   | 204       | 3.32%   |
| it_IT   | 171       | 2.78%   |
| es_ES   | 171       | 2.78%   |
| pl_PL   | 120       | 1.95%   |
| en_CA   | 78        | 1.27%   |
| C       | 68        | 1.11%   |
| en_AU   | 60        | 0.98%   |
| en_IN   | 59        | 0.96%   |
| es_MX   | 58        | 0.94%   |
| zh_CN   | 51        | 0.83%   |
| es_AR   | 46        | 0.75%   |
| en_IE   | 35        | 0.57%   |
| es_CL   | 34        | 0.55%   |
| sv_SE   | 33        | 0.54%   |
| hu_HU   | 31        | 0.5%    |
| de_CH   | 23        | 0.37%   |
| pt_PT   | 21        | 0.34%   |
| fi_FI   | 21        | 0.34%   |
| de_AT   | 21        | 0.34%   |
| cs_CZ   | 21        | 0.34%   |
| nl_NL   | 20        | 0.33%   |
| es_VE   | 20        | 0.33%   |
| tr_TR   | 18        | 0.29%   |
| es_CO   | 18        | 0.29%   |
| en_NZ   | 15        | 0.24%   |
| ja_JP   | 14        | 0.23%   |
| en_ZA   | 13        | 0.21%   |
| ca_ES   | 13        | 0.21%   |
| zh_TW   | 12        | 0.2%    |
| fr_BE   | 12        | 0.2%    |
| en_SG   | 12        | 0.2%    |
| ko_KR   | 11        | 0.18%   |
| sk_SK   | 10        | 0.16%   |
| fr_CH   | 10        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3749      | 61.21%  |
| BIOS | 2376      | 38.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4445      | 72.87%  |
| Overlay | 1186      | 19.44%  |
| Btrfs   | 209       | 3.43%   |
| Unknown | 78        | 1.28%   |
| Xfs     | 56        | 0.92%   |
| Tmpfs   | 41        | 0.67%   |
| Rootfs  | 34        | 0.56%   |
| Zfs     | 20        | 0.33%   |
| Ext2    | 16        | 0.26%   |
| Ext3    | 9         | 0.15%   |
| Aufs    | 4         | 0.07%   |
| Jfs     | 1         | 0.02%   |
| F2fs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 3796      | 61.72%  |
| Unknown | 1212      | 19.71%  |
| MBR     | 1142      | 18.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5129      | 83.53%  |
| Yes       | 1011      | 16.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4523      | 73.83%  |
| Yes       | 1603      | 26.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1372      | 22.66%  |
| Hewlett-Packard        | 921       | 15.21%  |
| Dell                   | 858       | 14.17%  |
| Apple                  | 681       | 11.25%  |
| ASUSTek Computer       | 563       | 9.3%    |
| Acer                   | 427       | 7.05%   |
| Google                 | 197       | 3.25%   |
| MSI                    | 111       | 1.83%   |
| Toshiba                | 104       | 1.72%   |
| Samsung Electronics    | 90        | 1.49%   |
| HUAWEI                 | 54        | 0.89%   |
| Unknown                | 51        | 0.84%   |
| Sony                   | 50        | 0.83%   |
| Aquarius               | 48        | 0.79%   |
| Notebook               | 33        | 0.55%   |
| Fujitsu                | 33        | 0.55%   |
| Medion                 | 20        | 0.33%   |
| Alienware              | 19        | 0.31%   |
| Packard Bell           | 18        | 0.3%    |
| Panasonic              | 17        | 0.28%   |
| Timi                   | 16        | 0.26%   |
| Positivo               | 16        | 0.26%   |
| TUXEDO                 | 15        | 0.25%   |
| IBM                    | 15        | 0.25%   |
| Intel                  | 14        | 0.23%   |
| HONOR                  | 12        | 0.2%    |
| Clevo                  | 12        | 0.2%    |
| LG Electronics         | 11        | 0.18%   |
| Gigabyte Technology    | 10        | 0.17%   |
| Fujitsu Siemens        | 10        | 0.17%   |
| Framework              | 10        | 0.17%   |
| Razer                  | 8         | 0.13%   |
| PC Specialist          | 8         | 0.13%   |
| GPU Company            | 8         | 0.13%   |
| eMachines              | 8         | 0.13%   |
| System76               | 6         | 0.1%    |
| SLIMBOOK               | 6         | 0.1%    |
| Chuwi                  | 6         | 0.1%    |
| Avell High Performance | 6         | 0.1%    |
| Schenker               | 5         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 355       | 5.86%   |
| Apple MacBookAir7,2                   | 81        | 1.34%   |
| Apple MacBookAir7,1                   | 77        | 1.27%   |
| Google Enguarde                       | 74        | 1.22%   |
| Unknown                               | 69        | 1.14%   |
| Apple MacBook2,1                      | 58        | 0.96%   |
| Aquarius NS585                        | 48        | 0.79%   |
| Google Reks                           | 45        | 0.74%   |
| HP Notebook                           | 28        | 0.46%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.4%    |
| Google Terra                          | 24        | 0.4%    |
| Apple MacBook4,1                      | 23        | 0.38%   |
| HP Pavilion g6                        | 18        | 0.3%    |
| Acer Aspire A315-23                   | 17        | 0.28%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.26%   |
| ASUS 1005HA                           | 15        | 0.25%   |
| HP EliteBook 840 G3                   | 14        | 0.23%   |
| HP Pavilion dv6                       | 13        | 0.21%   |
| HP Laptop 15-db0xxx                   | 13        | 0.21%   |
| Dell Latitude E7440                   | 13        | 0.21%   |
| Dell Latitude 7480                    | 13        | 0.21%   |
| HP EliteBook 8460p                    | 12        | 0.2%    |
| HP 255 G8 Notebook PC                 | 12        | 0.2%    |
| Dell Latitude E6430                   | 12        | 0.2%    |
| Dell Latitude E6420                   | 12        | 0.2%    |
| HP Pavilion Notebook                  | 11        | 0.18%   |
| HP Laptop 15s-eq2xxx                  | 11        | 0.18%   |
| HP 250 G7 Notebook PC                 | 11        | 0.18%   |
| Dell Latitude E7450                   | 11        | 0.18%   |
| Dell Latitude 5420                    | 11        | 0.18%   |
| Dell Inspiron 5570                    | 11        | 0.18%   |
| Acer Aspire A515-56                   | 11        | 0.18%   |
| Samsung 300E4C/300E5C/300E7C          | 9         | 0.15%   |
| HP EliteBook 840 G6                   | 9         | 0.15%   |
| HP EliteBook 840 G1                   | 9         | 0.15%   |
| Dell XPS 13 9370                      | 9         | 0.15%   |
| Dell XPS 13 9360                      | 9         | 0.15%   |
| Dell XPS 13 9310                      | 9         | 0.15%   |
| Dell Latitude 7490                    | 9         | 0.15%   |
| Dell Inspiron 15-3567                 | 9         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 895       | 14.78%  |
| Apple MacBook5    | 357       | 5.9%    |
| Dell Latitude     | 336       | 5.55%   |
| Acer Aspire       | 279       | 4.61%   |
| Dell Inspiron     | 240       | 3.96%   |
| Lenovo IdeaPad    | 238       | 3.93%   |
| HP EliteBook      | 192       | 3.17%   |
| Apple MacBookAir7 | 158       | 2.61%   |
| HP Pavilion       | 142       | 2.35%   |
| HP Laptop         | 128       | 2.11%   |
| HP ProBook        | 120       | 1.98%   |
| Dell XPS          | 101       | 1.67%   |
| ASUS VivoBook     | 98        | 1.62%   |
| Toshiba Satellite | 81        | 1.34%   |
| Google Enguarde   | 74        | 1.22%   |
| Dell Vostro       | 72        | 1.19%   |
| Unknown           | 69        | 1.14%   |
| Dell Precision    | 68        | 1.12%   |
| Apple MacBook2    | 58        | 0.96%   |
| HP Compaq         | 48        | 0.79%   |
| Aquarius NS585    | 48        | 0.79%   |
| Google Reks       | 45        | 0.74%   |
| ASUS ASUS         | 43        | 0.71%   |
| Lenovo Legion     | 42        | 0.69%   |
| HP ZBook          | 40        | 0.66%   |
| ASUS ZenBook      | 40        | 0.66%   |
| HP 250            | 38        | 0.63%   |
| Acer TravelMate   | 33        | 0.55%   |
| Acer Swift        | 33        | 0.55%   |
| ASUS ROG          | 32        | 0.53%   |
| Lenovo ThinkBook  | 31        | 0.51%   |
| Acer Nitro        | 31        | 0.51%   |
| Fujitsu LIFEBOOK  | 29        | 0.48%   |
| HP Notebook       | 28        | 0.46%   |
| HP 255            | 27        | 0.45%   |
| HP ENVY           | 24        | 0.4%    |
| Google Terra      | 24        | 0.4%    |
| Apple MacBook4    | 23        | 0.38%   |
| Lenovo Yoga       | 21        | 0.35%   |
| HP OMEN           | 21        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 571       | 9.43%   |
| 2019    | 562       | 9.28%   |
| 2020    | 549       | 9.07%   |
| 2009    | 522       | 8.62%   |
| 2012    | 386       | 6.38%   |
| 2018    | 382       | 6.31%   |
| 2011    | 363       | 6%      |
| 2017    | 352       | 5.81%   |
| 2016    | 352       | 5.81%   |
| 2022    | 323       | 5.34%   |
| 2013    | 304       | 5.02%   |
| 2014    | 279       | 4.61%   |
| 2015    | 244       | 4.03%   |
| 2010    | 222       | 3.67%   |
| 2007    | 221       | 3.65%   |
| 2008    | 182       | 3.01%   |
| 2023    | 130       | 2.15%   |
| 2006    | 38        | 0.63%   |
| 2005    | 28        | 0.46%   |
| Unknown | 19        | 0.31%   |
| 2004    | 12        | 0.2%    |
| 2003    | 11        | 0.18%   |
| 2002    | 2         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 6054      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 5566      | 91.41%  |
| Enabled  | 523       | 8.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5841      | 96.47%  |
| Yes  | 214       | 3.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1579      | 25.81%  |
| 3.01-4.0    | 1139      | 18.62%  |
| 16.01-24.0  | 1033      | 16.88%  |
| 8.01-16.0   | 988       | 16.15%  |
| 1.01-2.0    | 601       | 9.82%   |
| 32.01-64.0  | 399       | 6.52%   |
| 2.01-3.0    | 120       | 1.96%   |
| 0.51-1.0    | 87        | 1.42%   |
| 64.01-256.0 | 79        | 1.29%   |
| 24.01-32.0  | 68        | 1.11%   |
| 0.01-0.5    | 23        | 0.38%   |
| Unknown     | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2351      | 36.09%  |
| 2.01-3.0   | 1399      | 21.48%  |
| 4.01-8.0   | 946       | 14.52%  |
| 3.01-4.0   | 749       | 11.5%   |
| 0.51-1.0   | 611       | 9.38%   |
| 8.01-16.0  | 258       | 3.96%   |
| 0.01-0.5   | 154       | 2.36%   |
| 16.01-24.0 | 27        | 0.41%   |
| 24.01-32.0 | 7         | 0.11%   |
| Unknown    | 7         | 0.11%   |
| 32.01-64.0 | 4         | 0.06%   |
| 0          | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4733      | 76.97%  |
| 2      | 1199      | 19.5%   |
| 3      | 145       | 2.36%   |
| 0      | 42        | 0.68%   |
| 4      | 23        | 0.37%   |
| 5      | 5         | 0.08%   |
| 7      | 2         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4094      | 67.37%  |
| Yes       | 1983      | 32.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4885      | 80.37%  |
| No        | 1193      | 19.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5923      | 97.76%  |
| No        | 136       | 2.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4885      | 80.13%  |
| No        | 1211      | 19.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1465      | 24.03%  |
| Germany     | 594       | 9.74%   |
| Russia      | 471       | 7.73%   |
| France      | 415       | 6.81%   |
| Brazil      | 300       | 4.92%   |
| Spain       | 249       | 4.08%   |
| Italy       | 247       | 4.05%   |
| Poland      | 179       | 2.94%   |
| UK          | 144       | 2.36%   |
| Canada      | 135       | 2.21%   |
| Netherlands | 107       | 1.76%   |
| Mexico      | 86        | 1.41%   |
| India       | 83        | 1.36%   |
| Switzerland | 79        | 1.3%    |
| Sweden      | 77        | 1.26%   |
| China       | 75        | 1.23%   |
| Australia   | 71        | 1.16%   |
| Argentina   | 69        | 1.13%   |
| Turkey      | 63        | 1.03%   |
| Ukraine     | 61        | 1%      |
| Portugal    | 53        | 0.87%   |
| Austria     | 53        | 0.87%   |
| Hungary     | 51        | 0.84%   |
| Belgium     | 50        | 0.82%   |
| Czechia     | 48        | 0.79%   |
| Finland     | 41        | 0.67%   |
| Chile       | 41        | 0.67%   |
| Norway      | 38        | 0.62%   |
| Greece      | 38        | 0.62%   |
| Romania     | 37        | 0.61%   |
| Colombia    | 33        | 0.54%   |
| Indonesia   | 32        | 0.52%   |
| Ireland     | 29        | 0.48%   |
| Japan       | 25        | 0.41%   |
| Venezuela   | 24        | 0.39%   |
| Bulgaria    | 23        | 0.38%   |
| Thailand    | 21        | 0.34%   |
| New Zealand | 21        | 0.34%   |
| Denmark     | 21        | 0.34%   |
| Taiwan      | 19        | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 668       | 10.34%  |
| Dover-Foxcroft    | 229       | 3.54%   |
| Voronezh          | 170       | 2.63%   |
| Moscow            | 87        | 1.35%   |
| Paris             | 75        | 1.16%   |
| Berlin            | 61        | 0.94%   |
| St Petersburg     | 57        | 0.88%   |
| Madrid            | 46        | 0.71%   |
| Warsaw            | 41        | 0.63%   |
| Seville           | 41        | 0.63%   |
| Sao Paulo         | 40        | 0.62%   |
| Milan             | 40        | 0.62%   |
| Vienna            | 34        | 0.53%   |
| Munich            | 33        | 0.51%   |
| Amsterdam         | 32        | 0.5%    |
| Hamburg           | 31        | 0.48%   |
| Prague            | 25        | 0.39%   |
| Sydney            | 23        | 0.36%   |
| London            | 23        | 0.36%   |
| Istanbul          | 23        | 0.36%   |
| Barcelona         | 23        | 0.36%   |
| Frankfurt am Main | 22        | 0.34%   |
| Dublin            | 22        | 0.34%   |
| Budapest          | 22        | 0.34%   |
| Perm              | 21        | 0.33%   |
| Brasília         | 21        | 0.33%   |
| Zurich            | 19        | 0.29%   |
| Rome              | 19        | 0.29%   |
| Mexico City       | 19        | 0.29%   |
| Lisbon            | 19        | 0.29%   |
| Helsinki          | 19        | 0.29%   |
| Athens            | 19        | 0.29%   |
| Toronto           | 18        | 0.28%   |
| Leipzig           | 18        | 0.28%   |
| Singapore         | 16        | 0.25%   |
| Saltsjoe-Boo      | 15        | 0.23%   |
| Mesa              | 15        | 0.23%   |
| Melbourne         | 15        | 0.23%   |
| Cologne           | 15        | 0.23%   |
| Santiago          | 14        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1138      | 1462   | 15.5%   |
| WDC                         | 793       | 980    | 10.8%   |
| Seagate                     | 626       | 745    | 8.53%   |
| Toshiba                     | 525       | 590    | 7.15%   |
| Unknown                     | 480       | 630    | 6.54%   |
| Kingston                    | 394       | 503    | 5.37%   |
| SanDisk                     | 378       | 469    | 5.15%   |
| SK hynix                    | 301       | 363    | 4.1%    |
| Fujitsu                     | 294       | 306    | 4.01%   |
| Crucial                     | 279       | 337    | 3.8%    |
| Micron Technology           | 203       | 221    | 2.77%   |
| Apple                       | 201       | 257    | 2.74%   |
| Intel                       | 191       | 238    | 2.6%    |
| Hitachi                     | 184       | 214    | 2.51%   |
| A-DATA Technology           | 152       | 298    | 2.07%   |
| HGST                        | 145       | 167    | 1.98%   |
| KIOXIA                      | 84        | 99     | 1.14%   |
| Unknown                     | 56        | 64     | 0.76%   |
| China                       | 48        | 55     | 0.65%   |
| LITEON                      | 40        | 49     | 0.54%   |
| Phison                      | 36        | 46     | 0.49%   |
| Transcend                   | 35        | 43     | 0.48%   |
| Silicon Motion              | 32        | 38     | 0.44%   |
| Intenso                     | 32        | 42     | 0.44%   |
| SPCC                        | 31        | 41     | 0.42%   |
| PNY                         | 29        | 37     | 0.4%    |
| SSSTC                       | 26        | 27     | 0.35%   |
| Patriot                     | 26        | 28     | 0.35%   |
| JMicron Technology          | 25        | 26     | 0.34%   |
| Team                        | 22        | 24     | 0.3%    |
| LITEONIT                    | 20        | 25     | 0.27%   |
| SABRENT                     | 19        | 20     | 0.26%   |
| Micron/Crucial Technology   | 17        | 18     | 0.23%   |
| Netac                       | 16        | 21     | 0.22%   |
| GOODRAM                     | 16        | 19     | 0.22%   |
| Kingston Technology Company | 15        | 16     | 0.2%    |
| Phison Electronics          | 14        | 19     | 0.19%   |
| OCZ                         | 13        | 15     | 0.18%   |
| ADATA Technology            | 13        | 13     | 0.18%   |
| UMIS                        | 12        | 17     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 238       | 3.16%   |
| Seagate ST1000LM035-1RK172 1TB                      | 81        | 1.07%   |
| Apple SSD AP0128H 121GB                             | 77        | 1.02%   |
| Apple SSD SM0128G 121GB                             | 75        | 0.99%   |
| Kingston SA400S37240G 240GB SSD                     | 73        | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 62        | 0.82%   |
| Kingston SA400S37120G 120GB SSD                     | 62        | 0.82%   |
| Unknown                                             | 56        | 0.74%   |
| Toshiba MQ01ABD100 1TB                              | 52        | 0.69%   |
| Toshiba MK1655GSXF 160GB                            | 52        | 0.69%   |
| HGST HTS721010A9E630 1TB                            | 50        | 0.66%   |
| A-DATA SU800 512GB SSD                              | 50        | 0.66%   |
| Toshiba MQ04ABF100 1TB                              | 46        | 0.61%   |
| Crucial CT500MX500SSD1 500GB                        | 45        | 0.6%    |
| Toshiba MQ01ABF050 500GB                            | 44        | 0.58%   |
| Toshiba MK1653GSX 160GB                             | 43        | 0.57%   |
| Unknown MMC Card  32GB                              | 41        | 0.54%   |
| Unknown AGND3R  16GB                                | 39        | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB                        | 36        | 0.48%   |
| Samsung SSD 860 EVO 500GB                           | 36        | 0.48%   |
| Samsung SSD 850 EVO 250GB                           | 36        | 0.48%   |
| Kingston SA400S37480G 480GB SSD                     | 36        | 0.48%   |
| Unknown HAG2e  16GB                                 | 32        | 0.42%   |
| Unknown MMC Card  64GB                              | 31        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB                         | 31        | 0.41%   |
| Seagate ST500LT012-1DG142 500GB                     | 30        | 0.4%    |
| Seagate ST1000LM048-2E7172 1TB                      | 29        | 0.38%   |
| Samsung SSD 860 EVO 1TB                             | 29        | 0.38%   |
| Samsung SSD 860 EVO 250GB                           | 28        | 0.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 28        | 0.37%   |
| Seagate ST9500325AS 500GB                           | 27        | 0.36%   |
| Unknown SDW16G  16GB                                | 26        | 0.34%   |
| Samsung SSD 980 1TB                                 | 26        | 0.34%   |
| Unknown DF4016  16GB                                | 25        | 0.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 25        | 0.33%   |
| Samsung SSD 850 EVO 500GB                           | 24        | 0.32%   |
| Kingston SV300S37A120G 120GB SSD                    | 24        | 0.32%   |
| HGST HTS725050A7E630 500GB                          | 24        | 0.32%   |
| Crucial CT240BX500SSD1 240GB                        | 24        | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                        | 23        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 603       | 718    | 28.15%  |
| WDC                 | 446       | 513    | 20.82%  |
| Toshiba             | 376       | 416    | 17.55%  |
| Fujitsu             | 294       | 306    | 13.73%  |
| Hitachi             | 184       | 214    | 8.59%   |
| HGST                | 145       | 167    | 6.77%   |
| Samsung Electronics | 42        | 44     | 1.96%   |
| Unknown             | 18        | 21     | 0.84%   |
| TO Exter            | 5         | 6      | 0.23%   |
| IBM/Hitachi         | 5         | 6      | 0.23%   |
| Intenso             | 4         | 5      | 0.19%   |
| Apple               | 3         | 4      | 0.14%   |
| SILICONMOTION       | 2         | 2      | 0.09%   |
| ASMT                | 2         | 7      | 0.09%   |
| WALRAM              | 1         | 1      | 0.05%   |
| USB3.0              | 1         | 1      | 0.05%   |
| Unknown (CF)        | 1         | 1      | 0.05%   |
| SYMTEC              | 1         | 1      | 0.05%   |
| Space ke            | 1         | 1      | 0.05%   |
| SAGE                | 1         | 1      | 0.05%   |
| QNAP                | 1         | 2      | 0.05%   |
| Maxone              | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| IBM                 | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |
| Unknown             | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 472       | 595    | 20.22%  |
| Kingston            | 300       | 399    | 12.85%  |
| SanDisk             | 238       | 312    | 10.2%   |
| Crucial             | 238       | 290    | 10.2%   |
| A-DATA Technology   | 112       | 242    | 4.8%    |
| Apple               | 109       | 125    | 4.67%   |
| WDC                 | 99        | 128    | 4.24%   |
| Micron Technology   | 66        | 73     | 2.83%   |
| SK hynix            | 57        | 65     | 2.44%   |
| Intel               | 50        | 55     | 2.14%   |
| China               | 48        | 55     | 2.06%   |
| Toshiba             | 39        | 43     | 1.67%   |
| LITEON              | 34        | 40     | 1.46%   |
| Transcend           | 30        | 38     | 1.29%   |
| Intenso             | 26        | 34     | 1.11%   |
| PNY                 | 24        | 31     | 1.03%   |
| SPCC                | 23        | 32     | 0.99%   |
| Patriot             | 23        | 25     | 0.99%   |
| LITEONIT            | 20        | 25     | 0.86%   |
| Team                | 19        | 21     | 0.81%   |
| Netac               | 15        | 20     | 0.64%   |
| JMicron Technology  | 14        | 14     | 0.6%    |
| OCZ                 | 13        | 15     | 0.56%   |
| GOODRAM             | 13        | 16     | 0.56%   |
| Plextor             | 10        | 10     | 0.43%   |
| Lexar               | 10        | 11     | 0.43%   |
| Apacer              | 10        | 10     | 0.43%   |
| KIOXIA-EXCERIA      | 9         | 10     | 0.39%   |
| KingSpec            | 9         | 9      | 0.39%   |
| Unknown             | 9         | 9      | 0.39%   |
| LDLC                | 8         | 8      | 0.34%   |
| Hewlett-Packard     | 8         | 11     | 0.34%   |
| KingDian            | 7         | 7      | 0.3%    |
| ASMT                | 7         | 10     | 0.3%    |
| Seagate             | 6         | 6      | 0.26%   |
| Gigabyte Technology | 6         | 6      | 0.26%   |
| Dogfish             | 6         | 9      | 0.26%   |
| Corsair             | 6         | 6      | 0.26%   |
| FORESEE             | 5         | 5      | 0.21%   |
| Lenovo              | 4         | 4      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 2167      | 2985   | 30.92%  |
| NVMe    | 2150      | 2836   | 30.68%  |
| HDD     | 2096      | 2443   | 29.91%  |
| MMC     | 526       | 685    | 7.51%   |
| Unknown | 69        | 79     | 0.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3838      | 5241   | 57.07%  |
| NVMe | 2135      | 2807   | 31.75%  |
| MMC  | 526       | 685    | 7.82%   |
| SAS  | 226       | 295    | 3.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2975      | 3782   | 70.72%  |
| 0.51-1.0   | 1091      | 1458   | 25.93%  |
| 1.01-2.0   | 109       | 149    | 2.59%   |
| 4.01-10.0  | 21        | 25     | 0.5%    |
| 3.01-4.0   | 10        | 13     | 0.24%   |
| 2.01-3.0   | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1738      | 27.65%  |
| 251-500        | 1386      | 22.05%  |
| 501-1000       | 846       | 13.46%  |
| Unknown        | 843       | 13.41%  |
| 51-100         | 415       | 6.6%    |
| 1001-2000      | 344       | 5.47%   |
| 1-20           | 340       | 5.41%   |
| 21-50          | 228       | 3.63%   |
| 2001-3000      | 74        | 1.18%   |
| More than 3000 | 71        | 1.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2366      | 36.4%   |
| 21-50          | 869       | 13.37%  |
| Unknown        | 843       | 12.97%  |
| 101-250        | 828       | 12.74%  |
| 51-100         | 702       | 10.8%   |
| 251-500        | 465       | 7.15%   |
| 501-1000       | 272       | 4.18%   |
| 1001-2000      | 101       | 1.55%   |
| More than 3000 | 24        | 0.37%   |
| 2001-3000      | 19        | 0.29%   |
| 0              | 11        | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 25        | 25     | 4.25%   |
| Seagate ST9500325AS 500GB                           | 13        | 13     | 2.21%   |
| Toshiba MQ01ABD100 1TB                              | 11        | 12     | 1.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 11        | 13     | 1.87%   |
| Hitachi HTS543216L9SA02 160GB                       | 11        | 11     | 1.87%   |
| Toshiba MK1653GSX 160GB                             | 9         | 9      | 1.53%   |
| Toshiba MK1655GSXF 160GB                            | 8         | 8      | 1.36%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 8         | 10     | 1.36%   |
| Seagate ST9500420AS 500GB                           | 8         | 8      | 1.36%   |
| Seagate ST500LM021-1KJ152 500GB                     | 7         | 7      | 1.19%   |
| Seagate ST1000LM035-1RK172 1TB                      | 7         | 8      | 1.19%   |
| Hitachi HTS545050B9A300 500GB                       | 7         | 7      | 1.19%   |
| HGST HTS725050A7E630 500GB                          | 7         | 9      | 1.19%   |
| HGST HTS541010A9E680 1TB                            | 7         | 7      | 1.19%   |
| Toshiba MQ01ABF050 500GB                            | 6         | 6      | 1.02%   |
| Seagate ST9320325AS 320GB                           | 6         | 6      | 1.02%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 6      | 0.85%   |
| Kingston SV300S37A120G 120GB SSD                    | 5         | 5      | 0.85%   |
| Hitachi HTS542512K9SA00 120GB                       | 5         | 6      | 0.85%   |
| HGST HTS721010A9E630 1TB                            | 5         | 6      | 0.85%   |
| WDC WD1600BUDT-63DPZY0 160GB                        | 4         | 4      | 0.68%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 4         | 4      | 0.68%   |
| Seagate ST500LM000-SSHD-8GB                         | 4         | 4      | 0.68%   |
| Seagate ST320LT007-9ZV142 320GB                     | 4         | 6      | 0.68%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 4         | 4      | 0.68%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 4      | 0.68%   |
| Hitachi HTS547575A9E384 752GB                       | 4         | 4      | 0.68%   |
| HGST HTS545050A7E680 500GB                          | 4         | 4      | 0.68%   |
| Crucial CT275MX300SSD1 275GB                        | 4         | 4      | 0.68%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 3      | 0.51%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 3         | 3      | 0.51%   |
| SK hynix HFS256G39MND-2300A 256GB SSD               | 3         | 4      | 0.51%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 3         | 3      | 0.51%   |
| Seagate ST9250315AS 250GB                           | 3         | 4      | 0.51%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 3      | 0.51%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 3         | 3      | 0.51%   |
| Samsung Electronics SSD 870 EVO 500GB               | 3         | 3      | 0.51%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 4      | 0.51%   |
| Hitachi HTS547550A9E384 500GB                       | 3         | 3      | 0.51%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 0.51%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 114       | 124    | 19.42%  |
| Hitachi             | 81        | 88     | 13.8%   |
| Toshiba             | 72        | 74     | 12.27%  |
| WDC                 | 54        | 58     | 9.2%    |
| Fujitsu             | 40        | 41     | 6.81%   |
| HGST                | 38        | 41     | 6.47%   |
| Samsung Electronics | 35        | 38     | 5.96%   |
| SK hynix            | 29        | 32     | 4.94%   |
| Kingston            | 20        | 21     | 3.41%   |
| Micron Technology   | 16        | 17     | 2.73%   |
| Intel               | 16        | 17     | 2.73%   |
| SanDisk             | 15        | 17     | 2.56%   |
| Crucial             | 11        | 12     | 1.87%   |
| A-DATA Technology   | 10        | 11     | 1.7%    |
| LITEON              | 4         | 4      | 0.68%   |
| LITEONIT            | 3         | 4      | 0.51%   |
| SSSTC               | 2         | 2      | 0.34%   |
| Lenovo              | 2         | 2      | 0.34%   |
| KingSpec            | 2         | 2      | 0.34%   |
| JMicron Technology  | 2         | 2      | 0.34%   |
| IBM/Hitachi         | 2         | 2      | 0.34%   |
| Corsair             | 2         | 2      | 0.34%   |
| Apple               | 2         | 3      | 0.34%   |
| Unknown             | 2         | 2      | 0.34%   |
| Team                | 1         | 1      | 0.17%   |
| Silicon Motion      | 1         | 1      | 0.17%   |
| ShiJi               | 1         | 4      | 0.17%   |
| Plextor             | 1         | 1      | 0.17%   |
| KingDian            | 1         | 1      | 0.17%   |
| Kimtigo             | 1         | 1      | 0.17%   |
| IBM                 | 1         | 1      | 0.17%   |
| HECTRON             | 1         | 1      | 0.17%   |
| GOODRAM             | 1         | 1      | 0.17%   |
| GLOWAY              | 1         | 1      | 0.17%   |
| Dogfish             | 1         | 1      | 0.17%   |
| DGM                 | 1         | 1      | 0.17%   |
| China               | 1         | 1      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 114       | 124    | 27.47%  |
| Hitachi             | 81        | 88     | 19.52%  |
| Toshiba             | 71        | 73     | 17.11%  |
| WDC                 | 52        | 56     | 12.53%  |
| Fujitsu             | 40        | 41     | 9.64%   |
| HGST                | 38        | 41     | 9.16%   |
| Samsung Electronics | 15        | 15     | 3.61%   |
| IBM/Hitachi         | 2         | 2      | 0.48%   |
| IBM                 | 1         | 1      | 0.24%   |
| Apple               | 1         | 2      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 412       | 443    | 70.55%  |
| SSD     | 139       | 149    | 23.8%   |
| NVMe    | 32        | 39     | 5.48%   |
| Unknown | 1         | 1      | 0.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 11.11%  |
| Toshiba MQ04ABF100 1TB                          | 1         | 1      | 11.11%  |
| Toshiba MK6465GSX 640GB                         | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 11.11%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 11.11%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 11.11%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 11.11%  |
| Crucial CT500P2SSD8 500GB                       | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 22.22%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 2      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4068      | 5587   | 62.43%  |
| Detected | 1857      | 2798   | 28.5%   |
| Malfunc  | 581       | 632    | 8.92%   |
| Failed   | 9         | 10     | 0.14%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3640      | 53.09%  |
| Samsung Electronics                     | 735       | 10.72%  |
| AMD                                     | 572       | 8.34%   |
| Nvidia                                  | 387       | 5.64%   |
| SanDisk                                 | 375       | 5.47%   |
| SK hynix                                | 230       | 3.35%   |
| Micron Technology                       | 138       | 2.01%   |
| Toshiba America Info Systems            | 120       | 1.75%   |
| Kingston Technology Company             | 108       | 1.58%   |
| Apple                                   | 88        | 1.28%   |
| KIOXIA                                  | 81        | 1.18%   |
| Phison Electronics                      | 70        | 1.02%   |
| Micron/Crucial Technology               | 59        | 0.86%   |
| ADATA Technology                        | 53        | 0.77%   |
| Silicon Motion                          | 46        | 0.67%   |
| Solid State Storage Technology          | 30        | 0.44%   |
| Union Memory (Shenzhen)                 | 20        | 0.29%   |
| Silicon Integrated Systems [SiS]        | 15        | 0.22%   |
| Realtek Semiconductor                   | 12        | 0.18%   |
| MAXIO Technology (Hangzhou)             | 12        | 0.18%   |
| Shenzhen Longsys Electronics            | 8         | 0.12%   |
| Lite-On Technology                      | 7         | 0.1%    |
| Yangtze Memory Technologies             | 6         | 0.09%   |
| Seagate Technology                      | 6         | 0.09%   |
| Lenovo                                  | 6         | 0.09%   |
| Marvell Technology Group                | 4         | 0.06%   |
| VIA Technologies                        | 3         | 0.04%   |
| ULi Electronics                         | 3         | 0.04%   |
| Transcend                               | 3         | 0.04%   |
| Silicon Image                           | 3         | 0.04%   |
| Jiangsu Huacun Elec.                    | 3         | 0.04%   |
| Biwin Storage Technology                | 3         | 0.04%   |
| ASMedia Technology                      | 3         | 0.04%   |
| INNOGRIT                                | 2         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| ShenZhen TIGO Semiconductor             | 1         | 0.01%   |
| JMicron Technology                      | 1         | 0.01%   |
| Adaptec                                 | 1         | 0.01%   |
| Unknown                                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 497       | 6.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 460       | 6.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 386       | 5.27%   |
| Nvidia MCP79 AHCI Controller                                                   | 367       | 5.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 291       | 3.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 267       | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 255       | 3.48%   |
| Intel Volume Management Device NVMe RAID Controller                            | 214       | 2.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 176       | 2.4%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 174       | 2.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 144       | 1.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 139       | 1.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 126       | 1.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 106       | 1.45%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 105       | 1.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 105       | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 104       | 1.42%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 103       | 1.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 102       | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 102       | 1.39%   |
| Intel Tiger Lake-LP SATA Controller                                            | 95        | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 95        | 1.3%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 89        | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 89        | 1.21%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 86        | 1.17%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 80        | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 78        | 1.06%   |
| Apple S1X NVMe Controller                                                      | 78        | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 73        | 1%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 71        | 0.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 65        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 59        | 0.8%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 55        | 0.75%   |
| Intel SSD 660P Series                                                          | 55        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 55        | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 52        | 0.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 49        | 0.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 45        | 0.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 45        | 0.61%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 43        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4003      | 56.44%  |
| NVMe | 2140      | 30.17%  |
| RAID | 507       | 7.15%   |
| IDE  | 441       | 6.22%   |
| SCSI | 1         | 0.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 5118      | 84.51%  |
| AMD          | 916       | 15.13%  |
| ARM          | 15        | 0.25%   |
| CentaurHauls | 5         | 0.08%   |
| Unknown      | 2         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 357       | 5.89%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 149       | 2.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 122       | 2.01%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 98        | 1.62%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 89        | 1.47%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 88        | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 86        | 1.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 82        | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 79        | 1.3%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 79        | 1.3%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 75        | 1.24%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 73        | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 72        | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 65        | 1.07%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 62        | 1.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 61        | 1.01%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 61        | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 57        | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 56        | 0.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 53        | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 53        | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 48        | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 48        | 0.79%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 48        | 0.79%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 45        | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 41        | 0.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 41        | 0.68%   |
| Intel 12th Gen Core i7-12700H                 | 39        | 0.64%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 38        | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 36        | 0.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 36        | 0.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 35        | 0.58%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 35        | 0.58%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 35        | 0.58%   |
| Intel 12th Gen Core i5-1235U                  | 35        | 0.58%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 35        | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 34        | 0.56%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 33        | 0.54%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 30        | 0.49%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 30        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1428      | 23.56%  |
| Intel Core i7           | 1123      | 18.53%  |
| Other                   | 636       | 10.5%   |
| Intel Core 2 Duo        | 586       | 9.67%   |
| Intel Celeron           | 446       | 7.36%   |
| Intel Core i3           | 382       | 6.3%    |
| AMD Ryzen 5             | 258       | 4.26%   |
| AMD Ryzen 7             | 183       | 3.02%   |
| Intel Atom              | 167       | 2.76%   |
| Intel Pentium           | 110       | 1.82%   |
| Intel Core 2            | 75        | 1.24%   |
| AMD Ryzen 7 PRO         | 68        | 1.12%   |
| AMD A6                  | 47        | 0.78%   |
| Intel Pentium Dual-Core | 39        | 0.64%   |
| Intel Pentium M         | 37        | 0.61%   |
| AMD Ryzen 3             | 33        | 0.54%   |
| AMD A4                  | 31        | 0.51%   |
| Intel Genuine           | 29        | 0.48%   |
| AMD Ryzen 9             | 29        | 0.48%   |
| AMD Ryzen 5 PRO         | 27        | 0.45%   |
| AMD A8                  | 26        | 0.43%   |
| Intel Pentium Dual      | 24        | 0.4%    |
| AMD E                   | 20        | 0.33%   |
| AMD E1                  | 19        | 0.31%   |
| AMD A10                 | 17        | 0.28%   |
| Intel Pentium Silver    | 16        | 0.26%   |
| Intel Celeron M         | 16        | 0.26%   |
| AMD E2                  | 15        | 0.25%   |
| Intel Core i9           | 12        | 0.2%    |
| AMD Athlon              | 10        | 0.17%   |
| Intel Xeon              | 9         | 0.15%   |
| Intel Pentium 4         | 9         | 0.15%   |
| Intel Core m3           | 8         | 0.13%   |
| AMD Turion 64 X2 Mobile | 8         | 0.13%   |
| AMD Athlon II           | 8         | 0.13%   |
| AMD C-50                | 7         | 0.12%   |
| AMD A12                 | 7         | 0.12%   |
| AMD PRO A10             | 6         | 0.1%    |
| AMD C-60                | 6         | 0.1%    |
| Intel Core m7           | 5         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3192      | 52.66%  |
| 4      | 1746      | 28.81%  |
| 6      | 368       | 6.07%   |
| 8      | 317       | 5.23%   |
| 1      | 222       | 3.66%   |
| 10     | 92        | 1.52%   |
| 14     | 66        | 1.09%   |
| 12     | 47        | 0.78%   |
| 16     | 6         | 0.1%    |
| 24     | 2         | 0.03%   |
| 5      | 2         | 0.03%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 6053      | 99.98%  |
| 2      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4147      | 68.4%   |
| 1      | 1915      | 31.59%  |
| 4      | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5846      | 96.53%  |
| 32-bit         | 136       | 2.25%   |
| Unknown        | 72        | 1.19%   |
| 64-bit         | 2         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1460      | 23.49%  |
| 0x1067a    | 479       | 7.71%   |
| 0x306d4    | 280       | 4.51%   |
| 0x306a9    | 265       | 4.26%   |
| 0x206a7    | 257       | 4.14%   |
| 0x806c1    | 230       | 3.7%    |
| 0x806ec    | 227       | 3.65%   |
| 0x806e9    | 160       | 2.57%   |
| 0x806ea    | 157       | 2.53%   |
| 0x406e3    | 149       | 2.4%    |
| 0x40651    | 148       | 2.38%   |
| 0x30678    | 134       | 2.16%   |
| 0x406c4    | 111       | 1.79%   |
| 0x306c3    | 102       | 1.64%   |
| 0x906ea    | 91        | 1.46%   |
| 0x20655    | 85        | 1.37%   |
| 0xa0652    | 83        | 1.34%   |
| 0x0a50000c | 82        | 1.32%   |
| 0x906a3    | 78        | 1.26%   |
| 0x08108109 | 76        | 1.22%   |
| 0x6f6      | 69        | 1.11%   |
| 0x08608103 | 69        | 1.11%   |
| 0x08600106 | 65        | 1.05%   |
| 0x906a4    | 59        | 0.95%   |
| 0x706e5    | 55        | 0.88%   |
| 0x706a8    | 54        | 0.87%   |
| 0x10676    | 53        | 0.85%   |
| 0x6fd      | 50        | 0.8%    |
| 0x08108102 | 49        | 0.79%   |
| 0x906eb    | 48        | 0.77%   |
| 0x806eb    | 45        | 0.72%   |
| 0x506e3    | 43        | 0.69%   |
| 0x106ca    | 43        | 0.69%   |
| 0x906e9    | 42        | 0.68%   |
| 0x06006705 | 40        | 0.64%   |
| 0x806d1    | 38        | 0.61%   |
| 0x106c2    | 38        | 0.61%   |
| 0x506c9    | 37        | 0.6%    |
| 0x0600611a | 33        | 0.53%   |
| 0x6d8      | 32        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1082      | 17.83%  |
| Penryn           | 578       | 9.53%   |
| IvyBridge        | 368       | 6.07%   |
| SandyBridge      | 358       | 5.9%    |
| Haswell          | 344       | 5.67%   |
| Broadwell        | 325       | 5.36%   |
| Silvermont       | 313       | 5.16%   |
| TigerLake        | 297       | 4.9%    |
| Skylake          | 281       | 4.63%   |
| Unknown          | 260       | 4.29%   |
| Core             | 175       | 2.88%   |
| Westmere         | 158       | 2.6%    |
| Zen+             | 155       | 2.55%   |
| Alderlake Hybrid | 152       | 2.51%   |
| Zen 3            | 150       | 2.47%   |
| Zen 2            | 132       | 2.18%   |
| CometLake        | 120       | 1.98%   |
| Icelake          | 105       | 1.73%   |
| Bonnell          | 105       | 1.73%   |
| Excavator        | 101       | 1.66%   |
| Goldmont plus    | 96        | 1.58%   |
| P6               | 79        | 1.3%    |
| Goldmont         | 49        | 0.81%   |
| Bobcat           | 49        | 0.81%   |
| Zen              | 38        | 0.63%   |
| Puma             | 32        | 0.53%   |
| Jaguar           | 27        | 0.45%   |
| Piledriver       | 20        | 0.33%   |
| K8 Hammer        | 20        | 0.33%   |
| Tremont          | 18        | 0.3%    |
| K10 Llano        | 18        | 0.3%    |
| Nehalem          | 15        | 0.25%   |
| K10              | 15        | 0.25%   |
| NetBurst         | 14        | 0.23%   |
| K8 & K10 hybrid  | 10        | 0.16%   |
| Steamroller      | 7         | 0.12%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4424      | 60.21%  |
| Nvidia                           | 1687      | 22.96%  |
| AMD                              | 1218      | 16.58%  |
| Silicon Integrated Systems [SiS] | 10        | 0.14%   |
| Zhaoxin                          | 4         | 0.05%   |
| VIA Technologies                 | 2         | 0.03%   |
| S3 Graphics                      | 2         | 0.03%   |
| Neomagic                         | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 355       | 4.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 341       | 4.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 324       | 4.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 264       | 3.45%   |
| Intel UHD Graphics 620                                                                   | 232       | 3.03%   |
| Intel HD Graphics 620                                                                    | 205       | 2.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 198       | 2.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 192       | 2.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 180       | 2.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 164       | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 161       | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 160       | 2.09%   |
| Intel HD Graphics 6000                                                                   | 159       | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 152       | 1.99%   |
| Intel HD Graphics 5500                                                                   | 147       | 1.92%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 128       | 1.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 128       | 1.67%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 128       | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 124       | 1.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 122       | 1.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 119       | 1.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 119       | 1.56%   |
| AMD Lucienne                                                                             | 100       | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 94        | 1.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 87        | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 86        | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 86        | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 86        | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 86        | 1.12%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 74        | 0.97%   |
| Intel HD Graphics 630                                                                    | 58        | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 57        | 0.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 55        | 0.72%   |
| Intel HD Graphics 530                                                                    | 53        | 0.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 53        | 0.69%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 52        | 0.68%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 51        | 0.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 48        | 0.63%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 48        | 0.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 45        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 3196      | 52.67%  |
| Intel + Nvidia         | 1001      | 16.5%   |
| 1 x AMD                | 851       | 14.02%  |
| 1 x Nvidia             | 572       | 9.43%   |
| Intel + AMD            | 186       | 3.07%   |
| AMD + Nvidia           | 112       | 1.85%   |
| 2 x AMD                | 69        | 1.14%   |
| Other                  | 29        | 0.48%   |
| 2 x Intel              | 28        | 0.46%   |
| 1 x SiS                | 10        | 0.16%   |
| 1 x Zhaoxin            | 4         | 0.07%   |
| 2 x Nvidia             | 2         | 0.03%   |
| 1 x VIA                | 2         | 0.03%   |
| 1 x S3 Graphics        | 2         | 0.03%   |
| Intel + 2 x Nvidia     | 2         | 0.03%   |
| 2 x Intel + 1 x Nvidia | 1         | 0.02%   |
| 1 x Neomagic           | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5268      | 85.97%  |
| Proprietary | 455       | 7.42%   |
| Unknown     | 405       | 6.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 4466      | 72.82%  |
| 0.01-0.5       | 846       | 13.79%  |
| 1.01-2.0       | 335       | 5.46%   |
| 3.01-4.0       | 201       | 3.28%   |
| 0.51-1.0       | 181       | 2.95%   |
| 5.01-6.0       | 50        | 0.82%   |
| 7.01-8.0       | 37        | 0.6%    |
| 2.01-3.0       | 11        | 0.18%   |
| 8.01-16.0      | 3         | 0.05%   |
| More than 64.0 | 1         | 0.02%   |
| 16.01-24.0     | 1         | 0.02%   |
| 0              | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1204      | 18.32%  |
| BOE                     | 888       | 13.51%  |
| LG Display              | 770       | 11.72%  |
| Chimei Innolux          | 767       | 11.67%  |
| Apple                   | 679       | 10.33%  |
| Samsung Electronics     | 547       | 8.32%   |
| Dell                    | 177       | 2.69%   |
| Lenovo                  | 155       | 2.36%   |
| Sharp                   | 143       | 2.18%   |
| Goldstar                | 127       | 1.93%   |
| Chi Mei Optoelectronics | 105       | 1.6%    |
| InfoVision              | 99        | 1.51%   |
| PANDA                   | 82        | 1.25%   |
| Hewlett-Packard         | 78        | 1.19%   |
| Philips                 | 61        | 0.93%   |
| BenQ                    | 61        | 0.93%   |
| AOC                     | 52        | 0.79%   |
| CSO                     | 47        | 0.72%   |
| Acer                    | 45        | 0.68%   |
| LG Philips              | 43        | 0.65%   |
| Iiyama                  | 42        | 0.64%   |
| HannStar                | 39        | 0.59%   |
| Ancor Communications    | 35        | 0.53%   |
| ViewSonic               | 25        | 0.38%   |
| Unknown                 | 25        | 0.38%   |
| Sony                    | 20        | 0.3%    |
| CPT                     | 19        | 0.29%   |
| Eizo                    | 16        | 0.24%   |
| ASUSTek Computer        | 16        | 0.24%   |
| Quanta Display          | 10        | 0.15%   |
| Panasonic               | 9         | 0.14%   |
| NEC Computers           | 9         | 0.14%   |
| MSI                     | 9         | 0.14%   |
| LGD                     | 7         | 0.11%   |
| Pixio                   | 6         | 0.09%   |
| InnoLux Display         | 6         | 0.09%   |
| Toshiba                 | 5         | 0.08%   |
| TMX                     | 5         | 0.08%   |
| Denver                  | 5         | 0.08%   |
| Unknown                 | 5         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 210       | 3.16%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 191       | 2.87%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 70        | 1.05%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 54        | 0.81%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 48        | 0.72%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 48        | 0.72%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 45        | 0.68%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 42        | 0.63%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 38        | 0.57%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 35        | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 32        | 0.48%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 32        | 0.48%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 31        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 30        | 0.45%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 29        | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 27        | 0.41%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 26        | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 25        | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 24        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 23        | 0.35%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 23        | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 22        | 0.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 21        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 20        | 0.3%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 20        | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 19        | 0.29%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 19        | 0.29%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 18        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 18        | 0.27%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 18        | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 17        | 0.26%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 16        | 0.24%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 16        | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 16        | 0.24%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 16        | 0.24%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 16        | 0.24%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 15        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 15        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 15        | 0.23%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch     | 15        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2449      | 39.53%  |
| 1366x768 (WXGA)    | 1656      | 26.73%  |
| 1280x800 (WXGA)    | 614       | 9.91%   |
| 1600x900 (HD+)     | 250       | 4.03%   |
| 3840x2160 (4K)     | 194       | 3.13%   |
| 1920x1200 (WUXGA)  | 168       | 2.71%   |
| 1440x900 (WXGA+)   | 162       | 2.61%   |
| 2560x1440 (QHD)    | 147       | 2.37%   |
| 1024x600           | 80        | 1.29%   |
| 2560x1600          | 62        | 1%      |
| 1680x1050 (WSXGA+) | 44        | 0.71%   |
| 1280x1024 (SXGA)   | 44        | 0.71%   |
| 3840x2400          | 34        | 0.55%   |
| 2880x1800          | 31        | 0.5%    |
| 2560x1080          | 31        | 0.5%    |
| 3440x1440          | 30        | 0.48%   |
| 1360x768           | 22        | 0.36%   |
| 2288x1287          | 21        | 0.34%   |
| 1024x768 (XGA)     | 20        | 0.32%   |
| 3200x1800 (QHD+)   | 13        | 0.21%   |
| 2160x1440          | 12        | 0.19%   |
| 2256x1504          | 11        | 0.18%   |
| 1600x1200          | 10        | 0.16%   |
| Unknown            | 10        | 0.16%   |
| 3840x1080          | 7         | 0.11%   |
| 3072x1920          | 6         | 0.1%    |
| 1400x1050          | 6         | 0.1%    |
| 1920x540           | 5         | 0.08%   |
| 1280x720 (HD)      | 5         | 0.08%   |
| 3456x2160          | 4         | 0.06%   |
| 3200x2000          | 4         | 0.06%   |
| 1024x576           | 4         | 0.06%   |
| 800x1280           | 3         | 0.05%   |
| 3840x1200          | 3         | 0.05%   |
| 3840x1100          | 3         | 0.05%   |
| 2880x1920          | 3         | 0.05%   |
| 2880x1620          | 3         | 0.05%   |
| 2304x1440          | 3         | 0.05%   |
| 2240x1400          | 3         | 0.05%   |
| 1920x1280          | 3         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2083      | 31.72%  |
| 13      | 1374      | 20.92%  |
| 14      | 863       | 13.14%  |
| 17      | 358       | 5.45%   |
| 11      | 352       | 5.36%   |
| 24      | 233       | 3.55%   |
| 12      | 225       | 3.43%   |
| 27      | 182       | 2.77%   |
| 23      | 148       | 2.25%   |
| 21      | 128       | 1.95%   |
| 16      | 90        | 1.37%   |
| 10      | 81        | 1.23%   |
| 18      | 55        | 0.84%   |
| Unknown | 55        | 0.84%   |
| 34      | 49        | 0.75%   |
| 31      | 47        | 0.72%   |
| 19      | 38        | 0.58%   |
| 22      | 23        | 0.35%   |
| 142     | 21        | 0.32%   |
| 20      | 20        | 0.3%    |
| 25      | 19        | 0.29%   |
| 32      | 13        | 0.2%    |
| 72      | 12        | 0.18%   |
| 40      | 11        | 0.17%   |
| 54      | 10        | 0.15%   |
| 8       | 10        | 0.15%   |
| 84      | 8         | 0.12%   |
| 29      | 8         | 0.12%   |
| 28      | 7         | 0.11%   |
| 49      | 5         | 0.08%   |
| 46      | 5         | 0.08%   |
| 26      | 5         | 0.08%   |
| 48      | 4         | 0.06%   |
| 52      | 3         | 0.05%   |
| 43      | 3         | 0.05%   |
| 33      | 3         | 0.05%   |
| 35      | 2         | 0.03%   |
| 7       | 2         | 0.03%   |
| 86      | 1         | 0.02%   |
| 69      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3460      | 53.14%  |
| 201-300        | 1543      | 23.7%   |
| 501-600        | 532       | 8.17%   |
| 351-400        | 423       | 6.5%    |
| 401-500        | 240       | 3.69%   |
| 601-700        | 86        | 1.32%   |
| 701-800        | 65        | 1%      |
| Unknown        | 55        | 0.84%   |
| 1001-1500      | 34        | 0.52%   |
| More than 2000 | 21        | 0.32%   |
| 1501-2000      | 21        | 0.32%   |
| 801-900        | 15        | 0.23%   |
| 101-200        | 11        | 0.17%   |
| 1-100          | 3         | 0.05%   |
| 901-1000       | 2         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4468      | 76.19%  |
| 16/10   | 1131      | 19.29%  |
| 21/9    | 55        | 0.94%   |
| 3/2     | 45        | 0.77%   |
| 5/4     | 44        | 0.75%   |
| 4/3     | 41        | 0.7%    |
| Unknown | 35        | 0.6%    |
| 1.00    | 21        | 0.36%   |
| 32/9    | 6         | 0.1%    |
| 2.65    | 5         | 0.09%   |
| 3.40    | 3         | 0.05%   |
| 3.20    | 3         | 0.05%   |
| 0.67    | 2         | 0.03%   |
| 6/5     | 1         | 0.02%   |
| 3.73    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2081      | 31.77%  |
| 81-90          | 1866      | 28.48%  |
| 201-250        | 413       | 6.3%    |
| 71-80          | 361       | 5.51%   |
| 51-60          | 355       | 5.42%   |
| 121-130        | 292       | 4.46%   |
| 61-70          | 219       | 3.34%   |
| 301-350        | 186       | 2.84%   |
| 351-500        | 122       | 1.86%   |
| 251-300        | 100       | 1.53%   |
| 151-200        | 92        | 1.4%    |
| 41-50          | 81        | 1.24%   |
| 111-120        | 78        | 1.19%   |
| 141-150        | 74        | 1.13%   |
| More than 1000 | 62        | 0.95%   |
| Unknown        | 55        | 0.84%   |
| 131-140        | 46        | 0.7%    |
| 501-1000       | 29        | 0.44%   |
| 91-100         | 25        | 0.38%   |
| 1-40           | 14        | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2770      | 43.13%  |
| 101-120       | 2012      | 31.32%  |
| 51-100        | 907       | 14.12%  |
| 161-240       | 453       | 7.05%   |
| More than 240 | 155       | 2.41%   |
| 1-50          | 71        | 1.11%   |
| Unknown       | 55        | 0.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4800      | 77.54%  |
| 2     | 906       | 14.64%  |
| 0     | 379       | 6.12%   |
| 3     | 101       | 1.63%   |
| 4     | 3         | 0.05%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3093      | 31.91%  |
| Realtek Semiconductor             | 2727      | 28.13%  |
| Qualcomm Atheros                  | 1196      | 12.34%  |
| Broadcom                          | 840       | 8.67%   |
| Nvidia                            | 381       | 3.93%   |
| Broadcom Limited                  | 283       | 2.92%   |
| Marvell Technology Group          | 167       | 1.72%   |
| MediaTek                          | 165       | 1.7%    |
| ASIX Electronics                  | 75        | 0.77%   |
| Ralink                            | 69        | 0.71%   |
| TP-Link                           | 55        | 0.57%   |
| Qualcomm                          | 47        | 0.48%   |
| Sierra Wireless                   | 45        | 0.46%   |
| Samsung Electronics               | 44        | 0.45%   |
| Lenovo                            | 44        | 0.45%   |
| Dell                              | 43        | 0.44%   |
| Ralink Technology                 | 38        | 0.39%   |
| Xiaomi                            | 37        | 0.38%   |
| JMicron Technology                | 34        | 0.35%   |
| Ericsson Business Mobile Networks | 30        | 0.31%   |
| DisplayLink                       | 28        | 0.29%   |
| Hewlett-Packard                   | 22        | 0.23%   |
| Huawei Technologies               | 19        | 0.2%    |
| Fibocom                           | 18        | 0.19%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.14%   |
| NetGear                           | 10        | 0.1%    |
| Qualcomm Atheros Communications   | 9         | 0.09%   |
| OPPO Electronics                  | 9         | 0.09%   |
| Cypress Semiconductor             | 9         | 0.09%   |
| Attansic Technology               | 8         | 0.08%   |
| ASUSTek Computer                  | 8         | 0.08%   |
| Motorola PCS                      | 7         | 0.07%   |
| Microchip Technology              | 7         | 0.07%   |
| Google                            | 7         | 0.07%   |
| ICS Advent                        | 6         | 0.06%   |
| Edimax Technology                 | 6         | 0.06%   |
| D-Link                            | 6         | 0.06%   |
| Apple                             | 6         | 0.06%   |
| U-Blox                            | 5         | 0.05%   |
| AMD                               | 5         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1637      | 14.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 437       | 3.76%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 371       | 3.2%    |
| Nvidia MCP79 Ethernet                                                                 | 368       | 3.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 274       | 2.36%   |
| Intel Wireless 8265 / 8275                                                            | 254       | 2.19%   |
| Intel Wireless 7260                                                                   | 245       | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 242       | 2.08%   |
| Intel Wireless 7265                                                                   | 237       | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 230       | 1.98%   |
| Intel Wi-Fi 6 AX200                                                                   | 220       | 1.9%    |
| Intel Wi-Fi 6 AX201                                                                   | 206       | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 170       | 1.46%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 167       | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 159       | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 151       | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 148       | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 146       | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 144       | 1.24%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 143       | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 141       | 1.21%   |
| Intel Wireless 8260                                                                   | 138       | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 121       | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 113       | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 109       | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 107       | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 101       | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 93        | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 92        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 87        | 0.75%   |
| Intel Ethernet Connection I219-LM                                                     | 79        | 0.68%   |
| Intel Wireless 3165                                                                   | 78        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                                                  | 73        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 70        | 0.6%    |
| Intel Ethernet Connection I218-LM                                                     | 69        | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                                         | 62        | 0.53%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 61        | 0.53%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 60        | 0.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 59        | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 58        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2927      | 47.18%  |
| Qualcomm Atheros                      | 1057      | 17.04%  |
| Realtek Semiconductor                 | 786       | 12.67%  |
| Broadcom                              | 709       | 11.43%  |
| Broadcom Limited                      | 234       | 3.77%   |
| MediaTek                              | 154       | 2.48%   |
| Ralink                                | 69        | 1.11%   |
| Sierra Wireless                       | 45        | 0.73%   |
| Ralink Technology                     | 38        | 0.61%   |
| TP-Link                               | 34        | 0.55%   |
| Qualcomm                              | 32        | 0.52%   |
| Dell                                  | 31        | 0.5%    |
| Fibocom                               | 18        | 0.29%   |
| NetGear                               | 10        | 0.16%   |
| Qualcomm Atheros Communications       | 9         | 0.15%   |
| ASUSTek Computer                      | 8         | 0.13%   |
| Edimax Technology                     | 6         | 0.1%    |
| Hewlett-Packard                       | 5         | 0.08%   |
| Ericsson Business Mobile Networks     | 5         | 0.08%   |
| D-Link                                | 4         | 0.06%   |
| Microsoft                             | 3         | 0.05%   |
| D-Link System                         | 3         | 0.05%   |
| Wilocity                              | 2         | 0.03%   |
| Quectel Wireless Solutions            | 2         | 0.03%   |
| Linksys                               | 2         | 0.03%   |
| Belkin Components                     | 2         | 0.03%   |
| 3Com                                  | 2         | 0.03%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Marvell Technology Group              | 1         | 0.02%   |
| Cinterion                             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 371       | 5.95%   |
| Intel Wireless 8265 / 8275                                                            | 254       | 4.07%   |
| Intel Wireless 7260                                                                   | 245       | 3.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 242       | 3.88%   |
| Intel Wireless 7265                                                                   | 237       | 3.8%    |
| Intel Wi-Fi 6 AX200                                                                   | 220       | 3.53%   |
| Intel Wi-Fi 6 AX201                                                                   | 206       | 3.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 170       | 2.73%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 167       | 2.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 159       | 2.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 151       | 2.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 148       | 2.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 146       | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 144       | 2.31%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 143       | 2.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 141       | 2.26%   |
| Intel Wireless 8260                                                                   | 138       | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 121       | 1.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 113       | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 109       | 1.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 107       | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 93        | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 92        | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 87        | 1.39%   |
| Intel Wireless 3165                                                                   | 78        | 1.25%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 61        | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 59        | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 58        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 58        | 0.93%   |
| Intel Wireless-AC 9260                                                                | 58        | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 58        | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 56        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                                         | 54        | 0.87%   |
| Intel Centrino Ultimate-N 6300                                                        | 50        | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 46        | 0.74%   |
| Intel Wireless 3160                                                                   | 44        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 41        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 40        | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 40        | 0.64%   |
| Intel Centrino Advanced-N 6200                                                        | 38        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2421      | 47.09%  |
| Intel                            | 1250      | 24.31%  |
| Nvidia                           | 381       | 7.41%   |
| Qualcomm Atheros                 | 278       | 5.41%   |
| Broadcom                         | 185       | 3.6%    |
| Marvell Technology Group         | 166       | 3.23%   |
| ASIX Electronics                 | 75        | 1.46%   |
| Broadcom Limited                 | 53        | 1.03%   |
| Lenovo                           | 44        | 0.86%   |
| Xiaomi                           | 37        | 0.72%   |
| JMicron Technology               | 34        | 0.66%   |
| DisplayLink                      | 28        | 0.54%   |
| Samsung Electronics              | 24        | 0.47%   |
| TP-Link                          | 21        | 0.41%   |
| Silicon Integrated Systems [SiS] | 14        | 0.27%   |
| Qualcomm                         | 14        | 0.27%   |
| Huawei Technologies              | 13        | 0.25%   |
| MediaTek                         | 11        | 0.21%   |
| OPPO Electronics                 | 9         | 0.18%   |
| Cypress Semiconductor            | 9         | 0.18%   |
| Hewlett-Packard                  | 8         | 0.16%   |
| Attansic Technology              | 8         | 0.16%   |
| Microchip Technology             | 7         | 0.14%   |
| Google                           | 7         | 0.14%   |
| ICS Advent                       | 6         | 0.12%   |
| Apple                            | 6         | 0.12%   |
| Motorola PCS                     | 5         | 0.1%    |
| Spreadtrum Communications        | 4         | 0.08%   |
| VIA Technologies                 | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.04%   |
| National Semiconductor           | 2         | 0.04%   |
| LG Electronics                   | 2         | 0.04%   |
| D-Link                           | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| MosChip Semiconductor            | 1         | 0.02%   |
| Linksys                          | 1         | 0.02%   |
| LeEco                            | 1         | 0.02%   |
| HTC (High Tech Computer)         | 1         | 0.02%   |
| HMD Global                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1637      | 31.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 437       | 8.39%   |
| Nvidia MCP79 Ethernet                                             | 368       | 7.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 274       | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 230       | 4.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 101       | 1.94%   |
| Intel Ethernet Connection I219-LM                                 | 79        | 1.52%   |
| Intel Ethernet Connection (4) I219-V                              | 73        | 1.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 70        | 1.34%   |
| Intel Ethernet Connection I218-LM                                 | 69        | 1.32%   |
| ASIX AX88179 Gigabit Ethernet                                     | 62        | 1.19%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 60        | 1.15%   |
| Intel 82577LM Gigabit Network Connection                          | 52        | 1%      |
| Intel Ethernet Connection (6) I219-V                              | 45        | 0.86%   |
| Intel 82567LM Gigabit Network Connection                          | 45        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 44        | 0.84%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 44        | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 41        | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 39        | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 38        | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 38        | 0.73%   |
| Intel Ethernet Connection (13) I219-V                             | 37        | 0.71%   |
| Intel Ethernet Connection (10) I219-V                             | 30        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 29        | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 28        | 0.54%   |
| Intel Ethernet Connection (16) I219-V                             | 27        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 26        | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 25        | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 25        | 0.48%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 25        | 0.48%   |
| Intel 82579V Gigabit Network Connection                           | 25        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 22        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 22        | 0.42%   |
| Intel Ethernet Connection (16) I219-LM                            | 22        | 0.42%   |
| Intel Ethernet Connection (13) I219-LM                            | 22        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21        | 0.4%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 18        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5927      | 54.05%  |
| Ethernet | 4878      | 44.49%  |
| Modem    | 151       | 1.38%   |
| Unknown  | 9         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4561      | 70.98%  |
| Ethernet | 1864      | 29.01%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4380      | 72.22%  |
| 1     | 1532      | 25.26%  |
| 0     | 97        | 1.6%    |
| 3     | 54        | 0.89%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4967      | 80.76%  |
| Yes  | 1183      | 19.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2252      | 45.71%  |
| Apple                           | 661       | 13.42%  |
| Realtek Semiconductor           | 466       | 9.46%   |
| Qualcomm Atheros Communications | 403       | 8.18%   |
| Broadcom                        | 225       | 4.57%   |
| IMC Networks                    | 211       | 4.28%   |
| Lite-On Technology              | 184       | 3.73%   |
| Foxconn / Hon Hai               | 150       | 3.04%   |
| Dell                            | 73        | 1.48%   |
| Hewlett-Packard                 | 58        | 1.18%   |
| Cambridge Silicon Radio         | 50        | 1.01%   |
| Toshiba                         | 34        | 0.69%   |
| Realtek                         | 33        | 0.67%   |
| ASUSTek Computer                | 30        | 0.61%   |
| Ralink                          | 21        | 0.43%   |
| Foxconn International           | 13        | 0.26%   |
| USI                             | 12        | 0.24%   |
| Ralink Technology               | 9         | 0.18%   |
| MediaTek                        | 8         | 0.16%   |
| Alps Electric                   | 8         | 0.16%   |
| Taiyo Yuden                     | 5         | 0.1%    |
| Fujitsu                         | 4         | 0.08%   |
| Opticis                         | 2         | 0.04%   |
| Micro Star International        | 2         | 0.04%   |
| Chicony Electronics             | 2         | 0.04%   |
| Askey Computer                  | 2         | 0.04%   |
| Unknown                         | 1         | 0.02%   |
| TP-Link                         | 1         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Marvell Semiconductor           | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 931       | 18.88%  |
| Intel AX201 Bluetooth                               | 422       | 8.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 353       | 7.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 345       | 7%      |
| Realtek Bluetooth Radio                             | 270       | 5.47%   |
| Qualcomm Atheros  Bluetooth Device                  | 224       | 4.54%   |
| Intel AX200 Bluetooth                               | 209       | 4.24%   |
| Apple Bluetooth USB Host Controller                 | 170       | 3.45%   |
| Intel Bluetooth Device                              | 117       | 2.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 96        | 1.95%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 1.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 63        | 1.28%   |
| IMC Networks Wireless_Device                        | 61        | 1.24%   |
| Realtek 802.11ac WLAN Adapter                       | 57        | 1.16%   |
| IMC Networks Bluetooth Radio                        | 55        | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                  | 55        | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 54        | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 54        | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 53        | 1.07%   |
| Apple Bluetooth Host Controller                     | 53        | 1.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 50        | 1.01%   |
| Intel AX210 Bluetooth                               | 49        | 0.99%   |
| IMC Networks Bluetooth Device                       | 48        | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 46        | 0.93%   |
| Broadcom BCM2045B (BDC-2.1)                         | 46        | 0.93%   |
| Lite-On Bluetooth Device                            | 43        | 0.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 42        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 40        | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 40        | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 36        | 0.73%   |
| Lite-On Wireless_Device                             | 30        | 0.61%   |
| Realtek 802.11ac WLAN Adapter                       | 29        | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 28        | 0.57%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 28        | 0.57%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 0.51%   |
| Dell DW375 Bluetooth Module                         | 23        | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 22        | 0.45%   |
| Dell BCM20702A0 Bluetooth Module                    | 22        | 0.45%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 20        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4651      | 65.23%  |
| Nvidia                                       | 1027      | 14.4%   |
| AMD                                          | 1004      | 14.08%  |
| C-Media Electronics                          | 53        | 0.74%   |
| Lenovo                                       | 43        | 0.6%    |
| Realtek Semiconductor                        | 40        | 0.56%   |
| Logitech                                     | 38        | 0.53%   |
| Texas Instruments                            | 22        | 0.31%   |
| GN Netcom                                    | 21        | 0.29%   |
| Plantronics                                  | 19        | 0.27%   |
| Hewlett-Packard                              | 17        | 0.24%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.21%   |
| JMTek                                        | 13        | 0.18%   |
| ASUSTek Computer                             | 13        | 0.18%   |
| Generalplus Technology                       | 12        | 0.17%   |
| Creative Technology                          | 9         | 0.13%   |
| Kingston Technology                          | 8         | 0.11%   |
| Focusrite-Novation                           | 7         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 6         | 0.08%   |
| CMX Systems                                  | 5         | 0.07%   |
| Zhaoxin                                      | 4         | 0.06%   |
| SteelSeries ApS                              | 4         | 0.06%   |
| RODE Microphones                             | 4         | 0.06%   |
| Razer USA                                    | 4         | 0.06%   |
| Dell                                         | 4         | 0.06%   |
| Apple                                        | 4         | 0.06%   |
| Yamaha                                       | 3         | 0.04%   |
| VIA Technologies                             | 3         | 0.04%   |
| ULi Electronics                              | 3         | 0.04%   |
| Sennheiser Communications                    | 3         | 0.04%   |
| Microsoft                                    | 3         | 0.04%   |
| BEHRINGER International                      | 3         | 0.04%   |
| XMOS                                         | 2         | 0.03%   |
| Thomann                                      | 2         | 0.03%   |
| Sony                                         | 2         | 0.03%   |
| SAVITECH                                     | 2         | 0.03%   |
| M-Audio                                      | 2         | 0.03%   |
| Huawei Technologies                          | 2         | 0.03%   |
| Fujitsu                                      | 2         | 0.03%   |
| ESS Technology                               | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 688       | 7.99%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 597       | 6.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 436       | 5.06%   |
| Nvidia MCP79 High Definition Audio                                                                | 370       | 4.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 327       | 3.8%    |
| Intel Broadwell-U Audio Controller                                                                | 325       | 3.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 321       | 3.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 295       | 3.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 289       | 3.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 201       | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 198       | 2.3%    |
| Intel 8 Series HD Audio Controller                                                                | 198       | 2.3%    |
| Intel Cannon Lake PCH cAVS                                                                        | 191       | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 188       | 2.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 185       | 2.15%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 179       | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 171       | 1.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 169       | 1.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 163       | 1.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 145       | 1.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 129       | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 126       | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 125       | 1.45%   |
| AMD FCH Azalia Controller                                                                         | 122       | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 113       | 1.31%   |
| Intel Comet Lake PCH cAVS                                                                         | 108       | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                                          | 107       | 1.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 96        | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 96        | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 87        | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 67        | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 66        | 0.77%   |
| Intel CM238 HD Audio Controller                                                                   | 65        | 0.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 64        | 0.74%   |
| Nvidia Audio device                                                                               | 61        | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 61        | 0.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 61        | 0.71%   |
| AMD High Definition Audio Controller                                                              | 53        | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 50        | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 49        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1577      | 27.28%  |
| SK hynix            | 1533      | 26.52%  |
| Micron Technology   | 692       | 11.97%  |
| Kingston            | 405       | 7.01%   |
| Unknown             | 380       | 6.57%   |
| Crucial             | 286       | 4.95%   |
| Elpida              | 154       | 2.66%   |
| Ramaxel Technology  | 117       | 2.02%   |
| A-DATA Technology   | 112       | 1.94%   |
| Corsair             | 62        | 1.07%   |
| Nanya Technology    | 58        | 1%      |
| Smart               | 47        | 0.81%   |
| Unknown (ABCD)      | 45        | 0.78%   |
| G.Skill             | 29        | 0.5%    |
| Unknown             | 28        | 0.48%   |
| GOODRAM             | 26        | 0.45%   |
| Transcend           | 23        | 0.4%    |
| Team                | 22        | 0.38%   |
| Teikon              | 13        | 0.22%   |
| Silicon Power       | 9         | 0.16%   |
| Patriot             | 9         | 0.16%   |
| ASint Technology    | 9         | 0.16%   |
| Apacer              | 9         | 0.16%   |
| 4ea5                | 9         | 0.16%   |
| ff                  | 8         | 0.14%   |
| 48spaces            | 8         | 0.14%   |
| Timetec             | 6         | 0.1%    |
| Smart Brazil        | 6         | 0.1%    |
| Qimonda             | 6         | 0.1%    |
| fef5                | 5         | 0.09%   |
| AMD                 | 5         | 0.09%   |
| PNY                 | 4         | 0.07%   |
| Neo Forza           | 4         | 0.07%   |
| Wilk                | 3         | 0.05%   |
| Kllisre             | 3         | 0.05%   |
| Infineon            | 3         | 0.05%   |
| Goldkey             | 3         | 0.05%   |
| CSX                 | 3         | 0.05%   |
| Avant               | 3         | 0.05%   |
| 2B0B00000000        | 3         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 265       | 4.35%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.12%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 68        | 1.12%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 62        | 1.02%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 58        | 0.95%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 51        | 0.84%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 50        | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 48        | 0.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 48        | 0.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 47        | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 47        | 0.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 46        | 0.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 46        | 0.76%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 44        | 0.72%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 44        | 0.72%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 43        | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 42        | 0.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 41        | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 41        | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 39        | 0.64%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 38        | 0.62%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 38        | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 37        | 0.61%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 32        | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 32        | 0.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 31        | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.49%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 29        | 0.48%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 29        | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 28        | 0.46%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 28        | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 28        | 0.46%   |
| Unknown                                                          | 28        | 0.46%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 27        | 0.44%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 27        | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 26        | 0.43%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.41%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 2037      | 40.88%  |
| DDR3    | 1592      | 31.95%  |
| DDR2    | 639       | 12.82%  |
| LPDDR3  | 198       | 3.97%   |
| LPDDR4  | 194       | 3.89%   |
| SDRAM   | 99        | 1.99%   |
| DDR5    | 67        | 1.34%   |
| LPDDR5  | 60        | 1.2%    |
| DDR     | 49        | 0.98%   |
| Unknown | 35        | 0.7%    |
| DRAM    | 12        | 0.24%   |
| RAM     | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 4463      | 89.24%  |
| Row Of Chips | 379       | 7.58%   |
| Unknown      | 107       | 2.14%   |
| Chip         | 33        | 0.66%   |
| DIMM         | 19        | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1817      | 33.46%  |
| 4096  | 1344      | 24.75%  |
| 2048  | 808       | 14.88%  |
| 16384 | 650       | 11.97%  |
| 1024  | 592       | 10.9%   |
| 32768 | 148       | 2.73%   |
| 512   | 49        | 0.9%    |
| 256   | 18        | 0.33%   |
| 128   | 2         | 0.04%   |
| 8072  | 1         | 0.02%   |
| 1536  | 1         | 0.02%   |
| 384   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1126      | 21.11%  |
| 3200    | 991       | 18.58%  |
| 2667    | 884       | 16.57%  |
| 800     | 403       | 7.56%   |
| 2400    | 319       | 5.98%   |
| 2133    | 235       | 4.41%   |
| 1334    | 218       | 4.09%   |
| 667     | 197       | 3.69%   |
| 1333    | 160       | 3%      |
| Unknown | 125       | 2.34%   |
| 1867    | 96        | 1.8%    |
| 1067    | 73        | 1.37%   |
| 4267    | 72        | 1.35%   |
| 4800    | 59        | 1.11%   |
| 6400    | 57        | 1.07%   |
| 3266    | 47        | 0.88%   |
| 4199    | 38        | 0.71%   |
| 1066    | 34        | 0.64%   |
| 533     | 29        | 0.54%   |
| 2048    | 24        | 0.45%   |
| 975     | 24        | 0.45%   |
| 8400    | 18        | 0.34%   |
| 4266    | 18        | 0.34%   |
| 5600    | 12        | 0.22%   |
| 400     | 12        | 0.22%   |
| 3733    | 10        | 0.19%   |
| 333     | 10        | 0.19%   |
| 1866    | 8         | 0.15%   |
| 266     | 8         | 0.15%   |
| 2933    | 4         | 0.07%   |
| 2666    | 4         | 0.07%   |
| 7500    | 3         | 0.06%   |
| 933     | 3         | 0.06%   |
| 1776    | 2         | 0.04%   |
| 1639    | 2         | 0.04%   |
| 7467    | 1         | 0.02%   |
| 3000    | 1         | 0.02%   |
| 2134    | 1         | 0.02%   |
| 1596    | 1         | 0.02%   |
| 666     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 15        | 34.88%  |
| Canon                 | 6         | 13.95%  |
| Brother Industries    | 6         | 13.95%  |
| Xerox                 | 4         | 9.3%    |
| Samsung Electronics   | 3         | 6.98%   |
| Seiko Epson           | 2         | 4.65%   |
| Kyocera               | 2         | 4.65%   |
| Xiaomi                | 1         | 2.33%   |
| STMicroelectronics    | 1         | 2.33%   |
| Pantum                | 1         | 2.33%   |
| Lexmark International | 1         | 2.33%   |
| Dymo-CoStar           | 1         | 2.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 8.89%   |
| Brother HL-L2340D series                                  | 2         | 4.44%   |
| Xiaomi MiMouse 2                                          | 1         | 2.22%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.22%   |
| Seiko Epson Printer                                       | 1         | 2.22%   |
| Seiko Epson L120 Series                                   | 1         | 2.22%   |
| Samsung SCX-472x Series                                   | 1         | 2.22%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.22%   |
| Samsung CLX-3300 Series                                   | 1         | 2.22%   |
| Pantum P2500W series                                      | 1         | 2.22%   |
| Lexmark International E260dn                              | 1         | 2.22%   |
| Kyocera FS-1120MFP                                        | 1         | 2.22%   |
| Kyocera ECOSYS P2335d                                     | 1         | 2.22%   |
| HP Printing Support                                       | 1         | 2.22%   |
| HP OfficeJet 3830 series                                  | 1         | 2.22%   |
| HP LaserJet P1102                                         | 1         | 2.22%   |
| HP LaserJet P1005                                         | 1         | 2.22%   |
| HP LaserJet 1200                                          | 1         | 2.22%   |
| HP LaserJet 1160 series                                   | 1         | 2.22%   |
| HP LaserJet 1150                                          | 1         | 2.22%   |
| HP LaserJet 1022                                          | 1         | 2.22%   |
| HP LaserJet 1020                                          | 1         | 2.22%   |
| HP LaserJet 1018                                          | 1         | 2.22%   |
| HP Ink Tank 110 series                                    | 1         | 2.22%   |
| HP EWS UPD                                                | 1         | 2.22%   |
| HP DeskJet 2700 series                                    | 1         | 2.22%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 2.22%   |
| HP Deskjet 2540 series                                    | 1         | 2.22%   |
| HP DeskJet 2130 series                                    | 1         | 2.22%   |
| Dymo-CoStar DYMO XTL                                      | 1         | 2.22%   |
| Dymo-CoStar DYMO LabelWriter 4XL                          | 1         | 2.22%   |
| Canon PIXMA MX920 Series                                  | 1         | 2.22%   |
| Canon LiDE 400                                            | 1         | 2.22%   |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 2.22%   |
| Canon LBP2900                                             | 1         | 2.22%   |
| Canon G3010 series                                        | 1         | 2.22%   |
| Canon CanoScan LiDE 300                                   | 1         | 2.22%   |
| Brother PT-9500PC                                         | 1         | 2.22%   |
| Brother MFC-L2707DW                                       | 1         | 2.22%   |
| Brother HL-2240D series                                   | 1         | 2.22%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 7         | 43.75%  |
| Seiko Epson        | 5         | 31.25%  |
| Mustek Systems     | 2         | 12.5%   |
| Ultima Electronics | 1         | 6.25%   |
| Hewlett-Packard    | 1         | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                                                               | 2         | 12.5%   |
| Canon CanoScan LiDE 110                                                               | 2         | 12.5%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 6.25%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 6.25%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 6.25%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 6.25%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1         | 6.25%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1         | 6.25%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 6.25%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 1         | 6.25%   |
| HP Scanjet 200                                                                        | 1         | 6.25%   |
| Canon CanoScan LIDE 25                                                                | 1         | 6.25%   |
| Canon CanoScan LiDE 220                                                               | 1         | 6.25%   |
| Canon CanoScan LiDE 210                                                               | 1         | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1170      | 24.02%  |
| IMC Networks                           | 529       | 10.86%  |
| Microdia                               | 386       | 7.93%   |
| Quanta                                 | 379       | 7.78%   |
| Realtek Semiconductor                  | 370       | 7.6%    |
| Bison Electronics                      | 354       | 7.27%   |
| Sunplus Innovation Technology          | 269       | 5.52%   |
| Cheng Uei Precision Industry (Foxlink) | 153       | 3.14%   |
| Suyin                                  | 143       | 2.94%   |
| Acer                                   | 129       | 2.65%   |
| Lite-On Technology                     | 124       | 2.55%   |
| Luxvisions Innotech Limited            | 119       | 2.44%   |
| Syntek                                 | 115       | 2.36%   |
| Apple                                  | 89        | 1.83%   |
| Logitech                               | 69        | 1.42%   |
| Silicon Motion                         | 65        | 1.33%   |
| Alcor Micro                            | 47        | 0.97%   |
| Lenovo                                 | 41        | 0.84%   |
| Sonix Technology                       | 38        | 0.78%   |
| Ricoh                                  | 35        | 0.72%   |
| Z-Star Microelectronics                | 23        | 0.47%   |
| Primax Electronics                     | 21        | 0.43%   |
| Samsung Electronics                    | 18        | 0.37%   |
| icSpring                               | 14        | 0.29%   |
| SunplusIT                              | 13        | 0.27%   |
| ALi                                    | 13        | 0.27%   |
| Importek                               | 12        | 0.25%   |
| OmniVision Technologies                | 9         | 0.18%   |
| Genesys Logic                          | 8         | 0.16%   |
| Microsoft                              | 7         | 0.14%   |
| Intel                                  | 6         | 0.12%   |
| GEMBIRD                                | 6         | 0.12%   |
| ShineTech                              | 5         | 0.1%    |
| MacroSilicon                           | 5         | 0.1%    |
| Generalplus Technology                 | 5         | 0.1%    |
| Y Media                                | 4         | 0.08%   |
| USB Camera CS                          | 3         | 0.06%   |
| Sunplus Technology                     | 3         | 0.06%   |
| Pixart Imaging                         | 3         | 0.06%   |
| DigiTech                               | 3         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 322       | 6.57%   |
| Microdia Integrated_Webcam_HD                       | 187       | 3.81%   |
| IMC Networks Integrated Camera                      | 176       | 3.59%   |
| Realtek Integrated_Webcam_HD                        | 138       | 2.81%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 132       | 2.69%   |
| Bison Integrated Camera                             | 121       | 2.47%   |
| Quanta Chromebook HD Camera                         | 102       | 2.08%   |
| Chicony HD WebCam                                   | 99        | 2.02%   |
| Sunplus Integrated_Webcam_HD                        | 89        | 1.82%   |
| Syntek Integrated Camera                            | 67        | 1.37%   |
| Chicony HP HD Camera                                | 67        | 1.37%   |
| Acer BisonCam, NB Pro                               | 62        | 1.26%   |
| Quanta HP TrueVision HD Camera                      | 49        | 1%      |
| Chicony USB2.0 HD UVC WebCam                        | 49        | 1%      |
| Quanta HD User Facing                               | 48        | 0.98%   |
| Lite-On Integrated Camera                           | 48        | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 48        | 0.98%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 44        | 0.9%    |
| Bison SunplusIT Integrated Camera                   | 42        | 0.86%   |
| Microdia Integrated Webcam                          | 40        | 0.82%   |
| Lite-On HP HD Camera                                | 39        | 0.8%    |
| Chicony HD User Facing                              | 38        | 0.78%   |
| Quanta HP HD Camera                                 | 35        | 0.71%   |
| Chicony Integrated Camera (1280x720@30)             | 35        | 0.71%   |
| Sunplus HD WebCam                                   | 34        | 0.69%   |
| Chicony HP TrueVision HD Camera                     | 34        | 0.69%   |
| Realtek USB Camera                                  | 33        | 0.67%   |
| Bison HD Webcam                                     | 33        | 0.67%   |
| Quanta VGA WebCam                                   | 31        | 0.63%   |
| Sonix USB2.0 HD UVC WebCam                          | 29        | 0.59%   |
| Bison Lenovo EasyCamera                             | 29        | 0.59%   |
| Realtek Integrated Webcam                           | 28        | 0.57%   |
| Chicony HP Truevision HD                            | 28        | 0.57%   |
| Bison Lenovo Integrated Webcam                      | 28        | 0.57%   |
| Chicony EasyCamera                                  | 27        | 0.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 26        | 0.53%   |
| Apple Built-in iSight                               | 25        | 0.51%   |
| Luxvisions Innotech Limited HP HD Camera            | 24        | 0.49%   |
| Chicony USB2.0 VGA UVC WebCam                       | 24        | 0.49%   |
| Chicony Lenovo EasyCamera                           | 24        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 326       | 32.15%  |
| Validity Sensors                   | 321       | 31.66%  |
| Shenzhen Goodix Technology         | 131       | 12.92%  |
| Upek                               | 59        | 5.82%   |
| AuthenTec                          | 59        | 5.82%   |
| Elan Microelectronics              | 56        | 5.52%   |
| LighTuning Technology              | 31        | 3.06%   |
| STMicroelectronics                 | 19        | 1.87%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 0.49%   |
| Focal-systems.Corp                 | 2         | 0.2%    |
| DigitalPersona                     | 2         | 0.2%    |
| Samsung Electronics                | 1         | 0.1%    |
| Microsoft                          | 1         | 0.1%    |
| HOLTEK                             | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 144       | 14.2%   |
| Shenzhen Goodix  Fingerprint Device                                        | 84        | 8.28%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 67        | 6.61%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 60        | 5.92%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 59        | 5.82%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 53        | 5.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 50        | 4.93%   |
| Validity Sensors Synaptics WBDI                                            | 29        | 2.86%   |
| Elan ELAN:Fingerprint                                                      | 29        | 2.86%   |
| Elan ELAN:ARM-M4                                                           | 27        | 2.66%   |
| AuthenTec AES2810                                                          | 26        | 2.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 25        | 2.47%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 24        | 2.37%   |
| Shenzhen Goodix FingerPrint                                                | 22        | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 20        | 1.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 20        | 1.97%   |
| Synaptics Fingerprint reader [HP G6]                                       | 19        | 1.87%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 18        | 1.78%   |
| Validity Sensors VFS491                                                    | 17        | 1.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 17        | 1.68%   |
| STMicroelectronics Fingerprint Reader                                      | 17        | 1.68%   |
| Synaptics UWP WBDI Device                                                  | 14        | 1.38%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.38%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 1.28%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 1.08%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 1.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 0.99%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 0.99%   |
| Synaptics  WBDI                                                            | 10        | 0.99%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 0.89%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 0.79%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 0.79%   |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.59%   |
| Synaptics WBDI                                                             | 6         | 0.59%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.59%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 5         | 0.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.49%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 5         | 0.49%   |
| Unknown                                                                    | 4         | 0.39%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 206       | 39.09%  |
| Alcor Micro               | 199       | 37.76%  |
| Upek                      | 36        | 6.83%   |
| Lenovo                    | 33        | 6.26%   |
| O2 Micro                  | 31        | 5.88%   |
| Yubico.com                | 5         | 0.95%   |
| Gemalto (was Gemplus)     | 5         | 0.95%   |
| Clay Logic                | 3         | 0.57%   |
| SCM Microsystems          | 2         | 0.38%   |
| Aladdin Knowledge Systems | 2         | 0.38%   |
| Advanced Card Systems     | 2         | 0.38%   |
| OmniKey                   | 1         | 0.19%   |
| Cherry                    | 1         | 0.19%   |
| C3PO                      | 1         | 0.19%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 196       | 37.19%  |
| Broadcom BCM5880 Secure Applications Processor                               | 58        | 11.01%  |
| Broadcom 58200                                                               | 57        | 10.82%  |
| Broadcom 5880                                                                | 50        | 9.49%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 39        | 7.4%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 36        | 6.83%   |
| Lenovo Integrated Smart Card Reader                                          | 33        | 6.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 4.93%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 0.95%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 4         | 0.76%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.57%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.57%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.38%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.38%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.38%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.38%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.19%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.19%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.19%   |
| OmniKey CardMan 4321                                                         | 1         | 0.19%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.19%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.19%   |
| C3PO LTC31v2                                                                 | 1         | 0.19%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.19%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.19%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3445      | 55.45%  |
| 1     | 2084      | 33.54%  |
| 2     | 527       | 8.48%   |
| 3     | 120       | 1.93%   |
| 4     | 19        | 0.31%   |
| 5     | 13        | 0.21%   |
| 6     | 5         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1009      | 28.99%  |
| Graphics card            | 951       | 27.32%  |
| Chipcard                 | 482       | 13.85%  |
| Net/wireless             | 318       | 9.14%   |
| Multimedia controller    | 287       | 8.24%   |
| Camera                   | 111       | 3.19%   |
| Bluetooth                | 76        | 2.18%   |
| Communication controller | 54        | 1.55%   |
| Card reader              | 51        | 1.47%   |
| Storage                  | 44        | 1.26%   |
| Sound                    | 38        | 1.09%   |
| Net/ethernet             | 19        | 0.55%   |
| Network                  | 11        | 0.32%   |
| Modem                    | 9         | 0.26%   |
| Flash memory             | 7         | 0.2%    |
| Wireless                 | 4         | 0.11%   |
| Storage/raid             | 4         | 0.11%   |
| Unassigned class         | 2         | 0.06%   |
| Firewire controller      | 2         | 0.06%   |
| Tv card                  | 1         | 0.03%   |
| Storage/ide              | 1         | 0.03%   |

