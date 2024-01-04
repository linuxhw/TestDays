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

Total: 4648

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Chuwi         | HeroBook Pro                | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
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
| Chuwi         | HeroBook Pro                | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
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
| HP            | Pavilion dv7                | [8b90982317](https://linux-hardware.org/?probe=8b90982317) | Apr 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [db614f561e](https://linux-hardware.org/?probe=db614f561e) | Apr 23, 2023 |
| ASUSTek       | X510UAR                     | [3321ccb912](https://linux-hardware.org/?probe=3321ccb912) | Apr 23, 2023 |
| Google        | Kefka                       | [2802d83837](https://linux-hardware.org/?probe=2802d83837) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [63599179ae](https://linux-hardware.org/?probe=63599179ae) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| Gigabyte      | AERO 15-X9                  | [5eb2235e10](https://linux-hardware.org/?probe=5eb2235e10) | Apr 22, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [f2f6b7ab4e](https://linux-hardware.org/?probe=f2f6b7ab4e) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [44459cbe3a](https://linux-hardware.org/?probe=44459cbe3a) | Apr 20, 2023 |
| Dell          | Latitude E6420              | [6b5cc099a0](https://linux-hardware.org/?probe=6b5cc099a0) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| HP            | Pavilion dv7                | [f5c84d7a1b](https://linux-hardware.org/?probe=f5c84d7a1b) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [1a5add814c](https://linux-hardware.org/?probe=1a5add814c) | Apr 18, 2023 |
| Dell          | Latitude E5550              | [ce824f113c](https://linux-hardware.org/?probe=ce824f113c) | Apr 18, 2023 |
| Dell          | Latitude E5550              | [7611d6e018](https://linux-hardware.org/?probe=7611d6e018) | Apr 18, 2023 |
| Lenovo        | ThinkPad Edge 031946U       | [f9d813509a](https://linux-hardware.org/?probe=f9d813509a) | Apr 18, 2023 |
| Acer          | Nitro AN515-54              | [7b3a68ca48](https://linux-hardware.org/?probe=7b3a68ca48) | Apr 18, 2023 |
| MSI           | GF75 Thin 9SC               | [40b6c3bad6](https://linux-hardware.org/?probe=40b6c3bad6) | Apr 17, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [f8a45caf43](https://linux-hardware.org/?probe=f8a45caf43) | Apr 17, 2023 |
| Toshiba       | Satellite L850              | [2fd09b6ba5](https://linux-hardware.org/?probe=2fd09b6ba5) | Apr 16, 2023 |
| Dell          | Latitude E6430s             | [5358f67a6d](https://linux-hardware.org/?probe=5358f67a6d) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [afc478cf27](https://linux-hardware.org/?probe=afc478cf27) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [872416fe62](https://linux-hardware.org/?probe=872416fe62) | Apr 16, 2023 |
| MSI           | Modern 14 B10MW             | [c655afe860](https://linux-hardware.org/?probe=c655afe860) | Apr 15, 2023 |
| HP            | EliteBook 8440p             | [f3b7c9c255](https://linux-hardware.org/?probe=f3b7c9c255) | Apr 14, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c7b7e028e4](https://linux-hardware.org/?probe=c7b7e028e4) | Apr 14, 2023 |
| Dell          | Latitude E6420              | [7cf2e649e1](https://linux-hardware.org/?probe=7cf2e649e1) | Apr 14, 2023 |
| MSI           | GP72 7RDX                   | [2236248ba0](https://linux-hardware.org/?probe=2236248ba0) | Apr 14, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [d4de10f812](https://linux-hardware.org/?probe=d4de10f812) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7c862e338c](https://linux-hardware.org/?probe=7c862e338c) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | [15de4db91b](https://linux-hardware.org/?probe=15de4db91b) | Apr 14, 2023 |
| Dell          | Latitude 3590               | [eed6f4df10](https://linux-hardware.org/?probe=eed6f4df10) | Apr 14, 2023 |
| Toshiba       | Satellite L300D             | [76595cf176](https://linux-hardware.org/?probe=76595cf176) | Apr 12, 2023 |
| Dell          | Latitude 7390               | [9859e63f40](https://linux-hardware.org/?probe=9859e63f40) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a2c9f95f36](https://linux-hardware.org/?probe=a2c9f95f36) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [26358515bc](https://linux-hardware.org/?probe=26358515bc) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [509dbf780c](https://linux-hardware.org/?probe=509dbf780c) | Apr 12, 2023 |
| HP            | EliteBook 840 G3            | [0daac07546](https://linux-hardware.org/?probe=0daac07546) | Apr 12, 2023 |
| Gateway       | NE56R                       | [39a33d998b](https://linux-hardware.org/?probe=39a33d998b) | Apr 12, 2023 |
| Apple         | MacBookPro8,1               | [94372e3520](https://linux-hardware.org/?probe=94372e3520) | Apr 12, 2023 |
| Dell          | Latitude 7390               | [5c446957c5](https://linux-hardware.org/?probe=5c446957c5) | Apr 12, 2023 |
| HP            | Pavilion dv7                | [7cec7666c8](https://linux-hardware.org/?probe=7cec7666c8) | Apr 11, 2023 |
| HP            | Pavilion dv7                | [e3583c2121](https://linux-hardware.org/?probe=e3583c2121) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| Lenovo        | B575 1450ABU                | [ef58d2e8e6](https://linux-hardware.org/?probe=ef58d2e8e6) | Apr 09, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [e762a4eb1d](https://linux-hardware.org/?probe=e762a4eb1d) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [fa54308baa](https://linux-hardware.org/?probe=fa54308baa) | Apr 09, 2023 |
| Acer          | Predator PH315-54           | [edbc0b98a4](https://linux-hardware.org/?probe=edbc0b98a4) | Apr 08, 2023 |
| Apple         | MacBookPro11,1              | [08f117749f](https://linux-hardware.org/?probe=08f117749f) | Apr 08, 2023 |
| HP            | EliteBook 840 G5            | [0d68e199a9](https://linux-hardware.org/?probe=0d68e199a9) | Apr 05, 2023 |
| Dell          | Precision 7670              | [b5e95f0d21](https://linux-hardware.org/?probe=b5e95f0d21) | Apr 05, 2023 |
| Dell          | Latitude 7490               | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a467a04489](https://linux-hardware.org/?probe=a467a04489) | Apr 04, 2023 |
| Apple         | MacBookPro5,5               | [c674243118](https://linux-hardware.org/?probe=c674243118) | Apr 03, 2023 |
| Apple         | MacBookPro5,5               | [dca6973952](https://linux-hardware.org/?probe=dca6973952) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0b97a5a77a](https://linux-hardware.org/?probe=0b97a5a77a) | Apr 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7355f06eb3](https://linux-hardware.org/?probe=7355f06eb3) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [dabe76e4ca](https://linux-hardware.org/?probe=dabe76e4ca) | Apr 01, 2023 |
| Valve         | Jupiter                     | [a91aee62d3](https://linux-hardware.org/?probe=a91aee62d3) | Apr 01, 2023 |
| Apple         | MacBookPro11,1              | [53717700a1](https://linux-hardware.org/?probe=53717700a1) | Mar 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| Dell          | XPS M1330                   | [46b9a5cfde](https://linux-hardware.org/?probe=46b9a5cfde) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Dell          | Latitude 7490               | [06928c624b](https://linux-hardware.org/?probe=06928c624b) | Mar 31, 2023 |
| Lenovo        | G550 2958                   | [41f23ded68](https://linux-hardware.org/?probe=41f23ded68) | Mar 30, 2023 |
| Lenovo        | N22 80S6                    | [c6cbeeb984](https://linux-hardware.org/?probe=c6cbeeb984) | Mar 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [6de889ae8a](https://linux-hardware.org/?probe=6de889ae8a) | Mar 29, 2023 |
| Acer          | Swift SFX14-41G             | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| Sony          | VPCCB32FD                   | [ef684c34bb](https://linux-hardware.org/?probe=ef684c34bb) | Mar 28, 2023 |
| Dell          | Studio 1558                 | [955946c74d](https://linux-hardware.org/?probe=955946c74d) | Mar 28, 2023 |
| Dell          | Latitude 7490               | [58ccd5d7e0](https://linux-hardware.org/?probe=58ccd5d7e0) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [7dbe4350b5](https://linux-hardware.org/?probe=7dbe4350b5) | Mar 26, 2023 |
| Lenovo        | ThinkPad X220 4290LR3       | [dffa03da18](https://linux-hardware.org/?probe=dffa03da18) | Mar 26, 2023 |
| Lenovo        | ThinkPad T430 4237ZC7       | [845a2ed117](https://linux-hardware.org/?probe=845a2ed117) | Mar 26, 2023 |
| Sony          | VPCCB32FD                   | [20d8516896](https://linux-hardware.org/?probe=20d8516896) | Mar 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [513b14ace5](https://linux-hardware.org/?probe=513b14ace5) | Mar 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4f2d3a2402](https://linux-hardware.org/?probe=4f2d3a2402) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Apple         | MacBookPro11,2              | [ded37ac14c](https://linux-hardware.org/?probe=ded37ac14c) | Mar 24, 2023 |
| Apple         | MacBookPro11,2              | [13046d5580](https://linux-hardware.org/?probe=13046d5580) | Mar 24, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [aeb25bc22b](https://linux-hardware.org/?probe=aeb25bc22b) | Mar 23, 2023 |
| Dell          | Vostro 5620                 | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [c91fa425a5](https://linux-hardware.org/?probe=c91fa425a5) | Mar 23, 2023 |
| Acer          | Aspire A515-55              | [ebbb5efcbc](https://linux-hardware.org/?probe=ebbb5efcbc) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| ASUSTek       | G53SX                       | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| Framework     | Laptop                      | [a7dc7b28c9](https://linux-hardware.org/?probe=a7dc7b28c9) | Mar 21, 2023 |
| Fujitsu       | FMVNP8AE                    | [10efc9f976](https://linux-hardware.org/?probe=10efc9f976) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [63b182c7d6](https://linux-hardware.org/?probe=63b182c7d6) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7df2952615](https://linux-hardware.org/?probe=7df2952615) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [40f92632ab](https://linux-hardware.org/?probe=40f92632ab) | Mar 16, 2023 |
| HP            | Laptop 15-dy1xxx            | [63893daa0f](https://linux-hardware.org/?probe=63893daa0f) | Mar 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [5d43e434bc](https://linux-hardware.org/?probe=5d43e434bc) | Mar 16, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [ae37b87da6](https://linux-hardware.org/?probe=ae37b87da6) | Mar 16, 2023 |
| Dell          | Inspiron 15-3552            | [10e835b353](https://linux-hardware.org/?probe=10e835b353) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Matsushita... | CF-18KH2ZXBC                | [9aa73891cd](https://linux-hardware.org/?probe=9aa73891cd) | Mar 15, 2023 |
| Toshiba       | Satellite P870              | [113fcf770d](https://linux-hardware.org/?probe=113fcf770d) | Mar 15, 2023 |
| Acer          | Aspire 5750Z                | [3ea59ee8c5](https://linux-hardware.org/?probe=3ea59ee8c5) | Mar 14, 2023 |
| Dell          | Latitude E7240              | [7fbe857344](https://linux-hardware.org/?probe=7fbe857344) | Mar 14, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [9332803ca3](https://linux-hardware.org/?probe=9332803ca3) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [1525ad44e2](https://linux-hardware.org/?probe=1525ad44e2) | Mar 12, 2023 |

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
| Ubuntu 20.04                 | 361       | 11.1%   |
| Ubuntu 18.04                 | 200       | 6.15%   |
| Ubuntu 22.04                 | 185       | 5.69%   |
| Pop!_OS 22.04                | 83        | 2.55%   |
| Zorin 16                     | 70        | 2.15%   |
| Arch Rolling                 | 62        | 1.91%   |
| OpenMandriva 4.3             | 57        | 1.75%   |
| Fedora 38                    | 55        | 1.69%   |
| Manjaro                      | 54        | 1.66%   |
| Linux Mint 20.3              | 53        | 1.63%   |
| Debian 11                    | 53        | 1.63%   |
| KDE neon 20.04               | 50        | 1.54%   |
| OpenMandriva 4.2             | 49        | 1.51%   |
| Arch                         | 48        | 1.48%   |
| ArcoLinux Rolling            | 47        | 1.45%   |
| Zorin 15                     | 43        | 1.32%   |
| Xubuntu 20.04                | 43        | 1.32%   |
| Linux Mint 21.1              | 42        | 1.29%   |
| Ubuntu 19.10                 | 39        | 1.2%    |
| Linux Mint 19.3              | 39        | 1.2%    |
| Pop!_OS 21.04                | 38        | 1.17%   |
| Pop!_OS 20.04                | 36        | 1.11%   |
| Fedora 37                    | 36        | 1.11%   |
| Fedora 35                    | 35        | 1.08%   |
| Ubuntu 21.10                 | 33        | 1.01%   |
| Linux Mint 21                | 33        | 1.01%   |
| Ubuntu 20.10                 | 31        | 0.95%   |
| Linux Mint 20.1              | 31        | 0.95%   |
| Linux Mint 21.2              | 30        | 0.92%   |
| Linux Mint 20.2              | 30        | 0.92%   |
| Debian 12                    | 30        | 0.92%   |
| Pop!_OS 20.10                | 29        | 0.89%   |
| EndeavourOS Rolling          | 28        | 0.86%   |
| Ubuntu 19.04                 | 27        | 0.83%   |
| Ubuntu 23.04                 | 26        | 0.8%    |
| openSUSE Tumbleweed-XXXXXXXX | 26        | 0.8%    |
| Linux Mint 20                | 26        | 0.8%    |
| OpenMandriva 23.03           | 24        | 0.74%   |
| OpenMandriva 23.01           | 24        | 0.74%   |
| Fedora 32                    | 24        | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 938       | 30.28%  |
| Linux Mint    | 279       | 9.01%   |
| Fedora        | 235       | 7.59%   |
| Pop!_OS       | 201       | 6.49%   |
| OpenMandriva  | 190       | 6.13%   |
| Debian        | 138       | 4.45%   |
| Zorin         | 119       | 3.84%   |
| Manjaro       | 112       | 3.62%   |
| Arch          | 105       | 3.39%   |
| Xubuntu       | 73        | 2.36%   |
| KDE neon      | 72        | 2.32%   |
| Kubuntu       | 61        | 1.97%   |
| SteamOS       | 52        | 1.68%   |
| ArcoLinux     | 51        | 1.65%   |
| ROSA          | 36        | 1.16%   |
| Kali          | 36        | 1.16%   |
| Gentoo        | 34        | 1.1%    |
| openSUSE      | 30        | 0.97%   |
| EndeavourOS   | 30        | 0.97%   |
| Elementary    | 26        | 0.84%   |
| Lubuntu       | 24        | 0.77%   |
| MX            | 23        | 0.74%   |
| Clear Linux   | 19        | 0.61%   |
| Endless       | 17        | 0.55%   |
| BlackPanther  | 16        | 0.52%   |
| Garuda Linux  | 15        | 0.48%   |
| Ubuntu Unity  | 12        | 0.39%   |
| Ubuntu Budgie | 12        | 0.39%   |
| Parrot        | 10        | 0.32%   |
| LMDE          | 10        | 0.32%   |
| Ubuntu MATE   | 9         | 0.29%   |
| Peppermint    | 9         | 0.29%   |
| Alpine        | 9         | 0.29%   |
| Xero          | 6         | 0.19%   |
| Nobara        | 6         | 0.19%   |
| CentOS        | 6         | 0.19%   |
| Ubuntu Studio | 5         | 0.16%   |
| NixOS         | 5         | 0.16%   |
| LinuxFX       | 5         | 0.16%   |
| Artix         | 4         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 51        | 1.42%   |
| 5.10.14-desktop-1omv4002 | 47        | 1.31%   |
| 5.4.0-42-generic         | 45        | 1.25%   |
| 5.11.0-27-generic        | 42        | 1.17%   |
| 5.15.0-56-generic        | 32        | 0.89%   |
| 5.3.0-40-generic         | 27        | 0.75%   |
| 6.2.6-desktop-1omv2390   | 24        | 0.67%   |
| 5.15.0-52-generic        | 24        | 0.67%   |
| 5.10.10-64               | 24        | 0.67%   |
| 6.1.1-desktop-1omv2290   | 23        | 0.64%   |
| 5.4.0-29-generic         | 23        | 0.64%   |
| 5.15.0-58-generic        | 23        | 0.64%   |
| 5.4.0-52-generic         | 21        | 0.58%   |
| 5.4.0-40-generic         | 21        | 0.58%   |
| 5.0.0-37-generic         | 21        | 0.58%   |
| 6.2.0-26-generic         | 20        | 0.56%   |
| 5.8.0-7630-generic       | 20        | 0.56%   |
| 5.4.0-58-generic         | 20        | 0.56%   |
| 5.3.0-46-generic         | 20        | 0.56%   |
| 5.4.0-48-generic         | 18        | 0.5%    |
| 5.4.0-45-generic         | 18        | 0.5%    |
| 5.15.0-41-generic        | 18        | 0.5%    |
| 5.13.0-valve36-1-neptune | 18        | 0.5%    |
| 6.4.11-desktop-1omv2390  | 17        | 0.47%   |
| 6.2.6-76060206-generic   | 17        | 0.47%   |
| 5.15.0-71-generic        | 16        | 0.44%   |
| 5.15.0-46-generic        | 16        | 0.44%   |
| 5.4.0-37-generic         | 15        | 0.42%   |
| 5.4.0-26-generic         | 15        | 0.42%   |
| 5.15.0-47-generic        | 15        | 0.42%   |
| 5.13.0-7614-generic      | 15        | 0.42%   |
| 5.11.0-40-generic        | 15        | 0.42%   |
| 5.8.0-41-generic         | 14        | 0.39%   |
| 5.4.0-91-generic         | 14        | 0.39%   |
| 5.4.0-47-generic         | 14        | 0.39%   |
| 5.3.0-42-generic         | 14        | 0.39%   |
| 5.15.0-60-generic        | 14        | 0.39%   |
| 5.13.0-30-generic        | 14        | 0.39%   |
| 5.11.0-38-generic        | 14        | 0.39%   |
| 6.5.0-14-generic         | 13        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 476       | 14.1%   |
| 5.15.0  | 287       | 8.5%    |
| 5.11.0  | 178       | 5.27%   |
| 5.13.0  | 169       | 5%      |
| 5.8.0   | 147       | 4.35%   |
| 5.3.0   | 144       | 4.26%   |
| 4.15.0  | 141       | 4.18%   |
| 6.2.0   | 100       | 2.96%   |
| 5.19.0  | 98        | 2.9%    |
| 5.0.0   | 88        | 2.61%   |
| 5.10.0  | 69        | 2.04%   |
| 5.16.7  | 53        | 1.57%   |
| 4.18.0  | 49        | 1.45%   |
| 5.10.14 | 48        | 1.42%   |
| 6.1.0   | 46        | 1.36%   |
| 6.2.6   | 43        | 1.27%   |
| 6.5.0   | 32        | 0.95%   |
| 6.1.1   | 27        | 0.8%    |
| 5.10.10 | 26        | 0.77%   |
| 4.19.0  | 22        | 0.65%   |
| 6.4.11  | 20        | 0.59%   |
| 6.5.6   | 18        | 0.53%   |
| 5.14.0  | 17        | 0.5%    |
| 6.2.9   | 14        | 0.41%   |
| 6.0.0   | 14        | 0.41%   |
| 5.17.5  | 13        | 0.38%   |
| 5.18.0  | 12        | 0.36%   |
| 5.16.13 | 12        | 0.36%   |
| 6.0.6   | 11        | 0.33%   |
| 5.15.5  | 11        | 0.33%   |
| 4.18.16 | 11        | 0.33%   |
| 6.2.10  | 10        | 0.3%    |
| 6.1.52  | 10        | 0.3%    |
| 6.0.12  | 10        | 0.3%    |
| 6.6.2   | 9         | 0.27%   |
| 5.9.16  | 9         | 0.27%   |
| 5.9.11  | 9         | 0.27%   |
| 5.15.11 | 9         | 0.27%   |
| 6.4.8   | 8         | 0.24%   |
| 6.4.12  | 8         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 518       | 15.58%  |
| 5.15    | 383       | 11.52%  |
| 5.11    | 203       | 6.11%   |
| 6.2     | 199       | 5.99%   |
| 5.8     | 197       | 5.93%   |
| 5.13    | 189       | 5.69%   |
| 5.10    | 187       | 5.63%   |
| 5.3     | 153       | 4.6%    |
| 4.15    | 142       | 4.27%   |
| 6.1     | 124       | 3.73%   |
| 5.19    | 122       | 3.67%   |
| 5.16    | 106       | 3.19%   |
| 6.5     | 93        | 2.8%    |
| 5.0     | 90        | 2.71%   |
| 6.0     | 73        | 2.2%    |
| 6.4     | 65        | 1.96%   |
| 4.18    | 60        | 1.81%   |
| 5.17    | 49        | 1.47%   |
| 5.9     | 44        | 1.32%   |
| 6.6     | 40        | 1.2%    |
| 5.14    | 40        | 1.2%    |
| 5.18    | 38        | 1.14%   |
| 6.3     | 37        | 1.11%   |
| 5.12    | 31        | 0.93%   |
| 4.19    | 29        | 0.87%   |
| 5.6     | 26        | 0.78%   |
| 4.9     | 24        | 0.72%   |
| 5.7     | 23        | 0.69%   |
| 5.5     | 13        | 0.39%   |
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
| 3.18    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2877      | 97.1%   |
| i686    | 81        | 2.73%   |
| armv7l  | 3         | 0.1%    |
| aarch64 | 2         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| GNOME                | 1344      | 43.23%  |
| KDE5                 | 568       | 18.27%  |
| Unknown              | 327       | 10.52%  |
| XFCE                 | 245       | 7.88%   |
| X-Cinnamon           | 226       | 7.27%   |
| KDE                  | 76        | 2.44%   |
| MATE                 | 64        | 2.06%   |
| LXDE                 | 40        | 1.29%   |
| Cinnamon             | 36        | 1.16%   |
| LXQt                 | 26        | 0.84%   |
| KDE4                 | 25        | 0.8%    |
| Pantheon             | 24        | 0.77%   |
| i3                   | 23        | 0.74%   |
| Budgie               | 16        | 0.51%   |
| Unity                | 15        | 0.48%   |
| GNOME Flashback      | 10        | 0.32%   |
| DWM                  | 6         | 0.19%   |
| Deepin               | 5         | 0.16%   |
| sway                 | 4         | 0.13%   |
| qtile                | 4         | 0.13%   |
| Enlightenment        | 4         | 0.13%   |
| xmonad               | 3         | 0.1%    |
| GNOME Classic        | 3         | 0.1%    |
| awesome              | 3         | 0.1%    |
| Hyprland             | 2         | 0.06%   |
| chadwm               | 2         | 0.06%   |
| xsession             | 1         | 0.03%   |
| wmaker-common        | 1         | 0.03%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.03%   |
| spectrwm             | 1         | 0.03%   |
| lightdm-xsession     | 1         | 0.03%   |
| Jwm                  | 1         | 0.03%   |
| GNOME-Classic        | 1         | 0.03%   |
| bspwm                | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2269      | 74.03%  |
| Wayland | 577       | 18.83%  |
| Unknown | 185       | 6.04%   |
| Tty     | 33        | 1.08%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1548      | 49.9%   |
| SDDM    | 470       | 15.15%  |
| GDM3    | 359       | 11.57%  |
| GDM     | 305       | 9.83%   |
| LightDM | 281       | 9.06%   |
| TDM     | 74        | 2.39%   |
| NODM    | 24        | 0.77%   |
| KDM     | 24        | 0.77%   |
| XDM     | 6         | 0.19%   |
| Ly      | 6         | 0.19%   |
| LXDM    | 4         | 0.13%   |
| LY-DM   | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_CA   | 1515      | 49.35%  |
| en_US   | 889       | 28.96%  |
| Unknown | 284       | 9.25%   |
| fr_CA   | 207       | 6.74%   |
| C       | 70        | 2.28%   |
| fr_FR   | 35        | 1.14%   |
| en_GB   | 15        | 0.49%   |
| C.UTF8  | 8         | 0.26%   |
| POSIX   | 6         | 0.2%    |
| en_IN   | 4         | 0.13%   |
| en_AU   | 4         | 0.13%   |
| pt_BR   | 3         | 0.1%    |
| hu_HU   | 3         | 0.1%    |
| es_ES   | 3         | 0.1%    |
| zh_CN   | 2         | 0.07%   |
| uk_UA   | 2         | 0.07%   |
| ru_RU   | 2         | 0.07%   |
| pl_PL   | 2         | 0.07%   |
| zh_TW   | 1         | 0.03%   |
| tr_TR   | 1         | 0.03%   |
| ro_RO   | 1         | 0.03%   |
| pa_IN   | 1         | 0.03%   |
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
| BIOS | 1544      | 50.76%  |
| EFI  | 1498      | 49.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2191      | 71.88%  |
| Btrfs   | 357       | 11.71%  |
| Overlay | 244       | 8.01%   |
| Tmpfs   | 81        | 2.66%   |
| Unknown | 79        | 2.59%   |
| Xfs     | 29        | 0.95%   |
| Zfs     | 27        | 0.89%   |
| Rootfs  | 24        | 0.79%   |
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
| Unknown | 1608      | 52.72%  |
| GPT     | 1145      | 37.54%  |
| MBR     | 297       | 9.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2650      | 87.81%  |
| Yes       | 368       | 12.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2283      | 75.72%  |
| Yes       | 732       | 24.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 611       | 20.63%  |
| Dell                           | 547       | 18.47%  |
| Hewlett-Packard                | 473       | 15.97%  |
| ASUSTek Computer               | 336       | 11.35%  |
| Acer                           | 299       | 10.1%   |
| Apple                          | 128       | 4.32%   |
| Toshiba                        | 112       | 3.78%   |
| MSI                            | 82        | 2.77%   |
| Valve                          | 50        | 1.69%   |
| Google                         | 39        | 1.32%   |
| Sony                           | 38        | 1.28%   |
| Alienware                      | 28        | 0.95%   |
| System76                       | 23        | 0.78%   |
| Samsung Electronics            | 23        | 0.78%   |
| Panasonic                      | 20        | 0.68%   |
| Gateway                        | 20        | 0.68%   |
| Unknown                        | 20        | 0.68%   |
| Gigabyte Technology            | 10        | 0.34%   |
| Fujitsu                        | 10        | 0.34%   |
| Razer                          | 9         | 0.3%    |
| Framework                      | 8         | 0.27%   |
| Notebook                       | 7         | 0.24%   |
| HUAWEI                         | 6         | 0.2%    |
| LG Electronics                 | 5         | 0.17%   |
| Matsushita Electric Industrial | 4         | 0.14%   |
| Intel Client Systems           | 4         | 0.14%   |
| EUROCOM                        | 4         | 0.14%   |
| GPU Company                    | 3         | 0.1%    |
| eMachines                      | 3         | 0.1%    |
| Purism                         | 2         | 0.07%   |
| Motion Computing               | 2         | 0.07%   |
| Intel                          | 2         | 0.07%   |
| Getac                          | 2         | 0.07%   |
| Datto                          | 2         | 0.07%   |
| Chuwi                          | 2         | 0.07%   |
| BOSGAME                        | 2         | 0.07%   |
| AZW                            | 2         | 0.07%   |
| Xplore                         | 1         | 0.03%   |
| VIT                            | 1         | 0.03%   |
| Timi                           | 1         | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Valve Jupiter          | 48        | 1.62%   |
| Unknown                | 29        | 0.98%   |
| HP Notebook            | 24        | 0.81%   |
| HP Pavilion g6         | 20        | 0.68%   |
| Acer Aspire A315-21    | 17        | 0.57%   |
| Dell Latitude E6410    | 15        | 0.51%   |
| Dell XPS 15 9500       | 14        | 0.47%   |
| Dell XPS 15 7590       | 14        | 0.47%   |
| Dell Latitude E6420    | 14        | 0.47%   |
| Apple MacBookPro9,2    | 14        | 0.47%   |
| Apple MacBookPro8,1    | 13        | 0.44%   |
| HP Pavilion Notebook   | 12        | 0.41%   |
| HP Pavilion dv6        | 12        | 0.41%   |
| HP Pavilion 15         | 11        | 0.37%   |
| HP EliteBook 8460p     | 10        | 0.34%   |
| HP Pavilion dv7        | 9         | 0.3%    |
| Dell XPS 13 9310       | 9         | 0.3%    |
| Dell Latitude E6540    | 9         | 0.3%    |
| Apple MacBookPro5,5    | 9         | 0.3%    |
| Acer Aspire 5742       | 9         | 0.3%    |
| Toshiba Satellite A200 | 8         | 0.27%   |
| HP Laptop 15-db0xxx    | 8         | 0.27%   |
| HP EliteBook 840 G3    | 8         | 0.27%   |
| Dell XPS 13 9360       | 8         | 0.27%   |
| Dell Latitude E6440    | 8         | 0.27%   |
| Dell Latitude E6430    | 8         | 0.27%   |
| Dell Latitude 7490     | 8         | 0.27%   |
| Dell Inspiron 1545     | 8         | 0.27%   |
| Acer Aspire A315-42    | 8         | 0.27%   |
| Toshiba Satellite C650 | 7         | 0.24%   |
| HP EliteBook 840 G1    | 7         | 0.24%   |
| HP 2000                | 7         | 0.24%   |
| Dell XPS 15 9570       | 7         | 0.24%   |
| Dell XPS 15 9560       | 7         | 0.24%   |
| Dell Latitude E6400    | 7         | 0.24%   |
| Dell Latitude D830     | 7         | 0.24%   |
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
| Lenovo ThinkPad    | 407       | 13.75%  |
| Acer Aspire        | 229       | 7.73%   |
| Dell Latitude      | 200       | 6.75%   |
| Dell Inspiron      | 135       | 4.56%   |
| HP Pavilion        | 121       | 4.09%   |
| Dell XPS           | 117       | 3.95%   |
| Lenovo IdeaPad     | 102       | 3.44%   |
| HP EliteBook       | 95        | 3.21%   |
| Toshiba Satellite  | 94        | 3.17%   |
| ASUS VivoBook      | 78        | 2.63%   |
| HP Laptop          | 71        | 2.4%    |
| Valve Jupiter      | 48        | 1.62%   |
| HP ProBook         | 48        | 1.62%   |
| ASUS ROG           | 40        | 1.35%   |
| Dell Precision     | 37        | 1.25%   |
| Unknown            | 29        | 0.98%   |
| Lenovo Legion      | 28        | 0.95%   |
| Acer Swift         | 26        | 0.88%   |
| ASUS ZenBook       | 25        | 0.84%   |
| HP Notebook        | 24        | 0.81%   |
| ASUS ASUS          | 23        | 0.78%   |
| HP ENVY            | 21        | 0.71%   |
| Apple MacBookPro9  | 20        | 0.68%   |
| Dell Vostro        | 19        | 0.64%   |
| Apple MacBookPro8  | 17        | 0.57%   |
| Acer Nitro         | 17        | 0.57%   |
| Apple MacBookPro5  | 14        | 0.47%   |
| HP Stream          | 13        | 0.44%   |
| Dell Studio        | 13        | 0.44%   |
| Apple MacBookPro11 | 13        | 0.44%   |
| Lenovo ThinkBook   | 12        | 0.41%   |
| HP ZBook           | 12        | 0.41%   |
| HP Compaq          | 12        | 0.41%   |
| ASUS TUF           | 12        | 0.41%   |
| HP Presario        | 9         | 0.3%    |
| Dell System        | 9         | 0.3%    |
| Toshiba TECRA      | 8         | 0.27%   |
| Razer Blade        | 8         | 0.27%   |
| Framework Laptop   | 8         | 0.27%   |
| Apple MacBookPro6  | 8         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 249       | 8.41%   |
| 2012    | 249       | 8.41%   |
| 2011    | 249       | 8.41%   |
| 2018    | 228       | 7.7%    |
| 2019    | 225       | 7.6%    |
| 2017    | 197       | 6.65%   |
| 2013    | 191       | 6.45%   |
| 2014    | 181       | 6.11%   |
| 2010    | 171       | 5.78%   |
| 2021    | 169       | 5.71%   |
| 2022    | 159       | 5.37%   |
| 2016    | 140       | 4.73%   |
| 2008    | 129       | 4.36%   |
| 2015    | 113       | 3.82%   |
| 2009    | 102       | 3.44%   |
| 2007    | 86        | 2.9%    |
| 2023    | 76        | 2.57%   |
| 2006    | 30        | 1.01%   |
| 2005    | 9         | 0.3%    |
| Unknown | 6         | 0.2%    |
| 2004    | 2         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2961      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2727      | 91.36%  |
| Enabled  | 258       | 8.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2903      | 98.01%  |
| Yes  | 59        | 1.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 887       | 29.48%  |
| 8.01-16.0   | 584       | 19.41%  |
| 3.01-4.0    | 555       | 18.44%  |
| 16.01-24.0  | 526       | 17.48%  |
| 32.01-64.0  | 203       | 6.75%   |
| 1.01-2.0    | 121       | 4.02%   |
| 2.01-3.0    | 47        | 1.56%   |
| 64.01-256.0 | 35        | 1.16%   |
| 24.01-32.0  | 30        | 1%      |
| 0.51-1.0    | 19        | 0.63%   |
| 0.01-0.5    | 2         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1141      | 34.57%  |
| 2.01-3.0   | 829       | 25.11%  |
| 4.01-8.0   | 501       | 15.18%  |
| 3.01-4.0   | 445       | 13.48%  |
| 0.51-1.0   | 198       | 6%      |
| 8.01-16.0  | 126       | 3.82%   |
| 0.01-0.5   | 42        | 1.27%   |
| 16.01-24.0 | 11        | 0.33%   |
| 24.01-32.0 | 6         | 0.18%   |
| 32.01-64.0 | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2220      | 72.88%  |
| 2      | 673       | 22.09%  |
| 3      | 106       | 3.48%   |
| 0      | 29        | 0.95%   |
| 4      | 15        | 0.49%   |
| 5      | 2         | 0.07%   |
| 7      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1886      | 63.25%  |
| Yes       | 1096      | 36.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2383      | 80.18%  |
| No        | 589       | 19.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2902      | 97.94%  |
| No        | 61        | 2.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2242      | 74.66%  |
| No        | 761       | 25.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 2961      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Toronto         | 305       | 9.78%   |
| Montreal        | 291       | 9.33%   |
| Vancouver       | 127       | 4.07%   |
| Calgary         | 127       | 4.07%   |
| Edmonton        | 101       | 3.24%   |
| Ottawa          | 100       | 3.21%   |
| Québec         | 84        | 2.69%   |
| Winnipeg        | 67        | 2.15%   |
| Mississauga     | 57        | 1.83%   |
| Victoria        | 55        | 1.76%   |
| London          | 39        | 1.25%   |
| Surrey          | 38        | 1.22%   |
| Kitchener       | 36        | 1.15%   |
| Regina          | 34        | 1.09%   |
| Brampton        | 33        | 1.06%   |
| Laval           | 31        | 0.99%   |
| Burnaby         | 30        | 0.96%   |
| Halifax         | 28        | 0.9%    |
| Oshawa          | 25        | 0.8%    |
| Hamilton        | 25        | 0.8%    |
| Saskatoon       | 24        | 0.77%   |
| Markham         | 23        | 0.74%   |
| Sherbrooke      | 22        | 0.71%   |
| Scarborough     | 21        | 0.67%   |
| Moncton         | 20        | 0.64%   |
| Gatineau        | 19        | 0.61%   |
| Windsor         | 18        | 0.58%   |
| Levis           | 17        | 0.54%   |
| New Westminster | 16        | 0.51%   |
| Kingston        | 16        | 0.51%   |
| Richmond Hill   | 15        | 0.48%   |
| Kelowna         | 15        | 0.48%   |
| Barrie          | 15        | 0.48%   |
| Fredericton     | 14        | 0.45%   |
| Vernon          | 13        | 0.42%   |
| Dartmouth       | 13        | 0.42%   |
| Richmond        | 12        | 0.38%   |
| Longueuil       | 12        | 0.38%   |
| Guelph          | 12        | 0.38%   |
| Waterloo        | 11        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 564       | 772    | 15.37%  |
| WDC                         | 459       | 574    | 12.51%  |
| Seagate                     | 406       | 527    | 11.06%  |
| Toshiba                     | 281       | 346    | 7.66%   |
| Unknown                     | 244       | 327    | 6.65%   |
| SanDisk                     | 226       | 275    | 6.16%   |
| Kingston                    | 214       | 273    | 5.83%   |
| Intel                       | 149       | 215    | 4.06%   |
| SK hynix                    | 140       | 176    | 3.81%   |
| Hitachi                     | 120       | 137    | 3.27%   |
| HGST                        | 101       | 122    | 2.75%   |
| Crucial                     | 86        | 118    | 2.34%   |
| Micron Technology           | 82        | 105    | 2.23%   |
| A-DATA Technology           | 56        | 72     | 1.53%   |
| Apple                       | 54        | 62     | 1.47%   |
| Fujitsu                     | 39        | 57     | 1.06%   |
| KIOXIA                      | 37        | 43     | 1.01%   |
| SPCC                        | 27        | 41     | 0.74%   |
| LITEONIT                    | 22        | 26     | 0.6%    |
| Kingston Technology Company | 21        | 24     | 0.57%   |
| LITEON                      | 18        | 20     | 0.49%   |
| Unknown                     | 18        | 18     | 0.49%   |
| Phison Electronics          | 17        | 20     | 0.46%   |
| China                       | 17        | 18     | 0.46%   |
| PNY                         | 12        | 22     | 0.33%   |
| Phison                      | 11        | 12     | 0.3%    |
| Silicon Motion              | 10        | 10     | 0.27%   |
| Micron/Crucial Technology   | 9         | 10     | 0.25%   |
| Dogfish                     | 9         | 12     | 0.25%   |
| ASMT                        | 9         | 9      | 0.25%   |
| Patriot                     | 8         | 8      | 0.22%   |
| OCZ                         | 8         | 8      | 0.22%   |
| JMicron Technology          | 8         | 10     | 0.22%   |
| KingFast                    | 7         | 9      | 0.19%   |
| Team                        | 6         | 8      | 0.16%   |
| External                    | 6         | 8      | 0.16%   |
| Union Memory (Shenzhen)     | 5         | 6      | 0.14%   |
| UMIS                        | 5         | 5      | 0.14%   |
| TO Exter                    | 5         | 6      | 0.14%   |
| Timetec                     | 5         | 11     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 51        | 1.33%   |
| Toshiba MQ01ABD100 1TB                              | 47        | 1.23%   |
| Unknown MMC Card  64GB                              | 45        | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 43        | 1.12%   |
| Seagate ST1000LM035-1RK172 1TB                      | 40        | 1.05%   |
| Unknown MMC Card  32GB                              | 37        | 0.97%   |
| HGST HTS721010A9E630 1TB                            | 30        | 0.78%   |
| Samsung SSD 860 EVO 500GB                           | 26        | 0.68%   |
| Kingston SA400S37480G 480GB SSD                     | 25        | 0.65%   |
| Samsung SSD 860 EVO 1TB                             | 24        | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 23        | 0.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 22        | 0.58%   |
| Unknown MMC Card  16GB                              | 21        | 0.55%   |
| Seagate ST9500325AS 500GB                           | 21        | 0.55%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.55%   |
| Seagate ST1000LX015-1U7172 1TB                      | 20        | 0.52%   |
| Samsung NVMe SSD Drive 512GB                        | 20        | 0.52%   |
| Toshiba MQ04ABF100 1TB                              | 19        | 0.5%    |
| Intel NVMe SSD Drive 512GB                          | 19        | 0.5%    |
| HGST HTS725050A7E630 500GB                          | 19        | 0.5%    |
| WDC WD10SPZX-21Z10T0 1TB                            | 18        | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                     | 18        | 0.47%   |
| Unknown                                             | 18        | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 17        | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 17        | 0.44%   |
| Unknown MMC Card  128GB                             | 17        | 0.44%   |
| Seagate ST500LM021-1KJ152 500GB                     | 17        | 0.44%   |
| SanDisk NVMe SSD Drive 1TB                          | 17        | 0.44%   |
| Samsung SSD 850 EVO 250GB                           | 17        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 17        | 0.44%   |
| SK hynix NVMe SSD Drive 512GB                       | 16        | 0.42%   |
| Samsung SSD 860 EVO 250GB                           | 16        | 0.42%   |
| Intel SSD 660P Series 1TB                           | 16        | 0.42%   |
| HGST HTS541010A9E680 1TB                            | 16        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB                         | 16        | 0.42%   |
| Toshiba MQ01ABF050 500GB                            | 15        | 0.39%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 15        | 0.39%   |
| Samsung SSD 850 EVO 500GB                           | 15        | 0.39%   |
| Intel SSDPEKNU512GZ 512GB                           | 15        | 0.39%   |
| Seagate Expansion 2TB                               | 14        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 391       | 501    | 31.87%  |
| WDC                 | 296       | 356    | 24.12%  |
| Toshiba             | 219       | 277    | 17.85%  |
| Hitachi             | 120       | 137    | 9.78%   |
| HGST                | 101       | 122    | 8.23%   |
| Fujitsu             | 39        | 57     | 3.18%   |
| Samsung Electronics | 16        | 31     | 1.3%    |
| Apple               | 9         | 9      | 0.73%   |
| Unknown             | 8         | 9      | 0.65%   |
| External            | 6         | 8      | 0.49%   |
| TO Exter            | 5         | 6      | 0.41%   |
| SABRENT             | 4         | 4      | 0.33%   |
| Maxone              | 3         | 3      | 0.24%   |
| USB 3.0             | 1         | 2      | 0.08%   |
| StoreJet            | 1         | 1      | 0.08%   |
| SINTECHI            | 1         | 1      | 0.08%   |
| LaCie               | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 2      | 0.08%   |
| Inateck             | 1         | 1      | 0.08%   |
| Generic-            | 1         | 1      | 0.08%   |
| DAS                 | 1         | 5      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |
| ACASIS              | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 268       | 363    | 23.89%  |
| Kingston            | 179       | 223    | 15.95%  |
| SanDisk             | 98        | 117    | 8.73%   |
| Crucial             | 78        | 104    | 6.95%   |
| WDC                 | 76        | 108    | 6.77%   |
| Intel               | 49        | 67     | 4.37%   |
| A-DATA Technology   | 48        | 62     | 4.28%   |
| Micron Technology   | 33        | 50     | 2.94%   |
| Apple               | 33        | 34     | 2.94%   |
| SPCC                | 26        | 40     | 2.32%   |
| LITEONIT            | 22        | 26     | 1.96%   |
| SK hynix            | 21        | 28     | 1.87%   |
| Toshiba             | 20        | 23     | 1.78%   |
| China               | 17        | 18     | 1.52%   |
| LITEON              | 14        | 15     | 1.25%   |
| PNY                 | 12        | 22     | 1.07%   |
| Dogfish             | 9         | 12     | 0.8%    |
| Patriot             | 8         | 8      | 0.71%   |
| OCZ                 | 8         | 8      | 0.71%   |
| Seagate             | 7         | 10     | 0.62%   |
| ASMT                | 6         | 6      | 0.53%   |
| Team                | 5         | 7      | 0.45%   |
| Timetec             | 4         | 10     | 0.36%   |
| Mushkin             | 4         | 7      | 0.36%   |
| KingSpec            | 4         | 6      | 0.36%   |
| JMicron Technology  | 4         | 4      | 0.36%   |
| Transcend           | 3         | 4      | 0.27%   |
| Super Talent        | 3         | 5      | 0.27%   |
| OWC                 | 3         | 7      | 0.27%   |
| NGFF                | 3         | 3      | 0.27%   |
| KingFast            | 3         | 3      | 0.27%   |
| KingDian            | 3         | 3      | 0.27%   |
| Corsair             | 3         | 3      | 0.27%   |
| Unknown             | 3         | 3      | 0.27%   |
| Zheino              | 2         | 2      | 0.18%   |
| WDC WDS             | 2         | 2      | 0.18%   |
| Vaseky              | 2         | 2      | 0.18%   |
| Lexar               | 2         | 3      | 0.18%   |
| Kingchuxing         | 2         | 2      | 0.18%   |
| Hewlett-Packard     | 2         | 3      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1174      | 1536   | 33.92%  |
| SSD     | 1025      | 1467   | 29.62%  |
| NVMe    | 965       | 1317   | 27.88%  |
| MMC     | 249       | 335    | 7.19%   |
| Unknown | 48        | 57     | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1986      | 2839   | 59.2%   |
| NVMe | 964       | 1314   | 28.73%  |
| MMC  | 249       | 335    | 7.42%   |
| SAS  | 156       | 224    | 4.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1419      | 1943   | 64.85%  |
| 0.51-1.0   | 670       | 920    | 30.62%  |
| 1.01-2.0   | 72        | 100    | 3.29%   |
| 3.01-4.0   | 14        | 19     | 0.64%   |
| 4.01-10.0  | 13        | 21     | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 824       | 26.05%  |
| 251-500        | 822       | 25.99%  |
| 501-1000       | 528       | 16.69%  |
| 1-20           | 282       | 8.92%   |
| 51-100         | 210       | 6.64%   |
| 1001-2000      | 183       | 5.79%   |
| 21-50          | 117       | 3.7%    |
| Unknown        | 91        | 2.88%   |
| More than 3000 | 65        | 2.06%   |
| 2001-3000      | 41        | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1367      | 41.82%  |
| 21-50          | 606       | 18.54%  |
| 51-100         | 402       | 12.3%   |
| 101-250        | 394       | 12.05%  |
| 251-500        | 222       | 6.79%   |
| 501-1000       | 114       | 3.49%   |
| Unknown        | 91        | 2.78%   |
| 1001-2000      | 45        | 1.38%   |
| More than 3000 | 17        | 0.52%   |
| 2001-3000      | 11        | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 10        | 11     | 5.41%   |
| Toshiba MQ01ABD100 1TB              | 6         | 8      | 3.24%   |
| HGST HTS541010A9E680 1TB            | 6         | 6      | 3.24%   |
| Seagate ST9500325AS 500GB           | 5         | 5      | 2.7%    |
| HGST HTS545050A7E680 500GB          | 5         | 5      | 2.7%    |
| Seagate ST500LT012-9WS142 500GB     | 4         | 4      | 2.16%   |
| Seagate ST500LM000-1EJ162 500GB     | 4         | 4      | 2.16%   |
| HGST HTS721010A9E630 1TB            | 4         | 4      | 2.16%   |
| Toshiba MK3261GSYN 320GB            | 3         | 3      | 1.62%   |
| Seagate ST9500420AS 500GB           | 3         | 3      | 1.62%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 3      | 1.62%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 2         | 2      | 1.08%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 1.08%   |
| Toshiba MK6465GSX 640GB             | 2         | 2      | 1.08%   |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 1.08%   |
| Toshiba MK2035GSS 200GB             | 2         | 2      | 1.08%   |
| Seagate ST9750420AS 752GB           | 2         | 2      | 1.08%   |
| Seagate ST9500420ASG 500GB          | 2         | 2      | 1.08%   |
| Seagate ST9320423AS 320GB           | 2         | 4      | 1.08%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 1.08%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 1.08%   |
| Seagate ST320LT020-9YG142 320GB     | 2         | 2      | 1.08%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB | 2         | 2      | 1.08%   |
| Seagate ST1000LM014-1EJ164 1TB      | 2         | 2      | 1.08%   |
| Hitachi HTS725050A9A364 500GB       | 2         | 2      | 1.08%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 2      | 1.08%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 2      | 1.08%   |
| HGST HTS725050A7E630 500GB          | 2         | 3      | 1.08%   |
| A-DATA Technology SX900 256GB SSD   | 2         | 2      | 1.08%   |
| WDC WD7500BPKT-60PK4T0 752GB        | 1         | 1      | 0.54%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.54%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 1      | 0.54%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 0.54%   |
| WDC WD2500BEVT-75A23T0 250GB        | 1         | 1      | 0.54%   |
| WDC WD2500BEVT-00ZCT0 250GB         | 1         | 1      | 0.54%   |
| WDC WD2500BEVS-75UST0 250GB         | 1         | 1      | 0.54%   |
| WDC WD1600BEVS-22RST0 160GB         | 1         | 1      | 0.54%   |
| WDC WD10SPZX-16Z10T0 1TB            | 1         | 1      | 0.54%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 57     | 29.19%  |
| Toshiba             | 28        | 30     | 15.14%  |
| Hitachi             | 21        | 21     | 11.35%  |
| WDC                 | 19        | 22     | 10.27%  |
| HGST                | 19        | 20     | 10.27%  |
| Samsung Electronics | 9         | 19     | 4.86%   |
| Intel               | 7         | 7      | 3.78%   |
| A-DATA Technology   | 5         | 5      | 2.7%    |
| SK hynix            | 3         | 3      | 1.62%   |
| Kingston            | 3         | 3      | 1.62%   |
| SanDisk             | 2         | 2      | 1.08%   |
| Fujitsu             | 2         | 11     | 1.08%   |
| UMIS                | 1         | 1      | 0.54%   |
| Timetec             | 1         | 5      | 0.54%   |
| Super Talent        | 1         | 1      | 0.54%   |
| OCZ                 | 1         | 1      | 0.54%   |
| Micron Technology   | 1         | 1      | 0.54%   |
| LITEONIT            | 1         | 1      | 0.54%   |
| LITEON              | 1         | 1      | 0.54%   |
| LaCie               | 1         | 1      | 0.54%   |
| KingSpec            | 1         | 1      | 0.54%   |
| Crucial             | 1         | 1      | 0.54%   |
| Corsair             | 1         | 1      | 0.54%   |
| ASMT                | 1         | 1      | 0.54%   |
| Apple               | 1         | 1      | 0.54%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 57     | 37.76%  |
| Toshiba             | 26        | 28     | 18.18%  |
| Hitachi             | 21        | 21     | 14.69%  |
| HGST                | 19        | 20     | 13.29%  |
| WDC                 | 17        | 19     | 11.89%  |
| Samsung Electronics | 2         | 10     | 1.4%    |
| Fujitsu             | 2         | 11     | 1.4%    |
| LaCie               | 1         | 1      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 141       | 168    | 77.05%  |
| SSD  | 33        | 39     | 18.03%  |
| NVMe | 9         | 10     | 4.92%   |

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
| Detected | 1874      | 3001   | 59.76%  |
| Works    | 1078      | 1487   | 34.38%  |
| Malfunc  | 182       | 217    | 5.8%    |
| Failed   | 2         | 7      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1920      | 56.94%  |
| AMD                            | 434       | 12.87%  |
| Samsung Electronics            | 322       | 9.55%   |
| SanDisk                        | 203       | 6.02%   |
| SK hynix                       | 115       | 3.41%   |
| Kingston Technology Company    | 54        | 1.6%    |
| Micron Technology              | 50        | 1.48%   |
| Toshiba America Info Systems   | 43        | 1.28%   |
| Nvidia                         | 41        | 1.22%   |
| KIOXIA                         | 40        | 1.19%   |
| Phison Electronics             | 31        | 0.92%   |
| Micron/Crucial Technology      | 17        | 0.5%    |
| Silicon Motion                 | 13        | 0.39%   |
| ADATA Technology               | 13        | 0.39%   |
| Union Memory (Shenzhen)        | 12        | 0.36%   |
| Apple                          | 9         | 0.27%   |
| Marvell Technology Group       | 8         | 0.24%   |
| Lite-On Technology             | 8         | 0.24%   |
| Solid State Storage Technology | 6         | 0.18%   |
| Realtek Semiconductor          | 6         | 0.18%   |
| Lenovo                         | 4         | 0.12%   |
| ASMedia Technology             | 4         | 0.12%   |
| O2 Micro                       | 3         | 0.09%   |
| JMicron Technology             | 3         | 0.09%   |
| Solidigm                       | 2         | 0.06%   |
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
| AMD FCH SATA Controller [AHCI mode]                                              | 355       | 9.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 225       | 6.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 193       | 5.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 175       | 4.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 159       | 4.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 127       | 3.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 110       | 3.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 106       | 2.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 90        | 2.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 90        | 2.47%   |
| Intel Volume Management Device NVMe RAID Controller                              | 89        | 2.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 74        | 2.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 71        | 1.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 70        | 1.92%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 64        | 1.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 59        | 1.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 56        | 1.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 54        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 54        | 1.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 53        | 1.46%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 47        | 1.29%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 46        | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 40        | 1.1%    |
| Intel SSD 660P Series                                                            | 34        | 0.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 31        | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 30        | 0.82%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 28        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 26        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 26        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 25        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 24        | 0.66%   |
| Nvidia MCP79 AHCI Controller                                                     | 21        | 0.58%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 21        | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 20        | 0.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 19        | 0.52%   |
| SK hynix BC511 NVMe SSD                                                          | 19        | 0.52%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 19        | 0.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 19        | 0.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 19        | 0.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 18        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1974      | 57.04%  |
| NVMe | 964       | 27.85%  |
| RAID | 299       | 8.64%   |
| IDE  | 224       | 6.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 2333      | 78.79%  |
| AMD     | 623       | 21.04%  |
| ARM     | 3         | 0.1%    |
| Unknown | 2         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 50        | 1.69%   |
| AMD Custom APU 0405                           | 50        | 1.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 49        | 1.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 46        | 1.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 45        | 1.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 38        | 1.28%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 1.21%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 35        | 1.18%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 34        | 1.15%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 32        | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 30        | 1.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 29        | 0.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 28        | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 28        | 0.94%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 27        | 0.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 24        | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 23        | 0.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 0.78%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 22        | 0.74%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 22        | 0.74%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 21        | 0.71%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 20        | 0.67%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 19        | 0.64%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 0.57%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 17        | 0.57%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 16        | 0.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 16        | 0.54%   |
| Intel 12th Gen Core i7-12700H                 | 16        | 0.54%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 16        | 0.54%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 15        | 0.51%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 15        | 0.51%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 15        | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.47%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 14        | 0.47%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 14        | 0.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 14        | 0.47%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 14        | 0.47%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 14        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 719       | 24.27%  |
| Intel Core i7           | 688       | 23.22%  |
| Other                   | 302       | 10.19%  |
| Intel Core i3           | 165       | 5.57%   |
| Intel Core 2 Duo        | 160       | 5.4%    |
| Intel Celeron           | 120       | 4.05%   |
| AMD Ryzen 7             | 113       | 3.81%   |
| AMD Ryzen 5             | 77        | 2.6%    |
| Intel Pentium           | 63        | 2.13%   |
| AMD A6                  | 58        | 1.96%   |
| Intel Atom              | 47        | 1.59%   |
| AMD A10                 | 42        | 1.42%   |
| Intel Pentium Dual-Core | 30        | 1.01%   |
| AMD A4                  | 29        | 0.98%   |
| Intel Pentium Dual      | 25        | 0.84%   |
| AMD Ryzen 9             | 23        | 0.78%   |
| AMD Ryzen 3             | 23        | 0.78%   |
| AMD A8                  | 22        | 0.74%   |
| Intel Genuine           | 21        | 0.71%   |
| Intel Core i9           | 16        | 0.54%   |
| Intel Core 2            | 15        | 0.51%   |
| AMD E                   | 15        | 0.51%   |
| AMD E2                  | 13        | 0.44%   |
| AMD E1                  | 13        | 0.44%   |
| AMD A12                 | 13        | 0.44%   |
| Intel Pentium Silver    | 10        | 0.34%   |
| AMD Turion 64 X2 Mobile | 10        | 0.34%   |
| AMD Ryzen 5 PRO         | 10        | 0.34%   |
| AMD Athlon X2           | 10        | 0.34%   |
| Intel Xeon              | 8         | 0.27%   |
| AMD Ryzen 7 PRO         | 8         | 0.27%   |
| AMD Athlon              | 8         | 0.27%   |
| AMD Athlon 64 X2        | 7         | 0.24%   |
| AMD Phenom II           | 6         | 0.2%    |
| Intel Celeron M         | 5         | 0.17%   |
| AMD Turion 64 Mobile    | 5         | 0.17%   |
| AMD C-50                | 5         | 0.17%   |
| AMD Athlon II           | 5         | 0.17%   |
| Intel Pentium M         | 4         | 0.13%   |
| Intel Core m3           | 3         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1505      | 50.76%  |
| 4       | 904       | 30.49%  |
| 6       | 199       | 6.71%   |
| 8       | 180       | 6.07%   |
| 1       | 70        | 2.36%   |
| 14      | 43        | 1.45%   |
| 10      | 28        | 0.94%   |
| 12      | 22        | 0.74%   |
| 16      | 7         | 0.24%   |
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
| 1       | 2960      | 99.97%  |
| Unknown | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2162      | 72.89%  |
| 1       | 802       | 27.04%  |
| 12      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2893      | 97.51%  |
| 32-bit         | 39        | 1.31%   |
| Unknown        | 33        | 1.11%   |
| 64-bit         | 2         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1007      | 32.65%  |
| 0x306a9    | 166       | 5.38%   |
| 0x206a7    | 162       | 5.25%   |
| 0x40651    | 88        | 2.85%   |
| 0x1067a    | 88        | 2.85%   |
| 0x806ea    | 77        | 2.5%    |
| 0x906ea    | 76        | 2.46%   |
| 0x20655    | 71        | 2.3%    |
| 0x406e3    | 63        | 2.04%   |
| 0x806e9    | 61        | 1.98%   |
| 0x306c3    | 60        | 1.95%   |
| 0x806ec    | 56        | 1.82%   |
| 0x306d4    | 54        | 1.75%   |
| 0x6fd      | 49        | 1.59%   |
| 0xa0652    | 48        | 1.56%   |
| 0x20652    | 42        | 1.36%   |
| 0x806c1    | 39        | 1.26%   |
| 0x906e9    | 36        | 1.17%   |
| 0x906a3    | 36        | 1.17%   |
| 0x0a50000c | 34        | 1.1%    |
| 0x06001119 | 33        | 1.07%   |
| 0x506e3    | 29        | 0.94%   |
| 0x30678    | 29        | 0.94%   |
| 0x06006705 | 27        | 0.88%   |
| 0x706e5    | 25        | 0.81%   |
| 0x10676    | 25        | 0.81%   |
| 0x08108102 | 25        | 0.81%   |
| 0x406c4    | 23        | 0.75%   |
| 0x08108109 | 22        | 0.71%   |
| 0x406c3    | 21        | 0.68%   |
| 0x05000119 | 21        | 0.68%   |
| 0x07030105 | 19        | 0.62%   |
| 0x08600104 | 18        | 0.58%   |
| 0x03000027 | 18        | 0.58%   |
| 0x106e5    | 17        | 0.55%   |
| 0x806eb    | 16        | 0.52%   |
| 0x010000c8 | 16        | 0.52%   |
| 0x806d1    | 15        | 0.49%   |
| 0x08608103 | 15        | 0.49%   |
| 0x706a8    | 14        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 483       | 16.28%  |
| IvyBridge        | 229       | 7.72%   |
| Haswell          | 225       | 7.58%   |
| SandyBridge      | 212       | 7.15%   |
| Unknown          | 173       | 5.83%   |
| Penryn           | 148       | 4.99%   |
| Westmere         | 147       | 4.95%   |
| Skylake          | 132       | 4.45%   |
| Silvermont       | 101       | 3.4%    |
| Core             | 96        | 3.24%   |
| Broadwell        | 86        | 2.9%    |
| Excavator        | 85        | 2.86%   |
| TigerLake        | 79        | 2.66%   |
| CometLake        | 79        | 2.66%   |
| Alderlake Hybrid | 72        | 2.43%   |
| Zen+             | 68        | 2.29%   |
| Zen 3            | 60        | 2.02%   |
| Zen 2            | 59        | 1.99%   |
| Icelake          | 54        | 1.82%   |
| Piledriver       | 43        | 1.45%   |
| Goldmont plus    | 41        | 1.38%   |
| Bobcat           | 34        | 1.15%   |
| Puma             | 33        | 1.11%   |
| K8 Hammer        | 28        | 0.94%   |
| P6               | 26        | 0.88%   |
| Zen              | 24        | 0.81%   |
| K10 Llano        | 24        | 0.81%   |
| Nehalem          | 23        | 0.78%   |
| K10              | 23        | 0.78%   |
| Bonnell          | 23        | 0.78%   |
| Jaguar           | 19        | 0.64%   |
| Goldmont         | 16        | 0.54%   |
| K8 & K10 hybrid  | 13        | 0.44%   |
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
| Intel  | 2096      | 58.09%  |
| Nvidia | 768       | 21.29%  |
| AMD    | 744       | 20.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 202       | 5.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 190       | 5.08%   |
| Intel UHD Graphics 620                                                                   | 125       | 3.34%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 120       | 3.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 120       | 3.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 106       | 2.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 102       | 2.73%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 86        | 2.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 82        | 2.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 75        | 2%      |
| Intel HD Graphics 620                                                                    | 75        | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 74        | 1.98%   |
| Intel HD Graphics 5500                                                                   | 72        | 1.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 67        | 1.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 66        | 1.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 62        | 1.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 54        | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 54        | 1.44%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 53        | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 50        | 1.34%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 50        | 1.34%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 48        | 1.28%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 43        | 1.15%   |
| Intel HD Graphics 630                                                                    | 39        | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 39        | 1.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 38        | 1.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 38        | 1.02%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 37        | 0.99%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 35        | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 0.91%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 33        | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 33        | 0.88%   |
| Intel HD Graphics 530                                                                    | 29        | 0.78%   |
| AMD Lucienne                                                                             | 26        | 0.7%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 23        | 0.61%   |
| AMD Rembrandt [Radeon 680M]                                                              | 23        | 0.61%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 22        | 0.59%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 22        | 0.59%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 22        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1503      | 50.52%  |
| 1 x AMD            | 575       | 19.33%  |
| Intel + Nvidia     | 511       | 17.18%  |
| 1 x Nvidia         | 188       | 6.32%   |
| Intel + AMD        | 67        | 2.25%   |
| AMD + Nvidia       | 65        | 2.18%   |
| 2 x AMD            | 39        | 1.31%   |
| Other              | 11        | 0.37%   |
| 2 x Intel          | 10        | 0.34%   |
| 2 x Nvidia         | 5         | 0.17%   |
| Intel + 2 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2530      | 84.17%  |
| Proprietary | 385       | 12.81%  |
| Unknown     | 91        | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2035      | 66.74%  |
| 0.01-0.5   | 405       | 13.28%  |
| 1.01-2.0   | 240       | 7.87%   |
| 0.51-1.0   | 134       | 4.39%   |
| 3.01-4.0   | 130       | 4.26%   |
| 7.01-8.0   | 46        | 1.51%   |
| 5.01-6.0   | 43        | 1.41%   |
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
| AU Optronics            | 635       | 18.7%   |
| LG Display              | 452       | 13.31%  |
| Samsung Electronics     | 398       | 11.72%  |
| Chimei Innolux          | 359       | 10.57%  |
| BOE                     | 332       | 9.78%   |
| Sharp                   | 144       | 4.24%   |
| Apple                   | 125       | 3.68%   |
| Lenovo                  | 101       | 2.97%   |
| Dell                    | 96        | 2.83%   |
| Goldstar                | 84        | 2.47%   |
| Chi Mei Optoelectronics | 83        | 2.44%   |
| PANDA                   | 51        | 1.5%    |
| Hewlett-Packard         | 48        | 1.41%   |
| Acer                    | 45        | 1.33%   |
| ASUSTek Computer        | 35        | 1.03%   |
| Valve                   | 34        | 1%      |
| LG Philips              | 33        | 0.97%   |
| BenQ                    | 32        | 0.94%   |
| Ancor Communications    | 28        | 0.82%   |
| Toshiba                 | 26        | 0.77%   |
| InfoVision              | 24        | 0.71%   |
| ViewSonic               | 18        | 0.53%   |
| Sony                    | 18        | 0.53%   |
| CSO                     | 14        | 0.41%   |
| Panasonic               | 12        | 0.35%   |
| Philips                 | 11        | 0.32%   |
| AOC                     | 11        | 0.32%   |
| TMX                     | 10        | 0.29%   |
| Quanta Display          | 9         | 0.27%   |
| HannStar                | 9         | 0.27%   |
| HKC                     | 7         | 0.21%   |
| CPT                     | 7         | 0.21%   |
| Seiko/Epson             | 6         | 0.18%   |
| Insignia                | 6         | 0.18%   |
| LGD                     | 5         | 0.15%   |
| IBM                     | 5         | 0.15%   |
| MSI                     | 4         | 0.12%   |
| Gigabyte Technology     | 4         | 0.12%   |
| Unknown                 | 3         | 0.09%   |
| SANYO                   | 3         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 35        | 1.02%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 32        | 0.93%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 32        | 0.93%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.64%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 21        | 0.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 0.58%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 20        | 0.58%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 19        | 0.55%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 17        | 0.49%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 17        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 17        | 0.49%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 15        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 15        | 0.44%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 14        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 14        | 0.41%   |
| Toshiba TV TSB0206 1920x1080 890x500mm 40.2-inch                         | 13        | 0.38%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 13        | 0.38%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 13        | 0.38%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 12        | 0.35%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 12        | 0.35%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 12        | 0.35%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 11        | 0.32%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 11        | 0.32%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 11        | 0.32%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 11        | 0.32%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 10        | 0.29%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 10        | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.29%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 10        | 0.29%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 10        | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 0.29%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 10        | 0.29%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 9         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 9         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 9         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1161      | 36.17%  |
| 1366x768 (WXGA)    | 943       | 29.38%  |
| 1600x900 (HD+)     | 183       | 5.7%    |
| 1280x800 (WXGA)    | 166       | 5.17%   |
| 3840x2160 (4K)     | 139       | 4.33%   |
| 2560x1440 (QHD)    | 90        | 2.8%    |
| 1920x1200 (WUXGA)  | 76        | 2.37%   |
| 1440x900 (WXGA+)   | 74        | 2.31%   |
| 1680x1050 (WSXGA+) | 64        | 1.99%   |
| 2880x1800          | 38        | 1.18%   |
| 800x1280           | 36        | 1.12%   |
| 2560x1600          | 32        | 1%      |
| 3440x1440          | 19        | 0.59%   |
| 1280x1024 (SXGA)   | 18        | 0.56%   |
| 3200x1800 (QHD+)   | 17        | 0.53%   |
| 3840x2400          | 16        | 0.5%    |
| 2560x1080          | 16        | 0.5%    |
| 1024x600           | 15        | 0.47%   |
| 1024x768 (XGA)     | 12        | 0.37%   |
| 2256x1504          | 10        | 0.31%   |
| 1920x540           | 10        | 0.31%   |
| 1360x768           | 10        | 0.31%   |
| 3200x2000          | 8         | 0.25%   |
| Unknown            | 7         | 0.22%   |
| 3456x2160          | 5         | 0.16%   |
| 1920x1280          | 4         | 0.12%   |
| 1680x945           | 4         | 0.12%   |
| 3840x1080          | 3         | 0.09%   |
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
| 15      | 1402      | 41.32%  |
| 13      | 446       | 13.14%  |
| 14      | 389       | 11.46%  |
| 17      | 234       | 6.9%    |
| 27      | 113       | 3.33%   |
| 24      | 100       | 2.95%   |
| 23      | 76        | 2.24%   |
| 21      | 75        | 2.21%   |
| 11      | 64        | 1.89%   |
| 12      | 59        | 1.74%   |
| Unknown | 54        | 1.59%   |
| 31      | 39        | 1.15%   |
| 34      | 35        | 1.03%   |
| 16      | 35        | 1.03%   |
| 7       | 34        | 1%      |
| 22      | 31        | 0.91%   |
| 18      | 27        | 0.8%    |
| 20      | 22        | 0.65%   |
| 19      | 21        | 0.62%   |
| 10      | 16        | 0.47%   |
| 84      | 15        | 0.44%   |
| 72      | 14        | 0.41%   |
| 74      | 13        | 0.38%   |
| 54      | 11        | 0.32%   |
| 32      | 10        | 0.29%   |
| 25      | 8         | 0.24%   |
| 40      | 7         | 0.21%   |
| 86      | 5         | 0.15%   |
| 48      | 5         | 0.15%   |
| 37      | 5         | 0.15%   |
| 43      | 3         | 0.09%   |
| 42      | 3         | 0.09%   |
| 28      | 3         | 0.09%   |
| 26      | 3         | 0.09%   |
| 8       | 3         | 0.09%   |
| 39      | 2         | 0.06%   |
| 3       | 2         | 0.06%   |
| 85      | 1         | 0.03%   |
| 69      | 1         | 0.03%   |
| 60      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1966      | 58.49%  |
| 201-300     | 375       | 11.16%  |
| 351-400     | 305       | 9.07%   |
| 501-600     | 269       | 8%      |
| 401-500     | 165       | 4.91%   |
| 601-700     | 54        | 1.61%   |
| Unknown     | 54        | 1.61%   |
| 701-800     | 45        | 1.34%   |
| 1501-2000   | 43        | 1.28%   |
| 1-100       | 36        | 1.07%   |
| 1001-1500   | 27        | 0.8%    |
| 801-900     | 14        | 0.42%   |
| 901-1000    | 5         | 0.15%   |
| 101-200     | 3         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2317      | 77.65%  |
| 16/10   | 479       | 16.05%  |
| 21/9    | 35        | 1.17%   |
| 3/2     | 34        | 1.14%   |
| 0.67    | 32        | 1.07%   |
| Unknown | 30        | 1.01%   |
| 5/4     | 19        | 0.64%   |
| 4/3     | 16        | 0.54%   |
| 0.56    | 5         | 0.17%   |
| 6/5     | 4         | 0.13%   |
| 32/9    | 3         | 0.1%    |
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
| 101-110        | 1383      | 40.97%  |
| 81-90          | 657       | 19.46%  |
| 201-250        | 225       | 6.66%   |
| 121-130        | 195       | 5.78%   |
| 71-80          | 162       | 4.8%    |
| 301-350        | 114       | 3.38%   |
| 351-500        | 85        | 2.52%   |
| 151-200        | 68        | 2.01%   |
| 51-60          | 66        | 1.95%   |
| More than 1000 | 64        | 1.9%    |
| 61-70          | 56        | 1.66%   |
| Unknown        | 54        | 1.6%    |
| 111-120        | 48        | 1.42%   |
| 1-40           | 39        | 1.16%   |
| 131-140        | 36        | 1.07%   |
| 141-150        | 33        | 0.98%   |
| 251-300        | 32        | 0.95%   |
| 501-1000       | 26        | 0.77%   |
| 91-100         | 17        | 0.5%    |
| 41-50          | 16        | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1150      | 34.86%  |
| 101-120       | 1065      | 32.28%  |
| 51-100        | 593       | 17.98%  |
| 161-240       | 243       | 7.37%   |
| More than 240 | 129       | 3.91%   |
| 1-50          | 65        | 1.97%   |
| Unknown       | 54        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2367      | 78.04%  |
| 2     | 500       | 16.49%  |
| 0     | 88        | 2.9%    |
| 3     | 76        | 2.51%   |
| 4     | 2         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1614      | 35.14%  |
| Realtek Semiconductor           | 1351      | 29.41%  |
| Qualcomm Atheros                | 648       | 14.11%  |
| Broadcom                        | 361       | 7.86%   |
| Broadcom Limited                | 120       | 2.61%   |
| MediaTek                        | 75        | 1.63%   |
| Marvell Technology Group        | 51        | 1.11%   |
| ASIX Electronics                | 49        | 1.07%   |
| TP-Link                         | 34        | 0.74%   |
| Nvidia                          | 34        | 0.74%   |
| Ralink                          | 27        | 0.59%   |
| Ralink Technology               | 21        | 0.46%   |
| Linksys                         | 19        | 0.41%   |
| DisplayLink                     | 18        | 0.39%   |
| D-Link                          | 18        | 0.39%   |
| Samsung Electronics             | 16        | 0.35%   |
| Lenovo                          | 15        | 0.33%   |
| Qualcomm                        | 14        | 0.3%    |
| Sierra Wireless                 | 12        | 0.26%   |
| ASUSTek Computer                | 12        | 0.26%   |
| Qualcomm Atheros Communications | 11        | 0.24%   |
| NetGear                         | 7         | 0.15%   |
| Google                          | 7         | 0.15%   |
| AMD                             | 6         | 0.13%   |
| Hewlett-Packard                 | 4         | 0.09%   |
| Dell                            | 4         | 0.09%   |
| D-Link System                   | 4         | 0.09%   |
| Apple                           | 4         | 0.09%   |
| Research In Motion              | 3         | 0.07%   |
| JMicron Technology              | 3         | 0.07%   |
| Xiaomi                          | 2         | 0.04%   |
| U-Blox                          | 2         | 0.04%   |
| TRENDnet                        | 2         | 0.04%   |
| Microsoft                       | 2         | 0.04%   |
| LG Electronics                  | 2         | 0.04%   |
| Edimax Technology               | 2         | 0.04%   |
| Aquantia                        | 2         | 0.04%   |
| STMicroelectronics              | 1         | 0.02%   |
| SEGGER                          | 1         | 0.02%   |
| Qualcomm Technologies           | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 727       | 12.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 266       | 4.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 173       | 3.05%   |
| Intel Wireless 8265 / 8275                                        | 137       | 2.42%   |
| Intel Wireless 7260                                               | 120       | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 119       | 2.1%    |
| Intel Wi-Fi 6 AX200                                               | 116       | 2.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 108       | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 99        | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 98        | 1.73%   |
| Intel Wireless 7265                                               | 93        | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 86        | 1.52%   |
| Intel Wireless 8260                                               | 83        | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 81        | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 71        | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 66        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 64        | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 59        | 1.04%   |
| Intel Wi-Fi 6 AX201                                               | 58        | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 57        | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 56        | 0.99%   |
| Intel Centrino Ultimate-N 6300                                    | 55        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 50        | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 48        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 46        | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 46        | 0.81%   |
| Intel Ethernet Connection I217-LM                                 | 44        | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 40        | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 39        | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 38        | 0.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 37        | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 37        | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 36        | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 36        | 0.63%   |
| Intel Wireless 3165                                               | 35        | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 33        | 0.58%   |
| Intel Centrino Advanced-N 6235                                    | 33        | 0.58%   |
| Intel Centrino Advanced-N 6200                                    | 33        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 32        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1531      | 49.51%  |
| Qualcomm Atheros                      | 530       | 17.14%  |
| Realtek Semiconductor                 | 419       | 13.55%  |
| Broadcom                              | 283       | 9.15%   |
| Broadcom Limited                      | 77        | 2.49%   |
| MediaTek                              | 70        | 2.26%   |
| TP-Link                               | 31        | 1%      |
| Ralink                                | 27        | 0.87%   |
| Ralink Technology                     | 21        | 0.68%   |
| Linksys                               | 17        | 0.55%   |
| D-Link                                | 17        | 0.55%   |
| Sierra Wireless                       | 12        | 0.39%   |
| Qualcomm                              | 12        | 0.39%   |
| ASUSTek Computer                      | 12        | 0.39%   |
| Qualcomm Atheros Communications       | 11        | 0.36%   |
| NetGear                               | 7         | 0.23%   |
| D-Link System                         | 4         | 0.13%   |
| TRENDnet                              | 2         | 0.06%   |
| Edimax Technology                     | 2         | 0.06%   |
| Dell                                  | 2         | 0.06%   |
| Qualcomm Technologies                 | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Microsoft                             | 1         | 0.03%   |
| Marvell Technology Group              | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 137       | 4.39%   |
| Intel Wireless 7260                                                     | 120       | 3.85%   |
| Intel Wi-Fi 6 AX200                                                     | 116       | 3.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 108       | 3.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 99        | 3.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 98        | 3.14%   |
| Intel Wireless 7265                                                     | 93        | 2.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 86        | 2.76%   |
| Intel Wireless 8260                                                     | 83        | 2.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 81        | 2.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 71        | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 66        | 2.12%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 64        | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 59        | 1.89%   |
| Intel Wi-Fi 6 AX201                                                     | 58        | 1.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 56        | 1.8%    |
| Intel Centrino Ultimate-N 6300                                          | 55        | 1.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 50        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 46        | 1.48%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 40        | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 39        | 1.25%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 37        | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 36        | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 36        | 1.15%   |
| Intel Wireless 3165                                                     | 35        | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 33        | 1.06%   |
| Intel Centrino Advanced-N 6235                                          | 33        | 1.06%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 32        | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 32        | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 31        | 0.99%   |
| Intel Centrino Wireless-N 2230                                          | 31        | 0.99%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 31        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 29        | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 29        | 0.93%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 28        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 27        | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 27        | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 1154      | 46.59%  |
| Intel                    | 697       | 28.14%  |
| Qualcomm Atheros         | 198       | 7.99%   |
| Broadcom                 | 162       | 6.54%   |
| Marvell Technology Group | 50        | 2.02%   |
| ASIX Electronics         | 49        | 1.98%   |
| Broadcom Limited         | 48        | 1.94%   |
| Nvidia                   | 33        | 1.33%   |
| DisplayLink              | 18        | 0.73%   |
| Lenovo                   | 14        | 0.57%   |
| Samsung Electronics      | 9         | 0.36%   |
| Google                   | 7         | 0.28%   |
| TP-Link                  | 4         | 0.16%   |
| MediaTek                 | 4         | 0.16%   |
| Hewlett-Packard          | 4         | 0.16%   |
| Apple                    | 4         | 0.16%   |
| Research In Motion       | 3         | 0.12%   |
| JMicron Technology       | 3         | 0.12%   |
| Xiaomi                   | 2         | 0.08%   |
| Qualcomm                 | 2         | 0.08%   |
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


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 727       | 28.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 266       | 10.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 173       | 6.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 119       | 4.74%   |
| Intel 82577LM Gigabit Network Connection                          | 57        | 2.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 2.11%   |
| Intel Ethernet Connection I218-LM                                 | 48        | 1.91%   |
| ASIX AX88179 Gigabit Ethernet                                     | 46        | 1.83%   |
| Intel Ethernet Connection I217-LM                                 | 44        | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 38        | 1.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 37        | 1.47%   |
| Intel Ethernet Connection (4) I219-V                              | 32        | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 1.19%   |
| Intel 82567LM Gigabit Network Connection                          | 30        | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                             | 28        | 1.11%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.92%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23        | 0.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 20        | 0.8%    |
| Nvidia MCP79 Ethernet                                             | 20        | 0.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19        | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 18        | 0.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 18        | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 17        | 0.68%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 17        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16        | 0.64%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 16        | 0.64%   |
| Intel Ethernet Connection I219-V                                  | 16        | 0.64%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 15        | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.6%    |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 14        | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 13        | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 13        | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.48%   |
| Intel Ethernet Connection (6) I219-LM                             | 12        | 0.48%   |
| Realtek Killer E3000 2.5GbE Controller                            | 11        | 0.44%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 11        | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 10        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2902      | 54.52%  |
| Ethernet | 2379      | 44.69%  |
| Modem    | 36        | 0.68%   |
| Unknown  | 6         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2443      | 76.94%  |
| Ethernet | 732       | 23.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2173      | 73.26%  |
| 1     | 725       | 24.44%  |
| 0     | 43        | 1.45%   |
| 3     | 25        | 0.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2493      | 82.85%  |
| Yes  | 516       | 17.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1101      | 48.27%  |
| Broadcom                        | 171       | 7.5%    |
| Realtek Semiconductor           | 168       | 7.37%   |
| Qualcomm Atheros Communications | 160       | 7.01%   |
| IMC Networks                    | 156       | 6.84%   |
| Lite-On Technology              | 120       | 5.26%   |
| Apple                           | 112       | 4.91%   |
| Foxconn / Hon Hai               | 101       | 4.43%   |
| Dell                            | 41        | 1.8%    |
| Hewlett-Packard                 | 35        | 1.53%   |
| Cambridge Silicon Radio         | 32        | 1.4%    |
| Toshiba                         | 15        | 0.66%   |
| Ralink                          | 15        | 0.66%   |
| ASUSTek Computer                | 15        | 0.66%   |
| Alps Electric                   | 9         | 0.39%   |
| USI                             | 4         | 0.18%   |
| Realtek                         | 4         | 0.18%   |
| MediaTek                        | 3         | 0.13%   |
| TP-Link                         | 2         | 0.09%   |
| Taiyo Yuden                     | 2         | 0.09%   |
| SINO WEALTH                     | 2         | 0.09%   |
| Logitech                        | 2         | 0.09%   |
| Dynex                           | 2         | 0.09%   |
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
| Intel Bluetooth wireless interface                                                  | 470       | 20.54%  |
| Intel Bluetooth Device                                                              | 252       | 11.01%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 125       | 5.46%   |
| Realtek Bluetooth Radio                                                             | 118       | 5.16%   |
| Intel AX200 Bluetooth                                                               | 113       | 4.94%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 85        | 3.72%   |
| Apple Bluetooth Host Controller                                                     | 70        | 3.06%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 60        | 2.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 55        | 2.4%    |
| IMC Networks 802.11ac WLAN Adapter                                                  | 48        | 2.1%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 45        | 1.97%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 37        | 1.62%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 35        | 1.53%   |
| IMC Networks Bluetooth Radio                                                        | 34        | 1.49%   |
| IMC Networks Wireless_Device                                                        | 32        | 1.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 32        | 1.4%    |
| Apple Bluetooth USB Host Controller                                                 | 32        | 1.4%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 30        | 1.31%   |
| Intel AX210 Bluetooth                                                               | 27        | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 25        | 1.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 25        | 1.09%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 24        | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 21        | 0.92%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 19        | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 18        | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 18        | 0.79%   |
| Broadcom HP Portable SoftSailing                                                    | 18        | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 16        | 0.7%    |
| Ralink RT3290 Bluetooth                                                             | 15        | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 15        | 0.66%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 15        | 0.66%   |
| IMC Networks Bluetooth Device                                                       | 14        | 0.61%   |
| Dell DW375 Bluetooth Module                                                         | 14        | 0.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 14        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 12        | 0.52%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.52%   |
| IMC Networks BCM20702A0                                                             | 11        | 0.48%   |
| Lite-On Bluetooth Device                                                            | 10        | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 9         | 0.39%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 9         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2277      | 61.71%  |
| AMD                                  | 690       | 18.7%   |
| Nvidia                               | 465       | 12.6%   |
| C-Media Electronics                  | 28        | 0.76%   |
| Realtek Semiconductor                | 25        | 0.68%   |
| Logitech                             | 25        | 0.68%   |
| GN Netcom                            | 16        | 0.43%   |
| Lenovo                               | 13        | 0.35%   |
| Plantronics                          | 11        | 0.3%    |
| JMTek                                | 8         | 0.22%   |
| Hewlett-Packard                      | 7         | 0.19%   |
| Apple                                | 7         | 0.19%   |
| SteelSeries ApS                      | 6         | 0.16%   |
| Razer USA                            | 6         | 0.16%   |
| Kingston Technology                  | 6         | 0.16%   |
| Focusrite-Novation                   | 6         | 0.16%   |
| Blue Microphones                     | 6         | 0.16%   |
| ASUSTek Computer                     | 6         | 0.16%   |
| Creative Technology                  | 5         | 0.14%   |
| Texas Instruments                    | 4         | 0.11%   |
| Sony                                 | 4         | 0.11%   |
| No brand                             | 4         | 0.11%   |
| Generalplus Technology               | 4         | 0.11%   |
| Corsair                              | 4         | 0.11%   |
| Sennheiser Communications            | 3         | 0.08%   |
| Dell                                 | 3         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.05%   |
| Synaptics                            | 2         | 0.05%   |
| Samson Technologies                  | 2         | 0.05%   |
| Panasonic (Matsushita)               | 2         | 0.05%   |
| Native Instruments                   | 2         | 0.05%   |
| GYROCOM C&C                          | 2         | 0.05%   |
| DSEA A/S                             | 2         | 0.05%   |
| DCMT Technology                      | 2         | 0.05%   |
| BR23                                 | 2         | 0.05%   |
| Audio-Technica                       | 2         | 0.05%   |
| XMOS                                 | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |
| Shure                                | 1         | 0.03%   |
| SAVITECH                             | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 300       | 6.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 261       | 5.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 256       | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 183       | 4.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 169       | 3.77%   |
| AMD FCH Azalia Controller                                                                         | 134       | 2.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 127       | 2.83%   |
| Intel 8 Series HD Audio Controller                                                                | 125       | 2.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 124       | 2.77%   |
| Intel Cannon Lake PCH cAVS                                                                        | 122       | 2.72%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 119       | 2.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 101       | 2.25%   |
| AMD Kabini HDMI/DP Audio                                                                          | 87        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 86        | 1.92%   |
| Intel Broadwell-U Audio Controller                                                                | 86        | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 83        | 1.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 83        | 1.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 82        | 1.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 79        | 1.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 74        | 1.65%   |
| Intel Comet Lake PCH cAVS                                                                         | 70        | 1.56%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 70        | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 68        | 1.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 67        | 1.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 63        | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 56        | 1.25%   |
| AMD High Definition Audio Controller                                                              | 50        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 48        | 1.07%   |
| Nvidia Audio device                                                                               | 44        | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 44        | 0.98%   |
| Intel CM238 HD Audio Controller                                                                   | 44        | 0.98%   |
| AMD Trinity HDMI Audio Controller                                                                 | 43        | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 42        | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 41        | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 41        | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 39        | 0.87%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 38        | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 36        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 35        | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 35        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 516       | 27.56%  |
| SK hynix                                         | 458       | 24.47%  |
| Micron Technology                                | 249       | 13.3%   |
| Kingston                                         | 145       | 7.75%   |
| Unknown                                          | 132       | 7.05%   |
| Crucial                                          | 77        | 4.11%   |
| G.Skill                                          | 39        | 2.08%   |
| Elpida                                           | 39        | 2.08%   |
| Nanya Technology                                 | 33        | 1.76%   |
| Ramaxel Technology                               | 31        | 1.66%   |
| A-DATA Technology                                | 27        | 1.44%   |
| Corsair                                          | 25        | 1.34%   |
| Unknown                                          | 14        | 0.75%   |
| Timetec                                          | 8         | 0.43%   |
| Patriot                                          | 8         | 0.43%   |
| Goldkey                                          | 6         | 0.32%   |
| ff                                               | 6         | 0.32%   |
| 4ea5                                             | 6         | 0.32%   |
| Unknown (ABCD)                                   | 5         | 0.27%   |
| Toshiba                                          | 5         | 0.27%   |
| Team                                             | 4         | 0.21%   |
| PNY                                              | 3         | 0.16%   |
| Neo Forza                                        | 3         | 0.16%   |
| ASint Technology                                 | 3         | 0.16%   |
| Unknown (7F7F7F94FFFFFFFF)                       | 2         | 0.11%   |
| SHARETRONIC                                      | 2         | 0.11%   |
| fef5                                             | 2         | 0.11%   |
| CSX                                              | 2         | 0.11%   |
| Axiom                                            | 2         | 0.11%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.05%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.05%   |
| Unknown (0x48594D503132355336344350382D53362020) | 1         | 0.05%   |
| Unknown (0x0C26)                                 | 1         | 0.05%   |
| Unknown (0x0080)                                 | 1         | 0.05%   |
| Unknown (08AE)                                   | 1         | 0.05%   |
| Unknown (000080B30080)                           | 1         | 0.05%   |
| Unifosa                                          | 1         | 0.05%   |
| Transcend                                        | 1         | 0.05%   |
| Sesame                                           | 1         | 0.05%   |
| Qumo                                             | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 35        | 1.77%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 22        | 1.11%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 21        | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.96%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 17        | 0.86%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 16        | 0.81%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 16        | 0.81%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 16        | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.71%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 14        | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.71%   |
| Unknown                                                          | 14        | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.66%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 13        | 0.66%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 13        | 0.66%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.66%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 12        | 0.61%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.61%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 11        | 0.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 11        | 0.55%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 11        | 0.55%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 11        | 0.55%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.5%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.5%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 10        | 0.5%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 9         | 0.45%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.45%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.45%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 9         | 0.45%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 9         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 650       | 41.72%  |
| DDR3    | 561       | 36.01%  |
| LPDDR4  | 81        | 5.2%    |
| LPDDR3  | 71        | 4.56%   |
| DDR2    | 69        | 4.43%   |
| DDR5    | 48        | 3.08%   |
| SDRAM   | 26        | 1.67%   |
| LPDDR5  | 20        | 1.28%   |
| Unknown | 20        | 1.28%   |
| DDR     | 10        | 0.64%   |
| DRAM    | 2         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1365      | 87.78%  |
| Row Of Chips    | 147       | 9.45%   |
| Chip            | 19        | 1.22%   |
| Unknown         | 17        | 1.09%   |
| DIMM            | 6         | 0.39%   |
| Proprietary Car | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 690       | 39.63%  |
| 4096  | 495       | 28.43%  |
| 16384 | 232       | 13.33%  |
| 2048  | 218       | 12.52%  |
| 1024  | 54        | 3.1%    |
| 32768 | 45        | 2.58%   |
| 512   | 4         | 0.23%   |
| 256   | 2         | 0.11%   |
| 65536 | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 378       | 22.31%  |
| 2667    | 293       | 17.3%   |
| 3200    | 283       | 16.71%  |
| 2400    | 125       | 7.38%   |
| 2133    | 95        | 5.61%   |
| 1334    | 88        | 5.19%   |
| 1333    | 66        | 3.9%    |
| 4800    | 39        | 2.3%    |
| 667     | 37        | 2.18%   |
| 1067    | 36        | 2.13%   |
| 4267    | 32        | 1.89%   |
| 1867    | 27        | 1.59%   |
| Unknown | 27        | 1.59%   |
| 6400    | 22        | 1.3%    |
| 3266    | 19        | 1.12%   |
| 800     | 17        | 1%      |
| 4199    | 15        | 0.89%   |
| 4266    | 14        | 0.83%   |
| 1066    | 14        | 0.83%   |
| 8400    | 13        | 0.77%   |
| 975     | 12        | 0.71%   |
| 5600    | 9         | 0.53%   |
| 533     | 9         | 0.53%   |
| 3733    | 8         | 0.47%   |
| 2048    | 4         | 0.24%   |
| 1639    | 3         | 0.18%   |
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
| Chicony Electronics                    | 590       | 23.26%  |
| Microdia                               | 273       | 10.76%  |
| IMC Networks                           | 271       | 10.68%  |
| Realtek Semiconductor                  | 199       | 7.84%   |
| Sunplus Innovation Technology          | 154       | 6.07%   |
| Bison Electronics                      | 154       | 6.07%   |
| Quanta                                 | 113       | 4.45%   |
| Apple                                  | 105       | 4.14%   |
| Suyin                                  | 104       | 4.1%    |
| Cheng Uei Precision Industry (Foxlink) | 69        | 2.72%   |
| Acer                                   | 58        | 2.29%   |
| Logitech                               | 55        | 2.17%   |
| Lite-On Technology                     | 49        | 1.93%   |
| Luxvisions Innotech Limited            | 39        | 1.54%   |
| Syntek                                 | 33        | 1.3%    |
| Ricoh                                  | 32        | 1.26%   |
| Silicon Motion                         | 30        | 1.18%   |
| Lenovo                                 | 25        | 0.99%   |
| Sonix Technology                       | 24        | 0.95%   |
| Importek                               | 22        | 0.87%   |
| Samsung Electronics                    | 19        | 0.75%   |
| Alcor Micro                            | 17        | 0.67%   |
| Microsoft                              | 12        | 0.47%   |
| ALi                                    | 10        | 0.39%   |
| Primax Electronics                     | 8         | 0.32%   |
| OmniVision Technologies                | 8         | 0.32%   |
| Z-Star Microelectronics                | 6         | 0.24%   |
| LG Electronics                         | 4         | 0.16%   |
| YGTek                                  | 3         | 0.12%   |
| Sunplus Technology                     | 3         | 0.12%   |
| MacroSilicon                           | 3         | 0.12%   |
| icSpring                               | 3         | 0.12%   |
| AVerMedia Technologies                 | 3         | 0.12%   |
| 8SSC20F27114V1SR0BK1X4S                | 3         | 0.12%   |
| WaveRider Communications               | 2         | 0.08%   |
| SunplusIT                              | 2         | 0.08%   |
| HRY                                    | 2         | 0.08%   |
| Genesys Logic                          | 2         | 0.08%   |
| 8SSC21D67422V1SR28902JL                | 2         | 0.08%   |
| ZOOM                                   | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 140       | 5.49%   |
| Microdia Integrated_Webcam_HD                       | 123       | 4.82%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 100       | 3.92%   |
| Realtek Integrated_Webcam_HD                        | 84        | 3.29%   |
| IMC Networks Integrated Camera                      | 59        | 2.31%   |
| Chicony HD Webcam                                   | 55        | 2.16%   |
| Bison Integrated Camera                             | 43        | 1.69%   |
| Sunplus Integrated_Webcam_HD                        | 38        | 1.49%   |
| Microdia Integrated Webcam                          | 34        | 1.33%   |
| Apple Built-in iSight                               | 34        | 1.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 32        | 1.25%   |
| Apple FaceTime HD Camera                            | 32        | 1.25%   |
| Sunplus HD WebCam                                   | 27        | 1.06%   |
| Apple iPhone 5/5C/5S/6/SE                           | 27        | 1.06%   |
| Lite-On Integrated Camera                           | 24        | 0.94%   |
| Chicony HP TrueVision HD                            | 24        | 0.94%   |
| Bison HD Webcam                                     | 23        | 0.9%    |
| Quanta VGA WebCam                                   | 22        | 0.86%   |
| Quanta HD User Facing                               | 22        | 0.86%   |
| Chicony VGA WebCam                                  | 22        | 0.86%   |
| Chicony HP HD Camera                                | 22        | 0.86%   |
| Syntek Integrated Camera                            | 20        | 0.78%   |
| Bison SunplusIT Integrated Camera                   | 20        | 0.78%   |
| Samsung Galaxy series, misc. (MTP mode)             | 19        | 0.74%   |
| Quanta HP TrueVision HD Camera                      | 19        | 0.74%   |
| Realtek USB Camera                                  | 18        | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                        | 18        | 0.71%   |
| Chicony TOSHIBA Web Camera - HD                     | 18        | 0.71%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 17        | 0.67%   |
| Chicony USB 2.0 Camera                              | 17        | 0.67%   |
| Chicony Integrated Camera (1280x720@30)             | 17        | 0.67%   |
| Bison Lenovo EasyCamera                             | 17        | 0.67%   |
| Sonix USB2.0 HD UVC WebCam                          | 16        | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 16        | 0.63%   |
| Chicony HD User Facing                              | 16        | 0.63%   |
| IMC Networks VGA UVC WebCam                         | 15        | 0.59%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 15        | 0.59%   |
| Acer Integrated Camera                              | 15        | 0.59%   |
| Sunplus HP HD Webcam [Fixed]                        | 14        | 0.55%   |
| Logitech HD Pro Webcam C920                         | 14        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 223       | 39.54%  |
| Synaptics                          | 120       | 21.28%  |
| Shenzhen Goodix Technology         | 52        | 9.22%   |
| Elan Microelectronics              | 46        | 8.16%   |
| Upek                               | 39        | 6.91%   |
| AuthenTec                          | 37        | 6.56%   |
| LighTuning Technology              | 23        | 4.08%   |
| STMicroelectronics                 | 16        | 2.84%   |
| Focal-systems.Corp                 | 3         | 0.53%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.35%   |
| Microsoft                          | 1         | 0.18%   |
| HOLTEK                             | 1         | 0.18%   |
| Dell                               | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 52        | 9.22%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 44        | 7.8%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 40        | 7.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 6.74%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 34        | 6.03%   |
| Elan ELAN:Fingerprint                                                      | 34        | 6.03%   |
| Shenzhen Goodix FingerPrint                                                | 28        | 4.96%   |
| Validity Sensors Synaptics WBDI                                            | 27        | 4.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 3.55%   |
| Validity Sensors VFS491                                                    | 20        | 3.55%   |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 3.01%   |
| STMicroelectronics Fingerprint Reader                                      | 16        | 2.84%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 2.66%   |
| AuthenTec AES2810                                                          | 15        | 2.66%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 2.13%   |
| Elan ELAN:ARM-M4                                                           | 12        | 2.13%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 1.95%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 1.6%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 1.42%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 1.42%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 8         | 1.42%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.24%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.24%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 1.24%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.06%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.06%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 0.89%   |
| Synaptics  WBDI                                                            | 5         | 0.89%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.71%   |
| Synaptics TouchPad                                                         | 4         | 0.71%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 0.71%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.53%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.53%   |
| Synaptics WBDI                                                             | 3         | 0.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 0.53%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.53%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.53%   |
| AuthenTec AES1600                                                          | 3         | 0.53%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.35%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 103       | 47.91%  |
| Alcor Micro               | 41        | 19.07%  |
| O2 Micro                  | 27        | 12.56%  |
| Upek                      | 24        | 11.16%  |
| Lenovo                    | 13        | 6.05%   |
| Gemalto (was Gemplus)     | 4         | 1.86%   |
| Yubico.com                | 1         | 0.47%   |
| Giesecke & Devrient       | 1         | 0.47%   |
| Aladdin Knowledge Systems | 1         | 0.47%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 53        | 24.65%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 40        | 18.6%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 24        | 11.16%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 10.7%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 9.77%   |
| Broadcom 5880                                                                | 15        | 6.98%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 6.05%   |
| Broadcom 58200                                                               | 13        | 6.05%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.86%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 1.86%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.47%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.47%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.47%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.47%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1861      | 61.28%  |
| 1     | 918       | 30.23%  |
| 2     | 202       | 6.65%   |
| 3     | 32        | 1.05%   |
| 4     | 11        | 0.36%   |
| 5     | 7         | 0.23%   |
| 6     | 5         | 0.16%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 551       | 37.74%  |
| Graphics card            | 278       | 19.04%  |
| Chipcard                 | 198       | 13.56%  |
| Net/wireless             | 137       | 9.38%   |
| Multimedia controller    | 79        | 5.41%   |
| Storage                  | 38        | 2.6%    |
| Communication controller | 38        | 2.6%    |
| Camera                   | 33        | 2.26%   |
| Bluetooth                | 28        | 1.92%   |
| Sound                    | 23        | 1.58%   |
| Net/ethernet             | 15        | 1.03%   |
| Modem                    | 11        | 0.75%   |
| Card reader              | 10        | 0.68%   |
| Network                  | 5         | 0.34%   |
| Flash memory             | 5         | 0.34%   |
| Storage/raid             | 4         | 0.27%   |
| Storage/ide              | 2         | 0.14%   |
| Firewire controller      | 2         | 0.14%   |
| Unclassified device      | 1         | 0.07%   |
| Tv card                  | 1         | 0.07%   |
| Dvb card                 | 1         | 0.07%   |

