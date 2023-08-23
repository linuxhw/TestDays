Linux in Taiwan - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Taiwan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Taiwan/Desktop/README.md) and [notebooks](/Location/Taiwan/Notebook/README.md).

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

Total: 793

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | UX31LA                      | Notebook    | [0695e3bb09](https://linux-hardware.org/?probe=0695e3bb09) | Aug 08, 2023 |
| MSI           | GL65 9SD                    | Notebook    | [b3ef4f1363](https://linux-hardware.org/?probe=b3ef4f1363) | Aug 07, 2023 |
| MSI           | GL65 9SD                    | Notebook    | [2539f4ad7a](https://linux-hardware.org/?probe=2539f4ad7a) | Aug 06, 2023 |
| Gigabyte      | B550M K                     | Desktop     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| MSI           | PS63 Modern 8M              | Notebook    | [96e7b96787](https://linux-hardware.org/?probe=96e7b96787) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [04aeffbcf4](https://linux-hardware.org/?probe=04aeffbcf4) | Jul 26, 2023 |
| MSI           | GL65 9SD                    | Notebook    | [a3f9991e22](https://linux-hardware.org/?probe=a3f9991e22) | Jul 23, 2023 |
| Dell          | 00010C A00                  | Desktop     | [71eca6ee4c](https://linux-hardware.org/?probe=71eca6ee4c) | Jul 20, 2023 |
| Altos         | BrainSphere P10 F7          | Desktop     | [8608df7a38](https://linux-hardware.org/?probe=8608df7a38) | Jul 20, 2023 |
| AAEON         | GENE-CML5 V1.0              | Desktop     | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [62238aaf82](https://linux-hardware.org/?probe=62238aaf82) | Jul 17, 2023 |
| MSI           | GL65 9SD                    | Notebook    | [57c6b0a7dd](https://linux-hardware.org/?probe=57c6b0a7dd) | Jul 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP34... | Convertible | [be7dcafaba](https://linux-hardware.org/?probe=be7dcafaba) | Jul 14, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [bc805d82a7](https://linux-hardware.org/?probe=bc805d82a7) | Jul 13, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [36b6c49552](https://linux-hardware.org/?probe=36b6c49552) | Jul 09, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [ffa5984711](https://linux-hardware.org/?probe=ffa5984711) | Jul 09, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [030ecef01c](https://linux-hardware.org/?probe=030ecef01c) | Jul 08, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [56683a6866](https://linux-hardware.org/?probe=56683a6866) | Jul 08, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [e5d4d7b4a7](https://linux-hardware.org/?probe=e5d4d7b4a7) | Jul 06, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| Intel         | X99                         | Desktop     | [81dbd5c4f0](https://linux-hardware.org/?probe=81dbd5c4f0) | Jul 01, 2023 |
| Google        | Cave                        | Notebook    | [cc3b1bb1a3](https://linux-hardware.org/?probe=cc3b1bb1a3) | Jun 24, 2023 |
| Google        | Cave                        | Notebook    | [199eb4826d](https://linux-hardware.org/?probe=199eb4826d) | Jun 24, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [e72c8358c4](https://linux-hardware.org/?probe=e72c8358c4) | Jun 22, 2023 |
| Acer          | Aspire A515-53G             | Notebook    | [430cfefc6a](https://linux-hardware.org/?probe=430cfefc6a) | Jun 21, 2023 |
| ASRock        | X370 Killer SLI             | Desktop     | [10939cb152](https://linux-hardware.org/?probe=10939cb152) | Jun 20, 2023 |
| Lenovo        | ThinkPad X230 2324CD1       | Notebook    | [9ee6ed4144](https://linux-hardware.org/?probe=9ee6ed4144) | Jun 18, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | Notebook    | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | Notebook    | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [2734ce8c5d](https://linux-hardware.org/?probe=2734ce8c5d) | Jun 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | Notebook    | [dd5aaca858](https://linux-hardware.org/?probe=dd5aaca858) | Jun 15, 2023 |
| MSI           | B250M MORTAR ARCTIC         | Desktop     | [5e0e6586b7](https://linux-hardware.org/?probe=5e0e6586b7) | Jun 11, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | Notebook    | [ba129cd52d](https://linux-hardware.org/?probe=ba129cd52d) | Jun 11, 2023 |
| Acidanther... | MacBookPro15,2              | Notebook    | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [05a473a2be](https://linux-hardware.org/?probe=05a473a2be) | Jun 06, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [e92db65759](https://linux-hardware.org/?probe=e92db65759) | Jun 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [a3089228b1](https://linux-hardware.org/?probe=a3089228b1) | Jun 05, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [00ab711e0a](https://linux-hardware.org/?probe=00ab711e0a) | Jun 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fade8c50be](https://linux-hardware.org/?probe=fade8c50be) | May 30, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8bafef9e33](https://linux-hardware.org/?probe=8bafef9e33) | May 30, 2023 |
| Supermicro    | X13SAN-L                    | Server      | [e0b7939357](https://linux-hardware.org/?probe=e0b7939357) | May 30, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [47ac3b9c43](https://linux-hardware.org/?probe=47ac3b9c43) | May 28, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [dd79b67b18](https://linux-hardware.org/?probe=dd79b67b18) | May 27, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [936b06e11f](https://linux-hardware.org/?probe=936b06e11f) | May 25, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [324a8d5c88](https://linux-hardware.org/?probe=324a8d5c88) | May 22, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [88830e9fe8](https://linux-hardware.org/?probe=88830e9fe8) | May 22, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [2adc02040e](https://linux-hardware.org/?probe=2adc02040e) | May 21, 2023 |
| Win elemen... | M600                        | Desktop     | [4c5d685663](https://linux-hardware.org/?probe=4c5d685663) | May 21, 2023 |
| Win elemen... | M600                        | Desktop     | [84de4a3207](https://linux-hardware.org/?probe=84de4a3207) | May 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [fb58a4d348](https://linux-hardware.org/?probe=fb58a4d348) | May 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | Notebook    | [02fb267cbc](https://linux-hardware.org/?probe=02fb267cbc) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [e12a1d28ba](https://linux-hardware.org/?probe=e12a1d28ba) | May 06, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [867e98f955](https://linux-hardware.org/?probe=867e98f955) | May 05, 2023 |
| MSI           | H55M-P31                    | Desktop     | [386b720202](https://linux-hardware.org/?probe=386b720202) | May 04, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [71ff8cca4e](https://linux-hardware.org/?probe=71ff8cca4e) | May 03, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [4cb6025c16](https://linux-hardware.org/?probe=4cb6025c16) | May 03, 2023 |
| Acer          | Veriton M2630G V:1.0        | Desktop     | [7ffa9c83d7](https://linux-hardware.org/?probe=7ffa9c83d7) | May 03, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [e5051f5355](https://linux-hardware.org/?probe=e5051f5355) | May 02, 2023 |
| AMD           | Volcano                     | Server      | [b7e67f8130](https://linux-hardware.org/?probe=b7e67f8130) | Apr 27, 2023 |
| HP            | 83E2                        | Desktop     | [f10d975821](https://linux-hardware.org/?probe=f10d975821) | Apr 26, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [4a8d662bee](https://linux-hardware.org/?probe=4a8d662bee) | Apr 25, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7309ce024f](https://linux-hardware.org/?probe=7309ce024f) | Apr 25, 2023 |
| Gigabyte      | H81N                        | Desktop     | [5729c6c6a9](https://linux-hardware.org/?probe=5729c6c6a9) | Apr 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [b2a94c7310](https://linux-hardware.org/?probe=b2a94c7310) | Apr 18, 2023 |
| Acer          | Predator G3610              | Desktop     | [3d1841fa41](https://linux-hardware.org/?probe=3d1841fa41) | Apr 17, 2023 |
| Acer          | EG43LMK                     | Desktop     | [78b389b848](https://linux-hardware.org/?probe=78b389b848) | Apr 15, 2023 |
| Acer          | Predator G3610              | Desktop     | [d49e4d680c](https://linux-hardware.org/?probe=d49e4d680c) | Apr 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [965de2bcc4](https://linux-hardware.org/?probe=965de2bcc4) | Apr 11, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ad8009e647](https://linux-hardware.org/?probe=ad8009e647) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | Notebook    | [c0901def8d](https://linux-hardware.org/?probe=c0901def8d) | Apr 10, 2023 |
| Win elemen... | M600                        | Desktop     | [7723a03558](https://linux-hardware.org/?probe=7723a03558) | Apr 10, 2023 |
| Win elemen... | M600                        | Desktop     | [e20927ec15](https://linux-hardware.org/?probe=e20927ec15) | Apr 10, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [c8173d40cd](https://linux-hardware.org/?probe=c8173d40cd) | Apr 09, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [8f34b2347f](https://linux-hardware.org/?probe=8f34b2347f) | Apr 07, 2023 |
| Dell          | Latitude 7490               | Notebook    | [01957ea955](https://linux-hardware.org/?probe=01957ea955) | Apr 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f89b2c8b2a](https://linux-hardware.org/?probe=f89b2c8b2a) | Apr 05, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [2635da1e14](https://linux-hardware.org/?probe=2635da1e14) | Apr 03, 2023 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [0528b2df2b](https://linux-hardware.org/?probe=0528b2df2b) | Apr 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | Notebook    | [649b881439](https://linux-hardware.org/?probe=649b881439) | Mar 25, 2023 |
| ASRock        | N68-GS4/USB3 FX             | Desktop     | [b846b11174](https://linux-hardware.org/?probe=b846b11174) | Mar 25, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [9e658f67a2](https://linux-hardware.org/?probe=9e658f67a2) | Mar 25, 2023 |
| ASUSTek       | H110M-K D3                  | Desktop     | [24a568ad05](https://linux-hardware.org/?probe=24a568ad05) | Mar 25, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [de369a751a](https://linux-hardware.org/?probe=de369a751a) | Mar 25, 2023 |
| MSI           | H55M-P31                    | Desktop     | [07a5228600](https://linux-hardware.org/?probe=07a5228600) | Mar 25, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [b03324de35](https://linux-hardware.org/?probe=b03324de35) | Mar 24, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | Notebook    | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | Notebook    | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Gigabyte      | B75N                        | Desktop     | [8a16ffed3b](https://linux-hardware.org/?probe=8a16ffed3b) | Mar 21, 2023 |
| Intel         | N5095-AIO T1 E1.0G          | All in one  | [4af4017da0](https://linux-hardware.org/?probe=4af4017da0) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [7d1cd9aded](https://linux-hardware.org/?probe=7d1cd9aded) | Mar 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [882f82cf2c](https://linux-hardware.org/?probe=882f82cf2c) | Mar 20, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [6aee8060e9](https://linux-hardware.org/?probe=6aee8060e9) | Mar 17, 2023 |
| OEM           | B85 JHS359                  | Desktop     | [1d5d7e95fc](https://linux-hardware.org/?probe=1d5d7e95fc) | Mar 16, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dfd3b8546c](https://linux-hardware.org/?probe=dfd3b8546c) | Mar 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [db30abe51b](https://linux-hardware.org/?probe=db30abe51b) | Mar 13, 2023 |
| Toshiba       | Satellite C665              | Notebook    | [e95e34e3ba](https://linux-hardware.org/?probe=e95e34e3ba) | Mar 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [7f3075e65e](https://linux-hardware.org/?probe=7f3075e65e) | Mar 08, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [f5535f53dc](https://linux-hardware.org/?probe=f5535f53dc) | Mar 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | Notebook    | [2e864ba25e](https://linux-hardware.org/?probe=2e864ba25e) | Mar 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [367bc56a15](https://linux-hardware.org/?probe=367bc56a15) | Mar 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [c329f5f1c1](https://linux-hardware.org/?probe=c329f5f1c1) | Mar 05, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [fc1a09013d](https://linux-hardware.org/?probe=fc1a09013d) | Mar 05, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [ee356bc253](https://linux-hardware.org/?probe=ee356bc253) | Mar 02, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [061edbf583](https://linux-hardware.org/?probe=061edbf583) | Mar 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [2143a36dc5](https://linux-hardware.org/?probe=2143a36dc5) | Feb 28, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [97a1558878](https://linux-hardware.org/?probe=97a1558878) | Feb 25, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [dbccc5afa9](https://linux-hardware.org/?probe=dbccc5afa9) | Feb 23, 2023 |
| ASUSTek       | X202E                       | Notebook    | [6627e10e70](https://linux-hardware.org/?probe=6627e10e70) | Feb 19, 2023 |
| Dell          | Latitude E6320              | Notebook    | [467b45072e](https://linux-hardware.org/?probe=467b45072e) | Feb 19, 2023 |
| Lenovo        | ThinkPad X61 7673D13        | Notebook    | [b5399b39de](https://linux-hardware.org/?probe=b5399b39de) | Feb 19, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [b7e961dae3](https://linux-hardware.org/?probe=b7e961dae3) | Feb 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [e5f4ad1053](https://linux-hardware.org/?probe=e5f4ad1053) | Feb 12, 2023 |
| Maxtang       | EHL30 V1.0                  | Desktop     | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | Desktop     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [42e7c32817](https://linux-hardware.org/?probe=42e7c32817) | Feb 06, 2023 |
| HP            | Notebook                    | Notebook    | [41f5c97a09](https://linux-hardware.org/?probe=41f5c97a09) | Feb 06, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [7f895dc97f](https://linux-hardware.org/?probe=7f895dc97f) | Feb 04, 2023 |
| AVITA         | NE14A2                      | Notebook    | [c5d9f8e3ac](https://linux-hardware.org/?probe=c5d9f8e3ac) | Feb 02, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [9e9deedf0d](https://linux-hardware.org/?probe=9e9deedf0d) | Jan 31, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [37059de5b7](https://linux-hardware.org/?probe=37059de5b7) | Jan 27, 2023 |
| Gigabyte      | H81N                        | Desktop     | [e7cf6a4216](https://linux-hardware.org/?probe=e7cf6a4216) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d815a80782](https://linux-hardware.org/?probe=d815a80782) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d2c9a02f60](https://linux-hardware.org/?probe=d2c9a02f60) | Jan 24, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [335275777a](https://linux-hardware.org/?probe=335275777a) | Jan 23, 2023 |
| Dell          | Latitude 7490               | Notebook    | [e40bb2f01f](https://linux-hardware.org/?probe=e40bb2f01f) | Jan 23, 2023 |
| Dell          | Latitude 7490               | Notebook    | [31789ae630](https://linux-hardware.org/?probe=31789ae630) | Jan 23, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [24a0f33638](https://linux-hardware.org/?probe=24a0f33638) | Jan 22, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Acer          | Aspire XC-105               | Desktop     | [8192fe90a8](https://linux-hardware.org/?probe=8192fe90a8) | Jan 19, 2023 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [05df631dca](https://linux-hardware.org/?probe=05df631dca) | Jan 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [958ecc4388](https://linux-hardware.org/?probe=958ecc4388) | Jan 15, 2023 |
| Gigabyte      | GB-BKi3A-7100               | Notebook    | [8263d65b20](https://linux-hardware.org/?probe=8263d65b20) | Jan 08, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| System76      | Lemur Pro                   | Notebook    | [36156d9aa7](https://linux-hardware.org/?probe=36156d9aa7) | Jan 07, 2023 |
| Acer          | FMCP7A-ION-LE               | Desktop     | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| Dell          | Inspiron 13 5320            | Notebook    | [0007a36030](https://linux-hardware.org/?probe=0007a36030) | Jan 07, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [7ea6f8ee94](https://linux-hardware.org/?probe=7ea6f8ee94) | Jan 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [9e535c1e8e](https://linux-hardware.org/?probe=9e535c1e8e) | Jan 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [2abdc57712](https://linux-hardware.org/?probe=2abdc57712) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [632515014d](https://linux-hardware.org/?probe=632515014d) | Dec 31, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [34b6109940](https://linux-hardware.org/?probe=34b6109940) | Dec 29, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [1e7182cb70](https://linux-hardware.org/?probe=1e7182cb70) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [ee7b1d707c](https://linux-hardware.org/?probe=ee7b1d707c) | Dec 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [7c8560a87e](https://linux-hardware.org/?probe=7c8560a87e) | Dec 25, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [3256c282db](https://linux-hardware.org/?probe=3256c282db) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [9462031346](https://linux-hardware.org/?probe=9462031346) | Dec 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [7eb6658e3a](https://linux-hardware.org/?probe=7eb6658e3a) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [7a14c8194f](https://linux-hardware.org/?probe=7a14c8194f) | Dec 20, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [9b1f8e9a10](https://linux-hardware.org/?probe=9b1f8e9a10) | Dec 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a767e0fbf0](https://linux-hardware.org/?probe=a767e0fbf0) | Dec 16, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [9bfd668093](https://linux-hardware.org/?probe=9bfd668093) | Dec 16, 2022 |
| Lenovo        | ThinkPad W530 243858U       | Notebook    | [9dc4fb1abb](https://linux-hardware.org/?probe=9dc4fb1abb) | Dec 16, 2022 |
| Acer          | Aspire Z1801                | All in one  | [9d1453b919](https://linux-hardware.org/?probe=9d1453b919) | Dec 14, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [44484456f8](https://linux-hardware.org/?probe=44484456f8) | Dec 14, 2022 |
| ASUSTek       | CM1530                      | Desktop     | [3990cff263](https://linux-hardware.org/?probe=3990cff263) | Dec 06, 2022 |
| Dell          | 0NNFGG A00                  | Desktop     | [b955357ccc](https://linux-hardware.org/?probe=b955357ccc) | Dec 05, 2022 |
| ASUSTek       | PU403UA                     | Notebook    | [20007b4296](https://linux-hardware.org/?probe=20007b4296) | Dec 05, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [580b716020](https://linux-hardware.org/?probe=580b716020) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [52aaeb537b](https://linux-hardware.org/?probe=52aaeb537b) | Dec 03, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Dell          | 0XJ5V0 A03                  | Desktop     | [b954e4c174](https://linux-hardware.org/?probe=b954e4c174) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [55d95654c4](https://linux-hardware.org/?probe=55d95654c4) | Nov 30, 2022 |
| Supermicro    | X11SCA-FA                   | Server      | [5c1a9bfc40](https://linux-hardware.org/?probe=5c1a9bfc40) | Nov 24, 2022 |
| Supermicro    | X11SCA-FA                   | Server      | [89eb0756b2](https://linux-hardware.org/?probe=89eb0756b2) | Nov 24, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [aea7b4c016](https://linux-hardware.org/?probe=aea7b4c016) | Nov 23, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [8a773e7358](https://linux-hardware.org/?probe=8a773e7358) | Nov 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [678cfec38b](https://linux-hardware.org/?probe=678cfec38b) | Nov 20, 2022 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [abe3da973c](https://linux-hardware.org/?probe=abe3da973c) | Nov 19, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [3d2dd5419a](https://linux-hardware.org/?probe=3d2dd5419a) | Nov 18, 2022 |
| Intel         | Burnside                    | Desktop     | [5db283bd1f](https://linux-hardware.org/?probe=5db283bd1f) | Nov 17, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [8e55592803](https://linux-hardware.org/?probe=8e55592803) | Nov 15, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| MSI           | U270DX                      | Notebook    | [2a68a6ba02](https://linux-hardware.org/?probe=2a68a6ba02) | Nov 10, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [52080bf6ef](https://linux-hardware.org/?probe=52080bf6ef) | Nov 09, 2022 |
| HP            | EliteBook x360 1030 G4      | Notebook    | [4fa71c1d6d](https://linux-hardware.org/?probe=4fa71c1d6d) | Nov 09, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [ebdd62cbe3](https://linux-hardware.org/?probe=ebdd62cbe3) | Oct 28, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| HP            | 1589                        | Desktop     | [a6be3ee931](https://linux-hardware.org/?probe=a6be3ee931) | Oct 17, 2022 |
| Dell          | Inspiron 13 5320            | Notebook    | [9ac52708ad](https://linux-hardware.org/?probe=9ac52708ad) | Oct 17, 2022 |
| HP            | 1589                        | Desktop     | [c36aa260eb](https://linux-hardware.org/?probe=c36aa260eb) | Oct 17, 2022 |
| Intel Clie... | LAPRC710                    | Notebook    | [4a1e71b56a](https://linux-hardware.org/?probe=4a1e71b56a) | Oct 15, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e940ddf8a7](https://linux-hardware.org/?probe=e940ddf8a7) | Oct 12, 2022 |
| ASUSTek       | X99-A/USB                   | Desktop     | [11fc608e0a](https://linux-hardware.org/?probe=11fc608e0a) | Oct 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [5c45d7b1bf](https://linux-hardware.org/?probe=5c45d7b1bf) | Oct 09, 2022 |
| ASUSTek       | PU403UA                     | Notebook    | [8bf4879487](https://linux-hardware.org/?probe=8bf4879487) | Oct 04, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [0d7188c951](https://linux-hardware.org/?probe=0d7188c951) | Oct 03, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CBA    | Notebook    | [4cad2a770c](https://linux-hardware.org/?probe=4cad2a770c) | Sep 30, 2022 |
| Lenovo        | ThinkPad T480s 20L7001YU... | Notebook    | [929514123f](https://linux-hardware.org/?probe=929514123f) | Sep 30, 2022 |
| Gigabyte      | AORUS 5 SE                  | Notebook    | [c188e2c5b5](https://linux-hardware.org/?probe=c188e2c5b5) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [5503282548](https://linux-hardware.org/?probe=5503282548) | Sep 20, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [dbe024bea9](https://linux-hardware.org/?probe=dbe024bea9) | Sep 16, 2022 |
| AZW           | SER V01                     | Mini pc     | [169da4cd8a](https://linux-hardware.org/?probe=169da4cd8a) | Sep 14, 2022 |
| DNI           | SNDTP-1513N 5508015890      | Desktop     | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [c0b89ea222](https://linux-hardware.org/?probe=c0b89ea222) | Aug 26, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [96a87ada26](https://linux-hardware.org/?probe=96a87ada26) | Aug 26, 2022 |
| Sony          | SVS15115FWB                 | Notebook    | [6844bd3288](https://linux-hardware.org/?probe=6844bd3288) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [aaf726faa0](https://linux-hardware.org/?probe=aaf726faa0) | Aug 20, 2022 |
| Sony          | SVS15115FWB                 | Notebook    | [2fb1c4ab2d](https://linux-hardware.org/?probe=2fb1c4ab2d) | Aug 20, 2022 |
| Acer          | TravelMate P653-M           | Notebook    | [1e33abf031](https://linux-hardware.org/?probe=1e33abf031) | Aug 17, 2022 |
| Dell          | Inspiron 13 5320            | Notebook    | [cee0d5a717](https://linux-hardware.org/?probe=cee0d5a717) | Aug 14, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [8898e9247d](https://linux-hardware.org/?probe=8898e9247d) | Aug 11, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [f97852a196](https://linux-hardware.org/?probe=f97852a196) | Aug 08, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [2d41c9a29f](https://linux-hardware.org/?probe=2d41c9a29f) | Aug 08, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [ca880d8154](https://linux-hardware.org/?probe=ca880d8154) | Aug 06, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [21d06392bc](https://linux-hardware.org/?probe=21d06392bc) | Aug 06, 2022 |
| Dell          | Vostro 3525                 | Notebook    | [d6630abc3a](https://linux-hardware.org/?probe=d6630abc3a) | Aug 03, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [69188053f5](https://linux-hardware.org/?probe=69188053f5) | Aug 02, 2022 |
| ASUSTek       | K501LX                      | Notebook    | [8ea0c7daa9](https://linux-hardware.org/?probe=8ea0c7daa9) | Jul 30, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [a44d178033](https://linux-hardware.org/?probe=a44d178033) | Jul 30, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [6f083e1754](https://linux-hardware.org/?probe=6f083e1754) | Jul 27, 2022 |
| Gigabyte      | H310MSTX-HD3-CF             | Desktop     | [13e7ed20e1](https://linux-hardware.org/?probe=13e7ed20e1) | Jul 27, 2022 |
| LG Electro... | LE50-5BC6H1                 | Notebook    | [010123b7d5](https://linux-hardware.org/?probe=010123b7d5) | Jul 26, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| Acer          | Aspire K50-20               | Notebook    | [1f4543c39e](https://linux-hardware.org/?probe=1f4543c39e) | Jul 20, 2022 |
| Acer          | Aspire K50-20               | Notebook    | [3f0e68ecf5](https://linux-hardware.org/?probe=3f0e68ecf5) | Jul 20, 2022 |
| Acer          | TravelMate 8371             | Notebook    | [4af529e1c4](https://linux-hardware.org/?probe=4af529e1c4) | Jul 20, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [d88edfec1f](https://linux-hardware.org/?probe=d88edfec1f) | Jul 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4189e96860](https://linux-hardware.org/?probe=4189e96860) | Jul 19, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [f32b12f921](https://linux-hardware.org/?probe=f32b12f921) | Jul 19, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [54fda2d2bc](https://linux-hardware.org/?probe=54fda2d2bc) | Jul 16, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [43a9aeb04d](https://linux-hardware.org/?probe=43a9aeb04d) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [11fc460e29](https://linux-hardware.org/?probe=11fc460e29) | Jul 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [5f3670ea60](https://linux-hardware.org/?probe=5f3670ea60) | Jul 12, 2022 |
| MSI           | H81M-P33                    | Desktop     | [e523b324e6](https://linux-hardware.org/?probe=e523b324e6) | Jul 11, 2022 |
| Dell          | Vostro 3525                 | Notebook    | [2174c6314a](https://linux-hardware.org/?probe=2174c6314a) | Jul 11, 2022 |
| Dell          | Vostro 3525                 | Notebook    | [ff38c8714c](https://linux-hardware.org/?probe=ff38c8714c) | Jul 11, 2022 |
| Acer          | Swift SF514-54GT            | Notebook    | [554171275d](https://linux-hardware.org/?probe=554171275d) | Jul 07, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [32e2995911](https://linux-hardware.org/?probe=32e2995911) | Jun 30, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [e6d7a2a642](https://linux-hardware.org/?probe=e6d7a2a642) | Jun 30, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | Notebook    | [4e15b37546](https://linux-hardware.org/?probe=4e15b37546) | Jun 30, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [0a047126ba](https://linux-hardware.org/?probe=0a047126ba) | Jun 30, 2022 |
| MSI           | H81M-P33                    | Desktop     | [1a0e20ab20](https://linux-hardware.org/?probe=1a0e20ab20) | Jun 29, 2022 |
| MSI           | PE60 6QE                    | Notebook    | [4c7beba4e2](https://linux-hardware.org/?probe=4c7beba4e2) | Jun 29, 2022 |
| MSI           | H81M-P33                    | Desktop     | [e25d17a838](https://linux-hardware.org/?probe=e25d17a838) | Jun 25, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [43a27bb2dd](https://linux-hardware.org/?probe=43a27bb2dd) | Jun 23, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [39cc29c976](https://linux-hardware.org/?probe=39cc29c976) | Jun 23, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [f993d31672](https://linux-hardware.org/?probe=f993d31672) | Jun 22, 2022 |
| Dell          | Inspiron 14 5425            | Notebook    | [16e98704b5](https://linux-hardware.org/?probe=16e98704b5) | Jun 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d610c245f8](https://linux-hardware.org/?probe=d610c245f8) | Jun 22, 2022 |
| Acer          | Aspire R7-371T              | Notebook    | [b791797ef3](https://linux-hardware.org/?probe=b791797ef3) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | Notebook    | [d573a80e21](https://linux-hardware.org/?probe=d573a80e21) | Jun 12, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [73c4749082](https://linux-hardware.org/?probe=73c4749082) | Jun 10, 2022 |
| Sony          | SVS15115FWB                 | Notebook    | [da41314683](https://linux-hardware.org/?probe=da41314683) | Jun 09, 2022 |
| Sony          | SVS15115FWB                 | Notebook    | [ab97043dbe](https://linux-hardware.org/?probe=ab97043dbe) | Jun 09, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | Notebook    | [04e81b8b3f](https://linux-hardware.org/?probe=04e81b8b3f) | Jun 04, 2022 |
| Gigabyte      | B460 AORUS PRO AC           | Desktop     | [2966cd34b8](https://linux-hardware.org/?probe=2966cd34b8) | May 31, 2022 |
| Dell EMC      | Edge Gateway 3200           | Mini pc     | [15d4b0e11d](https://linux-hardware.org/?probe=15d4b0e11d) | May 27, 2022 |
| Dell          | Latitude 5420               | Notebook    | [fedd7d10fb](https://linux-hardware.org/?probe=fedd7d10fb) | May 25, 2022 |
| MSI           | B150M BAZOOKA               | Desktop     | [b8ec3bee43](https://linux-hardware.org/?probe=b8ec3bee43) | May 22, 2022 |
| Lex           | 3I610DW                     | Notebook    | [145688ea36](https://linux-hardware.org/?probe=145688ea36) | May 17, 2022 |
| Lex           | 3I610DW                     | Notebook    | [8baf27bb6a](https://linux-hardware.org/?probe=8baf27bb6a) | May 17, 2022 |
| Lex           | 3I610DW                     | Notebook    | [6c61eabd7c](https://linux-hardware.org/?probe=6c61eabd7c) | May 17, 2022 |
| Lex           | 3I610DW                     | Notebook    | [8a75530d17](https://linux-hardware.org/?probe=8a75530d17) | May 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2c8abb0fed](https://linux-hardware.org/?probe=2c8abb0fed) | May 12, 2022 |
| Ruckus Wir... | SCG-100                     | Desktop     | [781560aa15](https://linux-hardware.org/?probe=781560aa15) | May 09, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE-10G... | Desktop     | [4ebf4d9cc8](https://linux-hardware.org/?probe=4ebf4d9cc8) | May 09, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [0c04c6cb24](https://linux-hardware.org/?probe=0c04c6cb24) | May 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [1863683cb7](https://linux-hardware.org/?probe=1863683cb7) | May 06, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [1c94d4293a](https://linux-hardware.org/?probe=1c94d4293a) | May 02, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [b61c12247c](https://linux-hardware.org/?probe=b61c12247c) | May 02, 2022 |
| HP            | 15                          | Notebook    | [5d7a22faa6](https://linux-hardware.org/?probe=5d7a22faa6) | Apr 28, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [288bb26592](https://linux-hardware.org/?probe=288bb26592) | Apr 27, 2022 |
| Acer          | Aspire 1410                 | Notebook    | [0399a90ade](https://linux-hardware.org/?probe=0399a90ade) | Apr 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6af9cfacd0](https://linux-hardware.org/?probe=6af9cfacd0) | Apr 23, 2022 |
| Dell          | Precision 3260              | Desktop     | [70a8481a89](https://linux-hardware.org/?probe=70a8481a89) | Apr 19, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9d2aeecf05](https://linux-hardware.org/?probe=9d2aeecf05) | Apr 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [a084a48023](https://linux-hardware.org/?probe=a084a48023) | Apr 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [1a35138280](https://linux-hardware.org/?probe=1a35138280) | Apr 14, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [b6834625e2](https://linux-hardware.org/?probe=b6834625e2) | Apr 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [dccdc2c9f5](https://linux-hardware.org/?probe=dccdc2c9f5) | Apr 12, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [f8c3b429a2](https://linux-hardware.org/?probe=f8c3b429a2) | Apr 09, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | Notebook    | [369aac0795](https://linux-hardware.org/?probe=369aac0795) | Apr 09, 2022 |
| Acer          | Aspire 1410                 | Notebook    | [41ed1dae3d](https://linux-hardware.org/?probe=41ed1dae3d) | Apr 08, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [79aee125b7](https://linux-hardware.org/?probe=79aee125b7) | Apr 05, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | Notebook    | [46b4d12526](https://linux-hardware.org/?probe=46b4d12526) | Apr 04, 2022 |
| ASUSTek       | M3A78-EMH HDMI              | Desktop     | [4462ffed73](https://linux-hardware.org/?probe=4462ffed73) | Apr 01, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [192125a71f](https://linux-hardware.org/?probe=192125a71f) | Mar 29, 2022 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [7a4dfc156e](https://linux-hardware.org/?probe=7a4dfc156e) | Mar 28, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [b89fa9f260](https://linux-hardware.org/?probe=b89fa9f260) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [ce61872360](https://linux-hardware.org/?probe=ce61872360) | Mar 23, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [97cfd592c5](https://linux-hardware.org/?probe=97cfd592c5) | Mar 22, 2022 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | Notebook    | [0228881558](https://linux-hardware.org/?probe=0228881558) | Mar 18, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [f7ee97d348](https://linux-hardware.org/?probe=f7ee97d348) | Mar 16, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [5b18945822](https://linux-hardware.org/?probe=5b18945822) | Mar 15, 2022 |
| Acer          | Swift SF514-54GT            | Notebook    | [a170593a67](https://linux-hardware.org/?probe=a170593a67) | Mar 13, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [8d52e31d86](https://linux-hardware.org/?probe=8d52e31d86) | Mar 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [ea52efd6b6](https://linux-hardware.org/?probe=ea52efd6b6) | Mar 07, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [d9c28765e7](https://linux-hardware.org/?probe=d9c28765e7) | Mar 03, 2022 |
| MSI           | GV72 8RC                    | Notebook    | [60382ef4e5](https://linux-hardware.org/?probe=60382ef4e5) | Feb 25, 2022 |
| MSI           | GV72 8RC                    | Notebook    | [9cfacc57c2](https://linux-hardware.org/?probe=9cfacc57c2) | Feb 24, 2022 |
| MSI           | P65 Creator 9SD             | Notebook    | [093c9b9f41](https://linux-hardware.org/?probe=093c9b9f41) | Feb 24, 2022 |
| Unknown       | Unknown                     | Soc         | [1f1fc02023](https://linux-hardware.org/?probe=1f1fc02023) | Feb 24, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [076c8f6e01](https://linux-hardware.org/?probe=076c8f6e01) | Feb 23, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [85c09f63f0](https://linux-hardware.org/?probe=85c09f63f0) | Feb 23, 2022 |
| MSI           | P65 Creator 9SD             | Notebook    | [2782f833c9](https://linux-hardware.org/?probe=2782f833c9) | Feb 23, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [c11d937631](https://linux-hardware.org/?probe=c11d937631) | Feb 23, 2022 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [c408f72a53](https://linux-hardware.org/?probe=c408f72a53) | Feb 23, 2022 |
| HP            | DevX                        | Notebook    | [8dc3513586](https://linux-hardware.org/?probe=8dc3513586) | Feb 16, 2022 |
| HP            | DevX                        | Notebook    | [c6f8c8e65b](https://linux-hardware.org/?probe=c6f8c8e65b) | Feb 16, 2022 |
| CJSCOPE       | Z Series                    | Notebook    | [c594abda0a](https://linux-hardware.org/?probe=c594abda0a) | Feb 16, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [92456282bc](https://linux-hardware.org/?probe=92456282bc) | Feb 14, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [bf52168e79](https://linux-hardware.org/?probe=bf52168e79) | Feb 14, 2022 |
| Dell          | Latitude 5420               | Notebook    | [3c5cf0b4e7](https://linux-hardware.org/?probe=3c5cf0b4e7) | Feb 07, 2022 |
| Sony          | VAIO                        | All in one  | [d1d4080f45](https://linux-hardware.org/?probe=d1d4080f45) | Feb 07, 2022 |
| Dell          | Latitude E7450              | Notebook    | [dd81e34279](https://linux-hardware.org/?probe=dd81e34279) | Feb 07, 2022 |
| ASUSTek       | CM6630_CM6730_CM6830        | Desktop     | [bb588fd423](https://linux-hardware.org/?probe=bb588fd423) | Feb 07, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [9d00f74637](https://linux-hardware.org/?probe=9d00f74637) | Feb 05, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [76dff27038](https://linux-hardware.org/?probe=76dff27038) | Feb 02, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [a4c71279a4](https://linux-hardware.org/?probe=a4c71279a4) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [589137e95b](https://linux-hardware.org/?probe=589137e95b) | Feb 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [0a04b2d1b1](https://linux-hardware.org/?probe=0a04b2d1b1) | Jan 31, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [43011b8d27](https://linux-hardware.org/?probe=43011b8d27) | Jan 30, 2022 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [e6af97e09c](https://linux-hardware.org/?probe=e6af97e09c) | Jan 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f653016830](https://linux-hardware.org/?probe=f653016830) | Jan 28, 2022 |
| ASUSTek       | PU403UA                     | Notebook    | [25ac7ce226](https://linux-hardware.org/?probe=25ac7ce226) | Jan 28, 2022 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [40d8a83107](https://linux-hardware.org/?probe=40d8a83107) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [8db65bef56](https://linux-hardware.org/?probe=8db65bef56) | Jan 20, 2022 |
| Gigabyte      | P65                         | Notebook    | [4664ba9c41](https://linux-hardware.org/?probe=4664ba9c41) | Jan 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [fb4c60c7b1](https://linux-hardware.org/?probe=fb4c60c7b1) | Jan 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [0b302317eb](https://linux-hardware.org/?probe=0b302317eb) | Jan 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [94988f80b6](https://linux-hardware.org/?probe=94988f80b6) | Jan 09, 2022 |
| Acer          | Aspire M3970                | Desktop     | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [cbb5305dc7](https://linux-hardware.org/?probe=cbb5305dc7) | Dec 30, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [8eec04fc92](https://linux-hardware.org/?probe=8eec04fc92) | Dec 29, 2021 |
| DFI           | HD330-Q87CR                 | Desktop     | [000e53fce1](https://linux-hardware.org/?probe=000e53fce1) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f8a6ac527d](https://linux-hardware.org/?probe=f8a6ac527d) | Dec 27, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [85bcddc2e5](https://linux-hardware.org/?probe=85bcddc2e5) | Dec 27, 2021 |
| Dell          | Inspiron 5480               | Notebook    | [217737fa73](https://linux-hardware.org/?probe=217737fa73) | Dec 24, 2021 |
| Dell          | System Vostro 3450          | Notebook    | [482adf74be](https://linux-hardware.org/?probe=482adf74be) | Dec 21, 2021 |
| Dell          | System Vostro 3450          | Notebook    | [965939d30a](https://linux-hardware.org/?probe=965939d30a) | Dec 21, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [041e50f6a8](https://linux-hardware.org/?probe=041e50f6a8) | Dec 20, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [f9fbdf780e](https://linux-hardware.org/?probe=f9fbdf780e) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [2e9fd50292](https://linux-hardware.org/?probe=2e9fd50292) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [452b8c0ac4](https://linux-hardware.org/?probe=452b8c0ac4) | Dec 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0f6fd49686](https://linux-hardware.org/?probe=0f6fd49686) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [aae6578de1](https://linux-hardware.org/?probe=aae6578de1) | Dec 16, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [d5faa621cc](https://linux-hardware.org/?probe=d5faa621cc) | Dec 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [8705e3aea1](https://linux-hardware.org/?probe=8705e3aea1) | Dec 07, 2021 |
| Huanan        | B85                         | Desktop     | [d2b55c013c](https://linux-hardware.org/?probe=d2b55c013c) | Dec 07, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [ef6f4cf593](https://linux-hardware.org/?probe=ef6f4cf593) | Dec 05, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [2965330cf0](https://linux-hardware.org/?probe=2965330cf0) | Dec 02, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [6ab102bc84](https://linux-hardware.org/?probe=6ab102bc84) | Nov 30, 2021 |
| Acer          | EG43LMK                     | Desktop     | [28e31230a4](https://linux-hardware.org/?probe=28e31230a4) | Nov 28, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [a99a51f4e0](https://linux-hardware.org/?probe=a99a51f4e0) | Nov 23, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8fb57be688](https://linux-hardware.org/?probe=8fb57be688) | Nov 22, 2021 |
| Acer          | Aspire E5-432G              | Notebook    | [d6fe7992f3](https://linux-hardware.org/?probe=d6fe7992f3) | Nov 21, 2021 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [ae15f235e1](https://linux-hardware.org/?probe=ae15f235e1) | Nov 20, 2021 |
| ASRock        | G41C-VS                     | Desktop     | [e4a0a0c2c1](https://linux-hardware.org/?probe=e4a0a0c2c1) | Nov 19, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [0315115315](https://linux-hardware.org/?probe=0315115315) | Nov 07, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [9ebc122525](https://linux-hardware.org/?probe=9ebc122525) | Nov 02, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [1719b2dc9d](https://linux-hardware.org/?probe=1719b2dc9d) | Oct 30, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [edc27953c6](https://linux-hardware.org/?probe=edc27953c6) | Oct 28, 2021 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [f20f2bfc32](https://linux-hardware.org/?probe=f20f2bfc32) | Oct 26, 2021 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| Acer          | AS1830                      | Notebook    | [bcef8c44a6](https://linux-hardware.org/?probe=bcef8c44a6) | Oct 26, 2021 |
| Lenovo        | ThinkPad E585 20KVCTO1WW    | Notebook    | [204598f27d](https://linux-hardware.org/?probe=204598f27d) | Oct 26, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f8dc8086fb](https://linux-hardware.org/?probe=f8dc8086fb) | Oct 25, 2021 |
| PANSHI        | B85-S1 V1.0                 | Desktop     | [963f2f28d4](https://linux-hardware.org/?probe=963f2f28d4) | Oct 24, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [09e3d5da46](https://linux-hardware.org/?probe=09e3d5da46) | Oct 21, 2021 |
| HP            | 84FD 10                     | Desktop     | [fb32fc7215](https://linux-hardware.org/?probe=fb32fc7215) | Oct 14, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [caeaeaddf2](https://linux-hardware.org/?probe=caeaeaddf2) | Oct 12, 2021 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [eef22ec3df](https://linux-hardware.org/?probe=eef22ec3df) | Oct 10, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [22e290b148](https://linux-hardware.org/?probe=22e290b148) | Oct 08, 2021 |
| HP            | 21D0                        | Desktop     | [4fccb60381](https://linux-hardware.org/?probe=4fccb60381) | Oct 08, 2021 |
| win elemen... | MBOX WS001                  | Notebook    | [95cb9076bc](https://linux-hardware.org/?probe=95cb9076bc) | Oct 04, 2021 |
| Acer          | TMP645-M                    | Notebook    | [c3daab516f](https://linux-hardware.org/?probe=c3daab516f) | Oct 03, 2021 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [4b370353e4](https://linux-hardware.org/?probe=4b370353e4) | Sep 29, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [b961548815](https://linux-hardware.org/?probe=b961548815) | Sep 26, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [fbe6b1147d](https://linux-hardware.org/?probe=fbe6b1147d) | Sep 24, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [6174640bb5](https://linux-hardware.org/?probe=6174640bb5) | Sep 23, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [97a692e271](https://linux-hardware.org/?probe=97a692e271) | Sep 23, 2021 |
| MSI           | GS76 Stealth 11UH           | Notebook    | [0589c1c238](https://linux-hardware.org/?probe=0589c1c238) | Sep 18, 2021 |
| Lenovo        | ThinkPad X230 2324CD1       | Notebook    | [348eb8e841](https://linux-hardware.org/?probe=348eb8e841) | Sep 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [7725289d30](https://linux-hardware.org/?probe=7725289d30) | Sep 17, 2021 |
| Acer          | Swift SF514-55TA            | Notebook    | [b4ff244fa1](https://linux-hardware.org/?probe=b4ff244fa1) | Sep 14, 2021 |
| Acer          | Swift SF514-55TA            | Notebook    | [ca370567d0](https://linux-hardware.org/?probe=ca370567d0) | Sep 14, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7114ee3f72](https://linux-hardware.org/?probe=7114ee3f72) | Sep 13, 2021 |
| Acer          | Swift SF514-55TA            | Notebook    | [c3a4ff2798](https://linux-hardware.org/?probe=c3a4ff2798) | Sep 12, 2021 |
| HP            | Pavilion dv7                | Notebook    | [6ed3caac2b](https://linux-hardware.org/?probe=6ed3caac2b) | Sep 10, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [ddb9671a92](https://linux-hardware.org/?probe=ddb9671a92) | Sep 09, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [b59922b47b](https://linux-hardware.org/?probe=b59922b47b) | Sep 09, 2021 |
| Acer          | Aspire Z1801                | All in one  | [82c1656309](https://linux-hardware.org/?probe=82c1656309) | Aug 31, 2021 |
| Lenovo        | ThinkCentre M58 7627AA9     | Desktop     | [e5bedff47d](https://linux-hardware.org/?probe=e5bedff47d) | Aug 29, 2021 |
| HP            | 802E                        | Desktop     | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1674818018](https://linux-hardware.org/?probe=1674818018) | Aug 23, 2021 |
| MSI           | Modern 14 B11M              | Notebook    | [63c6a56896](https://linux-hardware.org/?probe=63c6a56896) | Aug 22, 2021 |
| MSI           | Modern 14 B11M              | Notebook    | [f73a28166b](https://linux-hardware.org/?probe=f73a28166b) | Aug 22, 2021 |
| ASUSTek       | H61-PLUS                    | Desktop     | [806118d8b3](https://linux-hardware.org/?probe=806118d8b3) | Aug 22, 2021 |
| ASUSTek       | GL552VW                     | Notebook    | [b48b810fc9](https://linux-hardware.org/?probe=b48b810fc9) | Aug 21, 2021 |
| Acer          | Aspire A515-46              | Notebook    | [ad8f403c6d](https://linux-hardware.org/?probe=ad8f403c6d) | Aug 17, 2021 |
| AVITA         | NE14A2                      | Notebook    | [cd5b403f7b](https://linux-hardware.org/?probe=cd5b403f7b) | Aug 16, 2021 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [65567a1be4](https://linux-hardware.org/?probe=65567a1be4) | Aug 10, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [51947c0182](https://linux-hardware.org/?probe=51947c0182) | Aug 07, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [a1565d1576](https://linux-hardware.org/?probe=a1565d1576) | Aug 05, 2021 |
| Unknown       | Unknown                     | Notebook    | [d4db86e4ac](https://linux-hardware.org/?probe=d4db86e4ac) | Aug 05, 2021 |
| Unknown       | Unknown                     | Notebook    | [bcb72c9247](https://linux-hardware.org/?probe=bcb72c9247) | Aug 05, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [37ac6809ad](https://linux-hardware.org/?probe=37ac6809ad) | Jul 31, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6b8e73456f](https://linux-hardware.org/?probe=6b8e73456f) | Jul 31, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [6c6e37fbfe](https://linux-hardware.org/?probe=6c6e37fbfe) | Jul 31, 2021 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [90d8b30078](https://linux-hardware.org/?probe=90d8b30078) | Jul 30, 2021 |
| Acer          | Swift SF313-52G             | Notebook    | [cf9d89a2f5](https://linux-hardware.org/?probe=cf9d89a2f5) | Jul 28, 2021 |
| AMI           | Unknown                     | Notebook    | [455466668e](https://linux-hardware.org/?probe=455466668e) | Jul 16, 2021 |
| Lenovo        | ThinkPad T510 4384CJ7       | Notebook    | [744091f92e](https://linux-hardware.org/?probe=744091f92e) | Jul 12, 2021 |
| Lenovo        | ThinkPad T510 4384CJ7       | Notebook    | [9f572c562f](https://linux-hardware.org/?probe=9f572c562f) | Jul 11, 2021 |
| Microsoft     | Surface Book 3              | Tablet      | [c8fb985280](https://linux-hardware.org/?probe=c8fb985280) | Jul 10, 2021 |
| ASUSTek       | E203NA                      | Notebook    | [a4aa015f4e](https://linux-hardware.org/?probe=a4aa015f4e) | Jul 09, 2021 |
| Dell          | Latitude 5420               | Notebook    | [7dc37e8b8c](https://linux-hardware.org/?probe=7dc37e8b8c) | Jul 09, 2021 |
| Dell          | Latitude 5420               | Notebook    | [1c11a8170f](https://linux-hardware.org/?probe=1c11a8170f) | Jul 09, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a8c5113f4c](https://linux-hardware.org/?probe=a8c5113f4c) | Jul 06, 2021 |
| Gigabyte      | H67MA-UD2H-B3               | Desktop     | [e014f9e41f](https://linux-hardware.org/?probe=e014f9e41f) | Jul 05, 2021 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [55bdc0f976](https://linux-hardware.org/?probe=55bdc0f976) | Jun 28, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [d90a6deaeb](https://linux-hardware.org/?probe=d90a6deaeb) | Jun 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [0e6ca5f944](https://linux-hardware.org/?probe=0e6ca5f944) | Jun 27, 2021 |
| Acer          | TravelMate P653-M           | Notebook    | [f8509314e3](https://linux-hardware.org/?probe=f8509314e3) | Jun 27, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [42090bac96](https://linux-hardware.org/?probe=42090bac96) | Jun 27, 2021 |
| Toshiba       | Satellite L850              | Notebook    | [4632f9e875](https://linux-hardware.org/?probe=4632f9e875) | Jun 26, 2021 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [0624df0c82](https://linux-hardware.org/?probe=0624df0c82) | Jun 26, 2021 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | Desktop     | [cf9f5ab2b6](https://linux-hardware.org/?probe=cf9f5ab2b6) | Jun 23, 2021 |
| Toshiba       | Satellite L850              | Notebook    | [a1f2e3a8a2](https://linux-hardware.org/?probe=a1f2e3a8a2) | Jun 23, 2021 |
| Acer          | Swift SF514-52T             | Notebook    | [9e0f7fa4a4](https://linux-hardware.org/?probe=9e0f7fa4a4) | Jun 22, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [98be9faa06](https://linux-hardware.org/?probe=98be9faa06) | Jun 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [6b7a4709ca](https://linux-hardware.org/?probe=6b7a4709ca) | Jun 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [b48bc39bc2](https://linux-hardware.org/?probe=b48bc39bc2) | Jun 20, 2021 |
| Acer          | Aspire U5-710               | All in one  | [c2ff1a33ee](https://linux-hardware.org/?probe=c2ff1a33ee) | Jun 19, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [7bf43ae0d0](https://linux-hardware.org/?probe=7bf43ae0d0) | Jun 19, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [9a4e288f49](https://linux-hardware.org/?probe=9a4e288f49) | Jun 19, 2021 |
| AMD           | Celadon-CZN                 | Notebook    | [cfad33c72b](https://linux-hardware.org/?probe=cfad33c72b) | Jun 16, 2021 |
| Supermicro    | C9Z490-PGW                  | Desktop     | [9b89e87202](https://linux-hardware.org/?probe=9b89e87202) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [18b2fc7e21](https://linux-hardware.org/?probe=18b2fc7e21) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [db99ef3085](https://linux-hardware.org/?probe=db99ef3085) | Jun 14, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3RM0... | Notebook    | [cb69a79f5c](https://linux-hardware.org/?probe=cb69a79f5c) | Jun 14, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [2b38485e94](https://linux-hardware.org/?probe=2b38485e94) | Jun 13, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [b87ca56da6](https://linux-hardware.org/?probe=b87ca56da6) | Jun 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [5221d99db7](https://linux-hardware.org/?probe=5221d99db7) | Jun 10, 2021 |
| HP            | Unknown                     | Notebook    | [e59d9dcf16](https://linux-hardware.org/?probe=e59d9dcf16) | Jun 08, 2021 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [be02c1622c](https://linux-hardware.org/?probe=be02c1622c) | Jun 06, 2021 |
| MSI           | PE62 8RD                    | Notebook    | [30bb43121d](https://linux-hardware.org/?probe=30bb43121d) | Jun 01, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [ba117fef7e](https://linux-hardware.org/?probe=ba117fef7e) | May 31, 2021 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [e7eca73b93](https://linux-hardware.org/?probe=e7eca73b93) | May 30, 2021 |
| Dell          | 0RY206                      | Desktop     | [f02982ff12](https://linux-hardware.org/?probe=f02982ff12) | May 29, 2021 |
| ASRock        | H310M-ITX/ac                | Desktop     | [839b20476a](https://linux-hardware.org/?probe=839b20476a) | May 29, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [6b0f0cd327](https://linux-hardware.org/?probe=6b0f0cd327) | May 27, 2021 |
| Lenovo        | V330-15IGM                  | Notebook    | [02894a3c1d](https://linux-hardware.org/?probe=02894a3c1d) | May 26, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [d63399b396](https://linux-hardware.org/?probe=d63399b396) | May 19, 2021 |
| Intel         | NUC7i5BNB J31144-303        | Mini pc     | [616e5444ca](https://linux-hardware.org/?probe=616e5444ca) | May 19, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [bbc8131c67](https://linux-hardware.org/?probe=bbc8131c67) | May 05, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [fdbc72ed13](https://linux-hardware.org/?probe=fdbc72ed13) | May 05, 2021 |
| ASUSTek       | P9D-X Series                | Server      | [ae3bfe95c9](https://linux-hardware.org/?probe=ae3bfe95c9) | May 03, 2021 |
| Toshiba       | Satellite L850              | Notebook    | [3f32e7ed1e](https://linux-hardware.org/?probe=3f32e7ed1e) | May 02, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [6928edc4c3](https://linux-hardware.org/?probe=6928edc4c3) | Apr 30, 2021 |
| ASRock        | H55M/USB3                   | Desktop     | [8041f40ea2](https://linux-hardware.org/?probe=8041f40ea2) | Apr 22, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [060122f540](https://linux-hardware.org/?probe=060122f540) | Apr 19, 2021 |
| Acer          | Aspire Z1-751               | All in one  | [6cca1f0784](https://linux-hardware.org/?probe=6cca1f0784) | Apr 18, 2021 |
| HP            | 0AECh D                     | Desktop     | [4e2517cb92](https://linux-hardware.org/?probe=4e2517cb92) | Apr 17, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [f67c224c2d](https://linux-hardware.org/?probe=f67c224c2d) | Apr 17, 2021 |
| Acer          | Aspire Z1-751               | All in one  | [088ee04d43](https://linux-hardware.org/?probe=088ee04d43) | Apr 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0c83abd0f8](https://linux-hardware.org/?probe=0c83abd0f8) | Apr 11, 2021 |
| Advantech     | VEGA-6301M                  | Soc         | [cfbb1b9f64](https://linux-hardware.org/?probe=cfbb1b9f64) | Mar 24, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3dcec36efc](https://linux-hardware.org/?probe=3dcec36efc) | Mar 24, 2021 |
| Acer          | M1930                       | Desktop     | [ecd09c75f9](https://linux-hardware.org/?probe=ecd09c75f9) | Mar 23, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [ecbfcfa59d](https://linux-hardware.org/?probe=ecbfcfa59d) | Mar 23, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [6fed85f2b6](https://linux-hardware.org/?probe=6fed85f2b6) | Mar 21, 2021 |
| MSI           | GL65 9SD                    | Notebook    | [e3c6065246](https://linux-hardware.org/?probe=e3c6065246) | Mar 16, 2021 |
| Acer          | Aspire A515-56G             | Notebook    | [8bedf1b6da](https://linux-hardware.org/?probe=8bedf1b6da) | Mar 13, 2021 |
| Dell          | Latitude E7240              | Notebook    | [448e25eb93](https://linux-hardware.org/?probe=448e25eb93) | Mar 04, 2021 |
| ASUSTek       | K53SV                       | Notebook    | [743ce0ed2d](https://linux-hardware.org/?probe=743ce0ed2d) | Mar 03, 2021 |
| Dell          | Latitude E7240              | Notebook    | [adcc4f6449](https://linux-hardware.org/?probe=adcc4f6449) | Feb 25, 2021 |
| Acer          | Veriton L4630G V:1.0        | Desktop     | [d5413884e0](https://linux-hardware.org/?probe=d5413884e0) | Feb 15, 2021 |
| Lenovo        | IdeaPad S410 20301          | Notebook    | [90bb71374c](https://linux-hardware.org/?probe=90bb71374c) | Feb 14, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [207fe36973](https://linux-hardware.org/?probe=207fe36973) | Feb 07, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [626560cf30](https://linux-hardware.org/?probe=626560cf30) | Feb 04, 2021 |
| ASRock        | HM87-MXM                    | Desktop     | [95efd1e9a2](https://linux-hardware.org/?probe=95efd1e9a2) | Feb 04, 2021 |
| Acer          | Aspire 4755                 | Notebook    | [1ce988a158](https://linux-hardware.org/?probe=1ce988a158) | Jan 30, 2021 |
| Acer          | IPIMB-AR                    | Desktop     | [eb7a1feeff](https://linux-hardware.org/?probe=eb7a1feeff) | Jan 25, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b40787d632](https://linux-hardware.org/?probe=b40787d632) | Jan 24, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [8fdb02babb](https://linux-hardware.org/?probe=8fdb02babb) | Jan 24, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [9ebcac45bd](https://linux-hardware.org/?probe=9ebcac45bd) | Jan 24, 2021 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [ac56dd5c89](https://linux-hardware.org/?probe=ac56dd5c89) | Jan 23, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [3cd78291fc](https://linux-hardware.org/?probe=3cd78291fc) | Jan 23, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [1deb2b04c5](https://linux-hardware.org/?probe=1deb2b04c5) | Jan 21, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [b690109a78](https://linux-hardware.org/?probe=b690109a78) | Jan 16, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [7ade5574be](https://linux-hardware.org/?probe=7ade5574be) | Jan 14, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [b6a804b8b9](https://linux-hardware.org/?probe=b6a804b8b9) | Jan 10, 2021 |
| Dell          | Inspiron 5537               | Notebook    | [c88fbbaa7b](https://linux-hardware.org/?probe=c88fbbaa7b) | Jan 10, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [4758f7fd48](https://linux-hardware.org/?probe=4758f7fd48) | Jan 07, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e5dc6589db](https://linux-hardware.org/?probe=e5dc6589db) | Jan 05, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [f8f8546b66](https://linux-hardware.org/?probe=f8f8546b66) | Dec 28, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f0d6282b73](https://linux-hardware.org/?probe=f0d6282b73) | Dec 23, 2020 |
| Gigabyte      | H310M H                     | Desktop     | [dfa5c13a96](https://linux-hardware.org/?probe=dfa5c13a96) | Dec 22, 2020 |
| MSI           | AM1M                        | Desktop     | [e7e7d1e0cc](https://linux-hardware.org/?probe=e7e7d1e0cc) | Dec 21, 2020 |
| HP            | ZBook 15 G6                 | Notebook    | [d4e634a972](https://linux-hardware.org/?probe=d4e634a972) | Dec 20, 2020 |
| ASUSTek       | PU403UA                     | Notebook    | [aee4dc13b7](https://linux-hardware.org/?probe=aee4dc13b7) | Dec 19, 2020 |
| Acer          | Aspire 4720Z                | Notebook    | [88bd8075b2](https://linux-hardware.org/?probe=88bd8075b2) | Dec 16, 2020 |
| Acer          | Aspire 4720Z                | Notebook    | [93cfeab463](https://linux-hardware.org/?probe=93cfeab463) | Dec 16, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [fb4b7a114e](https://linux-hardware.org/?probe=fb4b7a114e) | Dec 14, 2020 |
| Gigabyte      | H87-HD3                     | Desktop     | [55f095e43d](https://linux-hardware.org/?probe=55f095e43d) | Dec 13, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [db6ca10333](https://linux-hardware.org/?probe=db6ca10333) | Dec 02, 2020 |
| Gigabyte      | EP43-S3L                    | Desktop     | [7c9b5cd232](https://linux-hardware.org/?probe=7c9b5cd232) | Nov 28, 2020 |
| Gigabyte      | EP43-S3L                    | Desktop     | [218d68cc94](https://linux-hardware.org/?probe=218d68cc94) | Nov 27, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [f1f4d46046](https://linux-hardware.org/?probe=f1f4d46046) | Nov 26, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [799008f314](https://linux-hardware.org/?probe=799008f314) | Nov 26, 2020 |
| Gigabyte      | EP43-S3L                    | Desktop     | [c91fdcd723](https://linux-hardware.org/?probe=c91fdcd723) | Nov 26, 2020 |
| ASUSTek       | GR8 II-K                    | Desktop     | [dce0e65158](https://linux-hardware.org/?probe=dce0e65158) | Nov 24, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [df130b5488](https://linux-hardware.org/?probe=df130b5488) | Nov 23, 2020 |
| Unknown       | CMGB                        | Mini pc     | [66a02f462f](https://linux-hardware.org/?probe=66a02f462f) | Nov 19, 2020 |
| Nvidia        | Tegra                       | Soc         | [d03c207bf2](https://linux-hardware.org/?probe=d03c207bf2) | Nov 18, 2020 |
| Nvidia        | Tegra                       | Soc         | [df2ccd3ed4](https://linux-hardware.org/?probe=df2ccd3ed4) | Nov 18, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [8b7818376f](https://linux-hardware.org/?probe=8b7818376f) | Nov 18, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [3d64c2bcc8](https://linux-hardware.org/?probe=3d64c2bcc8) | Nov 17, 2020 |
| Acer          | Swift SF514-54GT            | Notebook    | [3301702747](https://linux-hardware.org/?probe=3301702747) | Nov 14, 2020 |
| Acer          | Swift SF514-54GT            | Notebook    | [70015c39cf](https://linux-hardware.org/?probe=70015c39cf) | Nov 14, 2020 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [35bc246b54](https://linux-hardware.org/?probe=35bc246b54) | Nov 13, 2020 |
| Acer          | Switch SW512-52             | Tablet      | [4b0ed624fa](https://linux-hardware.org/?probe=4b0ed624fa) | Nov 12, 2020 |
| Acer          | Aspire 4755                 | Notebook    | [5251bda552](https://linux-hardware.org/?probe=5251bda552) | Nov 11, 2020 |
| ASRock        | HM87-MXM                    | Desktop     | [d47723e369](https://linux-hardware.org/?probe=d47723e369) | Nov 03, 2020 |
| Unknown       | Unknown                     | Desktop     | [3ed3ea4f60](https://linux-hardware.org/?probe=3ed3ea4f60) | Oct 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [c80fe9e03a](https://linux-hardware.org/?probe=c80fe9e03a) | Oct 29, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [3735b2bb7d](https://linux-hardware.org/?probe=3735b2bb7d) | Oct 27, 2020 |
| Gigabyte      | B85M-D2V                    | Desktop     | [1f2b50c872](https://linux-hardware.org/?probe=1f2b50c872) | Oct 24, 2020 |
| Lenovo        | XiaoXinAir 15ARE 2021 82... | Notebook    | [2f285baee5](https://linux-hardware.org/?probe=2f285baee5) | Oct 23, 2020 |
| Lenovo        | ThinkPad Edge E531 68853... | Notebook    | [acbd72739e](https://linux-hardware.org/?probe=acbd72739e) | Oct 20, 2020 |
| Lenovo        | XiaoXinAir 15ARE 2021 82... | Notebook    | [d800296611](https://linux-hardware.org/?probe=d800296611) | Oct 16, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [352ce3d09c](https://linux-hardware.org/?probe=352ce3d09c) | Oct 16, 2020 |
| ASUSTek       | K30AM-J_A_F_K31AM-J         | Desktop     | [8de90e5004](https://linux-hardware.org/?probe=8de90e5004) | Oct 12, 2020 |
| MSI           | B450M-A PRO MAX             | Desktop     | [3712afebf5](https://linux-hardware.org/?probe=3712afebf5) | Oct 09, 2020 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8b4ffad831](https://linux-hardware.org/?probe=8b4ffad831) | Oct 06, 2020 |
| Acer          | Aspire A715-71G             | Notebook    | [cd05576b34](https://linux-hardware.org/?probe=cd05576b34) | Oct 04, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [605fe21a48](https://linux-hardware.org/?probe=605fe21a48) | Oct 03, 2020 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [c8033471fb](https://linux-hardware.org/?probe=c8033471fb) | Oct 01, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [62da42ec3c](https://linux-hardware.org/?probe=62da42ec3c) | Sep 27, 2020 |
| HP            | G62                         | Notebook    | [c9c310542a](https://linux-hardware.org/?probe=c9c310542a) | Sep 27, 2020 |
| ASUSTek       | P2440UA                     | Notebook    | [4c196d17c7](https://linux-hardware.org/?probe=4c196d17c7) | Sep 25, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [b2cdadc21e](https://linux-hardware.org/?probe=b2cdadc21e) | Sep 25, 2020 |
| Acer          | TravelMate P614-51TG        | Notebook    | [e0fbefb33a](https://linux-hardware.org/?probe=e0fbefb33a) | Sep 23, 2020 |
| IBM           | 49Y6512                     | Server      | [5c4a86988b](https://linux-hardware.org/?probe=5c4a86988b) | Sep 19, 2020 |
| HP            | 339A                        | Desktop     | [84f1e1735f](https://linux-hardware.org/?probe=84f1e1735f) | Sep 19, 2020 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [558b4c758d](https://linux-hardware.org/?probe=558b4c758d) | Sep 18, 2020 |
| Acer          | Swift SF514-52T             | Notebook    | [570875f21d](https://linux-hardware.org/?probe=570875f21d) | Sep 12, 2020 |
| ASUSTek       | PU403UA                     | Notebook    | [bdae065e30](https://linux-hardware.org/?probe=bdae065e30) | Sep 11, 2020 |
| Acer          | TravelMate P633-M           | Notebook    | [a7fdf21400](https://linux-hardware.org/?probe=a7fdf21400) | Sep 11, 2020 |
| IBM           | 49Y6512                     | Server      | [7bb9b3d0f9](https://linux-hardware.org/?probe=7bb9b3d0f9) | Sep 11, 2020 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [d2b7da6eeb](https://linux-hardware.org/?probe=d2b7da6eeb) | Sep 11, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [d22bad4798](https://linux-hardware.org/?probe=d22bad4798) | Sep 09, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [72ffc70b7f](https://linux-hardware.org/?probe=72ffc70b7f) | Sep 07, 2020 |
| Dell          | 0RY206                      | Desktop     | [40e7b0cafb](https://linux-hardware.org/?probe=40e7b0cafb) | Sep 05, 2020 |
| ASUSTek       | B85M-K                      | Desktop     | [8fe74ac1ad](https://linux-hardware.org/?probe=8fe74ac1ad) | Sep 04, 2020 |
| Unknown       | Unknown                     | Desktop     | [e5e9a43e32](https://linux-hardware.org/?probe=e5e9a43e32) | Sep 04, 2020 |
| MSI           | GS63 7RE                    | Notebook    | [e95a9b9d20](https://linux-hardware.org/?probe=e95a9b9d20) | Sep 03, 2020 |
| MSI           | GS63 7RE                    | Notebook    | [c21eb43b7a](https://linux-hardware.org/?probe=c21eb43b7a) | Sep 03, 2020 |
| NEXCOM        | SKLD4-P1                    | Desktop     | [23c5f53c73](https://linux-hardware.org/?probe=23c5f53c73) | Sep 03, 2020 |
| NEXCOM        | SKLD4-P1                    | Desktop     | [e27e3df3f3](https://linux-hardware.org/?probe=e27e3df3f3) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [26c3ba8ef4](https://linux-hardware.org/?probe=26c3ba8ef4) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [066c04a858](https://linux-hardware.org/?probe=066c04a858) | Sep 02, 2020 |
| Nvidia        | Tegra                       | Soc         | [a1e1fc9259](https://linux-hardware.org/?probe=a1e1fc9259) | Sep 01, 2020 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e46d6617a9](https://linux-hardware.org/?probe=e46d6617a9) | Aug 28, 2020 |
| Lenovo        | 7Z74                        | Desktop     | [84586c4db2](https://linux-hardware.org/?probe=84586c4db2) | Aug 27, 2020 |
| Acer          | Switch SW512-52             | Tablet      | [6e4861e310](https://linux-hardware.org/?probe=6e4861e310) | Aug 25, 2020 |
| ASUSTek       | B85M-K                      | Desktop     | [9fd11c530f](https://linux-hardware.org/?probe=9fd11c530f) | Aug 21, 2020 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [b4bad24684](https://linux-hardware.org/?probe=b4bad24684) | Aug 21, 2020 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [f7ea5d964e](https://linux-hardware.org/?probe=f7ea5d964e) | Aug 21, 2020 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [68f311bdd9](https://linux-hardware.org/?probe=68f311bdd9) | Aug 21, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [bec5ea27a1](https://linux-hardware.org/?probe=bec5ea27a1) | Aug 13, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [67cf1d26af](https://linux-hardware.org/?probe=67cf1d26af) | Aug 12, 2020 |
| Dell          | Inspiron 5759               | Notebook    | [6484055ab4](https://linux-hardware.org/?probe=6484055ab4) | Aug 10, 2020 |
| Intel         | JV10_CS                     | Notebook    | [f031e01d35](https://linux-hardware.org/?probe=f031e01d35) | Aug 09, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [5e3aebe1ec](https://linux-hardware.org/?probe=5e3aebe1ec) | Aug 02, 2020 |
| MSI           | CX62 6QD                    | Notebook    | [7484f1f7b0](https://linux-hardware.org/?probe=7484f1f7b0) | Jul 31, 2020 |
| Acer          | Aspire one                  | Notebook    | [534968996d](https://linux-hardware.org/?probe=534968996d) | Jul 24, 2020 |
| ASUSTek       | E203NA                      | Notebook    | [818318440a](https://linux-hardware.org/?probe=818318440a) | Jul 11, 2020 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [20cb7c14f8](https://linux-hardware.org/?probe=20cb7c14f8) | Jul 10, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [e012c28e4a](https://linux-hardware.org/?probe=e012c28e4a) | Jul 06, 2020 |
| Lenovo        | ThinkPad T420s 4171A18      | Notebook    | [aba119c0fe](https://linux-hardware.org/?probe=aba119c0fe) | Jul 03, 2020 |
| Lenovo        | ThinkPad T420s 4171A18      | Notebook    | [b23ac2b9df](https://linux-hardware.org/?probe=b23ac2b9df) | Jul 03, 2020 |
| HP            | Pavilion dv7                | Notebook    | [cdb63f485d](https://linux-hardware.org/?probe=cdb63f485d) | Jul 02, 2020 |
| HP            | Pavilion dv7                | Notebook    | [c130b59bb4](https://linux-hardware.org/?probe=c130b59bb4) | Jul 02, 2020 |
| MSI           | GS63 7RE                    | Notebook    | [2fe77551dc](https://linux-hardware.org/?probe=2fe77551dc) | Jun 30, 2020 |
| MSI           | PE72 8RD                    | Notebook    | [f91a312928](https://linux-hardware.org/?probe=f91a312928) | Jun 24, 2020 |
| ASUSTek       | UX30                        | Notebook    | [2b613d2551](https://linux-hardware.org/?probe=2b613d2551) | Jun 20, 2020 |
| MSI           | GS63 7RE                    | Notebook    | [3ddf7394d8](https://linux-hardware.org/?probe=3ddf7394d8) | Jun 18, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [925fdfd7c7](https://linux-hardware.org/?probe=925fdfd7c7) | Jun 16, 2020 |
| Acer          | Aspire E5-553G              | Notebook    | [7ac3604857](https://linux-hardware.org/?probe=7ac3604857) | Jun 14, 2020 |
| MSI           | GS63 7RE                    | Notebook    | [8f4591f672](https://linux-hardware.org/?probe=8f4591f672) | Jun 09, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [208f945a87](https://linux-hardware.org/?probe=208f945a87) | Jun 02, 2020 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [6e02cd7e95](https://linux-hardware.org/?probe=6e02cd7e95) | Jun 01, 2020 |
| Dell          | 0RY206                      | Desktop     | [648bdee6ec](https://linux-hardware.org/?probe=648bdee6ec) | May 29, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [9c2d3cb657](https://linux-hardware.org/?probe=9c2d3cb657) | May 24, 2020 |
| ASRock        | N68-GS4/USB3 FX             | Desktop     | [baefccea96](https://linux-hardware.org/?probe=baefccea96) | May 22, 2020 |
| Gigabyte      | B85M-D2V                    | Desktop     | [ec5da680aa](https://linux-hardware.org/?probe=ec5da680aa) | May 16, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [e9ce68b09f](https://linux-hardware.org/?probe=e9ce68b09f) | May 12, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1069d9adc6](https://linux-hardware.org/?probe=1069d9adc6) | May 10, 2020 |
| Accton        | SAU5041                     | Desktop     | [b1efc2e064](https://linux-hardware.org/?probe=b1efc2e064) | May 07, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [86b491fad9](https://linux-hardware.org/?probe=86b491fad9) | May 06, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [5ef719f7d8](https://linux-hardware.org/?probe=5ef719f7d8) | May 06, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [235c047618](https://linux-hardware.org/?probe=235c047618) | May 04, 2020 |
| ASUSTek       | P5Q                         | Desktop     | [c6681e044f](https://linux-hardware.org/?probe=c6681e044f) | May 02, 2020 |
| ASUSTek       | P5Q                         | Desktop     | [e620caac82](https://linux-hardware.org/?probe=e620caac82) | May 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [74697bc4d6](https://linux-hardware.org/?probe=74697bc4d6) | May 01, 2020 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [e818900359](https://linux-hardware.org/?probe=e818900359) | May 01, 2020 |
| ASUSTek       | X550VC                      | Notebook    | [e783786489](https://linux-hardware.org/?probe=e783786489) | May 01, 2020 |
| ASUSTek       | X550VC                      | Notebook    | [f46665f241](https://linux-hardware.org/?probe=f46665f241) | May 01, 2020 |
| ASUSTek       | X550VC                      | Notebook    | [c1036b76de](https://linux-hardware.org/?probe=c1036b76de) | May 01, 2020 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [ef970e6611](https://linux-hardware.org/?probe=ef970e6611) | Apr 30, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [b34b605dda](https://linux-hardware.org/?probe=b34b605dda) | Apr 30, 2020 |
| ASUSTek       | ASUSPRO B9440UAM            | Notebook    | [f77e6bd465](https://linux-hardware.org/?probe=f77e6bd465) | Apr 27, 2020 |
| ASUSTek       | ASUSPRO B9440UAM            | Notebook    | [96bb90cb10](https://linux-hardware.org/?probe=96bb90cb10) | Apr 27, 2020 |
| MSI           | GT63 Titan 9SG              | Notebook    | [c521df4d98](https://linux-hardware.org/?probe=c521df4d98) | Apr 25, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [530e0b1725](https://linux-hardware.org/?probe=530e0b1725) | Apr 24, 2020 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a90f89123d](https://linux-hardware.org/?probe=a90f89123d) | Apr 20, 2020 |
| Accton        | SAU5041                     | Desktop     | [c23eb2c1bb](https://linux-hardware.org/?probe=c23eb2c1bb) | Apr 13, 2020 |
| ASUSTek       | ZenBook 13 UX331UAL         | Notebook    | [188bcc68c0](https://linux-hardware.org/?probe=188bcc68c0) | Apr 11, 2020 |
| Dell          | Precision 7540              | Notebook    | [9b4e4569fc](https://linux-hardware.org/?probe=9b4e4569fc) | Apr 10, 2020 |
| Unknown       | Unknown                     | Desktop     | [c3983e6074](https://linux-hardware.org/?probe=c3983e6074) | Mar 31, 2020 |
| Unknown       | Unknown                     | Desktop     | [df51a87843](https://linux-hardware.org/?probe=df51a87843) | Mar 31, 2020 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [5568d1765b](https://linux-hardware.org/?probe=5568d1765b) | Mar 30, 2020 |
| Acer          | Switch SW512-52             | Tablet      | [3964989fab](https://linux-hardware.org/?probe=3964989fab) | Mar 30, 2020 |
| MSI           | MEG X299 CREATION           | Desktop     | [8112942b50](https://linux-hardware.org/?probe=8112942b50) | Mar 26, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [0a6d8786dc](https://linux-hardware.org/?probe=0a6d8786dc) | Mar 22, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [0b49d54fce](https://linux-hardware.org/?probe=0b49d54fce) | Mar 20, 2020 |
| ASUSTek       | D340MC-C                    | Desktop     | [e1396240d9](https://linux-hardware.org/?probe=e1396240d9) | Mar 19, 2020 |
| ASUSTek       | TAICHI31                    | Notebook    | [e942e4a43e](https://linux-hardware.org/?probe=e942e4a43e) | Mar 17, 2020 |
| ASUSTek       | D840MB                      | Desktop     | [c2599225a3](https://linux-hardware.org/?probe=c2599225a3) | Mar 11, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d491751516](https://linux-hardware.org/?probe=d491751516) | Mar 09, 2020 |
| Lenovo        | Board                       | Desktop     | [81650f1328](https://linux-hardware.org/?probe=81650f1328) | Mar 03, 2020 |
| MSI           | MEG X299 CREATION           | Desktop     | [dc2b1917fc](https://linux-hardware.org/?probe=dc2b1917fc) | Mar 02, 2020 |
| Acer          | Aspire one                  | Notebook    | [a956e8a20c](https://linux-hardware.org/?probe=a956e8a20c) | Mar 02, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [c291b5b947](https://linux-hardware.org/?probe=c291b5b947) | Feb 28, 2020 |
| ASRock        | A300M-STX                   | Desktop     | [fed0334ebb](https://linux-hardware.org/?probe=fed0334ebb) | Feb 25, 2020 |
| Acer          | Aspire E5-572G              | Notebook    | [1215219438](https://linux-hardware.org/?probe=1215219438) | Feb 24, 2020 |
| Gigabyte      | B360 M AORUS PRO-CF         | Desktop     | [8b8bf9eb3c](https://linux-hardware.org/?probe=8b8bf9eb3c) | Feb 05, 2020 |
| Acer          | Aspire V5-591G              | Notebook    | [a3dd0ecbb3](https://linux-hardware.org/?probe=a3dd0ecbb3) | Feb 04, 2020 |
| Acer          | Aspire V5-591G              | Notebook    | [06a759a4a5](https://linux-hardware.org/?probe=06a759a4a5) | Feb 04, 2020 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [ec012fce91](https://linux-hardware.org/?probe=ec012fce91) | Jan 30, 2020 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [871b431e0b](https://linux-hardware.org/?probe=871b431e0b) | Jan 23, 2020 |
| Gigabyte      | P55A-UD4                    | Desktop     | [0765c0e746](https://linux-hardware.org/?probe=0765c0e746) | Jan 23, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [553a1a04cd](https://linux-hardware.org/?probe=553a1a04cd) | Jan 21, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [c515f18bdf](https://linux-hardware.org/?probe=c515f18bdf) | Jan 21, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [1672f62e6a](https://linux-hardware.org/?probe=1672f62e6a) | Jan 18, 2020 |
| Acer          | Aspire one                  | Notebook    | [e5a2828fc4](https://linux-hardware.org/?probe=e5a2828fc4) | Jan 18, 2020 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [e1061f8758](https://linux-hardware.org/?probe=e1061f8758) | Jan 17, 2020 |
| Dell          | 0TP412                      | Desktop     | [92059b060a](https://linux-hardware.org/?probe=92059b060a) | Jan 15, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [4c444b85d5](https://linux-hardware.org/?probe=4c444b85d5) | Jan 11, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [161e031506](https://linux-hardware.org/?probe=161e031506) | Jan 11, 2020 |
| Acer          | Aspire one                  | Notebook    | [5e43adead0](https://linux-hardware.org/?probe=5e43adead0) | Jan 10, 2020 |
| NEC Comput... | Milo3-H                     | All in one  | [5c63f6a905](https://linux-hardware.org/?probe=5c63f6a905) | Jan 07, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [93e77f9dc3](https://linux-hardware.org/?probe=93e77f9dc3) | Dec 26, 2019 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [7cac7cc3cc](https://linux-hardware.org/?probe=7cac7cc3cc) | Dec 26, 2019 |
| Foxconn       | 2ADA                        | Desktop     | [61f3387aaa](https://linux-hardware.org/?probe=61f3387aaa) | Dec 19, 2019 |
| Acer          | M1930                       | Desktop     | [6f798ab348](https://linux-hardware.org/?probe=6f798ab348) | Dec 16, 2019 |
| HP            | ProBook 4310s               | Notebook    | [e835f92f9b](https://linux-hardware.org/?probe=e835f92f9b) | Dec 05, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e7a8d31ef](https://linux-hardware.org/?probe=3e7a8d31ef) | Dec 03, 2019 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9f10e816c5](https://linux-hardware.org/?probe=9f10e816c5) | Nov 21, 2019 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ad60feb203](https://linux-hardware.org/?probe=ad60feb203) | Nov 21, 2019 |
| Vizio         | CT14                        | Notebook    | [2959768de4](https://linux-hardware.org/?probe=2959768de4) | Oct 28, 2019 |
| MSI           | P45 Platinum                | Desktop     | [178de664ca](https://linux-hardware.org/?probe=178de664ca) | Oct 28, 2019 |
| Vizio         | CT14                        | Notebook    | [83072575a5](https://linux-hardware.org/?probe=83072575a5) | Oct 28, 2019 |
| Acer          | Makalu                      | Notebook    | [00dd5c3407](https://linux-hardware.org/?probe=00dd5c3407) | Oct 19, 2019 |
| Lenovo        | ThinkCentre M58 7627AA9     | Desktop     | [4ca1d19d3a](https://linux-hardware.org/?probe=4ca1d19d3a) | Oct 18, 2019 |
| Acer          | Aspire 4745G                | Notebook    | [1842d2a0dd](https://linux-hardware.org/?probe=1842d2a0dd) | Oct 17, 2019 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [8dd08d1a97](https://linux-hardware.org/?probe=8dd08d1a97) | Oct 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [0a39f948fd](https://linux-hardware.org/?probe=0a39f948fd) | Sep 29, 2019 |
| ASRock        | H81M-ITX                    | Desktop     | [ce10f2cbfe](https://linux-hardware.org/?probe=ce10f2cbfe) | Sep 26, 2019 |
| ASRock        | H81M-ITX                    | Desktop     | [aed359375a](https://linux-hardware.org/?probe=aed359375a) | Sep 26, 2019 |
| Unknown       | Unknown                     | Phone       | [ade7a886f0](https://linux-hardware.org/?probe=ade7a886f0) | Sep 24, 2019 |
| MSI           | X399 SLI PLUS               | Desktop     | [b281f9ca55](https://linux-hardware.org/?probe=b281f9ca55) | Sep 15, 2019 |
| MSI           | X399 SLI PLUS               | Desktop     | [130f51b891](https://linux-hardware.org/?probe=130f51b891) | Sep 11, 2019 |
| MSI           | X399 SLI PLUS               | Desktop     | [8da6642033](https://linux-hardware.org/?probe=8da6642033) | Sep 11, 2019 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [78cdbbd363](https://linux-hardware.org/?probe=78cdbbd363) | Sep 04, 2019 |
| Dell          | Inspiron 5437               | Notebook    | [3896fc1c82](https://linux-hardware.org/?probe=3896fc1c82) | Aug 18, 2019 |
| Lenovo        | ThinkPad T410 2537F34       | Notebook    | [25fa16d561](https://linux-hardware.org/?probe=25fa16d561) | Aug 17, 2019 |
| MiTAC         | Xeon D 411C41900030         | Server      | [06197ccb84](https://linux-hardware.org/?probe=06197ccb84) | Aug 16, 2019 |
| MSI           | GE70 2PE                    | Notebook    | [bba7f1b63c](https://linux-hardware.org/?probe=bba7f1b63c) | Aug 13, 2019 |
| MSI           | GE70 2PE                    | Notebook    | [1363b81c32](https://linux-hardware.org/?probe=1363b81c32) | Aug 11, 2019 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [a6a357de21](https://linux-hardware.org/?probe=a6a357de21) | Aug 08, 2019 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [f5c15b4975](https://linux-hardware.org/?probe=f5c15b4975) | Aug 01, 2019 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [517d2f4be4](https://linux-hardware.org/?probe=517d2f4be4) | Jul 31, 2019 |
| Gigabyte      | MZGLKCH-SI                  | Desktop     | [0f78f0b23e](https://linux-hardware.org/?probe=0f78f0b23e) | Jul 24, 2019 |
| Sony          | SVP13229PWB                 | Notebook    | [3aa37419af](https://linux-hardware.org/?probe=3aa37419af) | Jul 23, 2019 |
| Unknown       | Unknown                     | Desktop     | [55981af24a](https://linux-hardware.org/?probe=55981af24a) | Jul 17, 2019 |
| Unknown       | Unknown                     | Desktop     | [efe95ef406](https://linux-hardware.org/?probe=efe95ef406) | Jul 17, 2019 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [a11552d6ec](https://linux-hardware.org/?probe=a11552d6ec) | Jul 15, 2019 |
| Unknown       | Unknown                     | Desktop     | [e8900d6721](https://linux-hardware.org/?probe=e8900d6721) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [087f924e20](https://linux-hardware.org/?probe=087f924e20) | Jul 15, 2019 |
| Unknown       | Unknown                     | Desktop     | [e58e143a7f](https://linux-hardware.org/?probe=e58e143a7f) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [683b87be0f](https://linux-hardware.org/?probe=683b87be0f) | Jul 15, 2019 |
| Unknown       | Unknown                     | Notebook    | [13f65e01c3](https://linux-hardware.org/?probe=13f65e01c3) | Jul 15, 2019 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [43db5dc346](https://linux-hardware.org/?probe=43db5dc346) | Jul 15, 2019 |
| Unknown       | Unknown                     | Desktop     | [4124a2b6aa](https://linux-hardware.org/?probe=4124a2b6aa) | Jul 12, 2019 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [093c4071fd](https://linux-hardware.org/?probe=093c4071fd) | Jul 10, 2019 |
| Unknown       | Unknown                     | Notebook    | [7762bb952e](https://linux-hardware.org/?probe=7762bb952e) | Jul 09, 2019 |
| Unknown       | Unknown                     | Desktop     | [25b6099cd2](https://linux-hardware.org/?probe=25b6099cd2) | Jul 09, 2019 |
| Unknown       | Unknown                     | Desktop     | [c9ae4d965c](https://linux-hardware.org/?probe=c9ae4d965c) | Jul 09, 2019 |
| Unknown       | Unknown                     | Desktop     | [1e3ba128f6](https://linux-hardware.org/?probe=1e3ba128f6) | Jul 08, 2019 |
| Intel         | S1200BTL E98681-352         | Server      | [daa63a315c](https://linux-hardware.org/?probe=daa63a315c) | Jul 07, 2019 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [44650751a9](https://linux-hardware.org/?probe=44650751a9) | Jul 04, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [154fbbffd3](https://linux-hardware.org/?probe=154fbbffd3) | Jul 04, 2019 |
| NEXCOM        | B537-I                      | Notebook    | [ce97b8b28b](https://linux-hardware.org/?probe=ce97b8b28b) | Jun 27, 2019 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [7552a8cb4c](https://linux-hardware.org/?probe=7552a8cb4c) | Jun 20, 2019 |
| ASUSTek       | ASUSPRO B9440UAM            | Notebook    | [56aa80a6c4](https://linux-hardware.org/?probe=56aa80a6c4) | Jun 20, 2019 |
| ASUSTek       | N53Jl                       | Notebook    | [0df8ea73f2](https://linux-hardware.org/?probe=0df8ea73f2) | Jun 14, 2019 |
| ASUSTek       | N53Jl                       | Notebook    | [0e4db84a2e](https://linux-hardware.org/?probe=0e4db84a2e) | Jun 14, 2019 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [21fb8f59a4](https://linux-hardware.org/?probe=21fb8f59a4) | Jun 07, 2019 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [a210ba04d3](https://linux-hardware.org/?probe=a210ba04d3) | Jun 04, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [d2e0085e5f](https://linux-hardware.org/?probe=d2e0085e5f) | Jun 04, 2019 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [f96a5f5393](https://linux-hardware.org/?probe=f96a5f5393) | Jun 04, 2019 |
| Acer          | Aspire E5-553G              | Notebook    | [41e017c4ae](https://linux-hardware.org/?probe=41e017c4ae) | Jun 02, 2019 |
| Unknown       | Unknown                     | Server      | [4391dff8d2](https://linux-hardware.org/?probe=4391dff8d2) | May 28, 2019 |
| Unknown       | Unknown                     | Server      | [5b11f4c63c](https://linux-hardware.org/?probe=5b11f4c63c) | May 28, 2019 |
| Unknown       | Unknown                     | Server      | [1edcb7e6c2](https://linux-hardware.org/?probe=1edcb7e6c2) | May 28, 2019 |
| Unknown       | Unknown                     | Server      | [17de525522](https://linux-hardware.org/?probe=17de525522) | May 28, 2019 |
| Unknown       | Unknown                     | Server      | [6ee0d55160](https://linux-hardware.org/?probe=6ee0d55160) | May 28, 2019 |
| Unknown       | Unknown                     | Server      | [a47a28ccd5](https://linux-hardware.org/?probe=a47a28ccd5) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [33fd391144](https://linux-hardware.org/?probe=33fd391144) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [1d08524e85](https://linux-hardware.org/?probe=1d08524e85) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [daa1cc7f09](https://linux-hardware.org/?probe=daa1cc7f09) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [ba6b02c8ef](https://linux-hardware.org/?probe=ba6b02c8ef) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [a5c9b3c764](https://linux-hardware.org/?probe=a5c9b3c764) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [16220ef317](https://linux-hardware.org/?probe=16220ef317) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [003fec0a88](https://linux-hardware.org/?probe=003fec0a88) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [10cf68eb0e](https://linux-hardware.org/?probe=10cf68eb0e) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [076bcef32e](https://linux-hardware.org/?probe=076bcef32e) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [7466852d2e](https://linux-hardware.org/?probe=7466852d2e) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [1c7a26effc](https://linux-hardware.org/?probe=1c7a26effc) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [ae057b1a60](https://linux-hardware.org/?probe=ae057b1a60) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [f14d72c244](https://linux-hardware.org/?probe=f14d72c244) | May 27, 2019 |
| Unknown       | Unknown                     | Server      | [f256fc5b80](https://linux-hardware.org/?probe=f256fc5b80) | May 23, 2019 |
| ASUSTek       | WS X299 PRO                 | Desktop     | [510ae49df2](https://linux-hardware.org/?probe=510ae49df2) | May 22, 2019 |
| Acer          | Veriton M6620G v1.0         | Desktop     | [4f1a9afa27](https://linux-hardware.org/?probe=4f1a9afa27) | May 21, 2019 |
| Sony          | VPCCB15FW                   | Notebook    | [f1c5d4c3c4](https://linux-hardware.org/?probe=f1c5d4c3c4) | May 17, 2019 |
| Gigabyte      | Z170M-HERO-CF               | Desktop     | [0d7f7b5382](https://linux-hardware.org/?probe=0d7f7b5382) | Apr 28, 2019 |
| Acer          | Veriton M6620G v1.0         | Desktop     | [d5403368f6](https://linux-hardware.org/?probe=d5403368f6) | Apr 28, 2019 |
| Acer          | Veriton M6620G v1.0         | Desktop     | [1c42aae9b4](https://linux-hardware.org/?probe=1c42aae9b4) | Apr 27, 2019 |
| Gigabyte      | G41M-Combo                  | Desktop     | [f70f72098a](https://linux-hardware.org/?probe=f70f72098a) | Apr 21, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [4452107fd7](https://linux-hardware.org/?probe=4452107fd7) | Apr 14, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [2ab4402059](https://linux-hardware.org/?probe=2ab4402059) | Apr 13, 2019 |
| Dell          | Vostro 15-3568              | Notebook    | [417000b97b](https://linux-hardware.org/?probe=417000b97b) | Apr 13, 2019 |
| MSI           | Z68MA-G45                   | Desktop     | [c3e718dfec](https://linux-hardware.org/?probe=c3e718dfec) | Apr 09, 2019 |
| HP            | ProLiant ML150 Gen9         | Desktop     | [d9b1ec3c37](https://linux-hardware.org/?probe=d9b1ec3c37) | Apr 09, 2019 |
| HP            | ProLiant ML150 Gen9         | Desktop     | [d61584bf4e](https://linux-hardware.org/?probe=d61584bf4e) | Apr 09, 2019 |
| HP            | Pavilion dv4                | Notebook    | [8f256add2b](https://linux-hardware.org/?probe=8f256add2b) | Apr 08, 2019 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [7720ed3668](https://linux-hardware.org/?probe=7720ed3668) | Apr 08, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [925ee04320](https://linux-hardware.org/?probe=925ee04320) | Apr 07, 2019 |
| HP            | Compaq Presario CQ45        | Notebook    | [79588ac19b](https://linux-hardware.org/?probe=79588ac19b) | Apr 05, 2019 |
| ASUSTek       | BM1AF_BP1AF_BM6AF           | Desktop     | [dcf80c3fe6](https://linux-hardware.org/?probe=dcf80c3fe6) | Apr 03, 2019 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [d9a29354a7](https://linux-hardware.org/?probe=d9a29354a7) | Feb 19, 2019 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [a3a29982fd](https://linux-hardware.org/?probe=a3a29982fd) | Feb 19, 2019 |
| ASRock        | H310M-ITX/ac                | Desktop     | [0ae0ba17de](https://linux-hardware.org/?probe=0ae0ba17de) | Feb 02, 2019 |
| Gigabyte      | H87M-D3H                    | Desktop     | [dd3cc86ec3](https://linux-hardware.org/?probe=dd3cc86ec3) | Jan 29, 2019 |
| ASRock        | H310M-ITX/ac                | Desktop     | [899220711e](https://linux-hardware.org/?probe=899220711e) | Jan 25, 2019 |
| HP            | 8381 1000                   | All in one  | [8ed375662d](https://linux-hardware.org/?probe=8ed375662d) | Jan 23, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [660901d55e](https://linux-hardware.org/?probe=660901d55e) | Jan 23, 2019 |
| Dell          | Inspiron 5442               | Notebook    | [2a64f0ce54](https://linux-hardware.org/?probe=2a64f0ce54) | Jan 22, 2019 |
| Gigabyte      | H87M-D3H                    | Desktop     | [90a29cddfa](https://linux-hardware.org/?probe=90a29cddfa) | Dec 21, 2018 |
| ASUSTek       | X555LB                      | Notebook    | [87f78b7843](https://linux-hardware.org/?probe=87f78b7843) | Dec 18, 2018 |
| ASUSTek       | X555LB                      | Notebook    | [02891bd4ea](https://linux-hardware.org/?probe=02891bd4ea) | Dec 18, 2018 |
| ASUSTek       | X555LB                      | Notebook    | [314622e44e](https://linux-hardware.org/?probe=314622e44e) | Dec 17, 2018 |
| ASUSTek       | X555LB                      | Notebook    | [062f1d59ce](https://linux-hardware.org/?probe=062f1d59ce) | Dec 17, 2018 |
| Dell          | XPS 13 9380                 | Notebook    | [d809782cbd](https://linux-hardware.org/?probe=d809782cbd) | Dec 12, 2018 |
| ASRock        | H310M-STX/COM               | Desktop     | [d350550408](https://linux-hardware.org/?probe=d350550408) | Dec 07, 2018 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [3eaee61f5f](https://linux-hardware.org/?probe=3eaee61f5f) | Nov 29, 2018 |
| Gigabyte      | H310 D3                     | Desktop     | [eb95ee1f27](https://linux-hardware.org/?probe=eb95ee1f27) | Nov 20, 2018 |
| MSI           | FM2-A75MA-E35               | Desktop     | [d4730289c0](https://linux-hardware.org/?probe=d4730289c0) | Nov 12, 2018 |
| ASUSTek       | X510UQ                      | Notebook    | [5e508f8f1a](https://linux-hardware.org/?probe=5e508f8f1a) | Nov 09, 2018 |
| ASUSTek       | X510UQ                      | Notebook    | [5a5df173fb](https://linux-hardware.org/?probe=5a5df173fb) | Nov 09, 2018 |
| Acer          | Aspire 3820                 | Notebook    | [664332711f](https://linux-hardware.org/?probe=664332711f) | Nov 09, 2018 |
| Acer          | Aspire 3820                 | Notebook    | [7becdb1438](https://linux-hardware.org/?probe=7becdb1438) | Nov 09, 2018 |
| ASUSTek       | P8H67                       | Desktop     | [821e6f68ce](https://linux-hardware.org/?probe=821e6f68ce) | Sep 17, 2018 |
| Unknown       | Unknown                     | Server      | [f8d0599716](https://linux-hardware.org/?probe=f8d0599716) | Mar 09, 2018 |
| Unknown       | Unknown                     | Server      | [edf0dc6de6](https://linux-hardware.org/?probe=edf0dc6de6) | Mar 09, 2018 |
| Dell          | XPS 13 9360                 | Notebook    | [8a7077867f](https://linux-hardware.org/?probe=8a7077867f) | Mar 10, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Taiwan/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 18.04       | 92        | 15.75%  |
| Ubuntu 20.04       | 85        | 14.55%  |
| Ubuntu 22.04       | 36        | 6.16%   |
| Debian 11          | 22        | 3.77%   |
| Arch Rolling       | 22        | 3.77%   |
| OpenMandriva 4.2   | 14        | 2.4%    |
| Fedora 37          | 14        | 2.4%    |
| Pop!_OS 20.04      | 10        | 1.71%   |
| OpenMandriva 23.01 | 10        | 1.71%   |
| Linux Mint 20.3    | 9         | 1.54%   |
| OpenMandriva 4.3   | 8         | 1.37%   |
| Ubuntu 19.04       | 7         | 1.2%    |
| Ubuntu 22.10       | 6         | 1.03%   |
| Ubuntu 20.10       | 6         | 1.03%   |
| OpenMandriva 23.03 | 6         | 1.03%   |
| KDE neon 20.04     | 6         | 1.03%   |
| Fedora 38          | 6         | 1.03%   |
| Xubuntu 18.04      | 5         | 0.86%   |
| Ubuntu 21.04       | 5         | 0.86%   |
| Ubuntu 19.10       | 5         | 0.86%   |
| Ubuntu 16.04       | 5         | 0.86%   |
| Fedora 36          | 5         | 0.86%   |
| Zorin 16           | 4         | 0.68%   |
| Xubuntu 20.04      | 4         | 0.68%   |
| Ubuntu 21.10       | 4         | 0.68%   |
| Ubuntu 18.10       | 4         | 0.68%   |
| SteamOS 3.4.4      | 4         | 0.68%   |
| Manjaro            | 4         | 0.68%   |
| Linux Mint 20.1    | 4         | 0.68%   |
| Kubuntu 20.04      | 4         | 0.68%   |
| Fedora 34          | 4         | 0.68%   |
| Arch               | 4         | 0.68%   |
| Ubuntu MATE 20.04  | 3         | 0.51%   |
| Ubuntu 23.04       | 3         | 0.51%   |
| Pop!_OS 21.04      | 3         | 0.51%   |
| Manjaro 20.1       | 3         | 0.51%   |
| Linux Mint 21.1    | 3         | 0.51%   |
| Kali 2020.2        | 3         | 0.51%   |
| Fedora 35          | 3         | 0.51%   |
| Fedora 33          | 3         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 253       | 45.1%   |
| OpenMandriva     | 40        | 7.13%   |
| Fedora           | 37        | 6.6%    |
| Debian           | 30        | 5.35%   |
| Manjaro          | 29        | 5.17%   |
| Linux Mint       | 26        | 4.63%   |
| Arch             | 26        | 4.63%   |
| Pop!_OS          | 18        | 3.21%   |
| Xubuntu          | 15        | 2.67%   |
| Kubuntu          | 8         | 1.43%   |
| KDE neon         | 7         | 1.25%   |
| Gentoo           | 7         | 1.25%   |
| Endless          | 7         | 1.25%   |
| Zorin            | 6         | 1.07%   |
| Ubuntu MATE      | 6         | 1.07%   |
| Ubuntu Unity     | 4         | 0.71%   |
| SteamOS          | 4         | 0.71%   |
| openSUSE         | 4         | 0.71%   |
| Lubuntu          | 4         | 0.71%   |
| Kali             | 4         | 0.71%   |
| Clear Linux      | 3         | 0.53%   |
| CentOS           | 3         | 0.53%   |
| Ubuntu Studio    | 2         | 0.36%   |
| Ubuntu Budgie    | 2         | 0.36%   |
| ROSA             | 2         | 0.36%   |
| EndeavourOS      | 2         | 0.36%   |
| Rocky Linux      | 1         | 0.18%   |
| org.kde.Platform | 1         | 0.18%   |
| Nobara           | 1         | 0.18%   |
| NixOS            | 1         | 0.18%   |
| Mageia           | 1         | 0.18%   |
| Lilidog          | 1         | 0.18%   |
| Kylin            | 1         | 0.18%   |
| Garuda Linux     | 1         | 0.18%   |
| Elementary       | 1         | 0.18%   |
| BlackPanther     | 1         | 0.18%   |
| ArcoLinux        | 1         | 0.18%   |
| Android          | 1         | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.18.0-20-generic        | 18        | 2.88%   |
| 5.10.14-desktop-1omv4002 | 12        | 1.92%   |
| 6.1.1-desktop-1omv2290   | 10        | 1.6%    |
| 5.4.0-42-generic         | 8         | 1.28%   |
| 5.16.7-desktop-1omv4003  | 8         | 1.28%   |
| 5.11.0-27-generic        | 7         | 1.12%   |
| 6.2.6-desktop-1omv2390   | 5         | 0.8%    |
| 5.3.0-40-generic         | 5         | 0.8%    |
| 5.15.0-53-generic        | 5         | 0.8%    |
| 5.8.0-7630-generic       | 4         | 0.64%   |
| 5.8.0-59-generic         | 4         | 0.64%   |
| 5.8.0-50-generic         | 4         | 0.64%   |
| 5.8.0-43-generic         | 4         | 0.64%   |
| 5.4.0-58-generic         | 4         | 0.64%   |
| 5.4.0-52-generic         | 4         | 0.64%   |
| 5.4.0-48-generic         | 4         | 0.64%   |
| 5.4.0-45-generic         | 4         | 0.64%   |
| 5.4.0-28-generic         | 4         | 0.64%   |
| 5.3.0-46-generic         | 4         | 0.64%   |
| 5.19.0-46-generic        | 4         | 0.64%   |
| 5.19.0-38-generic        | 4         | 0.64%   |
| 5.15.0-58-generic        | 4         | 0.64%   |
| 5.13.0-valve36-1-neptune | 4         | 0.64%   |
| 5.13.0-30-generic        | 4         | 0.64%   |
| 5.11.0-43-generic        | 4         | 0.64%   |
| 5.11.0-25-generic        | 4         | 0.64%   |
| 5.0.0-37-generic         | 4         | 0.64%   |
| 5.0.0-23-generic         | 4         | 0.64%   |
| 4.15.0-43-generic        | 4         | 0.64%   |
| 6.0.12-300.fc37.x86_64   | 3         | 0.48%   |
| 5.8.0-53-generic         | 3         | 0.48%   |
| 5.4.0-84-generic         | 3         | 0.48%   |
| 5.4.0-7642-generic       | 3         | 0.48%   |
| 5.4.0-66-generic         | 3         | 0.48%   |
| 5.4.0-26-generic         | 3         | 0.48%   |
| 5.15.0-48-generic        | 3         | 0.48%   |
| 5.15.0-40-generic        | 3         | 0.48%   |
| 5.11.0-41-generic        | 3         | 0.48%   |
| 4.18.0-25-generic        | 3         | 0.48%   |
| 4.18.0-17-generic        | 3         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 84        | 14.02%  |
| 4.15.0  | 40        | 6.68%   |
| 5.15.0  | 38        | 6.34%   |
| 4.18.0  | 36        | 6.01%   |
| 5.8.0   | 35        | 5.84%   |
| 5.11.0  | 29        | 4.84%   |
| 5.13.0  | 25        | 4.17%   |
| 5.19.0  | 20        | 3.34%   |
| 5.0.0   | 18        | 3.01%   |
| 5.3.0   | 17        | 2.84%   |
| 5.10.0  | 17        | 2.84%   |
| 6.1.1   | 13        | 2.17%   |
| 5.10.14 | 12        | 2%      |
| 5.16.7  | 8         | 1.34%   |
| 6.2.6   | 7         | 1.17%   |
| 5.14.0  | 5         | 0.83%   |
| 6.2.0   | 4         | 0.67%   |
| 6.0.0   | 4         | 0.67%   |
| 6.2.9   | 3         | 0.5%    |
| 6.2.2   | 3         | 0.5%    |
| 6.0.12  | 3         | 0.5%    |
| 6.0.11  | 3         | 0.5%    |
| 5.16.18 | 3         | 0.5%    |
| 5.16.11 | 3         | 0.5%    |
| 6.3.5   | 2         | 0.33%   |
| 6.3.2   | 2         | 0.33%   |
| 6.2.12  | 2         | 0.33%   |
| 6.2.11  | 2         | 0.33%   |
| 6.1.9   | 2         | 0.33%   |
| 6.1.7   | 2         | 0.33%   |
| 6.1.31  | 2         | 0.33%   |
| 6.0.8   | 2         | 0.33%   |
| 6.0.2   | 2         | 0.33%   |
| 5.9.8   | 2         | 0.33%   |
| 5.8.18  | 2         | 0.33%   |
| 5.8.10  | 2         | 0.33%   |
| 5.7.1   | 2         | 0.33%   |
| 5.7.0   | 2         | 0.33%   |
| 5.5.0   | 2         | 0.33%   |
| 5.4.64  | 2         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 88        | 14.77%  |
| 5.15    | 60        | 10.07%  |
| 5.8     | 43        | 7.21%   |
| 4.15    | 40        | 6.71%   |
| 5.10    | 38        | 6.38%   |
| 4.18    | 37        | 6.21%   |
| 5.11    | 34        | 5.7%    |
| 5.13    | 30        | 5.03%   |
| 6.2     | 26        | 4.36%   |
| 6.1     | 25        | 4.19%   |
| 5.19    | 25        | 4.19%   |
| 5.0     | 21        | 3.52%   |
| 6.0     | 18        | 3.02%   |
| 5.3     | 17        | 2.85%   |
| 5.16    | 16        | 2.68%   |
| 5.7     | 10        | 1.68%   |
| 6.3     | 9         | 1.51%   |
| 5.14    | 8         | 1.34%   |
| 5.18    | 7         | 1.17%   |
| 5.17    | 5         | 0.84%   |
| 4.19    | 5         | 0.84%   |
| 5.9     | 4         | 0.67%   |
| 5.6     | 4         | 0.67%   |
| 5.5     | 4         | 0.67%   |
| 5.12    | 4         | 0.67%   |
| 4.9     | 3         | 0.5%    |
| 4.14    | 3         | 0.5%    |
| 4.4     | 2         | 0.34%   |
| 4.13    | 2         | 0.34%   |
| 4.12    | 2         | 0.34%   |
| 3.10    | 2         | 0.34%   |
| 6.4     | 1         | 0.17%   |
| 5.2     | 1         | 0.17%   |
| 5.1     | 1         | 0.17%   |
| 4.10    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 527       | 96.17%  |
| i686    | 10        | 1.82%   |
| aarch64 | 10        | 1.82%   |
| riscv64 | 1         | 0.18%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 257       | 45.49%  |
| Unknown          | 119       | 21.06%  |
| KDE5             | 86        | 15.22%  |
| XFCE             | 29        | 5.13%   |
| X-Cinnamon       | 14        | 2.48%   |
| MATE             | 13        | 2.3%    |
| KDE              | 9         | 1.59%   |
| Cinnamon         | 7         | 1.24%   |
| LXDE             | 5         | 0.88%   |
| Unity            | 4         | 0.71%   |
| LXQt             | 4         | 0.71%   |
| i3               | 3         | 0.53%   |
| Openbox          | 2         | 0.35%   |
| GNOME Flashback  | 2         | 0.35%   |
| Deepin           | 2         | 0.35%   |
| Budgie           | 2         | 0.35%   |
| sway             | 1         | 0.18%   |
| qtile            | 1         | 0.18%   |
| Pantheon         | 1         | 0.18%   |
| lightdm-xsession | 1         | 0.18%   |
| KDE4             | 1         | 0.18%   |
| Hyprland         | 1         | 0.18%   |
| GNOME Classic    | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 406       | 72.24%  |
| Wayland | 82        | 14.59%  |
| Unknown | 55        | 9.79%   |
| Tty     | 19        | 3.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 268       | 47.43%  |
| GDM     | 96        | 16.99%  |
| SDDM    | 82        | 14.51%  |
| GDM3    | 64        | 11.33%  |
| LightDM | 36        | 6.37%   |
| TDM     | 13        | 2.3%    |
| SLiM    | 3         | 0.53%   |
| KDM     | 2         | 0.35%   |
| LXDM    | 1         | 0.18%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 241       | 43.19%  |
| zh_TW   | 167       | 29.93%  |
| Unknown | 100       | 17.92%  |
| C       | 12        | 2.15%   |
| en_GB   | 7         | 1.25%   |
| zh_CN   | 6         | 1.08%   |
| ru_RU   | 3         | 0.54%   |
| lzh_TW  | 3         | 0.54%   |
| C.UTF8  | 3         | 0.54%   |
| zh_HK   | 2         | 0.36%   |
| en_SG   | 2         | 0.36%   |
| en_HK   | 2         | 0.36%   |
| de_DE   | 2         | 0.36%   |
| zh_SG   | 1         | 0.18%   |
| ja_JP   | 1         | 0.18%   |
| it_IT   | 1         | 0.18%   |
| es_ES   | 1         | 0.18%   |
| en_PH   | 1         | 0.18%   |
| en_IE   | 1         | 0.18%   |
| en_CA   | 1         | 0.18%   |
| en_AU   | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 318       | 57.19%  |
| BIOS | 238       | 42.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 426       | 76.9%   |
| Btrfs   | 50        | 9.03%   |
| Overlay | 34        | 6.14%   |
| Unknown | 14        | 2.53%   |
| Xfs     | 12        | 2.17%   |
| Tmpfs   | 9         | 1.62%   |
| Ext2    | 5         | 0.9%    |
| XXXXXXX | 1         | 0.18%   |
| Rootfs  | 1         | 0.18%   |
| F2fs    | 1         | 0.18%   |
| Ext3    | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 261       | 46.77%  |
| GPT     | 246       | 44.09%  |
| MBR     | 51        | 9.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 461       | 83.36%  |
| Yes       | 92        | 16.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 344       | 61.98%  |
| Yes       | 211       | 38.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 124       | 22.63%  |
| Gigabyte Technology     | 65        | 11.86%  |
| Acer                    | 59        | 10.77%  |
| Lenovo                  | 44        | 8.03%   |
| MSI                     | 41        | 7.48%   |
| Hewlett-Packard         | 41        | 7.48%   |
| Dell                    | 32        | 5.84%   |
| Unknown                 | 31        | 5.66%   |
| ASRock                  | 20        | 3.65%   |
| Intel                   | 11        | 2.01%   |
| Raspberry Pi Foundation | 6         | 1.09%   |
| Apple                   | 6         | 1.09%   |
| Valve                   | 4         | 0.73%   |
| Toshiba                 | 4         | 0.73%   |
| Supermicro              | 4         | 0.73%   |
| Sony                    | 4         | 0.73%   |
| Win element             | 2         | 0.36%   |
| Timi                    | 2         | 0.36%   |
| Nvidia                  | 2         | 0.36%   |
| NEXCOM                  | 2         | 0.36%   |
| Microsoft               | 2         | 0.36%   |
| LG Electronics          | 2         | 0.36%   |
| Lex                     | 2         | 0.36%   |
| Intel Client Systems    | 2         | 0.36%   |
| HUAWEI                  | 2         | 0.36%   |
| AVITA                   | 2         | 0.36%   |
| AMI                     | 2         | 0.36%   |
| AMD                     | 2         | 0.36%   |
| Vizio                   | 1         | 0.18%   |
| System76                | 1         | 0.18%   |
| Samsung Electronics     | 1         | 0.18%   |
| Ruckus Wireless         | 1         | 0.18%   |
| PANSHI                  | 1         | 0.18%   |
| OEM                     | 1         | 0.18%   |
| Neousys Technology      | 1         | 0.18%   |
| NEC Computers           | 1         | 0.18%   |
| MiTAC                   | 1         | 0.18%   |
| Maxtang                 | 1         | 0.18%   |
| Insyde                  | 1         | 0.18%   |
| IBM                     | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 33        | 6.02%   |
| ASUS All Series                    | 6         | 1.09%   |
| Valve Jupiter                      | 4         | 0.73%   |
| Gigabyte B75M-D3H                  | 4         | 0.73%   |
| Gigabyte B550I AORUS PRO AX        | 4         | 0.73%   |
| Lenovo ThinkCentre M58 7627AA9     | 3         | 0.55%   |
| Dell Inspiron 531s                 | 3         | 0.55%   |
| ASUS M5A78L-M/USB3                 | 3         | 0.55%   |
| ASRock X300M-STX                   | 3         | 0.55%   |
| Toshiba Satellite L850             | 2         | 0.36%   |
| Supermicro Super Server            | 2         | 0.36%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 2         | 0.36%   |
| RPi Raspberry Pi                   | 2         | 0.36%   |
| Nvidia Tegra                       | 2         | 0.36%   |
| MSI MS-7C52                        | 2         | 0.36%   |
| MSI MS-7A69                        | 2         | 0.36%   |
| MSI GS63 7RE                       | 2         | 0.36%   |
| Lex 3I610DW                        | 2         | 0.36%   |
| Lenovo IdeaPad 5 14ALC05 82LM      | 2         | 0.36%   |
| HP ProBook 430 G8 Notebook PC      | 2         | 0.36%   |
| HP Pavilion dv7                    | 2         | 0.36%   |
| Gigabyte Z97MX-Gaming 5            | 2         | 0.36%   |
| Gigabyte H81N                      | 2         | 0.36%   |
| Gigabyte G31M-ES2L                 | 2         | 0.36%   |
| Gigabyte B85M-D2V                  | 2         | 0.36%   |
| Dell XPS 13 9380                   | 2         | 0.36%   |
| AVITA NE14A2                       | 2         | 0.36%   |
| ASUS TUF Gaming B550M-PLUS         | 2         | 0.36%   |
| ASUS ROG STRIX B350-F GAMING       | 2         | 0.36%   |
| ASUS Pro WS X570-ACE               | 2         | 0.36%   |
| ASUS PRIME B660M-A WIFI D4         | 2         | 0.36%   |
| ASUS P8Z77-V LX                    | 2         | 0.36%   |
| ASUS CM6630_CM6730_CM6830          | 2         | 0.36%   |
| ASRock N68-GS4/USB3 FX             | 2         | 0.36%   |
| ASRock H310M-ITX/ac                | 2         | 0.36%   |
| ASRock A300M-STX                   | 2         | 0.36%   |
| ASRock 960GC-GS FX                 | 2         | 0.36%   |
| Acer Veriton L480                  | 2         | 0.36%   |
| Acer Swift SF514-52T               | 2         | 0.36%   |
| Acer Aspire V3-571G                | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 37        | 6.75%   |
| Unknown            | 33        | 6.02%   |
| Lenovo ThinkPad    | 23        | 4.2%    |
| ASUS ROG           | 18        | 3.28%   |
| Dell Inspiron      | 13        | 2.37%   |
| ASUS TUF           | 10        | 1.82%   |
| ASUS VivoBook      | 9         | 1.64%   |
| ASUS PRIME         | 9         | 1.64%   |
| Lenovo IdeaPad     | 8         | 1.46%   |
| HP ProBook         | 8         | 1.46%   |
| HP Pavilion        | 8         | 1.46%   |
| Acer Swift         | 7         | 1.28%   |
| RPi Raspberry      | 6         | 1.09%   |
| ASUS All           | 6         | 1.09%   |
| Dell Vostro        | 5         | 0.91%   |
| Dell Latitude      | 5         | 0.91%   |
| ASUS M5A78L-M      | 5         | 0.91%   |
| ASUS ASUSPRO       | 5         | 0.91%   |
| Acer Veriton       | 5         | 0.91%   |
| Valve Jupiter      | 4         | 0.73%   |
| Gigabyte B75M-D3H  | 4         | 0.73%   |
| Gigabyte B550I     | 4         | 0.73%   |
| ASUS ZenBook       | 4         | 0.73%   |
| Acer TravelMate    | 4         | 0.73%   |
| Toshiba Satellite  | 3         | 0.55%   |
| Lenovo ThinkCentre | 3         | 0.55%   |
| HP EliteBook       | 3         | 0.55%   |
| HP Compaq          | 3         | 0.55%   |
| Dell XPS           | 3         | 0.55%   |
| Dell Precision     | 3         | 0.55%   |
| ASUS Pro           | 3         | 0.55%   |
| ASUS P8Z77-V       | 3         | 0.55%   |
| ASRock X300M-STX   | 3         | 0.55%   |
| Supermicro Super   | 2         | 0.36%   |
| Nvidia Tegra       | 2         | 0.36%   |
| MSI MS-7C52        | 2         | 0.36%   |
| MSI MS-7A69        | 2         | 0.36%   |
| MSI Modern         | 2         | 0.36%   |
| MSI GS63           | 2         | 0.36%   |
| MSI GE70           | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 57        | 10.4%   |
| 2021    | 55        | 10.04%  |
| 2019    | 53        | 9.67%   |
| 2018    | 53        | 9.67%   |
| 2012    | 40        | 7.3%    |
| 2022    | 39        | 7.12%   |
| 2014    | 36        | 6.57%   |
| 2011    | 33        | 6.02%   |
| 2017    | 31        | 5.66%   |
| 2013    | 28        | 5.11%   |
| 2016    | 27        | 4.93%   |
| 2015    | 22        | 4.01%   |
| 2009    | 19        | 3.47%   |
| 2010    | 17        | 3.1%    |
| 2008    | 15        | 2.74%   |
| Unknown | 10        | 1.82%   |
| 2007    | 6         | 1.09%   |
| 2023    | 5         | 0.91%   |
| 2006    | 1         | 0.18%   |
| 2004    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 244       | 44.53%  |
| Notebook       | 236       | 43.07%  |
| Server         | 27        | 4.93%   |
| System on chip | 10        | 1.82%   |
| Mini pc        | 10        | 1.82%   |
| All in one     | 9         | 1.64%   |
| Convertible    | 8         | 1.46%   |
| Tablet         | 3         | 0.55%   |
| Phone          | 1         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 515       | 93.3%   |
| Enabled  | 37        | 6.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 546       | 99.64%  |
| Yes  | 2         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 144       | 25.95%  |
| 4.01-8.0        | 114       | 20.54%  |
| 8.01-16.0       | 93        | 16.76%  |
| 3.01-4.0        | 77        | 13.87%  |
| 32.01-64.0      | 71        | 12.79%  |
| 64.01-256.0     | 25        | 4.5%    |
| 24.01-32.0      | 14        | 2.52%   |
| 1.01-2.0        | 12        | 2.16%   |
| More than 256.0 | 2         | 0.36%   |
| 2.01-3.0        | 2         | 0.36%   |
| 0.51-1.0        | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 204       | 34.4%   |
| 2.01-3.0   | 149       | 25.13%  |
| 4.01-8.0   | 94        | 15.85%  |
| 3.01-4.0   | 83        | 14%     |
| 8.01-16.0  | 29        | 4.89%   |
| 0.51-1.0   | 19        | 3.2%    |
| 0.01-0.5   | 6         | 1.01%   |
| 24.01-32.0 | 5         | 0.84%   |
| 32.01-64.0 | 2         | 0.34%   |
| 16.01-24.0 | 2         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 284       | 50.9%   |
| 2       | 163       | 29.21%  |
| 3       | 55        | 9.86%   |
| 0       | 21        | 3.76%   |
| 4       | 18        | 3.23%   |
| 5       | 9         | 1.61%   |
| 6       | 4         | 0.72%   |
| 7       | 2         | 0.36%   |
| 14      | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 387       | 70.36%  |
| Yes       | 163       | 29.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 474       | 86.18%  |
| No        | 76        | 13.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 366       | 66.67%  |
| No        | 183       | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 326       | 58.84%  |
| No        | 228       | 41.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Taiwan  | 548       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Taipei            | 162       | 27.98%  |
| New Taipei        | 104       | 17.96%  |
| Taoyuan District  | 64        | 11.05%  |
| Taichung          | 44        | 7.6%    |
| Hsinchu           | 41        | 7.08%   |
| Kaohsiung City    | 36        | 6.22%   |
| Tainan City       | 26        | 4.49%   |
| Hsinchu County    | 16        | 2.76%   |
| Chang-hua         | 9         | 1.55%   |
| Keelung           | 6         | 1.04%   |
| Zhudong           | 5         | 0.86%   |
| Pingtung City     | 5         | 0.86%   |
| Zhongli District  | 4         | 0.69%   |
| Yunlin            | 4         | 0.69%   |
| Nantou City       | 4         | 0.69%   |
| Miaoli            | 4         | 0.69%   |
| Yilan             | 3         | 0.52%   |
| Taoyuan City      | 3         | 0.52%   |
| Yangmei District  | 2         | 0.35%   |
| Taichung City     | 2         | 0.35%   |
| Shulin District   | 2         | 0.35%   |
| Kanzijiao         | 2         | 0.35%   |
| Chiayi City       | 2         | 0.35%   |
| Chiayi            | 2         | 0.35%   |
| Banqiao           | 2         | 0.35%   |
| Baitang           | 2         | 0.35%   |
| Zhubei            | 1         | 0.17%   |
| Xinzhuang         | 1         | 0.17%   |
| Xindian           | 1         | 0.17%   |
| Xiawanzi          | 1         | 0.17%   |
| Xiatayou          | 1         | 0.17%   |
| Tuniugou          | 1         | 0.17%   |
| Taishan           | 1         | 0.17%   |
| Sanchong District | 1         | 0.17%   |
| Penghu County     | 1         | 0.17%   |
| Neihu             | 1         | 0.17%   |
| Minxiong          | 1         | 0.17%   |
| Magong            | 1         | 0.17%   |
| Jian              | 1         | 0.17%   |
| Hualien City      | 1         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 107       | 154    | 12.71%  |
| Seagate                     | 100       | 157    | 11.88%  |
| Toshiba                     | 62        | 78     | 7.36%   |
| Crucial                     | 55        | 70     | 6.53%   |
| Samsung Electronics         | 51        | 66     | 6.06%   |
| Unknown                     | 39        | 45     | 4.63%   |
| Intel                       | 39        | 56     | 4.63%   |
| SanDisk                     | 38        | 53     | 4.51%   |
| Kingston                    | 37        | 48     | 4.39%   |
| Hitachi                     | 31        | 38     | 3.68%   |
| A-DATA Technology           | 26        | 30     | 3.09%   |
| SK hynix                    | 21        | 26     | 2.49%   |
| HGST                        | 21        | 23     | 2.49%   |
| Micron Technology           | 17        | 18     | 2.02%   |
| Transcend                   | 15        | 16     | 1.78%   |
| Micron/Crucial Technology   | 10        | 13     | 1.19%   |
| Lite-On                     | 10        | 10     | 1.19%   |
| KIOXIA                      | 9         | 11     | 1.07%   |
| Apacer                      | 9         | 11     | 1.07%   |
| Plextor                     | 8         | 9      | 0.95%   |
| Unknown                     | 8         | 8      | 0.95%   |
| Phison Electronics          | 7         | 10     | 0.83%   |
| ASMT                        | 7         | 7      | 0.83%   |
| SPCC                        | 5         | 6      | 0.59%   |
| Silicon Motion              | 5         | 5      | 0.59%   |
| Phison                      | 5         | 6      | 0.59%   |
| Patriot                     | 5         | 5      | 0.59%   |
| ANACOMDA                    | 5         | 5      | 0.59%   |
| AGI                         | 5         | 6      | 0.59%   |
| XPG                         | 4         | 4      | 0.48%   |
| Team                        | 4         | 5      | 0.48%   |
| PNY                         | 3         | 3      | 0.36%   |
| OCZ                         | 3         | 3      | 0.36%   |
| Maxtor                      | 3         | 3      | 0.36%   |
| LITEONIT                    | 3         | 3      | 0.36%   |
| Kingston Technology Company | 3         | 4      | 0.36%   |
| JMicron Technology          | 3         | 7      | 0.36%   |
| China                       | 3         | 3      | 0.36%   |
| ADATA Technology            | 3         | 3      | 0.36%   |
| ZHITAI                      | 2         | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB            | 18        | 1.99%   |
| Toshiba DT01ACA100 1TB                  | 14        | 1.55%   |
| Crucial CT1000MX500SSD1 1TB             | 14        | 1.55%   |
| Toshiba DT01ACA200 2TB                  | 10        | 1.11%   |
| Seagate ST2000DM008-2FR102 2TB          | 10        | 1.11%   |
| Lite-On NVMe SSD Drive 512GB            | 8         | 0.88%   |
| HGST HTS721010A9E630 1TB                | 8         | 0.88%   |
| Unknown                                 | 8         | 0.88%   |
| Unknown MMC Card  64GB                  | 6         | 0.66%   |
| Toshiba MQ01ABD100 1TB                  | 6         | 0.66%   |
| Seagate ST3500418AS 500GB               | 6         | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB          | 6         | 0.66%   |
| Unknown MMC Card  32GB                  | 5         | 0.55%   |
| Toshiba MQ01ABD032 320GB                | 5         | 0.55%   |
| Seagate ST500DM002-1BD142 500GB         | 5         | 0.55%   |
| SanDisk NVMe SSD Drive 1TB              | 5         | 0.55%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB     | 5         | 0.55%   |
| Crucial CT240BX500SSD1 240GB            | 5         | 0.55%   |
| A-DATA SU800 512GB SSD                  | 5         | 0.55%   |
| WDC WDS250G1B0B-00AS40 250GB SSD        | 4         | 0.44%   |
| WDC WD10EZEX-75WN4A1 1TB                | 4         | 0.44%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 0.44%   |
| Silicon Motion NVMe SSD Drive 512GB     | 4         | 0.44%   |
| Seagate ST2000DM001-1CH164 2TB          | 4         | 0.44%   |
| Seagate ST1000LM049-2GH172 1TB          | 4         | 0.44%   |
| Seagate ST1000DM003-1ER162 1TB          | 4         | 0.44%   |
| SanDisk NVMe SSD Drive 512GB            | 4         | 0.44%   |
| SanDisk NVMe SSD Drive 500GB            | 4         | 0.44%   |
| SanDisk NVMe SSD Drive 256GB            | 4         | 0.44%   |
| Phison PS5013 E13 NVMe Controller 256GB | 4         | 0.44%   |
| Patriot Burst 120GB SSD                 | 4         | 0.44%   |
| Kingston SA400S37480G 480GB SSD         | 4         | 0.44%   |
| Kingston SA400S37240G 240GB SSD         | 4         | 0.44%   |
| Kingston SA2000M8500G 500GB             | 4         | 0.44%   |
| HGST HTS541010A9E680 1TB                | 4         | 0.44%   |
| ASMT 2115 64GB                          | 4         | 0.44%   |
| A-DATA SU800 256GB SSD                  | 4         | 0.44%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 3         | 0.33%   |
| WDC WDS250G2B0A-00SM50 250GB SSD        | 3         | 0.33%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 3         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 99        | 153    | 33.79%  |
| WDC                 | 68        | 98     | 23.21%  |
| Toshiba             | 53        | 69     | 18.09%  |
| Hitachi             | 31        | 38     | 10.58%  |
| HGST                | 21        | 23     | 7.17%   |
| ASMT                | 5         | 5      | 1.71%   |
| Unknown             | 4         | 5      | 1.37%   |
| Maxtor              | 3         | 3      | 1.02%   |
| JMicron Technology  | 2         | 6      | 0.68%   |
| StoreJet            | 1         | 2      | 0.34%   |
| Samsung Electronics | 1         | 2      | 0.34%   |
| NETAPP              | 1         | 2      | 0.34%   |
| NeoTech             | 1         | 1      | 0.34%   |
| Fujitsu             | 1         | 2      | 0.34%   |
| External            | 1         | 1      | 0.34%   |
| Apple               | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 52        | 65     | 19.4%   |
| A-DATA Technology   | 23        | 26     | 8.58%   |
| Kingston            | 20        | 23     | 7.46%   |
| Intel               | 19        | 27     | 7.09%   |
| WDC                 | 17        | 24     | 6.34%   |
| Transcend           | 15        | 16     | 5.6%    |
| SanDisk             | 15        | 18     | 5.6%    |
| Samsung Electronics | 13        | 15     | 4.85%   |
| Micron Technology   | 8         | 9      | 2.99%   |
| Toshiba             | 7         | 7      | 2.61%   |
| Plextor             | 7         | 8      | 2.61%   |
| Apacer              | 7         | 9      | 2.61%   |
| SPCC                | 5         | 6      | 1.87%   |
| Patriot             | 5         | 5      | 1.87%   |
| ANACOMDA            | 5         | 5      | 1.87%   |
| Team                | 3         | 4      | 1.12%   |
| SK hynix            | 3         | 3      | 1.12%   |
| OCZ                 | 3         | 3      | 1.12%   |
| LITEONIT            | 3         | 3      | 1.12%   |
| China               | 3         | 3      | 1.12%   |
| AGI                 | 3         | 4      | 1.12%   |
| Unknown             | 3         | 3      | 1.12%   |
| Leven               | 2         | 2      | 0.75%   |
| KLEVV               | 2         | 2      | 0.75%   |
| Gigastone           | 2         | 2      | 0.75%   |
| ASMT                | 2         | 2      | 0.75%   |
| ZHITAI              | 1         | 1      | 0.37%   |
| Wintec              | 1         | 1      | 0.37%   |
| Unknown             | 1         | 1      | 0.37%   |
| TO Exter            | 1         | 1      | 0.37%   |
| Sony                | 1         | 1      | 0.37%   |
| OCZ-VECT            | 1         | 1      | 0.37%   |
| OCZ-REVODRIVE       | 1         | 4      | 0.37%   |
| MyDigitalSSD        | 1         | 1      | 0.37%   |
| MX                  | 1         | 1      | 0.37%   |
| MemoCom             | 1         | 2      | 0.37%   |
| LITEON              | 1         | 1      | 0.37%   |
| Kingchuxing         | 1         | 1      | 0.37%   |
| Hewlett-Packard     | 1         | 1      | 0.37%   |
| Fujitsu             | 1         | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 247       | 411    | 33.61%  |
| SSD     | 231       | 320    | 31.43%  |
| NVMe    | 213       | 309    | 28.98%  |
| MMC     | 30        | 33     | 4.08%   |
| Unknown | 14        | 17     | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 383       | 693    | 58.12%  |
| NVMe | 212       | 308    | 32.17%  |
| SAS  | 34        | 56     | 5.16%   |
| MMC  | 30        | 33     | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 260       | 390    | 51.38%  |
| 0.51-1.0   | 163       | 214    | 32.21%  |
| 1.01-2.0   | 50        | 75     | 9.88%   |
| 3.01-4.0   | 11        | 15     | 2.17%   |
| 4.01-10.0  | 10        | 23     | 1.98%   |
| 2.01-3.0   | 9         | 11     | 1.78%   |
| 10.01-20.0 | 3         | 3      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 136       | 23.73%  |
| 101-250        | 135       | 23.56%  |
| 501-1000       | 70        | 12.22%  |
| 1001-2000      | 51        | 8.9%    |
| 1-20           | 42        | 7.33%   |
| 51-100         | 37        | 6.46%   |
| 21-50          | 32        | 5.58%   |
| 2001-3000      | 27        | 4.71%   |
| More than 3000 | 22        | 3.84%   |
| Unknown        | 21        | 3.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 241       | 40.92%  |
| 21-50          | 83        | 14.09%  |
| 101-250        | 72        | 12.22%  |
| 51-100         | 68        | 11.54%  |
| 251-500        | 47        | 7.98%   |
| 501-1000       | 27        | 4.58%   |
| Unknown        | 21        | 3.57%   |
| 1001-2000      | 17        | 2.89%   |
| More than 3000 | 7         | 1.19%   |
| 2001-3000      | 6         | 1.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Intel SSDPEKKW256G7 256GB                      | 2         | 3      | 5.41%   |
| WDC WD5000AAKX-60U6AA0 500GB                   | 1         | 1      | 2.7%    |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 2.7%    |
| WDC WD5000AADS-00L4B1 500GB                    | 1         | 1      | 2.7%    |
| WDC WD3200AAKS-00L9A0 320GB                    | 1         | 1      | 2.7%    |
| WDC WD20EARX-00PASB0 2TB                       | 1         | 1      | 2.7%    |
| WDC WD20EARS-00MVWB0 2TB                       | 1         | 1      | 2.7%    |
| WDC WD10EFRX-68JCSN0 1TB                       | 1         | 1      | 2.7%    |
| WDC WD10EALS-00Z8A0 1TB                        | 1         | 1      | 2.7%    |
| WDC WD1002FAEX-00Z3A0 1TB                      | 1         | 1      | 2.7%    |
| Transcend TS64GSSD340 64GB                     | 1         | 1      | 2.7%    |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 2.7%    |
| SK hynix HFS128G39MNC-2300A 128GB SSD          | 1         | 1      | 2.7%    |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 2.7%    |
| Seagate ST500LM000-1EJ162 500GB                | 1         | 1      | 2.7%    |
| Seagate ST4000DX001-1CE168 4TB                 | 1         | 2      | 2.7%    |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 2.7%    |
| Seagate ST3500410SV 500GB                      | 1         | 1      | 2.7%    |
| Seagate ST3160811AS 160GB                      | 1         | 1      | 2.7%    |
| Seagate ST2000VN000-1H3164 2TB                 | 1         | 2      | 2.7%    |
| Samsung Electronics HM321HI 320GB              | 1         | 2      | 2.7%    |
| Plextor PX-128M6Pro 128GB SSD                  | 1         | 1      | 2.7%    |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 2.7%    |
| LITEONIT E200-080 80GB SSD                     | 1         | 1      | 2.7%    |
| KLEVV SSD NEO N500 240GB                       | 1         | 1      | 2.7%    |
| Kingston SV300S37A60G 64GB SSD                 | 1         | 1      | 2.7%    |
| Intel SSDSC2BW080A4 80GB                       | 1         | 1      | 2.7%    |
| Intel SSDSC2BB016T7 2TB                        | 1         | 1      | 2.7%    |
| Hitachi HTS722080K9SA00 80GB                   | 1         | 1      | 2.7%    |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 2.7%    |
| Hitachi HDT721010SLA360 1TB                    | 1         | 1      | 2.7%    |
| Hitachi HDS723020BLA642 2TB                    | 1         | 2      | 2.7%    |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 2.7%    |
| Crucial CT275MX300SSD4 275GB                   | 1         | 1      | 2.7%    |
| ASMT 2115 64GB                                 | 1         | 1      | 2.7%    |
| A-DATA Technology IMSS332-960GB SSD            | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 24.32%  |
| Seagate             | 7         | 9      | 18.92%  |
| Intel               | 4         | 5      | 10.81%  |
| Hitachi             | 4         | 5      | 10.81%  |
| SK hynix            | 2         | 2      | 5.41%   |
| Transcend           | 1         | 1      | 2.7%    |
| Samsung Electronics | 1         | 2      | 2.7%    |
| Plextor             | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| LITEONIT            | 1         | 1      | 2.7%    |
| KLEVV               | 1         | 1      | 2.7%    |
| Kingston            | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Crucial             | 1         | 1      | 2.7%    |
| ASMT                | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 39.13%  |
| Seagate             | 7         | 9      | 30.43%  |
| Hitachi             | 4         | 5      | 17.39%  |
| Samsung Electronics | 1         | 2      | 4.35%   |
| HGST                | 1         | 1      | 4.35%   |
| ASMT                | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 27     | 60%     |
| SSD  | 11        | 11     | 31.43%  |
| NVMe | 3         | 4      | 8.57%   |

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
| Detected | 308       | 626    | 53.01%  |
| Works    | 238       | 422    | 40.96%  |
| Malfunc  | 35        | 42     | 6.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 361       | 50%     |
| AMD                            | 92        | 12.74%  |
| Samsung Electronics            | 52        | 7.2%    |
| SanDisk                        | 44        | 6.09%   |
| SK hynix                       | 18        | 2.49%   |
| Kingston Technology Company    | 18        | 2.49%   |
| Phison Electronics             | 17        | 2.35%   |
| ASMedia Technology             | 15        | 2.08%   |
| Micron/Crucial Technology      | 14        | 1.94%   |
| Nvidia                         | 10        | 1.39%   |
| Micron Technology              | 10        | 1.39%   |
| Lite-On Technology             | 10        | 1.39%   |
| ADATA Technology               | 9         | 1.25%   |
| Marvell Technology Group       | 7         | 0.97%   |
| KIOXIA                         | 7         | 0.97%   |
| Silicon Motion                 | 6         | 0.83%   |
| Toshiba America Info Systems   | 5         | 0.69%   |
| Yangtze Memory Technologies    | 3         | 0.42%   |
| Solid State Storage Technology | 3         | 0.42%   |
| Realtek Semiconductor          | 3         | 0.42%   |
| LSI Logic / Symbios Logic      | 3         | 0.42%   |
| JMicron Technology             | 3         | 0.42%   |
| Solidigm                       | 2         | 0.28%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.28%   |
| Broadcom / LSI                 | 2         | 0.28%   |
| Union Memory (Shenzhen)        | 1         | 0.14%   |
| Silicon Image                  | 1         | 0.14%   |
| Seagate Technology             | 1         | 0.14%   |
| Integrated Technology Express  | 1         | 0.14%   |
| INNOGRIT                       | 1         | 0.14%   |
| Innodisk                       | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 64        | 7.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 29        | 3.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 27        | 3.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 26        | 3.14%   |
| Intel Volume Management Device NVMe RAID Controller                            | 20        | 2.42%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 17        | 2.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 1.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 15        | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 14        | 1.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 13        | 1.57%   |
| AMD 500 Series Chipset SATA Controller                                         | 13        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 11        | 1.33%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 10        | 1.21%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 10        | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 1.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 1.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10        | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 10        | 1.21%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 9         | 1.09%   |
| Samsung NVMe SSD Controller 980                                                | 9         | 1.09%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 9         | 1.09%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 9         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 9         | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 0.97%   |
| Kingston Company A2000 NVMe SSD                                                | 8         | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 8         | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 8         | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 8         | 0.97%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 0.97%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 8         | 0.97%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 7         | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 0.85%   |
| Phison PS5013 E13 NVMe Controller                                              | 7         | 0.85%   |
| Lite-On Non-Volatile memory controller                                         | 7         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 7         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 388       | 53.67%  |
| NVMe | 223       | 30.84%  |
| IDE  | 65        | 8.99%   |
| RAID | 42        | 5.81%   |
| SAS  | 3         | 0.41%   |
| SCSI | 2         | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 413       | 75.36%  |
| AMD           | 124       | 22.63%  |
| ARM           | 8         | 1.46%   |
| sifive,u74-mc | 1         | 0.18%   |
| QUALCOMM      | 1         | 0.18%   |
| Unknown       | 1         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Xeon Gold 6248 CPU @ 2.50GHz      | 16        | 2.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 1.64%   |
| ARM Processor                           | 8         | 1.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 1.09%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 6         | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 5         | 0.91%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 0.91%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 5         | 0.91%   |
| Intel Core i3-4160 CPU @ 3.60GHz        | 5         | 0.91%   |
| Intel 12th Gen Core i5-12500H           | 5         | 0.91%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 5         | 0.91%   |
| AMD Ryzen 5 3600 6-Core Processor       | 5         | 0.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 0.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 0.73%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 4         | 0.73%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 4         | 0.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 0.73%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 4         | 0.73%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 4         | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 0.73%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 4         | 0.73%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 4         | 0.73%   |
| AMD Custom APU 0405                     | 4         | 0.73%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz     | 3         | 0.55%   |
| Intel Pentium CPU G840 @ 2.80GHz        | 3         | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 0.55%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 3         | 0.55%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 3         | 0.55%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 3         | 0.55%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 3         | 0.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 0.55%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 0.55%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz    | 3         | 0.55%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 3         | 0.55%   |
| Intel Celeron J4105 CPU @ 1.50GHz       | 3         | 0.55%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 3         | 0.55%   |
| AMD Ryzen 7 5800U with Radeon Graphics  | 3         | 0.55%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 0.55%   |
| AMD Ryzen 7 4800HS with Radeon Graphics | 3         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 110       | 20%     |
| Intel Core i7           | 93        | 16.91%  |
| Other                   | 61        | 11.09%  |
| Intel Core i3           | 42        | 7.64%   |
| AMD Ryzen 7             | 33        | 6%      |
| AMD Ryzen 5             | 29        | 5.27%   |
| Intel Xeon              | 22        | 4%      |
| Intel Celeron           | 22        | 4%      |
| Intel Xeon Gold         | 16        | 2.91%   |
| Intel Pentium           | 14        | 2.55%   |
| Intel Core 2 Duo        | 12        | 2.18%   |
| AMD Ryzen 9             | 12        | 2.18%   |
| Intel Core 2 Quad       | 9         | 1.64%   |
| AMD FX                  | 8         | 1.45%   |
| Intel Genuine           | 6         | 1.09%   |
| Intel Atom              | 6         | 1.09%   |
| AMD Ryzen 7 PRO         | 5         | 0.91%   |
| Intel Pentium Gold      | 4         | 0.73%   |
| AMD Ryzen 3             | 4         | 0.73%   |
| AMD Athlon 64 X2        | 4         | 0.73%   |
| Intel Core i9           | 3         | 0.55%   |
| AMD Ryzen 5 PRO         | 3         | 0.55%   |
| Intel Pentium Silver    | 2         | 0.36%   |
| Intel Pentium Dual-Core | 2         | 0.36%   |
| AMD Ryzen Threadripper  | 2         | 0.36%   |
| AMD Phenom II X4        | 2         | 0.36%   |
| AMD E2                  | 2         | 0.36%   |
| AMD Athlon II X4        | 2         | 0.36%   |
| AMD Athlon II X2        | 2         | 0.36%   |
| AMD A8                  | 2         | 0.36%   |
| QUALCOMM AArch64        | 1         | 0.18%   |
| Intel Xeon Silver       | 1         | 0.18%   |
| Intel Xeon Platinum     | 1         | 0.18%   |
| Intel Pentium M         | 1         | 0.18%   |
| Intel Pentium Dual      | 1         | 0.18%   |
| Intel Core m7           | 1         | 0.18%   |
| Intel Core 2 Solo       | 1         | 0.18%   |
| AMD Sempron             | 1         | 0.18%   |
| AMD Phenom II X6        | 1         | 0.18%   |
| AMD Phenom II X2        | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 213       | 38.8%   |
| 2       | 158       | 28.78%  |
| 8       | 58        | 10.56%  |
| 6       | 52        | 9.47%   |
| 12      | 19        | 3.46%   |
| 20      | 16        | 2.91%   |
| 16      | 8         | 1.46%   |
| 1       | 5         | 0.91%   |
| 10      | 4         | 0.73%   |
| 28      | 3         | 0.55%   |
| Unknown | 3         | 0.55%   |
| 24      | 2         | 0.36%   |
| 3       | 2         | 0.36%   |
| 192     | 1         | 0.18%   |
| 64      | 1         | 0.18%   |
| 48      | 1         | 0.18%   |
| 44      | 1         | 0.18%   |
| 18      | 1         | 0.18%   |
| 14      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 536       | 97.81%  |
| 2       | 7         | 1.28%   |
| Unknown | 3         | 0.55%   |
| 4       | 1         | 0.18%   |
| 3       | 1         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 379       | 68.91%  |
| 1       | 168       | 30.55%  |
| Unknown | 3         | 0.55%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 534       | 97.27%  |
| Unknown        | 13        | 2.37%   |
| 32-bit         | 2         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 136       | 23.99%  |
| 0x306c3    | 29        | 5.11%   |
| 0x306a9    | 29        | 5.11%   |
| 0x206a7    | 28        | 4.94%   |
| 0x50657    | 17        | 3%      |
| 0x906ea    | 14        | 2.47%   |
| 0x506e3    | 14        | 2.47%   |
| 0x806c1    | 13        | 2.29%   |
| 0x806ea    | 11        | 1.94%   |
| 0x40651    | 11        | 1.94%   |
| 0x1067a    | 11        | 1.94%   |
| 0x0a50000c | 11        | 1.94%   |
| 0x806e9    | 10        | 1.76%   |
| 0x806eb    | 9         | 1.59%   |
| 0x08701021 | 9         | 1.59%   |
| 0x906e9    | 8         | 1.41%   |
| 0x406e3    | 8         | 1.41%   |
| 0x306d4    | 8         | 1.41%   |
| 0x20655    | 8         | 1.41%   |
| 0x906eb    | 7         | 1.23%   |
| 0x08600106 | 7         | 1.23%   |
| 0x806ec    | 6         | 1.06%   |
| 0x706e5    | 6         | 1.06%   |
| 0x10676    | 6         | 1.06%   |
| 0x906a3    | 5         | 0.88%   |
| 0x706a1    | 5         | 0.88%   |
| 0x08608103 | 5         | 0.88%   |
| 0x906ed    | 4         | 0.71%   |
| 0x906a4    | 4         | 0.71%   |
| 0x90672    | 4         | 0.71%   |
| 0x06000852 | 4         | 0.71%   |
| 0xa0655    | 3         | 0.53%   |
| 0xa0653    | 3         | 0.53%   |
| 0x706a8    | 3         | 0.53%   |
| 0x6fd      | 3         | 0.53%   |
| 0x406c4    | 3         | 0.53%   |
| 0x106e5    | 3         | 0.53%   |
| 0x0a50000d | 3         | 0.53%   |
| 0x0810100b | 3         | 0.53%   |
| 0x08001138 | 3         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 89        | 16.21%  |
| Haswell          | 53        | 9.65%   |
| Skylake          | 50        | 9.11%   |
| Unknown          | 43        | 7.83%   |
| SandyBridge      | 36        | 6.56%   |
| IvyBridge        | 36        | 6.56%   |
| Zen 2            | 29        | 5.28%   |
| Zen 3            | 27        | 4.92%   |
| Penryn           | 23        | 4.19%   |
| Westmere         | 15        | 2.73%   |
| TigerLake        | 15        | 2.73%   |
| Alderlake Hybrid | 15        | 2.73%   |
| Broadwell        | 12        | 2.19%   |
| Zen              | 11        | 2%      |
| IceLake          | 10        | 1.82%   |
| K10              | 9         | 1.64%   |
| CometLake        | 9         | 1.64%   |
| Zen+             | 8         | 1.46%   |
| Piledriver       | 8         | 1.46%   |
| Goldmont plus    | 8         | 1.46%   |
| Silvermont       | 7         | 1.28%   |
| Core             | 6         | 1.09%   |
| Tremont          | 5         | 0.91%   |
| Nehalem          | 5         | 0.91%   |
| Excavator        | 5         | 0.91%   |
| K8 Hammer        | 4         | 0.73%   |
| Goldmont         | 3         | 0.55%   |
| Jaguar           | 2         | 0.36%   |
| Bonnell          | 2         | 0.36%   |
| Steamroller      | 1         | 0.18%   |
| P6               | 1         | 0.18%   |
| Bulldozer        | 1         | 0.18%   |
| Bobcat           | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 295       | 44.7%   |
| Nvidia                     | 213       | 32.27%  |
| AMD                        | 123       | 18.64%  |
| ASPEED Technology          | 25        | 3.79%   |
| Matrox Electronics Systems | 4         | 0.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 25        | 3.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 3.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 2.4%    |
| Nvidia TU104GL [PG189 SKU600]                                                            | 15        | 2.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 2.25%   |
| AMD Renoir                                                                               | 15        | 2.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 14        | 2.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.95%   |
| Intel HD Graphics 530                                                                    | 13        | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 1.95%   |
| Intel UHD Graphics 620                                                                   | 12        | 1.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 1.65%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 10        | 1.5%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 1.35%   |
| Intel HD Graphics 630                                                                    | 9         | 1.35%   |
| Intel HD Graphics 620                                                                    | 9         | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.35%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 8         | 1.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.2%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 8         | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.05%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.05%   |
| AMD Lucienne                                                                             | 7         | 1.05%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 0.75%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.75%   |
| Intel AlderLake-S GT1                                                                    | 5         | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.6%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 4         | 0.6%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 4         | 0.6%    |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 4         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 198       | 36%     |
| 1 x Nvidia      | 104       | 18.91%  |
| 1 x AMD         | 99        | 18%     |
| Intel + Nvidia  | 84        | 15.27%  |
| Nvidia + ASPEED | 17        | 3.09%   |
| Intel + AMD     | 14        | 2.55%   |
| Other           | 13        | 2.36%   |
| 1 x ASPEED      | 7         | 1.27%   |
| AMD + Nvidia    | 7         | 1.27%   |
| 1 x Matrox      | 4         | 0.73%   |
| 2 x AMD         | 2         | 0.36%   |
| AMD + ASPEED    | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 406       | 72.63%  |
| Proprietary | 115       | 20.57%  |
| Unknown     | 38        | 6.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 319       | 56.66%  |
| 1.01-2.0   | 70        | 12.43%  |
| 0.01-0.5   | 60        | 10.66%  |
| 0.51-1.0   | 34        | 6.04%   |
| 3.01-4.0   | 32        | 5.68%   |
| 5.01-6.0   | 24        | 4.26%   |
| 7.01-8.0   | 12        | 2.13%   |
| 8.01-16.0  | 8         | 1.42%   |
| 2.01-3.0   | 3         | 0.53%   |
| 16.01-24.0 | 1         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 65        | 11.42%  |
| Ancor Communications    | 45        | 7.91%   |
| BenQ                    | 42        | 7.38%   |
| Chimei Innolux          | 41        | 7.21%   |
| BOE                     | 39        | 6.85%   |
| LG Display              | 36        | 6.33%   |
| Acer                    | 35        | 6.15%   |
| ViewSonic               | 30        | 5.27%   |
| Philips                 | 28        | 4.92%   |
| Dell                    | 28        | 4.92%   |
| Samsung Electronics     | 23        | 4.04%   |
| Goldstar                | 17        | 2.99%   |
| AOC                     | 14        | 2.46%   |
| ASUSTek Computer        | 12        | 2.11%   |
| Hewlett-Packard         | 8         | 1.41%   |
| Eizo                    | 8         | 1.41%   |
| NEX                     | 7         | 1.23%   |
| Sharp                   | 6         | 1.05%   |
| Envision Peripherals    | 6         | 1.05%   |
| Unknown                 | 5         | 0.88%   |
| Apple                   | 5         | 0.88%   |
| Valve                   | 4         | 0.7%    |
| LG Electronics          | 4         | 0.7%    |
| Lenovo                  | 4         | 0.7%    |
| Vizio                   | 3         | 0.53%   |
| Sony                    | 3         | 0.53%   |
| PANDA                   | 3         | 0.53%   |
| InfoVision              | 3         | 0.53%   |
| Chi Mei Optoelectronics | 3         | 0.53%   |
| Wacom                   | 2         | 0.35%   |
| Unknown (XXX)           | 2         | 0.35%   |
| TMX                     | 2         | 0.35%   |
| MStar                   | 2         | 0.35%   |
| LG Philips              | 2         | 0.35%   |
| Gigabyte Technology     | 2         | 0.35%   |
| AUS                     | 2         | 0.35%   |
| Unknown                 | 2         | 0.35%   |
| ___                     | 1         | 0.18%   |
| WST                     | 1         | 0.18%   |
| VIZ                     | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips 190S PHL086B 1280x1024 376x301mm 19.0-inch                    | 15        | 2.61%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch           | 7         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.87%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 4         | 0.7%    |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch  | 4         | 0.7%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 0.7%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 4         | 0.7%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 4         | 0.7%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 4         | 0.7%    |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch          | 4         | 0.7%    |
| Ancor Communications ASUS VS229 ACI22C2 1920x1080 477x268mm 21.5-inch | 4         | 0.7%    |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 4         | 0.7%    |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                    | 4         | 0.7%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.52%   |
| Envision Peripherals LCD2271W ENV2271 1920x1080 476x268mm 21.5-inch   | 3         | 0.52%   |
| Dell U2415 DELA0B9 1920x1200 520x320mm 24.0-inch                      | 3         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 3         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.52%   |
| BenQ GW2470 BNQ78E4 1920x1080 530x300mm 24.0-inch                     | 3         | 0.52%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 3         | 0.52%   |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                    | 3         | 0.52%   |
| BenQ GL2450H BNQ78A6 1920x1080 531x298mm 24.0-inch                    | 3         | 0.52%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                     | 3         | 0.52%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.52%   |
| Ancor Communications ASUS VW247 ACI2496 1920x1080 531x299mm 24.0-inch | 3         | 0.52%   |
| Ancor Communications ASUS VS207 ACI20F2 1600x900 432x240mm 19.5-inch  | 3         | 0.52%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch | 3         | 0.52%   |
| Ancor Communications ASUS VH228 ACI22FC 1920x1080 477x268mm 21.5-inch | 3         | 0.52%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch | 3         | 0.52%   |
| Wacom Cintiq 13HD WAC1040 1920x1080 293x165mm 13.2-inch               | 2         | 0.35%   |
| ViewSonic VX2476 Series VSCD332 1920x1080 527x296mm 23.8-inch         | 2         | 0.35%   |
| ViewSonic VA916 Series VSC7C20 1280x1024 376x301mm 19.0-inch          | 2         | 0.35%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 480x270mm 21.7-inch         | 2         | 0.35%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 2         | 0.35%   |
| Unknown LCD Monitor Kingston Technology 43 TV 1920x1080               | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.35%   |
| Philips PHL 288P6L PHL08F2 3840x2160 621x341mm 27.9-inch              | 2         | 0.35%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 2         | 0.35%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.35%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 2         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 280       | 52.53%  |
| 1366x768 (WXGA)    | 66        | 12.38%  |
| 2560x1440 (QHD)    | 30        | 5.63%   |
| 3840x2160 (4K)     | 27        | 5.07%   |
| 1280x1024 (SXGA)   | 25        | 4.69%   |
| 1600x900 (HD+)     | 16        | 3%      |
| 1920x1200 (WUXGA)  | 15        | 2.81%   |
| 1680x1050 (WSXGA+) | 13        | 2.44%   |
| 2560x1080          | 9         | 1.69%   |
| 1440x900 (WXGA+)   | 8         | 1.5%    |
| Unknown            | 5         | 0.94%   |
| 800x1280           | 4         | 0.75%   |
| 2880x1800          | 4         | 0.75%   |
| 2560x1600          | 4         | 0.75%   |
| 1280x800 (WXGA)    | 4         | 0.75%   |
| 3840x1080          | 3         | 0.56%   |
| 3440x1440          | 3         | 0.56%   |
| 2160x1440          | 2         | 0.38%   |
| 1024x768 (XGA)     | 2         | 0.38%   |
| 3240x2160          | 1         | 0.19%   |
| 3200x2000          | 1         | 0.19%   |
| 3200x1800 (QHD+)   | 1         | 0.19%   |
| 2288x1287          | 1         | 0.19%   |
| 2256x1504          | 1         | 0.19%   |
| 2240x1400          | 1         | 0.19%   |
| 2048x1152          | 1         | 0.19%   |
| 1920x540           | 1         | 0.19%   |
| 1920x1280          | 1         | 0.19%   |
| 1680x945           | 1         | 0.19%   |
| 1360x768           | 1         | 0.19%   |
| 1280x720 (HD)      | 1         | 0.19%   |
| 1024x600           | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 86        | 15.17%  |
| 24      | 58        | 10.23%  |
| 13      | 56        | 9.88%   |
| 21      | 55        | 9.7%    |
| 27      | 51        | 8.99%   |
| 14      | 49        | 8.64%   |
| Unknown | 41        | 7.23%   |
| 23      | 39        | 6.88%   |
| 19      | 37        | 6.53%   |
| 31      | 11        | 1.94%   |
| 18      | 11        | 1.94%   |
| 17      | 11        | 1.94%   |
| 34      | 9         | 1.59%   |
| 22      | 9         | 1.59%   |
| 11      | 8         | 1.41%   |
| 12      | 7         | 1.23%   |
| 20      | 4         | 0.71%   |
| 7       | 4         | 0.71%   |
| 16      | 3         | 0.53%   |
| 54      | 2         | 0.35%   |
| 52      | 2         | 0.35%   |
| 43      | 2         | 0.35%   |
| 26      | 2         | 0.35%   |
| 10      | 2         | 0.35%   |
| 69      | 1         | 0.18%   |
| 65      | 1         | 0.18%   |
| 55      | 1         | 0.18%   |
| 48      | 1         | 0.18%   |
| 46      | 1         | 0.18%   |
| 42      | 1         | 0.18%   |
| 41      | 1         | 0.18%   |
| 25      | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 162       | 28.93%  |
| 501-600     | 136       | 24.29%  |
| 401-500     | 94        | 16.79%  |
| 201-300     | 49        | 8.75%   |
| Unknown     | 41        | 7.32%   |
| 351-400     | 32        | 5.71%   |
| 601-700     | 20        | 3.57%   |
| 701-800     | 9         | 1.61%   |
| 1001-1500   | 8         | 1.43%   |
| 901-1000    | 4         | 0.71%   |
| 1-100       | 4         | 0.71%   |
| 1501-2000   | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 372       | 71.95%  |
| 16/10   | 59        | 11.41%  |
| Unknown | 39        | 7.54%   |
| 5/4     | 23        | 4.45%   |
| 21/9    | 9         | 1.74%   |
| 3/2     | 6         | 1.16%   |
| 0.67    | 4         | 0.77%   |
| 4/3     | 2         | 0.39%   |
| 32/9    | 2         | 0.39%   |
| 6/5     | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 127       | 22.52%  |
| 101-110        | 84        | 14.89%  |
| 81-90          | 78        | 13.83%  |
| 151-200        | 58        | 10.28%  |
| 301-350        | 53        | 9.4%    |
| Unknown        | 41        | 7.27%   |
| 71-80          | 28        | 4.96%   |
| 351-500        | 20        | 3.55%   |
| 251-300        | 15        | 2.66%   |
| 141-150        | 13        | 2.3%    |
| 121-130        | 10        | 1.77%   |
| 51-60          | 9         | 1.6%    |
| More than 1000 | 7         | 1.24%   |
| 61-70          | 6         | 1.06%   |
| 501-1000       | 6         | 1.06%   |
| 1-40           | 4         | 0.71%   |
| 111-120        | 4         | 0.71%   |
| 41-50          | 1         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 210       | 37.57%  |
| 121-160       | 128       | 22.9%   |
| 101-120       | 118       | 21.11%  |
| 161-240       | 44        | 7.87%   |
| Unknown       | 41        | 7.33%   |
| More than 240 | 12        | 2.15%   |
| 1-50          | 6         | 1.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 445       | 80.32%  |
| 2     | 66        | 11.91%  |
| 0     | 40        | 7.22%   |
| 3     | 3         | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 287       | 34.29%  |
| Realtek Semiconductor                  | 271       | 32.38%  |
| Qualcomm Atheros                       | 74        | 8.84%   |
| Broadcom                               | 35        | 4.18%   |
| MediaTek                               | 29        | 3.46%   |
| American Megatrends                    | 17        | 2.03%   |
| Aquantia                               | 11        | 1.31%   |
| Ralink Technology                      | 10        | 1.19%   |
| Edimax Technology                      | 9         | 1.08%   |
| Broadcom Limited                       | 9         | 1.08%   |
| ASIX Electronics                       | 9         | 1.08%   |
| TP-Link                                | 8         | 0.96%   |
| Marvell Technology Group               | 7         | 0.84%   |
| Ralink                                 | 6         | 0.72%   |
| Nvidia                                 | 5         | 0.6%    |
| ASUSTek Computer                       | 5         | 0.6%    |
| Samsung Electronics                    | 4         | 0.48%   |
| HTC (High Tech Computer)               | 4         | 0.48%   |
| D-Link                                 | 4         | 0.48%   |
| OPPO Electronics                       | 3         | 0.36%   |
| Microsoft                              | 2         | 0.24%   |
| Mellanox Technologies                  | 2         | 0.24%   |
| IBM                                    | 2         | 0.24%   |
| Google                                 | 2         | 0.24%   |
| ZyXEL Communications                   | 1         | 0.12%   |
| U-Blox                                 | 1         | 0.12%   |
| SparkFun                               | 1         | 0.12%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.12%   |
| Senao                                  | 1         | 0.12%   |
| Qualcomm Atheros Communications        | 1         | 0.12%   |
| Prolific Technology                    | 1         | 0.12%   |
| Microchip Technology                   | 1         | 0.12%   |
| Mercucys                               | 1         | 0.12%   |
| Luminary Micro                         | 1         | 0.12%   |
| LG Electronics                         | 1         | 0.12%   |
| Lenovo                                 | 1         | 0.12%   |
| Insyde Software                        | 1         | 0.12%   |
| Huawei Technologies                    | 1         | 0.12%   |
| HMD Global                             | 1         | 0.12%   |
| Gemalto M2M                            | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 197       | 20.5%   |
| Intel Wi-Fi 6 AX200                                               | 31        | 3.23%   |
| Intel I211 Gigabit Network Connection                             | 22        | 2.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19        | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 1.87%   |
| Intel Wireless 8265 / 8275                                        | 18        | 1.87%   |
| Intel Ethernet Connection (3) I219-LM                             | 17        | 1.77%   |
| American Megatrends Virtual Ethernet.                             | 17        | 1.77%   |
| Intel Ethernet Controller I225-V                                  | 16        | 1.66%   |
| Intel Wi-Fi 6 AX201                                               | 14        | 1.46%   |
| Intel I210 Gigabit Network Connection                             | 14        | 1.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 14        | 1.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 1.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 11        | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 1.04%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 9         | 0.94%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 9         | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 9         | 0.94%   |
| Intel Wireless-AC 9260                                            | 9         | 0.94%   |
| Intel Wireless 7265                                               | 9         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 9         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 0.83%   |
| Intel Wireless 3165                                               | 8         | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 0.73%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.73%   |
| Intel Wireless 7260                                               | 7         | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 0.73%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7         | 0.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 6         | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 196       | 51.58%  |
| Qualcomm Atheros                | 43        | 11.32%  |
| Realtek Semiconductor           | 41        | 10.79%  |
| MediaTek                        | 27        | 7.11%   |
| Broadcom                        | 20        | 5.26%   |
| Ralink Technology               | 10        | 2.63%   |
| Edimax Technology               | 9         | 2.37%   |
| Ralink                          | 6         | 1.58%   |
| Broadcom Limited                | 6         | 1.58%   |
| TP-Link                         | 5         | 1.32%   |
| ASUSTek Computer                | 5         | 1.32%   |
| D-Link                          | 4         | 1.05%   |
| ZyXEL Communications            | 1         | 0.26%   |
| Senao                           | 1         | 0.26%   |
| Qualcomm Atheros Communications | 1         | 0.26%   |
| Microsoft                       | 1         | 0.26%   |
| Mercucys                        | 1         | 0.26%   |
| D-Link System                   | 1         | 0.26%   |
| BUFFALO                         | 1         | 0.26%   |
| Accton Technology               | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 31        | 8.14%   |
| Intel Wireless 8265 / 8275                                     | 18        | 4.72%   |
| Intel Wi-Fi 6 AX201                                            | 14        | 3.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 14        | 3.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 2.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 9         | 2.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 9         | 2.36%   |
| Intel Wireless-AC 9260                                         | 9         | 2.36%   |
| Intel Wireless 7265                                            | 9         | 2.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 9         | 2.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 9         | 2.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 2.1%    |
| Intel Wireless 3165                                            | 8         | 2.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 1.84%   |
| Ralink MT7601U Wireless Adapter                                | 7         | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 1.84%   |
| Intel Wireless 7260                                            | 7         | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 1.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 1.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.31%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 1.31%   |
| Intel Wireless 8260                                            | 5         | 1.31%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 4         | 1.05%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 4         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 1.05%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 4         | 1.05%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 4         | 1.05%   |
| Broadcom BCM43225 802.11b/g/n                                  | 4         | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.79%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter             | 3         | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 249       | 45.77%  |
| Intel                    | 152       | 27.94%  |
| Qualcomm Atheros         | 42        | 7.72%   |
| Broadcom                 | 18        | 3.31%   |
| American Megatrends      | 17        | 3.13%   |
| Aquantia                 | 11        | 2.02%   |
| ASIX Electronics         | 9         | 1.65%   |
| Marvell Technology Group | 7         | 1.29%   |
| Nvidia                   | 5         | 0.92%   |
| Samsung Electronics      | 4         | 0.74%   |
| HTC (High Tech Computer) | 4         | 0.74%   |
| TP-Link                  | 3         | 0.55%   |
| OPPO Electronics         | 3         | 0.55%   |
| Broadcom Limited         | 3         | 0.55%   |
| Mellanox Technologies    | 2         | 0.37%   |
| MediaTek                 | 2         | 0.37%   |
| IBM                      | 2         | 0.37%   |
| Google                   | 2         | 0.37%   |
| Microsoft                | 1         | 0.18%   |
| Microchip Technology     | 1         | 0.18%   |
| LG Electronics           | 1         | 0.18%   |
| Lenovo                   | 1         | 0.18%   |
| Insyde Software          | 1         | 0.18%   |
| Huawei Technologies      | 1         | 0.18%   |
| HMD Global               | 1         | 0.18%   |
| Apple                    | 1         | 0.18%   |
| 3Com                     | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 197       | 34.38%  |
| Intel I211 Gigabit Network Connection                               | 22        | 3.84%   |
| Realtek RTL8125 2.5GbE Controller                                   | 19        | 3.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 18        | 3.14%   |
| Intel Ethernet Connection (3) I219-LM                               | 17        | 2.97%   |
| American Megatrends Virtual Ethernet.                               | 17        | 2.97%   |
| Intel Ethernet Controller I225-V                                    | 16        | 2.79%   |
| Intel I210 Gigabit Network Connection                               | 14        | 2.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 12        | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 10        | 1.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 9         | 1.57%   |
| Intel Ethernet Connection (7) I219-V                                | 8         | 1.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 7         | 1.22%   |
| Intel Ethernet Connection (7) I219-LM                               | 7         | 1.22%   |
| Intel Ethernet Connection (2) I219-V                                | 7         | 1.22%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 7         | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 6         | 1.05%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                     | 6         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                       | 6         | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 5         | 0.87%   |
| Intel Ethernet Connection I217-V                                    | 5         | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 4         | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 4         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 4         | 0.7%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                       | 4         | 0.7%    |
| Intel Ethernet Connection I217-LM                                   | 4         | 0.7%    |
| Intel Ethernet Connection (4) I219-V                                | 4         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                               | 4         | 0.7%    |
| Intel 82574L Gigabit Network Connection                             | 4         | 0.7%    |
| HTC (High Tech Computer) Desire HD (modem mode)                     | 4         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 3         | 0.52%   |
| OPPO SM6375-QRD _SN:F4A23F05                                        | 3         | 0.52%   |
| Nvidia MCP61 Ethernet                                               | 3         | 0.52%   |
| Intel Ethernet Connection I218-LM                                   | 3         | 0.52%   |
| Intel 82579V Gigabit Network Connection                             | 3         | 0.52%   |
| Intel 82577LM Gigabit Network Connection                            | 3         | 0.52%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 0.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 2         | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2         | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                               | 2         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 472       | 55.86%  |
| WiFi     | 366       | 43.31%  |
| Modem    | 6         | 0.71%   |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 301       | 53.65%  |
| WiFi     | 259       | 46.17%  |
| Unknown  | 1         | 0.18%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 266       | 48.45%  |
| 1     | 236       | 42.99%  |
| 0     | 20        | 3.64%   |
| 3     | 17        | 3.1%    |
| 4     | 4         | 0.73%   |
| 10    | 2         | 0.36%   |
| 6     | 2         | 0.36%   |
| 5     | 2         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 486       | 87.57%  |
| Yes  | 69        | 12.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 179       | 54.91%  |
| IMC Networks                    | 20        | 6.13%   |
| Broadcom                        | 19        | 5.83%   |
| Realtek Semiconductor           | 17        | 5.21%   |
| Cambridge Silicon Radio         | 17        | 5.21%   |
| Foxconn / Hon Hai               | 15        | 4.6%    |
| Qualcomm Atheros Communications | 14        | 4.29%   |
| MediaTek                        | 11        | 3.37%   |
| Lite-On Technology              | 9         | 2.76%   |
| Apple                           | 6         | 1.84%   |
| ASUSTek Computer                | 5         | 1.53%   |
| Realtek                         | 3         | 0.92%   |
| Ralink                          | 3         | 0.92%   |
| Hewlett-Packard                 | 3         | 0.92%   |
| Toshiba                         | 2         | 0.61%   |
| TP-Link                         | 1         | 0.31%   |
| Opticis                         | 1         | 0.31%   |
| Dell                            | 1         | 0.31%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 51        | 15.64%  |
| Intel AX201 Bluetooth                                                               | 33        | 10.12%  |
| Intel AX200 Bluetooth                                                               | 31        | 9.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 20        | 6.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 17        | 5.21%   |
| Realtek Bluetooth Radio                                                             | 14        | 4.29%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 14        | 4.29%   |
| MediaTek Wireless_Device                                                            | 11        | 3.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 2.76%   |
| Intel AX210 Bluetooth                                                               | 9         | 2.76%   |
| Intel Bluetooth Device                                                              | 8         | 2.45%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 1.84%   |
| IMC Networks Bluetooth Radio                                                        | 6         | 1.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.53%   |
| IMC Networks Wireless_Device                                                        | 5         | 1.53%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.23%   |
| Apple Bluetooth Host Controller                                                     | 4         | 1.23%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 0.92%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth                                         | 3         | 0.92%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 0.92%   |
| Broadcom BCM2045 Bluetooth                                                          | 3         | 0.92%   |
| Toshiba Bluetooth USB Host Controller                                               | 2         | 0.61%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 0.61%   |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 0.61%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.61%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.61%   |
| IMC Networks BCM20702A0                                                             | 2         | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.61%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.61%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.61%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.61%   |
| Broadcom Bluetooth                                                                  | 2         | 0.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 0.61%   |
| Broadcom BCM20702A0                                                                 | 2         | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.61%   |
| ASUS Bluetooth Radio                                                                | 2         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 380       | 53.07%  |
| Nvidia                               | 139       | 19.41%  |
| AMD                                  | 139       | 19.41%  |
| C-Media Electronics                  | 7         | 0.98%   |
| ASUSTek Computer                     | 6         | 0.84%   |
| Logitech                             | 4         | 0.56%   |
| Texas Instruments                    | 3         | 0.42%   |
| GN Netcom                            | 3         | 0.42%   |
| Generalplus Technology               | 3         | 0.42%   |
| XMOS                                 | 2         | 0.28%   |
| SAVITECH                             | 2         | 0.28%   |
| Realtek Semiconductor                | 2         | 0.28%   |
| Micro Star International             | 2         | 0.28%   |
| KORG                                 | 2         | 0.28%   |
| Focusrite-Novation                   | 2         | 0.28%   |
| Dell                                 | 2         | 0.28%   |
| Audio-Technica                       | 2         | 0.28%   |
| ZOOM                                 | 1         | 0.14%   |
| Yamaha                               | 1         | 0.14%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.14%   |
| Sony                                 | 1         | 0.14%   |
| OPPO Electronics                     | 1         | 0.14%   |
| Novra/IDC/Wegener                    | 1         | 0.14%   |
| Microsoft                            | 1         | 0.14%   |
| JMTek                                | 1         | 0.14%   |
| Harman                               | 1         | 0.14%   |
| Giga-Byte Technology                 | 1         | 0.14%   |
| ESS Technology                       | 1         | 0.14%   |
| Elite Silicon                        | 1         | 0.14%   |
| Creative Technology                  | 1         | 0.14%   |
| Creative Labs                        | 1         | 0.14%   |
| Cambridge Silicon Radio              | 1         | 0.14%   |
| 2.4G Composite Device                | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 56        | 6.64%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 41        | 4.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 35        | 4.15%   |
| Intel Sunrise Point-LP HD Audio                                            | 33        | 3.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 33        | 3.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 30        | 3.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 28        | 3.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21        | 2.49%   |
| AMD Starship/Matisse HD Audio Controller                                   | 21        | 2.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19        | 2.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 1.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 15        | 1.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 15        | 1.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 14        | 1.66%   |
| Nvidia GP106 High Definition Audio Controller                              | 13        | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 1.54%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 1.54%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12        | 1.42%   |
| Intel 200 Series PCH HD Audio                                              | 11        | 1.3%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 10        | 1.19%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10        | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9         | 1.07%   |
| Intel Alder Lake-S HD Audio Controller                                     | 9         | 1.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9         | 1.07%   |
| Nvidia GP108 High Definition Audio Controller                              | 8         | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 0.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 0.95%   |
| Intel CM238 HD Audio Controller                                            | 8         | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 0.95%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 0.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                         | 7         | 0.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7         | 0.83%   |
| Nvidia MCP61 High Definition Audio                                         | 6         | 0.71%   |
| Nvidia GF116 High Definition Audio Controller                              | 6         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 57        | 15.53%  |
| Samsung Electronics | 53        | 14.44%  |
| Kingston            | 49        | 13.35%  |
| Crucial             | 48        | 13.08%  |
| Micron Technology   | 44        | 11.99%  |
| Transcend           | 28        | 7.63%   |
| Unknown             | 24        | 6.54%   |
| A-DATA Technology   | 16        | 4.36%   |
| Apacer              | 7         | 1.91%   |
| Unifosa             | 4         | 1.09%   |
| G.Skill             | 4         | 1.09%   |
| Team                | 3         | 0.82%   |
| Ramaxel Technology  | 3         | 0.82%   |
| Patriot             | 3         | 0.82%   |
| Unknown             | 3         | 0.82%   |
| Silicon Power       | 2         | 0.54%   |
| Goldkey             | 2         | 0.54%   |
| G-Alantic           | 2         | 0.54%   |
| Elpida              | 2         | 0.54%   |
| ASint Technology    | 2         | 0.54%   |
| V-Color             | 1         | 0.27%   |
| Unknown (ABCD)      | 1         | 0.27%   |
| Unknown (08AE)      | 1         | 0.27%   |
| UMAX                | 1         | 0.27%   |
| PNY                 | 1         | 0.27%   |
| Nanya Technology    | 1         | 0.27%   |
| Lexar               | 1         | 0.27%   |
| KLEVV               | 1         | 0.27%   |
| GLOWAY              | 1         | 0.27%   |
| CUSO                | 1         | 0.27%   |
| Avant               | 1         | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 4         | 1.02%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s           | 4         | 1.02%   |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s                    | 4         | 1.02%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s                 | 3         | 0.76%   |
| Transcend RAM Module 4GB DIMM DDR3 1600MT/s                      | 3         | 0.76%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.76%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.76%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.76%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.76%   |
| Kingston RAM 9905624-033.A00G 8GB SODIMM DDR4 2400MT/s           | 3         | 0.76%   |
| A-DATA RAM DDR4 3000 2OZ 16GB DIMM DDR4 3000MT/s                 | 3         | 0.76%   |
| Unknown                                                          | 3         | 0.76%   |
| Transcend RAM JM1333KLN-4G 4096MB DIMM SDRAM 1600MT/s            | 2         | 0.51%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s              | 2         | 0.51%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 2         | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.51%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.51%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.51%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.51%   |
| Samsung RAM M471A1K43CB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.51%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s   | 2         | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 0.51%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.51%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 2         | 0.51%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 0.51%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 2         | 0.51%   |
| G-Alantic RAM D4SS12161SH26A-C 4GB SODIMM DDR4 2133MT/s          | 2         | 0.51%   |
| Crucial RAM CT8G4SFS632A.C4FE 8GB SODIMM DDR4 3200MT/s           | 2         | 0.51%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 3600MT/s             | 2         | 0.51%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s         | 2         | 0.51%   |
| Crucial RAM CT16G4SFD832A.M16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 0.51%   |
| Crucial RAM CT16G4SFD8266.M16FE 16GB SODIMM DDR4 2667MT/s        | 2         | 0.51%   |
| V-Color RAM TD4G8C11-H11 4GB DIMM DDR3 1600MT/s                  | 1         | 0.25%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.25%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 172       | 54.95%  |
| DDR3    | 77        | 24.6%   |
| LPDDR4  | 15        | 4.79%   |
| Unknown | 13        | 4.15%   |
| LPDDR3  | 11        | 3.51%   |
| LPDDR5  | 7         | 2.24%   |
| DDR5    | 7         | 2.24%   |
| DDR2    | 6         | 1.92%   |
| SDRAM   | 4         | 1.28%   |
| DDR     | 1         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 153       | 49.2%   |
| DIMM         | 126       | 40.51%  |
| Row Of Chips | 30        | 9.65%   |
| Chip         | 1         | 0.32%   |
| Unknown      | 1         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 131       | 38.99%  |
| 4096  | 81        | 24.11%  |
| 16384 | 73        | 21.73%  |
| 2048  | 24        | 7.14%   |
| 32768 | 22        | 6.55%   |
| 1024  | 4         | 1.19%   |
| 8072  | 1         | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 73        | 21.79%  |
| 1600    | 64        | 19.1%   |
| 2667    | 44        | 13.13%  |
| 2400    | 29        | 8.66%   |
| 2133    | 21        | 6.27%   |
| 1333    | 12        | 3.58%   |
| 4800    | 8         | 2.39%   |
| 6400    | 7         | 2.09%   |
| 4267    | 7         | 2.09%   |
| 3600    | 7         | 2.09%   |
| 1867    | 6         | 1.79%   |
| 1334    | 6         | 1.79%   |
| 800     | 6         | 1.79%   |
| 3733    | 5         | 1.49%   |
| 3000    | 5         | 1.49%   |
| 4266    | 3         | 0.9%    |
| 667     | 3         | 0.9%    |
| 3466    | 2         | 0.6%    |
| 3400    | 2         | 0.6%    |
| 2933    | 2         | 0.6%    |
| 2666    | 2         | 0.6%    |
| 2000    | 2         | 0.6%    |
| 1066    | 2         | 0.6%    |
| 533     | 2         | 0.6%    |
| 8400    | 1         | 0.3%    |
| 6000    | 1         | 0.3%    |
| 5200    | 1         | 0.3%    |
| 4333    | 1         | 0.3%    |
| 4000    | 1         | 0.3%    |
| 3866    | 1         | 0.3%    |
| 3800    | 1         | 0.3%    |
| 3334    | 1         | 0.3%    |
| 3266    | 1         | 0.3%    |
| 3134    | 1         | 0.3%    |
| 2866    | 1         | 0.3%    |
| 1067    | 1         | 0.3%    |
| 975     | 1         | 0.3%    |
| 400     | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 60%     |
| Seiko Epson     | 2         | 40%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson XP-240 Series        | 1         | 20%     |
| Seiko Epson L3110 Series         | 1         | 20%     |
| HP LaserJet Professional P1102w  | 1         | 20%     |
| HP LaserJet Professional P 1102w | 1         | 20%     |
| HP LaserJet 1020                 | 1         | 20%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 57        | 24.46%  |
| IMC Networks                           | 32        | 13.73%  |
| Realtek Semiconductor                  | 21        | 9.01%   |
| Logitech                               | 15        | 6.44%   |
| Sunplus Innovation Technology          | 12        | 5.15%   |
| Microdia                               | 12        | 5.15%   |
| Quanta                                 | 11        | 4.72%   |
| Bison Electronics                      | 10        | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.43%   |
| Acer                                   | 8         | 3.43%   |
| Suyin                                  | 7         | 3%      |
| Apple                                  | 6         | 2.58%   |
| Syntek                                 | 4         | 1.72%   |
| Luxvisions Innotech Limited            | 4         | 1.72%   |
| ALi                                    | 3         | 1.29%   |
| Sunplus Technology                     | 2         | 0.86%   |
| Sonix Technology                       | 2         | 0.86%   |
| Ricoh                                  | 2         | 0.86%   |
| Lite-On Technology                     | 2         | 0.86%   |
| Lenovo                                 | 2         | 0.86%   |
| Importek                               | 2         | 0.86%   |
| Generalplus Technology                 | 2         | 0.86%   |
| SunplusIT                              | 1         | 0.43%   |
| Silicon Motion                         | 1         | 0.43%   |
| Samsung Electronics                    | 1         | 0.43%   |
| KYE Systems (Mouse Systems)            | 1         | 0.43%   |
| Intel                                  | 1         | 0.43%   |
| Google                                 | 1         | 0.43%   |
| Foxconn / Hon Hai                      | 1         | 0.43%   |
| eMeet                                  | 1         | 0.43%   |
| A4Tech                                 | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 16        | 6.84%   |
| Chicony Integrated Camera                                                  | 12        | 5.13%   |
| Chicony HD WebCam                                                          | 9         | 3.85%   |
| Realtek Integrated_Webcam_HD                                               | 6         | 2.56%   |
| IMC Networks Integrated Camera                                             | 6         | 2.56%   |
| Bison HD Webcam                                                            | 6         | 2.56%   |
| Sunplus HD WebCam                                                          | 5         | 2.14%   |
| Realtek USB Camera                                                         | 5         | 2.14%   |
| Logitech Webcam C270                                                       | 5         | 2.14%   |
| Chicony HP HD Camera                                                       | 5         | 2.14%   |
| Quanta HD User Facing                                                      | 4         | 1.71%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.71%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.71%   |
| Realtek HD WebCam                                                          | 3         | 1.28%   |
| Microdia Integrated_Webcam_FHD                                             | 3         | 1.28%   |
| Logitech Webcam C120                                                       | 3         | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.28%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.28%   |
| Chicony HD User Facing                                                     | 3         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.28%   |
| ALi Gateway Webcam                                                         | 3         | 1.28%   |
| Acer Integrated Camera                                                     | 3         | 1.28%   |
| Syntek Integrated Camera                                                   | 2         | 0.85%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.85%   |
| Sunplus 1.3M HD WebCam                                                     | 2         | 0.85%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.85%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 0.85%   |
| Quanta HP HD Camera                                                        | 2         | 0.85%   |
| Microdia USB 2.0 Camera                                                    | 2         | 0.85%   |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 0.85%   |
| Logitech Webcam C930e                                                      | 2         | 0.85%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 0.85%   |
| IMC Networks UVC VGA Webcam                                                | 2         | 0.85%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 2         | 0.85%   |
| Generalplus GENERAL WEBCAM                                                 | 2         | 0.85%   |
| Chicony Webcam                                                             | 2         | 0.85%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.85%   |
| Chicony USB2.0 Camera                                                      | 2         | 0.85%   |
| Chicony USB 2.0 Webcam Device                                              | 2         | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 16        | 28.57%  |
| Validity Sensors                   | 9         | 16.07%  |
| Shenzhen Goodix Technology         | 8         | 14.29%  |
| LighTuning Technology              | 8         | 14.29%  |
| Elan Microelectronics              | 6         | 10.71%  |
| Upek                               | 4         | 7.14%   |
| AuthenTec                          | 3         | 5.36%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                           | 5         | 8.93%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 7.14%   |
| Shenzhen Goodix  Fingerprint Device                             | 4         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                              | 4         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 4         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 3         | 5.36%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 3         | 5.36%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 3         | 5.36%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 2         | 3.57%   |
| Validity Sensors VFS Fingerprint sensor                         | 2         | 3.57%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 2         | 3.57%   |
| Synaptics WBDI                                                  | 2         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 3.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 3.57%   |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 3.57%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 3.57%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 1         | 1.79%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.79%   |
| Synaptics UWP WBDI                                              | 1         | 1.79%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                    | 1         | 1.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 1.79%   |
| LighTuning Fingerprint Reader                                   | 1         | 1.79%   |
| Elan fingerprint sensor [FeinTech FPS00200]                     | 1         | 1.79%   |
| AuthenTec AES2810                                               | 1         | 1.79%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 1.79%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 1.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 6         | 40%     |
| Broadcom              | 4         | 26.67%  |
| Upek                  | 2         | 13.33%  |
| SCM Microsystems      | 1         | 6.67%   |
| Lenovo                | 1         | 6.67%   |
| Gemalto (was Gemplus) | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 26.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 13.33%  |
| Broadcom 58200                                                               | 2         | 13.33%  |
| Alcor Micro Watchdata W 1981                                                 | 2         | 13.33%  |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 6.67%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 6.67%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 375       | 66.73%  |
| 1     | 131       | 23.31%  |
| 2     | 30        | 5.34%   |
| 3     | 20        | 3.56%   |
| 4     | 5         | 0.89%   |
| 5     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 56        | 23.83%  |
| Fingerprint reader       | 56        | 23.83%  |
| Communication controller | 30        | 12.77%  |
| Unassigned class         | 26        | 11.06%  |
| Net/wireless             | 17        | 7.23%   |
| Chipcard                 | 10        | 4.26%   |
| Multimedia controller    | 7         | 2.98%   |
| Camera                   | 7         | 2.98%   |
| Card reader              | 6         | 2.55%   |
| Net/ethernet             | 5         | 2.13%   |
| Bluetooth                | 5         | 2.13%   |
| Sound                    | 3         | 1.28%   |
| Storage/raid             | 2         | 0.85%   |
| Storage/nvme             | 2         | 0.85%   |
| Network                  | 2         | 0.85%   |
| Storage                  | 1         | 0.43%   |

