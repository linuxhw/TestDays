Linux in India - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in India.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/India/Desktop/README.md) and [notebooks](/Location/India/Notebook/README.md).

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

Total: 7145

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 859C                        | Desktop     | [bc1cc805c6](https://linux-hardware.org/?probe=bc1cc805c6) | Feb 02, 2024 |
| INP           | i1000BTS                    | Desktop     | [3148738295](https://linux-hardware.org/?probe=3148738295) | Feb 02, 2024 |
| MSI           | Thin GF63 12HW              | Notebook    | [b5b16477c3](https://linux-hardware.org/?probe=b5b16477c3) | Feb 02, 2024 |
| Intel         | DH61HO AAG62445-102         | Desktop     | [f6db94d707](https://linux-hardware.org/?probe=f6db94d707) | Feb 01, 2024 |
| Intel         | DH61HO AAG62445-102         | Desktop     | [4752f66f57](https://linux-hardware.org/?probe=4752f66f57) | Feb 01, 2024 |
| MSI           | Z370 PC PRO                 | Desktop     | [b0a50105f7](https://linux-hardware.org/?probe=b0a50105f7) | Feb 01, 2024 |
| Dell          | Latitude 5420               | Notebook    | [9ca4bb32d7](https://linux-hardware.org/?probe=9ca4bb32d7) | Feb 01, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [151239b938](https://linux-hardware.org/?probe=151239b938) | Feb 01, 2024 |
| Lenovo        | 3330 NOK                    | Mini pc     | [c925201205](https://linux-hardware.org/?probe=c925201205) | Feb 01, 2024 |
| Dell          | 0N0992 A00                  | Desktop     | [b1aae1e53b](https://linux-hardware.org/?probe=b1aae1e53b) | Feb 01, 2024 |
| Dell          | Inspiron 7501               | Notebook    | [5c071c25ab](https://linux-hardware.org/?probe=5c071c25ab) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [bb6dd71048](https://linux-hardware.org/?probe=bb6dd71048) | Feb 01, 2024 |
| Dell          | Inspiron 16 Plus 7630       | Notebook    | [af2db531a1](https://linux-hardware.org/?probe=af2db531a1) | Jan 31, 2024 |
| Lenovo        | IdeaPad Y560                | Notebook    | [e9a51b1fa8](https://linux-hardware.org/?probe=e9a51b1fa8) | Jan 31, 2024 |
| Infinix       | INBOOK X1 NEO               | Notebook    | [aca7de6cf8](https://linux-hardware.org/?probe=aca7de6cf8) | Jan 31, 2024 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [916a39975c](https://linux-hardware.org/?probe=916a39975c) | Jan 31, 2024 |
| MSI           | Bravo 15 B5DD               | Notebook    | [a989f7aa10](https://linux-hardware.org/?probe=a989f7aa10) | Jan 30, 2024 |
| Lenovo        | IdeaPad Y560                | Notebook    | [a32d1d3fa7](https://linux-hardware.org/?probe=a32d1d3fa7) | Jan 30, 2024 |
| MSI           | Thin GF63 12HW              | Notebook    | [5c79e92eb3](https://linux-hardware.org/?probe=5c79e92eb3) | Jan 30, 2024 |
| MSI           | GL63 9SD                    | Notebook    | [174a4f49ac](https://linux-hardware.org/?probe=174a4f49ac) | Jan 29, 2024 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [2e4fa19ae6](https://linux-hardware.org/?probe=2e4fa19ae6) | Jan 29, 2024 |
| Dell          | Latitude E6410              | Notebook    | [1d71a03516](https://linux-hardware.org/?probe=1d71a03516) | Jan 29, 2024 |
| Dell          | Vostro 3558                 | Notebook    | [f2c958ad91](https://linux-hardware.org/?probe=f2c958ad91) | Jan 29, 2024 |
| HP            | EliteBook 840 g5            | Notebook    | [b9ca87e1e4](https://linux-hardware.org/?probe=b9ca87e1e4) | Jan 28, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [0b1a4a9d6c](https://linux-hardware.org/?probe=0b1a4a9d6c) | Jan 28, 2024 |
| Lenovo        | ThinkPad T480 20L6S4T80H    | Notebook    | [cb5f6705aa](https://linux-hardware.org/?probe=cb5f6705aa) | Jan 28, 2024 |
| Tyrone Sys... | DIT400TR-48RL Intel Chip... | Server      | [6f84182a9b](https://linux-hardware.org/?probe=6f84182a9b) | Jan 28, 2024 |
| Dell          | Inspiron 3537               | Notebook    | [e91c3bfd73](https://linux-hardware.org/?probe=e91c3bfd73) | Jan 28, 2024 |
| Dell          | Inspiron 3537               | Notebook    | [0ee7687e3f](https://linux-hardware.org/?probe=0ee7687e3f) | Jan 28, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [e6b8ceb566](https://linux-hardware.org/?probe=e6b8ceb566) | Jan 27, 2024 |
| Lenovo        | ThinkPad E14 20RAS1S600     | Notebook    | [8544584b30](https://linux-hardware.org/?probe=8544584b30) | Jan 27, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [2a81d5f313](https://linux-hardware.org/?probe=2a81d5f313) | Jan 27, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [fad23c2b03](https://linux-hardware.org/?probe=fad23c2b03) | Jan 27, 2024 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [a354ee36fe](https://linux-hardware.org/?probe=a354ee36fe) | Jan 26, 2024 |
| Google        | Kench                       | Desktop     | [42065dff7f](https://linux-hardware.org/?probe=42065dff7f) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3932a6e2cf](https://linux-hardware.org/?probe=3932a6e2cf) | Jan 26, 2024 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [4d1f942627](https://linux-hardware.org/?probe=4d1f942627) | Jan 25, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [b892b5b8a4](https://linux-hardware.org/?probe=b892b5b8a4) | Jan 25, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [2b4a8624c9](https://linux-hardware.org/?probe=2b4a8624c9) | Jan 24, 2024 |
| Acer          | Nitro AN515-45              | Notebook    | [decd7eb6dc](https://linux-hardware.org/?probe=decd7eb6dc) | Jan 24, 2024 |
| Acer          | Aspire A315-55G             | Notebook    | [c04d6bddfb](https://linux-hardware.org/?probe=c04d6bddfb) | Jan 24, 2024 |
| LG Electro... | 14Z990-V.AR52A2             | Notebook    | [346844d302](https://linux-hardware.org/?probe=346844d302) | Jan 24, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9f4bd475eb](https://linux-hardware.org/?probe=9f4bd475eb) | Jan 23, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [91f61c4366](https://linux-hardware.org/?probe=91f61c4366) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [59eb577232](https://linux-hardware.org/?probe=59eb577232) | Jan 23, 2024 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [c2d6eded11](https://linux-hardware.org/?probe=c2d6eded11) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [5d754d0510](https://linux-hardware.org/?probe=5d754d0510) | Jan 23, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [ba1a3bef35](https://linux-hardware.org/?probe=ba1a3bef35) | Jan 21, 2024 |
| HP            | Pavilion g6                 | Notebook    | [58e29cfd8a](https://linux-hardware.org/?probe=58e29cfd8a) | Jan 21, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [dce46de08f](https://linux-hardware.org/?probe=dce46de08f) | Jan 21, 2024 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [320f2c215a](https://linux-hardware.org/?probe=320f2c215a) | Jan 21, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ddb59f8c7e](https://linux-hardware.org/?probe=ddb59f8c7e) | Jan 21, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [833af537d7](https://linux-hardware.org/?probe=833af537d7) | Jan 21, 2024 |
| Dell          | Inspiron 14 5410            | Notebook    | [018d9742c7](https://linux-hardware.org/?probe=018d9742c7) | Jan 21, 2024 |
| HP            | Notebook                    | Notebook    | [71136f647b](https://linux-hardware.org/?probe=71136f647b) | Jan 20, 2024 |
| Dell          | Inspiron 15 3511            | Notebook    | [d79a7275ed](https://linux-hardware.org/?probe=d79a7275ed) | Jan 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5797795e83](https://linux-hardware.org/?probe=5797795e83) | Jan 20, 2024 |
| Lenovo        | 1037 NO DPK                 | Server      | [da53a6a2c0](https://linux-hardware.org/?probe=da53a6a2c0) | Jan 20, 2024 |
| Infinix       | ZERO BOOK 13                | Notebook    | [5f3718642b](https://linux-hardware.org/?probe=5f3718642b) | Jan 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [9fd92c9632](https://linux-hardware.org/?probe=9fd92c9632) | Jan 20, 2024 |
| Intel         | H55                         | Desktop     | [ab5eadebb8](https://linux-hardware.org/?probe=ab5eadebb8) | Jan 19, 2024 |
| HONOR         | BMH-WCX9                    | Notebook    | [45113bdfbb](https://linux-hardware.org/?probe=45113bdfbb) | Jan 19, 2024 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [5cb5cb9692](https://linux-hardware.org/?probe=5cb5cb9692) | Jan 19, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [dcd7920f8c](https://linux-hardware.org/?probe=dcd7920f8c) | Jan 19, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [bf4f40eec4](https://linux-hardware.org/?probe=bf4f40eec4) | Jan 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [fb993819da](https://linux-hardware.org/?probe=fb993819da) | Jan 18, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [459fc53c83](https://linux-hardware.org/?probe=459fc53c83) | Jan 18, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [8d75949d34](https://linux-hardware.org/?probe=8d75949d34) | Jan 18, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 Ua 82F... | Notebook    | [741f29036a](https://linux-hardware.org/?probe=741f29036a) | Jan 17, 2024 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [972e4192b6](https://linux-hardware.org/?probe=972e4192b6) | Jan 17, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [589c4362a6](https://linux-hardware.org/?probe=589c4362a6) | Jan 16, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [78896edb96](https://linux-hardware.org/?probe=78896edb96) | Jan 16, 2024 |
| Infinix       | INBook X1 Pro               | Notebook    | [8fd49f9543](https://linux-hardware.org/?probe=8fd49f9543) | Jan 16, 2024 |
| Infinix       | INBOOK X1 NEO               | Notebook    | [ff730c7320](https://linux-hardware.org/?probe=ff730c7320) | Jan 16, 2024 |
| HP            | 15                          | Notebook    | [c84c138cef](https://linux-hardware.org/?probe=c84c138cef) | Jan 16, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [f1ec7dddcf](https://linux-hardware.org/?probe=f1ec7dddcf) | Jan 16, 2024 |
| Dell          | Latitude E5520              | Notebook    | [9700d44fe1](https://linux-hardware.org/?probe=9700d44fe1) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [d124634554](https://linux-hardware.org/?probe=d124634554) | Jan 15, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [fecc6a63eb](https://linux-hardware.org/?probe=fecc6a63eb) | Jan 15, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [51693df272](https://linux-hardware.org/?probe=51693df272) | Jan 15, 2024 |
| HP            | 15                          | Notebook    | [c247a8a3fb](https://linux-hardware.org/?probe=c247a8a3fb) | Jan 14, 2024 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [7f3e95be9c](https://linux-hardware.org/?probe=7f3e95be9c) | Jan 14, 2024 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [a14c93df78](https://linux-hardware.org/?probe=a14c93df78) | Jan 14, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ec35eb7a72](https://linux-hardware.org/?probe=ec35eb7a72) | Jan 14, 2024 |
| Dell          | Latitude E6420              | Notebook    | [78cffcaf30](https://linux-hardware.org/?probe=78cffcaf30) | Jan 14, 2024 |
| Lenovo        | ThinkPad L380 20M6S1MG0X    | Notebook    | [74d87d7f6f](https://linux-hardware.org/?probe=74d87d7f6f) | Jan 14, 2024 |
| Lenovo        | ThinkPad L380 20M6S1MG0X    | Notebook    | [9551a51d17](https://linux-hardware.org/?probe=9551a51d17) | Jan 13, 2024 |
| MSI           | GL63 8RC                    | Notebook    | [2e52a98d20](https://linux-hardware.org/?probe=2e52a98d20) | Jan 13, 2024 |
| Gigabyte      | H610M H DDR4                | Desktop     | [7ad8786f92](https://linux-hardware.org/?probe=7ad8786f92) | Jan 13, 2024 |
| Dell          | Vostro 3500                 | Notebook    | [a6d51704d8](https://linux-hardware.org/?probe=a6d51704d8) | Jan 13, 2024 |
| Samsung       | RV408/RV508                 | Notebook    | [05836028b1](https://linux-hardware.org/?probe=05836028b1) | Jan 13, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [f29e741e2b](https://linux-hardware.org/?probe=f29e741e2b) | Jan 13, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [52aaf67030](https://linux-hardware.org/?probe=52aaf67030) | Jan 13, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [a74400cdb0](https://linux-hardware.org/?probe=a74400cdb0) | Jan 12, 2024 |
| Google        | Kench                       | Desktop     | [09cb7c7c8c](https://linux-hardware.org/?probe=09cb7c7c8c) | Jan 12, 2024 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [212135f3b5](https://linux-hardware.org/?probe=212135f3b5) | Jan 12, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [c9788a2dac](https://linux-hardware.org/?probe=c9788a2dac) | Jan 12, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ddfda4248f](https://linux-hardware.org/?probe=ddfda4248f) | Jan 12, 2024 |
| HP            | 348 G5                      | Notebook    | [a7c6a60aaf](https://linux-hardware.org/?probe=a7c6a60aaf) | Jan 12, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8e72c34b9e](https://linux-hardware.org/?probe=8e72c34b9e) | Jan 11, 2024 |
| HP            | Notebook                    | Notebook    | [53e2f16b51](https://linux-hardware.org/?probe=53e2f16b51) | Jan 11, 2024 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [cbce15965a](https://linux-hardware.org/?probe=cbce15965a) | Jan 11, 2024 |
| Dell          | Latitude 5511               | Notebook    | [a445a8c583](https://linux-hardware.org/?probe=a445a8c583) | Jan 11, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6394ca334a](https://linux-hardware.org/?probe=6394ca334a) | Jan 10, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [54f475b387](https://linux-hardware.org/?probe=54f475b387) | Jan 10, 2024 |
| Dell          | 0J9VVP A00                  | Desktop     | [855cc5cb5c](https://linux-hardware.org/?probe=855cc5cb5c) | Jan 10, 2024 |
| Infinix       | ZERO BOOK 13                | Notebook    | [7101d9332b](https://linux-hardware.org/?probe=7101d9332b) | Jan 10, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5c2e8e03c6](https://linux-hardware.org/?probe=5c2e8e03c6) | Jan 10, 2024 |
| Infinix       | ZERO BOOK 13                | Notebook    | [a3c73eb2fd](https://linux-hardware.org/?probe=a3c73eb2fd) | Jan 09, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [1abf742848](https://linux-hardware.org/?probe=1abf742848) | Jan 09, 2024 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [dc1999f5b3](https://linux-hardware.org/?probe=dc1999f5b3) | Jan 09, 2024 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [5d90ffe9df](https://linux-hardware.org/?probe=5d90ffe9df) | Jan 09, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [ce95868b75](https://linux-hardware.org/?probe=ce95868b75) | Jan 09, 2024 |
| Infinix       | INBOOK X3 Slim              | Notebook    | [a62bc72974](https://linux-hardware.org/?probe=a62bc72974) | Jan 09, 2024 |
| HP            | Laptop 14s-dy5xxx           | Notebook    | [f64c72ed00](https://linux-hardware.org/?probe=f64c72ed00) | Jan 09, 2024 |
| Gigabyte      | H370N WIFI-CF               | Desktop     | [2ed3ba8539](https://linux-hardware.org/?probe=2ed3ba8539) | Jan 08, 2024 |
| HP            | ENVY TS 14 Sleekbook        | Notebook    | [48871db703](https://linux-hardware.org/?probe=48871db703) | Jan 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [81d7f1e405](https://linux-hardware.org/?probe=81d7f1e405) | Jan 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1673e31468](https://linux-hardware.org/?probe=1673e31468) | Jan 08, 2024 |
| Dell          | Latitude E6410              | Notebook    | [1260fc62f4](https://linux-hardware.org/?probe=1260fc62f4) | Jan 08, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [fff38da117](https://linux-hardware.org/?probe=fff38da117) | Jan 08, 2024 |
| Dell          | Latitude 5421               | Notebook    | [11ff1eb9a9](https://linux-hardware.org/?probe=11ff1eb9a9) | Jan 08, 2024 |
| Dell          | Vostro 5402                 | Notebook    | [4c1d546ae0](https://linux-hardware.org/?probe=4c1d546ae0) | Jan 08, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [a8bd0e8c75](https://linux-hardware.org/?probe=a8bd0e8c75) | Jan 08, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [132e89ac42](https://linux-hardware.org/?probe=132e89ac42) | Jan 08, 2024 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [c428c1eb3e](https://linux-hardware.org/?probe=c428c1eb3e) | Jan 08, 2024 |
| Lenovo        | IdeaPad 330S-15IKB D 81F... | Notebook    | [2068373a62](https://linux-hardware.org/?probe=2068373a62) | Jan 08, 2024 |
| Infinix       | INBOOK X3 Slim              | Notebook    | [8abae45d8f](https://linux-hardware.org/?probe=8abae45d8f) | Jan 07, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [d640505d97](https://linux-hardware.org/?probe=d640505d97) | Jan 07, 2024 |
| MSI           | Thin GF63 12HW              | Notebook    | [3b5cc98847](https://linux-hardware.org/?probe=3b5cc98847) | Jan 06, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [d922e42e7e](https://linux-hardware.org/?probe=d922e42e7e) | Jan 06, 2024 |
| Lenovo        | ThinkPad X390 20Q1S7RB00    | Notebook    | [cfcb27d0b7](https://linux-hardware.org/?probe=cfcb27d0b7) | Jan 06, 2024 |
| MSI           | Z97 PC Mate                 | Desktop     | [3911439492](https://linux-hardware.org/?probe=3911439492) | Jan 05, 2024 |
| MSI           | Z97 PC Mate                 | Desktop     | [86e4288461](https://linux-hardware.org/?probe=86e4288461) | Jan 05, 2024 |
| Intel         | H61/B75                     | Desktop     | [e44ccc1a76](https://linux-hardware.org/?probe=e44ccc1a76) | Jan 05, 2024 |
| Gigabyte      | B560M H                     | Desktop     | [d7952bcc19](https://linux-hardware.org/?probe=d7952bcc19) | Jan 05, 2024 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [e666d40d0e](https://linux-hardware.org/?probe=e666d40d0e) | Jan 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [7c5e33071f](https://linux-hardware.org/?probe=7c5e33071f) | Jan 04, 2024 |
| Unknown       | V00                         | Mini pc     | [32ca2bbb84](https://linux-hardware.org/?probe=32ca2bbb84) | Jan 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [9ccd4b5019](https://linux-hardware.org/?probe=9ccd4b5019) | Jan 04, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [cafe81526a](https://linux-hardware.org/?probe=cafe81526a) | Jan 04, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [840b965b43](https://linux-hardware.org/?probe=840b965b43) | Jan 04, 2024 |
| Lenovo        | ThinkCentre M71e 3156PT5    | Desktop     | [53089d138d](https://linux-hardware.org/?probe=53089d138d) | Jan 03, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [1f5691daf4](https://linux-hardware.org/?probe=1f5691daf4) | Jan 02, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [71fdca5d43](https://linux-hardware.org/?probe=71fdca5d43) | Jan 02, 2024 |
| Acer          | Nitro AN515-47              | Notebook    | [b53ce5dfb5](https://linux-hardware.org/?probe=b53ce5dfb5) | Jan 02, 2024 |
| HP            | Laptop 14s-dy5xxx           | Notebook    | [4c531fb260](https://linux-hardware.org/?probe=4c531fb260) | Jan 02, 2024 |
| ASUSTek       | K53SV                       | Notebook    | [0cc0c3f5e0](https://linux-hardware.org/?probe=0cc0c3f5e0) | Jan 02, 2024 |
| Google        | Blooguard                   | Notebook    | [dc6c0354a9](https://linux-hardware.org/?probe=dc6c0354a9) | Jan 02, 2024 |
| Acer          | One 14 Z8-415               | Notebook    | [b022baea77](https://linux-hardware.org/?probe=b022baea77) | Jan 01, 2024 |
| Acer          | One 14 Z8-415               | Notebook    | [0e2bbf3d20](https://linux-hardware.org/?probe=0e2bbf3d20) | Jan 01, 2024 |
| Dell          | Vostro 3405                 | Notebook    | [78db308528](https://linux-hardware.org/?probe=78db308528) | Jan 01, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [22ba5950e3](https://linux-hardware.org/?probe=22ba5950e3) | Jan 01, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [dddd9b59bf](https://linux-hardware.org/?probe=dddd9b59bf) | Jan 01, 2024 |
| HP            | Laptop 14s-ef1xxx           | Notebook    | [961d2db618](https://linux-hardware.org/?probe=961d2db618) | Dec 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | Notebook    | [f96a0610cb](https://linux-hardware.org/?probe=f96a0610cb) | Dec 30, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [bee026166f](https://linux-hardware.org/?probe=bee026166f) | Dec 30, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [cfec230076](https://linux-hardware.org/?probe=cfec230076) | Dec 30, 2023 |
| Infinix       | INBOOK X1 NEO               | Notebook    | [71e74b3e03](https://linux-hardware.org/?probe=71e74b3e03) | Dec 30, 2023 |
| Dell          | Latitude E5420              | Notebook    | [0bc1fb2eaf](https://linux-hardware.org/?probe=0bc1fb2eaf) | Dec 30, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [10d9fd3230](https://linux-hardware.org/?probe=10d9fd3230) | Dec 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2490d5b834](https://linux-hardware.org/?probe=2490d5b834) | Dec 30, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [85ac43fbee](https://linux-hardware.org/?probe=85ac43fbee) | Dec 29, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [e527034e74](https://linux-hardware.org/?probe=e527034e74) | Dec 29, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [aee31d728f](https://linux-hardware.org/?probe=aee31d728f) | Dec 29, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [74b6d51ade](https://linux-hardware.org/?probe=74b6d51ade) | Dec 29, 2023 |
| Acer          | Aspire A715-76G             | Notebook    | [e25984fb5e](https://linux-hardware.org/?probe=e25984fb5e) | Dec 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [42c812d36d](https://linux-hardware.org/?probe=42c812d36d) | Dec 29, 2023 |
| Dell          | Precision M6400             | Notebook    | [7ea3fcf3ed](https://linux-hardware.org/?probe=7ea3fcf3ed) | Dec 29, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [493e09fce5](https://linux-hardware.org/?probe=493e09fce5) | Dec 28, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [412a23e374](https://linux-hardware.org/?probe=412a23e374) | Dec 28, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ce26af0483](https://linux-hardware.org/?probe=ce26af0483) | Dec 28, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [6abb72e809](https://linux-hardware.org/?probe=6abb72e809) | Dec 28, 2023 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [6c4e2313d7](https://linux-hardware.org/?probe=6c4e2313d7) | Dec 28, 2023 |
| BY OEM        | B365C5                      | Desktop     | [b1f312c091](https://linux-hardware.org/?probe=b1f312c091) | Dec 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | Notebook    | [1948c445d8](https://linux-hardware.org/?probe=1948c445d8) | Dec 27, 2023 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [30d2bb71e5](https://linux-hardware.org/?probe=30d2bb71e5) | Dec 27, 2023 |
| Dell          | Vostro 3446                 | Notebook    | [ed9d04a3d2](https://linux-hardware.org/?probe=ed9d04a3d2) | Dec 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [cce90b21c6](https://linux-hardware.org/?probe=cce90b21c6) | Dec 27, 2023 |
| HP            | Laptop 14s-dy5xxx           | Notebook    | [de602b4dc6](https://linux-hardware.org/?probe=de602b4dc6) | Dec 27, 2023 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [106af034ae](https://linux-hardware.org/?probe=106af034ae) | Dec 27, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c3b34cdeb4](https://linux-hardware.org/?probe=c3b34cdeb4) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8fae3225fd](https://linux-hardware.org/?probe=8fae3225fd) | Dec 26, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [c436ff8cab](https://linux-hardware.org/?probe=c436ff8cab) | Dec 26, 2023 |
| Lenovo        | ThinkPad L470 20J5S0JM00    | Notebook    | [c8f1140dc5](https://linux-hardware.org/?probe=c8f1140dc5) | Dec 26, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [5972225791](https://linux-hardware.org/?probe=5972225791) | Dec 25, 2023 |
| HP            | 8299                        | Desktop     | [b579f81db7](https://linux-hardware.org/?probe=b579f81db7) | Dec 24, 2023 |
| HP            | 8299                        | Desktop     | [9d48e9f8cb](https://linux-hardware.org/?probe=9d48e9f8cb) | Dec 24, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [f9cf1edcee](https://linux-hardware.org/?probe=f9cf1edcee) | Dec 24, 2023 |
| Dell          | Latitude 3520               | Notebook    | [2bac03be10](https://linux-hardware.org/?probe=2bac03be10) | Dec 24, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [31f29a3843](https://linux-hardware.org/?probe=31f29a3843) | Dec 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [3366f8e90d](https://linux-hardware.org/?probe=3366f8e90d) | Dec 24, 2023 |
| Acer          | H81-M1                      | Desktop     | [e9fd2a5dc4](https://linux-hardware.org/?probe=e9fd2a5dc4) | Dec 23, 2023 |
| HP            | Victus by 15.6 inch Gami... | Notebook    | [b74170ede4](https://linux-hardware.org/?probe=b74170ede4) | Dec 23, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [d36af9d69e](https://linux-hardware.org/?probe=d36af9d69e) | Dec 22, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e42f9ff8f6](https://linux-hardware.org/?probe=e42f9ff8f6) | Dec 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [c7a31a4dab](https://linux-hardware.org/?probe=c7a31a4dab) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [18788fe1ea](https://linux-hardware.org/?probe=18788fe1ea) | Dec 22, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [cdff1cf322](https://linux-hardware.org/?probe=cdff1cf322) | Dec 22, 2023 |
| Acer          | One 14 Z2-493               | Notebook    | [11215309a3](https://linux-hardware.org/?probe=11215309a3) | Dec 22, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [bf0861748d](https://linux-hardware.org/?probe=bf0861748d) | Dec 22, 2023 |
| HP            | Notebook                    | Notebook    | [9010ced489](https://linux-hardware.org/?probe=9010ced489) | Dec 21, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [a2194f1fc6](https://linux-hardware.org/?probe=a2194f1fc6) | Dec 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [ded73c0619](https://linux-hardware.org/?probe=ded73c0619) | Dec 21, 2023 |
| Dell          | Latitude 3410               | Notebook    | [3de48ebce1](https://linux-hardware.org/?probe=3de48ebce1) | Dec 20, 2023 |
| Gigabyte      | H81M-S                      | Desktop     | [5583555782](https://linux-hardware.org/?probe=5583555782) | Dec 20, 2023 |
| Gigabyte      | H81M-S                      | Desktop     | [eded3a5ce4](https://linux-hardware.org/?probe=eded3a5ce4) | Dec 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [675b79ace4](https://linux-hardware.org/?probe=675b79ace4) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [870842c348](https://linux-hardware.org/?probe=870842c348) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c2eacfced7](https://linux-hardware.org/?probe=c2eacfced7) | Dec 20, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [dac9572e21](https://linux-hardware.org/?probe=dac9572e21) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [71bc732b86](https://linux-hardware.org/?probe=71bc732b86) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [5d14b45611](https://linux-hardware.org/?probe=5d14b45611) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [71d03541a9](https://linux-hardware.org/?probe=71d03541a9) | Dec 20, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [28287138f4](https://linux-hardware.org/?probe=28287138f4) | Dec 19, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [308a55288f](https://linux-hardware.org/?probe=308a55288f) | Dec 19, 2023 |
| Dell          | 0NV0M7 A02                  | Desktop     | [577e6d8d0e](https://linux-hardware.org/?probe=577e6d8d0e) | Dec 18, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [5a5f20e49a](https://linux-hardware.org/?probe=5a5f20e49a) | Dec 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7d1b99f3a7](https://linux-hardware.org/?probe=7d1b99f3a7) | Dec 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [19fe61d807](https://linux-hardware.org/?probe=19fe61d807) | Dec 18, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [90856c67e3](https://linux-hardware.org/?probe=90856c67e3) | Dec 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [16902836db](https://linux-hardware.org/?probe=16902836db) | Dec 17, 2023 |
| HP            | 2000                        | Notebook    | [3570eb7cd0](https://linux-hardware.org/?probe=3570eb7cd0) | Dec 17, 2023 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [e3d139cdb3](https://linux-hardware.org/?probe=e3d139cdb3) | Dec 16, 2023 |
| Intel         | H81                         | Desktop     | [9aaa6b2ab6](https://linux-hardware.org/?probe=9aaa6b2ab6) | Dec 16, 2023 |
| HP            | 15                          | Notebook    | [b1de66d4ed](https://linux-hardware.org/?probe=b1de66d4ed) | Dec 16, 2023 |
| Dell          | 0RT6HT A01                  | Desktop     | [3509be8560](https://linux-hardware.org/?probe=3509be8560) | Dec 16, 2023 |
| MSI           | PRO H410M-B                 | Desktop     | [0729c86d23](https://linux-hardware.org/?probe=0729c86d23) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9986fed725](https://linux-hardware.org/?probe=9986fed725) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [4a964fa296](https://linux-hardware.org/?probe=4a964fa296) | Dec 15, 2023 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [b60d191f59](https://linux-hardware.org/?probe=b60d191f59) | Dec 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6689e06c77](https://linux-hardware.org/?probe=6689e06c77) | Dec 15, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [c5e74761c7](https://linux-hardware.org/?probe=c5e74761c7) | Dec 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b653a2fdf8](https://linux-hardware.org/?probe=b653a2fdf8) | Dec 15, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [0728e617a0](https://linux-hardware.org/?probe=0728e617a0) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S0U302    | Notebook    | [163493b62b](https://linux-hardware.org/?probe=163493b62b) | Dec 14, 2023 |
| Acer          | Aspire 1510 Rev.A           | Desktop     | [452be93d1b](https://linux-hardware.org/?probe=452be93d1b) | Dec 13, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [f6f31f5ed6](https://linux-hardware.org/?probe=f6f31f5ed6) | Dec 13, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f79863b604](https://linux-hardware.org/?probe=f79863b604) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [4b88dcf6b3](https://linux-hardware.org/?probe=4b88dcf6b3) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1a63f79d28](https://linux-hardware.org/?probe=1a63f79d28) | Dec 13, 2023 |
| HP            | Pavilion dv6-1152tx (VB6... | Notebook    | [f8a2cfad5f](https://linux-hardware.org/?probe=f8a2cfad5f) | Dec 13, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [9c38707d13](https://linux-hardware.org/?probe=9c38707d13) | Dec 13, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [f837c928be](https://linux-hardware.org/?probe=f837c928be) | Dec 13, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [b718b97eef](https://linux-hardware.org/?probe=b718b97eef) | Dec 12, 2023 |
| HP            | 82DC 1100                   | All in one  | [96f4033f37](https://linux-hardware.org/?probe=96f4033f37) | Dec 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [293fe3fb8e](https://linux-hardware.org/?probe=293fe3fb8e) | Dec 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [c9dd6aebbd](https://linux-hardware.org/?probe=c9dd6aebbd) | Dec 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e5415e7df5](https://linux-hardware.org/?probe=e5415e7df5) | Dec 12, 2023 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [f985ca6bbb](https://linux-hardware.org/?probe=f985ca6bbb) | Dec 12, 2023 |
| Sony          | VPCEH25EN                   | Notebook    | [284401858f](https://linux-hardware.org/?probe=284401858f) | Dec 12, 2023 |
| Lenovo        | Unknown                     | Convertible | [ca130417ca](https://linux-hardware.org/?probe=ca130417ca) | Dec 12, 2023 |
| Acer          | H81-M1                      | Desktop     | [c6f5b1d841](https://linux-hardware.org/?probe=c6f5b1d841) | Dec 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bc96bd94d2](https://linux-hardware.org/?probe=bc96bd94d2) | Dec 11, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [e96af5da4d](https://linux-hardware.org/?probe=e96af5da4d) | Dec 11, 2023 |
| HP            | Laptop 14s-dy5xxx           | Notebook    | [bfe021294b](https://linux-hardware.org/?probe=bfe021294b) | Dec 11, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [bfd1a093c9](https://linux-hardware.org/?probe=bfd1a093c9) | Dec 11, 2023 |
| Dell          | 0J4NFV A01                  | Desktop     | [11207ddb80](https://linux-hardware.org/?probe=11207ddb80) | Dec 11, 2023 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [0b11b5e28f](https://linux-hardware.org/?probe=0b11b5e28f) | Dec 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9ae1729415](https://linux-hardware.org/?probe=9ae1729415) | Dec 10, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a086fa3ad5](https://linux-hardware.org/?probe=a086fa3ad5) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f0bcb0009e](https://linux-hardware.org/?probe=f0bcb0009e) | Dec 09, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [dd7e60da66](https://linux-hardware.org/?probe=dd7e60da66) | Dec 09, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [1ce8dbd527](https://linux-hardware.org/?probe=1ce8dbd527) | Dec 08, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [7082f03269](https://linux-hardware.org/?probe=7082f03269) | Dec 08, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [a696c1d832](https://linux-hardware.org/?probe=a696c1d832) | Dec 08, 2023 |
| Infinix       | INBOOK X3 Slim              | Notebook    | [124c166e5f](https://linux-hardware.org/?probe=124c166e5f) | Dec 08, 2023 |
| Acer          | H81-M1                      | Desktop     | [76ff7a29ae](https://linux-hardware.org/?probe=76ff7a29ae) | Dec 07, 2023 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [71cc90f71e](https://linux-hardware.org/?probe=71cc90f71e) | Dec 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [69fcc32b2c](https://linux-hardware.org/?probe=69fcc32b2c) | Dec 07, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [d1337f45be](https://linux-hardware.org/?probe=d1337f45be) | Dec 06, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [f2a72d7b29](https://linux-hardware.org/?probe=f2a72d7b29) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ed77f35114](https://linux-hardware.org/?probe=ed77f35114) | Dec 06, 2023 |
| Gigabyte      | Z690 UD                     | Desktop     | [d73ebb5e8c](https://linux-hardware.org/?probe=d73ebb5e8c) | Dec 06, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [896cdac0e2](https://linux-hardware.org/?probe=896cdac0e2) | Dec 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [0c0833952d](https://linux-hardware.org/?probe=0c0833952d) | Dec 06, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [aa183c25d7](https://linux-hardware.org/?probe=aa183c25d7) | Dec 06, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [3a07569e5f](https://linux-hardware.org/?probe=3a07569e5f) | Dec 05, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [84dc9cc524](https://linux-hardware.org/?probe=84dc9cc524) | Dec 05, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [54d3b585e6](https://linux-hardware.org/?probe=54d3b585e6) | Dec 05, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [8fbe891429](https://linux-hardware.org/?probe=8fbe891429) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [3306bdcb6c](https://linux-hardware.org/?probe=3306bdcb6c) | Dec 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9535cecf0f](https://linux-hardware.org/?probe=9535cecf0f) | Dec 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [48f3e5b7d8](https://linux-hardware.org/?probe=48f3e5b7d8) | Dec 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0fca0314d6](https://linux-hardware.org/?probe=0fca0314d6) | Dec 05, 2023 |
| Dell          | 02N3WF A03                  | Desktop     | [2974cc160f](https://linux-hardware.org/?probe=2974cc160f) | Dec 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [15b5925773](https://linux-hardware.org/?probe=15b5925773) | Dec 04, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [29d253c1cd](https://linux-hardware.org/?probe=29d253c1cd) | Dec 04, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [d088539ba0](https://linux-hardware.org/?probe=d088539ba0) | Dec 04, 2023 |
| Acer          | Unknown                     | Notebook    | [6555dd06ac](https://linux-hardware.org/?probe=6555dd06ac) | Dec 03, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a12d533400](https://linux-hardware.org/?probe=a12d533400) | Dec 03, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [0612c99f8a](https://linux-hardware.org/?probe=0612c99f8a) | Dec 03, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [69c3f996db](https://linux-hardware.org/?probe=69c3f996db) | Dec 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6c9bc77547](https://linux-hardware.org/?probe=6c9bc77547) | Dec 02, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [0cd9d3d156](https://linux-hardware.org/?probe=0cd9d3d156) | Dec 02, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [26d7ac2396](https://linux-hardware.org/?probe=26d7ac2396) | Dec 02, 2023 |
| Lenovo        | MAHOBAY No DPK              | All in one  | [d97ecb484d](https://linux-hardware.org/?probe=d97ecb484d) | Dec 02, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [e33632af4f](https://linux-hardware.org/?probe=e33632af4f) | Dec 02, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [f86dd8a709](https://linux-hardware.org/?probe=f86dd8a709) | Dec 02, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [6b97c68c9f](https://linux-hardware.org/?probe=6b97c68c9f) | Dec 01, 2023 |
| Dell          | Latitude 5480               | Notebook    | [dca8ec821b](https://linux-hardware.org/?probe=dca8ec821b) | Dec 01, 2023 |
| Lenovo        | K14 G2 IRU 21G1             | Notebook    | [b52ce46b0d](https://linux-hardware.org/?probe=b52ce46b0d) | Dec 01, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [53bc6eba90](https://linux-hardware.org/?probe=53bc6eba90) | Dec 01, 2023 |
| Lenovo        | K14 G2 IRU 21G1             | Notebook    | [22af506155](https://linux-hardware.org/?probe=22af506155) | Dec 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5cfd0eb0f5](https://linux-hardware.org/?probe=5cfd0eb0f5) | Nov 30, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [3e97ecc95d](https://linux-hardware.org/?probe=3e97ecc95d) | Nov 30, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [7c8b100c86](https://linux-hardware.org/?probe=7c8b100c86) | Nov 30, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [bb8295e3fa](https://linux-hardware.org/?probe=bb8295e3fa) | Nov 30, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [0d3ea0a6dc](https://linux-hardware.org/?probe=0d3ea0a6dc) | Nov 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [62b38954c4](https://linux-hardware.org/?probe=62b38954c4) | Nov 30, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [da1096c1ed](https://linux-hardware.org/?probe=da1096c1ed) | Nov 29, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [2f5a407d09](https://linux-hardware.org/?probe=2f5a407d09) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | Notebook    | [f99e3c8556](https://linux-hardware.org/?probe=f99e3c8556) | Nov 28, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [6eb25169c1](https://linux-hardware.org/?probe=6eb25169c1) | Nov 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7c4bb8dad1](https://linux-hardware.org/?probe=7c4bb8dad1) | Nov 28, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [608d264af2](https://linux-hardware.org/?probe=608d264af2) | Nov 27, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [2ecc0c852a](https://linux-hardware.org/?probe=2ecc0c852a) | Nov 27, 2023 |
| Dell          | 0XW3KG A02                  | All in one  | [bfab8a5c50](https://linux-hardware.org/?probe=bfab8a5c50) | Nov 27, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [7d4c7e1af2](https://linux-hardware.org/?probe=7d4c7e1af2) | Nov 27, 2023 |
| HP            | Laptop 15-hr0xxx            | Notebook    | [a2bef1066d](https://linux-hardware.org/?probe=a2bef1066d) | Nov 27, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [3f9a7e29e7](https://linux-hardware.org/?probe=3f9a7e29e7) | Nov 26, 2023 |
| Acer          | Aspire Lite AL15-41         | Notebook    | [1ab369fc06](https://linux-hardware.org/?probe=1ab369fc06) | Nov 26, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [82a4c6642b](https://linux-hardware.org/?probe=82a4c6642b) | Nov 25, 2023 |
| Dell          | 0RT6HT A01                  | Desktop     | [aedd0fa212](https://linux-hardware.org/?probe=aedd0fa212) | Nov 25, 2023 |
| Dell          | Precision M4500             | Notebook    | [c1833bf6b5](https://linux-hardware.org/?probe=c1833bf6b5) | Nov 25, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [409c3e67d2](https://linux-hardware.org/?probe=409c3e67d2) | Nov 25, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1aa46b36ee](https://linux-hardware.org/?probe=1aa46b36ee) | Nov 25, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [9cb8304240](https://linux-hardware.org/?probe=9cb8304240) | Nov 24, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [8cfb18380e](https://linux-hardware.org/?probe=8cfb18380e) | Nov 24, 2023 |
| FUTOPIA GL... | ULTIMUS PRO                 | Notebook    | [96b6b163d8](https://linux-hardware.org/?probe=96b6b163d8) | Nov 24, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [90499ad4f0](https://linux-hardware.org/?probe=90499ad4f0) | Nov 24, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [5bcef78473](https://linux-hardware.org/?probe=5bcef78473) | Nov 24, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [3edc0a53ce](https://linux-hardware.org/?probe=3edc0a53ce) | Nov 24, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [df38b119a1](https://linux-hardware.org/?probe=df38b119a1) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1e5ad7dda0](https://linux-hardware.org/?probe=1e5ad7dda0) | Nov 23, 2023 |
| Acer          | Aspire Lite AL15-52         | Notebook    | [a86c46d6fa](https://linux-hardware.org/?probe=a86c46d6fa) | Nov 23, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [c1d0f0a97d](https://linux-hardware.org/?probe=c1d0f0a97d) | Nov 22, 2023 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [ce96501574](https://linux-hardware.org/?probe=ce96501574) | Nov 22, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [f202c6760e](https://linux-hardware.org/?probe=f202c6760e) | Nov 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [2474e3d0e7](https://linux-hardware.org/?probe=2474e3d0e7) | Nov 21, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [b380bd45bd](https://linux-hardware.org/?probe=b380bd45bd) | Nov 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b12a3ea8d6](https://linux-hardware.org/?probe=b12a3ea8d6) | Nov 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a38bb99384](https://linux-hardware.org/?probe=a38bb99384) | Nov 21, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [7dcf0b28c0](https://linux-hardware.org/?probe=7dcf0b28c0) | Nov 21, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [b312b34d74](https://linux-hardware.org/?probe=b312b34d74) | Nov 20, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [3b72eaca1a](https://linux-hardware.org/?probe=3b72eaca1a) | Nov 20, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [8248b93899](https://linux-hardware.org/?probe=8248b93899) | Nov 20, 2023 |
| HP            | Pavilion 15                 | Notebook    | [7239efa8fe](https://linux-hardware.org/?probe=7239efa8fe) | Nov 20, 2023 |
| HP            | Laptop 15s-fr2xxx           | Notebook    | [fff3e03a74](https://linux-hardware.org/?probe=fff3e03a74) | Nov 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [49139037ec](https://linux-hardware.org/?probe=49139037ec) | Nov 20, 2023 |
| Dell          | Vostro 1310                 | Notebook    | [bd82e2c035](https://linux-hardware.org/?probe=bd82e2c035) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [f118e9b0a7](https://linux-hardware.org/?probe=f118e9b0a7) | Nov 19, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [8901c21f98](https://linux-hardware.org/?probe=8901c21f98) | Nov 19, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [6a9af286f8](https://linux-hardware.org/?probe=6a9af286f8) | Nov 19, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [aec2f789cf](https://linux-hardware.org/?probe=aec2f789cf) | Nov 18, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [3ad49c55c8](https://linux-hardware.org/?probe=3ad49c55c8) | Nov 18, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [92546d4efc](https://linux-hardware.org/?probe=92546d4efc) | Nov 18, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a8b7c376d](https://linux-hardware.org/?probe=4a8b7c376d) | Nov 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [70ca4894ab](https://linux-hardware.org/?probe=70ca4894ab) | Nov 18, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [a02f6c770c](https://linux-hardware.org/?probe=a02f6c770c) | Nov 18, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [54bad5da51](https://linux-hardware.org/?probe=54bad5da51) | Nov 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0f5f7fb08d](https://linux-hardware.org/?probe=0f5f7fb08d) | Nov 16, 2023 |
| HP            | 802E                        | Desktop     | [9046cfa950](https://linux-hardware.org/?probe=9046cfa950) | Nov 16, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [72a6eac951](https://linux-hardware.org/?probe=72a6eac951) | Nov 15, 2023 |
| HP            | Notebook                    | Notebook    | [73567de74e](https://linux-hardware.org/?probe=73567de74e) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [386519f50c](https://linux-hardware.org/?probe=386519f50c) | Nov 15, 2023 |
| HP            | Laptop 15s-fr2xxx           | Notebook    | [be79137b4b](https://linux-hardware.org/?probe=be79137b4b) | Nov 15, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [7df41d6e32](https://linux-hardware.org/?probe=7df41d6e32) | Nov 15, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [bdac7a70aa](https://linux-hardware.org/?probe=bdac7a70aa) | Nov 14, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [087220685a](https://linux-hardware.org/?probe=087220685a) | Nov 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b8e2bf284d](https://linux-hardware.org/?probe=b8e2bf284d) | Nov 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [f3d934ed44](https://linux-hardware.org/?probe=f3d934ed44) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ba805ada14](https://linux-hardware.org/?probe=ba805ada14) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [381c8b164d](https://linux-hardware.org/?probe=381c8b164d) | Nov 13, 2023 |
| Gigabyte      | B650M K                     | Desktop     | [8abd967216](https://linux-hardware.org/?probe=8abd967216) | Nov 13, 2023 |
| HP            | Laptop 15s-fr2xxx           | Notebook    | [f5d3c3e682](https://linux-hardware.org/?probe=f5d3c3e682) | Nov 12, 2023 |
| ASUSTek       | X556UR                      | Notebook    | [c4b344c176](https://linux-hardware.org/?probe=c4b344c176) | Nov 12, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c920563c0b](https://linux-hardware.org/?probe=c920563c0b) | Nov 12, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [bbf00de926](https://linux-hardware.org/?probe=bbf00de926) | Nov 12, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [530c444ea1](https://linux-hardware.org/?probe=530c444ea1) | Nov 12, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [197a03d08f](https://linux-hardware.org/?probe=197a03d08f) | Nov 12, 2023 |
| MSI           | H61M-P20                    | Desktop     | [6b4c00d564](https://linux-hardware.org/?probe=6b4c00d564) | Nov 11, 2023 |
| ZX            | H610ITXG                    | Desktop     | [89891cb41b](https://linux-hardware.org/?probe=89891cb41b) | Nov 11, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [f08c831e30](https://linux-hardware.org/?probe=f08c831e30) | Nov 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [565411e232](https://linux-hardware.org/?probe=565411e232) | Nov 11, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [86d8fabf27](https://linux-hardware.org/?probe=86d8fabf27) | Nov 11, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [26f1a89e53](https://linux-hardware.org/?probe=26f1a89e53) | Nov 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [08c8ac6e4d](https://linux-hardware.org/?probe=08c8ac6e4d) | Nov 09, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [c0e0567705](https://linux-hardware.org/?probe=c0e0567705) | Nov 09, 2023 |
| Lenovo        | ThinkPad X250 20CLAOMLIN    | Notebook    | [88967f98bd](https://linux-hardware.org/?probe=88967f98bd) | Nov 09, 2023 |
| HP            | Notebook                    | Notebook    | [28b2b3c585](https://linux-hardware.org/?probe=28b2b3c585) | Nov 08, 2023 |
| HP            | Notebook                    | Notebook    | [8881671430](https://linux-hardware.org/?probe=8881671430) | Nov 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JLC... | Notebook    | [d44b69e61b](https://linux-hardware.org/?probe=d44b69e61b) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [63e0b9fc88](https://linux-hardware.org/?probe=63e0b9fc88) | Nov 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d566deea22](https://linux-hardware.org/?probe=d566deea22) | Nov 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f8b6335bea](https://linux-hardware.org/?probe=f8b6335bea) | Nov 08, 2023 |
| Intel         | NUC13ANBi3 M89896-203       | Mini pc     | [106f97cc8b](https://linux-hardware.org/?probe=106f97cc8b) | Nov 08, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [79e23fd44a](https://linux-hardware.org/?probe=79e23fd44a) | Nov 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0f5ee4c730](https://linux-hardware.org/?probe=0f5ee4c730) | Nov 07, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [a8a46eb495](https://linux-hardware.org/?probe=a8a46eb495) | Nov 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ea37beb412](https://linux-hardware.org/?probe=ea37beb412) | Nov 05, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c17ad7033c](https://linux-hardware.org/?probe=c17ad7033c) | Nov 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [399dda92eb](https://linux-hardware.org/?probe=399dda92eb) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [49c91b6782](https://linux-hardware.org/?probe=49c91b6782) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [c39cd7480d](https://linux-hardware.org/?probe=c39cd7480d) | Nov 04, 2023 |
| HP            | 15                          | Notebook    | [5d5fb36764](https://linux-hardware.org/?probe=5d5fb36764) | Nov 04, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [ede0c05f18](https://linux-hardware.org/?probe=ede0c05f18) | Nov 04, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [07e66cf3c5](https://linux-hardware.org/?probe=07e66cf3c5) | Nov 04, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [3521a1f918](https://linux-hardware.org/?probe=3521a1f918) | Nov 04, 2023 |
| AVITA         | NS14A2                      | Notebook    | [738e0008ce](https://linux-hardware.org/?probe=738e0008ce) | Nov 04, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [dff06d88c5](https://linux-hardware.org/?probe=dff06d88c5) | Nov 03, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [c4aa915297](https://linux-hardware.org/?probe=c4aa915297) | Nov 03, 2023 |
| Dell          | 0CN7X8 A05                  | Server      | [afe0c7dfbe](https://linux-hardware.org/?probe=afe0c7dfbe) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [bb1da2575d](https://linux-hardware.org/?probe=bb1da2575d) | Nov 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS13J00     | Notebook    | [ebfdc934b7](https://linux-hardware.org/?probe=ebfdc934b7) | Nov 02, 2023 |
| Acer          | Swift SF314-55G             | Notebook    | [fee0e3c809](https://linux-hardware.org/?probe=fee0e3c809) | Nov 02, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [137dba2261](https://linux-hardware.org/?probe=137dba2261) | Nov 02, 2023 |
| HONOR         | BRN-FXX                     | Notebook    | [e4b4501211](https://linux-hardware.org/?probe=e4b4501211) | Nov 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [54516fba78](https://linux-hardware.org/?probe=54516fba78) | Nov 01, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [59e202bef7](https://linux-hardware.org/?probe=59e202bef7) | Nov 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3c04d0213b](https://linux-hardware.org/?probe=3c04d0213b) | Nov 01, 2023 |
| Gigabyte      | A520M K V2                  | Desktop     | [10670f1068](https://linux-hardware.org/?probe=10670f1068) | Nov 01, 2023 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [9031850aa0](https://linux-hardware.org/?probe=9031850aa0) | Nov 01, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [70e4b3b007](https://linux-hardware.org/?probe=70e4b3b007) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [352bf34e3b](https://linux-hardware.org/?probe=352bf34e3b) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [2e35f866e3](https://linux-hardware.org/?probe=2e35f866e3) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 20RAS13J00     | Notebook    | [91a0aacae9](https://linux-hardware.org/?probe=91a0aacae9) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [ebec8d6fd1](https://linux-hardware.org/?probe=ebec8d6fd1) | Oct 31, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d9da25aaae](https://linux-hardware.org/?probe=d9da25aaae) | Oct 31, 2023 |
| Acer          | One 14 Z8-415               | Notebook    | [e3b7fce5f3](https://linux-hardware.org/?probe=e3b7fce5f3) | Oct 31, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [069872b404](https://linux-hardware.org/?probe=069872b404) | Oct 31, 2023 |
| Chuwi         | CoreBook                    | Notebook    | [71b0d03991](https://linux-hardware.org/?probe=71b0d03991) | Oct 30, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [7ffe987b92](https://linux-hardware.org/?probe=7ffe987b92) | Oct 30, 2023 |
| Intel         | H81                         | Desktop     | [2e37259d45](https://linux-hardware.org/?probe=2e37259d45) | Oct 29, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [4e093f6544](https://linux-hardware.org/?probe=4e093f6544) | Oct 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [1b0a34d774](https://linux-hardware.org/?probe=1b0a34d774) | Oct 29, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [be3a00001c](https://linux-hardware.org/?probe=be3a00001c) | Oct 29, 2023 |
| HP            | 15                          | Notebook    | [cda635d432](https://linux-hardware.org/?probe=cda635d432) | Oct 28, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ecc6e8d906](https://linux-hardware.org/?probe=ecc6e8d906) | Oct 28, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [ce321700bc](https://linux-hardware.org/?probe=ce321700bc) | Oct 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c25324c2a2](https://linux-hardware.org/?probe=c25324c2a2) | Oct 28, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [8157e9bd12](https://linux-hardware.org/?probe=8157e9bd12) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [49982fda5c](https://linux-hardware.org/?probe=49982fda5c) | Oct 28, 2023 |
| HCL Infosy... | HCL ME Laptop               | Notebook    | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [44b772393d](https://linux-hardware.org/?probe=44b772393d) | Oct 27, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [66cfbcd057](https://linux-hardware.org/?probe=66cfbcd057) | Oct 26, 2023 |
| ECS           | H81H3-M3S                   | Desktop     | [6f4c530a93](https://linux-hardware.org/?probe=6f4c530a93) | Oct 26, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [f3407cd11d](https://linux-hardware.org/?probe=f3407cd11d) | Oct 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | Notebook    | [0ed2bd399f](https://linux-hardware.org/?probe=0ed2bd399f) | Oct 25, 2023 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [03333fbe23](https://linux-hardware.org/?probe=03333fbe23) | Oct 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [358936d398](https://linux-hardware.org/?probe=358936d398) | Oct 25, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [71a22f4706](https://linux-hardware.org/?probe=71a22f4706) | Oct 25, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9246bb9a28](https://linux-hardware.org/?probe=9246bb9a28) | Oct 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [ecde45a506](https://linux-hardware.org/?probe=ecde45a506) | Oct 24, 2023 |
| Google        | Teemo                       | Desktop     | [ae5140ac26](https://linux-hardware.org/?probe=ae5140ac26) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | Notebook    | [0f08eb340b](https://linux-hardware.org/?probe=0f08eb340b) | Oct 24, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [332b714861](https://linux-hardware.org/?probe=332b714861) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [673f62810a](https://linux-hardware.org/?probe=673f62810a) | Oct 23, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5a23f97862](https://linux-hardware.org/?probe=5a23f97862) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cf347b4567](https://linux-hardware.org/?probe=cf347b4567) | Oct 23, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [470eb40837](https://linux-hardware.org/?probe=470eb40837) | Oct 23, 2023 |
| HP            | Laptop 14s-dy5xxx           | Notebook    | [e873e5d24c](https://linux-hardware.org/?probe=e873e5d24c) | Oct 23, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | Notebook    | [399c501d43](https://linux-hardware.org/?probe=399c501d43) | Oct 23, 2023 |
| ASUSTek       | GL553VE                     | Notebook    | [9cb6cb4f5b](https://linux-hardware.org/?probe=9cb6cb4f5b) | Oct 22, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [f6831bde3b](https://linux-hardware.org/?probe=f6831bde3b) | Oct 22, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 Ua 82F... | Notebook    | [735bb309a1](https://linux-hardware.org/?probe=735bb309a1) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [f204c7469c](https://linux-hardware.org/?probe=f204c7469c) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [5f376e3415](https://linux-hardware.org/?probe=5f376e3415) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [97d1264314](https://linux-hardware.org/?probe=97d1264314) | Oct 21, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [422e70640a](https://linux-hardware.org/?probe=422e70640a) | Oct 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [76632b6a09](https://linux-hardware.org/?probe=76632b6a09) | Oct 21, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [b762dc0df0](https://linux-hardware.org/?probe=b762dc0df0) | Oct 20, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [cc2f4a6fce](https://linux-hardware.org/?probe=cc2f4a6fce) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [ee44c25ed9](https://linux-hardware.org/?probe=ee44c25ed9) | Oct 20, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [4e0af93a94](https://linux-hardware.org/?probe=4e0af93a94) | Oct 20, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [137f87e169](https://linux-hardware.org/?probe=137f87e169) | Oct 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a7dbe29bbe](https://linux-hardware.org/?probe=a7dbe29bbe) | Oct 19, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [0c6accd4fc](https://linux-hardware.org/?probe=0c6accd4fc) | Oct 19, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [c05a67e739](https://linux-hardware.org/?probe=c05a67e739) | Oct 19, 2023 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [9ad763d3a1](https://linux-hardware.org/?probe=9ad763d3a1) | Oct 18, 2023 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [5064906065](https://linux-hardware.org/?probe=5064906065) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [e7787b05fe](https://linux-hardware.org/?probe=e7787b05fe) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [57dbbcb9f3](https://linux-hardware.org/?probe=57dbbcb9f3) | Oct 18, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [8fb05c37a8](https://linux-hardware.org/?probe=8fb05c37a8) | Oct 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8543bed1b3](https://linux-hardware.org/?probe=8543bed1b3) | Oct 17, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [91d1297632](https://linux-hardware.org/?probe=91d1297632) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [c3bd837d33](https://linux-hardware.org/?probe=c3bd837d33) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | Notebook    | [72e348d9bb](https://linux-hardware.org/?probe=72e348d9bb) | Oct 17, 2023 |
| Intel         | DH77KC AAG39641-401         | Desktop     | [abfbdc1640](https://linux-hardware.org/?probe=abfbdc1640) | Oct 17, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [03670e3e53](https://linux-hardware.org/?probe=03670e3e53) | Oct 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [73e2838408](https://linux-hardware.org/?probe=73e2838408) | Oct 16, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [83cb446c19](https://linux-hardware.org/?probe=83cb446c19) | Oct 16, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3d308e7bb0](https://linux-hardware.org/?probe=3d308e7bb0) | Oct 16, 2023 |
| Gigabyte      | GA-78LMT-S2 R2              | Desktop     | [038f59eb24](https://linux-hardware.org/?probe=038f59eb24) | Oct 15, 2023 |
| Dell          | Latitude 5591               | Notebook    | [ef0287bbad](https://linux-hardware.org/?probe=ef0287bbad) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [7a732e8a25](https://linux-hardware.org/?probe=7a732e8a25) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [73f73df16b](https://linux-hardware.org/?probe=73f73df16b) | Oct 14, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [b63b919a75](https://linux-hardware.org/?probe=b63b919a75) | Oct 14, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [4ddde9e92e](https://linux-hardware.org/?probe=4ddde9e92e) | Oct 13, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [e66e176aac](https://linux-hardware.org/?probe=e66e176aac) | Oct 13, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [92726caa44](https://linux-hardware.org/?probe=92726caa44) | Oct 12, 2023 |
| Infinix       | ZERO BOOK 13                | Notebook    | [c20c04a240](https://linux-hardware.org/?probe=c20c04a240) | Oct 12, 2023 |
| Acer          | Swift SF315-41              | Notebook    | [804f28fe5b](https://linux-hardware.org/?probe=804f28fe5b) | Oct 12, 2023 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [9ca6bc0b08](https://linux-hardware.org/?probe=9ca6bc0b08) | Oct 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [941644a3ed](https://linux-hardware.org/?probe=941644a3ed) | Oct 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [605fcbffe8](https://linux-hardware.org/?probe=605fcbffe8) | Oct 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [7aeb935c28](https://linux-hardware.org/?probe=7aeb935c28) | Oct 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [427ca84f59](https://linux-hardware.org/?probe=427ca84f59) | Oct 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a0e076c7f3](https://linux-hardware.org/?probe=a0e076c7f3) | Oct 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [7d7f268cec](https://linux-hardware.org/?probe=7d7f268cec) | Oct 11, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [767f2c26e0](https://linux-hardware.org/?probe=767f2c26e0) | Oct 10, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [50682769d9](https://linux-hardware.org/?probe=50682769d9) | Oct 10, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [2bc390851d](https://linux-hardware.org/?probe=2bc390851d) | Oct 10, 2023 |
| Gigabyte      | H81M-S                      | Desktop     | [9799f9f959](https://linux-hardware.org/?probe=9799f9f959) | Oct 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [640744cc70](https://linux-hardware.org/?probe=640744cc70) | Oct 10, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [5d606c8b1c](https://linux-hardware.org/?probe=5d606c8b1c) | Oct 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [601fd070ec](https://linux-hardware.org/?probe=601fd070ec) | Oct 10, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [265a8e5346](https://linux-hardware.org/?probe=265a8e5346) | Oct 09, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [dd44b0dc9e](https://linux-hardware.org/?probe=dd44b0dc9e) | Oct 08, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [d8cf994cfe](https://linux-hardware.org/?probe=d8cf994cfe) | Oct 08, 2023 |
| Dell          | Vostro 1450                 | Notebook    | [55334a897d](https://linux-hardware.org/?probe=55334a897d) | Oct 08, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [5f69a24978](https://linux-hardware.org/?probe=5f69a24978) | Oct 08, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [36d48fe6f7](https://linux-hardware.org/?probe=36d48fe6f7) | Oct 07, 2023 |
| Intel         | H61                         | Desktop     | [a37805d0d3](https://linux-hardware.org/?probe=a37805d0d3) | Oct 07, 2023 |
| HP            | Laptop 15s-fr2xxx           | Notebook    | [2dc2d438ea](https://linux-hardware.org/?probe=2dc2d438ea) | Oct 07, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [8619f7e43e](https://linux-hardware.org/?probe=8619f7e43e) | Oct 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [0a18c0ff5d](https://linux-hardware.org/?probe=0a18c0ff5d) | Oct 06, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [425aa2b0f7](https://linux-hardware.org/?probe=425aa2b0f7) | Oct 05, 2023 |
| HP            | 198E                        | Desktop     | [a586865b3d](https://linux-hardware.org/?probe=a586865b3d) | Oct 05, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ddadccf492](https://linux-hardware.org/?probe=ddadccf492) | Oct 05, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [1729f3bfbe](https://linux-hardware.org/?probe=1729f3bfbe) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ee95e8f5fd](https://linux-hardware.org/?probe=ee95e8f5fd) | Oct 05, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [0cf58ae6b1](https://linux-hardware.org/?probe=0cf58ae6b1) | Oct 05, 2023 |
| Sony          | VPCEB16FG                   | Notebook    | [9e655187a5](https://linux-hardware.org/?probe=9e655187a5) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [bdf9fff544](https://linux-hardware.org/?probe=bdf9fff544) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS06E00     | Notebook    | [549cad8b4f](https://linux-hardware.org/?probe=549cad8b4f) | Oct 05, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ccd7cf5f34](https://linux-hardware.org/?probe=ccd7cf5f34) | Oct 05, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [3639fedec4](https://linux-hardware.org/?probe=3639fedec4) | Oct 04, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [eebbbc30b8](https://linux-hardware.org/?probe=eebbbc30b8) | Oct 03, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [f332024d38](https://linux-hardware.org/?probe=f332024d38) | Oct 03, 2023 |
| Dell          | Latitude 7400               | Notebook    | [bd6eee3b51](https://linux-hardware.org/?probe=bd6eee3b51) | Oct 03, 2023 |
| Acer          | Aspire A314-36M             | Notebook    | [5276b99f12](https://linux-hardware.org/?probe=5276b99f12) | Oct 03, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [8a780dd81c](https://linux-hardware.org/?probe=8a780dd81c) | Oct 02, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [160d49a81f](https://linux-hardware.org/?probe=160d49a81f) | Oct 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [445e604c2e](https://linux-hardware.org/?probe=445e604c2e) | Oct 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4e0bb2d740](https://linux-hardware.org/?probe=4e0bb2d740) | Oct 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [840bfbb2cb](https://linux-hardware.org/?probe=840bfbb2cb) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [81027151d1](https://linux-hardware.org/?probe=81027151d1) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f9a210173c](https://linux-hardware.org/?probe=f9a210173c) | Oct 01, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [1df2dc7261](https://linux-hardware.org/?probe=1df2dc7261) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| Pegatron      | Eureka3                     | Desktop     | [e5c7ff0c70](https://linux-hardware.org/?probe=e5c7ff0c70) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [1c4b1aa68d](https://linux-hardware.org/?probe=1c4b1aa68d) | Sep 30, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4074a9c221](https://linux-hardware.org/?probe=4074a9c221) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [988f015a89](https://linux-hardware.org/?probe=988f015a89) | Sep 30, 2023 |
| Acer          | Aspire SW3-016              | Notebook    | [62c3855aa7](https://linux-hardware.org/?probe=62c3855aa7) | Sep 30, 2023 |
| Lenovo        | H410                        | Desktop     | [f49a6ce32f](https://linux-hardware.org/?probe=f49a6ce32f) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [356b5f053d](https://linux-hardware.org/?probe=356b5f053d) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0c9b2c687a](https://linux-hardware.org/?probe=0c9b2c687a) | Sep 28, 2023 |
| HP            | Notebook                    | Notebook    | [7d55fd8520](https://linux-hardware.org/?probe=7d55fd8520) | Sep 28, 2023 |
| HP            | Notebook                    | Notebook    | [49192b29a6](https://linux-hardware.org/?probe=49192b29a6) | Sep 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d53c8ae481](https://linux-hardware.org/?probe=d53c8ae481) | Sep 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [001d5aa716](https://linux-hardware.org/?probe=001d5aa716) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c5c6c5233a](https://linux-hardware.org/?probe=c5c6c5233a) | Sep 27, 2023 |
| Dell          | Latitude 3410               | Notebook    | [7b326dd690](https://linux-hardware.org/?probe=7b326dd690) | Sep 27, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [167d2e893e](https://linux-hardware.org/?probe=167d2e893e) | Sep 27, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [afdb68ccfe](https://linux-hardware.org/?probe=afdb68ccfe) | Sep 26, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [d6982725f2](https://linux-hardware.org/?probe=d6982725f2) | Sep 26, 2023 |
| Infinix       | INBOOK Y1 PLUS NEO          | Notebook    | [30998449af](https://linux-hardware.org/?probe=30998449af) | Sep 26, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [cc34f92566](https://linux-hardware.org/?probe=cc34f92566) | Sep 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [17bb721483](https://linux-hardware.org/?probe=17bb721483) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [14766bbd15](https://linux-hardware.org/?probe=14766bbd15) | Sep 26, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [ccdfae441b](https://linux-hardware.org/?probe=ccdfae441b) | Sep 26, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [94ce4b6306](https://linux-hardware.org/?probe=94ce4b6306) | Sep 25, 2023 |
| Lenovo        | B480 20140                  | Notebook    | [960fe0be2b](https://linux-hardware.org/?probe=960fe0be2b) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9de1c7395f](https://linux-hardware.org/?probe=9de1c7395f) | Sep 25, 2023 |
| Infinix       | INBOOK X1 SLIM              | Notebook    | [bd6f358c7f](https://linux-hardware.org/?probe=bd6f358c7f) | Sep 25, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [7ff4162cbb](https://linux-hardware.org/?probe=7ff4162cbb) | Sep 25, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [55f54a0aeb](https://linux-hardware.org/?probe=55f54a0aeb) | Sep 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b69f53c8fe](https://linux-hardware.org/?probe=b69f53c8fe) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a7eb798aed](https://linux-hardware.org/?probe=a7eb798aed) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [ac45698051](https://linux-hardware.org/?probe=ac45698051) | Sep 25, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [b42e3e4395](https://linux-hardware.org/?probe=b42e3e4395) | Sep 24, 2023 |
| ASRock        | B150M Pro4/Hyper            | Desktop     | [6bd5055b96](https://linux-hardware.org/?probe=6bd5055b96) | Sep 24, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [fe5f9ad018](https://linux-hardware.org/?probe=fe5f9ad018) | Sep 23, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [4e91084325](https://linux-hardware.org/?probe=4e91084325) | Sep 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [f6369d0be5](https://linux-hardware.org/?probe=f6369d0be5) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| Samsung       | 935XDB                      | Notebook    | [a0672b9726](https://linux-hardware.org/?probe=a0672b9726) | Sep 23, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [674c086aa5](https://linux-hardware.org/?probe=674c086aa5) | Sep 22, 2023 |
| HP            | 834F                        | Desktop     | [b69b667f2c](https://linux-hardware.org/?probe=b69b667f2c) | Sep 22, 2023 |
| Getac         | T800G2                      | Tablet      | [fe815f3c1f](https://linux-hardware.org/?probe=fe815f3c1f) | Sep 22, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [67ac6fc0d9](https://linux-hardware.org/?probe=67ac6fc0d9) | Sep 22, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [519a567ecb](https://linux-hardware.org/?probe=519a567ecb) | Sep 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [fc49b16c1c](https://linux-hardware.org/?probe=fc49b16c1c) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c00e994c2c](https://linux-hardware.org/?probe=c00e994c2c) | Sep 21, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [874c33c481](https://linux-hardware.org/?probe=874c33c481) | Sep 21, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [af7ac2b917](https://linux-hardware.org/?probe=af7ac2b917) | Sep 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [a085f48523](https://linux-hardware.org/?probe=a085f48523) | Sep 20, 2023 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [0c99fa225e](https://linux-hardware.org/?probe=0c99fa225e) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | Desktop     | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [f01ce05b1f](https://linux-hardware.org/?probe=f01ce05b1f) | Sep 20, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [9b576274e4](https://linux-hardware.org/?probe=9b576274e4) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [1850488dd1](https://linux-hardware.org/?probe=1850488dd1) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [c122be4331](https://linux-hardware.org/?probe=c122be4331) | Sep 20, 2023 |
| Intel         | DZ68PL AAG42750-301         | Desktop     | [c16c7202a1](https://linux-hardware.org/?probe=c16c7202a1) | Sep 20, 2023 |
| Intel         | H61                         | Desktop     | [82a94f86d2](https://linux-hardware.org/?probe=82a94f86d2) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [00c6b8cced](https://linux-hardware.org/?probe=00c6b8cced) | Sep 20, 2023 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [6ded2501bf](https://linux-hardware.org/?probe=6ded2501bf) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [052438c7dd](https://linux-hardware.org/?probe=052438c7dd) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [a87ec029ab](https://linux-hardware.org/?probe=a87ec029ab) | Sep 19, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6784f50f9d](https://linux-hardware.org/?probe=6784f50f9d) | Sep 19, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6233a0f825](https://linux-hardware.org/?probe=6233a0f825) | Sep 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [aeffbe0fe5](https://linux-hardware.org/?probe=aeffbe0fe5) | Sep 19, 2023 |
| HP            | Notebook                    | Notebook    | [3c10ef5d72](https://linux-hardware.org/?probe=3c10ef5d72) | Sep 19, 2023 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [da930461ec](https://linux-hardware.org/?probe=da930461ec) | Sep 18, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a64dc1766a](https://linux-hardware.org/?probe=a64dc1766a) | Sep 18, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [39a50dc7e8](https://linux-hardware.org/?probe=39a50dc7e8) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cad09f007e](https://linux-hardware.org/?probe=cad09f007e) | Sep 18, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [f6a841ea3d](https://linux-hardware.org/?probe=f6a841ea3d) | Sep 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5b5eb2a0a5](https://linux-hardware.org/?probe=5b5eb2a0a5) | Sep 18, 2023 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [0460fafb99](https://linux-hardware.org/?probe=0460fafb99) | Sep 17, 2023 |
| Dell          | XPS L501X                   | Notebook    | [13d0075027](https://linux-hardware.org/?probe=13d0075027) | Sep 16, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [06e2986bbc](https://linux-hardware.org/?probe=06e2986bbc) | Sep 16, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [506d025e1e](https://linux-hardware.org/?probe=506d025e1e) | Sep 15, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [1c5a009557](https://linux-hardware.org/?probe=1c5a009557) | Sep 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8df91a5efc](https://linux-hardware.org/?probe=8df91a5efc) | Sep 15, 2023 |
| HP            | ENVY 15                     | Notebook    | [c5c9db023b](https://linux-hardware.org/?probe=c5c9db023b) | Sep 15, 2023 |
| HP            | ENVY 15                     | Notebook    | [9741cff4ca](https://linux-hardware.org/?probe=9741cff4ca) | Sep 15, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [71a6a04c4c](https://linux-hardware.org/?probe=71a6a04c4c) | Sep 15, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [bb4b6fe52f](https://linux-hardware.org/?probe=bb4b6fe52f) | Sep 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [37e1d06001](https://linux-hardware.org/?probe=37e1d06001) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [b30ec0e0a8](https://linux-hardware.org/?probe=b30ec0e0a8) | Sep 14, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [e1a54edbdc](https://linux-hardware.org/?probe=e1a54edbdc) | Sep 14, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [160685ce41](https://linux-hardware.org/?probe=160685ce41) | Sep 14, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [79e6e5fc48](https://linux-hardware.org/?probe=79e6e5fc48) | Sep 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1703cfdd5e](https://linux-hardware.org/?probe=1703cfdd5e) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e8b1e251a3](https://linux-hardware.org/?probe=e8b1e251a3) | Sep 13, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [deb3ba5bf7](https://linux-hardware.org/?probe=deb3ba5bf7) | Sep 13, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [23ded25239](https://linux-hardware.org/?probe=23ded25239) | Sep 12, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [c2b009d544](https://linux-hardware.org/?probe=c2b009d544) | Sep 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [ecc13f9294](https://linux-hardware.org/?probe=ecc13f9294) | Sep 12, 2023 |
| Lenovo        | IDEA 315-15 81WE            | Notebook    | [f148c9218a](https://linux-hardware.org/?probe=f148c9218a) | Sep 12, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [005f0b4e53](https://linux-hardware.org/?probe=005f0b4e53) | Sep 11, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [aabd401f54](https://linux-hardware.org/?probe=aabd401f54) | Sep 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [eb75d89868](https://linux-hardware.org/?probe=eb75d89868) | Sep 11, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [bffb256730](https://linux-hardware.org/?probe=bffb256730) | Sep 11, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [2088909e8a](https://linux-hardware.org/?probe=2088909e8a) | Sep 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [16b6bd1d3d](https://linux-hardware.org/?probe=16b6bd1d3d) | Sep 09, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [25649c8a92](https://linux-hardware.org/?probe=25649c8a92) | Sep 09, 2023 |
| Dell          | Latitude E6430              | Notebook    | [0ace4858e1](https://linux-hardware.org/?probe=0ace4858e1) | Sep 09, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [bdd270eddd](https://linux-hardware.org/?probe=bdd270eddd) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [f08f8e5ce8](https://linux-hardware.org/?probe=f08f8e5ce8) | Sep 09, 2023 |
| HP            | Laptop 15s-fr1xxx           | Notebook    | [a6e3c47b2d](https://linux-hardware.org/?probe=a6e3c47b2d) | Sep 08, 2023 |
| Intel         | H81                         | Desktop     | [52fa5b7a15](https://linux-hardware.org/?probe=52fa5b7a15) | Sep 08, 2023 |
| Gateway       | NE56R                       | Notebook    | [ec2415b16d](https://linux-hardware.org/?probe=ec2415b16d) | Sep 08, 2023 |
| Gateway       | NE56R                       | Notebook    | [4871fca687](https://linux-hardware.org/?probe=4871fca687) | Sep 08, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [8ebe24476b](https://linux-hardware.org/?probe=8ebe24476b) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [fd7e472e9b](https://linux-hardware.org/?probe=fd7e472e9b) | Sep 07, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [a2fab791b4](https://linux-hardware.org/?probe=a2fab791b4) | Sep 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [003d136012](https://linux-hardware.org/?probe=003d136012) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [24eca3030c](https://linux-hardware.org/?probe=24eca3030c) | Sep 07, 2023 |
| Dell          | Latitude 3520               | Notebook    | [0fa236983e](https://linux-hardware.org/?probe=0fa236983e) | Sep 06, 2023 |
| Dell          | 0KP561                      | Desktop     | [90055b146d](https://linux-hardware.org/?probe=90055b146d) | Sep 06, 2023 |
| Intel         | H81                         | Desktop     | [5a16cea30a](https://linux-hardware.org/?probe=5a16cea30a) | Sep 06, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| Gateway       | NE56R                       | Notebook    | [ade8432ca6](https://linux-hardware.org/?probe=ade8432ca6) | Sep 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b1f7a8316d](https://linux-hardware.org/?probe=b1f7a8316d) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [586f1d2fa7](https://linux-hardware.org/?probe=586f1d2fa7) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4ed976d4ba](https://linux-hardware.org/?probe=4ed976d4ba) | Sep 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [79328b47d8](https://linux-hardware.org/?probe=79328b47d8) | Sep 05, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [bb7f6aed1a](https://linux-hardware.org/?probe=bb7f6aed1a) | Sep 05, 2023 |
| Gateway       | NE56R                       | Notebook    | [be83386f4d](https://linux-hardware.org/?probe=be83386f4d) | Sep 05, 2023 |
| Intel         | H61                         | Desktop     | [d749d1595f](https://linux-hardware.org/?probe=d749d1595f) | Sep 05, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [613e4acc75](https://linux-hardware.org/?probe=613e4acc75) | Sep 05, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [7c5a59da7b](https://linux-hardware.org/?probe=7c5a59da7b) | Sep 05, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [b595dd4436](https://linux-hardware.org/?probe=b595dd4436) | Sep 05, 2023 |
| HONOR         | BRN-FXX                     | Notebook    | [381e87228c](https://linux-hardware.org/?probe=381e87228c) | Sep 04, 2023 |
| Gateway       | NE56R                       | Notebook    | [99b1c83e93](https://linux-hardware.org/?probe=99b1c83e93) | Sep 04, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [f7a6b9d479](https://linux-hardware.org/?probe=f7a6b9d479) | Sep 04, 2023 |
| HP            | 247 G8 Notebook PC          | Notebook    | [74a7d9e304](https://linux-hardware.org/?probe=74a7d9e304) | Sep 04, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [188a672b4d](https://linux-hardware.org/?probe=188a672b4d) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [7b776b30bd](https://linux-hardware.org/?probe=7b776b30bd) | Sep 03, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [733f5cb987](https://linux-hardware.org/?probe=733f5cb987) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [e0b3a3a55b](https://linux-hardware.org/?probe=e0b3a3a55b) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [69b91f1c46](https://linux-hardware.org/?probe=69b91f1c46) | Sep 03, 2023 |
| HP            | Pavilion dv4                | Notebook    | [8d183fb271](https://linux-hardware.org/?probe=8d183fb271) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [a2aebc52bd](https://linux-hardware.org/?probe=a2aebc52bd) | Sep 03, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | Notebook    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [05c90f0109](https://linux-hardware.org/?probe=05c90f0109) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [2c9f663c14](https://linux-hardware.org/?probe=2c9f663c14) | Sep 01, 2023 |
| HP            | Pavilion g6                 | Notebook    | [0f0960322d](https://linux-hardware.org/?probe=0f0960322d) | Sep 01, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [7d3823ff94](https://linux-hardware.org/?probe=7d3823ff94) | Sep 01, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [ec5d9509f6](https://linux-hardware.org/?probe=ec5d9509f6) | Sep 01, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [929ae155ea](https://linux-hardware.org/?probe=929ae155ea) | Sep 01, 2023 |
| Dell          | Latitude 5400               | Notebook    | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Unknown       | H110M2                      | Desktop     | [bff031410a](https://linux-hardware.org/?probe=bff031410a) | Aug 31, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [3411b788bc](https://linux-hardware.org/?probe=3411b788bc) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [c3d8f5daca](https://linux-hardware.org/?probe=c3d8f5daca) | Aug 31, 2023 |
| HP            | 339A                        | Desktop     | [6c323fe4d4](https://linux-hardware.org/?probe=6c323fe4d4) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [f94ed7f5d1](https://linux-hardware.org/?probe=f94ed7f5d1) | Aug 31, 2023 |
| HP            | 15                          | Notebook    | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| MSI           | Thin GF63 12VE              | Notebook    | [0615d252af](https://linux-hardware.org/?probe=0615d252af) | Aug 31, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8adf70b56e](https://linux-hardware.org/?probe=8adf70b56e) | Aug 31, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [f69425a68d](https://linux-hardware.org/?probe=f69425a68d) | Aug 30, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [4bedf20d35](https://linux-hardware.org/?probe=4bedf20d35) | Aug 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [78e163bc13](https://linux-hardware.org/?probe=78e163bc13) | Aug 30, 2023 |
| OEM           | Intel H81                   | Desktop     | [7d179cb8e9](https://linux-hardware.org/?probe=7d179cb8e9) | Aug 30, 2023 |
| Acer          | One Z1402                   | Notebook    | [2e917719ec](https://linux-hardware.org/?probe=2e917719ec) | Aug 29, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [6e4b12a41e](https://linux-hardware.org/?probe=6e4b12a41e) | Aug 29, 2023 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [93fd8245ab](https://linux-hardware.org/?probe=93fd8245ab) | Aug 29, 2023 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [fafc374d46](https://linux-hardware.org/?probe=fafc374d46) | Aug 29, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [9d092039d3](https://linux-hardware.org/?probe=9d092039d3) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | Notebook    | [8a7f22304b](https://linux-hardware.org/?probe=8a7f22304b) | Aug 29, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [65f52f1180](https://linux-hardware.org/?probe=65f52f1180) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | Notebook    | [598458b278](https://linux-hardware.org/?probe=598458b278) | Aug 28, 2023 |
| Intel         | H61                         | Desktop     | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [15b81ebfc0](https://linux-hardware.org/?probe=15b81ebfc0) | Aug 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a762e96941](https://linux-hardware.org/?probe=a762e96941) | Aug 28, 2023 |
| Dell          | Inspiron 5542               | Notebook    | [70fbf53140](https://linux-hardware.org/?probe=70fbf53140) | Aug 27, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [79c52635ec](https://linux-hardware.org/?probe=79c52635ec) | Aug 27, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [08f577f854](https://linux-hardware.org/?probe=08f577f854) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [fe02fb8d64](https://linux-hardware.org/?probe=fe02fb8d64) | Aug 27, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [3b5476180b](https://linux-hardware.org/?probe=3b5476180b) | Aug 26, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [1a1924897a](https://linux-hardware.org/?probe=1a1924897a) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [04426b4b83](https://linux-hardware.org/?probe=04426b4b83) | Aug 25, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [25c5011587](https://linux-hardware.org/?probe=25c5011587) | Aug 25, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [1fde0105bf](https://linux-hardware.org/?probe=1fde0105bf) | Aug 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3f37fa5636](https://linux-hardware.org/?probe=3f37fa5636) | Aug 25, 2023 |
| Dell          | Inspiron N5050              | Notebook    | [4d282e98b2](https://linux-hardware.org/?probe=4d282e98b2) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [c63d6cfab0](https://linux-hardware.org/?probe=c63d6cfab0) | Aug 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5bddf6d37d](https://linux-hardware.org/?probe=5bddf6d37d) | Aug 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38573350a3](https://linux-hardware.org/?probe=38573350a3) | Aug 23, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [61cb58f13b](https://linux-hardware.org/?probe=61cb58f13b) | Aug 23, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [6c4e1108c1](https://linux-hardware.org/?probe=6c4e1108c1) | Aug 23, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [c8cc960675](https://linux-hardware.org/?probe=c8cc960675) | Aug 21, 2023 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [c16bd959dc](https://linux-hardware.org/?probe=c16bd959dc) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0b0926bb45](https://linux-hardware.org/?probe=0b0926bb45) | Aug 21, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [b5b7a6d8f8](https://linux-hardware.org/?probe=b5b7a6d8f8) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| ASUSTek       | ROG Strix G712LU            | Notebook    | [7fd51c6d4d](https://linux-hardware.org/?probe=7fd51c6d4d) | Aug 20, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [b50e7eb542](https://linux-hardware.org/?probe=b50e7eb542) | Aug 20, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [6d8baa3226](https://linux-hardware.org/?probe=6d8baa3226) | Aug 20, 2023 |
| ASRockRack    | EP2C612D16C-4L              | Desktop     | [61802adf5b](https://linux-hardware.org/?probe=61802adf5b) | Aug 19, 2023 |
| ASRockRack    | EP2C612D16C-4L              | Desktop     | [52d818cdbd](https://linux-hardware.org/?probe=52d818cdbd) | Aug 19, 2023 |
| Lenovo        | ThinkPad E470 20H2S0XB00    | Notebook    | [517d8c57d2](https://linux-hardware.org/?probe=517d8c57d2) | Aug 19, 2023 |
| Dell          | Vostro 3401                 | Notebook    | [792ea03809](https://linux-hardware.org/?probe=792ea03809) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [80b304814d](https://linux-hardware.org/?probe=80b304814d) | Aug 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [dee14abe77](https://linux-hardware.org/?probe=dee14abe77) | Aug 18, 2023 |
| Lenovo        | ThinkPad X230 23253B3       | Notebook    | [8da8bfe394](https://linux-hardware.org/?probe=8da8bfe394) | Aug 18, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [c95ab5ea6e](https://linux-hardware.org/?probe=c95ab5ea6e) | Aug 18, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [5369c283ad](https://linux-hardware.org/?probe=5369c283ad) | Aug 18, 2023 |
| Infinix       | INBOOK X1 NEO               | Notebook    | [bb08f7158b](https://linux-hardware.org/?probe=bb08f7158b) | Aug 18, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a5a12b8086](https://linux-hardware.org/?probe=a5a12b8086) | Aug 17, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [18c9f279a1](https://linux-hardware.org/?probe=18c9f279a1) | Aug 17, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [6c31be997f](https://linux-hardware.org/?probe=6c31be997f) | Aug 17, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [78d5f440ff](https://linux-hardware.org/?probe=78d5f440ff) | Aug 17, 2023 |
| Dell          | Latitude E6520              | Notebook    | [15420bd102](https://linux-hardware.org/?probe=15420bd102) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [145e7ceb96](https://linux-hardware.org/?probe=145e7ceb96) | Aug 16, 2023 |
| Acer          | Swift SF314-510G            | Notebook    | [11a4bc0bac](https://linux-hardware.org/?probe=11a4bc0bac) | Aug 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [12f64c8222](https://linux-hardware.org/?probe=12f64c8222) | Aug 16, 2023 |
| Dell          | Latitude 3520               | Notebook    | [33d3220fa3](https://linux-hardware.org/?probe=33d3220fa3) | Aug 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8298417da7](https://linux-hardware.org/?probe=8298417da7) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [ff958dc821](https://linux-hardware.org/?probe=ff958dc821) | Aug 16, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [859e36f237](https://linux-hardware.org/?probe=859e36f237) | Aug 16, 2023 |
| Dell          | Latitude 5300               | Notebook    | [506c05d30c](https://linux-hardware.org/?probe=506c05d30c) | Aug 15, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [ea9845e55b](https://linux-hardware.org/?probe=ea9845e55b) | Aug 15, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [31beedbfba](https://linux-hardware.org/?probe=31beedbfba) | Aug 15, 2023 |
| Lenovo        | Legion Y740-15IRH 81UF      | Notebook    | [2b0ec42ffb](https://linux-hardware.org/?probe=2b0ec42ffb) | Aug 15, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [5a2c741f84](https://linux-hardware.org/?probe=5a2c741f84) | Aug 14, 2023 |
| Lenovo        | ThinkCentre M58p 7220AR1    | Desktop     | [2bc1532fb7](https://linux-hardware.org/?probe=2bc1532fb7) | Aug 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [28be66d0b1](https://linux-hardware.org/?probe=28be66d0b1) | Aug 14, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [cfc638b4b2](https://linux-hardware.org/?probe=cfc638b4b2) | Aug 14, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1c643cc90f](https://linux-hardware.org/?probe=1c643cc90f) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5286543cae](https://linux-hardware.org/?probe=5286543cae) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [464dc037bd](https://linux-hardware.org/?probe=464dc037bd) | Aug 13, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [f98e22f722](https://linux-hardware.org/?probe=f98e22f722) | Aug 13, 2023 |
| Dell          | 0100P6 A01                  | Desktop     | [2cf993001c](https://linux-hardware.org/?probe=2cf993001c) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e0e0c962d5](https://linux-hardware.org/?probe=e0e0c962d5) | Aug 12, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [c336f9aa8c](https://linux-hardware.org/?probe=c336f9aa8c) | Aug 11, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [7d31344218](https://linux-hardware.org/?probe=7d31344218) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [980f6773f8](https://linux-hardware.org/?probe=980f6773f8) | Aug 10, 2023 |
| Dell          | 0YF8P5 A00                  | Desktop     | [93f35a6d26](https://linux-hardware.org/?probe=93f35a6d26) | Aug 10, 2023 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [479f066821](https://linux-hardware.org/?probe=479f066821) | Aug 10, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [646d098c58](https://linux-hardware.org/?probe=646d098c58) | Aug 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e703bb179f](https://linux-hardware.org/?probe=e703bb179f) | Aug 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [eee501d93c](https://linux-hardware.org/?probe=eee501d93c) | Aug 09, 2023 |
| Dell          | 06CJMN A00                  | Desktop     | [cead9bd601](https://linux-hardware.org/?probe=cead9bd601) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [eec04bec1d](https://linux-hardware.org/?probe=eec04bec1d) | Aug 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c9c978701a](https://linux-hardware.org/?probe=c9c978701a) | Aug 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [f69459e15a](https://linux-hardware.org/?probe=f69459e15a) | Aug 08, 2023 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | Desktop     | [6ffda81a5e](https://linux-hardware.org/?probe=6ffda81a5e) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [58446ba97c](https://linux-hardware.org/?probe=58446ba97c) | Aug 08, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [2335e10b59](https://linux-hardware.org/?probe=2335e10b59) | Aug 08, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [d91d6193e6](https://linux-hardware.org/?probe=d91d6193e6) | Aug 07, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [608c3967b2](https://linux-hardware.org/?probe=608c3967b2) | Aug 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | Notebook    | [ebcf58253e](https://linux-hardware.org/?probe=ebcf58253e) | Aug 07, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [8dae611904](https://linux-hardware.org/?probe=8dae611904) | Aug 06, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [91376cc583](https://linux-hardware.org/?probe=91376cc583) | Aug 06, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [bc55c09547](https://linux-hardware.org/?probe=bc55c09547) | Aug 06, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [44d851d327](https://linux-hardware.org/?probe=44d851d327) | Aug 06, 2023 |
| Dell          | Inspiron 7572               | Notebook    | [2509709a1e](https://linux-hardware.org/?probe=2509709a1e) | Aug 06, 2023 |
| Dell          | Precision 3571              | Notebook    | [fdbbd33ee6](https://linux-hardware.org/?probe=fdbbd33ee6) | Aug 06, 2023 |
| Dell          | Precision 3571              | Notebook    | [76de48bd02](https://linux-hardware.org/?probe=76de48bd02) | Aug 06, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [6af70944d8](https://linux-hardware.org/?probe=6af70944d8) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [1790fa9d72](https://linux-hardware.org/?probe=1790fa9d72) | Aug 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [1e157ae535](https://linux-hardware.org/?probe=1e157ae535) | Aug 05, 2023 |
| HP            | 15                          | Notebook    | [77ae1d8e7e](https://linux-hardware.org/?probe=77ae1d8e7e) | Aug 05, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [771a45e46f](https://linux-hardware.org/?probe=771a45e46f) | Aug 05, 2023 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [ba3a2e1773](https://linux-hardware.org/?probe=ba3a2e1773) | Aug 04, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [c5ea71f927](https://linux-hardware.org/?probe=c5ea71f927) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [082f92da07](https://linux-hardware.org/?probe=082f92da07) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [1078db460a](https://linux-hardware.org/?probe=1078db460a) | Aug 04, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [db4954c21d](https://linux-hardware.org/?probe=db4954c21d) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [0cf8e99478](https://linux-hardware.org/?probe=0cf8e99478) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [38f33f3878](https://linux-hardware.org/?probe=38f33f3878) | Aug 03, 2023 |
| OEM           | Intel H81                   | Desktop     | [82606b5050](https://linux-hardware.org/?probe=82606b5050) | Aug 03, 2023 |
| Alienware     | 14                          | Notebook    | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | Notebook                    | Notebook    | [258f6a82ad](https://linux-hardware.org/?probe=258f6a82ad) | Aug 02, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [97d2508df2](https://linux-hardware.org/?probe=97d2508df2) | Aug 02, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [2019699cac](https://linux-hardware.org/?probe=2019699cac) | Aug 02, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [5523e61097](https://linux-hardware.org/?probe=5523e61097) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [32d205bbdf](https://linux-hardware.org/?probe=32d205bbdf) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a0270160ad](https://linux-hardware.org/?probe=a0270160ad) | Aug 02, 2023 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | Desktop     | [69cd0aae71](https://linux-hardware.org/?probe=69cd0aae71) | Aug 02, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [6fe0b53a1b](https://linux-hardware.org/?probe=6fe0b53a1b) | Aug 02, 2023 |
| Dell          | Latitude E7470              | Notebook    | [d377538364](https://linux-hardware.org/?probe=d377538364) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [5650f66cd4](https://linux-hardware.org/?probe=5650f66cd4) | Jul 31, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [ff6816b285](https://linux-hardware.org/?probe=ff6816b285) | Jul 31, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [f641b9c622](https://linux-hardware.org/?probe=f641b9c622) | Jul 30, 2023 |
| Dell          | Latitude E5270              | Notebook    | [ae07c57989](https://linux-hardware.org/?probe=ae07c57989) | Jul 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [d9d3f5bce4](https://linux-hardware.org/?probe=d9d3f5bce4) | Jul 30, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [20d5d0a3ad](https://linux-hardware.org/?probe=20d5d0a3ad) | Jul 30, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [eff9350e7f](https://linux-hardware.org/?probe=eff9350e7f) | Jul 29, 2023 |
| Lenovo        | 3132 NOK                    | Desktop     | [6ab9975946](https://linux-hardware.org/?probe=6ab9975946) | Jul 29, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [6a6420b23e](https://linux-hardware.org/?probe=6a6420b23e) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Dell          | Precision 3550              | Notebook    | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | Notebook    | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [2f6969a3c9](https://linux-hardware.org/?probe=2f6969a3c9) | Jul 27, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d6a4c29101](https://linux-hardware.org/?probe=d6a4c29101) | Jul 27, 2023 |
| Dell          | 0W7JN5 A01                  | Server      | [8f86e6220c](https://linux-hardware.org/?probe=8f86e6220c) | Jul 27, 2023 |
| Dell          | 0W7JN5 A01                  | Server      | [568da91aee](https://linux-hardware.org/?probe=568da91aee) | Jul 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CJC... | Notebook    | [d7fa33e7b1](https://linux-hardware.org/?probe=d7fa33e7b1) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [1bac11c715](https://linux-hardware.org/?probe=1bac11c715) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [1409af2a38](https://linux-hardware.org/?probe=1409af2a38) | Jul 26, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [2c7364f005](https://linux-hardware.org/?probe=2c7364f005) | Jul 26, 2023 |
| HP            | 87A4 10100                  | All in one  | [99d5e60209](https://linux-hardware.org/?probe=99d5e60209) | Jul 26, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [866a4197cd](https://linux-hardware.org/?probe=866a4197cd) | Jul 26, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [a6abe36eef](https://linux-hardware.org/?probe=a6abe36eef) | Jul 26, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [8a297cb644](https://linux-hardware.org/?probe=8a297cb644) | Jul 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [aa34907e3a](https://linux-hardware.org/?probe=aa34907e3a) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [82a990b785](https://linux-hardware.org/?probe=82a990b785) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [dc97ca175a](https://linux-hardware.org/?probe=dc97ca175a) | Jul 25, 2023 |
| HP            | ENVY Notebook               | Notebook    | [9ab8362949](https://linux-hardware.org/?probe=9ab8362949) | Jul 25, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [e1fea727ff](https://linux-hardware.org/?probe=e1fea727ff) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [61646d77f1](https://linux-hardware.org/?probe=61646d77f1) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [8377b87a66](https://linux-hardware.org/?probe=8377b87a66) | Jul 24, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [eb0aac9c32](https://linux-hardware.org/?probe=eb0aac9c32) | Jul 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [8ecb2eb1fc](https://linux-hardware.org/?probe=8ecb2eb1fc) | Jul 24, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [d9f18f8f28](https://linux-hardware.org/?probe=d9f18f8f28) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [e822964466](https://linux-hardware.org/?probe=e822964466) | Jul 24, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [313f3aa210](https://linux-hardware.org/?probe=313f3aa210) | Jul 23, 2023 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [d47fdd358d](https://linux-hardware.org/?probe=d47fdd358d) | Jul 23, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [545d840e2f](https://linux-hardware.org/?probe=545d840e2f) | Jul 23, 2023 |
| Dell          | Latitude 3490               | Notebook    | [8988026686](https://linux-hardware.org/?probe=8988026686) | Jul 23, 2023 |
| Dell          | Latitude 3490               | Notebook    | [b7f8f886f8](https://linux-hardware.org/?probe=b7f8f886f8) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [6c0c0671df](https://linux-hardware.org/?probe=6c0c0671df) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cc08425e5b](https://linux-hardware.org/?probe=cc08425e5b) | Jul 22, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [2cad6d3cb7](https://linux-hardware.org/?probe=2cad6d3cb7) | Jul 22, 2023 |
| Timi          | Mi NoteBook Horizon Edit... | Notebook    | [72a5dfb7cd](https://linux-hardware.org/?probe=72a5dfb7cd) | Jul 21, 2023 |
| Dell          | 0NKW6Y A00                  | Desktop     | [a331a92532](https://linux-hardware.org/?probe=a331a92532) | Jul 21, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [33150ea27b](https://linux-hardware.org/?probe=33150ea27b) | Jul 21, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [6bb2b5bfb6](https://linux-hardware.org/?probe=6bb2b5bfb6) | Jul 20, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [061efe2135](https://linux-hardware.org/?probe=061efe2135) | Jul 20, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [18a6e9f055](https://linux-hardware.org/?probe=18a6e9f055) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [d366e7101c](https://linux-hardware.org/?probe=d366e7101c) | Jul 20, 2023 |
| AVITA         | NS14A6                      | Notebook    | [594afbeb74](https://linux-hardware.org/?probe=594afbeb74) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [77468bcff7](https://linux-hardware.org/?probe=77468bcff7) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [eb7b37c1d2](https://linux-hardware.org/?probe=eb7b37c1d2) | Jul 19, 2023 |
| HP            | Notebook                    | Notebook    | [2ccf016245](https://linux-hardware.org/?probe=2ccf016245) | Jul 19, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [06e511f834](https://linux-hardware.org/?probe=06e511f834) | Jul 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [38c5f4d547](https://linux-hardware.org/?probe=38c5f4d547) | Jul 19, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [0c537839b2](https://linux-hardware.org/?probe=0c537839b2) | Jul 19, 2023 |
| Unknown       | G41 Series                  | Desktop     | [5890a777c5](https://linux-hardware.org/?probe=5890a777c5) | Jul 19, 2023 |
| Dell          | Precision 3581              | Notebook    | [68d58784d5](https://linux-hardware.org/?probe=68d58784d5) | Jul 18, 2023 |
| Dell          | Latitude 5480               | Notebook    | [30aaaf3ba8](https://linux-hardware.org/?probe=30aaaf3ba8) | Jul 18, 2023 |
| Dell          | Latitude 3590               | Notebook    | [6386a869e5](https://linux-hardware.org/?probe=6386a869e5) | Jul 18, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [3d0b2577a1](https://linux-hardware.org/?probe=3d0b2577a1) | Jul 18, 2023 |
| Dell          | Latitude 7480               | Notebook    | [83caa544f7](https://linux-hardware.org/?probe=83caa544f7) | Jul 18, 2023 |
| Dell          | Latitude 7480               | Notebook    | [526e020c94](https://linux-hardware.org/?probe=526e020c94) | Jul 18, 2023 |
| Dell          | 0XFWHV A00                  | Desktop     | [0c229a1245](https://linux-hardware.org/?probe=0c229a1245) | Jul 18, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [5b68d7d6e2](https://linux-hardware.org/?probe=5b68d7d6e2) | Jul 16, 2023 |
| Intel         | DH61BF AAG81311-102         | Desktop     | [bc2e347565](https://linux-hardware.org/?probe=bc2e347565) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d43ad7594c](https://linux-hardware.org/?probe=d43ad7594c) | Jul 16, 2023 |
| HP            | 15                          | Notebook    | [73b0c0312f](https://linux-hardware.org/?probe=73b0c0312f) | Jul 15, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [94f963ff8c](https://linux-hardware.org/?probe=94f963ff8c) | Jul 15, 2023 |
| POWERX        | G41                         | Desktop     | [70a6d4e6bf](https://linux-hardware.org/?probe=70a6d4e6bf) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [b8481d7a4c](https://linux-hardware.org/?probe=b8481d7a4c) | Jul 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [c74dc748f5](https://linux-hardware.org/?probe=c74dc748f5) | Jul 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1e2b959156](https://linux-hardware.org/?probe=1e2b959156) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [e042e7c94e](https://linux-hardware.org/?probe=e042e7c94e) | Jul 14, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b8b0b27baf](https://linux-hardware.org/?probe=b8b0b27baf) | Jul 14, 2023 |
| HP            | 86F3 00100                  | All in one  | [3ab66add04](https://linux-hardware.org/?probe=3ab66add04) | Jul 14, 2023 |
| HP            | 86F3 00100                  | All in one  | [95577f518a](https://linux-hardware.org/?probe=95577f518a) | Jul 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [76513f6a7d](https://linux-hardware.org/?probe=76513f6a7d) | Jul 14, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [67b2bb6155](https://linux-hardware.org/?probe=67b2bb6155) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [934947072a](https://linux-hardware.org/?probe=934947072a) | Jul 13, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [d5079cefe1](https://linux-hardware.org/?probe=d5079cefe1) | Jul 13, 2023 |
| MSI           | Katana GF66 11UC            | Notebook    | [d22ab22240](https://linux-hardware.org/?probe=d22ab22240) | Jul 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [b31130eea6](https://linux-hardware.org/?probe=b31130eea6) | Jul 13, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [04c4e233af](https://linux-hardware.org/?probe=04c4e233af) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [949ca22bb2](https://linux-hardware.org/?probe=949ca22bb2) | Jul 12, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [3532802c06](https://linux-hardware.org/?probe=3532802c06) | Jul 12, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [f3c9995017](https://linux-hardware.org/?probe=f3c9995017) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [aea754f076](https://linux-hardware.org/?probe=aea754f076) | Jul 11, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [995e13dee9](https://linux-hardware.org/?probe=995e13dee9) | Jul 11, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [05f889dc1a](https://linux-hardware.org/?probe=05f889dc1a) | Jul 11, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [ad7b13940b](https://linux-hardware.org/?probe=ad7b13940b) | Jul 11, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7a8f3c985f](https://linux-hardware.org/?probe=7a8f3c985f) | Jul 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [37bc760339](https://linux-hardware.org/?probe=37bc760339) | Jul 11, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [76d89b3b3b](https://linux-hardware.org/?probe=76d89b3b3b) | Jul 11, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [50ed801045](https://linux-hardware.org/?probe=50ed801045) | Jul 11, 2023 |
| HP            | Pavilion - 14-CE2068ST      | Notebook    | [bdf8b67813](https://linux-hardware.org/?probe=bdf8b67813) | Jul 10, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [806e14ad19](https://linux-hardware.org/?probe=806e14ad19) | Jul 10, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [784f886357](https://linux-hardware.org/?probe=784f886357) | Jul 10, 2023 |
| Gigabyte      | B365M DS3H WIFI             | Desktop     | [150b2a2675](https://linux-hardware.org/?probe=150b2a2675) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | Desktop     | [a887a01dd7](https://linux-hardware.org/?probe=a887a01dd7) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [3a1baa8f6c](https://linux-hardware.org/?probe=3a1baa8f6c) | Jul 09, 2023 |
| HP            | Notebook                    | Notebook    | [a1c37a6a4b](https://linux-hardware.org/?probe=a1c37a6a4b) | Jul 09, 2023 |
| Intel         | H61                         | Desktop     | [11e024727c](https://linux-hardware.org/?probe=11e024727c) | Jul 09, 2023 |
| MSI           | Z97 GUARD-PRO               | Desktop     | [298da90a40](https://linux-hardware.org/?probe=298da90a40) | Jul 09, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| Dell          | Latitude E5440              | Notebook    | [9b4a70fe2b](https://linux-hardware.org/?probe=9b4a70fe2b) | Jul 08, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [629f165835](https://linux-hardware.org/?probe=629f165835) | Jul 07, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [b7459d1653](https://linux-hardware.org/?probe=b7459d1653) | Jul 07, 2023 |
| HP            | ProBook 4525s               | Notebook    | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| HP            | Laptop                      | Notebook    | [30a1d8ec1c](https://linux-hardware.org/?probe=30a1d8ec1c) | Jul 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [e555b073b5](https://linux-hardware.org/?probe=e555b073b5) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [b11fe33b8c](https://linux-hardware.org/?probe=b11fe33b8c) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [f5f96d51ed](https://linux-hardware.org/?probe=f5f96d51ed) | Jul 05, 2023 |
| HP            | 339A                        | Desktop     | [e746807776](https://linux-hardware.org/?probe=e746807776) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [ca637a5884](https://linux-hardware.org/?probe=ca637a5884) | Jul 05, 2023 |
| HP            | Laptop 14s-ef1xxx           | Notebook    | [14e321559e](https://linux-hardware.org/?probe=14e321559e) | Jul 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a889efa719](https://linux-hardware.org/?probe=a889efa719) | Jul 04, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [86c82575ec](https://linux-hardware.org/?probe=86c82575ec) | Jul 04, 2023 |
| Dell          | Precision 3581              | Notebook    | [1d4db3cec3](https://linux-hardware.org/?probe=1d4db3cec3) | Jul 03, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5634ff05d5](https://linux-hardware.org/?probe=5634ff05d5) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [dfd66d3d07](https://linux-hardware.org/?probe=dfd66d3d07) | Jul 03, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [c4dcbea71d](https://linux-hardware.org/?probe=c4dcbea71d) | Jul 03, 2023 |
| HP            | 861A                        | Desktop     | [0531675f82](https://linux-hardware.org/?probe=0531675f82) | Jul 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [da24c07da6](https://linux-hardware.org/?probe=da24c07da6) | Jul 02, 2023 |
| Gigabyte      | GA-H61M-S                   | Desktop     | [351a27ff5e](https://linux-hardware.org/?probe=351a27ff5e) | Jul 02, 2023 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [71aa2fd160](https://linux-hardware.org/?probe=71aa2fd160) | Jul 02, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [09c7b86b2c](https://linux-hardware.org/?probe=09c7b86b2c) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [835f3a390f](https://linux-hardware.org/?probe=835f3a390f) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [3271b3b559](https://linux-hardware.org/?probe=3271b3b559) | Jul 02, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [a8caf9af8e](https://linux-hardware.org/?probe=a8caf9af8e) | Jul 02, 2023 |
| ASRock        | B150M Pro4/Hyper            | Desktop     | [84eee16dd5](https://linux-hardware.org/?probe=84eee16dd5) | Jul 01, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [0c4c59cf86](https://linux-hardware.org/?probe=0c4c59cf86) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [d0fc2ea58e](https://linux-hardware.org/?probe=d0fc2ea58e) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [8b5dc3456b](https://linux-hardware.org/?probe=8b5dc3456b) | Jul 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [0aed51f639](https://linux-hardware.org/?probe=0aed51f639) | Jul 01, 2023 |
| Infinix       | INBOOK X2 PLUS              | Notebook    | [9a74f19725](https://linux-hardware.org/?probe=9a74f19725) | Jul 01, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [f127804b4a](https://linux-hardware.org/?probe=f127804b4a) | Jun 30, 2023 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [5ac29ea67f](https://linux-hardware.org/?probe=5ac29ea67f) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10467d9f3e](https://linux-hardware.org/?probe=10467d9f3e) | Jun 30, 2023 |
| HP            | 15                          | Notebook    | [2d80407689](https://linux-hardware.org/?probe=2d80407689) | Jun 30, 2023 |
| HP            | 15                          | Notebook    | [398d659d8c](https://linux-hardware.org/?probe=398d659d8c) | Jun 30, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [602d134940](https://linux-hardware.org/?probe=602d134940) | Jun 30, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [eab5331f66](https://linux-hardware.org/?probe=eab5331f66) | Jun 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/India/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 960       | 18.08%  |
| Ubuntu 22.04        | 418       | 7.87%   |
| Ubuntu 18.04        | 414       | 7.8%    |
| Arch Rolling        | 149       | 2.81%   |
| Pop!_OS 22.04       | 108       | 2.03%   |
| Zorin 16            | 104       | 1.96%   |
| Arch                | 104       | 1.96%   |
| Fedora 38           | 90        | 1.7%    |
| ArcoLinux Rolling   | 86        | 1.62%   |
| KDE neon 20.04      | 84        | 1.58%   |
| OpenMandriva 4.3    | 78        | 1.47%   |
| Fedora 36           | 70        | 1.32%   |
| Pop!_OS 20.04       | 67        | 1.26%   |
| Fedora 37           | 62        | 1.17%   |
| Pop!_OS 21.04       | 60        | 1.13%   |
| Ubuntu 20.10        | 58        | 1.09%   |
| Fedora 34           | 58        | 1.09%   |
| OpenMandriva 4.2    | 57        | 1.07%   |
| Zorin 15            | 56        | 1.05%   |
| Manjaro             | 55        | 1.04%   |
| Ubuntu 21.04        | 54        | 1.02%   |
| Ubuntu 19.10        | 51        | 0.96%   |
| Debian 11           | 47        | 0.89%   |
| Ubuntu 21.10        | 45        | 0.85%   |
| Ubuntu 19.04        | 45        | 0.85%   |
| Pop!_OS 20.10       | 44        | 0.83%   |
| Fedora 39           | 43        | 0.81%   |
| Ubuntu 23.04        | 42        | 0.79%   |
| Linux Mint 21.1     | 41        | 0.77%   |
| Fedora 35           | 40        | 0.75%   |
| Fedora 32           | 39        | 0.73%   |
| Debian 12           | 38        | 0.72%   |
| EndeavourOS Rolling | 37        | 0.7%    |
| KDE neon 22.04      | 35        | 0.66%   |
| Ubuntu Unity 16.04  | 34        | 0.64%   |
| Linux Mint 20       | 34        | 0.64%   |
| Fedora 33           | 34        | 0.64%   |
| OpenMandriva 23.03  | 33        | 0.62%   |
| Ubuntu 16.04        | 32        | 0.6%    |
| Linux Mint 20.2     | 32        | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2129      | 41.73%  |
| Fedora        | 429       | 8.41%   |
| Pop!_OS       | 291       | 5.7%    |
| Arch          | 244       | 4.78%   |
| OpenMandriva  | 236       | 4.63%   |
| Linux Mint    | 233       | 4.57%   |
| Zorin         | 168       | 3.29%   |
| Manjaro       | 137       | 2.69%   |
| Debian        | 133       | 2.61%   |
| KDE neon      | 128       | 2.51%   |
| Kali          | 96        | 1.88%   |
| ArcoLinux     | 92        | 1.8%    |
| Kubuntu       | 85        | 1.67%   |
| Ubuntu Unity  | 61        | 1.2%    |
| Elementary    | 59        | 1.16%   |
| Endless       | 53        | 1.04%   |
| EndeavourOS   | 41        | 0.8%    |
| Xubuntu       | 39        | 0.76%   |
| openSUSE      | 38        | 0.74%   |
| Garuda Linux  | 30        | 0.59%   |
| Xero          | 28        | 0.55%   |
| CentOS        | 28        | 0.55%   |
| RHEL          | 26        | 0.51%   |
| ROSA          | 23        | 0.45%   |
| Clear Linux   | 23        | 0.45%   |
| MX            | 20        | 0.39%   |
| Ubuntu MATE   | 18        | 0.35%   |
| Parrot        | 18        | 0.35%   |
| Ubuntu Budgie | 16        | 0.31%   |
| Lubuntu       | 15        | 0.29%   |
| Nobara        | 12        | 0.24%   |
| Void Linux    | 10        | 0.2%    |
| Solus         | 9         | 0.18%   |
| LMDE          | 9         | 0.18%   |
| Gentoo        | 9         | 0.18%   |
| Artix         | 8         | 0.16%   |
| Peppermint    | 7         | 0.14%   |
| BlackPanther  | 7         | 0.14%   |
| Slackware     | 6         | 0.12%   |
| Archcraft     | 6         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 153       | 2.68%   |
| 5.16.7-desktop-1omv4003  | 73        | 1.28%   |
| 5.4.0-40-generic         | 61        | 1.07%   |
| 5.10.14-desktop-1omv4002 | 57        | 1%      |
| 5.15.0-56-generic        | 54        | 0.94%   |
| 5.4.0-48-generic         | 47        | 0.82%   |
| 5.4.0-58-generic         | 43        | 0.75%   |
| 5.11.0-27-generic        | 41        | 0.72%   |
| 5.4.0-52-generic         | 40        | 0.7%    |
| 5.4.0-26-generic         | 40        | 0.7%    |
| 5.4.0-47-generic         | 39        | 0.68%   |
| 6.2.0-26-generic         | 35        | 0.61%   |
| 5.11.0-25-generic        | 35        | 0.61%   |
| 5.11.0-7620-generic      | 34        | 0.59%   |
| 5.4.0-29-generic         | 33        | 0.58%   |
| 6.2.6-desktop-1omv2390   | 32        | 0.56%   |
| 5.15.0-52-generic        | 32        | 0.56%   |
| 5.15.0-46-generic        | 31        | 0.54%   |
| 5.15.0-58-generic        | 30        | 0.52%   |
| 5.8.0-48-generic         | 29        | 0.51%   |
| 5.3.0-28-generic         | 29        | 0.51%   |
| 5.11.0-40-generic        | 29        | 0.51%   |
| 5.8.0-53-generic         | 28        | 0.49%   |
| 5.8.0-55-generic         | 27        | 0.47%   |
| 5.8.0-43-generic         | 27        | 0.47%   |
| 5.4.0-37-generic         | 27        | 0.47%   |
| 5.11.0-43-generic        | 26        | 0.45%   |
| 5.11.0-38-generic        | 26        | 0.45%   |
| 5.11.0-37-generic        | 26        | 0.45%   |
| 5.19.0-41-generic        | 25        | 0.44%   |
| 5.13.0-30-generic        | 25        | 0.44%   |
| 5.0.0-37-generic         | 25        | 0.44%   |
| 6.5.0-14-generic         | 24        | 0.42%   |
| 5.8.0-59-generic         | 24        | 0.42%   |
| 5.8.0-44-generic         | 24        | 0.42%   |
| 5.4.0-74-generic         | 24        | 0.42%   |
| 5.3.0-40-generic         | 24        | 0.42%   |
| 5.19.0-38-generic        | 24        | 0.42%   |
| 5.15.0-43-generic        | 24        | 0.42%   |
| 4.15.0-45-generic        | 24        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 873       | 15.94%  |
| 5.15.0  | 472       | 8.62%   |
| 5.11.0  | 337       | 6.15%   |
| 5.8.0   | 310       | 5.66%   |
| 4.15.0  | 237       | 4.33%   |
| 5.13.0  | 208       | 3.8%    |
| 5.3.0   | 192       | 3.51%   |
| 5.19.0  | 189       | 3.45%   |
| 6.2.0   | 168       | 3.07%   |
| 5.0.0   | 130       | 2.37%   |
| 4.18.0  | 104       | 1.9%    |
| 5.10.0  | 79        | 1.44%   |
| 5.16.7  | 75        | 1.37%   |
| 6.5.0   | 68        | 1.24%   |
| 6.1.0   | 67        | 1.22%   |
| 5.10.14 | 57        | 1.04%   |
| 6.2.6   | 51        | 0.93%   |
| 5.14.0  | 37        | 0.68%   |
| 4.19.0  | 30        | 0.55%   |
| 4.4.0   | 25        | 0.46%   |
| 6.4.11  | 23        | 0.42%   |
| 6.1.1   | 22        | 0.4%    |
| 5.17.5  | 22        | 0.4%    |
| 6.0.12  | 19        | 0.35%   |
| 6.6.6   | 18        | 0.33%   |
| 6.0.0   | 18        | 0.33%   |
| 6.2.9   | 17        | 0.31%   |
| 6.5.9   | 15        | 0.27%   |
| 6.5.5   | 15        | 0.27%   |
| 5.7.0   | 14        | 0.26%   |
| 6.6.8   | 13        | 0.24%   |
| 6.0.8   | 13        | 0.24%   |
| 6.0.6   | 13        | 0.24%   |
| 5.18.0  | 13        | 0.24%   |
| 5.15.11 | 13        | 0.24%   |
| 6.6.2   | 12        | 0.22%   |
| 6.4.8   | 12        | 0.22%   |
| 6.3.8   | 12        | 0.22%   |
| 6.0.9   | 12        | 0.22%   |
| 5.9.0   | 12        | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 913       | 16.87%  |
| 5.15    | 607       | 11.21%  |
| 5.11    | 376       | 6.95%   |
| 5.8     | 370       | 6.84%   |
| 6.2     | 293       | 5.41%   |
| 5.13    | 262       | 4.84%   |
| 5.19    | 245       | 4.53%   |
| 4.15    | 240       | 4.43%   |
| 5.3     | 218       | 4.03%   |
| 5.10    | 208       | 3.84%   |
| 6.1     | 174       | 3.21%   |
| 6.5     | 148       | 2.73%   |
| 5.16    | 141       | 2.6%    |
| 5.0     | 135       | 2.49%   |
| 6.0     | 112       | 2.07%   |
| 4.18    | 111       | 2.05%   |
| 6.4     | 94        | 1.74%   |
| 5.14    | 93        | 1.72%   |
| 6.6     | 91        | 1.68%   |
| 5.17    | 83        | 1.53%   |
| 5.18    | 71        | 1.31%   |
| 6.3     | 62        | 1.15%   |
| 5.12    | 56        | 1.03%   |
| 5.9     | 51        | 0.94%   |
| 5.7     | 49        | 0.91%   |
| 4.19    | 42        | 0.78%   |
| 5.6     | 41        | 0.76%   |
| 4.4     | 28        | 0.52%   |
| 5.5     | 26        | 0.48%   |
| 4.9     | 16        | 0.3%    |
| 6.7     | 12        | 0.22%   |
| 3.10    | 12        | 0.22%   |
| 5.2     | 8         | 0.15%   |
| 4.13    | 5         | 0.09%   |
| 5.1     | 4         | 0.07%   |
| 4.20    | 3         | 0.06%   |
| 3.16    | 3         | 0.06%   |
| 4.14    | 2         | 0.04%   |
| 4.1     | 2         | 0.04%   |
| 5       | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4811      | 98.14%  |
| i686    | 69        | 1.41%   |
| aarch64 | 16        | 0.33%   |
| armv7l  | 6         | 0.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 2894      | 56.7%   |
| KDE5              | 712       | 13.95%  |
| Unknown           | 488       | 9.56%   |
| XFCE              | 239       | 4.68%   |
| X-Cinnamon        | 204       | 4%      |
| KDE               | 107       | 2.1%    |
| Unity             | 63        | 1.23%   |
| MATE              | 61        | 1.2%    |
| Pantheon          | 57        | 1.12%   |
| i3                | 35        | 0.69%   |
| Cinnamon          | 35        | 0.69%   |
| GNOME Flashback   | 25        | 0.49%   |
| Budgie            | 24        | 0.47%   |
| LXDE              | 21        | 0.41%   |
| LXQt              | 19        | 0.37%   |
| Deepin            | 15        | 0.29%   |
| GNOME Classic     | 12        | 0.24%   |
| KDE4              | 11        | 0.22%   |
| bspwm             | 11        | 0.22%   |
| awesome           | 11        | 0.22%   |
| qtile             | 9         | 0.18%   |
| Hyprland          | 8         | 0.16%   |
| sway              | 7         | 0.14%   |
| Openbox           | 7         | 0.14%   |
| dwm               | 7         | 0.14%   |
| LeftWM            | 5         | 0.1%    |
| xmonad            | 4         | 0.08%   |
| lightdm-xsession  | 2         | 0.04%   |
| Enlightenment     | 2         | 0.04%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| xinitrc           | 1         | 0.02%   |
| KDE6              | 1         | 0.02%   |
| icewm             | 1         | 0.02%   |
| i3-with-shmlog    | 1         | 0.02%   |
| i3-gaps           | 1         | 0.02%   |
| herbstluftwm      | 1         | 0.02%   |
| Endless:GNOME     | 1         | 0.02%   |
| chadwm            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3587      | 70.86%  |
| Wayland | 1101      | 21.75%  |
| Unknown | 303       | 5.99%   |
| Tty     | 71        | 1.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2384      | 46.86%  |
| GDM     | 831       | 16.34%  |
| GDM3    | 724       | 14.23%  |
| SDDM    | 636       | 12.5%   |
| LightDM | 377       | 7.41%   |
| TDM     | 105       | 2.06%   |
| XDM     | 9         | 0.18%   |
| KDM     | 9         | 0.18%   |
| LXDM    | 4         | 0.08%   |
| SLiM    | 3         | 0.06%   |
| Ly      | 3         | 0.06%   |
| LY-DM   | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| en_IN            | 3037      | 59.83%  |
| en_US            | 1419      | 27.96%  |
| Unknown          | 384       | 7.57%   |
| en_GB            | 100       | 1.97%   |
| C                | 95        | 1.87%   |
| en_AG            | 8         | 0.16%   |
| en_CA            | 5         | 0.1%    |
| POSIX            | 3         | 0.06%   |
| zh_TW            | 2         | 0.04%   |
| mr_IN            | 2         | 0.04%   |
| mni_IN           | 2         | 0.04%   |
| en_IE            | 2         | 0.04%   |
| en_AU            | 2         | 0.04%   |
| ta_LK            | 1         | 0.02%   |
| sa_IN            | 1         | 0.02%   |
| pl_PL            | 1         | 0.02%   |
| ks_IN            | 1         | 0.02%   |
| es_ES            | 1         | 0.02%   |
| en_US.ISO-8859-1 | 1         | 0.02%   |
| en_SG            | 1         | 0.02%   |
| en_NG            | 1         | 0.02%   |
| en_HK            | 1         | 0.02%   |
| en_DK            | 1         | 0.02%   |
| en_BW            | 1         | 0.02%   |
| de_DE            | 1         | 0.02%   |
| Default          | 1         | 0.02%   |
| C.UTF8           | 1         | 0.02%   |
| aa_DJ            | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2952      | 59.09%  |
| BIOS | 2044      | 40.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3894      | 77.23%  |
| Btrfs   | 539       | 10.69%  |
| Overlay | 234       | 4.64%   |
| Tmpfs   | 148       | 2.94%   |
| Xfs     | 87        | 1.73%   |
| Unknown | 79        | 1.57%   |
| Zfs     | 23        | 0.46%   |
| F2fs    | 13        | 0.26%   |
| Ext2    | 13        | 0.26%   |
| Ext3    | 9         | 0.18%   |
| XXXXX   | 1         | 0.02%   |
| Jfs     | 1         | 0.02%   |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2498      | 49.86%  |
| GPT     | 2128      | 42.48%  |
| MBR     | 384       | 7.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4322      | 86.68%  |
| Yes       | 664       | 13.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3020      | 60.62%  |
| Yes       | 1962      | 39.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 950       | 19.39%  |
| Hewlett-Packard         | 949       | 19.37%  |
| Dell                    | 891       | 18.18%  |
| ASUSTek Computer        | 625       | 12.76%  |
| Acer                    | 322       | 6.57%   |
| Gigabyte Technology     | 297       | 6.06%   |
| MSI                     | 163       | 3.33%   |
| Intel                   | 148       | 3.02%   |
| Unknown                 | 71        | 1.45%   |
| Sony                    | 51        | 1.04%   |
| ASRock                  | 41        | 0.84%   |
| Apple                   | 39        | 0.8%    |
| Timi                    | 37        | 0.76%   |
| Toshiba                 | 36        | 0.73%   |
| Samsung Electronics     | 28        | 0.57%   |
| AVITA                   | 23        | 0.47%   |
| OEM                     | 16        | 0.33%   |
| Infinix                 | 14        | 0.29%   |
| Raspberry Pi Foundation | 13        | 0.27%   |
| ECS                     | 12        | 0.24%   |
| Fujitsu                 | 11        | 0.22%   |
| Biostar                 | 11        | 0.22%   |
| HONOR                   | 10        | 0.2%    |
| HCL Infosystems Limited | 9         | 0.18%   |
| Google                  | 9         | 0.18%   |
| Foxconn                 | 9         | 0.18%   |
| AMI                     | 9         | 0.18%   |
| HUAWEI                  | 8         | 0.16%   |
| LG Electronics          | 6         | 0.12%   |
| Alienware               | 6         | 0.12%   |
| Gateway                 | 5         | 0.1%    |
| realme                  | 4         | 0.08%   |
| Radxa                   | 4         | 0.08%   |
| Pegatron                | 4         | 0.08%   |
| ITI LIMITED             | 4         | 0.08%   |
| eMachines               | 4         | 0.08%   |
| WIPRO                   | 3         | 0.06%   |
| Valve                   | 3         | 0.06%   |
| LORD ELECTRONICS        | 3         | 0.06%   |
| ZOTAC                   | 2         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 98        | 2%      |
| HP Notebook                            | 83        | 1.69%   |
| HP 15                                  | 35        | 0.71%   |
| HP Pavilion 15                         | 32        | 0.65%   |
| HP Pavilion g6                         | 29        | 0.59%   |
| Dell Inspiron 3542                     | 29        | 0.59%   |
| Lenovo E41-25 81FS                     | 23        | 0.47%   |
| Gigabyte H410M H V3                    | 23        | 0.47%   |
| Intel H61                              | 22        | 0.45%   |
| HP Laptop 15-bs0xx                     | 22        | 0.45%   |
| Dell Inspiron 15-3567                  | 22        | 0.45%   |
| Dell Inspiron 5570                     | 20        | 0.41%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 19        | 0.39%   |
| Dell Inspiron 3521                     | 19        | 0.39%   |
| HP Pavilion Notebook                   | 18        | 0.37%   |
| ASUS TUF Gaming FX505DT_FX505DT        | 18        | 0.37%   |
| Acer Aspire A715-75G                   | 17        | 0.35%   |
| Lenovo G50-80 80E5                     | 16        | 0.33%   |
| Gigabyte H81M-S                        | 16        | 0.33%   |
| Dell Vostro 15-3568                    | 16        | 0.33%   |
| Gigabyte H61MS                         | 15        | 0.31%   |
| Dell Vostro 3480                       | 15        | 0.31%   |
| Lenovo IdeaPad 320-15ISK 80XH          | 14        | 0.29%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 14        | 0.29%   |
| HP Laptop 15-da0xxx                    | 14        | 0.29%   |
| Timi Mi NoteBook Ultra                 | 13        | 0.27%   |
| HP Pavilion x360 Convertible 14-dh1xxx | 13        | 0.27%   |
| Dell Vostro 3578                       | 13        | 0.27%   |
| Dell Inspiron 5559                     | 13        | 0.27%   |
| Dell Inspiron 1545                     | 13        | 0.27%   |
| Lenovo G50-45 80E3                     | 12        | 0.24%   |
| HP Pavilion Laptop 14-dv0xxx           | 12        | 0.24%   |
| Gigabyte H310M S2 2.0                  | 12        | 0.24%   |
| Dell Inspiron N5010                    | 12        | 0.24%   |
| ASUS X510UNR                           | 12        | 0.24%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR   | 12        | 0.24%   |
| HP Laptop 15-bw0xx                     | 11        | 0.22%   |
| Gigabyte H110M-S2                      | 11        | 0.22%   |
| ASUS TUF Gaming FX505DY_FX505DY        | 11        | 0.22%   |
| ASUS All Series                        | 11        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 390       | 7.96%   |
| Lenovo ThinkPad    | 300       | 6.12%   |
| Lenovo IdeaPad     | 296       | 6.04%   |
| HP Pavilion        | 266       | 5.43%   |
| ASUS VivoBook      | 189       | 3.86%   |
| HP Laptop          | 178       | 3.63%   |
| Dell Latitude      | 173       | 3.53%   |
| Acer Aspire        | 166       | 3.39%   |
| Dell Vostro        | 163       | 3.33%   |
| Unknown            | 98        | 2%      |
| HP Notebook        | 84        | 1.71%   |
| HP EliteBook       | 66        | 1.35%   |
| ASUS ROG           | 66        | 1.35%   |
| ASUS TUF           | 60        | 1.22%   |
| ASUS ASUS          | 58        | 1.18%   |
| HP ProBook         | 55        | 1.12%   |
| Dell OptiPlex      | 53        | 1.08%   |
| Acer Nitro         | 46        | 0.94%   |
| HP ENVY            | 42        | 0.86%   |
| ASUS PRIME         | 42        | 0.86%   |
| Lenovo Legion      | 37        | 0.76%   |
| Dell XPS           | 37        | 0.76%   |
| HP 15              | 36        | 0.73%   |
| Dell Precision     | 33        | 0.67%   |
| Acer Swift         | 33        | 0.67%   |
| Toshiba Satellite  | 31        | 0.63%   |
| Lenovo ThinkBook   | 31        | 0.63%   |
| Gigabyte H410M     | 29        | 0.59%   |
| HP Compaq          | 28        | 0.57%   |
| Timi Mi            | 27        | 0.55%   |
| Lenovo ThinkCentre | 27        | 0.55%   |
| Lenovo E41-25      | 23        | 0.47%   |
| Intel H61          | 23        | 0.47%   |
| Gigabyte H310M     | 23        | 0.47%   |
| Lenovo Yoga        | 21        | 0.43%   |
| Lenovo IdeaPadFlex | 21        | 0.43%   |
| Acer Predator      | 21        | 0.43%   |
| HP OMEN            | 19        | 0.39%   |
| Acer Veriton       | 19        | 0.39%   |
| HP Victus          | 18        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 622       | 12.69%  |
| 2018    | 616       | 12.57%  |
| 2020    | 503       | 10.27%  |
| 2021    | 498       | 10.16%  |
| 2017    | 407       | 8.31%   |
| 2016    | 288       | 5.88%   |
| 2014    | 283       | 5.78%   |
| 2012    | 282       | 5.76%   |
| 2013    | 270       | 5.51%   |
| 2011    | 243       | 4.96%   |
| 2022    | 218       | 4.45%   |
| 2015    | 191       | 3.9%    |
| 2010    | 177       | 3.61%   |
| 2008    | 94        | 1.92%   |
| 2009    | 74        | 1.51%   |
| 2023    | 67        | 1.37%   |
| 2007    | 33        | 0.67%   |
| Unknown | 21        | 0.43%   |
| 2006    | 8         | 0.16%   |
| 2005    | 3         | 0.06%   |
| 2004    | 1         | 0.02%   |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3564      | 72.73%  |
| Desktop        | 1085      | 22.14%  |
| Convertible    | 133       | 2.71%   |
| Mini pc        | 36        | 0.73%   |
| All in one     | 34        | 0.69%   |
| System on chip | 21        | 0.43%   |
| Server         | 15        | 0.31%   |
| Tablet         | 12        | 0.24%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4328      | 87.52%  |
| Enabled  | 617       | 12.48%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4884      | 99.67%  |
| Yes  | 16        | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1579      | 31.75%  |
| 3.01-4.0        | 1066      | 21.43%  |
| 8.01-16.0       | 966       | 19.42%  |
| 16.01-24.0      | 845       | 16.99%  |
| 32.01-64.0      | 199       | 4%      |
| 1.01-2.0        | 162       | 3.26%   |
| 64.01-256.0     | 51        | 1.03%   |
| 2.01-3.0        | 44        | 0.88%   |
| 24.01-32.0      | 42        | 0.84%   |
| 0.51-1.0        | 17        | 0.34%   |
| 0.01-0.5        | 2         | 0.04%   |
| More than 256.0 | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1656      | 30.77%  |
| 1.01-2.0    | 1630      | 30.29%  |
| 4.01-8.0    | 865       | 16.08%  |
| 3.01-4.0    | 824       | 15.31%  |
| 0.51-1.0    | 186       | 3.46%   |
| 8.01-16.0   | 170       | 3.16%   |
| 0.01-0.5    | 33        | 0.61%   |
| 16.01-24.0  | 11        | 0.2%    |
| 32.01-64.0  | 2         | 0.04%   |
| 24.01-32.0  | 2         | 0.04%   |
| 64.01-256.0 | 1         | 0.02%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3460      | 69.52%  |
| 2      | 1226      | 24.63%  |
| 3      | 176       | 3.54%   |
| 4      | 48        | 0.96%   |
| 0      | 32        | 0.64%   |
| 5      | 19        | 0.38%   |
| 6      | 10        | 0.2%    |
| 7      | 3         | 0.06%   |
| 19     | 1         | 0.02%   |
| 9      | 1         | 0.02%   |
| 8      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3408      | 69.09%  |
| Yes       | 1525      | 30.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4024      | 81.96%  |
| No        | 886       | 18.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4309      | 87.62%  |
| No        | 609       | 12.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3670      | 74.07%  |
| No        | 1285      | 25.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| India   | 4900      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Bengaluru     | 630       | 12.04%  |
| Chennai       | 342       | 6.54%   |
| Mumbai        | 340       | 6.5%    |
| Hyderabad     | 315       | 6.02%   |
| Delhi         | 296       | 5.66%   |
| Pune          | 255       | 4.87%   |
| Kolkata       | 223       | 4.26%   |
| New Delhi     | 192       | 3.67%   |
| Ahmedabad     | 119       | 2.27%   |
| Lucknow       | 99        | 1.89%   |
| Patna         | 90        | 1.72%   |
| Jaipur        | 85        | 1.62%   |
| Ernakulam     | 79        | 1.51%   |
| Kochi         | 70        | 1.34%   |
| Gurgaon       | 70        | 1.34%   |
| Indore        | 67        | 1.28%   |
| Bhopal        | 63        | 1.2%    |
| Coimbatore    | 62        | 1.19%   |
| Trivandrum    | 53        | 1.01%   |
| Navi Mumbai   | 53        | 1.01%   |
| Thrissur      | 50        | 0.96%   |
| Surat         | 50        | 0.96%   |
| Guwahati      | 41        | 0.78%   |
| Bhubaneswar   | 40        | 0.76%   |
| Nagpur        | 39        | 0.75%   |
| Ludhiana      | 38        | 0.73%   |
| Malappuram    | 37        | 0.71%   |
| Noida         | 32        | 0.61%   |
| Chandigarh    | 30        | 0.57%   |
| Ghaziabad     | 28        | 0.54%   |
| Mangalore     | 26        | 0.5%    |
| Visakhapatnam | 25        | 0.48%   |
| Vadodara      | 24        | 0.46%   |
| Kanpur        | 24        | 0.46%   |
| Thane         | 23        | 0.44%   |
| Vijayawada    | 22        | 0.42%   |
| Gonikoppal    | 22        | 0.42%   |
| Dehradun      | 22        | 0.42%   |
| Kozhikode     | 20        | 0.38%   |
| Kottayam      | 20        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1289      | 1694   | 20.3%   |
| WDC                         | 1128      | 1469   | 17.76%  |
| Samsung Electronics         | 639       | 819    | 10.06%  |
| Toshiba                     | 577       | 665    | 9.09%   |
| Sandisk                     | 288       | 357    | 4.53%   |
| Crucial                     | 253       | 337    | 3.98%   |
| Kingston                    | 238       | 286    | 3.75%   |
| Intel                       | 218       | 294    | 3.43%   |
| SK hynix                    | 216       | 245    | 3.4%    |
| Micron Technology           | 193       | 225    | 3.04%   |
| HGST                        | 183       | 222    | 2.88%   |
| Unknown                     | 145       | 177    | 2.28%   |
| Hitachi                     | 117       | 140    | 1.84%   |
| KIOXIA                      | 93        | 107    | 1.46%   |
| A-DATA Technology           | 76        | 83     | 1.2%    |
| China                       | 57        | 68     | 0.9%    |
| Micron/Crucial Technology   | 42        | 47     | 0.66%   |
| Unknown                     | 34        | 43     | 0.54%   |
| Gigabyte Technology         | 30        | 35     | 0.47%   |
| FORESEE                     | 28        | 32     | 0.44%   |
| Silicon Motion              | 25        | 28     | 0.39%   |
| Apple                       | 23        | 31     | 0.36%   |
| UMIS                        | 22        | 26     | 0.35%   |
| Phison                      | 20        | 25     | 0.31%   |
| Hewlett-Packard             | 20        | 26     | 0.31%   |
| Kingston Technology Company | 17        | 20     | 0.27%   |
| LITEON                      | 16        | 20     | 0.25%   |
| SPCC                        | 14        | 21     | 0.22%   |
| Lexar                       | 14        | 14     | 0.22%   |
| Transcend                   | 12        | 14     | 0.19%   |
| Realtek Semiconductor       | 12        | 18     | 0.19%   |
| ADATA Technology            | 12        | 16     | 0.19%   |
| Acer                        | 12        | 13     | 0.19%   |
| XPG                         | 11        | 15     | 0.17%   |
| Maxtor                      | 10        | 26     | 0.16%   |
| POWER                       | 9         | 9      | 0.14%   |
| Fujitsu                     | 9         | 9      | 0.14%   |
| Union Memory (Shenzhen)     | 8         | 11     | 0.13%   |
| PNY                         | 8         | 10     | 0.13%   |
| Phison Electronics          | 8         | 8      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 306       | 4.58%   |
| Toshiba MQ04ABF100 1TB                            | 158       | 2.36%   |
| Toshiba MQ01ABD100 1TB                            | 111       | 1.66%   |
| Seagate ST1000DM010-2EP102 1TB                    | 96        | 1.44%   |
| Crucial CT240BX500SSD1 240GB                      | 84        | 1.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 74        | 1.11%   |
| Seagate ST1000LM049-2GH172 1TB                    | 70        | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 70        | 1.05%   |
| Seagate ST500LT012-1DG142 500GB                   | 66        | 0.99%   |
| Kingston SA400S37240G 240GB SSD                   | 61        | 0.91%   |
| Intel NVMe SSD Drive 512GB                        | 52        | 0.78%   |
| Toshiba MQ01ABF050 500GB                          | 47        | 0.7%    |
| Seagate ST500DM002-1BD142 500GB                   | 46        | 0.69%   |
| SanDisk NVMe SSD Drive 512GB                      | 45        | 0.67%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 42        | 0.63%   |
| Toshiba DT01ACA100 1TB                            | 42        | 0.63%   |
| Intel SSDPEKNW512G8 512GB                         | 41        | 0.61%   |
| HGST HTS541010A9E680 1TB                          | 41        | 0.61%   |
| Seagate ST9500325AS 500GB                         | 39        | 0.58%   |
| WDC WD10SPZX-24Z10 1TB                            | 38        | 0.57%   |
| SanDisk NVMe SSD Drive 256GB                      | 38        | 0.57%   |
| Seagate ST2000LM007-1R8174 2TB                    | 37        | 0.55%   |
| Seagate ST1000LM048-2E7172 1TB                    | 37        | 0.55%   |
| Micron 2450_MTFDKBA512TFK 512GB                   | 37        | 0.55%   |
| Samsung NVMe SSD Drive 512GB                      | 36        | 0.54%   |
| HGST HTS721010A9E630 1TB                          | 34        | 0.51%   |
| Unknown                                           | 34        | 0.51%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 33        | 0.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 31        | 0.46%   |
| Crucial CT480BX500SSD1 480GB                      | 31        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                     | 30        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 29        | 0.43%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 28        | 0.42%   |
| HGST HTS545050A7E680 500GB                        | 28        | 0.42%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 27        | 0.4%    |
| Samsung SSD 860 EVO 250GB                         | 27        | 0.4%    |
| Kingston SA400S37120G 120GB SSD                   | 27        | 0.4%    |
| Seagate ST3500312CS 500GB                         | 26        | 0.39%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 26        | 0.39%   |
| Samsung SSD 850 EVO 250GB                         | 25        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1272      | 1673   | 41.95%  |
| WDC                 | 845       | 1059   | 27.87%  |
| Toshiba             | 511       | 579    | 16.85%  |
| HGST                | 183       | 222    | 6.04%   |
| Hitachi             | 117       | 140    | 3.86%   |
| Unknown             | 26        | 30     | 0.86%   |
| Samsung Electronics | 24        | 29     | 0.79%   |
| Fujitsu             | 9         | 9      | 0.3%    |
| Apple               | 9         | 9      | 0.3%    |
| TO Exter            | 7         | 7      | 0.23%   |
| Hewlett-Packard     | 7         | 8      | 0.23%   |
| External            | 5         | 9      | 0.16%   |
| StoreJet            | 4         | 4      | 0.13%   |
| Maxtor              | 3         | 3      | 0.1%    |
| MARSHAL             | 3         | 3      | 0.1%    |
| WD MediaMax         | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| Lenovo              | 1         | 1      | 0.03%   |
| KESU                | 1         | 2      | 0.03%   |
| JMicron Technology  | 1         | 1      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 224       | 284    | 15.98%  |
| Crucial             | 223       | 300    | 15.91%  |
| WDC                 | 206       | 254    | 14.69%  |
| Kingston            | 162       | 203    | 11.55%  |
| SanDisk             | 70        | 90     | 4.99%   |
| A-DATA Technology   | 66        | 73     | 4.71%   |
| China               | 56        | 67     | 3.99%   |
| SK hynix            | 38        | 40     | 2.71%   |
| Micron Technology   | 27        | 35     | 1.93%   |
| Intel               | 27        | 30     | 1.93%   |
| Gigabyte Technology | 24        | 27     | 1.71%   |
| FORESEE             | 18        | 22     | 1.28%   |
| Unknown             | 17        | 18     | 1.21%   |
| Toshiba             | 14        | 15     | 1%      |
| LITEON              | 14        | 18     | 1%      |
| Lexar               | 13        | 13     | 0.93%   |
| Apple               | 12        | 16     | 0.86%   |
| Hewlett-Packard     | 11        | 16     | 0.78%   |
| SPCC                | 10        | 14     | 0.71%   |
| Seagate             | 10        | 10     | 0.71%   |
| Acer                | 10        | 11     | 0.71%   |
| Transcend           | 8         | 10     | 0.57%   |
| POWER               | 8         | 8      | 0.57%   |
| PNY                 | 8         | 10     | 0.57%   |
| Maxtor              | 7         | 23     | 0.5%    |
| EVM                 | 6         | 8      | 0.43%   |
| CONSISTENT          | 6         | 7      | 0.43%   |
| Zebronics           | 5         | 5      | 0.36%   |
| Unknown             | 5         | 5      | 0.36%   |
| HS-SSD-C100         | 5         | 6      | 0.36%   |
| Netac               | 4         | 4      | 0.29%   |
| LITEONIT            | 4         | 7      | 0.29%   |
| Leven               | 4         | 4      | 0.29%   |
| KingSpec            | 4         | 4      | 0.29%   |
| Aarvex              | 4         | 5      | 0.29%   |
| Plextor             | 3         | 3      | 0.21%   |
| KLEVV               | 3         | 4      | 0.21%   |
| geonix              | 3         | 3      | 0.21%   |
| Unknown (690)       | 2         | 2      | 0.14%   |
| Team                | 2         | 2      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2866      | 3792   | 47.3%   |
| NVMe    | 1706      | 2227   | 28.16%  |
| SSD     | 1318      | 1741   | 21.75%  |
| MMC     | 111       | 143    | 1.83%   |
| Unknown | 58        | 72     | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3584      | 5426   | 64.65%  |
| NVMe | 1704      | 2222   | 30.74%  |
| SAS  | 145       | 184    | 2.62%   |
| MMC  | 111       | 143    | 2%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2174      | 2917   | 51.98%  |
| 0.51-1.0   | 1785      | 2257   | 42.68%  |
| 1.01-2.0   | 152       | 228    | 3.63%   |
| 3.01-4.0   | 42        | 75     | 1%      |
| 4.01-10.0  | 15        | 31     | 0.36%   |
| 2.01-3.0   | 11        | 17     | 0.26%   |
| 10.01-20.0 | 3         | 8      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1397      | 26.95%  |
| 101-250        | 1319      | 25.45%  |
| 501-1000       | 887       | 17.11%  |
| 51-100         | 458       | 8.84%   |
| 1001-2000      | 328       | 6.33%   |
| 21-50          | 289       | 5.58%   |
| 1-20           | 270       | 5.21%   |
| More than 3000 | 85        | 1.64%   |
| 2001-3000      | 75        | 1.45%   |
| Unknown        | 75        | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1994      | 37.17%  |
| 21-50          | 1128      | 21.03%  |
| 101-250        | 738       | 13.76%  |
| 51-100         | 671       | 12.51%  |
| 251-500        | 414       | 7.72%   |
| 501-1000       | 226       | 4.21%   |
| 1001-2000      | 81        | 1.51%   |
| Unknown        | 75        | 1.4%    |
| More than 3000 | 22        | 0.41%   |
| 2001-3000      | 14        | 0.26%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 30        | 33     | 6.4%    |
| HGST HTS541010A9E680 1TB             | 14        | 14     | 2.99%   |
| HGST HTS545050A7E680 500GB           | 13        | 17     | 2.77%   |
| Seagate ST500LT012-1DG142 500GB      | 12        | 12     | 2.56%   |
| Seagate ST500DM002-1BD142 500GB      | 12        | 12     | 2.56%   |
| Toshiba MQ01ABD100 1TB               | 11        | 11     | 2.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 11        | 11     | 2.35%   |
| Seagate ST9500325AS 500GB            | 10        | 10     | 2.13%   |
| Seagate ST1000LM049-2GH172 1TB       | 10        | 12     | 2.13%   |
| Toshiba MQ04ABF100 1TB               | 6         | 7      | 1.28%   |
| Toshiba MQ01ABF050 500GB             | 6         | 6      | 1.28%   |
| Seagate ST500LT012-9WS142 500GB      | 6         | 7      | 1.28%   |
| Seagate ST500LM021-1KJ152 500GB      | 6         | 6      | 1.28%   |
| WDC WD10EZEX-08WN4A0 1TB             | 5         | 5      | 1.07%   |
| Seagate ST3500418AS 500GB            | 5         | 5      | 1.07%   |
| Seagate ST2000LM007-1R8174 2TB       | 5         | 5      | 1.07%   |
| HGST HTS721010A9E630 1TB             | 5         | 5      | 1.07%   |
| HGST HTS545050A7E380 500GB           | 5         | 5      | 1.07%   |
| Seagate ST3500312CS 500GB            | 4         | 4      | 0.85%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 5      | 0.85%   |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 4      | 0.85%   |
| Seagate ST1000DM003-1ER162 1TB       | 4         | 4      | 0.85%   |
| HGST HTS725050A7E630 500GB           | 4         | 4      | 0.85%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 3      | 0.64%   |
| WDC WD10JPVX-60JC3T1 1TB             | 3         | 3      | 0.64%   |
| Toshiba DT01ACA100 1TB               | 3         | 5      | 0.64%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 4      | 0.64%   |
| Seagate ST9320325AS 320GB            | 3         | 3      | 0.64%   |
| Seagate ST9160314AS 160GB            | 3         | 4      | 0.64%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 3      | 0.64%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 3      | 0.64%   |
| Hitachi HTS545032B9A300 320GB        | 3         | 5      | 0.64%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 3      | 0.64%   |
| Unknown                              | 3         | 3      | 0.64%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 2      | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 2      | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 2      | 0.43%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 2      | 0.43%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 2         | 2      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 179       | 197    | 38.74%  |
| WDC                         | 91        | 107    | 19.7%   |
| Toshiba                     | 46        | 50     | 9.96%   |
| HGST                        | 45        | 49     | 9.74%   |
| Hitachi                     | 31        | 35     | 6.71%   |
| SK hynix                    | 13        | 15     | 2.81%   |
| Samsung Electronics         | 12        | 16     | 2.6%    |
| SanDisk                     | 7         | 7      | 1.52%   |
| Intel                       | 4         | 4      | 0.87%   |
| Crucial                     | 4         | 5      | 0.87%   |
| Apple                       | 3         | 3      | 0.65%   |
| A-DATA Technology           | 3         | 4      | 0.65%   |
| Unknown                     | 3         | 3      | 0.65%   |
| SPCC                        | 2         | 2      | 0.43%   |
| Micron Technology           | 2         | 2      | 0.43%   |
| China                       | 2         | 2      | 0.43%   |
| ZEB-SD26                    | 1         | 1      | 0.22%   |
| YS                          | 1         | 1      | 0.22%   |
| Wibtek                      | 1         | 1      | 0.22%   |
| Unknown                     | 1         | 1      | 0.22%   |
| Secure                      | 1         | 1      | 0.22%   |
| POWER                       | 1         | 1      | 0.22%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.22%   |
| MARSHAL                     | 1         | 1      | 0.22%   |
| LITEONIT                    | 1         | 1      | 0.22%   |
| LITEON                      | 1         | 1      | 0.22%   |
| Leven                       | 1         | 1      | 0.22%   |
| Lenovo                      | 1         | 2      | 0.22%   |
| Innodisk                    | 1         | 1      | 0.22%   |
| IBM                         | 1         | 1      | 0.22%   |
| Gamers                      | 1         | 1      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 179       | 197    | 46.02%  |
| WDC                 | 79        | 94     | 20.31%  |
| Toshiba             | 45        | 49     | 11.57%  |
| HGST                | 45        | 49     | 11.57%  |
| Hitachi             | 31        | 35     | 7.97%   |
| Samsung Electronics | 5         | 7      | 1.29%   |
| Apple               | 3         | 3      | 0.77%   |
| MARSHAL             | 1         | 1      | 0.26%   |
| IBM                 | 1         | 1      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 384       | 436    | 84.03%  |
| SSD  | 52        | 57     | 11.38%  |
| NVMe | 21        | 24     | 4.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB         | 1         | 1      | 10%     |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 1      | 10%     |
| Toshiba HDWD110 1TB                 | 1         | 1      | 10%     |
| Seagate ST9320320AS 320GB           | 1         | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 10%     |
| Seagate ST3320418AS 320GB           | 1         | 1      | 10%     |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1         | 1      | 10%     |
| Samsung Electronics SSD 980 500GB   | 1         | 2      | 10%     |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 10%     |
| Acer SSD FA100 256GB                | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 40%     |
| WDC                 | 2         | 2      | 20%     |
| Toshiba             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 2      | 10%     |
| Apple               | 1         | 1      | 10%     |
| Acer                | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2879      | 4575   | 54.97%  |
| Works    | 1901      | 2872   | 36.3%   |
| Malfunc  | 447       | 517    | 8.54%   |
| Failed   | 10        | 11     | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3600      | 59.45%  |
| AMD                                     | 756       | 12.48%  |
| Samsung Electronics                     | 415       | 6.85%   |
| SanDisk                                 | 332       | 5.48%   |
| SK hynix                                | 178       | 2.94%   |
| Micron Technology                       | 166       | 2.74%   |
| KIOXIA                                  | 97        | 1.6%    |
| Kingston Technology Company             | 93        | 1.54%   |
| Micron/Crucial Technology               | 70        | 1.16%   |
| Toshiba America Info Systems            | 63        | 1.04%   |
| Union Memory (Shenzhen)                 | 32        | 0.53%   |
| Phison Electronics                      | 32        | 0.53%   |
| Silicon Motion                          | 30        | 0.5%    |
| ADATA Technology                        | 29        | 0.48%   |
| ASMedia Technology                      | 26        | 0.43%   |
| Shenzhen Longsys Electronics            | 18        | 0.3%    |
| Nvidia                                  | 18        | 0.3%    |
| Realtek Semiconductor                   | 17        | 0.28%   |
| Yangtze Memory Technologies             | 10        | 0.17%   |
| Solid State Storage Technology          | 8         | 0.13%   |
| Marvell Technology Group                | 8         | 0.13%   |
| JMicron Technology                      | 8         | 0.13%   |
| Lite-On Technology                      | 6         | 0.1%    |
| Lenovo                                  | 5         | 0.08%   |
| Silicon Integrated Systems [SiS]        | 4         | 0.07%   |
| MAXIO Technology (Hangzhou)             | 4         | 0.07%   |
| LSI Logic / Symbios Logic               | 4         | 0.07%   |
| INNOGRIT                                | 4         | 0.07%   |
| Broadcom / LSI                          | 4         | 0.07%   |
| Apple                                   | 3         | 0.05%   |
| VIA Technologies                        | 2         | 0.03%   |
| Transcend                               | 2         | 0.03%   |
| Shenzhen Unionmemory Information System | 2         | 0.03%   |
| Seagate Technology                      | 2         | 0.03%   |
| Solidigm                                | 1         | 0.02%   |
| ShenZhen TIGO Semiconductor             | 1         | 0.02%   |
| Nextorage                               | 1         | 0.02%   |
| Netac Technology                        | 1         | 0.02%   |
| Integrated Technology Express           | 1         | 0.02%   |
| Hosin Global Electronics                | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 635       | 9.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 515       | 7.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 364       | 5.38%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 229       | 3.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 211       | 3.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 193       | 2.86%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 178       | 2.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 155       | 2.29%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 147       | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 136       | 2.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 135       | 2%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 132       | 1.95%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 124       | 1.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 120       | 1.78%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 116       | 1.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 116       | 1.72%   |
| Intel SSD 660P Series                                                                   | 114       | 1.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 101       | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 90        | 1.33%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 85        | 1.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 83        | 1.23%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 81        | 1.2%    |
| AMD 400 Series Chipset SATA Controller                                                  | 70        | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 62        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 61        | 0.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 60        | 0.89%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                   | 57        | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 56        | 0.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 54        | 0.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 54        | 0.8%    |
| Micron 2210 NVMe SSD [Cobain]                                                           | 52        | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 50        | 0.74%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 49        | 0.72%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 49        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 48        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 47        | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                                   | 45        | 0.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 44        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 41        | 0.61%   |
| SK hynix BC511 NVMe SSD                                                                 | 40        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3470      | 55.59%  |
| NVMe | 1715      | 27.48%  |
| RAID | 655       | 10.49%  |
| IDE  | 397       | 6.36%   |
| SAS  | 3         | 0.05%   |
| SCSI | 2         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3876      | 79.1%   |
| AMD          | 1001      | 20.43%  |
| ARM          | 22        | 0.45%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 200       | 4.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 129       | 2.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 112       | 2.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 95        | 1.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 86        | 1.75%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 82        | 1.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 60        | 1.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 54        | 1.1%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 54        | 1.1%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 53        | 1.08%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 53        | 1.08%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 52        | 1.06%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 51        | 1.04%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 48        | 0.98%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 46        | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 45        | 0.92%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 45        | 0.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 41        | 0.84%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 41        | 0.84%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 41        | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 40        | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 40        | 0.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 38        | 0.78%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 37        | 0.75%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 37        | 0.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 35        | 0.71%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 35        | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 34        | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 33        | 0.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 32        | 0.65%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 32        | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 0.59%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 29        | 0.59%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 28        | 0.57%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 26        | 0.53%   |
| Intel 12th Gen Core i5-1240P                  | 26        | 0.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 26        | 0.53%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 25        | 0.51%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 24        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1422      | 29.01%  |
| Intel Core i3           | 790       | 16.12%  |
| Intel Core i7           | 596       | 12.16%  |
| Other                   | 524       | 10.69%  |
| AMD Ryzen 5             | 404       | 8.24%   |
| AMD Ryzen 7             | 179       | 3.65%   |
| Intel Pentium           | 149       | 3.04%   |
| Intel Core 2 Duo        | 138       | 2.82%   |
| Intel Celeron           | 88        | 1.8%    |
| AMD Ryzen 3             | 80        | 1.63%   |
| Intel Pentium Dual-Core | 61        | 1.24%   |
| AMD A6                  | 48        | 0.98%   |
| AMD Ryzen 9             | 39        | 0.8%    |
| AMD A8                  | 34        | 0.69%   |
| AMD A4                  | 32        | 0.65%   |
| Intel Atom              | 29        | 0.59%   |
| Intel Xeon              | 27        | 0.55%   |
| AMD FX                  | 24        | 0.49%   |
| Intel Pentium Dual      | 22        | 0.45%   |
| Intel Core 2            | 18        | 0.37%   |
| AMD A10                 | 18        | 0.37%   |
| Intel Core 2 Quad       | 17        | 0.35%   |
| AMD E1                  | 15        | 0.31%   |
| Intel Pentium Silver    | 12        | 0.24%   |
| AMD Ryzen 7 PRO         | 11        | 0.22%   |
| Intel Core i9           | 9         | 0.18%   |
| AMD E2                  | 9         | 0.18%   |
| Intel Pentium Gold      | 8         | 0.16%   |
| Intel Pentium 4         | 7         | 0.14%   |
| AMD Ryzen 5 PRO         | 7         | 0.14%   |
| AMD Athlon II X2        | 7         | 0.14%   |
| AMD E                   | 6         | 0.12%   |
| AMD Athlon              | 6         | 0.12%   |
| Intel Xeon Silver       | 5         | 0.1%    |
| ARM BCM                 | 5         | 0.1%    |
| AMD Sempron             | 5         | 0.1%    |
| Intel Pentium D         | 4         | 0.08%   |
| AMD Ryzen Threadripper  | 4         | 0.08%   |
| AMD Phenom II X4        | 4         | 0.08%   |
| AMD Phenom II X2        | 4         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2156      | 43.97%  |
| 4       | 1749      | 35.67%  |
| 6       | 474       | 9.67%   |
| 8       | 281       | 5.73%   |
| 12      | 79        | 1.61%   |
| 1       | 59        | 1.2%    |
| 10      | 38        | 0.78%   |
| 14      | 26        | 0.53%   |
| 16      | 18        | 0.37%   |
| 24      | 8         | 0.16%   |
| 3       | 8         | 0.16%   |
| 32      | 3         | 0.06%   |
| 20      | 2         | 0.04%   |
| 36      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4880      | 99.59%  |
| 2       | 19        | 0.39%   |
| Unknown | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3774      | 76.97%  |
| 1       | 1125      | 22.95%  |
| 4       | 2         | 0.04%   |
| 12      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4844      | 98.8%   |
| Unknown        | 52        | 1.06%   |
| 32-bit         | 6         | 0.12%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1341      | 26.45%  |
| 0x806ea    | 236       | 4.66%   |
| 0x306a9    | 236       | 4.66%   |
| 0x806ec    | 234       | 4.62%   |
| 0x206a7    | 216       | 4.26%   |
| 0x806c1    | 168       | 3.31%   |
| 0x906ea    | 158       | 3.12%   |
| 0x40651    | 155       | 3.06%   |
| 0x406e3    | 154       | 3.04%   |
| 0x806e9    | 148       | 2.92%   |
| 0x1067a    | 125       | 2.47%   |
| 0x306c3    | 117       | 2.31%   |
| 0x306d4    | 112       | 2.21%   |
| 0x08108109 | 97        | 1.91%   |
| 0x706e5    | 82        | 1.62%   |
| 0x0a50000c | 80        | 1.58%   |
| 0x906e9    | 67        | 1.32%   |
| 0x20655    | 65        | 1.28%   |
| 0x806eb    | 62        | 1.22%   |
| 0x506e3    | 58        | 1.14%   |
| 0x08108102 | 50        | 0.99%   |
| 0xa0652    | 46        | 0.91%   |
| 0x06006705 | 46        | 0.91%   |
| 0x08600106 | 40        | 0.79%   |
| 0x6fd      | 39        | 0.77%   |
| 0x08608103 | 39        | 0.77%   |
| 0x906a3    | 36        | 0.71%   |
| 0x0a50000d | 34        | 0.67%   |
| 0x07030105 | 33        | 0.65%   |
| 0x20652    | 31        | 0.61%   |
| 0x08701021 | 30        | 0.59%   |
| 0x08600104 | 30        | 0.59%   |
| 0x0810100b | 29        | 0.57%   |
| 0xa0655    | 28        | 0.55%   |
| 0x906ed    | 24        | 0.47%   |
| 0x30678    | 23        | 0.45%   |
| 0x08101007 | 22        | 0.43%   |
| 0x06001119 | 22        | 0.43%   |
| 0x010000c8 | 21        | 0.41%   |
| 0x706a1    | 16        | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1213      | 24.71%  |
| Haswell          | 363       | 7.39%   |
| IvyBridge        | 303       | 6.17%   |
| Skylake          | 294       | 5.99%   |
| SandyBridge      | 284       | 5.79%   |
| TigerLake        | 254       | 5.17%   |
| Zen+             | 204       | 4.16%   |
| Unknown          | 187       | 3.81%   |
| Penryn           | 181       | 3.69%   |
| Zen 2            | 177       | 3.61%   |
| Zen 3            | 154       | 3.14%   |
| Broadwell        | 153       | 3.12%   |
| IceLake          | 140       | 2.85%   |
| Alderlake Hybrid | 138       | 2.81%   |
| CometLake        | 127       | 2.59%   |
| Westmere         | 123       | 2.51%   |
| Zen              | 89        | 1.81%   |
| Excavator        | 89        | 1.81%   |
| Core             | 84        | 1.71%   |
| Silvermont       | 69        | 1.41%   |
| Puma             | 55        | 1.12%   |
| Piledriver       | 47        | 0.96%   |
| Goldmont plus    | 31        | 0.63%   |
| K10              | 25        | 0.51%   |
| Goldmont         | 24        | 0.49%   |
| Nehalem          | 15        | 0.31%   |
| K10 Llano        | 13        | 0.26%   |
| Bobcat           | 13        | 0.26%   |
| NetBurst         | 12        | 0.24%   |
| Bonnell          | 11        | 0.22%   |
| Tremont          | 8         | 0.16%   |
| Jaguar           | 8         | 0.16%   |
| Steamroller      | 6         | 0.12%   |
| Bulldozer        | 6         | 0.12%   |
| K8 Hammer        | 5         | 0.1%    |
| P6               | 3         | 0.06%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3538      | 56.59%  |
| Nvidia                           | 1448      | 23.16%  |
| AMD                              | 1250      | 19.99%  |
| Matrox Electronics Systems       | 6         | 0.1%    |
| Silicon Integrated Systems [SiS] | 4         | 0.06%   |
| ASPEED Technology                | 4         | 0.06%   |
| VIA Technologies                 | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 280       | 4.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 249       | 3.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 203       | 3.18%   |
| Intel HD Graphics 620                                                                 | 202       | 3.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 201       | 3.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 200       | 3.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 193       | 3.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 189       | 2.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 181       | 2.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 175       | 2.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 173       | 2.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 157       | 2.46%   |
| Intel HD Graphics 5500                                                                | 134       | 2.1%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 119       | 1.86%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 118       | 1.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 118       | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                   | 92        | 1.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 87        | 1.36%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 76        | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 74        | 1.16%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 71        | 1.11%   |
| AMD Lucienne                                                                          | 71        | 1.11%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 70        | 1.1%    |
| Intel HD Graphics 630                                                                 | 67        | 1.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 66        | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 63        | 0.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 62        | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 61        | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 61        | 0.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 59        | 0.92%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 55        | 0.86%   |
| Nvidia GP108M [GeForce MX250]                                                         | 54        | 0.85%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 51        | 0.8%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 50        | 0.78%   |
| Intel HD Graphics 530                                                                 | 47        | 0.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 47        | 0.74%   |
| Nvidia GP108M [GeForce MX150]                                                         | 45        | 0.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 44        | 0.69%   |
| Nvidia GM108M [GeForce MX130]                                                         | 43        | 0.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 41        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2355      | 47.8%   |
| Intel + Nvidia     | 847       | 17.19%  |
| 1 x AMD            | 670       | 13.6%   |
| 1 x Nvidia         | 406       | 8.24%   |
| Intel + AMD        | 302       | 6.13%   |
| AMD + Nvidia       | 190       | 3.86%   |
| 2 x AMD            | 93        | 1.89%   |
| Other              | 28        | 0.57%   |
| 2 x Intel          | 16        | 0.32%   |
| 1 x Matrox         | 6         | 0.12%   |
| 2 x Nvidia         | 4         | 0.08%   |
| 1 x SiS            | 4         | 0.08%   |
| Nvidia + ASPEED    | 2         | 0.04%   |
| 1 x ASPEED         | 2         | 0.04%   |
| 1 x VIA            | 1         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4020      | 80.89%  |
| Proprietary | 795       | 16%     |
| Unknown     | 155       | 3.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3130      | 62.08%  |
| 1.01-2.0   | 727       | 14.42%  |
| 0.01-0.5   | 449       | 8.91%   |
| 3.01-4.0   | 358       | 7.1%    |
| 0.51-1.0   | 222       | 4.4%    |
| 5.01-6.0   | 70        | 1.39%   |
| 7.01-8.0   | 45        | 0.89%   |
| 8.01-16.0  | 27        | 0.54%   |
| 16.01-24.0 | 9         | 0.18%   |
| 2.01-3.0   | 5         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 833       | 16.49%  |
| Chimei Innolux          | 775       | 15.34%  |
| AU Optronics            | 757       | 14.99%  |
| LG Display              | 584       | 11.56%  |
| Samsung Electronics     | 419       | 8.3%    |
| Dell                    | 281       | 5.56%   |
| Goldstar                | 225       | 4.45%   |
| BenQ                    | 146       | 2.89%   |
| Acer                    | 134       | 2.65%   |
| PANDA                   | 121       | 2.4%    |
| Hewlett-Packard         | 97        | 1.92%   |
| Lenovo                  | 81        | 1.6%    |
| AOC                     | 56        | 1.11%   |
| Sharp                   | 51        | 1.01%   |
| Chi Mei Optoelectronics | 43        | 0.85%   |
| InfoVision              | 40        | 0.79%   |
| Apple                   | 33        | 0.65%   |
| Sony                    | 31        | 0.61%   |
| ViewSonic               | 30        | 0.59%   |
| HCL                     | 21        | 0.42%   |
| TMX                     | 19        | 0.38%   |
| Unknown                 | 17        | 0.34%   |
| Philips                 | 17        | 0.34%   |
| LG Electronics          | 13        | 0.26%   |
| STD                     | 9         | 0.18%   |
| Panasonic               | 9         | 0.18%   |
| LG Philips              | 9         | 0.18%   |
| CSO                     | 9         | 0.18%   |
| ASUSTek Computer        | 9         | 0.18%   |
| MSI                     | 8         | 0.16%   |
| InnoLux Display         | 8         | 0.16%   |
| HKC                     | 8         | 0.16%   |
| Toshiba                 | 7         | 0.14%   |
| SGT                     | 7         | 0.14%   |
| Xiaomi                  | 6         | 0.12%   |
| KDC                     | 6         | 0.12%   |
| Gigabyte Technology     | 6         | 0.12%   |
| Ancor Communications    | 6         | 0.12%   |
| Unknown                 | 5         | 0.1%    |
| RTK                     | 4         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 95        | 1.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 76        | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 47        | 0.92%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 41        | 0.8%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 39        | 0.76%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 39        | 0.76%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 38        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 37        | 0.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 37        | 0.72%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                     | 33        | 0.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 32        | 0.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 31        | 0.61%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 29        | 0.57%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 28        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 27        | 0.53%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                    | 27        | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 26        | 0.51%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 25        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 25        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 25        | 0.49%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch        | 25        | 0.49%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 24        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 24        | 0.47%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 24        | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 22        | 0.43%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 20        | 0.39%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 20        | 0.39%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 20        | 0.39%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 19        | 0.37%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 17        | 0.33%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                    | 17        | 0.33%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 17        | 0.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 16        | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 16        | 0.31%   |
| BOE LCD Monitor BOE07BD 1920x1080 309x174mm 14.0-inch                | 16        | 0.31%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 16        | 0.31%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch       | 16        | 0.31%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch         | 15        | 0.29%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 15        | 0.29%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 15        | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2450      | 50.03%  |
| 1366x768 (WXGA)    | 1622      | 33.12%  |
| 1600x900 (HD+)     | 148       | 3.02%   |
| 3840x2160 (4K)     | 118       | 2.41%   |
| 2560x1440 (QHD)    | 99        | 2.02%   |
| 1440x900 (WXGA+)   | 66        | 1.35%   |
| 1920x1200 (WUXGA)  | 58        | 1.18%   |
| 1280x800 (WXGA)    | 51        | 1.04%   |
| 2560x1600          | 40        | 0.82%   |
| 1280x1024 (SXGA)   | 30        | 0.61%   |
| 1360x768           | 29        | 0.59%   |
| 2560x1080          | 27        | 0.55%   |
| 2880x1800          | 25        | 0.51%   |
| 1680x1050 (WSXGA+) | 19        | 0.39%   |
| Unknown            | 15        | 0.31%   |
| 3200x2000          | 13        | 0.27%   |
| 3840x1080          | 9         | 0.18%   |
| 1024x768 (XGA)     | 9         | 0.18%   |
| 1024x600           | 7         | 0.14%   |
| 1280x720 (HD)      | 6         | 0.12%   |
| 3840x2400          | 4         | 0.08%   |
| 3456x2160          | 4         | 0.08%   |
| 3440x1440          | 4         | 0.08%   |
| 2288x1287          | 4         | 0.08%   |
| 2160x1440          | 4         | 0.08%   |
| 800x1280           | 3         | 0.06%   |
| 4093x4093          | 3         | 0.06%   |
| 2240x1400          | 3         | 0.06%   |
| 3072x1920          | 2         | 0.04%   |
| 2736x1824          | 2         | 0.04%   |
| 2256x1504          | 2         | 0.04%   |
| 1920x1280          | 2         | 0.04%   |
| 1280x768           | 2         | 0.04%   |
| 1152x864           | 2         | 0.04%   |
| 8160x4627          | 1         | 0.02%   |
| 6400x2160          | 1         | 0.02%   |
| 5760x2160          | 1         | 0.02%   |
| 4480x1080          | 1         | 0.02%   |
| 3840x1100          | 1         | 0.02%   |
| 3286x1080          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2145      | 42.46%  |
| 14      | 644       | 12.75%  |
| 13      | 641       | 12.69%  |
| 21      | 295       | 5.84%   |
| 18      | 247       | 4.89%   |
| 24      | 163       | 3.23%   |
| 23      | 124       | 2.45%   |
| 19      | 116       | 2.3%    |
| 27      | 114       | 2.26%   |
| Unknown | 110       | 2.18%   |
| 20      | 62        | 1.23%   |
| 17      | 61        | 1.21%   |
| 12      | 55        | 1.09%   |
| 16      | 49        | 0.97%   |
| 31      | 48        | 0.95%   |
| 34      | 25        | 0.49%   |
| 11      | 21        | 0.42%   |
| 72      | 15        | 0.3%    |
| 26      | 15        | 0.3%    |
| 22      | 12        | 0.24%   |
| 40      | 11        | 0.22%   |
| 32      | 11        | 0.22%   |
| 10      | 10        | 0.2%    |
| 84      | 8         | 0.16%   |
| 65      | 7         | 0.14%   |
| 46      | 7         | 0.14%   |
| 25      | 5         | 0.1%    |
| 52      | 4         | 0.08%   |
| 142     | 3         | 0.06%   |
| 86      | 3         | 0.06%   |
| 54      | 3         | 0.06%   |
| 42      | 3         | 0.06%   |
| 39      | 3         | 0.06%   |
| 7       | 3         | 0.06%   |
| 36      | 2         | 0.04%   |
| 75      | 1         | 0.02%   |
| 63      | 1         | 0.02%   |
| 61      | 1         | 0.02%   |
| 58      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3272      | 65.13%  |
| 401-500        | 716       | 14.25%  |
| 501-600        | 388       | 7.72%   |
| 201-300        | 249       | 4.96%   |
| 351-400        | 112       | 2.23%   |
| Unknown        | 110       | 2.19%   |
| 601-700        | 62        | 1.23%   |
| 701-800        | 38        | 0.76%   |
| 1001-1500      | 28        | 0.56%   |
| 1501-2000      | 24        | 0.48%   |
| 801-900        | 15        | 0.3%    |
| 901-1000       | 4         | 0.08%   |
| More than 2000 | 3         | 0.06%   |
| 1-100          | 3         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4218      | 89.42%  |
| 16/10   | 278       | 5.89%   |
| Unknown | 103       | 2.18%   |
| 4/3     | 28        | 0.59%   |
| 5/4     | 27        | 0.57%   |
| 21/9    | 27        | 0.57%   |
| 3/2     | 13        | 0.28%   |
| 6/5     | 6         | 0.13%   |
| 2.00    | 6         | 0.13%   |
| 1.00    | 3         | 0.06%   |
| 0.67    | 3         | 0.06%   |
| 0.56    | 3         | 0.06%   |
| 32/9    | 1         | 0.02%   |
| 3.40    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2133      | 42.3%   |
| 81-90          | 1161      | 23.02%  |
| 201-250        | 503       | 9.97%   |
| 141-150        | 259       | 5.14%   |
| 151-200        | 240       | 4.76%   |
| 71-80          | 127       | 2.52%   |
| 301-350        | 118       | 2.34%   |
| Unknown        | 110       | 2.18%   |
| 351-500        | 85        | 1.69%   |
| More than 1000 | 47        | 0.93%   |
| 61-70          | 45        | 0.89%   |
| 121-130        | 42        | 0.83%   |
| 111-120        | 42        | 0.83%   |
| 251-300        | 39        | 0.77%   |
| 501-1000       | 28        | 0.56%   |
| 51-60          | 22        | 0.44%   |
| 91-100         | 18        | 0.36%   |
| 131-140        | 11        | 0.22%   |
| 41-50          | 10        | 0.2%    |
| 1-40           | 3         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1919      | 38.5%   |
| 101-120       | 1599      | 32.08%  |
| 51-100        | 1015      | 20.37%  |
| 161-240       | 221       | 4.43%   |
| Unknown       | 110       | 2.21%   |
| More than 240 | 67        | 1.34%   |
| 1-50          | 53        | 1.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4380      | 88.2%   |
| 2     | 420       | 8.46%   |
| 0     | 156       | 3.14%   |
| 3     | 10        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3291      | 42.4%   |
| Intel                             | 2041      | 26.29%  |
| Qualcomm Atheros                  | 910       | 11.72%  |
| Broadcom                          | 315       | 4.06%   |
| MediaTek                          | 156       | 2.01%   |
| Ralink Technology                 | 139       | 1.79%   |
| Xiaomi                            | 115       | 1.48%   |
| TP-Link                           | 115       | 1.48%   |
| Ralink                            | 73        | 0.94%   |
| Samsung Electronics               | 72        | 0.93%   |
| OPPO Electronics                  | 71        | 0.91%   |
| Broadcom Limited                  | 62        | 0.8%    |
| Qualcomm                          | 50        | 0.64%   |
| D-Link                            | 36        | 0.46%   |
| Marvell Technology Group          | 34        | 0.44%   |
| ASIX Electronics                  | 33        | 0.43%   |
| OnePlus Technology (Shenzhen)     | 25        | 0.32%   |
| Huawei Technologies               | 24        | 0.31%   |
| Motorola PCS                      | 22        | 0.28%   |
| Qualcomm Atheros Communications   | 15        | 0.19%   |
| Foxconn / Hon Hai                 | 15        | 0.19%   |
| Nvidia                            | 14        | 0.18%   |
| Google                            | 11        | 0.14%   |
| ICS Advent                        | 10        | 0.13%   |
| vivo                              | 8         | 0.1%    |
| NetGear                           | 8         | 0.1%    |
| DisplayLink                       | 8         | 0.1%    |
| Lenovo                            | 7         | 0.09%   |
| JMicron Technology                | 7         | 0.09%   |
| Edimax Technology                 | 6         | 0.08%   |
| ASUSTek Computer                  | 6         | 0.08%   |
| NTmore                            | 5         | 0.06%   |
| HMD Global                        | 5         | 0.06%   |
| Dell                              | 5         | 0.06%   |
| Microchip Technology              | 4         | 0.05%   |
| D-Link System                     | 4         | 0.05%   |
| QinHeng Electronics               | 3         | 0.04%   |
| Ericsson Business Mobile Networks | 3         | 0.04%   |
| Aquantia                          | 3         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2149      | 23.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 728       | 8.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 324       | 3.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 190       | 2.1%    |
| Intel Wi-Fi 6 AX201                                                    | 184       | 2.04%   |
| Intel Wi-Fi 6 AX200                                                    | 169       | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 161       | 1.78%   |
| Intel Wireless 8265 / 8275                                             | 161       | 1.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 135       | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 126       | 1.39%   |
| Ralink MT7601U Wireless Adapter                                        | 121       | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 120       | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 114       | 1.26%   |
| Broadcom BCM43142 802.11b/g/n                                          | 111       | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 108       | 1.2%    |
| Realtek RTL8723DE Wireless Network Adapter                             | 107       | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 96        | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 96        | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 94        | 1.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 94        | 1.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 92        | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 90        | 1%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 89        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 89        | 0.99%   |
| Intel Wireless 7265                                                    | 88        | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 82        | 0.91%   |
| Intel Wireless 3165                                                    | 80        | 0.89%   |
| Intel Wireless 3160                                                    | 72        | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 68        | 0.75%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 63        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 62        | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 60        | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 57        | 0.63%   |
| Intel Wireless 8260                                                    | 55        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 52        | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 49        | 0.54%   |
| Realtek RTL8125 2.5GbE Controller                                      | 49        | 0.54%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 47        | 0.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 45        | 0.5%    |
| Intel Wireless 7260                                                    | 43        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1778      | 39.71%  |
| Realtek Semiconductor             | 1031      | 23.03%  |
| Qualcomm Atheros                  | 811       | 18.11%  |
| Broadcom                          | 264       | 5.9%    |
| Ralink Technology                 | 139       | 3.1%    |
| MediaTek                          | 136       | 3.04%   |
| TP-Link                           | 106       | 2.37%   |
| Ralink                            | 72        | 1.61%   |
| Broadcom Limited                  | 47        | 1.05%   |
| D-Link                            | 36        | 0.8%    |
| Qualcomm Atheros Communications   | 15        | 0.34%   |
| Qualcomm                          | 11        | 0.25%   |
| NetGear                           | 8         | 0.18%   |
| Edimax Technology                 | 6         | 0.13%   |
| Dell                              | 4         | 0.09%   |
| Sierra Wireless                   | 2         | 0.04%   |
| D-Link System                     | 2         | 0.04%   |
| ASUSTek Computer                  | 2         | 0.04%   |
| Wacom                             | 1         | 0.02%   |
| Philips (or NXP)                  | 1         | 0.02%   |
| Micro Star International          | 1         | 0.02%   |
| Marvell Technology Group          | 1         | 0.02%   |
| IMC Networks                      | 1         | 0.02%   |
| Ericsson Business Mobile Networks | 1         | 0.02%   |
| Belkin Components                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 324       | 7.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 190       | 4.23%   |
| Intel Wi-Fi 6 AX201                                            | 184       | 4.09%   |
| Intel Wi-Fi 6 AX200                                            | 169       | 3.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 161       | 3.58%   |
| Intel Wireless 8265 / 8275                                     | 161       | 3.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 135       | 3%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 126       | 2.8%    |
| Ralink MT7601U Wireless Adapter                                | 121       | 2.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 120       | 2.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 114       | 2.54%   |
| Broadcom BCM43142 802.11b/g/n                                  | 111       | 2.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 108       | 2.4%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 107       | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 96        | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 96        | 2.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 94        | 2.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 94        | 2.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 92        | 2.05%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 89        | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 89        | 1.98%   |
| Intel Wireless 7265                                            | 88        | 1.96%   |
| Intel Wireless 3165                                            | 80        | 1.78%   |
| Intel Wireless 3160                                            | 72        | 1.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 68        | 1.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 62        | 1.38%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 60        | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 57        | 1.27%   |
| Intel Wireless 8260                                            | 55        | 1.22%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 49        | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 47        | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 45        | 1%      |
| Intel Wireless 7260                                            | 43        | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 37        | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 36        | 0.8%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 34        | 0.76%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 27        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 27        | 0.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 24        | 0.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 22        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3000      | 67.66%  |
| Intel                            | 645       | 14.55%  |
| Qualcomm Atheros                 | 145       | 3.27%   |
| Xiaomi                           | 115       | 2.59%   |
| Broadcom                         | 78        | 1.76%   |
| Samsung Electronics              | 72        | 1.62%   |
| OPPO Electronics                 | 71        | 1.6%    |
| Qualcomm                         | 39        | 0.88%   |
| Marvell Technology Group         | 33        | 0.74%   |
| ASIX Electronics                 | 33        | 0.74%   |
| MediaTek                         | 22        | 0.5%    |
| Huawei Technologies              | 20        | 0.45%   |
| OnePlus Technology (Shenzhen)    | 19        | 0.43%   |
| Broadcom Limited                 | 15        | 0.34%   |
| Motorola PCS                     | 14        | 0.32%   |
| Nvidia                           | 12        | 0.27%   |
| Google                           | 11        | 0.25%   |
| TP-Link                          | 10        | 0.23%   |
| ICS Advent                       | 10        | 0.23%   |
| DisplayLink                      | 8         | 0.18%   |
| JMicron Technology               | 7         | 0.16%   |
| vivo                             | 6         | 0.14%   |
| Lenovo                           | 6         | 0.14%   |
| NTmore                           | 5         | 0.11%   |
| HMD Global                       | 5         | 0.11%   |
| Foxconn / Hon Hai                | 4         | 0.09%   |
| ASUSTek Computer                 | 4         | 0.09%   |
| Microchip Technology             | 3         | 0.07%   |
| Aquantia                         | 3         | 0.07%   |
| Spreadtrum Communications        | 2         | 0.05%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| D-Link System                    | 2         | 0.05%   |
| Attansic Technology              | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| VIA Technologies                 | 1         | 0.02%   |
| Standard Microsystems            | 1         | 0.02%   |
| LG Electronics                   | 1         | 0.02%   |
| LeEco                            | 1         | 0.02%   |
| HTC (High Tech Computer)         | 1         | 0.02%   |
| Emulex                           | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2149      | 47.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 728       | 16.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 90        | 2.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 82        | 1.83%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 63        | 1.4%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 52        | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                      | 49        | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                                  | 40        | 0.89%   |
| Intel Ethernet Connection I219-LM                                      | 37        | 0.82%   |
| Intel Ethernet Connection (4) I219-V                                   | 36        | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 33        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 32        | 0.71%   |
| Realtek Killer E2600 GbE Controller                                    | 32        | 0.71%   |
| Qualcomm Redmi 9T                                                      | 32        | 0.71%   |
| Intel Ethernet Connection I217-LM                                      | 31        | 0.69%   |
| Intel I211 Gigabit Network Connection                                  | 29        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                                   | 29        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                | 29        | 0.65%   |
| Intel Ethernet Connection I218-LM                                      | 28        | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                          | 27        | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 23        | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 22        | 0.49%   |
| Intel Ethernet Controller I225-V                                       | 22        | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                                  | 21        | 0.47%   |
| OnePlus (Shenzhen) Android                                             | 19        | 0.42%   |
| Intel 82577LM Gigabit Network Connection                               | 18        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                                  | 17        | 0.38%   |
| Intel Ethernet Connection (10) I219-V                                  | 17        | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 16        | 0.36%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 16        | 0.36%   |
| MediaTek File-CD Gadget                                                | 16        | 0.36%   |
| Intel Ethernet Connection (7) I219-V                                   | 16        | 0.36%   |
| Intel Ethernet Connection (6) I219-V                                   | 16        | 0.36%   |
| Intel Ethernet Connection (6) I219-LM                                  | 15        | 0.33%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 0.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 15        | 0.33%   |
| Motorola PCS moto g52                                                  | 14        | 0.31%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 14        | 0.31%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 13        | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 13        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4309      | 51.42%  |
| Ethernet | 4019      | 47.96%  |
| Unknown  | 33        | 0.39%   |
| Modem    | 19        | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3565      | 73.05%  |
| Ethernet | 1310      | 26.84%  |
| Unknown  | 4         | 0.08%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2949      | 60.04%  |
| 1     | 1842      | 37.5%   |
| 0     | 71        | 1.45%   |
| 3     | 38        | 0.77%   |
| 4     | 8         | 0.16%   |
| 6     | 2         | 0.04%   |
| 10    | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3919      | 78.41%  |
| Yes  | 1079      | 21.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1562      | 42.25%  |
| Realtek Semiconductor           | 595       | 16.09%  |
| Qualcomm Atheros Communications | 498       | 13.47%  |
| IMC Networks                    | 195       | 5.27%   |
| Broadcom                        | 177       | 4.79%   |
| Cambridge Silicon Radio         | 150       | 4.06%   |
| Lite-On Technology              | 142       | 3.84%   |
| Foxconn / Hon Hai               | 120       | 3.25%   |
| Ralink                          | 57        | 1.54%   |
| Dell                            | 39        | 1.05%   |
| Apple                           | 37        | 1%      |
| TP-Link                         | 25        | 0.68%   |
| Hewlett-Packard                 | 18        | 0.49%   |
| MediaTek                        | 16        | 0.43%   |
| Toshiba                         | 10        | 0.27%   |
| Foxconn International           | 10        | 0.27%   |
| ASUSTek Computer                | 9         | 0.24%   |
| Realtek                         | 8         | 0.22%   |
| Ralink Technology               | 7         | 0.19%   |
| Opticis                         | 5         | 0.14%   |
| Integrated System Solution      | 4         | 0.11%   |
| USI                             | 3         | 0.08%   |
| SINO WEALTH                     | 2         | 0.05%   |
| Chicony Electronics             | 2         | 0.05%   |
| Unknown                         | 2         | 0.05%   |
| Micro Star International        | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |
| Alps Electric                   | 1         | 0.03%   |
| Accel Semiconductor             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 487       | 13.17%  |
| Realtek Bluetooth Radio                                                             | 401       | 10.84%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 350       | 9.46%   |
| Intel AX201 Bluetooth                                                               | 343       | 9.28%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 299       | 8.09%   |
| Intel AX200 Bluetooth                                                               | 165       | 4.46%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 157       | 4.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 150       | 4.06%   |
| Intel Bluetooth Device                                                              | 106       | 2.87%   |
| IMC Networks Bluetooth Radio                                                        | 70        | 1.89%   |
| IMC Networks Wireless_Device                                                        | 66        | 1.78%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 59        | 1.6%    |
| Ralink RT3290 Bluetooth                                                             | 57        | 1.54%   |
| IMC Networks Bluetooth Device                                                       | 56        | 1.51%   |
| Lite-On Bluetooth Device                                                            | 51        | 1.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 49        | 1.33%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 46        | 1.24%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 43        | 1.16%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 43        | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 39        | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 33        | 0.89%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 33        | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 30        | 0.81%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 26        | 0.7%    |
| TP-Link UB500 Adapter                                                               | 25        | 0.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 24        | 0.65%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 24        | 0.65%   |
| Apple Bluetooth USB Host Controller                                                 | 19        | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 18        | 0.49%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 18        | 0.49%   |
| Realtek RTL8723B Bluetooth                                                          | 17        | 0.46%   |
| Lite-On Wireless_Device                                                             | 17        | 0.46%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 17        | 0.46%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 16        | 0.43%   |
| Intel AX210 Bluetooth                                                               | 15        | 0.41%   |
| Dell Wireless 365 Bluetooth                                                         | 13        | 0.35%   |
| MediaTek Wireless_Device                                                            | 12        | 0.32%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.32%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 12        | 0.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 12        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3827      | 64.19%  |
| AMD                                          | 1064      | 17.85%  |
| Nvidia                                       | 826       | 13.85%  |
| C-Media Electronics                          | 41        | 0.69%   |
| GN Netcom                                    | 21        | 0.35%   |
| Creative Labs                                | 13        | 0.22%   |
| Texas Instruments                            | 10        | 0.17%   |
| Realtek Semiconductor                        | 10        | 0.17%   |
| JMTek                                        | 10        | 0.17%   |
| Plantronics                                  | 9         | 0.15%   |
| Generalplus Technology                       | 9         | 0.15%   |
| ASUSTek Computer                             | 9         | 0.15%   |
| Logitech                                     | 7         | 0.12%   |
| Tenx Technology                              | 6         | 0.1%    |
| Creative Technology                          | 6         | 0.1%    |
| OPPO Electronics                             | 5         | 0.08%   |
| SteelSeries ApS                              | 4         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.07%   |
| Sennheiser Communications                    | 4         | 0.07%   |
| Micro Star International                     | 4         | 0.07%   |
| M-Audio                                      | 3         | 0.05%   |
| Lenovo                                       | 3         | 0.05%   |
| Hewlett-Packard                              | 3         | 0.05%   |
| DSEA A/S                                     | 3         | 0.05%   |
| Corsair                                      | 3         | 0.05%   |
| BR23                                         | 3         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| YSTEK Technology                             | 2         | 0.03%   |
| Samson Technologies                          | 2         | 0.03%   |
| KTMicro                                      | 2         | 0.03%   |
| Kingston Technology                          | 2         | 0.03%   |
| GYROCOM C&C                                  | 2         | 0.03%   |
| Giga-Byte Technology                         | 2         | 0.03%   |
| Focusrite-Novation                           | 2         | 0.03%   |
| ClearOne Communications                      | 2         | 0.03%   |
| Cambridge Silicon Radio                      | 2         | 0.03%   |
| Apple                                        | 2         | 0.03%   |
| ZOOM                                         | 1         | 0.02%   |
| Yamaha                                       | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 694       | 9.6%    |
| AMD Family 17h/19h HD Audio Controller                                     | 610       | 8.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 292       | 4.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 289       | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 266       | 3.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 254       | 3.51%   |
| Intel Cannon Lake PCH cAVS                                                 | 219       | 3.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 211       | 2.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 203       | 2.81%   |
| Intel 8 Series HD Audio Controller                                         | 201       | 2.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 199       | 2.75%   |
| Intel Comet Lake PCH-LP cAVS                                               | 177       | 2.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 173       | 2.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 160       | 2.21%   |
| Intel Broadwell-U Audio Controller                                         | 148       | 2.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 147       | 2.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 147       | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 135       | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 129       | 1.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 115       | 1.59%   |
| AMD FCH Azalia Controller                                                  | 115       | 1.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 111       | 1.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 110       | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 96        | 1.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 87        | 1.2%    |
| Intel Comet Lake PCH cAVS                                                  | 78        | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                   | 78        | 1.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 71        | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 70        | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 70        | 0.97%   |
| AMD High Definition Audio Controller                                       | 69        | 0.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 67        | 0.93%   |
| Nvidia Audio device                                                        | 61        | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 56        | 0.77%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 54        | 0.75%   |
| Nvidia High Definition Audio Controller                                    | 45        | 0.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 44        | 0.61%   |
| Nvidia GA106 High Definition Audio Controller                              | 42        | 0.58%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 41        | 0.57%   |
| Intel CM238 HD Audio Controller                                            | 39        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 885       | 26.65%  |
| SK hynix                     | 776       | 23.37%  |
| Micron Technology            | 431       | 12.98%  |
| Kingston                     | 283       | 8.52%   |
| Crucial                      | 195       | 5.87%   |
| Unknown                      | 155       | 4.67%   |
| A-DATA Technology            | 124       | 3.73%   |
| Corsair                      | 118       | 3.55%   |
| Ramaxel Technology           | 107       | 3.22%   |
| Transcend                    | 61        | 1.84%   |
| G.Skill                      | 39        | 1.17%   |
| CSX                          | 31        | 0.93%   |
| Nanya Technology             | 23        | 0.69%   |
| Elpida                       | 22        | 0.66%   |
| Unknown                      | 15        | 0.45%   |
| Unknown (ABCD)               | 8         | 0.24%   |
| OM Nanotech                  | 6         | 0.18%   |
| Silicon Power                | 5         | 0.15%   |
| ZION                         | 3         | 0.09%   |
| Avant                        | 3         | 0.09%   |
| Unknown (0x0CDC)             | 2         | 0.06%   |
| Team                         | 2         | 0.06%   |
| Kllisre                      | 2         | 0.06%   |
| Gold Key                     | 2         | 0.06%   |
| ASint Technology             | 2         | 0.06%   |
| Apacer                       | 2         | 0.06%   |
| Unknown (0xAD44594E45540000) | 1         | 0.03%   |
| Unknown (0x1007)             | 1         | 0.03%   |
| Unknown (0x0CAB)             | 1         | 0.03%   |
| Unknown (0x0080)             | 1         | 0.03%   |
| Unknown (09D5)               | 1         | 0.03%   |
| Unknown (07F7)               | 1         | 0.03%   |
| Strontium                    | 1         | 0.03%   |
| SHARETRONIC                  | 1         | 0.03%   |
| Ramos Technology             | 1         | 0.03%   |
| Qumo                         | 1         | 0.03%   |
| Qimonda                      | 1         | 0.03%   |
| Patriot Memory (PDP Systems) | 1         | 0.03%   |
| NETSOL                       | 1         | 0.03%   |
| Lexar Co Limited             | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s    | 74        | 2.11%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 62        | 1.77%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 59        | 1.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 48        | 1.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 43        | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 42        | 1.2%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 41        | 1.17%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 40        | 1.14%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 38        | 1.08%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 37        | 1.06%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 36        | 1.03%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 36        | 1.03%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 33        | 0.94%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 32        | 0.91%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s        | 32        | 0.91%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 30        | 0.86%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 29        | 0.83%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 29        | 0.83%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s    | 29        | 0.83%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 29        | 0.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 29        | 0.83%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 27        | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 25        | 0.71%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 25        | 0.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 23        | 0.66%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 23        | 0.66%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 22        | 0.63%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 21        | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 18        | 0.51%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                    | 17        | 0.49%   |
| Crucial RAM CB8GS2400.C8ET 8GB SODIMM DDR4 2667MT/s         | 17        | 0.49%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s      | 17        | 0.49%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 16        | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 16        | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 15        | 0.43%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 15        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 15        | 0.43%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s        | 15        | 0.43%   |
| Corsair RAM CMK16GX4M1E3200C16 16GB DIMM DDR4 3200MT/s      | 15        | 0.43%   |
| Unknown                                                     | 15        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1724      | 62.9%   |
| DDR3    | 669       | 24.41%  |
| LPDDR4  | 103       | 3.76%   |
| SDRAM   | 65        | 2.37%   |
| DDR2    | 50        | 1.82%   |
| DDR5    | 42        | 1.53%   |
| LPDDR3  | 31        | 1.13%   |
| LPDDR5  | 26        | 0.95%   |
| Unknown | 24        | 0.88%   |
| DDR     | 6         | 0.22%   |
| DRAM    | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2005      | 73.63%  |
| DIMM         | 507       | 18.62%  |
| Row Of Chips | 202       | 7.42%   |
| Chip         | 4         | 0.15%   |
| Unknown      | 3         | 0.11%   |
| RIMM         | 2         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1405      | 46.62%  |
| 4096  | 876       | 29.06%  |
| 16384 | 384       | 12.74%  |
| 2048  | 250       | 8.29%   |
| 32768 | 53        | 1.76%   |
| 1024  | 40        | 1.33%   |
| 512   | 4         | 0.13%   |
| 1536  | 1         | 0.03%   |
| 256   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 714       | 23.98%  |
| 3200    | 701       | 23.55%  |
| 1600    | 505       | 16.96%  |
| 2400    | 246       | 8.26%   |
| 1333    | 123       | 4.13%   |
| 2133    | 101       | 3.39%   |
| 3266    | 74        | 2.49%   |
| 1334    | 65        | 2.18%   |
| Unknown | 41        | 1.38%   |
| 3600    | 39        | 1.31%   |
| 4267    | 33        | 1.11%   |
| 2666    | 32        | 1.07%   |
| 4800    | 31        | 1.04%   |
| 667     | 31        | 1.04%   |
| 6400    | 27        | 0.91%   |
| 1067    | 24        | 0.81%   |
| 4199    | 20        | 0.67%   |
| 3066    | 19        | 0.64%   |
| 3000    | 18        | 0.6%    |
| 800     | 18        | 0.6%    |
| 1867    | 16        | 0.54%   |
| 975     | 14        | 0.47%   |
| 1866    | 8         | 0.27%   |
| 3733    | 7         | 0.24%   |
| 2048    | 7         | 0.24%   |
| 8400    | 4         | 0.13%   |
| 6000    | 4         | 0.13%   |
| 4266    | 4         | 0.13%   |
| 3400    | 4         | 0.13%   |
| 1800    | 4         | 0.13%   |
| 5600    | 3         | 0.1%    |
| 5200    | 3         | 0.1%    |
| 3866    | 3         | 0.1%    |
| 3666    | 3         | 0.1%    |
| 2800    | 3         | 0.1%    |
| 1648    | 3         | 0.1%    |
| 3466    | 2         | 0.07%   |
| 2933    | 2         | 0.07%   |
| 2000    | 2         | 0.07%   |
| 1066    | 2         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 22        | 41.51%  |
| Seiko Epson         | 13        | 24.53%  |
| Canon               | 9         | 16.98%  |
| Brother Industries  | 5         | 9.43%   |
| STMicroelectronics  | 1         | 1.89%   |
| Samsung Electronics | 1         | 1.89%   |
| Ricoh               | 1         | 1.89%   |
| Konica Minolta      | 1         | 1.89%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                                      | 6         | 11.32%  |
| HP Ink Tank 310 series                                                | 4         | 7.55%   |
| Canon PIXMA MG2500 Series                                             | 3         | 5.66%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 2         | 3.77%   |
| Seiko Epson L382 Series                                               | 2         | 3.77%   |
| HP DeskJet 2130 series                                                | 2         | 3.77%   |
| HP DeskJet 1110 series                                                | 2         | 3.77%   |
| Canon LBP2900                                                         | 2         | 3.77%   |
| STMicroelectronics USB Printing Support                               | 1         | 1.89%   |
| Seiko Epson USB2.0 Printer                                            | 1         | 1.89%   |
| Seiko Epson M100 Series                                               | 1         | 1.89%   |
| Seiko Epson L6160 Series                                              | 1         | 1.89%   |
| Seiko Epson L405 Series                                               | 1         | 1.89%   |
| Seiko Epson L360 Series                                               | 1         | 1.89%   |
| Seiko Epson L3200 Series                                              | 1         | 1.89%   |
| Seiko Epson L3150 Series                                              | 1         | 1.89%   |
| Seiko Epson L3110 Series                                              | 1         | 1.89%   |
| Seiko Epson L132 Series                                               | 1         | 1.89%   |
| Samsung ML-1640 Series Laser Printer                                  | 1         | 1.89%   |
| Ricoh SP 112SU                                                        | 1         | 1.89%   |
| Konica Minolta 206                                                    | 1         | 1.89%   |
| HP Smart Install                                                      | 1         | 1.89%   |
| HP Printing Support                                                   | 1         | 1.89%   |
| HP LaserJet Professional P1566                                        | 1         | 1.89%   |
| HP LaserJet Pro M201dw                                                | 1         | 1.89%   |
| HP LaserJet P1102                                                     | 1         | 1.89%   |
| HP DeskJet 3630 series                                                | 1         | 1.89%   |
| HP DeskJet 2600 series                                                | 1         | 1.89%   |
| HP Deskjet 1510                                                       | 1         | 1.89%   |
| Canon PIXMA MP280                                                     | 1         | 1.89%   |
| Canon PIXMA MP190                                                     | 1         | 1.89%   |
| Canon MF4800 Series                                                   | 1         | 1.89%   |
| Canon G2000 series                                                    | 1         | 1.89%   |
| Brother Printer                                                       | 1         | 1.89%   |
| Brother HL-L2320D series                                              | 1         | 1.89%   |
| Brother DCP-T510W                                                     | 1         | 1.89%   |
| Brother DCP-T310                                                      | 1         | 1.89%   |
| Brother DCP-L2520D                                                    | 1         | 1.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 75%     |
| Seiko Epson     | 1         | 12.5%   |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                     | 5         | 62.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| HP ScanJet 2200c                            | 1         | 12.5%   |
| Canon CanoScan LiDE 120                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 657       | 17.9%   |
| IMC Networks                           | 528       | 14.39%  |
| Realtek Semiconductor                  | 362       | 9.86%   |
| Microdia                               | 362       | 9.86%   |
| Quanta                                 | 262       | 7.14%   |
| Sunplus Innovation Technology          | 209       | 5.69%   |
| Bison Electronics                      | 184       | 5.01%   |
| Cheng Uei Precision Industry (Foxlink) | 180       | 4.9%    |
| Syntek                                 | 142       | 3.87%   |
| Suyin                                  | 132       | 3.6%    |
| Luxvisions Innotech Limited            | 95        | 2.59%   |
| Logitech                               | 70        | 1.91%   |
| Acer                                   | 69        | 1.88%   |
| Lite-On Technology                     | 67        | 1.83%   |
| Sonix Technology                       | 42        | 1.14%   |
| Alcor Micro                            | 36        | 0.98%   |
| Apple                                  | 31        | 0.84%   |
| Samsung Electronics                    | 25        | 0.68%   |
| Silicon Motion                         | 22        | 0.6%    |
| Ricoh                                  | 15        | 0.41%   |
| Lenovo                                 | 14        | 0.38%   |
| Importek                               | 13        | 0.35%   |
| Z-Star Microelectronics                | 11        | 0.3%    |
| Primax Electronics                     | 10        | 0.27%   |
| Unknown                                | 9         | 0.25%   |
| OmniVision Technologies                | 9         | 0.25%   |
| OPPO Electronics                       | 8         | 0.22%   |
| SunplusIT                              | 7         | 0.19%   |
| Microsoft                              | 7         | 0.19%   |
| Arkmicro Technologies                  | 7         | 0.19%   |
| GEMBIRD                                | 6         | 0.16%   |
| 8SSC20F27114V1SR0BK1X4S                | 6         | 0.16%   |
| MacroSilicon                           | 5         | 0.14%   |
| Intel                                  | 5         | 0.14%   |
| Hewlett-Packard                        | 5         | 0.14%   |
| Pixart Imaging                         | 4         | 0.11%   |
| MSD                                    | 4         | 0.11%   |
| Cubeternet                             | 4         | 0.11%   |
| vivo                                   | 3         | 0.08%   |
| Jieli Technology                       | 3         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 184       | 5.01%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 183       | 4.98%   |
| Realtek Integrated_Webcam_HD                                   | 153       | 4.16%   |
| IMC Networks Integrated Camera                                 | 144       | 3.92%   |
| Chicony Integrated Camera                                      | 138       | 3.76%   |
| Sunplus Integrated_Webcam_HD                                   | 100       | 2.72%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 90        | 2.45%   |
| Syntek Integrated Camera                                       | 84        | 2.29%   |
| Chicony HP TrueVision HD Camera                                | 68        | 1.85%   |
| Realtek Integrated Webcam                                      | 61        | 1.66%   |
| Chicony HP TrueVision HD                                       | 61        | 1.66%   |
| Bison Integrated Camera                                        | 60        | 1.63%   |
| Quanta HP TrueVision HD Camera                                 | 52        | 1.41%   |
| Chicony EasyCamera                                             | 50        | 1.36%   |
| Chicony HD WebCam                                              | 48        | 1.31%   |
| Quanta HD User Facing                                          | 47        | 1.28%   |
| Suyin HP Truevision HD                                         | 45        | 1.22%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 42        | 1.14%   |
| Logitech Webcam C270                                           | 40        | 1.09%   |
| Quanta HP Wide Vision HD Camera                                | 39        | 1.06%   |
| Chicony HP Wide Vision HD Camera                               | 36        | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD        | 35        | 0.95%   |
| Syntek EasyCamera                                              | 34        | 0.93%   |
| Chicony HD User Facing                                         | 34        | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 34        | 0.93%   |
| Bison EasyCamera                                               | 34        | 0.93%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 33        | 0.9%    |
| Sonix USB2.0 HD UVC WebCam                                     | 32        | 0.87%   |
| Quanta HD Webcam                                               | 29        | 0.79%   |
| Lite-On Integrated Camera                                      | 29        | 0.79%   |
| IMC Networks HP TrueVision HD Camera                           | 29        | 0.79%   |
| Bison Lenovo EasyCamera                                        | 29        | 0.79%   |
| Quanta ACER HD User Facing                                     | 27        | 0.73%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 27        | 0.73%   |
| Suyin Integrated_Webcam_HD                                     | 25        | 0.68%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 25        | 0.68%   |
| Microdia Integrated Webcam                                     | 24        | 0.65%   |
| Acer SunplusIT Integrated Camera                               | 24        | 0.65%   |
| Realtek EasyCamera                                             | 23        | 0.63%   |
| Microdia USB 2.0 Camera                                        | 23        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 198       | 28.99%  |
| Synaptics                          | 166       | 24.3%   |
| Shenzhen Goodix Technology         | 139       | 20.35%  |
| Elan Microelectronics              | 104       | 15.23%  |
| LighTuning Technology              | 23        | 3.37%   |
| Realtek USB2.0 Finger Print Bridge | 21        | 3.07%   |
| AuthenTec                          | 12        | 1.76%   |
| Upek                               | 11        | 1.61%   |
| Focal-systems.Corp                 | 6         | 0.88%   |
| STMicroelectronics                 | 1         | 0.15%   |
| Futronic Technology                | 1         | 0.15%   |
| DigitalPersona                     | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 77        | 11.27%  |
| Elan ELAN:ARM-M4                                                           | 67        | 9.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 56        | 8.2%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 55        | 8.05%   |
| Elan ELAN:Fingerprint                                                      | 34        | 4.98%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 4.1%    |
| Synaptics WBDI                                                             | 27        | 3.95%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 25        | 3.66%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 25        | 3.66%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 3.37%   |
| Synaptics UWP WBDI                                                         | 22        | 3.22%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 21        | 3.07%   |
| Synaptics  WBDI                                                            | 20        | 2.93%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 2.93%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 16        | 2.34%   |
| Synaptics Fingerprint scanner                                              | 15        | 2.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 1.9%    |
| Validity Sensors VFS Fingerprint sensor                                    | 12        | 1.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.76%   |
| Validity Sensors VFS491                                                    | 11        | 1.61%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 1.46%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 1.32%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.02%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 0.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 0.88%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 0.88%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 0.88%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 0.88%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 6         | 0.88%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 0.73%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 0.73%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.73%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 0.59%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 3         | 0.44%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.44%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.29%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.29%   |
| Synaptics TouchPad                                                         | 2         | 0.29%   |
| AuthenTec AES2810                                                          | 2         | 0.29%   |
| AuthenTec AES1600                                                          | 2         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 72        | 64.86%  |
| Alcor Micro           | 21        | 18.92%  |
| Upek                  | 8         | 7.21%   |
| O2 Micro              | 4         | 3.6%    |
| Lenovo                | 3         | 2.7%    |
| Yubico.com            | 1         | 0.9%    |
| Gemalto (was Gemplus) | 1         | 0.9%    |
| Clay Logic            | 1         | 0.9%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 25        | 22.32%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 21        | 18.75%  |
| Broadcom 5880                                                                | 20        | 17.86%  |
| Broadcom 58200                                                               | 15        | 13.39%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 11.61%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2.68%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.68%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.89%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.89%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.89%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.89%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3349      | 66.66%  |
| 1     | 1389      | 27.65%  |
| 2     | 230       | 4.58%   |
| 3     | 30        | 0.6%    |
| 4     | 14        | 0.28%   |
| 5     | 7         | 0.14%   |
| 6     | 3         | 0.06%   |
| 9     | 2         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 678       | 34.29%  |
| Graphics card            | 458       | 23.17%  |
| Net/wireless             | 296       | 14.97%  |
| Chipcard                 | 104       | 5.26%   |
| Multimedia controller    | 103       | 5.21%   |
| Bluetooth                | 93        | 4.7%    |
| Camera                   | 70        | 3.54%   |
| Communication controller | 65        | 3.29%   |
| Sound                    | 27        | 1.37%   |
| Net/ethernet             | 27        | 1.37%   |
| Storage                  | 16        | 0.81%   |
| Unassigned class         | 13        | 0.66%   |
| Network                  | 10        | 0.51%   |
| Modem                    | 7         | 0.35%   |
| Card reader              | 5         | 0.25%   |
| Storage/ide              | 2         | 0.1%    |
| Storage/raid             | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |

