Linux in Belgium - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Belgium.

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

Total: 1526

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Medion        | Akoya THE TOUCH 10          | [d45603bb4e](https://linux-hardware.org/?probe=d45603bb4e) | Aug 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [5e64d2b59e](https://linux-hardware.org/?probe=5e64d2b59e) | Aug 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [db2732f0e8](https://linux-hardware.org/?probe=db2732f0e8) | Aug 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [deeafc23f9](https://linux-hardware.org/?probe=deeafc23f9) | Aug 03, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [8da287a76b](https://linux-hardware.org/?probe=8da287a76b) | Aug 01, 2023 |
| HP            | 620                         | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [c74f4bde19](https://linux-hardware.org/?probe=c74f4bde19) | Aug 01, 2023 |
| Valve         | Jupiter                     | [6eb487950f](https://linux-hardware.org/?probe=6eb487950f) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [93d193bdbc](https://linux-hardware.org/?probe=93d193bdbc) | Aug 01, 2023 |
| Lenovo        | WEI6 15 ITL 82F2            | [d30f44ebbb](https://linux-hardware.org/?probe=d30f44ebbb) | Jul 30, 2023 |
| HP            | 530                         | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| ASUSTek       | K50IJ                       | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Apple         | MacBookPro10,1              | [c3ec46f79e](https://linux-hardware.org/?probe=c3ec46f79e) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [e2cf7ed35f](https://linux-hardware.org/?probe=e2cf7ed35f) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7843df6b43](https://linux-hardware.org/?probe=7843df6b43) | Jul 19, 2023 |
| ASUSTek       | X756UQ                      | [be24f941c7](https://linux-hardware.org/?probe=be24f941c7) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | [f0f2c5a6a7](https://linux-hardware.org/?probe=f0f2c5a6a7) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | [6070a533c5](https://linux-hardware.org/?probe=6070a533c5) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [0d54b47098](https://linux-hardware.org/?probe=0d54b47098) | Jul 12, 2023 |
| HP            | EliteBook 840 G5            | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | [8f40997f5f](https://linux-hardware.org/?probe=8f40997f5f) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | [7d19e6a8f5](https://linux-hardware.org/?probe=7d19e6a8f5) | Jul 10, 2023 |
| Dell          | Precision M4800             | [ef29f43a6f](https://linux-hardware.org/?probe=ef29f43a6f) | Jul 09, 2023 |
| HP            | 620                         | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [b4d926a4bc](https://linux-hardware.org/?probe=b4d926a4bc) | Jul 08, 2023 |
| Dell          | Latitude 3380               | [b4403e7b15](https://linux-hardware.org/?probe=b4403e7b15) | Jul 07, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [31d5e724ba](https://linux-hardware.org/?probe=31d5e724ba) | Jul 07, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [84b5d3ce3c](https://linux-hardware.org/?probe=84b5d3ce3c) | Jul 06, 2023 |
| Dell          | Precision 7520              | [1bffd04c84](https://linux-hardware.org/?probe=1bffd04c84) | Jul 05, 2023 |
| Apple         | MacBook8,1                  | [d27490cbe0](https://linux-hardware.org/?probe=d27490cbe0) | Jul 04, 2023 |
| HP            | EliteBook 820 G1            | [5b1b409a2f](https://linux-hardware.org/?probe=5b1b409a2f) | Jul 04, 2023 |
| Apple         | MacBook8,1                  | [06ac15dcca](https://linux-hardware.org/?probe=06ac15dcca) | Jul 04, 2023 |
| Dell          | Precision 5560              | [5f8f3c917f](https://linux-hardware.org/?probe=5f8f3c917f) | Jul 04, 2023 |
| ASUSTek       | X556UQK                     | [b4560fc1c1](https://linux-hardware.org/?probe=b4560fc1c1) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [6df0ae15e1](https://linux-hardware.org/?probe=6df0ae15e1) | Jul 01, 2023 |
| Acer          | Aspire 7715Z                | [b288a09d6e](https://linux-hardware.org/?probe=b288a09d6e) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| HP            | EliteBook 8460p             | [d4a008aefb](https://linux-hardware.org/?probe=d4a008aefb) | Jun 30, 2023 |
| Dell          | Latitude 5440               | [7868400967](https://linux-hardware.org/?probe=7868400967) | Jun 30, 2023 |
| VALE          | Notebook Slim S132          | [3e381e10f7](https://linux-hardware.org/?probe=3e381e10f7) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [39f7adb927](https://linux-hardware.org/?probe=39f7adb927) | Jun 30, 2023 |
| MSI           | Modern 14 A10M              | [fcc6786de6](https://linux-hardware.org/?probe=fcc6786de6) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [99efa1a1c5](https://linux-hardware.org/?probe=99efa1a1c5) | Jun 24, 2023 |
| Acer          | Aspire A515-55              | [bf6de06fb9](https://linux-hardware.org/?probe=bf6de06fb9) | Jun 23, 2023 |
| Emdoor        | AG958                       | [3574f89b15](https://linux-hardware.org/?probe=3574f89b15) | Jun 21, 2023 |
| Acer          | Aspire F5-771G              | [034d235f5c](https://linux-hardware.org/?probe=034d235f5c) | Jun 19, 2023 |
| ASUSTek       | X555LJ                      | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| ASUSTek       | X556UQK                     | [50c975ae08](https://linux-hardware.org/?probe=50c975ae08) | Jun 13, 2023 |
| Emdoor        | AG958                       | [1688cc07b6](https://linux-hardware.org/?probe=1688cc07b6) | Jun 11, 2023 |
| ASUSTek       | X540SAA                     | [ea61fdd09a](https://linux-hardware.org/?probe=ea61fdd09a) | Jun 11, 2023 |
| MSI           | Modern 14 A10M              | [7d5fc6a209](https://linux-hardware.org/?probe=7d5fc6a209) | Jun 11, 2023 |
| Notebook      | NS50_70MU                   | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| Medion        | Akoya E7226                 | [b46a96183b](https://linux-hardware.org/?probe=b46a96183b) | Jun 10, 2023 |
| Dell          | Latitude 5530               | [a302ecd3cd](https://linux-hardware.org/?probe=a302ecd3cd) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| HP            | Pavilion Notebook           | [3fb05bfb0b](https://linux-hardware.org/?probe=3fb05bfb0b) | May 31, 2023 |
| Dell          | Latitude 5510               | [78bd1ae0e0](https://linux-hardware.org/?probe=78bd1ae0e0) | May 31, 2023 |
| Dell          | Latitude 7390               | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S6P801    | [8ec80f5e43](https://linux-hardware.org/?probe=8ec80f5e43) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [1aa973f6bc](https://linux-hardware.org/?probe=1aa973f6bc) | May 28, 2023 |
| Apple         | MacBookPro14,3              | [fd8a08639d](https://linux-hardware.org/?probe=fd8a08639d) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Lenovo        | V130-15IGM 81HL             | [76a357994a](https://linux-hardware.org/?probe=76a357994a) | May 27, 2023 |
| Dell          | Latitude 7390               | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| Lenovo        | V130-15IGM 81HL             | [5a4cf4d2e3](https://linux-hardware.org/?probe=5a4cf4d2e3) | May 23, 2023 |
| Acer          | Aspire E5-771G              | [0dadbeca5b](https://linux-hardware.org/?probe=0dadbeca5b) | May 19, 2023 |
| Valve         | Jupiter                     | [0de060a93f](https://linux-hardware.org/?probe=0de060a93f) | May 18, 2023 |
| MSI           | GS70 2PC Stealth            | [254f42a469](https://linux-hardware.org/?probe=254f42a469) | May 18, 2023 |
| HP            | 620                         | [6b688ce696](https://linux-hardware.org/?probe=6b688ce696) | May 17, 2023 |
| HP            | Pavilion dv6                | [1b931dc36f](https://linux-hardware.org/?probe=1b931dc36f) | May 17, 2023 |
| Emdoor        | AG958                       | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HP            | EliteBook 8470p             | [f97e4e7fc1](https://linux-hardware.org/?probe=f97e4e7fc1) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| ASUSTek       | UX410UAK                    | [d68a2bc7c0](https://linux-hardware.org/?probe=d68a2bc7c0) | May 10, 2023 |
| MSI           | Katana 17 B12UCXK           | [15b9d97c10](https://linux-hardware.org/?probe=15b9d97c10) | May 09, 2023 |
| HP            | EliteBook 8740w             | [29d129229b](https://linux-hardware.org/?probe=29d129229b) | May 08, 2023 |
| HP            | Laptop 17-cn2xxx            | [ddf0cb8a28](https://linux-hardware.org/?probe=ddf0cb8a28) | May 08, 2023 |
| Dell          | Latitude 7390               | [dc5c96e431](https://linux-hardware.org/?probe=dc5c96e431) | May 08, 2023 |
| MSI           | CR61 3M                     | [f41852fa6e](https://linux-hardware.org/?probe=f41852fa6e) | May 07, 2023 |
| MSI           | CR61 3M                     | [7b5d49d859](https://linux-hardware.org/?probe=7b5d49d859) | May 07, 2023 |
| MSI           | GS70 2PC Stealth            | [370f9304b6](https://linux-hardware.org/?probe=370f9304b6) | May 07, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [b0464a0b99](https://linux-hardware.org/?probe=b0464a0b99) | May 06, 2023 |
| Notebook      | NS5x_NS7xPU                 | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [7bb2ae638b](https://linux-hardware.org/?probe=7bb2ae638b) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [bd0458e8a9](https://linux-hardware.org/?probe=bd0458e8a9) | May 01, 2023 |
| Medion        | P6630                       | [93abad41dd](https://linux-hardware.org/?probe=93abad41dd) | Apr 30, 2023 |
| Dell          | Latitude 5521               | [1629b4efc4](https://linux-hardware.org/?probe=1629b4efc4) | Apr 30, 2023 |
| Lenovo        | V130-15IGM 81HL             | [ff24454021](https://linux-hardware.org/?probe=ff24454021) | Apr 29, 2023 |
| Lenovo        | V130-15IGM 81HL             | [9081fc703d](https://linux-hardware.org/?probe=9081fc703d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S56G00    | [8da21e9a17](https://linux-hardware.org/?probe=8da21e9a17) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| Dell          | Latitude E6440              | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| Acer          | Aspire E5-576G              | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | [2e542c241d](https://linux-hardware.org/?probe=2e542c241d) | Apr 25, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Emdoor        | AG958                       | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| Acer          | Nitro AN515-58              | [60251e08f5](https://linux-hardware.org/?probe=60251e08f5) | Apr 22, 2023 |
| Dell          | Latitude E6330              | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | [d342e4d24c](https://linux-hardware.org/?probe=d342e4d24c) | Apr 22, 2023 |
| Emdoor        | AG958                       | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| HP            | Laptop 17-cn2xxx            | [5b77cc21f4](https://linux-hardware.org/?probe=5b77cc21f4) | Apr 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [efdcb6b99e](https://linux-hardware.org/?probe=efdcb6b99e) | Apr 18, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [38aeb226af](https://linux-hardware.org/?probe=38aeb226af) | Apr 17, 2023 |
| Dell          | XPS 15 9500                 | [1a55ffc593](https://linux-hardware.org/?probe=1a55ffc593) | Apr 17, 2023 |
| Dell          | Latitude 5420               | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [f44bbda528](https://linux-hardware.org/?probe=f44bbda528) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | [b87471108a](https://linux-hardware.org/?probe=b87471108a) | Apr 14, 2023 |
| Lenovo        | ThinkPad X250 20CLS29J05    | [60c50f0a10](https://linux-hardware.org/?probe=60c50f0a10) | Apr 13, 2023 |
| MSI           | Vector GP76 12UHSO          | [6037aee790](https://linux-hardware.org/?probe=6037aee790) | Apr 11, 2023 |
| Sony          | SVE1713A1EW                 | [402fae93d5](https://linux-hardware.org/?probe=402fae93d5) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b220308aa1](https://linux-hardware.org/?probe=b220308aa1) | Apr 06, 2023 |
| HP            | 620                         | [ad46cdbb0d](https://linux-hardware.org/?probe=ad46cdbb0d) | Apr 06, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | [d9d2e73619](https://linux-hardware.org/?probe=d9d2e73619) | Apr 05, 2023 |
| Dell          | Vostro 15 3515              | [95a98c59b1](https://linux-hardware.org/?probe=95a98c59b1) | Apr 03, 2023 |
| Clevo         | P170HMx                     | [c963b350fc](https://linux-hardware.org/?probe=c963b350fc) | Apr 03, 2023 |
| AZW           | Speed S                     | [52292a4968](https://linux-hardware.org/?probe=52292a4968) | Apr 02, 2023 |
| HP            | Pavilion g7                 | [7820d2ca67](https://linux-hardware.org/?probe=7820d2ca67) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| HP            | Compaq 6730b (GB987ET#UU... | [6c6ceb9bc3](https://linux-hardware.org/?probe=6c6ceb9bc3) | Mar 31, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [c73c5374a4](https://linux-hardware.org/?probe=c73c5374a4) | Mar 30, 2023 |
| Medion        | P8614                       | [a66fe7042e](https://linux-hardware.org/?probe=a66fe7042e) | Mar 29, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| MSI           | GT70                        | [8b00b28b12](https://linux-hardware.org/?probe=8b00b28b12) | Mar 26, 2023 |
| Medion        | P7624                       | [fe5c568f41](https://linux-hardware.org/?probe=fe5c568f41) | Mar 26, 2023 |
| Medion        | P7624                       | [778f5948f1](https://linux-hardware.org/?probe=778f5948f1) | Mar 26, 2023 |
| Dell          | Latitude E6330              | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Alienware     | m17 R3                      | [6c62c223ed](https://linux-hardware.org/?probe=6c62c223ed) | Mar 21, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [7622701d31](https://linux-hardware.org/?probe=7622701d31) | Mar 21, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| HP            | Pavilion g7                 | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [837ed83646](https://linux-hardware.org/?probe=837ed83646) | Mar 18, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | [1825764856](https://linux-hardware.org/?probe=1825764856) | Mar 17, 2023 |
| ASUSTek       | K72Jr                       | [cde6fff1ad](https://linux-hardware.org/?probe=cde6fff1ad) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | [2c01c1fd0e](https://linux-hardware.org/?probe=2c01c1fd0e) | Mar 11, 2023 |
| Medion        | Akoya E1318T                | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| ASUSTek       | K52F                        | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| ASUSTek       | K50IJ                       | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| MSI           | GT60 2OC/2OD                | [72eed5b458](https://linux-hardware.org/?probe=72eed5b458) | Mar 08, 2023 |
| MSI           | GT60 2OC/2OD                | [d595ae284e](https://linux-hardware.org/?probe=d595ae284e) | Mar 07, 2023 |
| Alienware     | x14                         | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Acer          | Aspire 6530G                | [a4077c8432](https://linux-hardware.org/?probe=a4077c8432) | Mar 05, 2023 |
| Toshiba       | Satellite C855-112          | [8635f2eecd](https://linux-hardware.org/?probe=8635f2eecd) | Mar 05, 2023 |
| HP            | 620                         | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| ASUSTek       | F70SL                       | [5870cf8326](https://linux-hardware.org/?probe=5870cf8326) | Mar 01, 2023 |
| Dell          | Latitude 5530               | [b1d7964fc7](https://linux-hardware.org/?probe=b1d7964fc7) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| HP            | EliteBook 8540w             | [057c307bf5](https://linux-hardware.org/?probe=057c307bf5) | Feb 28, 2023 |
| Apple         | MacBookPro15,4              | [41330b2783](https://linux-hardware.org/?probe=41330b2783) | Feb 26, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7e5789e02b](https://linux-hardware.org/?probe=7e5789e02b) | Feb 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [da5050e2f8](https://linux-hardware.org/?probe=da5050e2f8) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| TUXEDO        | Aura 15 Gen2                | [9eca2efc88](https://linux-hardware.org/?probe=9eca2efc88) | Feb 19, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| ASUSTek       | K50IJ                       | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Acer          | Aspire V3-771               | [caeb6bc93f](https://linux-hardware.org/?probe=caeb6bc93f) | Feb 17, 2023 |
| Alienware     | 17 R2                       | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| Dell          | XPS 15 9560                 | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| Packard Be... | DOT S                       | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| Dell          | Latitude E6330              | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Valve         | Jupiter                     | [9c458e5a66](https://linux-hardware.org/?probe=9c458e5a66) | Feb 11, 2023 |
| Acer          | Aspire V5-122               | [99fd12250b](https://linux-hardware.org/?probe=99fd12250b) | Feb 10, 2023 |
| Teclast       | F15S                        | [951ded8432](https://linux-hardware.org/?probe=951ded8432) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Valve         | Jupiter                     | [870ba1caa7](https://linux-hardware.org/?probe=870ba1caa7) | Feb 07, 2023 |
| Sony          | VGN-Z31XN_B                 | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| Medion        | P6624                       | [5a31124376](https://linux-hardware.org/?probe=5a31124376) | Feb 06, 2023 |
| ASUSTek       | GL703VD                     | [62e1e79469](https://linux-hardware.org/?probe=62e1e79469) | Feb 03, 2023 |
| Dell          | Precision 7550              | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [72bdb7165c](https://linux-hardware.org/?probe=72bdb7165c) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| Apple         | MacBookAir6,2               | [2261a77abb](https://linux-hardware.org/?probe=2261a77abb) | Feb 01, 2023 |
| Google        | Pantheon                    | [12e0b96dd1](https://linux-hardware.org/?probe=12e0b96dd1) | Feb 01, 2023 |
| ASUSTek       | K50IJ                       | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [f6be582448](https://linux-hardware.org/?probe=f6be582448) | Jan 30, 2023 |
| Lenovo        | S21e-20 80M4                | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| Acer          | Peppy                       | [9a16262be8](https://linux-hardware.org/?probe=9a16262be8) | Jan 27, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [77a6b88d58](https://linux-hardware.org/?probe=77a6b88d58) | Jan 27, 2023 |
| Dell          | Latitude E6410              | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2c8424ac3d](https://linux-hardware.org/?probe=2c8424ac3d) | Jan 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Medion        | P6624                       | [344d427f44](https://linux-hardware.org/?probe=344d427f44) | Jan 20, 2023 |
| Dell          | Latitude 5320               | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Acer          | Aspire VN7-591G             | [9476823c0b](https://linux-hardware.org/?probe=9476823c0b) | Jan 19, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| MSI           | Katana GF76 11UC            | [8c0b32cf24](https://linux-hardware.org/?probe=8c0b32cf24) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Acer          | Aspire V3-571G              | [e3b9b73877](https://linux-hardware.org/?probe=e3b9b73877) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f59adc6dcd](https://linux-hardware.org/?probe=f59adc6dcd) | Jan 13, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | [10c4bcf564](https://linux-hardware.org/?probe=10c4bcf564) | Jan 12, 2023 |
| HP            | Pavilion dv6000 (RY604EA... | [a8ec5eb86a](https://linux-hardware.org/?probe=a8ec5eb86a) | Jan 11, 2023 |
| Acer          | Aspire 7560                 | [58cd9d7ad2](https://linux-hardware.org/?probe=58cd9d7ad2) | Jan 09, 2023 |
| Dell          | XPS L521X                   | [2930493243](https://linux-hardware.org/?probe=2930493243) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [0f1543c21d](https://linux-hardware.org/?probe=0f1543c21d) | Jan 09, 2023 |
| Notebook      | P7xxDM3(-G)                 | [7cafa98138](https://linux-hardware.org/?probe=7cafa98138) | Jan 08, 2023 |
| HP            | Laptop 15s-eq2xxx           | [d1eaa576e7](https://linux-hardware.org/?probe=d1eaa576e7) | Jan 07, 2023 |
| HP            | Laptop 15-db0xxx            | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| Medion        | S4214                       | [58131e715e](https://linux-hardware.org/?probe=58131e715e) | Jan 06, 2023 |
| HP            | Pavilion g7                 | [9f029a8cdb](https://linux-hardware.org/?probe=9f029a8cdb) | Jan 06, 2023 |
| MSI           | Raider GE67HX 12UGS         | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| Dell          | System XPS L702X            | [7030c340cc](https://linux-hardware.org/?probe=7030c340cc) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0A    | [82168627b7](https://linux-hardware.org/?probe=82168627b7) | Dec 31, 2022 |
| MSI           | Raider GE67HX 12UGS         | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| HP            | Notebook                    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Dell          | Latitude 5580               | [7c006e8c6d](https://linux-hardware.org/?probe=7c006e8c6d) | Dec 28, 2022 |
| Notebook      | N7x0WU                      | [9eee40dd50](https://linux-hardware.org/?probe=9eee40dd50) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Valve         | Jupiter                     | [e9811949dd](https://linux-hardware.org/?probe=e9811949dd) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| MSI           | Raider GE67HX 12UGS         | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | Pavilion g7                 | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Sony          | SVS1311N9ES                 | [5c1a4bed5b](https://linux-hardware.org/?probe=5c1a4bed5b) | Dec 24, 2022 |
| ASUSTek       | K53SC                       | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a2d763d722](https://linux-hardware.org/?probe=a2d763d722) | Dec 21, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| Valve         | Jupiter                     | [2f061a6d8d](https://linux-hardware.org/?probe=2f061a6d8d) | Dec 20, 2022 |
| Packard Be... | EasyNote TR85               | [6c56016ed0](https://linux-hardware.org/?probe=6c56016ed0) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | [abd93a5cca](https://linux-hardware.org/?probe=abd93a5cca) | Dec 19, 2022 |
| HP            | ProBook 6570b               | [4deb8fc518](https://linux-hardware.org/?probe=4deb8fc518) | Dec 19, 2022 |
| Valve         | Jupiter                     | [9c513daaf3](https://linux-hardware.org/?probe=9c513daaf3) | Dec 17, 2022 |
| Medion        | WIM2210                     | [d1a64f7b3b](https://linux-hardware.org/?probe=d1a64f7b3b) | Dec 17, 2022 |
| Lenovo        | B70-80 80MR                 | [c17bee3b4a](https://linux-hardware.org/?probe=c17bee3b4a) | Dec 17, 2022 |
| Lenovo        | ThinkPad T570 20H9S04C00    | [f3093ba13c](https://linux-hardware.org/?probe=f3093ba13c) | Dec 16, 2022 |
| Valve         | Jupiter                     | [26aae3342c](https://linux-hardware.org/?probe=26aae3342c) | Dec 16, 2022 |
| Acer          | Aspire A515-57              | [4e9bbbaa1f](https://linux-hardware.org/?probe=4e9bbbaa1f) | Dec 16, 2022 |
| Dell          | Inspiron 5567               | [1398958777](https://linux-hardware.org/?probe=1398958777) | Dec 14, 2022 |
| Apple         | MacBookPro9,2               | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| ASUSTek       | X75VC                       | [45efd7615d](https://linux-hardware.org/?probe=45efd7615d) | Dec 12, 2022 |
| Lenovo        | ThinkPad T430 2349L26       | [9d0bcbdc75](https://linux-hardware.org/?probe=9d0bcbdc75) | Dec 11, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| Lenovo        | ThinkPad T520 4243CJ2       | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| HP            | Pavilion Laptop             | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [6dbc014a04](https://linux-hardware.org/?probe=6dbc014a04) | Dec 03, 2022 |
| HP            | ProBook 6550b               | [564bf050f2](https://linux-hardware.org/?probe=564bf050f2) | Dec 02, 2022 |
| Dell          | G3 3779                     | [1cf1d8aa20](https://linux-hardware.org/?probe=1cf1d8aa20) | Nov 26, 2022 |
| Dell          | G3 3779                     | [4bc02c1721](https://linux-hardware.org/?probe=4bc02c1721) | Nov 26, 2022 |
| Acer          | NC-ES1-512-C3AH             | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [dfd1c98a18](https://linux-hardware.org/?probe=dfd1c98a18) | Nov 20, 2022 |
| HP            | Pavilion dv6                | [a7ca712256](https://linux-hardware.org/?probe=a7ca712256) | Nov 19, 2022 |
| HP            | Pavilion dv6                | [571dc553f9](https://linux-hardware.org/?probe=571dc553f9) | Nov 19, 2022 |
| Dell          | Latitude 5530               | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [7c8d905b3d](https://linux-hardware.org/?probe=7c8d905b3d) | Nov 17, 2022 |
| Dell          | Precision 7560              | [0ee8814502](https://linux-hardware.org/?probe=0ee8814502) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| Apple         | MacBookPro5,5               | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| HP            | EliteBook 850 G5            | [331a1db69d](https://linux-hardware.org/?probe=331a1db69d) | Nov 11, 2022 |
| HP            | Pavilion 15                 | [d703e1c63c](https://linux-hardware.org/?probe=d703e1c63c) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| Acer          | Aspire 1825PTZ              | [c2dc801a81](https://linux-hardware.org/?probe=c2dc801a81) | Nov 09, 2022 |
| Acer          | Aspire 7741                 | [9fda4c3798](https://linux-hardware.org/?probe=9fda4c3798) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| HP            | EliteBook 830 G5            | [25756ad3c1](https://linux-hardware.org/?probe=25756ad3c1) | Nov 07, 2022 |
| HP            | Pavilion 17                 | [958de69d5b](https://linux-hardware.org/?probe=958de69d5b) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| HP            | Pavilion 17                 | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| TUXEDO        | Aura 15 Gen2                | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| ASUSTek       | GL703VD                     | [3e8fbc43d7](https://linux-hardware.org/?probe=3e8fbc43d7) | Nov 04, 2022 |
| Dell          | Latitude 5580               | [92545fb976](https://linux-hardware.org/?probe=92545fb976) | Nov 02, 2022 |
| Dell          | Precision 7550              | [2065f4ab5f](https://linux-hardware.org/?probe=2065f4ab5f) | Nov 02, 2022 |
| HP            | ProBook 470 G5              | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| PC Special... | Recoil II                   | [9ec5a6ef20](https://linux-hardware.org/?probe=9ec5a6ef20) | Oct 27, 2022 |
| PC Special... | Recoil II                   | [38ec5a7708](https://linux-hardware.org/?probe=38ec5a7708) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [0e12d15b78](https://linux-hardware.org/?probe=0e12d15b78) | Oct 24, 2022 |
| Acer          | Aspire E5-521               | [a7bffc7d13](https://linux-hardware.org/?probe=a7bffc7d13) | Oct 22, 2022 |
| Valve         | Jupiter                     | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| Lenovo        | ThinkPad E590 20NB002BMB    | [4b272ef951](https://linux-hardware.org/?probe=4b272ef951) | Oct 20, 2022 |
| TUXEDO        | Aura 15 Gen2                | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| MSI           | GE70 2PE                    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Dell          | Latitude 3380               | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| HP            | ProBook 450 G6              | [fda3302752](https://linux-hardware.org/?probe=fda3302752) | Oct 16, 2022 |
| HP            | EliteBook 8570w             | [76f457f2aa](https://linux-hardware.org/?probe=76f457f2aa) | Oct 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Dell          | XPS 13 9305                 | [0bc0bf85be](https://linux-hardware.org/?probe=0bc0bf85be) | Oct 14, 2022 |
| Dell          | Latitude E6330              | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Dell          | Precision M3800             | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| Notebook      | NS5x_NS7xPU                 | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| Dell          | Latitude 5530               | [9453558076](https://linux-hardware.org/?probe=9453558076) | Oct 12, 2022 |
| ASUSTek       | X756UVK                     | [8d2e9a5e1e](https://linux-hardware.org/?probe=8d2e9a5e1e) | Oct 12, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [24d18c0f7f](https://linux-hardware.org/?probe=24d18c0f7f) | Oct 09, 2022 |
| Valve         | Jupiter                     | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| HP            | EliteBook 745 G6            | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| HP            | EliteBook 840 14 inch G9... | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| Gigabyte      | Spring Peak                 | [45794008e2](https://linux-hardware.org/?probe=45794008e2) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| ASUSTek       | X756UQ                      | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | ProBook 470 G5              | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| Notebook      | W330SU2                     | [a5d5500584](https://linux-hardware.org/?probe=a5d5500584) | Oct 01, 2022 |
| Dell          | Latitude 5530               | [43874dad6d](https://linux-hardware.org/?probe=43874dad6d) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| HP            | EliteBook 6930p             | [56e5d25094](https://linux-hardware.org/?probe=56e5d25094) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| Razer         | Blade                       | [63a4e5f829](https://linux-hardware.org/?probe=63a4e5f829) | Sep 29, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Apple         | MacBookAir6,2               | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Lenovo        | G50-45 80E3                 | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| Lenovo        | B570e 476025G               | [ab67a90ba7](https://linux-hardware.org/?probe=ab67a90ba7) | Sep 20, 2022 |
| HP            | ProBook 470 G5              | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| HP            | Pavilion Notebook           | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude 5520               | [3e023f86c9](https://linux-hardware.org/?probe=3e023f86c9) | Sep 17, 2022 |
| ASUSTek       | UX32VD                      | [324cafa8d2](https://linux-hardware.org/?probe=324cafa8d2) | Sep 17, 2022 |
| Dell          | Precision 7720              | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| Acer          | Aspire 7551                 | [916aa5cc5d](https://linux-hardware.org/?probe=916aa5cc5d) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | [3f97043d7a](https://linux-hardware.org/?probe=3f97043d7a) | Sep 14, 2022 |
| Sony          | SVE1712L1EW                 | [18400c7a0d](https://linux-hardware.org/?probe=18400c7a0d) | Sep 13, 2022 |
| Dell          | Inspiron 15-3567            | [f062dd3ff8](https://linux-hardware.org/?probe=f062dd3ff8) | Sep 12, 2022 |
| ASUSTek       | UX32VD                      | [6a6e7e4207](https://linux-hardware.org/?probe=6a6e7e4207) | Sep 12, 2022 |
| Sony          | SVE1712L1EW                 | [6a797dc1cf](https://linux-hardware.org/?probe=6a797dc1cf) | Sep 12, 2022 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [8d76919c1a](https://linux-hardware.org/?probe=8d76919c1a) | Sep 11, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [603514ef84](https://linux-hardware.org/?probe=603514ef84) | Sep 09, 2022 |
| HP            | Laptop 15-dw0xxx            | [90908282f2](https://linux-hardware.org/?probe=90908282f2) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| Notebook      | NL40_50CU                   | [af0da080ec](https://linux-hardware.org/?probe=af0da080ec) | Sep 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| Lenovo        | ThinkPad P1 20MDS0FC00      | [dcdde00f17](https://linux-hardware.org/?probe=dcdde00f17) | Aug 29, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| Dell          | Latitude 5511               | [22c835a93a](https://linux-hardware.org/?probe=22c835a93a) | Aug 25, 2022 |
| Apple         | MacBookAir6,2               | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Dell          | Vostro 3360                 | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Dell          | XPS 15 9560                 | [d1fb1214f6](https://linux-hardware.org/?probe=d1fb1214f6) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | [fc1a1cd41f](https://linux-hardware.org/?probe=fc1a1cd41f) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| ASUSTek       | X756UQ                      | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | Laptop 15-bs0xx             | [3e63b30226](https://linux-hardware.org/?probe=3e63b30226) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| Dell          | Latitude D630               | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [882cec3541](https://linux-hardware.org/?probe=882cec3541) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Dell          | Latitude 5520               | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Acer          | Swift SF114-32              | [9e219bd7c2](https://linux-hardware.org/?probe=9e219bd7c2) | Jul 29, 2022 |
| Acer          | Aspire A315-51              | [e6f2cdc55e](https://linux-hardware.org/?probe=e6f2cdc55e) | Jul 29, 2022 |
| Dell          | Latitude 5590               | [ab7d6b9f02](https://linux-hardware.org/?probe=ab7d6b9f02) | Jul 28, 2022 |
| Dell          | Latitude E6430s             | [356556d83a](https://linux-hardware.org/?probe=356556d83a) | Jul 28, 2022 |
| Dell          | Latitude D630               | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [910067609e](https://linux-hardware.org/?probe=910067609e) | Jul 27, 2022 |
| Toshiba       | Satellite C870D-116         | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| Sony          | VGN-Z31XN_B                 | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| Panasonic     | FZ55-2                      | [a190a7d890](https://linux-hardware.org/?probe=a190a7d890) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| MSI           | Vector GP76 12UH            | [7ac84940b8](https://linux-hardware.org/?probe=7ac84940b8) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Valve         | Jupiter                     | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Lenovo        | ThinkPad E580 20KSS0GK01    | [b2d902cbc6](https://linux-hardware.org/?probe=b2d902cbc6) | Jul 21, 2022 |
| HP            | EliteBook 8570p             | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| Acer          | Aspire A515-54              | [bffac60888](https://linux-hardware.org/?probe=bffac60888) | Jul 16, 2022 |
| Acer          | Aspire A515-54              | [d52eabbac8](https://linux-hardware.org/?probe=d52eabbac8) | Jul 16, 2022 |
| HP            | ProBook 650 G5              | [471b64a407](https://linux-hardware.org/?probe=471b64a407) | Jul 16, 2022 |
| Sony          | SVE1513H1EW                 | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Sony          | VGN-Z31XN_B                 | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| Dell          | XPS 13 9360                 | [b08ab62885](https://linux-hardware.org/?probe=b08ab62885) | Jul 06, 2022 |
| NEC Comput... | NEC Versa M370              | [d4dbd6878c](https://linux-hardware.org/?probe=d4dbd6878c) | Jul 04, 2022 |
| Lenovo        | G50-45 80E3                 | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| HP            | Pavilion dm1                | [927f5b38e0](https://linux-hardware.org/?probe=927f5b38e0) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [90a56ffa69](https://linux-hardware.org/?probe=90a56ffa69) | Jun 27, 2022 |
| ASUSTek       | X555LJ                      | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Dell          | Latitude E6330              | [969981b8cb](https://linux-hardware.org/?probe=969981b8cb) | Jun 25, 2022 |
| ASUSTek       | GL502VMK                    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| HP            | ProBook 470 G5              | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| Unknown       | Unknown                     | [812caba8bf](https://linux-hardware.org/?probe=812caba8bf) | Jun 16, 2022 |
| Apple         | MacBookPro14,1              | [4b6c230717](https://linux-hardware.org/?probe=4b6c230717) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| HP            | Compaq 8710w                | [666f2ebcf0](https://linux-hardware.org/?probe=666f2ebcf0) | Jun 08, 2022 |
| Apple         | MacBookPro10,1              | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| HP            | ProBook 470 G1              | [ea56369709](https://linux-hardware.org/?probe=ea56369709) | Jun 03, 2022 |
| Samsung       | 750XED                      | [1a900ee340](https://linux-hardware.org/?probe=1a900ee340) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| Toshiba       | Satellite C70D-A            | [70313d6ed4](https://linux-hardware.org/?probe=70313d6ed4) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | [820a9fb182](https://linux-hardware.org/?probe=820a9fb182) | May 30, 2022 |
| SLIMBOOK      | TITAN                       | [1029a819d7](https://linux-hardware.org/?probe=1029a819d7) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | [c4e27f4d19](https://linux-hardware.org/?probe=c4e27f4d19) | May 29, 2022 |
| HP            | Pavilion 17                 | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | [475315dc10](https://linux-hardware.org/?probe=475315dc10) | May 28, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [397d64e10c](https://linux-hardware.org/?probe=397d64e10c) | May 27, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [a74cc1410a](https://linux-hardware.org/?probe=a74cc1410a) | May 27, 2022 |
| HP            | Pavilion g6                 | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| HP            | OMEN by Laptop              | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| ASUSTek       | X756UQ                      | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Medion        | P6624                       | [ed8bd28269](https://linux-hardware.org/?probe=ed8bd28269) | May 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [a0597ba198](https://linux-hardware.org/?probe=a0597ba198) | May 20, 2022 |
| HP            | ProBook 470 G2              | [9d14cc23ca](https://linux-hardware.org/?probe=9d14cc23ca) | May 20, 2022 |
| HP            | ProBook 470 G2              | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | ProBook 470 G2              | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| ASUSTek       | GL552VW                     | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | [0f8829e460](https://linux-hardware.org/?probe=0f8829e460) | May 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS4X50... | [0fb588c686](https://linux-hardware.org/?probe=0fb588c686) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | [83b27998e5](https://linux-hardware.org/?probe=83b27998e5) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3f84f4220e](https://linux-hardware.org/?probe=3f84f4220e) | May 14, 2022 |
| Sony          | VPCEH1M0E                   | [eefe7eee06](https://linux-hardware.org/?probe=eefe7eee06) | May 13, 2022 |
| HP            | ProBook 470 G1              | [06030eee20](https://linux-hardware.org/?probe=06030eee20) | May 13, 2022 |
| MSI           | GF63 Thin 9SC               | [a6f5c6215d](https://linux-hardware.org/?probe=a6f5c6215d) | May 11, 2022 |
| Dell          | XPS 13 9305                 | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [8080b9becd](https://linux-hardware.org/?probe=8080b9becd) | May 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [1d84f1a74a](https://linux-hardware.org/?probe=1d84f1a74a) | May 07, 2022 |
| Dell          | Latitude E6330              | [cbfc4e6f78](https://linux-hardware.org/?probe=cbfc4e6f78) | May 07, 2022 |
| Lenovo        | ThinkPad X280 20KES94F05    | [16b4cbc9fb](https://linux-hardware.org/?probe=16b4cbc9fb) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [a7396f278d](https://linux-hardware.org/?probe=a7396f278d) | May 02, 2022 |
| Dell          | XPS 15 9570                 | [01a95b61fe](https://linux-hardware.org/?probe=01a95b61fe) | May 02, 2022 |
| ASUSTek       | X550LD                      | [5625deb6aa](https://linux-hardware.org/?probe=5625deb6aa) | May 01, 2022 |
| ASUSTek       | X756UQ                      | [130944084d](https://linux-hardware.org/?probe=130944084d) | May 01, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [0e0d0dd3aa](https://linux-hardware.org/?probe=0e0d0dd3aa) | Apr 30, 2022 |
| ASUSTek       | X756UQ                      | [2543d87831](https://linux-hardware.org/?probe=2543d87831) | Apr 30, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [21fcbc1850](https://linux-hardware.org/?probe=21fcbc1850) | Apr 27, 2022 |
| Dell          | XPS 13 9305                 | [edf60be002](https://linux-hardware.org/?probe=edf60be002) | Apr 26, 2022 |
| BLAUPUNKT     | Discovery 1011WI            | [c20b87673e](https://linux-hardware.org/?probe=c20b87673e) | Apr 24, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | [762843e768](https://linux-hardware.org/?probe=762843e768) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | [11ec4d291b](https://linux-hardware.org/?probe=11ec4d291b) | Apr 23, 2022 |
| Fujitsu       | LIFEBOOK E744               | [ca56dc9824](https://linux-hardware.org/?probe=ca56dc9824) | Apr 21, 2022 |
| ASUSTek       | GL502VMK                    | [cc5ed34db8](https://linux-hardware.org/?probe=cc5ed34db8) | Apr 21, 2022 |
| Lenovo        | ThinkPad T520 4243AP1       | [7723ab4bd9](https://linux-hardware.org/?probe=7723ab4bd9) | Apr 19, 2022 |
| MSI           | GL65 Leopard 10SER          | [2bdfe0279e](https://linux-hardware.org/?probe=2bdfe0279e) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440s 20ARS1940... | [a7fbe1af34](https://linux-hardware.org/?probe=a7fbe1af34) | Apr 18, 2022 |
| ASUSTek       | G752VSK                     | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | [7b1d2ec5a1](https://linux-hardware.org/?probe=7b1d2ec5a1) | Apr 17, 2022 |
| Acer          | Aspire 5735                 | [e43434e15c](https://linux-hardware.org/?probe=e43434e15c) | Apr 15, 2022 |
| Dell          | Inspiron 15-3567            | [4639b09a3e](https://linux-hardware.org/?probe=4639b09a3e) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [b80dc08588](https://linux-hardware.org/?probe=b80dc08588) | Apr 14, 2022 |
| Dell          | Latitude 5591               | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [5aafaf0890](https://linux-hardware.org/?probe=5aafaf0890) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [983dbbf9e8](https://linux-hardware.org/?probe=983dbbf9e8) | Apr 13, 2022 |
| Acer          | Aspire 7745G                | [7ea9773813](https://linux-hardware.org/?probe=7ea9773813) | Apr 12, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [09f8f09862](https://linux-hardware.org/?probe=09f8f09862) | Apr 11, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [da1cd5bf6e](https://linux-hardware.org/?probe=da1cd5bf6e) | Apr 11, 2022 |
| Google        | Akali 360                   | [dccccb359b](https://linux-hardware.org/?probe=dccccb359b) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2ce1788c33](https://linux-hardware.org/?probe=2ce1788c33) | Apr 11, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [01f57dd952](https://linux-hardware.org/?probe=01f57dd952) | Apr 10, 2022 |
| HP            | ProBook 470 G2              | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Dell          | Latitude E6430              | [dd09c863c8](https://linux-hardware.org/?probe=dd09c863c8) | Apr 08, 2022 |
| HP            | ProBook 430 G1              | [8bcbe236a7](https://linux-hardware.org/?probe=8bcbe236a7) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [af324f356f](https://linux-hardware.org/?probe=af324f356f) | Apr 07, 2022 |
| HP            | ZBook 15 G3                 | [27bddd0a9c](https://linux-hardware.org/?probe=27bddd0a9c) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [fc358abe4b](https://linux-hardware.org/?probe=fc358abe4b) | Apr 06, 2022 |
| HP            | 470 G7 Notebook PC          | [34fc91d9ac](https://linux-hardware.org/?probe=34fc91d9ac) | Apr 06, 2022 |
| Dell          | Latitude 5410               | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| Dell          | XPS 13 7390                 | [8c4011afa9](https://linux-hardware.org/?probe=8c4011afa9) | Apr 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [94a9015090](https://linux-hardware.org/?probe=94a9015090) | Apr 03, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| ASUSTek       | X540LA                      | [732406d8b0](https://linux-hardware.org/?probe=732406d8b0) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [086261ecef](https://linux-hardware.org/?probe=086261ecef) | Apr 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [4731581e9b](https://linux-hardware.org/?probe=4731581e9b) | Mar 31, 2022 |
| HP            | ZBook Studio G4             | [d5ec5c3e8e](https://linux-hardware.org/?probe=d5ec5c3e8e) | Mar 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Medion        | Crawler E25                 | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| HP            | ProBook 470 G5              | [b8969bf34b](https://linux-hardware.org/?probe=b8969bf34b) | Mar 27, 2022 |
| Acer          | Aspire 8930                 | [6774be59d3](https://linux-hardware.org/?probe=6774be59d3) | Mar 26, 2022 |
| HP            | EliteBook Folio 1040 G1     | [bbdb3c316f](https://linux-hardware.org/?probe=bbdb3c316f) | Mar 25, 2022 |
| HP            | EliteBook Folio 1040 G1     | [6096fbc1ba](https://linux-hardware.org/?probe=6096fbc1ba) | Mar 25, 2022 |
| ASUSTek       | N56VZ                       | [7ad46659a5](https://linux-hardware.org/?probe=7ad46659a5) | Mar 24, 2022 |
| Packard Be... | DOT S                       | [591be1d465](https://linux-hardware.org/?probe=591be1d465) | Mar 22, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | [26cd5cf250](https://linux-hardware.org/?probe=26cd5cf250) | Mar 20, 2022 |
| ASUSTek       | X555LJ                      | [9e38b0860e](https://linux-hardware.org/?probe=9e38b0860e) | Mar 19, 2022 |
| Dell          | XPS 13 9370                 | [1feeb83fb4](https://linux-hardware.org/?probe=1feeb83fb4) | Mar 19, 2022 |
| Acer          | Aspire 8930                 | [79f6f7d9c1](https://linux-hardware.org/?probe=79f6f7d9c1) | Mar 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6a5b5cd15e](https://linux-hardware.org/?probe=6a5b5cd15e) | Mar 17, 2022 |
| HP            | Laptop 15-bs0xx             | [37a24fa0b8](https://linux-hardware.org/?probe=37a24fa0b8) | Mar 13, 2022 |
| ASUSTek       | X756UQ                      | [30ec3132c4](https://linux-hardware.org/?probe=30ec3132c4) | Mar 12, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| Lenovo        | ThinkPad L390 20NSS1YV0B    | [a48bd2e59b](https://linux-hardware.org/?probe=a48bd2e59b) | Mar 10, 2022 |
| HP            | Pavilion zd8000 (EL052EA... | [18f42a184c](https://linux-hardware.org/?probe=18f42a184c) | Mar 08, 2022 |
| Dell          | Latitude 5500               | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Dell          | Latitude 5500               | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo        | ThinkPad W541 20EFA013MB    | [b4087fab13](https://linux-hardware.org/?probe=b4087fab13) | Mar 06, 2022 |
| Dell          | Latitude E6330              | [f4491d2da7](https://linux-hardware.org/?probe=f4491d2da7) | Mar 06, 2022 |
| Acer          | Aspire A315-21              | [435c237f8f](https://linux-hardware.org/?probe=435c237f8f) | Mar 02, 2022 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [f67c401f47](https://linux-hardware.org/?probe=f67c401f47) | Feb 27, 2022 |
| HP            | Pavilion dv6                | [d04802b99e](https://linux-hardware.org/?probe=d04802b99e) | Feb 27, 2022 |
| HP            | Pavilion 15                 | [e72fbddbc9](https://linux-hardware.org/?probe=e72fbddbc9) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [8166a6711c](https://linux-hardware.org/?probe=8166a6711c) | Feb 25, 2022 |
| Packard Be... | EasyNote_MX67               | [0687a8a072](https://linux-hardware.org/?probe=0687a8a072) | Feb 23, 2022 |
| Dell          | Latitude E5550              | [7eb0675554](https://linux-hardware.org/?probe=7eb0675554) | Feb 22, 2022 |
| HP            | Pavilion 15                 | [6aaa686668](https://linux-hardware.org/?probe=6aaa686668) | Feb 22, 2022 |
| Sony          | VGN-FW51JF_H                | [03c4e88514](https://linux-hardware.org/?probe=03c4e88514) | Feb 22, 2022 |
| Lenovo        | ThinkPad W541 20EFA013MB    | [99676b9365](https://linux-hardware.org/?probe=99676b9365) | Feb 21, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [59476747e2](https://linux-hardware.org/?probe=59476747e2) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | [ad3eb03b54](https://linux-hardware.org/?probe=ad3eb03b54) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | [83b3333eb0](https://linux-hardware.org/?probe=83b3333eb0) | Feb 20, 2022 |
| Acer          | Aspire V3-771               | [962c444158](https://linux-hardware.org/?probe=962c444158) | Feb 19, 2022 |
| ASUSTek       | P751JA                      | [54c2cab341](https://linux-hardware.org/?probe=54c2cab341) | Feb 18, 2022 |
| ASUSTek       | X756UQ                      | [757a05c274](https://linux-hardware.org/?probe=757a05c274) | Feb 18, 2022 |
| Acer          | Aspire 7745G                | [b32ffb9adc](https://linux-hardware.org/?probe=b32ffb9adc) | Feb 17, 2022 |
| Acer          | Aspire 5750G                | [3bb86aa608](https://linux-hardware.org/?probe=3bb86aa608) | Feb 17, 2022 |
| ASUSTek       | P751JA                      | [8e2a0e2970](https://linux-hardware.org/?probe=8e2a0e2970) | Feb 16, 2022 |
| HP            | Pavilion dv6500             | [70b0938bc3](https://linux-hardware.org/?probe=70b0938bc3) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | [918d93ea7a](https://linux-hardware.org/?probe=918d93ea7a) | Feb 15, 2022 |
| HP            | Pavilion 15                 | [67825b30b9](https://linux-hardware.org/?probe=67825b30b9) | Feb 15, 2022 |
| HP            | ProBook 6560b               | [425caa152d](https://linux-hardware.org/?probe=425caa152d) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ed2717ae86](https://linux-hardware.org/?probe=ed2717ae86) | Feb 14, 2022 |
| Lenovo        | ThinkPad X260 20F5S3FY00    | [08006b1c3a](https://linux-hardware.org/?probe=08006b1c3a) | Feb 13, 2022 |
| ASUSTek       | N501JW                      | [7937164c8a](https://linux-hardware.org/?probe=7937164c8a) | Feb 11, 2022 |
| HP            | ProBook 450 G5              | [804f3b74e0](https://linux-hardware.org/?probe=804f3b74e0) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | [9e1c3acaf3](https://linux-hardware.org/?probe=9e1c3acaf3) | Feb 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [baf12e4099](https://linux-hardware.org/?probe=baf12e4099) | Feb 09, 2022 |
| GPD           | G1621-02                    | [d823ea2989](https://linux-hardware.org/?probe=d823ea2989) | Feb 09, 2022 |
| Acer          | Aspire A715-74G             | [00f0fe6cd3](https://linux-hardware.org/?probe=00f0fe6cd3) | Feb 09, 2022 |
| HP            | Pavilion dv7                | [03b19f857f](https://linux-hardware.org/?probe=03b19f857f) | Feb 09, 2022 |
| Lenovo        | ThinkPad T500 20828VG       | [f79076499b](https://linux-hardware.org/?probe=f79076499b) | Feb 09, 2022 |
| PC Special... | GK5NPFO                     | [14695b59b4](https://linux-hardware.org/?probe=14695b59b4) | Feb 08, 2022 |
| Toshiba       | Satellite C855-112          | [99cb514a47](https://linux-hardware.org/?probe=99cb514a47) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [48b1ca5fbc](https://linux-hardware.org/?probe=48b1ca5fbc) | Feb 07, 2022 |
| Lenovo        | ThinkPad E495 20NES01600    | [c40a0c5222](https://linux-hardware.org/?probe=c40a0c5222) | Feb 07, 2022 |
| Sony          | VGN-FW51JF_H                | [0e5f92c7b7](https://linux-hardware.org/?probe=0e5f92c7b7) | Feb 07, 2022 |
| Acer          | Nitro AN515-52              | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| ASUSTek       | K73SV                       | [0610b130c8](https://linux-hardware.org/?probe=0610b130c8) | Feb 05, 2022 |
| ASUSTek       | K73SV                       | [519bc1d808](https://linux-hardware.org/?probe=519bc1d808) | Feb 05, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [0b95e33d17](https://linux-hardware.org/?probe=0b95e33d17) | Feb 03, 2022 |
| HP            | EliteBook 8570w             | [690ef309e9](https://linux-hardware.org/?probe=690ef309e9) | Feb 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [3171e9710d](https://linux-hardware.org/?probe=3171e9710d) | Feb 03, 2022 |
| ASUSTek       | K95VJ                       | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Notebook      | NH5x_7xDPx                  | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| Dell          | G3 3500                     | [141e63ae77](https://linux-hardware.org/?probe=141e63ae77) | Feb 02, 2022 |
| Sony          | SVE1713F1EW                 | [34db9cd3c0](https://linux-hardware.org/?probe=34db9cd3c0) | Feb 01, 2022 |
| Sony          | VGN-FE31H                   | [a7185cc26a](https://linux-hardware.org/?probe=a7185cc26a) | Feb 01, 2022 |
| Sony          | SVE1713F1EW                 | [591b6e4d01](https://linux-hardware.org/?probe=591b6e4d01) | Feb 01, 2022 |
| Unknown       | Unknown                     | [f3b0dd4384](https://linux-hardware.org/?probe=f3b0dd4384) | Jan 31, 2022 |
| MSI           | GE70 2OC\2OD\2OE            | [f9efba7bbf](https://linux-hardware.org/?probe=f9efba7bbf) | Jan 30, 2022 |
| Sony          | SVE1712W1EB                 | [c6b525e9c3](https://linux-hardware.org/?probe=c6b525e9c3) | Jan 29, 2022 |
| Sony          | SVE1712W1EB                 | [c780c90c73](https://linux-hardware.org/?probe=c780c90c73) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| Sony          | VGN-FE31H                   | [a53478c6b1](https://linux-hardware.org/?probe=a53478c6b1) | Jan 28, 2022 |
| Sony          | VGN-FE31H                   | [90e1046590](https://linux-hardware.org/?probe=90e1046590) | Jan 28, 2022 |
| ASUSTek       | X551CA                      | [0cb832f85f](https://linux-hardware.org/?probe=0cb832f85f) | Jan 27, 2022 |
| ASUSTek       | ZenBook UX325UAZ_UM325UA... | [7a90772bfd](https://linux-hardware.org/?probe=7a90772bfd) | Jan 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [1abbb329fa](https://linux-hardware.org/?probe=1abbb329fa) | Jan 26, 2022 |
| HP            | Pavilion dv7                | [c639bc4c98](https://linux-hardware.org/?probe=c639bc4c98) | Jan 25, 2022 |
| HP            | ProBook 6570b               | [681a804c88](https://linux-hardware.org/?probe=681a804c88) | Jan 24, 2022 |
| Lenovo        | ThinkPad X250 20CMS02F00    | [e4d90a5ae8](https://linux-hardware.org/?probe=e4d90a5ae8) | Jan 23, 2022 |
| Lenovo        | ThinkPad T420 423664U       | [0e2bb9a59f](https://linux-hardware.org/?probe=0e2bb9a59f) | Jan 23, 2022 |
| HP            | ProBook 470 G5              | [6610c7d6e1](https://linux-hardware.org/?probe=6610c7d6e1) | Jan 22, 2022 |
| Dell          | XPS 13 9350                 | [485c5e0968](https://linux-hardware.org/?probe=485c5e0968) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| Dell          | Latitude E6530              | [bf71e70abb](https://linux-hardware.org/?probe=bf71e70abb) | Jan 21, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SNC... | [0b0ddf4175](https://linux-hardware.org/?probe=0b0ddf4175) | Jan 21, 2022 |
| ASUSTek       | GL552VW                     | [4544642750](https://linux-hardware.org/?probe=4544642750) | Jan 20, 2022 |
| Dell          | Latitude E6530              | [8559d4a5b0](https://linux-hardware.org/?probe=8559d4a5b0) | Jan 19, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [cf36481feb](https://linux-hardware.org/?probe=cf36481feb) | Jan 16, 2022 |
| Dell          | XPS 13 9305                 | [d6594c7edb](https://linux-hardware.org/?probe=d6594c7edb) | Jan 15, 2022 |
| Dell          | Latitude 5520               | [95721c3566](https://linux-hardware.org/?probe=95721c3566) | Jan 15, 2022 |
| ASUSTek       | X580VD                      | [9cb7ebea38](https://linux-hardware.org/?probe=9cb7ebea38) | Jan 14, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [e293ddf5fc](https://linux-hardware.org/?probe=e293ddf5fc) | Jan 14, 2022 |
| Dell          | Latitude 7490               | [98c318edfd](https://linux-hardware.org/?probe=98c318edfd) | Jan 13, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de24bac4e8](https://linux-hardware.org/?probe=de24bac4e8) | Jan 13, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [7edab0851b](https://linux-hardware.org/?probe=7edab0851b) | Jan 12, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| Acer          | Aspire A315-21              | [2f505d02d9](https://linux-hardware.org/?probe=2f505d02d9) | Jan 09, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [62c4e26a01](https://linux-hardware.org/?probe=62c4e26a01) | Jan 09, 2022 |
| ASUSTek       | GL552VW                     | [69a4959007](https://linux-hardware.org/?probe=69a4959007) | Jan 09, 2022 |
| Dell          | XPS 13 9305                 | [83ccc00b28](https://linux-hardware.org/?probe=83ccc00b28) | Jan 08, 2022 |
| Dell          | Latitude E6330              | [da29c6f100](https://linux-hardware.org/?probe=da29c6f100) | Jan 08, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5ed2055b1e](https://linux-hardware.org/?probe=5ed2055b1e) | Jan 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [95c067b96e](https://linux-hardware.org/?probe=95c067b96e) | Jan 07, 2022 |
| HP            | Compaq 8710w                | [ab5f731d97](https://linux-hardware.org/?probe=ab5f731d97) | Jan 05, 2022 |
| Acer          | Aspire 7520                 | [462c034a56](https://linux-hardware.org/?probe=462c034a56) | Jan 04, 2022 |
| HP            | Compaq 8710w                | [573e8e760f](https://linux-hardware.org/?probe=573e8e760f) | Jan 03, 2022 |
| Dell          | Latitude E6510              | [7a6c58b609](https://linux-hardware.org/?probe=7a6c58b609) | Jan 02, 2022 |
| Fujitsu       | LIFEBOOK E752               | [e6e4d232a9](https://linux-hardware.org/?probe=e6e4d232a9) | Jan 02, 2022 |
| HP            | EliteBook 6930p (GB995EA... | [e0a482ab1e](https://linux-hardware.org/?probe=e0a482ab1e) | Jan 02, 2022 |
| Packard Be... | EasyNote TK85               | [cef3f4f826](https://linux-hardware.org/?probe=cef3f4f826) | Dec 28, 2021 |
| HP            | ProBook 4730s               | [08cca0b4b5](https://linux-hardware.org/?probe=08cca0b4b5) | Dec 28, 2021 |
| Lenovo        | ThinkPad L540 20AV0031MB    | [5abe6c6347](https://linux-hardware.org/?probe=5abe6c6347) | Dec 28, 2021 |
| ASUSTek       | X302LA                      | [3c747e6bb0](https://linux-hardware.org/?probe=3c747e6bb0) | Dec 28, 2021 |
| HP            | EliteBook 850 G5            | [f385608043](https://linux-hardware.org/?probe=f385608043) | Dec 28, 2021 |
| Sony          | VPCEL1E1E                   | [4deb7655c4](https://linux-hardware.org/?probe=4deb7655c4) | Dec 27, 2021 |
| HUAWEI        | HVY-WXX9                    | [23460afe38](https://linux-hardware.org/?probe=23460afe38) | Dec 27, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | [0af1aded1f](https://linux-hardware.org/?probe=0af1aded1f) | Dec 27, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Apple         | MacBookPro10,1              | [381c7dee2d](https://linux-hardware.org/?probe=381c7dee2d) | Dec 25, 2021 |
| HP            | ProBook 640 G4              | [f1fa3d65b1](https://linux-hardware.org/?probe=f1fa3d65b1) | Dec 25, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [14d7bc4e66](https://linux-hardware.org/?probe=14d7bc4e66) | Dec 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | [d4fcc94659](https://linux-hardware.org/?probe=d4fcc94659) | Dec 22, 2021 |
| MSI           | GE72 6QC                    | [4c5a8f6b4a](https://linux-hardware.org/?probe=4c5a8f6b4a) | Dec 21, 2021 |
| Notebook      | NH5x_NH7xHP                 | [0408aca941](https://linux-hardware.org/?probe=0408aca941) | Dec 21, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [88a4b38685](https://linux-hardware.org/?probe=88a4b38685) | Dec 21, 2021 |
| HP            | G62                         | [fac3d0a6b6](https://linux-hardware.org/?probe=fac3d0a6b6) | Dec 21, 2021 |
| ASUSTek       | N501JW                      | [2b928f1e66](https://linux-hardware.org/?probe=2b928f1e66) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | [9da235adb3](https://linux-hardware.org/?probe=9da235adb3) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | [037f47a340](https://linux-hardware.org/?probe=037f47a340) | Dec 19, 2021 |
| Google        | Pantheon                    | [8b1d8783ad](https://linux-hardware.org/?probe=8b1d8783ad) | Dec 17, 2021 |
| HP            | Pavilion dv7                | [0e0f0e3c23](https://linux-hardware.org/?probe=0e0f0e3c23) | Dec 15, 2021 |
| Acer          | Swift SF113-31              | [e951b45254](https://linux-hardware.org/?probe=e951b45254) | Dec 12, 2021 |
| Clevo         | W270HU                      | [486cbb154a](https://linux-hardware.org/?probe=486cbb154a) | Dec 12, 2021 |
| Dell          | Latitude E5410              | [8b6bc5cf8e](https://linux-hardware.org/?probe=8b6bc5cf8e) | Dec 12, 2021 |
| Clevo         | W270HU                      | [5152801cbe](https://linux-hardware.org/?probe=5152801cbe) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Lenovo        | G50-80 80E5                 | [77ee4f08a8](https://linux-hardware.org/?probe=77ee4f08a8) | Dec 10, 2021 |
| Lenovo        | ThinkPad X280 20KES94F05    | [ba3d89dca3](https://linux-hardware.org/?probe=ba3d89dca3) | Dec 08, 2021 |
| Acer          | Aspire 5750G                | [fb84f5c3c5](https://linux-hardware.org/?probe=fb84f5c3c5) | Dec 05, 2021 |
| HP            | ProBook 470 G5              | [1cfd3aadd8](https://linux-hardware.org/?probe=1cfd3aadd8) | Dec 04, 2021 |
| Acer          | Aspire A315-21              | [322f9afcb0](https://linux-hardware.org/?probe=322f9afcb0) | Dec 04, 2021 |
| Acer          | Aspire 7736                 | [20d3c3fff5](https://linux-hardware.org/?probe=20d3c3fff5) | Dec 01, 2021 |
| Celestica     | D4040                       | [109f886f1d](https://linux-hardware.org/?probe=109f886f1d) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [3a85954b66](https://linux-hardware.org/?probe=3a85954b66) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [5271c46262](https://linux-hardware.org/?probe=5271c46262) | Nov 29, 2021 |
| HP            | ProBook 640 G4              | [e58b0e7945](https://linux-hardware.org/?probe=e58b0e7945) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [6e63fb12a3](https://linux-hardware.org/?probe=6e63fb12a3) | Nov 28, 2021 |
| HP            | Compaq 6720s                | [2c62d9df9c](https://linux-hardware.org/?probe=2c62d9df9c) | Nov 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | [3d1d036e1e](https://linux-hardware.org/?probe=3d1d036e1e) | Nov 27, 2021 |
| Dell          | Latitude 5580               | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Toshiba       | Satellite A300              | [c62dc3b138](https://linux-hardware.org/?probe=c62dc3b138) | Nov 25, 2021 |
| HP            | EliteBook 735 G5            | [d80b574cb4](https://linux-hardware.org/?probe=d80b574cb4) | Nov 24, 2021 |
| ASUSTek       | GL552VW                     | [59670a3933](https://linux-hardware.org/?probe=59670a3933) | Nov 23, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [8c5bc064e9](https://linux-hardware.org/?probe=8c5bc064e9) | Nov 21, 2021 |
| Dell          | Latitude D630               | [0d437ca2f6](https://linux-hardware.org/?probe=0d437ca2f6) | Nov 21, 2021 |
| Notebook      | PA70ES                      | [55d43af19e](https://linux-hardware.org/?probe=55d43af19e) | Nov 20, 2021 |
| Lenovo        | ThinkPad E495 20NES01600    | [aacc57f134](https://linux-hardware.org/?probe=aacc57f134) | Nov 17, 2021 |
| Notebook      | N24_25JU                    | [30df18e398](https://linux-hardware.org/?probe=30df18e398) | Nov 16, 2021 |
| Teclast       | F6 Plus                     | [7e5836dbaa](https://linux-hardware.org/?probe=7e5836dbaa) | Nov 16, 2021 |
| Dell          | Latitude D620               | [855218ab46](https://linux-hardware.org/?probe=855218ab46) | Nov 16, 2021 |
| ASUSTek       | Strix GL703GS_GL703GS       | [6eb0749ee8](https://linux-hardware.org/?probe=6eb0749ee8) | Nov 15, 2021 |
| ASUSTek       | X75VC                       | [39352780e5](https://linux-hardware.org/?probe=39352780e5) | Nov 12, 2021 |
| Packard Be... | EasyNote TE11BZ             | [de427e19ea](https://linux-hardware.org/?probe=de427e19ea) | Nov 11, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | [0cbad8aae1](https://linux-hardware.org/?probe=0cbad8aae1) | Nov 11, 2021 |
| Acer          | AO751h                      | [e2beb798cc](https://linux-hardware.org/?probe=e2beb798cc) | Nov 10, 2021 |
| Sony          | VPCF13M1E                   | [9858905cc2](https://linux-hardware.org/?probe=9858905cc2) | Nov 09, 2021 |
| Toshiba       | TECRA W50-A                 | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Unknown       | Unknown                     | [ed806d64c8](https://linux-hardware.org/?probe=ed806d64c8) | Nov 05, 2021 |
| Gigabyte      | Spring Peak                 | [fc1efa8df5](https://linux-hardware.org/?probe=fc1efa8df5) | Nov 04, 2021 |
| Lenovo        | G50-80 80E5                 | [2ecc44141a](https://linux-hardware.org/?probe=2ecc44141a) | Oct 30, 2021 |
| HP            | ZBook Studio G4             | [984d3cdc29](https://linux-hardware.org/?probe=984d3cdc29) | Oct 30, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [3f5dd495d5](https://linux-hardware.org/?probe=3f5dd495d5) | Oct 27, 2021 |
| Lenovo        | G570 4334                   | [cc07ebf9b6](https://linux-hardware.org/?probe=cc07ebf9b6) | Oct 27, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | [65eac6abc6](https://linux-hardware.org/?probe=65eac6abc6) | Oct 27, 2021 |
| Dell          | Latitude 7390               | [92dcb677f7](https://linux-hardware.org/?probe=92dcb677f7) | Oct 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [39e318621b](https://linux-hardware.org/?probe=39e318621b) | Oct 26, 2021 |
| Notebook      | P7xxDM3(-G)                 | [5c62ec0ce3](https://linux-hardware.org/?probe=5c62ec0ce3) | Oct 24, 2021 |
| Dell          | Studio 1555                 | [3fed161971](https://linux-hardware.org/?probe=3fed161971) | Oct 24, 2021 |
| HP            | ProBook 4540s               | [49ce392cd2](https://linux-hardware.org/?probe=49ce392cd2) | Oct 24, 2021 |
| HP            | ProBook 470 G5              | [725627d16b](https://linux-hardware.org/?probe=725627d16b) | Oct 23, 2021 |
| Acer          | Nitro AN515-54              | [fe7a37dce1](https://linux-hardware.org/?probe=fe7a37dce1) | Oct 22, 2021 |
| Notebook      | P7xxDM3(-G)                 | [250e2a46b0](https://linux-hardware.org/?probe=250e2a46b0) | Oct 22, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [86bc5ddc56](https://linux-hardware.org/?probe=86bc5ddc56) | Oct 21, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [44537c7fba](https://linux-hardware.org/?probe=44537c7fba) | Oct 20, 2021 |
| Notebook      | PB50_70RF,RD,RC             | [ec41eeb7c0](https://linux-hardware.org/?probe=ec41eeb7c0) | Oct 20, 2021 |
| ASUSTek       | K72F                        | [0eedfc8a67](https://linux-hardware.org/?probe=0eedfc8a67) | Oct 20, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [2412314ad9](https://linux-hardware.org/?probe=2412314ad9) | Oct 18, 2021 |
| TUXEDO        | Aura 15 Gen1                | [57260c1999](https://linux-hardware.org/?probe=57260c1999) | Oct 18, 2021 |
| Lenovo        | G50-80 80E5                 | [7075439e69](https://linux-hardware.org/?probe=7075439e69) | Oct 17, 2021 |
| Acer          | Nitro AN515-55              | [9bf062da25](https://linux-hardware.org/?probe=9bf062da25) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [69fc64df8b](https://linux-hardware.org/?probe=69fc64df8b) | Oct 16, 2021 |
| HP            | ProBook 4540s               | [046acc5982](https://linux-hardware.org/?probe=046acc5982) | Oct 14, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [a5072cec8c](https://linux-hardware.org/?probe=a5072cec8c) | Oct 10, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | [4bb69f9fcc](https://linux-hardware.org/?probe=4bb69f9fcc) | Oct 10, 2021 |
| Lenovo        | ThinkPad L390 20NSS1YV0B    | [bf3209df55](https://linux-hardware.org/?probe=bf3209df55) | Oct 07, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [03ba78f145](https://linux-hardware.org/?probe=03ba78f145) | Oct 04, 2021 |
| ASUSTek       | N76VZ                       | [8e260cdbc8](https://linux-hardware.org/?probe=8e260cdbc8) | Oct 04, 2021 |
| ASUSTek       | N76VZ                       | [94e6fbc140](https://linux-hardware.org/?probe=94e6fbc140) | Oct 03, 2021 |
| Google        | Pantheon                    | [72ded95fab](https://linux-hardware.org/?probe=72ded95fab) | Oct 02, 2021 |
| HP            | ProBook 470 G5              | [fef4cfba03](https://linux-hardware.org/?probe=fef4cfba03) | Oct 02, 2021 |
| Notebook      | NH5x_NH7xHP                 | [f6fd6bd3dc](https://linux-hardware.org/?probe=f6fd6bd3dc) | Oct 02, 2021 |
| Notebook      | NH5x_NH7xHP                 | [fbcd6bfe42](https://linux-hardware.org/?probe=fbcd6bfe42) | Oct 02, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [fbade9e61e](https://linux-hardware.org/?probe=fbade9e61e) | Oct 01, 2021 |
| ASUSTek       | X555LJ                      | [dea4201e98](https://linux-hardware.org/?probe=dea4201e98) | Oct 01, 2021 |
| Notebook      | P7xxTM1                     | [a63472fe1d](https://linux-hardware.org/?probe=a63472fe1d) | Sep 30, 2021 |
| Dell          | Precision 3561              | [59bbb944c2](https://linux-hardware.org/?probe=59bbb944c2) | Sep 29, 2021 |
| HP            | Elite x2 1012 G1            | [90cbd6d0a7](https://linux-hardware.org/?probe=90cbd6d0a7) | Sep 26, 2021 |
| Apple         | MacBookPro16,2              | [f1c5cf0c43](https://linux-hardware.org/?probe=f1c5cf0c43) | Sep 25, 2021 |
| ASUSTek       | N56VZ                       | [824dc21fac](https://linux-hardware.org/?probe=824dc21fac) | Sep 23, 2021 |
| ASUSTek       | N56VZ                       | [6c4623e356](https://linux-hardware.org/?probe=6c4623e356) | Sep 23, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [81c1403674](https://linux-hardware.org/?probe=81c1403674) | Sep 22, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [710301deba](https://linux-hardware.org/?probe=710301deba) | Sep 22, 2021 |
| Google        | Pantheon                    | [eaa5a17c4b](https://linux-hardware.org/?probe=eaa5a17c4b) | Sep 19, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [67449a33dc](https://linux-hardware.org/?probe=67449a33dc) | Sep 18, 2021 |
| ASUSTek       | X540SA                      | [177c537ae0](https://linux-hardware.org/?probe=177c537ae0) | Sep 17, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [094059270a](https://linux-hardware.org/?probe=094059270a) | Sep 16, 2021 |
| HP            | EliteBook 6930p             | [8f38de340d](https://linux-hardware.org/?probe=8f38de340d) | Sep 15, 2021 |
| Dell          | Inspiron 14-3452            | [ec9da4ca73](https://linux-hardware.org/?probe=ec9da4ca73) | Sep 14, 2021 |
| Lenovo        | ThinkPad T61 7659AB7        | [3c213b818b](https://linux-hardware.org/?probe=3c213b818b) | Sep 14, 2021 |
| Lenovo        | ThinkPad X390 20Q00058MH    | [01755fd33c](https://linux-hardware.org/?probe=01755fd33c) | Sep 13, 2021 |
| Medion        | WIM2140                     | [cf2f9bdca7](https://linux-hardware.org/?probe=cf2f9bdca7) | Sep 12, 2021 |
| Medion        | WIM2140                     | [0023f88625](https://linux-hardware.org/?probe=0023f88625) | Sep 12, 2021 |
| ASUSTek       | F70SL                       | [32a3e01bbd](https://linux-hardware.org/?probe=32a3e01bbd) | Sep 12, 2021 |
| ASUSTek       | F70SL                       | [4db3ac07eb](https://linux-hardware.org/?probe=4db3ac07eb) | Sep 12, 2021 |
| Notebook      | NJ5x_NJ7xLU                 | [4d544fc5d5](https://linux-hardware.org/?probe=4d544fc5d5) | Sep 09, 2021 |
| Acer          | Aspire A514-53              | [a4c57ccf99](https://linux-hardware.org/?probe=a4c57ccf99) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| Dell          | Latitude 5520               | [7e327f4604](https://linux-hardware.org/?probe=7e327f4604) | Sep 09, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [6d55ad062f](https://linux-hardware.org/?probe=6d55ad062f) | Sep 08, 2021 |
| Lenovo        | Z50-70 20354                | [cfcaf524be](https://linux-hardware.org/?probe=cfcaf524be) | Sep 07, 2021 |
| Dell          | Inspiron 1010               | [ee05ebef50](https://linux-hardware.org/?probe=ee05ebef50) | Sep 07, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [a47848e559](https://linux-hardware.org/?probe=a47848e559) | Sep 07, 2021 |
| Dell          | Inspiron 1010               | [8805be4e5c](https://linux-hardware.org/?probe=8805be4e5c) | Sep 07, 2021 |
| ASUSTek       | K53U                        | [a2f8f1be7d](https://linux-hardware.org/?probe=a2f8f1be7d) | Sep 04, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [f1b58d72ac](https://linux-hardware.org/?probe=f1b58d72ac) | Aug 31, 2021 |
| Dell          | Vostro 3300                 | [7d86f3f367](https://linux-hardware.org/?probe=7d86f3f367) | Aug 31, 2021 |
| Dell          | Vostro 3300                 | [be8b05e2a2](https://linux-hardware.org/?probe=be8b05e2a2) | Aug 31, 2021 |
| HP            | Pavilion 17                 | [ca125d2f3c](https://linux-hardware.org/?probe=ca125d2f3c) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | [0edc78c136](https://linux-hardware.org/?probe=0edc78c136) | Aug 28, 2021 |
| YJKC          | vBOOK Plus RVP7             | [8c051a0ce9](https://linux-hardware.org/?probe=8c051a0ce9) | Aug 26, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [994e94defa](https://linux-hardware.org/?probe=994e94defa) | Aug 26, 2021 |
| HP            | Laptop 14s-fq0xxx           | [ad12a8f4b5](https://linux-hardware.org/?probe=ad12a8f4b5) | Aug 26, 2021 |
| Dell          | Latitude E5440              | [ed4911006a](https://linux-hardware.org/?probe=ed4911006a) | Aug 23, 2021 |
| Lenovo        | Z50-70 20354                | [5fcfdd2678](https://linux-hardware.org/?probe=5fcfdd2678) | Aug 20, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP            | ProBook 430 G1              | [9567d77449](https://linux-hardware.org/?probe=9567d77449) | Aug 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [05e4a8bcb2](https://linux-hardware.org/?probe=05e4a8bcb2) | Aug 16, 2021 |
| Dell          | XPS 17 9700                 | [0c38591981](https://linux-hardware.org/?probe=0c38591981) | Aug 16, 2021 |
| HP            | Compaq 8710w                | [1e1d518b29](https://linux-hardware.org/?probe=1e1d518b29) | Aug 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [71645376f3](https://linux-hardware.org/?probe=71645376f3) | Aug 13, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [eb8c86aba1](https://linux-hardware.org/?probe=eb8c86aba1) | Aug 13, 2021 |
| HP            | ProBook 6460b               | [83029580f3](https://linux-hardware.org/?probe=83029580f3) | Aug 11, 2021 |
| Acer          | Swift SF314-54G             | [0cf6373ba8](https://linux-hardware.org/?probe=0cf6373ba8) | Aug 10, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1a27b7d75c](https://linux-hardware.org/?probe=1a27b7d75c) | Aug 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f2c3f335f8](https://linux-hardware.org/?probe=f2c3f335f8) | Aug 09, 2021 |
| Dell          | Latitude 5500               | [7cb9c5d946](https://linux-hardware.org/?probe=7cb9c5d946) | Aug 09, 2021 |
| HP            | ProBook 430 G1              | [f7438f6cab](https://linux-hardware.org/?probe=f7438f6cab) | Aug 08, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [798feee097](https://linux-hardware.org/?probe=798feee097) | Aug 07, 2021 |
| Lenovo        | B40-30 80F1                 | [d7f9ec3de6](https://linux-hardware.org/?probe=d7f9ec3de6) | Aug 06, 2021 |
| HP            | ProBook 4540s               | [52b0186956](https://linux-hardware.org/?probe=52b0186956) | Aug 06, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [6af058344f](https://linux-hardware.org/?probe=6af058344f) | Aug 06, 2021 |
| Dell          | Latitude E6420              | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Acer          | Aspire ES1-111              | [5f5802297c](https://linux-hardware.org/?probe=5f5802297c) | Aug 05, 2021 |
| Acer          | Swift SF314-54G             | [3bca4552ab](https://linux-hardware.org/?probe=3bca4552ab) | Aug 04, 2021 |
| Acer          | Swift SF314-54G             | [8076357ae9](https://linux-hardware.org/?probe=8076357ae9) | Aug 03, 2021 |
| Lenovo        | ThinkPad T520 4243AP1       | [f1773945f2](https://linux-hardware.org/?probe=f1773945f2) | Aug 02, 2021 |
| HP            | OMEN by Laptop              | [7ca0de35b4](https://linux-hardware.org/?probe=7ca0de35b4) | Aug 01, 2021 |
| ASUSTek       | UX305CA                     | [7fec0c7d28](https://linux-hardware.org/?probe=7fec0c7d28) | Aug 01, 2021 |
| HP            | Pavilion dv7                | [2966b0fcc3](https://linux-hardware.org/?probe=2966b0fcc3) | Jul 31, 2021 |
| Dell          | Latitude E6530              | [3318146af3](https://linux-hardware.org/?probe=3318146af3) | Jul 31, 2021 |
| Dell          | XPS 15 7590                 | [b423307c7c](https://linux-hardware.org/?probe=b423307c7c) | Jul 28, 2021 |
| Toshiba       | Satellite C850D-11K         | [c442634262](https://linux-hardware.org/?probe=c442634262) | Jul 24, 2021 |
| Lenovo        | ThinkPad L580 20LXS4K600    | [fc8ad7a780](https://linux-hardware.org/?probe=fc8ad7a780) | Jul 20, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [1a3712c974](https://linux-hardware.org/?probe=1a3712c974) | Jul 19, 2021 |
| HP            | Laptop 17-by4xxx            | [d66405d958](https://linux-hardware.org/?probe=d66405d958) | Jul 19, 2021 |
| HP            | Pavilion Notebook           | [40d1ea391b](https://linux-hardware.org/?probe=40d1ea391b) | Jul 17, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [167ddb49ce](https://linux-hardware.org/?probe=167ddb49ce) | Jul 16, 2021 |
| HP            | Laptop 17-by4xxx            | [460e87a27d](https://linux-hardware.org/?probe=460e87a27d) | Jul 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [cb44035a70](https://linux-hardware.org/?probe=cb44035a70) | Jul 13, 2021 |
| HP            | Pavilion Notebook           | [0b23e90cfc](https://linux-hardware.org/?probe=0b23e90cfc) | Jul 12, 2021 |
| HP            | Laptop 17-by4xxx            | [fad62f8ce2](https://linux-hardware.org/?probe=fad62f8ce2) | Jul 08, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [cc542d5a92](https://linux-hardware.org/?probe=cc542d5a92) | Jul 07, 2021 |
| HP            | Laptop 17-by4xxx            | [bd9ce451e8](https://linux-hardware.org/?probe=bd9ce451e8) | Jul 07, 2021 |
| Dell          | Latitude D530               | [daf9b88063](https://linux-hardware.org/?probe=daf9b88063) | Jul 06, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [b083bc08c4](https://linux-hardware.org/?probe=b083bc08c4) | Jul 04, 2021 |
| Dell          | XPS 15 9570                 | [f8f823ef89](https://linux-hardware.org/?probe=f8f823ef89) | Jul 02, 2021 |
| Acer          | Aspire E5-771G              | [75dbf43fd0](https://linux-hardware.org/?probe=75dbf43fd0) | Jul 02, 2021 |
| Acer          | Aspire 5250                 | [4a9dcc3234](https://linux-hardware.org/?probe=4a9dcc3234) | Jul 01, 2021 |
| Sony          | SVE1713Y1EB                 | [dfe0f426a0](https://linux-hardware.org/?probe=dfe0f426a0) | Jun 28, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [39f7878023](https://linux-hardware.org/?probe=39f7878023) | Jun 28, 2021 |
| Acer          | Swift SF114-32              | [016ae4ca5b](https://linux-hardware.org/?probe=016ae4ca5b) | Jun 26, 2021 |
| Packard Be... | EasyNote LV44HC             | [a02e170d18](https://linux-hardware.org/?probe=a02e170d18) | Jun 26, 2021 |
| HP            | Compaq 8710w                | [ee58ebb902](https://linux-hardware.org/?probe=ee58ebb902) | Jun 24, 2021 |
| Acer          | Aspire A314-22              | [195778fcc3](https://linux-hardware.org/?probe=195778fcc3) | Jun 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2ddbaed76b](https://linux-hardware.org/?probe=2ddbaed76b) | Jun 21, 2021 |
| Dell          | Latitude 5420               | [1356be4391](https://linux-hardware.org/?probe=1356be4391) | Jun 18, 2021 |
| Dell          | Latitude E5570              | [e73c4bfd97](https://linux-hardware.org/?probe=e73c4bfd97) | Jun 18, 2021 |
| Fujitsu       | FMVE01004                   | [ae55084eb8](https://linux-hardware.org/?probe=ae55084eb8) | Jun 17, 2021 |
| HP            | EliteBook 8740w             | [9b54339e9b](https://linux-hardware.org/?probe=9b54339e9b) | Jun 16, 2021 |
| HP            | EliteBook 8740w             | [9ad5884fca](https://linux-hardware.org/?probe=9ad5884fca) | Jun 16, 2021 |
| Lenovo        | ThinkPad Helix 37027L8      | [7aebf5c1e1](https://linux-hardware.org/?probe=7aebf5c1e1) | Jun 15, 2021 |
| Dell          | Latitude E6330              | [69619cc6a0](https://linux-hardware.org/?probe=69619cc6a0) | Jun 12, 2021 |
| Dell          | Latitude E5570              | [d0c559ce72](https://linux-hardware.org/?probe=d0c559ce72) | Jun 12, 2021 |
| Acer          | Aspire 5100                 | [47cb66adb9](https://linux-hardware.org/?probe=47cb66adb9) | Jun 11, 2021 |
| Acer          | Aspire 5100                 | [d7758e5c1c](https://linux-hardware.org/?probe=d7758e5c1c) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Dell          | Latitude 7390               | [38724f6fd8](https://linux-hardware.org/?probe=38724f6fd8) | Jun 11, 2021 |
| Lenovo        | ThinkPad L540 20AV0031MB    | [fa116a8e6d](https://linux-hardware.org/?probe=fa116a8e6d) | Jun 11, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [53af8c5600](https://linux-hardware.org/?probe=53af8c5600) | Jun 09, 2021 |
| ASUSTek       | K50IJ                       | [5ca8108e62](https://linux-hardware.org/?probe=5ca8108e62) | Jun 09, 2021 |
| HP            | ProBook 4730s               | [2e561b3995](https://linux-hardware.org/?probe=2e561b3995) | Jun 09, 2021 |
| ASUSTek       | X510UQ                      | [78ae37cf88](https://linux-hardware.org/?probe=78ae37cf88) | Jun 09, 2021 |
| Acer          | Aspire E5-771G              | [292f75ec92](https://linux-hardware.org/?probe=292f75ec92) | Jun 08, 2021 |
| HP            | ProBook 470 G5              | [517c800c42](https://linux-hardware.org/?probe=517c800c42) | Jun 07, 2021 |
| Apple         | MacBookPro11,1              | [f6f2cf5f89](https://linux-hardware.org/?probe=f6f2cf5f89) | Jun 05, 2021 |
| ASUSTek       | N76VJ                       | [278ef790cf](https://linux-hardware.org/?probe=278ef790cf) | Jun 05, 2021 |
| ASUSTek       | X302LA                      | [437c3c84e2](https://linux-hardware.org/?probe=437c3c84e2) | Jun 04, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | [6b168c2c19](https://linux-hardware.org/?probe=6b168c2c19) | Jun 03, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [1fa6a4756a](https://linux-hardware.org/?probe=1fa6a4756a) | Jun 02, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [6b6205bc5d](https://linux-hardware.org/?probe=6b6205bc5d) | May 31, 2021 |
| Toshiba       | Satellite C670-17D          | [57b6c4f249](https://linux-hardware.org/?probe=57b6c4f249) | May 31, 2021 |
| Gigabyte      | Spring Peak                 | [20896c9bef](https://linux-hardware.org/?probe=20896c9bef) | May 29, 2021 |
| HP            | EliteBook 8440p             | [66a3f34824](https://linux-hardware.org/?probe=66a3f34824) | May 28, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [80fe8cc363](https://linux-hardware.org/?probe=80fe8cc363) | May 28, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [70849260b4](https://linux-hardware.org/?probe=70849260b4) | May 28, 2021 |
| HP            | EliteBook 8760w             | [dae07bf8cb](https://linux-hardware.org/?probe=dae07bf8cb) | May 26, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [065a3089d4](https://linux-hardware.org/?probe=065a3089d4) | May 24, 2021 |
| Samsung       | R780/R778                   | [3f35c907a2](https://linux-hardware.org/?probe=3f35c907a2) | May 21, 2021 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [6ca37bdf8b](https://linux-hardware.org/?probe=6ca37bdf8b) | May 21, 2021 |
| HP            | ProBook 6570b               | [2b341b7bf9](https://linux-hardware.org/?probe=2b341b7bf9) | May 21, 2021 |
| Acer          | Aspire 7750                 | [ecf8d0fa55](https://linux-hardware.org/?probe=ecf8d0fa55) | May 18, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [1579b9c9d7](https://linux-hardware.org/?probe=1579b9c9d7) | May 16, 2021 |
| Sony          | VPCEL1E1E                   | [33f8327bbe](https://linux-hardware.org/?probe=33f8327bbe) | May 13, 2021 |
| Sony          | VPCEL1E1E                   | [4e53335200](https://linux-hardware.org/?probe=4e53335200) | May 13, 2021 |
| Toshiba       | Satellite L855              | [70615b0780](https://linux-hardware.org/?probe=70615b0780) | May 12, 2021 |
| ASUSTek       | N53SN                       | [63b3bf3fd2](https://linux-hardware.org/?probe=63b3bf3fd2) | May 11, 2021 |
| Dell          | Latitude E5470              | [9ed0c349f9](https://linux-hardware.org/?probe=9ed0c349f9) | May 10, 2021 |
| Notebook      | P7xxDM3(-G)                 | [31cd72db1b](https://linux-hardware.org/?probe=31cd72db1b) | May 08, 2021 |
| ASUSTek       | N76VJ                       | [3b614f915c](https://linux-hardware.org/?probe=3b614f915c) | May 08, 2021 |
| HP            | ZBook 15 G6                 | [ea363ea07e](https://linux-hardware.org/?probe=ea363ea07e) | May 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6654328a0f](https://linux-hardware.org/?probe=6654328a0f) | May 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [48ff783788](https://linux-hardware.org/?probe=48ff783788) | May 05, 2021 |
| Lenovo        | G710 20252                  | [e77f1af187](https://linux-hardware.org/?probe=e77f1af187) | May 04, 2021 |
| HP            | ProBook 450 G0              | [f1828f8b3a](https://linux-hardware.org/?probe=f1828f8b3a) | May 03, 2021 |
| Dell          | Latitude E5570              | [497144cda8](https://linux-hardware.org/?probe=497144cda8) | Apr 23, 2021 |
| Dell          | XPS 13 9310                 | [3d4e2aaf41](https://linux-hardware.org/?probe=3d4e2aaf41) | Apr 22, 2021 |
| Toshiba       | Satellite C660              | [12faeec33f](https://linux-hardware.org/?probe=12faeec33f) | Apr 21, 2021 |
| Notebook      | N85_N87HCHN                 | [9a08ae1df0](https://linux-hardware.org/?probe=9a08ae1df0) | Apr 19, 2021 |
| Dell          | Latitude E4310              | [4135cd0970](https://linux-hardware.org/?probe=4135cd0970) | Apr 19, 2021 |
| HP            | ProBook 470 G5              | [1f0b5b042f](https://linux-hardware.org/?probe=1f0b5b042f) | Apr 18, 2021 |
| Acer          | Aspire E5-771G              | [eb63a6bb36](https://linux-hardware.org/?probe=eb63a6bb36) | Apr 17, 2021 |
| Acer          | Aspire E5-771G              | [e3bc507a07](https://linux-hardware.org/?probe=e3bc507a07) | Apr 17, 2021 |
| Notebook      | P7xxDM3(-G)                 | [7049a12bef](https://linux-hardware.org/?probe=7049a12bef) | Apr 17, 2021 |
| Intel         | ChiefRiver                  | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| Acer          | TravelMate 5720             | [4de4816949](https://linux-hardware.org/?probe=4de4816949) | Apr 14, 2021 |
| HP            | ProBook 650 G1              | [ce6e255493](https://linux-hardware.org/?probe=ce6e255493) | Apr 13, 2021 |
| HP            | Compaq 6830s                | [5b4a790a78](https://linux-hardware.org/?probe=5b4a790a78) | Apr 13, 2021 |
| HP            | Compaq 6830s                | [ff3b0f8b69](https://linux-hardware.org/?probe=ff3b0f8b69) | Apr 10, 2021 |
| TrekStor      | Notebook Slim S130          | [15a723bc0a](https://linux-hardware.org/?probe=15a723bc0a) | Apr 10, 2021 |
| Standard      | Unknown                     | [2e2b5648ce](https://linux-hardware.org/?probe=2e2b5648ce) | Apr 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [ff08d60192](https://linux-hardware.org/?probe=ff08d60192) | Apr 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0DP0... | [8bca9f26df](https://linux-hardware.org/?probe=8bca9f26df) | Apr 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0DP0... | [f04bf70e2c](https://linux-hardware.org/?probe=f04bf70e2c) | Apr 09, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | [59d83c563e](https://linux-hardware.org/?probe=59d83c563e) | Apr 09, 2021 |
| Dell          | Latitude E7440              | [9d9a93a1e7](https://linux-hardware.org/?probe=9d9a93a1e7) | Apr 08, 2021 |
| Dell          | Latitude E6330              | [46855c6116](https://linux-hardware.org/?probe=46855c6116) | Apr 07, 2021 |
| Dell          | Latitude E7440              | [882711c39c](https://linux-hardware.org/?probe=882711c39c) | Apr 06, 2021 |
| Dell          | Latitude E7440              | [5cc52e4eb3](https://linux-hardware.org/?probe=5cc52e4eb3) | Apr 06, 2021 |
| Acer          | Aspire 7250                 | [e362ae4b3e](https://linux-hardware.org/?probe=e362ae4b3e) | Apr 05, 2021 |
| Acer          | Aspire 7250                 | [fe6bc9b5b9](https://linux-hardware.org/?probe=fe6bc9b5b9) | Apr 05, 2021 |
| ASUSTek       | PU551LA                     | [6a492952ec](https://linux-hardware.org/?probe=6a492952ec) | Apr 04, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [6e7b77b0ee](https://linux-hardware.org/?probe=6e7b77b0ee) | Mar 31, 2021 |
| Dell          | XPS 17 9700                 | [339118d4e1](https://linux-hardware.org/?probe=339118d4e1) | Mar 31, 2021 |
| Dell          | XPS 17 9700                 | [65c6679e82](https://linux-hardware.org/?probe=65c6679e82) | Mar 31, 2021 |
| ASUSTek       | X540LA                      | [280ac2515b](https://linux-hardware.org/?probe=280ac2515b) | Mar 29, 2021 |
| ASUSTek       | X540LA                      | [d454811086](https://linux-hardware.org/?probe=d454811086) | Mar 29, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [4d05114173](https://linux-hardware.org/?probe=4d05114173) | Mar 28, 2021 |
| ASUSTek       | K52F                        | [ca51314e8c](https://linux-hardware.org/?probe=ca51314e8c) | Mar 28, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [39d2fcc25c](https://linux-hardware.org/?probe=39d2fcc25c) | Mar 28, 2021 |
| Sony          | VGN-CR19VN_B                | [fb82fced50](https://linux-hardware.org/?probe=fb82fced50) | Mar 27, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | [0b66d1d8d9](https://linux-hardware.org/?probe=0b66d1d8d9) | Mar 25, 2021 |
| HP            | Pavilion dv9000 (RP921EA... | [f39a330574](https://linux-hardware.org/?probe=f39a330574) | Mar 23, 2021 |
| HP            | Pavilion dv9000 (RP921EA... | [d04fc0aa98](https://linux-hardware.org/?probe=d04fc0aa98) | Mar 23, 2021 |
| Dell          | Latitude 7410               | [0805fdaa75](https://linux-hardware.org/?probe=0805fdaa75) | Mar 22, 2021 |
| Toshiba       | Satellite Pro A120          | [8a4710b123](https://linux-hardware.org/?probe=8a4710b123) | Mar 21, 2021 |
| Packard Be... | EasyNote_BG35-V-003BE       | [a3828dac52](https://linux-hardware.org/?probe=a3828dac52) | Mar 20, 2021 |
| Acer          | Aspire V3-771               | [6b0de26926](https://linux-hardware.org/?probe=6b0de26926) | Mar 19, 2021 |
| Acer          | Aspire 5755G                | [0984c7aebc](https://linux-hardware.org/?probe=0984c7aebc) | Mar 18, 2021 |
| Intel         | Tiger Lake Client Platfo... | [da214bbadb](https://linux-hardware.org/?probe=da214bbadb) | Mar 18, 2021 |
| HP            | EliteBook 850 G2            | [29665bb834](https://linux-hardware.org/?probe=29665bb834) | Mar 18, 2021 |
| HP            | EliteBook 850 G2            | [95d306f933](https://linux-hardware.org/?probe=95d306f933) | Mar 18, 2021 |
| Lenovo        | ThinkPad T495 20NKS0VY00    | [a30ff468ab](https://linux-hardware.org/?probe=a30ff468ab) | Mar 17, 2021 |
| Lenovo        | ThinkPad T495 20NKS0VY00    | [f8f4ebd88a](https://linux-hardware.org/?probe=f8f4ebd88a) | Mar 17, 2021 |
| Lenovo        | ThinkPad T430 2349GZG       | [592556c996](https://linux-hardware.org/?probe=592556c996) | Mar 17, 2021 |
| Lenovo        | ThinkPad T590 20N4004UMB    | [7746d65773](https://linux-hardware.org/?probe=7746d65773) | Mar 15, 2021 |
| HP            | ProBook 470 G5              | [ea759927d7](https://linux-hardware.org/?probe=ea759927d7) | Mar 13, 2021 |
| Medion        | S6421 MD60909               | [f43e4c999a](https://linux-hardware.org/?probe=f43e4c999a) | Mar 13, 2021 |
| Medion        | S6421 MD60909               | [7b1a21032f](https://linux-hardware.org/?probe=7b1a21032f) | Mar 12, 2021 |
| Dell          | XPS 13 7390                 | [49fa91c316](https://linux-hardware.org/?probe=49fa91c316) | Mar 10, 2021 |
| Dell          | XPS 13 7390                 | [7734e8dfb6](https://linux-hardware.org/?probe=7734e8dfb6) | Mar 10, 2021 |
| HP            | ProBook 6460b               | [d2997a258f](https://linux-hardware.org/?probe=d2997a258f) | Mar 09, 2021 |
| HP            | ProBook 6460b               | [9426162f4a](https://linux-hardware.org/?probe=9426162f4a) | Mar 09, 2021 |
| Acer          | Aspire 5755G                | [6fc4ecf2e5](https://linux-hardware.org/?probe=6fc4ecf2e5) | Mar 09, 2021 |
| Acer          | Aspire 5755G                | [861fb95171](https://linux-hardware.org/?probe=861fb95171) | Mar 09, 2021 |
| HP            | Compaq Presario CQ60        | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Sony          | VPCF23P1E                   | [5a1b84993b](https://linux-hardware.org/?probe=5a1b84993b) | Mar 03, 2021 |
| Lenovo        | ThinkPad T420s 4174CN5      | [d781333e25](https://linux-hardware.org/?probe=d781333e25) | Mar 03, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [17164e2111](https://linux-hardware.org/?probe=17164e2111) | Mar 03, 2021 |
| Dell          | Precision M3800             | [946b253122](https://linux-hardware.org/?probe=946b253122) | Mar 03, 2021 |
| Dell          | Latitude E7470              | [7edde637cc](https://linux-hardware.org/?probe=7edde637cc) | Mar 02, 2021 |
| Dell          | Inspiron 5521               | [dbf7e551cd](https://linux-hardware.org/?probe=dbf7e551cd) | Mar 01, 2021 |
| Dell          | Inspiron 5521               | [7073ff4a30](https://linux-hardware.org/?probe=7073ff4a30) | Mar 01, 2021 |
| Fujitsu Si... | AMILO Li3910                | [2e91ff573c](https://linux-hardware.org/?probe=2e91ff573c) | Mar 01, 2021 |
| Fujitsu Si... | AMILO Li3910                | [c675742f98](https://linux-hardware.org/?probe=c675742f98) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK E554               | [422e106fbf](https://linux-hardware.org/?probe=422e106fbf) | Feb 28, 2021 |
| Clevo         | W35_37ET                    | [3082e61cbf](https://linux-hardware.org/?probe=3082e61cbf) | Feb 28, 2021 |
| Clevo         | W35_37ET                    | [cec3a7741f](https://linux-hardware.org/?probe=cec3a7741f) | Feb 28, 2021 |
| Lenovo        | ThinkPad T520 4243AP1       | [08f0761a98](https://linux-hardware.org/?probe=08f0761a98) | Feb 27, 2021 |
| Lenovo        | ThinkPad X230 23252P7       | [bc15b2e135](https://linux-hardware.org/?probe=bc15b2e135) | Feb 26, 2021 |
| HP            | ProBook 6570b               | [bf8cc9c3db](https://linux-hardware.org/?probe=bf8cc9c3db) | Feb 25, 2021 |
| HP            | HDX 16                      | [214dc69b28](https://linux-hardware.org/?probe=214dc69b28) | Feb 22, 2021 |
| HP            | Pavilion dv7                | [6761663105](https://linux-hardware.org/?probe=6761663105) | Feb 22, 2021 |
| HP            | ENVY Laptop 17-cg1xxx       | [280e648d24](https://linux-hardware.org/?probe=280e648d24) | Feb 21, 2021 |
| ASUSTek       | X541UA                      | [3539743457](https://linux-hardware.org/?probe=3539743457) | Feb 20, 2021 |
| ASUSTek       | X705NA                      | [0fd92654c8](https://linux-hardware.org/?probe=0fd92654c8) | Feb 19, 2021 |
| Sony          | VGN-FW21Z                   | [49af7bb079](https://linux-hardware.org/?probe=49af7bb079) | Feb 17, 2021 |
| Dell          | XPS 13 9343                 | [cdd5eb3377](https://linux-hardware.org/?probe=cdd5eb3377) | Feb 15, 2021 |
| Acer          | Aspire 5738                 | [a20559dfa9](https://linux-hardware.org/?probe=a20559dfa9) | Feb 15, 2021 |
| BLAUPUNKT     | Discovery 1011WI            | [d472298741](https://linux-hardware.org/?probe=d472298741) | Feb 14, 2021 |
| Dell          | XPS 13 9343                 | [b40b5302a0](https://linux-hardware.org/?probe=b40b5302a0) | Feb 14, 2021 |
| ASUSTek       | X541UA                      | [74216aff6a](https://linux-hardware.org/?probe=74216aff6a) | Feb 14, 2021 |
| Dell          | Inspiron 1750               | [142735e487](https://linux-hardware.org/?probe=142735e487) | Feb 14, 2021 |
| HP            | Compaq 6730b (GB987ET#UU... | [2ef76d4042](https://linux-hardware.org/?probe=2ef76d4042) | Feb 13, 2021 |
| ASUSTek       | X540SA                      | [1cd727b4e5](https://linux-hardware.org/?probe=1cd727b4e5) | Feb 13, 2021 |
| Medion        | P7612                       | [25bdf5c5e1](https://linux-hardware.org/?probe=25bdf5c5e1) | Feb 12, 2021 |
| Medion        | P7612                       | [dd2eae8c08](https://linux-hardware.org/?probe=dd2eae8c08) | Feb 12, 2021 |
| Dell          | Latitude E6500              | [200b4ad049](https://linux-hardware.org/?probe=200b4ad049) | Feb 11, 2021 |
| HP            | ProBook 470 G5              | [980c47c7e1](https://linux-hardware.org/?probe=980c47c7e1) | Feb 08, 2021 |
| Intel         | Skylake Platform            | [c3772356cc](https://linux-hardware.org/?probe=c3772356cc) | Feb 08, 2021 |
| Dell          | XPS 13 7390                 | [8da49e5276](https://linux-hardware.org/?probe=8da49e5276) | Feb 07, 2021 |
| ASUSTek       | X541UA                      | [195a92067a](https://linux-hardware.org/?probe=195a92067a) | Feb 07, 2021 |
| Toshiba       | Satellite S50-B             | [0603c22e84](https://linux-hardware.org/?probe=0603c22e84) | Feb 07, 2021 |
| Dell          | G3 3779                     | [363e754d51](https://linux-hardware.org/?probe=363e754d51) | Feb 06, 2021 |
| ASUSTek       | 1005HA                      | [3271c9fcf1](https://linux-hardware.org/?probe=3271c9fcf1) | Feb 04, 2021 |
| BLAUPUNKT     | Discovery 1011WI            | [11caa65562](https://linux-hardware.org/?probe=11caa65562) | Jan 31, 2021 |
| Dell          | XPS 17 9700                 | [ddff47f92b](https://linux-hardware.org/?probe=ddff47f92b) | Jan 31, 2021 |
| HP            | EliteBook 840 G1            | [18d0877f0f](https://linux-hardware.org/?probe=18d0877f0f) | Jan 31, 2021 |
| Dell          | Studio 1737                 | [3550b981dd](https://linux-hardware.org/?probe=3550b981dd) | Jan 31, 2021 |
| Dell          | Inspiron 5370               | [c4fc1198ca](https://linux-hardware.org/?probe=c4fc1198ca) | Jan 31, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0ea19084de](https://linux-hardware.org/?probe=0ea19084de) | Jan 29, 2021 |
| Toshiba       | Satellite L670              | [cf01b0dc10](https://linux-hardware.org/?probe=cf01b0dc10) | Jan 29, 2021 |
| Notebook      | NV4XMZ                      | [85227cca30](https://linux-hardware.org/?probe=85227cca30) | Jan 28, 2021 |
| Acer          | Aspire E5-571               | [2855a371c3](https://linux-hardware.org/?probe=2855a371c3) | Jan 24, 2021 |
| BLAUPUNKT     | Discovery 1011WI            | [ca7bef1a68](https://linux-hardware.org/?probe=ca7bef1a68) | Jan 24, 2021 |
| Lenovo        | Yoga 300-11IBY 80M0         | [73ac79ea35](https://linux-hardware.org/?probe=73ac79ea35) | Jan 24, 2021 |
| HP            | ZBook Studio G4             | [83f8b119c5](https://linux-hardware.org/?probe=83f8b119c5) | Jan 23, 2021 |
| Dell          | Inspiron 7520               | [145f521d9a](https://linux-hardware.org/?probe=145f521d9a) | Jan 22, 2021 |
| Medion        | E7222                       | [c5b59cdd1a](https://linux-hardware.org/?probe=c5b59cdd1a) | Jan 21, 2021 |
| HP            | ZBook Studio G4             | [b4828f90e1](https://linux-hardware.org/?probe=b4828f90e1) | Jan 21, 2021 |
| Apple         | MacBookAir7,2               | [da811652ff](https://linux-hardware.org/?probe=da811652ff) | Jan 20, 2021 |
| ASUSTek       | X200CA                      | [90675c7c5d](https://linux-hardware.org/?probe=90675c7c5d) | Jan 16, 2021 |
| Dell          | XPS 13 9370                 | [ddd11f8f67](https://linux-hardware.org/?probe=ddd11f8f67) | Jan 15, 2021 |
| Dell          | XPS 13 9370                 | [3b42708115](https://linux-hardware.org/?probe=3b42708115) | Jan 15, 2021 |
| ASUSTek       | X55A                        | [bbac234938](https://linux-hardware.org/?probe=bbac234938) | Jan 14, 2021 |
| Samsung       | SQ1US                       | [c5b1d00d5a](https://linux-hardware.org/?probe=c5b1d00d5a) | Jan 14, 2021 |
| Samsung       | SQ1US                       | [b7c374caa7](https://linux-hardware.org/?probe=b7c374caa7) | Jan 14, 2021 |
| Samsung       | SQ1US                       | [38c340b504](https://linux-hardware.org/?probe=38c340b504) | Jan 13, 2021 |
| Dell          | Studio 1747                 | [1fe32f1f6c](https://linux-hardware.org/?probe=1fe32f1f6c) | Jan 12, 2021 |
| ASUSTek       | S400CA                      | [598845d6da](https://linux-hardware.org/?probe=598845d6da) | Jan 12, 2021 |
| ASUSTek       | S400CA                      | [ad5e96299b](https://linux-hardware.org/?probe=ad5e96299b) | Jan 12, 2021 |
| HP            | ProBook 450 G6              | [8cb1a97eeb](https://linux-hardware.org/?probe=8cb1a97eeb) | Jan 12, 2021 |
| Lenovo        | B590 62743BG                | [74e74ba835](https://linux-hardware.org/?probe=74e74ba835) | Jan 12, 2021 |
| Dell          | Latitude E7440              | [b941db31df](https://linux-hardware.org/?probe=b941db31df) | Jan 11, 2021 |
| Dell          | Latitude E7440              | [945b6f9fd9](https://linux-hardware.org/?probe=945b6f9fd9) | Jan 10, 2021 |
| ASUSTek       | X555LJ                      | [1b20a57823](https://linux-hardware.org/?probe=1b20a57823) | Jan 10, 2021 |
| ASUSTek       | X540SA                      | [f0e4a2ef6d](https://linux-hardware.org/?probe=f0e4a2ef6d) | Jan 07, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [ae395b2f7a](https://linux-hardware.org/?probe=ae395b2f7a) | Jan 06, 2021 |
| HP            | ProBook 6570b               | [cdd52e19bc](https://linux-hardware.org/?probe=cdd52e19bc) | Jan 03, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [4460990877](https://linux-hardware.org/?probe=4460990877) | Jan 02, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [3f3cc6b9d6](https://linux-hardware.org/?probe=3f3cc6b9d6) | Jan 02, 2021 |
| TUXEDO        | Unknown                     | [ab17e3576a](https://linux-hardware.org/?probe=ab17e3576a) | Jan 01, 2021 |
| Dell          | Inspiron 7537               | [0d0f758de9](https://linux-hardware.org/?probe=0d0f758de9) | Jan 01, 2021 |
| Dell          | XPS 13 7390                 | [e3c50af4ef](https://linux-hardware.org/?probe=e3c50af4ef) | Dec 31, 2020 |
| Medion        | S17402 MD63000              | [fba33aab51](https://linux-hardware.org/?probe=fba33aab51) | Dec 31, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e2599b8b3f](https://linux-hardware.org/?probe=e2599b8b3f) | Dec 30, 2020 |
| Acer          | Aspire 7250                 | [9495fc4339](https://linux-hardware.org/?probe=9495fc4339) | Dec 30, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belgium/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 160       | 14.29%  |
| Ubuntu 18.04                 | 82        | 7.32%   |
| Ubuntu 22.04                 | 60        | 5.36%   |
| ArcoLinux Rolling            | 27        | 2.41%   |
| Zorin 16                     | 25        | 2.23%   |
| Debian 11                    | 25        | 2.23%   |
| OpenMandriva 4.3             | 22        | 1.96%   |
| Linux Mint 20.3              | 21        | 1.88%   |
| OpenMandriva 4.2             | 20        | 1.79%   |
| Linux Mint 20.1              | 18        | 1.61%   |
| Manjaro                      | 17        | 1.52%   |
| Fedora 36                    | 17        | 1.52%   |
| Arch Rolling                 | 17        | 1.52%   |
| Ubuntu 19.10                 | 16        | 1.43%   |
| Arch                         | 16        | 1.43%   |
| Xubuntu 20.04                | 14        | 1.25%   |
| Linux Mint 20                | 14        | 1.25%   |
| OpenMandriva 23.01           | 13        | 1.16%   |
| Linux Mint 19.3              | 13        | 1.16%   |
| Fedora 38                    | 12        | 1.07%   |
| Ubuntu 20.10                 | 11        | 0.98%   |
| Pop!_OS 22.04                | 11        | 0.98%   |
| Pop!_OS 21.04                | 11        | 0.98%   |
| Pop!_OS 20.04                | 11        | 0.98%   |
| OpenMandriva 23.03           | 11        | 0.98%   |
| KDE neon 20.04               | 11        | 0.98%   |
| Ubuntu 19.04                 | 10        | 0.89%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.89%   |
| Fedora 34                    | 10        | 0.89%   |
| Fedora 32                    | 10        | 0.89%   |
| Elementary 6.1               | 10        | 0.89%   |
| Ubuntu 21.10                 | 9         | 0.8%    |
| Ubuntu 21.04                 | 9         | 0.8%    |
| Linux Mint 21.1              | 9         | 0.8%    |
| Linux Mint 20.2              | 9         | 0.8%    |
| Fedora 37                    | 9         | 0.8%    |
| Fedora 35                    | 9         | 0.8%    |
| Zorin 15                     | 8         | 0.71%   |
| ROSA R10                     | 8         | 0.71%   |
| Linux Mint 21                | 8         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 362       | 34.51%  |
| Linux Mint    | 99        | 9.44%   |
| OpenMandriva  | 71        | 6.77%   |
| Fedora        | 68        | 6.48%   |
| Debian        | 44        | 4.19%   |
| Pop!_OS       | 37        | 3.53%   |
| Zorin         | 35        | 3.34%   |
| Manjaro       | 35        | 3.34%   |
| Arch          | 32        | 3.05%   |
| Xubuntu       | 29        | 2.76%   |
| ArcoLinux     | 28        | 2.67%   |
| Kubuntu       | 27        | 2.57%   |
| ROSA          | 19        | 1.81%   |
| KDE neon      | 16        | 1.53%   |
| openSUSE      | 15        | 1.43%   |
| Ubuntu Unity  | 13        | 1.24%   |
| Lubuntu       | 13        | 1.24%   |
| Elementary    | 12        | 1.14%   |
| Ubuntu MATE   | 9         | 0.86%   |
| Gentoo        | 9         | 0.86%   |
| SteamOS       | 7         | 0.67%   |
| Kali          | 7         | 0.67%   |
| Endless       | 7         | 0.67%   |
| MX            | 5         | 0.48%   |
| EndeavourOS   | 5         | 0.48%   |
| CentOS        | 5         | 0.48%   |
| BlackPanther  | 5         | 0.48%   |
| Ubuntu Budgie | 4         | 0.38%   |
| LMDE          | 4         | 0.38%   |
| Clear Linux   | 4         | 0.38%   |
| LinuxFX       | 3         | 0.29%   |
| Garuda Linux  | 3         | 0.29%   |
| Rocky Linux   | 2         | 0.19%   |
| NixOS         | 2         | 0.19%   |
| Xero          | 1         | 0.1%    |
| Ultramarine   | 1         | 0.1%    |
| Solus         | 1         | 0.1%    |
| Reborn OS     | 1         | 0.1%    |
| Peppermint    | 1         | 0.1%    |
| Parrot        | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 21        | 1.69%   |
| 5.10.14-desktop-1omv4002 | 19        | 1.53%   |
| 5.4.0-42-generic         | 17        | 1.37%   |
| 5.4.0-58-generic         | 16        | 1.29%   |
| 5.3.0-42-generic         | 15        | 1.21%   |
| 5.4.0-48-generic         | 13        | 1.05%   |
| 6.2.6-desktop-1omv2390   | 11        | 0.89%   |
| 6.1.1-desktop-1omv2290   | 11        | 0.89%   |
| 5.4.0-66-generic         | 11        | 0.89%   |
| 5.15.0-56-generic        | 11        | 0.89%   |
| 5.15.0-48-generic        | 11        | 0.89%   |
| 5.4.0-29-generic         | 10        | 0.81%   |
| 5.3.0-46-generic         | 10        | 0.81%   |
| 5.15.0-58-generic        | 10        | 0.81%   |
| 5.15.0-46-generic        | 10        | 0.81%   |
| 5.8.0-43-generic         | 9         | 0.73%   |
| 5.15.0-52-generic        | 9         | 0.73%   |
| 5.11.0-43-generic        | 9         | 0.73%   |
| 5.10.0-21-amd64          | 9         | 0.73%   |
| 5.4.0-74-generic         | 8         | 0.64%   |
| 5.13.0-39-generic        | 8         | 0.64%   |
| 5.4.0-65-generic         | 7         | 0.56%   |
| 5.4.0-52-generic         | 7         | 0.56%   |
| 5.4.0-40-generic         | 7         | 0.56%   |
| 5.4.0-26-generic         | 7         | 0.56%   |
| 5.15.0-47-generic        | 7         | 0.56%   |
| 5.13.0-28-generic        | 7         | 0.56%   |
| 5.11.0-7620-generic      | 7         | 0.56%   |
| 5.11.0-38-generic        | 7         | 0.56%   |
| 5.10.0-20-amd64          | 7         | 0.56%   |
| 5.0.0-29-generic         | 7         | 0.56%   |
| 5.8.0-53-generic         | 6         | 0.48%   |
| 5.4.0-91-generic         | 6         | 0.48%   |
| 5.4.0-90-generic         | 6         | 0.48%   |
| 5.4.0-56-generic         | 6         | 0.48%   |
| 5.4.0-53-generic         | 6         | 0.48%   |
| 5.4.0-37-generic         | 6         | 0.48%   |
| 5.3.0-40-generic         | 6         | 0.48%   |
| 5.19.0-35-generic        | 6         | 0.48%   |
| 5.13.0-40-generic        | 6         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 199       | 17.11%  |
| 5.15.0  | 108       | 9.29%   |
| 5.11.0  | 68        | 5.85%   |
| 5.13.0  | 61        | 5.25%   |
| 5.8.0   | 58        | 4.99%   |
| 4.15.0  | 58        | 4.99%   |
| 5.3.0   | 49        | 4.21%   |
| 5.10.0  | 37        | 3.18%   |
| 5.19.0  | 32        | 2.75%   |
| 5.0.0   | 30        | 2.58%   |
| 5.16.7  | 21        | 1.81%   |
| 4.18.0  | 21        | 1.81%   |
| 5.10.14 | 19        | 1.63%   |
| 6.2.6   | 12        | 1.03%   |
| 6.1.1   | 11        | 0.95%   |
| 6.2.0   | 9         | 0.77%   |
| 5.17.5  | 6         | 0.52%   |
| 4.9.20  | 6         | 0.52%   |
| 4.19.0  | 6         | 0.52%   |
| 6.1.0   | 5         | 0.43%   |
| 6.0.0   | 5         | 0.43%   |
| 5.18.12 | 5         | 0.43%   |
| 4.18.16 | 5         | 0.43%   |
| 6.2.9   | 4         | 0.34%   |
| 6.2.8   | 4         | 0.34%   |
| 6.2.11  | 4         | 0.34%   |
| 6.0.12  | 4         | 0.34%   |
| 5.18.0  | 4         | 0.34%   |
| 5.16.0  | 4         | 0.34%   |
| 4.9.60  | 4         | 0.34%   |
| 4.4.0   | 4         | 0.34%   |
| 6.3.8   | 3         | 0.26%   |
| 6.0.8   | 3         | 0.26%   |
| 5.9.11  | 3         | 0.26%   |
| 5.8.5   | 3         | 0.26%   |
| 5.8.18  | 3         | 0.26%   |
| 5.4.8   | 3         | 0.26%   |
| 5.4.15  | 3         | 0.26%   |
| 5.3.18  | 3         | 0.26%   |
| 5.19.5  | 3         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 217       | 18.99%  |
| 5.15    | 128       | 11.2%   |
| 5.11    | 77        | 6.74%   |
| 5.8     | 71        | 6.21%   |
| 5.10    | 71        | 6.21%   |
| 5.13    | 70        | 6.12%   |
| 4.15    | 58        | 5.07%   |
| 5.3     | 55        | 4.81%   |
| 5.19    | 44        | 3.85%   |
| 6.2     | 40        | 3.5%    |
| 5.16    | 38        | 3.32%   |
| 5.0     | 32        | 2.8%    |
| 6.1     | 27        | 2.36%   |
| 4.18    | 27        | 2.36%   |
| 6.0     | 22        | 1.92%   |
| 5.18    | 22        | 1.92%   |
| 5.17    | 22        | 1.92%   |
| 5.12    | 15        | 1.31%   |
| 4.9     | 15        | 1.31%   |
| 5.14    | 14        | 1.22%   |
| 6.3     | 12        | 1.05%   |
| 5.6     | 12        | 1.05%   |
| 5.9     | 10        | 0.87%   |
| 4.19    | 10        | 0.87%   |
| 5.7     | 8         | 0.7%    |
| 6.4     | 5         | 0.44%   |
| 5.5     | 5         | 0.44%   |
| 4.4     | 4         | 0.35%   |
| 5.1     | 3         | 0.26%   |
| 5.2     | 2         | 0.17%   |
| 4.17    | 2         | 0.17%   |
| 4.1     | 2         | 0.17%   |
| 4.13    | 1         | 0.09%   |
| 4.12    | 1         | 0.09%   |
| 4.10    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 974       | 96.92%  |
| i686   | 31        | 3.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 464       | 43.45%  |
| KDE5             | 171       | 16.01%  |
| Unknown          | 121       | 11.33%  |
| XFCE             | 88        | 8.24%   |
| X-Cinnamon       | 69        | 6.46%   |
| MATE             | 32        | 3%      |
| KDE              | 20        | 1.87%   |
| LXQt             | 15        | 1.4%    |
| Unity            | 13        | 1.22%   |
| Pantheon         | 12        | 1.12%   |
| KDE4             | 11        | 1.03%   |
| i3               | 10        | 0.94%   |
| Cinnamon         | 10        | 0.94%   |
| Budgie           | 9         | 0.84%   |
| sway             | 3         | 0.28%   |
| LXDE             | 2         | 0.19%   |
| LeftWM           | 2         | 0.19%   |
| Hyprland         | 2         | 0.19%   |
| GNOME Flashback  | 2         | 0.19%   |
| bspwm            | 2         | 0.19%   |
| awesome          | 2         | 0.19%   |
| xmonad           | 1         | 0.09%   |
| spectrwm         | 1         | 0.09%   |
| qtile            | 1         | 0.09%   |
| Openbox          | 1         | 0.09%   |
| lightdm-xsession | 1         | 0.09%   |
| icewm            | 1         | 0.09%   |
| Enlightenment    | 1         | 0.09%   |
| Deepin           | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 789       | 75.94%  |
| Wayland | 175       | 16.84%  |
| Unknown | 68        | 6.54%   |
| Tty     | 7         | 0.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 494       | 46.69%  |
| SDDM    | 173       | 16.35%  |
| GDM     | 136       | 12.85%  |
| GDM3    | 115       | 10.87%  |
| LightDM | 89        | 8.41%   |
| TDM     | 37        | 3.5%    |
| KDM     | 11        | 1.04%   |
| XDM     | 2         | 0.19%   |
| SLiM    | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 350       | 33.59%  |
| fr_BE      | 181       | 17.37%  |
| nl_BE      | 146       | 14.01%  |
| Unknown    | 121       | 11.61%  |
| en_GB      | 62        | 5.95%   |
| nl_NL      | 53        | 5.09%   |
| fr_FR      | 51        | 4.89%   |
| C          | 14        | 1.34%   |
| de_DE      | 13        | 1.25%   |
| de_BE      | 7         | 0.67%   |
| ru_RU      | 5         | 0.48%   |
| pl_PL      | 5         | 0.48%   |
| es_ES      | 4         | 0.38%   |
| ro_RO      | 3         | 0.29%   |
| pt_PT      | 2         | 0.19%   |
| POSIX      | 2         | 0.19%   |
| it_IT      | 2         | 0.19%   |
| en_IE      | 2         | 0.19%   |
| en_CA      | 2         | 0.19%   |
| en_BE      | 2         | 0.19%   |
| C.UTF8     | 2         | 0.19%   |
| tt_RU      | 1         | 0.1%    |
| tr_TR      | 1         | 0.1%    |
| pt_BR      | 1         | 0.1%    |
| nl_BE.UTF8 | 1         | 0.1%    |
| nl_AW      | 1         | 0.1%    |
| ku_TR      | 1         | 0.1%    |
| it_CH      | 1         | 0.1%    |
| fr_CH      | 1         | 0.1%    |
| en_ZA      | 1         | 0.1%    |
| en_US.UTF8 | 1         | 0.1%    |
| en_IN      | 1         | 0.1%    |
| en_DK      | 1         | 0.1%    |
| bg_BG      | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 525       | 51.02%  |
| BIOS | 504       | 48.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 803       | 77.43%  |
| Btrfs   | 98        | 9.45%   |
| Overlay | 70        | 6.75%   |
| Unknown | 32        | 3.09%   |
| Xfs     | 14        | 1.35%   |
| Tmpfs   | 13        | 1.25%   |
| Zfs     | 5         | 0.48%   |
| Ext2    | 2         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 533       | 51.75%  |
| GPT     | 393       | 38.16%  |
| MBR     | 104       | 10.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 881       | 85.78%  |
| Yes       | 146       | 14.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 745       | 73.11%  |
| Yes       | 274       | 26.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 215       | 21.41%  |
| Lenovo              | 183       | 18.23%  |
| Dell                | 172       | 17.13%  |
| ASUSTek Computer    | 103       | 10.26%  |
| Acer                | 73        | 7.27%   |
| Toshiba             | 32        | 3.19%   |
| Medion              | 28        | 2.79%   |
| Apple               | 27        | 2.69%   |
| Sony                | 26        | 2.59%   |
| MSI                 | 25        | 2.49%   |
| Notebook            | 22        | 2.19%   |
| Packard Bell        | 15        | 1.49%   |
| TUXEDO              | 10        | 1%      |
| Valve               | 8         | 0.8%    |
| Samsung Electronics | 8         | 0.8%    |
| PC Specialist       | 4         | 0.4%    |
| Gigabyte Technology | 4         | 0.4%    |
| Fujitsu             | 4         | 0.4%    |
| Unknown             | 4         | 0.4%    |
| Intel               | 3         | 0.3%    |
| HUAWEI              | 3         | 0.3%    |
| Google              | 3         | 0.3%    |
| Fujitsu Siemens     | 3         | 0.3%    |
| Clevo               | 3         | 0.3%    |
| Alienware           | 3         | 0.3%    |
| Teclast             | 2         | 0.2%    |
| Razer               | 2         | 0.2%    |
| Panasonic           | 2         | 0.2%    |
| YJKC                | 1         | 0.1%    |
| VALE                | 1         | 0.1%    |
| TrekStor            | 1         | 0.1%    |
| Timi                | 1         | 0.1%    |
| Standard            | 1         | 0.1%    |
| SLIMBOOK            | 1         | 0.1%    |
| Schenker            | 1         | 0.1%    |
| NEC Computers       | 1         | 0.1%    |
| Inter Sales A/S     | 1         | 0.1%    |
| Hampoo              | 1         | 0.1%    |
| GPD                 | 1         | 0.1%    |
| Emdoor              | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Valve Jupiter                    | 8         | 0.8%    |
| HP Pavilion g7                   | 7         | 0.7%    |
| HP Pavilion Notebook             | 6         | 0.6%    |
| Unknown                          | 6         | 0.6%    |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5 | 5         | 0.5%    |
| HP ProBook 6570b                 | 5         | 0.5%    |
| HP ProBook 650 G1                | 5         | 0.5%    |
| HP Pavilion dv7                  | 5         | 0.5%    |
| HP EliteBook 850 G8 Notebook PC  | 5         | 0.5%    |
| Dell XPS 13 7390                 | 5         | 0.5%    |
| Dell Latitude 5530               | 5         | 0.5%    |
| Toshiba Satellite C660           | 4         | 0.4%    |
| HP Pavilion Laptop 15-eh1xxx     | 4         | 0.4%    |
| HP Pavilion Laptop 15-cw0xxx     | 4         | 0.4%    |
| HP Pavilion dv6                  | 4         | 0.4%    |
| HP Pavilion 17                   | 4         | 0.4%    |
| Gigabyte Spring Peak             | 4         | 0.4%    |
| Dell XPS 13 9370                 | 4         | 0.4%    |
| Dell Latitude 5520               | 4         | 0.4%    |
| Lenovo ThinkPad L390 20NSS1YV0B  | 3         | 0.3%    |
| Lenovo Legion 5 15ARH05 82B5     | 3         | 0.3%    |
| HP ProBook 470 G2                | 3         | 0.3%    |
| HP ProBook 450 G8 Notebook PC    | 3         | 0.3%    |
| HP ProBook 430 G1                | 3         | 0.3%    |
| HP Pavilion 15                   | 3         | 0.3%    |
| HP Notebook                      | 3         | 0.3%    |
| HP Laptop 15-db0xxx              | 3         | 0.3%    |
| HP EliteBook 8460p               | 3         | 0.3%    |
| HP EliteBook 840 G1              | 3         | 0.3%    |
| Dell XPS 15 9570                 | 3         | 0.3%    |
| Dell XPS 15 9560                 | 3         | 0.3%    |
| Dell XPS 13 9360                 | 3         | 0.3%    |
| Dell XPS 13 9305                 | 3         | 0.3%    |
| Dell Precision M4800             | 3         | 0.3%    |
| Dell Latitude E7440              | 3         | 0.3%    |
| Dell Latitude E6540              | 3         | 0.3%    |
| Dell Latitude E6500              | 3         | 0.3%    |
| Dell Latitude E6330              | 3         | 0.3%    |
| Dell Latitude E5540              | 3         | 0.3%    |
| Dell Latitude E5520              | 3         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 105       | 10.46%  |
| Dell Latitude         | 84        | 8.37%   |
| Acer Aspire           | 60        | 5.98%   |
| HP EliteBook          | 59        | 5.88%   |
| HP Pavilion           | 56        | 5.58%   |
| HP ProBook            | 41        | 4.08%   |
| Lenovo IdeaPad        | 35        | 3.49%   |
| Dell XPS              | 33        | 3.29%   |
| Toshiba Satellite     | 28        | 2.79%   |
| Dell Inspiron         | 20        | 1.99%   |
| HP Laptop             | 18        | 1.79%   |
| Dell Precision        | 17        | 1.69%   |
| Lenovo Legion         | 13        | 1.29%   |
| HP Compaq             | 13        | 1.29%   |
| Packard Bell EasyNote | 12        | 1.2%    |
| HP ZBook              | 10        | 1%      |
| ASUS VivoBook         | 10        | 1%      |
| Valve Jupiter         | 8         | 0.8%    |
| Medion Akoya          | 7         | 0.7%    |
| Dell Vostro           | 7         | 0.7%    |
| Lenovo ThinkBook      | 6         | 0.6%    |
| Unknown               | 6         | 0.6%    |
| Dell Studio           | 5         | 0.5%    |
| HP OMEN               | 4         | 0.4%    |
| Gigabyte Spring       | 4         | 0.4%    |
| Dell G3               | 4         | 0.4%    |
| ASUS ZenBook          | 4         | 0.4%    |
| ASUS ROG              | 4         | 0.4%    |
| Apple MacBookPro9     | 4         | 0.4%    |
| Acer Swift            | 4         | 0.4%    |
| Acer Nitro            | 4         | 0.4%    |
| TUXEDO Pulse          | 3         | 0.3%    |
| TUXEDO Aura           | 3         | 0.3%    |
| MSI Vector            | 3         | 0.3%    |
| Lenovo Yoga           | 3         | 0.3%    |
| HP Notebook           | 3         | 0.3%    |
| HP ENVY               | 3         | 0.3%    |
| Fujitsu LIFEBOOK      | 3         | 0.3%    |
| ASUS K52F             | 3         | 0.3%    |
| ASUS K50IJ            | 3         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 97        | 9.66%   |
| 2019    | 90        | 8.96%   |
| 2018    | 86        | 8.57%   |
| 2012    | 84        | 8.37%   |
| 2011    | 82        | 8.17%   |
| 2013    | 77        | 7.67%   |
| 2021    | 66        | 6.57%   |
| 2017    | 55        | 5.48%   |
| 2015    | 54        | 5.38%   |
| 2016    | 49        | 4.88%   |
| 2008    | 49        | 4.88%   |
| 2014    | 47        | 4.68%   |
| 2010    | 45        | 4.48%   |
| 2022    | 39        | 3.88%   |
| 2009    | 33        | 3.29%   |
| 2007    | 28        | 2.79%   |
| 2006    | 13        | 1.29%   |
| 2023    | 5         | 0.5%    |
| 2005    | 2         | 0.2%    |
| 2004    | 2         | 0.2%    |
| Unknown | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1004      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 906       | 89.44%  |
| Enabled  | 107       | 10.56%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1000      | 99.6%   |
| Yes  | 4         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 267       | 26.02%  |
| 8.01-16.0   | 204       | 19.88%  |
| 3.01-4.0    | 198       | 19.3%   |
| 16.01-24.0  | 181       | 17.64%  |
| 32.01-64.0  | 78        | 7.6%    |
| 1.01-2.0    | 40        | 3.9%    |
| 24.01-32.0  | 17        | 1.66%   |
| 64.01-256.0 | 15        | 1.46%   |
| 0.51-1.0    | 13        | 1.27%   |
| 2.01-3.0    | 12        | 1.17%   |
| 0.01-0.5    | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 388       | 34.49%  |
| 2.01-3.0   | 273       | 24.27%  |
| 4.01-8.0   | 152       | 13.51%  |
| 3.01-4.0   | 144       | 12.8%   |
| 0.51-1.0   | 79        | 7.02%   |
| 8.01-16.0  | 64        | 5.69%   |
| 0.01-0.5   | 18        | 1.6%    |
| 24.01-32.0 | 4         | 0.36%   |
| 16.01-24.0 | 3         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 734       | 71.12%  |
| 2      | 258       | 25%     |
| 3      | 27        | 2.62%   |
| 0      | 6         | 0.58%   |
| 4      | 5         | 0.48%   |
| 8      | 1         | 0.1%    |
| 5      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 610       | 60.46%  |
| Yes       | 399       | 39.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 880       | 87.13%  |
| No        | 130       | 12.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 992       | 98.41%  |
| No        | 16        | 1.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 768       | 75.29%  |
| No        | 252       | 24.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Belgium | 1004      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Brussels       | 141       | 12.7%   |
| Antwerp        | 68        | 6.13%   |
| Ghent          | 43        | 3.87%   |
| Liège         | 34        | 3.06%   |
| Ixelles-Elsene | 28        | 2.52%   |
| Mechelen       | 16        | 1.44%   |
| Bruges         | 14        | 1.26%   |
| Turnhout       | 13        | 1.17%   |
| Leuven         | 12        | 1.08%   |
| Anderlecht     | 11        | 0.99%   |
| Uccle          | 10        | 0.9%    |
| Schaarbeek     | 10        | 0.9%    |
| Sint-Truiden   | 9         | 0.81%   |
| Mons           | 8         | 0.72%   |
| Jette          | 8         | 0.72%   |
| Hasselt        | 8         | 0.72%   |
| Harelbeke      | 8         | 0.72%   |
| Etterbeek      | 8         | 0.72%   |
| Aalst          | 8         | 0.72%   |
| Namur          | 7         | 0.63%   |
| La Louvière   | 7         | 0.63%   |
| Kontich        | 7         | 0.63%   |
| Edegem         | 7         | 0.63%   |
| Charleroi      | 7         | 0.63%   |
| Brasschaat     | 7         | 0.63%   |
| Boom           | 7         | 0.63%   |
| Bilzen         | 7         | 0.63%   |
| Seraing        | 6         | 0.54%   |
| Kanne          | 6         | 0.54%   |
| Gavere         | 6         | 0.54%   |
| Wetteren       | 5         | 0.45%   |
| Tournai        | 5         | 0.45%   |
| Sint-Niklaas   | 5         | 0.45%   |
| Schoten        | 5         | 0.45%   |
| Mortsel        | 5         | 0.45%   |
| Mol            | 5         | 0.45%   |
| Merksem        | 5         | 0.45%   |
| Lier           | 5         | 0.45%   |
| Hamme          | 5         | 0.45%   |
| Geel           | 5         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 257       | 376    | 20.68%  |
| Seagate                     | 143       | 200    | 11.5%   |
| WDC                         | 130       | 175    | 10.46%  |
| Toshiba                     | 95        | 125    | 7.64%   |
| SK hynix                    | 64        | 82     | 5.15%   |
| SanDisk                     | 64        | 83     | 5.15%   |
| Kingston                    | 58        | 76     | 4.67%   |
| Unknown                     | 55        | 66     | 4.42%   |
| Intel                       | 52        | 61     | 4.18%   |
| Hitachi                     | 46        | 54     | 3.7%    |
| Micron Technology           | 36        | 39     | 2.9%    |
| HGST                        | 36        | 48     | 2.9%    |
| Crucial                     | 33        | 42     | 2.65%   |
| Apple                       | 16        | 22     | 1.29%   |
| KIOXIA                      | 14        | 16     | 1.13%   |
| LITEON                      | 12        | 14     | 0.97%   |
| Fujitsu                     | 12        | 18     | 0.97%   |
| LITEONIT                    | 8         | 11     | 0.64%   |
| China                       | 8         | 10     | 0.64%   |
| Intenso                     | 7         | 8      | 0.56%   |
| A-DATA Technology           | 7         | 9      | 0.56%   |
| PNY                         | 5         | 6      | 0.4%    |
| Micron/Crucial Technology   | 5         | 7      | 0.4%    |
| Transcend                   | 4         | 4      | 0.32%   |
| SSSTC                       | 4         | 4      | 0.32%   |
| Phison                      | 4         | 4      | 0.32%   |
| OCZ                         | 4         | 5      | 0.32%   |
| GOODRAM                     | 4         | 6      | 0.32%   |
| Corsair                     | 4         | 4      | 0.32%   |
| Silicon Motion              | 3         | 4      | 0.24%   |
| Phison Electronics          | 3         | 4      | 0.24%   |
| ASMT                        | 3         | 3      | 0.24%   |
| Zheino                      | 2         | 2      | 0.16%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.16%   |
| Union Memory                | 2         | 2      | 0.16%   |
| Reeinno                     | 2         | 4      | 0.16%   |
| LaCie                       | 2         | 2      | 0.16%   |
| Kingston Technology Company | 2         | 2      | 0.16%   |
| KingSpec                    | 2         | 2      | 0.16%   |
| JMicron Technology          | 2         | 3      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 17        | 1.31%   |
| Samsung NVMe SSD Drive 512GB                        | 17        | 1.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 14        | 1.08%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 1.08%   |
| Samsung NVMe SSD Drive 1TB                          | 13        | 1%      |
| Intel NVMe SSD Drive 512GB                          | 13        | 1%      |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.93%   |
| Seagate ST9500325AS 500GB                           | 12        | 0.93%   |
| Samsung SSD 860 EVO 500GB                           | 12        | 0.93%   |
| Samsung SSD 850 EVO 250GB                           | 12        | 0.93%   |
| HGST HTS721010A9E630 1TB                            | 11        | 0.85%   |
| Unknown MMC Card  32GB                              | 10        | 0.77%   |
| Toshiba MQ01ABD100 1TB                              | 10        | 0.77%   |
| Samsung SSD 850 EVO 500GB                           | 10        | 0.77%   |
| HGST HTS725050A7E630 500GB                          | 9         | 0.69%   |
| Unknown MMC Card  128GB                             | 8         | 0.62%   |
| Kingston SA400S37120G 120GB SSD                     | 8         | 0.62%   |
| Hitachi HTS547550A9E384 500GB                       | 8         | 0.62%   |
| Seagate ST1000LM048-2E7172 1TB                      | 7         | 0.54%   |
| Seagate Expansion 1TB                               | 7         | 0.54%   |
| Samsung SSD 860 EVO 1TB                             | 7         | 0.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 7         | 0.54%   |
| Seagate ST500LT012-1DG142 500GB                     | 6         | 0.46%   |
| Seagate ST2000LM015-2E8174 2TB                      | 6         | 0.46%   |
| Samsung NVMe SSD Drive 500GB                        | 6         | 0.46%   |
| Kingston SV300S37A120G 120GB SSD                    | 6         | 0.46%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 0.46%   |
| HGST HTS541010A9E680 1TB                            | 6         | 0.46%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 5         | 0.39%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 5         | 0.39%   |
| Unknown MMC Card  64GB                              | 5         | 0.39%   |
| Unknown MMC Card  256GB                             | 5         | 0.39%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 0.39%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 0.39%   |
| Toshiba MQ01ABD075 752GB                            | 5         | 0.39%   |
| SanDisk NVMe SSD Drive 256GB                        | 5         | 0.39%   |
| Samsung SSD 980 500GB                               | 5         | 0.39%   |
| Samsung SSD 870 EVO 1TB                             | 5         | 0.39%   |
| Samsung SSD 860 EVO 250GB                           | 5         | 0.39%   |
| Samsung SSD 850 EVO 120GB                           | 5         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 135       | 188    | 33.75%  |
| WDC                 | 93        | 123    | 23.25%  |
| Toshiba             | 65        | 88     | 16.25%  |
| Hitachi             | 46        | 54     | 11.5%   |
| HGST                | 36        | 48     | 9%      |
| Fujitsu             | 12        | 17     | 3%      |
| Samsung Electronics | 7         | 9      | 1.75%   |
| ASMT                | 2         | 2      | 0.5%    |
| Unknown             | 1         | 1      | 0.25%   |
| LaCie               | 1         | 1      | 0.25%   |
| JMicron Technology  | 1         | 1      | 0.25%   |
| Apple               | 1         | 1      | 0.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 133       | 195    | 33.08%  |
| Kingston            | 39        | 48     | 9.7%    |
| SanDisk             | 36        | 50     | 8.96%   |
| Crucial             | 28        | 36     | 6.97%   |
| WDC                 | 18        | 23     | 4.48%   |
| SK hynix            | 17        | 27     | 4.23%   |
| Intel               | 17        | 19     | 4.23%   |
| Toshiba             | 12        | 15     | 2.99%   |
| Micron Technology   | 12        | 12     | 2.99%   |
| LITEON              | 11        | 13     | 2.74%   |
| Apple               | 9         | 13     | 2.24%   |
| LITEONIT            | 8         | 11     | 1.99%   |
| China               | 8         | 10     | 1.99%   |
| Intenso             | 6         | 7      | 1.49%   |
| PNY                 | 5         | 6      | 1.24%   |
| A-DATA Technology   | 5         | 7      | 1.24%   |
| OCZ                 | 4         | 5      | 1%      |
| GOODRAM             | 4         | 6      | 1%      |
| Transcend           | 3         | 3      | 0.75%   |
| Zheino              | 2         | 2      | 0.5%    |
| KingSpec            | 2         | 2      | 0.5%    |
| Emtec               | 2         | 2      | 0.5%    |
| Corsair             | 2         | 2      | 0.5%    |
| TO Exter            | 1         | 1      | 0.25%   |
| Teclast             | 1         | 1      | 0.25%   |
| SPCC                | 1         | 2      | 0.25%   |
| Reeinno             | 1         | 3      | 0.25%   |
| Plextor             | 1         | 1      | 0.25%   |
| Patriot             | 1         | 1      | 0.25%   |
| OWC                 | 1         | 2      | 0.25%   |
| Netac               | 1         | 1      | 0.25%   |
| Leven               | 1         | 1      | 0.25%   |
| INTEL SS            | 1         | 1      | 0.25%   |
| Innodisk            | 1         | 1      | 0.25%   |
| Indilinx            | 1         | 1      | 0.25%   |
| HEORIADY            | 1         | 1      | 0.25%   |
| Fujitsu             | 1         | 1      | 0.25%   |
| FORESEE             | 1         | 1      | 0.25%   |
| Drevo               | 1         | 1      | 0.25%   |
| Dogfish             | 1         | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 378       | 533    | 32.17%  |
| SSD     | 376       | 537    | 32%     |
| NVMe    | 357       | 488    | 30.38%  |
| MMC     | 50        | 62     | 4.26%   |
| Unknown | 14        | 20     | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 668       | 1019   | 59.59%  |
| NVMe | 357       | 488    | 31.85%  |
| MMC  | 50        | 62     | 4.46%   |
| SAS  | 46        | 71     | 4.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 538       | 739    | 70.42%  |
| 0.51-1.0   | 199       | 295    | 26.05%  |
| 1.01-2.0   | 19        | 24     | 2.49%   |
| 4.01-10.0  | 5         | 7      | 0.65%   |
| 3.01-4.0   | 1         | 3      | 0.13%   |
| 2.01-3.0   | 1         | 1      | 0.13%   |
| 10.01-20.0 | 1         | 1      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 329       | 30.69%  |
| 251-500        | 296       | 27.61%  |
| 501-1000       | 132       | 12.31%  |
| 1001-2000      | 65        | 6.06%   |
| 51-100         | 65        | 6.06%   |
| 1-20           | 64        | 5.97%   |
| Unknown        | 39        | 3.64%   |
| 21-50          | 37        | 3.45%   |
| 2001-3000      | 24        | 2.24%   |
| More than 3000 | 21        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 434       | 38.61%  |
| 21-50          | 194       | 17.26%  |
| 101-250        | 168       | 14.95%  |
| 51-100         | 135       | 12.01%  |
| 251-500        | 73        | 6.49%   |
| 501-1000       | 48        | 4.27%   |
| Unknown        | 39        | 3.47%   |
| 1001-2000      | 22        | 1.96%   |
| 2001-3000      | 7         | 0.62%   |
| More than 3000 | 4         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 4         | 4      | 5.41%   |
| Toshiba MQ01ABD075 752GB                       | 2         | 2      | 2.7%    |
| Seagate ST9750420AS 752GB                      | 2         | 2      | 2.7%    |
| Seagate ST320LT007-9ZV142 320GB                | 2         | 7      | 2.7%    |
| Hitachi HTS545050A7E380 500GB                  | 2         | 3      | 2.7%    |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 2.7%    |
| WDC WD3200BPVT-55JJ5T0 320GB                   | 1         | 1      | 1.35%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 1         | 1      | 1.35%   |
| WDC WD3200BEKT-60PVMT0 320GB                   | 1         | 1      | 1.35%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 1.35%   |
| Toshiba MQ01ABD032 320GB                       | 1         | 1      | 1.35%   |
| Toshiba MK6476GSX 640GB                        | 1         | 1      | 1.35%   |
| Toshiba MK5075GSX 500GB                        | 1         | 1      | 1.35%   |
| Toshiba MK3263GSXN 320GB                       | 1         | 1      | 1.35%   |
| Toshiba KSG60ZSE512G SATA 512GB SSD            | 1         | 1      | 1.35%   |
| SK hynix SH920 mSATA 256GB SSD                 | 1         | 1      | 1.35%   |
| SK hynix SH920 2.5 7MM 256GB SSD               | 1         | 2      | 1.35%   |
| SK hynix SC401 SATA 512GB SSD                  | 1         | 3      | 1.35%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 2      | 1.35%   |
| SK hynix HFS256G32MND-2900A 256GB SSD          | 1         | 1      | 1.35%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 1.35%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 1.35%   |
| Seagate ST9320423AS 320GB                      | 1         | 2      | 1.35%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 1.35%   |
| Seagate ST9120822AS 120GB                      | 1         | 1      | 1.35%   |
| Seagate ST9120821AS 120GB                      | 1         | 1      | 1.35%   |
| Seagate ST9100824AS 100GB                      | 1         | 1      | 1.35%   |
| Seagate ST750LM022 HN-M750MBB 752GB            | 1         | 1      | 1.35%   |
| Seagate ST500LM000-SSHD-8GB                    | 1         | 1      | 1.35%   |
| Seagate ST2000LM015-2E8174 2TB                 | 1         | 1      | 1.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 6      | 1.35%   |
| SanDisk SSD PLUS 480GB                         | 1         | 1      | 1.35%   |
| SanDisk SD8SNAT128G1002 128GB SSD              | 1         | 1      | 1.35%   |
| SanDisk SD6SN1M-256G-1006 256GB SSD            | 1         | 1      | 1.35%   |
| Samsung Electronics HM641JI 640GB              | 1         | 1      | 1.35%   |
| OCZ VERTEX3 256GB SSD                          | 1         | 1      | 1.35%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.35%   |
| Micron Technology 1100 SATA 512GB SSD          | 1         | 1      | 1.35%   |
| Kingston SNS4151S332G 32GB SSD                 | 1         | 1      | 1.35%   |
| Kingston SA400S37120G 120GB SSD                | 1         | 6      | 1.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 29     | 24.32%  |
| Hitachi             | 11        | 12     | 14.86%  |
| Toshiba             | 8         | 8      | 10.81%  |
| Intel               | 7         | 7      | 9.46%   |
| SK hynix            | 6         | 10     | 8.11%   |
| HGST                | 5         | 5      | 6.76%   |
| Fujitsu             | 4         | 8      | 5.41%   |
| WDC                 | 3         | 3      | 4.05%   |
| SanDisk             | 3         | 3      | 4.05%   |
| Micron Technology   | 2         | 2      | 2.7%    |
| Kingston            | 2         | 7      | 2.7%    |
| Crucial             | 2         | 2      | 2.7%    |
| Samsung Electronics | 1         | 1      | 1.35%   |
| OCZ                 | 1         | 1      | 1.35%   |
| A-DATA Technology   | 1         | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 29     | 36.73%  |
| Hitachi             | 11        | 12     | 22.45%  |
| Toshiba             | 7         | 7      | 14.29%  |
| HGST                | 5         | 5      | 10.2%   |
| Fujitsu             | 4         | 8      | 8.16%   |
| WDC                 | 3         | 3      | 6.12%   |
| Samsung Electronics | 1         | 1      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 65     | 66.22%  |
| SSD  | 22        | 30     | 29.73%  |
| NVMe | 3         | 4      | 4.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BUCT-63TWBY0 320GB                 | 1         | 1      | 33.33%  |
| Samsung Electronics MZVLW128HEGR-000L2 128GB | 1         | 2      | 33.33%  |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 2      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 597       | 990    | 55.85%  |
| Works    | 397       | 547    | 37.14%  |
| Malfunc  | 72        | 99     | 6.74%   |
| Failed   | 3         | 4      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 706       | 59.93%  |
| Samsung Electronics              | 129       | 10.95%  |
| AMD                              | 98        | 8.32%   |
| SK hynix                         | 47        | 3.99%   |
| SanDisk                          | 45        | 3.82%   |
| Micron Technology                | 24        | 2.04%   |
| Kingston Technology Company      | 21        | 1.78%   |
| Toshiba America Info Systems     | 19        | 1.61%   |
| KIOXIA                           | 15        | 1.27%   |
| Nvidia                           | 10        | 0.85%   |
| Micron/Crucial Technology        | 10        | 0.85%   |
| Phison Electronics               | 9         | 0.76%   |
| Union Memory (Shenzhen)          | 7         | 0.59%   |
| Solid State Storage Technology   | 7         | 0.59%   |
| Marvell Technology Group         | 5         | 0.42%   |
| Apple                            | 5         | 0.42%   |
| Seagate Technology               | 4         | 0.34%   |
| Silicon Motion                   | 3         | 0.25%   |
| Silicon Image                    | 3         | 0.25%   |
| Silicon Integrated Systems [SiS] | 2         | 0.17%   |
| ADATA Technology                 | 2         | 0.17%   |
| VIA Technologies                 | 1         | 0.08%   |
| Transcend                        | 1         | 0.08%   |
| Lite-On Technology               | 1         | 0.08%   |
| Lenovo                           | 1         | 0.08%   |
| INNOGRIT                         | 1         | 0.08%   |
| Biwin Storage Technology         | 1         | 0.08%   |
| ASMedia Technology               | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 93        | 7.26%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 80        | 6.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 69        | 5.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 67        | 5.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 67        | 5.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 60        | 4.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 46        | 3.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 33        | 2.58%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 33        | 2.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 32        | 2.5%    |
| Samsung NVMe SSD Controller 980                                                | 29        | 2.26%   |
| Intel Volume Management Device NVMe RAID Controller                            | 29        | 2.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 26        | 2.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 24        | 1.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 24        | 1.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 23        | 1.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 22        | 1.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 16        | 1.25%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 15        | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 14        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 14        | 1.09%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 13        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 13        | 1.01%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 1.01%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 12        | 0.94%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 11        | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 11        | 0.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 11        | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 11        | 0.86%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 10        | 0.78%   |
| Intel SSD 660P Series                                                          | 10        | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 10        | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 10        | 0.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 0.7%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 9         | 0.7%    |
| Micron 2210 NVMe SSD [Cobain]                                                  | 8         | 0.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 0.62%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 697       | 56.76%  |
| NVMe | 359       | 29.23%  |
| RAID | 94        | 7.65%   |
| IDE  | 78        | 6.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 838       | 83.47%  |
| AMD    | 166       | 16.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 24        | 2.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 21        | 2.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 1.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 1.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 16        | 1.59%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 14        | 1.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.29%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 1.09%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 11        | 1.09%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 1%      |
| Intel Core i5-3230M CPU @ 2.60GHz             | 10        | 1%      |
| Intel Core i5-2430M CPU @ 2.40GHz             | 10        | 1%      |
| Intel Core i3-2350M CPU @ 2.30GHz             | 10        | 1%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1%      |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 1%      |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 9         | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.9%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.9%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 8         | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 8         | 0.8%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 0.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.8%    |
| AMD Custom APU 0405                           | 8         | 0.8%    |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 7         | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 7         | 0.7%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 7         | 0.7%    |
| Intel Core i5-4210M CPU @ 2.60GHz             | 7         | 0.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.7%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 7         | 0.7%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 7         | 0.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 273       | 27.19%  |
| Intel Core i5           | 235       | 23.41%  |
| Other                   | 81        | 8.07%   |
| Intel Core i3           | 70        | 6.97%   |
| Intel Core 2 Duo        | 65        | 6.47%   |
| AMD Ryzen 5             | 37        | 3.69%   |
| Intel Celeron           | 30        | 2.99%   |
| AMD Ryzen 7             | 29        | 2.89%   |
| Intel Pentium           | 18        | 1.79%   |
| Intel Atom              | 16        | 1.59%   |
| AMD Ryzen 7 PRO         | 13        | 1.29%   |
| Intel Pentium Dual-Core | 11        | 1.1%    |
| AMD E1                  | 11        | 1.1%    |
| Intel Core 2            | 9         | 0.9%    |
| AMD E                   | 9         | 0.9%    |
| AMD A6                  | 9         | 0.9%    |
| AMD Ryzen 9             | 8         | 0.8%    |
| AMD Ryzen 5 PRO         | 8         | 0.8%    |
| Intel Genuine           | 7         | 0.7%    |
| Intel Core i9           | 7         | 0.7%    |
| Intel Pentium Silver    | 6         | 0.6%    |
| AMD A8                  | 6         | 0.6%    |
| AMD A4                  | 6         | 0.6%    |
| AMD Ryzen 3             | 4         | 0.4%    |
| Intel Pentium Dual      | 3         | 0.3%    |
| Intel Celeron M         | 3         | 0.3%    |
| AMD Turion 64 X2 Mobile | 3         | 0.3%    |
| Intel Xeon              | 2         | 0.2%    |
| Intel Pentium 4         | 2         | 0.2%    |
| Intel Core Duo          | 2         | 0.2%    |
| AMD Athlon II           | 2         | 0.2%    |
| AMD A12                 | 2         | 0.2%    |
| Intel Pentium M         | 1         | 0.1%    |
| Intel Mobile Pentium 4  | 1         | 0.1%    |
| Intel Core m5           | 1         | 0.1%    |
| Intel Core m3           | 1         | 0.1%    |
| Intel Core M            | 1         | 0.1%    |
| Intel Core 2 Quad       | 1         | 0.1%    |
| Intel Core              | 1         | 0.1%    |
| Intel Celeron Dual-Core | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 489       | 48.66%  |
| 4       | 328       | 32.64%  |
| 6       | 77        | 7.66%   |
| 8       | 64        | 6.37%   |
| 1       | 20        | 1.99%   |
| 10      | 11        | 1.09%   |
| 12      | 6         | 0.6%    |
| 14      | 5         | 0.5%    |
| Unknown | 4         | 0.4%    |
| 16      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1004      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 770       | 76.54%  |
| 1       | 232       | 23.06%  |
| Unknown | 4         | 0.4%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 981       | 97.42%  |
| Unknown        | 14        | 1.39%   |
| 32-bit         | 12        | 1.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 250       | 23.95%  |
| 0x306a9    | 76        | 7.28%   |
| 0x206a7    | 62        | 5.94%   |
| 0x806ea    | 37        | 3.54%   |
| 0x806ec    | 34        | 3.26%   |
| 0x40651    | 34        | 3.26%   |
| 0x1067a    | 34        | 3.26%   |
| 0x306c3    | 31        | 2.97%   |
| 0x906ea    | 27        | 2.59%   |
| 0x806c1    | 26        | 2.49%   |
| 0x406e3    | 25        | 2.39%   |
| 0x306d4    | 25        | 2.39%   |
| 0x20655    | 25        | 2.39%   |
| 0x906e9    | 22        | 2.11%   |
| 0x806e9    | 22        | 2.11%   |
| 0x6fd      | 20        | 1.92%   |
| 0xa0652    | 18        | 1.72%   |
| 0x08600106 | 16        | 1.53%   |
| 0x10676    | 15        | 1.44%   |
| 0x0a50000c | 14        | 1.34%   |
| 0x30678    | 13        | 1.25%   |
| 0x08608103 | 13        | 1.25%   |
| 0x806eb    | 10        | 0.96%   |
| 0x07030105 | 9         | 0.86%   |
| 0x05000119 | 9         | 0.86%   |
| 0x906a4    | 8         | 0.77%   |
| 0x6f6      | 8         | 0.77%   |
| 0x506e3    | 8         | 0.77%   |
| 0x20652    | 7         | 0.67%   |
| 0x08600103 | 7         | 0.67%   |
| 0x806d1    | 6         | 0.57%   |
| 0x6fb      | 6         | 0.57%   |
| 0x08108102 | 6         | 0.57%   |
| 0x0700010f | 6         | 0.57%   |
| 0x906a3    | 5         | 0.48%   |
| 0x706a1    | 5         | 0.48%   |
| 0x106ca    | 5         | 0.48%   |
| 0x08600104 | 5         | 0.48%   |
| 0x08108109 | 5         | 0.48%   |
| 0x0810100b | 5         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 205       | 20.4%   |
| IvyBridge        | 92        | 9.15%   |
| Haswell          | 83        | 8.26%   |
| SandyBridge      | 80        | 7.96%   |
| Penryn           | 56        | 5.57%   |
| TigerLake        | 41        | 4.08%   |
| Skylake          | 41        | 4.08%   |
| Core             | 40        | 3.98%   |
| Westmere         | 39        | 3.88%   |
| Unknown          | 38        | 3.78%   |
| Zen 2            | 32        | 3.18%   |
| Broadwell        | 29        | 2.89%   |
| CometLake        | 28        | 2.79%   |
| Silvermont       | 26        | 2.59%   |
| Zen 3            | 22        | 2.19%   |
| Alderlake Hybrid | 18        | 1.79%   |
| Bobcat           | 15        | 1.49%   |
| Zen+             | 14        | 1.39%   |
| Puma             | 12        | 1.19%   |
| Icelake          | 12        | 1.19%   |
| Goldmont plus    | 12        | 1.19%   |
| Bonnell          | 10        | 1%      |
| Jaguar           | 9         | 0.9%    |
| Excavator        | 9         | 0.9%    |
| Zen              | 8         | 0.8%    |
| P6               | 8         | 0.8%    |
| Nehalem          | 5         | 0.5%    |
| K8 Hammer        | 4         | 0.4%    |
| NetBurst         | 3         | 0.3%    |
| K8 & K10 hybrid  | 3         | 0.3%    |
| K10              | 3         | 0.3%    |
| Tremont          | 2         | 0.2%    |
| Piledriver       | 2         | 0.2%    |
| K10 Llano        | 2         | 0.2%    |
| Goldmont         | 2         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 723       | 56.53%  |
| Nvidia                           | 307       | 24%     |
| AMD                              | 247       | 19.31%  |
| VIA Technologies                 | 1         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 84        | 6.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 67        | 5.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 43        | 3.26%   |
| Intel UHD Graphics 620                                                                   | 42        | 3.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 41        | 3.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 40        | 3.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 35        | 2.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 35        | 2.65%   |
| AMD Renoir                                                                               | 29        | 2.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 27        | 2.05%   |
| Intel HD Graphics 620                                                                    | 26        | 1.97%   |
| Intel HD Graphics 5500                                                                   | 26        | 1.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 1.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 25        | 1.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 1.52%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 1.44%   |
| Intel HD Graphics 630                                                                    | 19        | 1.44%   |
| AMD Lucienne                                                                             | 19        | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 1.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 1.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 11        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 0.83%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 11        | 0.83%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 10        | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.68%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 9         | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 8         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 0.61%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 8         | 0.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 8         | 0.61%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 8         | 0.61%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 8         | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 0.61%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 7         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 465       | 46.04%  |
| Intel + Nvidia | 207       | 20.5%   |
| 1 x AMD        | 169       | 16.73%  |
| 1 x Nvidia     | 82        | 8.12%   |
| Intel + AMD    | 50        | 4.95%   |
| AMD + Nvidia   | 19        | 1.88%   |
| 2 x AMD        | 9         | 0.89%   |
| Other          | 3         | 0.3%    |
| 2 x Intel      | 3         | 0.3%    |
| 2 x Nvidia     | 1         | 0.1%    |
| 1 x VIA        | 1         | 0.1%    |
| 1 x SiS        | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 852       | 83.28%  |
| Proprietary | 148       | 14.47%  |
| Unknown     | 23        | 2.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 612       | 59.07%  |
| 0.01-0.5   | 143       | 13.8%   |
| 1.01-2.0   | 123       | 11.87%  |
| 0.51-1.0   | 76        | 7.34%   |
| 3.01-4.0   | 51        | 4.92%   |
| 7.01-8.0   | 13        | 1.25%   |
| 5.01-6.0   | 12        | 1.16%   |
| 2.01-3.0   | 5         | 0.48%   |
| 8.01-16.0  | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 259       | 22.6%   |
| LG Display              | 175       | 15.27%  |
| Samsung Electronics     | 127       | 11.08%  |
| Chimei Innolux          | 125       | 10.91%  |
| BOE                     | 115       | 10.03%  |
| Sharp                   | 35        | 3.05%   |
| Dell                    | 35        | 3.05%   |
| Chi Mei Optoelectronics | 32        | 2.79%   |
| Apple                   | 26        | 2.27%   |
| Lenovo                  | 24        | 2.09%   |
| Iiyama                  | 22        | 1.92%   |
| Hewlett-Packard         | 19        | 1.66%   |
| Philips                 | 15        | 1.31%   |
| Goldstar                | 15        | 1.31%   |
| PANDA                   | 9         | 0.79%   |
| LG Philips              | 9         | 0.79%   |
| AOC                     | 9         | 0.79%   |
| BenQ                    | 8         | 0.7%    |
| CSO                     | 7         | 0.61%   |
| Valve                   | 6         | 0.52%   |
| InfoVision              | 6         | 0.52%   |
| Unknown                 | 5         | 0.44%   |
| Sony                    | 5         | 0.44%   |
| Seiko/Epson             | 5         | 0.44%   |
| Vestel Elektronik       | 4         | 0.35%   |
| Quanta Display          | 4         | 0.35%   |
| Panasonic               | 4         | 0.35%   |
| Medion                  | 4         | 0.35%   |
| ASUSTek Computer        | 4         | 0.35%   |
| Acer                    | 4         | 0.35%   |
| HannStar                | 3         | 0.26%   |
| Arnos Instruments       | 2         | 0.17%   |
| Analogix                | 2         | 0.17%   |
| ___                     | 1         | 0.09%   |
| WST                     | 1         | 0.09%   |
| ViewSonic               | 1         | 0.09%   |
| TMX                     | 1         | 0.09%   |
| RGB                     | 1         | 0.09%   |
| Nvidia                  | 1         | 0.09%   |
| MS_ Nvidia              | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 17        | 1.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 14        | 1.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.77%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 9         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 8         | 0.69%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 8         | 0.69%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 8         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 7         | 0.6%    |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 7         | 0.6%    |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 7         | 0.6%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 6         | 0.52%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 6         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 5         | 0.43%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 5         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 5         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch          | 5         | 0.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch  | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch            | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO149E 1600x900 382x214mm 17.2-inch             | 5         | 0.43%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 5         | 0.43%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                          | 4         | 0.34%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 4         | 0.34%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch              | 4         | 0.34%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch               | 4         | 0.34%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 4         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 4         | 0.34%   |
| BOE LCD Monitor BOE06FA 1920x1080 294x165mm 13.3-inch                     | 4         | 0.34%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                     | 4         | 0.34%   |
| AU Optronics LCD Monitor AUOA08B 1920x1080 344x193mm 15.5-inch            | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch            | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch             | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 4         | 0.34%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 3         | 0.26%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                   | 3         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 456       | 42.42%  |
| 1366x768 (WXGA)    | 215       | 20%     |
| 1600x900 (HD+)     | 117       | 10.88%  |
| 3840x2160 (4K)     | 58        | 5.4%    |
| 2560x1440 (QHD)    | 42        | 3.91%   |
| 1280x800 (WXGA)    | 37        | 3.44%   |
| 1440x900 (WXGA+)   | 26        | 2.42%   |
| 1920x1200 (WUXGA)  | 18        | 1.67%   |
| 1680x1050 (WSXGA+) | 14        | 1.3%    |
| 2560x1600          | 9         | 0.84%   |
| 800x1280           | 7         | 0.65%   |
| 1280x1024 (SXGA)   | 7         | 0.65%   |
| 1024x600           | 7         | 0.65%   |
| 3440x1440          | 6         | 0.56%   |
| 3200x1800 (QHD+)   | 6         | 0.56%   |
| 2880x1800          | 6         | 0.56%   |
| Unknown            | 6         | 0.56%   |
| 3840x2400          | 5         | 0.47%   |
| 1680x945           | 5         | 0.47%   |
| 1360x768           | 5         | 0.47%   |
| 1024x768 (XGA)     | 3         | 0.28%   |
| 3840x1080          | 2         | 0.19%   |
| 2560x1080          | 2         | 0.19%   |
| 7680x2160          | 1         | 0.09%   |
| 6320x1800          | 1         | 0.09%   |
| 3600x1080          | 1         | 0.09%   |
| 3520x1080          | 1         | 0.09%   |
| 3200x1080          | 1         | 0.09%   |
| 2880x1920          | 1         | 0.09%   |
| 2880x1620          | 1         | 0.09%   |
| 2304x1440          | 1         | 0.09%   |
| 2256x1504          | 1         | 0.09%   |
| 2160x1440          | 1         | 0.09%   |
| 2048x1152          | 1         | 0.09%   |
| 1920x515           | 1         | 0.09%   |
| 1920x1280          | 1         | 0.09%   |
| 1600x1200          | 1         | 0.09%   |
| 1280x720 (HD)      | 1         | 0.09%   |
| 1024x576           | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 461       | 40.37%  |
| 17      | 162       | 14.19%  |
| 13      | 130       | 11.38%  |
| 14      | 92        | 8.06%   |
| 24      | 48        | 4.2%    |
| 27      | 42        | 3.68%   |
| Unknown | 29        | 2.54%   |
| 23      | 23        | 2.01%   |
| 12      | 23        | 2.01%   |
| 21      | 20        | 1.75%   |
| 18      | 15        | 1.31%   |
| 11      | 12        | 1.05%   |
| 10      | 11        | 0.96%   |
| 16      | 10        | 0.88%   |
| 22      | 7         | 0.61%   |
| 84      | 6         | 0.53%   |
| 34      | 6         | 0.53%   |
| 7       | 6         | 0.53%   |
| 72      | 5         | 0.44%   |
| 25      | 5         | 0.44%   |
| 31      | 4         | 0.35%   |
| 20      | 4         | 0.35%   |
| 54      | 3         | 0.26%   |
| 40      | 3         | 0.26%   |
| 19      | 3         | 0.26%   |
| 39      | 2         | 0.18%   |
| 32      | 2         | 0.18%   |
| 3       | 2         | 0.18%   |
| 65      | 1         | 0.09%   |
| 52      | 1         | 0.09%   |
| 43      | 1         | 0.09%   |
| 42      | 1         | 0.09%   |
| 35      | 1         | 0.09%   |
| 29      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 594       | 52.38%  |
| 351-400     | 185       | 16.31%  |
| 201-300     | 127       | 11.2%   |
| 501-600     | 108       | 9.52%   |
| 401-500     | 42        | 3.7%    |
| Unknown     | 29        | 2.56%   |
| 1501-2000   | 11        | 0.97%   |
| 601-700     | 10        | 0.88%   |
| 701-800     | 8         | 0.71%   |
| 1-100       | 7         | 0.62%   |
| 801-900     | 6         | 0.53%   |
| 1001-1500   | 5         | 0.44%   |
| 901-1000    | 2         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 826       | 83.27%  |
| 16/10   | 116       | 11.69%  |
| Unknown | 19        | 1.92%   |
| 5/4     | 7         | 0.71%   |
| 21/9    | 7         | 0.71%   |
| 0.67    | 6         | 0.6%    |
| 4/3     | 4         | 0.4%    |
| 3/2     | 4         | 0.4%    |
| 6/5     | 2         | 0.2%    |
| 3.73    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 460       | 40.56%  |
| 81-90          | 149       | 13.14%  |
| 121-130        | 138       | 12.17%  |
| 201-250        | 77        | 6.79%   |
| 71-80          | 73        | 6.44%   |
| 301-350        | 42        | 3.7%    |
| Unknown        | 29        | 2.56%   |
| 61-70          | 23        | 2.03%   |
| 131-140        | 23        | 2.03%   |
| More than 1000 | 16        | 1.41%   |
| 151-200        | 15        | 1.32%   |
| 351-500        | 14        | 1.23%   |
| 251-300        | 14        | 1.23%   |
| 141-150        | 13        | 1.15%   |
| 51-60          | 12        | 1.06%   |
| 41-50          | 11        | 0.97%   |
| 111-120        | 10        | 0.88%   |
| 1-40           | 7         | 0.62%   |
| 501-1000       | 7         | 0.62%   |
| 91-100         | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 448       | 40.29%  |
| 101-120       | 323       | 29.05%  |
| 51-100        | 170       | 15.29%  |
| 161-240       | 90        | 8.09%   |
| More than 240 | 41        | 3.69%   |
| Unknown       | 29        | 2.61%   |
| 1-50          | 11        | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 811       | 78.59%  |
| 2     | 168       | 16.28%  |
| 0     | 31        | 3%      |
| 3     | 21        | 2.03%   |
| 4     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 591       | 36.37%  |
| Realtek Semiconductor             | 506       | 31.14%  |
| Qualcomm Atheros                  | 221       | 13.6%   |
| Broadcom                          | 101       | 6.22%   |
| Broadcom Limited                  | 23        | 1.42%   |
| MediaTek                          | 20        | 1.23%   |
| Marvell Technology Group          | 17        | 1.05%   |
| Ralink                            | 16        | 0.98%   |
| TP-Link                           | 13        | 0.8%    |
| Nvidia                            | 10        | 0.62%   |
| Dell                              | 10        | 0.62%   |
| ASIX Electronics                  | 10        | 0.62%   |
| Lenovo                            | 9         | 0.55%   |
| Ralink Technology                 | 8         | 0.49%   |
| Ericsson Business Mobile Networks | 6         | 0.37%   |
| DisplayLink                       | 6         | 0.37%   |
| Sierra Wireless                   | 5         | 0.31%   |
| JMicron Technology                | 5         | 0.31%   |
| D-Link System                     | 5         | 0.31%   |
| Hewlett-Packard                   | 4         | 0.25%   |
| Qualcomm                          | 3         | 0.18%   |
| ASUSTek Computer                  | 3         | 0.18%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.12%   |
| Samsung Electronics               | 2         | 0.12%   |
| Motorola PCS                      | 2         | 0.12%   |
| Huawei Technologies               | 2         | 0.12%   |
| Fibocom                           | 2         | 0.12%   |
| D-Link                            | 2         | 0.12%   |
| Attansic Technology               | 2         | 0.12%   |
| Apple                             | 2         | 0.12%   |
| ADMtek                            | 2         | 0.12%   |
| Z-Com                             | 1         | 0.06%   |
| Xiaomi                            | 1         | 0.06%   |
| VIA Technologies                  | 1         | 0.06%   |
| Shenzhen Goodix Technology        | 1         | 0.06%   |
| Seeed                             | 1         | 0.06%   |
| Panasonic (Matsushita)            | 1         | 0.06%   |
| OPPO Electronics                  | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.06%   |
| Microsoft                         | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 306       | 15.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 79        | 3.95%   |
| Intel Wi-Fi 6 AX200                                               | 74        | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 66        | 3.3%    |
| Intel Wireless 7260                                               | 43        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 42        | 2.1%    |
| Intel Wireless 8265 / 8275                                        | 37        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 37        | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 32        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 29        | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 29        | 1.45%   |
| Intel Wi-Fi 6 AX201                                               | 29        | 1.45%   |
| Intel Wireless 8260                                               | 28        | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 26        | 1.3%    |
| Intel Wireless 7265                                               | 26        | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 26        | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 24        | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 23        | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 22        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20        | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 18        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.9%    |
| Intel Wireless-AC 9260                                            | 18        | 0.9%    |
| Intel Ethernet Connection I218-LM                                 | 18        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 18        | 0.9%    |
| Intel Centrino Wireless-N 2230                                    | 17        | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 16        | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 16        | 0.8%    |
| Intel WiFi Link 5100                                              | 15        | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 0.7%    |
| Intel Centrino Advanced-N 6200                                    | 14        | 0.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 13        | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 13        | 0.65%   |
| Intel Centrino Advanced-N 6235                                    | 13        | 0.65%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                     | 13        | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 566       | 54.42%  |
| Qualcomm Atheros                      | 184       | 17.69%  |
| Realtek Semiconductor                 | 124       | 11.92%  |
| Broadcom                              | 69        | 6.63%   |
| Ralink                                | 16        | 1.54%   |
| MediaTek                              | 16        | 1.54%   |
| Broadcom Limited                      | 16        | 1.54%   |
| TP-Link                               | 8         | 0.77%   |
| Ralink Technology                     | 8         | 0.77%   |
| Sierra Wireless                       | 5         | 0.48%   |
| D-Link System                         | 5         | 0.48%   |
| Dell                                  | 4         | 0.38%   |
| Qualcomm                              | 3         | 0.29%   |
| ASUSTek Computer                      | 3         | 0.29%   |
| Fibocom                               | 2         | 0.19%   |
| Ericsson Business Mobile Networks     | 2         | 0.19%   |
| D-Link                                | 2         | 0.19%   |
| Z-Com                                 | 1         | 0.1%    |
| Panasonic (Matsushita)                | 1         | 0.1%    |
| Microsoft                             | 1         | 0.1%    |
| Hewlett-Packard                       | 1         | 0.1%    |
| Edimax Technology                     | 1         | 0.1%    |
| Belkin Components                     | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 74        | 7.09%   |
| Intel Wireless 7260                                                     | 43        | 4.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 42        | 4.02%   |
| Intel Wireless 8265 / 8275                                              | 37        | 3.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 32        | 3.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 2.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 29        | 2.78%   |
| Intel Wi-Fi 6 AX201                                                     | 29        | 2.78%   |
| Intel Wireless 8260                                                     | 28        | 2.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 26        | 2.49%   |
| Intel Wireless 7265                                                     | 26        | 2.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 26        | 2.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 24        | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 2.2%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 23        | 2.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 22        | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 1.72%   |
| Intel Wireless-AC 9260                                                  | 18        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 18        | 1.72%   |
| Intel Centrino Wireless-N 2230                                          | 17        | 1.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 16        | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 1.53%   |
| Intel WiFi Link 5100                                                    | 15        | 1.44%   |
| Intel Centrino Advanced-N 6200                                          | 14        | 1.34%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 13        | 1.25%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 1.25%   |
| Intel Centrino Advanced-N 6235                                          | 13        | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 1.05%   |
| Intel Wireless 3160                                                     | 11        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 9         | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 0.77%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 0.77%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 8         | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 460       | 50%     |
| Intel                            | 244       | 26.52%  |
| Qualcomm Atheros                 | 79        | 8.59%   |
| Broadcom                         | 43        | 4.67%   |
| Marvell Technology Group         | 17        | 1.85%   |
| Nvidia                           | 10        | 1.09%   |
| ASIX Electronics                 | 10        | 1.09%   |
| Lenovo                           | 9         | 0.98%   |
| Broadcom Limited                 | 7         | 0.76%   |
| DisplayLink                      | 6         | 0.65%   |
| JMicron Technology               | 5         | 0.54%   |
| TP-Link                          | 4         | 0.43%   |
| MediaTek                         | 4         | 0.43%   |
| Hewlett-Packard                  | 3         | 0.33%   |
| Silicon Integrated Systems [SiS] | 2         | 0.22%   |
| Samsung Electronics              | 2         | 0.22%   |
| Motorola PCS                     | 2         | 0.22%   |
| Attansic Technology              | 2         | 0.22%   |
| Apple                            | 2         | 0.22%   |
| ADMtek                           | 2         | 0.22%   |
| Xiaomi                           | 1         | 0.11%   |
| VIA Technologies                 | 1         | 0.11%   |
| OPPO Electronics                 | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.11%   |
| Microchip Technology             | 1         | 0.11%   |
| Huawei Technologies              | 1         | 0.11%   |
| Google                           | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 306       | 32.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 79        | 8.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 66        | 7.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 37        | 3.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 1.93%   |
| Intel Ethernet Connection I218-LM                                 | 18        | 1.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14        | 1.5%    |
| Intel Ethernet Connection I219-LM                                 | 13        | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 1.39%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 1.39%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 1.29%   |
| Intel Ethernet Connection (6) I219-V                              | 11        | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 1.18%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 1.18%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 1.07%   |
| Intel Ethernet Connection (6) I219-LM                             | 9         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 0.86%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.86%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 7         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 6         | 0.64%   |
| Intel Ethernet Connection (13) I219-LM                            | 6         | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 5         | 0.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.54%   |
| Intel Ethernet Connection (16) I219-LM                            | 5         | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.54%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 4         | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 0.43%   |
| Lenovo ThinkPad Lan                                               | 4         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 992       | 52.4%   |
| Ethernet | 879       | 46.43%  |
| Modem    | 19        | 1%      |
| Unknown  | 3         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 785       | 71.69%  |
| Ethernet | 310       | 28.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 782       | 77.66%  |
| 1     | 199       | 19.76%  |
| 3     | 14        | 1.39%   |
| 0     | 11        | 1.09%   |
| 4     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 728       | 70.27%  |
| Yes  | 308       | 29.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 403       | 52.2%   |
| Realtek Semiconductor           | 72        | 9.33%   |
| Qualcomm Atheros Communications | 51        | 6.61%   |
| Broadcom                        | 43        | 5.57%   |
| IMC Networks                    | 37        | 4.79%   |
| Foxconn / Hon Hai               | 34        | 4.4%    |
| Dell                            | 25        | 3.24%   |
| Hewlett-Packard                 | 24        | 3.11%   |
| Lite-On Technology              | 21        | 2.72%   |
| Apple                           | 21        | 2.72%   |
| Toshiba                         | 11        | 1.42%   |
| Ralink                          | 5         | 0.65%   |
| ASUSTek Computer                | 5         | 0.65%   |
| Alps Electric                   | 5         | 0.65%   |
| Foxconn International           | 4         | 0.52%   |
| Cambridge Silicon Radio         | 4         | 0.52%   |
| Ralink Technology               | 3         | 0.39%   |
| MediaTek                        | 2         | 0.26%   |
| Realtek                         | 1         | 0.13%   |
| Micro Star International        | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 146       | 18.91%  |
| Intel AX200 Bluetooth                               | 73        | 9.46%   |
| Intel AX201 Bluetooth                               | 63        | 8.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 54        | 6.99%   |
| Realtek Bluetooth Radio                             | 42        | 5.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 25        | 3.24%   |
| Realtek  Bluetooth 4.2 Adapter                      | 19        | 2.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 2.2%    |
| IMC Networks Bluetooth Radio                        | 15        | 1.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 1.81%   |
| Intel Bluetooth Device                              | 13        | 1.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 1.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 1.55%   |
| IMC Networks Bluetooth Device                       | 12        | 1.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 12        | 1.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 1.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 1.42%   |
| Apple Bluetooth Host Controller                     | 11        | 1.42%   |
| Dell DW375 Bluetooth Module                         | 10        | 1.3%    |
| Broadcom HP Portable SoftSailing                    | 10        | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 1.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 1.17%   |
| Broadcom BCM2045B (BDC-2.1)                         | 8         | 1.04%   |
| Apple Bluetooth USB Host Controller                 | 8         | 1.04%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 7         | 0.91%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.91%   |
| Intel AX210 Bluetooth                               | 6         | 0.78%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 0.78%   |
| Realtek RTL8821A Bluetooth                          | 5         | 0.65%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.65%   |
| Lite-On Bluetooth Device                            | 5         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.65%   |
| Toshiba Bluetooth Device                            | 4         | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 0.52%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 0.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.39%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.39%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 3         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 822       | 64.17%  |
| AMD                                  | 200       | 15.61%  |
| Nvidia                               | 169       | 13.19%  |
| C-Media Electronics                  | 11        | 0.86%   |
| Realtek Semiconductor                | 10        | 0.78%   |
| GN Netcom                            | 9         | 0.7%    |
| Logitech                             | 7         | 0.55%   |
| Hewlett-Packard                      | 7         | 0.55%   |
| Plantronics                          | 6         | 0.47%   |
| Lenovo                               | 3         | 0.23%   |
| Corsair                              | 3         | 0.23%   |
| Texas Instruments                    | 2         | 0.16%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.16%   |
| Roland                               | 2         | 0.16%   |
| Razer USA                            | 2         | 0.16%   |
| Kingston Technology                  | 2         | 0.16%   |
| Apple                                | 2         | 0.16%   |
| VIA Technologies                     | 1         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.08%   |
| SteelSeries ApS                      | 1         | 0.08%   |
| Sennheiser Communications            | 1         | 0.08%   |
| Samson Technologies                  | 1         | 0.08%   |
| RODE Microphones                     | 1         | 0.08%   |
| QinHeng Electronics                  | 1         | 0.08%   |
| Pioneer DJ                           | 1         | 0.08%   |
| Pioneer                              | 1         | 0.08%   |
| OPPO Electronics                     | 1         | 0.08%   |
| M-Audio                              | 1         | 0.08%   |
| JMTek                                | 1         | 0.08%   |
| Guillemot                            | 1         | 0.08%   |
| Focusrite-Novation                   | 1         | 0.08%   |
| FIFINE Microphones                   | 1         | 0.08%   |
| DSEA A/S                             | 1         | 0.08%   |
| Dell                                 | 1         | 0.08%   |
| Bose                                 | 1         | 0.08%   |
| Audio-Technica                       | 1         | 0.08%   |
| ASUSTek Computer                     | 1         | 0.08%   |
| Alesis                               | 1         | 0.08%   |
| AKAI                                 | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 108       | 7.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 101       | 6.61%   |
| AMD Family 17h/19h HD Audio Controller                                     | 98        | 6.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 71        | 4.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 60        | 3.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 49        | 3.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 44        | 2.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 43        | 2.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 43        | 2.81%   |
| Intel 8 Series HD Audio Controller                                         | 43        | 2.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 41        | 2.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 40        | 2.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 40        | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 34        | 2.23%   |
| AMD FCH Azalia Controller                                                  | 30        | 1.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 29        | 1.9%    |
| Intel Broadwell-U Audio Controller                                         | 29        | 1.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 29        | 1.9%    |
| Intel Comet Lake PCH cAVS                                                  | 27        | 1.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24        | 1.57%   |
| Intel CM238 HD Audio Controller                                            | 24        | 1.57%   |
| AMD Kabini HDMI/DP Audio                                                   | 24        | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 22        | 1.44%   |
| Intel Comet Lake PCH-LP cAVS                                               | 21        | 1.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 19        | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                              | 19        | 1.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 19        | 1.24%   |
| Nvidia GK107 HDMI Audio Controller                                         | 15        | 0.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 14        | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 12        | 0.79%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 12        | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11        | 0.72%   |
| AMD Wrestler HDMI Audio                                                    | 11        | 0.72%   |
| Realtek Semiconductor USB Audio                                            | 10        | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 10        | 0.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 0.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 9         | 0.59%   |
| Nvidia GP106 High Definition Audio Controller                              | 8         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 195       | 30.81%  |
| SK hynix            | 152       | 24.01%  |
| Micron Technology   | 76        | 12.01%  |
| Kingston            | 64        | 10.11%  |
| Unknown             | 32        | 5.06%   |
| Crucial             | 28        | 4.42%   |
| Elpida              | 19        | 3%      |
| Ramaxel Technology  | 14        | 2.21%   |
| Corsair             | 13        | 2.05%   |
| Nanya Technology    | 12        | 1.9%    |
| A-DATA Technology   | 9         | 1.42%   |
| Unknown (ABCD)      | 5         | 0.79%   |
| Timetec             | 2         | 0.32%   |
| GOODRAM             | 2         | 0.32%   |
| Unknown             | 2         | 0.32%   |
| Unknown (09D5)      | 1         | 0.16%   |
| Unifosa             | 1         | 0.16%   |
| TRS STAR            | 1         | 0.16%   |
| Transcend           | 1         | 0.16%   |
| Team                | 1         | 0.16%   |
| Patriot             | 1         | 0.16%   |
| G.Skill             | 1         | 0.16%   |
| A-DA                | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.17%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 1.17%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 1.17%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 1.17%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.02%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 1.02%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 7         | 1.02%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.02%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 7         | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.73%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.73%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.73%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.73%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s                 | 5         | 0.73%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.73%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.73%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.73%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 5         | 0.73%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.58%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.58%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.58%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 4         | 0.58%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.58%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.58%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.58%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s            | 4         | 0.58%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 4         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.58%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 4         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 3         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 3         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 276       | 49.46%  |
| DDR3    | 195       | 34.95%  |
| DDR2    | 26        | 4.66%   |
| LPDDR3  | 22        | 3.94%   |
| LPDDR4  | 15        | 2.69%   |
| SDRAM   | 14        | 2.51%   |
| DDR5    | 5         | 0.9%    |
| LPDDR5  | 3         | 0.54%   |
| Unknown | 2         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 506       | 91.01%  |
| Row Of Chips | 42        | 7.55%   |
| Chip         | 4         | 0.72%   |
| DIMM         | 3         | 0.54%   |
| Unknown      | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 239       | 39.64%  |
| 4096  | 170       | 28.19%  |
| 16384 | 110       | 18.24%  |
| 2048  | 60        | 9.95%   |
| 32768 | 13        | 2.16%   |
| 1024  | 10        | 1.66%   |
| 8     | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 134       | 22.41%  |
| 3200    | 118       | 19.73%  |
| 2667    | 115       | 19.23%  |
| 2400    | 50        | 8.36%   |
| 2133    | 40        | 6.69%   |
| 1334    | 31        | 5.18%   |
| 1333    | 21        | 3.51%   |
| 667     | 14        | 2.34%   |
| Unknown | 12        | 2.01%   |
| 1067    | 10        | 1.67%   |
| 2048    | 8         | 1.34%   |
| 4800    | 7         | 1.17%   |
| 3266    | 6         | 1%      |
| 800     | 6         | 1%      |
| 4267    | 5         | 0.84%   |
| 4199    | 4         | 0.67%   |
| 1867    | 4         | 0.67%   |
| 975     | 4         | 0.67%   |
| 8400    | 3         | 0.5%    |
| 6400    | 2         | 0.33%   |
| 5500    | 1         | 0.17%   |
| 4266    | 1         | 0.17%   |
| 3000    | 1         | 0.17%   |
| 1066    | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 42.86%  |
| Samsung Electronics | 2         | 28.57%  |
| Prolific Technology | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-472x Series       | 1         | 14.29%  |
| Samsung ML-1660 Series        | 1         | 14.29%  |
| Prolific PL2305 Parallel Port | 1         | 14.29%  |
| HP LaserJet CM1415fn          | 1         | 14.29%  |
| HP Deskjet F4500 series       | 1         | 14.29%  |
| HP DeskJet 3700 series        | 1         | 14.29%  |
| Canon TS5100 series           | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 40%     |
| Canon           | 2         | 40%     |
| Hewlett-Packard | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 20%     |
| Seiko Epson GT-X750 [Perfection 4490 Photo]      | 1         | 20%     |
| HP scanjet 8270                                  | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20               | 1         | 20%     |
| Canon CanoScan 3200F                             | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 231       | 26.07%  |
| Microdia                               | 97        | 10.95%  |
| Realtek Semiconductor                  | 79        | 8.92%   |
| IMC Networks                           | 69        | 7.79%   |
| Sunplus Innovation Technology          | 46        | 5.19%   |
| Quanta                                 | 41        | 4.63%   |
| Suyin                                  | 39        | 4.4%    |
| Bison Electronics                      | 37        | 4.18%   |
| Lite-On Technology                     | 35        | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 34        | 3.84%   |
| Acer                                   | 30        | 3.39%   |
| Syntek                                 | 28        | 3.16%   |
| Apple                                  | 17        | 1.92%   |
| Luxvisions Innotech Limited            | 15        | 1.69%   |
| Ricoh                                  | 14        | 1.58%   |
| Alcor Micro                            | 13        | 1.47%   |
| Logitech                               | 8         | 0.9%    |
| Silicon Motion                         | 6         | 0.68%   |
| Samsung Electronics                    | 6         | 0.68%   |
| Primax Electronics                     | 5         | 0.56%   |
| Lenovo                                 | 4         | 0.45%   |
| Importek                               | 4         | 0.45%   |
| Z-Star Microelectronics                | 3         | 0.34%   |
| ALi                                    | 3         | 0.34%   |
| Sonix Technology                       | 2         | 0.23%   |
| Pixart Imaging                         | 2         | 0.23%   |
| OPPO Electronics                       | 2         | 0.23%   |
| WaveRider Communications               | 1         | 0.11%   |
| Trust                                  | 1         | 0.11%   |
| SunplusIT                              | 1         | 0.11%   |
| STEREOLABS                             | 1         | 0.11%   |
| Panasonic (Matsushita)                 | 1         | 0.11%   |
| Mustek Systems                         | 1         | 0.11%   |
| icSpring                               | 1         | 0.11%   |
| Goertek Electronics                    | 1         | 0.11%   |
| Genesys Logic                          | 1         | 0.11%   |
| Foxconn / Hon Hai                      | 1         | 0.11%   |
| Dell                                   | 1         | 0.11%   |
| Cubeternet                             | 1         | 0.11%   |
| Creative Technology                    | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 34        | 3.82%   |
| Microdia Integrated_Webcam_HD                                              | 33        | 3.71%   |
| Chicony Integrated Camera                                                  | 30        | 3.37%   |
| IMC Networks Integrated Camera                                             | 28        | 3.15%   |
| Chicony HD WebCam                                                          | 18        | 2.02%   |
| Syntek Integrated Camera                                                   | 17        | 1.91%   |
| Microdia Integrated Webcam                                                 | 16        | 1.8%    |
| Quanta HP HD Camera                                                        | 15        | 1.69%   |
| Chicony USB2.0 Camera                                                      | 15        | 1.69%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 14        | 1.57%   |
| Chicony HP HD Webcam                                                       | 12        | 1.35%   |
| Sunplus HD WebCam                                                          | 11        | 1.24%   |
| Lite-On Integrated Camera                                                  | 11        | 1.24%   |
| Lite-On HP HD Camera                                                       | 11        | 1.24%   |
| Chicony HP HD Camera                                                       | 11        | 1.24%   |
| Chicony USB2.0 HD UVC WebCam                                               | 9         | 1.01%   |
| Acer BisonCam,NB Pro                                                       | 9         | 1.01%   |
| Chicony USB 2.0 Camera                                                     | 8         | 0.9%    |
| Chicony TOSHIBA Web Camera - HD                                            | 8         | 0.9%    |
| Chicony Integrated Camera (1280x720@30)                                    | 8         | 0.9%    |
| Acer Integrated Camera                                                     | 8         | 0.9%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 7         | 0.79%   |
| Realtek USB Camera                                                         | 7         | 0.79%   |
| Chicony Integrated HP HD Webcam                                            | 7         | 0.79%   |
| Bison Integrated Camera                                                    | 7         | 0.79%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 6         | 0.67%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 6         | 0.67%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 6         | 0.67%   |
| Microdia Integrated_Webcam_FHD                                             | 6         | 0.67%   |
| Lite-On HP HD Webcam                                                       | 6         | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 6         | 0.67%   |
| Chicony HP Wide Vision HD Camera                                           | 6         | 0.67%   |
| Chicony HP TrueVision HD Camera                                            | 6         | 0.67%   |
| Chicony EasyCamera                                                         | 6         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 6         | 0.67%   |
| Bison SunplusIT Integrated Camera                                          | 6         | 0.67%   |
| Bison BisonCam, NB Pro                                                     | 6         | 0.67%   |
| Acer HD Webcam                                                             | 6         | 0.67%   |
| Sunplus Integrated_Webcam_HD                                               | 5         | 0.56%   |
| Sunplus Asus Webcam                                                        | 5         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 76        | 36.71%  |
| Synaptics                          | 69        | 33.33%  |
| Shenzhen Goodix Technology         | 19        | 9.18%   |
| AuthenTec                          | 15        | 7.25%   |
| LighTuning Technology              | 9         | 4.35%   |
| Upek                               | 7         | 3.38%   |
| STMicroelectronics                 | 7         | 3.38%   |
| Elan Microelectronics              | 4         | 1.93%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.48%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 12.56%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 10.14%  |
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 5.31%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 3.86%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 3.86%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 3.86%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 3.38%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 3.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 2.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 2.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.9%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 2.9%    |
| Validity Sensors VFS491                                                    | 5         | 2.42%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.42%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.42%   |
| AuthenTec AES2810                                                          | 5         | 2.42%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.93%   |
| Synaptics WBDI Device                                                      | 4         | 1.93%   |
| Synaptics UWP WBDI                                                         | 4         | 1.93%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.93%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 1.93%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.45%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.45%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.45%   |
| AuthenTec AES1600                                                          | 3         | 1.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.97%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.97%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.97%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 0.97%   |
| Synaptics WBDI                                                             | 2         | 0.97%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.97%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.97%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.48%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.48%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.48%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.48%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.48%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.48%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 62        | 41.61%  |
| Alcor Micro                       | 47        | 31.54%  |
| O2 Micro                          | 13        | 8.72%   |
| Lenovo                            | 9         | 6.04%   |
| VASCO Data Security International | 4         | 2.68%   |
| Realtek Semiconductor             | 3         | 2.01%   |
| OmniKey                           | 3         | 2.01%   |
| Upek                              | 2         | 1.34%   |
| Advanced Card Systems             | 2         | 1.34%   |
| SCM Microsystems                  | 1         | 0.67%   |
| Integrated Technology Express     | 1         | 0.67%   |
| Gemalto (was Gemplus)             | 1         | 0.67%   |
| Clay Logic                        | 1         | 0.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 46        | 30.87%  |
| Broadcom 58200                                                               | 22        | 14.77%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 12.08%  |
| Broadcom 5880                                                                | 14        | 9.4%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 6.71%   |
| Lenovo Integrated Smart Card Reader                                          | 9         | 6.04%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 5.37%   |
| VASCO Data Security International DIGIPASS 870                               | 3         | 2.01%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 2.01%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 2.01%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.34%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.34%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.67%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.67%   |
| OmniKey CardMan 4321                                                         | 1         | 0.67%   |
| Integrated Technology Express SmartCard Reader                               | 1         | 0.67%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.67%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.67%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.67%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.67%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 589       | 56.42%  |
| 1     | 362       | 34.67%  |
| 2     | 74        | 7.09%   |
| 3     | 15        | 1.44%   |
| 4     | 2         | 0.19%   |
| 8     | 1         | 0.1%    |
| 6     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 203       | 37.52%  |
| Chipcard                 | 105       | 19.41%  |
| Graphics card            | 96        | 17.74%  |
| Net/wireless             | 39        | 7.21%   |
| Multimedia controller    | 22        | 4.07%   |
| Camera                   | 14        | 2.59%   |
| Storage                  | 11        | 2.03%   |
| Communication controller | 10        | 1.85%   |
| Card reader              | 10        | 1.85%   |
| Bluetooth                | 9         | 1.66%   |
| Net/ethernet             | 7         | 1.29%   |
| Flash memory             | 4         | 0.74%   |
| Sound                    | 3         | 0.55%   |
| Network                  | 3         | 0.55%   |
| Modem                    | 3         | 0.55%   |
| Unassigned class         | 1         | 0.18%   |
| Storage/ide              | 1         | 0.18%   |

