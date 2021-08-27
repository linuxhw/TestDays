Fedora 34 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 34 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=fedora-34

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 5566               | [21f8762e74](https://linux-hardware.org/?probe=21f8762e74) | Aug 26, 2021 |
| Dell          | Inspiron 5566               | [42184613d7](https://linux-hardware.org/?probe=42184613d7) | Aug 26, 2021 |
| Acer          | Aspire 5516                 | [5c779547e8](https://linux-hardware.org/?probe=5c779547e8) | Aug 26, 2021 |
| Maibenben     | S431                        | [6950bbec9b](https://linux-hardware.org/?probe=6950bbec9b) | Aug 26, 2021 |
| HP            | Pavilion Power Laptop 15... | [a663972867](https://linux-hardware.org/?probe=a663972867) | Aug 26, 2021 |
| HP            | Pavilion Power Laptop 15... | [d29deaa58e](https://linux-hardware.org/?probe=d29deaa58e) | Aug 26, 2021 |
| System76      | Oryx Pro                    | [766916b305](https://linux-hardware.org/?probe=766916b305) | Aug 26, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [2c4c7620cc](https://linux-hardware.org/?probe=2c4c7620cc) | Aug 26, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [48121667a9](https://linux-hardware.org/?probe=48121667a9) | Aug 25, 2021 |
| ASUSTek       | X750JN                      | [dcd95a7374](https://linux-hardware.org/?probe=dcd95a7374) | Aug 25, 2021 |
| HP            | ProBook 455 G7              | [56da4a55e4](https://linux-hardware.org/?probe=56da4a55e4) | Aug 25, 2021 |
| Acer          | Aspire SW5-012              | [fe8aa54fcd](https://linux-hardware.org/?probe=fe8aa54fcd) | Aug 25, 2021 |
| HP            | Laptop 15s-fq2xxx           | [15552cf8da](https://linux-hardware.org/?probe=15552cf8da) | Aug 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [1ab639abb8](https://linux-hardware.org/?probe=1ab639abb8) | Aug 24, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| Dell          | Inspiron 5559               | [bb902b38e1](https://linux-hardware.org/?probe=bb902b38e1) | Aug 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [49aac2eefe](https://linux-hardware.org/?probe=49aac2eefe) | Aug 24, 2021 |
| Sony          | VPCEH16EN                   | [b74cb4b68e](https://linux-hardware.org/?probe=b74cb4b68e) | Aug 24, 2021 |
| HP            | EliteBook 820 G4            | [5d6a3388dc](https://linux-hardware.org/?probe=5d6a3388dc) | Aug 24, 2021 |
| HUAWEI        | MACH-WX9                    | [ffd49f5a01](https://linux-hardware.org/?probe=ffd49f5a01) | Aug 23, 2021 |
| Acer          | Swift SF314-52              | [25ce57f1be](https://linux-hardware.org/?probe=25ce57f1be) | Aug 23, 2021 |
| Acer          | Swift SF314-52              | [cef75c8a5a](https://linux-hardware.org/?probe=cef75c8a5a) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [42c87d7154](https://linux-hardware.org/?probe=42c87d7154) | Aug 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b773fc8716](https://linux-hardware.org/?probe=b773fc8716) | Aug 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [e506f7ea95](https://linux-hardware.org/?probe=e506f7ea95) | Aug 23, 2021 |
| HP            | 14                          | [6d84790759](https://linux-hardware.org/?probe=6d84790759) | Aug 23, 2021 |
| HP            | ZBook 15 G6                 | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Timi          | A35S                        | [d00b7954e8](https://linux-hardware.org/?probe=d00b7954e8) | Aug 23, 2021 |
| Positivo      | C14CR21                     | [c4ae2acc0b](https://linux-hardware.org/?probe=c4ae2acc0b) | Aug 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | [7373f6a54d](https://linux-hardware.org/?probe=7373f6a54d) | Aug 22, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [3d417f197c](https://linux-hardware.org/?probe=3d417f197c) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f534340eab](https://linux-hardware.org/?probe=f534340eab) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4f6bd2a75e](https://linux-hardware.org/?probe=4f6bd2a75e) | Aug 22, 2021 |
| Lenovo        | IdeaPad FLEX-14API 81SS     | [b6390e7b7d](https://linux-hardware.org/?probe=b6390e7b7d) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | [b2de2ea1ab](https://linux-hardware.org/?probe=b2de2ea1ab) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | [9da6a33d24](https://linux-hardware.org/?probe=9da6a33d24) | Aug 22, 2021 |
| Dell          | XPS 17 9710                 | [2ec395c6ca](https://linux-hardware.org/?probe=2ec395c6ca) | Aug 22, 2021 |
| MSI           | GP62MVR 7RFX                | [64a52a91b1](https://linux-hardware.org/?probe=64a52a91b1) | Aug 22, 2021 |
| Acer          | Aspire ES1-572              | [07e3a21f1c](https://linux-hardware.org/?probe=07e3a21f1c) | Aug 22, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [7f439ff799](https://linux-hardware.org/?probe=7f439ff799) | Aug 22, 2021 |
| Unknown       | Unknown                     | [987edc4158](https://linux-hardware.org/?probe=987edc4158) | Aug 21, 2021 |
| Sony          | SVT1122B2EW                 | [7ef0a9c54a](https://linux-hardware.org/?probe=7ef0a9c54a) | Aug 21, 2021 |
| Dell          | XPS 15 9550                 | [1215c27927](https://linux-hardware.org/?probe=1215c27927) | Aug 21, 2021 |
| Dell          | Inspiron 13-7359            | [555a25c577](https://linux-hardware.org/?probe=555a25c577) | Aug 21, 2021 |
| ASUSTek       | UX303UA                     | [6f88337886](https://linux-hardware.org/?probe=6f88337886) | Aug 21, 2021 |
| Sony          | SVS1511X9RB                 | [5ee85bc3a6](https://linux-hardware.org/?probe=5ee85bc3a6) | Aug 21, 2021 |
| Sony          | SVS1511X9RB                 | [77326cdac5](https://linux-hardware.org/?probe=77326cdac5) | Aug 21, 2021 |
| Dell          | Precision 5550              | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [112c79071e](https://linux-hardware.org/?probe=112c79071e) | Aug 21, 2021 |
| HP            | EliteBook 820 G4            | [d31c0fcaac](https://linux-hardware.org/?probe=d31c0fcaac) | Aug 21, 2021 |
| Dell          | Latitude 7400               | [61fd9efe24](https://linux-hardware.org/?probe=61fd9efe24) | Aug 21, 2021 |
| Dell          | XPS L702X                   | [32448925cb](https://linux-hardware.org/?probe=32448925cb) | Aug 20, 2021 |
| Acer          | Nitro AN515-45              | [6136df7463](https://linux-hardware.org/?probe=6136df7463) | Aug 20, 2021 |
| Dell          | XPS L702X                   | [93f7edad9b](https://linux-hardware.org/?probe=93f7edad9b) | Aug 20, 2021 |
| HP            | ProBook 450 G6              | [227d87ab66](https://linux-hardware.org/?probe=227d87ab66) | Aug 20, 2021 |
| Lenovo        | ThinkPad P43s 20RJS1C200    | [3dab4fd1db](https://linux-hardware.org/?probe=3dab4fd1db) | Aug 20, 2021 |
| AMI           | Cherry Trail CR             | [bf0f2ff4a0](https://linux-hardware.org/?probe=bf0f2ff4a0) | Aug 20, 2021 |
| Lenovo        | ThinkPad T580 20LAS5XS00    | [472494a25c](https://linux-hardware.org/?probe=472494a25c) | Aug 20, 2021 |
| Acer          | Nitro AN515-54              | [70e32af3f7](https://linux-hardware.org/?probe=70e32af3f7) | Aug 19, 2021 |
| Alienware     | 15 R4                       | [bd2c12701c](https://linux-hardware.org/?probe=bd2c12701c) | Aug 19, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [0d33aed04c](https://linux-hardware.org/?probe=0d33aed04c) | Aug 19, 2021 |
| HP            | EliteBook 840 G1            | [b9d5b6e9e9](https://linux-hardware.org/?probe=b9d5b6e9e9) | Aug 19, 2021 |
| Acer          | Nitro AN515-54              | [5019993be7](https://linux-hardware.org/?probe=5019993be7) | Aug 19, 2021 |
| Notebook      | N150CU                      | [8d2621da6a](https://linux-hardware.org/?probe=8d2621da6a) | Aug 19, 2021 |
| Dell          | XPS 15 9560                 | [07fc61d3ba](https://linux-hardware.org/?probe=07fc61d3ba) | Aug 19, 2021 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | [24f73e707a](https://linux-hardware.org/?probe=24f73e707a) | Aug 18, 2021 |
| Apple         | MacBookPro11,1              | [7731a3a1da](https://linux-hardware.org/?probe=7731a3a1da) | Aug 18, 2021 |
| Apple         | MacBookPro11,1              | [64adb81ad2](https://linux-hardware.org/?probe=64adb81ad2) | Aug 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [a613776a9c](https://linux-hardware.org/?probe=a613776a9c) | Aug 18, 2021 |
| HP            | Pavilion dv7                | [7d6c08fc9e](https://linux-hardware.org/?probe=7d6c08fc9e) | Aug 17, 2021 |
| ASUSTek       | N56JN                       | [5c3c22a21d](https://linux-hardware.org/?probe=5c3c22a21d) | Aug 17, 2021 |
| ASUSTek       | N56JN                       | [affdbcbf08](https://linux-hardware.org/?probe=affdbcbf08) | Aug 17, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [28cd688d16](https://linux-hardware.org/?probe=28cd688d16) | Aug 17, 2021 |
| Acer          | S7-392                      | [1251d42538](https://linux-hardware.org/?probe=1251d42538) | Aug 17, 2021 |
| Lenovo        | ThinkPad E14 20RA001BUK     | [584785653a](https://linux-hardware.org/?probe=584785653a) | Aug 17, 2021 |
| HP            | EliteBook 840 G6            | [43ee57ed48](https://linux-hardware.org/?probe=43ee57ed48) | Aug 17, 2021 |
| Acer          | Aspire A515-46              | [ad8f403c6d](https://linux-hardware.org/?probe=ad8f403c6d) | Aug 17, 2021 |
| Dell          | Latitude E6510              | [b7071ddea1](https://linux-hardware.org/?probe=b7071ddea1) | Aug 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d64c2407ca](https://linux-hardware.org/?probe=d64c2407ca) | Aug 17, 2021 |
| HP            | 15 Notebook PC              | [86101835e0](https://linux-hardware.org/?probe=86101835e0) | Aug 17, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [10cec0686e](https://linux-hardware.org/?probe=10cec0686e) | Aug 17, 2021 |
| HP            | ProBook 470 G5              | [2864cc0f2a](https://linux-hardware.org/?probe=2864cc0f2a) | Aug 15, 2021 |
| Dell          | Studio 1747                 | [ba0f2b7d03](https://linux-hardware.org/?probe=ba0f2b7d03) | Aug 15, 2021 |
| Lenovo        | ThinkPad T450 20BU000QLM    | [41e2825c3d](https://linux-hardware.org/?probe=41e2825c3d) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [8bf626f6b3](https://linux-hardware.org/?probe=8bf626f6b3) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6909a1a841](https://linux-hardware.org/?probe=6909a1a841) | Aug 14, 2021 |
| HP            | Laptop 15s-eq2xxx           | [b8722b62ff](https://linux-hardware.org/?probe=b8722b62ff) | Aug 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [eda5da5e9d](https://linux-hardware.org/?probe=eda5da5e9d) | Aug 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [518309e6c8](https://linux-hardware.org/?probe=518309e6c8) | Aug 14, 2021 |
| HP            | Laptop 15s-eq2xxx           | [7df108445b](https://linux-hardware.org/?probe=7df108445b) | Aug 14, 2021 |
| Dell          | XPS 15 7590                 | [b656e3aec4](https://linux-hardware.org/?probe=b656e3aec4) | Aug 14, 2021 |
| HP            | ProBook 440 G3              | [e93a65b9cf](https://linux-hardware.org/?probe=e93a65b9cf) | Aug 14, 2021 |
| Framework     | Laptop                      | [bd868e3985](https://linux-hardware.org/?probe=bd868e3985) | Aug 14, 2021 |
| Chuwi         | GemiBook                    | [c7d0df9fbb](https://linux-hardware.org/?probe=c7d0df9fbb) | Aug 13, 2021 |
| HP            | Pavilion dv7                | [640a5fb2b3](https://linux-hardware.org/?probe=640a5fb2b3) | Aug 13, 2021 |
| Acer          | Aspire V3-772G              | [58d92680bb](https://linux-hardware.org/?probe=58d92680bb) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [4dc4a0efe0](https://linux-hardware.org/?probe=4dc4a0efe0) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6e44d2998d](https://linux-hardware.org/?probe=6e44d2998d) | Aug 13, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [10db213e5d](https://linux-hardware.org/?probe=10db213e5d) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [2aa119abf8](https://linux-hardware.org/?probe=2aa119abf8) | Aug 13, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [f7dabed440](https://linux-hardware.org/?probe=f7dabed440) | Aug 13, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [6f0b883adb](https://linux-hardware.org/?probe=6f0b883adb) | Aug 13, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [5d036af9c0](https://linux-hardware.org/?probe=5d036af9c0) | Aug 13, 2021 |
| Lenovo        | B50-80 80EW                 | [f8af262ae5](https://linux-hardware.org/?probe=f8af262ae5) | Aug 13, 2021 |
| Acer          | Aspire E5-574               | [7fb046bc6a](https://linux-hardware.org/?probe=7fb046bc6a) | Aug 12, 2021 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [adae4a7ada](https://linux-hardware.org/?probe=adae4a7ada) | Aug 12, 2021 |
| Dell          | XPS 15 7590                 | [185cff6125](https://linux-hardware.org/?probe=185cff6125) | Aug 12, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | [7b708488a2](https://linux-hardware.org/?probe=7b708488a2) | Aug 12, 2021 |
| Alienware     | x17 R1                      | [447d4de752](https://linux-hardware.org/?probe=447d4de752) | Aug 12, 2021 |
| HP            | ProBook 450 G5              | [745332d76b](https://linux-hardware.org/?probe=745332d76b) | Aug 12, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [34848a17dc](https://linux-hardware.org/?probe=34848a17dc) | Aug 12, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2e9babd6f4](https://linux-hardware.org/?probe=2e9babd6f4) | Aug 11, 2021 |
| HP            | Pavilion 15                 | [4e8387b8e9](https://linux-hardware.org/?probe=4e8387b8e9) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [42368b3305](https://linux-hardware.org/?probe=42368b3305) | Aug 10, 2021 |
| HP            | Laptop 15-dw3xxx            | [7ee6c3801e](https://linux-hardware.org/?probe=7ee6c3801e) | Aug 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [02a92f8ff3](https://linux-hardware.org/?probe=02a92f8ff3) | Aug 10, 2021 |
| HP            | EliteBook 850 G5            | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| Dell          | Precision 5530              | [e1f4582882](https://linux-hardware.org/?probe=e1f4582882) | Aug 09, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [dc5848146e](https://linux-hardware.org/?probe=dc5848146e) | Aug 09, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [c3b36c30d8](https://linux-hardware.org/?probe=c3b36c30d8) | Aug 09, 2021 |
| HP            | Laptop 15s-eq2xxx           | [b1cab0fd9c](https://linux-hardware.org/?probe=b1cab0fd9c) | Aug 09, 2021 |
| HP            | Pavilion dv7                | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| Notebook      | NH55RGQ                     | [985e447ff5](https://linux-hardware.org/?probe=985e447ff5) | Aug 09, 2021 |
| HP            | ProBook 6465b               | [8d7f457e6e](https://linux-hardware.org/?probe=8d7f457e6e) | Aug 09, 2021 |
| Sony          | VPCEH36EG                   | [ec709da453](https://linux-hardware.org/?probe=ec709da453) | Aug 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [fa2d2aa603](https://linux-hardware.org/?probe=fa2d2aa603) | Aug 09, 2021 |
| ASUSTek       | ZenBook 13 UX331FN_UX331... | [fe9a44853c](https://linux-hardware.org/?probe=fe9a44853c) | Aug 08, 2021 |
| Dell          | Inspiron 5502               | [955889f7c8](https://linux-hardware.org/?probe=955889f7c8) | Aug 08, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5a46a3aa4a](https://linux-hardware.org/?probe=5a46a3aa4a) | Aug 07, 2021 |
| Dell          | Inspiron 5558               | [7b24aa2b0c](https://linux-hardware.org/?probe=7b24aa2b0c) | Aug 07, 2021 |
| Lenovo        | G40-45 80E1                 | [322608eeb3](https://linux-hardware.org/?probe=322608eeb3) | Aug 07, 2021 |
| Lenovo        | G40-45 80E1                 | [2dd10ed83f](https://linux-hardware.org/?probe=2dd10ed83f) | Aug 07, 2021 |
| Toshiba       | TECRA Z50-A                 | [e04191385a](https://linux-hardware.org/?probe=e04191385a) | Aug 07, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [20b75d980d](https://linux-hardware.org/?probe=20b75d980d) | Aug 06, 2021 |
| Dell          | Inspiron 5323               | [3600f5a7a8](https://linux-hardware.org/?probe=3600f5a7a8) | Aug 06, 2021 |
| Apple         | MacBookPro16,2              | [4c2763b512](https://linux-hardware.org/?probe=4c2763b512) | Aug 06, 2021 |
| Notebook      | Titanium B155 MAX           | [f1fd39abcd](https://linux-hardware.org/?probe=f1fd39abcd) | Aug 06, 2021 |
| Dell          | Inspiron 7572               | [a41678d0ce](https://linux-hardware.org/?probe=a41678d0ce) | Aug 06, 2021 |
| Toshiba       | TECRA Z50-A                 | [6a9e7d18fc](https://linux-hardware.org/?probe=6a9e7d18fc) | Aug 06, 2021 |
| Dell          | Inspiron 7572               | [aea38e48c7](https://linux-hardware.org/?probe=aea38e48c7) | Aug 06, 2021 |
| HP            | 15                          | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| Notebook      | Titanium B155 MAX           | [2311d7a604](https://linux-hardware.org/?probe=2311d7a604) | Aug 05, 2021 |
| Dell          | Latitude 7410               | [013122833c](https://linux-hardware.org/?probe=013122833c) | Aug 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [a5e93c2b7f](https://linux-hardware.org/?probe=a5e93c2b7f) | Aug 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6fe693a80e](https://linux-hardware.org/?probe=6fe693a80e) | Aug 05, 2021 |
| HP            | ProBook 6465b               | [73822c2796](https://linux-hardware.org/?probe=73822c2796) | Aug 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [234f1782ff](https://linux-hardware.org/?probe=234f1782ff) | Aug 05, 2021 |
| Fujitsu       | LIFEBOOK A357               | [68af6cccad](https://linux-hardware.org/?probe=68af6cccad) | Aug 05, 2021 |
| Acer          | Aspire V5-122P              | [7c04b89c8a](https://linux-hardware.org/?probe=7c04b89c8a) | Aug 04, 2021 |
| HP            | Pavilion dv6                | [87b441ff00](https://linux-hardware.org/?probe=87b441ff00) | Aug 04, 2021 |
| Dell          | Inspiron 5370               | [40360bb1e3](https://linux-hardware.org/?probe=40360bb1e3) | Aug 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | [e70f3ab4cd](https://linux-hardware.org/?probe=e70f3ab4cd) | Aug 04, 2021 |
| ASUSTek       | K75DE                       | [139840a80c](https://linux-hardware.org/?probe=139840a80c) | Aug 04, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d4f12adb88](https://linux-hardware.org/?probe=d4f12adb88) | Aug 04, 2021 |
| HUAWEI        | HVY-WXX9                    | [b1d2bc3821](https://linux-hardware.org/?probe=b1d2bc3821) | Aug 03, 2021 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [bed31de6b8](https://linux-hardware.org/?probe=bed31de6b8) | Aug 03, 2021 |
| Dell          | XPS 15 7590                 | [4d3a4d6db1](https://linux-hardware.org/?probe=4d3a4d6db1) | Aug 03, 2021 |
| Dell          | XPS 13 7390                 | [3f857761fa](https://linux-hardware.org/?probe=3f857761fa) | Aug 03, 2021 |
| Gigabyte      | AORUS 15G KB                | [323ac43e6d](https://linux-hardware.org/?probe=323ac43e6d) | Aug 03, 2021 |
| Gigabyte      | AORUS 15G KB                | [5e01ce0d4f](https://linux-hardware.org/?probe=5e01ce0d4f) | Aug 03, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [847bf89546](https://linux-hardware.org/?probe=847bf89546) | Aug 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [6c6c327314](https://linux-hardware.org/?probe=6c6c327314) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d09a20ffb6](https://linux-hardware.org/?probe=d09a20ffb6) | Aug 02, 2021 |
| Lenovo        | ThinkPad Edge E440 20C50... | [ba11bbceb8](https://linux-hardware.org/?probe=ba11bbceb8) | Aug 01, 2021 |
| HP            | Pavilion dv6                | [ba0a55bf85](https://linux-hardware.org/?probe=ba0a55bf85) | Aug 01, 2021 |
| Acer          | Aspire A515-54G             | [8431041495](https://linux-hardware.org/?probe=8431041495) | Aug 01, 2021 |
| Acer          | Aspire A515-54G             | [8218aa8198](https://linux-hardware.org/?probe=8218aa8198) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0d6c963f0e](https://linux-hardware.org/?probe=0d6c963f0e) | Jul 31, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [c0d8e5adf6](https://linux-hardware.org/?probe=c0d8e5adf6) | Jul 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e88f8edeb9](https://linux-hardware.org/?probe=e88f8edeb9) | Jul 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e5e3591da2](https://linux-hardware.org/?probe=e5e3591da2) | Jul 31, 2021 |
| HP            | Laptop 15-dw3xxx            | [4a5ead6209](https://linux-hardware.org/?probe=4a5ead6209) | Jul 31, 2021 |
| HONOR         | NBD-WXX9                    | [2b6a0f8576](https://linux-hardware.org/?probe=2b6a0f8576) | Jul 31, 2021 |
| Lenovo        | Legion Y7000P 81LD          | [b92fbcc1fd](https://linux-hardware.org/?probe=b92fbcc1fd) | Jul 31, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [07d66d0963](https://linux-hardware.org/?probe=07d66d0963) | Jul 30, 2021 |
| Timi          | A35S                        | [dfd89e45de](https://linux-hardware.org/?probe=dfd89e45de) | Jul 30, 2021 |
| Dell          | Inspiron 5323               | [52700f62dc](https://linux-hardware.org/?probe=52700f62dc) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | [a627b4644e](https://linux-hardware.org/?probe=a627b4644e) | Jul 30, 2021 |
| Lenovo        | ThinkBook 13s G2 ARE 20W... | [23d664d987](https://linux-hardware.org/?probe=23d664d987) | Jul 30, 2021 |
| Lenovo        | ThinkBook 13s G2 ARE 20W... | [95a364c010](https://linux-hardware.org/?probe=95a364c010) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | [ac14ce7f86](https://linux-hardware.org/?probe=ac14ce7f86) | Jul 30, 2021 |
| Lenovo        | ThinkBook 13s G2 ARE 20W... | [a95b853ed8](https://linux-hardware.org/?probe=a95b853ed8) | Jul 30, 2021 |
| Acer          | Aspire E5-576               | [11d9b03eca](https://linux-hardware.org/?probe=11d9b03eca) | Jul 29, 2021 |
| HP            | EliteBook 850 G6            | [6933a56e5a](https://linux-hardware.org/?probe=6933a56e5a) | Jul 29, 2021 |
| HP            | EliteBook 850 G6            | [c1c1ff83e5](https://linux-hardware.org/?probe=c1c1ff83e5) | Jul 29, 2021 |
| HP            | Pavilion 11 x360 PC         | [6e097e987f](https://linux-hardware.org/?probe=6e097e987f) | Jul 29, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [8121463c28](https://linux-hardware.org/?probe=8121463c28) | Jul 29, 2021 |
| HP            | ProBook 445 G7              | [961bafd03a](https://linux-hardware.org/?probe=961bafd03a) | Jul 29, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [edfea43d47](https://linux-hardware.org/?probe=edfea43d47) | Jul 28, 2021 |
| HP            | EliteBook 850 G6            | [5b6c57fdb2](https://linux-hardware.org/?probe=5b6c57fdb2) | Jul 28, 2021 |
| HP            | EliteBook 850 G6            | [d95d409e75](https://linux-hardware.org/?probe=d95d409e75) | Jul 28, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [cbbc9c0451](https://linux-hardware.org/?probe=cbbc9c0451) | Jul 28, 2021 |
| Dell          | Inspiron 3502               | [9216707eed](https://linux-hardware.org/?probe=9216707eed) | Jul 28, 2021 |
| Acer          | Aspire A517-51G             | [85dececf7f](https://linux-hardware.org/?probe=85dececf7f) | Jul 28, 2021 |
| Acer          | Aspire A517-51G             | [4d811eb752](https://linux-hardware.org/?probe=4d811eb752) | Jul 28, 2021 |
| Timi          | TM1707                      | [69ece09721](https://linux-hardware.org/?probe=69ece09721) | Jul 28, 2021 |
| Prestigio     | PSB141C03                   | [60fe58fa1b](https://linux-hardware.org/?probe=60fe58fa1b) | Jul 27, 2021 |
| Lenovo        | ThinkPad T590 20N5S72000    | [f82a0e5777](https://linux-hardware.org/?probe=f82a0e5777) | Jul 27, 2021 |
| Dell          | Vostro 14-3468              | [c222cecae0](https://linux-hardware.org/?probe=c222cecae0) | Jul 27, 2021 |
| Samsung       | 305V4A/305V5A/3415VA        | [79fbd86b2a](https://linux-hardware.org/?probe=79fbd86b2a) | Jul 26, 2021 |
| Dell          | Latitude 7400               | [0ad7b49f7a](https://linux-hardware.org/?probe=0ad7b49f7a) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK T901               | [a470eeaa37](https://linux-hardware.org/?probe=a470eeaa37) | Jul 26, 2021 |
| Samsung       | 305V4A/305V5A/3415VA        | [7df57c3e0c](https://linux-hardware.org/?probe=7df57c3e0c) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a085cda70b](https://linux-hardware.org/?probe=a085cda70b) | Jul 25, 2021 |
| Dell          | Inspiron N4030              | [3f20462c62](https://linux-hardware.org/?probe=3f20462c62) | Jul 25, 2021 |
| HP            | Laptop 15-db1xxx            | [97b8085def](https://linux-hardware.org/?probe=97b8085def) | Jul 25, 2021 |
| Acer          | Aspire A315-42G             | [bfb12f37c8](https://linux-hardware.org/?probe=bfb12f37c8) | Jul 25, 2021 |
| Dell          | Inspiron 5558               | [1cbc95eb56](https://linux-hardware.org/?probe=1cbc95eb56) | Jul 25, 2021 |
| Samsung       | 305V4A/305V5A/3415VA        | [95937e3a67](https://linux-hardware.org/?probe=95937e3a67) | Jul 25, 2021 |
| Acer          | Aspire V5-122P              | [5025f05f95](https://linux-hardware.org/?probe=5025f05f95) | Jul 25, 2021 |
| Apple         | MacBookPro9,2               | [7ebac3504c](https://linux-hardware.org/?probe=7ebac3504c) | Jul 25, 2021 |
| Lenovo        | G40-45 80E1                 | [f2f6ae3a0d](https://linux-hardware.org/?probe=f2f6ae3a0d) | Jul 24, 2021 |
| Lenovo        | G40-45 80E1                 | [fef67a0fc3](https://linux-hardware.org/?probe=fef67a0fc3) | Jul 24, 2021 |
| HP            | 250 G1                      | [61d592b754](https://linux-hardware.org/?probe=61d592b754) | Jul 24, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [4c1fea7f03](https://linux-hardware.org/?probe=4c1fea7f03) | Jul 23, 2021 |
| FUJITSU CL... | LIFEBOOK U7411              | [ad8fb39682](https://linux-hardware.org/?probe=ad8fb39682) | Jul 23, 2021 |
| Timi          | TM1701                      | [2d44d6cccb](https://linux-hardware.org/?probe=2d44d6cccb) | Jul 23, 2021 |
| Dell          | Vostro 15-3568              | [94aa730eda](https://linux-hardware.org/?probe=94aa730eda) | Jul 23, 2021 |
| Fujitsu       | LIFEBOOK T5010              | [1da124bb23](https://linux-hardware.org/?probe=1da124bb23) | Jul 23, 2021 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [5ca74a5c0a](https://linux-hardware.org/?probe=5ca74a5c0a) | Jul 22, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [ed51414a9d](https://linux-hardware.org/?probe=ed51414a9d) | Jul 22, 2021 |
| Positivo      | C41TB                       | [fa578942bc](https://linux-hardware.org/?probe=fa578942bc) | Jul 22, 2021 |
| Acer          | Aspire V5-122P              | [b788dcfcdb](https://linux-hardware.org/?probe=b788dcfcdb) | Jul 22, 2021 |
| Acer          | Aspire V5-122P              | [76203cb8e7](https://linux-hardware.org/?probe=76203cb8e7) | Jul 22, 2021 |
| Lenovo        | ThinkPad X220 4289A92       | [c985a9874f](https://linux-hardware.org/?probe=c985a9874f) | Jul 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | [3006193ccc](https://linux-hardware.org/?probe=3006193ccc) | Jul 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [47b95dd012](https://linux-hardware.org/?probe=47b95dd012) | Jul 21, 2021 |
| Dell          | Inspiron 7572               | [0b2a96b6d7](https://linux-hardware.org/?probe=0b2a96b6d7) | Jul 21, 2021 |
| Google        | Kindred                     | [19b81352aa](https://linux-hardware.org/?probe=19b81352aa) | Jul 21, 2021 |
| HP            | Laptop 15s-eq2xxx           | [6ba7627daa](https://linux-hardware.org/?probe=6ba7627daa) | Jul 21, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [977c0df343](https://linux-hardware.org/?probe=977c0df343) | Jul 21, 2021 |
| Lenovo        | ThinkPad L580 20LXS4K600    | [fc8ad7a780](https://linux-hardware.org/?probe=fc8ad7a780) | Jul 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [87370c4ac2](https://linux-hardware.org/?probe=87370c4ac2) | Jul 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [b5194fe4e7](https://linux-hardware.org/?probe=b5194fe4e7) | Jul 20, 2021 |
| Acer          | Aspire E5-573G              | [d0d9ea99c9](https://linux-hardware.org/?probe=d0d9ea99c9) | Jul 20, 2021 |
| HP            | Laptop 15-bw0xx             | [c8821b395f](https://linux-hardware.org/?probe=c8821b395f) | Jul 19, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [33cd8cd38a](https://linux-hardware.org/?probe=33cd8cd38a) | Jul 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | [23e7b76362](https://linux-hardware.org/?probe=23e7b76362) | Jul 19, 2021 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [8cee50ac90](https://linux-hardware.org/?probe=8cee50ac90) | Jul 19, 2021 |
| Dell          | Precision 5510              | [62987d66d1](https://linux-hardware.org/?probe=62987d66d1) | Jul 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [e1d4b0e45d](https://linux-hardware.org/?probe=e1d4b0e45d) | Jul 18, 2021 |
| Lenovo        | ThinkPad L580 20LWZ3SMUS    | [0ec8152ed0](https://linux-hardware.org/?probe=0ec8152ed0) | Jul 18, 2021 |
| Unknown       | Unknown                     | [944b172397](https://linux-hardware.org/?probe=944b172397) | Jul 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [140d166cbb](https://linux-hardware.org/?probe=140d166cbb) | Jul 18, 2021 |
| Dell          | Vostro 3300                 | [67e30e41e8](https://linux-hardware.org/?probe=67e30e41e8) | Jul 17, 2021 |
| Notebook      | L14xMU                      | [90d627350d](https://linux-hardware.org/?probe=90d627350d) | Jul 17, 2021 |
| Sony          | VPCEB3PGX                   | [d979c2edc1](https://linux-hardware.org/?probe=d979c2edc1) | Jul 17, 2021 |
| Apple         | MacBookPro11,3              | [8384c9bc8b](https://linux-hardware.org/?probe=8384c9bc8b) | Jul 17, 2021 |
| Purism        | Librem 15 v4                | [4d73479f35](https://linux-hardware.org/?probe=4d73479f35) | Jul 16, 2021 |
| Unknown       | Unknown                     | [1d1680d9c3](https://linux-hardware.org/?probe=1d1680d9c3) | Jul 16, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [0f518d6dd3](https://linux-hardware.org/?probe=0f518d6dd3) | Jul 16, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3b38895b98](https://linux-hardware.org/?probe=3b38895b98) | Jul 16, 2021 |
| Toshiba       | Satellite L750              | [29781e432b](https://linux-hardware.org/?probe=29781e432b) | Jul 16, 2021 |
| MSI           | Modern 14 A10M              | [3ccfcf4bc7](https://linux-hardware.org/?probe=3ccfcf4bc7) | Jul 16, 2021 |
| Positivo      | CHT12CP                     | [f339240754](https://linux-hardware.org/?probe=f339240754) | Jul 15, 2021 |
| Medion        | E15301                      | [20b60d58c9](https://linux-hardware.org/?probe=20b60d58c9) | Jul 15, 2021 |
| HP            | ZBook 17 G5                 | [5292f36e16](https://linux-hardware.org/?probe=5292f36e16) | Jul 15, 2021 |
| HP            | ZBook 17 G5                 | [3367527048](https://linux-hardware.org/?probe=3367527048) | Jul 15, 2021 |
| HP            | Laptop 15s-eq2xxx           | [aec09069ed](https://linux-hardware.org/?probe=aec09069ed) | Jul 15, 2021 |
| Lenovo        | G500 20236                  | [23ba122f57](https://linux-hardware.org/?probe=23ba122f57) | Jul 15, 2021 |
| Toshiba       | Satellite P50-C             | [3b8ead252b](https://linux-hardware.org/?probe=3b8ead252b) | Jul 15, 2021 |
| Lenovo        | IdeaPad 15ARE05 81YQ        | [9edec18576](https://linux-hardware.org/?probe=9edec18576) | Jul 15, 2021 |
| HP            | Laptop 15s-eq2xxx           | [433f44e117](https://linux-hardware.org/?probe=433f44e117) | Jul 14, 2021 |
| Lenovo        | ThinkPad 25 20K70004US      | [444232e659](https://linux-hardware.org/?probe=444232e659) | Jul 14, 2021 |
| HP            | ProBook 470 G0              | [0ac8121d51](https://linux-hardware.org/?probe=0ac8121d51) | Jul 14, 2021 |
| Acer          | Aspire E5-573G              | [8294dc2b59](https://linux-hardware.org/?probe=8294dc2b59) | Jul 14, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [bad5668fb0](https://linux-hardware.org/?probe=bad5668fb0) | Jul 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | [70128f07ea](https://linux-hardware.org/?probe=70128f07ea) | Jul 13, 2021 |
| Razer         | Blade 15 Mid 2019-Base      | [197a44190e](https://linux-hardware.org/?probe=197a44190e) | Jul 13, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [c632e51628](https://linux-hardware.org/?probe=c632e51628) | Jul 13, 2021 |
| FUJITSU CL... | LIFEBOOK U7411              | [9d1dfce344](https://linux-hardware.org/?probe=9d1dfce344) | Jul 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [cb44035a70](https://linux-hardware.org/?probe=cb44035a70) | Jul 13, 2021 |
| Dell          | G7 7588                     | [899a0f9ae0](https://linux-hardware.org/?probe=899a0f9ae0) | Jul 12, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [d6812debb6](https://linux-hardware.org/?probe=d6812debb6) | Jul 12, 2021 |
| Dell          | Latitude 3570               | [de199e258b](https://linux-hardware.org/?probe=de199e258b) | Jul 12, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [e3d1b2dd96](https://linux-hardware.org/?probe=e3d1b2dd96) | Jul 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8f5ed33e46](https://linux-hardware.org/?probe=8f5ed33e46) | Jul 12, 2021 |
| HP            | ProBook 470 G5              | [3bca640897](https://linux-hardware.org/?probe=3bca640897) | Jul 12, 2021 |
| Linx          | VISION004                   | [52bb79b8a7](https://linux-hardware.org/?probe=52bb79b8a7) | Jul 12, 2021 |
| Lenovo        | ThinkPad L560 20F10029MC    | [a96e4cc1a5](https://linux-hardware.org/?probe=a96e4cc1a5) | Jul 12, 2021 |
| Lenovo        | ThinkPad P70 20ER0035MH     | [3b7269dbb9](https://linux-hardware.org/?probe=3b7269dbb9) | Jul 12, 2021 |
| MSI           | GF65 Thin 10UE              | [cfd00f1018](https://linux-hardware.org/?probe=cfd00f1018) | Jul 12, 2021 |
| Intel Clie... | LAPBC710                    | [49a2ccdeee](https://linux-hardware.org/?probe=49a2ccdeee) | Jul 12, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [96f87991b2](https://linux-hardware.org/?probe=96f87991b2) | Jul 12, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [3427802385](https://linux-hardware.org/?probe=3427802385) | Jul 12, 2021 |
| Dell          | XPS 17 9700                 | [592276c98f](https://linux-hardware.org/?probe=592276c98f) | Jul 12, 2021 |
| Acer          | Swift SF515-51T             | [f5ec156890](https://linux-hardware.org/?probe=f5ec156890) | Jul 12, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [cd32be6d20](https://linux-hardware.org/?probe=cd32be6d20) | Jul 12, 2021 |
| HP            | EliteBook 840 G6            | [14595ee84e](https://linux-hardware.org/?probe=14595ee84e) | Jul 12, 2021 |
| HP            | EliteBook 840 G6            | [c73776222b](https://linux-hardware.org/?probe=c73776222b) | Jul 11, 2021 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [4056165c35](https://linux-hardware.org/?probe=4056165c35) | Jul 11, 2021 |
| Lenovo        | ThinkPad W540 20BHS04B00    | [7601025893](https://linux-hardware.org/?probe=7601025893) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [d1c166c13e](https://linux-hardware.org/?probe=d1c166c13e) | Jul 11, 2021 |
| HP            | Laptop 15-da0xxx            | [cdc4222058](https://linux-hardware.org/?probe=cdc4222058) | Jul 11, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | [515b7e11d1](https://linux-hardware.org/?probe=515b7e11d1) | Jul 11, 2021 |
| HASEE Comp... | Computer                    | [641cab4c92](https://linux-hardware.org/?probe=641cab4c92) | Jul 11, 2021 |
| ASUSTek       | X556UR                      | [477a92a37e](https://linux-hardware.org/?probe=477a92a37e) | Jul 11, 2021 |
| Dell          | Latitude E6420              | [fe42f53d85](https://linux-hardware.org/?probe=fe42f53d85) | Jul 11, 2021 |
| Acer          | Nitro AN515-54              | [61ea8363bc](https://linux-hardware.org/?probe=61ea8363bc) | Jul 10, 2021 |
| Dell          | XPS 13 9310                 | [223f91e471](https://linux-hardware.org/?probe=223f91e471) | Jul 10, 2021 |
| Timi          | TM1604                      | [496798e57c](https://linux-hardware.org/?probe=496798e57c) | Jul 10, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b411603809](https://linux-hardware.org/?probe=b411603809) | Jul 10, 2021 |
| Apple         | MacBookPro11,3              | [0394bf80be](https://linux-hardware.org/?probe=0394bf80be) | Jul 10, 2021 |
| Lenovo        | ThinkPad T490 20N3S94A00    | [2c4c458feb](https://linux-hardware.org/?probe=2c4c458feb) | Jul 10, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [b059e3bcea](https://linux-hardware.org/?probe=b059e3bcea) | Jul 09, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [b4240819e1](https://linux-hardware.org/?probe=b4240819e1) | Jul 09, 2021 |
| HP            | ENVY TS m7                  | [6d939a6434](https://linux-hardware.org/?probe=6d939a6434) | Jul 09, 2021 |
| Dell          | Latitude E6530              | [7df496ffb5](https://linux-hardware.org/?probe=7df496ffb5) | Jul 09, 2021 |
| Dell          | Latitude 7420               | [ebf2372c3b](https://linux-hardware.org/?probe=ebf2372c3b) | Jul 09, 2021 |
| Lenovo        | G500 20236                  | [4f880e87a0](https://linux-hardware.org/?probe=4f880e87a0) | Jul 09, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [b1ae6e7111](https://linux-hardware.org/?probe=b1ae6e7111) | Jul 09, 2021 |
| Dell          | Latitude D530               | [d48cd58890](https://linux-hardware.org/?probe=d48cd58890) | Jul 09, 2021 |
| ASUSTek       | X556UR                      | [4e555accb1](https://linux-hardware.org/?probe=4e555accb1) | Jul 08, 2021 |
| Dell          | Latitude E6540              | [1b488de7b9](https://linux-hardware.org/?probe=1b488de7b9) | Jul 08, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | [af389420e2](https://linux-hardware.org/?probe=af389420e2) | Jul 08, 2021 |
| Dell          | Precision M4600             | [388aad414f](https://linux-hardware.org/?probe=388aad414f) | Jul 08, 2021 |
| eMachines     | eME732                      | [50e1042533](https://linux-hardware.org/?probe=50e1042533) | Jul 08, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [bdcc6ae937](https://linux-hardware.org/?probe=bdcc6ae937) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [3e43acf8af](https://linux-hardware.org/?probe=3e43acf8af) | Jul 08, 2021 |
| Lenovo        | ThinkPad T590 20N5S2NC1V    | [048e092d2f](https://linux-hardware.org/?probe=048e092d2f) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [196e6c6ec4](https://linux-hardware.org/?probe=196e6c6ec4) | Jul 08, 2021 |
| Notebook      | NH55RGQ                     | [553b287a99](https://linux-hardware.org/?probe=553b287a99) | Jul 08, 2021 |
| Fujitsu       | LIFEBOOK U747               | [68be809f45](https://linux-hardware.org/?probe=68be809f45) | Jul 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ba806c9513](https://linux-hardware.org/?probe=ba806c9513) | Jul 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0f7853a74f](https://linux-hardware.org/?probe=0f7853a74f) | Jul 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c325080602](https://linux-hardware.org/?probe=c325080602) | Jul 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [cc542d5a92](https://linux-hardware.org/?probe=cc542d5a92) | Jul 07, 2021 |
| Dell          | Vostro 3460                 | [d24bfb0cba](https://linux-hardware.org/?probe=d24bfb0cba) | Jul 07, 2021 |
| HP            | Laptop 17-bs1xx             | [17baeef261](https://linux-hardware.org/?probe=17baeef261) | Jul 07, 2021 |
| Acer          | Aspire E5-574               | [72aa4529ca](https://linux-hardware.org/?probe=72aa4529ca) | Jul 07, 2021 |
| Acer          | Aspire E5-574               | [8360c2bcdc](https://linux-hardware.org/?probe=8360c2bcdc) | Jul 07, 2021 |
| Dell          | Latitude D530               | [21ad721b61](https://linux-hardware.org/?probe=21ad721b61) | Jul 07, 2021 |
| Dell          | Inspiron 5770               | [48d7ad6341](https://linux-hardware.org/?probe=48d7ad6341) | Jul 07, 2021 |
| Lenovo        | ThinkPad X250 20CLS4NUSA    | [2f6b8a2bd6](https://linux-hardware.org/?probe=2f6b8a2bd6) | Jul 07, 2021 |
| Lenovo        | ThinkPad X250 20CLS4NUSA    | [c36dd3d8e6](https://linux-hardware.org/?probe=c36dd3d8e6) | Jul 07, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | [ec0db39d7a](https://linux-hardware.org/?probe=ec0db39d7a) | Jul 07, 2021 |
| HP            | ENVY Laptop 15-ep0xxx       | [86fdf9dc69](https://linux-hardware.org/?probe=86fdf9dc69) | Jul 07, 2021 |
| Acer          | Aspire 5749                 | [7aa3ecf46d](https://linux-hardware.org/?probe=7aa3ecf46d) | Jul 07, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [0ae36379ae](https://linux-hardware.org/?probe=0ae36379ae) | Jul 07, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | [4831f1aed2](https://linux-hardware.org/?probe=4831f1aed2) | Jul 07, 2021 |
| ASUSTek       | X555LA                      | [8c44ea27c9](https://linux-hardware.org/?probe=8c44ea27c9) | Jul 06, 2021 |
| ASUSTek       | X555LA                      | [9974f7325e](https://linux-hardware.org/?probe=9974f7325e) | Jul 06, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [429e94317f](https://linux-hardware.org/?probe=429e94317f) | Jul 06, 2021 |
| Dell          | Inspiron 13-7378            | [2006f747eb](https://linux-hardware.org/?probe=2006f747eb) | Jul 06, 2021 |
| HP            | EliteBook 2540p             | [5c9b345041](https://linux-hardware.org/?probe=5c9b345041) | Jul 06, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [e031e80b6b](https://linux-hardware.org/?probe=e031e80b6b) | Jul 06, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [85ee7fa5f1](https://linux-hardware.org/?probe=85ee7fa5f1) | Jul 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [70c0bc44a2](https://linux-hardware.org/?probe=70c0bc44a2) | Jul 05, 2021 |
| Apple         | MacBookPro11,2              | [f5c0f2dd2d](https://linux-hardware.org/?probe=f5c0f2dd2d) | Jul 05, 2021 |
| Acer          | Swift SF314-52G             | [ad7dfb7bf6](https://linux-hardware.org/?probe=ad7dfb7bf6) | Jul 05, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [3803784209](https://linux-hardware.org/?probe=3803784209) | Jul 05, 2021 |
| Dell          | G3 3579                     | [97c520db01](https://linux-hardware.org/?probe=97c520db01) | Jul 04, 2021 |
| Lenovo        | G50-30 80G0                 | [6f974e427e](https://linux-hardware.org/?probe=6f974e427e) | Jul 04, 2021 |
| Login Info... | LOG-QAL30                   | [3376c8f541](https://linux-hardware.org/?probe=3376c8f541) | Jul 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | [be18b0347f](https://linux-hardware.org/?probe=be18b0347f) | Jul 04, 2021 |
| HP            | ProBook 6465b               | [dd03f5f10c](https://linux-hardware.org/?probe=dd03f5f10c) | Jul 04, 2021 |
| HP            | ProBook 6465b               | [27a6794579](https://linux-hardware.org/?probe=27a6794579) | Jul 04, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [e684bf151e](https://linux-hardware.org/?probe=e684bf151e) | Jul 03, 2021 |
| HP            | Laptop 15s-eq2xxx           | [8dd431f915](https://linux-hardware.org/?probe=8dd431f915) | Jul 03, 2021 |
| HUAWEI        | HLYL-WXX9                   | [5aa1cef5bb](https://linux-hardware.org/?probe=5aa1cef5bb) | Jul 03, 2021 |
| Apple         | MacBookPro11,5              | [713b8738d7](https://linux-hardware.org/?probe=713b8738d7) | Jul 03, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [aa4b4e2c5e](https://linux-hardware.org/?probe=aa4b4e2c5e) | Jul 03, 2021 |
| HP            | Pavilion x2 Detachable P... | [d917cdea53](https://linux-hardware.org/?probe=d917cdea53) | Jul 02, 2021 |
| HP            | ENVY TS m7                  | [e4c275224b](https://linux-hardware.org/?probe=e4c275224b) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | [8f0d98b462](https://linux-hardware.org/?probe=8f0d98b462) | Jul 02, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | [f29842baff](https://linux-hardware.org/?probe=f29842baff) | Jul 02, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | [2c9eb028c4](https://linux-hardware.org/?probe=2c9eb028c4) | Jul 02, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [51e1bb06dd](https://linux-hardware.org/?probe=51e1bb06dd) | Jul 02, 2021 |
| Lenovo        | ThinkPad X220 42914CG       | [4f886f5775](https://linux-hardware.org/?probe=4f886f5775) | Jul 02, 2021 |
| Unknown       | Unknown                     | [99c56b3bda](https://linux-hardware.org/?probe=99c56b3bda) | Jul 01, 2021 |
| Acer          | Aspire 5250                 | [4a9dcc3234](https://linux-hardware.org/?probe=4a9dcc3234) | Jul 01, 2021 |
| Dell          | XPS 13 9343                 | [04e26d7f9d](https://linux-hardware.org/?probe=04e26d7f9d) | Jul 01, 2021 |
| Acer          | Aspire A515-51              | [6ee9cba880](https://linux-hardware.org/?probe=6ee9cba880) | Jul 01, 2021 |
| Acer          | Aspire A515-51              | [c2eb051f8c](https://linux-hardware.org/?probe=c2eb051f8c) | Jul 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [6b924d8505](https://linux-hardware.org/?probe=6b924d8505) | Jul 01, 2021 |
| Dell          | Inspiron 3442               | [544a5040ad](https://linux-hardware.org/?probe=544a5040ad) | Jul 01, 2021 |
| Apple         | MacBookPro11,5              | [43d77edd56](https://linux-hardware.org/?probe=43d77edd56) | Jul 01, 2021 |
| Apple         | MacBookPro11,5              | [103c0edcbd](https://linux-hardware.org/?probe=103c0edcbd) | Jun 30, 2021 |
| Apple         | MacBookPro5,1               | [47dfbc7a00](https://linux-hardware.org/?probe=47dfbc7a00) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [d85a7c67f9](https://linux-hardware.org/?probe=d85a7c67f9) | Jun 30, 2021 |
| HUAWEI        | HLYL-WXX9                   | [132edccbe5](https://linux-hardware.org/?probe=132edccbe5) | Jun 30, 2021 |
| Dell          | Latitude E6320              | [dd93a97faf](https://linux-hardware.org/?probe=dd93a97faf) | Jun 29, 2021 |
| Dell          | G7 7588                     | [c053b00ac1](https://linux-hardware.org/?probe=c053b00ac1) | Jun 29, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6820c53176](https://linux-hardware.org/?probe=6820c53176) | Jun 29, 2021 |
| eMachines     | eME732                      | [81bbc7fe0f](https://linux-hardware.org/?probe=81bbc7fe0f) | Jun 29, 2021 |
| eMachines     | eME732                      | [1f334d1a64](https://linux-hardware.org/?probe=1f334d1a64) | Jun 29, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [67e302d5d5](https://linux-hardware.org/?probe=67e302d5d5) | Jun 29, 2021 |
| Dell          | Vostro 5590                 | [1cc0df9bfd](https://linux-hardware.org/?probe=1cc0df9bfd) | Jun 28, 2021 |
| Dell          | Vostro 5590                 | [0caade1304](https://linux-hardware.org/?probe=0caade1304) | Jun 28, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d6ef1b054b](https://linux-hardware.org/?probe=d6ef1b054b) | Jun 28, 2021 |
| Acer          | Nitro AN515-52              | [ea190d7d5b](https://linux-hardware.org/?probe=ea190d7d5b) | Jun 27, 2021 |
| Lenovo        | ThinkPad W530 2447AC4       | [42a4d32f82](https://linux-hardware.org/?probe=42a4d32f82) | Jun 27, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | [09705e74ac](https://linux-hardware.org/?probe=09705e74ac) | Jun 27, 2021 |
| Dell          | Latitude E6510              | [554b7b8739](https://linux-hardware.org/?probe=554b7b8739) | Jun 27, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [4f8ff6b6a4](https://linux-hardware.org/?probe=4f8ff6b6a4) | Jun 26, 2021 |
| Positivo      | CHT14B                      | [4fd6be9b48](https://linux-hardware.org/?probe=4fd6be9b48) | Jun 26, 2021 |
| HP            | Pavilion dv6                | [44c09f0096](https://linux-hardware.org/?probe=44c09f0096) | Jun 26, 2021 |
| ASUSTek       | X510URR                     | [980f6dda35](https://linux-hardware.org/?probe=980f6dda35) | Jun 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a6c3875064](https://linux-hardware.org/?probe=a6c3875064) | Jun 25, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [3fabc021d6](https://linux-hardware.org/?probe=3fabc021d6) | Jun 25, 2021 |
| Acer          | Aspire E1-572P              | [b6b916afd7](https://linux-hardware.org/?probe=b6b916afd7) | Jun 25, 2021 |
| ASUSTek       | N551JX                      | [3ef394cafb](https://linux-hardware.org/?probe=3ef394cafb) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | [3b153ae2f9](https://linux-hardware.org/?probe=3b153ae2f9) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | [988fc9a599](https://linux-hardware.org/?probe=988fc9a599) | Jun 24, 2021 |
| Apple         | MacBookPro7,1               | [3853510dae](https://linux-hardware.org/?probe=3853510dae) | Jun 24, 2021 |
| HP            | EliteBook 745 G5            | [5b2fd462f9](https://linux-hardware.org/?probe=5b2fd462f9) | Jun 24, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [0a87a16629](https://linux-hardware.org/?probe=0a87a16629) | Jun 24, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [f08002593f](https://linux-hardware.org/?probe=f08002593f) | Jun 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [f008bcb38f](https://linux-hardware.org/?probe=f008bcb38f) | Jun 24, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [febe8388b9](https://linux-hardware.org/?probe=febe8388b9) | Jun 24, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [3e700499c7](https://linux-hardware.org/?probe=3e700499c7) | Jun 24, 2021 |
| Lenovo        | ThinkPad W540 20BHS04T0K    | [7f9142fffb](https://linux-hardware.org/?probe=7f9142fffb) | Jun 24, 2021 |
| ASUSTek       | N550JV                      | [1189ce0f29](https://linux-hardware.org/?probe=1189ce0f29) | Jun 23, 2021 |
| Acer          | Nitro AN515-52              | [63d7af3f6c](https://linux-hardware.org/?probe=63d7af3f6c) | Jun 23, 2021 |
| ASUSTek       | N550JV                      | [3d037467a7](https://linux-hardware.org/?probe=3d037467a7) | Jun 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [2c6ef158c3](https://linux-hardware.org/?probe=2c6ef158c3) | Jun 23, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [9d80703f35](https://linux-hardware.org/?probe=9d80703f35) | Jun 23, 2021 |
| Apple         | MacBookPro7,1               | [458921c45b](https://linux-hardware.org/?probe=458921c45b) | Jun 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [e563be02ff](https://linux-hardware.org/?probe=e563be02ff) | Jun 23, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ0B    | [3e8ac913f5](https://linux-hardware.org/?probe=3e8ac913f5) | Jun 23, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [6dc73fd38c](https://linux-hardware.org/?probe=6dc73fd38c) | Jun 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b9d01c99ff](https://linux-hardware.org/?probe=b9d01c99ff) | Jun 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [30717e79a0](https://linux-hardware.org/?probe=30717e79a0) | Jun 22, 2021 |
| Acer          | Aspire 5742                 | [38f25268b8](https://linux-hardware.org/?probe=38f25268b8) | Jun 22, 2021 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [6dbda9f5d3](https://linux-hardware.org/?probe=6dbda9f5d3) | Jun 22, 2021 |
| Dell          | Inspiron M5010              | [1776eab993](https://linux-hardware.org/?probe=1776eab993) | Jun 22, 2021 |
| Acer          | Nitro AN515-42              | [3fbcc9554f](https://linux-hardware.org/?probe=3fbcc9554f) | Jun 22, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [fecaaeafe2](https://linux-hardware.org/?probe=fecaaeafe2) | Jun 22, 2021 |
| HP            | ENVY TS m7                  | [8d0a64c8c1](https://linux-hardware.org/?probe=8d0a64c8c1) | Jun 22, 2021 |
| ASUSTek       | X450LA                      | [243cc91799](https://linux-hardware.org/?probe=243cc91799) | Jun 22, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [4d638e6ba4](https://linux-hardware.org/?probe=4d638e6ba4) | Jun 21, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [d0164778ea](https://linux-hardware.org/?probe=d0164778ea) | Jun 21, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [7499a86ba1](https://linux-hardware.org/?probe=7499a86ba1) | Jun 21, 2021 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [df96074b07](https://linux-hardware.org/?probe=df96074b07) | Jun 21, 2021 |
| LG Electro... | 17Z90N-R.AAC8U1             | [09434b48cf](https://linux-hardware.org/?probe=09434b48cf) | Jun 21, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [5b26e5e2c9](https://linux-hardware.org/?probe=5b26e5e2c9) | Jun 20, 2021 |
| Acer          | Aspire E5-475G              | [0d6df01751](https://linux-hardware.org/?probe=0d6df01751) | Jun 20, 2021 |
| Apple         | MacBookPro11,5              | [de8b613aef](https://linux-hardware.org/?probe=de8b613aef) | Jun 19, 2021 |
| Apple         | MacBookPro11,5              | [0cdcd68d1e](https://linux-hardware.org/?probe=0cdcd68d1e) | Jun 19, 2021 |
| HP            | 255 G4                      | [3a4a67761f](https://linux-hardware.org/?probe=3a4a67761f) | Jun 19, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [822acd5e9b](https://linux-hardware.org/?probe=822acd5e9b) | Jun 19, 2021 |
| Lenovo        | G500 20236                  | [55d0bea92e](https://linux-hardware.org/?probe=55d0bea92e) | Jun 19, 2021 |
| Acer          | Aspire E1-572               | [5d9f586d72](https://linux-hardware.org/?probe=5d9f586d72) | Jun 19, 2021 |
| Acer          | Predator G3-571             | [1e3a3e9e1b](https://linux-hardware.org/?probe=1e3a3e9e1b) | Jun 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3489fe1584](https://linux-hardware.org/?probe=3489fe1584) | Jun 18, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [0fe1eac567](https://linux-hardware.org/?probe=0fe1eac567) | Jun 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [0cfbaaded5](https://linux-hardware.org/?probe=0cfbaaded5) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L6S29D07    | [5c87bcb1dc](https://linux-hardware.org/?probe=5c87bcb1dc) | Jun 18, 2021 |
| Dell          | Latitude 5310               | [a38b907625](https://linux-hardware.org/?probe=a38b907625) | Jun 18, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [92d16a4d2d](https://linux-hardware.org/?probe=92d16a4d2d) | Jun 18, 2021 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [d7cfb8d16f](https://linux-hardware.org/?probe=d7cfb8d16f) | Jun 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [04fa70e3af](https://linux-hardware.org/?probe=04fa70e3af) | Jun 18, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [05dbeca379](https://linux-hardware.org/?probe=05dbeca379) | Jun 17, 2021 |
| Dell          | Inspiron 3543               | [4a5c3ed30c](https://linux-hardware.org/?probe=4a5c3ed30c) | Jun 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [a078b826cc](https://linux-hardware.org/?probe=a078b826cc) | Jun 17, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [f685842bb1](https://linux-hardware.org/?probe=f685842bb1) | Jun 16, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e66e2f9e89](https://linux-hardware.org/?probe=e66e2f9e89) | Jun 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [28d36f1b88](https://linux-hardware.org/?probe=28d36f1b88) | Jun 16, 2021 |
| TrekStor      | Notebook Slim S130          | [312670a9e8](https://linux-hardware.org/?probe=312670a9e8) | Jun 16, 2021 |
| TrekStor      | Notebook Slim S130          | [c5bd6200eb](https://linux-hardware.org/?probe=c5bd6200eb) | Jun 16, 2021 |
| Dell          | Precision 7530              | [3e5d3c4292](https://linux-hardware.org/?probe=3e5d3c4292) | Jun 15, 2021 |
| HP            | Notebook                    | [d8ac22f956](https://linux-hardware.org/?probe=d8ac22f956) | Jun 15, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [790371eae7](https://linux-hardware.org/?probe=790371eae7) | Jun 15, 2021 |
| Positivo      | C41TB                       | [3824885cc3](https://linux-hardware.org/?probe=3824885cc3) | Jun 15, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [6cf8aa4053](https://linux-hardware.org/?probe=6cf8aa4053) | Jun 15, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9145765cc5](https://linux-hardware.org/?probe=9145765cc5) | Jun 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [891f747f39](https://linux-hardware.org/?probe=891f747f39) | Jun 15, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [447e508593](https://linux-hardware.org/?probe=447e508593) | Jun 14, 2021 |
| Dell          | Latitude 5285               | [0fad55c520](https://linux-hardware.org/?probe=0fad55c520) | Jun 14, 2021 |
| Dell          | Latitude 5285               | [4d7dfa80fc](https://linux-hardware.org/?probe=4d7dfa80fc) | Jun 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [4ecc3eec8f](https://linux-hardware.org/?probe=4ecc3eec8f) | Jun 14, 2021 |
| Dell          | Inspiron 5548               | [11bea838aa](https://linux-hardware.org/?probe=11bea838aa) | Jun 14, 2021 |
| Lenovo        | ThinkPad W520 4282AB9       | [a5d7b02f3f](https://linux-hardware.org/?probe=a5d7b02f3f) | Jun 14, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [0c32c6e173](https://linux-hardware.org/?probe=0c32c6e173) | Jun 14, 2021 |
| Lenovo        | ThinkPad E15 20RD0011RT     | [c995062581](https://linux-hardware.org/?probe=c995062581) | Jun 14, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [696a1c9564](https://linux-hardware.org/?probe=696a1c9564) | Jun 13, 2021 |
| Notebook      | NH5x_7xDPx                  | [0f4817a280](https://linux-hardware.org/?probe=0f4817a280) | Jun 13, 2021 |
| Acer          | Nitro AN515-42              | [f70d1d9749](https://linux-hardware.org/?probe=f70d1d9749) | Jun 13, 2021 |
| Notebook      | NH5x_7xDPx                  | [1ffaea82ea](https://linux-hardware.org/?probe=1ffaea82ea) | Jun 13, 2021 |
| HP            | Laptop 15-db1xxx            | [ab3536f2c6](https://linux-hardware.org/?probe=ab3536f2c6) | Jun 13, 2021 |
| Notebook      | PB50_70DFx,DDx              | [48d6b0c4de](https://linux-hardware.org/?probe=48d6b0c4de) | Jun 13, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [86c9df0816](https://linux-hardware.org/?probe=86c9df0816) | Jun 12, 2021 |
| Samsung       | 700Z3C/700Z5C               | [01e22d19b3](https://linux-hardware.org/?probe=01e22d19b3) | Jun 12, 2021 |
| Dell          | Precision 5510              | [afb07c1b1a](https://linux-hardware.org/?probe=afb07c1b1a) | Jun 12, 2021 |
| Lenovo        | ThinkPad E480 20KN003YUS    | [33d07363b6](https://linux-hardware.org/?probe=33d07363b6) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [3641fab1a0](https://linux-hardware.org/?probe=3641fab1a0) | Jun 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [b0ded1652a](https://linux-hardware.org/?probe=b0ded1652a) | Jun 12, 2021 |
| Dell          | Inspiron 5555               | [dd9bf62ea7](https://linux-hardware.org/?probe=dd9bf62ea7) | Jun 11, 2021 |
| HP            | Laptop 15-db1xxx            | [b012f183ba](https://linux-hardware.org/?probe=b012f183ba) | Jun 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [2d43d8a465](https://linux-hardware.org/?probe=2d43d8a465) | Jun 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d4c54270ff](https://linux-hardware.org/?probe=d4c54270ff) | Jun 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c346ece974](https://linux-hardware.org/?probe=c346ece974) | Jun 11, 2021 |
| Dell          | Inspiron 5548               | [9c821bc1eb](https://linux-hardware.org/?probe=9c821bc1eb) | Jun 11, 2021 |
| HUAWEI        | HLYL-WXX9                   | [cf5a4ceda4](https://linux-hardware.org/?probe=cf5a4ceda4) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | [43b8801add](https://linux-hardware.org/?probe=43b8801add) | Jun 10, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [5221d99db7](https://linux-hardware.org/?probe=5221d99db7) | Jun 10, 2021 |
| HP            | Pavilion Notebook           | [c51cb3ca6a](https://linux-hardware.org/?probe=c51cb3ca6a) | Jun 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [241e4071cc](https://linux-hardware.org/?probe=241e4071cc) | Jun 10, 2021 |
| HP            | ZBook 17 G2                 | [05a2ecf3ec](https://linux-hardware.org/?probe=05a2ecf3ec) | Jun 09, 2021 |
| HP            | Laptop 15-db1xxx            | [d0192aebbf](https://linux-hardware.org/?probe=d0192aebbf) | Jun 09, 2021 |
| Acer          | Aspire 5742                 | [2cbf5797c7](https://linux-hardware.org/?probe=2cbf5797c7) | Jun 09, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [4134764afd](https://linux-hardware.org/?probe=4134764afd) | Jun 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [91d8938c98](https://linux-hardware.org/?probe=91d8938c98) | Jun 09, 2021 |
| Acer          | Aspire 5742                 | [07bd5e87d7](https://linux-hardware.org/?probe=07bd5e87d7) | Jun 09, 2021 |
| HP            | ZBook Studio G3             | [02463072c4](https://linux-hardware.org/?probe=02463072c4) | Jun 08, 2021 |
| Lenovo        | ThinkPad E560 20EV003WUS    | [fc739d0d64](https://linux-hardware.org/?probe=fc739d0d64) | Jun 08, 2021 |
| Dell          | Inspiron 5548               | [2ac85efa40](https://linux-hardware.org/?probe=2ac85efa40) | Jun 08, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [efff65d826](https://linux-hardware.org/?probe=efff65d826) | Jun 08, 2021 |
| ASUSTek       | N550JV                      | [7973dc9123](https://linux-hardware.org/?probe=7973dc9123) | Jun 08, 2021 |
| Dell          | Inspiron 3583               | [ead95cf972](https://linux-hardware.org/?probe=ead95cf972) | Jun 08, 2021 |
| Acer          | Aspire E5-573G              | [74bfd5efb9](https://linux-hardware.org/?probe=74bfd5efb9) | Jun 08, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| HP            | Pavilion 15                 | [8c0f52c64d](https://linux-hardware.org/?probe=8c0f52c64d) | Jun 08, 2021 |
| HP            | OMEN by HP Laptop           | [8f4c9482d3](https://linux-hardware.org/?probe=8f4c9482d3) | Jun 07, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [47a618e206](https://linux-hardware.org/?probe=47a618e206) | Jun 07, 2021 |
| HP            | ProBook 470 G5              | [517c800c42](https://linux-hardware.org/?probe=517c800c42) | Jun 07, 2021 |
| Lenovo        | ThinkPad X220 4290LT8       | [281446b9b1](https://linux-hardware.org/?probe=281446b9b1) | Jun 07, 2021 |
| Dell          | XPS 13 9300                 | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [c98bcbf189](https://linux-hardware.org/?probe=c98bcbf189) | Jun 07, 2021 |
| HP            | ProBook 450 G5              | [3f5df2365c](https://linux-hardware.org/?probe=3f5df2365c) | Jun 07, 2021 |
| Dell          | Latitude 7370               | [ddfe1dc0a3](https://linux-hardware.org/?probe=ddfe1dc0a3) | Jun 07, 2021 |
| HP            | Pavilion 15                 | [010da56dde](https://linux-hardware.org/?probe=010da56dde) | Jun 06, 2021 |
| Acer          | Nitro AN517-52              | [c79b400454](https://linux-hardware.org/?probe=c79b400454) | Jun 06, 2021 |
| Dell          | XPS 13 7390                 | [4d157e0cce](https://linux-hardware.org/?probe=4d157e0cce) | Jun 06, 2021 |
| ASUSTek       | T100TA                      | [6bd42268f6](https://linux-hardware.org/?probe=6bd42268f6) | Jun 05, 2021 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [da76c3ea04](https://linux-hardware.org/?probe=da76c3ea04) | Jun 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [25a53bf5a0](https://linux-hardware.org/?probe=25a53bf5a0) | Jun 05, 2021 |
| Apple         | MacBookPro9,2               | [4fb050f895](https://linux-hardware.org/?probe=4fb050f895) | Jun 05, 2021 |
| Dell          | Latitude E7440              | [32b9a694b3](https://linux-hardware.org/?probe=32b9a694b3) | Jun 04, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [43a9dc51d9](https://linux-hardware.org/?probe=43a9dc51d9) | Jun 04, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [4023b437d2](https://linux-hardware.org/?probe=4023b437d2) | Jun 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [b967eaa6db](https://linux-hardware.org/?probe=b967eaa6db) | Jun 03, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [00119f7ba5](https://linux-hardware.org/?probe=00119f7ba5) | Jun 03, 2021 |
| Dell          | XPS 15 9500                 | [1cba119582](https://linux-hardware.org/?probe=1cba119582) | Jun 03, 2021 |
| Acer          | Swift SF315-52G             | [8ed81a9451](https://linux-hardware.org/?probe=8ed81a9451) | Jun 02, 2021 |
| Acer          | Swift SF315-52G             | [5d8e928b43](https://linux-hardware.org/?probe=5d8e928b43) | Jun 02, 2021 |
| ASUSTek       | N550JV                      | [475195dcd9](https://linux-hardware.org/?probe=475195dcd9) | Jun 01, 2021 |
| HP            | 240 G4 Notebook PC          | [e47851b0ed](https://linux-hardware.org/?probe=e47851b0ed) | Jun 01, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [90afa2df5b](https://linux-hardware.org/?probe=90afa2df5b) | Jun 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [9c3ecf7ae2](https://linux-hardware.org/?probe=9c3ecf7ae2) | Jun 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [a6131ffc39](https://linux-hardware.org/?probe=a6131ffc39) | Jun 01, 2021 |
| Acer          | Swift SF314-56              | [1b59a580ea](https://linux-hardware.org/?probe=1b59a580ea) | Jun 01, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [add3cc76ee](https://linux-hardware.org/?probe=add3cc76ee) | Jun 01, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [5441c2ab6f](https://linux-hardware.org/?probe=5441c2ab6f) | Jun 01, 2021 |
| HP            | 240 G4 Notebook PC          | [0a9b2c114f](https://linux-hardware.org/?probe=0a9b2c114f) | Jun 01, 2021 |
| HP            | Laptop 15-bs0xx             | [5e75af2ba4](https://linux-hardware.org/?probe=5e75af2ba4) | May 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [af8045a7b3](https://linux-hardware.org/?probe=af8045a7b3) | May 31, 2021 |
| HP            | Notebook                    | [7493540206](https://linux-hardware.org/?probe=7493540206) | May 31, 2021 |
| HP            | Notebook                    | [eaabc0c626](https://linux-hardware.org/?probe=eaabc0c626) | May 31, 2021 |
| Login Info... | LOG-QAL30                   | [4caf31da4e](https://linux-hardware.org/?probe=4caf31da4e) | May 31, 2021 |
| ASUSTek       | K54C                        | [389e1a52a6](https://linux-hardware.org/?probe=389e1a52a6) | May 31, 2021 |
| Timi          | RedmiBook 14 II             | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| HP            | EliteBook 745 G4            | [c401996108](https://linux-hardware.org/?probe=c401996108) | May 31, 2021 |
| Dell          | Latitude 7490               | [a92377cb2a](https://linux-hardware.org/?probe=a92377cb2a) | May 31, 2021 |
| ASUSTek       | TUF Gaming FX505DD_TUF50... | [d8a3297ab9](https://linux-hardware.org/?probe=d8a3297ab9) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [80a31f37f4](https://linux-hardware.org/?probe=80a31f37f4) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [5002e43f11](https://linux-hardware.org/?probe=5002e43f11) | May 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0449b14156](https://linux-hardware.org/?probe=0449b14156) | May 30, 2021 |
| ASUSTek       | X750JN                      | [1f075feb49](https://linux-hardware.org/?probe=1f075feb49) | May 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [00c5d17913](https://linux-hardware.org/?probe=00c5d17913) | May 30, 2021 |
| Dell          | XPS 15 9570                 | [31a6f21ccd](https://linux-hardware.org/?probe=31a6f21ccd) | May 29, 2021 |
| Dell          | Inspiron 3505               | [1b68ebc549](https://linux-hardware.org/?probe=1b68ebc549) | May 29, 2021 |
| MSI           | PX60 6QE                    | [eca3f4ce76](https://linux-hardware.org/?probe=eca3f4ce76) | May 29, 2021 |
| Samsung       | 700T                        | [374154a439](https://linux-hardware.org/?probe=374154a439) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [af407b12e2](https://linux-hardware.org/?probe=af407b12e2) | May 29, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [35941050e8](https://linux-hardware.org/?probe=35941050e8) | May 29, 2021 |
| Dell          | XPS 13 9310                 | [7a13082af6](https://linux-hardware.org/?probe=7a13082af6) | May 29, 2021 |
| HUAWEI        | KPR-WX9                     | [9c73a8d7d6](https://linux-hardware.org/?probe=9c73a8d7d6) | May 29, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [1268e75895](https://linux-hardware.org/?probe=1268e75895) | May 29, 2021 |
| Acer          | Nitro AN515-56              | [d468019e77](https://linux-hardware.org/?probe=d468019e77) | May 29, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [eee4dbbb99](https://linux-hardware.org/?probe=eee4dbbb99) | May 28, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [e8440f3a09](https://linux-hardware.org/?probe=e8440f3a09) | May 28, 2021 |
| Dell          | XPS 13 7390                 | [9e26259821](https://linux-hardware.org/?probe=9e26259821) | May 28, 2021 |
| Dell          | Inspiron 5391               | [6722a1c1a6](https://linux-hardware.org/?probe=6722a1c1a6) | May 28, 2021 |
| Dell          | Inspiron 5584               | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [7a7114baf9](https://linux-hardware.org/?probe=7a7114baf9) | May 28, 2021 |
| HP            | Pavilion 15                 | [379b83c4c6](https://linux-hardware.org/?probe=379b83c4c6) | May 27, 2021 |
| Dell          | Latitude 7490               | [879fc7a838](https://linux-hardware.org/?probe=879fc7a838) | May 27, 2021 |
| HP            | Laptop 17-bs1xx             | [582d387cec](https://linux-hardware.org/?probe=582d387cec) | May 27, 2021 |
| Lenovo        | ThinkPad T450 20BUS0WK03    | [6131e3c22a](https://linux-hardware.org/?probe=6131e3c22a) | May 27, 2021 |
| MSI           | GF63 Thin 9SC               | [95561ae2cf](https://linux-hardware.org/?probe=95561ae2cf) | May 27, 2021 |
| Dell          | Latitude 5480               | [8a2f2558ac](https://linux-hardware.org/?probe=8a2f2558ac) | May 27, 2021 |
| Dell          | Latitude 5480               | [faa9bc7f20](https://linux-hardware.org/?probe=faa9bc7f20) | May 27, 2021 |
| Apple         | MacBookPro11,3              | [07190ac752](https://linux-hardware.org/?probe=07190ac752) | May 27, 2021 |
| Acer          | Aspire F5-573G              | [7d0b344759](https://linux-hardware.org/?probe=7d0b344759) | May 27, 2021 |
| Acer          | Aspire F5-573G              | [bfb194b61c](https://linux-hardware.org/?probe=bfb194b61c) | May 27, 2021 |
| Dell          | Inspiron N5110              | [ff37a9c00d](https://linux-hardware.org/?probe=ff37a9c00d) | May 27, 2021 |
| System76      | Oryx Pro                    | [a3d9cae93e](https://linux-hardware.org/?probe=a3d9cae93e) | May 27, 2021 |
| HP            | Laptop 15-bs0xx             | [8e85b5f3cf](https://linux-hardware.org/?probe=8e85b5f3cf) | May 26, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [22f2fd6b39](https://linux-hardware.org/?probe=22f2fd6b39) | May 26, 2021 |
| Lenovo        | G510 20238                  | [7fb630f632](https://linux-hardware.org/?probe=7fb630f632) | May 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001BUK     | [fb9abea0c5](https://linux-hardware.org/?probe=fb9abea0c5) | May 26, 2021 |
| HP            | EliteBook Folio 9470m       | [8c36612ff4](https://linux-hardware.org/?probe=8c36612ff4) | May 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [fbf4582983](https://linux-hardware.org/?probe=fbf4582983) | May 25, 2021 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [6cdaad9758](https://linux-hardware.org/?probe=6cdaad9758) | May 25, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [2ffefbd96c](https://linux-hardware.org/?probe=2ffefbd96c) | May 25, 2021 |
| Acer          | Aspire A315-41G             | [8dab17c109](https://linux-hardware.org/?probe=8dab17c109) | May 25, 2021 |
| HP            | ZBook Studio G5             | [522583da69](https://linux-hardware.org/?probe=522583da69) | May 25, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [e4c4563465](https://linux-hardware.org/?probe=e4c4563465) | May 24, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [980ef053d1](https://linux-hardware.org/?probe=980ef053d1) | May 24, 2021 |
| HP            | Laptop 15-bs0xx             | [be51fbb033](https://linux-hardware.org/?probe=be51fbb033) | May 24, 2021 |
| HP            | Laptop 15-bs0xx             | [8ffe17b548](https://linux-hardware.org/?probe=8ffe17b548) | May 24, 2021 |
| NEC Comput... | PC-VK25MXZCB                | [0a1b7b959f](https://linux-hardware.org/?probe=0a1b7b959f) | May 24, 2021 |
| Timi          | RedmiBook 16                | [6ec8bb7df6](https://linux-hardware.org/?probe=6ec8bb7df6) | May 24, 2021 |
| Apple         | MacBookPro11,3              | [4d0c48aa12](https://linux-hardware.org/?probe=4d0c48aa12) | May 24, 2021 |
| Apple         | MacBookPro11,3              | [07a4b88864](https://linux-hardware.org/?probe=07a4b88864) | May 24, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [55abc8169d](https://linux-hardware.org/?probe=55abc8169d) | May 24, 2021 |
| Dell          | Latitude 5480               | [bc9170f4cd](https://linux-hardware.org/?probe=bc9170f4cd) | May 23, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | [93b4f5b14e](https://linux-hardware.org/?probe=93b4f5b14e) | May 22, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [2198e565bf](https://linux-hardware.org/?probe=2198e565bf) | May 22, 2021 |
| Wortmann      | 1220692_1470187             | [8febf0d66c](https://linux-hardware.org/?probe=8febf0d66c) | May 22, 2021 |
| Notebook      | NH5x_7xDPx                  | [4a9dd7d6a1](https://linux-hardware.org/?probe=4a9dd7d6a1) | May 22, 2021 |
| HP            | Pavilion dv7                | [f04eba21ce](https://linux-hardware.org/?probe=f04eba21ce) | May 22, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [f367112b19](https://linux-hardware.org/?probe=f367112b19) | May 22, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [893f642cbb](https://linux-hardware.org/?probe=893f642cbb) | May 22, 2021 |
| Positivo      | CHT14B                      | [4aab647b4f](https://linux-hardware.org/?probe=4aab647b4f) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d5ea76578b](https://linux-hardware.org/?probe=d5ea76578b) | May 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [0ccd96a39e](https://linux-hardware.org/?probe=0ccd96a39e) | May 21, 2021 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [6ca37bdf8b](https://linux-hardware.org/?probe=6ca37bdf8b) | May 21, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [0ab74390ed](https://linux-hardware.org/?probe=0ab74390ed) | May 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [0a4bf488d4](https://linux-hardware.org/?probe=0a4bf488d4) | May 21, 2021 |
| HP            | Notebook                    | [1ce5457d13](https://linux-hardware.org/?probe=1ce5457d13) | May 21, 2021 |
| HP            | Notebook                    | [42756549fb](https://linux-hardware.org/?probe=42756549fb) | May 21, 2021 |
| ASUSTek       | X540YA                      | [c7d85ee10a](https://linux-hardware.org/?probe=c7d85ee10a) | May 21, 2021 |
| HP            | Laptop 15-da0xxx            | [197cbc5a5d](https://linux-hardware.org/?probe=197cbc5a5d) | May 21, 2021 |
| Dell          | XPS 15 9500                 | [b17a5c4cd5](https://linux-hardware.org/?probe=b17a5c4cd5) | May 21, 2021 |
| HP            | Pavilion dv7                | [f908acc1ad](https://linux-hardware.org/?probe=f908acc1ad) | May 20, 2021 |
| Apple         | MacBookPro11,5              | [550a3398ee](https://linux-hardware.org/?probe=550a3398ee) | May 20, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [c0b08eec61](https://linux-hardware.org/?probe=c0b08eec61) | May 20, 2021 |
| Lenovo        | ThinkPad P50 20EN0013US     | [88a08a450d](https://linux-hardware.org/?probe=88a08a450d) | May 20, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [7f2f6d6fc2](https://linux-hardware.org/?probe=7f2f6d6fc2) | May 20, 2021 |
| ASUSTek       | GL502VMK                    | [0d9f5609e7](https://linux-hardware.org/?probe=0d9f5609e7) | May 20, 2021 |
| Dell          | XPS 15 9550                 | [3366809177](https://linux-hardware.org/?probe=3366809177) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS2820... | [4ec9eaac2f](https://linux-hardware.org/?probe=4ec9eaac2f) | May 19, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [666ddeb09c](https://linux-hardware.org/?probe=666ddeb09c) | May 19, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [01af2920f0](https://linux-hardware.org/?probe=01af2920f0) | May 19, 2021 |
| Dell          | XPS 15 9500                 | [f2205716bb](https://linux-hardware.org/?probe=f2205716bb) | May 19, 2021 |
| Dell          | Inspiron 7737               | [ed5c16c955](https://linux-hardware.org/?probe=ed5c16c955) | May 19, 2021 |
| SLIMBOOK      | PROX15-AMD                  | [d80f4e83a0](https://linux-hardware.org/?probe=d80f4e83a0) | May 19, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [883f67612b](https://linux-hardware.org/?probe=883f67612b) | May 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c2267f8dd1](https://linux-hardware.org/?probe=c2267f8dd1) | May 19, 2021 |
| Acer          | Nitro AN515-42              | [507cb00cac](https://linux-hardware.org/?probe=507cb00cac) | May 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4a21e62a29](https://linux-hardware.org/?probe=4a21e62a29) | May 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [039435162c](https://linux-hardware.org/?probe=039435162c) | May 19, 2021 |
| Dell          | Inspiron 3421               | [4c5ee61420](https://linux-hardware.org/?probe=4c5ee61420) | May 19, 2021 |
| ASUSTek       | X510URR                     | [51577f00b4](https://linux-hardware.org/?probe=51577f00b4) | May 18, 2021 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [abdc61ad94](https://linux-hardware.org/?probe=abdc61ad94) | May 18, 2021 |
| ASUSTek       | X510URR                     | [e373dac808](https://linux-hardware.org/?probe=e373dac808) | May 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [56baaff907](https://linux-hardware.org/?probe=56baaff907) | May 18, 2021 |
| Samsung       | R580/R590                   | [41ca2c7546](https://linux-hardware.org/?probe=41ca2c7546) | May 18, 2021 |
| Acer          | Aspire A515-52              | [d2e4a69c16](https://linux-hardware.org/?probe=d2e4a69c16) | May 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS1B803    | [ae357880c6](https://linux-hardware.org/?probe=ae357880c6) | May 18, 2021 |
| Dell          | Latitude 7400               | [660659882e](https://linux-hardware.org/?probe=660659882e) | May 17, 2021 |
| Dell          | Latitude 7400               | [4901f6b836](https://linux-hardware.org/?probe=4901f6b836) | May 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e32d9effa0](https://linux-hardware.org/?probe=e32d9effa0) | May 17, 2021 |
| Lenovo        | V130-15IKB 81HN             | [3630dfb215](https://linux-hardware.org/?probe=3630dfb215) | May 17, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [c98ee08146](https://linux-hardware.org/?probe=c98ee08146) | May 17, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [d8cec0c95b](https://linux-hardware.org/?probe=d8cec0c95b) | May 17, 2021 |
| Dell          | G5 5590                     | [18621bd612](https://linux-hardware.org/?probe=18621bd612) | May 17, 2021 |
| Dell          | G5 5590                     | [3f55c4844d](https://linux-hardware.org/?probe=3f55c4844d) | May 17, 2021 |
| Dell          | Precision 5540              | [91e4aff19e](https://linux-hardware.org/?probe=91e4aff19e) | May 17, 2021 |
| Dell          | XPS 13 9350                 | [42eddedfb8](https://linux-hardware.org/?probe=42eddedfb8) | May 17, 2021 |
| Lenovo        | ThinkPad T440p 20AW009YB... | [1dda6f002e](https://linux-hardware.org/?probe=1dda6f002e) | May 16, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [51c5d13230](https://linux-hardware.org/?probe=51c5d13230) | May 16, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [557f952ce8](https://linux-hardware.org/?probe=557f952ce8) | May 16, 2021 |
| Sony          | VPCS12C5E                   | [188765c8f8](https://linux-hardware.org/?probe=188765c8f8) | May 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a035be3ea2](https://linux-hardware.org/?probe=a035be3ea2) | May 16, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [1579b9c9d7](https://linux-hardware.org/?probe=1579b9c9d7) | May 16, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [15a742842f](https://linux-hardware.org/?probe=15a742842f) | May 16, 2021 |
| Apple         | MacBookPro14,1              | [620cd76f75](https://linux-hardware.org/?probe=620cd76f75) | May 15, 2021 |
| Lenovo        | IdeaPad 330S-15IKB GTX10... | [0f8a6b3dcf](https://linux-hardware.org/?probe=0f8a6b3dcf) | May 15, 2021 |
| HP            | 15 Notebook PC              | [310752864a](https://linux-hardware.org/?probe=310752864a) | May 15, 2021 |
| Dell          | Latitude 5480               | [2c7c1983ac](https://linux-hardware.org/?probe=2c7c1983ac) | May 15, 2021 |
| ASUSTek       | N56VZ                       | [16d1cff353](https://linux-hardware.org/?probe=16d1cff353) | May 14, 2021 |
| Acer          | Nitro AN515-42              | [ffe39a0c5a](https://linux-hardware.org/?probe=ffe39a0c5a) | May 14, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [674a800477](https://linux-hardware.org/?probe=674a800477) | May 14, 2021 |
| HP            | EliteBook 850 G3            | [cb589a4d2c](https://linux-hardware.org/?probe=cb589a4d2c) | May 14, 2021 |
| HP            | EliteBook 850 G3            | [00a23f1149](https://linux-hardware.org/?probe=00a23f1149) | May 14, 2021 |
| Irbis         | TW94                        | [099d5c86c3](https://linux-hardware.org/?probe=099d5c86c3) | May 14, 2021 |
| HP            | EliteBook 850 G3            | [0885b824f7](https://linux-hardware.org/?probe=0885b824f7) | May 13, 2021 |
| HP            | EliteBook 850 G3            | [231212bfe0](https://linux-hardware.org/?probe=231212bfe0) | May 13, 2021 |
| Dell          | Latitude 7490               | [c533165389](https://linux-hardware.org/?probe=c533165389) | May 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [91d1b5e802](https://linux-hardware.org/?probe=91d1b5e802) | May 13, 2021 |
| Lenovo        | ThinkPad T490s 20NYS04V0... | [18da93a841](https://linux-hardware.org/?probe=18da93a841) | May 12, 2021 |
| HP            | ProBook 4530s               | [3d5a77511e](https://linux-hardware.org/?probe=3d5a77511e) | May 12, 2021 |
| Dell          | Inspiron 5555               | [e0a49e12f1](https://linux-hardware.org/?probe=e0a49e12f1) | May 12, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [b526eddd71](https://linux-hardware.org/?probe=b526eddd71) | May 12, 2021 |
| ASUSTek       | UX330UAK                    | [0abe5082fe](https://linux-hardware.org/?probe=0abe5082fe) | May 12, 2021 |
| ASUSTek       | UX330UAK                    | [0f72a78d10](https://linux-hardware.org/?probe=0f72a78d10) | May 12, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [eeac0e0535](https://linux-hardware.org/?probe=eeac0e0535) | May 12, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [dc39103e2e](https://linux-hardware.org/?probe=dc39103e2e) | May 12, 2021 |
| Apple         | MacBookPro9,2               | [d2951f517e](https://linux-hardware.org/?probe=d2951f517e) | May 12, 2021 |
| Dell          | Inspiron N5010              | [c4c9a421b7](https://linux-hardware.org/?probe=c4c9a421b7) | May 12, 2021 |
| ASUSTek       | X555LB                      | [10b0865cab](https://linux-hardware.org/?probe=10b0865cab) | May 12, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [744242646f](https://linux-hardware.org/?probe=744242646f) | May 12, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [c5e4ff103f](https://linux-hardware.org/?probe=c5e4ff103f) | May 11, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ad9a7e706d](https://linux-hardware.org/?probe=ad9a7e706d) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [049f443199](https://linux-hardware.org/?probe=049f443199) | May 11, 2021 |
| Unknown       | Unknown                     | [6b7557c4d1](https://linux-hardware.org/?probe=6b7557c4d1) | May 11, 2021 |
| Dell          | Latitude E6320              | [3d76e2296e](https://linux-hardware.org/?probe=3d76e2296e) | May 11, 2021 |
| HP            | 15 Notebook PC              | [6afabfb5b3](https://linux-hardware.org/?probe=6afabfb5b3) | May 11, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | [02280704ba](https://linux-hardware.org/?probe=02280704ba) | May 11, 2021 |
| HP            | 15 Notebook PC              | [1c1e7aeecf](https://linux-hardware.org/?probe=1c1e7aeecf) | May 11, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [fcc03f3447](https://linux-hardware.org/?probe=fcc03f3447) | May 11, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [6410919f51](https://linux-hardware.org/?probe=6410919f51) | May 10, 2021 |
| Positivo      | Q4128C-S                    | [15db0dcbec](https://linux-hardware.org/?probe=15db0dcbec) | May 10, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | [bb0d6e1883](https://linux-hardware.org/?probe=bb0d6e1883) | May 10, 2021 |
| AZW           | Z83-V                       | [6ca32efbd7](https://linux-hardware.org/?probe=6ca32efbd7) | May 10, 2021 |
| HP            | ProBook 470 G5              | [22781d64e0](https://linux-hardware.org/?probe=22781d64e0) | May 10, 2021 |
| HP            | ProBook 440 G8 Notebook ... | [b61a1c61d8](https://linux-hardware.org/?probe=b61a1c61d8) | May 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [c9b4ee21fd](https://linux-hardware.org/?probe=c9b4ee21fd) | May 10, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [c4df22f011](https://linux-hardware.org/?probe=c4df22f011) | May 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a1e5c2f4f5](https://linux-hardware.org/?probe=a1e5c2f4f5) | May 09, 2021 |
| HP            | ProBook 470 G5              | [f66084bbd9](https://linux-hardware.org/?probe=f66084bbd9) | May 09, 2021 |
| HP            | EliteBook 840 G6            | [08d59f23ab](https://linux-hardware.org/?probe=08d59f23ab) | May 09, 2021 |
| Lenovo        | ThinkPad P1 20MD001VUS      | [23c21ceedf](https://linux-hardware.org/?probe=23c21ceedf) | May 08, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [75431661e3](https://linux-hardware.org/?probe=75431661e3) | May 08, 2021 |
| HP            | Laptop 15s-du3xxx           | [25f309da06](https://linux-hardware.org/?probe=25f309da06) | May 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [dc95288d50](https://linux-hardware.org/?probe=dc95288d50) | May 08, 2021 |
| Lenovo        | ThinkPad P1 20MD001VUS      | [ec32719d86](https://linux-hardware.org/?probe=ec32719d86) | May 08, 2021 |
| Positivo      | C41TB                       | [060b2d882f](https://linux-hardware.org/?probe=060b2d882f) | May 08, 2021 |
| Dell          | Precision M4600             | [9f1f5b7ef7](https://linux-hardware.org/?probe=9f1f5b7ef7) | May 08, 2021 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [155ecefe3c](https://linux-hardware.org/?probe=155ecefe3c) | May 07, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [f34f4b2b22](https://linux-hardware.org/?probe=f34f4b2b22) | May 07, 2021 |
| Dell          | XPS 13 9310                 | [8d372d62b7](https://linux-hardware.org/?probe=8d372d62b7) | May 07, 2021 |
| Dell          | Latitude 5480               | [05ee730b0f](https://linux-hardware.org/?probe=05ee730b0f) | May 07, 2021 |
| Toshiba       | Satellite Click Mini L9W... | [b6204cb85d](https://linux-hardware.org/?probe=b6204cb85d) | May 07, 2021 |
| HP            | EliteBook 850 G3            | [85a71e335a](https://linux-hardware.org/?probe=85a71e335a) | May 06, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [91b671b246](https://linux-hardware.org/?probe=91b671b246) | May 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [d186bad578](https://linux-hardware.org/?probe=d186bad578) | May 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [9036e74d34](https://linux-hardware.org/?probe=9036e74d34) | May 06, 2021 |
| Unknown       | Unknown                     | [50d2466e84](https://linux-hardware.org/?probe=50d2466e84) | May 06, 2021 |
| Dell          | Latitude 5520               | [3d5b6379e3](https://linux-hardware.org/?probe=3d5b6379e3) | May 06, 2021 |
| Unknown       | Unknown                     | [410d40ca5f](https://linux-hardware.org/?probe=410d40ca5f) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [06d44f569d](https://linux-hardware.org/?probe=06d44f569d) | May 06, 2021 |
| Acer          | Aspire E5-576               | [58d3bc658d](https://linux-hardware.org/?probe=58d3bc658d) | May 06, 2021 |
| Acer          | Aspire E5-576               | [ee72676e37](https://linux-hardware.org/?probe=ee72676e37) | May 05, 2021 |
| Dell          | Latitude 5480               | [08f77f376e](https://linux-hardware.org/?probe=08f77f376e) | May 05, 2021 |
| Samsung       | R520/R522/R620              | [bf28931c58](https://linux-hardware.org/?probe=bf28931c58) | May 05, 2021 |
| HP            | ProBook 6460b               | [939b480c49](https://linux-hardware.org/?probe=939b480c49) | May 05, 2021 |
| Apple         | MacBookPro11,1              | [ce9091f8ae](https://linux-hardware.org/?probe=ce9091f8ae) | May 05, 2021 |
| HP            | G42                         | [4a107897cf](https://linux-hardware.org/?probe=4a107897cf) | May 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [9e64212d9f](https://linux-hardware.org/?probe=9e64212d9f) | May 05, 2021 |
| Dell          | Latitude 7400               | [a32714d409](https://linux-hardware.org/?probe=a32714d409) | May 05, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [05f84c951f](https://linux-hardware.org/?probe=05f84c951f) | May 05, 2021 |
| Dell          | Latitude 7400               | [eb8ca2d9d2](https://linux-hardware.org/?probe=eb8ca2d9d2) | May 05, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0NS0... | [6c0c3b3ea0](https://linux-hardware.org/?probe=6c0c3b3ea0) | May 05, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | [035481a413](https://linux-hardware.org/?probe=035481a413) | May 05, 2021 |
| Lenovo        | ThinkPad Edge E535 32607... | [b8627e7f6d](https://linux-hardware.org/?probe=b8627e7f6d) | May 05, 2021 |
| Acer          | Aspire V3-574G              | [507422ce0b](https://linux-hardware.org/?probe=507422ce0b) | May 05, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [1fefa80fdd](https://linux-hardware.org/?probe=1fefa80fdd) | May 05, 2021 |
| MSI           | CX61 2PC                    | [e0f172fbd5](https://linux-hardware.org/?probe=e0f172fbd5) | May 05, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1d8be54bc6](https://linux-hardware.org/?probe=1d8be54bc6) | May 04, 2021 |
| Fujitsu       | LIFEBOOK E780               | [79dc3442b5](https://linux-hardware.org/?probe=79dc3442b5) | May 04, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | [6d2bb231a4](https://linux-hardware.org/?probe=6d2bb231a4) | May 04, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | [1ea17840d1](https://linux-hardware.org/?probe=1ea17840d1) | May 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [aa18447496](https://linux-hardware.org/?probe=aa18447496) | May 03, 2021 |
| Acer          | Nitro AN515-44              | [c118461e82](https://linux-hardware.org/?probe=c118461e82) | May 03, 2021 |
| Dell          | Latitude E5420              | [989dd7d36f](https://linux-hardware.org/?probe=989dd7d36f) | May 03, 2021 |
| HUAWEI        | EUL-WX9                     | [e59bd99fd2](https://linux-hardware.org/?probe=e59bd99fd2) | May 03, 2021 |
| ordissimo     | E17201                      | [ada3ab54e0](https://linux-hardware.org/?probe=ada3ab54e0) | May 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ0R    | [11c98724d5](https://linux-hardware.org/?probe=11c98724d5) | May 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ0R    | [6b88e1bda9](https://linux-hardware.org/?probe=6b88e1bda9) | May 03, 2021 |
| Dell          | Inspiron 3593               | [4ade35b9d9](https://linux-hardware.org/?probe=4ade35b9d9) | May 02, 2021 |
| MSI           | Bravo 15 A4DDR              | [649dbceeff](https://linux-hardware.org/?probe=649dbceeff) | May 02, 2021 |
| Dell          | XPS 15 9550                 | [30b952e127](https://linux-hardware.org/?probe=30b952e127) | May 02, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1707ff6faf](https://linux-hardware.org/?probe=1707ff6faf) | May 02, 2021 |
| Samsung       | R520/R522/R620              | [95581f21a3](https://linux-hardware.org/?probe=95581f21a3) | May 01, 2021 |
| HP            | Pavilion dv7                | [98693d2a86](https://linux-hardware.org/?probe=98693d2a86) | May 01, 2021 |
| HP            | Pavilion dv7                | [bd65b55f0a](https://linux-hardware.org/?probe=bd65b55f0a) | May 01, 2021 |
| HP            | ProBook 4525s               | [809516ad9a](https://linux-hardware.org/?probe=809516ad9a) | May 01, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [285dfaddb2](https://linux-hardware.org/?probe=285dfaddb2) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [857022f167](https://linux-hardware.org/?probe=857022f167) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [a6afe0cc34](https://linux-hardware.org/?probe=a6afe0cc34) | May 01, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [0790e842a9](https://linux-hardware.org/?probe=0790e842a9) | May 01, 2021 |
| HP            | ProBook 430 G5              | [18081fbf4f](https://linux-hardware.org/?probe=18081fbf4f) | May 01, 2021 |
| Apple         | MacBookPro7,1               | [c00cb7a2c9](https://linux-hardware.org/?probe=c00cb7a2c9) | May 01, 2021 |
| Lenovo        | ThinkPad T460s 20FAS2BN0... | [8e3b1498da](https://linux-hardware.org/?probe=8e3b1498da) | Apr 30, 2021 |
| HP            | Laptop 15-db0xxx            | [0b1a312f87](https://linux-hardware.org/?probe=0b1a312f87) | Apr 30, 2021 |
| Dell          | XPS 13 7390                 | [2c97753280](https://linux-hardware.org/?probe=2c97753280) | Apr 30, 2021 |
| HP            | ProBook 470 G5              | [f37646891f](https://linux-hardware.org/?probe=f37646891f) | Apr 30, 2021 |
| HP            | ProBook 470 G5              | [b9dbe92598](https://linux-hardware.org/?probe=b9dbe92598) | Apr 30, 2021 |
| Acer          | Aspire F5-571G              | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| Notebook      | PB50_70DFx,DDx              | [e0484075af](https://linux-hardware.org/?probe=e0484075af) | Apr 30, 2021 |
| Dell          | Latitude 5480               | [a9a63b3679](https://linux-hardware.org/?probe=a9a63b3679) | Apr 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3401ccaf08](https://linux-hardware.org/?probe=3401ccaf08) | Apr 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [be1fac0a5c](https://linux-hardware.org/?probe=be1fac0a5c) | Apr 29, 2021 |
| Dell          | Inspiron 13-5378            | [e36e444bac](https://linux-hardware.org/?probe=e36e444bac) | Apr 29, 2021 |
| Acer          | Aspire V5-571G              | [89cb767ad1](https://linux-hardware.org/?probe=89cb767ad1) | Apr 29, 2021 |
| HP            | EliteBook 840 G3            | [880e12969e](https://linux-hardware.org/?probe=880e12969e) | Apr 29, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | [b4ec0e1cfe](https://linux-hardware.org/?probe=b4ec0e1cfe) | Apr 29, 2021 |
| ASUSTek       | G74Sx                       | [73c1eaa647](https://linux-hardware.org/?probe=73c1eaa647) | Apr 29, 2021 |
| HP            | EliteBook 850 G5            | [3b2545921f](https://linux-hardware.org/?probe=3b2545921f) | Apr 29, 2021 |
| HP            | ProBook 4525s               | [78228915c0](https://linux-hardware.org/?probe=78228915c0) | Apr 28, 2021 |
| System76      | Oryx Pro                    | [8c925dbcbe](https://linux-hardware.org/?probe=8c925dbcbe) | Apr 28, 2021 |
| Dell          | XPS 15 7590                 | [b73eecf0c5](https://linux-hardware.org/?probe=b73eecf0c5) | Apr 28, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [190564ec8e](https://linux-hardware.org/?probe=190564ec8e) | Apr 28, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | [267f4b13f7](https://linux-hardware.org/?probe=267f4b13f7) | Apr 28, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [f603a8365a](https://linux-hardware.org/?probe=f603a8365a) | Apr 28, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [e259d34a4c](https://linux-hardware.org/?probe=e259d34a4c) | Apr 28, 2021 |
| Dell          | Inspiron 13-5378            | [9edeb6f6ad](https://linux-hardware.org/?probe=9edeb6f6ad) | Apr 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [2a73d602a7](https://linux-hardware.org/?probe=2a73d602a7) | Apr 28, 2021 |
| Lenovo        | ThinkPad T430 2347G2P       | [c1fa54ec47](https://linux-hardware.org/?probe=c1fa54ec47) | Apr 28, 2021 |
| Lenovo        | ThinkPad T460p 20FXS1SX0... | [9595aedbc6](https://linux-hardware.org/?probe=9595aedbc6) | Apr 28, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [ad0dfb309f](https://linux-hardware.org/?probe=ad0dfb309f) | Apr 27, 2021 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [c1a5d52c30](https://linux-hardware.org/?probe=c1a5d52c30) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [f67c550f8e](https://linux-hardware.org/?probe=f67c550f8e) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [0876a200b7](https://linux-hardware.org/?probe=0876a200b7) | Apr 27, 2021 |
| Positivo      | C41TB                       | [1d746150af](https://linux-hardware.org/?probe=1d746150af) | Apr 26, 2021 |
| Chuwi         | CoreBook Pro                | [ca84914f1d](https://linux-hardware.org/?probe=ca84914f1d) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [e4b338aa1a](https://linux-hardware.org/?probe=e4b338aa1a) | Apr 25, 2021 |
| Positivo      | C41TB                       | [179c326307](https://linux-hardware.org/?probe=179c326307) | Apr 25, 2021 |
| HP            | 246 G7 Notebook PC          | [a1ab7115cf](https://linux-hardware.org/?probe=a1ab7115cf) | Apr 25, 2021 |
| Dell          | Latitude 5511               | [4884be79b4](https://linux-hardware.org/?probe=4884be79b4) | Apr 24, 2021 |
| Dell          | Latitude 5511               | [f9f9c1acaa](https://linux-hardware.org/?probe=f9f9c1acaa) | Apr 24, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [140e992105](https://linux-hardware.org/?probe=140e992105) | Apr 24, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [557ef5a2ae](https://linux-hardware.org/?probe=557ef5a2ae) | Apr 23, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [1c206551a3](https://linux-hardware.org/?probe=1c206551a3) | Apr 22, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [fa4b4edcec](https://linux-hardware.org/?probe=fa4b4edcec) | Apr 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [926fa9f69a](https://linux-hardware.org/?probe=926fa9f69a) | Apr 21, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [c4f21a1871](https://linux-hardware.org/?probe=c4f21a1871) | Apr 21, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ba7a3bd259](https://linux-hardware.org/?probe=ba7a3bd259) | Apr 21, 2021 |
| ASUSTek       | ZenBook UX481FAY_UX481FA    | [0ec748b06e](https://linux-hardware.org/?probe=0ec748b06e) | Apr 20, 2021 |
| ASUSTek       | ZenBook UX481FAY_UX481FA    | [79ae1f5b0c](https://linux-hardware.org/?probe=79ae1f5b0c) | Apr 20, 2021 |
| Acer          | Nitro AN515-42              | [1b6b0bfcef](https://linux-hardware.org/?probe=1b6b0bfcef) | Apr 20, 2021 |
| Acer          | Nitro AN515-42              | [94173730f8](https://linux-hardware.org/?probe=94173730f8) | Apr 20, 2021 |
| Dell          | Inspiron N5010              | [d54729d43d](https://linux-hardware.org/?probe=d54729d43d) | Apr 20, 2021 |
| Connect       | Tablet 9                    | [6d68fde5d8](https://linux-hardware.org/?probe=6d68fde5d8) | Apr 19, 2021 |
| HP            | Pavilion 15                 | [cb55fa7fcd](https://linux-hardware.org/?probe=cb55fa7fcd) | Apr 19, 2021 |
| MPMAN         | MPWIN8900CL                 | [3c21016b82](https://linux-hardware.org/?probe=3c21016b82) | Apr 19, 2021 |
| Dell          | Latitude 7410               | [d2a62b6afb](https://linux-hardware.org/?probe=d2a62b6afb) | Apr 19, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FX506... | [9d9c3e89a5](https://linux-hardware.org/?probe=9d9c3e89a5) | Apr 19, 2021 |
| Insyde        | i71c                        | [ec749b6624](https://linux-hardware.org/?probe=ec749b6624) | Apr 18, 2021 |
| ASUSTek       | X550CA                      | [103cc770c2](https://linux-hardware.org/?probe=103cc770c2) | Apr 18, 2021 |
| HP            | ProBook 470 G5              | [1f0b5b042f](https://linux-hardware.org/?probe=1f0b5b042f) | Apr 18, 2021 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [12af9205b0](https://linux-hardware.org/?probe=12af9205b0) | Apr 18, 2021 |
| HP            | Pavilion 11 x360 PC         | [8aab148f59](https://linux-hardware.org/?probe=8aab148f59) | Apr 17, 2021 |
| Teclast       | TbooK 11                    | [29537c9609](https://linux-hardware.org/?probe=29537c9609) | Apr 17, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FX506... | [f35c55ba89](https://linux-hardware.org/?probe=f35c55ba89) | Apr 17, 2021 |
| HP            | ProBook 4525s               | [5fea2f9652](https://linux-hardware.org/?probe=5fea2f9652) | Apr 17, 2021 |
| Lenovo        | IdeaPad Z580                | [757a310b4a](https://linux-hardware.org/?probe=757a310b4a) | Apr 17, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | [dc8fb53f61](https://linux-hardware.org/?probe=dc8fb53f61) | Apr 17, 2021 |
| Lenovo        | V330-14ARR 81B1             | [d79109ba72](https://linux-hardware.org/?probe=d79109ba72) | Apr 16, 2021 |
| Acer          | Aspire A315-42              | [f8d626eea1](https://linux-hardware.org/?probe=f8d626eea1) | Apr 16, 2021 |
| Dell          | Latitude 5480               | [ff6578cc63](https://linux-hardware.org/?probe=ff6578cc63) | Apr 16, 2021 |
| Shenzhen P... | MOMO7W                      | [763921a4a1](https://linux-hardware.org/?probe=763921a4a1) | Apr 16, 2021 |
| Lenovo        | ThinkPad X230 2325BP9       | [6b2b705578](https://linux-hardware.org/?probe=6b2b705578) | Apr 16, 2021 |
| Dell          | XPS 15 7590                 | [b5dda74089](https://linux-hardware.org/?probe=b5dda74089) | Apr 14, 2021 |
| Lenovo        | IdeaPad Z580                | [3089a9a333](https://linux-hardware.org/?probe=3089a9a333) | Apr 14, 2021 |
| Dell          | Latitude E6520              | [0283ca3671](https://linux-hardware.org/?probe=0283ca3671) | Apr 13, 2021 |
| Acer          | Aspire A315-55G             | [907647d9a2](https://linux-hardware.org/?probe=907647d9a2) | Apr 13, 2021 |
| Dell          | XPS 13 9360                 | [4b5e9623a8](https://linux-hardware.org/?probe=4b5e9623a8) | Apr 13, 2021 |
| Sony          | VPCSC41FM                   | [b04963620c](https://linux-hardware.org/?probe=b04963620c) | Apr 13, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [8a8adf8790](https://linux-hardware.org/?probe=8a8adf8790) | Apr 12, 2021 |
| Dell          | Inspiron N5010              | [e809ca489d](https://linux-hardware.org/?probe=e809ca489d) | Apr 12, 2021 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | [6a307c820d](https://linux-hardware.org/?probe=6a307c820d) | Apr 12, 2021 |
| HP            | ProBook 4525s               | [e6f339fbf7](https://linux-hardware.org/?probe=e6f339fbf7) | Apr 11, 2021 |
| Acer          | Swift SF314-55G             | [b9ec42b5ff](https://linux-hardware.org/?probe=b9ec42b5ff) | Apr 11, 2021 |
| Lenovo        | ThinkPad E14 20RACTO1WW     | [a1d56d3f37](https://linux-hardware.org/?probe=a1d56d3f37) | Apr 11, 2021 |
| Acer          | Nitro AN515-54              | [8cc623fb70](https://linux-hardware.org/?probe=8cc623fb70) | Apr 10, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5f52a14994](https://linux-hardware.org/?probe=5f52a14994) | Apr 10, 2021 |
| Lenovo        | ThinkPad E480 20KNS0MC00    | [92079ca9e3](https://linux-hardware.org/?probe=92079ca9e3) | Apr 10, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [8f5d7459d2](https://linux-hardware.org/?probe=8f5d7459d2) | Apr 10, 2021 |
| Standard      | Unknown                     | [2e2b5648ce](https://linux-hardware.org/?probe=2e2b5648ce) | Apr 09, 2021 |
| Notebook      | N8xEJEK                     | [4794a1ad98](https://linux-hardware.org/?probe=4794a1ad98) | Apr 09, 2021 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [006b564b4d](https://linux-hardware.org/?probe=006b564b4d) | Apr 09, 2021 |
| Acer          | Nitro AN515-44              | [c9dcfde4e1](https://linux-hardware.org/?probe=c9dcfde4e1) | Apr 09, 2021 |
| Lenovo        | V310-15IKB 80T3             | [6e1542aab7](https://linux-hardware.org/?probe=6e1542aab7) | Apr 09, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | [4e38c1e886](https://linux-hardware.org/?probe=4e38c1e886) | Apr 09, 2021 |
| Lenovo        | ThinkPad T440p 20AWS2820... | [3440af3ade](https://linux-hardware.org/?probe=3440af3ade) | Apr 09, 2021 |
| Dell          | XPS 15 9500                 | [81aeaba043](https://linux-hardware.org/?probe=81aeaba043) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [4c2971804a](https://linux-hardware.org/?probe=4c2971804a) | Apr 09, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [7730367108](https://linux-hardware.org/?probe=7730367108) | Apr 08, 2021 |
| Dell          | Inspiron 3581               | [8acf527693](https://linux-hardware.org/?probe=8acf527693) | Apr 08, 2021 |
| Lenovo        | G40-70 80GA                 | [ca5eaa8733](https://linux-hardware.org/?probe=ca5eaa8733) | Apr 08, 2021 |
| Lenovo        | ThinkPad T440p 20AWS2820... | [352aee7525](https://linux-hardware.org/?probe=352aee7525) | Apr 08, 2021 |
| ASUSTek       | X556URK                     | [0fe23f914d](https://linux-hardware.org/?probe=0fe23f914d) | Apr 06, 2021 |
| Dell          | XPS L502X                   | [fe680d21e1](https://linux-hardware.org/?probe=fe680d21e1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T490 20N20009MC    | [c40cb2c60f](https://linux-hardware.org/?probe=c40cb2c60f) | Apr 06, 2021 |
| Dell          | Inspiron 5580               | [9f4333693a](https://linux-hardware.org/?probe=9f4333693a) | Apr 06, 2021 |
| Lenovo        | ThinkPad T450s 20BX0013G... | [66d90069a1](https://linux-hardware.org/?probe=66d90069a1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T450s 20BX0013G... | [7441379cc7](https://linux-hardware.org/?probe=7441379cc7) | Apr 06, 2021 |
| Toshiba       | Satellite L50-C             | [1baa6a6817](https://linux-hardware.org/?probe=1baa6a6817) | Apr 06, 2021 |
| Dell          | XPS 13 9350                 | [07b527d603](https://linux-hardware.org/?probe=07b527d603) | Apr 05, 2021 |
| Dell          | XPS 13 9350                 | [914388c5c5](https://linux-hardware.org/?probe=914388c5c5) | Apr 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [1fe5a2530d](https://linux-hardware.org/?probe=1fe5a2530d) | Apr 05, 2021 |
| HP            | EliteBook 840 G3            | [ddfa056734](https://linux-hardware.org/?probe=ddfa056734) | Apr 05, 2021 |
| HP            | ProBook 650 G1              | [051017604f](https://linux-hardware.org/?probe=051017604f) | Apr 04, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [f1c3f62a55](https://linux-hardware.org/?probe=f1c3f62a55) | Apr 04, 2021 |
| Acer          | Nitro AN515-54              | [b865e7ccff](https://linux-hardware.org/?probe=b865e7ccff) | Apr 04, 2021 |
| HP            | Elite x2 1012 G1            | [4957115cec](https://linux-hardware.org/?probe=4957115cec) | Apr 04, 2021 |
| MSI           | GS73VR 7RG                  | [394ae3b96f](https://linux-hardware.org/?probe=394ae3b96f) | Apr 04, 2021 |
| Dell          | XPS L502X                   | [134b59c95e](https://linux-hardware.org/?probe=134b59c95e) | Apr 03, 2021 |
| Dell          | XPS L502X                   | [4b1e34e9ed](https://linux-hardware.org/?probe=4b1e34e9ed) | Apr 03, 2021 |
| ASUSTek       | UX303UA                     | [fb33764025](https://linux-hardware.org/?probe=fb33764025) | Apr 03, 2021 |
| ASUSTek       | UX303UA                     | [9c8c52cca9](https://linux-hardware.org/?probe=9c8c52cca9) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | [0984402bad](https://linux-hardware.org/?probe=0984402bad) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | [eba80415c0](https://linux-hardware.org/?probe=eba80415c0) | Apr 03, 2021 |
| Dell          | Latitude 3570               | [e83eac31ce](https://linux-hardware.org/?probe=e83eac31ce) | Apr 02, 2021 |
| Lenovo        | IdeaPad Z580                | [5af64d1099](https://linux-hardware.org/?probe=5af64d1099) | Apr 02, 2021 |
| Lenovo        | IdeaPad Z580                | [7dc56a24a6](https://linux-hardware.org/?probe=7dc56a24a6) | Apr 02, 2021 |
| System76      | Oryx Pro                    | [a2d6163aef](https://linux-hardware.org/?probe=a2d6163aef) | Apr 02, 2021 |
| System76      | Oryx Pro                    | [3b33c626bd](https://linux-hardware.org/?probe=3b33c626bd) | Apr 02, 2021 |
| HP            | EliteBook 755 G2            | [12cd60c247](https://linux-hardware.org/?probe=12cd60c247) | Mar 31, 2021 |
| HUAWEI        | KPL-W0X                     | [af3acea363](https://linux-hardware.org/?probe=af3acea363) | Mar 31, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [84cc759796](https://linux-hardware.org/?probe=84cc759796) | Mar 30, 2021 |
| Dell          | G5 5505                     | [466cbb0b8e](https://linux-hardware.org/?probe=466cbb0b8e) | Mar 30, 2021 |
| HP            | ProBook 4525s               | [390e030b1e](https://linux-hardware.org/?probe=390e030b1e) | Mar 29, 2021 |
| Toshiba       | TECRA Z40-A                 | [9b283640c6](https://linux-hardware.org/?probe=9b283640c6) | Mar 29, 2021 |
| HP            | EliteBook 840 G3            | [10b6c6cbc0](https://linux-hardware.org/?probe=10b6c6cbc0) | Mar 29, 2021 |
| HP            | EliteBook 840 G3            | [a0ef308b2c](https://linux-hardware.org/?probe=a0ef308b2c) | Mar 29, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6bf5c0b770](https://linux-hardware.org/?probe=6bf5c0b770) | Mar 27, 2021 |
| Dell          | Inspiron 5505               | [9b4af8147c](https://linux-hardware.org/?probe=9b4af8147c) | Mar 26, 2021 |
| Lenovo        | ThinkPad T480s 20L7001RP... | [1992bbf887](https://linux-hardware.org/?probe=1992bbf887) | Mar 24, 2021 |
| HP            | ProBook 4525s               | [e4df2fd0b0](https://linux-hardware.org/?probe=e4df2fd0b0) | Mar 24, 2021 |
| Dell          | XPS 13 9310                 | [684313d4d9](https://linux-hardware.org/?probe=684313d4d9) | Mar 24, 2021 |
| Lenovo        | ThinkPad T420 4236VD9       | [abaf5a9e37](https://linux-hardware.org/?probe=abaf5a9e37) | Mar 24, 2021 |
| ASUSTek       | UX305FA                     | [4a9ff479d0](https://linux-hardware.org/?probe=4a9ff479d0) | Mar 24, 2021 |
| HP            | Pavilion dm4                | [700de148a7](https://linux-hardware.org/?probe=700de148a7) | Mar 24, 2021 |
| Dell          | Precision 5520              | [f95b93d1ca](https://linux-hardware.org/?probe=f95b93d1ca) | Mar 23, 2021 |
| HP            | ZBook 15 G3                 | [4ab4d49018](https://linux-hardware.org/?probe=4ab4d49018) | Mar 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [25c2dd2a64](https://linux-hardware.org/?probe=25c2dd2a64) | Mar 15, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1deb9edb46](https://linux-hardware.org/?probe=1deb9edb46) | Mar 14, 2021 |
| Toshiba       | Satellite S55t-B            | [cbabe52a7f](https://linux-hardware.org/?probe=cbabe52a7f) | Mar 10, 2021 |
| Lenovo        | G50-80 80E5                 | [4336742334](https://linux-hardware.org/?probe=4336742334) | Mar 04, 2021 |
| HP            | Laptop 15-da0xxx            | [86f60bbc44](https://linux-hardware.org/?probe=86f60bbc44) | Feb 23, 2021 |
| ASUSTek       | K53SC                       | [24fe67fa00](https://linux-hardware.org/?probe=24fe67fa00) | Jan 29, 2021 |
| Dell          | Inspiron 3521               | [ce19e3ee18](https://linux-hardware.org/?probe=ce19e3ee18) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [e133316a3c](https://linux-hardware.org/?probe=e133316a3c) | Nov 28, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [f1c5e6588a](https://linux-hardware.org/?probe=f1c5e6588a) | Nov 23, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [a6e7ec5f07](https://linux-hardware.org/?probe=a6e7ec5f07) | Nov 22, 2020 |
| Lenovo        | ThinkPad X140e 20BLS0040... | [ec056bb102](https://linux-hardware.org/?probe=ec056bb102) | Nov 12, 2020 |
| Dell          | G5 5505                     | [5770e00a83](https://linux-hardware.org/?probe=5770e00a83) | Nov 11, 2020 |
| Lenovo        | ThinkPad X140e 20BLS0040... | [541347d1a0](https://linux-hardware.org/?probe=541347d1a0) | Nov 11, 2020 |
| HP            | Unknown                     | [734dd9e30e](https://linux-hardware.org/?probe=734dd9e30e) | Nov 08, 2020 |
| LG Electro... | 17Z90N-V.AA77G              | [eaeb99f180](https://linux-hardware.org/?probe=eaeb99f180) | Sep 06, 2020 |
| HP            | Notebook                    | [c5d0ec5edb](https://linux-hardware.org/?probe=c5d0ec5edb) | Aug 30, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                             | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| 5.11.12-300.fc34.x86_64                             | 50        | 7.12%   |
| 5.12.13-300.fc34.x86_64                             | 39        | 5.56%   |
| 5.12.14-300.fc34.x86_64                             | 35        | 4.99%   |
| 5.11.17-300.fc34.x86_64                             | 34        | 4.84%   |
| 5.12.8-300.fc34.x86_64                              | 28        | 3.99%   |
| 5.11.16-300.fc34.x86_64                             | 28        | 3.99%   |
| 5.12.9-300.fc34.x86_64                              | 26        | 3.7%    |
| 5.12.11-300.fc34.x86_64                             | 26        | 3.7%    |
| 5.13.8-200.fc34.x86_64                              | 25        | 3.56%   |
| 5.13.12-200.fc34.x86_64                             | 24        | 3.42%   |
| 5.11.20-300.fc34.x86_64                             | 24        | 3.42%   |
| 5.11.18-300.fc34.x86_64                             | 24        | 3.42%   |
| 5.11.11-300.fc34.x86_64                             | 24        | 3.42%   |
| 5.13.4-200.fc34.x86_64                              | 23        | 3.28%   |
| 5.13.9-200.fc34.x86_64                              | 22        | 3.13%   |
| 5.13.6-200.fc34.x86_64                              | 20        | 2.85%   |
| 5.12.10-300.fc34.x86_64                             | 20        | 2.85%   |
| 5.12.7-300.fc34.x86_64                              | 19        | 2.71%   |
| 5.11.15-300.fc34.x86_64                             | 19        | 2.71%   |
| 5.12.6-300.fc34.x86_64                              | 18        | 2.56%   |
| 5.12.15-300.fc34.x86_64                             | 18        | 2.56%   |
| 5.12.12-300.fc34.x86_64                             | 17        | 2.42%   |
| 5.13.10-200.fc34.x86_64                             | 16        | 2.28%   |
| 5.13.5-200.fc34.x86_64                              | 13        | 1.85%   |
| 5.11.21-300.fc34.x86_64                             | 12        | 1.71%   |
| 5.11.3-300.fc34.x86_64                              | 10        | 1.42%   |
| 5.11.19-300.fc34.x86_64                             | 8         | 1.14%   |
| 5.11.10-300.fc34.x86_64                             | 8         | 1.14%   |
| 5.11.14-300.fc34.x86_64                             | 7         | 1%      |
| 5.11.13-300.fc34.x86_64                             | 7         | 1%      |
| 5.12.5-300.fc34.x86_64                              | 6         | 0.85%   |
| 5.12.17-300.fc34.x86_64                             | 5         | 0.71%   |
| 5.13.7-200.fc34.x86_64                              | 4         | 0.57%   |
| 5.11.8-300.fc34.x86_64                              | 4         | 0.57%   |
| 5.11.7-300.fc34.x86_64                              | 3         | 0.43%   |
| 5.13.1-300.fc34.x86_64                              | 2         | 0.28%   |
| 5.10.0-0.rc3.68.fc34.x86_64                         | 2         | 0.28%   |
| 5.9.0-0.rc3.1.fc34.x86_64                           | 1         | 0.14%   |
| 5.8.0-1.fc33.x86_64                                 | 1         | 0.14%   |
| 5.4.111                                             | 1         | 0.14%   |
| 5.14.0-0.rc7.54.rog.fc34.x86_64                     | 1         | 0.14%   |
| 5.14.0-0.rc3.20210728git7d549995d4e0.31.fc35.x86_64 | 1         | 0.14%   |
| 5.13.9-200.rog.fc34.x86_64                          | 1         | 0.14%   |
| 5.13.6-250.vanilla.1.fc34.x86_64                    | 1         | 0.14%   |
| 5.13.2-300.fc34.x86_64                              | 1         | 0.14%   |
| 5.13.11-xm1.0.fc34.x86_64                           | 1         | 0.14%   |
| 5.13.1-xm1.0.fc34.x86_64                            | 1         | 0.14%   |
| 5.13.0-bersa1+                                      | 1         | 0.14%   |
| 5.12.8-300.fc34.aarch64                             | 1         | 0.14%   |
| 5.12.15-350.vanilla.1.fc34.x86_64                   | 1         | 0.14%   |
| 5.12.13                                             | 1         | 0.14%   |
| 5.12.11-300.mbp.fc33.x86_64                         | 1         | 0.14%   |
| 5.12.10-350.vanilla.1.fc34.x86_64                   | 1         | 0.14%   |
| 5.12.10-300.rog.fc34.x86_64                         | 1         | 0.14%   |
| 5.12.0-rc7+                                         | 1         | 0.14%   |
| 5.11.9-300.fc34.x86_64                              | 1         | 0.14%   |
| 5.11.6-300.fc34.x86_64                              | 1         | 0.14%   |
| 5.11.5-300.fc34.x86_64                              | 1         | 0.14%   |
| 5.11.2-300.fc34.x86_64                              | 1         | 0.14%   |
| 5.11.19-300.rog.fc34.x86_64                         | 1         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.11.12  | 50        | 7.12%   |
| 5.12.13  | 40        | 5.7%    |
| 5.12.14  | 35        | 4.99%   |
| 5.11.17  | 34        | 4.84%   |
| 5.12.8   | 29        | 4.13%   |
| 5.11.16  | 29        | 4.13%   |
| 5.12.11  | 27        | 3.85%   |
| 5.12.9   | 26        | 3.7%    |
| 5.13.8   | 25        | 3.56%   |
| 5.13.12  | 24        | 3.42%   |
| 5.11.20  | 24        | 3.42%   |
| 5.11.18  | 24        | 3.42%   |
| 5.11.11  | 24        | 3.42%   |
| 5.13.9   | 23        | 3.28%   |
| 5.13.4   | 23        | 3.28%   |
| 5.12.10  | 22        | 3.13%   |
| 5.13.6   | 21        | 2.99%   |
| 5.12.7   | 19        | 2.71%   |
| 5.12.15  | 19        | 2.71%   |
| 5.11.15  | 19        | 2.71%   |
| 5.12.6   | 18        | 2.56%   |
| 5.12.12  | 17        | 2.42%   |
| 5.13.10  | 16        | 2.28%   |
| 5.13.5   | 13        | 1.85%   |
| 5.11.21  | 12        | 1.71%   |
| 5.11.3   | 10        | 1.42%   |
| 5.11.19  | 9         | 1.28%   |
| 5.11.10  | 8         | 1.14%   |
| 5.11.14  | 7         | 1%      |
| 5.11.13  | 7         | 1%      |
| 5.12.5   | 6         | 0.85%   |
| 5.12.17  | 5         | 0.71%   |
| 5.10.0   | 5         | 0.71%   |
| 5.13.7   | 4         | 0.57%   |
| 5.11.8   | 4         | 0.57%   |
| 5.13.1   | 3         | 0.43%   |
| 5.11.7   | 3         | 0.43%   |
| 5.14.0   | 2         | 0.28%   |
| 5.11.0   | 2         | 0.28%   |
| 5.9.0    | 1         | 0.14%   |
| 5.8.0    | 1         | 0.14%   |
| 5.4.111  | 1         | 0.14%   |
| 5.13.2   | 1         | 0.14%   |
| 5.13.11  | 1         | 0.14%   |
| 5.13.0   | 1         | 0.14%   |
| 5.12.0   | 1         | 0.14%   |
| 5.11.9   | 1         | 0.14%   |
| 5.11.6   | 1         | 0.14%   |
| 5.11.5   | 1         | 0.14%   |
| 5.11.2   | 1         | 0.14%   |
| 5.10.13  | 1         | 0.14%   |
| 5.1.15   | 1         | 0.14%   |
| 4.14.190 | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 255       | 38.12%  |
| 5.12    | 251       | 37.52%  |
| 5.13    | 150       | 22.42%  |
| 5.10    | 6         | 0.9%    |
| 5.14    | 2         | 0.3%    |
| 5.9     | 1         | 0.15%   |
| 5.8     | 1         | 0.15%   |
| 5.4     | 1         | 0.15%   |
| 5.1     | 1         | 0.15%   |
| 4.14    | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 623       | 99.68%  |
| aarch64 | 2         | 0.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 526       | 83.62%  |
| KDE5          | 30        | 4.77%   |
| KDE           | 17        | 2.7%    |
| Unknown       | 15        | 2.38%   |
| X-Cinnamon    | 11        | 1.75%   |
| XFCE          | 10        | 1.59%   |
| MATE          | 5         | 0.79%   |
| Cinnamon      | 4         | 0.64%   |
| sway          | 2         | 0.32%   |
| i3            | 2         | 0.32%   |
| Deepin        | 2         | 0.32%   |
| Pantheon      | 1         | 0.16%   |
| LXQt          | 1         | 0.16%   |
| LXDE          | 1         | 0.16%   |
| GNOME Classic | 1         | 0.16%   |
| dwm           | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 435       | 68.61%  |
| X11     | 186       | 29.34%  |
| Unknown | 9         | 1.42%   |
| Tty     | 4         | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 349       | 55.31%  |
| GDM     | 238       | 37.72%  |
| SDDM    | 25        | 3.96%   |
| TDM     | 14        | 2.22%   |
| LightDM | 3         | 0.48%   |
| XDM     | 1         | 0.16%   |
| KDM     | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 323       | 51.43%  |
| en_GB   | 56        | 8.92%   |
| pt_BR   | 38        | 6.05%   |
| ru_RU   | 35        | 5.57%   |
| de_DE   | 22        | 3.5%    |
| fr_FR   | 20        | 3.18%   |
| en_IN   | 15        | 2.39%   |
| it_IT   | 13        | 2.07%   |
| es_ES   | 11        | 1.75%   |
| en_CA   | 9         | 1.43%   |
| cs_CZ   | 7         | 1.11%   |
| pt_PT   | 5         | 0.8%    |
| en_DK   | 5         | 0.8%    |
| en_AU   | 5         | 0.8%    |
| tr_TR   | 4         | 0.64%   |
| pl_PL   | 4         | 0.64%   |
| hu_HU   | 4         | 0.64%   |
| es_MX   | 4         | 0.64%   |
| es_CO   | 4         | 0.64%   |
| es_CL   | 4         | 0.64%   |
| de_AT   | 4         | 0.64%   |
| fi_FI   | 3         | 0.48%   |
| ru_UA   | 2         | 0.32%   |
| nl_NL   | 2         | 0.32%   |
| fr_BE   | 2         | 0.32%   |
| es_EC   | 2         | 0.32%   |
| en_IE   | 2         | 0.32%   |
| C       | 2         | 0.32%   |
| zh_TW   | 1         | 0.16%   |
| sv_SE   | 1         | 0.16%   |
| sr_ME   | 1         | 0.16%   |
| ro_RO   | 1         | 0.16%   |
| nl_BE   | 1         | 0.16%   |
| nb_NO   | 1         | 0.16%   |
| ms_MY   | 1         | 0.16%   |
| ko_KR   | 1         | 0.16%   |
| fr_CH   | 1         | 0.16%   |
| fr_CA   | 1         | 0.16%   |
| es_NI   | 1         | 0.16%   |
| es_DO   | 1         | 0.16%   |
| es_AR   | 1         | 0.16%   |
| en_SG   | 1         | 0.16%   |
| en_PH   | 1         | 0.16%   |
| en_NZ   | 1         | 0.16%   |
| el_GR   | 1         | 0.16%   |
| de_CH   | 1         | 0.16%   |
| da_DK   | 1         | 0.16%   |
| ca_ES   | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 499       | 79.46%  |
| BIOS | 129       | 20.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 459       | 73.21%  |
| Ext4                | 148       | 23.6%   |
| Xfs                 | 17        | 2.71%   |
| Overlay             | 1         | 0.16%   |
| Fuse.fuse-overlayfs | 1         | 0.16%   |
| Unknown             | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 346       | 54.83%  |
| GPT     | 243       | 38.51%  |
| MBR     | 42        | 6.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 581       | 92.52%  |
| Yes       | 47        | 7.48%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 525       | 83.6%   |
| Yes       | 103       | 16.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 182       | 29.12%  |
| Dell                             | 112       | 17.92%  |
| Hewlett-Packard                  | 91        | 14.56%  |
| ASUSTek Computer                 | 68        | 10.88%  |
| Acer                             | 45        | 7.2%    |
| Apple                            | 16        | 2.56%   |
| HUAWEI                           | 9         | 1.44%   |
| Toshiba                          | 7         | 1.12%   |
| Timi                             | 7         | 1.12%   |
| Samsung Electronics              | 7         | 1.12%   |
| Notebook                         | 7         | 1.12%   |
| MSI                              | 7         | 1.12%   |
| Sony                             | 6         | 0.96%   |
| Fujitsu                          | 6         | 0.96%   |
| Unknown                          | 6         | 0.96%   |
| Positivo                         | 5         | 0.8%    |
| TUXEDO                           | 2         | 0.32%   |
| TrekStor                         | 2         | 0.32%   |
| System76                         | 2         | 0.32%   |
| SLIMBOOK                         | 2         | 0.32%   |
| LG Electronics                   | 2         | 0.32%   |
| eMachines                        | 2         | 0.32%   |
| Chuwi                            | 2         | 0.32%   |
| Alienware                        | 2         | 0.32%   |
| Wortmann AG                      | 1         | 0.16%   |
| Teclast                          | 1         | 0.16%   |
| Standard                         | 1         | 0.16%   |
| Shenzhen PLOYER electronics      | 1         | 0.16%   |
| Razer                            | 1         | 0.16%   |
| Purism                           | 1         | 0.16%   |
| Prestigio                        | 1         | 0.16%   |
| Pine Microsystems                | 1         | 0.16%   |
| PC Specialist                    | 1         | 0.16%   |
| ordissimo                        | 1         | 0.16%   |
| NEC Computers                    | 1         | 0.16%   |
| MPMAN                            | 1         | 0.16%   |
| Medion                           | 1         | 0.16%   |
| Maibenben                        | 1         | 0.16%   |
| Login Informatica                | 1         | 0.16%   |
| Linx                             | 1         | 0.16%   |
| Intel Client Systems             | 1         | 0.16%   |
| Insyde                           | 1         | 0.16%   |
| HONOR                            | 1         | 0.16%   |
| HASEE Computer                   | 1         | 0.16%   |
| Hampoo                           | 1         | 0.16%   |
| Gigabyte Technology              | 1         | 0.16%   |
| FUJITSU CLIENT COMPUTING LIMITED | 1         | 0.16%   |
| Framework                        | 1         | 0.16%   |
| Connect                          | 1         | 0.16%   |
| AZW                              | 1         | 0.16%   |
| AMI                              | 1         | 0.16%   |
| A-DATA Technology                | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 8         | 1.28%   |
| Dell XPS 15 9500                           | 5         | 0.8%    |
| HP Pavilion dv7                            | 4         | 0.64%   |
| HP Notebook                                | 4         | 0.64%   |
| Dell XPS 15 7590                           | 4         | 0.64%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 4         | 0.64%   |
| Apple MacBookPro11,5                       | 4         | 0.64%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 3         | 0.48%   |
| HP Pavilion 15                             | 3         | 0.48%   |
| HP Laptop 15s-eq2xxx                       | 3         | 0.48%   |
| HP Laptop 15-da0xxx                        | 3         | 0.48%   |
| HP EliteBook 840 G6                        | 3         | 0.48%   |
| Dell XPS 15 9550                           | 3         | 0.48%   |
| Dell XPS 13 9310                           | 3         | 0.48%   |
| Dell XPS 13 7390                           | 3         | 0.48%   |
| Dell Latitude 7490                         | 3         | 0.48%   |
| Dell Latitude 7400                         | 3         | 0.48%   |
| Dell Latitude 5480                         | 3         | 0.48%   |
| ASUS ZenBook UX431DA_UM431DA               | 3         | 0.48%   |
| Apple MacBookPro11,3                       | 3         | 0.48%   |
| Acer Aspire E5-573G                        | 3         | 0.48%   |
| Timi A35S                                  | 2         | 0.32%   |
| System76 Oryx Pro                          | 2         | 0.32%   |
| SLIMBOOK PROX15-AMD                        | 2         | 0.32%   |
| Positivo CHT14B                            | 2         | 0.32%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 2         | 0.32%   |
| Lenovo Yoga 2 Pro 20266                    | 2         | 0.32%   |
| Lenovo ThinkPad T14 Gen 1 20UDCTO1WW       | 2         | 0.32%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW      | 2         | 0.32%   |
| Lenovo ThinkPad E595 20NFCTO1WW            | 2         | 0.32%   |
| Lenovo Legion 5 15ARH05H 82B1              | 2         | 0.32%   |
| Lenovo IdeaPad Yoga 13 20175               | 2         | 0.32%   |
| Lenovo IdeaPad S145-15IWL 81S9             | 2         | 0.32%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 2         | 0.32%   |
| Lenovo IdeaPad 5 15ALC05 82LN              | 2         | 0.32%   |
| Lenovo IdeaPad 330S-15IKB 81F5             | 2         | 0.32%   |
| HP ProBook 450 G5                          | 2         | 0.32%   |
| HP Pro x2 612 G1 Tablet                    | 2         | 0.32%   |
| HP Pavilion dv6                            | 2         | 0.32%   |
| HP Pavilion 11 x360 PC                     | 2         | 0.32%   |
| HP Laptop 17-bs1xx                         | 2         | 0.32%   |
| eMachines eME732                           | 2         | 0.32%   |
| Dell XPS L502X                             | 2         | 0.32%   |
| Dell Precision M4600                       | 2         | 0.32%   |
| Dell Latitude E6510                        | 2         | 0.32%   |
| Dell Latitude E6320                        | 2         | 0.32%   |
| Dell Latitude 7410                         | 2         | 0.32%   |
| Dell Inspiron 7572                         | 2         | 0.32%   |
| Dell Inspiron 3442                         | 2         | 0.32%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.32%   |
| Dell G7 7588                               | 2         | 0.32%   |
| Dell G5 5505                               | 2         | 0.32%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA     | 2         | 0.32%   |
| ASUS UX303UA                               | 2         | 0.32%   |
| ASUS N550JV                                | 2         | 0.32%   |
| ASUS ASUS TUF Gaming A17 FA706IU_FA706IU   | 2         | 0.32%   |
| Apple MacBookPro7,1                        | 2         | 0.32%   |
| Apple MacBookPro11,1                       | 2         | 0.32%   |
| Acer Nitro AN515-54                        | 2         | 0.32%   |
| Acer Aspire E5-576                         | 2         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Lenovo ThinkPad                    | 112       | 17.92%  |
| Lenovo IdeaPad                     | 36        | 5.76%   |
| Dell Inspiron                      | 34        | 5.44%   |
| Acer Aspire                        | 30        | 4.8%    |
| Dell XPS                           | 29        | 4.64%   |
| Dell Latitude                      | 29        | 4.64%   |
| HP Pavilion                        | 21        | 3.36%   |
| HP EliteBook                       | 16        | 2.56%   |
| HP ProBook                         | 15        | 2.4%    |
| HP Laptop                          | 15        | 2.4%    |
| ASUS VivoBook                      | 13        | 2.08%   |
| ASUS ROG                           | 12        | 1.92%   |
| Lenovo Yoga                        | 11        | 1.76%   |
| Apple MacBookPro11                 | 10        | 1.6%    |
| Dell Precision                     | 8         | 1.28%   |
| Unknown                            | 8         | 1.28%   |
| Lenovo ThinkBook                   | 7         | 1.12%   |
| Acer Nitro                         | 7         | 1.12%   |
| Fujitsu LIFEBOOK                   | 6         | 0.96%   |
| ASUS ZenBook                       | 6         | 0.96%   |
| ASUS TUF                           | 6         | 0.96%   |
| ASUS ASUS                          | 6         | 0.96%   |
| Acer Swift                         | 6         | 0.96%   |
| Toshiba Satellite                  | 5         | 0.8%    |
| Lenovo Legion                      | 5         | 0.8%    |
| HP ZBook                           | 5         | 0.8%    |
| Dell Vostro                        | 5         | 0.8%    |
| HP Notebook                        | 4         | 0.64%   |
| Dell G5                            | 3         | 0.48%   |
| Toshiba TECRA                      | 2         | 0.32%   |
| Timi RedmiBook                     | 2         | 0.32%   |
| Timi A35S                          | 2         | 0.32%   |
| System76 Oryx                      | 2         | 0.32%   |
| SLIMBOOK PROX15-AMD                | 2         | 0.32%   |
| Positivo CHT14B                    | 2         | 0.32%   |
| HP Pro                             | 2         | 0.32%   |
| HP OMEN                            | 2         | 0.32%   |
| HP ENVY                            | 2         | 0.32%   |
| eMachines eME732                   | 2         | 0.32%   |
| Dell G7                            | 2         | 0.32%   |
| ASUS UX303UA                       | 2         | 0.32%   |
| ASUS N550JV                        | 2         | 0.32%   |
| Apple MacBookPro7                  | 2         | 0.32%   |
| Wortmann AG 1220692                | 1         | 0.16%   |
| TUXEDO Pulse                       | 1         | 0.16%   |
| TUXEDO InfinityBook                | 1         | 0.16%   |
| TrekStor SurfTab                   | 1         | 0.16%   |
| TrekStor Notebook                  | 1         | 0.16%   |
| Timi TM1707                        | 1         | 0.16%   |
| Timi TM1701                        | 1         | 0.16%   |
| Timi TM1604                        | 1         | 0.16%   |
| Teclast TbooK                      | 1         | 0.16%   |
| Sony VPCSC41FM                     | 1         | 0.16%   |
| Sony VPCS12C5E                     | 1         | 0.16%   |
| Sony VPCEH36EG                     | 1         | 0.16%   |
| Sony VPCEH16EN                     | 1         | 0.16%   |
| Sony VPCEB3PGX                     | 1         | 0.16%   |
| Sony SVS1511X9RB                   | 1         | 0.16%   |
| Shenzhen PLOYER electronics MOMO7W | 1         | 0.16%   |
| Samsung R580                       | 1         | 0.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 168       | 26.88%  |
| 2021    | 141       | 22.56%  |
| 2019    | 84        | 13.44%  |
| 2018    | 44        | 7.04%   |
| 2015    | 29        | 4.64%   |
| 2012    | 26        | 4.16%   |
| 2017    | 25        | 4%      |
| 2016    | 24        | 3.84%   |
| 2014    | 22        | 3.52%   |
| 2013    | 21        | 3.36%   |
| 2011    | 21        | 3.36%   |
| 2010    | 12        | 1.92%   |
| 2009    | 5         | 0.8%    |
| 2008    | 2         | 0.32%   |
| Unknown | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 625       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 522       | 82.33%  |
| Enabled  | 112       | 17.67%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 622       | 99.52%  |
| Yes  | 3         | 0.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 192       | 30.52%  |
| 16.01-24.0  | 149       | 23.69%  |
| 8.01-16.0   | 118       | 18.76%  |
| 32.01-64.0  | 72        | 11.45%  |
| 3.01-4.0    | 55        | 8.74%   |
| 1.01-2.0    | 14        | 2.23%   |
| 24.01-32.0  | 12        | 1.91%   |
| 64.01-256.0 | 11        | 1.75%   |
| 0.51-1.0    | 5         | 0.79%   |
| 2.01-3.0    | 1         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 186       | 27.97%  |
| 4.01-8.0   | 165       | 24.81%  |
| 3.01-4.0   | 138       | 20.75%  |
| 1.01-2.0   | 107       | 16.09%  |
| 8.01-16.0  | 49        | 7.37%   |
| 0.51-1.0   | 16        | 2.41%   |
| 16.01-24.0 | 4         | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 452       | 71.97%  |
| 2      | 155       | 24.68%  |
| 3      | 15        | 2.39%   |
| 0      | 3         | 0.48%   |
| 5      | 2         | 0.32%   |
| 4      | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 506       | 80.7%   |
| Yes       | 121       | 19.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 447       | 71.18%  |
| No        | 181       | 28.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 601       | 96.01%  |
| No        | 25        | 3.99%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 523       | 83.15%  |
| No        | 106       | 16.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 96        | 15.29%  |
| Brazil       | 53        | 8.44%   |
| Germany      | 43        | 6.85%   |
| Russia       | 37        | 5.89%   |
| India        | 33        | 5.25%   |
| Netherlands  | 26        | 4.14%   |
| France       | 26        | 4.14%   |
| Italy        | 20        | 3.18%   |
| UK           | 18        | 2.87%   |
| Spain        | 16        | 2.55%   |
| Canada       | 16        | 2.55%   |
| Czechia      | 15        | 2.39%   |
| Poland       | 12        | 1.91%   |
| Ukraine      | 11        | 1.75%   |
| Turkey       | 11        | 1.75%   |
| Switzerland  | 9         | 1.43%   |
| Portugal     | 9         | 1.43%   |
| Finland      | 8         | 1.27%   |
| Belgium      | 8         | 1.27%   |
| Argentina    | 8         | 1.27%   |
| Sweden       | 7         | 1.11%   |
| Slovakia     | 7         | 1.11%   |
| Colombia     | 7         | 1.11%   |
| Romania      | 6         | 0.96%   |
| Denmark      | 6         | 0.96%   |
| Austria      | 6         | 0.96%   |
| Mexico       | 5         | 0.8%    |
| Hungary      | 5         | 0.8%    |
| Chile        | 5         | 0.8%    |
| Belarus      | 5         | 0.8%    |
| Norway       | 4         | 0.64%   |
| Iran         | 4         | 0.64%   |
| Indonesia    | 4         | 0.64%   |
| Greece       | 4         | 0.64%   |
| Australia    | 4         | 0.64%   |
| South Africa | 3         | 0.48%   |
| Slovenia     | 3         | 0.48%   |
| Serbia       | 3         | 0.48%   |
| Moldova      | 3         | 0.48%   |
| Estonia      | 3         | 0.48%   |
| China        | 3         | 0.48%   |
| Bulgaria     | 3         | 0.48%   |
| Vietnam      | 2         | 0.32%   |
| Taiwan       | 2         | 0.32%   |
| Sri Lanka    | 2         | 0.32%   |
| South Korea  | 2         | 0.32%   |
| Singapore    | 2         | 0.32%   |
| Philippines  | 2         | 0.32%   |
| Montenegro   | 2         | 0.32%   |
| Malaysia     | 2         | 0.32%   |
| Lithuania    | 2         | 0.32%   |
| Latvia       | 2         | 0.32%   |
| Kyrgyzstan   | 2         | 0.32%   |
| Israel       | 2         | 0.32%   |
| Ireland      | 2         | 0.32%   |
| Egypt        | 2         | 0.32%   |
| Ecuador      | 2         | 0.32%   |
| Uzbekistan   | 1         | 0.16%   |
| Uruguay      | 1         | 0.16%   |
| Tonga        | 1         | 0.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Moscow         | 14        | 2.17%   |
| Berlin         | 9         | 1.4%    |
| Prague         | 8         | 1.24%   |
| Kyiv           | 7         | 1.09%   |
| The Hague      | 6         | 0.93%   |
| Madrid         | 5         | 0.78%   |
| Budapest       | 5         | 0.78%   |
| Bengaluru      | 5         | 0.78%   |
| Amsterdam      | 5         | 0.78%   |
| São Paulo     | 4         | 0.62%   |
| Milan          | 4         | 0.62%   |
| Istanbul       | 4         | 0.62%   |
| Fortaleza      | 4         | 0.62%   |
| Buenos Aires   | 4         | 0.62%   |
| Tehran         | 3         | 0.47%   |
| Pune           | 3         | 0.47%   |
| Minsk          | 3         | 0.47%   |
| London         | 3         | 0.47%   |
| Helsinki       | 3         | 0.47%   |
| Feeding Hills  | 3         | 0.47%   |
| Chisinau       | 3         | 0.47%   |
| Brussels       | 3         | 0.47%   |
| Bratislava     | 3         | 0.47%   |
| Athens         | 3         | 0.47%   |
| Zurich         | 2         | 0.31%   |
| Yekaterinburg  | 2         | 0.31%   |
| Wroclaw        | 2         | 0.31%   |
| Winnipeg       | 2         | 0.31%   |
| Vienna         | 2         | 0.31%   |
| Uberlândia    | 2         | 0.31%   |
| Tyumen         | 2         | 0.31%   |
| Turin          | 2         | 0.31%   |
| Toronto        | 2         | 0.31%   |
| Tel Aviv       | 2         | 0.31%   |
| Tallinn        | 2         | 0.31%   |
| Sydney         | 2         | 0.31%   |
| Stuttgart      | 2         | 0.31%   |
| St Petersburg  | 2         | 0.31%   |
| Spalding       | 2         | 0.31%   |
| Sofia          | 2         | 0.31%   |
| Singapore      | 2         | 0.31%   |
| Sharon         | 2         | 0.31%   |
| Seattle        | 2         | 0.31%   |
| Santiago       | 2         | 0.31%   |
| Rio de Janeiro | 2         | 0.31%   |
| Riga           | 2         | 0.31%   |
| Raleigh        | 2         | 0.31%   |
| Quito          | 2         | 0.31%   |
| Porto Alegre   | 2         | 0.31%   |
| Podgorica      | 2         | 0.31%   |
| Paris          | 2         | 0.31%   |
| Oslo           | 2         | 0.31%   |
| Nuremberg      | 2         | 0.31%   |
| Newtownabbey   | 2         | 0.31%   |
| New Delhi      | 2         | 0.31%   |
| Mumbai         | 2         | 0.31%   |
| Montreal       | 2         | 0.31%   |
| Lyon           | 2         | 0.31%   |
| Lens           | 2         | 0.31%   |
| Las Vegas      | 2         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 177       | 239    | 22.61%  |
| WDC                       | 90        | 112    | 11.49%  |
| Toshiba                   | 59        | 63     | 7.54%   |
| Seagate                   | 55        | 65     | 7.02%   |
| SanDisk                   | 48        | 55     | 6.13%   |
| Unknown                   | 47        | 61     | 6%      |
| SK Hynix                  | 44        | 52     | 5.62%   |
| Kingston                  | 35        | 40     | 4.47%   |
| Intel                     | 35        | 48     | 4.47%   |
| Crucial                   | 21        | 25     | 2.68%   |
| Micron Technology         | 18        | 25     | 2.3%    |
| HGST                      | 14        | 17     | 1.79%   |
| A-DATA Technology         | 14        | 15     | 1.79%   |
| KIOXIA                    | 11        | 13     | 1.4%    |
| Apple                     | 11        | 13     | 1.4%    |
| Silicon Motion            | 7         | 12     | 0.89%   |
| SPCC                      | 6         | 7      | 0.77%   |
| Hitachi                   | 6         | 8      | 0.77%   |
| XPG                       | 5         | 6      | 0.64%   |
| Transcend                 | 5         | 5      | 0.64%   |
| LITEON                    | 5         | 5      | 0.64%   |
| Union Memory              | 4         | 4      | 0.51%   |
| Realtek Semiconductor     | 4         | 5      | 0.51%   |
| Phison                    | 4         | 5      | 0.51%   |
| LITEONIT                  | 4         | 4      | 0.51%   |
| Corsair                   | 4         | 5      | 0.51%   |
| Solid State Storage       | 3         | 3      | 0.38%   |
| Patriot                   | 3         | 4      | 0.38%   |
| KingFast                  | 3         | 4      | 0.38%   |
| Intenso                   | 3         | 3      | 0.38%   |
| PNY                       | 2         | 2      | 0.26%   |
| Micron/Crucial Technology | 2         | 2      | 0.26%   |
| Lite-On                   | 2         | 2      | 0.26%   |
| Lenovo                    | 2         | 2      | 0.26%   |
| JMicron                   | 2         | 2      | 0.26%   |
| BIWIN                     | 2         | 2      | 0.26%   |
| XrayDisk                  | 1         | 1      | 0.13%   |
| W800S                     | 1         | 1      | 0.13%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.13%   |
| UNIC2                     | 1         | 1      | 0.13%   |
| Team                      | 1         | 1      | 0.13%   |
| TCSUNBOW                  | 1         | 1      | 0.13%   |
| Tanbassh                  | 1         | 1      | 0.13%   |
| Reeinno                   | 1         | 1      | 0.13%   |
| OCZ-ARC1                  | 1         | 1      | 0.13%   |
| OCZ                       | 1         | 1      | 0.13%   |
| NGFF                      | 1         | 1      | 0.13%   |
| Mushkin                   | 1         | 2      | 0.13%   |
| MTFDDAK1                  | 1         | 1      | 0.13%   |
| Maxtor                    | 1         | 1      | 0.13%   |
| Lexar                     | 1         | 1      | 0.13%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.13%   |
| HS-SSD-C100               | 1         | 1      | 0.13%   |
| Hewlett-Packard           | 1         | 1      | 0.13%   |
| GOODRAM                   | 1         | 1      | 0.13%   |
| Gigabyte Technology       | 1         | 1      | 0.13%   |
| GALAX                     | 1         | 1      | 0.13%   |
| Fujitsu                   | 1         | 1      | 0.13%   |
| EMTEC                     | 1         | 1      | 0.13%   |
| DOGFISH                   | 1         | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB            | 24        | 2.87%   |
| Samsung SSD 860 EVO 500GB               | 15        | 1.79%   |
| Samsung NVMe SSD Drive 256GB            | 13        | 1.55%   |
| Seagate ST1000LM035-1RK172 1TB          | 12        | 1.43%   |
| Sandisk NVMe SSD Drive 512GB            | 11        | 1.31%   |
| Samsung NVMe SSD Drive 1TB              | 10        | 1.19%   |
| SK Hynix NVMe SSD Drive 512GB           | 8         | 0.96%   |
| Unknown MMC Card  32GB                  | 7         | 0.84%   |
| Samsung NVMe SSD Drive 500GB            | 7         | 0.84%   |
| Intel NVMe SSD Drive 512GB              | 7         | 0.84%   |
| Unknown SD/MMC/MS PRO 64GB              | 6         | 0.72%   |
| Toshiba MQ04ABF100 1TB                  | 6         | 0.72%   |
| Toshiba MQ01ABD100 1TB                  | 6         | 0.72%   |
| Seagate ST1000LM049-2GH172 1TB          | 6         | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 6         | 0.72%   |
| Sandisk NVMe SSD Drive 256GB            | 6         | 0.72%   |
| Samsung SSD 970 EVO Plus 1TB            | 6         | 0.72%   |
| Samsung NVMe SSD Drive 1024GB           | 6         | 0.72%   |
| Kingston SA400S37480G 480GB SSD         | 6         | 0.72%   |
| Kingston SA400S37240G 240GB SSD         | 6         | 0.72%   |
| Toshiba NVMe SSD Drive 512GB            | 5         | 0.6%    |
| Sandisk NVMe SSD Drive 1024GB           | 5         | 0.6%    |
| Samsung SSD 850 EVO 500GB               | 5         | 0.6%    |
| Samsung MZVLB512HBJQ-000L7 512GB        | 5         | 0.6%    |
| KIOXIA KBG40ZNV512G 512GB               | 5         | 0.6%    |
| HGST HTS721010A9E630 1TB                | 5         | 0.6%    |
| HGST HTS541010A9E680 1TB                | 5         | 0.6%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 4         | 0.48%   |
| WDC WD10SPZX-21Z10T0 1TB                | 4         | 0.48%   |
| Unknown NCard  16GB                     | 4         | 0.48%   |
| Seagate Expansion 1TB                   | 4         | 0.48%   |
| Samsung SSD 970 EVO Plus 2TB            | 4         | 0.48%   |
| Samsung SSD 860 EVO 250GB               | 4         | 0.48%   |
| Samsung MZALQ512HALU-000L2 512GB        | 4         | 0.48%   |
| Kingston SA400S37120G 120GB SSD         | 4         | 0.48%   |
| Crucial CT500MX500SSD1 500GB            | 4         | 0.48%   |
| Crucial CT1000MX500SSD1 1TB             | 4         | 0.48%   |
| XPG NVMe SSD Drive 256GB                | 3         | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 3         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 3         | 0.36%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 3         | 0.36%   |
| WDC WD10SPZX-24Z10 1TB                  | 3         | 0.36%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 3         | 0.36%   |
| Toshiba NVMe SSD Drive 256GB            | 3         | 0.36%   |
| Toshiba MQ01ABF050 500GB                | 3         | 0.36%   |
| Toshiba KXG60ZNV1T02 NVMe KIOXIA 1024GB | 3         | 0.36%   |
| SK Hynix SC311 SATA 512GB SSD           | 3         | 0.36%   |
| SK Hynix NVMe SSD Drive 256GB           | 3         | 0.36%   |
| SK Hynix HBG4e  32GB                    | 3         | 0.36%   |
| Seagate ST500LM021-1KJ152 500GB         | 3         | 0.36%   |
| Seagate ST2000LM007-1R8174 2TB          | 3         | 0.36%   |
| SanDisk SDSSDA240G 240GB                | 3         | 0.36%   |
| Samsung SSD 980 PRO 1TB                 | 3         | 0.36%   |
| Samsung SSD 970 EVO 1TB                 | 3         | 0.36%   |
| Samsung SSD 870 EVO 500GB               | 3         | 0.36%   |
| Samsung SSD 860 EVO 1TB                 | 3         | 0.36%   |
| Samsung SSD 850 PRO 512GB               | 3         | 0.36%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.36%   |
| Samsung NVMe SSD Drive 2TB              | 3         | 0.36%   |
| Samsung MZVLB1T0HBLR-000L7 1TB          | 3         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 52        | 61     | 34.67%  |
| WDC     | 48        | 64     | 32%     |
| Toshiba | 28        | 31     | 18.67%  |
| HGST    | 14        | 17     | 9.33%   |
| Hitachi | 6         | 8      | 4%      |
| Unknown | 1         | 1      | 0.67%   |
| Fujitsu | 1         | 1      | 0.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 74        | 90     | 27.72%  |
| Kingston            | 26        | 30     | 9.74%   |
| SanDisk             | 24        | 31     | 8.99%   |
| WDC                 | 20        | 22     | 7.49%   |
| Crucial             | 18        | 22     | 6.74%   |
| Intel               | 13        | 16     | 4.87%   |
| A-DATA Technology   | 10        | 10     | 3.75%   |
| Apple               | 9         | 10     | 3.37%   |
| Toshiba             | 8         | 8      | 3%      |
| SPCC                | 6         | 7      | 2.25%   |
| SK Hynix            | 6         | 7      | 2.25%   |
| Micron Technology   | 6         | 6      | 2.25%   |
| Transcend           | 5         | 5      | 1.87%   |
| LITEON              | 5         | 5      | 1.87%   |
| LITEONIT            | 4         | 4      | 1.5%    |
| Unknown             | 3         | 3      | 1.12%   |
| Intenso             | 3         | 3      | 1.12%   |
| Corsair             | 3         | 3      | 1.12%   |
| PNY                 | 2         | 2      | 0.75%   |
| Patriot             | 2         | 2      | 0.75%   |
| W800S               | 1         | 1      | 0.37%   |
| Union Memory        | 1         | 1      | 0.37%   |
| UNIC2               | 1         | 1      | 0.37%   |
| Team                | 1         | 1      | 0.37%   |
| TCSUNBOW            | 1         | 1      | 0.37%   |
| OCZ-ARC1            | 1         | 1      | 0.37%   |
| OCZ                 | 1         | 1      | 0.37%   |
| NGFF                | 1         | 1      | 0.37%   |
| Mushkin             | 1         | 2      | 0.37%   |
| Maxtor              | 1         | 1      | 0.37%   |
| Lexar               | 1         | 1      | 0.37%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.37%   |
| JMicron             | 1         | 1      | 0.37%   |
| GOODRAM             | 1         | 1      | 0.37%   |
| GALAX               | 1         | 1      | 0.37%   |
| EMTEC               | 1         | 1      | 0.37%   |
| DOGFISH             | 1         | 1      | 0.37%   |
| China               | 1         | 2      | 0.37%   |
| BIWIN               | 1         | 1      | 0.37%   |
| Apacer              | 1         | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 304       | 402    | 40.05%  |
| SSD     | 254       | 308    | 33.47%  |
| HDD     | 145       | 183    | 19.1%   |
| MMC     | 40        | 53     | 5.27%   |
| Unknown | 16        | 17     | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 352       | 482    | 49.16%  |
| NVMe | 304       | 402    | 42.46%  |
| MMC  | 40        | 53     | 5.59%   |
| SAS  | 20        | 26     | 2.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 240       | 298    | 62.18%  |
| 0.51-1.0   | 127       | 167    | 32.9%   |
| 1.01-2.0   | 17        | 24     | 4.4%    |
| 4.01-10.0  | 1         | 1      | 0.26%   |
| 0          | 1         | 1      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 148       | 23.31%  |
| 251-500        | 129       | 20.31%  |
| 101-250        | 82        | 12.91%  |
| 1-20           | 82        | 12.91%  |
| Unknown        | 69        | 10.87%  |
| 1001-2000      | 65        | 10.24%  |
| 51-100         | 31        | 4.88%   |
| 21-50          | 16        | 2.52%   |
| More than 3000 | 8         | 1.26%   |
| 2001-3000      | 5         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 209       | 32.15%  |
| 21-50     | 102       | 15.69%  |
| 101-250   | 97        | 14.92%  |
| Unknown   | 69        | 10.62%  |
| 51-100    | 68        | 10.46%  |
| 251-500   | 64        | 9.85%   |
| 501-1000  | 35        | 5.38%   |
| 1001-2000 | 6         | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 2         | 2      | 9.09%   |
| WDC WD3200BPVT-75ZEST0 320GB            | 1         | 1      | 4.55%   |
| WDC WD3200BPVT-24JJ5T0 320GB            | 1         | 1      | 4.55%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1      | 4.55%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 1      | 4.55%   |
| Union Memory UMIS RPJTJ128MED1MWX 128GB | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 4.55%   |
| SPCC Solid State Disk 256GB             | 1         | 1      | 4.55%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD   | 1         | 1      | 4.55%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1      | 4.55%   |
| Seagate ST1000LM049-2GH172 1TB          | 1         | 2      | 4.55%   |
| Samsung Electronics SSD 860 EVO 250GB   | 1         | 1      | 4.55%   |
| LITEON LGH-512V2G-11 M.2 2280 512GB SSD | 1         | 1      | 4.55%   |
| Intel SSDSC2KF480H6L 480GB              | 1         | 1      | 4.55%   |
| Intel SSDSA2M080G2GC 80GB               | 1         | 1      | 4.55%   |
| Hitachi HTS545032A7E380 320GB           | 1         | 1      | 4.55%   |
| HGST HTS725050A7E630 500GB              | 1         | 1      | 4.55%   |
| Fujitsu MHY2120BH 120GB                 | 1         | 1      | 4.55%   |
| Crucial CT1050MX300SSD1 1TB             | 1         | 2      | 4.55%   |
| Crucial CT1000P1SSD8 1TB                | 1         | 1      | 4.55%   |
| A-DATA Technology SX6000NP 128GB        | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 18.18%  |
| Seagate             | 4         | 5      | 18.18%  |
| Intel               | 2         | 2      | 9.09%   |
| Crucial             | 2         | 3      | 9.09%   |
| Union Memory        | 1         | 1      | 4.55%   |
| Toshiba             | 1         | 1      | 4.55%   |
| SPCC                | 1         | 1      | 4.55%   |
| SK Hynix            | 1         | 1      | 4.55%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| LITEON              | 1         | 1      | 4.55%   |
| Hitachi             | 1         | 1      | 4.55%   |
| HGST                | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |
| A-DATA Technology   | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 33.33%  |
| Seagate | 4         | 5      | 33.33%  |
| Toshiba | 1         | 1      | 8.33%   |
| Hitachi | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 13     | 54.55%  |
| SSD  | 7         | 8      | 31.82%  |
| NVMe | 3         | 3      | 13.64%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 383       | 565    | 56.66%  |
| Works    | 271       | 373    | 40.09%  |
| Malfunc  | 21        | 24     | 3.11%   |
| Failed   | 1         | 1      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 382       | 50.2%   |
| Samsung Electronics            | 117       | 15.37%  |
| AMD                            | 77        | 10.12%  |
| Sandisk                        | 47        | 6.18%   |
| SK Hynix                       | 34        | 4.47%   |
| Toshiba America Info Systems   | 22        | 2.89%   |
| Micron Technology              | 13        | 1.71%   |
| KIOXIA                         | 11        | 1.45%   |
| Kingston Technology Company    | 9         | 1.18%   |
| Silicon Motion                 | 8         | 1.05%   |
| ADATA Technology               | 7         | 0.92%   |
| Phison Electronics             | 6         | 0.79%   |
| Union Memory (Shenzhen)        | 4         | 0.53%   |
| Realtek Semiconductor          | 4         | 0.53%   |
| Micron/Crucial Technology      | 4         | 0.53%   |
| Solid State Storage Technology | 3         | 0.39%   |
| Seagate Technology             | 3         | 0.39%   |
| Nvidia                         | 3         | 0.39%   |
| Lite-On Technology             | 2         | 0.26%   |
| Lenovo                         | 2         | 0.26%   |
| Apple                          | 2         | 0.26%   |
| Shenzhen Longsys Electronics   | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 76        | 9.61%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 72        | 9.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 71        | 8.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 40        | 5.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 30        | 3.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 28        | 3.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 28        | 3.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 24        | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 19        | 2.4%    |
| Samsung NVMe Controller                                                          | 18        | 2.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 18        | 2.28%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 15        | 1.9%    |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 1.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 14        | 1.77%   |
| Micron Non-Volatile memory controller                                            | 13        | 1.64%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 1.64%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 12        | 1.52%   |
| KIOXIA Non-Volatile memory controller                                            | 11        | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 11        | 1.39%   |
| SK Hynix Non-Volatile memory controller                                          | 10        | 1.26%   |
| SK Hynix BC511                                                                   | 9         | 1.14%   |
| Sandisk Non-Volatile memory controller                                           | 9         | 1.14%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 8         | 1.01%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 8         | 1.01%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 8         | 1.01%   |
| Intel SSD 660P Series                                                            | 8         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 1.01%   |
| SK Hynix NVMe SSD Controller                                                     | 7         | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 7         | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7         | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7         | 0.88%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 7         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 7         | 0.88%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 6         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.76%   |
| Samsung Apple PCIe SSD                                                           | 5         | 0.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 0.63%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 5         | 0.63%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 4         | 0.51%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 0.51%   |
| Sandisk PC SN520 NVMe SSD                                                        | 4         | 0.51%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 4         | 0.51%   |
| Samsung Electronics SATA controller                                              | 4         | 0.51%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 4         | 0.51%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 3         | 0.38%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 3         | 0.38%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.38%   |
| Solid State Storage Non-Volatile memory controller                               | 3         | 0.38%   |
| Seagate FireCuda 510 SSD                                                         | 3         | 0.38%   |
| Realtek Realtek Non-Volatile memory controller                                   | 3         | 0.38%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.38%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 3         | 0.38%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.38%   |
| Kingston Company A2000 NVMe SSD                                                  | 3         | 0.38%   |
| Intel SSD 600P Series                                                            | 3         | 0.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 405       | 52.53%  |
| NVMe | 301       | 39.04%  |
| RAID | 54        | 7%      |
| IDE  | 11        | 1.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 498       | 79.68%  |
| AMD      | 125       | 20%     |
| QUALCOMM | 1         | 0.16%   |
| ARM      | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 20        | 3.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 16        | 2.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 2.4%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 2.24%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 2.24%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 2.08%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 1.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 11        | 1.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 11        | 1.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 11        | 1.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 1.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 1.6%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 1.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 1.44%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 9         | 1.44%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 8         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 1.28%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 1.28%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 1.28%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.12%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 7         | 1.12%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 7         | 1.12%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 6         | 0.96%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.96%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 6         | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 0.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 0.96%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 0.96%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.8%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.8%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 5         | 0.8%    |
| Intel Atom CPU Z3735G @ 1.33GHz               | 5         | 0.8%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 0.8%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.8%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 4         | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.64%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 0.64%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.64%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 4         | 0.64%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 4         | 0.64%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 0.64%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 4         | 0.64%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.64%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 3         | 0.48%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 3         | 0.48%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.48%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 3         | 0.48%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 3         | 0.48%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 3         | 0.48%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.48%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.48%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 0.48%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 3         | 0.48%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 3         | 0.48%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 3         | 0.48%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 199       | 31.84%  |
| Intel Core i5           | 157       | 25.12%  |
| Other                   | 41        | 6.56%   |
| Intel Core i3           | 41        | 6.56%   |
| AMD Ryzen 5             | 39        | 6.24%   |
| AMD Ryzen 7             | 31        | 4.96%   |
| Intel Atom              | 19        | 3.04%   |
| AMD Ryzen 7 PRO         | 10        | 1.6%    |
| Intel Pentium           | 9         | 1.44%   |
| Intel Core i9           | 9         | 1.44%   |
| AMD Ryzen 9             | 9         | 1.44%   |
| Intel Core 2 Duo        | 8         | 1.28%   |
| Intel Celeron           | 8         | 1.28%   |
| AMD Ryzen 3             | 7         | 1.12%   |
| AMD Ryzen 5 PRO         | 5         | 0.8%    |
| AMD A6                  | 4         | 0.64%   |
| AMD A4                  | 4         | 0.64%   |
| AMD A10                 | 4         | 0.64%   |
| Intel Pentium Silver    | 3         | 0.48%   |
| Intel Core m7           | 2         | 0.32%   |
| AMD A8                  | 2         | 0.32%   |
| QUALCOMM AArch64        | 1         | 0.16%   |
| Intel Xeon              | 1         | 0.16%   |
| Intel Pentium Dual      | 1         | 0.16%   |
| Intel Core m3           | 1         | 0.16%   |
| Intel Core M            | 1         | 0.16%   |
| AMD Turion II           | 1         | 0.16%   |
| AMD Turion 64 X2 Mobile | 1         | 0.16%   |
| AMD PRO A10             | 1         | 0.16%   |
| AMD E2                  | 1         | 0.16%   |
| AMD E1                  | 1         | 0.16%   |
| AMD E                   | 1         | 0.16%   |
| AMD Athlon II           | 1         | 0.16%   |
| AMD Athlon              | 1         | 0.16%   |
| AMD A12                 | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 290       | 46.4%   |
| 2      | 217       | 34.72%  |
| 6      | 59        | 9.44%   |
| 8      | 57        | 9.12%   |
| 1      | 2         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 623       | 99.68%  |
| 3      | 1         | 0.16%   |
| 2      | 1         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 540       | 86.26%  |
| 1      | 86        | 13.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 625       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 46        | 7.31%   |
| 0x806ea    | 41        | 6.52%   |
| 0x806c1    | 37        | 5.88%   |
| 0x206a7    | 35        | 5.56%   |
| 0x806e9    | 33        | 5.25%   |
| 0x906ea    | 29        | 4.61%   |
| 0x406e3    | 29        | 4.61%   |
| 0x306a9    | 26        | 4.13%   |
| Unknown    | 25        | 3.97%   |
| 0x306d4    | 23        | 3.66%   |
| 0x08600106 | 23        | 3.66%   |
| 0x40651    | 22        | 3.5%    |
| 0x306c3    | 20        | 3.18%   |
| 0xa0652    | 17        | 2.7%    |
| 0x08108102 | 15        | 2.38%   |
| 0x706e5    | 14        | 2.23%   |
| 0x20655    | 14        | 2.23%   |
| 0x30678    | 13        | 2.07%   |
| 0x08108109 | 13        | 2.07%   |
| 0x806eb    | 12        | 1.91%   |
| 0x08600104 | 12        | 1.91%   |
| 0x906e9    | 11        | 1.75%   |
| 0x906ed    | 10        | 1.59%   |
| 0x0a50000c | 10        | 1.59%   |
| 0x506e3    | 9         | 1.43%   |
| 0x40661    | 8         | 1.27%   |
| 0x406c4    | 7         | 1.11%   |
| 0x08600103 | 7         | 1.11%   |
| 0x406c3    | 6         | 0.95%   |
| 0x706a1    | 5         | 0.79%   |
| 0x08608102 | 5         | 0.79%   |
| 0x1067a    | 4         | 0.64%   |
| 0x0a50000b | 4         | 0.64%   |
| 0x0810100b | 4         | 0.64%   |
| 0x106e5    | 3         | 0.48%   |
| 0x806d1    | 2         | 0.32%   |
| 0x6fd      | 2         | 0.32%   |
| 0x20652    | 2         | 0.32%   |
| 0x08600102 | 2         | 0.32%   |
| 0x08101016 | 2         | 0.32%   |
| 0x08101007 | 2         | 0.32%   |
| 0x07030105 | 2         | 0.32%   |
| 0x0700010f | 2         | 0.32%   |
| 0x07000106 | 2         | 0.32%   |
| 0x0600110f | 2         | 0.32%   |
| 0x010000c8 | 2         | 0.32%   |
| 0xa0660    | 1         | 0.16%   |
| 0x706a8    | 1         | 0.16%   |
| 0x6fb      | 1         | 0.16%   |
| 0x6fa      | 1         | 0.16%   |
| 0x506c9    | 1         | 0.16%   |
| 0x30673    | 1         | 0.16%   |
| 0x06006705 | 1         | 0.16%   |
| 0x0600611a | 1         | 0.16%   |
| 0x06006118 | 1         | 0.16%   |
| 0x06006110 | 1         | 0.16%   |
| 0x06001116 | 1         | 0.16%   |
| 0x05000101 | 1         | 0.16%   |
| 0x03000027 | 1         | 0.16%   |
| 0x03000025 | 1         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 187       | 29.92%  |
| Haswell       | 50        | 8%      |
| Zen 2         | 46        | 7.36%   |
| Skylake       | 39        | 6.24%   |
| TigerLake     | 37        | 5.92%   |
| SandyBridge   | 36        | 5.76%   |
| Zen+          | 29        | 4.64%   |
| IvyBridge     | 28        | 4.48%   |
| Silvermont    | 27        | 4.32%   |
| Broadwell     | 24        | 3.84%   |
| CometLake     | 18        | 2.88%   |
| IceLake       | 17        | 2.72%   |
| Westmere      | 16        | 2.56%   |
| Zen 3         | 14        | 2.24%   |
| Zen           | 8         | 1.28%   |
| Unknown       | 7         | 1.12%   |
| Goldmont plus | 6         | 0.96%   |
| Penryn        | 5         | 0.8%    |
| Excavator     | 5         | 0.8%    |
| Jaguar        | 4         | 0.64%   |
| Core          | 4         | 0.64%   |
| Puma          | 3         | 0.48%   |
| Piledriver    | 3         | 0.48%   |
| Nehalem       | 3         | 0.48%   |
| K10 Llano     | 3         | 0.48%   |
| K10           | 2         | 0.32%   |
| Steamroller   | 1         | 0.16%   |
| K8 Hammer     | 1         | 0.16%   |
| Goldmont      | 1         | 0.16%   |
| Bobcat        | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 468       | 56.93%  |
| Nvidia | 194       | 23.6%   |
| AMD    | 160       | 19.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 46        | 5.49%   |
| Intel UHD Graphics 620                                                                   | 44        | 5.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 36        | 4.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 35        | 4.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 3.82%   |
| Intel HD Graphics 620                                                                    | 31        | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 3.58%   |
| AMD Picasso                                                                              | 29        | 3.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 27        | 3.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 3.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 2.86%   |
| Intel HD Graphics 5500                                                                   | 23        | 2.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 2.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 2.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 1.55%   |
| AMD Cezanne                                                                              | 13        | 1.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 1.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.43%   |
| Intel HD Graphics 630                                                                    | 11        | 1.31%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 1.31%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 1.07%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 1.07%   |
| Intel HD Graphics 530                                                                    | 9         | 1.07%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 8         | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 0.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 7         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.84%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 6         | 0.72%   |
| Nvidia GM108M [GeForce 940M]                                                             | 6         | 0.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.72%   |
| Nvidia GM108M [GeForce MX110]                                                            | 5         | 0.6%    |
| Nvidia GM108M [GeForce 930MX]                                                            | 5         | 0.6%    |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.6%    |
| AMD Lucienne                                                                             | 5         | 0.6%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.48%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.48%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.48%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 4         | 0.48%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 4         | 0.48%   |
| Nvidia GP108M [GeForce MX230]                                                            | 3         | 0.36%   |
| Nvidia GP107M [GeForce MX350]                                                            | 3         | 0.36%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 0.36%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 3         | 0.36%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.36%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.36%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 3         | 0.36%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.36%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.36%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.36%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 3         | 0.36%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.36%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.24%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 2         | 0.24%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.24%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 288       | 46.08%  |
| Intel + Nvidia | 150       | 24%     |
| 1 x AMD        | 101       | 16.16%  |
| Intel + AMD    | 28        | 4.48%   |
| 1 x Nvidia     | 24        | 3.84%   |
| AMD + Nvidia   | 19        | 3.04%   |
| 2 x AMD        | 12        | 1.92%   |
| Other          | 2         | 0.32%   |
| 2 x Nvidia     | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 546       | 86.39%  |
| Proprietary | 81        | 12.82%  |
| Unknown     | 5         | 0.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 371       | 58.24%  |
| 1.01-2.0   | 108       | 16.95%  |
| 0.01-0.5   | 78        | 12.24%  |
| 3.01-4.0   | 40        | 6.28%   |
| 0.51-1.0   | 21        | 3.3%    |
| 5.01-6.0   | 9         | 1.41%   |
| 2.01-3.0   | 5         | 0.78%   |
| 7.01-8.0   | 4         | 0.63%   |
| 8.01-16.0  | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 130       | 16.84%  |
| LG Display              | 120       | 15.54%  |
| Chimei Innolux          | 108       | 13.99%  |
| BOE                     | 91        | 11.79%  |
| Samsung Electronics     | 63        | 8.16%   |
| Dell                    | 41        | 5.31%   |
| Sharp                   | 39        | 5.05%   |
| Goldstar                | 28        | 3.63%   |
| PANDA                   | 16        | 2.07%   |
| Lenovo                  | 16        | 2.07%   |
| Apple                   | 16        | 2.07%   |
| Hewlett-Packard         | 15        | 1.94%   |
| Acer                    | 10        | 1.3%    |
| Ancor Communications    | 9         | 1.17%   |
| CSO                     | 8         | 1.04%   |
| Chi Mei Optoelectronics | 8         | 1.04%   |
| BenQ                    | 8         | 1.04%   |
| Philips                 | 7         | 0.91%   |
| InfoVision              | 4         | 0.52%   |
| AOC                     | 4         | 0.52%   |
| TMX                     | 3         | 0.39%   |
| Sony                    | 3         | 0.39%   |
| Sceptre Tech            | 3         | 0.39%   |
| Iiyama                  | 3         | 0.39%   |
| ASUSTek Computer        | 3         | 0.39%   |
| ViewSonic               | 2         | 0.26%   |
| Toshiba                 | 2         | 0.26%   |
| JDI                     | 2         | 0.26%   |
| Insignia                | 2         | 0.26%   |
| SKY                     | 1         | 0.13%   |
| QCM                     | 1         | 0.13%   |
| Pixio                   | 1         | 0.13%   |
| Panasonic               | 1         | 0.13%   |
| Orion                   | 1         | 0.13%   |
| OPT                     | 1         | 0.13%   |
| LG Philips              | 1         | 0.13%   |
| KTC                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 10        | 1.28%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 9         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 1.15%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 7         | 0.9%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 6         | 0.77%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 6         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 6         | 0.77%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 5         | 0.64%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 5         | 0.64%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 5         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch      | 5         | 0.64%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 4         | 0.51%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 0.51%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 0.51%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.51%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch        | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 4         | 0.51%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                 | 4         | 0.51%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 3         | 0.38%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.38%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 3         | 0.38%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 3         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch  | 3         | 0.38%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.38%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 3         | 0.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.38%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 3         | 0.38%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch      | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 3         | 0.38%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 0.38%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.38%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.38%   |
| BOE LCD Monitor BOE0690 1920x1080 344x193mm 15.5-inch                 | 3         | 0.38%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.38%   |
| Apple Color LCD APPA022 2880x1800 331x207mm 15.4-inch                 | 3         | 0.38%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 0.26%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 2         | 0.26%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 2         | 0.26%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 2         | 0.26%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 2         | 0.26%   |
| LG Display LCD Monitor LGD064E 1920x1080 309x174mm 14.0-inch          | 2         | 0.26%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch          | 2         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 364       | 51.63%  |
| 1366x768 (WXGA)    | 150       | 21.28%  |
| 3840x2160 (4K)     | 38        | 5.39%   |
| 2560x1440 (QHD)    | 29        | 4.11%   |
| 1600x900 (HD+)     | 23        | 3.26%   |
| 1920x1200 (WUXGA)  | 20        | 2.84%   |
| 2880x1800          | 11        | 1.56%   |
| 2560x1600          | 11        | 1.56%   |
| 2560x1080          | 7         | 0.99%   |
| 3200x1800 (QHD+)   | 6         | 0.85%   |
| 1360x768           | 6         | 0.85%   |
| 3440x1440          | 5         | 0.71%   |
| 1280x800 (WXGA)    | 5         | 0.71%   |
| 1440x900 (WXGA+)   | 4         | 0.57%   |
| 3840x2400          | 3         | 0.43%   |
| 3456x2160          | 2         | 0.28%   |
| 3000x2000          | 2         | 0.28%   |
| 2160x1440          | 2         | 0.28%   |
| 2160x1350          | 2         | 0.28%   |
| 1920x540           | 2         | 0.28%   |
| 1920x1280          | 2         | 0.28%   |
| 1680x1050 (WSXGA+) | 2         | 0.28%   |
| 1280x1024 (SXGA)   | 2         | 0.28%   |
| 3840x1600          | 1         | 0.14%   |
| 3840x1100          | 1         | 0.14%   |
| 2256x1504          | 1         | 0.14%   |
| 1920x515           | 1         | 0.14%   |
| 1680x945           | 1         | 0.14%   |
| 1440x2560          | 1         | 0.14%   |
| 1024x768 (XGA)     | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 316       | 41.04%  |
| 13      | 125       | 16.23%  |
| 14      | 92        | 11.95%  |
| 17      | 37        | 4.81%   |
| 27      | 36        | 4.68%   |
| 24      | 36        | 4.68%   |
| 23      | 32        | 4.16%   |
| 12      | 18        | 2.34%   |
| 21      | 14        | 1.82%   |
| 34      | 10        | 1.3%    |
| 18      | 10        | 1.3%    |
| 31      | 7         | 0.91%   |
| 11      | 7         | 0.91%   |
| 16      | 5         | 0.65%   |
| 32      | 3         | 0.39%   |
| 29      | 3         | 0.39%   |
| 25      | 3         | 0.39%   |
| 40      | 2         | 0.26%   |
| 20      | 2         | 0.26%   |
| 74      | 1         | 0.13%   |
| 65      | 1         | 0.13%   |
| 54      | 1         | 0.13%   |
| 47      | 1         | 0.13%   |
| 39      | 1         | 0.13%   |
| 37      | 1         | 0.13%   |
| 36      | 1         | 0.13%   |
| 35      | 1         | 0.13%   |
| 33      | 1         | 0.13%   |
| 22      | 1         | 0.13%   |
| 8       | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 473       | 62.48%  |
| 501-600     | 96        | 12.68%  |
| 201-300     | 77        | 10.17%  |
| 351-400     | 45        | 5.94%   |
| 401-500     | 27        | 3.57%   |
| 701-800     | 15        | 1.98%   |
| 601-700     | 13        | 1.72%   |
| 801-900     | 5         | 0.66%   |
| 1001-1500   | 3         | 0.4%    |
| 1501-2000   | 1         | 0.13%   |
| 101-200     | 1         | 0.13%   |
| Unknown     | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 559       | 86.13%  |
| 16/10 | 62        | 9.55%   |
| 21/9  | 13        | 2%      |
| 3/2   | 8         | 1.23%   |
| 5/4   | 2         | 0.31%   |
| 4/3   | 1         | 0.15%   |
| 32/9  | 1         | 0.15%   |
| 3.88  | 1         | 0.15%   |
| 3.40  | 1         | 0.15%   |
| 0.62  | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 317       | 41.33%  |
| 81-90          | 166       | 21.64%  |
| 201-250        | 66        | 8.6%    |
| 71-80          | 50        | 6.52%   |
| 301-350        | 36        | 4.69%   |
| 121-130        | 34        | 4.43%   |
| 351-500        | 25        | 3.26%   |
| 61-70          | 17        | 2.22%   |
| 251-300        | 14        | 1.83%   |
| 141-150        | 11        | 1.43%   |
| 51-60          | 8         | 1.04%   |
| 151-200        | 6         | 0.78%   |
| 501-1000       | 6         | 0.78%   |
| More than 1000 | 3         | 0.39%   |
| 111-120        | 3         | 0.39%   |
| 1-40           | 2         | 0.26%   |
| 131-140        | 1         | 0.13%   |
| 91-100         | 1         | 0.13%   |
| Unknown        | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 355       | 47.33%  |
| 101-120       | 172       | 22.93%  |
| 51-100        | 114       | 15.2%   |
| 161-240       | 66        | 8.8%    |
| More than 240 | 36        | 4.8%    |
| 1-50          | 6         | 0.8%    |
| Unknown       | 1         | 0.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 460       | 72.78%  |
| 2     | 136       | 21.52%  |
| 3     | 21        | 3.32%   |
| 0     | 15        | 2.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 389       | 41.21%  |
| Realtek Semiconductor             | 310       | 32.84%  |
| Qualcomm Atheros                  | 114       | 12.08%  |
| Broadcom                          | 37        | 3.92%   |
| Broadcom Limited                  | 15        | 1.59%   |
| TP-Link                           | 11        | 1.17%   |
| Lenovo                            | 10        | 1.06%   |
| DisplayLink                       | 6         | 0.64%   |
| Ralink                            | 5         | 0.53%   |
| MEDIATEK                          | 5         | 0.53%   |
| Ralink Technology                 | 4         | 0.42%   |
| Hewlett-Packard                   | 4         | 0.42%   |
| Sierra Wireless                   | 3         | 0.32%   |
| Samsung Electronics               | 3         | 0.32%   |
| Qualcomm                          | 3         | 0.32%   |
| Marvell Technology Group          | 3         | 0.32%   |
| NetGear                           | 2         | 0.21%   |
| FIBOCOM                           | 2         | 0.21%   |
| Ericsson Business Mobile Networks | 2         | 0.21%   |
| Apple                             | 2         | 0.21%   |
| T & A Mobile Phones               | 1         | 0.11%   |
| Qualcomm Atheros Communications   | 1         | 0.11%   |
| Nvidia                            | 1         | 0.11%   |
| MicroPython                       | 1         | 0.11%   |
| Linksys                           | 1         | 0.11%   |
| LG Electronics                    | 1         | 0.11%   |
| JMicron Technology                | 1         | 0.11%   |
| Huawei Technologies               | 1         | 0.11%   |
| Google                            | 1         | 0.11%   |
| Dell                              | 1         | 0.11%   |
| D-Link System                     | 1         | 0.11%   |
| D-Link                            | 1         | 0.11%   |
| ASUSTek Computer                  | 1         | 0.11%   |
| ASIX Electronics                  | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 210       | 18.77%  |
| Intel Wi-Fi 6 AX200                                               | 71        | 6.34%   |
| Intel Wireless 8265 / 8275                                        | 43        | 3.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 40        | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 3.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 34        | 3.04%   |
| Intel Wi-Fi 6 AX201                                               | 28        | 2.5%    |
| Intel Wireless 8260                                               | 22        | 1.97%   |
| Intel Wireless 7265                                               | 22        | 1.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 21        | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 20        | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 20        | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 20        | 1.79%   |
| Intel Wireless 7260                                               | 19        | 1.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 17        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 16        | 1.43%   |
| Intel Wireless 3165                                               | 14        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 14        | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 12        | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 11        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 10        | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 8         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 0.54%   |
| Intel Wireless 3160                                               | 6         | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.54%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.54%   |
| Intel Ethernet Connection (6) I219-LM                             | 6         | 0.54%   |
| Intel Centrino Advanced-N 6235                                    | 6         | 0.54%   |
| TP-Link USB 10/100/1000 LAN                                       | 5         | 0.45%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 0.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 5         | 0.45%   |
| Intel Wireless-AC 9260                                            | 5         | 0.45%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.45%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 5         | 0.45%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.45%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.36%   |
| MEDIATEK Network controller                                       | 4         | 0.36%   |
| Lenovo ThinkPad TBT3 LAN                                          | 4         | 0.36%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.36%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.36%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 4         | 0.36%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 4         | 0.36%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 0.36%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 379       | 60.74%  |
| Qualcomm Atheros                | 100       | 16.03%  |
| Realtek Semiconductor           | 73        | 11.7%   |
| Broadcom                        | 35        | 5.61%   |
| Broadcom Limited                | 7         | 1.12%   |
| TP-Link                         | 5         | 0.8%    |
| Ralink                          | 5         | 0.8%    |
| Ralink Technology               | 4         | 0.64%   |
| MEDIATEK                        | 4         | 0.64%   |
| Sierra Wireless                 | 3         | 0.48%   |
| Qualcomm                        | 2         | 0.32%   |
| NetGear                         | 2         | 0.32%   |
| FIBOCOM                         | 2         | 0.32%   |
| Qualcomm Atheros Communications | 1         | 0.16%   |
| Hewlett-Packard                 | 1         | 0.16%   |
| D-Link System                   | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 71        | 11.36%  |
| Intel Wireless 8265 / 8275                                     | 43        | 6.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 40        | 6.4%    |
| Intel Wi-Fi 6 AX201                                            | 28        | 4.48%   |
| Intel Wireless 8260                                            | 22        | 3.52%   |
| Intel Wireless 7265                                            | 22        | 3.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 21        | 3.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 20        | 3.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 20        | 3.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 20        | 3.2%    |
| Intel Wireless 7260                                            | 19        | 3.04%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 17        | 2.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 16        | 2.56%   |
| Intel Wireless 3165                                            | 14        | 2.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 14        | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 12        | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 1.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 1.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 0.96%   |
| Intel Wireless 3160                                            | 6         | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 0.96%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 0.8%    |
| Intel Wireless-AC 9260                                         | 5         | 0.8%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 5         | 0.8%    |
| Intel Centrino Advanced-N 6200                                 | 5         | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.64%   |
| MEDIATEK Network controller                                    | 4         | 0.64%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.64%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.64%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 0.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 0.48%   |
| Realtek Realtek Network controller                             | 3         | 0.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.48%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.48%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.48%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.48%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2         | 0.32%   |
| Sierra Wireless EM7345 4G LTE                                  | 2         | 0.32%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                         | 2         | 0.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.32%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.32%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 2         | 0.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.32%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.32%   |
| FIBOCOM L830-EB-00                                             | 2         | 0.32%   |
| Broadcom Limited BCM43602 802.11ac Wireless LAN SoC            | 2         | 0.32%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 0.32%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 0.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 284       | 59.17%  |
| Intel                    | 119       | 24.79%  |
| Qualcomm Atheros         | 22        | 4.58%   |
| Lenovo                   | 10        | 2.08%   |
| Broadcom Limited         | 8         | 1.67%   |
| TP-Link                  | 6         | 1.25%   |
| DisplayLink              | 6         | 1.25%   |
| Broadcom                 | 5         | 1.04%   |
| Samsung Electronics      | 3         | 0.63%   |
| Marvell Technology Group | 3         | 0.63%   |
| Apple                    | 2         | 0.42%   |
| Qualcomm                 | 1         | 0.21%   |
| Nvidia                   | 1         | 0.21%   |
| MediaTek                 | 1         | 0.21%   |
| Linksys                  | 1         | 0.21%   |
| LG Electronics           | 1         | 0.21%   |
| JMicron Technology       | 1         | 0.21%   |
| Huawei Technologies      | 1         | 0.21%   |
| Hewlett-Packard          | 1         | 0.21%   |
| Google                   | 1         | 0.21%   |
| D-Link                   | 1         | 0.21%   |
| ASUSTek Computer         | 1         | 0.21%   |
| ASIX Electronics         | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 210       | 43.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 39        | 8.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 34        | 6.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 21        | 4.31%   |
| Intel Ethernet Connection (4) I219-LM                                          | 11        | 2.26%   |
| Intel Ethernet Connection (4) I219-V                                           | 9         | 1.85%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 1.44%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 1.44%   |
| Intel Ethernet Connection (7) I219-LM                                          | 6         | 1.23%   |
| Intel Ethernet Connection (6) I219-V                                           | 6         | 1.23%   |
| Intel Ethernet Connection (6) I219-LM                                          | 6         | 1.23%   |
| TP-Link USB 10/100/1000 LAN                                                    | 5         | 1.03%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 1.03%   |
| Intel Ethernet Connection (10) I219-V                                          | 5         | 1.03%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 0.82%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 4         | 0.82%   |
| Intel Ethernet Connection I219-V                                               | 4         | 0.82%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 0.62%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 3         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.62%   |
| DisplayLink Dell Universal Dock D6000                                          | 3         | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.41%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.41%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 2         | 0.41%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.41%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.41%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 0.41%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 0.41%   |
| DisplayLink USB3.0 5K Graphic Docking                                          | 2         | 0.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.41%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.21%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.21%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.21%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.21%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.21%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.21%   |
| Qualcomm Android                                                               | 1         | 0.21%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.21%   |
| MediaTek WP6                                                                   | 1         | 0.21%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.21%   |
| Linksys Gigabit Ethernet Adapter                                               | 1         | 0.21%   |
| LG G2 Android Phone [tethering mode]                                           | 1         | 0.21%   |
| Lenovo USB-C Hub                                                               | 1         | 0.21%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.21%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.21%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.21%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.21%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 601       | 56.91%  |
| Ethernet | 448       | 42.42%  |
| Modem    | 7         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 557       | 64.1%   |
| Ethernet | 310       | 35.67%  |
| Modem    | 2         | 0.23%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 398       | 63.68%  |
| 1     | 199       | 31.84%  |
| 0     | 22        | 3.52%   |
| 3     | 6         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 482       | 76.63%  |
| Yes  | 147       | 23.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 324       | 61.6%   |
| Qualcomm Atheros Communications | 49        | 9.32%   |
| Realtek Semiconductor           | 40        | 7.6%    |
| Lite-On Technology              | 27        | 5.13%   |
| IMC Networks                    | 23        | 4.37%   |
| Broadcom                        | 21        | 3.99%   |
| Apple                           | 14        | 2.66%   |
| Dell                            | 6         | 1.14%   |
| Foxconn / Hon Hai               | 5         | 0.95%   |
| Realtek                         | 4         | 0.76%   |
| Ralink                          | 4         | 0.76%   |
| Cambridge Silicon Radio         | 4         | 0.76%   |
| Hewlett-Packard                 | 2         | 0.38%   |
| Unknown                         | 1         | 0.19%   |
| ASUSTek Computer                | 1         | 0.19%   |
| Askey Computer                  | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 121       | 23%     |
| Intel Bluetooth Device                                                              | 68        | 12.93%  |
| Intel AX200 Bluetooth                                                               | 68        | 12.93%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 49        | 9.32%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 30        | 5.7%    |
| Realtek Bluetooth Radio                                                             | 22        | 4.18%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 2.47%   |
| Apple Bluetooth Host Controller                                                     | 13        | 2.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 2.28%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 1.52%   |
| IMC Networks Bluetooth Radio                                                        | 8         | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 1.33%   |
| Intel AX210 Bluetooth                                                               | 6         | 1.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 5         | 0.95%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.76%   |
| Realtek Bluetooth Radio                                                             | 4         | 0.76%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 0.76%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 0.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 0.76%   |
| IMC Networks Wireless_Device                                                        | 4         | 0.76%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 0.76%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 0.76%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 0.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.57%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 3         | 0.57%   |
| Lite-On Bluetooth Radio                                                             | 3         | 0.57%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.57%   |
| IMC Networks Bluetooth Device                                                       | 3         | 0.57%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 2         | 0.38%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.38%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.38%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.38%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.38%   |
| Broadcom BCM20703A1 Bluetooth 4.1 + LE                                              | 2         | 0.38%   |
| Broadcom BCM20702A0                                                                 | 2         | 0.38%   |
| Unknown Bluetooth Device                                                            | 1         | 0.19%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.19%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE                                | 1         | 0.19%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.19%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.19%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.19%   |
| IMC Networks Bluetooth                                                              | 1         | 0.19%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.19%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.19%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.19%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.19%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.19%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.19%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.19%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.19%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.19%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.19%   |
| Askey Bluetooth Device                                                              | 1         | 0.19%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 476       | 60.25%  |
| AMD                       | 134       | 16.96%  |
| Nvidia                    | 111       | 14.05%  |
| Lenovo                    | 9         | 1.14%   |
| Logitech                  | 7         | 0.89%   |
| GN Netcom                 | 6         | 0.76%   |
| C-Media Electronics       | 6         | 0.76%   |
| Realtek Semiconductor     | 5         | 0.63%   |
| Plantronics               | 4         | 0.51%   |
| Sennheiser Communications | 3         | 0.38%   |
| Microsoft                 | 3         | 0.38%   |
| Hewlett-Packard           | 3         | 0.38%   |
| RODE Microphones          | 2         | 0.25%   |
| JMTek                     | 2         | 0.25%   |
| Dell                      | 2         | 0.25%   |
| Blue Microphones          | 2         | 0.25%   |
| ZOOM                      | 1         | 0.13%   |
| Trust                     | 1         | 0.13%   |
| Sony                      | 1         | 0.13%   |
| Signalpath International  | 1         | 0.13%   |
| SAVITECH                  | 1         | 0.13%   |
| Quanta                    | 1         | 0.13%   |
| Native Instruments        | 1         | 0.13%   |
| Generalplus Technology    | 1         | 0.13%   |
| Fujitsu                   | 1         | 0.13%   |
| Conexant Systems          | 1         | 0.13%   |
| CMX Systems               | 1         | 0.13%   |
| Cambridge Silicon Radio   | 1         | 0.13%   |
| BEHRINGER International   | 1         | 0.13%   |
| Audio-Technica            | 1         | 0.13%   |
| Apple                     | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 106       | 10.84%  |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 102       | 10.43%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 58        | 5.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 39        | 3.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 37        | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 34        | 3.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 34        | 3.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 32        | 3.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 30        | 3.07%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 28        | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 28        | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 2.45%   |
| Intel Broadwell-U Audio Controller                                                                | 24        | 2.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 2.25%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 20        | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 1.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 1.74%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 1.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 1.43%   |
| AMD FCH Azalia Controller                                                                         | 14        | 1.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 13        | 1.33%   |
| Intel CM238 HD Audio Controller                                                                   | 12        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 9         | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 0.82%   |
| Nvidia Audio device                                                                               | 8         | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 7         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 0.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.61%   |
| Realtek Semiconductor USB Audio                                                                   | 5         | 0.51%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 0.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 0.51%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.41%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 0.41%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.41%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 4         | 0.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.41%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 4         | 0.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 0.41%   |
| Sennheiser Communications Headset [PC 8]                                                          | 3         | 0.31%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.31%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.31%   |
| Microsoft LifeChat LX-3000 Headset                                                                | 3         | 0.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 0.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.31%   |
| Hewlett-Packard USB Audio                                                                         | 3         | 0.31%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.31%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.31%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 0.31%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.31%   |
| RODE Microphones RODE NT-USB                                                                      | 2         | 0.2%    |
| Plantronics Blackwire 3225 Series                                                                 | 2         | 0.2%    |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.2%    |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.2%    |
| Logitech H600 [Wireless Headset]                                                                  | 2         | 0.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 101       | 26.1%   |
| SK Hynix            | 94        | 24.29%  |
| Micron Technology   | 49        | 12.66%  |
| Kingston            | 34        | 8.79%   |
| Unknown             | 24        | 6.2%    |
| Crucial             | 18        | 4.65%   |
| A-DATA Technology   | 15        | 3.88%   |
| Ramaxel Technology  | 7         | 1.81%   |
| Elpida              | 6         | 1.55%   |
| Corsair             | 6         | 1.55%   |
| Teikon              | 4         | 1.03%   |
| Team                | 4         | 1.03%   |
| Smart               | 4         | 1.03%   |
| Nanya Technology    | 3         | 0.78%   |
| Avant               | 3         | 0.78%   |
| Unknown (ABCD)      | 2         | 0.52%   |
| Silicon Power       | 2         | 0.52%   |
| GOODRAM             | 2         | 0.52%   |
| Goldkey             | 2         | 0.52%   |
| OnBoard             | 1         | 0.26%   |
| KomputerBay         | 1         | 0.26%   |
| Kllisre             | 1         | 0.26%   |
| Golden Empire       | 1         | 0.26%   |
| Gold Key            | 1         | 0.26%   |
| G.Skill             | 1         | 0.26%   |
| 0898000080AD        | 1         | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s            | 9         | 2.2%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 8         | 1.95%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 8         | 1.95%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 7         | 1.71%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 5         | 1.22%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 5         | 1.22%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 1.22%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 5         | 1.22%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                         | 4         | 0.98%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 0.98%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 4         | 0.98%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 4         | 0.98%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s           | 4         | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 4         | 0.98%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s             | 4         | 0.98%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.73%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 0.73%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.73%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 0.73%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 3         | 0.73%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.73%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 3         | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 3         | 0.73%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s              | 3         | 0.73%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.73%   |
| Samsung RAM K4UBE3D4AA-MGCL 8192MB Row Of Chips LPDDR4 4267MT/s     | 3         | 0.73%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 3         | 0.73%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 3         | 0.73%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 3         | 0.73%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 2         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 2         | 0.49%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s               | 2         | 0.49%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 2         | 0.49%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 2         | 0.49%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s                        | 2         | 0.49%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.49%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.49%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.49%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.49%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 0.49%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 0.49%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s           | 2         | 0.49%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 2         | 0.49%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 2         | 0.49%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.49%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 2         | 0.49%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                         | 2         | 0.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 0.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s               | 2         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 2         | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 2         | 0.49%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s            | 2         | 0.49%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 0.49%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 2         | 0.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.49%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 2         | 0.49%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 2         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 190       | 59.75%  |
| DDR3    | 91        | 28.62%  |
| LPDDR4  | 16        | 5.03%   |
| LPDDR3  | 15        | 4.72%   |
| DDR2    | 3         | 0.94%   |
| Unknown | 2         | 0.63%   |
| SDRAM   | 1         | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 278       | 86.6%   |
| Row Of Chips | 35        | 10.9%   |
| Chip         | 5         | 1.56%   |
| DIMM         | 3         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 125       | 36.02%  |
| 4096  | 110       | 31.7%   |
| 16384 | 72        | 20.75%  |
| 2048  | 25        | 7.2%    |
| 32768 | 8         | 2.31%   |
| 1024  | 7         | 2.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 90        | 26.71%  |
| 3200    | 76        | 22.55%  |
| 1600    | 63        | 18.69%  |
| 2400    | 28        | 8.31%   |
| 2133    | 21        | 6.23%   |
| 1333    | 12        | 3.56%   |
| 4267    | 11        | 3.26%   |
| 1334    | 11        | 3.26%   |
| 1867    | 8         | 2.37%   |
| 1066    | 5         | 1.48%   |
| Unknown | 4         | 1.19%   |
| 667     | 3         | 0.89%   |
| 4266    | 1         | 0.3%    |
| 4199    | 1         | 0.3%    |
| 1866    | 1         | 0.3%    |
| 1067    | 1         | 0.3%    |
| 800     | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 66.67%  |
| Ricoh  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Ricoh SP 212SUw           | 1         | 33.33%  |
| Canon TR8500 series       | 1         | 33.33%  |
| Canon PIXMA MG3000 series | 1         | 33.33%  |

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
| Chicony Electronics                    | 156       | 27.23%  |
| IMC Networks                           | 86        | 15.01%  |
| Microdia                               | 58        | 10.12%  |
| Acer                                   | 46        | 8.03%   |
| Realtek Semiconductor                  | 40        | 6.98%   |
| Sunplus Innovation Technology          | 31        | 5.41%   |
| Quanta                                 | 31        | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 4.01%   |
| Syntek                                 | 15        | 2.62%   |
| Lite-On Technology                     | 15        | 2.62%   |
| Suyin                                  | 13        | 2.27%   |
| Apple                                  | 11        | 1.92%   |
| Logitech                               | 8         | 1.4%    |
| Silicon Motion                         | 6         | 1.05%   |
| Alcor Micro                            | 6         | 1.05%   |
| Ricoh                                  | 3         | 0.52%   |
| Microsoft                              | 3         | 0.52%   |
| Luxvisions Innotech Limited            | 3         | 0.52%   |
| ALi                                    | 3         | 0.52%   |
| Z-Star Microelectronics                | 2         | 0.35%   |
| Samsung Electronics                    | 2         | 0.35%   |
| Pixart Imaging                         | 2         | 0.35%   |
| Lenovo                                 | 2         | 0.35%   |
| KYE Systems (Mouse Systems)            | 2         | 0.35%   |
| Y Media                                | 1         | 0.17%   |
| WaveRider Communications               | 1         | 0.17%   |
| Jieli Technology                       | 1         | 0.17%   |
| Importek                               | 1         | 0.17%   |
| Foxconn / Hon Hai                      | 1         | 0.17%   |
| DigiTech                               | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 52        | 8.95%   |
| IMC Networks Integrated Camera                                 | 37        | 6.37%   |
| Microdia Integrated_Webcam_HD                                  | 32        | 5.51%   |
| Realtek Integrated_Webcam_HD                                   | 21        | 3.61%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 20        | 3.44%   |
| Acer Integrated Camera                                         | 19        | 3.27%   |
| Chicony HD WebCam                                              | 15        | 2.58%   |
| Sunplus Integrated_Webcam_HD                                   | 13        | 2.24%   |
| Syntek Integrated Camera                                       | 11        | 1.89%   |
| Chicony Integrated Camera (1280x720@30)                        | 11        | 1.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 10        | 1.72%   |
| Lite-On Integrated Camera                                      | 8         | 1.38%   |
| Chicony HP TrueVision HD Camera                                | 8         | 1.38%   |
| Chicony USB2.0 Camera                                          | 7         | 1.2%    |
| Apple iPhone5/5C/5S/6                                          | 7         | 1.2%    |
| Quanta HP TrueVision HD Camera                                 | 6         | 1.03%   |
| Chicony HP HD Camera                                           | 6         | 1.03%   |
| Sunplus HD WebCam                                              | 5         | 0.86%   |
| Quanta HP HD Camera                                            | 5         | 0.86%   |
| Quanta HD Webcam                                               | 5         | 0.86%   |
| Lite-On HP HD Camera                                           | 5         | 0.86%   |
| Chicony USB2.0 HD UVC WebCam                                   | 5         | 0.86%   |
| Chicony FJ Camera                                              | 5         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 5         | 0.86%   |
| Acer SunplusIT Integrated Camera                               | 5         | 0.86%   |
| Acer Lenovo EasyCamera                                         | 5         | 0.86%   |
| Quanta HD User Facing                                          | 4         | 0.69%   |
| Microdia USB Camera                                            | 4         | 0.69%   |
| Microdia Integrated Webcam                                     | 4         | 0.69%   |
| Logitech HD Pro Webcam C920                                    | 4         | 0.69%   |
| Chicony HD User Facing                                         | 4         | 0.69%   |
| Syntek EasyCamera                                              | 3         | 0.52%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 3         | 0.52%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 3         | 0.52%   |
| Realtek Lenovo EasyCamera                                      | 3         | 0.52%   |
| Realtek Integrated Webcam                                      | 3         | 0.52%   |
| Realtek HP Truevision HD                                       | 3         | 0.52%   |
| Quanta Laptop_Integrated_Webcam_2HDM                           | 3         | 0.52%   |
| Microdia Integrated Webcam HD                                  | 3         | 0.52%   |
| IMC Networks USB Camera                                        | 3         | 0.52%   |
| Chicony VGA Webcam                                             | 3         | 0.52%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 3         | 0.52%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 3         | 0.52%   |
| Chicony HP HD Webcam                                           | 3         | 0.52%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 3         | 0.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 3         | 0.52%   |
| Apple Built-in iSight                                          | 3         | 0.52%   |
| ALi Gateway Webcam                                             | 3         | 0.52%   |
| Acer EasyCamera                                                | 3         | 0.52%   |
| Acer BisonCam, NB Pro                                          | 3         | 0.52%   |
| Suyin Integrated_Webcam_HD                                     | 2         | 0.34%   |
| Sunplus Lenovo EasyCamera                                      | 2         | 0.34%   |
| Sunplus Integrated_Webcam_FHD                                  | 2         | 0.34%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 2         | 0.34%   |
| Realtek USB2.0 HD UVC WebCam                                   | 2         | 0.34%   |
| Realtek HD WebCam                                              | 2         | 0.34%   |
| Quanta VGA WebCam                                              | 2         | 0.34%   |
| Quanta ov9734_techfront_camera                                 | 2         | 0.34%   |
| Quanta hm1091_techfront                                        | 2         | 0.34%   |
| Pixart Imaging VGA Webcam                                      | 2         | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 50        | 32.47%  |
| Validity Sensors           | 48        | 31.17%  |
| Shenzhen Goodix Technology | 29        | 18.83%  |
| Elan Microelectronics      | 8         | 5.19%   |
| LighTuning Technology      | 7         | 4.55%   |
| Upek                       | 6         | 3.9%    |
| AuthenTec                  | 4         | 2.6%    |
| STMicroelectronics         | 1         | 0.65%   |
| Focal-systems.Corp         | 1         | 0.65%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 13.64%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 8.44%   |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 7.14%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 6.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 5.84%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 5.19%   |
| Elan ELAN:Fingerprint                                                      | 8         | 5.19%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 4.55%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 3.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 3.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 3.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 3.25%   |
| Unknown                                                                    | 5         | 3.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.6%    |
| Synaptics  WBDI                                                            | 4         | 2.6%    |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 1.95%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.95%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.95%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.95%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.3%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.3%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.65%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.65%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.65%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.65%   |
| Synaptics WBDI Device                                                      | 1         | 0.65%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.65%   |
| LighTuning EgisTec_ES603                                                   | 1         | 0.65%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.65%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.65%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.65%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.65%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.65%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 23        | 39.66%  |
| Alcor Micro           | 21        | 36.21%  |
| Lenovo                | 4         | 6.9%    |
| Upek                  | 3         | 5.17%   |
| O2 Micro              | 3         | 5.17%   |
| SCM Microsystems      | 1         | 1.72%   |
| Hewlett-Packard       | 1         | 1.72%   |
| Gemalto (was Gemplus) | 1         | 1.72%   |
| Chicony Electronics   | 1         | 1.72%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 21        | 36.21%  |
| Broadcom 58200                                                               | 8         | 13.79%  |
| Broadcom 5880                                                                | 6         | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 8.62%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.9%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 6.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 5.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 5.17%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 1.72%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.72%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.72%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.72%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 388       | 61.2%   |
| 1     | 223       | 35.17%  |
| 2     | 19        | 3%      |
| 3     | 3         | 0.47%   |
| 4     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 153       | 56.88%  |
| Multimedia controller    | 32        | 11.9%   |
| Graphics card            | 28        | 10.41%  |
| Net/wireless             | 20        | 7.43%   |
| Chipcard                 | 10        | 3.72%   |
| Storage                  | 8         | 2.97%   |
| Bluetooth                | 5         | 1.86%   |
| Modem                    | 3         | 1.12%   |
| Communication controller | 3         | 1.12%   |
| Sound                    | 2         | 0.74%   |
| Net/ethernet             | 2         | 0.74%   |
| Card reader              | 2         | 0.74%   |
| Camera                   | 1         | 0.37%   |

