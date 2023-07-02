Linux in Spain - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

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

Total: 4291

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookAir9,1               | [bd5c030739](https://linux-hardware.org/?probe=bd5c030739) | Jun 30, 2023 |
| Apple         | MacBookAir9,1               | [ce486a5063](https://linux-hardware.org/?probe=ce486a5063) | Jun 30, 2023 |
| MSI           | Modern 14 B5M               | [cb0eb574da](https://linux-hardware.org/?probe=cb0eb574da) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| ASUSTek       | X541UAK                     | [83d0d28a2a](https://linux-hardware.org/?probe=83d0d28a2a) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| Chuwi         | GemiBook                    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [5922b4d31f](https://linux-hardware.org/?probe=5922b4d31f) | Jun 27, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| MSI           | Prestige 14H B12UCX         | [abf425c8d7](https://linux-hardware.org/?probe=abf425c8d7) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| Dell          | Inspiron MM061              | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [f14b9f6ce5](https://linux-hardware.org/?probe=f14b9f6ce5) | Jun 25, 2023 |
| HUAWEI        | HKD-WXX                     | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | Compaq 610                  | [f312ec5ede](https://linux-hardware.org/?probe=f312ec5ede) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| Dell          | XPS 9320                    | [2dcfa6718b](https://linux-hardware.org/?probe=2dcfa6718b) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [69dfee1765](https://linux-hardware.org/?probe=69dfee1765) | Jun 22, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| win elemen... | MoreFine S500+              | [32b221a438](https://linux-hardware.org/?probe=32b221a438) | Jun 20, 2023 |
| Dell          | Latitude 7430               | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| Samsung       | RF510/RF410/RF710           | [6131e6746c](https://linux-hardware.org/?probe=6131e6746c) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2b32ca2d11](https://linux-hardware.org/?probe=2b32ca2d11) | Jun 18, 2023 |
| Toshiba       | NB510                       | [a66bda9742](https://linux-hardware.org/?probe=a66bda9742) | Jun 18, 2023 |
| HP            | Pavilion Notebook           | [5d417b3d76](https://linux-hardware.org/?probe=5d417b3d76) | Jun 18, 2023 |
| Samsung       | RV415/RV515/E3415           | [b17c80df83](https://linux-hardware.org/?probe=b17c80df83) | Jun 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| MSI           | Modern 14 B5M               | [21bd3b8234](https://linux-hardware.org/?probe=21bd3b8234) | Jun 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [3ea85763dc](https://linux-hardware.org/?probe=3ea85763dc) | Jun 16, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [2c6d49788f](https://linux-hardware.org/?probe=2c6d49788f) | Jun 16, 2023 |
| Valve         | Jupiter                     | [28dc5a83fe](https://linux-hardware.org/?probe=28dc5a83fe) | Jun 16, 2023 |
| Beelink       | Gemini X                    | [f95615a561](https://linux-hardware.org/?probe=f95615a561) | Jun 15, 2023 |
| Beelink       | Gemini X                    | [3f69d07a3e](https://linux-hardware.org/?probe=3f69d07a3e) | Jun 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [b9eac1e0b6](https://linux-hardware.org/?probe=b9eac1e0b6) | Jun 15, 2023 |
| HP            | Notebook                    | [dc40bd89f8](https://linux-hardware.org/?probe=dc40bd89f8) | Jun 15, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [542a1217bd](https://linux-hardware.org/?probe=542a1217bd) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [0b717c2785](https://linux-hardware.org/?probe=0b717c2785) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | Stealth 15M B12UE           | [aabb8192ee](https://linux-hardware.org/?probe=aabb8192ee) | Jun 12, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [7b48584062](https://linux-hardware.org/?probe=7b48584062) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [e6079c9659](https://linux-hardware.org/?probe=e6079c9659) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [5a7c331645](https://linux-hardware.org/?probe=5a7c331645) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | G580 2189                   | [eac7ae2f7a](https://linux-hardware.org/?probe=eac7ae2f7a) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [0d419f2c9d](https://linux-hardware.org/?probe=0d419f2c9d) | Jun 11, 2023 |
| Valve         | Jupiter                     | [c7e458735d](https://linux-hardware.org/?probe=c7e458735d) | Jun 11, 2023 |
| Valve         | Jupiter                     | [3e31827529](https://linux-hardware.org/?probe=3e31827529) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [afc5d143fe](https://linux-hardware.org/?probe=afc5d143fe) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| Lenovo        | ThinkPad T450 20BU000BIX    | [d82c175e3e](https://linux-hardware.org/?probe=d82c175e3e) | Jun 10, 2023 |
| Beelink       | Gemini X                    | [adcb5e774d](https://linux-hardware.org/?probe=adcb5e774d) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| Dell          | Latitude E5500              | [41ad12c465](https://linux-hardware.org/?probe=41ad12c465) | Jun 10, 2023 |
| Apple         | MacBookPro5,5               | [1b3630b25a](https://linux-hardware.org/?probe=1b3630b25a) | Jun 10, 2023 |
| Apple         | MacBookPro11,4              | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| MSI           | GE66 Raider 10UE            | [38a5122d9c](https://linux-hardware.org/?probe=38a5122d9c) | Jun 08, 2023 |
| Micro Comp... | NUCXI7                      | [3b930f4e22](https://linux-hardware.org/?probe=3b930f4e22) | Jun 08, 2023 |
| Beelink       | Gemini X                    | [49aca69972](https://linux-hardware.org/?probe=49aca69972) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [ff2ebbb0ae](https://linux-hardware.org/?probe=ff2ebbb0ae) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [265c19be27](https://linux-hardware.org/?probe=265c19be27) | Jun 07, 2023 |
| MSI           | GT72 2QE                    | [211494a051](https://linux-hardware.org/?probe=211494a051) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [acae4ee06e](https://linux-hardware.org/?probe=acae4ee06e) | Jun 06, 2023 |
| MSI           | Modern 14 C12M              | [a5d1a0e656](https://linux-hardware.org/?probe=a5d1a0e656) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| Acer          | Aspire E1-572P              | [a90316cac7](https://linux-hardware.org/?probe=a90316cac7) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [04fdc3c3b8](https://linux-hardware.org/?probe=04fdc3c3b8) | Jun 03, 2023 |
| Valve         | Jupiter                     | [8c33873318](https://linux-hardware.org/?probe=8c33873318) | Jun 03, 2023 |
| MSI           | Prestige 16 A12UD           | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Notebook      | NL40_50CU                   | [47b838db36](https://linux-hardware.org/?probe=47b838db36) | Jun 02, 2023 |
| Notebook      | N141CU                      | [4af09bd0c3](https://linux-hardware.org/?probe=4af09bd0c3) | Jun 02, 2023 |
| Valve         | Jupiter                     | [762287e555](https://linux-hardware.org/?probe=762287e555) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Lenovo        | ThinkPad T530 2392AHG       | [05c41c8464](https://linux-hardware.org/?probe=05c41c8464) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| Lenovo        | G580 2189                   | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| MSI           | Modern 14 B4MW              | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Acer          | Nitro AN515-54              | [7c031081c5](https://linux-hardware.org/?probe=7c031081c5) | May 31, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [5e96e1c54e](https://linux-hardware.org/?probe=5e96e1c54e) | May 31, 2023 |
| Chuwi         | HeroBook Air                | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e9830d0123](https://linux-hardware.org/?probe=e9830d0123) | May 29, 2023 |
| Lenovo        | V145-15AST 81MT             | [bf9c082ee0](https://linux-hardware.org/?probe=bf9c082ee0) | May 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [dc2b5e538f](https://linux-hardware.org/?probe=dc2b5e538f) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | [9605e313ac](https://linux-hardware.org/?probe=9605e313ac) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | [0a8ae92c13](https://linux-hardware.org/?probe=0a8ae92c13) | May 27, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [f7f07e78d5](https://linux-hardware.org/?probe=f7f07e78d5) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [89b7c17d00](https://linux-hardware.org/?probe=89b7c17d00) | May 26, 2023 |
| MSI           | Alpha 15 A3DDK              | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Acer          | TravelMate 5720             | [1066a7a5c5](https://linux-hardware.org/?probe=1066a7a5c5) | May 25, 2023 |
| HP            | Laptop 15s-fq4xxx           | [810c2ac411](https://linux-hardware.org/?probe=810c2ac411) | May 24, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [428a152134](https://linux-hardware.org/?probe=428a152134) | May 23, 2023 |
| Notebook      | W54_55SU1,SUW               | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [77f092da32](https://linux-hardware.org/?probe=77f092da32) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| Acer          | Extensa 5635Z               | [dcff2c30c6](https://linux-hardware.org/?probe=dcff2c30c6) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | [895bca272b](https://linux-hardware.org/?probe=895bca272b) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [21f52b0bc9](https://linux-hardware.org/?probe=21f52b0bc9) | May 22, 2023 |
| MSI           | Stealth 15M B12UE           | [4051f4b27d](https://linux-hardware.org/?probe=4051f4b27d) | May 22, 2023 |
| Dell          | Inspiron 5770               | [4c16a00ef6](https://linux-hardware.org/?probe=4c16a00ef6) | May 22, 2023 |
| Acer          | Aspire E5-575G              | [d27d5d547e](https://linux-hardware.org/?probe=d27d5d547e) | May 21, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [a6b4b230da](https://linux-hardware.org/?probe=a6b4b230da) | May 21, 2023 |
| Lenovo        | G580 2189                   | [8e7dbefb51](https://linux-hardware.org/?probe=8e7dbefb51) | May 21, 2023 |
| Apple         | MacBookPro8,1               | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [7687732509](https://linux-hardware.org/?probe=7687732509) | May 20, 2023 |
| HP            | 350 G1                      | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [e464ddd1b6](https://linux-hardware.org/?probe=e464ddd1b6) | May 20, 2023 |
| Chuwi         | GemiBook Pro                | [a8553d6ad6](https://linux-hardware.org/?probe=a8553d6ad6) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [7f2ca00e36](https://linux-hardware.org/?probe=7f2ca00e36) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [161776168b](https://linux-hardware.org/?probe=161776168b) | May 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d4fc64a451](https://linux-hardware.org/?probe=d4fc64a451) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| ASUSTek       | TP300LA                     | [e2e6bc0209](https://linux-hardware.org/?probe=e2e6bc0209) | May 17, 2023 |
| MSI           | Stealth 15M B12UE           | [8517139acb](https://linux-hardware.org/?probe=8517139acb) | May 16, 2023 |
| AZW           | GT-R                        | [e156c5b105](https://linux-hardware.org/?probe=e156c5b105) | May 16, 2023 |
| HP            | 630                         | [3527caae6f](https://linux-hardware.org/?probe=3527caae6f) | May 16, 2023 |
| HP            | 630                         | [f34f960671](https://linux-hardware.org/?probe=f34f960671) | May 16, 2023 |
| ASUSTek       | X541UJ                      | [923f447e90](https://linux-hardware.org/?probe=923f447e90) | May 15, 2023 |
| Acer          | TravelMate P215-41-G2       | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| HP            | Presario CQ61               | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | [d697ec6804](https://linux-hardware.org/?probe=d697ec6804) | May 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [8d819952c9](https://linux-hardware.org/?probe=8d819952c9) | May 14, 2023 |
| HP            | 630                         | [40e895a75a](https://linux-hardware.org/?probe=40e895a75a) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dc1c717240](https://linux-hardware.org/?probe=dc1c717240) | May 13, 2023 |
| ASUSTek       | X551CA                      | [df0583682c](https://linux-hardware.org/?probe=df0583682c) | May 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [9dda4f6b83](https://linux-hardware.org/?probe=9dda4f6b83) | May 13, 2023 |
| Valve         | Jupiter                     | [02275a9849](https://linux-hardware.org/?probe=02275a9849) | May 13, 2023 |
| Apple         | MacBookPro11,4              | [576d66cba7](https://linux-hardware.org/?probe=576d66cba7) | May 12, 2023 |
| HP            | Pavilion Sleekbook 15       | [db2c740451](https://linux-hardware.org/?probe=db2c740451) | May 12, 2023 |
| Valve         | Jupiter                     | [4b2b4bf799](https://linux-hardware.org/?probe=4b2b4bf799) | May 12, 2023 |
| Valve         | Jupiter                     | [e89eb08b8d](https://linux-hardware.org/?probe=e89eb08b8d) | May 11, 2023 |
| Acer          | Aspire 5253G                | [c5cae82cf1](https://linux-hardware.org/?probe=c5cae82cf1) | May 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [30d9e5ca7d](https://linux-hardware.org/?probe=30d9e5ca7d) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| Dell          | XPS 15 9560                 | [62abfc3d83](https://linux-hardware.org/?probe=62abfc3d83) | May 11, 2023 |
| Dell          | XPS 15 9560                 | [4c714fc6ea](https://linux-hardware.org/?probe=4c714fc6ea) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Toshiba       | TECRA M10                   | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| Samsung       | X420/X520                   | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [2e58ce6bd7](https://linux-hardware.org/?probe=2e58ce6bd7) | May 10, 2023 |
| HP            | Compaq Mini CQ10-500        | [4b9087625d](https://linux-hardware.org/?probe=4b9087625d) | May 09, 2023 |
| HP            | 630                         | [69a6753dab](https://linux-hardware.org/?probe=69a6753dab) | May 09, 2023 |
| HP            | 630                         | [d729f66fa2](https://linux-hardware.org/?probe=d729f66fa2) | May 09, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| eMachines     | eME728                      | [031e24359e](https://linux-hardware.org/?probe=031e24359e) | May 06, 2023 |
| HP            | 630                         | [20d6860e43](https://linux-hardware.org/?probe=20d6860e43) | May 05, 2023 |
| HP            | 630                         | [57d5ffbec9](https://linux-hardware.org/?probe=57d5ffbec9) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Acer          | Nitro AN515-55              | [6264cfc1e6](https://linux-hardware.org/?probe=6264cfc1e6) | May 04, 2023 |
| Gigabyte      | G5 KD                       | [15f1eb707f](https://linux-hardware.org/?probe=15f1eb707f) | May 04, 2023 |
| MSI           | Stealth 15M B12UE           | [9e3dbb15ed](https://linux-hardware.org/?probe=9e3dbb15ed) | May 04, 2023 |
| Acer          | Aspire 5732Z                | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| Notebook      | W54_55SU1,SUW               | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [2509256cea](https://linux-hardware.org/?probe=2509256cea) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [3e7b117db0](https://linux-hardware.org/?probe=3e7b117db0) | May 03, 2023 |
| Acer          | TravelMate 5720             | [ad56dc6f51](https://linux-hardware.org/?probe=ad56dc6f51) | May 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [f2c18c96df](https://linux-hardware.org/?probe=f2c18c96df) | May 02, 2023 |
| Lenovo        | V15-ADA 82C7                | [b11670d60d](https://linux-hardware.org/?probe=b11670d60d) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Toshiba       | Satellite L50-B             | [fb815bb11c](https://linux-hardware.org/?probe=fb815bb11c) | May 02, 2023 |
| Toshiba       | Satellite L755              | [20fdcbe744](https://linux-hardware.org/?probe=20fdcbe744) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [000c0450b9](https://linux-hardware.org/?probe=000c0450b9) | May 02, 2023 |
| HP            | 240 G6 Notebook PC          | [3ca97c367a](https://linux-hardware.org/?probe=3ca97c367a) | May 01, 2023 |
| Acer          | Aspire A315-21              | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| Dell          | Inspiron 7548               | [15fe439a9a](https://linux-hardware.org/?probe=15fe439a9a) | Apr 30, 2023 |
| ASUSTek       | X555QG                      | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| MSI           | GF63 Thin 9SC               | [f6a250b3e2](https://linux-hardware.org/?probe=f6a250b3e2) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Chuwi         | HeroBook Air                | [123f6df9f8](https://linux-hardware.org/?probe=123f6df9f8) | Apr 29, 2023 |
| Sony          | VPCZ13M9E                   | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| ASUSTek       | X555QG                      | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [61151daf36](https://linux-hardware.org/?probe=61151daf36) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [a72fdebd89](https://linux-hardware.org/?probe=a72fdebd89) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [beca0f768b](https://linux-hardware.org/?probe=beca0f768b) | Apr 27, 2023 |
| Gigabyte      | G5 GD                       | [d09d6fb712](https://linux-hardware.org/?probe=d09d6fb712) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Valve         | Jupiter                     | [72f64e795a](https://linux-hardware.org/?probe=72f64e795a) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [de95ac0857](https://linux-hardware.org/?probe=de95ac0857) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [07906a30e3](https://linux-hardware.org/?probe=07906a30e3) | Apr 26, 2023 |
| MSI           | Stealth 15M B12UE           | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [8a88263cea](https://linux-hardware.org/?probe=8a88263cea) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [2f7f2efd4f](https://linux-hardware.org/?probe=2f7f2efd4f) | Apr 26, 2023 |
| MSI           | Modern 14 A10M              | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| HP            | Compaq 15                   | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| INSYS         | PT1-140C                    | [902536abce](https://linux-hardware.org/?probe=902536abce) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [db8e950d12](https://linux-hardware.org/?probe=db8e950d12) | Apr 24, 2023 |
| Acer          | Aspire E1-571G              | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e682d7b9dd](https://linux-hardware.org/?probe=e682d7b9dd) | Apr 22, 2023 |
| HP            | Notebook                    | [1d975dfc4f](https://linux-hardware.org/?probe=1d975dfc4f) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [694966dbd7](https://linux-hardware.org/?probe=694966dbd7) | Apr 22, 2023 |
| Toshiba       | Satellite L50-C             | [11f0485b1a](https://linux-hardware.org/?probe=11f0485b1a) | Apr 21, 2023 |
| Toshiba       | Satellite L50-C             | [969bbe5df0](https://linux-hardware.org/?probe=969bbe5df0) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| MSI           | Stealth 15M B12UE           | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Acer          | TravelMate B115-M           | [178dbe3693](https://linux-hardware.org/?probe=178dbe3693) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Acer          | TravelMate B115-M           | [973070ca0e](https://linux-hardware.org/?probe=973070ca0e) | Apr 19, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Toshiba       | Satellite L500              | [0896195ea4](https://linux-hardware.org/?probe=0896195ea4) | Apr 18, 2023 |
| Toshiba       | Satellite L500              | [7105145a87](https://linux-hardware.org/?probe=7105145a87) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [e9278fb49b](https://linux-hardware.org/?probe=e9278fb49b) | Apr 18, 2023 |
| MSI           | PS42 Modern 8RC             | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [879e47fc04](https://linux-hardware.org/?probe=879e47fc04) | Apr 17, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [8b6a2af9ce](https://linux-hardware.org/?probe=8b6a2af9ce) | Apr 16, 2023 |
| Medion        | E15415                      | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| HUAWEI        | MRC-WX0                     | [5b446c43f3](https://linux-hardware.org/?probe=5b446c43f3) | Apr 15, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| Dell          | Inspiron 5759               | [f3bbb04052](https://linux-hardware.org/?probe=f3bbb04052) | Apr 15, 2023 |
| Dell          | Precision 5560              | [b6d20ef4bf](https://linux-hardware.org/?probe=b6d20ef4bf) | Apr 14, 2023 |
| Dell          | Precision 5560              | [b76f840bd9](https://linux-hardware.org/?probe=b76f840bd9) | Apr 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| Lenovo        | ThinkPad T410 2537NY6       | [977014ae11](https://linux-hardware.org/?probe=977014ae11) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | [a9b7cf3c18](https://linux-hardware.org/?probe=a9b7cf3c18) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | [b2259951b5](https://linux-hardware.org/?probe=b2259951b5) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [af4ccb91b1](https://linux-hardware.org/?probe=af4ccb91b1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | [d914c2a179](https://linux-hardware.org/?probe=d914c2a179) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | [5b861c968e](https://linux-hardware.org/?probe=5b861c968e) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| Valve         | Jupiter                     | [8fdb71aed1](https://linux-hardware.org/?probe=8fdb71aed1) | Apr 12, 2023 |
| Dell          | XPS 15 9520                 | [5b01d0eda1](https://linux-hardware.org/?probe=5b01d0eda1) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [27688332ee](https://linux-hardware.org/?probe=27688332ee) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire E1-571G              | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| HP            | Laptop 15-bw0xx             | [0cef536369](https://linux-hardware.org/?probe=0cef536369) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ac983c99b9](https://linux-hardware.org/?probe=ac983c99b9) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a2dcc97485](https://linux-hardware.org/?probe=a2dcc97485) | Apr 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | [eab5adc4e6](https://linux-hardware.org/?probe=eab5adc4e6) | Apr 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [7033d674d8](https://linux-hardware.org/?probe=7033d674d8) | Apr 09, 2023 |
| HP            | Pavilion dv6                | [10eeff8916](https://linux-hardware.org/?probe=10eeff8916) | Apr 08, 2023 |
| ASUSTek       | X540LA                      | [38299d8248](https://linux-hardware.org/?probe=38299d8248) | Apr 08, 2023 |
| Dell          | Latitude E5550              | [b0e2c2e0d5](https://linux-hardware.org/?probe=b0e2c2e0d5) | Apr 07, 2023 |
| Gigabyte      | G5 GD                       | [d492c2eca8](https://linux-hardware.org/?probe=d492c2eca8) | Apr 06, 2023 |
| Dell          | Latitude E7250              | [e5fe0c7962](https://linux-hardware.org/?probe=e5fe0c7962) | Apr 06, 2023 |
| HP            | Compaq Presario CQ70        | [11cd73fbce](https://linux-hardware.org/?probe=11cd73fbce) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [705d5f2396](https://linux-hardware.org/?probe=705d5f2396) | Apr 05, 2023 |
| Dell          | Latitude E4200              | [6dae8e5ff4](https://linux-hardware.org/?probe=6dae8e5ff4) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| ASUSTek       | X58C                        | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| ASUSTek       | X58C                        | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d006e94e8f](https://linux-hardware.org/?probe=d006e94e8f) | Apr 04, 2023 |
| Valve         | Jupiter                     | [70eb6c0ec1](https://linux-hardware.org/?probe=70eb6c0ec1) | Apr 04, 2023 |
| Timi          | RedmiBook 16                | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [89d4ef9333](https://linux-hardware.org/?probe=89d4ef9333) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | [f7f0d77f00](https://linux-hardware.org/?probe=f7f0d77f00) | Apr 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Google        | Snappy                      | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | [41b51a471d](https://linux-hardware.org/?probe=41b51a471d) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | [fc4116204b](https://linux-hardware.org/?probe=fc4116204b) | Apr 01, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [6ab0a0226d](https://linux-hardware.org/?probe=6ab0a0226d) | Apr 01, 2023 |
| Intel         | Kabylake Platform           | [2b0fd79264](https://linux-hardware.org/?probe=2b0fd79264) | Mar 31, 2023 |
| Acer          | Aspire E5-571               | [45887eb5f3](https://linux-hardware.org/?probe=45887eb5f3) | Mar 31, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [59b2b4e152](https://linux-hardware.org/?probe=59b2b4e152) | Mar 31, 2023 |
| MSI           | Modern 15 A5M               | [2a00bed043](https://linux-hardware.org/?probe=2a00bed043) | Mar 31, 2023 |
| ASUSTek       | X551MA                      | [5ea823d079](https://linux-hardware.org/?probe=5ea823d079) | Mar 31, 2023 |
| Apple         | MacBookPro9,2               | [8c60cf0ec1](https://linux-hardware.org/?probe=8c60cf0ec1) | Mar 31, 2023 |
| Dell          | G15 5515                    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [faa3d2b7ad](https://linux-hardware.org/?probe=faa3d2b7ad) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| ASUSTek       | K53SD                       | [81710aaa51](https://linux-hardware.org/?probe=81710aaa51) | Mar 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [3836173aad](https://linux-hardware.org/?probe=3836173aad) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [46a8636dfd](https://linux-hardware.org/?probe=46a8636dfd) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| TEKNOSERVI... | NJ5x_NJ7xLU                 | [2a0feae3f9](https://linux-hardware.org/?probe=2a0feae3f9) | Mar 28, 2023 |
| Notebook      | L140CU                      | [98b71e9790](https://linux-hardware.org/?probe=98b71e9790) | Mar 28, 2023 |
| Dell          | Precision 5540              | [f9e20de07f](https://linux-hardware.org/?probe=f9e20de07f) | Mar 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | [574bb4272c](https://linux-hardware.org/?probe=574bb4272c) | Mar 27, 2023 |
| Dell          | Precision 3571              | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [bddc9116d1](https://linux-hardware.org/?probe=bddc9116d1) | Mar 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [6a8962feba](https://linux-hardware.org/?probe=6a8962feba) | Mar 27, 2023 |
| Samsung       | N150P/N210P/N220P           | [70d943698c](https://linux-hardware.org/?probe=70d943698c) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ca83615d40](https://linux-hardware.org/?probe=ca83615d40) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [285462b197](https://linux-hardware.org/?probe=285462b197) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [fc40632056](https://linux-hardware.org/?probe=fc40632056) | Mar 26, 2023 |
| Dell          | G15 5515                    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | [68017924d7](https://linux-hardware.org/?probe=68017924d7) | Mar 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [bee83a6b50](https://linux-hardware.org/?probe=bee83a6b50) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [8a6705ba5a](https://linux-hardware.org/?probe=8a6705ba5a) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d1427e69b3](https://linux-hardware.org/?probe=d1427e69b3) | Mar 26, 2023 |
| Notebook      | NL40_50CU                   | [4870d52d1e](https://linux-hardware.org/?probe=4870d52d1e) | Mar 25, 2023 |
| Gigabyte      | AERO 15 XD                  | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [05b2003fc0](https://linux-hardware.org/?probe=05b2003fc0) | Mar 25, 2023 |
| MSI           | PE62 7RD                    | [de18d40d94](https://linux-hardware.org/?probe=de18d40d94) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| HP            | 255 G7 Notebook PC          | [2097578b64](https://linux-hardware.org/?probe=2097578b64) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [548c06032b](https://linux-hardware.org/?probe=548c06032b) | Mar 24, 2023 |
| ASUSTek       | K52Jr                       | [a88997ecfd](https://linux-hardware.org/?probe=a88997ecfd) | Mar 24, 2023 |
| Dell          | G15 5515                    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| HP            | 2000                        | [9820715e60](https://linux-hardware.org/?probe=9820715e60) | Mar 24, 2023 |
| ASUSTek       | GL752VW                     | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | [4054877ef0](https://linux-hardware.org/?probe=4054877ef0) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | [da37222f12](https://linux-hardware.org/?probe=da37222f12) | Mar 24, 2023 |
| HP            | 2000                        | [87ba6d3696](https://linux-hardware.org/?probe=87ba6d3696) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e4a3f70cbf](https://linux-hardware.org/?probe=e4a3f70cbf) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d55de052b1](https://linux-hardware.org/?probe=d55de052b1) | Mar 23, 2023 |
| Lenovo        | G500 20236                  | [8688a57db6](https://linux-hardware.org/?probe=8688a57db6) | Mar 22, 2023 |
| Packard Be... | EasyNote LJ75               | [1a3b095372](https://linux-hardware.org/?probe=1a3b095372) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| Dell          | G3 3579                     | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Acer          | Aspire ES1-512              | [901b9b1b6b](https://linux-hardware.org/?probe=901b9b1b6b) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| HP            | 250 G4                      | [46e0314fb1](https://linux-hardware.org/?probe=46e0314fb1) | Mar 20, 2023 |
| MSI           | Pulse GL66 12UEK            | [9790d0bb28](https://linux-hardware.org/?probe=9790d0bb28) | Mar 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [77b7fd07a4](https://linux-hardware.org/?probe=77b7fd07a4) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [5c0e12ebd0](https://linux-hardware.org/?probe=5c0e12ebd0) | Mar 19, 2023 |
| Acer          | Aspire E1-532               | [ed3693c1c8](https://linux-hardware.org/?probe=ed3693c1c8) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| HP            | 250 G8 Notebook PC          | [aade64a567](https://linux-hardware.org/?probe=aade64a567) | Mar 18, 2023 |
| Chuwi         | HeroBook                    | [7a70fa6c57](https://linux-hardware.org/?probe=7a70fa6c57) | Mar 17, 2023 |
| MSI           | GF63 Thin 9SC               | [88dcbd2740](https://linux-hardware.org/?probe=88dcbd2740) | Mar 17, 2023 |
| Apple         | MacBook8,1                  | [a3ef4e5a56](https://linux-hardware.org/?probe=a3ef4e5a56) | Mar 16, 2023 |
| Valve         | Jupiter                     | [0a2038deed](https://linux-hardware.org/?probe=0a2038deed) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [428ea81050](https://linux-hardware.org/?probe=428ea81050) | Mar 15, 2023 |
| Acer          | Aspire E5-573G              | [a24986d87d](https://linux-hardware.org/?probe=a24986d87d) | Mar 15, 2023 |
| HP            | Mini 210-1000               | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| MSI           | Katana GF66 12UC            | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Intel         | powered classmate PC        | [891664a0ae](https://linux-hardware.org/?probe=891664a0ae) | Mar 14, 2023 |
| Dell          | Inspiron 14 5410            | [54ff309c3d](https://linux-hardware.org/?probe=54ff309c3d) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| Chuwi         | GemiBook Pro                | [f30cf91b1c](https://linux-hardware.org/?probe=f30cf91b1c) | Mar 13, 2023 |
| Valve         | Jupiter                     | [95598d1841](https://linux-hardware.org/?probe=95598d1841) | Mar 13, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | [a421f89675](https://linux-hardware.org/?probe=a421f89675) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | [4708653fb3](https://linux-hardware.org/?probe=4708653fb3) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [1a37e14422](https://linux-hardware.org/?probe=1a37e14422) | Mar 11, 2023 |
| Toshiba       | Satellite Pro L300          | [7c5e811612](https://linux-hardware.org/?probe=7c5e811612) | Mar 11, 2023 |
| Valve         | Jupiter                     | [07f6e9ed10](https://linux-hardware.org/?probe=07f6e9ed10) | Mar 10, 2023 |
| Dynabook      | Satellite Pro C50-G         | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| MSI           | GL75 Leopard 10SEK          | [9fdc1bd5c4](https://linux-hardware.org/?probe=9fdc1bd5c4) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Dell          | Latitude E5420              | [9b346e0658](https://linux-hardware.org/?probe=9b346e0658) | Mar 10, 2023 |
| Acer          | Aspire 5750G                | [b4af1eb2cb](https://linux-hardware.org/?probe=b4af1eb2cb) | Mar 10, 2023 |
| Acer          | Aspire M3-581G              | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| Dell          | Latitude E6540              | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Chuwi         | GemiBook Pro                | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Intel         | powered classmate PC        | [c25d03cf3f](https://linux-hardware.org/?probe=c25d03cf3f) | Mar 09, 2023 |
| Intel         | powered classmate PC        | [8c62787a5b](https://linux-hardware.org/?probe=8c62787a5b) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fd15fc475a](https://linux-hardware.org/?probe=fd15fc475a) | Mar 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [0e054a9861](https://linux-hardware.org/?probe=0e054a9861) | Mar 08, 2023 |
| HP            | Pavilion g6                 | [35f93de82d](https://linux-hardware.org/?probe=35f93de82d) | Mar 08, 2023 |
| ASUSTek       | K53SC                       | [bd182b6d80](https://linux-hardware.org/?probe=bd182b6d80) | Mar 08, 2023 |
| Sony          | SVF1521B1EW                 | [5b5a9dbc40](https://linux-hardware.org/?probe=5b5a9dbc40) | Mar 08, 2023 |
| Acer          | Aspire 5740                 | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| Notebook      | N2x0WU                      | [4948392f03](https://linux-hardware.org/?probe=4948392f03) | Mar 06, 2023 |
| Fujitsu Si... | STYLISTIC ST6012            | [0d9314f673](https://linux-hardware.org/?probe=0d9314f673) | Mar 06, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| Intel         | powered classmate PC        | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Chuwi         | HeroBook Air                | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Lenovo        | ThinkPad E490 20N8002ASP    | [9b91ef4633](https://linux-hardware.org/?probe=9b91ef4633) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3a2e77122d](https://linux-hardware.org/?probe=3a2e77122d) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Dell          | G5 5590                     | [75f2235434](https://linux-hardware.org/?probe=75f2235434) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| Apple         | MacBookPro6,2               | [3696f0b49e](https://linux-hardware.org/?probe=3696f0b49e) | Feb 27, 2023 |
| HP            | 250 G7 Notebook PC          | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Notebook                    | [06dba3c8b3](https://linux-hardware.org/?probe=06dba3c8b3) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [02608a8288](https://linux-hardware.org/?probe=02608a8288) | Feb 25, 2023 |
| HP            | EliteBook Folio 9470m       | [8cc1fdf5b4](https://linux-hardware.org/?probe=8cc1fdf5b4) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Acer          | AOD255                      | [f5f5ed9b36](https://linux-hardware.org/?probe=f5f5ed9b36) | Feb 24, 2023 |
| Acer          | Aspire S3                   | [9d0301c490](https://linux-hardware.org/?probe=9d0301c490) | Feb 24, 2023 |
| Valve         | Jupiter                     | [08585b6c97](https://linux-hardware.org/?probe=08585b6c97) | Feb 24, 2023 |
| Lenovo        | ThinkPad X201 3680U6V       | [abcf384939](https://linux-hardware.org/?probe=abcf384939) | Feb 23, 2023 |
| Acer          | AOD255                      | [b4ccf00506](https://linux-hardware.org/?probe=b4ccf00506) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| HP            | Compaq 6720s                | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| HP            | Pavilion 15                 | [48439104ea](https://linux-hardware.org/?probe=48439104ea) | Feb 23, 2023 |
| Gigabyte      | G5 KD                       | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| Sony          | SVF1521N6EW                 | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Acer          | Swift SF514-54T             | [ebbff689ba](https://linux-hardware.org/?probe=ebbff689ba) | Feb 22, 2023 |
| Acer          | TravelMate P256-MG          | [4dbdb229c5](https://linux-hardware.org/?probe=4dbdb229c5) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [50f5c21eeb](https://linux-hardware.org/?probe=50f5c21eeb) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Toshiba       | PORTEGE Z30-A               | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Unknown       | Unknown                     | [e48cf758d0](https://linux-hardware.org/?probe=e48cf758d0) | Feb 19, 2023 |
| Dell          | XPS M1530                   | [c2f2509941](https://linux-hardware.org/?probe=c2f2509941) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [84d8598da2](https://linux-hardware.org/?probe=84d8598da2) | Feb 18, 2023 |
| Sony          | VPCZ13M9E                   | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| Unknown       | Unknown                     | [8cdf723a7d](https://linux-hardware.org/?probe=8cdf723a7d) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| HP            | G61                         | [52bb3c7afb](https://linux-hardware.org/?probe=52bb3c7afb) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| ASUSTek       | GL553VD                     | [97f3fd27fa](https://linux-hardware.org/?probe=97f3fd27fa) | Feb 16, 2023 |
| Acer          | Aspire V3-372               | [bde68b3ed7](https://linux-hardware.org/?probe=bde68b3ed7) | Feb 16, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [abc91903be](https://linux-hardware.org/?probe=abc91903be) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| Lenovo        | ThinkPad T510 43147VG       | [16b032ccc3](https://linux-hardware.org/?probe=16b032ccc3) | Feb 16, 2023 |
| Acer          | Aspire ES1-512              | [a21a70af4c](https://linux-hardware.org/?probe=a21a70af4c) | Feb 15, 2023 |
| Unknown       | Unknown                     | [7fd524ac5b](https://linux-hardware.org/?probe=7fd524ac5b) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| Acer          | Extensa 5230                | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | [fcf87be002](https://linux-hardware.org/?probe=fcf87be002) | Feb 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [a4f13f23ce](https://linux-hardware.org/?probe=a4f13f23ce) | Feb 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [9368822d6a](https://linux-hardware.org/?probe=9368822d6a) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| Gigabyte      | RC14UD                      | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Acer          | Extensa 5220                | [87682be3fd](https://linux-hardware.org/?probe=87682be3fd) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Google        | Droid                       | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Acer          | Extensa 5230                | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [96dfdd671c](https://linux-hardware.org/?probe=96dfdd671c) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| MSI           | Prestige 15 A12UD           | [9688180ef7](https://linux-hardware.org/?probe=9688180ef7) | Feb 11, 2023 |
| Dell          | Latitude 5290 2-in-1        | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | [c56001eede](https://linux-hardware.org/?probe=c56001eede) | Feb 10, 2023 |
| HP            | Pavilion 15                 | [408fd874e7](https://linux-hardware.org/?probe=408fd874e7) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Acer          | Aspire A515-51              | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| Lenovo        | ThinkPad P53s 20N6CTO1WW    | [6b74ce317f](https://linux-hardware.org/?probe=6b74ce317f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| Acer          | Aspire E5-573G              | [8400619736](https://linux-hardware.org/?probe=8400619736) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| Unknown       | Unknown                     | [b541173c03](https://linux-hardware.org/?probe=b541173c03) | Feb 09, 2023 |
| Samsung       | R530/R730                   | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Lenovo        | B50-70 80EU                 | [637336f0d0](https://linux-hardware.org/?probe=637336f0d0) | Feb 07, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [3b6bf45c6b](https://linux-hardware.org/?probe=3b6bf45c6b) | Feb 07, 2023 |
| Unknown       | Unknown                     | [556a341257](https://linux-hardware.org/?probe=556a341257) | Feb 06, 2023 |
| Acer          | Aspire ES1-512              | [75b3a6b384](https://linux-hardware.org/?probe=75b3a6b384) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| WinPAD 110... | I102A                       | [0619bb5a8d](https://linux-hardware.org/?probe=0619bb5a8d) | Feb 04, 2023 |
| Teclast       | F7S                         | [d4384ca831](https://linux-hardware.org/?probe=d4384ca831) | Feb 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | [b80bfcae04](https://linux-hardware.org/?probe=b80bfcae04) | Feb 04, 2023 |
| HP            | Pavilion dv6700             | [d3755b3636](https://linux-hardware.org/?probe=d3755b3636) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| Acer          | Aspire ES1-512              | [278fbf008f](https://linux-hardware.org/?probe=278fbf008f) | Feb 03, 2023 |
| Valve         | Jupiter                     | [75208bbb30](https://linux-hardware.org/?probe=75208bbb30) | Feb 03, 2023 |
| Acer          | Aspire A315-58              | [32563eeffc](https://linux-hardware.org/?probe=32563eeffc) | Feb 03, 2023 |
| Unknown       | Unknown                     | [8a95ab4f06](https://linux-hardware.org/?probe=8a95ab4f06) | Feb 03, 2023 |
| Acer          | AOD255                      | [1b65896663](https://linux-hardware.org/?probe=1b65896663) | Feb 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [50d19e4206](https://linux-hardware.org/?probe=50d19e4206) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| Apple         | MacBookPro11,1              | [44f90bc9ab](https://linux-hardware.org/?probe=44f90bc9ab) | Feb 01, 2023 |
| HP            | Presario CQ57               | [0e34caefa3](https://linux-hardware.org/?probe=0e34caefa3) | Feb 01, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK AH532              | [cf200b9cf1](https://linux-hardware.org/?probe=cf200b9cf1) | Jan 30, 2023 |
| MSI           | GF75 Thin 10UE              | [1177ccc150](https://linux-hardware.org/?probe=1177ccc150) | Jan 30, 2023 |
| Toshiba       | PORTEGE X30-E               | [01f74415b0](https://linux-hardware.org/?probe=01f74415b0) | Jan 30, 2023 |
| HP            | G62                         | [166ddbe627](https://linux-hardware.org/?probe=166ddbe627) | Jan 29, 2023 |
| HP            | ProBook 5320m               | [b8fc81e61c](https://linux-hardware.org/?probe=b8fc81e61c) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T420 4236PN3       | [3b5c51e8b8](https://linux-hardware.org/?probe=3b5c51e8b8) | Jan 29, 2023 |
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| ASUSTek       | X555LD                      | [3a3e1fafdf](https://linux-hardware.org/?probe=3a3e1fafdf) | Jan 28, 2023 |
| Valve         | Jupiter                     | [4a823b2eef](https://linux-hardware.org/?probe=4a823b2eef) | Jan 28, 2023 |
| ASUSTek       | ProArt StudioBook H7600H... | [8e9b78c0e8](https://linux-hardware.org/?probe=8e9b78c0e8) | Jan 28, 2023 |
| ASUSTek       | X751LB                      | [54094ae0a7](https://linux-hardware.org/?probe=54094ae0a7) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| Samsung       | R520/R522/R620              | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Notebook      | N13_N140ZU                  | [94396ecebc](https://linux-hardware.org/?probe=94396ecebc) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| Packard Be... | EasyNote TS44HR             | [2902a743da](https://linux-hardware.org/?probe=2902a743da) | Jan 26, 2023 |
| MSI           | Raider GE76 12UHS           | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| Acer          | Nitro AN515-52              | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| HP            | Pavilion g6                 | [a247cbd6d4](https://linux-hardware.org/?probe=a247cbd6d4) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [07d5199d1c](https://linux-hardware.org/?probe=07d5199d1c) | Jan 25, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [a1a1be6b56](https://linux-hardware.org/?probe=a1a1be6b56) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Samsung       | 305V4A/305V5A               | [0f78cdd47e](https://linux-hardware.org/?probe=0f78cdd47e) | Jan 23, 2023 |
| Chuwi         | GemiBook Pro                | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Qilive        | QW2214SP                    | [2dba516c91](https://linux-hardware.org/?probe=2dba516c91) | Jan 22, 2023 |
| Clevo         | W150ER                      | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| MSI           | Stealth 15M B12UE           | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| Acer          | Aspire E1-530               | [af5f0b7f58](https://linux-hardware.org/?probe=af5f0b7f58) | Jan 21, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [65919b95b4](https://linux-hardware.org/?probe=65919b95b4) | Jan 20, 2023 |
| Toshiba       | NB520                       | [0252e3bec1](https://linux-hardware.org/?probe=0252e3bec1) | Jan 20, 2023 |
| HP            | Stream Notebook PC 11       | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | Latitude 5410               | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [0d3da58e45](https://linux-hardware.org/?probe=0d3da58e45) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| Dell          | Latitude 7490               | [390dc07426](https://linux-hardware.org/?probe=390dc07426) | Jan 17, 2023 |
| ASUSTek       | 1018P                       | [45cdf08df5](https://linux-hardware.org/?probe=45cdf08df5) | Jan 16, 2023 |
| HP            | EliteBook 840 G6            | [5a622c4769](https://linux-hardware.org/?probe=5a622c4769) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Acer          | Aspire 5742G                | [5cda575387](https://linux-hardware.org/?probe=5cda575387) | Jan 16, 2023 |
| HUAWEI        | BOD-WXX9                    | [c854a01151](https://linux-hardware.org/?probe=c854a01151) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | [b0abb21613](https://linux-hardware.org/?probe=b0abb21613) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | [623477fd9e](https://linux-hardware.org/?probe=623477fd9e) | Jan 16, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [a8ab10ee00](https://linux-hardware.org/?probe=a8ab10ee00) | Jan 16, 2023 |
| ASUSTek       | K55DR                       | [0dde03d33e](https://linux-hardware.org/?probe=0dde03d33e) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| Sony          | VGN-AR51J                   | [ff9806f1ac](https://linux-hardware.org/?probe=ff9806f1ac) | Jan 15, 2023 |
| Dell          | Latitude E5550              | [ccbb0c484f](https://linux-hardware.org/?probe=ccbb0c484f) | Jan 15, 2023 |
| Dell          | Latitude E5550              | [28471496b4](https://linux-hardware.org/?probe=28471496b4) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | [9816c00c67](https://linux-hardware.org/?probe=9816c00c67) | Jan 15, 2023 |
| HP            | Presario CQ57               | [f223ceb77a](https://linux-hardware.org/?probe=f223ceb77a) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | [812b55536d](https://linux-hardware.org/?probe=812b55536d) | Jan 15, 2023 |
| Apple         | MacBookAir6,2               | [2931eab7f7](https://linux-hardware.org/?probe=2931eab7f7) | Jan 15, 2023 |
| Chuwi         | GemiBook Pro                | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| MSI           | Stealth GS77 12UHS          | [0dba4d0126](https://linux-hardware.org/?probe=0dba4d0126) | Jan 14, 2023 |
| Lenovo        | B51-80 80LM                 | [0c5b712b3e](https://linux-hardware.org/?probe=0c5b712b3e) | Jan 14, 2023 |
| MSI           | Stealth GS77 12UHS          | [6a6636d3ba](https://linux-hardware.org/?probe=6a6636d3ba) | Jan 14, 2023 |
| eMachines     | E725                        | [048d832cef](https://linux-hardware.org/?probe=048d832cef) | Jan 13, 2023 |
| MSI           | Katana GF66 11UC            | [39b5188695](https://linux-hardware.org/?probe=39b5188695) | Jan 12, 2023 |
| HP            | Mini 110-3100               | [e6f11256b8](https://linux-hardware.org/?probe=e6f11256b8) | Jan 12, 2023 |
| Samsung       | RF510/RF410/RF710           | [9d63c96c7a](https://linux-hardware.org/?probe=9d63c96c7a) | Jan 12, 2023 |
| Acer          | Aspire A315-56              | [6ea0b8eab9](https://linux-hardware.org/?probe=6ea0b8eab9) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| ALLDOCUBE     | i1405C                      | [0713c94107](https://linux-hardware.org/?probe=0713c94107) | Jan 11, 2023 |
| Dell          | Inspiron 15-3552            | [e4ca0a9947](https://linux-hardware.org/?probe=e4ca0a9947) | Jan 11, 2023 |
| ASUSTek       | X541UV                      | [41358ca49b](https://linux-hardware.org/?probe=41358ca49b) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| Toshiba       | Satellite Pro NB10-A-12Q    | [f0c82d2046](https://linux-hardware.org/?probe=f0c82d2046) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| Acer          | Aspire 5253G                | [930e997f3a](https://linux-hardware.org/?probe=930e997f3a) | Jan 11, 2023 |
| ASUSTek       | K53U                        | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Sony          | VPCCW1S1E                   | [5cc5248e94](https://linux-hardware.org/?probe=5cc5248e94) | Jan 10, 2023 |
| HP            | Notebook                    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| MSI           | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [be6a0a28e1](https://linux-hardware.org/?probe=be6a0a28e1) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| MSI           | Modern 14 B10RBSW           | [3dea4fbc97](https://linux-hardware.org/?probe=3dea4fbc97) | Jan 10, 2023 |
| Acer          | Aspire E1-531G              | [2476cc24c1](https://linux-hardware.org/?probe=2476cc24c1) | Jan 10, 2023 |
| ASUSTek       | K53SC                       | [002a8bdf0c](https://linux-hardware.org/?probe=002a8bdf0c) | Jan 09, 2023 |
| Acer          | Aspire E5-551G              | [dc659db065](https://linux-hardware.org/?probe=dc659db065) | Jan 09, 2023 |
| ASUSTek       | K54L                        | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Lenovo        | G480 20150                  | [31f01e01fe](https://linux-hardware.org/?probe=31f01e01fe) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | [532f3544a2](https://linux-hardware.org/?probe=532f3544a2) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| Dell          | Studio 1558                 | [0e01a19694](https://linux-hardware.org/?probe=0e01a19694) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| MSI           | Bravo 17 A4DDK              | [cf73810d98](https://linux-hardware.org/?probe=cf73810d98) | Jan 08, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| ASUSTek       | X540YA                      | [b7021632b6](https://linux-hardware.org/?probe=b7021632b6) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [333358164d](https://linux-hardware.org/?probe=333358164d) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Acer          | TravelMate P256-MG          | [e090a2b61c](https://linux-hardware.org/?probe=e090a2b61c) | Jan 07, 2023 |
| ASUSTek       | K53U                        | [46610b735e](https://linux-hardware.org/?probe=46610b735e) | Jan 07, 2023 |
| Google        | Candy                       | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| Chuwi         | HeroBook Air                | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6e3d10ba74](https://linux-hardware.org/?probe=6e3d10ba74) | Jan 06, 2023 |
| Apple         | MacBookPro4,1               | [9fd9040304](https://linux-hardware.org/?probe=9fd9040304) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| MSI           | Stealth 15M B12UE           | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| HP            | 250 G2                      | [430425dd1c](https://linux-hardware.org/?probe=430425dd1c) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Samsung       | RF510/RF410/RF710           | [3da2c535f7](https://linux-hardware.org/?probe=3da2c535f7) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| ASUSTek       | X550VX                      | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| Samsung       | RF510/RF410/RF710           | [220854be2e](https://linux-hardware.org/?probe=220854be2e) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | [5ada77ec03](https://linux-hardware.org/?probe=5ada77ec03) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | [817985e5bf](https://linux-hardware.org/?probe=817985e5bf) | Jan 01, 2023 |
| ASUSTek       | K53SC                       | [25912a6795](https://linux-hardware.org/?probe=25912a6795) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| MSI           | Stealth 15M B12UE           | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| HP            | 250 G8 Notebook PC          | [6b8db26ab8](https://linux-hardware.org/?probe=6b8db26ab8) | Dec 30, 2022 |
| Dell          | Latitude 9420               | [3c43afbd50](https://linux-hardware.org/?probe=3c43afbd50) | Dec 29, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [8e201646a8](https://linux-hardware.org/?probe=8e201646a8) | Dec 29, 2022 |
| HP            | ZBook 15 G2                 | [6d1ae8a0c9](https://linux-hardware.org/?probe=6d1ae8a0c9) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2ea31ca86e](https://linux-hardware.org/?probe=2ea31ca86e) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| HP            | Mini 100e                   | [dd184e04ad](https://linux-hardware.org/?probe=dd184e04ad) | Dec 28, 2022 |
| Gigabyte      | AERO 17 XE5                 | [979483f168](https://linux-hardware.org/?probe=979483f168) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| Valve         | Jupiter                     | [15cbe24d03](https://linux-hardware.org/?probe=15cbe24d03) | Dec 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9dec6385d7](https://linux-hardware.org/?probe=9dec6385d7) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| MSI           | MS-7A34                     | [4668f06370](https://linux-hardware.org/?probe=4668f06370) | Dec 26, 2022 |
| HP            | Mini 100e                   | [bf749ac406](https://linux-hardware.org/?probe=bf749ac406) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | [9b26454313](https://linux-hardware.org/?probe=9b26454313) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | [ee842c64a3](https://linux-hardware.org/?probe=ee842c64a3) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| Acer          | Aspire 5732Z                | [96bc08bcbd](https://linux-hardware.org/?probe=96bc08bcbd) | Dec 26, 2022 |
| ASUSTek       | K55VD                       | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [72fa60782d](https://linux-hardware.org/?probe=72fa60782d) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [419580e899](https://linux-hardware.org/?probe=419580e899) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| ASUSTek       | K52JT                       | [915e35ba2b](https://linux-hardware.org/?probe=915e35ba2b) | Dec 24, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [2c6f47974f](https://linux-hardware.org/?probe=2c6f47974f) | Dec 23, 2022 |
| Valve         | Jupiter                     | [fc52b9e656](https://linux-hardware.org/?probe=fc52b9e656) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Acer          | Predator PH315-54           | [84bdb8f2eb](https://linux-hardware.org/?probe=84bdb8f2eb) | Dec 23, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c47eaa75b3](https://linux-hardware.org/?probe=c47eaa75b3) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| Acer          | Aspire A315-54              | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | B590 62743PG                | [622f5d6e45](https://linux-hardware.org/?probe=622f5d6e45) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Acer          | Predator PH315-54           | [c291063360](https://linux-hardware.org/?probe=c291063360) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| Dell          | Latitude E5420              | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| Alienware     | x17 R1                      | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1deb35f268](https://linux-hardware.org/?probe=1deb35f268) | Dec 17, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [be60ec8881](https://linux-hardware.org/?probe=be60ec8881) | Dec 17, 2022 |
| Valve         | Jupiter                     | [4a37142af9](https://linux-hardware.org/?probe=4a37142af9) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| HP            | EliteBook 850 G1            | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| ASUSTek       | X550VX                      | [0ee46688fb](https://linux-hardware.org/?probe=0ee46688fb) | Dec 14, 2022 |
| MSI           | GF63 Thin 9SC               | [e8dcf65234](https://linux-hardware.org/?probe=e8dcf65234) | Dec 14, 2022 |
| Dell          | Vostro 14 5410              | [d858d468cc](https://linux-hardware.org/?probe=d858d468cc) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Dell          | XPS 15 9550                 | [61905b4fac](https://linux-hardware.org/?probe=61905b4fac) | Dec 13, 2022 |
| Acer          | Nitro AN515-58              | [9c13949220](https://linux-hardware.org/?probe=9c13949220) | Dec 13, 2022 |
| Dell          | Inspiron 3493               | [8ee8a5a64c](https://linux-hardware.org/?probe=8ee8a5a64c) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | Notebook                    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Unknown       | Unknown                     | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| MSI           | Modern 14 A10RB             | [849203accb](https://linux-hardware.org/?probe=849203accb) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| HP            | Laptop 15-bw0xx             | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| HP            | 620                         | [65ef44647a](https://linux-hardware.org/?probe=65ef44647a) | Dec 11, 2022 |
| Lenovo        | G710                        | [e1c54d8bc8](https://linux-hardware.org/?probe=e1c54d8bc8) | Dec 10, 2022 |
| Lenovo        | G710                        | [b2231f4343](https://linux-hardware.org/?probe=b2231f4343) | Dec 10, 2022 |
| Valve         | Jupiter                     | [e8e7f4358d](https://linux-hardware.org/?probe=e8e7f4358d) | Dec 10, 2022 |
| HP            | ProBook 650 G2              | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d7b8344d86](https://linux-hardware.org/?probe=d7b8344d86) | Dec 09, 2022 |
| Dell          | Latitude E6500              | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | [3327de3dc5](https://linux-hardware.org/?probe=3327de3dc5) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2A50... | [082e17aab7](https://linux-hardware.org/?probe=082e17aab7) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [302b36a67e](https://linux-hardware.org/?probe=302b36a67e) | Dec 05, 2022 |
| Toshiba       | PORTEGE M800                | [baf04ad2b3](https://linux-hardware.org/?probe=baf04ad2b3) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | [5ae5166847](https://linux-hardware.org/?probe=5ae5166847) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | [1a52a1c699](https://linux-hardware.org/?probe=1a52a1c699) | Dec 05, 2022 |
| Valve         | Jupiter                     | [a1975d14f5](https://linux-hardware.org/?probe=a1975d14f5) | Dec 04, 2022 |
| Acer          | Aspire E5-573               | [30f8bd2ae9](https://linux-hardware.org/?probe=30f8bd2ae9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c544d40ecb](https://linux-hardware.org/?probe=c544d40ecb) | Dec 02, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Acer          | Aspire A315-34              | [6bf371252b](https://linux-hardware.org/?probe=6bf371252b) | Nov 30, 2022 |
| ASUSTek       | UX550VD                     | [a3f2aafbf1](https://linux-hardware.org/?probe=a3f2aafbf1) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b4aeee5799](https://linux-hardware.org/?probe=b4aeee5799) | Nov 30, 2022 |
| HP            | EliteBook 860 16 inch G9... | [dda393ca54](https://linux-hardware.org/?probe=dda393ca54) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Aspire A315-34              | [56bb76fb28](https://linux-hardware.org/?probe=56bb76fb28) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [ddad96715a](https://linux-hardware.org/?probe=ddad96715a) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| HP            | Notebook                    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| HP            | ProBook 450 G5              | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | [d5f03d47ba](https://linux-hardware.org/?probe=d5f03d47ba) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | [e0701bc81d](https://linux-hardware.org/?probe=e0701bc81d) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | [8bd9aae635](https://linux-hardware.org/?probe=8bd9aae635) | Nov 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [c95bbb16de](https://linux-hardware.org/?probe=c95bbb16de) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | [3be194cb8a](https://linux-hardware.org/?probe=3be194cb8a) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| ASUSTek       | X555YA                      | [0e9bb436b5](https://linux-hardware.org/?probe=0e9bb436b5) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [419b7f448b](https://linux-hardware.org/?probe=419b7f448b) | Nov 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [4393448090](https://linux-hardware.org/?probe=4393448090) | Nov 25, 2022 |
| HP            | ProBook 430 G3              | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| Apple         | MacBook5,1                  | [f2ecb3f4a8](https://linux-hardware.org/?probe=f2ecb3f4a8) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [347af27c05](https://linux-hardware.org/?probe=347af27c05) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8bd0cdff15](https://linux-hardware.org/?probe=8bd0cdff15) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Apple         | MacBook5,1                  | [9311687e42](https://linux-hardware.org/?probe=9311687e42) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Acer          | Extensa 5220                | [0bf5f727ac](https://linux-hardware.org/?probe=0bf5f727ac) | Nov 19, 2022 |
| Acer          | Aspire E1-572G              | [36c1e37d05](https://linux-hardware.org/?probe=36c1e37d05) | Nov 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea12bf4774](https://linux-hardware.org/?probe=ea12bf4774) | Nov 18, 2022 |
| HP            | Elite x2 1012 G1            | [ef366c64fe](https://linux-hardware.org/?probe=ef366c64fe) | Nov 18, 2022 |
| Samsung       | R610                        | [b6c7aa2939](https://linux-hardware.org/?probe=b6c7aa2939) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| Apple         | MacBookPro14,1              | [248fcb5f13](https://linux-hardware.org/?probe=248fcb5f13) | Nov 17, 2022 |
| Acer          | Extensa 5220                | [8e9441be64](https://linux-hardware.org/?probe=8e9441be64) | Nov 17, 2022 |
| Toshiba       | Satellite L10W-B-101        | [544ad40774](https://linux-hardware.org/?probe=544ad40774) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b139741f4f](https://linux-hardware.org/?probe=b139741f4f) | Nov 15, 2022 |
| Dell          | Latitude E5470              | [ae3d91be5a](https://linux-hardware.org/?probe=ae3d91be5a) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| ALURIN        | PR1-M146                    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [722455f99d](https://linux-hardware.org/?probe=722455f99d) | Nov 14, 2022 |
| Lenovo        | V14-ADA 82C6                | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| Dell          | G3 3579                     | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Dell          | XPS 13 9343                 | [fed6627c3e](https://linux-hardware.org/?probe=fed6627c3e) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [76609a3bd3](https://linux-hardware.org/?probe=76609a3bd3) | Nov 12, 2022 |
| HP            | Pavilion 15                 | [f6125d7605](https://linux-hardware.org/?probe=f6125d7605) | Nov 11, 2022 |
| HP            | Pavilion 15                 | [a598e64905](https://linux-hardware.org/?probe=a598e64905) | Nov 11, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| LG Electro... | 16Z90Q-G.AD78B              | [e5129b607e](https://linux-hardware.org/?probe=e5129b607e) | Nov 09, 2022 |
| HP            | Pavilion g7                 | [3a18145808](https://linux-hardware.org/?probe=3a18145808) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [94746f0b72](https://linux-hardware.org/?probe=94746f0b72) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [61bf21f7dd](https://linux-hardware.org/?probe=61bf21f7dd) | Nov 09, 2022 |
| Valve         | Jupiter                     | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [c36ab935b5](https://linux-hardware.org/?probe=c36ab935b5) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [bbb94242ec](https://linux-hardware.org/?probe=bbb94242ec) | Nov 07, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [000b225d22](https://linux-hardware.org/?probe=000b225d22) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [80dc1502e1](https://linux-hardware.org/?probe=80dc1502e1) | Nov 06, 2022 |
| LG Electro... | 15Z990-V.AA78B              | [5ca4c426d8](https://linux-hardware.org/?probe=5ca4c426d8) | Nov 05, 2022 |
| HP            | Laptop 15-bs0xx             | [431f0124a5](https://linux-hardware.org/?probe=431f0124a5) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Valve         | Jupiter                     | [5c5b229108](https://linux-hardware.org/?probe=5c5b229108) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| HP            | Compaq Presario A900        | [4c48500597](https://linux-hardware.org/?probe=4c48500597) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [bd3b4f723e](https://linux-hardware.org/?probe=bd3b4f723e) | Nov 04, 2022 |
| HP            | EliteBook Folio 1040 G1     | [1582ffa7f2](https://linux-hardware.org/?probe=1582ffa7f2) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| Valve         | Jupiter                     | [62160ec2e5](https://linux-hardware.org/?probe=62160ec2e5) | Nov 03, 2022 |
| HP            | G62                         | [a00ba1aae7](https://linux-hardware.org/?probe=a00ba1aae7) | Nov 03, 2022 |
| HP            | 250 G4                      | [ff497e0d4c](https://linux-hardware.org/?probe=ff497e0d4c) | Nov 02, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [44e281e52c](https://linux-hardware.org/?probe=44e281e52c) | Nov 02, 2022 |
| Valve         | Jupiter                     | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Samsung       | 305V4A/305V5A               | [5df933ddda](https://linux-hardware.org/?probe=5df933ddda) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Toshiba       | Satellite L50-C             | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | [3db734a533](https://linux-hardware.org/?probe=3db734a533) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Panasonic     | CF-19RDRCHH7                | [99e94a7708](https://linux-hardware.org/?probe=99e94a7708) | Oct 31, 2022 |
| Fujitsu       | LIFEBOOK T904               | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [8dfb7265a9](https://linux-hardware.org/?probe=8dfb7265a9) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8cfddfcbf](https://linux-hardware.org/?probe=b8cfddfcbf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| Apple         | MacBookPro16,1              | [eba036175b](https://linux-hardware.org/?probe=eba036175b) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| MSI           | GE66 Raider 10UE            | [334d883dd3](https://linux-hardware.org/?probe=334d883dd3) | Oct 27, 2022 |
| Acer          | Aspire A315-21              | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| Lenovo        | G500 20236                  | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [81a4c0f5d5](https://linux-hardware.org/?probe=81a4c0f5d5) | Oct 26, 2022 |
| Acer          | Aspire ES1-511              | [0db2597f65](https://linux-hardware.org/?probe=0db2597f65) | Oct 26, 2022 |
| Apple         | MacBook5,1                  | [a7fa475b56](https://linux-hardware.org/?probe=a7fa475b56) | Oct 25, 2022 |
| ALURIN        | PR1-M146                    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490s 20NYS6FL0... | [ef0cad4118](https://linux-hardware.org/?probe=ef0cad4118) | Oct 25, 2022 |
| ASUSTek       | X550EA                      | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| HP            | Pavilion g6                 | [55a5d78e1c](https://linux-hardware.org/?probe=55a5d78e1c) | Oct 22, 2022 |
| HUAWEI        | RLEF-XX                     | [5bebcbd76d](https://linux-hardware.org/?probe=5bebcbd76d) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| HP            | 15                          | [937cf874b0](https://linux-hardware.org/?probe=937cf874b0) | Oct 21, 2022 |
| Toshiba       | Satellite P50-B-103         | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [85a58721ed](https://linux-hardware.org/?probe=85a58721ed) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| ASUSTek       | K54C                        | [124cad3faf](https://linux-hardware.org/?probe=124cad3faf) | Oct 20, 2022 |
| Valve         | Jupiter                     | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| MSI           | Modern 14 C12M              | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| HP            | Pavilion Notebook           | [462a0f1d13](https://linux-hardware.org/?probe=462a0f1d13) | Oct 18, 2022 |
| Chuwi         | HeroBook Air                | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Dell          | Latitude E6330              | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| MSI           | Stealth GS66 12UGS          | [10f52ac957](https://linux-hardware.org/?probe=10f52ac957) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| ASUSTek       | X540LA                      | [1680f919c8](https://linux-hardware.org/?probe=1680f919c8) | Oct 15, 2022 |
| Google        | Liara                       | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| VANT          | MOOVE3-15                   | [ed3f1f2728](https://linux-hardware.org/?probe=ed3f1f2728) | Oct 13, 2022 |
| HP            | Laptop 17-cn2xxx            | [55bdfc4aef](https://linux-hardware.org/?probe=55bdfc4aef) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3e43886af3](https://linux-hardware.org/?probe=3e43886af3) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Dell          | Latitude E7240              | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [a0833e04a4](https://linux-hardware.org/?probe=a0833e04a4) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [dc29e6568f](https://linux-hardware.org/?probe=dc29e6568f) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [b188c7c0dc](https://linux-hardware.org/?probe=b188c7c0dc) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [e2b4876c6e](https://linux-hardware.org/?probe=e2b4876c6e) | Oct 07, 2022 |
| HUAWEI        | RLEF-XX                     | [81f1574f73](https://linux-hardware.org/?probe=81f1574f73) | Oct 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [3ade8f820b](https://linux-hardware.org/?probe=3ade8f820b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Toshiba       | Satellite R830              | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| MSI           | Creator Z16 A11UE           | [ad24aa79d7](https://linux-hardware.org/?probe=ad24aa79d7) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| Valve         | Jupiter                     | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| HP            | Pavilion Notebook           | [17c8e22c3b](https://linux-hardware.org/?probe=17c8e22c3b) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | Notebook                    | [58dd536d7d](https://linux-hardware.org/?probe=58dd536d7d) | Oct 04, 2022 |
| Acer          | Extensa 5230                | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Acer          | Aspire 5253G                | [6bd00aec7a](https://linux-hardware.org/?probe=6bd00aec7a) | Oct 04, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Samsung       | N248P/N143P                 | [56e4d025af](https://linux-hardware.org/?probe=56e4d025af) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Valve         | Jupiter                     | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Valve         | Jupiter                     | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 394       | 12.63%  |
| Ubuntu 18.04       | 255       | 8.18%   |
| Ubuntu 22.04       | 157       | 5.03%   |
| Debian 11          | 135       | 4.33%   |
| OpenMandriva 4.2   | 84        | 2.69%   |
| Zorin 16           | 68        | 2.18%   |
| KDE neon 20.04     | 63        | 2.02%   |
| OpenMandriva 4.3   | 61        | 1.96%   |
| Linux Mint 20.3    | 45        | 1.44%   |
| Arch               | 41        | 1.31%   |
| Xubuntu 20.04      | 39        | 1.25%   |
| Ubuntu 20.10       | 39        | 1.25%   |
| Manjaro            | 38        | 1.22%   |
| OpenMandriva 23.01 | 37        | 1.19%   |
| Linux Mint 19.3    | 37        | 1.19%   |
| Arch Rolling       | 37        | 1.19%   |
| Debian 10          | 36        | 1.15%   |
| Ubuntu 19.10       | 34        | 1.09%   |
| Linux Mint 21.1    | 34        | 1.09%   |
| Ubuntu 21.04       | 32        | 1.03%   |
| Ubuntu 19.04       | 32        | 1.03%   |
| Linux Mint 20.1    | 32        | 1.03%   |
| Linux Mint 20      | 30        | 0.96%   |
| Kubuntu 20.04      | 30        | 0.96%   |
| Fedora 37          | 30        | 0.96%   |
| Fedora 36          | 30        | 0.96%   |
| Ubuntu 21.10       | 29        | 0.93%   |
| Pop!_OS 22.04      | 29        | 0.93%   |
| Xubuntu 18.04      | 28        | 0.9%    |
| Ubuntu 22.10       | 27        | 0.87%   |
| Linux Mint 20.2    | 27        | 0.87%   |
| Zorin 15           | 26        | 0.83%   |
| Linux Mint 21      | 25        | 0.8%    |
| Fedora 35          | 25        | 0.8%    |
| Fedora 34          | 24        | 0.77%   |
| Fedora 33          | 24        | 0.77%   |
| ROSA R10           | 22        | 0.71%   |
| Ubuntu 18.10       | 21        | 0.67%   |
| Pop!_OS 20.04      | 21        | 0.67%   |
| Pop!_OS 20.10      | 19        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1009      | 34.06%  |
| Linux Mint    | 249       | 8.41%   |
| Debian        | 208       | 7.02%   |
| OpenMandriva  | 206       | 6.95%   |
| Fedora        | 156       | 5.27%   |
| Manjaro       | 101       | 3.41%   |
| Endless       | 100       | 3.38%   |
| Zorin         | 97        | 3.27%   |
| Pop!_OS       | 82        | 2.77%   |
| KDE neon      | 81        | 2.73%   |
| Xubuntu       | 79        | 2.67%   |
| Arch          | 77        | 2.6%    |
| Kubuntu       | 70        | 2.36%   |
| ROSA          | 56        | 1.89%   |
| Ubuntu MATE   | 33        | 1.11%   |
| Kali          | 30        | 1.01%   |
| Elementary    | 29        | 0.98%   |
| openSUSE      | 27        | 0.91%   |
| SteamOS       | 26        | 0.88%   |
| Ubuntu Unity  | 23        | 0.78%   |
| ArcoLinux     | 21        | 0.71%   |
| Lubuntu       | 17        | 0.57%   |
| Gentoo        | 17        | 0.57%   |
| BlackPanther  | 16        | 0.54%   |
| Parrot        | 14        | 0.47%   |
| LMDE          | 14        | 0.47%   |
| Nobara        | 12        | 0.41%   |
| EndeavourOS   | 12        | 0.41%   |
| Ubuntu Budgie | 8         | 0.27%   |
| MX            | 7         | 0.24%   |
| Clear Linux   | 7         | 0.24%   |
| Garuda Linux  | 5         | 0.17%   |
| Deepin        | 5         | 0.17%   |
| CentOS        | 5         | 0.17%   |
| RHEL          | 4         | 0.14%   |
| Ubuntu Studio | 3         | 0.1%    |
| Solus         | 3         | 0.1%    |
| Reborn OS     | 3         | 0.1%    |
| Q4OS          | 3         | 0.1%    |
| Peppermint    | 3         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 82        | 2.41%   |
| 5.16.7-desktop-1omv4003  | 60        | 1.77%   |
| 5.4.0-42-generic         | 48        | 1.41%   |
| 5.15.0-56-generic        | 36        | 1.06%   |
| 6.1.1-desktop-1omv2290   | 34        | 1%      |
| 5.10.0-8-amd64           | 34        | 1%      |
| 5.4.0-58-generic         | 33        | 0.97%   |
| 5.15.0-52-generic        | 32        | 0.94%   |
| 5.3.0-28-generic         | 31        | 0.91%   |
| 5.4.0-54-generic         | 27        | 0.79%   |
| 5.4.0-52-generic         | 26        | 0.77%   |
| 5.4.0-26-generic         | 26        | 0.77%   |
| 5.10.0-18-amd64          | 26        | 0.77%   |
| 5.15.0-58-generic        | 23        | 0.68%   |
| 5.15.0-53-generic        | 22        | 0.65%   |
| 5.11.0-27-generic        | 22        | 0.65%   |
| 5.0.0-37-generic         | 22        | 0.65%   |
| 5.3.0-46-generic         | 21        | 0.62%   |
| 5.3.0-40-generic         | 21        | 0.62%   |
| 5.15.0-48-generic        | 21        | 0.62%   |
| 5.4.0-65-generic         | 20        | 0.59%   |
| 5.4.0-48-generic         | 20        | 0.59%   |
| 6.2.6-desktop-1omv2390   | 19        | 0.56%   |
| 5.19.0-35-generic        | 19        | 0.56%   |
| 5.11.0-43-generic        | 19        | 0.56%   |
| 5.11.0-41-generic        | 19        | 0.56%   |
| 5.4.0-72-generic         | 18        | 0.53%   |
| 5.4.0-40-generic         | 18        | 0.53%   |
| 5.0.0-32-generic         | 18        | 0.53%   |
| 5.8.0-44-generic         | 17        | 0.5%    |
| 5.4.0-19-generic         | 16        | 0.47%   |
| 5.3.0-45-generic         | 16        | 0.47%   |
| 5.8.0-14-generic         | 15        | 0.44%   |
| 5.4.0-53-generic         | 15        | 0.44%   |
| 5.4.0-29-generic         | 15        | 0.44%   |
| 5.15.0-47-generic        | 15        | 0.44%   |
| 5.13.0-valve36-1-neptune | 15        | 0.44%   |
| 5.13.0-28-generic        | 15        | 0.44%   |
| 5.8.0-43-generic         | 14        | 0.41%   |
| 5.4.0-91-generic         | 14        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 542       | 16.87%  |
| 5.15.0  | 290       | 9.03%   |
| 4.15.0  | 205       | 6.38%   |
| 5.11.0  | 168       | 5.23%   |
| 5.10.0  | 156       | 4.86%   |
| 5.3.0   | 153       | 4.76%   |
| 5.8.0   | 150       | 4.67%   |
| 5.13.0  | 140       | 4.36%   |
| 5.0.0   | 109       | 3.39%   |
| 5.19.0  | 104       | 3.24%   |
| 5.10.14 | 83        | 2.58%   |
| 4.18.0  | 71        | 2.21%   |
| 5.16.7  | 64        | 1.99%   |
| 4.19.0  | 41        | 1.28%   |
| 6.1.1   | 40        | 1.25%   |
| 6.2.6   | 28        | 0.87%   |
| 6.1.0   | 26        | 0.81%   |
| 6.2.0   | 16        | 0.5%    |
| 6.0.0   | 16        | 0.5%    |
| 5.14.0  | 16        | 0.5%    |
| 4.9.60  | 15        | 0.47%   |
| 6.0.12  | 13        | 0.4%    |
| 5.18.0  | 13        | 0.4%    |
| 4.4.0   | 13        | 0.4%    |
| 4.18.16 | 13        | 0.4%    |
| 6.1.11  | 11        | 0.34%   |
| 5.9.16  | 10        | 0.31%   |
| 5.17.5  | 9         | 0.28%   |
| 5.16.0  | 8         | 0.25%   |
| 6.1.12  | 7         | 0.22%   |
| 6.0.10  | 7         | 0.22%   |
| 5.3.18  | 7         | 0.22%   |
| 5.17.1  | 7         | 0.22%   |
| 5.13.12 | 7         | 0.22%   |
| 5.11.12 | 7         | 0.22%   |
| 6.3.1   | 6         | 0.19%   |
| 6.2.12  | 6         | 0.19%   |
| 6.0.6   | 6         | 0.19%   |
| 5.9.0   | 6         | 0.19%   |
| 5.16.11 | 6         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 575       | 18.16%  |
| 5.15    | 349       | 11.02%  |
| 5.10    | 277       | 8.75%   |
| 4.15    | 205       | 6.47%   |
| 5.11    | 196       | 6.19%   |
| 5.8     | 176       | 5.56%   |
| 5.3     | 168       | 5.3%    |
| 5.13    | 160       | 5.05%   |
| 5.19    | 137       | 4.33%   |
| 6.1     | 115       | 3.63%   |
| 5.0     | 111       | 3.5%    |
| 5.16    | 101       | 3.19%   |
| 4.18    | 84        | 2.65%   |
| 6.2     | 79        | 2.49%   |
| 6.0     | 59        | 1.86%   |
| 4.19    | 49        | 1.55%   |
| 5.14    | 44        | 1.39%   |
| 4.9     | 39        | 1.23%   |
| 5.18    | 37        | 1.17%   |
| 5.17    | 30        | 0.95%   |
| 5.9     | 29        | 0.92%   |
| 5.6     | 25        | 0.79%   |
| 5.7     | 24        | 0.76%   |
| 5.12    | 23        | 0.73%   |
| 6.3     | 18        | 0.57%   |
| 5.5     | 14        | 0.44%   |
| 4.4     | 14        | 0.44%   |
| 4.16    | 5         | 0.16%   |
| 5.2     | 4         | 0.13%   |
| 4.1     | 4         | 0.13%   |
| 3.10    | 4         | 0.13%   |
| 5.1     | 3         | 0.09%   |
| 4.20    | 3         | 0.09%   |
| 4.13    | 3         | 0.09%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 3.16    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2744      | 95.71%  |
| i686   | 123       | 4.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1319      | 43.95%  |
| KDE5             | 519       | 17.29%  |
| Unknown          | 334       | 11.13%  |
| XFCE             | 240       | 8%      |
| X-Cinnamon       | 191       | 6.36%   |
| MATE             | 86        | 2.87%   |
| KDE              | 76        | 2.53%   |
| Cinnamon         | 33        | 1.1%    |
| Pantheon         | 28        | 0.93%   |
| LXQt             | 25        | 0.83%   |
| Unity            | 22        | 0.73%   |
| KDE4             | 22        | 0.73%   |
| i3               | 20        | 0.67%   |
| LXDE             | 15        | 0.5%    |
| Budgie           | 14        | 0.47%   |
| GNOME Flashback  | 12        | 0.4%    |
| Deepin           | 9         | 0.3%    |
| openbox          | 6         | 0.2%    |
| GNOME Classic    | 5         | 0.17%   |
| bspwm            | 5         | 0.17%   |
| Dwm              | 4         | 0.13%   |
| LeftWM           | 2         | 0.07%   |
| xmonad           | 1         | 0.03%   |
| trinity          | 1         | 0.03%   |
| sway             | 1         | 0.03%   |
| river            | 1         | 0.03%   |
| qtile            | 1         | 0.03%   |
| Lubuntu          | 1         | 0.03%   |
| lightdm-xsession | 1         | 0.03%   |
| icewm            | 1         | 0.03%   |
| i3-with-shmlog   | 1         | 0.03%   |
| Hyprland         | 1         | 0.03%   |
| enlightenment    | 1         | 0.03%   |
| Cutefish         | 1         | 0.03%   |
| BunsenLabs       | 1         | 0.03%   |
| awesome          | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2285      | 77.43%  |
| Wayland | 455       | 15.42%  |
| Unknown | 191       | 6.47%   |
| Tty     | 20        | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1488      | 50.05%  |
| SDDM    | 432       | 14.53%  |
| GDM     | 371       | 12.48%  |
| GDM3    | 298       | 10.02%  |
| LightDM | 255       | 8.58%   |
| TDM     | 90        | 3.03%   |
| KDM     | 24        | 0.81%   |
| XDM     | 7         | 0.24%   |
| SLiM    | 3         | 0.1%    |
| Ly      | 3         | 0.1%    |
| LY-DM   | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| es_ES          | 1697      | 57.58%  |
| en_US          | 556       | 18.87%  |
| Unknown        | 342       | 11.61%  |
| ca_ES          | 112       | 3.8%    |
| en_GB          | 72        | 2.44%   |
| C              | 28        | 0.95%   |
| de_DE          | 20        | 0.68%   |
| gl_ES          | 12        | 0.41%   |
| eu_ES          | 12        | 0.41%   |
| ru_RU          | 10        | 0.34%   |
| fr_FR          | 10        | 0.34%   |
| it_IT          | 9         | 0.31%   |
| an_ES          | 9         | 0.31%   |
| es_MX          | 6         | 0.2%    |
| es_AR          | 6         | 0.2%    |
| en_AG          | 5         | 0.17%   |
| pt_BR          | 4         | 0.14%   |
| ca_AD          | 4         | 0.14%   |
| pl_PL          | 3         | 0.1%    |
| fr_BE          | 3         | 0.1%    |
| POSIX          | 2         | 0.07%   |
| nl_NL          | 2         | 0.07%   |
| es_US          | 2         | 0.07%   |
| es_BO          | 2         | 0.07%   |
| en_IE          | 2         | 0.07%   |
| de_CH          | 2         | 0.07%   |
| de_AT          | 2         | 0.07%   |
| sp_SP          | 1         | 0.03%   |
| ro_RO          | 1         | 0.03%   |
| nb_NO          | 1         | 0.03%   |
| fr_CH          | 1         | 0.03%   |
| et_EE          | 1         | 0.03%   |
| es_VE          | 1         | 0.03%   |
| es_PE          | 1         | 0.03%   |
| en_NZ          | 1         | 0.03%   |
| en_HK          | 1         | 0.03%   |
| en_CA          | 1         | 0.03%   |
| en_AU          | 1         | 0.03%   |
| ca_ES@valencia | 1         | 0.03%   |
| C.UTF8         | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1573      | 53.78%  |
| BIOS | 1352      | 46.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2289      | 77.83%  |
| Overlay | 218       | 7.41%   |
| Btrfs   | 215       | 7.31%   |
| Unknown | 111       | 3.77%   |
| Tmpfs   | 36        | 1.22%   |
| Xfs     | 34        | 1.16%   |
| Zfs     | 18        | 0.61%   |
| Ext2    | 10        | 0.34%   |
| Ext3    | 4         | 0.14%   |
| Aufs    | 3         | 0.1%    |
| Jfs     | 2         | 0.07%   |
| F2fs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1575      | 53.68%  |
| GPT     | 1056      | 35.99%  |
| MBR     | 303       | 10.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2585      | 88.56%  |
| Yes       | 334       | 11.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2021      | 69.33%  |
| Yes       | 894       | 30.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 533       | 18.6%   |
| Lenovo              | 490       | 17.1%   |
| ASUSTek Computer    | 425       | 14.83%  |
| Acer                | 287       | 10.01%  |
| Dell                | 230       | 8.03%   |
| MSI                 | 187       | 6.52%   |
| Toshiba             | 112       | 3.91%   |
| Apple               | 71        | 2.48%   |
| HUAWEI              | 49        | 1.71%   |
| Sony                | 42        | 1.47%   |
| Packard Bell        | 35        | 1.22%   |
| Chuwi               | 34        | 1.19%   |
| Notebook            | 32        | 1.12%   |
| Samsung Electronics | 31        | 1.08%   |
| Unknown             | 31        | 1.08%   |
| Valve               | 26        | 0.91%   |
| SLIMBOOK            | 26        | 0.91%   |
| LG Electronics      | 20        | 0.7%    |
| Medion              | 14        | 0.49%   |
| Fujitsu             | 13        | 0.45%   |
| Timi                | 12        | 0.42%   |
| Fujitsu Siemens     | 12        | 0.42%   |
| Gigabyte Technology | 11        | 0.38%   |
| eMachines           | 11        | 0.38%   |
| Teclast             | 8         | 0.28%   |
| Intel               | 8         | 0.28%   |
| Dynabook            | 8         | 0.28%   |
| Clevo               | 8         | 0.28%   |
| Google              | 5         | 0.17%   |
| Razer               | 4         | 0.14%   |
| PC Specialist       | 4         | 0.14%   |
| HONOR               | 4         | 0.14%   |
| Thomson             | 3         | 0.1%    |
| Qilive              | 3         | 0.1%    |
| IBM                 | 3         | 0.1%    |
| Compal              | 3         | 0.1%    |
| Beelink             | 3         | 0.1%    |
| Alienware           | 3         | 0.1%    |
| VANT                | 2         | 0.07%   |
| TUXEDO              | 2         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 50        | 1.74%   |
| Valve Jupiter                              | 26        | 0.91%   |
| HP Pavilion g6                             | 22        | 0.77%   |
| HP Pavilion dv6                            | 20        | 0.7%    |
| HP Notebook                                | 20        | 0.7%    |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.63%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 15        | 0.52%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.52%   |
| HP G62                                     | 12        | 0.42%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 10        | 0.35%   |
| HUAWEI BOHK-WAX9X                          | 10        | 0.35%   |
| HP Pavilion 15                             | 10        | 0.35%   |
| HP Laptop 15-da0xxx                        | 10        | 0.35%   |
| Dell XPS 13 7390                           | 10        | 0.35%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.31%   |
| Chuwi GemiBook Pro                         | 9         | 0.31%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.28%   |
| HP Laptop 15-bw0xx                         | 8         | 0.28%   |
| ASUS X555LAB                               | 8         | 0.28%   |
| ASUS X550VX                                | 8         | 0.28%   |
| ASUS X540NA                                | 8         | 0.28%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.28%   |
| Acer TravelMate 5720                       | 8         | 0.28%   |
| Acer Aspire 5750G                          | 8         | 0.28%   |
| MSI Modern 14 A10M                         | 7         | 0.24%   |
| Lenovo Y520-15IKBN 80WK                    | 7         | 0.24%   |
| Lenovo Legion 5 15ACH6H 82JU               | 7         | 0.24%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.24%   |
| Lenovo G50-70 20351                        | 7         | 0.24%   |
| HUAWEI NBLK-WAX9X                          | 7         | 0.24%   |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.24%   |
| HP Pavilion Notebook                       | 7         | 0.24%   |
| HP Pavilion dv7                            | 7         | 0.24%   |
| HP OMEN by Laptop                          | 7         | 0.24%   |
| HP Laptop 15s-fq1xxx                       | 7         | 0.24%   |
| HP Laptop 15-bs0xx                         | 7         | 0.24%   |
| Dell XPS 13 9370                           | 7         | 0.24%   |
| Acer Aspire 5738                           | 7         | 0.24%   |
| MSI Prestige 15 A10SC                      | 6         | 0.21%   |
| MSI GF63 Thin 9SC                          | 6         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 205       | 7.15%   |
| Lenovo ThinkPad       | 191       | 6.66%   |
| Lenovo IdeaPad        | 139       | 4.85%   |
| HP Pavilion           | 129       | 4.5%    |
| Dell Latitude         | 94        | 3.28%   |
| Toshiba Satellite     | 87        | 3.04%   |
| ASUS VivoBook         | 78        | 2.72%   |
| HP Laptop             | 75        | 2.62%   |
| HP EliteBook          | 60        | 2.09%   |
| Dell XPS              | 54        | 1.88%   |
| Unknown               | 50        | 1.74%   |
| HP Compaq             | 40        | 1.4%    |
| HP ProBook            | 39        | 1.36%   |
| Dell Inspiron         | 39        | 1.36%   |
| ASUS ZenBook          | 36        | 1.26%   |
| Packard Bell EasyNote | 32        | 1.12%   |
| HP 250                | 32        | 1.12%   |
| ASUS ROG              | 31        | 1.08%   |
| MSI Prestige          | 29        | 1.01%   |
| MSI Modern            | 27        | 0.94%   |
| Valve Jupiter         | 26        | 0.91%   |
| Lenovo Legion         | 26        | 0.91%   |
| HP OMEN               | 24        | 0.84%   |
| Acer TravelMate       | 24        | 0.84%   |
| HP Notebook           | 20        | 0.7%    |
| Acer Extensa          | 20        | 0.7%    |
| Lenovo ThinkBook      | 17        | 0.59%   |
| ASUS ASUS             | 17        | 0.59%   |
| ASUS TUF              | 16        | 0.56%   |
| HP ENVY               | 15        | 0.52%   |
| Chuwi GemiBook        | 14        | 0.49%   |
| Lenovo Yoga           | 13        | 0.45%   |
| HP G62                | 12        | 0.42%   |
| Fujitsu LIFEBOOK      | 12        | 0.42%   |
| Dell Vostro           | 12        | 0.42%   |
| HP 255                | 11        | 0.38%   |
| Apple MacBookPro11    | 11        | 0.38%   |
| Toshiba PORTEGE       | 10        | 0.35%   |
| HUAWEI BOHK-WAX9X     | 10        | 0.35%   |
| HP Victus             | 10        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 289       | 10.08%  |
| 2019    | 288       | 10.05%  |
| 2020    | 263       | 9.18%   |
| 2021    | 246       | 8.58%   |
| 2014    | 188       | 6.56%   |
| 2015    | 182       | 6.35%   |
| 2011    | 175       | 6.11%   |
| 2017    | 170       | 5.93%   |
| 2010    | 148       | 5.16%   |
| 2013    | 143       | 4.99%   |
| 2012    | 138       | 4.82%   |
| 2008    | 138       | 4.82%   |
| 2009    | 122       | 4.26%   |
| 2016    | 120       | 4.19%   |
| 2022    | 109       | 3.8%    |
| 2007    | 88        | 3.07%   |
| 2006    | 31        | 1.08%   |
| 2005    | 10        | 0.35%   |
| 2023    | 5         | 0.17%   |
| 2004    | 5         | 0.17%   |
| 2003    | 3         | 0.1%    |
| Unknown | 3         | 0.1%    |
| 2002    | 1         | 0.03%   |
| 2001    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2866      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2629      | 91.16%  |
| Enabled  | 255       | 8.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2858      | 99.72%  |
| Yes  | 8         | 0.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 753       | 25.97%  |
| 3.01-4.0    | 636       | 21.93%  |
| 8.01-16.0   | 537       | 18.52%  |
| 16.01-24.0  | 515       | 17.76%  |
| 32.01-64.0  | 182       | 6.28%   |
| 1.01-2.0    | 142       | 4.9%    |
| 2.01-3.0    | 54        | 1.86%   |
| 0.51-1.0    | 46        | 1.59%   |
| 24.01-32.0  | 17        | 0.59%   |
| 64.01-256.0 | 16        | 0.55%   |
| 0.01-0.5    | 2         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1185      | 37.42%  |
| 2.01-3.0   | 826       | 26.08%  |
| 4.01-8.0   | 403       | 12.72%  |
| 3.01-4.0   | 361       | 11.4%   |
| 0.51-1.0   | 250       | 7.89%   |
| 8.01-16.0  | 106       | 3.35%   |
| 0.01-0.5   | 26        | 0.82%   |
| 16.01-24.0 | 7         | 0.22%   |
| 24.01-32.0 | 3         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2200      | 75.45%  |
| 2      | 614       | 21.06%  |
| 3      | 69        | 2.37%   |
| 0      | 25        | 0.86%   |
| 4      | 5         | 0.17%   |
| 5      | 3         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1869      | 64.9%   |
| Yes       | 1011      | 35.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2295      | 79.66%  |
| No        | 586       | 20.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2808      | 97.98%  |
| No        | 58        | 2.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2134      | 73.84%  |
| No        | 756       | 26.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 2866      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 495       | 15.85%  |
| Barcelona                  | 344       | 11.02%  |
| Seville                    | 112       | 3.59%   |
| Valencia                   | 98        | 3.14%   |
| Zaragoza                   | 50        | 1.6%    |
| Granada                    | 48        | 1.54%   |
| Málaga                    | 44        | 1.41%   |
| Alcobendas                 | 40        | 1.28%   |
| Palma                      | 35        | 1.12%   |
| Vigo                       | 31        | 0.99%   |
| Sabadell                   | 30        | 0.96%   |
| Valladolid                 | 29        | 0.93%   |
| Bilbao                     | 26        | 0.83%   |
| Córdoba                   | 24        | 0.77%   |
| Pamplona                   | 23        | 0.74%   |
| Las Palmas de Gran Canaria | 23        | 0.74%   |
| Santiago de Compostela     | 22        | 0.7%    |
| Alicante                   | 22        | 0.7%    |
| Donostia / San Sebastian   | 21        | 0.67%   |
| Alcalá de Henares         | 21        | 0.67%   |
| A Coruña                  | 19        | 0.61%   |
| Oviedo                     | 18        | 0.58%   |
| Murcia                     | 18        | 0.58%   |
| León                      | 17        | 0.54%   |
| Mostoles                   | 16        | 0.51%   |
| Gijón                     | 16        | 0.51%   |
| Burgos                     | 15        | 0.48%   |
| Salamanca                  | 14        | 0.45%   |
| Reus                       | 14        | 0.45%   |
| Barakaldo                  | 14        | 0.45%   |
| Vitoria-Gasteiz            | 13        | 0.42%   |
| Ourense                    | 12        | 0.38%   |
| Getxo                      | 12        | 0.38%   |
| Almería                   | 12        | 0.38%   |
| Tarragona                  | 11        | 0.35%   |
| Santander                  | 11        | 0.35%   |
| Dos Hermanas               | 11        | 0.35%   |
| Cartagena                  | 11        | 0.35%   |
| Badalona                   | 11        | 0.35%   |
| Alcorcón                  | 11        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 492       | 610    | 14.13%  |
| WDC                         | 377       | 467    | 10.83%  |
| Seagate                     | 360       | 428    | 10.34%  |
| Kingston                    | 355       | 445    | 10.2%   |
| Toshiba                     | 290       | 360    | 8.33%   |
| SanDisk                     | 227       | 295    | 6.52%   |
| Unknown                     | 172       | 225    | 4.94%   |
| SK hynix                    | 153       | 185    | 4.39%   |
| Hitachi                     | 125       | 148    | 3.59%   |
| Micron Technology           | 112       | 142    | 3.22%   |
| Intel                       | 112       | 152    | 3.22%   |
| HGST                        | 105       | 128    | 3.02%   |
| Crucial                     | 102       | 127    | 2.93%   |
| China                       | 35        | 51     | 1.01%   |
| KIOXIA                      | 34        | 40     | 0.98%   |
| Fujitsu                     | 33        | 37     | 0.95%   |
| Phison                      | 30        | 32     | 0.86%   |
| Apple                       | 28        | 35     | 0.8%    |
| Phison Electronics          | 21        | 24     | 0.6%    |
| Kingston Technology Company | 20        | 26     | 0.57%   |
| Netac                       | 17        | 28     | 0.49%   |
| LITEON                      | 16        | 17     | 0.46%   |
| KingSpec                    | 15        | 20     | 0.43%   |
| Micron/Crucial Technology   | 14        | 16     | 0.4%    |
| A-DATA Technology           | 13        | 15     | 0.37%   |
| JMicron Technology          | 11        | 11     | 0.32%   |
| Transcend                   | 9         | 15     | 0.26%   |
| PNY                         | 8         | 14     | 0.23%   |
| OCZ                         | 8         | 9      | 0.23%   |
| FORESEE                     | 8         | 12     | 0.23%   |
| Unknown                     | 8         | 8      | 0.23%   |
| USB30                       | 7         | 8      | 0.2%    |
| Teclast                     | 7         | 7      | 0.2%    |
| Silicon Motion              | 7         | 7      | 0.2%    |
| Patriot                     | 6         | 7      | 0.17%   |
| LITEONIT                    | 6         | 7      | 0.17%   |
| Emtec                       | 6         | 6      | 0.17%   |
| TCSUNBOW                    | 5         | 5      | 0.14%   |
| O2 Micro                    | 5         | 5      | 0.14%   |
| KingDian                    | 5         | 5      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 126       | 3.51%   |
| Kingston SA400S37480G 480GB SSD                     | 49        | 1.36%   |
| Seagate ST500LT012-1DG142 500GB                     | 43        | 1.2%    |
| Unknown MMC Card  32GB                              | 37        | 1.03%   |
| HGST HTS721010A9E630 1TB                            | 35        | 0.97%   |
| SK hynix NVMe SSD Drive 512GB                       | 34        | 0.95%   |
| Toshiba MQ01ABD100 1TB                              | 33        | 0.92%   |
| Seagate ST1000LM035-1RK172 1TB                      | 33        | 0.92%   |
| Seagate ST9500325AS 500GB                           | 32        | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 32        | 0.89%   |
| Unknown MMC Card  64GB                              | 31        | 0.86%   |
| Toshiba MQ01ABF050 500GB                            | 31        | 0.86%   |
| Samsung NVMe SSD Drive 512GB                        | 31        | 0.86%   |
| Toshiba MQ04ABF100 1TB                              | 28        | 0.78%   |
| SanDisk NVMe SSD Drive 512GB                        | 26        | 0.72%   |
| Toshiba MQ01ABD050 500GB                            | 22        | 0.61%   |
| Samsung SSD 850 EVO 250GB                           | 22        | 0.61%   |
| Samsung NVMe SSD Drive 256GB                        | 22        | 0.61%   |
| Kingston SUV400S37240G 240GB SSD                    | 21        | 0.58%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.58%   |
| Intel NVMe SSD Drive 512GB                          | 21        | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 20        | 0.56%   |
| HGST HTS545050A7E680 500GB                          | 20        | 0.56%   |
| Unknown MMC Card  128GB                             | 19        | 0.53%   |
| SanDisk SSD PLUS 480GB                              | 19        | 0.53%   |
| Samsung SSD 860 EVO 500GB                           | 19        | 0.53%   |
| Kingston RBUSC180DS37256GJ 256GB SSD                | 19        | 0.53%   |
| HGST HTS541010A9E680 1TB                            | 18        | 0.5%    |
| SanDisk NVMe SSD Drive 256GB                        | 17        | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 16        | 0.45%   |
| Crucial CT500MX500SSD1 500GB                        | 16        | 0.45%   |
| Seagate ST1000LM049-2GH172 1TB                      | 15        | 0.42%   |
| Seagate Expansion 1TB                               | 15        | 0.42%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 15        | 0.42%   |
| Samsung SSD 850 EVO 500GB                           | 15        | 0.42%   |
| Kingston SA400S37960G 960GB SSD                     | 14        | 0.39%   |
| Micron NVMe SSD Drive 512GB                         | 13        | 0.36%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 11        | 0.31%   |
| SK hynix NVMe SSD Drive 256GB                       | 11        | 0.31%   |
| Seagate ST9500420AS 500GB                           | 11        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 356       | 424    | 32.22%  |
| WDC                 | 241       | 289    | 21.81%  |
| Toshiba             | 193       | 233    | 17.47%  |
| Hitachi             | 125       | 148    | 11.31%  |
| HGST                | 105       | 128    | 9.5%    |
| Fujitsu             | 33        | 37     | 2.99%   |
| Samsung Electronics | 28        | 29     | 2.53%   |
| Unknown             | 8         | 11     | 0.72%   |
| Apple               | 4         | 4      | 0.36%   |
| USB3.0              | 3         | 3      | 0.27%   |
| SSK                 | 2         | 2      | 0.18%   |
| USB                 | 1         | 1      | 0.09%   |
| PHD 3.0             | 1         | 1      | 0.09%   |
| OEM                 | 1         | 1      | 0.09%   |
| Maxone              | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| Inateck             | 1         | 1      | 0.09%   |
| IBM                 | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 305       | 385    | 27.31%  |
| Samsung Electronics | 186       | 232    | 16.65%  |
| SanDisk             | 116       | 142    | 10.38%  |
| Crucial             | 93        | 116    | 8.33%   |
| Toshiba             | 45        | 55     | 4.03%   |
| WDC                 | 44        | 59     | 3.94%   |
| SK hynix            | 37        | 40     | 3.31%   |
| China               | 35        | 51     | 3.13%   |
| Micron Technology   | 32        | 42     | 2.86%   |
| Intel               | 22        | 35     | 1.97%   |
| Netac               | 17        | 28     | 1.52%   |
| Apple               | 16        | 18     | 1.43%   |
| LITEON              | 15        | 15     | 1.34%   |
| KingSpec            | 15        | 20     | 1.34%   |
| A-DATA Technology   | 11        | 13     | 0.98%   |
| Transcend           | 8         | 14     | 0.72%   |
| OCZ                 | 8         | 9      | 0.72%   |
| FORESEE             | 8         | 12     | 0.72%   |
| USB30               | 7         | 8      | 0.63%   |
| Teclast             | 7         | 7      | 0.63%   |
| PNY                 | 6         | 12     | 0.54%   |
| LITEONIT            | 6         | 7      | 0.54%   |
| Patriot             | 5         | 6      | 0.45%   |
| Emtec               | 5         | 5      | 0.45%   |
| KingDian            | 4         | 4      | 0.36%   |
| Intenso             | 4         | 6      | 0.36%   |
| Corsair             | 4         | 5      | 0.36%   |
| Unknown             | 3         | 3      | 0.27%   |
| TCSUNBOW            | 3         | 3      | 0.27%   |
| Dogfish             | 3         | 3      | 0.27%   |
| BAITITON            | 3         | 4      | 0.27%   |
| ASMT                | 3         | 3      | 0.27%   |
| Unknown             | 3         | 3      | 0.27%   |
| ShanDianZhe         | 2         | 2      | 0.18%   |
| Plextor             | 2         | 3      | 0.18%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.18%   |
| Yeyian              | 1         | 1      | 0.09%   |
| W800S               | 1         | 2      | 0.09%   |
| Verbatim            | 1         | 1      | 0.09%   |
| Vaseky              | 1         | 1      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1078      | 1315   | 32.38%  |
| SSD     | 1045      | 1417   | 31.39%  |
| NVMe    | 1000      | 1328   | 30.04%  |
| MMC     | 169       | 220    | 5.08%   |
| Unknown | 37        | 42     | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1881      | 2649   | 59.51%  |
| NVMe | 994       | 1316   | 31.45%  |
| MMC  | 169       | 220    | 5.35%   |
| SAS  | 117       | 137    | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1519      | 2050   | 73.31%  |
| 0.51-1.0   | 508       | 625    | 24.52%  |
| 1.01-2.0   | 35        | 45     | 1.69%   |
| 4.01-10.0  | 5         | 6      | 0.24%   |
| 3.01-4.0   | 4         | 5      | 0.19%   |
| 2.01-3.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 930       | 30.93%  |
| 251-500        | 846       | 28.13%  |
| 501-1000       | 375       | 12.47%  |
| 1-20           | 222       | 7.38%   |
| 51-100         | 220       | 7.32%   |
| 21-50          | 140       | 4.66%   |
| 1001-2000      | 138       | 4.59%   |
| Unknown        | 63        | 2.1%    |
| 2001-3000      | 38        | 1.26%   |
| More than 3000 | 35        | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1287      | 40.92%  |
| 21-50          | 590       | 18.76%  |
| 101-250        | 438       | 13.93%  |
| 51-100         | 361       | 11.48%  |
| 251-500        | 236       | 7.5%    |
| 501-1000       | 118       | 3.75%   |
| Unknown        | 63        | 2%      |
| 1001-2000      | 31        | 0.99%   |
| 2001-3000      | 10        | 0.32%   |
| More than 3000 | 9         | 0.29%   |
| 0              | 2         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 7         | 8      | 4%      |
| Seagate ST500LT012-1DG142 500GB    | 5         | 5      | 2.86%   |
| SanDisk SSD PLUS 480GB             | 5         | 6      | 2.86%   |
| HGST HTS545050A7E680 500GB         | 5         | 7      | 2.86%   |
| Seagate ST9500420AS 500GB          | 4         | 4      | 2.29%   |
| Seagate ST9250827AS 250GB          | 4         | 4      | 2.29%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 4      | 2.29%   |
| Hitachi HTS545050A7E380 500GB      | 4         | 4      | 2.29%   |
| HGST HTS721010A9E630 1TB           | 4         | 4      | 2.29%   |
| China G521N256GB SSD               | 4         | 5      | 2.29%   |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 3      | 1.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 1.71%   |
| Kingston SA400S37480G 480GB SSD    | 3         | 3      | 1.71%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 1.71%   |
| WDC WD5000BPVT-60HXZT3 500GB       | 2         | 2      | 1.14%   |
| Toshiba Q300. 240GB SSD            | 2         | 2      | 1.14%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 1.14%   |
| Toshiba MK5076GSX 500GB            | 2         | 2      | 1.14%   |
| Seagate ST9500420ASG 500GB         | 2         | 2      | 1.14%   |
| Seagate ST320LT012-9WS14C 320GB    | 2         | 2      | 1.14%   |
| Kingston SV300S37A120G 120GB SSD   | 2         | 2      | 1.14%   |
| Intel SSDSC2BF180A5H SED 180GB     | 2         | 2      | 1.14%   |
| Hitachi HTS723232A7A364 320GB      | 2         | 2      | 1.14%   |
| Hitachi HTS545050B9A300 500GB      | 2         | 2      | 1.14%   |
| Hitachi HTS543232L9A300 320GB      | 2         | 3      | 1.14%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 2      | 1.14%   |
| HGST HTS545050A7E380 500GB         | 2         | 2      | 1.14%   |
| Fujitsu MHZ2250BH G2 250GB         | 2         | 2      | 1.14%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 1      | 0.57%   |
| WDC WD7500BPVT-60HXZT1 752GB       | 1         | 1      | 0.57%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 1      | 0.57%   |
| WDC WD5000BEVT-22ZAT0 500GB        | 1         | 1      | 0.57%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 1      | 0.57%   |
| WDC WD3200BEVT-00A0RT0 320GB       | 1         | 1      | 0.57%   |
| WDC WD3200BEKT-60V5T1 320GB        | 1         | 1      | 0.57%   |
| WDC WD3200BEKT-60F3T1 320GB        | 1         | 2      | 0.57%   |
| WDC WD2500BEVS-60UST0 250GB        | 1         | 1      | 0.57%   |
| WDC WD2500BEVS-22UST0 250GB        | 1         | 1      | 0.57%   |
| WDC WD1600BEVT-60ZCT0 160GB        | 1         | 1      | 0.57%   |
| WDC WD1600BEVS-60RST0 160GB        | 1         | 1      | 0.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 50     | 27.43%  |
| Hitachi             | 23        | 25     | 13.14%  |
| Toshiba             | 21        | 23     | 12%     |
| WDC                 | 17        | 18     | 9.71%   |
| HGST                | 16        | 19     | 9.14%   |
| Samsung Electronics | 10        | 10     | 5.71%   |
| Kingston            | 7         | 8      | 4%      |
| SanDisk             | 6         | 7      | 3.43%   |
| Intel               | 6         | 6      | 3.43%   |
| Fujitsu             | 5         | 5      | 2.86%   |
| China               | 5         | 6      | 2.86%   |
| SK hynix            | 3         | 3      | 1.71%   |
| Micron Technology   | 3         | 4      | 1.71%   |
| Crucial             | 3         | 5      | 1.71%   |
| OCZ                 | 1         | 1      | 0.57%   |
| IBM                 | 1         | 1      | 0.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 50     | 36.92%  |
| Hitachi             | 23        | 25     | 17.69%  |
| WDC                 | 16        | 17     | 12.31%  |
| Toshiba             | 16        | 18     | 12.31%  |
| HGST                | 16        | 19     | 12.31%  |
| Samsung Electronics | 5         | 5      | 3.85%   |
| Fujitsu             | 5         | 5      | 3.85%   |
| IBM                 | 1         | 1      | 0.77%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 128       | 140    | 74.42%  |
| SSD  | 39        | 46     | 22.67%  |
| NVMe | 5         | 5      | 2.91%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1758      | 2704   | 57.91%  |
| Works    | 1106      | 1426   | 36.43%  |
| Malfunc  | 171       | 191    | 5.63%   |
| Failed   | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1974      | 59.35%  |
| AMD                              | 322       | 9.68%   |
| Samsung Electronics              | 309       | 9.29%   |
| SanDisk                          | 196       | 5.89%   |
| SK hynix                         | 110       | 3.31%   |
| Micron Technology                | 80        | 2.41%   |
| Kingston Technology Company      | 68        | 2.04%   |
| Phison Electronics               | 55        | 1.65%   |
| Toshiba America Info Systems     | 53        | 1.59%   |
| KIOXIA                           | 39        | 1.17%   |
| Nvidia                           | 27        | 0.81%   |
| Micron/Crucial Technology        | 20        | 0.6%    |
| Silicon Integrated Systems [SiS] | 14        | 0.42%   |
| Silicon Motion                   | 10        | 0.3%    |
| Apple                            | 7         | 0.21%   |
| VIA Technologies                 | 6         | 0.18%   |
| Union Memory (Shenzhen)          | 6         | 0.18%   |
| O2 Micro                         | 5         | 0.15%   |
| JMicron Technology               | 5         | 0.15%   |
| Solid State Storage Technology   | 4         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.06%   |
| Marvell Technology Group         | 2         | 0.06%   |
| Lite-On Technology               | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| ADATA Technology                 | 2         | 0.06%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Silicon Image                    | 1         | 0.03%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Netac Technology                 | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 274       | 7.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 218       | 6.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 144       | 4%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 143       | 3.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 143       | 3.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 133       | 3.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 128       | 3.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 112       | 3.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 97        | 2.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 90        | 2.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 84        | 2.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 79        | 2.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 76        | 2.11%   |
| Samsung NVMe SSD Controller 980                                                | 72        | 2%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 72        | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 72        | 2%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 70        | 1.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 68        | 1.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 61        | 1.69%   |
| Intel SSD 660P Series                                                          | 54        | 1.5%    |
| Micron NVMe Storage Controller                                                 | 50        | 1.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 46        | 1.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 40        | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 39        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 38        | 1.06%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 37        | 1.03%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 36        | 1%      |
| Intel Tiger Lake-LP SATA Controller                                            | 35        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 34        | 0.94%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 33        | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 30        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 29        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                          | 29        | 0.81%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 29        | 0.81%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 28        | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 28        | 0.78%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 27        | 0.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 0.75%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 26        | 0.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 25        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1991      | 57.34%  |
| NVMe | 1003      | 28.89%  |
| IDE  | 250       | 7.2%    |
| RAID | 228       | 6.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2357      | 82.24%  |
| AMD          | 508       | 17.73%  |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 61        | 2.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 55        | 1.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 49        | 1.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 48        | 1.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 46        | 1.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 43        | 1.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 41        | 1.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 40        | 1.39%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 38        | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 38        | 1.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 37        | 1.29%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 37        | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 32        | 1.12%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 32        | 1.12%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 31        | 1.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 30        | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 1.05%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 27        | 0.94%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 26        | 0.91%   |
| AMD Custom APU 0405                           | 26        | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.87%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 25        | 0.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 24        | 0.84%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 23        | 0.8%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 21        | 0.73%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 21        | 0.73%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 19        | 0.66%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 19        | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 18        | 0.63%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 18        | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 0.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.63%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 18        | 0.63%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 18        | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 17        | 0.59%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 17        | 0.59%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 17        | 0.59%   |
| Intel 12th Gen Core i7-12700H                 | 17        | 0.59%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 17        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 665       | 23.19%  |
| Intel Core i5           | 559       | 19.5%   |
| Other                   | 282       | 9.84%   |
| Intel Celeron           | 214       | 7.46%   |
| Intel Core i3           | 213       | 7.43%   |
| Intel Core 2 Duo        | 172       | 6%      |
| AMD Ryzen 7             | 139       | 4.85%   |
| AMD Ryzen 5             | 106       | 3.7%    |
| Intel Atom              | 102       | 3.56%   |
| Intel Pentium Dual-Core | 41        | 1.43%   |
| Intel Pentium           | 38        | 1.33%   |
| Intel Pentium Dual      | 30        | 1.05%   |
| AMD A4                  | 29        | 1.01%   |
| AMD A6                  | 28        | 0.98%   |
| Intel Core 2            | 25        | 0.87%   |
| Intel Genuine           | 23        | 0.8%    |
| AMD E1                  | 21        | 0.73%   |
| AMD A8                  | 18        | 0.63%   |
| AMD E                   | 14        | 0.49%   |
| AMD Ryzen 9             | 13        | 0.45%   |
| AMD Ryzen 3             | 12        | 0.42%   |
| AMD Ryzen 7 PRO         | 11        | 0.38%   |
| Intel Pentium M         | 9         | 0.31%   |
| Intel Core i9           | 9         | 0.31%   |
| AMD Athlon              | 9         | 0.31%   |
| AMD A10                 | 9         | 0.31%   |
| Intel Celeron M         | 8         | 0.28%   |
| Intel Core m3           | 5         | 0.17%   |
| AMD Turion 64 X2 Mobile | 5         | 0.17%   |
| Intel Pentium 4         | 4         | 0.14%   |
| AMD Turion II Dual-Core | 4         | 0.14%   |
| AMD FX                  | 4         | 0.14%   |
| AMD Athlon II           | 4         | 0.14%   |
| AMD Turion 64 Mobile    | 3         | 0.1%    |
| AMD A12                 | 3         | 0.1%    |
| Intel Xeon              | 2         | 0.07%   |
| Intel Pentium Silver    | 2         | 0.07%   |
| Intel Core m5           | 2         | 0.07%   |
| Intel Core Duo          | 2         | 0.07%   |
| AMD Sempron             | 2         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1409      | 49.11%  |
| 4       | 901       | 31.4%   |
| 6       | 205       | 7.15%   |
| 8       | 180       | 6.27%   |
| 1       | 118       | 4.11%   |
| 14      | 27        | 0.94%   |
| 10      | 13        | 0.45%   |
| 12      | 12        | 0.42%   |
| Unknown | 4         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2865      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2029      | 70.72%  |
| 1       | 836       | 29.14%  |
| Unknown | 4         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2757      | 95.7%   |
| 32-bit         | 56        | 1.94%   |
| Unknown        | 54        | 1.87%   |
| 64-bit         | 14        | 0.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 614       | 20.67%  |
| 0x206a7    | 139       | 4.68%   |
| 0x306a9    | 118       | 3.97%   |
| 0x806c1    | 106       | 3.57%   |
| 0x806ea    | 99        | 3.33%   |
| 0x40651    | 97        | 3.27%   |
| 0x906ea    | 96        | 3.23%   |
| 0x806ec    | 91        | 3.06%   |
| 0x1067a    | 85        | 2.86%   |
| 0x406e3    | 81        | 2.73%   |
| 0x6fd      | 78        | 2.63%   |
| 0x20655    | 77        | 2.59%   |
| 0x806e9    | 76        | 2.56%   |
| 0x306d4    | 69        | 2.32%   |
| 0x306c3    | 61        | 2.05%   |
| 0x30678    | 52        | 1.75%   |
| 0x08108109 | 46        | 1.55%   |
| 0x0a50000c | 43        | 1.45%   |
| 0xa0652    | 42        | 1.41%   |
| 0x10676    | 41        | 1.38%   |
| 0x706e5    | 39        | 1.31%   |
| 0x06006705 | 37        | 1.25%   |
| 0x20652    | 36        | 1.21%   |
| 0x706a1    | 35        | 1.18%   |
| 0x506e3    | 35        | 1.18%   |
| 0x906a3    | 30        | 1.01%   |
| 0x106ca    | 30        | 1.01%   |
| 0x906e9    | 29        | 0.98%   |
| 0x08108102 | 29        | 0.98%   |
| 0x806eb    | 27        | 0.91%   |
| 0x08600106 | 27        | 0.91%   |
| 0x706a8    | 25        | 0.84%   |
| 0x506c9    | 25        | 0.84%   |
| 0x806d1    | 24        | 0.81%   |
| 0x406c4    | 24        | 0.81%   |
| 0x406c3    | 22        | 0.74%   |
| 0x08600104 | 21        | 0.71%   |
| 0x08608103 | 20        | 0.67%   |
| 0x6f6      | 19        | 0.64%   |
| 0x106c2    | 19        | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 520       | 18.14%  |
| Haswell          | 215       | 7.5%    |
| SandyBridge      | 164       | 5.72%   |
| Penryn           | 159       | 5.55%   |
| TigerLake        | 145       | 5.06%   |
| Core             | 145       | 5.06%   |
| Skylake          | 140       | 4.88%   |
| IvyBridge        | 134       | 4.68%   |
| Westmere         | 126       | 4.4%    |
| Silvermont       | 117       | 4.08%   |
| Unknown          | 93        | 3.24%   |
| Broadwell        | 90        | 3.14%   |
| Zen+             | 87        | 3.04%   |
| Zen 2            | 79        | 2.76%   |
| Goldmont plus    | 73        | 2.55%   |
| Zen 3            | 64        | 2.23%   |
| Excavator        | 63        | 2.2%    |
| Bonnell          | 63        | 2.2%    |
| IceLake          | 62        | 2.16%   |
| CometLake        | 62        | 2.16%   |
| Alderlake Hybrid | 36        | 1.26%   |
| Goldmont         | 31        | 1.08%   |
| Puma             | 27        | 0.94%   |
| P6               | 27        | 0.94%   |
| Zen              | 25        | 0.87%   |
| Jaguar           | 23        | 0.8%    |
| Bobcat           | 22        | 0.77%   |
| K8 Hammer        | 15        | 0.52%   |
| K10              | 15        | 0.52%   |
| Tremont          | 10        | 0.35%   |
| Nehalem          | 9         | 0.31%   |
| Piledriver       | 8         | 0.28%   |
| Steamroller      | 5         | 0.17%   |
| NetBurst         | 5         | 0.17%   |
| K10 Llano        | 4         | 0.14%   |
| K8 & K10 hybrid  | 3         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2101      | 57.28%  |
| Nvidia                           | 855       | 23.31%  |
| AMD                              | 697       | 19%     |
| Silicon Integrated Systems [SiS] | 9         | 0.25%   |
| VIA Technologies                 | 6         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 148       | 3.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 139       | 3.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 129       | 3.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 126       | 3.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 120       | 3.16%   |
| Intel UHD Graphics 620                                                                   | 109       | 2.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 97        | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 95        | 2.5%    |
| Intel HD Graphics 620                                                                    | 87        | 2.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 85        | 2.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 84        | 2.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 83        | 2.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 77        | 2.03%   |
| Intel HD Graphics 5500                                                                   | 76        | 2%      |
| AMD Renoir                                                                               | 76        | 2%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 71        | 1.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 66        | 1.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 63        | 1.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 63        | 1.66%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 58        | 1.53%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 52        | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 51        | 1.34%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 50        | 1.32%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 48        | 1.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 1.24%   |
| Intel HD Graphics 530                                                                    | 44        | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 41        | 1.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 38        | 1%      |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 38        | 1%      |
| Intel HD Graphics 630                                                                    | 35        | 0.92%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 33        | 0.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 31        | 0.82%   |
| AMD Lucienne                                                                             | 30        | 0.79%   |
| Intel HD Graphics 500                                                                    | 29        | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 28        | 0.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 28        | 0.74%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 27        | 0.71%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 27        | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1381      | 48.03%  |
| Intel + Nvidia | 618       | 21.5%   |
| 1 x AMD        | 471       | 16.38%  |
| 1 x Nvidia     | 149       | 5.18%   |
| Intel + AMD    | 93        | 3.23%   |
| AMD + Nvidia   | 88        | 3.06%   |
| 2 x AMD        | 44        | 1.53%   |
| 2 x Intel      | 9         | 0.31%   |
| 1 x SiS        | 9         | 0.31%   |
| 1 x VIA        | 6         | 0.21%   |
| 2 x Nvidia     | 4         | 0.14%   |
| Other          | 3         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2413      | 83.21%  |
| Proprietary | 395       | 13.62%  |
| Unknown     | 92        | 3.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1803      | 61.28%  |
| 0.01-0.5   | 374       | 12.71%  |
| 1.01-2.0   | 336       | 11.42%  |
| 3.01-4.0   | 193       | 6.56%   |
| 0.51-1.0   | 160       | 5.44%   |
| 5.01-6.0   | 41        | 1.39%   |
| 7.01-8.0   | 29        | 0.99%   |
| 2.01-3.0   | 3         | 0.1%    |
| 8.01-16.0  | 3         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 550       | 17.14%  |
| Chimei Innolux          | 503       | 15.67%  |
| LG Display              | 437       | 13.62%  |
| BOE                     | 383       | 11.94%  |
| Samsung Electronics     | 304       | 9.47%   |
| Chi Mei Optoelectronics | 91        | 2.84%   |
| Sharp                   | 88        | 2.74%   |
| Goldstar                | 82        | 2.56%   |
| Dell                    | 81        | 2.52%   |
| Apple                   | 70        | 2.18%   |
| PANDA                   | 66        | 2.06%   |
| Hewlett-Packard         | 64        | 1.99%   |
| BenQ                    | 47        | 1.46%   |
| Lenovo                  | 45        | 1.4%    |
| LG Philips              | 44        | 1.37%   |
| Philips                 | 29        | 0.9%    |
| Acer                    | 28        | 0.87%   |
| AOC                     | 24        | 0.75%   |
| Ancor Communications    | 24        | 0.75%   |
| HannStar                | 20        | 0.62%   |
| Sony                    | 19        | 0.59%   |
| InfoVision              | 18        | 0.56%   |
| Valve                   | 17        | 0.53%   |
| ASUSTek Computer        | 15        | 0.47%   |
| CPT                     | 14        | 0.44%   |
| CSO                     | 11        | 0.34%   |
| Quanta Display          | 8         | 0.25%   |
| MSI                     | 7         | 0.22%   |
| Analogix                | 7         | 0.22%   |
| ViewSonic               | 6         | 0.19%   |
| Unknown                 | 6         | 0.19%   |
| Seiko/Epson             | 5         | 0.16%   |
| Panasonic               | 5         | 0.16%   |
| Mi                      | 5         | 0.16%   |
| TMX                     | 4         | 0.12%   |
| NEC Computers           | 4         | 0.12%   |
| AGO                     | 4         | 0.12%   |
| Toshiba                 | 3         | 0.09%   |
| HUAWEI                  | 3         | 0.09%   |
| HKC                     | 3         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 65        | 2%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 38        | 1.17%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 31        | 0.96%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 31        | 0.96%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 31        | 0.96%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.65%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 21        | 0.65%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 20        | 0.62%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 18        | 0.55%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.55%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 17        | 0.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.52%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 16        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 16        | 0.49%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.46%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 15        | 0.46%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 15        | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 14        | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 0.43%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 14        | 0.43%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 13        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.4%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.4%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 13        | 0.4%    |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 12        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 12        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 11        | 0.34%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 11        | 0.34%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 11        | 0.34%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 11        | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 10        | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch             | 10        | 0.31%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 10        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch         | 10        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 10        | 0.31%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 10        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1212      | 40.6%   |
| 1366x768 (WXGA)    | 977       | 32.73%  |
| 1280x800 (WXGA)    | 168       | 5.63%   |
| 3840x2160 (4K)     | 83        | 2.78%   |
| 1600x900 (HD+)     | 78        | 2.61%   |
| 2560x1440 (QHD)    | 62        | 2.08%   |
| 1440x900 (WXGA+)   | 62        | 2.08%   |
| 1024x600           | 43        | 1.44%   |
| 1920x1200 (WUXGA)  | 40        | 1.34%   |
| 1280x1024 (SXGA)   | 32        | 1.07%   |
| 2560x1600          | 28        | 0.94%   |
| 1680x1050 (WSXGA+) | 27        | 0.9%    |
| 2160x1440          | 26        | 0.87%   |
| 800x1280           | 23        | 0.77%   |
| 3440x1440          | 16        | 0.54%   |
| 2880x1800          | 16        | 0.54%   |
| 2560x1080          | 14        | 0.47%   |
| 1024x768 (XGA)     | 8         | 0.27%   |
| 3200x1800 (QHD+)   | 7         | 0.23%   |
| 1360x768           | 7         | 0.23%   |
| 3840x2400          | 6         | 0.2%    |
| Unknown            | 5         | 0.17%   |
| 2520x1680          | 3         | 0.1%    |
| 2288x1287          | 3         | 0.1%    |
| 1920x540           | 3         | 0.1%    |
| 1920x1280          | 3         | 0.1%    |
| 1600x1200          | 3         | 0.1%    |
| 1400x1050          | 3         | 0.1%    |
| 1280x768           | 3         | 0.1%    |
| 3840x1600          | 2         | 0.07%   |
| 3840x1080          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 3200x2000          | 2         | 0.07%   |
| 3072x1920          | 2         | 0.07%   |
| 2304x1440          | 2         | 0.07%   |
| 5760x1080          | 1         | 0.03%   |
| 3200x1080          | 1         | 0.03%   |
| 3000x2000          | 1         | 0.03%   |
| 2880x1920          | 1         | 0.03%   |
| 2736x1824          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1557      | 48.5%   |
| 13      | 364       | 11.34%  |
| 14      | 266       | 8.29%   |
| 17      | 176       | 5.48%   |
| 24      | 112       | 3.49%   |
| 27      | 96        | 2.99%   |
| 21      | 86        | 2.68%   |
| 23      | 81        | 2.52%   |
| 12      | 61        | 1.9%    |
| 11      | 51        | 1.59%   |
| 10      | 50        | 1.56%   |
| 16      | 47        | 1.46%   |
| Unknown | 38        | 1.18%   |
| 34      | 30        | 0.93%   |
| 31      | 28        | 0.87%   |
| 19      | 24        | 0.75%   |
| 18      | 17        | 0.53%   |
| 7       | 17        | 0.53%   |
| 84      | 15        | 0.47%   |
| 20      | 14        | 0.44%   |
| 22      | 9         | 0.28%   |
| 72      | 8         | 0.25%   |
| 25      | 8         | 0.25%   |
| 54      | 7         | 0.22%   |
| 40      | 7         | 0.22%   |
| 3       | 7         | 0.22%   |
| 26      | 4         | 0.12%   |
| 52      | 3         | 0.09%   |
| 46      | 3         | 0.09%   |
| 38      | 3         | 0.09%   |
| 32      | 3         | 0.09%   |
| 8       | 3         | 0.09%   |
| 142     | 2         | 0.06%   |
| 37      | 2         | 0.06%   |
| 35      | 2         | 0.06%   |
| 65      | 1         | 0.03%   |
| 57      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 47      | 1         | 0.03%   |
| 42      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1975      | 62.15%  |
| 201-300        | 381       | 11.99%  |
| 501-600        | 276       | 8.68%   |
| 351-400        | 220       | 6.92%   |
| 401-500        | 135       | 4.25%   |
| Unknown        | 38        | 1.2%    |
| 601-700        | 36        | 1.13%   |
| 701-800        | 33        | 1.04%   |
| 1-100          | 24        | 0.76%   |
| 1501-2000      | 23        | 0.72%   |
| 1001-1500      | 17        | 0.53%   |
| 801-900        | 14        | 0.44%   |
| 101-200        | 3         | 0.09%   |
| More than 2000 | 2         | 0.06%   |
| 901-1000       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2288      | 81.08%  |
| 16/10   | 352       | 12.47%  |
| 3/2     | 43        | 1.52%   |
| 21/9    | 32        | 1.13%   |
| 5/4     | 31        | 1.1%    |
| Unknown | 29        | 1.03%   |
| 4/3     | 17        | 0.6%    |
| 0.67    | 17        | 0.6%    |
| 6/5     | 7         | 0.25%   |
| 1.00    | 2         | 0.07%   |
| 32/9    | 1         | 0.04%   |
| 1.03    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1569      | 49.02%  |
| 81-90          | 460       | 14.37%  |
| 201-250        | 240       | 7.5%    |
| 71-80          | 165       | 5.15%   |
| 121-130        | 126       | 3.94%   |
| 301-350        | 97        | 3.03%   |
| 351-500        | 62        | 1.94%   |
| 151-200        | 61        | 1.91%   |
| 61-70          | 57        | 1.78%   |
| 51-60          | 51        | 1.59%   |
| 41-50          | 50        | 1.56%   |
| More than 1000 | 38        | 1.19%   |
| Unknown        | 38        | 1.19%   |
| 131-140        | 35        | 1.09%   |
| 141-150        | 32        | 1%      |
| 251-300        | 30        | 0.94%   |
| 1-40           | 27        | 0.84%   |
| 111-120        | 27        | 0.84%   |
| 501-1000       | 18        | 0.56%   |
| 91-100         | 18        | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1128      | 35.98%  |
| 101-120       | 1028      | 32.79%  |
| 51-100        | 616       | 19.65%  |
| 161-240       | 217       | 6.92%   |
| More than 240 | 70        | 2.23%   |
| 1-50          | 38        | 1.21%   |
| Unknown       | 38        | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2305      | 78.48%  |
| 2     | 468       | 15.93%  |
| 0     | 97        | 3.3%    |
| 3     | 61        | 2.08%   |
| 4     | 5         | 0.17%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1601      | 34.6%   |
| Intel                             | 1360      | 29.39%  |
| Qualcomm Atheros                  | 717       | 15.5%   |
| Broadcom                          | 348       | 7.52%   |
| Broadcom Limited                  | 77        | 1.66%   |
| Marvell Technology Group          | 73        | 1.58%   |
| MediaTek                          | 52        | 1.12%   |
| TP-Link                           | 49        | 1.06%   |
| Ralink                            | 47        | 1.02%   |
| Ralink Technology                 | 36        | 0.78%   |
| ASIX Electronics                  | 24        | 0.52%   |
| Xiaomi                            | 20        | 0.43%   |
| Nvidia                            | 20        | 0.43%   |
| Samsung Electronics               | 18        | 0.39%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.3%    |
| Lenovo                            | 14        | 0.3%    |
| JMicron Technology                | 14        | 0.3%    |
| Dell                              | 14        | 0.3%    |
| Ericsson Business Mobile Networks | 13        | 0.28%   |
| Hewlett-Packard                   | 12        | 0.26%   |
| Sierra Wireless                   | 10        | 0.22%   |
| Qualcomm                          | 10        | 0.22%   |
| DisplayLink                       | 10        | 0.22%   |
| Qualcomm Atheros Communications   | 9         | 0.19%   |
| Huawei Technologies               | 6         | 0.13%   |
| D-Link                            | 6         | 0.13%   |
| VIA Technologies                  | 5         | 0.11%   |
| LSI                               | 4         | 0.09%   |
| Edimax Technology                 | 4         | 0.09%   |
| Attansic Technology               | 4         | 0.09%   |
| ASUSTek Computer                  | 4         | 0.09%   |
| Toshiba                           | 3         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.04%   |
| NetGear                           | 2         | 0.04%   |
| Google                            | 2         | 0.04%   |
| Fibocom                           | 2         | 0.04%   |
| D-Link System                     | 2         | 0.04%   |
| Arduino SA                        | 2         | 0.04%   |
| Accton Technology                 | 2         | 0.04%   |
| T & A Mobile Phones               | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 912       | 16.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 283       | 5.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 127       | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 125       | 2.29%   |
| Intel Wi-Fi 6 AX200                                                     | 120       | 2.2%    |
| Intel Wi-Fi 6 AX201                                                     | 109       | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 107       | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 104       | 1.91%   |
| Intel Wireless 8265 / 8275                                              | 103       | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 98        | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 98        | 1.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 86        | 1.58%   |
| Intel Wireless 7265                                                     | 82        | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 79        | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 67        | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 63        | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 1.16%   |
| Intel Wireless 7260                                                     | 62        | 1.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 59        | 1.08%   |
| Intel Wireless 3165                                                     | 56        | 1.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 55        | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 54        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 52        | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 46        | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 46        | 0.84%   |
| Intel WiFi Link 5100                                                    | 45        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 42        | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 39        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 37        | 0.68%   |
| Intel Wireless 8260                                                     | 36        | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 0.66%   |
| Intel Wireless 3160                                                     | 35        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 34        | 0.62%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 34        | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 32        | 0.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 29        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 29        | 0.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 0.51%   |
| Intel Centrino Advanced-N 6200                                          | 28        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1315      | 44.14%  |
| Qualcomm Atheros                | 603       | 20.24%  |
| Realtek Semiconductor           | 548       | 18.4%   |
| Broadcom                        | 232       | 7.79%   |
| Broadcom Limited                | 53        | 1.78%   |
| MediaTek                        | 50        | 1.68%   |
| Ralink                          | 47        | 1.58%   |
| Ralink Technology               | 36        | 1.21%   |
| TP-Link                         | 33        | 1.11%   |
| Sierra Wireless                 | 10        | 0.34%   |
| Qualcomm Atheros Communications | 9         | 0.3%    |
| Dell                            | 8         | 0.27%   |
| D-Link                          | 6         | 0.2%    |
| Qualcomm                        | 4         | 0.13%   |
| Hewlett-Packard                 | 4         | 0.13%   |
| Edimax Technology               | 4         | 0.13%   |
| ASUSTek Computer                | 4         | 0.13%   |
| NetGear                         | 2         | 0.07%   |
| Fibocom                         | 2         | 0.07%   |
| D-Link System                   | 2         | 0.07%   |
| Accton Technology               | 2         | 0.07%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Linksys                         | 1         | 0.03%   |
| Gemtek                          | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |
| AirTies Wireless Networks       | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 127       | 4.24%   |
| Intel Wi-Fi 6 AX200                                                     | 120       | 4.01%   |
| Intel Wi-Fi 6 AX201                                                     | 109       | 3.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 107       | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 104       | 3.47%   |
| Intel Wireless 8265 / 8275                                              | 103       | 3.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 98        | 3.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 98        | 3.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 86        | 2.87%   |
| Intel Wireless 7265                                                     | 82        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 79        | 2.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 67        | 2.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 63        | 2.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 2.1%    |
| Intel Wireless 7260                                                     | 62        | 2.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 59        | 1.97%   |
| Intel Wireless 3165                                                     | 56        | 1.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 54        | 1.8%    |
| Broadcom BCM43142 802.11b/g/n                                           | 52        | 1.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 46        | 1.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 46        | 1.54%   |
| Intel WiFi Link 5100                                                    | 45        | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 42        | 1.4%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 39        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 37        | 1.23%   |
| Intel Wireless 8260                                                     | 36        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 1.2%    |
| Intel Wireless 3160                                                     | 35        | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 34        | 1.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 29        | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 0.93%   |
| Intel Centrino Advanced-N 6200                                          | 28        | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 27        | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 27        | 0.9%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 25        | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 24        | 0.8%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 23        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 22        | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1363      | 57.66%  |
| Intel                                  | 370       | 15.65%  |
| Qualcomm Atheros                       | 192       | 8.12%   |
| Broadcom                               | 158       | 6.68%   |
| Marvell Technology Group               | 73        | 3.09%   |
| Broadcom Limited                       | 26        | 1.1%    |
| ASIX Electronics                       | 24        | 1.02%   |
| Xiaomi                                 | 20        | 0.85%   |
| Nvidia                                 | 20        | 0.85%   |
| TP-Link                                | 17        | 0.72%   |
| Silicon Integrated Systems [SiS]       | 14        | 0.59%   |
| Lenovo                                 | 14        | 0.59%   |
| JMicron Technology                     | 14        | 0.59%   |
| Samsung Electronics                    | 11        | 0.47%   |
| DisplayLink                            | 10        | 0.42%   |
| Qualcomm                               | 6         | 0.25%   |
| VIA Technologies                       | 5         | 0.21%   |
| LSI                                    | 4         | 0.17%   |
| Hewlett-Packard                        | 4         | 0.17%   |
| Attansic Technology                    | 4         | 0.17%   |
| Huawei Technologies                    | 3         | 0.13%   |
| MediaTek                               | 2         | 0.08%   |
| Google                                 | 2         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| OPPO Electronics                       | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| Davicom Semiconductor                  | 1         | 0.04%   |
| Apple                                  | 1         | 0.04%   |
| ADMtek                                 | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 912       | 38.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 283       | 11.82%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 125       | 5.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 55        | 2.3%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 34        | 1.42%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 32        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29        | 1.21%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 1.09%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 24        | 1%      |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                     | 22        | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 20        | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 19        | 0.79%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 17        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 17        | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 17        | 0.71%   |
| Intel Ethernet Connection (13) I219-V                             | 17        | 0.71%   |
| Intel 82567LM Gigabit Network Connection                          | 17        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 16        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 15        | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 15        | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14        | 0.58%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 14        | 0.58%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.58%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 13        | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 12        | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.5%    |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 11        | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2808      | 54.46%  |
| Ethernet | 2292      | 44.45%  |
| Modem    | 52        | 1.01%   |
| Unknown  | 4         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2289      | 75.47%  |
| Ethernet | 744       | 24.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2065      | 72%     |
| 1     | 728       | 25.38%  |
| 0     | 60        | 2.09%   |
| 3     | 14        | 0.49%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2767      | 95.98%  |
| Yes  | 116       | 4.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 997       | 46.31%  |
| Realtek Semiconductor           | 267       | 12.4%   |
| IMC Networks                    | 167       | 7.76%   |
| Qualcomm Atheros Communications | 142       | 6.6%    |
| Lite-On Technology              | 99        | 4.6%    |
| Broadcom                        | 94        | 4.37%   |
| Foxconn / Hon Hai               | 90        | 4.18%   |
| Apple                           | 63        | 2.93%   |
| Realtek                         | 40        | 1.86%   |
| Toshiba                         | 38        | 1.76%   |
| Cambridge Silicon Radio         | 38        | 1.76%   |
| Dell                            | 27        | 1.25%   |
| Hewlett-Packard                 | 24        | 1.11%   |
| Ralink                          | 19        | 0.88%   |
| ASUSTek Computer                | 14        | 0.65%   |
| Alps Electric                   | 14        | 0.65%   |
| Foxconn International           | 8         | 0.37%   |
| Ralink Technology               | 4         | 0.19%   |
| Taiyo Yuden                     | 2         | 0.09%   |
| MediaTek                        | 2         | 0.09%   |
| Askey Computer                  | 2         | 0.09%   |
| ISSC                            | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 369       | 17.14%  |
| Intel AX201 Bluetooth                               | 210       | 9.75%   |
| Realtek Bluetooth Radio                             | 182       | 8.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 182       | 8.45%   |
| Intel AX200 Bluetooth                               | 118       | 5.48%   |
| IMC Networks Bluetooth Radio                        | 86        | 3.99%   |
| Qualcomm Atheros  Bluetooth Device                  | 56        | 2.6%    |
| Realtek  Bluetooth 4.2 Adapter                      | 53        | 2.46%   |
| IMC Networks Bluetooth Device                       | 42        | 1.95%   |
| Realtek Bluetooth Radio                             | 40        | 1.86%   |
| Foxconn / Hon Hai Bluetooth Device                  | 40        | 1.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 38        | 1.76%   |
| Apple Bluetooth Host Controller                     | 38        | 1.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 33        | 1.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 29        | 1.35%   |
| Intel Bluetooth Device                              | 27        | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 26        | 1.21%   |
| Lite-On Bluetooth Device                            | 25        | 1.16%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 1.16%   |
| Intel AX210 Bluetooth                               | 23        | 1.07%   |
| IMC Networks Wireless_Device                        | 23        | 1.07%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 0.98%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 18        | 0.84%   |
| Apple Bluetooth USB Host Controller                 | 17        | 0.79%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.56%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 0.56%   |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.51%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 11        | 0.51%   |
| Realtek RTL8821A Bluetooth                          | 10        | 0.46%   |
| Broadcom BCM2045 Bluetooth                          | 10        | 0.46%   |
| Alps Electric BCM2046 Bluetooth Device              | 9         | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.37%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.37%   |
| Foxconn International BCM43142A0 Bluetooth module   | 8         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2271      | 65.45%  |
| AMD                                  | 596       | 17.18%  |
| Nvidia                               | 402       | 11.59%  |
| C-Media Electronics                  | 23        | 0.66%   |
| Logitech                             | 19        | 0.55%   |
| Lenovo                               | 15        | 0.43%   |
| Silicon Integrated Systems [SiS]     | 14        | 0.4%    |
| Plantronics                          | 11        | 0.32%   |
| GN Netcom                            | 11        | 0.32%   |
| Realtek Semiconductor                | 7         | 0.2%    |
| JMTek                                | 7         | 0.2%    |
| VIA Technologies                     | 6         | 0.17%   |
| Texas Instruments                    | 6         | 0.17%   |
| Kingston Technology                  | 5         | 0.14%   |
| Generalplus Technology               | 5         | 0.14%   |
| SteelSeries ApS                      | 4         | 0.12%   |
| Corsair                              | 4         | 0.12%   |
| ASUSTek Computer                     | 4         | 0.12%   |
| Sennheiser Communications            | 3         | 0.09%   |
| Hewlett-Packard                      | 3         | 0.09%   |
| Creative Technology                  | 3         | 0.09%   |
| BEHRINGER International              | 3         | 0.09%   |
| Apple                                | 3         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.06%   |
| Sony                                 | 2         | 0.06%   |
| No brand                             | 2         | 0.06%   |
| Huawei Technologies                  | 2         | 0.06%   |
| Guillemot                            | 2         | 0.06%   |
| CMX Systems                          | 2         | 0.06%   |
| Blue Microphones                     | 2         | 0.06%   |
| Alesis                               | 2         | 0.06%   |
| Vestax                               | 1         | 0.03%   |
| Veho                                 | 1         | 0.03%   |
| Trust                                | 1         | 0.03%   |
| ThrustMaster                         | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |
| Signalpath International             | 1         | 0.03%   |
| Samsung Electronics                  | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |
| PreSonus Audio Electronics           | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 296       | 7.07%   |
| AMD Family 17h/19h HD Audio Controller                                     | 288       | 6.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 163       | 3.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 151       | 3.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 145       | 3.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 135       | 3.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 135       | 3.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 130       | 3.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 128       | 3.06%   |
| Intel Haswell-ULT HD Audio Controller                                      | 127       | 3.03%   |
| Intel 8 Series HD Audio Controller                                         | 127       | 3.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 103       | 2.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 100       | 2.39%   |
| Intel Comet Lake PCH-LP cAVS                                               | 93        | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 92        | 2.2%    |
| Intel Broadwell-U Audio Controller                                         | 90        | 2.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 89        | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 85        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 75        | 1.79%   |
| AMD FCH Azalia Controller                                                  | 74        | 1.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 73        | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 66        | 1.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 62        | 1.48%   |
| AMD Kabini HDMI/DP Audio                                                   | 61        | 1.46%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 54        | 1.29%   |
| Intel Comet Lake PCH cAVS                                                  | 53        | 1.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 52        | 1.24%   |
| AMD High Definition Audio Controller                                       | 52        | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 51        | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 46        | 1.1%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 42        | 1%      |
| Nvidia GA106 High Definition Audio Controller                              | 41        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 40        | 0.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 39        | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 38        | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                            | 37        | 0.88%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 34        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 31        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 31        | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 30        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 534       | 30.2%   |
| SK hynix                                         | 376       | 21.27%  |
| Micron Technology                                | 225       | 12.73%  |
| Kingston                                         | 165       | 9.33%   |
| Unknown                                          | 133       | 7.52%   |
| Crucial                                          | 90        | 5.09%   |
| Ramaxel Technology                               | 59        | 3.34%   |
| Elpida                                           | 27        | 1.53%   |
| Unknown (ABCD)                                   | 26        | 1.47%   |
| A-DATA Technology                                | 20        | 1.13%   |
| Corsair                                          | 18        | 1.02%   |
| Nanya Technology                                 | 17        | 0.96%   |
| G.Skill                                          | 11        | 0.62%   |
| Silicon Power                                    | 10        | 0.57%   |
| Unknown                                          | 8         | 0.45%   |
| Goodram                                          | 6         | 0.34%   |
| Transcend                                        | 5         | 0.28%   |
| Wilk                                             | 3         | 0.17%   |
| Apacer                                           | 3         | 0.17%   |
| Toshiba                                          | 2         | 0.11%   |
| SHARETRONIC                                      | 2         | 0.11%   |
| Patriot                                          | 2         | 0.11%   |
| KomputerBay                                      | 2         | 0.11%   |
| ChangXin Memory                                  | 2         | 0.11%   |
| Avant                                            | 2         | 0.11%   |
| Unknown (0x202020202020202020202020202020202020) | 1         | 0.06%   |
| Unifosa                                          | 1         | 0.06%   |
| Timetec                                          | 1         | 0.06%   |
| Team                                             | 1         | 0.06%   |
| Qimonda                                          | 1         | 0.06%   |
| PUSKILL                                          | 1         | 0.06%   |
| PNY                                              | 1         | 0.06%   |
| Patriot Memory (PDP Systems)                     | 1         | 0.06%   |
| Netlist                                          | 1         | 0.06%   |
| Netac                                            | 1         | 0.06%   |
| Neo Forza                                        | 1         | 0.06%   |
| Micron/Elpida                                    | 1         | 0.06%   |
| Kllisre                                          | 1         | 0.06%   |
| Kembona                                          | 1         | 0.06%   |
| ff                                               | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 32        | 1.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 27        | 1.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 1.25%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 22        | 1.19%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 1.19%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 1.08%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 20        | 1.08%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.92%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 0.92%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 16        | 0.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.81%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 15        | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.76%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.76%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 13        | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 13        | 0.7%    |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 12        | 0.65%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.65%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.6%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.6%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 10        | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.54%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.54%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.54%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.54%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 10        | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 10        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 10        | 0.54%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 10        | 0.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 737       | 49.04%  |
| DDR3    | 452       | 30.07%  |
| DDR2    | 91        | 6.05%   |
| LPDDR4  | 83        | 5.52%   |
| LPDDR3  | 51        | 3.39%   |
| SDRAM   | 34        | 2.26%   |
| DDR5    | 22        | 1.46%   |
| Unknown | 10        | 0.67%   |
| LPDDR5  | 9         | 0.6%    |
| DDR     | 8         | 0.53%   |
| DRAM    | 6         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1338      | 88.32%  |
| Row Of Chips | 157       | 10.36%  |
| DIMM         | 10        | 0.66%   |
| Chip         | 8         | 0.53%   |
| Unknown      | 2         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 639       | 39.18%  |
| 4096  | 450       | 27.59%  |
| 16384 | 254       | 15.57%  |
| 2048  | 188       | 11.53%  |
| 1024  | 62        | 3.8%    |
| 32768 | 31        | 1.9%    |
| 512   | 4         | 0.25%   |
| 256   | 2         | 0.12%   |
| 3072  | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 335       | 20.73%  |
| 3200    | 315       | 19.49%  |
| 1600    | 303       | 18.75%  |
| 2400    | 112       | 6.93%   |
| 1334    | 75        | 4.64%   |
| 2133    | 72        | 4.46%   |
| 667     | 65        | 4.02%   |
| 1333    | 54        | 3.34%   |
| Unknown | 40        | 2.48%   |
| 8400    | 32        | 1.98%   |
| 4267    | 30        | 1.86%   |
| 1067    | 26        | 1.61%   |
| 4800    | 23        | 1.42%   |
| 1867    | 18        | 1.11%   |
| 800     | 17        | 1.05%   |
| 3266    | 16        | 0.99%   |
| 2048    | 13        | 0.8%    |
| 533     | 12        | 0.74%   |
| 4199    | 11        | 0.68%   |
| 6400    | 10        | 0.62%   |
| 1066    | 8         | 0.5%    |
| 4266    | 7         | 0.43%   |
| 975     | 6         | 0.37%   |
| 3733    | 3         | 0.19%   |
| 2933    | 2         | 0.12%   |
| 1639    | 2         | 0.12%   |
| 1200    | 2         | 0.12%   |
| 3600    | 1         | 0.06%   |
| 3000    | 1         | 0.06%   |
| 1866    | 1         | 0.06%   |
| 1776    | 1         | 0.06%   |
| 666     | 1         | 0.06%   |
| 333     | 1         | 0.06%   |
| 266     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 14        | 53.85%  |
| Seiko Epson        | 4         | 15.38%  |
| Canon              | 4         | 15.38%  |
| Brother Industries | 4         | 15.38%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon PIXMA MG2500 Series          | 3         | 11.54%  |
| Seiko Epson XP-230 Series          | 1         | 3.85%   |
| Seiko Epson Printer                | 1         | 3.85%   |
| Seiko Epson L555 Series            | 1         | 3.85%   |
| Seiko Epson ET-2700 Series         | 1         | 3.85%   |
| HP PSC 1500 series                 | 1         | 3.85%   |
| HP Printing Support                | 1         | 3.85%   |
| HP Officejet 7110 series           | 1         | 3.85%   |
| HP LaserJet Professional P 1102w   | 1         | 3.85%   |
| HP LaserJet Pro M404-M405          | 1         | 3.85%   |
| HP LaserJet M14-M17                | 1         | 3.85%   |
| HP LaserJet 1320                   | 1         | 3.85%   |
| HP LaserJet 1020                   | 1         | 3.85%   |
| HP LaserJet 1018                   | 1         | 3.85%   |
| HP LaserJet 1000                   | 1         | 3.85%   |
| HP DeskJet F300 series             | 1         | 3.85%   |
| HP DeskJet F2492 All-in-One        | 1         | 3.85%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 3.85%   |
| HP Deskjet 2050 J510               | 1         | 3.85%   |
| Canon TS3100 series                | 1         | 3.85%   |
| Brother MFC-J5330DW                | 1         | 3.85%   |
| Brother HL-L3270CDW series         | 1         | 3.85%   |
| Brother HL-2030 Laser Printer      | 1         | 3.85%   |
| Brother HL-1210W series            | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP ScanJet 4300c              | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30 | 1         | 33.33%  |
| Canon CanoScan LiDE 210       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 640       | 25.96%  |
| IMC Networks                           | 304       | 12.33%  |
| Realtek Semiconductor                  | 160       | 6.49%   |
| Microdia                               | 160       | 6.49%   |
| Acer                                   | 135       | 5.48%   |
| Quanta                                 | 131       | 5.31%   |
| Bison Electronics                      | 131       | 5.31%   |
| Suyin                                  | 122       | 4.95%   |
| Sunplus Innovation Technology          | 104       | 4.22%   |
| Cheng Uei Precision Industry (Foxlink) | 97        | 3.94%   |
| Syntek                                 | 76        | 3.08%   |
| Alcor Micro                            | 45        | 1.83%   |
| Apple                                  | 40        | 1.62%   |
| Lite-On Technology                     | 39        | 1.58%   |
| Luxvisions Innotech Limited            | 36        | 1.46%   |
| Ricoh                                  | 32        | 1.3%    |
| Logitech                               | 26        | 1.05%   |
| Silicon Motion                         | 22        | 0.89%   |
| Sonix Technology                       | 15        | 0.61%   |
| Samsung Electronics                    | 12        | 0.49%   |
| USB Camera                             | 11        | 0.45%   |
| Lenovo                                 | 10        | 0.41%   |
| Importek                               | 10        | 0.41%   |
| Z-Star Microelectronics                | 9         | 0.37%   |
| ALi                                    | 9         | 0.37%   |
| GEMBIRD                                | 8         | 0.32%   |
| Intel                                  | 7         | 0.28%   |
| Sunplus Technology                     | 6         | 0.24%   |
| Primax Electronics                     | 6         | 0.24%   |
| OmniVision Technologies                | 5         | 0.2%    |
| KYE Systems (Mouse Systems)            | 5         | 0.2%    |
| Genesys Logic                          | 5         | 0.2%    |
| DigiTech                               | 5         | 0.2%    |
| ARC International                      | 4         | 0.16%   |
| Trust                                  | 3         | 0.12%   |
| Generalplus Technology                 | 3         | 0.12%   |
| Novatek Microelectronics               | 2         | 0.08%   |
| Microsoft                              | 2         | 0.08%   |
| Creative Technology                    | 2         | 0.08%   |
| 2M UVC CAMERA                          | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 79        | 3.2%    |
| Chicony HD WebCam                                       | 70        | 2.83%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 67        | 2.71%   |
| Chicony Integrated Camera                               | 67        | 2.71%   |
| Microdia Integrated_Webcam_HD                           | 63        | 2.55%   |
| Acer HD Webcam                                          | 57        | 2.31%   |
| IMC Networks Integrated Camera                          | 49        | 1.98%   |
| Chicony USB2.0 VGA UVC WebCam                           | 42        | 1.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 33        | 1.33%   |
| Quanta HP TrueVision HD Camera                          | 33        | 1.33%   |
| Realtek Integrated_Webcam_HD                            | 31        | 1.25%   |
| Acer Integrated Camera                                  | 31        | 1.25%   |
| Sunplus HD WebCam                                       | 29        | 1.17%   |
| Bison Integrated Camera                                 | 28        | 1.13%   |
| Syntek Integrated Camera                                | 27        | 1.09%   |
| Realtek USB Camera                                      | 27        | 1.09%   |
| Chicony USB 2.0 Camera                                  | 26        | 1.05%   |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 1.05%   |
| Chicony EasyCamera                                      | 26        | 1.05%   |
| Chicony USB2.0 Camera                                   | 22        | 0.89%   |
| Chicony USB2.0 HD UVC WebCam                            | 20        | 0.81%   |
| Syntek EasyCamera                                       | 19        | 0.77%   |
| IMC Networks ov9734_azurewave_camera                    | 19        | 0.77%   |
| Bison HD Camera                                         | 19        | 0.77%   |
| Syntek Lenovo EasyCamera                                | 18        | 0.73%   |
| Lite-On Integrated Camera                               | 18        | 0.73%   |
| Chicony VGA Webcam                                      | 18        | 0.73%   |
| Chicony Integrated Camera (1280x720@30)                 | 18        | 0.73%   |
| Chicony HP TrueVision HD Camera                         | 18        | 0.73%   |
| Chicony HP Truevision HD                                | 18        | 0.73%   |
| Apple Built-in iSight                                   | 18        | 0.73%   |
| Realtek Lenovo EasyCamera                               | 17        | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 17        | 0.69%   |
| Alcor Micro Asus Integrated Webcam                      | 17        | 0.69%   |
| Sunplus Integrated_Webcam_HD                            | 16        | 0.65%   |
| Microdia Webcam Vitade AF                               | 16        | 0.65%   |
| Chicony HP HD Camera                                    | 16        | 0.65%   |
| Quanta HP Wide Vision HD Camera                         | 15        | 0.61%   |
| Quanta HP Webcam                                        | 15        | 0.61%   |
| Quanta HP HD Camera                                     | 15        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 111       | 28.24%  |
| Validity Sensors                   | 91        | 23.16%  |
| Shenzhen Goodix Technology         | 70        | 17.81%  |
| Elan Microelectronics              | 38        | 9.67%   |
| AuthenTec                          | 37        | 9.41%   |
| Upek                               | 27        | 6.87%   |
| LighTuning Technology              | 11        | 2.8%    |
| STMicroelectronics                 | 7         | 1.78%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 55        | 13.99%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 37        | 9.41%   |
| Elan ELAN:Fingerprint                                                      | 34        | 8.65%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 31        | 7.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 5.6%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 4.83%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 3.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.05%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 3.05%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.8%    |
| Validity Sensors Synaptics WBDI                                            | 8         | 2.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.04%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.78%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.78%   |
| AuthenTec AES1600                                                          | 7         | 1.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.53%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.53%   |
| Validity Sensors VFS491                                                    | 5         | 1.27%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.27%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.27%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.27%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.27%   |
| AuthenTec AES2810                                                          | 5         | 1.27%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 1.27%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1.02%   |
| Synaptics  WBDI                                                            | 4         | 1.02%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.02%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.02%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.76%   |
| Synaptics UWP WBDI                                                         | 3         | 0.76%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 0.76%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.76%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.76%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.51%   |
| Synaptics WBDI                                                             | 2         | 0.51%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.51%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 59        | 35.12%  |
| Broadcom              | 56        | 33.33%  |
| O2 Micro              | 24        | 14.29%  |
| Lenovo                | 10        | 5.95%   |
| Upek                  | 4         | 2.38%   |
| C3PO                  | 4         | 2.38%   |
| Realtek Semiconductor | 3         | 1.79%   |
| Cherry                | 3         | 1.79%   |
| Gemalto (was Gemplus) | 2         | 1.19%   |
| In Focus Systems      | 1         | 0.6%    |
| Chicony Electronics   | 1         | 0.6%    |
| Advanced Card Systems | 1         | 0.6%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 59        | 35.12%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 13.69%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 11.9%   |
| Broadcom 5880                                                                | 16        | 9.52%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 5.95%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 5.95%   |
| Broadcom 58200                                                               | 9         | 5.36%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.38%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.79%   |
| Cherry SmartTerminal XX1X                                                    | 3         | 1.79%   |
| C3PO LTC31v2                                                                 | 3         | 1.79%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.19%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.6%    |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.6%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.6%    |
| C3PO USB SMART CARD READER                                                   | 1         | 0.6%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.6%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.6%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1896      | 64.38%  |
| 1     | 810       | 27.5%   |
| 2     | 198       | 6.72%   |
| 3     | 26        | 0.88%   |
| 4     | 8         | 0.27%   |
| 5     | 5         | 0.17%   |
| 8     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 384       | 29.61%  |
| Graphics card            | 310       | 23.9%   |
| Net/wireless             | 172       | 13.26%  |
| Chipcard                 | 147       | 11.33%  |
| Multimedia controller    | 80        | 6.17%   |
| Camera                   | 47        | 3.62%   |
| Bluetooth                | 35        | 2.7%    |
| Storage                  | 27        | 2.08%   |
| Communication controller | 24        | 1.85%   |
| Card reader              | 18        | 1.39%   |
| Net/ethernet             | 13        | 1%      |
| Sound                    | 12        | 0.93%   |
| Flash memory             | 10        | 0.77%   |
| Modem                    | 8         | 0.62%   |
| Network                  | 6         | 0.46%   |
| Dvb card                 | 4         | 0.31%   |

