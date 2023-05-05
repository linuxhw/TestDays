Linux in Sweden - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Sweden/Desktop/README.md) and [notebooks](/Location/Sweden/Notebook/README.md).

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

Total: 2823

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [56db7fc27f](https://linux-hardware.org/?probe=56db7fc27f) | May 01, 2023 |
| Shuttle       | FS35V4                      | Desktop     | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| MSI           | MS-B120                     | Mini pc     | [8019bfa6d4](https://linux-hardware.org/?probe=8019bfa6d4) | Apr 30, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4f10159e93](https://linux-hardware.org/?probe=4f10159e93) | Apr 30, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [4b47a4606b](https://linux-hardware.org/?probe=4b47a4606b) | Apr 29, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [1a73639c02](https://linux-hardware.org/?probe=1a73639c02) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [a6eba14ab4](https://linux-hardware.org/?probe=a6eba14ab4) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6f56840307](https://linux-hardware.org/?probe=6f56840307) | Apr 28, 2023 |
| Dell          | Latitude 5430               | Notebook    | [644e44f95a](https://linux-hardware.org/?probe=644e44f95a) | Apr 28, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [c53a69bd72](https://linux-hardware.org/?probe=c53a69bd72) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [69f1753783](https://linux-hardware.org/?probe=69f1753783) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [067bc49888](https://linux-hardware.org/?probe=067bc49888) | Apr 26, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [99e0054492](https://linux-hardware.org/?probe=99e0054492) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [86b56d3e69](https://linux-hardware.org/?probe=86b56d3e69) | Apr 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [adab9d9f6b](https://linux-hardware.org/?probe=adab9d9f6b) | Apr 22, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [17c955a974](https://linux-hardware.org/?probe=17c955a974) | Apr 21, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [cb9c80dbba](https://linux-hardware.org/?probe=cb9c80dbba) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [3f12350d47](https://linux-hardware.org/?probe=3f12350d47) | Apr 20, 2023 |
| Dell          | Latitude 7490               | Notebook    | [57a719ce62](https://linux-hardware.org/?probe=57a719ce62) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [83c6b6137d](https://linux-hardware.org/?probe=83c6b6137d) | Apr 20, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [b45a30f071](https://linux-hardware.org/?probe=b45a30f071) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6SV0... | Notebook    | [8f05b53b93](https://linux-hardware.org/?probe=8f05b53b93) | Apr 17, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [4278a9f497](https://linux-hardware.org/?probe=4278a9f497) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | Notebook    | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [39106da598](https://linux-hardware.org/?probe=39106da598) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a9f8183365](https://linux-hardware.org/?probe=a9f8183365) | Apr 16, 2023 |
| Unknown       | Unknown                     | Phone       | [3d8d71ba51](https://linux-hardware.org/?probe=3d8d71ba51) | Apr 16, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [a51c500b65](https://linux-hardware.org/?probe=a51c500b65) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [b259f47200](https://linux-hardware.org/?probe=b259f47200) | Apr 15, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [40894d0141](https://linux-hardware.org/?probe=40894d0141) | Apr 14, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [d2c04327fb](https://linux-hardware.org/?probe=d2c04327fb) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [b7786541c0](https://linux-hardware.org/?probe=b7786541c0) | Apr 13, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [ec6dc0883b](https://linux-hardware.org/?probe=ec6dc0883b) | Apr 13, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [87d43c1f1d](https://linux-hardware.org/?probe=87d43c1f1d) | Apr 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a291f82fe3](https://linux-hardware.org/?probe=a291f82fe3) | Apr 12, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [810aed46d0](https://linux-hardware.org/?probe=810aed46d0) | Apr 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5db9e8f875](https://linux-hardware.org/?probe=5db9e8f875) | Apr 11, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [7ddf3af042](https://linux-hardware.org/?probe=7ddf3af042) | Apr 11, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [e3eee10ad1](https://linux-hardware.org/?probe=e3eee10ad1) | Apr 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [d5fb19d97c](https://linux-hardware.org/?probe=d5fb19d97c) | Apr 08, 2023 |
| HP            | ProBook 4530s               | Notebook    | [efd084d9d5](https://linux-hardware.org/?probe=efd084d9d5) | Apr 07, 2023 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [0ddbf6cc2e](https://linux-hardware.org/?probe=0ddbf6cc2e) | Apr 07, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [a0c75732ae](https://linux-hardware.org/?probe=a0c75732ae) | Apr 06, 2023 |
| LG Electro... | Kabylake Platform           | Notebook    | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [0f4a907d19](https://linux-hardware.org/?probe=0f4a907d19) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [d337edfd9a](https://linux-hardware.org/?probe=d337edfd9a) | Apr 05, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6ddafae4d0](https://linux-hardware.org/?probe=6ddafae4d0) | Apr 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [01f2e4a69f](https://linux-hardware.org/?probe=01f2e4a69f) | Apr 05, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [f49ec499ed](https://linux-hardware.org/?probe=f49ec499ed) | Apr 04, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [68322a0698](https://linux-hardware.org/?probe=68322a0698) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [53fc9d8c25](https://linux-hardware.org/?probe=53fc9d8c25) | Apr 04, 2023 |
| Dell          | Precision 5530              | Notebook    | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [550f1d522d](https://linux-hardware.org/?probe=550f1d522d) | Apr 04, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [56a619b537](https://linux-hardware.org/?probe=56a619b537) | Apr 04, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [08074927ff](https://linux-hardware.org/?probe=08074927ff) | Apr 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d57f6cb4c6](https://linux-hardware.org/?probe=d57f6cb4c6) | Apr 03, 2023 |
| Intel         | NUC12WSBi5 M63398-302       | Mini pc     | [785a41f4e9](https://linux-hardware.org/?probe=785a41f4e9) | Apr 02, 2023 |
| Acer          | Predator G3-605             | Desktop     | [f7ca1573d0](https://linux-hardware.org/?probe=f7ca1573d0) | Apr 02, 2023 |
| Acer          | Predator G3-605             | Desktop     | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [06275c19f3](https://linux-hardware.org/?probe=06275c19f3) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [36e57fb4cf](https://linux-hardware.org/?probe=36e57fb4cf) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a89c429c84](https://linux-hardware.org/?probe=a89c429c84) | Mar 31, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| HP            | 82B4                        | Desktop     | [9712d04ab5](https://linux-hardware.org/?probe=9712d04ab5) | Mar 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [f897573506](https://linux-hardware.org/?probe=f897573506) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [50affe59d1](https://linux-hardware.org/?probe=50affe59d1) | Mar 28, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b74b7f7d31](https://linux-hardware.org/?probe=b74b7f7d31) | Mar 28, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [f0e6089a6e](https://linux-hardware.org/?probe=f0e6089a6e) | Mar 28, 2023 |
| Acer          | Nitro N50-640               | Desktop     | [2219ec0fad](https://linux-hardware.org/?probe=2219ec0fad) | Mar 27, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [011d1b8bf7](https://linux-hardware.org/?probe=011d1b8bf7) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [c5a3b374a7](https://linux-hardware.org/?probe=c5a3b374a7) | Mar 27, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [8a1c592e98](https://linux-hardware.org/?probe=8a1c592e98) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [f403538019](https://linux-hardware.org/?probe=f403538019) | Mar 26, 2023 |
| HP            | 1998                        | Desktop     | [346f37956b](https://linux-hardware.org/?probe=346f37956b) | Mar 26, 2023 |
| Gigabyte      | AORUS 15G KC                | Notebook    | [d87e89d84f](https://linux-hardware.org/?probe=d87e89d84f) | Mar 26, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [6f9300474f](https://linux-hardware.org/?probe=6f9300474f) | Mar 26, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [d1baffa910](https://linux-hardware.org/?probe=d1baffa910) | Mar 25, 2023 |
| HP            | 2B05                        | Desktop     | [b34e6d230c](https://linux-hardware.org/?probe=b34e6d230c) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [1e549ae67e](https://linux-hardware.org/?probe=1e549ae67e) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| Shuttle       | SH570                       | Desktop     | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [240444cad9](https://linux-hardware.org/?probe=240444cad9) | Mar 21, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [a9a586ef2d](https://linux-hardware.org/?probe=a9a586ef2d) | Mar 20, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [51e5415bb0](https://linux-hardware.org/?probe=51e5415bb0) | Mar 19, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [c88d5f831a](https://linux-hardware.org/?probe=c88d5f831a) | Mar 19, 2023 |
| Intel         | NUC5CPYB H61145-412         | Mini pc     | [a87d0fe300](https://linux-hardware.org/?probe=a87d0fe300) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [87ba801b00](https://linux-hardware.org/?probe=87ba801b00) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d95b09eda0](https://linux-hardware.org/?probe=d95b09eda0) | Mar 17, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [dfb8518fa9](https://linux-hardware.org/?probe=dfb8518fa9) | Mar 16, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [bb4f0202b7](https://linux-hardware.org/?probe=bb4f0202b7) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Google        | Rabbid                      | Notebook    | [621762ceec](https://linux-hardware.org/?probe=621762ceec) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | Notebook    | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [016f5cd3be](https://linux-hardware.org/?probe=016f5cd3be) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | Desktop     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [070c7d809a](https://linux-hardware.org/?probe=070c7d809a) | Mar 13, 2023 |
| GPD           | P2 MAX                      | Notebook    | [dd958bf28e](https://linux-hardware.org/?probe=dd958bf28e) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [12120178de](https://linux-hardware.org/?probe=12120178de) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| HP            | 1825                        | Desktop     | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [1169593829](https://linux-hardware.org/?probe=1169593829) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [76e4cc71f5](https://linux-hardware.org/?probe=76e4cc71f5) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| HP            | 1998                        | Desktop     | [68d7c4350d](https://linux-hardware.org/?probe=68d7c4350d) | Mar 12, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c22a046fc6](https://linux-hardware.org/?probe=c22a046fc6) | Mar 11, 2023 |
| SiYW          | V200 Series                 | Desktop     | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [0555c85a89](https://linux-hardware.org/?probe=0555c85a89) | Mar 11, 2023 |
| HP            | 18E5                        | Desktop     | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [03f44a913e](https://linux-hardware.org/?probe=03f44a913e) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d15122995](https://linux-hardware.org/?probe=4d15122995) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc6e719e99](https://linux-hardware.org/?probe=cc6e719e99) | Mar 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1768ecbaa](https://linux-hardware.org/?probe=d1768ecbaa) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [081ecd2050](https://linux-hardware.org/?probe=081ecd2050) | Mar 07, 2023 |
| HP            | Presario CQ57               | Notebook    | [33b1812664](https://linux-hardware.org/?probe=33b1812664) | Mar 06, 2023 |
| HP            | Presario CQ57               | Notebook    | [26ec55c2cb](https://linux-hardware.org/?probe=26ec55c2cb) | Mar 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0d202dc031](https://linux-hardware.org/?probe=0d202dc031) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8814af9b71](https://linux-hardware.org/?probe=8814af9b71) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f9a2075d54](https://linux-hardware.org/?probe=f9a2075d54) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Dell          | Precision 3551              | Notebook    | [7c1bc8355a](https://linux-hardware.org/?probe=7c1bc8355a) | Mar 03, 2023 |
| Clevo         | W25xHNx                     | Notebook    | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [f3defb812b](https://linux-hardware.org/?probe=f3defb812b) | Mar 03, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [41d9c3d9ed](https://linux-hardware.org/?probe=41d9c3d9ed) | Mar 02, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a279108842](https://linux-hardware.org/?probe=a279108842) | Mar 02, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | Desktop     | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [3cd0e65d1f](https://linux-hardware.org/?probe=3cd0e65d1f) | Feb 27, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2fe31a709a](https://linux-hardware.org/?probe=2fe31a709a) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [5ef01d46d4](https://linux-hardware.org/?probe=5ef01d46d4) | Feb 25, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0AE0... | Notebook    | [7f8c9de1aa](https://linux-hardware.org/?probe=7f8c9de1aa) | Feb 24, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [fc86b476d7](https://linux-hardware.org/?probe=fc86b476d7) | Feb 22, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [da461191e8](https://linux-hardware.org/?probe=da461191e8) | Feb 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [54b9c4c95c](https://linux-hardware.org/?probe=54b9c4c95c) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ecc97fee86](https://linux-hardware.org/?probe=ecc97fee86) | Feb 21, 2023 |
| Dell          | Precision M4800             | Notebook    | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| ASUSTek       | G501VW                      | Notebook    | [6e014311b2](https://linux-hardware.org/?probe=6e014311b2) | Feb 20, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [5aa73f71fd](https://linux-hardware.org/?probe=5aa73f71fd) | Feb 20, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [7427fa6886](https://linux-hardware.org/?probe=7427fa6886) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [2b56edae65](https://linux-hardware.org/?probe=2b56edae65) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [dde311dcb2](https://linux-hardware.org/?probe=dde311dcb2) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [96b350db9f](https://linux-hardware.org/?probe=96b350db9f) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| GPD           | P2 MAX                      | Notebook    | [9a623b2196](https://linux-hardware.org/?probe=9a623b2196) | Feb 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [eac9c046ac](https://linux-hardware.org/?probe=eac9c046ac) | Feb 15, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [3717c2476f](https://linux-hardware.org/?probe=3717c2476f) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4e3ff30332](https://linux-hardware.org/?probe=4e3ff30332) | Feb 15, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [eb40144624](https://linux-hardware.org/?probe=eb40144624) | Feb 13, 2023 |
| HP            | 8455                        | Desktop     | [f75db6c5d5](https://linux-hardware.org/?probe=f75db6c5d5) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [3a18e2226c](https://linux-hardware.org/?probe=3a18e2226c) | Feb 12, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c1ac37fee3](https://linux-hardware.org/?probe=c1ac37fee3) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| MSI           | MS-B120                     | Mini pc     | [1d365cbddd](https://linux-hardware.org/?probe=1d365cbddd) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| AZW           | GTR V01                     | Mini pc     | [2898aebf10](https://linux-hardware.org/?probe=2898aebf10) | Feb 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| Dell          | Latitude E7250              | Notebook    | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [3797cf0990](https://linux-hardware.org/?probe=3797cf0990) | Feb 07, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [687e52dcb1](https://linux-hardware.org/?probe=687e52dcb1) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [e553ba2549](https://linux-hardware.org/?probe=e553ba2549) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [d888ff5291](https://linux-hardware.org/?probe=d888ff5291) | Feb 06, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [0c6df9267b](https://linux-hardware.org/?probe=0c6df9267b) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [452216b5ed](https://linux-hardware.org/?probe=452216b5ed) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f265a0e81e](https://linux-hardware.org/?probe=f265a0e81e) | Feb 04, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [9e2380e15d](https://linux-hardware.org/?probe=9e2380e15d) | Feb 03, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [fac45201b3](https://linux-hardware.org/?probe=fac45201b3) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6e089e22b1](https://linux-hardware.org/?probe=6e089e22b1) | Feb 01, 2023 |
| Dell          | Latitude 7420               | Notebook    | [f0b8816283](https://linux-hardware.org/?probe=f0b8816283) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [f1a9c37047](https://linux-hardware.org/?probe=f1a9c37047) | Jan 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [fe2a413caa](https://linux-hardware.org/?probe=fe2a413caa) | Jan 31, 2023 |
| Dell          | Latitude 7420               | Notebook    | [55f81648a1](https://linux-hardware.org/?probe=55f81648a1) | Jan 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| Dell          | Latitude D630C              | Notebook    | [401357bc99](https://linux-hardware.org/?probe=401357bc99) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | Notebook    | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [f01366b131](https://linux-hardware.org/?probe=f01366b131) | Jan 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [54ba66711b](https://linux-hardware.org/?probe=54ba66711b) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [756bf12bd7](https://linux-hardware.org/?probe=756bf12bd7) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [c4a13a66ed](https://linux-hardware.org/?probe=c4a13a66ed) | Jan 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [cb00a3e89d](https://linux-hardware.org/?probe=cb00a3e89d) | Jan 24, 2023 |
| Google        | Link                        | Notebook    | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [1a9bed0cf3](https://linux-hardware.org/?probe=1a9bed0cf3) | Jan 23, 2023 |
| Dell          | 0Y56T3 A00                  | Desktop     | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| AZW           | GTR V01                     | Mini pc     | [1d4c2002d5](https://linux-hardware.org/?probe=1d4c2002d5) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fa1f3d8e3b](https://linux-hardware.org/?probe=fa1f3d8e3b) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [1d10977303](https://linux-hardware.org/?probe=1d10977303) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [fdbbb4a832](https://linux-hardware.org/?probe=fdbbb4a832) | Jan 21, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [80e51b3319](https://linux-hardware.org/?probe=80e51b3319) | Jan 20, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [d7e7799006](https://linux-hardware.org/?probe=d7e7799006) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [e221c08388](https://linux-hardware.org/?probe=e221c08388) | Jan 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [d2bb65ed09](https://linux-hardware.org/?probe=d2bb65ed09) | Jan 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6d6698b316](https://linux-hardware.org/?probe=6d6698b316) | Jan 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [8bfae8a964](https://linux-hardware.org/?probe=8bfae8a964) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0e57f4ecbe](https://linux-hardware.org/?probe=0e57f4ecbe) | Jan 15, 2023 |
| Star Labs     | StarBook                    | Notebook    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [5b26575c52](https://linux-hardware.org/?probe=5b26575c52) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [0533348a3f](https://linux-hardware.org/?probe=0533348a3f) | Jan 14, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [b0308f4270](https://linux-hardware.org/?probe=b0308f4270) | Jan 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [262fe40796](https://linux-hardware.org/?probe=262fe40796) | Jan 12, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [18bdf2650e](https://linux-hardware.org/?probe=18bdf2650e) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| Dell          | Studio 1749                 | Notebook    | [28a19b2c03](https://linux-hardware.org/?probe=28a19b2c03) | Jan 11, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [7697ff8cb4](https://linux-hardware.org/?probe=7697ff8cb4) | Jan 11, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [994306b125](https://linux-hardware.org/?probe=994306b125) | Jan 11, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [72bf3e7a8b](https://linux-hardware.org/?probe=72bf3e7a8b) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [aacfe1b351](https://linux-hardware.org/?probe=aacfe1b351) | Jan 11, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [5cfaf7d715](https://linux-hardware.org/?probe=5cfaf7d715) | Jan 10, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [59155b3092](https://linux-hardware.org/?probe=59155b3092) | Jan 10, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [ac85316fc2](https://linux-hardware.org/?probe=ac85316fc2) | Jan 09, 2023 |
| MSI           | GP60 2PE                    | Notebook    | [e1506ca6f6](https://linux-hardware.org/?probe=e1506ca6f6) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [980ee9f42c](https://linux-hardware.org/?probe=980ee9f42c) | Jan 07, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [e64152748d](https://linux-hardware.org/?probe=e64152748d) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Samsung       | R530/R730                   | Notebook    | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Precision M90               | Notebook    | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a24229bc3b](https://linux-hardware.org/?probe=a24229bc3b) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2849ffe456](https://linux-hardware.org/?probe=2849ffe456) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [77cc17c28c](https://linux-hardware.org/?probe=77cc17c28c) | Jan 02, 2023 |
| Foxconn       | 2AAF                        | Desktop     | [813a45dc50](https://linux-hardware.org/?probe=813a45dc50) | Jan 01, 2023 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [de65990b87](https://linux-hardware.org/?probe=de65990b87) | Jan 01, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [273f6722e0](https://linux-hardware.org/?probe=273f6722e0) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [34cd286c5f](https://linux-hardware.org/?probe=34cd286c5f) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [15c60654b3](https://linux-hardware.org/?probe=15c60654b3) | Dec 30, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [87d0f67d84](https://linux-hardware.org/?probe=87d0f67d84) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b89e7eb1c9](https://linux-hardware.org/?probe=b89e7eb1c9) | Dec 28, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [f37619077b](https://linux-hardware.org/?probe=f37619077b) | Dec 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e979df032a](https://linux-hardware.org/?probe=e979df032a) | Dec 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [82a5aa7ead](https://linux-hardware.org/?probe=82a5aa7ead) | Dec 26, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| GMKtec        | NucBox8                     | Server      | [abc999a1a4](https://linux-hardware.org/?probe=abc999a1a4) | Dec 24, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| Dell          | Latitude 3380               | Notebook    | [e4847d5b1f](https://linux-hardware.org/?probe=e4847d5b1f) | Dec 24, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [92f12e3ec7](https://linux-hardware.org/?probe=92f12e3ec7) | Dec 24, 2022 |
| GMKtec        | NucBox8                     | Server      | [66b0fbce86](https://linux-hardware.org/?probe=66b0fbce86) | Dec 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [3237ff6784](https://linux-hardware.org/?probe=3237ff6784) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [ba82bee4c7](https://linux-hardware.org/?probe=ba82bee4c7) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [a2a2f20ef4](https://linux-hardware.org/?probe=a2a2f20ef4) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92515d8a95](https://linux-hardware.org/?probe=92515d8a95) | Dec 21, 2022 |
| Schenker      | XMG APEX 15 MAX (E22)       | Notebook    | [6b46538fea](https://linux-hardware.org/?probe=6b46538fea) | Dec 21, 2022 |
| Dell          | 0020HJ A01                  | Server      | [e266254c60](https://linux-hardware.org/?probe=e266254c60) | Dec 21, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [5477e8f714](https://linux-hardware.org/?probe=5477e8f714) | Dec 21, 2022 |
| Dell          | Latitude 3380               | Notebook    | [808c693271](https://linux-hardware.org/?probe=808c693271) | Dec 20, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [8a09a51987](https://linux-hardware.org/?probe=8a09a51987) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4fbc0ddbd5](https://linux-hardware.org/?probe=4fbc0ddbd5) | Dec 20, 2022 |
| HP            | 18E7                        | Desktop     | [31011a35a4](https://linux-hardware.org/?probe=31011a35a4) | Dec 17, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [3b48a01ef2](https://linux-hardware.org/?probe=3b48a01ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ffa7e28596](https://linux-hardware.org/?probe=ffa7e28596) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [bc3635620b](https://linux-hardware.org/?probe=bc3635620b) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [888e6092a6](https://linux-hardware.org/?probe=888e6092a6) | Dec 15, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [5248ee7dbe](https://linux-hardware.org/?probe=5248ee7dbe) | Dec 15, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [3403282c8c](https://linux-hardware.org/?probe=3403282c8c) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | Desktop     | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a0d408fecd](https://linux-hardware.org/?probe=a0d408fecd) | Dec 15, 2022 |
| Dell          | Latitude E7240              | Notebook    | [c47fc4fadf](https://linux-hardware.org/?probe=c47fc4fadf) | Dec 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6b47a036ab](https://linux-hardware.org/?probe=6b47a036ab) | Dec 14, 2022 |
| Insyde        | G0975                       | Notebook    | [1f4823542d](https://linux-hardware.org/?probe=1f4823542d) | Dec 14, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [39a9464c10](https://linux-hardware.org/?probe=39a9464c10) | Dec 14, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5a9654c743](https://linux-hardware.org/?probe=5a9654c743) | Dec 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [05ffc0ef7a](https://linux-hardware.org/?probe=05ffc0ef7a) | Dec 13, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [502792fe8a](https://linux-hardware.org/?probe=502792fe8a) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [7b8b3c2a86](https://linux-hardware.org/?probe=7b8b3c2a86) | Dec 12, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [65c6c18ffe](https://linux-hardware.org/?probe=65c6c18ffe) | Dec 12, 2022 |
| Dell          | Latitude 5430               | Notebook    | [b439d1e1a4](https://linux-hardware.org/?probe=b439d1e1a4) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| Google        | Orco                        | Notebook    | [40acd3207e](https://linux-hardware.org/?probe=40acd3207e) | Dec 10, 2022 |
| Google        | Orco                        | Notebook    | [9c369b40b3](https://linux-hardware.org/?probe=9c369b40b3) | Dec 10, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3a91c2e245](https://linux-hardware.org/?probe=3a91c2e245) | Dec 07, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [310ff494e7](https://linux-hardware.org/?probe=310ff494e7) | Dec 06, 2022 |
| HP            | 18E5                        | Desktop     | [9158a7ab6b](https://linux-hardware.org/?probe=9158a7ab6b) | Dec 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | Notebook    | [d01d1e9652](https://linux-hardware.org/?probe=d01d1e9652) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [ff90421b87](https://linux-hardware.org/?probe=ff90421b87) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [3bc6ea9cfa](https://linux-hardware.org/?probe=3bc6ea9cfa) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [aaed16d626](https://linux-hardware.org/?probe=aaed16d626) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [cd63efdbd4](https://linux-hardware.org/?probe=cd63efdbd4) | Dec 05, 2022 |
| SiYW          | V200 Series                 | Desktop     | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| Sony          | VPCEB1M1E                   | Notebook    | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [d8d5459ad6](https://linux-hardware.org/?probe=d8d5459ad6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [1dddd99280](https://linux-hardware.org/?probe=1dddd99280) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | Notebook    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | Notebook    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [258c074e40](https://linux-hardware.org/?probe=258c074e40) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [29ec19d38e](https://linux-hardware.org/?probe=29ec19d38e) | Nov 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [997ffc40f0](https://linux-hardware.org/?probe=997ffc40f0) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [efacbf6215](https://linux-hardware.org/?probe=efacbf6215) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [85ac938c0c](https://linux-hardware.org/?probe=85ac938c0c) | Nov 29, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [96b383097b](https://linux-hardware.org/?probe=96b383097b) | Nov 29, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | Notebook    | [97fda88c7b](https://linux-hardware.org/?probe=97fda88c7b) | Nov 28, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8f8f53c15b](https://linux-hardware.org/?probe=8f8f53c15b) | Nov 27, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ac8f0475f1](https://linux-hardware.org/?probe=ac8f0475f1) | Nov 27, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [669f6eaf1c](https://linux-hardware.org/?probe=669f6eaf1c) | Nov 26, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [b59180988d](https://linux-hardware.org/?probe=b59180988d) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | Notebook    | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [7121172cc6](https://linux-hardware.org/?probe=7121172cc6) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [c150f785ea](https://linux-hardware.org/?probe=c150f785ea) | Nov 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [52b55ea024](https://linux-hardware.org/?probe=52b55ea024) | Nov 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7ea2296eaf](https://linux-hardware.org/?probe=7ea2296eaf) | Nov 21, 2022 |
| AZW           | GTR V01                     | Mini pc     | [2042d4c2c0](https://linux-hardware.org/?probe=2042d4c2c0) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4f36ecd91b](https://linux-hardware.org/?probe=4f36ecd91b) | Nov 19, 2022 |
| ASRock        | Z790 PG Riptide             | Desktop     | [c852740256](https://linux-hardware.org/?probe=c852740256) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3534f07f4a](https://linux-hardware.org/?probe=3534f07f4a) | Nov 18, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [86a2f7caea](https://linux-hardware.org/?probe=86a2f7caea) | Nov 18, 2022 |
| Dell          | Latitude 5310               | Notebook    | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | Notebook    | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [4c5a2a2f55](https://linux-hardware.org/?probe=4c5a2a2f55) | Nov 16, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [e6600fae5a](https://linux-hardware.org/?probe=e6600fae5a) | Nov 16, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [08e4620733](https://linux-hardware.org/?probe=08e4620733) | Nov 13, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0bc3c759d6](https://linux-hardware.org/?probe=0bc3c759d6) | Nov 13, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [557fb98d98](https://linux-hardware.org/?probe=557fb98d98) | Nov 13, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [091c048c2a](https://linux-hardware.org/?probe=091c048c2a) | Nov 12, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [8dee2ceeb0](https://linux-hardware.org/?probe=8dee2ceeb0) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [48f127b453](https://linux-hardware.org/?probe=48f127b453) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [fae66184f2](https://linux-hardware.org/?probe=fae66184f2) | Nov 10, 2022 |
| ASUSTek       | U36SD                       | Notebook    | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [ed07b564ec](https://linux-hardware.org/?probe=ed07b564ec) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| HP            | 828A                        | Desktop     | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [92c837ff5a](https://linux-hardware.org/?probe=92c837ff5a) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [298819594a](https://linux-hardware.org/?probe=298819594a) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [2765ed4857](https://linux-hardware.org/?probe=2765ed4857) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [dd2877fcc2](https://linux-hardware.org/?probe=dd2877fcc2) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [d95735860b](https://linux-hardware.org/?probe=d95735860b) | Nov 05, 2022 |
| Acer          | Predator G3610              | Desktop     | [783c053a62](https://linux-hardware.org/?probe=783c053a62) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ad1ae18c98](https://linux-hardware.org/?probe=ad1ae18c98) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [df00a6281b](https://linux-hardware.org/?probe=df00a6281b) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [2ec155a4b6](https://linux-hardware.org/?probe=2ec155a4b6) | Nov 03, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [72467c5d61](https://linux-hardware.org/?probe=72467c5d61) | Oct 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d99707ef15](https://linux-hardware.org/?probe=d99707ef15) | Oct 29, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [063675c104](https://linux-hardware.org/?probe=063675c104) | Oct 29, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e51ca052ec](https://linux-hardware.org/?probe=e51ca052ec) | Oct 28, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [cd6e5e2095](https://linux-hardware.org/?probe=cd6e5e2095) | Oct 27, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [3c67c8efb7](https://linux-hardware.org/?probe=3c67c8efb7) | Oct 27, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [f95081e76e](https://linux-hardware.org/?probe=f95081e76e) | Oct 27, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [0fcfd33f95](https://linux-hardware.org/?probe=0fcfd33f95) | Oct 27, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [51cf8b4f9d](https://linux-hardware.org/?probe=51cf8b4f9d) | Oct 25, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | 2B05                        | Desktop     | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [8f3fdb4d9c](https://linux-hardware.org/?probe=8f3fdb4d9c) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f3ac5bf3df](https://linux-hardware.org/?probe=f3ac5bf3df) | Oct 20, 2022 |
| HP            | 8056                        | Desktop     | [37ed8a6b64](https://linux-hardware.org/?probe=37ed8a6b64) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d727afe327](https://linux-hardware.org/?probe=d727afe327) | Oct 17, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [4138cb5064](https://linux-hardware.org/?probe=4138cb5064) | Oct 17, 2022 |
| HP            | 2AE2                        | Desktop     | [a1a8fcfe49](https://linux-hardware.org/?probe=a1a8fcfe49) | Oct 17, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [2438851671](https://linux-hardware.org/?probe=2438851671) | Oct 16, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [10a3014c1a](https://linux-hardware.org/?probe=10a3014c1a) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [8457aa21e7](https://linux-hardware.org/?probe=8457aa21e7) | Oct 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [4f52cb1040](https://linux-hardware.org/?probe=4f52cb1040) | Oct 15, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [689281cab0](https://linux-hardware.org/?probe=689281cab0) | Oct 15, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Acer          | Aspire 8950G                | Notebook    | [8888f23e03](https://linux-hardware.org/?probe=8888f23e03) | Oct 14, 2022 |
| Lenovo        | ThinkPad E595 20NF001HMX    | Notebook    | [1ae4e8967a](https://linux-hardware.org/?probe=1ae4e8967a) | Oct 14, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | Desktop     | [89060aa147](https://linux-hardware.org/?probe=89060aa147) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [10ea852e71](https://linux-hardware.org/?probe=10ea852e71) | Oct 12, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [27b7798784](https://linux-hardware.org/?probe=27b7798784) | Oct 11, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [ef1a363500](https://linux-hardware.org/?probe=ef1a363500) | Oct 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c52e60caae](https://linux-hardware.org/?probe=c52e60caae) | Oct 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [92704e062f](https://linux-hardware.org/?probe=92704e062f) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [28d49251c7](https://linux-hardware.org/?probe=28d49251c7) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [16a6152e10](https://linux-hardware.org/?probe=16a6152e10) | Oct 02, 2022 |
| Dell          | Latitude E6320              | Notebook    | [69290cc372](https://linux-hardware.org/?probe=69290cc372) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9d5f38913b](https://linux-hardware.org/?probe=9d5f38913b) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [37a7291916](https://linux-hardware.org/?probe=37a7291916) | Sep 29, 2022 |
| HP            | 18E5                        | Desktop     | [bcc9927d20](https://linux-hardware.org/?probe=bcc9927d20) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [6f9bc0cdba](https://linux-hardware.org/?probe=6f9bc0cdba) | Sep 26, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d65cd8309b](https://linux-hardware.org/?probe=d65cd8309b) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a037b1ec8f](https://linux-hardware.org/?probe=a037b1ec8f) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0290975708](https://linux-hardware.org/?probe=0290975708) | Sep 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [8f29c3dc10](https://linux-hardware.org/?probe=8f29c3dc10) | Sep 24, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a68d3f20eb](https://linux-hardware.org/?probe=a68d3f20eb) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Lenovo        | Yoga 13sACN 2021 82CY       | Notebook    | [d374a74e0d](https://linux-hardware.org/?probe=d374a74e0d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [5ed0ffde54](https://linux-hardware.org/?probe=5ed0ffde54) | Sep 22, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1bec04d42d](https://linux-hardware.org/?probe=1bec04d42d) | Sep 21, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b35ec1a833](https://linux-hardware.org/?probe=b35ec1a833) | Sep 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [a5f3f12174](https://linux-hardware.org/?probe=a5f3f12174) | Sep 20, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [af2eb79f4c](https://linux-hardware.org/?probe=af2eb79f4c) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| HP            | 2B05                        | Desktop     | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4995ae034f](https://linux-hardware.org/?probe=4995ae034f) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4bf59d7938](https://linux-hardware.org/?probe=4bf59d7938) | Sep 19, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1d4585c98a](https://linux-hardware.org/?probe=1d4585c98a) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [e85965bc82](https://linux-hardware.org/?probe=e85965bc82) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [0278cf2e45](https://linux-hardware.org/?probe=0278cf2e45) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [52fd47ee14](https://linux-hardware.org/?probe=52fd47ee14) | Sep 15, 2022 |
| Dell          | Latitude 7300               | Notebook    | [9802315270](https://linux-hardware.org/?probe=9802315270) | Sep 14, 2022 |
| Dell          | Latitude 7300               | Notebook    | [5d82c4da95](https://linux-hardware.org/?probe=5d82c4da95) | Sep 14, 2022 |
| HP            | 1497                        | Desktop     | [7d44fed5d5](https://linux-hardware.org/?probe=7d44fed5d5) | Sep 13, 2022 |
| HP            | 1497                        | Desktop     | [3afd83b18b](https://linux-hardware.org/?probe=3afd83b18b) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | Notebook    | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [5987ef39e4](https://linux-hardware.org/?probe=5987ef39e4) | Sep 11, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [e77359618c](https://linux-hardware.org/?probe=e77359618c) | Sep 09, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [cf5955c3e1](https://linux-hardware.org/?probe=cf5955c3e1) | Sep 09, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [f6981692e0](https://linux-hardware.org/?probe=f6981692e0) | Sep 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| Rockchip      | Unknown                     | Soc         | [37447111b3](https://linux-hardware.org/?probe=37447111b3) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [308047a7cb](https://linux-hardware.org/?probe=308047a7cb) | Sep 07, 2022 |
| Acer          | 1.0                         | Desktop     | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b1edd48233](https://linux-hardware.org/?probe=b1edd48233) | Sep 05, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [a8d726946f](https://linux-hardware.org/?probe=a8d726946f) | Sep 04, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [3f17eeffec](https://linux-hardware.org/?probe=3f17eeffec) | Sep 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [30994e1857](https://linux-hardware.org/?probe=30994e1857) | Sep 03, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [4080f853b6](https://linux-hardware.org/?probe=4080f853b6) | Sep 03, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d54fe6c0ea](https://linux-hardware.org/?probe=d54fe6c0ea) | Sep 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [47dbe77b54](https://linux-hardware.org/?probe=47dbe77b54) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| Purism        | Librem 14                   | Notebook    | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| HP            | 18E5                        | Desktop     | [e7c5ab6cc4](https://linux-hardware.org/?probe=e7c5ab6cc4) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| HP            | Pavilion 15                 | Notebook    | [19c7cae23c](https://linux-hardware.org/?probe=19c7cae23c) | Aug 31, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [a23b1b0822](https://linux-hardware.org/?probe=a23b1b0822) | Aug 30, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce2bb0938b](https://linux-hardware.org/?probe=ce2bb0938b) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [61b05137a7](https://linux-hardware.org/?probe=61b05137a7) | Aug 26, 2022 |
| ASRock        | X99 WS                      | Desktop     | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| Foxconn       | P35A01                      | Desktop     | [fa220f1ce6](https://linux-hardware.org/?probe=fa220f1ce6) | Aug 25, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [b19844ee21](https://linux-hardware.org/?probe=b19844ee21) | Aug 25, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [6fcc3e058d](https://linux-hardware.org/?probe=6fcc3e058d) | Aug 22, 2022 |
| ASUSTek       | B150M-A                     | Desktop     | [0dac247b92](https://linux-hardware.org/?probe=0dac247b92) | Aug 21, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | Notebook    | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87fcf5d702](https://linux-hardware.org/?probe=87fcf5d702) | Aug 19, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [0271f9018f](https://linux-hardware.org/?probe=0271f9018f) | Aug 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e2a8c815e](https://linux-hardware.org/?probe=1e2a8c815e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ddc9a7396e](https://linux-hardware.org/?probe=ddc9a7396e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef1cbed5a4](https://linux-hardware.org/?probe=ef1cbed5a4) | Aug 16, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [63d41691ef](https://linux-hardware.org/?probe=63d41691ef) | Aug 15, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [837159c07a](https://linux-hardware.org/?probe=837159c07a) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [6dab67810d](https://linux-hardware.org/?probe=6dab67810d) | Aug 14, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [0b62c9a78f](https://linux-hardware.org/?probe=0b62c9a78f) | Aug 12, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [2487f351d2](https://linux-hardware.org/?probe=2487f351d2) | Aug 12, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [1091d27582](https://linux-hardware.org/?probe=1091d27582) | Aug 11, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [34938e0949](https://linux-hardware.org/?probe=34938e0949) | Aug 11, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [edf947ace6](https://linux-hardware.org/?probe=edf947ace6) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [3fbc687842](https://linux-hardware.org/?probe=3fbc687842) | Aug 08, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [c530c6e2cb](https://linux-hardware.org/?probe=c530c6e2cb) | Aug 08, 2022 |
| HP            | 304Bh                       | Desktop     | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f91ebc68e8](https://linux-hardware.org/?probe=f91ebc68e8) | Aug 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [b075418a73](https://linux-hardware.org/?probe=b075418a73) | Aug 07, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | Notebook    | [091235281e](https://linux-hardware.org/?probe=091235281e) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a0f4d75db6](https://linux-hardware.org/?probe=a0f4d75db6) | Aug 06, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | Notebook    | [431684d65c](https://linux-hardware.org/?probe=431684d65c) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Samsung       | 700G7C                      | Notebook    | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Dell          | Precision 14 5470           | Notebook    | [089d1a151f](https://linux-hardware.org/?probe=089d1a151f) | Aug 03, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [c52a590c5b](https://linux-hardware.org/?probe=c52a590c5b) | Aug 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [64a21844e4](https://linux-hardware.org/?probe=64a21844e4) | Aug 01, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [249d407b66](https://linux-hardware.org/?probe=249d407b66) | Jul 30, 2022 |
| Dell          | 0TP412                      | Desktop     | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [edd98c5418](https://linux-hardware.org/?probe=edd98c5418) | Jul 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3b661517b1](https://linux-hardware.org/?probe=3b661517b1) | Jul 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4fa56bac04](https://linux-hardware.org/?probe=4fa56bac04) | Jul 29, 2022 |
| HP            | 18E7                        | Desktop     | [3d7c1549eb](https://linux-hardware.org/?probe=3d7c1549eb) | Jul 29, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [32c295bae1](https://linux-hardware.org/?probe=32c295bae1) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c3f34f2c91](https://linux-hardware.org/?probe=c3f34f2c91) | Jul 28, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| Acer          | Aspire X1930                | Desktop     | [6a650f512e](https://linux-hardware.org/?probe=6a650f512e) | Jul 27, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [b3df887fe1](https://linux-hardware.org/?probe=b3df887fe1) | Jul 27, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5b4bccdf27](https://linux-hardware.org/?probe=5b4bccdf27) | Jul 27, 2022 |
| ASUSTek       | ZenBook UX325UA             | Notebook    | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [960fefaee7](https://linux-hardware.org/?probe=960fefaee7) | Jul 25, 2022 |
| Dell          | Precision 7560              | Notebook    | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | Notebook    | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| Gigabyte      | Z390 M-CF                   | Desktop     | [ae2926d93e](https://linux-hardware.org/?probe=ae2926d93e) | Jul 24, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [e29f39ad9e](https://linux-hardware.org/?probe=e29f39ad9e) | Jul 23, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [65c50de21a](https://linux-hardware.org/?probe=65c50de21a) | Jul 22, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [6dba304ba4](https://linux-hardware.org/?probe=6dba304ba4) | Jul 22, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [efd71c663d](https://linux-hardware.org/?probe=efd71c663d) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Toshiba       | BLB                         | Notebook    | [997a7c93d7](https://linux-hardware.org/?probe=997a7c93d7) | Jul 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | Precision 7760              | Notebook    | [742cb747ef](https://linux-hardware.org/?probe=742cb747ef) | Jul 20, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [31471e3583](https://linux-hardware.org/?probe=31471e3583) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| Dell          | Precision 3561              | Notebook    | [7dfa6ede1e](https://linux-hardware.org/?probe=7dfa6ede1e) | Jul 18, 2022 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [ba6f405592](https://linux-hardware.org/?probe=ba6f405592) | Jul 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [fb9a47e37f](https://linux-hardware.org/?probe=fb9a47e37f) | Jul 17, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [66fe37549d](https://linux-hardware.org/?probe=66fe37549d) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86ac444b35](https://linux-hardware.org/?probe=86ac444b35) | Jul 15, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9da64b4efa](https://linux-hardware.org/?probe=9da64b4efa) | Jul 14, 2022 |
| Star Labs     | StarBook                    | Notebook    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [235fc9b289](https://linux-hardware.org/?probe=235fc9b289) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [a42efbead1](https://linux-hardware.org/?probe=a42efbead1) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [8d8610ee4f](https://linux-hardware.org/?probe=8d8610ee4f) | Jul 11, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [4dba0dc5ab](https://linux-hardware.org/?probe=4dba0dc5ab) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [0e13eaa824](https://linux-hardware.org/?probe=0e13eaa824) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | Precision 5570              | Notebook    | [e4409961fd](https://linux-hardware.org/?probe=e4409961fd) | Jul 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [dcbdde4fdf](https://linux-hardware.org/?probe=dcbdde4fdf) | Jul 06, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [36aca635a8](https://linux-hardware.org/?probe=36aca635a8) | Jul 06, 2022 |
| MSI           | MS-AA71                     | All in one  | [4e7d1d05d6](https://linux-hardware.org/?probe=4e7d1d05d6) | Jul 06, 2022 |
| Dell          | 0GM819                      | Desktop     | [a366983f6a](https://linux-hardware.org/?probe=a366983f6a) | Jul 06, 2022 |
| Dell          | 0GM819                      | Desktop     | [78e233e42f](https://linux-hardware.org/?probe=78e233e42f) | Jul 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [fad2fe7297](https://linux-hardware.org/?probe=fad2fe7297) | Jul 04, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [848a8591de](https://linux-hardware.org/?probe=848a8591de) | Jul 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [0cb6549f23](https://linux-hardware.org/?probe=0cb6549f23) | Jun 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0f4c661912](https://linux-hardware.org/?probe=0f4c661912) | Jun 27, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5dd67bc68a](https://linux-hardware.org/?probe=5dd67bc68a) | Jun 25, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [57660d8f0f](https://linux-hardware.org/?probe=57660d8f0f) | Jun 24, 2022 |
| ASUSTek       | N61Vn                       | Notebook    | [72d62f755d](https://linux-hardware.org/?probe=72d62f755d) | Jun 24, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [cfa8a05299](https://linux-hardware.org/?probe=cfa8a05299) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [5188bfb9d3](https://linux-hardware.org/?probe=5188bfb9d3) | Jun 23, 2022 |
| HP            | 2B05                        | Desktop     | [677bb9d569](https://linux-hardware.org/?probe=677bb9d569) | Jun 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [273f19137a](https://linux-hardware.org/?probe=273f19137a) | Jun 21, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [07506542b5](https://linux-hardware.org/?probe=07506542b5) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | Desktop     | [280d4af2d2](https://linux-hardware.org/?probe=280d4af2d2) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | Desktop     | [c90adf6d43](https://linux-hardware.org/?probe=c90adf6d43) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [af5bb55ac5](https://linux-hardware.org/?probe=af5bb55ac5) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| HP            | 2B05                        | Desktop     | [a49ebb4aed](https://linux-hardware.org/?probe=a49ebb4aed) | Jun 19, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [5448ad3e33](https://linux-hardware.org/?probe=5448ad3e33) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [f76be8391b](https://linux-hardware.org/?probe=f76be8391b) | Jun 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [530c081484](https://linux-hardware.org/?probe=530c081484) | Jun 17, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [f75b5004f9](https://linux-hardware.org/?probe=f75b5004f9) | Jun 17, 2022 |
| Gigabyte      | H67M-UD2H-B3                | Desktop     | [1c8dd20713](https://linux-hardware.org/?probe=1c8dd20713) | Jun 16, 2022 |
| Acer          | Aspire TC-230               | Desktop     | [bec506a849](https://linux-hardware.org/?probe=bec506a849) | Jun 16, 2022 |
| Acer          | Predator G3610              | Desktop     | [ff347cdb53](https://linux-hardware.org/?probe=ff347cdb53) | Jun 15, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [fe963bacc6](https://linux-hardware.org/?probe=fe963bacc6) | Jun 14, 2022 |
| congatec      | conga-PA7 A.0               | Mini pc     | [e0c6234f77](https://linux-hardware.org/?probe=e0c6234f77) | Jun 13, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [8153e1c68e](https://linux-hardware.org/?probe=8153e1c68e) | Jun 13, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [12fb5f93c9](https://linux-hardware.org/?probe=12fb5f93c9) | Jun 13, 2022 |
| Dell          | Precision 7520              | Notebook    | [002f7ce017](https://linux-hardware.org/?probe=002f7ce017) | Jun 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [d9cffc5cc6](https://linux-hardware.org/?probe=d9cffc5cc6) | Jun 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63dcba0c57](https://linux-hardware.org/?probe=63dcba0c57) | Jun 10, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [884806d49f](https://linux-hardware.org/?probe=884806d49f) | Jun 09, 2022 |
| Acer          | Aspire 5749Z                | Notebook    | [d7020510e2](https://linux-hardware.org/?probe=d7020510e2) | Jun 08, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [3de14e06c5](https://linux-hardware.org/?probe=3de14e06c5) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [685df41f04](https://linux-hardware.org/?probe=685df41f04) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ba86261552](https://linux-hardware.org/?probe=ba86261552) | Jun 06, 2022 |
| Intel         | NUC11TNBi7 M11895-402       | Mini pc     | [4b972d5b22](https://linux-hardware.org/?probe=4b972d5b22) | Jun 05, 2022 |
| Dell          | Latitude D630               | Notebook    | [fb28805860](https://linux-hardware.org/?probe=fb28805860) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [dc7a83708a](https://linux-hardware.org/?probe=dc7a83708a) | Jun 04, 2022 |
| HP            | ProBook 6450b               | Notebook    | [52467822a6](https://linux-hardware.org/?probe=52467822a6) | Jun 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [b414c22d34](https://linux-hardware.org/?probe=b414c22d34) | Jun 02, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [90b0bc8a37](https://linux-hardware.org/?probe=90b0bc8a37) | Jun 02, 2022 |
| HP            | ProBook 6450b               | Notebook    | [26bce40d20](https://linux-hardware.org/?probe=26bce40d20) | Jun 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [e3c9cca7e1](https://linux-hardware.org/?probe=e3c9cca7e1) | Jun 01, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f4906f3799](https://linux-hardware.org/?probe=f4906f3799) | Jun 01, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [860be26e14](https://linux-hardware.org/?probe=860be26e14) | May 29, 2022 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [63747954e9](https://linux-hardware.org/?probe=63747954e9) | May 29, 2022 |
| Lenovo        | ThinkPad W500 4061W8H       | Notebook    | [db9160e089](https://linux-hardware.org/?probe=db9160e089) | May 29, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [bd97a6b3dd](https://linux-hardware.org/?probe=bd97a6b3dd) | May 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [b32a949b01](https://linux-hardware.org/?probe=b32a949b01) | May 28, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e64dfe3f6f](https://linux-hardware.org/?probe=e64dfe3f6f) | May 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [8f40318937](https://linux-hardware.org/?probe=8f40318937) | May 27, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c025e27a90](https://linux-hardware.org/?probe=c025e27a90) | May 27, 2022 |
| ASUSTek       | U31Jg                       | Notebook    | [b761173e5e](https://linux-hardware.org/?probe=b761173e5e) | May 26, 2022 |
| Fujitsu       | CELSIUS H730                | Notebook    | [6f0b24d450](https://linux-hardware.org/?probe=6f0b24d450) | May 26, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [25e4d08ac2](https://linux-hardware.org/?probe=25e4d08ac2) | May 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [2d28231751](https://linux-hardware.org/?probe=2d28231751) | May 25, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c00f6e1b2a](https://linux-hardware.org/?probe=c00f6e1b2a) | May 24, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [683ff3ab1a](https://linux-hardware.org/?probe=683ff3ab1a) | May 24, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [594e42160c](https://linux-hardware.org/?probe=594e42160c) | May 22, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b620a51628](https://linux-hardware.org/?probe=b620a51628) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Gigabyte      | H67N-USB3-B3                | Desktop     | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| HP            | 635                         | Notebook    | [2421582549](https://linux-hardware.org/?probe=2421582549) | May 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f02fa869ff](https://linux-hardware.org/?probe=f02fa869ff) | May 20, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [bdc2dbdba3](https://linux-hardware.org/?probe=bdc2dbdba3) | May 19, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [97e7c3fd74](https://linux-hardware.org/?probe=97e7c3fd74) | May 19, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a1cbc8b911](https://linux-hardware.org/?probe=a1cbc8b911) | May 19, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [736bd1ab68](https://linux-hardware.org/?probe=736bd1ab68) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [6c41f73e8a](https://linux-hardware.org/?probe=6c41f73e8a) | May 18, 2022 |
| HP            | 635                         | Notebook    | [3168b50a90](https://linux-hardware.org/?probe=3168b50a90) | May 18, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ceb6a7e5a3](https://linux-hardware.org/?probe=ceb6a7e5a3) | May 16, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [5c4ebc223f](https://linux-hardware.org/?probe=5c4ebc223f) | May 16, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [efd77955ef](https://linux-hardware.org/?probe=efd77955ef) | May 15, 2022 |
| MSI           | GS73VR 7RG                  | Notebook    | [3815425b08](https://linux-hardware.org/?probe=3815425b08) | May 15, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [70809098f6](https://linux-hardware.org/?probe=70809098f6) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [7f06d07456](https://linux-hardware.org/?probe=7f06d07456) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [a9c9d7da8d](https://linux-hardware.org/?probe=a9c9d7da8d) | May 14, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [bfcd03ba86](https://linux-hardware.org/?probe=bfcd03ba86) | May 14, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [2152787c64](https://linux-hardware.org/?probe=2152787c64) | May 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [235beb3d5f](https://linux-hardware.org/?probe=235beb3d5f) | May 13, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [6f09e11de7](https://linux-hardware.org/?probe=6f09e11de7) | May 12, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [cff8de13ce](https://linux-hardware.org/?probe=cff8de13ce) | May 12, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [ebf71be1f5](https://linux-hardware.org/?probe=ebf71be1f5) | May 12, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [a80ef1636d](https://linux-hardware.org/?probe=a80ef1636d) | May 12, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2342a9d519](https://linux-hardware.org/?probe=2342a9d519) | May 12, 2022 |
| ASUSTek       | A6U                         | Notebook    | [4a8ad00e5e](https://linux-hardware.org/?probe=4a8ad00e5e) | May 12, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [38bc924977](https://linux-hardware.org/?probe=38bc924977) | May 12, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [9f28ef42a4](https://linux-hardware.org/?probe=9f28ef42a4) | May 11, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [6a69aab6ee](https://linux-hardware.org/?probe=6a69aab6ee) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5b6165bc68](https://linux-hardware.org/?probe=5b6165bc68) | May 10, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [0bec73d852](https://linux-hardware.org/?probe=0bec73d852) | May 10, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [56c5f8cad8](https://linux-hardware.org/?probe=56c5f8cad8) | May 09, 2022 |
| Lenovo        | ThinkPad X270 20HMS27Q00    | Notebook    | [615d6650a0](https://linux-hardware.org/?probe=615d6650a0) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | Notebook    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [ba413ad853](https://linux-hardware.org/?probe=ba413ad853) | May 08, 2022 |
| Samsung       | 750XDA                      | Notebook    | [466689475e](https://linux-hardware.org/?probe=466689475e) | May 07, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [6fc7c6f086](https://linux-hardware.org/?probe=6fc7c6f086) | May 07, 2022 |
| Dell          | Precision M4700             | Notebook    | [81cc8ba45c](https://linux-hardware.org/?probe=81cc8ba45c) | May 06, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [be200c9e57](https://linux-hardware.org/?probe=be200c9e57) | May 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [64eb136705](https://linux-hardware.org/?probe=64eb136705) | May 03, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e2dfdb6af2](https://linux-hardware.org/?probe=e2dfdb6af2) | May 03, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [1bd7f7cd93](https://linux-hardware.org/?probe=1bd7f7cd93) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [1c3645cb67](https://linux-hardware.org/?probe=1c3645cb67) | May 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [f6cc5e2ad5](https://linux-hardware.org/?probe=f6cc5e2ad5) | May 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [adc0bdd7f8](https://linux-hardware.org/?probe=adc0bdd7f8) | May 01, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [e8fee79ec7](https://linux-hardware.org/?probe=e8fee79ec7) | Apr 30, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [995ea9538b](https://linux-hardware.org/?probe=995ea9538b) | Apr 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| ASUSTek       | B150M-A                     | Desktop     | [fa213f6681](https://linux-hardware.org/?probe=fa213f6681) | Apr 28, 2022 |
| Gigabyte      | H67M-UD2H-B3                | Desktop     | [7defbcb7bb](https://linux-hardware.org/?probe=7defbcb7bb) | Apr 28, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | Notebook    | [58076aa8e9](https://linux-hardware.org/?probe=58076aa8e9) | Apr 28, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [37b195945a](https://linux-hardware.org/?probe=37b195945a) | Apr 28, 2022 |
| Dell          | Latitude 7420               | Notebook    | [8e3bcab404](https://linux-hardware.org/?probe=8e3bcab404) | Apr 28, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [11a6c8f173](https://linux-hardware.org/?probe=11a6c8f173) | Apr 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [3b4a331875](https://linux-hardware.org/?probe=3b4a331875) | Apr 26, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | Notebook    | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [8cba4892be](https://linux-hardware.org/?probe=8cba4892be) | Apr 25, 2022 |
| ASUSTek       | UX461UN                     | Convertible | [57bbbf3023](https://linux-hardware.org/?probe=57bbbf3023) | Apr 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [c0af99fa7e](https://linux-hardware.org/?probe=c0af99fa7e) | Apr 24, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [6cc8c69a6c](https://linux-hardware.org/?probe=6cc8c69a6c) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS3FX0... | Notebook    | [00d3556f08](https://linux-hardware.org/?probe=00d3556f08) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | 18E9                        | Desktop     | [36ff483a2f](https://linux-hardware.org/?probe=36ff483a2f) | Apr 23, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [cd369fb3e3](https://linux-hardware.org/?probe=cd369fb3e3) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [4548a301f8](https://linux-hardware.org/?probe=4548a301f8) | Apr 22, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [757b005814](https://linux-hardware.org/?probe=757b005814) | Apr 21, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [ca406cf975](https://linux-hardware.org/?probe=ca406cf975) | Apr 21, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [32d9d8c8df](https://linux-hardware.org/?probe=32d9d8c8df) | Apr 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [94e43177eb](https://linux-hardware.org/?probe=94e43177eb) | Apr 21, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4c46fa8a5b](https://linux-hardware.org/?probe=4c46fa8a5b) | Apr 19, 2022 |
| ASUSTek       | G551JW                      | Notebook    | [b0d7f099f5](https://linux-hardware.org/?probe=b0d7f099f5) | Apr 18, 2022 |
| Lenovo        | ThinkPad X131e 33683YG      | Notebook    | [7855e19861](https://linux-hardware.org/?probe=7855e19861) | Apr 17, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ce158f41e2](https://linux-hardware.org/?probe=ce158f41e2) | Apr 17, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [5bd64f9988](https://linux-hardware.org/?probe=5bd64f9988) | Apr 17, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| Toshiba       | BLB                         | Notebook    | [903779c2b2](https://linux-hardware.org/?probe=903779c2b2) | Apr 16, 2022 |
| Toshiba       | BLB                         | Notebook    | [1dffc347dd](https://linux-hardware.org/?probe=1dffc347dd) | Apr 16, 2022 |
| MSI           | 990FXA-GD80                 | Desktop     | [391705d3c1](https://linux-hardware.org/?probe=391705d3c1) | Apr 15, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [c42de00504](https://linux-hardware.org/?probe=c42de00504) | Apr 15, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [8994d0ea9f](https://linux-hardware.org/?probe=8994d0ea9f) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | Notebook    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| Dell          | Latitude E7450              | Notebook    | [9af0006104](https://linux-hardware.org/?probe=9af0006104) | Apr 15, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [b2fdf48a7f](https://linux-hardware.org/?probe=b2fdf48a7f) | Apr 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [dba38dc289](https://linux-hardware.org/?probe=dba38dc289) | Apr 13, 2022 |
| HP            | 18E5                        | Desktop     | [3b4f9e8525](https://linux-hardware.org/?probe=3b4f9e8525) | Apr 13, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [ca14d0eb57](https://linux-hardware.org/?probe=ca14d0eb57) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [0056c8d32e](https://linux-hardware.org/?probe=0056c8d32e) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [68aa564b9f](https://linux-hardware.org/?probe=68aa564b9f) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [d9f1aff70a](https://linux-hardware.org/?probe=d9f1aff70a) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [b9b9565fae](https://linux-hardware.org/?probe=b9b9565fae) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | Notebook    | [8fdcef45a9](https://linux-hardware.org/?probe=8fdcef45a9) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ce0316a106](https://linux-hardware.org/?probe=ce0316a106) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [70e4d389af](https://linux-hardware.org/?probe=70e4d389af) | Apr 10, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [ffcbeed952](https://linux-hardware.org/?probe=ffcbeed952) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Maxtang       | FP30 V1.0                   | Desktop     | [2062d8578e](https://linux-hardware.org/?probe=2062d8578e) | Apr 08, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [16fa67b6c1](https://linux-hardware.org/?probe=16fa67b6c1) | Apr 07, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [fca3b357c3](https://linux-hardware.org/?probe=fca3b357c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f4c5281aa9](https://linux-hardware.org/?probe=f4c5281aa9) | Apr 07, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [1c62a4c421](https://linux-hardware.org/?probe=1c62a4c421) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [53e59cf805](https://linux-hardware.org/?probe=53e59cf805) | Apr 06, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [68397184cf](https://linux-hardware.org/?probe=68397184cf) | Apr 06, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [f3bc34e630](https://linux-hardware.org/?probe=f3bc34e630) | Apr 05, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [31836fcaa9](https://linux-hardware.org/?probe=31836fcaa9) | Apr 05, 2022 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [4361e01e42](https://linux-hardware.org/?probe=4361e01e42) | Apr 04, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [2af47af588](https://linux-hardware.org/?probe=2af47af588) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [3e01b6fb25](https://linux-hardware.org/?probe=3e01b6fb25) | Apr 03, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [bcff3a3aef](https://linux-hardware.org/?probe=bcff3a3aef) | Apr 03, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [893945236a](https://linux-hardware.org/?probe=893945236a) | Apr 03, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [b3a74c237d](https://linux-hardware.org/?probe=b3a74c237d) | Apr 02, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [01a521b3d1](https://linux-hardware.org/?probe=01a521b3d1) | Apr 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2d4957c88f](https://linux-hardware.org/?probe=2d4957c88f) | Apr 02, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [0b247aa185](https://linux-hardware.org/?probe=0b247aa185) | Mar 30, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [137477b9ef](https://linux-hardware.org/?probe=137477b9ef) | Mar 29, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [3a33018680](https://linux-hardware.org/?probe=3a33018680) | Mar 29, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [4ab227f4be](https://linux-hardware.org/?probe=4ab227f4be) | Mar 29, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [e4c1632bc2](https://linux-hardware.org/?probe=e4c1632bc2) | Mar 28, 2022 |
| Dell          | Precision 5540              | Notebook    | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [d5f059e17d](https://linux-hardware.org/?probe=d5f059e17d) | Mar 26, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [f625382909](https://linux-hardware.org/?probe=f625382909) | Mar 26, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e534bb83a](https://linux-hardware.org/?probe=4e534bb83a) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d08bb2f15b](https://linux-hardware.org/?probe=d08bb2f15b) | Mar 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6af3c57a8a](https://linux-hardware.org/?probe=6af3c57a8a) | Mar 24, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [9f295312dc](https://linux-hardware.org/?probe=9f295312dc) | Mar 21, 2022 |
| Dell          | Latitude 7300               | Notebook    | [751dc53e2b](https://linux-hardware.org/?probe=751dc53e2b) | Mar 20, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [b312650d8d](https://linux-hardware.org/?probe=b312650d8d) | Mar 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [4191a185d4](https://linux-hardware.org/?probe=4191a185d4) | Mar 19, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [f71ac898a8](https://linux-hardware.org/?probe=f71ac898a8) | Mar 19, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [2b46add19f](https://linux-hardware.org/?probe=2b46add19f) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK E546               | Notebook    | [247dd3e47c](https://linux-hardware.org/?probe=247dd3e47c) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | Notebook    | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [21c958ad5f](https://linux-hardware.org/?probe=21c958ad5f) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f9345bd168](https://linux-hardware.org/?probe=f9345bd168) | Mar 12, 2022 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | Desktop     | [e6c507dff4](https://linux-hardware.org/?probe=e6c507dff4) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [84e80f8c56](https://linux-hardware.org/?probe=84e80f8c56) | Mar 12, 2022 |
| ASUSTek       | G11CD-K                     | Desktop     | [f3347643b0](https://linux-hardware.org/?probe=f3347643b0) | Mar 12, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [d7c05bb862](https://linux-hardware.org/?probe=d7c05bb862) | Mar 11, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c4d9b11074](https://linux-hardware.org/?probe=c4d9b11074) | Mar 10, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [8b499a7b72](https://linux-hardware.org/?probe=8b499a7b72) | Mar 08, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3e4ac3a045](https://linux-hardware.org/?probe=3e4ac3a045) | Mar 07, 2022 |
| HP            | ENVY 15                     | Notebook    | [a4f5eedd3c](https://linux-hardware.org/?probe=a4f5eedd3c) | Mar 06, 2022 |
| ASUSTek       | E205SA                      | Notebook    | [4c896c9379](https://linux-hardware.org/?probe=4c896c9379) | Mar 05, 2022 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [db85b45bf6](https://linux-hardware.org/?probe=db85b45bf6) | Mar 05, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [c04f6c7365](https://linux-hardware.org/?probe=c04f6c7365) | Mar 05, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [3ff867b4e2](https://linux-hardware.org/?probe=3ff867b4e2) | Mar 05, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | Notebook    | [af4563cb12](https://linux-hardware.org/?probe=af4563cb12) | Mar 04, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [2efd176b6f](https://linux-hardware.org/?probe=2efd176b6f) | Mar 03, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [88a973e27f](https://linux-hardware.org/?probe=88a973e27f) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [d1c5534f6d](https://linux-hardware.org/?probe=d1c5534f6d) | Feb 27, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [2b2338382c](https://linux-hardware.org/?probe=2b2338382c) | Feb 27, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [ff2de5c1da](https://linux-hardware.org/?probe=ff2de5c1da) | Feb 27, 2022 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | Desktop     | [4ae8fd98cc](https://linux-hardware.org/?probe=4ae8fd98cc) | Feb 26, 2022 |
| Sony          | VPCEB36FG                   | Notebook    | [d46f784fbb](https://linux-hardware.org/?probe=d46f784fbb) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [cfd0806662](https://linux-hardware.org/?probe=cfd0806662) | Feb 25, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [1434453fc0](https://linux-hardware.org/?probe=1434453fc0) | Feb 24, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [3bfa40a4c8](https://linux-hardware.org/?probe=3bfa40a4c8) | Feb 24, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1cc7d4542a](https://linux-hardware.org/?probe=1cc7d4542a) | Feb 23, 2022 |
| Elo Touch ... | Geminilake Continental Z... | Desktop     | [6d9bcef1c7](https://linux-hardware.org/?probe=6d9bcef1c7) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [d31201b74c](https://linux-hardware.org/?probe=d31201b74c) | Feb 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [672f08c769](https://linux-hardware.org/?probe=672f08c769) | Feb 22, 2022 |
| HP            | 86C7                        | All in one  | [efb6906a46](https://linux-hardware.org/?probe=efb6906a46) | Feb 21, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [1c3e6a4af1](https://linux-hardware.org/?probe=1c3e6a4af1) | Feb 21, 2022 |
| Dell          | Precision 3510              | Notebook    | [3956ab645b](https://linux-hardware.org/?probe=3956ab645b) | Feb 21, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [d2119e4516](https://linux-hardware.org/?probe=d2119e4516) | Feb 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [129c8a24d9](https://linux-hardware.org/?probe=129c8a24d9) | Feb 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [34117f82de](https://linux-hardware.org/?probe=34117f82de) | Feb 20, 2022 |
| ZEPTO         | ZNOTE                       | Notebook    | [5ff5c2b966](https://linux-hardware.org/?probe=5ff5c2b966) | Feb 20, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [ed1a78c5a6](https://linux-hardware.org/?probe=ed1a78c5a6) | Feb 20, 2022 |
| Dell          | 0P4T42 A01                  | All in one  | [6b8b0ec7f9](https://linux-hardware.org/?probe=6b8b0ec7f9) | Feb 19, 2022 |
| HP            | 3032h                       | Desktop     | [df23e573ba](https://linux-hardware.org/?probe=df23e573ba) | Feb 19, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7b9e4b097d](https://linux-hardware.org/?probe=7b9e4b097d) | Feb 18, 2022 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [b0cf9aa220](https://linux-hardware.org/?probe=b0cf9aa220) | Feb 18, 2022 |
| HP            | Pavilion dv6                | Notebook    | [012e2b5d56](https://linux-hardware.org/?probe=012e2b5d56) | Feb 15, 2022 |
| Dell          | Latitude 5480               | Notebook    | [62ab6cb2c3](https://linux-hardware.org/?probe=62ab6cb2c3) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [cc35d4696d](https://linux-hardware.org/?probe=cc35d4696d) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| HP            | 829A                        | Mini pc     | [dfd0cb667c](https://linux-hardware.org/?probe=dfd0cb667c) | Feb 12, 2022 |
| Dell          | Latitude E6430              | Notebook    | [4b91478aaa](https://linux-hardware.org/?probe=4b91478aaa) | Feb 11, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [0600ea1165](https://linux-hardware.org/?probe=0600ea1165) | Feb 11, 2022 |
| Dell          | Latitude D620               | Notebook    | [dfbcd57dc6](https://linux-hardware.org/?probe=dfbcd57dc6) | Feb 10, 2022 |
| HP            | ENVY 15                     | Notebook    | [91c40a9559](https://linux-hardware.org/?probe=91c40a9559) | Feb 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [8f36d1baac](https://linux-hardware.org/?probe=8f36d1baac) | Feb 08, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [accf5c8a43](https://linux-hardware.org/?probe=accf5c8a43) | Feb 08, 2022 |
| Lenovo        | E31-70 80KX                 | Notebook    | [d4fe754aa4](https://linux-hardware.org/?probe=d4fe754aa4) | Feb 07, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [2427f8c1da](https://linux-hardware.org/?probe=2427f8c1da) | Feb 07, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [386053c3ce](https://linux-hardware.org/?probe=386053c3ce) | Feb 07, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [fbea64f951](https://linux-hardware.org/?probe=fbea64f951) | Feb 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [db7f189b71](https://linux-hardware.org/?probe=db7f189b71) | Feb 06, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [70c2ff9419](https://linux-hardware.org/?probe=70c2ff9419) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [3a8c47094b](https://linux-hardware.org/?probe=3a8c47094b) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [ae06eadc57](https://linux-hardware.org/?probe=ae06eadc57) | Feb 05, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cb34c3126d](https://linux-hardware.org/?probe=cb34c3126d) | Feb 05, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a8cc9c8481](https://linux-hardware.org/?probe=a8cc9c8481) | Feb 03, 2022 |
| Packard Be... | IMEDIA S2985                | Desktop     | [661d923ce2](https://linux-hardware.org/?probe=661d923ce2) | Feb 03, 2022 |
| Dell          | 0773VG A01                  | Desktop     | [b1c8ece218](https://linux-hardware.org/?probe=b1c8ece218) | Feb 03, 2022 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [15419beff9](https://linux-hardware.org/?probe=15419beff9) | Feb 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [c51e8a279f](https://linux-hardware.org/?probe=c51e8a279f) | Feb 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [19cb128817](https://linux-hardware.org/?probe=19cb128817) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [108d91c953](https://linux-hardware.org/?probe=108d91c953) | Feb 02, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [d866cabd88](https://linux-hardware.org/?probe=d866cabd88) | Feb 02, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [a6321e237c](https://linux-hardware.org/?probe=a6321e237c) | Feb 01, 2022 |
| Acer          | Predator G3610              | Desktop     | [126f12bd14](https://linux-hardware.org/?probe=126f12bd14) | Feb 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [bbe17ee442](https://linux-hardware.org/?probe=bbe17ee442) | Jan 31, 2022 |
| ASUSTek       | GR8                         | Notebook    | [1d8f5be27c](https://linux-hardware.org/?probe=1d8f5be27c) | Jan 30, 2022 |
| Linx          | LAMINALTT8W4G-HBN           | Tablet      | [6350a05df4](https://linux-hardware.org/?probe=6350a05df4) | Jan 29, 2022 |
| Linx          | LAMINALTT8W4G-HBN           | Tablet      | [fa389062e6](https://linux-hardware.org/?probe=fa389062e6) | Jan 29, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [a59b4aa98d](https://linux-hardware.org/?probe=a59b4aa98d) | Jan 29, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [fdf21ecdef](https://linux-hardware.org/?probe=fdf21ecdef) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [b584b0b69a](https://linux-hardware.org/?probe=b584b0b69a) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [6b771832b8](https://linux-hardware.org/?probe=6b771832b8) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | Notebook    | [1d8bb5fbe6](https://linux-hardware.org/?probe=1d8bb5fbe6) | Jan 27, 2022 |
| Lenovo        | ThinkPad T420 4236VJ7       | Notebook    | [87aa03d881](https://linux-hardware.org/?probe=87aa03d881) | Jan 27, 2022 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | Desktop     | [a0aecb00c0](https://linux-hardware.org/?probe=a0aecb00c0) | Jan 26, 2022 |
| AAEON         | GENE-BT05 V1.1              | Desktop     | [385d6a7c2e](https://linux-hardware.org/?probe=385d6a7c2e) | Jan 25, 2022 |
| MSI           | B85M-E45                    | Desktop     | [5751d3e736](https://linux-hardware.org/?probe=5751d3e736) | Jan 25, 2022 |
| MSI           | B85M-E45                    | Desktop     | [034f7c3687](https://linux-hardware.org/?probe=034f7c3687) | Jan 25, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [c5c764ccd7](https://linux-hardware.org/?probe=c5c764ccd7) | Jan 24, 2022 |
| Dell          | Latitude E7440              | Notebook    | [74aa958191](https://linux-hardware.org/?probe=74aa958191) | Jan 23, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [e5aea099ea](https://linux-hardware.org/?probe=e5aea099ea) | Jan 23, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [f82cb83a85](https://linux-hardware.org/?probe=f82cb83a85) | Jan 23, 2022 |
| Notebook      | N13xWU                      | Notebook    | [0d615c6812](https://linux-hardware.org/?probe=0d615c6812) | Jan 22, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [2aa2fc8ed9](https://linux-hardware.org/?probe=2aa2fc8ed9) | Jan 22, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [95afa35615](https://linux-hardware.org/?probe=95afa35615) | Jan 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [76ac118b42](https://linux-hardware.org/?probe=76ac118b42) | Jan 20, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [e5b1e0c400](https://linux-hardware.org/?probe=e5b1e0c400) | Jan 20, 2022 |
| Dell          | Inspiron 5721               | Notebook    | [5310b893aa](https://linux-hardware.org/?probe=5310b893aa) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c4103d5c5a](https://linux-hardware.org/?probe=c4103d5c5a) | Jan 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a7cc00f1bb](https://linux-hardware.org/?probe=a7cc00f1bb) | Jan 18, 2022 |
| Dell          | Latitude 7480               | Notebook    | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Acer          | Aspire ES1-111              | Notebook    | [2dfe5563ef](https://linux-hardware.org/?probe=2dfe5563ef) | Jan 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 266       | 13.08%  |
| Ubuntu 18.04                 | 131       | 6.44%   |
| Ubuntu 22.04                 | 117       | 5.76%   |
| Arch Rolling                 | 51        | 2.51%   |
| Pop!_OS 21.04                | 49        | 2.41%   |
| Debian 11                    | 49        | 2.41%   |
| Manjaro                      | 44        | 2.16%   |
| OpenMandriva 4.3             | 40        | 1.97%   |
| Arch                         | 40        | 1.97%   |
| OpenMandriva 4.2             | 39        | 1.92%   |
| KDE neon 20.04               | 38        | 1.87%   |
| Pop!_OS 22.04                | 35        | 1.72%   |
| Zorin 16                     | 30        | 1.48%   |
| Pop!_OS 20.04                | 30        | 1.48%   |
| Ubuntu 21.10                 | 29        | 1.43%   |
| Ubuntu 21.04                 | 29        | 1.43%   |
| Pop!_OS 20.10                | 29        | 1.43%   |
| Linux Mint 20.3              | 29        | 1.43%   |
| Fedora 37                    | 29        | 1.43%   |
| Fedora 35                    | 28        | 1.38%   |
| Ubuntu 19.04                 | 27        | 1.33%   |
| openSUSE Tumbleweed-XXXXXXXX | 26        | 1.28%   |
| Linux Mint 21.1              | 25        | 1.23%   |
| Fedora 34                    | 25        | 1.23%   |
| Ubuntu 19.10                 | 24        | 1.18%   |
| Fedora 36                    | 23        | 1.13%   |
| Fedora 32                    | 23        | 1.13%   |
| ArcoLinux Rolling            | 23        | 1.13%   |
| Zorin 15                     | 21        | 1.03%   |
| Linux Mint 20.2              | 20        | 0.98%   |
| Linux Mint 20                | 20        | 0.98%   |
| Xubuntu 20.04                | 19        | 0.93%   |
| Ubuntu 20.10                 | 19        | 0.93%   |
| Fedora 33                    | 19        | 0.93%   |
| Linux Mint 20.1              | 17        | 0.84%   |
| Fedora 31                    | 15        | 0.74%   |
| Pop!_OS 21.10                | 14        | 0.69%   |
| Debian 10                    | 14        | 0.69%   |
| Gentoo 2.6                   | 13        | 0.64%   |
| Ubuntu 22.10                 | 12        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 644       | 33.11%  |
| Fedora        | 161       | 8.28%   |
| Pop!_OS       | 149       | 7.66%   |
| Linux Mint    | 147       | 7.56%   |
| OpenMandriva  | 101       | 5.19%   |
| Arch          | 90        | 4.63%   |
| Manjaro       | 88        | 4.52%   |
| Debian        | 81        | 4.16%   |
| Zorin         | 51        | 2.62%   |
| KDE neon      | 47        | 2.42%   |
| Xubuntu       | 38        | 1.95%   |
| openSUSE      | 31        | 1.59%   |
| Gentoo        | 28        | 1.44%   |
| ArcoLinux     | 28        | 1.44%   |
| Kubuntu       | 25        | 1.29%   |
| ROSA          | 20        | 1.03%   |
| Kali          | 16        | 0.82%   |
| Ubuntu MATE   | 14        | 0.72%   |
| EndeavourOS   | 14        | 0.72%   |
| Elementary    | 14        | 0.72%   |
| CentOS        | 14        | 0.72%   |
| Endless       | 10        | 0.51%   |
| Clear Linux   | 10        | 0.51%   |
| LMDE          | 8         | 0.41%   |
| Ubuntu Unity  | 7         | 0.36%   |
| SteamOS       | 7         | 0.36%   |
| Ubuntu Budgie | 6         | 0.31%   |
| Peppermint    | 6         | 0.31%   |
| Nobara        | 6         | 0.31%   |
| MX            | 6         | 0.31%   |
| Garuda Linux  | 6         | 0.31%   |
| Solus         | 5         | 0.26%   |
| Lubuntu       | 5         | 0.26%   |
| BunsenLabs    | 5         | 0.26%   |
| Slackware     | 4         | 0.21%   |
| Parrot        | 4         | 0.21%   |
| BlackPanther  | 4         | 0.21%   |
| Alpine        | 4         | 0.21%   |
| Ubuntu Studio | 3         | 0.15%   |
| Raspbian      | 3         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 39        | 1.76%   |
| 5.16.7-desktop-1omv4003  | 38        | 1.71%   |
| 5.4.0-42-generic         | 33        | 1.49%   |
| 5.15.0-56-generic        | 27        | 1.22%   |
| 5.4.0-58-generic         | 21        | 0.95%   |
| 5.4.0-48-generic         | 20        | 0.9%    |
| 5.15.0-52-generic        | 19        | 0.86%   |
| 5.11.0-7620-generic      | 19        | 0.86%   |
| 5.3.0-40-generic         | 17        | 0.77%   |
| 5.13.0-7614-generic      | 17        | 0.77%   |
| 5.4.0-52-generic         | 16        | 0.72%   |
| 5.15.0-46-generic        | 15        | 0.68%   |
| 5.13.0-30-generic        | 15        | 0.68%   |
| 5.4.0-40-generic         | 14        | 0.63%   |
| 5.13.0-39-generic        | 14        | 0.63%   |
| 5.4.0-7634-generic       | 13        | 0.59%   |
| 5.15.0-58-generic        | 13        | 0.59%   |
| 5.15.0-48-generic        | 13        | 0.59%   |
| 5.4.0-54-generic         | 12        | 0.54%   |
| 5.4.0-33-generic         | 12        | 0.54%   |
| 5.11.0-37-generic        | 12        | 0.54%   |
| 5.8.0-48-generic         | 11        | 0.5%    |
| 5.4.0-70-generic         | 11        | 0.5%    |
| 5.19.0-35-generic        | 11        | 0.5%    |
| 5.15.0-53-generic        | 11        | 0.5%    |
| 5.15.0-50-generic        | 11        | 0.5%    |
| 5.11.0-7614-generic      | 11        | 0.5%    |
| 5.10.0-8-amd64           | 11        | 0.5%    |
| 5.8.0-43-generic         | 10        | 0.45%   |
| 5.4.0-65-generic         | 10        | 0.45%   |
| 5.4.0-29-generic         | 10        | 0.45%   |
| 5.19.0-38-generic        | 10        | 0.45%   |
| 5.15.0-60-generic        | 10        | 0.45%   |
| 5.15.0-41-generic        | 10        | 0.45%   |
| 5.11.0-41-generic        | 10        | 0.45%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.41%   |
| 5.8.0-50-generic         | 9         | 0.41%   |
| 5.4.0-81-generic         | 9         | 0.41%   |
| 5.4.0-67-generic         | 9         | 0.41%   |
| 5.15.0-25-generic        | 9         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 336       | 15.92%  |
| 5.15.0  | 176       | 8.34%   |
| 5.11.0  | 129       | 6.11%   |
| 5.13.0  | 118       | 5.59%   |
| 5.8.0   | 98        | 4.64%   |
| 4.15.0  | 81        | 3.84%   |
| 5.3.0   | 76        | 3.6%    |
| 5.10.0  | 66        | 3.13%   |
| 5.0.0   | 59        | 2.79%   |
| 4.18.0  | 47        | 2.23%   |
| 5.19.0  | 44        | 2.08%   |
| 5.10.14 | 40        | 1.89%   |
| 5.16.7  | 39        | 1.85%   |
| 6.1.1   | 12        | 0.57%   |
| 5.17.5  | 12        | 0.57%   |
| 5.14.0  | 12        | 0.57%   |
| 6.1.0   | 10        | 0.47%   |
| 5.18.0  | 10        | 0.47%   |
| 5.12.4  | 10        | 0.47%   |
| 4.19.0  | 10        | 0.47%   |
| 5.17.1  | 9         | 0.43%   |
| 6.0.12  | 8         | 0.38%   |
| 5.16.0  | 8         | 0.38%   |
| 6.2.0   | 7         | 0.33%   |
| 6.1.12  | 7         | 0.33%   |
| 5.7.0   | 7         | 0.33%   |
| 5.19.16 | 7         | 0.33%   |
| 5.15.7  | 7         | 0.33%   |
| 6.2.9   | 6         | 0.28%   |
| 6.1.11  | 6         | 0.28%   |
| 5.9.0   | 6         | 0.28%   |
| 5.8.1   | 6         | 0.28%   |
| 5.15.5  | 6         | 0.28%   |
| 4.9.20  | 6         | 0.28%   |
| 6.2.6   | 5         | 0.24%   |
| 6.1.9   | 5         | 0.24%   |
| 6.0.8   | 5         | 0.24%   |
| 6.0.15  | 5         | 0.24%   |
| 5.9.8   | 5         | 0.24%   |
| 5.9.14  | 5         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 366       | 17.63%  |
| 5.15    | 240       | 11.56%  |
| 5.11    | 158       | 7.61%   |
| 5.10    | 152       | 7.32%   |
| 5.13    | 138       | 6.65%   |
| 5.8     | 135       | 6.5%    |
| 5.3     | 88        | 4.24%   |
| 4.15    | 81        | 3.9%    |
| 5.16    | 79        | 3.81%   |
| 5.19    | 62        | 2.99%   |
| 5.0     | 62        | 2.99%   |
| 6.1     | 55        | 2.65%   |
| 4.18    | 54        | 2.6%    |
| 5.17    | 46        | 2.22%   |
| 6.0     | 44        | 2.12%   |
| 5.18    | 37        | 1.78%   |
| 6.2     | 36        | 1.73%   |
| 5.12    | 36        | 1.73%   |
| 5.9     | 33        | 1.59%   |
| 5.14    | 32        | 1.54%   |
| 5.6     | 28        | 1.35%   |
| 5.7     | 24        | 1.16%   |
| 4.19    | 22        | 1.06%   |
| 4.9     | 16        | 0.77%   |
| 5.5     | 15        | 0.72%   |
| 5.1     | 7         | 0.34%   |
| 5.2     | 6         | 0.29%   |
| 4.4     | 6         | 0.29%   |
| 4.14    | 3         | 0.14%   |
| 4.1     | 3         | 0.14%   |
| 6.3     | 2         | 0.1%    |
| 4.20    | 2         | 0.1%    |
| 4.12    | 2         | 0.1%    |
| 3.10    | 2         | 0.1%    |
| 5       | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.13    | 1         | 0.05%   |
| 3.2     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1825      | 97.65%  |
| i686    | 22        | 1.18%   |
| aarch64 | 15        | 0.8%    |
| armv7l  | 5         | 0.27%   |
| i586    | 1         | 0.05%   |
| armv8l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 911       | 46.46%  |
| Unknown         | 268       | 13.67%  |
| KDE5            | 267       | 13.62%  |
| XFCE            | 140       | 7.14%   |
| X-Cinnamon      | 121       | 6.17%   |
| KDE             | 70        | 3.57%   |
| MATE            | 38        | 1.94%   |
| Cinnamon        | 18        | 0.92%   |
| i3              | 15        | 0.76%   |
| LXDE            | 14        | 0.71%   |
| Pantheon        | 13        | 0.66%   |
| LXQt            | 12        | 0.61%   |
| KDE4            | 11        | 0.56%   |
| Budgie          | 10        | 0.51%   |
| Unity           | 8         | 0.41%   |
| Deepin          | 7         | 0.36%   |
| awesome         | 6         | 0.31%   |
| GNOME Classic   | 5         | 0.25%   |
| sway            | 4         | 0.2%    |
| openbox         | 4         | 0.2%    |
| GNOME Flashback | 4         | 0.2%    |
| DWM             | 3         | 0.15%   |
| qtile           | 2         | 0.1%    |
| LeftWM          | 2         | 0.1%    |
| xmonad          | 1         | 0.05%   |
| Trinity         | 1         | 0.05%   |
| spectrwm        | 1         | 0.05%   |
| Hyprland        | 1         | 0.05%   |
| GNOME-Flashback | 1         | 0.05%   |
| Enlightenment   | 1         | 0.05%   |
| BunsenLabs      | 1         | 0.05%   |
| bspwm           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1407      | 73.24%  |
| Wayland     | 310       | 16.14%  |
| Unknown     | 135       | 7.03%   |
| Tty         | 68        | 3.54%   |
| Unspecified | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1044      | 53.68%  |
| SDDM    | 236       | 12.13%  |
| GDM     | 221       | 11.36%  |
| GDM3    | 193       | 9.92%   |
| LightDM | 161       | 8.28%   |
| TDM     | 63        | 3.24%   |
| KDM     | 11        | 0.57%   |
| XDM     | 6         | 0.31%   |
| Ly      | 5         | 0.26%   |
| LXDM    | 4         | 0.21%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 915       | 47.58%  |
| sv_SE       | 526       | 27.35%  |
| Unknown     | 225       | 11.7%   |
| en_GB       | 120       | 6.24%   |
| C           | 44        | 2.29%   |
| de_DE       | 14        | 0.73%   |
| ru_RU       | 12        | 0.62%   |
| en_SE       | 8         | 0.42%   |
| pl_PL       | 7         | 0.36%   |
| en_DK       | 7         | 0.36%   |
| fr_FR       | 4         | 0.21%   |
| en_CA       | 3         | 0.16%   |
| bg_BG       | 3         | 0.16%   |
| uk_UA       | 2         | 0.1%    |
| POSIX       | 2         | 0.1%    |
| nb_NO       | 2         | 0.1%    |
| lt_LT       | 2         | 0.1%    |
| it_IT       | 2         | 0.1%    |
| en_US.UTf-8 | 2         | 0.1%    |
| en_IE       | 2         | 0.1%    |
| en_AG       | 2         | 0.1%    |
| C.UTF8      | 2         | 0.1%    |
| zh_CN       | 1         | 0.05%   |
| sv_SE.UTF8  | 1         | 0.05%   |
| sv_FI       | 1         | 0.05%   |
| sma_SE      | 1         | 0.05%   |
| nn_NO       | 1         | 0.05%   |
| hu_HU       | 1         | 0.05%   |
| hr_HR       | 1         | 0.05%   |
| gl_ES       | 1         | 0.05%   |
| fi_FI       | 1         | 0.05%   |
| es_VE       | 1         | 0.05%   |
| es_ES       | 1         | 0.05%   |
| en_IN       | 1         | 0.05%   |
| en_GB.UTF8  | 1         | 0.05%   |
| en_GB.utf-8 | 1         | 0.05%   |
| en_AU       | 1         | 0.05%   |
| el_GR       | 1         | 0.05%   |
| bs_BA       | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 982       | 51.07%  |
| BIOS | 941       | 48.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1447      | 75.4%   |
| Btrfs   | 206       | 10.73%  |
| Overlay | 131       | 6.83%   |
| Unknown | 59        | 3.07%   |
| Xfs     | 32        | 1.67%   |
| Zfs     | 18        | 0.94%   |
| Tmpfs   | 12        | 0.63%   |
| Ext2    | 7         | 0.36%   |
| F2fs    | 4         | 0.21%   |
| Ext3    | 2         | 0.1%    |
| XXXXXXX | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1059      | 54.87%  |
| GPT     | 708       | 36.68%  |
| MBR     | 163       | 8.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1650      | 86.71%  |
| Yes       | 253       | 13.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1448      | 76.17%  |
| Yes       | 453       | 23.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 411       | 21.99%  |
| Hewlett-Packard         | 274       | 14.66%  |
| Lenovo                  | 273       | 14.61%  |
| Dell                    | 202       | 10.81%  |
| MSI                     | 130       | 6.96%   |
| Gigabyte Technology     | 118       | 6.31%   |
| Acer                    | 94        | 5.03%   |
| Apple                   | 62        | 3.32%   |
| ASRock                  | 45        | 2.41%   |
| Intel                   | 27        | 1.44%   |
| Toshiba                 | 17        | 0.91%   |
| Raspberry Pi Foundation | 16        | 0.86%   |
| Sony                    | 15        | 0.8%    |
| Fujitsu                 | 15        | 0.8%    |
| Packard Bell            | 12        | 0.64%   |
| Unknown                 | 11        | 0.59%   |
| Samsung Electronics     | 10        | 0.54%   |
| Google                  | 9         | 0.48%   |
| Supermicro              | 8         | 0.43%   |
| Notebook                | 7         | 0.37%   |
| Microsoft               | 7         | 0.37%   |
| Foxconn                 | 7         | 0.37%   |
| Valve                   | 6         | 0.32%   |
| Pegatron                | 6         | 0.32%   |
| Fujitsu Siemens         | 6         | 0.32%   |
| AAEON                   | 5         | 0.27%   |
| Maxtang                 | 4         | 0.21%   |
| HUAWEI                  | 4         | 0.21%   |
| TUXEDO                  | 3         | 0.16%   |
| Star Labs               | 3         | 0.16%   |
| Shuttle                 | 2         | 0.11%   |
| Schenker                | 2         | 0.11%   |
| Razer                   | 2         | 0.11%   |
| PC Specialist           | 2         | 0.11%   |
| Linx                    | 2         | 0.11%   |
| LG Electronics          | 2         | 0.11%   |
| eMachines               | 2         | 0.11%   |
| Clevo                   | 2         | 0.11%   |
| AZW                     | 2         | 0.11%   |
| AMD                     | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 21        | 1.12%   |
| Unknown                            | 14        | 0.75%   |
| ASUS ROG STRIX B450-F GAMING       | 11        | 0.59%   |
| ASUS ROG STRIX X570-F GAMING       | 9         | 0.48%   |
| MSI MS-7C37                        | 8         | 0.43%   |
| ASUS ROG STRIX B550-F GAMING       | 8         | 0.43%   |
| Dell XPS 13 9370                   | 7         | 0.37%   |
| ASUS PRIME X470-PRO                | 7         | 0.37%   |
| Valve Jupiter                      | 6         | 0.32%   |
| HP EliteBook Folio 9470m           | 6         | 0.32%   |
| Dell Precision 5540                | 6         | 0.32%   |
| ASUS Z170 PRO GAMING               | 6         | 0.32%   |
| MSI MS-7C52                        | 5         | 0.27%   |
| MSI MS-7C02                        | 5         | 0.27%   |
| MSI MS-7817                        | 5         | 0.27%   |
| Lenovo Yoga C740-14IML 81TC        | 5         | 0.27%   |
| Lenovo MIIX 310-10ICR 80SG         | 5         | 0.27%   |
| HP Pavilion dv7                    | 5         | 0.27%   |
| HP Pavilion 15                     | 5         | 0.27%   |
| HP EliteBook 840 G3                | 5         | 0.27%   |
| HP EliteBook 840 G2                | 5         | 0.27%   |
| Gigabyte B450M DS3H                | 5         | 0.27%   |
| Dell XPS 13 9310                   | 5         | 0.27%   |
| ASUS ROG STRIX B550-I GAMING       | 5         | 0.27%   |
| ASUS ROG STRIX B350-F GAMING       | 5         | 0.27%   |
| ASUS PRIME X370-PRO                | 5         | 0.27%   |
| Apple MacBookPro9,2                | 5         | 0.27%   |
| Apple MacBookPro11,3               | 5         | 0.27%   |
| Acer Aspire V3-571                 | 5         | 0.27%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 4         | 0.21%   |
| Maxtang FP30                       | 4         | 0.21%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2  | 4         | 0.21%   |
| HP EliteBook 830 G6                | 4         | 0.21%   |
| Dell XPS 15 9570                   | 4         | 0.21%   |
| Dell XPS 15 9500                   | 4         | 0.21%   |
| Dell OptiPlex 7010                 | 4         | 0.21%   |
| ASUS TUF Gaming X570-PLUS          | 4         | 0.21%   |
| ASUS SABERTOOTH 990FX R2.0         | 4         | 0.21%   |
| ASUS ROG STRIX B450-F GAMING II    | 4         | 0.21%   |
| ASUS P8Z77-V LX                    | 4         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 146       | 7.81%   |
| ASUS ROG              | 92        | 4.92%   |
| HP EliteBook          | 78        | 4.17%   |
| Acer Aspire           | 60        | 3.21%   |
| Dell Latitude         | 58        | 3.1%    |
| Dell Precision        | 47        | 2.51%   |
| ASUS PRIME            | 47        | 2.51%   |
| Dell XPS              | 46        | 2.46%   |
| HP Pavilion           | 40        | 2.14%   |
| Lenovo IdeaPad        | 34        | 1.82%   |
| HP ProBook            | 31        | 1.66%   |
| HP Compaq             | 27        | 1.44%   |
| Dell OptiPlex         | 25        | 1.34%   |
| ASUS All              | 21        | 1.12%   |
| Lenovo Yoga           | 20        | 1.07%   |
| HP ENVY               | 17        | 0.91%   |
| ASUS VivoBook         | 17        | 0.91%   |
| ASUS TUF              | 17        | 0.91%   |
| RPi Raspberry         | 16        | 0.86%   |
| HP ZBook              | 15        | 0.8%    |
| Toshiba Satellite     | 14        | 0.75%   |
| HP Laptop             | 14        | 0.75%   |
| Unknown               | 14        | 0.75%   |
| Lenovo Legion         | 12        | 0.64%   |
| ASUS ZenBook          | 12        | 0.64%   |
| HP EliteDesk          | 11        | 0.59%   |
| Dell Inspiron         | 11        | 0.59%   |
| Acer Swift            | 10        | 0.54%   |
| Gigabyte X570         | 9         | 0.48%   |
| ASUS P8Z77-V          | 9         | 0.48%   |
| Packard Bell EasyNote | 8         | 0.43%   |
| MSI MS-7C37           | 8         | 0.43%   |
| Lenovo IdeaCentre     | 8         | 0.43%   |
| Dell Vostro           | 8         | 0.43%   |
| ASUS SABERTOOTH       | 8         | 0.43%   |
| Acer Predator         | 8         | 0.43%   |
| Microsoft Surface     | 7         | 0.37%   |
| Lenovo IdeaPadFlex    | 7         | 0.37%   |
| HP Spectre            | 7         | 0.37%   |
| Gigabyte B450M        | 7         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 202       | 10.81%  |
| 2019    | 189       | 10.11%  |
| 2020    | 168       | 8.99%   |
| 2013    | 141       | 7.54%   |
| 2011    | 137       | 7.33%   |
| 2017    | 134       | 7.17%   |
| 2012    | 134       | 7.17%   |
| 2021    | 129       | 6.9%    |
| 2015    | 120       | 6.42%   |
| 2014    | 104       | 5.56%   |
| 2016    | 99        | 5.3%    |
| 2010    | 84        | 4.49%   |
| 2022    | 53        | 2.84%   |
| 2008    | 52        | 2.78%   |
| 2009    | 49        | 2.62%   |
| 2007    | 38        | 2.03%   |
| Unknown | 15        | 0.8%    |
| 2006    | 10        | 0.54%   |
| 2005    | 7         | 0.37%   |
| 2023    | 2         | 0.11%   |
| 2004    | 1         | 0.05%   |
| 2002    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 965       | 51.63%  |
| Desktop        | 746       | 39.91%  |
| Convertible    | 51        | 2.73%   |
| Mini pc        | 38        | 2.03%   |
| System on chip | 18        | 0.96%   |
| Tablet         | 17        | 0.91%   |
| All in one     | 17        | 0.91%   |
| Server         | 14        | 0.75%   |
| Phone          | 3         | 0.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1718      | 91.38%  |
| Enabled  | 162       | 8.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1856      | 99.3%   |
| Yes  | 13        | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 455       | 24.02%  |
| 4.01-8.0        | 403       | 21.28%  |
| 8.01-16.0       | 328       | 17.32%  |
| 32.01-64.0      | 281       | 14.84%  |
| 3.01-4.0        | 245       | 12.94%  |
| 64.01-256.0     | 62        | 3.27%   |
| 1.01-2.0        | 52        | 2.75%   |
| 24.01-32.0      | 34        | 1.8%    |
| 2.01-3.0        | 16        | 0.84%   |
| 0.51-1.0        | 15        | 0.79%   |
| More than 256.0 | 2         | 0.11%   |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 656       | 31.75%  |
| 2.01-3.0   | 496       | 24.01%  |
| 4.01-8.0   | 381       | 18.44%  |
| 3.01-4.0   | 273       | 13.21%  |
| 8.01-16.0  | 113       | 5.47%   |
| 0.51-1.0   | 94        | 4.55%   |
| 16.01-24.0 | 24        | 1.16%   |
| 0.01-0.5   | 22        | 1.06%   |
| 24.01-32.0 | 5         | 0.24%   |
| 32.01-64.0 | 1         | 0.05%   |
| Unknown    | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1144      | 59.31%  |
| 2      | 412       | 21.36%  |
| 3      | 165       | 8.55%   |
| 4      | 93        | 4.82%   |
| 5      | 42        | 2.18%   |
| 6      | 27        | 1.4%    |
| 0      | 20        | 1.04%   |
| 7      | 16        | 0.83%   |
| 8      | 5         | 0.26%   |
| 10     | 2         | 0.1%    |
| 26     | 1         | 0.05%   |
| 11     | 1         | 0.05%   |
| 9      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1270      | 67.59%  |
| Yes       | 609       | 32.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1614      | 86.13%  |
| No        | 260       | 13.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1357      | 72.03%  |
| No        | 527       | 27.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1142      | 60.2%   |
| No        | 755       | 39.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 1869      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Stockholm               | 353       | 17.59%  |
| Gothenburg              | 200       | 9.97%   |
| Malmo                   | 94        | 4.68%   |
| Uppsala                 | 56        | 2.79%   |
| Lund                    | 41        | 2.04%   |
| Linköping              | 39        | 1.94%   |
| Bromma                  | 29        | 1.44%   |
| Västerås              | 28        | 1.4%    |
| Sollentuna              | 27        | 1.35%   |
| Vaxjo                   | 25        | 1.25%   |
| Norrköping             | 25        | 1.25%   |
| Solna                   | 24        | 1.2%    |
| Umeå                   | 22        | 1.1%    |
| Örebro                 | 22        | 1.1%    |
| Haegersten              | 19        | 0.95%   |
| Vaestra Froelunda       | 18        | 0.9%    |
| Sundsvall               | 18        | 0.9%    |
| Karlstad                | 18        | 0.9%    |
| Södertälje            | 16        | 0.8%    |
| Huddinge                | 16        | 0.8%    |
| Helsingborg             | 16        | 0.8%    |
| Sundbyberg              | 14        | 0.7%    |
| Kista                   | 14        | 0.7%    |
| Karlskrona              | 14        | 0.7%    |
| Taby                    | 13        | 0.65%   |
| Moelndal                | 13        | 0.65%   |
| Bandhagen               | 13        | 0.65%   |
| Katrineholm             | 12        | 0.6%    |
| Halmstad                | 12        | 0.6%    |
| Gävle                  | 12        | 0.6%    |
| Alvsjo                  | 12        | 0.6%    |
| Staffanstorp            | 11        | 0.55%   |
| Nyköping               | 11        | 0.55%   |
| Landskrona              | 11        | 0.55%   |
| Järfälla Municipality | 11        | 0.55%   |
| Upplands Vasby          | 10        | 0.5%    |
| Spanga                  | 10        | 0.5%    |
| Norsborg                | 10        | 0.5%    |
| Luleå                  | 10        | 0.5%    |
| Arboga                  | 10        | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 619       | 992    | 22.29%  |
| WDC                         | 377       | 605    | 13.58%  |
| Seagate                     | 339       | 551    | 12.21%  |
| Kingston                    | 213       | 298    | 7.67%   |
| Intel                       | 153       | 200    | 5.51%   |
| SanDisk                     | 137       | 176    | 4.93%   |
| Toshiba                     | 136       | 180    | 4.9%    |
| Unknown                     | 103       | 132    | 3.71%   |
| Hitachi                     | 83        | 118    | 2.99%   |
| SK hynix                    | 76        | 85     | 2.74%   |
| Crucial                     | 64        | 94     | 2.3%    |
| Micron Technology           | 56        | 70     | 2.02%   |
| HGST                        | 46        | 55     | 1.66%   |
| Apple                       | 34        | 42     | 1.22%   |
| OCZ                         | 23        | 29     | 0.83%   |
| Phison                      | 21        | 25     | 0.76%   |
| Corsair                     | 20        | 27     | 0.72%   |
| A-DATA Technology           | 19        | 19     | 0.68%   |
| LITEON                      | 17        | 22     | 0.61%   |
| KIOXIA                      | 15        | 16     | 0.54%   |
| Kingston Technology Company | 15        | 16     | 0.54%   |
| Transcend                   | 11        | 12     | 0.4%    |
| LITEONIT                    | 11        | 18     | 0.4%    |
| Intenso                     | 11        | 14     | 0.4%    |
| Fujitsu                     | 11        | 16     | 0.4%    |
| Silicon Motion              | 10        | 26     | 0.36%   |
| Phison Electronics          | 10        | 12     | 0.36%   |
| China                       | 9         | 9      | 0.32%   |
| PNY                         | 8         | 10     | 0.29%   |
| Maxtor                      | 6         | 6      | 0.22%   |
| LaCie                       | 6         | 7      | 0.22%   |
| ASMT                        | 6         | 6      | 0.22%   |
| Unknown                     | 6         | 6      | 0.22%   |
| SPCC                        | 5         | 10     | 0.18%   |
| Micron/Crucial Technology   | 5         | 8      | 0.18%   |
| JMicron Technology          | 5         | 5      | 0.18%   |
| Lenovo                      | 4         | 4      | 0.14%   |
| Hewlett-Packard             | 4         | 6      | 0.14%   |
| XPG                         | 3         | 3      | 0.11%   |
| Union Memory                | 3         | 3      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                          | 48        | 1.51%   |
| Samsung SSD 850 EVO 500GB                          | 41        | 1.29%   |
| Kingston SA400S37120G 120GB SSD                    | 31        | 0.97%   |
| Kingston SV300S37A120G 120GB SSD                   | 29        | 0.91%   |
| Kingston SA400S37240G 240GB SSD                    | 27        | 0.85%   |
| Samsung SSD 860 EVO 250GB                          | 25        | 0.79%   |
| Samsung NVMe SSD Drive 500GB                       | 25        | 0.79%   |
| Samsung SSD 840 EVO 250GB                          | 23        | 0.72%   |
| Seagate ST4000DM004-2CV104 4TB                     | 21        | 0.66%   |
| Samsung SSD 860 EVO 500GB                          | 21        | 0.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 21        | 0.66%   |
| Samsung NVMe SSD Drive 512GB                       | 20        | 0.63%   |
| Kingston SA400S37480G 480GB SSD                    | 20        | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB                     | 18        | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB                     | 18        | 0.57%   |
| SanDisk NVMe SSD Drive 1TB                         | 17        | 0.53%   |
| Unknown MMC Card  32GB                             | 16        | 0.5%    |
| Samsung NVMe SSD Drive 1TB                         | 16        | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB                     | 15        | 0.47%   |
| Samsung SSD 860 EVO 1TB                            | 15        | 0.47%   |
| Samsung NVMe SSD Drive 256GB                       | 15        | 0.47%   |
| HGST HTS721010A9E630 1TB                           | 14        | 0.44%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 13        | 0.41%   |
| Seagate ST500DM002-1BD142 500GB                    | 13        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                       | 13        | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB                       | 13        | 0.41%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB             | 13        | 0.41%   |
| Toshiba NVMe SSD Drive 512GB                       | 12        | 0.38%   |
| Seagate ST4000VN008-2DR166 4TB                     | 12        | 0.38%   |
| Samsung NVMe SSD Drive 1024GB                      | 12        | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 11        | 0.35%   |
| Unknown SD/MMC/MS PRO 249GB                        | 11        | 0.35%   |
| Unknown MMC Card  16GB                             | 11        | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                      | 11        | 0.35%   |
| Seagate ST2000DM006-2DM164 2TB                     | 11        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                     | 11        | 0.35%   |
| Seagate Expansion 4TB                              | 11        | 0.35%   |
| Samsung SSD 840 EVO 500GB                          | 11        | 0.35%   |
| Samsung SSD 840 EVO 120GB                          | 11        | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 11        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 335       | 538    | 35.79%  |
| WDC                 | 289       | 478    | 30.88%  |
| Hitachi             | 83        | 118    | 8.87%   |
| Toshiba             | 75        | 102    | 8.01%   |
| Samsung Electronics | 53        | 88     | 5.66%   |
| HGST                | 46        | 55     | 4.91%   |
| Unknown             | 12        | 14     | 1.28%   |
| Fujitsu             | 11        | 16     | 1.18%   |
| Apple               | 10        | 10     | 1.07%   |
| Maxtor              | 5         | 5      | 0.53%   |
| JMicron Technology  | 3         | 3      | 0.32%   |
| Intenso             | 3         | 3      | 0.32%   |
| ASMedia             | 3         | 3      | 0.32%   |
| Hewlett-Packard     | 2         | 4      | 0.21%   |
| ASMT                | 2         | 2      | 0.21%   |
| USB3.0              | 1         | 1      | 0.11%   |
| MARVELL             | 1         | 1      | 0.11%   |
| LaCie               | 1         | 1      | 0.11%   |
| IB                  | 1         | 2      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 349       | 520    | 33.27%  |
| Kingston            | 165       | 226    | 15.73%  |
| Intel               | 88        | 111    | 8.39%   |
| SanDisk             | 69        | 85     | 6.58%   |
| Crucial             | 61        | 90     | 5.82%   |
| WDC                 | 54        | 74     | 5.15%   |
| Micron Technology   | 37        | 49     | 3.53%   |
| SK hynix            | 24        | 27     | 2.29%   |
| OCZ                 | 23        | 29     | 2.19%   |
| Apple               | 22        | 28     | 2.1%    |
| Toshiba             | 19        | 26     | 1.81%   |
| LITEON              | 16        | 21     | 1.53%   |
| Corsair             | 12        | 14     | 1.14%   |
| A-DATA Technology   | 12        | 12     | 1.14%   |
| Transcend           | 11        | 12     | 1.05%   |
| LITEONIT            | 11        | 18     | 1.05%   |
| China               | 9         | 9      | 0.86%   |
| Intenso             | 7         | 7      | 0.67%   |
| SPCC                | 5         | 10     | 0.48%   |
| PNY                 | 5         | 7      | 0.48%   |
| ASMT                | 4         | 4      | 0.38%   |
| M4-CT128            | 3         | 3      | 0.29%   |
| Verbatim            | 2         | 3      | 0.19%   |
| Seagate             | 2         | 4      | 0.19%   |
| Patriot             | 2         | 3      | 0.19%   |
| OCZ-VERTEX3         | 2         | 2      | 0.19%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.19%   |
| KingSpec            | 2         | 2      | 0.19%   |
| GOODRAM             | 2         | 3      | 0.19%   |
| Emtec               | 2         | 2      | 0.19%   |
| XSTAR               | 1         | 2      | 0.1%    |
| WDC WDS2            | 1         | 1      | 0.1%    |
| WDC WDS1            | 1         | 1      | 0.1%    |
| Unknown             | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 1      | 0.1%    |
| tigo                | 1         | 1      | 0.1%    |
| StoreJet            | 1         | 1      | 0.1%    |
| Star                | 1         | 1      | 0.1%    |
| SSSTC               | 1         | 2      | 0.1%    |
| SATAFIRM            | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 904       | 1434   | 36.32%  |
| HDD     | 760       | 1444   | 30.53%  |
| NVMe    | 697       | 987    | 28%     |
| MMC     | 96        | 115    | 3.86%   |
| Unknown | 32        | 41     | 1.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1328      | 2737   | 59.39%  |
| NVMe | 695       | 982    | 31.08%  |
| SAS  | 117       | 187    | 5.23%   |
| MMC  | 96        | 115    | 4.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1086      | 1767   | 60.23%  |
| 0.51-1.0   | 387       | 584    | 21.46%  |
| 1.01-2.0   | 150       | 229    | 8.32%   |
| 3.01-4.0   | 76        | 131    | 4.22%   |
| 2.01-3.0   | 56        | 88     | 3.11%   |
| 4.01-10.0  | 37        | 65     | 2.05%   |
| 10.01-20.0 | 11        | 14     | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 530       | 26.71%  |
| 251-500        | 441       | 22.23%  |
| 501-1000       | 258       | 13%     |
| 1-20           | 169       | 8.52%   |
| 1001-2000      | 160       | 8.06%   |
| More than 3000 | 134       | 6.75%   |
| 51-100         | 98        | 4.94%   |
| Unknown        | 77        | 3.88%   |
| 2001-3000      | 62        | 3.13%   |
| 21-50          | 55        | 2.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 768       | 37.68%  |
| 21-50          | 302       | 14.82%  |
| 101-250        | 264       | 12.95%  |
| 51-100         | 212       | 10.4%   |
| 251-500        | 145       | 7.11%   |
| 501-1000       | 117       | 5.74%   |
| Unknown        | 77        | 3.78%   |
| 1001-2000      | 62        | 3.04%   |
| More than 3000 | 51        | 2.5%    |
| 2001-3000      | 38        | 1.86%   |
| 0              | 2         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 5         | 5      | 3.38%   |
| Seagate ST9250410AS 250GB                      | 3         | 4      | 2.03%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 2.03%   |
| WDC WD5000AAKX-75U6AA0 500GB                   | 2         | 2      | 1.35%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 1.35%   |
| Seagate ST4000DM004-2CV104 4TB                 | 2         | 2      | 1.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 2      | 1.35%   |
| Samsung Electronics SSD 870 EVO 1TB            | 2         | 2      | 1.35%   |
| Samsung Electronics HD501LJ 500GB              | 2         | 2      | 1.35%   |
| Samsung Electronics HD300LJ 304GB              | 2         | 2      | 1.35%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 3      | 1.35%   |
| Intel SSDSC2BW480A4 480GB                      | 2         | 3      | 1.35%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.35%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 1.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 0.68%   |
| WDC WD7500AACS-00ZJB0 752GB                    | 1         | 1      | 0.68%   |
| WDC WD740GD-00FLA1 74GB                        | 1         | 1      | 0.68%   |
| WDC WD6400AAKS-22A7B2 640GB                    | 1         | 1      | 0.68%   |
| WDC WD60EFRX-68L0BN1 6TB                       | 1         | 6      | 0.68%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 0.68%   |
| WDC WD5000BPKT-60PK4T0 500GB                   | 1         | 1      | 0.68%   |
| WDC WD5000AZRX-00A8LB0 500GB                   | 1         | 2      | 0.68%   |
| WDC WD5000AAKX-22ERMA0 500GB                   | 1         | 1      | 0.68%   |
| WDC WD5000AAKS-00A7B2 500GB                    | 1         | 1      | 0.68%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 2      | 0.68%   |
| WDC WD4003FZEX-00Z4SA0 4TB                     | 1         | 2      | 0.68%   |
| WDC WD3200AAKS-75L9A0 320GB                    | 1         | 1      | 0.68%   |
| WDC WD3200AAKS-00B3A0 320GB                    | 1         | 4      | 0.68%   |
| WDC WD30EFRX-68AX9N0 3TB                       | 1         | 1      | 0.68%   |
| WDC WD20EARS-00MVWB0 2TB                       | 1         | 1      | 0.68%   |
| WDC WD15EARS-00Z5B1 1TB                        | 1         | 1      | 0.68%   |
| WDC WD15EADS-00P8B0 1TB                        | 1         | 2      | 0.68%   |
| WDC WD10EZEX-21M2NA0 1TB                       | 1         | 2      | 0.68%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 3      | 0.68%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 0.68%   |
| WDC WD10EFRX-68FYTN0 1TB                       | 1         | 1      | 0.68%   |
| WDC WD10EARS-00Y5B1 1TB                        | 1         | 2      | 0.68%   |
| WDC WD10EARS-00MVWB0 1TB                       | 1         | 1      | 0.68%   |
| WDC WD10EALX-009BA0 1TB                        | 1         | 4      | 0.68%   |
| WDC WD10EADS-00M2B0 1TB                        | 1         | 1      | 0.68%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 39     | 23.08%  |
| WDC                 | 26        | 48     | 18.18%  |
| Samsung Electronics | 18        | 18     | 12.59%  |
| Hitachi             | 14        | 16     | 9.79%   |
| Intel               | 12        | 15     | 8.39%   |
| HGST                | 6         | 6      | 4.2%    |
| Kingston            | 4         | 4      | 2.8%    |
| Toshiba             | 3         | 4      | 2.1%    |
| OCZ                 | 3         | 5      | 2.1%    |
| Micron Technology   | 3         | 4      | 2.1%    |
| Crucial             | 3         | 3      | 2.1%    |
| Corsair             | 3         | 3      | 2.1%    |
| SK hynix            | 2         | 2      | 1.4%    |
| SanDisk             | 2         | 2      | 1.4%    |
| LITEONIT            | 2         | 2      | 1.4%    |
| Fujitsu             | 2         | 2      | 1.4%    |
| Apple               | 2         | 2      | 1.4%    |
| Union Memory        | 1         | 1      | 0.7%    |
| Transcend           | 1         | 1      | 0.7%    |
| PNY                 | 1         | 2      | 0.7%    |
| Hewlett-Packard     | 1         | 1      | 0.7%    |
| China               | 1         | 1      | 0.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 39     | 34.02%  |
| WDC                 | 25        | 47     | 25.77%  |
| Hitachi             | 14        | 16     | 14.43%  |
| Samsung Electronics | 11        | 11     | 11.34%  |
| HGST                | 6         | 6      | 6.19%   |
| Toshiba             | 3         | 4      | 3.09%   |
| Fujitsu             | 2         | 2      | 2.06%   |
| Apple               | 2         | 2      | 2.06%   |
| Hewlett-Packard     | 1         | 1      | 1.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 94        | 128    | 68.12%  |
| SSD  | 39        | 48     | 28.26%  |
| NVMe | 5         | 5      | 3.62%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                                 | 1         | 1      | 50%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1217      | 2559   | 59.42%  |
| Works    | 696       | 1279   | 33.98%  |
| Malfunc  | 133       | 181    | 6.49%   |
| Failed   | 2         | 2      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1171      | 48.43%  |
| AMD                              | 396       | 16.38%  |
| Samsung Electronics              | 313       | 12.94%  |
| SanDisk                          | 105       | 4.34%   |
| Kingston Technology Company      | 63        | 2.61%   |
| SK hynix                         | 51        | 2.11%   |
| Toshiba America Info Systems     | 46        | 1.9%    |
| ASMedia Technology               | 41        | 1.7%    |
| Phison Electronics               | 40        | 1.65%   |
| JMicron Technology               | 33        | 1.36%   |
| Marvell Technology Group         | 30        | 1.24%   |
| Micron Technology                | 20        | 0.83%   |
| Nvidia                           | 19        | 0.79%   |
| KIOXIA                           | 14        | 0.58%   |
| Silicon Motion                   | 12        | 0.5%    |
| ADATA Technology                 | 8         | 0.33%   |
| Micron/Crucial Technology        | 7         | 0.29%   |
| Silicon Image                    | 6         | 0.25%   |
| Union Memory (Shenzhen)          | 5         | 0.21%   |
| Lite-On Technology               | 5         | 0.21%   |
| VIA Technologies                 | 4         | 0.17%   |
| Lenovo                           | 4         | 0.17%   |
| Broadcom / LSI                   | 4         | 0.17%   |
| Apple                            | 4         | 0.17%   |
| Solid State Storage Technology   | 3         | 0.12%   |
| Silicon Integrated Systems [SiS] | 3         | 0.12%   |
| LSI Logic / Symbios Logic        | 3         | 0.12%   |
| Hewlett-Packard                  | 3         | 0.12%   |
| Seagate Technology               | 2         | 0.08%   |
| Realtek Semiconductor            | 2         | 0.08%   |
| Adaptec                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 260       | 9.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 171       | 6.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 91        | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 86        | 3.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 71        | 2.55%   |
| AMD 400 Series Chipset SATA Controller                                         | 67        | 2.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 57        | 2.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 54        | 1.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 53        | 1.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 53        | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 48        | 1.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 47        | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 45        | 1.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 42        | 1.51%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 40        | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 39        | 1.4%    |
| Intel Volume Management Device NVMe RAID Controller                            | 36        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 35        | 1.26%   |
| AMD 500 Series Chipset SATA Controller                                         | 35        | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 34        | 1.22%   |
| Intel SSD 660P Series                                                          | 34        | 1.22%   |
| Intel SATA Controller [RAID mode]                                              | 34        | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 34        | 1.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 33        | 1.19%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 32        | 1.15%   |
| Kingston Company A2000 NVMe SSD                                                | 31        | 1.12%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 31        | 1.12%   |
| Samsung NVMe SSD Controller 980                                                | 30        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 29        | 1.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 28        | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 27        | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 22        | 0.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 22        | 0.79%   |
| Phison E12 NVMe Controller                                                     | 21        | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 21        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 21        | 0.76%   |
| Micron NVMe Storage Controller                                                 | 20        | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 19        | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                          | 18        | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 18        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1342      | 55.48%  |
| NVMe | 703       | 29.06%  |
| IDE  | 220       | 9.09%   |
| RAID | 144       | 5.95%   |
| SAS  | 8         | 0.33%   |
| SCSI | 2         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1367      | 73.14%  |
| AMD      | 481       | 25.74%  |
| ARM      | 20        | 1.07%   |
| QUALCOMM | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 28        | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 27        | 1.44%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 23        | 1.23%   |
| AMD Ryzen 5 3600 6-Core Processor       | 23        | 1.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 21        | 1.12%   |
| Intel Core i5-6600K CPU @ 3.50GHz       | 17        | 0.91%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 17        | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 15        | 0.8%    |
| ARM Processor                           | 15        | 0.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 14        | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 14        | 0.75%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 12        | 0.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 11        | 0.59%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 11        | 0.59%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 11        | 0.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 11        | 0.59%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 11        | 0.59%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 11        | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 10        | 0.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 10        | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 10        | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 10        | 0.53%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 10        | 0.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 0.53%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 10        | 0.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 10        | 0.53%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 10        | 0.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 9         | 0.48%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 9         | 0.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 9         | 0.48%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 9         | 0.48%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 9         | 0.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 9         | 0.48%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 0.48%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 9         | 0.48%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 9         | 0.48%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 9         | 0.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 8         | 0.43%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 8         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 448       | 23.94%  |
| Intel Core i7           | 435       | 23.25%  |
| Other                   | 124       | 6.63%   |
| AMD Ryzen 5             | 121       | 6.47%   |
| AMD Ryzen 7             | 101       | 5.4%    |
| Intel Core i3           | 78        | 4.17%   |
| Intel Celeron           | 69        | 3.69%   |
| Intel Core 2 Duo        | 59        | 3.15%   |
| AMD Ryzen 9             | 46        | 2.46%   |
| Intel Xeon              | 42        | 2.24%   |
| Intel Pentium           | 33        | 1.76%   |
| AMD FX                  | 33        | 1.76%   |
| Intel Atom              | 25        | 1.34%   |
| AMD Ryzen 3             | 19        | 1.02%   |
| Intel Core i9           | 16        | 0.86%   |
| Intel Core 2 Quad       | 15        | 0.8%    |
| Intel Core 2            | 13        | 0.69%   |
| AMD A8                  | 13        | 0.69%   |
| AMD Ryzen Threadripper  | 11        | 0.59%   |
| AMD A6                  | 10        | 0.53%   |
| AMD A4                  | 10        | 0.53%   |
| Intel Pentium Dual-Core | 9         | 0.48%   |
| Intel Genuine           | 9         | 0.48%   |
| AMD Phenom II X4        | 9         | 0.48%   |
| AMD Ryzen 7 PRO         | 8         | 0.43%   |
| AMD E1                  | 7         | 0.37%   |
| AMD E                   | 7         | 0.37%   |
| AMD Athlon 64 X2        | 7         | 0.37%   |
| AMD Phenom II X6        | 6         | 0.32%   |
| AMD Athlon II X2        | 6         | 0.32%   |
| AMD A10                 | 6         | 0.32%   |
| Intel Pentium Dual      | 5         | 0.27%   |
| ARM BCM                 | 5         | 0.27%   |
| AMD Ryzen Embedded      | 5         | 0.27%   |
| AMD Ryzen 5 PRO         | 5         | 0.27%   |
| Intel Pentium Silver    | 4         | 0.21%   |
| Intel Core m3           | 3         | 0.16%   |
| Intel Celeron Dual-Core | 3         | 0.16%   |
| AMD Athlon II X4        | 3         | 0.16%   |
| AMD Athlon II X3        | 3         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 724       | 38.63%  |
| 2       | 621       | 33.14%  |
| 6       | 225       | 12.01%  |
| 8       | 159       | 8.48%   |
| 12      | 44        | 2.35%   |
| 16      | 29        | 1.55%   |
| 1       | 27        | 1.44%   |
| 3       | 18        | 0.96%   |
| 14      | 7         | 0.37%   |
| 10      | 6         | 0.32%   |
| Unknown | 5         | 0.27%   |
| 18      | 4         | 0.21%   |
| 32      | 2         | 0.11%   |
| 64      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1843      | 98.61%  |
| 2       | 21        | 1.12%   |
| Unknown | 4         | 0.21%   |
| 3       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1282      | 68.45%  |
| 1       | 586       | 31.29%  |
| Unknown | 5         | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1821      | 97.22%  |
| Unknown        | 41        | 2.19%   |
| 32-bit         | 10        | 0.53%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 512       | 26.28%  |
| 0x306c3    | 97        | 4.98%   |
| 0x206a7    | 89        | 4.57%   |
| 0x306a9    | 84        | 4.31%   |
| 0x906ea    | 47        | 2.41%   |
| 0x40651    | 47        | 2.41%   |
| 0x1067a    | 47        | 2.41%   |
| 0x806ec    | 45        | 2.31%   |
| 0x806ea    | 44        | 2.26%   |
| 0x506e3    | 44        | 2.26%   |
| 0x906e9    | 42        | 2.16%   |
| 0x306d4    | 41        | 2.1%    |
| 0x406e3    | 40        | 2.05%   |
| 0x806e9    | 39        | 2%      |
| 0x08701021 | 37        | 1.9%    |
| 0x806c1    | 34        | 1.75%   |
| 0x20655    | 26        | 1.33%   |
| 0x406c4    | 19        | 0.98%   |
| 0x0a50000c | 19        | 0.98%   |
| 0x0800820d | 19        | 0.98%   |
| 0x08701013 | 18        | 0.92%   |
| 0x08108109 | 18        | 0.92%   |
| 0x08600106 | 16        | 0.82%   |
| 0x906ed    | 15        | 0.77%   |
| 0x06000852 | 15        | 0.77%   |
| 0x6fd      | 14        | 0.72%   |
| 0x0810100b | 14        | 0.72%   |
| 0x010000c8 | 14        | 0.72%   |
| 0x806eb    | 13        | 0.67%   |
| 0x30678    | 13        | 0.67%   |
| 0x0a201009 | 13        | 0.67%   |
| 0xa0652    | 12        | 0.62%   |
| 0x906a3    | 12        | 0.62%   |
| 0x6f6      | 12        | 0.62%   |
| 0x306f2    | 12        | 0.62%   |
| 0x106e5    | 12        | 0.62%   |
| 0x10676    | 11        | 0.56%   |
| 0x08108102 | 10        | 0.51%   |
| 0x08001138 | 10        | 0.51%   |
| 0x06001119 | 10        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 332       | 17.74%  |
| Haswell          | 200       | 10.69%  |
| SandyBridge      | 129       | 6.89%   |
| Skylake          | 117       | 6.25%   |
| IvyBridge        | 116       | 6.2%    |
| Zen 2            | 109       | 5.83%   |
| Penryn           | 70        | 3.74%   |
| Unknown          | 70        | 3.74%   |
| Zen 3            | 68        | 3.63%   |
| Zen+             | 65        | 3.47%   |
| Broadwell        | 53        | 2.83%   |
| Silvermont       | 52        | 2.78%   |
| Zen              | 49        | 2.62%   |
| Core             | 48        | 2.57%   |
| Westmere         | 47        | 2.51%   |
| TigerLake        | 47        | 2.51%   |
| K10              | 39        | 2.08%   |
| Piledriver       | 35        | 1.87%   |
| CometLake        | 35        | 1.87%   |
| Alderlake Hybrid | 23        | 1.23%   |
| Goldmont plus    | 21        | 1.12%   |
| Icelake          | 19        | 1.02%   |
| Nehalem          | 18        | 0.96%   |
| Excavator        | 17        | 0.91%   |
| K8 Hammer        | 13        | 0.69%   |
| K10 Llano        | 12        | 0.64%   |
| Jaguar           | 10        | 0.53%   |
| Bulldozer        | 10        | 0.53%   |
| Bobcat           | 10        | 0.53%   |
| Goldmont         | 9         | 0.48%   |
| Bonnell          | 7         | 0.37%   |
| Puma             | 6         | 0.32%   |
| P6               | 4         | 0.21%   |
| NetBurst         | 3         | 0.16%   |
| Tremont          | 2         | 0.11%   |
| Steamroller      | 2         | 0.11%   |
| K8 & K10 hybrid  | 2         | 0.11%   |
| K6               | 1         | 0.05%   |
| Geode            | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 974       | 44.91%  |
| Nvidia                           | 686       | 31.63%  |
| AMD                              | 490       | 22.59%  |
| Matrox Electronics Systems       | 9         | 0.41%   |
| ASPEED Technology                | 7         | 0.32%   |
| Silicon Integrated Systems [SiS] | 3         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 85        | 3.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 64        | 2.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 57        | 2.54%   |
| Intel UHD Graphics 620                                                                   | 56        | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 46        | 2.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 45        | 2.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 42        | 1.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 42        | 1.87%   |
| Intel HD Graphics 620                                                                    | 40        | 1.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 1.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 37        | 1.65%   |
| Intel HD Graphics 5500                                                                   | 36        | 1.6%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 36        | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 33        | 1.47%   |
| AMD Renoir                                                                               | 31        | 1.38%   |
| Intel HD Graphics 630                                                                    | 30        | 1.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 30        | 1.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 25        | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 22        | 0.98%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 22        | 0.98%   |
| Intel HD Graphics 530                                                                    | 21        | 0.94%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 19        | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 19        | 0.85%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 18        | 0.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.76%   |
| AMD Lucienne                                                                             | 17        | 0.76%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 15        | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 15        | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 0.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 15        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 14        | 0.62%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 14        | 0.62%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 13        | 0.58%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 13        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 700       | 37.14%  |
| 1 x Nvidia               | 434       | 23.02%  |
| 1 x AMD                  | 393       | 20.85%  |
| Intel + Nvidia           | 211       | 11.19%  |
| 2 x AMD                  | 33        | 1.75%   |
| AMD + Nvidia             | 33        | 1.75%   |
| Intel + AMD              | 32        | 1.7%    |
| Other                    | 22        | 1.17%   |
| 1 x Matrox               | 7         | 0.37%   |
| 1 x ASPEED               | 7         | 0.37%   |
| 2 x Nvidia               | 4         | 0.21%   |
| 1 x SiS                  | 3         | 0.16%   |
| Intel + 2 x Nvidia       | 2         | 0.11%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.05%   |
| 2 x Intel                | 1         | 0.05%   |
| Nvidia + Matrox          | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1404      | 73.86%  |
| Proprietary | 412       | 21.67%  |
| Unknown     | 85        | 4.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1037      | 53.79%  |
| 1.01-2.0   | 216       | 11.2%   |
| 0.01-0.5   | 196       | 10.17%  |
| 0.51-1.0   | 124       | 6.43%   |
| 3.01-4.0   | 121       | 6.28%   |
| 7.01-8.0   | 114       | 5.91%   |
| 5.01-6.0   | 58        | 3.01%   |
| 8.01-16.0  | 36        | 1.87%   |
| 2.01-3.0   | 22        | 1.14%   |
| 16.01-24.0 | 4         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 268       | 12.65%  |
| Samsung Electronics     | 251       | 11.85%  |
| LG Display              | 157       | 7.41%   |
| Chimei Innolux          | 145       | 6.85%   |
| Dell                    | 115       | 5.43%   |
| BenQ                    | 111       | 5.24%   |
| Philips                 | 102       | 4.82%   |
| BOE                     | 90        | 4.25%   |
| Ancor Communications    | 87        | 4.11%   |
| Hewlett-Packard         | 84        | 3.97%   |
| AOC                     | 83        | 3.92%   |
| Acer                    | 73        | 3.45%   |
| Sharp                   | 59        | 2.79%   |
| Goldstar                | 54        | 2.55%   |
| Apple                   | 51        | 2.41%   |
| Lenovo                  | 42        | 1.98%   |
| ASUSTek Computer        | 33        | 1.56%   |
| Chi Mei Optoelectronics | 24        | 1.13%   |
| MSI                     | 22        | 1.04%   |
| InfoVision              | 21        | 0.99%   |
| Eizo                    | 20        | 0.94%   |
| LG Philips              | 17        | 0.8%    |
| Vestel Elektronik       | 14        | 0.66%   |
| Sony                    | 14        | 0.66%   |
| CSO                     | 12        | 0.57%   |
| Unknown                 | 11        | 0.52%   |
| LG Electronics          | 11        | 0.52%   |
| Panasonic               | 10        | 0.47%   |
| PANDA                   | 9         | 0.42%   |
| Fujitsu Siemens         | 9         | 0.42%   |
| ViewSonic               | 8         | 0.38%   |
| VOXICON                 | 5         | 0.24%   |
| Toshiba                 | 5         | 0.24%   |
| Microstep               | 5         | 0.24%   |
| BOE Technology Group    | 5         | 0.24%   |
| Quanta Display          | 4         | 0.19%   |
| OEM                     | 4         | 0.19%   |
| LGD                     | 4         | 0.19%   |
| Gigabyte Technology     | 4         | 0.19%   |
| AUS                     | 4         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 14        | 0.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 12        | 0.54%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 10        | 0.45%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 9         | 0.41%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 8         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 8         | 0.36%   |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                   | 8         | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 8         | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 8         | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 8         | 0.36%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 8         | 0.36%   |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch  | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 7         | 0.32%   |
| AOC 24P2W1DG5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 7         | 0.32%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 6         | 0.27%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                   | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch       | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch       | 6         | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 6         | 0.27%   |
| AOC U32U1WR6B AOC3201 3840x2160 697x392mm 31.5-inch                    | 6         | 0.27%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch       | 6         | 0.27%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch  | 6         | 0.27%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 5         | 0.23%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch              | 5         | 0.23%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch             | 5         | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 5         | 0.23%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 5         | 0.23%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 5         | 0.23%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 5         | 0.23%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                | 4         | 0.18%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 4         | 0.18%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch  | 4         | 0.18%   |
| Philips PHL 278E8Q PHLC161 1920x1080 598x336mm 27.0-inch               | 4         | 0.18%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 4         | 0.18%   |
| Panasonic VVY13F001G10 MEI96A2 1920x1080 344x193mm 15.5-inch           | 4         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 893       | 43.95%  |
| 1366x768 (WXGA)    | 237       | 11.66%  |
| 2560x1440 (QHD)    | 169       | 8.32%   |
| 3840x2160 (4K)     | 168       | 8.27%   |
| 1680x1050 (WSXGA+) | 72        | 3.54%   |
| 1920x1200 (WUXGA)  | 63        | 3.1%    |
| 3440x1440          | 53        | 2.61%   |
| 1280x1024 (SXGA)   | 45        | 2.21%   |
| 1600x900 (HD+)     | 44        | 2.17%   |
| 1280x800 (WXGA)    | 42        | 2.07%   |
| Unknown            | 37        | 1.82%   |
| 2560x1600          | 27        | 1.33%   |
| 1440x900 (WXGA+)   | 26        | 1.28%   |
| 3840x2400          | 17        | 0.84%   |
| 2880x1800          | 17        | 0.84%   |
| 3840x1080          | 16        | 0.79%   |
| 1024x768 (XGA)     | 12        | 0.59%   |
| 1360x768           | 9         | 0.44%   |
| 1920x540           | 8         | 0.39%   |
| 2736x1824          | 7         | 0.34%   |
| 1280x720 (HD)      | 7         | 0.34%   |
| 3200x1800 (QHD+)   | 6         | 0.3%    |
| 800x1280           | 5         | 0.25%   |
| 2560x1080          | 5         | 0.25%   |
| 1024x600           | 5         | 0.25%   |
| 3840x1600          | 4         | 0.2%    |
| 6400x2160          | 3         | 0.15%   |
| 5760x1080          | 3         | 0.15%   |
| 2288x1287          | 3         | 0.15%   |
| 2160x1440          | 3         | 0.15%   |
| 5760x2160          | 2         | 0.1%    |
| 4480x1440          | 2         | 0.1%    |
| 3840x1200          | 2         | 0.1%    |
| 3200x1200          | 2         | 0.1%    |
| 1280x768           | 2         | 0.1%    |
| 7280x2160          | 1         | 0.05%   |
| 5520x2160          | 1         | 0.05%   |
| 5360x1440          | 1         | 0.05%   |
| 4864x1080          | 1         | 0.05%   |
| 4240x1440          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 386       | 18.36%  |
| 13      | 240       | 11.42%  |
| 27      | 226       | 10.75%  |
| 24      | 214       | 10.18%  |
| 14      | 155       | 7.37%   |
| Unknown | 142       | 6.76%   |
| 23      | 132       | 6.28%   |
| 17      | 81        | 3.85%   |
| 12      | 60        | 2.85%   |
| 21      | 58        | 2.76%   |
| 22      | 53        | 2.52%   |
| 34      | 49        | 2.33%   |
| 31      | 48        | 2.28%   |
| 19      | 43        | 2.05%   |
| 84      | 31        | 1.47%   |
| 11      | 25        | 1.19%   |
| 32      | 18        | 0.86%   |
| 16      | 14        | 0.67%   |
| 72      | 10        | 0.48%   |
| 65      | 10        | 0.48%   |
| 25      | 10        | 0.48%   |
| 20      | 10        | 0.48%   |
| 54      | 8         | 0.38%   |
| 18      | 8         | 0.38%   |
| 42      | 6         | 0.29%   |
| 39      | 6         | 0.29%   |
| 35      | 6         | 0.29%   |
| 37      | 5         | 0.24%   |
| 29      | 5         | 0.24%   |
| 10      | 5         | 0.24%   |
| 50      | 4         | 0.19%   |
| 48      | 4         | 0.19%   |
| 49      | 3         | 0.14%   |
| 46      | 3         | 0.14%   |
| 40      | 3         | 0.14%   |
| 33      | 3         | 0.14%   |
| 55      | 2         | 0.1%    |
| 47      | 2         | 0.1%    |
| 26      | 2         | 0.1%    |
| 7       | 2         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 662       | 32.21%  |
| 501-600        | 524       | 25.5%   |
| 201-300        | 222       | 10.8%   |
| Unknown        | 142       | 6.91%   |
| 401-500        | 138       | 6.72%   |
| 351-400        | 112       | 5.45%   |
| 601-700        | 73        | 3.55%   |
| 701-800        | 69        | 3.36%   |
| 1501-2000      | 43        | 2.09%   |
| 1001-1500      | 38        | 1.85%   |
| 801-900        | 19        | 0.92%   |
| 901-1000       | 9         | 0.44%   |
| 1-100          | 2         | 0.1%    |
| More than 2000 | 1         | 0.05%   |
| 101-200        | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1330      | 70.44%  |
| 16/10   | 277       | 14.67%  |
| Unknown | 128       | 6.78%   |
| 21/9    | 59        | 3.13%   |
| 5/4     | 48        | 2.54%   |
| 3/2     | 19        | 1.01%   |
| 4/3     | 14        | 0.74%   |
| 32/9    | 5         | 0.26%   |
| 0.62    | 3         | 0.16%   |
| 0.67    | 2         | 0.11%   |
| 3.40    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.45    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 382       | 18.51%  |
| 201-250        | 341       | 16.52%  |
| 81-90          | 284       | 13.76%  |
| 301-350        | 228       | 11.05%  |
| Unknown        | 142       | 6.88%   |
| 351-500        | 125       | 6.06%   |
| 71-80          | 113       | 5.47%   |
| 251-300        | 85        | 4.12%   |
| More than 1000 | 73        | 3.54%   |
| 151-200        | 63        | 3.05%   |
| 121-130        | 62        | 3%      |
| 61-70          | 54        | 2.62%   |
| 501-1000       | 31        | 1.5%    |
| 51-60          | 26        | 1.26%   |
| 141-150        | 17        | 0.82%   |
| 111-120        | 15        | 0.73%   |
| 131-140        | 10        | 0.48%   |
| 41-50          | 6         | 0.29%   |
| 91-100         | 5         | 0.24%   |
| 1-40           | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 637       | 31.75%  |
| 121-160       | 515       | 25.67%  |
| 101-120       | 429       | 21.39%  |
| 161-240       | 158       | 7.88%   |
| Unknown       | 142       | 7.08%   |
| More than 240 | 75        | 3.74%   |
| 1-50          | 50        | 2.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1423      | 74.19%  |
| 2     | 354       | 18.46%  |
| 0     | 98        | 5.11%   |
| 3     | 38        | 1.98%   |
| 4     | 5         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1048      | 38.81%  |
| Realtek Semiconductor                  | 812       | 30.07%  |
| Qualcomm Atheros                       | 263       | 9.74%   |
| Broadcom                               | 167       | 6.19%   |
| Broadcom Limited                       | 42        | 1.56%   |
| MediaTek                               | 35        | 1.3%    |
| Marvell Technology Group               | 29        | 1.07%   |
| Ralink                                 | 21        | 0.78%   |
| Hewlett-Packard                        | 17        | 0.63%   |
| ASIX Electronics                       | 17        | 0.63%   |
| Nvidia                                 | 15        | 0.56%   |
| Lenovo                                 | 15        | 0.56%   |
| Microsoft                              | 14        | 0.52%   |
| D-Link System                          | 14        | 0.52%   |
| ASUSTek Computer                       | 14        | 0.52%   |
| NetGear                                | 13        | 0.48%   |
| Dell                                   | 13        | 0.48%   |
| TP-Link                                | 11        | 0.41%   |
| Sierra Wireless                        | 11        | 0.41%   |
| D-Link                                 | 11        | 0.41%   |
| Ralink Technology                      | 10        | 0.37%   |
| Huawei Technologies                    | 9         | 0.33%   |
| DisplayLink                            | 9         | 0.33%   |
| Ericsson Business Mobile Networks      | 7         | 0.26%   |
| Qualcomm Atheros Communications        | 5         | 0.19%   |
| Qualcomm                               | 5         | 0.19%   |
| Fibocom                                | 5         | 0.19%   |
| Samsung Electronics                    | 4         | 0.15%   |
| Aquantia                               | 4         | 0.15%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.11%   |
| Microchip Technology                   | 3         | 0.11%   |
| Linksys                                | 3         | 0.11%   |
| Belkin Components                      | 3         | 0.11%   |
| Arduino SA                             | 3         | 0.11%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.07%   |
| Xiaomi                                 | 2         | 0.07%   |
| Wacom                                  | 2         | 0.07%   |
| Texas Instruments                      | 2         | 0.07%   |
| Standard Microsystems                  | 2         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 574       | 17.75%  |
| Intel I211 Gigabit Network Connection                             | 93        | 2.88%   |
| Intel Wireless 8265 / 8275                                        | 87        | 2.69%   |
| Intel Wi-Fi 6 AX200                                               | 87        | 2.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 64        | 1.98%   |
| Intel Wireless 7260                                               | 63        | 1.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 53        | 1.64%   |
| Intel Wireless 8260                                               | 48        | 1.48%   |
| Intel Wireless 7265                                               | 48        | 1.48%   |
| Intel Ethernet Connection (2) I219-V                              | 46        | 1.42%   |
| Intel Wi-Fi 6 AX201                                               | 41        | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 39        | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 37        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 35        | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 33        | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 32        | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 31        | 0.96%   |
| Intel Ethernet Controller I225-V                                  | 30        | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 27        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 27        | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 25        | 0.77%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 0.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 24        | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 22        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 21        | 0.65%   |
| Intel Ethernet Connection I218-LM                                 | 20        | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 19        | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 19        | 0.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 19        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 18        | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 18        | 0.56%   |
| Intel Wireless-AC 9260                                            | 18        | 0.56%   |
| Intel Wireless 3160                                               | 18        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 739       | 51.68%  |
| Qualcomm Atheros                | 201       | 14.06%  |
| Realtek Semiconductor           | 177       | 12.38%  |
| Broadcom                        | 109       | 7.62%   |
| MediaTek                        | 34        | 2.38%   |
| Broadcom Limited                | 24        | 1.68%   |
| Ralink                          | 21        | 1.47%   |
| ASUSTek Computer                | 14        | 0.98%   |
| NetGear                         | 13        | 0.91%   |
| Ralink Technology               | 10        | 0.7%    |
| D-Link System                   | 10        | 0.7%    |
| D-Link                          | 10        | 0.7%    |
| Microsoft                       | 9         | 0.63%   |
| TP-Link                         | 8         | 0.56%   |
| Sierra Wireless                 | 8         | 0.56%   |
| Dell                            | 7         | 0.49%   |
| Qualcomm Atheros Communications | 5         | 0.35%   |
| Marvell Technology Group        | 5         | 0.35%   |
| Fibocom                         | 5         | 0.35%   |
| Hewlett-Packard                 | 4         | 0.28%   |
| Qualcomm                        | 3         | 0.21%   |
| Belkin Components               | 3         | 0.21%   |
| Wacom                           | 2         | 0.14%   |
| Linksys                         | 2         | 0.14%   |
| Edimax Technology               | 2         | 0.14%   |
| Wilocity                        | 1         | 0.07%   |
| Sitecom Europe                  | 1         | 0.07%   |
| Micro Star International        | 1         | 0.07%   |
| IMC Networks                    | 1         | 0.07%   |
| Chu Yuen Enterprise             | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 87        | 6.05%   |
| Intel Wi-Fi 6 AX200                                            | 87        | 6.05%   |
| Intel Wireless 7260                                            | 63        | 4.38%   |
| Intel Wireless 8260                                            | 48        | 3.34%   |
| Intel Wireless 7265                                            | 48        | 3.34%   |
| Intel Wi-Fi 6 AX201                                            | 41        | 2.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 37        | 2.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 35        | 2.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 33        | 2.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 31        | 2.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 27        | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 27        | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 25        | 1.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 24        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 22        | 1.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 1.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 21        | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 1.32%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 19        | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 18        | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 18        | 1.25%   |
| Intel Wireless-AC 9260                                         | 18        | 1.25%   |
| Intel Wireless 3160                                            | 18        | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 18        | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 17        | 1.18%   |
| Intel Wireless 3165                                            | 16        | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 16        | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 15        | 1.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 1.04%   |
| Intel Centrino Advanced-N 6200                                 | 14        | 0.97%   |
| Intel Centrino Advanced-N 6235                                 | 13        | 0.9%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 12        | 0.83%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 12        | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 0.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 11        | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 11        | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10        | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 10        | 0.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 10        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 741       | 43.56%  |
| Intel                                  | 628       | 36.92%  |
| Qualcomm Atheros                       | 91        | 5.35%   |
| Broadcom                               | 82        | 4.82%   |
| Marvell Technology Group               | 24        | 1.41%   |
| Broadcom Limited                       | 19        | 1.12%   |
| ASIX Electronics                       | 17        | 1%      |
| Nvidia                                 | 15        | 0.88%   |
| Lenovo                                 | 14        | 0.82%   |
| DisplayLink                            | 9         | 0.53%   |
| Huawei Technologies                    | 7         | 0.41%   |
| Microsoft                              | 5         | 0.29%   |
| Hewlett-Packard                        | 5         | 0.29%   |
| D-Link System                          | 4         | 0.24%   |
| Aquantia                               | 4         | 0.24%   |
| TP-Link                                | 3         | 0.18%   |
| Sierra Wireless                        | 3         | 0.18%   |
| Samsung Electronics                    | 3         | 0.18%   |
| Microchip Technology                   | 3         | 0.18%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.12%   |
| Xiaomi                                 | 2         | 0.12%   |
| Standard Microsystems                  | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.12%   |
| Qualcomm                               | 2         | 0.12%   |
| JMicron Technology                     | 2         | 0.12%   |
| ICS Advent                             | 2         | 0.12%   |
| VIA Technologies                       | 1         | 0.06%   |
| Unknown                                | 1         | 0.06%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Linksys                                | 1         | 0.06%   |
| Gemtek                                 | 1         | 0.06%   |
| D-Link                                 | 1         | 0.06%   |
| Apple                                  | 1         | 0.06%   |
| 3Com                                   | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 574       | 32.93%  |
| Intel I211 Gigabit Network Connection                             | 93        | 5.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 3.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 64        | 3.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 53        | 3.04%   |
| Intel Ethernet Connection (2) I219-V                              | 46        | 2.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 39        | 2.24%   |
| Intel Ethernet Connection I217-LM                                 | 32        | 1.84%   |
| Intel Ethernet Controller I225-V                                  | 30        | 1.72%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 1.26%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 20        | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 1.15%   |
| Intel Ethernet Connection (2) I218-V                              | 19        | 1.09%   |
| Intel Ethernet Connection (6) I219-V                              | 18        | 1.03%   |
| Intel Ethernet Connection I219-LM                                 | 17        | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 16        | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.86%   |
| Intel I210 Gigabit Network Connection                             | 14        | 0.8%    |
| Intel Ethernet Connection I219-V                                  | 14        | 0.8%    |
| Intel Ethernet Connection I217-V                                  | 14        | 0.8%    |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11        | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.46%   |
| Intel 82566MM Gigabit Network Connection                          | 8         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.4%    |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.4%    |
| DisplayLink Dell Universal Dock D6000                             | 7         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1609      | 53.33%  |
| WiFi     | 1355      | 44.91%  |
| Modem    | 43        | 1.43%   |
| Unknown  | 10        | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1017      | 52.29%  |
| Ethernet | 926       | 47.61%  |
| Unknown  | 2         | 0.1%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 966       | 51.52%  |
| 1     | 803       | 42.83%  |
| 3     | 49        | 2.61%   |
| 0     | 40        | 2.13%   |
| 4     | 10        | 0.53%   |
| 5     | 5         | 0.27%   |
| 9     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1809      | 96.27%  |
| Yes  | 70        | 3.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 599       | 52%     |
| Realtek Semiconductor           | 79        | 6.86%   |
| Qualcomm Atheros Communications | 65        | 5.64%   |
| ASUSTek Computer                | 57        | 4.95%   |
| Apple                           | 56        | 4.86%   |
| Cambridge Silicon Radio         | 55        | 4.77%   |
| IMC Networks                    | 53        | 4.6%    |
| Broadcom                        | 48        | 4.17%   |
| Foxconn / Hon Hai               | 40        | 3.47%   |
| Lite-On Technology              | 30        | 2.6%    |
| Hewlett-Packard                 | 16        | 1.39%   |
| Dell                            | 16        | 1.39%   |
| Ralink                          | 7         | 0.61%   |
| Toshiba                         | 5         | 0.43%   |
| MediaTek                        | 5         | 0.43%   |
| Marvell Semiconductor           | 5         | 0.43%   |
| Realtek                         | 3         | 0.26%   |
| Ralink Technology               | 2         | 0.17%   |
| Micro Star International        | 2         | 0.17%   |
| HTC (High Tech Computer)        | 2         | 0.17%   |
| Chicony Electronics             | 2         | 0.17%   |
| USI                             | 1         | 0.09%   |
| Fujitsu                         | 1         | 0.09%   |
| Creative Technology             | 1         | 0.09%   |
| Alps Electric                   | 1         | 0.09%   |
| Unknown                         | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 263       | 22.73%  |
| Intel AX201 Bluetooth                               | 97        | 8.38%   |
| Intel AX200 Bluetooth                               | 83        | 7.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 62        | 5.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 55        | 4.75%   |
| Realtek Bluetooth Radio                             | 53        | 4.58%   |
| Qualcomm Atheros  Bluetooth Device                  | 32        | 2.77%   |
| Apple Bluetooth Host Controller                     | 28        | 2.42%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 26        | 2.25%   |
| IMC Networks Bluetooth Radio                        | 23        | 1.99%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 1.73%   |
| Intel AX210 Bluetooth                               | 18        | 1.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 1.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 16        | 1.38%   |
| Intel Bluetooth Device                              | 15        | 1.3%    |
| Apple Bluetooth USB Host Controller                 | 14        | 1.21%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 1.12%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 1.12%   |
| IMC Networks Bluetooth Device                       | 12        | 1.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.95%   |
| Foxconn / Hon Hai Wireless_Device                   | 10        | 0.86%   |
| Lite-On Bluetooth Device                            | 9         | 0.78%   |
| IMC Networks Wireless_Device                        | 9         | 0.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 9         | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.69%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.69%   |
| ASUS ASUS USB-BT500                                 | 8         | 0.69%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.61%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.61%   |
| Broadcom HP Portable SoftSailing                    | 7         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 0.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.52%   |
| ASUS Bluetooth Radio                                | 6         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.43%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.35%   |
| Marvell Bluetooth and Wireless LAN Composite        | 4         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1296      | 46.82%  |
| AMD                              | 568       | 20.52%  |
| Nvidia                           | 507       | 18.32%  |
| C-Media Electronics              | 50        | 1.81%   |
| Logitech                         | 35        | 1.26%   |
| Kingston Technology              | 18        | 0.65%   |
| Creative Labs                    | 16        | 0.58%   |
| SteelSeries ApS                  | 15        | 0.54%   |
| Realtek Semiconductor            | 15        | 0.54%   |
| Plantronics                      | 15        | 0.54%   |
| Texas Instruments                | 13        | 0.47%   |
| Lenovo                           | 12        | 0.43%   |
| Focusrite-Novation               | 12        | 0.43%   |
| Creative Technology              | 12        | 0.43%   |
| GN Netcom                        | 11        | 0.4%    |
| Razer USA                        | 9         | 0.33%   |
| Corsair                          | 9         | 0.33%   |
| ASUSTek Computer                 | 8         | 0.29%   |
| SAVITECH                         | 7         | 0.25%   |
| RODE Microphones                 | 7         | 0.25%   |
| Micro Star International         | 7         | 0.25%   |
| GYROCOM C&C                      | 6         | 0.22%   |
| JMTek                            | 5         | 0.18%   |
| Yamaha                           | 4         | 0.14%   |
| Sennheiser Communications        | 4         | 0.14%   |
| Hewlett-Packard                  | 4         | 0.14%   |
| Blue Microphones                 | 4         | 0.14%   |
| Antlion Audio                    | 4         | 0.14%   |
| XMOS                             | 3         | 0.11%   |
| VIA Technologies                 | 3         | 0.11%   |
| Sony                             | 3         | 0.11%   |
| Silicon Integrated Systems [SiS] | 3         | 0.11%   |
| Samsung Electronics              | 3         | 0.11%   |
| Samson Technologies              | 3         | 0.11%   |
| PreSonus Audio Electronics       | 3         | 0.11%   |
| Generalplus Technology           | 3         | 0.11%   |
| Apple                            | 3         | 0.11%   |
| Valve Software                   | 2         | 0.07%   |
| Unknown                          | 2         | 0.07%   |
| Trust                            | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 154       | 4.72%   |
| AMD Family 17h/19h HD Audio Controller                                     | 145       | 4.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 119       | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 113       | 3.47%   |
| AMD Starship/Matisse HD Audio Controller                                   | 103       | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 99        | 3.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 78        | 2.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 77        | 2.36%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 77        | 2.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 66        | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 58        | 1.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 57        | 1.75%   |
| Intel 8 Series HD Audio Controller                                         | 57        | 1.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 55        | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 52        | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 51        | 1.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 47        | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 46        | 1.41%   |
| Intel Broadwell-U Audio Controller                                         | 46        | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 46        | 1.41%   |
| Intel 200 Series PCH HD Audio                                              | 45        | 1.38%   |
| AMD FCH Azalia Controller                                                  | 45        | 1.38%   |
| Nvidia GP106 High Definition Audio Controller                              | 41        | 1.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 41        | 1.26%   |
| Nvidia GP104 High Definition Audio Controller                              | 38        | 1.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 36        | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 34        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 31        | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                               | 28        | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 28        | 0.86%   |
| Nvidia GM204 High Definition Audio Controller                              | 27        | 0.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 27        | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 27        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 26        | 0.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 26        | 0.8%    |
| Nvidia GK107 HDMI Audio Controller                                         | 25        | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 25        | 0.77%   |
| AMD Navi 10 HDMI Audio                                                     | 25        | 0.77%   |
| Intel Comet Lake PCH cAVS                                                  | 24        | 0.74%   |
| Nvidia High Definition Audio Controller                                    | 23        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 239       | 22.03%  |
| SK hynix                     | 187       | 17.24%  |
| Corsair                      | 147       | 13.55%  |
| Kingston                     | 133       | 12.26%  |
| Micron Technology            | 117       | 10.78%  |
| Unknown                      | 87        | 8.02%   |
| Crucial                      | 56        | 5.16%   |
| G.Skill                      | 30        | 2.76%   |
| Ramaxel Technology           | 15        | 1.38%   |
| Elpida                       | 12        | 1.11%   |
| A-DATA Technology            | 10        | 0.92%   |
| Unknown (ABCD)               | 9         | 0.83%   |
| Nanya Technology             | 7         | 0.65%   |
| Unknown                      | 7         | 0.65%   |
| Team                         | 3         | 0.28%   |
| Patriot                      | 3         | 0.28%   |
| Transcend                    | 2         | 0.18%   |
| Qimonda                      | 2         | 0.18%   |
| GSkill                       | 2         | 0.18%   |
| G-Alantic                    | 2         | 0.18%   |
| Avant                        | 2         | 0.18%   |
| Unknown (AB)                 | 1         | 0.09%   |
| Unknown (836D)               | 1         | 0.09%   |
| Unifosa                      | 1         | 0.09%   |
| TEXTORM                      | 1         | 0.09%   |
| SHARETRONIC                  | 1         | 0.09%   |
| Patriot Memory (PDP Systems) | 1         | 0.09%   |
| Netlist                      | 1         | 0.09%   |
| Hewlett-Packard              | 1         | 0.09%   |
| GOODRAM                      | 1         | 0.09%   |
| fef5                         | 1         | 0.09%   |
| ASint Technology             | 1         | 0.09%   |
| Apacer                       | 1         | 0.09%   |
| Ankowall                     | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 22        | 1.89%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 1.03%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.95%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 11        | 0.95%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.77%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 8         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.69%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.69%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.6%    |
| Unknown                                                          | 7         | 0.6%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 0.52%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.52%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.52%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 6         | 0.52%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.52%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.52%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 6         | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 5         | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.43%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.43%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 5         | 0.43%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 5         | 0.43%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 5         | 0.43%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 5         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 4         | 0.34%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 4         | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 0.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.34%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 4         | 0.34%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.34%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 4         | 0.34%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.34%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.34%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 469       | 48.15%  |
| DDR3    | 313       | 32.14%  |
| LPDDR4  | 52        | 5.34%   |
| DDR2    | 37        | 3.8%    |
| LPDDR3  | 34        | 3.49%   |
| SDRAM   | 23        | 2.36%   |
| Unknown | 18        | 1.85%   |
| DDR5    | 11        | 1.13%   |
| DDR     | 8         | 0.82%   |
| LPDDR5  | 6         | 0.62%   |
| DRAM    | 3         | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 512       | 52.62%  |
| DIMM         | 363       | 37.31%  |
| Row Of Chips | 82        | 8.43%   |
| Chip         | 11        | 1.13%   |
| Unknown      | 4         | 0.41%   |
| FB-DIMM      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 407       | 39.06%  |
| 4096    | 255       | 24.47%  |
| 16384   | 187       | 17.95%  |
| 2048    | 130       | 12.48%  |
| 1024    | 29        | 2.78%   |
| 32768   | 28        | 2.69%   |
| 512     | 5         | 0.48%   |
| Unknown | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 204       | 19.58%  |
| 3200    | 131       | 12.57%  |
| 2667    | 121       | 11.61%  |
| 2400    | 79        | 7.58%   |
| 2133    | 74        | 7.1%    |
| 1333    | 55        | 5.28%   |
| 3600    | 54        | 5.18%   |
| 4267    | 26        | 2.5%    |
| 667     | 25        | 2.4%    |
| 1867    | 24        | 2.3%    |
| 1334    | 24        | 2.3%    |
| Unknown | 18        | 1.73%   |
| 800     | 17        | 1.63%   |
| 3466    | 16        | 1.54%   |
| 3400    | 12        | 1.15%   |
| 1067    | 12        | 1.15%   |
| 3000    | 11        | 1.06%   |
| 4800    | 10        | 0.96%   |
| 4266    | 10        | 0.96%   |
| 1066    | 10        | 0.96%   |
| 3733    | 8         | 0.77%   |
| 3266    | 8         | 0.77%   |
| 2666    | 8         | 0.77%   |
| 6400    | 7         | 0.67%   |
| 1800    | 7         | 0.67%   |
| 4199    | 6         | 0.58%   |
| 1866    | 6         | 0.58%   |
| 2933    | 5         | 0.48%   |
| 3866    | 4         | 0.38%   |
| 3800    | 4         | 0.38%   |
| 2747    | 4         | 0.38%   |
| 8400    | 3         | 0.29%   |
| 49926   | 2         | 0.19%   |
| 3933    | 2         | 0.19%   |
| 3151    | 2         | 0.19%   |
| 3100    | 2         | 0.19%   |
| 2800    | 2         | 0.19%   |
| 2600    | 2         | 0.19%   |
| 2048    | 2         | 0.19%   |
| 2000    | 2         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 12        | 40%     |
| Brother Industries    | 6         | 20%     |
| Samsung Electronics   | 5         | 16.67%  |
| Canon                 | 3         | 10%     |
| Seiko Epson           | 2         | 6.67%   |
| Oki Data              | 1         | 3.33%   |
| Lexmark International | 1         | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 6.67%   |
| HP LaserJet 1020                     | 2         | 6.67%   |
| Seiko Epson XP-4100 Series           | 1         | 3.33%   |
| Seiko Epson Printer                  | 1         | 3.33%   |
| Samsung SCX-3200 Series              | 1         | 3.33%   |
| Samsung M2070 Series                 | 1         | 3.33%   |
| Samsung Color Laser Printer          | 1         | 3.33%   |
| Oki Data USB Device                  | 1         | 3.33%   |
| Lexmark International MX317dn        | 1         | 3.33%   |
| HP OfficeJet Pro 8730                | 1         | 3.33%   |
| HP OfficeJet G55                     | 1         | 3.33%   |
| HP LaserJet P2035                    | 1         | 3.33%   |
| HP LaserJet 1320                     | 1         | 3.33%   |
| HP ENVY 4520 series                  | 1         | 3.33%   |
| HP DeskJet 5650c                     | 1         | 3.33%   |
| HP Deskjet 3050 J610 series          | 1         | 3.33%   |
| HP DeskJet 2700 series               | 1         | 3.33%   |
| HP DeskJet 2130 series               | 1         | 3.33%   |
| HP Color LaserJet CP1215             | 1         | 3.33%   |
| Canon LiDE 300                       | 1         | 3.33%   |
| Canon LBP7010C/7018C                 | 1         | 3.33%   |
| Canon LBP6200                        | 1         | 3.33%   |
| Brother QL-500 label printer         | 1         | 3.33%   |
| Brother HL-5150D series              | 1         | 3.33%   |
| Brother HL-2270DW Laser Printer      | 1         | 3.33%   |
| Brother HL-2130 series               | 1         | 3.33%   |
| Brother DCP-7055W                    | 1         | 3.33%   |
| Brother DCP-7040                     | 1         | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 87.5%   |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                | 2         | 25%     |
| HP ScanJet 2200c                       | 1         | 12.5%   |
| Canon CanoScan LiDE 700F               | 1         | 12.5%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 12.5%   |
| Canon CanoScan LiDE 210                | 1         | 12.5%   |
| Canon CanoScan LiDE 120                | 1         | 12.5%   |
| Canon CanoScan LiDE 110                | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 236       | 22.5%   |
| Microdia                               | 100       | 9.53%   |
| IMC Networks                           | 87        | 8.29%   |
| Logitech                               | 85        | 8.1%    |
| Realtek Semiconductor                  | 66        | 6.29%   |
| Acer                                   | 52        | 4.96%   |
| Sunplus Innovation Technology          | 48        | 4.58%   |
| Apple                                  | 45        | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 40        | 3.81%   |
| Quanta                                 | 36        | 3.43%   |
| Lite-On Technology                     | 35        | 3.34%   |
| Bison Electronics                      | 31        | 2.96%   |
| Syntek                                 | 30        | 2.86%   |
| Suyin                                  | 25        | 2.38%   |
| Samsung Electronics                    | 13        | 1.24%   |
| Luxvisions Innotech Limited            | 11        | 1.05%   |
| Ricoh                                  | 10        | 0.95%   |
| Microsoft                              | 10        | 0.95%   |
| Lenovo                                 | 9         | 0.86%   |
| Alcor Micro                            | 8         | 0.76%   |
| Silicon Motion                         | 7         | 0.67%   |
| ALi                                    | 6         | 0.57%   |
| Z-Star Microelectronics                | 5         | 0.48%   |
| Creative Technology                    | 5         | 0.48%   |
| Primax Electronics                     | 4         | 0.38%   |
| Trust                                  | 3         | 0.29%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.29%   |
| Generalplus Technology                 | 3         | 0.29%   |
| DigiTech                               | 3         | 0.29%   |
| ARC International                      | 3         | 0.29%   |
| Sunplus Technology                     | 2         | 0.19%   |
| LG Electronics                         | 2         | 0.19%   |
| Importek                               | 2         | 0.19%   |
| Valve Software                         | 1         | 0.1%    |
| Tobii Technology AB                    | 1         | 0.1%    |
| SunplusIT                              | 1         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.1%    |
| Sony                                   | 1         | 0.1%    |
| Sonix Technology                       | 1         | 0.1%    |
| Polycom                                | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 54        | 5.1%    |
| Microdia Integrated_Webcam_HD                                            | 46        | 4.35%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 34        | 3.21%   |
| IMC Networks Integrated Camera                                           | 26        | 2.46%   |
| Realtek Integrated_Webcam_HD                                             | 24        | 2.27%   |
| Syntek Integrated Camera                                                 | 23        | 2.17%   |
| Chicony HD WebCam                                                        | 21        | 1.98%   |
| Logitech Webcam C270                                                     | 16        | 1.51%   |
| Logitech HD Pro Webcam C920                                              | 16        | 1.51%   |
| Chicony HP HD Camera                                                     | 16        | 1.51%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                          | 14        | 1.32%   |
| Acer Integrated Camera                                                   | 14        | 1.32%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 13        | 1.23%   |
| Sunplus HD Webcam                                                        | 12        | 1.13%   |
| Logitech C922 Pro Stream Webcam                                          | 12        | 1.13%   |
| Lite-On HP HD Camera                                                     | 12        | 1.13%   |
| Acer Lenovo EasyCamera                                                   | 11        | 1.04%   |
| Sunplus Integrated_Webcam_HD                                             | 10        | 0.95%   |
| Quanta HP HD Camera                                                      | 10        | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 10        | 0.95%   |
| Bison SunplusIT Integrated Camera                                        | 10        | 0.95%   |
| Apple FaceTime HD Camera (Built-in)                                      | 10        | 0.95%   |
| Apple Built-in iSight                                                    | 10        | 0.95%   |
| Lite-On Integrated Camera                                                | 9         | 0.85%   |
| Lite-On HP HD Webcam                                                     | 9         | 0.85%   |
| Chicony HP HD Webcam                                                     | 9         | 0.85%   |
| Bison Integrated Camera                                                  | 9         | 0.85%   |
| Apple FaceTime HD Camera                                                 | 9         | 0.85%   |
| Quanta HD User Facing                                                    | 8         | 0.76%   |
| Microdia USB 2.0 Camera                                                  | 8         | 0.76%   |
| Chicony HP HD Webcam [Fixed]                                             | 8         | 0.76%   |
| Acer EasyCamera                                                          | 8         | 0.76%   |
| Syntek Lenovo EasyCamera                                                 | 7         | 0.66%   |
| Realtek USB2.0 HD UVC WebCam                                             | 7         | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 7         | 0.66%   |
| Chicony HP Wide Vision HD Camera                                         | 7         | 0.66%   |
| Chicony HP Truevision HD                                                 | 7         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 7         | 0.66%   |
| Suyin HP TrueVision HD                                                   | 6         | 0.57%   |
| Logitech Webcam C930e                                                    | 6         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 115       | 43.4%   |
| Synaptics                  | 76        | 28.68%  |
| Shenzhen Goodix Technology | 27        | 10.19%  |
| Elan Microelectronics      | 12        | 4.53%   |
| Upek                       | 11        | 4.15%   |
| AuthenTec                  | 11        | 4.15%   |
| LighTuning Technology      | 7         | 2.64%   |
| STMicroelectronics         | 6         | 2.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 40        | 15.09%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 5.66%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 5.28%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 4.91%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 4.91%   |
| Validity Sensors VFS491                                                    | 11        | 4.15%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 3.77%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.4%    |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.4%    |
| Synaptics WBDI                                                             | 8         | 3.02%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 3.02%   |
| Elan ELAN:Fingerprint                                                      | 8         | 3.02%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 2.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.26%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.26%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.89%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.89%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 1.89%   |
| AuthenTec AES2810                                                          | 5         | 1.89%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.89%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.51%   |
| Synaptics UWP WBDI                                                         | 4         | 1.51%   |
| Synaptics  WBDI                                                            | 4         | 1.51%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 1.51%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.13%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.13%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.13%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 3         | 1.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.13%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.13%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.75%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.75%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.75%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.75%   |
| Unknown                                                                    | 2         | 0.75%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.38%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 57        | 41.61%  |
| Alcor Micro                       | 55        | 40.15%  |
| O2 Micro                          | 10        | 7.3%    |
| Upek                              | 4         | 2.92%   |
| Lenovo                            | 4         | 2.92%   |
| Gemalto (was Gemplus)             | 2         | 1.46%   |
| Yubico.com                        | 1         | 0.73%   |
| VASCO Data Security International | 1         | 0.73%   |
| Hewlett-Packard                   | 1         | 0.73%   |
| Chicony Electronics               | 1         | 0.73%   |
| Cherry                            | 1         | 0.73%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 52        | 37.96%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 12.41%  |
| Broadcom 58200                                                               | 16        | 11.68%  |
| Broadcom 5880                                                                | 12        | 8.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 8.03%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 5.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.92%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 2.92%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 2.19%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.46%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.46%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 0.73%   |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.73%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.73%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.73%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.73%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.73%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1256      | 65.62%  |
| 1     | 503       | 26.28%  |
| 2     | 131       | 6.84%   |
| 3     | 16        | 0.84%   |
| 4     | 7         | 0.37%   |
| 7     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 263       | 32.19%  |
| Graphics card            | 146       | 17.87%  |
| Chipcard                 | 120       | 14.69%  |
| Net/wireless             | 74        | 9.06%   |
| Multimedia controller    | 52        | 6.36%   |
| Communication controller | 41        | 5.02%   |
| Camera                   | 27        | 3.3%    |
| Unassigned class         | 22        | 2.69%   |
| Bluetooth                | 21        | 2.57%   |
| Sound                    | 16        | 1.96%   |
| Card reader              | 11        | 1.35%   |
| Net/ethernet             | 7         | 0.86%   |
| Storage                  | 4         | 0.49%   |
| Storage/ata              | 2         | 0.24%   |
| Network                  | 2         | 0.24%   |
| Modem                    | 2         | 0.24%   |
| Flash memory             | 2         | 0.24%   |
| Storage/raid             | 1         | 0.12%   |
| Storage/nvme             | 1         | 0.12%   |
| Storage/ide              | 1         | 0.12%   |
| Firewire controller      | 1         | 0.12%   |
| Dvb card                 | 1         | 0.12%   |

