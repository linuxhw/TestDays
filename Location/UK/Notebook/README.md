Linux in UK - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

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

Total: 6512

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3542               | [c7753ffa8e](https://linux-hardware.org/?probe=c7753ffa8e) | Feb 02, 2024 |
| Dell          | Inspiron 13-7359            | [82a1195ef5](https://linux-hardware.org/?probe=82a1195ef5) | Feb 02, 2024 |
| PC Special... | GK5CQ7Z                     | [d7632585fc](https://linux-hardware.org/?probe=d7632585fc) | Feb 02, 2024 |
| Apple         | MacBook5,1                  | [48a998308b](https://linux-hardware.org/?probe=48a998308b) | Feb 02, 2024 |
| Apple         | MacBookAir7,2               | [632421d681](https://linux-hardware.org/?probe=632421d681) | Feb 01, 2024 |
| Dell          | XPS 15 9560                 | [63fe6fecb5](https://linux-hardware.org/?probe=63fe6fecb5) | Feb 01, 2024 |
| HP            | Pavilion Notebook           | [397f03250d](https://linux-hardware.org/?probe=397f03250d) | Feb 01, 2024 |
| Acer          | Swift SF314-512             | [28bd75703e](https://linux-hardware.org/?probe=28bd75703e) | Feb 01, 2024 |
| Dell          | XPS 15 9560                 | [0b1c1e6784](https://linux-hardware.org/?probe=0b1c1e6784) | Feb 01, 2024 |
| TrekStor      | Primebook P14               | [ffd6c873de](https://linux-hardware.org/?probe=ffd6c873de) | Feb 01, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [172f182e36](https://linux-hardware.org/?probe=172f182e36) | Feb 01, 2024 |
| HP            | Pavilion dv6                | [9d58677c2a](https://linux-hardware.org/?probe=9d58677c2a) | Feb 01, 2024 |
| Lenovo        | Flex 2-14 20404             | [b2d8a38af3](https://linux-hardware.org/?probe=b2d8a38af3) | Feb 01, 2024 |
| HP            | 15                          | [5abc868cce](https://linux-hardware.org/?probe=5abc868cce) | Jan 31, 2024 |
| Apple         | MacBookPro5,1               | [85b45c9a2f](https://linux-hardware.org/?probe=85b45c9a2f) | Jan 31, 2024 |
| Apple         | MacBook5,1                  | [e12d7e5691](https://linux-hardware.org/?probe=e12d7e5691) | Jan 31, 2024 |
| Apple         | MacBook5,1                  | [68076b1cbd](https://linux-hardware.org/?probe=68076b1cbd) | Jan 31, 2024 |
| Lenovo        | V330-14ARR 81B1             | [5dcee96cdb](https://linux-hardware.org/?probe=5dcee96cdb) | Jan 31, 2024 |
| Dell          | Latitude E6430s             | [6eacf03c08](https://linux-hardware.org/?probe=6eacf03c08) | Jan 31, 2024 |
| Acer          | Swift SF314-42              | [32d0112bcd](https://linux-hardware.org/?probe=32d0112bcd) | Jan 30, 2024 |
| HP            | Pavilion dv6                | [e1e2c04f8c](https://linux-hardware.org/?probe=e1e2c04f8c) | Jan 30, 2024 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [809fd2e9fa](https://linux-hardware.org/?probe=809fd2e9fa) | Jan 30, 2024 |
| Valve         | Jupiter                     | [0db5dcce8b](https://linux-hardware.org/?probe=0db5dcce8b) | Jan 30, 2024 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [b51ecf60ef](https://linux-hardware.org/?probe=b51ecf60ef) | Jan 30, 2024 |
| Lenovo        | Yoga S730-13IWL 81J0        | [87e2c70726](https://linux-hardware.org/?probe=87e2c70726) | Jan 30, 2024 |
| Acer          | Aspire E1-571               | [daf8c42eca](https://linux-hardware.org/?probe=daf8c42eca) | Jan 30, 2024 |
| Lenovo        | ThinkPad T510 43149TG       | [463b653f7a](https://linux-hardware.org/?probe=463b653f7a) | Jan 30, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H5C... | [7f42dbc84d](https://linux-hardware.org/?probe=7f42dbc84d) | Jan 30, 2024 |
| AWOW          | AK41                        | [4e8816ed0c](https://linux-hardware.org/?probe=4e8816ed0c) | Jan 30, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H5C... | [62bda5bd27](https://linux-hardware.org/?probe=62bda5bd27) | Jan 30, 2024 |
| HP            | Pavilion dv6                | [654b331eac](https://linux-hardware.org/?probe=654b331eac) | Jan 30, 2024 |
| HP            | Pavilion dv6                | [69c00fe459](https://linux-hardware.org/?probe=69c00fe459) | Jan 30, 2024 |
| Dell          | Latitude 7390               | [defc75091c](https://linux-hardware.org/?probe=defc75091c) | Jan 30, 2024 |
| Dell          | Inspiron 1525               | [ad26dae776](https://linux-hardware.org/?probe=ad26dae776) | Jan 30, 2024 |
| Dell          | Inspiron 1525               | [bc4394a85f](https://linux-hardware.org/?probe=bc4394a85f) | Jan 30, 2024 |
| Sony          | SVF1521Q1EW                 | [94c0695977](https://linux-hardware.org/?probe=94c0695977) | Jan 30, 2024 |
| CyberPower... | Tracer II                   | [ca21b317a2](https://linux-hardware.org/?probe=ca21b317a2) | Jan 29, 2024 |
| Apple         | MacBookPro9,2               | [6309dc5c20](https://linux-hardware.org/?probe=6309dc5c20) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [510f28a7d3](https://linux-hardware.org/?probe=510f28a7d3) | Jan 29, 2024 |
| HP            | Laptop 15s-fq5xxx           | [4ab253480b](https://linux-hardware.org/?probe=4ab253480b) | Jan 29, 2024 |
| Lenovo        | IdeaPad S510p 20298         | [7c9fb93a37](https://linux-hardware.org/?probe=7c9fb93a37) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [aa19c735f2](https://linux-hardware.org/?probe=aa19c735f2) | Jan 28, 2024 |
| Dell          | XPS L421X                   | [7eab16ad73](https://linux-hardware.org/?probe=7eab16ad73) | Jan 27, 2024 |
| Apple         | MacBookPro14,1              | [75f6092ef1](https://linux-hardware.org/?probe=75f6092ef1) | Jan 27, 2024 |
| LG Electro... | 17Z90P-K.AA78A1             | [7280098d0c](https://linux-hardware.org/?probe=7280098d0c) | Jan 27, 2024 |
| ASUSTek       | X551CA                      | [2147b3f8f3](https://linux-hardware.org/?probe=2147b3f8f3) | Jan 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2d82723a5a](https://linux-hardware.org/?probe=2d82723a5a) | Jan 27, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | [8c4e929f6f](https://linux-hardware.org/?probe=8c4e929f6f) | Jan 27, 2024 |
| Dell          | Latitude E6430              | [237d6e4d3e](https://linux-hardware.org/?probe=237d6e4d3e) | Jan 27, 2024 |
| Dell          | XPS 13 9350                 | [fb1c7c4cab](https://linux-hardware.org/?probe=fb1c7c4cab) | Jan 26, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | [43bf0c55e8](https://linux-hardware.org/?probe=43bf0c55e8) | Jan 26, 2024 |
| Valve         | Jupiter                     | [b69df41d1b](https://linux-hardware.org/?probe=b69df41d1b) | Jan 26, 2024 |
| HP            | ProBook 455 G2              | [f8d011e007](https://linux-hardware.org/?probe=f8d011e007) | Jan 25, 2024 |
| Acer          | Swift SFG14-72              | [a9239eecc8](https://linux-hardware.org/?probe=a9239eecc8) | Jan 25, 2024 |
| Acer          | Swift SF314-57              | [352b6edd13](https://linux-hardware.org/?probe=352b6edd13) | Jan 25, 2024 |
| Acer          | Aspire A315-24P             | [24a5e0a03c](https://linux-hardware.org/?probe=24a5e0a03c) | Jan 25, 2024 |
| Lenovo        | ThinkPad X250 20CM004XUK    | [a1e8059fd3](https://linux-hardware.org/?probe=a1e8059fd3) | Jan 25, 2024 |
| Lenovo        | ThinkPad T60p 20078JU       | [6c83cf1141](https://linux-hardware.org/?probe=6c83cf1141) | Jan 25, 2024 |
| Apple         | MacBook10,1                 | [da3e59958f](https://linux-hardware.org/?probe=da3e59958f) | Jan 24, 2024 |
| Dell          | Latitude 7390               | [ba979ded0e](https://linux-hardware.org/?probe=ba979ded0e) | Jan 24, 2024 |
| AZW           | GT-R                        | [b9cc91d07d](https://linux-hardware.org/?probe=b9cc91d07d) | Jan 24, 2024 |
| Apple         | MacBookAir6,2               | [6eb8876e79](https://linux-hardware.org/?probe=6eb8876e79) | Jan 24, 2024 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [9e41ae4dc7](https://linux-hardware.org/?probe=9e41ae4dc7) | Jan 23, 2024 |
| HP            | ProBook 455 G1              | [224d863e1d](https://linux-hardware.org/?probe=224d863e1d) | Jan 23, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [a756dd32a8](https://linux-hardware.org/?probe=a756dd32a8) | Jan 23, 2024 |
| Valve         | Jupiter                     | [d2a4f1790a](https://linux-hardware.org/?probe=d2a4f1790a) | Jan 22, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [2f77e5be01](https://linux-hardware.org/?probe=2f77e5be01) | Jan 22, 2024 |
| Apple         | MacBookPro9,2               | [a4c212bc8e](https://linux-hardware.org/?probe=a4c212bc8e) | Jan 22, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [19eaa1abc0](https://linux-hardware.org/?probe=19eaa1abc0) | Jan 22, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [a19e1e70ac](https://linux-hardware.org/?probe=a19e1e70ac) | Jan 22, 2024 |
| Lenovo        | ThinkPad X250 20CLS3320C    | [5525303ee4](https://linux-hardware.org/?probe=5525303ee4) | Jan 22, 2024 |
| Acer          | Swift SF314-511             | [c4578284c8](https://linux-hardware.org/?probe=c4578284c8) | Jan 22, 2024 |
| Lenovo        | V15-ADA 82C7                | [a8893e7742](https://linux-hardware.org/?probe=a8893e7742) | Jan 22, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | [8621eed350](https://linux-hardware.org/?probe=8621eed350) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | [af0244605f](https://linux-hardware.org/?probe=af0244605f) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | [024b0a26f9](https://linux-hardware.org/?probe=024b0a26f9) | Jan 21, 2024 |
| Lenovo        | ThinkPad X201 3323DAG       | [27542f7432](https://linux-hardware.org/?probe=27542f7432) | Jan 21, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | [bec3659c29](https://linux-hardware.org/?probe=bec3659c29) | Jan 21, 2024 |
| HP            | Notebook                    | [2dcfaac5fd](https://linux-hardware.org/?probe=2dcfaac5fd) | Jan 21, 2024 |
| Lenovo        | ThinkPad T400 6474W7T       | [fa80320d7c](https://linux-hardware.org/?probe=fa80320d7c) | Jan 21, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [aaf1d1d0de](https://linux-hardware.org/?probe=aaf1d1d0de) | Jan 21, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [af044c261f](https://linux-hardware.org/?probe=af044c261f) | Jan 20, 2024 |
| HP            | Laptop 14s-fq1xxx           | [5df2f7a287](https://linux-hardware.org/?probe=5df2f7a287) | Jan 20, 2024 |
| Panasonic     | CF-52PFN32PE                | [8399ba74d7](https://linux-hardware.org/?probe=8399ba74d7) | Jan 20, 2024 |
| Acer          | Swift SFG14-72              | [e37657c021](https://linux-hardware.org/?probe=e37657c021) | Jan 19, 2024 |
| HP            | ProBook 450 G1              | [09fe6e6426](https://linux-hardware.org/?probe=09fe6e6426) | Jan 19, 2024 |
| HP            | OMEN by Laptop 17-an0xx     | [4ac008d4c9](https://linux-hardware.org/?probe=4ac008d4c9) | Jan 19, 2024 |
| ASUSTek       | N55SL                       | [a6c913a5e2](https://linux-hardware.org/?probe=a6c913a5e2) | Jan 19, 2024 |
| Toshiba       | Satellite Pro R50-B         | [9b78c4adba](https://linux-hardware.org/?probe=9b78c4adba) | Jan 19, 2024 |
| Toshiba       | Satellite Pro R50-B         | [408beb089a](https://linux-hardware.org/?probe=408beb089a) | Jan 19, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e4d77bb448](https://linux-hardware.org/?probe=e4d77bb448) | Jan 19, 2024 |
| GPD           | P2 MAX                      | [ec59cadd15](https://linux-hardware.org/?probe=ec59cadd15) | Jan 19, 2024 |
| Dynabook      | Satellite Pro L50-G-193     | [516bbcf7a3](https://linux-hardware.org/?probe=516bbcf7a3) | Jan 18, 2024 |
| Dell          | XPS 9320                    | [eb5df7ed6d](https://linux-hardware.org/?probe=eb5df7ed6d) | Jan 18, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [1a9602bf0b](https://linux-hardware.org/?probe=1a9602bf0b) | Jan 17, 2024 |
| HP            | ZBook 14u G6                | [668a33bda1](https://linux-hardware.org/?probe=668a33bda1) | Jan 17, 2024 |
| ASUSTek       | X541UAK                     | [bd74ab2cc7](https://linux-hardware.org/?probe=bd74ab2cc7) | Jan 17, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | [1364b82d7c](https://linux-hardware.org/?probe=1364b82d7c) | Jan 17, 2024 |
| Lenovo        | Yoga S740-14IIL 81RS        | [a3813e2aa2](https://linux-hardware.org/?probe=a3813e2aa2) | Jan 16, 2024 |
| Apple         | MacBookPro15,2              | [547ddaf81d](https://linux-hardware.org/?probe=547ddaf81d) | Jan 16, 2024 |
| Dell          | XPS 15 9530                 | [61ade3f6d3](https://linux-hardware.org/?probe=61ade3f6d3) | Jan 15, 2024 |
| Valve         | Galileo                     | [c9db96cd08](https://linux-hardware.org/?probe=c9db96cd08) | Jan 15, 2024 |
| Valve         | Jupiter                     | [ff4dff4d2f](https://linux-hardware.org/?probe=ff4dff4d2f) | Jan 15, 2024 |
| HP            | Pavilion Notebook           | [94858d9522](https://linux-hardware.org/?probe=94858d9522) | Jan 15, 2024 |
| Dell          | Latitude E5470              | [d9fcb7e121](https://linux-hardware.org/?probe=d9fcb7e121) | Jan 15, 2024 |
| ASUSTek       | N56VB                       | [3542693793](https://linux-hardware.org/?probe=3542693793) | Jan 15, 2024 |
| Valve         | Galileo                     | [5d92a542e4](https://linux-hardware.org/?probe=5d92a542e4) | Jan 14, 2024 |
| PC Special... | P65_67RSRP                  | [f2af84bdfc](https://linux-hardware.org/?probe=f2af84bdfc) | Jan 13, 2024 |
| Lenovo        | ThinkPad X260 20F5S4A901    | [75e671c163](https://linux-hardware.org/?probe=75e671c163) | Jan 12, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [3be44d9c7c](https://linux-hardware.org/?probe=3be44d9c7c) | Jan 12, 2024 |
| Lenovo        | ThinkPad L570 20J9S0KG00    | [6d03ee96b8](https://linux-hardware.org/?probe=6d03ee96b8) | Jan 12, 2024 |
| Dell          | Latitude E6400              | [2059e9e8d0](https://linux-hardware.org/?probe=2059e9e8d0) | Jan 12, 2024 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [4d02212cbc](https://linux-hardware.org/?probe=4d02212cbc) | Jan 11, 2024 |
| Razer         | Blade Stealth               | [a8c542db2c](https://linux-hardware.org/?probe=a8c542db2c) | Jan 11, 2024 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [5e75e6b11a](https://linux-hardware.org/?probe=5e75e6b11a) | Jan 10, 2024 |
| ASUSTek       | N55SL                       | [b2c935edc3](https://linux-hardware.org/?probe=b2c935edc3) | Jan 10, 2024 |
| Dell          | Latitude E5470              | [a2211d635f](https://linux-hardware.org/?probe=a2211d635f) | Jan 10, 2024 |
| Dell          | XPS 9320                    | [86cf8ad410](https://linux-hardware.org/?probe=86cf8ad410) | Jan 10, 2024 |
| ASUSTek       | X200CA                      | [c27c1b9fc2](https://linux-hardware.org/?probe=c27c1b9fc2) | Jan 10, 2024 |
| MSI           | GS66 Stealth 10SE           | [4af36bad9f](https://linux-hardware.org/?probe=4af36bad9f) | Jan 09, 2024 |
| HP            | EliteBook 8470p             | [8a0e17b484](https://linux-hardware.org/?probe=8a0e17b484) | Jan 09, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [0bc6f72a01](https://linux-hardware.org/?probe=0bc6f72a01) | Jan 09, 2024 |
| Acer          | Aspire A515-44              | [2cb18af412](https://linux-hardware.org/?probe=2cb18af412) | Jan 09, 2024 |
| Razer         | Blade 15 Base Model (Ear... | [a7c594cca5](https://linux-hardware.org/?probe=a7c594cca5) | Jan 08, 2024 |
| HONOR         | BBR-WAX9                    | [b9d1ee2b4c](https://linux-hardware.org/?probe=b9d1ee2b4c) | Jan 08, 2024 |
| LG Electro... | 15Z90RT-K.AD7AA1            | [be4ff0f44a](https://linux-hardware.org/?probe=be4ff0f44a) | Jan 08, 2024 |
| Lenovo        | Yoga 3 14 80JH              | [960bf85acd](https://linux-hardware.org/?probe=960bf85acd) | Jan 08, 2024 |
| HUAWEI        | WRT-WX9                     | [5b9a494436](https://linux-hardware.org/?probe=5b9a494436) | Jan 08, 2024 |
| Acer          | Nitro AN517-52              | [1f601b8cb0](https://linux-hardware.org/?probe=1f601b8cb0) | Jan 08, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | [8ba032e1a2](https://linux-hardware.org/?probe=8ba032e1a2) | Jan 08, 2024 |
| Lenovo        | ThinkPad X220 4291RD2       | [dc1b40ea6f](https://linux-hardware.org/?probe=dc1b40ea6f) | Jan 08, 2024 |
| AWOW          | AK41                        | [62d6e6b631](https://linux-hardware.org/?probe=62d6e6b631) | Jan 08, 2024 |
| Dell          | Latitude 7280               | [de1f6a94e6](https://linux-hardware.org/?probe=de1f6a94e6) | Jan 08, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [fd3f275cfb](https://linux-hardware.org/?probe=fd3f275cfb) | Jan 07, 2024 |
| ENTITY        | ENTYG11Q1                   | [b2ca051044](https://linux-hardware.org/?probe=b2ca051044) | Jan 07, 2024 |
| ENTITY        | ENTYG11Q1                   | [f9b0c03994](https://linux-hardware.org/?probe=f9b0c03994) | Jan 07, 2024 |
| Star Labs     | StarLite                    | [751432d737](https://linux-hardware.org/?probe=751432d737) | Jan 07, 2024 |
| HP            | 255 G1                      | [c7391eb57a](https://linux-hardware.org/?probe=c7391eb57a) | Jan 07, 2024 |
| HP            | 255 G1                      | [0b734c978f](https://linux-hardware.org/?probe=0b734c978f) | Jan 06, 2024 |
| Acer          | Aspire A315-21              | [14528ba1f9](https://linux-hardware.org/?probe=14528ba1f9) | Jan 06, 2024 |
| Acer          | Aspire A315-21              | [60f51d8b49](https://linux-hardware.org/?probe=60f51d8b49) | Jan 06, 2024 |
| ASUSTek       | X551CA                      | [78faa77bac](https://linux-hardware.org/?probe=78faa77bac) | Jan 06, 2024 |
| AZW           | Speed S                     | [a16b812e0d](https://linux-hardware.org/?probe=a16b812e0d) | Jan 06, 2024 |
| Lenovo        | ThinkPad T480 20L50000UK    | [8a19e590f8](https://linux-hardware.org/?probe=8a19e590f8) | Jan 05, 2024 |
| Toshiba       | Satellite L50D-B            | [7a713e9106](https://linux-hardware.org/?probe=7a713e9106) | Jan 05, 2024 |
| HP            | ENVY Notebook               | [8a2c65e297](https://linux-hardware.org/?probe=8a2c65e297) | Jan 05, 2024 |
| Lenovo        | V15 G2 ALC 82KD             | [e5a4807041](https://linux-hardware.org/?probe=e5a4807041) | Jan 05, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [f7ad5f683a](https://linux-hardware.org/?probe=f7ad5f683a) | Jan 04, 2024 |
| HP            | Mini 210-1000               | [ddd4183f45](https://linux-hardware.org/?probe=ddd4183f45) | Jan 04, 2024 |
| HP            | Mini 210-1000               | [65f80ec87f](https://linux-hardware.org/?probe=65f80ec87f) | Jan 04, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a7dd37b5a2](https://linux-hardware.org/?probe=a7dd37b5a2) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [c23d61cde7](https://linux-hardware.org/?probe=c23d61cde7) | Jan 04, 2024 |
| Valve         | Jupiter                     | [348b004789](https://linux-hardware.org/?probe=348b004789) | Jan 04, 2024 |
| ASUSTek       | E201NA                      | [91cac0307a](https://linux-hardware.org/?probe=91cac0307a) | Jan 04, 2024 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [934cb11b0b](https://linux-hardware.org/?probe=934cb11b0b) | Jan 03, 2024 |
| Lenovo        | Z50-75 80EC                 | [0e5397d3f1](https://linux-hardware.org/?probe=0e5397d3f1) | Jan 03, 2024 |
| Dell          | Precision 5510              | [762ef434f5](https://linux-hardware.org/?probe=762ef434f5) | Jan 03, 2024 |
| Star Labs     | StarLite                    | [9f0fae17e5](https://linux-hardware.org/?probe=9f0fae17e5) | Jan 02, 2024 |
| Dell          | Precision M3800             | [5867b0c6eb](https://linux-hardware.org/?probe=5867b0c6eb) | Jan 02, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1V60... | [ca5f55438f](https://linux-hardware.org/?probe=ca5f55438f) | Jan 02, 2024 |
| Dell          | Inspiron 15 3530            | [ee21ee0e37](https://linux-hardware.org/?probe=ee21ee0e37) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d4335b1132](https://linux-hardware.org/?probe=d4335b1132) | Jan 01, 2024 |
| HP            | Laptop 15s-eq2xxx           | [2f1b4ada4b](https://linux-hardware.org/?probe=2f1b4ada4b) | Jan 01, 2024 |
| Lenovo        | Y50-70 20378                | [ff5e2959f8](https://linux-hardware.org/?probe=ff5e2959f8) | Dec 31, 2023 |
| Notebook      | NL5xNU                      | [915031852a](https://linux-hardware.org/?probe=915031852a) | Dec 31, 2023 |
| Acer          | Aspire 8943G                | [a75a2524f2](https://linux-hardware.org/?probe=a75a2524f2) | Dec 31, 2023 |
| Valve         | Jupiter                     | [2f8ea60a38](https://linux-hardware.org/?probe=2f8ea60a38) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [60da2c756f](https://linux-hardware.org/?probe=60da2c756f) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f805c2c9fc](https://linux-hardware.org/?probe=f805c2c9fc) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0fa90555a](https://linux-hardware.org/?probe=e0fa90555a) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [9e856c326a](https://linux-hardware.org/?probe=9e856c326a) | Dec 29, 2023 |
| Acer          | Aspire F5-571               | [d28fac242c](https://linux-hardware.org/?probe=d28fac242c) | Dec 29, 2023 |
| HP            | EliteBook 2570p             | [935d08358c](https://linux-hardware.org/?probe=935d08358c) | Dec 29, 2023 |
| HP            | ZBook 14u G6                | [409e402108](https://linux-hardware.org/?probe=409e402108) | Dec 28, 2023 |
| Google        | Nami                        | [3d7f7ba09c](https://linux-hardware.org/?probe=3d7f7ba09c) | Dec 28, 2023 |
| HP            | ProBook 455 G1              | [d132700b11](https://linux-hardware.org/?probe=d132700b11) | Dec 28, 2023 |
| AWOW          | AK41                        | [d081509ed9](https://linux-hardware.org/?probe=d081509ed9) | Dec 28, 2023 |
| MSI           | Pulse GL66 12UEK            | [4600a758fa](https://linux-hardware.org/?probe=4600a758fa) | Dec 27, 2023 |
| Acer          | Aspire E1-570               | [403dd9f171](https://linux-hardware.org/?probe=403dd9f171) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G614JZ_G614JZ     | [3ec4d2a40d](https://linux-hardware.org/?probe=3ec4d2a40d) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G614JZ_G614JZ     | [eb40e7ad5c](https://linux-hardware.org/?probe=eb40e7ad5c) | Dec 27, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [f745deb3d7](https://linux-hardware.org/?probe=f745deb3d7) | Dec 27, 2023 |
| Dell          | Latitude 7390               | [32c3fcc941](https://linux-hardware.org/?probe=32c3fcc941) | Dec 27, 2023 |
| Dell          | XPS 15 9570                 | [25466d5d3b](https://linux-hardware.org/?probe=25466d5d3b) | Dec 27, 2023 |
| Acer          | TravelMate P256-M           | [c4f9e9de5e](https://linux-hardware.org/?probe=c4f9e9de5e) | Dec 27, 2023 |
| Acer          | TravelMate P256-M           | [c129debcae](https://linux-hardware.org/?probe=c129debcae) | Dec 27, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | [b602153aeb](https://linux-hardware.org/?probe=b602153aeb) | Dec 26, 2023 |
| Notebook      | NL5xNU                      | [ad5a093909](https://linux-hardware.org/?probe=ad5a093909) | Dec 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | [5a76629311](https://linux-hardware.org/?probe=5a76629311) | Dec 26, 2023 |
| Acer          | Aspire A314-22              | [83c0e37ece](https://linux-hardware.org/?probe=83c0e37ece) | Dec 25, 2023 |
| Valve         | Jupiter                     | [4ab75ea56b](https://linux-hardware.org/?probe=4ab75ea56b) | Dec 25, 2023 |
| PC Special... | 14 Fusion Pro               | [76bf311c34](https://linux-hardware.org/?probe=76bf311c34) | Dec 25, 2023 |
| HP            | 255 G8 Notebook PC          | [1f14807c5e](https://linux-hardware.org/?probe=1f14807c5e) | Dec 25, 2023 |
| Valve         | Jupiter                     | [6ec124a0c4](https://linux-hardware.org/?probe=6ec124a0c4) | Dec 24, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | [eb3b2bf56b](https://linux-hardware.org/?probe=eb3b2bf56b) | Dec 24, 2023 |
| Valve         | Jupiter                     | [f57d2e51fe](https://linux-hardware.org/?probe=f57d2e51fe) | Dec 24, 2023 |
| Dell          | Latitude 5300               | [68336d8bc1](https://linux-hardware.org/?probe=68336d8bc1) | Dec 24, 2023 |
| Dell          | Latitude 12 Rugged Table... | [7690d56522](https://linux-hardware.org/?probe=7690d56522) | Dec 24, 2023 |
| Dell          | Inspiron 15 3530            | [0688896e27](https://linux-hardware.org/?probe=0688896e27) | Dec 23, 2023 |
| Dell          | Latitude E6420              | [82c13c188b](https://linux-hardware.org/?probe=82c13c188b) | Dec 23, 2023 |
| Dell          | Inspiron 5577               | [e6827a291e](https://linux-hardware.org/?probe=e6827a291e) | Dec 22, 2023 |
| Dell          | Latitude 7300               | [8792895835](https://linux-hardware.org/?probe=8792895835) | Dec 22, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | [38a9810e94](https://linux-hardware.org/?probe=38a9810e94) | Dec 22, 2023 |
| Dell          | Latitude E5510              | [92074a5231](https://linux-hardware.org/?probe=92074a5231) | Dec 22, 2023 |
| Valve         | Jupiter                     | [03491495da](https://linux-hardware.org/?probe=03491495da) | Dec 22, 2023 |
| HP            | EliteBook 830 G5            | [aa3d919a29](https://linux-hardware.org/?probe=aa3d919a29) | Dec 22, 2023 |
| ASUSTek       | E201NA                      | [ee5e05ce6d](https://linux-hardware.org/?probe=ee5e05ce6d) | Dec 21, 2023 |
| Lenovo        | ThinkPad X280 20KEA00SUK    | [bc380b4334](https://linux-hardware.org/?probe=bc380b4334) | Dec 21, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [088b5d3bba](https://linux-hardware.org/?probe=088b5d3bba) | Dec 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eef5dcab57](https://linux-hardware.org/?probe=eef5dcab57) | Dec 20, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [4f6ecdc95a](https://linux-hardware.org/?probe=4f6ecdc95a) | Dec 19, 2023 |
| Dell          | Latitude 5340               | [c9d3b3d7a7](https://linux-hardware.org/?probe=c9d3b3d7a7) | Dec 19, 2023 |
| HP            | Notebook                    | [31d6fc4280](https://linux-hardware.org/?probe=31d6fc4280) | Dec 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWA16R0... | [4f1e1945a7](https://linux-hardware.org/?probe=4f1e1945a7) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [91b5e05490](https://linux-hardware.org/?probe=91b5e05490) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [fde7aeea9c](https://linux-hardware.org/?probe=fde7aeea9c) | Dec 19, 2023 |
| Dell          | Inspiron 15 3535            | [f86bf3e2f1](https://linux-hardware.org/?probe=f86bf3e2f1) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [8596edc762](https://linux-hardware.org/?probe=8596edc762) | Dec 18, 2023 |
| Valve         | Jupiter                     | [f8d7e441a5](https://linux-hardware.org/?probe=f8d7e441a5) | Dec 18, 2023 |
| HP            | Pavilion Notebook           | [0376612ef7](https://linux-hardware.org/?probe=0376612ef7) | Dec 18, 2023 |
| Lenovo        | ThinkPad T420 4180PR1       | [2c0267b77e](https://linux-hardware.org/?probe=2c0267b77e) | Dec 17, 2023 |
| Dell          | Latitude E6400              | [855a8f55c4](https://linux-hardware.org/?probe=855a8f55c4) | Dec 17, 2023 |
| Toshiba       | Satellite L300              | [6528f813b7](https://linux-hardware.org/?probe=6528f813b7) | Dec 17, 2023 |
| HP            | ZBook 14u G6                | [125dbde28d](https://linux-hardware.org/?probe=125dbde28d) | Dec 17, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [209df55714](https://linux-hardware.org/?probe=209df55714) | Dec 17, 2023 |
| Valve         | Jupiter                     | [d6c8debc47](https://linux-hardware.org/?probe=d6c8debc47) | Dec 16, 2023 |
| HP            | EliteBook 8460p             | [9105f33be2](https://linux-hardware.org/?probe=9105f33be2) | Dec 16, 2023 |
| Acer          | Aspire 6930G                | [3e93a62792](https://linux-hardware.org/?probe=3e93a62792) | Dec 16, 2023 |
| AZW           | GT-R                        | [205436106b](https://linux-hardware.org/?probe=205436106b) | Dec 16, 2023 |
| Dell          | Inspiron 13-5378            | [d63cdec5eb](https://linux-hardware.org/?probe=d63cdec5eb) | Dec 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [921d38d2df](https://linux-hardware.org/?probe=921d38d2df) | Dec 15, 2023 |
| Dell          | XPS 15 9570                 | [67a32f0dd0](https://linux-hardware.org/?probe=67a32f0dd0) | Dec 14, 2023 |
| Dell          | XPS 15 9570                 | [283dc2dab5](https://linux-hardware.org/?probe=283dc2dab5) | Dec 14, 2023 |
| Schenker      | XMG NEO (E23)               | [ce84d5a464](https://linux-hardware.org/?probe=ce84d5a464) | Dec 13, 2023 |
| Dell          | XPS 15 9530                 | [33d1f683ba](https://linux-hardware.org/?probe=33d1f683ba) | Dec 13, 2023 |
| Acer          | TMP645-M                    | [55c3db256a](https://linux-hardware.org/?probe=55c3db256a) | Dec 13, 2023 |
| Valve         | Galileo                     | [835c844aed](https://linux-hardware.org/?probe=835c844aed) | Dec 13, 2023 |
| Dell          | Inspiron 16 Plus 7630       | [25017a9de6](https://linux-hardware.org/?probe=25017a9de6) | Dec 13, 2023 |
| HP            | Pavilion g6                 | [920939b6c0](https://linux-hardware.org/?probe=920939b6c0) | Dec 13, 2023 |
| MSI           | MS-16Y1                     | [41ce29bec7](https://linux-hardware.org/?probe=41ce29bec7) | Dec 12, 2023 |
| GEO           | GEOBOOK 2E                  | [86b33e33ca](https://linux-hardware.org/?probe=86b33e33ca) | Dec 12, 2023 |
| GEO           | GEOBOOK 2E                  | [cac69d7624](https://linux-hardware.org/?probe=cac69d7624) | Dec 12, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [46b5f7ee7b](https://linux-hardware.org/?probe=46b5f7ee7b) | Dec 12, 2023 |
| Samsung       | R720                        | [a434163017](https://linux-hardware.org/?probe=a434163017) | Dec 12, 2023 |
| Apple         | MacBookPro14,1              | [16e9faf4e6](https://linux-hardware.org/?probe=16e9faf4e6) | Dec 12, 2023 |
| Apple         | MacBookPro14,1              | [05ceb8703b](https://linux-hardware.org/?probe=05ceb8703b) | Dec 12, 2023 |
| Samsung       | R720                        | [b7a2f3044e](https://linux-hardware.org/?probe=b7a2f3044e) | Dec 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [f49dd0f010](https://linux-hardware.org/?probe=f49dd0f010) | Dec 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [31b92c3112](https://linux-hardware.org/?probe=31b92c3112) | Dec 11, 2023 |
| Dell          | Inspiron 13-5378            | [3d89daa3fa](https://linux-hardware.org/?probe=3d89daa3fa) | Dec 11, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [f604df3e48](https://linux-hardware.org/?probe=f604df3e48) | Dec 10, 2023 |
| Acer          | Aspire 6930G                | [eea9d9e525](https://linux-hardware.org/?probe=eea9d9e525) | Dec 10, 2023 |
| Dell          | XPS 15 9570                 | [35a10a1ae2](https://linux-hardware.org/?probe=35a10a1ae2) | Dec 10, 2023 |
| Sony          | SVE1511K1EW                 | [34875b90c4](https://linux-hardware.org/?probe=34875b90c4) | Dec 10, 2023 |
| MSI           | GS43VR 7RE                  | [23feee91ff](https://linux-hardware.org/?probe=23feee91ff) | Dec 10, 2023 |
| Dell          | G5 5590                     | [6970987854](https://linux-hardware.org/?probe=6970987854) | Dec 08, 2023 |
| Dell          | Inspiron 7400               | [0fb56c3b77](https://linux-hardware.org/?probe=0fb56c3b77) | Dec 08, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [3ca33a4b88](https://linux-hardware.org/?probe=3ca33a4b88) | Dec 08, 2023 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [767b4efa54](https://linux-hardware.org/?probe=767b4efa54) | Dec 06, 2023 |
| Tactus        | IOTA Flo                    | [a79fecbfad](https://linux-hardware.org/?probe=a79fecbfad) | Dec 06, 2023 |
| Acer          | Aspire A314-22              | [ce624b95df](https://linux-hardware.org/?probe=ce624b95df) | Dec 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [ad7bb46855](https://linux-hardware.org/?probe=ad7bb46855) | Dec 05, 2023 |
| HP            | ProBook 4540s               | [53eab461fb](https://linux-hardware.org/?probe=53eab461fb) | Dec 05, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [dfc33bff7a](https://linux-hardware.org/?probe=dfc33bff7a) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [fd95385327](https://linux-hardware.org/?probe=fd95385327) | Dec 04, 2023 |
| Dell          | Latitude 5290 2-in-1        | [525166f0d5](https://linux-hardware.org/?probe=525166f0d5) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [54ecb0a8b8](https://linux-hardware.org/?probe=54ecb0a8b8) | Dec 04, 2023 |
| Dell          | XPS 13 9360                 | [73fa5936a1](https://linux-hardware.org/?probe=73fa5936a1) | Dec 04, 2023 |
| HP            | EliteBook 840 G6            | [dc816e1423](https://linux-hardware.org/?probe=dc816e1423) | Dec 04, 2023 |
| Valve         | Jupiter                     | [0caac1007d](https://linux-hardware.org/?probe=0caac1007d) | Dec 04, 2023 |
| ASUSTek       | N552VW                      | [c2e09d65d5](https://linux-hardware.org/?probe=c2e09d65d5) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [7b5f2ca2f9](https://linux-hardware.org/?probe=7b5f2ca2f9) | Dec 03, 2023 |
| Dell          | Precision 7530              | [e75b16ca5e](https://linux-hardware.org/?probe=e75b16ca5e) | Dec 03, 2023 |
| ASUSTek       | X551CA                      | [08ce611291](https://linux-hardware.org/?probe=08ce611291) | Dec 02, 2023 |
| HP            | ProBook 4540s               | [d83489845d](https://linux-hardware.org/?probe=d83489845d) | Dec 02, 2023 |
| Acer          | Aspire E5-575               | [e6fd8cf7f1](https://linux-hardware.org/?probe=e6fd8cf7f1) | Dec 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [744c430aa7](https://linux-hardware.org/?probe=744c430aa7) | Dec 02, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [5cf002f5af](https://linux-hardware.org/?probe=5cf002f5af) | Dec 02, 2023 |
| Lenovo        | Flex 2-14 20404             | [f366381075](https://linux-hardware.org/?probe=f366381075) | Dec 02, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV0R     | [933f88f7e6](https://linux-hardware.org/?probe=933f88f7e6) | Dec 01, 2023 |
| Valve         | Jupiter                     | [545d093510](https://linux-hardware.org/?probe=545d093510) | Nov 30, 2023 |
| Valve         | Jupiter                     | [2251ba47fb](https://linux-hardware.org/?probe=2251ba47fb) | Nov 30, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [37545bd915](https://linux-hardware.org/?probe=37545bd915) | Nov 30, 2023 |
| Apple         | MacBookPro11,1              | [21a183f050](https://linux-hardware.org/?probe=21a183f050) | Nov 30, 2023 |
| Lenovo        | ThinkPad P52s 20LCA0ANUK    | [2cf85106d8](https://linux-hardware.org/?probe=2cf85106d8) | Nov 29, 2023 |
| HP            | Laptop 15-bw0xx             | [d9e4a9a2cd](https://linux-hardware.org/?probe=d9e4a9a2cd) | Nov 29, 2023 |
| HP            | Laptop 15-bw0xx             | [e3e8042ebf](https://linux-hardware.org/?probe=e3e8042ebf) | Nov 29, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [4948ddc4be](https://linux-hardware.org/?probe=4948ddc4be) | Nov 29, 2023 |
| Dell          | Inspiron 15 3530            | [410e2cc867](https://linux-hardware.org/?probe=410e2cc867) | Nov 29, 2023 |
| Acer          | Aspire E5-575               | [b4fbd61258](https://linux-hardware.org/?probe=b4fbd61258) | Nov 28, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [f2b1e6e4a9](https://linux-hardware.org/?probe=f2b1e6e4a9) | Nov 28, 2023 |
| Dell          | Latitude 7390               | [4cacd41fee](https://linux-hardware.org/?probe=4cacd41fee) | Nov 28, 2023 |
| AWOW          | AK41                        | [34d9bc9a34](https://linux-hardware.org/?probe=34d9bc9a34) | Nov 28, 2023 |
| AWOW          | AK41                        | [17f3a70619](https://linux-hardware.org/?probe=17f3a70619) | Nov 28, 2023 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [7be81f9e9c](https://linux-hardware.org/?probe=7be81f9e9c) | Nov 28, 2023 |
| Acer          | Aspire 5740                 | [bad53e91fc](https://linux-hardware.org/?probe=bad53e91fc) | Nov 27, 2023 |
| HP            | EliteBook 640 14 inch G9... | [51b0a49d02](https://linux-hardware.org/?probe=51b0a49d02) | Nov 27, 2023 |
| Dell          | Inspiron 1012               | [ffe483f5fd](https://linux-hardware.org/?probe=ffe483f5fd) | Nov 27, 2023 |
| Dell          | Latitude D830               | [2e017edf81](https://linux-hardware.org/?probe=2e017edf81) | Nov 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS0RK00    | [96642d7e8e](https://linux-hardware.org/?probe=96642d7e8e) | Nov 27, 2023 |
| HP            | Pavilion Notebook           | [2ccf3a5db5](https://linux-hardware.org/?probe=2ccf3a5db5) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [e552669069](https://linux-hardware.org/?probe=e552669069) | Nov 26, 2023 |
| Toshiba       | TECRA R940                  | [14de9f481a](https://linux-hardware.org/?probe=14de9f481a) | Nov 26, 2023 |
| Lenovo        | ThinkPad Edge E325 12973... | [0f165c67ac](https://linux-hardware.org/?probe=0f165c67ac) | Nov 26, 2023 |
| Dell          | XPS 15 9570                 | [99daa92571](https://linux-hardware.org/?probe=99daa92571) | Nov 25, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | [8973295484](https://linux-hardware.org/?probe=8973295484) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [082c36ab01](https://linux-hardware.org/?probe=082c36ab01) | Nov 25, 2023 |
| Acer          | Aspire A315-58              | [1bf1e47f81](https://linux-hardware.org/?probe=1bf1e47f81) | Nov 24, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [4f78b76325](https://linux-hardware.org/?probe=4f78b76325) | Nov 24, 2023 |
| Toshiba       | Satellite L300              | [370ddc00c4](https://linux-hardware.org/?probe=370ddc00c4) | Nov 24, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [d8bb656eaf](https://linux-hardware.org/?probe=d8bb656eaf) | Nov 24, 2023 |
| Dell          | XPS 15 9560                 | [a2313adb82](https://linux-hardware.org/?probe=a2313adb82) | Nov 24, 2023 |
| Dell          | Inspiron 5577               | [1302407078](https://linux-hardware.org/?probe=1302407078) | Nov 24, 2023 |
| Dell          | Inspiron 5577               | [7871e7654b](https://linux-hardware.org/?probe=7871e7654b) | Nov 24, 2023 |
| Apple         | MacBookPro14,2              | [e210f3a972](https://linux-hardware.org/?probe=e210f3a972) | Nov 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [59a3d34f64](https://linux-hardware.org/?probe=59a3d34f64) | Nov 24, 2023 |
| Valve         | Jupiter                     | [0c58fa47b9](https://linux-hardware.org/?probe=0c58fa47b9) | Nov 24, 2023 |
| Linx          | LINX1010L                   | [07d470eaac](https://linux-hardware.org/?probe=07d470eaac) | Nov 23, 2023 |
| Acer          | Aspire E5-511               | [87ccf00042](https://linux-hardware.org/?probe=87ccf00042) | Nov 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS00700    | [e0be96f7e5](https://linux-hardware.org/?probe=e0be96f7e5) | Nov 23, 2023 |
| HP            | Pavilion Notebook           | [7d55f31a65](https://linux-hardware.org/?probe=7d55f31a65) | Nov 23, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [48677cfae1](https://linux-hardware.org/?probe=48677cfae1) | Nov 23, 2023 |
| HUAWEI        | BoDE-WXX9                   | [343ba69496](https://linux-hardware.org/?probe=343ba69496) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | [b365872b3f](https://linux-hardware.org/?probe=b365872b3f) | Nov 22, 2023 |
| Acer          | TravelMate 5760             | [bcec28eaaa](https://linux-hardware.org/?probe=bcec28eaaa) | Nov 22, 2023 |
| Dell          | XPS 15 9570                 | [7728d0ab4b](https://linux-hardware.org/?probe=7728d0ab4b) | Nov 22, 2023 |
| Valve         | Jupiter                     | [157c8167b7](https://linux-hardware.org/?probe=157c8167b7) | Nov 22, 2023 |
| Valve         | Jupiter                     | [525a89cf72](https://linux-hardware.org/?probe=525a89cf72) | Nov 22, 2023 |
| ASUSTek       | E201NA                      | [11f7e8f675](https://linux-hardware.org/?probe=11f7e8f675) | Nov 22, 2023 |
| Apple         | MacBookPro11,4              | [007d6a928b](https://linux-hardware.org/?probe=007d6a928b) | Nov 21, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [c3fc46a4a5](https://linux-hardware.org/?probe=c3fc46a4a5) | Nov 21, 2023 |
| HP            | OMEN by Laptop              | [8fbd1e56eb](https://linux-hardware.org/?probe=8fbd1e56eb) | Nov 20, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [26ebeb2504](https://linux-hardware.org/?probe=26ebeb2504) | Nov 20, 2023 |
| Jumper        | EZbook                      | [f41c8192dc](https://linux-hardware.org/?probe=f41c8192dc) | Nov 20, 2023 |
| Notebook      | NS5x_NS7xPU                 | [7e047fc166](https://linux-hardware.org/?probe=7e047fc166) | Nov 19, 2023 |
| iOTA          | IOTA2320                    | [5c4d630f23](https://linux-hardware.org/?probe=5c4d630f23) | Nov 19, 2023 |
| Apple         | MacBookPro11,4              | [07fadadf4b](https://linux-hardware.org/?probe=07fadadf4b) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [a566513a93](https://linux-hardware.org/?probe=a566513a93) | Nov 19, 2023 |
| Toshiba       | Satellite C660D             | [fed171dba3](https://linux-hardware.org/?probe=fed171dba3) | Nov 18, 2023 |
| Dell          | Precision M6800             | [14dc3b5711](https://linux-hardware.org/?probe=14dc3b5711) | Nov 18, 2023 |
| Dell          | Inspiron 7591               | [edb7712542](https://linux-hardware.org/?probe=edb7712542) | Nov 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [8f0b8a5f62](https://linux-hardware.org/?probe=8f0b8a5f62) | Nov 17, 2023 |
| Google        | Liara                       | [0180a501ac](https://linux-hardware.org/?probe=0180a501ac) | Nov 17, 2023 |
| Apple         | MacBookAir3,2               | [17cf4dd653](https://linux-hardware.org/?probe=17cf4dd653) | Nov 17, 2023 |
| Google        | Liara                       | [081111241a](https://linux-hardware.org/?probe=081111241a) | Nov 16, 2023 |
| Google        | Liara                       | [c63d296cc8](https://linux-hardware.org/?probe=c63d296cc8) | Nov 16, 2023 |
| Samsung       | 550P5C/550P7C               | [343e6ecd28](https://linux-hardware.org/?probe=343e6ecd28) | Nov 16, 2023 |
| MSI           | Katana GF66 11UE            | [07a03ff43b](https://linux-hardware.org/?probe=07a03ff43b) | Nov 16, 2023 |
| Dell          | Latitude E6330              | [c7ef1a8bbd](https://linux-hardware.org/?probe=c7ef1a8bbd) | Nov 16, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [7e0ac6c6d6](https://linux-hardware.org/?probe=7e0ac6c6d6) | Nov 16, 2023 |
| Jumper        | EZbook                      | [844843779e](https://linux-hardware.org/?probe=844843779e) | Nov 16, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | [669eb1edcb](https://linux-hardware.org/?probe=669eb1edcb) | Nov 16, 2023 |
| Valve         | Jupiter                     | [821a98f0f9](https://linux-hardware.org/?probe=821a98f0f9) | Nov 15, 2023 |
| Acer          | Aspire E5-576G              | [694833562c](https://linux-hardware.org/?probe=694833562c) | Nov 15, 2023 |
| Apple         | MacBookPro7,1               | [90bcff6517](https://linux-hardware.org/?probe=90bcff6517) | Nov 15, 2023 |
| Dell          | XPS 17 9730                 | [27fb977584](https://linux-hardware.org/?probe=27fb977584) | Nov 15, 2023 |
| Alienware     | 14                          | [3f12c6cbcd](https://linux-hardware.org/?probe=3f12c6cbcd) | Nov 15, 2023 |
| Dell          | Latitude 5520               | [a50a13d22b](https://linux-hardware.org/?probe=a50a13d22b) | Nov 14, 2023 |
| Acer          | Aspire V5-571               | [6a560e9f7c](https://linux-hardware.org/?probe=6a560e9f7c) | Nov 14, 2023 |
| HP            | ZBook 14u G6                | [c6471dbbfd](https://linux-hardware.org/?probe=c6471dbbfd) | Nov 14, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [551661ff00](https://linux-hardware.org/?probe=551661ff00) | Nov 14, 2023 |
| Acer          | Aspire E1-572P              | [8644bc6bf3](https://linux-hardware.org/?probe=8644bc6bf3) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | [077bbdc325](https://linux-hardware.org/?probe=077bbdc325) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | [5e50f31cbb](https://linux-hardware.org/?probe=5e50f31cbb) | Nov 14, 2023 |
| Dell          | Latitude E5430 non-vPro     | [8c49972e61](https://linux-hardware.org/?probe=8c49972e61) | Nov 14, 2023 |
| AWOW          | AK41                        | [5d9f671218](https://linux-hardware.org/?probe=5d9f671218) | Nov 14, 2023 |
| AWOW          | AK41                        | [89e2926ff6](https://linux-hardware.org/?probe=89e2926ff6) | Nov 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [e3926c718f](https://linux-hardware.org/?probe=e3926c718f) | Nov 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [917ab5dcf0](https://linux-hardware.org/?probe=917ab5dcf0) | Nov 14, 2023 |
| Apple         | MacBookPro14,2              | [6ce3699c41](https://linux-hardware.org/?probe=6ce3699c41) | Nov 14, 2023 |
| Apple         | MacBookPro14,2              | [3e5fd22123](https://linux-hardware.org/?probe=3e5fd22123) | Nov 14, 2023 |
| Clevo         | W55xEU                      | [52795e38fa](https://linux-hardware.org/?probe=52795e38fa) | Nov 14, 2023 |
| HP            | Pavilion g6                 | [8e95b24f18](https://linux-hardware.org/?probe=8e95b24f18) | Nov 13, 2023 |
| Acer          | Aspire A114-33              | [e592b6bf5d](https://linux-hardware.org/?probe=e592b6bf5d) | Nov 13, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [c143de0389](https://linux-hardware.org/?probe=c143de0389) | Nov 13, 2023 |
| Dell          | XPS 15 9570                 | [ed85cdf855](https://linux-hardware.org/?probe=ed85cdf855) | Nov 13, 2023 |
| Acer          | Aspire A114-33              | [6c532c337f](https://linux-hardware.org/?probe=6c532c337f) | Nov 12, 2023 |
| HP            | EliteBook 840 G4            | [2651393e60](https://linux-hardware.org/?probe=2651393e60) | Nov 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [81dca17f20](https://linux-hardware.org/?probe=81dca17f20) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8b2e3f1f31](https://linux-hardware.org/?probe=8b2e3f1f31) | Nov 12, 2023 |
| Linx          | LINX1010B                   | [aa641d2775](https://linux-hardware.org/?probe=aa641d2775) | Nov 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [f0db6bb1ae](https://linux-hardware.org/?probe=f0db6bb1ae) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [4c24ca4aa2](https://linux-hardware.org/?probe=4c24ca4aa2) | Nov 11, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [20394838bd](https://linux-hardware.org/?probe=20394838bd) | Nov 11, 2023 |
| Acer          | Aspire V5-571               | [062edee7f6](https://linux-hardware.org/?probe=062edee7f6) | Nov 10, 2023 |
| Apple         | MacBookPro11,4              | [029e4d74e4](https://linux-hardware.org/?probe=029e4d74e4) | Nov 10, 2023 |
| Apple         | MacBookAir6,2               | [f5147fc0f5](https://linux-hardware.org/?probe=f5147fc0f5) | Nov 10, 2023 |
| HP            | Laptop 14-bs0xx             | [a6085bc08f](https://linux-hardware.org/?probe=a6085bc08f) | Nov 10, 2023 |
| HP            | Laptop 14-bs0xx             | [e8cbd8b1b9](https://linux-hardware.org/?probe=e8cbd8b1b9) | Nov 10, 2023 |
| Valve         | Jupiter                     | [ff8cbcd6be](https://linux-hardware.org/?probe=ff8cbcd6be) | Nov 09, 2023 |
| Lenovo        | ThinkPad T420 4180AZ8       | [089405c957](https://linux-hardware.org/?probe=089405c957) | Nov 09, 2023 |
| Toshiba       | Satellite C50-A-1CK         | [630df1e190](https://linux-hardware.org/?probe=630df1e190) | Nov 09, 2023 |
| Toshiba       | Satellite C50-A-1CK         | [9eb1ed3f2b](https://linux-hardware.org/?probe=9eb1ed3f2b) | Nov 09, 2023 |
| Dell          | XPS 15 9560                 | [f107797037](https://linux-hardware.org/?probe=f107797037) | Nov 09, 2023 |
| Valve         | Jupiter                     | [2e7ed7b6c8](https://linux-hardware.org/?probe=2e7ed7b6c8) | Nov 09, 2023 |
| HP            | Laptop 14s-dq2xxx           | [6bc6e8bb07](https://linux-hardware.org/?probe=6bc6e8bb07) | Nov 08, 2023 |
| Acer          | Aspire A515-43              | [6e215a4ade](https://linux-hardware.org/?probe=6e215a4ade) | Nov 08, 2023 |
| Acer          | Aspire A515-44              | [dbfe362cd8](https://linux-hardware.org/?probe=dbfe362cd8) | Nov 08, 2023 |
| Dell          | XPS 15 9560                 | [7e3747e291](https://linux-hardware.org/?probe=7e3747e291) | Nov 07, 2023 |
| Dell          | Latitude 5175               | [7b4721323a](https://linux-hardware.org/?probe=7b4721323a) | Nov 07, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [d698d770e1](https://linux-hardware.org/?probe=d698d770e1) | Nov 07, 2023 |
| Lenovo        | V130-15IKB 81HN             | [3ccd2441ac](https://linux-hardware.org/?probe=3ccd2441ac) | Nov 07, 2023 |
| Lenovo        | V130-15IKB 81HN             | [e2d2219122](https://linux-hardware.org/?probe=e2d2219122) | Nov 07, 2023 |
| HP            | EliteBook 840 14 inch G9... | [09b818e1d3](https://linux-hardware.org/?probe=09b818e1d3) | Nov 07, 2023 |
| Acer          | Aspire A315-21              | [f51da852ca](https://linux-hardware.org/?probe=f51da852ca) | Nov 07, 2023 |
| Acer          | Aspire A315-21              | [35b7b043ff](https://linux-hardware.org/?probe=35b7b043ff) | Nov 07, 2023 |
| Lenovo        | Z50-75 80EC                 | [c98cdea69b](https://linux-hardware.org/?probe=c98cdea69b) | Nov 07, 2023 |
| Valve         | Jupiter                     | [c00bcace68](https://linux-hardware.org/?probe=c00bcace68) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [6f9ee3fea0](https://linux-hardware.org/?probe=6f9ee3fea0) | Nov 06, 2023 |
| Dell          | Latitude E6440              | [ad28c1e239](https://linux-hardware.org/?probe=ad28c1e239) | Nov 06, 2023 |
| HP            | ProBook 6470b               | [50c1d43281](https://linux-hardware.org/?probe=50c1d43281) | Nov 05, 2023 |
| HP            | 250 G5 Notebook PC          | [7b281cb925](https://linux-hardware.org/?probe=7b281cb925) | Nov 05, 2023 |
| Valve         | Jupiter                     | [28e2c2aa38](https://linux-hardware.org/?probe=28e2c2aa38) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [7a8597dd50](https://linux-hardware.org/?probe=7a8597dd50) | Nov 05, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [fc01ceb47b](https://linux-hardware.org/?probe=fc01ceb47b) | Nov 05, 2023 |
| Dell          | Inspiron 7501               | [0926c7cdad](https://linux-hardware.org/?probe=0926c7cdad) | Nov 05, 2023 |
| HP            | Laptop 15-bw0xx             | [7d9395e4a7](https://linux-hardware.org/?probe=7d9395e4a7) | Nov 05, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [dc13d6012b](https://linux-hardware.org/?probe=dc13d6012b) | Nov 04, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [5d8cae0407](https://linux-hardware.org/?probe=5d8cae0407) | Nov 04, 2023 |
| HP            | Presario C500 (GF849EA#A... | [a4965dff09](https://linux-hardware.org/?probe=a4965dff09) | Nov 04, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [812ceefef6](https://linux-hardware.org/?probe=812ceefef6) | Nov 04, 2023 |
| Valve         | Jupiter                     | [af20418f73](https://linux-hardware.org/?probe=af20418f73) | Nov 04, 2023 |
| Valve         | Jupiter                     | [28f8f3e3cd](https://linux-hardware.org/?probe=28f8f3e3cd) | Nov 04, 2023 |
| HUAWEI        | MRGFG-XX                    | [5117a849b3](https://linux-hardware.org/?probe=5117a849b3) | Nov 03, 2023 |
| Dell          | Precision 5550              | [033e294199](https://linux-hardware.org/?probe=033e294199) | Nov 03, 2023 |
| Toshiba       | Satellite C660D             | [de50c92d6c](https://linux-hardware.org/?probe=de50c92d6c) | Nov 03, 2023 |
| Valve         | Jupiter                     | [b526accbcd](https://linux-hardware.org/?probe=b526accbcd) | Nov 03, 2023 |
| Dell          | Vostro 5590                 | [aa355fcc89](https://linux-hardware.org/?probe=aa355fcc89) | Nov 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [5d58dd522f](https://linux-hardware.org/?probe=5d58dd522f) | Nov 01, 2023 |
| Apple         | MacBook9,1                  | [44cec57d44](https://linux-hardware.org/?probe=44cec57d44) | Nov 01, 2023 |
| Apple         | MacBookAir5,1               | [d7b563a839](https://linux-hardware.org/?probe=d7b563a839) | Oct 31, 2023 |
| HP            | G56                         | [db44e7df47](https://linux-hardware.org/?probe=db44e7df47) | Oct 31, 2023 |
| Lenovo        | ThinkPad T530 24296JG       | [b443eebcad](https://linux-hardware.org/?probe=b443eebcad) | Oct 31, 2023 |
| Alienware     | 14                          | [e88b7c0ac6](https://linux-hardware.org/?probe=e88b7c0ac6) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [72131fb5de](https://linux-hardware.org/?probe=72131fb5de) | Oct 31, 2023 |
| HP            | Presario C500 (GF849EA#A... | [580f4bdb18](https://linux-hardware.org/?probe=580f4bdb18) | Oct 31, 2023 |
| Dell          | Latitude E5520              | [445903fc05](https://linux-hardware.org/?probe=445903fc05) | Oct 31, 2023 |
| Toshiba       | Satellite C660D             | [26479d99b9](https://linux-hardware.org/?probe=26479d99b9) | Oct 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [43772c58a4](https://linux-hardware.org/?probe=43772c58a4) | Oct 30, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [8b1fe7cf44](https://linux-hardware.org/?probe=8b1fe7cf44) | Oct 30, 2023 |
| AWOW          | AK41                        | [bed4203da6](https://linux-hardware.org/?probe=bed4203da6) | Oct 30, 2023 |
| ASUSTek       | X551CA                      | [1a14a8f0c4](https://linux-hardware.org/?probe=1a14a8f0c4) | Oct 29, 2023 |
| ASUSTek       | X551CA                      | [a43802c314](https://linux-hardware.org/?probe=a43802c314) | Oct 29, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [7bdcd09429](https://linux-hardware.org/?probe=7bdcd09429) | Oct 29, 2023 |
| HP            | Pavilion g6                 | [57441db309](https://linux-hardware.org/?probe=57441db309) | Oct 29, 2023 |
| Panasonic     | CF-191HA23DE                | [3ccc424983](https://linux-hardware.org/?probe=3ccc424983) | Oct 29, 2023 |
| Dell          | Precision M6800             | [3645954ce0](https://linux-hardware.org/?probe=3645954ce0) | Oct 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [1d1a7bd472](https://linux-hardware.org/?probe=1d1a7bd472) | Oct 28, 2023 |
| Dell          | Latitude E6500              | [41e90a6524](https://linux-hardware.org/?probe=41e90a6524) | Oct 28, 2023 |
| Dell          | Inspiron MM061              | [7545369484](https://linux-hardware.org/?probe=7545369484) | Oct 28, 2023 |
| Dell          | XPS 15 9560                 | [69a0449eee](https://linux-hardware.org/?probe=69a0449eee) | Oct 28, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [5c169fe4ed](https://linux-hardware.org/?probe=5c169fe4ed) | Oct 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6a8554304e](https://linux-hardware.org/?probe=6a8554304e) | Oct 27, 2023 |
| Lenovo        | ThinkPad T450 20BUS00700    | [f74328fd58](https://linux-hardware.org/?probe=f74328fd58) | Oct 27, 2023 |
| Apple         | MacBookPro7,1               | [fe15ca03f2](https://linux-hardware.org/?probe=fe15ca03f2) | Oct 27, 2023 |
| Dell          | Inspiron 1501               | [2c88e089bb](https://linux-hardware.org/?probe=2c88e089bb) | Oct 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JKC... | [c9ba633d37](https://linux-hardware.org/?probe=c9ba633d37) | Oct 27, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [1c1d7bd2b1](https://linux-hardware.org/?probe=1c1d7bd2b1) | Oct 27, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [311f057665](https://linux-hardware.org/?probe=311f057665) | Oct 26, 2023 |
| HP            | EliteBook 630 13.3 inch ... | [8f57ab5108](https://linux-hardware.org/?probe=8f57ab5108) | Oct 26, 2023 |
| HP            | ProBook 650 G1              | [5b2aac75a9](https://linux-hardware.org/?probe=5b2aac75a9) | Oct 26, 2023 |
| AWOW          | AK41                        | [e40c573853](https://linux-hardware.org/?probe=e40c573853) | Oct 26, 2023 |
| Acer          | Aspire A514-55              | [4d1e460056](https://linux-hardware.org/?probe=4d1e460056) | Oct 25, 2023 |
| Acer          | Aspire A514-55              | [3a1de9e1d1](https://linux-hardware.org/?probe=3a1de9e1d1) | Oct 25, 2023 |
| Dell          | Precision 7550              | [b6f0ce0285](https://linux-hardware.org/?probe=b6f0ce0285) | Oct 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [2b1387ee7c](https://linux-hardware.org/?probe=2b1387ee7c) | Oct 24, 2023 |
| Toshiba       | Satellite NB10t-A-102       | [85f85dffbd](https://linux-hardware.org/?probe=85f85dffbd) | Oct 24, 2023 |
| Eii           | WSA116                      | [85da70314e](https://linux-hardware.org/?probe=85da70314e) | Oct 23, 2023 |
| Dell          | XPS 13 9300                 | [9d7ecc567c](https://linux-hardware.org/?probe=9d7ecc567c) | Oct 23, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [38823c0a55](https://linux-hardware.org/?probe=38823c0a55) | Oct 22, 2023 |
| Dell          | Inspiron 3501               | [084dd63188](https://linux-hardware.org/?probe=084dd63188) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [e503ffe188](https://linux-hardware.org/?probe=e503ffe188) | Oct 21, 2023 |
| Lenovo        | V330-14ARR 81B1             | [b80592c227](https://linux-hardware.org/?probe=b80592c227) | Oct 21, 2023 |
| Dell          | Latitude E6400              | [5e09b89469](https://linux-hardware.org/?probe=5e09b89469) | Oct 20, 2023 |
| ASUSTek       | X453MA                      | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| Acer          | Swift SFX14-51G             | [2adde1171a](https://linux-hardware.org/?probe=2adde1171a) | Oct 20, 2023 |
| HP            | EliteBook 630 13.3 inch ... | [e1ed7c2ee4](https://linux-hardware.org/?probe=e1ed7c2ee4) | Oct 20, 2023 |
| Valve         | Jupiter                     | [fdbd97d08c](https://linux-hardware.org/?probe=fdbd97d08c) | Oct 20, 2023 |
| Novatech      | W9x0LU                      | [b6e3d3dfc9](https://linux-hardware.org/?probe=b6e3d3dfc9) | Oct 19, 2023 |
| HUAWEI        | HN-WX9X                     | [6fc8b26d2c](https://linux-hardware.org/?probe=6fc8b26d2c) | Oct 19, 2023 |
| HUAWEI        | HN-WX9X                     | [827a7bf56c](https://linux-hardware.org/?probe=827a7bf56c) | Oct 19, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [dae01ed766](https://linux-hardware.org/?probe=dae01ed766) | Oct 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [bc4cc061a2](https://linux-hardware.org/?probe=bc4cc061a2) | Oct 18, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [660d60e1a8](https://linux-hardware.org/?probe=660d60e1a8) | Oct 17, 2023 |
| HP            | ProBook 645 G1              | [d1eeca057f](https://linux-hardware.org/?probe=d1eeca057f) | Oct 17, 2023 |
| Alienware     | m15                         | [34919bdeca](https://linux-hardware.org/?probe=34919bdeca) | Oct 17, 2023 |
| Dell          | Latitude 5490               | [d85f87c8b0](https://linux-hardware.org/?probe=d85f87c8b0) | Oct 17, 2023 |
| Dell          | G15 5515                    | [080e34562c](https://linux-hardware.org/?probe=080e34562c) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [6fe57753a4](https://linux-hardware.org/?probe=6fe57753a4) | Oct 17, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [da0024090d](https://linux-hardware.org/?probe=da0024090d) | Oct 16, 2023 |
| Dell          | Latitude E6540              | [27875d6fe5](https://linux-hardware.org/?probe=27875d6fe5) | Oct 16, 2023 |
| Dell          | XPS 15 9500                 | [0dcdd0a6a6](https://linux-hardware.org/?probe=0dcdd0a6a6) | Oct 16, 2023 |
| Lenovo        | ThinkPad E565 20EY000XUK    | [b7cf6113c4](https://linux-hardware.org/?probe=b7cf6113c4) | Oct 16, 2023 |
| Dell          | Precision M6700             | [2fb2e2e9a5](https://linux-hardware.org/?probe=2fb2e2e9a5) | Oct 16, 2023 |
| Valve         | Jupiter                     | [d8ba22dd7f](https://linux-hardware.org/?probe=d8ba22dd7f) | Oct 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | [386d015b42](https://linux-hardware.org/?probe=386d015b42) | Oct 16, 2023 |
| HP            | ZBook 15 G3                 | [02bc0ccf6d](https://linux-hardware.org/?probe=02bc0ccf6d) | Oct 16, 2023 |
| HUAWEI        | CREF-XX                     | [3d9bd14288](https://linux-hardware.org/?probe=3d9bd14288) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [22b5b65e16](https://linux-hardware.org/?probe=22b5b65e16) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| Google        | Careena                     | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| ASUSTek       | K70IO                       | [e9d2ce541a](https://linux-hardware.org/?probe=e9d2ce541a) | Oct 13, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | [d14e3ec320](https://linux-hardware.org/?probe=d14e3ec320) | Oct 13, 2023 |
| Dell          | Precision 3580              | [f2a080ed43](https://linux-hardware.org/?probe=f2a080ed43) | Oct 13, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [1b88716ae2](https://linux-hardware.org/?probe=1b88716ae2) | Oct 13, 2023 |
| Dell          | XPS 15 9530                 | [f5f02b30f0](https://linux-hardware.org/?probe=f5f02b30f0) | Oct 13, 2023 |
| Dell          | Precision 7520              | [de5b9c8fa1](https://linux-hardware.org/?probe=de5b9c8fa1) | Oct 13, 2023 |
| HUAWEI        | BOHL-WXX9                   | [85cc4b4c4a](https://linux-hardware.org/?probe=85cc4b4c4a) | Oct 12, 2023 |
| Dell          | Inspiron 3505               | [dad114bac6](https://linux-hardware.org/?probe=dad114bac6) | Oct 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f767f8dd4d](https://linux-hardware.org/?probe=f767f8dd4d) | Oct 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [6396467c6d](https://linux-hardware.org/?probe=6396467c6d) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | [18b3c9fef8](https://linux-hardware.org/?probe=18b3c9fef8) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | [7c843b4c27](https://linux-hardware.org/?probe=7c843b4c27) | Oct 12, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [02c2fabd1e](https://linux-hardware.org/?probe=02c2fabd1e) | Oct 11, 2023 |
| Dell          | Precision 3571              | [ac3735cea4](https://linux-hardware.org/?probe=ac3735cea4) | Oct 11, 2023 |
| Dell          | Inspiron 15 3525            | [66bd7ea744](https://linux-hardware.org/?probe=66bd7ea744) | Oct 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [b4db6e379a](https://linux-hardware.org/?probe=b4db6e379a) | Oct 10, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [162889c4a3](https://linux-hardware.org/?probe=162889c4a3) | Oct 10, 2023 |
| Dell          | Inspiron 13-7359            | [64ad406dc0](https://linux-hardware.org/?probe=64ad406dc0) | Oct 10, 2023 |
| HP            | ProBook 450 G7              | [5805e4a7cb](https://linux-hardware.org/?probe=5805e4a7cb) | Oct 10, 2023 |
| Valve         | Jupiter                     | [daeb359dfb](https://linux-hardware.org/?probe=daeb359dfb) | Oct 10, 2023 |
| AZW           | SEi                         | [ed42118987](https://linux-hardware.org/?probe=ed42118987) | Oct 10, 2023 |
| ASUSTek       | N75SL                       | [8d6fe1b102](https://linux-hardware.org/?probe=8d6fe1b102) | Oct 09, 2023 |
| Dell          | Inspiron 13-5378            | [ee7086c9da](https://linux-hardware.org/?probe=ee7086c9da) | Oct 09, 2023 |
| Toshiba       | Satellite Pro R50-B         | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [44aa7c21f9](https://linux-hardware.org/?probe=44aa7c21f9) | Oct 09, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [02a4135aff](https://linux-hardware.org/?probe=02a4135aff) | Oct 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [d6b0808093](https://linux-hardware.org/?probe=d6b0808093) | Oct 09, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [6ffcd3c463](https://linux-hardware.org/?probe=6ffcd3c463) | Oct 09, 2023 |
| MSI           | Katana GF66 11UG            | [0816e0912b](https://linux-hardware.org/?probe=0816e0912b) | Oct 09, 2023 |
| Acer          | Aspire A517-52              | [fbe223cc6d](https://linux-hardware.org/?probe=fbe223cc6d) | Oct 08, 2023 |
| Acer          | Aspire A517-52              | [2a51c0c510](https://linux-hardware.org/?probe=2a51c0c510) | Oct 08, 2023 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | [43f05c011e](https://linux-hardware.org/?probe=43f05c011e) | Oct 08, 2023 |
| Valve         | Jupiter                     | [83976ddca6](https://linux-hardware.org/?probe=83976ddca6) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [63cbb26f44](https://linux-hardware.org/?probe=63cbb26f44) | Oct 08, 2023 |
| PC Special... | P65_P67RGRERA               | [c2779bc01c](https://linux-hardware.org/?probe=c2779bc01c) | Oct 08, 2023 |
| Valve         | Jupiter                     | [aa51056093](https://linux-hardware.org/?probe=aa51056093) | Oct 08, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [7f27dfbc34](https://linux-hardware.org/?probe=7f27dfbc34) | Oct 07, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [2adab9deb5](https://linux-hardware.org/?probe=2adab9deb5) | Oct 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e087628f2a](https://linux-hardware.org/?probe=e087628f2a) | Oct 07, 2023 |
| Apple         | MacBookAir6,1               | [9bd895191b](https://linux-hardware.org/?probe=9bd895191b) | Oct 06, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [da6b1b88e6](https://linux-hardware.org/?probe=da6b1b88e6) | Oct 06, 2023 |
| Star Labs     | StarBook                    | [57a76a9d14](https://linux-hardware.org/?probe=57a76a9d14) | Oct 06, 2023 |
| Lenovo        | ThinkPad T430 2349STC       | [53e8d1302b](https://linux-hardware.org/?probe=53e8d1302b) | Oct 05, 2023 |
| Dell          | Latitude 7390               | [6204f328e3](https://linux-hardware.org/?probe=6204f328e3) | Oct 05, 2023 |
| Dell          | XPS 15 9560                 | [381be666c0](https://linux-hardware.org/?probe=381be666c0) | Oct 04, 2023 |
| Fujitsu Si... | LIFEBOOK T4215              | [392481b855](https://linux-hardware.org/?probe=392481b855) | Oct 04, 2023 |
| Sony          | SVE1511K1ESI                | [935bdcf05c](https://linux-hardware.org/?probe=935bdcf05c) | Oct 04, 2023 |
| Toshiba       | Satellite C50-A-1DV         | [190ce47896](https://linux-hardware.org/?probe=190ce47896) | Oct 03, 2023 |
| Toshiba       | Satellite C50-A-1DV         | [791e483369](https://linux-hardware.org/?probe=791e483369) | Oct 03, 2023 |
| Acer          | Aspire 5720                 | [6009fced37](https://linux-hardware.org/?probe=6009fced37) | Oct 03, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | [fc95f3feef](https://linux-hardware.org/?probe=fc95f3feef) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3657d65cec](https://linux-hardware.org/?probe=3657d65cec) | Oct 03, 2023 |
| Apple         | MacBookAir6,2               | [23c850d9d3](https://linux-hardware.org/?probe=23c850d9d3) | Oct 03, 2023 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | [57b94fa258](https://linux-hardware.org/?probe=57b94fa258) | Oct 02, 2023 |
| Dell          | Inspiron 3542               | [4e74bbc8e2](https://linux-hardware.org/?probe=4e74bbc8e2) | Oct 02, 2023 |
| Samsung       | 750XED                      | [33e2bf8845](https://linux-hardware.org/?probe=33e2bf8845) | Oct 02, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [8cc4ccdbec](https://linux-hardware.org/?probe=8cc4ccdbec) | Oct 01, 2023 |
| Dell          | Inspiron 13-5378            | [c25e886d9d](https://linux-hardware.org/?probe=c25e886d9d) | Oct 01, 2023 |
| Dell          | XPS 15 9500                 | [a8f95ea32d](https://linux-hardware.org/?probe=a8f95ea32d) | Oct 01, 2023 |
| Acer          | Predator G9-793             | [fd305490af](https://linux-hardware.org/?probe=fd305490af) | Oct 01, 2023 |
| Valve         | Jupiter                     | [d64d0a1997](https://linux-hardware.org/?probe=d64d0a1997) | Sep 30, 2023 |
| Entroware     | Hybris                      | [5b124e9b7f](https://linux-hardware.org/?probe=5b124e9b7f) | Sep 30, 2023 |
| HP            | Pavilion dv5                | [0b1da8643f](https://linux-hardware.org/?probe=0b1da8643f) | Sep 30, 2023 |
| Acer          | Aspire 7741                 | [80d27e2808](https://linux-hardware.org/?probe=80d27e2808) | Sep 30, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [2afa933d2a](https://linux-hardware.org/?probe=2afa933d2a) | Sep 30, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [a7a8e627cb](https://linux-hardware.org/?probe=a7a8e627cb) | Sep 30, 2023 |
| OEGStone      | C4100/C5100                 | [0c27e50b14](https://linux-hardware.org/?probe=0c27e50b14) | Sep 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WY00    | [6a18fb9b21](https://linux-hardware.org/?probe=6a18fb9b21) | Sep 29, 2023 |
| Alienware     | m16 R1 AMD                  | [710a10efce](https://linux-hardware.org/?probe=710a10efce) | Sep 29, 2023 |
| Alienware     | x15 R1                      | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| Dell          | XPS 13 9360                 | [2a3e49f18f](https://linux-hardware.org/?probe=2a3e49f18f) | Sep 29, 2023 |
| Google        | Swanky                      | [599959ccbe](https://linux-hardware.org/?probe=599959ccbe) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | [cb2cbda84d](https://linux-hardware.org/?probe=cb2cbda84d) | Sep 28, 2023 |
| Dell          | Precision 3560              | [14af02a240](https://linux-hardware.org/?probe=14af02a240) | Sep 28, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [dcf11408af](https://linux-hardware.org/?probe=dcf11408af) | Sep 28, 2023 |
| Valve         | Jupiter                     | [39bc0d89fe](https://linux-hardware.org/?probe=39bc0d89fe) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | [2b7f074e47](https://linux-hardware.org/?probe=2b7f074e47) | Sep 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S5M000    | [58ddf5337a](https://linux-hardware.org/?probe=58ddf5337a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| Dell          | Precision 5570              | [f00d32a04a](https://linux-hardware.org/?probe=f00d32a04a) | Sep 27, 2023 |
| Toshiba       | Satellite A200              | [6bdac98313](https://linux-hardware.org/?probe=6bdac98313) | Sep 27, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [9a3f695f09](https://linux-hardware.org/?probe=9a3f695f09) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [fb82c6e942](https://linux-hardware.org/?probe=fb82c6e942) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [c7ec123b46](https://linux-hardware.org/?probe=c7ec123b46) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | [d8c3afba9b](https://linux-hardware.org/?probe=d8c3afba9b) | Sep 26, 2023 |
| Valve         | Jupiter                     | [277f5aca9b](https://linux-hardware.org/?probe=277f5aca9b) | Sep 26, 2023 |
| Apple         | MacBookPro11,1              | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| ASUSTek       | X551CA                      | [1fdceb9309](https://linux-hardware.org/?probe=1fdceb9309) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [47d912c5a9](https://linux-hardware.org/?probe=47d912c5a9) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [d2a926c703](https://linux-hardware.org/?probe=d2a926c703) | Sep 26, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [2568280c44](https://linux-hardware.org/?probe=2568280c44) | Sep 25, 2023 |
| Valve         | Jupiter                     | [7a64b4c44f](https://linux-hardware.org/?probe=7a64b4c44f) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 20HMS0EXOO    | [0818b5e737](https://linux-hardware.org/?probe=0818b5e737) | Sep 24, 2023 |
| HP            | ProBook 6545b               | [b0abb62083](https://linux-hardware.org/?probe=b0abb62083) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| Toshiba       | Satellite L50D-B            | [8b5b196475](https://linux-hardware.org/?probe=8b5b196475) | Sep 24, 2023 |
| Toshiba       | Satellite L50D-B            | [65d749c96e](https://linux-hardware.org/?probe=65d749c96e) | Sep 23, 2023 |
| Dell          | Inspiron 1564               | [f4232cfca8](https://linux-hardware.org/?probe=f4232cfca8) | Sep 23, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [083c0510ac](https://linux-hardware.org/?probe=083c0510ac) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d3322d740d](https://linux-hardware.org/?probe=d3322d740d) | Sep 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [13a9f1d65a](https://linux-hardware.org/?probe=13a9f1d65a) | Sep 23, 2023 |
| Dell          | Inspiron 1564               | [c84457748d](https://linux-hardware.org/?probe=c84457748d) | Sep 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [d464d79df3](https://linux-hardware.org/?probe=d464d79df3) | Sep 23, 2023 |
| HP            | Pavilion g6                 | [c49107d782](https://linux-hardware.org/?probe=c49107d782) | Sep 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [e63d1ae740](https://linux-hardware.org/?probe=e63d1ae740) | Sep 22, 2023 |
| Dell          | XPS 15 9560                 | [a437fe8bcf](https://linux-hardware.org/?probe=a437fe8bcf) | Sep 21, 2023 |
| Toshiba       | Satellite L855              | [ee1cb0c5cc](https://linux-hardware.org/?probe=ee1cb0c5cc) | Sep 21, 2023 |
| ASUSTek       | X550CL                      | [6c2de2dfb8](https://linux-hardware.org/?probe=6c2de2dfb8) | Sep 21, 2023 |
| PC Special... | Ionico 16                   | [dd18901106](https://linux-hardware.org/?probe=dd18901106) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | [2bb7ed1454](https://linux-hardware.org/?probe=2bb7ed1454) | Sep 21, 2023 |
| ASUSTek       | X501A                       | [5045eb238f](https://linux-hardware.org/?probe=5045eb238f) | Sep 20, 2023 |
| Acer          | Swift SF314-512             | [5c5a2a36e2](https://linux-hardware.org/?probe=5c5a2a36e2) | Sep 20, 2023 |
| HP            | EliteBook 845 14 inch G9... | [35d24c31cf](https://linux-hardware.org/?probe=35d24c31cf) | Sep 20, 2023 |
| Apple         | MacBook4,1                  | [3434dd8b54](https://linux-hardware.org/?probe=3434dd8b54) | Sep 20, 2023 |
| ASUSTek       | K52F                        | [8d4b7a978b](https://linux-hardware.org/?probe=8d4b7a978b) | Sep 19, 2023 |
| Dell          | Precision 5550              | [a1c163a7e2](https://linux-hardware.org/?probe=a1c163a7e2) | Sep 19, 2023 |
| Mini PC       | Cherry Trail CR             | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| ASUSTek       | X550CL                      | [2d5c5ab820](https://linux-hardware.org/?probe=2d5c5ab820) | Sep 19, 2023 |
| Valve         | Jupiter                     | [7baec97424](https://linux-hardware.org/?probe=7baec97424) | Sep 19, 2023 |
| HP            | Pavilion dv7                | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| Lenovo        | ThinkPad T430 2349BG6       | [dbd8f7715f](https://linux-hardware.org/?probe=dbd8f7715f) | Sep 19, 2023 |
| Dell          | Precision 3581              | [e1c8eb2810](https://linux-hardware.org/?probe=e1c8eb2810) | Sep 18, 2023 |
| Apple         | MacBookPro5,4               | [f2d4f47a8e](https://linux-hardware.org/?probe=f2d4f47a8e) | Sep 18, 2023 |
| Unknown       | M17PRO                      | [ccf362f14d](https://linux-hardware.org/?probe=ccf362f14d) | Sep 17, 2023 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [612bda7c21](https://linux-hardware.org/?probe=612bda7c21) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| HP            | EliteBook 820 G4            | [a16a2ef714](https://linux-hardware.org/?probe=a16a2ef714) | Sep 16, 2023 |
| MSI           | GS43VR 7RE                  | [d9893a35c8](https://linux-hardware.org/?probe=d9893a35c8) | Sep 16, 2023 |
| Acer          | Aspire 5720                 | [9bfcaaa71a](https://linux-hardware.org/?probe=9bfcaaa71a) | Sep 16, 2023 |
| Acer          | Aspire 5720                 | [bad46323d7](https://linux-hardware.org/?probe=bad46323d7) | Sep 16, 2023 |
| Dell          | XPS 9320                    | [99fce2103f](https://linux-hardware.org/?probe=99fce2103f) | Sep 16, 2023 |
| HP            | Compaq 6820s                | [99a625283d](https://linux-hardware.org/?probe=99a625283d) | Sep 16, 2023 |
| HP            | Compaq 6820s                | [2ae8b9ac9d](https://linux-hardware.org/?probe=2ae8b9ac9d) | Sep 16, 2023 |
| Dell          | Latitude E5570              | [fd5ba4aa5a](https://linux-hardware.org/?probe=fd5ba4aa5a) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | [2073aca95d](https://linux-hardware.org/?probe=2073aca95d) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | [fa484cf261](https://linux-hardware.org/?probe=fa484cf261) | Sep 15, 2023 |
| Dell          | XPS 15 9560                 | [c1f02dd477](https://linux-hardware.org/?probe=c1f02dd477) | Sep 15, 2023 |
| Dell          | XPS 9320                    | [054584d248](https://linux-hardware.org/?probe=054584d248) | Sep 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [982f29b6cc](https://linux-hardware.org/?probe=982f29b6cc) | Sep 14, 2023 |
| Clevo         | P170EM                      | [ee87854652](https://linux-hardware.org/?probe=ee87854652) | Sep 14, 2023 |
| Dell          | Precision 7530              | [035a4eb568](https://linux-hardware.org/?probe=035a4eb568) | Sep 14, 2023 |
| Dell          | Latitude 7390               | [4d8e0cb72b](https://linux-hardware.org/?probe=4d8e0cb72b) | Sep 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [aea796bbd9](https://linux-hardware.org/?probe=aea796bbd9) | Sep 14, 2023 |
| Acer          | AOA150                      | [bc32c4814d](https://linux-hardware.org/?probe=bc32c4814d) | Sep 13, 2023 |
| Dell          | Latitude 7390               | [2afdbd653c](https://linux-hardware.org/?probe=2afdbd653c) | Sep 13, 2023 |
| HP            | Compaq 6730b (NN204ET#AB... | [255f6ba979](https://linux-hardware.org/?probe=255f6ba979) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3831230caa](https://linux-hardware.org/?probe=3831230caa) | Sep 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f24f476710](https://linux-hardware.org/?probe=f24f476710) | Sep 11, 2023 |
| HP            | Pavilion Notebook           | [e4a14b2349](https://linux-hardware.org/?probe=e4a14b2349) | Sep 11, 2023 |
| ASUSTek       | N551JX                      | [8c034b254e](https://linux-hardware.org/?probe=8c034b254e) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [36c9a9e4d4](https://linux-hardware.org/?probe=36c9a9e4d4) | Sep 10, 2023 |
| HP            | 255 G7 Notebook PC          | [c5be1f9523](https://linux-hardware.org/?probe=c5be1f9523) | Sep 10, 2023 |
| Google        | Lillipup                    | [c3a892cdca](https://linux-hardware.org/?probe=c3a892cdca) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [3021f551f4](https://linux-hardware.org/?probe=3021f551f4) | Sep 09, 2023 |
| Valve         | Jupiter                     | [249a085da0](https://linux-hardware.org/?probe=249a085da0) | Sep 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [a03aa3f52d](https://linux-hardware.org/?probe=a03aa3f52d) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fd38d07a69](https://linux-hardware.org/?probe=fd38d07a69) | Sep 08, 2023 |
| Apple         | MacBookPro10,1              | [81aab795b5](https://linux-hardware.org/?probe=81aab795b5) | Sep 08, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [6870581b7c](https://linux-hardware.org/?probe=6870581b7c) | Sep 08, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [2614f063f8](https://linux-hardware.org/?probe=2614f063f8) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4fd02051b6](https://linux-hardware.org/?probe=4fd02051b6) | Sep 07, 2023 |
| Unknown       | Unknown                     | [16cb5e0d5b](https://linux-hardware.org/?probe=16cb5e0d5b) | Sep 06, 2023 |
| eMachines     | eM350                       | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 20MD0014UK      | [428c816118](https://linux-hardware.org/?probe=428c816118) | Sep 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | [f24dc99222](https://linux-hardware.org/?probe=f24dc99222) | Sep 06, 2023 |
| Sony          | SVF1521A7EB                 | [8b130feb09](https://linux-hardware.org/?probe=8b130feb09) | Sep 06, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [57764e02db](https://linux-hardware.org/?probe=57764e02db) | Sep 06, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [8b44f9cbdc](https://linux-hardware.org/?probe=8b44f9cbdc) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [f50ce96f55](https://linux-hardware.org/?probe=f50ce96f55) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [cd1be324d4](https://linux-hardware.org/?probe=cd1be324d4) | Sep 05, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | [6ab6bec7be](https://linux-hardware.org/?probe=6ab6bec7be) | Sep 05, 2023 |
| Notebook      | NL5xNU                      | [306dab3d42](https://linux-hardware.org/?probe=306dab3d42) | Sep 05, 2023 |
| HUAWEI        | NBD-WXX9                    | [005ebd39ce](https://linux-hardware.org/?probe=005ebd39ce) | Sep 05, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| HP            | Compaq 6730b (NN204ET#AB... | [7165368bfe](https://linux-hardware.org/?probe=7165368bfe) | Sep 04, 2023 |
| Dell          | Inspiron 5770               | [1f2c94fe31](https://linux-hardware.org/?probe=1f2c94fe31) | Sep 03, 2023 |
| Dell          | XPS 17 9700                 | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| Dell          | G15 5511                    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS24300    | [a28d4357d8](https://linux-hardware.org/?probe=a28d4357d8) | Sep 03, 2023 |
| Dell          | Latitude E6410              | [23f9814b2b](https://linux-hardware.org/?probe=23f9814b2b) | Sep 03, 2023 |
| Dell          | Studio 1735                 | [88cf1723e0](https://linux-hardware.org/?probe=88cf1723e0) | Sep 03, 2023 |
| Framework     | Laptop                      | [d153316fdd](https://linux-hardware.org/?probe=d153316fdd) | Sep 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [024e3beca4](https://linux-hardware.org/?probe=024e3beca4) | Sep 03, 2023 |
| Timi          | TM1613                      | [6acee9a858](https://linux-hardware.org/?probe=6acee9a858) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0f8242693](https://linux-hardware.org/?probe=e0f8242693) | Sep 02, 2023 |
| Dell          | Vostro 3590                 | [9a914c816e](https://linux-hardware.org/?probe=9a914c816e) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| ASUSTek       | UX305CA                     | [2220cac066](https://linux-hardware.org/?probe=2220cac066) | Sep 01, 2023 |
| HUAWEI        | MACH-WX9                    | [6f761aa23b](https://linux-hardware.org/?probe=6f761aa23b) | Aug 31, 2023 |
| Dell          | XPS 15 9560                 | [cef6754cd9](https://linux-hardware.org/?probe=cef6754cd9) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | [aad9baafe2](https://linux-hardware.org/?probe=aad9baafe2) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | [86b1c6ecfa](https://linux-hardware.org/?probe=86b1c6ecfa) | Aug 30, 2023 |
| ASUSTek       | S500CA                      | [60d87bd79b](https://linux-hardware.org/?probe=60d87bd79b) | Aug 30, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [18f51f883e](https://linux-hardware.org/?probe=18f51f883e) | Aug 30, 2023 |
| Lenovo        | ThinkPad X200 7459BN8       | [38c0341384](https://linux-hardware.org/?probe=38c0341384) | Aug 30, 2023 |
| Dell          | XPS 15 9560                 | [a31df2b8fe](https://linux-hardware.org/?probe=a31df2b8fe) | Aug 30, 2023 |
| Dell          | Latitude 5290               | [0b4debc293](https://linux-hardware.org/?probe=0b4debc293) | Aug 30, 2023 |
| Lenovo        | G500 20236                  | [93f309e8ad](https://linux-hardware.org/?probe=93f309e8ad) | Aug 29, 2023 |
| Acer          | Aspire 5720                 | [36403a156e](https://linux-hardware.org/?probe=36403a156e) | Aug 29, 2023 |
| Dell          | Latitude 3190               | [7d8714663f](https://linux-hardware.org/?probe=7d8714663f) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [704a62ef33](https://linux-hardware.org/?probe=704a62ef33) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [beb1174dde](https://linux-hardware.org/?probe=beb1174dde) | Aug 29, 2023 |
| Dell          | XPS 15 9500                 | [74ad31c9de](https://linux-hardware.org/?probe=74ad31c9de) | Aug 29, 2023 |
| Acer          | Aspire V5-471               | [c5d2dabe27](https://linux-hardware.org/?probe=c5d2dabe27) | Aug 28, 2023 |
| Toshiba       | Satellite C55D-A-14W        | [9f725ce1a7](https://linux-hardware.org/?probe=9f725ce1a7) | Aug 28, 2023 |
| Apple         | MacBookPro5,1               | [62464b6b0d](https://linux-hardware.org/?probe=62464b6b0d) | Aug 28, 2023 |
| Toshiba       | Satellite C55D-A-14W        | [c091e0bc8b](https://linux-hardware.org/?probe=c091e0bc8b) | Aug 28, 2023 |
| Dell          | Latitude E7240              | [1eab9b5f8d](https://linux-hardware.org/?probe=1eab9b5f8d) | Aug 28, 2023 |
| Valve         | Jupiter                     | [8a68ffe7b0](https://linux-hardware.org/?probe=8a68ffe7b0) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| Dell          | Latitude 7480               | [95f7cd5046](https://linux-hardware.org/?probe=95f7cd5046) | Aug 27, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| Dell          | Latitude E6420              | [1e2c15f171](https://linux-hardware.org/?probe=1e2c15f171) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Studio 1737                 | [8e668fe167](https://linux-hardware.org/?probe=8e668fe167) | Aug 27, 2023 |
| ZOOSTORM      | 7200-9062A                  | [5ee843d3d1](https://linux-hardware.org/?probe=5ee843d3d1) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Dell          | Precision M6800             | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| Acer          | Aspire V5-571               | [033994cebf](https://linux-hardware.org/?probe=033994cebf) | Aug 26, 2023 |
| Acer          | Aspire A515-56              | [53b787dc90](https://linux-hardware.org/?probe=53b787dc90) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [83695164cc](https://linux-hardware.org/?probe=83695164cc) | Aug 26, 2023 |
| Unknown       | Unknown                     | [dc1c907cda](https://linux-hardware.org/?probe=dc1c907cda) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [ee4e04964c](https://linux-hardware.org/?probe=ee4e04964c) | Aug 26, 2023 |
| Acer          | Aspire V3-571               | [376d5e8a22](https://linux-hardware.org/?probe=376d5e8a22) | Aug 25, 2023 |
| HUAWEI        | MACHR-WX9                   | [a8c4ca7aee](https://linux-hardware.org/?probe=a8c4ca7aee) | Aug 25, 2023 |
| Packard Be... | EasyNote TJ66               | [010fe56f65](https://linux-hardware.org/?probe=010fe56f65) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7355715562](https://linux-hardware.org/?probe=7355715562) | Aug 25, 2023 |
| Notebook      | NL5xNU                      | [116561b889](https://linux-hardware.org/?probe=116561b889) | Aug 25, 2023 |
| Lenovo        | ThinkPad T430 2349KAG       | [f2348b8eee](https://linux-hardware.org/?probe=f2348b8eee) | Aug 25, 2023 |
| PC Special... | Ionico 16                   | [78125c34b4](https://linux-hardware.org/?probe=78125c34b4) | Aug 25, 2023 |
| Sony          | SVF15A1M2ES                 | [b352453232](https://linux-hardware.org/?probe=b352453232) | Aug 24, 2023 |
| Google        | Eldrid                      | [e451d840cf](https://linux-hardware.org/?probe=e451d840cf) | Aug 24, 2023 |
| Valve         | Jupiter                     | [98dce455d0](https://linux-hardware.org/?probe=98dce455d0) | Aug 24, 2023 |
| HP            | Laptop 17-cn0xxx            | [5b5a4fa5d9](https://linux-hardware.org/?probe=5b5a4fa5d9) | Aug 23, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [adda6295fb](https://linux-hardware.org/?probe=adda6295fb) | Aug 23, 2023 |
| Acer          | AOD255                      | [06c6346db1](https://linux-hardware.org/?probe=06c6346db1) | Aug 23, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | [0005c7836c](https://linux-hardware.org/?probe=0005c7836c) | Aug 22, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| Acer          | Swift SF314-512             | [fce52ede18](https://linux-hardware.org/?probe=fce52ede18) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [f35c644052](https://linux-hardware.org/?probe=f35c644052) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [4f4bed768e](https://linux-hardware.org/?probe=4f4bed768e) | Aug 22, 2023 |
| Acer          | Swift SF314-512             | [9cd3fa37a0](https://linux-hardware.org/?probe=9cd3fa37a0) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [62cddb0954](https://linux-hardware.org/?probe=62cddb0954) | Aug 21, 2023 |
| Medion        | Akoya THE TOUCH 10          | [c121ae9a76](https://linux-hardware.org/?probe=c121ae9a76) | Aug 21, 2023 |
| Apple         | MacBookPro14,1              | [dc96aa9cee](https://linux-hardware.org/?probe=dc96aa9cee) | Aug 19, 2023 |
| Dell          | XPS 15 9550                 | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | [97a87f1178](https://linux-hardware.org/?probe=97a87f1178) | Aug 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS5W000    | [cb1eebf517](https://linux-hardware.org/?probe=cb1eebf517) | Aug 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS5W000    | [87d16e9431](https://linux-hardware.org/?probe=87d16e9431) | Aug 19, 2023 |
| Timi          | RedmiBook Pro 14S           | [323664ecb8](https://linux-hardware.org/?probe=323664ecb8) | Aug 18, 2023 |
| Acer          | Swift SF514-52T             | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | [c9e9e56ddd](https://linux-hardware.org/?probe=c9e9e56ddd) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| Dell          | XPS 15 9530                 | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c647987aaf](https://linux-hardware.org/?probe=c647987aaf) | Aug 16, 2023 |
| Dell          | Inspiron 7370               | [2676762739](https://linux-hardware.org/?probe=2676762739) | Aug 16, 2023 |
| Acer          | Aspire V5-571               | [bb39a5a125](https://linux-hardware.org/?probe=bb39a5a125) | Aug 15, 2023 |
| MSI           | GP62 6QF                    | [d9455cbed8](https://linux-hardware.org/?probe=d9455cbed8) | Aug 15, 2023 |
| Sony          | VPCEH3N6E                   | [884688ddbf](https://linux-hardware.org/?probe=884688ddbf) | Aug 15, 2023 |
| Samsung       | 755XDA                      | [3be32e2365](https://linux-hardware.org/?probe=3be32e2365) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Google        | Bobba360                    | [e2ae1afdcc](https://linux-hardware.org/?probe=e2ae1afdcc) | Aug 14, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [fe4612b027](https://linux-hardware.org/?probe=fe4612b027) | Aug 14, 2023 |
| Google        | Bobba360                    | [f211501fde](https://linux-hardware.org/?probe=f211501fde) | Aug 14, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c822a4c96f](https://linux-hardware.org/?probe=c822a4c96f) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [9db2ba151b](https://linux-hardware.org/?probe=9db2ba151b) | Aug 13, 2023 |
| Dell          | XPS 15 9560                 | [2461c78ff0](https://linux-hardware.org/?probe=2461c78ff0) | Aug 13, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [cd8b4a2836](https://linux-hardware.org/?probe=cd8b4a2836) | Aug 13, 2023 |
| HP            | Pavilion dv5                | [78530d4418](https://linux-hardware.org/?probe=78530d4418) | Aug 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS3320C    | [51f9e0c482](https://linux-hardware.org/?probe=51f9e0c482) | Aug 13, 2023 |
| Toshiba       | Satellite C50D-A-13G        | [e1a3542078](https://linux-hardware.org/?probe=e1a3542078) | Aug 12, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [411b9f412c](https://linux-hardware.org/?probe=411b9f412c) | Aug 12, 2023 |
| Timi          | RedmiBook Pro 15S           | [20559d710a](https://linux-hardware.org/?probe=20559d710a) | Aug 12, 2023 |
| Acer          | Aspire A317-53              | [17dacd99a6](https://linux-hardware.org/?probe=17dacd99a6) | Aug 12, 2023 |
| HP            | Pavilion dv5                | [41c7682f98](https://linux-hardware.org/?probe=41c7682f98) | Aug 11, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [abaa0512b0](https://linux-hardware.org/?probe=abaa0512b0) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [a8f62e42dc](https://linux-hardware.org/?probe=a8f62e42dc) | Aug 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [83a0a8a2aa](https://linux-hardware.org/?probe=83a0a8a2aa) | Aug 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [f062831bd7](https://linux-hardware.org/?probe=f062831bd7) | Aug 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | [e45562b838](https://linux-hardware.org/?probe=e45562b838) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [24629e2553](https://linux-hardware.org/?probe=24629e2553) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [6f422f386f](https://linux-hardware.org/?probe=6f422f386f) | Aug 10, 2023 |
| Gigabyte      | AERO 15-WA                  | [bd9f5d0f39](https://linux-hardware.org/?probe=bd9f5d0f39) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c87b299407](https://linux-hardware.org/?probe=c87b299407) | Aug 10, 2023 |
| Acer          | Aspire A317-53              | [5a2d81b438](https://linux-hardware.org/?probe=5a2d81b438) | Aug 09, 2023 |
| Samsung       | N150P/N210P/N220P           | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Dell          | Inspiron 7537               | [61093a9af1](https://linux-hardware.org/?probe=61093a9af1) | Aug 08, 2023 |
| Dell          | Latitude D630               | [a57bb7cde1](https://linux-hardware.org/?probe=a57bb7cde1) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | [6165a2d50e](https://linux-hardware.org/?probe=6165a2d50e) | Aug 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [6738a625d8](https://linux-hardware.org/?probe=6738a625d8) | Aug 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [66488bdd81](https://linux-hardware.org/?probe=66488bdd81) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5babb790d3](https://linux-hardware.org/?probe=5babb790d3) | Aug 08, 2023 |
| Acer          | Aspire 1825PTZ              | [553d2539fa](https://linux-hardware.org/?probe=553d2539fa) | Aug 07, 2023 |
| Acer          | Aspire A515-56              | [84b0c88b0a](https://linux-hardware.org/?probe=84b0c88b0a) | Aug 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [de8e0fbde8](https://linux-hardware.org/?probe=de8e0fbde8) | Aug 07, 2023 |
| HP            | Laptop 15-da0xxx            | [0cb4da66e3](https://linux-hardware.org/?probe=0cb4da66e3) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [b4b049b997](https://linux-hardware.org/?probe=b4b049b997) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8633bc5aa5](https://linux-hardware.org/?probe=8633bc5aa5) | Aug 07, 2023 |
| Dell          | Latitude 5411               | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | [3e9ce860b6](https://linux-hardware.org/?probe=3e9ce860b6) | Aug 07, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [053d461635](https://linux-hardware.org/?probe=053d461635) | Aug 06, 2023 |
| Unknown       | Unknown                     | [691c44286e](https://linux-hardware.org/?probe=691c44286e) | Aug 06, 2023 |
| Acer          | Aspire A515-56              | [dfe905b869](https://linux-hardware.org/?probe=dfe905b869) | Aug 06, 2023 |
| Acer          | Aspire A317-53              | [5bb0feab0c](https://linux-hardware.org/?probe=5bb0feab0c) | Aug 06, 2023 |
| Dell          | Latitude 5590               | [83d389e795](https://linux-hardware.org/?probe=83d389e795) | Aug 06, 2023 |
| Dell          | Venue 8 Pro 5855            | [146fa40942](https://linux-hardware.org/?probe=146fa40942) | Aug 05, 2023 |
| Lenovo        | 100w Gen 3 82HY             | [3feb7899d2](https://linux-hardware.org/?probe=3feb7899d2) | Aug 05, 2023 |
| GPD           | G1621-02                    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| HP            | 470 G7 Notebook PC          | [7e4a9b4618](https://linux-hardware.org/?probe=7e4a9b4618) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [a9072f3117](https://linux-hardware.org/?probe=a9072f3117) | Aug 04, 2023 |
| HP            | 255 G3                      | [c8b3db6b0b](https://linux-hardware.org/?probe=c8b3db6b0b) | Aug 03, 2023 |
| Acer          | Aspire 7750G                | [71f5ef03f9](https://linux-hardware.org/?probe=71f5ef03f9) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| Valve         | Jupiter                     | [f928feaff9](https://linux-hardware.org/?probe=f928feaff9) | Aug 02, 2023 |
| Toshiba       | Satellite C660              | [5e74aca4e7](https://linux-hardware.org/?probe=5e74aca4e7) | Aug 02, 2023 |
| HP            | Pavilion 15                 | [c66316cd62](https://linux-hardware.org/?probe=c66316cd62) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Acer          | Aspire A317-53              | [3f1af34e1b](https://linux-hardware.org/?probe=3f1af34e1b) | Aug 01, 2023 |
| HP            | Pavilion 15                 | [1ad3dc2f1b](https://linux-hardware.org/?probe=1ad3dc2f1b) | Aug 01, 2023 |
| Lenovo        | Flex 2-14 20404             | [dd24507513](https://linux-hardware.org/?probe=dd24507513) | Jul 31, 2023 |
| HP            | ProBook 4740s               | [d0aae87145](https://linux-hardware.org/?probe=d0aae87145) | Jul 31, 2023 |
| HP            | ProBook 4740s               | [985ee4b495](https://linux-hardware.org/?probe=985ee4b495) | Jul 30, 2023 |
| HP            | ProBook 430 G3              | [a42e1c787e](https://linux-hardware.org/?probe=a42e1c787e) | Jul 30, 2023 |
| Valve         | Jupiter                     | [82e4fa2fbc](https://linux-hardware.org/?probe=82e4fa2fbc) | Jul 30, 2023 |
| HP            | ENVY Notebook               | [3e13681e00](https://linux-hardware.org/?probe=3e13681e00) | Jul 29, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [dbcda8f4d0](https://linux-hardware.org/?probe=dbcda8f4d0) | Jul 29, 2023 |
| Razer         | Blade                       | [6c3ef3aa59](https://linux-hardware.org/?probe=6c3ef3aa59) | Jul 29, 2023 |
| Dell          | Latitude E6420              | [a70852def5](https://linux-hardware.org/?probe=a70852def5) | Jul 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1N700    | [3486243fd6](https://linux-hardware.org/?probe=3486243fd6) | Jul 29, 2023 |
| Unknown       | Unknown                     | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| Dell          | XPS 9320                    | [4000df5584](https://linux-hardware.org/?probe=4000df5584) | Jul 29, 2023 |
| Valve         | Jupiter                     | [ff714f1791](https://linux-hardware.org/?probe=ff714f1791) | Jul 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [ba7c69f7e0](https://linux-hardware.org/?probe=ba7c69f7e0) | Jul 28, 2023 |
| Apple         | MacBookPro12,1              | [bc3cb3cbfd](https://linux-hardware.org/?probe=bc3cb3cbfd) | Jul 28, 2023 |
| Dell          | Latitude 3410               | [449e4c62f3](https://linux-hardware.org/?probe=449e4c62f3) | Jul 28, 2023 |
| Dell          | XPS 13 9380                 | [b784cbe3ab](https://linux-hardware.org/?probe=b784cbe3ab) | Jul 28, 2023 |
| Dell          | Inspiron 13-5378            | [cd318f6b75](https://linux-hardware.org/?probe=cd318f6b75) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e08f65110d](https://linux-hardware.org/?probe=e08f65110d) | Jul 27, 2023 |
| Acer          | Aspire A515-56              | [7c716b6ab0](https://linux-hardware.org/?probe=7c716b6ab0) | Jul 27, 2023 |
| HP            | Laptop 14s-fq1xxx           | [84ab2faa6f](https://linux-hardware.org/?probe=84ab2faa6f) | Jul 27, 2023 |
| PC Special... | Ionico 16                   | [5c91300246](https://linux-hardware.org/?probe=5c91300246) | Jul 26, 2023 |
| Dell          | Inspiron 13-5378            | [fd43074149](https://linux-hardware.org/?probe=fd43074149) | Jul 26, 2023 |
| Valve         | Jupiter                     | [1adda13639](https://linux-hardware.org/?probe=1adda13639) | Jul 26, 2023 |
| HP            | Laptop 14s-fq1xxx           | [ee10ac6c06](https://linux-hardware.org/?probe=ee10ac6c06) | Jul 26, 2023 |
| HP            | Notebook                    | [beef8e7fce](https://linux-hardware.org/?probe=beef8e7fce) | Jul 25, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| Dell          | Latitude 5530               | [cccd0bf0b8](https://linux-hardware.org/?probe=cccd0bf0b8) | Jul 25, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [6fc7661aae](https://linux-hardware.org/?probe=6fc7661aae) | Jul 25, 2023 |
| MSI           | Katana GF66 11UG            | [bd45023e8e](https://linux-hardware.org/?probe=bd45023e8e) | Jul 25, 2023 |
| Acer          | Swift SFE16-43              | [ada40722ae](https://linux-hardware.org/?probe=ada40722ae) | Jul 25, 2023 |
| Dell          | Vostro 1500                 | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [e46d04faa8](https://linux-hardware.org/?probe=e46d04faa8) | Jul 25, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [0b7f69aaf6](https://linux-hardware.org/?probe=0b7f69aaf6) | Jul 25, 2023 |
| Chuwi         | CoreBook Pro                | [21ab3832ea](https://linux-hardware.org/?probe=21ab3832ea) | Jul 24, 2023 |
| Dell          | Inspiron 5570               | [3d08e59ce3](https://linux-hardware.org/?probe=3d08e59ce3) | Jul 24, 2023 |
| Dell          | Latitude 2110               | [05a7868709](https://linux-hardware.org/?probe=05a7868709) | Jul 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8b89c63576](https://linux-hardware.org/?probe=8b89c63576) | Jul 24, 2023 |
| Gigabyte      | P17FR5                      | [817b78d77b](https://linux-hardware.org/?probe=817b78d77b) | Jul 23, 2023 |
| PC Special... | Standard                    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| HP            | Notebook                    | [4746f66332](https://linux-hardware.org/?probe=4746f66332) | Jul 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [ff5e295a5d](https://linux-hardware.org/?probe=ff5e295a5d) | Jul 23, 2023 |
| HP            | 255 G6 Notebook PC          | [5c5147b82d](https://linux-hardware.org/?probe=5c5147b82d) | Jul 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS1N700    | [e42f9111c6](https://linux-hardware.org/?probe=e42f9111c6) | Jul 23, 2023 |
| Dell          | XPS 15 9570                 | [9a62fe1979](https://linux-hardware.org/?probe=9a62fe1979) | Jul 22, 2023 |
| Valve         | Jupiter                     | [0e8e6ce1ae](https://linux-hardware.org/?probe=0e8e6ce1ae) | Jul 22, 2023 |
| Valve         | Jupiter                     | [fa8db9f24a](https://linux-hardware.org/?probe=fa8db9f24a) | Jul 22, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [c06811057a](https://linux-hardware.org/?probe=c06811057a) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| Dell          | System XPS L702X            | [21f1d68bc1](https://linux-hardware.org/?probe=21f1d68bc1) | Jul 21, 2023 |
| Apple         | MacBookAir7,1               | [e82f5072df](https://linux-hardware.org/?probe=e82f5072df) | Jul 20, 2023 |
| Dell          | Vostro 1500                 | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Acer          | Aspire A317-53              | [d8e84157ab](https://linux-hardware.org/?probe=d8e84157ab) | Jul 20, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e0b92a00b5](https://linux-hardware.org/?probe=e0b92a00b5) | Jul 19, 2023 |
| Dell          | Inspiron N5110              | [140474e198](https://linux-hardware.org/?probe=140474e198) | Jul 19, 2023 |
| Lenovo        | ThinkPad E560 20EV000YUK    | [0e89144534](https://linux-hardware.org/?probe=0e89144534) | Jul 19, 2023 |
| Dell          | XPS 15 9570                 | [e6cf0622b0](https://linux-hardware.org/?probe=e6cf0622b0) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [a4584a139f](https://linux-hardware.org/?probe=a4584a139f) | Jul 19, 2023 |
| HP            | Laptop 15-dw0xxx            | [ba24f3bb61](https://linux-hardware.org/?probe=ba24f3bb61) | Jul 18, 2023 |
| Valve         | Jupiter                     | [3abdfed88b](https://linux-hardware.org/?probe=3abdfed88b) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| Valve         | Jupiter                     | [4beb3117df](https://linux-hardware.org/?probe=4beb3117df) | Jul 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [a448a20876](https://linux-hardware.org/?probe=a448a20876) | Jul 17, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [958f57fd27](https://linux-hardware.org/?probe=958f57fd27) | Jul 17, 2023 |
| Sony          | VGN-S3HP                    | [6e2c92c447](https://linux-hardware.org/?probe=6e2c92c447) | Jul 17, 2023 |
| Dell          | Precision M6800             | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [3a7fbf07fa](https://linux-hardware.org/?probe=3a7fbf07fa) | Jul 17, 2023 |
| Dell          | Inspiron 1501               | [a79d62db7c](https://linux-hardware.org/?probe=a79d62db7c) | Jul 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [ec4db25eb9](https://linux-hardware.org/?probe=ec4db25eb9) | Jul 16, 2023 |
| Acer          | Aspire A317-53              | [9dd235116d](https://linux-hardware.org/?probe=9dd235116d) | Jul 16, 2023 |
| Dell          | G5 5587                     | [fc861c593a](https://linux-hardware.org/?probe=fc861c593a) | Jul 16, 2023 |
| Acer          | Predator PH315-52           | [8231c1b7c0](https://linux-hardware.org/?probe=8231c1b7c0) | Jul 16, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [8977d2e0a3](https://linux-hardware.org/?probe=8977d2e0a3) | Jul 16, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [35f3837811](https://linux-hardware.org/?probe=35f3837811) | Jul 16, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Acer          | Aspire A315-32              | [7044de848c](https://linux-hardware.org/?probe=7044de848c) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | [bcd1c01ad6](https://linux-hardware.org/?probe=bcd1c01ad6) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | [390008fe3c](https://linux-hardware.org/?probe=390008fe3c) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| HP            | Pavilion 15                 | [95f81cdf21](https://linux-hardware.org/?probe=95f81cdf21) | Jul 15, 2023 |
| Dell          | G15 5510                    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| Lenovo        | ThinkPad T530 2429HD6       | [1c48702f3c](https://linux-hardware.org/?probe=1c48702f3c) | Jul 14, 2023 |
| Dell          | XPS 13 9300                 | [ca425f6c38](https://linux-hardware.org/?probe=ca425f6c38) | Jul 14, 2023 |
| Lenovo        | ThinkPad X220 4290FC1       | [d6c0ccb8f1](https://linux-hardware.org/?probe=d6c0ccb8f1) | Jul 14, 2023 |
| Notebook      | N150ZU                      | [61be22ac36](https://linux-hardware.org/?probe=61be22ac36) | Jul 14, 2023 |
| Dell          | Inspiron 15 3520            | [163766c886](https://linux-hardware.org/?probe=163766c886) | Jul 14, 2023 |
| Acer          | Swift SF313-52              | [3b393fc916](https://linux-hardware.org/?probe=3b393fc916) | Jul 14, 2023 |
| Google        | Droid                       | [9b77a9ba04](https://linux-hardware.org/?probe=9b77a9ba04) | Jul 14, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | [4df76c784c](https://linux-hardware.org/?probe=4df76c784c) | Jul 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | [4b9cba03ac](https://linux-hardware.org/?probe=4b9cba03ac) | Jul 13, 2023 |
| Dell          | XPS 17 9730                 | [b074a1deb3](https://linux-hardware.org/?probe=b074a1deb3) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS50T0Q    | [0d5f86f700](https://linux-hardware.org/?probe=0d5f86f700) | Jul 13, 2023 |
| MSI           | GT70 2PE                    | [9e49d96293](https://linux-hardware.org/?probe=9e49d96293) | Jul 13, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd2c7b0c60](https://linux-hardware.org/?probe=dd2c7b0c60) | Jul 12, 2023 |
| Google        | Lillipup                    | [b7b430e7b4](https://linux-hardware.org/?probe=b7b430e7b4) | Jul 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [15067533b3](https://linux-hardware.org/?probe=15067533b3) | Jul 12, 2023 |
| HP            | EliteBook Folio 1040 G3     | [95c073864d](https://linux-hardware.org/?probe=95c073864d) | Jul 12, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ad18a95d12](https://linux-hardware.org/?probe=ad18a95d12) | Jul 12, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9479004a7e](https://linux-hardware.org/?probe=9479004a7e) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | [ad75f0a6e0](https://linux-hardware.org/?probe=ad75f0a6e0) | Jul 12, 2023 |
| Dell          | XPS 15 9530                 | [d78fb6bdd4](https://linux-hardware.org/?probe=d78fb6bdd4) | Jul 12, 2023 |
| HP            | 630                         | [671710637c](https://linux-hardware.org/?probe=671710637c) | Jul 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [90466d16ca](https://linux-hardware.org/?probe=90466d16ca) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [08bbd89b8c](https://linux-hardware.org/?probe=08bbd89b8c) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [23b123605f](https://linux-hardware.org/?probe=23b123605f) | Jul 11, 2023 |
| Sony          | SVP1321M2EB                 | [e767bbc26b](https://linux-hardware.org/?probe=e767bbc26b) | Jul 11, 2023 |
| Sony          | VPCZ214GX                   | [d63fc5c563](https://linux-hardware.org/?probe=d63fc5c563) | Jul 11, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [56de408d31](https://linux-hardware.org/?probe=56de408d31) | Jul 10, 2023 |
| Valve         | Jupiter                     | [5d55bf223d](https://linux-hardware.org/?probe=5d55bf223d) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [96ca518dc6](https://linux-hardware.org/?probe=96ca518dc6) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| Apple         | MacBookPro10,1              | [43ec3cf70b](https://linux-hardware.org/?probe=43ec3cf70b) | Jul 09, 2023 |
| Dell          | XPS 15 9530                 | [513a03f793](https://linux-hardware.org/?probe=513a03f793) | Jul 08, 2023 |
| Apple         | MacBookPro10,1              | [ef7acb569d](https://linux-hardware.org/?probe=ef7acb569d) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [ffde5244e6](https://linux-hardware.org/?probe=ffde5244e6) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [2e2541c7a6](https://linux-hardware.org/?probe=2e2541c7a6) | Jul 08, 2023 |
| Apple         | MacBookPro13,1              | [3a64eabd9b](https://linux-hardware.org/?probe=3a64eabd9b) | Jul 08, 2023 |
| Acer          | Aspire A315-54              | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Lenovo        | Flex 2-14 20404             | [93f50211c2](https://linux-hardware.org/?probe=93f50211c2) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [03f454349c](https://linux-hardware.org/?probe=03f454349c) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [e17ab8bbe7](https://linux-hardware.org/?probe=e17ab8bbe7) | Jul 06, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [bdc65d0c9f](https://linux-hardware.org/?probe=bdc65d0c9f) | Jul 05, 2023 |
| Lenovo        | ThinkPad T400 6474W7T       | [56144d66ac](https://linux-hardware.org/?probe=56144d66ac) | Jul 05, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [bb0e10ceef](https://linux-hardware.org/?probe=bb0e10ceef) | Jul 05, 2023 |
| MSI           | GF75 Thin 9SC               | [b180548e9c](https://linux-hardware.org/?probe=b180548e9c) | Jul 05, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [d5b720740f](https://linux-hardware.org/?probe=d5b720740f) | Jul 04, 2023 |
| Valve         | Jupiter                     | [8b40767026](https://linux-hardware.org/?probe=8b40767026) | Jul 04, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| HP            | EliteBook 2540p             | [d69b1af76b](https://linux-hardware.org/?probe=d69b1af76b) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | [9c8f32ac20](https://linux-hardware.org/?probe=9c8f32ac20) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | [6c32038385](https://linux-hardware.org/?probe=6c32038385) | Jul 02, 2023 |
| Dell          | G3 3779                     | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Teclast       | F15Plus 2                   | [29b2c807e6](https://linux-hardware.org/?probe=29b2c807e6) | Jul 01, 2023 |
| Alienware     | m16 R1 AMD                  | [291c477bd0](https://linux-hardware.org/?probe=291c477bd0) | Jul 01, 2023 |
| HP            | Stream Notebook PC 11       | [c1e18957a4](https://linux-hardware.org/?probe=c1e18957a4) | Jul 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [e9f511bc00](https://linux-hardware.org/?probe=e9f511bc00) | Jul 01, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [8f38634e0e](https://linux-hardware.org/?probe=8f38634e0e) | Jul 01, 2023 |
| lapbook       | S15 PRO                     | [06ae615fd1](https://linux-hardware.org/?probe=06ae615fd1) | Jul 01, 2023 |
| Toshiba       | Satellite Pro L650          | [d8da913f23](https://linux-hardware.org/?probe=d8da913f23) | Jul 01, 2023 |
| Teclast       | F15Plus 2                   | [4593b411f0](https://linux-hardware.org/?probe=4593b411f0) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | [6c8a67be9e](https://linux-hardware.org/?probe=6c8a67be9e) | Jun 30, 2023 |
| Valve         | Jupiter                     | [89d751f07f](https://linux-hardware.org/?probe=89d751f07f) | Jun 30, 2023 |
| HP            | Unknown                     | [0f4ae63ce0](https://linux-hardware.org/?probe=0f4ae63ce0) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | [703ae4bd0b](https://linux-hardware.org/?probe=703ae4bd0b) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | [bf3c982248](https://linux-hardware.org/?probe=bf3c982248) | Jun 30, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d058f48980](https://linux-hardware.org/?probe=d058f48980) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [93e0628fbe](https://linux-hardware.org/?probe=93e0628fbe) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| Google        | Reef                        | [221e64e148](https://linux-hardware.org/?probe=221e64e148) | Jun 29, 2023 |
| HP            | ProBook 450 G2              | [2b47aff042](https://linux-hardware.org/?probe=2b47aff042) | Jun 28, 2023 |
| Lenovo        | ThinkPad X240 20AL007LUK    | [ee0761a131](https://linux-hardware.org/?probe=ee0761a131) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| HP            | ProBook 450 G2              | [dc758ef355](https://linux-hardware.org/?probe=dc758ef355) | Jun 28, 2023 |
| MSI           | GE70 2PL                    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [9128946047](https://linux-hardware.org/?probe=9128946047) | Jun 27, 2023 |
| HP            | EliteBook 8440p             | [3d2a2196ae](https://linux-hardware.org/?probe=3d2a2196ae) | Jun 27, 2023 |
| Valve         | Jupiter                     | [f6d3a1e787](https://linux-hardware.org/?probe=f6d3a1e787) | Jun 27, 2023 |
| Dell          | Precision M6800             | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | [5e6365efcf](https://linux-hardware.org/?probe=5e6365efcf) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | [88baca047c](https://linux-hardware.org/?probe=88baca047c) | Jun 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Apple         | MacBook4,1                  | [fe27e643ac](https://linux-hardware.org/?probe=fe27e643ac) | Jun 26, 2023 |
| HP            | Unknown                     | [d681765bb7](https://linux-hardware.org/?probe=d681765bb7) | Jun 26, 2023 |
| Dell          | Precision M6800             | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| Acer          | Aspire A317-53              | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [75f62d2200](https://linux-hardware.org/?probe=75f62d2200) | Jun 24, 2023 |
| Toshiba       | Satellite C650              | [54ef5b6567](https://linux-hardware.org/?probe=54ef5b6567) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 554       | 11.75%  |
| Ubuntu 22.04       | 295       | 6.26%   |
| Ubuntu 18.04       | 279       | 5.92%   |
| Zorin 16           | 128       | 2.72%   |
| Pop!_OS 22.04      | 102       | 2.16%   |
| Arch Rolling       | 95        | 2.02%   |
| OpenMandriva 4.3   | 85        | 1.8%    |
| Debian 11          | 78        | 1.65%   |
| Fedora 38          | 70        | 1.48%   |
| Linux Mint 19.3    | 68        | 1.44%   |
| Manjaro            | 64        | 1.36%   |
| Ubuntu 19.04       | 62        | 1.32%   |
| ArcoLinux Rolling  | 62        | 1.32%   |
| Linux Mint 20.3    | 61        | 1.29%   |
| OpenMandriva 4.2   | 60        | 1.27%   |
| Linux Mint 21.1    | 59        | 1.25%   |
| Pop!_OS 20.04      | 55        | 1.17%   |
| Linux Mint 20.2    | 55        | 1.17%   |
| Arch               | 54        | 1.15%   |
| Ubuntu 20.10       | 53        | 1.12%   |
| Zorin 15           | 52        | 1.1%    |
| KDE neon 20.04     | 52        | 1.1%    |
| Ubuntu 21.10       | 51        | 1.08%   |
| Linux Mint 20.1    | 50        | 1.06%   |
| Ubuntu 19.10       | 49        | 1.04%   |
| Linux Mint 21.2    | 47        | 1%      |
| Pop!_OS 21.04      | 45        | 0.95%   |
| Ubuntu 21.04       | 44        | 0.93%   |
| OpenMandriva 23.01 | 44        | 0.93%   |
| Debian 12          | 42        | 0.89%   |
| OpenMandriva 23.03 | 41        | 0.87%   |
| Xubuntu 20.04      | 39        | 0.83%   |
| Fedora 39          | 38        | 0.81%   |
| Linux Mint 20      | 36        | 0.76%   |
| Pop!_OS 20.10      | 34        | 0.72%   |
| Fedora 37          | 34        | 0.72%   |
| Fedora 35          | 34        | 0.72%   |
| Pop!_OS 21.10      | 33        | 0.7%    |
| Fedora 36          | 33        | 0.7%    |
| Fedora 34          | 33        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1446      | 32.28%  |
| Linux Mint    | 420       | 9.38%   |
| Fedora        | 313       | 6.99%   |
| OpenMandriva  | 280       | 6.25%   |
| Pop!_OS       | 253       | 5.65%   |
| Zorin         | 193       | 4.31%   |
| Debian        | 152       | 3.39%   |
| Arch          | 147       | 3.28%   |
| Manjaro       | 140       | 3.13%   |
| SteamOS       | 119       | 2.66%   |
| Kubuntu       | 106       | 2.37%   |
| Xubuntu       | 96        | 2.14%   |
| KDE neon      | 79        | 1.76%   |
| ArcoLinux     | 66        | 1.47%   |
| Elementary    | 47        | 1.05%   |
| Lubuntu       | 44        | 0.98%   |
| openSUSE      | 38        | 0.85%   |
| ROSA          | 37        | 0.83%   |
| Ubuntu MATE   | 36        | 0.8%    |
| Kali          | 34        | 0.76%   |
| Gentoo        | 32        | 0.71%   |
| BlackPanther  | 32        | 0.71%   |
| Ubuntu Unity  | 29        | 0.65%   |
| Endless       | 29        | 0.65%   |
| EndeavourOS   | 25        | 0.56%   |
| MX            | 22        | 0.49%   |
| LMDE          | 21        | 0.47%   |
| Garuda Linux  | 19        | 0.42%   |
| Clear Linux   | 19        | 0.42%   |
| Ubuntu Budgie | 17        | 0.38%   |
| Parrot        | 17        | 0.38%   |
| Peppermint    | 14        | 0.31%   |
| Nobara        | 14        | 0.31%   |
| CentOS        | 11        | 0.25%   |
| NixOS         | 10        | 0.22%   |
| RHEL          | 9         | 0.2%    |
| Q4OS          | 5         | 0.11%   |
| PureOS        | 5         | 0.11%   |
| Oracle Linux  | 5         | 0.11%   |
| Linux Lite    | 5         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 79        | 1.52%   |
| 5.4.0-42-generic         | 77        | 1.48%   |
| 5.10.14-desktop-1omv4002 | 57        | 1.1%    |
| 5.15.0-56-generic        | 50        | 0.96%   |
| 5.13.0-valve36-1-neptune | 42        | 0.81%   |
| 6.2.6-desktop-1omv2390   | 41        | 0.79%   |
| 5.4.0-48-generic         | 40        | 0.77%   |
| 5.4.0-52-generic         | 39        | 0.75%   |
| 6.1.1-desktop-1omv2290   | 38        | 0.73%   |
| 5.15.0-58-generic        | 38        | 0.73%   |
| 5.15.0-52-generic        | 38        | 0.73%   |
| 5.4.0-29-generic         | 35        | 0.67%   |
| 5.3.0-40-generic         | 35        | 0.67%   |
| 5.11.0-27-generic        | 34        | 0.65%   |
| 5.4.0-26-generic         | 33        | 0.64%   |
| 5.3.0-28-generic         | 33        | 0.64%   |
| 5.15.0-46-generic        | 33        | 0.64%   |
| 5.4.0-58-generic         | 31        | 0.6%    |
| 5.4.0-40-generic         | 29        | 0.56%   |
| 5.0.0-32-generic         | 29        | 0.56%   |
| 5.11.0-38-generic        | 28        | 0.54%   |
| 6.4.11-desktop-1omv2390  | 27        | 0.52%   |
| 6.2.0-26-generic         | 27        | 0.52%   |
| 5.8.0-43-generic         | 25        | 0.48%   |
| 5.3.0-42-generic         | 25        | 0.48%   |
| 5.19.0-35-generic        | 25        | 0.48%   |
| 5.4.0-91-generic         | 24        | 0.46%   |
| 5.11.0-37-generic        | 24        | 0.46%   |
| 5.11.0-25-generic        | 24        | 0.46%   |
| 5.4.0-65-generic         | 23        | 0.44%   |
| 5.4.0-7634-generic       | 22        | 0.42%   |
| 5.4.0-33-generic         | 22        | 0.42%   |
| 5.13.0-7614-generic      | 22        | 0.42%   |
| 5.13.0-28-generic        | 22        | 0.42%   |
| 5.0.0-37-generic         | 22        | 0.42%   |
| 4.18.16-desktop-1bP      | 22        | 0.42%   |
| 6.5.0-14-generic         | 21        | 0.4%    |
| 5.8.0-50-generic         | 21        | 0.4%    |
| 5.8.0-44-generic         | 21        | 0.4%    |
| 5.4.0-56-generic         | 21        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 741       | 15.22%  |
| 5.15.0  | 477       | 9.8%    |
| 5.13.0  | 285       | 5.86%   |
| 5.11.0  | 243       | 4.99%   |
| 5.8.0   | 234       | 4.81%   |
| 5.3.0   | 204       | 4.19%   |
| 4.15.0  | 203       | 4.17%   |
| 5.19.0  | 158       | 3.25%   |
| 6.2.0   | 144       | 2.96%   |
| 5.0.0   | 137       | 2.81%   |
| 5.10.0  | 104       | 2.14%   |
| 4.18.0  | 93        | 1.91%   |
| 5.16.7  | 79        | 1.62%   |
| 6.2.6   | 64        | 1.31%   |
| 6.1.0   | 64        | 1.31%   |
| 6.5.0   | 62        | 1.27%   |
| 5.10.14 | 57        | 1.17%   |
| 6.1.1   | 39        | 0.8%    |
| 6.4.11  | 30        | 0.62%   |
| 4.19.0  | 30        | 0.62%   |
| 4.18.16 | 23        | 0.47%   |
| 6.5.6   | 20        | 0.41%   |
| 5.14.0  | 18        | 0.37%   |
| 6.1.52  | 17        | 0.35%   |
| 5.17.5  | 16        | 0.33%   |
| 6.0.6   | 15        | 0.31%   |
| 6.0.0   | 15        | 0.31%   |
| 6.2.9   | 14        | 0.29%   |
| 6.6.8   | 12        | 0.25%   |
| 6.5.5   | 12        | 0.25%   |
| 6.4.6   | 12        | 0.25%   |
| 6.4.12  | 12        | 0.25%   |
| 6.3.5   | 12        | 0.25%   |
| 6.0.12  | 12        | 0.25%   |
| 4.9.60  | 12        | 0.25%   |
| 5.17.1  | 11        | 0.23%   |
| 5.16.0  | 11        | 0.23%   |
| 6.6.7   | 10        | 0.21%   |
| 6.6.6   | 10        | 0.21%   |
| 6.6.2   | 10        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 777       | 16.12%  |
| 5.15    | 570       | 11.83%  |
| 5.13    | 325       | 6.74%   |
| 5.8     | 279       | 5.79%   |
| 5.11    | 267       | 5.54%   |
| 6.2     | 257       | 5.33%   |
| 5.3     | 228       | 4.73%   |
| 5.10    | 211       | 4.38%   |
| 4.15    | 204       | 4.23%   |
| 5.19    | 199       | 4.13%   |
| 6.1     | 195       | 4.05%   |
| 5.16    | 146       | 3.03%   |
| 5.0     | 144       | 2.99%   |
| 6.5     | 125       | 2.59%   |
| 4.18    | 118       | 2.45%   |
| 6.4     | 103       | 2.14%   |
| 6.0     | 79        | 1.64%   |
| 6.6     | 73        | 1.51%   |
| 5.17    | 58        | 1.2%    |
| 6.3     | 56        | 1.16%   |
| 5.14    | 55        | 1.14%   |
| 5.9     | 46        | 0.95%   |
| 4.19    | 46        | 0.95%   |
| 5.12    | 42        | 0.87%   |
| 5.6     | 40        | 0.83%   |
| 4.9     | 33        | 0.68%   |
| 5.18    | 32        | 0.66%   |
| 5.7     | 30        | 0.62%   |
| 5.5     | 19        | 0.39%   |
| 5.2     | 11        | 0.23%   |
| 4.4     | 11        | 0.23%   |
| 5.1     | 8         | 0.17%   |
| 6.7     | 7         | 0.15%   |
| 3.10    | 4         | 0.08%   |
| 4.20    | 3         | 0.06%   |
| 4.16    | 3         | 0.06%   |
| 4.14    | 3         | 0.06%   |
| 4.8     | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 4.1     | 2         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4197      | 97.22%  |
| i686    | 118       | 2.73%   |
| aarch64 | 2         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 2020      | 44.88%  |
| KDE5             | 821       | 18.24%  |
| Unknown          | 435       | 9.66%   |
| X-Cinnamon       | 344       | 7.64%   |
| XFCE             | 324       | 7.2%    |
| MATE             | 117       | 2.6%    |
| KDE              | 85        | 1.89%   |
| LXQt             | 50        | 1.11%   |
| Cinnamon         | 46        | 1.02%   |
| Pantheon         | 44        | 0.98%   |
| Unity            | 31        | 0.69%   |
| LXDE             | 29        | 0.64%   |
| Budgie           | 25        | 0.56%   |
| i3               | 22        | 0.49%   |
| GNOME Flashback  | 19        | 0.42%   |
| KDE4             | 14        | 0.31%   |
| Hyprland         | 13        | 0.29%   |
| sway             | 10        | 0.22%   |
| awesome          | 7         | 0.16%   |
| qtile            | 6         | 0.13%   |
| GNOME Classic    | 6         | 0.13%   |
| openbox          | 4         | 0.09%   |
| bspwm            | 4         | 0.09%   |
| xmonad           | 3         | 0.07%   |
| trinity          | 3         | 0.07%   |
| Deepin           | 3         | 0.07%   |
| Unicorn:XFCE     | 2         | 0.04%   |
| i3-with-shmlog   | 2         | 0.04%   |
| DWM              | 2         | 0.04%   |
| chadwm           | 2         | 0.04%   |
| BunsenLabs       | 2         | 0.04%   |
| mwm              | 1         | 0.02%   |
| lightdm-xsession | 1         | 0.02%   |
| Hypr             | 1         | 0.02%   |
| GNUstep          | 1         | 0.02%   |
| Enlightenment    | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3276      | 73.83%  |
| Wayland | 868       | 19.56%  |
| Unknown | 240       | 5.41%   |
| Tty     | 53        | 1.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2282      | 50.84%  |
| SDDM    | 650       | 14.48%  |
| GDM3    | 525       | 11.7%   |
| GDM     | 476       | 10.6%   |
| LightDM | 418       | 9.31%   |
| TDM     | 101       | 2.25%   |
| KDM     | 15        | 0.33%   |
| XDM     | 6         | 0.13%   |
| LXDM    | 6         | 0.13%   |
| Ly      | 4         | 0.09%   |
| GREETD  | 2         | 0.04%   |
| SLiM    | 1         | 0.02%   |
| NODM    | 1         | 0.02%   |
| LY-DM   | 1         | 0.02%   |
| CDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| en_GB          | 3191      | 72.13%  |
| en_US          | 595       | 13.45%  |
| Unknown        | 421       | 9.52%   |
| C              | 65        | 1.47%   |
| pl_PL          | 44        | 0.99%   |
| de_DE          | 10        | 0.23%   |
| fr_FR          | 9         | 0.2%    |
| ru_RU          | 8         | 0.18%   |
| en_AU          | 8         | 0.18%   |
| it_IT          | 7         | 0.16%   |
| en_CA          | 7         | 0.16%   |
| POSIX          | 6         | 0.14%   |
| es_ES          | 6         | 0.14%   |
| en_IN          | 5         | 0.11%   |
| en_IE          | 5         | 0.11%   |
| cs_CZ          | 5         | 0.11%   |
| hu_HU          | 4         | 0.09%   |
| zh_CN          | 3         | 0.07%   |
| ro_RO          | 3         | 0.07%   |
| uk_UA          | 2         | 0.05%   |
| sk_SK          | 2         | 0.05%   |
| pt_PT          | 2         | 0.05%   |
| pt_BR          | 2         | 0.05%   |
| tr_TR          | 1         | 0.02%   |
| nl_BE          | 1         | 0.02%   |
| en_US.utf-8    | 1         | 0.02%   |
| en_NZ          | 1         | 0.02%   |
| en_IL          | 1         | 0.02%   |
| en_HK          | 1         | 0.02%   |
| en_GG          | 1         | 0.02%   |
| en_GB.utf-8    | 1         | 0.02%   |
| en_GB.iso88591 | 1         | 0.02%   |
| en_AG          | 1         | 0.02%   |
| enGB           | 1         | 0.02%   |
| da_DK          | 1         | 0.02%   |
| C.UTF8         | 1         | 0.02%   |
| bg_BG          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2287      | 51.97%  |
| BIOS | 2114      | 48.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3271      | 73.62%  |
| Btrfs   | 524       | 11.79%  |
| Overlay | 296       | 6.66%   |
| Tmpfs   | 134       | 3.02%   |
| Unknown | 112       | 2.52%   |
| Xfs     | 52        | 1.17%   |
| Zfs     | 34        | 0.77%   |
| Ext2    | 9         | 0.2%    |
| F2fs    | 6         | 0.14%   |
| Ext3    | 4         | 0.09%   |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2375      | 53.68%  |
| GPT     | 1657      | 37.45%  |
| MBR     | 392       | 8.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3927      | 89.43%  |
| Yes       | 464       | 10.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3328      | 75.98%  |
| Yes       | 1052      | 24.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 861       | 19.96%  |
| Dell                | 836       | 19.38%  |
| Hewlett-Packard     | 698       | 16.18%  |
| ASUSTek Computer    | 317       | 7.35%   |
| Acer                | 313       | 7.26%   |
| Toshiba             | 183       | 4.24%   |
| Apple               | 142       | 3.29%   |
| Valve               | 120       | 2.78%   |
| Samsung Electronics | 79        | 1.83%   |
| MSI                 | 68        | 1.58%   |
| Sony                | 66        | 1.53%   |
| HUAWEI              | 51        | 1.18%   |
| Google              | 50        | 1.16%   |
| PC Specialist       | 48        | 1.11%   |
| Notebook            | 34        | 0.79%   |
| Unknown             | 33        | 0.77%   |
| Razer               | 24        | 0.56%   |
| Alienware           | 23        | 0.53%   |
| Star Labs           | 20        | 0.46%   |
| Fujitsu             | 19        | 0.44%   |
| Packard Bell        | 18        | 0.42%   |
| Fujitsu Siemens     | 15        | 0.35%   |
| Entroware           | 15        | 0.35%   |
| Dixonsxp            | 14        | 0.32%   |
| TUXEDO              | 13        | 0.3%    |
| GEO                 | 13        | 0.3%    |
| Clevo               | 13        | 0.3%    |
| LG Electronics      | 12        | 0.28%   |
| Linx                | 11        | 0.26%   |
| Panasonic           | 9         | 0.21%   |
| Gigabyte Technology | 9         | 0.21%   |
| Framework           | 9         | 0.21%   |
| Advent              | 9         | 0.21%   |
| Timi                | 8         | 0.19%   |
| Jumper              | 8         | 0.19%   |
| eMachines           | 8         | 0.19%   |
| OEGStone            | 7         | 0.16%   |
| Novatech            | 7         | 0.16%   |
| Medion              | 7         | 0.16%   |
| Intel               | 7         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Valve Jupiter                | 117       | 2.71%   |
| Unknown                      | 55        | 1.28%   |
| HP Pavilion g6               | 27        | 0.63%   |
| HP Notebook                  | 22        | 0.51%   |
| HP Pavilion 15               | 20        | 0.46%   |
| HP Pavilion Notebook         | 19        | 0.44%   |
| Dell XPS 15 9570             | 17        | 0.39%   |
| Dell XPS 15 9560             | 16        | 0.37%   |
| Dell XPS 15 7590             | 16        | 0.37%   |
| Dell Inspiron 1545           | 15        | 0.35%   |
| Dell XPS 13 9380             | 14        | 0.32%   |
| Dell XPS 13 9370             | 14        | 0.32%   |
| Dell XPS 13 9360             | 14        | 0.32%   |
| Dell Latitude E6400          | 13        | 0.3%    |
| HP Pavilion dv6              | 12        | 0.28%   |
| Dell Latitude E6410          | 12        | 0.28%   |
| Apple MacBookPro12,1         | 12        | 0.28%   |
| Toshiba Satellite C660       | 11        | 0.26%   |
| Lenovo V145-15AST 81MT       | 11        | 0.26%   |
| HP Laptop 15-bw0xx           | 11        | 0.26%   |
| Dell XPS 13 7390             | 11        | 0.26%   |
| Dell Latitude E7240          | 11        | 0.26%   |
| Apple MacBookPro9,2          | 11        | 0.26%   |
| Lenovo Z50-75 80EC           | 10        | 0.23%   |
| HP Laptop 15-da0xxx          | 10        | 0.23%   |
| HP 15                        | 10        | 0.23%   |
| Dell XPS 15 9550             | 10        | 0.23%   |
| Dell XPS 15 9510             | 10        | 0.23%   |
| Dell XPS 15 9500             | 10        | 0.23%   |
| Dell Latitude E7450          | 10        | 0.23%   |
| Dell Latitude E7440          | 10        | 0.23%   |
| Dell Latitude E6420          | 10        | 0.23%   |
| Acer Aspire ES1-531          | 10        | 0.23%   |
| Dell XPS 13 9310             | 9         | 0.21%   |
| Dell XPS 13 9305             | 9         | 0.21%   |
| Apple MacBookPro5,5          | 9         | 0.21%   |
| Linx LINX1010B               | 8         | 0.19%   |
| Dell Latitude E5430 non-vPro | 8         | 0.19%   |
| Dell Inspiron 5570           | 8         | 0.19%   |
| Dell Inspiron 13-5378        | 8         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 498       | 11.55%  |
| Dell Latitude         | 286       | 6.63%   |
| Acer Aspire           | 223       | 5.17%   |
| Dell Inspiron         | 213       | 4.94%   |
| Dell XPS              | 197       | 4.57%   |
| Toshiba Satellite     | 159       | 3.69%   |
| Lenovo IdeaPad        | 155       | 3.59%   |
| HP Pavilion           | 151       | 3.5%    |
| Valve Jupiter         | 117       | 2.71%   |
| HP EliteBook          | 116       | 2.69%   |
| ASUS VivoBook         | 80        | 1.85%   |
| HP Laptop             | 79        | 1.83%   |
| HP ProBook            | 76        | 1.76%   |
| Dell Precision        | 59        | 1.37%   |
| Unknown               | 55        | 1.28%   |
| HP ENVY               | 36        | 0.83%   |
| Lenovo Legion         | 34        | 0.79%   |
| HP Compaq             | 32        | 0.74%   |
| Acer Swift            | 32        | 0.74%   |
| ASUS Zenbook          | 30        | 0.7%    |
| ASUS ROG              | 30        | 0.7%    |
| HP Stream             | 29        | 0.67%   |
| Lenovo Yoga           | 26        | 0.6%    |
| Dell Vostro           | 26        | 0.6%    |
| Razer Blade           | 24        | 0.56%   |
| HP ZBook              | 23        | 0.53%   |
| HP Notebook           | 22        | 0.51%   |
| HP 255                | 21        | 0.49%   |
| Lenovo ThinkBook      | 20        | 0.46%   |
| HP Presario           | 18        | 0.42%   |
| Packard Bell EasyNote | 17        | 0.39%   |
| HP OMEN               | 17        | 0.39%   |
| Acer Nitro            | 17        | 0.39%   |
| Fujitsu LIFEBOOK      | 16        | 0.37%   |
| ASUS ASUS             | 16        | 0.37%   |
| Apple MacBookPro9     | 14        | 0.32%   |
| Apple MacBookPro11    | 14        | 0.32%   |
| Dell System           | 13        | 0.3%    |
| Apple MacBookPro5     | 13        | 0.3%    |
| ASUS TUF              | 12        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 367       | 8.51%   |
| 2020    | 351       | 8.14%   |
| 2019    | 351       | 8.14%   |
| 2021    | 310       | 7.19%   |
| 2012    | 303       | 7.03%   |
| 2013    | 300       | 6.96%   |
| 2017    | 283       | 6.56%   |
| 2011    | 266       | 6.17%   |
| 2015    | 248       | 5.75%   |
| 2014    | 246       | 5.7%    |
| 2016    | 243       | 5.63%   |
| 2022    | 241       | 5.59%   |
| 2010    | 199       | 4.61%   |
| 2008    | 195       | 4.52%   |
| 2009    | 153       | 3.55%   |
| 2007    | 106       | 2.46%   |
| 2023    | 92        | 2.13%   |
| 2006    | 42        | 0.97%   |
| 2005    | 8         | 0.19%   |
| Unknown | 7         | 0.16%   |
| 2003    | 1         | 0.02%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4313      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3868      | 88.82%  |
| Enabled  | 487       | 11.18%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4241      | 98.31%  |
| Yes  | 73        | 1.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1257      | 28.69%  |
| 3.01-4.0    | 836       | 19.08%  |
| 16.01-24.0  | 791       | 18.06%  |
| 8.01-16.0   | 747       | 17.05%  |
| 32.01-64.0  | 298       | 6.8%    |
| 1.01-2.0    | 234       | 5.34%   |
| 2.01-3.0    | 93        | 2.12%   |
| 64.01-256.0 | 49        | 1.12%   |
| 24.01-32.0  | 42        | 0.96%   |
| 0.51-1.0    | 33        | 0.75%   |
| 0.01-0.5    | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1733      | 36.26%  |
| 2.01-3.0   | 1178      | 24.64%  |
| 4.01-8.0   | 700       | 14.64%  |
| 3.01-4.0   | 642       | 13.43%  |
| 0.51-1.0   | 298       | 6.23%   |
| 8.01-16.0  | 162       | 3.39%   |
| 0.01-0.5   | 38        | 0.79%   |
| 16.01-24.0 | 19        | 0.4%    |
| 24.01-32.0 | 7         | 0.15%   |
| 32.01-64.0 | 2         | 0.04%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3191      | 72.34%  |
| 2      | 1032      | 23.4%   |
| 3      | 114       | 2.58%   |
| 0      | 37        | 0.84%   |
| 4      | 25        | 0.57%   |
| 5      | 6         | 0.14%   |
| 7      | 3         | 0.07%   |
| 9      | 1         | 0.02%   |
| 8      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2855      | 65.86%  |
| Yes       | 1480      | 34.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3271      | 75.58%  |
| No        | 1057      | 24.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4254      | 98.56%  |
| No        | 62        | 1.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3397      | 77.95%  |
| No        | 961       | 22.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 4313      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| London              | 285       | 5.97%   |
| Manchester          | 97        | 2.03%   |
| Birmingham          | 87        | 1.82%   |
| Glasgow             | 85        | 1.78%   |
| Edinburgh           | 73        | 1.53%   |
| Bristol             | 65        | 1.36%   |
| Leeds               | 59        | 1.24%   |
| Liverpool           | 54        | 1.13%   |
| Sheffield           | 51        | 1.07%   |
| Nottingham          | 51        | 1.07%   |
| Islington           | 46        | 0.96%   |
| Reading             | 44        | 0.92%   |
| Cambridge           | 41        | 0.86%   |
| Coventry            | 37        | 0.77%   |
| Southampton         | 34        | 0.71%   |
| Leicester           | 34        | 0.71%   |
| Norwich             | 33        | 0.69%   |
| Oxford              | 32        | 0.67%   |
| Croydon             | 31        | 0.65%   |
| Cardiff             | 31        | 0.65%   |
| York                | 28        | 0.59%   |
| Aberdeen            | 28        | 0.59%   |
| Milton Keynes       | 27        | 0.57%   |
| Bradford            | 25        | 0.52%   |
| Plymouth            | 24        | 0.5%    |
| Hackney             | 24        | 0.5%    |
| Newcastle upon Tyne | 23        | 0.48%   |
| Brighton            | 23        | 0.48%   |
| Southwark           | 22        | 0.46%   |
| Gloucester          | 22        | 0.46%   |
| Bolton              | 22        | 0.46%   |
| Wolverhampton       | 21        | 0.44%   |
| Swindon             | 21        | 0.44%   |
| Colchester          | 21        | 0.44%   |
| Chesterfield        | 21        | 0.44%   |
| Kensington          | 20        | 0.42%   |
| Derby               | 20        | 0.42%   |
| Belfast             | 20        | 0.42%   |
| Wigan               | 19        | 0.4%    |
| Walsall             | 19        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 835       | 1115   | 15.68%  |
| WDC                         | 498       | 638    | 9.35%   |
| Seagate                     | 492       | 671    | 9.24%   |
| Unknown                     | 476       | 624    | 8.94%   |
| Toshiba                     | 447       | 559    | 8.4%    |
| SanDisk                     | 337       | 423    | 6.33%   |
| Crucial                     | 229       | 314    | 4.3%    |
| SK hynix                    | 227       | 268    | 4.26%   |
| Kingston                    | 205       | 258    | 3.85%   |
| Hitachi                     | 180       | 216    | 3.38%   |
| Intel                       | 158       | 193    | 2.97%   |
| HGST                        | 126       | 185    | 2.37%   |
| Micron Technology           | 121       | 144    | 2.27%   |
| Apple                       | 73        | 100    | 1.37%   |
| KIOXIA                      | 63        | 74     | 1.18%   |
| Phison Electronics          | 53        | 62     | 1%      |
| Phison                      | 48        | 56     | 0.9%    |
| China                       | 47        | 68     | 0.88%   |
| LITEON                      | 42        | 55     | 0.79%   |
| A-DATA Technology           | 39        | 48     | 0.73%   |
| Unknown                     | 36        | 42     | 0.68%   |
| Micron/Crucial Technology   | 34        | 40     | 0.64%   |
| PNY                         | 32        | 39     | 0.6%    |
| Fujitsu                     | 32        | 42     | 0.6%    |
| Transcend                   | 31        | 38     | 0.58%   |
| Kingston Technology Company | 28        | 31     | 0.53%   |
| Silicon Motion              | 27        | 33     | 0.51%   |
| LITEONIT                    | 27        | 34     | 0.51%   |
| O2 Micro                    | 20        | 21     | 0.38%   |
| Integral                    | 17        | 19     | 0.32%   |
| SPCC                        | 13        | 19     | 0.24%   |
| OCZ                         | 12        | 13     | 0.23%   |
| Lenovo                      | 12        | 13     | 0.23%   |
| JMicron Technology          | 11        | 16     | 0.21%   |
| SABRENT                     | 10        | 12     | 0.19%   |
| Realtek                     | 10        | 10     | 0.19%   |
| Corsair                     | 10        | 14     | 0.19%   |
| Team                        | 9         | 12     | 0.17%   |
| Netac                       | 8         | 11     | 0.15%   |
| TCSUNBOW                    | 7         | 12     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                             | 101       | 1.81%   |
| Seagate ST1000LM035-1RK172 1TB                     | 66        | 1.18%   |
| Unknown MMC Card  64GB                             | 60        | 1.08%   |
| Toshiba MQ01ABD100 1TB                             | 58        | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 54        | 0.97%   |
| Unknown MMC Card  128GB                            | 45        | 0.81%   |
| Unknown MMC Card  512GB                            | 43        | 0.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 43        | 0.77%   |
| Phison PS5013 E13 NVMe Controller 256GB            | 41        | 0.73%   |
| Samsung NVMe SSD Drive 512GB                       | 37        | 0.66%   |
| Toshiba MQ01ABF050 500GB                           | 36        | 0.65%   |
| Unknown                                            | 36        | 0.65%   |
| Unknown MMC Card  16GB                             | 32        | 0.57%   |
| Kingston SA400S37240G 240GB SSD                    | 32        | 0.57%   |
| HGST HTS721010A9E630 1TB                           | 32        | 0.57%   |
| HGST HTS541010A9E680 1TB                           | 32        | 0.57%   |
| Samsung SSD 850 EVO 500GB                          | 30        | 0.54%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 29        | 0.52%   |
| Crucial CT500MX500SSD1 500GB                       | 29        | 0.52%   |
| Samsung SSD 860 EVO 500GB                          | 26        | 0.47%   |
| Kingston SA400S37120G 120GB SSD                    | 26        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB                        | 26        | 0.47%   |
| Toshiba NVMe SSD Drive 256GB                       | 25        | 0.45%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                 | 25        | 0.45%   |
| SanDisk NVMe SSD Drive 512GB                       | 25        | 0.45%   |
| Samsung SSD 850 EVO 250GB                          | 24        | 0.43%   |
| Unknown SD/MMC/MS PRO 256GB                        | 23        | 0.41%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                | 23        | 0.41%   |
| Unknown MMC Card  256GB                            | 22        | 0.39%   |
| Seagate ST500LT012-1DG142 500GB                    | 22        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB                       | 22        | 0.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 22        | 0.39%   |
| Seagate ST9500325AS 500GB                          | 21        | 0.38%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB            | 21        | 0.38%   |
| Kingston SA400S37480G 480GB SSD                    | 21        | 0.38%   |
| Toshiba MQ04ABF100 1TB                             | 20        | 0.36%   |
| Samsung NVMe SSD Drive 1024GB                      | 20        | 0.36%   |
| Crucial CT240BX500SSD1 240GB                       | 20        | 0.36%   |
| Crucial CT250MX500SSD1 250GB                       | 19        | 0.34%   |
| SK hynix NVMe SSD Drive 512GB                      | 18        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 476       | 648    | 31.63%  |
| WDC                 | 296       | 377    | 19.67%  |
| Toshiba             | 289       | 350    | 19.2%   |
| Hitachi             | 180       | 216    | 11.96%  |
| HGST                | 126       | 185    | 8.37%   |
| Samsung Electronics | 49        | 54     | 3.26%   |
| Fujitsu             | 32        | 42     | 2.13%   |
| Unknown             | 23        | 28     | 1.53%   |
| Apple               | 7         | 7      | 0.47%   |
| ASMT                | 5         | 28     | 0.33%   |
| TO Exter            | 4         | 4      | 0.27%   |
| SSK                 | 4         | 7      | 0.27%   |
| JMicron Technology  | 4         | 8      | 0.27%   |
| Initio              | 2         | 2      | 0.13%   |
| IBM/Hitachi         | 2         | 2      | 0.13%   |
| Maxone              | 1         | 1      | 0.07%   |
| LaCie               | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |
| HGST HTS            | 1         | 1      | 0.07%   |
| Generic-            | 1         | 1      | 0.07%   |
| External            | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 351       | 477    | 21.03%  |
| Crucial             | 208       | 289    | 12.46%  |
| SanDisk             | 182       | 224    | 10.9%   |
| Kingston            | 162       | 201    | 9.71%   |
| WDC                 | 91        | 127    | 5.45%   |
| Intel               | 54        | 58     | 3.24%   |
| Micron Technology   | 49        | 57     | 2.94%   |
| SK hynix            | 44        | 57     | 2.64%   |
| China               | 44        | 62     | 2.64%   |
| Apple               | 44        | 55     | 2.64%   |
| Toshiba             | 42        | 59     | 2.52%   |
| LITEON              | 40        | 53     | 2.4%    |
| PNY                 | 31        | 37     | 1.86%   |
| Transcend           | 30        | 37     | 1.8%    |
| A-DATA Technology   | 30        | 37     | 1.8%    |
| LITEONIT            | 27        | 34     | 1.62%   |
| Integral            | 17        | 19     | 1.02%   |
| SPCC                | 12        | 17     | 0.72%   |
| OCZ                 | 12        | 13     | 0.72%   |
| SABRENT             | 10        | 12     | 0.6%    |
| Seagate             | 9         | 9      | 0.54%   |
| Team                | 8         | 11     | 0.48%   |
| Netac               | 8         | 11     | 0.48%   |
| Unknown             | 7         | 7      | 0.42%   |
| Patriot             | 7         | 15     | 0.42%   |
| Drevo               | 7         | 10     | 0.42%   |
| TCSUNBOW            | 6         | 11     | 0.36%   |
| Star                | 6         | 8      | 0.36%   |
| Lexar               | 6         | 7      | 0.36%   |
| Corsair             | 6         | 10     | 0.36%   |
| BHT                 | 6         | 9      | 0.36%   |
| KIOXIA-EXCERIA      | 5         | 5      | 0.3%    |
| Gigabyte Technology | 5         | 6      | 0.3%    |
| XUM                 | 4         | 4      | 0.24%   |
| ORTIAL              | 4         | 4      | 0.24%   |
| BIWIN               | 4         | 4      | 0.24%   |
| ZTC                 | 3         | 6      | 0.18%   |
| Zheino              | 3         | 5      | 0.18%   |
| Vaseky              | 3         | 4      | 0.18%   |
| ShiJi               | 3         | 3      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1535      | 2035   | 30.48%  |
| SSD     | 1510      | 2176   | 29.98%  |
| HDD     | 1458      | 1964   | 28.95%  |
| MMC     | 475       | 619    | 9.43%   |
| Unknown | 58        | 70     | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2717      | 3966   | 55.48%  |
| NVMe | 1532      | 2021   | 31.28%  |
| MMC  | 475       | 619    | 9.7%    |
| SAS  | 173       | 258    | 3.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2047      | 2841   | 68.58%  |
| 0.51-1.0   | 803       | 1093   | 26.9%   |
| 1.01-2.0   | 109       | 147    | 3.65%   |
| 4.01-10.0  | 16        | 26     | 0.54%   |
| 3.01-4.0   | 9         | 32     | 0.3%    |
| 2.01-3.0   | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1337      | 29.29%  |
| 251-500        | 1067      | 23.38%  |
| 501-1000       | 691       | 15.14%  |
| 1-20           | 352       | 7.71%   |
| 51-100         | 323       | 7.08%   |
| 1001-2000      | 262       | 5.74%   |
| 21-50          | 254       | 5.57%   |
| Unknown        | 126       | 2.76%   |
| More than 3000 | 91        | 1.99%   |
| 2001-3000      | 61        | 1.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1972      | 41.63%  |
| 21-50          | 893       | 18.85%  |
| 101-250        | 604       | 12.75%  |
| 51-100         | 540       | 11.4%   |
| 251-500        | 326       | 6.88%   |
| 501-1000       | 166       | 3.5%    |
| Unknown        | 126       | 2.66%   |
| 1001-2000      | 70        | 1.48%   |
| 2001-3000      | 20        | 0.42%   |
| More than 3000 | 19        | 0.4%    |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 6         | 10     | 2.71%   |
| Seagate ST1000LM035-1RK172 1TB                 | 6         | 6      | 2.71%   |
| HGST HTS725050A7E630 500GB                     | 6         | 9      | 2.71%   |
| Hitachi HTS547575A9E384 752GB                  | 5         | 7      | 2.26%   |
| HGST HTS541010A9E680 1TB                       | 5         | 5      | 2.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 4         | 6      | 1.81%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 3      | 1.36%   |
| Toshiba MK1656GSY 160GB                        | 3         | 3      | 1.36%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 3      | 1.36%   |
| Intel SSDSC2BF180A5L 180GB                     | 3         | 3      | 1.36%   |
| Hitachi HTS543216L9A300 160GB                  | 3         | 3      | 1.36%   |
| Hitachi HTS542512K9SA00 120GB                  | 3         | 3      | 1.36%   |
| HGST HTS721010A9E630 1TB                       | 3         | 3      | 1.36%   |
| WDC WD2500BEVT-80A23T0 250GB                   | 2         | 5      | 0.9%    |
| Toshiba MK5065GSXN 500GB                       | 2         | 2      | 0.9%    |
| Toshiba MK3256GSY 320GB                        | 2         | 3      | 0.9%    |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.9%    |
| Seagate ST9320325AS 320GB                      | 2         | 3      | 0.9%    |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 0.9%    |
| Seagate ST2000LX001-1RG174 2TB                 | 2         | 2      | 0.9%    |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 2         | 2      | 0.9%    |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 3      | 0.9%    |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.9%    |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.9%    |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 2      | 0.9%    |
| LITEON LCH-256V2S-11 2.5 7mm 256GB SSD         | 2         | 3      | 0.9%    |
| LITEON CS1-SP32-11 M.2 2242 32GB SSD           | 2         | 2      | 0.9%    |
| Hitachi HTS547564A9E384 640GB                  | 2         | 2      | 0.9%    |
| Hitachi HTS545050A7E380 500GB                  | 2         | 2      | 0.9%    |
| Hitachi HTS545032B9A302 320GB                  | 2         | 3      | 0.9%    |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 0.9%    |
| Hitachi HTS545025B9A300 250GB                  | 2         | 2      | 0.9%    |
| Hitachi HTS541680J9SA00 80GB                   | 2         | 3      | 0.9%    |
| Drevo X1 SSD 480GB                             | 2         | 2      | 0.9%    |
| Crucial CT525MX300SSD4 528GB                   | 2         | 2      | 0.9%    |
| Zheino CHN mSATA02M 256 256GB SSD              | 1         | 2      | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 0.45%   |
| WDC WD7500BPVT-60HXZT3 752GB                   | 1         | 1      | 0.45%   |
| WDC WD5000BPVT-55HXZT3 500GB                   | 1         | 1      | 0.45%   |
| WDC WD5000BEVT-75A0RT0 500GB                   | 1         | 1      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 60     | 23.18%  |
| Hitachi             | 35        | 39     | 15.91%  |
| Toshiba             | 26        | 27     | 11.82%  |
| WDC                 | 18        | 23     | 8.18%   |
| HGST                | 18        | 21     | 8.18%   |
| Samsung Electronics | 12        | 13     | 5.45%   |
| Intel               | 10        | 10     | 4.55%   |
| Crucial             | 10        | 10     | 4.55%   |
| SanDisk             | 5         | 5      | 2.27%   |
| Kingston            | 5         | 7      | 2.27%   |
| SK hynix            | 4         | 4      | 1.82%   |
| Micron Technology   | 4         | 4      | 1.82%   |
| LITEON              | 4         | 5      | 1.82%   |
| Fujitsu             | 4         | 5      | 1.82%   |
| Drevo               | 2         | 2      | 0.91%   |
| China               | 2         | 2      | 0.91%   |
| A-DATA Technology   | 2         | 2      | 0.91%   |
| Zheino              | 1         | 2      | 0.45%   |
| Team                | 1         | 1      | 0.45%   |
| OCZ                 | 1         | 1      | 0.45%   |
| LITEONIT            | 1         | 2      | 0.45%   |
| HECTRON             | 1         | 1      | 0.45%   |
| Corsair             | 1         | 1      | 0.45%   |
| BAITITON            | 1         | 1      | 0.45%   |
| 2-Power             | 1         | 1      | 0.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 60     | 33.33%  |
| Hitachi             | 35        | 39     | 22.88%  |
| Toshiba             | 24        | 25     | 15.69%  |
| HGST                | 18        | 21     | 11.76%  |
| WDC                 | 16        | 21     | 10.46%  |
| Samsung Electronics | 5         | 5      | 3.27%   |
| Fujitsu             | 4         | 5      | 2.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 152       | 176    | 69.41%  |
| SSD  | 61        | 67     | 27.85%  |
| NVMe | 6         | 6      | 2.74%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB | 1         | 1      | 33.33%  |
| Toshiba THNSN5512GPUK NVMe 512GB              | 1         | 2      | 33.33%  |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba                 | 2         | 3      | 66.67%  |
| Union Memory (Shenzhen) | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2786      | 4490   | 61.37%  |
| Works    | 1535      | 2121   | 33.81%  |
| Malfunc  | 216       | 249    | 4.76%   |
| Failed   | 3         | 4      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2849      | 57.28%  |
| Samsung Electronics              | 500       | 10.05%  |
| AMD                              | 480       | 9.65%   |
| SanDisk                          | 257       | 5.17%   |
| SK hynix                         | 179       | 3.6%    |
| Toshiba America Info Systems     | 123       | 2.47%   |
| Phison Electronics               | 109       | 2.19%   |
| Micron Technology                | 74        | 1.49%   |
| Kingston Technology Company      | 71        | 1.43%   |
| KIOXIA                           | 62        | 1.25%   |
| Micron/Crucial Technology        | 52        | 1.05%   |
| Nvidia                           | 44        | 0.88%   |
| Silicon Motion                   | 30        | 0.6%    |
| O2 Micro                         | 20        | 0.4%    |
| Apple                            | 19        | 0.38%   |
| ADATA Technology                 | 14        | 0.28%   |
| Silicon Integrated Systems [SiS] | 12        | 0.24%   |
| Solid State Storage Technology   | 11        | 0.22%   |
| Lenovo                           | 11        | 0.22%   |
| Union Memory (Shenzhen)          | 7         | 0.14%   |
| Marvell Technology Group         | 7         | 0.14%   |
| Lite-On Technology               | 6         | 0.12%   |
| Shenzhen Longsys Electronics     | 5         | 0.1%    |
| VIA Technologies                 | 4         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.08%   |
| Yangtze Memory Technologies      | 3         | 0.06%   |
| Solidigm                         | 3         | 0.06%   |
| Realtek Semiconductor            | 3         | 0.06%   |
| JMicron Technology               | 3         | 0.06%   |
| ASMedia Technology               | 3         | 0.06%   |
| INNOGRIT                         | 2         | 0.04%   |
| Biwin Storage Technology         | 2         | 0.04%   |
| Silicon Image                    | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 408       | 7.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 324       | 6.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 282       | 5.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 278       | 5.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 226       | 4.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 197       | 3.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 171       | 3.21%   |
| Intel Volume Management Device NVMe RAID Controller                              | 148       | 2.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 134       | 2.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 128       | 2.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 122       | 2.29%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 101       | 1.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 97        | 1.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 86        | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 82        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 82        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 73        | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 69        | 1.29%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 65        | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 62        | 1.16%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 61        | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 60        | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                            | 57        | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 56        | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 52        | 0.98%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 51        | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 51        | 0.96%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 49        | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 47        | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 46        | 0.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 43        | 0.81%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 43        | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 41        | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 40        | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 39        | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                              | 39        | 0.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 36        | 0.68%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 31        | 0.58%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 31        | 0.58%   |
| Intel SSD 660P Series                                                            | 30        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2804      | 54.89%  |
| NVMe | 1544      | 30.23%  |
| RAID | 441       | 8.63%   |
| IDE  | 319       | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 3513      | 81.45%  |
| AMD     | 798       | 18.5%   |
| ARM     | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 120       | 2.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 64        | 1.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 60        | 1.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 55        | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 53        | 1.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 53        | 1.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 52        | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 50        | 1.16%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 49        | 1.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 46        | 1.07%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 46        | 1.07%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 44        | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 44        | 1.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 41        | 0.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 41        | 0.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 41        | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 40        | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 40        | 0.93%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 39        | 0.9%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 38        | 0.88%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 37        | 0.86%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 35        | 0.81%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 34        | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 34        | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 32        | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 30        | 0.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 30        | 0.69%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 29        | 0.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 28        | 0.65%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 25        | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 24        | 0.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 24        | 0.56%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 24        | 0.56%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 24        | 0.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 23        | 0.53%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 23        | 0.53%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 23        | 0.53%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 22        | 0.51%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 22        | 0.51%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1008      | 23.35%  |
| Intel Core i7           | 923       | 21.38%  |
| Other                   | 483       | 11.19%  |
| Intel Core i3           | 292       | 6.76%   |
| Intel Celeron           | 291       | 6.74%   |
| Intel Core 2 Duo        | 220       | 5.1%    |
| AMD Ryzen 7             | 128       | 2.97%   |
| AMD Ryzen 5             | 126       | 2.92%   |
| Intel Pentium           | 112       | 2.59%   |
| Intel Atom              | 85        | 1.97%   |
| AMD A6                  | 63        | 1.46%   |
| AMD A8                  | 46        | 1.07%   |
| AMD Ryzen 3             | 40        | 0.93%   |
| Intel Pentium Dual-Core | 37        | 0.86%   |
| Intel Core 2            | 34        | 0.79%   |
| AMD Ryzen 9             | 28        | 0.65%   |
| AMD A4                  | 28        | 0.65%   |
| Intel Pentium Dual      | 27        | 0.63%   |
| AMD Ryzen 7 PRO         | 27        | 0.63%   |
| Intel Genuine           | 25        | 0.58%   |
| Intel Core i9           | 24        | 0.56%   |
| Intel Celeron Dual-Core | 21        | 0.49%   |
| AMD E1                  | 21        | 0.49%   |
| AMD A10                 | 20        | 0.46%   |
| AMD E                   | 18        | 0.42%   |
| Intel Pentium Silver    | 15        | 0.35%   |
| Intel Celeron M         | 15        | 0.35%   |
| AMD E2                  | 15        | 0.35%   |
| Intel Pentium M         | 10        | 0.23%   |
| AMD Athlon              | 10        | 0.23%   |
| AMD Turion 64 X2 Mobile | 8         | 0.19%   |
| AMD Athlon II           | 8         | 0.19%   |
| Intel Core m3           | 7         | 0.16%   |
| AMD Ryzen 5 PRO         | 7         | 0.16%   |
| AMD FX                  | 7         | 0.16%   |
| AMD Athlon X2           | 7         | 0.16%   |
| Intel Core M            | 6         | 0.14%   |
| AMD Turion 64 Mobile    | 6         | 0.14%   |
| Intel Pentium Gold      | 5         | 0.12%   |
| AMD Phenom II           | 5         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2244      | 52%     |
| 4      | 1361      | 31.54%  |
| 6      | 239       | 5.54%   |
| 8      | 236       | 5.47%   |
| 1      | 113       | 2.62%   |
| 14     | 43        | 1%      |
| 12     | 37        | 0.86%   |
| 10     | 34        | 0.79%   |
| 16     | 4         | 0.09%   |
| 24     | 2         | 0.05%   |
| 3      | 2         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4312      | 99.98%  |
| 2      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3105      | 71.94%  |
| 1      | 1211      | 28.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4208      | 97.29%  |
| 32-bit         | 58        | 1.34%   |
| Unknown        | 58        | 1.34%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1426      | 31.79%  |
| 0x306a9    | 243       | 5.42%   |
| 0x206a7    | 208       | 4.64%   |
| 0x1067a    | 158       | 3.52%   |
| 0x806ea    | 124       | 2.76%   |
| 0x806ec    | 123       | 2.74%   |
| 0x40651    | 123       | 2.74%   |
| 0x406e3    | 114       | 2.54%   |
| 0x806e9    | 113       | 2.52%   |
| 0x306d4    | 107       | 2.39%   |
| 0x20655    | 98        | 2.18%   |
| 0x806c1    | 96        | 2.14%   |
| 0x906ea    | 92        | 2.05%   |
| 0x6fd      | 69        | 1.54%   |
| 0x406c4    | 65        | 1.45%   |
| 0x306c3    | 65        | 1.45%   |
| 0x30678    | 63        | 1.4%    |
| 0x906e9    | 51        | 1.14%   |
| 0xa0652    | 50        | 1.11%   |
| 0x506e3    | 45        | 1%      |
| 0x506c9    | 45        | 1%      |
| 0x08108109 | 44        | 0.98%   |
| 0x0a50000c | 43        | 0.96%   |
| 0x06006705 | 43        | 0.96%   |
| 0x706e5    | 37        | 0.82%   |
| 0x08108102 | 37        | 0.82%   |
| 0x406c3    | 35        | 0.78%   |
| 0x10676    | 34        | 0.76%   |
| 0x20652    | 33        | 0.74%   |
| 0x806d1    | 31        | 0.69%   |
| 0x906a3    | 30        | 0.67%   |
| 0x706a1    | 30        | 0.67%   |
| 0x07030105 | 30        | 0.67%   |
| 0x08600106 | 27        | 0.6%    |
| 0x6f6      | 25        | 0.56%   |
| 0x06006704 | 24        | 0.53%   |
| 0x806eb    | 21        | 0.47%   |
| 0x08608103 | 20        | 0.45%   |
| 0x08600104 | 20        | 0.45%   |
| 0x05000119 | 20        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 770       | 17.82%  |
| IvyBridge         | 321       | 7.43%   |
| Haswell           | 288       | 6.67%   |
| SandyBridge       | 276       | 6.39%   |
| Unknown           | 251       | 5.81%   |
| Skylake           | 230       | 5.32%   |
| Penryn            | 227       | 5.25%   |
| Silvermont        | 208       | 4.81%   |
| TigerLake         | 169       | 3.91%   |
| Westmere          | 168       | 3.89%   |
| Core              | 159       | 3.68%   |
| Broadwell         | 155       | 3.59%   |
| Zen+              | 102       | 2.36%   |
| IceLake           | 95        | 2.2%    |
| Alderlake Hybrid  | 93        | 2.15%   |
| Excavator         | 90        | 2.08%   |
| CometLake         | 85        | 1.97%   |
| Zen 2             | 81        | 1.88%   |
| Goldmont plus     | 73        | 1.69%   |
| Zen 3             | 69        | 1.6%    |
| Puma              | 57        | 1.32%   |
| Goldmont          | 55        | 1.27%   |
| P6                | 41        | 0.95%   |
| Zen               | 40        | 0.93%   |
| Bobcat            | 38        | 0.88%   |
| Bonnell           | 34        | 0.79%   |
| Piledriver        | 23        | 0.53%   |
| K10               | 23        | 0.53%   |
| Jaguar            | 22        | 0.51%   |
| K8 Hammer         | 20        | 0.46%   |
| Steamroller       | 16        | 0.37%   |
| Nehalem           | 13        | 0.3%    |
| K8 & K10 hybrid   | 13        | 0.3%    |
| K10 Llano         | 7         | 0.16%   |
| Tremont           | 5         | 0.12%   |
| NetBurst          | 2         | 0.05%   |
| Meteorlake Hybrid | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3242      | 62.51%  |
| Nvidia                           | 988       | 19.05%  |
| AMD                              | 939       | 18.11%  |
| Silicon Integrated Systems [SiS] | 12        | 0.23%   |
| VIA Technologies                 | 4         | 0.08%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 305       | 5.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 262       | 4.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 176       | 3.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 167       | 3.12%   |
| Intel UHD Graphics 620                                                                   | 160       | 2.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 150       | 2.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 145       | 2.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 140       | 2.62%   |
| Intel Core Processor Integrated Graphics Controller                                      | 137       | 2.56%   |
| Intel HD Graphics 620                                                                    | 136       | 2.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 117       | 2.19%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 117       | 2.19%   |
| Intel HD Graphics 5500                                                                   | 115       | 2.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 108       | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 108       | 2.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 108       | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 95        | 1.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 91        | 1.7%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 76        | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 74        | 1.38%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 71        | 1.33%   |
| Intel HD Graphics 630                                                                    | 65        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 62        | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 62        | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 62        | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 58        | 1.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 56        | 1.05%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 54        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 51        | 0.95%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 50        | 0.93%   |
| Intel HD Graphics 530                                                                    | 49        | 0.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 47        | 0.88%   |
| Intel HD Graphics 500                                                                    | 45        | 0.84%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 42        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 39        | 0.73%   |
| AMD Lucienne                                                                             | 38        | 0.71%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 37        | 0.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 36        | 0.67%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 33        | 0.62%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 33        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2419      | 55.88%  |
| 1 x AMD                  | 746       | 17.23%  |
| Intel + Nvidia           | 709       | 16.38%  |
| 1 x Nvidia               | 209       | 4.83%   |
| Intel + AMD              | 91        | 2.1%    |
| AMD + Nvidia             | 65        | 1.5%    |
| 2 x AMD                  | 37        | 0.85%   |
| 2 x Intel                | 23        | 0.53%   |
| 1 x SiS                  | 12        | 0.28%   |
| Other                    | 9         | 0.21%   |
| 1 x VIA                  | 4         | 0.09%   |
| 2 x Nvidia               | 3         | 0.07%   |
| Intel + 2 x Nvidia       | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3761      | 86.12%  |
| Proprietary | 511       | 11.7%   |
| Unknown     | 95        | 2.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3086      | 69.82%  |
| 0.01-0.5   | 490       | 11.09%  |
| 1.01-2.0   | 348       | 7.87%   |
| 3.01-4.0   | 192       | 4.34%   |
| 0.51-1.0   | 173       | 3.91%   |
| 5.01-6.0   | 66        | 1.49%   |
| 7.01-8.0   | 45        | 1.02%   |
| 2.01-3.0   | 10        | 0.23%   |
| 8.01-16.0  | 10        | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 883       | 18.63%  |
| LG Display              | 713       | 15.04%  |
| Chimei Innolux          | 571       | 12.05%  |
| BOE                     | 548       | 11.56%  |
| Samsung Electronics     | 482       | 10.17%  |
| Sharp                   | 224       | 4.73%   |
| Apple                   | 146       | 3.08%   |
| Dell                    | 121       | 2.55%   |
| Lenovo                  | 100       | 2.11%   |
| Chi Mei Optoelectronics | 87        | 1.84%   |
| Valve                   | 76        | 1.6%    |
| PANDA                   | 70        | 1.48%   |
| Goldstar                | 66        | 1.39%   |
| LG Philips              | 52        | 1.1%    |
| Acer                    | 50        | 1.05%   |
| Hewlett-Packard         | 48        | 1.01%   |
| InfoVision              | 42        | 0.89%   |
| Iiyama                  | 40        | 0.84%   |
| BenQ                    | 39        | 0.82%   |
| AOC                     | 37        | 0.78%   |
| Philips                 | 26        | 0.55%   |
| Analogix                | 26        | 0.55%   |
| CSO                     | 25        | 0.53%   |
| Ancor Communications    | 21        | 0.44%   |
| Panasonic               | 18        | 0.38%   |
| Sony                    | 16        | 0.34%   |
| ViewSonic               | 14        | 0.3%    |
| Toshiba                 | 13        | 0.27%   |
| LGD                     | 13        | 0.27%   |
| InnoLux Display         | 13        | 0.27%   |
| HannStar                | 11        | 0.23%   |
| ASUSTek Computer        | 11        | 0.23%   |
| Vestel Elektronik       | 9         | 0.19%   |
| CPT                     | 8         | 0.17%   |
| Quanta Display          | 7         | 0.15%   |
| Seiko/Epson             | 6         | 0.13%   |
| Unknown                 | 5         | 0.11%   |
| TMX                     | 5         | 0.11%   |
| NEC Computers           | 5         | 0.11%   |
| JDI                     | 5         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 73        | 1.52%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 47        | 0.98%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 38        | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 33        | 0.69%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 33        | 0.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 31        | 0.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 31        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 28        | 0.58%   |
| Analogix ANX7530 U ANX7539 800x1280                                   | 26        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 24        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 22        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 22        | 0.46%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 21        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 19        | 0.4%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 18        | 0.38%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 18        | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 16        | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 16        | 0.33%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch         | 16        | 0.33%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 15        | 0.31%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 15        | 0.31%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 14        | 0.29%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 14        | 0.29%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 14        | 0.29%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 14        | 0.29%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 14        | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 14        | 0.29%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 13        | 0.27%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 13        | 0.27%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 13        | 0.27%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 13        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 13        | 0.27%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 12        | 0.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 12        | 0.25%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch         | 12        | 0.25%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch         | 12        | 0.25%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 12        | 0.25%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 11        | 0.23%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 11        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1725      | 38.2%   |
| 1366x768 (WXGA)    | 1336      | 29.58%  |
| 1280x800 (WXGA)    | 224       | 4.96%   |
| 3840x2160 (4K)     | 211       | 4.67%   |
| 1600x900 (HD+)     | 166       | 3.68%   |
| 2560x1440 (QHD)    | 143       | 3.17%   |
| 800x1280           | 99        | 2.19%   |
| 1920x1200 (WUXGA)  | 97        | 2.15%   |
| 1440x900 (WXGA+)   | 86        | 1.9%    |
| 2560x1600          | 69        | 1.53%   |
| 3840x2400          | 41        | 0.91%   |
| 2880x1800          | 41        | 0.91%   |
| 1680x1050 (WSXGA+) | 32        | 0.71%   |
| 3440x1440          | 27        | 0.6%    |
| 3200x1800 (QHD+)   | 25        | 0.55%   |
| 1024x600           | 23        | 0.51%   |
| 1280x1024 (SXGA)   | 19        | 0.42%   |
| 2160x1440          | 15        | 0.33%   |
| 2560x1080          | 13        | 0.29%   |
| 2256x1504          | 11        | 0.24%   |
| Unknown            | 10        | 0.22%   |
| 1360x768           | 9         | 0.2%    |
| 3072x1920          | 8         | 0.18%   |
| 1920x540           | 7         | 0.16%   |
| 3456x2160          | 6         | 0.13%   |
| 1680x945           | 6         | 0.13%   |
| 1024x768 (XGA)     | 6         | 0.13%   |
| 3000x2000          | 5         | 0.11%   |
| 2560x1700          | 5         | 0.11%   |
| 1920x1280          | 5         | 0.11%   |
| 3840x1080          | 3         | 0.07%   |
| 3200x2000          | 3         | 0.07%   |
| 2880x1920          | 3         | 0.07%   |
| 2520x1680          | 3         | 0.07%   |
| 2304x1440          | 3         | 0.07%   |
| 1280x768           | 3         | 0.07%   |
| 3120x2080          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 2240x1400          | 2         | 0.04%   |
| 2160x1350          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1884      | 39.85%  |
| 13      | 752       | 15.91%  |
| 14      | 484       | 10.24%  |
| 17      | 293       | 6.2%    |
| 12      | 203       | 4.29%   |
| 27      | 146       | 3.09%   |
| 11      | 130       | 2.75%   |
| 24      | 113       | 2.39%   |
| 23      | 84        | 1.78%   |
| 21      | 79        | 1.67%   |
| 7       | 76        | 1.61%   |
| 16      | 65        | 1.37%   |
| Unknown | 63        | 1.33%   |
| 31      | 47        | 0.99%   |
| 34      | 36        | 0.76%   |
| 10      | 34        | 0.72%   |
| 18      | 32        | 0.68%   |
| 3       | 26        | 0.55%   |
| 84      | 24        | 0.51%   |
| 19      | 18        | 0.38%   |
| 25      | 15        | 0.32%   |
| 22      | 13        | 0.27%   |
| 72      | 12        | 0.25%   |
| 26      | 12        | 0.25%   |
| 20      | 9         | 0.19%   |
| 8       | 9         | 0.19%   |
| 40      | 8         | 0.17%   |
| 54      | 7         | 0.15%   |
| 65      | 6         | 0.13%   |
| 48      | 6         | 0.13%   |
| 32      | 5         | 0.11%   |
| 33      | 4         | 0.08%   |
| 86      | 3         | 0.06%   |
| 50      | 3         | 0.06%   |
| 35      | 3         | 0.06%   |
| 28      | 3         | 0.06%   |
| 142     | 2         | 0.04%   |
| 49      | 2         | 0.04%   |
| 46      | 2         | 0.04%   |
| 42      | 2         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2672      | 56.88%  |
| 201-300        | 811       | 17.26%  |
| 351-400        | 373       | 7.94%   |
| 501-600        | 334       | 7.11%   |
| 401-500        | 134       | 2.85%   |
| 1-100          | 99        | 2.11%   |
| 601-700        | 67        | 1.43%   |
| Unknown        | 63        | 1.34%   |
| 701-800        | 45        | 0.96%   |
| 1501-2000      | 38        | 0.81%   |
| 1001-1500      | 33        | 0.7%    |
| 801-900        | 13        | 0.28%   |
| 101-200        | 9         | 0.19%   |
| 901-1000       | 4         | 0.09%   |
| More than 2000 | 3         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3395      | 79.3%   |
| 16/10   | 583       | 13.62%  |
| 0.67    | 73        | 1.71%   |
| 3/2     | 60        | 1.4%    |
| Unknown | 56        | 1.31%   |
| 21/9    | 42        | 0.98%   |
| 6/5     | 29        | 0.68%   |
| 5/4     | 16        | 0.37%   |
| 4/3     | 12        | 0.28%   |
| 0.62    | 6         | 0.14%   |
| 32/9    | 3         | 0.07%   |
| 1.00    | 3         | 0.07%   |
| 0.56    | 2         | 0.05%   |
| 3.40    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1876      | 39.74%  |
| 81-90          | 875       | 18.53%  |
| 71-80          | 356       | 7.54%   |
| 121-130        | 247       | 5.23%   |
| 201-250        | 240       | 5.08%   |
| 61-70          | 195       | 4.13%   |
| 301-350        | 156       | 3.3%    |
| 51-60          | 132       | 2.8%    |
| 1-40           | 108       | 2.29%   |
| 351-500        | 98        | 2.08%   |
| More than 1000 | 69        | 1.46%   |
| 111-120        | 64        | 1.36%   |
| Unknown        | 63        | 1.33%   |
| 151-200        | 47        | 1%      |
| 131-140        | 47        | 1%      |
| 251-300        | 43        | 0.91%   |
| 41-50          | 33        | 0.7%    |
| 141-150        | 33        | 0.7%    |
| 91-100         | 20        | 0.42%   |
| 501-1000       | 19        | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1791      | 38.43%  |
| 101-120       | 1355      | 29.08%  |
| 51-100        | 643       | 13.8%   |
| 161-240       | 515       | 11.05%  |
| More than 240 | 241       | 5.17%   |
| Unknown       | 63        | 1.35%   |
| 1-50          | 52        | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3660      | 83.18%  |
| 2     | 584       | 13.27%  |
| 0     | 96        | 2.18%   |
| 3     | 55        | 1.25%   |
| 4     | 4         | 0.09%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2348      | 35.26%  |
| Realtek Semiconductor             | 2043      | 30.68%  |
| Qualcomm Atheros                  | 873       | 13.11%  |
| Broadcom                          | 482       | 7.24%   |
| Broadcom Limited                  | 117       | 1.76%   |
| Marvell Technology Group          | 95        | 1.43%   |
| MediaTek                          | 71        | 1.07%   |
| Ralink Technology                 | 58        | 0.87%   |
| TP-Link                           | 51        | 0.77%   |
| Ralink                            | 50        | 0.75%   |
| Ericsson Business Mobile Networks | 43        | 0.65%   |
| ASIX Electronics                  | 43        | 0.65%   |
| Qualcomm                          | 37        | 0.56%   |
| Dell                              | 35        | 0.53%   |
| DisplayLink                       | 31        | 0.47%   |
| Nvidia                            | 30        | 0.45%   |
| Lenovo                            | 26        | 0.39%   |
| Samsung Electronics               | 23        | 0.35%   |
| Sierra Wireless                   | 20        | 0.3%    |
| Hewlett-Packard                   | 20        | 0.3%    |
| JMicron Technology                | 12        | 0.18%   |
| Huawei Technologies               | 12        | 0.18%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.17%   |
| Edimax Technology                 | 9         | 0.14%   |
| NetGear                           | 8         | 0.12%   |
| Qualcomm Atheros Communications   | 7         | 0.11%   |
| ICS Advent                        | 7         | 0.11%   |
| Google                            | 7         | 0.11%   |
| Xiaomi                            | 5         | 0.08%   |
| OPPO Electronics                  | 5         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.08%   |
| Micro Star International          | 5         | 0.08%   |
| Belkin Components                 | 5         | 0.08%   |
| Attansic Technology               | 5         | 0.08%   |
| ASUSTek Computer                  | 5         | 0.08%   |
| Apple                             | 5         | 0.08%   |
| VIA Technologies                  | 4         | 0.06%   |
| Fibocom                           | 4         | 0.06%   |
| Motorola PCS                      | 3         | 0.05%   |
| D-Link                            | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 1084      | 13.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 412       | 5.11%   |
| Intel Wi-Fi 6 AX200                                                     | 197       | 2.44%   |
| Intel Wireless 8265 / 8275                                              | 185       | 2.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 184       | 2.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 183       | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 168       | 2.08%   |
| Intel Wireless 7265                                                     | 162       | 2.01%   |
| Intel Wireless 7260                                                     | 153       | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 145       | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 144       | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 138       | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 137       | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 121       | 1.5%    |
| Intel Wi-Fi 6 AX201                                                     | 114       | 1.41%   |
| Intel Wireless 8260                                                     | 111       | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 102       | 1.27%   |
| Intel Wireless 3165                                                     | 97        | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 87        | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 77        | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 73        | 0.91%   |
| Intel 82577LM Gigabit Network Connection                                | 70        | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 70        | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                   | 69        | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 68        | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 67        | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 67        | 0.83%   |
| Intel Ethernet Connection I218-LM                                       | 65        | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 64        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 58        | 0.72%   |
| Intel Wireless 3160                                                     | 54        | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 54        | 0.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 53        | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 51        | 0.63%   |
| Intel WiFi Link 5100                                                    | 50        | 0.62%   |
| Intel Ethernet Connection I219-LM                                       | 49        | 0.61%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 48        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                   | 48        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                          | 48        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 47        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2256      | 49.89%  |
| Qualcomm Atheros                  | 756       | 16.72%  |
| Realtek Semiconductor             | 693       | 15.33%  |
| Broadcom                          | 371       | 8.2%    |
| Broadcom Limited                  | 92        | 2.03%   |
| MediaTek                          | 66        | 1.46%   |
| Ralink Technology                 | 58        | 1.28%   |
| Ralink                            | 50        | 1.11%   |
| TP-Link                           | 44        | 0.97%   |
| Qualcomm                          | 26        | 0.57%   |
| Sierra Wireless                   | 20        | 0.44%   |
| Dell                              | 19        | 0.42%   |
| Ericsson Business Mobile Networks | 9         | 0.2%    |
| Edimax Technology                 | 9         | 0.2%    |
| NetGear                           | 8         | 0.18%   |
| Qualcomm Atheros Communications   | 7         | 0.15%   |
| Micro Star International          | 5         | 0.11%   |
| Belkin Components                 | 5         | 0.11%   |
| Fibocom                           | 4         | 0.09%   |
| ASUSTek Computer                  | 4         | 0.09%   |
| D-Link                            | 3         | 0.07%   |
| Wacom                             | 2         | 0.04%   |
| Qualcomm Technologies             | 2         | 0.04%   |
| Microsoft                         | 2         | 0.04%   |
| Hewlett-Packard                   | 2         | 0.04%   |
| ZyDAS                             | 1         | 0.02%   |
| Senao                             | 1         | 0.02%   |
| Marvell Technology Group          | 1         | 0.02%   |
| Linksys                           | 1         | 0.02%   |
| InProComm                         | 1         | 0.02%   |
| Fujitsu Siemens Computers         | 1         | 0.02%   |
| Askey Computer                    | 1         | 0.02%   |
| Apple                             | 1         | 0.02%   |
| 3Com                              | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 197       | 4.33%   |
| Intel Wireless 8265 / 8275                                              | 185       | 4.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 184       | 4.05%   |
| Intel Wireless 7265                                                     | 162       | 3.56%   |
| Intel Wireless 7260                                                     | 153       | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 145       | 3.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 144       | 3.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 138       | 3.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 137       | 3.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 121       | 2.66%   |
| Intel Wi-Fi 6 AX201                                                     | 114       | 2.51%   |
| Intel Wireless 8260                                                     | 111       | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 102       | 2.24%   |
| Intel Wireless 3165                                                     | 97        | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 87        | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 77        | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 73        | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                           | 70        | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 68        | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 67        | 1.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 67        | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 64        | 1.41%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 58        | 1.28%   |
| Intel Wireless 3160                                                     | 54        | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 54        | 1.19%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 53        | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 51        | 1.12%   |
| Intel WiFi Link 5100                                                    | 50        | 1.1%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 48        | 1.06%   |
| Intel Centrino Ultimate-N 6300                                          | 48        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 47        | 1.03%   |
| Intel Centrino Advanced-N 6235                                          | 46        | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 42        | 0.92%   |
| Intel Centrino Advanced-N 6200                                          | 42        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 40        | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 39        | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 36        | 0.79%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 32        | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 32        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1734      | 51.29%  |
| Intel                            | 858       | 25.38%  |
| Qualcomm Atheros                 | 219       | 6.48%   |
| Broadcom                         | 183       | 5.41%   |
| Marvell Technology Group         | 94        | 2.78%   |
| ASIX Electronics                 | 43        | 1.27%   |
| DisplayLink                      | 31        | 0.92%   |
| Nvidia                           | 30        | 0.89%   |
| Broadcom Limited                 | 28        | 0.83%   |
| Samsung Electronics              | 23        | 0.68%   |
| Lenovo                           | 23        | 0.68%   |
| JMicron Technology               | 12        | 0.35%   |
| Qualcomm                         | 11        | 0.33%   |
| Silicon Integrated Systems [SiS] | 10        | 0.3%    |
| Huawei Technologies              | 10        | 0.3%    |
| TP-Link                          | 7         | 0.21%   |
| ICS Advent                       | 7         | 0.21%   |
| Google                           | 7         | 0.21%   |
| Xiaomi                           | 5         | 0.15%   |
| OPPO Electronics                 | 5         | 0.15%   |
| OnePlus Technology (Shenzhen)    | 5         | 0.15%   |
| Hewlett-Packard                  | 5         | 0.15%   |
| Attansic Technology              | 5         | 0.15%   |
| VIA Technologies                 | 4         | 0.12%   |
| MediaTek                         | 4         | 0.12%   |
| Apple                            | 4         | 0.12%   |
| Motorola PCS                     | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.06%   |
| Microchip Technology             | 2         | 0.06%   |
| HTC (High Tech Computer)         | 2         | 0.06%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| Research In Motion               | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| ASUSTek Computer                 | 1         | 0.03%   |
| Aquantia                         | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1084      | 31.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 412       | 12.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 183       | 5.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 168       | 4.92%   |
| Intel 82577LM Gigabit Network Connection                               | 70        | 2.05%   |
| Intel Ethernet Connection (4) I219-LM                                  | 69        | 2.02%   |
| Intel Ethernet Connection I218-LM                                      | 65        | 1.9%    |
| Intel Ethernet Connection I219-LM                                      | 49        | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                                  | 48        | 1.41%   |
| Intel Ethernet Connection (4) I219-V                                   | 43        | 1.26%   |
| Intel 82567LM Gigabit Network Connection                               | 43        | 1.26%   |
| Intel Ethernet Connection I217-LM                                      | 42        | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                          | 38        | 1.11%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 37        | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 34        | 1%      |
| Intel Ethernet Connection I219-V                                       | 27        | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 26        | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 25        | 0.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 25        | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 25        | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                      | 21        | 0.62%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 20        | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 20        | 0.59%   |
| Nvidia MCP79 Ethernet                                                  | 20        | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                  | 19        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 18        | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 18        | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                  | 18        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 17        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 17        | 0.5%    |
| Intel Ethernet Connection (6) I219-V                                   | 17        | 0.5%    |
| Intel 82566MM Gigabit Network Connection                               | 15        | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 15        | 0.44%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 15        | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                                  | 14        | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 14        | 0.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 14        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 13        | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 13        | 0.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 13        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4253      | 55.81%  |
| Ethernet | 3267      | 42.87%  |
| Modem    | 93        | 1.22%   |
| Unknown  | 7         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3672      | 81.17%  |
| Ethernet | 852       | 18.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2943      | 68.17%  |
| 1     | 1292      | 29.93%  |
| 0     | 63        | 1.46%   |
| 3     | 18        | 0.42%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3745      | 85.31%  |
| Yes  | 645       | 14.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1688      | 49.21%  |
| Qualcomm Atheros Communications | 293       | 8.54%   |
| Realtek Semiconductor           | 288       | 8.4%    |
| IMC Networks                    | 229       | 6.68%   |
| Broadcom                        | 215       | 6.27%   |
| Apple                           | 122       | 3.56%   |
| Foxconn / Hon Hai               | 119       | 3.47%   |
| Lite-On Technology              | 104       | 3.03%   |
| Dell                            | 77        | 2.24%   |
| Cambridge Silicon Radio         | 67        | 1.95%   |
| Toshiba                         | 63        | 1.84%   |
| Hewlett-Packard                 | 46        | 1.34%   |
| Realtek                         | 24        | 0.7%    |
| Alps Electric                   | 19        | 0.55%   |
| Foxconn International           | 14        | 0.41%   |
| USI                             | 11        | 0.32%   |
| Ralink                          | 11        | 0.32%   |
| ASUSTek Computer                | 8         | 0.23%   |
| Ralink Technology               | 7         | 0.2%    |
| Askey Computer                  | 6         | 0.17%   |
| Taiyo Yuden                     | 5         | 0.15%   |
| Belkin Components               | 5         | 0.15%   |
| MediaTek                        | 2         | 0.06%   |
| TP-Link                         | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 728       | 21.21%  |
| Intel AX201 Bluetooth                               | 291       | 8.48%   |
| Intel AX200 Bluetooth                               | 192       | 5.59%   |
| Realtek Bluetooth Radio                             | 188       | 5.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 173       | 5.04%   |
| IMC Networks Bluetooth Radio                        | 156       | 4.54%   |
| Intel Bluetooth Device                              | 110       | 3.2%    |
| Qualcomm Atheros  Bluetooth Device                  | 109       | 3.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 79        | 2.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 78        | 2.27%   |
| Apple Bluetooth Host Controller                     | 76        | 2.21%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 68        | 1.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 67        | 1.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 59        | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 54        | 1.57%   |
| Broadcom BCM2045B (BDC-2.1)                         | 47        | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 44        | 1.28%   |
| Intel AX210 Bluetooth                               | 44        | 1.28%   |
| Intel Wireless-AC 3168 Bluetooth                    | 40        | 1.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.14%   |
| Apple Bluetooth USB Host Controller                 | 34        | 0.99%   |
| IMC Networks Wireless_Device                        | 31        | 0.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 31        | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 26        | 0.76%   |
| Dell DW375 Bluetooth Module                         | 26        | 0.76%   |
| Realtek Bluetooth Radio                             | 24        | 0.7%    |
| IMC Networks Bluetooth Device                       | 23        | 0.67%   |
| Toshiba Bluetooth Device                            | 22        | 0.64%   |
| Lite-On Bluetooth Device                            | 22        | 0.64%   |
| Lite-On Atheros AR3012 Bluetooth                    | 22        | 0.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 22        | 0.64%   |
| Dell BCM20702A0 Bluetooth Module                    | 21        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 19        | 0.55%   |
| HP Broadcom 2070 Bluetooth Combo                    | 18        | 0.52%   |
| Broadcom HP Portable SoftSailing                    | 16        | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 14        | 0.41%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 0.41%   |
| Toshiba Atheros AR3012 Bluetooth                    | 13        | 0.38%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3415      | 66.6%   |
| AMD                              | 857       | 16.71%  |
| Nvidia                           | 534       | 10.41%  |
| C-Media Electronics              | 39        | 0.76%   |
| Realtek Semiconductor            | 31        | 0.6%    |
| GN Netcom                        | 22        | 0.43%   |
| Plantronics                      | 20        | 0.39%   |
| Lenovo                           | 19        | 0.37%   |
| Texas Instruments                | 14        | 0.27%   |
| Silicon Integrated Systems [SiS] | 12        | 0.23%   |
| Logitech                         | 11        | 0.21%   |
| JMTek                            | 11        | 0.21%   |
| Apple                            | 11        | 0.21%   |
| ASUSTek Computer                 | 9         | 0.18%   |
| Creative Technology              | 8         | 0.16%   |
| Generalplus Technology           | 6         | 0.12%   |
| VIA Technologies                 | 5         | 0.1%    |
| Hewlett-Packard                  | 5         | 0.1%    |
| Focusrite-Novation               | 5         | 0.1%    |
| Corsair                          | 5         | 0.1%    |
| Conexant Systems                 | 5         | 0.1%    |
| SteelSeries ApS                  | 4         | 0.08%   |
| Sennheiser Communications        | 4         | 0.08%   |
| RODE Microphones                 | 4         | 0.08%   |
| Razer USA                        | 4         | 0.08%   |
| Kingston Technology              | 4         | 0.08%   |
| Dell                             | 4         | 0.08%   |
| Blue Microphones                 | 4         | 0.08%   |
| Yamaha                           | 3         | 0.06%   |
| XMOS                             | 3         | 0.06%   |
| Sony                             | 3         | 0.06%   |
| PreSonus Audio Electronics       | 3         | 0.06%   |
| Google                           | 3         | 0.06%   |
| AKAI Professional M.I.           | 3         | 0.06%   |
| Samsung Electronics              | 2         | 0.04%   |
| Native Instruments               | 2         | 0.04%   |
| M-Audio                          | 2         | 0.04%   |
| GYROCOM C&C                      | 2         | 0.04%   |
| FiiO Electronics Technology      | 2         | 0.04%   |
| AudioQuest                       | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 486       | 7.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 374       | 6.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 361       | 5.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 221       | 3.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 214       | 3.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 181       | 2.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 169       | 2.74%   |
| Intel 8 Series HD Audio Controller                                                                | 169       | 2.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 168       | 2.73%   |
| Intel Cannon Lake PCH cAVS                                                                        | 158       | 2.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 157       | 2.55%   |
| Intel Broadwell-U Audio Controller                                                                | 155       | 2.52%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 154       | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 149       | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 143       | 2.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 131       | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 120       | 1.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 118       | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 102       | 1.66%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 102       | 1.66%   |
| AMD Kabini HDMI/DP Audio                                                                          | 95        | 1.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 90        | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 88        | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 87        | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 85        | 1.38%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 82        | 1.33%   |
| Intel Comet Lake PCH cAVS                                                                         | 79        | 1.28%   |
| Intel CM238 HD Audio Controller                                                                   | 74        | 1.2%    |
| AMD High Definition Audio Controller                                                              | 74        | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 73        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 71        | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 63        | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 62        | 1.01%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 55        | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 55        | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 53        | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 51        | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 47        | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 43        | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 41        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 688       | 27.29%  |
| SK hynix            | 621       | 24.63%  |
| Micron Technology   | 337       | 13.37%  |
| Crucial             | 198       | 7.85%   |
| Kingston            | 169       | 6.7%    |
| Unknown             | 167       | 6.62%   |
| Corsair             | 61        | 2.42%   |
| Ramaxel Technology  | 53        | 2.1%    |
| Elpida              | 43        | 1.71%   |
| Nanya Technology    | 36        | 1.43%   |
| A-DATA Technology   | 27        | 1.07%   |
| Unknown (ABCD)      | 23        | 0.91%   |
| Unknown             | 19        | 0.75%   |
| Toshiba             | 6         | 0.24%   |
| Qimonda             | 5         | 0.2%    |
| GSkill              | 4         | 0.16%   |
| GOODRAM             | 4         | 0.16%   |
| Essencore           | 4         | 0.16%   |
| 4ea5                | 4         | 0.16%   |
| Transcend           | 3         | 0.12%   |
| Timetec             | 3         | 0.12%   |
| Patriot             | 3         | 0.12%   |
| Neo Forza           | 3         | 0.12%   |
| ff                  | 3         | 0.12%   |
| ASint Technology    | 3         | 0.12%   |
| Apacer              | 3         | 0.12%   |
| A Force             | 3         | 0.12%   |
| Team                | 2         | 0.08%   |
| SHARETRONIC         | 2         | 0.08%   |
| Innodisk            | 2         | 0.08%   |
| G.Skill             | 2         | 0.08%   |
| fef5                | 2         | 0.08%   |
| V-Color             | 1         | 0.04%   |
| Unknown (F301)      | 1         | 0.04%   |
| Unknown (CB83)      | 1         | 0.04%   |
| Unknown (0B38)      | 1         | 0.04%   |
| Smart               | 1         | 0.04%   |
| OnBoard             | 1         | 0.04%   |
| Miron               | 1         | 0.04%   |
| Memox               | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 50        | 1.87%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 36        | 1.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 28        | 1.05%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 27        | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 26        | 0.97%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 26        | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 26        | 0.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 24        | 0.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 24        | 0.9%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 23        | 0.86%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 22        | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 21        | 0.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 21        | 0.79%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 21        | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 19        | 0.71%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 19        | 0.71%   |
| Unknown                                                             | 19        | 0.71%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 18        | 0.67%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 17        | 0.64%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 16        | 0.6%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 16        | 0.6%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 16        | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 15        | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 15        | 0.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 15        | 0.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 15        | 0.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 14        | 0.52%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 14        | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 14        | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 14        | 0.52%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 13        | 0.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 13        | 0.49%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s             | 13        | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 12        | 0.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 12        | 0.45%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 0.41%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 10        | 0.37%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 0.37%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 10        | 0.37%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 10        | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 956       | 43.91%  |
| DDR3    | 692       | 31.79%  |
| LPDDR4  | 124       | 5.7%    |
| DDR2    | 117       | 5.37%   |
| LPDDR3  | 111       | 5.1%    |
| SDRAM   | 59        | 2.71%   |
| DDR5    | 47        | 2.16%   |
| LPDDR5  | 39        | 1.79%   |
| Unknown | 14        | 0.64%   |
| DDR     | 10        | 0.46%   |
| DRAM    | 8         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1865      | 86.34%  |
| Row Of Chips | 238       | 11.02%  |
| Unknown      | 25        | 1.16%   |
| Chip         | 21        | 0.97%   |
| DIMM         | 11        | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 915       | 38.56%  |
| 4096  | 675       | 28.45%  |
| 16384 | 320       | 13.49%  |
| 2048  | 299       | 12.6%   |
| 1024  | 87        | 3.67%   |
| 32768 | 63        | 2.65%   |
| 512   | 13        | 0.55%   |
| 256   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 501       | 21.52%  |
| 2667    | 459       | 19.72%  |
| 3200    | 364       | 15.64%  |
| 2400    | 161       | 6.92%   |
| 2133    | 135       | 5.8%    |
| 1334    | 94        | 4.04%   |
| 1333    | 68        | 2.92%   |
| 667     | 61        | 2.62%   |
| 1867    | 52        | 2.23%   |
| 4267    | 51        | 2.19%   |
| 4800    | 44        | 1.89%   |
| 1067    | 43        | 1.85%   |
| Unknown | 42        | 1.8%    |
| 6400    | 38        | 1.63%   |
| 800     | 31        | 1.33%   |
| 4199    | 28        | 1.2%    |
| 3266    | 26        | 1.12%   |
| 2048    | 24        | 1.03%   |
| 1066    | 18        | 0.77%   |
| 4266    | 15        | 0.64%   |
| 975     | 11        | 0.47%   |
| 533     | 10        | 0.43%   |
| 1866    | 8         | 0.34%   |
| 3733    | 6         | 0.26%   |
| 8400    | 5         | 0.21%   |
| 5600    | 5         | 0.21%   |
| 333     | 4         | 0.17%   |
| 3000    | 3         | 0.13%   |
| 2933    | 3         | 0.13%   |
| 1639    | 3         | 0.13%   |
| 400     | 3         | 0.13%   |
| 1776    | 2         | 0.09%   |
| 933     | 2         | 0.09%   |
| 7467    | 1         | 0.04%   |
| 5500    | 1         | 0.04%   |
| 3800    | 1         | 0.04%   |
| 1777    | 1         | 0.04%   |
| 1596    | 1         | 0.04%   |
| 1200    | 1         | 0.04%   |
| 666     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Canon                 | 10        | 29.41%  |
| Hewlett-Packard       | 7         | 20.59%  |
| Samsung Electronics   | 4         | 11.76%  |
| Brother Industries    | 4         | 11.76%  |
| Lexmark International | 3         | 8.82%   |
| Prolific Technology   | 2         | 5.88%   |
| STMicroelectronics    | 1         | 2.94%   |
| Seiko Epson           | 1         | 2.94%   |
| Kyocera               | 1         | 2.94%   |
| KODAK                 | 1         | 2.94%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon PIXMA MG3600 Series                                 | 3         | 8.57%   |
| Prolific PL2305 Parallel Port                             | 2         | 5.71%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.86%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 2.86%   |
| Samsung M2020 Series                                      | 1         | 2.86%   |
| Samsung CLX-6260 Series                                   | 1         | 2.86%   |
| Samsung CLP-300 Series                                    | 1         | 2.86%   |
| Samsung C43x Series                                       | 1         | 2.86%   |
| Lexmark International MS610de                             | 1         | 2.86%   |
| Lexmark International C544                                | 1         | 2.86%   |
| Lexmark International 640 Series                          | 1         | 2.86%   |
| Kyocera FS-1041                                           | 1         | 2.86%   |
| KODAK ESP 5 AiO                                           | 1         | 2.86%   |
| HP Officejet 4630 series                                  | 1         | 2.86%   |
| HP LaserJet P2015 series                                  | 1         | 2.86%   |
| HP LaserJet 1010                                          | 1         | 2.86%   |
| HP ENVY Photo 6200 series                                 | 1         | 2.86%   |
| HP ENVY 4520 series                                       | 1         | 2.86%   |
| HP Deskjet 2540 series                                    | 1         | 2.86%   |
| HP Deskjet 1510                                           | 1         | 2.86%   |
| Canon SELPHY CP400                                        | 1         | 2.86%   |
| Canon PIXMA MX490 Series                                  | 1         | 2.86%   |
| Canon PIXMA MG2500 Series                                 | 1         | 2.86%   |
| Canon MF4360-4390                                         | 1         | 2.86%   |
| Canon LiDE 400                                            | 1         | 2.86%   |
| Canon iX6500 series                                       | 1         | 2.86%   |
| Canon iP4800 series                                       | 1         | 2.86%   |
| Canon CanoScan LiDE 300                                   | 1         | 2.86%   |
| Brother PT-9500PC                                         | 1         | 2.86%   |
| Brother MFC-J4540DW                                       | 1         | 2.86%   |
| Brother DCP-L3510CDW                                      | 1         | 2.86%   |
| Brother DCP-7025 Printer                                  | 1         | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 62.5%   |
| Seiko Epson     | 2         | 25%     |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                     | 2         | 25%     |
| Seiko Epson Scanner                         | 1         | 12.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| HP ScanJet 5300c/5370c                      | 1         | 12.5%   |
| Canon CanoScan LiDE 600F                    | 1         | 12.5%   |
| Canon CanoScan LiDE 220                     | 1         | 12.5%   |
| Canon CanoScan LiDE 200                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 930       | 25.22%  |
| Microdia                               | 411       | 11.14%  |
| IMC Networks                           | 326       | 8.84%   |
| Realtek Semiconductor                  | 310       | 8.41%   |
| Sunplus Innovation Technology          | 206       | 5.59%   |
| Bison Electronics                      | 190       | 5.15%   |
| Quanta                                 | 154       | 4.18%   |
| Cheng Uei Precision Industry (Foxlink) | 147       | 3.99%   |
| Suyin                                  | 116       | 3.15%   |
| Lite-On Technology                     | 102       | 2.77%   |
| Apple                                  | 96        | 2.6%    |
| Acer                                   | 86        | 2.33%   |
| Syntek                                 | 84        | 2.28%   |
| Silicon Motion                         | 64        | 1.74%   |
| Logitech                               | 52        | 1.41%   |
| Alcor Micro                            | 50        | 1.36%   |
| Ricoh                                  | 47        | 1.27%   |
| Luxvisions Innotech Limited            | 46        | 1.25%   |
| Lenovo                                 | 42        | 1.14%   |
| Samsung Electronics                    | 20        | 0.54%   |
| Sonix Technology                       | 19        | 0.52%   |
| Z-Star Microelectronics                | 16        | 0.43%   |
| ALi                                    | 16        | 0.43%   |
| Primax Electronics                     | 14        | 0.38%   |
| Microsoft                              | 13        | 0.35%   |
| SunplusIT                              | 11        | 0.3%    |
| Importek                               | 8         | 0.22%   |
| Sunplus Technology                     | 7         | 0.19%   |
| OmniVision Technologies                | 6         | 0.16%   |
| Intel                                  | 6         | 0.16%   |
| Generalplus Technology                 | 6         | 0.16%   |
| DigiTech                               | 6         | 0.16%   |
| GEMBIRD                                | 5         | 0.14%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.11%   |
| Razer USA                              | 4         | 0.11%   |
| ARC International                      | 4         | 0.11%   |
| MacroSilicon                           | 3         | 0.08%   |
| Google                                 | 3         | 0.08%   |
| Genesys Logic                          | 3         | 0.08%   |
| Foxconn / Hon Hai                      | 3         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 204       | 5.5%    |
| Chicony Integrated Camera                               | 172       | 4.64%   |
| Realtek Integrated_Webcam_HD                            | 127       | 3.43%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 96        | 2.59%   |
| IMC Networks Integrated Camera                          | 87        | 2.35%   |
| Chicony HD WebCam                                       | 82        | 2.21%   |
| Sunplus Integrated_Webcam_HD                            | 73        | 1.97%   |
| Chicony TOSHIBA Web Camera - HD                         | 58        | 1.56%   |
| Microdia Integrated Webcam                              | 42        | 1.13%   |
| Chicony HP TrueVision HD Camera                         | 39        | 1.05%   |
| Lite-On Integrated Camera                               | 38        | 1.02%   |
| Syntek Integrated Camera                                | 36        | 0.97%   |
| Chicony USB2.0 Camera                                   | 36        | 0.97%   |
| Bison Integrated Camera                                 | 35        | 0.94%   |
| Apple Built-in iSight                                   | 35        | 0.94%   |
| Realtek USB Camera                                      | 33        | 0.89%   |
| Chicony USB 2.0 Camera                                  | 31        | 0.84%   |
| Chicony HP HD Camera                                    | 31        | 0.84%   |
| Bison BisonCam,NB Pro                                   | 31        | 0.84%   |
| Quanta HD User Facing                                   | 30        | 0.81%   |
| Chicony HP Truevision HD                                | 30        | 0.81%   |
| Chicony Integrated Camera (1280x720@30)                 | 28        | 0.76%   |
| Chicony EasyCamera                                      | 28        | 0.76%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 27        | 0.73%   |
| Acer SunplusIT Integrated Camera                        | 27        | 0.73%   |
| Acer Integrated Camera                                  | 26        | 0.7%    |
| Syntek Lenovo EasyCamera                                | 25        | 0.67%   |
| Chicony VGA Webcam                                      | 25        | 0.67%   |
| Apple FaceTime HD Camera                                | 25        | 0.67%   |
| Alcor Micro USB 2.0 Camera                              | 24        | 0.65%   |
| Bison Lenovo EasyCamera                                 | 23        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 22        | 0.59%   |
| Chicony HP Wide Vision HD Camera                        | 21        | 0.57%   |
| Chicony HD User Facing                                  | 21        | 0.57%   |
| Chicony CNF9055 Toshiba Webcam                          | 21        | 0.57%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 21        | 0.57%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 20        | 0.54%   |
| Quanta HP TrueVision HD Camera                          | 20        | 0.54%   |
| Lenovo Integrated Webcam [R5U877]                       | 20        | 0.54%   |
| Microdia Integrated Webcam HD                           | 19        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 236       | 32.78%  |
| Synaptics                          | 175       | 24.31%  |
| Shenzhen Goodix Technology         | 117       | 16.25%  |
| Upek                               | 57        | 7.92%   |
| AuthenTec                          | 55        | 7.64%   |
| LighTuning Technology              | 34        | 4.72%   |
| Elan Microelectronics              | 26        | 3.61%   |
| STMicroelectronics                 | 15        | 2.08%   |
| Samsung Electronics                | 2         | 0.28%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.28%   |
| Focal-systems.Corp                 | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 60        | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 55        | 7.64%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 47        | 6.53%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 43        | 5.97%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 41        | 5.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 32        | 4.44%   |
| Shenzhen Goodix FingerPrint                                                | 31        | 4.31%   |
| Shenzhen Goodix Fingerprint Reader                                         | 26        | 3.61%   |
| Validity Sensors Synaptics WBDI                                            | 22        | 3.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.64%   |
| Validity Sensors VFS491                                                    | 19        | 2.64%   |
| AuthenTec AES2810                                                          | 16        | 2.22%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 16        | 2.22%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 15        | 2.08%   |
| STMicroelectronics Fingerprint Reader                                      | 15        | 2.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 15        | 2.08%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.94%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.94%   |
| Elan ELAN:Fingerprint                                                      | 14        | 1.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 1.67%   |
| Elan ELAN:ARM-M4                                                           | 12        | 1.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 11        | 1.53%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 1.39%   |
| Synaptics UWP WBDI                                                         | 10        | 1.39%   |
| Unknown                                                                    | 10        | 1.39%   |
| Synaptics UWP WBDI Device                                                  | 9         | 1.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 1.25%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 8         | 1.11%   |
| Synaptics WBDI Device                                                      | 8         | 1.11%   |
| Synaptics  WBDI                                                            | 8         | 1.11%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 1.11%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 6         | 0.83%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 0.83%   |
| AuthenTec AES1600                                                          | 6         | 0.83%   |
| Synaptics WBDI                                                             | 5         | 0.69%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.69%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 199       | 52.51%  |
| Alcor Micro           | 86        | 22.69%  |
| Upek                  | 30        | 7.92%   |
| O2 Micro              | 27        | 7.12%   |
| Lenovo                | 24        | 6.33%   |
| Gemalto (was Gemplus) | 5         | 1.32%   |
| SCM Microsystems      | 3         | 0.79%   |
| Purism, SPC           | 1         | 0.26%   |
| OmniKey               | 1         | 0.26%   |
| Clay Logic            | 1         | 0.26%   |
| Chicony Electronics   | 1         | 0.26%   |
| Cherry                | 1         | 0.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 85        | 22.43%  |
| Broadcom BCM5880 Secure Applications Processor                               | 75        | 19.79%  |
| Broadcom 5880                                                                | 53        | 13.98%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 36        | 9.5%    |
| Broadcom 58200                                                               | 33        | 8.71%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 30        | 7.92%   |
| Lenovo Integrated Smart Card Reader                                          | 23        | 6.07%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 5.8%    |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.32%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.79%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.53%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.53%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.53%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.26%   |
| Purism, SPC Librem Key                                                       | 1         | 0.26%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.26%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.26%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.26%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.26%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.26%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2758      | 62.4%   |
| 1     | 1296      | 29.32%  |
| 2     | 313       | 7.08%   |
| 3     | 40        | 0.9%    |
| 4     | 5         | 0.11%   |
| 5     | 4         | 0.09%   |
| 7     | 2         | 0.05%   |
| 8     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 702       | 34.48%  |
| Graphics card            | 351       | 17.24%  |
| Chipcard                 | 346       | 16.99%  |
| Net/wireless             | 224       | 11%     |
| Multimedia controller    | 127       | 6.24%   |
| Camera                   | 49        | 2.41%   |
| Communication controller | 44        | 2.16%   |
| Bluetooth                | 43        | 2.11%   |
| Storage                  | 42        | 2.06%   |
| Sound                    | 23        | 1.13%   |
| Card reader              | 23        | 1.13%   |
| Net/ethernet             | 18        | 0.88%   |
| Modem                    | 16        | 0.79%   |
| Network                  | 8         | 0.39%   |
| Flash memory             | 8         | 0.39%   |
| Firewire controller      | 5         | 0.25%   |
| Storage/nvme             | 3         | 0.15%   |
| Unassigned class         | 2         | 0.1%    |
| Storage/ide              | 2         | 0.1%    |

