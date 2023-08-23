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

Total: 4093

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Google        | Droid                       | [b2a41c71ac](https://linux-hardware.org/?probe=b2a41c71ac) | Mar 12, 2023 |
| HP            | ProBook 650 G2              | [2eb6d39ced](https://linux-hardware.org/?probe=2eb6d39ced) | Mar 12, 2023 |
| HP            | ProBook 650 G2              | [01f61fad51](https://linux-hardware.org/?probe=01f61fad51) | Mar 12, 2023 |
| Unknown       | Unknown                     | [d1336c09a0](https://linux-hardware.org/?probe=d1336c09a0) | Mar 11, 2023 |
| Lenovo        | V15-IIL 82C5                | [da8c40d88c](https://linux-hardware.org/?probe=da8c40d88c) | Mar 11, 2023 |
| Acer          | Aspire ES1-531              | [bf2d3857fd](https://linux-hardware.org/?probe=bf2d3857fd) | Mar 09, 2023 |
| Dell          | Latitude 3180               | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [da38390eca](https://linux-hardware.org/?probe=da38390eca) | Mar 09, 2023 |
| Lenovo        | 3000 N200 0769AUU           | [faaa24cfbf](https://linux-hardware.org/?probe=faaa24cfbf) | Mar 07, 2023 |
| Dell          | Studio 1537                 | [2cadadec43](https://linux-hardware.org/?probe=2cadadec43) | Mar 07, 2023 |
| Dell          | Latitude E6520              | [5e7340faf5](https://linux-hardware.org/?probe=5e7340faf5) | Mar 07, 2023 |
| Lenovo        | 3000 N200 0769AUU           | [fe3f99601c](https://linux-hardware.org/?probe=fe3f99601c) | Mar 07, 2023 |
| Datto         | 1000                        | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Acer          | Aspire E1-571               | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| Apple         | MacBookPro9,2               | [64d9894f5e](https://linux-hardware.org/?probe=64d9894f5e) | Mar 05, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | [24373477d9](https://linux-hardware.org/?probe=24373477d9) | Mar 05, 2023 |
| MSI           | PS42 8RB                    | [effde33b49](https://linux-hardware.org/?probe=effde33b49) | Mar 05, 2023 |
| HP            | ProBook 650 G2              | [886fdbe7c9](https://linux-hardware.org/?probe=886fdbe7c9) | Mar 05, 2023 |
| HP            | ProBook 650 G2              | [2fdc151d2f](https://linux-hardware.org/?probe=2fdc151d2f) | Mar 05, 2023 |
| Dell          | Precision M4800             | [b014753659](https://linux-hardware.org/?probe=b014753659) | Mar 05, 2023 |
| HP            | Presario CQ61               | [912b79009b](https://linux-hardware.org/?probe=912b79009b) | Mar 04, 2023 |
| Acer          | Swift SF314-42              | [b9a0465659](https://linux-hardware.org/?probe=b9a0465659) | Mar 04, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9aebf534a5](https://linux-hardware.org/?probe=9aebf534a5) | Mar 04, 2023 |
| Lenovo        | ThinkPad X220 429035U       | [83266c1006](https://linux-hardware.org/?probe=83266c1006) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | ENVY 17                     | [52b43673bb](https://linux-hardware.org/?probe=52b43673bb) | Mar 03, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | [e8f0217102](https://linux-hardware.org/?probe=e8f0217102) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Dell          | Precision 5520              | [9ce4c56521](https://linux-hardware.org/?probe=9ce4c56521) | Mar 02, 2023 |
| Valve         | Jupiter                     | [6525b5d0a4](https://linux-hardware.org/?probe=6525b5d0a4) | Mar 01, 2023 |
| HP            | EliteBook 830 G5            | [9abfe7631c](https://linux-hardware.org/?probe=9abfe7631c) | Mar 01, 2023 |
| Valve         | Jupiter                     | [a6c009eb9c](https://linux-hardware.org/?probe=a6c009eb9c) | Mar 01, 2023 |
| Acer          | Aspire E1-532P              | [8a23f06db4](https://linux-hardware.org/?probe=8a23f06db4) | Mar 01, 2023 |
| HP            | Pavilion dv6                | [c937edbfcd](https://linux-hardware.org/?probe=c937edbfcd) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [d8b58a8ea1](https://linux-hardware.org/?probe=d8b58a8ea1) | Feb 28, 2023 |
| Alienware     | x15 R2                      | [f0335542ce](https://linux-hardware.org/?probe=f0335542ce) | Feb 28, 2023 |
| Toshiba       | Satellite P870              | [6d9216b866](https://linux-hardware.org/?probe=6d9216b866) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [091e4e3188](https://linux-hardware.org/?probe=091e4e3188) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | [a9a8184201](https://linux-hardware.org/?probe=a9a8184201) | Feb 27, 2023 |
| HP            | ProBook 650 G2              | [07f46e8e62](https://linux-hardware.org/?probe=07f46e8e62) | Feb 27, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [8de57c03d5](https://linux-hardware.org/?probe=8de57c03d5) | Feb 27, 2023 |
| HP            | EliteBook 2530p             | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS35H02    | [a396e54378](https://linux-hardware.org/?probe=a396e54378) | Feb 25, 2023 |
| Apple         | MacBook5,1                  | [fbb2478f8c](https://linux-hardware.org/?probe=fbb2478f8c) | Feb 25, 2023 |
| HP            | G60                         | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| Google        | Kefka                       | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Dell          | Inspiron 5566               | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| Dell          | Latitude E6520              | [4a9371ec87](https://linux-hardware.org/?probe=4a9371ec87) | Feb 22, 2023 |
| Dell          | Inspiron 5493               | [ad7bee8a6e](https://linux-hardware.org/?probe=ad7bee8a6e) | Feb 20, 2023 |
| Dell          | Latitude E5440              | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| Dell          | XPS 15 9520                 | [d346153872](https://linux-hardware.org/?probe=d346153872) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| Dell          | Precision M4500             | [b0d8bf3c56](https://linux-hardware.org/?probe=b0d8bf3c56) | Feb 19, 2023 |
| Panasonic     | CF-S10CDHEDM                | [7228f7a915](https://linux-hardware.org/?probe=7228f7a915) | Feb 19, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [b0941b8ef0](https://linux-hardware.org/?probe=b0941b8ef0) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | [58ca93166c](https://linux-hardware.org/?probe=58ca93166c) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9978dc62b3](https://linux-hardware.org/?probe=9978dc62b3) | Feb 18, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [6b7a3b68f3](https://linux-hardware.org/?probe=6b7a3b68f3) | Feb 18, 2023 |
| MSI           | Raider GE76 12UGS           | [041cf0d3d8](https://linux-hardware.org/?probe=041cf0d3d8) | Feb 18, 2023 |
| MSI           | Raider GE76 12UGS           | [20dc6d6c5c](https://linux-hardware.org/?probe=20dc6d6c5c) | Feb 18, 2023 |
| HP            | Pavilion 13 x360 PC         | [af3167a0d4](https://linux-hardware.org/?probe=af3167a0d4) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | [9ab628bcf2](https://linux-hardware.org/?probe=9ab628bcf2) | Feb 18, 2023 |
| Dell          | Inspiron 5575               | [aaa83a4af0](https://linux-hardware.org/?probe=aaa83a4af0) | Feb 18, 2023 |
| Dell          | Inspiron 5575               | [18b6274238](https://linux-hardware.org/?probe=18b6274238) | Feb 18, 2023 |
| HP            | ProBook 650 G2              | [33d9c73cb9](https://linux-hardware.org/?probe=33d9c73cb9) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| Google        | Coral                       | [7a9869ff50](https://linux-hardware.org/?probe=7a9869ff50) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [0e694f49fe](https://linux-hardware.org/?probe=0e694f49fe) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| Dell          | Precision 7710              | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| HP            | EliteBook 840 G5            | [2d99eeaca6](https://linux-hardware.org/?probe=2d99eeaca6) | Feb 13, 2023 |
| Panasonic     | CF-C2CCEZXCM                | [c435502e6e](https://linux-hardware.org/?probe=c435502e6e) | Feb 13, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1VL0... | [d4b5ca228c](https://linux-hardware.org/?probe=d4b5ca228c) | Feb 13, 2023 |
| HP            | Pavilion dv2500             | [bea8c0162f](https://linux-hardware.org/?probe=bea8c0162f) | Feb 12, 2023 |
| Panasonic     | CF-C2CCEZXCM                | [3a0ce0730a](https://linux-hardware.org/?probe=3a0ce0730a) | Feb 12, 2023 |
| Acer          | Aspire 8942G                | [d517f63625](https://linux-hardware.org/?probe=d517f63625) | Feb 12, 2023 |
| Valve         | Jupiter                     | [10084e1b16](https://linux-hardware.org/?probe=10084e1b16) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3982ec4e74](https://linux-hardware.org/?probe=3982ec4e74) | Feb 12, 2023 |
| HP            | Presario V6000 (RN927UA#... | [0524b3b524](https://linux-hardware.org/?probe=0524b3b524) | Feb 11, 2023 |
| Google        | Droid                       | [33dbb43623](https://linux-hardware.org/?probe=33dbb43623) | Feb 10, 2023 |
| HP            | Notebook                    | [17664bf689](https://linux-hardware.org/?probe=17664bf689) | Feb 10, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [0a74293474](https://linux-hardware.org/?probe=0a74293474) | Feb 10, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [9b8563ab53](https://linux-hardware.org/?probe=9b8563ab53) | Feb 10, 2023 |
| HP            | EliteBook 8460p             | [91de8b5956](https://linux-hardware.org/?probe=91de8b5956) | Feb 09, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [d236f5fa51](https://linux-hardware.org/?probe=d236f5fa51) | Feb 09, 2023 |
| HP            | Pavilion dv7                | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| Lenovo        | Unknown                     | [67c2761551](https://linux-hardware.org/?probe=67c2761551) | Feb 07, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [ebe5940bd7](https://linux-hardware.org/?probe=ebe5940bd7) | Feb 07, 2023 |
| MSI           | GT72 6QE                    | [bd02e4c770](https://linux-hardware.org/?probe=bd02e4c770) | Feb 07, 2023 |
| MSI           | GT72 6QE                    | [43a7194d4b](https://linux-hardware.org/?probe=43a7194d4b) | Feb 07, 2023 |
| Acer          | Okinawa                     | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Acer          | Aspire A315-21              | [b452c164d0](https://linux-hardware.org/?probe=b452c164d0) | Feb 05, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [f3f4d9fc40](https://linux-hardware.org/?probe=f3f4d9fc40) | Feb 04, 2023 |
| HP            | G60                         | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Valve         | Jupiter                     | [d78de63927](https://linux-hardware.org/?probe=d78de63927) | Feb 04, 2023 |
| Acer          | Aspire A517-51G             | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [c122070f4f](https://linux-hardware.org/?probe=c122070f4f) | Feb 03, 2023 |
| Dell          | XPS 15 9520                 | [830188ba1b](https://linux-hardware.org/?probe=830188ba1b) | Feb 03, 2023 |
| Dell          | Latitude 3400               | [c954aad23a](https://linux-hardware.org/?probe=c954aad23a) | Feb 02, 2023 |
| HP            | EliteBook 2570p             | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
| Dell          | XPS 15 9510                 | [78ea388883](https://linux-hardware.org/?probe=78ea388883) | Feb 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [8bc290ef67](https://linux-hardware.org/?probe=8bc290ef67) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |
| HP            | Laptop 14-dq4xxx            | [c102edf6a0](https://linux-hardware.org/?probe=c102edf6a0) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [1d212c67b2](https://linux-hardware.org/?probe=1d212c67b2) | Jan 31, 2023 |
| Dell          | Inspiron 15-7579            | [b5bd231bf3](https://linux-hardware.org/?probe=b5bd231bf3) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| ASUSTek       | Zenbook UX8402ZA_UX8402Z... | [4dcc88b215](https://linux-hardware.org/?probe=4dcc88b215) | Jan 31, 2023 |
| Dell          | Latitude D630               | [ff0aa8c4ed](https://linux-hardware.org/?probe=ff0aa8c4ed) | Jan 31, 2023 |
| Dell          | Latitude D630               | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS0BR00     | [6c05048c9d](https://linux-hardware.org/?probe=6c05048c9d) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| Apple         | MacBookPro8,1               | [0eac708be5](https://linux-hardware.org/?probe=0eac708be5) | Jan 31, 2023 |
| HP            | Notebook                    | [fc93f8e357](https://linux-hardware.org/?probe=fc93f8e357) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | [5802e6b9b9](https://linux-hardware.org/?probe=5802e6b9b9) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430 2347G4U       | [3fcf581653](https://linux-hardware.org/?probe=3fcf581653) | Jan 30, 2023 |
| Dell          | Vostro 7620                 | [b6d43b8741](https://linux-hardware.org/?probe=b6d43b8741) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [3e7c902731](https://linux-hardware.org/?probe=3e7c902731) | Jan 28, 2023 |
| ASUSTek       | X555QA                      | [8eec8468fb](https://linux-hardware.org/?probe=8eec8468fb) | Jan 28, 2023 |
| Notebook      | P9XXEN_EF_ED                | [991bb71df8](https://linux-hardware.org/?probe=991bb71df8) | Jan 28, 2023 |
| Notebook      | P9XXEN_EF_ED                | [d86e915f12](https://linux-hardware.org/?probe=d86e915f12) | Jan 28, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [796df2715d](https://linux-hardware.org/?probe=796df2715d) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| HP            | Laptop 17-cp0xxx            | [55477da159](https://linux-hardware.org/?probe=55477da159) | Jan 27, 2023 |
| Dell          | Latitude E6540              | [2e014cf1ba](https://linux-hardware.org/?probe=2e014cf1ba) | Jan 27, 2023 |
| Acer          | Aspire R3-131T              | [021d999708](https://linux-hardware.org/?probe=021d999708) | Jan 27, 2023 |
| Dell          | Latitude E6420              | [9837928212](https://linux-hardware.org/?probe=9837928212) | Jan 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [08204bf161](https://linux-hardware.org/?probe=08204bf161) | Jan 26, 2023 |
| Apple         | MacBookAir4,1               | [45ea832a59](https://linux-hardware.org/?probe=45ea832a59) | Jan 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [aa6488b6b8](https://linux-hardware.org/?probe=aa6488b6b8) | Jan 25, 2023 |
| Valve         | Jupiter                     | [ba217c947c](https://linux-hardware.org/?probe=ba217c947c) | Jan 25, 2023 |
| Valve         | Jupiter                     | [ffd9523db2](https://linux-hardware.org/?probe=ffd9523db2) | Jan 25, 2023 |
| Apple         | MacBookPro5,4               | [4bdccd0680](https://linux-hardware.org/?probe=4bdccd0680) | Jan 24, 2023 |
| ASUSTek       | X555QA                      | [f981af502a](https://linux-hardware.org/?probe=f981af502a) | Jan 24, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| Acer          | AO722                       | [85f48171a2](https://linux-hardware.org/?probe=85f48171a2) | Jan 23, 2023 |
| GPU Compan... | GWNR71517                   | [77d4494f3b](https://linux-hardware.org/?probe=77d4494f3b) | Jan 23, 2023 |
| GPU Compan... | GWNR71517                   | [f3d76bcb70](https://linux-hardware.org/?probe=f3d76bcb70) | Jan 23, 2023 |
| Dell          | Inspiron 3521               | [ff122405db](https://linux-hardware.org/?probe=ff122405db) | Jan 22, 2023 |
| Dell          | Inspiron 3521               | [bb77ccdda7](https://linux-hardware.org/?probe=bb77ccdda7) | Jan 22, 2023 |
| Dell          | Inspiron 3521               | [2189958490](https://linux-hardware.org/?probe=2189958490) | Jan 22, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [6ae7274931](https://linux-hardware.org/?probe=6ae7274931) | Jan 22, 2023 |
| Acer          | Aspire E1-531               | [217c63b8f6](https://linux-hardware.org/?probe=217c63b8f6) | Jan 22, 2023 |
| Dell          | Latitude E5400              | [ee6e466820](https://linux-hardware.org/?probe=ee6e466820) | Jan 22, 2023 |
| Dell          | Latitude E5400              | [f61d1e0868](https://linux-hardware.org/?probe=f61d1e0868) | Jan 22, 2023 |
| Dell          | XPS 15 9520                 | [330a3844cb](https://linux-hardware.org/?probe=330a3844cb) | Jan 21, 2023 |
| Lenovo        | ThinkPad P52s 20LBCTO1WW    | [e0b197c0c4](https://linux-hardware.org/?probe=e0b197c0c4) | Jan 21, 2023 |
| HP            | Laptop 15-dy3xxx            | [1053d34e69](https://linux-hardware.org/?probe=1053d34e69) | Jan 20, 2023 |
| ASUSTek       | X555QA                      | [cd42f89819](https://linux-hardware.org/?probe=cd42f89819) | Jan 20, 2023 |
| Valve         | Jupiter                     | [e29a7a31ae](https://linux-hardware.org/?probe=e29a7a31ae) | Jan 20, 2023 |
| Dell          | Studio XPS 1647             | [4086a6120a](https://linux-hardware.org/?probe=4086a6120a) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| Toshiba       | Satellite L650D             | [86d99d74cd](https://linux-hardware.org/?probe=86d99d74cd) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0770f064de](https://linux-hardware.org/?probe=0770f064de) | Jan 19, 2023 |
| Intel Clie... | LAPRC510                    | [6d570a1aee](https://linux-hardware.org/?probe=6d570a1aee) | Jan 19, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | [3ab44ae2f5](https://linux-hardware.org/?probe=3ab44ae2f5) | Jan 17, 2023 |
| HP            | Pavilion dv7                | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| Dell          | Inspiron 3521               | [2d46e86664](https://linux-hardware.org/?probe=2d46e86664) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [a602bcd50a](https://linux-hardware.org/?probe=a602bcd50a) | Jan 17, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | [1bd88ff8c7](https://linux-hardware.org/?probe=1bd88ff8c7) | Jan 17, 2023 |
| Valve         | Jupiter                     | [2b355faaee](https://linux-hardware.org/?probe=2b355faaee) | Jan 16, 2023 |
| Dell          | Inspiron 3521               | [da7f445f06](https://linux-hardware.org/?probe=da7f445f06) | Jan 16, 2023 |
| HP            | Pavilion 17                 | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | [e04d230b62](https://linux-hardware.org/?probe=e04d230b62) | Jan 16, 2023 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | [620185bf98](https://linux-hardware.org/?probe=620185bf98) | Jan 15, 2023 |
| Apple         | MacBookPro8,1               | [422f31719c](https://linux-hardware.org/?probe=422f31719c) | Jan 15, 2023 |
| Apple         | MacBookPro8,1               | [c16748dc74](https://linux-hardware.org/?probe=c16748dc74) | Jan 15, 2023 |
| Lenovo        | G560 0679                   | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Toshiba       | Satellite L650              | [b893aecea2](https://linux-hardware.org/?probe=b893aecea2) | Jan 15, 2023 |
| Valve         | Jupiter                     | [c9bc8bf29b](https://linux-hardware.org/?probe=c9bc8bf29b) | Jan 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [9527eef253](https://linux-hardware.org/?probe=9527eef253) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | [6194c3a2fe](https://linux-hardware.org/?probe=6194c3a2fe) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | [a24b95f891](https://linux-hardware.org/?probe=a24b95f891) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | [4776fc6062](https://linux-hardware.org/?probe=4776fc6062) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | [f9fe88837c](https://linux-hardware.org/?probe=f9fe88837c) | Jan 15, 2023 |
| Lenovo        | ThinkPad T420 4236V6S       | [59607f5e75](https://linux-hardware.org/?probe=59607f5e75) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | [a4b4747500](https://linux-hardware.org/?probe=a4b4747500) | Jan 14, 2023 |
| Apple         | MacBookPro5,5               | [4340505060](https://linux-hardware.org/?probe=4340505060) | Jan 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [03f7a5fdea](https://linux-hardware.org/?probe=03f7a5fdea) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | [9e4c15fff7](https://linux-hardware.org/?probe=9e4c15fff7) | Jan 14, 2023 |
| Apple         | MacBookPro5,5               | [77d37c245a](https://linux-hardware.org/?probe=77d37c245a) | Jan 14, 2023 |
| MSI           | GP72 7RDX                   | [9cf1da2d69](https://linux-hardware.org/?probe=9cf1da2d69) | Jan 14, 2023 |
| Dell          | Latitude E6420              | [e7c4823aee](https://linux-hardware.org/?probe=e7c4823aee) | Jan 14, 2023 |
| HP            | Notebook                    | [e242059a08](https://linux-hardware.org/?probe=e242059a08) | Jan 14, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [eeec2db688](https://linux-hardware.org/?probe=eeec2db688) | Jan 13, 2023 |
| Acer          | Aspire E1-572               | [fa6e296766](https://linux-hardware.org/?probe=fa6e296766) | Jan 13, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [fad743f278](https://linux-hardware.org/?probe=fad743f278) | Jan 12, 2023 |
| Matsushita... | CF-18KH2ZXBC                | [41e8ef7b23](https://linux-hardware.org/?probe=41e8ef7b23) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| Valve         | Jupiter                     | [6bfa934fb6](https://linux-hardware.org/?probe=6bfa934fb6) | Jan 11, 2023 |
| Dell          | G5 5590                     | [846a462365](https://linux-hardware.org/?probe=846a462365) | Jan 10, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | [c6e3650e2b](https://linux-hardware.org/?probe=c6e3650e2b) | Jan 10, 2023 |
| System76      | Darter Pro                  | [ffaaf5c90e](https://linux-hardware.org/?probe=ffaaf5c90e) | Jan 10, 2023 |
| HP            | ENVY Notebook               | [ff8cd12017](https://linux-hardware.org/?probe=ff8cd12017) | Jan 10, 2023 |
| Google        | Blooglet                    | [bf644ec6f4](https://linux-hardware.org/?probe=bf644ec6f4) | Jan 10, 2023 |
| Dell          | Inspiron 5577               | [86cfa19622](https://linux-hardware.org/?probe=86cfa19622) | Jan 10, 2023 |
| Lenovo        | ThinkPad T420 4236A38       | [302f3a5ebe](https://linux-hardware.org/?probe=302f3a5ebe) | Jan 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [2bbe617df6](https://linux-hardware.org/?probe=2bbe617df6) | Jan 09, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [d6115e24c1](https://linux-hardware.org/?probe=d6115e24c1) | Jan 09, 2023 |
| GPU Compan... | GWNR71517                   | [5626a7c211](https://linux-hardware.org/?probe=5626a7c211) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [f884203e84](https://linux-hardware.org/?probe=f884203e84) | Jan 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b518c0a817](https://linux-hardware.org/?probe=b518c0a817) | Jan 09, 2023 |
| ASUSTek       | X550ZA                      | [272bff51c5](https://linux-hardware.org/?probe=272bff51c5) | Jan 09, 2023 |
| GPU Compan... | GWNR71517                   | [11cb3f9636](https://linux-hardware.org/?probe=11cb3f9636) | Jan 08, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [c8e96fe453](https://linux-hardware.org/?probe=c8e96fe453) | Jan 08, 2023 |
| Lenovo        | ThinkPad T420 4236A38       | [b95882e5cf](https://linux-hardware.org/?probe=b95882e5cf) | Jan 08, 2023 |
| Lenovo        | N22 80S6                    | [cfcc0a49c6](https://linux-hardware.org/?probe=cfcc0a49c6) | Jan 08, 2023 |
| Valve         | Jupiter                     | [4c96ccba44](https://linux-hardware.org/?probe=4c96ccba44) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2e22cc1bb2](https://linux-hardware.org/?probe=2e22cc1bb2) | Jan 08, 2023 |
| Lenovo        | ThinkPad W520 4284A24       | [263e00840a](https://linux-hardware.org/?probe=263e00840a) | Jan 08, 2023 |
| Dell          | XPS 9320                    | [55be119900](https://linux-hardware.org/?probe=55be119900) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [83ec1382a3](https://linux-hardware.org/?probe=83ec1382a3) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [354b2538a4](https://linux-hardware.org/?probe=354b2538a4) | Jan 07, 2023 |
| HP            | Pavilion dv4                | [5caee4abe0](https://linux-hardware.org/?probe=5caee4abe0) | Jan 07, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [15eaac1fac](https://linux-hardware.org/?probe=15eaac1fac) | Jan 07, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | [28c9b60939](https://linux-hardware.org/?probe=28c9b60939) | Jan 07, 2023 |
| Dell          | Inspiron 7577               | [ff95fa094b](https://linux-hardware.org/?probe=ff95fa094b) | Jan 06, 2023 |
| ASUSTek       | X301A1                      | [e575482522](https://linux-hardware.org/?probe=e575482522) | Jan 06, 2023 |
| Dell          | G15 5525                    | [2c61cbc942](https://linux-hardware.org/?probe=2c61cbc942) | Jan 06, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | [4d2721777a](https://linux-hardware.org/?probe=4d2721777a) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | [d2ee3f78a9](https://linux-hardware.org/?probe=d2ee3f78a9) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | [9c9801b860](https://linux-hardware.org/?probe=9c9801b860) | Jan 06, 2023 |
| Lenovo        | Z50-75 80EC                 | [7fe70dc4c8](https://linux-hardware.org/?probe=7fe70dc4c8) | Jan 06, 2023 |
| Lenovo        | ThinkPad T450s 20BX001PU... | [907ceedda1](https://linux-hardware.org/?probe=907ceedda1) | Jan 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [2da57c3386](https://linux-hardware.org/?probe=2da57c3386) | Jan 04, 2023 |
| Acer          | Swift SF314-43              | [50d8f0c1cb](https://linux-hardware.org/?probe=50d8f0c1cb) | Jan 04, 2023 |
| Dell          | Latitude 7420               | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | [3d589a827c](https://linux-hardware.org/?probe=3d589a827c) | Jan 04, 2023 |
| Dell          | Latitude D520               | [7f05ddf105](https://linux-hardware.org/?probe=7f05ddf105) | Jan 04, 2023 |
| Datto         | Unknown                     | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| HP            | Pavilion dv7                | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [a73ca839a1](https://linux-hardware.org/?probe=a73ca839a1) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| Dell          | Latitude E5440              | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [b9522e3683](https://linux-hardware.org/?probe=b9522e3683) | Jan 02, 2023 |
| HP            | Pavilion dv6                | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| Valve         | Jupiter                     | [1dedff3ad9](https://linux-hardware.org/?probe=1dedff3ad9) | Jan 01, 2023 |
| Dell          | Latitude E7450              | [f48717bb6f](https://linux-hardware.org/?probe=f48717bb6f) | Jan 01, 2023 |
| Acer          | Aspire E5-521               | [d9b5e3cfc3](https://linux-hardware.org/?probe=d9b5e3cfc3) | Dec 31, 2022 |
| Intel Clie... | LAPRC710                    | [47e562afc7](https://linux-hardware.org/?probe=47e562afc7) | Dec 31, 2022 |
| ASUSTek       | TP501UA                     | [1f2aaf8804](https://linux-hardware.org/?probe=1f2aaf8804) | Dec 30, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [770c5eee84](https://linux-hardware.org/?probe=770c5eee84) | Dec 30, 2022 |
| Acer          | Aspire A115-32              | [7c8ec90c8a](https://linux-hardware.org/?probe=7c8ec90c8a) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [1cab27a65e](https://linux-hardware.org/?probe=1cab27a65e) | Dec 29, 2022 |
| HP            | EliteBook 2540p             | [ec9251ac5d](https://linux-hardware.org/?probe=ec9251ac5d) | Dec 28, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [9e95d6a4ac](https://linux-hardware.org/?probe=9e95d6a4ac) | Dec 28, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [00a92c3818](https://linux-hardware.org/?probe=00a92c3818) | Dec 28, 2022 |
| Panasonic     | FZ55-2                      | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| Lenovo        | ThinkPad T500 205545F       | [c12d9f8c6a](https://linux-hardware.org/?probe=c12d9f8c6a) | Dec 27, 2022 |
| Dell          | Latitude E7440              | [f2c052dde9](https://linux-hardware.org/?probe=f2c052dde9) | Dec 27, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [877e3cd944](https://linux-hardware.org/?probe=877e3cd944) | Dec 26, 2022 |
| Dell          | Latitude E4310              | [f63df6ad2c](https://linux-hardware.org/?probe=f63df6ad2c) | Dec 26, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [90a67d3589](https://linux-hardware.org/?probe=90a67d3589) | Dec 25, 2022 |
| Valve         | Jupiter                     | [91be8cc560](https://linux-hardware.org/?probe=91be8cc560) | Dec 25, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |
| HP            | Pavilion dv7                | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| System76      | Pangolin                    | [1c936bfe04](https://linux-hardware.org/?probe=1c936bfe04) | Dec 24, 2022 |
| MSI           | Pulse GL76 12UEK            | [9ca4075241](https://linux-hardware.org/?probe=9ca4075241) | Dec 23, 2022 |
| MSI           | Pulse GL76 12UEK            | [099b612c13](https://linux-hardware.org/?probe=099b612c13) | Dec 23, 2022 |
| Toshiba       | TECRA R940                  | [939e438746](https://linux-hardware.org/?probe=939e438746) | Dec 22, 2022 |
| HP            | Stream Notebook PC 13       | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [13e778509f](https://linux-hardware.org/?probe=13e778509f) | Dec 22, 2022 |
| Dell          | Latitude 5510               | [b4f32be15b](https://linux-hardware.org/?probe=b4f32be15b) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fb60e7984c](https://linux-hardware.org/?probe=fb60e7984c) | Dec 21, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [0377cc3170](https://linux-hardware.org/?probe=0377cc3170) | Dec 21, 2022 |
| Dell          | Latitude D820               | [e79993028e](https://linux-hardware.org/?probe=e79993028e) | Dec 21, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [d5a877b2c6](https://linux-hardware.org/?probe=d5a877b2c6) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5ba954d88a](https://linux-hardware.org/?probe=5ba954d88a) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [318b7c1400](https://linux-hardware.org/?probe=318b7c1400) | Dec 19, 2022 |
| Dell          | XPS 13 9350                 | [d414748117](https://linux-hardware.org/?probe=d414748117) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| Lenovo        | IdeaPad Z570 10249UU        | [2160e3e2c3](https://linux-hardware.org/?probe=2160e3e2c3) | Dec 18, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [071b57d5f6](https://linux-hardware.org/?probe=071b57d5f6) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [2ba98da01d](https://linux-hardware.org/?probe=2ba98da01d) | Dec 16, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [a12207ff89](https://linux-hardware.org/?probe=a12207ff89) | Dec 16, 2022 |
| Google        | Blorb                       | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [20240705a9](https://linux-hardware.org/?probe=20240705a9) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [955de558cb](https://linux-hardware.org/?probe=955de558cb) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [e1d8403247](https://linux-hardware.org/?probe=e1d8403247) | Dec 16, 2022 |
| Dell          | Inspiron 7501               | [1749ece1b3](https://linux-hardware.org/?probe=1749ece1b3) | Dec 15, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [36afd57275](https://linux-hardware.org/?probe=36afd57275) | Dec 14, 2022 |
| MSI           | GE72VR 6RF                  | [ce2ebf80a1](https://linux-hardware.org/?probe=ce2ebf80a1) | Dec 14, 2022 |
| HP            | Pavilion dv7                | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| Dell          | Latitude E4310              | [dd3e716d03](https://linux-hardware.org/?probe=dd3e716d03) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Acer          | Nitro AN517-41              | [468d665801](https://linux-hardware.org/?probe=468d665801) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| Dell          | Latitude 7430               | [87e9348100](https://linux-hardware.org/?probe=87e9348100) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [ca560a74e4](https://linux-hardware.org/?probe=ca560a74e4) | Dec 12, 2022 |
| Apple         | MacBookPro11,2              | [6048cffe66](https://linux-hardware.org/?probe=6048cffe66) | Dec 12, 2022 |
| Dell          | Inspiron 13-5378            | [d8bb31c8c7](https://linux-hardware.org/?probe=d8bb31c8c7) | Dec 11, 2022 |
| Alienware     | 18                          | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Acer          | Aspire A515-55              | [9451601259](https://linux-hardware.org/?probe=9451601259) | Dec 11, 2022 |
| Dell          | Inspiron 7537               | [890f5f6529](https://linux-hardware.org/?probe=890f5f6529) | Dec 11, 2022 |
| Google        | Candy                       | [12e6466598](https://linux-hardware.org/?probe=12e6466598) | Dec 11, 2022 |
| Dell          | G5 5505                     | [60053b5d4b](https://linux-hardware.org/?probe=60053b5d4b) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [ed7cb7fb48](https://linux-hardware.org/?probe=ed7cb7fb48) | Dec 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2dc32e31b3](https://linux-hardware.org/?probe=2dc32e31b3) | Dec 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [aebce6bc5f](https://linux-hardware.org/?probe=aebce6bc5f) | Dec 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [4c7a6feb83](https://linux-hardware.org/?probe=4c7a6feb83) | Dec 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57373e16ba](https://linux-hardware.org/?probe=57373e16ba) | Dec 07, 2022 |
| HP            | Laptop 15-dy5xxx            | [12676c4b5b](https://linux-hardware.org/?probe=12676c4b5b) | Dec 07, 2022 |
| Acer          | Swift SF314-42              | [4c5be8eaf3](https://linux-hardware.org/?probe=4c5be8eaf3) | Dec 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [388bcfc8e6](https://linux-hardware.org/?probe=388bcfc8e6) | Dec 07, 2022 |
| Dell          | Latitude 5421               | [f310b80613](https://linux-hardware.org/?probe=f310b80613) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [ce36965c1f](https://linux-hardware.org/?probe=ce36965c1f) | Dec 06, 2022 |
| Dell          | Latitude 5421               | [5114034147](https://linux-hardware.org/?probe=5114034147) | Dec 06, 2022 |
| Apple         | MacBook4,1                  | [109d33ef14](https://linux-hardware.org/?probe=109d33ef14) | Dec 06, 2022 |
| MSI           | GE72VR 6RF                  | [23a83a5e8e](https://linux-hardware.org/?probe=23a83a5e8e) | Dec 06, 2022 |
| HP            | 15                          | [e5a0cdc9de](https://linux-hardware.org/?probe=e5a0cdc9de) | Dec 06, 2022 |
| MSI           | GS66 Stealth 11UH           | [b16c3a06ba](https://linux-hardware.org/?probe=b16c3a06ba) | Dec 05, 2022 |
| Apple         | MacBookPro6,1               | [137dd6d1ba](https://linux-hardware.org/?probe=137dd6d1ba) | Dec 05, 2022 |
| ASUSTek       | UL50VT                      | [ff4edb7010](https://linux-hardware.org/?probe=ff4edb7010) | Dec 05, 2022 |
| Dell          | Latitude 7490               | [7377ad6d99](https://linux-hardware.org/?probe=7377ad6d99) | Dec 05, 2022 |
| Dell          | Latitude 7430               | [d153a4f803](https://linux-hardware.org/?probe=d153a4f803) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| Apple         | MacBookPro10,1              | [d321abafcd](https://linux-hardware.org/?probe=d321abafcd) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Toshiba       | Satellite C650D             | [694d2c9099](https://linux-hardware.org/?probe=694d2c9099) | Dec 05, 2022 |
| System76      | Gazelle                     | [deb2c9b6c9](https://linux-hardware.org/?probe=deb2c9b6c9) | Dec 04, 2022 |
| Dell          | Latitude E5450              | [eced7855f2](https://linux-hardware.org/?probe=eced7855f2) | Dec 03, 2022 |
| HP            | G62                         | [494d9e65e4](https://linux-hardware.org/?probe=494d9e65e4) | Dec 03, 2022 |
| HP            | ProBook 4530s               | [f8f94617e8](https://linux-hardware.org/?probe=f8f94617e8) | Dec 03, 2022 |
| Toshiba       | Satellite S50-A             | [ac76869bea](https://linux-hardware.org/?probe=ac76869bea) | Dec 02, 2022 |
| Dell          | Inspiron 5566               | [54e06d37fc](https://linux-hardware.org/?probe=54e06d37fc) | Dec 02, 2022 |
| Dell          | Latitude E6410              | [92bae2f9d5](https://linux-hardware.org/?probe=92bae2f9d5) | Dec 02, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [253135f8dc](https://linux-hardware.org/?probe=253135f8dc) | Dec 01, 2022 |
| Acer          | Aspire V5-121               | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [5b22a7d584](https://linux-hardware.org/?probe=5b22a7d584) | Dec 01, 2022 |
| Lenovo        | ThinkPad T420 4236V6S       | [5900d34c9a](https://linux-hardware.org/?probe=5900d34c9a) | Dec 01, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [19c2f41d14](https://linux-hardware.org/?probe=19c2f41d14) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | [d313455fa8](https://linux-hardware.org/?probe=d313455fa8) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | [31b9efe771](https://linux-hardware.org/?probe=31b9efe771) | Dec 01, 2022 |
| HP            | Pavilion dv5                | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| HP            | Elite x2 1011 G1 Tablet     | [1a00258de3](https://linux-hardware.org/?probe=1a00258de3) | Nov 29, 2022 |
| MSI           | GF75 Thin 9SC               | [50a779c35d](https://linux-hardware.org/?probe=50a779c35d) | Nov 29, 2022 |
| HP            | ProBook 450 G8              | [eec30c7857](https://linux-hardware.org/?probe=eec30c7857) | Nov 29, 2022 |
| Acer          | Aspire A315-22              | [c52689296b](https://linux-hardware.org/?probe=c52689296b) | Nov 29, 2022 |
| Dell          | Latitude 7480               | [409c2f27c8](https://linux-hardware.org/?probe=409c2f27c8) | Nov 28, 2022 |
| HP            | ProBook 650 G1              | [f038c3cc67](https://linux-hardware.org/?probe=f038c3cc67) | Nov 28, 2022 |
| HP            | EliteBook Folio 9480m       | [7f9d229259](https://linux-hardware.org/?probe=7f9d229259) | Nov 28, 2022 |
| Dell          | Inspiron 15-3552            | [03a1a706d1](https://linux-hardware.org/?probe=03a1a706d1) | Nov 28, 2022 |
| Apple         | MacBookPro9,2               | [e87a096d85](https://linux-hardware.org/?probe=e87a096d85) | Nov 27, 2022 |
| HP            | Laptop 15-db0xxx            | [fada18bff7](https://linux-hardware.org/?probe=fada18bff7) | Nov 27, 2022 |
| ASUSTek       | T100TA                      | [2734591eb0](https://linux-hardware.org/?probe=2734591eb0) | Nov 26, 2022 |
| Acer          | Swift SF314-57              | [ba4ed6c5f4](https://linux-hardware.org/?probe=ba4ed6c5f4) | Nov 26, 2022 |
| Gigabyte      | AORUS 5 SE                  | [d9e1ceb3c1](https://linux-hardware.org/?probe=d9e1ceb3c1) | Nov 26, 2022 |
| Apple         | MacBookPro9,2               | [9e465f741d](https://linux-hardware.org/?probe=9e465f741d) | Nov 26, 2022 |
| Sony          | VGN-NS110E                  | [5ccfd5f230](https://linux-hardware.org/?probe=5ccfd5f230) | Nov 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [682993f58f](https://linux-hardware.org/?probe=682993f58f) | Nov 25, 2022 |
| Sony          | VGN-NS110E                  | [999e5f4ed6](https://linux-hardware.org/?probe=999e5f4ed6) | Nov 25, 2022 |
| ASUSTek       | G73Jh                       | [575f0a8c5a](https://linux-hardware.org/?probe=575f0a8c5a) | Nov 24, 2022 |
| Dell          | XPS 15 9520                 | [344721473a](https://linux-hardware.org/?probe=344721473a) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | [4f6911ae2c](https://linux-hardware.org/?probe=4f6911ae2c) | Nov 23, 2022 |
| Dell          | Latitude E6530              | [71623eedf3](https://linux-hardware.org/?probe=71623eedf3) | Nov 23, 2022 |
| Dell          | Inspiron 5567               | [96e8bf5249](https://linux-hardware.org/?probe=96e8bf5249) | Nov 23, 2022 |
| Toshiba       | PORTEGE R930                | [9e5d02ab88](https://linux-hardware.org/?probe=9e5d02ab88) | Nov 23, 2022 |
| Lenovo        | Y520-15IKBA 80WY            | [c1cccb2b2a](https://linux-hardware.org/?probe=c1cccb2b2a) | Nov 22, 2022 |
| Gigabyte      | AORUS 5 SE                  | [c88614e7f3](https://linux-hardware.org/?probe=c88614e7f3) | Nov 22, 2022 |
| AZW           | BT3 PRO                     | [ee8fc8db42](https://linux-hardware.org/?probe=ee8fc8db42) | Nov 22, 2022 |
| AZW           | BT3 PRO                     | [48047be395](https://linux-hardware.org/?probe=48047be395) | Nov 21, 2022 |
| Dell          | XPS 15 7590                 | [5360c65b7a](https://linux-hardware.org/?probe=5360c65b7a) | Nov 21, 2022 |
| Apple         | MacBookPro5,4               | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| ASUSTek       | GL552VW                     | [66f37717f6](https://linux-hardware.org/?probe=66f37717f6) | Nov 21, 2022 |
| Toshiba       | TECRA R940                  | [0f231b600d](https://linux-hardware.org/?probe=0f231b600d) | Nov 20, 2022 |
| Dell          | Latitude 5285               | [145341899a](https://linux-hardware.org/?probe=145341899a) | Nov 20, 2022 |
| HP            | ZBook 15 G4                 | [ad20223c29](https://linux-hardware.org/?probe=ad20223c29) | Nov 20, 2022 |
| Acer          | Aspire A317-51              | [43c8f9b08b](https://linux-hardware.org/?probe=43c8f9b08b) | Nov 19, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d4bb2f3867](https://linux-hardware.org/?probe=d4bb2f3867) | Nov 19, 2022 |
| Acer          | Aspire A317-51              | [a4a3dabbb4](https://linux-hardware.org/?probe=a4a3dabbb4) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [7ac338ce0d](https://linux-hardware.org/?probe=7ac338ce0d) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [50bd30f30d](https://linux-hardware.org/?probe=50bd30f30d) | Nov 19, 2022 |
| Lenovo        | ThinkPad T480 20L6S09E00    | [cd7fb0289f](https://linux-hardware.org/?probe=cd7fb0289f) | Nov 19, 2022 |
| Apple         | MacBookPro8,2               | [6fb901efa3](https://linux-hardware.org/?probe=6fb901efa3) | Nov 19, 2022 |
| Alienware     | m17                         | [e3e14a271a](https://linux-hardware.org/?probe=e3e14a271a) | Nov 17, 2022 |
| Toshiba       | Satellite A200              | [5648565f20](https://linux-hardware.org/?probe=5648565f20) | Nov 17, 2022 |
| Toshiba       | Satellite A200              | [7c530443f0](https://linux-hardware.org/?probe=7c530443f0) | Nov 17, 2022 |
| Dell          | XPS 15 9520                 | [ba362db69a](https://linux-hardware.org/?probe=ba362db69a) | Nov 16, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [d0bcf66bd1](https://linux-hardware.org/?probe=d0bcf66bd1) | Nov 16, 2022 |
| Dell          | Latitude E6520              | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| Alienware     | m17                         | [4140c68e95](https://linux-hardware.org/?probe=4140c68e95) | Nov 15, 2022 |
| Dell          | XPS 15 9520                 | [5fa04fae9e](https://linux-hardware.org/?probe=5fa04fae9e) | Nov 15, 2022 |
| Razer         | Blade Stealth               | [52ac7c7393](https://linux-hardware.org/?probe=52ac7c7393) | Nov 14, 2022 |
| Razer         | Blade Stealth               | [6f8078d5ec](https://linux-hardware.org/?probe=6f8078d5ec) | Nov 14, 2022 |
| Acer          | E1-532P                     | [1e666341f7](https://linux-hardware.org/?probe=1e666341f7) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [4121297e16](https://linux-hardware.org/?probe=4121297e16) | Nov 14, 2022 |
| Lenovo        | ThinkPad L490 20Q5CTO1WW    | [575d67b22c](https://linux-hardware.org/?probe=575d67b22c) | Nov 13, 2022 |
| Dell          | Inspiron 7520               | [8d1eaa5bf0](https://linux-hardware.org/?probe=8d1eaa5bf0) | Nov 10, 2022 |
| Google        | Droid                       | [e73c485f75](https://linux-hardware.org/?probe=e73c485f75) | Nov 10, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [94c1e12b90](https://linux-hardware.org/?probe=94c1e12b90) | Nov 09, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [431acad421](https://linux-hardware.org/?probe=431acad421) | Nov 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fba0c1a99c](https://linux-hardware.org/?probe=fba0c1a99c) | Nov 09, 2022 |
| Google        | Cyan                        | [814cdea7b3](https://linux-hardware.org/?probe=814cdea7b3) | Nov 08, 2022 |
| HP            | ProBook 650 G1              | [f0e91578b7](https://linux-hardware.org/?probe=f0e91578b7) | Nov 07, 2022 |
| Lenovo        | ThinkPad T420 4236V6S       | [a1d8f7bbca](https://linux-hardware.org/?probe=a1d8f7bbca) | Nov 07, 2022 |
| HP            | ENVY 17                     | [83906ebbfc](https://linux-hardware.org/?probe=83906ebbfc) | Nov 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [3febd144a4](https://linux-hardware.org/?probe=3febd144a4) | Nov 07, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [5cee459a0f](https://linux-hardware.org/?probe=5cee459a0f) | Nov 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [caf9066e2a](https://linux-hardware.org/?probe=caf9066e2a) | Nov 06, 2022 |
| Timi          | RedmiBook Pro 15            | [226d8de9bb](https://linux-hardware.org/?probe=226d8de9bb) | Nov 04, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [fab8493ac2](https://linux-hardware.org/?probe=fab8493ac2) | Nov 04, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [a2362fefe3](https://linux-hardware.org/?probe=a2362fefe3) | Nov 04, 2022 |
| Dell          | G3 3590                     | [03fec4f4d4](https://linux-hardware.org/?probe=03fec4f4d4) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [608c7f56e6](https://linux-hardware.org/?probe=608c7f56e6) | Nov 03, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | [e4d29df724](https://linux-hardware.org/?probe=e4d29df724) | Nov 02, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Stream Laptop 14-cb1XX      | [18db43ffed](https://linux-hardware.org/?probe=18db43ffed) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| Toshiba       | Satellite A200              | [296d9a0f38](https://linux-hardware.org/?probe=296d9a0f38) | Oct 31, 2022 |
| Toshiba       | Satellite A200              | [07a165b373](https://linux-hardware.org/?probe=07a165b373) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| HP            | ProBook 650 G1              | [54c64976ee](https://linux-hardware.org/?probe=54c64976ee) | Oct 30, 2022 |
| HP            | Pavilion dv7                | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [ce9df2cf8f](https://linux-hardware.org/?probe=ce9df2cf8f) | Oct 29, 2022 |
| Dell          | Precision 7520              | [30f6ad7a26](https://linux-hardware.org/?probe=30f6ad7a26) | Oct 29, 2022 |
| Dell          | Precision 7520              | [b81923dbd2](https://linux-hardware.org/?probe=b81923dbd2) | Oct 29, 2022 |
| HP            | G60                         | [e9af8a9e61](https://linux-hardware.org/?probe=e9af8a9e61) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [2829b0b18f](https://linux-hardware.org/?probe=2829b0b18f) | Oct 28, 2022 |
| Acer          | AOD257                      | [d3efba72cc](https://linux-hardware.org/?probe=d3efba72cc) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Acer          | AOD257                      | [c399f9db2b](https://linux-hardware.org/?probe=c399f9db2b) | Oct 27, 2022 |
| Apple         | MacBookAir5,2               | [f3c9ea3e12](https://linux-hardware.org/?probe=f3c9ea3e12) | Oct 27, 2022 |
| Dell          | Precision 5570              | [67d7b55dab](https://linux-hardware.org/?probe=67d7b55dab) | Oct 26, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [c19eaa0502](https://linux-hardware.org/?probe=c19eaa0502) | Oct 26, 2022 |
| ASUSTek       | UX430UAR                    | [07d56a833e](https://linux-hardware.org/?probe=07d56a833e) | Oct 25, 2022 |
| Panasonic     | CFSX4-1                     | [2ddae6e0e1](https://linux-hardware.org/?probe=2ddae6e0e1) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| Acer          | TravelMate B311-31          | [010dd1e876](https://linux-hardware.org/?probe=010dd1e876) | Oct 24, 2022 |
| Alienware     | 18                          | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | [33bef6bb6f](https://linux-hardware.org/?probe=33bef6bb6f) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | [da114c9e74](https://linux-hardware.org/?probe=da114c9e74) | Oct 23, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [77bbf74390](https://linux-hardware.org/?probe=77bbf74390) | Oct 22, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [acbf2e94c1](https://linux-hardware.org/?probe=acbf2e94c1) | Oct 22, 2022 |
| Lenovo        | G50-30 80G0                 | [32a9b1de4f](https://linux-hardware.org/?probe=32a9b1de4f) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [66fae864f2](https://linux-hardware.org/?probe=66fae864f2) | Oct 22, 2022 |
| Apple         | MacBookPro14,1              | [2a02bdc30d](https://linux-hardware.org/?probe=2a02bdc30d) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eaff8befe8](https://linux-hardware.org/?probe=eaff8befe8) | Oct 22, 2022 |
| Sony          | VPCEH3QFX                   | [def39e1ddd](https://linux-hardware.org/?probe=def39e1ddd) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [bfdfd5d11e](https://linux-hardware.org/?probe=bfdfd5d11e) | Oct 21, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | [77de0f71bd](https://linux-hardware.org/?probe=77de0f71bd) | Oct 21, 2022 |
| HP            | EliteBook 840 G1            | [837845f259](https://linux-hardware.org/?probe=837845f259) | Oct 20, 2022 |
| MSI           | GP66 Leopard 11UH           | [9485d1e744](https://linux-hardware.org/?probe=9485d1e744) | Oct 20, 2022 |
| HP            | ENVY TS 15                  | [b27ee147cf](https://linux-hardware.org/?probe=b27ee147cf) | Oct 20, 2022 |
| HP            | EliteBook 840 G1            | [1f8284bf7d](https://linux-hardware.org/?probe=1f8284bf7d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6271fbb0fb](https://linux-hardware.org/?probe=6271fbb0fb) | Oct 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00fece9d77](https://linux-hardware.org/?probe=00fece9d77) | Oct 18, 2022 |
| Valve         | Jupiter                     | [1e000a30c5](https://linux-hardware.org/?probe=1e000a30c5) | Oct 18, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | [e480e5d6ae](https://linux-hardware.org/?probe=e480e5d6ae) | Oct 18, 2022 |
| Apple         | MacBookPro5,4               | [2a51555c53](https://linux-hardware.org/?probe=2a51555c53) | Oct 18, 2022 |
| Acer          | Aspire one                  | [fced25613a](https://linux-hardware.org/?probe=fced25613a) | Oct 18, 2022 |
| HP            | Laptop 15-db0xxx            | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| HP            | ProBook 440 G6              | [def45e1980](https://linux-hardware.org/?probe=def45e1980) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Google        | Coral                       | [a1811601a0](https://linux-hardware.org/?probe=a1811601a0) | Oct 15, 2022 |
| Google        | Coral                       | [93a674ea2b](https://linux-hardware.org/?probe=93a674ea2b) | Oct 15, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7d6c345f35](https://linux-hardware.org/?probe=7d6c345f35) | Oct 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS4U300    | [bcdea92f5d](https://linux-hardware.org/?probe=bcdea92f5d) | Oct 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS4U300    | [1a5aa81d1a](https://linux-hardware.org/?probe=1a5aa81d1a) | Oct 15, 2022 |
| Dell          | Latitude 3340               | [d99dbe3b99](https://linux-hardware.org/?probe=d99dbe3b99) | Oct 14, 2022 |
| Valve         | Jupiter                     | [2d38b191e7](https://linux-hardware.org/?probe=2d38b191e7) | Oct 14, 2022 |
| Dell          | Latitude E6400              | [3516901ea0](https://linux-hardware.org/?probe=3516901ea0) | Oct 14, 2022 |
| Dell          | Precision M4800             | [9c9ad77c56](https://linux-hardware.org/?probe=9c9ad77c56) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| ASUSTek       | K53E                        | [ee3acd2da1](https://linux-hardware.org/?probe=ee3acd2da1) | Oct 11, 2022 |
| ASUSTek       | K53E                        | [8a8058467a](https://linux-hardware.org/?probe=8a8058467a) | Oct 11, 2022 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [89ee3db150](https://linux-hardware.org/?probe=89ee3db150) | Oct 11, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | [18c02300b9](https://linux-hardware.org/?probe=18c02300b9) | Oct 11, 2022 |
| Alienware     | Area-51m                    | [a227d548e4](https://linux-hardware.org/?probe=a227d548e4) | Oct 11, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [71c926fc14](https://linux-hardware.org/?probe=71c926fc14) | Oct 11, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [b8e434e4db](https://linux-hardware.org/?probe=b8e434e4db) | Oct 10, 2022 |
| Apple         | MacBookPro6,2               | [8315e5ed7d](https://linux-hardware.org/?probe=8315e5ed7d) | Oct 10, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [db3419c5de](https://linux-hardware.org/?probe=db3419c5de) | Oct 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [1f013f181d](https://linux-hardware.org/?probe=1f013f181d) | Oct 09, 2022 |
| HP            | Laptop 15-da2xxx            | [b699753cc6](https://linux-hardware.org/?probe=b699753cc6) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK E752               | [b7c6acd46c](https://linux-hardware.org/?probe=b7c6acd46c) | Oct 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [b31ac1623d](https://linux-hardware.org/?probe=b31ac1623d) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [9eaff58099](https://linux-hardware.org/?probe=9eaff58099) | Oct 05, 2022 |
| HP            | Pavilion 17                 | [f7626421b2](https://linux-hardware.org/?probe=f7626421b2) | Oct 05, 2022 |
| Dell          | XPS 9320                    | [c4888023c3](https://linux-hardware.org/?probe=c4888023c3) | Oct 04, 2022 |
| Acer          | Aspire A315-21              | [48901aff3f](https://linux-hardware.org/?probe=48901aff3f) | Oct 04, 2022 |
| Valve         | Jupiter                     | [6bc437ef3d](https://linux-hardware.org/?probe=6bc437ef3d) | Oct 03, 2022 |
| Google        | Droid                       | [40550baeb8](https://linux-hardware.org/?probe=40550baeb8) | Oct 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | [b2d146f923](https://linux-hardware.org/?probe=b2d146f923) | Oct 01, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [5c5353c8b6](https://linux-hardware.org/?probe=5c5353c8b6) | Oct 01, 2022 |
| Dell          | Latitude E4300              | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| Lenovo        | ThinkPad T480 20L5001FUS    | [a7e0da7aa4](https://linux-hardware.org/?probe=a7e0da7aa4) | Sep 30, 2022 |
| HP            | Notebook                    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| Dell          | Latitude E6430              | [f3e5e0005d](https://linux-hardware.org/?probe=f3e5e0005d) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| Gigabyte      | AORUS 15P YD                | [61e297be71](https://linux-hardware.org/?probe=61e297be71) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fb2de59c3f](https://linux-hardware.org/?probe=fb2de59c3f) | Sep 27, 2022 |
| ASUSTek       | G73Jh                       | [e5405dd3d8](https://linux-hardware.org/?probe=e5405dd3d8) | Sep 27, 2022 |
| ASUSTek       | G73Jh                       | [ac96a56edf](https://linux-hardware.org/?probe=ac96a56edf) | Sep 27, 2022 |
| HP            | Laptop 15-dw3xxx            | [d7dcd834e2](https://linux-hardware.org/?probe=d7dcd834e2) | Sep 27, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [4f58ff1174](https://linux-hardware.org/?probe=4f58ff1174) | Sep 26, 2022 |
| Acer          | Aspire A515-55              | [a9ac678198](https://linux-hardware.org/?probe=a9ac678198) | Sep 26, 2022 |
| ASUSTek       | K52N                        | [8d7b00011f](https://linux-hardware.org/?probe=8d7b00011f) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| MSI           | GS65 Stealth 9SE            | [0c8e0eb1f5](https://linux-hardware.org/?probe=0c8e0eb1f5) | Sep 26, 2022 |
| MSI           | GE75 Raider 8SF             | [094a9b115b](https://linux-hardware.org/?probe=094a9b115b) | Sep 26, 2022 |
| Apple         | MacBookPro14,1              | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Dell          | Inspiron 1440               | [c928a944c0](https://linux-hardware.org/?probe=c928a944c0) | Sep 24, 2022 |
| Dell          | Latitude E5510              | [04f4e9a803](https://linux-hardware.org/?probe=04f4e9a803) | Sep 24, 2022 |
| HP            | Notebook                    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| Lenovo        | ThinkPad T61p 64575KU       | [a5e3ca7c25](https://linux-hardware.org/?probe=a5e3ca7c25) | Sep 23, 2022 |
| Valve         | Jupiter                     | [ca6d2abcd9](https://linux-hardware.org/?probe=ca6d2abcd9) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| Acer          | Aspire A515-55              | [fb1cce613c](https://linux-hardware.org/?probe=fb1cce613c) | Sep 22, 2022 |
| ASUSTek       | G73Jh                       | [58b83fee74](https://linux-hardware.org/?probe=58b83fee74) | Sep 22, 2022 |
| ASUSTek       | G73Jh                       | [e40a8996c4](https://linux-hardware.org/?probe=e40a8996c4) | Sep 22, 2022 |
| Razer         | Blade                       | [c835fe2f90](https://linux-hardware.org/?probe=c835fe2f90) | Sep 21, 2022 |
| Dell          | Latitude E4310              | [06dc3db422](https://linux-hardware.org/?probe=06dc3db422) | Sep 20, 2022 |
| Valve         | Jupiter                     | [090e33f643](https://linux-hardware.org/?probe=090e33f643) | Sep 20, 2022 |
| Acer          | Aspire E5-532               | [1d0f80e0f1](https://linux-hardware.org/?probe=1d0f80e0f1) | Sep 20, 2022 |
| Acer          | Aspire E5-532               | [f349ec9700](https://linux-hardware.org/?probe=f349ec9700) | Sep 20, 2022 |
| Acer          | Nitro AN517-51              | [7bd22a5e38](https://linux-hardware.org/?probe=7bd22a5e38) | Sep 20, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [66596e407c](https://linux-hardware.org/?probe=66596e407c) | Sep 19, 2022 |
| ASUSTek       | GL502VMK                    | [9776f2c20c](https://linux-hardware.org/?probe=9776f2c20c) | Sep 19, 2022 |
| Dell          | Latitude E6540              | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [b707354c65](https://linux-hardware.org/?probe=b707354c65) | Sep 18, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [2e1e251503](https://linux-hardware.org/?probe=2e1e251503) | Sep 18, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [5f56e8b10f](https://linux-hardware.org/?probe=5f56e8b10f) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50da0a8acf](https://linux-hardware.org/?probe=50da0a8acf) | Sep 18, 2022 |
| Dell          | XPS 15 7590                 | [a191bd2a9f](https://linux-hardware.org/?probe=a191bd2a9f) | Sep 18, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 358       | 12.54%  |
| Ubuntu 18.04       | 200       | 7.01%   |
| Ubuntu 22.04       | 141       | 4.94%   |
| Pop!_OS 22.04      | 65        | 2.28%   |
| Zorin 16           | 64        | 2.24%   |
| OpenMandriva 4.3   | 55        | 1.93%   |
| Arch Rolling       | 52        | 1.82%   |
| Linux Mint 20.3    | 51        | 1.79%   |
| Debian 11          | 51        | 1.79%   |
| Manjaro            | 50        | 1.75%   |
| KDE neon 20.04     | 50        | 1.75%   |
| OpenMandriva 4.2   | 49        | 1.72%   |
| Arch               | 48        | 1.68%   |
| Zorin 15           | 43        | 1.51%   |
| Xubuntu 20.04      | 43        | 1.51%   |
| Ubuntu 19.10       | 39        | 1.37%   |
| Linux Mint 19.3    | 39        | 1.37%   |
| Pop!_OS 21.04      | 38        | 1.33%   |
| Linux Mint 21.1    | 38        | 1.33%   |
| ArcoLinux Rolling  | 37        | 1.3%    |
| Pop!_OS 20.04      | 36        | 1.26%   |
| Fedora 37          | 35        | 1.23%   |
| Fedora 35          | 35        | 1.23%   |
| Fedora 38          | 34        | 1.19%   |
| Ubuntu 21.10       | 33        | 1.16%   |
| Ubuntu 20.10       | 31        | 1.09%   |
| Linux Mint 21      | 31        | 1.09%   |
| Linux Mint 20.1    | 31        | 1.09%   |
| Linux Mint 20.2    | 30        | 1.05%   |
| Pop!_OS 20.10      | 29        | 1.02%   |
| Ubuntu 19.04       | 27        | 0.95%   |
| Linux Mint 20      | 26        | 0.91%   |
| Fedora 32          | 24        | 0.84%   |
| Ubuntu 21.04       | 23        | 0.81%   |
| Pop!_OS 21.10      | 23        | 0.81%   |
| OpenMandriva 23.03 | 23        | 0.81%   |
| OpenMandriva 23.01 | 23        | 0.81%   |
| Fedora 36          | 22        | 0.77%   |
| Fedora 33          | 22        | 0.77%   |
| Ubuntu 22.10       | 21        | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 865       | 31.81%  |
| Linux Mint    | 248       | 9.12%   |
| Fedora        | 194       | 7.13%   |
| Pop!_OS       | 183       | 6.73%   |
| OpenMandriva  | 162       | 5.96%   |
| Zorin         | 112       | 4.12%   |
| Manjaro       | 103       | 3.79%   |
| Arch          | 95        | 3.49%   |
| Debian        | 93        | 3.42%   |
| Xubuntu       | 70        | 2.57%   |
| KDE neon      | 63        | 2.32%   |
| Kubuntu       | 52        | 1.91%   |
| ArcoLinux     | 40        | 1.47%   |
| SteamOS       | 37        | 1.36%   |
| ROSA          | 36        | 1.32%   |
| Gentoo        | 31        | 1.14%   |
| Kali          | 26        | 0.96%   |
| Elementary    | 24        | 0.88%   |
| EndeavourOS   | 23        | 0.85%   |
| Lubuntu       | 22        | 0.81%   |
| openSUSE      | 20        | 0.74%   |
| MX            | 18        | 0.66%   |
| Clear Linux   | 18        | 0.66%   |
| Endless       | 17        | 0.63%   |
| BlackPanther  | 16        | 0.59%   |
| Garuda Linux  | 12        | 0.44%   |
| Ubuntu Unity  | 11        | 0.4%    |
| Ubuntu Budgie | 11        | 0.4%    |
| Ubuntu MATE   | 9         | 0.33%   |
| Peppermint    | 9         | 0.33%   |
| LMDE          | 8         | 0.29%   |
| Parrot        | 7         | 0.26%   |
| CentOS        | 6         | 0.22%   |
| Alpine        | 6         | 0.22%   |
| LinuxFX       | 5         | 0.18%   |
| Ubuntu Studio | 4         | 0.15%   |
| Nobara        | 4         | 0.15%   |
| NixOS         | 4         | 0.15%   |
| Artix         | 4         | 0.15%   |
| Xero          | 3         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 50        | 1.58%   |
| 5.10.14-desktop-1omv4002 | 47        | 1.48%   |
| 5.4.0-42-generic         | 45        | 1.42%   |
| 5.11.0-27-generic        | 42        | 1.33%   |
| 5.15.0-56-generic        | 32        | 1.01%   |
| 5.3.0-40-generic         | 27        | 0.85%   |
| 5.15.0-52-generic        | 24        | 0.76%   |
| 6.2.6-desktop-1omv2390   | 23        | 0.73%   |
| 5.4.0-29-generic         | 23        | 0.73%   |
| 5.15.0-58-generic        | 23        | 0.73%   |
| 6.1.1-desktop-1omv2290   | 22        | 0.69%   |
| 5.4.0-52-generic         | 21        | 0.66%   |
| 5.4.0-40-generic         | 21        | 0.66%   |
| 5.0.0-37-generic         | 21        | 0.66%   |
| 5.8.0-7630-generic       | 20        | 0.63%   |
| 5.4.0-58-generic         | 20        | 0.63%   |
| 5.3.0-46-generic         | 20        | 0.63%   |
| 5.4.0-48-generic         | 18        | 0.57%   |
| 5.4.0-45-generic         | 18        | 0.57%   |
| 6.2.6-76060206-generic   | 17        | 0.54%   |
| 5.15.0-41-generic        | 17        | 0.54%   |
| 5.13.0-valve36-1-neptune | 17        | 0.54%   |
| 5.15.0-71-generic        | 16        | 0.5%    |
| 5.15.0-46-generic        | 16        | 0.5%    |
| 5.4.0-37-generic         | 15        | 0.47%   |
| 5.4.0-26-generic         | 15        | 0.47%   |
| 5.15.0-47-generic        | 15        | 0.47%   |
| 5.13.0-7614-generic      | 15        | 0.47%   |
| 5.11.0-40-generic        | 15        | 0.47%   |
| 5.8.0-41-generic         | 14        | 0.44%   |
| 5.4.0-91-generic         | 14        | 0.44%   |
| 5.4.0-47-generic         | 14        | 0.44%   |
| 5.3.0-42-generic         | 14        | 0.44%   |
| 5.13.0-30-generic        | 14        | 0.44%   |
| 5.11.0-38-generic        | 14        | 0.44%   |
| 5.8.0-43-generic         | 13        | 0.41%   |
| 5.4.0-72-generic         | 13        | 0.41%   |
| 5.4.0-54-generic         | 13        | 0.41%   |
| 5.3.0-51-generic         | 13        | 0.41%   |
| 5.11.0-34-generic        | 13        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 475       | 16.02%  |
| 5.15.0  | 248       | 8.36%   |
| 5.11.0  | 178       | 6%      |
| 5.13.0  | 162       | 5.46%   |
| 5.8.0   | 147       | 4.96%   |
| 5.3.0   | 144       | 4.86%   |
| 4.15.0  | 139       | 4.69%   |
| 5.19.0  | 96        | 3.24%   |
| 5.0.0   | 88        | 2.97%   |
| 5.10.0  | 67        | 2.26%   |
| 5.16.7  | 52        | 1.75%   |
| 5.10.14 | 48        | 1.62%   |
| 4.18.0  | 48        | 1.62%   |
| 6.2.6   | 42        | 1.42%   |
| 6.1.1   | 25        | 0.84%   |
| 6.2.0   | 23        | 0.78%   |
| 6.1.0   | 22        | 0.74%   |
| 4.19.0  | 22        | 0.74%   |
| 5.14.0  | 15        | 0.51%   |
| 6.0.0   | 13        | 0.44%   |
| 5.17.5  | 12        | 0.4%    |
| 6.0.6   | 11        | 0.37%   |
| 5.15.5  | 11        | 0.37%   |
| 4.18.16 | 11        | 0.37%   |
| 6.2.9   | 10        | 0.34%   |
| 6.2.10  | 10        | 0.34%   |
| 6.0.12  | 10        | 0.34%   |
| 5.16.13 | 10        | 0.34%   |
| 5.9.16  | 9         | 0.3%    |
| 5.9.11  | 9         | 0.3%    |
| 5.18.0  | 9         | 0.3%    |
| 5.15.11 | 9         | 0.3%    |
| 6.2.15  | 8         | 0.27%   |
| 5.17.9  | 8         | 0.27%   |
| 5.17.0  | 8         | 0.27%   |
| 5.16.0  | 8         | 0.27%   |
| 5.11.12 | 8         | 0.27%   |
| 4.9.60  | 8         | 0.27%   |
| 4.9.20  | 8         | 0.27%   |
| 6.3.5   | 7         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 517       | 17.74%  |
| 5.15    | 343       | 11.77%  |
| 5.11    | 203       | 6.97%   |
| 5.8     | 197       | 6.76%   |
| 5.13    | 182       | 6.25%   |
| 5.10    | 161       | 5.53%   |
| 5.3     | 153       | 5.25%   |
| 4.15    | 140       | 4.8%    |
| 5.19    | 120       | 4.12%   |
| 6.2     | 117       | 4.02%   |
| 5.16    | 103       | 3.53%   |
| 5.0     | 90        | 3.09%   |
| 6.1     | 78        | 2.68%   |
| 6.0     | 71        | 2.44%   |
| 4.18    | 59        | 2.02%   |
| 5.17    | 47        | 1.61%   |
| 5.9     | 44        | 1.51%   |
| 5.14    | 37        | 1.27%   |
| 5.18    | 35        | 1.2%    |
| 6.3     | 32        | 1.1%    |
| 5.12    | 31        | 1.06%   |
| 4.19    | 29        | 1%      |
| 5.6     | 26        | 0.89%   |
| 4.9     | 24        | 0.82%   |
| 5.7     | 23        | 0.79%   |
| 6.4     | 14        | 0.48%   |
| 5.5     | 13        | 0.45%   |
| 4.4     | 7         | 0.24%   |
| 3.10    | 3         | 0.1%    |
| 5.2     | 2         | 0.07%   |
| 5.1     | 2         | 0.07%   |
| 4.8     | 2         | 0.07%   |
| 4.20    | 2         | 0.07%   |
| 4.14    | 2         | 0.07%   |
| 4.1     | 2         | 0.07%   |
| 4.16    | 1         | 0.03%   |
| 4.13    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2520      | 96.92%  |
| i686    | 77        | 2.96%   |
| armv7l  | 2         | 0.08%   |
| aarch64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| GNOME                | 1193      | 43.72%  |
| KDE5                 | 456       | 16.71%  |
| Unknown              | 318       | 11.65%  |
| XFCE                 | 215       | 7.88%   |
| X-Cinnamon           | 192       | 7.04%   |
| KDE                  | 75        | 2.75%   |
| MATE                 | 60        | 2.2%    |
| Cinnamon             | 32        | 1.17%   |
| KDE4                 | 25        | 0.92%   |
| LXQt                 | 23        | 0.84%   |
| Pantheon             | 22        | 0.81%   |
| i3                   | 22        | 0.81%   |
| LXDE                 | 15        | 0.55%   |
| Budgie               | 15        | 0.55%   |
| Unity                | 14        | 0.51%   |
| GNOME Flashback      | 10        | 0.37%   |
| DWM                  | 6         | 0.22%   |
| Deepin               | 5         | 0.18%   |
| sway                 | 4         | 0.15%   |
| qtile                | 4         | 0.15%   |
| Enlightenment        | 4         | 0.15%   |
| xmonad               | 3         | 0.11%   |
| awesome              | 3         | 0.11%   |
| Hyprland             | 2         | 0.07%   |
| GNOME Classic        | 2         | 0.07%   |
| chadwm               | 2         | 0.07%   |
| xsession             | 1         | 0.04%   |
| wmaker-common        | 1         | 0.04%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.04%   |
| spectrwm             | 1         | 0.04%   |
| Jwm                  | 1         | 0.04%   |
| GNOME-Classic        | 1         | 0.04%   |
| bspwm                | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2058      | 76.56%  |
| Wayland | 422       | 15.7%   |
| Unknown | 177       | 6.58%   |
| Tty     | 30        | 1.12%   |
| Web     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1428      | 52.4%   |
| SDDM    | 384       | 14.09%  |
| GDM     | 285       | 10.46%  |
| GDM3    | 280       | 10.28%  |
| LightDM | 234       | 8.59%   |
| TDM     | 74        | 2.72%   |
| KDM     | 24        | 0.88%   |
| XDM     | 6         | 0.22%   |
| Ly      | 6         | 0.22%   |
| LXDM    | 3         | 0.11%   |
| LY-DM   | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_CA   | 1352      | 50.13%  |
| en_US   | 746       | 27.66%  |
| Unknown | 280       | 10.38%  |
| fr_CA   | 186       | 6.9%    |
| C       | 54        | 2%      |
| fr_FR   | 26        | 0.96%   |
| en_GB   | 12        | 0.44%   |
| POSIX   | 4         | 0.15%   |
| en_AU   | 4         | 0.15%   |
| C.UTF8  | 4         | 0.15%   |
| pt_BR   | 3         | 0.11%   |
| es_ES   | 3         | 0.11%   |
| en_IN   | 3         | 0.11%   |
| zh_CN   | 2         | 0.07%   |
| uk_UA   | 2         | 0.07%   |
| pl_PL   | 2         | 0.07%   |
| hu_HU   | 2         | 0.07%   |
| ru_RU   | 1         | 0.04%   |
| ro_RO   | 1         | 0.04%   |
| pa_IN   | 1         | 0.04%   |
| hr_HR   | 1         | 0.04%   |
| ga_IE   | 1         | 0.04%   |
| es_CL   | 1         | 0.04%   |
| en_ZA   | 1         | 0.04%   |
| en_NZ   | 1         | 0.04%   |
| en_IE   | 1         | 0.04%   |
| en_FI   | 1         | 0.04%   |
| de_DE   | 1         | 0.04%   |
| co_FR   | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1377      | 51.57%  |
| EFI  | 1293      | 48.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2000      | 74.74%  |
| Btrfs   | 276       | 10.31%  |
| Overlay | 223       | 8.33%   |
| Unknown | 79        | 2.95%   |
| Tmpfs   | 32        | 1.2%    |
| Zfs     | 26        | 0.97%   |
| Xfs     | 26        | 0.97%   |
| Ext2    | 8         | 0.3%    |
| Aufs    | 3         | 0.11%   |
| Ext3    | 2         | 0.07%   |
| F2fs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1493      | 55.81%  |
| GPT     | 929       | 34.73%  |
| MBR     | 253       | 9.46%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2322      | 87.59%  |
| Yes       | 329       | 12.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2017      | 76.23%  |
| Yes       | 629       | 23.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 535       | 20.59%  |
| Dell                           | 501       | 19.28%  |
| Hewlett-Packard                | 421       | 16.2%   |
| ASUSTek Computer               | 286       | 11.01%  |
| Acer                           | 265       | 10.2%   |
| Apple                          | 109       | 4.2%    |
| Toshiba                        | 100       | 3.85%   |
| MSI                            | 70        | 2.69%   |
| Sony                           | 36        | 1.39%   |
| Valve                          | 35        | 1.35%   |
| Google                         | 31        | 1.19%   |
| Samsung Electronics            | 22        | 0.85%   |
| Alienware                      | 22        | 0.85%   |
| System76                       | 21        | 0.81%   |
| Panasonic                      | 18        | 0.69%   |
| Gateway                        | 16        | 0.62%   |
| Unknown                        | 12        | 0.46%   |
| Gigabyte Technology            | 9         | 0.35%   |
| Fujitsu                        | 9         | 0.35%   |
| Razer                          | 8         | 0.31%   |
| Framework                      | 8         | 0.31%   |
| Notebook                       | 5         | 0.19%   |
| HUAWEI                         | 5         | 0.19%   |
| LG Electronics                 | 4         | 0.15%   |
| EUROCOM                        | 4         | 0.15%   |
| Intel Client Systems           | 3         | 0.12%   |
| GPU Company                    | 3         | 0.12%   |
| eMachines                      | 3         | 0.12%   |
| Purism                         | 2         | 0.08%   |
| Motion Computing               | 2         | 0.08%   |
| Matsushita Electric Industrial | 2         | 0.08%   |
| Intel                          | 2         | 0.08%   |
| Getac                          | 2         | 0.08%   |
| Datto                          | 2         | 0.08%   |
| BOSGAME                        | 2         | 0.08%   |
| AZW                            | 2         | 0.08%   |
| Xplore                         | 1         | 0.04%   |
| VIT                            | 1         | 0.04%   |
| Timi                           | 1         | 0.04%   |
| Teclast                        | 1         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Valve Jupiter          | 35        | 1.35%   |
| HP NOTEBOOK            | 23        | 0.89%   |
| Unknown                | 21        | 0.81%   |
| HP Pavilion g6         | 18        | 0.69%   |
| Acer Aspire A315-21    | 15        | 0.58%   |
| Dell Latitude E6420    | 14        | 0.54%   |
| Dell XPS 15 7590       | 13        | 0.5%    |
| Dell Latitude E6410    | 13        | 0.5%    |
| HP Pavilion dv6        | 12        | 0.46%   |
| Dell XPS 15 9500       | 12        | 0.46%   |
| Apple MacBookPro8,1    | 12        | 0.46%   |
| HP Pavilion 15         | 11        | 0.42%   |
| Apple MacBookPro9,2    | 11        | 0.42%   |
| HP Pavilion Notebook   | 10        | 0.38%   |
| HP EliteBook 8460p     | 10        | 0.38%   |
| Dell XPS 13 9310       | 9         | 0.35%   |
| Apple MacBookPro5,5    | 9         | 0.35%   |
| Toshiba Satellite A200 | 8         | 0.31%   |
| HP Pavilion dv7        | 8         | 0.31%   |
| HP Laptop 15-db0xxx    | 8         | 0.31%   |
| Dell Latitude E6540    | 8         | 0.31%   |
| Dell Latitude 7490     | 8         | 0.31%   |
| Dell Inspiron 1545     | 8         | 0.31%   |
| Acer Aspire A315-42    | 8         | 0.31%   |
| HP EliteBook 840 G3    | 7         | 0.27%   |
| Dell XPS 15 9570       | 7         | 0.27%   |
| Dell XPS 15 9560       | 7         | 0.27%   |
| Dell Latitude E6430    | 7         | 0.27%   |
| Dell Latitude D830     | 7         | 0.27%   |
| Acer Aspire 5742       | 7         | 0.27%   |
| Toshiba Satellite C650 | 6         | 0.23%   |
| HP Laptop 14-fq0xxx    | 6         | 0.23%   |
| HP G60                 | 6         | 0.23%   |
| HP EliteBook 8570w     | 6         | 0.23%   |
| HP EliteBook 8470p     | 6         | 0.23%   |
| HP EliteBook 840 G5    | 6         | 0.23%   |
| HP EliteBook 840 G1    | 6         | 0.23%   |
| HP 2000                | 6         | 0.23%   |
| Dell XPS 13 9360       | 6         | 0.23%   |
| Dell Latitude E6440    | 6         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 359       | 13.82%  |
| Acer Aspire        | 204       | 7.85%   |
| Dell Latitude      | 180       | 6.93%   |
| Dell Inspiron      | 128       | 4.93%   |
| HP Pavilion        | 112       | 4.31%   |
| Dell XPS           | 105       | 4.04%   |
| Lenovo IdeaPad     | 89        | 3.43%   |
| Toshiba Satellite  | 84        | 3.23%   |
| HP EliteBook       | 84        | 3.23%   |
| ASUS VivoBook      | 62        | 2.39%   |
| HP Laptop          | 58        | 2.23%   |
| HP ProBook         | 45        | 1.73%   |
| Valve Jupiter      | 35        | 1.35%   |
| Dell Precision     | 34        | 1.31%   |
| ASUS ROG           | 31        | 1.19%   |
| HP Notebook        | 23        | 0.89%   |
| Acer Swift         | 22        | 0.85%   |
| Lenovo Legion      | 21        | 0.81%   |
| HP ENVY            | 21        | 0.81%   |
| Unknown            | 21        | 0.81%   |
| ASUS ZenBook       | 18        | 0.69%   |
| Dell Vostro        | 16        | 0.62%   |
| Apple MacBookPro8  | 16        | 0.62%   |
| Apple MacBookPro9  | 15        | 0.58%   |
| Acer Nitro         | 15        | 0.58%   |
| ASUS ASUS          | 14        | 0.54%   |
| Dell Studio        | 13        | 0.5%    |
| Apple MacBookPro5  | 13        | 0.5%    |
| HP Stream          | 12        | 0.46%   |
| HP Compaq          | 11        | 0.42%   |
| ASUS TUF           | 11        | 0.42%   |
| Apple MacBookPro11 | 11        | 0.42%   |
| Lenovo ThinkBook   | 10        | 0.38%   |
| Dell System        | 9         | 0.35%   |
| HP ZBook           | 8         | 0.31%   |
| HP Presario        | 8         | 0.31%   |
| Framework Laptop   | 8         | 0.31%   |
| Apple MacBookPro6  | 8         | 0.31%   |
| Toshiba TECRA      | 7         | 0.27%   |
| Razer Blade        | 7         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 228       | 8.78%   |
| 2012    | 227       | 8.74%   |
| 2020    | 220       | 8.47%   |
| 2019    | 202       | 7.78%   |
| 2018    | 196       | 7.54%   |
| 2017    | 177       | 6.81%   |
| 2013    | 171       | 6.58%   |
| 2010    | 156       | 6%      |
| 2021    | 149       | 5.74%   |
| 2014    | 149       | 5.74%   |
| 2016    | 134       | 5.16%   |
| 2022    | 124       | 4.77%   |
| 2008    | 122       | 4.7%    |
| 2015    | 120       | 4.62%   |
| 2009    | 90        | 3.46%   |
| 2007    | 73        | 2.81%   |
| 2006    | 28        | 1.08%   |
| 2023    | 18        | 0.69%   |
| 2005    | 8         | 0.31%   |
| Unknown | 4         | 0.15%   |
| 2004    | 2         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2598      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2397      | 91.45%  |
| Enabled  | 224       | 8.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2551      | 98.15%  |
| Yes  | 48        | 1.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 789       | 29.89%  |
| 3.01-4.0    | 503       | 19.05%  |
| 8.01-16.0   | 495       | 18.75%  |
| 16.01-24.0  | 453       | 17.16%  |
| 32.01-64.0  | 172       | 6.52%   |
| 1.01-2.0    | 114       | 4.32%   |
| 2.01-3.0    | 44        | 1.67%   |
| 64.01-256.0 | 27        | 1.02%   |
| 24.01-32.0  | 23        | 0.87%   |
| 0.51-1.0    | 18        | 0.68%   |
| 0.01-0.5    | 2         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1031      | 35.53%  |
| 2.01-3.0   | 741       | 25.53%  |
| 4.01-8.0   | 423       | 14.58%  |
| 3.01-4.0   | 380       | 13.09%  |
| 0.51-1.0   | 170       | 5.86%   |
| 8.01-16.0  | 99        | 3.41%   |
| 0.01-0.5   | 39        | 1.34%   |
| 16.01-24.0 | 11        | 0.38%   |
| 24.01-32.0 | 6         | 0.21%   |
| 32.01-64.0 | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1952      | 73.14%  |
| 2      | 580       | 21.73%  |
| 3      | 95        | 3.56%   |
| 0      | 24        | 0.9%    |
| 4      | 15        | 0.56%   |
| 5      | 2         | 0.07%   |
| 7      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1610      | 61.54%  |
| Yes       | 1006      | 38.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2111      | 80.91%  |
| No        | 498       | 19.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2550      | 98.08%  |
| No        | 50        | 1.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1954      | 74.04%  |
| No        | 685       | 25.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 2598      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Toronto         | 262       | 9.57%   |
| Montreal        | 255       | 9.31%   |
| Vancouver       | 115       | 4.2%    |
| Calgary         | 108       | 3.94%   |
| Ottawa          | 93        | 3.4%    |
| Edmonton        | 90        | 3.29%   |
| Québec         | 65        | 2.37%   |
| Winnipeg        | 62        | 2.26%   |
| Mississauga     | 50        | 1.83%   |
| Victoria        | 48        | 1.75%   |
| London          | 37        | 1.35%   |
| Regina          | 32        | 1.17%   |
| Surrey          | 30        | 1.1%    |
| Laval           | 29        | 1.06%   |
| Brampton        | 29        | 1.06%   |
| Kitchener       | 27        | 0.99%   |
| Burnaby         | 25        | 0.91%   |
| Hamilton        | 24        | 0.88%   |
| Halifax         | 23        | 0.84%   |
| Saskatoon       | 21        | 0.77%   |
| Oshawa          | 20        | 0.73%   |
| Markham         | 20        | 0.73%   |
| Scarborough     | 19        | 0.69%   |
| Moncton         | 19        | 0.69%   |
| Sherbrooke      | 18        | 0.66%   |
| Windsor         | 17        | 0.62%   |
| Gatineau        | 17        | 0.62%   |
| New Westminster | 15        | 0.55%   |
| Kingston        | 15        | 0.55%   |
| Richmond Hill   | 14        | 0.51%   |
| Kelowna         | 13        | 0.47%   |
| Vernon          | 12        | 0.44%   |
| Richmond        | 12        | 0.44%   |
| Levis           | 12        | 0.44%   |
| Fredericton     | 12        | 0.44%   |
| Barrie          | 12        | 0.44%   |
| Waterloo        | 11        | 0.4%    |
| Thunder Bay     | 11        | 0.4%    |
| Trois-Rivières | 10        | 0.37%   |
| St. Catharines  | 10        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 482       | 668    | 14.97%  |
| WDC                         | 425       | 530    | 13.2%   |
| Seagate                     | 376       | 493    | 11.68%  |
| Toshiba                     | 260       | 323    | 8.07%   |
| Unknown                     | 211       | 273    | 6.55%   |
| Kingston                    | 190       | 248    | 5.9%    |
| SanDisk                     | 186       | 222    | 5.78%   |
| Intel                       | 129       | 189    | 4.01%   |
| SK hynix                    | 120       | 153    | 3.73%   |
| Hitachi                     | 108       | 122    | 3.35%   |
| HGST                        | 95        | 114    | 2.95%   |
| Crucial                     | 76        | 95     | 2.36%   |
| Micron Technology           | 60        | 82     | 1.86%   |
| A-DATA Technology           | 50        | 63     | 1.55%   |
| Apple                       | 44        | 50     | 1.37%   |
| Fujitsu                     | 38        | 51     | 1.18%   |
| KIOXIA                      | 29        | 34     | 0.9%    |
| LITEONIT                    | 22        | 25     | 0.68%   |
| SPCC                        | 20        | 33     | 0.62%   |
| LITEON                      | 17        | 19     | 0.53%   |
| China                       | 15        | 16     | 0.47%   |
| Kingston Technology Company | 14        | 16     | 0.43%   |
| Unknown                     | 12        | 12     | 0.37%   |
| PNY                         | 11        | 19     | 0.34%   |
| Phison Electronics          | 11        | 13     | 0.34%   |
| Phison                      | 10        | 11     | 0.31%   |
| OCZ                         | 8         | 8      | 0.25%   |
| JMicron Technology          | 8         | 10     | 0.25%   |
| Silicon Motion              | 7         | 7      | 0.22%   |
| Micron/Crucial Technology   | 7         | 8      | 0.22%   |
| Dogfish                     | 7         | 10     | 0.22%   |
| ASMT                        | 7         | 7      | 0.22%   |
| Team                        | 6         | 8      | 0.19%   |
| Patriot                     | 6         | 6      | 0.19%   |
| KingFast                    | 6         | 8      | 0.19%   |
| External                    | 6         | 8      | 0.19%   |
| Timetec                     | 5         | 8      | 0.16%   |
| Mushkin                     | 5         | 8      | 0.16%   |
| Corsair                     | 5         | 5      | 0.16%   |
| Union Memory (Shenzhen)     | 4         | 4      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 46        | 1.37%   |
| Toshiba MQ01ABD100 1TB                              | 43        | 1.28%   |
| Unknown MMC Card  64GB                              | 42        | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 39        | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB                      | 37        | 1.1%    |
| Unknown MMC Card  32GB                              | 32        | 0.95%   |
| HGST HTS721010A9E630 1TB                            | 29        | 0.86%   |
| Samsung SSD 860 EVO 500GB                           | 25        | 0.75%   |
| Unknown MMC Card  16GB                              | 21        | 0.63%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.63%   |
| Seagate ST9500325AS 500GB                           | 20        | 0.6%    |
| Seagate ST1000LX015-1U7172 1TB                      | 20        | 0.6%    |
| Samsung NVMe SSD Drive 512GB                        | 20        | 0.6%    |
| Samsung SSD 860 EVO 1TB                             | 19        | 0.57%   |
| Kingston SA400S37480G 480GB SSD                     | 19        | 0.57%   |
| Intel NVMe SSD Drive 512GB                          | 19        | 0.57%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 18        | 0.54%   |
| Seagate ST500LT012-1DG142 500GB                     | 18        | 0.54%   |
| HGST HTS725050A7E630 500GB                          | 18        | 0.54%   |
| Samsung SSD 850 EVO 250GB                           | 17        | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 16        | 0.48%   |
| SK hynix NVMe SSD Drive 512GB                       | 16        | 0.48%   |
| Samsung SSD 860 EVO 250GB                           | 16        | 0.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 16        | 0.48%   |
| HGST HTS541010A9E680 1TB                            | 16        | 0.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 15        | 0.45%   |
| Toshiba MQ01ABF050 500GB                            | 15        | 0.45%   |
| Seagate ST500LM021-1KJ152 500GB                     | 15        | 0.45%   |
| Samsung SSD 850 EVO 500GB                           | 15        | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 15        | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                    | 15        | 0.45%   |
| Toshiba MQ04ABF100 1TB                              | 14        | 0.42%   |
| Seagate Expansion 1TB                               | 14        | 0.42%   |
| Samsung NVMe SSD Drive 256GB                        | 14        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB                         | 14        | 0.42%   |
| Unknown MMC Card  128GB                             | 13        | 0.39%   |
| Seagate ST1000LM048-2E7172 1TB                      | 13        | 0.39%   |
| SanDisk NVMe SSD Drive 512GB                        | 13        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                          | 13        | 0.39%   |
| Samsung NVMe SSD Drive 500GB                        | 13        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 364       | 470    | 32.01%  |
| WDC                 | 277       | 331    | 24.36%  |
| Toshiba             | 202       | 258    | 17.77%  |
| Hitachi             | 108       | 122    | 9.5%    |
| HGST                | 95        | 114    | 8.36%   |
| Fujitsu             | 38        | 51     | 3.34%   |
| Samsung Electronics | 14        | 24     | 1.23%   |
| Unknown             | 8         | 9      | 0.7%    |
| Apple               | 8         | 8      | 0.7%    |
| External            | 6         | 8      | 0.53%   |
| JMicron Technology  | 5         | 6      | 0.44%   |
| Maxone              | 3         | 3      | 0.26%   |
| ASMT                | 3         | 3      | 0.26%   |
| USB 3.0             | 1         | 2      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| Inateck             | 1         | 1      | 0.09%   |
| Generic-            | 1         | 1      | 0.09%   |
| DAS                 | 1         | 5      | 0.09%   |
| ACASIS              | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 243       | 331    | 24.2%   |
| Kingston            | 160       | 203    | 15.94%  |
| SanDisk             | 90        | 105    | 8.96%   |
| Crucial             | 70        | 87     | 6.97%   |
| WDC                 | 69        | 98     | 6.87%   |
| A-DATA Technology   | 44        | 56     | 4.38%   |
| Intel               | 43        | 59     | 4.28%   |
| Micron Technology   | 30        | 47     | 2.99%   |
| Apple               | 28        | 29     | 2.79%   |
| LITEONIT            | 22        | 25     | 2.19%   |
| SPCC                | 19        | 32     | 1.89%   |
| SK hynix            | 19        | 25     | 1.89%   |
| Toshiba             | 18        | 21     | 1.79%   |
| China               | 15        | 16     | 1.49%   |
| LITEON              | 13        | 14     | 1.29%   |
| PNY                 | 11        | 19     | 1.1%    |
| OCZ                 | 8         | 8      | 0.8%    |
| Dogfish             | 7         | 10     | 0.7%    |
| Patriot             | 6         | 6      | 0.6%    |
| Team                | 5         | 7      | 0.5%    |
| Seagate             | 5         | 8      | 0.5%    |
| TO Exter            | 4         | 5      | 0.4%    |
| Timetec             | 4         | 7      | 0.4%    |
| Mushkin             | 4         | 7      | 0.4%    |
| KingSpec            | 4         | 6      | 0.4%    |
| Transcend           | 3         | 4      | 0.3%    |
| Super Talent        | 3         | 4      | 0.3%    |
| OWC                 | 3         | 6      | 0.3%    |
| NGFF                | 3         | 3      | 0.3%    |
| KingFast            | 3         | 3      | 0.3%    |
| KingDian            | 3         | 3      | 0.3%    |
| Corsair             | 3         | 3      | 0.3%    |
| ASMT                | 3         | 3      | 0.3%    |
| Zheino              | 2         | 2      | 0.2%    |
| WDC WDS             | 2         | 2      | 0.2%    |
| Kingchuxing         | 2         | 2      | 0.2%    |
| BHT                 | 2         | 2      | 0.2%    |
| AMD                 | 2         | 3      | 0.2%    |
| Unknown             | 2         | 2      | 0.2%    |
| Wibtek              | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1089      | 1418   | 35.82%  |
| SSD     | 915       | 1310   | 30.1%   |
| NVMe    | 784       | 1083   | 25.79%  |
| MMC     | 210       | 274    | 6.91%   |
| Unknown | 42        | 50     | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1815      | 2583   | 61.69%  |
| NVMe | 780       | 1079   | 26.51%  |
| MMC  | 210       | 274    | 7.14%   |
| SAS  | 137       | 199    | 4.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1296      | 1776   | 65.03%  |
| 0.51-1.0   | 629       | 857    | 31.56%  |
| 1.01-2.0   | 46        | 65     | 2.31%   |
| 4.01-10.0  | 18        | 25     | 0.9%    |
| 3.01-4.0   | 3         | 4      | 0.15%   |
| 10.01-20.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 731       | 26.3%   |
| 101-250        | 730       | 26.27%  |
| 501-1000       | 462       | 16.62%  |
| 1-20           | 248       | 8.92%   |
| 51-100         | 184       | 6.62%   |
| 1001-2000      | 152       | 5.47%   |
| 21-50          | 107       | 3.85%   |
| Unknown        | 77        | 2.77%   |
| More than 3000 | 52        | 1.87%   |
| 2001-3000      | 36        | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1204      | 41.83%  |
| 21-50          | 544       | 18.9%   |
| 51-100         | 356       | 12.37%  |
| 101-250        | 343       | 11.92%  |
| 251-500        | 196       | 6.81%   |
| 501-1000       | 101       | 3.51%   |
| Unknown        | 77        | 2.68%   |
| 1001-2000      | 37        | 1.29%   |
| More than 3000 | 13        | 0.45%   |
| 2001-3000      | 7         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 10     | 5.42%   |
| Toshiba MQ01ABD100 1TB               | 6         | 8      | 3.61%   |
| HGST HTS541010A9E680 1TB             | 6         | 6      | 3.61%   |
| Seagate ST9500325AS 500GB            | 5         | 5      | 3.01%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 2.41%   |
| Seagate ST500LM000-1EJ162 500GB      | 4         | 4      | 2.41%   |
| HGST HTS721010A9E630 1TB             | 4         | 4      | 2.41%   |
| HGST HTS545050A7E680 500GB           | 4         | 4      | 2.41%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 3      | 1.81%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 2      | 1.2%    |
| Toshiba MQ01ABD075 752GB             | 2         | 2      | 1.2%    |
| Toshiba MK3261GSYN 320GB             | 2         | 2      | 1.2%    |
| Toshiba MK2552GSX 250GB              | 2         | 2      | 1.2%    |
| Toshiba MK2035GSS 200GB              | 2         | 2      | 1.2%    |
| Seagate ST9750420AS 752GB            | 2         | 2      | 1.2%    |
| Seagate ST9500420AS 500GB            | 2         | 2      | 1.2%    |
| Seagate ST9320423AS 320GB            | 2         | 4      | 1.2%    |
| Seagate ST9320325AS 320GB            | 2         | 2      | 1.2%    |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 2      | 1.2%    |
| Seagate ST320LT020-9YG142 320GB      | 2         | 2      | 1.2%    |
| Seagate ST1000LX015-1U7172-SSHD 1TB  | 2         | 2      | 1.2%    |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 2      | 1.2%    |
| Hitachi HTS725050A9A364 500GB        | 2         | 2      | 1.2%    |
| Hitachi HTS547575A9E384 752GB        | 2         | 2      | 1.2%    |
| Hitachi HTS545050B9A300 500GB        | 2         | 2      | 1.2%    |
| HGST HTS725050A7E630 500GB           | 2         | 3      | 1.2%    |
| A-DATA Technology SX900 256GB SSD    | 2         | 2      | 1.2%    |
| WDC WD7500BPKT-60PK4T0 752GB         | 1         | 1      | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 1      | 0.6%    |
| WDC WD3200LPVX-22V0TT0 320GB         | 1         | 1      | 0.6%    |
| WDC WD2500BEVT-75A23T0 250GB         | 1         | 1      | 0.6%    |
| WDC WD2500BEVT-00ZCT0 250GB          | 1         | 1      | 0.6%    |
| WDC WD2500BEVS-75UST0 250GB          | 1         | 1      | 0.6%    |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 1      | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1      | 0.6%    |
| WDC WD10JPVX-08JC3T5 1TB             | 1         | 1      | 0.6%    |
| WDC WD10JPVT-55A1YT0 1TB             | 1         | 1      | 0.6%    |
| WDC WD10JPLX-00MBPT1 1TB             | 1         | 2      | 0.6%    |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 2      | 0.6%    |
| WDC WD Blue SA510 M.2 2280 500GB SSD | 1         | 1      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 54     | 30.72%  |
| Toshiba             | 26        | 28     | 15.66%  |
| Hitachi             | 18        | 18     | 10.84%  |
| HGST                | 18        | 19     | 10.84%  |
| WDC                 | 15        | 17     | 9.04%   |
| Samsung Electronics | 7         | 16     | 4.22%   |
| Intel               | 7         | 7      | 4.22%   |
| A-DATA Technology   | 4         | 4      | 2.41%   |
| Kingston            | 3         | 3      | 1.81%   |
| Sandisk             | 2         | 2      | 1.2%    |
| Fujitsu             | 2         | 6      | 1.2%    |
| Timetec             | 1         | 2      | 0.6%    |
| Super Talent        | 1         | 1      | 0.6%    |
| SK hynix            | 1         | 1      | 0.6%    |
| OCZ                 | 1         | 1      | 0.6%    |
| Micron Technology   | 1         | 1      | 0.6%    |
| LITEONIT            | 1         | 1      | 0.6%    |
| LITEON              | 1         | 1      | 0.6%    |
| LaCie               | 1         | 1      | 0.6%    |
| KingSpec            | 1         | 1      | 0.6%    |
| Crucial             | 1         | 1      | 0.6%    |
| Corsair             | 1         | 1      | 0.6%    |
| ASMT                | 1         | 1      | 0.6%    |
| Apple               | 1         | 1      | 0.6%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 54     | 38.93%  |
| Toshiba             | 24        | 26     | 18.32%  |
| Hitachi             | 18        | 18     | 13.74%  |
| HGST                | 18        | 19     | 13.74%  |
| WDC                 | 14        | 16     | 10.69%  |
| Fujitsu             | 2         | 6      | 1.53%   |
| Samsung Electronics | 1         | 9      | 0.76%   |
| LaCie               | 1         | 1      | 0.76%   |
| ASMT                | 1         | 1      | 0.76%   |
| Apple               | 1         | 1      | 0.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 129       | 151    | 78.66%  |
| SSD  | 29        | 30     | 17.68%  |
| NVMe | 6         | 7      | 3.66%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Notebooks | Drives | Percent |
|------------------------|-----------|--------|---------|
| LITEON CA3-8D512 512GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| LITEON | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1682      | 2701   | 61.3%   |
| Works    | 898       | 1244   | 32.73%  |
| Malfunc  | 163       | 188    | 5.94%   |
| Failed   | 1         | 2      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1709      | 58.17%  |
| AMD                            | 403       | 13.72%  |
| Samsung Electronics            | 263       | 8.95%   |
| SanDisk                        | 167       | 5.68%   |
| SK hynix                       | 98        | 3.34%   |
| Kingston Technology Company    | 43        | 1.46%   |
| Toshiba America Info Systems   | 40        | 1.36%   |
| Nvidia                         | 38        | 1.29%   |
| KIOXIA                         | 32        | 1.09%   |
| Micron Technology              | 31        | 1.06%   |
| Phison Electronics             | 24        | 0.82%   |
| Micron/Crucial Technology      | 14        | 0.48%   |
| Union Memory (Shenzhen)        | 10        | 0.34%   |
| Silicon Motion                 | 10        | 0.34%   |
| ADATA Technology               | 10        | 0.34%   |
| Lite-On Technology             | 7         | 0.24%   |
| Apple                          | 6         | 0.2%    |
| Marvell Technology Group       | 5         | 0.17%   |
| Solid State Storage Technology | 4         | 0.14%   |
| Realtek Semiconductor          | 4         | 0.14%   |
| Lenovo                         | 4         | 0.14%   |
| ASMedia Technology             | 4         | 0.14%   |
| JMicron Technology             | 3         | 0.1%    |
| Seagate Technology             | 2         | 0.07%   |
| O2 Micro                       | 2         | 0.07%   |
| INNOGRIT                       | 2         | 0.07%   |
| Yangtze Memory Technologies    | 1         | 0.03%   |
| Shenzhen Longsys Electronics   | 1         | 0.03%   |
| OCZ Technology Group           | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 332       | 10.46%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 211       | 6.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 171       | 5.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 157       | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 144       | 4.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 115       | 3.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 101       | 3.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 95        | 2.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 85        | 2.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 83        | 2.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 68        | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 63        | 1.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 62        | 1.95%   |
| Intel Volume Management Device NVMe RAID Controller                              | 62        | 1.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 56        | 1.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 51        | 1.61%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 50        | 1.58%   |
| Samsung NVMe SSD Controller 980                                                  | 48        | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 48        | 1.51%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 41        | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 41        | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 39        | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 34        | 1.07%   |
| Intel SSD 660P Series                                                            | 29        | 0.91%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 29        | 0.91%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 27        | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 26        | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 23        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 23        | 0.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 21        | 0.66%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 20        | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 19        | 0.6%    |
| Nvidia MCP79 AHCI Controller                                                     | 19        | 0.6%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 18        | 0.57%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 18        | 0.57%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 17        | 0.54%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]               | 17        | 0.54%   |
| SK hynix BC511 NVMe SSD                                                          | 16        | 0.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 16        | 0.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 16        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1792      | 59.34%  |
| NVMe | 781       | 25.86%  |
| RAID | 240       | 7.95%   |
| IDE  | 207       | 6.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 2045      | 78.71%  |
| AMD     | 550       | 21.17%  |
| ARM     | 2         | 0.08%   |
| Unknown | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 45        | 1.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 44        | 1.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 39        | 1.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 36        | 1.38%   |
| AMD Custom APU 0405                           | 35        | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 34        | 1.31%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 34        | 1.31%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 1.31%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 28        | 1.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 27        | 1.04%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 27        | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 26        | 1%      |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 24        | 0.92%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 24        | 0.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 24        | 0.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 21        | 0.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 21        | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 20        | 0.77%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 19        | 0.73%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 19        | 0.73%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 19        | 0.73%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 18        | 0.69%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 17        | 0.65%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 17        | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 0.58%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 15        | 0.58%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 15        | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 14        | 0.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 0.54%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 13        | 0.5%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 13        | 0.5%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 13        | 0.5%    |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 13        | 0.5%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 13        | 0.5%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 0.5%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 12        | 0.46%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 12        | 0.46%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 12        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 632       | 24.31%  |
| Intel Core i7           | 616       | 23.69%  |
| Other                   | 220       | 8.46%   |
| Intel Core i3           | 148       | 5.69%   |
| Intel Core 2 Duo        | 146       | 5.62%   |
| Intel Celeron           | 106       | 4.08%   |
| AMD Ryzen 7             | 98        | 3.77%   |
| AMD Ryzen 5             | 64        | 2.46%   |
| Intel Pentium           | 61        | 2.35%   |
| AMD A6                  | 55        | 2.12%   |
| Intel Atom              | 42        | 1.62%   |
| AMD A10                 | 39        | 1.5%    |
| Intel Pentium Dual-Core | 28        | 1.08%   |
| AMD A4                  | 28        | 1.08%   |
| Intel Pentium Dual      | 24        | 0.92%   |
| Intel Genuine           | 21        | 0.81%   |
| AMD Ryzen 3             | 21        | 0.81%   |
| AMD A8                  | 21        | 0.81%   |
| AMD Ryzen 9             | 20        | 0.77%   |
| Intel Core i9           | 15        | 0.58%   |
| Intel Core 2            | 14        | 0.54%   |
| AMD E                   | 13        | 0.5%    |
| AMD E2                  | 12        | 0.46%   |
| AMD E1                  | 12        | 0.46%   |
| AMD A12                 | 11        | 0.42%   |
| AMD Turion 64 X2 Mobile | 10        | 0.38%   |
| AMD Ryzen 5 PRO         | 10        | 0.38%   |
| AMD Athlon X2           | 9         | 0.35%   |
| Intel Pentium Silver    | 7         | 0.27%   |
| AMD Athlon 64 X2        | 7         | 0.27%   |
| Intel Xeon              | 6         | 0.23%   |
| AMD Ryzen 7 PRO         | 6         | 0.23%   |
| AMD Phenom II           | 6         | 0.23%   |
| AMD Athlon              | 6         | 0.23%   |
| AMD C-50                | 5         | 0.19%   |
| AMD Athlon II           | 5         | 0.19%   |
| Intel Pentium M         | 4         | 0.15%   |
| Intel Celeron M         | 4         | 0.15%   |
| AMD Turion 64 Mobile    | 4         | 0.15%   |
| Intel Core m3           | 3         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1366      | 52.5%   |
| 4      | 786       | 30.21%  |
| 6      | 169       | 6.5%    |
| 8      | 155       | 5.96%   |
| 1      | 64        | 2.46%   |
| 14     | 28        | 1.08%   |
| 12     | 13        | 0.5%    |
| 10     | 12        | 0.46%   |
| 16     | 4         | 0.15%   |
| 24     | 2         | 0.08%   |
| 3      | 2         | 0.08%   |
| 7      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2598      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1886      | 72.48%  |
| 1      | 715       | 27.48%  |
| 12     | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2536      | 97.39%  |
| 32-bit         | 36        | 1.38%   |
| Unknown        | 31        | 1.19%   |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 768       | 28.35%  |
| 0x306a9    | 161       | 5.94%   |
| 0x206a7    | 156       | 5.76%   |
| 0x40651    | 86        | 3.17%   |
| 0x1067a    | 84        | 3.1%    |
| 0x806ea    | 73        | 2.69%   |
| 0x906ea    | 72        | 2.66%   |
| 0x20655    | 67        | 2.47%   |
| 0x406e3    | 62        | 2.29%   |
| 0x806e9    | 60        | 2.21%   |
| 0x306c3    | 58        | 2.14%   |
| 0x306d4    | 53        | 1.96%   |
| 0x806ec    | 49        | 1.81%   |
| 0x6fd      | 49        | 1.81%   |
| 0xa0652    | 45        | 1.66%   |
| 0x20652    | 41        | 1.51%   |
| 0x806c1    | 38        | 1.4%    |
| 0x906e9    | 36        | 1.33%   |
| 0x06001119 | 32        | 1.18%   |
| 0x906a3    | 28        | 1.03%   |
| 0x30678    | 28        | 1.03%   |
| 0x0a50000c | 28        | 1.03%   |
| 0x506e3    | 27        | 1%      |
| 0x10676    | 24        | 0.89%   |
| 0x08108102 | 24        | 0.89%   |
| 0x06006705 | 24        | 0.89%   |
| 0x706e5    | 23        | 0.85%   |
| 0x406c4    | 22        | 0.81%   |
| 0x406c3    | 20        | 0.74%   |
| 0x05000119 | 20        | 0.74%   |
| 0x08108109 | 18        | 0.66%   |
| 0x07030105 | 18        | 0.66%   |
| 0x106e5    | 17        | 0.63%   |
| 0x08600104 | 17        | 0.63%   |
| 0x03000027 | 17        | 0.63%   |
| 0x806eb    | 16        | 0.59%   |
| 0x010000c8 | 14        | 0.52%   |
| 0x6e8      | 13        | 0.48%   |
| 0x506c9    | 13        | 0.48%   |
| 0x08608103 | 13        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 422       | 16.21%  |
| IvyBridge        | 212       | 8.14%   |
| Haswell          | 197       | 7.57%   |
| SandyBridge      | 193       | 7.41%   |
| Penryn           | 134       | 5.15%   |
| Westmere         | 133       | 5.11%   |
| Skylake          | 119       | 4.57%   |
| Unknown          | 114       | 4.38%   |
| Silvermont       | 93        | 3.57%   |
| Core             | 92        | 3.53%   |
| Broadwell        | 78        | 3%      |
| Excavator        | 77        | 2.96%   |
| TigerLake        | 68        | 2.61%   |
| CometLake        | 67        | 2.57%   |
| Zen+             | 61        | 2.34%   |
| Zen 2            | 56        | 2.15%   |
| Zen 3            | 49        | 1.88%   |
| Alderlake Hybrid | 48        | 1.84%   |
| Icelake          | 43        | 1.65%   |
| Piledriver       | 41        | 1.57%   |
| Puma             | 32        | 1.23%   |
| Bobcat           | 32        | 1.23%   |
| Goldmont plus    | 30        | 1.15%   |
| K8 Hammer        | 27        | 1.04%   |
| P6               | 24        | 0.92%   |
| Zen              | 23        | 0.88%   |
| K10 Llano        | 23        | 0.88%   |
| Nehalem          | 22        | 0.84%   |
| Bonnell          | 21        | 0.81%   |
| K10              | 19        | 0.73%   |
| Jaguar           | 18        | 0.69%   |
| Goldmont         | 16        | 0.61%   |
| K8 & K10 hybrid  | 12        | 0.46%   |
| Steamroller      | 4         | 0.15%   |
| Tremont          | 3         | 0.12%   |
| NetBurst         | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1834      | 58.04%  |
| Nvidia | 666       | 21.08%  |
| AMD    | 660       | 20.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 186       | 5.66%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 173       | 5.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 109       | 3.32%   |
| Intel UHD Graphics 620                                                                   | 105       | 3.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 105       | 3.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 99        | 3.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 95        | 2.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 76        | 2.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 74        | 2.25%   |
| Intel HD Graphics 620                                                                    | 69        | 2.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 67        | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 65        | 1.98%   |
| Intel HD Graphics 5500                                                                   | 64        | 1.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 56        | 1.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 56        | 1.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 53        | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 52        | 1.58%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 52        | 1.58%   |
| AMD Renoir                                                                               | 50        | 1.52%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 46        | 1.4%    |
| Intel HD Graphics 630                                                                    | 37        | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 37        | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 36        | 1.1%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 36        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 36        | 1.1%    |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 35        | 1.07%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 31        | 0.94%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 31        | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 30        | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 29        | 0.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 29        | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 27        | 0.82%   |
| Intel HD Graphics 530                                                                    | 26        | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 24        | 0.73%   |
| AMD Lucienne                                                                             | 23        | 0.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 21        | 0.64%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 21        | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 20        | 0.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 20        | 0.61%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 19        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1322      | 50.63%  |
| 1 x AMD            | 506       | 19.38%  |
| Intel + Nvidia     | 439       | 16.81%  |
| 1 x Nvidia         | 169       | 6.47%   |
| Intel + AMD        | 63        | 2.41%   |
| AMD + Nvidia       | 56        | 2.14%   |
| 2 x AMD            | 36        | 1.38%   |
| Other              | 9         | 0.34%   |
| 2 x Intel          | 6         | 0.23%   |
| 2 x Nvidia         | 4         | 0.15%   |
| Intel + 2 x Nvidia | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2226      | 84.45%  |
| Proprietary | 346       | 13.13%  |
| Unknown     | 64        | 2.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1742      | 65.02%  |
| 0.01-0.5   | 365       | 13.62%  |
| 1.01-2.0   | 228       | 8.51%   |
| 0.51-1.0   | 125       | 4.67%   |
| 3.01-4.0   | 121       | 4.52%   |
| 5.01-6.0   | 42        | 1.57%   |
| 7.01-8.0   | 40        | 1.49%   |
| 2.01-3.0   | 8         | 0.3%    |
| 8.01-16.0  | 8         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 565       | 18.81%  |
| LG Display              | 413       | 13.75%  |
| Samsung Electronics     | 354       | 11.79%  |
| Chimei Innolux          | 316       | 10.52%  |
| BOE                     | 272       | 9.06%   |
| Sharp                   | 134       | 4.46%   |
| Apple                   | 106       | 3.53%   |
| Lenovo                  | 92        | 3.06%   |
| Dell                    | 86        | 2.86%   |
| Chi Mei Optoelectronics | 79        | 2.63%   |
| Goldstar                | 72        | 2.4%    |
| PANDA                   | 46        | 1.53%   |
| Hewlett-Packard         | 42        | 1.4%    |
| Acer                    | 38        | 1.27%   |
| LG Philips              | 32        | 1.07%   |
| ASUSTek Computer        | 31        | 1.03%   |
| BenQ                    | 29        | 0.97%   |
| Ancor Communications    | 27        | 0.9%    |
| Toshiba                 | 23        | 0.77%   |
| InfoVision              | 21        | 0.7%    |
| Valve                   | 20        | 0.67%   |
| ViewSonic               | 15        | 0.5%    |
| Sony                    | 14        | 0.47%   |
| CSO                     | 12        | 0.4%    |
| Philips                 | 11        | 0.37%   |
| AOC                     | 11        | 0.37%   |
| Panasonic               | 10        | 0.33%   |
| TMX                     | 9         | 0.3%    |
| Quanta Display          | 8         | 0.27%   |
| HannStar                | 8         | 0.27%   |
| CPT                     | 7         | 0.23%   |
| Seiko/Epson             | 6         | 0.2%    |
| Insignia                | 6         | 0.2%    |
| HKC                     | 6         | 0.2%    |
| LGD                     | 5         | 0.17%   |
| IBM                     | 5         | 0.17%   |
| MSI                     | 4         | 0.13%   |
| Unknown                 | 3         | 0.1%    |
| SANYO                   | 3         | 0.1%    |
| InnoLux Display         | 3         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 33        | 1.08%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 31        | 1.02%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 20        | 0.66%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 19        | 0.62%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 19        | 0.62%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 18        | 0.59%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 18        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 17        | 0.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 16        | 0.52%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 16        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 16        | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 15        | 0.49%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 12        | 0.39%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 12        | 0.39%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 12        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.39%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.39%   |
| Toshiba TV TSB0206 1920x1080 1600x1000mm 74.3-inch                       | 11        | 0.36%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 11        | 0.36%   |
| LG Display LCD Monitor LGD0563 1920x1080 340x190mm 15.3-inch             | 11        | 0.36%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 10        | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 10        | 0.33%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 10        | 0.33%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 10        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.33%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 10        | 0.33%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 9         | 0.29%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch            | 9         | 0.29%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 9         | 0.29%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 8         | 0.26%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 8         | 0.26%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 8         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 8         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 8         | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 8         | 0.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.26%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch            | 8         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1002      | 35.31%  |
| 1366x768 (WXGA)    | 858       | 30.23%  |
| 1600x900 (HD+)     | 166       | 5.85%   |
| 1280x800 (WXGA)    | 157       | 5.53%   |
| 3840x2160 (4K)     | 126       | 4.44%   |
| 2560x1440 (QHD)    | 78        | 2.75%   |
| 1920x1200 (WUXGA)  | 66        | 2.33%   |
| 1440x900 (WXGA+)   | 66        | 2.33%   |
| 1680x1050 (WSXGA+) | 58        | 2.04%   |
| 2880x1800          | 32        | 1.13%   |
| 800x1280           | 22        | 0.78%   |
| 1280x1024 (SXGA)   | 21        | 0.74%   |
| 2560x1600          | 18        | 0.63%   |
| 3440x1440          | 17        | 0.6%    |
| 3840x2400          | 15        | 0.53%   |
| 3200x1800 (QHD+)   | 13        | 0.46%   |
| 2560x1080          | 13        | 0.46%   |
| 1024x600           | 13        | 0.46%   |
| 2256x1504          | 10        | 0.35%   |
| 1920x540           | 10        | 0.35%   |
| 1360x768           | 10        | 0.35%   |
| 1024x768 (XGA)     | 10        | 0.35%   |
| Unknown            | 7         | 0.25%   |
| 3200x2000          | 6         | 0.21%   |
| 3456x2160          | 4         | 0.14%   |
| 1920x1280          | 4         | 0.14%   |
| 3840x1080          | 3         | 0.11%   |
| 2560x1700          | 3         | 0.11%   |
| 1680x945           | 3         | 0.11%   |
| 3840x1200          | 2         | 0.07%   |
| 3840x1100          | 2         | 0.07%   |
| 3072x1920          | 2         | 0.07%   |
| 3000x2000          | 2         | 0.07%   |
| 2288x1287          | 2         | 0.07%   |
| 2160x1440          | 2         | 0.07%   |
| 1600x1200          | 2         | 0.07%   |
| 1280x720 (HD)      | 2         | 0.07%   |
| 1024x576           | 2         | 0.07%   |
| 3520x1080          | 1         | 0.04%   |
| 3280x1080          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1262      | 42.05%  |
| 13      | 394       | 13.13%  |
| 14      | 332       | 11.06%  |
| 17      | 210       | 7%      |
| 27      | 97        | 3.23%   |
| 24      | 93        | 3.1%    |
| 23      | 65        | 2.17%   |
| 21      | 62        | 2.07%   |
| 12      | 56        | 1.87%   |
| 11      | 56        | 1.87%   |
| Unknown | 52        | 1.73%   |
| 31      | 33        | 1.1%    |
| 34      | 31        | 1.03%   |
| 22      | 30        | 1%      |
| 18      | 24        | 0.8%    |
| 16      | 21        | 0.7%    |
| 19      | 20        | 0.67%   |
| 7       | 20        | 0.67%   |
| 20      | 19        | 0.63%   |
| 10      | 15        | 0.5%    |
| 84      | 13        | 0.43%   |
| 72      | 13        | 0.43%   |
| 74      | 11        | 0.37%   |
| 32      | 10        | 0.33%   |
| 25      | 8         | 0.27%   |
| 54      | 7         | 0.23%   |
| 26      | 7         | 0.23%   |
| 40      | 6         | 0.2%    |
| 37      | 5         | 0.17%   |
| 48      | 4         | 0.13%   |
| 47      | 3         | 0.1%    |
| 43      | 3         | 0.1%    |
| 42      | 3         | 0.1%    |
| 28      | 3         | 0.1%    |
| 39      | 2         | 0.07%   |
| 3       | 2         | 0.07%   |
| 69      | 1         | 0.03%   |
| 60      | 1         | 0.03%   |
| 58      | 1         | 0.03%   |
| 57      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1738      | 58.5%   |
| 201-300     | 333       | 11.21%  |
| 351-400     | 275       | 9.26%   |
| 501-600     | 240       | 8.08%   |
| 401-500     | 146       | 4.91%   |
| Unknown     | 52        | 1.75%   |
| 601-700     | 47        | 1.58%   |
| 701-800     | 41        | 1.38%   |
| 1501-2000   | 37        | 1.25%   |
| 1-100       | 22        | 0.74%   |
| 1001-1500   | 21        | 0.71%   |
| 801-900     | 13        | 0.44%   |
| 901-1000    | 5         | 0.17%   |
| 101-200     | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2051      | 77.96%  |
| 16/10   | 417       | 15.85%  |
| 3/2     | 33        | 1.25%   |
| 21/9    | 31        | 1.18%   |
| Unknown | 30        | 1.14%   |
| 0.67    | 20        | 0.76%   |
| 5/4     | 18        | 0.68%   |
| 4/3     | 18        | 0.68%   |
| 6/5     | 4         | 0.15%   |
| 32/9    | 2         | 0.08%   |
| 3.40    | 2         | 0.08%   |
| 1.96    | 2         | 0.08%   |
| 3.73    | 1         | 0.04%   |
| 3.33    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1245      | 41.75%  |
| 81-90          | 574       | 19.25%  |
| 201-250        | 200       | 6.71%   |
| 121-130        | 172       | 5.77%   |
| 71-80          | 139       | 4.66%   |
| 301-350        | 101       | 3.39%   |
| 351-500        | 75        | 2.52%   |
| 51-60          | 58        | 1.95%   |
| 151-200        | 58        | 1.95%   |
| 61-70          | 53        | 1.78%   |
| Unknown        | 52        | 1.74%   |
| More than 1000 | 49        | 1.64%   |
| 111-120        | 35        | 1.17%   |
| 131-140        | 33        | 1.11%   |
| 251-300        | 30        | 1.01%   |
| 141-150        | 30        | 1.01%   |
| 501-1000       | 27        | 0.91%   |
| 1-40           | 23        | 0.77%   |
| 41-50          | 15        | 0.5%    |
| 91-100         | 13        | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 993       | 34.07%  |
| 101-120       | 958       | 32.86%  |
| 51-100        | 548       | 18.8%   |
| 161-240       | 196       | 6.72%   |
| More than 240 | 113       | 3.88%   |
| 1-50          | 55        | 1.89%   |
| Unknown       | 52        | 1.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2092      | 78.5%   |
| 2     | 444       | 16.66%  |
| 3     | 69        | 2.59%   |
| 0     | 58        | 2.18%   |
| 4     | 2         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1404      | 34.74%  |
| Realtek Semiconductor           | 1181      | 29.22%  |
| Qualcomm Atheros                | 598       | 14.79%  |
| Broadcom                        | 326       | 8.07%   |
| Broadcom Limited                | 109       | 2.7%    |
| MediaTek                        | 56        | 1.39%   |
| Marvell Technology Group        | 49        | 1.21%   |
| ASIX Electronics                | 39        | 0.96%   |
| Nvidia                          | 32        | 0.79%   |
| TP-Link                         | 28        | 0.69%   |
| Ralink                          | 27        | 0.67%   |
| Ralink Technology               | 19        | 0.47%   |
| Linksys                         | 19        | 0.47%   |
| D-Link                          | 15        | 0.37%   |
| Lenovo                          | 13        | 0.32%   |
| DisplayLink                     | 12        | 0.3%    |
| Samsung Electronics             | 11        | 0.27%   |
| ASUSTek Computer                | 11        | 0.27%   |
| Qualcomm Atheros Communications | 10        | 0.25%   |
| Sierra Wireless                 | 9         | 0.22%   |
| Qualcomm                        | 9         | 0.22%   |
| Google                          | 7         | 0.17%   |
| NetGear                         | 6         | 0.15%   |
| AMD                             | 5         | 0.12%   |
| Hewlett-Packard                 | 4         | 0.1%    |
| Apple                           | 4         | 0.1%    |
| Research In Motion              | 3         | 0.07%   |
| JMicron Technology              | 3         | 0.07%   |
| D-Link System                   | 3         | 0.07%   |
| Xiaomi                          | 2         | 0.05%   |
| U-Blox                          | 2         | 0.05%   |
| TRENDnet                        | 2         | 0.05%   |
| Microsoft                       | 2         | 0.05%   |
| LG Electronics                  | 2         | 0.05%   |
| Edimax Technology               | 2         | 0.05%   |
| Dell                            | 2         | 0.05%   |
| Aquantia                        | 2         | 0.05%   |
| STMicroelectronics              | 1         | 0.02%   |
| Panasonic (Matsushita)          | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 647       | 12.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 248       | 4.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 159       | 3.19%   |
| Intel Wireless 8265 / 8275                                        | 125       | 2.5%    |
| Intel Wi-Fi 6 AX200                                               | 105       | 2.1%    |
| Intel Wireless 7260                                               | 101       | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 97        | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 96        | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 91        | 1.82%   |
| Intel Wireless 7265                                               | 84        | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 81        | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 81        | 1.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 80        | 1.6%    |
| Intel Wireless 8260                                               | 74        | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 65        | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 62        | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 54        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 53        | 1.06%   |
| Intel 82577LM Gigabit Network Connection                          | 50        | 1%      |
| Intel Centrino Ultimate-N 6300                                    | 49        | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 48        | 0.96%   |
| Intel Wi-Fi 6 AX201                                               | 47        | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 46        | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 42        | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 41        | 0.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 39        | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 37        | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                     | 37        | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 32        | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 32        | 0.64%   |
| Intel Wireless 3165                                               | 32        | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 31        | 0.62%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 31        | 0.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 30        | 0.6%    |
| Intel Centrino Wireless-N 2230                                    | 30        | 0.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 30        | 0.6%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 30        | 0.6%    |
| Intel Centrino Advanced-N 6235                                    | 29        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1326      | 48.79%  |
| Qualcomm Atheros                      | 492       | 18.1%   |
| Realtek Semiconductor                 | 361       | 13.28%  |
| Broadcom                              | 256       | 9.42%   |
| Broadcom Limited                      | 69        | 2.54%   |
| MediaTek                              | 54        | 1.99%   |
| Ralink                                | 27        | 0.99%   |
| TP-Link                               | 26        | 0.96%   |
| Ralink Technology                     | 19        | 0.7%    |
| Linksys                               | 17        | 0.63%   |
| D-Link                                | 14        | 0.52%   |
| ASUSTek Computer                      | 11        | 0.4%    |
| Qualcomm Atheros Communications       | 10        | 0.37%   |
| Sierra Wireless                       | 9         | 0.33%   |
| Qualcomm                              | 8         | 0.29%   |
| NetGear                               | 6         | 0.22%   |
| D-Link System                         | 3         | 0.11%   |
| TRENDnet                              | 2         | 0.07%   |
| Edimax Technology                     | 2         | 0.07%   |
| Dell                                  | 2         | 0.07%   |
| Panasonic (Matsushita)                | 1         | 0.04%   |
| Microsoft                             | 1         | 0.04%   |
| Marvell Technology Group              | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 125       | 4.56%   |
| Intel Wi-Fi 6 AX200                                                     | 105       | 3.83%   |
| Intel Wireless 7260                                                     | 101       | 3.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 96        | 3.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 91        | 3.32%   |
| Intel Wireless 7265                                                     | 84        | 3.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 81        | 2.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 81        | 2.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 80        | 2.92%   |
| Intel Wireless 8260                                                     | 74        | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 65        | 2.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 62        | 2.26%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 54        | 1.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 53        | 1.93%   |
| Intel Centrino Ultimate-N 6300                                          | 49        | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 48        | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 47        | 1.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 1.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 39        | 1.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 37        | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 32        | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 32        | 1.17%   |
| Intel Wireless 3165                                                     | 32        | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 31        | 1.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 30        | 1.09%   |
| Intel Centrino Wireless-N 2230                                          | 30        | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 30        | 1.09%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 30        | 1.09%   |
| Intel Centrino Advanced-N 6235                                          | 29        | 1.06%   |
| Intel Centrino Advanced-N 6200                                          | 29        | 1.06%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 29        | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 28        | 1.02%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 27        | 0.99%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 26        | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 25        | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 24        | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 24        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 24        | 0.88%   |
| Intel Wireless 3160                                                     | 23        | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 1021      | 46.6%   |
| Intel                    | 611       | 27.89%  |
| Qualcomm Atheros         | 180       | 8.22%   |
| Broadcom                 | 145       | 6.62%   |
| Marvell Technology Group | 48        | 2.19%   |
| Broadcom Limited         | 45        | 2.05%   |
| ASIX Electronics         | 39        | 1.78%   |
| Nvidia                   | 31        | 1.41%   |
| Lenovo                   | 13        | 0.59%   |
| DisplayLink              | 12        | 0.55%   |
| Google                   | 7         | 0.32%   |
| Samsung Electronics      | 6         | 0.27%   |
| Hewlett-Packard          | 4         | 0.18%   |
| Apple                    | 4         | 0.18%   |
| TP-Link                  | 3         | 0.14%   |
| Research In Motion       | 3         | 0.14%   |
| JMicron Technology       | 3         | 0.14%   |
| Xiaomi                   | 2         | 0.09%   |
| Linksys                  | 2         | 0.09%   |
| LG Electronics           | 2         | 0.09%   |
| Aquantia                 | 2         | 0.09%   |
| Qualcomm                 | 1         | 0.05%   |
| Motorola PCS             | 1         | 0.05%   |
| Microsoft                | 1         | 0.05%   |
| MediaTek                 | 1         | 0.05%   |
| HTC (High Tech Computer) | 1         | 0.05%   |
| HMD Global               | 1         | 0.05%   |
| D-Link                   | 1         | 0.05%   |
| Attansic Technology      | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 647       | 29.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 248       | 11.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 159       | 7.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 97        | 4.37%   |
| Intel 82577LM Gigabit Network Connection                          | 50        | 2.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 46        | 2.07%   |
| Intel Ethernet Connection I218-LM                                 | 42        | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 1.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 37        | 1.67%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 1.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 31        | 1.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 26        | 1.17%   |
| Intel Ethernet Connection (4) I219-V                              | 26        | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 26        | 1.17%   |
| Intel 82567LM Gigabit Network Connection                          | 26        | 1.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19        | 0.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 19        | 0.86%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 17        | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 16        | 0.72%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 16        | 0.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 16        | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.68%   |
| Intel Ethernet Connection I219-V                                  | 15        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 14        | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 14        | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 13        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12        | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.54%   |
| Intel Ethernet Connection (6) I219-V                              | 11        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.45%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 10        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 9         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2550      | 54.41%  |
| Ethernet | 2107      | 44.95%  |
| Modem    | 27        | 0.58%   |
| Unknown  | 3         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2161      | 77.37%  |
| Ethernet | 632       | 22.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1935      | 74.34%  |
| 1     | 609       | 23.4%   |
| 0     | 34        | 1.31%   |
| 3     | 25        | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2216      | 83.97%  |
| Yes  | 423       | 16.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 943       | 47.41%  |
| Broadcom                        | 154       | 7.74%   |
| Qualcomm Atheros Communications | 150       | 7.54%   |
| Realtek Semiconductor           | 149       | 7.49%   |
| IMC Networks                    | 126       | 6.33%   |
| Lite-On Technology              | 113       | 5.68%   |
| Apple                           | 97        | 4.88%   |
| Foxconn / Hon Hai               | 87        | 4.37%   |
| Dell                            | 38        | 1.91%   |
| Hewlett-Packard                 | 30        | 1.51%   |
| Cambridge Silicon Radio         | 30        | 1.51%   |
| Ralink                          | 15        | 0.75%   |
| ASUSTek Computer                | 13        | 0.65%   |
| Toshiba                         | 12        | 0.6%    |
| Alps Electric                   | 7         | 0.35%   |
| Realtek                         | 3         | 0.15%   |
| MediaTek                        | 3         | 0.15%   |
| USI                             | 2         | 0.1%    |
| SINO WEALTH                     | 2         | 0.1%    |
| Logitech                        | 2         | 0.1%    |
| Dynex                           | 2         | 0.1%    |
| TP-Link                         | 1         | 0.05%   |
| Taiyo Yuden                     | 1         | 0.05%   |
| Ralink Technology               | 1         | 0.05%   |
| Qcom                            | 1         | 0.05%   |
| Primax Electronics              | 1         | 0.05%   |
| Marvell Semiconductor           | 1         | 0.05%   |
| Kensington                      | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| Foxconn International           | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 424       | 21.26%  |
| Intel AX201 Bluetooth                                                               | 147       | 7.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 106       | 5.32%   |
| Intel AX200 Bluetooth                                                               | 102       | 5.12%   |
| Realtek Bluetooth Radio                                                             | 101       | 5.07%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 80        | 4.01%   |
| IMC Networks Bluetooth Radio                                                        | 65        | 3.26%   |
| Apple Bluetooth Host Controller                                                     | 64        | 3.21%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 55        | 2.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 49        | 2.46%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 41        | 2.06%   |
| Intel Bluetooth Device                                                              | 39        | 1.96%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 35        | 1.76%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 32        | 1.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 30        | 1.5%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 29        | 1.45%   |
| Intel AX210 Bluetooth                                                               | 24        | 1.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 23        | 1.15%   |
| IMC Networks Wireless_Device                                                        | 23        | 1.15%   |
| Apple Bluetooth USB Host Controller                                                 | 23        | 1.15%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 22        | 1.1%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 21        | 1.05%   |
| Broadcom HP Portable SoftSailing                                                    | 18        | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 17        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 17        | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 17        | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 16        | 0.8%    |
| Ralink RT3290 Bluetooth                                                             | 15        | 0.75%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 14        | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 13        | 0.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 13        | 0.65%   |
| IMC Networks Bluetooth Device                                                       | 12        | 0.6%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 12        | 0.6%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 11        | 0.55%   |
| Dell DW375 Bluetooth Module                                                         | 11        | 0.55%   |
| Lite-On Bluetooth Device                                                            | 10        | 0.5%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 9         | 0.45%   |
| IMC Networks BCM20702A0                                                             | 9         | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 9         | 0.45%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 9         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1997      | 62.12%  |
| AMD                                  | 609       | 18.94%  |
| Nvidia                               | 392       | 12.19%  |
| C-Media Electronics                  | 26        | 0.81%   |
| Realtek Semiconductor                | 22        | 0.68%   |
| Logitech                             | 19        | 0.59%   |
| GN Netcom                            | 14        | 0.44%   |
| Lenovo                               | 12        | 0.37%   |
| Plantronics                          | 9         | 0.28%   |
| SteelSeries ApS                      | 6         | 0.19%   |
| JMTek                                | 6         | 0.19%   |
| Focusrite-Novation                   | 6         | 0.19%   |
| Razer USA                            | 5         | 0.16%   |
| Kingston Technology                  | 5         | 0.16%   |
| Creative Technology                  | 5         | 0.16%   |
| Blue Microphones                     | 5         | 0.16%   |
| Sony                                 | 4         | 0.12%   |
| Sennheiser Communications            | 4         | 0.12%   |
| No brand                             | 4         | 0.12%   |
| Hewlett-Packard                      | 4         | 0.12%   |
| Corsair                              | 4         | 0.12%   |
| Texas Instruments                    | 3         | 0.09%   |
| Generalplus Technology               | 3         | 0.09%   |
| Dell                                 | 3         | 0.09%   |
| ASUSTek Computer                     | 3         | 0.09%   |
| Apple                                | 3         | 0.09%   |
| Synaptics                            | 2         | 0.06%   |
| Samson Technologies                  | 2         | 0.06%   |
| Panasonic (Matsushita)               | 2         | 0.06%   |
| Native Instruments                   | 2         | 0.06%   |
| Jieli Technology                     | 2         | 0.06%   |
| Audio-Technica                       | 2         | 0.06%   |
| XMOS                                 | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |
| Shure                                | 1         | 0.03%   |
| SAVITECH                             | 1         | 0.03%   |
| RODE Microphones                     | 1         | 0.03%   |
| RME                                  | 1         | 0.03%   |
| PreSonus Audio Electronics           | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 264       | 6.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 238       | 6.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 224       | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 166       | 4.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 154       | 3.93%   |
| AMD FCH Azalia Controller                                                                         | 128       | 3.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 117       | 2.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 113       | 2.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 109       | 2.78%   |
| Intel 8 Series HD Audio Controller                                                                | 109       | 2.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 103       | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 88        | 2.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 81        | 2.07%   |
| Intel Broadwell-U Audio Controller                                                                | 78        | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 76        | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 75        | 1.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 75        | 1.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 74        | 1.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 70        | 1.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 68        | 1.73%   |
| Intel Comet Lake PCH cAVS                                                                         | 58        | 1.48%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 57        | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 54        | 1.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 52        | 1.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 49        | 1.25%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 47        | 1.2%    |
| AMD High Definition Audio Controller                                                              | 46        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 44        | 1.12%   |
| Intel CM238 HD Audio Controller                                                                   | 42        | 1.07%   |
| AMD Trinity HDMI Audio Controller                                                                 | 41        | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 37        | 0.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 37        | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 35        | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 33        | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 31        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 30        | 0.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 30        | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 30        | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 29        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 29        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 432       | 27.12%  |
| SK hynix                                         | 405       | 25.42%  |
| Micron Technology                                | 201       | 12.62%  |
| Kingston                                         | 127       | 7.97%   |
| Unknown                                          | 115       | 7.22%   |
| Crucial                                          | 70        | 4.39%   |
| Elpida                                           | 35        | 2.2%    |
| G.Skill                                          | 33        | 2.07%   |
| Ramaxel Technology                               | 29        | 1.82%   |
| Nanya Technology                                 | 28        | 1.76%   |
| A-DATA Technology                                | 22        | 1.38%   |
| Corsair                                          | 20        | 1.26%   |
| Unknown                                          | 10        | 0.63%   |
| Patriot                                          | 8         | 0.5%    |
| Toshiba                                          | 5         | 0.31%   |
| Timetec                                          | 4         | 0.25%   |
| Goldkey                                          | 4         | 0.25%   |
| Unknown (ABCD)                                   | 3         | 0.19%   |
| PNY                                              | 3         | 0.19%   |
| ff                                               | 3         | 0.19%   |
| ASint Technology                                 | 3         | 0.19%   |
| 4ea5                                             | 3         | 0.19%   |
| Unknown (7F7F7F94FFFFFFFF)                       | 2         | 0.13%   |
| SHARETRONIC                                      | 2         | 0.13%   |
| Neo Forza                                        | 2         | 0.13%   |
| fef5                                             | 2         | 0.13%   |
| Axiom                                            | 2         | 0.13%   |
| Unknown (0x505344323247363637325300000000000000) | 1         | 0.06%   |
| Unknown (0x4D342037305432383634515A332D43453620) | 1         | 0.06%   |
| Unknown (0x48594D503132355336344350382D53362020) | 1         | 0.06%   |
| Unknown (0x0C26)                                 | 1         | 0.06%   |
| Unknown (0x0080)                                 | 1         | 0.06%   |
| Unknown (08AE)                                   | 1         | 0.06%   |
| Unknown (000080B30080)                           | 1         | 0.06%   |
| Unifosa                                          | 1         | 0.06%   |
| Transcend                                        | 1         | 0.06%   |
| Team                                             | 1         | 0.06%   |
| Sesame                                           | 1         | 0.06%   |
| Qumo                                             | 1         | 0.06%   |
| Qimonda                                          | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 32        | 1.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 21        | 1.25%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 1.19%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 19        | 1.13%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 1.07%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.95%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.95%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.95%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.89%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.89%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 14        | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.77%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 13        | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.71%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.71%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 12        | 0.71%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 11        | 0.65%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 11        | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.65%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 11        | 0.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 10        | 0.59%   |
| Unknown                                                          | 10        | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.53%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.53%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.53%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 8         | 0.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 8         | 0.47%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s           | 8         | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.47%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 8         | 0.47%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 7         | 0.42%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 7         | 0.42%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 7         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 556       | 41.9%   |
| DDR3    | 501       | 37.75%  |
| LPDDR4  | 66        | 4.97%   |
| DDR2    | 60        | 4.52%   |
| LPDDR3  | 59        | 4.45%   |
| DDR5    | 25        | 1.88%   |
| SDRAM   | 23        | 1.73%   |
| Unknown | 16        | 1.21%   |
| LPDDR5  | 10        | 0.75%   |
| DDR     | 10        | 0.75%   |
| DRAM    | 1         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1170      | 88.37%  |
| Row Of Chips    | 119       | 8.99%   |
| Chip            | 18        | 1.36%   |
| Unknown         | 12        | 0.91%   |
| DIMM            | 4         | 0.3%    |
| Proprietary Car | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 582       | 39.17%  |
| 4096  | 443       | 29.81%  |
| 16384 | 198       | 13.32%  |
| 2048  | 188       | 12.65%  |
| 1024  | 49        | 3.3%    |
| 32768 | 22        | 1.48%   |
| 512   | 2         | 0.13%   |
| 65536 | 1         | 0.07%   |
| 256   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 336       | 23.32%  |
| 2667    | 263       | 18.25%  |
| 3200    | 213       | 14.78%  |
| 2400    | 113       | 7.84%   |
| 2133    | 82        | 5.69%   |
| 1334    | 77        | 5.34%   |
| 1333    | 60        | 4.16%   |
| 667     | 35        | 2.43%   |
| 1067    | 33        | 2.29%   |
| 4267    | 29        | 2.01%   |
| 4800    | 26        | 1.8%    |
| 1867    | 22        | 1.53%   |
| Unknown | 21        | 1.46%   |
| 3266    | 17        | 1.18%   |
| 1066    | 14        | 0.97%   |
| 8400    | 13        | 0.9%    |
| 6400    | 13        | 0.9%    |
| 4199    | 13        | 0.9%    |
| 800     | 13        | 0.9%    |
| 4266    | 10        | 0.69%   |
| 975     | 10        | 0.69%   |
| 533     | 7         | 0.49%   |
| 3733    | 6         | 0.42%   |
| 2048    | 3         | 0.21%   |
| 1639    | 3         | 0.21%   |
| 400     | 2         | 0.14%   |
| 2933    | 1         | 0.07%   |
| 2666    | 1         | 0.07%   |
| 1866    | 1         | 0.07%   |
| 1777    | 1         | 0.07%   |
| 1200    | 1         | 0.07%   |
| 933     | 1         | 0.07%   |
| 333     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 9         | 28.13%  |
| Brother Industries  | 9         | 28.13%  |
| Samsung Electronics | 6         | 18.75%  |
| Canon               | 5         | 15.63%  |
| Xerox               | 1         | 3.13%   |
| QinHeng Electronics | 1         | 3.13%   |
| Prolific Technology | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Samsung M2070 Series                            | 2         | 5.88%   |
| HP OfficeJet 3830 series                        | 2         | 5.88%   |
| Canon PIXMA MG2900 Series                       | 2         | 5.88%   |
| Brother Printer                                 | 2         | 5.88%   |
| Xerox B210                                      | 1         | 2.94%   |
| Samsung ML-2510 Series                          | 1         | 2.94%   |
| Samsung M267x 287x Series                       | 1         | 2.94%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 2.94%   |
| Samsung M2020 Series                            | 1         | 2.94%   |
| QinHeng CH340S                                  | 1         | 2.94%   |
| Prolific PL2305 Parallel Port                   | 1         | 2.94%   |
| HP LaserJet Professional P1102w                 | 1         | 2.94%   |
| HP LaserJet 1160 series                         | 1         | 2.94%   |
| HP LaserJet 1020                                | 1         | 2.94%   |
| HP LaserJet 1018                                | 1         | 2.94%   |
| HP ENVY 5000 series                             | 1         | 2.94%   |
| HP ENVY 4520 series                             | 1         | 2.94%   |
| HP DeskJet 2620 All-in-One Printer              | 1         | 2.94%   |
| Canon MG2100 series                             | 1         | 2.94%   |
| Canon MF3010                                    | 1         | 2.94%   |
| Canon G3060 series                              | 1         | 2.94%   |
| Brother MFC-L2730DW series                      | 1         | 2.94%   |
| Brother MFC-L2717DW                             | 1         | 2.94%   |
| Brother MFC-J6945DW                             | 1         | 2.94%   |
| Brother MFC-J480DW                              | 1         | 2.94%   |
| Brother MFC-9330CDW                             | 1         | 2.94%   |
| Brother HL-L2390DW                              | 1         | 2.94%   |
| Brother HL-2270DW Laser Printer                 | 1         | 2.94%   |
| Brother HL-2170W series                         | 1         | 2.94%   |
| Brother DCP-L2550DW series                      | 1         | 2.94%   |

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
| Chicony Electronics                    | 532       | 23.72%  |
| Microdia                               | 250       | 11.15%  |
| IMC Networks                           | 231       | 10.3%   |
| Realtek Semiconductor                  | 174       | 7.76%   |
| Sunplus Innovation Technology          | 146       | 6.51%   |
| Bison Electronics                      | 117       | 5.22%   |
| Quanta                                 | 101       | 4.5%    |
| Apple                                  | 94        | 4.19%   |
| Suyin                                  | 92        | 4.1%    |
| Acer                                   | 66        | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) | 61        | 2.72%   |
| Logitech                               | 48        | 2.14%   |
| Lite-On Technology                     | 42        | 1.87%   |
| Luxvisions Innotech Limited            | 32        | 1.43%   |
| Ricoh                                  | 30        | 1.34%   |
| Syntek                                 | 29        | 1.29%   |
| Silicon Motion                         | 29        | 1.29%   |
| Lenovo                                 | 25        | 1.11%   |
| Importek                               | 19        | 0.85%   |
| Samsung Electronics                    | 18        | 0.8%    |
| Alcor Micro                            | 14        | 0.62%   |
| Microsoft                              | 11        | 0.49%   |
| Sonix Technology                       | 10        | 0.45%   |
| ALi                                    | 9         | 0.4%    |
| OmniVision Technologies                | 8         | 0.36%   |
| Primax Electronics                     | 7         | 0.31%   |
| Z-Star Microelectronics                | 5         | 0.22%   |
| LG Electronics                         | 4         | 0.18%   |
| YGTek                                  | 3         | 0.13%   |
| MacroSilicon                           | 3         | 0.13%   |
| AVerMedia Technologies                 | 3         | 0.13%   |
| Sunplus Technology                     | 2         | 0.09%   |
| HRY                                    | 2         | 0.09%   |
| Genesys Logic                          | 2         | 0.09%   |
| ZOOM                                   | 1         | 0.04%   |
| WaveRider Communications               | 1         | 0.04%   |
| SunplusIT                              | 1         | 0.04%   |
| Sony                                   | 1         | 0.04%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.04%   |
| Razer USA                              | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 123       | 5.45%   |
| Microdia Integrated_Webcam_HD                       | 113       | 5.01%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 82        | 3.63%   |
| Realtek Integrated_Webcam_HD                        | 73        | 3.23%   |
| Chicony HD WebCam                                   | 51        | 2.26%   |
| IMC Networks Integrated Camera                      | 49        | 2.17%   |
| Sunplus Integrated_Webcam_HD                        | 33        | 1.46%   |
| Microdia Integrated Webcam                          | 33        | 1.46%   |
| Apple Built-in iSight                               | 31        | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 29        | 1.28%   |
| Sunplus HD WebCam                                   | 27        | 1.2%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 27        | 1.2%    |
| Apple FaceTime HD Camera                            | 26        | 1.15%   |
| Acer Integrated Camera                              | 26        | 1.15%   |
| Chicony VGA WebCam                                  | 22        | 0.97%   |
| Chicony HP TrueVision HD                            | 21        | 0.93%   |
| Bison Integrated Camera                             | 21        | 0.93%   |
| Quanta HD User Facing                               | 20        | 0.89%   |
| Lite-On Integrated Camera                           | 20        | 0.89%   |
| Quanta VGA WebCam                                   | 19        | 0.84%   |
| Chicony HP HD Camera                                | 19        | 0.84%   |
| Syntek Integrated Camera                            | 18        | 0.8%    |
| Samsung Galaxy series, misc. (MTP mode)             | 18        | 0.8%    |
| Quanta HP TrueVision HD Camera                      | 18        | 0.8%    |
| Chicony USB2.0 HD UVC WebCam                        | 17        | 0.75%   |
| Bison SunplusIT Integrated Camera                   | 17        | 0.75%   |
| Chicony USB 2.0 Camera                              | 16        | 0.71%   |
| Chicony TOSHIBA Web Camera - HD                     | 15        | 0.66%   |
| Sunplus HP HD Webcam [Fixed]                        | 14        | 0.62%   |
| Realtek USB Camera                                  | 14        | 0.62%   |
| Chicony HD User Facing                              | 14        | 0.62%   |
| Bison Lenovo EasyCamera                             | 14        | 0.62%   |
| Bison HD Webcam                                     | 14        | 0.62%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 13        | 0.58%   |
| IMC Networks VGA UVC WebCam                         | 13        | 0.58%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 13        | 0.58%   |
| Chicony Lenovo EasyCamera                           | 13        | 0.58%   |
| Chicony Integrated Camera (1280x720@30)             | 13        | 0.58%   |
| Acer BisonCam,NB Pro                                | 13        | 0.58%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 12        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 203       | 41.18%  |
| Synaptics                          | 99        | 20.08%  |
| Shenzhen Goodix Technology         | 44        | 8.92%   |
| Upek                               | 35        | 7.1%    |
| Elan Microelectronics              | 35        | 7.1%    |
| AuthenTec                          | 33        | 6.69%   |
| LighTuning Technology              | 22        | 4.46%   |
| STMicroelectronics                 | 15        | 3.04%   |
| Focal-systems.Corp                 | 3         | 0.61%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.2%    |
| Microsoft                          | 1         | 0.2%    |
| HOLTEK                             | 1         | 0.2%    |
| Dell                               | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 48        | 9.74%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 38        | 7.71%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 34        | 6.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 34        | 6.9%    |
| Elan ELAN:Fingerprint                                                      | 29        | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 26        | 5.27%   |
| Shenzhen Goodix FingerPrint                                                | 25        | 5.07%   |
| Validity Sensors Synaptics WBDI                                            | 24        | 4.87%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 3.85%   |
| Validity Sensors VFS491                                                    | 18        | 3.65%   |
| STMicroelectronics Fingerprint Reader                                      | 15        | 3.04%   |
| Shenzhen Goodix  Fingerprint Device                                        | 15        | 3.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 2.84%   |
| AuthenTec AES2810                                                          | 14        | 2.84%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 2.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 1.83%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 1.62%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.42%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.42%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.42%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 1.42%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.22%   |
| Elan ELAN:ARM-M4                                                           | 6         | 1.22%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.01%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.81%   |
| Synaptics UWP WBDI                                                         | 4         | 0.81%   |
| Synaptics  WBDI                                                            | 4         | 0.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 0.81%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.61%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.61%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.61%   |
| AuthenTec AES1600                                                          | 3         | 0.61%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.41%   |
| Synaptics WBDI                                                             | 2         | 0.41%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.41%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.41%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 91        | 47.4%   |
| Alcor Micro               | 35        | 18.23%  |
| O2 Micro                  | 25        | 13.02%  |
| Upek                      | 22        | 11.46%  |
| Lenovo                    | 12        | 6.25%   |
| Gemalto (was Gemplus)     | 4         | 2.08%   |
| Yubico.com                | 1         | 0.52%   |
| Giesecke & Devrient       | 1         | 0.52%   |
| Aladdin Knowledge Systems | 1         | 0.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 49        | 25.52%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 34        | 17.71%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 11.46%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 10.94%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 9.9%    |
| Broadcom 5880                                                                | 14        | 7.29%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 6.25%   |
| Broadcom 58200                                                               | 8         | 4.17%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 2.08%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 2.08%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.52%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.52%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.52%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1654      | 62.13%  |
| 1     | 798       | 29.98%  |
| 2     | 177       | 6.65%   |
| 3     | 25        | 0.94%   |
| 4     | 5         | 0.19%   |
| 7     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 484       | 39.67%  |
| Graphics card            | 218       | 17.87%  |
| Chipcard                 | 177       | 14.51%  |
| Net/wireless             | 106       | 8.69%   |
| Multimedia controller    | 70        | 5.74%   |
| Storage                  | 34        | 2.79%   |
| Camera                   | 27        | 2.21%   |
| Bluetooth                | 26        | 2.13%   |
| Communication controller | 22        | 1.8%    |
| Net/ethernet             | 14        | 1.15%   |
| Modem                    | 9         | 0.74%   |
| Card reader              | 9         | 0.74%   |
| Sound                    | 8         | 0.66%   |
| Flash memory             | 5         | 0.41%   |
| Network                  | 4         | 0.33%   |
| Storage/ide              | 2         | 0.16%   |
| Firewire controller      | 2         | 0.16%   |
| Unclassified device      | 1         | 0.08%   |
| Tv card                  | 1         | 0.08%   |
| Dvb card                 | 1         | 0.08%   |

