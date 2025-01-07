Linux in Malaysia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Malaysia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Malaysia/Desktop/README.md) and [notebooks](/Location/Malaysia/Notebook/README.md).

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

Total: 969

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [735622d487](https://linux-hardware.org/?probe=735622d487) | Jan 05, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [51be04fcd7](https://linux-hardware.org/?probe=51be04fcd7) | Jan 03, 2025 |
| Lenovo        | ThinkPad T510 4313A11       | Notebook    | [ecf4a20d48](https://linux-hardware.org/?probe=ecf4a20d48) | Jan 01, 2025 |
| HP            | 3032h                       | Desktop     | [fb4af81907](https://linux-hardware.org/?probe=fb4af81907) | Dec 31, 2024 |
| HP            | ProBook 440 G2              | Notebook    | [8f1c0b45da](https://linux-hardware.org/?probe=8f1c0b45da) | Dec 31, 2024 |
| HP            | ProBook 440 G2              | Notebook    | [98d64b84a8](https://linux-hardware.org/?probe=98d64b84a8) | Dec 31, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [27c0c9eacb](https://linux-hardware.org/?probe=27c0c9eacb) | Dec 31, 2024 |
| Google        | Auron_Paine                 | Notebook    | [9603115c16](https://linux-hardware.org/?probe=9603115c16) | Dec 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0831cecc24](https://linux-hardware.org/?probe=0831cecc24) | Dec 30, 2024 |
| HP            | 2B47                        | Desktop     | [1415963334](https://linux-hardware.org/?probe=1415963334) | Dec 28, 2024 |
| ASRock        | A620M-HDV/M.2               | Desktop     | [7bd64010ea](https://linux-hardware.org/?probe=7bd64010ea) | Dec 28, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [e3ba91e9a3](https://linux-hardware.org/?probe=e3ba91e9a3) | Dec 28, 2024 |
| Acer          | Veriton S6630G V:1.0        | Desktop     | [2cbeac15c3](https://linux-hardware.org/?probe=2cbeac15c3) | Dec 26, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [3cd26b82de](https://linux-hardware.org/?probe=3cd26b82de) | Dec 25, 2024 |
| Apple         | MacBook9,1                  | Notebook    | [ebdeaba538](https://linux-hardware.org/?probe=ebdeaba538) | Dec 24, 2024 |
| Lenovo        | ThinkPad T560 20FH001RUS    | Notebook    | [dbc1f4abf5](https://linux-hardware.org/?probe=dbc1f4abf5) | Dec 20, 2024 |
| MSI           | H81M-P33                    | Desktop     | [7fa7cfc46d](https://linux-hardware.org/?probe=7fa7cfc46d) | Dec 18, 2024 |
| Dell          | 02GDWG A00                  | Desktop     | [0576666072](https://linux-hardware.org/?probe=0576666072) | Dec 15, 2024 |
| Lenovo        | Legion Slim 5 16AHP9 83D... | Notebook    | [c67af7e433](https://linux-hardware.org/?probe=c67af7e433) | Dec 13, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [d72d3b5ba5](https://linux-hardware.org/?probe=d72d3b5ba5) | Dec 13, 2024 |
| Google        | Auron_Paine                 | Notebook    | [58c2386219](https://linux-hardware.org/?probe=58c2386219) | Dec 13, 2024 |
| Lenovo        | Legion Slim 5 16AHP9 83D... | Notebook    | [02c452576f](https://linux-hardware.org/?probe=02c452576f) | Dec 12, 2024 |
| Intel         | H61                         | Desktop     | [2f69f512f3](https://linux-hardware.org/?probe=2f69f512f3) | Dec 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7b600860b9](https://linux-hardware.org/?probe=7b600860b9) | Dec 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [6b5111843a](https://linux-hardware.org/?probe=6b5111843a) | Dec 09, 2024 |
| Dell          | 0CRWCR A01                  | All in one  | [a552eb99ee](https://linux-hardware.org/?probe=a552eb99ee) | Dec 09, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4e75b83008](https://linux-hardware.org/?probe=4e75b83008) | Dec 08, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [56d85b7552](https://linux-hardware.org/?probe=56d85b7552) | Dec 07, 2024 |
| Acer          | FIH57                       | All in one  | [aa23301e4b](https://linux-hardware.org/?probe=aa23301e4b) | Dec 06, 2024 |
| HP            | Unknown                     | Notebook    | [0fa9417cad](https://linux-hardware.org/?probe=0fa9417cad) | Dec 05, 2024 |
| ECS           | G31T-M7                     | Desktop     | [fc3fdf0841](https://linux-hardware.org/?probe=fc3fdf0841) | Dec 03, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [13478eefd3](https://linux-hardware.org/?probe=13478eefd3) | Nov 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [e5904a131c](https://linux-hardware.org/?probe=e5904a131c) | Nov 29, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [46151592a2](https://linux-hardware.org/?probe=46151592a2) | Nov 26, 2024 |
| Google        | Reks                        | Notebook    | [14fec8c05b](https://linux-hardware.org/?probe=14fec8c05b) | Nov 21, 2024 |
| MSI           | H410M BOMBER                | Desktop     | [0fdf3b3e0b](https://linux-hardware.org/?probe=0fdf3b3e0b) | Nov 21, 2024 |
| MSI           | H410M BOMBER                | Desktop     | [97ed06f147](https://linux-hardware.org/?probe=97ed06f147) | Nov 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [1ed45c318d](https://linux-hardware.org/?probe=1ed45c318d) | Nov 20, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [c382838a7e](https://linux-hardware.org/?probe=c382838a7e) | Nov 14, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [583860bb6e](https://linux-hardware.org/?probe=583860bb6e) | Nov 12, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [324fcc00f0](https://linux-hardware.org/?probe=324fcc00f0) | Nov 08, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [4f13f8529a](https://linux-hardware.org/?probe=4f13f8529a) | Nov 08, 2024 |
| Google        | Reks                        | Notebook    | [812c11b90a](https://linux-hardware.org/?probe=812c11b90a) | Nov 06, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [e550cab5bc](https://linux-hardware.org/?probe=e550cab5bc) | Nov 01, 2024 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [72f8654114](https://linux-hardware.org/?probe=72f8654114) | Oct 29, 2024 |
| HP            | 1906                        | Desktop     | [2d314c1b57](https://linux-hardware.org/?probe=2d314c1b57) | Oct 28, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [7ae06e5667](https://linux-hardware.org/?probe=7ae06e5667) | Oct 27, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [4710ecffdc](https://linux-hardware.org/?probe=4710ecffdc) | Oct 22, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [841c88c37f](https://linux-hardware.org/?probe=841c88c37f) | Oct 22, 2024 |
| MSI           | Katana GF66 11UG            | Notebook    | [5aa616e2ec](https://linux-hardware.org/?probe=5aa616e2ec) | Oct 21, 2024 |
| MSI           | Katana GF66 11UG            | Notebook    | [5e01b1b5d6](https://linux-hardware.org/?probe=5e01b1b5d6) | Oct 21, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [b89abab194](https://linux-hardware.org/?probe=b89abab194) | Oct 19, 2024 |
| MSI           | MS-7388                     | Desktop     | [2bd3894bc8](https://linux-hardware.org/?probe=2bd3894bc8) | Oct 19, 2024 |
| MSI           | MS-7388                     | Desktop     | [422aa52e15](https://linux-hardware.org/?probe=422aa52e15) | Oct 16, 2024 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [8306979b1b](https://linux-hardware.org/?probe=8306979b1b) | Oct 14, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [ecbc7507b4](https://linux-hardware.org/?probe=ecbc7507b4) | Oct 13, 2024 |
| MSI           | MS-7388                     | Desktop     | [99b0ab9f8b](https://linux-hardware.org/?probe=99b0ab9f8b) | Oct 11, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [1b5dcb7d94](https://linux-hardware.org/?probe=1b5dcb7d94) | Oct 11, 2024 |
| Gigabyte      | B85-D3V                     | Desktop     | [80e0a9b3bf](https://linux-hardware.org/?probe=80e0a9b3bf) | Oct 09, 2024 |
| Dell          | 0V0D45 A01                  | All in one  | [3dc4874e0a](https://linux-hardware.org/?probe=3dc4874e0a) | Oct 04, 2024 |
| Dell          | 0V0D45 A01                  | All in one  | [abf164d886](https://linux-hardware.org/?probe=abf164d886) | Oct 03, 2024 |
| HP            | Compaq Presario CQ41        | Notebook    | [8883290af4](https://linux-hardware.org/?probe=8883290af4) | Oct 03, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f1755431ef](https://linux-hardware.org/?probe=f1755431ef) | Oct 02, 2024 |
| Intel         | X99                         | Desktop     | [02e8e3a503](https://linux-hardware.org/?probe=02e8e3a503) | Oct 01, 2024 |
| SZMZ          | X99M-G2                     | Desktop     | [382a390721](https://linux-hardware.org/?probe=382a390721) | Oct 01, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [23c6bbe37a](https://linux-hardware.org/?probe=23c6bbe37a) | Sep 25, 2024 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [10e3fce76a](https://linux-hardware.org/?probe=10e3fce76a) | Sep 21, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [c22b23aa7e](https://linux-hardware.org/?probe=c22b23aa7e) | Sep 20, 2024 |
| Toshiba       | Satellite L745              | Notebook    | [b60f22f240](https://linux-hardware.org/?probe=b60f22f240) | Sep 19, 2024 |
| MSI           | Thin GF63 12UCX             | Notebook    | [0e28e2e5d1](https://linux-hardware.org/?probe=0e28e2e5d1) | Sep 16, 2024 |
| HP            | 802E                        | Desktop     | [4962c81f46](https://linux-hardware.org/?probe=4962c81f46) | Sep 15, 2024 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [302ff2daa0](https://linux-hardware.org/?probe=302ff2daa0) | Sep 11, 2024 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [f7d4189909](https://linux-hardware.org/?probe=f7d4189909) | Sep 11, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [201f5c142b](https://linux-hardware.org/?probe=201f5c142b) | Sep 11, 2024 |
| Gigabyte      | H310M S2                    | Desktop     | [8761a4e0d3](https://linux-hardware.org/?probe=8761a4e0d3) | Sep 10, 2024 |
| Gigabyte      | H310M S2                    | Desktop     | [81d62ee509](https://linux-hardware.org/?probe=81d62ee509) | Sep 10, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [75baa3ca2a](https://linux-hardware.org/?probe=75baa3ca2a) | Sep 02, 2024 |
| Lenovo        | MIIX 520-12IKB 81CG         | Tablet      | [c14be2a0ff](https://linux-hardware.org/?probe=c14be2a0ff) | Aug 31, 2024 |
| MSI           | MS-7388                     | Desktop     | [54d27d1746](https://linux-hardware.org/?probe=54d27d1746) | Aug 31, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [ffdb47e443](https://linux-hardware.org/?probe=ffdb47e443) | Aug 31, 2024 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [62b809ea1a](https://linux-hardware.org/?probe=62b809ea1a) | Aug 28, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [3d8dd6c9ee](https://linux-hardware.org/?probe=3d8dd6c9ee) | Aug 24, 2024 |
| Lenovo        | ThinkPad X201 36809D4       | Notebook    | [8911266341](https://linux-hardware.org/?probe=8911266341) | Aug 22, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [244824354d](https://linux-hardware.org/?probe=244824354d) | Aug 22, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [4625259735](https://linux-hardware.org/?probe=4625259735) | Aug 20, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [d076181f00](https://linux-hardware.org/?probe=d076181f00) | Aug 16, 2024 |
| Toshiba       | Satellite A660              | Notebook    | [1a5131aae1](https://linux-hardware.org/?probe=1a5131aae1) | Aug 13, 2024 |
| HP            | 2B2C                        | Desktop     | [5cfdd8de1c](https://linux-hardware.org/?probe=5cfdd8de1c) | Aug 12, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [5ed76d1753](https://linux-hardware.org/?probe=5ed76d1753) | Aug 11, 2024 |
| HP            | 81C5 MVB                    | Desktop     | [e933142655](https://linux-hardware.org/?probe=e933142655) | Aug 08, 2024 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [519a8e1780](https://linux-hardware.org/?probe=519a8e1780) | Aug 04, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [d94adc0177](https://linux-hardware.org/?probe=d94adc0177) | Aug 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [684edc9afe](https://linux-hardware.org/?probe=684edc9afe) | Aug 02, 2024 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [1c61147d91](https://linux-hardware.org/?probe=1c61147d91) | Aug 01, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21M5C... | Notebook    | [f8e8647224](https://linux-hardware.org/?probe=f8e8647224) | Jul 30, 2024 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [3eee89f1db](https://linux-hardware.org/?probe=3eee89f1db) | Jul 30, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [4a933ffcd7](https://linux-hardware.org/?probe=4a933ffcd7) | Jul 30, 2024 |
| HP            | Notebook                    | Notebook    | [5624ada989](https://linux-hardware.org/?probe=5624ada989) | Jul 29, 2024 |
| Unknown       | Unknown                     | Notebook    | [a385aca400](https://linux-hardware.org/?probe=a385aca400) | Jul 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [f621a647f0](https://linux-hardware.org/?probe=f621a647f0) | Jul 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [d6d176ebe7](https://linux-hardware.org/?probe=d6d176ebe7) | Jul 27, 2024 |
| ASRock        | Q1900M                      | Desktop     | [a91507fe3f](https://linux-hardware.org/?probe=a91507fe3f) | Jul 25, 2024 |
| Intel         | H61S                        | Desktop     | [e71f6eb2d9](https://linux-hardware.org/?probe=e71f6eb2d9) | Jul 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [98a9cbc497](https://linux-hardware.org/?probe=98a9cbc497) | Jul 21, 2024 |
| AMI           | XT-J1X00E-DZP               | Desktop     | [3da1f9c6d9](https://linux-hardware.org/?probe=3da1f9c6d9) | Jul 17, 2024 |
| ASUSTek       | X550LC                      | Notebook    | [c07ee31aaf](https://linux-hardware.org/?probe=c07ee31aaf) | Jul 16, 2024 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [eadc051df3](https://linux-hardware.org/?probe=eadc051df3) | Jul 13, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [96ddb17c0f](https://linux-hardware.org/?probe=96ddb17c0f) | Jul 13, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [e58422e1b4](https://linux-hardware.org/?probe=e58422e1b4) | Jul 12, 2024 |
| Gigabyte      | G7 GE                       | Notebook    | [c0c18a4870](https://linux-hardware.org/?probe=c0c18a4870) | Jul 11, 2024 |
| HP            | ProLiant ML10               | Desktop     | [040e4b5264](https://linux-hardware.org/?probe=040e4b5264) | Jul 10, 2024 |
| HP            | ProLiant ML10               | Desktop     | [b71e8110c0](https://linux-hardware.org/?probe=b71e8110c0) | Jul 09, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [ffcfcb65e7](https://linux-hardware.org/?probe=ffcfcb65e7) | Jul 06, 2024 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [b541df6068](https://linux-hardware.org/?probe=b541df6068) | Jul 06, 2024 |
| Lenovo        | IdeaPad Z370                | Notebook    | [42eeaeef31](https://linux-hardware.org/?probe=42eeaeef31) | Jul 06, 2024 |
| HP            | Notebook                    | Notebook    | [2c8a9c40ff](https://linux-hardware.org/?probe=2c8a9c40ff) | Jul 03, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS       | Desktop     | [8473676081](https://linux-hardware.org/?probe=8473676081) | Jul 03, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [1f9560d5f1](https://linux-hardware.org/?probe=1f9560d5f1) | Jun 30, 2024 |
| ASRock        | B550M Pro4                  | Notebook    | [71d8153a82](https://linux-hardware.org/?probe=71d8153a82) | Jun 29, 2024 |
| Dell          | Latitude 7330               | Convertible | [ff939f558c](https://linux-hardware.org/?probe=ff939f558c) | Jun 29, 2024 |
| HP            | 2B2C                        | Desktop     | [c370ca2da9](https://linux-hardware.org/?probe=c370ca2da9) | Jun 26, 2024 |
| Toshiba       | dynabook Satellite B65/R    | Notebook    | [d7dbb83ddf](https://linux-hardware.org/?probe=d7dbb83ddf) | Jun 26, 2024 |
| ECS           | G31T-M7                     | Desktop     | [26b4fc8ac7](https://linux-hardware.org/?probe=26b4fc8ac7) | Jun 25, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [f40ec91ddf](https://linux-hardware.org/?probe=f40ec91ddf) | Jun 24, 2024 |
| Dell          | Latitude E6230              | Notebook    | [dcc280d724](https://linux-hardware.org/?probe=dcc280d724) | Jun 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [0fa52f5fa6](https://linux-hardware.org/?probe=0fa52f5fa6) | Jun 18, 2024 |
| Lenovo        | MIIX 3-1030 80HV            | Tablet      | [35aed6a35b](https://linux-hardware.org/?probe=35aed6a35b) | Jun 13, 2024 |
| Lenovo        | MIIX 3-1030 80HV            | Tablet      | [a3cf66797a](https://linux-hardware.org/?probe=a3cf66797a) | Jun 13, 2024 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [d3f3aa71b0](https://linux-hardware.org/?probe=d3f3aa71b0) | Jun 12, 2024 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [3ef8d7d35a](https://linux-hardware.org/?probe=3ef8d7d35a) | Jun 08, 2024 |
| MSI           | Bravo 15 A4DCR              | Notebook    | [5c198c5fc1](https://linux-hardware.org/?probe=5c198c5fc1) | Jun 05, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [1f24db13b9](https://linux-hardware.org/?probe=1f24db13b9) | Jun 03, 2024 |
| Gigabyte      | G41M-Combo                  | Desktop     | [075953fb1c](https://linux-hardware.org/?probe=075953fb1c) | Jun 03, 2024 |
| MSI           | MS-7388                     | Desktop     | [a805fbfd2a](https://linux-hardware.org/?probe=a805fbfd2a) | Jun 02, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [24a4f4c934](https://linux-hardware.org/?probe=24a4f4c934) | Jun 02, 2024 |
| MSI           | MS-7388                     | Desktop     | [f9a5f38d58](https://linux-hardware.org/?probe=f9a5f38d58) | May 31, 2024 |
| Lenovo        | ThinkPad T470 20HES0171P    | Notebook    | [98a7aec6dd](https://linux-hardware.org/?probe=98a7aec6dd) | May 30, 2024 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [7d884ed9cf](https://linux-hardware.org/?probe=7d884ed9cf) | May 30, 2024 |
| Dell          | Latitude E6230              | Notebook    | [7167a7a5aa](https://linux-hardware.org/?probe=7167a7a5aa) | May 29, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3986408709](https://linux-hardware.org/?probe=3986408709) | May 29, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [19082ee33f](https://linux-hardware.org/?probe=19082ee33f) | May 28, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [493e19c3c5](https://linux-hardware.org/?probe=493e19c3c5) | May 27, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [46d4ec8068](https://linux-hardware.org/?probe=46d4ec8068) | May 27, 2024 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [ea849a415f](https://linux-hardware.org/?probe=ea849a415f) | May 24, 2024 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [ec9ce7305d](https://linux-hardware.org/?probe=ec9ce7305d) | May 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [21bf4b6407](https://linux-hardware.org/?probe=21bf4b6407) | May 17, 2024 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [faac458723](https://linux-hardware.org/?probe=faac458723) | May 15, 2024 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [97f3382524](https://linux-hardware.org/?probe=97f3382524) | May 14, 2024 |
| ASUSTek       | K73TK                       | Notebook    | [d125c9715c](https://linux-hardware.org/?probe=d125c9715c) | May 13, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f95460ab80](https://linux-hardware.org/?probe=f95460ab80) | May 13, 2024 |
| Dell          | Inspiron 3476               | Notebook    | [e40be330be](https://linux-hardware.org/?probe=e40be330be) | May 12, 2024 |
| Dell          | Inspiron 3476               | Notebook    | [b023057ee3](https://linux-hardware.org/?probe=b023057ee3) | May 11, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [666c42747e](https://linux-hardware.org/?probe=666c42747e) | May 10, 2024 |
| Lenovo        | ThinkPad Edge 031946U       | Notebook    | [8f8fb39c6e](https://linux-hardware.org/?probe=8f8fb39c6e) | May 08, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [7cf91d002b](https://linux-hardware.org/?probe=7cf91d002b) | May 04, 2024 |
| Lenovo        | ThinkPad T480s 20L8S3KR0... | Notebook    | [3853332c92](https://linux-hardware.org/?probe=3853332c92) | May 04, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [456554dd36](https://linux-hardware.org/?probe=456554dd36) | May 04, 2024 |
| Dell          | 0V0D45 A01                  | All in one  | [8ac266bc9b](https://linux-hardware.org/?probe=8ac266bc9b) | May 03, 2024 |
| Lenovo        | ThinkPad Edge 031946U       | Notebook    | [192d9bc00a](https://linux-hardware.org/?probe=192d9bc00a) | May 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [db48550f51](https://linux-hardware.org/?probe=db48550f51) | May 02, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [cd0f207f60](https://linux-hardware.org/?probe=cd0f207f60) | Apr 28, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [82b1b1485a](https://linux-hardware.org/?probe=82b1b1485a) | Apr 28, 2024 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [a1fbe8858b](https://linux-hardware.org/?probe=a1fbe8858b) | Apr 26, 2024 |
| HP            | Notebook                    | Notebook    | [98ad243a7d](https://linux-hardware.org/?probe=98ad243a7d) | Apr 26, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [069de8abaf](https://linux-hardware.org/?probe=069de8abaf) | Apr 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8cff3fe858](https://linux-hardware.org/?probe=8cff3fe858) | Apr 20, 2024 |
| Gigabyte      | X570 UD                     | Desktop     | [5240449916](https://linux-hardware.org/?probe=5240449916) | Apr 18, 2024 |
| ASRock        | B550 Pro4                   | Desktop     | [f906fa4f7c](https://linux-hardware.org/?probe=f906fa4f7c) | Apr 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [9be7b4bfdc](https://linux-hardware.org/?probe=9be7b4bfdc) | Apr 17, 2024 |
| ECS           | G31T-M7                     | Desktop     | [fa7e63c25c](https://linux-hardware.org/?probe=fa7e63c25c) | Apr 17, 2024 |
| Dell          | 06D7TR A02                  | Desktop     | [8b107755d6](https://linux-hardware.org/?probe=8b107755d6) | Apr 17, 2024 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [7b641eb6ba](https://linux-hardware.org/?probe=7b641eb6ba) | Apr 16, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0428aaf36d](https://linux-hardware.org/?probe=0428aaf36d) | Apr 15, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [8f232e4e6c](https://linux-hardware.org/?probe=8f232e4e6c) | Apr 11, 2024 |
| Fujitsu       | FARQ01024                   | Notebook    | [11340c8636](https://linux-hardware.org/?probe=11340c8636) | Apr 09, 2024 |
| HP            | 18E7                        | Desktop     | [467ac72efe](https://linux-hardware.org/?probe=467ac72efe) | Apr 07, 2024 |
| ECS           | G31T-M7                     | Desktop     | [ce42a0a99a](https://linux-hardware.org/?probe=ce42a0a99a) | Apr 01, 2024 |
| MSI           | MS-7388                     | Desktop     | [7ece0030bf](https://linux-hardware.org/?probe=7ece0030bf) | Mar 30, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [f6d71cfa9f](https://linux-hardware.org/?probe=f6d71cfa9f) | Mar 30, 2024 |
| Gigabyte      | X570 UD                     | Desktop     | [539238d399](https://linux-hardware.org/?probe=539238d399) | Mar 29, 2024 |
| ASRock        | B550 Pro4                   | Desktop     | [9144eb7fe4](https://linux-hardware.org/?probe=9144eb7fe4) | Mar 29, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [d84d712a77](https://linux-hardware.org/?probe=d84d712a77) | Mar 29, 2024 |
| Acer          | Aspire TC-1660 V:1.1        | Desktop     | [c0dfdce31b](https://linux-hardware.org/?probe=c0dfdce31b) | Mar 21, 2024 |
| Toshiba       | PORTEGE R930                | Notebook    | [c0ac0e9072](https://linux-hardware.org/?probe=c0ac0e9072) | Mar 21, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [8ff1245537](https://linux-hardware.org/?probe=8ff1245537) | Mar 19, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a19c2ddfef](https://linux-hardware.org/?probe=a19c2ddfef) | Mar 14, 2024 |
| Dell          | Latitude 5490               | Notebook    | [8eee3b1f21](https://linux-hardware.org/?probe=8eee3b1f21) | Mar 11, 2024 |
| Dell          | Latitude 5490               | Notebook    | [ace23bd1bf](https://linux-hardware.org/?probe=ace23bd1bf) | Mar 09, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [edd6400e24](https://linux-hardware.org/?probe=edd6400e24) | Mar 08, 2024 |
| Dell          | Inspiron 11-3168            | Notebook    | [fb161333d5](https://linux-hardware.org/?probe=fb161333d5) | Mar 07, 2024 |
| Dell          | 06D7TR A02                  | Desktop     | [e92342cc9d](https://linux-hardware.org/?probe=e92342cc9d) | Mar 06, 2024 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [363dfceefd](https://linux-hardware.org/?probe=363dfceefd) | Mar 06, 2024 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d746e0ee2c](https://linux-hardware.org/?probe=d746e0ee2c) | Mar 05, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b75f098f59](https://linux-hardware.org/?probe=b75f098f59) | Mar 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [f1068af6ca](https://linux-hardware.org/?probe=f1068af6ca) | Mar 03, 2024 |
| MSI           | Z97 GAMING 7                | Desktop     | [be7cf8b3fc](https://linux-hardware.org/?probe=be7cf8b3fc) | Mar 01, 2024 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [5b10f28295](https://linux-hardware.org/?probe=5b10f28295) | Mar 01, 2024 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | Notebook    | [b6042aa087](https://linux-hardware.org/?probe=b6042aa087) | Feb 25, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [1b1f6e6704](https://linux-hardware.org/?probe=1b1f6e6704) | Feb 25, 2024 |
| MSI           | MS-7388                     | Desktop     | [2429edf24b](https://linux-hardware.org/?probe=2429edf24b) | Feb 24, 2024 |
| HP            | ProLiant DL320 G6           | Server      | [a3f006e207](https://linux-hardware.org/?probe=a3f006e207) | Feb 22, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [4958d63fb4](https://linux-hardware.org/?probe=4958d63fb4) | Feb 20, 2024 |
| Lenovo        | ThinkPad X230 2325CY4       | Notebook    | [6491a02f07](https://linux-hardware.org/?probe=6491a02f07) | Feb 20, 2024 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [68ae08681c](https://linux-hardware.org/?probe=68ae08681c) | Feb 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [89d1e82e1f](https://linux-hardware.org/?probe=89d1e82e1f) | Feb 16, 2024 |
| Dell          | Latitude E5510              | Notebook    | [5f80ee2a3d](https://linux-hardware.org/?probe=5f80ee2a3d) | Feb 12, 2024 |
| Dell          | Latitude E5510              | Notebook    | [caaa63a7ad](https://linux-hardware.org/?probe=caaa63a7ad) | Feb 12, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [1bbac9a561](https://linux-hardware.org/?probe=1bbac9a561) | Feb 06, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [14fa3f411f](https://linux-hardware.org/?probe=14fa3f411f) | Feb 03, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [378bef57f2](https://linux-hardware.org/?probe=378bef57f2) | Feb 03, 2024 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [5661819818](https://linux-hardware.org/?probe=5661819818) | Feb 02, 2024 |
| Intel         | NUC7i5BNB J31144-302        | Mini pc     | [b7e8bed4cd](https://linux-hardware.org/?probe=b7e8bed4cd) | Jan 30, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [c737ef78e9](https://linux-hardware.org/?probe=c737ef78e9) | Jan 30, 2024 |
| AZW           | MINI S 10                   | Desktop     | [a209f8ae32](https://linux-hardware.org/?probe=a209f8ae32) | Jan 30, 2024 |
| ASRock        | X370 Professional Gaming    | Desktop     | [ddff1295a4](https://linux-hardware.org/?probe=ddff1295a4) | Jan 30, 2024 |
| Dell          | 0W0CHX A00                  | Desktop     | [e57642d0d4](https://linux-hardware.org/?probe=e57642d0d4) | Jan 28, 2024 |
| Machenike     | ARB19                       | Desktop     | [3002916884](https://linux-hardware.org/?probe=3002916884) | Jan 28, 2024 |
| Machenike     | ARB19                       | Desktop     | [4f289b9a02](https://linux-hardware.org/?probe=4f289b9a02) | Jan 28, 2024 |
| NEC Comput... | PC-VK27MXZCG                | Notebook    | [3ff2676eeb](https://linux-hardware.org/?probe=3ff2676eeb) | Jan 27, 2024 |
| Google        | Kefka                       | Notebook    | [810d5a47f7](https://linux-hardware.org/?probe=810d5a47f7) | Jan 27, 2024 |
| Dell          | 0427JK A00                  | Desktop     | [7f8cfea83b](https://linux-hardware.org/?probe=7f8cfea83b) | Jan 20, 2024 |
| MSI           | MS-7388                     | Desktop     | [e151be731a](https://linux-hardware.org/?probe=e151be731a) | Jan 20, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [c7ac75fb19](https://linux-hardware.org/?probe=c7ac75fb19) | Jan 20, 2024 |
| Gigabyte      | A520M K V2                  | Desktop     | [65409c0132](https://linux-hardware.org/?probe=65409c0132) | Jan 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [553986db8b](https://linux-hardware.org/?probe=553986db8b) | Jan 18, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [dddcaf6303](https://linux-hardware.org/?probe=dddcaf6303) | Jan 16, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [26452561bd](https://linux-hardware.org/?probe=26452561bd) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [b54faba218](https://linux-hardware.org/?probe=b54faba218) | Jan 14, 2024 |
| Rockchip      | RK3566 OPi 3B               | Soc         | [1ad7806df7](https://linux-hardware.org/?probe=1ad7806df7) | Jan 12, 2024 |
| HP            | 2B2C                        | Desktop     | [6e5219edb5](https://linux-hardware.org/?probe=6e5219edb5) | Jan 11, 2024 |
| HP            | 2B2C                        | Desktop     | [5ac47f9e43](https://linux-hardware.org/?probe=5ac47f9e43) | Jan 04, 2024 |
| Lenovo        | G480                        | Notebook    | [e9a25c068d](https://linux-hardware.org/?probe=e9a25c068d) | Jan 03, 2024 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [de165da202](https://linux-hardware.org/?probe=de165da202) | Dec 27, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [9f4b6b970d](https://linux-hardware.org/?probe=9f4b6b970d) | Dec 26, 2023 |
| MSI           | MS-7388                     | Desktop     | [efab378a60](https://linux-hardware.org/?probe=efab378a60) | Dec 24, 2023 |
| Dell          | Latitude E5510              | Notebook    | [379ebf6111](https://linux-hardware.org/?probe=379ebf6111) | Dec 23, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [1c3e40ac13](https://linux-hardware.org/?probe=1c3e40ac13) | Dec 23, 2023 |
| MSI           | MS-7388                     | Desktop     | [5027d4b8ed](https://linux-hardware.org/?probe=5027d4b8ed) | Dec 23, 2023 |
| Sony          | VPCEG18FG                   | Notebook    | [e1b5fa6cac](https://linux-hardware.org/?probe=e1b5fa6cac) | Dec 15, 2023 |
| Sony          | VPCEG18FG                   | Notebook    | [3cf20aa9ea](https://linux-hardware.org/?probe=3cf20aa9ea) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [68e68f1683](https://linux-hardware.org/?probe=68e68f1683) | Dec 13, 2023 |
| HP            | 2129                        | Desktop     | [3a95965680](https://linux-hardware.org/?probe=3a95965680) | Dec 13, 2023 |
| Dell          | Latitude E5510              | Notebook    | [1e0f4dcd24](https://linux-hardware.org/?probe=1e0f4dcd24) | Dec 13, 2023 |
| Dell          | Latitude E5510              | Notebook    | [a980a75837](https://linux-hardware.org/?probe=a980a75837) | Dec 12, 2023 |
| Acer          | AOD257                      | Notebook    | [79c121ca0e](https://linux-hardware.org/?probe=79c121ca0e) | Dec 09, 2023 |
| Acer          | AOD257                      | Notebook    | [c817dc5cca](https://linux-hardware.org/?probe=c817dc5cca) | Dec 08, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [31de30cc0e](https://linux-hardware.org/?probe=31de30cc0e) | Dec 06, 2023 |
| Fujitsu       | LIFEBOOK UH554              | Notebook    | [cfdc07bd6d](https://linux-hardware.org/?probe=cfdc07bd6d) | Dec 05, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [796859e80e](https://linux-hardware.org/?probe=796859e80e) | Dec 05, 2023 |
| Lenovo        | G480                        | Notebook    | [e82d31d252](https://linux-hardware.org/?probe=e82d31d252) | Dec 05, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [d6e3212623](https://linux-hardware.org/?probe=d6e3212623) | Dec 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [e5546145aa](https://linux-hardware.org/?probe=e5546145aa) | Dec 02, 2023 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [3248206a01](https://linux-hardware.org/?probe=3248206a01) | Nov 30, 2023 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [f3b42d14f6](https://linux-hardware.org/?probe=f3b42d14f6) | Nov 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [11d4048dc9](https://linux-hardware.org/?probe=11d4048dc9) | Nov 28, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [42fb4ae911](https://linux-hardware.org/?probe=42fb4ae911) | Nov 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0390B    | Notebook    | [9b37545fa9](https://linux-hardware.org/?probe=9b37545fa9) | Nov 28, 2023 |
| Dell          | Latitude E5510              | Notebook    | [5f68594a94](https://linux-hardware.org/?probe=5f68594a94) | Nov 28, 2023 |
| Intel         | H61                         | Desktop     | [97a16fcd1b](https://linux-hardware.org/?probe=97a16fcd1b) | Nov 27, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [c6955988fb](https://linux-hardware.org/?probe=c6955988fb) | Nov 25, 2023 |
| IBM           | ThinkPad T42 2374GB1        | Notebook    | [455a2c937b](https://linux-hardware.org/?probe=455a2c937b) | Nov 19, 2023 |
| Lenovo        | 30C7 SDK0K13468 WIN 3273... | Desktop     | [27b54b9945](https://linux-hardware.org/?probe=27b54b9945) | Nov 19, 2023 |
| Lenovo        | ThinkPad Edge 03282XA       | Notebook    | [c46ed26c69](https://linux-hardware.org/?probe=c46ed26c69) | Nov 18, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [98f59c07de](https://linux-hardware.org/?probe=98f59c07de) | Nov 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [386450b69c](https://linux-hardware.org/?probe=386450b69c) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [1063cc1572](https://linux-hardware.org/?probe=1063cc1572) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [8ee2dc1361](https://linux-hardware.org/?probe=8ee2dc1361) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [6ff4b2ddd5](https://linux-hardware.org/?probe=6ff4b2ddd5) | Nov 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e8e0ef7485](https://linux-hardware.org/?probe=e8e0ef7485) | Nov 15, 2023 |
| Xiaomi        | Technologies, Inc. Polar... | Phone       | [83199a2c2d](https://linux-hardware.org/?probe=83199a2c2d) | Nov 13, 2023 |
| Dell          | Latitude E7250              | Notebook    | [265c13751a](https://linux-hardware.org/?probe=265c13751a) | Nov 10, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [4dbd78f68d](https://linux-hardware.org/?probe=4dbd78f68d) | Nov 09, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [31c6154826](https://linux-hardware.org/?probe=31c6154826) | Nov 08, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [8cf5696a9e](https://linux-hardware.org/?probe=8cf5696a9e) | Nov 07, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [c126c9e041](https://linux-hardware.org/?probe=c126c9e041) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [49baeb0911](https://linux-hardware.org/?probe=49baeb0911) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [03fbe0b1a4](https://linux-hardware.org/?probe=03fbe0b1a4) | Oct 24, 2023 |
| ECS           | G31T-M7                     | Desktop     | [297db99cc3](https://linux-hardware.org/?probe=297db99cc3) | Oct 20, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [0d55c2a6af](https://linux-hardware.org/?probe=0d55c2a6af) | Oct 20, 2023 |
| Dell          | 0WWR83 A04                  | Server      | [e0d564d8c4](https://linux-hardware.org/?probe=e0d564d8c4) | Oct 17, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [67365133d9](https://linux-hardware.org/?probe=67365133d9) | Oct 17, 2023 |
| Acer          | Aspire VN7-592G             | Notebook    | [13b64fc9bd](https://linux-hardware.org/?probe=13b64fc9bd) | Oct 15, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [f6373646f3](https://linux-hardware.org/?probe=f6373646f3) | Oct 14, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [954eecec42](https://linux-hardware.org/?probe=954eecec42) | Oct 09, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5295ac09d9](https://linux-hardware.org/?probe=5295ac09d9) | Oct 06, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [fcfe482832](https://linux-hardware.org/?probe=fcfe482832) | Oct 04, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T52R     | Notebook    | [39983ac5b1](https://linux-hardware.org/?probe=39983ac5b1) | Oct 04, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [ee02fff8df](https://linux-hardware.org/?probe=ee02fff8df) | Sep 28, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [273b056209](https://linux-hardware.org/?probe=273b056209) | Sep 25, 2023 |
| Dell          | Latitude E7450              | Notebook    | [6ba017a802](https://linux-hardware.org/?probe=6ba017a802) | Sep 23, 2023 |
| MSI           | MS-7388                     | Desktop     | [f5ee235af0](https://linux-hardware.org/?probe=f5ee235af0) | Sep 23, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M8S... | Convertible | [e935ac4c0a](https://linux-hardware.org/?probe=e935ac4c0a) | Sep 22, 2023 |
| Lenovo        | ThinkPad E480 20KNS0MM00    | Notebook    | [ef56d33374](https://linux-hardware.org/?probe=ef56d33374) | Sep 19, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [af2217289d](https://linux-hardware.org/?probe=af2217289d) | Sep 19, 2023 |
| MSI           | Modern 14 C11M              | Notebook    | [4c6156df05](https://linux-hardware.org/?probe=4c6156df05) | Sep 18, 2023 |
| Dell          | Latitude E7470              | Notebook    | [8b06be8e07](https://linux-hardware.org/?probe=8b06be8e07) | Sep 18, 2023 |
| Dell          | Latitude E7470              | Notebook    | [c2acf11095](https://linux-hardware.org/?probe=c2acf11095) | Sep 18, 2023 |
| Fujitsu       | LIFEBOOK UH554              | Notebook    | [92f2e6135e](https://linux-hardware.org/?probe=92f2e6135e) | Sep 13, 2023 |
| Acer          | AOD270                      | Notebook    | [d7d4474d69](https://linux-hardware.org/?probe=d7d4474d69) | Sep 11, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [8a0ad0652e](https://linux-hardware.org/?probe=8a0ad0652e) | Sep 06, 2023 |
| Acer          | Aspire 4738Z                | Notebook    | [88b34596c0](https://linux-hardware.org/?probe=88b34596c0) | Sep 05, 2023 |
| Acer          | Aspire 4741                 | Notebook    | [2f2b673625](https://linux-hardware.org/?probe=2f2b673625) | Sep 04, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [92b5ca6639](https://linux-hardware.org/?probe=92b5ca6639) | Sep 03, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [f2eccf0aa8](https://linux-hardware.org/?probe=f2eccf0aa8) | Sep 02, 2023 |
| ASRock        | A620M-HDV/M.2+              | Desktop     | [674da4ba95](https://linux-hardware.org/?probe=674da4ba95) | Sep 02, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4660dc9f99](https://linux-hardware.org/?probe=4660dc9f99) | Sep 01, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [d53deba94a](https://linux-hardware.org/?probe=d53deba94a) | Aug 31, 2023 |
| Lenovo        | ThinkPad X201 36809D4       | Notebook    | [1e4311af0b](https://linux-hardware.org/?probe=1e4311af0b) | Aug 28, 2023 |
| ECS           | G31T-M7                     | Desktop     | [f095887170](https://linux-hardware.org/?probe=f095887170) | Aug 28, 2023 |
| Dell          | Latitude 5580               | Notebook    | [eb2a994e98](https://linux-hardware.org/?probe=eb2a994e98) | Aug 28, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [4e72e77dc6](https://linux-hardware.org/?probe=4e72e77dc6) | Aug 27, 2023 |
| MSI           | MS-7388                     | Desktop     | [42530086f2](https://linux-hardware.org/?probe=42530086f2) | Aug 27, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [629b07f8bc](https://linux-hardware.org/?probe=629b07f8bc) | Aug 27, 2023 |
| MSI           | MS-7388                     | Desktop     | [5c1e4b0c2b](https://linux-hardware.org/?probe=5c1e4b0c2b) | Aug 25, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [d28f06dcc5](https://linux-hardware.org/?probe=d28f06dcc5) | Aug 25, 2023 |
| Intel         | X99                         | Desktop     | [785fcd2a1d](https://linux-hardware.org/?probe=785fcd2a1d) | Aug 21, 2023 |
| Intel         | X99                         | Desktop     | [b54ecfbbc3](https://linux-hardware.org/?probe=b54ecfbbc3) | Aug 21, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [109c0dbb17](https://linux-hardware.org/?probe=109c0dbb17) | Aug 20, 2023 |
| Acer          | Veriton M2611G v1.0         | Desktop     | [1527c20b46](https://linux-hardware.org/?probe=1527c20b46) | Aug 19, 2023 |
| HP            | Notebook                    | Notebook    | [dd8c90afbe](https://linux-hardware.org/?probe=dd8c90afbe) | Aug 16, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [b288a65e53](https://linux-hardware.org/?probe=b288a65e53) | Aug 16, 2023 |
| Intel         | S1200SP H57532-210          | Server      | [65dc0edd69](https://linux-hardware.org/?probe=65dc0edd69) | Aug 14, 2023 |
| ECS           | G31T-M7                     | Desktop     | [2d35b5e140](https://linux-hardware.org/?probe=2d35b5e140) | Aug 14, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [d4c5a12d06](https://linux-hardware.org/?probe=d4c5a12d06) | Aug 10, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [becf318878](https://linux-hardware.org/?probe=becf318878) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [1b9794e2e3](https://linux-hardware.org/?probe=1b9794e2e3) | Aug 06, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [9cda5ca576](https://linux-hardware.org/?probe=9cda5ca576) | Aug 05, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [78566a197e](https://linux-hardware.org/?probe=78566a197e) | Aug 05, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [f82f03bf86](https://linux-hardware.org/?probe=f82f03bf86) | Aug 04, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [356e8a0637](https://linux-hardware.org/?probe=356e8a0637) | Jul 28, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [dcab108dc9](https://linux-hardware.org/?probe=dcab108dc9) | Jul 27, 2023 |
| Raspberry ... | Raspberry Pi Zero Rev 1.... | Soc         | [7d14afe547](https://linux-hardware.org/?probe=7d14afe547) | Jul 26, 2023 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [c7373023dd](https://linux-hardware.org/?probe=c7373023dd) | Jul 26, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [e074ee90be](https://linux-hardware.org/?probe=e074ee90be) | Jul 25, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f2f1f87d0c](https://linux-hardware.org/?probe=f2f1f87d0c) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [fee4019ae0](https://linux-hardware.org/?probe=fee4019ae0) | Jul 22, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [eb68b04a83](https://linux-hardware.org/?probe=eb68b04a83) | Jul 22, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [9b6d9b3e96](https://linux-hardware.org/?probe=9b6d9b3e96) | Jul 21, 2023 |
| MSI           | PRO B660M-E DDR4            | Desktop     | [62aa29ec8e](https://linux-hardware.org/?probe=62aa29ec8e) | Jul 19, 2023 |
| Dell          | 05XKKK A05                  | Server      | [3e627de1a2](https://linux-hardware.org/?probe=3e627de1a2) | Jul 19, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [556e1f1fd7](https://linux-hardware.org/?probe=556e1f1fd7) | Jul 19, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [0878c1fae6](https://linux-hardware.org/?probe=0878c1fae6) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [a8779931a8](https://linux-hardware.org/?probe=a8779931a8) | Jul 18, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [28c6cd48b8](https://linux-hardware.org/?probe=28c6cd48b8) | Jul 16, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [9ef499d31f](https://linux-hardware.org/?probe=9ef499d31f) | Jul 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [85d7cb63b8](https://linux-hardware.org/?probe=85d7cb63b8) | Jul 16, 2023 |
| Acer          | Veriton X6610G              | Desktop     | [e1189e3406](https://linux-hardware.org/?probe=e1189e3406) | Jul 13, 2023 |
| HP            | Notebook                    | Notebook    | [50376757dd](https://linux-hardware.org/?probe=50376757dd) | Jul 13, 2023 |
| ASRockRack    | ROMED8QM-2T                 | Desktop     | [a4fe5ea9c9](https://linux-hardware.org/?probe=a4fe5ea9c9) | Jul 13, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [87a1bbb5cc](https://linux-hardware.org/?probe=87a1bbb5cc) | Jul 08, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [8f01854bc7](https://linux-hardware.org/?probe=8f01854bc7) | Jul 07, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [8287d6e8e3](https://linux-hardware.org/?probe=8287d6e8e3) | Jul 04, 2023 |
| Dell          | Latitude E5440              | Notebook    | [03ed0e9ebb](https://linux-hardware.org/?probe=03ed0e9ebb) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [51d003ae6a](https://linux-hardware.org/?probe=51d003ae6a) | Jul 02, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [18b6484d81](https://linux-hardware.org/?probe=18b6484d81) | Jul 01, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [3932620fb9](https://linux-hardware.org/?probe=3932620fb9) | Jun 30, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [971852cb38](https://linux-hardware.org/?probe=971852cb38) | Jun 28, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [1a84c61bd4](https://linux-hardware.org/?probe=1a84c61bd4) | Jun 27, 2023 |
| HP            | 2B2C                        | Desktop     | [a8ec805431](https://linux-hardware.org/?probe=a8ec805431) | Jun 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [a03717af50](https://linux-hardware.org/?probe=a03717af50) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 34766TT       | Notebook    | [06ad7b4a25](https://linux-hardware.org/?probe=06ad7b4a25) | Jun 26, 2023 |
| HP            | 2B2C                        | Desktop     | [3b82186362](https://linux-hardware.org/?probe=3b82186362) | Jun 26, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [4269ca2c0b](https://linux-hardware.org/?probe=4269ca2c0b) | Jun 25, 2023 |
| AZW           | GT-R                        | Notebook    | [11f032f354](https://linux-hardware.org/?probe=11f032f354) | Jun 24, 2023 |
| HP            | 2B2C                        | Desktop     | [4303d28839](https://linux-hardware.org/?probe=4303d28839) | Jun 22, 2023 |
| Unknown       | Unknown                     | Phone       | [32b03337ba](https://linux-hardware.org/?probe=32b03337ba) | Jun 19, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [1623fa6455](https://linux-hardware.org/?probe=1623fa6455) | Jun 11, 2023 |
| MSI           | MS-7388                     | Desktop     | [6d3a406400](https://linux-hardware.org/?probe=6d3a406400) | Jun 10, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [59c8fdd841](https://linux-hardware.org/?probe=59c8fdd841) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [626a677331](https://linux-hardware.org/?probe=626a677331) | Jun 06, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [b1c1176a5b](https://linux-hardware.org/?probe=b1c1176a5b) | Jun 05, 2023 |
| MSI           | MS-7388                     | Desktop     | [fc12ac6b90](https://linux-hardware.org/?probe=fc12ac6b90) | Jun 02, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [f65eac842b](https://linux-hardware.org/?probe=f65eac842b) | May 23, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [9d2439e8d7](https://linux-hardware.org/?probe=9d2439e8d7) | May 18, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7957c81218](https://linux-hardware.org/?probe=7957c81218) | May 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1aedc7da48](https://linux-hardware.org/?probe=1aedc7da48) | May 17, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [83537861c1](https://linux-hardware.org/?probe=83537861c1) | May 14, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1f22322c4a](https://linux-hardware.org/?probe=1f22322c4a) | May 11, 2023 |
| MSI           | Stealth 14Studio A13VE      | Notebook    | [86f43bbff1](https://linux-hardware.org/?probe=86f43bbff1) | May 10, 2023 |
| Samsung       | 535U3C                      | Notebook    | [5f2e46be0a](https://linux-hardware.org/?probe=5f2e46be0a) | May 05, 2023 |
| MSI           | MS-7388                     | Desktop     | [948e1d2358](https://linux-hardware.org/?probe=948e1d2358) | May 03, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [0a9bdb3cea](https://linux-hardware.org/?probe=0a9bdb3cea) | May 02, 2023 |
| MSI           | MS-7388                     | Desktop     | [ec819aca80](https://linux-hardware.org/?probe=ec819aca80) | May 01, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [6da1ddcef5](https://linux-hardware.org/?probe=6da1ddcef5) | May 01, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [a3d2b3dcd3](https://linux-hardware.org/?probe=a3d2b3dcd3) | Apr 30, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [915147a191](https://linux-hardware.org/?probe=915147a191) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [92a968e58d](https://linux-hardware.org/?probe=92a968e58d) | Apr 25, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [a09ea158cc](https://linux-hardware.org/?probe=a09ea158cc) | Apr 20, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| MSI           | MS-7388                     | Desktop     | [4efa2b04da](https://linux-hardware.org/?probe=4efa2b04da) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [c17cfe4d6d](https://linux-hardware.org/?probe=c17cfe4d6d) | Apr 13, 2023 |
| HP            | Notebook                    | Notebook    | [5fc60b1d5f](https://linux-hardware.org/?probe=5fc60b1d5f) | Apr 13, 2023 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [04eb10296f](https://linux-hardware.org/?probe=04eb10296f) | Apr 13, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [ffdcd55e2e](https://linux-hardware.org/?probe=ffdcd55e2e) | Apr 13, 2023 |
| MSI           | MS-7388                     | Desktop     | [d7f892b3e2](https://linux-hardware.org/?probe=d7f892b3e2) | Apr 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eb03b75c27](https://linux-hardware.org/?probe=eb03b75c27) | Apr 11, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [d76bd92923](https://linux-hardware.org/?probe=d76bd92923) | Apr 07, 2023 |
| NEC Comput... | PC-VK27MCZCK                | Notebook    | [e9572ebd2e](https://linux-hardware.org/?probe=e9572ebd2e) | Apr 06, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [f64cf6a2ae](https://linux-hardware.org/?probe=f64cf6a2ae) | Apr 02, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [54789b15f3](https://linux-hardware.org/?probe=54789b15f3) | Mar 29, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [798462942d](https://linux-hardware.org/?probe=798462942d) | Mar 25, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [eb1d734a53](https://linux-hardware.org/?probe=eb1d734a53) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Biostar       | G41D3+                      | Desktop     | [ebb9a17568](https://linux-hardware.org/?probe=ebb9a17568) | Mar 23, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [b54b641b36](https://linux-hardware.org/?probe=b54b641b36) | Mar 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| Dell          | 084J0R A00                  | Desktop     | [dcde5e81ed](https://linux-hardware.org/?probe=dcde5e81ed) | Mar 04, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [c9b32e7136](https://linux-hardware.org/?probe=c9b32e7136) | Mar 03, 2023 |
| Dell          | Latitude 5420               | Notebook    | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [59d082bd5f](https://linux-hardware.org/?probe=59d082bd5f) | Feb 26, 2023 |
| ASUSTek       | ZenBook UX462DA             | Convertible | [4f45a3b6bd](https://linux-hardware.org/?probe=4f45a3b6bd) | Feb 25, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [c812182e32](https://linux-hardware.org/?probe=c812182e32) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [9763d78500](https://linux-hardware.org/?probe=9763d78500) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [c803a7f9e8](https://linux-hardware.org/?probe=c803a7f9e8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [3a660768c0](https://linux-hardware.org/?probe=3a660768c0) | Feb 15, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [43bd1ca5e1](https://linux-hardware.org/?probe=43bd1ca5e1) | Feb 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [0a0e30ba0a](https://linux-hardware.org/?probe=0a0e30ba0a) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6012e644eb](https://linux-hardware.org/?probe=6012e644eb) | Feb 13, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [91ac69dfa1](https://linux-hardware.org/?probe=91ac69dfa1) | Feb 13, 2023 |
| HP            | 18E4                        | Desktop     | [55972b87dd](https://linux-hardware.org/?probe=55972b87dd) | Feb 11, 2023 |
| HP            | ENVY 4                      | Notebook    | [0344f89eea](https://linux-hardware.org/?probe=0344f89eea) | Feb 07, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [56e5f689ab](https://linux-hardware.org/?probe=56e5f689ab) | Feb 06, 2023 |
| Lenovo        | ThinkPad E590 20NBCTO1WW    | Notebook    | [5260560c15](https://linux-hardware.org/?probe=5260560c15) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [2d40451b53](https://linux-hardware.org/?probe=2d40451b53) | Feb 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [903e8715e4](https://linux-hardware.org/?probe=903e8715e4) | Feb 03, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6013489300](https://linux-hardware.org/?probe=6013489300) | Feb 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a195487665](https://linux-hardware.org/?probe=a195487665) | Jan 30, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [d356c9846a](https://linux-hardware.org/?probe=d356c9846a) | Jan 30, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [e660f922a4](https://linux-hardware.org/?probe=e660f922a4) | Jan 27, 2023 |
| HP            | ENVY 4                      | Notebook    | [55ee9d4ca9](https://linux-hardware.org/?probe=55ee9d4ca9) | Jan 27, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [cb932accdb](https://linux-hardware.org/?probe=cb932accdb) | Jan 24, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [d3e44e2970](https://linux-hardware.org/?probe=d3e44e2970) | Jan 20, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [d16f5ca08a](https://linux-hardware.org/?probe=d16f5ca08a) | Jan 19, 2023 |
| Dell          | Latitude 3410               | Notebook    | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0fe4db1f37](https://linux-hardware.org/?probe=0fe4db1f37) | Jan 16, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [20e990e236](https://linux-hardware.org/?probe=20e990e236) | Jan 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [5d228e798d](https://linux-hardware.org/?probe=5d228e798d) | Jan 16, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [4acb924b75](https://linux-hardware.org/?probe=4acb924b75) | Jan 14, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [f34e2c982f](https://linux-hardware.org/?probe=f34e2c982f) | Jan 13, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [72a6b9a90b](https://linux-hardware.org/?probe=72a6b9a90b) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a712e2524b](https://linux-hardware.org/?probe=a712e2524b) | Jan 09, 2023 |
| HP            | 2B2C                        | Desktop     | [1a74d92aaf](https://linux-hardware.org/?probe=1a74d92aaf) | Jan 08, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| Dell          | Latitude 5420               | Notebook    | [06dc453cbc](https://linux-hardware.org/?probe=06dc453cbc) | Dec 27, 2022 |
| HP            | Notebook                    | Notebook    | [8ba42c8ebc](https://linux-hardware.org/?probe=8ba42c8ebc) | Dec 27, 2022 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [44d3b06704](https://linux-hardware.org/?probe=44d3b06704) | Dec 23, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [fd4611b301](https://linux-hardware.org/?probe=fd4611b301) | Dec 21, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4efe19137d](https://linux-hardware.org/?probe=4efe19137d) | Dec 21, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [3d33008fb2](https://linux-hardware.org/?probe=3d33008fb2) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [2b0d31db9d](https://linux-hardware.org/?probe=2b0d31db9d) | Dec 18, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [10a6f30aeb](https://linux-hardware.org/?probe=10a6f30aeb) | Dec 04, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [725404aadb](https://linux-hardware.org/?probe=725404aadb) | Dec 04, 2022 |
| Sony          | VPCEG16EG                   | Notebook    | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| HP            | 2B2C                        | Desktop     | [91862a2497](https://linux-hardware.org/?probe=91862a2497) | Nov 19, 2022 |
| Dell          | Latitude E6220              | Notebook    | [c92cd25690](https://linux-hardware.org/?probe=c92cd25690) | Nov 19, 2022 |
| HP            | 2B2C                        | Desktop     | [2eb8311f18](https://linux-hardware.org/?probe=2eb8311f18) | Nov 16, 2022 |
| Lenovo        | ThinkPad T450 20BUS1S81K    | Notebook    | [ee3fb9c9d2](https://linux-hardware.org/?probe=ee3fb9c9d2) | Nov 14, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1fef4a8aa5](https://linux-hardware.org/?probe=1fef4a8aa5) | Nov 13, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [29641e8b7c](https://linux-hardware.org/?probe=29641e8b7c) | Nov 09, 2022 |
| Dell          | 0V52N7 A02                  | Server      | [3151a21ebf](https://linux-hardware.org/?probe=3151a21ebf) | Nov 09, 2022 |
| Dell          | Latitude E6230              | Notebook    | [da1e32759d](https://linux-hardware.org/?probe=da1e32759d) | Nov 05, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b39c12a9a4](https://linux-hardware.org/?probe=b39c12a9a4) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Seco          | C40 C                       | Desktop     | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [abe170cf19](https://linux-hardware.org/?probe=abe170cf19) | Oct 27, 2022 |
| NEC Comput... | PC-VK27MXZCG                | Notebook    | [04c88c4087](https://linux-hardware.org/?probe=04c88c4087) | Oct 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [dcf74e5715](https://linux-hardware.org/?probe=dcf74e5715) | Oct 22, 2022 |
| Dell          | Precision 3561              | Notebook    | [f514228295](https://linux-hardware.org/?probe=f514228295) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| ASUSTek       | UN65U                       | Mini pc     | [f0bab8d97c](https://linux-hardware.org/?probe=f0bab8d97c) | Oct 06, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1cceb45dea](https://linux-hardware.org/?probe=1cceb45dea) | Oct 04, 2022 |
| HP            | 2B2C                        | Desktop     | [df8a8ec9bc](https://linux-hardware.org/?probe=df8a8ec9bc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | Notebook    | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3e5af3e86c](https://linux-hardware.org/?probe=3e5af3e86c) | Sep 25, 2022 |
| HP            | 18E7                        | Desktop     | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [3f33a64102](https://linux-hardware.org/?probe=3f33a64102) | Sep 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [0d8e7f2e92](https://linux-hardware.org/?probe=0d8e7f2e92) | Sep 21, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| Alienware     | M14xR1                      | Notebook    | [a4064c0342](https://linux-hardware.org/?probe=a4064c0342) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | Notebook    | [3162a68bf5](https://linux-hardware.org/?probe=3162a68bf5) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | Notebook    | [d764e72d74](https://linux-hardware.org/?probe=d764e72d74) | Sep 12, 2022 |
| Alienware     | M14xR1                      | Notebook    | [ea2adf914b](https://linux-hardware.org/?probe=ea2adf914b) | Sep 10, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [3310a4c592](https://linux-hardware.org/?probe=3310a4c592) | Sep 02, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [1918459ea4](https://linux-hardware.org/?probe=1918459ea4) | Sep 02, 2022 |
| Vorke         | V1 Plus                     | Desktop     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [25e7e97937](https://linux-hardware.org/?probe=25e7e97937) | Aug 29, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9b0e2c480f](https://linux-hardware.org/?probe=9b0e2c480f) | Aug 28, 2022 |
| Alienware     | M14xR1                      | Notebook    | [498d5f5254](https://linux-hardware.org/?probe=498d5f5254) | Aug 27, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [398f6d4b78](https://linux-hardware.org/?probe=398f6d4b78) | Aug 25, 2022 |
| Dell          | 0PU052                      | Desktop     | [2bffd37724](https://linux-hardware.org/?probe=2bffd37724) | Aug 24, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [23316377ee](https://linux-hardware.org/?probe=23316377ee) | Aug 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [9630e2d4f5](https://linux-hardware.org/?probe=9630e2d4f5) | Aug 21, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [ee6cfb6de5](https://linux-hardware.org/?probe=ee6cfb6de5) | Aug 19, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [0aefa0613d](https://linux-hardware.org/?probe=0aefa0613d) | Aug 15, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [d000ce4d8c](https://linux-hardware.org/?probe=d000ce4d8c) | Aug 15, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [66a759db9c](https://linux-hardware.org/?probe=66a759db9c) | Aug 14, 2022 |
| Acer          | Peppy                       | Notebook    | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [30715e2f04](https://linux-hardware.org/?probe=30715e2f04) | Aug 01, 2022 |
| GPD           | G1619-02                    | Notebook    | [c61c4280c8](https://linux-hardware.org/?probe=c61c4280c8) | Jul 31, 2022 |
| Lenovo        | ThinkCentre M58 7359DHJ     | Desktop     | [46c2c1db62](https://linux-hardware.org/?probe=46c2c1db62) | Jul 26, 2022 |
| ONDA          | H110-MINI V3.00 Ver:3.00    | Desktop     | [62b2a7897b](https://linux-hardware.org/?probe=62b2a7897b) | Jul 24, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8dd3e52620](https://linux-hardware.org/?probe=8dd3e52620) | Jul 21, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [82b077a668](https://linux-hardware.org/?probe=82b077a668) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [aa2a721361](https://linux-hardware.org/?probe=aa2a721361) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [1c3c80b88e](https://linux-hardware.org/?probe=1c3c80b88e) | Jul 13, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [0287348f80](https://linux-hardware.org/?probe=0287348f80) | Jul 12, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [616a2b7524](https://linux-hardware.org/?probe=616a2b7524) | Jul 12, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [71758de9e1](https://linux-hardware.org/?probe=71758de9e1) | Jul 06, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [39c0379cee](https://linux-hardware.org/?probe=39c0379cee) | Jul 04, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [5540b74d09](https://linux-hardware.org/?probe=5540b74d09) | Jul 03, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [c793608515](https://linux-hardware.org/?probe=c793608515) | Jul 03, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [4857a7b7bf](https://linux-hardware.org/?probe=4857a7b7bf) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [c5a5b25674](https://linux-hardware.org/?probe=c5a5b25674) | Jun 28, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [c292904665](https://linux-hardware.org/?probe=c292904665) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2a4d1c8a0b](https://linux-hardware.org/?probe=2a4d1c8a0b) | Jun 19, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [35c05116d1](https://linux-hardware.org/?probe=35c05116d1) | Jun 16, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [4692c93a71](https://linux-hardware.org/?probe=4692c93a71) | Jun 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| ASUSTek       | K42Jc                       | Notebook    | [29538e9e80](https://linux-hardware.org/?probe=29538e9e80) | May 21, 2022 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [d525e0eb0c](https://linux-hardware.org/?probe=d525e0eb0c) | May 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [0a9f8b0a4a](https://linux-hardware.org/?probe=0a9f8b0a4a) | May 09, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [f34555b3d6](https://linux-hardware.org/?probe=f34555b3d6) | Apr 30, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [43adb86887](https://linux-hardware.org/?probe=43adb86887) | Apr 25, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ba9b8d5ac1](https://linux-hardware.org/?probe=ba9b8d5ac1) | Apr 25, 2022 |
| ECS           | Iris8                       | Desktop     | [1cff4313c1](https://linux-hardware.org/?probe=1cff4313c1) | Apr 23, 2022 |
| HP            | 2B2C                        | Desktop     | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [c4456aaa4f](https://linux-hardware.org/?probe=c4456aaa4f) | Apr 19, 2022 |
| HP            | 2B2C                        | Desktop     | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| ILLEGEAR      | ROGUE                       | Notebook    | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ddd1338d3](https://linux-hardware.org/?probe=9ddd1338d3) | Apr 08, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [7ec10d98e3](https://linux-hardware.org/?probe=7ec10d98e3) | Apr 03, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [6cd967267b](https://linux-hardware.org/?probe=6cd967267b) | Mar 31, 2022 |
| Lenovo        | 30D9 NOK                    | Desktop     | [c378cd6fd3](https://linux-hardware.org/?probe=c378cd6fd3) | Mar 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [d9e3d65314](https://linux-hardware.org/?probe=d9e3d65314) | Mar 24, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell          | Inspiron 15 5501            | Notebook    | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a1c0612337](https://linux-hardware.org/?probe=a1c0612337) | Mar 17, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [d52d9feb9e](https://linux-hardware.org/?probe=d52d9feb9e) | Mar 09, 2022 |
| Dell          | Precision 7730              | Notebook    | [9e9710e890](https://linux-hardware.org/?probe=9e9710e890) | Mar 08, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [8d3f72c54f](https://linux-hardware.org/?probe=8d3f72c54f) | Mar 03, 2022 |
| Biostar       | G41D3+                      | Desktop     | [62ba30cf71](https://linux-hardware.org/?probe=62ba30cf71) | Mar 02, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [bbedea92ea](https://linux-hardware.org/?probe=bbedea92ea) | Mar 01, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [297c168632](https://linux-hardware.org/?probe=297c168632) | Mar 01, 2022 |
| Shuttle       | FH170                       | Desktop     | [768e13fd34](https://linux-hardware.org/?probe=768e13fd34) | Feb 25, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [1dec2ddfad](https://linux-hardware.org/?probe=1dec2ddfad) | Feb 19, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [747515703c](https://linux-hardware.org/?probe=747515703c) | Jan 25, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5d1c8ba7f2](https://linux-hardware.org/?probe=5d1c8ba7f2) | Jan 18, 2022 |
| Dell          | Precision 5550              | Notebook    | [6b866b7c2f](https://linux-hardware.org/?probe=6b866b7c2f) | Jan 18, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [7e0ee3374e](https://linux-hardware.org/?probe=7e0ee3374e) | Jan 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [ff2f0db3fe](https://linux-hardware.org/?probe=ff2f0db3fe) | Jan 09, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Lenovo        | ThinkStation S10 6483CTO    | Desktop     | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | Latitude 7490               | Notebook    | [4ac5151ac0](https://linux-hardware.org/?probe=4ac5151ac0) | Dec 29, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| MSI           | GL62M 7RDX                  | Notebook    | [3f8cb0706d](https://linux-hardware.org/?probe=3f8cb0706d) | Dec 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9fe5f60531](https://linux-hardware.org/?probe=9fe5f60531) | Dec 26, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c8ca1c8cc8](https://linux-hardware.org/?probe=c8ca1c8cc8) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | Notebook    | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Acer          | E3-112M-C6BV                | Notebook    | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [c748f77108](https://linux-hardware.org/?probe=c748f77108) | Dec 12, 2021 |
| HP            | 2B44                        | Desktop     | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| Dell          | Latitude E6520              | Notebook    | [faf1be45ae](https://linux-hardware.org/?probe=faf1be45ae) | Dec 03, 2021 |
| Dell          | Latitude E6520              | Notebook    | [16b69bfefc](https://linux-hardware.org/?probe=16b69bfefc) | Dec 01, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [eb4fb496ae](https://linux-hardware.org/?probe=eb4fb496ae) | Dec 01, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5c4ae3bd8c](https://linux-hardware.org/?probe=5c4ae3bd8c) | Nov 30, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c731d25471](https://linux-hardware.org/?probe=c731d25471) | Nov 30, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [6e5e669c60](https://linux-hardware.org/?probe=6e5e669c60) | Nov 25, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | Notebook    | [644d197332](https://linux-hardware.org/?probe=644d197332) | Nov 17, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | Notebook    | [bece194d5a](https://linux-hardware.org/?probe=bece194d5a) | Nov 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [b5393ad660](https://linux-hardware.org/?probe=b5393ad660) | Nov 12, 2021 |
| ASUSTek       | T200TA                      | Notebook    | [1f55c83774](https://linux-hardware.org/?probe=1f55c83774) | Nov 04, 2021 |
| ASUSTek       | M2N32-SLI DELUXE            | Desktop     | [87fff05f0f](https://linux-hardware.org/?probe=87fff05f0f) | Nov 03, 2021 |
| Lenovo        | U310                        | Notebook    | [986ba47618](https://linux-hardware.org/?probe=986ba47618) | Oct 24, 2021 |
| Lenovo        | U310                        | Notebook    | [c74a07756c](https://linux-hardware.org/?probe=c74a07756c) | Oct 24, 2021 |
| Intel         | B75                         | Desktop     | [fef715f491](https://linux-hardware.org/?probe=fef715f491) | Oct 23, 2021 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [ccd587fde5](https://linux-hardware.org/?probe=ccd587fde5) | Oct 21, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | Notebook                    | Notebook    | [2761140513](https://linux-hardware.org/?probe=2761140513) | Oct 14, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [8fee3106f7](https://linux-hardware.org/?probe=8fee3106f7) | Oct 12, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [f79000e059](https://linux-hardware.org/?probe=f79000e059) | Oct 12, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Biostar       | G41D3C                      | Desktop     | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [09b2cd1736](https://linux-hardware.org/?probe=09b2cd1736) | Oct 06, 2021 |
| Biostar       | G41D3C                      | Desktop     | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [07b1aa0f24](https://linux-hardware.org/?probe=07b1aa0f24) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [2cdb257de7](https://linux-hardware.org/?probe=2cdb257de7) | Sep 27, 2021 |
| HP            | Notebook                    | Notebook    | [32d9b71796](https://linux-hardware.org/?probe=32d9b71796) | Sep 25, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [17c3d61831](https://linux-hardware.org/?probe=17c3d61831) | Sep 21, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [1292424ff8](https://linux-hardware.org/?probe=1292424ff8) | Sep 17, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [7441498212](https://linux-hardware.org/?probe=7441498212) | Sep 14, 2021 |
| Lenovo        | Flex 6-11IGM 81A7           | Convertible | [17e78af479](https://linux-hardware.org/?probe=17e78af479) | Sep 14, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [c2533e9d48](https://linux-hardware.org/?probe=c2533e9d48) | Sep 11, 2021 |
| MSI           | H81M-P33                    | Desktop     | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [930ad79fe0](https://linux-hardware.org/?probe=930ad79fe0) | Sep 08, 2021 |
| Biostar       | G41D3C                      | Desktop     | [8137e09a97](https://linux-hardware.org/?probe=8137e09a97) | Sep 08, 2021 |
| Biostar       | G41D3C                      | Desktop     | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9c46f65e1d](https://linux-hardware.org/?probe=9c46f65e1d) | Sep 06, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| HP            | ENVY 4                      | Notebook    | [b61e9946e0](https://linux-hardware.org/?probe=b61e9946e0) | Sep 04, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5377e486bc](https://linux-hardware.org/?probe=5377e486bc) | Sep 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [acc6c11a97](https://linux-hardware.org/?probe=acc6c11a97) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [7b28a98a35](https://linux-hardware.org/?probe=7b28a98a35) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [7fada0ab8c](https://linux-hardware.org/?probe=7fada0ab8c) | Sep 01, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a61ee6d83a](https://linux-hardware.org/?probe=a61ee6d83a) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a1ec21ae3f](https://linux-hardware.org/?probe=a1ec21ae3f) | Aug 29, 2021 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [cac6720bff](https://linux-hardware.org/?probe=cac6720bff) | Aug 29, 2021 |
| Lenovo        | G400s VILG1                 | Notebook    | [20d6b25fd3](https://linux-hardware.org/?probe=20d6b25fd3) | Aug 29, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [777faedb05](https://linux-hardware.org/?probe=777faedb05) | Aug 27, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [9e8fa8f32d](https://linux-hardware.org/?probe=9e8fa8f32d) | Aug 23, 2021 |
| HP            | Notebook                    | Notebook    | [4028a5fb73](https://linux-hardware.org/?probe=4028a5fb73) | Aug 21, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [de1fa2ccc0](https://linux-hardware.org/?probe=de1fa2ccc0) | Aug 20, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [e359985b75](https://linux-hardware.org/?probe=e359985b75) | Aug 14, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [bb82d97c94](https://linux-hardware.org/?probe=bb82d97c94) | Aug 10, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [38abf3b8e9](https://linux-hardware.org/?probe=38abf3b8e9) | Aug 10, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [89188fe3ca](https://linux-hardware.org/?probe=89188fe3ca) | Aug 08, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3e56e95f2f](https://linux-hardware.org/?probe=3e56e95f2f) | Aug 05, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | Notebook    | [b10f021bef](https://linux-hardware.org/?probe=b10f021bef) | Aug 01, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [36562061d6](https://linux-hardware.org/?probe=36562061d6) | Jul 30, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | Notebook    | [4cf28c3600](https://linux-hardware.org/?probe=4cf28c3600) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| HP            | Notebook                    | Notebook    | [458741e8e2](https://linux-hardware.org/?probe=458741e8e2) | Jul 23, 2021 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [e71a7fc65b](https://linux-hardware.org/?probe=e71a7fc65b) | Jul 23, 2021 |
| HP            | Pavilion 14                 | Notebook    | [0556a517ff](https://linux-hardware.org/?probe=0556a517ff) | Jul 23, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [fe43d29e0e](https://linux-hardware.org/?probe=fe43d29e0e) | Jul 22, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [3e66028cf8](https://linux-hardware.org/?probe=3e66028cf8) | Jul 22, 2021 |
| ASUSTek       | K43SA                       | Notebook    | [3c81cd98ac](https://linux-hardware.org/?probe=3c81cd98ac) | Jul 21, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| ASUSTek       | K43SA                       | Notebook    | [3da0ea28fa](https://linux-hardware.org/?probe=3da0ea28fa) | Jul 20, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [5a349c4952](https://linux-hardware.org/?probe=5a349c4952) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [275304e806](https://linux-hardware.org/?probe=275304e806) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [99df792e3b](https://linux-hardware.org/?probe=99df792e3b) | Jul 18, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9ffbb5bc79](https://linux-hardware.org/?probe=9ffbb5bc79) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [0e8b29c721](https://linux-hardware.org/?probe=0e8b29c721) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [da8679ccca](https://linux-hardware.org/?probe=da8679ccca) | Jul 14, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [2495cf9be5](https://linux-hardware.org/?probe=2495cf9be5) | Jul 12, 2021 |
| HP            | Compaq 6530b (VA036PA#UU... | Notebook    | [ac0b6b96cc](https://linux-hardware.org/?probe=ac0b6b96cc) | Jul 11, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b551baea7d](https://linux-hardware.org/?probe=b551baea7d) | Jul 11, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [477a92a37e](https://linux-hardware.org/?probe=477a92a37e) | Jul 11, 2021 |
| HP            | Notebook                    | Notebook    | [2f040042a3](https://linux-hardware.org/?probe=2f040042a3) | Jul 10, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [82c73cf6be](https://linux-hardware.org/?probe=82c73cf6be) | Jul 09, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [4e555accb1](https://linux-hardware.org/?probe=4e555accb1) | Jul 08, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [416014c8b8](https://linux-hardware.org/?probe=416014c8b8) | Jul 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [a630867e0a](https://linux-hardware.org/?probe=a630867e0a) | Jul 06, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [e8965c736d](https://linux-hardware.org/?probe=e8965c736d) | Jul 05, 2021 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | Notebook    | [e1a02c3dcb](https://linux-hardware.org/?probe=e1a02c3dcb) | Jul 04, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [939fe39f71](https://linux-hardware.org/?probe=939fe39f71) | Jul 01, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [44c1472c85](https://linux-hardware.org/?probe=44c1472c85) | Jun 30, 2021 |
| AZW           | GT-R                        | Notebook    | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [de1dbcbd7f](https://linux-hardware.org/?probe=de1dbcbd7f) | Jun 27, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [ddb8152ea4](https://linux-hardware.org/?probe=ddb8152ea4) | Jun 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [1104a3ca5a](https://linux-hardware.org/?probe=1104a3ca5a) | Jun 26, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a5a80d3f13](https://linux-hardware.org/?probe=a5a80d3f13) | Jun 24, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [d9270ab2c1](https://linux-hardware.org/?probe=d9270ab2c1) | Jun 23, 2021 |
| Lenovo        | ThinkPad X201 3626RZ4       | Notebook    | [737819a617](https://linux-hardware.org/?probe=737819a617) | Jun 22, 2021 |
| HP            | Notebook                    | Notebook    | [0f663cf796](https://linux-hardware.org/?probe=0f663cf796) | Jun 20, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [9a397ba3b9](https://linux-hardware.org/?probe=9a397ba3b9) | Jun 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [0183eeb644](https://linux-hardware.org/?probe=0183eeb644) | Jun 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [b0ded1652a](https://linux-hardware.org/?probe=b0ded1652a) | Jun 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e4a2d2d3c9](https://linux-hardware.org/?probe=e4a2d2d3c9) | Jun 06, 2021 |
| MSI           | H81M-P33                    | Desktop     | [69a8b43e74](https://linux-hardware.org/?probe=69a8b43e74) | Jun 02, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a67e6bcfce](https://linux-hardware.org/?probe=a67e6bcfce) | Jun 02, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [49a2755ccd](https://linux-hardware.org/?probe=49a2755ccd) | May 31, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [00658a23ab](https://linux-hardware.org/?probe=00658a23ab) | May 27, 2021 |
| Lenovo        | ThinkPad X120e 0611CTO      | Notebook    | [72608b2ea0](https://linux-hardware.org/?probe=72608b2ea0) | May 27, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [5f39051050](https://linux-hardware.org/?probe=5f39051050) | May 26, 2021 |
| Dell          | Inspiron 3443               | Notebook    | [1a314f201b](https://linux-hardware.org/?probe=1a314f201b) | May 26, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [4c5c7570f6](https://linux-hardware.org/?probe=4c5c7570f6) | May 25, 2021 |
| HP            | Notebook                    | Notebook    | [a075cb3a8d](https://linux-hardware.org/?probe=a075cb3a8d) | May 24, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [2b0de1ba10](https://linux-hardware.org/?probe=2b0de1ba10) | May 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [021e17aa96](https://linux-hardware.org/?probe=021e17aa96) | May 19, 2021 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [0cd0f0c51f](https://linux-hardware.org/?probe=0cd0f0c51f) | May 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [71f7778600](https://linux-hardware.org/?probe=71f7778600) | May 13, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [d6ab5352b8](https://linux-hardware.org/?probe=d6ab5352b8) | May 10, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [67e6985b08](https://linux-hardware.org/?probe=67e6985b08) | May 02, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [8624f1c148](https://linux-hardware.org/?probe=8624f1c148) | Apr 30, 2021 |
| HP            | 0AA8h                       | Desktop     | [5f350b471f](https://linux-hardware.org/?probe=5f350b471f) | Apr 29, 2021 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [6bb8ea7872](https://linux-hardware.org/?probe=6bb8ea7872) | Apr 23, 2021 |
| System76      | Galago Pro                  | Notebook    | [e712e1fadc](https://linux-hardware.org/?probe=e712e1fadc) | Apr 21, 2021 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [07efcf431f](https://linux-hardware.org/?probe=07efcf431f) | Apr 14, 2021 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [9f265d798d](https://linux-hardware.org/?probe=9f265d798d) | Apr 14, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [87041c97fb](https://linux-hardware.org/?probe=87041c97fb) | Apr 14, 2021 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [6d3642385e](https://linux-hardware.org/?probe=6d3642385e) | Apr 11, 2021 |
| HP            | 2B1C MVB,A                  | All in one  | [ea47f5adbe](https://linux-hardware.org/?probe=ea47f5adbe) | Apr 05, 2021 |
| Dell          | XPS L412Z                   | Notebook    | [e383c24416](https://linux-hardware.org/?probe=e383c24416) | Apr 01, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [006be2bbab](https://linux-hardware.org/?probe=006be2bbab) | Mar 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [1a6bdfe860](https://linux-hardware.org/?probe=1a6bdfe860) | Mar 22, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [7a17fa61d9](https://linux-hardware.org/?probe=7a17fa61d9) | Mar 17, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [d476794634](https://linux-hardware.org/?probe=d476794634) | Mar 16, 2021 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [fc405347a5](https://linux-hardware.org/?probe=fc405347a5) | Mar 12, 2021 |
| Sony          | VPCEA42EG                   | Notebook    | [e49095cfef](https://linux-hardware.org/?probe=e49095cfef) | Mar 09, 2021 |
| ASUSTek       | S550CM                      | Notebook    | [5ac3e9de20](https://linux-hardware.org/?probe=5ac3e9de20) | Mar 08, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [597b4f88b9](https://linux-hardware.org/?probe=597b4f88b9) | Mar 08, 2021 |
| HP            | Presario CQ43               | Notebook    | [4f9c0e744c](https://linux-hardware.org/?probe=4f9c0e744c) | Feb 28, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [082f8fd3e5](https://linux-hardware.org/?probe=082f8fd3e5) | Feb 27, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [1555ed8743](https://linux-hardware.org/?probe=1555ed8743) | Feb 27, 2021 |
| ASUSTek       | H110M-D                     | Desktop     | [19e3cff2be](https://linux-hardware.org/?probe=19e3cff2be) | Feb 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [4f82ee745a](https://linux-hardware.org/?probe=4f82ee745a) | Feb 25, 2021 |
| HP            | Presario CQ43               | Notebook    | [e6e7199511](https://linux-hardware.org/?probe=e6e7199511) | Feb 22, 2021 |
| ASUSTek       | X456UF                      | Notebook    | [f69a109f5c](https://linux-hardware.org/?probe=f69a109f5c) | Feb 14, 2021 |
| HP            | G42                         | Notebook    | [7e1ebb9cf3](https://linux-hardware.org/?probe=7e1ebb9cf3) | Feb 13, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [6c0820678b](https://linux-hardware.org/?probe=6c0820678b) | Feb 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [92518dacfe](https://linux-hardware.org/?probe=92518dacfe) | Feb 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4f8464acc9](https://linux-hardware.org/?probe=4f8464acc9) | Feb 10, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [b50872caf4](https://linux-hardware.org/?probe=b50872caf4) | Feb 07, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [7daa68908c](https://linux-hardware.org/?probe=7daa68908c) | Feb 06, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [acb369859f](https://linux-hardware.org/?probe=acb369859f) | Feb 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [aa40d0ff2b](https://linux-hardware.org/?probe=aa40d0ff2b) | Feb 04, 2021 |
| Acer          | Veriton X6630G V:1.0        | Desktop     | [d6126d9f25](https://linux-hardware.org/?probe=d6126d9f25) | Jan 27, 2021 |
| Acer          | Veriton X6630G V:1.0        | Desktop     | [9e5a28d45d](https://linux-hardware.org/?probe=9e5a28d45d) | Jan 27, 2021 |
| Dell          | 0WR7PY A01                  | Desktop     | [9b13ab689f](https://linux-hardware.org/?probe=9b13ab689f) | Jan 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [31faebfa48](https://linux-hardware.org/?probe=31faebfa48) | Jan 23, 2021 |
| Dell          | Latitude 3440               | Notebook    | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [353fb07166](https://linux-hardware.org/?probe=353fb07166) | Jan 20, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [dd87c824a0](https://linux-hardware.org/?probe=dd87c824a0) | Jan 18, 2021 |
| HP            | G42                         | Notebook    | [b4a8c3727b](https://linux-hardware.org/?probe=b4a8c3727b) | Jan 13, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9e291d5782](https://linux-hardware.org/?probe=9e291d5782) | Jan 12, 2021 |
| HP            | Notebook                    | Notebook    | [6bb93d5d1d](https://linux-hardware.org/?probe=6bb93d5d1d) | Jan 03, 2021 |
| HP            | Presario CQ43               | Notebook    | [d410f07eef](https://linux-hardware.org/?probe=d410f07eef) | Jan 03, 2021 |
| HP            | Presario CQ43               | Notebook    | [15ba146bfe](https://linux-hardware.org/?probe=15ba146bfe) | Jan 03, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [f3c691cbf8](https://linux-hardware.org/?probe=f3c691cbf8) | Jan 01, 2021 |
| MSI           | H81M-P33                    | Desktop     | [e8d73a49e5](https://linux-hardware.org/?probe=e8d73a49e5) | Dec 30, 2020 |
| HP            | Pavilion g4                 | Notebook    | [c495b342b0](https://linux-hardware.org/?probe=c495b342b0) | Dec 30, 2020 |
| ASUSTek       | TP500LN                     | Notebook    | [36ae52e7d3](https://linux-hardware.org/?probe=36ae52e7d3) | Dec 27, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [fa76a31b79](https://linux-hardware.org/?probe=fa76a31b79) | Dec 24, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [7e473c8d12](https://linux-hardware.org/?probe=7e473c8d12) | Dec 24, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [645dfe5a80](https://linux-hardware.org/?probe=645dfe5a80) | Dec 23, 2020 |
| Dell          | 0PU052                      | Desktop     | [520a4ef3d0](https://linux-hardware.org/?probe=520a4ef3d0) | Dec 23, 2020 |
| Biostar       | A320MH                      | Desktop     | [a6b1134a37](https://linux-hardware.org/?probe=a6b1134a37) | Dec 18, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [41d76fb580](https://linux-hardware.org/?probe=41d76fb580) | Dec 17, 2020 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [a0b90b128d](https://linux-hardware.org/?probe=a0b90b128d) | Dec 16, 2020 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [9af064ae47](https://linux-hardware.org/?probe=9af064ae47) | Dec 16, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [414fc579a1](https://linux-hardware.org/?probe=414fc579a1) | Dec 02, 2020 |
| HP            | 2B1C MVB,A                  | All in one  | [4d1d3b1722](https://linux-hardware.org/?probe=4d1d3b1722) | Dec 02, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [cf6242caca](https://linux-hardware.org/?probe=cf6242caca) | Dec 02, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [afbf8ce7bc](https://linux-hardware.org/?probe=afbf8ce7bc) | Dec 01, 2020 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [967bb7f4d6](https://linux-hardware.org/?probe=967bb7f4d6) | Nov 30, 2020 |
| HP            | 2B1C MVB,A                  | All in one  | [400561434f](https://linux-hardware.org/?probe=400561434f) | Nov 27, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [151262b7a2](https://linux-hardware.org/?probe=151262b7a2) | Nov 26, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eecae3dcbf](https://linux-hardware.org/?probe=eecae3dcbf) | Nov 26, 2020 |
| Dell          | G3 3590                     | Notebook    | [d76accb676](https://linux-hardware.org/?probe=d76accb676) | Nov 18, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [c323f09a39](https://linux-hardware.org/?probe=c323f09a39) | Nov 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [db8eeca79f](https://linux-hardware.org/?probe=db8eeca79f) | Nov 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [f617d36143](https://linux-hardware.org/?probe=f617d36143) | Nov 12, 2020 |
| Gigabyte      | Z490 VISION D               | Desktop     | [af58d1579d](https://linux-hardware.org/?probe=af58d1579d) | Nov 09, 2020 |
| Acer          | TM4750                      | Notebook    | [8380f08a89](https://linux-hardware.org/?probe=8380f08a89) | Nov 07, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [4c1052e401](https://linux-hardware.org/?probe=4c1052e401) | Nov 06, 2020 |
| Dell          | G3 3590                     | Notebook    | [b2a86aaf94](https://linux-hardware.org/?probe=b2a86aaf94) | Nov 04, 2020 |
| Dell          | Latitude E6530              | Notebook    | [50772450d3](https://linux-hardware.org/?probe=50772450d3) | Nov 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [1a5aef928b](https://linux-hardware.org/?probe=1a5aef928b) | Nov 01, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [5021546be8](https://linux-hardware.org/?probe=5021546be8) | Oct 30, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [adc51544ee](https://linux-hardware.org/?probe=adc51544ee) | Oct 29, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | Notebook    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Acer          | TM4750                      | Notebook    | [2f46c4d024](https://linux-hardware.org/?probe=2f46c4d024) | Oct 27, 2020 |
| Acer          | TM4750                      | Notebook    | [29124f29f8](https://linux-hardware.org/?probe=29124f29f8) | Oct 23, 2020 |
| Dell          | G3 3590                     | Notebook    | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b6aa803efb](https://linux-hardware.org/?probe=b6aa803efb) | Oct 21, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [02a2657831](https://linux-hardware.org/?probe=02a2657831) | Oct 20, 2020 |
| Dell          | 09WH54 A00                  | Desktop     | [5c8d0c0991](https://linux-hardware.org/?probe=5c8d0c0991) | Oct 15, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a37736727](https://linux-hardware.org/?probe=1a37736727) | Oct 13, 2020 |
| Dell          | 06D7TR A02                  | Desktop     | [1fff522fa1](https://linux-hardware.org/?probe=1fff522fa1) | Oct 13, 2020 |
| Dell          | 09WH54 A00                  | Desktop     | [e8e5a3c2ac](https://linux-hardware.org/?probe=e8e5a3c2ac) | Oct 12, 2020 |
| Sony          | VGN-Z27GN_X                 | Notebook    | [a9230212d3](https://linux-hardware.org/?probe=a9230212d3) | Oct 03, 2020 |
| Unknown       | Unknown                     | Notebook    | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [80297bebea](https://linux-hardware.org/?probe=80297bebea) | Sep 17, 2020 |
| HP            | Pavilion dv6                | Notebook    | [f48a018bbb](https://linux-hardware.org/?probe=f48a018bbb) | Sep 16, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [5eaf26f820](https://linux-hardware.org/?probe=5eaf26f820) | Sep 15, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [4e3ee75e9b](https://linux-hardware.org/?probe=4e3ee75e9b) | Sep 15, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f7f932b330](https://linux-hardware.org/?probe=f7f932b330) | Sep 14, 2020 |
| Acer          | Aspire ES1-420              | Notebook    | [730ae12528](https://linux-hardware.org/?probe=730ae12528) | Sep 10, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [828c695fab](https://linux-hardware.org/?probe=828c695fab) | Sep 06, 2020 |
| HP            | Pavilion dv6                | Notebook    | [47c4b0fdaa](https://linux-hardware.org/?probe=47c4b0fdaa) | Sep 03, 2020 |
| Dell          | Inspiron 5482               | Convertible | [4085a729ac](https://linux-hardware.org/?probe=4085a729ac) | Sep 03, 2020 |
| Dell          | 0RW203                      | Desktop     | [594ab9e6d3](https://linux-hardware.org/?probe=594ab9e6d3) | Sep 02, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [0930a62ca5](https://linux-hardware.org/?probe=0930a62ca5) | Aug 21, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| ASUSTek       | VivoBook S15 X530UN         | Notebook    | [64e65fe674](https://linux-hardware.org/?probe=64e65fe674) | Aug 11, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [bc44361c47](https://linux-hardware.org/?probe=bc44361c47) | Aug 02, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [e8cc620228](https://linux-hardware.org/?probe=e8cc620228) | Aug 02, 2020 |
| Unknown       | Unknown                     | Phone       | [38378b572a](https://linux-hardware.org/?probe=38378b572a) | Aug 01, 2020 |
| HP            | Presario CQ43               | Notebook    | [df780756ee](https://linux-hardware.org/?probe=df780756ee) | Jul 31, 2020 |
| HP            | Presario CQ43               | Notebook    | [102ab797a7](https://linux-hardware.org/?probe=102ab797a7) | Jul 31, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3f99c1674c](https://linux-hardware.org/?probe=3f99c1674c) | Jul 30, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [dbbc5219fd](https://linux-hardware.org/?probe=dbbc5219fd) | Jul 27, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [c85ae35bff](https://linux-hardware.org/?probe=c85ae35bff) | Jul 25, 2020 |
| Dell          | Latitude 7285               | Tablet      | [ed3aa05fd5](https://linux-hardware.org/?probe=ed3aa05fd5) | Jul 25, 2020 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [81e5774167](https://linux-hardware.org/?probe=81e5774167) | Jul 24, 2020 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [1856c4ccbf](https://linux-hardware.org/?probe=1856c4ccbf) | Jul 23, 2020 |
| Dell          | Latitude 7480               | Notebook    | [7fa880215f](https://linux-hardware.org/?probe=7fa880215f) | Jul 21, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [2bfaffc9c5](https://linux-hardware.org/?probe=2bfaffc9c5) | Jul 21, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [7b83e5785f](https://linux-hardware.org/?probe=7b83e5785f) | Jul 19, 2020 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [d45acf2543](https://linux-hardware.org/?probe=d45acf2543) | Jul 18, 2020 |
| Unknown       | Unknown                     | Phone       | [c0d8474803](https://linux-hardware.org/?probe=c0d8474803) | Jul 18, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [4b144fb616](https://linux-hardware.org/?probe=4b144fb616) | Jul 14, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [7d9a43933e](https://linux-hardware.org/?probe=7d9a43933e) | Jul 14, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [48cdbb3d36](https://linux-hardware.org/?probe=48cdbb3d36) | Jul 11, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [f5ff1447a7](https://linux-hardware.org/?probe=f5ff1447a7) | Jul 08, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [a97a2e14e2](https://linux-hardware.org/?probe=a97a2e14e2) | Jul 06, 2020 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [0aa18d5241](https://linux-hardware.org/?probe=0aa18d5241) | Jul 05, 2020 |
| Dell          | Latitude E6440              | Notebook    | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5d32eb1d75](https://linux-hardware.org/?probe=5d32eb1d75) | Jun 30, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [33534eca13](https://linux-hardware.org/?probe=33534eca13) | Jun 28, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6ae79e439f](https://linux-hardware.org/?probe=6ae79e439f) | Jun 28, 2020 |
| Acer          | Aspire 4738                 | Notebook    | [519a7577c0](https://linux-hardware.org/?probe=519a7577c0) | Jun 28, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [0cd3f983c9](https://linux-hardware.org/?probe=0cd3f983c9) | Jun 26, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [bad4de6363](https://linux-hardware.org/?probe=bad4de6363) | Jun 26, 2020 |
| Dell          | Latitude E6440              | Notebook    | [1ffde1aa78](https://linux-hardware.org/?probe=1ffde1aa78) | Jun 24, 2020 |
| HP            | Pavilion dv6                | Notebook    | [4833031b9b](https://linux-hardware.org/?probe=4833031b9b) | Jun 23, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [99ff555015](https://linux-hardware.org/?probe=99ff555015) | Jun 21, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [05556ef252](https://linux-hardware.org/?probe=05556ef252) | Jun 19, 2020 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0a15b3f355](https://linux-hardware.org/?probe=0a15b3f355) | Jun 18, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [eac1260628](https://linux-hardware.org/?probe=eac1260628) | Jun 17, 2020 |
| Unknown       | Unknown                     | Phone       | [6566b884d6](https://linux-hardware.org/?probe=6566b884d6) | Jun 15, 2020 |
| ASUSTek       | G551JM                      | Notebook    | [3ab69ab51e](https://linux-hardware.org/?probe=3ab69ab51e) | Jun 10, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [ba4a677fab](https://linux-hardware.org/?probe=ba4a677fab) | Jun 10, 2020 |
| HP            | 14                          | Notebook    | [5a36b38b50](https://linux-hardware.org/?probe=5a36b38b50) | Jun 07, 2020 |
| Fujitsu       | LIFEBOOK S761               | Notebook    | [7d4e0682de](https://linux-hardware.org/?probe=7d4e0682de) | Jun 07, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [6c1d889b0d](https://linux-hardware.org/?probe=6c1d889b0d) | Jun 06, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [709dcae624](https://linux-hardware.org/?probe=709dcae624) | Jun 06, 2020 |
| MSI           | A320M-A PRO MAX             | Desktop     | [11c6b72a1b](https://linux-hardware.org/?probe=11c6b72a1b) | Jun 03, 2020 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ecf8e72f94](https://linux-hardware.org/?probe=ecf8e72f94) | May 31, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [b335d617f7](https://linux-hardware.org/?probe=b335d617f7) | May 26, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [865933043f](https://linux-hardware.org/?probe=865933043f) | May 26, 2020 |
| Acer          | EQ45M                       | Desktop     | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [d2113ac640](https://linux-hardware.org/?probe=d2113ac640) | May 21, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [1882c535de](https://linux-hardware.org/?probe=1882c535de) | May 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [445fc4fef9](https://linux-hardware.org/?probe=445fc4fef9) | May 19, 2020 |
| Dell          | 0PU052                      | Desktop     | [40ab4a84b5](https://linux-hardware.org/?probe=40ab4a84b5) | May 18, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8156a3eef6](https://linux-hardware.org/?probe=8156a3eef6) | May 11, 2020 |
| SNS Networ... | JOI Book 150                | Notebook    | [3d61c3722c](https://linux-hardware.org/?probe=3d61c3722c) | May 11, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [f92d9768ce](https://linux-hardware.org/?probe=f92d9768ce) | May 07, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [b119ccc5f2](https://linux-hardware.org/?probe=b119ccc5f2) | May 07, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4893a0cfcd](https://linux-hardware.org/?probe=4893a0cfcd) | May 06, 2020 |
| Dell          | 0RY007                      | Desktop     | [4d44e2723d](https://linux-hardware.org/?probe=4d44e2723d) | May 04, 2020 |
| HP            | 14                          | Notebook    | [c0318bc179](https://linux-hardware.org/?probe=c0318bc179) | Apr 30, 2020 |
| Acer          | EQ45M                       | Desktop     | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| Dell          | 0C3YXR A01                  | Desktop     | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| BUSH          | Windows tablet              | Notebook    | [a25abad9de](https://linux-hardware.org/?probe=a25abad9de) | Apr 18, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [9c68002e3d](https://linux-hardware.org/?probe=9c68002e3d) | Apr 13, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [0444963962](https://linux-hardware.org/?probe=0444963962) | Apr 12, 2020 |
| MSI           | B150M Night Elf             | Desktop     | [01013b611d](https://linux-hardware.org/?probe=01013b611d) | Apr 11, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [1211d7770c](https://linux-hardware.org/?probe=1211d7770c) | Mar 15, 2020 |
| Acer          | TM4750                      | Notebook    | [bedf724360](https://linux-hardware.org/?probe=bedf724360) | Mar 11, 2020 |
| Acer          | TM4750                      | Notebook    | [db9b7453f2](https://linux-hardware.org/?probe=db9b7453f2) | Mar 11, 2020 |
| Acer          | TM4750                      | Notebook    | [69bbe5f0ee](https://linux-hardware.org/?probe=69bbe5f0ee) | Mar 11, 2020 |
| Dell          | Inspiron 1464               | Notebook    | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Dell          | 0JWGHC A01                  | All in one  | [46ad418d75](https://linux-hardware.org/?probe=46ad418d75) | Feb 24, 2020 |
| Dell          | 0JWGHC A01                  | All in one  | [c1b65d99ff](https://linux-hardware.org/?probe=c1b65d99ff) | Feb 23, 2020 |
| Teclast       | F5                          | Convertible | [23690a5a6e](https://linux-hardware.org/?probe=23690a5a6e) | Feb 16, 2020 |
| Acer          | Aspire 4736Z                | Notebook    | [a6e2ff9c02](https://linux-hardware.org/?probe=a6e2ff9c02) | Feb 15, 2020 |
| ASUSTek       | P6T SE                      | Desktop     | [05737b4c23](https://linux-hardware.org/?probe=05737b4c23) | Feb 11, 2020 |
| HP            | 3647h                       | Desktop     | [06df72e240](https://linux-hardware.org/?probe=06df72e240) | Feb 08, 2020 |
| HP            | ProBook 645 G1              | Notebook    | [18fb680615](https://linux-hardware.org/?probe=18fb680615) | Feb 04, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [5ab23205d8](https://linux-hardware.org/?probe=5ab23205d8) | Jan 21, 2020 |
| ASUSTek       | P8Z77-M                     | Desktop     | [9247337003](https://linux-hardware.org/?probe=9247337003) | Jan 20, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [1b04478121](https://linux-hardware.org/?probe=1b04478121) | Jan 14, 2020 |
| Chuwi         | LapBook Pro                 | Notebook    | [f9d248ac7c](https://linux-hardware.org/?probe=f9d248ac7c) | Jan 03, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3b64de1ec8](https://linux-hardware.org/?probe=3b64de1ec8) | Dec 31, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [31643f4ace](https://linux-hardware.org/?probe=31643f4ace) | Dec 31, 2019 |
| Lenovo        | G500s 20245                 | Notebook    | [82346138d0](https://linux-hardware.org/?probe=82346138d0) | Dec 30, 2019 |
| HP            | ProBook 4545s               | Notebook    | [66e278f8a6](https://linux-hardware.org/?probe=66e278f8a6) | Dec 29, 2019 |
| HP            | ProBook 4545s               | Notebook    | [7c1a6a786f](https://linux-hardware.org/?probe=7c1a6a786f) | Dec 29, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [02d013ad00](https://linux-hardware.org/?probe=02d013ad00) | Dec 20, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f4689330d7](https://linux-hardware.org/?probe=f4689330d7) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [d651477524](https://linux-hardware.org/?probe=d651477524) | Dec 14, 2019 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c0c7973b78](https://linux-hardware.org/?probe=c0c7973b78) | Nov 20, 2019 |
| Supermicro    | K1SPE-IN001                 | Server      | [5f6d0233a8](https://linux-hardware.org/?probe=5f6d0233a8) | Nov 18, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [9e78c03471](https://linux-hardware.org/?probe=9e78c03471) | Nov 17, 2019 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [875f14ed53](https://linux-hardware.org/?probe=875f14ed53) | Nov 13, 2019 |
| Dell          | Vostro V130                 | Notebook    | [ca716fdbad](https://linux-hardware.org/?probe=ca716fdbad) | Nov 09, 2019 |
| Dell          | Vostro V130                 | Notebook    | [0ba8558483](https://linux-hardware.org/?probe=0ba8558483) | Nov 08, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [7ce70fa206](https://linux-hardware.org/?probe=7ce70fa206) | Oct 25, 2019 |
| Acer          | Swift SF314-55G             | Notebook    | [8526e89541](https://linux-hardware.org/?probe=8526e89541) | Oct 16, 2019 |
| ASUSTek       | X456URK                     | Notebook    | [03b7432783](https://linux-hardware.org/?probe=03b7432783) | Oct 10, 2019 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [b37e090603](https://linux-hardware.org/?probe=b37e090603) | Oct 06, 2019 |
| HP            | 0AA8h                       | Desktop     | [a60543a450](https://linux-hardware.org/?probe=a60543a450) | Sep 07, 2019 |
| HP            | ZBook 15                    | Notebook    | [f9aaccbfe0](https://linux-hardware.org/?probe=f9aaccbfe0) | Sep 06, 2019 |
| Dell          | Latitude E7440              | Notebook    | [04bd492077](https://linux-hardware.org/?probe=04bd492077) | Sep 06, 2019 |
| MSI           | GP70 2PE                    | Notebook    | [ae117eb491](https://linux-hardware.org/?probe=ae117eb491) | Sep 03, 2019 |
| Dell          | 0RY007                      | Desktop     | [576ec7dcd0](https://linux-hardware.org/?probe=576ec7dcd0) | Aug 22, 2019 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [d9d789a4f2](https://linux-hardware.org/?probe=d9d789a4f2) | Aug 21, 2019 |
| MSI           | GP70 2PE                    | Notebook    | [3442bbe40c](https://linux-hardware.org/?probe=3442bbe40c) | Aug 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f8d49fa793](https://linux-hardware.org/?probe=f8d49fa793) | Aug 03, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [46b9ff1fff](https://linux-hardware.org/?probe=46b9ff1fff) | Aug 03, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [a91c21a426](https://linux-hardware.org/?probe=a91c21a426) | Aug 02, 2019 |
| HP            | ProLiant DL60 Gen9          | Server      | [140daf886e](https://linux-hardware.org/?probe=140daf886e) | Jul 24, 2019 |
| ASUSTek       | H81M-C                      | Desktop     | [38a96dff85](https://linux-hardware.org/?probe=38a96dff85) | Jul 02, 2019 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [62b0b05a66](https://linux-hardware.org/?probe=62b0b05a66) | Jul 01, 2019 |
| ASUSTek       | X450CP                      | Notebook    | [2931234c98](https://linux-hardware.org/?probe=2931234c98) | May 02, 2019 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [c7b00947af](https://linux-hardware.org/?probe=c7b00947af) | Apr 30, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [35e3cab7fd](https://linux-hardware.org/?probe=35e3cab7fd) | Apr 24, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3783735e9b](https://linux-hardware.org/?probe=3783735e9b) | Apr 23, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [672cf7aa7f](https://linux-hardware.org/?probe=672cf7aa7f) | Apr 20, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [5202aae85e](https://linux-hardware.org/?probe=5202aae85e) | Feb 26, 2019 |
| ASUSTek       | X101H                       | Notebook    | [bfa018d76d](https://linux-hardware.org/?probe=bfa018d76d) | Jan 21, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [323f6e2eeb](https://linux-hardware.org/?probe=323f6e2eeb) | Dec 17, 2018 |
| ASRock        | X79 Extreme9                | Desktop     | [c96c05c47b](https://linux-hardware.org/?probe=c96c05c47b) | Nov 30, 2018 |
| Dell          | XPS L521X                   | Notebook    | [3f3c8f2571](https://linux-hardware.org/?probe=3f3c8f2571) | Nov 25, 2018 |
| Dell          | Latitude E6520              | Notebook    | [166d529d12](https://linux-hardware.org/?probe=166d529d12) | Nov 12, 2018 |
| HP            | 2820h                       | Desktop     | [1f42af0283](https://linux-hardware.org/?probe=1f42af0283) | Dec 17, 2017 |
| Dell          | XPS L412Z                   | Notebook    | [8381b26177](https://linux-hardware.org/?probe=8381b26177) | Jan 27, 2017 |
| Dell          | XPS L412Z                   | Notebook    | [799ee32fce](https://linux-hardware.org/?probe=799ee32fce) | Jan 21, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Malaysia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 64        | 9.29%   |
| Ubuntu 22.04                 | 41        | 5.95%   |
| Ubuntu 18.04                 | 25        | 3.63%   |
| Debian 11                    | 23        | 3.34%   |
| Pop!_OS 22.04                | 18        | 2.61%   |
| Zorin 16                     | 14        | 2.03%   |
| ArcoLinux Rolling            | 14        | 2.03%   |
| Arch Rolling                 | 14        | 2.03%   |
| OpenMandriva 4.3             | 13        | 1.89%   |
| OpenMandriva 23.08           | 12        | 1.74%   |
| Debian 12                    | 12        | 1.74%   |
| OpenMandriva 4.2             | 11        | 1.6%    |
| Ubuntu 24.04                 | 10        | 1.45%   |
| Pop!_OS 20.10                | 10        | 1.45%   |
| OpenMandriva 23.01           | 10        | 1.45%   |
| Fedora 40                    | 10        | 1.45%   |
| Zorin 17                     | 9         | 1.31%   |
| Pop!_OS 21.04                | 9         | 1.31%   |
| OpenMandriva 4.50            | 9         | 1.31%   |
| KDE neon 20.04               | 9         | 1.31%   |
| Pop!_OS 20.04                | 8         | 1.16%   |
| OpenMandriva 23.03           | 8         | 1.16%   |
| Fedora 33                    | 8         | 1.16%   |
| Ubuntu 19.04                 | 7         | 1.02%   |
| OpenMandriva 24.12           | 7         | 1.02%   |
| Fedora 41                    | 7         | 1.02%   |
| Fedora 39                    | 7         | 1.02%   |
| Fedora 37                    | 7         | 1.02%   |
| Ubuntu 23.04                 | 6         | 0.87%   |
| OpenMandriva 5.0             | 6         | 0.87%   |
| LMDE 6                       | 6         | 0.87%   |
| Linux Mint 19.3              | 6         | 0.87%   |
| Fedora 34                    | 6         | 0.87%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 0.73%   |
| Linux Mint 21.1              | 5         | 0.73%   |
| KDE neon 22.04               | 5         | 0.73%   |
| Fedora 38                    | 5         | 0.73%   |
| EndeavourOS Rolling          | 5         | 0.73%   |
| Arch                         | 5         | 0.73%   |
| Android                      | 5         | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 170       | 26.11%  |
| OpenMandriva  | 75        | 11.52%  |
| Fedora        | 51        | 7.83%   |
| Pop!_OS       | 43        | 6.61%   |
| Debian        | 40        | 6.14%   |
| Linux Mint    | 31        | 4.76%   |
| Zorin         | 27        | 4.15%   |
| Arch          | 19        | 2.92%   |
| KDE neon      | 15        | 2.3%    |
| Elementary    | 14        | 2.15%   |
| ArcoLinux     | 14        | 2.15%   |
| Manjaro       | 13        | 2%      |
| Lubuntu       | 10        | 1.54%   |
| Kubuntu       | 10        | 1.54%   |
| Xubuntu       | 9         | 1.38%   |
| Kali          | 9         | 1.38%   |
| openSUSE      | 8         | 1.23%   |
| Endless       | 8         | 1.23%   |
| LMDE          | 7         | 1.08%   |
| SteamOS       | 6         | 0.92%   |
| EndeavourOS   | 6         | 0.92%   |
| ROSA          | 5         | 0.77%   |
| Raspbian      | 5         | 0.77%   |
| Android       | 5         | 0.77%   |
| Xero          | 4         | 0.61%   |
| Ubuntu MATE   | 4         | 0.61%   |
| Nobara        | 4         | 0.61%   |
| CentOS        | 4         | 0.61%   |
| Ubuntu Unity  | 3         | 0.46%   |
| Ubuntu Budgie | 3         | 0.46%   |
| Ultramarine   | 2         | 0.31%   |
| Rocky Linux   | 2         | 0.31%   |
| NixOS         | 2         | 0.31%   |
| Gentoo        | 2         | 0.31%   |
| ChimeraOS     | 2         | 0.31%   |
| Archcraft     | 2         | 0.31%   |
| Vanilla       | 1         | 0.15%   |
| TUXEDO OS     | 1         | 0.15%   |
| Sparky        | 1         | 0.15%   |
| Slackware     | 1         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.4.11-desktop-1omv2390  | 10        | 1.29%   |
| 5.16.7-desktop-1omv4003  | 10        | 1.29%   |
| 5.10.14-desktop-1omv4002 | 10        | 1.29%   |
| 6.2.6-desktop-1omv2390   | 9         | 1.16%   |
| 5.4.0-58-generic         | 8         | 1.03%   |
| 5.4.0-42-generic         | 8         | 1.03%   |
| 6.1.1-desktop-1omv2290   | 7         | 0.9%    |
| 6.6.2-desktop-1omv2390   | 6         | 0.77%   |
| 6.12.1-desktop-1omv2490  | 6         | 0.77%   |
| 5.15.0-58-generic        | 6         | 0.77%   |
| 5.15.0-52-generic        | 6         | 0.77%   |
| 5.13.19-6-pve            | 6         | 0.77%   |
| 5.11.0-7620-generic      | 6         | 0.77%   |
| 6.8.0-31-generic         | 5         | 0.64%   |
| 6.5.0-27-generic         | 5         | 0.64%   |
| 6.5.0-14-generic         | 5         | 0.64%   |
| 6.2.6-76060206-generic   | 5         | 0.64%   |
| 6.1.0-25-amd64           | 5         | 0.64%   |
| 5.19.0-46-generic        | 5         | 0.64%   |
| 5.12.4-desktop-1omv4050  | 5         | 0.64%   |
| 5.11.0-27-generic        | 5         | 0.64%   |
| 6.8.0-49-generic         | 4         | 0.51%   |
| 6.3.9-arch1-1            | 4         | 0.51%   |
| 5.4.0-7634-generic       | 4         | 0.51%   |
| 5.4.0-40-generic         | 4         | 0.51%   |
| 5.15.126-1-pve           | 4         | 0.51%   |
| 5.15.108-1-pve           | 4         | 0.51%   |
| 5.15.0-91-generic        | 4         | 0.51%   |
| 5.15.0-89-generic        | 4         | 0.51%   |
| 5.15.0-56-generic        | 4         | 0.51%   |
| 5.13.0-22-generic        | 4         | 0.51%   |
| 5.0.0-37-generic         | 4         | 0.51%   |
| 6.8.11-300.fc40.x86_64   | 3         | 0.39%   |
| 6.8.0-51-generic         | 3         | 0.39%   |
| 6.8.0-45-generic         | 3         | 0.39%   |
| 6.8.0-44-generic         | 3         | 0.39%   |
| 6.5.0-28-generic         | 3         | 0.39%   |
| 6.5.0-21-generic         | 3         | 0.39%   |
| 6.2.0-33-generic         | 3         | 0.39%   |
| 6.0.12-76060006-generic  | 3         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 70        | 9.42%   |
| 5.15.0   | 52        | 7%      |
| 5.11.0   | 29        | 3.9%    |
| 6.5.0    | 27        | 3.63%   |
| 6.8.0    | 26        | 3.5%    |
| 5.8.0    | 26        | 3.5%    |
| 5.13.0   | 20        | 2.69%   |
| 4.15.0   | 20        | 2.69%   |
| 5.3.0    | 19        | 2.56%   |
| 5.0.0    | 18        | 2.42%   |
| 5.19.0   | 17        | 2.29%   |
| 6.1.0    | 16        | 2.15%   |
| 6.2.6    | 14        | 1.88%   |
| 6.2.0    | 12        | 1.62%   |
| 6.4.11   | 11        | 1.48%   |
| 5.16.7   | 10        | 1.35%   |
| 5.10.14  | 10        | 1.35%   |
| 6.1.1    | 8         | 1.08%   |
| 5.10.0   | 8         | 1.08%   |
| 6.6.2    | 7         | 0.94%   |
| 6.3.9    | 6         | 0.81%   |
| 6.12.1   | 6         | 0.81%   |
| 5.13.19  | 6         | 0.81%   |
| 4.18.0   | 6         | 0.81%   |
| 6.1.21   | 5         | 0.67%   |
| 6.0.12   | 5         | 0.67%   |
| 5.17.1   | 5         | 0.67%   |
| 5.12.4   | 5         | 0.67%   |
| 6.8.11   | 4         | 0.54%   |
| 6.5.6    | 4         | 0.54%   |
| 6.2.16   | 4         | 0.54%   |
| 5.18.0   | 4         | 0.54%   |
| 5.15.126 | 4         | 0.54%   |
| 5.15.108 | 4         | 0.54%   |
| 6.9.9    | 3         | 0.4%    |
| 6.9.3    | 3         | 0.4%    |
| 6.8.9    | 3         | 0.4%    |
| 6.8.2    | 3         | 0.4%    |
| 6.6.11   | 3         | 0.4%    |
| 6.5.5    | 3         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 74        | 10.29%  |
| 5.4     | 70        | 9.74%   |
| 6.8     | 39        | 5.42%   |
| 6.2     | 37        | 5.15%   |
| 6.1     | 37        | 5.15%   |
| 6.5     | 35        | 4.87%   |
| 5.11    | 34        | 4.73%   |
| 5.8     | 33        | 4.59%   |
| 5.13    | 29        | 4.03%   |
| 5.10    | 28        | 3.89%   |
| 6.4     | 24        | 3.34%   |
| 5.19    | 24        | 3.34%   |
| 6.6     | 23        | 3.2%    |
| 5.16    | 20        | 2.78%   |
| 4.15    | 20        | 2.78%   |
| 5.3     | 19        | 2.64%   |
| 5.0     | 18        | 2.5%    |
| 6.10    | 15        | 2.09%   |
| 6.3     | 14        | 1.95%   |
| 6.11    | 13        | 1.81%   |
| 5.12    | 13        | 1.81%   |
| 5.14    | 12        | 1.67%   |
| 6.9     | 11        | 1.53%   |
| 6.0     | 10        | 1.39%   |
| 6.12    | 9         | 1.25%   |
| 5.18    | 9         | 1.25%   |
| 5.17    | 9         | 1.25%   |
| 6.7     | 8         | 1.11%   |
| 5.9     | 8         | 1.11%   |
| 4.18    | 6         | 0.83%   |
| 4.9     | 3         | 0.42%   |
| 3.10    | 3         | 0.42%   |
| 5.7     | 2         | 0.28%   |
| 5.6     | 2         | 0.28%   |
| 4.4     | 2         | 0.28%   |
| 4.19    | 2         | 0.28%   |
| 3.18    | 2         | 0.28%   |
| 4.10    | 1         | 0.14%   |
| 4.1     | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 601       | 96.62%  |
| i686    | 6         | 0.96%   |
| aarch64 | 6         | 0.96%   |
| armv7l  | 4         | 0.64%   |
| armv8l  | 3         | 0.48%   |
| armv6l  | 2         | 0.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 282       | 42.53%  |
| KDE5          | 126       | 19%     |
| Unknown       | 67        | 10.11%  |
| XFCE          | 49        | 7.39%   |
| X-Cinnamon    | 32        | 4.83%   |
| MATE          | 15        | 2.26%   |
| KDE           | 15        | 2.26%   |
| Pantheon      | 14        | 2.11%   |
| LXQt          | 14        | 2.11%   |
| Openbox       | 13        | 1.96%   |
| KDE6          | 9         | 1.36%   |
| Budgie        | 5         | 0.75%   |
| Unity         | 3         | 0.45%   |
| i3            | 3         | 0.45%   |
| wayfire       | 2         | 0.3%    |
| LXDE          | 2         | 0.3%    |
| Hyprland      | 2         | 0.3%    |
| herbstluftwm  | 2         | 0.3%    |
| GNOME Classic | 2         | 0.3%    |
| bspwm         | 2         | 0.3%    |
| Peppermint    | 1         | 0.15%   |
| KDE4          | 1         | 0.15%   |
| fvwm3         | 1         | 0.15%   |
| Cinnamon      | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 438       | 66.77%  |
| Wayland | 161       | 24.54%  |
| Tty     | 33        | 5.03%   |
| Unknown | 24        | 3.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 296       | 46.03%  |
| SDDM    | 133       | 20.68%  |
| GDM3    | 84        | 13.06%  |
| LightDM | 71        | 11.04%  |
| GDM     | 52        | 8.09%   |
| TDM     | 5         | 0.78%   |
| LXDM    | 2         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 486       | 76.3%   |
| en_GB      | 46        | 7.22%   |
| Unknown    | 33        | 5.18%   |
| en_SG      | 30        | 4.71%   |
| C          | 12        | 1.88%   |
| zh_CN      | 6         | 0.94%   |
| en_AU      | 4         | 0.63%   |
| ms_MY      | 3         | 0.47%   |
| en_MY      | 3         | 0.47%   |
| en_HK      | 3         | 0.47%   |
| de_DE      | 3         | 0.47%   |
| zh_TW      | 2         | 0.31%   |
| zh_SG      | 1         | 0.16%   |
| zh_CN.UTF8 | 1         | 0.16%   |
| POSIX      | 1         | 0.16%   |
| ja_JP      | 1         | 0.16%   |
| id_ID      | 1         | 0.16%   |
| en_PH      | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 329       | 51.89%  |
| EFI  | 305       | 48.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 429       | 66.41%  |
| Btrfs    | 87        | 13.47%  |
| Overlay  | 54        | 8.36%   |
| Tmpfs    | 30        | 4.64%   |
| Zfs      | 16        | 2.48%   |
| Unknown  | 14        | 2.17%   |
| Xfs      | 12        | 1.86%   |
| Ext2     | 2         | 0.31%   |
| Ext3     | 1         | 0.15%   |
| Bcachefs | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 291       | 45.54%  |
| GPT     | 270       | 42.25%  |
| MBR     | 78        | 12.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 510       | 79.81%  |
| Yes       | 129       | 20.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 431       | 67.66%  |
| Yes       | 206       | 32.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 101       | 16.26%  |
| Dell                    | 88        | 14.17%  |
| Hewlett-Packard         | 82        | 13.2%   |
| Lenovo                  | 72        | 11.59%  |
| Gigabyte Technology     | 55        | 8.86%   |
| MSI                     | 38        | 6.12%   |
| Acer                    | 36        | 5.8%    |
| Intel                   | 23        | 3.7%    |
| ASRock                  | 16        | 2.58%   |
| Apple                   | 15        | 2.42%   |
| Unknown                 | 13        | 2.09%   |
| Raspberry Pi Foundation | 8         | 1.29%   |
| Fujitsu                 | 6         | 0.97%   |
| Toshiba                 | 5         | 0.81%   |
| Sony                    | 5         | 0.81%   |
| Google                  | 5         | 0.81%   |
| Biostar                 | 5         | 0.81%   |
| Valve                   | 4         | 0.64%   |
| HUAWEI                  | 4         | 0.64%   |
| Samsung Electronics     | 3         | 0.48%   |
| ILLEGEAR                | 3         | 0.48%   |
| ECS                     | 3         | 0.48%   |
| NEC Computers           | 2         | 0.32%   |
| Chuwi                   | 2         | 0.32%   |
| AZW                     | 2         | 0.32%   |
| ASRockRack              | 2         | 0.32%   |
| AMI                     | 2         | 0.32%   |
| Acidanthera             | 2         | 0.32%   |
| Xiaomi                  | 1         | 0.16%   |
| Vorke                   | 1         | 0.16%   |
| Timi                    | 1         | 0.16%   |
| Teclast                 | 1         | 0.16%   |
| SZMZ                    | 1         | 0.16%   |
| System76                | 1         | 0.16%   |
| Supermicro              | 1         | 0.16%   |
| SNS Network (M)         | 1         | 0.16%   |
| Shuttle                 | 1         | 0.16%   |
| Seco                    | 1         | 0.16%   |
| Rockchip                | 1         | 0.16%   |
| ONDA                    | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 14        | 2.25%   |
| Intel DH61WW AAG23116-204                | 8         | 1.29%   |
| ASUS All Series                          | 8         | 1.29%   |
| Gigabyte Z77M-D3H                        | 7         | 1.13%   |
| HP Notebook                              | 6         | 0.97%   |
| Gigabyte B85M-D3H                        | 6         | 0.97%   |
| MSI MS-7C52                              | 5         | 0.81%   |
| Valve Jupiter                            | 4         | 0.64%   |
| MSI MS-7817                              | 4         | 0.64%   |
| Gigabyte X570 UD                         | 4         | 0.64%   |
| Gigabyte B450M S2H                       | 4         | 0.64%   |
| Intel DH61WW AAG23116-300                | 3         | 0.48%   |
| HP Laptop 15-bs0xx                       | 3         | 0.48%   |
| HP Compaq Presario CQ40                  | 3         | 0.48%   |
| Dell XPS 15 7590                         | 3         | 0.48%   |
| Dell OptiPlex 755                        | 3         | 0.48%   |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA | 3         | 0.48%   |
| ASRock B550 Pro4                         | 3         | 0.48%   |
| MSI MS-7C96                              | 2         | 0.32%   |
| MSI MS-7C81                              | 2         | 0.32%   |
| MSI MS-7B89                              | 2         | 0.32%   |
| MSI Modern 14 B5M                        | 2         | 0.32%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 2         | 0.32%   |
| Lenovo G50-70 20351                      | 2         | 0.32%   |
| Intel X99                                | 2         | 0.32%   |
| Intel MAHOBAY                            | 2         | 0.32%   |
| ILLEGEAR RAVEN SE                        | 2         | 0.32%   |
| HP Pavilion Notebook                     | 2         | 0.32%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 2         | 0.32%   |
| HP Pavilion dv6                          | 2         | 0.32%   |
| HP ENVY 4                                | 2         | 0.32%   |
| HP ElitePad 1000 G2                      | 2         | 0.32%   |
| HP EliteBook 8470p                       | 2         | 0.32%   |
| HP EliteBook 840 G2                      | 2         | 0.32%   |
| Google Reks                              | 2         | 0.32%   |
| Google Auron_Paine                       | 2         | 0.32%   |
| Gigabyte B550 AORUS PRO V2               | 2         | 0.32%   |
| Dell XPS 8940                            | 2         | 0.32%   |
| Dell OptiPlex 990                        | 2         | 0.32%   |
| Dell OptiPlex 7010                       | 2         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 31        | 4.99%   |
| Dell Latitude       | 29        | 4.67%   |
| Dell Inspiron       | 21        | 3.38%   |
| Acer Aspire         | 21        | 3.38%   |
| Dell OptiPlex       | 16        | 2.58%   |
| ASUS VivoBook       | 15        | 2.42%   |
| Unknown             | 14        | 2.25%   |
| HP Pavilion         | 12        | 1.93%   |
| Intel DH61WW        | 11        | 1.77%   |
| HP Compaq           | 11        | 1.77%   |
| HP EliteBook        | 10        | 1.61%   |
| HP Laptop           | 9         | 1.45%   |
| Dell XPS            | 9         | 1.45%   |
| RPi Raspberry       | 8         | 1.29%   |
| Lenovo IdeaPad      | 8         | 1.29%   |
| ASUS ROG            | 8         | 1.29%   |
| ASUS All            | 8         | 1.29%   |
| Gigabyte Z77M-D3H   | 7         | 1.13%   |
| Dell Precision      | 7         | 1.13%   |
| ASUS TUF            | 7         | 1.13%   |
| Lenovo ThinkCentre  | 6         | 0.97%   |
| HP Notebook         | 6         | 0.97%   |
| Gigabyte X570       | 6         | 0.97%   |
| Gigabyte B85M-D3H   | 6         | 0.97%   |
| MSI MS-7C52         | 5         | 0.81%   |
| Lenovo Legion       | 5         | 0.81%   |
| HP ENVY             | 5         | 0.81%   |
| Gigabyte B450M      | 5         | 0.81%   |
| ASUS PRIME          | 5         | 0.81%   |
| Acer Veriton        | 5         | 0.81%   |
| Valve Jupiter       | 4         | 0.64%   |
| MSI MS-7817         | 4         | 0.64%   |
| HP ProLiant         | 4         | 0.64%   |
| Fujitsu LIFEBOOK    | 4         | 0.64%   |
| ASUS ZenBook        | 4         | 0.64%   |
| MSI Modern          | 3         | 0.48%   |
| Lenovo Yoga         | 3         | 0.48%   |
| Lenovo ThinkStation | 3         | 0.48%   |
| HP ProBook          | 3         | 0.48%   |
| Dell PowerEdge      | 3         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 55        | 8.86%   |
| 2011    | 53        | 8.53%   |
| 2019    | 52        | 8.37%   |
| 2012    | 52        | 8.37%   |
| 2020    | 49        | 7.89%   |
| 2013    | 46        | 7.41%   |
| 2021    | 41        | 6.6%    |
| 2017    | 36        | 5.8%    |
| 2015    | 35        | 5.64%   |
| 2014    | 31        | 4.99%   |
| 2010    | 30        | 4.83%   |
| 2022    | 29        | 4.67%   |
| 2008    | 24        | 3.86%   |
| 2023    | 21        | 3.38%   |
| 2009    | 17        | 2.74%   |
| 2016    | 15        | 2.42%   |
| Unknown | 14        | 2.25%   |
| 2007    | 11        | 1.77%   |
| 2024    | 8         | 1.29%   |
| 2006    | 1         | 0.16%   |
| 2004    | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 317       | 51.05%  |
| Desktop        | 242       | 38.97%  |
| Convertible    | 14        | 2.25%   |
| All in one     | 13        | 2.09%   |
| System on chip | 9         | 1.45%   |
| Server         | 9         | 1.45%   |
| Tablet         | 7         | 1.13%   |
| Phone          | 5         | 0.81%   |
| Mini pc        | 5         | 0.81%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 577       | 92.62%  |
| Enabled  | 46        | 7.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 614       | 98.87%  |
| Yes  | 7         | 1.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 140       | 22.12%  |
| 16.01-24.0  | 130       | 20.54%  |
| 3.01-4.0    | 115       | 18.17%  |
| 8.01-16.0   | 115       | 18.17%  |
| 32.01-64.0  | 46        | 7.27%   |
| 64.01-256.0 | 27        | 4.27%   |
| 24.01-32.0  | 20        | 3.16%   |
| 1.01-2.0    | 19        | 3%      |
| 2.01-3.0    | 12        | 1.9%    |
| 0.51-1.0    | 6         | 0.95%   |
| 0.01-0.5    | 3         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 207       | 29.28%  |
| 2.01-3.0    | 205       | 29%     |
| 3.01-4.0    | 102       | 14.43%  |
| 4.01-8.0    | 94        | 13.3%   |
| 0.51-1.0    | 38        | 5.37%   |
| 8.01-16.0   | 26        | 3.68%   |
| 0.01-0.5    | 13        | 1.84%   |
| 32.01-64.0  | 7         | 0.99%   |
| 16.01-24.0  | 6         | 0.85%   |
| 24.01-32.0  | 4         | 0.57%   |
| 64.01-256.0 | 4         | 0.57%   |
| Unknown     | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 354       | 55.05%  |
| 2      | 171       | 26.59%  |
| 3      | 48        | 7.47%   |
| 4      | 29        | 4.51%   |
| 5      | 11        | 1.71%   |
| 7      | 9         | 1.4%    |
| 8      | 7         | 1.09%   |
| 6      | 5         | 0.78%   |
| 0      | 4         | 0.62%   |
| 11     | 2         | 0.31%   |
| 10     | 2         | 0.31%   |
| 9      | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 443       | 70.99%  |
| Yes       | 181       | 29.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 518       | 83.15%  |
| No        | 105       | 16.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 492       | 78.22%  |
| No        | 137       | 21.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 376       | 59.97%  |
| No        | 251       | 40.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Malaysia | 621       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 258       | 37.89%  |
| Petaling Jaya          | 72        | 10.57%  |
| Shah Alam              | 24        | 3.52%   |
| Johor Bahru            | 24        | 3.52%   |
| George Town            | 24        | 3.52%   |
| Kota Kinabalu          | 22        | 3.23%   |
| Seremban               | 19        | 2.79%   |
| Ipoh                   | 19        | 2.79%   |
| Subang Jaya            | 16        | 2.35%   |
| Puchong Batu Dua Belas | 16        | 2.35%   |
| Kajang                 | 15        | 2.2%    |
| Seri Kembangan         | 14        | 2.06%   |
| Kuching                | 13        | 1.91%   |
| Sungai Buloh           | 9         | 1.32%   |
| Malacca                | 9         | 1.32%   |
| Kota Bharu             | 9         | 1.32%   |
| Sungai Petani          | 8         | 1.17%   |
| Marabu                 | 7         | 1.03%   |
| Cheras                 | 7         | 1.03%   |
| Kulim                  | 5         | 0.73%   |
| Kulai                  | 5         | 0.73%   |
| Klang                  | 5         | 0.73%   |
| Butterworth            | 5         | 0.73%   |
| Tawau                  | 4         | 0.59%   |
| Skudai                 | 4         | 0.59%   |
| Cyberjaya              | 4         | 0.59%   |
| Bayan Lepas            | 4         | 0.59%   |
| Ampang                 | 4         | 0.59%   |
| Putrajaya              | 3         | 0.44%   |
| Bukit Mertajam         | 3         | 0.44%   |
| Batu Pahat             | 3         | 0.44%   |
| Taman Prai             | 2         | 0.29%   |
| Sungai Besar           | 2         | 0.29%   |
| Sibu                   | 2         | 0.29%   |
| Semenyih               | 2         | 0.29%   |
| Rawang                 | 2         | 0.29%   |
| Nibong Tebal           | 2         | 0.29%   |
| Long Seridan           | 2         | 0.29%   |
| Labuan                 | 2         | 0.29%   |
| Kuantan                | 2         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 164       | 289    | 16.63%  |
| WDC                         | 143       | 239    | 14.5%   |
| Samsung Electronics         | 80        | 121    | 8.11%   |
| Kingston                    | 71        | 123    | 7.2%    |
| Toshiba                     | 55        | 70     | 5.58%   |
| SanDisk                     | 49        | 63     | 4.97%   |
| Unknown                     | 42        | 53     | 4.26%   |
| A-DATA Technology           | 31        | 53     | 3.14%   |
| Intel                       | 24        | 36     | 2.43%   |
| HGST                        | 22        | 30     | 2.23%   |
| Micron Technology           | 21        | 29     | 2.13%   |
| PNY                         | 19        | 59     | 1.93%   |
| Hitachi                     | 19        | 25     | 1.93%   |
| SK hynix                    | 18        | 18     | 1.83%   |
| Crucial                     | 18        | 37     | 1.83%   |
| Apacer                      | 16        | 24     | 1.62%   |
| Kingston Technology Company | 12        | 14     | 1.22%   |
| Phison Electronics          | 9         | 10     | 0.91%   |
| China                       | 9         | 9      | 0.91%   |
| Transcend                   | 8         | 10     | 0.81%   |
| SPCC                        | 8         | 9      | 0.81%   |
| Silicon Motion              | 8         | 18     | 0.81%   |
| KIOXIA                      | 8         | 11     | 0.81%   |
| Phison                      | 7         | 10     | 0.71%   |
| ADATA Technology            | 7         | 8      | 0.71%   |
| TO Exter                    | 6         | 8      | 0.61%   |
| Hewlett-Packard             | 6         | 8      | 0.61%   |
| Corsair                     | 6         | 17     | 0.61%   |
| Apple                       | 6         | 8      | 0.61%   |
| Patriot                     | 5         | 6      | 0.51%   |
| Gigabyte Technology         | 5         | 6      | 0.51%   |
| Kingchuxing                 | 4         | 6      | 0.41%   |
| AGI                         | 4         | 5      | 0.41%   |
| Unknown                     | 4         | 4      | 0.41%   |
| Verbatim                    | 3         | 4      | 0.3%    |
| Team                        | 3         | 3      | 0.3%    |
| Plextor                     | 3         | 3      | 0.3%    |
| Pioneer                     | 3         | 3      | 0.3%    |
| KIOXIA-EXCERIA              | 3         | 5      | 0.3%    |
| KingSpec                    | 3         | 3      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                                   | 17        | 1.56%   |
| Seagate ST2000DM008-2UB102 2TB                                    | 14        | 1.29%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 13        | 1.19%   |
| Seagate ST3500414CS 500GB                                         | 10        | 0.92%   |
| PNY 1TB SATA SSD                                                  | 10        | 0.92%   |
| Toshiba MQ01ABD100 1TB                                            | 9         | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                                | 8         | 0.73%   |
| Samsung HD103SJ 1TB                                               | 8         | 0.73%   |
| WDC WD5000AAKX-75U6AA0 500GB                                      | 7         | 0.64%   |
| WDC WD2500AAKX-753CA1 250GB                                       | 7         | 0.64%   |
| Unknown MMC Card  32GB                                            | 7         | 0.64%   |
| Seagate ST500DM002-1BD142 500GB                                   | 7         | 0.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 7         | 0.64%   |
| HGST HTS545050A7E680 500GB                                        | 7         | 0.64%   |
| Crucial CT500MX500SSD1 500GB                                      | 7         | 0.64%   |
| A-DATA SX8200PNP 256GB                                            | 7         | 0.64%   |
| Unknown MMC Card  64GB                                            | 6         | 0.55%   |
| Toshiba MQ04ABF100 1TB                                            | 6         | 0.55%   |
| TO Exter nal USB 3.0 1024GB                                       | 6         | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 6         | 0.55%   |
| Kingston SEDC500R1920G 2TB SSD                                    | 6         | 0.55%   |
| Kingston SA400S37480G 480GB SSD                                   | 6         | 0.55%   |
| Corsair Force MP510 240GB                                         | 6         | 0.55%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 6         | 0.55%   |
| WDC WD5000AAKX-00ERMA0 500GB                                      | 5         | 0.46%   |
| WDC WD20EZRX-00D8PB0 2TB                                          | 5         | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                                   | 5         | 0.46%   |
| Seagate ST380815AS 80GB                                           | 5         | 0.46%   |
| Seagate ST1000LM048-2E7172 1TB                                    | 5         | 0.46%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                              | 5         | 0.46%   |
| Samsung SSD 860 EVO 500GB                                         | 5         | 0.46%   |
| PNY CS900 1TB SSD                                                 | 5         | 0.46%   |
| Kingston SEDC1000BM8960G 960GB                                    | 5         | 0.46%   |
| Apacer AS340 120GB SSD                                            | 5         | 0.46%   |
| A-DATA SU650 120GB SSD                                            | 5         | 0.46%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                                  | 4         | 0.37%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB             | 4         | 0.37%   |
| Seagate ST500DM002-1BC142 500GB                                   | 4         | 0.37%   |
| Seagate ST3320418AS 320GB                                         | 4         | 0.37%   |
| Seagate ST3160815AS 160GB                                         | 4         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 160       | 285    | 39.7%   |
| WDC                 | 119       | 215    | 29.53%  |
| Toshiba             | 45        | 58     | 11.17%  |
| HGST                | 22        | 30     | 5.46%   |
| Hitachi             | 19        | 25     | 4.71%   |
| Samsung Electronics | 13        | 19     | 3.23%   |
| TO Exter            | 6         | 8      | 1.49%   |
| Unknown             | 3         | 3      | 0.74%   |
| JMicron Technology  | 3         | 3      | 0.74%   |
| Hewlett-Packard     | 3         | 3      | 0.74%   |
| Fujitsu             | 2         | 2      | 0.5%    |
| External            | 2         | 2      | 0.5%    |
| ASMT                | 2         | 3      | 0.5%    |
| Apple               | 2         | 2      | 0.5%    |
| WALRAM              | 1         | 1      | 0.25%   |
| Maxtor              | 1         | 4      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 58        | 87     | 19.27%  |
| Samsung Electronics | 31        | 53     | 10.3%   |
| SanDisk             | 20        | 24     | 6.64%   |
| PNY                 | 18        | 58     | 5.98%   |
| Crucial             | 18        | 37     | 5.98%   |
| A-DATA Technology   | 18        | 24     | 5.98%   |
| Apacer              | 16        | 24     | 5.32%   |
| WDC                 | 12        | 12     | 3.99%   |
| Intel               | 11        | 15     | 3.65%   |
| China               | 9         | 9      | 2.99%   |
| Transcend           | 7         | 8      | 2.33%   |
| SPCC                | 6         | 7      | 1.99%   |
| Micron Technology   | 6         | 11     | 1.99%   |
| Patriot             | 5         | 6      | 1.66%   |
| Verbatim            | 3         | 4      | 1%      |
| Toshiba             | 3         | 4      | 1%      |
| Team                | 3         | 3      | 1%      |
| SK hynix            | 3         | 3      | 1%      |
| Plextor             | 3         | 3      | 1%      |
| Pioneer             | 3         | 3      | 1%      |
| KingSpec            | 3         | 3      | 1%      |
| Apple               | 3         | 4      | 1%      |
| AGI                 | 3         | 3      | 1%      |
| USB3.0              | 2         | 2      | 0.66%   |
| Seagate             | 2         | 2      | 0.66%   |
| OCZ                 | 2         | 8      | 0.66%   |
| Netac               | 2         | 2      | 0.66%   |
| KIOXIA-EXCERIA      | 2         | 4      | 0.66%   |
| Kingchuxing         | 2         | 3      | 0.66%   |
| KimMiDi             | 2         | 2      | 0.66%   |
| Hewlett-Packard     | 2         | 4      | 0.66%   |
| Gigabyte Technology | 2         | 2      | 0.66%   |
| Colorful            | 2         | 2      | 0.66%   |
| Zheino              | 1         | 1      | 0.33%   |
| WISE                | 1         | 1      | 0.33%   |
| WALRAM              | 1         | 1      | 0.33%   |
| Unknown             | 1         | 1      | 0.33%   |
| Teclast             | 1         | 1      | 0.33%   |
| sk600               | 1         | 1      | 0.33%   |
| SATAFIRM            | 1         | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 331       | 663    | 39.26%  |
| SSD     | 257       | 456    | 30.49%  |
| NVMe    | 203       | 339    | 24.08%  |
| MMC     | 37        | 48     | 4.39%   |
| Unknown | 15        | 19     | 1.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 471       | 1094   | 63.14%  |
| NVMe | 203       | 338    | 27.21%  |
| MMC  | 37        | 48     | 4.96%   |
| SAS  | 35        | 45     | 4.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 345       | 583    | 57.02%  |
| 0.51-1.0   | 179       | 326    | 29.59%  |
| 1.01-2.0   | 60        | 160    | 9.92%   |
| 3.01-4.0   | 10        | 20     | 1.65%   |
| 4.01-10.0  | 5         | 12     | 0.83%   |
| 2.01-3.0   | 4         | 6      | 0.66%   |
| 10.01-20.0 | 2         | 12     | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 172       | 25.63%  |
| 251-500        | 144       | 21.46%  |
| 501-1000       | 103       | 15.35%  |
| 1-20           | 64        | 9.54%   |
| 1001-2000      | 47        | 7%      |
| 51-100         | 47        | 7%      |
| 21-50          | 35        | 5.22%   |
| More than 3000 | 24        | 3.58%   |
| Unknown        | 23        | 3.43%   |
| 2001-3000      | 12        | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 293       | 42.22%  |
| 21-50          | 109       | 15.71%  |
| 51-100         | 81        | 11.67%  |
| 101-250        | 78        | 11.24%  |
| 251-500        | 49        | 7.06%   |
| 501-1000       | 27        | 3.89%   |
| Unknown        | 23        | 3.31%   |
| 1001-2000      | 17        | 2.45%   |
| More than 3000 | 10        | 1.44%   |
| 2001-3000      | 6         | 0.86%   |
| 0              | 1         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB                | 7         | 7      | 10.29%  |
| Toshiba MQ01ABD100 1TB                      | 2         | 2      | 2.94%   |
| Seagate ST9320325AS 320GB                   | 2         | 2      | 2.94%   |
| Seagate ST3500414CS 500GB                   | 2         | 3      | 2.94%   |
| Seagate ST1000DM010-2EP102 1TB              | 2         | 2      | 2.94%   |
| WDC WDS480G2G0A-00JH30 480GB SSD            | 1         | 1      | 1.47%   |
| WDC WD800AAJS-00PSA0 80GB                   | 1         | 1      | 1.47%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 1      | 1.47%   |
| WDC WD5000BPVT-24HXZT3 500GB                | 1         | 1      | 1.47%   |
| WDC WD5000BPVT-00HXZT1 500GB                | 1         | 1      | 1.47%   |
| WDC WD5000AVDS-73U7B1 500GB                 | 1         | 1      | 1.47%   |
| WDC WD5000AAKX-753CA1 500GB                 | 1         | 1      | 1.47%   |
| WDC WD5000AAKX-00ERMA0 500GB                | 1         | 1      | 1.47%   |
| WDC WD5000AADS-00S9B0 500GB                 | 1         | 1      | 1.47%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1      | 1.47%   |
| WDC WD10JPVX-08JC3T5 1TB                    | 1         | 1      | 1.47%   |
| WDC WD10JPVT-75A1YT0 1TB                    | 1         | 1      | 1.47%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1      | 1.47%   |
| WDC WD10EZEX-60M2NA0 1TB                    | 1         | 1      | 1.47%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 1         | 1      | 1.47%   |
| WDC WD Green 2.5 240GB SSD                  | 1         | 1      | 1.47%   |
| WALRAM SSD 128GB                            | 1         | 1      | 1.47%   |
| Toshiba MK5065GSX 500GB                     | 1         | 1      | 1.47%   |
| Toshiba MK1059GSMP 1TB                      | 1         | 1      | 1.47%   |
| Toshiba DT01ACA100 1TB                      | 1         | 1      | 1.47%   |
| SPCC Solid State Disk 256GB                 | 1         | 1      | 1.47%   |
| Seagate ST9750420AS 752GB                   | 1         | 1      | 1.47%   |
| Seagate ST9250315AS 250GB                   | 1         | 1      | 1.47%   |
| Seagate ST500LT012-9WS142 500GB             | 1         | 1      | 1.47%   |
| Seagate ST500DM002-1BD142 500GB             | 1         | 1      | 1.47%   |
| Seagate ST380211AS 80GB                     | 1         | 1      | 1.47%   |
| Seagate ST3320620A 320GB                    | 1         | 1      | 1.47%   |
| Seagate ST31000524AS 1TB                    | 1         | 1      | 1.47%   |
| Seagate ST31000322CS 1TB                    | 1         | 1      | 1.47%   |
| Seagate ST2000LM003 HN-M201RAD 2TB          | 1         | 1      | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 1         | 1      | 1.47%   |
| Seagate ST1000DM003-1CH162 1TB              | 1         | 1      | 1.47%   |
| Samsung Electronics SSD PM830 2.5 7mm 512GB | 1         | 1      | 1.47%   |
| Samsung Electronics HM160HI 160GB           | 1         | 1      | 1.47%   |
| PNY 1TB SATA SSD                            | 1         | 6      | 1.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 23        | 23     | 34.33%  |
| Seagate                   | 16        | 18     | 23.88%  |
| Hitachi                   | 6         | 9      | 8.96%   |
| Toshiba                   | 5         | 5      | 7.46%   |
| HGST                      | 4         | 4      | 5.97%   |
| Samsung Electronics       | 2         | 2      | 2.99%   |
| WALRAM                    | 1         | 1      | 1.49%   |
| SPCC                      | 1         | 1      | 1.49%   |
| PNY                       | 1         | 6      | 1.49%   |
| Micron/Crucial Technology | 1         | 2      | 1.49%   |
| Micron Technology         | 1         | 1      | 1.49%   |
| Kingston                  | 1         | 1      | 1.49%   |
| Intel                     | 1         | 1      | 1.49%   |
| Hewlett-Packard           | 1         | 1      | 1.49%   |
| Crucial                   | 1         | 2      | 1.49%   |
| A-DATA Technology         | 1         | 1      | 1.49%   |
| Unknown                   | 1         | 1      | 1.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 21     | 39.62%  |
| Seagate             | 16        | 18     | 30.19%  |
| Hitachi             | 6         | 9      | 11.32%  |
| Toshiba             | 5         | 5      | 9.43%   |
| HGST                | 4         | 4      | 7.55%   |
| Samsung Electronics | 1         | 1      | 1.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 58     | 78.46%  |
| SSD  | 12        | 18     | 18.46%  |
| NVMe | 2         | 3      | 3.08%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 361       | 795    | 52.62%  |
| Works    | 261       | 651    | 38.05%  |
| Malfunc  | 64        | 79     | 9.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 428       | 53.97%  |
| AMD                                     | 101       | 12.74%  |
| Samsung Electronics                     | 40        | 5.04%   |
| SanDisk                                 | 39        | 4.92%   |
| Kingston Technology Company             | 30        | 3.78%   |
| Phison Electronics                      | 27        | 3.4%    |
| ADATA Technology                        | 17        | 2.14%   |
| SK hynix                                | 16        | 2.02%   |
| Micron Technology                       | 15        | 1.89%   |
| ASMedia Technology                      | 14        | 1.77%   |
| Silicon Motion                          | 13        | 1.64%   |
| KIOXIA                                  | 9         | 1.13%   |
| Nvidia                                  | 8         | 1.01%   |
| Toshiba America Info Systems            | 7         | 0.88%   |
| Marvell Technology Group                | 5         | 0.63%   |
| JMicron Technology                      | 4         | 0.5%    |
| Broadcom / LSI                          | 4         | 0.5%    |
| Realtek Semiconductor                   | 3         | 0.38%   |
| Transcend                               | 2         | 0.25%   |
| Micron/Crucial Technology               | 2         | 0.25%   |
| LSI Logic / Symbios Logic               | 2         | 0.25%   |
| Silicon Image                           | 1         | 0.13%   |
| Shenzhen Unionmemory Information System | 1         | 0.13%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.13%   |
| Lite-On IT Corp. / Plextor              | 1         | 0.13%   |
| Hewlett-Packard                         | 1         | 0.13%   |
| Biwin Storage Technology                | 1         | 0.13%   |
| Apple                                   | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 71        | 7.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 32        | 3.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 28        | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 27        | 2.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 24        | 2.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 21        | 2.3%    |
| Intel SATA Controller [RAID mode]                                              | 17        | 1.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 1.75%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 16        | 1.75%   |
| Intel Volume Management Device NVMe RAID Controller                            | 15        | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 15        | 1.64%   |
| AMD 400 Series Chipset SATA Controller                                         | 15        | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 13        | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 1.42%   |
| Phison E12 NVMe Controller                                                     | 12        | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 12        | 1.31%   |
| AMD 500 Series Chipset SATA Controller                                         | 12        | 1.31%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 11        | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 11        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 11        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 11        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 11        | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 1.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 1.09%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 10        | 1.09%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 9         | 0.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 9         | 0.98%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 8         | 0.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 0.87%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 8         | 0.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 0.77%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 7         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 7         | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 0.77%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 6         | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 423       | 54.58%  |
| NVMe | 204       | 26.32%  |
| IDE  | 73        | 9.42%   |
| RAID | 70        | 9.03%   |
| SAS  | 4         | 0.52%   |
| SCSI | 1         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 469       | 75.52%  |
| AMD      | 138       | 22.22%  |
| ARM      | 13        | 2.09%   |
| Qualcomm | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz              | 9         | 1.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 9         | 1.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.28%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.28%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 1.12%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 7         | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 0.96%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 6         | 0.96%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 6         | 0.96%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 6         | 0.96%   |
| ARM BCM2835 Processor                         | 6         | 0.96%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 6         | 0.96%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 5         | 0.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 5         | 0.8%    |
| Intel Core i3-4130 CPU @ 3.40GHz              | 5         | 0.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 0.64%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 4         | 0.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.64%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.64%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 0.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.64%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 4         | 0.64%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 4         | 0.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 0.64%   |
| ARM Processor                                 | 4         | 0.64%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 0.64%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 0.64%   |
| AMD Custom APU 0405                           | 4         | 0.64%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 3         | 0.48%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 0.48%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.48%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.48%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 3         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 153       | 24.48%  |
| Intel Core i7           | 80        | 12.8%   |
| Intel Core i3           | 59        | 9.44%   |
| Other                   | 54        | 8.64%   |
| AMD Ryzen 5             | 46        | 7.36%   |
| Intel Core 2 Duo        | 27        | 4.32%   |
| Intel Celeron           | 27        | 4.32%   |
| AMD Ryzen 7             | 26        | 4.16%   |
| Intel Pentium           | 25        | 4%      |
| Intel Xeon              | 24        | 3.84%   |
| AMD Ryzen 9             | 13        | 2.08%   |
| Intel Atom              | 12        | 1.92%   |
| AMD Ryzen 3             | 10        | 1.6%    |
| Intel Pentium Dual-Core | 7         | 1.12%   |
| Intel Core 2 Quad       | 7         | 1.12%   |
| ARM BCM                 | 6         | 0.96%   |
| AMD A6                  | 6         | 0.96%   |
| AMD Athlon              | 4         | 0.64%   |
| AMD A10                 | 4         | 0.64%   |
| AMD Ryzen Threadripper  | 3         | 0.48%   |
| AMD Ryzen 7 PRO         | 3         | 0.48%   |
| AMD FX                  | 3         | 0.48%   |
| AMD A4                  | 3         | 0.48%   |
| Intel Genuine           | 2         | 0.32%   |
| Intel Core i9           | 2         | 0.32%   |
| ARM AArch64             | 2         | 0.32%   |
| AMD EPYC                | 2         | 0.32%   |
| AMD E                   | 2         | 0.32%   |
| AMD Athlon 64 X2        | 2         | 0.32%   |
| AMD A12                 | 2         | 0.32%   |
| Intel Pentium M         | 1         | 0.16%   |
| Intel Pentium Gold      | 1         | 0.16%   |
| Intel Pentium Dual      | 1         | 0.16%   |
| Intel Core m5           | 1         | 0.16%   |
| AMD Ryzen Embedded      | 1         | 0.16%   |
| AMD Ryzen 5 PRO         | 1         | 0.16%   |
| AMD Phenom II X6        | 1         | 0.16%   |
| AMD Phenom II X4        | 1         | 0.16%   |
| AMD Athlon X2           | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 254       | 40.71%  |
| 4       | 209       | 33.49%  |
| 6       | 67        | 10.74%  |
| 8       | 40        | 6.41%   |
| 16      | 13        | 2.08%   |
| 1       | 10        | 1.6%    |
| 12      | 9         | 1.44%   |
| 10      | 8         | 1.28%   |
| 14      | 6         | 0.96%   |
| Unknown | 3         | 0.48%   |
| 64      | 1         | 0.16%   |
| 36      | 1         | 0.16%   |
| 32      | 1         | 0.16%   |
| 28      | 1         | 0.16%   |
| 3       | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 611       | 98.23%  |
| 2       | 8         | 1.29%   |
| Unknown | 3         | 0.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 412       | 65.92%  |
| 1       | 208       | 33.28%  |
| Unknown | 3         | 0.48%   |
| 8       | 1         | 0.16%   |
| 4       | 1         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 613       | 98.39%  |
| Unknown        | 9         | 1.44%   |
| 32-bit         | 1         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 276       | 42.33%  |
| 0x206a7    | 39        | 5.98%   |
| 0x306c3    | 33        | 5.06%   |
| 0x306a9    | 32        | 4.91%   |
| 0x1067a    | 17        | 2.61%   |
| 0x906ea    | 12        | 1.84%   |
| 0x08108109 | 12        | 1.84%   |
| 0x806e9    | 11        | 1.69%   |
| 0x20655    | 11        | 1.69%   |
| 0x40651    | 10        | 1.53%   |
| 0x506e3    | 8         | 1.23%   |
| 0x306d4    | 7         | 1.07%   |
| 0x806ec    | 6         | 0.92%   |
| 0x806ea    | 6         | 0.92%   |
| 0x406e3    | 6         | 0.92%   |
| 0x08701021 | 6         | 0.92%   |
| 0xa0652    | 5         | 0.77%   |
| 0x90672    | 5         | 0.77%   |
| 0x6fb      | 5         | 0.77%   |
| 0x20652    | 5         | 0.77%   |
| 0x906e9    | 4         | 0.61%   |
| 0x806eb    | 4         | 0.61%   |
| 0x806c1    | 4         | 0.61%   |
| 0x706a1    | 4         | 0.61%   |
| 0x6fd      | 4         | 0.61%   |
| 0x406c4    | 4         | 0.61%   |
| 0x30678    | 4         | 0.61%   |
| 0x10676    | 4         | 0.61%   |
| 0x0a601203 | 4         | 0.61%   |
| 0x08600104 | 4         | 0.61%   |
| 0x06001119 | 4         | 0.61%   |
| 0xa0653    | 3         | 0.46%   |
| 0x806d1    | 3         | 0.46%   |
| 0x106ca    | 3         | 0.46%   |
| 0x0a50000d | 3         | 0.46%   |
| 0x0a50000b | 3         | 0.46%   |
| 0x0a20120a | 3         | 0.46%   |
| 0x0830104d | 3         | 0.46%   |
| 0x0810100b | 3         | 0.46%   |
| 0xa0671    | 2         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 76        | 12.22%  |
| Haswell          | 63        | 10.13%  |
| IvyBridge        | 57        | 9.16%   |
| SandyBridge      | 52        | 8.36%   |
| Unknown          | 43        | 6.91%   |
| Penryn           | 35        | 5.63%   |
| Zen 3            | 34        | 5.47%   |
| Skylake          | 30        | 4.82%   |
| Westmere         | 25        | 4.02%   |
| Zen+             | 24        | 3.86%   |
| Zen 2            | 21        | 3.38%   |
| Silvermont       | 20        | 3.22%   |
| Broadwell        | 18        | 2.89%   |
| Alderlake Hybrid | 18        | 2.89%   |
| CometLake        | 15        | 2.41%   |
| Zen              | 13        | 2.09%   |
| TigerLake        | 11        | 1.77%   |
| Core             | 11        | 1.77%   |
| Icelake          | 10        | 1.61%   |
| Piledriver       | 7         | 1.13%   |
| Goldmont plus    | 6         | 0.96%   |
| Nehalem          | 5         | 0.8%    |
| Excavator        | 5         | 0.8%    |
| Bonnell          | 4         | 0.64%   |
| K10              | 3         | 0.48%   |
| Goldmont         | 3         | 0.48%   |
| Steamroller      | 2         | 0.32%   |
| K8 Hammer        | 2         | 0.32%   |
| K10 Llano        | 2         | 0.32%   |
| Jaguar           | 2         | 0.32%   |
| Bobcat           | 2         | 0.32%   |
| P6               | 1         | 0.16%   |
| K8 & K10 hybrid  | 1         | 0.16%   |
| Gracemont        | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 358       | 48.38%  |
| Nvidia                     | 207       | 27.97%  |
| AMD                        | 164       | 22.16%  |
| Matrox Electronics Systems | 6         | 0.81%   |
| ASPEED Technology          | 5         | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 35        | 4.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 3.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 19        | 2.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 2.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 2.37%   |
| Intel HD Graphics 620                                                                    | 17        | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 2.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 2.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 1.98%   |
| Intel UHD Graphics 620                                                                   | 13        | 1.72%   |
| Intel HD Graphics 5500                                                                   | 13        | 1.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 1.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 1.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12        | 1.58%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 1.45%   |
| Intel HD Graphics 530                                                                    | 11        | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 1.19%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 9         | 1.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 1.06%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 8         | 1.06%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 7         | 0.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 0.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 0.79%   |
| AMD Raphael                                                                              | 6         | 0.79%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 5         | 0.66%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 5         | 0.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 0.66%   |
| Intel HD Graphics 630                                                                    | 5         | 0.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 0.66%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.53%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 244       | 38.98%  |
| 1 x AMD              | 116       | 18.53%  |
| 1 x Nvidia           | 108       | 17.25%  |
| Intel + Nvidia       | 80        | 12.78%  |
| Intel + AMD          | 22        | 3.51%   |
| Other                | 15        | 2.4%    |
| AMD + Nvidia         | 15        | 2.4%    |
| 2 x AMD              | 12        | 1.92%   |
| 1 x Matrox           | 5         | 0.8%    |
| Nvidia + ASPEED      | 4         | 0.64%   |
| 2 x Intel            | 2         | 0.32%   |
| 2 x AMD + 3 x Nvidia | 1         | 0.16%   |
| Nvidia + Matrox      | 1         | 0.16%   |
| 1 x ASPEED           | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 490       | 77.53%  |
| Proprietary | 104       | 16.46%  |
| Unknown     | 38        | 6.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 383       | 59.84%  |
| 1.01-2.0   | 81        | 12.66%  |
| 0.51-1.0   | 46        | 7.19%   |
| 0.01-0.5   | 46        | 7.19%   |
| 3.01-4.0   | 36        | 5.63%   |
| 7.01-8.0   | 27        | 4.22%   |
| 5.01-6.0   | 9         | 1.41%   |
| 8.01-16.0  | 6         | 0.94%   |
| 2.01-3.0   | 5         | 0.78%   |
| 32.01-64.0 | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 81        | 12.24%  |
| Samsung Electronics     | 67        | 10.12%  |
| Dell                    | 63        | 9.52%   |
| LG Display              | 52        | 7.85%   |
| Chimei Innolux          | 52        | 7.85%   |
| BOE                     | 49        | 7.4%    |
| Acer                    | 33        | 4.98%   |
| BenQ                    | 29        | 4.38%   |
| Hewlett-Packard         | 28        | 4.23%   |
| Goldstar                | 25        | 3.78%   |
| AOC                     | 21        | 3.17%   |
| Philips                 | 17        | 2.57%   |
| Sharp                   | 15        | 2.27%   |
| Lenovo                  | 15        | 2.27%   |
| Apple                   | 13        | 1.96%   |
| ViewSonic               | 8         | 1.21%   |
| Chi Mei Optoelectronics | 7         | 1.06%   |
| PANDA                   | 5         | 0.76%   |
| Panasonic               | 5         | 0.76%   |
| MSI                     | 5         | 0.76%   |
| ASUSTek Computer        | 5         | 0.76%   |
| Unknown                 | 4         | 0.6%    |
| Toshiba                 | 4         | 0.6%    |
| Denver                  | 4         | 0.6%    |
| Valve                   | 3         | 0.45%   |
| Sony                    | 3         | 0.45%   |
| RTK                     | 3         | 0.45%   |
| Unknown                 | 3         | 0.45%   |
| Mi                      | 2         | 0.3%    |
| LG Electronics          | 2         | 0.3%    |
| IPS                     | 2         | 0.3%    |
| InnoLux Display         | 2         | 0.3%    |
| InfoVision              | 2         | 0.3%    |
| EXP                     | 2         | 0.3%    |
| Xiaomi                  | 1         | 0.15%   |
| Unknown (BBC)           | 1         | 0.15%   |
| TRI                     | 1         | 0.15%   |
| QCM                     | 1         | 0.15%   |
| NXP                     | 1         | 0.15%   |
| NCS                     | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 8         | 1.18%   |
| BenQ GL2023 BNQ78CC 1600x900 430x240mm 19.4-inch                      | 7         | 1.03%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                    | 5         | 0.74%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 5         | 0.74%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 5         | 0.74%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 5         | 0.74%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 4         | 0.59%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.59%   |
| Dell E2720HS DELA15E 1920x1080 598x336mm 27.0-inch                    | 4         | 0.59%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 4         | 0.59%   |
| BenQ EX3203R BNQ7F66 2560x1440 698x393mm 31.5-inch                    | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 4         | 0.59%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 3         | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch  | 3         | 0.44%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 3         | 0.44%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 3         | 0.44%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 3         | 0.44%   |
| Denver PrimetekH3CQC LHCFFFF 3840x1080 1197x337mm 49.0-inch           | 3         | 0.44%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch      | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO103C 1366x768 310x170mm 13.9-inch         | 3         | 0.44%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 3         | 0.44%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 3         | 0.44%   |
| Unknown                                                               | 3         | 0.44%   |
| Sony TV SNYAC03 1680x1050                                             | 2         | 0.29%   |
| Sharp LCD SHP10C9 1920x540                                            | 2         | 0.29%   |
| Sharp HDMI SHP10A1 1360x768 700x390mm 31.5-inch                       | 2         | 0.29%   |
| Samsung Electronics S24C31x SAM7311 1920x1080 527x296mm 23.8-inch     | 2         | 0.29%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch  | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 2         | 0.29%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 2         | 0.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 263       | 41.03%  |
| 1366x768 (WXGA)    | 161       | 25.12%  |
| 3840x2160 (4K)     | 34        | 5.3%    |
| 1600x900 (HD+)     | 32        | 4.99%   |
| 2560x1440 (QHD)    | 22        | 3.43%   |
| 1920x1200 (WUXGA)  | 14        | 2.18%   |
| 1280x800 (WXGA)    | 14        | 2.18%   |
| 1680x1050 (WSXGA+) | 12        | 1.87%   |
| 1440x900 (WXGA+)   | 10        | 1.56%   |
| 2560x1080          | 9         | 1.4%    |
| 1360x768           | 8         | 1.25%   |
| Unknown            | 7         | 1.09%   |
| 1280x1024 (SXGA)   | 6         | 0.94%   |
| 2560x1600          | 4         | 0.62%   |
| 800x1280           | 3         | 0.47%   |
| 3440x1440          | 3         | 0.47%   |
| 2880x1800          | 3         | 0.47%   |
| 2160x1440          | 3         | 0.47%   |
| 1280x720 (HD)      | 3         | 0.47%   |
| 1024x768 (XGA)     | 3         | 0.47%   |
| 1024x600           | 3         | 0.47%   |
| 5760x1080          | 2         | 0.31%   |
| 3840x1080          | 2         | 0.31%   |
| 1920x540           | 2         | 0.31%   |
| 1600x1200          | 2         | 0.31%   |
| 1280x960           | 2         | 0.31%   |
| 5440x1080          | 1         | 0.16%   |
| 5120x1440          | 1         | 0.16%   |
| 3840x2400          | 1         | 0.16%   |
| 3120x1600          | 1         | 0.16%   |
| 3000x2000          | 1         | 0.16%   |
| 2880x1920          | 1         | 0.16%   |
| 2880x1620          | 1         | 0.16%   |
| 2800x1752          | 1         | 0.16%   |
| 2520x1680          | 1         | 0.16%   |
| 2304x1440          | 1         | 0.16%   |
| 2288x1287          | 1         | 0.16%   |
| 2240x1400          | 1         | 0.16%   |
| 1920x1280          | 1         | 0.16%   |
| 1360x765           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 113       | 17.12%  |
| 14      | 75        | 11.36%  |
| 13      | 75        | 11.36%  |
| 23      | 52        | 7.88%   |
| 24      | 48        | 7.27%   |
| 27      | 37        | 5.61%   |
| 18      | 32        | 4.85%   |
| 21      | 29        | 4.39%   |
| 31      | 27        | 4.09%   |
| Unknown | 24        | 3.64%   |
| 20      | 20        | 3.03%   |
| 19      | 17        | 2.58%   |
| 17      | 16        | 2.42%   |
| 12      | 16        | 2.42%   |
| 11      | 12        | 1.82%   |
| 34      | 9         | 1.36%   |
| 22      | 8         | 1.21%   |
| 16      | 8         | 1.21%   |
| 32      | 7         | 1.06%   |
| 10      | 5         | 0.76%   |
| 84      | 4         | 0.61%   |
| 72      | 4         | 0.61%   |
| 7       | 4         | 0.61%   |
| 49      | 3         | 0.45%   |
| 25      | 3         | 0.45%   |
| 52      | 2         | 0.3%    |
| 28      | 2         | 0.3%    |
| 142     | 1         | 0.15%   |
| 67      | 1         | 0.15%   |
| 65      | 1         | 0.15%   |
| 57      | 1         | 0.15%   |
| 55      | 1         | 0.15%   |
| 40      | 1         | 0.15%   |
| 39      | 1         | 0.15%   |
| 26      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 241       | 36.96%  |
| 501-600        | 130       | 19.94%  |
| 401-500        | 105       | 16.1%   |
| 201-300        | 64        | 9.82%   |
| 601-700        | 32        | 4.91%   |
| Unknown        | 24        | 3.68%   |
| 701-800        | 18        | 2.76%   |
| 351-400        | 16        | 2.45%   |
| 1501-2000      | 8         | 1.23%   |
| 1001-1500      | 7         | 1.07%   |
| 1-100          | 3         | 0.46%   |
| 801-900        | 2         | 0.31%   |
| More than 2000 | 1         | 0.15%   |
| 101-200        | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 465       | 78.15%  |
| 16/10   | 61        | 10.25%  |
| Unknown | 20        | 3.36%   |
| 21/9    | 11        | 1.85%   |
| 3/2     | 10        | 1.68%   |
| 5/4     | 9         | 1.51%   |
| 4/3     | 7         | 1.18%   |
| 32/9    | 5         | 0.84%   |
| 0.67    | 3         | 0.5%    |
| 1.00    | 2         | 0.34%   |
| 0.56    | 1         | 0.17%   |
| 0.45    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 124       | 18.93%  |
| 201-250        | 117       | 17.86%  |
| 101-110        | 113       | 17.25%  |
| 151-200        | 47        | 7.18%   |
| 351-500        | 43        | 6.56%   |
| 301-350        | 37        | 5.65%   |
| 141-150        | 37        | 5.65%   |
| 71-80          | 24        | 3.66%   |
| Unknown        | 24        | 3.66%   |
| More than 1000 | 15        | 2.29%   |
| 61-70          | 14        | 2.14%   |
| 251-300        | 14        | 2.14%   |
| 51-60          | 12        | 1.83%   |
| 121-130        | 9         | 1.37%   |
| 111-120        | 7         | 1.07%   |
| 41-50          | 5         | 0.76%   |
| 501-1000       | 5         | 0.76%   |
| 1-40           | 4         | 0.61%   |
| 91-100         | 4         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 242       | 38.05%  |
| 101-120       | 162       | 25.47%  |
| 121-160       | 149       | 23.43%  |
| 161-240       | 36        | 5.66%   |
| Unknown       | 24        | 3.77%   |
| 1-50          | 15        | 2.36%   |
| More than 240 | 8         | 1.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 494       | 77.92%  |
| 2     | 92        | 14.51%  |
| 0     | 43        | 6.78%   |
| 3     | 5         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 320       | 32.32%  |
| Intel                             | 295       | 29.8%   |
| Qualcomm Atheros                  | 115       | 11.62%  |
| Broadcom                          | 59        | 5.96%   |
| TP-Link                           | 36        | 3.64%   |
| Ralink Technology                 | 26        | 2.63%   |
| MediaTek                          | 21        | 2.12%   |
| D-Link                            | 15        | 1.52%   |
| Xiaomi                            | 11        | 1.11%   |
| Qualcomm Atheros Communications   | 11        | 1.11%   |
| Broadcom Limited                  | 9         | 0.91%   |
| Samsung Electronics               | 6         | 0.61%   |
| Nvidia                            | 6         | 0.61%   |
| ASIX Electronics                  | 6         | 0.61%   |
| Ralink                            | 5         | 0.51%   |
| OPPO Electronics                  | 5         | 0.51%   |
| Microchip Technology              | 5         | 0.51%   |
| Marvell Technology Group          | 3         | 0.3%    |
| Huawei Technologies               | 3         | 0.3%    |
| Dell                              | 3         | 0.3%    |
| Aquantia                          | 3         | 0.3%    |
| Qualcomm                          | 2         | 0.2%    |
| Mercucys                          | 2         | 0.2%    |
| InterBiometrics                   | 2         | 0.2%    |
| D-Link System                     | 2         | 0.2%    |
| American Megatrends               | 2         | 0.2%    |
| Winbond Electronics               | 1         | 0.1%    |
| Toshiba                           | 1         | 0.1%    |
| Tehuti Networks                   | 1         | 0.1%    |
| T & A Mobile Phones               | 1         | 0.1%    |
| Sundance Technology Inc / IC Plus | 1         | 0.1%    |
| Spreadtrum Communications         | 1         | 0.1%    |
| Sierra Wireless                   | 1         | 0.1%    |
| Raspberry Pi                      | 1         | 0.1%    |
| Mellanox Technologies             | 1         | 0.1%    |
| JMicron Technology                | 1         | 0.1%    |
| ICS Advent                        | 1         | 0.1%    |
| Hewlett-Packard                   | 1         | 0.1%    |
| DisplayLink                       | 1         | 0.1%    |
| Attansic Technology               | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 213       | 18.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 36        | 3.11%   |
| Intel Wi-Fi 6 AX200                                                    | 24        | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 22        | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 1.64%   |
| Intel Wireless 8265 / 8275                                             | 19        | 1.64%   |
| Realtek 802.11ac NIC                                                   | 17        | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 16        | 1.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 1.38%   |
| Intel Wireless 7265                                                    | 16        | 1.38%   |
| Ralink MT7601U Wireless Adapter                                        | 15        | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 14        | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 12        | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 12        | 1.04%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 0.95%   |
| TP-Link Archer T4U ver.3                                               | 10        | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 10        | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 10        | 0.87%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 10        | 0.87%   |
| Intel 82579V Gigabit Network Connection                                | 10        | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 9         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 9         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 9         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 0.78%   |
| TP-Link 802.11n NIC                                                    | 8         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 8         | 0.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 8         | 0.69%   |
| Intel Wireless 7260                                                    | 8         | 0.69%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 0.69%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 0.69%   |
| Intel Ethernet Controller I225-V                                       | 8         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 8         | 0.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 8         | 0.69%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 8         | 0.69%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                         | 8         | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 0.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 7         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 204       | 37.57%  |
| Realtek Semiconductor           | 88        | 16.21%  |
| Qualcomm Atheros                | 86        | 15.84%  |
| Broadcom                        | 40        | 7.37%   |
| TP-Link                         | 36        | 6.63%   |
| Ralink Technology               | 26        | 4.79%   |
| MediaTek                        | 18        | 3.31%   |
| D-Link                          | 15        | 2.76%   |
| Qualcomm Atheros Communications | 11        | 2.03%   |
| Ralink                          | 5         | 0.92%   |
| Broadcom Limited                | 5         | 0.92%   |
| Mercucys                        | 2         | 0.37%   |
| Dell                            | 2         | 0.37%   |
| D-Link System                   | 2         | 0.37%   |
| Sierra Wireless                 | 1         | 0.18%   |
| ASUSTek Computer                | 1         | 0.18%   |
| AboCom Systems                  | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 24        | 4.37%   |
| Intel Wireless 8265 / 8275                                     | 19        | 3.46%   |
| Realtek 802.11ac NIC                                           | 17        | 3.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 2.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 16        | 2.91%   |
| Intel Wireless 7265                                            | 16        | 2.91%   |
| Ralink MT7601U Wireless Adapter                                | 15        | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 12        | 2.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 2.19%   |
| TP-Link Archer T4U ver.3                                       | 10        | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 1.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 10        | 1.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 10        | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 9         | 1.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 9         | 1.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 9         | 1.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 1.64%   |
| TP-Link 802.11n NIC                                            | 8         | 1.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 8         | 1.46%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 8         | 1.46%   |
| Intel Wireless 7260                                            | 8         | 1.46%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 1.46%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 8         | 1.46%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 8         | 1.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 7         | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                | 7         | 1.28%   |
| Intel Wireless 3165                                            | 7         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 1.09%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 6         | 1.09%   |
| Intel Wireless 8260                                            | 5         | 0.91%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 5         | 0.91%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 0.91%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 0.91%   |
| Intel Centrino Advanced-N 6200                                 | 5         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 284       | 49.65%  |
| Intel                             | 161       | 28.15%  |
| Qualcomm Atheros                  | 36        | 6.29%   |
| Broadcom                          | 25        | 4.37%   |
| Xiaomi                            | 11        | 1.92%   |
| Nvidia                            | 6         | 1.05%   |
| ASIX Electronics                  | 6         | 1.05%   |
| OPPO Electronics                  | 5         | 0.87%   |
| Microchip Technology              | 5         | 0.87%   |
| Broadcom Limited                  | 4         | 0.7%    |
| MediaTek                          | 3         | 0.52%   |
| Marvell Technology Group          | 3         | 0.52%   |
| Huawei Technologies               | 3         | 0.52%   |
| Aquantia                          | 3         | 0.52%   |
| Samsung Electronics               | 2         | 0.35%   |
| Qualcomm                          | 2         | 0.35%   |
| American Megatrends               | 2         | 0.35%   |
| Tehuti Networks                   | 1         | 0.17%   |
| T & A Mobile Phones               | 1         | 0.17%   |
| Sundance Technology Inc / IC Plus | 1         | 0.17%   |
| Spreadtrum Communications         | 1         | 0.17%   |
| Raspberry Pi                      | 1         | 0.17%   |
| Mellanox Technologies             | 1         | 0.17%   |
| JMicron Technology                | 1         | 0.17%   |
| ICS Advent                        | 1         | 0.17%   |
| DisplayLink                       | 1         | 0.17%   |
| Attansic Technology               | 1         | 0.17%   |
| Apple                             | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 213       | 35.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 36        | 6.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 22        | 3.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 3.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 2.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 14        | 2.35%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 1.85%   |
| Intel 82579V Gigabit Network Connection                                | 10        | 1.68%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1.51%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 1.34%   |
| Intel Ethernet Controller I225-V                                       | 8         | 1.34%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 1.34%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 8         | 1.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 1.17%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 5         | 0.84%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 0.84%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.84%   |
| Intel Ethernet Connection (11) I219-V                                  | 5         | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 5         | 0.84%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4         | 0.67%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 4         | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.67%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 4         | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 4         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.67%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 3         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.5%    |
| OPPO OnePlus Nord 4                                                    | 3         | 0.5%    |
| Intel Ethernet Controller X550                                         | 3         | 0.5%    |
| Intel Ethernet 10G 2P X520 Adapter                                     | 3         | 0.5%    |
| Huawei FOA-LX9                                                         | 3         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.34%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.34%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 0.34%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 517       | 50.69%  |
| WiFi     | 492       | 48.24%  |
| Modem    | 11        | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 397       | 63.52%  |
| Ethernet | 228       | 36.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 318       | 50.8%   |
| 1     | 242       | 38.66%  |
| 0     | 35        | 5.59%   |
| 3     | 19        | 3.04%   |
| 4     | 4         | 0.64%   |
| 5     | 3         | 0.48%   |
| 6     | 2         | 0.32%   |
| 11    | 1         | 0.16%   |
| 9     | 1         | 0.16%   |
| 8     | 1         | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 402       | 62.62%  |
| Yes  | 240       | 37.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 162       | 42.41%  |
| Realtek Semiconductor           | 39        | 10.21%  |
| Cambridge Silicon Radio         | 29        | 7.59%   |
| Qualcomm Atheros Communications | 27        | 7.07%   |
| IMC Networks                    | 24        | 6.28%   |
| Foxconn / Hon Hai               | 20        | 5.24%   |
| Apple                           | 18        | 4.71%   |
| Broadcom                        | 17        | 4.45%   |
| Lite-On Technology              | 12        | 3.14%   |
| Dell                            | 7         | 1.83%   |
| Hewlett-Packard                 | 6         | 1.57%   |
| TP-Link                         | 5         | 1.31%   |
| Realtek                         | 4         | 1.05%   |
| MediaTek                        | 4         | 1.05%   |
| Ralink                          | 2         | 0.52%   |
| D-Link                          | 2         | 0.52%   |
| Ralink Technology               | 1         | 0.26%   |
| ASUSTek Computer                | 1         | 0.26%   |
| Askey Computer                  | 1         | 0.26%   |
| Alps Electric                   | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 58        | 15.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 29        | 7.59%   |
| Intel AX201 Bluetooth                               | 28        | 7.33%   |
| Realtek Bluetooth Radio                             | 26        | 6.81%   |
| Intel AX200 Bluetooth                               | 24        | 6.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 4.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 2.62%   |
| Apple Bluetooth Host Controller                     | 10        | 2.62%   |
| Intel AX211 Bluetooth                               | 9         | 2.36%   |
| Intel AX210 Bluetooth                               | 9         | 2.36%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 2.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 2.09%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 1.83%   |
| IMC Networks Wireless_Device                        | 7         | 1.83%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.57%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 5         | 1.31%   |
| Lite-On Bluetooth Device                            | 5         | 1.31%   |
| IMC Networks Bluetooth Device                       | 5         | 1.31%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 1.31%   |
| Realtek Bluetooth Radio                             | 4         | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.05%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 1.05%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 1.05%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.05%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 1.05%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 1.05%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.79%   |
| MediaTek Wireless_Device                            | 3         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.79%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 0.79%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.79%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.52%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.52%   |
| Lite-On Atheros Bluetooth                           | 2         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 441       | 52.81%  |
| AMD                                          | 165       | 19.76%  |
| Nvidia                                       | 156       | 18.68%  |
| C-Media Electronics                          | 11        | 1.32%   |
| Logitech                                     | 8         | 0.96%   |
| JMTek                                        | 6         | 0.72%   |
| ASUSTek Computer                             | 6         | 0.72%   |
| Texas Instruments                            | 5         | 0.6%    |
| Realtek Semiconductor                        | 3         | 0.36%   |
| Sony                                         | 2         | 0.24%   |
| Samsung Electronics                          | 2         | 0.24%   |
| RODE Microphones                             | 2         | 0.24%   |
| Generalplus Technology                       | 2         | 0.24%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.12%   |
| Yamaha                                       | 1         | 0.12%   |
| XMOS                                         | 1         | 0.12%   |
| Walmart                                      | 1         | 0.12%   |
| TTGK Technology                              | 1         | 0.12%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.12%   |
| Tenx Technology                              | 1         | 0.12%   |
| SteelSeries ApS                              | 1         | 0.12%   |
| Setek Elektronik                             | 1         | 0.12%   |
| Razer USA                                    | 1         | 0.12%   |
| Plantronics                                  | 1         | 0.12%   |
| Philips (or NXP)                             | 1         | 0.12%   |
| MVSILICON.INC.                               | 1         | 0.12%   |
| MosArt Semiconductor                         | 1         | 0.12%   |
| KTMicro                                      | 1         | 0.12%   |
| Jieli Technology                             | 1         | 0.12%   |
| GYROCOM C&C                                  | 1         | 0.12%   |
| GN Netcom                                    | 1         | 0.12%   |
| FiiO Electronics Technology                  | 1         | 0.12%   |
| Ensoniq                                      | 1         | 0.12%   |
| Creative Technology                          | 1         | 0.12%   |
| Creative Labs                                | 1         | 0.12%   |
| Cooler Master                                | 1         | 0.12%   |
| Cambridge Audio                              | 1         | 0.12%   |
| Barco Display Systems                        | 1         | 0.12%   |
| Audio-Technica                               | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 67        | 6.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 52        | 5.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 51        | 5.17%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 44        | 4.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 39        | 3.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 28        | 2.84%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 25        | 2.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 24        | 2.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 24        | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 23        | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 20        | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 19        | 1.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 1.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 15        | 1.52%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 1.52%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 1.52%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 15        | 1.52%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 14        | 1.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 14        | 1.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 12        | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 1.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 1.12%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 0.91%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 8         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 0.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 0.81%   |
| Intel 200 Series PCH HD Audio                                                                     | 8         | 0.81%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 8         | 0.81%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 7         | 0.71%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 7         | 0.71%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 0.61%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 6         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston                                | 102       | 24.88%  |
| Samsung Electronics                     | 71        | 17.32%  |
| SK hynix                                | 61        | 14.88%  |
| Micron Technology                       | 31        | 7.56%   |
| Corsair                                 | 28        | 6.83%   |
| Unknown                                 | 22        | 5.37%   |
| A-DATA Technology                       | 15        | 3.66%   |
| Nanya Technology                        | 11        | 2.68%   |
| Crucial                                 | 9         | 2.2%    |
| Ramaxel Technology                      | 8         | 1.95%   |
| Team                                    | 6         | 1.46%   |
| Unknown                                 | 6         | 1.46%   |
| Kingmax                                 | 5         | 1.22%   |
| Apacer                                  | 5         | 1.22%   |
| PNY                                     | 4         | 0.98%   |
| Elpida                                  | 4         | 0.98%   |
| Unknown (ABCD)                          | 3         | 0.73%   |
| Transcend                               | 3         | 0.73%   |
| G.Skill                                 | 3         | 0.73%   |
| Silicon Power                           | 2         | 0.49%   |
| Kimtigo                                 | 2         | 0.49%   |
| Unknown (08AE)                          | 1         | 0.24%   |
| Silicon Power Computer & Communications | 1         | 0.24%   |
| SemsoTai                                | 1         | 0.24%   |
| Patriot Memory                          | 1         | 0.24%   |
| MAXSUN                                  | 1         | 0.24%   |
| Lexar                                   | 1         | 0.24%   |
| Kinlstuo                                | 1         | 0.24%   |
| Hewlett-Packard                         | 1         | 0.24%   |
| Goldenmars                              | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s              | 7         | 1.61%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3600MT/s           | 6         | 1.38%   |
| Unknown                                                          | 6         | 1.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.15%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 5         | 1.15%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 4         | 0.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.92%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s            | 4         | 0.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.69%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.69%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 3         | 0.69%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.69%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 3         | 0.69%   |
| Kingmax RAM FLFE85F-C8KM9 2GB DIMM DDR3 1333MT/s                 | 3         | 0.69%   |
| Kingmax RAM FLFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                 | 3         | 0.69%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                       | 3         | 0.69%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 2         | 0.46%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 0.46%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 2         | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.46%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.46%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.46%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.46%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.46%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471B2873EH1-CF8 1GB SODIMM 1067MT/s                 | 2         | 0.46%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 0.46%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 152       | 44.44%  |
| DDR3    | 123       | 35.96%  |
| SDRAM   | 21        | 6.14%   |
| DDR5    | 13        | 3.8%    |
| DDR2    | 9         | 2.63%   |
| LPDDR4  | 8         | 2.34%   |
| LPDDR3  | 7         | 2.05%   |
| Unknown | 4         | 1.17%   |
| LPDDR5  | 2         | 0.58%   |
| DDR     | 2         | 0.58%   |
| DRAM    | 1         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 181       | 53.71%  |
| DIMM         | 139       | 41.25%  |
| Row Of Chips | 13        | 3.86%   |
| Unknown      | 2         | 0.59%   |
| FB-DIMM      | 1         | 0.3%    |
| Chip         | 1         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 143       | 38.65%  |
| 4096  | 93        | 25.14%  |
| 2048  | 53        | 14.32%  |
| 16384 | 45        | 12.16%  |
| 32768 | 27        | 7.3%    |
| 1024  | 9         | 2.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 83        | 21.9%   |
| 3200    | 50        | 13.19%  |
| 2667    | 46        | 12.14%  |
| 2400    | 28        | 7.39%   |
| 1333    | 26        | 6.86%   |
| 2133    | 19        | 5.01%   |
| 1334    | 19        | 5.01%   |
| 3600    | 11        | 2.9%    |
| 1067    | 9         | 2.37%   |
| 667     | 8         | 2.11%   |
| 800     | 7         | 1.85%   |
| Unknown | 7         | 1.85%   |
| 5600    | 5         | 1.32%   |
| 4800    | 5         | 1.32%   |
| 1867    | 5         | 1.32%   |
| 3933    | 4         | 1.06%   |
| 1066    | 4         | 1.06%   |
| 5200    | 3         | 0.79%   |
| 4267    | 3         | 0.79%   |
| 3733    | 3         | 0.79%   |
| 2666    | 3         | 0.79%   |
| 2048    | 3         | 0.79%   |
| 1800    | 3         | 0.79%   |
| 6400    | 2         | 0.53%   |
| 4199    | 2         | 0.53%   |
| 3266    | 2         | 0.53%   |
| 2134    | 2         | 0.53%   |
| 1866    | 2         | 0.53%   |
| 49926   | 1         | 0.26%   |
| 8400    | 1         | 0.26%   |
| 6000    | 1         | 0.26%   |
| 3800    | 1         | 0.26%   |
| 3666    | 1         | 0.26%   |
| 3534    | 1         | 0.26%   |
| 3466    | 1         | 0.26%   |
| 3400    | 1         | 0.26%   |
| 3334    | 1         | 0.26%   |
| 3333    | 1         | 0.26%   |
| 3000    | 1         | 0.26%   |
| 2933    | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 22.22%  |
| Brother Industries  | 4         | 22.22%  |
| Seiko Epson         | 3         | 16.67%  |
| Samsung Electronics | 3         | 16.67%  |
| Canon               | 3         | 16.67%  |
| Prolific Technology | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-3400 Series       | 3         | 16.67%  |
| Canon E410 series             | 2         | 11.11%  |
| Seiko Epson L3150 Series      | 1         | 5.56%   |
| Seiko Epson L312 Series       | 1         | 5.56%   |
| Seiko Epson L210 Series       | 1         | 5.56%   |
| Prolific PL2305 Parallel Port | 1         | 5.56%   |
| HP LaserJet P1006             | 1         | 5.56%   |
| HP Ink Tank 110 series        | 1         | 5.56%   |
| HP DeskJet F4200 series       | 1         | 5.56%   |
| HP DeskJet 2700 series        | 1         | 5.56%   |
| Canon LBP6030/6030B/6018L     | 1         | 5.56%   |
| Brother MFC-1910W             | 1         | 5.56%   |
| Brother DCP-J105              | 1         | 5.56%   |
| Brother DCP-1610W             | 1         | 5.56%   |
| Brother DCP-1510              | 1         | 5.56%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 63        | 19.03%  |
| Microdia                               | 33        | 9.97%   |
| IMC Networks                           | 31        | 9.37%   |
| Sunplus Innovation Technology          | 24        | 7.25%   |
| Realtek Semiconductor                  | 23        | 6.95%   |
| Bison Electronics                      | 18        | 5.44%   |
| Suyin                                  | 16        | 4.83%   |
| Logitech                               | 16        | 4.83%   |
| Apple                                  | 16        | 4.83%   |
| Quanta                                 | 12        | 3.63%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 3.02%   |
| Generalplus Technology                 | 9         | 2.72%   |
| Syntek                                 | 7         | 2.11%   |
| Luxvisions Innotech Limited            | 6         | 1.81%   |
| Alcor Micro                            | 6         | 1.81%   |
| Lite-On Technology                     | 5         | 1.51%   |
| ShineTech                              | 4         | 1.21%   |
| Acer                                   | 4         | 1.21%   |
| YGTek                                  | 3         | 0.91%   |
| Silicon Motion                         | 3         | 0.91%   |
| Sonix Technology                       | 2         | 0.6%    |
| Samsung Electronics                    | 2         | 0.6%    |
| Lenovo                                 | 2         | 0.6%    |
| Jieli Technology                       | 2         | 0.6%    |
| Genesys Logic                          | 2         | 0.6%    |
| Z-Star Microelectronics                | 1         | 0.3%    |
| WCM_USB                                | 1         | 0.3%    |
| vivo                                   | 1         | 0.3%    |
| Sunplus Technology                     | 1         | 0.3%    |
| Ricoh                                  | 1         | 0.3%    |
| Remo Tech                              | 1         | 0.3%    |
| Primax Electronics                     | 1         | 0.3%    |
| OmniVision Technologies                | 1         | 0.3%    |
| icSpring                               | 1         | 0.3%    |
| eMPIA Technology                       | 1         | 0.3%    |
| Cubeternet                             | 1         | 0.3%    |
| ARC International                      | 1         | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 12        | 3.6%    |
| Chicony Integrated Camera                               | 10        | 3%      |
| Chicony USB2.0 VGA UVC WebCam                           | 9         | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 8         | 2.4%    |
| Sunplus Integrated_Webcam_HD                            | 7         | 2.1%    |
| Generalplus GENERAL WEBCAM                              | 7         | 2.1%    |
| IMC Networks Integrated Camera                          | 6         | 1.8%    |
| Chicony HD WebCam                                       | 6         | 1.8%    |
| Microdia USB 2.0 Camera                                 | 5         | 1.5%    |
| Apple Built-in iSight                                   | 5         | 1.5%    |
| ShineTech USB2.0 HD UVC WebCam                          | 4         | 1.2%    |
| Realtek Integrated_Webcam_HD                            | 4         | 1.2%    |
| Microdia Laptop_Integrated_Webcam_HD                    | 4         | 1.2%    |
| Logitech Webcam C270                                    | 4         | 1.2%    |
| Logitech HD Pro Webcam C920                             | 4         | 1.2%    |
| Lite-On Integrated Camera                               | 4         | 1.2%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 4         | 1.2%    |
| IMC Networks USB2.0 UVC HD Webcam                       | 4         | 1.2%    |
| Chicony USB2.0 HD UVC WebCam                            | 4         | 1.2%    |
| Chicony Integrated Camera (1280x720@30)                 | 4         | 1.2%    |
| Chicony HP HD Webcam                                    | 4         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 4         | 1.2%    |
| Bison HD Webcam                                         | 4         | 1.2%    |
| Apple FaceTime HD Camera                                | 4         | 1.2%    |
| YGTek Webcam                                            | 3         | 0.9%    |
| Syntek USB Camera Device                                | 3         | 0.9%    |
| Suyin 1.3M HD WebCam                                    | 3         | 0.9%    |
| Sunplus Laptop Integrated Webcam HD                     | 3         | 0.9%    |
| Realtek HD WebCam                                       | 3         | 0.9%    |
| Quanta HP TrueVision HD Camera                          | 3         | 0.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 3         | 0.9%    |
| Chicony HP Wide Vision HD Camera                        | 3         | 0.9%    |
| Bison Lenovo Integrated Webcam                          | 3         | 0.9%    |
| Bison Lenovo EasyCamera                                 | 3         | 0.9%    |
| Bison Integrated Camera                                 | 3         | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 3         | 0.9%    |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 0.9%    |
| Syntek Integrated Camera                                | 2         | 0.6%    |
| Suyin WebCam                                            | 2         | 0.6%    |
| Suyin Laptop_Integrated_Webcam_HD                       | 2         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 31.11%  |
| Synaptics                  | 11        | 24.44%  |
| Shenzhen Goodix Technology | 7         | 15.56%  |
| Elan Microelectronics      | 5         | 11.11%  |
| Upek                       | 3         | 6.67%   |
| AuthenTec                  | 3         | 6.67%   |
| LighTuning Technology      | 1         | 2.22%   |
| Focal-systems.Corp         | 1         | 2.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Synaptics Metallica MOH Touch Fingerprint Reader            | 4         | 8.89%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 3         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 3         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                         | 3         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                          | 3         | 6.67%   |
| Elan ELAN:ARM-M4                                            | 3         | 6.67%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 2         | 4.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 2         | 4.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 2         | 4.44%   |
| Elan ELAN:Fingerprint                                       | 2         | 4.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 1         | 2.22%   |
| Validity Sensors VFS491                                     | 1         | 2.22%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 1         | 2.22%   |
| Validity Sensors Synaptics WBDI                             | 1         | 2.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 2.22%   |
| Validity Sensors Swipe Fingerprint Sensor                   | 1         | 2.22%   |
| Validity Sensors Fingerprint scanner                        | 1         | 2.22%   |
| Synaptics WBDI Fingerprint Reader USB 086                   | 1         | 2.22%   |
| Synaptics UWP WBDI                                          | 1         | 2.22%   |
| Synaptics  WBDI                                             | 1         | 2.22%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 2.22%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint    | 1         | 2.22%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 2.22%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 1         | 2.22%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                   | 1         | 2.22%   |
| AuthenTec Fingerprint Sensor                                | 1         | 2.22%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 1         | 2.22%   |
| AuthenTec AES1660 Fingerprint Sensor                        | 1         | 2.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 13        | 76.47%  |
| O2 Micro    | 2         | 11.76%  |
| Lenovo      | 1         | 5.88%   |
| Alcor Micro | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 23.53%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 23.53%  |
| Broadcom 58200                                                               | 3         | 17.65%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 11.76%  |
| Broadcom 5880                                                                | 2         | 11.76%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5.88%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 465       | 72.66%  |
| 1     | 149       | 23.28%  |
| 2     | 20        | 3.13%   |
| 3     | 3         | 0.47%   |
| 9     | 1         | 0.16%   |
| 6     | 1         | 0.16%   |
| 5     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 58        | 28.43%  |
| Fingerprint reader       | 45        | 22.06%  |
| Net/wireless             | 34        | 16.67%  |
| Multimedia controller    | 17        | 8.33%   |
| Chipcard                 | 15        | 7.35%   |
| Communication controller | 8         | 3.92%   |
| Unassigned class         | 5         | 2.45%   |
| Bluetooth                | 5         | 2.45%   |
| Sound                    | 4         | 1.96%   |
| Storage                  | 3         | 1.47%   |
| Camera                   | 3         | 1.47%   |
| Storage/ide              | 2         | 0.98%   |
| Net/ethernet             | 2         | 0.98%   |
| Network                  | 1         | 0.49%   |
| Modem                    | 1         | 0.49%   |
| Card reader              | 1         | 0.49%   |

