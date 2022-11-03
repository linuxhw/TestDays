Linux Mint - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Linux Mint.

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

Total: 11442

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | G15 5515                    | [92f1423303](https://linux-hardware.org/?probe=92f1423303) | Nov 02, 2022 |
| ASUSTek       | X540SAA                     | [ccaedd7155](https://linux-hardware.org/?probe=ccaedd7155) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [a3b1926b7e](https://linux-hardware.org/?probe=a3b1926b7e) | Nov 02, 2022 |
| Lenovo        | G560 0679                   | [c97e8f3436](https://linux-hardware.org/?probe=c97e8f3436) | Nov 02, 2022 |
| HP            | EliteBook 2730p             | [79830976d8](https://linux-hardware.org/?probe=79830976d8) | Nov 02, 2022 |
| Dell          | G15 5515                    | [dae7c630d5](https://linux-hardware.org/?probe=dae7c630d5) | Nov 02, 2022 |
| Dell          | Inspiron 15-3567            | [a9b57edf35](https://linux-hardware.org/?probe=a9b57edf35) | Nov 02, 2022 |
| Dell          | Inspiron 15 3511            | [5786a01590](https://linux-hardware.org/?probe=5786a01590) | Nov 02, 2022 |
| HP            | ProBook 4530s               | [6490664312](https://linux-hardware.org/?probe=6490664312) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [9fa0489d64](https://linux-hardware.org/?probe=9fa0489d64) | Nov 01, 2022 |
| HP            | ProBook 4530s               | [34682f3bfe](https://linux-hardware.org/?probe=34682f3bfe) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [411a5da53c](https://linux-hardware.org/?probe=411a5da53c) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | [4cdb36db63](https://linux-hardware.org/?probe=4cdb36db63) | Nov 01, 2022 |
| HUAWEI        | MACHC-WAX9                  | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| ASUSTek       | N61Vg                       | [27f288e5f1](https://linux-hardware.org/?probe=27f288e5f1) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | [05eeb9e341](https://linux-hardware.org/?probe=05eeb9e341) | Nov 01, 2022 |
| Packard Be... | EasyNote TE11BZ             | [0301f1ddf1](https://linux-hardware.org/?probe=0301f1ddf1) | Oct 31, 2022 |
| ASUSTek       | K54L                        | [200f6044c2](https://linux-hardware.org/?probe=200f6044c2) | Oct 31, 2022 |
| Lenovo        | G700                        | [9bf9b4e263](https://linux-hardware.org/?probe=9bf9b4e263) | Oct 31, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| HP            | Laptop 15-bs1xx             | [fabbcc9035](https://linux-hardware.org/?probe=fabbcc9035) | Oct 30, 2022 |
| ASUSTek       | G74Sx                       | [c24c24ab27](https://linux-hardware.org/?probe=c24c24ab27) | Oct 30, 2022 |
| HP            | 15                          | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| Lenovo        | V110-15IAP 80TG             | [01d8b89e0d](https://linux-hardware.org/?probe=01d8b89e0d) | Oct 30, 2022 |
| Dell          | Studio 1735                 | [8f070a2831](https://linux-hardware.org/?probe=8f070a2831) | Oct 30, 2022 |
| Lenovo        | V110-15IAP 80TG             | [183feb626d](https://linux-hardware.org/?probe=183feb626d) | Oct 30, 2022 |
| HP            | ProBook 6540b               | [be9c128b00](https://linux-hardware.org/?probe=be9c128b00) | Oct 30, 2022 |
| HP            | ProBook 6560b               | [89feda4b09](https://linux-hardware.org/?probe=89feda4b09) | Oct 30, 2022 |
| HP            | Unknown                     | [6e024c825e](https://linux-hardware.org/?probe=6e024c825e) | Oct 30, 2022 |
| HP            | Laptop 17-by1xxx            | [b3e8975edf](https://linux-hardware.org/?probe=b3e8975edf) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | [18ca81370b](https://linux-hardware.org/?probe=18ca81370b) | Oct 29, 2022 |
| HP            | Laptop 17-bs0xx             | [68238274ff](https://linux-hardware.org/?probe=68238274ff) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | [0a95698cb6](https://linux-hardware.org/?probe=0a95698cb6) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [ce9df2cf8f](https://linux-hardware.org/?probe=ce9df2cf8f) | Oct 29, 2022 |
| SANTECH       | PCx0Dx                      | [24462321e8](https://linux-hardware.org/?probe=24462321e8) | Oct 29, 2022 |
| Acer          | Nitro AN515-52              | [38570237ac](https://linux-hardware.org/?probe=38570237ac) | Oct 29, 2022 |
| Acer          | Nitro AN515-52              | [5551d222b2](https://linux-hardware.org/?probe=5551d222b2) | Oct 29, 2022 |
| ASUSTek       | X751NV                      | [9ef2717db0](https://linux-hardware.org/?probe=9ef2717db0) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| ASUSTek       | K55VJ                       | [6dc11e517b](https://linux-hardware.org/?probe=6dc11e517b) | Oct 29, 2022 |
| Wortmann      | CR700                       | [7030308edf](https://linux-hardware.org/?probe=7030308edf) | Oct 29, 2022 |
| Dell          | Inspiron 7737               | [f352df76ef](https://linux-hardware.org/?probe=f352df76ef) | Oct 29, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0DD0... | [973a3662b9](https://linux-hardware.org/?probe=973a3662b9) | Oct 29, 2022 |
| Kruger&Mat... | KM1406                      | [70b8441ccf](https://linux-hardware.org/?probe=70b8441ccf) | Oct 29, 2022 |
| Dell          | Inspiron 3583               | [4f6c1e374f](https://linux-hardware.org/?probe=4f6c1e374f) | Oct 29, 2022 |
| ASUSTek       | K50C                        | [af80714f09](https://linux-hardware.org/?probe=af80714f09) | Oct 29, 2022 |
| Acer          | Aspire SW5-012              | [90dd31edc8](https://linux-hardware.org/?probe=90dd31edc8) | Oct 29, 2022 |
| ASUSTek       | K50C                        | [ca606469d8](https://linux-hardware.org/?probe=ca606469d8) | Oct 29, 2022 |
| Prestigio     | PSB141S01                   | [646d3fd287](https://linux-hardware.org/?probe=646d3fd287) | Oct 28, 2022 |
| Lenovo        | ThinkPad Edge E320 1298R... | [c79d1e6209](https://linux-hardware.org/?probe=c79d1e6209) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| Dell          | Latitude 5531               | [a7ff9a34d2](https://linux-hardware.org/?probe=a7ff9a34d2) | Oct 28, 2022 |
| Dell          | Latitude 5531               | [73ddced77b](https://linux-hardware.org/?probe=73ddced77b) | Oct 28, 2022 |
| Fujitsu       | LIFEBOOK U728               | [c5867e7dd3](https://linux-hardware.org/?probe=c5867e7dd3) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| Dell          | XPS 15 9510                 | [d3879c6bb0](https://linux-hardware.org/?probe=d3879c6bb0) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [2829b0b18f](https://linux-hardware.org/?probe=2829b0b18f) | Oct 28, 2022 |
| Unknown       | Unknown                     | [c867c45a75](https://linux-hardware.org/?probe=c867c45a75) | Oct 28, 2022 |
| Samsung       | 275E4E/275E5E               | [d3aebcbac6](https://linux-hardware.org/?probe=d3aebcbac6) | Oct 27, 2022 |
| Unknown       | Unknown                     | [967c2c956d](https://linux-hardware.org/?probe=967c2c956d) | Oct 27, 2022 |
| Dell          | Inspiron 15-7568            | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | [7ffc8c3537](https://linux-hardware.org/?probe=7ffc8c3537) | Oct 27, 2022 |
| Acer          | Aspire A315-54              | [6de38f7802](https://linux-hardware.org/?probe=6de38f7802) | Oct 27, 2022 |
| ASUSTek       | Q304UAK                     | [2c51d603ee](https://linux-hardware.org/?probe=2c51d603ee) | Oct 27, 2022 |
| HP            | ProBook 6560b               | [222a5c2dbe](https://linux-hardware.org/?probe=222a5c2dbe) | Oct 27, 2022 |
| ASUSTek       | Q304UAK                     | [4b624e6f98](https://linux-hardware.org/?probe=4b624e6f98) | Oct 27, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [3541e2e011](https://linux-hardware.org/?probe=3541e2e011) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| Acer          | Swift SF314-512             | [951c734c1b](https://linux-hardware.org/?probe=951c734c1b) | Oct 27, 2022 |
| MSI           | Katana GF66 12UC            | [9b8f917e6b](https://linux-hardware.org/?probe=9b8f917e6b) | Oct 27, 2022 |
| HP            | ProBook 450 G3              | [4aa258716b](https://linux-hardware.org/?probe=4aa258716b) | Oct 26, 2022 |
| HP            | ProBook 450 G3              | [26d1b8b2b2](https://linux-hardware.org/?probe=26d1b8b2b2) | Oct 26, 2022 |
| Acer          | Aspire A315-21              | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| HP            | ProBook 640 G1              | [e30a33bfd8](https://linux-hardware.org/?probe=e30a33bfd8) | Oct 26, 2022 |
| Google        | Akemi                       | [45fd84f413](https://linux-hardware.org/?probe=45fd84f413) | Oct 26, 2022 |
| HP            | EliteBook 840 G5            | [4b28c73302](https://linux-hardware.org/?probe=4b28c73302) | Oct 26, 2022 |
| Dell          | Latitude E4300              | [8ee3fadd0b](https://linux-hardware.org/?probe=8ee3fadd0b) | Oct 26, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [c19eaa0502](https://linux-hardware.org/?probe=c19eaa0502) | Oct 26, 2022 |
| HP            | Pavilion dv6                | [03e2594419](https://linux-hardware.org/?probe=03e2594419) | Oct 25, 2022 |
| Dell          | Precision 5560              | [c6cfa3f96d](https://linux-hardware.org/?probe=c6cfa3f96d) | Oct 25, 2022 |
| Dell          | Precision 5560              | [e0dce17c1f](https://linux-hardware.org/?probe=e0dce17c1f) | Oct 25, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [814da05eec](https://linux-hardware.org/?probe=814da05eec) | Oct 25, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [80177955c3](https://linux-hardware.org/?probe=80177955c3) | Oct 25, 2022 |
| Lenovo        | G40-80 80JE                 | [97dfa18602](https://linux-hardware.org/?probe=97dfa18602) | Oct 25, 2022 |
| Toshiba       | Satellite U920t             | [268814e9ab](https://linux-hardware.org/?probe=268814e9ab) | Oct 25, 2022 |
| HP            | EliteBook 8570p             | [c3ec764ff3](https://linux-hardware.org/?probe=c3ec764ff3) | Oct 25, 2022 |
| HP            | 8433 11                     | [81740a5a8e](https://linux-hardware.org/?probe=81740a5a8e) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [18931ec5f6](https://linux-hardware.org/?probe=18931ec5f6) | Oct 25, 2022 |
| Lenovo        | V15-IIL 82C5                | [a56ad41b2f](https://linux-hardware.org/?probe=a56ad41b2f) | Oct 25, 2022 |
| HP            | 250 G6 Notebook PC          | [e2baff543b](https://linux-hardware.org/?probe=e2baff543b) | Oct 24, 2022 |
| Sony          | SVE1712Z1EB                 | [23b6ac5cde](https://linux-hardware.org/?probe=23b6ac5cde) | Oct 24, 2022 |
| Olivetti      | Olibook P75B                | [a1b4023949](https://linux-hardware.org/?probe=a1b4023949) | Oct 24, 2022 |
| Dell          | Studio 1735                 | [21959a7db7](https://linux-hardware.org/?probe=21959a7db7) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [e198c305e4](https://linux-hardware.org/?probe=e198c305e4) | Oct 24, 2022 |
| HP            | Laptop 17-cp0xxx            | [4a818d766f](https://linux-hardware.org/?probe=4a818d766f) | Oct 24, 2022 |
| Dell          | Latitude E7240              | [33c37015df](https://linux-hardware.org/?probe=33c37015df) | Oct 24, 2022 |
| ASUSTek       | X550LC                      | [75c0c3e97b](https://linux-hardware.org/?probe=75c0c3e97b) | Oct 24, 2022 |
| Dell          | XPS L412Z                   | [92d8a4b47a](https://linux-hardware.org/?probe=92d8a4b47a) | Oct 24, 2022 |
| Apple         | MacBookAir7,2               | [7b901320c7](https://linux-hardware.org/?probe=7b901320c7) | Oct 24, 2022 |
| Apple         | MacBookAir7,2               | [daac29aff2](https://linux-hardware.org/?probe=daac29aff2) | Oct 24, 2022 |
| Dell          | Studio 1735                 | [4385640990](https://linux-hardware.org/?probe=4385640990) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4c0e49ae2b](https://linux-hardware.org/?probe=4c0e49ae2b) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | [753874362e](https://linux-hardware.org/?probe=753874362e) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [8138e910ce](https://linux-hardware.org/?probe=8138e910ce) | Oct 23, 2022 |
| HP            | 15                          | [5baa47ecd1](https://linux-hardware.org/?probe=5baa47ecd1) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | [33bef6bb6f](https://linux-hardware.org/?probe=33bef6bb6f) | Oct 23, 2022 |
| Acer          | Aspire A315-53              | [5388646329](https://linux-hardware.org/?probe=5388646329) | Oct 23, 2022 |
| Apple         | MacBookPro8,1               | [da114c9e74](https://linux-hardware.org/?probe=da114c9e74) | Oct 23, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [62bdd854b4](https://linux-hardware.org/?probe=62bdd854b4) | Oct 23, 2022 |
| Dell          | Vostro 1520                 | [a5106ca47d](https://linux-hardware.org/?probe=a5106ca47d) | Oct 22, 2022 |
| Dell          | XPS 13 9305                 | [8fec9e2536](https://linux-hardware.org/?probe=8fec9e2536) | Oct 22, 2022 |
| Lenovo        | Legion Y730-17ICH 81HG      | [c9a85159dd](https://linux-hardware.org/?probe=c9a85159dd) | Oct 22, 2022 |
| Acer          | TravelMate P256-M           | [7ca952de68](https://linux-hardware.org/?probe=7ca952de68) | Oct 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [1f26696990](https://linux-hardware.org/?probe=1f26696990) | Oct 22, 2022 |
| Lenovo        | Legion Y730-17ICH 81HG      | [15a66ac64c](https://linux-hardware.org/?probe=15a66ac64c) | Oct 22, 2022 |
| Dell          | Latitude E4300              | [fb144bfcb2](https://linux-hardware.org/?probe=fb144bfcb2) | Oct 22, 2022 |
| ASUSTek       | X550LN                      | [7a6daf6023](https://linux-hardware.org/?probe=7a6daf6023) | Oct 22, 2022 |
| Acer          | Aspire A315-53              | [72f0c231fb](https://linux-hardware.org/?probe=72f0c231fb) | Oct 21, 2022 |
| Positivo      | S14CT01                     | [1a5f77c8f9](https://linux-hardware.org/?probe=1a5f77c8f9) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | [c7e03dae2f](https://linux-hardware.org/?probe=c7e03dae2f) | Oct 21, 2022 |
| HP            | EliteBook 820 G1            | [7abef2546e](https://linux-hardware.org/?probe=7abef2546e) | Oct 21, 2022 |
| Google        | Treeya                      | [1a93d190b0](https://linux-hardware.org/?probe=1a93d190b0) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [de5adb6775](https://linux-hardware.org/?probe=de5adb6775) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | [0f73d884ff](https://linux-hardware.org/?probe=0f73d884ff) | Oct 21, 2022 |
| Acer          | Aspire S3                   | [a24603a142](https://linux-hardware.org/?probe=a24603a142) | Oct 20, 2022 |
| Gigabyte      | X7X7                        | [f2c35e3917](https://linux-hardware.org/?probe=f2c35e3917) | Oct 20, 2022 |
| Lenovo        | G780                        | [986b0fdbd0](https://linux-hardware.org/?probe=986b0fdbd0) | Oct 20, 2022 |
| Toshiba       | Satellite C660              | [3632c8a48d](https://linux-hardware.org/?probe=3632c8a48d) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | [ef1acaa7da](https://linux-hardware.org/?probe=ef1acaa7da) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | [3ec2887574](https://linux-hardware.org/?probe=3ec2887574) | Oct 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [f5073cd7a2](https://linux-hardware.org/?probe=f5073cd7a2) | Oct 20, 2022 |
| ASUSTek       | X540SAA                     | [e3fef524ee](https://linux-hardware.org/?probe=e3fef524ee) | Oct 20, 2022 |
| Lenovo        | G505s 20255                 | [a105e25fa5](https://linux-hardware.org/?probe=a105e25fa5) | Oct 20, 2022 |
| GPU Compan... | GWNR71517                   | [27ae96160e](https://linux-hardware.org/?probe=27ae96160e) | Oct 20, 2022 |
| GPU Compan... | GWNR71517                   | [d55bceb8fb](https://linux-hardware.org/?probe=d55bceb8fb) | Oct 19, 2022 |
| Toshiba       | Satellite A300              | [ce897bc567](https://linux-hardware.org/?probe=ce897bc567) | Oct 19, 2022 |
| Lenovo        | ThinkPad T460s 20FAS1Q10... | [a96060006f](https://linux-hardware.org/?probe=a96060006f) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | [eb7940e5a4](https://linux-hardware.org/?probe=eb7940e5a4) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [e5f7b07e9c](https://linux-hardware.org/?probe=e5f7b07e9c) | Oct 19, 2022 |
| Acer          | Aspire V5-571PG             | [e00a049460](https://linux-hardware.org/?probe=e00a049460) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [25bb674789](https://linux-hardware.org/?probe=25bb674789) | Oct 19, 2022 |
| Dell          | XPS L412Z                   | [eb1b1f7950](https://linux-hardware.org/?probe=eb1b1f7950) | Oct 19, 2022 |
| ASUSTek       | N82JV                       | [7157bb5872](https://linux-hardware.org/?probe=7157bb5872) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6271fbb0fb](https://linux-hardware.org/?probe=6271fbb0fb) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [0d145a7293](https://linux-hardware.org/?probe=0d145a7293) | Oct 19, 2022 |
| Dell          | Latitude E7440              | [5c81fc2db0](https://linux-hardware.org/?probe=5c81fc2db0) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | [098e362854](https://linux-hardware.org/?probe=098e362854) | Oct 19, 2022 |
| HP            | ENVY Laptop 17-bw0xxx       | [6b7263006f](https://linux-hardware.org/?probe=6b7263006f) | Oct 18, 2022 |
| Dell          | G15 5510                    | [1286ecf9dd](https://linux-hardware.org/?probe=1286ecf9dd) | Oct 18, 2022 |
| HP            | 15                          | [072d4ee592](https://linux-hardware.org/?probe=072d4ee592) | Oct 18, 2022 |
| Lenovo        | ThinkPad T15g Gen 1 20US... | [ec42bc932e](https://linux-hardware.org/?probe=ec42bc932e) | Oct 18, 2022 |
| HP            | Laptop 17-bs0xx             | [369934a06c](https://linux-hardware.org/?probe=369934a06c) | Oct 18, 2022 |
| Acer          | Aspire 5830T                | [2423f8bf08](https://linux-hardware.org/?probe=2423f8bf08) | Oct 18, 2022 |
| Acer          | Swift SF314-54              | [04fed978ae](https://linux-hardware.org/?probe=04fed978ae) | Oct 18, 2022 |
| HP            | ZBook 14u G5                | [151433ee2e](https://linux-hardware.org/?probe=151433ee2e) | Oct 18, 2022 |
| MOTILE        | M141                        | [c9ca7c65f0](https://linux-hardware.org/?probe=c9ca7c65f0) | Oct 18, 2022 |
| HP            | EliteBook Folio 9470m       | [c1e67135ac](https://linux-hardware.org/?probe=c1e67135ac) | Oct 18, 2022 |
| Acer          | Aspire E5-573               | [baf225a894](https://linux-hardware.org/?probe=baf225a894) | Oct 17, 2022 |
| Monster       | TULPAR T5 V21.6             | [eaeb6f6610](https://linux-hardware.org/?probe=eaeb6f6610) | Oct 17, 2022 |
| HUAWEI        | BOM-WXX9                    | [594b141136](https://linux-hardware.org/?probe=594b141136) | Oct 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a4ebad3748](https://linux-hardware.org/?probe=a4ebad3748) | Oct 17, 2022 |
| Acer          | Aspire 6930                 | [7ef117fa52](https://linux-hardware.org/?probe=7ef117fa52) | Oct 17, 2022 |
| Apple         | MacBook5,1                  | [84200c663d](https://linux-hardware.org/?probe=84200c663d) | Oct 17, 2022 |
| Toshiba       | Satellite U920t             | [75918848c4](https://linux-hardware.org/?probe=75918848c4) | Oct 17, 2022 |
| Toshiba       | Satellite U920t             | [9eb5519133](https://linux-hardware.org/?probe=9eb5519133) | Oct 17, 2022 |
| Multilaser    | PC024                       | [892f53a067](https://linux-hardware.org/?probe=892f53a067) | Oct 17, 2022 |
| ASUSTek       | X553MA                      | [71cfc713af](https://linux-hardware.org/?probe=71cfc713af) | Oct 17, 2022 |
| ASUSTek       | M70Vn                       | [e9301bdee2](https://linux-hardware.org/?probe=e9301bdee2) | Oct 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [62fd5f4526](https://linux-hardware.org/?probe=62fd5f4526) | Oct 16, 2022 |
| Dell          | Latitude 3500               | [d578b45420](https://linux-hardware.org/?probe=d578b45420) | Oct 16, 2022 |
| HP            | 245 G7 Notebook PC          | [c164c2ab59](https://linux-hardware.org/?probe=c164c2ab59) | Oct 16, 2022 |
| HP            | Notebook                    | [f88b853298](https://linux-hardware.org/?probe=f88b853298) | Oct 16, 2022 |
| Acer          | Aspire 5742G                | [79a5162024](https://linux-hardware.org/?probe=79a5162024) | Oct 16, 2022 |
| Thomson       | NEO14A-4WH128               | [daa7836c39](https://linux-hardware.org/?probe=daa7836c39) | Oct 16, 2022 |
| Dell          | Latitude E7450              | [500311a1b8](https://linux-hardware.org/?probe=500311a1b8) | Oct 16, 2022 |
| Acer          | Aspire V3-571               | [8457aa21e7](https://linux-hardware.org/?probe=8457aa21e7) | Oct 16, 2022 |
| HP            | Laptop 17-bs0xx             | [090cc3b6c5](https://linux-hardware.org/?probe=090cc3b6c5) | Oct 16, 2022 |
| Dell          | Inspiron 3505               | [ea75db9cc9](https://linux-hardware.org/?probe=ea75db9cc9) | Oct 16, 2022 |
| HP            | ZBook 14u G5                | [c35a9f90e8](https://linux-hardware.org/?probe=c35a9f90e8) | Oct 15, 2022 |
| ASUSTek       | X751NV                      | [174ee8f3e7](https://linux-hardware.org/?probe=174ee8f3e7) | Oct 15, 2022 |
| Google        | Coral                       | [a1811601a0](https://linux-hardware.org/?probe=a1811601a0) | Oct 15, 2022 |
| Google        | Coral                       | [93a674ea2b](https://linux-hardware.org/?probe=93a674ea2b) | Oct 15, 2022 |
| HP            | Pavilion ZV6100 (EC356UA... | [a001b5a9f9](https://linux-hardware.org/?probe=a001b5a9f9) | Oct 15, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7d6c345f35](https://linux-hardware.org/?probe=7d6c345f35) | Oct 15, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [6a0a056c36](https://linux-hardware.org/?probe=6a0a056c36) | Oct 15, 2022 |
| Acer          | AOD270                      | [7fbd540e61](https://linux-hardware.org/?probe=7fbd540e61) | Oct 15, 2022 |
| Acer          | Aspire 7730ZG               | [4796b36078](https://linux-hardware.org/?probe=4796b36078) | Oct 15, 2022 |
| HP            | ENVY Notebook               | [ae760be223](https://linux-hardware.org/?probe=ae760be223) | Oct 15, 2022 |
| Compaq        | 420                         | [cc3fae2a79](https://linux-hardware.org/?probe=cc3fae2a79) | Oct 15, 2022 |
| HP            | ZBook Firefly 14 inch G8... | [b7a5ca0670](https://linux-hardware.org/?probe=b7a5ca0670) | Oct 15, 2022 |
| ASUSTek       | X541UV                      | [ba7c1c3d83](https://linux-hardware.org/?probe=ba7c1c3d83) | Oct 14, 2022 |
| Lenovo        | V15 G2 IJL 82QY             | [240811f34a](https://linux-hardware.org/?probe=240811f34a) | Oct 14, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [fefb833511](https://linux-hardware.org/?probe=fefb833511) | Oct 14, 2022 |
| Getac         | V110G3                      | [09cd83f0ec](https://linux-hardware.org/?probe=09cd83f0ec) | Oct 14, 2022 |
| Google        | Dragonair                   | [4cfbc6aeac](https://linux-hardware.org/?probe=4cfbc6aeac) | Oct 14, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [bc23ce28e0](https://linux-hardware.org/?probe=bc23ce28e0) | Oct 14, 2022 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [1ae4e8967a](https://linux-hardware.org/?probe=1ae4e8967a) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | X502CA                      | [1243c07d09](https://linux-hardware.org/?probe=1243c07d09) | Oct 13, 2022 |
| ASUSTek       | X502CA                      | [064718ff22](https://linux-hardware.org/?probe=064718ff22) | Oct 13, 2022 |
| HP            | EliteBook 840 G1            | [fe9dde997d](https://linux-hardware.org/?probe=fe9dde997d) | Oct 13, 2022 |
| ASUSTek       | X553MA                      | [256cb98ed8](https://linux-hardware.org/?probe=256cb98ed8) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [5eafc7c12c](https://linux-hardware.org/?probe=5eafc7c12c) | Oct 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Dell          | Latitude E5550              | [fc1fa79f81](https://linux-hardware.org/?probe=fc1fa79f81) | Oct 13, 2022 |
| Dell          | Inspiron 5759               | [2656af4553](https://linux-hardware.org/?probe=2656af4553) | Oct 13, 2022 |
| Dell          | Precision 3550              | [e4d97d0229](https://linux-hardware.org/?probe=e4d97d0229) | Oct 13, 2022 |
| Acer          | Aspire 5732Z                | [b75d98cfc2](https://linux-hardware.org/?probe=b75d98cfc2) | Oct 13, 2022 |
| Daten Tecn... | DT02-M4                     | [d800a06da5](https://linux-hardware.org/?probe=d800a06da5) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | [9d4c4f0c96](https://linux-hardware.org/?probe=9d4c4f0c96) | Oct 12, 2022 |
| HUAWEI        | HVY-WXX9                    | [a2ec61226c](https://linux-hardware.org/?probe=a2ec61226c) | Oct 12, 2022 |
| HP            | EliteBook 8570p             | [51954462c5](https://linux-hardware.org/?probe=51954462c5) | Oct 12, 2022 |
| Dell          | G3 3500                     | [831b4e147e](https://linux-hardware.org/?probe=831b4e147e) | Oct 12, 2022 |
| ASUSTek       | M70Vn                       | [62cb9744e6](https://linux-hardware.org/?probe=62cb9744e6) | Oct 12, 2022 |
| ASUSTek       | X751LD                      | [230969c119](https://linux-hardware.org/?probe=230969c119) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f7f3439df7](https://linux-hardware.org/?probe=f7f3439df7) | Oct 11, 2022 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [89ee3db150](https://linux-hardware.org/?probe=89ee3db150) | Oct 11, 2022 |
| Acer          | Aspire ES1-571              | [3e2cf72b67](https://linux-hardware.org/?probe=3e2cf72b67) | Oct 11, 2022 |
| Acer          | Aspire ES1-571              | [6c313eca4e](https://linux-hardware.org/?probe=6c313eca4e) | Oct 11, 2022 |
| HP            | Laptop 17-by4xxx            | [392c089837](https://linux-hardware.org/?probe=392c089837) | Oct 10, 2022 |
| Acer          | Aspire E1-572               | [4097531dec](https://linux-hardware.org/?probe=4097531dec) | Oct 10, 2022 |
| Dell          | Latitude E7240              | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [b8e434e4db](https://linux-hardware.org/?probe=b8e434e4db) | Oct 10, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [989fe39fa7](https://linux-hardware.org/?probe=989fe39fa7) | Oct 10, 2022 |
| Sony          | VGN-N21E_W                  | [464905b4f8](https://linux-hardware.org/?probe=464905b4f8) | Oct 10, 2022 |
| Letni         | Z156                        | [994c588906](https://linux-hardware.org/?probe=994c588906) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [98a14153ba](https://linux-hardware.org/?probe=98a14153ba) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [58eb34d574](https://linux-hardware.org/?probe=58eb34d574) | Oct 10, 2022 |
| HP            | Compaq 6710b (GB887EA#AC... | [9f2e301993](https://linux-hardware.org/?probe=9f2e301993) | Oct 10, 2022 |
| HP            | Compaq 6710b (GB887EA#AC... | [af662698b9](https://linux-hardware.org/?probe=af662698b9) | Oct 10, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [e860301211](https://linux-hardware.org/?probe=e860301211) | Oct 09, 2022 |
| HP            | Pavilion g6                 | [582de9d5d6](https://linux-hardware.org/?probe=582de9d5d6) | Oct 09, 2022 |
| HP            | Pavilion g6                 | [f1b7cbae01](https://linux-hardware.org/?probe=f1b7cbae01) | Oct 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [cd06846004](https://linux-hardware.org/?probe=cd06846004) | Oct 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [2f4281aaaf](https://linux-hardware.org/?probe=2f4281aaaf) | Oct 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Dell          | Vostro 1520                 | [2de097618b](https://linux-hardware.org/?probe=2de097618b) | Oct 09, 2022 |
| MSI           | MS-7A34                     | [9f2f5898d2](https://linux-hardware.org/?probe=9f2f5898d2) | Oct 09, 2022 |
| MSI           | MS-7A34                     | [2b1c4c2738](https://linux-hardware.org/?probe=2b1c4c2738) | Oct 09, 2022 |
| Acer          | Aspire V5-471               | [46e5edbd41](https://linux-hardware.org/?probe=46e5edbd41) | Oct 08, 2022 |
| Fujitsu Si... | AMILO Pa 1538               | [11d843f241](https://linux-hardware.org/?probe=11d843f241) | Oct 08, 2022 |
| Sony          | VGN-AR71J                   | [57348f6a71](https://linux-hardware.org/?probe=57348f6a71) | Oct 08, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [ff4f9614fd](https://linux-hardware.org/?probe=ff4f9614fd) | Oct 08, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [acd8e18972](https://linux-hardware.org/?probe=acd8e18972) | Oct 08, 2022 |
| Dell          | Inspiron 3583               | [35b77097e9](https://linux-hardware.org/?probe=35b77097e9) | Oct 08, 2022 |
| Lenovo        | ThinkPad X200 7458EB2       | [70673f67bd](https://linux-hardware.org/?probe=70673f67bd) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [1b720b4302](https://linux-hardware.org/?probe=1b720b4302) | Oct 08, 2022 |
| Toshiba       | Satellite P200              | [55e4a786bd](https://linux-hardware.org/?probe=55e4a786bd) | Oct 08, 2022 |
| Apple         | MacBookAir6,2               | [9f434d86be](https://linux-hardware.org/?probe=9f434d86be) | Oct 08, 2022 |
| Dell          | Venue 11 Pro 5130           | [776d52e413](https://linux-hardware.org/?probe=776d52e413) | Oct 08, 2022 |
| Dell          | Inspiron 3520               | [5cf6d495ff](https://linux-hardware.org/?probe=5cf6d495ff) | Oct 08, 2022 |
| Lenovo        | IdeaPad Z500 5931           | [76791672ad](https://linux-hardware.org/?probe=76791672ad) | Oct 08, 2022 |
| Dell          | Inspiron 3537               | [39b5d635aa](https://linux-hardware.org/?probe=39b5d635aa) | Oct 08, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [b3b9f964b7](https://linux-hardware.org/?probe=b3b9f964b7) | Oct 08, 2022 |
| Standard      | MB40II                      | [97b446abda](https://linux-hardware.org/?probe=97b446abda) | Oct 08, 2022 |
| Unknown       | Unknown                     | [b941499384](https://linux-hardware.org/?probe=b941499384) | Oct 08, 2022 |
| Quanta        | TWS                         | [f7ba149979](https://linux-hardware.org/?probe=f7ba149979) | Oct 08, 2022 |
| Samsung       | RC530/RC730                 | [ee62bfc634](https://linux-hardware.org/?probe=ee62bfc634) | Oct 07, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [dc99eb14fb](https://linux-hardware.org/?probe=dc99eb14fb) | Oct 07, 2022 |
| Timi          | RedmiBook Pro 15S           | [108ff1fbdd](https://linux-hardware.org/?probe=108ff1fbdd) | Oct 07, 2022 |
| Apple         | MacBookPro9,2               | [acc90115ba](https://linux-hardware.org/?probe=acc90115ba) | Oct 06, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [2bcb266a0a](https://linux-hardware.org/?probe=2bcb266a0a) | Oct 06, 2022 |
| Fujitsu       | LIFEBOOK E752               | [b7c6acd46c](https://linux-hardware.org/?probe=b7c6acd46c) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19c7d98b00](https://linux-hardware.org/?probe=19c7d98b00) | Oct 06, 2022 |
| ASUSTek       | X580VD                      | [16d2a296c8](https://linux-hardware.org/?probe=16d2a296c8) | Oct 06, 2022 |
| Positivo      | W940SU2                     | [d403edabc4](https://linux-hardware.org/?probe=d403edabc4) | Oct 06, 2022 |
| HP            | ProBook 650 G2              | [9a79250780](https://linux-hardware.org/?probe=9a79250780) | Oct 06, 2022 |
| Sony          | SVF15A13SAB                 | [7c39add556](https://linux-hardware.org/?probe=7c39add556) | Oct 06, 2022 |
| HONOR         | BOD-WXX9                    | [26c4b5f06a](https://linux-hardware.org/?probe=26c4b5f06a) | Oct 06, 2022 |
| ASUSTek       | 1001PXD                     | [524e4ab046](https://linux-hardware.org/?probe=524e4ab046) | Oct 06, 2022 |
| ASUSTek       | X55U                        | [88b9f9be12](https://linux-hardware.org/?probe=88b9f9be12) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| HP            | EliteBook 8470p             | [4ba28bc3a8](https://linux-hardware.org/?probe=4ba28bc3a8) | Oct 05, 2022 |
| HP            | ProBook 450 G3              | [16b58b369a](https://linux-hardware.org/?probe=16b58b369a) | Oct 05, 2022 |
| Apple         | MacBookPro9,2               | [62e168299d](https://linux-hardware.org/?probe=62e168299d) | Oct 05, 2022 |
| Microtech     | EBL14                       | [8420051a94](https://linux-hardware.org/?probe=8420051a94) | Oct 05, 2022 |
| Dell          | Inspiron 3558               | [6f34c34ca6](https://linux-hardware.org/?probe=6f34c34ca6) | Oct 05, 2022 |
| Dell          | Inspiron 3558               | [0c5818ef54](https://linux-hardware.org/?probe=0c5818ef54) | Oct 05, 2022 |
| Acer          | Aspire S3                   | [ab3226a7fe](https://linux-hardware.org/?probe=ab3226a7fe) | Oct 05, 2022 |
| HP            | ZBook 17 G4                 | [d97c3b286d](https://linux-hardware.org/?probe=d97c3b286d) | Oct 04, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [d059117188](https://linux-hardware.org/?probe=d059117188) | Oct 04, 2022 |
| HP            | Notebook                    | [58dd536d7d](https://linux-hardware.org/?probe=58dd536d7d) | Oct 04, 2022 |
| Lenovo        | ThinkPad T520 424329U       | [3e16bd83b6](https://linux-hardware.org/?probe=3e16bd83b6) | Oct 04, 2022 |
| HP            | ProBook 4530s               | [8be2220d0f](https://linux-hardware.org/?probe=8be2220d0f) | Oct 04, 2022 |
| HP            | Laptop 17-by4xxx            | [e0a8530172](https://linux-hardware.org/?probe=e0a8530172) | Oct 04, 2022 |
| Dell          | Inspiron 1525               | [77f9a2e79a](https://linux-hardware.org/?probe=77f9a2e79a) | Oct 04, 2022 |
| Medion        | E7214                       | [c4ee9367cf](https://linux-hardware.org/?probe=c4ee9367cf) | Oct 04, 2022 |
| Medion        | E7214                       | [e8e78221ca](https://linux-hardware.org/?probe=e8e78221ca) | Oct 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [de59de7b14](https://linux-hardware.org/?probe=de59de7b14) | Oct 04, 2022 |
| Dell          | Latitude E6540              | [2deb597bbe](https://linux-hardware.org/?probe=2deb597bbe) | Oct 04, 2022 |
| Samsung       | R530/R730/R540              | [82629aeacd](https://linux-hardware.org/?probe=82629aeacd) | Oct 04, 2022 |
| Acer          | Aspire ES1-523              | [a80da55e0c](https://linux-hardware.org/?probe=a80da55e0c) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | [e4cc03e802](https://linux-hardware.org/?probe=e4cc03e802) | Oct 03, 2022 |
| Dell          | Inspiron N5040              | [8ccfb39433](https://linux-hardware.org/?probe=8ccfb39433) | Oct 03, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ee4c1a5f66](https://linux-hardware.org/?probe=ee4c1a5f66) | Oct 03, 2022 |
| Toshiba       | Satellite M50D-A            | [6eaada1ab0](https://linux-hardware.org/?probe=6eaada1ab0) | Oct 03, 2022 |
| Dell          | Latitude E5540              | [9804fbe4c4](https://linux-hardware.org/?probe=9804fbe4c4) | Oct 03, 2022 |
| HP            | EliteBook 840 G1            | [5bcba21765](https://linux-hardware.org/?probe=5bcba21765) | Oct 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f8224dfb59](https://linux-hardware.org/?probe=f8224dfb59) | Oct 03, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [bd8ce563ff](https://linux-hardware.org/?probe=bd8ce563ff) | Oct 03, 2022 |
| HP            | ENVY 15                     | [950623d8b2](https://linux-hardware.org/?probe=950623d8b2) | Oct 02, 2022 |
| HP            | OMEN by Laptop              | [971859f63e](https://linux-hardware.org/?probe=971859f63e) | Oct 02, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [23475045f2](https://linux-hardware.org/?probe=23475045f2) | Oct 02, 2022 |
| ASUSTek       | G752VS                      | [49ca9b71c8](https://linux-hardware.org/?probe=49ca9b71c8) | Oct 02, 2022 |
| ASUSTek       | K55VJ                       | [e405dee0bd](https://linux-hardware.org/?probe=e405dee0bd) | Oct 02, 2022 |
| Dell          | Inspiron 15 7510            | [521636075a](https://linux-hardware.org/?probe=521636075a) | Oct 02, 2022 |
| Samsung       | 275E4E/275E5E               | [ba82d9366c](https://linux-hardware.org/?probe=ba82d9366c) | Oct 02, 2022 |
| ASUSTek       | K54LY                       | [7c19c1f557](https://linux-hardware.org/?probe=7c19c1f557) | Oct 02, 2022 |
| HP            | EliteBook 840 G1            | [3f70868547](https://linux-hardware.org/?probe=3f70868547) | Oct 02, 2022 |
| Positivo      | Mobile                      | [640bc1a962](https://linux-hardware.org/?probe=640bc1a962) | Oct 01, 2022 |
| ASUSTek       | K54LY                       | [98197c818f](https://linux-hardware.org/?probe=98197c818f) | Oct 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [462f9bbdbe](https://linux-hardware.org/?probe=462f9bbdbe) | Oct 01, 2022 |
| Toshiba       | Satellite L55-B             | [f3680300d7](https://linux-hardware.org/?probe=f3680300d7) | Oct 01, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [73c4e6626f](https://linux-hardware.org/?probe=73c4e6626f) | Oct 01, 2022 |
| Lenovo        | ThinkPad T440 20B6005JUS    | [f12950ed92](https://linux-hardware.org/?probe=f12950ed92) | Oct 01, 2022 |
| Lenovo        | ThinkPad T440 20B6005JUS    | [b395d9ce9b](https://linux-hardware.org/?probe=b395d9ce9b) | Oct 01, 2022 |
| Dell          | G3 3500                     | [245ebaabe5](https://linux-hardware.org/?probe=245ebaabe5) | Oct 01, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [5c5353c8b6](https://linux-hardware.org/?probe=5c5353c8b6) | Oct 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [b62ddbdab0](https://linux-hardware.org/?probe=b62ddbdab0) | Oct 01, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [dffb22efdc](https://linux-hardware.org/?probe=dffb22efdc) | Oct 01, 2022 |
| Timi          | TM1709                      | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| HP            | ZBook 17 G4                 | [1476da42c3](https://linux-hardware.org/?probe=1476da42c3) | Sep 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [92f9efe077](https://linux-hardware.org/?probe=92f9efe077) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | [130c0489f9](https://linux-hardware.org/?probe=130c0489f9) | Sep 30, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [73e2559339](https://linux-hardware.org/?probe=73e2559339) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e829c9c0c6](https://linux-hardware.org/?probe=e829c9c0c6) | Sep 30, 2022 |
| Acer          | Aspire A715-74G             | [17abc08754](https://linux-hardware.org/?probe=17abc08754) | Sep 30, 2022 |
| Acer          | Aspire A315-56              | [1ee3922873](https://linux-hardware.org/?probe=1ee3922873) | Sep 30, 2022 |
| Positivo      | Mobile                      | [dcf8b09bec](https://linux-hardware.org/?probe=dcf8b09bec) | Sep 30, 2022 |
| Positivo      | Mobile                      | [6d2584bcb8](https://linux-hardware.org/?probe=6d2584bcb8) | Sep 30, 2022 |
| Dell          | Inspiron 3505               | [097825430f](https://linux-hardware.org/?probe=097825430f) | Sep 30, 2022 |
| Dell          | Inspiron 15-3567            | [5f1d0e6142](https://linux-hardware.org/?probe=5f1d0e6142) | Sep 30, 2022 |
| Dell          | Inspiron 15-3567            | [70a80b4201](https://linux-hardware.org/?probe=70a80b4201) | Sep 30, 2022 |
| Toshiba       | Satellite S70-A             | [7c6b3e14ce](https://linux-hardware.org/?probe=7c6b3e14ce) | Sep 30, 2022 |
| Toshiba       | Satellite L670              | [3b3e7965a5](https://linux-hardware.org/?probe=3b3e7965a5) | Sep 29, 2022 |
| GHIA          | LFI3H                       | [4233e4e6c5](https://linux-hardware.org/?probe=4233e4e6c5) | Sep 29, 2022 |
| GHIA          | LFI3H                       | [482e78460a](https://linux-hardware.org/?probe=482e78460a) | Sep 29, 2022 |
| AMI           | Cherry Trail CR             | [58caf99a77](https://linux-hardware.org/?probe=58caf99a77) | Sep 29, 2022 |
| HP            | EliteBook 6930p             | [56e5d25094](https://linux-hardware.org/?probe=56e5d25094) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | [8f42666f03](https://linux-hardware.org/?probe=8f42666f03) | Sep 29, 2022 |
| Dell          | Latitude E6330              | [b075fbcb56](https://linux-hardware.org/?probe=b075fbcb56) | Sep 29, 2022 |
| Dell          | Inspiron 1564               | [d9dd05aa12](https://linux-hardware.org/?probe=d9dd05aa12) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| Dell          | Latitude E6430              | [f3e5e0005d](https://linux-hardware.org/?probe=f3e5e0005d) | Sep 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [96c4c8ba02](https://linux-hardware.org/?probe=96c4c8ba02) | Sep 28, 2022 |
| Chuwi         | GemiBook Pro                | [fb12905329](https://linux-hardware.org/?probe=fb12905329) | Sep 28, 2022 |
| LG Electro... | C400-G.BC22P1               | [a325f5eb86](https://linux-hardware.org/?probe=a325f5eb86) | Sep 28, 2022 |
| Samsung       | 750XED                      | [dcb54d69f8](https://linux-hardware.org/?probe=dcb54d69f8) | Sep 27, 2022 |
| Toshiba       | QOSMIO X70-B                | [04589a6a6c](https://linux-hardware.org/?probe=04589a6a6c) | Sep 27, 2022 |
| Dell          | Latitude E6540              | [27c854b1a0](https://linux-hardware.org/?probe=27c854b1a0) | Sep 27, 2022 |
| Lenovo        | G780                        | [057a86bcdc](https://linux-hardware.org/?probe=057a86bcdc) | Sep 27, 2022 |
| Toshiba       | Satellite C50-B             | [3cea1ede58](https://linux-hardware.org/?probe=3cea1ede58) | Sep 27, 2022 |
| Dell          | XPS 17 9700                 | [cd6dcf0de8](https://linux-hardware.org/?probe=cd6dcf0de8) | Sep 27, 2022 |
| Standard      | AHV                         | [a80b2d344d](https://linux-hardware.org/?probe=a80b2d344d) | Sep 27, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [6f4452adc5](https://linux-hardware.org/?probe=6f4452adc5) | Sep 27, 2022 |
| ASUSTek       | K53SV                       | [d2801f9560](https://linux-hardware.org/?probe=d2801f9560) | Sep 26, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [3c0a494baa](https://linux-hardware.org/?probe=3c0a494baa) | Sep 26, 2022 |
| Fujitsu       | LIFEBOOK A544               | [6e4694775c](https://linux-hardware.org/?probe=6e4694775c) | Sep 26, 2022 |
| HP            | Laptop 17-cp0xxx            | [fa6a915235](https://linux-hardware.org/?probe=fa6a915235) | Sep 26, 2022 |
| HP            | G42                         | [39a4836398](https://linux-hardware.org/?probe=39a4836398) | Sep 26, 2022 |
| MSI           | GE75 Raider 8SF             | [094a9b115b](https://linux-hardware.org/?probe=094a9b115b) | Sep 26, 2022 |
| HP            | Pavilion g7                 | [19b206ba2f](https://linux-hardware.org/?probe=19b206ba2f) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [7be473c3c6](https://linux-hardware.org/?probe=7be473c3c6) | Sep 25, 2022 |
| Timi          | RedmiBook 16                | [0a65bab615](https://linux-hardware.org/?probe=0a65bab615) | Sep 25, 2022 |
| Lenovo        | ThinkPad X250 20CL001DMS    | [7662278b86](https://linux-hardware.org/?probe=7662278b86) | Sep 25, 2022 |
| HUAWEI        | KLVL-WXXW                   | [6828f26ab2](https://linux-hardware.org/?probe=6828f26ab2) | Sep 25, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [0e69d41fef](https://linux-hardware.org/?probe=0e69d41fef) | Sep 25, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [2854d30785](https://linux-hardware.org/?probe=2854d30785) | Sep 25, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [939bba43d1](https://linux-hardware.org/?probe=939bba43d1) | Sep 25, 2022 |
| Dell          | Inspiron 3442               | [7fb024bb5d](https://linux-hardware.org/?probe=7fb024bb5d) | Sep 25, 2022 |
| HP            | 255 G5                      | [2a8f595510](https://linux-hardware.org/?probe=2a8f595510) | Sep 24, 2022 |
| Dell          | Inspiron 3442               | [1190ad2886](https://linux-hardware.org/?probe=1190ad2886) | Sep 24, 2022 |
| Dell          | Inspiron 1440               | [c928a944c0](https://linux-hardware.org/?probe=c928a944c0) | Sep 24, 2022 |
| ASUSTek       | X55U                        | [863a5df6ad](https://linux-hardware.org/?probe=863a5df6ad) | Sep 24, 2022 |
| Lenovo        | ThinkPad T430 23476Y7       | [8488ad9e53](https://linux-hardware.org/?probe=8488ad9e53) | Sep 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [b7a5cfcf9c](https://linux-hardware.org/?probe=b7a5cfcf9c) | Sep 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [dc165f65b5](https://linux-hardware.org/?probe=dc165f65b5) | Sep 24, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [977d73b98a](https://linux-hardware.org/?probe=977d73b98a) | Sep 24, 2022 |
| Dell          | Latitude E5510              | [04f4e9a803](https://linux-hardware.org/?probe=04f4e9a803) | Sep 24, 2022 |
| Dell          | Latitude E5570              | [df18be69a3](https://linux-hardware.org/?probe=df18be69a3) | Sep 24, 2022 |
| HP            | Laptop 17-bs0xx             | [33398b1a21](https://linux-hardware.org/?probe=33398b1a21) | Sep 23, 2022 |
| Lenovo        | Y50-70 Touch 20349          | [f038a5908f](https://linux-hardware.org/?probe=f038a5908f) | Sep 23, 2022 |
| Toshiba       | ENCORE 2 WT8-B              | [b9cd7b49d3](https://linux-hardware.org/?probe=b9cd7b49d3) | Sep 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [e8e1108a58](https://linux-hardware.org/?probe=e8e1108a58) | Sep 23, 2022 |
| Dell          | Precision 7710              | [c48bccbee4](https://linux-hardware.org/?probe=c48bccbee4) | Sep 23, 2022 |
| Acer          | TravelMate P256-MG          | [0a7c58d00a](https://linux-hardware.org/?probe=0a7c58d00a) | Sep 23, 2022 |
| Acer          | Aspire 5532                 | [b427a13b9b](https://linux-hardware.org/?probe=b427a13b9b) | Sep 22, 2022 |
| Dell          | Inspiron 1721               | [ab0eb7f4ce](https://linux-hardware.org/?probe=ab0eb7f4ce) | Sep 22, 2022 |
| Fujitsu       | LIFEBOOK A544               | [648fb5c63e](https://linux-hardware.org/?probe=648fb5c63e) | Sep 22, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [fc2ea7b0a0](https://linux-hardware.org/?probe=fc2ea7b0a0) | Sep 22, 2022 |
| ASUSTek       | G750JM                      | [2e53c11312](https://linux-hardware.org/?probe=2e53c11312) | Sep 22, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [2d8eefaf6a](https://linux-hardware.org/?probe=2d8eefaf6a) | Sep 22, 2022 |
| Dell          | Latitude E6320              | [452304d040](https://linux-hardware.org/?probe=452304d040) | Sep 22, 2022 |
| HP            | Pavilion dv4000 (PX306UA... | [372160583e](https://linux-hardware.org/?probe=372160583e) | Sep 22, 2022 |
| Sony          | VPCEB1Z1E                   | [37fea84df6](https://linux-hardware.org/?probe=37fea84df6) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [641ad27b06](https://linux-hardware.org/?probe=641ad27b06) | Sep 22, 2022 |
| Dell          | Latitude E6510              | [fa644f90c4](https://linux-hardware.org/?probe=fa644f90c4) | Sep 22, 2022 |
| Chuwi         | HeroBook Pro                | [76be3ff1db](https://linux-hardware.org/?probe=76be3ff1db) | Sep 22, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | [cae7b3dc49](https://linux-hardware.org/?probe=cae7b3dc49) | Sep 22, 2022 |
| Sony          | SVE15125CBW                 | [50b65906b1](https://linux-hardware.org/?probe=50b65906b1) | Sep 22, 2022 |
| MSI           | GT70 2OC/2OD                | [c6a0b0d987](https://linux-hardware.org/?probe=c6a0b0d987) | Sep 22, 2022 |
| Lenovo        | ThinkPad Edge E320 1298A... | [869b076838](https://linux-hardware.org/?probe=869b076838) | Sep 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [afd66066bc](https://linux-hardware.org/?probe=afd66066bc) | Sep 21, 2022 |
| Lenovo        | ThinkPad X230 23255Z6       | [25cc23e2ad](https://linux-hardware.org/?probe=25cc23e2ad) | Sep 21, 2022 |
| Lenovo        | ThinkPad T61 6468AE1        | [8719597c22](https://linux-hardware.org/?probe=8719597c22) | Sep 21, 2022 |
| Acer          | Aspire ES1-111M             | [04f08de672](https://linux-hardware.org/?probe=04f08de672) | Sep 21, 2022 |
| Apple         | MacBookPro8,1               | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [8e46e07b3a](https://linux-hardware.org/?probe=8e46e07b3a) | Sep 21, 2022 |
| Lenovo        | G40-80 80E4                 | [575b85b038](https://linux-hardware.org/?probe=575b85b038) | Sep 21, 2022 |
| Lenovo        | G40-80 80E4                 | [18a0a2158c](https://linux-hardware.org/?probe=18a0a2158c) | Sep 21, 2022 |
| Dell          | Latitude 3540               | [7e56d744b7](https://linux-hardware.org/?probe=7e56d744b7) | Sep 21, 2022 |
| Dell          | Latitude 3540               | [0216f52b36](https://linux-hardware.org/?probe=0216f52b36) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [910b604abc](https://linux-hardware.org/?probe=910b604abc) | Sep 21, 2022 |
| Dell          | Latitude E6540              | [08bd609dbe](https://linux-hardware.org/?probe=08bd609dbe) | Sep 20, 2022 |
| LG Electro... | C400-G.BC22P1               | [b5aad7f903](https://linux-hardware.org/?probe=b5aad7f903) | Sep 20, 2022 |
| Dell          | Latitude E7240              | [6db3839532](https://linux-hardware.org/?probe=6db3839532) | Sep 20, 2022 |
| Dell          | Latitude E7240              | [21dc4700da](https://linux-hardware.org/?probe=21dc4700da) | Sep 20, 2022 |
| Framework     | Laptop                      | [dd163cfa96](https://linux-hardware.org/?probe=dd163cfa96) | Sep 20, 2022 |
| Toshiba       | Satellite L875-11M          | [42f3498e9e](https://linux-hardware.org/?probe=42f3498e9e) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61 6468AE1        | [028ead1680](https://linux-hardware.org/?probe=028ead1680) | Sep 20, 2022 |
| Dell          | Latitude E6420              | [e46ce42e90](https://linux-hardware.org/?probe=e46ce42e90) | Sep 20, 2022 |
| Dell          | Latitude E4310              | [06dc3db422](https://linux-hardware.org/?probe=06dc3db422) | Sep 20, 2022 |
| Acer          | Aspire E5-532               | [1d0f80e0f1](https://linux-hardware.org/?probe=1d0f80e0f1) | Sep 20, 2022 |
| Acer          | Aspire E5-532               | [f349ec9700](https://linux-hardware.org/?probe=f349ec9700) | Sep 20, 2022 |
| Lenovo        | B570e 476025G               | [ab67a90ba7](https://linux-hardware.org/?probe=ab67a90ba7) | Sep 20, 2022 |
| HUAWEI        | BOM-WXX9                    | [f2906f8b8d](https://linux-hardware.org/?probe=f2906f8b8d) | Sep 19, 2022 |
| LG Electro... | C400-G.BC31P1               | [66c8977810](https://linux-hardware.org/?probe=66c8977810) | Sep 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [85952e171d](https://linux-hardware.org/?probe=85952e171d) | Sep 19, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [66596e407c](https://linux-hardware.org/?probe=66596e407c) | Sep 19, 2022 |
| Chuwi         | HeroBook Pro                | [3759658825](https://linux-hardware.org/?probe=3759658825) | Sep 19, 2022 |
| HP            | Pavilion dv6                | [9c52e7d0f0](https://linux-hardware.org/?probe=9c52e7d0f0) | Sep 19, 2022 |
| Samsung       | R530/R730/R540              | [3062da6263](https://linux-hardware.org/?probe=3062da6263) | Sep 19, 2022 |
| Acer          | Aspire A515-51G             | [3f987553d9](https://linux-hardware.org/?probe=3f987553d9) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [b707354c65](https://linux-hardware.org/?probe=b707354c65) | Sep 18, 2022 |
| Samsung       | Lumpy                       | [9c1fd4f253](https://linux-hardware.org/?probe=9c1fd4f253) | Sep 18, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [2e1e251503](https://linux-hardware.org/?probe=2e1e251503) | Sep 18, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | [5f56e8b10f](https://linux-hardware.org/?probe=5f56e8b10f) | Sep 18, 2022 |
| Lenovo        | G780                        | [eb3df9a17e](https://linux-hardware.org/?probe=eb3df9a17e) | Sep 18, 2022 |
| Lenovo        | ThinkPad X200 7458VL3       | [700ff6630e](https://linux-hardware.org/?probe=700ff6630e) | Sep 18, 2022 |
| Samsung       | R430/P430                   | [50cf13ed55](https://linux-hardware.org/?probe=50cf13ed55) | Sep 18, 2022 |
| HP            | 2000                        | [0020624077](https://linux-hardware.org/?probe=0020624077) | Sep 18, 2022 |
| Lenovo        | ThinkPad T580 20L9001YRT    | [7ac55602e6](https://linux-hardware.org/?probe=7ac55602e6) | Sep 18, 2022 |
| Lenovo        | ThinkPad E480 20KQS00000    | [c3c44800e7](https://linux-hardware.org/?probe=c3c44800e7) | Sep 18, 2022 |
| Dell          | Latitude E5420              | [7416dc3fb1](https://linux-hardware.org/?probe=7416dc3fb1) | Sep 18, 2022 |
| Acer          | Swift SF314-57              | [8c905d820d](https://linux-hardware.org/?probe=8c905d820d) | Sep 17, 2022 |
| Lenovo        | G780                        | [04f924450d](https://linux-hardware.org/?probe=04f924450d) | Sep 17, 2022 |
| Medion        | Akoya S6213T                | [6fb8ca6c1b](https://linux-hardware.org/?probe=6fb8ca6c1b) | Sep 17, 2022 |
| Dell          | XPS 13 9360                 | [af2f12093c](https://linux-hardware.org/?probe=af2f12093c) | Sep 17, 2022 |
| Dell          | Inspiron 15-3567            | [7ef8a544c4](https://linux-hardware.org/?probe=7ef8a544c4) | Sep 17, 2022 |
| MSI           | Katana GF66 12UD            | [fde2d03f98](https://linux-hardware.org/?probe=fde2d03f98) | Sep 17, 2022 |
| Dell          | Latitude E5400              | [9859a54bc4](https://linux-hardware.org/?probe=9859a54bc4) | Sep 17, 2022 |
| Lenovo        | ThinkPad X230 2325CZ1       | [b484febc13](https://linux-hardware.org/?probe=b484febc13) | Sep 17, 2022 |
| HP            | Laptop 15-da0xxx            | [6341f27d68](https://linux-hardware.org/?probe=6341f27d68) | Sep 16, 2022 |
| Dell          | Inspiron 1545               | [cc3af3e194](https://linux-hardware.org/?probe=cc3af3e194) | Sep 16, 2022 |
| Dell          | Inspiron 1545               | [598341495c](https://linux-hardware.org/?probe=598341495c) | Sep 16, 2022 |
| Alienware     | M17xR4                      | [210bd15049](https://linux-hardware.org/?probe=210bd15049) | Sep 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [7a390e81b1](https://linux-hardware.org/?probe=7a390e81b1) | Sep 16, 2022 |
| HP            | Compaq 6720s                | [75bc6df1df](https://linux-hardware.org/?probe=75bc6df1df) | Sep 16, 2022 |
| Dell          | Precision 7520              | [5deca1e73b](https://linux-hardware.org/?probe=5deca1e73b) | Sep 16, 2022 |
| Lenovo        | Z50-70 20354                | [fafabb8c1f](https://linux-hardware.org/?probe=fafabb8c1f) | Sep 16, 2022 |
| Dell          | Inspiron 15-3552            | [583d7c550e](https://linux-hardware.org/?probe=583d7c550e) | Sep 16, 2022 |
| Dell          | Inspiron 15-3567            | [3ea454c43f](https://linux-hardware.org/?probe=3ea454c43f) | Sep 16, 2022 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [4bc5802227](https://linux-hardware.org/?probe=4bc5802227) | Sep 16, 2022 |
| Dell          | Latitude 5410               | [f476f4e380](https://linux-hardware.org/?probe=f476f4e380) | Sep 16, 2022 |
| HP            | ProBook 4530s               | [821a6eda47](https://linux-hardware.org/?probe=821a6eda47) | Sep 16, 2022 |
| Lenovo        | IdeaPad 110S-11IBR          | [32e42e0b52](https://linux-hardware.org/?probe=32e42e0b52) | Sep 15, 2022 |
| Samsung       | Lumpy                       | [1ea9c40a42](https://linux-hardware.org/?probe=1ea9c40a42) | Sep 15, 2022 |
| ASUSTek       | X555LD                      | [12d6e02796](https://linux-hardware.org/?probe=12d6e02796) | Sep 15, 2022 |
| HP            | 2000                        | [17e86a7d4b](https://linux-hardware.org/?probe=17e86a7d4b) | Sep 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [e965de4ced](https://linux-hardware.org/?probe=e965de4ced) | Sep 15, 2022 |
| Panasonic     | CF-53JWX1CFG                | [f4e1cd21d9](https://linux-hardware.org/?probe=f4e1cd21d9) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [38fa0eaf03](https://linux-hardware.org/?probe=38fa0eaf03) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [72c53fd3c8](https://linux-hardware.org/?probe=72c53fd3c8) | Sep 15, 2022 |
| HP            | ProBook 455 15.6 inch G9... | [027a02cfc2](https://linux-hardware.org/?probe=027a02cfc2) | Sep 15, 2022 |
| Acer          | Aspire E5-571G              | [0a02b8ef94](https://linux-hardware.org/?probe=0a02b8ef94) | Sep 15, 2022 |
| Lenovo        | Slim 7 14IAP7 82SX          | [9dc2707813](https://linux-hardware.org/?probe=9dc2707813) | Sep 15, 2022 |
| HP            | 240 G7 Notebook PC          | [09f7be676c](https://linux-hardware.org/?probe=09f7be676c) | Sep 15, 2022 |
| Acer          | Aspire 6530                 | [9b356c761d](https://linux-hardware.org/?probe=9b356c761d) | Sep 14, 2022 |
| Lenovo        | ThinkPad T510 4349BR8       | [d60b0c8539](https://linux-hardware.org/?probe=d60b0c8539) | Sep 14, 2022 |
| HP            | Laptop 15-da0xxx            | [82140783de](https://linux-hardware.org/?probe=82140783de) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [54ea6ab133](https://linux-hardware.org/?probe=54ea6ab133) | Sep 14, 2022 |
| HP            | Unknown                     | [692825c1eb](https://linux-hardware.org/?probe=692825c1eb) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [8d189da7a7](https://linux-hardware.org/?probe=8d189da7a7) | Sep 14, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [277daa8d6d](https://linux-hardware.org/?probe=277daa8d6d) | Sep 14, 2022 |
| Dell          | Inspiron 15-3567            | [5006dca507](https://linux-hardware.org/?probe=5006dca507) | Sep 14, 2022 |
| Dell          | Inspiron 3558               | [51e0624bf7](https://linux-hardware.org/?probe=51e0624bf7) | Sep 13, 2022 |
| Acer          | Aspire 5742G                | [051893f147](https://linux-hardware.org/?probe=051893f147) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fa652e45e1](https://linux-hardware.org/?probe=fa652e45e1) | Sep 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P5440FA_... | [d441c68f40](https://linux-hardware.org/?probe=d441c68f40) | Sep 13, 2022 |
| Dell          | Latitude 5480               | [59bcf57d5b](https://linux-hardware.org/?probe=59bcf57d5b) | Sep 13, 2022 |
| Apple         | MacBookPro5,3               | [3e00c86066](https://linux-hardware.org/?probe=3e00c86066) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9d57c27e](https://linux-hardware.org/?probe=aa9d57c27e) | Sep 13, 2022 |
| Apple         | MacBookPro5,3               | [9211f5de76](https://linux-hardware.org/?probe=9211f5de76) | Sep 13, 2022 |
| Lenovo        | G50-70 20351                | [4105fc929e](https://linux-hardware.org/?probe=4105fc929e) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| HUAWEI        | HBB-WX9                     | [30b6cc18c5](https://linux-hardware.org/?probe=30b6cc18c5) | Sep 13, 2022 |
| ASUSTek       | X550CC                      | [cb36241a3b](https://linux-hardware.org/?probe=cb36241a3b) | Sep 13, 2022 |
| Acer          | Aspire 5349                 | [39f83f7692](https://linux-hardware.org/?probe=39f83f7692) | Sep 13, 2022 |
| Dell          | Inspiron 13-7378            | [689047aef1](https://linux-hardware.org/?probe=689047aef1) | Sep 13, 2022 |
| Dell          | XPS 17 9700                 | [24eaecfdd8](https://linux-hardware.org/?probe=24eaecfdd8) | Sep 13, 2022 |
| Lenovo        | ThinkPad T540p 20BF002CM... | [3343da6005](https://linux-hardware.org/?probe=3343da6005) | Sep 12, 2022 |
| Toshiba       | Satellite L50D-B            | [2d09796251](https://linux-hardware.org/?probe=2d09796251) | Sep 12, 2022 |
| HP            | Laptop 17-cp0xxx            | [78068a1338](https://linux-hardware.org/?probe=78068a1338) | Sep 12, 2022 |
| Acer          | Aspire 6930G                | [cb054f2964](https://linux-hardware.org/?probe=cb054f2964) | Sep 12, 2022 |
| Samsung       | RV415/RV515                 | [bc83707f72](https://linux-hardware.org/?probe=bc83707f72) | Sep 12, 2022 |
| Dell          | Latitude E6540              | [e23aacd364](https://linux-hardware.org/?probe=e23aacd364) | Sep 12, 2022 |
| Samsung       | R530/R730/R540              | [9149fde5c5](https://linux-hardware.org/?probe=9149fde5c5) | Sep 12, 2022 |
| HP            | Laptop 17-cp0xxx            | [4005fc56a4](https://linux-hardware.org/?probe=4005fc56a4) | Sep 12, 2022 |
| Dell          | Inspiron 13-7378            | [4e7d1fc8a7](https://linux-hardware.org/?probe=4e7d1fc8a7) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [2fdf233a71](https://linux-hardware.org/?probe=2fdf233a71) | Sep 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [60d15f4f46](https://linux-hardware.org/?probe=60d15f4f46) | Sep 12, 2022 |
| Dell          | XPS 13 9350                 | [e137564f6b](https://linux-hardware.org/?probe=e137564f6b) | Sep 12, 2022 |
| Lenovo        | ThinkPad W540 20BG0016US    | [9f0543edc4](https://linux-hardware.org/?probe=9f0543edc4) | Sep 11, 2022 |
| Dell          | Latitude 3190               | [14d836c020](https://linux-hardware.org/?probe=14d836c020) | Sep 11, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [390223e073](https://linux-hardware.org/?probe=390223e073) | Sep 11, 2022 |
| Gigabyte      | AORUS 17 KE4                | [d22756fbc1](https://linux-hardware.org/?probe=d22756fbc1) | Sep 11, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6f309073f2](https://linux-hardware.org/?probe=6f309073f2) | Sep 11, 2022 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [8d76919c1a](https://linux-hardware.org/?probe=8d76919c1a) | Sep 11, 2022 |
| Acer          | Aspire 6530                 | [89af5e8adb](https://linux-hardware.org/?probe=89af5e8adb) | Sep 11, 2022 |
| Acer          | Aspire 6530                 | [1798b7751a](https://linux-hardware.org/?probe=1798b7751a) | Sep 11, 2022 |
| Lenovo        | ZHAOYANG E47                | [7f1fab5ff0](https://linux-hardware.org/?probe=7f1fab5ff0) | Sep 11, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [4ff88a6670](https://linux-hardware.org/?probe=4ff88a6670) | Sep 11, 2022 |
| Apple         | MacBookPro13,1              | [4b7f579852](https://linux-hardware.org/?probe=4b7f579852) | Sep 11, 2022 |
| Dell          | XPS 15 9500                 | [a400135c2f](https://linux-hardware.org/?probe=a400135c2f) | Sep 11, 2022 |
| Acer          | Aspire ES1-411              | [064b2bd5f2](https://linux-hardware.org/?probe=064b2bd5f2) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a7a06f548f](https://linux-hardware.org/?probe=a7a06f548f) | Sep 11, 2022 |
| HP            | EliteBook 840 G5            | [0f40490437](https://linux-hardware.org/?probe=0f40490437) | Sep 11, 2022 |
| UMAX          | VisionBook N15G Plus        | [d17fb4f8f9](https://linux-hardware.org/?probe=d17fb4f8f9) | Sep 11, 2022 |
| Packard Be... | EasyNote LE69KB             | [a008db4da9](https://linux-hardware.org/?probe=a008db4da9) | Sep 11, 2022 |
| GPU Compan... | GWTN141-10                  | [8380b841fd](https://linux-hardware.org/?probe=8380b841fd) | Sep 10, 2022 |
| MSI           | GF75 Thin 10SC              | [be99178497](https://linux-hardware.org/?probe=be99178497) | Sep 10, 2022 |
| ASUSTek       | K53E                        | [d39f35f5d9](https://linux-hardware.org/?probe=d39f35f5d9) | Sep 10, 2022 |
| Toshiba       | Satellite C55-A-1JL         | [906f27f221](https://linux-hardware.org/?probe=906f27f221) | Sep 10, 2022 |
| ASUSTek       | N61Vn                       | [788cf883c5](https://linux-hardware.org/?probe=788cf883c5) | Sep 10, 2022 |
| Dell          | Precision 3550              | [e29e0944e6](https://linux-hardware.org/?probe=e29e0944e6) | Sep 10, 2022 |
| HP            | ZBook 15 G5                 | [fe1d0da2fc](https://linux-hardware.org/?probe=fe1d0da2fc) | Sep 10, 2022 |
| Lenovo        | G50-70 20351                | [633c0eae94](https://linux-hardware.org/?probe=633c0eae94) | Sep 09, 2022 |
| Apple         | MacBookPro9,2               | [228136508c](https://linux-hardware.org/?probe=228136508c) | Sep 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [603514ef84](https://linux-hardware.org/?probe=603514ef84) | Sep 09, 2022 |
| Lenovo        | IdeaPad 110S-11IBR          | [b1c1a2e4e0](https://linux-hardware.org/?probe=b1c1a2e4e0) | Sep 09, 2022 |
| Dell          | Vostro 3550                 | [f04353bb0e](https://linux-hardware.org/?probe=f04353bb0e) | Sep 08, 2022 |
| Acer          | Aspire ES1-411              | [d3df9a2592](https://linux-hardware.org/?probe=d3df9a2592) | Sep 08, 2022 |
| Digibras      | US41II1                     | [890a4894cf](https://linux-hardware.org/?probe=890a4894cf) | Sep 08, 2022 |
| Toshiba       | Satellite C55-A-1JL         | [d229fa96f3](https://linux-hardware.org/?probe=d229fa96f3) | Sep 08, 2022 |
| Dell          | Latitude E6540              | [5700f37281](https://linux-hardware.org/?probe=5700f37281) | Sep 08, 2022 |
| Dell          | Latitude E7470              | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| Google        | Akemi                       | [459c9226ed](https://linux-hardware.org/?probe=459c9226ed) | Sep 07, 2022 |
| HP            | EliteBook 8440p             | [5cf26fac4d](https://linux-hardware.org/?probe=5cf26fac4d) | Sep 07, 2022 |
| Dell          | Inspiron 3593               | [fd6ab0c9e5](https://linux-hardware.org/?probe=fd6ab0c9e5) | Sep 07, 2022 |
| Dell          | Inspiron 5584               | [3691775658](https://linux-hardware.org/?probe=3691775658) | Sep 07, 2022 |
| Dell          | Studio 1747                 | [42ae5d9dbe](https://linux-hardware.org/?probe=42ae5d9dbe) | Sep 07, 2022 |
| Toshiba       | Satellite C660              | [e7ad5166eb](https://linux-hardware.org/?probe=e7ad5166eb) | Sep 07, 2022 |
| HP            | Pavilion Notebook           | [062f15a645](https://linux-hardware.org/?probe=062f15a645) | Sep 07, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [35ead5350d](https://linux-hardware.org/?probe=35ead5350d) | Sep 07, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | [104331cf4c](https://linux-hardware.org/?probe=104331cf4c) | Sep 07, 2022 |
| HP            | ProBook 430 G3              | [f1b171fc10](https://linux-hardware.org/?probe=f1b171fc10) | Sep 06, 2022 |
| Lenovo        | ThinkPad 11e 3rd Gen 20G... | [a3cd19321c](https://linux-hardware.org/?probe=a3cd19321c) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [aa4d4912e2](https://linux-hardware.org/?probe=aa4d4912e2) | Sep 06, 2022 |
| Samsung       | 755XDA                      | [58091d8a85](https://linux-hardware.org/?probe=58091d8a85) | Sep 06, 2022 |
| Dell          | Latitude E6520              | [8d45b1f987](https://linux-hardware.org/?probe=8d45b1f987) | Sep 06, 2022 |
| ASUSTek       | X550CC                      | [ef103b9abb](https://linux-hardware.org/?probe=ef103b9abb) | Sep 06, 2022 |
| ASUSTek       | P751JF                      | [6f3898fe12](https://linux-hardware.org/?probe=6f3898fe12) | Sep 06, 2022 |
| Acer          | Extensa 5230                | [a5546cc97c](https://linux-hardware.org/?probe=a5546cc97c) | Sep 06, 2022 |
| Samsung       | 755XDA                      | [a2013be10e](https://linux-hardware.org/?probe=a2013be10e) | Sep 06, 2022 |
| ASUSTek       | X550CC                      | [264006f609](https://linux-hardware.org/?probe=264006f609) | Sep 06, 2022 |
| Apple         | MacBookPro10,1              | [e9e7867de9](https://linux-hardware.org/?probe=e9e7867de9) | Sep 06, 2022 |
| Apple         | MacBookPro10,1              | [bbd84689a3](https://linux-hardware.org/?probe=bbd84689a3) | Sep 06, 2022 |
| Dell          | Inspiron 16 5620            | [5a1fe06c62](https://linux-hardware.org/?probe=5a1fe06c62) | Sep 06, 2022 |
| Acer          | Aspire 5920G                | [af0e5553e9](https://linux-hardware.org/?probe=af0e5553e9) | Sep 05, 2022 |
| Lenovo        | ThinkPad X230 23252UU       | [0853f0ca45](https://linux-hardware.org/?probe=0853f0ca45) | Sep 05, 2022 |
| Dell          | Latitude E6530              | [9e0c4566c5](https://linux-hardware.org/?probe=9e0c4566c5) | Sep 05, 2022 |
| Gateway       | NS30                        | [2ade42aacf](https://linux-hardware.org/?probe=2ade42aacf) | Sep 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b1edd48233](https://linux-hardware.org/?probe=b1edd48233) | Sep 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [999dde8580](https://linux-hardware.org/?probe=999dde8580) | Sep 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3aa5926982](https://linux-hardware.org/?probe=3aa5926982) | Sep 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34601... | [00e7f83f25](https://linux-hardware.org/?probe=00e7f83f25) | Sep 05, 2022 |
| Apple         | MacBookAir7,2               | [2efecd6c36](https://linux-hardware.org/?probe=2efecd6c36) | Sep 05, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [27d4905678](https://linux-hardware.org/?probe=27d4905678) | Sep 04, 2022 |
| Acer          | Aspire A515-45              | [89baeb107f](https://linux-hardware.org/?probe=89baeb107f) | Sep 04, 2022 |
| Google        | Akemi                       | [5f47a081e3](https://linux-hardware.org/?probe=5f47a081e3) | Sep 04, 2022 |
| Toshiba       | Satellite L50-B             | [1aedf1fdc1](https://linux-hardware.org/?probe=1aedf1fdc1) | Sep 04, 2022 |
| Lenovo        | G40-80 80JE                 | [c876beae17](https://linux-hardware.org/?probe=c876beae17) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [beec88b95c](https://linux-hardware.org/?probe=beec88b95c) | Sep 04, 2022 |
| Lenovo        | E31-80 80MX                 | [0eecb590e6](https://linux-hardware.org/?probe=0eecb590e6) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [35e98b0a2a](https://linux-hardware.org/?probe=35e98b0a2a) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [985872733c](https://linux-hardware.org/?probe=985872733c) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [e61768b292](https://linux-hardware.org/?probe=e61768b292) | Sep 04, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [874553b1fd](https://linux-hardware.org/?probe=874553b1fd) | Sep 04, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0a309ba168](https://linux-hardware.org/?probe=0a309ba168) | Sep 04, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0a4fea005a](https://linux-hardware.org/?probe=0a4fea005a) | Sep 04, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [0a729ebdd9](https://linux-hardware.org/?probe=0a729ebdd9) | Sep 04, 2022 |
| HP            | Presario CQ61               | [5ef0184c8e](https://linux-hardware.org/?probe=5ef0184c8e) | Sep 04, 2022 |
| Lenovo        | G40-80 80JE                 | [e6fa43e12e](https://linux-hardware.org/?probe=e6fa43e12e) | Sep 04, 2022 |
| Dell          | Latitude 7200 2-in-1        | [67de9b81be](https://linux-hardware.org/?probe=67de9b81be) | Sep 04, 2022 |
| Toshiba       | Satellite Pro C660          | [4e2e6fe4ea](https://linux-hardware.org/?probe=4e2e6fe4ea) | Sep 03, 2022 |
| ASUSTek       | K61IC                       | [d85b0c9b4f](https://linux-hardware.org/?probe=d85b0c9b4f) | Sep 03, 2022 |
| ASUSTek       | X551MA                      | [84339ff991](https://linux-hardware.org/?probe=84339ff991) | Sep 03, 2022 |
| Dell          | Latitude 3510               | [9477575b26](https://linux-hardware.org/?probe=9477575b26) | Sep 03, 2022 |
| Acer          | TravelMate P653-M           | [c0fcc47188](https://linux-hardware.org/?probe=c0fcc47188) | Sep 03, 2022 |
| Timi          | RedmiBook Pro 15S           | [74c07405db](https://linux-hardware.org/?probe=74c07405db) | Sep 03, 2022 |
| Daten Tecn... | DT02-M4                     | [b697980a15](https://linux-hardware.org/?probe=b697980a15) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [ae224152de](https://linux-hardware.org/?probe=ae224152de) | Sep 03, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [6109fc3fa8](https://linux-hardware.org/?probe=6109fc3fa8) | Sep 02, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [9f98c80601](https://linux-hardware.org/?probe=9f98c80601) | Sep 02, 2022 |
| ASUSTek       | X756UAM                     | [23f0391963](https://linux-hardware.org/?probe=23f0391963) | Sep 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [be1fece9bd](https://linux-hardware.org/?probe=be1fece9bd) | Sep 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [8e1f677318](https://linux-hardware.org/?probe=8e1f677318) | Sep 02, 2022 |
| Acer          | Aspire 5942                 | [c2c893f2c2](https://linux-hardware.org/?probe=c2c893f2c2) | Sep 02, 2022 |
| ASUSTek       | X75VC                       | [3cd89c5ac3](https://linux-hardware.org/?probe=3cd89c5ac3) | Sep 02, 2022 |
| Dell          | Latitude E6520              | [8f097a1a3f](https://linux-hardware.org/?probe=8f097a1a3f) | Sep 02, 2022 |
| Dell          | Inspiron 5559               | [c7b43caa52](https://linux-hardware.org/?probe=c7b43caa52) | Sep 01, 2022 |
| HP            | Laptop 15-db1xxx            | [51b19bb74b](https://linux-hardware.org/?probe=51b19bb74b) | Sep 01, 2022 |
| Dell          | Inspiron 15-3567            | [5b1f25ca62](https://linux-hardware.org/?probe=5b1f25ca62) | Sep 01, 2022 |
| Acer          | Aspire V5-431               | [5ac694007d](https://linux-hardware.org/?probe=5ac694007d) | Sep 01, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [814c094769](https://linux-hardware.org/?probe=814c094769) | Sep 01, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [9da6412308](https://linux-hardware.org/?probe=9da6412308) | Sep 01, 2022 |
| Medion        | E6227                       | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Daten Tecn... | DT02-M4                     | [6e337cb132](https://linux-hardware.org/?probe=6e337cb132) | Sep 01, 2022 |
| Alienware     | m15 R4                      | [267e4bb2dd](https://linux-hardware.org/?probe=267e4bb2dd) | Sep 01, 2022 |
| Daten Tecn... | DT02-M4                     | [cdac9cafaf](https://linux-hardware.org/?probe=cdac9cafaf) | Sep 01, 2022 |
| Apple         | MacBookPro5,1               | [4c90105342](https://linux-hardware.org/?probe=4c90105342) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c9fcbe9935](https://linux-hardware.org/?probe=c9fcbe9935) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [52efef286f](https://linux-hardware.org/?probe=52efef286f) | Sep 01, 2022 |
| Acer          | Aspire 5810T                | [6f807b1a84](https://linux-hardware.org/?probe=6f807b1a84) | Sep 01, 2022 |
| Toshiba       | PORTEGE M800                | [547ef88897](https://linux-hardware.org/?probe=547ef88897) | Aug 31, 2022 |
| Toshiba       | PORTEGE M800                | [355cc5a1ec](https://linux-hardware.org/?probe=355cc5a1ec) | Aug 31, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [c1d60c7b0b](https://linux-hardware.org/?probe=c1d60c7b0b) | Aug 31, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [dafd789095](https://linux-hardware.org/?probe=dafd789095) | Aug 31, 2022 |
| Dell          | Inspiron 7720               | [97883c54a3](https://linux-hardware.org/?probe=97883c54a3) | Aug 31, 2022 |
| The Wareho... | E2037                       | [e9599d1061](https://linux-hardware.org/?probe=e9599d1061) | Aug 31, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | [454c7382bd](https://linux-hardware.org/?probe=454c7382bd) | Aug 31, 2022 |
| HP            | EliteBook 840 G5            | [e4b0cb981a](https://linux-hardware.org/?probe=e4b0cb981a) | Aug 31, 2022 |
| Lenovo        | ThinkPad L540 20AUA06000    | [e2fd79b86e](https://linux-hardware.org/?probe=e2fd79b86e) | Aug 30, 2022 |
| Dell          | Inspiron N5110              | [9fe8c04ec6](https://linux-hardware.org/?probe=9fe8c04ec6) | Aug 30, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [aa35aacc70](https://linux-hardware.org/?probe=aa35aacc70) | Aug 30, 2022 |
| Lenovo        | ThinkPad Edge E535 3260E... | [05141be4a5](https://linux-hardware.org/?probe=05141be4a5) | Aug 30, 2022 |
| ASUSTek       | F3F                         | [57c5732aaa](https://linux-hardware.org/?probe=57c5732aaa) | Aug 30, 2022 |
| HP            | Laptop 17-cp0xxx            | [62c06b8d9c](https://linux-hardware.org/?probe=62c06b8d9c) | Aug 30, 2022 |
| Acer          | Aspire 5680                 | [e58163df64](https://linux-hardware.org/?probe=e58163df64) | Aug 30, 2022 |
| Dell          | Latitude E5270              | [d61a2cd74a](https://linux-hardware.org/?probe=d61a2cd74a) | Aug 30, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [4d2ce353d4](https://linux-hardware.org/?probe=4d2ce353d4) | Aug 30, 2022 |
| HP            | ProBook 4540s               | [0509af43f4](https://linux-hardware.org/?probe=0509af43f4) | Aug 30, 2022 |
| HP            | 2000                        | [106a330325](https://linux-hardware.org/?probe=106a330325) | Aug 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [adcfb8a267](https://linux-hardware.org/?probe=adcfb8a267) | Aug 30, 2022 |
| HP            | EliteBook 8440p             | [1f0f196305](https://linux-hardware.org/?probe=1f0f196305) | Aug 29, 2022 |
| Acer          | Aspire E1-571G              | [414795a69b](https://linux-hardware.org/?probe=414795a69b) | Aug 29, 2022 |
| HP            | 2000                        | [9705fe4434](https://linux-hardware.org/?probe=9705fe4434) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [fc5f863965](https://linux-hardware.org/?probe=fc5f863965) | Aug 29, 2022 |
| HP            | ProBook 6550b               | [662065bfe2](https://linux-hardware.org/?probe=662065bfe2) | Aug 29, 2022 |
| Dell          | Latitude 3440               | [3e3f5ac9ab](https://linux-hardware.org/?probe=3e3f5ac9ab) | Aug 29, 2022 |
| Dell          | Vostro 14 5410              | [2d4b907d84](https://linux-hardware.org/?probe=2d4b907d84) | Aug 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b3c97eb801](https://linux-hardware.org/?probe=b3c97eb801) | Aug 29, 2022 |
| Plaisio       | Turbo X                     | [ae92ead1ca](https://linux-hardware.org/?probe=ae92ead1ca) | Aug 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [748d6f1523](https://linux-hardware.org/?probe=748d6f1523) | Aug 29, 2022 |
| Lenovo        | V145-15AST 81MT             | [40b9d37c2a](https://linux-hardware.org/?probe=40b9d37c2a) | Aug 29, 2022 |
| HP            | EliteBook 8560w             | [0ea43b9010](https://linux-hardware.org/?probe=0ea43b9010) | Aug 29, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | [ee3156dfc5](https://linux-hardware.org/?probe=ee3156dfc5) | Aug 29, 2022 |
| Lenovo        | G70-80 80FF                 | [8ac571d297](https://linux-hardware.org/?probe=8ac571d297) | Aug 28, 2022 |
| Lenovo        | G70-80 80FF                 | [3f2eb2720b](https://linux-hardware.org/?probe=3f2eb2720b) | Aug 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a8acbb8d0b](https://linux-hardware.org/?probe=a8acbb8d0b) | Aug 28, 2022 |
| Dell          | Inspiron MM061              | [7d69c012fb](https://linux-hardware.org/?probe=7d69c012fb) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dd415db306](https://linux-hardware.org/?probe=dd415db306) | Aug 28, 2022 |
| ASUSTek       | N71Jv                       | [b30a3030ae](https://linux-hardware.org/?probe=b30a3030ae) | Aug 28, 2022 |
| Dell          | Latitude E6400              | [666ba32534](https://linux-hardware.org/?probe=666ba32534) | Aug 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [8b4125a88a](https://linux-hardware.org/?probe=8b4125a88a) | Aug 28, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [a66f7c7a3a](https://linux-hardware.org/?probe=a66f7c7a3a) | Aug 28, 2022 |
| Acer          | V3-771                      | [3efe8f2f41](https://linux-hardware.org/?probe=3efe8f2f41) | Aug 28, 2022 |
| Lenovo        | G700 20251                  | [25e0f764b5](https://linux-hardware.org/?probe=25e0f764b5) | Aug 28, 2022 |
| Dell          | Inspiron 3505               | [32f22bef7f](https://linux-hardware.org/?probe=32f22bef7f) | Aug 28, 2022 |
| Dell          | Latitude E5510              | [50831b94bf](https://linux-hardware.org/?probe=50831b94bf) | Aug 28, 2022 |
| Dell          | Inspiron 3537               | [d7bec5678a](https://linux-hardware.org/?probe=d7bec5678a) | Aug 27, 2022 |
| Dell          | Inspiron 1501               | [8ec322c539](https://linux-hardware.org/?probe=8ec322c539) | Aug 27, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [e86eacb6b4](https://linux-hardware.org/?probe=e86eacb6b4) | Aug 27, 2022 |
| HP            | ENVY Notebook               | [c43c52b493](https://linux-hardware.org/?probe=c43c52b493) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | [0008869bb6](https://linux-hardware.org/?probe=0008869bb6) | Aug 27, 2022 |
| Apple         | MacBookPro11,3              | [c0e9a2e062](https://linux-hardware.org/?probe=c0e9a2e062) | Aug 27, 2022 |
| TrekStor      | Primebook P14               | [d3237a664d](https://linux-hardware.org/?probe=d3237a664d) | Aug 27, 2022 |
| MSI           | GL72 6QF                    | [1ffe55389e](https://linux-hardware.org/?probe=1ffe55389e) | Aug 27, 2022 |
| Acer          | Aspire 8920                 | [b93b80fdbd](https://linux-hardware.org/?probe=b93b80fdbd) | Aug 27, 2022 |
| MSI           | GL72 6QF                    | [46b40c3c67](https://linux-hardware.org/?probe=46b40c3c67) | Aug 27, 2022 |
| HP            | OMEN by Laptop 15z-en100    | [41f0deff42](https://linux-hardware.org/?probe=41f0deff42) | Aug 27, 2022 |
| Alienware     | m15 R6                      | [d39642f1ce](https://linux-hardware.org/?probe=d39642f1ce) | Aug 26, 2022 |
| HP            | OMEN by Laptop 15z-en100    | [04c6e61e44](https://linux-hardware.org/?probe=04c6e61e44) | Aug 26, 2022 |
| ASUSTek       | X550CC                      | [8b85141416](https://linux-hardware.org/?probe=8b85141416) | Aug 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3f94d521d4](https://linux-hardware.org/?probe=3f94d521d4) | Aug 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | [adf76251c5](https://linux-hardware.org/?probe=adf76251c5) | Aug 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | [7c7a83f951](https://linux-hardware.org/?probe=7c7a83f951) | Aug 26, 2022 |
| ASUSTek       | X542URR                     | [11867009b0](https://linux-hardware.org/?probe=11867009b0) | Aug 26, 2022 |
| Acer          | Aspire 5942                 | [528e0a954b](https://linux-hardware.org/?probe=528e0a954b) | Aug 26, 2022 |
| ASUSTek       | X542URR                     | [909b7dcd37](https://linux-hardware.org/?probe=909b7dcd37) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | [c8d0dcb323](https://linux-hardware.org/?probe=c8d0dcb323) | Aug 26, 2022 |
| ASUSTek       | K72Jk                       | [d456f7083c](https://linux-hardware.org/?probe=d456f7083c) | Aug 26, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [010f9d02e1](https://linux-hardware.org/?probe=010f9d02e1) | Aug 26, 2022 |
| Razer         | Blade                       | [7d825be87d](https://linux-hardware.org/?probe=7d825be87d) | Aug 26, 2022 |
| Apple         | MacBookAir7,2               | [faf049bedc](https://linux-hardware.org/?probe=faf049bedc) | Aug 26, 2022 |
| Apple         | MacBookAir7,2               | [eed296b506](https://linux-hardware.org/?probe=eed296b506) | Aug 26, 2022 |
| Dell          | Latitude 5300               | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | [f2de49c59b](https://linux-hardware.org/?probe=f2de49c59b) | Aug 26, 2022 |
| Daten Tecn... | DT02-M4                     | [21e69486fd](https://linux-hardware.org/?probe=21e69486fd) | Aug 26, 2022 |
| Apple         | MacBookPro8,1               | [c94e06f68f](https://linux-hardware.org/?probe=c94e06f68f) | Aug 26, 2022 |
| Acer          | Aspire 5680                 | [8ee728569a](https://linux-hardware.org/?probe=8ee728569a) | Aug 25, 2022 |
| ASUSTek       | K52Jc                       | [5c10927d11](https://linux-hardware.org/?probe=5c10927d11) | Aug 25, 2022 |
| Apple         | MacBookPro8,1               | [7be66c9d4c](https://linux-hardware.org/?probe=7be66c9d4c) | Aug 25, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [adf697ae96](https://linux-hardware.org/?probe=adf697ae96) | Aug 25, 2022 |
| ASUSTek       | N61Vg                       | [30be913709](https://linux-hardware.org/?probe=30be913709) | Aug 25, 2022 |
| Apple         | MacBookPro5,1               | [6efab17b42](https://linux-hardware.org/?probe=6efab17b42) | Aug 25, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [2a441a673b](https://linux-hardware.org/?probe=2a441a673b) | Aug 25, 2022 |
| HP            | ProBook 640 G2              | [fc50d4e200](https://linux-hardware.org/?probe=fc50d4e200) | Aug 25, 2022 |
| Panasonic     | CF-53AAGZXDX                | [e4bc97855b](https://linux-hardware.org/?probe=e4bc97855b) | Aug 25, 2022 |
| HP            | 15                          | [832c6247b2](https://linux-hardware.org/?probe=832c6247b2) | Aug 25, 2022 |
| Dell          | Precision M4800             | [b00f73e4a3](https://linux-hardware.org/?probe=b00f73e4a3) | Aug 24, 2022 |
| HP            | Compaq CQ58                 | [c4f7e439a9](https://linux-hardware.org/?probe=c4f7e439a9) | Aug 24, 2022 |
| Lenovo        | IdeaPad S205 10382EG        | [f87311cbd3](https://linux-hardware.org/?probe=f87311cbd3) | Aug 24, 2022 |
| ASUSTek       | X705UAP                     | [eacfc15b6c](https://linux-hardware.org/?probe=eacfc15b6c) | Aug 24, 2022 |
| Acer          | TravelMate 5742G            | [37418dc2c7](https://linux-hardware.org/?probe=37418dc2c7) | Aug 24, 2022 |
| ASUSTek       | X751LD                      | [4306baa541](https://linux-hardware.org/?probe=4306baa541) | Aug 24, 2022 |
| HP            | 2000                        | [a17502ee0a](https://linux-hardware.org/?probe=a17502ee0a) | Aug 24, 2022 |
| Razer         | Blade                       | [b552b446f0](https://linux-hardware.org/?probe=b552b446f0) | Aug 24, 2022 |
| HP            | Compaq 6735s                | [4e52bb6ecb](https://linux-hardware.org/?probe=4e52bb6ecb) | Aug 23, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3507cf3eab](https://linux-hardware.org/?probe=3507cf3eab) | Aug 23, 2022 |
| Google        | Snappy                      | [89c9384dc4](https://linux-hardware.org/?probe=89c9384dc4) | Aug 23, 2022 |
| Acer          | Nitro AN517-51              | [e53f196e21](https://linux-hardware.org/?probe=e53f196e21) | Aug 23, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [0c5ed030a3](https://linux-hardware.org/?probe=0c5ed030a3) | Aug 23, 2022 |
| Toshiba       | Satellite L855              | [07b2f24172](https://linux-hardware.org/?probe=07b2f24172) | Aug 23, 2022 |
| Sony          | VGN-NR210FH                 | [8c007bfa55](https://linux-hardware.org/?probe=8c007bfa55) | Aug 23, 2022 |
| HP            | EliteBook 820 G3            | [5cb6011138](https://linux-hardware.org/?probe=5cb6011138) | Aug 23, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c2f58df994](https://linux-hardware.org/?probe=c2f58df994) | Aug 22, 2022 |
| AMI           | Unknown                     | [b6004987ab](https://linux-hardware.org/?probe=b6004987ab) | Aug 22, 2022 |
| Apple         | MacBookPro8,1               | [88bb92c310](https://linux-hardware.org/?probe=88bb92c310) | Aug 22, 2022 |
| ASUSTek       | K53E                        | [65ddd1bb6f](https://linux-hardware.org/?probe=65ddd1bb6f) | Aug 22, 2022 |
| Dell          | Latitude 7420               | [ebbef2bf39](https://linux-hardware.org/?probe=ebbef2bf39) | Aug 22, 2022 |
| Dell          | Latitude 5521               | [b14afc8c75](https://linux-hardware.org/?probe=b14afc8c75) | Aug 22, 2022 |
| Apple         | MacBookPro12,1              | [222fd7ac34](https://linux-hardware.org/?probe=222fd7ac34) | Aug 22, 2022 |
| Dell          | Latitude E6540              | [546fed0c24](https://linux-hardware.org/?probe=546fed0c24) | Aug 22, 2022 |
| Dell          | Inspiron 13-5368            | [9d0f972a5f](https://linux-hardware.org/?probe=9d0f972a5f) | Aug 22, 2022 |
| Lenovo        | ThinkPad X230 2324BB5       | [0c6c383c92](https://linux-hardware.org/?probe=0c6c383c92) | Aug 22, 2022 |
| Apple         | MacBookPro12,1              | [e4dec4681f](https://linux-hardware.org/?probe=e4dec4681f) | Aug 22, 2022 |
| HP            | Mini 110-3100               | [1e27123078](https://linux-hardware.org/?probe=1e27123078) | Aug 22, 2022 |
| Acer          | Aspire 5742G                | [546164ada0](https://linux-hardware.org/?probe=546164ada0) | Aug 22, 2022 |
| HP            | 2000                        | [8462eb5175](https://linux-hardware.org/?probe=8462eb5175) | Aug 22, 2022 |
| HP            | Pavilion dv7                | [81b7ddb4e9](https://linux-hardware.org/?probe=81b7ddb4e9) | Aug 21, 2022 |
| Samsung       | 550XCJ/550XCR               | [cae0d518ee](https://linux-hardware.org/?probe=cae0d518ee) | Aug 21, 2022 |
| HP            | Pavilion 15                 | [c8d31e4708](https://linux-hardware.org/?probe=c8d31e4708) | Aug 21, 2022 |
| Medion        | P7816                       | [086f9ac20c](https://linux-hardware.org/?probe=086f9ac20c) | Aug 20, 2022 |
| Dell          | Latitude E5530 non-vPro     | [d0737ad7f1](https://linux-hardware.org/?probe=d0737ad7f1) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [2fda694b9c](https://linux-hardware.org/?probe=2fda694b9c) | Aug 20, 2022 |
| Apple         | MacBookPro11,3              | [51a98d93a6](https://linux-hardware.org/?probe=51a98d93a6) | Aug 20, 2022 |
| GPU Compan... | GWTN141-10                  | [3bb80937c1](https://linux-hardware.org/?probe=3bb80937c1) | Aug 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ac28d2918e](https://linux-hardware.org/?probe=ac28d2918e) | Aug 20, 2022 |
| HP            | Compaq CQ58                 | [59fadaa084](https://linux-hardware.org/?probe=59fadaa084) | Aug 20, 2022 |
| ASUSTek       | X756UAK                     | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | Precision 7750              | [53e5baea4e](https://linux-hardware.org/?probe=53e5baea4e) | Aug 20, 2022 |
| Acer          | Aspire one 1-431            | [cd1755e81d](https://linux-hardware.org/?probe=cd1755e81d) | Aug 20, 2022 |
| Lenovo        | ThinkPad L540 20AUA06000    | [7783d3ca34](https://linux-hardware.org/?probe=7783d3ca34) | Aug 20, 2022 |
| GPU Compan... | GWTN141-10                  | [ba4a181e92](https://linux-hardware.org/?probe=ba4a181e92) | Aug 20, 2022 |
| HP            | Stream Laptop 14-cb1XX      | [7ab9912d76](https://linux-hardware.org/?probe=7ab9912d76) | Aug 19, 2022 |
| Acer          | Aspire E5-575G              | [771804393e](https://linux-hardware.org/?probe=771804393e) | Aug 19, 2022 |
| HP            | HDX16                       | [46e0559af0](https://linux-hardware.org/?probe=46e0559af0) | Aug 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b97f13141f](https://linux-hardware.org/?probe=b97f13141f) | Aug 19, 2022 |
| HP            | HDX16                       | [fb119a9cb4](https://linux-hardware.org/?probe=fb119a9cb4) | Aug 19, 2022 |
| HP            | EliteBook 8460p             | [1eca9d2f2d](https://linux-hardware.org/?probe=1eca9d2f2d) | Aug 19, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [71b36edb04](https://linux-hardware.org/?probe=71b36edb04) | Aug 19, 2022 |
| HP            | 15                          | [166efee25e](https://linux-hardware.org/?probe=166efee25e) | Aug 19, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [69c8e5eedc](https://linux-hardware.org/?probe=69c8e5eedc) | Aug 19, 2022 |
| Apple         | MacBookPro9,2               | [23fb1e2721](https://linux-hardware.org/?probe=23fb1e2721) | Aug 19, 2022 |
| Apple         | MacBookPro9,2               | [eb35a0b474](https://linux-hardware.org/?probe=eb35a0b474) | Aug 18, 2022 |
| Dell          | Latitude E6420              | [588755599f](https://linux-hardware.org/?probe=588755599f) | Aug 18, 2022 |
| Apple         | MacBook2,1                  | [46208653fa](https://linux-hardware.org/?probe=46208653fa) | Aug 18, 2022 |
| ASUSTek       | X542UQR                     | [4c8af9dc73](https://linux-hardware.org/?probe=4c8af9dc73) | Aug 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9619850e97](https://linux-hardware.org/?probe=9619850e97) | Aug 18, 2022 |
| Toshiba       | QOSMIO X70-B                | [9d599f3d84](https://linux-hardware.org/?probe=9d599f3d84) | Aug 18, 2022 |
| HP            | Pavilion g6                 | [edcd723a3f](https://linux-hardware.org/?probe=edcd723a3f) | Aug 18, 2022 |
| Acer          | Aspire V3-771               | [dc65bd0f38](https://linux-hardware.org/?probe=dc65bd0f38) | Aug 17, 2022 |
| ASUSTek       | X542UQR                     | [8236615818](https://linux-hardware.org/?probe=8236615818) | Aug 17, 2022 |
| Unknown       | Unknown                     | [66053f0e50](https://linux-hardware.org/?probe=66053f0e50) | Aug 17, 2022 |
| HP            | Notebook                    | [784ad31f68](https://linux-hardware.org/?probe=784ad31f68) | Aug 17, 2022 |
| Chuwi         | LarkBook X                  | [b3c5eba91b](https://linux-hardware.org/?probe=b3c5eba91b) | Aug 17, 2022 |
| Lenovo        | Unknown                     | [d6a318092b](https://linux-hardware.org/?probe=d6a318092b) | Aug 16, 2022 |
| Lenovo        | Unknown                     | [a8af2e8de4](https://linux-hardware.org/?probe=a8af2e8de4) | Aug 16, 2022 |
| HP            | 2000                        | [9ac959eca8](https://linux-hardware.org/?probe=9ac959eca8) | Aug 15, 2022 |
| HP            | 2000                        | [caf3781c13](https://linux-hardware.org/?probe=caf3781c13) | Aug 15, 2022 |
| AMI           | Unknown                     | [a1a8c0b2c5](https://linux-hardware.org/?probe=a1a8c0b2c5) | Aug 15, 2022 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [da0503d5dd](https://linux-hardware.org/?probe=da0503d5dd) | Aug 15, 2022 |
| ASUSTek       | B43E                        | [dccc24ad88](https://linux-hardware.org/?probe=dccc24ad88) | Aug 15, 2022 |
| Toshiba       | dynabook T75/RW             | [ff35aa835d](https://linux-hardware.org/?probe=ff35aa835d) | Aug 15, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [82c1a32493](https://linux-hardware.org/?probe=82c1a32493) | Aug 15, 2022 |
| Acer          | AO725                       | [3ee4520923](https://linux-hardware.org/?probe=3ee4520923) | Aug 15, 2022 |
| ASUSTek       | N551VW                      | [b84ee36534](https://linux-hardware.org/?probe=b84ee36534) | Aug 15, 2022 |
| ASUSTek       | N551VW                      | [b4daacb47f](https://linux-hardware.org/?probe=b4daacb47f) | Aug 15, 2022 |
| HP            | 240 G7 Notebook PC          | [24849a5c23](https://linux-hardware.org/?probe=24849a5c23) | Aug 15, 2022 |
| Lenovo        | G470 20078                  | [cafdc06a51](https://linux-hardware.org/?probe=cafdc06a51) | Aug 14, 2022 |
| HP            | EliteBook 8560w             | [86b3f33331](https://linux-hardware.org/?probe=86b3f33331) | Aug 14, 2022 |
| HP            | EliteBook 8560w             | [4ea7538e24](https://linux-hardware.org/?probe=4ea7538e24) | Aug 14, 2022 |
| ASUSTek       | X756UXM                     | [68be00c00d](https://linux-hardware.org/?probe=68be00c00d) | Aug 14, 2022 |
| Acer          | Swift SF114-34              | [b70232aabe](https://linux-hardware.org/?probe=b70232aabe) | Aug 14, 2022 |
| Lenovo        | ThinkPad W540 20BHS0F206    | [7f24672b73](https://linux-hardware.org/?probe=7f24672b73) | Aug 14, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [cacd0ad0a8](https://linux-hardware.org/?probe=cacd0ad0a8) | Aug 14, 2022 |
| Unknown       | Unknown                     | [5cdd2332d5](https://linux-hardware.org/?probe=5cdd2332d5) | Aug 14, 2022 |
| Dell          | Inspiron 5420               | [83b14f40e6](https://linux-hardware.org/?probe=83b14f40e6) | Aug 14, 2022 |
| Acer          | Aspire 6930G                | [c0ba049caf](https://linux-hardware.org/?probe=c0ba049caf) | Aug 14, 2022 |
| Acer          | Aspire 3100                 | [8ea61dbd3c](https://linux-hardware.org/?probe=8ea61dbd3c) | Aug 14, 2022 |
| Dell          | Inspiron 15-3567            | [42223a802a](https://linux-hardware.org/?probe=42223a802a) | Aug 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [4dec80cf41](https://linux-hardware.org/?probe=4dec80cf41) | Aug 13, 2022 |
| Toshiba       | Satellite C660              | [50d9a2d6fe](https://linux-hardware.org/?probe=50d9a2d6fe) | Aug 13, 2022 |
| Alienware     | x15 R2                      | [1d415b648a](https://linux-hardware.org/?probe=1d415b648a) | Aug 13, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | [4a52da1c38](https://linux-hardware.org/?probe=4a52da1c38) | Aug 13, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | [f71b1992c9](https://linux-hardware.org/?probe=f71b1992c9) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | [e93f8de88b](https://linux-hardware.org/?probe=e93f8de88b) | Aug 13, 2022 |
| Acer          | Aspire A515-56              | [e429237c05](https://linux-hardware.org/?probe=e429237c05) | Aug 13, 2022 |
| Notebook      | N9x0TC                      | [a809b1cf7b](https://linux-hardware.org/?probe=a809b1cf7b) | Aug 13, 2022 |
| Foxconn       | Kangaroo Mobile Desktop     | [1b9f19b21e](https://linux-hardware.org/?probe=1b9f19b21e) | Aug 13, 2022 |
| Google        | Celes                       | [f6716098f9](https://linux-hardware.org/?probe=f6716098f9) | Aug 13, 2022 |
| Samsung       | 550XDA                      | [4964cf32aa](https://linux-hardware.org/?probe=4964cf32aa) | Aug 12, 2022 |
| ASUSTek       | UX303LAB                    | [169419cea0](https://linux-hardware.org/?probe=169419cea0) | Aug 12, 2022 |
| Dell          | Latitude 5521               | [39f7c1e9ce](https://linux-hardware.org/?probe=39f7c1e9ce) | Aug 12, 2022 |
| Lenovo        | ThinkPad T480 20L6SBD000    | [b0bbce7c9d](https://linux-hardware.org/?probe=b0bbce7c9d) | Aug 12, 2022 |
| ASUSTek       | G53SW                       | [4aa126ad5b](https://linux-hardware.org/?probe=4aa126ad5b) | Aug 12, 2022 |
| Samsung       | R430/R480/R440              | [39323c99dc](https://linux-hardware.org/?probe=39323c99dc) | Aug 12, 2022 |
| Positivo      | Q4128C-S                    | [4f8b07c958](https://linux-hardware.org/?probe=4f8b07c958) | Aug 12, 2022 |
| HP            | EliteBook 2760p             | [0ce6a49a7f](https://linux-hardware.org/?probe=0ce6a49a7f) | Aug 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f41308ccdc](https://linux-hardware.org/?probe=f41308ccdc) | Aug 12, 2022 |
| Lenovo        | ThinkPad T540p 20BFA0MN0... | [396a40a489](https://linux-hardware.org/?probe=396a40a489) | Aug 12, 2022 |
| HP            | Laptop 15-da0xxx            | [70ea8b51c8](https://linux-hardware.org/?probe=70ea8b51c8) | Aug 12, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [279c16c1e3](https://linux-hardware.org/?probe=279c16c1e3) | Aug 12, 2022 |
| Apple         | MacBookPro9,2               | [f48110428f](https://linux-hardware.org/?probe=f48110428f) | Aug 11, 2022 |
| Packard Be... | EasyNote LE69KB             | [8e79ac1a3e](https://linux-hardware.org/?probe=8e79ac1a3e) | Aug 11, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [24534c03df](https://linux-hardware.org/?probe=24534c03df) | Aug 11, 2022 |
| Intel         | (R) Education Tablet        | [a9b5863c1a](https://linux-hardware.org/?probe=a9b5863c1a) | Aug 11, 2022 |
| Lenovo        | ThinkPad E590 20NB0029MC    | [233b3cdd54](https://linux-hardware.org/?probe=233b3cdd54) | Aug 11, 2022 |
| Apple         | MacBookPro5,1               | [ab09f2f44b](https://linux-hardware.org/?probe=ab09f2f44b) | Aug 11, 2022 |
| Dell          | Latitude E6420              | [c5ce4b0bff](https://linux-hardware.org/?probe=c5ce4b0bff) | Aug 10, 2022 |
| Dell          | Latitude 5521               | [25f117c439](https://linux-hardware.org/?probe=25f117c439) | Aug 10, 2022 |
| Toshiba       | Satellite L300              | [b5eb0f557d](https://linux-hardware.org/?probe=b5eb0f557d) | Aug 10, 2022 |
| HP            | EliteBook 840r G4           | [d8dded5468](https://linux-hardware.org/?probe=d8dded5468) | Aug 10, 2022 |
| HP            | EliteBook 840r G4           | [cbe6c79fc8](https://linux-hardware.org/?probe=cbe6c79fc8) | Aug 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [f8c3a3a610](https://linux-hardware.org/?probe=f8c3a3a610) | Aug 10, 2022 |
| HP            | ProBook 4540s               | [426365299d](https://linux-hardware.org/?probe=426365299d) | Aug 10, 2022 |
| Lenovo        | ThinkPad W530 2447D87       | [f987585f09](https://linux-hardware.org/?probe=f987585f09) | Aug 10, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [1bc504293c](https://linux-hardware.org/?probe=1bc504293c) | Aug 10, 2022 |
| Dell          | Latitude E5450              | [19b094ca76](https://linux-hardware.org/?probe=19b094ca76) | Aug 09, 2022 |
| Lenovo        | V3000 80KV                  | [32c1aa64cf](https://linux-hardware.org/?probe=32c1aa64cf) | Aug 09, 2022 |
| Lenovo        | G500 20236                  | [08df57d0e3](https://linux-hardware.org/?probe=08df57d0e3) | Aug 09, 2022 |
| Lenovo        | ThinkPad T520 423946U       | [c65d210466](https://linux-hardware.org/?probe=c65d210466) | Aug 09, 2022 |
| Lenovo        | G570 4334                   | [8da94d8c9a](https://linux-hardware.org/?probe=8da94d8c9a) | Aug 09, 2022 |
| AMI           | Intel                       | [8d8db9dc8b](https://linux-hardware.org/?probe=8d8db9dc8b) | Aug 09, 2022 |
| Sony          | SVF1521L1RW                 | [c5f143f93d](https://linux-hardware.org/?probe=c5f143f93d) | Aug 09, 2022 |
| AMI           | Intel                       | [0958b0a578](https://linux-hardware.org/?probe=0958b0a578) | Aug 09, 2022 |
| ASUSTek       | X751LD                      | [e9d631e886](https://linux-hardware.org/?probe=e9d631e886) | Aug 08, 2022 |
| ASUSTek       | X200MA                      | [f5a57fdc48](https://linux-hardware.org/?probe=f5a57fdc48) | Aug 08, 2022 |
| Acer          | Aspire A315-56              | [95de2fe5b3](https://linux-hardware.org/?probe=95de2fe5b3) | Aug 08, 2022 |
| Dell          | Latitude E6420              | [54981e31fa](https://linux-hardware.org/?probe=54981e31fa) | Aug 08, 2022 |
| Apple         | MacBook2,1                  | [d3f41ae4fb](https://linux-hardware.org/?probe=d3f41ae4fb) | Aug 08, 2022 |
| Google        | Treeya                      | [11f77c6171](https://linux-hardware.org/?probe=11f77c6171) | Aug 08, 2022 |
| HP            | Mini 110-3100               | [f91eefcb06](https://linux-hardware.org/?probe=f91eefcb06) | Aug 07, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [37aba41425](https://linux-hardware.org/?probe=37aba41425) | Aug 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [98a74dfffd](https://linux-hardware.org/?probe=98a74dfffd) | Aug 07, 2022 |
| Lenovo        | Unknown                     | [4fe504845e](https://linux-hardware.org/?probe=4fe504845e) | Aug 07, 2022 |
| Toshiba       | dynabook R732/G             | [82ef8736b3](https://linux-hardware.org/?probe=82ef8736b3) | Aug 07, 2022 |
| HP            | Laptop 17-by3xxx            | [8ef73154f3](https://linux-hardware.org/?probe=8ef73154f3) | Aug 07, 2022 |
| HP            | Laptop 17-by3xxx            | [f6e0bbd5d6](https://linux-hardware.org/?probe=f6e0bbd5d6) | Aug 07, 2022 |
| HP            | EliteBook 2540p             | [14e0900f42](https://linux-hardware.org/?probe=14e0900f42) | Aug 06, 2022 |
| Matsushita... | CF-52DCABZBM                | [2778e96587](https://linux-hardware.org/?probe=2778e96587) | Aug 06, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [2826163ef7](https://linux-hardware.org/?probe=2826163ef7) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [9c945add4e](https://linux-hardware.org/?probe=9c945add4e) | Aug 06, 2022 |
| System76      | Oryx Pro                    | [60bd35b24f](https://linux-hardware.org/?probe=60bd35b24f) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [d1ab7d1d36](https://linux-hardware.org/?probe=d1ab7d1d36) | Aug 06, 2022 |
| Dell          | Latitude E5470              | [7663151d4a](https://linux-hardware.org/?probe=7663151d4a) | Aug 06, 2022 |
| Packard Be... | EasyNote LS11HR             | [0f1a9e4af2](https://linux-hardware.org/?probe=0f1a9e4af2) | Aug 06, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | [091235281e](https://linux-hardware.org/?probe=091235281e) | Aug 06, 2022 |
| HP            | Laptop 15-bs0xx             | [7e9b1406b1](https://linux-hardware.org/?probe=7e9b1406b1) | Aug 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [89b2da04d8](https://linux-hardware.org/?probe=89b2da04d8) | Aug 06, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [12dd099419](https://linux-hardware.org/?probe=12dd099419) | Aug 06, 2022 |
| Sony          | VPCSB35FB                   | [edbd7a9cb8](https://linux-hardware.org/?probe=edbd7a9cb8) | Aug 06, 2022 |
| Apple         | MacBookPro9,2               | [a1b55cc875](https://linux-hardware.org/?probe=a1b55cc875) | Aug 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a449c3a1b5](https://linux-hardware.org/?probe=a449c3a1b5) | Aug 05, 2022 |
| Acer          | AO756                       | [4bc715a31c](https://linux-hardware.org/?probe=4bc715a31c) | Aug 05, 2022 |
| Acer          | Aspire A515-56G             | [3df2b6b19b](https://linux-hardware.org/?probe=3df2b6b19b) | Aug 05, 2022 |
| Medion        | P6612                       | [ecf722df7c](https://linux-hardware.org/?probe=ecf722df7c) | Aug 05, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | [431684d65c](https://linux-hardware.org/?probe=431684d65c) | Aug 05, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e6c4370f10](https://linux-hardware.org/?probe=e6c4370f10) | Aug 05, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [237cf11989](https://linux-hardware.org/?probe=237cf11989) | Aug 05, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [aec2ac880f](https://linux-hardware.org/?probe=aec2ac880f) | Aug 05, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [fa0a089121](https://linux-hardware.org/?probe=fa0a089121) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [4acbeffc03](https://linux-hardware.org/?probe=4acbeffc03) | Aug 05, 2022 |
| OnLogic       | Helix3X0                    | [4704efd8b5](https://linux-hardware.org/?probe=4704efd8b5) | Aug 05, 2022 |
| OnLogic       | Helix3X0                    | [fe16142cb8](https://linux-hardware.org/?probe=fe16142cb8) | Aug 05, 2022 |
| Acer          | Aspire E5-571               | [a249c68580](https://linux-hardware.org/?probe=a249c68580) | Aug 04, 2022 |
| Dell          | Latitude 5521               | [d8ee57e2d5](https://linux-hardware.org/?probe=d8ee57e2d5) | Aug 04, 2022 |
| Dell          | Inspiron 3583               | [7f2e8ddf72](https://linux-hardware.org/?probe=7f2e8ddf72) | Aug 04, 2022 |
| Apple         | MacBook4,1                  | [96645b0a94](https://linux-hardware.org/?probe=96645b0a94) | Aug 04, 2022 |
| Notebook      | NJ50_70CU                   | [fc31dfa99e](https://linux-hardware.org/?probe=fc31dfa99e) | Aug 04, 2022 |
| Dell          | Latitude E5520              | [1e3f6832b1](https://linux-hardware.org/?probe=1e3f6832b1) | Aug 04, 2022 |
| Acer          | Aspire A515-55              | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| HUAWEI        | HVY-WXX9                    | [06852d59ac](https://linux-hardware.org/?probe=06852d59ac) | Aug 04, 2022 |
| HUAWEI        | HVY-WXX9                    | [057187b6c9](https://linux-hardware.org/?probe=057187b6c9) | Aug 04, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [8bd9c2f957](https://linux-hardware.org/?probe=8bd9c2f957) | Aug 04, 2022 |
| Dell          | Latitude E6430s             | [542db6380a](https://linux-hardware.org/?probe=542db6380a) | Aug 04, 2022 |
| OnLogic       | Helix3X0                    | [8ca2fd3322](https://linux-hardware.org/?probe=8ca2fd3322) | Aug 04, 2022 |
| Acer          | Aspire 5820TG               | [c07c231f70](https://linux-hardware.org/?probe=c07c231f70) | Aug 04, 2022 |
| HP            | Pavilion 17                 | [cbbaa8f0db](https://linux-hardware.org/?probe=cbbaa8f0db) | Aug 03, 2022 |
| Apple         | MacBookPro9,2               | [f0479b116f](https://linux-hardware.org/?probe=f0479b116f) | Aug 03, 2022 |
| Apple         | MacBookPro9,2               | [245834865d](https://linux-hardware.org/?probe=245834865d) | Aug 03, 2022 |
| Acer          | Aspire A315-56              | [aed4690a47](https://linux-hardware.org/?probe=aed4690a47) | Aug 03, 2022 |
| HP            | 255 G6 Notebook PC          | [9f2e2f9442](https://linux-hardware.org/?probe=9f2e2f9442) | Aug 03, 2022 |
| Dell          | Latitude E6430              | [82abc4b330](https://linux-hardware.org/?probe=82abc4b330) | Aug 03, 2022 |
| HP            | ProBook 650 G1              | [da1731c1d2](https://linux-hardware.org/?probe=da1731c1d2) | Aug 03, 2022 |
| Acer          | Aspire E5-476G              | [9c842ec71c](https://linux-hardware.org/?probe=9c842ec71c) | Aug 03, 2022 |
| Lenovo        | 3000 G530 4151/200          | [8e9bf5b1f9](https://linux-hardware.org/?probe=8e9bf5b1f9) | Aug 03, 2022 |
| Dell          | XPS 9320                    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| Dell          | XPS 15 9550                 | [fe2d85b49b](https://linux-hardware.org/?probe=fe2d85b49b) | Aug 03, 2022 |
| LG Electro... | R480-L.B211P1               | [307f422c53](https://linux-hardware.org/?probe=307f422c53) | Aug 03, 2022 |
| HP            | ProBook 455 G7              | [86bdcba616](https://linux-hardware.org/?probe=86bdcba616) | Aug 02, 2022 |
| Dell          | Latitude E6420              | [59c6623274](https://linux-hardware.org/?probe=59c6623274) | Aug 02, 2022 |
| HP            | Laptop 17-cp0xxx            | [eedeb321f6](https://linux-hardware.org/?probe=eedeb321f6) | Aug 02, 2022 |
| Dell          | G3 3500                     | [440b43e5e5](https://linux-hardware.org/?probe=440b43e5e5) | Aug 02, 2022 |
| Lenovo        | ThinkPad X230 23245NJ       | [3c85e43b86](https://linux-hardware.org/?probe=3c85e43b86) | Aug 01, 2022 |
| Acer          | Aspire 7741                 | [4e266f6d7f](https://linux-hardware.org/?probe=4e266f6d7f) | Jul 31, 2022 |
| Acer          | Aspire 7741                 | [932a460553](https://linux-hardware.org/?probe=932a460553) | Jul 31, 2022 |
| Lenovo        | IdeaPad 110S-11IBR          | [02e0db6837](https://linux-hardware.org/?probe=02e0db6837) | Jul 31, 2022 |
| Dell          | Latitude E6400              | [6962d36f57](https://linux-hardware.org/?probe=6962d36f57) | Jul 31, 2022 |
| HP            | Stream Notebook PC 13       | [d736692861](https://linux-hardware.org/?probe=d736692861) | Jul 31, 2022 |
| HP            | ProBook 645 G1              | [f5035ff86e](https://linux-hardware.org/?probe=f5035ff86e) | Jul 31, 2022 |
| Google        | Cyan                        | [34f759ebd1](https://linux-hardware.org/?probe=34f759ebd1) | Jul 31, 2022 |
| HP            | Laptop 15-dy3xxx            | [e54cde5e86](https://linux-hardware.org/?probe=e54cde5e86) | Jul 31, 2022 |
| HP            | Pavilion TS 14 Sleekbook    | [9264052a8c](https://linux-hardware.org/?probe=9264052a8c) | Jul 31, 2022 |
| Fujitsu       | LIFEBOOK S936               | [90a08a49a3](https://linux-hardware.org/?probe=90a08a49a3) | Jul 31, 2022 |
| Fujitsu       | LIFEBOOK S936               | [1af46d1c56](https://linux-hardware.org/?probe=1af46d1c56) | Jul 31, 2022 |
| Acer          | Aspire A315-54K             | [d090bce067](https://linux-hardware.org/?probe=d090bce067) | Jul 30, 2022 |
| Dell          | XPS 13 9380                 | [7463861dcf](https://linux-hardware.org/?probe=7463861dcf) | Jul 30, 2022 |
| Sony          | SVE1511Y1ESI                | [7e5ced1b91](https://linux-hardware.org/?probe=7e5ced1b91) | Jul 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [a2f1dbe3f7](https://linux-hardware.org/?probe=a2f1dbe3f7) | Jul 30, 2022 |
| Google        | Auron_Paine                 | [0ac60b52f1](https://linux-hardware.org/?probe=0ac60b52f1) | Jul 30, 2022 |
| Acer          | Peppy                       | [d8f9cbdb86](https://linux-hardware.org/?probe=d8f9cbdb86) | Jul 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0dce3ee4a5](https://linux-hardware.org/?probe=0dce3ee4a5) | Jul 30, 2022 |
| Acer          | Peppy                       | [6f4ce7e1f9](https://linux-hardware.org/?probe=6f4ce7e1f9) | Jul 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [90fec04191](https://linux-hardware.org/?probe=90fec04191) | Jul 30, 2022 |
| AMI           | T3 MRD                      | [7e0a2ced92](https://linux-hardware.org/?probe=7e0a2ced92) | Jul 29, 2022 |
| ASUSTek       | T100TAM                     | [fca54dfc19](https://linux-hardware.org/?probe=fca54dfc19) | Jul 29, 2022 |
| ASUSTek       | T100TAM                     | [4321f0776b](https://linux-hardware.org/?probe=4321f0776b) | Jul 29, 2022 |
| HP            | 255 G8 Notebook PC          | [e271ff9bf8](https://linux-hardware.org/?probe=e271ff9bf8) | Jul 29, 2022 |
| HP            | EliteBook 8570w             | [37c6d6abde](https://linux-hardware.org/?probe=37c6d6abde) | Jul 29, 2022 |
| Dell          | Latitude 9420               | [1ee70bdfc6](https://linux-hardware.org/?probe=1ee70bdfc6) | Jul 29, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [53a117cd64](https://linux-hardware.org/?probe=53a117cd64) | Jul 29, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [e943a26cec](https://linux-hardware.org/?probe=e943a26cec) | Jul 29, 2022 |
| HP            | Pavilion 15                 | [e6bfde2a29](https://linux-hardware.org/?probe=e6bfde2a29) | Jul 29, 2022 |
| Acer          | Aspire 7520                 | [934f648cb3](https://linux-hardware.org/?probe=934f648cb3) | Jul 28, 2022 |
| MSI           | GT72S 6QE                   | [9cb4896eba](https://linux-hardware.org/?probe=9cb4896eba) | Jul 28, 2022 |
| ASUSTek       | X75A                        | [646a5239a8](https://linux-hardware.org/?probe=646a5239a8) | Jul 28, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [ec8af984d2](https://linux-hardware.org/?probe=ec8af984d2) | Jul 28, 2022 |
| Notebook      | NL4x_NL5xLU                 | [12d6dbed8b](https://linux-hardware.org/?probe=12d6dbed8b) | Jul 28, 2022 |
| HP            | Laptop 15-bw0xx             | [1c661d6eea](https://linux-hardware.org/?probe=1c661d6eea) | Jul 28, 2022 |
| Acer          | Aspire 5755G                | [ba944df1b9](https://linux-hardware.org/?probe=ba944df1b9) | Jul 28, 2022 |
| HP            | 255 G8 Notebook PC          | [ceb1b7da41](https://linux-hardware.org/?probe=ceb1b7da41) | Jul 28, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [cd00cf1bbe](https://linux-hardware.org/?probe=cd00cf1bbe) | Jul 28, 2022 |
| HP            | ProBook 645 G1              | [5e19387465](https://linux-hardware.org/?probe=5e19387465) | Jul 28, 2022 |
| HP            | ProBook 645 G1              | [8774828c9b](https://linux-hardware.org/?probe=8774828c9b) | Jul 28, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [ce7d32f9d0](https://linux-hardware.org/?probe=ce7d32f9d0) | Jul 28, 2022 |
| Positivo      | Mobile                      | [a8719171ea](https://linux-hardware.org/?probe=a8719171ea) | Jul 28, 2022 |
| Positivo      | Mobile                      | [422b663a21](https://linux-hardware.org/?probe=422b663a21) | Jul 28, 2022 |
| Unknown       | Unknown                     | [f14e834c32](https://linux-hardware.org/?probe=f14e834c32) | Jul 28, 2022 |
| HP            | Pavilion g7                 | [02040b1ca1](https://linux-hardware.org/?probe=02040b1ca1) | Jul 27, 2022 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | [bc3633b5a0](https://linux-hardware.org/?probe=bc3633b5a0) | Jul 27, 2022 |
| HP            | Pavilion dv5                | [5e73f42d72](https://linux-hardware.org/?probe=5e73f42d72) | Jul 27, 2022 |
| Acer          | Aspire 4732Z                | [3d23b4bbdc](https://linux-hardware.org/?probe=3d23b4bbdc) | Jul 27, 2022 |
| Dell          | Latitude 7480               | [86fd278e6d](https://linux-hardware.org/?probe=86fd278e6d) | Jul 27, 2022 |
| Notebook      | P7xxDM(-G)                  | [5ec2e8ed2b](https://linux-hardware.org/?probe=5ec2e8ed2b) | Jul 27, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b4a9542143](https://linux-hardware.org/?probe=b4a9542143) | Jul 27, 2022 |
| HP            | 250 G6 Notebook PC          | [ae677e8869](https://linux-hardware.org/?probe=ae677e8869) | Jul 27, 2022 |
| HP            | Pavilion g6                 | [a57cf84361](https://linux-hardware.org/?probe=a57cf84361) | Jul 27, 2022 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [c872c322dc](https://linux-hardware.org/?probe=c872c322dc) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| HP            | Pavilion dv2                | [1d7f92e6ac](https://linux-hardware.org/?probe=1d7f92e6ac) | Jul 27, 2022 |
| HP            | EliteBook 840 G1            | [2dc0ffa0d1](https://linux-hardware.org/?probe=2dc0ffa0d1) | Jul 26, 2022 |
| Intel         | powered classmate PC        | [5ef3ce99dc](https://linux-hardware.org/?probe=5ef3ce99dc) | Jul 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [d748013457](https://linux-hardware.org/?probe=d748013457) | Jul 26, 2022 |
| HP            | OMEN by Laptop 15z-en100    | [d796f6c916](https://linux-hardware.org/?probe=d796f6c916) | Jul 26, 2022 |
| Intel         | powered classmate PC        | [53e2fcbd36](https://linux-hardware.org/?probe=53e2fcbd36) | Jul 26, 2022 |
| Lenovo        | G50-70 20351                | [4ddfbb6ad8](https://linux-hardware.org/?probe=4ddfbb6ad8) | Jul 26, 2022 |
| Lenovo        | ThinkPad SL510 28477MG      | [23c5c0f139](https://linux-hardware.org/?probe=23c5c0f139) | Jul 26, 2022 |
| Dell          | Inspiron 14-3467            | [1c2babaa0a](https://linux-hardware.org/?probe=1c2babaa0a) | Jul 26, 2022 |
| eMachines     | D730                        | [4cba9849a0](https://linux-hardware.org/?probe=4cba9849a0) | Jul 26, 2022 |
| Dell          | Latitude 3400               | [3412e8deac](https://linux-hardware.org/?probe=3412e8deac) | Jul 26, 2022 |
| GPU Compan... | GWNR71517                   | [44ce7e516b](https://linux-hardware.org/?probe=44ce7e516b) | Jul 26, 2022 |
| MSI           | GS40 6QE Phantom            | [137d7c8701](https://linux-hardware.org/?probe=137d7c8701) | Jul 26, 2022 |
| MSI           | GS40 6QE Phantom            | [76bd6feebe](https://linux-hardware.org/?probe=76bd6feebe) | Jul 26, 2022 |
| Daten Tecn... | DT02-M4                     | [8719e60f77](https://linux-hardware.org/?probe=8719e60f77) | Jul 25, 2022 |
| HP            | 245 G7 Notebook PC          | [07c70033f5](https://linux-hardware.org/?probe=07c70033f5) | Jul 25, 2022 |
| Dell          | Latitude 3440               | [a47121441e](https://linux-hardware.org/?probe=a47121441e) | Jul 25, 2022 |
| ASUSTek       | X751LD                      | [0c7a0b98b4](https://linux-hardware.org/?probe=0c7a0b98b4) | Jul 25, 2022 |
| Acer          | Aspire 5749                 | [fa3b08453b](https://linux-hardware.org/?probe=fa3b08453b) | Jul 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Linux_Mint/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Linux Mint 20.3 | 1437      | 17.99%  |
| Linux Mint 20.2 | 1312      | 16.42%  |
| Linux Mint 20.1 | 1218      | 15.25%  |
| Linux Mint 19.3 | 1218      | 15.25%  |
| Linux Mint 20   | 1108      | 13.87%  |
| Linux Mint 19.1 | 473       | 5.92%   |
| Linux Mint 19.2 | 425       | 5.32%   |
| Linux Mint 21   | 406       | 5.08%   |
| Linux Mint 19   | 191       | 2.39%   |
| Linux Mint 18.3 | 148       | 1.85%   |
| Linux Mint 18.2 | 21        | 0.26%   |
| Linux Mint 18.1 | 12        | 0.15%   |
| Linux Mint 18   | 10        | 0.13%   |
| Linux Mint 17.3 | 4         | 0.05%   |
| Linux Mint 17   | 2         | 0.03%   |
| Linux Mint 17.2 | 1         | 0.01%   |
| Linux Mint 15   | 1         | 0.01%   |
| Linux Mint 13   | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Linux Mint | 7446      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-91-generic  | 395       | 4.47%   |
| 5.4.0-58-generic  | 282       | 3.19%   |
| 5.4.0-74-generic  | 262       | 2.96%   |
| 5.4.0-42-generic  | 218       | 2.47%   |
| 5.0.0-32-generic  | 212       | 2.4%    |
| 5.4.0-65-generic  | 175       | 1.98%   |
| 5.4.0-80-generic  | 160       | 1.81%   |
| 5.4.0-77-generic  | 156       | 1.76%   |
| 5.4.0-66-generic  | 156       | 1.76%   |
| 5.4.0-81-generic  | 152       | 1.72%   |
| 5.4.0-72-generic  | 144       | 1.63%   |
| 5.4.0-100-generic | 141       | 1.6%    |
| 5.4.0-73-generic  | 139       | 1.57%   |
| 5.4.0-122-generic | 136       | 1.54%   |
| 5.4.0-70-generic  | 132       | 1.49%   |
| 4.15.0-54-generic | 128       | 1.45%   |
| 4.15.0-20-generic | 128       | 1.45%   |
| 5.4.0-90-generic  | 127       | 1.44%   |
| 5.4.0-89-generic  | 122       | 1.38%   |
| 5.4.0-107-generic | 121       | 1.37%   |
| 5.4.0-26-generic  | 116       | 1.31%   |
| 5.4.0-88-generic  | 115       | 1.3%    |
| 5.4.0-109-generic | 111       | 1.26%   |
| 5.4.0-48-generic  | 110       | 1.24%   |
| 5.15.0-47-generic | 99        | 1.12%   |
| 5.4.0-96-generic  | 98        | 1.11%   |
| 5.15.0-46-generic | 94        | 1.06%   |
| 5.3.0-46-generic  | 92        | 1.04%   |
| 5.4.0-84-generic  | 91        | 1.03%   |
| 5.4.0-121-generic | 86        | 0.97%   |
| 5.15.0-48-generic | 82        | 0.93%   |
| 5.3.0-51-generic  | 79        | 0.89%   |
| 5.3.0-53-generic  | 78        | 0.88%   |
| 5.4.0-104-generic | 77        | 0.87%   |
| 5.4.0-52-generic  | 75        | 0.85%   |
| 5.4.0-99-generic  | 74        | 0.84%   |
| 5.0.0-37-generic  | 72        | 0.81%   |
| 4.15.0-46-generic | 70        | 0.79%   |
| 5.3.0-40-generic  | 68        | 0.77%   |
| 5.4.0-40-generic  | 66        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 4528      | 57.48%  |
| 4.15.0  | 1070      | 13.58%  |
| 5.3.0   | 516       | 6.55%   |
| 5.15.0  | 470       | 5.97%   |
| 5.0.0   | 321       | 4.08%   |
| 5.13.0  | 191       | 2.42%   |
| 5.8.0   | 176       | 2.23%   |
| 5.11.0  | 161       | 2.04%   |
| 4.10.0  | 51        | 0.65%   |
| 4.18.0  | 36        | 0.46%   |
| 5.14.0  | 35        | 0.44%   |
| 4.4.0   | 33        | 0.42%   |
| 4.13.0  | 32        | 0.41%   |
| 5.10.0  | 22        | 0.28%   |
| 5.6.0   | 13        | 0.17%   |
| 4.8.0   | 11        | 0.14%   |
| 5.7.1   | 7         | 0.09%   |
| 5.9.8   | 4         | 0.05%   |
| 5.9.0   | 4         | 0.05%   |
| 5.17.0  | 4         | 0.05%   |
| 6.0.0   | 3         | 0.04%   |
| 5.9.1   | 3         | 0.04%   |
| 5.7.11  | 3         | 0.04%   |
| 5.7.0   | 3         | 0.04%   |
| 5.5.0   | 3         | 0.04%   |
| 5.4.2   | 3         | 0.04%   |
| 5.18.2  | 3         | 0.04%   |
| 5.18.12 | 3         | 0.04%   |
| 5.17.5  | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 5.9.4   | 2         | 0.03%   |
| 5.9.10  | 2         | 0.03%   |
| 5.8.9   | 2         | 0.03%   |
| 5.8.16  | 2         | 0.03%   |
| 5.8.10  | 2         | 0.03%   |
| 5.6.2   | 2         | 0.03%   |
| 5.3.8   | 2         | 0.03%   |
| 5.3.6   | 2         | 0.03%   |
| 5.3.11  | 2         | 0.03%   |
| 5.2.0   | 2         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 4536      | 57.64%  |
| 4.15    | 1072      | 13.62%  |
| 5.3     | 527       | 6.7%    |
| 5.15    | 485       | 6.16%   |
| 5.0     | 324       | 4.12%   |
| 5.13    | 196       | 2.49%   |
| 5.8     | 186       | 2.36%   |
| 5.11    | 164       | 2.08%   |
| 4.10    | 51        | 0.65%   |
| 5.14    | 41        | 0.52%   |
| 4.18    | 38        | 0.48%   |
| 5.10    | 33        | 0.42%   |
| 4.4     | 33        | 0.42%   |
| 4.13    | 33        | 0.42%   |
| 5.6     | 19        | 0.24%   |
| 5.9     | 18        | 0.23%   |
| 5.7     | 15        | 0.19%   |
| 5.18    | 11        | 0.14%   |
| 5.17    | 11        | 0.14%   |
| 4.8     | 11        | 0.14%   |
| 5.12    | 9         | 0.11%   |
| 5.16    | 8         | 0.1%    |
| 5.5     | 6         | 0.08%   |
| 5.1     | 6         | 0.08%   |
| 5.2     | 5         | 0.06%   |
| 4.19    | 5         | 0.06%   |
| 6.0     | 4         | 0.05%   |
| 5.19    | 4         | 0.05%   |
| 4.20    | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 4.16    | 2         | 0.03%   |
| 3.13    | 2         | 0.03%   |
| 5       | 1         | 0.01%   |
| 4.7     | 1         | 0.01%   |
| 4.17    | 1         | 0.01%   |
| 4.12    | 1         | 0.01%   |
| 4.11    | 1         | 0.01%   |
| 3.8     | 1         | 0.01%   |
| 3.2     | 1         | 0.01%   |
| 3.19    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 7043      | 94.54%  |
| i686   | 407       | 5.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| X-Cinnamon    | 4198      | 54.86%  |
| Cinnamon      | 870       | 11.37%  |
| MATE          | 846       | 11.06%  |
| XFCE          | 788       | 10.3%   |
| Unknown       | 703       | 9.19%   |
| GNOME         | 193       | 2.52%   |
| KDE5          | 18        | 0.24%   |
| KDE           | 17        | 0.22%   |
| i3            | 8         | 0.1%    |
| Deepin        | 3         | 0.04%   |
| Budgie        | 2         | 0.03%   |
| qtile         | 1         | 0.01%   |
| Pantheon      | 1         | 0.01%   |
| LXQt          | 1         | 0.01%   |
| LXDE          | 1         | 0.01%   |
| KDE4          | 1         | 0.01%   |
| GNOME Classic | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 7431      | 99.69%  |
| Wayland | 11        | 0.15%   |
| Tty     | 7         | 0.09%   |
| Unknown | 5         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4559      | 60.01%  |
| LightDM | 1626      | 21.4%   |
| TDM     | 1331      | 17.52%  |
| MDM     | 40        | 0.53%   |
| GDM     | 22        | 0.29%   |
| SDDM    | 17        | 0.22%   |
| GDM3    | 2         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1911      | 25.28%  |
| de_DE   | 1012      | 13.39%  |
| Unknown | 934       | 12.36%  |
| pt_BR   | 648       | 8.57%   |
| ru_RU   | 332       | 4.39%   |
| fr_FR   | 298       | 3.94%   |
| en_GB   | 296       | 3.92%   |
| C       | 262       | 3.47%   |
| it_IT   | 167       | 2.21%   |
| pl_PL   | 154       | 2.04%   |
| es_ES   | 146       | 1.93%   |
| en_CA   | 139       | 1.84%   |
| en_IN   | 96        | 1.27%   |
| en_AU   | 96        | 1.27%   |
| nl_NL   | 71        | 0.94%   |
| cs_CZ   | 58        | 0.77%   |
| en_ZA   | 57        | 0.75%   |
| es_MX   | 54        | 0.71%   |
| es_AR   | 52        | 0.69%   |
| hu_HU   | 50        | 0.66%   |
| pt_PT   | 45        | 0.6%    |
| de_AT   | 45        | 0.6%    |
| ru_UA   | 43        | 0.57%   |
| de_CH   | 37        | 0.49%   |
| tr_TR   | 33        | 0.44%   |
| sv_SE   | 30        | 0.4%    |
| fi_FI   | 25        | 0.33%   |
| fr_CA   | 24        | 0.32%   |
| es_CL   | 24        | 0.32%   |
| el_GR   | 24        | 0.32%   |
| es_CO   | 23        | 0.3%    |
| zh_CN   | 22        | 0.29%   |
| sk_SK   | 20        | 0.26%   |
| fr_BE   | 20        | 0.26%   |
| en_NZ   | 20        | 0.26%   |
| bg_BG   | 20        | 0.26%   |
| nl_BE   | 18        | 0.24%   |
| en_IE   | 18        | 0.24%   |
| uk_UA   | 16        | 0.21%   |
| en_PH   | 15        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3808      | 50.55%  |
| BIOS | 3725      | 49.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 6500      | 86.25%  |
| Unknown  | 644       | 8.55%   |
| Overlay  | 240       | 3.18%   |
| Btrfs    | 93        | 1.23%   |
| Xfs      | 16        | 0.21%   |
| Ext3     | 16        | 0.21%   |
| Ext2     | 12        | 0.16%   |
| Zfs      | 9         | 0.12%   |
| Aufs     | 2         | 0.03%   |
| XXXXX    | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |
| ExX4     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4641      | 61.5%   |
| GPT     | 1971      | 26.12%  |
| MBR     | 934       | 12.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7064      | 94.35%  |
| Yes       | 423       | 5.65%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6161      | 82.17%  |
| Yes       | 1337      | 17.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 1531      | 20.56%  |
| Lenovo              | 1319      | 17.71%  |
| Dell                | 1117      | 15%     |
| Acer                | 780       | 10.48%  |
| ASUSTek Computer    | 739       | 9.92%   |
| Toshiba             | 282       | 3.79%   |
| Samsung Electronics | 240       | 3.22%   |
| Apple               | 170       | 2.28%   |
| Sony                | 137       | 1.84%   |
| MSI                 | 98        | 1.32%   |
| Medion              | 73        | 0.98%   |
| Positivo            | 69        | 0.93%   |
| Fujitsu             | 62        | 0.83%   |
| Google              | 54        | 0.73%   |
| Notebook            | 51        | 0.68%   |
| Unknown             | 49        | 0.66%   |
| Packard Bell        | 45        | 0.6%    |
| Fujitsu Siemens     | 42        | 0.56%   |
| HUAWEI              | 39        | 0.52%   |
| LG Electronics      | 25        | 0.34%   |
| Alienware           | 23        | 0.31%   |
| Timi                | 20        | 0.27%   |
| Intel               | 20        | 0.27%   |
| Gateway             | 20        | 0.27%   |
| Itautec             | 18        | 0.24%   |
| eMachines           | 18        | 0.24%   |
| Digibras            | 18        | 0.24%   |
| Chuwi               | 17        | 0.23%   |
| Panasonic           | 15        | 0.2%    |
| Clevo               | 15        | 0.2%    |
| Semp Toshiba        | 14        | 0.19%   |
| TUXEDO              | 12        | 0.16%   |
| GPU Company         | 12        | 0.16%   |
| Gigabyte Technology | 11        | 0.15%   |
| AMI                 | 11        | 0.15%   |
| OEM                 | 9         | 0.12%   |
| Compal              | 8         | 0.11%   |
| Teclast             | 7         | 0.09%   |
| Schenker            | 7         | 0.09%   |
| Pegatron            | 7         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 82        | 1.1%    |
| HP Notebook                  | 60        | 0.81%   |
| HP Pavilion g6               | 38        | 0.51%   |
| HP Pavilion dv6              | 36        | 0.48%   |
| ASUS P50IJ                   | 30        | 0.4%    |
| HP Laptop 15-bw0xx           | 29        | 0.39%   |
| HP Pavilion dv7              | 28        | 0.38%   |
| HP Pavilion 15               | 28        | 0.38%   |
| Positivo Mobile              | 25        | 0.34%   |
| Dell Inspiron 15-3567        | 24        | 0.32%   |
| HP Laptop 15-bs0xx           | 19        | 0.26%   |
| HP 15                        | 19        | 0.26%   |
| Dell Latitude E6420          | 19        | 0.26%   |
| Dell Inspiron 1545           | 19        | 0.26%   |
| Dell Latitude E6410          | 18        | 0.24%   |
| HP Pavilion g7               | 17        | 0.23%   |
| Dell Latitude E6430          | 17        | 0.23%   |
| Apple MacBookPro8,1          | 17        | 0.23%   |
| HP Pavilion Notebook         | 16        | 0.21%   |
| Dell Latitude E6400          | 16        | 0.21%   |
| Apple MacBookPro9,2          | 16        | 0.21%   |
| Samsung 300E4C/300E5C/300E7C | 15        | 0.2%    |
| Dell Latitude E6540          | 15        | 0.2%    |
| Dell Inspiron 1525           | 15        | 0.2%    |
| HP ProBook 4540s             | 14        | 0.19%   |
| HP ProBook 4530s             | 14        | 0.19%   |
| Lenovo G50-70 20351          | 13        | 0.17%   |
| HP Laptop 15-bs1xx           | 13        | 0.17%   |
| HP EliteBook 8460p           | 13        | 0.17%   |
| HP EliteBook 840 G1          | 13        | 0.17%   |
| Dell Inspiron 3583           | 13        | 0.17%   |
| Samsung 340XAA/350XAA/550XAA | 12        | 0.16%   |
| HP Laptop 15-db0xxx          | 12        | 0.16%   |
| HP G42                       | 12        | 0.16%   |
| HP EliteBook 8470p           | 12        | 0.16%   |
| HP 2000                      | 12        | 0.16%   |
| Dell Latitude E6510          | 12        | 0.16%   |
| Dell Inspiron 5570           | 12        | 0.16%   |
| Acer Swift SF114-34          | 12        | 0.16%   |
| Toshiba Satellite C660       | 11        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 595       | 7.99%   |
| Acer Aspire           | 579       | 7.78%   |
| Dell Inspiron         | 440       | 5.91%   |
| Dell Latitude         | 387       | 5.2%    |
| HP Pavilion           | 363       | 4.88%   |
| Lenovo IdeaPad        | 359       | 4.82%   |
| HP Laptop             | 247       | 3.32%   |
| Toshiba Satellite     | 238       | 3.2%    |
| HP ProBook            | 208       | 2.79%   |
| HP EliteBook          | 199       | 2.67%   |
| ASUS VivoBook         | 100       | 1.34%   |
| Dell Vostro           | 91        | 1.22%   |
| Unknown               | 82        | 1.1%    |
| Dell XPS              | 72        | 0.97%   |
| HP Compaq             | 70        | 0.94%   |
| HP Notebook           | 60        | 0.81%   |
| Fujitsu LIFEBOOK      | 56        | 0.75%   |
| Dell Precision        | 53        | 0.71%   |
| HP 250                | 44        | 0.59%   |
| HP ENVY               | 42        | 0.56%   |
| Acer Swift            | 42        | 0.56%   |
| Packard Bell EasyNote | 39        | 0.52%   |
| HP ZBook              | 35        | 0.47%   |
| Acer TravelMate       | 32        | 0.43%   |
| ASUS ZenBook          | 30        | 0.4%    |
| ASUS P50IJ            | 30        | 0.4%    |
| Acer Extensa          | 30        | 0.4%    |
| HP 255                | 29        | 0.39%   |
| Lenovo Legion         | 27        | 0.36%   |
| HP Presario           | 26        | 0.35%   |
| Positivo Mobile       | 25        | 0.34%   |
| Lenovo Yoga           | 25        | 0.34%   |
| Apple MacBookPro8     | 25        | 0.34%   |
| Acer Nitro            | 25        | 0.34%   |
| HP OMEN               | 24        | 0.32%   |
| ASUS ASUS             | 24        | 0.32%   |
| Fujitsu Siemens AMILO | 23        | 0.31%   |
| HP 15                 | 21        | 0.28%   |
| Apple MacBookPro9     | 21        | 0.28%   |
| ASUS TUF              | 20        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 725       | 9.74%   |
| 2012    | 699       | 9.39%   |
| 2013    | 621       | 8.34%   |
| 2019    | 530       | 7.12%   |
| 2010    | 507       | 6.81%   |
| 2018    | 505       | 6.78%   |
| 2020    | 477       | 6.41%   |
| 2017    | 464       | 6.23%   |
| 2016    | 437       | 5.87%   |
| 2014    | 432       | 5.8%    |
| 2008    | 421       | 5.65%   |
| 2015    | 420       | 5.64%   |
| 2021    | 407       | 5.47%   |
| 2009    | 330       | 4.43%   |
| 2007    | 242       | 3.25%   |
| 2006    | 99        | 1.33%   |
| 2022    | 71        | 0.95%   |
| 2005    | 34        | 0.46%   |
| 2004    | 12        | 0.16%   |
| Unknown | 10        | 0.13%   |
| 2003    | 3         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 7446      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 6665      | 88.89%  |
| Enabled  | 833       | 11.11%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7384      | 99.17%  |
| Yes  | 62        | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2167      | 28.78%  |
| 3.01-4.0    | 2121      | 28.17%  |
| 8.01-16.0   | 1177      | 15.63%  |
| 16.01-24.0  | 914       | 12.14%  |
| 1.01-2.0    | 571       | 7.58%   |
| 32.01-64.0  | 209       | 2.78%   |
| 2.01-3.0    | 201       | 2.67%   |
| 0.51-1.0    | 88        | 1.17%   |
| 24.01-32.0  | 53        | 0.7%    |
| 64.01-256.0 | 27        | 0.36%   |
| 0.01-0.5    | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 3512      | 42.98%  |
| 2.01-3.0   | 2041      | 24.98%  |
| 3.01-4.0   | 853       | 10.44%  |
| 0.51-1.0   | 802       | 9.81%   |
| 4.01-8.0   | 746       | 9.13%   |
| 8.01-16.0  | 135       | 1.65%   |
| 0.01-0.5   | 65        | 0.8%    |
| 16.01-24.0 | 12        | 0.15%   |
| Unknown    | 4         | 0.05%   |
| 24.01-32.0 | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5486      | 72.21%  |
| 2      | 1796      | 23.64%  |
| 3      | 211       | 2.78%   |
| 0      | 65        | 0.86%   |
| 4      | 26        | 0.34%   |
| 5      | 9         | 0.12%   |
| 7      | 2         | 0.03%   |
| 9      | 1         | 0.01%   |
| 6      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3952      | 52.79%  |
| Yes       | 3534      | 47.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6422      | 85.98%  |
| No        | 1047      | 14.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7298      | 97.93%  |
| No        | 154       | 2.07%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5191      | 68.89%  |
| No        | 2344      | 31.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 1174      | 15.67%  |
| USA          | 1111      | 14.83%  |
| Brazil       | 889       | 11.87%  |
| Russia       | 544       | 7.26%   |
| France       | 332       | 4.43%   |
| UK           | 279       | 3.72%   |
| Italy        | 215       | 2.87%   |
| Spain        | 192       | 2.56%   |
| Poland       | 192       | 2.56%   |
| Canada       | 184       | 2.46%   |
| Ukraine      | 153       | 2.04%   |
| Netherlands  | 146       | 1.95%   |
| India        | 117       | 1.56%   |
| Australia    | 110       | 1.47%   |
| Mexico       | 88        | 1.17%   |
| Belgium      | 85        | 1.13%   |
| Czechia      | 83        | 1.11%   |
| Austria      | 79        | 1.05%   |
| Switzerland  | 78        | 1.04%   |
| Portugal     | 76        | 1.01%   |
| Turkey       | 70        | 0.93%   |
| Argentina    | 70        | 0.93%   |
| Hungary      | 63        | 0.84%   |
| Sweden       | 62        | 0.83%   |
| South Africa | 62        | 0.83%   |
| Greece       | 51        | 0.68%   |
| Bulgaria     | 50        | 0.67%   |
| Finland      | 48        | 0.64%   |
| Romania      | 43        | 0.57%   |
| Colombia     | 39        | 0.52%   |
| Slovakia     | 36        | 0.48%   |
| Norway       | 33        | 0.44%   |
| Denmark      | 33        | 0.44%   |
| Indonesia    | 32        | 0.43%   |
| Chile        | 32        | 0.43%   |
| Belarus      | 31        | 0.41%   |
| New Zealand  | 27        | 0.36%   |
| Ireland      | 26        | 0.35%   |
| China        | 26        | 0.35%   |
| Serbia       | 22        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 143       | 1.81%   |
| Berlin            | 109       | 1.38%   |
| Sao Paulo         | 97        | 1.23%   |
| St Petersburg     | 60        | 0.76%   |
| Rockville         | 54        | 0.68%   |
| Vienna            | 53        | 0.67%   |
| Rio de Janeiro    | 53        | 0.67%   |
| Kyiv              | 51        | 0.64%   |
| Paris             | 50        | 0.63%   |
| Milan             | 43        | 0.54%   |
| Warsaw            | 42        | 0.53%   |
| Munich            | 39        | 0.49%   |
| Hamburg           | 38        | 0.48%   |
| Sydney            | 34        | 0.43%   |
| Frankfurt am Main | 34        | 0.43%   |
| Chicago           | 31        | 0.39%   |
| Porto Alegre      | 30        | 0.38%   |
| Madrid            | 30        | 0.38%   |
| Prague            | 29        | 0.37%   |
| Cologne           | 28        | 0.35%   |
| Istanbul          | 27        | 0.34%   |
| Curitiba          | 27        | 0.34%   |
| Belo Horizonte    | 27        | 0.34%   |
| Sofia             | 26        | 0.33%   |
| Amsterdam         | 25        | 0.32%   |
| Stuttgart         | 24        | 0.3%    |
| Brasília         | 23        | 0.29%   |
| Barcelona         | 23        | 0.29%   |
| Zurich            | 22        | 0.28%   |
| Toronto           | 22        | 0.28%   |
| Rome              | 22        | 0.28%   |
| Melbourne         | 22        | 0.28%   |
| Athens            | 22        | 0.28%   |
| London            | 21        | 0.27%   |
| Leipzig           | 21        | 0.27%   |
| Krasnodar         | 21        | 0.27%   |
| Fortaleza         | 21        | 0.27%   |
| Montreal          | 20        | 0.25%   |
| Helsinki          | 20        | 0.25%   |
| Budapest          | 20        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 1287      | 1619   | 14.11%  |
| Seagate                   | 1276      | 1571   | 13.99%  |
| Samsung Electronics       | 1163      | 1522   | 12.75%  |
| Toshiba                   | 854       | 1029   | 9.37%   |
| Unknown                   | 561       | 752    | 6.15%   |
| SanDisk                   | 492       | 662    | 5.4%    |
| Kingston                  | 479       | 586    | 5.25%   |
| Hitachi                   | 377       | 460    | 4.13%   |
| Crucial                   | 285       | 389    | 3.13%   |
| HGST                      | 265       | 341    | 2.91%   |
| SK hynix                  | 260       | 296    | 2.85%   |
| Intel                     | 206       | 268    | 2.26%   |
| A-DATA Technology         | 124       | 163    | 1.36%   |
| Micron Technology         | 121       | 153    | 1.33%   |
| Fujitsu                   | 89        | 112    | 0.98%   |
| China                     | 88        | 111    | 0.97%   |
| Apple                     | 86        | 106    | 0.94%   |
| KIOXIA                    | 66        | 80     | 0.72%   |
| LITEON                    | 60        | 78     | 0.66%   |
| PNY                       | 49        | 58     | 0.54%   |
| Intenso                   | 49        | 59     | 0.54%   |
| SPCC                      | 39        | 51     | 0.43%   |
| LITEONIT                  | 39        | 47     | 0.43%   |
| Transcend                 | 36        | 45     | 0.39%   |
| Phison                    | 35        | 41     | 0.38%   |
| Patriot                   | 33        | 47     | 0.36%   |
| OCZ                       | 32        | 40     | 0.35%   |
| GOODRAM                   | 29        | 40     | 0.32%   |
| KingSpec                  | 27        | 32     | 0.3%    |
| JMicron Technology        | 27        | 36     | 0.3%    |
| Unknown                   | 27        | 30     | 0.3%    |
| Netac                     | 22        | 23     | 0.24%   |
| Apacer                    | 19        | 22     | 0.21%   |
| SSSTC                     | 17        | 17     | 0.19%   |
| Plextor                   | 17        | 21     | 0.19%   |
| Corsair                   | 17        | 18     | 0.19%   |
| Team                      | 15        | 16     | 0.16%   |
| SABRENT                   | 13        | 15     | 0.14%   |
| Silicon Motion            | 12        | 14     | 0.13%   |
| Micron/Crucial Technology | 12        | 15     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB     | 147       | 1.56%   |
| Unknown MMC Card  32GB                 | 143       | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB         | 138       | 1.46%   |
| Toshiba MQ01ABD100 1TB                 | 136       | 1.44%   |
| Kingston SA400S37240G 240GB SSD        | 126       | 1.34%   |
| Toshiba MQ01ABF050 500GB               | 106       | 1.12%   |
| Seagate ST9500325AS 500GB              | 92        | 0.98%   |
| Seagate ST500LT012-1DG142 500GB        | 92        | 0.98%   |
| Unknown MMC Card  64GB                 | 89        | 0.94%   |
| Toshiba MQ04ABF100 1TB                 | 84        | 0.89%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 66        | 0.7%    |
| Unknown MMC Card  128GB                | 65        | 0.69%   |
| Samsung SSD 860 EVO 500GB              | 63        | 0.67%   |
| Kingston SA400S37480G 480GB SSD        | 62        | 0.66%   |
| HGST HTS721010A9E630 1TB               | 59        | 0.63%   |
| HGST HTS545050A7E680 500GB             | 56        | 0.59%   |
| Samsung SSD 850 EVO 500GB              | 52        | 0.55%   |
| Unknown MMC Card  16GB                 | 51        | 0.54%   |
| Kingston SA400S37120G 120GB SSD        | 51        | 0.54%   |
| Samsung SSD 850 EVO 250GB              | 47        | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB               | 45        | 0.48%   |
| Samsung SSD 860 EVO 1TB                | 44        | 0.47%   |
| HGST HTS541010A9E680 1TB               | 44        | 0.47%   |
| Seagate ST500LT012-9WS142 500GB        | 43        | 0.46%   |
| SanDisk NVMe SSD Drive 512GB           | 42        | 0.45%   |
| Samsung NVMe SSD Drive 512GB           | 42        | 0.45%   |
| Crucial CT500MX500SSD1 500GB           | 42        | 0.45%   |
| SanDisk SSD PLUS 240GB                 | 40        | 0.42%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 37        | 0.39%   |
| WDC WD10SPZX-24Z10 1TB                 | 36        | 0.38%   |
| Seagate Expansion 2TB                  | 36        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB            | 36        | 0.38%   |
| Samsung SSD 840 EVO 500GB              | 34        | 0.36%   |
| WDC WD10SPZX-21Z10T0 1TB               | 33        | 0.35%   |
| Seagate ST9320325AS 320GB              | 33        | 0.35%   |
| Crucial CT240BX500SSD1 240GB           | 33        | 0.35%   |
| Toshiba MQ01ABD075 752GB               | 32        | 0.34%   |
| Seagate ST9500420AS 500GB              | 32        | 0.34%   |
| Seagate ST1000LM048-2E7172 1TB         | 32        | 0.34%   |
| Hitachi HTS547575A9E384 752GB          | 31        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1255      | 1537   | 32.61%  |
| WDC                 | 968       | 1192   | 25.16%  |
| Toshiba             | 707       | 838    | 18.37%  |
| Hitachi             | 377       | 460    | 9.8%    |
| HGST                | 265       | 341    | 6.89%   |
| Samsung Electronics | 97        | 113    | 2.52%   |
| Fujitsu             | 88        | 110    | 2.29%   |
| Unknown             | 28        | 38     | 0.73%   |
| Apple               | 15        | 16     | 0.39%   |
| SABRENT             | 12        | 14     | 0.31%   |
| JMicron Technology  | 4         | 5      | 0.1%    |
| HGST HTS            | 4         | 6      | 0.1%    |
| USB3.0              | 3         | 4      | 0.08%   |
| USB                 | 2         | 2      | 0.05%   |
| PHD 3.0             | 2         | 2      | 0.05%   |
| Initio              | 2         | 2      | 0.05%   |
| IBM/Hitachi         | 2         | 2      | 0.05%   |
| HGST HUS            | 2         | 2      | 0.05%   |
| ASMT                | 2         | 3      | 0.05%   |
| ASMedia             | 2         | 2      | 0.05%   |
| Apricorn            | 2         | 4      | 0.05%   |
| SILICONMOTION       | 1         | 2      | 0.03%   |
| SAGE                | 1         | 2      | 0.03%   |
| Maxtor              | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| Intenso             | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| Dell                | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 2      | 0.03%   |
| APPLE HD            | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 679       | 893    | 21.9%   |
| Kingston            | 405       | 503    | 13.06%  |
| SanDisk             | 359       | 484    | 11.58%  |
| Crucial             | 271       | 375    | 8.74%   |
| WDC                 | 192       | 239    | 6.19%   |
| A-DATA Technology   | 112       | 150    | 3.61%   |
| China               | 88        | 111    | 2.84%   |
| Intel               | 78        | 112    | 2.52%   |
| Toshiba             | 60        | 73     | 1.94%   |
| Micron Technology   | 57        | 78     | 1.84%   |
| LITEON              | 57        | 75     | 1.84%   |
| SK hynix            | 55        | 70     | 1.77%   |
| Apple               | 48        | 54     | 1.55%   |
| PNY                 | 46        | 55     | 1.48%   |
| Intenso             | 41        | 49     | 1.32%   |
| LITEONIT            | 39        | 47     | 1.26%   |
| SPCC                | 36        | 48     | 1.16%   |
| Transcend           | 34        | 43     | 1.1%    |
| OCZ                 | 32        | 40     | 1.03%   |
| Patriot             | 31        | 45     | 1%      |
| GOODRAM             | 28        | 39     | 0.9%    |
| KingSpec            | 27        | 32     | 0.87%   |
| Netac               | 20        | 21     | 0.65%   |
| Apacer              | 18        | 21     | 0.58%   |
| Plextor             | 15        | 19     | 0.48%   |
| Team                | 14        | 15     | 0.45%   |
| Lexar               | 12        | 17     | 0.39%   |
| Corsair             | 12        | 13     | 0.39%   |
| KingDian            | 11        | 17     | 0.35%   |
| Unknown             | 11        | 14     | 0.35%   |
| Teclast             | 10        | 11     | 0.32%   |
| Gigabyte Technology | 10        | 12     | 0.32%   |
| TO Exter            | 8         | 10     | 0.26%   |
| Seagate             | 8         | 12     | 0.26%   |
| Hewlett-Packard     | 8         | 9      | 0.26%   |
| Dogfish             | 8         | 13     | 0.26%   |
| BHT                 | 8         | 8      | 0.26%   |
| Union Memory        | 6         | 7      | 0.19%   |
| Phison              | 6         | 9      | 0.19%   |
| Mushkin             | 5         | 11     | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3734      | 4705   | 42.51%  |
| SSD     | 2901      | 4026   | 33.03%  |
| NVMe    | 1467      | 1890   | 16.7%   |
| MMC     | 555       | 740    | 6.32%   |
| Unknown | 126       | 153    | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5978      | 8502   | 72.15%  |
| NVMe | 1452      | 1864   | 17.52%  |
| MMC  | 555       | 740    | 6.7%    |
| SAS  | 301       | 408    | 3.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4526      | 6094   | 69.49%  |
| 0.51-1.0   | 1766      | 2300   | 27.12%  |
| 1.01-2.0   | 181       | 278    | 2.78%   |
| 3.01-4.0   | 24        | 30     | 0.37%   |
| 4.01-10.0  | 15        | 28     | 0.23%   |
| 10.01-20.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2503      | 32.39%  |
| 251-500        | 2217      | 28.69%  |
| 501-1000       | 1160      | 15.01%  |
| 51-100         | 590       | 7.64%   |
| 1001-2000      | 406       | 5.25%   |
| 21-50          | 377       | 4.88%   |
| 1-20           | 240       | 3.11%   |
| More than 3000 | 97        | 1.26%   |
| 2001-3000      | 94        | 1.22%   |
| Unknown        | 43        | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2564      | 31.52%  |
| 21-50          | 1923      | 23.64%  |
| 101-250        | 1260      | 15.49%  |
| 51-100         | 1240      | 15.24%  |
| 251-500        | 625       | 7.68%   |
| 501-1000       | 310       | 3.81%   |
| 1001-2000      | 115       | 1.41%   |
| Unknown        | 43        | 0.53%   |
| More than 3000 | 29        | 0.36%   |
| 2001-3000      | 25        | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 18        | 20     | 3.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 18        | 18     | 3.25%   |
| Seagate ST1000LM035-1RK172 1TB      | 16        | 23     | 2.89%   |
| HGST HTS545050A7E680 500GB          | 16        | 37     | 2.89%   |
| Seagate ST500LT012-9WS142 500GB     | 12        | 13     | 2.17%   |
| Seagate ST500LT012-1DG142 500GB     | 12        | 13     | 2.17%   |
| Toshiba MQ01ABD100 1TB              | 11        | 12     | 1.99%   |
| Toshiba MQ01ABF050 500GB            | 9         | 10     | 1.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 9         | 10     | 1.63%   |
| HGST HTS725050A7E630 500GB          | 9         | 9      | 1.63%   |
| LITEON CV8-8E128-HP 128GB SSD       | 8         | 10     | 1.45%   |
| HGST HTS541010A9E680 1TB            | 8         | 8      | 1.45%   |
| Toshiba MK7575GSX 752GB             | 7         | 7      | 1.27%   |
| Hitachi HTS547575A9E384 752GB       | 7         | 7      | 1.27%   |
| HGST HTS721010A9E630 1TB            | 7         | 7      | 1.27%   |
| Seagate ST9500420AS 500GB           | 6         | 6      | 1.08%   |
| Seagate ST9320325AS 320GB           | 6         | 6      | 1.08%   |
| Toshiba MK3265GSX 320GB             | 5         | 5      | 0.9%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 5         | 5      | 0.9%    |
| SanDisk SD8SN8U-128G-1006 128GB SSD | 5         | 7      | 0.9%    |
| Hitachi HTS547550A9E384 500GB       | 5         | 5      | 0.9%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 4         | 4      | 0.72%   |
| WDC WD10JPVX-60JC3T0 1TB            | 4         | 5      | 0.72%   |
| WDC WD10JPVX-22JC3T0 1TB            | 4         | 4      | 0.72%   |
| Toshiba MQ04ABF100 1TB              | 4         | 4      | 0.72%   |
| Toshiba MK1652GSX 160GB             | 4         | 4      | 0.72%   |
| Seagate ST9250410AS 250GB           | 4         | 4      | 0.72%   |
| Seagate ST9250315AS 250GB           | 4         | 4      | 0.72%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 4      | 0.72%   |
| Seagate ST500LM000-SSHD-8GB         | 4         | 4      | 0.72%   |
| Seagate ST320LT020-9YG142 320GB     | 4         | 4      | 0.72%   |
| Seagate ST1000LM014-1EJ164 1TB      | 4         | 4      | 0.72%   |
| Hitachi HTS545050A7E380 500GB       | 4         | 4      | 0.72%   |
| Hitachi HTS545025B9A300 250GB       | 4         | 4      | 0.72%   |
| Hitachi HTS543232A7A384 320GB       | 4         | 4      | 0.72%   |
| HGST HTS545050A7E380 500GB          | 4         | 5      | 0.72%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 3         | 3      | 0.54%   |
| WDC WD5000LPVT-22G33T0 500GB        | 3         | 3      | 0.54%   |
| Toshiba MK5059GSXP 500GB            | 3         | 3      | 0.54%   |
| Seagate ST9750420AS 752GB           | 3         | 3      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 164       | 180    | 29.76%  |
| Toshiba             | 80        | 87     | 14.52%  |
| WDC                 | 70        | 80     | 12.7%   |
| Hitachi             | 58        | 60     | 10.53%  |
| HGST                | 50        | 72     | 9.07%   |
| SanDisk             | 28        | 33     | 5.08%   |
| Samsung Electronics | 14        | 15     | 2.54%   |
| Kingston            | 13        | 13     | 2.36%   |
| Crucial             | 12        | 16     | 2.18%   |
| Intel               | 11        | 11     | 2%      |
| SK hynix            | 8         | 10     | 1.45%   |
| LITEON              | 8         | 10     | 1.45%   |
| Fujitsu             | 5         | 5      | 0.91%   |
| Micron Technology   | 4         | 6      | 0.73%   |
| A-DATA Technology   | 4         | 4      | 0.73%   |
| LITEONIT            | 3         | 3      | 0.54%   |
| Apple               | 3         | 3      | 0.54%   |
| OCZ                 | 2         | 2      | 0.36%   |
| China               | 2         | 2      | 0.36%   |
| XPG                 | 1         | 1      | 0.18%   |
| WDC WDS2            | 1         | 1      | 0.18%   |
| Transcend           | 1         | 1      | 0.18%   |
| SSSTC               | 1         | 1      | 0.18%   |
| PNY                 | 1         | 2      | 0.18%   |
| Patriot             | 1         | 1      | 0.18%   |
| Lenovo              | 1         | 1      | 0.18%   |
| KingSpec            | 1         | 1      | 0.18%   |
| JMicron Technology  | 1         | 1      | 0.18%   |
| JDa                 | 1         | 1      | 0.18%   |
| JD                  | 1         | 1      | 0.18%   |
| HGST HTS            | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 164       | 180    | 38.23%  |
| Toshiba             | 75        | 81     | 17.48%  |
| WDC                 | 66        | 76     | 15.38%  |
| Hitachi             | 58        | 60     | 13.52%  |
| HGST                | 50        | 72     | 11.66%  |
| Samsung Electronics | 8         | 9      | 1.86%   |
| Fujitsu             | 5         | 5      | 1.17%   |
| JMicron Technology  | 1         | 1      | 0.23%   |
| HGST HTS            | 1         | 1      | 0.23%   |
| Apple               | 1         | 1      | 0.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 427       | 486    | 77.92%  |
| SSD  | 114       | 132    | 20.8%   |
| NVMe | 7         | 7      | 1.28%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-80V0TT0 500GB                   | 2         | 2      | 18.18%  |
| Toshiba THNSN5512GPU7 512GB                    | 1         | 1      | 9.09%   |
| Toshiba MQ01ABF032 320GB                       | 1         | 1      | 9.09%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 9.09%   |
| Seagate ST9160821AS 160GB                      | 1         | 1      | 9.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1         | 1      | 9.09%   |
| Seagate ST1000LM 024 HN-M101MBB 1TB            | 1         | 1      | 9.09%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 9.09%   |
| Hitachi HTS547550A9E384 500GB                  | 1         | 1      | 9.09%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 3         | 3      | 27.27%  |
| Seagate           | 3         | 3      | 27.27%  |
| WDC               | 2         | 2      | 18.18%  |
| Micron Technology | 1         | 1      | 9.09%   |
| Hitachi           | 1         | 1      | 9.09%   |
| HGST              | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4882      | 7618   | 62.24%  |
| Works    | 2412      | 3259   | 30.75%  |
| Malfunc  | 538       | 625    | 6.86%   |
| Failed   | 11        | 11     | 0.14%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5585      | 68.58%  |
| AMD                              | 958       | 11.76%  |
| Samsung Electronics              | 444       | 5.45%   |
| SanDisk                          | 253       | 3.11%   |
| SK hynix                         | 196       | 2.41%   |
| Toshiba America Info Systems     | 92        | 1.13%   |
| Kingston Technology Company      | 76        | 0.93%   |
| KIOXIA                           | 68        | 0.83%   |
| Nvidia                           | 65        | 0.8%    |
| Micron Technology                | 64        | 0.79%   |
| Silicon Integrated Systems [SiS] | 60        | 0.74%   |
| Phison Electronics               | 43        | 0.53%   |
| Union Memory (Shenzhen)          | 31        | 0.38%   |
| Solid State Storage Technology   | 26        | 0.32%   |
| Micron/Crucial Technology        | 23        | 0.28%   |
| Apple                            | 22        | 0.27%   |
| ADATA Technology                 | 22        | 0.27%   |
| Silicon Motion                   | 21        | 0.26%   |
| VIA Technologies                 | 17        | 0.21%   |
| Realtek Semiconductor            | 14        | 0.17%   |
| Lite-On Technology               | 12        | 0.15%   |
| Marvell Technology Group         | 10        | 0.12%   |
| JMicron Technology               | 10        | 0.12%   |
| Lenovo                           | 8         | 0.1%    |
| Silicon Image                    | 6         | 0.07%   |
| ASMedia Technology               | 5         | 0.06%   |
| Seagate Technology               | 3         | 0.04%   |
| Yangtze Memory Technologies      | 2         | 0.02%   |
| Shenzhen Longsys Electronics     | 2         | 0.02%   |
| OCZ Technology Group             | 2         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |
| Biwin Storage Technology         | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 743       | 8.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 717       | 8.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 556       | 6.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 517       | 5.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 409       | 4.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 377       | 4.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 338       | 3.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 270       | 3.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 210       | 2.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 206       | 2.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 205       | 2.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 203       | 2.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 175       | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller                              | 133       | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 133       | 1.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 132       | 1.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 132       | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 130       | 1.46%   |
| Samsung NVMe SSD Controller 980                                                  | 122       | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 122       | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 108       | 1.21%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 105       | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 99        | 1.11%   |
| Intel Tiger Lake-LP SATA Controller                                              | 90        | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 86        | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 85        | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 78        | 0.87%   |
| Intel SSD 660P Series                                                            | 74        | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 72        | 0.81%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 66        | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                            | 66        | 0.74%   |
| Micron Non-Volatile memory controller                                            | 64        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 64        | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 61        | 0.68%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 60        | 0.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 58        | 0.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 53        | 0.59%   |
| SK hynix Gold P31 SSD                                                            | 52        | 0.58%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 51        | 0.57%   |
| SK hynix BC511                                                                   | 48        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 5703      | 66.76%  |
| NVMe | 1454      | 17.02%  |
| IDE  | 828       | 9.69%   |
| RAID | 557       | 6.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 6219      | 83.52%  |
| AMD          | 1226      | 16.47%  |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 104       | 1.4%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 101       | 1.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 97        | 1.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 87        | 1.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 84        | 1.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 79        | 1.06%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 78        | 1.05%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 73        | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 69        | 0.93%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 69        | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 69        | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 67        | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 65        | 0.87%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 64        | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 63        | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 62        | 0.83%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 61        | 0.82%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 58        | 0.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 57        | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 55        | 0.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 54        | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 53        | 0.71%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 52        | 0.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 51        | 0.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 50        | 0.67%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 50        | 0.67%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 50        | 0.67%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 49        | 0.66%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 46        | 0.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 46        | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 45        | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 45        | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 43        | 0.58%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 43        | 0.58%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 42        | 0.56%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 42        | 0.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 42        | 0.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 41        | 0.55%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 41        | 0.55%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 40        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1805      | 24.22%  |
| Intel Core i7           | 1302      | 17.47%  |
| Intel Core i3           | 783       | 10.51%  |
| Intel Celeron           | 537       | 7.21%   |
| Intel Core 2 Duo        | 487       | 6.54%   |
| Other                   | 313       | 4.2%    |
| Intel Pentium           | 288       | 3.87%   |
| Intel Atom              | 262       | 3.52%   |
| AMD Ryzen 5             | 220       | 2.95%   |
| AMD Ryzen 7             | 159       | 2.13%   |
| AMD A6                  | 106       | 1.42%   |
| Intel Pentium Dual-Core | 102       | 1.37%   |
| AMD A4                  | 90        | 1.21%   |
| Intel Pentium Dual      | 83        | 1.11%   |
| AMD A8                  | 71        | 0.95%   |
| Intel Core 2            | 66        | 0.89%   |
| Intel Genuine           | 63        | 0.85%   |
| AMD A10                 | 60        | 0.81%   |
| AMD Ryzen 3             | 53        | 0.71%   |
| AMD E                   | 51        | 0.68%   |
| Intel Pentium Silver    | 44        | 0.59%   |
| AMD E1                  | 44        | 0.59%   |
| AMD E2                  | 41        | 0.55%   |
| AMD Turion 64 X2 Mobile | 40        | 0.54%   |
| Intel Celeron M         | 32        | 0.43%   |
| AMD Ryzen 7 PRO         | 30        | 0.4%    |
| Intel Pentium M         | 22        | 0.3%    |
| Intel Core i9           | 18        | 0.24%   |
| Intel Celeron Dual-Core | 18        | 0.24%   |
| AMD Ryzen 9             | 15        | 0.2%    |
| AMD Athlon II Dual-Core | 15        | 0.2%    |
| AMD Athlon              | 15        | 0.2%    |
| Intel Core Duo          | 14        | 0.19%   |
| AMD A12                 | 13        | 0.17%   |
| AMD C-60                | 12        | 0.16%   |
| AMD Athlon II           | 12        | 0.16%   |
| AMD Turion 64 Mobile    | 11        | 0.15%   |
| AMD Ryzen 5 PRO         | 11        | 0.15%   |
| AMD Athlon 64 X2        | 11        | 0.15%   |
| AMD Athlon X2           | 10        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4647      | 62.38%  |
| 4      | 1961      | 26.32%  |
| 1      | 311       | 4.17%   |
| 6      | 294       | 3.95%   |
| 8      | 206       | 2.77%   |
| 14     | 14        | 0.19%   |
| 10     | 7         | 0.09%   |
| 12     | 5         | 0.07%   |
| 3      | 4         | 0.05%   |
| 5      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 7446      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4835      | 64.9%   |
| 1      | 2614      | 35.09%  |
| 4      | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6858      | 91.37%  |
| Unknown        | 502       | 6.69%   |
| 32-bit         | 146       | 1.95%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 688       | 9.08%   |
| 0x306a9    | 628       | 8.28%   |
| Unknown    | 605       | 7.98%   |
| 0x40651    | 362       | 4.78%   |
| 0x1067a    | 353       | 4.66%   |
| 0x20655    | 289       | 3.81%   |
| 0x406e3    | 246       | 3.25%   |
| 0x306d4    | 234       | 3.09%   |
| 0x306c3    | 216       | 2.85%   |
| 0x806ea    | 211       | 2.78%   |
| 0x806c1    | 203       | 2.68%   |
| 0x6fd      | 198       | 2.61%   |
| 0x806e9    | 190       | 2.51%   |
| 0x806ec    | 178       | 2.35%   |
| 0x30678    | 157       | 2.07%   |
| 0x906ea    | 156       | 2.06%   |
| 0x406c4    | 151       | 1.99%   |
| 0x20652    | 119       | 1.57%   |
| 0x10676    | 119       | 1.57%   |
| 0x06006705 | 95        | 1.25%   |
| 0x08108109 | 92        | 1.21%   |
| 0x706e5    | 78        | 1.03%   |
| 0x05000119 | 78        | 1.03%   |
| 0x506e3    | 77        | 1.02%   |
| 0x406c3    | 74        | 0.98%   |
| 0x08108102 | 73        | 0.96%   |
| 0x106ca    | 71        | 0.94%   |
| 0x08600106 | 71        | 0.94%   |
| 0x706a1    | 69        | 0.91%   |
| 0xa0652    | 68        | 0.9%    |
| 0x806eb    | 68        | 0.9%    |
| 0x906e9    | 66        | 0.87%   |
| 0x506c9    | 66        | 0.87%   |
| 0x0a50000c | 64        | 0.84%   |
| 0x07030105 | 64        | 0.84%   |
| 0x706a8    | 58        | 0.77%   |
| 0x08608103 | 55        | 0.73%   |
| 0x06001119 | 55        | 0.73%   |
| 0x6f6      | 53        | 0.7%    |
| 0x0700010f | 47        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 970       | 13.02%  |
| SandyBridge      | 718       | 9.64%   |
| IvyBridge        | 674       | 9.05%   |
| Haswell          | 619       | 8.31%   |
| Penryn           | 490       | 6.58%   |
| Westmere         | 426       | 5.72%   |
| Silvermont       | 414       | 5.56%   |
| Skylake          | 361       | 4.85%   |
| Core             | 350       | 4.7%    |
| Broadwell        | 245       | 3.29%   |
| TigerLake        | 211       | 2.83%   |
| Excavator        | 189       | 2.54%   |
| Zen+             | 180       | 2.42%   |
| Bonnell          | 145       | 1.95%   |
| Goldmont plus    | 131       | 1.76%   |
| Zen 2            | 130       | 1.74%   |
| Icelake          | 112       | 1.5%    |
| Unknown          | 110       | 1.48%   |
| P6               | 106       | 1.42%   |
| Bobcat           | 100       | 1.34%   |
| Puma             | 92        | 1.23%   |
| CometLake        | 87        | 1.17%   |
| K8 Hammer        | 80        | 1.07%   |
| Zen 3            | 72        | 0.97%   |
| Goldmont         | 69        | 0.93%   |
| Piledriver       | 64        | 0.86%   |
| K10              | 58        | 0.78%   |
| Jaguar           | 56        | 0.75%   |
| K10 Llano        | 50        | 0.67%   |
| Zen              | 43        | 0.58%   |
| Nehalem          | 30        | 0.4%    |
| K8 & K10 hybrid  | 21        | 0.28%   |
| Alderlake Hybrid | 15        | 0.2%    |
| Steamroller      | 13        | 0.17%   |
| Tremont          | 11        | 0.15%   |
| NetBurst         | 7         | 0.09%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5541      | 61.16%  |
| AMD                              | 1813      | 20.01%  |
| Nvidia                           | 1640      | 18.1%   |
| Silicon Integrated Systems [SiS] | 52        | 0.57%   |
| VIA Technologies                 | 13        | 0.14%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 661       | 6.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 640       | 6.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 372       | 3.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 324       | 3.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 306       | 3.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 240       | 2.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 234       | 2.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 217       | 2.28%   |
| Intel UHD Graphics 620                                                                   | 209       | 2.2%    |
| Intel HD Graphics 5500                                                                   | 209       | 2.2%    |
| Intel HD Graphics 620                                                                    | 199       | 2.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 182       | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 180       | 1.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 170       | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 163       | 1.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 157       | 1.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 148       | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 148       | 1.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 138       | 1.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 130       | 1.37%   |
| AMD Renoir                                                                               | 127       | 1.34%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 102       | 1.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 92        | 0.97%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 89        | 0.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 88        | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 87        | 0.91%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 86        | 0.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 74        | 0.78%   |
| AMD Lucienne                                                                             | 73        | 0.77%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 72        | 0.76%   |
| Intel HD Graphics 530                                                                    | 71        | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 66        | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 65        | 0.68%   |
| Intel HD Graphics 630                                                                    | 65        | 0.68%   |
| AMD Cezanne                                                                              | 64        | 0.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 63        | 0.66%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 59        | 0.62%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 56        | 0.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 52        | 0.55%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 51        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 4004      | 53.71%  |
| 1 x AMD         | 1229      | 16.49%  |
| Intel + Nvidia  | 1182      | 15.86%  |
| 1 x Nvidia      | 381       | 5.11%   |
| Intel + AMD     | 351       | 4.71%   |
| 2 x AMD         | 160       | 2.15%   |
| AMD + Nvidia    | 71        | 0.95%   |
| 1 x SiS         | 52        | 0.7%    |
| 1 x VIA         | 13        | 0.17%   |
| 2 x Nvidia      | 7         | 0.09%   |
| Other           | 4         | 0.05%   |
| 1 x S3 Graphics | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 6151      | 81.86%  |
| Proprietary | 973       | 12.95%  |
| Unknown     | 390       | 5.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4232      | 55.73%  |
| 0.01-0.5   | 1172      | 15.43%  |
| 1.01-2.0   | 1156      | 15.22%  |
| 0.51-1.0   | 472       | 6.22%   |
| 3.01-4.0   | 430       | 5.66%   |
| 5.01-6.0   | 71        | 0.93%   |
| 7.01-8.0   | 42        | 0.55%   |
| 2.01-3.0   | 18        | 0.24%   |
| 8.01-16.0  | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1643      | 20.96%  |
| LG Display              | 1238      | 15.79%  |
| Chimei Innolux          | 944       | 12.04%  |
| Samsung Electronics     | 921       | 11.75%  |
| BOE                     | 887       | 11.32%  |
| Chi Mei Optoelectronics | 253       | 3.23%   |
| Apple                   | 175       | 2.23%   |
| Goldstar                | 159       | 2.03%   |
| Lenovo                  | 157       | 2%      |
| Dell                    | 147       | 1.88%   |
| LG Philips              | 120       | 1.53%   |
| Sharp                   | 94        | 1.2%    |
| PANDA                   | 88        | 1.12%   |
| InfoVision              | 82        | 1.05%   |
| Hewlett-Packard         | 74        | 0.94%   |
| Philips                 | 70        | 0.89%   |
| Acer                    | 69        | 0.88%   |
| AOC                     | 56        | 0.71%   |
| CPT                     | 55        | 0.7%    |
| Sony                    | 53        | 0.68%   |
| BenQ                    | 42        | 0.54%   |
| Seiko/Epson             | 33        | 0.42%   |
| Ancor Communications    | 33        | 0.42%   |
| Toshiba                 | 30        | 0.38%   |
| HannStar                | 30        | 0.38%   |
| InnoLux Display         | 28        | 0.36%   |
| LGD                     | 27        | 0.34%   |
| Iiyama                  | 25        | 0.32%   |
| Quanta Display          | 23        | 0.29%   |
| Panasonic               | 14        | 0.18%   |
| ViewSonic               | 11        | 0.14%   |
| NEC Computers           | 11        | 0.14%   |
| Unknown                 | 10        | 0.13%   |
| Vestel Elektronik       | 9         | 0.11%   |
| JDI                     | 9         | 0.11%   |
| LPL                     | 8         | 0.1%    |
| Fujitsu Siemens         | 8         | 0.1%    |
| ASUSTek Computer        | 8         | 0.1%    |
| IBM                     | 7         | 0.09%   |
| Eizo                    | 7         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 81        | 1.02%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 77        | 0.97%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 66        | 0.83%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 55        | 0.69%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 55        | 0.69%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 53        | 0.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 50        | 0.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 48        | 0.61%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 41        | 0.52%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 40        | 0.51%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 40        | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 37        | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 36        | 0.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 36        | 0.45%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 35        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 34        | 0.43%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch              | 33        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 31        | 0.39%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 31        | 0.39%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 31        | 0.39%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 30        | 0.38%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 27        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 25        | 0.32%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 24        | 0.3%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch             | 24        | 0.3%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 24        | 0.3%    |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                   | 23        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 23        | 0.29%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 23        | 0.29%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 23        | 0.29%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 23        | 0.29%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 22        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 22        | 0.28%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 22        | 0.28%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 22        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 21        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 21        | 0.27%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                      | 21        | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 21        | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 20        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 3120      | 41.35%  |
| 1920x1080 (FHD)    | 2326      | 30.83%  |
| 1600x900 (HD+)     | 545       | 7.22%   |
| 1280x800 (WXGA)    | 467       | 6.19%   |
| 1440x900 (WXGA+)   | 203       | 2.69%   |
| 3840x2160 (4K)     | 160       | 2.12%   |
| 1920x1200 (WUXGA)  | 103       | 1.37%   |
| 1024x600           | 82        | 1.09%   |
| 1680x1050 (WSXGA+) | 68        | 0.9%    |
| 2560x1440 (QHD)    | 66        | 0.87%   |
| 1280x1024 (SXGA)   | 64        | 0.85%   |
| 1360x768           | 42        | 0.56%   |
| 2560x1080          | 30        | 0.4%    |
| 2560x1600          | 28        | 0.37%   |
| 2880x1800          | 27        | 0.36%   |
| Unknown            | 25        | 0.33%   |
| 1024x768 (XGA)     | 23        | 0.3%    |
| 1680x945           | 16        | 0.21%   |
| 3200x1800 (QHD+)   | 15        | 0.2%    |
| 3440x1440          | 14        | 0.19%   |
| 2160x1440          | 13        | 0.17%   |
| 1920x540           | 13        | 0.17%   |
| 3000x2000          | 11        | 0.15%   |
| 3840x2400          | 7         | 0.09%   |
| 3072x1920          | 7         | 0.09%   |
| 1280x720 (HD)      | 7         | 0.09%   |
| 2256x1504          | 5         | 0.07%   |
| 3840x1080          | 4         | 0.05%   |
| 1920x1280          | 4         | 0.05%   |
| 1400x1050          | 4         | 0.05%   |
| 1280x768           | 4         | 0.05%   |
| 3200x2000          | 3         | 0.04%   |
| 1600x1200          | 3         | 0.04%   |
| 3840x1200          | 2         | 0.03%   |
| 3456x2160          | 2         | 0.03%   |
| 3286x1080          | 2         | 0.03%   |
| 3200x1200          | 2         | 0.03%   |
| 2304x1440          | 2         | 0.03%   |
| 2288x1287          | 2         | 0.03%   |
| 1280x960           | 2         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3550      | 45.31%  |
| 13      | 919       | 11.73%  |
| 14      | 897       | 11.45%  |
| 17      | 686       | 8.76%   |
| 11      | 196       | 2.5%    |
| 12      | 188       | 2.4%    |
| Unknown | 179       | 2.28%   |
| 24      | 174       | 2.22%   |
| 23      | 155       | 1.98%   |
| 27      | 137       | 1.75%   |
| 21      | 130       | 1.66%   |
| 18      | 96        | 1.23%   |
| 10      | 85        | 1.08%   |
| 19      | 70        | 0.89%   |
| 31      | 51        | 0.65%   |
| 34      | 44        | 0.56%   |
| 22      | 40        | 0.51%   |
| 72      | 36        | 0.46%   |
| 16      | 32        | 0.41%   |
| 20      | 25        | 0.32%   |
| 84      | 23        | 0.29%   |
| 32      | 21        | 0.27%   |
| 40      | 17        | 0.22%   |
| 54      | 11        | 0.14%   |
| 25      | 10        | 0.13%   |
| 28      | 7         | 0.09%   |
| 26      | 7         | 0.09%   |
| 8       | 7         | 0.09%   |
| 65      | 5         | 0.06%   |
| 47      | 4         | 0.05%   |
| 74      | 3         | 0.04%   |
| 52      | 3         | 0.04%   |
| 48      | 3         | 0.04%   |
| 29      | 3         | 0.04%   |
| 46      | 2         | 0.03%   |
| 42      | 2         | 0.03%   |
| 41      | 2         | 0.03%   |
| 39      | 2         | 0.03%   |
| 37      | 2         | 0.03%   |
| 33      | 2         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 4886      | 62.71%  |
| 201-300     | 853       | 10.95%  |
| 351-400     | 826       | 10.6%   |
| 501-600     | 450       | 5.78%   |
| 401-500     | 323       | 4.15%   |
| Unknown     | 179       | 2.3%    |
| 601-700     | 79        | 1.01%   |
| 701-800     | 67        | 0.86%   |
| 1501-2000   | 62        | 0.8%    |
| 1001-1500   | 32        | 0.41%   |
| 801-900     | 22        | 0.28%   |
| 101-200     | 7         | 0.09%   |
| 901-1000    | 5         | 0.06%   |
| 1-100       | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 5898      | 82.94%  |
| 16/10   | 865       | 12.16%  |
| Unknown | 148       | 2.08%   |
| 5/4     | 62        | 0.87%   |
| 3/2     | 50        | 0.7%    |
| 21/9    | 45        | 0.63%   |
| 4/3     | 36        | 0.51%   |
| 6/5     | 4         | 0.06%   |
| 32/9    | 2         | 0.03%   |
| 1.96    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3541      | 45.24%  |
| 81-90          | 1519      | 19.41%  |
| 121-130        | 552       | 7.05%   |
| 201-250        | 413       | 5.28%   |
| 71-80          | 292       | 3.73%   |
| 51-60          | 196       | 2.5%    |
| 61-70          | 181       | 2.31%   |
| Unknown        | 179       | 2.29%   |
| 301-350        | 141       | 1.8%    |
| 151-200        | 141       | 1.8%    |
| 351-500        | 124       | 1.58%   |
| 141-150        | 111       | 1.42%   |
| 131-140        | 109       | 1.39%   |
| More than 1000 | 86        | 1.1%    |
| 41-50          | 86        | 1.1%    |
| 251-300        | 60        | 0.77%   |
| 501-1000       | 36        | 0.46%   |
| 91-100         | 31        | 0.4%    |
| 111-120        | 21        | 0.27%   |
| 1-40           | 8         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 3296      | 42.87%  |
| 121-160       | 2366      | 30.77%  |
| 51-100        | 1375      | 17.88%  |
| 161-240       | 251       | 3.26%   |
| Unknown       | 179       | 2.33%   |
| More than 240 | 111       | 1.44%   |
| 1-50          | 111       | 1.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6156      | 81.45%  |
| 2     | 955       | 12.64%  |
| 0     | 369       | 4.88%   |
| 3     | 75        | 0.99%   |
| 4     | 3         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4190      | 33.92%  |
| Intel                             | 3158      | 25.56%  |
| Qualcomm Atheros                  | 2260      | 18.3%   |
| Broadcom                          | 984       | 7.97%   |
| Broadcom Limited                  | 226       | 1.83%   |
| Marvell Technology Group          | 225       | 1.82%   |
| Ralink                            | 184       | 1.49%   |
| Ralink Technology                 | 99        | 0.8%    |
| MediaTek                          | 86        | 0.7%    |
| TP-Link                           | 81        | 0.66%   |
| ASIX Electronics                  | 58        | 0.47%   |
| Samsung Electronics               | 56        | 0.45%   |
| JMicron Technology                | 54        | 0.44%   |
| Dell                              | 54        | 0.44%   |
| Silicon Integrated Systems [SiS]  | 51        | 0.41%   |
| Nvidia                            | 46        | 0.37%   |
| Ericsson Business Mobile Networks | 46        | 0.37%   |
| Huawei Technologies               | 39        | 0.32%   |
| Xiaomi                            | 38        | 0.31%   |
| Sierra Wireless                   | 37        | 0.3%    |
| Hewlett-Packard                   | 37        | 0.3%    |
| DisplayLink                       | 23        | 0.19%   |
| Edimax Technology                 | 20        | 0.16%   |
| Qualcomm                          | 18        | 0.15%   |
| NetGear                           | 18        | 0.15%   |
| Qualcomm Atheros Communications   | 17        | 0.14%   |
| Attansic Technology               | 17        | 0.14%   |
| Motorola PCS                      | 16        | 0.13%   |
| Lenovo                            | 15        | 0.12%   |
| VIA Technologies                  | 14        | 0.11%   |
| ASUSTek Computer                  | 14        | 0.11%   |
| D-Link                            | 12        | 0.1%    |
| ICS Advent                        | 11        | 0.09%   |
| Belkin Components                 | 11        | 0.09%   |
| D-Link System                     | 9         | 0.07%   |
| AMD                               | 8         | 0.06%   |
| Linksys                           | 7         | 0.06%   |
| T & A Mobile Phones               | 6         | 0.05%   |
| Microsoft                         | 6         | 0.05%   |
| Google                            | 6         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2383      | 16.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1082      | 7.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 395       | 2.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 363       | 2.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 357       | 2.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 327       | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 319       | 2.17%   |
| Intel Wireless 7260                                                     | 254       | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 240       | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 225       | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 209       | 1.42%   |
| Intel Wireless 8265 / 8275                                              | 182       | 1.24%   |
| Intel Wireless 7265                                                     | 178       | 1.21%   |
| Intel Wi-Fi 6 AX200                                                     | 174       | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 148       | 1%      |
| Broadcom BCM43142 802.11b/g/n                                           | 146       | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 145       | 0.98%   |
| Intel Wi-Fi 6 AX201                                                     | 142       | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 137       | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 132       | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 130       | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 126       | 0.86%   |
| Intel Wireless 8260                                                     | 125       | 0.85%   |
| Intel Wireless 3165                                                     | 124       | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 120       | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 113       | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 112       | 0.76%   |
| Intel Wireless 3160                                                     | 112       | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 104       | 0.71%   |
| Intel 82577LM Gigabit Network Connection                                | 103       | 0.7%    |
| Intel WiFi Link 5100                                                    | 92        | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 87        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                          | 84        | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 82        | 0.56%   |
| Intel Ethernet Connection I218-LM                                       | 82        | 0.56%   |
| Intel Centrino Advanced-N 6200                                          | 81        | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 81        | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 79        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                                | 75        | 0.51%   |
| Intel Centrino Wireless-N 2230                                          | 73        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2981      | 38.31%  |
| Qualcomm Atheros                      | 1952      | 25.09%  |
| Realtek Semiconductor                 | 1302      | 16.73%  |
| Broadcom                              | 746       | 9.59%   |
| Ralink                                | 184       | 2.36%   |
| Broadcom Limited                      | 145       | 1.86%   |
| Ralink Technology                     | 99        | 1.27%   |
| MediaTek                              | 76        | 0.98%   |
| TP-Link                               | 75        | 0.96%   |
| Sierra Wireless                       | 37        | 0.48%   |
| Dell                                  | 26        | 0.33%   |
| Edimax Technology                     | 20        | 0.26%   |
| Qualcomm Atheros Communications       | 17        | 0.22%   |
| NetGear                               | 17        | 0.22%   |
| ASUSTek Computer                      | 14        | 0.18%   |
| D-Link                                | 11        | 0.14%   |
| Belkin Components                     | 11        | 0.14%   |
| D-Link System                         | 9         | 0.12%   |
| Qualcomm                              | 7         | 0.09%   |
| Hewlett-Packard                       | 7         | 0.09%   |
| Microsoft                             | 5         | 0.06%   |
| Linksys                               | 5         | 0.06%   |
| Micro Star International              | 4         | 0.05%   |
| FIBOCOM                               | 4         | 0.05%   |
| AVM                                   | 4         | 0.05%   |
| ZyDAS                                 | 2         | 0.03%   |
| TRENDnet                              | 2         | 0.03%   |
| Sitecom Europe                        | 2         | 0.03%   |
| Marvell Technology Group              | 2         | 0.03%   |
| Fujitsu Siemens Computers             | 2         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.03%   |
| Xiaomi                                | 1         | 0.01%   |
| Winbond Electronics                   | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.01%   |
| Senao                                 | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Encore Electronics                    | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 395       | 5.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 363       | 4.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 357       | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 327       | 4.17%   |
| Intel Wireless 7260                                                     | 254       | 3.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 240       | 3.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 225       | 2.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 209       | 2.66%   |
| Intel Wireless 8265 / 8275                                              | 182       | 2.32%   |
| Intel Wireless 7265                                                     | 178       | 2.27%   |
| Intel Wi-Fi 6 AX200                                                     | 174       | 2.22%   |
| Broadcom BCM43142 802.11b/g/n                                           | 146       | 1.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 145       | 1.85%   |
| Intel Wi-Fi 6 AX201                                                     | 142       | 1.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 137       | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 132       | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 130       | 1.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 126       | 1.61%   |
| Intel Wireless 8260                                                     | 125       | 1.59%   |
| Intel Wireless 3165                                                     | 124       | 1.58%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 113       | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 112       | 1.43%   |
| Intel Wireless 3160                                                     | 112       | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 104       | 1.33%   |
| Intel WiFi Link 5100                                                    | 92        | 1.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 87        | 1.11%   |
| Intel Centrino Ultimate-N 6300                                          | 84        | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 82        | 1.04%   |
| Intel Centrino Advanced-N 6200                                          | 81        | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 81        | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 79        | 1.01%   |
| Intel Centrino Wireless-N 2230                                          | 73        | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 72        | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 68        | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 68        | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 67        | 0.85%   |
| Intel Centrino Advanced-N 6235                                          | 66        | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 60        | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 60        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 59        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3710      | 55.76%  |
| Intel                                  | 1172      | 17.62%  |
| Qualcomm Atheros                       | 581       | 8.73%   |
| Broadcom                               | 378       | 5.68%   |
| Marvell Technology Group               | 223       | 3.35%   |
| Broadcom Limited                       | 88        | 1.32%   |
| ASIX Electronics                       | 58        | 0.87%   |
| Samsung Electronics                    | 54        | 0.81%   |
| JMicron Technology                     | 54        | 0.81%   |
| Silicon Integrated Systems [SiS]       | 49        | 0.74%   |
| Nvidia                                 | 45        | 0.68%   |
| Xiaomi                                 | 37        | 0.56%   |
| Huawei Technologies                    | 25        | 0.38%   |
| DisplayLink                            | 23        | 0.35%   |
| Attansic Technology                    | 17        | 0.26%   |
| Lenovo                                 | 15        | 0.23%   |
| VIA Technologies                       | 14        | 0.21%   |
| Motorola PCS                           | 11        | 0.17%   |
| ICS Advent                             | 11        | 0.17%   |
| Qualcomm                               | 10        | 0.15%   |
| Hewlett-Packard                        | 10        | 0.15%   |
| MediaTek                               | 9         | 0.14%   |
| TP-Link                                | 6         | 0.09%   |
| Google                                 | 6         | 0.09%   |
| HMD Global                             | 5         | 0.08%   |
| Apple                                  | 5         | 0.08%   |
| T & A Mobile Phones                    | 4         | 0.06%   |
| OPPO Electronics                       | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| OnePlus                                | 2         | 0.03%   |
| MosChip Semiconductor                  | 2         | 0.03%   |
| Microchip Technology                   | 2         | 0.03%   |
| Linksys                                | 2         | 0.03%   |
| Vimtron Electronics                    | 1         | 0.02%   |
| ULi Electronics                        | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| Promise Technology                     | 1         | 0.02%   |
| NTmore                                 | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2383      | 35.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1082      | 16.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 319       | 4.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 148       | 2.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 120       | 1.79%   |
| Intel 82577LM Gigabit Network Connection                                       | 103       | 1.54%   |
| Intel Ethernet Connection I218-LM                                              | 82        | 1.23%   |
| Intel 82567LM Gigabit Network Connection                                       | 75        | 1.12%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 71        | 1.06%   |
| Intel Ethernet Connection I217-LM                                              | 71        | 1.06%   |
| Intel Ethernet Connection I219-LM                                              | 66        | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 61        | 0.91%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 60        | 0.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 59        | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                                          | 57        | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 55        | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 53        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                          | 48        | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 48        | 0.72%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 46        | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 45        | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 45        | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 43        | 0.64%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 41        | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 38        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 36        | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 36        | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 35        | 0.52%   |
| Intel 82579V Gigabit Network Connection                                        | 34        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 33        | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 30        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                                           | 30        | 0.45%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 29        | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 28        | 0.42%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 28        | 0.42%   |
| Intel Ethernet Connection I219-V                                               | 28        | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 27        | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 27        | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 26        | 0.39%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 26        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7300      | 52.49%  |
| Ethernet | 6414      | 46.12%  |
| Modem    | 180       | 1.29%   |
| Unknown  | 13        | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6034      | 77.09%  |
| Ethernet | 1790      | 22.87%  |
| Unknown  | 2         | 0.03%   |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5958      | 79.91%  |
| 1     | 1308      | 17.54%  |
| 0     | 150       | 2.01%   |
| 3     | 40        | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6211      | 81.78%  |
| Yes  | 1384      | 18.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1952      | 37.26%  |
| Qualcomm Atheros Communications | 662       | 12.64%  |
| Realtek Semiconductor           | 657       | 12.54%  |
| Broadcom                        | 395       | 7.54%   |
| Lite-On Technology              | 272       | 5.19%   |
| IMC Networks                    | 243       | 4.64%   |
| Foxconn / Hon Hai               | 188       | 3.59%   |
| Apple                           | 150       | 2.86%   |
| Dell                            | 128       | 2.44%   |
| Hewlett-Packard                 | 111       | 2.12%   |
| Cambridge Silicon Radio         | 110       | 2.1%    |
| Ralink                          | 87        | 1.66%   |
| Toshiba                         | 67        | 1.28%   |
| ASUSTek Computer                | 35        | 0.67%   |
| Foxconn International           | 30        | 0.57%   |
| Alps Electric                   | 30        | 0.57%   |
| Ralink Technology               | 29        | 0.55%   |
| Realtek                         | 23        | 0.44%   |
| Chicony Electronics             | 11        | 0.21%   |
| Qcom                            | 10        | 0.19%   |
| Unknown                         | 8         | 0.15%   |
| Taiyo Yuden                     | 8         | 0.15%   |
| MediaTek                        | 8         | 0.15%   |
| Askey Computer                  | 7         | 0.13%   |
| Edimax Technology               | 4         | 0.08%   |
| Micro Star International        | 3         | 0.06%   |
| Fujitsu                         | 3         | 0.06%   |
| Dynex                           | 3         | 0.06%   |
| Opticis                         | 2         | 0.04%   |
| TP-Link                         | 1         | 0.02%   |
| Primax Electronics              | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 938       | 17.9%   |
| Realtek Bluetooth Radio                             | 343       | 6.54%   |
| Qualcomm Atheros  Bluetooth Device                  | 304       | 5.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 285       | 5.44%   |
| Intel AX201 Bluetooth                               | 257       | 4.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 227       | 4.33%   |
| Intel AX200 Bluetooth                               | 169       | 3.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 121       | 2.31%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 113       | 2.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 112       | 2.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 110       | 2.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 108       | 2.06%   |
| Ralink RT3290 Bluetooth                             | 87        | 1.66%   |
| IMC Networks Bluetooth Device                       | 75        | 1.43%   |
| Apple Bluetooth Host Controller                     | 73        | 1.39%   |
| IMC Networks Bluetooth Radio                        | 69        | 1.32%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 66        | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 65        | 1.24%   |
| HP Broadcom 2070 Bluetooth Combo                    | 59        | 1.13%   |
| Lite-On Atheros AR3012 Bluetooth                    | 53        | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                    | 53        | 1.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 50        | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                         | 50        | 0.95%   |
| Lite-On Bluetooth Device                            | 49        | 0.93%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 47        | 0.9%    |
| Apple Bluetooth USB Host Controller                 | 47        | 0.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 43        | 0.82%   |
| Dell DW375 Bluetooth Module                         | 42        | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 40        | 0.76%   |
| Broadcom BCM2045 Bluetooth                          | 35        | 0.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 34        | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 33        | 0.63%   |
| Foxconn International BCM43142A0 Bluetooth module   | 30        | 0.57%   |
| IMC Networks Wireless_Device                        | 29        | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 29        | 0.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 28        | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 27        | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 27        | 0.52%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 27        | 0.52%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 26        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5972      | 69.45%  |
| AMD                                          | 1441      | 16.76%  |
| Nvidia                                       | 741       | 8.62%   |
| C-Media Electronics                          | 66        | 0.77%   |
| Silicon Integrated Systems [SiS]             | 60        | 0.7%    |
| Logitech                                     | 36        | 0.42%   |
| Texas Instruments                            | 18        | 0.21%   |
| JMTek                                        | 18        | 0.21%   |
| Realtek Semiconductor                        | 17        | 0.2%    |
| Plantronics                                  | 17        | 0.2%    |
| GN Netcom                                    | 17        | 0.2%    |
| VIA Technologies                             | 16        | 0.19%   |
| Lenovo                                       | 15        | 0.17%   |
| Generalplus Technology                       | 13        | 0.15%   |
| Kingston Technology                          | 12        | 0.14%   |
| Apple                                        | 12        | 0.14%   |
| Creative Technology                          | 11        | 0.13%   |
| SteelSeries ApS                              | 9         | 0.1%    |
| Hewlett-Packard                              | 8         | 0.09%   |
| Microsoft                                    | 6         | 0.07%   |
| Corsair                                      | 5         | 0.06%   |
| Tenx Technology                              | 4         | 0.05%   |
| Sony                                         | 4         | 0.05%   |
| Razer USA                                    | 4         | 0.05%   |
| Samson Technologies                          | 3         | 0.03%   |
| PreSonus Audio Electronics                   | 3         | 0.03%   |
| OPPO Electronics                             | 3         | 0.03%   |
| Jieli Technology                             | 3         | 0.03%   |
| Focusrite-Novation                           | 3         | 0.03%   |
| Dell                                         | 3         | 0.03%   |
| BEHRINGER International                      | 3         | 0.03%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.02%   |
| Trust                                        | 2         | 0.02%   |
| Sennheiser Communications                    | 2         | 0.02%   |
| RODE Microphones                             | 2         | 0.02%   |
| QinHeng Electronics                          | 2         | 0.02%   |
| KORG                                         | 2         | 0.02%   |
| Cambridge Silicon Radio                      | 2         | 0.02%   |
| Bose                                         | 2         | 0.02%   |
| AKAI                                         | 2         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 822       | 7.83%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 709       | 6.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 566       | 5.39%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 490       | 4.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 456       | 4.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 441       | 4.2%    |
| Intel 8 Series HD Audio Controller                                                                | 375       | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 372       | 3.54%   |
| AMD FCH Azalia Controller                                                                         | 314       | 2.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 269       | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 253       | 2.41%   |
| Intel Broadwell-U Audio Controller                                                                | 245       | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 243       | 2.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 242       | 2.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 220       | 2.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 210       | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 208       | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 208       | 1.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 197       | 1.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 180       | 1.71%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 179       | 1.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 177       | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 175       | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 152       | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 149       | 1.42%   |
| AMD High Definition Audio Controller                                                              | 138       | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 130       | 1.24%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 108       | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 93        | 0.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 87        | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 82        | 0.78%   |
| Intel Comet Lake PCH cAVS                                                                         | 75        | 0.71%   |
| Intel CM238 HD Audio Controller                                                                   | 74        | 0.7%    |
| AMD Wrestler HDMI Audio                                                                           | 74        | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 70        | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 69        | 0.66%   |
| AMD Trinity HDMI Audio Controller                                                                 | 64        | 0.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 64        | 0.61%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 56        | 0.53%   |
| Nvidia High Definition Audio Controller                                                           | 56        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1058      | 27.26%  |
| SK hynix            | 870       | 22.42%  |
| Micron Technology   | 443       | 11.41%  |
| Kingston            | 339       | 8.73%   |
| Unknown             | 278       | 7.16%   |
| Crucial             | 158       | 4.07%   |
| Elpida              | 106       | 2.73%   |
| Ramaxel Technology  | 105       | 2.71%   |
| A-DATA Technology   | 80        | 2.06%   |
| Smart               | 64        | 1.65%   |
| Nanya Technology    | 59        | 1.52%   |
| Corsair             | 54        | 1.39%   |
| Unknown (ABCD)      | 49        | 1.26%   |
| Teikon              | 17        | 0.44%   |
| G.Skill             | 17        | 0.44%   |
| Transcend           | 14        | 0.36%   |
| ASint Technology    | 12        | 0.31%   |
| Apacer              | 11        | 0.28%   |
| Team                | 9         | 0.23%   |
| GOODRAM             | 9         | 0.23%   |
| Unknown             | 9         | 0.23%   |
| Smart Brazil        | 8         | 0.21%   |
| Patriot             | 7         | 0.18%   |
| Avant               | 7         | 0.18%   |
| Goldkey             | 6         | 0.15%   |
| Qimonda             | 5         | 0.13%   |
| PNY                 | 5         | 0.13%   |
| Kllisre             | 5         | 0.13%   |
| AMD                 | 5         | 0.13%   |
| SHARETRONIC         | 4         | 0.1%    |
| Sesame              | 4         | 0.1%    |
| Multilaser          | 4         | 0.1%    |
| High Bridge         | 4         | 0.1%    |
| Toshiba             | 3         | 0.08%   |
| Timetec             | 3         | 0.08%   |
| CSX                 | 3         | 0.08%   |
| 48spaces            | 3         | 0.08%   |
| Unknown (08AE)      | 2         | 0.05%   |
| Silicon Power       | 2         | 0.05%   |
| Qumo                | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 59        | 1.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 53        | 1.28%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 52        | 1.26%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 50        | 1.21%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 47        | 1.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 46        | 1.11%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 42        | 1.01%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 41        | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 40        | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 38        | 0.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 38        | 0.92%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 35        | 0.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 35        | 0.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 0.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 31        | 0.75%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.72%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 30        | 0.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 29        | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 28        | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 27        | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 0.63%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 25        | 0.6%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 25        | 0.6%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 23        | 0.56%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 23        | 0.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 22        | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 22        | 0.53%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 0.53%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 21        | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 20        | 0.48%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.48%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 20        | 0.48%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 0.48%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.48%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.46%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.46%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 17        | 0.41%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 17        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1442      | 44.17%  |
| DDR4    | 1288      | 39.45%  |
| LPDDR4  | 153       | 4.69%   |
| DDR2    | 152       | 4.66%   |
| SDRAM   | 86        | 2.63%   |
| LPDDR3  | 73        | 2.24%   |
| Unknown | 22        | 0.67%   |
| DDR     | 20        | 0.61%   |
| DRAM    | 16        | 0.49%   |
| DDR5    | 6         | 0.18%   |
| LPDDR5  | 5         | 0.15%   |
| RAM     | 2         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2982      | 91.92%  |
| Row Of Chips | 206       | 6.35%   |
| DIMM         | 25        | 0.77%   |
| Chip         | 17        | 0.52%   |
| Unknown      | 14        | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 1381      | 38.73%  |
| 8192  | 1165      | 32.67%  |
| 2048  | 542       | 15.2%   |
| 16384 | 308       | 8.64%   |
| 1024  | 124       | 3.48%   |
| 32768 | 32        | 0.9%    |
| 512   | 11        | 0.31%   |
| 256   | 2         | 0.06%   |
| 1536  | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 995       | 27.95%  |
| 2667    | 628       | 17.64%  |
| 3200    | 446       | 12.53%  |
| 2400    | 283       | 7.95%   |
| 1334    | 243       | 6.83%   |
| 1333    | 186       | 5.22%   |
| 2133    | 144       | 4.04%   |
| Unknown | 87        | 2.44%   |
| 667     | 80        | 2.25%   |
| 1067    | 67        | 1.88%   |
| 3266    | 59        | 1.66%   |
| 4267    | 52        | 1.46%   |
| 4199    | 47        | 1.32%   |
| 800     | 40        | 1.12%   |
| 1066    | 37        | 1.04%   |
| 1867    | 32        | 0.9%    |
| 2048    | 27        | 0.76%   |
| 975     | 16        | 0.45%   |
| 8400    | 15        | 0.42%   |
| 533     | 14        | 0.39%   |
| 4800    | 11        | 0.31%   |
| 4266    | 8         | 0.22%   |
| 6400    | 5         | 0.14%   |
| 333     | 5         | 0.14%   |
| 3000    | 4         | 0.11%   |
| 1639    | 4         | 0.11%   |
| 1200    | 4         | 0.11%   |
| 933     | 4         | 0.11%   |
| 400     | 4         | 0.11%   |
| 1866    | 3         | 0.08%   |
| 2933    | 2         | 0.06%   |
| 1776    | 2         | 0.06%   |
| 3733    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 2267    | 1         | 0.03%   |
| 1777    | 1         | 0.03%   |
| 1400    | 1         | 0.03%   |
| 266     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 34        | 34%     |
| Canon                 | 23        | 23%     |
| Brother Industries    | 16        | 16%     |
| Samsung Electronics   | 10        | 10%     |
| Seiko Epson           | 7         | 7%      |
| Kyocera               | 4         | 4%      |
| Prolific Technology   | 2         | 2%      |
| STMicroelectronics    | 1         | 1%      |
| QinHeng Electronics   | 1         | 1%      |
| Lexmark International | 1         | 1%      |
| Dell                  | 1         | 1%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 4         | 3.92%   |
| Canon PIXMA MG2500 Series                                 | 4         | 3.92%   |
| Seiko Epson L805 Series                                   | 2         | 1.96%   |
| Seiko Epson ET-2710 Series                                | 2         | 1.96%   |
| Samsung M267x 287x Series                                 | 2         | 1.96%   |
| Prolific PL2305 Parallel Port                             | 2         | 1.96%   |
| Kyocera Mita FS-820                                       | 2         | 1.96%   |
| HP OfficeJet 3830 series                                  | 2         | 1.96%   |
| HP LaserJet P2035                                         | 2         | 1.96%   |
| HP Ink Tank Wireless 410 series                           | 2         | 1.96%   |
| HP ENVY 4520 series                                       | 2         | 1.96%   |
| HP Deskjet 2540 series                                    | 2         | 1.96%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.96%   |
| Canon PIXMA MX920 Series                                  | 2         | 1.96%   |
| Canon LBP6030w/6018w                                      | 2         | 1.96%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.98%   |
| Seiko Epson WF-3520 Series                                | 1         | 0.98%   |
| Seiko Epson WF-2830 Series                                | 1         | 0.98%   |
| Seiko Epson L395 Series                                   | 1         | 0.98%   |
| Samsung SCX-6545 Series                                   | 1         | 0.98%   |
| Samsung ML-2510 Series                                    | 1         | 0.98%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 0.98%   |
| Samsung ML-1660 Series                                    | 1         | 0.98%   |
| Samsung M2070 Series                                      | 1         | 0.98%   |
| Samsung M2020 Series                                      | 1         | 0.98%   |
| Samsung CLP-300 Series                                    | 1         | 0.98%   |
| Samsung C3060 Series                                      | 1         | 0.98%   |
| QinHeng CH340S                                            | 1         | 0.98%   |
| Lexmark International InkJet Color Printer                | 1         | 0.98%   |
| Kyocera FS-1030D printer                                  | 1         | 0.98%   |
| Kyocera ECOSYS M5526cdw                                   | 1         | 0.98%   |
| HP OfficeJet Pro 8030 series                              | 1         | 0.98%   |
| HP LaserJet Professional P 1102w                          | 1         | 0.98%   |
| HP LaserJet Pro M404-M405                                 | 1         | 0.98%   |
| HP LaserJet P1505n                                        | 1         | 0.98%   |
| HP LaserJet CP 1025                                       | 1         | 0.98%   |
| HP LaserJet 1020                                          | 1         | 0.98%   |
| HP LaserJet 1018                                          | 1         | 0.98%   |
| HP ENVY 5000 series                                       | 1         | 0.98%   |
| HP DeskJet F4100 Printer series                           | 1         | 0.98%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Canon             | 12        | 66.67%  |
| Hewlett-Packard   | 3         | 16.67%  |
| Seiko Epson       | 1         | 5.56%   |
| Canon Electronics | 1         | 5.56%   |
| AGFA-Gevaert NV   | 1         | 5.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 5.26%   |
| HP ScanJet 5300c/5370c                      | 1         | 5.26%   |
| HP ScanJet 2400c                            | 1         | 5.26%   |
| HP ScanJet 2200c                            | 1         | 5.26%   |
| Canon P-150 Scanner                         | 1         | 5.26%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 5.26%   |
| Canon CanoScan N650U/N656U                  | 1         | 5.26%   |
| Canon CanoScan LiDE 700F                    | 1         | 5.26%   |
| Canon CanoScan LiDE 600F                    | 1         | 5.26%   |
| Canon CanoScan LiDE 500F                    | 1         | 5.26%   |
| Canon CanoScan LiDE 220                     | 1         | 5.26%   |
| Canon CanoScan LiDE 120                     | 1         | 5.26%   |
| Canon CanoScan LiDE 110                     | 1         | 5.26%   |
| Canon CanoScan LiDE 100                     | 1         | 5.26%   |
| Canon CanoScan 4400F                        | 1         | 5.26%   |
| Canon CanoScan 4200F                        | 1         | 5.26%   |
| Canon CanoScan 3200F                        | 1         | 5.26%   |
| Canon CanoScan 1220U                        | 1         | 5.26%   |
| AGFA-Gevaert NV SnapScan 1212U (?)          | 1         | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1620      | 25.38%  |
| IMC Networks                           | 560       | 8.77%   |
| Realtek Semiconductor                  | 506       | 7.93%   |
| Microdia                               | 490       | 7.68%   |
| Acer                                   | 479       | 7.5%    |
| Sunplus Innovation Technology          | 394       | 6.17%   |
| Suyin                                  | 336       | 5.26%   |
| Quanta                                 | 324       | 5.08%   |
| Cheng Uei Precision Industry (Foxlink) | 324       | 5.08%   |
| Silicon Motion                         | 174       | 2.73%   |
| Syntek                                 | 172       | 2.69%   |
| Lite-On Technology                     | 129       | 2.02%   |
| Alcor Micro                            | 111       | 1.74%   |
| Apple                                  | 110       | 1.72%   |
| Ricoh                                  | 84        | 1.32%   |
| Logitech                               | 62        | 0.97%   |
| Luxvisions Innotech Limited            | 59        | 0.92%   |
| Z-Star Microelectronics                | 45        | 0.7%    |
| Importek                               | 44        | 0.69%   |
| Samsung Electronics                    | 43        | 0.67%   |
| Lenovo                                 | 35        | 0.55%   |
| ALi                                    | 31        | 0.49%   |
| Primax Electronics                     | 30        | 0.47%   |
| OmniVision Technologies                | 17        | 0.27%   |
| DigiTech                               | 17        | 0.27%   |
| Sonix Technology                       | 15        | 0.23%   |
| icSpring                               | 14        | 0.22%   |
| SunplusIT                              | 11        | 0.17%   |
| GEMBIRD                                | 9         | 0.14%   |
| Y Media                                | 8         | 0.13%   |
| Microsoft                              | 8         | 0.13%   |
| Generalplus Technology                 | 8         | 0.13%   |
| Sunplus Technology                     | 7         | 0.11%   |
| Jieli Technology                       | 6         | 0.09%   |
| Intel                                  | 6         | 0.09%   |
| Unknown                                | 5         | 0.08%   |
| LG Electronics                         | 5         | 0.08%   |
| Image Processor                        | 5         | 0.08%   |
| Trust                                  | 4         | 0.06%   |
| Creative Technology                    | 4         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 219       | 3.42%   |
| Chicony HD WebCam                                | 157       | 2.45%   |
| Microdia Integrated_Webcam_HD                    | 149       | 2.33%   |
| Realtek Integrated_Webcam_HD                     | 117       | 1.83%   |
| Sunplus Integrated_Webcam_HD                     | 115       | 1.8%    |
| IMC Networks USB2.0 HD UVC WebCam                | 114       | 1.78%   |
| IMC Networks Integrated Camera                   | 106       | 1.66%   |
| Acer Integrated Camera                           | 85        | 1.33%   |
| Chicony USB 2.0 Camera                           | 73        | 1.14%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 69        | 1.08%   |
| Acer Lenovo EasyCamera                           | 65        | 1.01%   |
| Chicony USB2.0 HD UVC WebCam                     | 64        | 1%      |
| Microdia Integrated Webcam                       | 60        | 0.94%   |
| Chicony HP Truevision HD                         | 59        | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 58        | 0.91%   |
| Syntek Integrated Camera                         | 55        | 0.86%   |
| Chicony HP Webcam                                | 55        | 0.86%   |
| Chicony HP HD Camera                             | 55        | 0.86%   |
| Sunplus HD WebCam                                | 54        | 0.84%   |
| Chicony Lenovo EasyCamera                        | 54        | 0.84%   |
| Chicony HP Truevision HD camera                  | 53        | 0.83%   |
| Chicony EasyCamera                               | 52        | 0.81%   |
| Realtek USB Camera                               | 49        | 0.77%   |
| Quanta VGA WebCam                                | 49        | 0.77%   |
| Acer BisonCam, NB Pro                            | 49        | 0.77%   |
| Quanta HD User Facing                            | 48        | 0.75%   |
| Syntek Lenovo EasyCamera                         | 47        | 0.73%   |
| Quanta HP TrueVision HD Camera                   | 47        | 0.73%   |
| Lite-On Integrated Camera                        | 45        | 0.7%    |
| Chicony VGA WebCam                               | 44        | 0.69%   |
| Chicony HD User Facing                           | 44        | 0.69%   |
| Apple FaceTime HD Camera                         | 44        | 0.69%   |
| Acer EasyCamera                                  | 44        | 0.69%   |
| Quanta HP Webcam                                 | 43        | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam                    | 43        | 0.67%   |
| Chicony TOSHIBA Web Camera - HD                  | 43        | 0.67%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 42        | 0.66%   |
| Samsung Galaxy series, misc. (MTP mode)          | 41        | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 40        | 0.62%   |
| Realtek Integrated Webcam                        | 39        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 441       | 43.15%  |
| Synaptics                  | 156       | 15.26%  |
| AuthenTec                  | 109       | 10.67%  |
| Upek                       | 95        | 9.3%    |
| Shenzhen Goodix Technology | 82        | 8.02%   |
| Elan Microelectronics      | 58        | 5.68%   |
| LighTuning Technology      | 51        | 4.99%   |
| STMicroelectronics         | 22        | 2.15%   |
| Focal-systems.Corp         | 4         | 0.39%   |
| HOLTEK                     | 3         | 0.29%   |
| Suprema                    | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 97        | 9.49%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 91        | 8.9%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 49        | 4.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 47        | 4.6%    |
| Shenzhen Goodix  Fingerprint Device                                        | 47        | 4.6%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 44        | 4.31%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 43        | 4.21%   |
| Validity Sensors Fingerprint scanner                                       | 35        | 3.42%   |
| Validity Sensors VFS491                                                    | 33        | 3.23%   |
| Unknown                                                                    | 32        | 3.13%   |
| Elan ELAN:Fingerprint                                                      | 31        | 3.03%   |
| AuthenTec AES2810                                                          | 31        | 3.03%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 25        | 2.45%   |
| Elan ELAN:ARM-M4                                                           | 24        | 2.35%   |
| AuthenTec AES1600                                                          | 24        | 2.35%   |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 2.25%   |
| STMicroelectronics Fingerprint Reader                                      | 22        | 2.15%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 22        | 2.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 21        | 2.05%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 1.96%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 19        | 1.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 19        | 1.86%   |
| AuthenTec Fingerprint Sensor                                               | 17        | 1.66%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 1.57%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 16        | 1.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 16        | 1.57%   |
| LighTuning EgisTec_ES603                                                   | 16        | 1.57%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 15        | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 1.27%   |
| LighTuning Fingerprint Reader                                              | 13        | 1.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 1.17%   |
| Synaptics  WBDI                                                            | 12        | 1.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 1.17%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 1.17%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 9         | 0.88%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 8         | 0.78%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.68%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 6         | 0.59%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.39%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 242       | 48.21%  |
| Alcor Micro               | 108       | 21.51%  |
| O2 Micro                  | 56        | 11.16%  |
| Upek                      | 37        | 7.37%   |
| Lenovo                    | 35        | 6.97%   |
| Gemalto (was Gemplus)     | 7         | 1.39%   |
| SCM Microsystems          | 5         | 1%      |
| Realtek Semiconductor     | 3         | 0.6%    |
| OmniKey                   | 2         | 0.4%    |
| NXP Semiconductors        | 1         | 0.2%    |
| In Focus Systems          | 1         | 0.2%    |
| Giesecke & Devrient       | 1         | 0.2%    |
| Clay Logic                | 1         | 0.2%    |
| Cherry                    | 1         | 0.2%    |
| C3PO                      | 1         | 0.2%    |
| Aladdin Knowledge Systems | 1         | 0.2%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 116       | 23.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 106       | 21.12%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 54        | 10.76%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 45        | 8.96%   |
| Broadcom 5880                                                                | 43        | 8.57%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 37        | 7.37%   |
| Lenovo Integrated Smart Card Reader                                          | 35        | 6.97%   |
| Broadcom 58200                                                               | 25        | 4.98%   |
| O2 Micro Oz776 SmartCard Reader                                              | 11        | 2.19%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 5         | 1%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 4         | 0.8%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.6%    |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 0.4%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.4%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.4%    |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.4%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.2%    |
| OmniKey CardMan 4321                                                         | 1         | 0.2%    |
| OmniKey CardMan 1021                                                         | 1         | 0.2%    |
| NXP Semiconductors PR533                                                     | 1         | 0.2%    |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.2%    |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.2%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.2%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.2%    |
| C3PO USB SMART CARD READER                                                   | 1         | 0.2%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.2%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4780      | 62.85%  |
| 1     | 2198      | 28.9%   |
| 2     | 496       | 6.52%   |
| 3     | 85        | 1.12%   |
| 4     | 28        | 0.37%   |
| 5     | 9         | 0.12%   |
| 6     | 7         | 0.09%   |
| 7     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1009      | 28.93%  |
| Graphics card            | 806       | 23.11%  |
| Chipcard                 | 477       | 13.68%  |
| Net/wireless             | 463       | 13.27%  |
| Multimedia controller    | 188       | 5.39%   |
| Bluetooth                | 127       | 3.64%   |
| Storage                  | 92        | 2.64%   |
| Communication controller | 79        | 2.26%   |
| Camera                   | 58        | 1.66%   |
| Sound                    | 54        | 1.55%   |
| Modem                    | 34        | 0.97%   |
| Card reader              | 30        | 0.86%   |
| Net/ethernet             | 25        | 0.72%   |
| Flash memory             | 23        | 0.66%   |
| Network                  | 6         | 0.17%   |
| Storage/ide              | 5         | 0.14%   |
| Unassigned class         | 4         | 0.11%   |
| Tv card                  | 2         | 0.06%   |
| Firewire controller      | 2         | 0.06%   |
| Unclassified device      | 1         | 0.03%   |
| Storage/raid             | 1         | 0.03%   |
| Storage/nvme             | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

