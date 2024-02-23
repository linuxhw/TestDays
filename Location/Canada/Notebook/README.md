Linux in Canada - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Canada.

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

Total: 4760

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [7b22729e20](https://linux-hardware.org/?probe=7b22729e20) | Feb 02, 2024 |
| HP            | Laptop 17-cp0xxx            | [601c3c2cc4](https://linux-hardware.org/?probe=601c3c2cc4) | Feb 02, 2024 |
| ASUSTek       | N56VZ                       | [2209fe1372](https://linux-hardware.org/?probe=2209fe1372) | Feb 02, 2024 |
| HP            | EliteBook 840 G7 Noteboo... | [6f09cb7800](https://linux-hardware.org/?probe=6f09cb7800) | Feb 02, 2024 |
| Lenovo        | ThinkPad X230 Tablet 343... | [1c4d4deade](https://linux-hardware.org/?probe=1c4d4deade) | Feb 01, 2024 |
| Dell          | Vostro 3500                 | [1d57e2e0b1](https://linux-hardware.org/?probe=1d57e2e0b1) | Feb 01, 2024 |
| Apple         | MacBookPro11,3              | [3a809ef1d0](https://linux-hardware.org/?probe=3a809ef1d0) | Jan 31, 2024 |
| Unknown       | Unknown                     | [13b20f5383](https://linux-hardware.org/?probe=13b20f5383) | Jan 31, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th (... | [14b81c317f](https://linux-hardware.org/?probe=14b81c317f) | Jan 31, 2024 |
| HP            | ProBook 650 G2              | [cd22b7035d](https://linux-hardware.org/?probe=cd22b7035d) | Jan 30, 2024 |
| Lenovo        | ThinkPad P52s 20LCS2Y800    | [cb08606d1d](https://linux-hardware.org/?probe=cb08606d1d) | Jan 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bd5392e681](https://linux-hardware.org/?probe=bd5392e681) | Jan 30, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [bf8891bdd5](https://linux-hardware.org/?probe=bf8891bdd5) | Jan 30, 2024 |
| HP            | Notebook                    | [6757d33e0e](https://linux-hardware.org/?probe=6757d33e0e) | Jan 30, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [b82e78486b](https://linux-hardware.org/?probe=b82e78486b) | Jan 29, 2024 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [c0c78e6476](https://linux-hardware.org/?probe=c0c78e6476) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [50f8982bd3](https://linux-hardware.org/?probe=50f8982bd3) | Jan 28, 2024 |
| Apple         | MacBookPro11,3              | [efdf2169af](https://linux-hardware.org/?probe=efdf2169af) | Jan 27, 2024 |
| Apple         | MacBookPro11,3              | [5859ff1ab1](https://linux-hardware.org/?probe=5859ff1ab1) | Jan 26, 2024 |
| HP            | Pavilion dv6                | [9a15d7d823](https://linux-hardware.org/?probe=9a15d7d823) | Jan 26, 2024 |
| Lenovo        | ThinkPad E420 114155F       | [cdee2fb160](https://linux-hardware.org/?probe=cdee2fb160) | Jan 26, 2024 |
| Acer          | Aspire E1-522               | [a43c97b66c](https://linux-hardware.org/?probe=a43c97b66c) | Jan 26, 2024 |
| HP            | ProBook 650 G2              | [169fd21256](https://linux-hardware.org/?probe=169fd21256) | Jan 25, 2024 |
| Acer          | Swift SF314-43              | [bfbce1457c](https://linux-hardware.org/?probe=bfbce1457c) | Jan 25, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [136eed1999](https://linux-hardware.org/?probe=136eed1999) | Jan 25, 2024 |
| Lenovo        | ThinkPad T470 20HES18S02    | [9f18c011e4](https://linux-hardware.org/?probe=9f18c011e4) | Jan 25, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [057c708875](https://linux-hardware.org/?probe=057c708875) | Jan 24, 2024 |
| ASUSTek       | G750JW                      | [2b196e9839](https://linux-hardware.org/?probe=2b196e9839) | Jan 23, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [ff7b63a668](https://linux-hardware.org/?probe=ff7b63a668) | Jan 23, 2024 |
| Dell          | Latitude E5420              | [8347319849](https://linux-hardware.org/?probe=8347319849) | Jan 23, 2024 |
| HP            | Laptop 15-dy3xxx            | [ddb53329c6](https://linux-hardware.org/?probe=ddb53329c6) | Jan 23, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f37a4265ba](https://linux-hardware.org/?probe=f37a4265ba) | Jan 23, 2024 |
| Lenovo        | ThinkPad X250 20CLS60800    | [37338c49f8](https://linux-hardware.org/?probe=37338c49f8) | Jan 23, 2024 |
| Lenovo        | ThinkPad L480 20LTS8CY00    | [a18fc04450](https://linux-hardware.org/?probe=a18fc04450) | Jan 23, 2024 |
| HP            | Pavilion dv5                | [6fdec1f88a](https://linux-hardware.org/?probe=6fdec1f88a) | Jan 23, 2024 |
| HP            | Elite x2 1012 G1            | [0528733539](https://linux-hardware.org/?probe=0528733539) | Jan 22, 2024 |
| MSI           | GP72 6QF                    | [0cbab5c5f1](https://linux-hardware.org/?probe=0cbab5c5f1) | Jan 21, 2024 |
| Dell          | Precision M4800             | [dccdba8512](https://linux-hardware.org/?probe=dccdba8512) | Jan 21, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [f4d4b6f022](https://linux-hardware.org/?probe=f4d4b6f022) | Jan 21, 2024 |
| Lenovo        | ThinkPad X220 429044U       | [d5fd867450](https://linux-hardware.org/?probe=d5fd867450) | Jan 21, 2024 |
| HP            | Pavilion dv6                | [8e6edcce2d](https://linux-hardware.org/?probe=8e6edcce2d) | Jan 21, 2024 |
| Dell          | Latitude 7440               | [2871324f95](https://linux-hardware.org/?probe=2871324f95) | Jan 19, 2024 |
| Panasonic     | CF-31ATAAX1M                | [f9cc94a1c9](https://linux-hardware.org/?probe=f9cc94a1c9) | Jan 19, 2024 |
| Dell          | Latitude 7440               | [5ff30573ae](https://linux-hardware.org/?probe=5ff30573ae) | Jan 19, 2024 |
| Acer          | Nitro AN515-57              | [e9423fb2cd](https://linux-hardware.org/?probe=e9423fb2cd) | Jan 19, 2024 |
| Acer          | Aspire V3-772G              | [e9bc1c5d68](https://linux-hardware.org/?probe=e9bc1c5d68) | Jan 19, 2024 |
| Acer          | Aspire E5-523               | [02378722b6](https://linux-hardware.org/?probe=02378722b6) | Jan 19, 2024 |
| Lenovo        | ThinkPad X131e 3371AF5      | [1741e3b346](https://linux-hardware.org/?probe=1741e3b346) | Jan 18, 2024 |
| Lenovo        | ThinkPad T490 20N3S8W501    | [399ba4e0e5](https://linux-hardware.org/?probe=399ba4e0e5) | Jan 18, 2024 |
| Apple         | MacBookPro10,2              | [a819ad5cb5](https://linux-hardware.org/?probe=a819ad5cb5) | Jan 18, 2024 |
| MSI           | GF63 Thin 11UC              | [73b96295fe](https://linux-hardware.org/?probe=73b96295fe) | Jan 18, 2024 |
| MSI           | Prestige 13Evo A13M         | [3b3a0ddd43](https://linux-hardware.org/?probe=3b3a0ddd43) | Jan 18, 2024 |
| Panasonic     | CF-52PFN61PM                | [971bbaea1a](https://linux-hardware.org/?probe=971bbaea1a) | Jan 17, 2024 |
| HP            | EliteBook 850 G4            | [df8bb12b29](https://linux-hardware.org/?probe=df8bb12b29) | Jan 17, 2024 |
| Lenovo        | ThinkPad T490 20N3S8W501    | [87e440b878](https://linux-hardware.org/?probe=87e440b878) | Jan 17, 2024 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [7b068dc524](https://linux-hardware.org/?probe=7b068dc524) | Jan 17, 2024 |
| Dell          | XPS 13 9380                 | [15a7a78b43](https://linux-hardware.org/?probe=15a7a78b43) | Jan 16, 2024 |
| Acer          | Aspire E1-522               | [538c5ee96f](https://linux-hardware.org/?probe=538c5ee96f) | Jan 16, 2024 |
| Acer          | Aspire 5810T                | [69c2f12576](https://linux-hardware.org/?probe=69c2f12576) | Jan 16, 2024 |
| Lenovo        | ThinkPad X61 76754BJ        | [42f1380b4e](https://linux-hardware.org/?probe=42f1380b4e) | Jan 15, 2024 |
| Acer          | Swift SF315-52G             | [b1df864ab5](https://linux-hardware.org/?probe=b1df864ab5) | Jan 15, 2024 |
| Unknown       | Unknown                     | [cc6ea90bc9](https://linux-hardware.org/?probe=cc6ea90bc9) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [ff290c247d](https://linux-hardware.org/?probe=ff290c247d) | Jan 15, 2024 |
| ASUSTek       | X550JK                      | [1e70a82b32](https://linux-hardware.org/?probe=1e70a82b32) | Jan 15, 2024 |
| Dell          | Inspiron 3543               | [402af8548c](https://linux-hardware.org/?probe=402af8548c) | Jan 15, 2024 |
| Lenovo        | ThinkPad T430s 2356GUU      | [df4e542b16](https://linux-hardware.org/?probe=df4e542b16) | Jan 15, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [4af392aac3](https://linux-hardware.org/?probe=4af392aac3) | Jan 14, 2024 |
| Samsung       | 700Z3C/700Z5C               | [6055feefa2](https://linux-hardware.org/?probe=6055feefa2) | Jan 14, 2024 |
| HP            | ProBook 4540s               | [6b8cd0306a](https://linux-hardware.org/?probe=6b8cd0306a) | Jan 14, 2024 |
| Lenovo        | ThinkPad A285 20MXS0GT00    | [6fe7454ae4](https://linux-hardware.org/?probe=6fe7454ae4) | Jan 14, 2024 |
| MSI           | GE70 2PE                    | [5f5076a207](https://linux-hardware.org/?probe=5f5076a207) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [19467f2a4d](https://linux-hardware.org/?probe=19467f2a4d) | Jan 14, 2024 |
| Dell          | Precision 5540              | [f29887c5e2](https://linux-hardware.org/?probe=f29887c5e2) | Jan 13, 2024 |
| Framework     | Laptop                      | [ab77469364](https://linux-hardware.org/?probe=ab77469364) | Jan 13, 2024 |
| Samsung       | 300E5M/300E5L               | [23fdab96e1](https://linux-hardware.org/?probe=23fdab96e1) | Jan 13, 2024 |
| Apple         | MacBookPro11,3              | [e47ef53e7f](https://linux-hardware.org/?probe=e47ef53e7f) | Jan 13, 2024 |
| MSI           | MPG Z390 GAMING EDGE AC     | [4fc5db3901](https://linux-hardware.org/?probe=4fc5db3901) | Jan 13, 2024 |
| ASUSTek       | ROG Strix G733ZM_G733ZM     | [e4f7fe0969](https://linux-hardware.org/?probe=e4f7fe0969) | Jan 13, 2024 |
| Acer          | Aspire A315-31              | [22135f150d](https://linux-hardware.org/?probe=22135f150d) | Jan 12, 2024 |
| Dell          | Precision 5770              | [5c8b9a5262](https://linux-hardware.org/?probe=5c8b9a5262) | Jan 11, 2024 |
| ASUSTek       | X550JK                      | [53f8040dbd](https://linux-hardware.org/?probe=53f8040dbd) | Jan 10, 2024 |
| HP            | ProBook 650 G1              | [90b63b0d8a](https://linux-hardware.org/?probe=90b63b0d8a) | Jan 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [48f6f6e2c9](https://linux-hardware.org/?probe=48f6f6e2c9) | Jan 09, 2024 |
| ASUSTek       | K53U                        | [df631caaa2](https://linux-hardware.org/?probe=df631caaa2) | Jan 09, 2024 |
| HP            | Pavilion dv2700             | [957ec4cc30](https://linux-hardware.org/?probe=957ec4cc30) | Jan 09, 2024 |
| HP            | Stream Laptop 11-ah1XX      | [bb9623d23f](https://linux-hardware.org/?probe=bb9623d23f) | Jan 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [86ebfc719f](https://linux-hardware.org/?probe=86ebfc719f) | Jan 08, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [d12278cd24](https://linux-hardware.org/?probe=d12278cd24) | Jan 08, 2024 |
| HP            | Laptop 14                   | [78522b0358](https://linux-hardware.org/?probe=78522b0358) | Jan 07, 2024 |
| Dell          | Latitude E5420              | [40835d5737](https://linux-hardware.org/?probe=40835d5737) | Jan 07, 2024 |
| HP            | ProBook 4540s               | [8549d601f6](https://linux-hardware.org/?probe=8549d601f6) | Jan 07, 2024 |
| Acer          | Aspire E1-570               | [2d9d0b5619](https://linux-hardware.org/?probe=2d9d0b5619) | Jan 07, 2024 |
| HP            | EliteBook 850 G6            | [605ea399c5](https://linux-hardware.org/?probe=605ea399c5) | Jan 07, 2024 |
| Dell          | XPS 15 9570                 | [8ca8b318eb](https://linux-hardware.org/?probe=8ca8b318eb) | Jan 06, 2024 |
| ASUSTek       | ROG Strix G733ZM_G733ZM     | [b753b7e847](https://linux-hardware.org/?probe=b753b7e847) | Jan 06, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [33b192a7d0](https://linux-hardware.org/?probe=33b192a7d0) | Jan 06, 2024 |
| Acer          | Aspire E5-722               | [f037171af4](https://linux-hardware.org/?probe=f037171af4) | Jan 06, 2024 |
| Dell          | Precision 5520              | [1e0e2ac107](https://linux-hardware.org/?probe=1e0e2ac107) | Jan 06, 2024 |
| Apple         | MacBookPro8,3               | [b1467995b6](https://linux-hardware.org/?probe=b1467995b6) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [5fdb8bdac3](https://linux-hardware.org/?probe=5fdb8bdac3) | Jan 06, 2024 |
| Dell          | Precision 5520              | [4ff73a814c](https://linux-hardware.org/?probe=4ff73a814c) | Jan 05, 2024 |
| HP            | Laptop 15-gw0xxx            | [303ecb8cf7](https://linux-hardware.org/?probe=303ecb8cf7) | Jan 05, 2024 |
| HP            | ZBook 14u G5                | [33c5c3bf2c](https://linux-hardware.org/?probe=33c5c3bf2c) | Jan 05, 2024 |
| HP            | ZBook 14u G5                | [7774c1745d](https://linux-hardware.org/?probe=7774c1745d) | Jan 05, 2024 |
| Alienware     | M14xR2                      | [191eeae180](https://linux-hardware.org/?probe=191eeae180) | Jan 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [197d144ab0](https://linux-hardware.org/?probe=197d144ab0) | Jan 03, 2024 |
| Acer          | Aspire 8730                 | [69f291e4be](https://linux-hardware.org/?probe=69f291e4be) | Jan 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [c2be0ba0b8](https://linux-hardware.org/?probe=c2be0ba0b8) | Jan 02, 2024 |
| HP            | Pavilion 13 x360 PC         | [c1d7df8730](https://linux-hardware.org/?probe=c1d7df8730) | Jan 02, 2024 |
| Dell          | Inspiron 5521               | [31f27ced42](https://linux-hardware.org/?probe=31f27ced42) | Jan 02, 2024 |
| Toshiba       | Satellite Pro A50-C         | [2b5c053b26](https://linux-hardware.org/?probe=2b5c053b26) | Jan 02, 2024 |
| Dell          | Inspiron 5570               | [ce562f726a](https://linux-hardware.org/?probe=ce562f726a) | Jan 02, 2024 |
| Acer          | Aspire 8730                 | [a435ff1bd6](https://linux-hardware.org/?probe=a435ff1bd6) | Jan 02, 2024 |
| Acer          | Aspire 8730                 | [4db4a265b6](https://linux-hardware.org/?probe=4db4a265b6) | Jan 02, 2024 |
| Lenovo        | G505 20240                  | [ff10a3ab7d](https://linux-hardware.org/?probe=ff10a3ab7d) | Jan 02, 2024 |
| HP            | ProBook 4540s               | [aaebda14c1](https://linux-hardware.org/?probe=aaebda14c1) | Jan 01, 2024 |
| HP            | EliteBook 850 G4            | [bd25e4866f](https://linux-hardware.org/?probe=bd25e4866f) | Jan 01, 2024 |
| Alienware     | M17xR3                      | [ed05d87c74](https://linux-hardware.org/?probe=ed05d87c74) | Dec 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [577f6b15de](https://linux-hardware.org/?probe=577f6b15de) | Dec 31, 2023 |
| Lenovo        | ThinkPad T61 7662CTO        | [d38807fbbe](https://linux-hardware.org/?probe=d38807fbbe) | Dec 31, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [d694f21feb](https://linux-hardware.org/?probe=d694f21feb) | Dec 31, 2023 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | [0afd47e9fc](https://linux-hardware.org/?probe=0afd47e9fc) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | [70c84eadc0](https://linux-hardware.org/?probe=70c84eadc0) | Dec 31, 2023 |
| Apple         | MacBook6,1                  | [ba4ad2bc18](https://linux-hardware.org/?probe=ba4ad2bc18) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [9c355f1603](https://linux-hardware.org/?probe=9c355f1603) | Dec 31, 2023 |
| Apple         | MacBookPro10,2              | [275f675ca4](https://linux-hardware.org/?probe=275f675ca4) | Dec 31, 2023 |
| Lenovo        | ThinkPad X390 20Q0004VUS    | [4bd6b36cd6](https://linux-hardware.org/?probe=4bd6b36cd6) | Dec 30, 2023 |
| MSI           | Stealth 16Studio A13VF      | [04acb5230d](https://linux-hardware.org/?probe=04acb5230d) | Dec 30, 2023 |
| Apple         | MacBookAir9,1               | [25fea8aab5](https://linux-hardware.org/?probe=25fea8aab5) | Dec 30, 2023 |
| MSI           | Stealth 16Studio A13VF      | [1fd1d2e727](https://linux-hardware.org/?probe=1fd1d2e727) | Dec 30, 2023 |
| Lenovo        | ThinkPad T61 7662CTO        | [9e025b8cde](https://linux-hardware.org/?probe=9e025b8cde) | Dec 30, 2023 |
| Acer          | Aspire A115-31              | [01aeb12545](https://linux-hardware.org/?probe=01aeb12545) | Dec 29, 2023 |
| HP            | Laptop 17t-cn200            | [4c241f7e1d](https://linux-hardware.org/?probe=4c241f7e1d) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [6c5599855c](https://linux-hardware.org/?probe=6c5599855c) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6a99e4eda2](https://linux-hardware.org/?probe=6a99e4eda2) | Dec 29, 2023 |
| Lenovo        | ThinkPad T450 20BUS05V00    | [3334aeb4e1](https://linux-hardware.org/?probe=3334aeb4e1) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [0be6e9ce52](https://linux-hardware.org/?probe=0be6e9ce52) | Dec 29, 2023 |
| HP            | ProBook 650 G2              | [1dd3970627](https://linux-hardware.org/?probe=1dd3970627) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [d6477c7999](https://linux-hardware.org/?probe=d6477c7999) | Dec 28, 2023 |
| Acer          | Aspire 8730                 | [3110584890](https://linux-hardware.org/?probe=3110584890) | Dec 28, 2023 |
| Acer          | Aspire 8730                 | [3a9461e870](https://linux-hardware.org/?probe=3a9461e870) | Dec 28, 2023 |
| Acer          | Aspire A315-41              | [1042d42263](https://linux-hardware.org/?probe=1042d42263) | Dec 28, 2023 |
| Dell          | Inspiron 7720               | [965fc7c4a3](https://linux-hardware.org/?probe=965fc7c4a3) | Dec 28, 2023 |
| Acer          | Aspire A315-41              | [d68aa800c6](https://linux-hardware.org/?probe=d68aa800c6) | Dec 28, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [3a0b2d2a21](https://linux-hardware.org/?probe=3a0b2d2a21) | Dec 28, 2023 |
| Razer         | Blade                       | [bd2101718d](https://linux-hardware.org/?probe=bd2101718d) | Dec 28, 2023 |
| Apple         | MacBookAir9,1               | [13a55dee9a](https://linux-hardware.org/?probe=13a55dee9a) | Dec 27, 2023 |
| Gigabyte      | AERO 15-X9                  | [906642b6ec](https://linux-hardware.org/?probe=906642b6ec) | Dec 27, 2023 |
| Google        | Swanky                      | [12fd273db1](https://linux-hardware.org/?probe=12fd273db1) | Dec 27, 2023 |
| Alienware     | m16 R1 AMD                  | [98aaf575cc](https://linux-hardware.org/?probe=98aaf575cc) | Dec 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [b000376310](https://linux-hardware.org/?probe=b000376310) | Dec 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ff3773b480](https://linux-hardware.org/?probe=ff3773b480) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [c38f5ee95e](https://linux-hardware.org/?probe=c38f5ee95e) | Dec 25, 2023 |
| Unknown       | Unknown                     | [a9015bc697](https://linux-hardware.org/?probe=a9015bc697) | Dec 25, 2023 |
| Lenovo        | ThinkPad T540p 20BFS0620... | [5cceadde0c](https://linux-hardware.org/?probe=5cceadde0c) | Dec 25, 2023 |
| Unknown       | Apple MacBook Air (13-in... | [1954e2b6a8](https://linux-hardware.org/?probe=1954e2b6a8) | Dec 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [c0ff23eba6](https://linux-hardware.org/?probe=c0ff23eba6) | Dec 24, 2023 |
| HP            | Elite x2 1012 G1            | [b093087b3c](https://linux-hardware.org/?probe=b093087b3c) | Dec 23, 2023 |
| Unknown       | Unknown                     | [a0d7edc452](https://linux-hardware.org/?probe=a0d7edc452) | Dec 23, 2023 |
| HP            | Elite x2 1012 G1            | [c93fffc388](https://linux-hardware.org/?probe=c93fffc388) | Dec 23, 2023 |
| Acer          | Aspire A515-55              | [9412d138fb](https://linux-hardware.org/?probe=9412d138fb) | Dec 23, 2023 |
| Acer          | Aspire A515-55              | [4166459262](https://linux-hardware.org/?probe=4166459262) | Dec 23, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [201d4ed37f](https://linux-hardware.org/?probe=201d4ed37f) | Dec 23, 2023 |
| Acer          | Aspire R3-131T              | [647b2fddf6](https://linux-hardware.org/?probe=647b2fddf6) | Dec 23, 2023 |
| Dell          | Latitude 5420               | [9858586a84](https://linux-hardware.org/?probe=9858586a84) | Dec 22, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [b09c4dd8a2](https://linux-hardware.org/?probe=b09c4dd8a2) | Dec 22, 2023 |
| HP            | Pavilion g6                 | [ebdf3d244f](https://linux-hardware.org/?probe=ebdf3d244f) | Dec 22, 2023 |
| HP            | Pavilion g6                 | [b62f9f41d3](https://linux-hardware.org/?probe=b62f9f41d3) | Dec 22, 2023 |
| Dell          | Latitude 7420               | [f2b2511de1](https://linux-hardware.org/?probe=f2b2511de1) | Dec 21, 2023 |
| Valve         | Jupiter                     | [6003cb709f](https://linux-hardware.org/?probe=6003cb709f) | Dec 21, 2023 |
| Valve         | Jupiter                     | [186428f160](https://linux-hardware.org/?probe=186428f160) | Dec 21, 2023 |
| Google        | Casta                       | [70f6e5e978](https://linux-hardware.org/?probe=70f6e5e978) | Dec 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [faabc05597](https://linux-hardware.org/?probe=faabc05597) | Dec 21, 2023 |
| Lenovo        | ThinkPad T520 42404AU       | [2b29070879](https://linux-hardware.org/?probe=2b29070879) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [54ed87ec87](https://linux-hardware.org/?probe=54ed87ec87) | Dec 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3SW0... | [eebb86b95f](https://linux-hardware.org/?probe=eebb86b95f) | Dec 19, 2023 |
| Acer          | Aspire AV15-52              | [daf4aa326d](https://linux-hardware.org/?probe=daf4aa326d) | Dec 19, 2023 |
| MSI           | Pulse 17 B13VGK             | [71d0660568](https://linux-hardware.org/?probe=71d0660568) | Dec 18, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [e94e9e0fd9](https://linux-hardware.org/?probe=e94e9e0fd9) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [f47c731a09](https://linux-hardware.org/?probe=f47c731a09) | Dec 18, 2023 |
| Acer          | Aspire 8730                 | [c7b60bcb33](https://linux-hardware.org/?probe=c7b60bcb33) | Dec 18, 2023 |
| Gateway       | NV54 Series                 | [1bd87c77d2](https://linux-hardware.org/?probe=1bd87c77d2) | Dec 18, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [f46bf3981f](https://linux-hardware.org/?probe=f46bf3981f) | Dec 18, 2023 |
| Unknown       | Unknown                     | [81187bebc0](https://linux-hardware.org/?probe=81187bebc0) | Dec 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [709891824c](https://linux-hardware.org/?probe=709891824c) | Dec 18, 2023 |
| MSI           | Vector GP77 13VG            | [7b6b5a14f8](https://linux-hardware.org/?probe=7b6b5a14f8) | Dec 18, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [e7ed0c7c8a](https://linux-hardware.org/?probe=e7ed0c7c8a) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [fd17674af7](https://linux-hardware.org/?probe=fd17674af7) | Dec 17, 2023 |
| MSI           | Cyborg 15 A12VF             | [af666cc67d](https://linux-hardware.org/?probe=af666cc67d) | Dec 17, 2023 |
| Acer          | Aspire 4736Z                | [38866fae79](https://linux-hardware.org/?probe=38866fae79) | Dec 17, 2023 |
| MSI           | Vector GP77 13VG            | [267679e074](https://linux-hardware.org/?probe=267679e074) | Dec 17, 2023 |
| Dell          | Precision 5510              | [d723f4a031](https://linux-hardware.org/?probe=d723f4a031) | Dec 17, 2023 |
| Dell          | Latitude E6440              | [b91055b95e](https://linux-hardware.org/?probe=b91055b95e) | Dec 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0018284858](https://linux-hardware.org/?probe=0018284858) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [e0fa989ed0](https://linux-hardware.org/?probe=e0fa989ed0) | Dec 17, 2023 |
| Alienware     | m18 R1                      | [a136406723](https://linux-hardware.org/?probe=a136406723) | Dec 16, 2023 |
| Toshiba       | TECRA Z50-A                 | [8717000b31](https://linux-hardware.org/?probe=8717000b31) | Dec 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [f65efa02b6](https://linux-hardware.org/?probe=f65efa02b6) | Dec 16, 2023 |
| HP            | Compaq Presario A900        | [cafb584a35](https://linux-hardware.org/?probe=cafb584a35) | Dec 16, 2023 |
| Dell          | Latitude E7240              | [8fc0b7d8ea](https://linux-hardware.org/?probe=8fc0b7d8ea) | Dec 16, 2023 |
| Dell          | Latitude E6440              | [bfbadf07a9](https://linux-hardware.org/?probe=bfbadf07a9) | Dec 16, 2023 |
| Dell          | Latitude E6440              | [bde33cad70](https://linux-hardware.org/?probe=bde33cad70) | Dec 16, 2023 |
| Dell          | Latitude E6440              | [5d02de18b4](https://linux-hardware.org/?probe=5d02de18b4) | Dec 16, 2023 |
| Acer          | Aspire 8730                 | [5f7e5fbfd8](https://linux-hardware.org/?probe=5f7e5fbfd8) | Dec 15, 2023 |
| Acer          | Aspire 8730                 | [8e1f3c1aa9](https://linux-hardware.org/?probe=8e1f3c1aa9) | Dec 15, 2023 |
| Valve         | Jupiter                     | [bef7a2d5b3](https://linux-hardware.org/?probe=bef7a2d5b3) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [d8db62d461](https://linux-hardware.org/?probe=d8db62d461) | Dec 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [3d4b7d5e8b](https://linux-hardware.org/?probe=3d4b7d5e8b) | Dec 15, 2023 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [a0eaa74105](https://linux-hardware.org/?probe=a0eaa74105) | Dec 15, 2023 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [db4a7dea97](https://linux-hardware.org/?probe=db4a7dea97) | Dec 15, 2023 |
| Gigabyte      | AERO 15 KD                  | [ef9cf1d767](https://linux-hardware.org/?probe=ef9cf1d767) | Dec 15, 2023 |
| Dell          | Precision 5540              | [beae57f4bb](https://linux-hardware.org/?probe=beae57f4bb) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3SW0... | [990fd9f312](https://linux-hardware.org/?probe=990fd9f312) | Dec 14, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [2b65b49ba3](https://linux-hardware.org/?probe=2b65b49ba3) | Dec 14, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [309aea6480](https://linux-hardware.org/?probe=309aea6480) | Dec 14, 2023 |
| Toshiba       | PORTEGE R930                | [e341599417](https://linux-hardware.org/?probe=e341599417) | Dec 14, 2023 |
| HP            | Laptop 17t-cn200            | [ffe76142c0](https://linux-hardware.org/?probe=ffe76142c0) | Dec 14, 2023 |
| Dell          | Inspiron 5584               | [525d98e3f0](https://linux-hardware.org/?probe=525d98e3f0) | Dec 13, 2023 |
| Valve         | Jupiter                     | [75070d8783](https://linux-hardware.org/?probe=75070d8783) | Dec 12, 2023 |
| Dell          | Vostro 1320                 | [cf44765cd0](https://linux-hardware.org/?probe=cf44765cd0) | Dec 11, 2023 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [048ee8c70a](https://linux-hardware.org/?probe=048ee8c70a) | Dec 11, 2023 |
| Apple         | MacBookPro9,2               | [6e230c56bf](https://linux-hardware.org/?probe=6e230c56bf) | Dec 11, 2023 |
| HP            | ProBook 4540s               | [187b090bc8](https://linux-hardware.org/?probe=187b090bc8) | Dec 11, 2023 |
| Unknown       | Unknown                     | [e70fd6bdb5](https://linux-hardware.org/?probe=e70fd6bdb5) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | [832dd09409](https://linux-hardware.org/?probe=832dd09409) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | [b17b809ccf](https://linux-hardware.org/?probe=b17b809ccf) | Dec 10, 2023 |
| Dell          | XPS 15 9500                 | [5910eefbd0](https://linux-hardware.org/?probe=5910eefbd0) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [324e195003](https://linux-hardware.org/?probe=324e195003) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f60e90cfd0](https://linux-hardware.org/?probe=f60e90cfd0) | Dec 10, 2023 |
| ASUSTek       | X550JK                      | [06e9cf1c8d](https://linux-hardware.org/?probe=06e9cf1c8d) | Dec 10, 2023 |
| HP            | Laptop 14-fq1xxx            | [ef158cd28b](https://linux-hardware.org/?probe=ef158cd28b) | Dec 09, 2023 |
| HP            | G61                         | [ce104b5b73](https://linux-hardware.org/?probe=ce104b5b73) | Dec 09, 2023 |
| Toshiba       | Satellite L650D             | [90ec46f444](https://linux-hardware.org/?probe=90ec46f444) | Dec 09, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [b743ce445f](https://linux-hardware.org/?probe=b743ce445f) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ec6f114cca](https://linux-hardware.org/?probe=ec6f114cca) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | [b53080f09f](https://linux-hardware.org/?probe=b53080f09f) | Dec 08, 2023 |
| Toshiba       | Satellite S50D-A            | [eaa6d2bf5e](https://linux-hardware.org/?probe=eaa6d2bf5e) | Dec 07, 2023 |
| Toshiba       | Satellite S50D-A            | [749ddd65d7](https://linux-hardware.org/?probe=749ddd65d7) | Dec 07, 2023 |
| Dell          | Latitude 7400               | [692f8c13ff](https://linux-hardware.org/?probe=692f8c13ff) | Dec 07, 2023 |
| Alienware     | m18 R1                      | [79c8580eb9](https://linux-hardware.org/?probe=79c8580eb9) | Dec 07, 2023 |
| HP            | ProBook 4540s               | [c1b70f6050](https://linux-hardware.org/?probe=c1b70f6050) | Dec 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444C... | [04bbb5a104](https://linux-hardware.org/?probe=04bbb5a104) | Dec 07, 2023 |
| Valve         | Jupiter                     | [7eec257dd6](https://linux-hardware.org/?probe=7eec257dd6) | Dec 07, 2023 |
| Acer          | Swift SF314-54              | [cfc6e89dca](https://linux-hardware.org/?probe=cfc6e89dca) | Dec 07, 2023 |
| Valve         | Galileo                     | [20b7e72741](https://linux-hardware.org/?probe=20b7e72741) | Dec 06, 2023 |
| Alienware     | m18 R1                      | [4a4c2cec97](https://linux-hardware.org/?probe=4a4c2cec97) | Dec 06, 2023 |
| Dell          | XPS 13 9380                 | [e0f4aeb360](https://linux-hardware.org/?probe=e0f4aeb360) | Dec 06, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | [65ec6660cc](https://linux-hardware.org/?probe=65ec6660cc) | Dec 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0cb29ce493](https://linux-hardware.org/?probe=0cb29ce493) | Dec 05, 2023 |
| Apple         | MacBookPro9,2               | [f665409b48](https://linux-hardware.org/?probe=f665409b48) | Dec 05, 2023 |
| Lenovo        | ThinkPad X390 20Q1S1WB00    | [ab1ae6521e](https://linux-hardware.org/?probe=ab1ae6521e) | Dec 05, 2023 |
| HP            | EliteBook 840 G1            | [1b39d673f8](https://linux-hardware.org/?probe=1b39d673f8) | Dec 05, 2023 |
| Acer          | TravelMate B311-31          | [9611377d0c](https://linux-hardware.org/?probe=9611377d0c) | Dec 05, 2023 |
| ASUSTek       | ROG Strix G614JU_G614JU     | [68ec81b134](https://linux-hardware.org/?probe=68ec81b134) | Dec 04, 2023 |
| HP            | Spectre Notebook            | [95b8230b80](https://linux-hardware.org/?probe=95b8230b80) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [de877c77b2](https://linux-hardware.org/?probe=de877c77b2) | Dec 04, 2023 |
| MSI           | Thin GF63 12VE              | [ada68f6d8a](https://linux-hardware.org/?probe=ada68f6d8a) | Dec 04, 2023 |
| MSI           | GF65 Thin 10SER             | [f382271478](https://linux-hardware.org/?probe=f382271478) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [23cf3c751a](https://linux-hardware.org/?probe=23cf3c751a) | Dec 04, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [890efb3114](https://linux-hardware.org/?probe=890efb3114) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [22b736c30d](https://linux-hardware.org/?probe=22b736c30d) | Dec 04, 2023 |
| Valve         | Galileo                     | [1760875677](https://linux-hardware.org/?probe=1760875677) | Dec 04, 2023 |
| HP            | ProBook 650 G2              | [16cd39b5e2](https://linux-hardware.org/?probe=16cd39b5e2) | Dec 04, 2023 |
| HP            | Victus by Gaming Laptop ... | [44542d3f3a](https://linux-hardware.org/?probe=44542d3f3a) | Dec 04, 2023 |
| HP            | ZBook 15 G3                 | [db4ce11de0](https://linux-hardware.org/?probe=db4ce11de0) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [1af4b60513](https://linux-hardware.org/?probe=1af4b60513) | Dec 03, 2023 |
| Acer          | Aspire 4736Z                | [844b16d408](https://linux-hardware.org/?probe=844b16d408) | Dec 03, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [1b6b67ba62](https://linux-hardware.org/?probe=1b6b67ba62) | Dec 03, 2023 |
| Unknown       | Unknown                     | [ecc015c709](https://linux-hardware.org/?probe=ecc015c709) | Dec 03, 2023 |
| Dell          | Precision 5540              | [b347a82e85](https://linux-hardware.org/?probe=b347a82e85) | Dec 02, 2023 |
| Unknown       | Unknown                     | [112dd093ba](https://linux-hardware.org/?probe=112dd093ba) | Dec 02, 2023 |
| HP            | Victus by Gaming Laptop ... | [e9e9db4763](https://linux-hardware.org/?probe=e9e9db4763) | Dec 02, 2023 |
| HP            | ZBook 15 G3                 | [c9b71f256a](https://linux-hardware.org/?probe=c9b71f256a) | Dec 02, 2023 |
| Acer          | Predator PH317-52           | [013bd43bc7](https://linux-hardware.org/?probe=013bd43bc7) | Dec 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [6ece5a0c44](https://linux-hardware.org/?probe=6ece5a0c44) | Dec 01, 2023 |
| ASUSTek       | X555QA                      | [0b156341f6](https://linux-hardware.org/?probe=0b156341f6) | Dec 01, 2023 |
| Acer          | Predator PH317-52           | [abb14dcedb](https://linux-hardware.org/?probe=abb14dcedb) | Dec 01, 2023 |
| ASUSTek       | X555LAB                     | [b60a0a3ed7](https://linux-hardware.org/?probe=b60a0a3ed7) | Dec 01, 2023 |
| ASUSTek       | T100HAN                     | [8ffd531af0](https://linux-hardware.org/?probe=8ffd531af0) | Dec 01, 2023 |
| HP            | ProBook 650 G2              | [ce6f82a6b0](https://linux-hardware.org/?probe=ce6f82a6b0) | Nov 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8SA3Q0... | [94a4aacf4f](https://linux-hardware.org/?probe=94a4aacf4f) | Nov 29, 2023 |
| Dell          | Precision 3550              | [935b0dba56](https://linux-hardware.org/?probe=935b0dba56) | Nov 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [b01d99f799](https://linux-hardware.org/?probe=b01d99f799) | Nov 28, 2023 |
| Apple         | MacBookPro11,1              | [e8fadc04f4](https://linux-hardware.org/?probe=e8fadc04f4) | Nov 28, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [62b0e92532](https://linux-hardware.org/?probe=62b0e92532) | Nov 28, 2023 |
| Dell          | Latitude E6520              | [a03b74a3d3](https://linux-hardware.org/?probe=a03b74a3d3) | Nov 28, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [93d9d89a9a](https://linux-hardware.org/?probe=93d9d89a9a) | Nov 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [3fe11b3243](https://linux-hardware.org/?probe=3fe11b3243) | Nov 27, 2023 |
| MSI           | GP60 2QE                    | [f45ab6d514](https://linux-hardware.org/?probe=f45ab6d514) | Nov 27, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [abbb97fea2](https://linux-hardware.org/?probe=abbb97fea2) | Nov 27, 2023 |
| Acer          | Nitro AN515-53              | [0a47341bcf](https://linux-hardware.org/?probe=0a47341bcf) | Nov 27, 2023 |
| HP            | Laptop 15-dy5xxx            | [4169d58764](https://linux-hardware.org/?probe=4169d58764) | Nov 27, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [9f8aab70f1](https://linux-hardware.org/?probe=9f8aab70f1) | Nov 27, 2023 |
| Dell          | Latitude 5590               | [cd823db120](https://linux-hardware.org/?probe=cd823db120) | Nov 26, 2023 |
| HP            | Notebook                    | [d13874e201](https://linux-hardware.org/?probe=d13874e201) | Nov 26, 2023 |
| HP            | Pavilion dv7                | [c617d0a2d4](https://linux-hardware.org/?probe=c617d0a2d4) | Nov 26, 2023 |
| HP            | Notebook                    | [6d348c3a7a](https://linux-hardware.org/?probe=6d348c3a7a) | Nov 26, 2023 |
| HP            | Laptop 14-dk1xxx            | [eb3634e98f](https://linux-hardware.org/?probe=eb3634e98f) | Nov 26, 2023 |
| Toshiba       | Satellite L300D             | [5910ef90fd](https://linux-hardware.org/?probe=5910ef90fd) | Nov 26, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [1e704edcd6](https://linux-hardware.org/?probe=1e704edcd6) | Nov 26, 2023 |
| Valve         | Jupiter                     | [7f42b09854](https://linux-hardware.org/?probe=7f42b09854) | Nov 26, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | [1106c092a2](https://linux-hardware.org/?probe=1106c092a2) | Nov 26, 2023 |
| Panasonic     | CF-53JALZY1M                | [e90faa0f97](https://linux-hardware.org/?probe=e90faa0f97) | Nov 26, 2023 |
| Apple         | MacBookPro9,2               | [ab9cf7394e](https://linux-hardware.org/?probe=ab9cf7394e) | Nov 25, 2023 |
| Lenovo        | ThinkPad T470p 20J6000TA... | [0bccb463ab](https://linux-hardware.org/?probe=0bccb463ab) | Nov 25, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [6c397edda9](https://linux-hardware.org/?probe=6c397edda9) | Nov 25, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [cc4ce2ca20](https://linux-hardware.org/?probe=cc4ce2ca20) | Nov 25, 2023 |
| Google        | Droid                       | [b04324334b](https://linux-hardware.org/?probe=b04324334b) | Nov 24, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [2a29f65958](https://linux-hardware.org/?probe=2a29f65958) | Nov 24, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [1dea02682f](https://linux-hardware.org/?probe=1dea02682f) | Nov 24, 2023 |
| MSI           | GF65 Thin 10UE              | [1eb750acac](https://linux-hardware.org/?probe=1eb750acac) | Nov 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2e2bb5865d](https://linux-hardware.org/?probe=2e2bb5865d) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [be47adc197](https://linux-hardware.org/?probe=be47adc197) | Nov 23, 2023 |
| Unknown       | Unknown                     | [de65da2f94](https://linux-hardware.org/?probe=de65da2f94) | Nov 23, 2023 |
| Unknown       | Unknown                     | [0c65e69853](https://linux-hardware.org/?probe=0c65e69853) | Nov 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c4d2e974ae](https://linux-hardware.org/?probe=c4d2e974ae) | Nov 23, 2023 |
| Acer          | Aspire 5733                 | [7b6e215012](https://linux-hardware.org/?probe=7b6e215012) | Nov 22, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [1862966cbe](https://linux-hardware.org/?probe=1862966cbe) | Nov 22, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [9f4829b792](https://linux-hardware.org/?probe=9f4829b792) | Nov 22, 2023 |
| Dell          | Latitude 7480               | [e6a9139a06](https://linux-hardware.org/?probe=e6a9139a06) | Nov 22, 2023 |
| Dell          | Latitude E6400              | [adb43d89ab](https://linux-hardware.org/?probe=adb43d89ab) | Nov 22, 2023 |
| Dell          | Latitude 7480               | [9cc316e781](https://linux-hardware.org/?probe=9cc316e781) | Nov 22, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [5f281a926a](https://linux-hardware.org/?probe=5f281a926a) | Nov 22, 2023 |
| Acer          | Aspire One 721              | [e50838c5ff](https://linux-hardware.org/?probe=e50838c5ff) | Nov 22, 2023 |
| Dell          | Latitude E6540              | [6fe2a2a1dd](https://linux-hardware.org/?probe=6fe2a2a1dd) | Nov 22, 2023 |
| Dell          | Latitude E6400              | [96e98f8c80](https://linux-hardware.org/?probe=96e98f8c80) | Nov 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [3b815bebf3](https://linux-hardware.org/?probe=3b815bebf3) | Nov 21, 2023 |
| Lenovo        | ThinkPad T500 20552CU       | [7389e9e37c](https://linux-hardware.org/?probe=7389e9e37c) | Nov 21, 2023 |
| Acer          | Aspire 5733                 | [348094cd98](https://linux-hardware.org/?probe=348094cd98) | Nov 21, 2023 |
| Apple         | MacBookPro14,3              | [3664fc3164](https://linux-hardware.org/?probe=3664fc3164) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2b84d65d1a](https://linux-hardware.org/?probe=2b84d65d1a) | Nov 20, 2023 |
| Lenovo        | ThinkPad X230 2320JPU       | [10e0d2e090](https://linux-hardware.org/?probe=10e0d2e090) | Nov 20, 2023 |
| Apple         | MacBookAir6,2               | [9274d4e825](https://linux-hardware.org/?probe=9274d4e825) | Nov 20, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [7183e48f52](https://linux-hardware.org/?probe=7183e48f52) | Nov 20, 2023 |
| Toshiba       | Satellite L755              | [9392b89fe2](https://linux-hardware.org/?probe=9392b89fe2) | Nov 20, 2023 |
| Toshiba       | Satellite L755              | [e2c96d8a97](https://linux-hardware.org/?probe=e2c96d8a97) | Nov 20, 2023 |
| HP            | ZBook Firefly 16 inch G1... | [e27aa36a0d](https://linux-hardware.org/?probe=e27aa36a0d) | Nov 19, 2023 |
| HP            | Laptop 15-ef3xxx            | [196040012f](https://linux-hardware.org/?probe=196040012f) | Nov 18, 2023 |
| HP            | ProBook 5330m               | [80cf29bda5](https://linux-hardware.org/?probe=80cf29bda5) | Nov 18, 2023 |
| HP            | ProBook 5330m               | [6a176f629c](https://linux-hardware.org/?probe=6a176f629c) | Nov 18, 2023 |
| HP            | Pavilion dv7                | [4c482baa30](https://linux-hardware.org/?probe=4c482baa30) | Nov 18, 2023 |
| HP            | Pavilion dv7                | [e05cf328e2](https://linux-hardware.org/?probe=e05cf328e2) | Nov 18, 2023 |
| Dell          | Latitude E6230              | [2a2d7c242e](https://linux-hardware.org/?probe=2a2d7c242e) | Nov 18, 2023 |
| Dell          | XPS 13 7390                 | [4735287055](https://linux-hardware.org/?probe=4735287055) | Nov 18, 2023 |
| HP            | Laptop 15-ef3xxx            | [e20df9a48a](https://linux-hardware.org/?probe=e20df9a48a) | Nov 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [a8dd03176b](https://linux-hardware.org/?probe=a8dd03176b) | Nov 16, 2023 |
| Dell          | XPS 15 9510                 | [8414c926f0](https://linux-hardware.org/?probe=8414c926f0) | Nov 16, 2023 |
| HP            | Pavilion g7                 | [9f8b6f3432](https://linux-hardware.org/?probe=9f8b6f3432) | Nov 16, 2023 |
| HP            | Pavilion g7                 | [0c4816a4f2](https://linux-hardware.org/?probe=0c4816a4f2) | Nov 16, 2023 |
| Acer          | Aspire E5-553               | [a8349dda46](https://linux-hardware.org/?probe=a8349dda46) | Nov 16, 2023 |
| Dell          | XPS 13 9360                 | [e0bc805f38](https://linux-hardware.org/?probe=e0bc805f38) | Nov 16, 2023 |
| Dell          | Latitude E6440              | [a0a06323e0](https://linux-hardware.org/?probe=a0a06323e0) | Nov 16, 2023 |
| MSI           | GF65 Thin 10UE              | [04d65c8c40](https://linux-hardware.org/?probe=04d65c8c40) | Nov 15, 2023 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [455efd5541](https://linux-hardware.org/?probe=455efd5541) | Nov 15, 2023 |
| Acer          | Aspire AV15-52              | [0eb415a325](https://linux-hardware.org/?probe=0eb415a325) | Nov 15, 2023 |
| Dell          | Latitude E6540              | [6ee01afb58](https://linux-hardware.org/?probe=6ee01afb58) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [98dd1a4a4f](https://linux-hardware.org/?probe=98dd1a4a4f) | Nov 15, 2023 |
| Google        | Nami                        | [53f0d03d36](https://linux-hardware.org/?probe=53f0d03d36) | Nov 15, 2023 |
| Dell          | Precision 5540              | [dd020f9dbe](https://linux-hardware.org/?probe=dd020f9dbe) | Nov 14, 2023 |
| Dell          | Precision 5540              | [a809cf8ae4](https://linux-hardware.org/?probe=a809cf8ae4) | Nov 14, 2023 |
| Intel Clie... | LAPRC710                    | [75dbf98926](https://linux-hardware.org/?probe=75dbf98926) | Nov 14, 2023 |
| HP            | Pavilion Notebook           | [1b2ee4df88](https://linux-hardware.org/?probe=1b2ee4df88) | Nov 13, 2023 |
| Valve         | Jupiter                     | [638956d8a1](https://linux-hardware.org/?probe=638956d8a1) | Nov 13, 2023 |
| Dell          | Vostro 3480                 | [4eae719332](https://linux-hardware.org/?probe=4eae719332) | Nov 13, 2023 |
| Dell          | Latitude E6430              | [ac45698de6](https://linux-hardware.org/?probe=ac45698de6) | Nov 13, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [b65b59b050](https://linux-hardware.org/?probe=b65b59b050) | Nov 13, 2023 |
| HP            | EliteBook 8440p             | [f3be98d9fc](https://linux-hardware.org/?probe=f3be98d9fc) | Nov 12, 2023 |
| HP            | Laptop 14-cf0xxx            | [ff911a411f](https://linux-hardware.org/?probe=ff911a411f) | Nov 12, 2023 |
| Google        | Edgar                       | [838bd73737](https://linux-hardware.org/?probe=838bd73737) | Nov 12, 2023 |
| HP            | Pavilion dv9500             | [1cbc855f91](https://linux-hardware.org/?probe=1cbc855f91) | Nov 12, 2023 |
| Google        | Edgar                       | [42f8059f62](https://linux-hardware.org/?probe=42f8059f62) | Nov 11, 2023 |
| Gateway       | NV57H                       | [e5f084f72c](https://linux-hardware.org/?probe=e5f084f72c) | Nov 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ccbd44cb8b](https://linux-hardware.org/?probe=ccbd44cb8b) | Nov 11, 2023 |
| Dell          | Latitude E5420              | [ac31e56717](https://linux-hardware.org/?probe=ac31e56717) | Nov 11, 2023 |
| HP            | ProBook 650 G2              | [c4fc402545](https://linux-hardware.org/?probe=c4fc402545) | Nov 11, 2023 |
| HP            | ProBook 650 G2              | [0523c4d3fd](https://linux-hardware.org/?probe=0523c4d3fd) | Nov 11, 2023 |
| ASUSTek       | X555QA                      | [8775266ad7](https://linux-hardware.org/?probe=8775266ad7) | Nov 10, 2023 |
| Dell          | XPS 13 9370                 | [dadc0b1102](https://linux-hardware.org/?probe=dadc0b1102) | Nov 10, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [80062f7576](https://linux-hardware.org/?probe=80062f7576) | Nov 09, 2023 |
| Lenovo        | ThinkPad T430s 23553J2      | [d035513169](https://linux-hardware.org/?probe=d035513169) | Nov 09, 2023 |
| HP            | Pavilion Notebook           | [c8c4c09226](https://linux-hardware.org/?probe=c8c4c09226) | Nov 08, 2023 |
| Acer          | Aspire 5732Z                | [7bd71c0cfe](https://linux-hardware.org/?probe=7bd71c0cfe) | Nov 08, 2023 |
| Acer          | Aspire 5732Z                | [18ea83581a](https://linux-hardware.org/?probe=18ea83581a) | Nov 08, 2023 |
| Valve         | Jupiter                     | [848dfcb217](https://linux-hardware.org/?probe=848dfcb217) | Nov 08, 2023 |
| HP            | G61                         | [65f7664fe3](https://linux-hardware.org/?probe=65f7664fe3) | Nov 06, 2023 |
| Valve         | Jupiter                     | [aef9c84cf7](https://linux-hardware.org/?probe=aef9c84cf7) | Nov 06, 2023 |
| Valve         | Jupiter                     | [d8ac880948](https://linux-hardware.org/?probe=d8ac880948) | Nov 06, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [ad7dc81954](https://linux-hardware.org/?probe=ad7dc81954) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [290be8911e](https://linux-hardware.org/?probe=290be8911e) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| Acer          | AO532h                      | [0b3d66b04a](https://linux-hardware.org/?probe=0b3d66b04a) | Nov 04, 2023 |
| HP            | EliteBook 840 G4            | [5abff2e87a](https://linux-hardware.org/?probe=5abff2e87a) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1bdfa38b3e](https://linux-hardware.org/?probe=1bdfa38b3e) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [94cdd979b2](https://linux-hardware.org/?probe=94cdd979b2) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [5149df3a58](https://linux-hardware.org/?probe=5149df3a58) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [3c92af97b9](https://linux-hardware.org/?probe=3c92af97b9) | Nov 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [99992393e4](https://linux-hardware.org/?probe=99992393e4) | Nov 01, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [11c06a97d7](https://linux-hardware.org/?probe=11c06a97d7) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [8a2a3561ab](https://linux-hardware.org/?probe=8a2a3561ab) | Nov 01, 2023 |
| Apple         | MacBookPro8,1               | [0ea1a71a53](https://linux-hardware.org/?probe=0ea1a71a53) | Oct 31, 2023 |
| Lenovo        | ThinkPad T440 20B7S03Q00    | [de24032ac7](https://linux-hardware.org/?probe=de24032ac7) | Oct 30, 2023 |
| Dell          | Latitude 5490               | [63f4fce332](https://linux-hardware.org/?probe=63f4fce332) | Oct 30, 2023 |
| Acer          | Nitro AN515-55              | [0325d9a6e8](https://linux-hardware.org/?probe=0325d9a6e8) | Oct 30, 2023 |
| Acer          | Nitro AN515-55              | [80e9a059c1](https://linux-hardware.org/?probe=80e9a059c1) | Oct 29, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [bf9ff8ba5b](https://linux-hardware.org/?probe=bf9ff8ba5b) | Oct 29, 2023 |
| System76      | Gazelle                     | [3bc4a66a13](https://linux-hardware.org/?probe=3bc4a66a13) | Oct 29, 2023 |
| Acer          | Aspire A315-21              | [7f9b48f63b](https://linux-hardware.org/?probe=7f9b48f63b) | Oct 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [22380583c4](https://linux-hardware.org/?probe=22380583c4) | Oct 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b83a355a39](https://linux-hardware.org/?probe=b83a355a39) | Oct 28, 2023 |
| HUAWEI        | MACHD-WXX9                  | [551a5c8aa2](https://linux-hardware.org/?probe=551a5c8aa2) | Oct 28, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4468cb093d](https://linux-hardware.org/?probe=4468cb093d) | Oct 28, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [c0aef363fa](https://linux-hardware.org/?probe=c0aef363fa) | Oct 28, 2023 |
| Dell          | Latitude E6520              | [dbbca588de](https://linux-hardware.org/?probe=dbbca588de) | Oct 26, 2023 |
| HP            | Laptop 15-da0xxx            | [6c18f4a4ef](https://linux-hardware.org/?probe=6c18f4a4ef) | Oct 25, 2023 |
| ASUSTek       | ZenBook UX434FL             | [139d1a74ed](https://linux-hardware.org/?probe=139d1a74ed) | Oct 25, 2023 |
| Matsushita... | CF-30CTWAZBM                | [4211783dac](https://linux-hardware.org/?probe=4211783dac) | Oct 25, 2023 |
| Dell          | Latitude E6420              | [54c82901c0](https://linux-hardware.org/?probe=54c82901c0) | Oct 25, 2023 |
| Lenovo        | ThinkPad P52 20MAS0WG00     | [e7e16a6ac8](https://linux-hardware.org/?probe=e7e16a6ac8) | Oct 25, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [7476940ad0](https://linux-hardware.org/?probe=7476940ad0) | Oct 25, 2023 |
| Toshiba       | Satellite L655              | [504b65f326](https://linux-hardware.org/?probe=504b65f326) | Oct 25, 2023 |
| Toshiba       | Satellite L655              | [6f1c644900](https://linux-hardware.org/?probe=6f1c644900) | Oct 25, 2023 |
| HP            | Victus by Laptop PC         | [53988c0c73](https://linux-hardware.org/?probe=53988c0c73) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | [84883d560d](https://linux-hardware.org/?probe=84883d560d) | Oct 24, 2023 |
| Valve         | Jupiter                     | [fa38785b75](https://linux-hardware.org/?probe=fa38785b75) | Oct 23, 2023 |
| Dell          | XPS 15 7590                 | [e9ecf74d68](https://linux-hardware.org/?probe=e9ecf74d68) | Oct 23, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [817367d444](https://linux-hardware.org/?probe=817367d444) | Oct 23, 2023 |
| Dell          | Latitude E6520              | [c2fd0014ab](https://linux-hardware.org/?probe=c2fd0014ab) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SS0... | [9877bb17c1](https://linux-hardware.org/?probe=9877bb17c1) | Oct 23, 2023 |
| Dell          | Inspiron 3521               | [43b2c926ef](https://linux-hardware.org/?probe=43b2c926ef) | Oct 22, 2023 |
| ASUSTek       | G750JW                      | [9bafdb8250](https://linux-hardware.org/?probe=9bafdb8250) | Oct 22, 2023 |
| Dell          | XPS 13 9300                 | [ccf935ca37](https://linux-hardware.org/?probe=ccf935ca37) | Oct 22, 2023 |
| Acer          | Aspire A315-23              | [14ed4adf6c](https://linux-hardware.org/?probe=14ed4adf6c) | Oct 22, 2023 |
| HP            | 2000                        | [743e2b0bdf](https://linux-hardware.org/?probe=743e2b0bdf) | Oct 22, 2023 |
| Acer          | Aspire 5742                 | [f30dc155bd](https://linux-hardware.org/?probe=f30dc155bd) | Oct 21, 2023 |
| Toshiba       | Satellite A660              | [a5e343d353](https://linux-hardware.org/?probe=a5e343d353) | Oct 21, 2023 |
| Dell          | Latitude E6410              | [5b363ffe33](https://linux-hardware.org/?probe=5b363ffe33) | Oct 21, 2023 |
| Acer          | Aspire 5253                 | [871f28b131](https://linux-hardware.org/?probe=871f28b131) | Oct 20, 2023 |
| Dell          | G7 7700                     | [336bd76568](https://linux-hardware.org/?probe=336bd76568) | Oct 20, 2023 |
| Lenovo        | ThinkPad T510 4384DJ3       | [bd0354850e](https://linux-hardware.org/?probe=bd0354850e) | Oct 19, 2023 |
| Lenovo        | ThinkPad T510 4384DJ3       | [85099af926](https://linux-hardware.org/?probe=85099af926) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [2f2d05a226](https://linux-hardware.org/?probe=2f2d05a226) | Oct 19, 2023 |
| HP            | G60                         | [3c3f75c072](https://linux-hardware.org/?probe=3c3f75c072) | Oct 19, 2023 |
| Alienware     | 13                          | [15e7dfbbab](https://linux-hardware.org/?probe=15e7dfbbab) | Oct 19, 2023 |
| HP            | Pavilion dv7                | [13b6b396e9](https://linux-hardware.org/?probe=13b6b396e9) | Oct 18, 2023 |
| Valve         | Jupiter                     | [6eab7fbd58](https://linux-hardware.org/?probe=6eab7fbd58) | Oct 18, 2023 |
| Gateway       | NV59                        | [ec598a2d11](https://linux-hardware.org/?probe=ec598a2d11) | Oct 18, 2023 |
| Dell          | XPS 15 9500                 | [7e5d5dd6dd](https://linux-hardware.org/?probe=7e5d5dd6dd) | Oct 17, 2023 |
| Lenovo        | ThinkPad P52 20MAS0WG00     | [edfeee597d](https://linux-hardware.org/?probe=edfeee597d) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d5d89eba92](https://linux-hardware.org/?probe=d5d89eba92) | Oct 17, 2023 |
| Sony          | SVE15128CCW                 | [2d2c699b43](https://linux-hardware.org/?probe=2d2c699b43) | Oct 16, 2023 |
| Dell          | Latitude 7440               | [513083adb4](https://linux-hardware.org/?probe=513083adb4) | Oct 16, 2023 |
| Dell          | Latitude 7440               | [f8d4813ce1](https://linux-hardware.org/?probe=f8d4813ce1) | Oct 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [8e489a0275](https://linux-hardware.org/?probe=8e489a0275) | Oct 16, 2023 |
| Alienware     | 13                          | [24ce621e56](https://linux-hardware.org/?probe=24ce621e56) | Oct 16, 2023 |
| Apple         | MacBookPro8,1               | [df7395bd63](https://linux-hardware.org/?probe=df7395bd63) | Oct 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [d01a91e5bb](https://linux-hardware.org/?probe=d01a91e5bb) | Oct 15, 2023 |
| Acer          | Aspire A315-21              | [7476ed8679](https://linux-hardware.org/?probe=7476ed8679) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [ae2789f31f](https://linux-hardware.org/?probe=ae2789f31f) | Oct 14, 2023 |
| HP            | Pavilion dv7                | [de47e931a1](https://linux-hardware.org/?probe=de47e931a1) | Oct 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d4be846a3c](https://linux-hardware.org/?probe=d4be846a3c) | Oct 13, 2023 |
| Acer          | Aspire 7750G                | [d634013b16](https://linux-hardware.org/?probe=d634013b16) | Oct 13, 2023 |
| Notebook      | P9XXEN_EF_ED                | [89eae06fc2](https://linux-hardware.org/?probe=89eae06fc2) | Oct 13, 2023 |
| Acer          | Aspire E5-523               | [e45e982b6e](https://linux-hardware.org/?probe=e45e982b6e) | Oct 13, 2023 |
| HP            | G61                         | [34e955886e](https://linux-hardware.org/?probe=34e955886e) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [21e9b8cbc9](https://linux-hardware.org/?probe=21e9b8cbc9) | Oct 11, 2023 |
| Chuwi         | GemiBook XPro               | [b9da20666a](https://linux-hardware.org/?probe=b9da20666a) | Oct 10, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d0abc8a7e8](https://linux-hardware.org/?probe=d0abc8a7e8) | Oct 10, 2023 |
| Lenovo        | ThinkPad L490 20Q6S07X00    | [07ebe46482](https://linux-hardware.org/?probe=07ebe46482) | Oct 10, 2023 |
| Gateway       | NV59                        | [79392cad25](https://linux-hardware.org/?probe=79392cad25) | Oct 09, 2023 |
| HP            | EliteBook 840 G3            | [29af84698a](https://linux-hardware.org/?probe=29af84698a) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [60a4c67d48](https://linux-hardware.org/?probe=60a4c67d48) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [65a1ff3587](https://linux-hardware.org/?probe=65a1ff3587) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [a1ae219e54](https://linux-hardware.org/?probe=a1ae219e54) | Oct 09, 2023 |
| Dell          | Latitude 7430               | [1de7d3085b](https://linux-hardware.org/?probe=1de7d3085b) | Oct 08, 2023 |
| Acer          | Aspire A515-54              | [30b5d7d52b](https://linux-hardware.org/?probe=30b5d7d52b) | Oct 08, 2023 |
| Apple         | MacBookPro11,1              | [b30fe669c6](https://linux-hardware.org/?probe=b30fe669c6) | Oct 07, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [aaa295fa26](https://linux-hardware.org/?probe=aaa295fa26) | Oct 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3854d7db80](https://linux-hardware.org/?probe=3854d7db80) | Oct 06, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [84eebff0a6](https://linux-hardware.org/?probe=84eebff0a6) | Oct 06, 2023 |
| Dell          | Precision 5540              | [117d31349f](https://linux-hardware.org/?probe=117d31349f) | Oct 05, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [09c308ed3d](https://linux-hardware.org/?probe=09c308ed3d) | Oct 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7700b3d342](https://linux-hardware.org/?probe=7700b3d342) | Oct 04, 2023 |
| Google        | Fleex                       | [534bbe966a](https://linux-hardware.org/?probe=534bbe966a) | Oct 04, 2023 |
| Valve         | Jupiter                     | [4c7b5edf25](https://linux-hardware.org/?probe=4c7b5edf25) | Oct 04, 2023 |
| HP            | EliteBook 850 G1            | [49b19b9f02](https://linux-hardware.org/?probe=49b19b9f02) | Oct 03, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [eb797a8074](https://linux-hardware.org/?probe=eb797a8074) | Oct 03, 2023 |
| Dell          | Vostro 3550                 | [3d22b8f169](https://linux-hardware.org/?probe=3d22b8f169) | Oct 03, 2023 |
| Fujitsu       | LIFEBOOK AH531              | [4746fb19fb](https://linux-hardware.org/?probe=4746fb19fb) | Oct 03, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [dfeeeb9cbc](https://linux-hardware.org/?probe=dfeeeb9cbc) | Oct 03, 2023 |
| Dell          | Precision 5540              | [2bf28ed41e](https://linux-hardware.org/?probe=2bf28ed41e) | Oct 03, 2023 |
| Dell          | Inspiron 3543               | [1c681f7a14](https://linux-hardware.org/?probe=1c681f7a14) | Oct 02, 2023 |
| ASUSTek       | G73Jh                       | [0b9b84be03](https://linux-hardware.org/?probe=0b9b84be03) | Oct 01, 2023 |
| Acer          | AOA150                      | [969a729098](https://linux-hardware.org/?probe=969a729098) | Oct 01, 2023 |
| Apple         | MacBookPro5,3               | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| Apple         | MacBookAir6,1               | [b77b45ce58](https://linux-hardware.org/?probe=b77b45ce58) | Sep 29, 2023 |
| ASUSTek       | X505BA                      | [1caa3c5c7e](https://linux-hardware.org/?probe=1caa3c5c7e) | Sep 28, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [1492e2178d](https://linux-hardware.org/?probe=1492e2178d) | Sep 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [f86a0719d7](https://linux-hardware.org/?probe=f86a0719d7) | Sep 28, 2023 |
| Dell          | XPS 15 7590                 | [3c87964524](https://linux-hardware.org/?probe=3c87964524) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | [3ee705f2f3](https://linux-hardware.org/?probe=3ee705f2f3) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | [2b86c9fac4](https://linux-hardware.org/?probe=2b86c9fac4) | Sep 28, 2023 |
| Acer          | Swift SF314-42              | [f436f21240](https://linux-hardware.org/?probe=f436f21240) | Sep 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [17f9208e1a](https://linux-hardware.org/?probe=17f9208e1a) | Sep 27, 2023 |
| Dell          | Latitude 5420               | [3a22857022](https://linux-hardware.org/?probe=3a22857022) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [d14e65fadf](https://linux-hardware.org/?probe=d14e65fadf) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [1c764be0e3](https://linux-hardware.org/?probe=1c764be0e3) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [b8b2b3ff7e](https://linux-hardware.org/?probe=b8b2b3ff7e) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [9e9ff26362](https://linux-hardware.org/?probe=9e9ff26362) | Sep 26, 2023 |
| HP            | EliteBook 850 G1            | [55b3c2717b](https://linux-hardware.org/?probe=55b3c2717b) | Sep 25, 2023 |
| Apple         | MacBookPro7,1               | [677446fafa](https://linux-hardware.org/?probe=677446fafa) | Sep 25, 2023 |
| Lenovo        | ThinkPad T60 2623DAU        | [b5edbc8fbf](https://linux-hardware.org/?probe=b5edbc8fbf) | Sep 24, 2023 |
| Lenovo        | ThinkPad T60 2623DAU        | [144d6b3290](https://linux-hardware.org/?probe=144d6b3290) | Sep 24, 2023 |
| HP            | EliteBook 850 G1            | [00bb1a3a44](https://linux-hardware.org/?probe=00bb1a3a44) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [37ecdee3d3](https://linux-hardware.org/?probe=37ecdee3d3) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [ecc0e92fb0](https://linux-hardware.org/?probe=ecc0e92fb0) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [575df2588e](https://linux-hardware.org/?probe=575df2588e) | Sep 23, 2023 |
| Google        | Asuka                       | [cf59aebc4c](https://linux-hardware.org/?probe=cf59aebc4c) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [d6943b89de](https://linux-hardware.org/?probe=d6943b89de) | Sep 23, 2023 |
| Apple         | MacBookPro8,1               | [0c1f872edb](https://linux-hardware.org/?probe=0c1f872edb) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | [eedf248084](https://linux-hardware.org/?probe=eedf248084) | Sep 23, 2023 |
| Alienware     | m15 R3                      | [d9628d131b](https://linux-hardware.org/?probe=d9628d131b) | Sep 22, 2023 |
| ASUSTek       | GL502VM                     | [ae49f40dca](https://linux-hardware.org/?probe=ae49f40dca) | Sep 22, 2023 |
| Dell          | Latitude 5590               | [068de61e23](https://linux-hardware.org/?probe=068de61e23) | Sep 22, 2023 |
| Lenovo        | Slim 7 14IRP8 83A4          | [b1ccf59045](https://linux-hardware.org/?probe=b1ccf59045) | Sep 21, 2023 |
| Apple         | MacBookPro9,1               | [27f3ee04f8](https://linux-hardware.org/?probe=27f3ee04f8) | Sep 21, 2023 |
| HP            | Pavilion g6                 | [11c60c8645](https://linux-hardware.org/?probe=11c60c8645) | Sep 21, 2023 |
| HP            | ProBook 650 G2              | [215bdc7f1c](https://linux-hardware.org/?probe=215bdc7f1c) | Sep 20, 2023 |
| Dell          | Latitude E5550              | [8e67cb247c](https://linux-hardware.org/?probe=8e67cb247c) | Sep 20, 2023 |
| Apple         | MacBookPro15,1              | [b74bbced53](https://linux-hardware.org/?probe=b74bbced53) | Sep 20, 2023 |
| Dell          | XPS 9320                    | [611c8a5cc8](https://linux-hardware.org/?probe=611c8a5cc8) | Sep 20, 2023 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [f8f954cde7](https://linux-hardware.org/?probe=f8f954cde7) | Sep 20, 2023 |
| Lenovo        | ThinkPad W540 20BG0014US    | [2d1c5101ea](https://linux-hardware.org/?probe=2d1c5101ea) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [210a1090b3](https://linux-hardware.org/?probe=210a1090b3) | Sep 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [7678b8a06e](https://linux-hardware.org/?probe=7678b8a06e) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [cbfe8b032d](https://linux-hardware.org/?probe=cbfe8b032d) | Sep 18, 2023 |
| Valve         | Jupiter                     | [9b95215db5](https://linux-hardware.org/?probe=9b95215db5) | Sep 17, 2023 |
| HP            | Pavilion g6                 | [dd1ade8736](https://linux-hardware.org/?probe=dd1ade8736) | Sep 17, 2023 |
| HP            | Laptop 15-da0xxx            | [43081eb0eb](https://linux-hardware.org/?probe=43081eb0eb) | Sep 17, 2023 |
| Apple         | MacBookPro11,1              | [82879c821a](https://linux-hardware.org/?probe=82879c821a) | Sep 17, 2023 |
| Unknown       | Unknown                     | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [9e2d4356b2](https://linux-hardware.org/?probe=9e2d4356b2) | Sep 16, 2023 |
| Google        | Terra                       | [c96e879351](https://linux-hardware.org/?probe=c96e879351) | Sep 15, 2023 |
| Google        | Terra                       | [3f63d76318](https://linux-hardware.org/?probe=3f63d76318) | Sep 14, 2023 |
| Fujitsu       | STYLISTIC Q702              | [f3ca596dc5](https://linux-hardware.org/?probe=f3ca596dc5) | Sep 14, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [5d79965e45](https://linux-hardware.org/?probe=5d79965e45) | Sep 14, 2023 |
| HP            | ProBook 650 G2              | [654bee8844](https://linux-hardware.org/?probe=654bee8844) | Sep 14, 2023 |
| HP            | ProBook 6570b               | [fc5c01d215](https://linux-hardware.org/?probe=fc5c01d215) | Sep 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [9ace0dfae8](https://linux-hardware.org/?probe=9ace0dfae8) | Sep 14, 2023 |
| Valve         | Jupiter                     | [17d891df44](https://linux-hardware.org/?probe=17d891df44) | Sep 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [cb29d8cb77](https://linux-hardware.org/?probe=cb29d8cb77) | Sep 13, 2023 |
| Apple         | MacBookPro11,2              | [e38a2e668b](https://linux-hardware.org/?probe=e38a2e668b) | Sep 12, 2023 |
| Apple         | MacBookPro9,2               | [77db8877eb](https://linux-hardware.org/?probe=77db8877eb) | Sep 12, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [471faa50e0](https://linux-hardware.org/?probe=471faa50e0) | Sep 12, 2023 |
| Acer          | Swift SF314-512             | [4628c4e630](https://linux-hardware.org/?probe=4628c4e630) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5b93cd5b36](https://linux-hardware.org/?probe=5b93cd5b36) | Sep 11, 2023 |
| Unknown       | Unknown                     | [4944b22636](https://linux-hardware.org/?probe=4944b22636) | Sep 11, 2023 |
| Apple         | MacBookPro11,2              | [830ca674bb](https://linux-hardware.org/?probe=830ca674bb) | Sep 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d8ac2101a](https://linux-hardware.org/?probe=6d8ac2101a) | Sep 10, 2023 |
| Dell          | Precision 5540              | [061e46a96c](https://linux-hardware.org/?probe=061e46a96c) | Sep 10, 2023 |
| HP            | Laptop 15-fd0xxx            | [470e6325a3](https://linux-hardware.org/?probe=470e6325a3) | Sep 10, 2023 |
| HP            | ProBook 6570b               | [3ed768081c](https://linux-hardware.org/?probe=3ed768081c) | Sep 09, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [6104b2383d](https://linux-hardware.org/?probe=6104b2383d) | Sep 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [ae24b6af25](https://linux-hardware.org/?probe=ae24b6af25) | Sep 09, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005QU... | [0a57a98442](https://linux-hardware.org/?probe=0a57a98442) | Sep 09, 2023 |
| Dell          | Latitude E6410              | [9b57eaa1eb](https://linux-hardware.org/?probe=9b57eaa1eb) | Sep 09, 2023 |
| MSI           | GP75 Leopard 10SEK          | [11e5581873](https://linux-hardware.org/?probe=11e5581873) | Sep 08, 2023 |
| Dell          | Latitude E6410              | [5371b3f488](https://linux-hardware.org/?probe=5371b3f488) | Sep 08, 2023 |
| Dell          | Latitude E5400              | [0ede91c6cd](https://linux-hardware.org/?probe=0ede91c6cd) | Sep 08, 2023 |
| Apple         | MacBookPro5,5               | [3ab6390052](https://linux-hardware.org/?probe=3ab6390052) | Sep 08, 2023 |
| Dell          | Latitude E5400              | [727b5526f9](https://linux-hardware.org/?probe=727b5526f9) | Sep 08, 2023 |
| ASUSTek       | X541UVK                     | [425b748769](https://linux-hardware.org/?probe=425b748769) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [29c824f7ef](https://linux-hardware.org/?probe=29c824f7ef) | Sep 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [fd60499219](https://linux-hardware.org/?probe=fd60499219) | Sep 08, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Matsushita... | CF-74JCJBDAM                | [0cc1e4014d](https://linux-hardware.org/?probe=0cc1e4014d) | Sep 07, 2023 |
| Google        | Blooguard                   | [c9dec98f0f](https://linux-hardware.org/?probe=c9dec98f0f) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [b5f142ae13](https://linux-hardware.org/?probe=b5f142ae13) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [7b717719f5](https://linux-hardware.org/?probe=7b717719f5) | Sep 05, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [5728a3a48b](https://linux-hardware.org/?probe=5728a3a48b) | Sep 05, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [fdecc11aba](https://linux-hardware.org/?probe=fdecc11aba) | Sep 05, 2023 |
| HP            | Pavilion dv7                | [2d6aa7667d](https://linux-hardware.org/?probe=2d6aa7667d) | Sep 05, 2023 |
| Toshiba       | Satellite C650              | [0b87bf5b4b](https://linux-hardware.org/?probe=0b87bf5b4b) | Sep 05, 2023 |
| HP            | ZBook 15 G2                 | [18d9c74d60](https://linux-hardware.org/?probe=18d9c74d60) | Sep 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [2a53f8dc55](https://linux-hardware.org/?probe=2a53f8dc55) | Sep 04, 2023 |
| Sony          | VPCEB27FX                   | [268d3a14a7](https://linux-hardware.org/?probe=268d3a14a7) | Sep 04, 2023 |
| Acer          | Aspire A515-51              | [91bc08d933](https://linux-hardware.org/?probe=91bc08d933) | Sep 03, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [20be702d65](https://linux-hardware.org/?probe=20be702d65) | Sep 03, 2023 |
| Apple         | MacBookPro8,2               | [8ed88aa6f1](https://linux-hardware.org/?probe=8ed88aa6f1) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| Lenovo        | G570 20079                  | [3e995d059e](https://linux-hardware.org/?probe=3e995d059e) | Sep 03, 2023 |
| Google        | Droid                       | [da26431a82](https://linux-hardware.org/?probe=da26431a82) | Sep 03, 2023 |
| Google        | Droid                       | [278861e9e8](https://linux-hardware.org/?probe=278861e9e8) | Sep 03, 2023 |
| Acer          | Aspire A315-21              | [9c71da2165](https://linux-hardware.org/?probe=9c71da2165) | Sep 03, 2023 |
| HP            | EliteBook 850 G1            | [adacf1a54a](https://linux-hardware.org/?probe=adacf1a54a) | Sep 02, 2023 |
| Dell          | Precision 5540              | [3d800b12e0](https://linux-hardware.org/?probe=3d800b12e0) | Sep 02, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [affa07b412](https://linux-hardware.org/?probe=affa07b412) | Sep 02, 2023 |
| Lenovo        | ThinkPad W510 438923U       | [b0648eccac](https://linux-hardware.org/?probe=b0648eccac) | Sep 02, 2023 |
| HP            | ProBook 650 G2              | [a00c4f0a62](https://linux-hardware.org/?probe=a00c4f0a62) | Sep 02, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [28fc3470c8](https://linux-hardware.org/?probe=28fc3470c8) | Sep 01, 2023 |
| Acer          | Aspire E5-571               | [04f5152e0c](https://linux-hardware.org/?probe=04f5152e0c) | Sep 01, 2023 |
| MOTION        | NVX00                       | [8e26121033](https://linux-hardware.org/?probe=8e26121033) | Aug 31, 2023 |
| MSI           | MS-7E06                     | [afd9e6ccb2](https://linux-hardware.org/?probe=afd9e6ccb2) | Aug 30, 2023 |
| Dell          | Latitude 3510               | [220b298103](https://linux-hardware.org/?probe=220b298103) | Aug 30, 2023 |
| Lenovo        | ThinkPad W520 427637U       | [5f995c7c48](https://linux-hardware.org/?probe=5f995c7c48) | Aug 30, 2023 |
| MSI           | GP72 7RDX                   | [071785ab97](https://linux-hardware.org/?probe=071785ab97) | Aug 30, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [958ecd81e5](https://linux-hardware.org/?probe=958ecd81e5) | Aug 30, 2023 |
| Apple         | MacBookPro8,1               | [2e3c70287a](https://linux-hardware.org/?probe=2e3c70287a) | Aug 30, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [4904c007c7](https://linux-hardware.org/?probe=4904c007c7) | Aug 29, 2023 |
| Acer          | Swift SF314-512             | [a41a08d4ae](https://linux-hardware.org/?probe=a41a08d4ae) | Aug 29, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [62ff88eaf7](https://linux-hardware.org/?probe=62ff88eaf7) | Aug 29, 2023 |
| Acer          | Aspire 5742                 | [9bbb56c640](https://linux-hardware.org/?probe=9bbb56c640) | Aug 29, 2023 |
| System76      | Galago Pro                  | [31330746e6](https://linux-hardware.org/?probe=31330746e6) | Aug 29, 2023 |
| Toshiba       | Satellite Pro C70-C         | [eb9fbb104c](https://linux-hardware.org/?probe=eb9fbb104c) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4bff36d914](https://linux-hardware.org/?probe=4bff36d914) | Aug 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [e165507af8](https://linux-hardware.org/?probe=e165507af8) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [329d960437](https://linux-hardware.org/?probe=329d960437) | Aug 27, 2023 |
| Apple         | MacBookPro9,1               | [20eda7fab5](https://linux-hardware.org/?probe=20eda7fab5) | Aug 26, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | [46a647db9b](https://linux-hardware.org/?probe=46a647db9b) | Aug 26, 2023 |
| Dell          | Precision M4600             | [fcc3763c08](https://linux-hardware.org/?probe=fcc3763c08) | Aug 26, 2023 |
| Lenovo        | ThinkPad T410 25222AU       | [fdc78cf5a0](https://linux-hardware.org/?probe=fdc78cf5a0) | Aug 26, 2023 |
| HP            | Laptop 17-ca2xxx            | [f6d894d339](https://linux-hardware.org/?probe=f6d894d339) | Aug 26, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [f09b86405b](https://linux-hardware.org/?probe=f09b86405b) | Aug 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [3c528e98c6](https://linux-hardware.org/?probe=3c528e98c6) | Aug 26, 2023 |
| Lenovo        | V15-IIL 82C5                | [cee65701f2](https://linux-hardware.org/?probe=cee65701f2) | Aug 25, 2023 |
| Dell          | Inspiron 5585               | [49a9e7dbf0](https://linux-hardware.org/?probe=49a9e7dbf0) | Aug 25, 2023 |
| Acer          | Aspire 5742                 | [7d896ad750](https://linux-hardware.org/?probe=7d896ad750) | Aug 24, 2023 |
| System76      | Gazelle                     | [ee67365e0c](https://linux-hardware.org/?probe=ee67365e0c) | Aug 24, 2023 |
| Dell          | Latitude 5510               | [d0b9ab746d](https://linux-hardware.org/?probe=d0b9ab746d) | Aug 24, 2023 |
| Lenovo        | ThinkPad T450s 20BWS2M30... | [052c7eaa90](https://linux-hardware.org/?probe=052c7eaa90) | Aug 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [19433fe76f](https://linux-hardware.org/?probe=19433fe76f) | Aug 24, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [2431197665](https://linux-hardware.org/?probe=2431197665) | Aug 24, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HM_... | [2281d96afb](https://linux-hardware.org/?probe=2281d96afb) | Aug 24, 2023 |
| Xplore        | iX104C6                     | [5d8ea1a454](https://linux-hardware.org/?probe=5d8ea1a454) | Aug 24, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [816f3ce721](https://linux-hardware.org/?probe=816f3ce721) | Aug 24, 2023 |
| HP            | EliteBook 8530w             | [3ee1fe77ce](https://linux-hardware.org/?probe=3ee1fe77ce) | Aug 23, 2023 |
| MSI           | GP72 6QF                    | [3afc91a639](https://linux-hardware.org/?probe=3afc91a639) | Aug 23, 2023 |
| HP            | Presario V2000 (ES307UA#... | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| ASUSTek       | G751JM                      | [7cdb0c52e4](https://linux-hardware.org/?probe=7cdb0c52e4) | Aug 23, 2023 |
| HP            | EliteBook 2170p             | [0bba785aee](https://linux-hardware.org/?probe=0bba785aee) | Aug 21, 2023 |
| Dell          | Latitude 5510               | [e5d8770a77](https://linux-hardware.org/?probe=e5d8770a77) | Aug 21, 2023 |
| Lenovo        | ThinkPad X220 42902WU       | [9fd887dc27](https://linux-hardware.org/?probe=9fd887dc27) | Aug 21, 2023 |
| Toshiba       | Satellite Pro A50-C         | [ed71bba366](https://linux-hardware.org/?probe=ed71bba366) | Aug 19, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [030cbe1086](https://linux-hardware.org/?probe=030cbe1086) | Aug 19, 2023 |
| HP            | Pavilion g6                 | [8e7844a79d](https://linux-hardware.org/?probe=8e7844a79d) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | [93530d7cb1](https://linux-hardware.org/?probe=93530d7cb1) | Aug 18, 2023 |
| Panasonic     | CF-31AQAAA1M                | [64416dbba5](https://linux-hardware.org/?probe=64416dbba5) | Aug 17, 2023 |
| Acer          | Aspire 5920                 | [31447ef238](https://linux-hardware.org/?probe=31447ef238) | Aug 17, 2023 |
| Acer          | Aspire 5920                 | [8c57c50f82](https://linux-hardware.org/?probe=8c57c50f82) | Aug 17, 2023 |
| Dell          | Precision 5540              | [a0a36884a0](https://linux-hardware.org/?probe=a0a36884a0) | Aug 17, 2023 |
| Dell          | Inspiron 1200               | [2340dcab47](https://linux-hardware.org/?probe=2340dcab47) | Aug 17, 2023 |
| Dell          | XPS 9320                    | [cb112d9f03](https://linux-hardware.org/?probe=cb112d9f03) | Aug 17, 2023 |
| Lenovo        | IdeaPad 520S-14IKB 81BL     | [a69ad2f7b8](https://linux-hardware.org/?probe=a69ad2f7b8) | Aug 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [2ac8f6838a](https://linux-hardware.org/?probe=2ac8f6838a) | Aug 15, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [65f7a020fe](https://linux-hardware.org/?probe=65f7a020fe) | Aug 14, 2023 |
| Dell          | XPS 13 9360                 | [69b51e3f5a](https://linux-hardware.org/?probe=69b51e3f5a) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [24b85b3417](https://linux-hardware.org/?probe=24b85b3417) | Aug 14, 2023 |
| Google        | Blooglet                    | [b9967e65c2](https://linux-hardware.org/?probe=b9967e65c2) | Aug 14, 2023 |
| HP            | ProBook 650 G2              | [b310a70636](https://linux-hardware.org/?probe=b310a70636) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Apple         | MacBookAir6,2               | [4eeea4cc95](https://linux-hardware.org/?probe=4eeea4cc95) | Aug 13, 2023 |
| Lenovo        | IdeaPad Y570 0862           | [0ea140ff49](https://linux-hardware.org/?probe=0ea140ff49) | Aug 12, 2023 |
| Unknown       | Unknown                     | [21abd7288e](https://linux-hardware.org/?probe=21abd7288e) | Aug 12, 2023 |
| HP            | Notebook                    | [de8a0230c4](https://linux-hardware.org/?probe=de8a0230c4) | Aug 11, 2023 |
| HP            | EliteBook 840 G1            | [95d93fda2c](https://linux-hardware.org/?probe=95d93fda2c) | Aug 11, 2023 |
| HP            | EliteBook 2560p             | [0b5cf409d8](https://linux-hardware.org/?probe=0b5cf409d8) | Aug 11, 2023 |
| Dell          | Inspiron 3531               | [0384e8a950](https://linux-hardware.org/?probe=0384e8a950) | Aug 11, 2023 |
| Google        | Bobba360                    | [128700115a](https://linux-hardware.org/?probe=128700115a) | Aug 10, 2023 |
| Dell          | Latitude 3540               | [496e3ab340](https://linux-hardware.org/?probe=496e3ab340) | Aug 10, 2023 |
| Google        | Snappy                      | [73ecdd5048](https://linux-hardware.org/?probe=73ecdd5048) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [75b55100a9](https://linux-hardware.org/?probe=75b55100a9) | Aug 10, 2023 |
| Dell          | Precision 5540              | [e68fee1e24](https://linux-hardware.org/?probe=e68fee1e24) | Aug 10, 2023 |
| Gateway       | NV57H                       | [826aaf5dd8](https://linux-hardware.org/?probe=826aaf5dd8) | Aug 10, 2023 |
| HP            | ProBook 650 G2              | [8fbbf1483d](https://linux-hardware.org/?probe=8fbbf1483d) | Aug 09, 2023 |
| Google        | Bobba360                    | [fa4a78b024](https://linux-hardware.org/?probe=fa4a78b024) | Aug 09, 2023 |
| System76      | Darter Pro                  | [5162d61c01](https://linux-hardware.org/?probe=5162d61c01) | Aug 09, 2023 |
| Dell          | Latitude 3350               | [77100b2ef6](https://linux-hardware.org/?probe=77100b2ef6) | Aug 09, 2023 |
| HP            | ProBook 650 G2              | [78859b39fb](https://linux-hardware.org/?probe=78859b39fb) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [f48f680274](https://linux-hardware.org/?probe=f48f680274) | Aug 08, 2023 |
| Dell          | Latitude E5470              | [f64529e38b](https://linux-hardware.org/?probe=f64529e38b) | Aug 08, 2023 |
| HP            | Laptop 14-dq3xxx            | [c547f01fbb](https://linux-hardware.org/?probe=c547f01fbb) | Aug 08, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [088a8fad47](https://linux-hardware.org/?probe=088a8fad47) | Aug 08, 2023 |
| HP            | Elite x2 1012 G1            | [0ee8428f91](https://linux-hardware.org/?probe=0ee8428f91) | Aug 07, 2023 |
| Dell          | Latitude 7300               | [932f04033c](https://linux-hardware.org/?probe=932f04033c) | Aug 07, 2023 |
| HP            | Laptop 15-dy2xxx            | [5777798e8f](https://linux-hardware.org/?probe=5777798e8f) | Aug 07, 2023 |
| Acer          | E1-510                      | [2d6776c4fe](https://linux-hardware.org/?probe=2d6776c4fe) | Aug 06, 2023 |
| HP            | EliteBook 840 G5            | [9688966097](https://linux-hardware.org/?probe=9688966097) | Aug 06, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [bd989967e7](https://linux-hardware.org/?probe=bd989967e7) | Aug 06, 2023 |
| Dell          | Inspiron 15 3525            | [0219350ae0](https://linux-hardware.org/?probe=0219350ae0) | Aug 05, 2023 |
| Dell          | Inspiron 15 3525            | [350a405f33](https://linux-hardware.org/?probe=350a405f33) | Aug 05, 2023 |
| Apple         | MacBookPro14,1              | [d3630fa2ed](https://linux-hardware.org/?probe=d3630fa2ed) | Aug 05, 2023 |
| Lenovo        | ThinkPad X131e 33671S2      | [3f83b5efac](https://linux-hardware.org/?probe=3f83b5efac) | Aug 05, 2023 |
| Corsair       | Voyager a1600               | [6dea5f2c0c](https://linux-hardware.org/?probe=6dea5f2c0c) | Aug 04, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [ff55512c0e](https://linux-hardware.org/?probe=ff55512c0e) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| HP            | Laptop 15-fd0xxx            | [8f3b8dea26](https://linux-hardware.org/?probe=8f3b8dea26) | Aug 04, 2023 |
| HP            | EliteBook Folio G1          | [b9bb38ddd4](https://linux-hardware.org/?probe=b9bb38ddd4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [7d86876920](https://linux-hardware.org/?probe=7d86876920) | Aug 03, 2023 |
| Dell          | Latitude 5440               | [5791d15bc8](https://linux-hardware.org/?probe=5791d15bc8) | Aug 02, 2023 |
| Dell          | Latitude 5540               | [e521b93e2f](https://linux-hardware.org/?probe=e521b93e2f) | Aug 02, 2023 |
| Dell          | Latitude 5440               | [5b0eb512d1](https://linux-hardware.org/?probe=5b0eb512d1) | Aug 02, 2023 |
| HP            | ProBook 650 G4              | [d041df173b](https://linux-hardware.org/?probe=d041df173b) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [944afe5083](https://linux-hardware.org/?probe=944afe5083) | Aug 02, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [74f1782ead](https://linux-hardware.org/?probe=74f1782ead) | Aug 02, 2023 |
| Acer          | Aspire E1-532               | [9042ebc249](https://linux-hardware.org/?probe=9042ebc249) | Aug 01, 2023 |
| Valve         | Jupiter                     | [896569d1d6](https://linux-hardware.org/?probe=896569d1d6) | Aug 01, 2023 |
| ASUSTek       | X751LA                      | [928a69b9af](https://linux-hardware.org/?probe=928a69b9af) | Aug 01, 2023 |
| Lenovo        | 3000 C100 07612GU           | [3941ecc4f2](https://linux-hardware.org/?probe=3941ecc4f2) | Aug 01, 2023 |
| HP            | ProBook 445 G7              | [96e95e4bd2](https://linux-hardware.org/?probe=96e95e4bd2) | Jul 31, 2023 |
| HP            | EliteBook 840 G2            | [067b112fb8](https://linux-hardware.org/?probe=067b112fb8) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50s 20FLCTO1WW    | [1594795f9e](https://linux-hardware.org/?probe=1594795f9e) | Jul 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0DT0... | [bd0d0f2888](https://linux-hardware.org/?probe=bd0d0f2888) | Jul 30, 2023 |
| HP            | ProBook 4540s               | [0fae07b574](https://linux-hardware.org/?probe=0fae07b574) | Jul 30, 2023 |
| Dell          | XPS 15 7590                 | [4f2f49a6b2](https://linux-hardware.org/?probe=4f2f49a6b2) | Jul 30, 2023 |
| BOSGAME       | U56                         | [39d52e51f5](https://linux-hardware.org/?probe=39d52e51f5) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | [c3101b6a76](https://linux-hardware.org/?probe=c3101b6a76) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | [915938d446](https://linux-hardware.org/?probe=915938d446) | Jul 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [74a7a53f6a](https://linux-hardware.org/?probe=74a7a53f6a) | Jul 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [cd073a7899](https://linux-hardware.org/?probe=cd073a7899) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [e62cce964c](https://linux-hardware.org/?probe=e62cce964c) | Jul 29, 2023 |
| HP            | ProBook 455R G6             | [3731e7465c](https://linux-hardware.org/?probe=3731e7465c) | Jul 29, 2023 |
| Dell          | Latitude 5520               | [5151c4275a](https://linux-hardware.org/?probe=5151c4275a) | Jul 29, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [d94c3cc0e8](https://linux-hardware.org/?probe=d94c3cc0e8) | Jul 28, 2023 |
| Acer          | Aspire 5810T                | [2d141d703d](https://linux-hardware.org/?probe=2d141d703d) | Jul 28, 2023 |
| MSI           | Katana GF66 11UE            | [78e12df29a](https://linux-hardware.org/?probe=78e12df29a) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ea402f269e](https://linux-hardware.org/?probe=ea402f269e) | Jul 28, 2023 |
| Alienware     | m17 R4                      | [eece2da9ed](https://linux-hardware.org/?probe=eece2da9ed) | Jul 27, 2023 |
| Acer          | Aspire 5810T                | [9b7b328324](https://linux-hardware.org/?probe=9b7b328324) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4152e1f98e](https://linux-hardware.org/?probe=4152e1f98e) | Jul 27, 2023 |
| HP            | ProBook 4540s               | [f41d6c4f4b](https://linux-hardware.org/?probe=f41d6c4f4b) | Jul 26, 2023 |
| HP            | G60                         | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [3cb74490f6](https://linux-hardware.org/?probe=3cb74490f6) | Jul 25, 2023 |
| Google        | Droid                       | [ae803483c2](https://linux-hardware.org/?probe=ae803483c2) | Jul 25, 2023 |
| HP            | Laptop 15-db0xxx            | [f01ec95642](https://linux-hardware.org/?probe=f01ec95642) | Jul 25, 2023 |
| HP            | ProBook 4540s               | [5c4b165cea](https://linux-hardware.org/?probe=5c4b165cea) | Jul 25, 2023 |
| HP            | ProBook 4540s               | [4ad8be01ca](https://linux-hardware.org/?probe=4ad8be01ca) | Jul 25, 2023 |
| Lenovo        | ThinkPad T430 2347H91       | [0ed3c4bc6a](https://linux-hardware.org/?probe=0ed3c4bc6a) | Jul 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [5c52eecd16](https://linux-hardware.org/?probe=5c52eecd16) | Jul 25, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [562e6e1026](https://linux-hardware.org/?probe=562e6e1026) | Jul 25, 2023 |
| Dell          | Latitude 7490               | [066e3b9518](https://linux-hardware.org/?probe=066e3b9518) | Jul 25, 2023 |
| Lenovo        | ThinkPad T420s 417152U      | [22e09689b0](https://linux-hardware.org/?probe=22e09689b0) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [032db75736](https://linux-hardware.org/?probe=032db75736) | Jul 23, 2023 |
| Lenovo        | ThinkPad P53 20QN004BCA     | [04a2ed4bd2](https://linux-hardware.org/?probe=04a2ed4bd2) | Jul 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [1ee910fc1c](https://linux-hardware.org/?probe=1ee910fc1c) | Jul 22, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [d02b0e9f74](https://linux-hardware.org/?probe=d02b0e9f74) | Jul 22, 2023 |
| Gateway       | NV57H                       | [3209dcf267](https://linux-hardware.org/?probe=3209dcf267) | Jul 22, 2023 |
| Gateway       | NV57H                       | [35dac8980f](https://linux-hardware.org/?probe=35dac8980f) | Jul 22, 2023 |
| HP            | Pavilion dv7                | [a74719eac2](https://linux-hardware.org/?probe=a74719eac2) | Jul 21, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | [27b5dabe8d](https://linux-hardware.org/?probe=27b5dabe8d) | Jul 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fb09f582c5](https://linux-hardware.org/?probe=fb09f582c5) | Jul 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2fcc9e6028](https://linux-hardware.org/?probe=2fcc9e6028) | Jul 20, 2023 |
| ASUSTek       | T100TAM                     | [43cb18f0ee](https://linux-hardware.org/?probe=43cb18f0ee) | Jul 20, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0C800     | [b894a6d96b](https://linux-hardware.org/?probe=b894a6d96b) | Jul 19, 2023 |
| ASUSTek       | GL502VM                     | [dd46e07611](https://linux-hardware.org/?probe=dd46e07611) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8cb16d19aa](https://linux-hardware.org/?probe=8cb16d19aa) | Jul 19, 2023 |
| Apple         | MacBookPro11,2              | [3121fc5450](https://linux-hardware.org/?probe=3121fc5450) | Jul 18, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [efd490f52d](https://linux-hardware.org/?probe=efd490f52d) | Jul 18, 2023 |
| HP            | Pavilion Notebook           | [babb224527](https://linux-hardware.org/?probe=babb224527) | Jul 18, 2023 |
| HP            | Pavilion Laptop 17-ar0xx    | [574cd2e0f8](https://linux-hardware.org/?probe=574cd2e0f8) | Jul 17, 2023 |
| Google        | Phaser360                   | [1e66458514](https://linux-hardware.org/?probe=1e66458514) | Jul 17, 2023 |
| System76      | Serval WS                   | [a916a92726](https://linux-hardware.org/?probe=a916a92726) | Jul 17, 2023 |
| ASUSTek       | X751LA                      | [345fab37ab](https://linux-hardware.org/?probe=345fab37ab) | Jul 17, 2023 |
| Dell          | Latitude E6420              | [7006e50178](https://linux-hardware.org/?probe=7006e50178) | Jul 17, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [55a5100039](https://linux-hardware.org/?probe=55a5100039) | Jul 16, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [ad8f031cb2](https://linux-hardware.org/?probe=ad8f031cb2) | Jul 16, 2023 |
| HP            | Pavilion dv7                | [e983b50085](https://linux-hardware.org/?probe=e983b50085) | Jul 15, 2023 |
| System76      | Pangolin                    | [486df7ead2](https://linux-hardware.org/?probe=486df7ead2) | Jul 14, 2023 |
| Dell          | Precision 5480              | [57d3fff688](https://linux-hardware.org/?probe=57d3fff688) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [21fc63e4dd](https://linux-hardware.org/?probe=21fc63e4dd) | Jul 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e84bf83ac1](https://linux-hardware.org/?probe=e84bf83ac1) | Jul 13, 2023 |
| Panasonic     | CF-S10CDHEDM                | [55204a29c3](https://linux-hardware.org/?probe=55204a29c3) | Jul 12, 2023 |
| MSI           | GF65 Thin 10UE              | [414c5bc2c0](https://linux-hardware.org/?probe=414c5bc2c0) | Jul 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [15c5dec8dc](https://linux-hardware.org/?probe=15c5dec8dc) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | [27df8fc0e5](https://linux-hardware.org/?probe=27df8fc0e5) | Jul 11, 2023 |
| Dell          | Latitude E5540              | [cdad6cb751](https://linux-hardware.org/?probe=cdad6cb751) | Jul 11, 2023 |
| Lenovo        | IdeaPad Z570 10249UU        | [4179167c95](https://linux-hardware.org/?probe=4179167c95) | Jul 11, 2023 |
| MSI           | GF65 Thin 10UE              | [d73ac20739](https://linux-hardware.org/?probe=d73ac20739) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | [beef3128c2](https://linux-hardware.org/?probe=beef3128c2) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | [cf25605b3a](https://linux-hardware.org/?probe=cf25605b3a) | Jul 10, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [7d5e51d9a8](https://linux-hardware.org/?probe=7d5e51d9a8) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | [3c3c2ac038](https://linux-hardware.org/?probe=3c3c2ac038) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [707f0b8eeb](https://linux-hardware.org/?probe=707f0b8eeb) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | [8dd1516457](https://linux-hardware.org/?probe=8dd1516457) | Jul 08, 2023 |
| Dell          | Latitude 5540               | [1bd623d7b0](https://linux-hardware.org/?probe=1bd623d7b0) | Jul 07, 2023 |
| Acer          | Nitro AN515-57              | [12e3f9ecc7](https://linux-hardware.org/?probe=12e3f9ecc7) | Jul 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| Lenovo        | ThinkPad T510 4349RK6       | [e25d3f6783](https://linux-hardware.org/?probe=e25d3f6783) | Jul 07, 2023 |
| Lenovo        | ThinkPad T450s 20BWS0PJ0... | [2345d00757](https://linux-hardware.org/?probe=2345d00757) | Jul 07, 2023 |
| Dell          | Latitude 3540               | [4ebbd2913f](https://linux-hardware.org/?probe=4ebbd2913f) | Jul 06, 2023 |
| ASUSTek       | GL703VD                     | [68235880f7](https://linux-hardware.org/?probe=68235880f7) | Jul 06, 2023 |
| Framework     | Laptop                      | [ea4c4585d0](https://linux-hardware.org/?probe=ea4c4585d0) | Jul 06, 2023 |
| Dell          | XPS 15 9520                 | [f255433162](https://linux-hardware.org/?probe=f255433162) | Jul 06, 2023 |
| ASUSTek       | TP501UA                     | [ee28aacdd1](https://linux-hardware.org/?probe=ee28aacdd1) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [46e6f4b081](https://linux-hardware.org/?probe=46e6f4b081) | Jul 05, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [6bf093ef61](https://linux-hardware.org/?probe=6bf093ef61) | Jul 05, 2023 |
| HP            | ProBook 450 G5              | [7a15493631](https://linux-hardware.org/?probe=7a15493631) | Jul 05, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [79c5344e62](https://linux-hardware.org/?probe=79c5344e62) | Jul 04, 2023 |
| HP            | Pavilion dv7                | [09627980f5](https://linux-hardware.org/?probe=09627980f5) | Jul 04, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [9ec1de725f](https://linux-hardware.org/?probe=9ec1de725f) | Jul 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [5d1b3596c1](https://linux-hardware.org/?probe=5d1b3596c1) | Jul 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [3290dd955a](https://linux-hardware.org/?probe=3290dd955a) | Jul 03, 2023 |
| Toshiba       | TECRA R950                  | [77a720dc31](https://linux-hardware.org/?probe=77a720dc31) | Jul 03, 2023 |
| MSI           | GT72VR 6RD                  | [ea6887d031](https://linux-hardware.org/?probe=ea6887d031) | Jul 01, 2023 |
| Dell          | Latitude 3500               | [8e82f9abda](https://linux-hardware.org/?probe=8e82f9abda) | Jul 01, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [585ee2564e](https://linux-hardware.org/?probe=585ee2564e) | Jul 01, 2023 |
| HP            | ENVY m6                     | [b4f8d19895](https://linux-hardware.org/?probe=b4f8d19895) | Jun 30, 2023 |
| Dell          | Latitude E5440              | [1fd8c9652a](https://linux-hardware.org/?probe=1fd8c9652a) | Jun 30, 2023 |
| Samsung       | R430/R480                   | [485a09a0d2](https://linux-hardware.org/?probe=485a09a0d2) | Jun 30, 2023 |
| Lenovo        | ThinkPad Edge E545 20B2S... | [c7e71c8c0b](https://linux-hardware.org/?probe=c7e71c8c0b) | Jun 29, 2023 |
| Lenovo        | ThinkPad Edge E545 20B2S... | [0c3b48af38](https://linux-hardware.org/?probe=0c3b48af38) | Jun 29, 2023 |
| Lenovo        | ThinkPad T580 20LAS0DL00    | [5d27a44710](https://linux-hardware.org/?probe=5d27a44710) | Jun 28, 2023 |
| Apple         | MacBookAir7,2               | [92a71d25d7](https://linux-hardware.org/?probe=92a71d25d7) | Jun 28, 2023 |
| Dell          | Latitude 3500               | [e1831984f8](https://linux-hardware.org/?probe=e1831984f8) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [2debd02f0c](https://linux-hardware.org/?probe=2debd02f0c) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [3b775b8099](https://linux-hardware.org/?probe=3b775b8099) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| Sony          | VPCEB37FD                   | [afe6ac4f32](https://linux-hardware.org/?probe=afe6ac4f32) | Jun 27, 2023 |
| MSI           | GP72 7RDX                   | [d61ba42fcf](https://linux-hardware.org/?probe=d61ba42fcf) | Jun 27, 2023 |
| HP            | Laptop 15-ef1xxx            | [765d0708eb](https://linux-hardware.org/?probe=765d0708eb) | Jun 26, 2023 |
| Gateway       | NV57H                       | [a49db45595](https://linux-hardware.org/?probe=a49db45595) | Jun 26, 2023 |
| Dell          | XPS 15 7590                 | [dfc817892b](https://linux-hardware.org/?probe=dfc817892b) | Jun 26, 2023 |
| Gateway       | NV57H                       | [ee84597590](https://linux-hardware.org/?probe=ee84597590) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [4518a77b73](https://linux-hardware.org/?probe=4518a77b73) | Jun 26, 2023 |
| HP            | ProBook 650 G2              | [d34d125de2](https://linux-hardware.org/?probe=d34d125de2) | Jun 26, 2023 |
| HP            | ProBook 650 G2              | [1858ae62ee](https://linux-hardware.org/?probe=1858ae62ee) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [501d3b5530](https://linux-hardware.org/?probe=501d3b5530) | Jun 25, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | [68117675ab](https://linux-hardware.org/?probe=68117675ab) | Jun 25, 2023 |
| ASUSTek       | E403SA                      | [bdc47269c3](https://linux-hardware.org/?probe=bdc47269c3) | Jun 25, 2023 |
| Sony          | VPCEB37FD                   | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| Dell          | Inspiron 15-3567            | [614687bba4](https://linux-hardware.org/?probe=614687bba4) | Jun 25, 2023 |
| Xplore        | iX104C6                     | [23bb4c656b](https://linux-hardware.org/?probe=23bb4c656b) | Jun 24, 2023 |
| Dell          | XPS 13 9370                 | [7ba7b1dc58](https://linux-hardware.org/?probe=7ba7b1dc58) | Jun 22, 2023 |
| Google        | Kefka                       | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| HP            | ProBook 450 G2              | [60babdeb16](https://linux-hardware.org/?probe=60babdeb16) | Jun 21, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [caaf6ce403](https://linux-hardware.org/?probe=caaf6ce403) | Jun 21, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [e5db90d1b4](https://linux-hardware.org/?probe=e5db90d1b4) | Jun 20, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [f38684c33d](https://linux-hardware.org/?probe=f38684c33d) | Jun 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [e3ded6b5e4](https://linux-hardware.org/?probe=e3ded6b5e4) | Jun 19, 2023 |
| Apple         | MacBookPro8,1               | [70d76362e2](https://linux-hardware.org/?probe=70d76362e2) | Jun 19, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [125b4fefa5](https://linux-hardware.org/?probe=125b4fefa5) | Jun 19, 2023 |
| Dell          | System XPS L502X            | [463e017820](https://linux-hardware.org/?probe=463e017820) | Jun 19, 2023 |
| Lenovo        | ThinkPad E590 20NB001JUS    | [5fb441bf83](https://linux-hardware.org/?probe=5fb441bf83) | Jun 18, 2023 |
| Acer          | Aspire A315-22              | [f977b4851c](https://linux-hardware.org/?probe=f977b4851c) | Jun 18, 2023 |
| HP            | EliteBook 840 G3            | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| HP            | Pavilion dv7                | [166b70ddad](https://linux-hardware.org/?probe=166b70ddad) | Jun 18, 2023 |
| ASUSTek       | X553MA                      | [ef0c9e5597](https://linux-hardware.org/?probe=ef0c9e5597) | Jun 18, 2023 |
| Google        | Kefka                       | [86421e3d29](https://linux-hardware.org/?probe=86421e3d29) | Jun 18, 2023 |
| Valve         | Jupiter                     | [9da2af6fe5](https://linux-hardware.org/?probe=9da2af6fe5) | Jun 18, 2023 |
| HP            | ProBook 445 G7              | [71c3b52599](https://linux-hardware.org/?probe=71c3b52599) | Jun 17, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [d415965e91](https://linux-hardware.org/?probe=d415965e91) | Jun 17, 2023 |
| Dell          | Latitude E6400              | [0f8aca3e72](https://linux-hardware.org/?probe=0f8aca3e72) | Jun 17, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [268b733c44](https://linux-hardware.org/?probe=268b733c44) | Jun 16, 2023 |
| Acer          | Aspire V3-572P              | [49302da0a9](https://linux-hardware.org/?probe=49302da0a9) | Jun 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [3b552a7f4a](https://linux-hardware.org/?probe=3b552a7f4a) | Jun 15, 2023 |
| Apple         | MacBookPro7,1               | [ae4444566b](https://linux-hardware.org/?probe=ae4444566b) | Jun 14, 2023 |
| Apple         | MacBookPro5,5               | [b639a64b45](https://linux-hardware.org/?probe=b639a64b45) | Jun 14, 2023 |
| MSI           | GE62 2QF                    | [aabf8f661a](https://linux-hardware.org/?probe=aabf8f661a) | Jun 14, 2023 |
| Acer          | Aspire 5733                 | [6291133649](https://linux-hardware.org/?probe=6291133649) | Jun 13, 2023 |
| Acer          | Aspire V3-572P              | [12f6b82789](https://linux-hardware.org/?probe=12f6b82789) | Jun 13, 2023 |
| Apple         | MacBookPro5,5               | [b303846ade](https://linux-hardware.org/?probe=b303846ade) | Jun 13, 2023 |
| Apple         | MacBookPro7,1               | [c1f5bf2148](https://linux-hardware.org/?probe=c1f5bf2148) | Jun 13, 2023 |
| Dell          | XPS 15 9560                 | [ca84981180](https://linux-hardware.org/?probe=ca84981180) | Jun 12, 2023 |
| Fujitsu       | T900                        | [4716750f3f](https://linux-hardware.org/?probe=4716750f3f) | Jun 12, 2023 |
| Apple         | MacBookPro5,5               | [cba5fb51f8](https://linux-hardware.org/?probe=cba5fb51f8) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3c7683dfc4](https://linux-hardware.org/?probe=3c7683dfc4) | Jun 11, 2023 |
| Dell          | XPS 13 9310                 | [740fb14b2f](https://linux-hardware.org/?probe=740fb14b2f) | Jun 11, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1a36e2fa98](https://linux-hardware.org/?probe=1a36e2fa98) | Jun 10, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [42722d78d8](https://linux-hardware.org/?probe=42722d78d8) | Jun 10, 2023 |
| Sony          | VPCF120FD                   | [47f02bd498](https://linux-hardware.org/?probe=47f02bd498) | Jun 10, 2023 |
| Sony          | VPCEB2AFD                   | [1d9d6ddd74](https://linux-hardware.org/?probe=1d9d6ddd74) | Jun 09, 2023 |
| Panasonic     | CF-S10CDHEDM                | [19b6085754](https://linux-hardware.org/?probe=19b6085754) | Jun 09, 2023 |
| Apple         | MacBookPro5,5               | [09344fa63e](https://linux-hardware.org/?probe=09344fa63e) | Jun 09, 2023 |
| Dell          | Inspiron 5505               | [05973f7d9b](https://linux-hardware.org/?probe=05973f7d9b) | Jun 08, 2023 |
| Dell          | Inspiron 5547               | [7775c4c871](https://linux-hardware.org/?probe=7775c4c871) | Jun 07, 2023 |
| Dell          | Inspiron 5547               | [3a43778152](https://linux-hardware.org/?probe=3a43778152) | Jun 07, 2023 |
| Lenovo        | ThinkPad W520 4282AB9       | [790550e99f](https://linux-hardware.org/?probe=790550e99f) | Jun 06, 2023 |
| Apple         | MacBookPro8,1               | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| Valve         | Jupiter                     | [aa2925f22f](https://linux-hardware.org/?probe=aa2925f22f) | Jun 05, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0DR0... | [6fad1535c3](https://linux-hardware.org/?probe=6fad1535c3) | Jun 04, 2023 |
| Dell          | Precision 5540              | [f9f2304792](https://linux-hardware.org/?probe=f9f2304792) | Jun 03, 2023 |
| HP            | ProBook 450 G2              | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [d75ea1f93f](https://linux-hardware.org/?probe=d75ea1f93f) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [29c4ba7312](https://linux-hardware.org/?probe=29c4ba7312) | Jun 01, 2023 |
| HP            | ZBook 15 G3                 | [28eec89b69](https://linux-hardware.org/?probe=28eec89b69) | Jun 01, 2023 |
| Lenovo        | ThinkPad W510 4391B49       | [1e1004a387](https://linux-hardware.org/?probe=1e1004a387) | Jun 01, 2023 |
| Dell          | XPS 13 9310                 | [b3eed1356b](https://linux-hardware.org/?probe=b3eed1356b) | Jun 01, 2023 |
| Dell          | Latitude E5540              | [83d7c0065d](https://linux-hardware.org/?probe=83d7c0065d) | Jun 01, 2023 |
| Apple         | MacBookPro9,1               | [0b958e0c5c](https://linux-hardware.org/?probe=0b958e0c5c) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [e065b72b88](https://linux-hardware.org/?probe=e065b72b88) | May 31, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [52047d2230](https://linux-hardware.org/?probe=52047d2230) | May 31, 2023 |
| MSI           | GF65 Thin 10UE              | [98e2096ab6](https://linux-hardware.org/?probe=98e2096ab6) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Dell          | Latitude E6530              | [26f783c383](https://linux-hardware.org/?probe=26f783c383) | May 29, 2023 |
| Dell          | Latitude E6530              | [a47a934500](https://linux-hardware.org/?probe=a47a934500) | May 29, 2023 |
| Acer          | Aspire E1-572               | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo        | ThinkPad T420 4236N79       | [9908724093](https://linux-hardware.org/?probe=9908724093) | May 28, 2023 |
| Acer          | Aspire A315-41              | [8bdf6722e2](https://linux-hardware.org/?probe=8bdf6722e2) | May 28, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [22cbc01649](https://linux-hardware.org/?probe=22cbc01649) | May 28, 2023 |
| Apple         | MacBookPro16,2              | [993b013d0a](https://linux-hardware.org/?probe=993b013d0a) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| Dell          | Latitude E6330              | [dd302db25c](https://linux-hardware.org/?probe=dd302db25c) | May 27, 2023 |
| Acer          | Aspire ES1-523              | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| Dell          | Latitude E6330              | [f93b318d71](https://linux-hardware.org/?probe=f93b318d71) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| Apple         | MacBookPro5,5               | [f1b7ea69ea](https://linux-hardware.org/?probe=f1b7ea69ea) | May 27, 2023 |
| Lenovo        | Unknown                     | [dbf5c576b2](https://linux-hardware.org/?probe=dbf5c576b2) | May 27, 2023 |
| Samsung       | 910S3G/910S3T               | [e041a5365e](https://linux-hardware.org/?probe=e041a5365e) | May 26, 2023 |
| Acer          | Aspire A315-42              | [d229a8eb01](https://linux-hardware.org/?probe=d229a8eb01) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| Acer          | Aspire V3-551               | [316db578fe](https://linux-hardware.org/?probe=316db578fe) | May 25, 2023 |
| Valve         | Jupiter                     | [84756c6406](https://linux-hardware.org/?probe=84756c6406) | May 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [9294d16ea5](https://linux-hardware.org/?probe=9294d16ea5) | May 25, 2023 |
| Apple         | MacBookAir4,1               | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| Alienware     | 17 R3                       | [a567b379a1](https://linux-hardware.org/?probe=a567b379a1) | May 24, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d99af6bab2](https://linux-hardware.org/?probe=d99af6bab2) | May 24, 2023 |
| HP            | EliteBook 8570w             | [35a7542634](https://linux-hardware.org/?probe=35a7542634) | May 23, 2023 |
| Lenovo        | ThinkPad T540p 20BF001NU... | [2a770d2eac](https://linux-hardware.org/?probe=2a770d2eac) | May 23, 2023 |
| Apple         | MacBookPro5,5               | [7978c97691](https://linux-hardware.org/?probe=7978c97691) | May 22, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | [5c190a4d57](https://linux-hardware.org/?probe=5c190a4d57) | May 22, 2023 |
| Sony          | VPCF120FD                   | [a438459d06](https://linux-hardware.org/?probe=a438459d06) | May 21, 2023 |
| ASUSTek       | UX430UAR                    | [7815f47a45](https://linux-hardware.org/?probe=7815f47a45) | May 21, 2023 |
| HP            | EliteBook 840 G5            | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| BOSGAME       | B95                         | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| HP            | HDX18                       | [fbfe87f9b5](https://linux-hardware.org/?probe=fbfe87f9b5) | May 19, 2023 |
| HP            | HDX18                       | [a0d050763b](https://linux-hardware.org/?probe=a0d050763b) | May 19, 2023 |
| Acer          | Swift SF316-51              | [663e7fe745](https://linux-hardware.org/?probe=663e7fe745) | May 17, 2023 |
| Dell          | Precision 5540              | [a97a05dd0e](https://linux-hardware.org/?probe=a97a05dd0e) | May 16, 2023 |
| HP            | ProBook 450 G2              | [a399b17822](https://linux-hardware.org/?probe=a399b17822) | May 16, 2023 |
| HP            | EliteBook 8760w             | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| HP            | ProBook 450 G2              | [2ab0709f22](https://linux-hardware.org/?probe=2ab0709f22) | May 14, 2023 |
| Dell          | Precision 5540              | [22e1b4dbd4](https://linux-hardware.org/?probe=22e1b4dbd4) | May 14, 2023 |
| Dell          | Latitude 5490               | [57e94dd4b7](https://linux-hardware.org/?probe=57e94dd4b7) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [5ce272e9ee](https://linux-hardware.org/?probe=5ce272e9ee) | May 13, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [79db0c9b3c](https://linux-hardware.org/?probe=79db0c9b3c) | May 13, 2023 |
| Acer          | Aspire E1-570               | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [71f1904bc6](https://linux-hardware.org/?probe=71f1904bc6) | May 13, 2023 |
| Google        | Kled                        | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| Panasonic     | CF-19-8                     | [1aa7d4071a](https://linux-hardware.org/?probe=1aa7d4071a) | May 12, 2023 |
| System76      | Gazelle                     | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| Samsung       | R430/R480                   | [076f13d198](https://linux-hardware.org/?probe=076f13d198) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c590339049](https://linux-hardware.org/?probe=c590339049) | May 12, 2023 |
| Valve         | Jupiter                     | [9d7e434968](https://linux-hardware.org/?probe=9d7e434968) | May 12, 2023 |
| HP            | Laptop 17-by2xxx            | [21faeddba9](https://linux-hardware.org/?probe=21faeddba9) | May 10, 2023 |
| Google        | Edgar                       | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| Valve         | Jupiter                     | [8cc543c6af](https://linux-hardware.org/?probe=8cc543c6af) | May 09, 2023 |
| HP            | Laptop 15                   | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| ASUSTek       | K53TK                       | [baf643f95f](https://linux-hardware.org/?probe=baf643f95f) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [69dfa20c09](https://linux-hardware.org/?probe=69dfa20c09) | May 07, 2023 |
| Dell          | Inspiron 5521               | [d5f70fc2eb](https://linux-hardware.org/?probe=d5f70fc2eb) | May 07, 2023 |
| HP            | Pavilion dv6                | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| HP            | ENVY TS 17                  | [d18f9c3e77](https://linux-hardware.org/?probe=d18f9c3e77) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [620d5955bb](https://linux-hardware.org/?probe=620d5955bb) | May 06, 2023 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | [21ef45e81c](https://linux-hardware.org/?probe=21ef45e81c) | May 06, 2023 |
| HP            | Pavilion 15                 | [308afd60ea](https://linux-hardware.org/?probe=308afd60ea) | May 06, 2023 |
| HP            | Pavilion 15                 | [2f59970cf9](https://linux-hardware.org/?probe=2f59970cf9) | May 05, 2023 |
| Dell          | Latitude 5401               | [671e11d184](https://linux-hardware.org/?probe=671e11d184) | May 05, 2023 |
| Dell          | Latitude E6520              | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [72336867ab](https://linux-hardware.org/?probe=72336867ab) | May 04, 2023 |
| Lenovo        | G505s 20255                 | [44c5b43b8d](https://linux-hardware.org/?probe=44c5b43b8d) | May 04, 2023 |
| Dell          | XPS 15 9560                 | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [1c26fc22d1](https://linux-hardware.org/?probe=1c26fc22d1) | May 04, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [6a70490cd6](https://linux-hardware.org/?probe=6a70490cd6) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [6d2d5b74d2](https://linux-hardware.org/?probe=6d2d5b74d2) | May 03, 2023 |
| Acer          | Aspire E1-570               | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| HP            | EliteBook 840 G3            | [6f015f949c](https://linux-hardware.org/?probe=6f015f949c) | May 02, 2023 |
| Google        | Kip                         | [19b726ec68](https://linux-hardware.org/?probe=19b726ec68) | May 02, 2023 |
| HP            | EliteBook 840 G2            | [9cee4296b5](https://linux-hardware.org/?probe=9cee4296b5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | [a9406a1851](https://linux-hardware.org/?probe=a9406a1851) | May 02, 2023 |
| Dell          | XPS 15 9570                 | [5b8daf89b4](https://linux-hardware.org/?probe=5b8daf89b4) | May 01, 2023 |
| Dell          | XPS 15 9570                 | [0f39841ca1](https://linux-hardware.org/?probe=0f39841ca1) | May 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1605338d8f](https://linux-hardware.org/?probe=1605338d8f) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Alienware     | m17 R5 AMD                  | [4e665db2b1](https://linux-hardware.org/?probe=4e665db2b1) | May 01, 2023 |
| Acer          | Aspire E1-571               | [e03d5ff056](https://linux-hardware.org/?probe=e03d5ff056) | Apr 30, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [3695c070f9](https://linux-hardware.org/?probe=3695c070f9) | Apr 30, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [2545d9dd31](https://linux-hardware.org/?probe=2545d9dd31) | Apr 29, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [59b9a9ceb3](https://linux-hardware.org/?probe=59b9a9ceb3) | Apr 29, 2023 |
| HP            | G62                         | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek       | N550JX                      | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [346cbe0e48](https://linux-hardware.org/?probe=346cbe0e48) | Apr 28, 2023 |
| HP            | Pavilion dv7                | [afafdbce36](https://linux-hardware.org/?probe=afafdbce36) | Apr 28, 2023 |
| HP            | EliteBook 2560p             | [ce35b62e32](https://linux-hardware.org/?probe=ce35b62e32) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [96006a1098](https://linux-hardware.org/?probe=96006a1098) | Apr 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a3df65a55c](https://linux-hardware.org/?probe=a3df65a55c) | Apr 26, 2023 |
| HP            | EliteBook 840 G3            | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| Acer          | Swift SF313-53              | [b487229ea2](https://linux-hardware.org/?probe=b487229ea2) | Apr 25, 2023 |
| HP            | Pavilion dv7                | [e8318168c4](https://linux-hardware.org/?probe=e8318168c4) | Apr 25, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [cc14ce03b0](https://linux-hardware.org/?probe=cc14ce03b0) | Apr 25, 2023 |
| Dell          | Latitude E7240              | [b72361ca9e](https://linux-hardware.org/?probe=b72361ca9e) | Apr 24, 2023 |
| Alienware     | 13 R2                       | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Acer          | Aspire V5-552P              | [28c276f9da](https://linux-hardware.org/?probe=28c276f9da) | Apr 23, 2023 |
| HP            | Pavilion dv7                | [0ca422761e](https://linux-hardware.org/?probe=0ca422761e) | Apr 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 364       | 10.91%  |
| Ubuntu 18.04                 | 200       | 6%      |
| Ubuntu 22.04                 | 197       | 5.91%   |
| Pop!_OS 22.04                | 88        | 2.64%   |
| Zorin 16                     | 72        | 2.16%   |
| Arch Rolling                 | 65        | 1.95%   |
| OpenMandriva 4.3             | 57        | 1.71%   |
| Fedora 38                    | 56        | 1.68%   |
| Manjaro                      | 54        | 1.62%   |
| Debian 11                    | 54        | 1.62%   |
| Linux Mint 20.3              | 53        | 1.59%   |
| ArcoLinux Rolling            | 51        | 1.53%   |
| OpenMandriva 4.2             | 50        | 1.5%    |
| KDE neon 20.04               | 50        | 1.5%    |
| Arch                         | 48        | 1.44%   |
| Zorin 15                     | 43        | 1.29%   |
| Xubuntu 20.04                | 43        | 1.29%   |
| Linux Mint 21.1              | 42        | 1.26%   |
| Ubuntu 19.10                 | 39        | 1.17%   |
| Linux Mint 19.3              | 39        | 1.17%   |
| Pop!_OS 21.04                | 38        | 1.14%   |
| Pop!_OS 20.04                | 36        | 1.08%   |
| Fedora 37                    | 36        | 1.08%   |
| Linux Mint 21.2              | 35        | 1.05%   |
| Fedora 35                    | 35        | 1.05%   |
| Debian 12                    | 34        | 1.02%   |
| Ubuntu 21.10                 | 33        | 0.99%   |
| Linux Mint 21                | 33        | 0.99%   |
| Linux Mint 20.1              | 32        | 0.96%   |
| Fedora 39                    | 32        | 0.96%   |
| Ubuntu 20.10                 | 31        | 0.93%   |
| EndeavourOS Rolling          | 31        | 0.93%   |
| Linux Mint 20.2              | 30        | 0.9%    |
| Pop!_OS 20.10                | 29        | 0.87%   |
| Ubuntu 23.04                 | 27        | 0.81%   |
| Ubuntu 19.04                 | 27        | 0.81%   |
| openSUSE Tumbleweed-XXXXXXXX | 27        | 0.81%   |
| Linux Mint 20                | 26        | 0.78%   |
| OpenMandriva 23.03           | 24        | 0.72%   |
| OpenMandriva 23.01           | 24        | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 956       | 30.08%  |
| Linux Mint    | 285       | 8.97%   |
| Fedora        | 246       | 7.74%   |
| Pop!_OS       | 206       | 6.48%   |
| OpenMandriva  | 194       | 6.1%    |
| Debian        | 143       | 4.5%    |
| Zorin         | 122       | 3.84%   |
| Manjaro       | 113       | 3.56%   |
| Arch          | 108       | 3.4%    |
| Xubuntu       | 73        | 2.3%    |
| KDE neon      | 72        | 2.27%   |
| Kubuntu       | 63        | 1.98%   |
| ArcoLinux     | 55        | 1.73%   |
| SteamOS       | 52        | 1.64%   |
| Kali          | 38        | 1.2%    |
| ROSA          | 36        | 1.13%   |
| Gentoo        | 34        | 1.07%   |
| EndeavourOS   | 33        | 1.04%   |
| openSUSE      | 31        | 0.98%   |
| Elementary    | 26        | 0.82%   |
| Lubuntu       | 25        | 0.79%   |
| MX            | 24        | 0.76%   |
| Clear Linux   | 19        | 0.6%    |
| Endless       | 17        | 0.53%   |
| BlackPanther  | 16        | 0.5%    |
| Garuda Linux  | 15        | 0.47%   |
| Ubuntu Budgie | 13        | 0.41%   |
| Ubuntu Unity  | 12        | 0.38%   |
| Parrot        | 11        | 0.35%   |
| LMDE          | 11        | 0.35%   |
| Ubuntu MATE   | 9         | 0.28%   |
| Peppermint    | 9         | 0.28%   |
| Alpine        | 9         | 0.28%   |
| Nobara        | 8         | 0.25%   |
| Xero          | 6         | 0.19%   |
| CentOS        | 6         | 0.19%   |
| Ubuntu Studio | 5         | 0.16%   |
| NixOS         | 5         | 0.16%   |
| LinuxFX       | 5         | 0.16%   |
| Artix         | 5         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 51        | 1.38%   |
| 5.10.14-desktop-1omv4002 | 48        | 1.3%    |
| 5.4.0-42-generic         | 45        | 1.22%   |
| 5.11.0-27-generic        | 42        | 1.14%   |
| 5.15.0-56-generic        | 32        | 0.87%   |
| 6.5.0-14-generic         | 28        | 0.76%   |
| 5.3.0-40-generic         | 27        | 0.73%   |
| 6.2.6-desktop-1omv2390   | 24        | 0.65%   |
| 5.15.0-52-generic        | 24        | 0.65%   |
| 5.10.10-64               | 24        | 0.65%   |
| 6.1.1-desktop-1omv2290   | 23        | 0.62%   |
| 5.4.0-29-generic         | 23        | 0.62%   |
| 5.15.0-58-generic        | 23        | 0.62%   |
| 6.2.0-26-generic         | 21        | 0.57%   |
| 5.4.0-52-generic         | 21        | 0.57%   |
| 5.4.0-40-generic         | 21        | 0.57%   |
| 5.0.0-37-generic         | 21        | 0.57%   |
| 5.8.0-7630-generic       | 20        | 0.54%   |
| 5.4.0-58-generic         | 20        | 0.54%   |
| 5.3.0-46-generic         | 20        | 0.54%   |
| 6.4.11-desktop-1omv2390  | 18        | 0.49%   |
| 5.4.0-48-generic         | 18        | 0.49%   |
| 5.4.0-45-generic         | 18        | 0.49%   |
| 5.15.0-41-generic        | 18        | 0.49%   |
| 5.13.0-valve36-1-neptune | 18        | 0.49%   |
| 6.2.6-76060206-generic   | 17        | 0.46%   |
| 5.15.0-71-generic        | 16        | 0.43%   |
| 5.15.0-46-generic        | 16        | 0.43%   |
| 5.4.0-37-generic         | 15        | 0.41%   |
| 5.4.0-26-generic         | 15        | 0.41%   |
| 5.15.0-76-generic        | 15        | 0.41%   |
| 5.15.0-47-generic        | 15        | 0.41%   |
| 5.13.0-7614-generic      | 15        | 0.41%   |
| 5.11.0-40-generic        | 15        | 0.41%   |
| 5.8.0-41-generic         | 14        | 0.38%   |
| 5.4.0-91-generic         | 14        | 0.38%   |
| 5.4.0-47-generic         | 14        | 0.38%   |
| 5.3.0-42-generic         | 14        | 0.38%   |
| 5.15.0-91-generic        | 14        | 0.38%   |
| 5.15.0-60-generic        | 14        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 477       | 13.77%  |
| 5.15.0  | 300       | 8.66%   |
| 5.11.0  | 178       | 5.14%   |
| 5.13.0  | 169       | 4.88%   |
| 5.8.0   | 147       | 4.24%   |
| 5.3.0   | 144       | 4.16%   |
| 4.15.0  | 141       | 4.07%   |
| 6.2.0   | 106       | 3.06%   |
| 5.19.0  | 98        | 2.83%   |
| 5.0.0   | 88        | 2.54%   |
| 5.10.0  | 70        | 2.02%   |
| 6.1.0   | 53        | 1.53%   |
| 5.16.7  | 53        | 1.53%   |
| 6.5.0   | 50        | 1.44%   |
| 5.10.14 | 49        | 1.41%   |
| 4.18.0  | 49        | 1.41%   |
| 6.2.6   | 43        | 1.24%   |
| 6.1.1   | 27        | 0.78%   |
| 5.10.10 | 26        | 0.75%   |
| 4.19.0  | 22        | 0.64%   |
| 6.4.11  | 21        | 0.61%   |
| 6.5.6   | 20        | 0.58%   |
| 5.14.0  | 18        | 0.52%   |
| 6.2.9   | 14        | 0.4%    |
| 6.0.0   | 14        | 0.4%    |
| 5.17.5  | 13        | 0.38%   |
| 5.18.0  | 12        | 0.35%   |
| 5.16.13 | 12        | 0.35%   |
| 6.6.2   | 11        | 0.32%   |
| 6.0.6   | 11        | 0.32%   |
| 5.15.5  | 11        | 0.32%   |
| 4.18.16 | 11        | 0.32%   |
| 6.2.10  | 10        | 0.29%   |
| 6.1.52  | 10        | 0.29%   |
| 6.0.12  | 10        | 0.29%   |
| 6.6.6   | 9         | 0.26%   |
| 5.9.16  | 9         | 0.26%   |
| 5.9.11  | 9         | 0.26%   |
| 5.15.11 | 9         | 0.26%   |
| 6.6.7   | 8         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 519       | 15.22%  |
| 5.15    | 396       | 11.62%  |
| 6.2     | 205       | 6.01%   |
| 5.11    | 203       | 5.95%   |
| 5.8     | 197       | 5.78%   |
| 5.13    | 189       | 5.54%   |
| 5.10    | 189       | 5.54%   |
| 5.3     | 153       | 4.49%   |
| 4.15    | 142       | 4.17%   |
| 6.1     | 131       | 3.84%   |
| 5.19    | 122       | 3.58%   |
| 6.5     | 113       | 3.31%   |
| 5.16    | 106       | 3.11%   |
| 5.0     | 90        | 2.64%   |
| 6.0     | 73        | 2.14%   |
| 6.6     | 67        | 1.97%   |
| 6.4     | 66        | 1.94%   |
| 4.18    | 60        | 1.76%   |
| 5.17    | 49        | 1.44%   |
| 5.9     | 44        | 1.29%   |
| 5.14    | 41        | 1.2%    |
| 5.18    | 38        | 1.11%   |
| 6.3     | 37        | 1.09%   |
| 5.12    | 31        | 0.91%   |
| 4.19    | 29        | 0.85%   |
| 5.6     | 26        | 0.76%   |
| 4.9     | 24        | 0.7%    |
| 5.7     | 23        | 0.67%   |
| 5.5     | 13        | 0.38%   |
| 6.7     | 7         | 0.21%   |
| 4.4     | 7         | 0.21%   |
| 3.10    | 3         | 0.09%   |
| 5.2     | 2         | 0.06%   |
| 5.1     | 2         | 0.06%   |
| 4.8     | 2         | 0.06%   |
| 4.20    | 2         | 0.06%   |
| 4.14    | 2         | 0.06%   |
| 4.1     | 2         | 0.06%   |
| 4.16    | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2955      | 97.14%  |
| i686    | 82        | 2.7%    |
| armv7l  | 3         | 0.1%    |
| aarch64 | 2         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| GNOME                | 1386      | 43.46%  |
| KDE5                 | 583       | 18.28%  |
| Unknown              | 327       | 10.25%  |
| XFCE                 | 252       | 7.9%    |
| X-Cinnamon           | 233       | 7.31%   |
| KDE                  | 76        | 2.38%   |
| MATE                 | 65        | 2.04%   |
| LXDE                 | 40        | 1.25%   |
| Cinnamon             | 36        | 1.13%   |
| LXQt                 | 27        | 0.85%   |
| KDE4                 | 25        | 0.78%   |
| Pantheon             | 24        | 0.75%   |
| i3                   | 24        | 0.75%   |
| Budgie               | 17        | 0.53%   |
| Unity                | 15        | 0.47%   |
| GNOME Flashback      | 10        | 0.31%   |
| DWM                  | 6         | 0.19%   |
| sway                 | 5         | 0.16%   |
| Enlightenment        | 5         | 0.16%   |
| deepin               | 5         | 0.16%   |
| qtile                | 4         | 0.13%   |
| Hyprland             | 4         | 0.13%   |
| xmonad               | 3         | 0.09%   |
| GNOME Classic        | 3         | 0.09%   |
| awesome              | 3         | 0.09%   |
| lightdm-xsession     | 2         | 0.06%   |
| chadwm               | 2         | 0.06%   |
| xsession             | 1         | 0.03%   |
| wmaker-common        | 1         | 0.03%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.03%   |
| spectrwm             | 1         | 0.03%   |
| Jwm                  | 1         | 0.03%   |
| GNOME-Classic        | 1         | 0.03%   |
| bspwm                | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2313      | 73.55%  |
| Wayland | 611       | 19.43%  |
| Unknown | 185       | 5.88%   |
| Tty     | 35        | 1.11%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1576      | 49.53%  |
| SDDM    | 485       | 15.24%  |
| GDM3    | 375       | 11.79%  |
| GDM     | 312       | 9.81%   |
| LightDM | 292       | 9.18%   |
| TDM     | 74        | 2.33%   |
| NODM    | 25        | 0.79%   |
| KDM     | 24        | 0.75%   |
| XDM     | 7         | 0.22%   |
| Ly      | 6         | 0.19%   |
| LXDM    | 4         | 0.13%   |
| LY-DM   | 1         | 0.03%   |
| GREETD  | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_CA   | 1556      | 49.41%  |
| en_US   | 917       | 29.12%  |
| Unknown | 284       | 9.02%   |
| fr_CA   | 210       | 6.67%   |
| C       | 72        | 2.29%   |
| fr_FR   | 37        | 1.17%   |
| en_GB   | 16        | 0.51%   |
| C.UTF8  | 8         | 0.25%   |
| POSIX   | 6         | 0.19%   |
| en_IN   | 4         | 0.13%   |
| en_AU   | 4         | 0.13%   |
| zh_CN   | 3         | 0.1%    |
| pt_BR   | 3         | 0.1%    |
| hu_HU   | 3         | 0.1%    |
| es_ES   | 3         | 0.1%    |
| uk_UA   | 2         | 0.06%   |
| ru_RU   | 2         | 0.06%   |
| pl_PL   | 2         | 0.06%   |
| zh_TW   | 1         | 0.03%   |
| tr_TR   | 1         | 0.03%   |
| ro_RO   | 1         | 0.03%   |
| pa_IN   | 1         | 0.03%   |
| it_IT   | 1         | 0.03%   |
| hr_HR   | 1         | 0.03%   |
| ga_IE   | 1         | 0.03%   |
| es_CL   | 1         | 0.03%   |
| es_AR   | 1         | 0.03%   |
| en_ZA   | 1         | 0.03%   |
| en_NZ   | 1         | 0.03%   |
| en_IE   | 1         | 0.03%   |
| en_FI   | 1         | 0.03%   |
| en_DK   | 1         | 0.03%   |
| de_DE   | 1         | 0.03%   |
| co_FR   | 1         | 0.03%   |
| ar_EG   | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1583      | 50.7%   |
| EFI  | 1539      | 49.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2233      | 71.39%  |
| Btrfs   | 376       | 12.02%  |
| Overlay | 248       | 7.93%   |
| Tmpfs   | 94        | 3.01%   |
| Unknown | 79        | 2.53%   |
| Xfs     | 30        | 0.96%   |
| Zfs     | 28        | 0.9%    |
| Rootfs  | 24        | 0.77%   |
| Ext2    | 8         | 0.26%   |
| Aufs    | 4         | 0.13%   |
| Ext3    | 3         | 0.1%    |
| F2fs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1635      | 52.25%  |
| GPT     | 1188      | 37.97%  |
| MBR     | 306       | 9.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2722      | 87.86%  |
| Yes       | 376       | 12.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2348      | 75.89%  |
| Yes       | 746       | 24.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 632       | 20.79%  |
| Dell                           | 557       | 18.32%  |
| Hewlett-Packard                | 487       | 16.02%  |
| ASUSTek Computer               | 349       | 11.48%  |
| Acer                           | 308       | 10.13%  |
| Apple                          | 131       | 4.31%   |
| Toshiba                        | 112       | 3.68%   |
| MSI                            | 86        | 2.83%   |
| Valve                          | 50        | 1.64%   |
| Google                         | 39        | 1.28%   |
| Sony                           | 38        | 1.25%   |
| Alienware                      | 29        | 0.95%   |
| Samsung Electronics            | 24        | 0.79%   |
| System76                       | 23        | 0.76%   |
| Panasonic                      | 22        | 0.72%   |
| Unknown                        | 21        | 0.69%   |
| Gateway                        | 20        | 0.66%   |
| Gigabyte Technology            | 10        | 0.33%   |
| Fujitsu                        | 10        | 0.33%   |
| Razer                          | 9         | 0.3%    |
| Framework                      | 9         | 0.3%    |
| Notebook                       | 7         | 0.23%   |
| HUAWEI                         | 6         | 0.2%    |
| LG Electronics                 | 5         | 0.16%   |
| Matsushita Electric Industrial | 4         | 0.13%   |
| Intel Client Systems           | 4         | 0.13%   |
| EUROCOM                        | 4         | 0.13%   |
| GPU Company                    | 3         | 0.1%    |
| eMachines                      | 3         | 0.1%    |
| Purism                         | 2         | 0.07%   |
| Motion Computing               | 2         | 0.07%   |
| Intel                          | 2         | 0.07%   |
| Getac                          | 2         | 0.07%   |
| Datto                          | 2         | 0.07%   |
| BOSGAME                        | 2         | 0.07%   |
| AZW                            | 2         | 0.07%   |
| Xplore                         | 1         | 0.03%   |
| VIT                            | 1         | 0.03%   |
| Timi                           | 1         | 0.03%   |
| Teclast                        | 1         | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Valve Jupiter          | 48        | 1.58%   |
| Unknown                | 30        | 0.99%   |
| HP Notebook            | 25        | 0.82%   |
| HP Pavilion g6         | 20        | 0.66%   |
| Acer Aspire A315-21    | 17        | 0.56%   |
| Dell Latitude E6410    | 15        | 0.49%   |
| Dell XPS 15 9500       | 14        | 0.46%   |
| Dell XPS 15 7590       | 14        | 0.46%   |
| Dell Latitude E6420    | 14        | 0.46%   |
| Apple MacBookPro9,2    | 14        | 0.46%   |
| HP Pavilion dv6        | 13        | 0.43%   |
| Apple MacBookPro8,1    | 13        | 0.43%   |
| HP Pavilion Notebook   | 12        | 0.39%   |
| HP Pavilion 15         | 11        | 0.36%   |
| HP EliteBook 8460p     | 10        | 0.33%   |
| HP Pavilion dv7        | 9         | 0.3%    |
| Dell XPS 13 9310       | 9         | 0.3%    |
| Dell Latitude E6540    | 9         | 0.3%    |
| Apple MacBookPro5,5    | 9         | 0.3%    |
| Acer Aspire 5742       | 9         | 0.3%    |
| Toshiba Satellite A200 | 8         | 0.26%   |
| HP Laptop 15-db0xxx    | 8         | 0.26%   |
| HP EliteBook 840 G3    | 8         | 0.26%   |
| Dell XPS 15 9570       | 8         | 0.26%   |
| Dell XPS 13 9360       | 8         | 0.26%   |
| Dell Latitude E6440    | 8         | 0.26%   |
| Dell Latitude E6430    | 8         | 0.26%   |
| Dell Latitude 7490     | 8         | 0.26%   |
| Dell Inspiron 1545     | 8         | 0.26%   |
| Acer Aspire A315-42    | 8         | 0.26%   |
| Toshiba Satellite C650 | 7         | 0.23%   |
| HP EliteBook 840 G1    | 7         | 0.23%   |
| HP 2000                | 7         | 0.23%   |
| Dell XPS 15 9560       | 7         | 0.23%   |
| Dell Latitude E6400    | 7         | 0.23%   |
| Dell Latitude D830     | 7         | 0.23%   |
| System76 Galago Pro    | 6         | 0.2%    |
| HP Laptop 14-fq0xxx    | 6         | 0.2%    |
| HP G60                 | 6         | 0.2%    |
| HP EliteBook 8570w     | 6         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 424       | 13.95%  |
| Acer Aspire        | 235       | 7.73%   |
| Dell Latitude      | 202       | 6.64%   |
| Dell Inspiron      | 138       | 4.54%   |
| HP Pavilion        | 125       | 4.11%   |
| Dell XPS           | 118       | 3.88%   |
| Lenovo IdeaPad     | 104       | 3.42%   |
| HP EliteBook       | 97        | 3.19%   |
| Toshiba Satellite  | 94        | 3.09%   |
| ASUS VivoBook      | 85        | 2.8%    |
| HP Laptop          | 74        | 2.43%   |
| HP ProBook         | 50        | 1.64%   |
| Valve Jupiter      | 48        | 1.58%   |
| ASUS ROG           | 41        | 1.35%   |
| Dell Precision     | 40        | 1.32%   |
| Lenovo Legion      | 30        | 0.99%   |
| Unknown            | 30        | 0.99%   |
| Acer Swift         | 28        | 0.92%   |
| ASUS ZenBook       | 27        | 0.89%   |
| HP Notebook        | 25        | 0.82%   |
| ASUS ASUS          | 23        | 0.76%   |
| HP ENVY            | 21        | 0.69%   |
| Dell Vostro        | 20        | 0.66%   |
| Apple MacBookPro9  | 20        | 0.66%   |
| Apple MacBookPro8  | 18        | 0.59%   |
| Acer Nitro         | 18        | 0.59%   |
| Apple MacBookPro11 | 15        | 0.49%   |
| Apple MacBookPro5  | 14        | 0.46%   |
| HP ZBook           | 13        | 0.43%   |
| HP Stream          | 13        | 0.43%   |
| Dell Studio        | 13        | 0.43%   |
| Lenovo ThinkBook   | 12        | 0.39%   |
| HP Compaq          | 12        | 0.39%   |
| ASUS TUF           | 12        | 0.39%   |
| HP Presario        | 9         | 0.3%    |
| Framework Laptop   | 9         | 0.3%    |
| Dell System        | 9         | 0.3%    |
| Toshiba TECRA      | 8         | 0.26%   |
| Razer Blade        | 8         | 0.26%   |
| Apple MacBookPro6  | 8         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 254       | 8.36%   |
| 2020    | 253       | 8.32%   |
| 2012    | 252       | 8.29%   |
| 2018    | 232       | 7.63%   |
| 2019    | 231       | 7.6%    |
| 2017    | 204       | 6.71%   |
| 2013    | 199       | 6.55%   |
| 2014    | 184       | 6.05%   |
| 2021    | 177       | 5.82%   |
| 2010    | 173       | 5.69%   |
| 2022    | 167       | 5.49%   |
| 2016    | 140       | 4.61%   |
| 2008    | 135       | 4.44%   |
| 2015    | 119       | 3.91%   |
| 2009    | 102       | 3.36%   |
| 2007    | 88        | 2.89%   |
| 2023    | 83        | 2.73%   |
| 2006    | 30        | 0.99%   |
| 2005    | 9         | 0.3%    |
| Unknown | 6         | 0.2%    |
| 2004    | 2         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3040      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2802      | 91.42%  |
| Enabled  | 263       | 8.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2982      | 98.06%  |
| Yes  | 59        | 1.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 909       | 29.44%  |
| 8.01-16.0   | 599       | 19.4%   |
| 3.01-4.0    | 566       | 18.33%  |
| 16.01-24.0  | 542       | 17.55%  |
| 32.01-64.0  | 210       | 6.8%    |
| 1.01-2.0    | 122       | 3.95%   |
| 2.01-3.0    | 47        | 1.52%   |
| 64.01-256.0 | 38        | 1.23%   |
| 24.01-32.0  | 34        | 1.1%    |
| 0.51-1.0    | 19        | 0.62%   |
| 0.01-0.5    | 2         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1166      | 34.41%  |
| 2.01-3.0   | 857       | 25.29%  |
| 4.01-8.0   | 514       | 15.17%  |
| 3.01-4.0   | 457       | 13.48%  |
| 0.51-1.0   | 199       | 5.87%   |
| 8.01-16.0  | 135       | 3.98%   |
| 0.01-0.5   | 42        | 1.24%   |
| 16.01-24.0 | 11        | 0.32%   |
| 24.01-32.0 | 6         | 0.18%   |
| 32.01-64.0 | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2283      | 73.03%  |
| 2      | 687       | 21.98%  |
| 3      | 107       | 3.42%   |
| 0      | 30        | 0.96%   |
| 4      | 16        | 0.51%   |
| 5      | 2         | 0.06%   |
| 7      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1941      | 63.41%  |
| Yes       | 1120      | 36.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2443      | 80.05%  |
| No        | 609       | 19.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2982      | 98.03%  |
| No        | 60        | 1.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2314      | 75.06%  |
| No        | 769       | 24.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 3040      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Toronto         | 320       | 9.98%   |
| Montreal        | 300       | 9.36%   |
| Calgary         | 134       | 4.18%   |
| Vancouver       | 127       | 3.96%   |
| Edmonton        | 105       | 3.28%   |
| Ottawa          | 101       | 3.15%   |
| Québec         | 85        | 2.65%   |
| Winnipeg        | 71        | 2.22%   |
| Mississauga     | 58        | 1.81%   |
| Victoria        | 56        | 1.75%   |
| London          | 40        | 1.25%   |
| Surrey          | 39        | 1.22%   |
| Kitchener       | 36        | 1.12%   |
| Regina          | 35        | 1.09%   |
| Brampton        | 35        | 1.09%   |
| Laval           | 32        | 1%      |
| Burnaby         | 31        | 0.97%   |
| Halifax         | 28        | 0.87%   |
| Oshawa          | 26        | 0.81%   |
| Hamilton        | 26        | 0.81%   |
| Saskatoon       | 24        | 0.75%   |
| Markham         | 23        | 0.72%   |
| Sherbrooke      | 22        | 0.69%   |
| Scarborough     | 22        | 0.69%   |
| Moncton         | 21        | 0.66%   |
| Gatineau        | 20        | 0.62%   |
| Windsor         | 19        | 0.59%   |
| Levis           | 17        | 0.53%   |
| New Westminster | 16        | 0.5%    |
| Kingston        | 16        | 0.5%    |
| Richmond Hill   | 15        | 0.47%   |
| Kelowna         | 15        | 0.47%   |
| Dartmouth       | 15        | 0.47%   |
| Barrie          | 15        | 0.47%   |
| Fredericton     | 14        | 0.44%   |
| Vernon          | 13        | 0.41%   |
| Waterloo        | 12        | 0.37%   |
| Richmond        | 12        | 0.37%   |
| Red Deer        | 12        | 0.37%   |
| Longueuil       | 12        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 582       | 795    | 15.45%  |
| WDC                         | 469       | 587    | 12.45%  |
| Seagate                     | 409       | 532    | 10.86%  |
| Toshiba                     | 287       | 352    | 7.62%   |
| Unknown                     | 250       | 340    | 6.64%   |
| SanDisk                     | 231       | 280    | 6.13%   |
| Kingston                    | 222       | 284    | 5.89%   |
| Intel                       | 154       | 220    | 4.09%   |
| SK hynix                    | 142       | 179    | 3.77%   |
| Hitachi                     | 124       | 141    | 3.29%   |
| HGST                        | 102       | 123    | 2.71%   |
| Crucial                     | 89        | 123    | 2.36%   |
| Micron Technology           | 85        | 109    | 2.26%   |
| Apple                       | 56        | 64     | 1.49%   |
| A-DATA Technology           | 56        | 72     | 1.49%   |
| KIOXIA                      | 41        | 47     | 1.09%   |
| Fujitsu                     | 39        | 57     | 1.04%   |
| SPCC                        | 28        | 42     | 0.74%   |
| Kingston Technology Company | 25        | 28     | 0.66%   |
| LITEONIT                    | 24        | 28     | 0.64%   |
| Unknown                     | 19        | 19     | 0.5%    |
| LITEON                      | 18        | 20     | 0.48%   |
| China                       | 18        | 19     | 0.48%   |
| Phison Electronics          | 17        | 20     | 0.45%   |
| PNY                         | 12        | 22     | 0.32%   |
| Phison                      | 11        | 12     | 0.29%   |
| Silicon Motion              | 10        | 10     | 0.27%   |
| Patriot                     | 9         | 9      | 0.24%   |
| Micron/Crucial Technology   | 9         | 10     | 0.24%   |
| JMicron Technology          | 9         | 11     | 0.24%   |
| Dogfish                     | 9         | 12     | 0.24%   |
| ASMT                        | 9         | 9      | 0.24%   |
| OCZ                         | 8         | 8      | 0.21%   |
| KingFast                    | 7         | 9      | 0.19%   |
| External                    | 7         | 9      | 0.19%   |
| Team                        | 6         | 8      | 0.16%   |
| Corsair                     | 6         | 6      | 0.16%   |
| Union Memory (Shenzhen)     | 5         | 6      | 0.13%   |
| UMIS                        | 5         | 5      | 0.13%   |
| TO Exter                    | 5         | 6      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 53        | 1.35%   |
| Toshiba MQ01ABD100 1TB                             | 50        | 1.27%   |
| Unknown MMC Card  64GB                             | 47        | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 43        | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB                     | 41        | 1.04%   |
| Unknown MMC Card  32GB                             | 37        | 0.94%   |
| HGST HTS721010A9E630 1TB                           | 31        | 0.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 28        | 0.71%   |
| Samsung SSD 860 EVO 500GB                          | 26        | 0.66%   |
| Kingston SA400S37480G 480GB SSD                    | 25        | 0.64%   |
| Samsung SSD 860 EVO 1TB                            | 24        | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 24        | 0.61%   |
| Unknown MMC Card  16GB                             | 21        | 0.53%   |
| Seagate ST9500325AS 500GB                          | 21        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                    | 21        | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 20        | 0.51%   |
| Toshiba MQ04ABF100 1TB                             | 20        | 0.51%   |
| Seagate ST1000LX015-1U7172 1TB                     | 20        | 0.51%   |
| Samsung NVMe SSD Drive 512GB                       | 20        | 0.51%   |
| Intel NVMe SSD Drive 512GB                         | 19        | 0.48%   |
| HGST HTS725050A7E630 500GB                         | 19        | 0.48%   |
| Unknown                                            | 19        | 0.48%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 18        | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 18        | 0.46%   |
| Unknown MMC Card  128GB                            | 18        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                    | 18        | 0.46%   |
| Samsung SSD 850 EVO 250GB                          | 18        | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                   | 18        | 0.46%   |
| Seagate ST500LM021-1KJ152 500GB                    | 17        | 0.43%   |
| SanDisk NVMe SSD Drive 1TB                         | 17        | 0.43%   |
| Samsung SSD 860 EVO 250GB                          | 17        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB                        | 17        | 0.43%   |
| SK hynix NVMe SSD Drive 512GB                      | 16        | 0.41%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 16        | 0.41%   |
| Intel SSDPEKNU512GZ 512GB                          | 16        | 0.41%   |
| Intel SSD 660P Series 1024GB                       | 16        | 0.41%   |
| HGST HTS541010A9E680 1TB                           | 16        | 0.41%   |
| Toshiba MQ01ABF050 500GB                           | 15        | 0.38%   |
| Samsung SSD 850 EVO 500GB                          | 15        | 0.38%   |
| Seagate Expansion 1TB                              | 14        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 394       | 506    | 31.65%  |
| WDC                 | 300       | 361    | 24.1%   |
| Toshiba             | 225       | 283    | 18.07%  |
| Hitachi             | 124       | 141    | 9.96%   |
| HGST                | 102       | 123    | 8.19%   |
| Fujitsu             | 39        | 57     | 3.13%   |
| Samsung Electronics | 16        | 31     | 1.29%   |
| Apple               | 9         | 9      | 0.72%   |
| Unknown             | 8         | 9      | 0.64%   |
| External            | 7         | 9      | 0.56%   |
| TO Exter            | 5         | 6      | 0.4%    |
| JMicron Technology  | 5         | 6      | 0.4%    |
| Maxone              | 3         | 3      | 0.24%   |
| USB 3.0             | 1         | 2      | 0.08%   |
| StoreJet            | 1         | 1      | 0.08%   |
| SINTECHI            | 1         | 1      | 0.08%   |
| LaCie               | 1         | 1      | 0.08%   |
| Inateck             | 1         | 1      | 0.08%   |
| Generic-            | 1         | 1      | 0.08%   |
| DAS                 | 1         | 5      | 0.08%   |
| ACASIS              | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 274       | 370    | 23.76%  |
| Kingston            | 183       | 228    | 15.87%  |
| SanDisk             | 99        | 118    | 8.59%   |
| WDC                 | 82        | 115    | 7.11%   |
| Crucial             | 80        | 107    | 6.94%   |
| Intel               | 49        | 67     | 4.25%   |
| A-DATA Technology   | 48        | 62     | 4.16%   |
| Apple               | 35        | 36     | 3.04%   |
| Micron Technology   | 33        | 50     | 2.86%   |
| SPCC                | 27        | 41     | 2.34%   |
| LITEONIT            | 24        | 28     | 2.08%   |
| SK hynix            | 22        | 29     | 1.91%   |
| Toshiba             | 20        | 23     | 1.73%   |
| China               | 18        | 19     | 1.56%   |
| LITEON              | 14        | 15     | 1.21%   |
| PNY                 | 12        | 22     | 1.04%   |
| Patriot             | 9         | 9      | 0.78%   |
| Dogfish             | 9         | 12     | 0.78%   |
| OCZ                 | 8         | 8      | 0.69%   |
| Seagate             | 7         | 10     | 0.61%   |
| ASMT                | 7         | 7      | 0.61%   |
| Team                | 5         | 7      | 0.43%   |
| KingSpec            | 5         | 7      | 0.43%   |
| Timetec             | 4         | 11     | 0.35%   |
| SABRENT             | 4         | 4      | 0.35%   |
| Mushkin             | 4         | 7      | 0.35%   |
| Corsair             | 4         | 4      | 0.35%   |
| Transcend           | 3         | 4      | 0.26%   |
| Super Talent        | 3         | 5      | 0.26%   |
| OWC                 | 3         | 7      | 0.26%   |
| NGFF                | 3         | 3      | 0.26%   |
| KingFast            | 3         | 3      | 0.26%   |
| KingDian            | 3         | 3      | 0.26%   |
| Unknown             | 3         | 3      | 0.26%   |
| Zheino              | 2         | 2      | 0.17%   |
| WDC WDS             | 2         | 2      | 0.17%   |
| Vaseky              | 2         | 2      | 0.17%   |
| Lexar               | 2         | 3      | 0.17%   |
| Kingchuxing         | 2         | 2      | 0.17%   |
| Hewlett-Packard     | 2         | 3      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1193      | 1557   | 33.58%  |
| SSD     | 1053      | 1503   | 29.64%  |
| NVMe    | 1003      | 1367   | 28.23%  |
| MMC     | 255       | 348    | 7.18%   |
| Unknown | 49        | 58     | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2028      | 2891   | 58.83%  |
| NVMe | 1002      | 1364   | 29.07%  |
| MMC  | 255       | 348    | 7.4%    |
| SAS  | 162       | 230    | 4.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1452      | 1983   | 65.2%   |
| 0.51-1.0   | 704       | 972    | 31.61%  |
| 1.01-2.0   | 53        | 76     | 2.38%   |
| 4.01-10.0  | 14        | 24     | 0.63%   |
| 3.01-4.0   | 4         | 5      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 841       | 25.92%  |
| 251-500        | 840       | 25.89%  |
| 501-1000       | 545       | 16.8%   |
| 1-20           | 290       | 8.94%   |
| 51-100         | 210       | 6.47%   |
| 1001-2000      | 193       | 5.95%   |
| 21-50          | 120       | 3.7%    |
| Unknown        | 92        | 2.84%   |
| More than 3000 | 71        | 2.19%   |
| 2001-3000      | 42        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1397      | 41.64%  |
| 21-50          | 625       | 18.63%  |
| 51-100         | 413       | 12.31%  |
| 101-250        | 403       | 12.01%  |
| 251-500        | 230       | 6.86%   |
| 501-1000       | 120       | 3.58%   |
| Unknown        | 92        | 2.74%   |
| 1001-2000      | 47        | 1.4%    |
| More than 3000 | 17        | 0.51%   |
| 2001-3000      | 11        | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 10        | 11     | 5.29%   |
| Toshiba MQ01ABD100 1TB              | 6         | 8      | 3.17%   |
| HGST HTS541010A9E680 1TB            | 6         | 6      | 3.17%   |
| Seagate ST9500325AS 500GB           | 5         | 5      | 2.65%   |
| HGST HTS545050A7E680 500GB          | 5         | 5      | 2.65%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 4      | 2.12%   |
| Seagate ST500LM000-1EJ162 500GB     | 4         | 4      | 2.12%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 2.12%   |
| Toshiba MK3261GSYN 320GB            | 3         | 3      | 1.59%   |
| Seagate ST9500420AS 500GB           | 3         | 3      | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 3      | 1.59%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 2         | 2      | 1.06%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 1.06%   |
| Toshiba MK6465GSX 640GB             | 2         | 2      | 1.06%   |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 1.06%   |
| Toshiba MK2035GSS 200GB             | 2         | 2      | 1.06%   |
| Seagate ST9750420AS 752GB           | 2         | 2      | 1.06%   |
| Seagate ST9500420ASG 500GB          | 2         | 2      | 1.06%   |
| Seagate ST9320423AS 320GB           | 2         | 4      | 1.06%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 1.06%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 1.06%   |
| Seagate ST320LT020-9YG142 320GB     | 2         | 2      | 1.06%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB | 2         | 2      | 1.06%   |
| Seagate ST1000LM014-1EJ164 1TB      | 2         | 2      | 1.06%   |
| Hitachi HTS725050A9A364 500GB       | 2         | 2      | 1.06%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 2      | 1.06%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 2      | 1.06%   |
| HGST HTS725050A7E630 500GB          | 2         | 3      | 1.06%   |
| A-DATA Technology SX900 256GB SSD   | 2         | 2      | 1.06%   |
| WDC WD7500BPKT-60PK4T0 752GB        | 1         | 1      | 0.53%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.53%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 1      | 0.53%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 0.53%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 0.53%   |
| WDC WD2500BEVT-75A23T0 250GB        | 1         | 1      | 0.53%   |
| WDC WD2500BEVT-00ZCT0 250GB         | 1         | 1      | 0.53%   |
| WDC WD2500BEVS-75UST0 250GB         | 1         | 1      | 0.53%   |
| WDC WD1600BEVS-22RST0 160GB         | 1         | 1      | 0.53%   |
| WDC WD10SPZX-16Z10T0 1TB            | 1         | 1      | 0.53%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 54        | 57     | 28.57%  |
| Toshiba                     | 28        | 30     | 14.81%  |
| Hitachi                     | 21        | 21     | 11.11%  |
| WDC                         | 20        | 23     | 10.58%  |
| HGST                        | 19        | 20     | 10.05%  |
| Samsung Electronics         | 9         | 19     | 4.76%   |
| Intel                       | 7         | 7      | 3.7%    |
| A-DATA Technology           | 5         | 5      | 2.65%   |
| SK hynix                    | 3         | 3      | 1.59%   |
| Kingston                    | 3         | 3      | 1.59%   |
| SanDisk                     | 2         | 2      | 1.06%   |
| Fujitsu                     | 2         | 11     | 1.06%   |
| Crucial                     | 2         | 2      | 1.06%   |
| Apple                       | 2         | 2      | 1.06%   |
| UMIS                        | 1         | 1      | 0.53%   |
| Timetec                     | 1         | 6      | 0.53%   |
| Super Talent                | 1         | 1      | 0.53%   |
| OCZ                         | 1         | 1      | 0.53%   |
| Micron Technology           | 1         | 1      | 0.53%   |
| LITEONIT                    | 1         | 1      | 0.53%   |
| LITEON                      | 1         | 1      | 0.53%   |
| LaCie                       | 1         | 1      | 0.53%   |
| Kingston Technology Company | 1         | 1      | 0.53%   |
| KingSpec                    | 1         | 1      | 0.53%   |
| Corsair                     | 1         | 1      | 0.53%   |
| ASMT                        | 1         | 1      | 0.53%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 57     | 37.5%   |
| Toshiba             | 26        | 28     | 18.06%  |
| Hitachi             | 21        | 21     | 14.58%  |
| HGST                | 19        | 20     | 13.19%  |
| WDC                 | 18        | 20     | 12.5%   |
| Samsung Electronics | 2         | 10     | 1.39%   |
| Fujitsu             | 2         | 11     | 1.39%   |
| LaCie               | 1         | 1      | 0.69%   |
| Apple               | 1         | 1      | 0.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 142       | 169    | 75.94%  |
| SSD  | 35        | 42     | 18.72%  |
| NVMe | 10        | 11     | 5.35%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM160HC 160GB | 1         | 5      | 50%     |
| LITEON CA3-8D512 512GB            | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 5      | 50%     |
| LITEON              | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1918      | 3069   | 59.6%   |
| Works    | 1112      | 1535   | 34.56%  |
| Malfunc  | 186       | 222    | 5.78%   |
| Failed   | 2         | 7      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1966      | 56.72%  |
| AMD                            | 445       | 12.84%  |
| Samsung Electronics            | 336       | 9.69%   |
| SanDisk                        | 207       | 5.97%   |
| SK hynix                       | 116       | 3.35%   |
| Kingston Technology Company    | 61        | 1.76%   |
| Micron Technology              | 53        | 1.53%   |
| KIOXIA                         | 44        | 1.27%   |
| Toshiba America Info Systems   | 43        | 1.24%   |
| Nvidia                         | 42        | 1.21%   |
| Phison Electronics             | 31        | 0.89%   |
| Micron/Crucial Technology      | 18        | 0.52%   |
| Silicon Motion                 | 13        | 0.38%   |
| ADATA Technology               | 13        | 0.38%   |
| Union Memory (Shenzhen)        | 12        | 0.35%   |
| Apple                          | 9         | 0.26%   |
| Marvell Technology Group       | 8         | 0.23%   |
| Lite-On Technology             | 8         | 0.23%   |
| Solid State Storage Technology | 7         | 0.2%    |
| Realtek Semiconductor          | 6         | 0.17%   |
| Lenovo                         | 4         | 0.12%   |
| ASMedia Technology             | 4         | 0.12%   |
| Solidigm                       | 3         | 0.09%   |
| O2 Micro                       | 3         | 0.09%   |
| JMicron Technology             | 3         | 0.09%   |
| Shenzhen Longsys Electronics   | 2         | 0.06%   |
| Seagate Technology             | 2         | 0.06%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.06%   |
| INNOGRIT                       | 2         | 0.06%   |
| Yangtze Memory Technologies    | 1         | 0.03%   |
| OCZ Technology Group           | 1         | 0.03%   |
| Biwin Storage Technology       | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 365       | 9.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 231       | 6.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 195       | 5.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 179       | 4.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 163       | 4.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 133       | 3.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 111       | 2.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 107       | 2.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 92        | 2.46%   |
| Intel Volume Management Device NVMe RAID Controller                              | 90        | 2.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 90        | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 79        | 2.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 72        | 1.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 72        | 1.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 66        | 1.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 60        | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 59        | 1.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 55        | 1.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 54        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 54        | 1.45%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 47        | 1.26%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 47        | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 40        | 1.07%   |
| Intel SSD 660P Series                                                            | 34        | 0.91%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 31        | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 30        | 0.8%    |
| Intel SSD 670p Series [Keystone Harbor]                                          | 29        | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 27        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 26        | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 26        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 24        | 0.64%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 23        | 0.62%   |
| Nvidia MCP79 AHCI Controller                                                     | 21        | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 20        | 0.54%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 19        | 0.51%   |
| SK hynix BC511 NVMe SSD                                                          | 19        | 0.51%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 19        | 0.51%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 19        | 0.51%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 19        | 0.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 19        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2021      | 56.83%  |
| NVMe | 1002      | 28.18%  |
| RAID | 305       | 8.58%   |
| IDE  | 228       | 6.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 2393      | 78.72%  |
| AMD     | 642       | 21.12%  |
| ARM     | 3         | 0.1%    |
| Unknown | 2         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 53        | 1.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 50        | 1.64%   |
| AMD Custom APU 0405                           | 50        | 1.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 48        | 1.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 45        | 1.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 38        | 1.25%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 37        | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 35        | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 34        | 1.12%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 34        | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 31        | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 29        | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 29        | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 28        | 0.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 27        | 0.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 0.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 24        | 0.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 24        | 0.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 24        | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 24        | 0.79%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 23        | 0.76%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 22        | 0.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 20        | 0.66%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 20        | 0.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 18        | 0.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 18        | 0.59%   |
| Intel 12th Gen Core i7-12700H                 | 18        | 0.59%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 16        | 0.53%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 16        | 0.53%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 16        | 0.53%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 16        | 0.53%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 15        | 0.49%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 15        | 0.49%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 15        | 0.49%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 15        | 0.49%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 15        | 0.49%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 15        | 0.49%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 15        | 0.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 740       | 24.33%  |
| Intel Core i7           | 705       | 23.18%  |
| Other                   | 316       | 10.39%  |
| Intel Core i3           | 167       | 5.49%   |
| Intel Core 2 Duo        | 162       | 5.33%   |
| Intel Celeron           | 122       | 4.01%   |
| AMD Ryzen 7             | 118       | 3.88%   |
| AMD Ryzen 5             | 80        | 2.63%   |
| Intel Pentium           | 63        | 2.07%   |
| AMD A6                  | 58        | 1.91%   |
| Intel Atom              | 48        | 1.58%   |
| AMD A10                 | 42        | 1.38%   |
| Intel Pentium Dual-Core | 30        | 0.99%   |
| AMD A4                  | 30        | 0.99%   |
| Intel Pentium Dual      | 25        | 0.82%   |
| AMD Ryzen 3             | 25        | 0.82%   |
| AMD Ryzen 9             | 23        | 0.76%   |
| AMD A8                  | 23        | 0.76%   |
| Intel Genuine           | 21        | 0.69%   |
| Intel Core i9           | 17        | 0.56%   |
| Intel Core 2            | 15        | 0.49%   |
| AMD E                   | 15        | 0.49%   |
| AMD E2                  | 14        | 0.46%   |
| AMD E1                  | 14        | 0.46%   |
| AMD A12                 | 13        | 0.43%   |
| AMD Ryzen 5 PRO         | 11        | 0.36%   |
| Intel Pentium Silver    | 10        | 0.33%   |
| AMD Turion 64 X2 Mobile | 10        | 0.33%   |
| AMD Athlon X2           | 10        | 0.33%   |
| AMD Athlon              | 9         | 0.3%    |
| Intel Xeon              | 8         | 0.26%   |
| AMD Ryzen 7 PRO         | 8         | 0.26%   |
| AMD Athlon 64 X2        | 7         | 0.23%   |
| AMD Phenom II           | 6         | 0.2%    |
| Intel Celeron M         | 5         | 0.16%   |
| AMD Turion 64 Mobile    | 5         | 0.16%   |
| AMD C-50                | 5         | 0.16%   |
| AMD Athlon II           | 5         | 0.16%   |
| Intel Pentium M         | 4         | 0.13%   |
| AMD C-60                | 4         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1534      | 50.39%  |
| 4       | 934       | 30.68%  |
| 6       | 204       | 6.7%    |
| 8       | 186       | 6.11%   |
| 1       | 70        | 2.3%    |
| 14      | 49        | 1.61%   |
| 10      | 30        | 0.99%   |
| 12      | 23        | 0.76%   |
| 16      | 7         | 0.23%   |
| 24      | 3         | 0.1%    |
| 3       | 2         | 0.07%   |
| 7       | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 3039      | 99.97%  |
| Unknown | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2226      | 73.1%   |
| 1       | 817       | 26.83%  |
| 12      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2972      | 97.57%  |
| 32-bit         | 39        | 1.28%   |
| Unknown        | 33        | 1.08%   |
| 64-bit         | 2         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1063      | 33.59%  |
| 0x306a9    | 168       | 5.31%   |
| 0x206a7    | 163       | 5.15%   |
| 0x40651    | 88        | 2.78%   |
| 0x1067a    | 88        | 2.78%   |
| 0x806ea    | 78        | 2.46%   |
| 0x906ea    | 76        | 2.4%    |
| 0x20655    | 72        | 2.27%   |
| 0x406e3    | 63        | 1.99%   |
| 0x806e9    | 62        | 1.96%   |
| 0x306c3    | 61        | 1.93%   |
| 0x806ec    | 56        | 1.77%   |
| 0x306d4    | 54        | 1.71%   |
| 0x6fd      | 49        | 1.55%   |
| 0xa0652    | 48        | 1.52%   |
| 0x20652    | 42        | 1.33%   |
| 0x806c1    | 39        | 1.23%   |
| 0x906e9    | 36        | 1.14%   |
| 0x906a3    | 36        | 1.14%   |
| 0x0a50000c | 34        | 1.07%   |
| 0x06001119 | 33        | 1.04%   |
| 0x506e3    | 30        | 0.95%   |
| 0x30678    | 29        | 0.92%   |
| 0x06006705 | 27        | 0.85%   |
| 0x08108102 | 26        | 0.82%   |
| 0x706e5    | 25        | 0.79%   |
| 0x10676    | 25        | 0.79%   |
| 0x406c4    | 23        | 0.73%   |
| 0x08108109 | 23        | 0.73%   |
| 0x406c3    | 21        | 0.66%   |
| 0x05000119 | 21        | 0.66%   |
| 0x07030105 | 20        | 0.63%   |
| 0x08600104 | 18        | 0.57%   |
| 0x03000027 | 18        | 0.57%   |
| 0x106e5    | 17        | 0.54%   |
| 0x806eb    | 16        | 0.51%   |
| 0x08608103 | 16        | 0.51%   |
| 0x010000c8 | 16        | 0.51%   |
| 0x806d1    | 15        | 0.47%   |
| 0x706a8    | 14        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 498       | 16.35%  |
| IvyBridge        | 234       | 7.68%   |
| Haswell          | 233       | 7.65%   |
| SandyBridge      | 217       | 7.12%   |
| Unknown          | 184       | 6.04%   |
| Westmere         | 151       | 4.96%   |
| Penryn           | 149       | 4.89%   |
| Skylake          | 134       | 4.4%    |
| Silvermont       | 102       | 3.35%   |
| Core             | 97        | 3.18%   |
| Broadwell        | 88        | 2.89%   |
| Excavator        | 86        | 2.82%   |
| TigerLake        | 81        | 2.66%   |
| CometLake        | 79        | 2.59%   |
| Alderlake Hybrid | 76        | 2.5%    |
| Zen+             | 71        | 2.33%   |
| Zen 3            | 64        | 2.1%    |
| Zen 2            | 59        | 1.94%   |
| Icelake          | 55        | 1.81%   |
| Piledriver       | 43        | 1.41%   |
| Goldmont plus    | 42        | 1.38%   |
| Bobcat           | 36        | 1.18%   |
| Puma             | 34        | 1.12%   |
| K8 Hammer        | 29        | 0.95%   |
| P6               | 26        | 0.85%   |
| Zen              | 25        | 0.82%   |
| K10 Llano        | 24        | 0.79%   |
| Nehalem          | 23        | 0.76%   |
| K10              | 23        | 0.76%   |
| Bonnell          | 23        | 0.76%   |
| Jaguar           | 21        | 0.69%   |
| Goldmont         | 17        | 0.56%   |
| K8 & K10 hybrid  | 13        | 0.43%   |
| Steamroller      | 4         | 0.13%   |
| Tremont          | 3         | 0.1%    |
| NetBurst         | 1         | 0.03%   |
| Gracemont        | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2148      | 57.94%  |
| Nvidia | 794       | 21.42%  |
| AMD    | 765       | 20.64%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 207       | 5.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 195       | 5.08%   |
| Intel UHD Graphics 620                                                                   | 131       | 3.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 123       | 3.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 121       | 3.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 107       | 2.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 102       | 2.66%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 89        | 2.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 82        | 2.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 77        | 2%      |
| Intel HD Graphics 620                                                                    | 77        | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 77        | 2%      |
| Intel HD Graphics 5500                                                                   | 74        | 1.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 70        | 1.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 66        | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 63        | 1.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 55        | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 55        | 1.43%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 53        | 1.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 51        | 1.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 51        | 1.33%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 48        | 1.25%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 46        | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 42        | 1.09%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 39        | 1.02%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 39        | 1.02%   |
| Intel HD Graphics 630                                                                    | 39        | 1.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 39        | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 38        | 0.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 0.91%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 35        | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 34        | 0.89%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 33        | 0.86%   |
| Intel HD Graphics 530                                                                    | 30        | 0.78%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 28        | 0.73%   |
| AMD Lucienne                                                                             | 28        | 0.73%   |
| AMD Rembrandt [Radeon 680M]                                                              | 24        | 0.62%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 23        | 0.6%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 23        | 0.6%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 23        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1535      | 50.26%  |
| 1 x AMD            | 592       | 19.38%  |
| Intel + Nvidia     | 526       | 17.22%  |
| 1 x Nvidia         | 198       | 6.48%   |
| Intel + AMD        | 70        | 2.29%   |
| AMD + Nvidia       | 66        | 2.16%   |
| 2 x AMD            | 39        | 1.28%   |
| Other              | 11        | 0.36%   |
| 2 x Intel          | 11        | 0.36%   |
| 2 x Nvidia         | 5         | 0.16%   |
| Intel + 2 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2593      | 84.02%  |
| Proprietary | 400       | 12.96%  |
| Unknown     | 93        | 3.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2089      | 66.76%  |
| 0.01-0.5   | 416       | 13.29%  |
| 1.01-2.0   | 247       | 7.89%   |
| 0.51-1.0   | 136       | 4.35%   |
| 3.01-4.0   | 134       | 4.28%   |
| 7.01-8.0   | 47        | 1.5%    |
| 5.01-6.0   | 44        | 1.41%   |
| 2.01-3.0   | 8         | 0.26%   |
| 8.01-16.0  | 8         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 655       | 18.82%  |
| LG Display              | 459       | 13.19%  |
| Samsung Electronics     | 407       | 11.7%   |
| Chimei Innolux          | 371       | 10.66%  |
| BOE                     | 342       | 9.83%   |
| Sharp                   | 147       | 4.22%   |
| Apple                   | 128       | 3.68%   |
| Lenovo                  | 103       | 2.96%   |
| Dell                    | 100       | 2.87%   |
| Goldstar                | 86        | 2.47%   |
| Chi Mei Optoelectronics | 84        | 2.41%   |
| PANDA                   | 53        | 1.52%   |
| Hewlett-Packard         | 48        | 1.38%   |
| Acer                    | 45        | 1.29%   |
| ASUSTek Computer        | 36        | 1.03%   |
| LG Philips              | 35        | 1.01%   |
| Valve                   | 34        | 0.98%   |
| BenQ                    | 32        | 0.92%   |
| Ancor Communications    | 28        | 0.8%    |
| Toshiba                 | 27        | 0.78%   |
| InfoVision              | 26        | 0.75%   |
| ViewSonic               | 18        | 0.52%   |
| Sony                    | 18        | 0.52%   |
| CSO                     | 15        | 0.43%   |
| Philips                 | 12        | 0.34%   |
| Panasonic               | 12        | 0.34%   |
| AOC                     | 11        | 0.32%   |
| TMX                     | 10        | 0.29%   |
| Quanta Display          | 9         | 0.26%   |
| HannStar                | 9         | 0.26%   |
| HKC                     | 7         | 0.2%    |
| CPT                     | 7         | 0.2%    |
| Seiko/Epson             | 6         | 0.17%   |
| Insignia                | 6         | 0.17%   |
| LGD                     | 5         | 0.14%   |
| IBM                     | 5         | 0.14%   |
| MSI                     | 4         | 0.11%   |
| Gigabyte Technology     | 4         | 0.11%   |
| Unknown                 | 3         | 0.09%   |
| SANYO                   | 3         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 35        | 0.99%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 32        | 0.91%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 32        | 0.91%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.62%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 22        | 0.62%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 21        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 0.57%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 19        | 0.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 18        | 0.51%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 17        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 17        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 15        | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.42%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 15        | 0.42%   |
| Toshiba TV TSB0206 1920x1080                                             | 14        | 0.4%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 14        | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 14        | 0.4%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 13        | 0.37%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 13        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 13        | 0.37%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 12        | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 12        | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 12        | 0.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 12        | 0.34%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 11        | 0.31%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 11        | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 11        | 0.31%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 11        | 0.31%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 11        | 0.31%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 10        | 0.28%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 10        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.28%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 10        | 0.28%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 10        | 0.28%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 9         | 0.25%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 9         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 9         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 9         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1190      | 36.17%  |
| 1366x768 (WXGA)    | 967       | 29.39%  |
| 1600x900 (HD+)     | 187       | 5.68%   |
| 1280x800 (WXGA)    | 168       | 5.11%   |
| 3840x2160 (4K)     | 142       | 4.32%   |
| 2560x1440 (QHD)    | 92        | 2.8%    |
| 1920x1200 (WUXGA)  | 81        | 2.46%   |
| 1440x900 (WXGA+)   | 74        | 2.25%   |
| 1680x1050 (WSXGA+) | 64        | 1.95%   |
| 2880x1800          | 42        | 1.28%   |
| 800x1280           | 36        | 1.09%   |
| 2560x1600          | 34        | 1.03%   |
| 3440x1440          | 20        | 0.61%   |
| 1280x1024 (SXGA)   | 18        | 0.55%   |
| 3840x2400          | 17        | 0.52%   |
| 3200x1800 (QHD+)   | 17        | 0.52%   |
| 2560x1080          | 16        | 0.49%   |
| 1024x600           | 15        | 0.46%   |
| 1024x768 (XGA)     | 12        | 0.36%   |
| 2256x1504          | 11        | 0.33%   |
| 1920x540           | 10        | 0.3%    |
| 1360x768           | 10        | 0.3%    |
| 3200x2000          | 8         | 0.24%   |
| Unknown            | 7         | 0.21%   |
| 3456x2160          | 5         | 0.15%   |
| 1920x1280          | 5         | 0.15%   |
| 3840x1080          | 4         | 0.12%   |
| 1680x945           | 4         | 0.12%   |
| 3000x2000          | 3         | 0.09%   |
| 2560x1700          | 3         | 0.09%   |
| 3840x1200          | 2         | 0.06%   |
| 3840x1100          | 2         | 0.06%   |
| 3072x1920          | 2         | 0.06%   |
| 2288x1287          | 2         | 0.06%   |
| 2160x1440          | 2         | 0.06%   |
| 2160x1350          | 2         | 0.06%   |
| 1600x1200          | 2         | 0.06%   |
| 1280x768           | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 1024x576           | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1430      | 41.12%  |
| 13      | 456       | 13.11%  |
| 14      | 405       | 11.64%  |
| 17      | 241       | 6.93%   |
| 27      | 117       | 3.36%   |
| 24      | 102       | 2.93%   |
| 23      | 77        | 2.21%   |
| 21      | 76        | 2.19%   |
| 11      | 65        | 1.87%   |
| 12      | 64        | 1.84%   |
| Unknown | 54        | 1.55%   |
| 31      | 39        | 1.12%   |
| 16      | 38        | 1.09%   |
| 34      | 36        | 1.04%   |
| 7       | 34        | 0.98%   |
| 22      | 31        | 0.89%   |
| 18      | 28        | 0.81%   |
| 20      | 22        | 0.63%   |
| 19      | 21        | 0.6%    |
| 10      | 16        | 0.46%   |
| 84      | 15        | 0.43%   |
| 74      | 14        | 0.4%    |
| 72      | 14        | 0.4%    |
| 54      | 11        | 0.32%   |
| 32      | 10        | 0.29%   |
| 40      | 8         | 0.23%   |
| 25      | 8         | 0.23%   |
| 86      | 5         | 0.14%   |
| 37      | 5         | 0.14%   |
| 48      | 4         | 0.12%   |
| 43      | 3         | 0.09%   |
| 42      | 3         | 0.09%   |
| 28      | 3         | 0.09%   |
| 26      | 3         | 0.09%   |
| 8       | 3         | 0.09%   |
| 60      | 2         | 0.06%   |
| 58      | 2         | 0.06%   |
| 52      | 2         | 0.06%   |
| 49      | 2         | 0.06%   |
| 39      | 2         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2017      | 58.55%  |
| 201-300     | 385       | 11.18%  |
| 351-400     | 314       | 9.11%   |
| 501-600     | 274       | 7.95%   |
| 401-500     | 167       | 4.85%   |
| 601-700     | 55        | 1.6%    |
| Unknown     | 54        | 1.57%   |
| 701-800     | 46        | 1.34%   |
| 1501-2000   | 44        | 1.28%   |
| 1-100       | 36        | 1.04%   |
| 1001-1500   | 30        | 0.87%   |
| 801-900     | 15        | 0.44%   |
| 901-1000    | 5         | 0.15%   |
| 101-200     | 3         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2375      | 77.59%  |
| 16/10   | 494       | 16.14%  |
| 3/2     | 36        | 1.18%   |
| 21/9    | 36        | 1.18%   |
| 0.67    | 32        | 1.05%   |
| Unknown | 30        | 0.98%   |
| 5/4     | 19        | 0.62%   |
| 4/3     | 16        | 0.52%   |
| 0.56    | 5         | 0.16%   |
| 6/5     | 4         | 0.13%   |
| 32/9    | 4         | 0.13%   |
| 0.62    | 3         | 0.1%    |
| 3.40    | 2         | 0.07%   |
| 1.96    | 2         | 0.07%   |
| 3.73    | 1         | 0.03%   |
| 3.33    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1410      | 40.74%  |
| 81-90          | 679       | 19.62%  |
| 201-250        | 229       | 6.62%   |
| 121-130        | 202       | 5.84%   |
| 71-80          | 165       | 4.77%   |
| 301-350        | 118       | 3.41%   |
| 351-500        | 86        | 2.48%   |
| More than 1000 | 68        | 1.96%   |
| 151-200        | 68        | 1.96%   |
| 51-60          | 67        | 1.94%   |
| 61-70          | 61        | 1.76%   |
| Unknown        | 54        | 1.56%   |
| 111-120        | 50        | 1.44%   |
| 1-40           | 39        | 1.13%   |
| 131-140        | 37        | 1.07%   |
| 141-150        | 34        | 0.98%   |
| 251-300        | 32        | 0.92%   |
| 501-1000       | 27        | 0.78%   |
| 91-100         | 19        | 0.55%   |
| 41-50          | 16        | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1181      | 34.91%  |
| 101-120       | 1089      | 32.19%  |
| 51-100        | 604       | 17.85%  |
| 161-240       | 256       | 7.57%   |
| More than 240 | 131       | 3.87%   |
| 1-50          | 68        | 2.01%   |
| Unknown       | 54        | 1.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2431      | 78.07%  |
| 2     | 512       | 16.44%  |
| 0     | 91        | 2.92%   |
| 3     | 78        | 2.5%    |
| 4     | 2         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1658      | 35.22%  |
| Realtek Semiconductor                 | 1384      | 29.4%   |
| Qualcomm Atheros                      | 665       | 14.12%  |
| Broadcom                              | 371       | 7.88%   |
| Broadcom Limited                      | 123       | 2.61%   |
| MediaTek                              | 77        | 1.64%   |
| Marvell Technology Group              | 51        | 1.08%   |
| ASIX Electronics                      | 50        | 1.06%   |
| Nvidia                                | 35        | 0.74%   |
| TP-Link                               | 34        | 0.72%   |
| Ralink                                | 27        | 0.57%   |
| Ralink Technology                     | 21        | 0.45%   |
| Linksys                               | 19        | 0.4%    |
| D-Link                                | 19        | 0.4%    |
| Samsung Electronics                   | 18        | 0.38%   |
| DisplayLink                           | 18        | 0.38%   |
| Lenovo                                | 15        | 0.32%   |
| Qualcomm                              | 14        | 0.3%    |
| Sierra Wireless                       | 12        | 0.25%   |
| ASUSTek Computer                      | 12        | 0.25%   |
| Qualcomm Atheros Communications       | 11        | 0.23%   |
| NetGear                               | 7         | 0.15%   |
| Google                                | 7         | 0.15%   |
| AMD                                   | 6         | 0.13%   |
| Hewlett-Packard                       | 4         | 0.08%   |
| Dell                                  | 4         | 0.08%   |
| D-Link System                         | 4         | 0.08%   |
| Apple                                 | 4         | 0.08%   |
| Research In Motion                    | 3         | 0.06%   |
| JMicron Technology                    | 3         | 0.06%   |
| Xiaomi                                | 2         | 0.04%   |
| U-Blox                                | 2         | 0.04%   |
| TRENDnet                              | 2         | 0.04%   |
| Microsoft                             | 2         | 0.04%   |
| LG Electronics                        | 2         | 0.04%   |
| Edimax Technology                     | 2         | 0.04%   |
| Aquantia                              | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| STMicroelectronics                    | 1         | 0.02%   |
| SEGGER                                | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 742       | 12.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 271       | 4.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 176       | 3.03%   |
| Intel Wireless 8265 / 8275                                             | 144       | 2.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 123       | 2.12%   |
| Intel Wireless 7260                                                    | 121       | 2.08%   |
| Intel Wi-Fi 6 AX200                                                    | 119       | 2.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 113       | 1.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 101       | 1.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 100       | 1.72%   |
| Intel Wireless 7265                                                    | 95        | 1.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 87        | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 86        | 1.48%   |
| Intel Wireless 8260                                                    | 84        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 72        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 66        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 64        | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 61        | 1.05%   |
| Intel Wi-Fi 6 AX201                                                    | 59        | 1.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 59        | 1.01%   |
| Intel 82577LM Gigabit Network Connection                               | 59        | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                                  | 57        | 0.98%   |
| Intel Centrino Ultimate-N 6300                                         | 55        | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 51        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 48        | 0.83%   |
| Intel Ethernet Connection I218-LM                                      | 48        | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                          | 47        | 0.81%   |
| Intel Ethernet Connection I217-LM                                      | 45        | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 40        | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 40        | 0.69%   |
| Intel Ethernet Connection I219-LM                                      | 38        | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 38        | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 38        | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 37        | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 37        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 35        | 0.6%    |
| Intel Wireless 3165                                                    | 35        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 34        | 0.58%   |
| Intel Centrino Advanced-N 6235                                         | 34        | 0.58%   |
| Intel Centrino Advanced-N 6200                                         | 34        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1574      | 49.56%  |
| Qualcomm Atheros                      | 544       | 17.13%  |
| Realtek Semiconductor                 | 430       | 13.54%  |
| Broadcom                              | 292       | 9.19%   |
| Broadcom Limited                      | 78        | 2.46%   |
| MediaTek                              | 74        | 2.33%   |
| TP-Link                               | 31        | 0.98%   |
| Ralink                                | 27        | 0.85%   |
| Ralink Technology                     | 21        | 0.66%   |
| D-Link                                | 18        | 0.57%   |
| Linksys                               | 17        | 0.54%   |
| Sierra Wireless                       | 12        | 0.38%   |
| Qualcomm                              | 12        | 0.38%   |
| ASUSTek Computer                      | 12        | 0.38%   |
| Qualcomm Atheros Communications       | 11        | 0.35%   |
| NetGear                               | 7         | 0.22%   |
| D-Link System                         | 4         | 0.13%   |
| TRENDnet                              | 2         | 0.06%   |
| Edimax Technology                     | 2         | 0.06%   |
| Dell                                  | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| Qualcomm Technologies                 | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Microsoft                             | 1         | 0.03%   |
| Marvell Technology Group              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 144       | 4.5%    |
| Intel Wireless 7260                                                     | 121       | 3.78%   |
| Intel Wi-Fi 6 AX200                                                     | 119       | 3.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 113       | 3.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 101       | 3.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 100       | 3.12%   |
| Intel Wireless 7265                                                     | 95        | 2.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 87        | 2.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 86        | 2.68%   |
| Intel Wireless 8260                                                     | 84        | 2.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 72        | 2.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 66        | 2.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 64        | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                         | 61        | 1.9%    |
| Intel Wi-Fi 6 AX201                                                     | 59        | 1.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 59        | 1.84%   |
| Intel Centrino Ultimate-N 6300                                          | 55        | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 51        | 1.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 48        | 1.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 40        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 40        | 1.25%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 38        | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 37        | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 37        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 35        | 1.09%   |
| Intel Wireless 3165                                                     | 35        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 34        | 1.06%   |
| Intel Centrino Advanced-N 6235                                          | 34        | 1.06%   |
| Intel Centrino Advanced-N 6200                                          | 34        | 1.06%   |
| Intel Centrino Wireless-N 2230                                          | 33        | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 32        | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 32        | 1%      |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 31        | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 30        | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 29        | 0.91%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 29        | 0.91%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 29        | 0.91%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 29        | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                           | 29        | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 1181      | 46.5%   |
| Intel                    | 715       | 28.15%  |
| Qualcomm Atheros         | 202       | 7.95%   |
| Broadcom                 | 165       | 6.5%    |
| Marvell Technology Group | 50        | 1.97%   |
| Broadcom Limited         | 50        | 1.97%   |
| ASIX Electronics         | 50        | 1.97%   |
| Nvidia                   | 34        | 1.34%   |
| Samsung Electronics      | 18        | 0.71%   |
| DisplayLink              | 18        | 0.71%   |
| Lenovo                   | 14        | 0.55%   |
| Google                   | 7         | 0.28%   |
| TP-Link                  | 4         | 0.16%   |
| Hewlett-Packard          | 4         | 0.16%   |
| Apple                    | 4         | 0.16%   |
| Research In Motion       | 3         | 0.12%   |
| JMicron Technology       | 3         | 0.12%   |
| Xiaomi                   | 2         | 0.08%   |
| Qualcomm                 | 2         | 0.08%   |
| MediaTek                 | 2         | 0.08%   |
| Linksys                  | 2         | 0.08%   |
| LG Electronics           | 2         | 0.08%   |
| Aquantia                 | 2         | 0.08%   |
| Motorola PCS             | 1         | 0.04%   |
| Microsoft                | 1         | 0.04%   |
| HTC (High Tech Computer) | 1         | 0.04%   |
| HMD Global               | 1         | 0.04%   |
| D-Link                   | 1         | 0.04%   |
| Attansic Technology      | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 742       | 28.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 271       | 10.52%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 176       | 6.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 123       | 4.77%   |
| Intel 82577LM Gigabit Network Connection                               | 59        | 2.29%   |
| Intel Ethernet Connection (4) I219-LM                                  | 57        | 2.21%   |
| Intel Ethernet Connection I218-LM                                      | 48        | 1.86%   |
| ASIX AX88179 Gigabit Ethernet                                          | 47        | 1.82%   |
| Intel Ethernet Connection I217-LM                                      | 45        | 1.75%   |
| Intel Ethernet Connection I219-LM                                      | 38        | 1.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 38        | 1.48%   |
| Intel Ethernet Connection (4) I219-V                                   | 33        | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 31        | 1.2%    |
| Intel 82567LM Gigabit Network Connection                               | 30        | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                                  | 29        | 1.13%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 24        | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 23        | 0.89%   |
| Realtek RTL8125 2.5GbE Controller                                      | 21        | 0.82%   |
| Nvidia MCP79 Ethernet                                                  | 20        | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 19        | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 18        | 0.7%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 18        | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 18        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 17        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 16        | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 16        | 0.62%   |
| Intel Ethernet Connection I219-V                                       | 16        | 0.62%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 15        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 15        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                                   | 15        | 0.58%   |
| Intel Ethernet Connection (6) I219-LM                                  | 14        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                                  | 14        | 0.54%   |
| Intel 82579V Gigabit Network Connection                                | 14        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 13        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 13        | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 13        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 11        | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 11        | 0.43%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 11        | 0.43%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 11        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2982      | 54.68%  |
| Ethernet | 2438      | 44.7%   |
| Modem    | 28        | 0.51%   |
| Unknown  | 6         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2511      | 76.91%  |
| Ethernet | 754       | 23.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2221      | 72.94%  |
| 1     | 755       | 24.79%  |
| 0     | 43        | 1.41%   |
| 3     | 25        | 0.82%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2547      | 82.48%  |
| Yes  | 541       | 17.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1137      | 48.32%  |
| Broadcom                        | 177       | 7.52%   |
| Realtek Semiconductor           | 171       | 7.27%   |
| Qualcomm Atheros Communications | 165       | 7.01%   |
| IMC Networks                    | 161       | 6.84%   |
| Lite-On Technology              | 125       | 5.31%   |
| Apple                           | 115       | 4.89%   |
| Foxconn / Hon Hai               | 104       | 4.42%   |
| Dell                            | 42        | 1.78%   |
| Hewlett-Packard                 | 37        | 1.57%   |
| Cambridge Silicon Radio         | 33        | 1.4%    |
| Toshiba                         | 15        | 0.64%   |
| Ralink                          | 15        | 0.64%   |
| ASUSTek Computer                | 15        | 0.64%   |
| Alps Electric                   | 11        | 0.47%   |
| USI                             | 4         | 0.17%   |
| Realtek                         | 4         | 0.17%   |
| MediaTek                        | 3         | 0.13%   |
| TP-Link                         | 2         | 0.08%   |
| Taiyo Yuden                     | 2         | 0.08%   |
| SINO WEALTH                     | 2         | 0.08%   |
| Logitech                        | 2         | 0.08%   |
| Dynex                           | 2         | 0.08%   |
| Ralink Technology               | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Primax Electronics              | 1         | 0.04%   |
| Marvell Semiconductor           | 1         | 0.04%   |
| Kensington                      | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Foxconn International           | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 482       | 20.42%  |
| Intel AX201 Bluetooth                                                               | 190       | 8.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 127       | 5.38%   |
| Realtek Bluetooth Radio                                                             | 126       | 5.34%   |
| Intel AX200 Bluetooth                                                               | 116       | 4.92%   |
| Intel Bluetooth Device                                                              | 99        | 4.19%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 89        | 3.77%   |
| IMC Networks Bluetooth Radio                                                        | 86        | 3.64%   |
| Apple Bluetooth Host Controller                                                     | 73        | 3.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 63        | 2.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 57        | 2.42%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 47        | 1.99%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 38        | 1.61%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 36        | 1.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 33        | 1.4%    |
| IMC Networks Wireless_Device                                                        | 32        | 1.36%   |
| Apple Bluetooth USB Host Controller                                                 | 32        | 1.36%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 31        | 1.31%   |
| Intel AX210 Bluetooth                                                               | 29        | 1.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 27        | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 25        | 1.06%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 21        | 0.89%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 20        | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 18        | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 18        | 0.76%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 18        | 0.76%   |
| Broadcom HP Portable SoftSailing                                                    | 18        | 0.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 17        | 0.72%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 16        | 0.68%   |
| Ralink RT3290 Bluetooth                                                             | 15        | 0.64%   |
| Dell DW375 Bluetooth Module                                                         | 15        | 0.64%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 15        | 0.64%   |
| IMC Networks Bluetooth Device                                                       | 14        | 0.59%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 14        | 0.59%   |
| IMC Networks BCM20702A0                                                             | 12        | 0.51%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.51%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 12        | 0.51%   |
| Lite-On Bluetooth Device                                                            | 11        | 0.47%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 10        | 0.42%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 9         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2335      | 61.59%  |
| AMD                                  | 709       | 18.7%   |
| Nvidia                               | 481       | 12.69%  |
| C-Media Electronics                  | 28        | 0.74%   |
| Realtek Semiconductor                | 26        | 0.69%   |
| Logitech                             | 26        | 0.69%   |
| GN Netcom                            | 16        | 0.42%   |
| Lenovo                               | 14        | 0.37%   |
| Plantronics                          | 11        | 0.29%   |
| JMTek                                | 8         | 0.21%   |
| Hewlett-Packard                      | 8         | 0.21%   |
| SteelSeries ApS                      | 7         | 0.18%   |
| Razer USA                            | 7         | 0.18%   |
| Apple                                | 7         | 0.18%   |
| Kingston Technology                  | 6         | 0.16%   |
| Focusrite-Novation                   | 6         | 0.16%   |
| Blue Microphones                     | 6         | 0.16%   |
| ASUSTek Computer                     | 6         | 0.16%   |
| Sony                                 | 5         | 0.13%   |
| Creative Technology                  | 5         | 0.13%   |
| Texas Instruments                    | 4         | 0.11%   |
| Sennheiser Communications            | 4         | 0.11%   |
| No brand                             | 4         | 0.11%   |
| Generalplus Technology               | 4         | 0.11%   |
| Corsair                              | 4         | 0.11%   |
| Native Instruments                   | 3         | 0.08%   |
| Dell                                 | 3         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.05%   |
| Synaptics                            | 2         | 0.05%   |
| Samson Technologies                  | 2         | 0.05%   |
| Panasonic (Matsushita)               | 2         | 0.05%   |
| KTMicro                              | 2         | 0.05%   |
| GYROCOM C&C                          | 2         | 0.05%   |
| BR23                                 | 2         | 0.05%   |
| Audio-Technica                       | 2         | 0.05%   |
| XMOS                                 | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |
| Shure                                | 1         | 0.03%   |
| SAVITECH                             | 1         | 0.03%   |
| RODE Microphones                     | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 309       | 6.71%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 273       | 5.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 262       | 5.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 187       | 4.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 173       | 3.76%   |
| AMD FCH Azalia Controller                                                                         | 138       | 3%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 128       | 2.78%   |
| Intel 8 Series HD Audio Controller                                                                | 126       | 2.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 125       | 2.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 125       | 2.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 125       | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 107       | 2.32%   |
| AMD Kabini HDMI/DP Audio                                                                          | 90        | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 89        | 1.93%   |
| Intel Broadwell-U Audio Controller                                                                | 88        | 1.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 87        | 1.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 84        | 1.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 84        | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 81        | 1.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 75        | 1.63%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 72        | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 71        | 1.54%   |
| Intel Comet Lake PCH cAVS                                                                         | 70        | 1.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 70        | 1.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 64        | 1.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 56        | 1.22%   |
| AMD High Definition Audio Controller                                                              | 51        | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 48        | 1.04%   |
| Nvidia Audio device                                                                               | 47        | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 45        | 0.98%   |
| Intel CM238 HD Audio Controller                                                                   | 45        | 0.98%   |
| AMD Trinity HDMI Audio Controller                                                                 | 43        | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 42        | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 42        | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 42        | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 41        | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 41        | 0.89%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 39        | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 36        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 35        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 523       | 27.17%  |
| SK hynix                                         | 477       | 24.78%  |
| Micron Technology                                | 256       | 13.3%   |
| Kingston                                         | 145       | 7.53%   |
| Unknown                                          | 136       | 7.06%   |
| Crucial                                          | 82        | 4.26%   |
| G.Skill                                          | 39        | 2.03%   |
| Elpida                                           | 39        | 2.03%   |
| Nanya Technology                                 | 33        | 1.71%   |
| Ramaxel Technology                               | 31        | 1.61%   |
| A-DATA Technology                                | 28        | 1.45%   |
| Corsair                                          | 27        | 1.4%    |
| Unknown                                          | 15        | 0.78%   |
| Patriot                                          | 10        | 0.52%   |
| Timetec                                          | 9         | 0.47%   |
| Goldkey                                          | 6         | 0.31%   |
| ff                                               | 6         | 0.31%   |
| 4ea5                                             | 6         | 0.31%   |
| Unknown (ABCD)                                   | 5         | 0.26%   |
| Toshiba                                          | 5         | 0.26%   |
| Team                                             | 5         | 0.26%   |
| PNY                                              | 3         | 0.16%   |
| Neo Forza                                        | 3         | 0.16%   |
| ASint Technology                                 | 3         | 0.16%   |
| Unknown (7F7F7F94FFFFFFFF)                       | 2         | 0.1%    |
| SHARETRONIC                                      | 2         | 0.1%    |
| fef5                                             | 2         | 0.1%    |
| CSX                                              | 2         | 0.1%    |
| Axiom                                            | 2         | 0.1%    |
| Unknown (268C)                                   | 1         | 0.05%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.05%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.05%   |
| Unknown (0x48594D503132355336344350382D53362020) | 1         | 0.05%   |
| Unknown (0x0C26)                                 | 1         | 0.05%   |
| Unknown (0x0080)                                 | 1         | 0.05%   |
| Unknown (08AE)                                   | 1         | 0.05%   |
| Unknown (000080B30080)                           | 1         | 0.05%   |
| Unifosa                                          | 1         | 0.05%   |
| Transcend                                        | 1         | 0.05%   |
| Smart                                            | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 36        | 1.77%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 22        | 1.08%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 21        | 1.03%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 21        | 1.03%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 20        | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 19        | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 19        | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 18        | 0.88%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 17        | 0.83%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 16        | 0.79%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 16        | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 16        | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 15        | 0.74%   |
| Unknown                                                             | 15        | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 14        | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 14        | 0.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 14        | 0.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 14        | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 14        | 0.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 14        | 0.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 13        | 0.64%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 13        | 0.64%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 13        | 0.64%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 13        | 0.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 12        | 0.59%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 12        | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 12        | 0.59%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 12        | 0.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 12        | 0.59%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 11        | 0.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 11        | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 11        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 11        | 0.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 0.49%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 10        | 0.49%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s             | 10        | 0.49%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 9         | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 9         | 0.44%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 9         | 0.44%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 9         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 667       | 41.71%  |
| DDR3    | 571       | 35.71%  |
| LPDDR4  | 82        | 5.13%   |
| LPDDR3  | 73        | 4.57%   |
| DDR2    | 70        | 4.38%   |
| DDR5    | 55        | 3.44%   |
| SDRAM   | 26        | 1.63%   |
| LPDDR5  | 23        | 1.44%   |
| Unknown | 19        | 1.19%   |
| DDR     | 11        | 0.69%   |
| DRAM    | 2         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1401      | 87.78%  |
| Row Of Chips    | 152       | 9.52%   |
| Chip            | 19        | 1.19%   |
| Unknown         | 17        | 1.07%   |
| DIMM            | 6         | 0.38%   |
| Proprietary Car | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 710       | 39.75%  |
| 4096  | 504       | 28.22%  |
| 16384 | 244       | 13.66%  |
| 2048  | 220       | 12.32%  |
| 1024  | 54        | 3.02%   |
| 32768 | 47        | 2.63%   |
| 512   | 4         | 0.22%   |
| 256   | 2         | 0.11%   |
| 65536 | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 385       | 22.15%  |
| 2667    | 300       | 17.26%  |
| 3200    | 291       | 16.74%  |
| 2400    | 129       | 7.42%   |
| 2133    | 98        | 5.64%   |
| 1334    | 89        | 5.12%   |
| 1333    | 67        | 3.86%   |
| 4800    | 41        | 2.36%   |
| 667     | 38        | 2.19%   |
| 1067    | 37        | 2.13%   |
| 4267    | 32        | 1.84%   |
| 1867    | 27        | 1.55%   |
| Unknown | 27        | 1.55%   |
| 6400    | 25        | 1.44%   |
| 3266    | 19        | 1.09%   |
| 800     | 18        | 1.04%   |
| 4266    | 15        | 0.86%   |
| 4199    | 15        | 0.86%   |
| 1066    | 14        | 0.81%   |
| 8400    | 13        | 0.75%   |
| 5600    | 13        | 0.75%   |
| 975     | 12        | 0.69%   |
| 533     | 9         | 0.52%   |
| 3733    | 8         | 0.46%   |
| 2048    | 4         | 0.23%   |
| 1639    | 3         | 0.17%   |
| 400     | 2         | 0.12%   |
| 6000    | 1         | 0.06%   |
| 2933    | 1         | 0.06%   |
| 2666    | 1         | 0.06%   |
| 1866    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |
| 933     | 1         | 0.06%   |
| 333     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 11        | 29.73%  |
| Brother Industries  | 10        | 27.03%  |
| Samsung Electronics | 6         | 16.22%  |
| Canon               | 6         | 16.22%  |
| Xerox               | 1         | 2.7%    |
| QinHeng Electronics | 1         | 2.7%    |
| Prolific Technology | 1         | 2.7%    |
| Dymo-CoStar         | 1         | 2.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Samsung M2070 Series                            | 2         | 5.13%   |
| HP OfficeJet 3830 series                        | 2         | 5.13%   |
| Canon PIXMA MG2900 Series                       | 2         | 5.13%   |
| Brother Printer                                 | 2         | 5.13%   |
| Xerox B210                                      | 1         | 2.56%   |
| Samsung ML-2510 Series                          | 1         | 2.56%   |
| Samsung M267x 287x Series                       | 1         | 2.56%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 2.56%   |
| Samsung M2020 Series                            | 1         | 2.56%   |
| QinHeng CH340S                                  | 1         | 2.56%   |
| Prolific PL2305 Parallel Port                   | 1         | 2.56%   |
| HP LaserJet Professional P1102w                 | 1         | 2.56%   |
| HP LaserJet 1160 series                         | 1         | 2.56%   |
| HP LaserJet 1020                                | 1         | 2.56%   |
| HP LaserJet 1018                                | 1         | 2.56%   |
| HP ENVY 5000 series                             | 1         | 2.56%   |
| HP ENVY 4520 series                             | 1         | 2.56%   |
| HP Deskjet 3050A                                | 1         | 2.56%   |
| HP DeskJet 2700 series                          | 1         | 2.56%   |
| HP DeskJet 2600 series                          | 1         | 2.56%   |
| Dymo-CoStar LabelWriter 450                     | 1         | 2.56%   |
| Canon MG2100 series                             | 1         | 2.56%   |
| Canon MF3010                                    | 1         | 2.56%   |
| Canon MF230 Series UFRII LT                     | 1         | 2.56%   |
| Canon G3060 series                              | 1         | 2.56%   |
| Brother MFC-L2730DW series                      | 1         | 2.56%   |
| Brother MFC-L2717DW                             | 1         | 2.56%   |
| Brother MFC-J6945DW                             | 1         | 2.56%   |
| Brother MFC-J480DW                              | 1         | 2.56%   |
| Brother MFC-9330CDW                             | 1         | 2.56%   |
| Brother HL-L2390DW                              | 1         | 2.56%   |
| Brother HL-2270DW Laser Printer                 | 1         | 2.56%   |
| Brother HL-2240 series                          | 1         | 2.56%   |
| Brother HL-2170W series                         | 1         | 2.56%   |
| Brother DCP-L2550DW series                      | 1         | 2.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 85.71%  |
| AGFA-Gevaert NV | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220            | 2         | 28.57%  |
| Canon CanoScan LiDE 120            | 2         | 28.57%  |
| Canon CanoScan LiDE 700F           | 1         | 14.29%  |
| Canon CanoScan 4200F               | 1         | 14.29%  |
| AGFA-Gevaert NV SnapScan 1212U (?) | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 604       | 23.15%  |
| Microdia                               | 279       | 10.69%  |
| IMC Networks                           | 276       | 10.58%  |
| Realtek Semiconductor                  | 204       | 7.82%   |
| Sunplus Innovation Technology          | 158       | 6.06%   |
| Bison Electronics                      | 133       | 5.1%    |
| Quanta                                 | 119       | 4.56%   |
| Apple                                  | 107       | 4.1%    |
| Suyin                                  | 105       | 4.02%   |
| Acer                                   | 86        | 3.3%    |
| Cheng Uei Precision Industry (Foxlink) | 72        | 2.76%   |
| Logitech                               | 57        | 2.18%   |
| Lite-On Technology                     | 52        | 1.99%   |
| Luxvisions Innotech Limited            | 41        | 1.57%   |
| Syntek                                 | 34        | 1.3%    |
| Ricoh                                  | 32        | 1.23%   |
| Silicon Motion                         | 31        | 1.19%   |
| Sonix Technology                       | 25        | 0.96%   |
| Lenovo                                 | 25        | 0.96%   |
| Importek                               | 22        | 0.84%   |
| Samsung Electronics                    | 20        | 0.77%   |
| Alcor Micro                            | 18        | 0.69%   |
| Microsoft                              | 13        | 0.5%    |
| ALi                                    | 10        | 0.38%   |
| Primax Electronics                     | 8         | 0.31%   |
| OmniVision Technologies                | 8         | 0.31%   |
| Z-Star Microelectronics                | 6         | 0.23%   |
| LG Electronics                         | 4         | 0.15%   |
| 8SSC21D67422V1SR3AV5KW1                | 4         | 0.15%   |
| YGTek                                  | 3         | 0.11%   |
| USB Camera                             | 3         | 0.11%   |
| Sunplus Technology                     | 3         | 0.11%   |
| MacroSilicon                           | 3         | 0.11%   |
| AVerMedia Technologies                 | 3         | 0.11%   |
| 8SSC21K12273V1SR33X2817                | 3         | 0.11%   |
| 8SSC20F27114V1SR0BK1X4S                | 3         | 0.11%   |
| WaveRider Communications               | 2         | 0.08%   |
| SunplusIT                              | 2         | 0.08%   |
| ShineTech                              | 2         | 0.08%   |
| HRY                                    | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 143       | 5.45%   |
| Microdia Integrated_Webcam_HD                       | 125       | 4.76%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 104       | 3.96%   |
| Realtek Integrated_Webcam_HD                        | 87        | 3.32%   |
| IMC Networks Integrated Camera                      | 59        | 2.25%   |
| Chicony HD WebCam                                   | 56        | 2.13%   |
| Sunplus Integrated_Webcam_HD                        | 37        | 1.41%   |
| Microdia Integrated Webcam                          | 35        | 1.33%   |
| Bison Integrated Camera                             | 35        | 1.33%   |
| Apple Built-in iSight                               | 34        | 1.3%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 33        | 1.26%   |
| Apple FaceTime HD Camera                            | 33        | 1.26%   |
| Sunplus HD WebCam                                   | 28        | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 28        | 1.07%   |
| Lite-On Integrated Camera                           | 27        | 1.03%   |
| Acer Integrated Camera                              | 25        | 0.95%   |
| Chicony HP TrueVision HD                            | 24        | 0.91%   |
| Quanta VGA WebCam                                   | 23        | 0.88%   |
| Quanta HD User Facing                               | 23        | 0.88%   |
| Chicony VGA WebCam                                  | 22        | 0.84%   |
| Chicony HP HD Camera                                | 22        | 0.84%   |
| Syntek Integrated Camera                            | 21        | 0.8%    |
| Acer SunplusIT Integrated Camera                    | 21        | 0.8%    |
| Samsung Galaxy series, misc. (MTP mode)             | 20        | 0.76%   |
| Quanta HP TrueVision HD Camera                      | 20        | 0.76%   |
| Chicony Integrated Camera (1280x720@30)             | 19        | 0.72%   |
| Realtek USB Camera                                  | 18        | 0.69%   |
| Chicony USB2.0 HD UVC WebCam                        | 18        | 0.69%   |
| Chicony TOSHIBA Web Camera - HD                     | 18        | 0.69%   |
| Bison Lenovo EasyCamera                             | 18        | 0.69%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 17        | 0.65%   |
| Microdia Laptop_Integrated_Webcam_HD                | 17        | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 17        | 0.65%   |
| Chicony USB 2.0 Camera                              | 17        | 0.65%   |
| Chicony HD User Facing                              | 17        | 0.65%   |
| Sonix USB2.0 HD UVC WebCam                          | 16        | 0.61%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 16        | 0.61%   |
| Logitech HD Pro Webcam C920                         | 15        | 0.57%   |
| IMC Networks VGA UVC WebCam                         | 15        | 0.57%   |
| Bison BisonCam,NB Pro                               | 15        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 229       | 39.01%  |
| Synaptics                          | 127       | 21.64%  |
| Shenzhen Goodix Technology         | 52        | 8.86%   |
| Elan Microelectronics              | 51        | 8.69%   |
| Upek                               | 40        | 6.81%   |
| AuthenTec                          | 38        | 6.47%   |
| LighTuning Technology              | 24        | 4.09%   |
| STMicroelectronics                 | 17        | 2.9%    |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.51%   |
| Focal-systems.Corp                 | 3         | 0.51%   |
| Microsoft                          | 1         | 0.17%   |
| HOLTEK                             | 1         | 0.17%   |
| Dell                               | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 53        | 9.03%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 7.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 40        | 6.81%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 39        | 6.64%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 38        | 6.47%   |
| Elan ELAN:Fingerprint                                                      | 37        | 6.3%    |
| Validity Sensors Synaptics WBDI                                            | 28        | 4.77%   |
| Shenzhen Goodix FingerPrint                                                | 28        | 4.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 3.41%   |
| Validity Sensors VFS491                                                    | 20        | 3.41%   |
| STMicroelectronics Fingerprint Reader                                      | 17        | 2.9%    |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 2.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 2.56%   |
| AuthenTec AES2810                                                          | 15        | 2.56%   |
| Elan ELAN:ARM-M4                                                           | 14        | 2.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 2.21%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 1.87%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 9         | 1.53%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 1.53%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 1.53%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 1.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.19%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 1.19%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.02%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 0.85%   |
| Synaptics  WBDI                                                            | 5         | 0.85%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 0.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.68%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 0.68%   |
| Synaptics TouchPad                                                         | 4         | 0.68%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.51%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.51%   |
| Synaptics WBDI                                                             | 3         | 0.51%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.51%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 0.51%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.51%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 3         | 0.51%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 105       | 47.51%  |
| Alcor Micro               | 44        | 19.91%  |
| O2 Micro                  | 27        | 12.22%  |
| Upek                      | 25        | 11.31%  |
| Lenovo                    | 13        | 5.88%   |
| Gemalto (was Gemplus)     | 4         | 1.81%   |
| Yubico.com                | 1         | 0.45%   |
| Giesecke & Devrient       | 1         | 0.45%   |
| Aladdin Knowledge Systems | 1         | 0.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 54        | 24.43%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 43        | 19.46%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 25        | 11.31%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 10.41%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 9.5%    |
| Broadcom 5880                                                                | 15        | 6.79%   |
| Broadcom 58200                                                               | 14        | 6.33%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 5.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.81%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 1.81%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.45%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.45%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.45%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1909      | 61.24%  |
| 1     | 949       | 30.45%  |
| 2     | 204       | 6.54%   |
| 3     | 32        | 1.03%   |
| 4     | 10        | 0.32%   |
| 5     | 7         | 0.22%   |
| 6     | 5         | 0.16%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 574       | 38.47%  |
| Graphics card            | 271       | 18.16%  |
| Chipcard                 | 203       | 13.61%  |
| Net/wireless             | 141       | 9.45%   |
| Multimedia controller    | 84        | 5.63%   |
| Storage                  | 39        | 2.61%   |
| Communication controller | 38        | 2.55%   |
| Camera                   | 33        | 2.21%   |
| Bluetooth                | 28        | 1.88%   |
| Sound                    | 23        | 1.54%   |
| Net/ethernet             | 15        | 1.01%   |
| Modem                    | 12        | 0.8%    |
| Card reader              | 10        | 0.67%   |
| Network                  | 5         | 0.34%   |
| Flash memory             | 5         | 0.34%   |
| Storage/raid             | 4         | 0.27%   |
| Storage/ide              | 2         | 0.13%   |
| Firewire controller      | 2         | 0.13%   |
| Unclassified device      | 1         | 0.07%   |
| Tv card                  | 1         | 0.07%   |
| Dvb card                 | 1         | 0.07%   |

