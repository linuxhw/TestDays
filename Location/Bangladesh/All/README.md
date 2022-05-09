Linux in Bangladesh - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Bangladesh.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bangladesh/Desktop/README.md) and [notebooks](/Location/Bangladesh/Notebook/README.md).

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

Total: 320

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 240 G3                      | Notebook    | [7062083e69](https://linux-hardware.org/?probe=7062083e69) | May 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3055b0e95f](https://linux-hardware.org/?probe=3055b0e95f) | May 05, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [88f6586c4b](https://linux-hardware.org/?probe=88f6586c4b) | May 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ab11d6ac2f](https://linux-hardware.org/?probe=ab11d6ac2f) | Apr 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6577346b8](https://linux-hardware.org/?probe=c6577346b8) | Apr 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e993bc145](https://linux-hardware.org/?probe=6e993bc145) | Apr 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [73abf1d6fd](https://linux-hardware.org/?probe=73abf1d6fd) | Apr 08, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [19623aa8b6](https://linux-hardware.org/?probe=19623aa8b6) | Apr 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [287aa3ba8e](https://linux-hardware.org/?probe=287aa3ba8e) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [d9aef69378](https://linux-hardware.org/?probe=d9aef69378) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [d1b6ca0f16](https://linux-hardware.org/?probe=d1b6ca0f16) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [14a3433a91](https://linux-hardware.org/?probe=14a3433a91) | Apr 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [863c2666dc](https://linux-hardware.org/?probe=863c2666dc) | Apr 02, 2022 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | Notebook    | [8199781e64](https://linux-hardware.org/?probe=8199781e64) | Mar 28, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [33d1544ea1](https://linux-hardware.org/?probe=33d1544ea1) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [52ce856be5](https://linux-hardware.org/?probe=52ce856be5) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [1dd07eeee0](https://linux-hardware.org/?probe=1dd07eeee0) | Mar 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [321d0c1b4a](https://linux-hardware.org/?probe=321d0c1b4a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [5db5bac582](https://linux-hardware.org/?probe=5db5bac582) | Mar 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [fec31ddcd9](https://linux-hardware.org/?probe=fec31ddcd9) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [cb949f34eb](https://linux-hardware.org/?probe=cb949f34eb) | Mar 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [da23c76a90](https://linux-hardware.org/?probe=da23c76a90) | Mar 19, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [a3ad6439b8](https://linux-hardware.org/?probe=a3ad6439b8) | Mar 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [fd9e66788c](https://linux-hardware.org/?probe=fd9e66788c) | Mar 17, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e141c99bf2](https://linux-hardware.org/?probe=e141c99bf2) | Mar 09, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [87d97b3c00](https://linux-hardware.org/?probe=87d97b3c00) | Mar 05, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [5bb83b4355](https://linux-hardware.org/?probe=5bb83b4355) | Mar 05, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [d7a873bf3d](https://linux-hardware.org/?probe=d7a873bf3d) | Feb 27, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [87f30f494f](https://linux-hardware.org/?probe=87f30f494f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [62c028a881](https://linux-hardware.org/?probe=62c028a881) | Feb 16, 2022 |
| Biostar       | H55 HD                      | Desktop     | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [42647bc4b3](https://linux-hardware.org/?probe=42647bc4b3) | Feb 12, 2022 |
| HP            | 339A                        | Desktop     | [6f8e63bfb0](https://linux-hardware.org/?probe=6f8e63bfb0) | Feb 11, 2022 |
| ASUSTek       | TUF GAMING Z690-PLUS WIF... | Desktop     | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [8e73dc39ab](https://linux-hardware.org/?probe=8e73dc39ab) | Feb 09, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [42e37d6172](https://linux-hardware.org/?probe=42e37d6172) | Feb 07, 2022 |
| Biostar       | H55 HD                      | Desktop     | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [47c47a0121](https://linux-hardware.org/?probe=47c47a0121) | Feb 02, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [d7431ab69e](https://linux-hardware.org/?probe=d7431ab69e) | Jan 31, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [76d17811e3](https://linux-hardware.org/?probe=76d17811e3) | Jan 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [caca9680a9](https://linux-hardware.org/?probe=caca9680a9) | Jan 25, 2022 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [be92c29259](https://linux-hardware.org/?probe=be92c29259) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1e89749691](https://linux-hardware.org/?probe=1e89749691) | Jan 22, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [ac35b74090](https://linux-hardware.org/?probe=ac35b74090) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [88f62c8333](https://linux-hardware.org/?probe=88f62c8333) | Jan 15, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [38a7870ece](https://linux-hardware.org/?probe=38a7870ece) | Jan 13, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [2fb0411785](https://linux-hardware.org/?probe=2fb0411785) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [0d69dca8f3](https://linux-hardware.org/?probe=0d69dca8f3) | Jan 04, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [692274162f](https://linux-hardware.org/?probe=692274162f) | Jan 04, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e6a4a21d5c](https://linux-hardware.org/?probe=e6a4a21d5c) | Jan 02, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [8e8da56e93](https://linux-hardware.org/?probe=8e8da56e93) | Jan 01, 2022 |
| OEM           | Unknown                     | Desktop     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [b674024789](https://linux-hardware.org/?probe=b674024789) | Dec 30, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [209e15690e](https://linux-hardware.org/?probe=209e15690e) | Dec 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [00696e3398](https://linux-hardware.org/?probe=00696e3398) | Dec 28, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [7280895518](https://linux-hardware.org/?probe=7280895518) | Dec 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [56d5bb8659](https://linux-hardware.org/?probe=56d5bb8659) | Dec 22, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [96aeb2edec](https://linux-hardware.org/?probe=96aeb2edec) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [30372f5462](https://linux-hardware.org/?probe=30372f5462) | Dec 12, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [6ab6a89db8](https://linux-hardware.org/?probe=6ab6a89db8) | Dec 12, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [50182e0cd0](https://linux-hardware.org/?probe=50182e0cd0) | Dec 11, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3cd505591d](https://linux-hardware.org/?probe=3cd505591d) | Dec 11, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Dell          | Latitude 7480               | Notebook    | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [42edbb20ce](https://linux-hardware.org/?probe=42edbb20ce) | Dec 04, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [07bcad31f5](https://linux-hardware.org/?probe=07bcad31f5) | Dec 02, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [cf0cd5c862](https://linux-hardware.org/?probe=cf0cd5c862) | Dec 01, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [5cd208a361](https://linux-hardware.org/?probe=5cd208a361) | Dec 01, 2021 |
| ASUSTek       | P453UJ                      | Notebook    | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [aa0a0e67b3](https://linux-hardware.org/?probe=aa0a0e67b3) | Nov 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [9bffff74e0](https://linux-hardware.org/?probe=9bffff74e0) | Nov 26, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [09b0e5058d](https://linux-hardware.org/?probe=09b0e5058d) | Nov 23, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [623b2b0ba9](https://linux-hardware.org/?probe=623b2b0ba9) | Nov 19, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [47d816d00f](https://linux-hardware.org/?probe=47d816d00f) | Nov 12, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [6d2cade66c](https://linux-hardware.org/?probe=6d2cade66c) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [312e04d7f9](https://linux-hardware.org/?probe=312e04d7f9) | Nov 09, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f1f7ca30e5](https://linux-hardware.org/?probe=f1f7ca30e5) | Nov 05, 2021 |
| ASUSTek       | X442UAR                     | Notebook    | [0db140fa3d](https://linux-hardware.org/?probe=0db140fa3d) | Nov 03, 2021 |
| OEM           | Intel H81                   | Desktop     | [a4e298caf1](https://linux-hardware.org/?probe=a4e298caf1) | Nov 02, 2021 |
| OEM           | Intel H81                   | Desktop     | [50758cfaf3](https://linux-hardware.org/?probe=50758cfaf3) | Oct 26, 2021 |
| OEM           | Intel H81                   | Desktop     | [e997f638bc](https://linux-hardware.org/?probe=e997f638bc) | Oct 26, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [356632b328](https://linux-hardware.org/?probe=356632b328) | Oct 19, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [d377aa2b23](https://linux-hardware.org/?probe=d377aa2b23) | Oct 17, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [7447071c00](https://linux-hardware.org/?probe=7447071c00) | Oct 16, 2021 |
| MSI           | Boston                      | Desktop     | [77d385bc09](https://linux-hardware.org/?probe=77d385bc09) | Oct 13, 2021 |
| MSI           | Boston                      | Desktop     | [14528f628a](https://linux-hardware.org/?probe=14528f628a) | Oct 13, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [9a11428a51](https://linux-hardware.org/?probe=9a11428a51) | Oct 12, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [0bf0387391](https://linux-hardware.org/?probe=0bf0387391) | Oct 07, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [883e0dec71](https://linux-hardware.org/?probe=883e0dec71) | Sep 19, 2021 |
| Dell          | Latitude E7250              | Notebook    | [275b9204f5](https://linux-hardware.org/?probe=275b9204f5) | Sep 13, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [8109d84e42](https://linux-hardware.org/?probe=8109d84e42) | Sep 12, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [6a9842e166](https://linux-hardware.org/?probe=6a9842e166) | Sep 06, 2021 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [752964e357](https://linux-hardware.org/?probe=752964e357) | Sep 05, 2021 |
| ASUSTek       | X456UQ                      | Notebook    | [6ce8e44ad3](https://linux-hardware.org/?probe=6ce8e44ad3) | Sep 02, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [7a654e5473](https://linux-hardware.org/?probe=7a654e5473) | Aug 28, 2021 |
| Acer          | Aspire 4349                 | Notebook    | [527e511232](https://linux-hardware.org/?probe=527e511232) | Aug 27, 2021 |
| Gigabyte      | B250M-Gaming5-CF            | Desktop     | [c34514576a](https://linux-hardware.org/?probe=c34514576a) | Aug 17, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [460fc8dfd4](https://linux-hardware.org/?probe=460fc8dfd4) | Aug 08, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [48853e253b](https://linux-hardware.org/?probe=48853e253b) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | Notebook    | [c22e4ce5b4](https://linux-hardware.org/?probe=c22e4ce5b4) | Jul 29, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| ASUSTek       | X550JK                      | Notebook    | [ebd01f2605](https://linux-hardware.org/?probe=ebd01f2605) | Jul 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6dea4c88d](https://linux-hardware.org/?probe=c6dea4c88d) | Jul 19, 2021 |
| Biostar       | TZ68K+                      | Desktop     | [52ef8197ad](https://linux-hardware.org/?probe=52ef8197ad) | Jul 13, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [3b153ae2f9](https://linux-hardware.org/?probe=3b153ae2f9) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [988fc9a599](https://linux-hardware.org/?probe=988fc9a599) | Jun 24, 2021 |
| HP            | 15                          | Notebook    | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [406cb898f1](https://linux-hardware.org/?probe=406cb898f1) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [1927d0abfe](https://linux-hardware.org/?probe=1927d0abfe) | Jun 13, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [23e735bb8f](https://linux-hardware.org/?probe=23e735bb8f) | Jun 08, 2021 |
| Dell          | 0VHWTR A02                  | Desktop     | [ec7174828a](https://linux-hardware.org/?probe=ec7174828a) | Jun 04, 2021 |
| ASUSTek       | UX310UAK                    | Notebook    | [4a79148721](https://linux-hardware.org/?probe=4a79148721) | Jun 03, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6b5f1170f9](https://linux-hardware.org/?probe=6b5f1170f9) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [e2389864db](https://linux-hardware.org/?probe=e2389864db) | Jun 02, 2021 |
| HP            | ENVY TS 14 Sleekbook        | Notebook    | [f52091e51e](https://linux-hardware.org/?probe=f52091e51e) | May 31, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [0226c84811](https://linux-hardware.org/?probe=0226c84811) | May 25, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [b2c4e6f3a5](https://linux-hardware.org/?probe=b2c4e6f3a5) | May 25, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [b34d6d63d9](https://linux-hardware.org/?probe=b34d6d63d9) | May 22, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [4d2529b647](https://linux-hardware.org/?probe=4d2529b647) | May 22, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [8f1510061b](https://linux-hardware.org/?probe=8f1510061b) | May 18, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [e78b76fcf3](https://linux-hardware.org/?probe=e78b76fcf3) | May 18, 2021 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [aba051d387](https://linux-hardware.org/?probe=aba051d387) | May 15, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [fa9f8b7f7e](https://linux-hardware.org/?probe=fa9f8b7f7e) | May 10, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db1a234412](https://linux-hardware.org/?probe=db1a234412) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [b7e4895fd8](https://linux-hardware.org/?probe=b7e4895fd8) | May 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [1254eab2b7](https://linux-hardware.org/?probe=1254eab2b7) | May 04, 2021 |
| HP            | 15                          | Notebook    | [fd4d562cd2](https://linux-hardware.org/?probe=fd4d562cd2) | May 04, 2021 |
| MSI           | Summit B14 A11MOT           | Notebook    | [9bdd91f198](https://linux-hardware.org/?probe=9bdd91f198) | May 02, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [dbcbb68258](https://linux-hardware.org/?probe=dbcbb68258) | Apr 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [b2600d2372](https://linux-hardware.org/?probe=b2600d2372) | Apr 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [367455807e](https://linux-hardware.org/?probe=367455807e) | Mar 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1de185d0da](https://linux-hardware.org/?probe=1de185d0da) | Mar 22, 2021 |
| Dell          | Latitude E4300              | Notebook    | [2ccfcf6a1b](https://linux-hardware.org/?probe=2ccfcf6a1b) | Mar 22, 2021 |
| HP            | 15                          | Notebook    | [860412bddc](https://linux-hardware.org/?probe=860412bddc) | Mar 20, 2021 |
| HP            | 15                          | Notebook    | [62447250f9](https://linux-hardware.org/?probe=62447250f9) | Mar 17, 2021 |
| HP            | 15                          | Notebook    | [2313114b6e](https://linux-hardware.org/?probe=2313114b6e) | Mar 17, 2021 |
| ASUSTek       | H110M-CS                    | Desktop     | [ac52c3630c](https://linux-hardware.org/?probe=ac52c3630c) | Mar 12, 2021 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | Notebook    | [4ee1271923](https://linux-hardware.org/?probe=4ee1271923) | Mar 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [6343267ab7](https://linux-hardware.org/?probe=6343267ab7) | Mar 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [47123299d4](https://linux-hardware.org/?probe=47123299d4) | Mar 09, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [a8091a8c28](https://linux-hardware.org/?probe=a8091a8c28) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8f8fe2c911](https://linux-hardware.org/?probe=8f8fe2c911) | Mar 06, 2021 |
| ASUSTek       | X411UNV                     | Notebook    | [009f3bb5e5](https://linux-hardware.org/?probe=009f3bb5e5) | Feb 27, 2021 |
| HP            | 15                          | Notebook    | [e74fa488e9](https://linux-hardware.org/?probe=e74fa488e9) | Feb 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| ASUSTek       | ZenBook UX461FA_UX461FA     | Convertible | [8efc8caada](https://linux-hardware.org/?probe=8efc8caada) | Feb 27, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [b414109f66](https://linux-hardware.org/?probe=b414109f66) | Feb 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [08a1160725](https://linux-hardware.org/?probe=08a1160725) | Feb 07, 2021 |
| HP            | Notebook                    | Notebook    | [df39c8aaf8](https://linux-hardware.org/?probe=df39c8aaf8) | Feb 02, 2021 |
| ASUSTek       | X45C                        | Notebook    | [349beec2d5](https://linux-hardware.org/?probe=349beec2d5) | Jan 27, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [474d61d1a7](https://linux-hardware.org/?probe=474d61d1a7) | Jan 27, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [c9e8f99464](https://linux-hardware.org/?probe=c9e8f99464) | Jan 21, 2021 |
| Lenovo        | ThinkPad T450 20BUS2021M    | Notebook    | [60929bb3d1](https://linux-hardware.org/?probe=60929bb3d1) | Jan 21, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [32878b3dae](https://linux-hardware.org/?probe=32878b3dae) | Jan 20, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [03b73f8223](https://linux-hardware.org/?probe=03b73f8223) | Jan 20, 2021 |
| HP            | Notebook                    | Notebook    | [d14d8fe5db](https://linux-hardware.org/?probe=d14d8fe5db) | Jan 19, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [0bfbe639fc](https://linux-hardware.org/?probe=0bfbe639fc) | Jan 18, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [e053ef39b6](https://linux-hardware.org/?probe=e053ef39b6) | Jan 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [5ee0809420](https://linux-hardware.org/?probe=5ee0809420) | Jan 16, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [4c2ddc3c14](https://linux-hardware.org/?probe=4c2ddc3c14) | Jan 10, 2021 |
| HP            | 15                          | Notebook    | [1b3597829c](https://linux-hardware.org/?probe=1b3597829c) | Jan 05, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [150aed5937](https://linux-hardware.org/?probe=150aed5937) | Dec 28, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [f3aaccf16d](https://linux-hardware.org/?probe=f3aaccf16d) | Dec 19, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [eff007611b](https://linux-hardware.org/?probe=eff007611b) | Dec 16, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [1eec63b277](https://linux-hardware.org/?probe=1eec63b277) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| MSI           | GS63 7RD                    | Notebook    | [51929f5d16](https://linux-hardware.org/?probe=51929f5d16) | Dec 05, 2020 |
| HP            | 15                          | Notebook    | [dc1ee023a1](https://linux-hardware.org/?probe=dc1ee023a1) | Nov 30, 2020 |
| HP            | 15                          | Notebook    | [c23988dc61](https://linux-hardware.org/?probe=c23988dc61) | Nov 26, 2020 |
| HP            | 15                          | Notebook    | [86cae084f4](https://linux-hardware.org/?probe=86cae084f4) | Nov 23, 2020 |
| HP            | 15                          | Notebook    | [314db0144d](https://linux-hardware.org/?probe=314db0144d) | Nov 23, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [983f59c8ba](https://linux-hardware.org/?probe=983f59c8ba) | Nov 17, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [4d0297d500](https://linux-hardware.org/?probe=4d0297d500) | Nov 15, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [2898db77af](https://linux-hardware.org/?probe=2898db77af) | Nov 14, 2020 |
| HP            | 15                          | Notebook    | [95c88a477d](https://linux-hardware.org/?probe=95c88a477d) | Nov 06, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [399693b152](https://linux-hardware.org/?probe=399693b152) | Nov 04, 2020 |
| HP            | 15                          | Notebook    | [751dbba280](https://linux-hardware.org/?probe=751dbba280) | Nov 04, 2020 |
| Unknown       | Unknown                     | Desktop     | [49351fb74d](https://linux-hardware.org/?probe=49351fb74d) | Nov 03, 2020 |
| Unknown       | Unknown                     | Desktop     | [a5450c668e](https://linux-hardware.org/?probe=a5450c668e) | Oct 30, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [7e48c5dac7](https://linux-hardware.org/?probe=7e48c5dac7) | Oct 30, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [20da8831d7](https://linux-hardware.org/?probe=20da8831d7) | Oct 29, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [6abbe0be7c](https://linux-hardware.org/?probe=6abbe0be7c) | Oct 29, 2020 |
| Notebook      | DCL C483                    | Notebook    | [ed2bb10c86](https://linux-hardware.org/?probe=ed2bb10c86) | Oct 29, 2020 |
| ASUSTek       | H110M-CS                    | Desktop     | [4bc7a25c4b](https://linux-hardware.org/?probe=4bc7a25c4b) | Oct 29, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [7a6ee90819](https://linux-hardware.org/?probe=7a6ee90819) | Oct 29, 2020 |
| HP            | ENVY Sleekbook 4            | Notebook    | [b2377a6388](https://linux-hardware.org/?probe=b2377a6388) | Oct 29, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [1f7d96b34a](https://linux-hardware.org/?probe=1f7d96b34a) | Oct 27, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [76e61701fa](https://linux-hardware.org/?probe=76e61701fa) | Oct 24, 2020 |
| ASUSTek       | P453UA                      | Notebook    | [a376addbeb](https://linux-hardware.org/?probe=a376addbeb) | Oct 21, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [218b3ce742](https://linux-hardware.org/?probe=218b3ce742) | Oct 12, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [da1765fe36](https://linux-hardware.org/?probe=da1765fe36) | Oct 11, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [a9c53146fc](https://linux-hardware.org/?probe=a9c53146fc) | Oct 10, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [be8091856c](https://linux-hardware.org/?probe=be8091856c) | Oct 09, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [a6f1865423](https://linux-hardware.org/?probe=a6f1865423) | Oct 07, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [75933321b6](https://linux-hardware.org/?probe=75933321b6) | Oct 02, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [ae7fe5907d](https://linux-hardware.org/?probe=ae7fe5907d) | Sep 27, 2020 |
| ASUSTek       | X555LF                      | Notebook    | [ed0ef70a05](https://linux-hardware.org/?probe=ed0ef70a05) | Sep 19, 2020 |
| Gigabyte      | GA-E350N                    | Desktop     | [871d27c2e8](https://linux-hardware.org/?probe=871d27c2e8) | Sep 18, 2020 |
| Gigabyte      | GA-E350N                    | Desktop     | [3f442c236c](https://linux-hardware.org/?probe=3f442c236c) | Sep 18, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [d7b1ce1a01](https://linux-hardware.org/?probe=d7b1ce1a01) | Sep 15, 2020 |
| Notebook      | N2x0LU                      | Notebook    | [86354a1c26](https://linux-hardware.org/?probe=86354a1c26) | Sep 14, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [e289d19d20](https://linux-hardware.org/?probe=e289d19d20) | Sep 14, 2020 |
| ASRock        | Z77 Pro3                    | Desktop     | [8d6db6e2d3](https://linux-hardware.org/?probe=8d6db6e2d3) | Sep 09, 2020 |
| ASUSTek       | X555LF                      | Notebook    | [22629ba9b2](https://linux-hardware.org/?probe=22629ba9b2) | Sep 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | Notebook    | [43ddcf3c95](https://linux-hardware.org/?probe=43ddcf3c95) | Sep 06, 2020 |
| Unknown       | Unknown                     | Phone       | [d4a5776865](https://linux-hardware.org/?probe=d4a5776865) | Sep 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [38548d7877](https://linux-hardware.org/?probe=38548d7877) | Sep 01, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [3edf866f94](https://linux-hardware.org/?probe=3edf866f94) | Aug 22, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [6c9f54a608](https://linux-hardware.org/?probe=6c9f54a608) | Aug 16, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [3a9beeb9f4](https://linux-hardware.org/?probe=3a9beeb9f4) | Aug 16, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [3c3b21f81b](https://linux-hardware.org/?probe=3c3b21f81b) | Aug 15, 2020 |
| HP            | 14                          | Notebook    | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| SYS           | H310CH5-TI2                 | Desktop     | [fb33742784](https://linux-hardware.org/?probe=fb33742784) | Aug 06, 2020 |
| HP            | EliteBook 850 G2            | Notebook    | [1c81c3c24d](https://linux-hardware.org/?probe=1c81c3c24d) | Jul 30, 2020 |
| Acer          | Aspire E5-473               | Notebook    | [27a9cd08a6](https://linux-hardware.org/?probe=27a9cd08a6) | Jul 26, 2020 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [f1ef1518c4](https://linux-hardware.org/?probe=f1ef1518c4) | Jul 25, 2020 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [bf80f266b6](https://linux-hardware.org/?probe=bf80f266b6) | Jul 25, 2020 |
| Acer          | Aspire E5-473               | Notebook    | [9c3656a710](https://linux-hardware.org/?probe=9c3656a710) | Jul 24, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [3c50b289eb](https://linux-hardware.org/?probe=3c50b289eb) | Jul 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e800855127](https://linux-hardware.org/?probe=e800855127) | Jul 21, 2020 |
| Dell          | Latitude E7470              | Notebook    | [74e59971a2](https://linux-hardware.org/?probe=74e59971a2) | Jul 09, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [eb79a1863c](https://linux-hardware.org/?probe=eb79a1863c) | Jul 08, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [374493e07f](https://linux-hardware.org/?probe=374493e07f) | Jul 08, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [04f260c99a](https://linux-hardware.org/?probe=04f260c99a) | Jul 06, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [aa5a987949](https://linux-hardware.org/?probe=aa5a987949) | Jul 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [e8be3d4a45](https://linux-hardware.org/?probe=e8be3d4a45) | Jul 02, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [d59cf3e39f](https://linux-hardware.org/?probe=d59cf3e39f) | Jun 21, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | Notebook    | [bedb334316](https://linux-hardware.org/?probe=bedb334316) | Jun 11, 2020 |
| Gigabyte      | B75MS                       | Desktop     | [116d7e4473](https://linux-hardware.org/?probe=116d7e4473) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [0690307575](https://linux-hardware.org/?probe=0690307575) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [2d68573dcb](https://linux-hardware.org/?probe=2d68573dcb) | Jun 04, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [24ebee7f8d](https://linux-hardware.org/?probe=24ebee7f8d) | Jun 03, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e10a133997](https://linux-hardware.org/?probe=e10a133997) | Jun 02, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [7b57cf3668](https://linux-hardware.org/?probe=7b57cf3668) | May 30, 2020 |
| ASUSTek       | H61M-A                      | Desktop     | [821df8e348](https://linux-hardware.org/?probe=821df8e348) | May 25, 2020 |
| ASUSTek       | H61M-A                      | Desktop     | [6118e39327](https://linux-hardware.org/?probe=6118e39327) | May 25, 2020 |
| HP            | Notebook                    | Notebook    | [024a28eb0b](https://linux-hardware.org/?probe=024a28eb0b) | May 23, 2020 |
| Dell          | Latitude E7450              | Notebook    | [f3e9ca7a40](https://linux-hardware.org/?probe=f3e9ca7a40) | May 21, 2020 |
| Lenovo        | ThinkPad E470 20H1A029SG    | Notebook    | [6afaed7f7f](https://linux-hardware.org/?probe=6afaed7f7f) | May 21, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e6818ffd7d](https://linux-hardware.org/?probe=e6818ffd7d) | May 21, 2020 |
| Notebook      | W9x0LU                      | Notebook    | [c7455fcb18](https://linux-hardware.org/?probe=c7455fcb18) | May 17, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [5d81beb457](https://linux-hardware.org/?probe=5d81beb457) | May 17, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [7b1a18ebf9](https://linux-hardware.org/?probe=7b1a18ebf9) | May 09, 2020 |
| ASUSTek       | X556URK                     | Notebook    | [63c6b5a357](https://linux-hardware.org/?probe=63c6b5a357) | May 08, 2020 |
| Foxconn       | 17A0                        | Desktop     | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| Notebook      | N750BU                      | Notebook    | [e3f870729f](https://linux-hardware.org/?probe=e3f870729f) | Apr 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [de6fa960ad](https://linux-hardware.org/?probe=de6fa960ad) | Apr 23, 2020 |
| I-Life Dig... | ZED_AIR_PLUS                | Convertible | [b1a911e13e](https://linux-hardware.org/?probe=b1a911e13e) | Mar 27, 2020 |
| MSI           | H61M-P31/W8                 | Desktop     | [26d8323c91](https://linux-hardware.org/?probe=26d8323c91) | Mar 25, 2020 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [4da5909f03](https://linux-hardware.org/?probe=4da5909f03) | Mar 24, 2020 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [baa90e0762](https://linux-hardware.org/?probe=baa90e0762) | Mar 22, 2020 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | Desktop     | [34ced022e3](https://linux-hardware.org/?probe=34ced022e3) | Feb 29, 2020 |
| HP            | Mini 210-4000               | Notebook    | [61c0ab33d8](https://linux-hardware.org/?probe=61c0ab33d8) | Feb 28, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [729f8e494d](https://linux-hardware.org/?probe=729f8e494d) | Feb 14, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [357823f120](https://linux-hardware.org/?probe=357823f120) | Feb 03, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e9a4da7f1c](https://linux-hardware.org/?probe=e9a4da7f1c) | Jan 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [4fad937155](https://linux-hardware.org/?probe=4fad937155) | Jan 10, 2020 |
| Lenovo        | ThinkPad L380 20M6S22500    | Notebook    | [15c43def70](https://linux-hardware.org/?probe=15c43def70) | Jan 09, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [9d4e0d1911](https://linux-hardware.org/?probe=9d4e0d1911) | Jan 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [2d0bca85ea](https://linux-hardware.org/?probe=2d0bca85ea) | Dec 29, 2019 |
| Gigabyte      | B85M-D3H                    | Desktop     | [753205d5df](https://linux-hardware.org/?probe=753205d5df) | Dec 27, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [d85b25cd22](https://linux-hardware.org/?probe=d85b25cd22) | Dec 24, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [30c00cb837](https://linux-hardware.org/?probe=30c00cb837) | Dec 14, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [e004d9f500](https://linux-hardware.org/?probe=e004d9f500) | Dec 14, 2019 |
| ASUSTek       | E202SA                      | Notebook    | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [44d09b2105](https://linux-hardware.org/?probe=44d09b2105) | Nov 19, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [3fc910f23c](https://linux-hardware.org/?probe=3fc910f23c) | Nov 19, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [afc9fdb4b3](https://linux-hardware.org/?probe=afc9fdb4b3) | Nov 14, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [7914862967](https://linux-hardware.org/?probe=7914862967) | Nov 14, 2019 |
| MSI           | PH67A-C43                   | Desktop     | [b472118c5a](https://linux-hardware.org/?probe=b472118c5a) | Oct 29, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [73a0de63c0](https://linux-hardware.org/?probe=73a0de63c0) | Sep 27, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [4299e1c036](https://linux-hardware.org/?probe=4299e1c036) | Sep 27, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [1f5846e43d](https://linux-hardware.org/?probe=1f5846e43d) | Sep 27, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [f0ec7fa44d](https://linux-hardware.org/?probe=f0ec7fa44d) | Sep 27, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [671ea53b31](https://linux-hardware.org/?probe=671ea53b31) | Sep 22, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [53b4bf1914](https://linux-hardware.org/?probe=53b4bf1914) | Sep 22, 2019 |
| ASUSTek       | X441UA                      | Notebook    | [6022620aee](https://linux-hardware.org/?probe=6022620aee) | Sep 17, 2019 |
| ASUSTek       | X441UA                      | Notebook    | [d0632368ab](https://linux-hardware.org/?probe=d0632368ab) | Sep 04, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [ede7f2c199](https://linux-hardware.org/?probe=ede7f2c199) | Aug 30, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [e3c13fc2d8](https://linux-hardware.org/?probe=e3c13fc2d8) | Aug 20, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d0d6cd20b1](https://linux-hardware.org/?probe=d0d6cd20b1) | Jul 26, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [f9b65f1415](https://linux-hardware.org/?probe=f9b65f1415) | Jul 14, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a6f5bc1b0f](https://linux-hardware.org/?probe=a6f5bc1b0f) | Jul 13, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [0110b6895b](https://linux-hardware.org/?probe=0110b6895b) | Jul 13, 2019 |
| HP            | Notebook                    | Notebook    | [2ce0b2ff35](https://linux-hardware.org/?probe=2ce0b2ff35) | Jul 04, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [298e510c05](https://linux-hardware.org/?probe=298e510c05) | Jun 22, 2019 |
| Lenovo        | ThinkPad X230 2324F51       | Notebook    | [9291e8f5f3](https://linux-hardware.org/?probe=9291e8f5f3) | Jun 22, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [70fecd4e42](https://linux-hardware.org/?probe=70fecd4e42) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [ee5c9fcc02](https://linux-hardware.org/?probe=ee5c9fcc02) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [424ee39d57](https://linux-hardware.org/?probe=424ee39d57) | Jun 04, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [37a334e523](https://linux-hardware.org/?probe=37a334e523) | Jun 02, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [cb301afe49](https://linux-hardware.org/?probe=cb301afe49) | Jun 02, 2019 |
| Lenovo        | S10-3                       | Notebook    | [09f132c2fa](https://linux-hardware.org/?probe=09f132c2fa) | May 27, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [24c1251a9a](https://linux-hardware.org/?probe=24c1251a9a) | May 09, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [0f42a3ea73](https://linux-hardware.org/?probe=0f42a3ea73) | May 09, 2019 |
| Daffodil C... | DCL S4                      | Notebook    | [291cd2445c](https://linux-hardware.org/?probe=291cd2445c) | May 08, 2019 |
| HP            | ProBook 4540s               | Notebook    | [a8b0fbe3a8](https://linux-hardware.org/?probe=a8b0fbe3a8) | Apr 22, 2019 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [83303ad448](https://linux-hardware.org/?probe=83303ad448) | Apr 07, 2019 |
| Intel         | Board                       | Desktop     | [6abdeb3169](https://linux-hardware.org/?probe=6abdeb3169) | Mar 10, 2019 |
| Intel         | Board                       | Desktop     | [d27842b77f](https://linux-hardware.org/?probe=d27842b77f) | Mar 10, 2019 |
| Intel         | Board                       | Desktop     | [1c484063a6](https://linux-hardware.org/?probe=1c484063a6) | Mar 09, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| MSI           | P55A-G55                    | Desktop     | [8bc6ce2174](https://linux-hardware.org/?probe=8bc6ce2174) | Dec 08, 2018 |
| MSI           | P55A-G55                    | Desktop     | [24654f4990](https://linux-hardware.org/?probe=24654f4990) | Dec 07, 2018 |
| Gigabyte      | P55-USB3                    | Desktop     | [3cf949c024](https://linux-hardware.org/?probe=3cf949c024) | Jul 21, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 43        | 19.63%  |
| Ubuntu 18.04      | 11        | 5.02%   |
| Arch              | 10        | 4.57%   |
| ArcoLinux Rolling | 9         | 4.11%   |
| Ubuntu 19.10      | 8         | 3.65%   |
| Zorin 15          | 5         | 2.28%   |
| OpenMandriva 4.2  | 5         | 2.28%   |
| Manjaro           | 5         | 2.28%   |
| KDE neon 20.04    | 5         | 2.28%   |
| Fedora 33         | 5         | 2.28%   |
| Debian 11         | 5         | 2.28%   |
| Manjaro 20.0.1    | 4         | 1.83%   |
| Linux Mint 20.2   | 4         | 1.83%   |
| Zorin 16          | 3         | 1.37%   |
| Ubuntu 19.04      | 3         | 1.37%   |
| Pop!_OS 21.10     | 3         | 1.37%   |
| Pop!_OS 21.04     | 3         | 1.37%   |
| Manjaro 20.1.2    | 3         | 1.37%   |
| Linux Mint 20.1   | 3         | 1.37%   |
| Linux Mint 20     | 3         | 1.37%   |
| Kubuntu 20.04     | 3         | 1.37%   |
| Ubuntu 22.04      | 2         | 0.91%   |
| Ubuntu 21.04      | 2         | 0.91%   |
| Ubuntu 20.10      | 2         | 0.91%   |
| Ubuntu 18.10      | 2         | 0.91%   |
| Ubuntu 16.04      | 2         | 0.91%   |
| Pop!_OS 20.10     | 2         | 0.91%   |
| OpenMandriva 4.3  | 2         | 0.91%   |
| Manjaro 21.0.3    | 2         | 0.91%   |
| Manjaro 18.0.4    | 2         | 0.91%   |
| LMDE 4            | 2         | 0.91%   |
| Fedora 34         | 2         | 0.91%   |
| Fedora 32         | 2         | 0.91%   |
| CentOS 8          | 2         | 0.91%   |
| BlackPanther 18.1 | 2         | 0.91%   |
| Arch Rolling      | 2         | 0.91%   |
| Void Linux        | 1         | 0.46%   |
| Ubuntu MATE 18.04 | 1         | 0.46%   |
| Ubuntu 21.10      | 1         | 0.46%   |
| Ubuntu 17.10      | 1         | 0.46%   |
| ROSA R9           | 1         | 0.46%   |
| Pragma            | 1         | 0.46%   |
| Pop!_OS 20.04     | 1         | 0.46%   |
| Parrot 4.5        | 1         | 0.46%   |
| Parrot 4.11       | 1         | 0.46%   |
| Parrot 4.10       | 1         | 0.46%   |
| openSUSE 20201005 | 1         | 0.46%   |
| Manjaro 21.2.5    | 1         | 0.46%   |
| Manjaro 21.2.1    | 1         | 0.46%   |
| Manjaro 21.1.2    | 1         | 0.46%   |
| Manjaro 21.1.0    | 1         | 0.46%   |
| Manjaro 21.0.5    | 1         | 0.46%   |
| Manjaro 21.0.4    | 1         | 0.46%   |
| Manjaro 21.0      | 1         | 0.46%   |
| Manjaro 20.2.1    | 1         | 0.46%   |
| Manjaro 20.2      | 1         | 0.46%   |
| Manjaro 20.1.1    | 1         | 0.46%   |
| Manjaro 20.1      | 1         | 0.46%   |
| Manjaro 18.1.5    | 1         | 0.46%   |
| Linux Mint 19.3   | 1         | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 76        | 37.44%  |
| Manjaro      | 21        | 10.34%  |
| Arch         | 12        | 5.91%   |
| Linux Mint   | 11        | 5.42%   |
| Fedora       | 9         | 4.43%   |
| ArcoLinux    | 9         | 4.43%   |
| Zorin        | 8         | 3.94%   |
| Pop!_OS      | 7         | 3.45%   |
| OpenMandriva | 7         | 3.45%   |
| Kubuntu      | 6         | 2.96%   |
| Debian       | 6         | 2.96%   |
| KDE neon     | 5         | 2.46%   |
| Endless      | 4         | 1.97%   |
| Parrot       | 2         | 0.99%   |
| LMDE         | 2         | 0.99%   |
| Deepin       | 2         | 0.99%   |
| CentOS       | 2         | 0.99%   |
| BlackPanther | 2         | 0.99%   |
| Void Linux   | 1         | 0.49%   |
| Ubuntu MATE  | 1         | 0.49%   |
| ROSA         | 1         | 0.49%   |
| Pragma       | 1         | 0.49%   |
| openSUSE     | 1         | 0.49%   |
| Kali         | 1         | 0.49%   |
| Gentoo       | 1         | 0.49%   |
| EndeavourOS  | 1         | 0.49%   |
| Elementary   | 1         | 0.49%   |
| Clear Linux  | 1         | 0.49%   |
| Artix        | 1         | 0.49%   |
| Android      | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.4.0-42-generic          | 8         | 3.32%   |
| 5.4.0-52-generic          | 7         | 2.9%    |
| 5.10.14-desktop-1omv4002  | 5         | 2.07%   |
| 5.13.0-28-generic         | 4         | 1.66%   |
| 5.9.16-1-MANJARO          | 3         | 1.24%   |
| 5.8.0-55-generic          | 3         | 1.24%   |
| 5.8.0-41-generic          | 3         | 1.24%   |
| 5.6.11-1-MANJARO          | 3         | 1.24%   |
| 5.4.0-53-generic          | 3         | 1.24%   |
| 5.4.0-40-generic          | 3         | 1.24%   |
| 5.4.0-29-generic          | 3         | 1.24%   |
| 5.11.0-37-generic         | 3         | 1.24%   |
| 5.11.0-16-generic         | 3         | 1.24%   |
| 5.8.16-2-MANJARO          | 2         | 0.83%   |
| 5.8.0-50-generic          | 2         | 0.83%   |
| 5.8.0-44-generic          | 2         | 0.83%   |
| 5.8.0-38-generic          | 2         | 0.83%   |
| 5.8.0-14-generic          | 2         | 0.83%   |
| 5.7.19-2-MANJARO          | 2         | 0.83%   |
| 5.4.8-arch1-1             | 2         | 0.83%   |
| 5.4.0-90-generic          | 2         | 0.83%   |
| 5.4.0-73-generic          | 2         | 0.83%   |
| 5.4.0-47-generic          | 2         | 0.83%   |
| 5.4.0-26-generic          | 2         | 0.83%   |
| 5.4.0-19-generic          | 2         | 0.83%   |
| 5.3.0-40-generic          | 2         | 0.83%   |
| 5.3.0-24-generic          | 2         | 0.83%   |
| 5.3.0-23-generic          | 2         | 0.83%   |
| 5.3.0-18-generic          | 2         | 0.83%   |
| 5.16.7-desktop-1omv4003   | 2         | 0.83%   |
| 5.13.0-35-generic         | 2         | 0.83%   |
| 5.11.0-40-generic         | 2         | 0.83%   |
| 5.11.0-27-generic         | 2         | 0.83%   |
| 5.10.52-1-lts             | 2         | 0.83%   |
| 5.10.0-8-amd64            | 2         | 0.83%   |
| 5.10.0-10-amd64           | 2         | 0.83%   |
| 5.0.0-32-generic          | 2         | 0.83%   |
| 5.0.0-25-generic          | 2         | 0.83%   |
| 4.15.0-47-generic         | 2         | 0.83%   |
| 4.15.0-42-generic         | 2         | 0.83%   |
| 6.0.0-Phaco-g8f10ff49057f | 1         | 0.41%   |
| 5.9.16-200.fc33.x86_64    | 1         | 0.41%   |
| 5.9.11-200.fc33.x86_64    | 1         | 0.41%   |
| 5.8.6-1-MANJARO           | 1         | 0.41%   |
| 5.8.4-200.fc32.x86_64     | 1         | 0.41%   |
| 5.8.16.a-1-hardened       | 1         | 0.41%   |
| 5.8.16-300.fc33.x86_64    | 1         | 0.41%   |
| 5.8.12-1-default          | 1         | 0.41%   |
| 5.8.0-7630-generic        | 1         | 0.41%   |
| 5.8.0-63-generic          | 1         | 0.41%   |
| 5.8.0-43-generic          | 1         | 0.41%   |
| 5.8.0-40-generic          | 1         | 0.41%   |
| 5.7.17-200.fc32.x86_64    | 1         | 0.41%   |
| 5.7.15-ck                 | 1         | 0.41%   |
| 5.7.0-2parrot2-amd64      | 1         | 0.41%   |
| 5.6.15-1-MANJARO          | 1         | 0.41%   |
| 5.6.14-desktop-2bP        | 1         | 0.41%   |
| 5.4.81-1-lts              | 1         | 0.41%   |
| 5.4.70-amd64-desktop      | 1         | 0.41%   |
| 5.4.68-1-lts              | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 39        | 17.26%  |
| 5.8.0   | 18        | 7.96%   |
| 5.11.0  | 17        | 7.52%   |
| 5.3.0   | 13        | 5.75%   |
| 5.13.0  | 11        | 4.87%   |
| 5.10.0  | 7         | 3.1%    |
| 5.0.0   | 7         | 3.1%    |
| 4.18.0  | 7         | 3.1%    |
| 4.15.0  | 7         | 3.1%    |
| 5.10.14 | 5         | 2.21%   |
| 5.9.16  | 4         | 1.77%   |
| 5.8.16  | 4         | 1.77%   |
| 4.19.0  | 4         | 1.77%   |
| 5.6.11  | 3         | 1.33%   |
| 5.15.0  | 3         | 1.33%   |
| 5.7.19  | 2         | 0.88%   |
| 5.4.8   | 2         | 0.88%   |
| 5.16.7  | 2         | 0.88%   |
| 5.16.15 | 2         | 0.88%   |
| 5.16.11 | 2         | 0.88%   |
| 5.15.7  | 2         | 0.88%   |
| 5.15.5  | 2         | 0.88%   |
| 5.15.13 | 2         | 0.88%   |
| 5.11.6  | 2         | 0.88%   |
| 5.10.52 | 2         | 0.88%   |
| 6.0.0   | 1         | 0.44%   |
| 5.9.11  | 1         | 0.44%   |
| 5.8.6   | 1         | 0.44%   |
| 5.8.4   | 1         | 0.44%   |
| 5.8.12  | 1         | 0.44%   |
| 5.7.17  | 1         | 0.44%   |
| 5.7.15  | 1         | 0.44%   |
| 5.7.0   | 1         | 0.44%   |
| 5.6.15  | 1         | 0.44%   |
| 5.6.14  | 1         | 0.44%   |
| 5.4.81  | 1         | 0.44%   |
| 5.4.70  | 1         | 0.44%   |
| 5.4.68  | 1         | 0.44%   |
| 5.4.64  | 1         | 0.44%   |
| 5.4.40  | 1         | 0.44%   |
| 5.4.15  | 1         | 0.44%   |
| 5.17.1  | 1         | 0.44%   |
| 5.17.0  | 1         | 0.44%   |
| 5.16.14 | 1         | 0.44%   |
| 5.16.13 | 1         | 0.44%   |
| 5.16.12 | 1         | 0.44%   |
| 5.16.1  | 1         | 0.44%   |
| 5.16.0  | 1         | 0.44%   |
| 5.15.8  | 1         | 0.44%   |
| 5.15.6  | 1         | 0.44%   |
| 5.15.28 | 1         | 0.44%   |
| 5.15.21 | 1         | 0.44%   |
| 5.15.15 | 1         | 0.44%   |
| 5.15.12 | 1         | 0.44%   |
| 5.14.5  | 1         | 0.44%   |
| 5.14.14 | 1         | 0.44%   |
| 5.14.0  | 1         | 0.44%   |
| 5.13.6  | 1         | 0.44%   |
| 5.13.19 | 1         | 0.44%   |
| 5.12.12 | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 46        | 21.1%   |
| 5.8     | 25        | 11.47%  |
| 5.11    | 22        | 10.09%  |
| 5.10    | 19        | 8.72%   |
| 5.15    | 14        | 6.42%   |
| 5.3     | 13        | 5.96%   |
| 5.13    | 13        | 5.96%   |
| 5.16    | 10        | 4.59%   |
| 4.18    | 8         | 3.67%   |
| 5.0     | 7         | 3.21%   |
| 4.15    | 7         | 3.21%   |
| 5.9     | 5         | 2.29%   |
| 5.7     | 5         | 2.29%   |
| 5.6     | 5         | 2.29%   |
| 4.19    | 5         | 2.29%   |
| 5.14    | 3         | 1.38%   |
| 5.17    | 2         | 0.92%   |
| 5.12    | 2         | 0.92%   |
| 5.1     | 2         | 0.92%   |
| 6.0     | 1         | 0.46%   |
| 4.9     | 1         | 0.46%   |
| 4.4     | 1         | 0.46%   |
| 4.13    | 1         | 0.46%   |
| 3.18    | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 189       | 96.92%  |
| i686    | 4         | 2.05%   |
| aarch64 | 2         | 1.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 100       | 49.02%  |
| KDE5            | 36        | 17.65%  |
| Unknown         | 27        | 13.24%  |
| X-Cinnamon      | 11        | 5.39%   |
| XFCE            | 7         | 3.43%   |
| awesome         | 5         | 2.45%   |
| KDE             | 4         | 1.96%   |
| MATE            | 3         | 1.47%   |
| i3-with-shmlog  | 2         | 0.98%   |
| Deepin          | 2         | 0.98%   |
| Unity           | 1         | 0.49%   |
| Pantheon        | 1         | 0.49%   |
| i3              | 1         | 0.49%   |
| GNOME Flashback | 1         | 0.49%   |
| dwm             | 1         | 0.49%   |
| Cinnamon        | 1         | 0.49%   |
| bspwm           | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 164       | 80.79%  |
| Wayland | 21        | 10.34%  |
| Unknown | 16        | 7.88%   |
| Tty     | 2         | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 107       | 52.71%  |
| GDM     | 35        | 17.24%  |
| SDDM    | 31        | 15.27%  |
| LightDM | 12        | 5.91%   |
| TDM     | 9         | 4.43%   |
| GDM3    | 9         | 4.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 157       | 79.29%  |
| Unknown | 27        | 13.64%  |
| en_GB   | 7         | 3.54%   |
| C       | 5         | 2.53%   |
| en_IE   | 1         | 0.51%   |
| en_CA   | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 101       | 50.25%  |
| EFI  | 100       | 49.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 159       | 79.9%   |
| Overlay | 18        | 9.05%   |
| Btrfs   | 14        | 7.04%   |
| Unknown | 4         | 2.01%   |
| Xfs     | 3         | 1.51%   |
| Zfs     | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 115       | 57.21%  |
| GPT     | 67        | 33.33%  |
| MBR     | 19        | 9.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 167       | 83.5%   |
| Yes       | 33        | 16.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 51.5%   |
| Yes       | 97        | 48.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 47        | 24.1%   |
| Hewlett-Packard             | 38        | 19.49%  |
| MSI                         | 19        | 9.74%   |
| Lenovo                      | 16        | 8.21%   |
| Gigabyte Technology         | 16        | 8.21%   |
| Dell                        | 14        | 7.18%   |
| Acer                        | 12        | 6.15%   |
| Unknown                     | 7         | 3.59%   |
| ASRock                      | 5         | 2.56%   |
| Notebook                    | 4         | 2.05%   |
| Intel                       | 4         | 2.05%   |
| OEM                         | 3         | 1.54%   |
| Foxconn                     | 2         | 1.03%   |
| Biostar                     | 2         | 1.03%   |
| SYS                         | 1         | 0.51%   |
| Samsung Electronics         | 1         | 0.51%   |
| Raspberry Pi Foundation     | 1         | 0.51%   |
| I-Life Digital Technologies | 1         | 0.51%   |
| Daffodil Computers          | 1         | 0.51%   |
| Apple                       | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 8         | 4.1%    |
| HP ProBook 450 G4                                     | 5         | 2.56%   |
| MSI MS-7C52                                           | 3         | 1.54%   |
| ASUS All Series                                       | 3         | 1.54%   |
| OEM Intel H81                                         | 2         | 1.03%   |
| MSI MS-7B89                                           | 2         | 1.03%   |
| MSI MS-7668                                           | 2         | 1.03%   |
| Intel DG41RQ AAE54511-203                             | 2         | 1.03%   |
| HP ProBook 450 G2                                     | 2         | 1.03%   |
| HP Notebook                                           | 2         | 1.03%   |
| HP EliteBook 840 G3                                   | 2         | 1.03%   |
| ASUS X510UQ                                           | 2         | 1.03%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 1.03%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 1.03%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 1.03%   |
| SYS H310CH5-TI2                                       | 1         | 0.51%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.51%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 1         | 0.51%   |
| Notebook W9x0LU                                       | 1         | 0.51%   |
| Notebook N750BU                                       | 1         | 0.51%   |
| Notebook N2x0LU                                       | 1         | 0.51%   |
| Notebook DCL C483                                     | 1         | 0.51%   |
| MSI Summit B14 A11MOT                                 | 1         | 0.51%   |
| MSI MS-7C91                                           | 1         | 0.51%   |
| MSI MS-7C88                                           | 1         | 0.51%   |
| MSI MS-7C08                                           | 1         | 0.51%   |
| MSI MS-7B79                                           | 1         | 0.51%   |
| MSI MS-7823                                           | 1         | 0.51%   |
| MSI MS-7788                                           | 1         | 0.51%   |
| MSI MS-7721                                           | 1         | 0.51%   |
| MSI MS-7673                                           | 1         | 0.51%   |
| MSI MS-7640                                           | 1         | 0.51%   |
| MSI KY722AA-AB4 CQ3012L                               | 1         | 0.51%   |
| MSI GS63 7RD                                          | 1         | 0.51%   |
| Lenovo V330-14IKB 81B0                                | 1         | 0.51%   |
| Lenovo ThinkPad X230 2324F51                          | 1         | 0.51%   |
| Lenovo ThinkPad X230 2324A82                          | 1         | 0.51%   |
| Lenovo ThinkPad T450 20BUS2021M                       | 1         | 0.51%   |
| Lenovo ThinkPad T430s 2356GPU                         | 1         | 0.51%   |
| Lenovo ThinkPad L380 20M6S22500                       | 1         | 0.51%   |
| Lenovo ThinkPad E490 20N9S1XE00                       | 1         | 0.51%   |
| Lenovo ThinkPad E470 20H1A029SG                       | 1         | 0.51%   |
| Lenovo S10-3                                          | 1         | 0.51%   |
| Lenovo Legion 5 15ARH05H 82B1                         | 1         | 0.51%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                      | 1         | 0.51%   |
| Lenovo IdeaPad 330-15IKB 81DE                         | 1         | 0.51%   |
| Lenovo IdeaPad 320-15IKB 81BG                         | 1         | 0.51%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.51%   |
| Lenovo IdeaPad 310-14ISK 80SL                         | 1         | 0.51%   |
| Lenovo IdeaPad 110-15IBR 80T7                         | 1         | 0.51%   |
| Intel DG31PR AAD97573-302                             | 1         | 0.51%   |
| Intel Board                                           | 1         | 0.51%   |
| I-Life Digital ZED_AIR_PLUS                           | 1         | 0.51%   |
| HP ZHAN 66 Pro A 14 G4 Notebook PC                    | 1         | 0.51%   |
| HP ProBook 4540s                                      | 1         | 0.51%   |
| HP ProBook 450 G8 Notebook PC                         | 1         | 0.51%   |
| HP ProBook 450 G5                                     | 1         | 0.51%   |
| HP ProBook 450 G1                                     | 1         | 0.51%   |
| HP ProBook 440 G7                                     | 1         | 0.51%   |
| HP ProBook 440 G6                                     | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS VivoBook      | 16        | 8.21%   |
| HP ProBook         | 14        | 7.18%   |
| Acer Aspire        | 10        | 5.13%   |
| Unknown            | 8         | 4.1%    |
| Lenovo ThinkPad    | 7         | 3.59%   |
| Dell Inspiron      | 7         | 3.59%   |
| Lenovo IdeaPad     | 6         | 3.08%   |
| HP EliteBook       | 6         | 3.08%   |
| Dell Latitude      | 5         | 2.56%   |
| MSI MS-7C52        | 3         | 1.54%   |
| ASUS TUF           | 3         | 1.54%   |
| ASUS All           | 3         | 1.54%   |
| OEM Intel          | 2         | 1.03%   |
| MSI MS-7B89        | 2         | 1.03%   |
| MSI MS-7668        | 2         | 1.03%   |
| Intel DG41RQ       | 2         | 1.03%   |
| HP Pavilion        | 2         | 1.03%   |
| HP Notebook        | 2         | 1.03%   |
| HP Laptop          | 2         | 1.03%   |
| HP ENVY            | 2         | 1.03%   |
| HP Compaq          | 2         | 1.03%   |
| HP 15              | 2         | 1.03%   |
| ASUS ZenBook       | 2         | 1.03%   |
| ASUS X510UQ        | 2         | 1.03%   |
| SYS H310CH5-TI2    | 1         | 0.51%   |
| Samsung 300E5EV    | 1         | 0.51%   |
| RPi Raspberry      | 1         | 0.51%   |
| Notebook W9x0LU    | 1         | 0.51%   |
| Notebook N750BU    | 1         | 0.51%   |
| Notebook N2x0LU    | 1         | 0.51%   |
| Notebook DCL       | 1         | 0.51%   |
| MSI Summit         | 1         | 0.51%   |
| MSI MS-7C91        | 1         | 0.51%   |
| MSI MS-7C88        | 1         | 0.51%   |
| MSI MS-7C08        | 1         | 0.51%   |
| MSI MS-7B79        | 1         | 0.51%   |
| MSI MS-7823        | 1         | 0.51%   |
| MSI MS-7788        | 1         | 0.51%   |
| MSI MS-7721        | 1         | 0.51%   |
| MSI MS-7673        | 1         | 0.51%   |
| MSI MS-7640        | 1         | 0.51%   |
| MSI KY722AA-AB4    | 1         | 0.51%   |
| MSI GS63           | 1         | 0.51%   |
| Lenovo V330-14IKB  | 1         | 0.51%   |
| Lenovo S10-3       | 1         | 0.51%   |
| Lenovo Legion      | 1         | 0.51%   |
| Intel DG31PR       | 1         | 0.51%   |
| Intel Board        | 1         | 0.51%   |
| I-Life Digital ZED | 1         | 0.51%   |
| HP ZHAN            | 1         | 0.51%   |
| HP Mini            | 1         | 0.51%   |
| HP Elite           | 1         | 0.51%   |
| HP 250             | 1         | 0.51%   |
| HP 240             | 1         | 0.51%   |
| HP 14              | 1         | 0.51%   |
| Gigabyte X299      | 1         | 0.51%   |
| Gigabyte P55-USB3  | 1         | 0.51%   |
| Gigabyte H81M-S    | 1         | 0.51%   |
| Gigabyte H61M-S2PV | 1         | 0.51%   |
| Gigabyte GA-E350N  | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 27        | 13.85%  |
| 2017    | 27        | 13.85%  |
| 2016    | 23        | 11.79%  |
| 2018    | 22        | 11.28%  |
| 2012    | 19        | 9.74%   |
| 2015    | 18        | 9.23%   |
| 2013    | 12        | 6.15%   |
| 2014    | 11        | 5.64%   |
| 2021    | 8         | 4.1%    |
| 2011    | 8         | 4.1%    |
| 2010    | 6         | 3.08%   |
| 2020    | 5         | 2.56%   |
| 2009    | 4         | 2.05%   |
| 2008    | 3         | 1.54%   |
| Unknown | 2         | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 121       | 62.05%  |
| Desktop        | 69        | 35.38%  |
| Convertible    | 2         | 1.03%   |
| Phone          | 1         | 0.51%   |
| System on chip | 1         | 0.51%   |
| Tablet         | 1         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 183       | 92.42%  |
| Enabled  | 15        | 7.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 195       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 74        | 37%     |
| 3.01-4.0   | 57        | 28.5%   |
| 8.01-16.0  | 31        | 15.5%   |
| 16.01-24.0 | 22        | 11%     |
| 1.01-2.0   | 11        | 5.5%    |
| 32.01-64.0 | 3         | 1.5%    |
| 2.01-3.0   | 1         | 0.5%    |
| 0.51-1.0   | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 83        | 38.25%  |
| 2.01-3.0  | 68        | 31.34%  |
| 3.01-4.0  | 26        | 11.98%  |
| 4.01-8.0  | 22        | 10.14%  |
| 0.51-1.0  | 11        | 5.07%   |
| 8.01-16.0 | 4         | 1.84%   |
| 0.01-0.5  | 3         | 1.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 125       | 63.13%  |
| 2      | 60        | 30.3%   |
| 3      | 11        | 5.56%   |
| 5      | 1         | 0.51%   |
| 4      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 132       | 67.01%  |
| Yes       | 65        | 32.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 84.69%  |
| No        | 30        | 15.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 74.37%  |
| No        | 51        | 25.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 58.59%  |
| No        | 82        | 41.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Bangladesh | 195       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Dhaka         | 130       | 63.41%  |
| Chittagong    | 12        | 5.85%   |
| Rajshahi      | 7         | 3.41%   |
| Tongi         | 5         | 2.44%   |
| Jessore       | 5         | 2.44%   |
| Pabna         | 4         | 1.95%   |
| Rangpur City  | 3         | 1.46%   |
| Narayanganj   | 3         | 1.46%   |
| Manikganj     | 3         | 1.46%   |
| Comilla       | 3         | 1.46%   |
| Bogra         | 3         | 1.46%   |
| Sylhet        | 2         | 0.98%   |
| Ghazipur      | 2         | 0.98%   |
| Feni          | 2         | 0.98%   |
| Azimpur       | 2         | 0.98%   |
| Ulpur         | 1         | 0.49%   |
| Teknaf        | 1         | 0.49%   |
| Sherpur       | 1         | 0.49%   |
| Rangpur       | 1         | 0.49%   |
| Paltan        | 1         | 0.49%   |
| Nilphamari    | 1         | 0.49%   |
| Netrakona     | 1         | 0.49%   |
| Narsingdi     | 1         | 0.49%   |
| Nalitabari    | 1         | 0.49%   |
| Nabiganj      | 1         | 0.49%   |
| Mymensingh    | 1         | 0.49%   |
| LДЃkshДЃm | 1         | 0.49%   |
| Khulna        | 1         | 0.49%   |
| Khilgaon      | 1         | 0.49%   |
| Hajiganj      | 1         | 0.49%   |
| Gulshan       | 1         | 0.49%   |
| Fatullah      | 1         | 0.49%   |
| Faridpur      | 1         | 0.49%   |
| Chhagalnaiya  | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 56        | 79     | 20.82%  |
| Seagate             | 47        | 61     | 17.47%  |
| Toshiba             | 46        | 57     | 17.1%   |
| Samsung Electronics | 20        | 31     | 7.43%   |
| Transcend           | 17        | 18     | 6.32%   |
| Hitachi             | 10        | 13     | 3.72%   |
| HGST                | 10        | 10     | 3.72%   |
| SanDisk             | 8         | 8      | 2.97%   |
| A-DATA Technology   | 5         | 6      | 1.86%   |
| Micron Technology   | 4         | 4      | 1.49%   |
| Corsair             | 4         | 6      | 1.49%   |
| Silicon Motion      | 3         | 7      | 1.12%   |
| Phison              | 3         | 3      | 1.12%   |
| Kingston            | 3         | 4      | 1.12%   |
| Hewlett-Packard     | 3         | 3      | 1.12%   |
| Unknown             | 2         | 3      | 0.74%   |
| TwinMOS             | 2         | 2      | 0.74%   |
| Teutons             | 2         | 6      | 0.74%   |
| SK Hynix            | 2         | 2      | 0.74%   |
| KingSpec            | 2         | 2      | 0.74%   |
| Intel               | 2         | 3      | 0.74%   |
| HS-SSD-E100         | 2         | 3      | 0.74%   |
| Unknown             | 2         | 2      | 0.74%   |
| WDC WDS4            | 1         | 1      | 0.37%   |
| Team                | 1         | 1      | 0.37%   |
| Ramsta              | 1         | 1      | 0.37%   |
| PNY                 | 1         | 1      | 0.37%   |
| Phison Electronics  | 1         | 1      | 0.37%   |
| Patriot             | 1         | 1      | 0.37%   |
| OCZ                 | 1         | 1      | 0.37%   |
| Lexar               | 1         | 2      | 0.37%   |
| Gigabyte Technology | 1         | 1      | 0.37%   |
| Crucial             | 1         | 2      | 0.37%   |
| Colorful            | 1         | 1      | 0.37%   |
| China               | 1         | 1      | 0.37%   |
| Biwin               | 1         | 1      | 0.37%   |
| Apacer              | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB               | 14        | 5.04%   |
| Seagate ST1000LM035-1RK172 1TB       | 14        | 5.04%   |
| Toshiba DT01ACA100 1TB               | 9         | 3.24%   |
| Seagate ST500DM002-1BD142 500GB      | 7         | 2.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 5         | 1.8%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 5         | 1.8%    |
| WDC WD10JPVX-60JC3T0 1TB             | 5         | 1.8%    |
| Toshiba HDWD110 1TB                  | 5         | 1.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 1.8%    |
| Seagate ST1000DM010-2EP102 1TB       | 5         | 1.8%    |
| Toshiba MQ01ABD100 1TB               | 4         | 1.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 3         | 1.08%   |
| WDC WD10JPVX-60JC3T1 1TB             | 3         | 1.08%   |
| WDC WD10EZEX-60WN4A0 1TB             | 3         | 1.08%   |
| Transcend TS256GSSD230S 256GB        | 3         | 1.08%   |
| Transcend TS120GMTS420S 120GB SSD    | 3         | 1.08%   |
| Toshiba DT01ACA200 2TB               | 3         | 1.08%   |
| Sandisk NVMe SSD Drive 512GB         | 3         | 1.08%   |
| Samsung HD502HJ 500GB                | 3         | 1.08%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.08%   |
| Corsair Force MP510 240GB            | 3         | 1.08%   |
| A-DATA SU650 240GB SSD               | 3         | 1.08%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 0.72%   |
| WDC WD40PURX-64N96Y0 4TB             | 2         | 0.72%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 2         | 0.72%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.72%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 0.72%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2         | 0.72%   |
| WDC WD10EZEX-00BN5A0 1TB             | 2         | 0.72%   |
| WDC WD SSD 120GB                     | 2         | 0.72%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 2         | 0.72%   |
| Transcend TS240GSSD220S 240GB        | 2         | 0.72%   |
| Transcend TS128GSSD370S 128GB        | 2         | 0.72%   |
| Transcend TS120GSSD220S 120GB        | 2         | 0.72%   |
| Toshiba THNSNK128GVN8 128GB SSD      | 2         | 0.72%   |
| Silicon Motion NVMe SSD Drive 256GB  | 2         | 0.72%   |
| Seagate ST9500325AS 500GB            | 2         | 0.72%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.72%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.72%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.72%   |
| Samsung SP2504C 250GB                | 2         | 0.72%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.72%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.72%   |
| HGST HTS545050A7E680 500GB           | 2         | 0.72%   |
| HGST HTS541010B7E610 1TB             | 2         | 0.72%   |
| HP SSD S700 250GB                    | 2         | 0.72%   |
| Unknown                              | 2         | 0.72%   |
| WDC WDS4 80G2G0B-00EPW0 480GB SSD    | 1         | 0.36%   |
| WDC WDS240GS2G0A-00JH30 240GB SSD    | 1         | 0.36%   |
| WDC WDS240G2G0A 240GB SSD            | 1         | 0.36%   |
| WDC WDS120G2G0B-00EPWP 120GB SSD     | 1         | 0.36%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.36%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.36%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.36%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.36%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.36%   |
| WDC WD3200BPVT-60JJ5T0 320GB         | 1         | 0.36%   |
| WDC WD3200BPVT-00ZEST0 320GB         | 1         | 0.36%   |
| WDC WD3200AAJS-00L7A0 320GB          | 1         | 0.36%   |
| WDC WD30PURX-64P6ZY0 3TB             | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 61     | 29.94%  |
| Toshiba             | 42        | 52     | 26.75%  |
| WDC                 | 37        | 53     | 23.57%  |
| Samsung Electronics | 11        | 19     | 7.01%   |
| Hitachi             | 10        | 13     | 6.37%   |
| HGST                | 10        | 10     | 6.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 22     | 22.22%  |
| Transcend           | 16        | 17     | 19.75%  |
| Samsung Electronics | 6         | 8      | 7.41%   |
| SanDisk             | 5         | 5      | 6.17%   |
| A-DATA Technology   | 5         | 6      | 6.17%   |
| Micron Technology   | 4         | 4      | 4.94%   |
| Toshiba             | 3         | 4      | 3.7%    |
| Hewlett-Packard     | 3         | 3      | 3.7%    |
| TWINMOS             | 2         | 2      | 2.47%   |
| TEUTONS             | 2         | 6      | 2.47%   |
| KingSpec            | 2         | 2      | 2.47%   |
| HS-SSD-E100         | 2         | 2      | 2.47%   |
| WDC WDS4            | 1         | 1      | 1.23%   |
| Team                | 1         | 1      | 1.23%   |
| SK Hynix            | 1         | 1      | 1.23%   |
| Ramsta              | 1         | 1      | 1.23%   |
| PNY                 | 1         | 1      | 1.23%   |
| Patriot             | 1         | 1      | 1.23%   |
| OCZ                 | 1         | 1      | 1.23%   |
| Kingston            | 1         | 1      | 1.23%   |
| Gigabyte Technology | 1         | 1      | 1.23%   |
| Crucial             | 1         | 2      | 1.23%   |
| Corsair             | 1         | 2      | 1.23%   |
| China               | 1         | 1      | 1.23%   |
| Apacer              | 1         | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 149       | 208    | 57.09%  |
| SSD     | 78        | 96     | 29.89%  |
| NVMe    | 28        | 38     | 10.73%  |
| Unknown | 4         | 4      | 1.53%   |
| MMC     | 2         | 3      | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 179       | 307    | 85.24%  |
| NVMe | 28        | 38     | 13.33%  |
| MMC  | 2         | 3      | 0.95%   |
| SAS  | 1         | 1      | 0.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 117       | 163    | 52.7%   |
| 0.51-1.0   | 94        | 126    | 42.34%  |
| 1.01-2.0   | 7         | 7      | 3.15%   |
| 3.01-4.0   | 2         | 3      | 0.9%    |
| 2.01-3.0   | 1         | 4      | 0.45%   |
| 4.01-10.0  | 1         | 1      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 57        | 27.14%  |
| 501-1000       | 44        | 20.95%  |
| 251-500        | 42        | 20%     |
| 1001-2000      | 22        | 10.48%  |
| 51-100         | 20        | 9.52%   |
| 21-50          | 11        | 5.24%   |
| 1-20           | 9         | 4.29%   |
| Unknown        | 3         | 1.43%   |
| More than 3000 | 2         | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 78        | 36.62%  |
| 21-50          | 46        | 21.6%   |
| 101-250        | 32        | 15.02%  |
| 51-100         | 28        | 13.15%  |
| 251-500        | 11        | 5.16%   |
| 501-1000       | 10        | 4.69%   |
| 1001-2000      | 4         | 1.88%   |
| Unknown        | 3         | 1.41%   |
| More than 3000 | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 2         | 4      | 6.67%   |
| Seagate ST500DM002-1BD142 500GB                | 2         | 2      | 6.67%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 6.67%   |
| WDC WD5000LPCX-22VHAT0 500GB                   | 1         | 1      | 3.33%   |
| WDC WD5000BPVT-22HXZT3 500GB                   | 1         | 1      | 3.33%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 3.33%   |
| WDC WD10JPVX-60JC3T0 1TB                       | 1         | 2      | 3.33%   |
| WDC WD10JPVT-00MS8T0 1TB                       | 1         | 1      | 3.33%   |
| WDC WD10EZEX-60WN4A0 1TB                       | 1         | 1      | 3.33%   |
| WDC WD10EZEX-22MFCA0 1TB                       | 1         | 1      | 3.33%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 3.33%   |
| Toshiba HDWD110 1TB                            | 1         | 1      | 3.33%   |
| Toshiba DT01ACA200 2TB                         | 1         | 1      | 3.33%   |
| Toshiba DT01ACA100 1TB                         | 1         | 1      | 3.33%   |
| SK Hynix HFS256G3AMNB-2200A 256GB SSD          | 1         | 1      | 3.33%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 3.33%   |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 3.33%   |
| Samsung Electronics HD161HJ 160GB              | 1         | 2      | 3.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 3.33%   |
| HS-SSD-E100 SSD 128G                           | 1         | 1      | 3.33%   |
| Hitachi HDT725050VLA380 500GB                  | 1         | 1      | 3.33%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 3.33%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 3.33%   |
| Hewlett-Packard SSD S600 240GB                 | 1         | 1      | 3.33%   |
| A-DATA Technology SU650 240GB SSD              | 1         | 2      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 26.67%  |
| Toshiba             | 6         | 8      | 20%     |
| Seagate             | 5         | 5      | 16.67%  |
| HGST                | 4         | 4      | 13.33%  |
| SK Hynix            | 1         | 1      | 3.33%   |
| Samsung Electronics | 1         | 2      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| HS-SSD-E100         | 1         | 1      | 3.33%   |
| Hitachi             | 1         | 1      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 2      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 32%     |
| Toshiba             | 6         | 8      | 24%     |
| Seagate             | 5         | 5      | 20%     |
| HGST                | 4         | 4      | 16%     |
| Samsung Electronics | 1         | 2      | 4%      |
| Hitachi             | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 29     | 82.76%  |
| SSD  | 5         | 6      | 17.24%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| Toshiba DT01ACA200 2TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 116       | 194    | 53.7%   |
| Works    | 70        | 119    | 32.41%  |
| Malfunc  | 29        | 35     | 13.43%  |
| Failed   | 1         | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 163       | 73.76%  |
| AMD                          | 24        | 10.86%  |
| Sandisk                      | 7         | 3.17%   |
| Phison Electronics           | 7         | 3.17%   |
| Samsung Electronics          | 4         | 1.81%   |
| Silicon Motion               | 3         | 1.36%   |
| Marvell Technology Group     | 3         | 1.36%   |
| Kingston Technology Company  | 2         | 0.9%    |
| ASMedia Technology           | 2         | 0.9%    |
| VIA Technologies             | 1         | 0.45%   |
| Unknown                      | 1         | 0.45%   |
| Toshiba America Info Systems | 1         | 0.45%   |
| SK Hynix                     | 1         | 0.45%   |
| Shenzhen Longsys Electronics | 1         | 0.45%   |
| Biwin Storage Technology     | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 44        | 16.99%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 6.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 13        | 5.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 4.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 4.25%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10        | 3.86%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9         | 3.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 3.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8         | 3.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 7         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 2.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 2.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 1.93%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 4         | 1.54%   |
| Phison E12 NVMe Controller                                                              | 4         | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4         | 1.54%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.16%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.77%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 0.77%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 2         | 0.77%   |
| Marvell Group 88SE912x IDE Controller                                                   | 2         | 0.77%   |
| Intel SSD 660P Series                                                                   | 2         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 0.77%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 0.77%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.77%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 0.77%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.39%   |
| Unknown Non-Volatile memory controller                                                  | 1         | 0.39%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.39%   |
| SK Hynix Non-Volatile memory controller                                                 | 1         | 0.39%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1         | 0.39%   |
| Shenzhen Longsys Non-Volatile memory controller                                         | 1         | 0.39%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.39%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.39%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1         | 0.39%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.39%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.39%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 0.39%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 0.39%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 0.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.39%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.39%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1         | 0.39%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1         | 0.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 147       | 67.12%  |
| NVMe | 29        | 13.24%  |
| IDE  | 26        | 11.87%  |
| RAID | 17        | 7.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 167       | 85.64%  |
| AMD    | 26        | 13.33%  |
| ARM    | 2         | 1.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 4.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 3.57%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 7         | 3.57%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 3.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 3.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 2.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.04%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 2.04%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 4         | 2.04%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 2.04%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 2.04%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.53%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.53%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 3         | 1.53%   |
| Intel Xeon CPU X3440 @ 2.53GHz                | 2         | 1.02%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 2         | 1.02%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 2         | 1.02%   |
| Intel Pentium CPU G3260 @ 3.30GHz             | 2         | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.02%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 2         | 1.02%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 2         | 1.02%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.02%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.02%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 2         | 1.02%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.02%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.02%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.02%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.02%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 2         | 1.02%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz          | 2         | 1.02%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 1.02%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.02%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.02%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 1.02%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.51%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1         | 0.51%   |
| Intel Pentium CPU G3240 @ 3.10GHz             | 1         | 0.51%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.51%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.51%   |
| Intel Core i7-7800X CPU @ 3.50GHz             | 1         | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.51%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.51%   |
| Intel Core i5-8600K CPU @ 3.60GHz             | 1         | 0.51%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1         | 0.51%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 0.51%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.51%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 0.51%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.51%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 0.51%   |
| Intel Core i5-4200H CPU @ 2.80GHz             | 1         | 0.51%   |
| Intel Core i5-3550 CPU @ 3.30GHz              | 1         | 0.51%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.51%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 78        | 40%     |
| Intel Core i3           | 38        | 19.49%  |
| AMD Ryzen 5             | 14        | 7.18%   |
| Intel Core i7           | 13        | 6.67%   |
| Intel Pentium           | 11        | 5.64%   |
| Intel Core 2 Duo        | 7         | 3.59%   |
| Other                   | 6         | 3.08%   |
| Intel Celeron           | 6         | 3.08%   |
| AMD Ryzen 7             | 4         | 2.05%   |
| AMD Ryzen 3             | 4         | 2.05%   |
| Intel Xeon              | 3         | 1.54%   |
| Intel Pentium Dual-Core | 3         | 1.54%   |
| Intel Atom              | 2         | 1.03%   |
| Intel Core 2 Quad       | 1         | 0.51%   |
| ARM AArch64             | 1         | 0.51%   |
| AMD FX                  | 1         | 0.51%   |
| AMD E2                  | 1         | 0.51%   |
| AMD E                   | 1         | 0.51%   |
| AMD A8                  | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 113       | 57.65%  |
| 4       | 62        | 31.63%  |
| 6       | 13        | 6.63%   |
| 8       | 4         | 2.04%   |
| 1       | 2         | 1.02%   |
| 10      | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 194       | 99.49%  |
| Unknown | 1         | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 138       | 70.77%  |
| 1       | 56        | 28.72%  |
| Unknown | 1         | 0.51%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 194       | 99.49%  |
| Unknown        | 1         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 19.21%  |
| 0x806e9    | 21        | 10.34%  |
| 0x806ea    | 15        | 7.39%   |
| 0x306a9    | 13        | 6.4%    |
| 0x206a7    | 10        | 4.93%   |
| 0x406e3    | 9         | 4.43%   |
| 0x306c3    | 9         | 4.43%   |
| 0x306d4    | 8         | 3.94%   |
| 0x906e9    | 5         | 2.46%   |
| 0x806ec    | 5         | 2.46%   |
| 0x806eb    | 5         | 2.46%   |
| 0x40651    | 5         | 2.46%   |
| 0x1067a    | 5         | 2.46%   |
| 0x08108109 | 5         | 2.46%   |
| 0x406c4    | 4         | 1.97%   |
| 0x906ea    | 3         | 1.48%   |
| 0x806c1    | 3         | 1.48%   |
| 0x706e5    | 3         | 1.48%   |
| 0x106e5    | 3         | 1.48%   |
| 0x10676    | 3         | 1.48%   |
| 0x08701021 | 3         | 1.48%   |
| 0x08108102 | 3         | 1.48%   |
| 0x6fb      | 2         | 0.99%   |
| 0x506e3    | 2         | 0.99%   |
| 0x20652    | 2         | 0.99%   |
| 0x0a50000c | 2         | 0.99%   |
| 0x0810100b | 2         | 0.99%   |
| 0x906eb    | 1         | 0.49%   |
| 0x90672    | 1         | 0.49%   |
| 0x506c9    | 1         | 0.49%   |
| 0x50654    | 1         | 0.49%   |
| 0x406c3    | 1         | 0.49%   |
| 0x30678    | 1         | 0.49%   |
| 0x30661    | 1         | 0.49%   |
| 0x106ca    | 1         | 0.49%   |
| 0x10661    | 1         | 0.49%   |
| 0x08701013 | 1         | 0.49%   |
| 0x08001137 | 1         | 0.49%   |
| 0x06006705 | 1         | 0.49%   |
| 0x06001119 | 1         | 0.49%   |
| 0x05000029 | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 60        | 30.61%  |
| IvyBridge        | 17        | 8.67%   |
| Haswell          | 17        | 8.67%   |
| Skylake          | 15        | 7.65%   |
| SandyBridge      | 13        | 6.63%   |
| Broadwell        | 10        | 5.1%    |
| Zen+             | 9         | 4.59%   |
| Penryn           | 9         | 4.59%   |
| Zen 2            | 6         | 3.06%   |
| Silvermont       | 6         | 3.06%   |
| Zen 3            | 4         | 2.04%   |
| TigerLake        | 4         | 2.04%   |
| Core             | 4         | 2.04%   |
| Zen              | 3         | 1.53%   |
| Nehalem          | 3         | 1.53%   |
| IceLake          | 3         | 1.53%   |
| Westmere         | 2         | 1.02%   |
| Piledriver       | 2         | 1.02%   |
| Bonnell          | 2         | 1.02%   |
| Unknown          | 2         | 1.02%   |
| Goldmont         | 1         | 0.51%   |
| Excavator        | 1         | 0.51%   |
| CometLake        | 1         | 0.51%   |
| Bobcat           | 1         | 0.51%   |
| Alderlake Hybrid | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 155       | 67.1%   |
| Nvidia | 45        | 19.48%  |
| AMD    | 31        | 13.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 23        | 9.91%   |
| Intel UHD Graphics 620                                                                   | 15        | 6.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 5.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 4.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.31%   |
| Intel HD Graphics 5500                                                                   | 9         | 3.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 3.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 3.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 2.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 2.59%   |
| Intel HD Graphics 630                                                                    | 5         | 2.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 2.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.16%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.72%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.72%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4         | 1.72%   |
| AMD Cezanne                                                                              | 4         | 1.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.29%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.29%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.29%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.86%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 0.86%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.86%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 2         | 0.86%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.43%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.43%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.43%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.43%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.43%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.43%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.43%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.43%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.43%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.43%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.43%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.43%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 0.43%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.43%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.43%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 0.43%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.43%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 0.43%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.43%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.43%   |
| Intel HD Graphics 500                                                                    | 1         | 0.43%   |
| Intel HD Graphics                                                                        | 1         | 0.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.43%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 0.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.43%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 122       | 62.24%  |
| Intel + Nvidia | 26        | 13.27%  |
| 1 x AMD        | 22        | 11.22%  |
| 1 x Nvidia     | 15        | 7.65%   |
| Intel + AMD    | 4         | 2.04%   |
| AMD + Nvidia   | 4         | 2.04%   |
| Other          | 2         | 1.02%   |
| 2 x AMD        | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 166       | 83.42%  |
| Proprietary | 24        | 12.06%  |
| Unknown     | 9         | 4.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 143       | 71.86%  |
| 1.01-2.0   | 29        | 14.57%  |
| 3.01-4.0   | 11        | 5.53%   |
| 0.51-1.0   | 8         | 4.02%   |
| 0.01-0.5   | 6         | 3.02%   |
| 7.01-8.0   | 1         | 0.5%    |
| 5.01-6.0   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 35        | 17.5%   |
| AU Optronics            | 31        | 15.5%   |
| Chimei Innolux          | 29        | 14.5%   |
| Samsung Electronics     | 21        | 10.5%   |
| LG Display              | 20        | 10%     |
| Dell                    | 18        | 9%      |
| Goldstar                | 10        | 5%      |
| Hewlett-Packard         | 9         | 4.5%    |
| ViewSonic               | 4         | 2%      |
| Philips                 | 3         | 1.5%    |
| Ancor Communications    | 3         | 1.5%    |
| MSI                     | 2         | 1%      |
| Chi Mei Optoelectronics | 2         | 1%      |
| ASUSTek Computer        | 2         | 1%      |
| ___                     | 1         | 0.5%    |
| UTV                     | 1         | 0.5%    |
| Unknown                 | 1         | 0.5%    |
| Sony                    | 1         | 0.5%    |
| Sharp                   | 1         | 0.5%    |
| QXS                     | 1         | 0.5%    |
| PANDA                   | 1         | 0.5%    |
| FSR                     | 1         | 0.5%    |
| CND                     | 1         | 0.5%    |
| CHR                     | 1         | 0.5%    |
| Apple                   | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 7         | 3.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 2.44%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 4         | 1.95%   |
| Dell S2240L DELD054 1920x1080 476x267mm 21.5-inch                     | 3         | 1.46%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 3         | 1.46%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 3         | 1.46%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.46%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch   | 2         | 0.98%   |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch     | 2         | 0.98%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 0.98%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.98%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 2         | 0.98%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch           | 2         | 0.98%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 0.98%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch             | 2         | 0.98%   |
| Hewlett-Packard v185w HWP2820 1366x768 410x230mm 18.5-inch            | 2         | 0.98%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 2         | 0.98%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2         | 0.98%   |
| Dell SE2219H DELF10F 1920x1080 476x268mm 21.5-inch                    | 2         | 0.98%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                     | 2         | 0.98%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 2         | 0.98%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 0.98%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 2         | 0.98%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 2         | 0.98%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 0.98%   |
| ___ AAA ___1062 1440x900 410x260mm 19.1-inch                          | 1         | 0.49%   |
| ViewSonic VX2276 Series VSC2F32 1920x1080 476x268mm 21.5-inch         | 1         | 0.49%   |
| ViewSonic VX2263 Series VSC692F 1920x1080 476x268mm 21.5-inch         | 1         | 0.49%   |
| ViewSonic VX1951m VSCD627 1600x900 410x260mm 19.1-inch                | 1         | 0.49%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1         | 0.49%   |
| UTV MONITOR UTV0030 1920x1080 580x330mm 26.3-inch                     | 1         | 0.49%   |
| Unknown AAA 1062 1440x900 341x256mm 16.8-inch                         | 1         | 0.49%   |
| Sony TV SNYAB03 1920x1080                                             | 1         | 0.49%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM043E 1600x1200 520x320mm 24.0-inch  | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0107 1280x1024 312x234mm 15.4-inch  | 1         | 0.49%   |
| Samsung Electronics SMS16A100 SAM0880 1366x768 344x194mm 15.5-inch    | 1         | 0.49%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch     | 1         | 0.49%   |
| Samsung Electronics S22E390 SAM0C17 1920x1080 477x268mm 21.5-inch     | 1         | 0.49%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch     | 1         | 0.49%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch      | 1         | 0.49%   |
| Samsung Electronics S19B150 SAM0980 1366x768 410x230mm 18.5-inch      | 1         | 0.49%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4751 1366x768 344x194mm 15.5-inch  | 1         | 0.49%   |
| Samsung Electronics LCD Monitor S22R35x 1920x1080                     | 1         | 0.49%   |
| QXS QUHMINEI185 QXS1850 1366x768 410x230mm 18.5-inch                  | 1         | 0.49%   |
| Philips PHL 226E9Q PHLC17D 1920x1080 477x268mm 21.5-inch              | 1         | 0.49%   |
| Philips 224EL PHLC054 1920x1080 476x268mm 21.5-inch                   | 1         | 0.49%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                    | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 86        | 45.5%   |
| 1920x1080 (FHD)   | 74        | 39.15%  |
| 3840x2160 (4K)    | 6         | 3.17%   |
| 1440x900 (WXGA+)  | 5         | 2.65%   |
| 1600x900 (HD+)    | 4         | 2.12%   |
| 1280x800 (WXGA)   | 2         | 1.06%   |
| 1280x1024 (SXGA)  | 2         | 1.06%   |
| 1024x600          | 2         | 1.06%   |
| 3440x1440         | 1         | 0.53%   |
| 3360x1080         | 1         | 0.53%   |
| 2736x1824         | 1         | 0.53%   |
| 2560x1440 (QHD)   | 1         | 0.53%   |
| 2240x1400         | 1         | 0.53%   |
| 1920x1200 (WUXGA) | 1         | 0.53%   |
| 1024x768 (XGA)    | 1         | 0.53%   |
| Unknown           | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 58        | 29%     |
| 13      | 38        | 19%     |
| 21      | 28        | 14%     |
| 18      | 22        | 11%     |
| 14      | 22        | 11%     |
| 23      | 5         | 2.5%    |
| 12      | 5         | 2.5%    |
| 17      | 4         | 2%      |
| 19      | 3         | 1.5%    |
| Unknown | 3         | 1.5%    |
| 24      | 2         | 1%      |
| 11      | 2         | 1%      |
| 10      | 2         | 1%      |
| 84      | 1         | 0.5%    |
| 72      | 1         | 0.5%    |
| 34      | 1         | 0.5%    |
| 27      | 1         | 0.5%    |
| 20      | 1         | 0.5%    |
| 16      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 110       | 55.28%  |
| 401-500     | 56        | 28.14%  |
| 201-300     | 18        | 9.05%   |
| 501-600     | 6         | 3.02%   |
| 351-400     | 3         | 1.51%   |
| Unknown     | 3         | 1.51%   |
| 1501-2000   | 2         | 1.01%   |
| 701-800     | 1         | 0.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 163       | 89.07%  |
| 16/10   | 10        | 5.46%   |
| 4/3     | 4         | 2.19%   |
| Unknown | 3         | 1.64%   |
| 5/4     | 1         | 0.55%   |
| 3/2     | 1         | 0.55%   |
| 21/9    | 1         | 0.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 58        | 29%     |
| 81-90          | 53        | 26.5%   |
| 201-250        | 26        | 13%     |
| 141-150        | 23        | 11.5%   |
| 151-200        | 11        | 5.5%    |
| 71-80          | 6         | 3%      |
| 61-70          | 5         | 2.5%    |
| 131-140        | 4         | 2%      |
| Unknown        | 3         | 1.5%    |
| More than 1000 | 2         | 1%      |
| 51-60          | 2         | 1%      |
| 41-50          | 2         | 1%      |
| 251-300        | 2         | 1%      |
| 351-500        | 1         | 0.5%    |
| 301-350        | 1         | 0.5%    |
| 111-120        | 1         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 95        | 48.47%  |
| 121-160       | 52        | 26.53%  |
| 51-100        | 39        | 19.9%   |
| 161-240       | 5         | 2.55%   |
| Unknown       | 3         | 1.53%   |
| More than 240 | 1         | 0.51%   |
| 1-50          | 1         | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 169       | 84.92%  |
| 2     | 20        | 10.05%  |
| 0     | 8         | 4.02%   |
| 3     | 2         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 146       | 50.17%  |
| Intel                             | 72        | 24.74%  |
| Qualcomm Atheros                  | 34        | 11.68%  |
| Ralink Technology                 | 11        | 3.78%   |
| Xiaomi                            | 6         | 2.06%   |
| TP-Link                           | 5         | 1.72%   |
| Broadcom                          | 3         | 1.03%   |
| Ralink                            | 2         | 0.69%   |
| Qualcomm                          | 2         | 0.69%   |
| Sundance Technology Inc / IC Plus | 1         | 0.34%   |
| Samsung Electronics               | 1         | 0.34%   |
| NetGear                           | 1         | 0.34%   |
| MEDIATEK                          | 1         | 0.34%   |
| HMD Global                        | 1         | 0.34%   |
| Dell                              | 1         | 0.34%   |
| D-Link                            | 1         | 0.34%   |
| ASIX Electronics                  | 1         | 0.34%   |
| Arduino SA                        | 1         | 0.34%   |
| AboCom Systems                    | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 103       | 31.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 8.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 4.22%   |
| Intel Wireless 8265 / 8275                                        | 13        | 3.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 3.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 3.31%   |
| Ralink MT7601U Wireless Adapter                                   | 9         | 2.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.11%   |
| Intel Wireless 3165                                               | 6         | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.51%   |
| Intel Wireless 8260                                               | 5         | 1.51%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.2%    |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.9%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3         | 0.9%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3         | 0.9%    |
| Intel Wireless 7265                                               | 3         | 0.9%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.9%    |
| Xiaomi MediaTek MT7601U [MI WiFi]                                 | 2         | 0.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.6%    |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.6%    |
| Qualcomm Redmi 9T                                                 | 2         | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.6%    |
| Intel Wireless 3160                                               | 2         | 0.6%    |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.3%    |
| TP-Link Archer T4U ver.3                                          | 1         | 0.3%    |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet             | 1         | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.3%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.3%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.3%    |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.3%    |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.3%    |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1         | 0.3%    |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1         | 0.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.3%    |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]               | 1         | 0.3%    |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 40.65%  |
| Qualcomm Atheros      | 34        | 21.94%  |
| Realtek Semiconductor | 31        | 20%     |
| Ralink Technology     | 11        | 7.1%    |
| TP-Link               | 5         | 3.23%   |
| Xiaomi                | 2         | 1.29%   |
| Ralink                | 2         | 1.29%   |
| Broadcom              | 2         | 1.29%   |
| NetGear               | 1         | 0.65%   |
| MEDIATEK              | 1         | 0.65%   |
| Dell                  | 1         | 0.65%   |
| D-Link                | 1         | 0.65%   |
| AboCom Systems        | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 14        | 9.03%   |
| Intel Wireless 8265 / 8275                                                 | 13        | 8.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 12        | 7.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 11        | 7.1%    |
| Ralink MT7601U Wireless Adapter                                            | 9         | 5.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 7         | 4.52%   |
| Intel Wireless 3165                                                        | 6         | 3.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 5         | 3.23%   |
| Intel Wireless 8260                                                        | 5         | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 2.58%   |
| Intel Wi-Fi 6 AX201                                                        | 4         | 2.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 4         | 2.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 3         | 1.94%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 3         | 1.94%   |
| Intel Wireless 7265                                                        | 3         | 1.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                            | 3         | 1.94%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                          | 2         | 1.29%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2         | 1.29%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 1.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.29%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 2         | 1.29%   |
| Realtek 802.11n WLAN Adapter                                               | 2         | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.29%   |
| Intel Wireless 3160                                                        | 2         | 1.29%   |
| Intel Wi-Fi 6 AX200                                                        | 2         | 1.29%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                            | 2         | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 2         | 1.29%   |
| TP-Link Archer T4U ver.3                                                   | 1         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.65%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                 | 1         | 0.65%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                     | 1         | 0.65%   |
| Realtek RTL8187 Wireless Adapter                                           | 1         | 0.65%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.65%   |
| Ralink RT2501/RT2573 Wireless Adapter                                      | 1         | 0.65%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                | 1         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1         | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 0.65%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                        | 1         | 0.65%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter              | 1         | 0.65%   |
| Intel Wireless 7260                                                        | 1         | 0.65%   |
| Intel Ultimate N WiFi Link 5300                                            | 1         | 0.65%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 0.65%   |
| Intel Centrino Ultimate-N 6300                                             | 1         | 0.65%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 1         | 0.65%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                       | 1         | 0.65%   |
| D-Link DWA-171                                                             | 1         | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 1         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 0.65%   |
| AboCom Systems AboCom Systems Inc [WN2001 Prolink Wireless-N Nano Adapter] | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 136       | 78.16%  |
| Intel                             | 23        | 13.22%  |
| Xiaomi                            | 4         | 2.3%    |
| Qualcomm Atheros                  | 3         | 1.72%   |
| Qualcomm                          | 2         | 1.15%   |
| Broadcom                          | 2         | 1.15%   |
| Sundance Technology Inc / IC Plus | 1         | 0.57%   |
| Samsung Electronics               | 1         | 0.57%   |
| HMD Global                        | 1         | 0.57%   |
| ASIX Electronics                  | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 103       | 58.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 15.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.98%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.84%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.7%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.14%   |
| Qualcomm Redmi 9T                                                 | 2         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.57%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet             | 1         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.57%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.57%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.57%   |
| HMD Global Android                                                | 1         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 166       | 52.87%  |
| WiFi     | 147       | 46.82%  |
| Modem    | 1         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 129       | 55.6%   |
| Ethernet | 103       | 44.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 97        | 49.74%  |
| 2     | 95        | 48.72%  |
| 0     | 3         | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 194       | 99.49%  |
| Yes  | 1         | 0.51%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 43.59%  |
| IMC Networks                    | 18        | 15.38%  |
| Realtek Semiconductor           | 11        | 9.4%    |
| Qualcomm Atheros Communications | 9         | 7.69%   |
| Lite-On Technology              | 8         | 6.84%   |
| Cambridge Silicon Radio         | 8         | 6.84%   |
| Broadcom                        | 6         | 5.13%   |
| Foxconn / Hon Hai               | 2         | 1.71%   |
| Toshiba                         | 1         | 0.85%   |
| Ralink                          | 1         | 0.85%   |
| Hewlett-Packard                 | 1         | 0.85%   |
| Unknown                         | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 31        | 26.5%   |
| IMC Networks Bluetooth Device                       | 11        | 9.4%    |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 8.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 6.84%   |
| Realtek Bluetooth Radio                             | 7         | 5.98%   |
| IMC Networks Bluetooth Radio                        | 6         | 5.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 4.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 3.42%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.56%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 2.56%   |
| Intel AX201 Bluetooth                               | 3         | 2.56%   |
| Lite-On Bluetooth Device                            | 2         | 1.71%   |
| Intel AX200 Bluetooth                               | 2         | 1.71%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.71%   |
| Toshiba Bluetooth Radio                             | 1         | 0.85%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.85%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.85%   |
| Intel Bluetooth Device                              | 1         | 0.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.85%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.85%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.85%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.85%   |
| Unknown                                             | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 165       | 72.37%  |
| AMD                    | 32        | 14.04%  |
| Nvidia                 | 19        | 8.33%   |
| Generalplus Technology | 7         | 3.07%   |
| Logitech               | 1         | 0.44%   |
| JMTek                  | 1         | 0.44%   |
| iCreate Technologies   | 1         | 0.44%   |
| Creative Labs          | 1         | 0.44%   |
| C-Media Electronics    | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 50        | 18.38%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 4.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 4.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 4.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 3.68%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 3.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.94%   |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 2.57%   |
| Generalplus Technology Usb Audio Device                                                           | 7         | 2.57%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.84%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.84%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.84%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.47%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.1%    |
| Intel USB PnP Sound Device                                                                        | 3         | 1.1%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 1.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.37%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.37%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.37%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.37%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Logitech Headset H390                                                                             | 1         | 0.37%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.37%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.37%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.37%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.37%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 0.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.37%   |
| iCreate Technologies ASUS BE/C6 webcam series                                                     | 1         | 0.37%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 1         | 0.37%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.37%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.37%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.37%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.37%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.37%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.37%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.37%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 23.97%  |
| SK Hynix            | 23        | 19.01%  |
| Micron Technology   | 11        | 9.09%   |
| Unknown             | 7         | 5.79%   |
| Kingston            | 7         | 5.79%   |
| G.Skill             | 7         | 5.79%   |
| A-DATA Technology   | 7         | 5.79%   |
| Corsair             | 6         | 4.96%   |
| Transcend           | 5         | 4.13%   |
| Team                | 5         | 4.13%   |
| Ramaxel Technology  | 4         | 3.31%   |
| SemsoTai            | 2         | 1.65%   |
| Unknown (C509)      | 1         | 0.83%   |
| Unknown (768A)      | 1         | 0.83%   |
| TwinMOS             | 1         | 0.83%   |
| Ramos Technology    | 1         | 0.83%   |
| Qumo                | 1         | 0.83%   |
| Nanya Technology    | 1         | 0.83%   |
| GeIL                | 1         | 0.83%   |
| Crucial             | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 4         | 3.2%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.4%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 2.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.4%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.6%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.6%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.6%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 1.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.6%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.6%    |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 2         | 1.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.6%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.6%    |
| Corsair RAM CMK8GX4M1E3200C16 8GB DIMM DDR4 3200MT/s             | 2         | 1.6%    |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s             | 2         | 1.6%    |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                        | 1         | 0.8%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.8%    |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.8%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.8%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.8%    |
| Unknown RAM Module 4096MB DIMM 1066MT/s                          | 1         | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.8%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 1         | 0.8%    |
| Unknown RAM Module 2048MB DIMM 1066MT/s                          | 1         | 0.8%    |
| Unknown (C509) RAM Module 4GB SODIMM DDR4 2400MT/s               | 1         | 0.8%    |
| Unknown (768A) RAM Module 8192MB SODIMM DDR4 3200MT/s            | 1         | 0.8%    |
| TwinMOS RAM 9DEPBMZ8-TATP 2048MB DIMM DDR3 1333MT/s              | 1         | 0.8%    |
| Transcend RAM TX2133KLN-8GK 4096MB DIMM DDR3 2000MT/s            | 1         | 0.8%    |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s              | 1         | 0.8%    |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s              | 1         | 0.8%    |
| Transcend RAM JM1600KLN-4GK 2GB DIMM DDR3 1600MT/s               | 1         | 0.8%    |
| Transcend RAM JM1600KLN-4G 4096MB DIMM DDR3 1600MT/s             | 1         | 0.8%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s               | 1         | 0.8%    |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s            | 1         | 0.8%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.8%    |
| Team RAM TEAMGROUP-SD4-2400 8192MB SODIMM DDR4 8400MT/s          | 1         | 0.8%    |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                       | 1         | 0.8%    |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.8%    |
| SK Hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s             | 1         | 0.8%    |
| SK Hynix RAM Module 4096MB SODIMM DDR4 2133MT/s                  | 1         | 0.8%    |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.8%    |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.8%    |
| SK Hynix RAM H9CCNNNBJTMLAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.8%    |
| SemsoTai RAM Module 4GB DIMM DDR4 2400MT/s                       | 1         | 0.8%    |
| SemsoTai RAM Module 4GB DIMM DDR3 1600MT/s                       | 1         | 0.8%    |
| SemsoTai RAM Module 4096MB DIMM DDR4 2400MT/s                    | 1         | 0.8%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.8%    |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.8%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.8%    |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.8%    |
| Samsung RAM M471B5673DZ1-CF8 2048MB SODIMM DDR3 1067MT/s         | 1         | 0.8%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.8%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.8%    |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s         | 1         | 0.8%    |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s            | 1         | 0.8%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 57        | 60.64%  |
| DDR3    | 29        | 30.85%  |
| LPDDR3  | 3         | 3.19%   |
| LPDDR4  | 2         | 2.13%   |
| Unknown | 2         | 2.13%   |
| DDR2    | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 62        | 67.39%  |
| DIMM         | 27        | 29.35%  |
| Row Of Chips | 3         | 3.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 50        | 47.62%  |
| 8192  | 38        | 36.19%  |
| 16384 | 8         | 7.62%   |
| 2048  | 7         | 6.67%   |
| 32768 | 2         | 1.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 24        | 23.08%  |
| 1600  | 23        | 22.12%  |
| 2400  | 13        | 12.5%   |
| 3200  | 12        | 11.54%  |
| 2133  | 10        | 9.62%   |
| 1333  | 4         | 3.85%   |
| 2800  | 3         | 2.88%   |
| 1867  | 3         | 2.88%   |
| 3266  | 2         | 1.92%   |
| 1067  | 2         | 1.92%   |
| 8400  | 1         | 0.96%   |
| 3333  | 1         | 0.96%   |
| 3151  | 1         | 0.96%   |
| 3000  | 1         | 0.96%   |
| 2000  | 1         | 0.96%   |
| 1334  | 1         | 0.96%   |
| 1066  | 1         | 0.96%   |
| 800   | 1         | 0.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L132 Series | 2         | 100%    |

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
| IMC Networks                           | 25        | 20.16%  |
| Chicony Electronics                    | 25        | 20.16%  |
| Cheng Uei Precision Industry (Foxlink) | 14        | 11.29%  |
| Realtek Semiconductor                  | 10        | 8.06%   |
| Quanta                                 | 8         | 6.45%   |
| Sunplus Innovation Technology          | 6         | 4.84%   |
| Acer                                   | 6         | 4.84%   |
| Suyin                                  | 5         | 4.03%   |
| Lite-On Technology                     | 5         | 4.03%   |
| Microdia                               | 3         | 2.42%   |
| Luxvisions Innotech Limited            | 3         | 2.42%   |
| Silicon Motion                         | 2         | 1.61%   |
| Primax Electronics                     | 2         | 1.61%   |
| Logitech                               | 2         | 1.61%   |
| Alcor Micro                            | 2         | 1.61%   |
| Z-Star Microelectronics                | 1         | 0.81%   |
| WCM_USB                                | 1         | 0.81%   |
| Syntek                                 | 1         | 0.81%   |
| SiGma Micro                            | 1         | 0.81%   |
| Apple                                  | 1         | 0.81%   |
| ANYKA                                  | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 9         | 7.26%   |
| Chicony USB2.0 VGA UVC WebCam                           | 7         | 5.65%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 6         | 4.84%   |
| IMC Networks VGA UVC WebCam                             | 5         | 4.03%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 4         | 3.23%   |
| Quanta HD Webcam                                        | 3         | 2.42%   |
| Lite-On HP HD Camera                                    | 3         | 2.42%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 2.42%   |
| Chicony EasyCamera                                      | 3         | 2.42%   |
| Suyin Integrated_Webcam_HD                              | 2         | 1.61%   |
| Suyin HP Truevision HD                                  | 2         | 1.61%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.61%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 1.61%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.61%   |
| Primax HP HD Webcam [Fixed]                             | 2         | 1.61%   |
| Luxvisions Innotech Limited HP HD Camera                | 2         | 1.61%   |
| Logitech Webcam C270                                    | 2         | 1.61%   |
| Lite-On Integrated Camera                               | 2         | 1.61%   |
| IMC Networks Integrated Camera                          | 2         | 1.61%   |
| Chicony USB2.0 Camera                                   | 2         | 1.61%   |
| Chicony Integrated Camera                               | 2         | 1.61%   |
| Chicony HP HD Webcam                                    | 2         | 1.61%   |
| Chicony HP HD Camera                                    | 2         | 1.61%   |
| Chicony HD WebCam                                       | 2         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 2         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 1.61%   |
| Acer HD Webcam                                          | 2         | 1.61%   |
| Z-Star A4 TECH USB2.0 PC Camera J                       | 1         | 0.81%   |
| WCM_USB WEB CAM                                         | 1         | 0.81%   |
| Syntek Integrated Camera                                | 1         | 0.81%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 1         | 0.81%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.81%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.81%   |
| Sunplus Dell HD Webcam                                  | 1         | 0.81%   |
| Sunplus ASUS USB2.0 Webcam                              | 1         | 0.81%   |
| Silicon Motion WebCam SC-10HDD12636N                    | 1         | 0.81%   |
| Silicon Motion Endoscope camera                         | 1         | 0.81%   |
| SiGma Micro WebCam SiGma Micro                          | 1         | 0.81%   |
| Realtek USB Camera                                      | 1         | 0.81%   |
| Realtek Integrated_Webcam_HD                            | 1         | 0.81%   |
| Realtek Integrated_Webcam_FHD                           | 1         | 0.81%   |
| Realtek Integrated Webcam_HD                            | 1         | 0.81%   |
| Realtek HD WebCam                                       | 1         | 0.81%   |
| Realtek EasyCamera                                      | 1         | 0.81%   |
| Quanta VGA WebCam                                       | 1         | 0.81%   |
| Quanta HP Webcam                                        | 1         | 0.81%   |
| Quanta HP TrueVision HD Camera                          | 1         | 0.81%   |
| Quanta HP HD Camera                                     | 1         | 0.81%   |
| Quanta HD User Facing                                   | 1         | 0.81%   |
| Microdia Laptop_Integrated_Webcam_0.3M                  | 1         | 0.81%   |
| Microdia Integrated Webcam HD                           | 1         | 0.81%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 0.81%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 1         | 0.81%   |
| Chicony WebCam                                          | 1         | 0.81%   |
| Chicony thinkpad t430s camera                           | 1         | 0.81%   |
| Chicony Integrated Camera (1280x720@30)                 | 1         | 0.81%   |
| Chicony HP Webcam-50                                    | 1         | 0.81%   |
| Chicony HP Truevision HD camera                         | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 24        | 82.76%  |
| Synaptics             | 3         | 10.34%  |
| Elan Microelectronics | 2         | 6.9%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 44.83%  |
| Validity Sensors VFS491                                                    | 3         | 10.34%  |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 6.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 6.9%    |
| Elan ELAN:Fingerprint                                                      | 2         | 6.9%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 3.45%   |
| Synaptics  WBDI                                                            | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 40%     |
| Broadcom 5880                                                                | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 138       | 67.65%  |
| 1     | 60        | 29.41%  |
| 2     | 5         | 2.45%   |
| 3     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 29        | 41.43%  |
| Graphics card            | 17        | 24.29%  |
| Net/wireless             | 9         | 12.86%  |
| Chipcard                 | 5         | 7.14%   |
| Camera                   | 4         | 5.71%   |
| Multimedia controller    | 2         | 2.86%   |
| Card reader              | 2         | 2.86%   |
| Communication controller | 1         | 1.43%   |
| Bluetooth                | 1         | 1.43%   |

