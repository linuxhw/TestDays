BigLinux - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for BigLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/BigLinux/Desktop/README.md) and [notebooks](/Dist/BigLinux/Notebook/README.md).

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

Total: 186

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [b81a572516](https://linux-hardware.org/?probe=b81a572516) | May 09, 2024 |
| PCWare        | IPMH61R3                    | Desktop     | [1f3c6428d2](https://linux-hardware.org/?probe=1f3c6428d2) | May 09, 2024 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [1168634a54](https://linux-hardware.org/?probe=1168634a54) | May 06, 2024 |
| Itautec       | Itautec                     | Notebook    | [cb012e89fc](https://linux-hardware.org/?probe=cb012e89fc) | May 06, 2024 |
| Itautec       | Itautec                     | Notebook    | [e1d6b279b9](https://linux-hardware.org/?probe=e1d6b279b9) | May 06, 2024 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [ee738361ee](https://linux-hardware.org/?probe=ee738361ee) | May 01, 2024 |
| Positivo      | POS-RAX300ES 11191478       | Desktop     | [3e201c7230](https://linux-hardware.org/?probe=3e201c7230) | Apr 26, 2024 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [59fff37f7f](https://linux-hardware.org/?probe=59fff37f7f) | Apr 24, 2024 |
| HP            | Victus by Gaming Laptop     | Notebook    | [7178fbf1eb](https://linux-hardware.org/?probe=7178fbf1eb) | Apr 23, 2024 |
| HP            | EliteBook Folio 9470m       | Notebook    | [72485d4ec0](https://linux-hardware.org/?probe=72485d4ec0) | Apr 20, 2024 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [8d6d79b4d7](https://linux-hardware.org/?probe=8d6d79b4d7) | Apr 13, 2024 |
| MSI           | B350 TOMAHAWK               | Desktop     | [e80bbf7d11](https://linux-hardware.org/?probe=e80bbf7d11) | Apr 12, 2024 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [94efe11b98](https://linux-hardware.org/?probe=94efe11b98) | Apr 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [96271e0269](https://linux-hardware.org/?probe=96271e0269) | Apr 10, 2024 |
| Gigabyte      | H77-D3H                     | Desktop     | [647ad74796](https://linux-hardware.org/?probe=647ad74796) | Apr 07, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [4fc00ab41f](https://linux-hardware.org/?probe=4fc00ab41f) | Apr 01, 2024 |
| Google        | Blooguard                   | Notebook    | [6c7218afa7](https://linux-hardware.org/?probe=6c7218afa7) | Mar 27, 2024 |
| Google        | Blooguard                   | Notebook    | [583f5aada6](https://linux-hardware.org/?probe=583f5aada6) | Mar 25, 2024 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [85db87031e](https://linux-hardware.org/?probe=85db87031e) | Mar 23, 2024 |
| ASRock        | Z390 Phantom Gaming 4S-I... | Desktop     | [2d0dc9eb8a](https://linux-hardware.org/?probe=2d0dc9eb8a) | Mar 22, 2024 |
| ASUSTek       | X541SA                      | Notebook    | [4f1901506d](https://linux-hardware.org/?probe=4f1901506d) | Mar 22, 2024 |
| HP            | ENVY TS m7                  | Notebook    | [2b3732863e](https://linux-hardware.org/?probe=2b3732863e) | Mar 21, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [e660816556](https://linux-hardware.org/?probe=e660816556) | Mar 20, 2024 |
| HP            | Laptop 15-bs1xx             | Notebook    | [fa1b40fdce](https://linux-hardware.org/?probe=fa1b40fdce) | Mar 17, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [73b6e42771](https://linux-hardware.org/?probe=73b6e42771) | Mar 16, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [92707b25ae](https://linux-hardware.org/?probe=92707b25ae) | Mar 14, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [ad99c77be4](https://linux-hardware.org/?probe=ad99c77be4) | Mar 13, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS2... | Convertible | [ed6bb738cc](https://linux-hardware.org/?probe=ed6bb738cc) | Mar 03, 2024 |
| Acer          | TravelMate 5740             | Notebook    | [b1366802c6](https://linux-hardware.org/?probe=b1366802c6) | Mar 01, 2024 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [2ca44d747e](https://linux-hardware.org/?probe=2ca44d747e) | Feb 29, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [270dd04b52](https://linux-hardware.org/?probe=270dd04b52) | Feb 28, 2024 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [a187c17778](https://linux-hardware.org/?probe=a187c17778) | Feb 20, 2024 |
| Multilaser    | UB820                       | All in one  | [61d0d3731f](https://linux-hardware.org/?probe=61d0d3731f) | Feb 14, 2024 |
| Lenovo        | Yoga Book 9 13IRU8 82YQ     | Convertible | [d765abe84c](https://linux-hardware.org/?probe=d765abe84c) | Feb 11, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [3790ad9e05](https://linux-hardware.org/?probe=3790ad9e05) | Feb 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [975b3a3b77](https://linux-hardware.org/?probe=975b3a3b77) | Feb 05, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [20ca543652](https://linux-hardware.org/?probe=20ca543652) | Jan 29, 2024 |
| Lenovo        | G50-80 80R0                 | Notebook    | [980165425e](https://linux-hardware.org/?probe=980165425e) | Jan 27, 2024 |
| Lenovo        | G50-80 80R0                 | Notebook    | [eeee227df0](https://linux-hardware.org/?probe=eeee227df0) | Jan 26, 2024 |
| HP            | 8617                        | Desktop     | [4ea51313bd](https://linux-hardware.org/?probe=4ea51313bd) | Jan 15, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c8f6ccf6a8](https://linux-hardware.org/?probe=c8f6ccf6a8) | Jan 13, 2024 |
| Gigabyte      | A520M H                     | Desktop     | [0394447477](https://linux-hardware.org/?probe=0394447477) | Jan 12, 2024 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [d109d298a5](https://linux-hardware.org/?probe=d109d298a5) | Jan 11, 2024 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [585f20355c](https://linux-hardware.org/?probe=585f20355c) | Jan 11, 2024 |
| Digiboard     | NM70-TI                     | Desktop     | [9f740d246e](https://linux-hardware.org/?probe=9f740d246e) | Jan 08, 2024 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [daf43e4658](https://linux-hardware.org/?probe=daf43e4658) | Jan 02, 2024 |
| Lenovo        | ThinkCentre M91p 7005A21    | Desktop     | [043bcfc503](https://linux-hardware.org/?probe=043bcfc503) | Dec 31, 2023 |
| Lenovo        | ThinkCentre M91p 7005A21    | Desktop     | [e783d0ce11](https://linux-hardware.org/?probe=e783d0ce11) | Dec 31, 2023 |
| OEM           | B75 Ver:1.41                | Desktop     | [4117a986c8](https://linux-hardware.org/?probe=4117a986c8) | Dec 16, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [de83793263](https://linux-hardware.org/?probe=de83793263) | Dec 16, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [a960a2a5b7](https://linux-hardware.org/?probe=a960a2a5b7) | Dec 10, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [e04ad23cd3](https://linux-hardware.org/?probe=e04ad23cd3) | Dec 10, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [b5f0453a4b](https://linux-hardware.org/?probe=b5f0453a4b) | Dec 09, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [b5f3fbe4c5](https://linux-hardware.org/?probe=b5f3fbe4c5) | Dec 09, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b4efc55410](https://linux-hardware.org/?probe=b4efc55410) | Dec 05, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [15d4dc2fe9](https://linux-hardware.org/?probe=15d4dc2fe9) | Dec 05, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [b71e5d49a4](https://linux-hardware.org/?probe=b71e5d49a4) | Dec 04, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [638021e67d](https://linux-hardware.org/?probe=638021e67d) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [626135b546](https://linux-hardware.org/?probe=626135b546) | Dec 04, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [c4839c409c](https://linux-hardware.org/?probe=c4839c409c) | Dec 02, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [0dc4701502](https://linux-hardware.org/?probe=0dc4701502) | Dec 02, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [561cad738d](https://linux-hardware.org/?probe=561cad738d) | Dec 02, 2023 |
| Unknown       | Unknown                     | Notebook    | [ecae393240](https://linux-hardware.org/?probe=ecae393240) | Dec 02, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [c5dd65037d](https://linux-hardware.org/?probe=c5dd65037d) | Nov 29, 2023 |
| Positivo      | POS-EIH61CQ POSITIVO        | Desktop     | [bed32da0ed](https://linux-hardware.org/?probe=bed32da0ed) | Nov 26, 2023 |
| Positivo      | C41TF                       | Notebook    | [09be1cbd3a](https://linux-hardware.org/?probe=09be1cbd3a) | Nov 25, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c24820ad94](https://linux-hardware.org/?probe=c24820ad94) | Nov 24, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [688d81c63c](https://linux-hardware.org/?probe=688d81c63c) | Nov 22, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [713583bc52](https://linux-hardware.org/?probe=713583bc52) | Nov 22, 2023 |
| Intel         | B75                         | Desktop     | [0620da2ddb](https://linux-hardware.org/?probe=0620da2ddb) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d6c8994c15](https://linux-hardware.org/?probe=d6c8994c15) | Nov 20, 2023 |
| HP            | 1495                        | Desktop     | [c03adda1fa](https://linux-hardware.org/?probe=c03adda1fa) | Nov 20, 2023 |
| HP            | Pavilion g4                 | Notebook    | [37d7289eb6](https://linux-hardware.org/?probe=37d7289eb6) | Nov 16, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [fd1be084ac](https://linux-hardware.org/?probe=fd1be084ac) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [3113cdd229](https://linux-hardware.org/?probe=3113cdd229) | Nov 11, 2023 |
| Positivo      | C41TF                       | Notebook    | [4bb5f6150c](https://linux-hardware.org/?probe=4bb5f6150c) | Nov 06, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [f6db4cc5a7](https://linux-hardware.org/?probe=f6db4cc5a7) | Oct 31, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [35fabc6811](https://linux-hardware.org/?probe=35fabc6811) | Oct 31, 2023 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [439b0a3497](https://linux-hardware.org/?probe=439b0a3497) | Oct 28, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [65494c95ec](https://linux-hardware.org/?probe=65494c95ec) | Oct 23, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [f904697713](https://linux-hardware.org/?probe=f904697713) | Oct 23, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [be03ed57d8](https://linux-hardware.org/?probe=be03ed57d8) | Oct 20, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [e648a8c32a](https://linux-hardware.org/?probe=e648a8c32a) | Oct 20, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [50aa4fc1e1](https://linux-hardware.org/?probe=50aa4fc1e1) | Oct 18, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [952772fde5](https://linux-hardware.org/?probe=952772fde5) | Oct 14, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [673113259c](https://linux-hardware.org/?probe=673113259c) | Oct 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [d45a6f5bf2](https://linux-hardware.org/?probe=d45a6f5bf2) | Oct 14, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [0592faaf34](https://linux-hardware.org/?probe=0592faaf34) | Oct 12, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [cd9071e2ad](https://linux-hardware.org/?probe=cd9071e2ad) | Oct 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7508b7cf4f](https://linux-hardware.org/?probe=7508b7cf4f) | Oct 10, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [45a4c0fbe0](https://linux-hardware.org/?probe=45a4c0fbe0) | Oct 06, 2023 |
| Dell          | Latitude E6420              | Notebook    | [90883fd019](https://linux-hardware.org/?probe=90883fd019) | Oct 02, 2023 |
| Intel         | H61                         | Desktop     | [5dd60be36a](https://linux-hardware.org/?probe=5dd60be36a) | Sep 14, 2023 |
| PCWare        | IPMH81G1                    | Desktop     | [181367c2db](https://linux-hardware.org/?probe=181367c2db) | Sep 12, 2023 |
| Biostar       | G31M+                       | Desktop     | [24eb0eb2db](https://linux-hardware.org/?probe=24eb0eb2db) | Sep 06, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [73e3b8ef8a](https://linux-hardware.org/?probe=73e3b8ef8a) | Sep 04, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [332e78dfba](https://linux-hardware.org/?probe=332e78dfba) | Sep 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [9cf292357b](https://linux-hardware.org/?probe=9cf292357b) | Aug 30, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| ASUSTek       | X455LA                      | Notebook    | [8b60fb0411](https://linux-hardware.org/?probe=8b60fb0411) | Aug 08, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [30ea6db008](https://linux-hardware.org/?probe=30ea6db008) | Jul 23, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [e699ffe719](https://linux-hardware.org/?probe=e699ffe719) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [a2487119a6](https://linux-hardware.org/?probe=a2487119a6) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [f9a1d993b2](https://linux-hardware.org/?probe=f9a1d993b2) | Jul 07, 2023 |
| ASUSTek       | VX7SX                       | Notebook    | [2ef4295d22](https://linux-hardware.org/?probe=2ef4295d22) | Jul 05, 2023 |
| Positivo      | Q464B                       | Notebook    | [9dad5f0aa1](https://linux-hardware.org/?probe=9dad5f0aa1) | Jul 02, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [3aa4a11068](https://linux-hardware.org/?probe=3aa4a11068) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [3a8a822af9](https://linux-hardware.org/?probe=3a8a822af9) | Jun 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [5223ed2efd](https://linux-hardware.org/?probe=5223ed2efd) | Jun 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e25224b362](https://linux-hardware.org/?probe=e25224b362) | Jun 13, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [613d703a17](https://linux-hardware.org/?probe=613d703a17) | Jun 10, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [91d11f8da1](https://linux-hardware.org/?probe=91d11f8da1) | Jun 04, 2023 |
| Toshiba       | STI 005492G                 | Desktop     | [4f161f4ed0](https://linux-hardware.org/?probe=4f161f4ed0) | May 26, 2023 |
| LG Electro... | V720                        | All in one  | [686e013b62](https://linux-hardware.org/?probe=686e013b62) | May 25, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [ebd65238d8](https://linux-hardware.org/?probe=ebd65238d8) | May 22, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [696014fc68](https://linux-hardware.org/?probe=696014fc68) | May 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [620668d216](https://linux-hardware.org/?probe=620668d216) | Apr 25, 2023 |
| Dell          | G15 5520                    | Notebook    | [d2cc8527a5](https://linux-hardware.org/?probe=d2cc8527a5) | Apr 23, 2023 |
| HP            | 1495                        | Desktop     | [96283c0a09](https://linux-hardware.org/?probe=96283c0a09) | Apr 01, 2023 |
| HP            | 1495                        | Desktop     | [f25125625a](https://linux-hardware.org/?probe=f25125625a) | Apr 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e3a13c69ef](https://linux-hardware.org/?probe=e3a13c69ef) | Apr 01, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [ebe6cc115e](https://linux-hardware.org/?probe=ebe6cc115e) | Mar 22, 2023 |
| Clevo         | W340EU                      | Notebook    | [fb9df7f581](https://linux-hardware.org/?probe=fb9df7f581) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [176b7d75bf](https://linux-hardware.org/?probe=176b7d75bf) | Mar 18, 2023 |
| Avell High... | STORM TWO                   | Notebook    | [e6b20084b5](https://linux-hardware.org/?probe=e6b20084b5) | Mar 16, 2023 |
| HP            | 3397                        | Desktop     | [0b74e11cdd](https://linux-hardware.org/?probe=0b74e11cdd) | Mar 12, 2023 |
| HP            | 1495                        | Desktop     | [058beaa7d1](https://linux-hardware.org/?probe=058beaa7d1) | Mar 12, 2023 |
| HP            | 1495                        | Desktop     | [517a7a6401](https://linux-hardware.org/?probe=517a7a6401) | Mar 12, 2023 |
| Lenovo        | NOK                         | Desktop     | [2e90ce2e87](https://linux-hardware.org/?probe=2e90ce2e87) | Mar 10, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [066cc238c4](https://linux-hardware.org/?probe=066cc238c4) | Feb 26, 2023 |
| Intel         | H61                         | Desktop     | [5e26cd7b85](https://linux-hardware.org/?probe=5e26cd7b85) | Feb 23, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [789bcfe82f](https://linux-hardware.org/?probe=789bcfe82f) | Feb 22, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [7c6973f1fa](https://linux-hardware.org/?probe=7c6973f1fa) | Feb 21, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [4bcfe32668](https://linux-hardware.org/?probe=4bcfe32668) | Feb 12, 2023 |
| Intel         | H61                         | Desktop     | [81e14fd083](https://linux-hardware.org/?probe=81e14fd083) | Feb 08, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [3f958de9bb](https://linux-hardware.org/?probe=3f958de9bb) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [fd498f882b](https://linux-hardware.org/?probe=fd498f882b) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [009adbd75c](https://linux-hardware.org/?probe=009adbd75c) | Jan 18, 2023 |
| Intel         | H55                         | Desktop     | [4fdea85eec](https://linux-hardware.org/?probe=4fdea85eec) | Jan 14, 2023 |
| Intel         | H55                         | Desktop     | [d875a18037](https://linux-hardware.org/?probe=d875a18037) | Jan 14, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b1a7adefab](https://linux-hardware.org/?probe=b1a7adefab) | Jan 09, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [12b3654541](https://linux-hardware.org/?probe=12b3654541) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [89e97c7099](https://linux-hardware.org/?probe=89e97c7099) | Nov 29, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d0d37dd251](https://linux-hardware.org/?probe=d0d37dd251) | Nov 17, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [16dc745785](https://linux-hardware.org/?probe=16dc745785) | Nov 16, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [9b43ddbe11](https://linux-hardware.org/?probe=9b43ddbe11) | Nov 09, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8e89ed396e](https://linux-hardware.org/?probe=8e89ed396e) | Nov 05, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [8cb2cd8c19](https://linux-hardware.org/?probe=8cb2cd8c19) | Oct 26, 2022 |
| eMachines     | EMCP61M                     | Desktop     | [711594c5b4](https://linux-hardware.org/?probe=711594c5b4) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [75502d8d96](https://linux-hardware.org/?probe=75502d8d96) | Oct 09, 2022 |
| Dell          | System XPS L502X            | Notebook    | [cd40a3f168](https://linux-hardware.org/?probe=cd40a3f168) | Oct 08, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [94c783f944](https://linux-hardware.org/?probe=94c783f944) | Sep 11, 2022 |
| ASUSTek       | X45U                        | Notebook    | [3efe835653](https://linux-hardware.org/?probe=3efe835653) | Aug 22, 2022 |
| Positivo      | C14RV01                     | Notebook    | [818c67da93](https://linux-hardware.org/?probe=818c67da93) | Aug 21, 2022 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [43a16c5e88](https://linux-hardware.org/?probe=43a16c5e88) | Aug 21, 2022 |
| Sony          | VGN-NR230AE                 | Notebook    | [ba78970975](https://linux-hardware.org/?probe=ba78970975) | Aug 15, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [0efc94e34d](https://linux-hardware.org/?probe=0efc94e34d) | Jul 24, 2022 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [cfd6e87e09](https://linux-hardware.org/?probe=cfd6e87e09) | Jul 23, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [2f8b49e4f8](https://linux-hardware.org/?probe=2f8b49e4f8) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [c30806c628](https://linux-hardware.org/?probe=c30806c628) | Jul 23, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [b805fa0cd8](https://linux-hardware.org/?probe=b805fa0cd8) | Jul 23, 2022 |
| Positivo      | C14RV01                     | Notebook    | [fc6fa07b38](https://linux-hardware.org/?probe=fc6fa07b38) | Sep 10, 2021 |
| Acer          | Predator G9-793             | Notebook    | [6004b8b462](https://linux-hardware.org/?probe=6004b8b462) | Jun 24, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [e58da0d3ca](https://linux-hardware.org/?probe=e58da0d3ca) | Jun 23, 2021 |
| Acer          | Predator G9-793             | Notebook    | [ae4824f52e](https://linux-hardware.org/?probe=ae4824f52e) | Jun 20, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [41512cfc6a](https://linux-hardware.org/?probe=41512cfc6a) | Jun 20, 2021 |
| ECS           | H67H2-M2                    | Desktop     | [d82e4c4eb4](https://linux-hardware.org/?probe=d82e4c4eb4) | Apr 10, 2021 |
| Positivo      | C14RV01                     | Notebook    | [36efae3128](https://linux-hardware.org/?probe=36efae3128) | Feb 03, 2021 |
| Acer          | A315-41                     | Notebook    | [021dc9110e](https://linux-hardware.org/?probe=021dc9110e) | Nov 11, 2020 |
| Lenovo        | ThinkPad T410 25379N2       | Notebook    | [ed777f25b7](https://linux-hardware.org/?probe=ed777f25b7) | Nov 09, 2020 |
| Dell          | Inspiron 3480               | Notebook    | [1f0823c074](https://linux-hardware.org/?probe=1f0823c074) | Oct 13, 2020 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [0c4cd978f2](https://linux-hardware.org/?probe=0c4cd978f2) | Jul 24, 2020 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [3cef63e59d](https://linux-hardware.org/?probe=3cef63e59d) | Jul 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [8b89f99351](https://linux-hardware.org/?probe=8b89f99351) | Jul 17, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [07fb6950a2](https://linux-hardware.org/?probe=07fb6950a2) | Jul 11, 2020 |
| PCWare        | IPX1800E2                   | Desktop     | [0990462881](https://linux-hardware.org/?probe=0990462881) | Jun 21, 2020 |
| PCWare        | IPX1800E2                   | Desktop     | [93916c17f2](https://linux-hardware.org/?probe=93916c17f2) | Jun 21, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [0e5ac5a0bf](https://linux-hardware.org/?probe=0e5ac5a0bf) | Jun 12, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [a4f3841c00](https://linux-hardware.org/?probe=a4f3841c00) | May 29, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [3fe70d9fdd](https://linux-hardware.org/?probe=3fe70d9fdd) | May 06, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [8fa9935547](https://linux-hardware.org/?probe=8fa9935547) | Apr 27, 2020 |
| Lenovo        | IdeaPad Z470                | Notebook    | [3a8f141df4](https://linux-hardware.org/?probe=3a8f141df4) | Mar 28, 2020 |
| Alienware     | 17                          | Notebook    | [14abe97f88](https://linux-hardware.org/?probe=14abe97f88) | Oct 23, 2019 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [419565138f](https://linux-hardware.org/?probe=419565138f) | Aug 30, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| BigLinux                  | 40        | 28.17%  |
| BigLinux 20.04            | 11        | 7.75%   |
| BigLinux 23.0.0           | 7         | 4.93%   |
| BigLinux 22.0.0           | 6         | 4.23%   |
| BigLinux 19.04            | 5         | 3.52%   |
| BigLinux 22.1.0           | 4         | 2.82%   |
| BigLinux 22.0.4           | 4         | 2.82%   |
| BigLinux 23.1.4           | 3         | 2.11%   |
| BigLinux 23.1.0           | 3         | 2.11%   |
| BigLinux 21.3.7           | 3         | 2.11%   |
| BigLinux 21.3.5           | 3         | 2.11%   |
| BigLinux 2024-03-15_05-13 | 3         | 2.11%   |
| BigLinux 2024-03-08_05-13 | 3         | 2.11%   |
| BigLinux 23.1.3           | 2         | 1.41%   |
| BigLinux 23.02.20         | 2         | 1.41%   |
| BigLinux 23.0.3           | 2         | 1.41%   |
| BigLinux 23.0.1           | 2         | 1.41%   |
| BigLinux 2023-12-01_05-13 | 2         | 1.41%   |
| BigLinux 2023-06-30_08-01 | 2         | 1.41%   |
| BigLinux 23.1.2           | 1         | 0.7%    |
| BigLinux 23.02.24         | 1         | 0.7%    |
| BigLinux 23.02.07         | 1         | 0.7%    |
| BigLinux 23.01.30         | 1         | 0.7%    |
| BigLinux 23.01.06         | 1         | 0.7%    |
| BigLinux 23.0.4           | 1         | 0.7%    |
| BigLinux 22.12.24         | 1         | 0.7%    |
| BigLinux 22.11.19         | 1         | 0.7%    |
| BigLinux 22.11.14         | 1         | 0.7%    |
| BigLinux 22.10.28         | 1         | 0.7%    |
| BigLinux 22.10.06         | 1         | 0.7%    |
| BigLinux 22.1.1           | 1         | 0.7%    |
| BigLinux 22.09.09         | 1         | 0.7%    |
| BigLinux 22.0.5           | 1         | 0.7%    |
| BigLinux 22.0.2           | 1         | 0.7%    |
| BigLinux 21.3.6           | 1         | 0.7%    |
| BigLinux 21.1.2           | 1         | 0.7%    |
| BigLinux 2024-05-03_00-50 | 1         | 0.7%    |
| BigLinux 2024-05-01_19-57 | 1         | 0.7%    |
| BigLinux 2024-02-23_05-13 | 1         | 0.7%    |
| BigLinux 2024-02-23_05-09 | 1         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| BigLinux | 137       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 6.1.55-1-MANJARO           | 7         | 4.73%   |
| 6.6.19-1-MANJARO           | 6         | 4.05%   |
| 6.6.26-1-MANJARO           | 5         | 3.38%   |
| 6.1.64-1-MANJARO           | 5         | 3.38%   |
| 6.5.5-1-MANJARO            | 4         | 2.7%    |
| 6.1.71-1-MANJARO           | 4         | 2.7%    |
| 6.1.62-1-MANJARO           | 4         | 2.7%    |
| 6.1.31-2-MANJARO           | 4         | 2.7%    |
| 6.1.12-1-MANJARO           | 4         | 2.7%    |
| 6.6.3-1-MANJARO            | 3         | 2.03%   |
| 6.1.23-1-MANJARO           | 3         | 2.03%   |
| 5.15.94-1-MANJARO          | 3         | 2.03%   |
| 5.15.85-1-MANJARO          | 3         | 2.03%   |
| 5.15.60-1-MANJARO          | 3         | 2.03%   |
| 6.8.5-1-MANJARO            | 2         | 1.35%   |
| 6.8.0-1-MANJARO            | 2         | 1.35%   |
| 6.7.7-1-MANJARO            | 2         | 1.35%   |
| 6.6.10-1-MANJARO           | 2         | 1.35%   |
| 6.5.11-1-MANJARO           | 2         | 1.35%   |
| 6.4.12-1-MANJARO           | 2         | 1.35%   |
| 6.2.12-1-MANJARO           | 2         | 1.35%   |
| 6.1.80-1-MANJARO           | 2         | 1.35%   |
| 6.1.69-1-MANJARO           | 2         | 1.35%   |
| 6.1.51-1-MANJARO           | 2         | 1.35%   |
| 6.0.8-1-MANJARO            | 2         | 1.35%   |
| 5.8.0-43-generic           | 2         | 1.35%   |
| 5.4.0-37-generic           | 2         | 1.35%   |
| 5.2.8-xanmod8              | 2         | 1.35%   |
| 5.15.78-1-MANJARO          | 2         | 1.35%   |
| 5.15.71-1-MANJARO          | 2         | 1.35%   |
| 5.15.102-1-MANJARO         | 2         | 1.35%   |
| 6.8.8-2-MANJARO            | 1         | 0.68%   |
| 6.8.4-1-MANJARO            | 1         | 0.68%   |
| 6.7.4-2-MANJARO            | 1         | 0.68%   |
| 6.7.10-x64v2-xanmod1-1     | 1         | 0.68%   |
| 6.7.0-4-MANJARO            | 1         | 0.68%   |
| 6.7.0-0-MANJARO            | 1         | 0.68%   |
| 6.6.8-2-MANJARO            | 1         | 0.68%   |
| 6.6.5-x64v2-xanmod1-1      | 1         | 0.68%   |
| 6.6.22-x64v2-xanmod1-1-lts | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.55   | 7         | 4.76%   |
| 6.6.19   | 6         | 4.08%   |
| 6.1.64   | 6         | 4.08%   |
| 6.6.26   | 5         | 3.4%    |
| 6.1.62   | 5         | 3.4%    |
| 6.5.5    | 4         | 2.72%   |
| 6.1.71   | 4         | 2.72%   |
| 6.1.31   | 4         | 2.72%   |
| 6.1.12   | 4         | 2.72%   |
| 5.8.0    | 4         | 2.72%   |
| 5.4.0    | 4         | 2.72%   |
| 6.6.3    | 3         | 2.04%   |
| 6.1.23   | 3         | 2.04%   |
| 5.15.94  | 3         | 2.04%   |
| 5.15.85  | 3         | 2.04%   |
| 5.15.60  | 3         | 2.04%   |
| 6.8.5    | 2         | 1.36%   |
| 6.8.0    | 2         | 1.36%   |
| 6.7.7    | 2         | 1.36%   |
| 6.7.0    | 2         | 1.36%   |
| 6.6.10   | 2         | 1.36%   |
| 6.5.11   | 2         | 1.36%   |
| 6.4.12   | 2         | 1.36%   |
| 6.3.5    | 2         | 1.36%   |
| 6.2.12   | 2         | 1.36%   |
| 6.1.9    | 2         | 1.36%   |
| 6.1.80   | 2         | 1.36%   |
| 6.1.69   | 2         | 1.36%   |
| 6.1.51   | 2         | 1.36%   |
| 6.0.8    | 2         | 1.36%   |
| 5.2.8    | 2         | 1.36%   |
| 5.15.78  | 2         | 1.36%   |
| 5.15.71  | 2         | 1.36%   |
| 5.15.102 | 2         | 1.36%   |
| 6.8.8    | 1         | 0.68%   |
| 6.8.4    | 1         | 0.68%   |
| 6.7.4    | 1         | 0.68%   |
| 6.7.10   | 1         | 0.68%   |
| 6.6.8    | 1         | 0.68%   |
| 6.6.5    | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 46        | 33.09%  |
| 6.6     | 22        | 15.83%  |
| 5.15    | 19        | 13.67%  |
| 6.5     | 7         | 5.04%   |
| 6.8     | 6         | 4.32%   |
| 6.7     | 6         | 4.32%   |
| 5.8     | 4         | 2.88%   |
| 5.4     | 4         | 2.88%   |
| 5.10    | 4         | 2.88%   |
| 6.4     | 3         | 2.16%   |
| 6.3     | 3         | 2.16%   |
| 6.2     | 3         | 2.16%   |
| 5.2     | 3         | 2.16%   |
| 6.0     | 2         | 1.44%   |
| 5.9     | 1         | 0.72%   |
| 5.7     | 1         | 0.72%   |
| 5.6     | 1         | 0.72%   |
| 5.3     | 1         | 0.72%   |
| 5.19    | 1         | 0.72%   |
| 5.17    | 1         | 0.72%   |
| 5.16    | 1         | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 137       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 126       | 91.97%  |
| KDE      | 6         | 4.38%   |
| Unknown  | 2         | 1.46%   |
| XFCE     | 1         | 0.73%   |
| Deepin   | 1         | 0.73%   |
| Cinnamon | 1         | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 134       | 97.1%   |
| Wayland | 3         | 2.17%   |
| Unknown | 1         | 0.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 86        | 62.32%  |
| Unknown | 47        | 34.06%  |
| LightDM | 4         | 2.9%    |
| LXDM    | 1         | 0.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| pt_BR   | 77        | 56.2%   |
| en_US   | 23        | 16.79%  |
| pl_PL   | 8         | 5.84%   |
| es_MX   | 4         | 2.92%   |
| en_GB   | 4         | 2.92%   |
| pt_PT   | 3         | 2.19%   |
| de_DE   | 3         | 2.19%   |
| el_GR   | 2         | 1.46%   |
| Unknown | 2         | 1.46%   |
| tr_TR   | 1         | 0.73%   |
| it_IT   | 1         | 0.73%   |
| fr_FR   | 1         | 0.73%   |
| fr_BE   | 1         | 0.73%   |
| fi_FI   | 1         | 0.73%   |
| es_ES   | 1         | 0.73%   |
| es_CR   | 1         | 0.73%   |
| es_CO   | 1         | 0.73%   |
| es_AR   | 1         | 0.73%   |
| en_AU   | 1         | 0.73%   |
| de_AT   | 1         | 0.73%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 90        | 64.75%  |
| BIOS | 49        | 35.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 122       | 89.05%  |
| Ext4    | 10        | 7.3%    |
| Overlay | 3         | 2.19%   |
| Tmpfs   | 1         | 0.73%   |
| Unknown | 1         | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 68        | 48.57%  |
| Unknown | 49        | 35%     |
| MBR     | 23        | 16.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 132       | 95.65%  |
| Yes       | 6         | 4.35%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 62.32%  |
| Yes       | 52        | 37.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 21        | 15.33%  |
| Lenovo                 | 19        | 13.87%  |
| Gigabyte Technology    | 14        | 10.22%  |
| Hewlett-Packard        | 13        | 9.49%   |
| Acer                   | 11        | 8.03%   |
| Intel                  | 9         | 6.57%   |
| Dell                   | 8         | 5.84%   |
| Positivo               | 6         | 4.38%   |
| PCWare                 | 3         | 2.19%   |
| MSI                    | 3         | 2.19%   |
| ASRock                 | 3         | 2.19%   |
| Apple                  | 3         | 2.19%   |
| Semp Toshiba           | 2         | 1.46%   |
| Samsung Electronics    | 2         | 1.46%   |
| Multilaser             | 2         | 1.46%   |
| Microsoft              | 2         | 1.46%   |
| Google                 | 2         | 1.46%   |
| Toshiba                | 1         | 0.73%   |
| Sony                   | 1         | 0.73%   |
| OEM                    | 1         | 0.73%   |
| Itautec                | 1         | 0.73%   |
| eMachines              | 1         | 0.73%   |
| ECS                    | 1         | 0.73%   |
| Digiboard              | 1         | 0.73%   |
| Daten Tecnologia       | 1         | 0.73%   |
| Clevo                  | 1         | 0.73%   |
| Biostar                | 1         | 0.73%   |
| BESSTAR Tech           | 1         | 0.73%   |
| Avell High Performance | 1         | 0.73%   |
| Alienware              | 1         | 0.73%   |
| Unknown                | 1         | 0.73%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Intel H61                           | 3         | 2.19%   |
| Positivo C41TF                      | 2         | 1.46%   |
| HP Compaq 8200 Elite SFF PC         | 2         | 1.46%   |
| Google Blooguard                    | 2         | 1.46%   |
| ASUS VivoBook_ASUSLaptop M5602RA    | 2         | 1.46%   |
| ASRock 775Dual-VSTA                 | 2         | 1.46%   |
| Toshiba Satellite S55-A             | 1         | 0.73%   |
| Sony VGN-NR230AE                    | 1         | 0.73%   |
| Semp Toshiba STI                    | 1         | 0.73%   |
| Semp Toshiba IS 1412                | 1         | 0.73%   |
| Samsung 550XCJ/550XCR               | 1         | 0.73%   |
| Samsung 300E5M/300E5L               | 1         | 0.73%   |
| Positivo Q464B                      | 1         | 0.73%   |
| Positivo POS-EIH61CQ                | 1         | 0.73%   |
| Positivo C4400                      | 1         | 0.73%   |
| Positivo C14RV01                    | 1         | 0.73%   |
| PCWare IPX1800E2                    | 1         | 0.73%   |
| PCWare IPMH81G1                     | 1         | 0.73%   |
| PCWare IPMH61R3                     | 1         | 0.73%   |
| OEM B75                             | 1         | 0.73%   |
| Multilaser UB82X                    | 1         | 0.73%   |
| Multilaser MLSH1H LINUX             | 1         | 0.73%   |
| MSI MS-7C95                         | 1         | 0.73%   |
| MSI MS-7C91                         | 1         | 0.73%   |
| MSI Cyborg 15 A12VF                 | 1         | 0.73%   |
| Microsoft Surface Pro 3             | 1         | 0.73%   |
| Microsoft Surface Pro               | 1         | 0.73%   |
| Lenovo Yoga Slim 7 14ARE05 82A2     | 1         | 0.73%   |
| Lenovo Yoga Book 9 13IRU8 82YQ      | 1         | 0.73%   |
| Lenovo Yoga 910-13IKB 80VF          | 1         | 0.73%   |
| Lenovo Yoga 520-14IKB 80YM          | 1         | 0.73%   |
| Lenovo ThinkPad Yoga 370 20JJS25D0H | 1         | 0.73%   |
| Lenovo ThinkPad T480s 20L70028US    | 1         | 0.73%   |
| Lenovo ThinkPad T410 25379N2        | 1         | 0.73%   |
| Lenovo ThinkCentre M93p 10AB0010US  | 1         | 0.73%   |
| Lenovo ThinkCentre M91p 7005A21     | 1         | 0.73%   |
| Lenovo ThinkCentre M710s 10M8SBAT00 | 1         | 0.73%   |
| Lenovo IdeaPad Z470                 | 1         | 0.73%   |
| Lenovo IdeaPad S400 VIUS3           | 1         | 0.73%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7    | 1         | 0.73%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo IdeaPad       | 7         | 5.11%   |
| ASUS VivoBook        | 6         | 4.38%   |
| Acer Aspire          | 5         | 3.65%   |
| Lenovo Yoga          | 4         | 2.92%   |
| Lenovo ThinkPad      | 3         | 2.19%   |
| Lenovo ThinkCentre   | 3         | 2.19%   |
| Intel H61            | 3         | 2.19%   |
| HP Compaq            | 3         | 2.19%   |
| Dell Inspiron        | 3         | 2.19%   |
| ASUS TUF             | 3         | 2.19%   |
| ASUS PRIME           | 3         | 2.19%   |
| Acer Nitro           | 3         | 2.19%   |
| Positivo C41TF       | 2         | 1.46%   |
| Microsoft Surface    | 2         | 1.46%   |
| HP EliteBook         | 2         | 1.46%   |
| HP 255               | 2         | 1.46%   |
| Google Blooguard     | 2         | 1.46%   |
| Gigabyte A520M       | 2         | 1.46%   |
| Dell System          | 2         | 1.46%   |
| ASRock 775Dual-VSTA  | 2         | 1.46%   |
| Toshiba Satellite    | 1         | 0.73%   |
| Sony VGN-NR230AE     | 1         | 0.73%   |
| Semp Toshiba STI     | 1         | 0.73%   |
| Semp Toshiba IS      | 1         | 0.73%   |
| Samsung 550XCJ       | 1         | 0.73%   |
| Samsung 300E5M       | 1         | 0.73%   |
| Positivo Q464B       | 1         | 0.73%   |
| Positivo POS-EIH61CQ | 1         | 0.73%   |
| Positivo C4400       | 1         | 0.73%   |
| Positivo C14RV01     | 1         | 0.73%   |
| PCWare IPX1800E2     | 1         | 0.73%   |
| PCWare IPMH81G1      | 1         | 0.73%   |
| PCWare IPMH61R3      | 1         | 0.73%   |
| OEM B75              | 1         | 0.73%   |
| Multilaser UB82X     | 1         | 0.73%   |
| Multilaser MLSH1H    | 1         | 0.73%   |
| MSI MS-7C95          | 1         | 0.73%   |
| MSI MS-7C91          | 1         | 0.73%   |
| MSI Cyborg           | 1         | 0.73%   |
| Lenovo G50-80        | 1         | 0.73%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2017 | 15        | 10.95%  |
| 2021 | 13        | 9.49%   |
| 2022 | 12        | 8.76%   |
| 2020 | 12        | 8.76%   |
| 2011 | 11        | 8.03%   |
| 2012 | 10        | 7.3%    |
| 2013 | 9         | 6.57%   |
| 2023 | 8         | 5.84%   |
| 2016 | 8         | 5.84%   |
| 2018 | 7         | 5.11%   |
| 2014 | 6         | 4.38%   |
| 2019 | 5         | 3.65%   |
| 2010 | 5         | 3.65%   |
| 2009 | 5         | 3.65%   |
| 2015 | 4         | 2.92%   |
| 2007 | 3         | 2.19%   |
| 2008 | 2         | 1.46%   |
| 2006 | 2         | 1.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 69        | 50.36%  |
| Desktop     | 60        | 43.8%   |
| Convertible | 4         | 2.92%   |
| Tablet      | 2         | 1.46%   |
| Mini pc     | 1         | 0.73%   |
| All in one  | 1         | 0.73%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 136       | 99.27%  |
| Enabled  | 1         | 0.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 135       | 98.54%  |
| Yes  | 2         | 1.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 33        | 23.91%  |
| 3.01-4.0    | 29        | 21.01%  |
| 4.01-8.0    | 25        | 18.12%  |
| 32.01-64.0  | 19        | 13.77%  |
| 16.01-24.0  | 19        | 13.77%  |
| 1.01-2.0    | 5         | 3.62%   |
| 2.01-3.0    | 4         | 2.9%    |
| 24.01-32.0  | 3         | 2.17%   |
| 64.01-256.0 | 1         | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 50        | 34.72%  |
| 1.01-2.0   | 48        | 33.33%  |
| 3.01-4.0   | 16        | 11.11%  |
| 4.01-8.0   | 13        | 9.03%   |
| 0.51-1.0   | 10        | 6.94%   |
| 8.01-16.0  | 5         | 3.47%   |
| 24.01-32.0 | 1         | 0.69%   |
| 0.01-0.5   | 1         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 75        | 53.96%  |
| 2      | 29        | 20.86%  |
| 3      | 20        | 14.39%  |
| 4      | 9         | 6.47%   |
| 6      | 3         | 2.16%   |
| 9      | 1         | 0.72%   |
| 5      | 1         | 0.72%   |
| 0      | 1         | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 65.94%  |
| Yes       | 47        | 34.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 85.4%   |
| No        | 20        | 14.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 76.64%  |
| No        | 32        | 23.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 64.96%  |
| No        | 48        | 35.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Brazil       | 80        | 58.39%  |
| USA          | 16        | 11.68%  |
| Poland       | 7         | 5.11%   |
| UK           | 5         | 3.65%   |
| Portugal     | 4         | 2.92%   |
| Mexico       | 4         | 2.92%   |
| Greece       | 4         | 2.92%   |
| Germany      | 3         | 2.19%   |
| Turkey       | 1         | 0.73%   |
| Spain        | 1         | 0.73%   |
| Saudi Arabia | 1         | 0.73%   |
| Japan        | 1         | 0.73%   |
| Italy        | 1         | 0.73%   |
| Ghana        | 1         | 0.73%   |
| France       | 1         | 0.73%   |
| Finland      | 1         | 0.73%   |
| Costa Rica   | 1         | 0.73%   |
| Colombia     | 1         | 0.73%   |
| Belgium      | 1         | 0.73%   |
| Austria      | 1         | 0.73%   |
| Australia    | 1         | 0.73%   |
| Argentina    | 1         | 0.73%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Sao Paulo              | 7         | 5%      |
| Rio de Janeiro         | 5         | 3.57%   |
| Brasília              | 4         | 2.86%   |
| Belo Horizonte         | 4         | 2.86%   |
| Maringá               | 3         | 2.14%   |
| Clarksville            | 3         | 2.14%   |
| Thessaloniki           | 2         | 1.43%   |
| Sao Domingos do Capim  | 2         | 1.43%   |
| Fortaleza              | 2         | 1.43%   |
| Curitiba               | 2         | 1.43%   |
| Castanhal              | 2         | 1.43%   |
| Caratinga              | 2         | 1.43%   |
| Campo Grande           | 2         | 1.43%   |
| Belém                 | 2         | 1.43%   |
| Zdzieszowice           | 1         | 0.71%   |
| Wiener Neustadt        | 1         | 0.71%   |
| Vitória da Conquista  | 1         | 0.71%   |
| Villa Bosch            | 1         | 0.71%   |
| Vila Velha             | 1         | 0.71%   |
| Vila Nova de Famalicao | 1         | 0.71%   |
| Venda do Pinheiro      | 1         | 0.71%   |
| Tychy                  | 1         | 0.71%   |
| Tramandai              | 1         | 0.71%   |
| Torun                  | 1         | 0.71%   |
| Tokyo                  | 1         | 0.71%   |
| Tlajomulco de Zuniga   | 1         | 0.71%   |
| Timon                  | 1         | 0.71%   |
| The Villages           | 1         | 0.71%   |
| Texarkana              | 1         | 0.71%   |
| Szczyrk                | 1         | 0.71%   |
| Stralsund              | 1         | 0.71%   |
| Springfield            | 1         | 0.71%   |
| Sparti                 | 1         | 0.71%   |
| Serafina Correa        | 1         | 0.71%   |
| Schwenksville          | 1         | 0.71%   |
| Sao Paulo das Missoes  | 1         | 0.71%   |
| Sao José dos Pinhais  | 1         | 0.71%   |
| Sao Jose do Rio Preto  | 1         | 0.71%   |
| Sao Joaquim da Barra   | 1         | 0.71%   |
| Santo André           | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 35        | 47     | 15.15%  |
| Seagate                        | 30        | 44     | 12.99%  |
| Samsung Electronics            | 19        | 22     | 8.23%   |
| Kingston                       | 16        | 20     | 6.93%   |
| Toshiba                        | 12        | 13     | 5.19%   |
| China                          | 10        | 12     | 4.33%   |
| Hitachi                        | 9         | 15     | 3.9%    |
| Unknown                        | 8         | 8      | 3.46%   |
| SanDisk                        | 8         | 8      | 3.46%   |
| Crucial                        | 8         | 8      | 3.46%   |
| KingSpec                       | 6         | 6      | 2.6%    |
| MAXIO Technology (Hangzhou)    | 5         | 5      | 2.16%   |
| ADATA Technology               | 5         | 5      | 2.16%   |
| SK hynix                       | 4         | 4      | 1.73%   |
| Silicon Motion                 | 4         | 5      | 1.73%   |
| Micron Technology              | 4         | 4      | 1.73%   |
| Realtek Semiconductor          | 3         | 3      | 1.3%    |
| PNY                            | 3         | 4      | 1.3%    |
| Micron/Crucial Technology      | 3         | 3      | 1.3%    |
| HGST                           | 3         | 4      | 1.3%    |
| A-DATA Technology              | 3         | 4      | 1.3%    |
| XrayDisk                       | 2         | 2      | 0.87%   |
| Solid State Storage Technology | 2         | 2      | 0.87%   |
| Netac                          | 2         | 3      | 0.87%   |
| LITEON                         | 2         | 3      | 0.87%   |
| Kingston Technology Company    | 2         | 2      | 0.87%   |
| JMicron Technology             | 2         | 2      | 0.87%   |
| GOODRAM                        | 2         | 4      | 0.87%   |
| Apacer                         | 2         | 2      | 0.87%   |
| WALRAM                         | 1         | 1      | 0.43%   |
| Team                           | 1         | 2      | 0.43%   |
| T-FORCE                        | 1         | 1      | 0.43%   |
| PRO Z                          | 1         | 1      | 0.43%   |
| Plextor                        | 1         | 1      | 0.43%   |
| Pichau                         | 1         | 1      | 0.43%   |
| NT-1TB                         | 1         | 1      | 0.43%   |
| KIOXIA                         | 1         | 1      | 0.43%   |
| Intel                          | 1         | 1      | 0.43%   |
| Inland                         | 1         | 1      | 0.43%   |
| EYOTA                          | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 5         | 2.02%   |
| Kingston SA400S37240G 240GB SSD                       | 5         | 2.02%   |
| WDC WD10SPZX-21Z10T0 1TB                              | 4         | 1.61%   |
| Unknown MMC Card  64GB                                | 4         | 1.61%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB    | 4         | 1.61%   |
| WDC WD10SPZX-80Z10T2 1TB                              | 3         | 1.21%   |
| Toshiba MQ04ABF100 1TB                                | 3         | 1.21%   |
| Toshiba MQ01ABD050V -63 500GB                         | 3         | 1.21%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3         | 1.21%   |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 3         | 1.21%   |
| Seagate ST500DM002-1BD142 500GB                       | 3         | 1.21%   |
| Seagate ST1000DM010-2EP102 1TB                        | 3         | 1.21%   |
| Kingston SV300S37A240G 240GB SSD                      | 3         | 1.21%   |
| Kingston SA400S37480G 480GB SSD                       | 3         | 1.21%   |
| Toshiba DT01ACA050 500GB                              | 2         | 0.81%   |
| Seagate ST4000DM004-2CV104 4TB                        | 2         | 0.81%   |
| Seagate ST320LM001 HN-M320MBB 320GB                   | 2         | 0.81%   |
| Seagate Backup+ Hub BK 8TB                            | 2         | 0.81%   |
| Micron/Crucial CT500P5SSD8 500GB                      | 2         | 0.81%   |
| KingSpec P3-512 512GB SSD                             | 2         | 0.81%   |
| JMicron Tech 250GB                                    | 2         | 0.81%   |
| Hitachi HDS721050DLE630 500GB                         | 2         | 0.81%   |
| Hitachi HDS721010CLA332 1TB                           | 2         | 0.81%   |
| Crucial CT500MX500SSD1 500GB                          | 2         | 0.81%   |
| Crucial CT480BX500SSD1 480GB                          | 2         | 0.81%   |
| China SSD 120GB                                       | 2         | 0.81%   |
| XrayDisk 512GB SSD                                    | 1         | 0.4%    |
| XrayDisk 120GB                                        | 1         | 0.4%    |
| WDC WDS480G2G0A-00JH30 480GB SSD                      | 1         | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD                      | 1         | 0.4%    |
| WDC WDS100T2G0A-00JH30 1TB SSD                        | 1         | 0.4%    |
| WDC WD800BD-22MRA1 80GB                               | 1         | 0.4%    |
| WDC WD800AAJS-75M0A0 80GB                             | 1         | 0.4%    |
| WDC WD7500BPKX-75HPJT0 752GB                          | 1         | 0.4%    |
| WDC WD5000LPVX-75V0TT0 500GB                          | 1         | 0.4%    |
| WDC WD5000LPVX-60V0TT0 500GB                          | 1         | 0.4%    |
| WDC WD5000LPVT-08G33T1 500GB                          | 1         | 0.4%    |
| WDC WD5000LPCX-24VHAT0 500GB                          | 1         | 0.4%    |
| WDC WD5000AVDS-63U7B1 500GB                           | 1         | 0.4%    |
| WDC WD5000AAKX-60U6AA0 500GB                          | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 32        | 43     | 35.16%  |
| Seagate             | 30        | 44     | 32.97%  |
| Toshiba             | 11        | 12     | 12.09%  |
| Hitachi             | 9         | 15     | 9.89%   |
| Samsung Electronics | 3         | 5      | 3.3%    |
| HGST                | 3         | 4      | 3.3%    |
| Unknown             | 1         | 1      | 1.1%    |
| ASMedia             | 1         | 1      | 1.1%    |
| Apple               | 1         | 2      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 13        | 16     | 16.67%  |
| China               | 10        | 12     | 12.82%  |
| Samsung Electronics | 8         | 9      | 10.26%  |
| Crucial             | 8         | 8      | 10.26%  |
| KingSpec            | 6         | 6      | 7.69%   |
| SanDisk             | 5         | 5      | 6.41%   |
| WDC                 | 4         | 4      | 5.13%   |
| PNY                 | 3         | 4      | 3.85%   |
| A-DATA Technology   | 3         | 4      | 3.85%   |
| Micron Technology   | 2         | 2      | 2.56%   |
| LITEON              | 2         | 3      | 2.56%   |
| GOODRAM             | 2         | 4      | 2.56%   |
| Apacer              | 2         | 2      | 2.56%   |
| XrayDisk            | 1         | 1      | 1.28%   |
| Toshiba             | 1         | 1      | 1.28%   |
| Team                | 1         | 2      | 1.28%   |
| T-FORCE             | 1         | 1      | 1.28%   |
| Plextor             | 1         | 1      | 1.28%   |
| Pichau              | 1         | 1      | 1.28%   |
| NT-1TB              | 1         | 1      | 1.28%   |
| Inland              | 1         | 1      | 1.28%   |
| BHT                 | 1         | 1      | 1.28%   |
| Unknown             | 1         | 1      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 71        | 127    | 36.22%  |
| SSD     | 66        | 90     | 33.67%  |
| NVMe    | 45        | 51     | 22.96%  |
| Unknown | 8         | 9      | 4.08%   |
| MMC     | 6         | 6      | 3.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 110       | 212    | 63.95%  |
| NVMe | 45        | 51     | 26.16%  |
| SAS  | 11        | 14     | 6.4%    |
| MMC  | 6         | 6      | 3.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 120    | 55.48%  |
| 0.51-1.0   | 49        | 71     | 33.56%  |
| 1.01-2.0   | 6         | 10     | 4.11%   |
| 3.01-4.0   | 4         | 9      | 2.74%   |
| 4.01-10.0  | 4         | 5      | 2.74%   |
| 2.01-3.0   | 1         | 1      | 0.68%   |
| 10.01-20.0 | 1         | 1      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 32        | 23.19%  |
| 2001-3000      | 31        | 22.46%  |
| 251-500        | 22        | 15.94%  |
| More than 3000 | 17        | 12.32%  |
| 501-1000       | 17        | 12.32%  |
| 101-250        | 14        | 10.14%  |
| 1-20           | 3         | 2.17%   |
| 51-100         | 2         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 37        | 25.69%  |
| 51-100         | 37        | 25.69%  |
| 251-500        | 18        | 12.5%   |
| 101-250        | 18        | 12.5%   |
| 501-1000       | 17        | 11.81%  |
| 1-20           | 11        | 7.64%   |
| 2001-3000      | 3         | 2.08%   |
| More than 3000 | 2         | 1.39%   |
| 1001-2000      | 1         | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                  | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050V -63 500GB          | 2         | 2      | 10%     |
| WDC WD800AAJS-75M0A0 80GB              | 1         | 1      | 5%      |
| WDC WD5000AAKX-60U6AA0 500GB           | 1         | 1      | 5%      |
| WDC WD5000AAKX-08U6AA0 500GB           | 1         | 1      | 5%      |
| WDC WD3200BPVT-00JJ5T0 320GB           | 1         | 3      | 5%      |
| WDC WD1001FALS-41Y6A1 1TB              | 1         | 2      | 5%      |
| Seagate ST9250410AS 250GB              | 1         | 1      | 5%      |
| Seagate ST9100824AS 100GB              | 1         | 1      | 5%      |
| Seagate ST8000AS0002-1NA17Z 8TB        | 1         | 1      | 5%      |
| Seagate ST500DM002-1BD142 500GB        | 1         | 2      | 5%      |
| Seagate ST3320613AS 320GB              | 1         | 1      | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1         | 1      | 5%      |
| Hitachi HTS727575A9E364 752GB          | 1         | 1      | 5%      |
| Hitachi HTS545032A7E380 320GB          | 1         | 1      | 5%      |
| Hitachi HDS721050DLE630 500GB          | 1         | 1      | 5%      |
| Crucial CT500MX200SSD3 500GB           | 1         | 1      | 5%      |
| China SATA SSD 240GB                   | 1         | 1      | 5%      |
| ADATA Technology SM2P32A8-512GC1 512GB | 1         | 1      | 5%      |
| A-DATA Technology SU630 240GB SSD      | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 7      | 30%     |
| WDC               | 5         | 8      | 25%     |
| Hitachi           | 3         | 3      | 15%     |
| Toshiba           | 2         | 2      | 10%     |
| Crucial           | 1         | 1      | 5%      |
| China             | 1         | 1      | 5%      |
| ADATA Technology  | 1         | 1      | 5%      |
| A-DATA Technology | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 7      | 37.5%   |
| WDC     | 5         | 8      | 31.25%  |
| Hitachi | 3         | 3      | 18.75%  |
| Toshiba | 2         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 20     | 77.78%  |
| SSD  | 3         | 3      | 16.67%  |
| NVMe | 1         | 1      | 5.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 93        | 181    | 59.62%  |
| Works    | 45        | 77     | 28.85%  |
| Malfunc  | 17        | 24     | 10.9%   |
| Failed   | 1         | 1      | 0.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 91        | 52.6%   |
| AMD                            | 22        | 12.72%  |
| Samsung Electronics            | 7         | 4.05%   |
| Kingston Technology Company    | 6         | 3.47%   |
| MAXIO Technology (Hangzhou)    | 5         | 2.89%   |
| ADATA Technology               | 5         | 2.89%   |
| SK hynix                       | 4         | 2.31%   |
| Silicon Motion                 | 4         | 2.31%   |
| SanDisk                        | 3         | 1.73%   |
| Realtek Semiconductor          | 3         | 1.73%   |
| Micron/Crucial Technology      | 3         | 1.73%   |
| JMicron Technology             | 3         | 1.73%   |
| VIA Technologies               | 2         | 1.16%   |
| Solid State Storage Technology | 2         | 1.16%   |
| Nvidia                         | 2         | 1.16%   |
| Netac Technology               | 2         | 1.16%   |
| Micron Technology              | 2         | 1.16%   |
| Marvell Technology Group       | 2         | 1.16%   |
| ASMedia Technology             | 2         | 1.16%   |
| Phison Electronics             | 1         | 0.58%   |
| Lite-On IT Corp. / Plextor     | 1         | 0.58%   |
| KIOXIA                         | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 6.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 4.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 4.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 4.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 7         | 3.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 3.61%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7         | 3.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 2.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 2.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 2.06%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 4         | 2.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 2.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 2.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 2.06%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3         | 1.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.55%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 1.55%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2         | 1.03%   |
| VIA VT8237A SATA 2-Port Controller                                                      | 2         | 1.03%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                       | 2         | 1.03%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 2         | 1.03%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                                | 2         | 1.03%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                        | 2         | 1.03%   |
| Kingston Company NV2 NVMe SSD E21T (DRAM-less)                                          | 2         | 1.03%   |
| JMicron JMB368 IDE controller                                                           | 2         | 1.03%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.03%   |
| Intel Tiger Lake SATA AHCI Controller                                                   | 2         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.03%   |
| ADATA SM2P41C3 NVMe SSD (DRAM-less)                                                     | 2         | 1.03%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                                  | 1         | 0.52%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                          | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 100       | 59.17%  |
| NVMe | 44        | 26.04%  |
| IDE  | 16        | 9.47%   |
| RAID | 9         | 5.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 107       | 78.1%   |
| AMD    | 30        | 21.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 4         | 2.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 2.19%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.19%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3         | 2.19%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 2.19%   |
| AMD Ryzen 5 4600G with Radeon Graphics      | 3         | 2.19%   |
| Intel Pentium D CPU 3.00GHz                 | 2         | 1.46%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2         | 1.46%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 1.46%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2         | 1.46%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 1.46%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.46%   |
| Intel Celeron N4120 CPU @ 1.10GHz           | 2         | 1.46%   |
| AMD Ryzen 7 6800H with Radeon Graphics      | 2         | 1.46%   |
| AMD Ryzen 5 5600 6-Core Processor           | 2         | 1.46%   |
| Intel Xeon CPU E5-2603 v3 @ 1.60GHz         | 1         | 0.73%   |
| Intel Xeon CPU E5-2420 v2 @ 2.20GHz         | 1         | 0.73%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.73%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.73%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz | 1         | 0.73%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.73%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.73%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz      | 1         | 0.73%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.73%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.73%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 0.73%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 0.73%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.73%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.73%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.73%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.73%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.73%   |
| Intel Core i7-3667U CPU @ 2.00GHz           | 1         | 0.73%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 0.73%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.73%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 0.73%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1         | 0.73%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 0.73%   |
| Intel Core i7 CPU S 860 @ 2.53GHz           | 1         | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 34        | 24.82%  |
| Intel Core i7           | 21        | 15.33%  |
| Intel Core i3           | 13        | 9.49%   |
| AMD Ryzen 5             | 13        | 9.49%   |
| Other                   | 11        | 8.03%   |
| Intel Celeron           | 11        | 8.03%   |
| AMD Ryzen 7             | 7         | 5.11%   |
| Intel Pentium Dual-Core | 4         | 2.92%   |
| Intel Xeon              | 2         | 1.46%   |
| Intel Pentium Dual      | 2         | 1.46%   |
| Intel Pentium D         | 2         | 1.46%   |
| Intel Pentium           | 2         | 1.46%   |
| Intel Core 2 Duo        | 2         | 1.46%   |
| AMD Ryzen 5 PRO         | 2         | 1.46%   |
| Intel Pentium Silver    | 1         | 0.73%   |
| Intel Core 2 Quad       | 1         | 0.73%   |
| Intel Core 2            | 1         | 0.73%   |
| Intel Atom              | 1         | 0.73%   |
| AMD Ryzen Threadripper  | 1         | 0.73%   |
| AMD Ryzen 9             | 1         | 0.73%   |
| AMD Phenom II X6        | 1         | 0.73%   |
| AMD FX                  | 1         | 0.73%   |
| AMD C-70                | 1         | 0.73%   |
| AMD C-60                | 1         | 0.73%   |
| AMD Athlon              | 1         | 0.73%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 56        | 40.88%  |
| 4      | 45        | 32.85%  |
| 6      | 18        | 13.14%  |
| 8      | 9         | 6.57%   |
| 12     | 4         | 2.92%   |
| 10     | 3         | 2.19%   |
| 14     | 1         | 0.73%   |
| 1      | 1         | 0.73%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 99.27%  |
| 2      | 1         | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 87        | 63.5%   |
| 1      | 50        | 36.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 136       | 99.27%  |
| Unknown        | 1         | 0.73%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 34.31%  |
| 0x206a7    | 13        | 9.49%   |
| 0x806e9    | 6         | 4.38%   |
| 0x306c3    | 6         | 4.38%   |
| 0x306a9    | 6         | 4.38%   |
| 0x506e3    | 4         | 2.92%   |
| 0x1067a    | 4         | 2.92%   |
| 0x08600106 | 3         | 2.19%   |
| 0x08108109 | 3         | 2.19%   |
| 0x0800820d | 3         | 2.19%   |
| 0xf64      | 2         | 1.46%   |
| 0x906a3    | 2         | 1.46%   |
| 0x806ea    | 2         | 1.46%   |
| 0x806d1    | 2         | 1.46%   |
| 0x706a8    | 2         | 1.46%   |
| 0x6fd      | 2         | 1.46%   |
| 0x05000119 | 2         | 1.46%   |
| 0xa0671    | 1         | 0.73%   |
| 0xa0660    | 1         | 0.73%   |
| 0x906ed    | 1         | 0.73%   |
| 0x906c0    | 1         | 0.73%   |
| 0x806ec    | 1         | 0.73%   |
| 0x706e5    | 1         | 0.73%   |
| 0x6fb      | 1         | 0.73%   |
| 0x406e3    | 1         | 0.73%   |
| 0x406c4    | 1         | 0.73%   |
| 0x306f2    | 1         | 0.73%   |
| 0x306e4    | 1         | 0.73%   |
| 0x306d4    | 1         | 0.73%   |
| 0x30678    | 1         | 0.73%   |
| 0x20655    | 1         | 0.73%   |
| 0x20652    | 1         | 0.73%   |
| 0x0a601201 | 1         | 0.73%   |
| 0x0a50000d | 1         | 0.73%   |
| 0x0a404102 | 1         | 0.73%   |
| 0x0a404101 | 1         | 0.73%   |
| 0x0a20120a | 1         | 0.73%   |
| 0x0a201025 | 1         | 0.73%   |
| 0x08701021 | 1         | 0.73%   |
| 0x08600109 | 1         | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 19        | 13.87%  |
| KabyLake         | 19        | 13.87%  |
| Haswell          | 11        | 8.03%   |
| IvyBridge        | 10        | 7.3%    |
| Zen 2            | 8         | 5.84%   |
| Zen+             | 6         | 4.38%   |
| Skylake          | 6         | 4.38%   |
| Penryn           | 6         | 4.38%   |
| Goldmont plus    | 6         | 4.38%   |
| Alderlake Hybrid | 6         | 4.38%   |
| Unknown          | 5         | 3.65%   |
| Zen 3            | 4         | 2.92%   |
| Silvermont       | 4         | 2.92%   |
| IceLake          | 4         | 2.92%   |
| Core             | 4         | 2.92%   |
| Westmere         | 3         | 2.19%   |
| Zen              | 2         | 1.46%   |
| NetBurst         | 2         | 1.46%   |
| CometLake        | 2         | 1.46%   |
| Bobcat           | 2         | 1.46%   |
| Tremont          | 1         | 0.73%   |
| TigerLake        | 1         | 0.73%   |
| Piledriver       | 1         | 0.73%   |
| Nehalem          | 1         | 0.73%   |
| K8 Hammer        | 1         | 0.73%   |
| K10              | 1         | 0.73%   |
| Excavator        | 1         | 0.73%   |
| Broadwell        | 1         | 0.73%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 84        | 52.5%   |
| AMD    | 39        | 24.38%  |
| Nvidia | 37        | 23.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 8.54%   |
| Intel HD Graphics 620                                                                    | 10        | 6.1%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 4.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 3.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 3.05%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.83%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.83%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.22%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.22%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.22%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 1.22%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.22%   |
| Intel HD Graphics 630                                                                    | 2         | 1.22%   |
| Intel HD Graphics 530                                                                    | 2         | 1.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.22%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.22%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 1.22%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 2         | 1.22%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                                     | 2         | 1.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.61%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.61%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.61%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.61%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 0.61%   |
| Nvidia TU106 [GeForce GTX 1650]                                                          | 1         | 0.61%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.61%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 1         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.61%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.61%   |
| Nvidia GM206GL [Quadro M2000]                                                            | 1         | 0.61%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.61%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.61%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 41.3%   |
| 1 x AMD        | 33        | 23.91%  |
| 1 x Nvidia     | 20        | 14.49%  |
| Intel + Nvidia | 16        | 11.59%  |
| Intel + AMD    | 4         | 2.9%    |
| 2 x Intel      | 3         | 2.17%   |
| Other          | 2         | 1.45%   |
| 2 x AMD        | 2         | 1.45%   |
| AMD + Nvidia   | 1         | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 107       | 78.1%   |
| Proprietary | 27        | 19.71%  |
| Unknown     | 3         | 2.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 56.93%  |
| 1.01-2.0   | 22        | 16.06%  |
| 0.01-0.5   | 12        | 8.76%   |
| 7.01-8.0   | 8         | 5.84%   |
| 3.01-4.0   | 7         | 5.11%   |
| 0.51-1.0   | 6         | 4.38%   |
| 5.01-6.0   | 2         | 1.46%   |
| 2.01-3.0   | 1         | 0.73%   |
| 8.01-16.0  | 1         | 0.73%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 27        | 18.75%  |
| AU Optronics            | 20        | 13.89%  |
| Chimei Innolux          | 14        | 9.72%   |
| BOE                     | 14        | 9.72%   |
| LG Display              | 12        | 8.33%   |
| Goldstar                | 10        | 6.94%   |
| AOC                     | 7         | 4.86%   |
| Dell                    | 5         | 3.47%   |
| Philips                 | 3         | 2.08%   |
| Apple                   | 3         | 2.08%   |
| Unknown (XXX)           | 2         | 1.39%   |
| Sony                    | 2         | 1.39%   |
| Positivo                | 2         | 1.39%   |
| Panasonic               | 2         | 1.39%   |
| Hewlett-Packard         | 2         | 1.39%   |
| GDH                     | 2         | 1.39%   |
| Chi Mei Optoelectronics | 2         | 1.39%   |
| VIZ                     | 1         | 0.69%   |
| Unknown                 | 1         | 0.69%   |
| Philco                  | 1         | 0.69%   |
| NEC Computers           | 1         | 0.69%   |
| MTD                     | 1         | 0.69%   |
| LRX                     | 1         | 0.69%   |
| LG Electronics          | 1         | 0.69%   |
| Lenovo                  | 1         | 0.69%   |
| ITE                     | 1         | 0.69%   |
| Iiyama                  | 1         | 0.69%   |
| Denver                  | 1         | 0.69%   |
| CSO                     | 1         | 0.69%   |
| BenQ                    | 1         | 0.69%   |
| ASUSTek Computer        | 1         | 0.69%   |
| Unknown                 | 1         | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 2.01%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch           | 3         | 2.01%   |
| Samsung Electronics SyncMaster SAM037A 1680x1050 433x271mm 20.1-inch    | 2         | 1.34%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 477x268mm 21.5-inch     | 2         | 1.34%   |
| Panasonic TV MEIC10C 1920x540 697x392mm 31.5-inch                       | 2         | 1.34%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 2         | 1.34%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2         | 1.34%   |
| GDH TV PHILCO GDH0030 3840x2160 708x398mm 32.0-inch                     | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 1.34%   |
| BOE LCD Monitor BOE0913 1366x768 309x174mm 14.0-inch                    | 2         | 1.34%   |
| AU Optronics LCD Monitor AUOE495 2560x1600 344x215mm 16.0-inch          | 2         | 1.34%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                        | 2         | 1.34%   |
| VIZ LCD Monitor M190VA 1360x768                                         | 1         | 0.67%   |
| Unknown LCD Monitor XXX Beyond TV                                       | 1         | 0.67%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 0.67%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1         | 0.67%   |
| Sony TV SNY7E02 1920x1080                                               | 1         | 0.67%   |
| Sony TV SNY1A02 1920x1080                                               | 1         | 0.67%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch       | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch     | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 340x190mm 15.3-inch     | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0322 1440x900 428x255mm 19.6-inch     | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch     | 1         | 0.67%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch    | 1         | 0.67%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch       | 1         | 0.67%   |
| Samsung Electronics S19B300 SAM08A5 1366x768 410x230mm 18.5-inch        | 1         | 0.67%   |
| Samsung Electronics LS32A70 SAM7166 3840x2160 698x393mm 31.5-inch       | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch    | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4182 2880x1800 289x186mm 13.5-inch   | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4167 2880x1800 289x186mm 13.5-inch   | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM0E33 1920x1080 1210x680mm 54.6-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 886x498mm 40.0-inch   | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 410x230mm 18.5-inch   | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM04DB 1280x1024 886x498mm 40.0-inch   | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM02C9 1360x768 885x498mm 40.0-inch    | 1         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 50        | 34.72%  |
| 1366x768 (WXGA)    | 37        | 25.69%  |
| 3840x2160 (4K)     | 9         | 6.25%   |
| 1360x768           | 7         | 4.86%   |
| 2560x1080          | 6         | 4.17%   |
| 1600x900 (HD+)     | 5         | 3.47%   |
| 1440x900 (WXGA+)   | 4         | 2.78%   |
| 1280x800 (WXGA)    | 4         | 2.78%   |
| 2880x1800          | 3         | 2.08%   |
| 1920x540           | 3         | 2.08%   |
| 1280x1024 (SXGA)   | 3         | 2.08%   |
| 2560x1600          | 2         | 1.39%   |
| 2560x1440 (QHD)    | 2         | 1.39%   |
| 1680x1050 (WSXGA+) | 2         | 1.39%   |
| Unknown            | 2         | 1.39%   |
| 4240x1280          | 1         | 0.69%   |
| 3200x1080          | 1         | 0.69%   |
| 2736x1824          | 1         | 0.69%   |
| 1920x1200 (WUXGA)  | 1         | 0.69%   |
| 1280x960           | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 24.31%  |
| 13      | 15        | 10.42%  |
| 14      | 14        | 9.72%   |
| 17      | 10        | 6.94%   |
| 23      | 9         | 6.25%   |
| 18      | 8         | 5.56%   |
| Unknown | 6         | 4.17%   |
| 27      | 5         | 3.47%   |
| 31      | 4         | 2.78%   |
| 24      | 4         | 2.78%   |
| 21      | 4         | 2.78%   |
| 19      | 4         | 2.78%   |
| 54      | 3         | 2.08%   |
| 40      | 3         | 2.08%   |
| 34      | 3         | 2.08%   |
| 20      | 3         | 2.08%   |
| 16      | 3         | 2.08%   |
| 72      | 2         | 1.39%   |
| 52      | 2         | 1.39%   |
| 84      | 1         | 0.69%   |
| 48      | 1         | 0.69%   |
| 32      | 1         | 0.69%   |
| 29      | 1         | 0.69%   |
| 28      | 1         | 0.69%   |
| 25      | 1         | 0.69%   |
| 12      | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 62        | 43.66%  |
| 401-500     | 18        | 12.68%  |
| 501-600     | 17        | 11.97%  |
| 351-400     | 10        | 7.04%   |
| 601-700     | 7         | 4.93%   |
| 201-300     | 6         | 4.23%   |
| 1001-1500   | 6         | 4.23%   |
| Unknown     | 6         | 4.23%   |
| 701-800     | 4         | 2.82%   |
| 801-900     | 3         | 2.11%   |
| 1501-2000   | 3         | 2.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 99        | 75.57%  |
| 16/10   | 16        | 12.21%  |
| 21/9    | 6         | 4.58%   |
| Unknown | 5         | 3.82%   |
| 5/4     | 3         | 2.29%   |
| 4/3     | 1         | 0.76%   |
| 3/2     | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 24.48%  |
| 81-90          | 27        | 18.88%  |
| 201-250        | 14        | 9.79%   |
| More than 1000 | 9         | 6.29%   |
| 141-150        | 9         | 6.29%   |
| 351-500        | 8         | 5.59%   |
| 151-200        | 8         | 5.59%   |
| 121-130        | 7         | 4.9%    |
| 301-350        | 6         | 4.2%    |
| Unknown        | 6         | 4.2%    |
| 251-300        | 4         | 2.8%    |
| 71-80          | 3         | 2.1%    |
| 501-1000       | 3         | 2.1%    |
| 131-140        | 2         | 1.4%    |
| 111-120        | 2         | 1.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 45        | 32.61%  |
| 101-120       | 42        | 30.43%  |
| 121-160       | 28        | 20.29%  |
| 1-50          | 10        | 7.25%   |
| Unknown       | 6         | 4.35%   |
| 161-240       | 4         | 2.9%    |
| More than 240 | 3         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 108       | 78.26%  |
| 2     | 25        | 18.12%  |
| 0     | 4         | 2.9%    |
| 3     | 1         | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 95        | 45.89%  |
| Intel                    | 45        | 21.74%  |
| Qualcomm Atheros         | 28        | 13.53%  |
| Broadcom                 | 8         | 3.86%   |
| MediaTek                 | 5         | 2.42%   |
| Ralink Technology        | 4         | 1.93%   |
| TP-Link                  | 3         | 1.45%   |
| Marvell Technology Group | 3         | 1.45%   |
| VIA Technologies         | 2         | 0.97%   |
| Samsung Electronics      | 2         | 0.97%   |
| D-Link System            | 2         | 0.97%   |
| Ralink                   | 1         | 0.48%   |
| Prolific Technology      | 1         | 0.48%   |
| Nvidia                   | 1         | 0.48%   |
| Lenovo                   | 1         | 0.48%   |
| JMicron Technology       | 1         | 0.48%   |
| Edimax Technology        | 1         | 0.48%   |
| D-Link                   | 1         | 0.48%   |
| Belkin Components        | 1         | 0.48%   |
| ASUSTek Computer         | 1         | 0.48%   |
| ASIX Electronics         | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 54        | 22.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 6.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 3.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 2.87%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 2.46%   |
| Realtek 802.11ac NIC                                                   | 6         | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 4         | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 1.64%   |
| Intel Wi-Fi 6 AX200                                                    | 4         | 1.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 3         | 1.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 1.23%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.23%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 1.23%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2         | 0.82%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 2         | 0.82%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 2         | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2         | 0.82%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.82%   |
| Ralink RT5370 Wireless Adapter                                         | 2         | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.82%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                      | 2         | 0.82%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 0.82%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 0.82%   |
| TP-Link Archer T4U ver.3                                               | 1         | 0.41%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1         | 0.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1         | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.41%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1         | 0.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1         | 0.41%   |
| Realtek RTL8192SE Wireless LAN Controller                              | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 35        | 31.25%  |
| Realtek Semiconductor    | 30        | 26.79%  |
| Qualcomm Atheros         | 21        | 18.75%  |
| Broadcom                 | 7         | 6.25%   |
| MediaTek                 | 5         | 4.46%   |
| Ralink Technology        | 4         | 3.57%   |
| TP-Link                  | 3         | 2.68%   |
| Marvell Technology Group | 2         | 1.79%   |
| Ralink                   | 1         | 0.89%   |
| Edimax Technology        | 1         | 0.89%   |
| D-Link                   | 1         | 0.89%   |
| Belkin Components        | 1         | 0.89%   |
| ASUSTek Computer         | 1         | 0.89%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 8         | 7.08%   |
| Realtek 802.11ac NIC                                                                  | 6         | 5.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 5         | 4.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 4         | 3.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 4         | 3.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 4         | 3.54%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 3.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 4         | 3.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 3         | 2.65%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 3         | 2.65%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 2.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 3         | 2.65%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                            | 2         | 1.77%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2         | 1.77%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 1.77%   |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.77%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                     | 2         | 1.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 1.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 1.77%   |
| TP-Link Archer T4U ver.3                                                              | 1         | 0.88%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                   | 1         | 0.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 1         | 0.88%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                   | 1         | 0.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.88%   |
| Realtek RTL8192SE Wireless LAN Controller                                             | 1         | 0.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                       | 1         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.88%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 0.88%   |
| Realtek 802.11n WLAN Adapter                                                          | 1         | 0.88%   |
| Ralink RT3072 Wireless Adapter                                                        | 1         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.88%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.88%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1         | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 0.88%   |
| Intel Wireless 8260                                                                   | 1         | 0.88%   |
| Intel Wireless 7265                                                                   | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 81        | 65.85%  |
| Intel                    | 22        | 17.89%  |
| Qualcomm Atheros         | 8         | 6.5%    |
| VIA Technologies         | 2         | 1.63%   |
| Samsung Electronics      | 2         | 1.63%   |
| D-Link System            | 2         | 1.63%   |
| Broadcom                 | 2         | 1.63%   |
| Nvidia                   | 1         | 0.81%   |
| Marvell Technology Group | 1         | 0.81%   |
| JMicron Technology       | 1         | 0.81%   |
| ASIX Electronics         | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 54        | 41.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 13.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 5.43%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 4.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 3.1%    |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 2.33%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2         | 1.55%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 1.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 1.55%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.55%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2         | 1.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.78%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 0.78%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.78%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.78%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.78%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.78%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.78%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.78%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.78%   |
| Intel Ethernet Controller I225-LM                                      | 1         | 0.78%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.78%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 0.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1         | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 117       | 52.23%  |
| WiFi     | 105       | 46.88%  |
| Modem    | 2         | 0.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 56.83%  |
| Ethernet | 60        | 43.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 69        | 50.36%  |
| 1     | 62        | 45.26%  |
| 0     | 3         | 2.19%   |
| 3     | 2         | 1.46%   |
| 5     | 1         | 0.73%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 80        | 58.39%  |
| Yes  | 57        | 41.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 34.83%  |
| Cambridge Silicon Radio         | 13        | 14.61%  |
| Qualcomm Atheros Communications | 8         | 8.99%   |
| Realtek Semiconductor           | 7         | 7.87%   |
| IMC Networks                    | 7         | 7.87%   |
| Lite-On Technology              | 6         | 6.74%   |
| Foxconn / Hon Hai               | 3         | 3.37%   |
| MediaTek                        | 2         | 2.25%   |
| Marvell Semiconductor           | 2         | 2.25%   |
| Broadcom                        | 2         | 2.25%   |
| Apple                           | 2         | 2.25%   |
| TP-Link                         | 1         | 1.12%   |
| Hewlett-Packard                 | 1         | 1.12%   |
| Dell                            | 1         | 1.12%   |
| ASUSTek Computer                | 1         | 1.12%   |
| Actions                         | 1         | 1.12%   |
| AboCom Systems                  | 1         | 1.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 14.61%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 6.74%   |
| Realtek Bluetooth Radio                             | 5         | 5.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 4.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 4.49%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 4.49%   |
| Intel Bluetooth Device                              | 4         | 4.49%   |
| Intel AX201 Bluetooth                               | 4         | 4.49%   |
| Intel AX200 Bluetooth                               | 4         | 4.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 3.37%   |
| IMC Networks Bluetooth Radio                        | 3         | 3.37%   |
| MediaTek Wireless_Device                            | 2         | 2.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.25%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 2.25%   |
| Intel Bluetooth wireless interface                  | 2         | 2.25%   |
| IMC Networks Bluetooth Device                       | 2         | 2.25%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 2.25%   |
| TP-Link UB500 Adapter                               | 1         | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.12%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.12%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.12%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.12%   |
| Lite-On Bluetooth Device                            | 1         | 1.12%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.12%   |
| Intel AX211 Bluetooth                               | 1         | 1.12%   |
| Intel AX210 Bluetooth                               | 1         | 1.12%   |
| IMC Networks Wireless_Device                        | 1         | 1.12%   |
| IMC Networks BCM20702A0                             | 1         | 1.12%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.12%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.12%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.12%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.12%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.12%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 1.12%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.12%   |
| Apple Bluetooth Host Controller                     | 1         | 1.12%   |
| Actions general adapter                             | 1         | 1.12%   |
| AboCom Systems AboCom Bluetooth Device              | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 102       | 54.26%  |
| AMD                    | 41        | 21.81%  |
| Nvidia                 | 31        | 16.49%  |
| C-Media Electronics    | 4         | 2.13%   |
| Generalplus Technology | 2         | 1.06%   |
| Creative Labs          | 2         | 1.06%   |
| VIA Technologies       | 1         | 0.53%   |
| Roland                 | 1         | 0.53%   |
| Realtek Semiconductor  | 1         | 0.53%   |
| Razer USA              | 1         | 0.53%   |
| JMTek                  | 1         | 0.53%   |
| DCMT Technology        | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 7.66%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 7.66%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 6.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 4.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 2.25%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 2.25%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 1.8%    |
| Nvidia Audio device                                                                               | 4         | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.8%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 4         | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.8%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1.35%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 3         | 1.35%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.9%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.9%    |
| Intel 8 Series HD Audio Controller                                                                | 2         | 0.9%    |
| Generalplus Technology USB Audio Device                                                           | 2         | 0.9%    |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 2         | 0.9%    |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 2         | 0.9%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.9%    |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 2         | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.9%    |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 0.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 17.17%  |
| Kingston            | 14        | 14.14%  |
| Unknown             | 13        | 13.13%  |
| Micron Technology   | 9         | 9.09%   |
| Smart               | 7         | 7.07%   |
| SK hynix            | 7         | 7.07%   |
| Corsair             | 6         | 6.06%   |
| Unknown             | 5         | 5.05%   |
| Crucial             | 3         | 3.03%   |
| Teikon              | 2         | 2.02%   |
| Ramaxel Technology  | 2         | 2.02%   |
| Kllisre             | 2         | 2.02%   |
| G.Skill             | 2         | 2.02%   |
| A-DATA Technology   | 2         | 2.02%   |
| Walton Chaintech    | 1         | 1.01%   |
| Unknown (B98C)      | 1         | 1.01%   |
| Unknown (8A6B)      | 1         | 1.01%   |
| Timetec             | 1         | 1.01%   |
| Smart Brazil        | 1         | 1.01%   |
| PLEXHD              | 1         | 1.01%   |
| Nanya Technology    | 1         | 1.01%   |
| Kembona             | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 4.72%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 2         | 1.89%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 1.89%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 2         | 1.89%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.89%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 1.89%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 1.89%   |
| Micron RAM MICRON/MT60B1G16HC-4 8GB SODIMM DDR5 4800MT/s         | 2         | 1.89%   |
| Kllisre RAM KRE-D3U1600M/8G 8GB DIMM DDR3 1600MT/s               | 2         | 1.89%   |
| Walton Chaintech RAM AS2G732-800P005 2GB SODIMM DDR2 800MT/s     | 1         | 0.94%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.94%   |
| Unknown RAM Module 8GB DIMM SDRAM                                | 1         | 0.94%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.94%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR2 266MT/s                         | 1         | 0.94%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.94%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.94%   |
| Unknown RAM Module 16GB DIMM DDR4 3200MT/s                       | 1         | 0.94%   |
| Unknown (B98C) RAM Module 8GB DIMM DDR4 2667MT/s                 | 1         | 0.94%   |
| Unknown (8A6B) RAM BL.9BWWA.221 8GB DIMM DDR4 2667MT/s           | 1         | 0.94%   |
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.94%   |
| Teikon RAM TMT351S6EFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 1         | 0.94%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 1         | 0.94%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 1         | 0.94%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s            | 1         | 0.94%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 1         | 0.94%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.94%   |
| Smart RAM SF4641G8CKHIWDFSEG 8GB SODIMM DDR4 2133MT/s            | 1         | 0.94%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 1         | 0.94%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s           | 1         | 0.94%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 0.94%   |
| SK hynix RAM MMXIV 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.94%   |
| SK hynix RAM MD4512NSE-CB3M2 00 4096MB DIMM DDR4 2400MT/s        | 1         | 0.94%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.94%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.94%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 1         | 0.94%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.94%   |
| Samsung RAM Module 4GB SODIMM LPDDR3 2133MT/s                    | 1         | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 32        | 38.55%  |
| DDR4    | 30        | 36.14%  |
| DDR5    | 7         | 8.43%   |
| SDRAM   | 5         | 6.02%   |
| LPDDR3  | 3         | 3.61%   |
| DDR2    | 3         | 3.61%   |
| LPDDR5  | 1         | 1.2%    |
| LPDDR4  | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 51.81%  |
| DIMM         | 35        | 42.17%  |
| Row Of Chips | 5         | 6.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 33        | 35.11%  |
| 4096  | 27        | 28.72%  |
| 16384 | 14        | 14.89%  |
| 2048  | 14        | 14.89%  |
| 32768 | 3         | 3.19%   |
| 1024  | 2         | 2.13%   |
| 512   | 1         | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 22        | 23.66%  |
| 1333    | 10        | 10.75%  |
| 2667    | 9         | 9.68%   |
| 2400    | 8         | 8.6%    |
| 4800    | 7         | 7.53%   |
| 3200    | 6         | 6.45%   |
| 2133    | 6         | 6.45%   |
| Unknown | 5         | 5.38%   |
| 1334    | 4         | 4.3%    |
| 1867    | 2         | 2.15%   |
| 1067    | 2         | 2.15%   |
| 6400    | 1         | 1.08%   |
| 4266    | 1         | 1.08%   |
| 4000    | 1         | 1.08%   |
| 3866    | 1         | 1.08%   |
| 3800    | 1         | 1.08%   |
| 3733    | 1         | 1.08%   |
| 2666    | 1         | 1.08%   |
| 2200    | 1         | 1.08%   |
| 1066    | 1         | 1.08%   |
| 975     | 1         | 1.08%   |
| 800     | 1         | 1.08%   |
| 266     | 1         | 1.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Seiko Epson        | 1         | 20%     |
| Canon              | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| Seiko Epson L382 Series     | 1         | 20%     |
| HP Officejet 4620 series    | 1         | 20%     |
| HP Deskjet 3050 J610 series | 1         | 20%     |
| Canon E410 series           | 1         | 20%     |
| Brother DCP-T500W           | 1         | 20%     |

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
| Chicony Electronics                    | 9         | 12.5%   |
| Quanta                                 | 8         | 11.11%  |
| Sunplus Innovation Technology          | 7         | 9.72%   |
| Bison Electronics                      | 6         | 8.33%   |
| IMC Networks                           | 5         | 6.94%   |
| Realtek Semiconductor                  | 4         | 5.56%   |
| Microdia                               | 4         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.17%   |
| Alcor Micro                            | 3         | 4.17%   |
| SunplusIT                              | 2         | 2.78%   |
| Luxvisions Innotech Limited            | 2         | 2.78%   |
| Lenovo                                 | 2         | 2.78%   |
| Apple                                  | 2         | 2.78%   |
| Acer                                   | 2         | 2.78%   |
| Y Media                                | 1         | 1.39%   |
| USB Camera CS                          | 1         | 1.39%   |
| Syntek                                 | 1         | 1.39%   |
| Sonix Technology                       | 1         | 1.39%   |
| Silicon Motion                         | 1         | 1.39%   |
| Shine-optics                           | 1         | 1.39%   |
| Samsung Electronics                    | 1         | 1.39%   |
| Microsoft                              | 1         | 1.39%   |
| Lite-On Technology                     | 1         | 1.39%   |
| Jieli Technology                       | 1         | 1.39%   |
| Generalplus Technology                 | 1         | 1.39%   |
| GEMBIRD                                | 1         | 1.39%   |
| ALi                                    | 1         | 1.39%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Quanta VGA WebCam                                    | 3         | 4.17%   |
| Chicony Integrated Camera                            | 3         | 4.17%   |
| SunplusIT MTD camera                                 | 2         | 2.78%   |
| Sunplus PC Camera                                    | 2         | 2.78%   |
| Quanta HD Webcam                                     | 2         | 2.78%   |
| Microdia Integrated_Webcam_HD                        | 2         | 2.78%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 2.78%   |
| Chicony HD WebCam                                    | 2         | 2.78%   |
| Bison HD Webcam                                      | 2         | 2.78%   |
| Bison EasyCamera                                     | 2         | 2.78%   |
| Acer Lenovo EasyCamera                               | 2         | 2.78%   |
| Y Media USB Camera                                   | 1         | 1.39%   |
| USB Camera CS USB Camera CS                          | 1         | 1.39%   |
| Syntek Integrated Camera                             | 1         | 1.39%   |
| Sunplus Laptop_Integrated_Webcam_HD                  | 1         | 1.39%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.39%   |
| Sunplus Laptop Integrated Webcam FHD                 | 1         | 1.39%   |
| Sunplus HP TrueVision HD Camera                      | 1         | 1.39%   |
| Sunplus HP HD Webcam [Fixed]                         | 1         | 1.39%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 1.39%   |
| Silicon Motion Web Camera                            | 1         | 1.39%   |
| Shine-optics USB2.0 HD UVC WebCam                    | 1         | 1.39%   |
| Samsung Galaxy series, misc. (MTP mode)              | 1         | 1.39%   |
| Realtek USB Camera                                   | 1         | 1.39%   |
| Realtek HP Webcam                                    | 1         | 1.39%   |
| Realtek HP Truevision HD                             | 1         | 1.39%   |
| Realtek HD WebCam                                    | 1         | 1.39%   |
| Quanta Laptop_Integrated_Webcam_2HDM                 | 1         | 1.39%   |
| Quanta HD User Facing                                | 1         | 1.39%   |
| Quanta ACER HD User Facing                           | 1         | 1.39%   |
| Microsoft LifeCam VX-2000                            | 1         | 1.39%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam       | 1         | 1.39%   |
| Microdia Integrated Camera                           | 1         | 1.39%   |
| Lite-On TOSHIBA Web Camera - HD                      | 1         | 1.39%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.39%   |
| Lenovo FHD Webcam                                    | 1         | 1.39%   |
| Jieli USB PHY 2.0                                    | 1         | 1.39%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.39%   |
| IMC Networks SunplusIT Integrated Camera             | 1         | 1.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 4         | 50%     |
| Synaptics                          | 2         | 25%     |
| Realtek USB2.0 Finger Print Bridge | 2         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                 | 2         | 25%     |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 25%     |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 12.5%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 12.5%   |
| Synaptics  WBDI                                                 | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Giesecke & Devrient | 1         | 50%     |
| Broadcom            | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Giesecke & Devrient StarSign CUT               | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 108       | 78.83%  |
| 1     | 25        | 18.25%  |
| 2     | 3         | 2.19%   |
| 3     | 1         | 0.73%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 9         | 27.27%  |
| Fingerprint reader    | 8         | 24.24%  |
| Graphics card         | 7         | 21.21%  |
| Multimedia controller | 2         | 6.06%   |
| Chipcard              | 2         | 6.06%   |
| Unassigned class      | 1         | 3.03%   |
| Tv card               | 1         | 3.03%   |
| Storage               | 1         | 3.03%   |
| Network               | 1         | 3.03%   |
| Bluetooth             | 1         | 3.03%   |

