Zorin - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Zorin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin/Desktop/README.md) and [notebooks](/Dist/Zorin/Notebook/README.md).

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

Total: 6700

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | T100HAN                     | Notebook    | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [480ff87a20](https://linux-hardware.org/?probe=480ff87a20) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [b4be9a72dd](https://linux-hardware.org/?probe=b4be9a72dd) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [66e63a311d](https://linux-hardware.org/?probe=66e63a311d) | Feb 28, 2023 |
| HP            | ENVY 17                     | Notebook    | [61d1252ef3](https://linux-hardware.org/?probe=61d1252ef3) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | Notebook    | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
| Google        | Buddy                       | Desktop     | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [d7b51f6048](https://linux-hardware.org/?probe=d7b51f6048) | Feb 27, 2023 |
| AZW           | SER                         | Mini pc     | [e086890e6a](https://linux-hardware.org/?probe=e086890e6a) | Feb 27, 2023 |
| HP            | Pavilion dv7                | Notebook    | [d5da5f62b8](https://linux-hardware.org/?probe=d5da5f62b8) | Feb 27, 2023 |
| Acer          | TravelMate B113             | Notebook    | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [42acb38635](https://linux-hardware.org/?probe=42acb38635) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [e8c76a33fe](https://linux-hardware.org/?probe=e8c76a33fe) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | Vostro 1540                 | Notebook    | [8f09ea4351](https://linux-hardware.org/?probe=8f09ea4351) | Feb 27, 2023 |
| HP            | ENVY m7 Notebook            | Notebook    | [14374fbcc8](https://linux-hardware.org/?probe=14374fbcc8) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | Desktop     | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| HP            | 620                         | Notebook    | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Quanta        | XV1                         | All in one  | [fa596130ae](https://linux-hardware.org/?probe=fa596130ae) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| Dell          | Latitude E6440              | Notebook    | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [7f88a11698](https://linux-hardware.org/?probe=7f88a11698) | Feb 25, 2023 |
| HP            | 2AF7                        | Desktop     | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | Desktop     | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [bafb67390c](https://linux-hardware.org/?probe=bafb67390c) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [3b27d3609f](https://linux-hardware.org/?probe=3b27d3609f) | Feb 24, 2023 |
| HP            | ProBook 4545s               | Notebook    | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| HP            | 2129                        | Desktop     | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [fd80b301db](https://linux-hardware.org/?probe=fd80b301db) | Feb 23, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [294c5c45e6](https://linux-hardware.org/?probe=294c5c45e6) | Feb 23, 2023 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [472721d72c](https://linux-hardware.org/?probe=472721d72c) | Feb 22, 2023 |
| DERE          | V14                         | Notebook    | [bb2d40e676](https://linux-hardware.org/?probe=bb2d40e676) | Feb 22, 2023 |
| HP            | 2129                        | Desktop     | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| HP            | ENVY 17                     | Notebook    | [ea0b2e63ef](https://linux-hardware.org/?probe=ea0b2e63ef) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | Desktop     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [9a9c8192de](https://linux-hardware.org/?probe=9a9c8192de) | Feb 21, 2023 |
| Teclast       | F7                          | Notebook    | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5d32bc7f7c](https://linux-hardware.org/?probe=5d32bc7f7c) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a00e724475](https://linux-hardware.org/?probe=a00e724475) | Feb 21, 2023 |
| HP            | 1850                        | Desktop     | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| Dell          | System XPS L502X            | Notebook    | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| HP            | 620                         | Notebook    | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Dell          | Latitude E5440              | Notebook    | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | Notebook    | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [3c53a60245](https://linux-hardware.org/?probe=3c53a60245) | Feb 19, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| ASUSTek       | Zenbook UX562UG_Q508UG      | Convertible | [2bb870a042](https://linux-hardware.org/?probe=2bb870a042) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | Notebook    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [752cdf5b2b](https://linux-hardware.org/?probe=752cdf5b2b) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| Multilaser    | PC130                       | Notebook    | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | Notebook    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | Notebook    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| HP            | Unknown                     | Notebook    | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | Notebook    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| HP            | ENVY 17                     | Notebook    | [de8af1b249](https://linux-hardware.org/?probe=de8af1b249) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| Medion        | E7220                       | Notebook    | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Google        | Robo                        | Notebook    | [303c72db93](https://linux-hardware.org/?probe=303c72db93) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [b997f44969](https://linux-hardware.org/?probe=b997f44969) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| Quanta        | XV1                         | All in one  | [6c4ea36dc2](https://linux-hardware.org/?probe=6c4ea36dc2) | Feb 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [c08ad0f295](https://linux-hardware.org/?probe=c08ad0f295) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [1189701feb](https://linux-hardware.org/?probe=1189701feb) | Feb 15, 2023 |
| Acer          | Extensa 5230                | Notebook    | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Dell          | Latitude 3320               | Notebook    | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| MSI           | Z370M MORTAR                | Desktop     | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [6c1c0027b1](https://linux-hardware.org/?probe=6c1c0027b1) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Dell          | System XPS L502X            | Notebook    | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [b9301138cc](https://linux-hardware.org/?probe=b9301138cc) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [03123ee601](https://linux-hardware.org/?probe=03123ee601) | Feb 14, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [e271dc0c66](https://linux-hardware.org/?probe=e271dc0c66) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | Notebook    | [a7aa67f64e](https://linux-hardware.org/?probe=a7aa67f64e) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | Notebook    | [eda645cefe](https://linux-hardware.org/?probe=eda645cefe) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | Desktop     | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| Samsung       | 700T1C                      | Notebook    | [66c15f037d](https://linux-hardware.org/?probe=66c15f037d) | Feb 14, 2023 |
| Samsung       | 700T1C                      | Notebook    | [9e154ea3a4](https://linux-hardware.org/?probe=9e154ea3a4) | Feb 14, 2023 |
| MSI           | MS-B9181                    | Desktop     | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [d1edc30dac](https://linux-hardware.org/?probe=d1edc30dac) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [baa5f72e80](https://linux-hardware.org/?probe=baa5f72e80) | Feb 12, 2023 |
| HP            | Notebook                    | Notebook    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [6f7c0f381e](https://linux-hardware.org/?probe=6f7c0f381e) | Feb 12, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [131d5052d1](https://linux-hardware.org/?probe=131d5052d1) | Feb 11, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a789235fe3](https://linux-hardware.org/?probe=a789235fe3) | Feb 11, 2023 |
| HP            | 8054                        | Desktop     | [55c5642509](https://linux-hardware.org/?probe=55c5642509) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [f3919f8d69](https://linux-hardware.org/?probe=f3919f8d69) | Feb 11, 2023 |
| IBM           | 819046G                     | Desktop     | [a43370bbbd](https://linux-hardware.org/?probe=a43370bbbd) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [518f413d2f](https://linux-hardware.org/?probe=518f413d2f) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [a24d7423c4](https://linux-hardware.org/?probe=a24d7423c4) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| Dell          | Latitude E6400              | Notebook    | [8c489c529a](https://linux-hardware.org/?probe=8c489c529a) | Feb 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [5e8a88b237](https://linux-hardware.org/?probe=5e8a88b237) | Feb 11, 2023 |
| ASUSTek       | P5K                         | Desktop     | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| Acer          | TravelMate P253             | Notebook    | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| HONOR         | HLYL-WXX9                   | Notebook    | [9d916e8e03](https://linux-hardware.org/?probe=9d916e8e03) | Feb 10, 2023 |
| Acer          | Aspire 5720                 | Notebook    | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [477eb8ad3c](https://linux-hardware.org/?probe=477eb8ad3c) | Feb 10, 2023 |
| MSI           | GF615M-P31                  | Desktop     | [36dcd2e516](https://linux-hardware.org/?probe=36dcd2e516) | Feb 10, 2023 |
| Acer          | Predator G3-571             | Notebook    | [50fe192ea1](https://linux-hardware.org/?probe=50fe192ea1) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | Notebook    | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [dba0167a53](https://linux-hardware.org/?probe=dba0167a53) | Feb 09, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [ad403b2126](https://linux-hardware.org/?probe=ad403b2126) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [8513e7eb92](https://linux-hardware.org/?probe=8513e7eb92) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [458744c54d](https://linux-hardware.org/?probe=458744c54d) | Feb 09, 2023 |
| Positivo      | Smash2                      | Notebook    | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| Positivo      | Smash2                      | Notebook    | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [dd9b71e8d2](https://linux-hardware.org/?probe=dd9b71e8d2) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | Desktop     | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | Notebook    | [5c9ca6cd47](https://linux-hardware.org/?probe=5c9ca6cd47) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [dd76c764a1](https://linux-hardware.org/?probe=dd76c764a1) | Feb 08, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [e7ee51ecdd](https://linux-hardware.org/?probe=e7ee51ecdd) | Feb 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [0d0c6fe86c](https://linux-hardware.org/?probe=0d0c6fe86c) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| AZW           | GTR V01                     | Mini pc     | [69bc815c6d](https://linux-hardware.org/?probe=69bc815c6d) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | Notebook    | [ae78404854](https://linux-hardware.org/?probe=ae78404854) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | Notebook    | [b2c3e0fa85](https://linux-hardware.org/?probe=b2c3e0fa85) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | Notebook    | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | Desktop     | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [1830edf54c](https://linux-hardware.org/?probe=1830edf54c) | Feb 07, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| Acer          | Okinawa                     | Notebook    | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| TWC           | Unknown                     | Notebook    | [4ea2803396](https://linux-hardware.org/?probe=4ea2803396) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [96f24866e0](https://linux-hardware.org/?probe=96f24866e0) | Feb 06, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Intel         | Unknown                     | Notebook    | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Sony          | VPCEG36FX                   | Notebook    | [d760d9e79b](https://linux-hardware.org/?probe=d760d9e79b) | Feb 06, 2023 |
| Acer          | TravelMate P253             | Notebook    | [050d7b5d68](https://linux-hardware.org/?probe=050d7b5d68) | Feb 06, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [f536be92d0](https://linux-hardware.org/?probe=f536be92d0) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3bba794976](https://linux-hardware.org/?probe=3bba794976) | Feb 05, 2023 |
| Acer          | One S1002                   | Notebook    | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [b3ad379bdc](https://linux-hardware.org/?probe=b3ad379bdc) | Feb 05, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [0de7e3b318](https://linux-hardware.org/?probe=0de7e3b318) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| HP            | 2B47                        | Desktop     | [3db96ac186](https://linux-hardware.org/?probe=3db96ac186) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e5a1cf7284](https://linux-hardware.org/?probe=e5a1cf7284) | Feb 03, 2023 |
| Quanta        | XV1                         | All in one  | [8904f5e7fa](https://linux-hardware.org/?probe=8904f5e7fa) | Feb 03, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| MSI           | B85M-E45                    | Desktop     | [13453f924e](https://linux-hardware.org/?probe=13453f924e) | Feb 03, 2023 |
| Intel         | X58                         | Desktop     | [55a6a5bd82](https://linux-hardware.org/?probe=55a6a5bd82) | Feb 03, 2023 |
| Unknown       | G41 Series                  | Desktop     | [69d4cb64a2](https://linux-hardware.org/?probe=69d4cb64a2) | Feb 03, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [5bfa4ad142](https://linux-hardware.org/?probe=5bfa4ad142) | Feb 02, 2023 |
| HP            | 1825                        | Desktop     | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
| Intel         | Unknown                     | Notebook    | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| HP            | 09F8h                       | Desktop     | [19339c9512](https://linux-hardware.org/?probe=19339c9512) | Feb 02, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [e1da7f708a](https://linux-hardware.org/?probe=e1da7f708a) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| MSI           | Raider GE66 12UHS           | Notebook    | [75e83dae8b](https://linux-hardware.org/?probe=75e83dae8b) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [d221bc6b8d](https://linux-hardware.org/?probe=d221bc6b8d) | Feb 01, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [92f6e450b8](https://linux-hardware.org/?probe=92f6e450b8) | Jan 31, 2023 |
| Dell          | Latitude E6540              | Notebook    | [156a047a82](https://linux-hardware.org/?probe=156a047a82) | Jan 31, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [a663152b7c](https://linux-hardware.org/?probe=a663152b7c) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [ae3838cc5d](https://linux-hardware.org/?probe=ae3838cc5d) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9bb7eb28ed](https://linux-hardware.org/?probe=9bb7eb28ed) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [912213d849](https://linux-hardware.org/?probe=912213d849) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [456415a23e](https://linux-hardware.org/?probe=456415a23e) | Jan 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [f042c5966b](https://linux-hardware.org/?probe=f042c5966b) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1F20... | Notebook    | [39b709296b](https://linux-hardware.org/?probe=39b709296b) | Jan 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | Desktop     | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [56622f5d6c](https://linux-hardware.org/?probe=56622f5d6c) | Jan 29, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| Dell          | Precision 5530              | Notebook    | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [62b104b3d2](https://linux-hardware.org/?probe=62b104b3d2) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [b7cf9bee5c](https://linux-hardware.org/?probe=b7cf9bee5c) | Jan 28, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Dell          | Precision 5530              | Notebook    | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| HP            | 843F                        | Desktop     | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [cf4086f3e4](https://linux-hardware.org/?probe=cf4086f3e4) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| HP            | 2B47                        | Desktop     | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| Dell          | Latitude E7470              | Notebook    | [4245585e75](https://linux-hardware.org/?probe=4245585e75) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| HP            | Notebook                    | Notebook    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [de7bee1cd6](https://linux-hardware.org/?probe=de7bee1cd6) | Jan 26, 2023 |
| Alienware     | M11xR3                      | Notebook    | [634b7f8eb0](https://linux-hardware.org/?probe=634b7f8eb0) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [756bf12bd7](https://linux-hardware.org/?probe=756bf12bd7) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| HP            | 625                         | Notebook    | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Google        | Blorb                       | Notebook    | [adae28c837](https://linux-hardware.org/?probe=adae28c837) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5dfd026f77](https://linux-hardware.org/?probe=5dfd026f77) | Jan 25, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | Notebook    | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [61d7aa3ef9](https://linux-hardware.org/?probe=61d7aa3ef9) | Jan 25, 2023 |
| Google        | Kip                         | Notebook    | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | Notebook    | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [af9518a90a](https://linux-hardware.org/?probe=af9518a90a) | Jan 24, 2023 |
| HP            | 2ADE                        | Desktop     | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [db73b82761](https://linux-hardware.org/?probe=db73b82761) | Jan 24, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [dc93e9d9f0](https://linux-hardware.org/?probe=dc93e9d9f0) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [6fd520f670](https://linux-hardware.org/?probe=6fd520f670) | Jan 23, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [788d350490](https://linux-hardware.org/?probe=788d350490) | Jan 23, 2023 |
| Acer          | RS880M05                    | Desktop     | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f72fec3364](https://linux-hardware.org/?probe=f72fec3364) | Jan 23, 2023 |
| Dell          | Latitude E7470              | Notebook    | [525bcdd915](https://linux-hardware.org/?probe=525bcdd915) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [20b73bd156](https://linux-hardware.org/?probe=20b73bd156) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6d5ca0b2e3](https://linux-hardware.org/?probe=6d5ca0b2e3) | Jan 22, 2023 |
| ASRock        | H61M                        | Desktop     | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| Dell          | Precision M6800             | Notebook    | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| HP            | 625                         | Notebook    | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [25013b14a9](https://linux-hardware.org/?probe=25013b14a9) | Jan 22, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1c3214e8c5](https://linux-hardware.org/?probe=1c3214e8c5) | Jan 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [b47caaf20b](https://linux-hardware.org/?probe=b47caaf20b) | Jan 22, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [1707a21fed](https://linux-hardware.org/?probe=1707a21fed) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | Notebook    | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| HP            | 625                         | Notebook    | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [548d331968](https://linux-hardware.org/?probe=548d331968) | Jan 21, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| Timi          | Mi Notebook Pro             | Notebook    | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| HP            | 89B5 A                      | Desktop     | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [f3af245bf8](https://linux-hardware.org/?probe=f3af245bf8) | Jan 20, 2023 |
| HP            | 843F                        | Desktop     | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| ASUSTek       | A6U                         | Notebook    | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | Notebook    | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | Desktop     | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| HP            | 843F                        | Desktop     | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| HP            | ProBook 4740s               | Notebook    | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | Desktop     | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [f3ab78c392](https://linux-hardware.org/?probe=f3ab78c392) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [4908236396](https://linux-hardware.org/?probe=4908236396) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [9e17ffeecc](https://linux-hardware.org/?probe=9e17ffeecc) | Jan 19, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [cfe9a9d924](https://linux-hardware.org/?probe=cfe9a9d924) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | 15                          | Notebook    | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| HP            | 3397                        | Desktop     | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d87fb3cf65](https://linux-hardware.org/?probe=d87fb3cf65) | Jan 17, 2023 |
| Fujitsu       | LIFEBOOK T726               | Convertible | [ab8e5c3c70](https://linux-hardware.org/?probe=ab8e5c3c70) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [473ae331ec](https://linux-hardware.org/?probe=473ae331ec) | Jan 16, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Wortmann      | Mobile 1524                 | Notebook    | [17fc7e2f75](https://linux-hardware.org/?probe=17fc7e2f75) | Jan 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | Desktop     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f4232dc72a](https://linux-hardware.org/?probe=f4232dc72a) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Alienware     | 2                           | Desktop     | [97c74c0c7b](https://linux-hardware.org/?probe=97c74c0c7b) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| Sony          | VGN-SR16GN_B                | Notebook    | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| Tactus        | GeoPad 110                  | Tablet      | [810d937888](https://linux-hardware.org/?probe=810d937888) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [331b5e3efa](https://linux-hardware.org/?probe=331b5e3efa) | Jan 14, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [e5ab68f182](https://linux-hardware.org/?probe=e5ab68f182) | Jan 14, 2023 |
| Dell          | 0F0TGN A00                  | Desktop     | [38a44bb08b](https://linux-hardware.org/?probe=38a44bb08b) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | Notebook    | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| HP            | 18E7                        | Desktop     | [3acf05bf4e](https://linux-hardware.org/?probe=3acf05bf4e) | Jan 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [19531b68b1](https://linux-hardware.org/?probe=19531b68b1) | Jan 14, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [941c62872e](https://linux-hardware.org/?probe=941c62872e) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | Notebook    | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [845fca1774](https://linux-hardware.org/?probe=845fca1774) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | Notebook    | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [ddf679df3a](https://linux-hardware.org/?probe=ddf679df3a) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| Dell          | 0F0TGN A00                  | Desktop     | [dc548d070e](https://linux-hardware.org/?probe=dc548d070e) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | Notebook    | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [250b4a09a0](https://linux-hardware.org/?probe=250b4a09a0) | Jan 13, 2023 |
| HP            | 3397                        | Desktop     | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | Desktop     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | Notebook    | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [3d1b3bf218](https://linux-hardware.org/?probe=3d1b3bf218) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| GPU Compan... | GWTC116-2                   | Convertible | [a1c1965381](https://linux-hardware.org/?probe=a1c1965381) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| Acer          | Aspire 2920                 | Notebook    | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [78eb96d148](https://linux-hardware.org/?probe=78eb96d148) | Jan 11, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [9dfcb68d9a](https://linux-hardware.org/?probe=9dfcb68d9a) | Jan 11, 2023 |
| Wortmann      | TERRA_MOBILE_1062           | Tablet      | [d363c969bc](https://linux-hardware.org/?probe=d363c969bc) | Jan 10, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [fd9ae626c7](https://linux-hardware.org/?probe=fd9ae626c7) | Jan 10, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [8c41599fdd](https://linux-hardware.org/?probe=8c41599fdd) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d482768ec9](https://linux-hardware.org/?probe=d482768ec9) | Jan 09, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| Dell          | Latitude E6510              | Notebook    | [28cceb82e3](https://linux-hardware.org/?probe=28cceb82e3) | Jan 09, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [a8f14a8a8e](https://linux-hardware.org/?probe=a8f14a8a8e) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5bd32eb6f6](https://linux-hardware.org/?probe=5bd32eb6f6) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [88ba7d805e](https://linux-hardware.org/?probe=88ba7d805e) | Jan 08, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [b5b4c3f6ef](https://linux-hardware.org/?probe=b5b4c3f6ef) | Jan 08, 2023 |
| HP            | 2129                        | Desktop     | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |
| MSI           | CR62 6M                     | Notebook    | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| Sony          | VAIO                        | All in one  | [1f521568e1](https://linux-hardware.org/?probe=1f521568e1) | Jan 07, 2023 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [f3e00dc862](https://linux-hardware.org/?probe=f3e00dc862) | Jan 07, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [4c680e9948](https://linux-hardware.org/?probe=4c680e9948) | Jan 07, 2023 |
| HP            | Laptop 17-cp1xxx            | Notebook    | [d699356fd1](https://linux-hardware.org/?probe=d699356fd1) | Jan 07, 2023 |
| Standard      | X50-V2                      | Desktop     | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| HP            | 2B47                        | Desktop     | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [cc8d4f6e6d](https://linux-hardware.org/?probe=cc8d4f6e6d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [393397e25c](https://linux-hardware.org/?probe=393397e25c) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [76f452827f](https://linux-hardware.org/?probe=76f452827f) | Jan 06, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [6148bc3313](https://linux-hardware.org/?probe=6148bc3313) | Jan 06, 2023 |
| Multilaser    | PC024                       | Notebook    | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | Notebook    | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Multilaser    | PC024                       | Notebook    | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| Dell          | Precision M90               | Notebook    | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | ProBook 4540s               | Notebook    | [6e2638a12e](https://linux-hardware.org/?probe=6e2638a12e) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | Notebook    | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [4ec59dca55](https://linux-hardware.org/?probe=4ec59dca55) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | Notebook    | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [e597f176c2](https://linux-hardware.org/?probe=e597f176c2) | Jan 03, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [309e449325](https://linux-hardware.org/?probe=309e449325) | Jan 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [9ba9bcee90](https://linux-hardware.org/?probe=9ba9bcee90) | Jan 03, 2023 |
| Foxconn       | H67S/H61SP                  | Desktop     | [c7684d1f93](https://linux-hardware.org/?probe=c7684d1f93) | Jan 03, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [ce3dc1998f](https://linux-hardware.org/?probe=ce3dc1998f) | Jan 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [fcf5d132a5](https://linux-hardware.org/?probe=fcf5d132a5) | Jan 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f31ae01428](https://linux-hardware.org/?probe=f31ae01428) | Jan 02, 2023 |
| HP            | 8350                        | Desktop     | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| ASUSTek       | D300TA                      | Desktop     | [f522fa7b4d](https://linux-hardware.org/?probe=f522fa7b4d) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | Notebook    | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| Dell          | Latitude E5440              | Notebook    | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0360bb01d0](https://linux-hardware.org/?probe=0360bb01d0) | Jan 01, 2023 |
| Dell          | Latitude E5500              | Notebook    | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | Notebook    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | Notebook    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| HOUTER        | IPMIP-GS                    | Desktop     | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| HP            | Pavilion dv6                | Notebook    | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
| Biostar       | TA970                       | Desktop     | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | 03KWTV A02                  | Desktop     | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| HP            | 2AF7                        | Desktop     | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [b65d5ce654](https://linux-hardware.org/?probe=b65d5ce654) | Dec 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [71c1ee486e](https://linux-hardware.org/?probe=71c1ee486e) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [2fe0a7fe8b](https://linux-hardware.org/?probe=2fe0a7fe8b) | Dec 27, 2022 |
| Acer          | Aspire XC-780               | Desktop     | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [052cdcd8bb](https://linux-hardware.org/?probe=052cdcd8bb) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [940218d084](https://linux-hardware.org/?probe=940218d084) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | Notebook    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | Notebook    | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [1ba51900a6](https://linux-hardware.org/?probe=1ba51900a6) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| HP            | 2AF7                        | Desktop     | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | Desktop     | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | Notebook    | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1c2f8d9457](https://linux-hardware.org/?probe=1c2f8d9457) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [e968a4fe6d](https://linux-hardware.org/?probe=e968a4fe6d) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2415ad5980](https://linux-hardware.org/?probe=2415ad5980) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [9bcea5d857](https://linux-hardware.org/?probe=9bcea5d857) | Dec 24, 2022 |
| HP            | Pavilion dv7                | Notebook    | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| Intel         | H61                         | Desktop     | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | Pavilion g7                 | Notebook    | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| HP            | 2AF7                        | Desktop     | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [3e8fb581f0](https://linux-hardware.org/?probe=3e8fb581f0) | Dec 23, 2022 |
| HP            | 2AF7                        | Desktop     | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [bb9724d53f](https://linux-hardware.org/?probe=bb9724d53f) | Dec 23, 2022 |
| Dell          | Latitude E4310              | Notebook    | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| ASRock        | G31M-S                      | Desktop     | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [cb9ec3d5ad](https://linux-hardware.org/?probe=cb9ec3d5ad) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [bfdc9d1e12](https://linux-hardware.org/?probe=bfdc9d1e12) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [79aabf81c4](https://linux-hardware.org/?probe=79aabf81c4) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | Desktop     | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | G31M-S                      | Desktop     | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [3caae1ba3b](https://linux-hardware.org/?probe=3caae1ba3b) | Dec 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | Desktop     | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| Sony          | VJZ13A                      | Notebook    | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| HP            | 09CCh                       | Desktop     | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Dell          | 0MGK50 A04                  | Desktop     | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [5212fb0d93](https://linux-hardware.org/?probe=5212fb0d93) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [9f456f73eb](https://linux-hardware.org/?probe=9f456f73eb) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0e5b8434fe](https://linux-hardware.org/?probe=0e5b8434fe) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| MSI           | MS-1035                     | Notebook    | [6a8a6b7de4](https://linux-hardware.org/?probe=6a8a6b7de4) | Dec 19, 2022 |
| GPD           | G1619-04                    | Notebook    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| HP            | 8715                        | Mini pc     | [a6f7705fd4](https://linux-hardware.org/?probe=a6f7705fd4) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [0d5c4254b7](https://linux-hardware.org/?probe=0d5c4254b7) | Dec 19, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [20b69069fa](https://linux-hardware.org/?probe=20b69069fa) | Dec 18, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [7064963568](https://linux-hardware.org/?probe=7064963568) | Dec 18, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [55cf134a8b](https://linux-hardware.org/?probe=55cf134a8b) | Dec 18, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d12b0d42fc](https://linux-hardware.org/?probe=d12b0d42fc) | Dec 17, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [e64e0ee27a](https://linux-hardware.org/?probe=e64e0ee27a) | Dec 17, 2022 |
| Fusion5       | C60Bv2-128GB                | Notebook    | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [be98ae95c3](https://linux-hardware.org/?probe=be98ae95c3) | Dec 17, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| HP            | Compaq 6910p (RM231UT#AB... | Notebook    | [4653b4877b](https://linux-hardware.org/?probe=4653b4877b) | Dec 17, 2022 |
| HP            | 250 G1                      | Notebook    | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [010f6841e5](https://linux-hardware.org/?probe=010f6841e5) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [53ae51748b](https://linux-hardware.org/?probe=53ae51748b) | Dec 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [bbae74f641](https://linux-hardware.org/?probe=bbae74f641) | Dec 17, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [396db83818](https://linux-hardware.org/?probe=396db83818) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | Notebook    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [255499abee](https://linux-hardware.org/?probe=255499abee) | Dec 17, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [1a8c883ac5](https://linux-hardware.org/?probe=1a8c883ac5) | Dec 16, 2022 |
| Toshiba       | Satellite P500              | Notebook    | [58163fa1d7](https://linux-hardware.org/?probe=58163fa1d7) | Dec 16, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | Desktop     | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ced1979abf](https://linux-hardware.org/?probe=ced1979abf) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| Google        | Blorb                       | Notebook    | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| HP            | 8750                        | Desktop     | [a4911352d1](https://linux-hardware.org/?probe=a4911352d1) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | Notebook    | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Machcreato... | 14                          | Notebook    | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [827fabbd5f](https://linux-hardware.org/?probe=827fabbd5f) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [34611b96d0](https://linux-hardware.org/?probe=34611b96d0) | Dec 15, 2022 |
| ASUSTek       | P5PL2-E                     | Desktop     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS2AN00    | Notebook    | [7db77c4fcd](https://linux-hardware.org/?probe=7db77c4fcd) | Dec 14, 2022 |
| Lenovo        | ThinkPad Helix 2nd 20CG0... | Tablet      | [e32ae95f08](https://linux-hardware.org/?probe=e32ae95f08) | Dec 14, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [3339909881](https://linux-hardware.org/?probe=3339909881) | Dec 14, 2022 |
| MSI           | MS-B9071                    | Desktop     | [fc31fe11a2](https://linux-hardware.org/?probe=fc31fe11a2) | Dec 14, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [1e8031daad](https://linux-hardware.org/?probe=1e8031daad) | Dec 13, 2022 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [c8c56f3e93](https://linux-hardware.org/?probe=c8c56f3e93) | Dec 13, 2022 |
| HP            | 1905                        | Desktop     | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| AZW           | GTR V01                     | Mini pc     | [7cae9d407c](https://linux-hardware.org/?probe=7cae9d407c) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | Desktop     | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| AZW           | GTR V01                     | Mini pc     | [9f1097843c](https://linux-hardware.org/?probe=9f1097843c) | Dec 12, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [09b233d518](https://linux-hardware.org/?probe=09b233d518) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [45ad14cbc2](https://linux-hardware.org/?probe=45ad14cbc2) | Dec 12, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [bc16110ca8](https://linux-hardware.org/?probe=bc16110ca8) | Dec 12, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [477bcdd546](https://linux-hardware.org/?probe=477bcdd546) | Dec 12, 2022 |
| Alienware     | 18                          | Notebook    | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Biostar       | A520MH                      | Desktop     | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Sony          | VGN-NR32M_S                 | Notebook    | [f37234d095](https://linux-hardware.org/?probe=f37234d095) | Dec 10, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [097b783ae5](https://linux-hardware.org/?probe=097b783ae5) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0f4312c32e](https://linux-hardware.org/?probe=0f4312c32e) | Dec 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3e0d5dc490](https://linux-hardware.org/?probe=3e0d5dc490) | Dec 09, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [fbbd6a06c8](https://linux-hardware.org/?probe=fbbd6a06c8) | Dec 09, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [69e83bcd80](https://linux-hardware.org/?probe=69e83bcd80) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [30bbadcb93](https://linux-hardware.org/?probe=30bbadcb93) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [3258bb06ef](https://linux-hardware.org/?probe=3258bb06ef) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| HP            | 82FE 11                     | Desktop     | [6bf35b7005](https://linux-hardware.org/?probe=6bf35b7005) | Dec 08, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [54eaa6d2f3](https://linux-hardware.org/?probe=54eaa6d2f3) | Dec 07, 2022 |
| Dell          | Latitude 7490               | Notebook    | [6021de66f0](https://linux-hardware.org/?probe=6021de66f0) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [1c99985945](https://linux-hardware.org/?probe=1c99985945) | Dec 07, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| MSI           | K9A2 Platinum               | Desktop     | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8442e3381c](https://linux-hardware.org/?probe=8442e3381c) | Dec 06, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2b29482df2](https://linux-hardware.org/?probe=2b29482df2) | Dec 06, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [f8e7b50548](https://linux-hardware.org/?probe=f8e7b50548) | Dec 06, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [a4029fd324](https://linux-hardware.org/?probe=a4029fd324) | Dec 06, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [a28616ab1b](https://linux-hardware.org/?probe=a28616ab1b) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [5132e1aba1](https://linux-hardware.org/?probe=5132e1aba1) | Dec 05, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| HP            | 8350                        | Desktop     | [f7768016d5](https://linux-hardware.org/?probe=f7768016d5) | Dec 05, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [586b9fe0a6](https://linux-hardware.org/?probe=586b9fe0a6) | Dec 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [9775fe7147](https://linux-hardware.org/?probe=9775fe7147) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [d5ba349e44](https://linux-hardware.org/?probe=d5ba349e44) | Dec 04, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9a547affad](https://linux-hardware.org/?probe=9a547affad) | Dec 04, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [0e270ccc80](https://linux-hardware.org/?probe=0e270ccc80) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | Desktop     | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | K9A2 Platinum               | Desktop     | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| HP            | 2AE2                        | Desktop     | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| MSI           | B75A-G41                    | Desktop     | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [e74106a982](https://linux-hardware.org/?probe=e74106a982) | Dec 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [26e6a987d0](https://linux-hardware.org/?probe=26e6a987d0) | Dec 03, 2022 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [dba5f63d66](https://linux-hardware.org/?probe=dba5f63d66) | Dec 03, 2022 |
| HP            | Pavilion g4                 | Notebook    | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| Biostar       | TPower X58                  | Desktop     | [320769fceb](https://linux-hardware.org/?probe=320769fceb) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [686afd3c20](https://linux-hardware.org/?probe=686afd3c20) | Dec 02, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [71b49e89e9](https://linux-hardware.org/?probe=71b49e89e9) | Dec 02, 2022 |
| AZW           | U59                         | Desktop     | [6a7c9cb905](https://linux-hardware.org/?probe=6a7c9cb905) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | Notebook    | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| NZXT          | N7 Z590                     | Desktop     | [cc56e65209](https://linux-hardware.org/?probe=cc56e65209) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| MSI           | G41M-S03                    | Desktop     | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [7f91a09589](https://linux-hardware.org/?probe=7f91a09589) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | Notebook    | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| HP            | 8433 11                     | Desktop     | [01f9a28da3](https://linux-hardware.org/?probe=01f9a28da3) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [ab421fd2d4](https://linux-hardware.org/?probe=ab421fd2d4) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [4f517e816d](https://linux-hardware.org/?probe=4f517e816d) | Dec 01, 2022 |
| Dell          | Latitude E5520              | Notebook    | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| Dell          | Studio 1558                 | Notebook    | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e214cb1bb9](https://linux-hardware.org/?probe=e214cb1bb9) | Nov 30, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [9d6aeff37c](https://linux-hardware.org/?probe=9d6aeff37c) | Nov 30, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Dell          | Latitude E6540              | Notebook    | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| Gateway       | SX2851                      | Desktop     | [b408695def](https://linux-hardware.org/?probe=b408695def) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| HOUTER        | IPMIP-GS                    | Desktop     | [cbc472e6df](https://linux-hardware.org/?probe=cbc472e6df) | Nov 28, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c4bbe90221](https://linux-hardware.org/?probe=c4bbe90221) | Nov 28, 2022 |
| Dell          | System XPS L502X            | Notebook    | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [3dd83d6d9d](https://linux-hardware.org/?probe=3dd83d6d9d) | Nov 27, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [47782768eb](https://linux-hardware.org/?probe=47782768eb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | Notebook    | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [eda49557ae](https://linux-hardware.org/?probe=eda49557ae) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [6867d8eeaf](https://linux-hardware.org/?probe=6867d8eeaf) | Nov 27, 2022 |
| Dell          | Studio 1558                 | Notebook    | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | Notebook    | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | Desktop     | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [c26e52327e](https://linux-hardware.org/?probe=c26e52327e) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [def104dd7d](https://linux-hardware.org/?probe=def104dd7d) | Nov 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [5e51349002](https://linux-hardware.org/?probe=5e51349002) | Nov 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [f70a6fa6ae](https://linux-hardware.org/?probe=f70a6fa6ae) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [2eb5cc0a12](https://linux-hardware.org/?probe=2eb5cc0a12) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [c0102f2633](https://linux-hardware.org/?probe=c0102f2633) | Nov 25, 2022 |
| ASUSTek       | X202E                       | Notebook    | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | Notebook    | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Toshiba       | Satellite C50D-B            | Notebook    | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| HP            | ENVY m6                     | Notebook    | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 18E7                        | Desktop     | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2c7485441f](https://linux-hardware.org/?probe=2c7485441f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | Notebook    | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [e49d5c5f9d](https://linux-hardware.org/?probe=e49d5c5f9d) | Nov 24, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [6bcefa911d](https://linux-hardware.org/?probe=6bcefa911d) | Nov 24, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | Notebook    | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| ASRock        | FP6D4-P1                    | Desktop     | [5e52f1b520](https://linux-hardware.org/?probe=5e52f1b520) | Nov 24, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Toshiba       | Satellite S55t-B            | Notebook    | [4b01021314](https://linux-hardware.org/?probe=4b01021314) | Nov 24, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [51f3e71650](https://linux-hardware.org/?probe=51f3e71650) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| HP            | Notebook                    | Notebook    | [d65b0a06fe](https://linux-hardware.org/?probe=d65b0a06fe) | Nov 24, 2022 |
| HP            | Notebook                    | Notebook    | [54b351457e](https://linux-hardware.org/?probe=54b351457e) | Nov 24, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a41bb9177a](https://linux-hardware.org/?probe=a41bb9177a) | Nov 23, 2022 |
| HP            | 15                          | Notebook    | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [5357d43f13](https://linux-hardware.org/?probe=5357d43f13) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| Intel         | D946GZAB AAD66610-302       | Desktop     | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [7a2c8b647d](https://linux-hardware.org/?probe=7a2c8b647d) | Nov 22, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | Notebook    | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| HP            | 8184 X4                     | Desktop     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| HP            | 822A                        | Desktop     | [b464dc4cf0](https://linux-hardware.org/?probe=b464dc4cf0) | Nov 21, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Acer          | Veriton N4640G              | Desktop     | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [41cca3d850](https://linux-hardware.org/?probe=41cca3d850) | Nov 20, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [87f2179621](https://linux-hardware.org/?probe=87f2179621) | Nov 20, 2022 |
| Framework     | Laptop                      | Notebook    | [6cc495c0d9](https://linux-hardware.org/?probe=6cc495c0d9) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | Notebook    | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [77dcd3bef6](https://linux-hardware.org/?probe=77dcd3bef6) | Nov 19, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| Acer          | FX58M                       | Desktop     | [837da7d885](https://linux-hardware.org/?probe=837da7d885) | Nov 19, 2022 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [c92c0834ef](https://linux-hardware.org/?probe=c92c0834ef) | Nov 19, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [a7c034bd91](https://linux-hardware.org/?probe=a7c034bd91) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [4148292f4d](https://linux-hardware.org/?probe=4148292f4d) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [0185c349b9](https://linux-hardware.org/?probe=0185c349b9) | Nov 18, 2022 |
| HP            | 14                          | Notebook    | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [6992e11b21](https://linux-hardware.org/?probe=6992e11b21) | Nov 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [31752fdaa8](https://linux-hardware.org/?probe=31752fdaa8) | Nov 18, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| HP            | 14                          | Notebook    | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [ef7af01d47](https://linux-hardware.org/?probe=ef7af01d47) | Nov 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [ceca708c95](https://linux-hardware.org/?probe=ceca708c95) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| Dell          | 0C27VV A02                  | Desktop     | [5f4b4b8571](https://linux-hardware.org/?probe=5f4b4b8571) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [522c9222c5](https://linux-hardware.org/?probe=522c9222c5) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [23f8c23e8b](https://linux-hardware.org/?probe=23f8c23e8b) | Nov 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| MSI           | 2AE0                        | Desktop     | [c0d9e23faa](https://linux-hardware.org/?probe=c0d9e23faa) | Nov 16, 2022 |
| MSI           | H81M-P33                    | Desktop     | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| Gateway       | NV59C                       | Notebook    | [b3be978b72](https://linux-hardware.org/?probe=b3be978b72) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | Notebook    | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| HP            | 0AA4h                       | Desktop     | [328259669b](https://linux-hardware.org/?probe=328259669b) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [d1e60135e1](https://linux-hardware.org/?probe=d1e60135e1) | Nov 15, 2022 |
| HP            | 18E7                        | Desktop     | [7ecd6a2f37](https://linux-hardware.org/?probe=7ecd6a2f37) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [b240ae5338](https://linux-hardware.org/?probe=b240ae5338) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [d1049db1fb](https://linux-hardware.org/?probe=d1049db1fb) | Nov 15, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [73bc7e7428](https://linux-hardware.org/?probe=73bc7e7428) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [9d798077df](https://linux-hardware.org/?probe=9d798077df) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [5d1cf4ca11](https://linux-hardware.org/?probe=5d1cf4ca11) | Nov 14, 2022 |
| Microtech     | ebookLite                   | Notebook    | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| Acer          | Extensa 2530                | Notebook    | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [4ce82dba3d](https://linux-hardware.org/?probe=4ce82dba3d) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| HP            | 1850                        | Desktop     | [0b5e36c27b](https://linux-hardware.org/?probe=0b5e36c27b) | Nov 13, 2022 |
| Hampoo        | Cherry Trail CR             | Notebook    | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [1c7b3f934d](https://linux-hardware.org/?probe=1c7b3f934d) | Nov 12, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | Desktop     | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| HP            | 250 G4                      | Notebook    | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| HP            | 250 G4                      | Notebook    | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| JGINYUE       | X79M-PLUS V2.3              | Desktop     | [8dac2a9292](https://linux-hardware.org/?probe=8dac2a9292) | Nov 12, 2022 |
| Microtech     | ebookLite                   | Notebook    | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | Notebook    | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Unknown       | 775i65G                     | Desktop     | [b872a779af](https://linux-hardware.org/?probe=b872a779af) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [16247a3667](https://linux-hardware.org/?probe=16247a3667) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [bc5562e288](https://linux-hardware.org/?probe=bc5562e288) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Biostar       | TPower X58                  | Desktop     | [8662697d27](https://linux-hardware.org/?probe=8662697d27) | Nov 11, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [2e79d44f43](https://linux-hardware.org/?probe=2e79d44f43) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [1f9e0a7e16](https://linux-hardware.org/?probe=1f9e0a7e16) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [d3a6ca47df](https://linux-hardware.org/?probe=d3a6ca47df) | Nov 11, 2022 |
| HP            | 2000                        | Notebook    | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Microtech     | ebookLite                   | Notebook    | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| ASUSTek       | G50VT                       | Notebook    | [57f7e69b18](https://linux-hardware.org/?probe=57f7e69b18) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [bb4dff706b](https://linux-hardware.org/?probe=bb4dff706b) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b7619dbd72](https://linux-hardware.org/?probe=b7619dbd72) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fb2770f137](https://linux-hardware.org/?probe=fb2770f137) | Nov 10, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [cf64038190](https://linux-hardware.org/?probe=cf64038190) | Nov 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c17772f8e7](https://linux-hardware.org/?probe=c17772f8e7) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | Notebook    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [5d6f34affd](https://linux-hardware.org/?probe=5d6f34affd) | Nov 08, 2022 |
| Gateway       | ML6732                      | Notebook    | [7889349228](https://linux-hardware.org/?probe=7889349228) | Nov 08, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Linx          | LINX1010B                   | Notebook    | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | Notebook    | [185c483599](https://linux-hardware.org/?probe=185c483599) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| ASUSTek       | U36SD                       | Notebook    | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| ASUSTek       | F5V                         | Notebook    | [877e968b61](https://linux-hardware.org/?probe=877e968b61) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [e44a807758](https://linux-hardware.org/?probe=e44a807758) | Nov 06, 2022 |
| Acer          | H81H3-M4                    | Desktop     | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | Notebook    | [d763771ba6](https://linux-hardware.org/?probe=d763771ba6) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [31caaec976](https://linux-hardware.org/?probe=31caaec976) | Nov 05, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [e14cb334c4](https://linux-hardware.org/?probe=e14cb334c4) | Nov 05, 2022 |
| HP            | 1790                        | Desktop     | [8916928344](https://linux-hardware.org/?probe=8916928344) | Nov 05, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| HP            | 1790                        | Desktop     | [1de8a8af0d](https://linux-hardware.org/?probe=1de8a8af0d) | Nov 05, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| Dell          | 0C27VV A02                  | Desktop     | [fb4c1f85a2](https://linux-hardware.org/?probe=fb4c1f85a2) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| BANGHO        | W240HU/W250HUQ              | Notebook    | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c796c2f9ee](https://linux-hardware.org/?probe=c796c2f9ee) | Nov 03, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [baf6b79b85](https://linux-hardware.org/?probe=baf6b79b85) | Nov 03, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [30cd9b0d29](https://linux-hardware.org/?probe=30cd9b0d29) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| Microtech     | CoreBook                    | Notebook    | [1276c24890](https://linux-hardware.org/?probe=1276c24890) | Nov 03, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [920c4567d3](https://linux-hardware.org/?probe=920c4567d3) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [df00a6281b](https://linux-hardware.org/?probe=df00a6281b) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [2ec155a4b6](https://linux-hardware.org/?probe=2ec155a4b6) | Nov 03, 2022 |
| Dell          | Latitude E6540              | Notebook    | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [56767f430b](https://linux-hardware.org/?probe=56767f430b) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [b1ffa94d76](https://linux-hardware.org/?probe=b1ffa94d76) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [609ccd3204](https://linux-hardware.org/?probe=609ccd3204) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [7c6ddf22b5](https://linux-hardware.org/?probe=7c6ddf22b5) | Nov 02, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [a7fb2c2163](https://linux-hardware.org/?probe=a7fb2c2163) | Nov 02, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [005b25ef06](https://linux-hardware.org/?probe=005b25ef06) | Nov 02, 2022 |
| Gigabyte      | P55-UD6                     | Desktop     | [2898ec20b3](https://linux-hardware.org/?probe=2898ec20b3) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | Desktop     | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| HP            | 2B3B                        | All in one  | [a42ac6f6c7](https://linux-hardware.org/?probe=a42ac6f6c7) | Nov 01, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [99ab599fbc](https://linux-hardware.org/?probe=99ab599fbc) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| Dell          | Latitude E6500              | Notebook    | [b7be8c3204](https://linux-hardware.org/?probe=b7be8c3204) | Oct 31, 2022 |
| Dell          | Latitude E6500              | Notebook    | [cb3b467ba8](https://linux-hardware.org/?probe=cb3b467ba8) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| HP            | 1790                        | Desktop     | [6dc2cef5ea](https://linux-hardware.org/?probe=6dc2cef5ea) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| Seco          | C40 C                       | Desktop     | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| HP            | 2000                        | Notebook    | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | Notebook    | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | Notebook    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d8f6faad10](https://linux-hardware.org/?probe=d8f6faad10) | Oct 30, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [75dcd27c77](https://linux-hardware.org/?probe=75dcd27c77) | Oct 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Zorin 16 | 2664      | 59.66%  |
| Zorin 15 | 1605      | 35.95%  |
| Zorin 12 | 196       | 4.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Zorin | 4451      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 199       | 3.96%   |
| 5.11.0-38-generic | 178       | 3.54%   |
| 5.11.0-27-generic | 154       | 3.06%   |
| 5.15.0-46-generic | 152       | 3.02%   |
| 5.15.0-58-generic | 147       | 2.92%   |
| 5.15.0-52-generic | 143       | 2.84%   |
| 5.13.0-30-generic | 125       | 2.49%   |
| 5.11.0-40-generic | 124       | 2.47%   |
| 5.13.0-39-generic | 120       | 2.39%   |
| 5.3.0-40-generic  | 110       | 2.19%   |
| 5.11.0-41-generic | 107       | 2.13%   |
| 5.11.0-37-generic | 107       | 2.13%   |
| 5.11.0-43-generic | 101       | 2.01%   |
| 5.4.0-42-generic  | 99        | 1.97%   |
| 5.15.0-48-generic | 95        | 1.89%   |
| 5.11.0-34-generic | 94        | 1.87%   |
| 5.15.0-60-generic | 90        | 1.79%   |
| 5.13.0-40-generic | 89        | 1.77%   |
| 5.0.0-37-generic  | 79        | 1.57%   |
| 5.15.0-53-generic | 78        | 1.55%   |
| 5.13.0-44-generic | 76        | 1.51%   |
| 5.15.0-41-generic | 75        | 1.49%   |
| 5.13.0-35-generic | 74        | 1.47%   |
| 5.3.0-46-generic  | 73        | 1.45%   |
| 5.13.0-28-generic | 73        | 1.45%   |
| 5.3.0-51-generic  | 65        | 1.29%   |
| 5.4.0-47-generic  | 60        | 1.19%   |
| 5.13.0-52-generic | 59        | 1.17%   |
| 5.13.0-27-generic | 59        | 1.17%   |
| 5.3.0-53-generic  | 54        | 1.07%   |
| 5.13.0-41-generic | 54        | 1.07%   |
| 5.4.0-58-generic  | 53        | 1.05%   |
| 5.3.0-42-generic  | 52        | 1.03%   |
| 5.4.0-48-generic  | 48        | 0.95%   |
| 5.4.0-65-generic  | 46        | 0.91%   |
| 5.4.0-45-generic  | 46        | 0.91%   |
| 5.4.0-72-generic  | 45        | 0.89%   |
| 5.13.0-51-generic | 42        | 0.83%   |
| 5.4.0-80-generic  | 41        | 0.82%   |
| 5.15.0-43-generic | 40        | 0.8%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 992       | 21.32%  |
| 5.11.0  | 947       | 20.36%  |
| 5.4.0   | 929       | 19.97%  |
| 5.13.0  | 765       | 16.44%  |
| 5.3.0   | 487       | 10.47%  |
| 4.15.0  | 189       | 4.06%   |
| 5.0.0   | 153       | 3.29%   |
| 4.18.0  | 75        | 1.61%   |
| 5.8.0   | 53        | 1.14%   |
| 5.14.0  | 10        | 0.21%   |
| 4.4.0   | 6         | 0.13%   |
| 5.7.1   | 3         | 0.06%   |
| 5.7.0   | 2         | 0.04%   |
| 5.6.0   | 2         | 0.04%   |
| 5.19.12 | 2         | 0.04%   |
| 5.17.5  | 2         | 0.04%   |
| 5.17.1  | 2         | 0.04%   |
| 5.16.0  | 2         | 0.04%   |
| 5.10.0  | 2         | 0.04%   |
| 4.13.0  | 2         | 0.04%   |
| 6.1.7   | 1         | 0.02%   |
| 6.0.8   | 1         | 0.02%   |
| 6.0.0   | 1         | 0.02%   |
| 5.9.12  | 1         | 0.02%   |
| 5.9.0   | 1         | 0.02%   |
| 5.8.5   | 1         | 0.02%   |
| 5.7.17  | 1         | 0.02%   |
| 5.4.180 | 1         | 0.02%   |
| 5.4.1   | 1         | 0.02%   |
| 5.19.9  | 1         | 0.02%   |
| 5.19.6  | 1         | 0.02%   |
| 5.19.2  | 1         | 0.02%   |
| 5.19.14 | 1         | 0.02%   |
| 5.19.1  | 1         | 0.02%   |
| 5.19.0  | 1         | 0.02%   |
| 5.18.6  | 1         | 0.02%   |
| 5.18.15 | 1         | 0.02%   |
| 5.17.9  | 1         | 0.02%   |
| 5.16.5  | 1         | 0.02%   |
| 5.16.14 | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 995       | 21.39%  |
| 5.11    | 947       | 20.36%  |
| 5.4     | 931       | 20.01%  |
| 5.13    | 766       | 16.47%  |
| 5.3     | 487       | 10.47%  |
| 4.15    | 189       | 4.06%   |
| 5.0     | 153       | 3.29%   |
| 4.18    | 75        | 1.61%   |
| 5.8     | 54        | 1.16%   |
| 5.14    | 10        | 0.21%   |
| 5.19    | 8         | 0.17%   |
| 5.7     | 6         | 0.13%   |
| 4.4     | 6         | 0.13%   |
| 5.17    | 5         | 0.11%   |
| 5.16    | 5         | 0.11%   |
| 5.10    | 4         | 0.09%   |
| 6.0     | 2         | 0.04%   |
| 5.9     | 2         | 0.04%   |
| 5.6     | 2         | 0.04%   |
| 5.18    | 2         | 0.04%   |
| 4.13    | 2         | 0.04%   |
| 6.1     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 4076      | 91.51%  |
| i686   | 378       | 8.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 3252      | 72.15%  |
| XFCE       | 934       | 20.72%  |
| Unknown    | 296       | 6.57%   |
| X-Cinnamon | 8         | 0.18%   |
| KDE        | 4         | 0.09%   |
| Unity      | 3         | 0.07%   |
| Cinnamon   | 3         | 0.07%   |
| KDE5       | 2         | 0.04%   |
| Budgie     | 2         | 0.04%   |
| MATE       | 1         | 0.02%   |
| LXDE       | 1         | 0.02%   |
| i3         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4241      | 94.5%   |
| Unknown | 182       | 4.06%   |
| Wayland | 64        | 1.43%   |
| Tty     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3672      | 81.2%   |
| GDM3    | 328       | 7.25%   |
| GDM     | 293       | 6.48%   |
| LightDM | 214       | 4.73%   |
| TDM     | 11        | 0.24%   |
| SDDM    | 3         | 0.07%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1623      | 36.18%  |
| de_DE   | 351       | 7.82%   |
| pt_BR   | 294       | 6.55%   |
| en_GB   | 271       | 6.04%   |
| Unknown | 230       | 5.13%   |
| it_IT   | 153       | 3.41%   |
| fr_FR   | 127       | 2.83%   |
| en_CA   | 127       | 2.83%   |
| en_IN   | 121       | 2.7%    |
| es_ES   | 114       | 2.54%   |
| pl_PL   | 99        | 2.21%   |
| en_AU   | 81        | 1.81%   |
| nl_NL   | 67        | 1.49%   |
| es_MX   | 62        | 1.38%   |
| ru_RU   | 61        | 1.36%   |
| pt_PT   | 50        | 1.11%   |
| es_AR   | 48        | 1.07%   |
| cs_CZ   | 42        | 0.94%   |
| en_ZA   | 41        | 0.91%   |
| C       | 29        | 0.65%   |
| tr_TR   | 28        | 0.62%   |
| hu_HU   | 28        | 0.62%   |
| sv_SE   | 27        | 0.6%    |
| es_CL   | 27        | 0.6%    |
| en_NZ   | 24        | 0.53%   |
| fr_CA   | 21        | 0.47%   |
| es_CO   | 21        | 0.47%   |
| de_AT   | 20        | 0.45%   |
| ja_JP   | 19        | 0.42%   |
| nl_BE   | 18        | 0.4%    |
| de_CH   | 17        | 0.38%   |
| el_GR   | 15        | 0.33%   |
| fr_BE   | 14        | 0.31%   |
| en_PH   | 13        | 0.29%   |
| da_DK   | 13        | 0.29%   |
| es_PE   | 12        | 0.27%   |
| nb_NO   | 11        | 0.25%   |
| fi_FI   | 10        | 0.22%   |
| ru_UA   | 9         | 0.2%    |
| ro_RO   | 9         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2462      | 54.67%  |
| EFI  | 2041      | 45.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4206      | 94.16%  |
| Overlay  | 95        | 2.13%   |
| Zfs      | 52        | 1.16%   |
| Btrfs    | 37        | 0.83%   |
| Ext2     | 32        | 0.72%   |
| Unknown  | 27        | 0.6%    |
| Ext3     | 9         | 0.2%    |
| Xfs      | 8         | 0.18%   |
| Reiserfs | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4014      | 89.48%  |
| GPT     | 352       | 7.85%   |
| MBR     | 120       | 2.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4209      | 93.99%  |
| Yes       | 269       | 6.01%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3640      | 81.14%  |
| Yes       | 846       | 18.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 776       | 17.43%  |
| ASUSTek Computer    | 640       | 14.38%  |
| Dell                | 585       | 13.14%  |
| Lenovo              | 505       | 11.35%  |
| Acer                | 247       | 5.55%   |
| Gigabyte Technology | 245       | 5.5%    |
| MSI                 | 185       | 4.16%   |
| Toshiba             | 146       | 3.28%   |
| ASRock              | 125       | 2.81%   |
| Apple               | 124       | 2.79%   |
| Intel               | 70        | 1.57%   |
| Samsung Electronics | 60        | 1.35%   |
| Unknown             | 52        | 1.17%   |
| Sony                | 48        | 1.08%   |
| Fujitsu             | 39        | 0.88%   |
| Packard Bell        | 30        | 0.67%   |
| Pegatron            | 27        | 0.61%   |
| Positivo            | 24        | 0.54%   |
| Foxconn             | 23        | 0.52%   |
| Biostar             | 23        | 0.52%   |
| Google              | 22        | 0.49%   |
| Microsoft           | 20        | 0.45%   |
| Medion              | 20        | 0.45%   |
| HUAWEI              | 19        | 0.43%   |
| Fujitsu Siemens     | 18        | 0.4%    |
| ECS                 | 18        | 0.4%    |
| Alienware           | 17        | 0.38%   |
| Gateway             | 13        | 0.29%   |
| AMI                 | 13        | 0.29%   |
| Notebook            | 11        | 0.25%   |
| eMachines           | 10        | 0.22%   |
| Panasonic           | 9         | 0.2%    |
| Multilaser          | 8         | 0.18%   |
| Chuwi               | 8         | 0.18%   |
| NEC Computers       | 7         | 0.16%   |
| IBM                 | 7         | 0.16%   |
| Shuttle             | 6         | 0.13%   |
| Semp Toshiba        | 6         | 0.13%   |
| Quanta              | 6         | 0.13%   |
| Insyde              | 6         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 83        | 1.86%   |
| ASUS All Series            | 34        | 0.76%   |
| HP Notebook                | 27        | 0.61%   |
| HP Pavilion Notebook       | 16        | 0.36%   |
| HP Pavilion dv6            | 13        | 0.29%   |
| HP 15                      | 12        | 0.27%   |
| Dell OptiPlex 7010         | 11        | 0.25%   |
| Toshiba Satellite C660     | 10        | 0.22%   |
| HP Pavilion dv7            | 10        | 0.22%   |
| Dell OptiPlex 790          | 10        | 0.22%   |
| Dell OptiPlex 780          | 10        | 0.22%   |
| HP Pavilion 15             | 9         | 0.2%    |
| Dell OptiPlex 380          | 9         | 0.2%    |
| Dell Latitude D630         | 9         | 0.2%    |
| Dell Inspiron 1545         | 9         | 0.2%    |
| MSI MS-7C02                | 8         | 0.18%   |
| MSI MS-7817                | 8         | 0.18%   |
| HP Pavilion g6             | 8         | 0.18%   |
| HP Laptop 15-bw0xx         | 8         | 0.18%   |
| Gigabyte A320M-S2H         | 8         | 0.18%   |
| Dell Latitude E6540        | 8         | 0.18%   |
| Dell Latitude E6400        | 8         | 0.18%   |
| Dell Inspiron 15-3567      | 8         | 0.18%   |
| ASUS M5A78L-M/USB3         | 8         | 0.18%   |
| Apple MacBookPro8,1        | 8         | 0.18%   |
| Apple iMac12,2             | 8         | 0.18%   |
| Lenovo MIIX 320-10ICR 80XF | 7         | 0.16%   |
| Gigabyte 970A-DS3P         | 7         | 0.16%   |
| Dell OptiPlex 990          | 7         | 0.16%   |
| Dell OptiPlex 755          | 7         | 0.16%   |
| Dell Latitude E6410        | 7         | 0.16%   |
| Dell Inspiron 3521         | 7         | 0.16%   |
| Dell Inspiron 1525         | 7         | 0.16%   |
| ASUS M5A97 R2.0            | 7         | 0.16%   |
| HP ProDesk 600 G1 SFF      | 6         | 0.13%   |
| HP ProBook 640 G1          | 6         | 0.13%   |
| HP Pavilion g7             | 6         | 0.13%   |
| HP Pavilion dv6700         | 6         | 0.13%   |
| HP Pavilion 17             | 6         | 0.13%   |
| HP EliteBook 840 G1        | 6         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 181       | 4.07%   |
| HP Pavilion           | 170       | 3.82%   |
| Acer Aspire           | 161       | 3.62%   |
| Lenovo ThinkPad       | 158       | 3.55%   |
| Dell Latitude         | 149       | 3.35%   |
| Lenovo IdeaPad        | 129       | 2.9%    |
| Toshiba Satellite     | 124       | 2.79%   |
| Dell OptiPlex         | 102       | 2.29%   |
| HP Compaq             | 100       | 2.25%   |
| Unknown               | 83        | 1.86%   |
| HP EliteBook          | 75        | 1.69%   |
| HP ProBook            | 65        | 1.46%   |
| HP Laptop             | 53        | 1.19%   |
| Lenovo ThinkCentre    | 48        | 1.08%   |
| ASUS ROG              | 48        | 1.08%   |
| ASUS PRIME            | 41        | 0.92%   |
| Dell Vostro           | 39        | 0.88%   |
| ASUS VivoBook         | 35        | 0.79%   |
| HP ENVY               | 34        | 0.76%   |
| ASUS All              | 34        | 0.76%   |
| ASUS TUF              | 32        | 0.72%   |
| Dell Precision        | 31        | 0.7%    |
| Dell XPS              | 30        | 0.67%   |
| Lenovo Yoga           | 27        | 0.61%   |
| HP Notebook           | 27        | 0.61%   |
| Packard Bell EasyNote | 25        | 0.56%   |
| Microsoft Surface     | 20        | 0.45%   |
| HP Stream             | 17        | 0.38%   |
| HP EliteDesk          | 17        | 0.38%   |
| Fujitsu ESPRIMO       | 17        | 0.38%   |
| Dell Studio           | 16        | 0.36%   |
| ASUS ZenBook          | 16        | 0.36%   |
| HP Presario           | 14        | 0.31%   |
| HP 15                 | 14        | 0.31%   |
| HP 255                | 13        | 0.29%   |
| ASUS M5A78L-M         | 13        | 0.29%   |
| Apple iMac12          | 13        | 0.29%   |
| Lenovo MIIX           | 12        | 0.27%   |
| HP ProDesk            | 12        | 0.27%   |
| HP OMEN               | 12        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 401       | 9.01%   |
| 2012    | 368       | 8.27%   |
| 2013    | 354       | 7.95%   |
| 2010    | 327       | 7.35%   |
| 2018    | 318       | 7.14%   |
| 2008    | 283       | 6.36%   |
| 2014    | 280       | 6.29%   |
| 2019    | 263       | 5.91%   |
| 2017    | 248       | 5.57%   |
| 2021    | 244       | 5.48%   |
| 2009    | 244       | 5.48%   |
| 2020    | 233       | 5.23%   |
| 2007    | 219       | 4.92%   |
| 2016    | 215       | 4.83%   |
| 2015    | 214       | 4.81%   |
| 2006    | 95        | 2.13%   |
| 2005    | 61        | 1.37%   |
| 2022    | 52        | 1.17%   |
| 2004    | 11        | 0.25%   |
| Unknown | 9         | 0.2%    |
| 2003    | 8         | 0.18%   |
| 2023    | 3         | 0.07%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2569      | 57.72%  |
| Desktop     | 1585      | 35.61%  |
| Convertible | 88        | 1.98%   |
| All in one  | 87        | 1.95%   |
| Tablet      | 59        | 1.33%   |
| Mini pc     | 54        | 1.21%   |
| Server      | 9         | 0.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4050      | 90.46%  |
| Enabled  | 427       | 9.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4425      | 99.42%  |
| Yes  | 26        | 0.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1149      | 25.57%  |
| 4.01-8.0        | 1042      | 23.19%  |
| 8.01-16.0       | 698       | 15.53%  |
| 16.01-24.0      | 587       | 13.06%  |
| 1.01-2.0        | 435       | 9.68%   |
| 32.01-64.0      | 252       | 5.61%   |
| 2.01-3.0        | 152       | 3.38%   |
| 0.51-1.0        | 90        | 2%      |
| 64.01-256.0     | 54        | 1.2%    |
| 24.01-32.0      | 34        | 0.76%   |
| More than 256.0 | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2054      | 42.83%  |
| 2.01-3.0   | 1304      | 27.19%  |
| 3.01-4.0   | 526       | 10.97%  |
| 4.01-8.0   | 410       | 8.55%   |
| 0.51-1.0   | 382       | 7.96%   |
| 8.01-16.0  | 65        | 1.36%   |
| 0.01-0.5   | 41        | 0.85%   |
| 16.01-24.0 | 8         | 0.17%   |
| 24.01-32.0 | 4         | 0.08%   |
| 32.01-64.0 | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2992      | 65.85%  |
| 2       | 1067      | 23.48%  |
| 3       | 252       | 5.55%   |
| 4       | 105       | 2.31%   |
| 5       | 50        | 1.1%    |
| 6       | 30        | 0.66%   |
| 0       | 22        | 0.48%   |
| 7       | 12        | 0.26%   |
| 8       | 9         | 0.2%    |
| 51      | 1         | 0.02%   |
| 30      | 1         | 0.02%   |
| 11      | 1         | 0.02%   |
| 10      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2243      | 50.15%  |
| Yes       | 2230      | 49.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3877      | 86.95%  |
| No        | 582       | 13.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3524      | 78.87%  |
| No        | 944       | 21.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2335      | 51.96%  |
| No        | 2159      | 48.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1026      | 22.96%  |
| Germany      | 406       | 9.08%   |
| Brazil       | 334       | 7.47%   |
| UK           | 271       | 6.06%   |
| Canada       | 171       | 3.83%   |
| Italy        | 169       | 3.78%   |
| Spain        | 130       | 2.91%   |
| India        | 129       | 2.89%   |
| France       | 125       | 2.8%    |
| Netherlands  | 117       | 2.62%   |
| Poland       | 102       | 2.28%   |
| Australia    | 91        | 2.04%   |
| Mexico       | 83        | 1.86%   |
| Argentina    | 61        | 1.36%   |
| Portugal     | 59        | 1.32%   |
| Russia       | 55        | 1.23%   |
| Czechia      | 50        | 1.12%   |
| Sweden       | 49        | 1.1%    |
| South Africa | 49        | 1.1%    |
| Belgium      | 49        | 1.1%    |
| Romania      | 42        | 0.94%   |
| Greece       | 41        | 0.92%   |
| Switzerland  | 40        | 0.9%    |
| Indonesia    | 40        | 0.9%    |
| Austria      | 37        | 0.83%   |
| Turkey       | 35        | 0.78%   |
| Hungary      | 35        | 0.78%   |
| Chile        | 33        | 0.74%   |
| Norway       | 31        | 0.69%   |
| Colombia     | 31        | 0.69%   |
| New Zealand  | 30        | 0.67%   |
| Japan        | 29        | 0.65%   |
| Denmark      | 28        | 0.63%   |
| Serbia       | 27        | 0.6%    |
| Egypt        | 24        | 0.54%   |
| Bulgaria     | 21        | 0.47%   |
| Ukraine      | 19        | 0.43%   |
| Philippines  | 19        | 0.43%   |
| Finland      | 17        | 0.38%   |
| Slovakia     | 15        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Berlin         | 39        | 0.84%   |
| Sao Paulo      | 36        | 0.78%   |
| Athens         | 30        | 0.65%   |
| Munich         | 27        | 0.58%   |
| Sydney         | 26        | 0.56%   |
| Rio de Janeiro | 23        | 0.5%    |
| Madrid         | 23        | 0.5%    |
| Vienna         | 22        | 0.47%   |
| Milan          | 22        | 0.47%   |
| Rome           | 19        | 0.41%   |
| Montreal       | 19        | 0.41%   |
| Toronto        | 17        | 0.37%   |
| New York       | 17        | 0.37%   |
| Dallas         | 17        | 0.37%   |
| Belgrade       | 17        | 0.37%   |
| Auckland       | 17        | 0.37%   |
| Perth          | 16        | 0.34%   |
| Johannesburg   | 16        | 0.34%   |
| Istanbul       | 16        | 0.34%   |
| Bengaluru      | 16        | 0.34%   |
| London         | 15        | 0.32%   |
| Hamburg        | 15        | 0.32%   |
| Cairo          | 15        | 0.32%   |
| Buenos Aires   | 15        | 0.32%   |
| Warsaw         | 14        | 0.3%    |
| Paris          | 14        | 0.3%    |
| Mexico City    | 14        | 0.3%    |
| Denver         | 14        | 0.3%    |
| Bogotá        | 14        | 0.3%    |
| Prague         | 13        | 0.28%   |
| Moscow         | 13        | 0.28%   |
| Jakarta        | 13        | 0.28%   |
| Bucharest      | 13        | 0.28%   |
| Brisbane       | 13        | 0.28%   |
| Zurich         | 12        | 0.26%   |
| Seattle        | 12        | 0.26%   |
| Melbourne      | 12        | 0.26%   |
| Stockholm      | 11        | 0.24%   |
| Portland       | 11        | 0.24%   |
| Phoenix        | 11        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1007      | 1381   | 16.74%  |
| WDC                       | 901       | 1176   | 14.98%  |
| Samsung Electronics       | 729       | 1034   | 12.12%  |
| Toshiba                   | 479       | 599    | 7.96%   |
| Unknown                   | 345       | 489    | 5.74%   |
| Kingston                  | 313       | 398    | 5.2%    |
| SanDisk                   | 311       | 367    | 5.17%   |
| Hitachi                   | 290       | 357    | 4.82%   |
| Crucial                   | 196       | 235    | 3.26%   |
| Intel                     | 119       | 155    | 1.98%   |
| HGST                      | 109       | 132    | 1.81%   |
| SK hynix                  | 83        | 100    | 1.38%   |
| A-DATA Technology         | 72        | 81     | 1.2%    |
| China                     | 60        | 69     | 1%      |
| Micron Technology         | 58        | 67     | 0.96%   |
| Apple                     | 50        | 53     | 0.83%   |
| Phison                    | 46        | 58     | 0.76%   |
| Maxtor                    | 44        | 61     | 0.73%   |
| Intenso                   | 43        | 47     | 0.71%   |
| PNY                       | 41        | 52     | 0.68%   |
| Fujitsu                   | 41        | 43     | 0.68%   |
| Silicon Motion            | 32        | 40     | 0.53%   |
| SPCC                      | 31        | 35     | 0.52%   |
| Patriot                   | 29        | 41     | 0.48%   |
| OCZ                       | 26        | 30     | 0.43%   |
| Transcend                 | 22        | 43     | 0.37%   |
| LITEON                    | 22        | 27     | 0.37%   |
| KIOXIA                    | 22        | 24     | 0.37%   |
| JMicron Technology        | 22        | 28     | 0.37%   |
| Netac                     | 20        | 22     | 0.33%   |
| GOODRAM                   | 18        | 19     | 0.3%    |
| Micron/Crucial Technology | 17        | 18     | 0.28%   |
| LITEONIT                  | 17        | 20     | 0.28%   |
| SABRENT                   | 16        | 17     | 0.27%   |
| Team                      | 15        | 18     | 0.25%   |
| Hewlett-Packard           | 15        | 19     | 0.25%   |
| Unknown                   | 15        | 17     | 0.25%   |
| Lexar                     | 13        | 13     | 0.22%   |
| KingSpec                  | 12        | 14     | 0.2%    |
| Gigabyte Technology       | 11        | 19     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 118       | 1.8%    |
| Unknown MMC Card  64GB                              | 91        | 1.39%   |
| Kingston SA400S37240G 240GB SSD                     | 76        | 1.16%   |
| Seagate ST500DM002-1BD142 500GB                     | 55        | 0.84%   |
| Toshiba MQ01ABF050 500GB                            | 49        | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                      | 49        | 0.75%   |
| Kingston SA400S37480G 480GB SSD                     | 46        | 0.7%    |
| Crucial CT240BX500SSD1 240GB                        | 43        | 0.66%   |
| Samsung SSD 860 EVO 500GB                           | 42        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                     | 41        | 0.63%   |
| Toshiba MQ01ABD100 1TB                              | 40        | 0.61%   |
| Unknown MMC Card  128GB                             | 38        | 0.58%   |
| Seagate ST500LT012-1DG142 500GB                     | 37        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 37        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB                      | 36        | 0.55%   |
| Toshiba MQ04ABF100 1TB                              | 34        | 0.52%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 34        | 0.52%   |
| Samsung NVMe SSD Drive 512GB                        | 33        | 0.5%    |
| Samsung SSD 850 EVO 500GB                           | 32        | 0.49%   |
| Samsung SSD 850 EVO 250GB                           | 31        | 0.47%   |
| Unknown SD/MMC/MS PRO 16GB                          | 30        | 0.46%   |
| Samsung NVMe SSD Drive 500GB                        | 30        | 0.46%   |
| Seagate ST9500325AS 500GB                           | 29        | 0.44%   |
| Samsung NVMe SSD Drive 1TB                          | 29        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 29        | 0.44%   |
| Seagate ST3500418AS 500GB                           | 28        | 0.43%   |
| Crucial CT500MX500SSD1 500GB                        | 28        | 0.43%   |
| Unknown MMC Card  16GB                              | 25        | 0.38%   |
| Toshiba DT01ACA100 1TB                              | 25        | 0.38%   |
| Seagate Expansion 1TB                               | 25        | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 23        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 22        | 0.34%   |
| SanDisk NVMe SSD Drive 256GB                        | 22        | 0.34%   |
| Samsung SSD 860 EVO 250GB                           | 22        | 0.34%   |
| Samsung SSD 840 EVO 250GB                           | 21        | 0.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 21        | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB                      | 20        | 0.31%   |
| Intel NVMe SSD Drive 512GB                          | 20        | 0.31%   |
| Seagate ST1000DM003-1CH162 1TB                      | 19        | 0.29%   |
| SanDisk NVMe SSD Drive 512GB                        | 19        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 996       | 1353   | 33.82%  |
| WDC                 | 812       | 1046   | 27.57%  |
| Toshiba             | 405       | 512    | 13.75%  |
| Hitachi             | 290       | 357    | 9.85%   |
| Samsung Electronics | 144       | 182    | 4.89%   |
| HGST                | 109       | 132    | 3.7%    |
| Maxtor              | 42        | 59     | 1.43%   |
| Fujitsu             | 41        | 43     | 1.39%   |
| Unknown             | 30        | 40     | 1.02%   |
| Apple               | 26        | 28     | 0.88%   |
| SABRENT             | 16        | 17     | 0.54%   |
| JMicron Technology  | 15        | 20     | 0.51%   |
| USB3.0              | 4         | 5      | 0.14%   |
| IBM/Hitachi         | 4         | 5      | 0.14%   |
| Hewlett-Packard     | 3         | 6      | 0.1%    |
| Intenso             | 2         | 2      | 0.07%   |
| Quantum             | 1         | 1      | 0.03%   |
| Pioneer             | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 2      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 377       | 518    | 19.85%  |
| Kingston            | 270       | 336    | 14.22%  |
| SanDisk             | 193       | 230    | 10.16%  |
| Crucial             | 190       | 227    | 10.01%  |
| WDC                 | 86        | 104    | 4.53%   |
| A-DATA Technology   | 67        | 76     | 3.53%   |
| Intel               | 57        | 67     | 3%      |
| China               | 57        | 66     | 3%      |
| PNY                 | 41        | 52     | 2.16%   |
| Toshiba             | 40        | 46     | 2.11%   |
| SK hynix            | 31        | 35     | 1.63%   |
| Micron Technology   | 31        | 36     | 1.63%   |
| SPCC                | 29        | 33     | 1.53%   |
| Intenso             | 29        | 32     | 1.53%   |
| Patriot             | 28        | 40     | 1.47%   |
| OCZ                 | 24        | 28     | 1.26%   |
| Transcend           | 22        | 43     | 1.16%   |
| LITEON              | 22        | 27     | 1.16%   |
| Netac               | 20        | 21     | 1.05%   |
| Apple               | 20        | 20     | 1.05%   |
| LITEONIT            | 17        | 20     | 0.9%    |
| GOODRAM             | 17        | 18     | 0.9%    |
| Team                | 15        | 18     | 0.79%   |
| Lexar               | 12        | 12     | 0.63%   |
| KingSpec            | 11        | 13     | 0.58%   |
| Hewlett-Packard     | 11        | 12     | 0.58%   |
| Apacer              | 10        | 11     | 0.53%   |
| Leven               | 9         | 10     | 0.47%   |
| Gigabyte Technology | 9         | 16     | 0.47%   |
| Corsair             | 8         | 10     | 0.42%   |
| Plextor             | 7         | 8      | 0.37%   |
| ASMT                | 7         | 7      | 0.37%   |
| Unknown             | 7         | 9      | 0.37%   |
| OWC                 | 6         | 7      | 0.32%   |
| Verbatim            | 4         | 4      | 0.21%   |
| TCSUNBOW            | 4         | 4      | 0.21%   |
| Super Talent        | 4         | 5      | 0.21%   |
| Seagate             | 4         | 6      | 0.21%   |
| Mushkin             | 4         | 4      | 0.21%   |
| FORESEE             | 4         | 4      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2573      | 3814   | 46.88%  |
| SSD     | 1718      | 2350   | 31.3%   |
| NVMe    | 757       | 1010   | 13.79%  |
| MMC     | 321       | 443    | 5.85%   |
| Unknown | 120       | 150    | 2.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3738      | 5994   | 74.23%  |
| NVMe | 756       | 1008   | 15.01%  |
| MMC  | 321       | 443    | 6.37%   |
| SAS  | 221       | 322    | 4.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2944      | 4092   | 67.08%  |
| 0.51-1.0        | 1064      | 1450   | 24.24%  |
| 1.01-2.0        | 231       | 329    | 5.26%   |
| 3.01-4.0        | 56        | 135    | 1.28%   |
| 4.01-10.0       | 56        | 80     | 1.28%   |
| 2.01-3.0        | 33        | 61     | 0.75%   |
| 10.01-20.0      | 4         | 16     | 0.09%   |
| More than 100.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1505      | 32.72%  |
| 251-500        | 1129      | 24.54%  |
| 501-1000       | 603       | 13.11%  |
| 51-100         | 473       | 10.28%  |
| 21-50          | 275       | 5.98%   |
| 1001-2000      | 225       | 4.89%   |
| 1-20           | 139       | 3.02%   |
| More than 3000 | 135       | 2.93%   |
| 2001-3000      | 75        | 1.63%   |
| Unknown        | 41        | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2290      | 48.08%  |
| 21-50          | 1069      | 22.44%  |
| 51-100         | 492       | 10.33%  |
| 101-250        | 392       | 8.23%   |
| 251-500        | 216       | 4.53%   |
| 501-1000       | 119       | 2.5%    |
| 1001-2000      | 66        | 1.39%   |
| More than 3000 | 60        | 1.26%   |
| Unknown        | 41        | 0.86%   |
| 2001-3000      | 18        | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 3         | 3      | 3.26%   |
| Seagate ST9500325AS 500GB                | 3         | 3      | 3.26%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 2.17%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 2.17%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 2.17%   |
| HGST HTS541010A9E680 1TB                 | 2         | 2      | 2.17%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 1.09%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 1.09%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 1.09%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 1.09%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1         | 1      | 1.09%   |
| WDC WD3200BPVT-55ZEST0 320GB             | 1         | 1      | 1.09%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 1.09%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 1.09%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1      | 1.09%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 1.09%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.09%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 1.09%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 1.09%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 1.09%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 1.09%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 1.09%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 1.09%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 1.09%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 1.09%   |
| Toshiba MK5061GSY 500GB                  | 1         | 1      | 1.09%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 1.09%   |
| Toshiba MK2046GSX 200GB                  | 1         | 1      | 1.09%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 1.09%   |
| Teclast 128GB NS550-2242 SSD             | 1         | 1      | 1.09%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 1         | 1      | 1.09%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1         | 1      | 1.09%   |
| Seagate ST9320325AS 320GB                | 1         | 1      | 1.09%   |
| Seagate ST9320310AS 320GB                | 1         | 1      | 1.09%   |
| Seagate ST9250315AS 250GB                | 1         | 1      | 1.09%   |
| Seagate ST9200420ASG 200GB               | 1         | 1      | 1.09%   |
| Seagate ST9160411ASG 160GB               | 1         | 1      | 1.09%   |
| Seagate ST9160314AS 160GB                | 1         | 1      | 1.09%   |
| Seagate ST9120822AS 120GB                | 1         | 1      | 1.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 33     | 35.16%  |
| WDC                 | 14        | 15     | 15.38%  |
| Toshiba             | 14        | 14     | 15.38%  |
| HGST                | 6         | 6      | 6.59%   |
| Kingston            | 5         | 5      | 5.49%   |
| Hitachi             | 5         | 5      | 5.49%   |
| Samsung Electronics | 4         | 4      | 4.4%    |
| A-DATA Technology   | 2         | 2      | 2.2%    |
| Teclast             | 1         | 1      | 1.1%    |
| SK hynix            | 1         | 1      | 1.1%    |
| Silicon Motion      | 1         | 1      | 1.1%    |
| OCZ                 | 1         | 1      | 1.1%    |
| Micron Technology   | 1         | 1      | 1.1%    |
| LITEONIT            | 1         | 1      | 1.1%    |
| LITEON              | 1         | 1      | 1.1%    |
| Intel               | 1         | 1      | 1.1%    |
| Hewlett-Packard     | 1         | 1      | 1.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 33     | 45.07%  |
| WDC                 | 14        | 15     | 19.72%  |
| Toshiba             | 12        | 12     | 16.9%   |
| HGST                | 6         | 6      | 8.45%   |
| Hitachi             | 5         | 5      | 7.04%   |
| Samsung Electronics | 2         | 2      | 2.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 68        | 73     | 77.27%  |
| SSD  | 17        | 17     | 19.32%  |
| NVMe | 3         | 3      | 3.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4103      | 7115   | 90.57%  |
| Works    | 338       | 557    | 7.46%   |
| Malfunc  | 87        | 93     | 1.92%   |
| Failed   | 2         | 2      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3083      | 60.92%  |
| AMD                              | 822       | 16.24%  |
| Samsung Electronics              | 266       | 5.26%   |
| Nvidia                           | 133       | 2.63%   |
| SanDisk                          | 122       | 2.41%   |
| ASMedia Technology               | 60        | 1.19%   |
| Phison Electronics               | 58        | 1.15%   |
| JMicron Technology               | 58        | 1.15%   |
| Kingston Technology Company      | 53        | 1.05%   |
| SK hynix                         | 48        | 0.95%   |
| Marvell Technology Group         | 45        | 0.89%   |
| VIA Technologies                 | 35        | 0.69%   |
| Toshiba America Info Systems     | 35        | 0.69%   |
| Silicon Motion                   | 34        | 0.67%   |
| Silicon Integrated Systems [SiS] | 34        | 0.67%   |
| Micron Technology                | 28        | 0.55%   |
| KIOXIA                           | 24        | 0.47%   |
| Micron/Crucial Technology        | 23        | 0.45%   |
| ADATA Technology                 | 18        | 0.36%   |
| Silicon Image                    | 14        | 0.28%   |
| Realtek Semiconductor            | 10        | 0.2%    |
| Broadcom / LSI                   | 7         | 0.14%   |
| Union Memory (Shenzhen)          | 6         | 0.12%   |
| Lite-On Technology               | 6         | 0.12%   |
| Seagate Technology               | 5         | 0.1%    |
| LSI Logic / Symbios Logic        | 4         | 0.08%   |
| Apple                            | 4         | 0.08%   |
| Solid State Storage Technology   | 3         | 0.06%   |
| OCZ Technology Group             | 3         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Promise Technology               | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 509       | 8.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 218       | 3.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 201       | 3.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 199       | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 183       | 2.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 163       | 2.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 156       | 2.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 146       | 2.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 141       | 2.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 124       | 2.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 118       | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 117       | 1.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 116       | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 113       | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 111       | 1.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 99        | 1.62%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 91        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 89        | 1.45%   |
| AMD 400 Series Chipset SATA Controller                                                  | 80        | 1.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 73        | 1.19%   |
| Intel SATA Controller [RAID mode]                                                       | 72        | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 65        | 1.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 64        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 62        | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 57        | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 56        | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 54        | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 54        | 0.88%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 54        | 0.88%   |
| Samsung NVMe SSD Controller 980                                                         | 49        | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 46        | 0.75%   |
| Nvidia MCP61 SATA Controller                                                            | 44        | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 41        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 41        | 0.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 40        | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 40        | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 38        | 0.62%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 37        | 0.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 37        | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 35        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3161      | 59.47%  |
| IDE  | 1037      | 19.51%  |
| NVMe | 759       | 14.28%  |
| RAID | 344       | 6.47%   |
| SAS  | 8         | 0.15%   |
| SCSI | 6         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3470      | 77.96%  |
| AMD          | 980       | 22.02%  |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 65        | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 38        | 0.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 35        | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 33        | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 30        | 0.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 30        | 0.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 30        | 0.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 27        | 0.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.58%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 25        | 0.56%   |
| AMD Ryzen 5 3600 6-Core Processor             | 25        | 0.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 24        | 0.54%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 0.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 23        | 0.52%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 23        | 0.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 0.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 21        | 0.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 21        | 0.47%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 21        | 0.47%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 20        | 0.45%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 20        | 0.45%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 20        | 0.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 19        | 0.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 19        | 0.43%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 19        | 0.43%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.43%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 18        | 0.4%    |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 18        | 0.4%    |
| Intel Atom CPU Z3735F @ 1.33GHz               | 18        | 0.4%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 18        | 0.4%    |
| Intel Pentium 4 CPU 3.00GHz                   | 17        | 0.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 17        | 0.38%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 17        | 0.38%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 17        | 0.38%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 0.36%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 16        | 0.36%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.36%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 16        | 0.36%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 16        | 0.36%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 16        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 889       | 19.94%  |
| Intel Core i7           | 561       | 12.58%  |
| Intel Core i3           | 409       | 9.17%   |
| Intel Core 2 Duo        | 319       | 7.16%   |
| Intel Celeron           | 286       | 6.42%   |
| Intel Atom              | 197       | 4.42%   |
| AMD Ryzen 5             | 163       | 3.66%   |
| Other                   | 141       | 3.16%   |
| Intel Pentium           | 137       | 3.07%   |
| AMD Ryzen 7             | 111       | 2.49%   |
| Intel Xeon              | 81        | 1.82%   |
| Intel Pentium Dual-Core | 81        | 1.82%   |
| AMD FX                  | 73        | 1.64%   |
| Intel Pentium Dual      | 68        | 1.53%   |
| AMD A6                  | 65        | 1.46%   |
| Intel Core 2 Quad       | 59        | 1.32%   |
| AMD A4                  | 52        | 1.17%   |
| Intel Genuine           | 46        | 1.03%   |
| Intel Core 2            | 44        | 0.99%   |
| AMD Ryzen 3             | 43        | 0.96%   |
| AMD A8                  | 41        | 0.92%   |
| Intel Pentium 4         | 40        | 0.9%    |
| AMD Athlon 64 X2        | 39        | 0.87%   |
| AMD A10                 | 39        | 0.87%   |
| AMD Ryzen 9             | 38        | 0.85%   |
| AMD Athlon II X2        | 31        | 0.7%    |
| Intel Pentium M         | 24        | 0.54%   |
| Intel Celeron M         | 24        | 0.54%   |
| AMD E1                  | 24        | 0.54%   |
| AMD Phenom II X4        | 22        | 0.49%   |
| AMD E                   | 21        | 0.47%   |
| AMD Athlon              | 20        | 0.45%   |
| AMD Sempron             | 17        | 0.38%   |
| AMD Turion 64 X2 Mobile | 16        | 0.36%   |
| Intel Core i9           | 15        | 0.34%   |
| Intel Pentium Silver    | 13        | 0.29%   |
| AMD Athlon II X4        | 12        | 0.27%   |
| Intel Pentium Gold      | 9         | 0.2%    |
| Intel Pentium D         | 9         | 0.2%    |
| Intel Core M            | 9         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2311      | 51.82%  |
| 4      | 1369      | 30.7%   |
| 1      | 269       | 6.03%   |
| 6      | 243       | 5.45%   |
| 8      | 172       | 3.86%   |
| 3      | 34        | 0.76%   |
| 12     | 26        | 0.58%   |
| 16     | 14        | 0.31%   |
| 10     | 14        | 0.31%   |
| 14     | 4         | 0.09%   |
| 20     | 2         | 0.04%   |
| 40     | 1         | 0.02%   |
| 28     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4433      | 99.6%   |
| 2      | 18        | 0.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2382      | 53.5%   |
| 1      | 2070      | 46.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4305      | 96.7%   |
| 32-bit         | 144       | 3.23%   |
| Unknown        | 3         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 408       | 9.02%   |
| 0x206a7    | 371       | 8.2%    |
| 0x306a9    | 294       | 6.5%    |
| 0x1067a    | 280       | 6.19%   |
| 0x306c3    | 233       | 5.15%   |
| 0x6fd      | 130       | 2.87%   |
| 0x40651    | 129       | 2.85%   |
| 0x20655    | 116       | 2.56%   |
| 0x406e3    | 96        | 2.12%   |
| 0x806e9    | 90        | 1.99%   |
| 0x406c4    | 87        | 1.92%   |
| 0x306d4    | 86        | 1.9%    |
| 0x30678    | 86        | 1.9%    |
| 0x806ea    | 75        | 1.66%   |
| 0x806c1    | 72        | 1.59%   |
| 0x506e3    | 71        | 1.57%   |
| 0x906ea    | 65        | 1.44%   |
| 0x10676    | 65        | 1.44%   |
| 0x906e9    | 58        | 1.28%   |
| 0x806ec    | 57        | 1.26%   |
| 0x6fb      | 55        | 1.22%   |
| 0x06000852 | 53        | 1.17%   |
| 0x010000c8 | 51        | 1.13%   |
| 0x06001119 | 49        | 1.08%   |
| 0x20652    | 46        | 1.02%   |
| 0x08701021 | 46        | 1.02%   |
| 0x506c9    | 44        | 0.97%   |
| 0x406c3    | 41        | 0.91%   |
| 0x706a8    | 38        | 0.84%   |
| 0x08108109 | 37        | 0.82%   |
| 0x6f6      | 36        | 0.8%    |
| 0x106ca    | 36        | 0.8%    |
| 0x06006705 | 36        | 0.8%    |
| 0x0700010f | 32        | 0.71%   |
| 0x706e5    | 31        | 0.69%   |
| 0x6e8      | 30        | 0.66%   |
| 0x6d8      | 29        | 0.64%   |
| 0x07030105 | 28        | 0.62%   |
| 0x0800820d | 26        | 0.57%   |
| 0x05000119 | 26        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 429       | 9.63%   |
| SandyBridge      | 395       | 8.87%   |
| Haswell          | 395       | 8.87%   |
| Penryn           | 366       | 8.22%   |
| IvyBridge        | 313       | 7.03%   |
| Core             | 281       | 6.31%   |
| Silvermont       | 249       | 5.59%   |
| Westmere         | 182       | 4.09%   |
| Skylake          | 178       | 4%      |
| K10              | 116       | 2.6%    |
| Piledriver       | 110       | 2.47%   |
| Zen 2            | 106       | 2.38%   |
| Zen+             | 102       | 2.29%   |
| K8 Hammer        | 97        | 2.18%   |
| Broadwell        | 91        | 2.04%   |
| P6               | 83        | 1.86%   |
| TigerLake        | 82        | 1.84%   |
| Zen 3            | 77        | 1.73%   |
| Excavator        | 73        | 1.64%   |
| Bonnell          | 73        | 1.64%   |
| Zen              | 64        | 1.44%   |
| Goldmont plus    | 63        | 1.41%   |
| CometLake        | 60        | 1.35%   |
| NetBurst         | 57        | 1.28%   |
| IceLake          | 53        | 1.19%   |
| Goldmont         | 47        | 1.06%   |
| Puma             | 45        | 1.01%   |
| Unknown          | 44        | 0.99%   |
| Nehalem          | 43        | 0.97%   |
| Bobcat           | 41        | 0.92%   |
| Jaguar           | 39        | 0.88%   |
| K10 Llano        | 26        | 0.58%   |
| Steamroller      | 19        | 0.43%   |
| Bulldozer        | 17        | 0.38%   |
| K8 & K10 hybrid  | 15        | 0.34%   |
| Alderlake Hybrid | 13        | 0.29%   |
| Tremont          | 7         | 0.16%   |
| K6               | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2629      | 52.35%  |
| Nvidia                           | 1179      | 23.48%  |
| AMD                              | 1161      | 23.12%  |
| Silicon Integrated Systems [SiS] | 27        | 0.54%   |
| VIA Technologies                 | 17        | 0.34%   |
| Matrox Electronics Systems       | 5         | 0.1%    |
| ASPEED Technology                | 2         | 0.04%   |
| Trident Microsystems             | 1         | 0.02%   |
| Silicon Motion                   | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 306       | 5.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 191       | 3.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 139       | 2.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 132       | 2.51%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 124       | 2.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 122       | 2.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 109       | 2.07%   |
| Intel HD Graphics 620                                                                    | 88        | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 86        | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 81        | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 77        | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 77        | 1.46%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 75        | 1.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 72        | 1.37%   |
| Intel UHD Graphics 620                                                                   | 71        | 1.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 64        | 1.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 63        | 1.2%    |
| Intel HD Graphics 5500                                                                   | 61        | 1.16%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 56        | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 54        | 1.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 54        | 1.03%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 53        | 1.01%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 50        | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 48        | 0.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 46        | 0.87%   |
| Intel HD Graphics 630                                                                    | 45        | 0.86%   |
| Intel HD Graphics 530                                                                    | 42        | 0.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 0.78%   |
| AMD Renoir                                                                               | 41        | 0.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 0.76%   |
| Intel HD Graphics 500                                                                    | 39        | 0.74%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 37        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 36        | 0.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 0.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 29        | 0.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 28        | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 27        | 0.51%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 27        | 0.51%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 27        | 0.51%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 27        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2114      | 47.31%  |
| 1 x AMD                  | 934       | 20.9%   |
| 1 x Nvidia               | 784       | 17.55%  |
| Intel + Nvidia           | 341       | 7.63%   |
| Intel + AMD              | 121       | 2.71%   |
| 2 x AMD                  | 68        | 1.52%   |
| AMD + Nvidia             | 37        | 0.83%   |
| 1 x SiS                  | 27        | 0.6%    |
| 1 x VIA                  | 17        | 0.38%   |
| 2 x Nvidia               | 9         | 0.2%    |
| Other                    | 6         | 0.13%   |
| 1 x Matrox               | 5         | 0.11%   |
| 2 x Intel                | 1         | 0.02%   |
| 1 x Trident Microsystems | 1         | 0.02%   |
| Nvidia + Silicon Motion  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |
| 1 x ASPEED               | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3627      | 80.87%  |
| Proprietary | 642       | 14.31%  |
| Unknown     | 216       | 4.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2556      | 56.4%   |
| 0.01-0.5   | 703       | 15.51%  |
| 1.01-2.0   | 465       | 10.26%  |
| 0.51-1.0   | 393       | 8.67%   |
| 3.01-4.0   | 191       | 4.21%   |
| 7.01-8.0   | 114       | 2.52%   |
| 5.01-6.0   | 54        | 1.19%   |
| 8.01-16.0  | 29        | 0.64%   |
| 2.01-3.0   | 22        | 0.49%   |
| 16.01-24.0 | 4         | 0.09%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 618       | 14.03%  |
| AU Optronics            | 535       | 12.15%  |
| LG Display              | 403       | 9.15%   |
| Chimei Innolux          | 348       | 7.9%    |
| BOE                     | 308       | 6.99%   |
| Dell                    | 214       | 4.86%   |
| Goldstar                | 197       | 4.47%   |
| Hewlett-Packard         | 164       | 3.72%   |
| Acer                    | 126       | 2.86%   |
| Chi Mei Optoelectronics | 109       | 2.47%   |
| Apple                   | 108       | 2.45%   |
| Philips                 | 89        | 2.02%   |
| AOC                     | 89        | 2.02%   |
| Ancor Communications    | 78        | 1.77%   |
| LG Philips              | 69        | 1.57%   |
| BenQ                    | 69        | 1.57%   |
| Lenovo                  | 65        | 1.48%   |
| Sharp                   | 47        | 1.07%   |
| LG Electronics          | 40        | 0.91%   |
| InfoVision              | 39        | 0.89%   |
| ViewSonic               | 37        | 0.84%   |
| Unknown                 | 35        | 0.79%   |
| Sony                    | 32        | 0.73%   |
| PANDA                   | 27        | 0.61%   |
| Vizio                   | 26        | 0.59%   |
| Toshiba                 | 26        | 0.59%   |
| HannStar                | 25        | 0.57%   |
| Iiyama                  | 23        | 0.52%   |
| ASUSTek Computer        | 20        | 0.45%   |
| Unknown                 | 19        | 0.43%   |
| CPT                     | 18        | 0.41%   |
| Eizo                    | 17        | 0.39%   |
| Sceptre Tech            | 14        | 0.32%   |
| NEC Computers           | 13        | 0.3%    |
| Panasonic               | 12        | 0.27%   |
| Fujitsu Siemens         | 12        | 0.27%   |
| Quanta Display          | 11        | 0.25%   |
| Gateway                 | 11        | 0.25%   |
| MSI                     | 10        | 0.23%   |
| LGD                     | 10        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 31        | 0.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 23        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 20        | 0.44%   |
| Unknown                                                                  | 19        | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 16        | 0.35%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 14        | 0.31%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 14        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.27%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 11        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 11        | 0.24%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 10        | 0.22%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 10        | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.22%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 10        | 0.22%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 0.22%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 9         | 0.2%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 9         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.2%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.2%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 8         | 0.18%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 8         | 0.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 8         | 0.18%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 8         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1430      | 33.09%  |
| 1366x768 (WXGA)    | 1185      | 27.42%  |
| 1600x900 (HD+)     | 247       | 5.72%   |
| 1280x800 (WXGA)    | 211       | 4.88%   |
| 3840x2160 (4K)     | 181       | 4.19%   |
| 1440x900 (WXGA+)   | 143       | 3.31%   |
| 1280x1024 (SXGA)   | 142       | 3.29%   |
| 1680x1050 (WSXGA+) | 125       | 2.89%   |
| 2560x1440 (QHD)    | 101       | 2.34%   |
| 1920x1200 (WUXGA)  | 72        | 1.67%   |
| Unknown            | 72        | 1.67%   |
| 1360x768           | 62        | 1.43%   |
| 1024x600           | 46        | 1.06%   |
| 3840x1080          | 27        | 0.62%   |
| 3440x1440          | 26        | 0.6%    |
| 2560x1600          | 24        | 0.56%   |
| 1024x768 (XGA)     | 24        | 0.56%   |
| 2560x1080          | 22        | 0.51%   |
| 1920x540           | 20        | 0.46%   |
| 2736x1824          | 14        | 0.32%   |
| 2160x1440          | 9         | 0.21%   |
| 2256x1504          | 8         | 0.19%   |
| 1600x1200          | 8         | 0.19%   |
| 5760x1080          | 7         | 0.16%   |
| 3200x1800 (QHD+)   | 7         | 0.16%   |
| 1280x768           | 7         | 0.16%   |
| 3840x2400          | 5         | 0.12%   |
| 3600x1080          | 5         | 0.12%   |
| 2880x1800          | 5         | 0.12%   |
| 1280x720 (HD)      | 5         | 0.12%   |
| 5760x2160          | 4         | 0.09%   |
| 4480x1440          | 4         | 0.09%   |
| 3840x1600          | 4         | 0.09%   |
| 1680x945           | 4         | 0.09%   |
| 1400x1050          | 4         | 0.09%   |
| 2048x1152          | 3         | 0.07%   |
| 1920x1280          | 3         | 0.07%   |
| 1024x576           | 3         | 0.07%   |
| 6400x1440          | 2         | 0.05%   |
| 5440x1080          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1220      | 27.89%  |
| Unknown | 367       | 8.39%   |
| 13      | 364       | 8.32%   |
| 14      | 316       | 7.22%   |
| 17      | 295       | 6.74%   |
| 27      | 200       | 4.57%   |
| 24      | 191       | 4.37%   |
| 23      | 190       | 4.34%   |
| 21      | 185       | 4.23%   |
| 19      | 130       | 2.97%   |
| 18      | 113       | 2.58%   |
| 11      | 102       | 2.33%   |
| 20      | 97        | 2.22%   |
| 12      | 83        | 1.9%    |
| 31      | 80        | 1.83%   |
| 22      | 77        | 1.76%   |
| 10      | 58        | 1.33%   |
| 34      | 42        | 0.96%   |
| 40      | 29        | 0.66%   |
| 84      | 24        | 0.55%   |
| 72      | 23        | 0.53%   |
| 54      | 21        | 0.48%   |
| 16      | 19        | 0.43%   |
| 32      | 17        | 0.39%   |
| 26      | 16        | 0.37%   |
| 25      | 10        | 0.23%   |
| 52      | 9         | 0.21%   |
| 65      | 7         | 0.16%   |
| 42      | 7         | 0.16%   |
| 36      | 7         | 0.16%   |
| 29      | 7         | 0.16%   |
| 49      | 6         | 0.14%   |
| 74      | 5         | 0.11%   |
| 47      | 5         | 0.11%   |
| 37      | 5         | 0.11%   |
| 33      | 5         | 0.11%   |
| 8       | 4         | 0.09%   |
| 64      | 3         | 0.07%   |
| 55      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1757      | 40.7%   |
| 501-600     | 549       | 12.72%  |
| 401-500     | 531       | 12.3%   |
| 201-300     | 413       | 9.57%   |
| Unknown     | 367       | 8.5%    |
| 351-400     | 343       | 7.95%   |
| 601-700     | 107       | 2.48%   |
| 701-800     | 71        | 1.64%   |
| 1001-1500   | 67        | 1.55%   |
| 1501-2000   | 55        | 1.27%   |
| 801-900     | 39        | 0.9%    |
| 901-1000    | 14        | 0.32%   |
| 101-200     | 4         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2906      | 71.3%   |
| 16/10   | 565       | 13.86%  |
| Unknown | 325       | 7.97%   |
| 5/4     | 126       | 3.09%   |
| 21/9    | 48        | 1.18%   |
| 3/2     | 44        | 1.08%   |
| 4/3     | 43        | 1.05%   |
| 32/9    | 11        | 0.27%   |
| 6/5     | 5         | 0.12%   |
| 3.73    | 2         | 0.05%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1217      | 28%     |
| 81-90          | 550       | 12.66%  |
| 201-250        | 503       | 11.57%  |
| Unknown        | 367       | 8.44%   |
| 151-200        | 308       | 7.09%   |
| 301-350        | 206       | 4.74%   |
| 121-130        | 168       | 3.87%   |
| 141-150        | 159       | 3.66%   |
| 351-500        | 153       | 3.52%   |
| 71-80          | 128       | 2.95%   |
| More than 1000 | 108       | 2.49%   |
| 51-60          | 104       | 2.39%   |
| 251-300        | 82        | 1.89%   |
| 61-70          | 74        | 1.7%    |
| 501-1000       | 70        | 1.61%   |
| 131-140        | 61        | 1.4%    |
| 41-50          | 56        | 1.29%   |
| 111-120        | 15        | 0.35%   |
| 91-100         | 13        | 0.3%    |
| 1-40           | 4         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1407      | 33.18%  |
| 51-100        | 1344      | 31.7%   |
| 121-160       | 804       | 18.96%  |
| Unknown       | 367       | 8.66%   |
| 161-240       | 155       | 3.66%   |
| 1-50          | 113       | 2.67%   |
| More than 240 | 50        | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3786      | 83.72%  |
| 2     | 471       | 10.42%  |
| 0     | 219       | 4.84%   |
| 3     | 42        | 0.93%   |
| 4     | 3         | 0.07%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2365      | 33.94%  |
| Intel                             | 1738      | 24.94%  |
| Qualcomm Atheros                  | 935       | 13.42%  |
| Broadcom                          | 572       | 8.21%   |
| Broadcom Limited                  | 178       | 2.55%   |
| Marvell Technology Group          | 128       | 1.84%   |
| Ralink Technology                 | 117       | 1.68%   |
| Nvidia                            | 115       | 1.65%   |
| Ralink                            | 91        | 1.31%   |
| TP-Link                           | 82        | 1.18%   |
| MediaTek                          | 48        | 0.69%   |
| Samsung Electronics               | 44        | 0.63%   |
| Silicon Integrated Systems [SiS]  | 31        | 0.44%   |
| Xiaomi                            | 30        | 0.43%   |
| ASIX Electronics                  | 30        | 0.43%   |
| VIA Technologies                  | 29        | 0.42%   |
| NetGear                           | 28        | 0.4%    |
| D-Link                            | 26        | 0.37%   |
| JMicron Technology                | 24        | 0.34%   |
| Qualcomm Atheros Communications   | 23        | 0.33%   |
| Huawei Technologies               | 22        | 0.32%   |
| D-Link System                     | 22        | 0.32%   |
| Dell                              | 19        | 0.27%   |
| Edimax Technology                 | 18        | 0.26%   |
| DisplayLink                       | 18        | 0.26%   |
| ASUSTek Computer                  | 17        | 0.24%   |
| Sierra Wireless                   | 13        | 0.19%   |
| Microsoft                         | 13        | 0.19%   |
| Hewlett-Packard                   | 13        | 0.19%   |
| OPPO                              | 12        | 0.17%   |
| Qualcomm                          | 10        | 0.14%   |
| Motorola PCS                      | 10        | 0.14%   |
| Ericsson Business Mobile Networks | 9         | 0.13%   |
| Belkin Components                 | 9         | 0.13%   |
| Linksys                           | 8         | 0.11%   |
| AMD                               | 8         | 0.11%   |
| Aquantia                          | 7         | 0.1%    |
| Attansic Technology               | 6         | 0.09%   |
| T & A Mobile Phones               | 5         | 0.07%   |
| Sitecom Europe                    | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1416      | 17.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 445       | 5.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 186       | 2.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 144       | 1.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 134       | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 123       | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 116       | 1.43%   |
| Intel Wireless 7260                                                     | 105       | 1.3%    |
| Intel Wi-Fi 6 AX200                                                     | 102       | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 88        | 1.09%   |
| Intel Wireless 7265                                                     | 82        | 1.01%   |
| Intel Wireless 8265 / 8275                                              | 81        | 1%      |
| Intel Ethernet Connection I217-LM                                       | 77        | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 76        | 0.94%   |
| Intel Wireless 3165                                                     | 69        | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 65        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 64        | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                           | 64        | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 62        | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 61        | 0.75%   |
| Intel I211 Gigabit Network Connection                                   | 61        | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 60        | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                       | 58        | 0.72%   |
| Intel Wireless 8260                                                     | 57        | 0.7%    |
| Intel Wi-Fi 6 AX201                                                     | 57        | 0.7%    |
| Ralink MT7601U Wireless Adapter                                         | 56        | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 55        | 0.68%   |
| Realtek 802.11ac NIC                                                    | 50        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 49        | 0.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 47        | 0.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 46        | 0.57%   |
| Intel WiFi Link 5100                                                    | 45        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 43        | 0.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 42        | 0.52%   |
| Nvidia MCP61 Ethernet                                                   | 41        | 0.51%   |
| Intel Ethernet Connection (2) I219-V                                    | 38        | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 37        | 0.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 0.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 35        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1277      | 33.56%  |
| Qualcomm Atheros                      | 747       | 19.63%  |
| Realtek Semiconductor                 | 720       | 18.92%  |
| Broadcom                              | 395       | 10.38%  |
| Ralink Technology                     | 117       | 3.07%   |
| Broadcom Limited                      | 113       | 2.97%   |
| Ralink                                | 91        | 2.39%   |
| TP-Link                               | 73        | 1.92%   |
| MediaTek                              | 32        | 0.84%   |
| NetGear                               | 27        | 0.71%   |
| D-Link                                | 26        | 0.68%   |
| Qualcomm Atheros Communications       | 23        | 0.6%    |
| Marvell Technology Group              | 18        | 0.47%   |
| Edimax Technology                     | 18        | 0.47%   |
| D-Link System                         | 18        | 0.47%   |
| ASUSTek Computer                      | 15        | 0.39%   |
| Sierra Wireless                       | 13        | 0.34%   |
| Microsoft                             | 11        | 0.29%   |
| Dell                                  | 9         | 0.24%   |
| Belkin Components                     | 9         | 0.24%   |
| Linksys                               | 8         | 0.21%   |
| Sitecom Europe                        | 4         | 0.11%   |
| Micro Star International              | 4         | 0.11%   |
| Gemtek                                | 4         | 0.11%   |
| ZyDAS                                 | 3         | 0.08%   |
| Hewlett-Packard                       | 3         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.08%   |
| ZyXEL Communications                  | 2         | 0.05%   |
| Xiaomi                                | 2         | 0.05%   |
| TRENDnet                              | 2         | 0.05%   |
| Senao                                 | 2         | 0.05%   |
| IMC Networks                          | 2         | 0.05%   |
| FIBOCOM                               | 2         | 0.05%   |
| AVM                                   | 2         | 0.05%   |
| Qualcomm                              | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Ovislink                              | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 144       | 3.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 134       | 3.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 123       | 3.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 116       | 3.02%   |
| Intel Wireless 7260                                                     | 105       | 2.73%   |
| Intel Wi-Fi 6 AX200                                                     | 102       | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 88        | 2.29%   |
| Intel Wireless 7265                                                     | 82        | 2.13%   |
| Intel Wireless 8265 / 8275                                              | 81        | 2.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 76        | 1.98%   |
| Intel Wireless 3165                                                     | 69        | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 65        | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                           | 64        | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 62        | 1.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 61        | 1.59%   |
| Intel Wireless 8260                                                     | 57        | 1.48%   |
| Intel Wi-Fi 6 AX201                                                     | 57        | 1.48%   |
| Ralink MT7601U Wireless Adapter                                         | 56        | 1.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 55        | 1.43%   |
| Realtek 802.11ac NIC                                                    | 50        | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 49        | 1.28%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 47        | 1.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 46        | 1.2%    |
| Intel WiFi Link 5100                                                    | 45        | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 42        | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 37        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 35        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 35        | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 0.88%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 34        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 33        | 0.86%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 33        | 0.86%   |
| Intel Wireless 3160                                                     | 32        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                          | 31        | 0.81%   |
| Intel Centrino Wireless-N 2230                                          | 29        | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 27        | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 26        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2065      | 50.38%  |
| Intel                                  | 895       | 21.83%  |
| Qualcomm Atheros                       | 270       | 6.59%   |
| Broadcom                               | 248       | 6.05%   |
| Nvidia                                 | 115       | 2.81%   |
| Marvell Technology Group               | 110       | 2.68%   |
| Broadcom Limited                       | 71        | 1.73%   |
| Samsung Electronics                    | 43        | 1.05%   |
| ASIX Electronics                       | 30        | 0.73%   |
| VIA Technologies                       | 29        | 0.71%   |
| Silicon Integrated Systems [SiS]       | 29        | 0.71%   |
| Xiaomi                                 | 28        | 0.68%   |
| JMicron Technology                     | 24        | 0.59%   |
| Huawei Technologies                    | 18        | 0.44%   |
| DisplayLink                            | 18        | 0.44%   |
| MediaTek                               | 16        | 0.39%   |
| OPPO                                   | 12        | 0.29%   |
| TP-Link                                | 9         | 0.22%   |
| Qualcomm                               | 9         | 0.22%   |
| Motorola PCS                           | 7         | 0.17%   |
| Aquantia                               | 7         | 0.17%   |
| Attansic Technology                    | 6         | 0.15%   |
| Google                                 | 4         | 0.1%    |
| D-Link System                          | 4         | 0.1%    |
| Sundance Technology Inc / IC Plus      | 3         | 0.07%   |
| Hewlett-Packard                        | 3         | 0.07%   |
| Davicom Semiconductor                  | 3         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| HMD Global                             | 2         | 0.05%   |
| ASUSTek Computer                       | 2         | 0.05%   |
| Apple                                  | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.02%   |
| T & A Mobile Phones                    | 1         | 0.02%   |
| Sun Microsystems                       | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Research In Motion                     | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Motorola BCS                           | 1         | 0.02%   |
| Microsoft                              | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1416      | 34.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 445       | 10.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 186       | 4.48%   |
| Intel Ethernet Connection I217-LM                                 | 77        | 1.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 64        | 1.54%   |
| Intel I211 Gigabit Network Connection                             | 61        | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 60        | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 58        | 1.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 43        | 1.04%   |
| Nvidia MCP61 Ethernet                                             | 41        | 0.99%   |
| Intel Ethernet Connection (2) I219-V                              | 38        | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 30        | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 30        | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 29        | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 28        | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 28        | 0.67%   |
| Intel 82577LM Gigabit Network Connection                          | 28        | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25        | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 25        | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 24        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 0.58%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 24        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 24        | 0.58%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 23        | 0.55%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 23        | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 0.55%   |
| Nvidia MCP79 Ethernet                                             | 22        | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 21        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20        | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 20        | 0.48%   |
| Intel 82566MM Gigabit Network Connection                          | 20        | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 18        | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 18        | 0.43%   |
| Intel Ethernet Connection (2) I218-V                              | 18        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3871      | 51.57%  |
| WiFi     | 3523      | 46.93%  |
| Modem    | 100       | 1.33%   |
| Unknown  | 13        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2764      | 59.96%  |
| Ethernet | 1842      | 39.96%  |
| Modem    | 2         | 0.04%   |
| Unknown  | 2         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2558      | 57.26%  |
| 1     | 1694      | 37.92%  |
| 0     | 142       | 3.18%   |
| 3     | 66        | 1.48%   |
| 5     | 4         | 0.09%   |
| 4     | 2         | 0.04%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3519      | 78.01%  |
| Yes  | 992       | 21.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 852       | 36.07%  |
| Realtek Semiconductor           | 271       | 11.47%  |
| Qualcomm Atheros Communications | 248       | 10.5%   |
| Broadcom                        | 167       | 7.07%   |
| Cambridge Silicon Radio         | 134       | 5.67%   |
| Apple                           | 118       | 5%      |
| IMC Networks                    | 103       | 4.36%   |
| Lite-On Technology              | 71        | 3.01%   |
| Foxconn / Hon Hai               | 63        | 2.67%   |
| Dell                            | 63        | 2.67%   |
| Hewlett-Packard                 | 58        | 2.46%   |
| Toshiba                         | 36        | 1.52%   |
| ASUSTek Computer                | 35        | 1.48%   |
| Ralink                          | 22        | 0.93%   |
| Marvell Semiconductor           | 15        | 0.64%   |
| Realtek                         | 14        | 0.59%   |
| Alps Electric                   | 14        | 0.59%   |
| MediaTek                        | 10        | 0.42%   |
| Foxconn International           | 10        | 0.42%   |
| Dynex                           | 9         | 0.38%   |
| Integrated System Solution      | 7         | 0.3%    |
| TP-Link                         | 6         | 0.25%   |
| Askey Computer                  | 6         | 0.25%   |
| Taiyo Yuden                     | 4         | 0.17%   |
| Ralink Technology               | 4         | 0.17%   |
| Micro Star International        | 4         | 0.17%   |
| Belkin Components               | 4         | 0.17%   |
| Chicony Electronics             | 3         | 0.13%   |
| Qcom                            | 2         | 0.08%   |
| Sitecom Europe                  | 1         | 0.04%   |
| National Semiconductor          | 1         | 0.04%   |
| Mobile Action Technology        | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Actions                         | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 402       | 17.01%  |
| Realtek Bluetooth Radio                             | 173       | 7.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 134       | 5.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 106       | 4.48%   |
| Intel AX201 Bluetooth                               | 102       | 4.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 97        | 4.1%    |
| Intel AX200 Bluetooth                               | 89        | 3.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 74        | 3.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 49        | 2.07%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 42        | 1.78%   |
| Apple Bluetooth Host Controller                     | 41        | 1.73%   |
| IMC Networks Bluetooth Device                       | 40        | 1.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 34        | 1.44%   |
| Intel AX210 Bluetooth                               | 33        | 1.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 33        | 1.4%    |
| Intel Wireless-AC 3168 Bluetooth                    | 31        | 1.31%   |
| Apple Bluetooth USB Host Controller                 | 31        | 1.31%   |
| IMC Networks Bluetooth Radio                        | 29        | 1.23%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 28        | 1.18%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 27        | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 25        | 1.06%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 24        | 1.02%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 24        | 1.02%   |
| Ralink RT3290 Bluetooth                             | 22        | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 21        | 0.89%   |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 0.76%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 18        | 0.76%   |
| Apple Bluetooth HCI                                 | 18        | 0.76%   |
| Dell DW375 Bluetooth Module                         | 17        | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.68%   |
| Marvell Bluetooth and Wireless LAN Composite        | 14        | 0.59%   |
| Lite-On Bluetooth Device                            | 14        | 0.59%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 14        | 0.59%   |
| Dell Wireless 365 Bluetooth                         | 12        | 0.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.51%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.51%   |
| Toshiba Bluetooth Device                            | 11        | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3229      | 56.6%   |
| AMD                                  | 1157      | 20.28%  |
| Nvidia                               | 876       | 15.35%  |
| C-Media Electronics                  | 73        | 1.28%   |
| Silicon Integrated Systems [SiS]     | 34        | 0.6%    |
| Creative Labs                        | 32        | 0.56%   |
| VIA Technologies                     | 31        | 0.54%   |
| Logitech                             | 24        | 0.42%   |
| Texas Instruments                    | 17        | 0.3%    |
| JMTek                                | 16        | 0.28%   |
| Generalplus Technology               | 15        | 0.26%   |
| Kingston Technology                  | 14        | 0.25%   |
| GN Netcom                            | 12        | 0.21%   |
| Realtek Semiconductor                | 11        | 0.19%   |
| Creative Technology                  | 10        | 0.18%   |
| Tenx Technology                      | 9         | 0.16%   |
| Razer USA                            | 9         | 0.16%   |
| Plantronics                          | 9         | 0.16%   |
| ASUSTek Computer                     | 9         | 0.16%   |
| SteelSeries ApS                      | 6         | 0.11%   |
| DCMT Technology                      | 5         | 0.09%   |
| Lenovo                               | 4         | 0.07%   |
| Focusrite-Novation                   | 4         | 0.07%   |
| DSEA A/S                             | 4         | 0.07%   |
| Corsair                              | 4         | 0.07%   |
| Yamaha                               | 3         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.05%   |
| Samsung Electronics                  | 3         | 0.05%   |
| Micro Star International             | 3         | 0.05%   |
| Astro Gaming                         | 3         | 0.05%   |
| Turtle Beach                         | 2         | 0.04%   |
| Sony                                 | 2         | 0.04%   |
| SAVITECH                             | 2         | 0.04%   |
| RODE Microphones                     | 2         | 0.04%   |
| Numark                               | 2         | 0.04%   |
| Micronas                             | 2         | 0.04%   |
| Klipsch Audio                        | 2         | 0.04%   |
| Jieli Technology                     | 2         | 0.04%   |
| Hewlett-Packard                      | 2         | 0.04%   |
| Ensoniq                              | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 365       | 5.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 326       | 4.83%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 281       | 4.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 279       | 4.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 224       | 3.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 216       | 3.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 215       | 3.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 209       | 3.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 195       | 2.89%   |
| AMD FCH Azalia Controller                                                                         | 195       | 2.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 160       | 2.37%   |
| Intel 8 Series HD Audio Controller                                                                | 135       | 2%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 133       | 1.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 131       | 1.94%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 102       | 1.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 100       | 1.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 94        | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 94        | 1.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 93        | 1.38%   |
| Intel Broadwell-U Audio Controller                                                                | 87        | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 86        | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 83        | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 82        | 1.22%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 81        | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 77        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 75        | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 70        | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 63        | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 59        | 0.87%   |
| Nvidia High Definition Audio Controller                                                           | 55        | 0.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 55        | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 54        | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 53        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 50        | 0.74%   |
| AMD High Definition Audio Controller                                                              | 50        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 47        | 0.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 46        | 0.68%   |
| Nvidia MCP61 High Definition Audio                                                                | 43        | 0.64%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 43        | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 42        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 203       | 21.8%   |
| SK hynix               | 177       | 19.01%  |
| Unknown                | 125       | 13.43%  |
| Micron Technology      | 85        | 9.13%   |
| Kingston               | 80        | 8.59%   |
| Crucial                | 39        | 4.19%   |
| Corsair                | 28        | 3.01%   |
| G.Skill                | 24        | 2.58%   |
| Unknown (ABCD)         | 21        | 2.26%   |
| Elpida                 | 20        | 2.15%   |
| Ramaxel Technology     | 17        | 1.83%   |
| Nanya Technology       | 17        | 1.83%   |
| A-DATA Technology      | 16        | 1.72%   |
| Team                   | 8         | 0.86%   |
| Smart                  | 7         | 0.75%   |
| Qimonda                | 6         | 0.64%   |
| Patriot                | 6         | 0.64%   |
| Unknown                | 4         | 0.43%   |
| Transcend              | 3         | 0.32%   |
| Avant                  | 3         | 0.32%   |
| Wilk                   | 2         | 0.21%   |
| Timetec                | 2         | 0.21%   |
| Teikon                 | 2         | 0.21%   |
| SHARETRONIC            | 2         | 0.21%   |
| High Bridge            | 2         | 0.21%   |
| ff                     | 2         | 0.21%   |
| CSX                    | 2         | 0.21%   |
| 4ea5                   | 2         | 0.21%   |
| Walton Chaintech       | 1         | 0.11%   |
| Unknown (08B5)         | 1         | 0.11%   |
| Unknown (000080B30080) | 1         | 0.11%   |
| Unifosa                | 1         | 0.11%   |
| Toshiba                | 1         | 0.11%   |
| Strontium              | 1         | 0.11%   |
| Smart Brazil           | 1         | 0.11%   |
| Ramos Technology       | 1         | 0.11%   |
| PUSKILL                | 1         | 0.11%   |
| ProMos/Mosel Vitelic   | 1         | 0.11%   |
| PNY                    | 1         | 0.11%   |
| Patriot Memory         | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 19        | 1.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 1.3%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.7%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 6         | 0.6%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.6%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.6%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 5         | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.5%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.5%    |
| Unknown RAM Module 1GB DIMM SDRAM                                | 4         | 0.4%    |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.4%    |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.4%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.4%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.4%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.4%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.4%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.4%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.4%    |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.4%    |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 4         | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.4%    |
| Unknown                                                          | 4         | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 3         | 0.3%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 3         | 0.3%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 3         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 308       | 38.5%   |
| DDR4    | 263       | 32.88%  |
| DDR2    | 83        | 10.38%  |
| LPDDR4  | 43        | 5.38%   |
| SDRAM   | 35        | 4.38%   |
| Unknown | 28        | 3.5%    |
| LPDDR3  | 22        | 2.75%   |
| DDR     | 9         | 1.13%   |
| DRAM    | 6         | 0.75%   |
| DDR5    | 2         | 0.25%   |
| LPDDR5  | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 494       | 62.77%  |
| DIMM         | 227       | 28.84%  |
| Row Of Chips | 57        | 7.24%   |
| Chip         | 4         | 0.51%   |
| Unknown      | 4         | 0.51%   |
| FB-DIMM      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 284       | 31.7%   |
| 8192  | 270       | 30.13%  |
| 2048  | 180       | 20.09%  |
| 1024  | 72        | 8.04%   |
| 16384 | 62        | 6.92%   |
| 32768 | 14        | 1.56%   |
| 512   | 12        | 1.34%   |
| 256   | 2         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 195       | 22.49%  |
| 2667    | 91        | 10.5%   |
| 3200    | 82        | 9.46%   |
| 1333    | 66        | 7.61%   |
| 2400    | 58        | 6.69%   |
| 667     | 45        | 5.19%   |
| 1334    | 38        | 4.38%   |
| Unknown | 38        | 4.38%   |
| 2133    | 34        | 3.92%   |
| 800     | 26        | 3%      |
| 1066    | 21        | 2.42%   |
| 3600    | 16        | 1.85%   |
| 3266    | 16        | 1.85%   |
| 1867    | 14        | 1.61%   |
| 4267    | 12        | 1.38%   |
| 533     | 11        | 1.27%   |
| 4199    | 9         | 1.04%   |
| 975     | 9         | 1.04%   |
| 2048    | 8         | 0.92%   |
| 3000    | 6         | 0.69%   |
| 1866    | 6         | 0.69%   |
| 400     | 6         | 0.69%   |
| 1067    | 5         | 0.58%   |
| 2666    | 4         | 0.46%   |
| 1800    | 4         | 0.46%   |
| 333     | 4         | 0.46%   |
| 8400    | 3         | 0.35%   |
| 4266    | 3         | 0.35%   |
| 3866    | 3         | 0.35%   |
| 3733    | 3         | 0.35%   |
| 3466    | 3         | 0.35%   |
| 2933    | 3         | 0.35%   |
| 2800    | 3         | 0.35%   |
| 4800    | 2         | 0.23%   |
| 3800    | 2         | 0.23%   |
| 3666    | 2         | 0.23%   |
| 3400    | 2         | 0.23%   |
| 3333    | 2         | 0.23%   |
| 1639    | 2         | 0.23%   |
| 49926   | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 36        | 29.27%  |
| Canon                 | 29        | 23.58%  |
| Brother Industries    | 19        | 15.45%  |
| Seiko Epson           | 17        | 13.82%  |
| Samsung Electronics   | 14        | 11.38%  |
| STMicroelectronics    | 2         | 1.63%   |
| Zebra                 | 1         | 0.81%   |
| Toshiba TEC           | 1         | 0.81%   |
| Ricoh                 | 1         | 0.81%   |
| QinHeng Electronics   | 1         | 0.81%   |
| Pantum                | 1         | 0.81%   |
| Lexmark International | 1         | 0.81%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon TS3100 series                                       | 4         | 3.25%   |
| Seiko Epson L3110 Series                                  | 3         | 2.44%   |
| Canon PIXMA MG2500 Series                                 | 3         | 2.44%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.63%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 2         | 1.63%   |
| Samsung SCX-3400 Series                                   | 2         | 1.63%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.63%   |
| Samsung CLX-3300 Series                                   | 2         | 1.63%   |
| HP LaserJet Professional P 1102w                          | 2         | 1.63%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.63%   |
| HP ENVY 5000 series                                       | 2         | 1.63%   |
| HP ENVY 4520 series                                       | 2         | 1.63%   |
| HP DeskJet 2700 series                                    | 2         | 1.63%   |
| HP DeskJet 2130 series                                    | 2         | 1.63%   |
| HP DeskJet 1110 series                                    | 2         | 1.63%   |
| Canon PIXMA MX340                                         | 2         | 1.63%   |
| Canon MF4010 series                                       | 2         | 1.63%   |
| Canon LiDE 400                                            | 2         | 1.63%   |
| Brother HL-2140 series                                    | 2         | 1.63%   |
| Brother HL-2130 series                                    | 2         | 1.63%   |
| Zebra ZP 450 Printer                                      | 1         | 0.81%   |
| Toshiba TEC e-STD120 USB                                  | 1         | 0.81%   |
| Seiko Epson XP-7100 Series                                | 1         | 0.81%   |
| Seiko Epson XP-225 Series                                 | 1         | 0.81%   |
| Seiko Epson XP-200 Series                                 | 1         | 0.81%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.81%   |
| Seiko Epson Printer                                       | 1         | 0.81%   |
| Seiko Epson L365 Series                                   | 1         | 0.81%   |
| Seiko Epson L355 Series                                   | 1         | 0.81%   |
| Seiko Epson L220 Series                                   | 1         | 0.81%   |
| Seiko Epson L120 Series                                   | 1         | 0.81%   |
| Seiko Epson ET-2820 Series                                | 1         | 0.81%   |
| Seiko Epson ET-2810 Series                                | 1         | 0.81%   |
| Seiko Epson ET-2710 Series                                | 1         | 0.81%   |
| Samsung SCX-483x 5x3x Series                              | 1         | 0.81%   |
| Samsung SCX-4623 Series                                   | 1         | 0.81%   |
| Samsung SCX-4200 series                                   | 1         | 0.81%   |
| Samsung ML-2950 Series                                    | 1         | 0.81%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 0.81%   |
| Samsung M2070 Series                                      | 1         | 0.81%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 73.33%  |
| Seiko Epson     | 2         | 13.33%  |
| Hewlett-Packard | 2         | 13.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 13.33%  |
| Canon CanoScan LIDE 25                      | 2         | 13.33%  |
| Canon CanoScan LiDE 100                     | 2         | 13.33%  |
| HP ScanJet 2400c                            | 1         | 6.67%   |
| HP PSC 1200                                 | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 6.67%   |
| Canon CanoScan LiDE 90                      | 1         | 6.67%   |
| Canon CanoScan LiDE 60                      | 1         | 6.67%   |
| Canon CanoScan LiDE 200                     | 1         | 6.67%   |
| Canon CanoScan LiDE 110                     | 1         | 6.67%   |
| Canon CanoScan D660U                        | 1         | 6.67%   |
| Canon CanoScan 8800F                        | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 564       | 22.79%  |
| Microdia                               | 231       | 9.33%   |
| Realtek Semiconductor                  | 184       | 7.43%   |
| IMC Networks                           | 176       | 7.11%   |
| Acer                                   | 152       | 6.14%   |
| Sunplus Innovation Technology          | 128       | 5.17%   |
| Suyin                                  | 119       | 4.81%   |
| Apple                                  | 115       | 4.65%   |
| Cheng Uei Precision Industry (Foxlink) | 110       | 4.44%   |
| Quanta                                 | 88        | 3.56%   |
| Logitech                               | 76        | 3.07%   |
| Syntek                                 | 55        | 2.22%   |
| Silicon Motion                         | 50        | 2.02%   |
| Lite-On Technology                     | 45        | 1.82%   |
| Alcor Micro                            | 42        | 1.7%    |
| Ricoh                                  | 32        | 1.29%   |
| Samsung Electronics                    | 26        | 1.05%   |
| Microsoft                              | 23        | 0.93%   |
| Importek                               | 17        | 0.69%   |
| ALi                                    | 16        | 0.65%   |
| Luxvisions Innotech Limited            | 15        | 0.61%   |
| Z-Star Microelectronics                | 14        | 0.57%   |
| Primax Electronics                     | 14        | 0.57%   |
| Generalplus Technology                 | 12        | 0.48%   |
| GEMBIRD                                | 12        | 0.48%   |
| icSpring                               | 11        | 0.44%   |
| OmniVision Technologies                | 9         | 0.36%   |
| Lenovo                                 | 9         | 0.36%   |
| ARC International                      | 9         | 0.36%   |
| Sonix Technology                       | 8         | 0.32%   |
| Genesys Logic                          | 7         | 0.28%   |
| Unknown                                | 6         | 0.24%   |
| SunplusIT                              | 5         | 0.2%    |
| Sunplus Technology                     | 5         | 0.2%    |
| Cubeternet                             | 5         | 0.2%    |
| Razer USA                              | 4         | 0.16%   |
| Pixart Imaging                         | 4         | 0.16%   |
| Jieli Technology                       | 4         | 0.16%   |
| Huawei Technologies                    | 4         | 0.16%   |
| Creative Technology                    | 4         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 67        | 2.69%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 41        | 1.65%   |
| Microdia Integrated_Webcam_HD                           | 39        | 1.57%   |
| Realtek Integrated_Webcam_HD                            | 38        | 1.53%   |
| Apple FaceTime HD Camera (Built-in)                     | 37        | 1.49%   |
| Microdia Integrated Webcam                              | 35        | 1.41%   |
| Acer Integrated Camera                                  | 34        | 1.37%   |
| Chicony HD WebCam                                       | 33        | 1.33%   |
| Chicony HP Truevision HD                                | 32        | 1.29%   |
| Apple iPhone 5/5C/5S/6/SE                               | 31        | 1.25%   |
| Acer Lenovo EasyCamera                                  | 31        | 1.25%   |
| Samsung Galaxy A5 (MTP)                                 | 26        | 1.05%   |
| Chicony USB 2.0 Camera                                  | 26        | 1.05%   |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 1.05%   |
| Syntek Integrated Camera                                | 25        | 1%      |
| IMC Networks Integrated Camera                          | 25        | 1%      |
| Apple Built-in iSight                                   | 24        | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 23        | 0.92%   |
| Chicony HP Truevision HD camera                         | 23        | 0.92%   |
| Sunplus Integrated_Webcam_HD                            | 21        | 0.84%   |
| Chicony EasyCamera                                      | 21        | 0.84%   |
| Logitech Webcam C270                                    | 20        | 0.8%    |
| Chicony Lenovo EasyCamera                               | 19        | 0.76%   |
| Sunplus HD WebCam                                       | 18        | 0.72%   |
| Chicony HP HD Webcam                                    | 18        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 18        | 0.72%   |
| Realtek USB Camera                                      | 17        | 0.68%   |
| Realtek Integrated Webcam                               | 17        | 0.68%   |
| Chicony VGA WebCam                                      | 17        | 0.68%   |
| Alcor Micro USB Camera                                  | 17        | 0.68%   |
| Suyin HP Truevision HD                                  | 16        | 0.64%   |
| Chicony USB2.0 VGA UVC WebCam                           | 16        | 0.64%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 15        | 0.6%    |
| Quanta HP TrueVision HD Camera                          | 15        | 0.6%    |
| Microdia Sonix USB 2.0 Camera                           | 15        | 0.6%    |
| Chicony CNF9055 Toshiba Webcam                          | 15        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 15        | 0.6%    |
| Quanta HP Webcam                                        | 14        | 0.56%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 14        | 0.56%   |
| Chicony USB2.0 HD UVC WebCam                            | 14        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 172       | 43.99%  |
| AuthenTec                  | 56        | 14.32%  |
| Synaptics                  | 41        | 10.49%  |
| Shenzhen Goodix Technology | 39        | 9.97%   |
| Upek                       | 31        | 7.93%   |
| Elan Microelectronics      | 20        | 5.12%   |
| STMicroelectronics         | 18        | 4.6%    |
| LighTuning Technology      | 10        | 2.56%   |
| Samsung Electronics        | 2         | 0.51%   |
| HOLTEK                     | 1         | 0.26%   |
| Focal-systems.Corp         | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 37        | 9.46%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 7.67%   |
| Shenzhen Goodix  Fingerprint Device                                        | 22        | 5.63%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 20        | 5.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 4.86%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 4.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 4.35%   |
| AuthenTec AES2810                                                          | 17        | 4.35%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 4.35%   |
| Validity Sensors VFS491                                                    | 16        | 4.09%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 3.84%   |
| Shenzhen Goodix Fingerprint Reader                                         | 14        | 3.58%   |
| Unknown                                                                    | 14        | 3.58%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.56%   |
| Elan ELAN:ARM-M4                                                           | 10        | 2.56%   |
| Synaptics  WBDI                                                            | 9         | 2.3%    |
| AuthenTec AES1600                                                          | 9         | 2.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 2.05%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.05%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 1.79%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.53%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.53%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.28%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.28%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 1.28%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.02%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.02%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.02%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.02%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 1.02%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.77%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.77%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.51%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.51%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.51%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.51%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.51%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.51%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.51%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 79        | 47.88%  |
| Alcor Micro                       | 28        | 16.97%  |
| O2 Micro                          | 25        | 15.15%  |
| Lenovo                            | 9         | 5.45%   |
| Upek                              | 7         | 4.24%   |
| Realtek Semiconductor             | 4         | 2.42%   |
| SCM Microsystems                  | 3         | 1.82%   |
| Yubico.com                        | 2         | 1.21%   |
| VASCO Data Security International | 2         | 1.21%   |
| Advanced Card Systems             | 2         | 1.21%   |
| Reiner SCT Kartensysteme          | 1         | 0.61%   |
| OmniKey                           | 1         | 0.61%   |
| Kobil Systems                     | 1         | 0.61%   |
| Fujitsu Siemens Computers         | 1         | 0.61%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 38        | 23.03%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 16.36%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 12.73%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 12.12%  |
| Broadcom 5880                                                                | 16        | 9.7%    |
| Lenovo Integrated Smart Card Reader                                          | 9         | 5.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.24%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 3.03%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 2.42%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 1.21%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.21%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.21%   |
| Broadcom 58200                                                               | 2         | 1.21%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.61%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.61%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.61%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.61%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.61%   |
| Kobil Systems KOBIL Class 3 Reader                                           | 1         | 0.61%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.61%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.61%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.61%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.61%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3169      | 70.11%  |
| 1     | 1096      | 24.25%  |
| 2     | 231       | 5.11%   |
| 3     | 19        | 0.42%   |
| 4     | 4         | 0.09%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 400       | 25.43%  |
| Fingerprint reader       | 384       | 24.41%  |
| Net/wireless             | 272       | 17.29%  |
| Chipcard                 | 154       | 9.79%   |
| Multimedia controller    | 120       | 7.63%   |
| Modem                    | 44        | 2.8%    |
| Storage                  | 40        | 2.54%   |
| Communication controller | 38        | 2.42%   |
| Bluetooth                | 30        | 1.91%   |
| Sound                    | 20        | 1.27%   |
| Camera                   | 15        | 0.95%   |
| Unassigned class         | 13        | 0.83%   |
| Flash memory             | 11        | 0.7%    |
| Net/ethernet             | 7         | 0.45%   |
| Card reader              | 6         | 0.38%   |
| Network                  | 4         | 0.25%   |
| Dvb card                 | 4         | 0.25%   |
| Storage/raid             | 3         | 0.19%   |
| Storage/nvme             | 3         | 0.19%   |
| Storage/ide              | 3         | 0.19%   |
| Unclassified device      | 1         | 0.06%   |
| Storage/ata              | 1         | 0.06%   |

