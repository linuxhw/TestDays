ArcoLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ArcoLinux/Desktop/README.md) and [notebooks](/Dist/ArcoLinux/Notebook/README.md).

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

Total: 3228

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| BESSTAR Te... | UM700                       | Desktop     | [d635105967](https://linux-hardware.org/?probe=d635105967) | Sep 07, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [bedbf331b0](https://linux-hardware.org/?probe=bedbf331b0) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4fd02051b6](https://linux-hardware.org/?probe=4fd02051b6) | Sep 07, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [2385447c50](https://linux-hardware.org/?probe=2385447c50) | Sep 07, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [a4624a95da](https://linux-hardware.org/?probe=a4624a95da) | Sep 07, 2023 |
| Dell          | Latitude E5450              | Notebook    | [a705913b6e](https://linux-hardware.org/?probe=a705913b6e) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8c22ca23f2](https://linux-hardware.org/?probe=8c22ca23f2) | Sep 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | Notebook    | [f24dc99222](https://linux-hardware.org/?probe=f24dc99222) | Sep 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c890510220](https://linux-hardware.org/?probe=c890510220) | Sep 06, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [e47f10b579](https://linux-hardware.org/?probe=e47f10b579) | Sep 06, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [d1cf42c68c](https://linux-hardware.org/?probe=d1cf42c68c) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [4d1ca2eb79](https://linux-hardware.org/?probe=4d1ca2eb79) | Sep 06, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [995b1f100d](https://linux-hardware.org/?probe=995b1f100d) | Sep 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [a1c2c12b6f](https://linux-hardware.org/?probe=a1c2c12b6f) | Sep 06, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [99dd75f86a](https://linux-hardware.org/?probe=99dd75f86a) | Sep 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [cdabed6210](https://linux-hardware.org/?probe=cdabed6210) | Sep 05, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [054c5e3dc5](https://linux-hardware.org/?probe=054c5e3dc5) | Sep 05, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | Notebook    | [6ab6bec7be](https://linux-hardware.org/?probe=6ab6bec7be) | Sep 05, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [8bca1f8244](https://linux-hardware.org/?probe=8bca1f8244) | Sep 05, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e48cab52a7](https://linux-hardware.org/?probe=e48cab52a7) | Sep 05, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [dc22012520](https://linux-hardware.org/?probe=dc22012520) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | Desktop     | [77c07d0f70](https://linux-hardware.org/?probe=77c07d0f70) | Sep 05, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming-... | Desktop     | [a0aaf4be5d](https://linux-hardware.org/?probe=a0aaf4be5d) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e65692f205](https://linux-hardware.org/?probe=e65692f205) | Sep 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [106e2d1e98](https://linux-hardware.org/?probe=106e2d1e98) | Sep 04, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [5a9932b3b8](https://linux-hardware.org/?probe=5a9932b3b8) | Sep 04, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [def3f0d266](https://linux-hardware.org/?probe=def3f0d266) | Sep 04, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [a28ca9b2fb](https://linux-hardware.org/?probe=a28ca9b2fb) | Sep 04, 2023 |
| HP            | Pavilion g7                 | Notebook    | [a2a69279d6](https://linux-hardware.org/?probe=a2a69279d6) | Sep 04, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [8a8a236a44](https://linux-hardware.org/?probe=8a8a236a44) | Sep 04, 2023 |
| AZW           | MINI S                      | Desktop     | [331702f893](https://linux-hardware.org/?probe=331702f893) | Sep 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS24300    | Notebook    | [a28d4357d8](https://linux-hardware.org/?probe=a28d4357d8) | Sep 03, 2023 |
| HP            | Folio 13                    | Notebook    | [d5844cc9e8](https://linux-hardware.org/?probe=d5844cc9e8) | Sep 03, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | Notebook    | [b9de538f7e](https://linux-hardware.org/?probe=b9de538f7e) | Sep 03, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [884eaad43c](https://linux-hardware.org/?probe=884eaad43c) | Sep 03, 2023 |
| IP3 Tech      | rev1.0                      | All in one  | [d2c6f51ff8](https://linux-hardware.org/?probe=d2c6f51ff8) | Sep 03, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [d15e4d0045](https://linux-hardware.org/?probe=d15e4d0045) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e05acf231c](https://linux-hardware.org/?probe=e05acf231c) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [78c449e398](https://linux-hardware.org/?probe=78c449e398) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [7f25cc995d](https://linux-hardware.org/?probe=7f25cc995d) | Sep 03, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [47ef8122dc](https://linux-hardware.org/?probe=47ef8122dc) | Sep 03, 2023 |
| Dell          | G3 3779                     | Notebook    | [56fa43078f](https://linux-hardware.org/?probe=56fa43078f) | Sep 02, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [9f8e38af3e](https://linux-hardware.org/?probe=9f8e38af3e) | Sep 02, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [59014a9e20](https://linux-hardware.org/?probe=59014a9e20) | Sep 02, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [19e076e3e1](https://linux-hardware.org/?probe=19e076e3e1) | Sep 01, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [4b8aead223](https://linux-hardware.org/?probe=4b8aead223) | Sep 01, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [773143cf61](https://linux-hardware.org/?probe=773143cf61) | Sep 01, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [b52faa8776](https://linux-hardware.org/?probe=b52faa8776) | Sep 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5f50ef24fe](https://linux-hardware.org/?probe=5f50ef24fe) | Sep 01, 2023 |
| Intel         | NUC7i3BNB J22859-310        | Mini pc     | [cd552285b0](https://linux-hardware.org/?probe=cd552285b0) | Sep 01, 2023 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [ad4df3d293](https://linux-hardware.org/?probe=ad4df3d293) | Aug 31, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [cef6754cd9](https://linux-hardware.org/?probe=cef6754cd9) | Aug 31, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [13ec5c53cf](https://linux-hardware.org/?probe=13ec5c53cf) | Aug 31, 2023 |
| Lenovo        | Legion Y920-17IKB Laptop... | Notebook    | [5976d2d9e9](https://linux-hardware.org/?probe=5976d2d9e9) | Aug 31, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a829cc0dce](https://linux-hardware.org/?probe=a829cc0dce) | Aug 31, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [c75a044974](https://linux-hardware.org/?probe=c75a044974) | Aug 30, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [ebcd50f639](https://linux-hardware.org/?probe=ebcd50f639) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [885c22f859](https://linux-hardware.org/?probe=885c22f859) | Aug 30, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a31df2b8fe](https://linux-hardware.org/?probe=a31df2b8fe) | Aug 30, 2023 |
| HP            | 802F                        | Desktop     | [7d065f8fd1](https://linux-hardware.org/?probe=7d065f8fd1) | Aug 30, 2023 |
| Lenovo        | ThinkPad A475 20KMS0K20S    | Notebook    | [2685098cd9](https://linux-hardware.org/?probe=2685098cd9) | Aug 29, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [ca4dd5a11e](https://linux-hardware.org/?probe=ca4dd5a11e) | Aug 29, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [c392d83e8e](https://linux-hardware.org/?probe=c392d83e8e) | Aug 29, 2023 |
| Dell          | 0V8WGR A01                  | Desktop     | [9e5ed52b45](https://linux-hardware.org/?probe=9e5ed52b45) | Aug 29, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5a20b8cd20](https://linux-hardware.org/?probe=5a20b8cd20) | Aug 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [708fc220a9](https://linux-hardware.org/?probe=708fc220a9) | Aug 29, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [0789880eae](https://linux-hardware.org/?probe=0789880eae) | Aug 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [265430a40c](https://linux-hardware.org/?probe=265430a40c) | Aug 29, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [6bd291c8b0](https://linux-hardware.org/?probe=6bd291c8b0) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0f3d530e12](https://linux-hardware.org/?probe=0f3d530e12) | Aug 29, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [e27639a1f9](https://linux-hardware.org/?probe=e27639a1f9) | Aug 29, 2023 |
| HP            | 8061                        | Desktop     | [31a0fa50a3](https://linux-hardware.org/?probe=31a0fa50a3) | Aug 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | Notebook    | [0ccccd5c9d](https://linux-hardware.org/?probe=0ccccd5c9d) | Aug 28, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [5df3abe62e](https://linux-hardware.org/?probe=5df3abe62e) | Aug 28, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [3c5aa8e05a](https://linux-hardware.org/?probe=3c5aa8e05a) | Aug 28, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [0cda85fdd1](https://linux-hardware.org/?probe=0cda85fdd1) | Aug 28, 2023 |
| Acer          | Aspire M3470                | Desktop     | [60d18d6d6e](https://linux-hardware.org/?probe=60d18d6d6e) | Aug 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [269a4ac17d](https://linux-hardware.org/?probe=269a4ac17d) | Aug 28, 2023 |
| Lenovo        | ThinkPad X220 4291C84       | Notebook    | [623b0f76d1](https://linux-hardware.org/?probe=623b0f76d1) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8b82375189](https://linux-hardware.org/?probe=8b82375189) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [90474aa183](https://linux-hardware.org/?probe=90474aa183) | Aug 27, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [1112486ef3](https://linux-hardware.org/?probe=1112486ef3) | Aug 27, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f1422f4092](https://linux-hardware.org/?probe=f1422f4092) | Aug 27, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [99e5a7a753](https://linux-hardware.org/?probe=99e5a7a753) | Aug 27, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [8c616e6421](https://linux-hardware.org/?probe=8c616e6421) | Aug 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [8ee512db27](https://linux-hardware.org/?probe=8ee512db27) | Aug 27, 2023 |
| Acer          | Aspire M3470                | Desktop     | [7e6d230bf5](https://linux-hardware.org/?probe=7e6d230bf5) | Aug 27, 2023 |
| ASRock        | X570 Phantom Gaming 4S      | Desktop     | [1be18fe99f](https://linux-hardware.org/?probe=1be18fe99f) | Aug 27, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | Desktop     | [512429f429](https://linux-hardware.org/?probe=512429f429) | Aug 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [bf1d0a62ed](https://linux-hardware.org/?probe=bf1d0a62ed) | Aug 26, 2023 |
| MSI           | GL73 8RC                    | Notebook    | [5ca33a6111](https://linux-hardware.org/?probe=5ca33a6111) | Aug 26, 2023 |
| Acer          | Predator G9-793             | Notebook    | [531f857477](https://linux-hardware.org/?probe=531f857477) | Aug 26, 2023 |
| HP            | 802F                        | Desktop     | [6759058353](https://linux-hardware.org/?probe=6759058353) | Aug 25, 2023 |
| Dell          | 0658N7 A01                  | Server      | [0b0ac21b18](https://linux-hardware.org/?probe=0b0ac21b18) | Aug 25, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [d28f06dcc5](https://linux-hardware.org/?probe=d28f06dcc5) | Aug 25, 2023 |
| System76      | Gazelle                     | Notebook    | [ee67365e0c](https://linux-hardware.org/?probe=ee67365e0c) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [aa3157f519](https://linux-hardware.org/?probe=aa3157f519) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [8d3738c790](https://linux-hardware.org/?probe=8d3738c790) | Aug 24, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [7fdfaacf03](https://linux-hardware.org/?probe=7fdfaacf03) | Aug 24, 2023 |
| AZW           | SER                         | Mini pc     | [309bc27af7](https://linux-hardware.org/?probe=309bc27af7) | Aug 24, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [3898bac5d4](https://linux-hardware.org/?probe=3898bac5d4) | Aug 24, 2023 |
| Intel         | NUC7i7DNB J83500-204        | Mini pc     | [de9c4fce3c](https://linux-hardware.org/?probe=de9c4fce3c) | Aug 24, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [a3de2e9813](https://linux-hardware.org/?probe=a3de2e9813) | Aug 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [68d3bc88e4](https://linux-hardware.org/?probe=68d3bc88e4) | Aug 23, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6fa7d1e35d](https://linux-hardware.org/?probe=6fa7d1e35d) | Aug 23, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [799390e547](https://linux-hardware.org/?probe=799390e547) | Aug 23, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [81b8c378f7](https://linux-hardware.org/?probe=81b8c378f7) | Aug 23, 2023 |
| Dell          | G3 3579                     | Notebook    | [49b4227da5](https://linux-hardware.org/?probe=49b4227da5) | Aug 22, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [353c7bca5a](https://linux-hardware.org/?probe=353c7bca5a) | Aug 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [39fa23e4b7](https://linux-hardware.org/?probe=39fa23e4b7) | Aug 22, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b4133748fc](https://linux-hardware.org/?probe=b4133748fc) | Aug 21, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e06223da9](https://linux-hardware.org/?probe=2e06223da9) | Aug 21, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9d07a3d5c7](https://linux-hardware.org/?probe=9d07a3d5c7) | Aug 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2a468a2183](https://linux-hardware.org/?probe=2a468a2183) | Aug 21, 2023 |
| ASUSTek       | K53E                        | Notebook    | [9cce7a150e](https://linux-hardware.org/?probe=9cce7a150e) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [e6dceda4bc](https://linux-hardware.org/?probe=e6dceda4bc) | Aug 21, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [8be90f267b](https://linux-hardware.org/?probe=8be90f267b) | Aug 20, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [048ca1ce02](https://linux-hardware.org/?probe=048ca1ce02) | Aug 20, 2023 |
| Dell          | System XPS L502X            | Notebook    | [e85150614a](https://linux-hardware.org/?probe=e85150614a) | Aug 20, 2023 |
| Acer          | TravelMate P645-S           | Notebook    | [658d88e2a5](https://linux-hardware.org/?probe=658d88e2a5) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [dedf0b23a3](https://linux-hardware.org/?probe=dedf0b23a3) | Aug 19, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | Notebook    | [498c86055c](https://linux-hardware.org/?probe=498c86055c) | Aug 19, 2023 |
| Dell          | G15 5511                    | Notebook    | [8032cca2b5](https://linux-hardware.org/?probe=8032cca2b5) | Aug 19, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d7805c8232](https://linux-hardware.org/?probe=d7805c8232) | Aug 19, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | Notebook    | [7a389ac976](https://linux-hardware.org/?probe=7a389ac976) | Aug 19, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [9f5242decc](https://linux-hardware.org/?probe=9f5242decc) | Aug 19, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d8de59f346](https://linux-hardware.org/?probe=d8de59f346) | Aug 19, 2023 |
| Dell          | XPS L521X                   | Notebook    | [fdd6adb89a](https://linux-hardware.org/?probe=fdd6adb89a) | Aug 18, 2023 |
| Toshiba       | Satellite L55-B             | Notebook    | [4b2bcc2231](https://linux-hardware.org/?probe=4b2bcc2231) | Aug 18, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [3c8853c045](https://linux-hardware.org/?probe=3c8853c045) | Aug 18, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [beddeba8b6](https://linux-hardware.org/?probe=beddeba8b6) | Aug 18, 2023 |
| MSI           | Indio                       | Desktop     | [162ed509d4](https://linux-hardware.org/?probe=162ed509d4) | Aug 18, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [bee6142eee](https://linux-hardware.org/?probe=bee6142eee) | Aug 17, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [b72192373b](https://linux-hardware.org/?probe=b72192373b) | Aug 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [567acf505b](https://linux-hardware.org/?probe=567acf505b) | Aug 17, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [8478931432](https://linux-hardware.org/?probe=8478931432) | Aug 17, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [3f0a5a32cf](https://linux-hardware.org/?probe=3f0a5a32cf) | Aug 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [6a2e05ff64](https://linux-hardware.org/?probe=6a2e05ff64) | Aug 17, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0ba07cce6b](https://linux-hardware.org/?probe=0ba07cce6b) | Aug 17, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [06aebc0204](https://linux-hardware.org/?probe=06aebc0204) | Aug 17, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [79d8f79efe](https://linux-hardware.org/?probe=79d8f79efe) | Aug 17, 2023 |
| ASUSTek       | GL552JX                     | Notebook    | [9594a231bd](https://linux-hardware.org/?probe=9594a231bd) | Aug 16, 2023 |
| Dell          | Inspiron 7370               | Notebook    | [2676762739](https://linux-hardware.org/?probe=2676762739) | Aug 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [bf65b5fe16](https://linux-hardware.org/?probe=bf65b5fe16) | Aug 16, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [122b800eae](https://linux-hardware.org/?probe=122b800eae) | Aug 16, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [b288a65e53](https://linux-hardware.org/?probe=b288a65e53) | Aug 16, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [948ab98a6f](https://linux-hardware.org/?probe=948ab98a6f) | Aug 15, 2023 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [fc92556049](https://linux-hardware.org/?probe=fc92556049) | Aug 15, 2023 |
| Lenovo        | ThinkPad T490 20N2004EGE    | Notebook    | [11552492c0](https://linux-hardware.org/?probe=11552492c0) | Aug 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [2ac8f6838a](https://linux-hardware.org/?probe=2ac8f6838a) | Aug 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b53cba2654](https://linux-hardware.org/?probe=b53cba2654) | Aug 15, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [64a1b8ad5d](https://linux-hardware.org/?probe=64a1b8ad5d) | Aug 14, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [65f7a020fe](https://linux-hardware.org/?probe=65f7a020fe) | Aug 14, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [fe4612b027](https://linux-hardware.org/?probe=fe4612b027) | Aug 14, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | Desktop     | [5a3c9080d8](https://linux-hardware.org/?probe=5a3c9080d8) | Aug 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9d7d216fc0](https://linux-hardware.org/?probe=9d7d216fc0) | Aug 14, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [da00873a9d](https://linux-hardware.org/?probe=da00873a9d) | Aug 14, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [e6da28e1fb](https://linux-hardware.org/?probe=e6da28e1fb) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [a65f824e07](https://linux-hardware.org/?probe=a65f824e07) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [2da924ecb2](https://linux-hardware.org/?probe=2da924ecb2) | Aug 13, 2023 |
| Notebook      | N141CU                      | Notebook    | [06c2f33fb5](https://linux-hardware.org/?probe=06c2f33fb5) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [c28cbbd2a1](https://linux-hardware.org/?probe=c28cbbd2a1) | Aug 13, 2023 |
| Monster       | ABRA A5 V17.2               | Notebook    | [0049202ca7](https://linux-hardware.org/?probe=0049202ca7) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [6d1e3a24e8](https://linux-hardware.org/?probe=6d1e3a24e8) | Aug 13, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [2461c78ff0](https://linux-hardware.org/?probe=2461c78ff0) | Aug 13, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [3d99363ed5](https://linux-hardware.org/?probe=3d99363ed5) | Aug 13, 2023 |
| HP            | Folio 13                    | Notebook    | [62fcebde8c](https://linux-hardware.org/?probe=62fcebde8c) | Aug 13, 2023 |
| Lenovo        | ThinkPad P53s 20N6S00B00    | Notebook    | [3170e56ed1](https://linux-hardware.org/?probe=3170e56ed1) | Aug 13, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [8414f16824](https://linux-hardware.org/?probe=8414f16824) | Aug 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [b6b99bf7bd](https://linux-hardware.org/?probe=b6b99bf7bd) | Aug 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [3ea3856297](https://linux-hardware.org/?probe=3ea3856297) | Aug 12, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [e65db8d147](https://linux-hardware.org/?probe=e65db8d147) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [72899a615b](https://linux-hardware.org/?probe=72899a615b) | Aug 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d387c8fec5](https://linux-hardware.org/?probe=d387c8fec5) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [c90f282238](https://linux-hardware.org/?probe=c90f282238) | Aug 11, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [6f323e0954](https://linux-hardware.org/?probe=6f323e0954) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9f30f8dd0](https://linux-hardware.org/?probe=a9f30f8dd0) | Aug 11, 2023 |
| HP            | 158A                        | Desktop     | [96e7fa3b8f](https://linux-hardware.org/?probe=96e7fa3b8f) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY            | Notebook    | [eacd0cc54d](https://linux-hardware.org/?probe=eacd0cc54d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [c083cb5f2f](https://linux-hardware.org/?probe=c083cb5f2f) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [980f6773f8](https://linux-hardware.org/?probe=980f6773f8) | Aug 10, 2023 |
| Lenovo        | ThinkPad P53s 20N6S00B00    | Notebook    | [c76e31ff8e](https://linux-hardware.org/?probe=c76e31ff8e) | Aug 10, 2023 |
| HP            | Folio 13                    | Notebook    | [67121fc711](https://linux-hardware.org/?probe=67121fc711) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [025afcb20d](https://linux-hardware.org/?probe=025afcb20d) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [6f422f386f](https://linux-hardware.org/?probe=6f422f386f) | Aug 10, 2023 |
| HP            | 829A                        | Mini pc     | [ae08c868cf](https://linux-hardware.org/?probe=ae08c868cf) | Aug 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e703bb179f](https://linux-hardware.org/?probe=e703bb179f) | Aug 10, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [60cfdb5283](https://linux-hardware.org/?probe=60cfdb5283) | Aug 10, 2023 |
| HP            | Folio 13                    | Notebook    | [889aae1772](https://linux-hardware.org/?probe=889aae1772) | Aug 10, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [817c5f9f93](https://linux-hardware.org/?probe=817c5f9f93) | Aug 09, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [12e0dbd72c](https://linux-hardware.org/?probe=12e0dbd72c) | Aug 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [0cf2ab49c0](https://linux-hardware.org/?probe=0cf2ab49c0) | Aug 09, 2023 |
| HP            | Compaq 15                   | Notebook    | [387a3b8af2](https://linux-hardware.org/?probe=387a3b8af2) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [e22cd6fdac](https://linux-hardware.org/?probe=e22cd6fdac) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | Desktop     | [2242417727](https://linux-hardware.org/?probe=2242417727) | Aug 09, 2023 |
| Lenovo        | ThinkPad X240 20AL00C6UK    | Notebook    | [d33c586eab](https://linux-hardware.org/?probe=d33c586eab) | Aug 09, 2023 |
| Dell          | 073Y7Y A00                  | Desktop     | [cbf4153713](https://linux-hardware.org/?probe=cbf4153713) | Aug 09, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [ccb4eadbca](https://linux-hardware.org/?probe=ccb4eadbca) | Aug 08, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [d79ab70370](https://linux-hardware.org/?probe=d79ab70370) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5babb790d3](https://linux-hardware.org/?probe=5babb790d3) | Aug 08, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [ff4ead4bd3](https://linux-hardware.org/?probe=ff4ead4bd3) | Aug 08, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [e5a8c891d0](https://linux-hardware.org/?probe=e5a8c891d0) | Aug 08, 2023 |
| Toshiba       | Satellite C50-A510          | Notebook    | [335af4e25a](https://linux-hardware.org/?probe=335af4e25a) | Aug 08, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [3ff7f02af7](https://linux-hardware.org/?probe=3ff7f02af7) | Aug 08, 2023 |
| Insyde        | BayTrail                    | Notebook    | [df18553ec6](https://linux-hardware.org/?probe=df18553ec6) | Aug 07, 2023 |
| HP            | 8876 11                     | Desktop     | [059d4c2db2](https://linux-hardware.org/?probe=059d4c2db2) | Aug 07, 2023 |
| HP            | 158A                        | Desktop     | [657812fbbf](https://linux-hardware.org/?probe=657812fbbf) | Aug 07, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [51c3d4511a](https://linux-hardware.org/?probe=51c3d4511a) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [5e64d2b59e](https://linux-hardware.org/?probe=5e64d2b59e) | Aug 06, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [458a26f70c](https://linux-hardware.org/?probe=458a26f70c) | Aug 06, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [5a254fe1d6](https://linux-hardware.org/?probe=5a254fe1d6) | Aug 06, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [f670b492a9](https://linux-hardware.org/?probe=f670b492a9) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [35bb5f3e65](https://linux-hardware.org/?probe=35bb5f3e65) | Aug 06, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [bd989967e7](https://linux-hardware.org/?probe=bd989967e7) | Aug 06, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [597461a5ac](https://linux-hardware.org/?probe=597461a5ac) | Aug 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48cf16e31d](https://linux-hardware.org/?probe=48cf16e31d) | Aug 06, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [e815f65a97](https://linux-hardware.org/?probe=e815f65a97) | Aug 05, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [dfc4d46266](https://linux-hardware.org/?probe=dfc4d46266) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb92759c2a](https://linux-hardware.org/?probe=eb92759c2a) | Aug 05, 2023 |
| Dell          | G15 5520                    | Notebook    | [baca0d14f5](https://linux-hardware.org/?probe=baca0d14f5) | Aug 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fafbd706de](https://linux-hardware.org/?probe=fafbd706de) | Aug 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [dd1767aec1](https://linux-hardware.org/?probe=dd1767aec1) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [af4f153b11](https://linux-hardware.org/?probe=af4f153b11) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [c163ae3710](https://linux-hardware.org/?probe=c163ae3710) | Aug 04, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [656e917b79](https://linux-hardware.org/?probe=656e917b79) | Aug 04, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [363bee1696](https://linux-hardware.org/?probe=363bee1696) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [31d1c3bfbc](https://linux-hardware.org/?probe=31d1c3bfbc) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [44e0cbb52e](https://linux-hardware.org/?probe=44e0cbb52e) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7f601fe313](https://linux-hardware.org/?probe=7f601fe313) | Aug 03, 2023 |
| HP            | 21D0                        | Desktop     | [099fea9193](https://linux-hardware.org/?probe=099fea9193) | Aug 02, 2023 |
| HP            | Pavilion g7                 | Notebook    | [882d2d9a16](https://linux-hardware.org/?probe=882d2d9a16) | Aug 02, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [75c36d43c3](https://linux-hardware.org/?probe=75c36d43c3) | Aug 02, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [e391326d89](https://linux-hardware.org/?probe=e391326d89) | Aug 02, 2023 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [251b811e9b](https://linux-hardware.org/?probe=251b811e9b) | Aug 02, 2023 |
| HP            | Notebook                    | Notebook    | [258f6a82ad](https://linux-hardware.org/?probe=258f6a82ad) | Aug 02, 2023 |
| MSI           | H170M PRO-DH                | Desktop     | [e0b553c4dd](https://linux-hardware.org/?probe=e0b553c4dd) | Aug 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [eb2554dce9](https://linux-hardware.org/?probe=eb2554dce9) | Aug 02, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [451bfcf27d](https://linux-hardware.org/?probe=451bfcf27d) | Aug 02, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [79c3c3612b](https://linux-hardware.org/?probe=79c3c3612b) | Aug 02, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [19aa30337f](https://linux-hardware.org/?probe=19aa30337f) | Aug 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [589f0a8599](https://linux-hardware.org/?probe=589f0a8599) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8da287a76b](https://linux-hardware.org/?probe=8da287a76b) | Aug 01, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [26cca552dd](https://linux-hardware.org/?probe=26cca552dd) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [93d193bdbc](https://linux-hardware.org/?probe=93d193bdbc) | Aug 01, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [8aaca0803f](https://linux-hardware.org/?probe=8aaca0803f) | Jul 31, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [18924cfab7](https://linux-hardware.org/?probe=18924cfab7) | Jul 31, 2023 |
| Samsung       | 535U3C                      | Notebook    | [8d0ebb957a](https://linux-hardware.org/?probe=8d0ebb957a) | Jul 31, 2023 |
| Samsung       | 535U3C                      | Notebook    | [030fc15fac](https://linux-hardware.org/?probe=030fc15fac) | Jul 31, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [93c8724c91](https://linux-hardware.org/?probe=93c8724c91) | Jul 31, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8559f3826b](https://linux-hardware.org/?probe=8559f3826b) | Jul 31, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [04b1a06dbd](https://linux-hardware.org/?probe=04b1a06dbd) | Jul 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e66bd4564e](https://linux-hardware.org/?probe=e66bd4564e) | Jul 30, 2023 |
| Apple         | MacBookAir1,1               | Notebook    | [ac140cf8c4](https://linux-hardware.org/?probe=ac140cf8c4) | Jul 30, 2023 |
| Unknown       | HX90                        | Desktop     | [2eba30b5be](https://linux-hardware.org/?probe=2eba30b5be) | Jul 30, 2023 |
| HP            | Folio 13                    | Notebook    | [baaa648a4b](https://linux-hardware.org/?probe=baaa648a4b) | Jul 29, 2023 |
| Dell          | Latitude E6230              | Notebook    | [462496c6db](https://linux-hardware.org/?probe=462496c6db) | Jul 29, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [60bf32a368](https://linux-hardware.org/?probe=60bf32a368) | Jul 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [fb2ba2d3eb](https://linux-hardware.org/?probe=fb2ba2d3eb) | Jul 29, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [1b9bb7c266](https://linux-hardware.org/?probe=1b9bb7c266) | Jul 29, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [51d9b57967](https://linux-hardware.org/?probe=51d9b57967) | Jul 29, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [081608e70c](https://linux-hardware.org/?probe=081608e70c) | Jul 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [e8368bcae8](https://linux-hardware.org/?probe=e8368bcae8) | Jul 28, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [32fcc0f81f](https://linux-hardware.org/?probe=32fcc0f81f) | Jul 28, 2023 |
| Intel         | HM570                       | Desktop     | [c969a88e87](https://linux-hardware.org/?probe=c969a88e87) | Jul 28, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [3c0f7ba188](https://linux-hardware.org/?probe=3c0f7ba188) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [d32fa8840b](https://linux-hardware.org/?probe=d32fa8840b) | Jul 27, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [1a6962dc65](https://linux-hardware.org/?probe=1a6962dc65) | Jul 27, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0b04075e09](https://linux-hardware.org/?probe=0b04075e09) | Jul 27, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [20221ed288](https://linux-hardware.org/?probe=20221ed288) | Jul 27, 2023 |
| Lenovo        | 3743 SDK0J40700 WIN 3258... | Desktop     | [546f011b1a](https://linux-hardware.org/?probe=546f011b1a) | Jul 27, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [ba305b3271](https://linux-hardware.org/?probe=ba305b3271) | Jul 26, 2023 |
| HP            | Folio 13                    | Notebook    | [a3269c0930](https://linux-hardware.org/?probe=a3269c0930) | Jul 26, 2023 |
| Dell          | G3 3579                     | Notebook    | [b6b50ffa46](https://linux-hardware.org/?probe=b6b50ffa46) | Jul 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [aa34907e3a](https://linux-hardware.org/?probe=aa34907e3a) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [24c092f0b0](https://linux-hardware.org/?probe=24c092f0b0) | Jul 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [a5933aa510](https://linux-hardware.org/?probe=a5933aa510) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [74adf4cb3d](https://linux-hardware.org/?probe=74adf4cb3d) | Jul 26, 2023 |
| Lenovo        | Legion R9000X 2021 82HN     | Notebook    | [0079a4e7a0](https://linux-hardware.org/?probe=0079a4e7a0) | Jul 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [7cd1c7cdf2](https://linux-hardware.org/?probe=7cd1c7cdf2) | Jul 25, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fcb6317c1b](https://linux-hardware.org/?probe=fcb6317c1b) | Jul 25, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [7da659326d](https://linux-hardware.org/?probe=7da659326d) | Jul 24, 2023 |
| Dell          | Latitude E6230              | Notebook    | [6f832e0bb3](https://linux-hardware.org/?probe=6f832e0bb3) | Jul 24, 2023 |
| SiS Techno... | 760                         | Desktop     | [1c5bd52522](https://linux-hardware.org/?probe=1c5bd52522) | Jul 24, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [176adf0a2b](https://linux-hardware.org/?probe=176adf0a2b) | Jul 24, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4a262a2a2d](https://linux-hardware.org/?probe=4a262a2a2d) | Jul 24, 2023 |
| ASUSTek       | PN61                        | Mini pc     | [78418a9a7f](https://linux-hardware.org/?probe=78418a9a7f) | Jul 24, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [df1a812c11](https://linux-hardware.org/?probe=df1a812c11) | Jul 24, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [bd66a96c97](https://linux-hardware.org/?probe=bd66a96c97) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [579d5d5771](https://linux-hardware.org/?probe=579d5d5771) | Jul 24, 2023 |
| Dell          | Latitude 5410               | Notebook    | [29261ea2bb](https://linux-hardware.org/?probe=29261ea2bb) | Jul 24, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [f9bd193456](https://linux-hardware.org/?probe=f9bd193456) | Jul 23, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ae4343c245](https://linux-hardware.org/?probe=ae4343c245) | Jul 23, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [b844b9a353](https://linux-hardware.org/?probe=b844b9a353) | Jul 23, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f2f1f87d0c](https://linux-hardware.org/?probe=f2f1f87d0c) | Jul 23, 2023 |
| Dell          | Latitude 5480               | Notebook    | [0595e16f65](https://linux-hardware.org/?probe=0595e16f65) | Jul 23, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [f291f72d81](https://linux-hardware.org/?probe=f291f72d81) | Jul 23, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [c4890b8f34](https://linux-hardware.org/?probe=c4890b8f34) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [23d73ededd](https://linux-hardware.org/?probe=23d73ededd) | Jul 23, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [af255054c3](https://linux-hardware.org/?probe=af255054c3) | Jul 22, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [afc4d3c307](https://linux-hardware.org/?probe=afc4d3c307) | Jul 22, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [be58f943df](https://linux-hardware.org/?probe=be58f943df) | Jul 22, 2023 |
| HP            | 21D0                        | Desktop     | [774375de1f](https://linux-hardware.org/?probe=774375de1f) | Jul 22, 2023 |
| Dell          | Latitude E7440              | Notebook    | [ffa2aad2b5](https://linux-hardware.org/?probe=ffa2aad2b5) | Jul 21, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [f3435d221b](https://linux-hardware.org/?probe=f3435d221b) | Jul 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [516853cca9](https://linux-hardware.org/?probe=516853cca9) | Jul 21, 2023 |
| Biostar       | A320MH                      | Desktop     | [5fd84925fd](https://linux-hardware.org/?probe=5fd84925fd) | Jul 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [874f8dff98](https://linux-hardware.org/?probe=874f8dff98) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d1dee26c33](https://linux-hardware.org/?probe=d1dee26c33) | Jul 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [dc0a2fb7ef](https://linux-hardware.org/?probe=dc0a2fb7ef) | Jul 20, 2023 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [f7218e4043](https://linux-hardware.org/?probe=f7218e4043) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [13a6f964eb](https://linux-hardware.org/?probe=13a6f964eb) | Jul 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c8fa0f7219](https://linux-hardware.org/?probe=c8fa0f7219) | Jul 19, 2023 |
| Dell          | Latitude 5580               | Notebook    | [6efcf73621](https://linux-hardware.org/?probe=6efcf73621) | Jul 19, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d79851836e](https://linux-hardware.org/?probe=d79851836e) | Jul 19, 2023 |
| HP            | G62                         | Notebook    | [c36d4392da](https://linux-hardware.org/?probe=c36d4392da) | Jul 19, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [56e1ff54a3](https://linux-hardware.org/?probe=56e1ff54a3) | Jul 19, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | Notebook    | [dc091872ec](https://linux-hardware.org/?probe=dc091872ec) | Jul 18, 2023 |
| Acer          | One S1003                   | Tablet      | [380ae70fb2](https://linux-hardware.org/?probe=380ae70fb2) | Jul 18, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [ef3c6c941e](https://linux-hardware.org/?probe=ef3c6c941e) | Jul 18, 2023 |
| Google        | Kip                         | Notebook    | [00dd9a1c67](https://linux-hardware.org/?probe=00dd9a1c67) | Jul 18, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [5797e88a56](https://linux-hardware.org/?probe=5797e88a56) | Jul 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [322db1cde6](https://linux-hardware.org/?probe=322db1cde6) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [f0ecaa209e](https://linux-hardware.org/?probe=f0ecaa209e) | Jul 18, 2023 |
| Dell          | Latitude 5580               | Notebook    | [16f62b67d3](https://linux-hardware.org/?probe=16f62b67d3) | Jul 17, 2023 |
| Google        | Dragonair                   | Notebook    | [11d9394545](https://linux-hardware.org/?probe=11d9394545) | Jul 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a83e3b42b3](https://linux-hardware.org/?probe=a83e3b42b3) | Jul 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [553cbdb79d](https://linux-hardware.org/?probe=553cbdb79d) | Jul 17, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [56a9ce9630](https://linux-hardware.org/?probe=56a9ce9630) | Jul 17, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [e46543841d](https://linux-hardware.org/?probe=e46543841d) | Jul 16, 2023 |
| Dell          | G15 5520                    | Notebook    | [ed22e67151](https://linux-hardware.org/?probe=ed22e67151) | Jul 16, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [8977d2e0a3](https://linux-hardware.org/?probe=8977d2e0a3) | Jul 16, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [19b39ef686](https://linux-hardware.org/?probe=19b39ef686) | Jul 16, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [61ed023e0c](https://linux-hardware.org/?probe=61ed023e0c) | Jul 16, 2023 |
| HP            | 8053                        | Desktop     | [bcdddcb036](https://linux-hardware.org/?probe=bcdddcb036) | Jul 15, 2023 |
| Dell          | G3 3779                     | Notebook    | [87b8ecffa4](https://linux-hardware.org/?probe=87b8ecffa4) | Jul 15, 2023 |
| Acer          | One S1003                   | Tablet      | [0e200bc1a5](https://linux-hardware.org/?probe=0e200bc1a5) | Jul 15, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [56448b6dd8](https://linux-hardware.org/?probe=56448b6dd8) | Jul 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [10946f1220](https://linux-hardware.org/?probe=10946f1220) | Jul 15, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [064a46bc1d](https://linux-hardware.org/?probe=064a46bc1d) | Jul 14, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [c56d5e4e7b](https://linux-hardware.org/?probe=c56d5e4e7b) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f1bbc61bb6](https://linux-hardware.org/?probe=f1bbc61bb6) | Jul 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0ac2423aa2](https://linux-hardware.org/?probe=0ac2423aa2) | Jul 14, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1577fae8ee](https://linux-hardware.org/?probe=1577fae8ee) | Jul 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [76513f6a7d](https://linux-hardware.org/?probe=76513f6a7d) | Jul 14, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [7816d37e02](https://linux-hardware.org/?probe=7816d37e02) | Jul 14, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [67b2bb6155](https://linux-hardware.org/?probe=67b2bb6155) | Jul 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [91145d3929](https://linux-hardware.org/?probe=91145d3929) | Jul 13, 2023 |
| Lenovo        | ThinkPad X280 20KES73S06    | Notebook    | [b301164e01](https://linux-hardware.org/?probe=b301164e01) | Jul 13, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [fa3485dbc6](https://linux-hardware.org/?probe=fa3485dbc6) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2f943c811e](https://linux-hardware.org/?probe=2f943c811e) | Jul 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [9430a42f8b](https://linux-hardware.org/?probe=9430a42f8b) | Jul 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f73994358d](https://linux-hardware.org/?probe=f73994358d) | Jul 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b189eebd1c](https://linux-hardware.org/?probe=b189eebd1c) | Jul 13, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [99c9883e16](https://linux-hardware.org/?probe=99c9883e16) | Jul 12, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [85d4919b9c](https://linux-hardware.org/?probe=85d4919b9c) | Jul 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a167d41a74](https://linux-hardware.org/?probe=a167d41a74) | Jul 12, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [6e7ff15b27](https://linux-hardware.org/?probe=6e7ff15b27) | Jul 11, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [72454f0f8e](https://linux-hardware.org/?probe=72454f0f8e) | Jul 11, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ea833bb195](https://linux-hardware.org/?probe=ea833bb195) | Jul 11, 2023 |
| HP            | Folio 13                    | Notebook    | [864b74d611](https://linux-hardware.org/?probe=864b74d611) | Jul 11, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [cc4f862316](https://linux-hardware.org/?probe=cc4f862316) | Jul 11, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0549d09ceb](https://linux-hardware.org/?probe=0549d09ceb) | Jul 11, 2023 |
| HP            | 21D0                        | Desktop     | [a6d51a414c](https://linux-hardware.org/?probe=a6d51a414c) | Jul 11, 2023 |
| HP            | Folio 13                    | Notebook    | [35d5a3c2a3](https://linux-hardware.org/?probe=35d5a3c2a3) | Jul 11, 2023 |
| Dell          | Inspiron 7573               | Notebook    | [7cc0dc9187](https://linux-hardware.org/?probe=7cc0dc9187) | Jul 11, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [cf79171424](https://linux-hardware.org/?probe=cf79171424) | Jul 10, 2023 |
| MSI           | MS-7309                     | Desktop     | [16f6545b66](https://linux-hardware.org/?probe=16f6545b66) | Jul 10, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [ef2ca9e804](https://linux-hardware.org/?probe=ef2ca9e804) | Jul 10, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [3924343595](https://linux-hardware.org/?probe=3924343595) | Jul 10, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [61ac758cca](https://linux-hardware.org/?probe=61ac758cca) | Jul 10, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [7790bc9f7b](https://linux-hardware.org/?probe=7790bc9f7b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [ea2102a05b](https://linux-hardware.org/?probe=ea2102a05b) | Jul 09, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [655b6ba155](https://linux-hardware.org/?probe=655b6ba155) | Jul 09, 2023 |
| Intel         | H61                         | Desktop     | [11e024727c](https://linux-hardware.org/?probe=11e024727c) | Jul 09, 2023 |
| HP            | ZBook Studio x360 G5        | Convertible | [e01e0e6f7e](https://linux-hardware.org/?probe=e01e0e6f7e) | Jul 09, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [db2be54a62](https://linux-hardware.org/?probe=db2be54a62) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [ee4b75fe8e](https://linux-hardware.org/?probe=ee4b75fe8e) | Jul 09, 2023 |
| Notebook      | N141CU                      | Notebook    | [6d98546fa9](https://linux-hardware.org/?probe=6d98546fa9) | Jul 09, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [e23beb2c2a](https://linux-hardware.org/?probe=e23beb2c2a) | Jul 08, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [8ef192f620](https://linux-hardware.org/?probe=8ef192f620) | Jul 08, 2023 |
| HP            | 83E2                        | Desktop     | [7764034dad](https://linux-hardware.org/?probe=7764034dad) | Jul 08, 2023 |
| Dell          | Latitude 3380               | Notebook    | [b4403e7b15](https://linux-hardware.org/?probe=b4403e7b15) | Jul 07, 2023 |
| HP            | Folio 13                    | Notebook    | [dd1a09fa9d](https://linux-hardware.org/?probe=dd1a09fa9d) | Jul 07, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [28b2f72ea7](https://linux-hardware.org/?probe=28b2f72ea7) | Jul 07, 2023 |
| Acer          | Predator G3600              | Desktop     | [79f515acf1](https://linux-hardware.org/?probe=79f515acf1) | Jul 07, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1327d1ff3b](https://linux-hardware.org/?probe=1327d1ff3b) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [dd071cd632](https://linux-hardware.org/?probe=dd071cd632) | Jul 07, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [fdb4fd8cb4](https://linux-hardware.org/?probe=fdb4fd8cb4) | Jul 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e7a7107e85](https://linux-hardware.org/?probe=e7a7107e85) | Jul 07, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [7d1d71b0fe](https://linux-hardware.org/?probe=7d1d71b0fe) | Jul 06, 2023 |
| HP            | 8053                        | Desktop     | [66ee68d1ba](https://linux-hardware.org/?probe=66ee68d1ba) | Jul 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [56609b5da2](https://linux-hardware.org/?probe=56609b5da2) | Jul 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e6d6494e7a](https://linux-hardware.org/?probe=e6d6494e7a) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [cd2c46c45c](https://linux-hardware.org/?probe=cd2c46c45c) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [54a88e79d1](https://linux-hardware.org/?probe=54a88e79d1) | Jul 04, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [941c70d512](https://linux-hardware.org/?probe=941c70d512) | Jul 04, 2023 |
| CompuLab      | fitlet                      | Mini pc     | [41b26129b6](https://linux-hardware.org/?probe=41b26129b6) | Jul 04, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [075cc6eb8a](https://linux-hardware.org/?probe=075cc6eb8a) | Jul 04, 2023 |
| Dell          | Inspiron 5765               | Notebook    | [7d34d64627](https://linux-hardware.org/?probe=7d34d64627) | Jul 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [bba1bf2655](https://linux-hardware.org/?probe=bba1bf2655) | Jul 04, 2023 |
| Foxconn       | H81MXV/H81MXV-D             | Desktop     | [5920f3fec9](https://linux-hardware.org/?probe=5920f3fec9) | Jul 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [5d1b3596c1](https://linux-hardware.org/?probe=5d1b3596c1) | Jul 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [3290dd955a](https://linux-hardware.org/?probe=3290dd955a) | Jul 03, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [78bdc20fe8](https://linux-hardware.org/?probe=78bdc20fe8) | Jul 03, 2023 |
| HP            | 886C                        | Desktop     | [735b488512](https://linux-hardware.org/?probe=735b488512) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b7222ef19f](https://linux-hardware.org/?probe=b7222ef19f) | Jul 03, 2023 |
| HP            | Folio 13                    | Notebook    | [faf3cb7d1f](https://linux-hardware.org/?probe=faf3cb7d1f) | Jul 03, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [f78f6977d9](https://linux-hardware.org/?probe=f78f6977d9) | Jul 03, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6ce7d33591](https://linux-hardware.org/?probe=6ce7d33591) | Jul 03, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [8120591fdf](https://linux-hardware.org/?probe=8120591fdf) | Jul 02, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e3285ce484](https://linux-hardware.org/?probe=e3285ce484) | Jul 02, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [4f24850748](https://linux-hardware.org/?probe=4f24850748) | Jul 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f341618e19](https://linux-hardware.org/?probe=f341618e19) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5a84f67b67](https://linux-hardware.org/?probe=5a84f67b67) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [48df5942cf](https://linux-hardware.org/?probe=48df5942cf) | Jul 02, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [7bdc183ddc](https://linux-hardware.org/?probe=7bdc183ddc) | Jul 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f22f547276](https://linux-hardware.org/?probe=f22f547276) | Jul 01, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d3fb700ff1](https://linux-hardware.org/?probe=d3fb700ff1) | Jul 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a559729258](https://linux-hardware.org/?probe=a559729258) | Jul 01, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [6c8a67be9e](https://linux-hardware.org/?probe=6c8a67be9e) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10467d9f3e](https://linux-hardware.org/?probe=10467d9f3e) | Jun 30, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [3e1517b7a7](https://linux-hardware.org/?probe=3e1517b7a7) | Jun 30, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [c959833db6](https://linux-hardware.org/?probe=c959833db6) | Jun 30, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [3932620fb9](https://linux-hardware.org/?probe=3932620fb9) | Jun 30, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [a73fd92e21](https://linux-hardware.org/?probe=a73fd92e21) | Jun 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [69cb8803e1](https://linux-hardware.org/?probe=69cb8803e1) | Jun 29, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [eb31590a2c](https://linux-hardware.org/?probe=eb31590a2c) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [b8194aee09](https://linux-hardware.org/?probe=b8194aee09) | Jun 28, 2023 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [031ec94437](https://linux-hardware.org/?probe=031ec94437) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [cb40f5d060](https://linux-hardware.org/?probe=cb40f5d060) | Jun 28, 2023 |
| ASRock        | Z75 Pro3                    | Desktop     | [13ac46e7fb](https://linux-hardware.org/?probe=13ac46e7fb) | Jun 28, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [966b21f9af](https://linux-hardware.org/?probe=966b21f9af) | Jun 28, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1ef6edecef](https://linux-hardware.org/?probe=1ef6edecef) | Jun 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [98ad52d973](https://linux-hardware.org/?probe=98ad52d973) | Jun 28, 2023 |
| AZW           | GTR V02                     | Desktop     | [d8a1975328](https://linux-hardware.org/?probe=d8a1975328) | Jun 27, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9128946047](https://linux-hardware.org/?probe=9128946047) | Jun 27, 2023 |
| HP            | 2B2C                        | Desktop     | [a8ec805431](https://linux-hardware.org/?probe=a8ec805431) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [dc32791d25](https://linux-hardware.org/?probe=dc32791d25) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [adf7a275be](https://linux-hardware.org/?probe=adf7a275be) | Jun 27, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [6958b0e619](https://linux-hardware.org/?probe=6958b0e619) | Jun 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9e3cbeb0f5](https://linux-hardware.org/?probe=9e3cbeb0f5) | Jun 27, 2023 |
| Dell          | Latitude E6230              | Notebook    | [b52e22e663](https://linux-hardware.org/?probe=b52e22e663) | Jun 27, 2023 |
| ASRock        | G31M-S                      | Desktop     | [2437008395](https://linux-hardware.org/?probe=2437008395) | Jun 26, 2023 |
| HP            | 859B                        | Desktop     | [63fdd4ed7e](https://linux-hardware.org/?probe=63fdd4ed7e) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [13c7f88d66](https://linux-hardware.org/?probe=13c7f88d66) | Jun 26, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [b598080123](https://linux-hardware.org/?probe=b598080123) | Jun 26, 2023 |
| MSI           | GP72MVR 7RGX                | Notebook    | [7fa12ec2d8](https://linux-hardware.org/?probe=7fa12ec2d8) | Jun 26, 2023 |
| HP            | 8599                        | Desktop     | [d72522f488](https://linux-hardware.org/?probe=d72522f488) | Jun 26, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [bc4e778aa5](https://linux-hardware.org/?probe=bc4e778aa5) | Jun 26, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [ad1a470baf](https://linux-hardware.org/?probe=ad1a470baf) | Jun 26, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [3b27404402](https://linux-hardware.org/?probe=3b27404402) | Jun 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3df76bbd0e](https://linux-hardware.org/?probe=3df76bbd0e) | Jun 26, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [49172baecf](https://linux-hardware.org/?probe=49172baecf) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1a21c582de](https://linux-hardware.org/?probe=1a21c582de) | Jun 26, 2023 |
| HP            | 2B2C                        | Desktop     | [3b82186362](https://linux-hardware.org/?probe=3b82186362) | Jun 26, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [1a5d46559c](https://linux-hardware.org/?probe=1a5d46559c) | Jun 25, 2023 |
| Intel         | X99H                        | Desktop     | [60f1f4a8ba](https://linux-hardware.org/?probe=60f1f4a8ba) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [62dd78e250](https://linux-hardware.org/?probe=62dd78e250) | Jun 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [f84d78f3cf](https://linux-hardware.org/?probe=f84d78f3cf) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5679200535](https://linux-hardware.org/?probe=5679200535) | Jun 24, 2023 |
| Intel         | H61                         | Desktop     | [0f1d3e1299](https://linux-hardware.org/?probe=0f1d3e1299) | Jun 24, 2023 |
| HP            | 0A54h                       | Desktop     | [7383b90fc8](https://linux-hardware.org/?probe=7383b90fc8) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [628fca0448](https://linux-hardware.org/?probe=628fca0448) | Jun 24, 2023 |
| AZW           | GT-R                        | Notebook    | [11f032f354](https://linux-hardware.org/?probe=11f032f354) | Jun 24, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b7ac1c1ba6](https://linux-hardware.org/?probe=b7ac1c1ba6) | Jun 24, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [cafe332307](https://linux-hardware.org/?probe=cafe332307) | Jun 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [007cf1edce](https://linux-hardware.org/?probe=007cf1edce) | Jun 23, 2023 |
| HP            | 0A54h                       | Desktop     | [8cf79bc35e](https://linux-hardware.org/?probe=8cf79bc35e) | Jun 23, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [abbe9c9751](https://linux-hardware.org/?probe=abbe9c9751) | Jun 23, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [70b7839ea8](https://linux-hardware.org/?probe=70b7839ea8) | Jun 23, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [645a24c7bc](https://linux-hardware.org/?probe=645a24c7bc) | Jun 23, 2023 |
| Dell          | G5 5505                     | Notebook    | [dbe52869d7](https://linux-hardware.org/?probe=dbe52869d7) | Jun 23, 2023 |
| Dell          | Latitude E6420              | Notebook    | [162293d893](https://linux-hardware.org/?probe=162293d893) | Jun 23, 2023 |
| Dell          | G5 5505                     | Notebook    | [f435440e91](https://linux-hardware.org/?probe=f435440e91) | Jun 23, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [7f87bb5b32](https://linux-hardware.org/?probe=7f87bb5b32) | Jun 23, 2023 |
| MSI           | GL73 8RD                    | Notebook    | [2739b46bbe](https://linux-hardware.org/?probe=2739b46bbe) | Jun 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [70b047f976](https://linux-hardware.org/?probe=70b047f976) | Jun 22, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [2807f81cc7](https://linux-hardware.org/?probe=2807f81cc7) | Jun 22, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [bbdbdd30a9](https://linux-hardware.org/?probe=bbdbdd30a9) | Jun 22, 2023 |
| HP            | 2B2C                        | Desktop     | [4303d28839](https://linux-hardware.org/?probe=4303d28839) | Jun 22, 2023 |
| HP            | 802F                        | Desktop     | [da2666b4b8](https://linux-hardware.org/?probe=da2666b4b8) | Jun 22, 2023 |
| Sony          | SVE1712C1EW                 | Notebook    | [12f0ee026f](https://linux-hardware.org/?probe=12f0ee026f) | Jun 22, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [3d506cafad](https://linux-hardware.org/?probe=3d506cafad) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [69dfee1765](https://linux-hardware.org/?probe=69dfee1765) | Jun 22, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [5199a5d1f8](https://linux-hardware.org/?probe=5199a5d1f8) | Jun 22, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [198b248306](https://linux-hardware.org/?probe=198b248306) | Jun 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [6609cc4a31](https://linux-hardware.org/?probe=6609cc4a31) | Jun 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [31d17d4d65](https://linux-hardware.org/?probe=31d17d4d65) | Jun 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [8845f67824](https://linux-hardware.org/?probe=8845f67824) | Jun 22, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [eba6a24be2](https://linux-hardware.org/?probe=eba6a24be2) | Jun 21, 2023 |
| MSI           | X99A SLI Krait Edition      | Desktop     | [2e86965134](https://linux-hardware.org/?probe=2e86965134) | Jun 21, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [fd3c5ae570](https://linux-hardware.org/?probe=fd3c5ae570) | Jun 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [3574f89b15](https://linux-hardware.org/?probe=3574f89b15) | Jun 21, 2023 |
| HP            | 802F                        | Desktop     | [96b020f763](https://linux-hardware.org/?probe=96b020f763) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [fc06bc7209](https://linux-hardware.org/?probe=fc06bc7209) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0a36c0985d](https://linux-hardware.org/?probe=0a36c0985d) | Jun 20, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [0ccace2cfb](https://linux-hardware.org/?probe=0ccace2cfb) | Jun 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [3e09affd03](https://linux-hardware.org/?probe=3e09affd03) | Jun 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [529320d8fe](https://linux-hardware.org/?probe=529320d8fe) | Jun 20, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [b6b7fa0f5d](https://linux-hardware.org/?probe=b6b7fa0f5d) | Jun 19, 2023 |
| MSI           | Z170A GAMING M7             | Desktop     | [49e7c6d51b](https://linux-hardware.org/?probe=49e7c6d51b) | Jun 19, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [7b370bd18c](https://linux-hardware.org/?probe=7b370bd18c) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [63381e724a](https://linux-hardware.org/?probe=63381e724a) | Jun 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [3acc831573](https://linux-hardware.org/?probe=3acc831573) | Jun 19, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [6579287940](https://linux-hardware.org/?probe=6579287940) | Jun 18, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [928b30815b](https://linux-hardware.org/?probe=928b30815b) | Jun 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [f4cf5bef09](https://linux-hardware.org/?probe=f4cf5bef09) | Jun 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [9fe2c6961e](https://linux-hardware.org/?probe=9fe2c6961e) | Jun 18, 2023 |
| Dell          | 06JWJY A01                  | Desktop     | [2131eadb5b](https://linux-hardware.org/?probe=2131eadb5b) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [8fe751618d](https://linux-hardware.org/?probe=8fe751618d) | Jun 18, 2023 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [8385742d7d](https://linux-hardware.org/?probe=8385742d7d) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [337d8e9d36](https://linux-hardware.org/?probe=337d8e9d36) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5c365e154b](https://linux-hardware.org/?probe=5c365e154b) | Jun 17, 2023 |
| Intel         | H55                         | Desktop     | [d47f462b1a](https://linux-hardware.org/?probe=d47f462b1a) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4907b6927a](https://linux-hardware.org/?probe=4907b6927a) | Jun 16, 2023 |
| HP            | 886C                        | Desktop     | [ef429234c7](https://linux-hardware.org/?probe=ef429234c7) | Jun 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1412c501d2](https://linux-hardware.org/?probe=1412c501d2) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [896d66d33f](https://linux-hardware.org/?probe=896d66d33f) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [b26c331bfc](https://linux-hardware.org/?probe=b26c331bfc) | Jun 16, 2023 |
| Intel         | H55                         | Desktop     | [76c89618f1](https://linux-hardware.org/?probe=76c89618f1) | Jun 16, 2023 |
| CompuLab      | fitlet                      | Mini pc     | [82c3257031](https://linux-hardware.org/?probe=82c3257031) | Jun 16, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [4448a99385](https://linux-hardware.org/?probe=4448a99385) | Jun 16, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [9c446242a8](https://linux-hardware.org/?probe=9c446242a8) | Jun 15, 2023 |
| Intel         | H61                         | Desktop     | [ac2b137243](https://linux-hardware.org/?probe=ac2b137243) | Jun 15, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [bd74568d10](https://linux-hardware.org/?probe=bd74568d10) | Jun 15, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [175aa8aae4](https://linux-hardware.org/?probe=175aa8aae4) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [dba6acd01e](https://linux-hardware.org/?probe=dba6acd01e) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [3dd5692b24](https://linux-hardware.org/?probe=3dd5692b24) | Jun 15, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [550aa0fda6](https://linux-hardware.org/?probe=550aa0fda6) | Jun 14, 2023 |
| ASRock        | Z97 Extreme6                | Desktop     | [8f727c50fb](https://linux-hardware.org/?probe=8f727c50fb) | Jun 14, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [0e499971b7](https://linux-hardware.org/?probe=0e499971b7) | Jun 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [5349772ea1](https://linux-hardware.org/?probe=5349772ea1) | Jun 14, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [192105166b](https://linux-hardware.org/?probe=192105166b) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0b917dc778](https://linux-hardware.org/?probe=0b917dc778) | Jun 13, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [e722fda49e](https://linux-hardware.org/?probe=e722fda49e) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [bd6a04d15d](https://linux-hardware.org/?probe=bd6a04d15d) | Jun 13, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [6a1f1e134c](https://linux-hardware.org/?probe=6a1f1e134c) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c3ec3eaa27](https://linux-hardware.org/?probe=c3ec3eaa27) | Jun 13, 2023 |
| Acidanther... | Mac-AF89B6D9451A490B iMa... | All in one  | [b9e0fd4223](https://linux-hardware.org/?probe=b9e0fd4223) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [58235def6c](https://linux-hardware.org/?probe=58235def6c) | Jun 12, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [1fad9d3d52](https://linux-hardware.org/?probe=1fad9d3d52) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [98a4801b23](https://linux-hardware.org/?probe=98a4801b23) | Jun 12, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7be8732d39](https://linux-hardware.org/?probe=7be8732d39) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [66a01fdc35](https://linux-hardware.org/?probe=66a01fdc35) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [f92739d54b](https://linux-hardware.org/?probe=f92739d54b) | Jun 11, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [2fe8080014](https://linux-hardware.org/?probe=2fe8080014) | Jun 11, 2023 |
| HP            | OMEN by Laptop 15t-en000    | Notebook    | [cdda8d0103](https://linux-hardware.org/?probe=cdda8d0103) | Jun 11, 2023 |
| HP            | 2B0D A01                    | All in one  | [b4f5677d00](https://linux-hardware.org/?probe=b4f5677d00) | Jun 11, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [a192769f1b](https://linux-hardware.org/?probe=a192769f1b) | Jun 11, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [8a07e36a48](https://linux-hardware.org/?probe=8a07e36a48) | Jun 11, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [396e828c07](https://linux-hardware.org/?probe=396e828c07) | Jun 11, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [d71e612bbb](https://linux-hardware.org/?probe=d71e612bbb) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7eda1ce433](https://linux-hardware.org/?probe=7eda1ce433) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4fcc967374](https://linux-hardware.org/?probe=4fcc967374) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [864729436a](https://linux-hardware.org/?probe=864729436a) | Jun 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [07dac575d9](https://linux-hardware.org/?probe=07dac575d9) | Jun 10, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [49ebfc0459](https://linux-hardware.org/?probe=49ebfc0459) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [7ab0866235](https://linux-hardware.org/?probe=7ab0866235) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [29085f8fb4](https://linux-hardware.org/?probe=29085f8fb4) | Jun 10, 2023 |
| MSI           | MS-B9321                    | Desktop     | [a7a878dbe6](https://linux-hardware.org/?probe=a7a878dbe6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0eae3567d9](https://linux-hardware.org/?probe=0eae3567d9) | Jun 10, 2023 |
| ASRock        | B550AM Gaming               | Desktop     | [eca79c3bbb](https://linux-hardware.org/?probe=eca79c3bbb) | Jun 10, 2023 |
| Lenovo        | ThinkPad T440 20B6005RUS    | Notebook    | [e7ea5a9368](https://linux-hardware.org/?probe=e7ea5a9368) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [5446a0003e](https://linux-hardware.org/?probe=5446a0003e) | Jun 10, 2023 |
| HP            | Notebook                    | Notebook    | [9487146a2f](https://linux-hardware.org/?probe=9487146a2f) | Jun 09, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [9b52b20f3e](https://linux-hardware.org/?probe=9b52b20f3e) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [c5accf4cf8](https://linux-hardware.org/?probe=c5accf4cf8) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [45e51a6b5d](https://linux-hardware.org/?probe=45e51a6b5d) | Jun 09, 2023 |
| HP            | 2B0D A01                    | All in one  | [84275606e0](https://linux-hardware.org/?probe=84275606e0) | Jun 09, 2023 |
| Acer          | Aspire A517-53              | Notebook    | [c14dcffa32](https://linux-hardware.org/?probe=c14dcffa32) | Jun 08, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3f04b950e8](https://linux-hardware.org/?probe=3f04b950e8) | Jun 08, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [4614addc21](https://linux-hardware.org/?probe=4614addc21) | Jun 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [b7f109f62e](https://linux-hardware.org/?probe=b7f109f62e) | Jun 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [8d48df5869](https://linux-hardware.org/?probe=8d48df5869) | Jun 07, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [73bc5d84c9](https://linux-hardware.org/?probe=73bc5d84c9) | Jun 07, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [281be42f34](https://linux-hardware.org/?probe=281be42f34) | Jun 07, 2023 |
| Lenovo        | G585 20137                  | Notebook    | [6eeacffa3c](https://linux-hardware.org/?probe=6eeacffa3c) | Jun 07, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [db91b1b71c](https://linux-hardware.org/?probe=db91b1b71c) | Jun 07, 2023 |
| Dell          | 06D7TR A01                  | Desktop     | [8db1a8c132](https://linux-hardware.org/?probe=8db1a8c132) | Jun 06, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [d2c05f91c4](https://linux-hardware.org/?probe=d2c05f91c4) | Jun 06, 2023 |
| HP            | 8053                        | Desktop     | [29a84ce224](https://linux-hardware.org/?probe=29a84ce224) | Jun 06, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [249f9343d0](https://linux-hardware.org/?probe=249f9343d0) | Jun 06, 2023 |
| Win elemen... | M600                        | Desktop     | [360ab80d9b](https://linux-hardware.org/?probe=360ab80d9b) | Jun 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [bdfe605b6a](https://linux-hardware.org/?probe=bdfe605b6a) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a9ea51ea77](https://linux-hardware.org/?probe=a9ea51ea77) | Jun 06, 2023 |
| Dell          | Precision 7510              | Notebook    | [2a465173d3](https://linux-hardware.org/?probe=2a465173d3) | Jun 06, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [18663e1382](https://linux-hardware.org/?probe=18663e1382) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Toshiba       | Satellite L305              | Notebook    | [c11012336c](https://linux-hardware.org/?probe=c11012336c) | Jun 05, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [917462f8c8](https://linux-hardware.org/?probe=917462f8c8) | Jun 05, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [50f682ce84](https://linux-hardware.org/?probe=50f682ce84) | Jun 04, 2023 |
| SYWZ          | S200 Series                 | Desktop     | [577c490fb7](https://linux-hardware.org/?probe=577c490fb7) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87b33e1181](https://linux-hardware.org/?probe=87b33e1181) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [9a66179aaf](https://linux-hardware.org/?probe=9a66179aaf) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a39c2e8d55](https://linux-hardware.org/?probe=a39c2e8d55) | Jun 04, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [b0efe96508](https://linux-hardware.org/?probe=b0efe96508) | Jun 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [6f8af3d7af](https://linux-hardware.org/?probe=6f8af3d7af) | Jun 03, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [b92c18e955](https://linux-hardware.org/?probe=b92c18e955) | Jun 03, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [5ee3eec233](https://linux-hardware.org/?probe=5ee3eec233) | Jun 03, 2023 |
| Acer          | TravelMate 8572T            | Notebook    | [46920007ed](https://linux-hardware.org/?probe=46920007ed) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 2325SLU       | Notebook    | [3a1d630346](https://linux-hardware.org/?probe=3a1d630346) | Jun 03, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [30a95a3f53](https://linux-hardware.org/?probe=30a95a3f53) | Jun 03, 2023 |
| AZW           | SER V01                     | Mini pc     | [e28ef4a6b7](https://linux-hardware.org/?probe=e28ef4a6b7) | Jun 03, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [7837922f5b](https://linux-hardware.org/?probe=7837922f5b) | Jun 02, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [3de77b392a](https://linux-hardware.org/?probe=3de77b392a) | Jun 02, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [b4ba7702cb](https://linux-hardware.org/?probe=b4ba7702cb) | Jun 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c9e073b763](https://linux-hardware.org/?probe=c9e073b763) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [ca1bce793b](https://linux-hardware.org/?probe=ca1bce793b) | Jun 01, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [1bd92e67d7](https://linux-hardware.org/?probe=1bd92e67d7) | Jun 01, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [d75bfc397f](https://linux-hardware.org/?probe=d75bfc397f) | Jun 01, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [6b3efa1ef7](https://linux-hardware.org/?probe=6b3efa1ef7) | May 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [270fcf5e69](https://linux-hardware.org/?probe=270fcf5e69) | May 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [79de4bed98](https://linux-hardware.org/?probe=79de4bed98) | May 31, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6c814f5bb5](https://linux-hardware.org/?probe=6c814f5bb5) | May 31, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [d21f59bea5](https://linux-hardware.org/?probe=d21f59bea5) | May 31, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [9131b2b568](https://linux-hardware.org/?probe=9131b2b568) | May 31, 2023 |
| Acer          | Predator G9-793             | Notebook    | [26ea66d872](https://linux-hardware.org/?probe=26ea66d872) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [eae4d1e9ba](https://linux-hardware.org/?probe=eae4d1e9ba) | May 31, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [2ad4b7fd55](https://linux-hardware.org/?probe=2ad4b7fd55) | May 30, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6dbaa9e2ff](https://linux-hardware.org/?probe=6dbaa9e2ff) | May 30, 2023 |
| HP            | 82DC 1000                   | All in one  | [8300907fc1](https://linux-hardware.org/?probe=8300907fc1) | May 30, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [4ed64d3d45](https://linux-hardware.org/?probe=4ed64d3d45) | May 30, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [5c089f9b06](https://linux-hardware.org/?probe=5c089f9b06) | May 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [8ec80f5e43](https://linux-hardware.org/?probe=8ec80f5e43) | May 30, 2023 |
| Dell          | 002KVM A01                  | Desktop     | [09d2d63c82](https://linux-hardware.org/?probe=09d2d63c82) | May 30, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8e0413af72](https://linux-hardware.org/?probe=8e0413af72) | May 30, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [9171b7f0f0](https://linux-hardware.org/?probe=9171b7f0f0) | May 29, 2023 |
| Lenovo        | ThinkPad T430 2349GDU       | Notebook    | [829c193554](https://linux-hardware.org/?probe=829c193554) | May 29, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [b90162f812](https://linux-hardware.org/?probe=b90162f812) | May 29, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [1aa973f6bc](https://linux-hardware.org/?probe=1aa973f6bc) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [77e5b682ff](https://linux-hardware.org/?probe=77e5b682ff) | May 28, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [04e50de864](https://linux-hardware.org/?probe=04e50de864) | May 28, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [519e04a228](https://linux-hardware.org/?probe=519e04a228) | May 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [f7f07e78d5](https://linux-hardware.org/?probe=f7f07e78d5) | May 27, 2023 |
| ASRock        | H87M Pro4                   | Desktop     | [efd2db0783](https://linux-hardware.org/?probe=efd2db0783) | May 27, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [cb642c7b9d](https://linux-hardware.org/?probe=cb642c7b9d) | May 27, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [b5fd752412](https://linux-hardware.org/?probe=b5fd752412) | May 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d5d9543a5a](https://linux-hardware.org/?probe=d5d9543a5a) | May 26, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [07ecf79e17](https://linux-hardware.org/?probe=07ecf79e17) | May 26, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [ca130b5f89](https://linux-hardware.org/?probe=ca130b5f89) | May 26, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [184afbb9c3](https://linux-hardware.org/?probe=184afbb9c3) | May 26, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [3392305134](https://linux-hardware.org/?probe=3392305134) | May 26, 2023 |
| HP            | 8437                        | Desktop     | [c1c9154683](https://linux-hardware.org/?probe=c1c9154683) | May 26, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [89b7c17d00](https://linux-hardware.org/?probe=89b7c17d00) | May 26, 2023 |
| ASUSTek       | X751LAB                     | Notebook    | [02b17f35d9](https://linux-hardware.org/?probe=02b17f35d9) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [13906a8f3d](https://linux-hardware.org/?probe=13906a8f3d) | May 26, 2023 |
| A14CR         | Unknown                     | Notebook    | [a504061244](https://linux-hardware.org/?probe=a504061244) | May 25, 2023 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [b00cde0e71](https://linux-hardware.org/?probe=b00cde0e71) | May 25, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [52e1964d2c](https://linux-hardware.org/?probe=52e1964d2c) | May 25, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [7389c979b6](https://linux-hardware.org/?probe=7389c979b6) | May 25, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [e52868c107](https://linux-hardware.org/?probe=e52868c107) | May 25, 2023 |
| Dell          | Precision 7510              | Notebook    | [8c677420fa](https://linux-hardware.org/?probe=8c677420fa) | May 25, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [1387725836](https://linux-hardware.org/?probe=1387725836) | May 24, 2023 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c309714d15](https://linux-hardware.org/?probe=c309714d15) | May 23, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [627afe1447](https://linux-hardware.org/?probe=627afe1447) | May 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3d594ff1da](https://linux-hardware.org/?probe=3d594ff1da) | May 23, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a2986e9b7a](https://linux-hardware.org/?probe=a2986e9b7a) | May 23, 2023 |
| Lenovo        | ThinkPad T550 20CJS0S800    | Notebook    | [b7efa91563](https://linux-hardware.org/?probe=b7efa91563) | May 23, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [e250801798](https://linux-hardware.org/?probe=e250801798) | May 23, 2023 |
| Dell          | Precision 7510              | Notebook    | [15458a1b29](https://linux-hardware.org/?probe=15458a1b29) | May 22, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [87b976a24c](https://linux-hardware.org/?probe=87b976a24c) | May 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [5e89fe1dc9](https://linux-hardware.org/?probe=5e89fe1dc9) | May 22, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | Notebook    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [a1fb857bcc](https://linux-hardware.org/?probe=a1fb857bcc) | May 22, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | Notebook    | [7cba5b3595](https://linux-hardware.org/?probe=7cba5b3595) | May 22, 2023 |
| HP            | 8599                        | Desktop     | [2e9caaf13a](https://linux-hardware.org/?probe=2e9caaf13a) | May 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ab21a2a608](https://linux-hardware.org/?probe=ab21a2a608) | May 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [ef28026334](https://linux-hardware.org/?probe=ef28026334) | May 22, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [5534aabaf1](https://linux-hardware.org/?probe=5534aabaf1) | May 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [cf10c1fb13](https://linux-hardware.org/?probe=cf10c1fb13) | May 21, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [9db5706bfc](https://linux-hardware.org/?probe=9db5706bfc) | May 21, 2023 |
| ASUSTek       | X540SC                      | Notebook    | [240bb6c246](https://linux-hardware.org/?probe=240bb6c246) | May 21, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [e7a27c7429](https://linux-hardware.org/?probe=e7a27c7429) | May 21, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [2df0364d3c](https://linux-hardware.org/?probe=2df0364d3c) | May 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [222ebac915](https://linux-hardware.org/?probe=222ebac915) | May 21, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [bc16fc021e](https://linux-hardware.org/?probe=bc16fc021e) | May 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8f2ccf9c6d](https://linux-hardware.org/?probe=8f2ccf9c6d) | May 21, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1fdf5742d0](https://linux-hardware.org/?probe=1fdf5742d0) | May 21, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [3e94769b79](https://linux-hardware.org/?probe=3e94769b79) | May 20, 2023 |
| Lenovo        | ThinkPad T430 2347EA2       | Notebook    | [dc3fdbd5ff](https://linux-hardware.org/?probe=dc3fdbd5ff) | May 20, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [14e978a000](https://linux-hardware.org/?probe=14e978a000) | May 20, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [d687dbc74a](https://linux-hardware.org/?probe=d687dbc74a) | May 20, 2023 |
| HP            | 8433 11                     | Desktop     | [5d9e3a1dcc](https://linux-hardware.org/?probe=5d9e3a1dcc) | May 20, 2023 |
| Eluktronic... | MAG-15 1660Ti               | Notebook    | [55ced5d6bb](https://linux-hardware.org/?probe=55ced5d6bb) | May 20, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b001b01a08](https://linux-hardware.org/?probe=b001b01a08) | May 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f76ac6d7b5](https://linux-hardware.org/?probe=f76ac6d7b5) | May 19, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [76592cf444](https://linux-hardware.org/?probe=76592cf444) | May 19, 2023 |
| NEC Comput... | PC-VK26TXZCM                | Notebook    | [064b725160](https://linux-hardware.org/?probe=064b725160) | May 19, 2023 |
| Lenovo        | ThinkPad T430 2347EA2       | Notebook    | [c718a18472](https://linux-hardware.org/?probe=c718a18472) | May 19, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [dde73bc060](https://linux-hardware.org/?probe=dde73bc060) | May 18, 2023 |
| Medion        | BTDD-TI                     | All in one  | [cc45e1f2f4](https://linux-hardware.org/?probe=cc45e1f2f4) | May 18, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [763654d8fc](https://linux-hardware.org/?probe=763654d8fc) | May 18, 2023 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [bf1eed0e60](https://linux-hardware.org/?probe=bf1eed0e60) | May 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [3c8dcfcf15](https://linux-hardware.org/?probe=3c8dcfcf15) | May 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [fd87e57fc3](https://linux-hardware.org/?probe=fd87e57fc3) | May 18, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [856242dc26](https://linux-hardware.org/?probe=856242dc26) | May 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [70b4a6b7f7](https://linux-hardware.org/?probe=70b4a6b7f7) | May 18, 2023 |
| HP            | 339A                        | Desktop     | [44a6e1f861](https://linux-hardware.org/?probe=44a6e1f861) | May 17, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [7f3487434e](https://linux-hardware.org/?probe=7f3487434e) | May 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7957c81218](https://linux-hardware.org/?probe=7957c81218) | May 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1aedc7da48](https://linux-hardware.org/?probe=1aedc7da48) | May 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e236450e11](https://linux-hardware.org/?probe=e236450e11) | May 17, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [0c26a47ae5](https://linux-hardware.org/?probe=0c26a47ae5) | May 17, 2023 |
| Acer          | Predator G9-793             | Notebook    | [1739ea2f45](https://linux-hardware.org/?probe=1739ea2f45) | May 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f4514801d8](https://linux-hardware.org/?probe=f4514801d8) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e31c83db5e](https://linux-hardware.org/?probe=e31c83db5e) | May 16, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d9b18c7990](https://linux-hardware.org/?probe=d9b18c7990) | May 16, 2023 |
| HP            | ENVY dv6                    | Notebook    | [2490803f28](https://linux-hardware.org/?probe=2490803f28) | May 16, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [b06c75ac5e](https://linux-hardware.org/?probe=b06c75ac5e) | May 16, 2023 |
| Lenovo        | ThinkPad T440 20B7S1MF0D    | Notebook    | [6173458650](https://linux-hardware.org/?probe=6173458650) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [8c10a0ad96](https://linux-hardware.org/?probe=8c10a0ad96) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [be5ad76a6e](https://linux-hardware.org/?probe=be5ad76a6e) | May 16, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [19feb08b89](https://linux-hardware.org/?probe=19feb08b89) | May 15, 2023 |
| Google        | Sumo                        | Desktop     | [1455a81901](https://linux-hardware.org/?probe=1455a81901) | May 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [93979d632e](https://linux-hardware.org/?probe=93979d632e) | May 15, 2023 |
| Toshiba       | TECRA Z40-A                 | Notebook    | [55210b06ca](https://linux-hardware.org/?probe=55210b06ca) | May 15, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [53f395d7fa](https://linux-hardware.org/?probe=53f395d7fa) | May 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f97e4e7fc1](https://linux-hardware.org/?probe=f97e4e7fc1) | May 15, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [9beabf1347](https://linux-hardware.org/?probe=9beabf1347) | May 15, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [eaef457c8a](https://linux-hardware.org/?probe=eaef457c8a) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [36df0e0f57](https://linux-hardware.org/?probe=36df0e0f57) | May 14, 2023 |
| Unknown       | HX90                        | Desktop     | [85edf2e24e](https://linux-hardware.org/?probe=85edf2e24e) | May 14, 2023 |
| ASUSTek       | G752VT                      | Notebook    | [e8459680a4](https://linux-hardware.org/?probe=e8459680a4) | May 14, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [5bd115a1b4](https://linux-hardware.org/?probe=5bd115a1b4) | May 14, 2023 |
| HP            | ENVY 15                     | Notebook    | [0d1450cd2d](https://linux-hardware.org/?probe=0d1450cd2d) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [49a47c559e](https://linux-hardware.org/?probe=49a47c559e) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [91986cf051](https://linux-hardware.org/?probe=91986cf051) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [ced38114fc](https://linux-hardware.org/?probe=ced38114fc) | May 14, 2023 |
| Dell          | Latitude 5490               | Notebook    | [57e94dd4b7](https://linux-hardware.org/?probe=57e94dd4b7) | May 14, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [1556b05d13](https://linux-hardware.org/?probe=1556b05d13) | May 14, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [5e7cf34522](https://linux-hardware.org/?probe=5e7cf34522) | May 14, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [748e0f187f](https://linux-hardware.org/?probe=748e0f187f) | May 14, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [677e681a2d](https://linux-hardware.org/?probe=677e681a2d) | May 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [4bde221d90](https://linux-hardware.org/?probe=4bde221d90) | May 13, 2023 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [d0f5ee2781](https://linux-hardware.org/?probe=d0f5ee2781) | May 13, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [71f2dc616d](https://linux-hardware.org/?probe=71f2dc616d) | May 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [82f01de919](https://linux-hardware.org/?probe=82f01de919) | May 12, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [c0841ef7e1](https://linux-hardware.org/?probe=c0841ef7e1) | May 12, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [bfb11f92b1](https://linux-hardware.org/?probe=bfb11f92b1) | May 11, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ed18615cb3](https://linux-hardware.org/?probe=ed18615cb3) | May 11, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [12d23bdebb](https://linux-hardware.org/?probe=12d23bdebb) | May 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [efc35b1887](https://linux-hardware.org/?probe=efc35b1887) | May 11, 2023 |
| ASRock        | Z370 Extreme4               | Desktop     | [bdd9bcedf5](https://linux-hardware.org/?probe=bdd9bcedf5) | May 11, 2023 |
| Acer          | Predator G9-793             | Notebook    | [95595808a8](https://linux-hardware.org/?probe=95595808a8) | May 11, 2023 |
| ASUSTek       | TUF Gaming H670-PRO WIFI... | Desktop     | [0b4b06b5fa](https://linux-hardware.org/?probe=0b4b06b5fa) | May 10, 2023 |
| ASUSTek       | UX410UAK                    | Notebook    | [d68a2bc7c0](https://linux-hardware.org/?probe=d68a2bc7c0) | May 10, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [b65333ae05](https://linux-hardware.org/?probe=b65333ae05) | May 10, 2023 |
| Lenovo        | 36EB SDK0K17763 WIN 1801... | Desktop     | [4d68e2912b](https://linux-hardware.org/?probe=4d68e2912b) | May 10, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9ce4debe84](https://linux-hardware.org/?probe=9ce4debe84) | May 09, 2023 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [90bec72fa7](https://linux-hardware.org/?probe=90bec72fa7) | May 09, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [756ed502db](https://linux-hardware.org/?probe=756ed502db) | May 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [13bace1181](https://linux-hardware.org/?probe=13bace1181) | May 09, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d3de6b6b31](https://linux-hardware.org/?probe=d3de6b6b31) | May 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a4f7fc7b31](https://linux-hardware.org/?probe=a4f7fc7b31) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d055c2e022](https://linux-hardware.org/?probe=d055c2e022) | May 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | Notebook    | [18b79bbfa4](https://linux-hardware.org/?probe=18b79bbfa4) | May 07, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [dbeb828b17](https://linux-hardware.org/?probe=dbeb828b17) | May 07, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d58e08c9ab](https://linux-hardware.org/?probe=d58e08c9ab) | May 07, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6a93900fb9](https://linux-hardware.org/?probe=6a93900fb9) | May 07, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [1eddb3203a](https://linux-hardware.org/?probe=1eddb3203a) | May 06, 2023 |
| System76      | Oryx Pro                    | Notebook    | [6026e88ad4](https://linux-hardware.org/?probe=6026e88ad4) | May 06, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [faabff7b74](https://linux-hardware.org/?probe=faabff7b74) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [d905babc43](https://linux-hardware.org/?probe=d905babc43) | May 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1143344e93](https://linux-hardware.org/?probe=1143344e93) | May 06, 2023 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [d572509eb2](https://linux-hardware.org/?probe=d572509eb2) | May 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [91661b66d1](https://linux-hardware.org/?probe=91661b66d1) | May 06, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [5d12a9965b](https://linux-hardware.org/?probe=5d12a9965b) | May 06, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [bb7835495e](https://linux-hardware.org/?probe=bb7835495e) | May 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6a54ace5f8](https://linux-hardware.org/?probe=6a54ace5f8) | May 06, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [3bea2bcd99](https://linux-hardware.org/?probe=3bea2bcd99) | May 05, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [09e73cade8](https://linux-hardware.org/?probe=09e73cade8) | May 05, 2023 |
| ASRock        | H370 Pro4                   | Desktop     | [afffccef92](https://linux-hardware.org/?probe=afffccef92) | May 05, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e28a5499a4](https://linux-hardware.org/?probe=e28a5499a4) | May 05, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [624e1c3f06](https://linux-hardware.org/?probe=624e1c3f06) | May 05, 2023 |
| System76      | Oryx Pro                    | Notebook    | [fe799bc532](https://linux-hardware.org/?probe=fe799bc532) | May 04, 2023 |
| Gigabyte      | 2AC8                        | Desktop     | [4f5b51c45e](https://linux-hardware.org/?probe=4f5b51c45e) | May 04, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2509256cea](https://linux-hardware.org/?probe=2509256cea) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3e7b117db0](https://linux-hardware.org/?probe=3e7b117db0) | May 03, 2023 |
| Intel         | DG43GT AAE62768-300         | Desktop     | [e0f10df0f9](https://linux-hardware.org/?probe=e0f10df0f9) | May 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [728b1e3209](https://linux-hardware.org/?probe=728b1e3209) | May 03, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [c20844716d](https://linux-hardware.org/?probe=c20844716d) | May 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2b17563b98](https://linux-hardware.org/?probe=2b17563b98) | May 02, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [8b4f50125b](https://linux-hardware.org/?probe=8b4f50125b) | May 02, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [e5051f5355](https://linux-hardware.org/?probe=e5051f5355) | May 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [f4f7391b8a](https://linux-hardware.org/?probe=f4f7391b8a) | May 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9a43268d9b](https://linux-hardware.org/?probe=9a43268d9b) | May 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [8cb7a3612c](https://linux-hardware.org/?probe=8cb7a3612c) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [446a548122](https://linux-hardware.org/?probe=446a548122) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f0a784354c](https://linux-hardware.org/?probe=f0a784354c) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [332a777929](https://linux-hardware.org/?probe=332a777929) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [fa805f77f7](https://linux-hardware.org/?probe=fa805f77f7) | Apr 29, 2023 |
| Acer          | Aspire A514-54G             | Notebook    | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [0ea5e1926e](https://linux-hardware.org/?probe=0ea5e1926e) | Apr 29, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [1ef93daf0b](https://linux-hardware.org/?probe=1ef93daf0b) | Apr 28, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [852dac1035](https://linux-hardware.org/?probe=852dac1035) | Apr 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [19c2a17ec5](https://linux-hardware.org/?probe=19c2a17ec5) | Apr 27, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [cde129cf45](https://linux-hardware.org/?probe=cde129cf45) | Apr 26, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [add3c03eef](https://linux-hardware.org/?probe=add3c03eef) | Apr 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9824006277](https://linux-hardware.org/?probe=9824006277) | Apr 26, 2023 |
| HP            | 18E7                        | Desktop     | [26ca79a633](https://linux-hardware.org/?probe=26ca79a633) | Apr 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [856de630ec](https://linux-hardware.org/?probe=856de630ec) | Apr 25, 2023 |
| System76      | Oryx Pro                    | Notebook    | [298bf97b70](https://linux-hardware.org/?probe=298bf97b70) | Apr 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [962bffed9f](https://linux-hardware.org/?probe=962bffed9f) | Apr 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a2c2f1f536](https://linux-hardware.org/?probe=a2c2f1f536) | Apr 25, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [c897ecd954](https://linux-hardware.org/?probe=c897ecd954) | Apr 25, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [90fa428095](https://linux-hardware.org/?probe=90fa428095) | Apr 25, 2023 |
| ZOTAC         | ZBOX-CI527/CI547NANO        | Mini pc     | [97f86da425](https://linux-hardware.org/?probe=97f86da425) | Apr 25, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [8a600077f6](https://linux-hardware.org/?probe=8a600077f6) | Apr 25, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [cb64c7f963](https://linux-hardware.org/?probe=cb64c7f963) | Apr 25, 2023 |
| ASRock        | Z690 Extreme                | Desktop     | [3767d30290](https://linux-hardware.org/?probe=3767d30290) | Apr 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [df85ceaa6b](https://linux-hardware.org/?probe=df85ceaa6b) | Apr 24, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [6a6beb844d](https://linux-hardware.org/?probe=6a6beb844d) | Apr 23, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [66d61baf71](https://linux-hardware.org/?probe=66d61baf71) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [03bcaf6334](https://linux-hardware.org/?probe=03bcaf6334) | Apr 21, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [5b14b21a19](https://linux-hardware.org/?probe=5b14b21a19) | Apr 21, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [7641434e4d](https://linux-hardware.org/?probe=7641434e4d) | Apr 21, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [4e69a80310](https://linux-hardware.org/?probe=4e69a80310) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [880ee85934](https://linux-hardware.org/?probe=880ee85934) | Apr 21, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [d48ffa8191](https://linux-hardware.org/?probe=d48ffa8191) | Apr 21, 2023 |
| Packard Be... | EasyNote TSX62HR            | Notebook    | [7e7dbc9acd](https://linux-hardware.org/?probe=7e7dbc9acd) | Apr 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c10e38e18e](https://linux-hardware.org/?probe=c10e38e18e) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [2afe988f2e](https://linux-hardware.org/?probe=2afe988f2e) | Apr 20, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [8e02f43636](https://linux-hardware.org/?probe=8e02f43636) | Apr 20, 2023 |
| Acer          | Predator G9-793             | Notebook    | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d8025962bf](https://linux-hardware.org/?probe=d8025962bf) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [46ade409df](https://linux-hardware.org/?probe=46ade409df) | Apr 20, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [bebc7ec91b](https://linux-hardware.org/?probe=bebc7ec91b) | Apr 19, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ec0b554256](https://linux-hardware.org/?probe=ec0b554256) | Apr 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [fdb308cd9f](https://linux-hardware.org/?probe=fdb308cd9f) | Apr 19, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [618b59dac2](https://linux-hardware.org/?probe=618b59dac2) | Apr 19, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [954388c5e0](https://linux-hardware.org/?probe=954388c5e0) | Apr 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [e3ebb38e6b](https://linux-hardware.org/?probe=e3ebb38e6b) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4185aada87](https://linux-hardware.org/?probe=4185aada87) | Apr 19, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [512bad7a33](https://linux-hardware.org/?probe=512bad7a33) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [323dc7fa4b](https://linux-hardware.org/?probe=323dc7fa4b) | Apr 18, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [10bfabc1b8](https://linux-hardware.org/?probe=10bfabc1b8) | Apr 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6ce11cef12](https://linux-hardware.org/?probe=6ce11cef12) | Apr 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [efdcb6b99e](https://linux-hardware.org/?probe=efdcb6b99e) | Apr 18, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [3decfdc1f6](https://linux-hardware.org/?probe=3decfdc1f6) | Apr 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3738d57a9c](https://linux-hardware.org/?probe=3738d57a9c) | Apr 15, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [6f8dbb2e8e](https://linux-hardware.org/?probe=6f8dbb2e8e) | Apr 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [2e6b5600aa](https://linux-hardware.org/?probe=2e6b5600aa) | Apr 14, 2023 |
| Dell          | Latitude 3590               | Notebook    | [eed6f4df10](https://linux-hardware.org/?probe=eed6f4df10) | Apr 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [615a9d3871](https://linux-hardware.org/?probe=615a9d3871) | Apr 12, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ef5829077e](https://linux-hardware.org/?probe=ef5829077e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e0e2242a64](https://linux-hardware.org/?probe=e0e2242a64) | Apr 11, 2023 |
| Gigabyte      | X299 AORUS Ultra Gaming ... | Desktop     | [415b7ce80b](https://linux-hardware.org/?probe=415b7ce80b) | Apr 10, 2023 |
| BESSTAR Te... | HX90                        | Desktop     | [2639d597e8](https://linux-hardware.org/?probe=2639d597e8) | Apr 10, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fa729987de](https://linux-hardware.org/?probe=fa729987de) | Apr 09, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [ca9fe9c7f1](https://linux-hardware.org/?probe=ca9fe9c7f1) | Apr 09, 2023 |
| HP            | ENVY 15                     | Notebook    | [5ecc7b36c8](https://linux-hardware.org/?probe=5ecc7b36c8) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c2e1cb3f46](https://linux-hardware.org/?probe=c2e1cb3f46) | Apr 09, 2023 |
| ASUSTek       | Zenbook UX7602ZM            | Notebook    | [aeded4c133](https://linux-hardware.org/?probe=aeded4c133) | Apr 08, 2023 |
| HP            | Pavilion dv4                | Notebook    | [a554538ed8](https://linux-hardware.org/?probe=a554538ed8) | Apr 07, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2acb260eb1](https://linux-hardware.org/?probe=2acb260eb1) | Apr 07, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4f37849c94](https://linux-hardware.org/?probe=4f37849c94) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [cd157a6ebf](https://linux-hardware.org/?probe=cd157a6ebf) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [00fef3bb7b](https://linux-hardware.org/?probe=00fef3bb7b) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [ebc3f9d008](https://linux-hardware.org/?probe=ebc3f9d008) | Apr 06, 2023 |
| HP            | Pavilion dv7                | Notebook    | [bdb5d286b5](https://linux-hardware.org/?probe=bdb5d286b5) | Apr 06, 2023 |
| Dell          | Latitude 3510               | Notebook    | [e927d04a2d](https://linux-hardware.org/?probe=e927d04a2d) | Apr 06, 2023 |
| Biostar       | TZ77B                       | Desktop     | [c5d5603dc4](https://linux-hardware.org/?probe=c5d5603dc4) | Apr 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b9e77efbb1](https://linux-hardware.org/?probe=b9e77efbb1) | Apr 05, 2023 |
| Shenzhen W... | GB1                         | Mini pc     | [ca02164e4d](https://linux-hardware.org/?probe=ca02164e4d) | Apr 01, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6eb533f1d7](https://linux-hardware.org/?probe=6eb533f1d7) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [2cc7a15de5](https://linux-hardware.org/?probe=2cc7a15de5) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490s 20NXS0DS0... | Notebook    | [1228998af5](https://linux-hardware.org/?probe=1228998af5) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [0ff3ab318e](https://linux-hardware.org/?probe=0ff3ab318e) | Mar 31, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [dbe7f7ac9b](https://linux-hardware.org/?probe=dbe7f7ac9b) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [09679af7dc](https://linux-hardware.org/?probe=09679af7dc) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e78d2454c](https://linux-hardware.org/?probe=1e78d2454c) | Mar 31, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [01492665ee](https://linux-hardware.org/?probe=01492665ee) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0b4fae8189](https://linux-hardware.org/?probe=0b4fae8189) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [13acfd725a](https://linux-hardware.org/?probe=13acfd725a) | Mar 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [514d8ed8d6](https://linux-hardware.org/?probe=514d8ed8d6) | Mar 30, 2023 |
| HP            | 8399                        | Desktop     | [d8c0ad05f5](https://linux-hardware.org/?probe=d8c0ad05f5) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a1d2ac5e6e](https://linux-hardware.org/?probe=a1d2ac5e6e) | Mar 30, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7554f35f1d](https://linux-hardware.org/?probe=7554f35f1d) | Mar 30, 2023 |
| ASUSTek       | Q170M2                      | Desktop     | [8808e457a1](https://linux-hardware.org/?probe=8808e457a1) | Mar 29, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [2f1975360e](https://linux-hardware.org/?probe=2f1975360e) | Mar 28, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [5ac9dd16da](https://linux-hardware.org/?probe=5ac9dd16da) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| Dell          | 0W2F8G A02                  | Desktop     | [511510b501](https://linux-hardware.org/?probe=511510b501) | Mar 27, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [b960038661](https://linux-hardware.org/?probe=b960038661) | Mar 27, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [39802560c1](https://linux-hardware.org/?probe=39802560c1) | Mar 27, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [af90cee242](https://linux-hardware.org/?probe=af90cee242) | Mar 27, 2023 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [da016d15c7](https://linux-hardware.org/?probe=da016d15c7) | Mar 27, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [1ed601999d](https://linux-hardware.org/?probe=1ed601999d) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [1988691e71](https://linux-hardware.org/?probe=1988691e71) | Mar 27, 2023 |
| Unknown       | Unknown                     | Notebook    | [dd081eb573](https://linux-hardware.org/?probe=dd081eb573) | Mar 27, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [f1ed5dd70d](https://linux-hardware.org/?probe=f1ed5dd70d) | Mar 26, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [6ac498fa82](https://linux-hardware.org/?probe=6ac498fa82) | Mar 26, 2023 |
| Toshiba       | Satellite C50-A510          | Notebook    | [69eb2dad8f](https://linux-hardware.org/?probe=69eb2dad8f) | Mar 26, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [7c10ad8eb9](https://linux-hardware.org/?probe=7c10ad8eb9) | Mar 26, 2023 |
| MSI           | GT70                        | Notebook    | [8b00b28b12](https://linux-hardware.org/?probe=8b00b28b12) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [fe5c568f41](https://linux-hardware.org/?probe=fe5c568f41) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [22e7978cc8](https://linux-hardware.org/?probe=22e7978cc8) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [778f5948f1](https://linux-hardware.org/?probe=778f5948f1) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [3772f7397b](https://linux-hardware.org/?probe=3772f7397b) | Mar 26, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [915cac124b](https://linux-hardware.org/?probe=915cac124b) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f889f2ddf5](https://linux-hardware.org/?probe=f889f2ddf5) | Mar 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [513b14ace5](https://linux-hardware.org/?probe=513b14ace5) | Mar 25, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [9d9e4e184f](https://linux-hardware.org/?probe=9d9e4e184f) | Mar 25, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [6c4d5eee3f](https://linux-hardware.org/?probe=6c4d5eee3f) | Mar 25, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [765602e7bf](https://linux-hardware.org/?probe=765602e7bf) | Mar 24, 2023 |
| MSI           | A320M-HDV R4.0              | Desktop     | [a04e0acbcf](https://linux-hardware.org/?probe=a04e0acbcf) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [5b6af55009](https://linux-hardware.org/?probe=5b6af55009) | Mar 23, 2023 |
| HP            | 828A                        | Desktop     | [cce5214801](https://linux-hardware.org/?probe=cce5214801) | Mar 22, 2023 |
| Lenovo        | ThinkPad Edge S430 33643... | Notebook    | [f6b05c3b0b](https://linux-hardware.org/?probe=f6b05c3b0b) | Mar 21, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b784685da3](https://linux-hardware.org/?probe=b784685da3) | Mar 21, 2023 |
| System76      | Pangolin                    | Notebook    | [ee7dd00fbf](https://linux-hardware.org/?probe=ee7dd00fbf) | Mar 19, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c770db7fd](https://linux-hardware.org/?probe=7c770db7fd) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [49df72f291](https://linux-hardware.org/?probe=49df72f291) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [1f939ee045](https://linux-hardware.org/?probe=1f939ee045) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [5e6e5276e3](https://linux-hardware.org/?probe=5e6e5276e3) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| HP            | 18E8                        | Desktop     | [bf7c3c9080](https://linux-hardware.org/?probe=bf7c3c9080) | Mar 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [8c71ef60d0](https://linux-hardware.org/?probe=8c71ef60d0) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8681f176da](https://linux-hardware.org/?probe=8681f176da) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [70a1f8041b](https://linux-hardware.org/?probe=70a1f8041b) | Mar 17, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [593bd6b3ac](https://linux-hardware.org/?probe=593bd6b3ac) | Mar 17, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [42391e1ac6](https://linux-hardware.org/?probe=42391e1ac6) | Mar 16, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7630033ffb](https://linux-hardware.org/?probe=7630033ffb) | Mar 15, 2023 |
| Lenovo        | 36EB NOK                    | Desktop     | [b6d8243d49](https://linux-hardware.org/?probe=b6d8243d49) | Mar 15, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [60bd2eeae4](https://linux-hardware.org/?probe=60bd2eeae4) | Mar 15, 2023 |
| HP            | 828A                        | Desktop     | [9d6df1b56e](https://linux-hardware.org/?probe=9d6df1b56e) | Mar 15, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [77b68431f7](https://linux-hardware.org/?probe=77b68431f7) | Mar 14, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b94932937e](https://linux-hardware.org/?probe=b94932937e) | Mar 14, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [54d17115b9](https://linux-hardware.org/?probe=54d17115b9) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [79932e56ad](https://linux-hardware.org/?probe=79932e56ad) | Mar 13, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [1de50d9986](https://linux-hardware.org/?probe=1de50d9986) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b17210218f](https://linux-hardware.org/?probe=b17210218f) | Mar 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [1fc9174c06](https://linux-hardware.org/?probe=1fc9174c06) | Mar 11, 2023 |
| Dell          | Inspiron 5420               | Notebook    | [9e6843fe2e](https://linux-hardware.org/?probe=9e6843fe2e) | Mar 10, 2023 |
| Dell          | Inspiron 5420               | Notebook    | [77d13c9c12](https://linux-hardware.org/?probe=77d13c9c12) | Mar 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dd06fbb0f9](https://linux-hardware.org/?probe=dd06fbb0f9) | Mar 10, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [bdf01893f8](https://linux-hardware.org/?probe=bdf01893f8) | Mar 10, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [b46bb47333](https://linux-hardware.org/?probe=b46bb47333) | Mar 09, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [24444c6d30](https://linux-hardware.org/?probe=24444c6d30) | Mar 08, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [f500d72edd](https://linux-hardware.org/?probe=f500d72edd) | Mar 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [42e5be35d6](https://linux-hardware.org/?probe=42e5be35d6) | Mar 08, 2023 |
| HP            | 8055                        | Desktop     | [0b9ddd5940](https://linux-hardware.org/?probe=0b9ddd5940) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d15122995](https://linux-hardware.org/?probe=4d15122995) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc6e719e99](https://linux-hardware.org/?probe=cc6e719e99) | Mar 07, 2023 |
| Huanan        | X79-ZD3 INTEL (INTEL Xeo... | Desktop     | [0e00a19a03](https://linux-hardware.org/?probe=0e00a19a03) | Mar 07, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [676eaa7960](https://linux-hardware.org/?probe=676eaa7960) | Mar 06, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8f08518290](https://linux-hardware.org/?probe=8f08518290) | Mar 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [819f8b1cad](https://linux-hardware.org/?probe=819f8b1cad) | Mar 06, 2023 |
| Dell          | G7 7500                     | Notebook    | [d5abfa6d0d](https://linux-hardware.org/?probe=d5abfa6d0d) | Mar 06, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [a6c7741454](https://linux-hardware.org/?probe=a6c7741454) | Mar 06, 2023 |
| Dell          | G7 7500                     | Notebook    | [bfaad602b7](https://linux-hardware.org/?probe=bfaad602b7) | Mar 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8814af9b71](https://linux-hardware.org/?probe=8814af9b71) | Mar 05, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [e560390e4f](https://linux-hardware.org/?probe=e560390e4f) | Mar 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3d1560d3d1](https://linux-hardware.org/?probe=3d1560d3d1) | Mar 05, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c2f98c3014](https://linux-hardware.org/?probe=c2f98c3014) | Mar 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3e484b7bac](https://linux-hardware.org/?probe=3e484b7bac) | Mar 04, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f163816260](https://linux-hardware.org/?probe=f163816260) | Mar 04, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5523730c91](https://linux-hardware.org/?probe=5523730c91) | Mar 04, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [422fa2cf16](https://linux-hardware.org/?probe=422fa2cf16) | Mar 02, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f441cc82e4](https://linux-hardware.org/?probe=f441cc82e4) | Mar 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [edf5f00bf8](https://linux-hardware.org/?probe=edf5f00bf8) | Mar 01, 2023 |
| Sony          | VPCEH10EB                   | Notebook    | [9c8bb09559](https://linux-hardware.org/?probe=9c8bb09559) | Mar 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [eca37862f3](https://linux-hardware.org/?probe=eca37862f3) | Mar 01, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [ecdef0f6db](https://linux-hardware.org/?probe=ecdef0f6db) | Mar 01, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [6bd63e7974](https://linux-hardware.org/?probe=6bd63e7974) | Mar 01, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [4f2c05c854](https://linux-hardware.org/?probe=4f2c05c854) | Feb 28, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [db5b346bd5](https://linux-hardware.org/?probe=db5b346bd5) | Feb 28, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [166a6bbb4b](https://linux-hardware.org/?probe=166a6bbb4b) | Feb 28, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [dd74cb518b](https://linux-hardware.org/?probe=dd74cb518b) | Feb 27, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [677e93841e](https://linux-hardware.org/?probe=677e93841e) | Feb 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [068ad292bd](https://linux-hardware.org/?probe=068ad292bd) | Feb 27, 2023 |
| Gigabyte      | X99-UD4P-CF                 | Desktop     | [b78a53985a](https://linux-hardware.org/?probe=b78a53985a) | Feb 26, 2023 |
| MSI           | Z97-G43 GAMING              | Desktop     | [b13f16cb2f](https://linux-hardware.org/?probe=b13f16cb2f) | Feb 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [267da4138c](https://linux-hardware.org/?probe=267da4138c) | Feb 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [de7aec7f12](https://linux-hardware.org/?probe=de7aec7f12) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8a2a361aff](https://linux-hardware.org/?probe=8a2a361aff) | Feb 26, 2023 |
| Lenovo        | ThinkPad L470 20J4003WGE    | Notebook    | [42f6425b2d](https://linux-hardware.org/?probe=42f6425b2d) | Feb 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS35H02    | Notebook    | [a396e54378](https://linux-hardware.org/?probe=a396e54378) | Feb 25, 2023 |
| Gigabyte      | B85N PHOENIX                | Desktop     | [5fe00f35c4](https://linux-hardware.org/?probe=5fe00f35c4) | Feb 25, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [31bd9738ca](https://linux-hardware.org/?probe=31bd9738ca) | Feb 25, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [4066713adb](https://linux-hardware.org/?probe=4066713adb) | Feb 24, 2023 |
| Dell          | 0MM599                      | Desktop     | [00304aefe6](https://linux-hardware.org/?probe=00304aefe6) | Feb 24, 2023 |
| AZW           | GTR V02                     | Desktop     | [c8d4bfd6e3](https://linux-hardware.org/?probe=c8d4bfd6e3) | Feb 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 1951      | 91.25%  |
| ArcoLinux             | 139       | 6.5%    |
| ArcoLinux 20.6.5      | 11        | 0.51%   |
| ArcoLinux 20.7.5      | 8         | 0.37%   |
| ArcoLinux 20.3.4      | 4         | 0.19%   |
| ArcoLinux 20.3.3      | 3         | 0.14%   |
| ArcoLinux 20.2.12     | 3         | 0.14%   |
| ArcoLinux 19.12.15    | 3         | 0.14%   |
| ArcoLinux 19.07.11    | 3         | 0.14%   |
| ArcoLinux 20.1.4      | 2         | 0.09%   |
| ArcoLinux 19.02.4     | 2         | 0.09%   |
| ArcoLinux I3-v19.02.4 | 1         | 0.05%   |
| ArcoLinux 6.9.2       | 1         | 0.05%   |
| ArcoLinux 6.9.1       | 1         | 0.05%   |
| ArcoLinux 20.5.7      | 1         | 0.05%   |
| ArcoLinux 20.5.2      | 1         | 0.05%   |
| ArcoLinux 20.4.11     | 1         | 0.05%   |
| ArcoLinux 20.2.9      | 1         | 0.05%   |
| ArcoLinux 19.11.3     | 1         | 0.05%   |
| ArcoLinux 19.03.3     | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 2119      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.15.7-arch1-1  | 48        | 1.83%   |
| 6.4.12-arch1-1  | 39        | 1.48%   |
| 5.15.10-arch1-1 | 39        | 1.48%   |
| 5.13.13-arch1-1 | 38        | 1.45%   |
| 6.3.8-arch1-1   | 34        | 1.29%   |
| 6.3.9-arch1-1   | 29        | 1.1%    |
| 6.2.11-arch1-1  | 28        | 1.07%   |
| 6.3.2-arch1-1   | 26        | 0.99%   |
| 5.14.14-arch1-1 | 26        | 0.99%   |
| 5.16.11-arch1-1 | 25        | 0.95%   |
| 6.2.8-arch1-1   | 23        | 0.88%   |
| 5.13.12-arch1-1 | 22        | 0.84%   |
| 5.14.12-arch1-1 | 21        | 0.8%    |
| 6.4.10-arch1-1  | 20        | 0.76%   |
| 6.3.3-arch1-1   | 20        | 0.76%   |
| 6.1.12-arch1-1  | 20        | 0.76%   |
| 6.3.7-arch1-1   | 19        | 0.72%   |
| 5.17.1-arch1-1  | 18        | 0.68%   |
| 6.3.5-arch1-1   | 17        | 0.65%   |
| 5.8.14-arch1-1  | 16        | 0.61%   |
| 5.12.13-arch1-2 | 16        | 0.61%   |
| 6.4.11-arch2-1  | 15        | 0.57%   |
| 6.3.4-arch1-1   | 15        | 0.57%   |
| 5.9.14-arch1-1  | 15        | 0.57%   |
| 5.19.13-arch1-1 | 15        | 0.57%   |
| 5.16.2-arch1-1  | 15        | 0.57%   |
| 5.12.15-arch1-1 | 15        | 0.57%   |
| 6.4.8-arch1-1   | 14        | 0.53%   |
| 6.3.6-arch1-1   | 14        | 0.53%   |
| 6.3.1-arch2-1   | 14        | 0.53%   |
| 6.0.8-arch1-1   | 14        | 0.53%   |
| 5.15.5-arch1-1  | 14        | 0.53%   |
| 5.15.11-arch2-1 | 14        | 0.53%   |
| 6.3.1-arch1-1   | 13        | 0.49%   |
| 6.0.12-arch1-1  | 13        | 0.49%   |
| 5.9.8-arch1-1   | 13        | 0.49%   |
| 5.17.9-arch1-1  | 13        | 0.49%   |
| 5.15.4-arch1-1  | 13        | 0.49%   |
| 5.12.12-arch1-1 | 13        | 0.49%   |
| 6.4.3-arch1-1   | 12        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.7  | 59        | 2.25%   |
| 6.4.12  | 50        | 1.9%    |
| 6.3.8   | 50        | 1.9%    |
| 5.15.10 | 41        | 1.56%   |
| 5.13.13 | 38        | 1.45%   |
| 6.3.2   | 35        | 1.33%   |
| 6.3.9   | 33        | 1.26%   |
| 6.3.1   | 32        | 1.22%   |
| 6.2.11  | 31        | 1.18%   |
| 6.3.3   | 28        | 1.07%   |
| 6.1.12  | 28        | 1.07%   |
| 5.16.11 | 28        | 1.07%   |
| 6.2.8   | 26        | 0.99%   |
| 5.14.14 | 26        | 0.99%   |
| 6.4.11  | 25        | 0.95%   |
| 6.3.5   | 25        | 0.95%   |
| 6.0.2   | 25        | 0.95%   |
| 5.17.1  | 25        | 0.95%   |
| 6.4.2   | 24        | 0.91%   |
| 5.14.12 | 24        | 0.91%   |
| 5.13.12 | 24        | 0.91%   |
| 6.4.3   | 23        | 0.88%   |
| 6.4.10  | 22        | 0.84%   |
| 6.3.7   | 22        | 0.84%   |
| 6.3.4   | 22        | 0.84%   |
| 6.2.10  | 22        | 0.84%   |
| 6.4.7   | 20        | 0.76%   |
| 6.0.8   | 19        | 0.72%   |
| 5.9.14  | 19        | 0.72%   |
| 5.16.2  | 19        | 0.72%   |
| 6.4.8   | 18        | 0.69%   |
| 5.9.8   | 18        | 0.69%   |
| 5.17.5  | 18        | 0.69%   |
| 5.15.4  | 18        | 0.69%   |
| 5.12.15 | 18        | 0.69%   |
| 5.12.13 | 18        | 0.69%   |
| 6.4.1   | 17        | 0.65%   |
| 6.3.6   | 17        | 0.65%   |
| 5.8.14  | 17        | 0.65%   |
| 6.2.12  | 16        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15     | 301       | 12.02%  |
| 6.3      | 252       | 10.06%  |
| 6.1      | 214       | 8.54%   |
| 5.10     | 214       | 8.54%   |
| 6.4      | 207       | 8.26%   |
| 6.2      | 147       | 5.87%   |
| 5.16     | 132       | 5.27%   |
| 5.14     | 131       | 5.23%   |
| 6.0      | 122       | 4.87%   |
| 5.13     | 110       | 4.39%   |
| 5.9      | 109       | 4.35%   |
| 5.12     | 107       | 4.27%   |
| 5.17     | 92        | 3.67%   |
| 5.18     | 87        | 3.47%   |
| 5.11     | 77        | 3.07%   |
| 5.19     | 72        | 2.87%   |
| 5.4      | 60        | 2.4%    |
| 5.8      | 34        | 1.36%   |
| 5.6      | 7         | 0.28%   |
| 5.7      | 6         | 0.24%   |
| 5.5      | 5         | 0.2%    |
| 5.3      | 3         | 0.12%   |
| 5.0      | 3         | 0.12%   |
| 6.3.3    | 2         | 0.08%   |
| 5.15.96  | 2         | 0.08%   |
| 4.19     | 2         | 0.08%   |
| 6.3.0    | 1         | 0.04%   |
| 6.2.0    | 1         | 0.04%   |
| 5.2      | 1         | 0.04%   |
| 5.15.107 | 1         | 0.04%   |
| 4.20     | 1         | 0.04%   |
| 4.18     | 1         | 0.04%   |
| 4.17     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2119      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| XFCE           | 750       | 32.94%  |
| KDE5           | 453       | 19.89%  |
| i3             | 164       | 7.2%    |
| GNOME          | 149       | 6.54%   |
| awesome        | 115       | 5.05%   |
| qtile          | 78        | 3.43%   |
| X-Cinnamon     | 65        | 2.85%   |
| bspwm          | 64        | 2.81%   |
| xmonad         | 52        | 2.28%   |
| Hyprland       | 49        | 2.15%   |
| Cinnamon       | 48        | 2.11%   |
| DWM            | 44        | 1.93%   |
| LeftWM         | 31        | 1.36%   |
| Deepin         | 31        | 1.36%   |
| Unknown        | 27        | 1.19%   |
| KDE            | 25        | 1.1%    |
| Budgie         | 21        | 0.92%   |
| LXQt           | 19        | 0.83%   |
| chadwm         | 18        | 0.79%   |
| MATE           | 16        | 0.7%    |
| i3-with-shmlog | 12        | 0.53%   |
| herbstluftwm   | 12        | 0.53%   |
| sway           | 6         | 0.26%   |
| ICEWM          | 4         | 0.18%   |
| Cutefish       | 4         | 0.18%   |
| Unity          | 3         | 0.13%   |
| spectrwm       | 3         | 0.13%   |
| openbox        | 3         | 0.13%   |
| cwm            | 3         | 0.13%   |
| Hypr           | 2         | 0.09%   |
| dusk           | 2         | 0.09%   |
| river          | 1         | 0.04%   |
| jwm            | 1         | 0.04%   |
| GNOME Classic  | 1         | 0.04%   |
| dwm-sc         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1904      | 87.94%  |
| Wayland | 137       | 6.33%   |
| Tty     | 100       | 4.62%   |
| Unknown | 24        | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1321      | 58.76%  |
| LightDM | 383       | 17.04%  |
| TDM     | 295       | 13.12%  |
| Unknown | 181       | 8.05%   |
| GDM     | 54        | 2.4%    |
| Ly      | 8         | 0.36%   |
| LXDM    | 4         | 0.18%   |
| XDM     | 1         | 0.04%   |
| SLiM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1195      | 55.56%  |
| en_GB   | 177       | 8.23%   |
| de_DE   | 101       | 4.7%    |
| en_CA   | 72        | 3.35%   |
| en_IN   | 55        | 2.56%   |
| fr_FR   | 44        | 2.05%   |
| en_AU   | 43        | 2%      |
| C       | 42        | 1.95%   |
| ru_RU   | 41        | 1.91%   |
| pt_BR   | 35        | 1.63%   |
| es_ES   | 31        | 1.44%   |
| pl_PL   | 21        | 0.98%   |
| it_IT   | 21        | 0.98%   |
| es_MX   | 17        | 0.79%   |
| en_ZA   | 17        | 0.79%   |
| hu_HU   | 16        | 0.74%   |
| tr_TR   | 14        | 0.65%   |
| Unknown | 14        | 0.65%   |
| es_AR   | 13        | 0.6%    |
| sv_SE   | 12        | 0.56%   |
| nl_NL   | 9         | 0.42%   |
| zh_CN   | 8         | 0.37%   |
| en_IE   | 8         | 0.37%   |
| en_DK   | 8         | 0.37%   |
| fr_CA   | 7         | 0.33%   |
| en_PH   | 7         | 0.33%   |
| en_IL   | 7         | 0.33%   |
| ru_UA   | 6         | 0.28%   |
| pt_PT   | 6         | 0.28%   |
| ja_JP   | 6         | 0.28%   |
| fi_FI   | 6         | 0.28%   |
| nl_BE   | 5         | 0.23%   |
| en_SG   | 5         | 0.23%   |
| de_CH   | 5         | 0.23%   |
| da_DK   | 5         | 0.23%   |
| nb_NO   | 4         | 0.19%   |
| fr_BE   | 4         | 0.19%   |
| es_CO   | 4         | 0.19%   |
| es_CL   | 4         | 0.19%   |
| en_AG   | 4         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1582      | 73.89%  |
| BIOS | 559       | 26.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1552      | 71.32%  |
| Btrfs    | 465       | 21.37%  |
| Overlay  | 105       | 4.83%   |
| Xfs      | 27        | 1.24%   |
| F2fs     | 14        | 0.64%   |
| Unknown  | 8         | 0.37%   |
| Reiserfs | 2         | 0.09%   |
| Jfs      | 2         | 0.09%   |
| Tmpfs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1683      | 78.28%  |
| MBR     | 298       | 13.86%  |
| Unknown | 169       | 7.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1623      | 73.87%  |
| Yes       | 574       | 26.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1266      | 58.88%  |
| Yes       | 884       | 41.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 428       | 20.2%   |
| Lenovo              | 355       | 16.75%  |
| Hewlett-Packard     | 238       | 11.23%  |
| Dell                | 232       | 10.95%  |
| Gigabyte Technology | 172       | 8.12%   |
| MSI                 | 165       | 7.79%   |
| ASRock              | 84        | 3.96%   |
| Acer                | 84        | 3.96%   |
| Apple               | 50        | 2.36%   |
| Toshiba             | 24        | 1.13%   |
| Intel               | 23        | 1.09%   |
| Unknown             | 22        | 1.04%   |
| Supermicro          | 18        | 0.85%   |
| Samsung Electronics | 13        | 0.61%   |
| Sony                | 12        | 0.57%   |
| HUAWEI              | 12        | 0.57%   |
| System76            | 11        | 0.52%   |
| Fujitsu             | 11        | 0.52%   |
| Medion              | 10        | 0.47%   |
| Razer               | 9         | 0.42%   |
| AZW                 | 9         | 0.42%   |
| Alienware           | 9         | 0.42%   |
| TUXEDO              | 7         | 0.33%   |
| Timi                | 7         | 0.33%   |
| Notebook            | 7         | 0.33%   |
| Chuwi               | 6         | 0.28%   |
| Pegatron            | 4         | 0.19%   |
| Packard Bell        | 4         | 0.19%   |
| Microsoft           | 4         | 0.19%   |
| Google              | 4         | 0.19%   |
| Foxconn             | 4         | 0.19%   |
| Biostar             | 4         | 0.19%   |
| BESSTAR Tech        | 4         | 0.19%   |
| ZOTAC               | 3         | 0.14%   |
| Schenker            | 3         | 0.14%   |
| Monster             | 3         | 0.14%   |
| LG Electronics      | 3         | 0.14%   |
| Huanan              | 3         | 0.14%   |
| Casper              | 3         | 0.14%   |
| Teclast             | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 27        | 1.27%   |
| ASUS TUF Gaming X570-PLUS        | 19        | 0.9%    |
| ASUS All Series                  | 18        | 0.85%   |
| ASUS ROG STRIX B550-F GAMING     | 12        | 0.57%   |
| Supermicro SYS-5019A-FTN4        | 10        | 0.47%   |
| MSI MS-7C37                      | 10        | 0.47%   |
| ASUS PRIME X570-P                | 10        | 0.47%   |
| MSI MS-7C91                      | 8         | 0.38%   |
| HP Pavilion Notebook             | 8         | 0.38%   |
| ASUS PRIME X470-PRO              | 8         | 0.38%   |
| MSI MS-7C02                      | 7         | 0.33%   |
| MSI MS-7B89                      | 7         | 0.33%   |
| MSI MS-7B79                      | 7         | 0.33%   |
| ASUS PRIME A320M-K               | 7         | 0.33%   |
| HP Notebook                      | 6         | 0.28%   |
| Gigabyte X570 AORUS MASTER       | 6         | 0.28%   |
| Gigabyte X570 AORUS ELITE        | 6         | 0.28%   |
| Dell OptiPlex 7010               | 6         | 0.28%   |
| ASRock B450M Pro4                | 6         | 0.28%   |
| MSI MS-7C95                      | 5         | 0.24%   |
| MSI MS-7A38                      | 5         | 0.24%   |
| MSI MS-7971                      | 5         | 0.24%   |
| HP Laptop 15s-eq2xxx             | 5         | 0.24%   |
| Gigabyte X570 AORUS PRO WIFI     | 5         | 0.24%   |
| Gigabyte B450 AORUS ELITE        | 5         | 0.24%   |
| Dell OptiPlex 9020               | 5         | 0.24%   |
| Dell OptiPlex 9010               | 5         | 0.24%   |
| AZW SER                          | 5         | 0.24%   |
| ASUS ROG CROSSHAIR VIII HERO     | 5         | 0.24%   |
| ASUS PRIME B450M-A               | 5         | 0.24%   |
| ASUS M5A78L-M/USB3               | 5         | 0.24%   |
| Razer Blade                      | 4         | 0.19%   |
| MSI MS-7C56                      | 4         | 0.19%   |
| MSI MS-7B98                      | 4         | 0.19%   |
| MSI MS-7B86                      | 4         | 0.19%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ | 4         | 0.19%   |
| Intel H61                        | 4         | 0.19%   |
| HUAWEI KLVL-WXX9                 | 4         | 0.19%   |
| HP ProDesk 600 G1 SFF            | 4         | 0.19%   |
| HP Laptop 15-da0xxx              | 4         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 169       | 7.98%   |
| ASUS ROG                  | 79        | 3.73%   |
| ASUS PRIME                | 78        | 3.68%   |
| Lenovo IdeaPad            | 70        | 3.3%    |
| Dell Inspiron             | 69        | 3.26%   |
| Dell Latitude             | 53        | 2.5%    |
| ASUS TUF                  | 52        | 2.45%   |
| Acer Aspire               | 51        | 2.41%   |
| HP Pavilion               | 46        | 2.17%   |
| Dell OptiPlex             | 35        | 1.65%   |
| ASUS VivoBook             | 32        | 1.51%   |
| Lenovo Legion             | 31        | 1.46%   |
| HP Laptop                 | 31        | 1.46%   |
| Dell XPS                  | 31        | 1.46%   |
| Unknown                   | 27        | 1.27%   |
| HP EliteBook              | 26        | 1.23%   |
| Gigabyte X570             | 24        | 1.13%   |
| Toshiba Satellite         | 20        | 0.94%   |
| HP ENVY                   | 20        | 0.94%   |
| Dell Precision            | 18        | 0.85%   |
| ASUS All                  | 18        | 0.85%   |
| Lenovo Yoga               | 16        | 0.76%   |
| Lenovo ThinkCentre        | 15        | 0.71%   |
| Gigabyte B450M            | 13        | 0.61%   |
| Dell Vostro               | 12        | 0.57%   |
| Acer Nitro                | 12        | 0.57%   |
| HP OMEN                   | 11        | 0.52%   |
| HP EliteDesk              | 11        | 0.52%   |
| Gigabyte B450             | 11        | 0.52%   |
| ASRock B450M              | 11        | 0.52%   |
| Supermicro SYS-5019A-FTN4 | 10        | 0.47%   |
| MSI MS-7C37               | 10        | 0.47%   |
| HP Compaq                 | 10        | 0.47%   |
| Razer Blade               | 9         | 0.42%   |
| HP ZBook                  | 9         | 0.42%   |
| HP ProDesk                | 9         | 0.42%   |
| HP ProBook                | 9         | 0.42%   |
| ASUS ZenBook              | 9         | 0.42%   |
| ASUS P8Z77-V              | 9         | 0.42%   |
| MSI MS-7C91               | 8         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 284       | 13.4%   |
| 2020    | 276       | 13.03%  |
| 2018    | 264       | 12.46%  |
| 2021    | 182       | 8.59%   |
| 2017    | 178       | 8.4%    |
| 2016    | 129       | 6.09%   |
| 2013    | 128       | 6.04%   |
| 2012    | 123       | 5.8%    |
| 2015    | 112       | 5.29%   |
| 2011    | 110       | 5.19%   |
| 2014    | 98        | 4.62%   |
| 2022    | 75        | 3.54%   |
| 2010    | 70        | 3.3%    |
| 2009    | 27        | 1.27%   |
| 2008    | 26        | 1.23%   |
| 2023    | 17        | 0.8%    |
| 2007    | 11        | 0.52%   |
| 2006    | 6         | 0.28%   |
| 2005    | 1         | 0.05%   |
| 2004    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1083      | 51.11%  |
| Desktop     | 921       | 43.46%  |
| Convertible | 46        | 2.17%   |
| Mini pc     | 32        | 1.51%   |
| All in one  | 22        | 1.04%   |
| Tablet      | 8         | 0.38%   |
| Server      | 6         | 0.28%   |
| Stick pc    | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2117      | 99.91%  |
| Enabled  | 2         | 0.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2110      | 99.58%  |
| Yes  | 9         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 580       | 27.01%  |
| 4.01-8.0        | 478       | 22.26%  |
| 8.01-16.0       | 372       | 17.33%  |
| 32.01-64.0      | 348       | 16.21%  |
| 3.01-4.0        | 185       | 8.62%   |
| 64.01-256.0     | 95        | 4.42%   |
| 24.01-32.0      | 56        | 2.61%   |
| 1.01-2.0        | 22        | 1.02%   |
| 2.01-3.0        | 9         | 0.42%   |
| More than 256.0 | 1         | 0.05%   |
| Unknown         | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 732       | 30.34%  |
| 2.01-3.0   | 598       | 24.78%  |
| 4.01-8.0   | 385       | 15.96%  |
| 3.01-4.0   | 360       | 14.92%  |
| 0.51-1.0   | 188       | 7.79%   |
| 8.01-16.0  | 108       | 4.48%   |
| 0.01-0.5   | 28        | 1.16%   |
| 16.01-24.0 | 12        | 0.5%    |
| 24.01-32.0 | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1014      | 46.03%  |
| 2      | 635       | 28.82%  |
| 3      | 265       | 12.03%  |
| 4      | 151       | 6.85%   |
| 5      | 73        | 3.31%   |
| 6      | 30        | 1.36%   |
| 7      | 15        | 0.68%   |
| 0      | 6         | 0.27%   |
| 9      | 5         | 0.23%   |
| 11     | 3         | 0.14%   |
| 8      | 3         | 0.14%   |
| 21     | 1         | 0.05%   |
| 19     | 1         | 0.05%   |
| 10     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1588      | 74.52%  |
| Yes       | 543       | 25.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1869      | 87.79%  |
| No        | 260       | 12.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1609      | 75.61%  |
| No        | 519       | 24.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1468      | 68.31%  |
| No        | 681       | 31.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 474       | 22.22%  |
| Germany      | 160       | 7.5%    |
| UK           | 124       | 5.81%   |
| Canada       | 97        | 4.55%   |
| India        | 82        | 3.84%   |
| Brazil       | 71        | 3.33%   |
| France       | 65        | 3.05%   |
| Russia       | 54        | 2.53%   |
| Spain        | 52        | 2.44%   |
| Belgium      | 48        | 2.25%   |
| Australia    | 47        | 2.2%    |
| Netherlands  | 43        | 2.02%   |
| Italy        | 42        | 1.97%   |
| Poland       | 41        | 1.92%   |
| Turkey       | 40        | 1.88%   |
| Sweden       | 40        | 1.88%   |
| Mexico       | 29        | 1.36%   |
| Hungary      | 26        | 1.22%   |
| Argentina    | 25        | 1.17%   |
| Switzerland  | 24        | 1.13%   |
| Romania      | 23        | 1.08%   |
| Norway       | 22        | 1.03%   |
| Finland      | 20        | 0.94%   |
| Ukraine      | 19        | 0.89%   |
| Indonesia    | 19        | 0.89%   |
| South Africa | 18        | 0.84%   |
| Portugal     | 18        | 0.84%   |
| Greece       | 17        | 0.8%    |
| Bulgaria     | 17        | 0.8%    |
| Austria      | 16        | 0.75%   |
| Czechia      | 15        | 0.7%    |
| Denmark      | 14        | 0.66%   |
| Malaysia     | 12        | 0.56%   |
| Japan        | 12        | 0.56%   |
| Ireland      | 12        | 0.56%   |
| Colombia     | 12        | 0.56%   |
| China        | 12        | 0.56%   |
| Bangladesh   | 12        | 0.56%   |
| Egypt        | 11        | 0.52%   |
| Serbia       | 10        | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sydney            | 22        | 0.97%   |
| Berlin            | 20        | 0.88%   |
| Durham            | 17        | 0.75%   |
| Istanbul          | 15        | 0.66%   |
| Toronto           | 14        | 0.62%   |
| Madrid            | 14        | 0.62%   |
| Paris             | 13        | 0.57%   |
| Warsaw            | 12        | 0.53%   |
| New York          | 12        | 0.53%   |
| Moscow            | 12        | 0.53%   |
| Vienna            | 11        | 0.49%   |
| Lier              | 11        | 0.49%   |
| Houston           | 11        | 0.49%   |
| Helsinki          | 11        | 0.49%   |
| Stockholm         | 10        | 0.44%   |
| Sao Paulo         | 10        | 0.44%   |
| Pune              | 10        | 0.44%   |
| London            | 10        | 0.44%   |
| Budapest          | 10        | 0.44%   |
| Atlanta           | 10        | 0.44%   |
| Amsterdam         | 10        | 0.44%   |
| Portland          | 9         | 0.4%    |
| Frankfurt am Main | 9         | 0.4%    |
| Sofia             | 8         | 0.35%   |
| Rio de Janeiro    | 8         | 0.35%   |
| Oslo              | 8         | 0.35%   |
| Melbourne         | 8         | 0.35%   |
| Chicago           | 8         | 0.35%   |
| Brooklyn          | 8         | 0.35%   |
| Brisbane          | 8         | 0.35%   |
| Bengaluru         | 8         | 0.35%   |
| Athens            | 8         | 0.35%   |
| Zurich            | 7         | 0.31%   |
| Wilrijk           | 7         | 0.31%   |
| St Petersburg     | 7         | 0.31%   |
| Spokane           | 7         | 0.31%   |
| Singapore         | 7         | 0.31%   |
| Montevideo        | 7         | 0.31%   |
| Milan             | 7         | 0.31%   |
| Hamburg           | 7         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 700       | 1212   | 19.05%  |
| WDC                         | 547       | 919    | 14.88%  |
| Seagate                     | 469       | 722    | 12.76%  |
| Toshiba                     | 214       | 273    | 5.82%   |
| SanDisk                     | 204       | 255    | 5.55%   |
| Kingston                    | 192       | 280    | 5.22%   |
| Crucial                     | 150       | 217    | 4.08%   |
| SK hynix                    | 98        | 126    | 2.67%   |
| Intel                       | 97        | 142    | 2.64%   |
| Hitachi                     | 74        | 86     | 2.01%   |
| Unknown                     | 71        | 104    | 1.93%   |
| A-DATA Technology           | 58        | 73     | 1.58%   |
| Phison Electronics          | 45        | 61     | 1.22%   |
| HGST                        | 45        | 60     | 1.22%   |
| Micron Technology           | 44        | 52     | 1.2%    |
| Micron/Crucial Technology   | 35        | 47     | 0.95%   |
| PNY                         | 32        | 46     | 0.87%   |
| Apple                       | 31        | 47     | 0.84%   |
| Silicon Motion              | 28        | 33     | 0.76%   |
| Phison                      | 28        | 45     | 0.76%   |
| KIOXIA                      | 27        | 32     | 0.73%   |
| Kingston Technology Company | 24        | 32     | 0.65%   |
| SPCC                        | 23        | 29     | 0.63%   |
| China                       | 23        | 39     | 0.63%   |
| JMicron Technology          | 22        | 25     | 0.6%    |
| Corsair                     | 19        | 37     | 0.52%   |
| LITEON                      | 16        | 21     | 0.44%   |
| Patriot                     | 14        | 24     | 0.38%   |
| SABRENT                     | 13        | 15     | 0.35%   |
| Hewlett-Packard             | 13        | 17     | 0.35%   |
| Transcend                   | 12        | 16     | 0.33%   |
| Realtek Semiconductor       | 12        | 14     | 0.33%   |
| OCZ                         | 12        | 15     | 0.33%   |
| Gigabyte Technology         | 12        | 16     | 0.33%   |
| ADATA Technology            | 12        | 13     | 0.33%   |
| LITEONIT                    | 11        | 11     | 0.3%    |
| Intenso                     | 11        | 17     | 0.3%    |
| XPG                         | 10        | 13     | 0.27%   |
| Plextor                     | 10        | 10     | 0.27%   |
| ASMT                        | 8         | 12     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 99        | 2.36%   |
| Samsung SSD 860 EVO 500GB                             | 55        | 1.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 46        | 1.1%    |
| Kingston SA400S37240G 240GB SSD                       | 46        | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB                        | 43        | 1.02%   |
| Samsung SSD 850 EVO 250GB                             | 40        | 0.95%   |
| Crucial CT1000MX500SSD1 1TB                           | 34        | 0.81%   |
| Toshiba MQ01ABD100 1TB                                | 30        | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB                        | 30        | 0.71%   |
| Samsung SSD 860 EVO 1TB                               | 30        | 0.71%   |
| Samsung SSD 850 EVO 500GB                             | 28        | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 26        | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB                        | 26        | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 25        | 0.6%    |
| Kingston SA400S37480G 480GB SSD                       | 25        | 0.6%    |
| Samsung SSD 860 EVO 250GB                             | 24        | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 24        | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB                        | 23        | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB                          | 23        | 0.55%   |
| Toshiba MQ04ABF100 1TB                                | 22        | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 21        | 0.5%    |
| Kingston SA400S37120G 120GB SSD                       | 21        | 0.5%    |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 20        | 0.48%   |
| Unknown SD/MMC/MS PRO 1GB                             | 19        | 0.45%   |
| Samsung SSD 870 EVO 1TB                               | 19        | 0.45%   |
| Crucial CT500MX500SSD1 500GB                          | 19        | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB                        | 18        | 0.43%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 18        | 0.43%   |
| Crucial CT240BX500SSD1 240GB                          | 17        | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 16        | 0.38%   |
| Seagate Expansion 2TB                                 | 16        | 0.38%   |
| Phison E12 NVMe Controller 256GB                      | 16        | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 15        | 0.36%   |
| Toshiba HDWD110 1TB                                   | 15        | 0.36%   |
| Toshiba DT01ACA100 1TB                                | 15        | 0.36%   |
| Samsung SSD 970 EVO 1TB                               | 15        | 0.36%   |
| JMicron Generic 1TB                                   | 15        | 0.36%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 14        | 0.33%   |
| Seagate ST1000DM003-1ER162 1TB                        | 14        | 0.33%   |
| Samsung SSD 980 1TB                                   | 14        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 455       | 690    | 36.69%  |
| WDC                 | 389       | 662    | 31.37%  |
| Toshiba             | 151       | 197    | 12.18%  |
| Hitachi             | 74        | 86     | 5.97%   |
| HGST                | 44        | 58     | 3.55%   |
| Samsung Electronics | 43        | 63     | 3.47%   |
| Unknown             | 21        | 29     | 1.69%   |
| Apple               | 9         | 17     | 0.73%   |
| SABRENT             | 8         | 10     | 0.65%   |
| Maxtor              | 5         | 7      | 0.4%    |
| External            | 5         | 9      | 0.4%    |
| SSK                 | 4         | 4      | 0.32%   |
| Hewlett-Packard     | 4         | 5      | 0.32%   |
| ASMT                | 4         | 8      | 0.32%   |
| USB3.0              | 2         | 3      | 0.16%   |
| LaCie               | 2         | 2      | 0.16%   |
| Intenso             | 2         | 2      | 0.16%   |
| Fujitsu             | 2         | 2      | 0.16%   |
| Fantom              | 2         | 5      | 0.16%   |
| ASMedia             | 2         | 3      | 0.16%   |
| WD MediaMax         | 1         | 1      | 0.08%   |
| RSH-319             | 1         | 1      | 0.08%   |
| PHD 3.0             | 1         | 1      | 0.08%   |
| Maxone              | 1         | 1      | 0.08%   |
| KESU                | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 3      | 0.08%   |
| Inateck             | 1         | 1      | 0.08%   |
| HGST HUS            | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| H/W                 | 1         | 9      | 0.08%   |
| ExcelStor           | 1         | 2      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 374       | 605    | 27.42%  |
| Kingston            | 154       | 215    | 11.29%  |
| Crucial             | 133       | 186    | 9.75%   |
| WDC                 | 116       | 163    | 8.5%    |
| SanDisk             | 109       | 130    | 7.99%   |
| A-DATA Technology   | 40        | 53     | 2.93%   |
| PNY                 | 31        | 42     | 2.27%   |
| SK hynix            | 30        | 46     | 2.2%    |
| Toshiba             | 24        | 31     | 1.76%   |
| Intel               | 24        | 32     | 1.76%   |
| China               | 23        | 39     | 1.69%   |
| Apple               | 20        | 22     | 1.47%   |
| SPCC                | 19        | 23     | 1.39%   |
| Micron Technology   | 19        | 23     | 1.39%   |
| JMicron Technology  | 15        | 15     | 1.1%    |
| Patriot             | 14        | 24     | 1.03%   |
| LITEON              | 13        | 18     | 0.95%   |
| OCZ                 | 12        | 15     | 0.88%   |
| Transcend           | 11        | 15     | 0.81%   |
| LITEONIT            | 11        | 11     | 0.81%   |
| Intenso             | 9         | 15     | 0.66%   |
| Plextor             | 8         | 8      | 0.59%   |
| Corsair             | 8         | 18     | 0.59%   |
| Team                | 7         | 8      | 0.51%   |
| Hewlett-Packard     | 7         | 10     | 0.51%   |
| Seagate             | 6         | 9      | 0.44%   |
| GOODRAM             | 6         | 10     | 0.44%   |
| Gigabyte Technology | 6         | 7      | 0.44%   |
| TO Exter            | 5         | 5      | 0.37%   |
| Mushkin             | 5         | 8      | 0.37%   |
| KingSpec            | 5         | 5      | 0.37%   |
| Verbatim            | 4         | 5      | 0.29%   |
| Lexar               | 4         | 4      | 0.29%   |
| ASMT                | 4         | 4      | 0.29%   |
| Unknown             | 4         | 4      | 0.29%   |
| Unknown             | 3         | 3      | 0.22%   |
| Leven               | 3         | 3      | 0.22%   |
| HS-SSD-C100         | 3         | 4      | 0.22%   |
| Apacer              | 3         | 3      | 0.22%   |
| Acer                | 3         | 3      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1105      | 1930   | 34.6%   |
| HDD     | 1022      | 1885   | 32%     |
| NVMe    | 986       | 1543   | 30.87%  |
| MMC     | 47        | 68     | 1.47%   |
| Unknown | 34        | 48     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1579      | 3541   | 56.09%  |
| NVMe | 986       | 1538   | 35.03%  |
| SAS  | 203       | 327    | 7.21%   |
| MMC  | 47        | 68     | 1.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1110      | 1918   | 48.03%  |
| 0.51-1.0   | 781       | 1156   | 33.79%  |
| 1.01-2.0   | 260       | 454    | 11.25%  |
| 3.01-4.0   | 67        | 118    | 2.9%    |
| 4.01-10.0  | 47        | 95     | 2.03%   |
| 2.01-3.0   | 41        | 65     | 1.77%   |
| 10.01-20.0 | 5         | 9      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 470       | 20.68%  |
| 251-500        | 457       | 20.11%  |
| 501-1000       | 362       | 15.93%  |
| More than 3000 | 282       | 12.41%  |
| 1001-2000      | 278       | 12.23%  |
| 2001-3000      | 104       | 4.58%   |
| Unknown        | 98        | 4.31%   |
| 1-20           | 96        | 4.22%   |
| 51-100         | 88        | 3.87%   |
| 21-50          | 38        | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 584       | 24.53%  |
| 21-50          | 424       | 17.81%  |
| 101-250        | 364       | 15.29%  |
| 51-100         | 265       | 11.13%  |
| 251-500        | 230       | 9.66%   |
| 501-1000       | 189       | 7.94%   |
| 1001-2000      | 113       | 4.75%   |
| Unknown        | 98        | 4.12%   |
| More than 3000 | 66        | 2.77%   |
| 2001-3000      | 46        | 1.93%   |
| 0              | 2         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 11        | 11     | 2.46%   |
| Toshiba MQ01ABD100 1TB                                          | 10        | 13     | 2.24%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 8         | 9      | 1.79%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 8         | 11     | 1.79%   |
| Toshiba MQ01ABF050 500GB                                        | 6         | 6      | 1.34%   |
| Seagate ST3500413AS 500GB                                       | 6         | 7      | 1.34%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 6         | 8      | 1.34%   |
| Seagate ST9320325AS 320GB                                       | 5         | 6      | 1.12%   |
| Seagate ST31000528AS 1TB                                        | 5         | 5      | 1.12%   |
| Hitachi HTS547575A9E384 752GB                                   | 5         | 5      | 1.12%   |
| Seagate ST500LT012-1DG142 500GB                                 | 4         | 4      | 0.89%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 4         | 8      | 0.89%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 4         | 4      | 0.89%   |
| SanDisk SSD PLUS 1000GB                                         | 4         | 4      | 0.89%   |
| Hitachi HDS721010CLA332 1TB                                     | 4         | 5      | 0.89%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 3         | 7      | 0.67%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                            | 3         | 3      | 0.67%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 3         | 3      | 0.67%   |
| Seagate ST3500312CS 500GB                                       | 3         | 5      | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 3         | 6      | 0.67%   |
| Seagate ST1000LM014-1EJ164 1TB                                  | 3         | 3      | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 3         | 3      | 0.67%   |
| Samsung Electronics SSD 850 EVO 250GB                           | 3         | 4      | 0.67%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 3      | 0.67%   |
| Maxtor STM3250310AS 250GB                                       | 3         | 4      | 0.67%   |
| Hitachi HDS721050CLA662 500GB                                   | 3         | 4      | 0.67%   |
| WDC WDS500G1X0E-00AFY0 500GB                                    | 2         | 2      | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 2         | 2      | 0.45%   |
| WDC WD6400AAKS-22A7B2 640GB                                     | 2         | 3      | 0.45%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 2         | 2      | 0.45%   |
| WDC WD5000AAKX-603CA0 500GB                                     | 2         | 6      | 0.45%   |
| WDC WD5000AAKX-00ERMA0 500GB                                    | 2         | 2      | 0.45%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 2         | 3      | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB                                        | 2         | 6      | 0.45%   |
| WDC WD3200AVJS-63B6A0 320GB                                     | 2         | 5      | 0.45%   |
| WDC WD3200AAJS-00L7A0 320GB                                     | 2         | 2      | 0.45%   |
| WDC WD20EFRX-68EUZN0 2TB                                        | 2         | 3      | 0.45%   |
| WDC WD20EARX-00PASB0 2TB                                        | 2         | 2      | 0.45%   |
| WDC WD2002FAEX-007BA0 2TB                                       | 2         | 2      | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 2         | 2      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 114       | 143    | 26.76%  |
| WDC                       | 102       | 162    | 23.94%  |
| Samsung Electronics       | 36        | 50     | 8.45%   |
| Toshiba                   | 33        | 41     | 7.75%   |
| Hitachi                   | 27        | 31     | 6.34%   |
| HGST                      | 12        | 16     | 2.82%   |
| SanDisk                   | 11        | 11     | 2.58%   |
| Kingston                  | 11        | 15     | 2.58%   |
| Intel                     | 11        | 17     | 2.58%   |
| SK hynix                  | 8         | 9      | 1.88%   |
| Crucial                   | 8         | 8      | 1.88%   |
| Micron Technology         | 5         | 8      | 1.17%   |
| Maxtor                    | 4         | 6      | 0.94%   |
| Corsair                   | 4         | 14     | 0.94%   |
| A-DATA Technology         | 4         | 4      | 0.94%   |
| Transcend                 | 3         | 3      | 0.7%    |
| Hewlett-Packard           | 3         | 3      | 0.7%    |
| Micron/Crucial Technology | 2         | 4      | 0.47%   |
| LITEONIT                  | 2         | 2      | 0.47%   |
| Drevo                     | 2         | 2      | 0.47%   |
| China                     | 2         | 3      | 0.47%   |
| ASMedia                   | 2         | 3      | 0.47%   |
| Apple                     | 2         | 2      | 0.47%   |
| Unknown                   | 2         | 2      | 0.47%   |
| XPG                       | 1         | 1      | 0.23%   |
| USB3.0                    | 1         | 2      | 0.23%   |
| Team                      | 1         | 1      | 0.23%   |
| SSSTC                     | 1         | 1      | 0.23%   |
| SPCC                      | 1         | 1      | 0.23%   |
| Realtek Semiconductor     | 1         | 1      | 0.23%   |
| Plextor                   | 1         | 1      | 0.23%   |
| Patriot                   | 1         | 1      | 0.23%   |
| Mushkin                   | 1         | 1      | 0.23%   |
| Lenovo                    | 1         | 1      | 0.23%   |
| LaCie                     | 1         | 1      | 0.23%   |
| JMicron Technology        | 1         | 1      | 0.23%   |
| Inateck                   | 1         | 1      | 0.23%   |
| HS-SSD-C100               | 1         | 1      | 0.23%   |
| HGST HTS                  | 1         | 1      | 0.23%   |
| Colorful                  | 1         | 1      | 0.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 114       | 143    | 37.13%  |
| WDC                 | 98        | 155    | 31.92%  |
| Toshiba             | 30        | 38     | 9.77%   |
| Hitachi             | 27        | 31     | 8.79%   |
| HGST                | 12        | 16     | 3.91%   |
| Samsung Electronics | 11        | 13     | 3.58%   |
| Maxtor              | 4         | 6      | 1.3%    |
| Hewlett-Packard     | 2         | 2      | 0.65%   |
| ASMedia             | 2         | 3      | 0.65%   |
| Apple               | 2         | 2      | 0.65%   |
| USB3.0              | 1         | 2      | 0.33%   |
| LaCie               | 1         | 1      | 0.33%   |
| Inateck             | 1         | 1      | 0.33%   |
| HGST HTS            | 1         | 1      | 0.33%   |
| Unknown             | 1         | 1      | 0.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 285       | 415    | 70.54%  |
| SSD  | 95        | 127    | 23.51%  |
| NVMe | 24        | 34     | 5.94%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB                      | 1         | 1      | 9.09%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 9.09%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 9.09%   |
| Seagate ST32000641AS 2TB                         | 1         | 2      | 9.09%   |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 9.09%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 9.09%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 9.09%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 36.36%  |
| Samsung Electronics | 3         | 3      | 27.27%  |
| WDC                 | 2         | 2      | 18.18%  |
| HGST                | 2         | 2      | 18.18%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1774      | 4137   | 68.89%  |
| Detected | 399       | 749    | 15.5%   |
| Malfunc  | 391       | 576    | 15.18%  |
| Failed   | 11        | 12     | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1326      | 43.25%  |
| AMD                              | 557       | 18.17%  |
| Samsung Electronics              | 392       | 12.79%  |
| SanDisk                          | 164       | 5.35%   |
| Phison Electronics               | 91        | 2.97%   |
| SK hynix                         | 69        | 2.25%   |
| Kingston Technology Company      | 68        | 2.22%   |
| Micron/Crucial Technology        | 54        | 1.76%   |
| ASMedia Technology               | 54        | 1.76%   |
| Toshiba America Info Systems     | 36        | 1.17%   |
| Silicon Motion                   | 34        | 1.11%   |
| Marvell Technology Group         | 32        | 1.04%   |
| KIOXIA                           | 32        | 1.04%   |
| ADATA Technology                 | 30        | 0.98%   |
| Micron Technology                | 27        | 0.88%   |
| Realtek Semiconductor            | 19        | 0.62%   |
| Nvidia                           | 16        | 0.52%   |
| Seagate Technology               | 10        | 0.33%   |
| Union Memory (Shenzhen)          | 8         | 0.26%   |
| Lite-On Technology               | 7         | 0.23%   |
| JMicron Technology               | 7         | 0.23%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.16%   |
| Lenovo                           | 3         | 0.1%    |
| Apple                            | 3         | 0.1%    |
| VIA Technologies                 | 2         | 0.07%   |
| Silicon Image                    | 2         | 0.07%   |
| Shenzhen Longsys Electronics     | 2         | 0.07%   |
| Netac Technology                 | 2         | 0.07%   |
| LSI Logic / Symbios Logic        | 2         | 0.07%   |
| INNOGRIT                         | 2         | 0.07%   |
| Broadcom / LSI                   | 2         | 0.07%   |
| Adaptec                          | 2         | 0.07%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| TenaFe                           | 1         | 0.03%   |
| Solid State Storage Technology   | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 407       | 11.91%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 212       | 6.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 124       | 3.63%   |
| AMD 400 Series Chipset SATA Controller                                         | 121       | 3.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 94        | 2.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 85        | 2.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 74        | 2.17%   |
| AMD 500 Series Chipset SATA Controller                                         | 73        | 2.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 67        | 1.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 66        | 1.93%   |
| Samsung NVMe SSD Controller 980                                                | 64        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 61        | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 60        | 1.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 54        | 1.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 52        | 1.52%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 52        | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 49        | 1.43%   |
| Phison E12 NVMe Controller                                                     | 46        | 1.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 45        | 1.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 43        | 1.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 42        | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 37        | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 36        | 1.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 35        | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                            | 35        | 1.02%   |
| Intel SATA Controller [RAID mode]                                              | 34        | 1%      |
| Intel SSD 660P Series                                                          | 33        | 0.97%   |
| Phison E16 PCIe4 NVMe Controller                                               | 30        | 0.88%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 30        | 0.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 30        | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                          | 29        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 29        | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 28        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 28        | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 26        | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 25        | 0.73%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 25        | 0.73%   |
| Kingston Company A2000 NVMe SSD                                                | 24        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 24        | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 22        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1664      | 56.45%  |
| NVMe | 987       | 33.48%  |
| RAID | 176       | 5.97%   |
| IDE  | 115       | 3.9%    |
| SAS  | 4         | 0.14%   |
| SCSI | 2         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1462      | 68.99%  |
| AMD     | 656       | 30.96%  |
| Unknown | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 38        | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 30        | 1.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 27        | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 27        | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 25        | 1.18%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 24        | 1.13%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 23        | 1.08%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 23        | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 22        | 1.04%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 22        | 1.04%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 22        | 1.04%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 21        | 0.99%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 20        | 0.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 19        | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 18        | 0.85%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 18        | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 17        | 0.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz           | 17        | 0.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 17        | 0.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 16        | 0.75%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 16        | 0.75%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 16        | 0.75%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 16        | 0.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 15        | 0.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 15        | 0.71%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 14        | 0.66%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 13        | 0.61%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 13        | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 13        | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 13        | 0.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 12        | 0.56%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 12        | 0.56%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 12        | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 12        | 0.56%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 12        | 0.56%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 12        | 0.56%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 12        | 0.56%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 12        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 11        | 0.52%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 11        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 502       | 23.63%  |
| Intel Core i7           | 476       | 22.41%  |
| AMD Ryzen 5             | 212       | 9.98%   |
| AMD Ryzen 7             | 185       | 8.71%   |
| Other                   | 126       | 5.93%   |
| Intel Core i3           | 116       | 5.46%   |
| AMD Ryzen 9             | 83        | 3.91%   |
| Intel Xeon              | 49        | 2.31%   |
| Intel Celeron           | 47        | 2.21%   |
| AMD Ryzen 3             | 44        | 2.07%   |
| Intel Pentium           | 43        | 2.02%   |
| Intel Core 2 Duo        | 28        | 1.32%   |
| Intel Core i9           | 27        | 1.27%   |
| Intel Atom              | 23        | 1.08%   |
| AMD FX                  | 23        | 1.08%   |
| AMD A6                  | 15        | 0.71%   |
| AMD A10                 | 12        | 0.56%   |
| AMD Ryzen 7 PRO         | 10        | 0.47%   |
| Intel Pentium Dual-Core | 7         | 0.33%   |
| AMD Phenom II X4        | 7         | 0.33%   |
| AMD A8                  | 7         | 0.33%   |
| AMD A4                  | 7         | 0.33%   |
| AMD Ryzen Threadripper  | 6         | 0.28%   |
| AMD A12                 | 6         | 0.28%   |
| Intel Pentium Silver    | 5         | 0.24%   |
| Intel Pentium Dual      | 5         | 0.24%   |
| Intel Core 2 Quad       | 5         | 0.24%   |
| AMD Ryzen 5 PRO         | 5         | 0.24%   |
| Intel Core 2            | 4         | 0.19%   |
| AMD Athlon 64 X2        | 4         | 0.19%   |
| AMD Athlon              | 4         | 0.19%   |
| Intel Xeon Silver       | 3         | 0.14%   |
| Intel Core m3           | 3         | 0.14%   |
| AMD E2                  | 3         | 0.14%   |
| AMD E1                  | 3         | 0.14%   |
| AMD Athlon II X2        | 3         | 0.14%   |
| Intel Pentium Gold      | 2         | 0.09%   |
| Intel Genuine           | 2         | 0.09%   |
| AMD Phenom II X6        | 2         | 0.09%   |
| Intel Pentium 4         | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 748       | 35.2%   |
| 2       | 607       | 28.56%  |
| 6       | 349       | 16.42%  |
| 8       | 271       | 12.75%  |
| 12      | 61        | 2.87%   |
| 16      | 27        | 1.27%   |
| 10      | 19        | 0.89%   |
| 1       | 13        | 0.61%   |
| 3       | 11        | 0.52%   |
| 14      | 10        | 0.47%   |
| 24      | 4         | 0.19%   |
| 18      | 2         | 0.09%   |
| 40      | 1         | 0.05%   |
| 32      | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2114      | 99.72%  |
| 2       | 5         | 0.24%   |
| Unknown | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1674      | 78.93%  |
| 1       | 446       | 21.03%  |
| Unknown | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2112      | 99.67%  |
| Unknown        | 7         | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 547       | 24.81%  |
| 0x306c3    | 95        | 4.31%   |
| 0x906ea    | 91        | 4.13%   |
| 0x306a9    | 88        | 3.99%   |
| 0x206a7    | 79        | 3.58%   |
| 0x08701021 | 76        | 3.45%   |
| 0x906e9    | 60        | 2.72%   |
| 0x806ea    | 51        | 2.31%   |
| 0x806e9    | 49        | 2.22%   |
| 0x506e3    | 48        | 2.18%   |
| 0x0a50000c | 45        | 2.04%   |
| 0x0800820d | 45        | 2.04%   |
| 0x406e3    | 43        | 1.95%   |
| 0x0a201016 | 38        | 1.72%   |
| 0x08108109 | 36        | 1.63%   |
| 0x806ec    | 35        | 1.59%   |
| 0x40651    | 34        | 1.54%   |
| 0x08600106 | 34        | 1.54%   |
| 0x806c1    | 33        | 1.5%    |
| 0x306d4    | 29        | 1.32%   |
| 0x08701013 | 25        | 1.13%   |
| 0xa0652    | 24        | 1.09%   |
| 0x08108102 | 24        | 1.09%   |
| 0x20655    | 23        | 1.04%   |
| 0x1067a    | 22        | 1%      |
| 0x0a201009 | 22        | 1%      |
| 0x08608103 | 22        | 1%      |
| 0x0a50000d | 19        | 0.86%   |
| 0x706e5    | 15        | 0.68%   |
| 0xa0655    | 14        | 0.63%   |
| 0x08101016 | 13        | 0.59%   |
| 0x806eb    | 12        | 0.54%   |
| 0x806d1    | 12        | 0.54%   |
| 0x106e5    | 12        | 0.54%   |
| 0x0810100b | 12        | 0.54%   |
| 0xa0653    | 11        | 0.5%    |
| 0x30678    | 11        | 0.5%    |
| 0x0a20120a | 11        | 0.5%    |
| 0x08600104 | 11        | 0.5%    |
| 0x08600103 | 11        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 446       | 20.98%  |
| Haswell          | 188       | 8.84%   |
| Zen 2            | 175       | 8.23%   |
| Zen 3            | 163       | 7.67%   |
| IvyBridge        | 143       | 6.73%   |
| Skylake          | 132       | 6.21%   |
| Zen+             | 119       | 5.6%    |
| SandyBridge      | 113       | 5.32%   |
| CometLake        | 67        | 3.15%   |
| TigerLake        | 51        | 2.4%    |
| Zen              | 49        | 2.3%    |
| Unknown          | 48        | 2.26%   |
| Broadwell        | 47        | 2.21%   |
| Westmere         | 45        | 2.12%   |
| Icelake          | 40        | 1.88%   |
| Alderlake Hybrid | 39        | 1.83%   |
| Penryn           | 35        | 1.65%   |
| Silvermont       | 34        | 1.6%    |
| Excavator        | 33        | 1.55%   |
| Piledriver       | 30        | 1.41%   |
| Goldmont plus    | 20        | 0.94%   |
| Goldmont         | 19        | 0.89%   |
| Nehalem          | 17        | 0.8%    |
| K10              | 17        | 0.8%    |
| Core             | 16        | 0.75%   |
| Steamroller      | 8         | 0.38%   |
| K8 Hammer        | 6         | 0.28%   |
| Puma             | 5         | 0.24%   |
| Jaguar           | 5         | 0.24%   |
| Tremont          | 4         | 0.19%   |
| Bulldozer        | 3         | 0.14%   |
| Bonnell          | 3         | 0.14%   |
| K10 Llano        | 2         | 0.09%   |
| Bobcat           | 2         | 0.09%   |
| NetBurst         | 1         | 0.05%   |
| K8 & K10 hybrid  | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1101      | 42.54%  |
| Nvidia                     | 854       | 33%     |
| AMD                        | 615       | 23.76%  |
| ASPEED Technology          | 15        | 0.58%   |
| Matrox Electronics Systems | 2         | 0.08%   |
| ATI Technologies           | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 86        | 3.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 78        | 2.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 68        | 2.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 67        | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 66        | 2.49%   |
| Intel HD Graphics 620                                                                    | 62        | 2.34%   |
| Intel UHD Graphics 620                                                                   | 59        | 2.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 58        | 2.19%   |
| AMD Renoir                                                                               | 54        | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 51        | 1.93%   |
| Intel HD Graphics 630                                                                    | 49        | 1.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 46        | 1.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 45        | 1.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 43        | 1.62%   |
| Intel HD Graphics 530                                                                    | 39        | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 38        | 1.44%   |
| Intel HD Graphics 5500                                                                   | 37        | 1.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 36        | 1.36%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 33        | 1.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 33        | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 32        | 1.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 1.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 29        | 1.1%    |
| AMD Lucienne                                                                             | 28        | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 27        | 1.02%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 26        | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 24        | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 23        | 0.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 22        | 0.83%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 21        | 0.79%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 20        | 0.76%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 19        | 0.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 19        | 0.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 17        | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 0.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 16        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 16        | 0.6%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 16        | 0.6%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 16        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 683       | 31.93%  |
| 1 x AMD        | 486       | 22.72%  |
| 1 x Nvidia     | 467       | 21.83%  |
| Intel + Nvidia | 339       | 15.85%  |
| Intel + AMD    | 49        | 2.29%   |
| AMD + Nvidia   | 47        | 2.2%    |
| 2 x AMD        | 36        | 1.68%   |
| 1 x ASPEED     | 14        | 0.65%   |
| 2 x Intel      | 8         | 0.37%   |
| 2 x Nvidia     | 4         | 0.19%   |
| Other          | 3         | 0.14%   |
| 1 x Matrox     | 2         | 0.09%   |
| AMD + ASPEED   | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1506      | 70.14%  |
| Proprietary | 589       | 27.43%  |
| Unknown     | 52        | 2.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1091      | 50.28%  |
| 1.01-2.0   | 207       | 9.54%   |
| 7.01-8.0   | 195       | 8.99%   |
| 0.01-0.5   | 183       | 8.43%   |
| 3.01-4.0   | 173       | 7.97%   |
| 5.01-6.0   | 98        | 4.52%   |
| 8.01-16.0  | 94        | 4.33%   |
| 0.51-1.0   | 92        | 4.24%   |
| 2.01-3.0   | 26        | 1.2%    |
| 16.01-24.0 | 8         | 0.37%   |
| 4.01-5.0   | 3         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 281       | 11.28%  |
| AU Optronics            | 235       | 9.43%   |
| LG Display              | 220       | 8.83%   |
| BOE                     | 195       | 7.83%   |
| Chimei Innolux          | 193       | 7.74%   |
| Dell                    | 186       | 7.46%   |
| Goldstar                | 170       | 6.82%   |
| Acer                    | 96        | 3.85%   |
| AOC                     | 78        | 3.13%   |
| BenQ                    | 75        | 3.01%   |
| Ancor Communications    | 74        | 2.97%   |
| Hewlett-Packard         | 73        | 2.93%   |
| Sharp                   | 46        | 1.85%   |
| Philips                 | 42        | 1.69%   |
| Apple                   | 40        | 1.61%   |
| ASUSTek Computer        | 36        | 1.44%   |
| Lenovo                  | 34        | 1.36%   |
| ViewSonic               | 32        | 1.28%   |
| PANDA                   | 27        | 1.08%   |
| Sony                    | 25        | 1%      |
| MSI                     | 23        | 0.92%   |
| Iiyama                  | 22        | 0.88%   |
| Chi Mei Optoelectronics | 18        | 0.72%   |
| Eizo                    | 16        | 0.64%   |
| CSO                     | 16        | 0.64%   |
| Unknown                 | 13        | 0.52%   |
| Vizio                   | 12        | 0.48%   |
| Sceptre Tech            | 12        | 0.48%   |
| LG Electronics          | 12        | 0.48%   |
| InfoVision              | 11        | 0.44%   |
| Panasonic               | 10        | 0.4%    |
| Toshiba                 | 9         | 0.36%   |
| Gigabyte Technology     | 9         | 0.36%   |
| Unknown                 | 9         | 0.36%   |
| HannStar                | 8         | 0.32%   |
| Vestel Elektronik       | 5         | 0.2%    |
| VIE                     | 4         | 0.16%   |
| MStar                   | 4         | 0.16%   |
| Microstep               | 4         | 0.16%   |
| Insignia                | 4         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 14        | 0.54%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 12        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 12        | 0.46%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 10        | 0.39%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 9         | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9         | 0.35%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 9         | 0.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.35%   |
| Unknown                                                               | 9         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 8         | 0.31%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 8         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 8         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 8         | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 8         | 0.31%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 7         | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.27%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 7         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 7         | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 7         | 0.27%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 7         | 0.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 6         | 0.23%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 6         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 6         | 0.23%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 6         | 0.23%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 6         | 0.23%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 6         | 0.23%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6         | 0.23%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                         | 5         | 0.19%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 5         | 0.19%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 5         | 0.19%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.19%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 5         | 0.19%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 5         | 0.19%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 5         | 0.19%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5         | 0.19%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 5         | 0.19%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1153      | 49.13%  |
| 1366x768 (WXGA)    | 321       | 13.68%  |
| 2560x1440 (QHD)    | 198       | 8.44%   |
| 3840x2160 (4K)     | 168       | 7.16%   |
| 1600x900 (HD+)     | 69        | 2.94%   |
| 2560x1080          | 48        | 2.05%   |
| 1920x1200 (WUXGA)  | 43        | 1.83%   |
| 1680x1050 (WSXGA+) | 42        | 1.79%   |
| 1440x900 (WXGA+)   | 40        | 1.7%    |
| 1280x1024 (SXGA)   | 36        | 1.53%   |
| 3440x1440          | 34        | 1.45%   |
| 1280x800 (WXGA)    | 28        | 1.19%   |
| Unknown            | 20        | 0.85%   |
| 3840x1080          | 19        | 0.81%   |
| 2880x1800          | 17        | 0.72%   |
| 1360x768           | 16        | 0.68%   |
| 2560x1600          | 15        | 0.64%   |
| 2160x1440          | 10        | 0.43%   |
| 1920x540           | 10        | 0.43%   |
| 1600x1200          | 7         | 0.3%    |
| 3840x2400          | 6         | 0.26%   |
| 3200x1800 (QHD+)   | 6         | 0.26%   |
| 3840x1600          | 5         | 0.21%   |
| 2288x1287          | 4         | 0.17%   |
| 2944x1080          | 2         | 0.09%   |
| 2160x1350          | 2         | 0.09%   |
| 2048x1152          | 2         | 0.09%   |
| 1024x768 (XGA)     | 2         | 0.09%   |
| 1024x600           | 2         | 0.09%   |
| 7280x1440          | 1         | 0.04%   |
| 6400x1440          | 1         | 0.04%   |
| 5760x2160          | 1         | 0.04%   |
| 5520x1080          | 1         | 0.04%   |
| 5360x1440          | 1         | 0.04%   |
| 480x1920           | 1         | 0.04%   |
| 4480x1080          | 1         | 0.04%   |
| 4096x2160          | 1         | 0.04%   |
| 3840x2524          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3840x1100          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 567       | 22.86%  |
| 27      | 258       | 10.4%   |
| 24      | 219       | 8.83%   |
| 14      | 183       | 7.38%   |
| 13      | 170       | 6.85%   |
| 23      | 167       | 6.73%   |
| 21      | 153       | 6.17%   |
| 17      | 124       | 5%      |
| 31      | 94        | 3.79%   |
| Unknown | 84        | 3.39%   |
| 34      | 68        | 2.74%   |
| 12      | 44        | 1.77%   |
| 19      | 42        | 1.69%   |
| 18      | 40        | 1.61%   |
| 22      | 32        | 1.29%   |
| 20      | 21        | 0.85%   |
| 84      | 19        | 0.77%   |
| 72      | 18        | 0.73%   |
| 40      | 17        | 0.69%   |
| 32      | 17        | 0.69%   |
| 54      | 16        | 0.65%   |
| 16      | 16        | 0.65%   |
| 28      | 11        | 0.44%   |
| 25      | 11        | 0.44%   |
| 11      | 10        | 0.4%    |
| 26      | 9         | 0.36%   |
| 48      | 8         | 0.32%   |
| 52      | 5         | 0.2%    |
| 49      | 5         | 0.2%    |
| 39      | 5         | 0.2%    |
| 29      | 5         | 0.2%    |
| 10      | 5         | 0.2%    |
| 65      | 4         | 0.16%   |
| 43      | 4         | 0.16%   |
| 42      | 4         | 0.16%   |
| 37      | 4         | 0.16%   |
| 35      | 4         | 0.16%   |
| 142     | 3         | 0.12%   |
| 46      | 3         | 0.12%   |
| 74      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 845       | 34.96%  |
| 501-600        | 589       | 24.37%  |
| 401-500        | 262       | 10.84%  |
| 201-300        | 153       | 6.33%   |
| 601-700        | 136       | 5.63%   |
| 351-400        | 134       | 5.54%   |
| 701-800        | 88        | 3.64%   |
| Unknown        | 84        | 3.48%   |
| 1001-1500      | 43        | 1.78%   |
| 1501-2000      | 39        | 1.61%   |
| 801-900        | 32        | 1.32%   |
| 901-1000       | 9         | 0.37%   |
| More than 2000 | 3         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1733      | 79.2%   |
| 16/10   | 206       | 9.41%   |
| 21/9    | 87        | 3.98%   |
| Unknown | 67        | 3.06%   |
| 5/4     | 34        | 1.55%   |
| 3/2     | 22        | 1.01%   |
| 4/3     | 17        | 0.78%   |
| 32/9    | 10        | 0.46%   |
| 6/5     | 5         | 0.23%   |
| 1.00    | 3         | 0.14%   |
| 3.40    | 1         | 0.05%   |
| 2.00    | 1         | 0.05%   |
| 0.80    | 1         | 0.05%   |
| 0.25    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 559       | 22.8%   |
| 201-250        | 471       | 19.21%  |
| 81-90          | 285       | 11.62%  |
| 301-350        | 264       | 10.77%  |
| 351-500        | 189       | 7.71%   |
| 121-130        | 99        | 4.04%   |
| 151-200        | 95        | 3.87%   |
| Unknown        | 84        | 3.43%   |
| 251-300        | 78        | 3.18%   |
| More than 1000 | 72        | 2.94%   |
| 71-80          | 67        | 2.73%   |
| 141-150        | 53        | 2.16%   |
| 501-1000       | 48        | 1.96%   |
| 61-70          | 40        | 1.63%   |
| 111-120        | 13        | 0.53%   |
| 51-60          | 12        | 0.49%   |
| 131-140        | 10        | 0.41%   |
| 91-100         | 9         | 0.37%   |
| 41-50          | 4         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 788       | 33.59%  |
| 121-160       | 666       | 28.39%  |
| 101-120       | 569       | 24.25%  |
| 161-240       | 131       | 5.58%   |
| Unknown       | 84        | 3.58%   |
| 1-50          | 57        | 2.43%   |
| More than 240 | 51        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1588      | 73.21%  |
| 2     | 459       | 21.16%  |
| 0     | 63        | 2.9%    |
| 3     | 55        | 2.54%   |
| 4     | 4         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1200      | 38.38%  |
| Intel                             | 1184      | 37.86%  |
| Qualcomm Atheros                  | 304       | 9.72%   |
| Broadcom                          | 112       | 3.58%   |
| MediaTek                          | 43        | 1.38%   |
| TP-Link                           | 28        | 0.9%    |
| Ralink Technology                 | 28        | 0.9%    |
| Broadcom Limited                  | 24        | 0.77%   |
| Marvell Technology Group          | 14        | 0.45%   |
| Nvidia                            | 13        | 0.42%   |
| ASIX Electronics                  | 13        | 0.42%   |
| Sierra Wireless                   | 11        | 0.35%   |
| Ralink                            | 11        | 0.35%   |
| Microsoft                         | 11        | 0.35%   |
| Samsung Electronics               | 9         | 0.29%   |
| DisplayLink                       | 8         | 0.26%   |
| Dell                              | 8         | 0.26%   |
| Aquantia                          | 8         | 0.26%   |
| Qualcomm                          | 7         | 0.22%   |
| Ericsson Business Mobile Networks | 7         | 0.22%   |
| D-Link System                     | 7         | 0.22%   |
| Qualcomm Atheros Communications   | 5         | 0.16%   |
| Lenovo                            | 5         | 0.16%   |
| Huawei Technologies               | 5         | 0.16%   |
| Xiaomi                            | 4         | 0.13%   |
| NetGear                           | 4         | 0.13%   |
| Insyde Software                   | 4         | 0.13%   |
| Hewlett-Packard                   | 4         | 0.13%   |
| Fibocom                           | 4         | 0.13%   |
| T & A Mobile Phones               | 3         | 0.1%    |
| JMicron Technology                | 3         | 0.1%    |
| D-Link                            | 3         | 0.1%    |
| Oculus VR                         | 2         | 0.06%   |
| Motorola PCS                      | 2         | 0.06%   |
| Emulex                            | 2         | 0.06%   |
| ASUSTek Computer                  | 2         | 0.06%   |
| vivo                              | 1         | 0.03%   |
| VIA Technologies                  | 1         | 0.03%   |
| U-Blox                            | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 880       | 23.48%  |
| Intel Wi-Fi 6 AX200                                               | 178       | 4.75%   |
| Intel I211 Gigabit Network Connection                             | 104       | 2.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 97        | 2.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73        | 1.95%   |
| Intel Wireless 8265 / 8275                                        | 72        | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 71        | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 70        | 1.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 59        | 1.57%   |
| Intel Wireless 7260                                               | 57        | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 55        | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 55        | 1.47%   |
| Intel Ethernet Connection (2) I219-V                              | 53        | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 47        | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 46        | 1.23%   |
| Intel Wireless 8260                                               | 45        | 1.2%    |
| Intel Ethernet Controller I225-V                                  | 45        | 1.2%    |
| Intel Wireless 7265                                               | 43        | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 40        | 1.07%   |
| Intel Wireless-AC 9260                                            | 38        | 1.01%   |
| Intel Wi-Fi 6 AX201                                               | 37        | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 37        | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 37        | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 36        | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 35        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 34        | 0.91%   |
| Intel Wireless 3165                                               | 34        | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 33        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 22        | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 22        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.51%   |
| Intel Wireless 3160                                               | 19        | 0.51%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 19        | 0.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 18        | 0.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 18        | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 17        | 0.45%   |
| Intel Ethernet Connection I219-LM                                 | 17        | 0.45%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 907       | 53.92%  |
| Realtek Semiconductor                 | 269       | 15.99%  |
| Qualcomm Atheros                      | 238       | 14.15%  |
| Broadcom                              | 81        | 4.82%   |
| MediaTek                              | 43        | 2.56%   |
| Ralink Technology                     | 28        | 1.66%   |
| TP-Link                               | 25        | 1.49%   |
| Broadcom Limited                      | 18        | 1.07%   |
| Sierra Wireless                       | 11        | 0.65%   |
| Ralink                                | 11        | 0.65%   |
| Microsoft                             | 11        | 0.65%   |
| Qualcomm Atheros Communications       | 5         | 0.3%    |
| NetGear                               | 4         | 0.24%   |
| Fibocom                               | 4         | 0.24%   |
| Dell                                  | 4         | 0.24%   |
| D-Link System                         | 4         | 0.24%   |
| Marvell Technology Group              | 3         | 0.18%   |
| D-Link                                | 3         | 0.18%   |
| Hewlett-Packard                       | 2         | 0.12%   |
| Ericsson Business Mobile Networks     | 2         | 0.12%   |
| ASUSTek Computer                      | 2         | 0.12%   |
| Xiaomi                                | 1         | 0.06%   |
| Tenda                                 | 1         | 0.06%   |
| Ovislink                              | 1         | 0.06%   |
| IMC Networks                          | 1         | 0.06%   |
| Edimax Technology                     | 1         | 0.06%   |
| CyberTAN Technology                   | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 178       | 10.52%  |
| Intel Wireless 8265 / 8275                                     | 72        | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 70        | 4.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 59        | 3.49%   |
| Intel Wireless 7260                                            | 57        | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 55        | 3.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 47        | 2.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 46        | 2.72%   |
| Intel Wireless 8260                                            | 45        | 2.66%   |
| Intel Wireless 7265                                            | 43        | 2.54%   |
| Intel Wireless-AC 9260                                         | 38        | 2.25%   |
| Intel Wi-Fi 6 AX201                                            | 37        | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 37        | 2.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 36        | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 35        | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 34        | 2.01%   |
| Intel Wireless 3165                                            | 34        | 2.01%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 33        | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 23        | 1.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 22        | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 22        | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.12%   |
| Intel Wireless 3160                                            | 19        | 1.12%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 19        | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 18        | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 18        | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 17        | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 16        | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 16        | 0.95%   |
| Intel Centrino Ultimate-N 6300                                 | 16        | 0.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 0.89%   |
| Ralink MT7601U Wireless Adapter                                | 14        | 0.83%   |
| Intel Centrino Advanced-N 6200                                 | 14        | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 13        | 0.77%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 13        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 13        | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 12        | 0.71%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 12        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1100      | 55.61%  |
| Intel                                  | 618       | 31.24%  |
| Qualcomm Atheros                       | 93        | 4.7%    |
| Broadcom                               | 51        | 2.58%   |
| Nvidia                                 | 13        | 0.66%   |
| ASIX Electronics                       | 13        | 0.66%   |
| Marvell Technology Group               | 11        | 0.56%   |
| Samsung Electronics                    | 9         | 0.46%   |
| DisplayLink                            | 8         | 0.4%    |
| Aquantia                               | 8         | 0.4%    |
| Qualcomm                               | 7         | 0.35%   |
| Broadcom Limited                       | 6         | 0.3%    |
| Lenovo                                 | 4         | 0.2%    |
| Insyde Software                        | 4         | 0.2%    |
| Xiaomi                                 | 3         | 0.15%   |
| TP-Link                                | 3         | 0.15%   |
| T & A Mobile Phones                    | 3         | 0.15%   |
| JMicron Technology                     | 3         | 0.15%   |
| Huawei Technologies                    | 3         | 0.15%   |
| D-Link System                          | 3         | 0.15%   |
| Motorola PCS                           | 2         | 0.1%    |
| Emulex                                 | 2         | 0.1%    |
| VIA Technologies                       | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Solarflare Communications              | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.05%   |
| Novatel Wireless                       | 1         | 0.05%   |
| Mellanox Technologies                  | 1         | 0.05%   |
| MediaTek                               | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| Google                                 | 1         | 0.05%   |
| Apple                                  | 1         | 0.05%   |
| 3Com                                   | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 880       | 43.33%  |
| Intel I211 Gigabit Network Connection                             | 104       | 5.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 97        | 4.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73        | 3.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 71        | 3.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 55        | 2.71%   |
| Intel Ethernet Connection (2) I219-V                              | 53        | 2.61%   |
| Intel Ethernet Controller I225-V                                  | 45        | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 40        | 1.97%   |
| Intel Ethernet Connection (7) I219-V                              | 37        | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.98%   |
| Intel Ethernet Connection I219-LM                                 | 17        | 0.84%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 16        | 0.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.74%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 0.74%   |
| Intel 82577LM Gigabit Network Connection                          | 15        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 12        | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.54%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.49%   |
| Intel Ethernet Connection X553 1GbE                               | 10        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 9         | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 9         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.39%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.39%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.39%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 8         | 0.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 7         | 0.34%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.3%    |
| Intel Ethernet Connection (12) I219-V                             | 6         | 0.3%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1864      | 53.29%  |
| WiFi     | 1609      | 46%     |
| Modem    | 23        | 0.66%   |
| Unknown  | 2         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1203      | 53.95%  |
| Ethernet | 1027      | 46.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1193      | 56.04%  |
| 1     | 835       | 39.22%  |
| 3     | 66        | 3.1%    |
| 4     | 20        | 0.94%   |
| 0     | 12        | 0.56%   |
| 5     | 2         | 0.09%   |
| 9     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1625      | 74.99%  |
| Yes  | 542       | 25.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 782       | 52.52%  |
| Realtek Semiconductor           | 155       | 10.41%  |
| Qualcomm Atheros Communications | 105       | 7.05%   |
| Cambridge Silicon Radio         | 94        | 6.31%   |
| IMC Networks                    | 67        | 4.5%    |
| Broadcom                        | 55        | 3.69%   |
| Apple                           | 51        | 3.43%   |
| ASUSTek Computer                | 40        | 2.69%   |
| Lite-On Technology              | 38        | 2.55%   |
| Foxconn / Hon Hai               | 32        | 2.15%   |
| MediaTek                        | 16        | 1.07%   |
| Dell                            | 9         | 0.6%    |
| Toshiba                         | 6         | 0.4%    |
| Realtek                         | 6         | 0.4%    |
| TP-Link                         | 5         | 0.34%   |
| Belkin Components               | 4         | 0.27%   |
| Ralink                          | 3         | 0.2%    |
| Hewlett-Packard                 | 3         | 0.2%    |
| Edimax Technology               | 3         | 0.2%    |
| Dynex                           | 3         | 0.2%    |
| Ralink Technology               | 2         | 0.13%   |
| Marvell Semiconductor           | 2         | 0.13%   |
| HTC (High Tech Computer)        | 2         | 0.13%   |
| Actions                         | 2         | 0.13%   |
| SINO WEALTH                     | 1         | 0.07%   |
| Opticis                         | 1         | 0.07%   |
| Creative Technology             | 1         | 0.07%   |
| Chicony Electronics             | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 261       | 17.51%  |
| Intel AX200 Bluetooth                                 | 172       | 11.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 105       | 7.04%   |
| Intel AX201 Bluetooth                                 | 102       | 6.84%   |
| Realtek Bluetooth Radio                               | 98        | 6.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 94        | 6.3%    |
| Qualcomm Atheros  Bluetooth Device                    | 68        | 4.56%   |
| Intel Bluetooth Device                                | 60        | 4.02%   |
| Realtek  Bluetooth 4.2 Adapter                        | 40        | 2.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 39        | 2.62%   |
| Apple Bluetooth Host Controller                       | 28        | 1.88%   |
| IMC Networks Bluetooth Radio                          | 21        | 1.41%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 19        | 1.27%   |
| IMC Networks Bluetooth Device                         | 19        | 1.27%   |
| Broadcom BCM2045B (BDC-2.1)                           | 18        | 1.21%   |
| Apple Bluetooth USB Host Controller                   | 17        | 1.14%   |
| IMC Networks Wireless_Device                          | 16        | 1.07%   |
| MediaTek Wireless_Device                              | 15        | 1.01%   |
| Intel AX210 Bluetooth                                 | 15        | 1.01%   |
| Lite-On Bluetooth Device                              | 14        | 0.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 14        | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 13        | 0.87%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 13        | 0.87%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 13        | 0.87%   |
| ASUS ASUS USB-BT500                                   | 13        | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 12        | 0.8%    |
| Realtek RTL8821A Bluetooth                            | 10        | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 9         | 0.6%    |
| Foxconn / Hon Hai Bluetooth Device                    | 9         | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 8         | 0.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 6         | 0.4%    |
| Realtek 802.11ac WLAN Adapter                         | 6         | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                      | 6         | 0.4%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 6         | 0.4%    |
| TP-Link UB5A Adapter                                  | 5         | 0.34%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 5         | 0.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4         | 0.27%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 4         | 0.27%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 4         | 0.27%   |
| ASUS BCM20702A0                                       | 4         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1418      | 42.29%  |
| AMD                                  | 765       | 22.82%  |
| Nvidia                               | 686       | 20.46%  |
| C-Media Electronics                  | 71        | 2.12%   |
| Logitech                             | 50        | 1.49%   |
| Texas Instruments                    | 28        | 0.84%   |
| Kingston Technology                  | 26        | 0.78%   |
| Focusrite-Novation                   | 20        | 0.6%    |
| Razer USA                            | 19        | 0.57%   |
| JMTek                                | 19        | 0.57%   |
| Corsair                              | 14        | 0.42%   |
| Realtek Semiconductor                | 12        | 0.36%   |
| Creative Technology                  | 12        | 0.36%   |
| ASUSTek Computer                     | 12        | 0.36%   |
| SteelSeries ApS                      | 11        | 0.33%   |
| Generalplus Technology               | 10        | 0.3%    |
| Creative Labs                        | 10        | 0.3%    |
| GN Netcom                            | 8         | 0.24%   |
| Samson Technologies                  | 7         | 0.21%   |
| RODE Microphones                     | 7         | 0.21%   |
| BEHRINGER International              | 7         | 0.21%   |
| SAVITECH                             | 6         | 0.18%   |
| DSEA A/S                             | 6         | 0.18%   |
| Yamaha                               | 5         | 0.15%   |
| XMOS                                 | 5         | 0.15%   |
| Sony                                 | 5         | 0.15%   |
| Lenovo                               | 5         | 0.15%   |
| Blue Microphones                     | 5         | 0.15%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.12%   |
| PreSonus Audio Electronics           | 4         | 0.12%   |
| Plantronics                          | 4         | 0.12%   |
| VIA Technologies                     | 3         | 0.09%   |
| Native Instruments                   | 3         | 0.09%   |
| Mark of the Unicorn                  | 3         | 0.09%   |
| Hewlett-Packard                      | 3         | 0.09%   |
| FIFINE Microphones                   | 3         | 0.09%   |
| Audio-Technica                       | 3         | 0.09%   |
| Astro Gaming                         | 3         | 0.09%   |
| Asahi Kasei Microsystems             | 3         | 0.09%   |
| Turtle Beach                         | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 271       | 6.79%   |
| AMD Starship/Matisse HD Audio Controller                                   | 194       | 4.86%   |
| Intel Sunrise Point-LP HD Audio                                            | 185       | 4.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 134       | 3.36%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 134       | 3.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 132       | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 112       | 2.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 111       | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 82        | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 80        | 2.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 79        | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 78        | 1.96%   |
| Intel 200 Series PCH HD Audio                                              | 67        | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 67        | 1.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 60        | 1.5%    |
| Nvidia TU116 High Definition Audio Controller                              | 57        | 1.43%   |
| Nvidia TU106 High Definition Audio Controller                              | 55        | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 55        | 1.38%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 55        | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 52        | 1.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 51        | 1.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 51        | 1.28%   |
| Nvidia GP104 High Definition Audio Controller                              | 49        | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 46        | 1.15%   |
| Intel 8 Series HD Audio Controller                                         | 46        | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 44        | 1.1%    |
| Intel Broadwell-U Audio Controller                                         | 44        | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 43        | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 41        | 1.03%   |
| Nvidia GA104 High Definition Audio Controller                              | 37        | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 37        | 0.93%   |
| AMD Navi 10 HDMI Audio                                                     | 36        | 0.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 35        | 0.88%   |
| Nvidia TU104 HD Audio Controller                                           | 34        | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 33        | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                               | 32        | 0.8%    |
| AMD FCH Azalia Controller                                                  | 31        | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                              | 27        | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 25        | 0.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 25        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 482       | 20.83%  |
| SK hynix            | 387       | 16.72%  |
| Kingston            | 243       | 10.5%   |
| Micron Technology   | 224       | 9.68%   |
| Corsair             | 219       | 9.46%   |
| Crucial             | 177       | 7.65%   |
| G.Skill             | 134       | 5.79%   |
| Unknown             | 126       | 5.45%   |
| A-DATA Technology   | 45        | 1.94%   |
| Ramaxel Technology  | 37        | 1.6%    |
| Team                | 32        | 1.38%   |
| Nanya Technology    | 23        | 0.99%   |
| Elpida              | 20        | 0.86%   |
| Patriot             | 17        | 0.73%   |
| Unknown (ABCD)      | 12        | 0.52%   |
| Unknown             | 11        | 0.48%   |
| GOODRAM             | 10        | 0.43%   |
| Avant               | 7         | 0.3%    |
| Apacer              | 7         | 0.3%    |
| Silicon Power       | 6         | 0.26%   |
| Transcend           | 5         | 0.22%   |
| PNY                 | 5         | 0.22%   |
| Neo Forza           | 5         | 0.22%   |
| Goldkey             | 5         | 0.22%   |
| ASint Technology    | 5         | 0.22%   |
| Timetec             | 4         | 0.17%   |
| Smart               | 4         | 0.17%   |
| Kingmax             | 3         | 0.13%   |
| CSX                 | 3         | 0.13%   |
| AMD                 | 3         | 0.13%   |
| Unknown (0x0B5E)    | 2         | 0.09%   |
| Unifosa             | 2         | 0.09%   |
| Teikon              | 2         | 0.09%   |
| Sesame              | 2         | 0.09%   |
| Lexar               | 2         | 0.09%   |
| Golden Empire       | 2         | 0.09%   |
| GeIL                | 2         | 0.09%   |
| Wodposit            | 1         | 0.04%   |
| V-Color             | 1         | 0.04%   |
| Unknown (8AF1)      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 24        | 0.96%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 23        | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.92%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 21        | 0.84%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 20        | 0.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.76%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 16        | 0.64%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 15        | 0.6%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 14        | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.52%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 12        | 0.48%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16384MB DIMM DDR4 3200MT/s         | 12        | 0.48%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.48%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.48%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 12        | 0.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.44%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 11        | 0.44%   |
| Unknown                                                          | 11        | 0.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 10        | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.4%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 10        | 0.4%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 10        | 0.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.36%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 9         | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 8         | 0.32%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 8         | 0.32%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 8         | 0.32%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 8         | 0.32%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.32%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 8         | 0.32%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.32%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1191      | 60.49%  |
| DDR3    | 576       | 29.25%  |
| LPDDR4  | 43        | 2.18%   |
| LPDDR3  | 39        | 1.98%   |
| Unknown | 31        | 1.57%   |
| DDR5    | 29        | 1.47%   |
| DDR2    | 25        | 1.27%   |
| SDRAM   | 24        | 1.22%   |
| LPDDR5  | 7         | 0.36%   |
| DDR     | 3         | 0.15%   |
| DRAM    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1041      | 52.6%   |
| DIMM         | 821       | 41.49%  |
| Row Of Chips | 104       | 5.26%   |
| Chip         | 10        | 0.51%   |
| RIMM         | 2         | 0.1%    |
| Unknown      | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 982       | 45.3%   |
| 4096  | 539       | 24.86%  |
| 16384 | 389       | 17.94%  |
| 2048  | 138       | 6.37%   |
| 32768 | 95        | 4.38%   |
| 1024  | 19        | 0.88%   |
| 512   | 2         | 0.09%   |
| 49152 | 1         | 0.05%   |
| 12288 | 1         | 0.05%   |
| 64    | 1         | 0.05%   |
| 16    | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 411       | 18.73%  |
| 3200    | 390       | 17.78%  |
| 2667    | 351       | 16%     |
| 2400    | 186       | 8.48%   |
| 2133    | 104       | 4.74%   |
| 3600    | 102       | 4.65%   |
| 1333    | 99        | 4.51%   |
| 1334    | 40        | 1.82%   |
| 1867    | 38        | 1.73%   |
| 3733    | 30        | 1.37%   |
| 3400    | 30        | 1.37%   |
| 3000    | 26        | 1.19%   |
| 3266    | 25        | 1.14%   |
| 1067    | 22        | 1%      |
| 4800    | 18        | 0.82%   |
| Unknown | 18        | 0.82%   |
| 3800    | 17        | 0.77%   |
| 1866    | 17        | 0.77%   |
| 667     | 17        | 0.77%   |
| 800     | 16        | 0.73%   |
| 4267    | 15        | 0.68%   |
| 3533    | 15        | 0.68%   |
| 2933    | 14        | 0.64%   |
| 2666    | 14        | 0.64%   |
| 1800    | 14        | 0.64%   |
| 3866    | 13        | 0.59%   |
| 2800    | 13        | 0.59%   |
| 3466    | 12        | 0.55%   |
| 3666    | 8         | 0.36%   |
| 4199    | 7         | 0.32%   |
| 8400    | 6         | 0.27%   |
| 6400    | 6         | 0.27%   |
| 3334    | 6         | 0.27%   |
| 3333    | 6         | 0.27%   |
| 5200    | 5         | 0.23%   |
| 4266    | 5         | 0.23%   |
| 3534    | 5         | 0.23%   |
| 2465    | 5         | 0.23%   |
| 2048    | 5         | 0.23%   |
| 2000    | 5         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 18        | 35.29%  |
| Brother Industries    | 16        | 31.37%  |
| Canon                 | 6         | 11.76%  |
| Seiko Epson           | 5         | 9.8%    |
| Samsung Electronics   | 2         | 3.92%   |
| MIIIW                 | 1         | 1.96%   |
| Lexmark International | 1         | 1.96%   |
| Gprinter              | 1         | 1.96%   |
| Dymo-CoStar           | 1         | 1.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon PIXMA MG3600 Series              | 3         | 5.77%   |
| Seiko Epson ET-4700 Series             | 2         | 3.85%   |
| HP DeskJet F4100 Printer series        | 2         | 3.85%   |
| HP DeskJet 2600 series                 | 2         | 3.85%   |
| Brother Printer                        | 2         | 3.85%   |
| Brother DCP-7055 scanner/printer       | 2         | 3.85%   |
| Seiko Epson XP-240 Series              | 1         | 1.92%   |
| Seiko Epson XP-2100 Series             | 1         | 1.92%   |
| Seiko Epson ET-2710 Series             | 1         | 1.92%   |
| Samsung SCX-3400 Series                | 1         | 1.92%   |
| Samsung SCX-3200 Series                | 1         | 1.92%   |
| MIIIW MW Keyboard Air Mini             | 1         | 1.92%   |
| Lexmark International B2236dw          | 1         | 1.92%   |
| HP PSC 1400                            | 1         | 1.92%   |
| HP OfficeJet Pro 8020 series           | 1         | 1.92%   |
| HP OfficeJet Pro 6960                  | 1         | 1.92%   |
| HP OfficeJet 5200 series               | 1         | 1.92%   |
| HP OfficeJet 4650 series               | 1         | 1.92%   |
| HP LaserJet Professional P1102w        | 1         | 1.92%   |
| HP LaserJet P1005                      | 1         | 1.92%   |
| HP LaserJet M203-M206                  | 1         | 1.92%   |
| HP LaserJet 1015                       | 1         | 1.92%   |
| HP ENVY 6400 series                    | 1         | 1.92%   |
| HP ENVY 4500 series                    | 1         | 1.92%   |
| HP Deskjet 4640 series                 | 1         | 1.92%   |
| HP DeskJet 3700 series                 | 1         | 1.92%   |
| HP DeskJet 2700 series                 | 1         | 1.92%   |
| HP Deskjet 1050 J410                   | 1         | 1.92%   |
| Gprinter GP-58                         | 1         | 1.92%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 1.92%   |
| Canon TS5100 series                    | 1         | 1.92%   |
| Canon G2000 series                     | 1         | 1.92%   |
| Canon CanoScan LiDE 300                | 1         | 1.92%   |
| Brother MFC-L3770CDW series            | 1         | 1.92%   |
| Brother MFC-L3750CDW                   | 1         | 1.92%   |
| Brother MFC-J6545DW                    | 1         | 1.92%   |
| Brother MFC-J497DW                     | 1         | 1.92%   |
| Brother MFC-J485DW                     | 1         | 1.92%   |
| Brother MFC-J450DW                     | 1         | 1.92%   |
| Brother MFC-7460DN                     | 1         | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 40%     |
| Hewlett-Packard | 2         | 40%     |
| Canon           | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 20%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1         | 20%     |
| HP ScanJet 2400c                                        | 1         | 20%     |
| HP ScanJet 2200c                                        | 1         | 20%     |
| Canon CanoScan LiDE 200                                 | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 293       | 22.85%  |
| IMC Networks                           | 136       | 10.61%  |
| Logitech                               | 104       | 8.11%   |
| Microdia                               | 98        | 7.64%   |
| Realtek Semiconductor                  | 93        | 7.25%   |
| Bison Electronics                      | 92        | 7.18%   |
| Sunplus Innovation Technology          | 69        | 5.38%   |
| Quanta                                 | 53        | 4.13%   |
| Apple                                  | 42        | 3.28%   |
| Cheng Uei Precision Industry (Foxlink) | 37        | 2.89%   |
| Syntek                                 | 28        | 2.18%   |
| Lite-On Technology                     | 25        | 1.95%   |
| Suyin                                  | 22        | 1.72%   |
| Acer                                   | 22        | 1.72%   |
| Luxvisions Innotech Limited            | 17        | 1.33%   |
| Silicon Motion                         | 11        | 0.86%   |
| Microsoft                              | 11        | 0.86%   |
| Lenovo                                 | 11        | 0.86%   |
| Sonix Technology                       | 10        | 0.78%   |
| Samsung Electronics                    | 10        | 0.78%   |
| Primax Electronics                     | 6         | 0.47%   |
| Generalplus Technology                 | 6         | 0.47%   |
| Alcor Micro                            | 6         | 0.47%   |
| Razer USA                              | 5         | 0.39%   |
| KYE Systems (Mouse Systems)            | 5         | 0.39%   |
| GEMBIRD                                | 5         | 0.39%   |
| Creative Technology                    | 5         | 0.39%   |
| Hewlett-Packard                        | 4         | 0.31%   |
| Z-Star Microelectronics                | 3         | 0.23%   |
| Ricoh                                  | 3         | 0.23%   |
| MacroSilicon                           | 3         | 0.23%   |
| Importek                               | 3         | 0.23%   |
| ARC International                      | 3         | 0.23%   |
| WaveRider Communications               | 2         | 0.16%   |
| Sunplus Technology                     | 2         | 0.16%   |
| Ruision                                | 2         | 0.16%   |
| OPPO Electronics                       | 2         | 0.16%   |
| icSpring                               | 2         | 0.16%   |
| Hopewin Electronic Material            | 2         | 0.16%   |
| Google                                 | 2         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 78        | 6.05%   |
| IMC Networks Integrated Camera                      | 43        | 3.33%   |
| Microdia Integrated_Webcam_HD                       | 40        | 3.1%    |
| Realtek Integrated_Webcam_HD                        | 36        | 2.79%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 32        | 2.48%   |
| Bison Integrated Camera                             | 31        | 2.4%    |
| Logitech HD Pro Webcam C920                         | 29        | 2.25%   |
| Chicony HD WebCam                                   | 27        | 2.09%   |
| Logitech Webcam C270                                | 22        | 1.71%   |
| Sunplus Integrated_Webcam_HD                        | 21        | 1.63%   |
| Syntek Integrated Camera                            | 18        | 1.4%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 18        | 1.4%    |
| Lite-On Integrated Camera                           | 15        | 1.16%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 15        | 1.16%   |
| Logitech C922 Pro Stream Webcam                     | 14        | 1.09%   |
| Chicony USB2.0 Camera                               | 14        | 1.09%   |
| Chicony HP Wide Vision HD Camera                    | 13        | 1.01%   |
| Chicony USB2.0 VGA UVC WebCam                       | 11        | 0.85%   |
| Chicony HP Truevision HD                            | 11        | 0.85%   |
| Bison HD Webcam                                     | 11        | 0.85%   |
| Apple Built-in iSight                               | 11        | 0.85%   |
| Samsung Galaxy series, misc. (MTP mode)             | 10        | 0.78%   |
| Quanta HP TrueVision HD Camera                      | 10        | 0.78%   |
| Microdia Integrated Webcam                          | 10        | 0.78%   |
| Quanta HD Webcam                                    | 9         | 0.7%    |
| Chicony Integrated Camera (1280x720@30)             | 9         | 0.7%    |
| Chicony HP HD Camera                                | 9         | 0.7%    |
| Chicony EasyCamera                                  | 9         | 0.7%    |
| Bison EasyCamera                                    | 9         | 0.7%    |
| Bison BisonCam,NB Pro                               | 9         | 0.7%    |
| Quanta HD User Facing                               | 8         | 0.62%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 8         | 0.62%   |
| Chicony USB2.0 HD UVC WebCam                        | 8         | 0.62%   |
| Chicony TOSHIBA Web Camera - HD                     | 8         | 0.62%   |
| Chicony HP Truevision HD camera                     | 8         | 0.62%   |
| Chicony HD User Facing                              | 8         | 0.62%   |
| Apple FaceTime HD Camera (Built-in)                 | 8         | 0.62%   |
| Realtek Integrated Webcam HD                        | 7         | 0.54%   |
| Microsoft LifeCam HD-3000                           | 7         | 0.54%   |
| Bison SunplusIT Integrated Camera                   | 7         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 84        | 38.18%  |
| Synaptics                          | 57        | 25.91%  |
| Shenzhen Goodix Technology         | 33        | 15%     |
| Elan Microelectronics              | 15        | 6.82%   |
| Upek                               | 11        | 5%      |
| LighTuning Technology              | 11        | 5%      |
| AuthenTec                          | 6         | 2.73%   |
| STMicroelectronics                 | 1         | 0.45%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.45%   |
| DigitalPersona                     | 1         | 0.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 9.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 9.09%   |
| Shenzhen Goodix  FingerPrint Device                                        | 16        | 7.27%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 5.91%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 5.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 4.55%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 3.18%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 3.18%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 3.18%   |
| Elan ELAN:Fingerprint                                                      | 7         | 3.18%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.73%   |
| Synaptics  WBDI                                                            | 6         | 2.73%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 2.27%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.27%   |
| Elan ELAN:ARM-M4                                                           | 5         | 2.27%   |
| Synaptics UWP WBDI                                                         | 4         | 1.82%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.36%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.36%   |
| Synaptics WBDI                                                             | 3         | 1.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.36%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.36%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.91%   |
| Validity Sensors VFS491                                                    | 2         | 0.91%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.91%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.91%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.91%   |
| Synaptics WBDI Device                                                      | 2         | 0.91%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.91%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.91%   |
| AuthenTec AES1600                                                          | 2         | 0.91%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.45%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.45%   |
| Synaptics Fingerprint scanner                                              | 1         | 0.45%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.45%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.45%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.45%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 40        | 41.24%  |
| Broadcom              | 34        | 35.05%  |
| O2 Micro              | 6         | 6.19%   |
| Upek                  | 5         | 5.15%   |
| Lenovo                | 4         | 4.12%   |
| Gemalto (was Gemplus) | 2         | 2.06%   |
| Yubico.com            | 1         | 1.03%   |
| SCM Microsystems      | 1         | 1.03%   |
| OmniKey               | 1         | 1.03%   |
| Clay Logic            | 1         | 1.03%   |
| Cherry                | 1         | 1.03%   |
| Aladdin R.D.          | 1         | 1.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 40        | 41.24%  |
| Broadcom 5880                                                                | 12        | 12.37%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 8.25%   |
| Broadcom 58200                                                               | 7         | 7.22%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 6.19%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.15%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 5.15%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.12%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 2.06%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 1.03%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 1.03%   |
| OmniKey CardMan 1021                                                         | 1         | 1.03%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.03%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.03%   |
| Cherry Smart Card Reader USB                                                 | 1         | 1.03%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.03%   |
| Aladdin R.D. JaCarta LT                                                      | 1         | 1.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1587      | 73.27%  |
| 1     | 463       | 21.38%  |
| 2     | 107       | 4.94%   |
| 3     | 5         | 0.23%   |
| 4     | 4         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 220       | 32.5%   |
| Graphics card            | 176       | 26%     |
| Chipcard                 | 92        | 13.59%  |
| Net/wireless             | 58        | 8.57%   |
| Multimedia controller    | 30        | 4.43%   |
| Camera                   | 30        | 4.43%   |
| Unassigned class         | 18        | 2.66%   |
| Communication controller | 17        | 2.51%   |
| Bluetooth                | 11        | 1.62%   |
| Network                  | 5         | 0.74%   |
| Net/ethernet             | 5         | 0.74%   |
| Card reader              | 5         | 0.74%   |
| Storage/nvme             | 2         | 0.3%    |
| Storage                  | 2         | 0.3%    |
| Modem                    | 2         | 0.3%    |
| Dvb card                 | 2         | 0.3%    |
| Wireless                 | 1         | 0.15%   |
| Sound                    | 1         | 0.15%   |

