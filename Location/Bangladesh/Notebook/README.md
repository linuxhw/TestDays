Linux in Bangladesh - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bangladesh.

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

Total: 190

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X507UB                      | [0ba0fc4089](https://linux-hardware.org/?probe=0ba0fc4089) | Jun 28, 2022 |
| Acer          | Aspire E5-573               | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [99283be07b](https://linux-hardware.org/?probe=99283be07b) | May 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b85af00b16](https://linux-hardware.org/?probe=b85af00b16) | May 18, 2022 |
| Dell          | Latitude 5580               | [18cefe0718](https://linux-hardware.org/?probe=18cefe0718) | May 17, 2022 |
| Dell          | Inspiron 5505               | [c1353ba170](https://linux-hardware.org/?probe=c1353ba170) | May 15, 2022 |
| Dell          | Inspiron 5567               | [f09183023d](https://linux-hardware.org/?probe=f09183023d) | May 10, 2022 |
| HP            | 240 G3                      | [7062083e69](https://linux-hardware.org/?probe=7062083e69) | May 06, 2022 |
| HP            | EliteBook 840 G3            | [88f6586c4b](https://linux-hardware.org/?probe=88f6586c4b) | May 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ab11d6ac2f](https://linux-hardware.org/?probe=ab11d6ac2f) | Apr 28, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [19623aa8b6](https://linux-hardware.org/?probe=19623aa8b6) | Apr 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [287aa3ba8e](https://linux-hardware.org/?probe=287aa3ba8e) | Apr 07, 2022 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | [8199781e64](https://linux-hardware.org/?probe=8199781e64) | Mar 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [321d0c1b4a](https://linux-hardware.org/?probe=321d0c1b4a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [5db5bac582](https://linux-hardware.org/?probe=5db5bac582) | Mar 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [da23c76a90](https://linux-hardware.org/?probe=da23c76a90) | Mar 19, 2022 |
| Acer          | TravelMate P214-53          | [a3ad6439b8](https://linux-hardware.org/?probe=a3ad6439b8) | Mar 17, 2022 |
| HP            | ProBook 450 G4              | [87d97b3c00](https://linux-hardware.org/?probe=87d97b3c00) | Mar 05, 2022 |
| Acer          | TravelMate P214-53          | [87f30f494f](https://linux-hardware.org/?probe=87f30f494f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [62c028a881](https://linux-hardware.org/?probe=62c028a881) | Feb 16, 2022 |
| HP            | ProBook 440 G6              | [d7431ab69e](https://linux-hardware.org/?probe=d7431ab69e) | Jan 31, 2022 |
| Dell          | XPS 13 9360                 | [76d17811e3](https://linux-hardware.org/?probe=76d17811e3) | Jan 31, 2022 |
| Lenovo        | ThinkPad X230 2324A82       | [be92c29259](https://linux-hardware.org/?probe=be92c29259) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1e89749691](https://linux-hardware.org/?probe=1e89749691) | Jan 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [88f62c8333](https://linux-hardware.org/?probe=88f62c8333) | Jan 15, 2022 |
| HP            | ProBook 450 G4              | [38a7870ece](https://linux-hardware.org/?probe=38a7870ece) | Jan 13, 2022 |
| Dell          | Inspiron N5110              | [2fb0411785](https://linux-hardware.org/?probe=2fb0411785) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0d69dca8f3](https://linux-hardware.org/?probe=0d69dca8f3) | Jan 04, 2022 |
| HP            | Laptop 14s-dq2xxx           | [8e8da56e93](https://linux-hardware.org/?probe=8e8da56e93) | Jan 01, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [00696e3398](https://linux-hardware.org/?probe=00696e3398) | Dec 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| Dell          | Inspiron 5468               | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Dell          | Latitude 7480               | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| HP            | ProBook 450 G4              | [42edbb20ce](https://linux-hardware.org/?probe=42edbb20ce) | Dec 04, 2021 |
| HP            | EliteBook 8460p             | [07bcad31f5](https://linux-hardware.org/?probe=07bcad31f5) | Dec 02, 2021 |
| ASUSTek       | UX430UQ                     | [cf0cd5c862](https://linux-hardware.org/?probe=cf0cd5c862) | Dec 01, 2021 |
| ASUSTek       | UX430UQ                     | [5cd208a361](https://linux-hardware.org/?probe=5cd208a361) | Dec 01, 2021 |
| ASUSTek       | P453UJ                      | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| HP            | Pavilion Notebook           | [aa0a0e67b3](https://linux-hardware.org/?probe=aa0a0e67b3) | Nov 26, 2021 |
| HP            | Pavilion Notebook           | [9bffff74e0](https://linux-hardware.org/?probe=9bffff74e0) | Nov 26, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [623b2b0ba9](https://linux-hardware.org/?probe=623b2b0ba9) | Nov 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f1f7ca30e5](https://linux-hardware.org/?probe=f1f7ca30e5) | Nov 05, 2021 |
| ASUSTek       | X442UAR                     | [0db140fa3d](https://linux-hardware.org/?probe=0db140fa3d) | Nov 03, 2021 |
| HP            | ProBook 450 G5              | [d377aa2b23](https://linux-hardware.org/?probe=d377aa2b23) | Oct 17, 2021 |
| HP            | ProBook 450 G5              | [7447071c00](https://linux-hardware.org/?probe=7447071c00) | Oct 16, 2021 |
| HP            | ProBook 450 G5              | [0bf0387391](https://linux-hardware.org/?probe=0bf0387391) | Oct 07, 2021 |
| Acer          | Aspire V5-471               | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [883e0dec71](https://linux-hardware.org/?probe=883e0dec71) | Sep 19, 2021 |
| Dell          | Latitude E7250              | [275b9204f5](https://linux-hardware.org/?probe=275b9204f5) | Sep 13, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | [6a9842e166](https://linux-hardware.org/?probe=6a9842e166) | Sep 06, 2021 |
| ASUSTek       | X456UQ                      | [6ce8e44ad3](https://linux-hardware.org/?probe=6ce8e44ad3) | Sep 02, 2021 |
| Acer          | Aspire 4349                 | [527e511232](https://linux-hardware.org/?probe=527e511232) | Aug 27, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [48853e253b](https://linux-hardware.org/?probe=48853e253b) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | [c22e4ce5b4](https://linux-hardware.org/?probe=c22e4ce5b4) | Jul 29, 2021 |
| HP            | 250 G7 Notebook PC          | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| Unknown       | Unknown                     | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| ASUSTek       | X550JK                      | [ebd01f2605](https://linux-hardware.org/?probe=ebd01f2605) | Jul 22, 2021 |
| Dell          | Inspiron 3442               | [3b153ae2f9](https://linux-hardware.org/?probe=3b153ae2f9) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | [988fc9a599](https://linux-hardware.org/?probe=988fc9a599) | Jun 24, 2021 |
| HP            | 15                          | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| HP            | Laptop 14-ck0xxx            | [406cb898f1](https://linux-hardware.org/?probe=406cb898f1) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| ASUSTek       | UX310UAK                    | [4a79148721](https://linux-hardware.org/?probe=4a79148721) | Jun 03, 2021 |
| HP            | Laptop 14-ck0xxx            | [6b5f1170f9](https://linux-hardware.org/?probe=6b5f1170f9) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | [e2389864db](https://linux-hardware.org/?probe=e2389864db) | Jun 02, 2021 |
| HP            | ENVY TS 14 Sleekbook        | [f52091e51e](https://linux-hardware.org/?probe=f52091e51e) | May 31, 2021 |
| HP            | 15 Notebook PC              | [b34d6d63d9](https://linux-hardware.org/?probe=b34d6d63d9) | May 22, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | [8f1510061b](https://linux-hardware.org/?probe=8f1510061b) | May 18, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | [e78b76fcf3](https://linux-hardware.org/?probe=e78b76fcf3) | May 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [b7e4895fd8](https://linux-hardware.org/?probe=b7e4895fd8) | May 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [1254eab2b7](https://linux-hardware.org/?probe=1254eab2b7) | May 04, 2021 |
| HP            | 15                          | [fd4d562cd2](https://linux-hardware.org/?probe=fd4d562cd2) | May 04, 2021 |
| MSI           | Summit B14 A11MOT           | [9bdd91f198](https://linux-hardware.org/?probe=9bdd91f198) | May 02, 2021 |
| HP            | ProBook 440 G7              | [dbcbb68258](https://linux-hardware.org/?probe=dbcbb68258) | Apr 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [367455807e](https://linux-hardware.org/?probe=367455807e) | Mar 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1de185d0da](https://linux-hardware.org/?probe=1de185d0da) | Mar 22, 2021 |
| Dell          | Latitude E4300              | [2ccfcf6a1b](https://linux-hardware.org/?probe=2ccfcf6a1b) | Mar 22, 2021 |
| HP            | 15                          | [860412bddc](https://linux-hardware.org/?probe=860412bddc) | Mar 20, 2021 |
| HP            | 15                          | [62447250f9](https://linux-hardware.org/?probe=62447250f9) | Mar 17, 2021 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | [4ee1271923](https://linux-hardware.org/?probe=4ee1271923) | Mar 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [6343267ab7](https://linux-hardware.org/?probe=6343267ab7) | Mar 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [47123299d4](https://linux-hardware.org/?probe=47123299d4) | Mar 09, 2021 |
| HP            | ProBook 450 G4              | [a8091a8c28](https://linux-hardware.org/?probe=a8091a8c28) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8f8fe2c911](https://linux-hardware.org/?probe=8f8fe2c911) | Mar 06, 2021 |
| ASUSTek       | X411UNV                     | [009f3bb5e5](https://linux-hardware.org/?probe=009f3bb5e5) | Feb 27, 2021 |
| HP            | 15                          | [e74fa488e9](https://linux-hardware.org/?probe=e74fa488e9) | Feb 27, 2021 |
| Apple         | MacBookPro8,1               | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| HP            | EliteBook 8470p             | [b414109f66](https://linux-hardware.org/?probe=b414109f66) | Feb 07, 2021 |
| HP            | EliteBook 8470p             | [08a1160725](https://linux-hardware.org/?probe=08a1160725) | Feb 07, 2021 |
| HP            | Notebook                    | [df39c8aaf8](https://linux-hardware.org/?probe=df39c8aaf8) | Feb 02, 2021 |
| ASUSTek       | X45C                        | [349beec2d5](https://linux-hardware.org/?probe=349beec2d5) | Jan 27, 2021 |
| HP            | ProBook 450 G2              | [c9e8f99464](https://linux-hardware.org/?probe=c9e8f99464) | Jan 21, 2021 |
| Lenovo        | ThinkPad T450 20BUS2021M    | [60929bb3d1](https://linux-hardware.org/?probe=60929bb3d1) | Jan 21, 2021 |
| HP            | Notebook                    | [d14d8fe5db](https://linux-hardware.org/?probe=d14d8fe5db) | Jan 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [5ee0809420](https://linux-hardware.org/?probe=5ee0809420) | Jan 16, 2021 |
| HP            | 15                          | [1b3597829c](https://linux-hardware.org/?probe=1b3597829c) | Jan 05, 2021 |
| HP            | ProBook 450 G4              | [150aed5937](https://linux-hardware.org/?probe=150aed5937) | Dec 28, 2020 |
| Acer          | Aspire A315-21              | [f3aaccf16d](https://linux-hardware.org/?probe=f3aaccf16d) | Dec 19, 2020 |
| HP            | ProBook 450 G2              | [eff007611b](https://linux-hardware.org/?probe=eff007611b) | Dec 16, 2020 |
| Acer          | Aspire A315-21              | [1eec63b277](https://linux-hardware.org/?probe=1eec63b277) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| MSI           | GS63 7RD                    | [51929f5d16](https://linux-hardware.org/?probe=51929f5d16) | Dec 05, 2020 |
| HP            | ProBook 450 G2              | [4d0297d500](https://linux-hardware.org/?probe=4d0297d500) | Nov 15, 2020 |
| HP            | ProBook 450 G2              | [2898db77af](https://linux-hardware.org/?probe=2898db77af) | Nov 14, 2020 |
| Acer          | Nitro AN515-43              | [399693b152](https://linux-hardware.org/?probe=399693b152) | Nov 04, 2020 |
| HP            | 15                          | [751dbba280](https://linux-hardware.org/?probe=751dbba280) | Nov 04, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [20da8831d7](https://linux-hardware.org/?probe=20da8831d7) | Oct 29, 2020 |
| Notebook      | DCL C483                    | [ed2bb10c86](https://linux-hardware.org/?probe=ed2bb10c86) | Oct 29, 2020 |
| HP            | ENVY Sleekbook 4            | [b2377a6388](https://linux-hardware.org/?probe=b2377a6388) | Oct 29, 2020 |
| Dell          | Inspiron 3521               | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Acer          | Aspire E5-576               | [1f7d96b34a](https://linux-hardware.org/?probe=1f7d96b34a) | Oct 27, 2020 |
| ASUSTek       | P453UA                      | [a376addbeb](https://linux-hardware.org/?probe=a376addbeb) | Oct 21, 2020 |
| Acer          | Aspire E5-575               | [218b3ce742](https://linux-hardware.org/?probe=218b3ce742) | Oct 12, 2020 |
| Acer          | Nitro AN515-43              | [da1765fe36](https://linux-hardware.org/?probe=da1765fe36) | Oct 11, 2020 |
| Acer          | Aspire A515-51G             | [be8091856c](https://linux-hardware.org/?probe=be8091856c) | Oct 09, 2020 |
| Acer          | Nitro AN515-43              | [a6f1865423](https://linux-hardware.org/?probe=a6f1865423) | Oct 07, 2020 |
| ASUSTek       | X510UQ                      | [75933321b6](https://linux-hardware.org/?probe=75933321b6) | Oct 02, 2020 |
| Acer          | Aspire 4752                 | [ae7fe5907d](https://linux-hardware.org/?probe=ae7fe5907d) | Sep 27, 2020 |
| ASUSTek       | X555LF                      | [ed0ef70a05](https://linux-hardware.org/?probe=ed0ef70a05) | Sep 19, 2020 |
| HP            | ProBook 440 G5              | [d7b1ce1a01](https://linux-hardware.org/?probe=d7b1ce1a01) | Sep 15, 2020 |
| Notebook      | N2x0LU                      | [86354a1c26](https://linux-hardware.org/?probe=86354a1c26) | Sep 14, 2020 |
| ASUSTek       | X510UQ                      | [e289d19d20](https://linux-hardware.org/?probe=e289d19d20) | Sep 14, 2020 |
| ASUSTek       | X555LF                      | [22629ba9b2](https://linux-hardware.org/?probe=22629ba9b2) | Sep 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | [43ddcf3c95](https://linux-hardware.org/?probe=43ddcf3c95) | Sep 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [38548d7877](https://linux-hardware.org/?probe=38548d7877) | Sep 01, 2020 |
| Acer          | Aspire A315-21              | [3edf866f94](https://linux-hardware.org/?probe=3edf866f94) | Aug 22, 2020 |
| Acer          | Aspire E5-576               | [3a9beeb9f4](https://linux-hardware.org/?probe=3a9beeb9f4) | Aug 16, 2020 |
| HP            | ProBook 450 G4              | [3c3b21f81b](https://linux-hardware.org/?probe=3c3b21f81b) | Aug 15, 2020 |
| HP            | 14                          | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| HP            | EliteBook 850 G2            | [1c81c3c24d](https://linux-hardware.org/?probe=1c81c3c24d) | Jul 30, 2020 |
| Acer          | Aspire E5-473               | [27a9cd08a6](https://linux-hardware.org/?probe=27a9cd08a6) | Jul 26, 2020 |
| Acer          | Aspire E5-473               | [9c3656a710](https://linux-hardware.org/?probe=9c3656a710) | Jul 24, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [3c50b289eb](https://linux-hardware.org/?probe=3c50b289eb) | Jul 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [e800855127](https://linux-hardware.org/?probe=e800855127) | Jul 21, 2020 |
| Dell          | Latitude E7470              | [74e59971a2](https://linux-hardware.org/?probe=74e59971a2) | Jul 09, 2020 |
| ASUSTek       | X200CA                      | [eb79a1863c](https://linux-hardware.org/?probe=eb79a1863c) | Jul 08, 2020 |
| ASUSTek       | X200CA                      | [374493e07f](https://linux-hardware.org/?probe=374493e07f) | Jul 08, 2020 |
| HP            | EliteBook 2570p             | [04f260c99a](https://linux-hardware.org/?probe=04f260c99a) | Jul 06, 2020 |
| HP            | EliteBook 2570p             | [aa5a987949](https://linux-hardware.org/?probe=aa5a987949) | Jul 06, 2020 |
| Acer          | Aspire A315-21              | [e8be3d4a45](https://linux-hardware.org/?probe=e8be3d4a45) | Jul 02, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [bedb334316](https://linux-hardware.org/?probe=bedb334316) | Jun 11, 2020 |
| Acer          | Aspire A315-21              | [0690307575](https://linux-hardware.org/?probe=0690307575) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | [2d68573dcb](https://linux-hardware.org/?probe=2d68573dcb) | Jun 04, 2020 |
| HP            | ProBook 450 G4              | [e10a133997](https://linux-hardware.org/?probe=e10a133997) | Jun 02, 2020 |
| HP            | ProBook 450 G4              | [7b57cf3668](https://linux-hardware.org/?probe=7b57cf3668) | May 30, 2020 |
| HP            | Notebook                    | [024a28eb0b](https://linux-hardware.org/?probe=024a28eb0b) | May 23, 2020 |
| Dell          | Latitude E7450              | [f3e9ca7a40](https://linux-hardware.org/?probe=f3e9ca7a40) | May 21, 2020 |
| Lenovo        | ThinkPad E470 20H1A029SG    | [6afaed7f7f](https://linux-hardware.org/?probe=6afaed7f7f) | May 21, 2020 |
| Dell          | Latitude E7450              | [e6818ffd7d](https://linux-hardware.org/?probe=e6818ffd7d) | May 21, 2020 |
| Notebook      | W9x0LU                      | [c7455fcb18](https://linux-hardware.org/?probe=c7455fcb18) | May 17, 2020 |
| Lenovo        | V330-14IKB 81B0             | [5d81beb457](https://linux-hardware.org/?probe=5d81beb457) | May 17, 2020 |
| ASUSTek       | X510UNR                     | [7b1a18ebf9](https://linux-hardware.org/?probe=7b1a18ebf9) | May 09, 2020 |
| ASUSTek       | X556URK                     | [63c6b5a357](https://linux-hardware.org/?probe=63c6b5a357) | May 08, 2020 |
| Notebook      | N750BU                      | [e3f870729f](https://linux-hardware.org/?probe=e3f870729f) | Apr 23, 2020 |
| HP            | Mini 210-4000               | [61c0ab33d8](https://linux-hardware.org/?probe=61c0ab33d8) | Feb 28, 2020 |
| HP            | ProBook 450 G4              | [729f8e494d](https://linux-hardware.org/?probe=729f8e494d) | Feb 14, 2020 |
| Dell          | Inspiron 13-5378            | [357823f120](https://linux-hardware.org/?probe=357823f120) | Feb 03, 2020 |
| HP            | ProBook 450 G4              | [e9a4da7f1c](https://linux-hardware.org/?probe=e9a4da7f1c) | Jan 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [4fad937155](https://linux-hardware.org/?probe=4fad937155) | Jan 10, 2020 |
| Lenovo        | ThinkPad L380 20M6S22500    | [15c43def70](https://linux-hardware.org/?probe=15c43def70) | Jan 09, 2020 |
| Dell          | Inspiron 5559               | [9d4e0d1911](https://linux-hardware.org/?probe=9d4e0d1911) | Jan 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [2d0bca85ea](https://linux-hardware.org/?probe=2d0bca85ea) | Dec 29, 2019 |
| HP            | ProBook 450 G4              | [d85b25cd22](https://linux-hardware.org/?probe=d85b25cd22) | Dec 24, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [30c00cb837](https://linux-hardware.org/?probe=30c00cb837) | Dec 14, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [e004d9f500](https://linux-hardware.org/?probe=e004d9f500) | Dec 14, 2019 |
| ASUSTek       | E202SA                      | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| HP            | ProBook 450 G4              | [44d09b2105](https://linux-hardware.org/?probe=44d09b2105) | Nov 19, 2019 |
| HP            | ProBook 450 G4              | [3fc910f23c](https://linux-hardware.org/?probe=3fc910f23c) | Nov 19, 2019 |
| Acer          | Aspire E5-571G              | [afc9fdb4b3](https://linux-hardware.org/?probe=afc9fdb4b3) | Nov 14, 2019 |
| Acer          | Aspire E5-571G              | [7914862967](https://linux-hardware.org/?probe=7914862967) | Nov 14, 2019 |
| HP            | ProBook 450 G1              | [671ea53b31](https://linux-hardware.org/?probe=671ea53b31) | Sep 22, 2019 |
| HP            | ProBook 450 G1              | [53b4bf1914](https://linux-hardware.org/?probe=53b4bf1914) | Sep 22, 2019 |
| ASUSTek       | X441UA                      | [6022620aee](https://linux-hardware.org/?probe=6022620aee) | Sep 17, 2019 |
| ASUSTek       | X441UA                      | [d0632368ab](https://linux-hardware.org/?probe=d0632368ab) | Sep 04, 2019 |
| HP            | Notebook                    | [2ce0b2ff35](https://linux-hardware.org/?probe=2ce0b2ff35) | Jul 04, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [298e510c05](https://linux-hardware.org/?probe=298e510c05) | Jun 22, 2019 |
| Lenovo        | ThinkPad X230 2324F51       | [9291e8f5f3](https://linux-hardware.org/?probe=9291e8f5f3) | Jun 22, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [70fecd4e42](https://linux-hardware.org/?probe=70fecd4e42) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | [ee5c9fcc02](https://linux-hardware.org/?probe=ee5c9fcc02) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | [424ee39d57](https://linux-hardware.org/?probe=424ee39d57) | Jun 04, 2019 |
| Lenovo        | S10-3                       | [09f132c2fa](https://linux-hardware.org/?probe=09f132c2fa) | May 27, 2019 |
| Daffodil C... | DCL S4                      | [291cd2445c](https://linux-hardware.org/?probe=291cd2445c) | May 08, 2019 |
| HP            | ProBook 4540s               | [a8b0fbe3a8](https://linux-hardware.org/?probe=a8b0fbe3a8) | Apr 22, 2019 |
| ASUSTek       | X510UQ                      | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 33        | 23.4%   |
| Arch                         | 8         | 5.67%   |
| ArcoLinux Rolling            | 7         | 4.96%   |
| Ubuntu 19.10                 | 4         | 2.84%   |
| Ubuntu 18.04                 | 4         | 2.84%   |
| KDE neon 20.04               | 4         | 2.84%   |
| Fedora 33                    | 4         | 2.84%   |
| OpenMandriva 4.2             | 3         | 2.13%   |
| Manjaro 20.0.1               | 3         | 2.13%   |
| Manjaro                      | 3         | 2.13%   |
| Arch Rolling                 | 3         | 2.13%   |
| Zorin 16                     | 2         | 1.42%   |
| Zorin 15                     | 2         | 1.42%   |
| Ubuntu 19.04                 | 2         | 1.42%   |
| Ubuntu 18.10                 | 2         | 1.42%   |
| Pop!_OS 21.10                | 2         | 1.42%   |
| Manjaro 21.2.6               | 2         | 1.42%   |
| Manjaro 18.0.4               | 2         | 1.42%   |
| Linux Mint 20.1              | 2         | 1.42%   |
| Linux Mint 20                | 2         | 1.42%   |
| Kubuntu 20.04                | 2         | 1.42%   |
| Fedora 34                    | 2         | 1.42%   |
| Debian 11                    | 2         | 1.42%   |
| Ubuntu 22.04                 | 1         | 0.71%   |
| Ubuntu 21.04                 | 1         | 0.71%   |
| Ubuntu 20.10                 | 1         | 0.71%   |
| Ubuntu 16.04                 | 1         | 0.71%   |
| Pop!_OS 21.04                | 1         | 0.71%   |
| Pop!_OS 20.10                | 1         | 0.71%   |
| Parrot 4.5                   | 1         | 0.71%   |
| Parrot 4.11                  | 1         | 0.71%   |
| Parrot 4.10                  | 1         | 0.71%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.71%   |
| Manjaro 21.2.1               | 1         | 0.71%   |
| Manjaro 21.1.2               | 1         | 0.71%   |
| Manjaro 21.0.5               | 1         | 0.71%   |
| Manjaro 21.0.4               | 1         | 0.71%   |
| Manjaro 21.0.3               | 1         | 0.71%   |
| Manjaro 21.0                 | 1         | 0.71%   |
| Manjaro 20.2.1               | 1         | 0.71%   |
| Manjaro 20.2                 | 1         | 0.71%   |
| Manjaro 20.1.2               | 1         | 0.71%   |
| Manjaro 20.1.1               | 1         | 0.71%   |
| Manjaro 18.1.5               | 1         | 0.71%   |
| LMDE 4                       | 1         | 0.71%   |
| Linux Mint 20.2              | 1         | 0.71%   |
| Linux Mint 19.3              | 1         | 0.71%   |
| Kubuntu 20.10                | 1         | 0.71%   |
| Kubuntu 2.0                  | 1         | 0.71%   |
| Fedora 32                    | 1         | 0.71%   |
| Endless 3.9.5                | 1         | 0.71%   |
| Endless 3.9.0                | 1         | 0.71%   |
| Endless 3.8.5                | 1         | 0.71%   |
| Endless 3.8.4                | 1         | 0.71%   |
| Endless 3.8.3                | 1         | 0.71%   |
| Endless 3.8.1                | 1         | 0.71%   |
| Endless 3.7.5                | 1         | 0.71%   |
| EndeavourOS Rolling          | 1         | 0.71%   |
| Deepin 15.11                 | 1         | 0.71%   |
| Debian 10                    | 1         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 48        | 36.92%  |
| Manjaro      | 16        | 12.31%  |
| Arch         | 11        | 8.46%   |
| ArcoLinux    | 7         | 5.38%   |
| Linux Mint   | 6         | 4.62%   |
| Fedora       | 6         | 4.62%   |
| Zorin        | 4         | 3.08%   |
| Pop!_OS      | 4         | 3.08%   |
| Kubuntu      | 4         | 3.08%   |
| KDE neon     | 4         | 3.08%   |
| Endless      | 4         | 3.08%   |
| OpenMandriva | 3         | 2.31%   |
| Debian       | 3         | 2.31%   |
| Parrot       | 2         | 1.54%   |
| openSUSE     | 1         | 0.77%   |
| LMDE         | 1         | 0.77%   |
| EndeavourOS  | 1         | 0.77%   |
| Deepin       | 1         | 0.77%   |
| Clear Linux  | 1         | 0.77%   |
| CentOS       | 1         | 0.77%   |
| BlackPanther | 1         | 0.77%   |
| Artix        | 1         | 0.77%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 4.52%   |
| 5.4.0-52-generic         | 3         | 1.94%   |
| 5.4.0-40-generic         | 3         | 1.94%   |
| 5.4.0-29-generic         | 3         | 1.94%   |
| 5.10.14-desktop-1omv4002 | 3         | 1.94%   |
| 5.9.16-1-MANJARO         | 2         | 1.29%   |
| 5.8.0-50-generic         | 2         | 1.29%   |
| 5.8.0-41-generic         | 2         | 1.29%   |
| 5.8.0-14-generic         | 2         | 1.29%   |
| 5.7.19-2-MANJARO         | 2         | 1.29%   |
| 5.6.11-1-MANJARO         | 2         | 1.29%   |
| 5.4.8-arch1-1            | 2         | 1.29%   |
| 5.4.0-53-generic         | 2         | 1.29%   |
| 5.4.0-19-generic         | 2         | 1.29%   |
| 5.3.0-24-generic         | 2         | 1.29%   |
| 5.3.0-23-generic         | 2         | 1.29%   |
| 5.13.0-35-generic        | 2         | 1.29%   |
| 5.13.0-28-generic        | 2         | 1.29%   |
| 5.11.0-40-generic        | 2         | 1.29%   |
| 5.11.0-27-generic        | 2         | 1.29%   |
| 5.10.52-1-lts            | 2         | 1.29%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.65%   |
| 5.9.11-200.fc33.x86_64   | 1         | 0.65%   |
| 5.8.4-200.fc32.x86_64    | 1         | 0.65%   |
| 5.8.16.a-1-hardened      | 1         | 0.65%   |
| 5.8.12-1-default         | 1         | 0.65%   |
| 5.8.0-7630-generic       | 1         | 0.65%   |
| 5.8.0-63-generic         | 1         | 0.65%   |
| 5.8.0-55-generic         | 1         | 0.65%   |
| 5.8.0-44-generic         | 1         | 0.65%   |
| 5.8.0-43-generic         | 1         | 0.65%   |
| 5.8.0-40-generic         | 1         | 0.65%   |
| 5.8.0-38-generic         | 1         | 0.65%   |
| 5.7.0-2parrot2-amd64     | 1         | 0.65%   |
| 5.4.81-1-lts             | 1         | 0.65%   |
| 5.4.68-1-lts             | 1         | 0.65%   |
| 5.4.64-1-lts             | 1         | 0.65%   |
| 5.4.40-1-MANJARO         | 1         | 0.65%   |
| 5.4.15-2-MANJARO         | 1         | 0.65%   |
| 5.4.0-88-generic         | 1         | 0.65%   |
| 5.4.0-73-generic         | 1         | 0.65%   |
| 5.4.0-62-generic         | 1         | 0.65%   |
| 5.4.0-58-generic         | 1         | 0.65%   |
| 5.4.0-49-generic         | 1         | 0.65%   |
| 5.4.0-47-generic         | 1         | 0.65%   |
| 5.4.0-45-generic         | 1         | 0.65%   |
| 5.4.0-39-generic         | 1         | 0.65%   |
| 5.4.0-33-generic         | 1         | 0.65%   |
| 5.4.0-31-generic         | 1         | 0.65%   |
| 5.4.0-26-generic         | 1         | 0.65%   |
| 5.4.0-110-generic        | 1         | 0.65%   |
| 5.3.0-51-generic         | 1         | 0.65%   |
| 5.3.0-46-generic         | 1         | 0.65%   |
| 5.3.0-40-generic         | 1         | 0.65%   |
| 5.3.0-29-generic         | 1         | 0.65%   |
| 5.18.6-1-MANJARO         | 1         | 0.65%   |
| 5.17.9-arch1-1           | 1         | 0.65%   |
| 5.17.5-arch1-1           | 1         | 0.65%   |
| 5.17.4-zen1-1-zen        | 1         | 0.65%   |
| 5.16.20-2-MANJARO        | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 27        | 18.49%  |
| 5.8.0   | 13        | 8.9%    |
| 5.11.0  | 11        | 7.53%   |
| 5.13.0  | 7         | 4.79%   |
| 5.3.0   | 6         | 4.11%   |
| 5.10.0  | 4         | 2.74%   |
| 5.0.0   | 4         | 2.74%   |
| 4.18.0  | 4         | 2.74%   |
| 4.15.0  | 4         | 2.74%   |
| 5.9.16  | 3         | 2.05%   |
| 5.10.14 | 3         | 2.05%   |
| 4.19.0  | 3         | 2.05%   |
| 5.7.19  | 2         | 1.37%   |
| 5.6.11  | 2         | 1.37%   |
| 5.4.8   | 2         | 1.37%   |
| 5.16.15 | 2         | 1.37%   |
| 5.15.5  | 2         | 1.37%   |
| 5.10.52 | 2         | 1.37%   |
| 5.9.11  | 1         | 0.68%   |
| 5.8.4   | 1         | 0.68%   |
| 5.8.16  | 1         | 0.68%   |
| 5.8.12  | 1         | 0.68%   |
| 5.7.0   | 1         | 0.68%   |
| 5.4.81  | 1         | 0.68%   |
| 5.4.68  | 1         | 0.68%   |
| 5.4.64  | 1         | 0.68%   |
| 5.4.40  | 1         | 0.68%   |
| 5.4.15  | 1         | 0.68%   |
| 5.18.6  | 1         | 0.68%   |
| 5.17.9  | 1         | 0.68%   |
| 5.17.5  | 1         | 0.68%   |
| 5.17.4  | 1         | 0.68%   |
| 5.16.20 | 1         | 0.68%   |
| 5.16.12 | 1         | 0.68%   |
| 5.16.0  | 1         | 0.68%   |
| 5.15.8  | 1         | 0.68%   |
| 5.15.6  | 1         | 0.68%   |
| 5.15.38 | 1         | 0.68%   |
| 5.15.28 | 1         | 0.68%   |
| 5.15.13 | 1         | 0.68%   |
| 5.15.12 | 1         | 0.68%   |
| 5.15.0  | 1         | 0.68%   |
| 5.14.5  | 1         | 0.68%   |
| 5.14.14 | 1         | 0.68%   |
| 5.13.6  | 1         | 0.68%   |
| 5.12.12 | 1         | 0.68%   |
| 5.12.11 | 1         | 0.68%   |
| 5.12.0  | 1         | 0.68%   |
| 5.11.8  | 1         | 0.68%   |
| 5.11.6  | 1         | 0.68%   |
| 5.11.2  | 1         | 0.68%   |
| 5.11.12 | 1         | 0.68%   |
| 5.11.1  | 1         | 0.68%   |
| 5.10.84 | 1         | 0.68%   |
| 5.10.83 | 1         | 0.68%   |
| 5.10.60 | 1         | 0.68%   |
| 5.10.34 | 1         | 0.68%   |
| 5.10.20 | 1         | 0.68%   |
| 5.10.18 | 1         | 0.68%   |
| 5.1.5   | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 33        | 23.74%  |
| 5.8     | 16        | 11.51%  |
| 5.11    | 14        | 10.07%  |
| 5.10    | 13        | 9.35%   |
| 5.15    | 8         | 5.76%   |
| 5.13    | 8         | 5.76%   |
| 5.3     | 6         | 4.32%   |
| 5.16    | 5         | 3.6%    |
| 4.18    | 5         | 3.6%    |
| 5.9     | 4         | 2.88%   |
| 5.0     | 4         | 2.88%   |
| 4.19    | 4         | 2.88%   |
| 4.15    | 4         | 2.88%   |
| 5.7     | 3         | 2.16%   |
| 5.17    | 3         | 2.16%   |
| 5.6     | 2         | 1.44%   |
| 5.14    | 2         | 1.44%   |
| 5.12    | 2         | 1.44%   |
| 5.1     | 2         | 1.44%   |
| 5.18    | 1         | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 125       | 98.43%  |
| i686   | 2         | 1.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| GNOME          | 69        | 52.27%  |
| KDE5           | 23        | 17.42%  |
| Unknown        | 16        | 12.12%  |
| XFCE           | 5         | 3.79%   |
| X-Cinnamon     | 5         | 3.79%   |
| awesome        | 3         | 2.27%   |
| MATE           | 2         | 1.52%   |
| KDE            | 2         | 1.52%   |
| i3-with-shmlog | 2         | 1.52%   |
| Unity          | 1         | 0.76%   |
| i3             | 1         | 0.76%   |
| DWM            | 1         | 0.76%   |
| Deepin         | 1         | 0.76%   |
| bspwm          | 1         | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 105       | 79.55%  |
| Wayland | 17        | 12.88%  |
| Unknown | 9         | 6.82%   |
| Tty     | 1         | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 66        | 50%     |
| GDM     | 25        | 18.94%  |
| SDDM    | 20        | 15.15%  |
| LightDM | 8         | 6.06%   |
| GDM3    | 7         | 5.3%    |
| TDM     | 6         | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 105       | 81.4%   |
| Unknown | 15        | 11.63%  |
| en_GB   | 4         | 3.1%    |
| C       | 3         | 2.33%   |
| en_IE   | 1         | 0.78%   |
| en_CA   | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 69        | 53.08%  |
| BIOS | 61        | 46.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 106       | 82.81%  |
| Overlay | 9         | 7.03%   |
| Btrfs   | 9         | 7.03%   |
| Unknown | 3         | 2.34%   |
| Xfs     | 1         | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 74        | 56.92%  |
| GPT     | 43        | 33.08%  |
| MBR     | 13        | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 110       | 85.27%  |
| Yes       | 19        | 14.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 52.34%  |
| Yes       | 61        | 47.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 37        | 29.13%  |
| Hewlett-Packard     | 36        | 28.35%  |
| Lenovo              | 16        | 12.6%   |
| Dell                | 15        | 11.81%  |
| Acer                | 13        | 10.24%  |
| Notebook            | 4         | 3.15%   |
| MSI                 | 2         | 1.57%   |
| Samsung Electronics | 1         | 0.79%   |
| Daffodil Computers  | 1         | 0.79%   |
| Apple               | 1         | 0.79%   |
| Unknown             | 1         | 0.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G4                                     | 5         | 3.94%   |
| HP ProBook 450 G2                                     | 2         | 1.57%   |
| HP Notebook                                           | 2         | 1.57%   |
| HP EliteBook 840 G3                                   | 2         | 1.57%   |
| ASUS X510UQ                                           | 2         | 1.57%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 1.57%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 1.57%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 1.57%   |
| ASUS VivoBook 14_ASUS Laptop X407UA                   | 2         | 1.57%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.79%   |
| Notebook W9x0LU                                       | 1         | 0.79%   |
| Notebook N750BU                                       | 1         | 0.79%   |
| Notebook N2x0LU                                       | 1         | 0.79%   |
| Notebook DCL C483                                     | 1         | 0.79%   |
| MSI Summit B14 A11MOT                                 | 1         | 0.79%   |
| MSI GS63 7RD                                          | 1         | 0.79%   |
| Lenovo V330-14IKB 81B0                                | 1         | 0.79%   |
| Lenovo ThinkPad X230 2324F51                          | 1         | 0.79%   |
| Lenovo ThinkPad X230 2324A82                          | 1         | 0.79%   |
| Lenovo ThinkPad T450 20BUS2021M                       | 1         | 0.79%   |
| Lenovo ThinkPad T430s 2356GPU                         | 1         | 0.79%   |
| Lenovo ThinkPad L380 20M6S22500                       | 1         | 0.79%   |
| Lenovo ThinkPad E490 20N9S1XE00                       | 1         | 0.79%   |
| Lenovo ThinkPad E470 20H1A029SG                       | 1         | 0.79%   |
| Lenovo S10-3                                          | 1         | 0.79%   |
| Lenovo Legion 5 15ARH05H 82B1                         | 1         | 0.79%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                      | 1         | 0.79%   |
| Lenovo IdeaPad 330-15IKB 81DE                         | 1         | 0.79%   |
| Lenovo IdeaPad 320-15IKB 81BG                         | 1         | 0.79%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.79%   |
| Lenovo IdeaPad 310-14ISK 80SL                         | 1         | 0.79%   |
| Lenovo IdeaPad 110-15IBR 80T7                         | 1         | 0.79%   |
| HP ZHAN 66 Pro A 14 G4 Notebook PC                    | 1         | 0.79%   |
| HP ProBook 4540s                                      | 1         | 0.79%   |
| HP ProBook 450 G8 Notebook PC                         | 1         | 0.79%   |
| HP ProBook 450 G5                                     | 1         | 0.79%   |
| HP ProBook 450 G1                                     | 1         | 0.79%   |
| HP ProBook 440 G8 Notebook PC                         | 1         | 0.79%   |
| HP ProBook 440 G7                                     | 1         | 0.79%   |
| HP ProBook 440 G6                                     | 1         | 0.79%   |
| HP ProBook 440 G5                                     | 1         | 0.79%   |
| HP Pavilion Notebook                                  | 1         | 0.79%   |
| HP Pavilion Laptop 15-cc1xx                           | 1         | 0.79%   |
| HP Mini 210-4000                                      | 1         | 0.79%   |
| HP Laptop 14s-dq2xxx                                  | 1         | 0.79%   |
| HP Laptop 14-ck0xxx                                   | 1         | 0.79%   |
| HP ENVY TS 14 Sleekbook                               | 1         | 0.79%   |
| HP ENVY Sleekbook 4                                   | 1         | 0.79%   |
| HP EliteBook 850 G2                                   | 1         | 0.79%   |
| HP EliteBook 8470p                                    | 1         | 0.79%   |
| HP EliteBook 8460p                                    | 1         | 0.79%   |
| HP EliteBook 2570p                                    | 1         | 0.79%   |
| HP 250 G7 Notebook PC                                 | 1         | 0.79%   |
| HP 240 G3                                             | 1         | 0.79%   |
| HP 15 Notebook PC                                     | 1         | 0.79%   |
| HP 15                                                 | 1         | 0.79%   |
| HP 14                                                 | 1         | 0.79%   |
| Dell XPS 13 9360                                      | 1         | 0.79%   |
| Dell Latitude E7470                                   | 1         | 0.79%   |
| Dell Latitude E7450                                   | 1         | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ASUS VivoBook          | 17        | 13.39%  |
| HP ProBook             | 15        | 11.81%  |
| Acer Aspire            | 11        | 8.66%   |
| Dell Inspiron          | 8         | 6.3%    |
| Lenovo ThinkPad        | 7         | 5.51%   |
| Lenovo IdeaPad         | 6         | 4.72%   |
| HP EliteBook           | 6         | 4.72%   |
| Dell Latitude          | 6         | 4.72%   |
| HP Pavilion            | 2         | 1.57%   |
| HP Notebook            | 2         | 1.57%   |
| HP Laptop              | 2         | 1.57%   |
| HP ENVY                | 2         | 1.57%   |
| HP 15                  | 2         | 1.57%   |
| ASUS X510UQ            | 2         | 1.57%   |
| Samsung 300E5EV        | 1         | 0.79%   |
| Notebook W9x0LU        | 1         | 0.79%   |
| Notebook N750BU        | 1         | 0.79%   |
| Notebook N2x0LU        | 1         | 0.79%   |
| Notebook DCL           | 1         | 0.79%   |
| MSI Summit             | 1         | 0.79%   |
| MSI GS63               | 1         | 0.79%   |
| Lenovo V330-14IKB      | 1         | 0.79%   |
| Lenovo S10-3           | 1         | 0.79%   |
| Lenovo Legion          | 1         | 0.79%   |
| HP ZHAN                | 1         | 0.79%   |
| HP Mini                | 1         | 0.79%   |
| HP 250                 | 1         | 0.79%   |
| HP 240                 | 1         | 0.79%   |
| HP 14                  | 1         | 0.79%   |
| Dell XPS               | 1         | 0.79%   |
| Daffodil Computers DCL | 1         | 0.79%   |
| ASUS ZenBook           | 1         | 0.79%   |
| ASUS X556URK           | 1         | 0.79%   |
| ASUS X555LF            | 1         | 0.79%   |
| ASUS X550JK            | 1         | 0.79%   |
| ASUS X510UNR           | 1         | 0.79%   |
| ASUS X507UB            | 1         | 0.79%   |
| ASUS X45C              | 1         | 0.79%   |
| ASUS X456UQ            | 1         | 0.79%   |
| ASUS X442UAR           | 1         | 0.79%   |
| ASUS X441UA            | 1         | 0.79%   |
| ASUS X411UNV           | 1         | 0.79%   |
| ASUS X200CA            | 1         | 0.79%   |
| ASUS UX430UQ           | 1         | 0.79%   |
| ASUS UX310UAK          | 1         | 0.79%   |
| ASUS TUF               | 1         | 0.79%   |
| ASUS P453UJ            | 1         | 0.79%   |
| ASUS P453UA            | 1         | 0.79%   |
| ASUS E202SA            | 1         | 0.79%   |
| Apple MacBookPro8      | 1         | 0.79%   |
| Acer TravelMate        | 1         | 0.79%   |
| Acer Nitro             | 1         | 0.79%   |
| Unknown                | 1         | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 22        | 17.32%  |
| 2017 | 20        | 15.75%  |
| 2018 | 16        | 12.6%   |
| 2019 | 14        | 11.02%  |
| 2015 | 14        | 11.02%  |
| 2012 | 10        | 7.87%   |
| 2014 | 8         | 6.3%    |
| 2021 | 6         | 4.72%   |
| 2011 | 6         | 4.72%   |
| 2013 | 5         | 3.94%   |
| 2020 | 4         | 3.15%   |
| 2010 | 1         | 0.79%   |
| 2008 | 1         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 127       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 116       | 89.23%  |
| Enabled  | 14        | 10.77%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 127       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 53        | 40.77%  |
| 3.01-4.0   | 41        | 31.54%  |
| 8.01-16.0  | 20        | 15.38%  |
| 16.01-24.0 | 12        | 9.23%   |
| 1.01-2.0   | 4         | 3.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 51        | 35.66%  |
| 2.01-3.0  | 47        | 32.87%  |
| 3.01-4.0  | 23        | 16.08%  |
| 4.01-8.0  | 12        | 8.39%   |
| 0.51-1.0  | 7         | 4.9%    |
| 8.01-16.0 | 2         | 1.4%    |
| 0.01-0.5  | 1         | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 92        | 71.32%  |
| 2      | 35        | 27.13%  |
| 3      | 2         | 1.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 84        | 65.63%  |
| Yes       | 44        | 34.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 77.34%  |
| No        | 29        | 22.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 98.43%  |
| No        | 2         | 1.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 85.94%  |
| No        | 18        | 14.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Bangladesh | 127       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dhaka             | 78        | 59.09%  |
| Chittagong        | 8         | 6.06%   |
| Rajshahi          | 7         | 5.3%    |
| Jessore           | 6         | 4.55%   |
| Tongi             | 4         | 3.03%   |
| Comilla           | 3         | 2.27%   |
| Sherpur           | 2         | 1.52%   |
| Narayanganj       | 2         | 1.52%   |
| Mirpur            | 2         | 1.52%   |
| Khulna            | 2         | 1.52%   |
| Azimpur           | 2         | 1.52%   |
| Wari              | 1         | 0.76%   |
| Sylhet            | 1         | 0.76%   |
| Savar Upazila     | 1         | 0.76%   |
| Rangpur City      | 1         | 0.76%   |
| Pirganj           | 1         | 0.76%   |
| Pabna Sadar       | 1         | 0.76%   |
| Pabna             | 1         | 0.76%   |
| NДЃrДЃyanganj | 1         | 0.76%   |
| Nalitabari        | 1         | 0.76%   |
| LДЃkshДЃm     | 1         | 0.76%   |
| Jamalpur          | 1         | 0.76%   |
| Gulshan           | 1         | 0.76%   |
| Faridpur          | 1         | 0.76%   |
| Dewangonj         | 1         | 0.76%   |
| Bogra             | 1         | 0.76%   |
| Belkuchi          | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 33        | 45     | 20.25%  |
| Seagate             | 31        | 41     | 19.02%  |
| Toshiba             | 28        | 36     | 17.18%  |
| Transcend           | 10        | 11     | 6.13%   |
| HGST                | 9         | 9      | 5.52%   |
| SanDisk             | 8         | 8      | 4.91%   |
| Samsung Electronics | 5         | 8      | 3.07%   |
| Hitachi             | 5         | 6      | 3.07%   |
| Micron Technology   | 4         | 4      | 2.45%   |
| SK hynix            | 3         | 3      | 1.84%   |
| Kingston            | 3         | 4      | 1.84%   |
| Intel               | 3         | 4      | 1.84%   |
| Corsair             | 3         | 5      | 1.84%   |
| A-DATA Technology   | 3         | 3      | 1.84%   |
| KingSpec            | 2         | 2      | 1.23%   |
| WDC WDS4            | 1         | 1      | 0.61%   |
| Silicon Motion      | 1         | 2      | 0.61%   |
| Ramsta              | 1         | 1      | 0.61%   |
| PNY                 | 1         | 1      | 0.61%   |
| Phison              | 1         | 1      | 0.61%   |
| Lexar               | 1         | 2      | 0.61%   |
| HS-SSD-E100         | 1         | 1      | 0.61%   |
| Hewlett-Packard     | 1         | 1      | 0.61%   |
| Crucial             | 1         | 2      | 0.61%   |
| Colorful            | 1         | 1      | 0.61%   |
| BIWIN               | 1         | 1      | 0.61%   |
| Apacer              | 1         | 1      | 0.61%   |
| Unknown             | 1         | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                | 14        | 8.54%   |
| Seagate ST1000LM035-1RK172 1TB        | 14        | 8.54%   |
| WDC WD10JPVX-60JC3T0 1TB              | 5         | 3.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 5         | 3.05%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 4         | 2.44%   |
| Toshiba MQ01ABD100 1TB                | 4         | 2.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 3         | 1.83%   |
| Transcend TS120GMTS420S 120GB SSD     | 3         | 1.83%   |
| SanDisk NVMe SSD Drive 512GB          | 3         | 1.83%   |
| Intel NVMe SSD Drive 512GB            | 3         | 1.83%   |
| HGST HTS541010A9E680 1TB              | 3         | 1.83%   |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 1.22%   |
| WDC WD10SPZX-24Z10T0 1TB              | 2         | 1.22%   |
| WDC WD10JPVX-60JC3T1 1TB              | 2         | 1.22%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB  | 2         | 1.22%   |
| Transcend TS240GMTS820S 240GB SSD     | 2         | 1.22%   |
| Toshiba THNSNK128GVN8 128GB SSD       | 2         | 1.22%   |
| Seagate ST9500325AS 500GB             | 2         | 1.22%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 1.22%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 1.22%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 1.22%   |
| Samsung SSD 860 EVO 500GB             | 2         | 1.22%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD   | 2         | 1.22%   |
| HGST HTS545050A7E680 500GB            | 2         | 1.22%   |
| HGST HTS541010B7E610 1TB              | 2         | 1.22%   |
| Corsair Force MP510 240GB             | 2         | 1.22%   |
| WDC WDS4 80G2G0B-00EPW0 480GB SSD     | 1         | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 0.61%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD      | 1         | 0.61%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 0.61%   |
| WDC WD5000LPCX-22VHAT0 500GB          | 1         | 0.61%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 0.61%   |
| WDC WD3200BPVT-60JJ5T0 320GB          | 1         | 0.61%   |
| WDC WD3200BPVT-00ZEST0 320GB          | 1         | 0.61%   |
| WDC WD1600BEVT-75ZCT1 160GB           | 1         | 0.61%   |
| WDC WD10SPZX-22Z10T1 1TB              | 1         | 0.61%   |
| WDC WD10SPZX-22Z10T0 1TB              | 1         | 0.61%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1         | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 0.61%   |
| WDC WD SSD 120GB                      | 1         | 0.61%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 1         | 0.61%   |
| Transcend TS512GSSD370 512GB          | 1         | 0.61%   |
| Transcend TS256GSSD230S 256GB         | 1         | 0.61%   |
| Transcend TS240GSSD220S 240GB         | 1         | 0.61%   |
| Transcend TS128GSSD370S 128GB         | 1         | 0.61%   |
| Transcend TS120GSSD220S 120GB         | 1         | 0.61%   |
| Toshiba MQ01ABF050 500GB              | 1         | 0.61%   |
| Toshiba MQ01ABF032 320GB              | 1         | 0.61%   |
| Toshiba MQ01ABD100V 1TB               | 1         | 0.61%   |
| Toshiba MQ01ABD050 500GB              | 1         | 0.61%   |
| Toshiba MQ01ABD032 320GB              | 1         | 0.61%   |
| Toshiba KXG50ZNV256G NVMe 256GB       | 1         | 0.61%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD   | 1         | 0.61%   |
| Toshiba HDWL110 1TB                   | 1         | 0.61%   |
| SK hynix NVMe SSD Drive 512GB         | 1         | 0.61%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD | 1         | 0.61%   |
| SK hynix BC511 NVMe 512GB             | 1         | 0.61%   |
| Silicon Motion NVMe SSD Drive 256GB   | 1         | 0.61%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1         | 0.61%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 31        | 41     | 34.44%  |
| Toshiba | 24        | 31     | 26.67%  |
| WDC     | 21        | 30     | 23.33%  |
| HGST    | 9         | 9      | 10%     |
| Hitachi | 5         | 6      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 20.41%  |
| Transcend           | 10        | 11     | 20.41%  |
| SanDisk             | 5         | 5      | 10.2%   |
| Micron Technology   | 4         | 4      | 8.16%   |
| Samsung Electronics | 3         | 5      | 6.12%   |
| A-DATA Technology   | 3         | 3      | 6.12%   |
| Toshiba             | 2         | 3      | 4.08%   |
| KingSpec            | 2         | 2      | 4.08%   |
| WDC WDS4            | 1         | 1      | 2.04%   |
| SK hynix            | 1         | 1      | 2.04%   |
| Ramsta              | 1         | 1      | 2.04%   |
| PNY                 | 1         | 1      | 2.04%   |
| Kingston            | 1         | 1      | 2.04%   |
| HS-SSD-E100         | 1         | 1      | 2.04%   |
| Hewlett-Packard     | 1         | 1      | 2.04%   |
| Crucial             | 1         | 2      | 2.04%   |
| Corsair             | 1         | 2      | 2.04%   |
| Apacer              | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 90        | 117    | 56.25%  |
| SSD     | 46        | 57     | 28.75%  |
| NVMe    | 22        | 29     | 13.75%  |
| Unknown | 2         | 2      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 175    | 83.21%  |
| NVMe | 22        | 29     | 16.06%  |
| SAS  | 1         | 1      | 0.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 84     | 50%     |
| 0.51-1.0   | 66        | 89     | 49.25%  |
| 1.01-2.0   | 1         | 1      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 36        | 27.07%  |
| 251-500    | 33        | 24.81%  |
| 501-1000   | 27        | 20.3%   |
| 1001-2000  | 13        | 9.77%   |
| 51-100     | 13        | 9.77%   |
| 1-20       | 5         | 3.76%   |
| 21-50      | 4         | 3.01%   |
| Unknown    | 2         | 1.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 46        | 33.09%  |
| 21-50     | 29        | 20.86%  |
| 101-250   | 24        | 17.27%  |
| 51-100    | 23        | 16.55%  |
| 251-500   | 7         | 5.04%   |
| 501-1000  | 6         | 4.32%   |
| 1001-2000 | 2         | 1.44%   |
| Unknown   | 2         | 1.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 2         | 4      | 12.5%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 12.5%   |
| WDC WD5000LPCX-22VHAT0 500GB                   | 1         | 1      | 6.25%   |
| WDC WD5000BPVT-22HXZT3 500GB                   | 1         | 1      | 6.25%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 6.25%   |
| WDC WD10JPVX-60JC3T0 1TB                       | 1         | 2      | 6.25%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 6.25%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD          | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 6.25%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 6.25%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 6.25%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 6.25%   |
| Hewlett-Packard SSD S600 240GB                 | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 4         | 5      | 25%     |
| HGST              | 4         | 4      | 25%     |
| Toshiba           | 3         | 5      | 18.75%  |
| Seagate           | 2         | 2      | 12.5%   |
| SK hynix          | 1         | 1      | 6.25%   |
| Micron Technology | 1         | 1      | 6.25%   |
| Hewlett-Packard   | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 30.77%  |
| HGST    | 4         | 4      | 30.77%  |
| Toshiba | 3         | 5      | 23.08%  |
| Seagate | 2         | 2      | 15.38%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 16     | 81.25%  |
| SSD  | 3         | 3      | 18.75%  |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 74        | 114    | 54.41%  |
| Works    | 46        | 72     | 33.82%  |
| Malfunc  | 16        | 19     | 11.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 114       | 80.28%  |
| AMD                          | 8         | 5.63%   |
| SanDisk                      | 6         | 4.23%   |
| Phison Electronics           | 3         | 2.11%   |
| Toshiba America Info Systems | 2         | 1.41%   |
| SK hynix                     | 2         | 1.41%   |
| Samsung Electronics          | 2         | 1.41%   |
| Kingston Technology Company  | 2         | 1.41%   |
| Silicon Motion               | 1         | 0.7%    |
| Shenzhen Longsys Electronics | 1         | 0.7%    |
| Biwin Storage Technology     | 1         | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 47        | 31.97%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 13        | 8.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 10        | 6.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 6.12%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 8         | 5.44%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 7         | 4.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 5         | 3.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 2.72%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 3         | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 2.04%   |
| Intel SSD 660P Series                                                                  | 3         | 2.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 2         | 1.36%   |
| Phison E12 NVMe Controller                                                             | 2         | 1.36%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 1.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 1.36%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 1         | 0.68%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 1         | 0.68%   |
| SK hynix Non-Volatile memory controller                                                | 1         | 0.68%   |
| SK hynix BC511                                                                         | 1         | 0.68%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 1         | 0.68%   |
| Shenzhen Longsys Non-Volatile memory controller                                        | 1         | 0.68%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.68%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 0.68%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 0.68%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.68%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.68%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 0.68%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 0.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 0.68%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.68%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.68%   |
| Biwin Storage Non-Volatile memory controller                                           | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 103       | 71.53%  |
| NVMe | 22        | 15.28%  |
| RAID | 16        | 11.11%  |
| IDE  | 3         | 2.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 92.13%  |
| AMD    | 10        | 7.87%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 7.87%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 7         | 5.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 4.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 4.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 4.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 3.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 3.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 3.15%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 3.15%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 3.15%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 3.15%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 2.36%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.36%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.36%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 2.36%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.57%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 2         | 1.57%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.57%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.57%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.57%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.57%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 1.57%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.57%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.79%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.79%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.79%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 0.79%   |
| Intel Core i5-4200H CPU @ 2.80GHz             | 1         | 0.79%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 0.79%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 0.79%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 0.79%   |
| Intel Core i3-5010U CPU @ 2.10GHz             | 1         | 0.79%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 1         | 0.79%   |
| Intel Core i3-2377M CPU @ 1.50GHz             | 1         | 0.79%   |
| Intel Core i3-2328M CPU @ 2.20GHz             | 1         | 0.79%   |
| Intel Core 2 Duo CPU P9400 @ 2.40GHz          | 1         | 0.79%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 0.79%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 0.79%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 0.79%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 1         | 0.79%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 0.79%   |
| Intel Atom CPU N2800 @ 1.86GHz                | 1         | 0.79%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 0.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 0.79%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 0.79%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 0.79%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 1         | 0.79%   |
| AMD E2-9000 RADEON R2, 4 COMPUTE CORES 2C+2G  | 1         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 57        | 44.88%  |
| Intel Core i3    | 30        | 23.62%  |
| Intel Core i7    | 13        | 10.24%  |
| Other            | 5         | 3.94%   |
| Intel Pentium    | 5         | 3.94%   |
| Intel Celeron    | 4         | 3.15%   |
| AMD Ryzen 7      | 4         | 3.15%   |
| AMD Ryzen 5      | 4         | 3.15%   |
| Intel Atom       | 2         | 1.57%   |
| Intel Core 2 Duo | 1         | 0.79%   |
| AMD Ryzen 3      | 1         | 0.79%   |
| AMD E2           | 1         | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 88        | 69.29%  |
| 4      | 34        | 26.77%  |
| 8      | 4         | 3.15%   |
| 1      | 1         | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 127       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 116       | 91.34%  |
| 1      | 11        | 8.66%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 126       | 99.21%  |
| Unknown        | 1         | 0.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 18.18%  |
| 0x806e9    | 22        | 16.67%  |
| 0x806ea    | 15        | 11.36%  |
| 0x406e3    | 10        | 7.58%   |
| 0x306d4    | 9         | 6.82%   |
| 0x306a9    | 6         | 4.55%   |
| 0x206a7    | 6         | 4.55%   |
| 0x806ec    | 5         | 3.79%   |
| 0x40651    | 5         | 3.79%   |
| 0x806eb    | 4         | 3.03%   |
| 0x406c4    | 4         | 3.03%   |
| 0x806c1    | 3         | 2.27%   |
| 0x706e5    | 3         | 2.27%   |
| 0x08108102 | 3         | 2.27%   |
| 0x306c3    | 2         | 1.52%   |
| 0x906e9    | 1         | 0.76%   |
| 0x406c3    | 1         | 0.76%   |
| 0x30678    | 1         | 0.76%   |
| 0x30661    | 1         | 0.76%   |
| 0x106ca    | 1         | 0.76%   |
| 0x10676    | 1         | 0.76%   |
| 0x0a50000c | 1         | 0.76%   |
| 0x08600104 | 1         | 0.76%   |
| 0x08108109 | 1         | 0.76%   |
| 0x0810100b | 1         | 0.76%   |
| 0x06006705 | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 52        | 40.94%  |
| Skylake     | 13        | 10.24%  |
| Broadwell   | 11        | 8.66%   |
| IvyBridge   | 9         | 7.09%   |
| SandyBridge | 8         | 6.3%    |
| Haswell     | 7         | 5.51%   |
| Silvermont  | 6         | 4.72%   |
| TigerLake   | 5         | 3.94%   |
| Zen+        | 4         | 3.15%   |
| IceLake     | 3         | 2.36%   |
| Zen 3       | 2         | 1.57%   |
| Zen 2       | 2         | 1.57%   |
| Bonnell     | 2         | 1.57%   |
| Zen         | 1         | 0.79%   |
| Penryn      | 1         | 0.79%   |
| Excavator   | 1         | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 72.22%  |
| Nvidia | 31        | 19.14%  |
| AMD    | 14        | 8.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 25        | 15.34%  |
| Intel UHD Graphics 620                                                                   | 15        | 9.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 7.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 6.13%   |
| Intel HD Graphics 5500                                                                   | 10        | 6.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 5.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 4.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 3.07%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 2.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 2.45%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 2.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.45%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.84%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.84%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.23%   |
| AMD Renoir                                                                               | 2         | 1.23%   |
| AMD Cezanne                                                                              | 2         | 1.23%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.61%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.61%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.61%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.61%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.61%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.61%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.61%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.61%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.61%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.61%   |
| Intel HD Graphics 630                                                                    | 1         | 0.61%   |
| Intel HD Graphics                                                                        | 1         | 0.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.61%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.61%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.61%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.61%   |
| AMD Topaz PRO [Radeon R5 M255]                                                           | 1         | 0.61%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.61%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 1         | 0.61%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 67.72%  |
| Intel + Nvidia | 27        | 21.26%  |
| 1 x AMD        | 5         | 3.94%   |
| Intel + AMD    | 4         | 3.15%   |
| AMD + Nvidia   | 4         | 3.15%   |
| 2 x AMD        | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 113       | 86.92%  |
| Proprietary | 15        | 11.54%  |
| Unknown     | 2         | 1.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 101       | 77.69%  |
| 1.01-2.0   | 18        | 13.85%  |
| 3.01-4.0   | 6         | 4.62%   |
| 0.01-0.5   | 3         | 2.31%   |
| 5.01-6.0   | 1         | 0.77%   |
| 0.51-1.0   | 1         | 0.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 36        | 24.32%  |
| AU Optronics            | 33        | 22.3%   |
| Chimei Innolux          | 29        | 19.59%  |
| LG Display              | 21        | 14.19%  |
| Samsung Electronics     | 8         | 5.41%   |
| Dell                    | 5         | 3.38%   |
| Hewlett-Packard         | 3         | 2.03%   |
| Goldstar                | 3         | 2.03%   |
| Chi Mei Optoelectronics | 2         | 1.35%   |
| ViewSonic               | 1         | 0.68%   |
| Sharp                   | 1         | 0.68%   |
| PANDA                   | 1         | 0.68%   |
| MSI                     | 1         | 0.68%   |
| ASUSTek Computer        | 1         | 0.68%   |
| Apple                   | 1         | 0.68%   |
| AOC                     | 1         | 0.68%   |
| Ancor Communications    | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 5.41%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 3         | 2.03%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 3         | 2.03%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 2.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.03%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 1.35%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 1.35%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 2         | 1.35%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch           | 2         | 1.35%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch       | 2         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.35%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 1.35%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 2         | 1.35%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.35%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1         | 0.68%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM043E 1600x1200 520x320mm 24.0-inch  | 1         | 0.68%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch     | 1         | 0.68%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 1         | 0.68%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch      | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4751 1366x768 344x194mm 15.5-inch  | 1         | 0.68%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.68%   |
| MSI MP241 MSI3BA9 1920x1080 527x296mm 23.8-inch                       | 1         | 0.68%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.68%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 0.68%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD0455 1366x768 310x174mm 14.0-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD03DF 1366x768 344x194mm 15.5-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.68%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch             | 1         | 0.68%   |
| Hewlett-Packard E223 HPN345C 1920x1080 476x268mm 21.5-inch            | 1         | 0.68%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 1         | 0.68%   |
| Goldstar LS1920wG GSM4BF0 1366x768 410x230mm 18.5-inch                | 1         | 0.68%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 1         | 0.68%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 0.68%   |
| Dell S2240L DELD054 1920x1080 476x267mm 21.5-inch                     | 1         | 0.68%   |
| Dell S2216H DELD07A 1920x1080 476x268mm 21.5-inch                     | 1         | 0.68%   |
| Dell E2015HV DELF05E 1600x900 430x240mm 19.4-inch                     | 1         | 0.68%   |
| Dell E1914H DELD03A 1366x768 410x230mm 18.5-inch                      | 1         | 0.68%   |
| Dell E1715S DELD061 1280x1024 338x270mm 17.0-inch                     | 1         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 1         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 1         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 1         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 1         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 1         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 1         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 70        | 50.72%  |
| 1920x1080 (FHD)   | 56        | 40.58%  |
| 1600x900 (HD+)    | 3         | 2.17%   |
| 1280x800 (WXGA)   | 2         | 1.45%   |
| 1024x600          | 2         | 1.45%   |
| 3840x2160 (4K)    | 1         | 0.72%   |
| 2560x1440 (QHD)   | 1         | 0.72%   |
| 2240x1400         | 1         | 0.72%   |
| 1920x1200 (WUXGA) | 1         | 0.72%   |
| 1280x1024 (SXGA)  | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 60        | 40.82%  |
| 13     | 36        | 24.49%  |
| 14     | 22        | 14.97%  |
| 21     | 8         | 5.44%   |
| 18     | 7         | 4.76%   |
| 12     | 4         | 2.72%   |
| 23     | 2         | 1.36%   |
| 11     | 2         | 1.36%   |
| 10     | 2         | 1.36%   |
| 27     | 1         | 0.68%   |
| 24     | 1         | 0.68%   |
| 19     | 1         | 0.68%   |
| 17     | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 111       | 76.03%  |
| 401-500     | 17        | 11.64%  |
| 201-300     | 15        | 10.27%  |
| 501-600     | 3         | 2.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 124       | 96.12%  |
| 16/10 | 4         | 3.1%    |
| 5/4   | 1         | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 60        | 41.1%   |
| 81-90          | 52        | 35.62%  |
| 141-150        | 8         | 5.48%   |
| 71-80          | 6         | 4.11%   |
| 201-250        | 6         | 4.11%   |
| 61-70          | 4         | 2.74%   |
| 151-200        | 4         | 2.74%   |
| 51-60          | 2         | 1.37%   |
| 41-50          | 2         | 1.37%   |
| 301-350        | 1         | 0.68%   |
| 251-300        | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 69        | 48.59%  |
| 121-160 | 56        | 39.44%  |
| 51-100  | 12        | 8.45%   |
| 161-240 | 5         | 3.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 109       | 84.5%   |
| 2     | 18        | 13.95%  |
| 3     | 1         | 0.78%   |
| 0     | 1         | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 88        | 44.44%  |
| Intel                 | 64        | 32.32%  |
| Qualcomm Atheros      | 35        | 17.68%  |
| Ralink Technology     | 3         | 1.52%   |
| Broadcom              | 3         | 1.52%   |
| Samsung Electronics   | 1         | 0.51%   |
| Ralink                | 1         | 0.51%   |
| MediaTek              | 1         | 0.51%   |
| Dell                  | 1         | 0.51%   |
| Arduino SA            | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57        | 24.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 7.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 6.52%   |
| Intel Wireless 8265 / 8275                                        | 13        | 5.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 5.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 4.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 3.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 3.04%   |
| Intel Wireless 3165                                               | 6         | 2.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.61%   |
| Intel Wireless 8260                                               | 5         | 2.17%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.3%    |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.3%    |
| Intel Wireless 7265                                               | 3         | 1.3%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.87%   |
| Intel Wireless 3160                                               | 2         | 0.87%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.43%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.43%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.43%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.43%   |
| Intel Wireless 7260                                               | 1         | 0.43%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.43%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 0.43%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 0.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.43%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.43%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                              | 1         | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.43%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.43%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 0.43%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1         | 0.43%   |
| Arduino SA Uno R3 (CDC ACM)                                       | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 62        | 47.69%  |
| Qualcomm Atheros      | 35        | 26.92%  |
| Realtek Semiconductor | 25        | 19.23%  |
| Ralink Technology     | 3         | 2.31%   |
| Broadcom              | 2         | 1.54%   |
| Ralink                | 1         | 0.77%   |
| MediaTek              | 1         | 0.77%   |
| Dell                  | 1         | 0.77%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 15        | 11.54%  |
| Intel Wireless 8265 / 8275                                     | 13        | 10%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 9.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 7.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 5.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 5.38%   |
| Intel Wireless 3165                                            | 6         | 4.62%   |
| Intel Wireless 8260                                            | 5         | 3.85%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 3.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.31%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 2.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.31%   |
| Intel Wireless 7265                                            | 3         | 2.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 2.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.54%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.54%   |
| Intel Wireless 3160                                            | 2         | 1.54%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.77%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.77%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.77%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.77%   |
| Intel Wireless 7260                                            | 1         | 0.77%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.77%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.77%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 0.77%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 77        | 77.78%  |
| Intel                 | 16        | 16.16%  |
| Qualcomm Atheros      | 3         | 3.03%   |
| Broadcom              | 2         | 2.02%   |
| Samsung Electronics   | 1         | 1.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57        | 57.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 18.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 6.06%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 4.04%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 3.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.02%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.01%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.01%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.01%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.01%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 125       | 55.56%  |
| Ethernet | 99        | 44%     |
| Modem    | 1         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 87.6%   |
| Ethernet | 16        | 12.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 92        | 72.44%  |
| 1     | 35        | 27.56%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 127       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 45.45%  |
| IMC Networks                    | 18        | 16.36%  |
| Realtek Semiconductor           | 13        | 11.82%  |
| Qualcomm Atheros Communications | 9         | 8.18%   |
| Lite-On Technology              | 9         | 8.18%   |
| Broadcom                        | 6         | 5.45%   |
| Foxconn / Hon Hai               | 2         | 1.82%   |
| Toshiba                         | 1         | 0.91%   |
| Ralink                          | 1         | 0.91%   |
| Hewlett-Packard                 | 1         | 0.91%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 30        | 27.27%  |
| IMC Networks Bluetooth Device                     | 11        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                  | 10        | 9.09%   |
| Realtek Bluetooth Radio                           | 7         | 6.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 6         | 5.45%   |
| IMC Networks Bluetooth Radio                      | 6         | 5.45%   |
| Qualcomm Atheros  Bluetooth Device                | 4         | 3.64%   |
| Intel Bluetooth Device                            | 4         | 3.64%   |
| Realtek  Bluetooth 4.2 Adapter                    | 3         | 2.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 3         | 2.73%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 2         | 1.82%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 2         | 1.82%   |
| Lite-On Bluetooth Device                          | 2         | 1.82%   |
| Intel AX200 Bluetooth                             | 2         | 1.82%   |
| Broadcom HP Portable SoftSailing                  | 2         | 1.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 1.82%   |
| Toshiba Bluetooth Radio                           | 1         | 0.91%   |
| Realtek RTL8821A Bluetooth                        | 1         | 0.91%   |
| Ralink RT3290 Bluetooth                           | 1         | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.91%   |
| Qualcomm Atheros AR3012 Bluetooth                 | 1         | 0.91%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.91%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.91%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 0.91%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 0.91%   |
| Foxconn / Hon Hai Wireless_Device                 | 1         | 0.91%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 0.91%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 1         | 0.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                 | 1         | 0.91%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 116       | 88.55%  |
| AMD                    | 10        | 7.63%   |
| Nvidia                 | 4         | 3.05%   |
| Generalplus Technology | 1         | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 53        | 33.54%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 6.96%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 6.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 6.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 6.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 5.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 3.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 3.16%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 3.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.9%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.63%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.63%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.63%   |
| Generalplus Technology IMYB 7.1 Channel                                                           | 1         | 0.63%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 31.52%  |
| SK hynix            | 24        | 26.09%  |
| Micron Technology   | 10        | 10.87%  |
| A-DATA Technology   | 6         | 6.52%   |
| Kingston            | 5         | 5.43%   |
| Unknown             | 3         | 3.26%   |
| Transcend           | 3         | 3.26%   |
| G.Skill             | 3         | 3.26%   |
| Team                | 2         | 2.17%   |
| Ramaxel Technology  | 2         | 2.17%   |
| Unknown (C509)      | 1         | 1.09%   |
| Unknown (768A)      | 1         | 1.09%   |
| Nanya Technology    | 1         | 1.09%   |
| Crucial             | 1         | 1.09%   |
| Unknown             | 1         | 1.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 4.35%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 4.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 3.26%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 3.26%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 2.17%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 2.17%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 2.17%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 2.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 2.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 2.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 2.17%   |
| Samsung RAM M471A1K44BM0-CRC 8192MB SODIMM DDR4 2400MT/s            | 2         | 2.17%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 2.17%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 2         | 2.17%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 1.09%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                         | 1         | 1.09%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 1.09%   |
| Unknown (C509) RAM Module 4GB SODIMM DDR4 2400MT/s                  | 1         | 1.09%   |
| Unknown (768A) RAM Module 8192MB SODIMM DDR4 3200MT/s               | 1         | 1.09%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s                 | 1         | 1.09%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.09%   |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s                 | 1         | 1.09%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s               | 1         | 1.09%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s               | 1         | 1.09%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 1         | 1.09%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2133MT/s                     | 1         | 1.09%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.09%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.09%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.09%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 1.09%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.09%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.09%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 1.09%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.09%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 1.09%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                      | 1         | 1.09%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 1.09%   |
| Samsung RAM M471B5673DZ1-CF8 2048MB SODIMM DDR3 1067MT/s            | 1         | 1.09%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.09%   |
| Samsung RAM M471A5244BB0-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.09%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s               | 1         | 1.09%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s               | 1         | 1.09%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.09%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.09%   |
| Samsung RAM M471A1G43EB1-CPB 8192MB SODIMM DDR4 2133MT/s            | 1         | 1.09%   |
| Ramaxel RAM RMT3170EF68F9W1600 4096MB SODIMM DDR3 1600MT/s          | 1         | 1.09%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 1         | 1.09%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                | 1         | 1.09%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 1         | 1.09%   |
| Micron RAM 8ATF51264HZ-2G1B1 8GB SODIMM DDR4 2667MT/s               | 1         | 1.09%   |
| Micron RAM 8ATF51264AZ-2G1A2 4096MB SODIMM DDR4 2133MT/s            | 1         | 1.09%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.09%   |
| Micron RAM 4ATF51264HZ-2G3E1 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.09%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 1         | 1.09%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.09%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.09%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s               | 1         | 1.09%   |
| Kingston RAM KKRVFX-MIE 8192MB SODIMM DDR4 3200MT/s                 | 1         | 1.09%   |
| Kingston RAM HP687515-H66-MCN 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.09%   |
| Kingston RAM CL15-15-15 D4-2133 4096MB SODIMM DDR4 2133MT/s         | 1         | 1.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 66.67%  |
| DDR3   | 19        | 27.54%  |
| LPDDR4 | 3         | 4.35%   |
| LPDDR3 | 1         | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 65        | 98.48%  |
| Row Of Chips | 1         | 1.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 37        | 49.33%  |
| 8192  | 30        | 40%     |
| 16384 | 5         | 6.67%   |
| 2048  | 2         | 2.67%   |
| 32768 | 1         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 25        | 33.33%  |
| 1600  | 16        | 21.33%  |
| 2400  | 12        | 16%     |
| 2133  | 9         | 12%     |
| 3200  | 6         | 8%      |
| 3266  | 2         | 2.67%   |
| 1067  | 2         | 2.67%   |
| 8400  | 1         | 1.33%   |
| 1867  | 1         | 1.33%   |
| 1334  | 1         | 1.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L132 Series | 1         | 100%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 22.5%   |
| IMC Networks                           | 25        | 20.83%  |
| Cheng Uei Precision Industry (Foxlink) | 14        | 11.67%  |
| Realtek Semiconductor                  | 10        | 8.33%   |
| Quanta                                 | 8         | 6.67%   |
| Sunplus Innovation Technology          | 7         | 5.83%   |
| Acer                                   | 6         | 5%      |
| Lite-On Technology                     | 5         | 4.17%   |
| Suyin                                  | 4         | 3.33%   |
| Microdia                               | 4         | 3.33%   |
| Luxvisions Innotech Limited            | 4         | 3.33%   |
| Silicon Motion                         | 2         | 1.67%   |
| Primax Electronics                     | 2         | 1.67%   |
| Syntek                                 | 1         | 0.83%   |
| Apple                                  | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 8         | 6.67%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 8         | 6.67%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 7         | 5.83%   |
| IMC Networks VGA UVC WebCam                                                | 5         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 4         | 3.33%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 3         | 2.5%    |
| Lite-On HP HD Camera                                                       | 3         | 2.5%    |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 3         | 2.5%    |
| Chicony HD WebCam                                                          | 3         | 2.5%    |
| Chicony EasyCamera                                                         | 3         | 2.5%    |
| Suyin Integrated_Webcam_HD                                                 | 2         | 1.67%   |
| Suyin HP Truevision HD                                                     | 2         | 1.67%   |
| Sunplus Laptop Integrated Webcam HD                                        | 2         | 1.67%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 1.67%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.67%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 1.67%   |
| Quanta VGA WebCam                                                          | 2         | 1.67%   |
| Quanta HD Webcam                                                           | 2         | 1.67%   |
| Primax HP HD Webcam [Fixed]                                                | 2         | 1.67%   |
| Lite-On Integrated Camera                                                  | 2         | 1.67%   |
| IMC Networks Integrated Camera                                             | 2         | 1.67%   |
| Chicony USB2.0 Camera                                                      | 2         | 1.67%   |
| Chicony Integrated Camera                                                  | 2         | 1.67%   |
| Chicony HP HD Webcam                                                       | 2         | 1.67%   |
| Chicony HP HD Camera                                                       | 2         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 2         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 2         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 2         | 1.67%   |
| Acer HD Webcam                                                             | 2         | 1.67%   |
| Syntek Integrated Camera                                                   | 1         | 0.83%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 0.83%   |
| Sunplus Integrated Webcam                                                  | 1         | 0.83%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 0.83%   |
| Sunplus Dell HD Webcam                                                     | 1         | 0.83%   |
| Sunplus Asus Webcam                                                        | 1         | 0.83%   |
| Silicon Motion WebCam SC-10HDD12636N                                       | 1         | 0.83%   |
| Silicon Motion Endoscope camera                                            | 1         | 0.83%   |
| Realtek USB Camera                                                         | 1         | 0.83%   |
| Realtek Lenovo easy camera                                                 | 1         | 0.83%   |
| Realtek Integrated Webcam_HD                                               | 1         | 0.83%   |
| Realtek HD WebCam                                                          | 1         | 0.83%   |
| Quanta HP Webcam                                                           | 1         | 0.83%   |
| Quanta HP TrueVision HD Camera                                             | 1         | 0.83%   |
| Quanta HP HD Camera                                                        | 1         | 0.83%   |
| Quanta HD User Facing                                                      | 1         | 0.83%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 0.83%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 0.83%   |
| Microdia Integrated Webcam HD                                              | 1         | 0.83%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 1         | 0.83%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 0.83%   |
| Chicony WebCam                                                             | 1         | 0.83%   |
| Chicony thinkpad t430s camera                                              | 1         | 0.83%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 0.83%   |
| Chicony HP Webcam-50                                                       | 1         | 0.83%   |
| Chicony HP Truevision HD camera                                            | 1         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 1         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 1         | 0.83%   |
| Apple FaceTime HD Camera                                                   | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 23        | 82.14%  |
| Synaptics             | 3         | 10.71%  |
| Elan Microelectronics | 2         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 46.43%  |
| Validity Sensors VFS491                                                    | 3         | 10.71%  |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 7.14%   |
| Elan ELAN:Fingerprint                                                      | 2         | 7.14%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Synaptics  WBDI                                                            | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 83        | 62.88%  |
| 1     | 42        | 31.82%  |
| 2     | 6         | 4.55%   |
| 3     | 1         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 28        | 52.83%  |
| Graphics card         | 11        | 20.75%  |
| Chipcard              | 5         | 9.43%   |
| Camera                | 3         | 5.66%   |
| Net/wireless          | 2         | 3.77%   |
| Multimedia controller | 2         | 3.77%   |
| Card reader           | 1         | 1.89%   |
| Bluetooth             | 1         | 1.89%   |

