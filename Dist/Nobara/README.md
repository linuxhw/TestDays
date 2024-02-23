Nobara - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Nobara.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Nobara/Desktop/README.md) and [notebooks](/Dist/Nobara/Notebook/README.md).

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

Total: 1119

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite L55-C             | Notebook    | [f32d9dc51a](https://linux-hardware.org/?probe=f32d9dc51a) | Feb 02, 2024 |
| Acer          | Aspire A315-54              | Notebook    | [3621142f4d](https://linux-hardware.org/?probe=3621142f4d) | Feb 02, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [d4c61a6527](https://linux-hardware.org/?probe=d4c61a6527) | Feb 01, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [f708da8a98](https://linux-hardware.org/?probe=f708da8a98) | Feb 01, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [8b5fd80f76](https://linux-hardware.org/?probe=8b5fd80f76) | Feb 01, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [31fc253b87](https://linux-hardware.org/?probe=31fc253b87) | Feb 01, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [52f18f604d](https://linux-hardware.org/?probe=52f18f604d) | Feb 01, 2024 |
| Intel         | B75                         | Desktop     | [000ad7f808](https://linux-hardware.org/?probe=000ad7f808) | Jan 31, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [02a1844f63](https://linux-hardware.org/?probe=02a1844f63) | Jan 31, 2024 |
| Toshiba       | Satellite C55-B             | Notebook    | [cfd7031cd9](https://linux-hardware.org/?probe=cfd7031cd9) | Jan 31, 2024 |
| MSI           | GE62 6QE                    | Notebook    | [6d6f9ba002](https://linux-hardware.org/?probe=6d6f9ba002) | Jan 30, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [df2c10b408](https://linux-hardware.org/?probe=df2c10b408) | Jan 29, 2024 |
| HP            | 1497                        | Desktop     | [edbda38746](https://linux-hardware.org/?probe=edbda38746) | Jan 29, 2024 |
| HP            | 212B                        | Desktop     | [fb3993d66a](https://linux-hardware.org/?probe=fb3993d66a) | Jan 28, 2024 |
| NZXT          | N7 B650E                    | Desktop     | [2a31518f97](https://linux-hardware.org/?probe=2a31518f97) | Jan 28, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a85c3034f2](https://linux-hardware.org/?probe=a85c3034f2) | Jan 27, 2024 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [88efa5aca1](https://linux-hardware.org/?probe=88efa5aca1) | Jan 27, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [68364930e7](https://linux-hardware.org/?probe=68364930e7) | Jan 27, 2024 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [96bce63bad](https://linux-hardware.org/?probe=96bce63bad) | Jan 27, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [c1267550bc](https://linux-hardware.org/?probe=c1267550bc) | Jan 27, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [531cd352a8](https://linux-hardware.org/?probe=531cd352a8) | Jan 27, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [840164bd48](https://linux-hardware.org/?probe=840164bd48) | Jan 27, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [30139ed46d](https://linux-hardware.org/?probe=30139ed46d) | Jan 27, 2024 |
| Unknown       | Unknown                     | Notebook    | [9e979ee4e4](https://linux-hardware.org/?probe=9e979ee4e4) | Jan 26, 2024 |
| Unknown       | Unknown                     | Notebook    | [3e9fd3e31a](https://linux-hardware.org/?probe=3e9fd3e31a) | Jan 26, 2024 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Desktop     | [13a3740810](https://linux-hardware.org/?probe=13a3740810) | Jan 26, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [04feb5fc7d](https://linux-hardware.org/?probe=04feb5fc7d) | Jan 26, 2024 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [cb67574020](https://linux-hardware.org/?probe=cb67574020) | Jan 26, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | Notebook    | [ec87598c40](https://linux-hardware.org/?probe=ec87598c40) | Jan 26, 2024 |
| ASRock        | B550 Pro4                   | Desktop     | [e6dfa57418](https://linux-hardware.org/?probe=e6dfa57418) | Jan 26, 2024 |
| ASRock        | Z97 Anniversary             | Desktop     | [0973057025](https://linux-hardware.org/?probe=0973057025) | Jan 25, 2024 |
| NZXT          | N7 B650E                    | Desktop     | [9354117703](https://linux-hardware.org/?probe=9354117703) | Jan 25, 2024 |
| Gigabyte      | H510M H                     | Notebook    | [88b87b3353](https://linux-hardware.org/?probe=88b87b3353) | Jan 22, 2024 |
| HP            | Laptop 17z-cp000            | Notebook    | [51e7d942bc](https://linux-hardware.org/?probe=51e7d942bc) | Jan 22, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [871f86a545](https://linux-hardware.org/?probe=871f86a545) | Jan 21, 2024 |
| Pegatron      | 2AB6                        | Desktop     | [660b2b76ed](https://linux-hardware.org/?probe=660b2b76ed) | Jan 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f7ebff5e4f](https://linux-hardware.org/?probe=f7ebff5e4f) | Jan 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [e07a558ed5](https://linux-hardware.org/?probe=e07a558ed5) | Jan 20, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [12e32cbc19](https://linux-hardware.org/?probe=12e32cbc19) | Jan 19, 2024 |
| Gigabyte      | A5 K1                       | Notebook    | [219882fa36](https://linux-hardware.org/?probe=219882fa36) | Jan 19, 2024 |
| Gigabyte      | A5 K1                       | Notebook    | [2270b0b961](https://linux-hardware.org/?probe=2270b0b961) | Jan 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [96aa415cee](https://linux-hardware.org/?probe=96aa415cee) | Jan 18, 2024 |
| Lenovo        | ThinkPad X131e 3371AF5      | Notebook    | [1741e3b346](https://linux-hardware.org/?probe=1741e3b346) | Jan 18, 2024 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d732f80c75](https://linux-hardware.org/?probe=d732f80c75) | Jan 18, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [195a26ad26](https://linux-hardware.org/?probe=195a26ad26) | Jan 17, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b4bb61edfe](https://linux-hardware.org/?probe=b4bb61edfe) | Jan 17, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [781a81dea6](https://linux-hardware.org/?probe=781a81dea6) | Jan 17, 2024 |
| MSI           | Z170-A PRO                  | Desktop     | [bcf19edc1d](https://linux-hardware.org/?probe=bcf19edc1d) | Jan 16, 2024 |
| ASUSTek       | Q87M-E                      | Desktop     | [318aab51d9](https://linux-hardware.org/?probe=318aab51d9) | Jan 15, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c8e849a73](https://linux-hardware.org/?probe=0c8e849a73) | Jan 15, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [3ea676a743](https://linux-hardware.org/?probe=3ea676a743) | Jan 14, 2024 |
| Dell          | 0DYHRY A00                  | Desktop     | [d605dd9a8a](https://linux-hardware.org/?probe=d605dd9a8a) | Jan 14, 2024 |
| Digibras      | NH4CU03                     | Notebook    | [7cccdf824c](https://linux-hardware.org/?probe=7cccdf824c) | Jan 13, 2024 |
| ASRock        | Z97M Pro4                   | Desktop     | [594754cd87](https://linux-hardware.org/?probe=594754cd87) | Jan 13, 2024 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [a3bc588c07](https://linux-hardware.org/?probe=a3bc588c07) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [23c4e3e208](https://linux-hardware.org/?probe=23c4e3e208) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b98091e5e6](https://linux-hardware.org/?probe=b98091e5e6) | Jan 13, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [e3c1908003](https://linux-hardware.org/?probe=e3c1908003) | Jan 13, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [1b25ee0779](https://linux-hardware.org/?probe=1b25ee0779) | Jan 13, 2024 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [e1560ce8a3](https://linux-hardware.org/?probe=e1560ce8a3) | Jan 13, 2024 |
| ASUSTek       | ROG Strix G733ZM_G733ZM     | Notebook    | [e4f7fe0969](https://linux-hardware.org/?probe=e4f7fe0969) | Jan 13, 2024 |
| ASRock        | X570 Steel Legend           | Notebook    | [2dc1dca01f](https://linux-hardware.org/?probe=2dc1dca01f) | Jan 13, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [bcbcc04761](https://linux-hardware.org/?probe=bcbcc04761) | Jan 13, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5de7f8ed8](https://linux-hardware.org/?probe=e5de7f8ed8) | Jan 13, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [daefd59105](https://linux-hardware.org/?probe=daefd59105) | Jan 13, 2024 |
| Intel         | X79G V2.x                   | Desktop     | [cf61b1759b](https://linux-hardware.org/?probe=cf61b1759b) | Jan 12, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [5f11aaf980](https://linux-hardware.org/?probe=5f11aaf980) | Jan 12, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8e72c34b9e](https://linux-hardware.org/?probe=8e72c34b9e) | Jan 11, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b0705704b0](https://linux-hardware.org/?probe=b0705704b0) | Jan 11, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [2a5022eba4](https://linux-hardware.org/?probe=2a5022eba4) | Jan 11, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [7c77830f2f](https://linux-hardware.org/?probe=7c77830f2f) | Jan 10, 2024 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [03202bdde9](https://linux-hardware.org/?probe=03202bdde9) | Jan 10, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0df1250b28](https://linux-hardware.org/?probe=0df1250b28) | Jan 10, 2024 |
| Intel         | NUC11PABi5 M68265-400       | Mini pc     | [f6c6a9ba46](https://linux-hardware.org/?probe=f6c6a9ba46) | Jan 10, 2024 |
| ASUSTek       | G10DK                       | Desktop     | [7339bf1ed8](https://linux-hardware.org/?probe=7339bf1ed8) | Jan 09, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [9cfcebcd8c](https://linux-hardware.org/?probe=9cfcebcd8c) | Jan 09, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [0306a42404](https://linux-hardware.org/?probe=0306a42404) | Jan 09, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e1d9aaa0f2](https://linux-hardware.org/?probe=e1d9aaa0f2) | Jan 09, 2024 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [cd8ee8db1f](https://linux-hardware.org/?probe=cd8ee8db1f) | Jan 09, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [fc9099926d](https://linux-hardware.org/?probe=fc9099926d) | Jan 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [91485ca232](https://linux-hardware.org/?probe=91485ca232) | Jan 09, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ce4125a4f0](https://linux-hardware.org/?probe=ce4125a4f0) | Jan 09, 2024 |
| Dell          | Latitude E6440              | Notebook    | [bb917628b1](https://linux-hardware.org/?probe=bb917628b1) | Jan 09, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [513efe6ed6](https://linux-hardware.org/?probe=513efe6ed6) | Jan 09, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | Notebook    | [9ff97bbae7](https://linux-hardware.org/?probe=9ff97bbae7) | Jan 09, 2024 |
| HP            | 8054                        | Desktop     | [94be81d143](https://linux-hardware.org/?probe=94be81d143) | Jan 08, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [d9dc289509](https://linux-hardware.org/?probe=d9dc289509) | Jan 08, 2024 |
| HP            | ENVY TS 14 Sleekbook        | Notebook    | [48871db703](https://linux-hardware.org/?probe=48871db703) | Jan 08, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [1c83544337](https://linux-hardware.org/?probe=1c83544337) | Jan 08, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [4e246bdbaa](https://linux-hardware.org/?probe=4e246bdbaa) | Jan 07, 2024 |
| Alienware     | 0P0JWX A00                  | Desktop     | [47bd2f6e34](https://linux-hardware.org/?probe=47bd2f6e34) | Jan 07, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [ea0e1750c9](https://linux-hardware.org/?probe=ea0e1750c9) | Jan 06, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [6a8402b6a7](https://linux-hardware.org/?probe=6a8402b6a7) | Jan 06, 2024 |
| ASUSTek       | ROG Strix G733ZM_G733ZM     | Notebook    | [b753b7e847](https://linux-hardware.org/?probe=b753b7e847) | Jan 06, 2024 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [c16b44c1ce](https://linux-hardware.org/?probe=c16b44c1ce) | Jan 06, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7f28dd699b](https://linux-hardware.org/?probe=7f28dd699b) | Jan 06, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [6ced1e30f9](https://linux-hardware.org/?probe=6ced1e30f9) | Jan 06, 2024 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [009c5330a2](https://linux-hardware.org/?probe=009c5330a2) | Jan 06, 2024 |
| MSI           | MEG X570 UNIFY              | Desktop     | [56df310601](https://linux-hardware.org/?probe=56df310601) | Jan 06, 2024 |
| HP            | 83E1                        | Desktop     | [d3f2371283](https://linux-hardware.org/?probe=d3f2371283) | Jan 05, 2024 |
| Dell          | G7 7700                     | Notebook    | [126b71c515](https://linux-hardware.org/?probe=126b71c515) | Jan 05, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [6971ec53cd](https://linux-hardware.org/?probe=6971ec53cd) | Jan 05, 2024 |
| ASRock        | H61M                        | Desktop     | [e4a7c28d85](https://linux-hardware.org/?probe=e4a7c28d85) | Jan 04, 2024 |
| Notebook      | P7xxTM1                     | Notebook    | [9ed3be2a69](https://linux-hardware.org/?probe=9ed3be2a69) | Jan 04, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [42e67a91b0](https://linux-hardware.org/?probe=42e67a91b0) | Jan 04, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bb19b91823](https://linux-hardware.org/?probe=bb19b91823) | Jan 04, 2024 |
| Dell          | 0MG0RG A00                  | Desktop     | [f3847b13ce](https://linux-hardware.org/?probe=f3847b13ce) | Jan 04, 2024 |
| Acer          | Aspire A315-54              | Notebook    | [50c718d2c6](https://linux-hardware.org/?probe=50c718d2c6) | Jan 04, 2024 |
| ASUSTek       | Q500A                       | Notebook    | [c3f961d8be](https://linux-hardware.org/?probe=c3f961d8be) | Jan 03, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [fb4e22f4a6](https://linux-hardware.org/?probe=fb4e22f4a6) | Jan 03, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [f10936a9f7](https://linux-hardware.org/?probe=f10936a9f7) | Jan 02, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [2ae0bbe734](https://linux-hardware.org/?probe=2ae0bbe734) | Jan 01, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [f0cb030b5f](https://linux-hardware.org/?probe=f0cb030b5f) | Jan 01, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e1c9fdb53b](https://linux-hardware.org/?probe=e1c9fdb53b) | Dec 31, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [96395212e8](https://linux-hardware.org/?probe=96395212e8) | Dec 31, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [2f69bdfbc7](https://linux-hardware.org/?probe=2f69bdfbc7) | Dec 30, 2023 |
| Monster       | ABRA A5 V13.4               | Notebook    | [8cb3a2ee0a](https://linux-hardware.org/?probe=8cb3a2ee0a) | Dec 30, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [85c8033229](https://linux-hardware.org/?probe=85c8033229) | Dec 30, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ebdb840dba](https://linux-hardware.org/?probe=ebdb840dba) | Dec 30, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [bacd120c51](https://linux-hardware.org/?probe=bacd120c51) | Dec 30, 2023 |
| Monster       | ABRA A5 V13.4               | Notebook    | [274f6e86fc](https://linux-hardware.org/?probe=274f6e86fc) | Dec 29, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [3729a3492e](https://linux-hardware.org/?probe=3729a3492e) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [988bd71a05](https://linux-hardware.org/?probe=988bd71a05) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [9f85581cdb](https://linux-hardware.org/?probe=9f85581cdb) | Dec 29, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [6b98d84cb0](https://linux-hardware.org/?probe=6b98d84cb0) | Dec 28, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [754b2e0faf](https://linux-hardware.org/?probe=754b2e0faf) | Dec 27, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [be356bc929](https://linux-hardware.org/?probe=be356bc929) | Dec 27, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [aa60bdb2cb](https://linux-hardware.org/?probe=aa60bdb2cb) | Dec 27, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [ce4c03fbee](https://linux-hardware.org/?probe=ce4c03fbee) | Dec 26, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [e1bbb2ee71](https://linux-hardware.org/?probe=e1bbb2ee71) | Dec 26, 2023 |
| HP            | 8767 A                      | Desktop     | [6d2a367189](https://linux-hardware.org/?probe=6d2a367189) | Dec 25, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [5cc2120efc](https://linux-hardware.org/?probe=5cc2120efc) | Dec 25, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6bcc868ad6](https://linux-hardware.org/?probe=6bcc868ad6) | Dec 25, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [b00112da41](https://linux-hardware.org/?probe=b00112da41) | Dec 24, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [64a00841b2](https://linux-hardware.org/?probe=64a00841b2) | Dec 23, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [4adc5f3f81](https://linux-hardware.org/?probe=4adc5f3f81) | Dec 22, 2023 |
| Alienware     | 0P0JWX A00                  | Desktop     | [99d0e56ef1](https://linux-hardware.org/?probe=99d0e56ef1) | Dec 22, 2023 |
| HP            | 83E0                        | Desktop     | [07e6f563f9](https://linux-hardware.org/?probe=07e6f563f9) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [18788fe1ea](https://linux-hardware.org/?probe=18788fe1ea) | Dec 22, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [58a2ef76f9](https://linux-hardware.org/?probe=58a2ef76f9) | Dec 22, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [1a4d75f062](https://linux-hardware.org/?probe=1a4d75f062) | Dec 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4b1991c655](https://linux-hardware.org/?probe=4b1991c655) | Dec 21, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [4e3b422400](https://linux-hardware.org/?probe=4e3b422400) | Dec 19, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [925bd9bbac](https://linux-hardware.org/?probe=925bd9bbac) | Dec 19, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [1cd7c1b629](https://linux-hardware.org/?probe=1cd7c1b629) | Dec 19, 2023 |
| Dell          | G3 3590                     | Notebook    | [15decf2dfc](https://linux-hardware.org/?probe=15decf2dfc) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c2a8ace4dd](https://linux-hardware.org/?probe=c2a8ace4dd) | Dec 18, 2023 |
| HP            | Pavilion dv5                | Notebook    | [cf88cdfeb2](https://linux-hardware.org/?probe=cf88cdfeb2) | Dec 18, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [8a69294494](https://linux-hardware.org/?probe=8a69294494) | Dec 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ec58c18087](https://linux-hardware.org/?probe=ec58c18087) | Dec 17, 2023 |
| Acer          | Aspire A515-56T             | Notebook    | [9579acc8a0](https://linux-hardware.org/?probe=9579acc8a0) | Dec 16, 2023 |
| Gigabyte      | H310M A-CF                  | Desktop     | [cdf7a1ffd4](https://linux-hardware.org/?probe=cdf7a1ffd4) | Dec 15, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [93e9419d49](https://linux-hardware.org/?probe=93e9419d49) | Dec 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [6855d17ce1](https://linux-hardware.org/?probe=6855d17ce1) | Dec 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5d1e9e6d47](https://linux-hardware.org/?probe=5d1e9e6d47) | Dec 13, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [2c8846a637](https://linux-hardware.org/?probe=2c8846a637) | Dec 12, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [e17d6cbfa7](https://linux-hardware.org/?probe=e17d6cbfa7) | Dec 12, 2023 |
| Dell          | G7 7700                     | Notebook    | [9d4e191ab5](https://linux-hardware.org/?probe=9d4e191ab5) | Dec 12, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [68ba082c42](https://linux-hardware.org/?probe=68ba082c42) | Dec 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [f49dd0f010](https://linux-hardware.org/?probe=f49dd0f010) | Dec 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [dc0acbdb23](https://linux-hardware.org/?probe=dc0acbdb23) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [bc8d773d9d](https://linux-hardware.org/?probe=bc8d773d9d) | Dec 10, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [114391b743](https://linux-hardware.org/?probe=114391b743) | Dec 10, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [46be0f459d](https://linux-hardware.org/?probe=46be0f459d) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [04e25c9660](https://linux-hardware.org/?probe=04e25c9660) | Dec 10, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [e63d83327b](https://linux-hardware.org/?probe=e63d83327b) | Dec 09, 2023 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [d5d6865b7d](https://linux-hardware.org/?probe=d5d6865b7d) | Dec 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [ece705bc91](https://linux-hardware.org/?probe=ece705bc91) | Dec 09, 2023 |
| ONE-NETBOO... | ONEXPLAYER F1               | Tablet      | [158658e952](https://linux-hardware.org/?probe=158658e952) | Dec 08, 2023 |
| ONE-NETBOO... | ONEXPLAYER F1               | Tablet      | [3539ea142d](https://linux-hardware.org/?probe=3539ea142d) | Dec 08, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [9da65cd80e](https://linux-hardware.org/?probe=9da65cd80e) | Dec 07, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [acf5ffd938](https://linux-hardware.org/?probe=acf5ffd938) | Dec 06, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [5326fc7737](https://linux-hardware.org/?probe=5326fc7737) | Dec 06, 2023 |
| Dell          | G5 5505                     | Notebook    | [74d0a53db4](https://linux-hardware.org/?probe=74d0a53db4) | Dec 06, 2023 |
| Samsung       | 960QFG                      | Convertible | [42e5646709](https://linux-hardware.org/?probe=42e5646709) | Dec 06, 2023 |
| Exo           | Smart XQ7                   | Notebook    | [f1ebc77dfc](https://linux-hardware.org/?probe=f1ebc77dfc) | Dec 05, 2023 |
| Exo           | Smart XQ7                   | Notebook    | [3d56eb720e](https://linux-hardware.org/?probe=3d56eb720e) | Dec 05, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [110604e0da](https://linux-hardware.org/?probe=110604e0da) | Dec 05, 2023 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [6cd3d66979](https://linux-hardware.org/?probe=6cd3d66979) | Dec 05, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [e1478d8694](https://linux-hardware.org/?probe=e1478d8694) | Dec 03, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [f1d29c75a0](https://linux-hardware.org/?probe=f1d29c75a0) | Dec 03, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [2787907c00](https://linux-hardware.org/?probe=2787907c00) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e9e31f8aaa](https://linux-hardware.org/?probe=e9e31f8aaa) | Dec 03, 2023 |
| HP            | 0B54h D                     | Desktop     | [bffc586a45](https://linux-hardware.org/?probe=bffc586a45) | Dec 02, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [4f3cfed57b](https://linux-hardware.org/?probe=4f3cfed57b) | Dec 02, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [a5997eb3f2](https://linux-hardware.org/?probe=a5997eb3f2) | Dec 02, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [0d5166b475](https://linux-hardware.org/?probe=0d5166b475) | Dec 02, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [f86124413d](https://linux-hardware.org/?probe=f86124413d) | Dec 01, 2023 |
| Acer          | Aspire E5-473               | Notebook    | [f3b2c01ef7](https://linux-hardware.org/?probe=f3b2c01ef7) | Dec 01, 2023 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [322ac1cb94](https://linux-hardware.org/?probe=322ac1cb94) | Dec 01, 2023 |
| Lenovo        | Yoga 9 14IRP8 83B1          | Convertible | [515d60d68e](https://linux-hardware.org/?probe=515d60d68e) | Dec 01, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [ec402bfe2f](https://linux-hardware.org/?probe=ec402bfe2f) | Nov 30, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [2eaa838401](https://linux-hardware.org/?probe=2eaa838401) | Nov 30, 2023 |
| Acer          | Veriton N4680G              | Desktop     | [033223b8bc](https://linux-hardware.org/?probe=033223b8bc) | Nov 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6357a41a39](https://linux-hardware.org/?probe=6357a41a39) | Nov 30, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [37545bd915](https://linux-hardware.org/?probe=37545bd915) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d385ea9309](https://linux-hardware.org/?probe=d385ea9309) | Nov 29, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [11d3e45e2d](https://linux-hardware.org/?probe=11d3e45e2d) | Nov 29, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [d2dcb1f2da](https://linux-hardware.org/?probe=d2dcb1f2da) | Nov 29, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [b4fbd61258](https://linux-hardware.org/?probe=b4fbd61258) | Nov 28, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5509bd1ba](https://linux-hardware.org/?probe=e5509bd1ba) | Nov 28, 2023 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [a39fba5394](https://linux-hardware.org/?probe=a39fba5394) | Nov 27, 2023 |
| Google        | Kench                       | Desktop     | [efdf5874c1](https://linux-hardware.org/?probe=efdf5874c1) | Nov 27, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [ab44413728](https://linux-hardware.org/?probe=ab44413728) | Nov 26, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [5c10f3d5a1](https://linux-hardware.org/?probe=5c10f3d5a1) | Nov 25, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [05ba5178cb](https://linux-hardware.org/?probe=05ba5178cb) | Nov 25, 2023 |
| HP            | 8054                        | Desktop     | [dfa212d5da](https://linux-hardware.org/?probe=dfa212d5da) | Nov 25, 2023 |
| Dell          | Precision 7740              | Notebook    | [50b0f0be08](https://linux-hardware.org/?probe=50b0f0be08) | Nov 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0f9d912f7f](https://linux-hardware.org/?probe=0f9d912f7f) | Nov 24, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [4f1d1d579c](https://linux-hardware.org/?probe=4f1d1d579c) | Nov 24, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [c3b398c792](https://linux-hardware.org/?probe=c3b398c792) | Nov 24, 2023 |
| ASRock        | X370 Gaming X               | Notebook    | [0c39910834](https://linux-hardware.org/?probe=0c39910834) | Nov 23, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2ab108f743](https://linux-hardware.org/?probe=2ab108f743) | Nov 22, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [0714d466f7](https://linux-hardware.org/?probe=0714d466f7) | Nov 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [dc02cb2409](https://linux-hardware.org/?probe=dc02cb2409) | Nov 20, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [639c2b7832](https://linux-hardware.org/?probe=639c2b7832) | Nov 20, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [0d4fe4c2b9](https://linux-hardware.org/?probe=0d4fe4c2b9) | Nov 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [1048b240d5](https://linux-hardware.org/?probe=1048b240d5) | Nov 19, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [74162bf452](https://linux-hardware.org/?probe=74162bf452) | Nov 19, 2023 |
| LG Electro... | 16Z90R-G.AD75F              | Notebook    | [83d650792f](https://linux-hardware.org/?probe=83d650792f) | Nov 18, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [db393353d9](https://linux-hardware.org/?probe=db393353d9) | Nov 18, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [c00a7584bf](https://linux-hardware.org/?probe=c00a7584bf) | Nov 18, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [adf1b0c27a](https://linux-hardware.org/?probe=adf1b0c27a) | Nov 16, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [168e0af4e6](https://linux-hardware.org/?probe=168e0af4e6) | Nov 16, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [ca5d20d4a4](https://linux-hardware.org/?probe=ca5d20d4a4) | Nov 16, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [914e24f740](https://linux-hardware.org/?probe=914e24f740) | Nov 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Notebook    | [aca7636589](https://linux-hardware.org/?probe=aca7636589) | Nov 16, 2023 |
| MSI           | GF62 8RC                    | Notebook    | [8e186cf8b9](https://linux-hardware.org/?probe=8e186cf8b9) | Nov 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Notebook    | [7856865861](https://linux-hardware.org/?probe=7856865861) | Nov 16, 2023 |
| HP            | Pavilion dv9700             | Notebook    | [0b039b15e7](https://linux-hardware.org/?probe=0b039b15e7) | Nov 15, 2023 |
| HP            | Pavilion dv9700             | Notebook    | [b5e651a2bf](https://linux-hardware.org/?probe=b5e651a2bf) | Nov 15, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [038ffaab27](https://linux-hardware.org/?probe=038ffaab27) | Nov 13, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [f0db6bb1ae](https://linux-hardware.org/?probe=f0db6bb1ae) | Nov 11, 2023 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [99fa1c416d](https://linux-hardware.org/?probe=99fa1c416d) | Nov 11, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [404f1947fd](https://linux-hardware.org/?probe=404f1947fd) | Nov 11, 2023 |
| Microsoft     | Surface Book                | Tablet      | [67575d0e41](https://linux-hardware.org/?probe=67575d0e41) | Nov 08, 2023 |
| ASUSTek       | Q504UAK                     | Convertible | [177cde7808](https://linux-hardware.org/?probe=177cde7808) | Nov 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [9f1e875996](https://linux-hardware.org/?probe=9f1e875996) | Nov 07, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [993c65a274](https://linux-hardware.org/?probe=993c65a274) | Nov 06, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [615e914ddd](https://linux-hardware.org/?probe=615e914ddd) | Nov 05, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [7ba5de3dfd](https://linux-hardware.org/?probe=7ba5de3dfd) | Nov 05, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c17ad7033c](https://linux-hardware.org/?probe=c17ad7033c) | Nov 05, 2023 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [2b9b1f909c](https://linux-hardware.org/?probe=2b9b1f909c) | Nov 05, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [701314a2ff](https://linux-hardware.org/?probe=701314a2ff) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [12b6cd2d09](https://linux-hardware.org/?probe=12b6cd2d09) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [119816ea7d](https://linux-hardware.org/?probe=119816ea7d) | Nov 04, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [6d39c4f814](https://linux-hardware.org/?probe=6d39c4f814) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e928da88d7](https://linux-hardware.org/?probe=e928da88d7) | Nov 03, 2023 |
| Dell          | Precision 7740              | Notebook    | [71b262696a](https://linux-hardware.org/?probe=71b262696a) | Nov 02, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [72a2946c83](https://linux-hardware.org/?probe=72a2946c83) | Nov 01, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | Notebook    | [b89ceef38d](https://linux-hardware.org/?probe=b89ceef38d) | Nov 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [8161abddda](https://linux-hardware.org/?probe=8161abddda) | Nov 01, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [5b82a04d09](https://linux-hardware.org/?probe=5b82a04d09) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [70e4b3b007](https://linux-hardware.org/?probe=70e4b3b007) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [352bf34e3b](https://linux-hardware.org/?probe=352bf34e3b) | Oct 31, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d9da25aaae](https://linux-hardware.org/?probe=d9da25aaae) | Oct 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0eae5ed294](https://linux-hardware.org/?probe=0eae5ed294) | Oct 31, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [4254def277](https://linux-hardware.org/?probe=4254def277) | Oct 30, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [d40277c6b4](https://linux-hardware.org/?probe=d40277c6b4) | Oct 30, 2023 |
| System76      | Gazelle                     | Notebook    | [3bc4a66a13](https://linux-hardware.org/?probe=3bc4a66a13) | Oct 29, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [9dad78d2eb](https://linux-hardware.org/?probe=9dad78d2eb) | Oct 27, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [354a804750](https://linux-hardware.org/?probe=354a804750) | Oct 27, 2023 |
| HP            | Notebook                    | Notebook    | [b6f188a1fe](https://linux-hardware.org/?probe=b6f188a1fe) | Oct 27, 2023 |
| Dell          | Latitude E5470              | Notebook    | [fbbcdd8d9f](https://linux-hardware.org/?probe=fbbcdd8d9f) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [3d7ad8a1d6](https://linux-hardware.org/?probe=3d7ad8a1d6) | Oct 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cac52e6eaf](https://linux-hardware.org/?probe=cac52e6eaf) | Oct 25, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2355d71878](https://linux-hardware.org/?probe=2355d71878) | Oct 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [38cbc0d5d7](https://linux-hardware.org/?probe=38cbc0d5d7) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [29adbcb90f](https://linux-hardware.org/?probe=29adbcb90f) | Oct 24, 2023 |
| ASUSTek       | GL502VSK                    | Notebook    | [5f455e693f](https://linux-hardware.org/?probe=5f455e693f) | Oct 24, 2023 |
| ASRock        | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [24cad9ca71](https://linux-hardware.org/?probe=24cad9ca71) | Oct 22, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [2c786f10b7](https://linux-hardware.org/?probe=2c786f10b7) | Oct 22, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [7b1e876aef](https://linux-hardware.org/?probe=7b1e876aef) | Oct 22, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [72d780f5f7](https://linux-hardware.org/?probe=72d780f5f7) | Oct 22, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [2f2798b05c](https://linux-hardware.org/?probe=2f2798b05c) | Oct 22, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [451317bd25](https://linux-hardware.org/?probe=451317bd25) | Oct 22, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [fa46708f8f](https://linux-hardware.org/?probe=fa46708f8f) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [390f0188b4](https://linux-hardware.org/?probe=390f0188b4) | Oct 19, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [459dc02cda](https://linux-hardware.org/?probe=459dc02cda) | Oct 18, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4a7b98d45e](https://linux-hardware.org/?probe=4a7b98d45e) | Oct 18, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [a4661384e1](https://linux-hardware.org/?probe=a4661384e1) | Oct 17, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [fb2bf1baa8](https://linux-hardware.org/?probe=fb2bf1baa8) | Oct 16, 2023 |
| Lenovo        | ThinkPad T450 20BUS1K50X    | Notebook    | [11ccdc870b](https://linux-hardware.org/?probe=11ccdc870b) | Oct 16, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [c5183a57ce](https://linux-hardware.org/?probe=c5183a57ce) | Oct 16, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a116875c3f](https://linux-hardware.org/?probe=a116875c3f) | Oct 15, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [9f5a8c985a](https://linux-hardware.org/?probe=9f5a8c985a) | Oct 15, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [6f3a56878d](https://linux-hardware.org/?probe=6f3a56878d) | Oct 15, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [d2e0e9fc07](https://linux-hardware.org/?probe=d2e0e9fc07) | Oct 14, 2023 |
| MSI           | GT72S 6QE                   | Notebook    | [9a2d87eb4c](https://linux-hardware.org/?probe=9a2d87eb4c) | Oct 12, 2023 |
| MSI           | GT72S 6QE                   | Notebook    | [4927bfc263](https://linux-hardware.org/?probe=4927bfc263) | Oct 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [dc82ec9351](https://linux-hardware.org/?probe=dc82ec9351) | Oct 11, 2023 |
| Toshiba       | Satellite C55D-C            | Notebook    | [e083a8012f](https://linux-hardware.org/?probe=e083a8012f) | Oct 11, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [1014c56a70](https://linux-hardware.org/?probe=1014c56a70) | Oct 10, 2023 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [15d9d16ec9](https://linux-hardware.org/?probe=15d9d16ec9) | Oct 09, 2023 |
| Biostar       | A320MH                      | Desktop     | [9623471fc7](https://linux-hardware.org/?probe=9623471fc7) | Oct 09, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [c0e071789f](https://linux-hardware.org/?probe=c0e071789f) | Oct 09, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [85d999063f](https://linux-hardware.org/?probe=85d999063f) | Oct 09, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [536b59322e](https://linux-hardware.org/?probe=536b59322e) | Oct 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [e087628f2a](https://linux-hardware.org/?probe=e087628f2a) | Oct 07, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [06f03211a6](https://linux-hardware.org/?probe=06f03211a6) | Oct 06, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [811561ec05](https://linux-hardware.org/?probe=811561ec05) | Oct 04, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [65ae20098f](https://linux-hardware.org/?probe=65ae20098f) | Oct 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d3e6e2aa83](https://linux-hardware.org/?probe=d3e6e2aa83) | Oct 03, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [78c54897a1](https://linux-hardware.org/?probe=78c54897a1) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [288f5f8266](https://linux-hardware.org/?probe=288f5f8266) | Sep 30, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [4bb43a39c1](https://linux-hardware.org/?probe=4bb43a39c1) | Sep 29, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81JN     | Notebook    | [747f0d45fe](https://linux-hardware.org/?probe=747f0d45fe) | Sep 28, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [dd4a3f701c](https://linux-hardware.org/?probe=dd4a3f701c) | Sep 27, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [55c34c64a6](https://linux-hardware.org/?probe=55c34c64a6) | Sep 27, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [87a3517005](https://linux-hardware.org/?probe=87a3517005) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [c33d31195f](https://linux-hardware.org/?probe=c33d31195f) | Sep 26, 2023 |
| Dell          | G5 5505                     | Notebook    | [787ccf4559](https://linux-hardware.org/?probe=787ccf4559) | Sep 25, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [93b975d65b](https://linux-hardware.org/?probe=93b975d65b) | Sep 24, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [9b6bbb4b56](https://linux-hardware.org/?probe=9b6bbb4b56) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d21f140b5e](https://linux-hardware.org/?probe=d21f140b5e) | Sep 23, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c40dbfbd1d](https://linux-hardware.org/?probe=c40dbfbd1d) | Sep 23, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [5043f41a8d](https://linux-hardware.org/?probe=5043f41a8d) | Sep 20, 2023 |
| AZW           | GTR V02                     | Desktop     | [2d4817f092](https://linux-hardware.org/?probe=2d4817f092) | Sep 18, 2023 |
| Dell          | G3 3579                     | Notebook    | [eff563e086](https://linux-hardware.org/?probe=eff563e086) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [4c854cc233](https://linux-hardware.org/?probe=4c854cc233) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [27763442c0](https://linux-hardware.org/?probe=27763442c0) | Sep 16, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [cd2fb41835](https://linux-hardware.org/?probe=cd2fb41835) | Sep 15, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [52f0ac41db](https://linux-hardware.org/?probe=52f0ac41db) | Sep 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [caf0257156](https://linux-hardware.org/?probe=caf0257156) | Sep 13, 2023 |
| Dell          | Latitude E6440              | Notebook    | [591c479a8d](https://linux-hardware.org/?probe=591c479a8d) | Sep 13, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [b9f46a8a9b](https://linux-hardware.org/?probe=b9f46a8a9b) | Sep 12, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [f818765b79](https://linux-hardware.org/?probe=f818765b79) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3857377d7a](https://linux-hardware.org/?probe=3857377d7a) | Sep 09, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [6521407977](https://linux-hardware.org/?probe=6521407977) | Sep 06, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [b395463f0e](https://linux-hardware.org/?probe=b395463f0e) | Sep 06, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [95d0f9505b](https://linux-hardware.org/?probe=95d0f9505b) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3900a91c0b](https://linux-hardware.org/?probe=3900a91c0b) | Sep 03, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [174cff0e19](https://linux-hardware.org/?probe=174cff0e19) | Sep 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [07a44c323f](https://linux-hardware.org/?probe=07a44c323f) | Sep 01, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [a0649549b3](https://linux-hardware.org/?probe=a0649549b3) | Sep 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c865cde7a2](https://linux-hardware.org/?probe=c865cde7a2) | Sep 01, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| ASRock        | Z490M Pro4                  | Desktop     | [e07d4a9c90](https://linux-hardware.org/?probe=e07d4a9c90) | Aug 30, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [cdbff2ba81](https://linux-hardware.org/?probe=cdbff2ba81) | Aug 28, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [a4fe691c36](https://linux-hardware.org/?probe=a4fe691c36) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [0bda6b93da](https://linux-hardware.org/?probe=0bda6b93da) | Aug 27, 2023 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [5af1e720cc](https://linux-hardware.org/?probe=5af1e720cc) | Aug 27, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [de1d12ec95](https://linux-hardware.org/?probe=de1d12ec95) | Aug 24, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [523acf034e](https://linux-hardware.org/?probe=523acf034e) | Aug 23, 2023 |
| ASUSTek       | G751JM                      | Notebook    | [7cdb0c52e4](https://linux-hardware.org/?probe=7cdb0c52e4) | Aug 23, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [530e70e1ab](https://linux-hardware.org/?probe=530e70e1ab) | Aug 22, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ca9423253c](https://linux-hardware.org/?probe=ca9423253c) | Aug 21, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [45264bf6e6](https://linux-hardware.org/?probe=45264bf6e6) | Aug 20, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [0887b2e549](https://linux-hardware.org/?probe=0887b2e549) | Aug 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [f7d3395ffc](https://linux-hardware.org/?probe=f7d3395ffc) | Aug 18, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [f368b5bf17](https://linux-hardware.org/?probe=f368b5bf17) | Aug 18, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [712bd65558](https://linux-hardware.org/?probe=712bd65558) | Aug 16, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [9c5e7cc1fb](https://linux-hardware.org/?probe=9c5e7cc1fb) | Aug 16, 2023 |
| Pegatron      | Benicia                     | Desktop     | [0ab394fa9e](https://linux-hardware.org/?probe=0ab394fa9e) | Aug 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [876d7e9992](https://linux-hardware.org/?probe=876d7e9992) | Aug 15, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [da3036b8e3](https://linux-hardware.org/?probe=da3036b8e3) | Aug 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [e9b2347b46](https://linux-hardware.org/?probe=e9b2347b46) | Aug 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [f9d07e4f97](https://linux-hardware.org/?probe=f9d07e4f97) | Aug 12, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [ecbc3827d1](https://linux-hardware.org/?probe=ecbc3827d1) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [f4d0fd6811](https://linux-hardware.org/?probe=f4d0fd6811) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [a5681e12d3](https://linux-hardware.org/?probe=a5681e12d3) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3a7d1d1f9b](https://linux-hardware.org/?probe=3a7d1d1f9b) | Aug 11, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [f016fa3756](https://linux-hardware.org/?probe=f016fa3756) | Aug 11, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [40c31ab8e5](https://linux-hardware.org/?probe=40c31ab8e5) | Aug 11, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [d490bb32ec](https://linux-hardware.org/?probe=d490bb32ec) | Aug 10, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [fffee60e72](https://linux-hardware.org/?probe=fffee60e72) | Aug 10, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d6b7da58e7](https://linux-hardware.org/?probe=d6b7da58e7) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [d9c999ffa3](https://linux-hardware.org/?probe=d9c999ffa3) | Aug 08, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | Notebook    | [101c521941](https://linux-hardware.org/?probe=101c521941) | Aug 08, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [f7c7290847](https://linux-hardware.org/?probe=f7c7290847) | Aug 08, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [9a0fa703d7](https://linux-hardware.org/?probe=9a0fa703d7) | Aug 07, 2023 |
| Micro Comp... | NUCXI7                      | Notebook    | [96d3ade9eb](https://linux-hardware.org/?probe=96d3ade9eb) | Aug 07, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [ec7fa20ab4](https://linux-hardware.org/?probe=ec7fa20ab4) | Aug 06, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [d9107b9cb9](https://linux-hardware.org/?probe=d9107b9cb9) | Aug 06, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [28384fb38c](https://linux-hardware.org/?probe=28384fb38c) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [5ec7de1222](https://linux-hardware.org/?probe=5ec7de1222) | Aug 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ab9328165e](https://linux-hardware.org/?probe=ab9328165e) | Aug 05, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [2cb4df0aab](https://linux-hardware.org/?probe=2cb4df0aab) | Aug 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS3ES0A    | Notebook    | [1038e99486](https://linux-hardware.org/?probe=1038e99486) | Aug 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [cd0d64a16a](https://linux-hardware.org/?probe=cd0d64a16a) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [53c9161fc5](https://linux-hardware.org/?probe=53c9161fc5) | Aug 03, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [18dad15a33](https://linux-hardware.org/?probe=18dad15a33) | Aug 02, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [ceb7e754a1](https://linux-hardware.org/?probe=ceb7e754a1) | Aug 02, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [84c1a14a56](https://linux-hardware.org/?probe=84c1a14a56) | Aug 01, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3aeae112c3](https://linux-hardware.org/?probe=3aeae112c3) | Jul 31, 2023 |
| NZXT          | N7 B650E                    | Desktop     | [38e481c3d5](https://linux-hardware.org/?probe=38e481c3d5) | Jul 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [513ac15990](https://linux-hardware.org/?probe=513ac15990) | Jul 28, 2023 |
| ASRock        | WRX80 Creator R2.0          | Other       | [f37cf89f5f](https://linux-hardware.org/?probe=f37cf89f5f) | Jul 28, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [23c1f6fa05](https://linux-hardware.org/?probe=23c1f6fa05) | Jul 28, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [49cbe32874](https://linux-hardware.org/?probe=49cbe32874) | Jul 28, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [c9c42e4857](https://linux-hardware.org/?probe=c9c42e4857) | Jul 26, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [35f41c1327](https://linux-hardware.org/?probe=35f41c1327) | Jul 25, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [319cb6659d](https://linux-hardware.org/?probe=319cb6659d) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [567693892b](https://linux-hardware.org/?probe=567693892b) | Jul 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ca354dd42d](https://linux-hardware.org/?probe=ca354dd42d) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [228ded2955](https://linux-hardware.org/?probe=228ded2955) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5f9962eafc](https://linux-hardware.org/?probe=5f9962eafc) | Jul 21, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [2109b6ace6](https://linux-hardware.org/?probe=2109b6ace6) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [022d677eda](https://linux-hardware.org/?probe=022d677eda) | Jul 21, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [25311760a9](https://linux-hardware.org/?probe=25311760a9) | Jul 21, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [0ba223e9ae](https://linux-hardware.org/?probe=0ba223e9ae) | Jul 19, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [26313914e4](https://linux-hardware.org/?probe=26313914e4) | Jul 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| Toshiba       | Satellite S55t-C            | Notebook    | [be8777b248](https://linux-hardware.org/?probe=be8777b248) | Jul 17, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [5ead4ab228](https://linux-hardware.org/?probe=5ead4ab228) | Jul 17, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [8231c1b7c0](https://linux-hardware.org/?probe=8231c1b7c0) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [91f38d0ab5](https://linux-hardware.org/?probe=91f38d0ab5) | Jul 16, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [70b7e2a7f5](https://linux-hardware.org/?probe=70b7e2a7f5) | Jul 16, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [ac55f32c4e](https://linux-hardware.org/?probe=ac55f32c4e) | Jul 16, 2023 |
| ASRock        | H370 Performance            | Desktop     | [43286f18d3](https://linux-hardware.org/?probe=43286f18d3) | Jul 16, 2023 |
| HP            | 3396                        | Desktop     | [5713dca497](https://linux-hardware.org/?probe=5713dca497) | Jul 15, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [d8550d27e3](https://linux-hardware.org/?probe=d8550d27e3) | Jul 15, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c27ff02a84](https://linux-hardware.org/?probe=c27ff02a84) | Jul 14, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [7026c5b007](https://linux-hardware.org/?probe=7026c5b007) | Jul 14, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [8e3cc576fd](https://linux-hardware.org/?probe=8e3cc576fd) | Jul 14, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [d20f9ee7a7](https://linux-hardware.org/?probe=d20f9ee7a7) | Jul 14, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [110a53c220](https://linux-hardware.org/?probe=110a53c220) | Jul 13, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [9e49d96293](https://linux-hardware.org/?probe=9e49d96293) | Jul 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [e612d95542](https://linux-hardware.org/?probe=e612d95542) | Jul 12, 2023 |
| Unknown       | EA A520M-E                  | Desktop     | [184201d556](https://linux-hardware.org/?probe=184201d556) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [0e411803b2](https://linux-hardware.org/?probe=0e411803b2) | Jul 10, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [429e4e7636](https://linux-hardware.org/?probe=429e4e7636) | Jul 10, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [f273c7ffee](https://linux-hardware.org/?probe=f273c7ffee) | Jul 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e9e376fb10](https://linux-hardware.org/?probe=e9e376fb10) | Jul 09, 2023 |
| Acer          | Nitro N50-620               | Desktop     | [8286ddb9ae](https://linux-hardware.org/?probe=8286ddb9ae) | Jul 08, 2023 |
| Dell          | G7 7790                     | Notebook    | [a6dd0d72f7](https://linux-hardware.org/?probe=a6dd0d72f7) | Jul 06, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [f4f1e6f9ff](https://linux-hardware.org/?probe=f4f1e6f9ff) | Jul 05, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [afa2978397](https://linux-hardware.org/?probe=afa2978397) | Jul 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [2be3b17236](https://linux-hardware.org/?probe=2be3b17236) | Jul 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9472db0bf4](https://linux-hardware.org/?probe=9472db0bf4) | Jul 04, 2023 |
| GPD           | G1618-03                    | Desktop     | [0cb58087bf](https://linux-hardware.org/?probe=0cb58087bf) | Jul 04, 2023 |
| Dell          | Latitude E5440              | Notebook    | [03ed0e9ebb](https://linux-hardware.org/?probe=03ed0e9ebb) | Jul 03, 2023 |
| Samsung       | 730QED                      | Convertible | [5bcec42625](https://linux-hardware.org/?probe=5bcec42625) | Jul 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [626416c230](https://linux-hardware.org/?probe=626416c230) | Jul 03, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [be7a8d9ce0](https://linux-hardware.org/?probe=be7a8d9ce0) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ff0f73c325](https://linux-hardware.org/?probe=ff0f73c325) | Jul 02, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [e7e4a3562f](https://linux-hardware.org/?probe=e7e4a3562f) | Jul 02, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [488ebd160a](https://linux-hardware.org/?probe=488ebd160a) | Jul 02, 2023 |
| Dell          | G7 7790                     | Notebook    | [6345fbbe32](https://linux-hardware.org/?probe=6345fbbe32) | Jul 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [c1051d3ef0](https://linux-hardware.org/?probe=c1051d3ef0) | Jul 01, 2023 |
| ASRock        | X299 Taichi CLX             | Desktop     | [ff1f31ff36](https://linux-hardware.org/?probe=ff1f31ff36) | Jul 01, 2023 |
| ASRock        | X299 Taichi CLX             | Desktop     | [d4362fb3ca](https://linux-hardware.org/?probe=d4362fb3ca) | Jul 01, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [593959e6f3](https://linux-hardware.org/?probe=593959e6f3) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [c93f4f0d0b](https://linux-hardware.org/?probe=c93f4f0d0b) | Jun 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [bbd5ba331d](https://linux-hardware.org/?probe=bbd5ba331d) | Jun 30, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [9979e7a733](https://linux-hardware.org/?probe=9979e7a733) | Jun 29, 2023 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [8086d33203](https://linux-hardware.org/?probe=8086d33203) | Jun 29, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [4846eae54f](https://linux-hardware.org/?probe=4846eae54f) | Jun 28, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [f5c922b6d3](https://linux-hardware.org/?probe=f5c922b6d3) | Jun 28, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [c77b479e22](https://linux-hardware.org/?probe=c77b479e22) | Jun 27, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [c243b40ffb](https://linux-hardware.org/?probe=c243b40ffb) | Jun 26, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | Notebook    | [5e67041129](https://linux-hardware.org/?probe=5e67041129) | Jun 26, 2023 |
| Google        | Blooglet                    | Notebook    | [88fae074d1](https://linux-hardware.org/?probe=88fae074d1) | Jun 25, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [279f2cedcc](https://linux-hardware.org/?probe=279f2cedcc) | Jun 24, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5b780b9ebd](https://linux-hardware.org/?probe=5b780b9ebd) | Jun 24, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [54d0d54490](https://linux-hardware.org/?probe=54d0d54490) | Jun 24, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [f83de9c7b9](https://linux-hardware.org/?probe=f83de9c7b9) | Jun 24, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [0ee3f7532c](https://linux-hardware.org/?probe=0ee3f7532c) | Jun 23, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | Notebook    | [305e202fd3](https://linux-hardware.org/?probe=305e202fd3) | Jun 22, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [379c36642b](https://linux-hardware.org/?probe=379c36642b) | Jun 22, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [2656caf6b8](https://linux-hardware.org/?probe=2656caf6b8) | Jun 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac0a9c170f](https://linux-hardware.org/?probe=ac0a9c170f) | Jun 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [666f5d0ce5](https://linux-hardware.org/?probe=666f5d0ce5) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [2805733dcd](https://linux-hardware.org/?probe=2805733dcd) | Jun 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [370e948985](https://linux-hardware.org/?probe=370e948985) | Jun 21, 2023 |
| MSI           | GT70 2OC/2OD                | Notebook    | [d8d81f0614](https://linux-hardware.org/?probe=d8d81f0614) | Jun 20, 2023 |
| MSI           | GE75 Raider 10SE            | Notebook    | [f7a3caaef1](https://linux-hardware.org/?probe=f7a3caaef1) | Jun 20, 2023 |
| MSI           | GE75 Raider 10SE            | Notebook    | [f11d231c6a](https://linux-hardware.org/?probe=f11d231c6a) | Jun 20, 2023 |
| Timi          | A30                         | Notebook    | [34d77f385a](https://linux-hardware.org/?probe=34d77f385a) | Jun 19, 2023 |
| Lenovo        | ThinkPad A485 20MU000TUS    | Notebook    | [10cf405f89](https://linux-hardware.org/?probe=10cf405f89) | Jun 17, 2023 |
| Dell          | Precision 7510              | Notebook    | [cbbfdafd46](https://linux-hardware.org/?probe=cbbfdafd46) | Jun 17, 2023 |
| ASRock        | Z370 Gaming-ITX/ac          | Desktop     | [e05a90c6c5](https://linux-hardware.org/?probe=e05a90c6c5) | Jun 16, 2023 |
| HP            | 8054                        | Desktop     | [97a4b34236](https://linux-hardware.org/?probe=97a4b34236) | Jun 15, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [448a3cf6b1](https://linux-hardware.org/?probe=448a3cf6b1) | Jun 15, 2023 |
| ASRock        | B650E Steel Legend WiFi     | Desktop     | [3edca35793](https://linux-hardware.org/?probe=3edca35793) | Jun 14, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [6febc3ef2e](https://linux-hardware.org/?probe=6febc3ef2e) | Jun 13, 2023 |
| Google        | Blooglet                    | Notebook    | [80ce635393](https://linux-hardware.org/?probe=80ce635393) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d21e64704](https://linux-hardware.org/?probe=5d21e64704) | Jun 10, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [42722d78d8](https://linux-hardware.org/?probe=42722d78d8) | Jun 10, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6491127e6e](https://linux-hardware.org/?probe=6491127e6e) | Jun 09, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [12736be80e](https://linux-hardware.org/?probe=12736be80e) | Jun 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [bc00b26e0a](https://linux-hardware.org/?probe=bc00b26e0a) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [ee25039289](https://linux-hardware.org/?probe=ee25039289) | Jun 06, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [43c70efbe7](https://linux-hardware.org/?probe=43c70efbe7) | Jun 05, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [efa9cac1df](https://linux-hardware.org/?probe=efa9cac1df) | Jun 04, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [1285aacf1b](https://linux-hardware.org/?probe=1285aacf1b) | Jun 04, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [386f19f4f1](https://linux-hardware.org/?probe=386f19f4f1) | Jun 03, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3e7ad22b6b](https://linux-hardware.org/?probe=3e7ad22b6b) | Jun 03, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [ae3bf8f79c](https://linux-hardware.org/?probe=ae3bf8f79c) | Jun 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Notebook    | [9a91f8aedc](https://linux-hardware.org/?probe=9a91f8aedc) | Jun 02, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [259865e80e](https://linux-hardware.org/?probe=259865e80e) | Jun 01, 2023 |
| Alienware     | m17 R5 AMD                  | Notebook    | [f5eeb72c4d](https://linux-hardware.org/?probe=f5eeb72c4d) | May 31, 2023 |
| Samsung       | 730QED                      | Convertible | [8b5ecbd84f](https://linux-hardware.org/?probe=8b5ecbd84f) | May 31, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [54b872a39b](https://linux-hardware.org/?probe=54b872a39b) | May 31, 2023 |
| ASRock        | B650E Steel Legend WiFi     | Desktop     | [88d16bf040](https://linux-hardware.org/?probe=88d16bf040) | May 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0cb4af5367](https://linux-hardware.org/?probe=0cb4af5367) | May 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S06Q0... | Notebook    | [e54e204b28](https://linux-hardware.org/?probe=e54e204b28) | May 29, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | Notebook    | [9496942a44](https://linux-hardware.org/?probe=9496942a44) | May 28, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [9099d721d2](https://linux-hardware.org/?probe=9099d721d2) | May 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [447bbfbd40](https://linux-hardware.org/?probe=447bbfbd40) | May 27, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [c2640c22ff](https://linux-hardware.org/?probe=c2640c22ff) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [94f79f2f74](https://linux-hardware.org/?probe=94f79f2f74) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [d2cca6c2a1](https://linux-hardware.org/?probe=d2cca6c2a1) | May 27, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6bf848e58f](https://linux-hardware.org/?probe=6bf848e58f) | May 25, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | Desktop     | [cc674d2878](https://linux-hardware.org/?probe=cc674d2878) | May 25, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [1efd2eb268](https://linux-hardware.org/?probe=1efd2eb268) | May 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [c43cfd04ad](https://linux-hardware.org/?probe=c43cfd04ad) | May 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0aba7a98b9](https://linux-hardware.org/?probe=0aba7a98b9) | May 24, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [a5df8ea9d7](https://linux-hardware.org/?probe=a5df8ea9d7) | May 23, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [0d3bc48240](https://linux-hardware.org/?probe=0d3bc48240) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d1c4b3ee44](https://linux-hardware.org/?probe=d1c4b3ee44) | May 22, 2023 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [1e648e8f50](https://linux-hardware.org/?probe=1e648e8f50) | May 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| ASRock        | B650E Steel Legend WiFi     | Desktop     | [b034244bec](https://linux-hardware.org/?probe=b034244bec) | May 20, 2023 |
| langchao      | IPM41-D3                    | Desktop     | [2f659faa92](https://linux-hardware.org/?probe=2f659faa92) | May 20, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [758f0dbd4b](https://linux-hardware.org/?probe=758f0dbd4b) | May 19, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ca0ae58640](https://linux-hardware.org/?probe=ca0ae58640) | May 18, 2023 |
| Samsung       | 730QED                      | Convertible | [7440f51d53](https://linux-hardware.org/?probe=7440f51d53) | May 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [fee6b2f55b](https://linux-hardware.org/?probe=fee6b2f55b) | May 17, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [dc2f3b9cdc](https://linux-hardware.org/?probe=dc2f3b9cdc) | May 17, 2023 |
| ASRock        | Z97 Pro3                    | Desktop     | [f8be8d5d2c](https://linux-hardware.org/?probe=f8be8d5d2c) | May 16, 2023 |
| HP            | Pavilion 15                 | Notebook    | [5a43663b87](https://linux-hardware.org/?probe=5a43663b87) | May 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b298e421bb](https://linux-hardware.org/?probe=b298e421bb) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| ASRock        | Z97 Pro3                    | Desktop     | [34b2fb40b9](https://linux-hardware.org/?probe=34b2fb40b9) | May 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [71f1904bc6](https://linux-hardware.org/?probe=71f1904bc6) | May 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [bd6f8927b4](https://linux-hardware.org/?probe=bd6f8927b4) | May 12, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [2b0bc04757](https://linux-hardware.org/?probe=2b0bc04757) | May 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ebe0f52831](https://linux-hardware.org/?probe=ebe0f52831) | May 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d2d1037c9d](https://linux-hardware.org/?probe=d2d1037c9d) | May 09, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [aa31c3dd8f](https://linux-hardware.org/?probe=aa31c3dd8f) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [c39e7fa08d](https://linux-hardware.org/?probe=c39e7fa08d) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [dc1db599ea](https://linux-hardware.org/?probe=dc1db599ea) | May 09, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [40d1bba9e2](https://linux-hardware.org/?probe=40d1bba9e2) | May 07, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [e2ce1c3d6c](https://linux-hardware.org/?probe=e2ce1c3d6c) | May 07, 2023 |
| Gigabyte      | P43-ES3G                    | Desktop     | [1095d1ef7f](https://linux-hardware.org/?probe=1095d1ef7f) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [de65a79bf1](https://linux-hardware.org/?probe=de65a79bf1) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [4b76463d57](https://linux-hardware.org/?probe=4b76463d57) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [b0a2a0b536](https://linux-hardware.org/?probe=b0a2a0b536) | May 06, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [5c506f94e0](https://linux-hardware.org/?probe=5c506f94e0) | May 05, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [d7c37a25de](https://linux-hardware.org/?probe=d7c37a25de) | May 05, 2023 |
| Samsung       | 535U3C                      | Notebook    | [5f2e46be0a](https://linux-hardware.org/?probe=5f2e46be0a) | May 05, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [352e8b2616](https://linux-hardware.org/?probe=352e8b2616) | May 03, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [017222d810](https://linux-hardware.org/?probe=017222d810) | May 02, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [b54238dc33](https://linux-hardware.org/?probe=b54238dc33) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [62d194e85e](https://linux-hardware.org/?probe=62d194e85e) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [e2acacabb3](https://linux-hardware.org/?probe=e2acacabb3) | Apr 30, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8aa973e0f5](https://linux-hardware.org/?probe=8aa973e0f5) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [9419686ec7](https://linux-hardware.org/?probe=9419686ec7) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [1f61fda034](https://linux-hardware.org/?probe=1f61fda034) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [b2616ea409](https://linux-hardware.org/?probe=b2616ea409) | Apr 28, 2023 |
| HP            | Unknown                     | Notebook    | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [169e095fab](https://linux-hardware.org/?probe=169e095fab) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c80b811f3e](https://linux-hardware.org/?probe=c80b811f3e) | Apr 27, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [072b88204c](https://linux-hardware.org/?probe=072b88204c) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f02e8339e9](https://linux-hardware.org/?probe=f02e8339e9) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [8de5e39740](https://linux-hardware.org/?probe=8de5e39740) | Apr 25, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [e4064abe78](https://linux-hardware.org/?probe=e4064abe78) | Apr 24, 2023 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [fc22fb4921](https://linux-hardware.org/?probe=fc22fb4921) | Apr 23, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e3dc4788e7](https://linux-hardware.org/?probe=e3dc4788e7) | Apr 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [8db6f88fd3](https://linux-hardware.org/?probe=8db6f88fd3) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [28631c09aa](https://linux-hardware.org/?probe=28631c09aa) | Apr 22, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | Notebook    | [edf0d6d941](https://linux-hardware.org/?probe=edf0d6d941) | Apr 21, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [4004491274](https://linux-hardware.org/?probe=4004491274) | Apr 21, 2023 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [712657fa81](https://linux-hardware.org/?probe=712657fa81) | Apr 20, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [47831c9091](https://linux-hardware.org/?probe=47831c9091) | Apr 18, 2023 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [c248c05349](https://linux-hardware.org/?probe=c248c05349) | Apr 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [28d52a565b](https://linux-hardware.org/?probe=28d52a565b) | Apr 18, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [9552ef2174](https://linux-hardware.org/?probe=9552ef2174) | Apr 17, 2023 |
| HP            | 18E7                        | Desktop     | [ef0b00cf80](https://linux-hardware.org/?probe=ef0b00cf80) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d40208e7f6](https://linux-hardware.org/?probe=d40208e7f6) | Apr 17, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7371569bbf](https://linux-hardware.org/?probe=7371569bbf) | Apr 15, 2023 |
| Supermicro    | X10SAE                      | Server      | [4b0cfec9a7](https://linux-hardware.org/?probe=4b0cfec9a7) | Apr 15, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [d1084f0d90](https://linux-hardware.org/?probe=d1084f0d90) | Apr 15, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [6419c7fb77](https://linux-hardware.org/?probe=6419c7fb77) | Apr 15, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [26db4eab1f](https://linux-hardware.org/?probe=26db4eab1f) | Apr 15, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [d49b1775be](https://linux-hardware.org/?probe=d49b1775be) | Apr 14, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [1c8d776510](https://linux-hardware.org/?probe=1c8d776510) | Apr 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [2f29d1d7b8](https://linux-hardware.org/?probe=2f29d1d7b8) | Apr 13, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [06e6f2f745](https://linux-hardware.org/?probe=06e6f2f745) | Apr 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [222d699e31](https://linux-hardware.org/?probe=222d699e31) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [4cea64e81b](https://linux-hardware.org/?probe=4cea64e81b) | Apr 13, 2023 |
| GEO           | GeoBook 120                 | Notebook    | [2e51a1bab5](https://linux-hardware.org/?probe=2e51a1bab5) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [7b4e6e07cf](https://linux-hardware.org/?probe=7b4e6e07cf) | Apr 12, 2023 |
| Unknown       | ACB20                       | Notebook    | [16543ac693](https://linux-hardware.org/?probe=16543ac693) | Apr 12, 2023 |
| Unknown       | ACB20                       | Notebook    | [4c0422096b](https://linux-hardware.org/?probe=4c0422096b) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [3e3a141713](https://linux-hardware.org/?probe=3e3a141713) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [07bd1b4df7](https://linux-hardware.org/?probe=07bd1b4df7) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [7863ff02eb](https://linux-hardware.org/?probe=7863ff02eb) | Apr 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eb03b75c27](https://linux-hardware.org/?probe=eb03b75c27) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [b35b8e1503](https://linux-hardware.org/?probe=b35b8e1503) | Apr 09, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0913458ee](https://linux-hardware.org/?probe=e0913458ee) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [5a044a37f7](https://linux-hardware.org/?probe=5a044a37f7) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [81a8d7a1fc](https://linux-hardware.org/?probe=81a8d7a1fc) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c599e701fc](https://linux-hardware.org/?probe=c599e701fc) | Apr 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7aec6da94d](https://linux-hardware.org/?probe=7aec6da94d) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [aa3b0a7d6f](https://linux-hardware.org/?probe=aa3b0a7d6f) | Apr 04, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [731bd99503](https://linux-hardware.org/?probe=731bd99503) | Apr 03, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [e97e71fc7a](https://linux-hardware.org/?probe=e97e71fc7a) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [f96e01d74d](https://linux-hardware.org/?probe=f96e01d74d) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [539137fb36](https://linux-hardware.org/?probe=539137fb36) | Apr 01, 2023 |
| Unknown       | ACB20                       | Notebook    | [6e70bacda5](https://linux-hardware.org/?probe=6e70bacda5) | Apr 01, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [4434a1266b](https://linux-hardware.org/?probe=4434a1266b) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [fbef2fe274](https://linux-hardware.org/?probe=fbef2fe274) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d79127e48c](https://linux-hardware.org/?probe=d79127e48c) | Mar 31, 2023 |
| Intel         | X79                         | Desktop     | [c06125262b](https://linux-hardware.org/?probe=c06125262b) | Mar 31, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [f0540604bc](https://linux-hardware.org/?probe=f0540604bc) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1c575e8cb6](https://linux-hardware.org/?probe=1c575e8cb6) | Mar 30, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [e4d56ca8c8](https://linux-hardware.org/?probe=e4d56ca8c8) | Mar 28, 2023 |
| ASUSTek       | M3N78 PRO                   | Desktop     | [0f9abe9400](https://linux-hardware.org/?probe=0f9abe9400) | Mar 28, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [5242d56a0f](https://linux-hardware.org/?probe=5242d56a0f) | Mar 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [ebb59fa31d](https://linux-hardware.org/?probe=ebb59fa31d) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b084807397](https://linux-hardware.org/?probe=b084807397) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bc38c5ed22](https://linux-hardware.org/?probe=bc38c5ed22) | Mar 26, 2023 |
| Gigabyte      | AERO 15 XD                  | Notebook    | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6601de8aae](https://linux-hardware.org/?probe=6601de8aae) | Mar 25, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9240540b33](https://linux-hardware.org/?probe=9240540b33) | Mar 24, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| Intel         | powered classmate PC        | Notebook    | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70a7fd895e](https://linux-hardware.org/?probe=70a7fd895e) | Mar 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | Notebook    | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [0912041935](https://linux-hardware.org/?probe=0912041935) | Mar 21, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | Notebook    | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [61e1c5eff9](https://linux-hardware.org/?probe=61e1c5eff9) | Mar 21, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ca34d8e7d4](https://linux-hardware.org/?probe=ca34d8e7d4) | Mar 20, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [eba8868f8b](https://linux-hardware.org/?probe=eba8868f8b) | Mar 20, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [7891e82ac4](https://linux-hardware.org/?probe=7891e82ac4) | Mar 17, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6ad4034797](https://linux-hardware.org/?probe=6ad4034797) | Mar 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7e6ae6ba16](https://linux-hardware.org/?probe=7e6ae6ba16) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [8c4023bd5d](https://linux-hardware.org/?probe=8c4023bd5d) | Mar 16, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [ab9d7b857f](https://linux-hardware.org/?probe=ab9d7b857f) | Mar 16, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [7659c07b7c](https://linux-hardware.org/?probe=7659c07b7c) | Mar 16, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [26b62abfc9](https://linux-hardware.org/?probe=26b62abfc9) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ab4a88037a](https://linux-hardware.org/?probe=ab4a88037a) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [23e21d1440](https://linux-hardware.org/?probe=23e21d1440) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [34ad3eb730](https://linux-hardware.org/?probe=34ad3eb730) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [06c53ecdec](https://linux-hardware.org/?probe=06c53ecdec) | Mar 15, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [7637d41bf3](https://linux-hardware.org/?probe=7637d41bf3) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [727390b14d](https://linux-hardware.org/?probe=727390b14d) | Mar 14, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [0eefdece9c](https://linux-hardware.org/?probe=0eefdece9c) | Mar 13, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [7320131972](https://linux-hardware.org/?probe=7320131972) | Mar 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [01bfc3e026](https://linux-hardware.org/?probe=01bfc3e026) | Mar 13, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1ad75bea9c](https://linux-hardware.org/?probe=1ad75bea9c) | Mar 12, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [3ec784f6be](https://linux-hardware.org/?probe=3ec784f6be) | Mar 11, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [126b4a73a2](https://linux-hardware.org/?probe=126b4a73a2) | Mar 11, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7ba7da9138](https://linux-hardware.org/?probe=7ba7da9138) | Mar 10, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [46b213149e](https://linux-hardware.org/?probe=46b213149e) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [ed7724b921](https://linux-hardware.org/?probe=ed7724b921) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [6605d9e257](https://linux-hardware.org/?probe=6605d9e257) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0c14a418fb](https://linux-hardware.org/?probe=0c14a418fb) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [aa31db4d3f](https://linux-hardware.org/?probe=aa31db4d3f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3629efc5a5](https://linux-hardware.org/?probe=3629efc5a5) | Mar 08, 2023 |
| HP            | ZBook 17                    | Notebook    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Dell          | 0773VG A01                  | Desktop     | [d954bdd915](https://linux-hardware.org/?probe=d954bdd915) | Mar 07, 2023 |
| ASRock        | H310M-HDV                   | Desktop     | [316510fe69](https://linux-hardware.org/?probe=316510fe69) | Mar 07, 2023 |
| Acer          | Aspire X1400                | Desktop     | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ebf75e7be8](https://linux-hardware.org/?probe=ebf75e7be8) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ef186545cb](https://linux-hardware.org/?probe=ef186545cb) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [21db48a23b](https://linux-hardware.org/?probe=21db48a23b) | Mar 06, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Dell          | Latitude 7390               | Notebook    | [892100e074](https://linux-hardware.org/?probe=892100e074) | Mar 05, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [e5e134cc80](https://linux-hardware.org/?probe=e5e134cc80) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4eb7bea837](https://linux-hardware.org/?probe=4eb7bea837) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1d24df340b](https://linux-hardware.org/?probe=1d24df340b) | Mar 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [82994d7312](https://linux-hardware.org/?probe=82994d7312) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| MSI           | GP65 Leopard 9SF            | Notebook    | [45f56a0c5b](https://linux-hardware.org/?probe=45f56a0c5b) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [950e36afc7](https://linux-hardware.org/?probe=950e36afc7) | Mar 03, 2023 |
| Schenker      | XMG NEO (M19, RTX 2070)     | Notebook    | [c45dbeb188](https://linux-hardware.org/?probe=c45dbeb188) | Mar 02, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [686db926da](https://linux-hardware.org/?probe=686db926da) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [15318beac5](https://linux-hardware.org/?probe=15318beac5) | Feb 27, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [a5496030e7](https://linux-hardware.org/?probe=a5496030e7) | Feb 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [659ff1672e](https://linux-hardware.org/?probe=659ff1672e) | Feb 26, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [92f1f7d3b5](https://linux-hardware.org/?probe=92f1f7d3b5) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [824f4eafd0](https://linux-hardware.org/?probe=824f4eafd0) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [101d8d4577](https://linux-hardware.org/?probe=101d8d4577) | Feb 25, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [bc6078dda0](https://linux-hardware.org/?probe=bc6078dda0) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [012415eb50](https://linux-hardware.org/?probe=012415eb50) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [e1c3e1611f](https://linux-hardware.org/?probe=e1c3e1611f) | Feb 24, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [802ba906a0](https://linux-hardware.org/?probe=802ba906a0) | Feb 23, 2023 |
| Sony          | SVF1521N6EW                 | Notebook    | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [b2ef9d5ede](https://linux-hardware.org/?probe=b2ef9d5ede) | Feb 21, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [2752a9660a](https://linux-hardware.org/?probe=2752a9660a) | Feb 19, 2023 |
| Dell          | G3 3590                     | Notebook    | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| HP            | ENVY 15                     | Notebook    | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e81d0741bb](https://linux-hardware.org/?probe=e81d0741bb) | Feb 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [dd63e968bd](https://linux-hardware.org/?probe=dd63e968bd) | Feb 17, 2023 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [a32189e068](https://linux-hardware.org/?probe=a32189e068) | Feb 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e486b2bb46](https://linux-hardware.org/?probe=e486b2bb46) | Feb 15, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [486f7258a6](https://linux-hardware.org/?probe=486f7258a6) | Feb 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [dc91c0e32b](https://linux-hardware.org/?probe=dc91c0e32b) | Feb 14, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [c3d08b4f2e](https://linux-hardware.org/?probe=c3d08b4f2e) | Feb 13, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b25d844a19](https://linux-hardware.org/?probe=b25d844a19) | Feb 12, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| HP            | 17E2                        | Mini pc     | [e99d3c0a69](https://linux-hardware.org/?probe=e99d3c0a69) | Feb 12, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| HP            | 17E2                        | Mini pc     | [ff80271dce](https://linux-hardware.org/?probe=ff80271dce) | Feb 11, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9b95bc446b](https://linux-hardware.org/?probe=9b95bc446b) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c4eb0b2a62](https://linux-hardware.org/?probe=c4eb0b2a62) | Feb 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [9de8235ca5](https://linux-hardware.org/?probe=9de8235ca5) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [fdaab67fe9](https://linux-hardware.org/?probe=fdaab67fe9) | Feb 09, 2023 |
| Acer          | TravelMate P256-M           | Notebook    | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [eece150870](https://linux-hardware.org/?probe=eece150870) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [4ff2fc81bc](https://linux-hardware.org/?probe=4ff2fc81bc) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| HP            | 834F                        | Desktop     | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c1862b275d](https://linux-hardware.org/?probe=c1862b275d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1aa5d63f0c](https://linux-hardware.org/?probe=1aa5d63f0c) | Feb 01, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| HP            | 8054                        | Desktop     | [36f5306e37](https://linux-hardware.org/?probe=36f5306e37) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS79000    | Notebook    | [2b397905e1](https://linux-hardware.org/?probe=2b397905e1) | Jan 29, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [95f5d0904e](https://linux-hardware.org/?probe=95f5d0904e) | Jan 26, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | Notebook    | [3b7c64dc34](https://linux-hardware.org/?probe=3b7c64dc34) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | Notebook    | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [5a5a26c29e](https://linux-hardware.org/?probe=5a5a26c29e) | Jan 24, 2023 |
| Positivo      | N1240                       | Notebook    | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [bc95b86800](https://linux-hardware.org/?probe=bc95b86800) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3eb7e4f3cf](https://linux-hardware.org/?probe=3eb7e4f3cf) | Jan 22, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [4807ed03d5](https://linux-hardware.org/?probe=4807ed03d5) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4d52b408c2](https://linux-hardware.org/?probe=4d52b408c2) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9a0b1c62f5](https://linux-hardware.org/?probe=9a0b1c62f5) | Jan 18, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [f0137b1f08](https://linux-hardware.org/?probe=f0137b1f08) | Jan 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [dcc8c2a63b](https://linux-hardware.org/?probe=dcc8c2a63b) | Jan 17, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [b49ce7a30a](https://linux-hardware.org/?probe=b49ce7a30a) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| AZW           | S3                          | Mini pc     | [0e94de97c8](https://linux-hardware.org/?probe=0e94de97c8) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [ef011d0700](https://linux-hardware.org/?probe=ef011d0700) | Jan 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| HP            | 8054                        | Desktop     | [d4398dee29](https://linux-hardware.org/?probe=d4398dee29) | Jan 08, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c74a6daaaa](https://linux-hardware.org/?probe=c74a6daaaa) | Jan 07, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| HP            | 1497                        | Desktop     | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [406b407b64](https://linux-hardware.org/?probe=406b407b64) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [569f5cd751](https://linux-hardware.org/?probe=569f5cd751) | Jan 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8c219aafe4](https://linux-hardware.org/?probe=8c219aafe4) | Jan 05, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b6bf9d074f](https://linux-hardware.org/?probe=b6bf9d074f) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [6f4cc6e4c7](https://linux-hardware.org/?probe=6f4cc6e4c7) | Jan 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [6c40dc7dd6](https://linux-hardware.org/?probe=6c40dc7dd6) | Jan 03, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [f097aa1c92](https://linux-hardware.org/?probe=f097aa1c92) | Jan 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6d047b6620](https://linux-hardware.org/?probe=6d047b6620) | Dec 30, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [26e56628ec](https://linux-hardware.org/?probe=26e56628ec) | Dec 30, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [dc7201711c](https://linux-hardware.org/?probe=dc7201711c) | Dec 30, 2022 |
| Lenovo        | 3181 SEK0T35577 IOT 4247... | Mini pc     | [fa1b60ae23](https://linux-hardware.org/?probe=fa1b60ae23) | Dec 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [4ca2070d42](https://linux-hardware.org/?probe=4ca2070d42) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | Notebook    | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| HP            | 1589                        | Desktop     | [4769414712](https://linux-hardware.org/?probe=4769414712) | Dec 24, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | Notebook    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [353cbeb5c8](https://linux-hardware.org/?probe=353cbeb5c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Biostar       | X470GTN                     | Desktop     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [3bc811ef2a](https://linux-hardware.org/?probe=3bc811ef2a) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c5c5c07485](https://linux-hardware.org/?probe=c5c5c07485) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c992b15fbe](https://linux-hardware.org/?probe=c992b15fbe) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [4378eff64f](https://linux-hardware.org/?probe=4378eff64f) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | Desktop     | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [94b281cfa1](https://linux-hardware.org/?probe=94b281cfa1) | Dec 09, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| Dell          | 0215PR A02                  | Desktop     | [b9d16b98d2](https://linux-hardware.org/?probe=b9d16b98d2) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9cc2be8747](https://linux-hardware.org/?probe=9cc2be8747) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [d7b2726838](https://linux-hardware.org/?probe=d7b2726838) | Dec 08, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f5bd8a0e5b](https://linux-hardware.org/?probe=f5bd8a0e5b) | Dec 07, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a742429421](https://linux-hardware.org/?probe=a742429421) | Dec 06, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f2025f3847](https://linux-hardware.org/?probe=f2025f3847) | Dec 04, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [69ed3a0345](https://linux-hardware.org/?probe=69ed3a0345) | Dec 02, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1775ec9d4b](https://linux-hardware.org/?probe=1775ec9d4b) | Dec 01, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [097d1c062e](https://linux-hardware.org/?probe=097d1c062e) | Dec 01, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [ae30b95cd8](https://linux-hardware.org/?probe=ae30b95cd8) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [56c9fb93ce](https://linux-hardware.org/?probe=56c9fb93ce) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1ec2520541](https://linux-hardware.org/?probe=1ec2520541) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0fd2d81cad](https://linux-hardware.org/?probe=0fd2d81cad) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | Desktop     | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | Notebook    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | Notebook    | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [2ff9360669](https://linux-hardware.org/?probe=2ff9360669) | Nov 17, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| Dell          | Studio 1737                 | Notebook    | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [ab1c46c857](https://linux-hardware.org/?probe=ab1c46c857) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [4d4d5aa456](https://linux-hardware.org/?probe=4d4d5aa456) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [51d6598b74](https://linux-hardware.org/?probe=51d6598b74) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a49a1465d3](https://linux-hardware.org/?probe=a49a1465d3) | Nov 10, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [5e151ea22f](https://linux-hardware.org/?probe=5e151ea22f) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [55d7ddf0c8](https://linux-hardware.org/?probe=55d7ddf0c8) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [049bac8501](https://linux-hardware.org/?probe=049bac8501) | Nov 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5ca257fd77](https://linux-hardware.org/?probe=5ca257fd77) | Nov 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Notebook    | [bd9e0be4e8](https://linux-hardware.org/?probe=bd9e0be4e8) | Nov 03, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | Notebook    | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP            | 8653 A                      | Desktop     | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel         | B75                         | Desktop     | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP            | 3029h                       | Desktop     | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | Notebook    | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| MSI           | Z87 XPOWER                  | Desktop     | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| HP            | 2000                        | Notebook    | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| HP            | 1998                        | Desktop     | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Nobara/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Nobara 37 | 265       | 31.4%   |
| Nobara 36 | 255       | 30.21%  |
| Nobara 38 | 243       | 28.79%  |
| Nobara 39 | 81        | 9.6%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Nobara | 821       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.4.10-202.fsync.fc38.x86_64  | 52        | 5.79%   |
| 6.0.14-201.fsync.fc36.x86_64  | 38        | 4.23%   |
| 6.0.10-201.fc36.x86_64        | 37        | 4.12%   |
| 6.2.14-300.fsync.fc37.x86_64  | 33        | 3.67%   |
| 6.3.12-204.fsync.fc38.x86_64  | 27        | 3.01%   |
| 6.7.0-204.fsync.fc39.x86_64   | 25        | 2.78%   |
| 6.1.14-201.fsync.fc37.x86_64  | 25        | 2.78%   |
| 5.19.14-201.fsync.fc36.x86_64 | 25        | 2.78%   |
| 6.6.9-200.fsync.fc39.x86_64   | 23        | 2.56%   |
| 6.1.11-201.fsync.fc37.x86_64  | 20        | 2.23%   |
| 6.5.9-201.fsync.fc38.x86_64   | 19        | 2.12%   |
| 6.2.12-200.fsync.fc37.x86_64  | 18        | 2%      |
| 6.5.6-200.fsync.fc38.x86_64   | 17        | 1.89%   |
| 6.2.6-201.fsync.fc37.x86_64   | 17        | 1.89%   |
| 6.1.9-200.fsync.fc37.x86_64   | 17        | 1.89%   |
| 6.1.4-203.fsync.fc37.x86_64   | 17        | 1.89%   |
| 6.6.7-203.fsync.fc38.x86_64   | 16        | 1.78%   |
| 5.19.9-201.fsync.fc36.x86_64  | 16        | 1.78%   |
| 5.19.7-204.fsync.fc36.x86_64  | 16        | 1.78%   |
| 6.3.10-200.fsync.fc38.x86_64  | 14        | 1.56%   |
| 6.3.7-200.fsync.fc37.x86_64   | 13        | 1.45%   |
| 6.2.10-200.fsync.fc37.x86_64  | 13        | 1.45%   |
| 6.7.0-201.fsync.fc39.x86_64   | 12        | 1.34%   |
| 6.0.7-201.fsync.fc36.x86_64   | 12        | 1.34%   |
| 5.19.16-201.fsync.fc36.x86_64 | 12        | 1.34%   |
| 6.3.12-205.fsync.fc38.x86_64  | 11        | 1.22%   |
| 6.2.8-200.fsync.fc37.x86_64   | 11        | 1.22%   |
| 6.0.5-201.fsync.fc36.x86_64   | 11        | 1.22%   |
| 6.0.16-301.fsync.fc37.x86_64  | 11        | 1.22%   |
| 5.18.13-201.fsync.fc36.x86_64 | 11        | 1.22%   |
| 6.6.8-200.fsync.fc39.x86_64   | 10        | 1.11%   |
| 6.3.5-201.fsync.fc37.x86_64   | 10        | 1.11%   |
| 6.1.6-203.fsync.fc37.x86_64   | 10        | 1.11%   |
| 6.6.4-202.fsync.fc38.x86_64   | 9         | 1%      |
| 6.6.2-201.fsync.fc38.x86_64   | 9         | 1%      |
| 6.2.11-201.fsync.fc37.x86_64  | 9         | 1%      |
| 6.1.8-202.fsync.fc37.x86_64   | 9         | 1%      |
| 6.0.9-201.fc36.x86_64         | 9         | 1%      |
| 6.6.7-203.fsync.fc39.x86_64   | 8         | 0.89%   |
| 6.5.9-200.fsync.fc38.x86_64   | 8         | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.10  | 60        | 6.7%    |
| 6.3.12  | 52        | 5.8%    |
| 6.7.0   | 43        | 4.8%    |
| 6.0.14  | 38        | 4.24%   |
| 6.0.10  | 37        | 4.13%   |
| 6.2.14  | 34        | 3.79%   |
| 6.6.7   | 28        | 3.13%   |
| 6.5.9   | 26        | 2.9%    |
| 6.1.14  | 25        | 2.79%   |
| 5.19.14 | 25        | 2.79%   |
| 6.6.9   | 23        | 2.57%   |
| 6.3.10  | 20        | 2.23%   |
| 6.1.11  | 20        | 2.23%   |
| 6.5.6   | 18        | 2.01%   |
| 6.2.12  | 18        | 2.01%   |
| 5.19.7  | 18        | 2.01%   |
| 6.2.6   | 17        | 1.9%    |
| 6.1.9   | 17        | 1.9%    |
| 6.1.4   | 17        | 1.9%    |
| 6.5.5   | 16        | 1.79%   |
| 6.2.11  | 16        | 1.79%   |
| 6.1.6   | 16        | 1.79%   |
| 6.0.7   | 16        | 1.79%   |
| 5.19.9  | 16        | 1.79%   |
| 6.3.7   | 14        | 1.56%   |
| 6.2.10  | 13        | 1.45%   |
| 6.1.8   | 13        | 1.45%   |
| 6.0.9   | 13        | 1.45%   |
| 6.6.4   | 12        | 1.34%   |
| 6.5.3   | 12        | 1.34%   |
| 5.19.16 | 12        | 1.34%   |
| 6.6.8   | 11        | 1.23%   |
| 6.3.5   | 11        | 1.23%   |
| 6.2.8   | 11        | 1.23%   |
| 6.0.5   | 11        | 1.23%   |
| 6.0.16  | 11        | 1.23%   |
| 5.18.13 | 11        | 1.23%   |
| 6.6.2   | 9         | 1%      |
| 5.19.12 | 8         | 0.89%   |
| 5.19.10 | 8         | 0.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 131       | 14.95%  |
| 5.19    | 114       | 13.01%  |
| 6.1     | 108       | 12.33%  |
| 6.2     | 106       | 12.1%   |
| 6.3     | 105       | 11.99%  |
| 6.6     | 89        | 10.16%  |
| 6.5     | 80        | 9.13%   |
| 6.4     | 66        | 7.53%   |
| 6.7     | 43        | 4.91%   |
| 5.18    | 34        | 3.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 821       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 539       | 65.1%   |
| KDE5          | 275       | 33.21%  |
| Unknown       | 9         | 1.09%   |
| GNOME Classic | 2         | 0.24%   |
| X-Cinnamon    | 1         | 0.12%   |
| sway          | 1         | 0.12%   |
| Hyprland      | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 664       | 79.52%  |
| X11     | 163       | 19.52%  |
| Unknown | 6         | 0.72%   |
| Tty     | 2         | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 674       | 81.3%   |
| GDM     | 101       | 12.18%  |
| SDDM    | 50        | 6.03%   |
| LightDM | 4         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 422       | 51.21%  |
| en_GB   | 67        | 8.13%   |
| de_DE   | 65        | 7.89%   |
| es_ES   | 29        | 3.52%   |
| es_MX   | 26        | 3.16%   |
| en_CA   | 22        | 2.67%   |
| ru_RU   | 21        | 2.55%   |
| pt_BR   | 16        | 1.94%   |
| fr_FR   | 16        | 1.94%   |
| it_IT   | 15        | 1.82%   |
| pl_PL   | 14        | 1.7%    |
| es_AR   | 13        | 1.58%   |
| en_NZ   | 9         | 1.09%   |
| en_AU   | 7         | 0.85%   |
| de_AT   | 7         | 0.85%   |
| en_IN   | 6         | 0.73%   |
| es_CO   | 5         | 0.61%   |
| Unknown | 5         | 0.61%   |
| pt_PT   | 4         | 0.49%   |
| nl_NL   | 4         | 0.49%   |
| tr_TR   | 3         | 0.36%   |
| hu_HU   | 3         | 0.36%   |
| es_CL   | 3         | 0.36%   |
| en_PH   | 3         | 0.36%   |
| da_DK   | 3         | 0.36%   |
| zh_TW   | 2         | 0.24%   |
| uk_UA   | 2         | 0.24%   |
| sv_SE   | 2         | 0.24%   |
| nl_BE   | 2         | 0.24%   |
| nb_NO   | 2         | 0.24%   |
| fi_FI   | 2         | 0.24%   |
| es_VE   | 2         | 0.24%   |
| en_ZA   | 2         | 0.24%   |
| ar_SA   | 2         | 0.24%   |
| sk_SK   | 1         | 0.12%   |
| ro_RO   | 1         | 0.12%   |
| hr_HR   | 1         | 0.12%   |
| fr_BE   | 1         | 0.12%   |
| es_UY   | 1         | 0.12%   |
| es_US   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 679       | 82%     |
| BIOS | 149       | 18%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 670       | 81.21%  |
| Ext4  | 153       | 18.55%  |
| Xfs   | 2         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 667       | 80.26%  |
| GPT     | 156       | 18.77%  |
| MBR     | 8         | 0.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 776       | 94.17%  |
| Yes       | 48        | 5.83%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 741       | 90.15%  |
| Yes       | 81        | 9.85%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 189       | 23.02%  |
| MSI                                  | 117       | 14.25%  |
| Lenovo                               | 88        | 10.72%  |
| Hewlett-Packard                      | 83        | 10.11%  |
| Gigabyte Technology                  | 74        | 9.01%   |
| ASRock                               | 63        | 7.67%   |
| Dell                                 | 55        | 6.7%    |
| Acer                                 | 27        | 3.29%   |
| Apple                                | 20        | 2.44%   |
| Intel                                | 11        | 1.34%   |
| Toshiba                              | 7         | 0.85%   |
| Samsung Electronics                  | 6         | 0.73%   |
| AZW                                  | 5         | 0.61%   |
| Alienware                            | 5         | 0.61%   |
| Microsoft                            | 4         | 0.49%   |
| Unknown                              | 4         | 0.49%   |
| Notebook                             | 3         | 0.37%   |
| Biostar                              | 3         | 0.37%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.24%   |
| Positivo                             | 2         | 0.24%   |
| Pegatron                             | 2         | 0.24%   |
| ONE-NETBOOK                          | 2         | 0.24%   |
| NZXT                                 | 2         | 0.24%   |
| Monster                              | 2         | 0.24%   |
| Infinix                              | 2         | 0.24%   |
| GPU Company                          | 2         | 0.24%   |
| Google                               | 2         | 0.24%   |
| Fujitsu                              | 2         | 0.24%   |
| Acidanthera                          | 2         | 0.24%   |
| ZOTAC                                | 1         | 0.12%   |
| Valve                                | 1         | 0.12%   |
| TUXEDO                               | 1         | 0.12%   |
| Timi                                 | 1         | 0.12%   |
| System76                             | 1         | 0.12%   |
| Supermicro                           | 1         | 0.12%   |
| Sony                                 | 1         | 0.12%   |
| Schenker                             | 1         | 0.12%   |
| Razer                                | 1         | 0.12%   |
| Protectli                            | 1         | 0.12%   |
| Packard Bell                         | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| MSI MS-7B86                         | 10        | 1.22%   |
| MSI MS-7C37                         | 8         | 0.97%   |
| Unknown                             | 8         | 0.97%   |
| MSI MS-7C91                         | 6         | 0.73%   |
| MSI MS-7C02                         | 6         | 0.73%   |
| MSI MS-7B79                         | 6         | 0.73%   |
| ASUS All Series                     | 6         | 0.73%   |
| MSI MS-7D25                         | 5         | 0.61%   |
| MSI MS-7C56                         | 5         | 0.61%   |
| ASUS ROG STRIX B550-F GAMING        | 5         | 0.61%   |
| ASUS TUF Gaming X570-PLUS           | 4         | 0.49%   |
| ASUS TUF Gaming B550M-PLUS          | 4         | 0.49%   |
| ASUS ROG STRIX B650E-I GAMING WIFI  | 4         | 0.49%   |
| MSI MS-7C35                         | 3         | 0.37%   |
| Lenovo Legion 5 15ARH05 82B5        | 3         | 0.37%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 3         | 0.37%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 3         | 0.37%   |
| Lenovo IdeaPad C340-14API 81N6      | 3         | 0.37%   |
| Intel X79                           | 3         | 0.37%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 3         | 0.37%   |
| Gigabyte X570 AORUS ELITE           | 3         | 0.37%   |
| Gigabyte B550 AORUS ELITE V2        | 3         | 0.37%   |
| Dell XPS 8700                       | 3         | 0.37%   |
| Dell Inspiron 15 3520               | 3         | 0.37%   |
| Dell G5 5505                        | 3         | 0.37%   |
| AZW SER                             | 3         | 0.37%   |
| ASUS PRIME A320M-K                  | 3         | 0.37%   |
| ASRock B450M Pro4                   | 3         | 0.37%   |
| Samsung 730QED                      | 2         | 0.24%   |
| NZXT N7 B650E                       | 2         | 0.24%   |
| MSI MS-7C87                         | 2         | 0.24%   |
| MSI MS-7B85                         | 2         | 0.24%   |
| MSI MS-7B84                         | 2         | 0.24%   |
| MSI MS-7B51                         | 2         | 0.24%   |
| MSI MS-7B17                         | 2         | 0.24%   |
| MSI MS-7A34                         | 2         | 0.24%   |
| MSI MS-7977                         | 2         | 0.24%   |
| MSI MS-7971                         | 2         | 0.24%   |
| MSI MS-7817                         | 2         | 0.24%   |
| MSI MS-7721                         | 2         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 59        | 7.19%   |
| ASUS TUF           | 31        | 3.78%   |
| ASUS PRIME         | 26        | 3.17%   |
| Lenovo IdeaPad     | 25        | 3.05%   |
| Lenovo ThinkPad    | 22        | 2.68%   |
| HP Pavilion        | 21        | 2.56%   |
| Lenovo Legion      | 15        | 1.83%   |
| ASUS VivoBook      | 13        | 1.58%   |
| Acer Aspire        | 13        | 1.58%   |
| Dell Inspiron      | 11        | 1.34%   |
| MSI MS-7B86        | 10        | 1.22%   |
| HP Laptop          | 9         | 1.1%    |
| MSI MS-7C37        | 8         | 0.97%   |
| HP ENVY            | 8         | 0.97%   |
| HP EliteBook       | 8         | 0.97%   |
| Gigabyte X570      | 8         | 0.97%   |
| Dell Precision     | 8         | 0.97%   |
| Dell Latitude      | 8         | 0.97%   |
| Acer Nitro         | 8         | 0.97%   |
| Unknown            | 8         | 0.97%   |
| Dell OptiPlex      | 7         | 0.85%   |
| Toshiba Satellite  | 6         | 0.73%   |
| MSI MS-7C91        | 6         | 0.73%   |
| MSI MS-7C02        | 6         | 0.73%   |
| MSI MS-7B79        | 6         | 0.73%   |
| Gigabyte B550      | 6         | 0.73%   |
| ASUS All           | 6         | 0.73%   |
| MSI MS-7D25        | 5         | 0.61%   |
| MSI MS-7C56        | 5         | 0.61%   |
| Lenovo Yoga        | 5         | 0.61%   |
| Lenovo ThinkCentre | 5         | 0.61%   |
| HP ZBook           | 5         | 0.61%   |
| HP EliteDesk       | 5         | 0.61%   |
| Gigabyte B550M     | 5         | 0.61%   |
| Dell XPS           | 5         | 0.61%   |
| ASUS ASUS          | 5         | 0.61%   |
| ASRock B450M       | 5         | 0.61%   |
| Microsoft Surface  | 4         | 0.49%   |
| HP Compaq          | 4         | 0.49%   |
| Dell Vostro        | 4         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 114       | 13.89%  |
| 2021 | 110       | 13.4%   |
| 2019 | 105       | 12.79%  |
| 2018 | 97        | 11.81%  |
| 2022 | 90        | 10.96%  |
| 2013 | 44        | 5.36%   |
| 2012 | 42        | 5.12%   |
| 2014 | 40        | 4.87%   |
| 2017 | 39        | 4.75%   |
| 2016 | 34        | 4.14%   |
| 2023 | 33        | 4.02%   |
| 2015 | 28        | 3.41%   |
| 2011 | 20        | 2.44%   |
| 2010 | 9         | 1.1%    |
| 2009 | 8         | 0.97%   |
| 2008 | 6         | 0.73%   |
| 2007 | 2         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 426       | 51.89%  |
| Notebook    | 334       | 40.68%  |
| Convertible | 25        | 3.05%   |
| Mini pc     | 14        | 1.71%   |
| Tablet      | 11        | 1.34%   |
| All in one  | 9         | 1.1%    |
| Other       | 1         | 0.12%   |
| Server      | 1         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 821       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 818       | 99.63%  |
| Yes  | 3         | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 235       | 28.45%  |
| 32.01-64.0      | 191       | 23.12%  |
| 4.01-8.0        | 130       | 15.74%  |
| 8.01-16.0       | 130       | 15.74%  |
| 24.01-32.0      | 49        | 5.93%   |
| 3.01-4.0        | 48        | 5.81%   |
| 64.01-256.0     | 37        | 4.48%   |
| 1.01-2.0        | 3         | 0.36%   |
| 2.01-3.0        | 2         | 0.24%   |
| More than 256.0 | 1         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 384       | 44.04%  |
| 3.01-4.0   | 197       | 22.59%  |
| 2.01-3.0   | 159       | 18.23%  |
| 8.01-16.0  | 82        | 9.4%    |
| 1.01-2.0   | 36        | 4.13%   |
| 16.01-24.0 | 10        | 1.15%   |
| 24.01-32.0 | 3         | 0.34%   |
| 32.01-64.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 365       | 43.61%  |
| 2      | 241       | 28.79%  |
| 3      | 113       | 13.5%   |
| 4      | 54        | 6.45%   |
| 5      | 35        | 4.18%   |
| 6      | 12        | 1.43%   |
| 7      | 7         | 0.84%   |
| 8      | 5         | 0.6%    |
| 10     | 2         | 0.24%   |
| 9      | 2         | 0.24%   |
| 0      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 675       | 81.62%  |
| Yes       | 152       | 18.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 725       | 87.99%  |
| No        | 99        | 12.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 643       | 77.94%  |
| No        | 182       | 22.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 583       | 70.58%  |
| No        | 243       | 29.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 241       | 29.35%  |
| Germany      | 84        | 10.23%  |
| UK           | 40        | 4.87%   |
| Canada       | 32        | 3.9%    |
| Spain        | 28        | 3.41%   |
| Russia       | 27        | 3.29%   |
| Brazil       | 26        | 3.17%   |
| France       | 22        | 2.68%   |
| Argentina    | 22        | 2.68%   |
| Poland       | 21        | 2.56%   |
| Italy        | 21        | 2.56%   |
| Mexico       | 20        | 2.44%   |
| Netherlands  | 14        | 1.71%   |
| Sweden       | 12        | 1.46%   |
| India        | 12        | 1.46%   |
| Australia    | 12        | 1.46%   |
| Austria      | 11        | 1.34%   |
| New Zealand  | 9         | 1.1%    |
| Colombia     | 9         | 1.1%    |
| Indonesia    | 8         | 0.97%   |
| Hungary      | 8         | 0.97%   |
| Chile        | 8         | 0.97%   |
| Turkey       | 7         | 0.85%   |
| Portugal     | 7         | 0.85%   |
| Philippines  | 7         | 0.85%   |
| Romania      | 6         | 0.73%   |
| Finland      | 6         | 0.73%   |
| Venezuela    | 5         | 0.61%   |
| Saudi Arabia | 5         | 0.61%   |
| Belgium      | 5         | 0.61%   |
| Norway       | 4         | 0.49%   |
| Estonia      | 4         | 0.49%   |
| Czechia      | 4         | 0.49%   |
| Vietnam      | 3         | 0.37%   |
| South Africa | 3         | 0.37%   |
| Serbia       | 3         | 0.37%   |
| Malaysia     | 3         | 0.37%   |
| Greece       | 3         | 0.37%   |
| Denmark      | 3         | 0.37%   |
| Croatia      | 3         | 0.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Buenos Aires  | 6         | 0.7%    |
| Berlin        | 6         | 0.7%    |
| Stockholm     | 5         | 0.59%   |
| Melbourne     | 5         | 0.59%   |
| Los Angeles   | 5         | 0.59%   |
| Guadalajara   | 5         | 0.59%   |
| Auckland      | 5         | 0.59%   |
| Atlanta       | 5         | 0.59%   |
| Toronto       | 4         | 0.47%   |
| San Francisco | 4         | 0.47%   |
| Milano        | 4         | 0.47%   |
| Wroclaw       | 3         | 0.35%   |
| Wellington    | 3         | 0.35%   |
| Warsaw        | 3         | 0.35%   |
| Vienna        | 3         | 0.35%   |
| Tucson        | 3         | 0.35%   |
| Sydney        | 3         | 0.35%   |
| Seattle       | 3         | 0.35%   |
| Sao Paulo     | 3         | 0.35%   |
| Santiago      | 3         | 0.35%   |
| San Jose      | 3         | 0.35%   |
| Rotterdam     | 3         | 0.35%   |
| Rome          | 3         | 0.35%   |
| Poznan        | 3         | 0.35%   |
| Philadelphia  | 3         | 0.35%   |
| Perm          | 3         | 0.35%   |
| Nuremberg     | 3         | 0.35%   |
| Milan         | 3         | 0.35%   |
| Madrid        | 3         | 0.35%   |
| Kuala Lumpur  | 3         | 0.35%   |
| Fortaleza     | 3         | 0.35%   |
| Denver        | 3         | 0.35%   |
| Cologne       | 3         | 0.35%   |
| Cardiff       | 3         | 0.35%   |
| Calgary       | 3         | 0.35%   |
| Bucharest     | 3         | 0.35%   |
| Boynton Beach | 3         | 0.35%   |
| Amsterdam     | 3         | 0.35%   |
| Wuppertal     | 2         | 0.23%   |
| Wasilla       | 2         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 265       | 423    | 17.83%  |
| WDC                          | 162       | 230    | 10.9%   |
| Seagate                      | 158       | 216    | 10.63%  |
| SanDisk                      | 108       | 133    | 7.27%   |
| Kingston                     | 94        | 106    | 6.33%   |
| Toshiba                      | 79        | 97     | 5.32%   |
| Crucial                      | 79        | 110    | 5.32%   |
| Micron/Crucial Technology    | 45        | 56     | 3.03%   |
| Intel                        | 43        | 54     | 2.89%   |
| Phison Electronics           | 41        | 48     | 2.76%   |
| SK hynix                     | 38        | 42     | 2.56%   |
| Micron Technology            | 31        | 35     | 2.09%   |
| Unknown                      | 24        | 35     | 1.62%   |
| Kingston Technology Company  | 22        | 27     | 1.48%   |
| PNY                          | 17        | 26     | 1.14%   |
| Hitachi                      | 17        | 23     | 1.14%   |
| KIOXIA                       | 16        | 19     | 1.08%   |
| HGST                         | 14        | 17     | 0.94%   |
| China                        | 14        | 14     | 0.94%   |
| A-DATA Technology            | 14        | 15     | 0.94%   |
| SPCC                         | 11        | 14     | 0.74%   |
| Silicon Motion               | 11        | 13     | 0.74%   |
| Realtek Semiconductor        | 11        | 13     | 0.74%   |
| Apple                        | 11        | 12     | 0.74%   |
| ADATA Technology             | 10        | 11     | 0.67%   |
| Team                         | 9         | 9      | 0.61%   |
| Phison                       | 8         | 9      | 0.54%   |
| MAXIO Technology (Hangzhou)  | 8         | 8      | 0.54%   |
| Intenso                      | 6         | 7      | 0.4%    |
| Verbatim                     | 4         | 5      | 0.27%   |
| Lexar                        | 4         | 5      | 0.27%   |
| Fanxiang                     | 4         | 4      | 0.27%   |
| Corsair                      | 4         | 4      | 0.27%   |
| Unknown                      | 4         | 5      | 0.27%   |
| USB3.0                       | 3         | 3      | 0.2%    |
| Shenzhen Longsys Electronics | 3         | 3      | 0.2%    |
| SABRENT                      | 3         | 4      | 0.2%    |
| OCZ                          | 3         | 3      | 0.2%    |
| KIOXIA-EXCERIA               | 3         | 4      | 0.2%    |
| KingFast                     | 3         | 3      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 64        | 3.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 32        | 1.89%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 31        | 1.83%   |
| Kingston SA400S37240G 240GB SSD                       | 30        | 1.77%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 19        | 1.12%   |
| Phison E12 NVMe Controller 1TB                        | 19        | 1.12%   |
| Samsung SSD 860 EVO 500GB                             | 16        | 0.95%   |
| Samsung SSD 860 EVO 1TB                               | 15        | 0.89%   |
| Intel SSD 660P Series 1024GB                          | 15        | 0.89%   |
| Crucial CT1000MX500SSD1 1TB                           | 15        | 0.89%   |
| Samsung SSD 850 EVO 500GB                             | 14        | 0.83%   |
| Crucial CT1000BX500SSD1 1TB                           | 14        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 13        | 0.77%   |
| Seagate ST2000DM008-2FR102 2TB                        | 12        | 0.71%   |
| Samsung SSD 980 1TB                                   | 12        | 0.71%   |
| Toshiba DT01ACA100 1TB                                | 11        | 0.65%   |
| Samsung SSD 850 EVO 250GB                             | 11        | 0.65%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 11        | 0.65%   |
| Kingston SA400S37480G 480GB SSD                       | 11        | 0.65%   |
| Unknown MMC Card  64GB                                | 8         | 0.47%   |
| Toshiba MQ04ABF100 1TB                                | 8         | 0.47%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 8         | 0.47%   |
| Samsung SSD 870 EVO 1TB                               | 8         | 0.47%   |
| Crucial CT240BX500SSD1 240GB                          | 8         | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 7         | 0.41%   |
| Toshiba DT01ACA200 2TB                                | 7         | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 7         | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 7         | 0.41%   |
| Samsung NVMe SSD Controller SM951/PM951 256GB         | 7         | 0.41%   |
| Crucial CT500MX500SSD1 500GB                          | 7         | 0.41%   |
| Crucial CT2000MX500SSD1 2TB                           | 7         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 6         | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 6         | 0.35%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 6         | 0.35%   |
| Toshiba MQ01ABD100 1TB                                | 6         | 0.35%   |
| Toshiba HDWD110 1TB                                   | 6         | 0.35%   |
| Seagate ST500DM002-1BD142 500GB                       | 6         | 0.35%   |
| Seagate ST2000DM001-1ER164 2TB                        | 6         | 0.35%   |
| Sandisk WD Blue SN570 1TB                             | 6         | 0.35%   |
| Samsung SSD 870 QVO 1TB                               | 6         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 155       | 209    | 37.08%  |
| WDC                 | 126       | 176    | 30.14%  |
| Toshiba             | 66        | 81     | 15.79%  |
| Samsung Electronics | 18        | 29     | 4.31%   |
| Hitachi             | 17        | 23     | 4.07%   |
| HGST                | 14        | 17     | 3.35%   |
| Apple               | 7         | 7      | 1.67%   |
| ASMT                | 3         | 6      | 0.72%   |
| Unknown             | 2         | 2      | 0.48%   |
| Maxtor              | 2         | 2      | 0.48%   |
| JMicron Technology  | 2         | 5      | 0.48%   |
| TO Exter            | 1         | 1      | 0.24%   |
| SSK                 | 1         | 1      | 0.24%   |
| SABRENT             | 1         | 2      | 0.24%   |
| HGST HTS            | 1         | 1      | 0.24%   |
| Hewlett-Packard     | 1         | 1      | 0.24%   |
| Fujitsu             | 1         | 1      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 126       | 169    | 24.56%  |
| Crucial             | 77        | 108    | 15.01%  |
| Kingston            | 70        | 77     | 13.65%  |
| WDC                 | 39        | 45     | 7.6%    |
| SanDisk             | 29        | 34     | 5.65%   |
| PNY                 | 17        | 26     | 3.31%   |
| China               | 14        | 14     | 2.73%   |
| A-DATA Technology   | 14        | 15     | 2.73%   |
| SPCC                | 11        | 14     | 2.14%   |
| Team                | 8         | 8      | 1.56%   |
| Intel               | 8         | 9      | 1.56%   |
| Micron Technology   | 7         | 8      | 1.36%   |
| Toshiba             | 6         | 7      | 1.17%   |
| SK hynix            | 6         | 6      | 1.17%   |
| Intenso             | 5         | 5      | 0.97%   |
| Verbatim            | 3         | 4      | 0.58%   |
| USB3.0              | 3         | 3      | 0.58%   |
| OCZ                 | 3         | 3      | 0.58%   |
| Lexar               | 3         | 4      | 0.58%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.58%   |
| Corsair             | 3         | 3      | 0.58%   |
| Apacer              | 3         | 3      | 0.58%   |
| Wibtek              | 2         | 2      | 0.39%   |
| Transcend           | 2         | 2      | 0.39%   |
| Seagate             | 2         | 2      | 0.39%   |
| SABRENT             | 2         | 2      | 0.39%   |
| Plextor             | 2         | 2      | 0.39%   |
| Patriot             | 2         | 2      | 0.39%   |
| Mushkin             | 2         | 2      | 0.39%   |
| LITEON              | 2         | 2      | 0.39%   |
| KingSpec            | 2         | 2      | 0.39%   |
| KingFast            | 2         | 2      | 0.39%   |
| Fanxiang            | 2         | 2      | 0.39%   |
| Drevo               | 2         | 2      | 0.39%   |
| Apple               | 2         | 2      | 0.39%   |
| XSTAR               | 1         | 1      | 0.19%   |
| XrayDisk            | 1         | 1      | 0.19%   |
| WDC WDS             | 1         | 1      | 0.19%   |
| V-GeN               | 1         | 1      | 0.19%   |
| SuperSSpeed         | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 488       | 718    | 37.92%  |
| SSD     | 412       | 625    | 32.01%  |
| HDD     | 345       | 564    | 26.81%  |
| Unknown | 27        | 33     | 2.1%    |
| MMC     | 15        | 17     | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 555       | 1141   | 49.78%  |
| NVMe | 486       | 713    | 43.59%  |
| SAS  | 59        | 86     | 5.29%   |
| MMC  | 15        | 17     | 1.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 364       | 538    | 43.8%   |
| 0.51-1.0   | 287       | 391    | 34.54%  |
| 1.01-2.0   | 108       | 163    | 13%     |
| 3.01-4.0   | 29        | 39     | 3.49%   |
| 4.01-10.0  | 23        | 33     | 2.77%   |
| 2.01-3.0   | 16        | 20     | 1.93%   |
| 10.01-20.0 | 4         | 5      | 0.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 173       | 20.5%   |
| 1001-2000      | 162       | 19.19%  |
| 251-500        | 149       | 17.65%  |
| More than 3000 | 119       | 14.1%   |
| 101-250        | 115       | 13.63%  |
| 2001-3000      | 58        | 6.87%   |
| Unknown        | 23        | 2.73%   |
| 21-50          | 22        | 2.61%   |
| 51-100         | 17        | 2.01%   |
| 1-20           | 6         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 196       | 22.5%   |
| 1-20           | 143       | 16.42%  |
| 101-250        | 132       | 15.15%  |
| 251-500        | 96        | 11.02%  |
| 51-100         | 89        | 10.22%  |
| 501-1000       | 80        | 9.18%   |
| 1001-2000      | 54        | 6.2%    |
| More than 3000 | 30        | 3.44%   |
| 2001-3000      | 28        | 3.21%   |
| Unknown        | 23        | 2.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2         | 2      | 10.53%  |
| WDC WD30EZRX-00DC0B0 3TB                       | 1         | 1      | 5.26%   |
| WDC WD20EURS-63S48Y0 2TB                       | 1         | 1      | 5.26%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1         | 1      | 5.26%   |
| WDC WD10EACS-00D6B0 1TB                        | 1         | 1      | 5.26%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 1      | 5.26%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1         | 1      | 5.26%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 5.26%   |
| Samsung Electronics SSD 980 1TB                | 1         | 1      | 5.26%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 5.26%   |
| Samsung Electronics HD161GJ 160GB              | 1         | 1      | 5.26%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 5.26%   |
| Hitachi HTS54323 320GB                         | 1         | 1      | 5.26%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 5.26%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 5.26%   |
| ASMT ASM1156-PM 480GB                          | 1         | 2      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 31.58%  |
| Seagate             | 3         | 3      | 15.79%  |
| Samsung Electronics | 3         | 3      | 15.79%  |
| HGST                | 2         | 2      | 10.53%  |
| SK hynix            | 1         | 1      | 5.26%   |
| Ramsta              | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Hitachi             | 1         | 1      | 5.26%   |
| ASMT                | 1         | 2      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 42.86%  |
| Seagate             | 3         | 3      | 21.43%  |
| HGST                | 2         | 2      | 14.29%  |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| ASMT                | 1         | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 15     | 73.68%  |
| SSD  | 3         | 3      | 15.79%  |
| NVMe | 2         | 2      | 10.53%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 682       | 1622   | 79.49%  |
| Works    | 158       | 314    | 18.41%  |
| Malfunc  | 17        | 20     | 1.98%   |
| Limited  | 1         | 1      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 414       | 31.53%  |
| AMD                                  | 308       | 23.46%  |
| Samsung Electronics                  | 165       | 12.57%  |
| SanDisk                              | 88        | 6.7%    |
| Kingston Technology Company          | 50        | 3.81%   |
| Phison Electronics                   | 49        | 3.73%   |
| Micron/Crucial Technology            | 47        | 3.58%   |
| ASMedia Technology                   | 33        | 2.51%   |
| SK hynix                             | 32        | 2.44%   |
| Micron Technology                    | 24        | 1.83%   |
| KIOXIA                               | 16        | 1.22%   |
| Realtek Semiconductor                | 12        | 0.91%   |
| Silicon Motion                       | 11        | 0.84%   |
| ADATA Technology                     | 10        | 0.76%   |
| Nvidia                               | 8         | 0.61%   |
| MAXIO Technology (Hangzhou)          | 8         | 0.61%   |
| Toshiba America Info Systems         | 7         | 0.53%   |
| Marvell Technology Group             | 6         | 0.46%   |
| Solidigm                             | 3         | 0.23%   |
| Shenzhen Longsys Electronics         | 3         | 0.23%   |
| JMicron Technology                   | 3         | 0.23%   |
| Union Memory (Shenzhen)              | 2         | 0.15%   |
| Seagate Technology                   | 2         | 0.15%   |
| Broadcom / LSI                       | 2         | 0.15%   |
| Apple                                | 2         | 0.15%   |
| Solid State Storage Technology       | 1         | 0.08%   |
| Silicon Image                        | 1         | 0.08%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.08%   |
| Netac Technology                     | 1         | 0.08%   |
| LSI Logic / Symbios Logic            | 1         | 0.08%   |
| Lenovo                               | 1         | 0.08%   |
| INNOGRIT                             | 1         | 0.08%   |
| Biwin Storage Technology             | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 180       | 12.37%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 76        | 5.22%   |
| AMD 400 Series Chipset SATA Controller                                         | 63        | 4.33%   |
| AMD 500 Series Chipset SATA Controller                                         | 55        | 3.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 38        | 2.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 35        | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 32        | 2.2%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 32        | 2.2%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 31        | 2.13%   |
| AMD 600 Series Chipset SATA Controller                                         | 31        | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 24        | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 23        | 1.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 22        | 1.51%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 20        | 1.37%   |
| Phison E12 NVMe Controller                                                     | 20        | 1.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 18        | 1.24%   |
| Intel SSD 660P Series                                                          | 17        | 1.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 17        | 1.17%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 17        | 1.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 17        | 1.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 17        | 1.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 17        | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 17        | 1.17%   |
| Intel SATA Controller [RAID mode]                                              | 16        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 15        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 14        | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                            | 14        | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 14        | 0.96%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 13        | 0.89%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 13        | 0.89%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 13        | 0.89%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 13        | 0.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 13        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12        | 0.82%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 11        | 0.76%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 11        | 0.76%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 10        | 0.69%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 646       | 52.52%  |
| NVMe | 486       | 39.51%  |
| RAID | 65        | 5.28%   |
| IDE  | 29        | 2.36%   |
| SAS  | 4         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 453       | 55.18%  |
| AMD    | 368       | 44.82%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 21        | 2.55%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 17        | 2.06%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 16        | 1.94%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 14        | 1.7%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 13        | 1.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 11        | 1.33%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 10        | 1.21%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 9         | 1.09%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 8         | 0.97%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.97%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 8         | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 0.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 0.97%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 8         | 0.97%   |
| AMD Ryzen 7 7800X3D 8-Core Processor          | 8         | 0.97%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 8         | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 0.85%   |
| AMD Ryzen 7 5800X3D 8-Core Processor          | 7         | 0.85%   |
| AMD Ryzen 7 5700X 8-Core Processor            | 7         | 0.85%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 7         | 0.85%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 7         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.73%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 6         | 0.73%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 0.73%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 6         | 0.73%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.73%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 6         | 0.73%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 6         | 0.73%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 0.73%   |
| AMD Ryzen 5 7600X 6-Core Processor            | 6         | 0.73%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 6         | 0.73%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 0.73%   |
| AMD FX-8350 Eight-Core Processor              | 6         | 0.73%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 0.61%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 5         | 0.61%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 5         | 0.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 0.61%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.61%   |
| AMD Ryzen 9 6900HX with Radeon Graphics       | 5         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 140       | 16.99%  |
| AMD Ryzen 5             | 132       | 16.02%  |
| Intel Core i7           | 126       | 15.29%  |
| AMD Ryzen 7             | 113       | 13.71%  |
| Other                   | 92        | 11.17%  |
| AMD Ryzen 9             | 55        | 6.67%   |
| Intel Core i3           | 36        | 4.37%   |
| Intel Xeon              | 18        | 2.18%   |
| Intel Celeron           | 16        | 1.94%   |
| AMD Ryzen 3             | 16        | 1.94%   |
| AMD FX                  | 13        | 1.58%   |
| Intel Core i9           | 9         | 1.09%   |
| Intel Pentium           | 7         | 0.85%   |
| Intel Core 2 Duo        | 7         | 0.85%   |
| AMD A6                  | 5         | 0.61%   |
| Intel Atom              | 4         | 0.49%   |
| AMD A4                  | 4         | 0.49%   |
| AMD A10                 | 4         | 0.49%   |
| AMD Phenom II X6        | 3         | 0.36%   |
| Intel Pentium Dual-Core | 2         | 0.24%   |
| AMD Ryzen Threadripper  | 2         | 0.24%   |
| AMD Athlon              | 2         | 0.24%   |
| Intel Core m7           | 1         | 0.12%   |
| Intel Core 2 Quad       | 1         | 0.12%   |
| Intel Core 2 Extreme    | 1         | 0.12%   |
| AMD Turion 64 X2 Mobile | 1         | 0.12%   |
| AMD Ryzen 7 PRO         | 1         | 0.12%   |
| AMD Ryzen 5 PRO         | 1         | 0.12%   |
| AMD Ryzen 3 PRO         | 1         | 0.12%   |
| AMD PRO A10             | 1         | 0.12%   |
| AMD Phenom II X4        | 1         | 0.12%   |
| AMD Phenom II           | 1         | 0.12%   |
| AMD Phenom              | 1         | 0.12%   |
| AMD G                   | 1         | 0.12%   |
| AMD E2                  | 1         | 0.12%   |
| AMD E                   | 1         | 0.12%   |
| AMD Athlon X4           | 1         | 0.12%   |
| AMD Athlon II X2        | 1         | 0.12%   |
| AMD Athlon Dual Core    | 1         | 0.12%   |
| AMD A8                  | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 236       | 28.71%  |
| 6      | 189       | 22.99%  |
| 8      | 155       | 18.86%  |
| 2      | 146       | 17.76%  |
| 12     | 34        | 4.14%   |
| 16     | 25        | 3.04%   |
| 14     | 13        | 1.58%   |
| 10     | 13        | 1.58%   |
| 3      | 4         | 0.49%   |
| 1      | 4         | 0.49%   |
| 24     | 3         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 819       | 99.76%  |
| 2      | 2         | 0.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 687       | 83.27%  |
| 1      | 138       | 16.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 821       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 280       | 33.45%  |
| 0x08701021 | 39        | 4.66%   |
| 0x0a50000c | 29        | 3.46%   |
| 0x0a601203 | 24        | 2.87%   |
| 0x08108109 | 23        | 2.75%   |
| 0x0a50000d | 21        | 2.51%   |
| 0x306c3    | 20        | 2.39%   |
| 0x306a9    | 20        | 2.39%   |
| 0x0800820d | 19        | 2.27%   |
| 0x0a201016 | 17        | 2.03%   |
| 0x206a7    | 16        | 1.91%   |
| 0x906ea    | 15        | 1.79%   |
| 0x0a20120a | 15        | 1.79%   |
| 0x40651    | 14        | 1.67%   |
| 0x906e9    | 13        | 1.55%   |
| 0xa0652    | 12        | 1.43%   |
| 0x08600106 | 11        | 1.31%   |
| 0x08701030 | 10        | 1.19%   |
| 0x08608103 | 10        | 1.19%   |
| 0x506e3    | 9         | 1.08%   |
| 0x0a404102 | 9         | 1.08%   |
| 0x906a3    | 8         | 0.96%   |
| 0x806c1    | 8         | 0.96%   |
| 0x08600104 | 8         | 0.96%   |
| 0x06000822 | 8         | 0.96%   |
| 0x806e9    | 7         | 0.84%   |
| 0xa0655    | 6         | 0.72%   |
| 0x90672    | 6         | 0.72%   |
| 0x0a201205 | 6         | 0.72%   |
| 0x0a201204 | 6         | 0.72%   |
| 0x08001138 | 6         | 0.72%   |
| 0x906ed    | 5         | 0.6%    |
| 0x806d1    | 5         | 0.6%    |
| 0x406e3    | 5         | 0.6%    |
| 0x0a601206 | 5         | 0.6%    |
| 0x0a20120e | 5         | 0.6%    |
| 0xa0653    | 4         | 0.48%   |
| 0x906ec    | 4         | 0.48%   |
| 0x206d7    | 4         | 0.48%   |
| 0x1067a    | 4         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 3            | 120       | 14.6%   |
| KabyLake         | 108       | 13.14%  |
| Zen 2            | 78        | 9.49%   |
| Unknown          | 70        | 8.52%   |
| Haswell          | 66        | 8.03%   |
| Zen+             | 52        | 6.33%   |
| Alderlake Hybrid | 43        | 5.23%   |
| IvyBridge        | 38        | 4.62%   |
| Skylake          | 37        | 4.5%    |
| CometLake        | 36        | 4.38%   |
| SandyBridge      | 31        | 3.77%   |
| TigerLake        | 23        | 2.8%    |
| Icelake          | 21        | 2.55%   |
| Zen              | 16        | 1.95%   |
| Piledriver       | 15        | 1.82%   |
| Penryn           | 10        | 1.22%   |
| Broadwell        | 10        | 1.22%   |
| Silvermont       | 9         | 1.09%   |
| K10              | 7         | 0.85%   |
| Excavator        | 6         | 0.73%   |
| Goldmont plus    | 5         | 0.61%   |
| Steamroller      | 4         | 0.49%   |
| Westmere         | 3         | 0.36%   |
| Bobcat           | 3         | 0.36%   |
| Puma             | 2         | 0.24%   |
| K8 Hammer        | 2         | 0.24%   |
| Core             | 2         | 0.24%   |
| Nehalem          | 1         | 0.12%   |
| Jaguar           | 1         | 0.12%   |
| Goldmont         | 1         | 0.12%   |
| Bulldozer        | 1         | 0.12%   |
| Bonnell          | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 370       | 36.13%  |
| Nvidia | 352       | 34.38%  |
| Intel  | 302       | 29.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 45        | 4.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 38        | 3.55%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 33        | 3.08%   |
| AMD Raphael                                                                 | 28        | 2.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 27        | 2.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 24        | 2.24%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 23        | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 21        | 1.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 19        | 1.77%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 19        | 1.77%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 19        | 1.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 18        | 1.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 17        | 1.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 17        | 1.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 16        | 1.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 15        | 1.4%    |
| Intel HD Graphics 620                                                       | 14        | 1.31%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 14        | 1.31%   |
| Intel HD Graphics 530                                                       | 13        | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 13        | 1.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12        | 1.12%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 12        | 1.12%   |
| AMD Rembrandt [Radeon 680M]                                                 | 12        | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 11        | 1.03%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 11        | 1.03%   |
| AMD Lucienne                                                                | 11        | 1.03%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 10        | 0.93%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 10        | 0.93%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 10        | 0.93%   |
| Intel UHD Graphics 620                                                      | 9         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 8         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 8         | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 8         | 0.75%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 8         | 0.75%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 7         | 0.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7         | 0.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 7         | 0.65%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 7         | 0.65%   |
| Intel HD Graphics 630                                                       | 7         | 0.65%   |
| Intel HD Graphics 5500                                                      | 7         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 265       | 32.12%  |
| 1 x Nvidia         | 193       | 23.39%  |
| 1 x Intel          | 153       | 18.55%  |
| Intel + Nvidia     | 107       | 12.97%  |
| AMD + Nvidia       | 47        | 5.7%    |
| 2 x AMD            | 36        | 4.36%   |
| Intel + AMD        | 19        | 2.3%    |
| 2 x Nvidia         | 3         | 0.36%   |
| Other              | 1         | 0.12%   |
| Intel + 2 x Nvidia | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 534       | 64.57%  |
| Proprietary | 278       | 33.62%  |
| Unknown     | 15        | 1.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 359       | 42.94%  |
| 7.01-8.0   | 115       | 13.76%  |
| 0.01-0.5   | 88        | 10.53%  |
| 8.01-16.0  | 77        | 9.21%   |
| 1.01-2.0   | 67        | 8.01%   |
| 3.01-4.0   | 50        | 5.98%   |
| 0.51-1.0   | 32        | 3.83%   |
| 5.01-6.0   | 25        | 2.99%   |
| 16.01-24.0 | 17        | 2.03%   |
| 2.01-3.0   | 6         | 0.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 133       | 13.49%  |
| AU Optronics            | 82        | 8.32%   |
| Goldstar                | 71        | 7.2%    |
| BOE                     | 69        | 7%      |
| LG Display              | 55        | 5.58%   |
| Chimei Innolux          | 53        | 5.38%   |
| Dell                    | 52        | 5.27%   |
| Acer                    | 52        | 5.27%   |
| Ancor Communications    | 37        | 3.75%   |
| BenQ                    | 35        | 3.55%   |
| Hewlett-Packard         | 33        | 3.35%   |
| ASUSTek Computer        | 30        | 3.04%   |
| AOC                     | 27        | 2.74%   |
| MSI                     | 19        | 1.93%   |
| PANDA                   | 17        | 1.72%   |
| Apple                   | 16        | 1.62%   |
| ViewSonic               | 13        | 1.32%   |
| Sony                    | 13        | 1.32%   |
| Sharp                   | 13        | 1.32%   |
| Lenovo                  | 13        | 1.32%   |
| Vizio                   | 12        | 1.22%   |
| Philips                 | 11        | 1.12%   |
| Iiyama                  | 8         | 0.81%   |
| Gigabyte Technology     | 8         | 0.81%   |
| InfoVision              | 7         | 0.71%   |
| Sceptre Tech            | 6         | 0.61%   |
| HKC                     | 6         | 0.61%   |
| Toshiba                 | 5         | 0.51%   |
| Unknown                 | 4         | 0.41%   |
| TMX                     | 4         | 0.41%   |
| Panasonic               | 4         | 0.41%   |
| Insignia                | 4         | 0.41%   |
| Eizo                    | 4         | 0.41%   |
| Chi Mei Optoelectronics | 4         | 0.41%   |
| Pixio                   | 3         | 0.3%    |
| NEC Computers           | 3         | 0.3%    |
| HUAWEI                  | 3         | 0.3%    |
| Viotek                  | 2         | 0.2%    |
| Valve                   | 2         | 0.2%    |
| SNC                     | 2         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 8         | 0.78%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5         | 0.49%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 5         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.49%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 4         | 0.39%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.39%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 4         | 0.39%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 4         | 0.39%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 4         | 0.39%   |
| Acer GN246HL ACR02F9 1920x1080 531x299mm 24.0-inch                    | 4         | 0.39%   |
| Vizio V405-H9 VIZ1039 3840x2160 878x485mm 39.5-inch                   | 3         | 0.29%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 3         | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3         | 0.29%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 3         | 0.29%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                    | 3         | 0.29%   |
| MSI G32C4 MSI3DA6 1920x1080 698x393mm 31.5-inch                       | 3         | 0.29%   |
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                       | 3         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 0.29%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 3         | 0.29%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch           | 3         | 0.29%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.29%   |
| BenQ EX3501R BNQ7F5E 3440x1440 819x346mm 35.0-inch                    | 3         | 0.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.29%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch         | 3         | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.29%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch          | 3         | 0.29%   |
| ASUSTek Computer VA27EHE AUS27D2 1920x1080 598x336mm 27.0-inch        | 3         | 0.29%   |
| ASUSTek Computer PA278QV AUS2700 2560x1440 597x336mm 27.0-inch        | 3         | 0.29%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3         | 0.29%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 3         | 0.29%   |
| Acer GN246HL ACR02FA 1920x1080 531x299mm 24.0-inch                    | 3         | 0.29%   |
| Vizio E32-C1 VIZ1004 1920x1080 698x392mm 31.5-inch                    | 2         | 0.2%    |
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                   | 2         | 0.2%    |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch         | 2         | 0.2%    |
| Toshiba TV TSB0108 1920x540                                           | 2         | 0.2%    |
| TMX TL070FVXS01-0 TMX0002 1920x1080 160x100mm 7.4-inch                | 2         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 435       | 47.33%  |
| 2560x1440 (QHD)    | 115       | 12.51%  |
| 3840x2160 (4K)     | 94        | 10.23%  |
| 1366x768 (WXGA)    | 80        | 8.71%   |
| 3440x1440          | 24        | 2.61%   |
| 1680x1050 (WSXGA+) | 22        | 2.39%   |
| 1920x1200 (WUXGA)  | 18        | 1.96%   |
| 2560x1600          | 14        | 1.52%   |
| 1440x900 (WXGA+)   | 14        | 1.52%   |
| 2560x1080          | 13        | 1.41%   |
| 1280x1024 (SXGA)   | 12        | 1.31%   |
| 1600x900 (HD+)     | 10        | 1.09%   |
| 1360x768           | 10        | 1.09%   |
| 1920x540           | 9         | 0.98%   |
| 2880x1800          | 8         | 0.87%   |
| 3840x1080          | 5         | 0.54%   |
| 2288x1287          | 4         | 0.44%   |
| 1280x800 (WXGA)    | 4         | 0.44%   |
| 2736x1824          | 3         | 0.33%   |
| 2240x1400          | 3         | 0.33%   |
| 3840x2400          | 2         | 0.22%   |
| 3840x1600          | 2         | 0.22%   |
| 3200x2000          | 2         | 0.22%   |
| 1600x1200          | 2         | 0.22%   |
| Unknown            | 2         | 0.22%   |
| 800x1280           | 1         | 0.11%   |
| 5760x1080          | 1         | 0.11%   |
| 3840x2560          | 1         | 0.11%   |
| 3456x2160          | 1         | 0.11%   |
| 3200x1800 (QHD+)   | 1         | 0.11%   |
| 2520x1680          | 1         | 0.11%   |
| 2160x1440          | 1         | 0.11%   |
| 2048x1152          | 1         | 0.11%   |
| 1600x2560          | 1         | 0.11%   |
| 1280x960           | 1         | 0.11%   |
| 1280x720 (HD)      | 1         | 0.11%   |
| 1080x1920          | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 185       | 18.95%  |
| 27      | 139       | 14.24%  |
| 24      | 75        | 7.68%   |
| 23      | 67        | 6.86%   |
| 31      | 55        | 5.64%   |
| 13      | 54        | 5.53%   |
| 21      | 52        | 5.33%   |
| 17      | 46        | 4.71%   |
| 14      | 43        | 4.41%   |
| 34      | 28        | 2.87%   |
| 84      | 16        | 1.64%   |
| 16      | 16        | 1.64%   |
| Unknown | 16        | 1.64%   |
| 19      | 15        | 1.54%   |
| 22      | 14        | 1.43%   |
| 18      | 13        | 1.33%   |
| 40      | 12        | 1.23%   |
| 32      | 12        | 1.23%   |
| 72      | 11        | 1.13%   |
| 20      | 11        | 1.13%   |
| 48      | 10        | 1.02%   |
| 29      | 7         | 0.72%   |
| 42      | 6         | 0.61%   |
| 26      | 6         | 0.61%   |
| 12      | 5         | 0.51%   |
| 54      | 4         | 0.41%   |
| 49      | 4         | 0.41%   |
| 35      | 4         | 0.41%   |
| 33      | 4         | 0.41%   |
| 142     | 3         | 0.31%   |
| 69      | 3         | 0.31%   |
| 52      | 3         | 0.31%   |
| 43      | 3         | 0.31%   |
| 38      | 3         | 0.31%   |
| 28      | 3         | 0.31%   |
| 25      | 3         | 0.31%   |
| 11      | 3         | 0.31%   |
| 7       | 3         | 0.31%   |
| 60      | 2         | 0.2%    |
| 55      | 2         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 272       | 28.39%  |
| 501-600        | 257       | 26.83%  |
| 401-500        | 100       | 10.44%  |
| 601-700        | 79        | 8.25%   |
| 351-400        | 51        | 5.32%   |
| 701-800        | 43        | 4.49%   |
| 201-300        | 38        | 3.97%   |
| 1501-2000      | 32        | 3.34%   |
| 1001-1500      | 29        | 3.03%   |
| 801-900        | 22        | 2.3%    |
| Unknown        | 16        | 1.67%   |
| 901-1000       | 10        | 1.04%   |
| More than 2000 | 4         | 0.42%   |
| 101-200        | 4         | 0.42%   |
| 1-100          | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 654       | 78.89%  |
| 16/10   | 89        | 10.74%  |
| 21/9    | 38        | 4.58%   |
| 5/4     | 14        | 1.69%   |
| 3/2     | 9         | 1.09%   |
| 32/9    | 7         | 0.84%   |
| 4/3     | 6         | 0.72%   |
| 1.00    | 3         | 0.36%   |
| Unknown | 3         | 0.36%   |
| 1.96    | 2         | 0.24%   |
| 0.62    | 2         | 0.24%   |
| 0.67    | 1         | 0.12%   |
| 0.56    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 188       | 19.62%  |
| 201-250        | 163       | 17.01%  |
| 301-350        | 146       | 15.24%  |
| 351-500        | 103       | 10.75%  |
| 81-90          | 75        | 7.83%   |
| More than 1000 | 55        | 5.74%   |
| 151-200        | 44        | 4.59%   |
| 501-1000       | 37        | 3.86%   |
| 121-130        | 36        | 3.76%   |
| 251-300        | 27        | 2.82%   |
| 71-80          | 23        | 2.4%    |
| 141-150        | 16        | 1.67%   |
| Unknown        | 16        | 1.67%   |
| 111-120        | 12        | 1.25%   |
| 1-40           | 5         | 0.52%   |
| 131-140        | 4         | 0.42%   |
| 61-70          | 3         | 0.31%   |
| 51-60          | 3         | 0.31%   |
| 41-50          | 1         | 0.1%    |
| 91-100         | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 353       | 38.16%  |
| 121-160       | 222       | 24%     |
| 101-120       | 204       | 22.05%  |
| 161-240       | 64        | 6.92%   |
| 1-50          | 43        | 4.65%   |
| More than 240 | 23        | 2.49%   |
| Unknown       | 16        | 1.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 600       | 71.68%  |
| 2     | 182       | 21.74%  |
| 3     | 29        | 3.46%   |
| 0     | 24        | 2.87%   |
| 4     | 2         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 504       | 38.71%  |
| Intel                           | 422       | 32.41%  |
| Qualcomm Atheros                | 76        | 5.84%   |
| MediaTek                        | 66        | 5.07%   |
| Broadcom                        | 59        | 4.53%   |
| TP-Link                         | 28        | 2.15%   |
| Microsoft                       | 21        | 1.61%   |
| Ralink Technology               | 14        | 1.08%   |
| Broadcom Limited                | 10        | 0.77%   |
| ASIX Electronics                | 10        | 0.77%   |
| Xiaomi                          | 8         | 0.61%   |
| Samsung Electronics             | 7         | 0.54%   |
| Qualcomm                        | 6         | 0.46%   |
| Aquantia                        | 6         | 0.46%   |
| Nvidia                          | 5         | 0.38%   |
| Marvell Technology Group        | 5         | 0.38%   |
| ASUSTek Computer                | 5         | 0.38%   |
| Ralink                          | 4         | 0.31%   |
| Qualcomm Atheros Communications | 4         | 0.31%   |
| Motorola PCS                    | 4         | 0.31%   |
| Lenovo                          | 3         | 0.23%   |
| Sierra Wireless                 | 2         | 0.15%   |
| OPPO Electronics                | 2         | 0.15%   |
| Oculus VR                       | 2         | 0.15%   |
| NetGear                         | 2         | 0.15%   |
| Hewlett-Packard                 | 2         | 0.15%   |
| D-Link System                   | 2         | 0.15%   |
| D-Link                          | 2         | 0.15%   |
| Belkin Components               | 2         | 0.15%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.08%   |
| Wacom                           | 1         | 0.08%   |
| T & A Mobile Phones             | 1         | 0.08%   |
| ROCCAT                          | 1         | 0.08%   |
| Panasonic (Matsushita)          | 1         | 0.08%   |
| Padix (Rockfire)                | 1         | 0.08%   |
| Microchip Technology            | 1         | 0.08%   |
| Mellanox Technologies           | 1         | 0.08%   |
| Loupedeck                       | 1         | 0.08%   |
| Linksys                         | 1         | 0.08%   |
| JMicron Technology              | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 347       | 23.16%  |
| Realtek RTL8125 2.5GbE Controller                                      | 82        | 5.47%   |
| Intel Wi-Fi 6 AX200                                                    | 77        | 5.14%   |
| Intel I211 Gigabit Network Connection                                  | 42        | 2.8%    |
| Intel Ethernet Controller I225-V                                       | 42        | 2.8%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 28        | 1.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 24        | 1.6%    |
| Intel Wireless 8265 / 8275                                             | 21        | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 21        | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 20        | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 19        | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 19        | 1.27%   |
| Intel Wi-Fi 6 AX201                                                    | 19        | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 1.2%    |
| Intel Ethernet Connection (7) I219-V                                   | 18        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 17        | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 16        | 1.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 16        | 1.07%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 15        | 1%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 15        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 0.93%   |
| Intel Wireless 7265                                                    | 14        | 0.93%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 14        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 14        | 0.93%   |
| Intel Wireless 8260                                                    | 13        | 0.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12        | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 11        | 0.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 0.73%   |
| Intel Wireless 7260                                                    | 10        | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                          | 10        | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 9         | 0.6%    |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 9         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 8         | 0.53%   |
| Realtek 802.11ac NIC                                                   | 8         | 0.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 8         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 8         | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 8         | 0.53%   |
| Intel Ethernet Connection I217-LM                                      | 8         | 0.53%   |
| Intel Ethernet Connection (2) I219-V                                   | 8         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 320       | 46.31%  |
| Realtek Semiconductor           | 108       | 15.63%  |
| MediaTek                        | 66        | 9.55%   |
| Broadcom                        | 51        | 7.38%   |
| Qualcomm Atheros                | 46        | 6.66%   |
| TP-Link                         | 27        | 3.91%   |
| Microsoft                       | 21        | 3.04%   |
| Ralink Technology               | 14        | 2.03%   |
| Broadcom Limited                | 8         | 1.16%   |
| ASUSTek Computer                | 5         | 0.72%   |
| Ralink                          | 4         | 0.58%   |
| Qualcomm Atheros Communications | 4         | 0.58%   |
| Marvell Technology Group        | 3         | 0.43%   |
| Sierra Wireless                 | 2         | 0.29%   |
| NetGear                         | 2         | 0.29%   |
| D-Link System                   | 2         | 0.29%   |
| Belkin Components               | 2         | 0.29%   |
| Wacom                           | 1         | 0.14%   |
| Panasonic (Matsushita)          | 1         | 0.14%   |
| Linksys                         | 1         | 0.14%   |
| Fibocom                         | 1         | 0.14%   |
| D-Link                          | 1         | 0.14%   |
| AVM                             | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 77        | 11.1%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 28        | 4.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 24        | 3.46%   |
| Intel Wireless 8265 / 8275                                    | 21        | 3.03%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 21        | 3.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 20        | 2.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 19        | 2.74%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 19        | 2.74%   |
| Intel Wi-Fi 6 AX201                                           | 19        | 2.74%   |
| Intel Comet Lake PCH CNVi WiFi                                | 17        | 2.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 16        | 2.31%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 16        | 2.31%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 15        | 2.16%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 15        | 2.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 14        | 2.02%   |
| Intel Wireless 7265                                           | 14        | 2.02%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 14        | 2.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 14        | 2.02%   |
| Intel Wireless 8260                                           | 13        | 1.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 11        | 1.59%   |
| Intel Wireless 7260                                           | 10        | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                 | 10        | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 9         | 1.3%    |
| Intel Alder Lake-S PCH CNVi WiFi                              | 9         | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 8         | 1.15%   |
| Realtek 802.11ac NIC                                          | 8         | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 8         | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 7         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 7         | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 7         | 1.01%   |
| Microsoft Xbox 360 Wireless Adapter                           | 6         | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 6         | 0.86%   |
| TP-Link 802.11ac NIC                                          | 5         | 0.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 5         | 0.72%   |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 5         | 0.72%   |
| Intel Raptor Lake PCH CNVi WiFi                               | 5         | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 5         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 5         | 0.72%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 4         | 0.58%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 4         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 460       | 59.13%  |
| Intel                      | 198       | 25.45%  |
| Qualcomm Atheros           | 35        | 4.5%    |
| Broadcom                   | 18        | 2.31%   |
| ASIX Electronics           | 10        | 1.29%   |
| Xiaomi                     | 8         | 1.03%   |
| Samsung Electronics        | 6         | 0.77%   |
| Qualcomm                   | 6         | 0.77%   |
| Aquantia                   | 6         | 0.77%   |
| Nvidia                     | 5         | 0.64%   |
| Motorola PCS               | 4         | 0.51%   |
| Lenovo                     | 3         | 0.39%   |
| OPPO Electronics           | 2         | 0.26%   |
| Marvell Technology Group   | 2         | 0.26%   |
| Hewlett-Packard            | 2         | 0.26%   |
| Broadcom Limited           | 2         | 0.26%   |
| ZTE WCDMA Technologies MSM | 1         | 0.13%   |
| TP-Link                    | 1         | 0.13%   |
| T & A Mobile Phones        | 1         | 0.13%   |
| Mellanox Technologies      | 1         | 0.13%   |
| MediaTek                   | 1         | 0.13%   |
| JMicron Technology         | 1         | 0.13%   |
| ICS Advent                 | 1         | 0.13%   |
| Google                     | 1         | 0.13%   |
| DisplayLink                | 1         | 0.13%   |
| D-Link                     | 1         | 0.13%   |
| American Megatrends        | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 347       | 43.65%  |
| Realtek RTL8125 2.5GbE Controller                                               | 82        | 10.31%  |
| Intel I211 Gigabit Network Connection                                           | 42        | 5.28%   |
| Intel Ethernet Controller I225-V                                                | 42        | 5.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 18        | 2.26%   |
| Intel Ethernet Connection (7) I219-V                                            | 18        | 2.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 12        | 1.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 11        | 1.38%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 9         | 1.13%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 8         | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 8         | 1.01%   |
| Intel Ethernet Connection I217-LM                                               | 8         | 1.01%   |
| Intel Ethernet Connection (2) I219-V                                            | 8         | 1.01%   |
| Intel Ethernet Connection (2) I218-V                                            | 8         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                  | 7         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 7         | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                           | 7         | 0.88%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                               | 7         | 0.88%   |
| Intel Ethernet Connection I217-V                                                | 6         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 5         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 5         | 0.63%   |
| Intel 82579V Gigabit Network Connection                                         | 5         | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                               | 5         | 0.63%   |
| Realtek Killer E2600 GbE Controller                                             | 4         | 0.5%    |
| Motorola PCS moto g52                                                           | 4         | 0.5%    |
| Intel Ethernet Connection I218-LM                                               | 4         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                            | 4         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                                           | 4         | 0.5%    |
| Intel Ethernet Connection (17) I219-V                                           | 4         | 0.5%    |
| Intel Ethernet Connection (12) I219-V                                           | 4         | 0.5%    |
| Nvidia MCP79 Ethernet                                                           | 3         | 0.38%   |
| Intel I210 Gigabit Network Connection                                           | 3         | 0.38%   |
| Intel Ethernet Connection (4) I219-LM                                           | 3         | 0.38%   |
| Intel Ethernet Connection (2) I219-LM                                           | 3         | 0.38%   |
| Intel Ethernet Connection (14) I219-V                                           | 3         | 0.38%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 3         | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                                           | 2         | 0.25%   |
| Realtek Killer E3000 2.5GbE Controller                                          | 2         | 0.25%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                                | 2         | 0.25%   |
| Qualcomm Redmi 9T                                                               | 2         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 726       | 52.84%  |
| WiFi     | 639       | 46.51%  |
| Modem    | 5         | 0.36%   |
| Unknown  | 4         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 440       | 51.16%  |
| WiFi     | 420       | 48.84%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 441       | 53.58%  |
| 1     | 348       | 42.28%  |
| 3     | 23        | 2.79%   |
| 0     | 9         | 1.09%   |
| 6     | 1         | 0.12%   |
| 4     | 1         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 558       | 67.47%  |
| Yes  | 269       | 32.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 306       | 51.09%  |
| Realtek Semiconductor           | 55        | 9.18%   |
| Cambridge Silicon Radio         | 46        | 7.68%   |
| MediaTek                        | 28        | 4.67%   |
| Foxconn / Hon Hai               | 26        | 4.34%   |
| Qualcomm Atheros Communications | 23        | 3.84%   |
| Broadcom                        | 22        | 3.67%   |
| IMC Networks                    | 21        | 3.51%   |
| Apple                           | 18        | 3.01%   |
| Lite-On Technology              | 16        | 2.67%   |
| ASUSTek Computer                | 10        | 1.67%   |
| TP-Link                         | 7         | 1.17%   |
| Toshiba                         | 4         | 0.67%   |
| Marvell Semiconductor           | 3         | 0.5%    |
| Edimax Technology               | 3         | 0.5%    |
| Ralink                          | 2         | 0.33%   |
| Foxconn International           | 2         | 0.33%   |
| Actions                         | 2         | 0.33%   |
| Realtek                         | 1         | 0.17%   |
| Integrated System Solution      | 1         | 0.17%   |
| Dynex                           | 1         | 0.17%   |
| Dell                            | 1         | 0.17%   |
| Unknown                         | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                   | 75        | 12.5%   |
| Intel Bluetooth wireless interface                      | 70        | 11.67%  |
| Intel AX201 Bluetooth                                   | 48        | 8%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 46        | 7.67%   |
| Realtek Bluetooth Radio                                 | 43        | 7.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 29        | 4.83%   |
| MediaTek Wireless_Device                                | 27        | 4.5%    |
| Intel Bluetooth Device                                  | 27        | 4.5%    |
| Intel AX210 Bluetooth                                   | 27        | 4.5%    |
| Foxconn / Hon Hai Wireless_Device                       | 19        | 3.17%   |
| Intel Wireless-AC 3168 Bluetooth                        | 14        | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 12        | 2%      |
| IMC Networks Wireless_Device                            | 12        | 2%      |
| Apple Bluetooth Host Controller                         | 11        | 1.83%   |
| Realtek  Bluetooth 4.2 Adapter                          | 9         | 1.5%    |
| Qualcomm Atheros  Bluetooth Device                      | 8         | 1.33%   |
| TP-Link UB500 Adapter                                   | 7         | 1.17%   |
| IMC Networks Bluetooth Radio                            | 6         | 1%      |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 6         | 1%      |
| ASUS ASUS USB-BT500                                     | 6         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                   | 5         | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 5         | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver           | 5         | 0.83%   |
| Apple Bluetooth USB Host Controller                     | 4         | 0.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 3         | 0.5%    |
| Qualcomm Atheros Bluetooth USB Host Controller          | 3         | 0.5%    |
| Marvell Bluetooth and Wireless LAN Composite            | 3         | 0.5%    |
| Lite-On Bluetooth Radio                                 | 3         | 0.5%    |
| Lite-On Bluetooth Device                                | 3         | 0.5%    |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 3         | 0.5%    |
| Broadcom BCM20702A0                                     | 3         | 0.5%    |
| Toshiba BCM43142A0                                      | 2         | 0.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                 | 2         | 0.33%   |
| Ralink RT3290 Bluetooth                                 | 2         | 0.33%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 2         | 0.33%   |
| Lite-On Wireless_Device                                 | 2         | 0.33%   |
| Lite-On Atheros AR3012 Bluetooth                        | 2         | 0.33%   |
| IMC Networks Bluetooth Device                           | 2         | 0.33%   |
| Foxconn International BCM43142A0 Bluetooth module       | 2         | 0.33%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth           | 2         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 445       | 30.4%   |
| AMD                        | 439       | 29.99%  |
| Nvidia                     | 297       | 20.29%  |
| C-Media Electronics        | 39        | 2.66%   |
| Logitech                   | 32        | 2.19%   |
| Kingston Technology        | 15        | 1.02%   |
| Creative Labs              | 14        | 0.96%   |
| ASUSTek Computer           | 14        | 0.96%   |
| Razer USA                  | 13        | 0.89%   |
| Sony                       | 10        | 0.68%   |
| SteelSeries ApS            | 9         | 0.61%   |
| Creative Technology        | 8         | 0.55%   |
| Realtek Semiconductor      | 7         | 0.48%   |
| JMTek                      | 7         | 0.48%   |
| Texas Instruments          | 6         | 0.41%   |
| Plantronics                | 6         | 0.41%   |
| Corsair                    | 6         | 0.41%   |
| Samson Technologies        | 5         | 0.34%   |
| Micro Star International   | 5         | 0.34%   |
| Lenovo                     | 5         | 0.34%   |
| Focusrite-Novation         | 5         | 0.34%   |
| Hewlett-Packard            | 4         | 0.27%   |
| GN Netcom                  | 4         | 0.27%   |
| Blue Microphones           | 4         | 0.27%   |
| Audio-Technica             | 4         | 0.27%   |
| SAVITECH                   | 3         | 0.2%    |
| ROCCAT                     | 3         | 0.2%    |
| PreSonus Audio Electronics | 3         | 0.2%    |
| BEHRINGER International    | 3         | 0.2%    |
| Astro Gaming               | 3         | 0.2%    |
| TTGK Technology            | 2         | 0.14%   |
| Tenx Technology            | 2         | 0.14%   |
| ONN                        | 2         | 0.14%   |
| Native Instruments         | 2         | 0.14%   |
| Generalplus Technology     | 2         | 0.14%   |
| Cambridge Silicon Radio    | 2         | 0.14%   |
| Asahi Kasei Microsystems   | 2         | 0.14%   |
| Apple                      | 2         | 0.14%   |
| Unknown                    | 2         | 0.14%   |
| VIA Technologies           | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 163       | 9.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 115       | 6.37%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 90        | 4.98%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 69        | 3.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 49        | 2.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 48        | 2.66%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 41        | 2.27%   |
| Intel Sunrise Point-LP HD Audio                                            | 38        | 2.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 36        | 1.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 35        | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 33        | 1.83%   |
| Nvidia TU106 High Definition Audio Controller                              | 32        | 1.77%   |
| Nvidia GA106 High Definition Audio Controller                              | 29        | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 29        | 1.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 29        | 1.61%   |
| Nvidia GA104 High Definition Audio Controller                              | 28        | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25        | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 23        | 1.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 23        | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 23        | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                              | 22        | 1.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21        | 1.16%   |
| AMD Navi 10 HDMI Audio                                                     | 21        | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 20        | 1.11%   |
| Intel 8 Series HD Audio Controller                                         | 20        | 1.11%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 20        | 1.11%   |
| Nvidia GA102 High Definition Audio Controller                              | 19        | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 1.05%   |
| Intel 200 Series PCH HD Audio                                              | 18        | 1%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 17        | 0.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 17        | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 16        | 0.89%   |
| Nvidia TU104 HD Audio Controller                                           | 16        | 0.89%   |
| Nvidia Audio device                                                        | 16        | 0.89%   |
| Intel Alder Lake-S HD Audio Controller                                     | 16        | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 15        | 0.83%   |
| AMD FCH Azalia Controller                                                  | 14        | 0.78%   |
| ASUSTek Computer USB Audio                                                 | 13        | 0.72%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13        | 0.72%   |
| C-Media Electronics USB Audio Device                                       | 11        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 20.85%  |
| SK hynix            | 27        | 12.8%   |
| Micron Technology   | 27        | 12.8%   |
| Corsair             | 26        | 12.32%  |
| Kingston            | 21        | 9.95%   |
| G.Skill             | 20        | 9.48%   |
| Crucial             | 11        | 5.21%   |
| Unknown             | 8         | 3.79%   |
| Team                | 7         | 3.32%   |
| A-DATA Technology   | 5         | 2.37%   |
| Ramaxel Technology  | 3         | 1.42%   |
| Unknown (ABCD)      | 2         | 0.95%   |
| Unknown             | 2         | 0.95%   |
| Transcend           | 1         | 0.47%   |
| Nanya Technology    | 1         | 0.47%   |
| Hewlett-Packard     | 1         | 0.47%   |
| Gowe                | 1         | 0.47%   |
| GOODRAM             | 1         | 0.47%   |
| Elpida              | 1         | 0.47%   |
| Asgard              | 1         | 0.47%   |
| AMD                 | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 2.25%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 5         | 2.25%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 1.8%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 4         | 1.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.35%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s                 | 3         | 1.35%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                           | 2         | 0.9%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.9%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 0.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 0.9%    |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s            | 2         | 0.9%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s            | 2         | 0.9%    |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s             | 2         | 0.9%    |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.9%    |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s                | 2         | 0.9%    |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.9%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.9%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s                | 2         | 0.9%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 2         | 0.9%    |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s              | 2         | 0.9%    |
| G.Skill RAM F4-3600C18-8GTRS 8GB DIMM DDR4 3600MT/s                 | 2         | 0.9%    |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s                | 2         | 0.9%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                | 2         | 0.9%    |
| Corsair RAM CMY16GX3M2A1866C9 8GB DIMM DDR3 2400MT/s                | 2         | 0.9%    |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s               | 2         | 0.9%    |
| Corsair RAM CMSX32GX4M2A2400C16 16GB SODIMM DDR4 2400MT/s           | 2         | 0.9%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s              | 2         | 0.9%    |
| Unknown                                                             | 2         | 0.9%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.45%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                         | 1         | 0.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1         | 0.45%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                         | 1         | 0.45%   |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s              | 1         | 0.45%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s                 | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 114       | 63.33%  |
| DDR3    | 29        | 16.11%  |
| DDR5    | 20        | 11.11%  |
| LPDDR4  | 9         | 5%      |
| LPDDR5  | 3         | 1.67%   |
| Unknown | 2         | 1.11%   |
| SDRAM   | 1         | 0.56%   |
| LPDDR3  | 1         | 0.56%   |
| DDR2    | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 47.51%  |
| DIMM         | 81        | 44.75%  |
| Row Of Chips | 14        | 7.73%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 89        | 45.88%  |
| 16384 | 45        | 23.2%   |
| 4096  | 29        | 14.95%  |
| 32768 | 19        | 9.79%   |
| 2048  | 11        | 5.67%   |
| 1024  | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 47        | 24.48%  |
| 2667  | 22        | 11.46%  |
| 1600  | 20        | 10.42%  |
| 3600  | 15        | 7.81%   |
| 2400  | 14        | 7.29%   |
| 4800  | 8         | 4.17%   |
| 1333  | 7         | 3.65%   |
| 3733  | 6         | 3.13%   |
| 6000  | 5         | 2.6%    |
| 5600  | 5         | 2.6%    |
| 6400  | 4         | 2.08%   |
| 4267  | 4         | 2.08%   |
| 3866  | 3         | 1.56%   |
| 3800  | 3         | 1.56%   |
| 3266  | 3         | 1.56%   |
| 2133  | 3         | 1.56%   |
| 3534  | 2         | 1.04%   |
| 3466  | 2         | 1.04%   |
| 2933  | 2         | 1.04%   |
| 1066  | 2         | 1.04%   |
| 5800  | 1         | 0.52%   |
| 5200  | 1         | 0.52%   |
| 4266  | 1         | 0.52%   |
| 3933  | 1         | 0.52%   |
| 3533  | 1         | 0.52%   |
| 3400  | 1         | 0.52%   |
| 3334  | 1         | 0.52%   |
| 3333  | 1         | 0.52%   |
| 3100  | 1         | 0.52%   |
| 3066  | 1         | 0.52%   |
| 2800  | 1         | 0.52%   |
| 1867  | 1         | 0.52%   |
| 1334  | 1         | 0.52%   |
| 975   | 1         | 0.52%   |
| 800   | 1         | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 5         | 33.33%  |
| Canon               | 4         | 26.67%  |
| Hewlett-Packard     | 2         | 13.33%  |
| STMicroelectronics  | 1         | 6.67%   |
| Seiko Epson         | 1         | 6.67%   |
| Samsung Electronics | 1         | 6.67%   |
| Dell                | 1         | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 6.67%   |
| Seiko Epson XP-2100 Series                                | 1         | 6.67%   |
| Samsung Composite Device                                  | 1         | 6.67%   |
| HP DeskJet Plus 4100 series                               | 1         | 6.67%   |
| HP Color LaserJet CP1215                                  | 1         | 6.67%   |
| Dell 1130 Laser Printer                                   | 1         | 6.67%   |
| Canon TS700 series                                        | 1         | 6.67%   |
| Canon TR4500 series                                       | 1         | 6.67%   |
| Canon PIXMA MX370 Series                                  | 1         | 6.67%   |
| Canon G2000 series                                        | 1         | 6.67%   |
| Brother MFC-L2710DN series                                | 1         | 6.67%   |
| Brother MFC-J460DW                                        | 1         | 6.67%   |
| Brother HL-L2370DW series                                 | 1         | 6.67%   |
| Brother HL-L2320D series                                  | 1         | 6.67%   |
| Brother DCP-1510                                          | 1         | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| HP ScanJet 2400c              | 1         | 50%     |
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 76        | 18.63%  |
| IMC Networks                           | 40        | 9.8%    |
| Logitech                               | 35        | 8.58%   |
| Apple                                  | 25        | 6.13%   |
| Realtek Semiconductor                  | 24        | 5.88%   |
| Microdia                               | 23        | 5.64%   |
| Bison Electronics                      | 21        | 5.15%   |
| Sunplus Innovation Technology          | 19        | 4.66%   |
| Quanta                                 | 19        | 4.66%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.19%   |
| Syntek                                 | 12        | 2.94%   |
| Luxvisions Innotech Limited            | 10        | 2.45%   |
| Sonix Technology                       | 9         | 2.21%   |
| Lite-On Technology                     | 9         | 2.21%   |
| Microsoft                              | 8         | 1.96%   |
| Suyin                                  | 6         | 1.47%   |
| Samsung Electronics                    | 6         | 1.47%   |
| SunplusIT                              | 5         | 1.23%   |
| Silicon Motion                         | 3         | 0.74%   |
| Razer USA                              | 3         | 0.74%   |
| Generalplus Technology                 | 3         | 0.74%   |
| ARC International                      | 3         | 0.74%   |
| Acer                                   | 3         | 0.74%   |
| webcamvendor                           | 2         | 0.49%   |
| MacroSilicon                           | 2         | 0.49%   |
| Intel                                  | 2         | 0.49%   |
| HRY                                    | 2         | 0.49%   |
| Hewlett-Packard                        | 2         | 0.49%   |
| Elgato Systems                         | 2         | 0.49%   |
| Z-Star Microelectronics                | 1         | 0.25%   |
| YGTek                                  | 1         | 0.25%   |
| WCM_USB                                | 1         | 0.25%   |
| Tobii Technology AB                    | 1         | 0.25%   |
| Shine-optics                           | 1         | 0.25%   |
| Ruision                                | 1         | 0.25%   |
| Owon                                   | 1         | 0.25%   |
| Minton Optic Industry                  | 1         | 0.25%   |
| lihappe8                               | 1         | 0.25%   |
| Lenovo                                 | 1         | 0.25%   |
| KYE Systems (Mouse Systems)            | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 21        | 5.11%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 17        | 4.14%   |
| Realtek Integrated_Webcam_HD                        | 14        | 3.41%   |
| Chicony HD Webcam                                   | 11        | 2.68%   |
| IMC Networks Integrated Camera                      | 10        | 2.43%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 10        | 2.43%   |
| Syntek Integrated Camera                            | 9         | 2.19%   |
| Logitech C922 Pro Stream Webcam                     | 9         | 2.19%   |
| Logitech HD Pro Webcam C920                         | 8         | 1.95%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 1.7%    |
| Bison Integrated Camera                             | 7         | 1.7%    |
| Samsung Galaxy series, misc. (MTP mode)             | 6         | 1.46%   |
| Microdia USB 2.0 Camera                             | 6         | 1.46%   |
| Microdia Integrated_Webcam_HD                       | 6         | 1.46%   |
| Apple FaceTime HD Camera (Built-in)                 | 6         | 1.46%   |
| Sonix USB2.0 HD UVC WebCam                          | 5         | 1.22%   |
| Quanta HP TrueVision HD Camera                      | 5         | 1.22%   |
| Logitech Webcam C270                                | 5         | 1.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 1.22%   |
| Bison Lenovo Integrated Webcam                      | 5         | 1.22%   |
| Sonix USB2.0 FHD UVC WebCam                         | 4         | 0.97%   |
| Quanta HD User Facing                               | 4         | 0.97%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 0.97%   |
| Chicony USB 2.0 Camera                              | 4         | 0.97%   |
| Chicony HP TrueVision HD                            | 4         | 0.97%   |
| Bison HD Webcam                                     | 4         | 0.97%   |
| Apple FaceTime HD Camera                            | 4         | 0.97%   |
| Apple Built-in iSight                               | 4         | 0.97%   |
| Sunplus HD WebCam                                   | 3         | 0.73%   |
| Realtek USB Camera                                  | 3         | 0.73%   |
| Razer USA Gaming Webcam [Kiyo]                      | 3         | 0.73%   |
| Quanta VGA WebCam                                   | 3         | 0.73%   |
| Quanta HP Wide Vision HD Camera                     | 3         | 0.73%   |
| Microsoft LifeCam Cinema                            | 3         | 0.73%   |
| Microdia Integrated Camera                          | 3         | 0.73%   |
| Logitech StreamCam                                  | 3         | 0.73%   |
| Logitech C920 PRO HD Webcam                         | 3         | 0.73%   |
| Lite-On HP HD Webcam                                | 3         | 0.73%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 0.73%   |
| Chicony USB2.0 Camera                               | 3         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 18        | 33.33%  |
| Synaptics                          | 14        | 25.93%  |
| Shenzhen Goodix Technology         | 9         | 16.67%  |
| Elan Microelectronics              | 7         | 12.96%  |
| Realtek USB2.0 Finger Print Bridge | 3         | 5.56%   |
| Focal-systems.Corp                 | 2         | 3.7%    |
| LighTuning Technology              | 1         | 1.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 8         | 14.81%  |
| Shenzhen Goodix  FingerPrint Device                             | 5         | 9.26%   |
| Validity Sensors Synaptics WBDI                                 | 4         | 7.41%   |
| Shenzhen Goodix Fingerprint Reader                              | 4         | 7.41%   |
| Elan ELAN:Fingerprint                                           | 4         | 7.41%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 5.56%   |
| Elan ELAN:ARM-M4                                                | 3         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 3.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 2         | 3.7%    |
| Synaptics WBDI Device                                           | 2         | 3.7%    |
| Synaptics UWP WBDI                                              | 2         | 3.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 3.7%    |
| Focal-systems.Corp FT9201Fingerprint.Ì                       | 2         | 3.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.85%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.85%   |
| Synaptics WBDI                                                  | 1         | 1.85%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.85%   |
| Synaptics  WBDI                                                 | 1         | 1.85%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.85%   |
| Synaptics Fingerprint scanner                                   | 1         | 1.85%   |
| Synaptics Fingerprint reader [HP G6]                            | 1         | 1.85%   |
| LighTuning Fingerprint Sensor                                   | 1         | 1.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 46.15%  |
| Alcor Micro           | 5         | 38.46%  |
| Realtek Semiconductor | 1         | 7.69%   |
| Cherry                | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 38.46%  |
| Broadcom 5880                                                                | 3         | 23.08%  |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 7.69%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 626       | 75.06%  |
| 1     | 179       | 21.46%  |
| 2     | 25        | 3%      |
| 3     | 4         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 63        | 26.58%  |
| Graphics card            | 58        | 24.47%  |
| Fingerprint reader       | 53        | 22.36%  |
| Multimedia controller    | 38        | 16.03%  |
| Unassigned class         | 6         | 2.53%   |
| Sound                    | 4         | 1.69%   |
| Camera                   | 3         | 1.27%   |
| Bluetooth                | 3         | 1.27%   |
| Net/ethernet             | 2         | 0.84%   |
| Communication controller | 2         | 0.84%   |
| Card reader              | 2         | 0.84%   |
| Storage/nvme             | 1         | 0.42%   |
| Modem                    | 1         | 0.42%   |
| Chipcard                 | 1         | 0.42%   |

