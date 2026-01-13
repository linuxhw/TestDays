Linux in Costa Rica - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

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

Total: 428

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite C45-A             | [77b66b2e02](https://linux-hardware.org/?probe=77b66b2e02) | Dec 22, 2025 |
| HP            | Pavilion dv6                | [2ac9f001db](https://linux-hardware.org/?probe=2ac9f001db) | Dec 07, 2025 |
| HP            | Laptop 15-ef2xxx            | [d548a7cca2](https://linux-hardware.org/?probe=d548a7cca2) | Nov 25, 2025 |
| HP            | Pavilion dv6                | [f0677cf414](https://linux-hardware.org/?probe=f0677cf414) | Nov 24, 2025 |
| Dell          | Latitude 5480               | [93e994452a](https://linux-hardware.org/?probe=93e994452a) | Nov 21, 2025 |
| HP            | ZBook 15 G6                 | [a8c0e68ff4](https://linux-hardware.org/?probe=a8c0e68ff4) | Nov 11, 2025 |
| HP            | Pavilion Laptop 15-eh3xx... | [575587426f](https://linux-hardware.org/?probe=575587426f) | Nov 05, 2025 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [80c85090ee](https://linux-hardware.org/?probe=80c85090ee) | Nov 01, 2025 |
| Dell          | Precision 5530              | [3d4820c80e](https://linux-hardware.org/?probe=3d4820c80e) | Oct 31, 2025 |
| Lenovo        | Legion 5 15IMH05 82AU       | [7856a8097f](https://linux-hardware.org/?probe=7856a8097f) | Oct 29, 2025 |
| HP            | Laptop 15-dw3xxx            | [215194c9f3](https://linux-hardware.org/?probe=215194c9f3) | Oct 22, 2025 |
| Acer          | Aspire A315-58              | [8549aeb987](https://linux-hardware.org/?probe=8549aeb987) | Oct 21, 2025 |
| Chuwi         | MiniBook X                  | [107ba5c65d](https://linux-hardware.org/?probe=107ba5c65d) | Oct 10, 2025 |
| Lenovo        | ThinkPad T440p 20AWA0X00... | [b4feab5ac0](https://linux-hardware.org/?probe=b4feab5ac0) | Oct 09, 2025 |
| Toshiba       | Satellite C55-C             | [b5a81e32ac](https://linux-hardware.org/?probe=b5a81e32ac) | Oct 08, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [648cf323e6](https://linux-hardware.org/?probe=648cf323e6) | Oct 04, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4e46c71662](https://linux-hardware.org/?probe=4e46c71662) | Oct 04, 2025 |
| Dell          | Precision 5530              | [02a3829142](https://linux-hardware.org/?probe=02a3829142) | Oct 02, 2025 |
| Sony          | VPCSB35FL                   | [21433b11ac](https://linux-hardware.org/?probe=21433b11ac) | Sep 24, 2025 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [0daca3b2c5](https://linux-hardware.org/?probe=0daca3b2c5) | Sep 24, 2025 |
| HP            | EliteBook 840 G6            | [35c82a243a](https://linux-hardware.org/?probe=35c82a243a) | Sep 18, 2025 |
| Dell          | Vostro 3400                 | [ad15b9ddff](https://linux-hardware.org/?probe=ad15b9ddff) | Sep 18, 2025 |
| HP            | Laptop 15-ef2xxx            | [f29d7c94bf](https://linux-hardware.org/?probe=f29d7c94bf) | Sep 07, 2025 |
| HP            | ZBook 15 G6                 | [322743fc38](https://linux-hardware.org/?probe=322743fc38) | Sep 06, 2025 |
| Dell          | Latitude 5480               | [3019d55201](https://linux-hardware.org/?probe=3019d55201) | Sep 04, 2025 |
| HP            | Laptop 17-cn3xxx            | [26123fce6a](https://linux-hardware.org/?probe=26123fce6a) | Sep 03, 2025 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [3bbb13e52e](https://linux-hardware.org/?probe=3bbb13e52e) | Aug 24, 2025 |
| System76      | Darter Pro                  | [bc6a4cf761](https://linux-hardware.org/?probe=bc6a4cf761) | Aug 17, 2025 |
| HP            | Laptop 15-da2xxx            | [a4d332bd7d](https://linux-hardware.org/?probe=a4d332bd7d) | Aug 10, 2025 |
| HP            | ZBook 15 G6                 | [c59160de34](https://linux-hardware.org/?probe=c59160de34) | Aug 06, 2025 |
| Chuwi         | MiniBook X                  | [7108f47d05](https://linux-hardware.org/?probe=7108f47d05) | Aug 04, 2025 |
| MSI           | MS-7C91                     | [db94be2d1d](https://linux-hardware.org/?probe=db94be2d1d) | Aug 04, 2025 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [aaf84cc3f8](https://linux-hardware.org/?probe=aaf84cc3f8) | Jul 29, 2025 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [0261e8ac3a](https://linux-hardware.org/?probe=0261e8ac3a) | Jul 29, 2025 |
| HP            | ProBook 640 G3              | [cd44fad51b](https://linux-hardware.org/?probe=cd44fad51b) | Jul 29, 2025 |
| Acer          | Aspire 4738                 | [33b9a3aeea](https://linux-hardware.org/?probe=33b9a3aeea) | Jul 29, 2025 |
| HP            | Pavilion dv6                | [055941f549](https://linux-hardware.org/?probe=055941f549) | Jul 24, 2025 |
| Apple         | MacBookPro8,1               | [8551ce0b30](https://linux-hardware.org/?probe=8551ce0b30) | Jul 23, 2025 |
| Apple         | MacBookPro8,1               | [7b834bb702](https://linux-hardware.org/?probe=7b834bb702) | Jul 23, 2025 |
| HP            | Pavilion dv6                | [0d67e8183f](https://linux-hardware.org/?probe=0d67e8183f) | Jul 20, 2025 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [7b3e394085](https://linux-hardware.org/?probe=7b3e394085) | Jul 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [b759d856f9](https://linux-hardware.org/?probe=b759d856f9) | Jul 15, 2025 |
| HP            | ZBook Firefly 15 G7 Mobi... | [719f63beeb](https://linux-hardware.org/?probe=719f63beeb) | Jul 12, 2025 |
| MSI           | PRO Z790-A MAX WIFI         | [83b7ef3ed0](https://linux-hardware.org/?probe=83b7ef3ed0) | Jul 05, 2025 |
| Chuwi         | MiniBook X                  | [397c70f19d](https://linux-hardware.org/?probe=397c70f19d) | Jul 01, 2025 |
| HP            | Pavilion dv6                | [b25edc2e93](https://linux-hardware.org/?probe=b25edc2e93) | Jun 27, 2025 |
| Dell          | Latitude 3540               | [e4288f74d1](https://linux-hardware.org/?probe=e4288f74d1) | Jun 15, 2025 |
| Toshiba       | Satellite C55-C             | [4bc0f65b19](https://linux-hardware.org/?probe=4bc0f65b19) | Jun 03, 2025 |
| Dell          | Precision 5530              | [61f6056247](https://linux-hardware.org/?probe=61f6056247) | Jun 02, 2025 |
| Toshiba       | Satellite C55-C             | [1479a19681](https://linux-hardware.org/?probe=1479a19681) | May 27, 2025 |
| HP            | Laptop 15-da0xxx            | [7c449be419](https://linux-hardware.org/?probe=7c449be419) | May 25, 2025 |
| Apple         | MacBookPro16,2              | [2629fccdf0](https://linux-hardware.org/?probe=2629fccdf0) | May 20, 2025 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [3a9a3490ad](https://linux-hardware.org/?probe=3a9a3490ad) | May 20, 2025 |
| Dell          | Latitude E5430 non-vPro     | [04e3a5e32c](https://linux-hardware.org/?probe=04e3a5e32c) | May 12, 2025 |
| Dell          | Latitude E5430 non-vPro     | [bae1356b6f](https://linux-hardware.org/?probe=bae1356b6f) | May 12, 2025 |
| HP            | ZBook Firefly 15 G7 Mobi... | [c8daf79761](https://linux-hardware.org/?probe=c8daf79761) | May 12, 2025 |
| Dell          | Latitude E5430 non-vPro     | [4e30062380](https://linux-hardware.org/?probe=4e30062380) | May 12, 2025 |
| Dell          | Latitude E6430              | [f175e1c5db](https://linux-hardware.org/?probe=f175e1c5db) | May 12, 2025 |
| Dell          | Inspiron 14-3467            | [38da2fbd90](https://linux-hardware.org/?probe=38da2fbd90) | May 09, 2025 |
| Chuwi         | MiniBook X                  | [0715aee2c3](https://linux-hardware.org/?probe=0715aee2c3) | May 01, 2025 |
| Dell          | Precision 5530              | [400faddbab](https://linux-hardware.org/?probe=400faddbab) | Apr 24, 2025 |
| Samsung       | 940XFG                      | [3a46336512](https://linux-hardware.org/?probe=3a46336512) | Apr 24, 2025 |
| Dell          | Inspiron 15 3525            | [4e5d6e50cd](https://linux-hardware.org/?probe=4e5d6e50cd) | Apr 24, 2025 |
| Toshiba       | Satellite C40-A             | [1534b1488a](https://linux-hardware.org/?probe=1534b1488a) | Apr 24, 2025 |
| Apple         | MacBookPro16,2              | [0ee7878102](https://linux-hardware.org/?probe=0ee7878102) | Apr 23, 2025 |
| Apple         | MacBookPro16,2              | [3154d6f792](https://linux-hardware.org/?probe=3154d6f792) | Apr 23, 2025 |
| HP            | Notebook                    | [a41367efb3](https://linux-hardware.org/?probe=a41367efb3) | Apr 16, 2025 |
| Dell          | Precision 5530              | [c9656048e3](https://linux-hardware.org/?probe=c9656048e3) | Apr 12, 2025 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [9a795a9315](https://linux-hardware.org/?probe=9a795a9315) | Apr 08, 2025 |
| Dell          | Precision 5530              | [5bdd3116b0](https://linux-hardware.org/?probe=5bdd3116b0) | Apr 04, 2025 |
| Acer          | Aspire A315-44P             | [46008d86f9](https://linux-hardware.org/?probe=46008d86f9) | Apr 03, 2025 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [371d584a7f](https://linux-hardware.org/?probe=371d584a7f) | Mar 31, 2025 |
| Chuwi         | MiniBook X                  | [80141fc8d4](https://linux-hardware.org/?probe=80141fc8d4) | Mar 30, 2025 |
| HP            | EliteBook 840 G7 Noteboo... | [e6115028e1](https://linux-hardware.org/?probe=e6115028e1) | Mar 29, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [d7fbd7e85d](https://linux-hardware.org/?probe=d7fbd7e85d) | Mar 27, 2025 |
| Acer          | Nitro AN515-57              | [898ee7d999](https://linux-hardware.org/?probe=898ee7d999) | Mar 21, 2025 |
| HP            | ZBook Firefly 15 G7 Mobi... | [b686c55108](https://linux-hardware.org/?probe=b686c55108) | Mar 20, 2025 |
| Apple         | MacBookPro8,1               | [16f9c90be6](https://linux-hardware.org/?probe=16f9c90be6) | Mar 17, 2025 |
| Dell          | Precision 5530              | [e60fdba4b6](https://linux-hardware.org/?probe=e60fdba4b6) | Mar 14, 2025 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0ee63ae562](https://linux-hardware.org/?probe=0ee63ae562) | Mar 12, 2025 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [73b39a0ede](https://linux-hardware.org/?probe=73b39a0ede) | Mar 10, 2025 |
| Apple         | MacBookPro9,2               | [8e77314cdf](https://linux-hardware.org/?probe=8e77314cdf) | Mar 09, 2025 |
| Lenovo        | V130-15IGM 81HL             | [02fa7490d8](https://linux-hardware.org/?probe=02fa7490d8) | Mar 08, 2025 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [c57882b043](https://linux-hardware.org/?probe=c57882b043) | Feb 25, 2025 |
| HP            | Laptop 15-da0xxx            | [99a9f8d81e](https://linux-hardware.org/?probe=99a9f8d81e) | Feb 21, 2025 |
| Dell          | Latitude E7440              | [c94f36ee79](https://linux-hardware.org/?probe=c94f36ee79) | Feb 13, 2025 |
| Dell          | Precision 5530              | [fec2e6bf45](https://linux-hardware.org/?probe=fec2e6bf45) | Jan 29, 2025 |
| Dell          | Precision 5530              | [70cf9fc019](https://linux-hardware.org/?probe=70cf9fc019) | Jan 23, 2025 |
| Acer          | Aspire A315-23              | [f0611430b1](https://linux-hardware.org/?probe=f0611430b1) | Jan 22, 2025 |
| Apple         | MacBookPro8,1               | [82099bc650](https://linux-hardware.org/?probe=82099bc650) | Jan 18, 2025 |
| Dell          | Latitude 5480               | [521cf6926d](https://linux-hardware.org/?probe=521cf6926d) | Jan 18, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [fd8e483f06](https://linux-hardware.org/?probe=fd8e483f06) | Jan 15, 2025 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [97ea06eea2](https://linux-hardware.org/?probe=97ea06eea2) | Jan 13, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a40f8a9531](https://linux-hardware.org/?probe=a40f8a9531) | Jan 05, 2025 |
| HP            | EliteBook 840 G6            | [b2c0345c76](https://linux-hardware.org/?probe=b2c0345c76) | Dec 24, 2024 |
| Acer          | Aspire V5-472               | [4f7f3b1702](https://linux-hardware.org/?probe=4f7f3b1702) | Dec 05, 2024 |
| Acer          | Aspire V5-472               | [f653a24c52](https://linux-hardware.org/?probe=f653a24c52) | Dec 05, 2024 |
| Google        | Kefka                       | [1bab1809fc](https://linux-hardware.org/?probe=1bab1809fc) | Nov 27, 2024 |
| Samsung       | 300E5K/300E5Q               | [073b6e567f](https://linux-hardware.org/?probe=073b6e567f) | Nov 26, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6a69e8dd2b](https://linux-hardware.org/?probe=6a69e8dd2b) | Nov 14, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [cb6f1609b1](https://linux-hardware.org/?probe=cb6f1609b1) | Oct 27, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [6028ccb88f](https://linux-hardware.org/?probe=6028ccb88f) | Oct 25, 2024 |
| Dell          | Latitude E5470              | [430ace52f3](https://linux-hardware.org/?probe=430ace52f3) | Oct 24, 2024 |
| Apple         | MacBookPro16,2              | [6e69e5e4a4](https://linux-hardware.org/?probe=6e69e5e4a4) | Oct 23, 2024 |
| HP            | ProBook 4510s               | [82921bfaa3](https://linux-hardware.org/?probe=82921bfaa3) | Oct 16, 2024 |
| HP            | Notebook                    | [5d34e36859](https://linux-hardware.org/?probe=5d34e36859) | Oct 12, 2024 |
| Dell          | Inspiron 3543               | [8867a3f043](https://linux-hardware.org/?probe=8867a3f043) | Oct 05, 2024 |
| Dell          | Latitude 7420               | [bdec0be003](https://linux-hardware.org/?probe=bdec0be003) | Sep 30, 2024 |
| Acer          | Aspire A315-44P             | [a60bab1d76](https://linux-hardware.org/?probe=a60bab1d76) | Sep 16, 2024 |
| Acer          | Aspire A315-44P             | [a2e4ae9bf4](https://linux-hardware.org/?probe=a2e4ae9bf4) | Sep 16, 2024 |
| Apple         | MacBookPro8,1               | [606582cd82](https://linux-hardware.org/?probe=606582cd82) | Sep 10, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b92c75fb55](https://linux-hardware.org/?probe=b92c75fb55) | Aug 26, 2024 |
| HP            | EliteBook 8540w             | [37bf22daf9](https://linux-hardware.org/?probe=37bf22daf9) | Aug 16, 2024 |
| HP            | EliteBook 8540w             | [e96ce0732d](https://linux-hardware.org/?probe=e96ce0732d) | Aug 16, 2024 |
| Acer          | Aspire 5742                 | [280430e59d](https://linux-hardware.org/?probe=280430e59d) | Jul 30, 2024 |
| HP            | Laptop 15-da0xxx            | [ed33f895c9](https://linux-hardware.org/?probe=ed33f895c9) | Jul 28, 2024 |
| Samsung       | 700T1C                      | [33a6415fdc](https://linux-hardware.org/?probe=33a6415fdc) | Jul 07, 2024 |
| Toshiba       | Satellite L755              | [f146c7cd82](https://linux-hardware.org/?probe=f146c7cd82) | Jul 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [845660f83a](https://linux-hardware.org/?probe=845660f83a) | Jul 06, 2024 |
| Acer          | Aspire E1-431               | [7927c359f4](https://linux-hardware.org/?probe=7927c359f4) | Jul 05, 2024 |
| Apple         | MacBookPro8,1               | [b749879a8b](https://linux-hardware.org/?probe=b749879a8b) | Jul 04, 2024 |
| TCL Commun... | 8085                        | [e0f28c27e1](https://linux-hardware.org/?probe=e0f28c27e1) | Jul 03, 2024 |
| TCL Commun... | 8085                        | [9163504543](https://linux-hardware.org/?probe=9163504543) | Jul 03, 2024 |
| HP            | Laptop 15-dy1xxx            | [91276fd4b3](https://linux-hardware.org/?probe=91276fd4b3) | Jul 02, 2024 |
| Dell          | Inspiron N4010              | [dad60b8122](https://linux-hardware.org/?probe=dad60b8122) | Jun 20, 2024 |
| Apple         | MacBookPro8,1               | [2639f09193](https://linux-hardware.org/?probe=2639f09193) | Jun 19, 2024 |
| Dell          | Latitude 7410               | [51a29349b7](https://linux-hardware.org/?probe=51a29349b7) | Jun 02, 2024 |
| Dell          | Latitude E5470              | [0471527291](https://linux-hardware.org/?probe=0471527291) | May 30, 2024 |
| Dell          | Latitude E5470              | [cb017d9ab6](https://linux-hardware.org/?probe=cb017d9ab6) | May 29, 2024 |
| Dell          | XPS 15 9560                 | [35684afb98](https://linux-hardware.org/?probe=35684afb98) | May 28, 2024 |
| Unknown       | Unknown                     | [c9abc346e8](https://linux-hardware.org/?probe=c9abc346e8) | May 27, 2024 |
| Dell          | XPS 15 9560                 | [134bad9ba1](https://linux-hardware.org/?probe=134bad9ba1) | May 25, 2024 |
| Samsung       | 930X2K/931X2K               | [f69d6ceb2c](https://linux-hardware.org/?probe=f69d6ceb2c) | May 23, 2024 |
| Samsung       | 930X2K/931X2K               | [032615adcb](https://linux-hardware.org/?probe=032615adcb) | May 23, 2024 |
| HP            | Notebook                    | [143a137ce0](https://linux-hardware.org/?probe=143a137ce0) | May 17, 2024 |
| HP            | Laptop 14-ck0xxx            | [94f1e2e58a](https://linux-hardware.org/?probe=94f1e2e58a) | May 16, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | [a0a81ab433](https://linux-hardware.org/?probe=a0a81ab433) | May 11, 2024 |
| Apple         | MacBookPro8,1               | [ac1a840bb3](https://linux-hardware.org/?probe=ac1a840bb3) | May 10, 2024 |
| Apple         | MacBookPro8,1               | [f6c6a3c2cb](https://linux-hardware.org/?probe=f6c6a3c2cb) | Apr 28, 2024 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | [a9c83df6f3](https://linux-hardware.org/?probe=a9c83df6f3) | Apr 20, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | [0ccf03f0d9](https://linux-hardware.org/?probe=0ccf03f0d9) | Apr 13, 2024 |
| Apple         | MacBookPro8,1               | [ab1cbc61a9](https://linux-hardware.org/?probe=ab1cbc61a9) | Mar 30, 2024 |
| Valve         | Jupiter                     | [a4d5199429](https://linux-hardware.org/?probe=a4d5199429) | Mar 23, 2024 |
| Unknown       | WY133A                      | [de159f4170](https://linux-hardware.org/?probe=de159f4170) | Mar 20, 2024 |
| Unknown       | WY133A                      | [1abe291a71](https://linux-hardware.org/?probe=1abe291a71) | Mar 20, 2024 |
| Dell          | XPS 15 9530                 | [4cfd0ba254](https://linux-hardware.org/?probe=4cfd0ba254) | Mar 13, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | [b136a57d61](https://linux-hardware.org/?probe=b136a57d61) | Mar 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [644841f4df](https://linux-hardware.org/?probe=644841f4df) | Mar 07, 2024 |
| EVOO          | EV-C-125-3                  | [d452f3776a](https://linux-hardware.org/?probe=d452f3776a) | Feb 26, 2024 |
| HP            | EliteBook 840 G6            | [997fde90ec](https://linux-hardware.org/?probe=997fde90ec) | Feb 26, 2024 |
| HP            | EliteBook 840 G6            | [49371cd72c](https://linux-hardware.org/?probe=49371cd72c) | Feb 23, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [496f8751d2](https://linux-hardware.org/?probe=496f8751d2) | Feb 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [8888984d3d](https://linux-hardware.org/?probe=8888984d3d) | Feb 14, 2024 |
| Acer          | Aspire E5-473               | [0a294c97ee](https://linux-hardware.org/?probe=0a294c97ee) | Jan 31, 2024 |
| HP            | Pavilion g4                 | [1edc58a524](https://linux-hardware.org/?probe=1edc58a524) | Jan 22, 2024 |
| GPU Compan... | GWTN141-10                  | [cd417ed644](https://linux-hardware.org/?probe=cd417ed644) | Jan 10, 2024 |
| GPU Compan... | GWTN141-10                  | [443e0e2a67](https://linux-hardware.org/?probe=443e0e2a67) | Jan 04, 2024 |
| HP            | G60                         | [a151a8084c](https://linux-hardware.org/?probe=a151a8084c) | Jan 01, 2024 |
| HP            | Laptop 15-da0xxx            | [4e00c088e8](https://linux-hardware.org/?probe=4e00c088e8) | Dec 29, 2023 |
| Lenovo        | ThinkPad T420 4236DA4       | [1188c1619d](https://linux-hardware.org/?probe=1188c1619d) | Dec 20, 2023 |
| Dell          | XPS 15 9560                 | [bb58136a7c](https://linux-hardware.org/?probe=bb58136a7c) | Dec 18, 2023 |
| Dell          | G15 5515                    | [259739c8b5](https://linux-hardware.org/?probe=259739c8b5) | Dec 14, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [6b350f2aaf](https://linux-hardware.org/?probe=6b350f2aaf) | Dec 11, 2023 |
| HP            | EliteBook 8470p             | [c723bcc62a](https://linux-hardware.org/?probe=c723bcc62a) | Dec 07, 2023 |
| Apple         | MacBookPro8,1               | [7d8d9279cd](https://linux-hardware.org/?probe=7d8d9279cd) | Nov 21, 2023 |
| Apple         | MacBookPro5,4               | [7045b84f52](https://linux-hardware.org/?probe=7045b84f52) | Nov 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [af8edff0b6](https://linux-hardware.org/?probe=af8edff0b6) | Nov 15, 2023 |
| Toshiba       | Satellite L845              | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| Apple         | MacBookPro16,2              | [9266111091](https://linux-hardware.org/?probe=9266111091) | Oct 27, 2023 |
| Dell          | Inspiron 3443               | [bbe3093cb4](https://linux-hardware.org/?probe=bbe3093cb4) | Oct 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [d8335b95a8](https://linux-hardware.org/?probe=d8335b95a8) | Oct 19, 2023 |
| Apple         | MacBookPro8,1               | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| HP            | Laptop 15-da0xxx            | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| HP            | EliteBook 745 G3            | [a814d9fa4b](https://linux-hardware.org/?probe=a814d9fa4b) | Sep 25, 2023 |
| HP            | Mini 110-1000               | [dda4d7a910](https://linux-hardware.org/?probe=dda4d7a910) | Sep 18, 2023 |
| HP            | Mini 110-1000               | [ee2d142228](https://linux-hardware.org/?probe=ee2d142228) | Sep 18, 2023 |
| Apple         | MacBookPro8,1               | [c7b5f9224a](https://linux-hardware.org/?probe=c7b5f9224a) | Sep 17, 2023 |
| ASUSTek       | X541UV                      | [a66fcc9edb](https://linux-hardware.org/?probe=a66fcc9edb) | Sep 11, 2023 |
| Sony          | SVE14123CLW                 | [2fffba7739](https://linux-hardware.org/?probe=2fffba7739) | Sep 08, 2023 |
| Dell          | Inspiron 5567               | [3b740d65f2](https://linux-hardware.org/?probe=3b740d65f2) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [40693c0171](https://linux-hardware.org/?probe=40693c0171) | Aug 29, 2023 |
| Lenovo        | B590 20208                  | [65bf0970da](https://linux-hardware.org/?probe=65bf0970da) | Aug 27, 2023 |
| Dell          | Latitude E6420              | [ae48a8c618](https://linux-hardware.org/?probe=ae48a8c618) | Aug 26, 2023 |
| MSI           | Katana 15 B13VGK            | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b65293c5a8](https://linux-hardware.org/?probe=b65293c5a8) | Aug 17, 2023 |
| HP            | EliteBook 840 G3            | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Samsung       | 930X2K/931X2K               | [5985901bef](https://linux-hardware.org/?probe=5985901bef) | Aug 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [ec5a50d1d8](https://linux-hardware.org/?probe=ec5a50d1d8) | Jul 29, 2023 |
| ASUSTek       | Q551LN                      | [ad2abcddcf](https://linux-hardware.org/?probe=ad2abcddcf) | Jul 27, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Toshiba       | Satellite L755              | [cb309977d0](https://linux-hardware.org/?probe=cb309977d0) | Jul 08, 2023 |
| Samsung       | 930X2K/931X2K               | [fd0d25039d](https://linux-hardware.org/?probe=fd0d25039d) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | [294e57d915](https://linux-hardware.org/?probe=294e57d915) | Jul 07, 2023 |
| Dell          | Inspiron 5593               | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [3e3987b43f](https://linux-hardware.org/?probe=3e3987b43f) | Jun 20, 2023 |
| HP            | ENVY 15                     | [101fb8810b](https://linux-hardware.org/?probe=101fb8810b) | Jun 19, 2023 |
| HP            | Notebook                    | [42558904aa](https://linux-hardware.org/?probe=42558904aa) | Jun 10, 2023 |
| Apple         | MacBookPro8,1               | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1aa286ccff](https://linux-hardware.org/?probe=1aa286ccff) | Jun 03, 2023 |
| HP            | Notebook                    | [c246477ea2](https://linux-hardware.org/?probe=c246477ea2) | May 31, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [360e8fd5e5](https://linux-hardware.org/?probe=360e8fd5e5) | May 30, 2023 |
| HP            | Notebook                    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Samsung       | 930X2K/931X2K               | [14eae60f4f](https://linux-hardware.org/?probe=14eae60f4f) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | [7ac717a41d](https://linux-hardware.org/?probe=7ac717a41d) | May 13, 2023 |
| Apple         | MacBookPro9,2               | [ba104d9250](https://linux-hardware.org/?probe=ba104d9250) | May 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b06388c1f4](https://linux-hardware.org/?probe=b06388c1f4) | May 09, 2023 |
| Samsung       | 930X2K/931X2K               | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [36ec2bb4c2](https://linux-hardware.org/?probe=36ec2bb4c2) | Apr 22, 2023 |
| HP            | ProBook 6570b               | [2b01f67020](https://linux-hardware.org/?probe=2b01f67020) | Apr 14, 2023 |
| Samsung       | 930X2K/931X2K               | [126c7a430c](https://linux-hardware.org/?probe=126c7a430c) | Apr 13, 2023 |
| Samsung       | 930X2K/931X2K               | [80d44eb98b](https://linux-hardware.org/?probe=80d44eb98b) | Apr 12, 2023 |
| HP            | EliteBook 8560p             | [2ecc0fe5bc](https://linux-hardware.org/?probe=2ecc0fe5bc) | Apr 07, 2023 |
| Apple         | MacBookPro8,1               | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Laptop 15-da0xxx            | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| Google        | Snappy                      | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| Apple         | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Acer          | Aspire E1-431               | [f56a2c21cf](https://linux-hardware.org/?probe=f56a2c21cf) | Mar 26, 2023 |
| Dell          | XPS 15 9510                 | [d8fee2b6b1](https://linux-hardware.org/?probe=d8fee2b6b1) | Mar 08, 2023 |
| Acer          | Aspire V3-571G              | [b02e34a7f9](https://linux-hardware.org/?probe=b02e34a7f9) | Feb 25, 2023 |
| Unknown       | Unknown                     | [6707aef886](https://linux-hardware.org/?probe=6707aef886) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Acer          | Aspire A515-45              | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| HP            | Laptop 14-dk1xxx            | [8761a4096a](https://linux-hardware.org/?probe=8761a4096a) | Jan 22, 2023 |
| HP            | Laptop 14-dk1xxx            | [7099ccff2f](https://linux-hardware.org/?probe=7099ccff2f) | Jan 22, 2023 |
| HP            | Laptop 15-da0xxx            | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| Apple         | MacBookPro8,1               | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| HP            | Laptop 15-da0xxx            | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Toshiba       | Satellite S55-A             | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| HP            | Unknown                     | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Apple         | MacBookPro8,1               | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Toshiba       | Satellite S55-A             | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | [a6f536ca3d](https://linux-hardware.org/?probe=a6f536ca3d) | Oct 25, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | [813bd112f8](https://linux-hardware.org/?probe=813bd112f8) | Oct 25, 2022 |
| MSI           | GF65 Thin 10SDR             | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| Dell          | Inspiron 3493               | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell          | G3 3579                     | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| Dell          | Inspiron 3543               | [68d1385b7e](https://linux-hardware.org/?probe=68d1385b7e) | Aug 28, 2022 |
| Toshiba       | Satellite C55-C             | [99faef3f00](https://linux-hardware.org/?probe=99faef3f00) | Aug 20, 2022 |
| Toshiba       | Satellite L655              | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Toshiba       | Satellite C55-C             | [992b4f4910](https://linux-hardware.org/?probe=992b4f4910) | Aug 06, 2022 |
| ASUSTek       | GL552VW                     | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Acer          | Aspire E5-576               | [a31ceb9a36](https://linux-hardware.org/?probe=a31ceb9a36) | Jul 31, 2022 |
| Acer          | Aspire R3-131T              | [f4efe63bf8](https://linux-hardware.org/?probe=f4efe63bf8) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | [a06c4e1f6b](https://linux-hardware.org/?probe=a06c4e1f6b) | Jul 13, 2022 |
| Deffad        | Unknown                     | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| Dell          | Inspiron 3520               | [b865370f11](https://linux-hardware.org/?probe=b865370f11) | Jun 28, 2022 |
| Lenovo        | ThinkPad P50 20EN001PUS     | [52ef9383a4](https://linux-hardware.org/?probe=52ef9383a4) | Jun 09, 2022 |
| Lenovo        | ThinkPad T440s 20ARS29U0... | [50de8ad2e9](https://linux-hardware.org/?probe=50de8ad2e9) | Jun 01, 2022 |
| Dell          | Latitude 7400               | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Dell          | Inspiron 5565               | [d5a8629a31](https://linux-hardware.org/?probe=d5a8629a31) | May 19, 2022 |
| Lenovo        | ThinkPad L420 7829AA4       | [9c1bbe8cf2](https://linux-hardware.org/?probe=9c1bbe8cf2) | May 14, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [637af2dcc6](https://linux-hardware.org/?probe=637af2dcc6) | Apr 29, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| HP            | Pavilion Notebook           | [a1130d8070](https://linux-hardware.org/?probe=a1130d8070) | Apr 13, 2022 |
| Acer          | Nitro AN515-43              | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell          | Latitude E5500              | [13be4a0a1b](https://linux-hardware.org/?probe=13be4a0a1b) | Mar 16, 2022 |
| Dell          | Latitude E5500              | [d5f8fd7890](https://linux-hardware.org/?probe=d5f8fd7890) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | [b7b428082a](https://linux-hardware.org/?probe=b7b428082a) | Mar 05, 2022 |
| Dell          | XPS 13 9305                 | [8807d99cb4](https://linux-hardware.org/?probe=8807d99cb4) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [c0adf77f3f](https://linux-hardware.org/?probe=c0adf77f3f) | Feb 26, 2022 |
| Sony          | SVD13215PLB                 | [82c4287f85](https://linux-hardware.org/?probe=82c4287f85) | Feb 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [8468cd0da9](https://linux-hardware.org/?probe=8468cd0da9) | Feb 19, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [80e2f3c47e](https://linux-hardware.org/?probe=80e2f3c47e) | Feb 19, 2022 |
| Apple         | MacBookPro8,1               | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| HP            | Laptop 15-da0xxx            | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [dbc7cbcfe1](https://linux-hardware.org/?probe=dbc7cbcfe1) | Feb 07, 2022 |
| Toshiba       | Satellite L45-B             | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Dell          | Latitude 5490               | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | EliteBook 8460p             | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| Dell          | Inspiron 3595               | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Apple         | MacBookPro8,1               | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| HP            | EliteBook 8460p             | [5bb3c9bc8b](https://linux-hardware.org/?probe=5bb3c9bc8b) | Oct 19, 2021 |
| Apple         | MacBookPro8,1               | [bfadd59ae5](https://linux-hardware.org/?probe=bfadd59ae5) | Oct 18, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Acer          | Aspire 5750                 | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| HP            | Laptop 15-da0xxx            | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Dell          | Latitude D620               | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| Apple         | MacBookPro8,1               | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| HP            | EliteBook 820 G1            | [00b3e62e2e](https://linux-hardware.org/?probe=00b3e62e2e) | Sep 10, 2021 |
| MSI           | GF75 Thin 9SD               | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| Olivetti      | CL133A                      | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| HP            | Pavilion g4                 | [3f01790d4e](https://linux-hardware.org/?probe=3f01790d4e) | Jul 21, 2021 |
| AZW           | GT-R                        | [115230aa47](https://linux-hardware.org/?probe=115230aa47) | Jul 19, 2021 |
| Olivetti      | CL133A                      | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| ASUSTek       | U46E                        | [720dec33c4](https://linux-hardware.org/?probe=720dec33c4) | Jul 14, 2021 |
| HP            | ProBook 6460b               | [b39eb9b256](https://linux-hardware.org/?probe=b39eb9b256) | Jul 13, 2021 |
| Dell          | G3 3590                     | [3781e31377](https://linux-hardware.org/?probe=3781e31377) | Jul 12, 2021 |
| Olivetti      | CL133A                      | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| HP            | EliteBook 8570p             | [ab19b80507](https://linux-hardware.org/?probe=ab19b80507) | Jun 09, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| HP            | Pavilion dv6000 (RP297UA... | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Dell          | Inspiron 5584               | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| Toshiba       | Satellite C845              | [e3b90e238b](https://linux-hardware.org/?probe=e3b90e238b) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | [6f3c2aa3be](https://linux-hardware.org/?probe=6f3c2aa3be) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | [8ccda2ce59](https://linux-hardware.org/?probe=8ccda2ce59) | May 24, 2021 |
| Toshiba       | Satellite C845              | [4d346e2691](https://linux-hardware.org/?probe=4d346e2691) | May 24, 2021 |
| Dell          | Inspiron 5584               | [5e2e76f838](https://linux-hardware.org/?probe=5e2e76f838) | May 20, 2021 |
| Acer          | Aspire A515-43              | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| Apple         | MacBookPro8,1               | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [93286a0d38](https://linux-hardware.org/?probe=93286a0d38) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [796f490bbb](https://linux-hardware.org/?probe=796f490bbb) | May 15, 2021 |
| Dell          | Inspiron 5584               | [1da876ea0b](https://linux-hardware.org/?probe=1da876ea0b) | May 06, 2021 |
| Dell          | Inspiron 5584               | [0216a041d2](https://linux-hardware.org/?probe=0216a041d2) | May 05, 2021 |
| HP            | Laptop 15-da0xxx            | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| Acer          | Aspire A515-43              | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP            | Pavilion dv6                | [a181ae8691](https://linux-hardware.org/?probe=a181ae8691) | Apr 30, 2021 |
| HP            | Pavilion dv6                | [d363966e4c](https://linux-hardware.org/?probe=d363966e4c) | Apr 30, 2021 |
| HP            | Pavilion dv6                | [204cd9c44f](https://linux-hardware.org/?probe=204cd9c44f) | Apr 30, 2021 |
| HP            | Pavilion dv6                | [e20fc33e2b](https://linux-hardware.org/?probe=e20fc33e2b) | Apr 29, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [3cca89aa74](https://linux-hardware.org/?probe=3cca89aa74) | Apr 28, 2021 |
| HP            | Laptop 15-da0xxx            | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [38c505f6bd](https://linux-hardware.org/?probe=38c505f6bd) | Apr 23, 2021 |
| Apple         | MacBook2,1                  | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| HP            | Laptop 15-da0xxx            | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e990abe7f1](https://linux-hardware.org/?probe=e990abe7f1) | Apr 11, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [41c14db0ef](https://linux-hardware.org/?probe=41c14db0ef) | Apr 11, 2021 |
| Dell          | G3 3590                     | [3c952dbc96](https://linux-hardware.org/?probe=3c952dbc96) | Mar 26, 2021 |
| Toshiba       | QOSMIO X775                 | [d8f82a3984](https://linux-hardware.org/?probe=d8f82a3984) | Mar 26, 2021 |
| HP            | OMEN by Laptop              | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| HP            | Pavilion g4                 | [1e7372e4f2](https://linux-hardware.org/?probe=1e7372e4f2) | Mar 01, 2021 |
| Toshiba       | Satellite C45-A             | [e00317dc4d](https://linux-hardware.org/?probe=e00317dc4d) | Mar 01, 2021 |
| Unknown       | Unknown                     | [941e941403](https://linux-hardware.org/?probe=941e941403) | Feb 27, 2021 |
| Dell          | Inspiron 5584               | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Google        | Celes                       | [b30c090b2b](https://linux-hardware.org/?probe=b30c090b2b) | Feb 22, 2021 |
| Dell          | Inspiron 3558               | [41ba11dbb4](https://linux-hardware.org/?probe=41ba11dbb4) | Feb 18, 2021 |
| Dell          | Inspiron 5584               | [660afa073b](https://linux-hardware.org/?probe=660afa073b) | Feb 11, 2021 |
| Dell          | Inspiron 5584               | [840e0e2818](https://linux-hardware.org/?probe=840e0e2818) | Feb 04, 2021 |
| Dell          | Inspiron 5584               | [e10690d1d2](https://linux-hardware.org/?probe=e10690d1d2) | Feb 04, 2021 |
| HP            | Laptop 14-dq1xxx            | [84c932e071](https://linux-hardware.org/?probe=84c932e071) | Feb 02, 2021 |
| Dell          | Inspiron 5584               | [473419d486](https://linux-hardware.org/?probe=473419d486) | Jan 24, 2021 |
| Dell          | Inspiron 5584               | [738e03e488](https://linux-hardware.org/?probe=738e03e488) | Jan 23, 2021 |
| Dell          | Precision M4800             | [f24be700aa](https://linux-hardware.org/?probe=f24be700aa) | Jan 21, 2021 |
| Dell          | Precision M4800             | [316c7dd34b](https://linux-hardware.org/?probe=316c7dd34b) | Jan 21, 2021 |
| HP            | Laptop 14-bp0xx             | [4badbab2db](https://linux-hardware.org/?probe=4badbab2db) | Jan 19, 2021 |
| Dell          | Inspiron 5584               | [1a731e13e0](https://linux-hardware.org/?probe=1a731e13e0) | Jan 18, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6a0e9eff49](https://linux-hardware.org/?probe=6a0e9eff49) | Jan 16, 2021 |
| Dell          | Inspiron 5584               | [76fe08b67a](https://linux-hardware.org/?probe=76fe08b67a) | Jan 14, 2021 |
| Dell          | Inspiron 5584               | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 5584               | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| HP            | Laptop 14-bp0xx             | [a481e8e9c0](https://linux-hardware.org/?probe=a481e8e9c0) | Dec 16, 2020 |
| HP            | Laptop 14-bp0xx             | [266b8d7543](https://linux-hardware.org/?probe=266b8d7543) | Dec 16, 2020 |
| MSI           | GE60 2OC\2OD\2OE            | [a305c14111](https://linux-hardware.org/?probe=a305c14111) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| Dell          | Latitude 7480               | [2e569dcaed](https://linux-hardware.org/?probe=2e569dcaed) | Oct 22, 2020 |
| Dell          | Latitude 7480               | [1cc0a03f18](https://linux-hardware.org/?probe=1cc0a03f18) | Oct 22, 2020 |
| Dell          | XPS 15 9560                 | [9f10520397](https://linux-hardware.org/?probe=9f10520397) | Oct 11, 2020 |
| Dell          | G3 3590                     | [4c2ddd8b88](https://linux-hardware.org/?probe=4c2ddd8b88) | Oct 01, 2020 |
| Toshiba       | Satellite C55-B             | [6acb0908ff](https://linux-hardware.org/?probe=6acb0908ff) | Sep 18, 2020 |
| HP            | Unknown                     | [a446c81ca9](https://linux-hardware.org/?probe=a446c81ca9) | Sep 10, 2020 |
| HP            | EliteBook 8570p             | [48e494142e](https://linux-hardware.org/?probe=48e494142e) | Aug 27, 2020 |
| Toshiba       | Satellite X205              | [b0d5e7d0dd](https://linux-hardware.org/?probe=b0d5e7d0dd) | Aug 26, 2020 |
| Toshiba       | Satellite X205              | [45e52f3631](https://linux-hardware.org/?probe=45e52f3631) | Aug 26, 2020 |
| Acer          | Aspire 4739Z                | [44ec59d132](https://linux-hardware.org/?probe=44ec59d132) | Aug 11, 2020 |
| HP            | Pavilion dv2500             | [4bdd603282](https://linux-hardware.org/?probe=4bdd603282) | Aug 06, 2020 |
| HP            | Pavilion dv2500             | [4114f58581](https://linux-hardware.org/?probe=4114f58581) | Aug 06, 2020 |
| Dell          | Latitude E5440              | [9d31b1e38d](https://linux-hardware.org/?probe=9d31b1e38d) | Jul 29, 2020 |
| Dell          | G3 3590                     | [e2fa394ba6](https://linux-hardware.org/?probe=e2fa394ba6) | Jun 28, 2020 |
| Dell          | XPS 15 9560                 | [8119688776](https://linux-hardware.org/?probe=8119688776) | Jun 27, 2020 |
| Dell          | XPS 15 9560                 | [d2a2900148](https://linux-hardware.org/?probe=d2a2900148) | Jun 20, 2020 |
| Dell          | Inspiron 5559               | [4619502a6b](https://linux-hardware.org/?probe=4619502a6b) | May 28, 2020 |
| HP            | ProBook 455 G4              | [6b6fe8e0c1](https://linux-hardware.org/?probe=6b6fe8e0c1) | May 18, 2020 |
| HP            | 245 G4 Notebook PC          | [9311532f56](https://linux-hardware.org/?probe=9311532f56) | Apr 23, 2020 |
| HP            | 245 G4 Notebook PC          | [b662f230b2](https://linux-hardware.org/?probe=b662f230b2) | Apr 23, 2020 |
| HP            | Notebook                    | [5815277bb0](https://linux-hardware.org/?probe=5815277bb0) | Apr 22, 2020 |
| HP            | Laptop 15-da0xxx            | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [2f87bcd627](https://linux-hardware.org/?probe=2f87bcd627) | Apr 07, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [16ff51d343](https://linux-hardware.org/?probe=16ff51d343) | Apr 07, 2020 |
| Acer          | Aspire V3-471               | [024d5b0563](https://linux-hardware.org/?probe=024d5b0563) | Apr 06, 2020 |
| Dell          | G3 3590                     | [26a4f7e20b](https://linux-hardware.org/?probe=26a4f7e20b) | Mar 22, 2020 |
| Dell          | G3 3590                     | [96d9b68953](https://linux-hardware.org/?probe=96d9b68953) | Mar 21, 2020 |
| Toshiba       | Satellite C855D             | [9246f32b7e](https://linux-hardware.org/?probe=9246f32b7e) | Mar 01, 2020 |
| HP            | Pavilion Notebook           | [2bbf18e9e5](https://linux-hardware.org/?probe=2bbf18e9e5) | Feb 20, 2020 |
| HP            | Pavilion Notebook           | [68895d1461](https://linux-hardware.org/?probe=68895d1461) | Feb 20, 2020 |
| HP            | ProBook 6460b               | [121b074dd0](https://linux-hardware.org/?probe=121b074dd0) | Feb 19, 2020 |
| Dell          | Latitude 5500               | [3a7f8e19f1](https://linux-hardware.org/?probe=3a7f8e19f1) | Feb 17, 2020 |
| ASUSTek       | K52F                        | [9dde03d12c](https://linux-hardware.org/?probe=9dde03d12c) | Feb 13, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [9eb64d7269](https://linux-hardware.org/?probe=9eb64d7269) | Jan 17, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [8211b13acf](https://linux-hardware.org/?probe=8211b13acf) | Jan 17, 2020 |
| HP            | 240 G6 Notebook PC          | [73da3dccf1](https://linux-hardware.org/?probe=73da3dccf1) | Nov 14, 2019 |
| HP            | 240 G6 Notebook PC          | [efeee7f2fc](https://linux-hardware.org/?probe=efeee7f2fc) | Nov 14, 2019 |
| System76      | Lemur                       | [a9cc263cb4](https://linux-hardware.org/?probe=a9cc263cb4) | Oct 09, 2019 |
| HP            | ProBook 450 G2              | [c7959cccb3](https://linux-hardware.org/?probe=c7959cccb3) | Sep 30, 2019 |
| HP            | Notebook                    | [163fc3e9dd](https://linux-hardware.org/?probe=163fc3e9dd) | Sep 14, 2019 |
| ASUSTek       | Strix 17 GL703GE            | [c34161a66d](https://linux-hardware.org/?probe=c34161a66d) | Sep 02, 2019 |
| System76      | Lemur                       | [01bbf99115](https://linux-hardware.org/?probe=01bbf99115) | Sep 02, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | [47182bd3e3](https://linux-hardware.org/?probe=47182bd3e3) | Sep 01, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | [2105fa4def](https://linux-hardware.org/?probe=2105fa4def) | Sep 01, 2019 |
| HP            | Notebook                    | [b7e9995b67](https://linux-hardware.org/?probe=b7e9995b67) | Aug 18, 2019 |
| HP            | Notebook                    | [273d0bcc2e](https://linux-hardware.org/?probe=273d0bcc2e) | Aug 18, 2019 |
| Dell          | Venue 11 Pro 7130 vPro      | [2e5b92af00](https://linux-hardware.org/?probe=2e5b92af00) | Aug 17, 2019 |
| Dell          | Latitude E5450              | [3336801ccf](https://linux-hardware.org/?probe=3336801ccf) | Aug 10, 2019 |
| Toshiba       | Satellite A305D             | [ebf0a9c89e](https://linux-hardware.org/?probe=ebf0a9c89e) | Aug 08, 2019 |
| Acer          | SW5-017P                    | [fbf9b74a34](https://linux-hardware.org/?probe=fbf9b74a34) | Jul 29, 2019 |
| Dell          | Latitude 5480               | [f488cfd08f](https://linux-hardware.org/?probe=f488cfd08f) | Jun 22, 2019 |
| ASUSTek       | Strix 17 GL703GE            | [328975f3a5](https://linux-hardware.org/?probe=328975f3a5) | May 15, 2019 |
| Dell          | Latitude 5480               | [694ca16d49](https://linux-hardware.org/?probe=694ca16d49) | May 04, 2019 |
| Purism        | Librem 15 v3                | [00259367c8](https://linux-hardware.org/?probe=00259367c8) | Oct 29, 2018 |
| Purism        | Librem 15 v3                | [c5e1ab1520](https://linux-hardware.org/?probe=c5e1ab1520) | Oct 29, 2018 |
| ASUSTek       | X555LAB                     | [243803142a](https://linux-hardware.org/?probe=243803142a) | Aug 01, 2018 |
| Toshiba       | Satellite C645D             | [9d50eb7fdb](https://linux-hardware.org/?probe=9d50eb7fdb) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 14        | 4.46%   |
| Debian 12                    | 14        | 4.46%   |
| Ubuntu 22.04                 | 13        | 4.14%   |
| Ubuntu 18.04                 | 12        | 3.82%   |
| Zorin 17                     | 8         | 2.55%   |
| Ubuntu 24.04                 | 8         | 2.55%   |
| Zorin 16                     | 7         | 2.23%   |
| OpenMandriva 4.2             | 7         | 2.23%   |
| OpenMandriva 25.06           | 6         | 1.91%   |
| OpenMandriva 5.0             | 5         | 1.59%   |
| OpenMandriva 25.90           | 5         | 1.59%   |
| OpenMandriva 24.12           | 5         | 1.59%   |
| Ubuntu 19.04                 | 4         | 1.27%   |
| Pop!_OS 22.04                | 4         | 1.27%   |
| OpenMandriva 6.0             | 4         | 1.27%   |
| OpenMandriva 4.3             | 4         | 1.27%   |
| Lubuntu 24.04                | 4         | 1.27%   |
| Linux Mint 22.2              | 4         | 1.27%   |
| Linux Mint 22.1              | 4         | 1.27%   |
| Debian 11                    | 4         | 1.27%   |
| Arch Rolling                 | 4         | 1.27%   |
| Ubuntu 23.04                 | 3         | 0.96%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.96%   |
| OpenMandriva 25.03           | 3         | 0.96%   |
| OpenMandriva 23.08           | 3         | 0.96%   |
| Manjaro                      | 3         | 0.96%   |
| Lubuntu 22.10                | 3         | 0.96%   |
| Lubuntu 22.04                | 3         | 0.96%   |
| Lubuntu 21.10                | 3         | 0.96%   |
| Lubuntu 21.04                | 3         | 0.96%   |
| Kubuntu 25.04                | 3         | 0.96%   |
| Fedora 42                    | 3         | 0.96%   |
| Fedora 41                    | 3         | 0.96%   |
| Fedora 38                    | 3         | 0.96%   |
| Xubuntu 20.04                | 2         | 0.64%   |
| Ubuntu Studio 20.04          | 2         | 0.64%   |
| Ubuntu 21.04                 | 2         | 0.64%   |
| ROSA 12.5                    | 2         | 0.64%   |
| OpenMandriva 25.01           | 2         | 0.64%   |
| OpenMandriva 23.03           | 2         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 60        | 21.9%   |
| OpenMandriva     | 42        | 15.33%  |
| Debian           | 22        | 8.03%   |
| Linux Mint       | 21        | 7.66%   |
| Zorin            | 16        | 5.84%   |
| Fedora           | 15        | 5.47%   |
| Manjaro          | 10        | 3.65%   |
| Lubuntu          | 9         | 3.28%   |
| Kubuntu          | 9         | 3.28%   |
| Pop!_OS          | 6         | 2.19%   |
| ROSA             | 5         | 1.82%   |
| Arch             | 5         | 1.82%   |
| Xubuntu          | 3         | 1.09%   |
| openSUSE         | 3         | 1.09%   |
| Nobara           | 3         | 1.09%   |
| KDE neon         | 3         | 1.09%   |
| Kali             | 3         | 1.09%   |
| Ubuntu Unity     | 2         | 0.73%   |
| Ubuntu Studio    | 2         | 0.73%   |
| Ubuntu MATE      | 2         | 0.73%   |
| Ubuntu Budgie    | 2         | 0.73%   |
| SteamOS          | 2         | 0.73%   |
| Parrot           | 2         | 0.73%   |
| LMDE             | 2         | 0.73%   |
| Garuda Linux     | 2         | 0.73%   |
| Endless          | 2         | 0.73%   |
| Elementary       | 2         | 0.73%   |
| BigLinux         | 2         | 0.73%   |
| Bazzite          | 2         | 0.73%   |
| UbuntuDDE        | 1         | 0.36%   |
| Rocky Linux      | 1         | 0.36%   |
| Reborn OS        | 1         | 0.36%   |
| PureOS           | 1         | 0.36%   |
| Peppermint       | 1         | 0.36%   |
| org.kde.Platform | 1         | 0.36%   |
| Mageia           | 1         | 0.36%   |
| LinuxFX          | 1         | 0.36%   |
| Deepin           | 1         | 0.36%   |
| Crystal Linux    | 1         | 0.36%   |
| Clear Linux      | 1         | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 6.14.2-desktop-3omv2590           | 16        | 4.6%    |
| 5.10.14-desktop-1omv4002          | 7         | 2.01%   |
| 6.6.2-desktop-1omv2390            | 5         | 1.44%   |
| 6.12.9-desktop-1omv2490           | 5         | 1.44%   |
| 6.4.11-desktop-1omv2390           | 4         | 1.15%   |
| 5.16.7-desktop-1omv4003           | 4         | 1.15%   |
| 5.0.0-23-generic                  | 4         | 1.15%   |
| 6.8.0-31-generic                  | 3         | 0.86%   |
| 5.4.0-77-generic                  | 3         | 0.86%   |
| 5.4.0-42-generic                  | 3         | 0.86%   |
| 5.19.0-32-generic                 | 3         | 0.86%   |
| 5.19.0-26-generic                 | 3         | 0.86%   |
| 5.13.0-16-generic                 | 3         | 0.86%   |
| 5.11.0-27-generic                 | 3         | 0.86%   |
| 5.0.0-25-generic                  | 3         | 0.86%   |
| 6.8.0-71-generic                  | 2         | 0.57%   |
| 6.8.0-59-generic                  | 2         | 0.57%   |
| 6.8.0-52-generic                  | 2         | 0.57%   |
| 6.8.0-36-generic                  | 2         | 0.57%   |
| 6.6.21-generic-8rosa2021.1-x86_64 | 2         | 0.57%   |
| 6.5.0-5-generic                   | 2         | 0.57%   |
| 6.5.0-41-generic                  | 2         | 0.57%   |
| 6.3.8-200.fc38.x86_64             | 2         | 0.57%   |
| 6.2.6-desktop-1omv2390            | 2         | 0.57%   |
| 6.2.0-20-generic                  | 2         | 0.57%   |
| 6.2.0-18-generic                  | 2         | 0.57%   |
| 6.14.0-15-generic                 | 2         | 0.57%   |
| 6.12.1-desktop-1omv2490           | 2         | 0.57%   |
| 6.11.0-9-generic                  | 2         | 0.57%   |
| 6.1.0-10-amd64                    | 2         | 0.57%   |
| 6.0.6-76060006-generic            | 2         | 0.57%   |
| 5.9.16-1-MANJARO                  | 2         | 0.57%   |
| 5.8.0-50-generic                  | 2         | 0.57%   |
| 5.4.0-21-generic                  | 2         | 0.57%   |
| 5.3.0-40-generic                  | 2         | 0.57%   |
| 5.3.0-28-generic                  | 2         | 0.57%   |
| 5.15.0-91-generic                 | 2         | 0.57%   |
| 5.15.0-83-generic                 | 2         | 0.57%   |
| 5.15.0-58-generic                 | 2         | 0.57%   |
| 5.15.0-52-generic                 | 2         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 23        | 6.91%   |
| 5.15.0  | 22        | 6.61%   |
| 6.8.0   | 20        | 6.01%   |
| 6.14.2  | 16        | 4.8%    |
| 6.1.0   | 14        | 4.2%    |
| 6.5.0   | 13        | 3.9%    |
| 5.11.0  | 11        | 3.3%    |
| 5.19.0  | 10        | 3%      |
| 6.2.0   | 8         | 2.4%    |
| 6.14.0  | 8         | 2.4%    |
| 5.13.0  | 8         | 2.4%    |
| 5.0.0   | 8         | 2.4%    |
| 5.3.0   | 7         | 2.1%    |
| 5.10.14 | 7         | 2.1%    |
| 5.10.0  | 7         | 2.1%    |
| 6.6.2   | 6         | 1.8%    |
| 6.12.9  | 6         | 1.8%    |
| 6.11.0  | 6         | 1.8%    |
| 5.8.0   | 5         | 1.5%    |
| 4.15.0  | 5         | 1.5%    |
| 6.4.11  | 4         | 1.2%    |
| 5.16.7  | 4         | 1.2%    |
| 6.12.1  | 3         | 0.9%    |
| 6.6.21  | 2         | 0.6%    |
| 6.3.8   | 2         | 0.6%    |
| 6.3.6   | 2         | 0.6%    |
| 6.2.6   | 2         | 0.6%    |
| 6.17.8  | 2         | 0.6%    |
| 6.16.4  | 2         | 0.6%    |
| 6.15.7  | 2         | 0.6%    |
| 6.15.4  | 2         | 0.6%    |
| 6.14.8  | 2         | 0.6%    |
| 6.14.7  | 2         | 0.6%    |
| 6.13.8  | 2         | 0.6%    |
| 6.1.1   | 2         | 0.6%    |
| 6.0.6   | 2         | 0.6%    |
| 5.9.16  | 2         | 0.6%    |
| 5.18.13 | 2         | 0.6%    |
| 5.14.0  | 2         | 0.6%    |
| 4.19.0  | 2         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.14    | 29        | 8.92%   |
| 5.4     | 23        | 7.08%   |
| 5.15    | 23        | 7.08%   |
| 6.8     | 21        | 6.46%   |
| 6.1     | 20        | 6.15%   |
| 5.10    | 18        | 5.54%   |
| 6.6     | 15        | 4.62%   |
| 6.5     | 15        | 4.62%   |
| 5.11    | 14        | 4.31%   |
| 6.12    | 13        | 4%      |
| 5.19    | 13        | 4%      |
| 6.2     | 11        | 3.38%   |
| 6.11    | 10        | 3.08%   |
| 5.0     | 9         | 2.77%   |
| 5.13    | 8         | 2.46%   |
| 5.3     | 7         | 2.15%   |
| 6.13    | 6         | 1.85%   |
| 5.8     | 6         | 1.85%   |
| 6.4     | 5         | 1.54%   |
| 6.3     | 5         | 1.54%   |
| 6.15    | 5         | 1.54%   |
| 4.15    | 5         | 1.54%   |
| 6.9     | 4         | 1.23%   |
| 6.16    | 4         | 1.23%   |
| 6.0     | 4         | 1.23%   |
| 5.16    | 4         | 1.23%   |
| 6.17    | 3         | 0.92%   |
| 5.9     | 3         | 0.92%   |
| 5.18    | 3         | 0.92%   |
| 5.12    | 3         | 0.92%   |
| 4.19    | 3         | 0.92%   |
| 6.7     | 2         | 0.62%   |
| 6.10    | 2         | 0.62%   |
| 5.14    | 2         | 0.62%   |
| 4.18    | 2         | 0.62%   |
| 5.7     | 1         | 0.31%   |
| 5.2     | 1         | 0.31%   |
| 5.17    | 1         | 0.31%   |
| 4.9     | 1         | 0.31%   |
| 4.1     | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 255       | 99.22%  |
| i686   | 2         | 0.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 109       | 39.93%  |
| KDE6       | 40        | 14.65%  |
| KDE5       | 39        | 14.29%  |
| XFCE       | 17        | 6.23%   |
| Unknown    | 16        | 5.86%   |
| X-Cinnamon | 14        | 5.13%   |
| LXQt       | 10        | 3.66%   |
| MATE       | 7         | 2.56%   |
| KDE        | 5         | 1.83%   |
| Unity      | 2         | 0.73%   |
| Pantheon   | 2         | 0.73%   |
| i3         | 2         | 0.73%   |
| Deepin     | 2         | 0.73%   |
| DDE        | 2         | 0.73%   |
| Budgie     | 2         | 0.73%   |
| onyx:GNOME | 1         | 0.37%   |
| LXDE       | 1         | 0.37%   |
| Hyprland   | 1         | 0.37%   |
| Cinnamon   | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 167       | 63.02%  |
| Wayland | 88        | 33.21%  |
| Unknown | 8         | 3.02%   |
| Tty     | 2         | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 103       | 38.58%  |
| SDDM    | 76        | 28.46%  |
| GDM3    | 38        | 14.23%  |
| LightDM | 22        | 8.24%   |
| GDM     | 20        | 7.49%   |
| TDM     | 8         | 3%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 117       | 44.32%  |
| es_CR   | 91        | 34.47%  |
| es_ES   | 23        | 8.71%   |
| Unknown | 14        | 5.3%    |
| es_MX   | 11        | 4.17%   |
| C       | 2         | 0.76%   |
| pt_BR   | 1         | 0.38%   |
| fr_FR   | 1         | 0.38%   |
| es_US   | 1         | 0.38%   |
| es_EC   | 1         | 0.38%   |
| es_CO   | 1         | 0.38%   |
| en_AG   | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 141       | 52.81%  |
| BIOS | 126       | 47.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 183       | 68.8%   |
| Btrfs   | 33        | 12.41%  |
| Overlay | 24        | 9.02%   |
| Tmpfs   | 17        | 6.39%   |
| Xfs     | 5         | 1.88%   |
| Unknown | 4         | 1.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 127       | 48.29%  |
| Unknown | 112       | 42.59%  |
| MBR     | 24        | 9.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 237       | 89.77%  |
| Yes       | 27        | 10.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 186       | 70.72%  |
| Yes       | 77        | 29.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 58        | 22.57%  |
| Dell                | 55        | 21.4%   |
| Lenovo              | 44        | 17.12%  |
| Acer                | 19        | 7.39%   |
| Toshiba             | 18        | 7%      |
| ASUSTek Computer    | 16        | 6.23%   |
| Apple               | 13        | 5.06%   |
| MSI                 | 6         | 2.33%   |
| Samsung Electronics | 4         | 1.56%   |
| Chuwi               | 4         | 1.56%   |
| Sony                | 3         | 1.17%   |
| Google              | 3         | 1.17%   |
| Unknown             | 3         | 1.17%   |
| System76            | 2         | 0.78%   |
| Valve               | 1         | 0.39%   |
| TCL Communication   | 1         | 0.39%   |
| Purism              | 1         | 0.39%   |
| Olivetti            | 1         | 0.39%   |
| HUAWEI              | 1         | 0.39%   |
| GPU Company         | 1         | 0.39%   |
| EVOO                | 1         | 0.39%   |
| Deffad              | 1         | 0.39%   |
| AZW                 | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Precision 5530                  | 8         | 3.11%   |
| Apple MacBookPro8,1                  | 7         | 2.72%   |
| Unknown                              | 6         | 2.33%   |
| HP Notebook                          | 4         | 1.56%   |
| Chuwi MiniBook X                     | 4         | 1.56%   |
| Lenovo ThinkPad L14 Gen 2 20X2S89600 | 3         | 1.17%   |
| HP Laptop 15-da0xxx                  | 3         | 1.17%   |
| HP EliteBook 840 G6                  | 3         | 1.17%   |
| Dell Latitude 5480                   | 3         | 1.17%   |
| Dell Inspiron 5584                   | 3         | 1.17%   |
| Toshiba Satellite L755               | 2         | 0.78%   |
| Toshiba Satellite C55-C              | 2         | 0.78%   |
| Toshiba Satellite C45-A              | 2         | 0.78%   |
| Lenovo IdeaPad 1 15IJL7 82LX         | 2         | 0.78%   |
| HP ProBook 6460b                     | 2         | 0.78%   |
| HP Pavilion Notebook                 | 2         | 0.78%   |
| HP Pavilion g4                       | 2         | 0.78%   |
| HP Pavilion dv6                      | 2         | 0.78%   |
| HP Laptop 14-ck0xxx                  | 2         | 0.78%   |
| Dell Latitude E5470                  | 2         | 0.78%   |
| Apple MacBookPro9,2                  | 2         | 0.78%   |
| Apple MacBookPro16,2                 | 2         | 0.78%   |
| Valve Jupiter                        | 1         | 0.39%   |
| Toshiba Satellite X205               | 1         | 0.39%   |
| Toshiba Satellite S55-A              | 1         | 0.39%   |
| Toshiba Satellite L845               | 1         | 0.39%   |
| Toshiba Satellite L655               | 1         | 0.39%   |
| Toshiba Satellite L45-B              | 1         | 0.39%   |
| Toshiba Satellite C855D              | 1         | 0.39%   |
| Toshiba Satellite C845               | 1         | 0.39%   |
| Toshiba Satellite C645D              | 1         | 0.39%   |
| Toshiba Satellite C55-B              | 1         | 0.39%   |
| Toshiba Satellite C40-A              | 1         | 0.39%   |
| Toshiba Satellite A305D              | 1         | 0.39%   |
| Toshiba QOSMIO X775                  | 1         | 0.39%   |
| TCL Communication 8085               | 1         | 0.39%   |
| System76 Lemur                       | 1         | 0.39%   |
| System76 Darter Pro                  | 1         | 0.39%   |
| Sony VPCSB35FL                       | 1         | 0.39%   |
| Sony SVE14123CLW                     | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 28        | 10.89%  |
| Dell Latitude          | 21        | 8.17%   |
| Toshiba Satellite      | 17        | 6.61%   |
| Dell Inspiron          | 16        | 6.23%   |
| Acer Aspire            | 16        | 6.23%   |
| HP Laptop              | 13        | 5.06%   |
| HP EliteBook           | 13        | 5.06%   |
| Lenovo IdeaPad         | 11        | 4.28%   |
| HP Pavilion            | 11        | 4.28%   |
| Dell Precision         | 9         | 3.5%    |
| HP ProBook             | 7         | 2.72%   |
| Apple MacBookPro8      | 7         | 2.72%   |
| Unknown                | 6         | 2.33%   |
| HP Notebook            | 4         | 1.56%   |
| Dell XPS               | 4         | 1.56%   |
| Chuwi MiniBook         | 4         | 1.56%   |
| ASUS VivoBook          | 4         | 1.56%   |
| Lenovo Legion          | 3         | 1.17%   |
| HP ZBook               | 2         | 0.78%   |
| Dell G3                | 2         | 0.78%   |
| ASUS ROG               | 2         | 0.78%   |
| Apple MacBookPro9      | 2         | 0.78%   |
| Apple MacBookPro16     | 2         | 0.78%   |
| Acer Nitro             | 2         | 0.78%   |
| Valve Jupiter          | 1         | 0.39%   |
| Toshiba QOSMIO         | 1         | 0.39%   |
| TCL Communication 8085 | 1         | 0.39%   |
| System76 Lemur         | 1         | 0.39%   |
| System76 Darter        | 1         | 0.39%   |
| Sony VPCSB35FL         | 1         | 0.39%   |
| Sony SVE14123CLW       | 1         | 0.39%   |
| Sony SVD13215PLB       | 1         | 0.39%   |
| Samsung 940XFG         | 1         | 0.39%   |
| Samsung 930X2K         | 1         | 0.39%   |
| Samsung 700T1C         | 1         | 0.39%   |
| Samsung 300E5K         | 1         | 0.39%   |
| Purism Librem          | 1         | 0.39%   |
| Olivetti CL133A        | 1         | 0.39%   |
| MSI MS-7E07            | 1         | 0.39%   |
| MSI MS-7C91            | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 27        | 10.51%  |
| 2018 | 26        | 10.12%  |
| 2020 | 24        | 9.34%   |
| 2011 | 23        | 8.95%   |
| 2021 | 20        | 7.78%   |
| 2012 | 19        | 7.39%   |
| 2016 | 15        | 5.84%   |
| 2015 | 15        | 5.84%   |
| 2017 | 14        | 5.45%   |
| 2013 | 14        | 5.45%   |
| 2014 | 12        | 4.67%   |
| 2023 | 8         | 3.11%   |
| 2010 | 8         | 3.11%   |
| 2024 | 7         | 2.72%   |
| 2022 | 7         | 2.72%   |
| 2008 | 6         | 2.33%   |
| 2009 | 5         | 1.95%   |
| 2007 | 3         | 1.17%   |
| 2006 | 3         | 1.17%   |
| 2025 | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 257       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 241       | 92.69%  |
| Enabled  | 19        | 7.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 253       | 98.44%  |
| Yes  | 4         | 1.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 68        | 25.47%  |
| 8.01-16.0   | 61        | 22.85%  |
| 16.01-24.0  | 44        | 16.48%  |
| 3.01-4.0    | 42        | 15.73%  |
| 32.01-64.0  | 28        | 10.49%  |
| 64.01-256.0 | 9         | 3.37%   |
| 24.01-32.0  | 5         | 1.87%   |
| 1.01-2.0    | 5         | 1.87%   |
| 2.01-3.0    | 4         | 1.5%    |
| 0.51-1.0    | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 100       | 34.84%  |
| 2.01-3.0   | 75        | 26.13%  |
| 3.01-4.0   | 44        | 15.33%  |
| 4.01-8.0   | 43        | 14.98%  |
| 8.01-16.0  | 13        | 4.53%   |
| 0.51-1.0   | 9         | 3.14%   |
| 16.01-24.0 | 3         | 1.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 184       | 69.7%   |
| 2      | 73        | 27.65%  |
| 3      | 6         | 2.27%   |
| 5      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 167       | 64.73%  |
| Yes       | 91        | 35.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 208       | 80.62%  |
| No        | 50        | 19.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 247       | 96.11%  |
| No        | 10        | 3.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 207       | 79.31%  |
| No        | 54        | 20.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Costa Rica | 257       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| San José     | 124       | 43.97%  |
| Heredia       | 40        | 14.18%  |
| Alajuela      | 15        | 5.32%   |
| Quesada       | 10        | 3.55%   |
| Cartago       | 10        | 3.55%   |
| Grecia        | 9         | 3.19%   |
| Pavas         | 6         | 2.13%   |
| Perez Zeledon | 5         | 1.77%   |
| Escazu        | 5         | 1.77%   |
| San Ramon     | 4         | 1.42%   |
| Rio Segundo   | 4         | 1.42%   |
| Puntarenas    | 4         | 1.42%   |
| Santa Cruz    | 3         | 1.06%   |
| Liberia       | 3         | 1.06%   |
| Esparza       | 3         | 1.06%   |
| Siquirres     | 2         | 0.71%   |
| Santa Fe      | 2         | 0.71%   |
| San Pedro     | 2         | 0.71%   |
| Naranjo       | 2         | 0.71%   |
| Colon         | 2         | 0.71%   |
| Bagaces       | 2         | 0.71%   |
| Zarcero       | 1         | 0.35%   |
| Turrialba     | 1         | 0.35%   |
| Tres Rios     | 1         | 0.35%   |
| Santo Domingo | 1         | 0.35%   |
| Santiago      | 1         | 0.35%   |
| San Rafael    | 1         | 0.35%   |
| San Pablo     | 1         | 0.35%   |
| San Juan      | 1         | 0.35%   |
| San Francisco | 1         | 0.35%   |
| San Felipe    | 1         | 0.35%   |
| Quepos        | 1         | 0.35%   |
| Quebrada Palo | 1         | 0.35%   |
| Palmares      | 1         | 0.35%   |
| Nosara        | 1         | 0.35%   |
| Mercedes      | 1         | 0.35%   |
| Limón        | 1         | 0.35%   |
| La Fortuna    | 1         | 0.35%   |
| Jaco          | 1         | 0.35%   |
| Guapiles      | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 40        | 57     | 11.87%  |
| Seagate                     | 38        | 52     | 11.28%  |
| Toshiba                     | 37        | 44     | 10.98%  |
| WDC                         | 34        | 51     | 10.09%  |
| Unknown                     | 22        | 28     | 6.53%   |
| Kingston                    | 19        | 24     | 5.64%   |
| Patriot                     | 14        | 14     | 4.15%   |
| SanDisk                     | 13        | 14     | 3.86%   |
| Intel                       | 13        | 40     | 3.86%   |
| A-DATA Technology           | 10        | 10     | 2.97%   |
| SK hynix                    | 9         | 16     | 2.67%   |
| HGST                        | 9         | 10     | 2.67%   |
| Kingston Technology Company | 7         | 12     | 2.08%   |
| Team                        | 6         | 6      | 1.78%   |
| Realtek Semiconductor       | 6         | 6      | 1.78%   |
| Micron Technology           | 6         | 7      | 1.78%   |
| Crucial                     | 6         | 6      | 1.78%   |
| Silicon Motion              | 5         | 6      | 1.48%   |
| ADATA Technology            | 5         | 9      | 1.48%   |
| Netac                       | 4         | 5      | 1.19%   |
| LITEON                      | 4         | 6      | 1.19%   |
| KIOXIA                      | 4         | 6      | 1.19%   |
| Hitachi                     | 3         | 4      | 0.89%   |
| PNY                         | 2         | 2      | 0.59%   |
| JMicron Technology          | 2         | 2      | 0.59%   |
| Gigabyte Technology         | 2         | 2      | 0.59%   |
| Apple                       | 2         | 2      | 0.59%   |
| Zheino                      | 1         | 1      | 0.3%    |
| Wibtek                      | 1         | 1      | 0.3%    |
| UMIS                        | 1         | 1      | 0.3%    |
| Transcend                   | 1         | 1      | 0.3%    |
| ShiJi                       | 1         | 1      | 0.3%    |
| Phison Electronics          | 1         | 3      | 0.3%    |
| O2 Micro                    | 1         | 1      | 0.3%    |
| Mushkin                     | 1         | 1      | 0.3%    |
| LITEONIT                    | 1         | 1      | 0.3%    |
| Lexar                       | 1         | 1      | 0.3%    |
| Fujitsu                     | 1         | 1      | 0.3%    |
| Dell                        | 1         | 1      | 0.3%    |
| BP4                         | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB                        | 8         | 2.27%   |
| Toshiba MQ01ABD100 1TB                                | 7         | 1.99%   |
| Seagate ST1000LM035-1RK172 1TB                        | 7         | 1.99%   |
| Toshiba MQ01ABF050 500GB                              | 6         | 1.7%    |
| Realtek Patriot M.2 P300 512GB                        | 5         | 1.42%   |
| Patriot M.2 P300 512GB                                | 5         | 1.42%   |
| Kingston SA400S37240G 240GB SSD                       | 5         | 1.42%   |
| Unknown MMC Card  32GB                                | 4         | 1.14%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 4         | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 4         | 1.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 4         | 1.14%   |
| Kingston Company SNV2S1000G 1TB                       | 4         | 1.14%   |
| WDC WDS500G2B0A-00SM50 500GB                          | 3         | 0.85%   |
| Unknown MMC Card  128GB                               | 3         | 0.85%   |
| Toshiba MQ04ABF100 1TB                                | 3         | 0.85%   |
| Toshiba MQ01ABD075 752GB                              | 3         | 0.85%   |
| Toshiba KBG30ZMS256G NVMe 256GB                       | 3         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 3         | 0.85%   |
| LITEON LCH-256V2S 256GB SSD                           | 3         | 0.85%   |
| Intel SSDSC2MH250A2 250GB                             | 3         | 0.85%   |
| Intel SSDSC2BF180A4H 180GB                            | 3         | 0.85%   |
| Intel SSDSA2CW300G3 304GB                             | 3         | 0.85%   |
| HGST HTS541010A9E680 1TB                              | 3         | 0.85%   |
| WDC WD20SPZX-08UA7 2TB                                | 2         | 0.57%   |
| Unknown MMC128  128GB                                 | 2         | 0.57%   |
| Toshiba NVMe SSD Drive 256GB                          | 2         | 0.57%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD               | 2         | 0.57%   |
| SK hynix NVMe SSD Drive 128GB                         | 2         | 0.57%   |
| Seagate ST9500325AS 500GB                             | 2         | 0.57%   |
| Seagate ST500LM021-1KJ152 500GB                       | 2         | 0.57%   |
| SanDisk NVMe SSD Drive 1TB                            | 2         | 0.57%   |
| Samsung MZVLQ256HAJD-000H1 256GB                      | 2         | 0.57%   |
| Samsung MZVL4512HBLU-00BH1 512GB                      | 2         | 0.57%   |
| PNY CS900 500GB SSD                                   | 2         | 0.57%   |
| Patriot P210 256GB SSD                                | 2         | 0.57%   |
| Patriot P210 1024GB SSD                               | 2         | 0.57%   |
| Netac SSD 120GB                                       | 2         | 0.57%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB               | 2         | 0.57%   |
| Kingston SV300S37A120G 120GB SSD                      | 2         | 0.57%   |
| Kingston SA400S37960G 960GB SSD                       | 2         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 36        | 50     | 35.29%  |
| Toshiba            | 28        | 29     | 27.45%  |
| WDC                | 21        | 25     | 20.59%  |
| HGST               | 9         | 10     | 8.82%   |
| Hitachi            | 3         | 4      | 2.94%   |
| JMicron Technology | 2         | 2      | 1.96%   |
| Unknown            | 1         | 1      | 0.98%   |
| Fujitsu            | 1         | 1      | 0.98%   |
| ASMedia            | 1         | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 15        | 16     | 14.42%  |
| Samsung Electronics | 13        | 25     | 12.5%   |
| WDC                 | 9         | 19     | 8.65%   |
| A-DATA Technology   | 9         | 9      | 8.65%   |
| Patriot             | 8         | 8      | 7.69%   |
| Intel               | 8         | 28     | 7.69%   |
| Team                | 5         | 5      | 4.81%   |
| SanDisk             | 5         | 5      | 4.81%   |
| Crucial             | 5         | 5      | 4.81%   |
| Netac               | 4         | 5      | 3.85%   |
| Micron Technology   | 4         | 4      | 3.85%   |
| LITEON              | 4         | 6      | 3.85%   |
| Toshiba             | 2         | 3      | 1.92%   |
| PNY                 | 2         | 2      | 1.92%   |
| Gigabyte Technology | 2         | 2      | 1.92%   |
| Zheino              | 1         | 1      | 0.96%   |
| Wibtek              | 1         | 1      | 0.96%   |
| Transcend           | 1         | 1      | 0.96%   |
| ShiJi               | 1         | 1      | 0.96%   |
| Seagate             | 1         | 1      | 0.96%   |
| Mushkin             | 1         | 1      | 0.96%   |
| LITEONIT            | 1         | 1      | 0.96%   |
| Lexar               | 1         | 1      | 0.96%   |
| BP4                 | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 100       | 123    | 31.35%  |
| NVMe    | 99        | 155    | 31.03%  |
| SSD     | 97        | 151    | 30.41%  |
| MMC     | 20        | 26     | 6.27%   |
| Unknown | 3         | 3      | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 180       | 265    | 58.06%  |
| NVMe | 98        | 154    | 31.61%  |
| MMC  | 20        | 26     | 6.45%   |
| SAS  | 12        | 13     | 3.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 114       | 159    | 58.16%  |
| 0.51-1.0   | 66        | 95     | 33.67%  |
| 1.01-2.0   | 15        | 19     | 7.65%   |
| 2.01-3.0   | 1         | 1      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 73        | 26.35%  |
| 251-500        | 65        | 23.47%  |
| 501-1000       | 44        | 15.88%  |
| 1001-2000      | 24        | 8.66%   |
| 1-20           | 20        | 7.22%   |
| 51-100         | 16        | 5.78%   |
| 21-50          | 13        | 4.69%   |
| More than 3000 | 10        | 3.61%   |
| 2001-3000      | 6         | 2.17%   |
| Unknown        | 6         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 117       | 39.39%  |
| 21-50          | 46        | 15.49%  |
| 101-250        | 44        | 14.81%  |
| 51-100         | 33        | 11.11%  |
| 251-500        | 30        | 10.1%   |
| 501-1000       | 15        | 5.05%   |
| Unknown        | 6         | 2.02%   |
| 1001-2000      | 5         | 1.68%   |
| More than 3000 | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM049-2GH172 1TB                      | 8         | 9      | 24.24%  |
| Realtek Semiconductor Patriot M.2 P300 512GB        | 4         | 4      | 12.12%  |
| WDC WD6400BPVT-55HXZT2 640GB                        | 1         | 1      | 3.03%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 3.03%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 3.03%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 3.03%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.03%   |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 3.03%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 3.03%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 1         | 1      | 3.03%   |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 3.03%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 3.03%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 3.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 3.03%   |
| Samsung Electronics SSD SM841 2.5 7mm 256GB         | 1         | 1      | 3.03%   |
| Netac SSD 120GB                                     | 1         | 2      | 3.03%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 3.03%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 3.03%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 3.03%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 3.03%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 12        | 13     | 36.36%  |
| Toshiba               | 7         | 7      | 21.21%  |
| Realtek Semiconductor | 4         | 4      | 12.12%  |
| WDC                   | 3         | 3      | 9.09%   |
| HGST                  | 2         | 2      | 6.06%   |
| Samsung Electronics   | 1         | 1      | 3.03%   |
| Netac                 | 1         | 2      | 3.03%   |
| Micron Technology     | 1         | 1      | 3.03%   |
| Intel                 | 1         | 1      | 3.03%   |
| Hitachi               | 1         | 2      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 13     | 50%     |
| Toshiba | 6         | 6      | 25%     |
| WDC     | 3         | 3      | 12.5%   |
| HGST    | 2         | 2      | 8.33%   |
| Hitachi | 1         | 2      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 26     | 72.73%  |
| SSD  | 5         | 6      | 15.15%  |
| NVMe | 4         | 4      | 12.12%  |

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
| Detected | 141       | 245    | 51.46%  |
| Works    | 105       | 177    | 38.32%  |
| Malfunc  | 28        | 36     | 10.22%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 179       | 56.29%  |
| AMD                          | 29        | 9.12%   |
| Samsung Electronics          | 27        | 8.49%   |
| SanDisk                      | 13        | 4.09%   |
| Kingston Technology Company  | 11        | 3.46%   |
| Realtek Semiconductor        | 10        | 3.14%   |
| Toshiba America Info Systems | 8         | 2.52%   |
| SK hynix                     | 8         | 2.52%   |
| ADATA Technology             | 7         | 2.2%    |
| Silicon Motion               | 5         | 1.57%   |
| Micron Technology            | 3         | 0.94%   |
| KIOXIA                       | 3         | 0.94%   |
| ASMedia Technology           | 3         | 0.94%   |
| Phison Electronics           | 2         | 0.63%   |
| Nvidia                       | 2         | 0.63%   |
| Hosin Global Electronics     | 2         | 0.63%   |
| Apple                        | 2         | 0.63%   |
| Union Memory (Shenzhen)      | 1         | 0.31%   |
| Solidigm                     | 1         | 0.31%   |
| O2 Micro                     | 1         | 0.31%   |
| Micron/Crucial Technology    | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 24        | 7.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 21        | 6.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 19        | 5.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 19        | 5.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 17        | 4.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 15        | 4.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 11        | 3.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 10        | 2.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 8         | 2.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 8         | 2.35%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                      | 8         | 2.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 8         | 2.35%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 7         | 2.05%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 6         | 1.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 5         | 1.47%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 5         | 1.47%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 5         | 1.47%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 4         | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 1.17%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                          | 4         | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 4         | 1.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 1.17%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                    | 3         | 0.88%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                           | 3         | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 0.88%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                   | 3         | 0.88%   |
| Intel RST Volume Management Device Controller                                          | 3         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 0.88%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                          | 3         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 0.88%   |
| SK hynix PC611 NVMe Solid State Drive                                                  | 2         | 0.59%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 2         | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.59%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)              | 2         | 0.59%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                      | 2         | 0.59%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 2         | 0.59%   |
| Kingston Company NV2 NVMe SSD [E21T] (DRAM-less)                                       | 2         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 177       | 55.14%  |
| NVMe | 100       | 31.15%  |
| RAID | 28        | 8.72%   |
| IDE  | 16        | 4.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 215       | 83.66%  |
| AMD    | 42        | 16.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Xeon E-2176M CPU @ 2.70GHz        | 9         | 3.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 2.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 5         | 1.94%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 5         | 1.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 1.94%   |
| Intel N100                              | 4         | 1.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 1.55%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 4         | 1.55%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 4         | 1.55%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 4         | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 1.55%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 4         | 1.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 1.16%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 3         | 1.16%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 3         | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 3         | 1.16%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 3         | 1.16%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 1.16%   |
| Intel Core i5-2435M CPU @ 2.40GHz       | 3         | 1.16%   |
| Intel Core i3-7020U CPU @ 2.30GHz       | 3         | 1.16%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 3         | 1.16%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 3         | 1.16%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 1.16%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 2         | 0.78%   |
| Intel Core i7-9850H CPU @ 2.60GHz       | 2         | 0.78%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 2         | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 0.78%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 2         | 0.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.78%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 2         | 0.78%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 2         | 0.78%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 0.78%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 2         | 0.78%   |
| Intel Core i5-1038NG7 CPU @ 2.00GHz     | 2         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 59        | 22.87%  |
| Intel Core i7                  | 53        | 20.54%  |
| Other                          | 31        | 12.02%  |
| Intel Core i3                  | 25        | 9.69%   |
| Intel Celeron                  | 19        | 7.36%   |
| AMD Ryzen 7                    | 14        | 5.43%   |
| Intel Xeon                     | 10        | 3.88%   |
| AMD Ryzen 5                    | 8         | 3.1%    |
| Intel Core 2 Duo               | 5         | 1.94%   |
| Intel Atom                     | 4         | 1.55%   |
| Intel Pentium                  | 3         | 1.16%   |
| Intel Core 2                   | 3         | 1.16%   |
| AMD A10                        | 3         | 1.16%   |
| Intel Pentium Silver           | 2         | 0.78%   |
| Intel Genuine                  | 2         | 0.78%   |
| AMD Ryzen 5 PRO                | 2         | 0.78%   |
| AMD Ryzen 3                    | 2         | 0.78%   |
| AMD E1                         | 2         | 0.78%   |
| AMD A8                         | 2         | 0.78%   |
| Intel Pentium Dual-Core        | 1         | 0.39%   |
| Intel Core M                   | 1         | 0.39%   |
| AMD V120                       | 1         | 0.39%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.39%   |
| AMD Turion 64 X2               | 1         | 0.39%   |
| AMD Ryzen 9                    | 1         | 0.39%   |
| AMD PRO A10                    | 1         | 0.39%   |
| AMD E                          | 1         | 0.39%   |
| AMD Athlon                     | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 133       | 51.55%  |
| 4      | 71        | 27.52%  |
| 6      | 25        | 9.69%   |
| 8      | 18        | 6.98%   |
| 12     | 4         | 1.55%   |
| 14     | 2         | 0.78%   |
| 1      | 2         | 0.78%   |
| 24     | 1         | 0.39%   |
| 16     | 1         | 0.39%   |
| 10     | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 257       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 198       | 77.04%  |
| 1      | 59        | 22.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 254       | 98.45%  |
| 32-bit         | 2         | 0.78%   |
| Unknown        | 2         | 0.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 143       | 53.36%  |
| 0x206a7    | 14        | 5.22%   |
| 0x406c4    | 7         | 2.61%   |
| 0x40651    | 7         | 2.61%   |
| 0x306d4    | 7         | 2.61%   |
| 0x406e3    | 6         | 2.24%   |
| 0x306a9    | 6         | 2.24%   |
| 0x08108109 | 6         | 2.24%   |
| 0x806ec    | 5         | 1.87%   |
| 0x806e9    | 5         | 1.87%   |
| 0x906ea    | 4         | 1.49%   |
| 0x706a1    | 4         | 1.49%   |
| 0x306c3    | 4         | 1.49%   |
| 0x1067a    | 4         | 1.49%   |
| 0x806eb    | 3         | 1.12%   |
| 0x806ea    | 3         | 1.12%   |
| 0x806c1    | 3         | 1.12%   |
| 0x20655    | 3         | 1.12%   |
| 0x6fd      | 2         | 0.75%   |
| 0x506e3    | 2         | 0.75%   |
| 0x0a50000d | 2         | 0.75%   |
| 0x05000119 | 2         | 0.75%   |
| 0xb06a2    | 1         | 0.37%   |
| 0xa0652    | 1         | 0.37%   |
| 0x906ed    | 1         | 0.37%   |
| 0x906e9    | 1         | 0.37%   |
| 0x706a8    | 1         | 0.37%   |
| 0x6f6      | 1         | 0.37%   |
| 0x6ec      | 1         | 0.37%   |
| 0x506c9    | 1         | 0.37%   |
| 0x30678    | 1         | 0.37%   |
| 0x106c2    | 1         | 0.37%   |
| 0x0a500014 | 1         | 0.37%   |
| 0x0a50000f | 1         | 0.37%   |
| 0x08a00008 | 1         | 0.37%   |
| 0x08a00006 | 1         | 0.37%   |
| 0x08608102 | 1         | 0.37%   |
| 0x08600106 | 1         | 0.37%   |
| 0x08600104 | 1         | 0.37%   |
| 0x08600103 | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 51        | 19.62%  |
| SandyBridge      | 29        | 11.15%  |
| Unknown          | 18        | 6.92%   |
| Haswell          | 16        | 6.15%   |
| IvyBridge        | 15        | 5.77%   |
| TigerLake        | 13        | 5%      |
| Skylake          | 13        | 5%      |
| Broadwell        | 11        | 4.23%   |
| Silvermont       | 10        | 3.85%   |
| Zen 3            | 9         | 3.46%   |
| Zen+             | 8         | 3.08%   |
| Goldmont plus    | 8         | 3.08%   |
| Westmere         | 7         | 2.69%   |
| IceLake          | 7         | 2.69%   |
| Alderlake Hybrid | 6         | 2.31%   |
| Zen 2            | 5         | 1.92%   |
| Penryn           | 5         | 1.92%   |
| Core             | 5         | 1.92%   |
| Excavator        | 4         | 1.54%   |
| Gracemont        | 3         | 1.15%   |
| Tremont          | 2         | 0.77%   |
| Goldmont         | 2         | 0.77%   |
| CometLake        | 2         | 0.77%   |
| Bobcat           | 2         | 0.77%   |
| Puma             | 1         | 0.38%   |
| Piledriver       | 1         | 0.38%   |
| P6               | 1         | 0.38%   |
| K8 Hammer        | 1         | 0.38%   |
| K8 & K10 hybrid  | 1         | 0.38%   |
| K10 Llano        | 1         | 0.38%   |
| K10              | 1         | 0.38%   |
| Jaguar           | 1         | 0.38%   |
| Bonnell          | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 204       | 65.59%  |
| Nvidia | 58        | 18.65%  |
| AMD    | 49        | 15.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 7.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 4.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 3.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 3.41%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 10        | 3.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.1%    |
| Intel Coffee Lake-S GT2 [UHD Graphics P630]                                              | 9         | 2.79%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 9         | 2.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 2.79%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 8         | 2.48%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 8         | 2.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 2.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.86%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 1.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.55%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 5         | 1.55%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 5         | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.55%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 1.24%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.24%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.24%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.24%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 4         | 1.24%   |
| AMD Lucienne                                                                             | 4         | 1.24%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.93%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.93%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 3         | 0.93%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 0.93%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.93%   |
| AMD Barcelo                                                                              | 3         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.62%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.62%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 154       | 59.92%  |
| Intel + Nvidia | 44        | 17.12%  |
| 1 x AMD        | 34        | 13.23%  |
| 1 x Nvidia     | 9         | 3.5%    |
| 2 x AMD        | 5         | 1.95%   |
| Intel + AMD    | 5         | 1.95%   |
| AMD + Nvidia   | 5         | 1.95%   |
| Other          | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 217       | 83.14%  |
| Proprietary | 27        | 10.34%  |
| Unknown     | 17        | 6.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 199       | 76.25%  |
| 0.01-0.5   | 18        | 6.9%    |
| 1.01-2.0   | 17        | 6.51%   |
| 3.01-4.0   | 14        | 5.36%   |
| 0.51-1.0   | 10        | 3.83%   |
| 5.01-6.0   | 2         | 0.77%   |
| 8.01-16.0  | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 63        | 20%     |
| LG Display              | 52        | 16.51%  |
| BOE                     | 31        | 9.84%   |
| Samsung Electronics     | 29        | 9.21%   |
| Chimei Innolux          | 29        | 9.21%   |
| Dell                    | 15        | 4.76%   |
| Apple                   | 12        | 3.81%   |
| Sharp                   | 11        | 3.49%   |
| Goldstar                | 9         | 2.86%   |
| AOC                     | 9         | 2.86%   |
| Hewlett-Packard         | 5         | 1.59%   |
| Chi Mei Optoelectronics | 5         | 1.59%   |
| JVC                     | 4         | 1.27%   |
| PANDA                   | 3         | 0.95%   |
| Acer                    | 3         | 0.95%   |
| Sony                    | 2         | 0.63%   |
| Lenovo                  | 2         | 0.63%   |
| IFS                     | 2         | 0.63%   |
| CPT                     | 2         | 0.63%   |
| ASUSTek Computer        | 2         | 0.63%   |
| ViewSonic               | 1         | 0.32%   |
| Valve                   | 1         | 0.32%   |
| Sun                     | 1         | 0.32%   |
| RTK                     | 1         | 0.32%   |
| PRISM+                  | 1         | 0.32%   |
| Philips                 | 1         | 0.32%   |
| Panasonic               | 1         | 0.32%   |
| MSI                     | 1         | 0.32%   |
| Mi                      | 1         | 0.32%   |
| LG Philips              | 1         | 0.32%   |
| LED                     | 1         | 0.32%   |
| KDC                     | 1         | 0.32%   |
| ITE                     | 1         | 0.32%   |
| InnoLux Display         | 1         | 0.32%   |
| InfoVision              | 1         | 0.32%   |
| HKC                     | 1         | 0.32%   |
| Hitachi                 | 1         | 0.32%   |
| Hikvision               | 1         | 0.32%   |
| GreenWood               | 1         | 0.32%   |
| Gigabyte Technology     | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 8         | 2.51%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 6         | 1.88%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 5         | 1.57%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 5         | 1.57%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 4         | 1.25%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 4         | 1.25%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 3         | 0.94%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 3         | 0.94%   |
| Dell E2213 DELD04D 1680x1050 473x296mm 22.0-inch                     | 3         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 0.94%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 3         | 0.94%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch       | 3         | 0.94%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 2         | 0.63%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch         | 2         | 0.63%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.63%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 2         | 0.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.63%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 2         | 0.63%   |
| JVC LT-MK24220 JVC2413 1920x1080 530x300mm 24.0-inch                 | 2         | 0.63%   |
| JVC LT-MK24220 JVC2413 1920x1080 530x290mm 23.8-inch                 | 2         | 0.63%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch          | 2         | 0.63%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                    | 2         | 0.63%   |
| Dell AW2518HF DELA103 1920x1080 544x303mm 24.5-inch                  | 2         | 0.63%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                  | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.63%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 2         | 0.63%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch               | 2         | 0.63%   |
| Apple Color LCD APPA03E 2560x1600 286x179mm 13.3-inch                | 2         | 0.63%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch        | 1         | 0.31%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.31%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch               | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 109       | 37.72%  |
| 1366x768 (WXGA)    | 100       | 34.6%   |
| 3840x2160 (4K)     | 14        | 4.84%   |
| 1280x800 (WXGA)    | 14        | 4.84%   |
| 1600x900 (HD+)     | 12        | 4.15%   |
| 2560x1440 (QHD)    | 6         | 2.08%   |
| 1920x1200 (WUXGA)  | 5         | 1.73%   |
| 1680x1050 (WSXGA+) | 4         | 1.38%   |
| 1440x900 (WXGA+)   | 4         | 1.38%   |
| 1280x1024 (SXGA)   | 4         | 1.38%   |
| 2880x1800          | 3         | 1.04%   |
| 2560x1600          | 3         | 1.04%   |
| 1400x1050          | 2         | 0.69%   |
| 1360x768           | 2         | 0.69%   |
| 800x1280           | 1         | 0.35%   |
| 3840x2400          | 1         | 0.35%   |
| 3440x1440          | 1         | 0.35%   |
| 3200x2000          | 1         | 0.35%   |
| 2560x1080          | 1         | 0.35%   |
| 1600x1200          | 1         | 0.35%   |
| 1024x576           | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 118       | 37.46%  |
| 14      | 49        | 15.56%  |
| 13      | 48        | 15.24%  |
| 23      | 12        | 3.81%   |
| 24      | 11        | 3.49%   |
| 21      | 11        | 3.49%   |
| 17      | 10        | 3.17%   |
| 31      | 8         | 2.54%   |
| 19      | 5         | 1.59%   |
| 18      | 5         | 1.59%   |
| 11      | 5         | 1.59%   |
| 27      | 4         | 1.27%   |
| 22      | 4         | 1.27%   |
| 12      | 4         | 1.27%   |
| 84      | 3         | 0.95%   |
| 32      | 3         | 0.95%   |
| 16      | 3         | 0.95%   |
| 72      | 2         | 0.63%   |
| 57      | 2         | 0.63%   |
| Unknown | 2         | 0.63%   |
| 39      | 1         | 0.32%   |
| 34      | 1         | 0.32%   |
| 28      | 1         | 0.32%   |
| 20      | 1         | 0.32%   |
| 10      | 1         | 0.32%   |
| 7       | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 202       | 64.74%  |
| 501-600     | 26        | 8.33%   |
| 201-300     | 25        | 8.01%   |
| 401-500     | 24        | 7.69%   |
| 351-400     | 11        | 3.53%   |
| 601-700     | 9         | 2.88%   |
| 701-800     | 5         | 1.6%    |
| 1501-2000   | 5         | 1.6%    |
| Unknown     | 2         | 0.64%   |
| 801-900     | 1         | 0.32%   |
| 1001-1500   | 1         | 0.32%   |
| 1-100       | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 220       | 82.4%   |
| 16/10 | 36        | 13.48%  |
| 5/4   | 4         | 1.5%    |
| 4/3   | 3         | 1.12%   |
| 21/9  | 2         | 0.75%   |
| 0.67  | 1         | 0.37%   |
| 0.56  | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 116       | 37.18%  |
| 81-90          | 91        | 29.17%  |
| 201-250        | 26        | 8.33%   |
| 351-500        | 12        | 3.85%   |
| 151-200        | 12        | 3.85%   |
| More than 1000 | 7         | 2.24%   |
| 121-130        | 7         | 2.24%   |
| 71-80          | 6         | 1.92%   |
| 141-150        | 6         | 1.92%   |
| 51-60          | 5         | 1.6%    |
| 251-300        | 5         | 1.6%    |
| 111-120        | 5         | 1.6%    |
| 301-350        | 4         | 1.28%   |
| 61-70          | 3         | 0.96%   |
| Unknown        | 2         | 0.64%   |
| 41-50          | 1         | 0.32%   |
| 1-40           | 1         | 0.32%   |
| 131-140        | 1         | 0.32%   |
| 501-1000       | 1         | 0.32%   |
| 91-100         | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 120       | 39.6%   |
| 121-160       | 105       | 34.65%  |
| 51-100        | 51        | 16.83%  |
| 161-240       | 10        | 3.3%    |
| More than 240 | 9         | 2.97%   |
| 1-50          | 6         | 1.98%   |
| Unknown       | 2         | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 197       | 72.69%  |
| 2     | 57        | 21.03%  |
| 0     | 9         | 3.32%   |
| 3     | 6         | 2.21%   |
| 4     | 2         | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 139       | 32.71%  |
| Intel                      | 122       | 28.71%  |
| Qualcomm Atheros           | 61        | 14.35%  |
| Broadcom                   | 37        | 8.71%   |
| MediaTek                   | 13        | 3.06%   |
| Broadcom Limited           | 9         | 2.12%   |
| TP-Link                    | 8         | 1.88%   |
| Shenzhen Goodix Technology | 8         | 1.88%   |
| ASIX Electronics           | 6         | 1.41%   |
| Apple                      | 3         | 0.71%   |
| Xiaomi                     | 2         | 0.47%   |
| Nvidia                     | 2         | 0.47%   |
| Marvell Technology Group   | 2         | 0.47%   |
| Dell                       | 2         | 0.47%   |
| Aquantia                   | 2         | 0.47%   |
| Qualcomm Technologies      | 1         | 0.24%   |
| Qualcomm                   | 1         | 0.24%   |
| Lenovo                     | 1         | 0.24%   |
| JMicron Technology         | 1         | 0.24%   |
| Huawei Technologies        | 1         | 0.24%   |
| Hewlett-Packard            | 1         | 0.24%   |
| DisplayLink                | 1         | 0.24%   |
| D-Link System              | 1         | 0.24%   |
| D-Link                     | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 67        | 13.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 31        | 6.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 20        | 3.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 14        | 2.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 12        | 2.33%   |
| Intel Wi-Fi 6 AX200                                                    | 11        | 2.14%   |
| Intel Wireless 7265                                                    | 10        | 1.95%   |
| Intel Wireless 7260                                                    | 9         | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 1.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 1.75%   |
| Shenzhen Goodix Fingerprint Reader                                     | 8         | 1.56%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 8         | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 8         | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 1.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 8         | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.36%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 7         | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                          | 7         | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.17%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 0.97%   |
| Intel Wireless 8265 / 8275                                             | 5         | 0.97%   |
| Intel Wireless 8260                                                    | 5         | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 4         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4         | 0.78%   |
| Intel Ethernet Controller I225-V                                       | 4         | 0.78%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.78%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 0.78%   |
| Intel Alder Lake-N PCH CNVi WiFi                                       | 4         | 0.78%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 4         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 106       | 40.3%   |
| Qualcomm Atheros      | 50        | 19.01%  |
| Realtek Semiconductor | 45        | 17.11%  |
| Broadcom              | 30        | 11.41%  |
| MediaTek              | 11        | 4.18%   |
| TP-Link               | 8         | 3.04%   |
| Broadcom Limited      | 8         | 3.04%   |
| Dell                  | 2         | 0.76%   |
| Qualcomm              | 1         | 0.38%   |
| D-Link System         | 1         | 0.38%   |
| D-Link                | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 14        | 5.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 12        | 4.48%   |
| Intel Wi-Fi 6 AX200                                                  | 11        | 4.1%    |
| Intel Wireless 7265                                                  | 10        | 3.73%   |
| Intel Wireless 7260                                                  | 9         | 3.36%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 8         | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 8         | 2.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 8         | 2.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 8         | 2.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 7         | 2.61%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 7         | 2.61%   |
| Broadcom BCM43142 802.11b/g/n                                        | 7         | 2.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 2.24%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 2.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 6         | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 5         | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5         | 1.87%   |
| Intel Wireless 8265 / 8275                                           | 5         | 1.87%   |
| Intel Wireless 8260                                                  | 5         | 1.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 1.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 4         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 4         | 1.49%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 4         | 1.49%   |
| Intel Alder Lake-N PCH CNVi WiFi                                     | 4         | 1.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 4         | 1.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 3         | 1.12%   |
| Realtek 802.11ac NIC                                                 | 3         | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 3         | 1.12%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 3         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3         | 1.12%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                            | 2         | 0.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 2         | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 0.75%   |
| Intel Wireless 3160                                                  | 2         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 117       | 51.54%  |
| Intel                    | 52        | 22.91%  |
| Broadcom                 | 17        | 7.49%   |
| Qualcomm Atheros         | 16        | 7.05%   |
| ASIX Electronics         | 6         | 2.64%   |
| Apple                    | 3         | 1.32%   |
| Xiaomi                   | 2         | 0.88%   |
| Nvidia                   | 2         | 0.88%   |
| MediaTek                 | 2         | 0.88%   |
| Marvell Technology Group | 2         | 0.88%   |
| Aquantia                 | 2         | 0.88%   |
| Qualcomm Technologies    | 1         | 0.44%   |
| Lenovo                   | 1         | 0.44%   |
| JMicron Technology       | 1         | 0.44%   |
| Huawei Technologies      | 1         | 0.44%   |
| DisplayLink              | 1         | 0.44%   |
| Broadcom Limited         | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 67        | 28.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 31        | 13.08%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 20        | 8.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 3.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 3.8%    |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 2.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 2.11%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 2.11%   |
| Intel Ethernet Controller I225-V                                       | 4         | 1.69%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.69%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 1.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 1.27%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 3         | 1.27%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.84%   |
| Realtek USB 10/100/1G/2.5 LAN                                          | 2         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.84%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.84%   |
| Intel 82599 10 Gigabit Network Connection                              | 2         | 0.84%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.84%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 2         | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.84%   |
| Apple iBridge                                                          | 2         | 0.84%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.42%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.42%   |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]       | 1         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.42%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.42%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 0.42%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.42%   |
| MediaTek Infinix HOT 50i                                               | 1         | 0.42%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.42%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 247       | 53.23%  |
| Ethernet | 208       | 44.83%  |
| Modem    | 9         | 1.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 192       | 71.91%  |
| Ethernet | 75        | 28.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 179       | 68.85%  |
| 1     | 68        | 26.15%  |
| 3     | 7         | 2.69%   |
| 0     | 5         | 1.92%   |
| 4     | 1         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 237       | 90.8%   |
| Yes  | 24        | 9.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 89        | 42.38%  |
| Realtek Semiconductor           | 30        | 14.29%  |
| Qualcomm Atheros Communications | 28        | 13.33%  |
| Foxconn / Hon Hai               | 11        | 5.24%   |
| Broadcom                        | 11        | 5.24%   |
| Apple                           | 11        | 5.24%   |
| Lite-On Technology              | 7         | 3.33%   |
| IMC Networks                    | 7         | 3.33%   |
| Toshiba                         | 5         | 2.38%   |
| Hewlett-Packard                 | 5         | 2.38%   |
| Dell                            | 2         | 0.95%   |
| Cambridge Silicon Radio         | 2         | 0.95%   |
| Realtek                         | 1         | 0.48%   |
| MediaTek                        | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 30        | 14.29%  |
| Qualcomm Atheros  Bluetooth Device                  | 20        | 9.52%   |
| Realtek Bluetooth Radio                             | 19        | 9.05%   |
| Intel AX201 Bluetooth                               | 16        | 7.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 6.67%   |
| Intel AX200 Bluetooth                               | 11        | 5.24%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 4.76%   |
| Intel Bluetooth Device                              | 7         | 3.33%   |
| Apple Bluetooth Host Controller                     | 7         | 3.33%   |
| Intel AX210 Bluetooth                               | 4         | 1.9%    |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 1.9%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 1.9%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 1.9%    |
| Toshiba Bluetooth Device                            | 3         | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.43%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.43%   |
| IMC Networks Wireless_Device                        | 3         | 1.43%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.43%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.43%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.43%   |
| Toshiba BCM43142A0                                  | 2         | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.95%   |
| Lite-On Wireless_Device                             | 2         | 0.95%   |
| Lite-On Bluetooth Device                            | 2         | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.95%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.95%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.95%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.48%   |
| Realtek Bluetooth Radio                             | 1         | 0.48%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.48%   |
| MediaTek Wireless_Device                            | 1         | 0.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.48%   |
| IMC Networks Bluetooth                              | 1         | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 212       | 65.43%  |
| AMD                      | 46        | 14.2%   |
| Nvidia                   | 30        | 9.26%   |
| Sony                     | 3         | 0.93%   |
| Realtek Semiconductor    | 3         | 0.93%   |
| GN Netcom                | 3         | 0.93%   |
| Generalplus Technology   | 3         | 0.93%   |
| Plantronics              | 2         | 0.62%   |
| Logitech                 | 2         | 0.62%   |
| Lenovo                   | 2         | 0.62%   |
| KTMicro                  | 2         | 0.62%   |
| JMTek                    | 2         | 0.62%   |
| Hewlett-Packard          | 2         | 0.62%   |
| C-Media Electronics      | 2         | 0.62%   |
| Apple                    | 2         | 0.62%   |
| Unknown                  | 1         | 0.31%   |
| Samsung Electronics      | 1         | 0.31%   |
| Micro Star International | 1         | 0.31%   |
| Kingston Technology      | 1         | 0.31%   |
| Focusrite-Novation       | 1         | 0.31%   |
| CMX Systems              | 1         | 0.31%   |
| ASUSTek Computer         | 1         | 0.31%   |
| Afatech                  | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 26        | 6.77%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 5.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 5.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 18        | 4.69%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 14        | 3.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 3.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 2.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 2.86%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.6%    |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.56%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.3%    |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 5         | 1.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.3%    |
| AMD FCH Azalia Controller                                                                         | 5         | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 1.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.04%   |
| Sony DualSense wireless controller (PS5)                                                          | 3         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.78%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 3         | 0.78%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 0.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.78%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.78%   |
| AMD Radeon High Definition Audio Controller                                                       | 3         | 0.78%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.78%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 33.71%  |
| SK hynix            | 30        | 16.85%  |
| Kingston            | 27        | 15.17%  |
| Micron Technology   | 15        | 8.43%   |
| Crucial             | 10        | 5.62%   |
| Unknown             | 6         | 3.37%   |
| Team                | 6         | 3.37%   |
| Nanya Technology    | 5         | 2.81%   |
| Corsair             | 4         | 2.25%   |
| A-DATA Technology   | 4         | 2.25%   |
| Ramaxel Technology  | 3         | 1.69%   |
| Unknown (ABCD)      | 2         | 1.12%   |
| Transcend           | 1         | 0.56%   |
| Super Talent        | 1         | 0.56%   |
| Patriot             | 1         | 0.56%   |
| Goldkey             | 1         | 0.56%   |
| G.Skill             | 1         | 0.56%   |
| fef5                | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s                | 8         | 4.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 2.53%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 4         | 2.02%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s              | 4         | 2.02%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 4         | 2.02%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                      | 4         | 2.02%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4         | 2.02%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 1.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.52%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 3         | 1.52%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 2         | 1.01%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1.01%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.01%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 1.01%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.01%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 1.01%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.01%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 2         | 1.01%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.01%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.01%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.01%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 1.01%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 2         | 1.01%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 1.01%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.01%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.01%   |
| Kingston RAM 9905744-106.A00G 32GB SODIMM DDR4 3200MT/s          | 2         | 1.01%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.51%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.51%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 1         | 0.51%   |
| Super Talent RAM SUPERTALENT02 4GB SODIMM DDR3 1600MT/s          | 1         | 0.51%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.51%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.51%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.51%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 77        | 51.68%  |
| DDR3    | 44        | 29.53%  |
| LPDDR5  | 7         | 4.7%    |
| LPDDR4  | 7         | 4.7%    |
| SDRAM   | 4         | 2.68%   |
| DDR2    | 4         | 2.68%   |
| DDR5    | 3         | 2.01%   |
| LPDDR3  | 2         | 1.34%   |
| Unknown | 1         | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 130       | 87.25%  |
| Row Of Chips | 17        | 11.41%  |
| Chip         | 1         | 0.67%   |
| Unknown      | 1         | 0.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 65        | 37.14%  |
| 4096  | 51        | 29.14%  |
| 16384 | 29        | 16.57%  |
| 32768 | 14        | 8%      |
| 2048  | 10        | 5.71%   |
| 3072  | 4         | 2.29%   |
| 1024  | 2         | 1.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 40        | 23.67%  |
| 3200    | 31        | 18.34%  |
| 1600    | 31        | 18.34%  |
| 2400    | 10        | 5.92%   |
| 1333    | 8         | 4.73%   |
| 6400    | 6         | 3.55%   |
| 2133    | 6         | 3.55%   |
| 1334    | 6         | 3.55%   |
| 8400    | 5         | 2.96%   |
| 3266    | 5         | 2.96%   |
| Unknown | 4         | 2.37%   |
| 4267    | 3         | 1.78%   |
| 667     | 3         | 1.78%   |
| 4800    | 2         | 1.18%   |
| 4199    | 2         | 1.18%   |
| 1067    | 2         | 1.18%   |
| 7500    | 1         | 0.59%   |
| 5600    | 1         | 0.59%   |
| 2933    | 1         | 0.59%   |
| 2048    | 1         | 0.59%   |
| 800     | 1         | 0.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson L380 Series       | 1         | 50%     |
| Seiko Epson EPSON L220 Series | 1         | 50%     |

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
| Chicony Electronics                    | 45        | 19.74%  |
| Microdia                               | 31        | 13.6%   |
| Realtek Semiconductor                  | 18        | 7.89%   |
| IMC Networks                           | 17        | 7.46%   |
| Sunplus Innovation Technology          | 15        | 6.58%   |
| Apple                                  | 13        | 5.7%    |
| Quanta                                 | 12        | 5.26%   |
| Bison Electronics                      | 11        | 4.82%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.95%   |
| Luxvisions Innotech Limited            | 8         | 3.51%   |
| Lite-On Technology                     | 8         | 3.51%   |
| Syntek                                 | 5         | 2.19%   |
| Primax Electronics                     | 4         | 1.75%   |
| HYGD-220831-A                          | 4         | 1.75%   |
| Alcor Micro                            | 4         | 1.75%   |
| Suyin                                  | 3         | 1.32%   |
| Silicon Motion                         | 3         | 1.32%   |
| Sonix Technology                       | 2         | 0.88%   |
| Microsoft                              | 2         | 0.88%   |
| Logitech                               | 2         | 0.88%   |
| ALi                                    | 2         | 0.88%   |
| Z-Star Microelectronics                | 1         | 0.44%   |
| SunplusIT                              | 1         | 0.44%   |
| Samsung Electronics                    | 1         | 0.44%   |
| LG Electronics                         | 1         | 0.44%   |
| Importek                               | 1         | 0.44%   |
| GEMBIRD                                | 1         | 0.44%   |
| Creative Technology                    | 1         | 0.44%   |
| BRS 2Mp Camera                         | 1         | 0.44%   |
| ARC International                      | 1         | 0.44%   |
| Alpha Imaging Technology               | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 24        | 10.34%  |
| Chicony Integrated Camera                           | 11        | 4.74%   |
| Apple FaceTime HD Camera                            | 8         | 3.45%   |
| IMC Networks Integrated Camera                      | 6         | 2.59%   |
| Sunplus HD WebCam                                   | 5         | 2.16%   |
| Realtek Integrated_Webcam_HD                        | 5         | 2.16%   |
| Chicony TOSHIBA Web Camera - HD                     | 5         | 2.16%   |
| Syntek Integrated Camera                            | 4         | 1.72%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.72%   |
| Realtek Integrated Webcam HD                        | 4         | 1.72%   |
| Luxvisions Innotech Limited Integrated Camera       | 4         | 1.72%   |
| HYGD-220831-A Hy-Usb2.0-1*MIC                       | 4         | 1.72%   |
| Chicony HP HD Camera                                | 4         | 1.72%   |
| Bison Integrated Camera                             | 4         | 1.72%   |
| Realtek Integrated Webcam                           | 3         | 1.29%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.29%   |
| Quanta HD Webcam                                    | 3         | 1.29%   |
| Quanta HD User Facing                               | 3         | 1.29%   |
| Primax HP HD Webcam [Fixed]                         | 3         | 1.29%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 1.29%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.29%   |
| Sunplus HP HD Webcam [Fixed]                        | 2         | 0.86%   |
| Sonix USB2.0 FHD UVC WebCam                         | 2         | 0.86%   |
| Microdia Integrated Webcam                          | 2         | 0.86%   |
| Lite-On TOSHIBA Web Camera - HD                     | 2         | 0.86%   |
| Lite-On Integrated Camera                           | 2         | 0.86%   |
| Lite-On HP HD Camera                                | 2         | 0.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 0.86%   |
| IMC Networks TOSHIBA Web Camera - HD                | 2         | 0.86%   |
| Chicony USB 2.0 Camera                              | 2         | 0.86%   |
| Chicony Integrated HP HD Webcam                     | 2         | 0.86%   |
| Chicony HP TrueVision HD Camera                     | 2         | 0.86%   |
| Chicony HP Truevision HD                            | 2         | 0.86%   |
| Chicony HP HD Webcam                                | 2         | 0.86%   |
| Chicony HD WebCam                                   | 2         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 0.86%   |
| Bison BisonCam,NB Pro                               | 2         | 0.86%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 0.86%   |
| ALi Gateway Webcam                                  | 2         | 0.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 38.3%   |
| Validity Sensors           | 17        | 36.17%  |
| Shenzhen Goodix Technology | 4         | 8.51%   |
| Elan Microelectronics      | 3         | 6.38%   |
| AuthenTec                  | 2         | 4.26%   |
| Upek                       | 1         | 2.13%   |
| STMicroelectronics         | 1         | 2.13%   |
| LighTuning Technology      | 1         | 2.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 8         | 17.02%  |
| Validity Sensors VFS495 Fingerprint Reader                | 4         | 8.51%   |
| Synaptics Fingerprint reader [HP G6]                      | 4         | 8.51%   |
| Shenzhen Goodix  FingerPrint Device                       | 4         | 8.51%   |
| Validity Sensors VFS491                                   | 3         | 6.38%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 3         | 6.38%   |
| Elan ELAN:ARM-M4                                          | 3         | 6.38%   |
| Validity Sensors VFS471 Fingerprint Reader                | 2         | 4.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 2         | 4.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 2.13%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 2.13%   |
| Validity Sensors Synaptics WBDI                           | 1         | 2.13%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 2.13%   |
| Validity Sensors Fingerprint scanner                      | 1         | 2.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 1         | 2.13%   |
| Synaptics WBDI                                            | 1         | 2.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.13%   |
| Synaptics Prometheus Fingerprint Reader                   | 1         | 2.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 2.13%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 2.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 1         | 2.13%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 1         | 2.13%   |
| AuthenTec AES1600                                         | 1         | 2.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 7         | 53.85%  |
| O2 Micro                   | 3         | 23.08%  |
| Athena Smartcard Solutions | 2         | 15.38%  |
| Alcor Micro                | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 38.46%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 15.38%  |
| Athena Smartcard Solutions ASEDrive V3C                                      | 2         | 15.38%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 1         | 7.69%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 175       | 65.06%  |
| 1     | 78        | 29%     |
| 2     | 12        | 4.46%   |
| 3     | 4         | 1.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 46        | 41.07%  |
| Graphics card            | 20        | 17.86%  |
| Net/wireless             | 18        | 16.07%  |
| Chipcard                 | 10        | 8.93%   |
| Multimedia controller    | 4         | 3.57%   |
| Communication controller | 4         | 3.57%   |
| Camera                   | 3         | 2.68%   |
| Firewire controller      | 2         | 1.79%   |
| Storage                  | 1         | 0.89%   |
| Sound                    | 1         | 0.89%   |
| Net/ethernet             | 1         | 0.89%   |
| Card reader              | 1         | 0.89%   |
| Bluetooth                | 1         | 0.89%   |

