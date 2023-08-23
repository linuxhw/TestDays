Linux in Belgium - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Belgium.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Belgium/Desktop/README.md) and [notebooks](/Location/Belgium/Notebook/README.md).

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

Total: 2872

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [6e7a8f72dd](https://linux-hardware.org/?probe=6e7a8f72dd) | Aug 10, 2023 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [d45603bb4e](https://linux-hardware.org/?probe=d45603bb4e) | Aug 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [5e64d2b59e](https://linux-hardware.org/?probe=5e64d2b59e) | Aug 06, 2023 |
| AZW           | EQ                          | Desktop     | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [584974f252](https://linux-hardware.org/?probe=584974f252) | Aug 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5a0ec66589](https://linux-hardware.org/?probe=5a0ec66589) | Aug 05, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a4f9f590c](https://linux-hardware.org/?probe=9a4f9f590c) | Aug 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [db2732f0e8](https://linux-hardware.org/?probe=db2732f0e8) | Aug 04, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [38f7c8653b](https://linux-hardware.org/?probe=38f7c8653b) | Aug 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [deeafc23f9](https://linux-hardware.org/?probe=deeafc23f9) | Aug 03, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8da287a76b](https://linux-hardware.org/?probe=8da287a76b) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [9b314ec48b](https://linux-hardware.org/?probe=9b314ec48b) | Aug 01, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [1fa056944b](https://linux-hardware.org/?probe=1fa056944b) | Aug 01, 2023 |
| HP            | 620                         | Notebook    | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | Notebook    | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [c74f4bde19](https://linux-hardware.org/?probe=c74f4bde19) | Aug 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [6eb487950f](https://linux-hardware.org/?probe=6eb487950f) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [93d193bdbc](https://linux-hardware.org/?probe=93d193bdbc) | Aug 01, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [41cc0d3bfc](https://linux-hardware.org/?probe=41cc0d3bfc) | Aug 01, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [1fe93c22b0](https://linux-hardware.org/?probe=1fe93c22b0) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [4e2e9f1f7f](https://linux-hardware.org/?probe=4e2e9f1f7f) | Jul 31, 2023 |
| Dell          | 0M863N A00                  | Desktop     | [3c403d83cc](https://linux-hardware.org/?probe=3c403d83cc) | Jul 30, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [42bf6e1e48](https://linux-hardware.org/?probe=42bf6e1e48) | Jul 30, 2023 |
| Lenovo        | WEI6 15 ITL 82F2            | Notebook    | [d30f44ebbb](https://linux-hardware.org/?probe=d30f44ebbb) | Jul 30, 2023 |
| HP            | 530                         | Notebook    | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [edbd410baa](https://linux-hardware.org/?probe=edbd410baa) | Jul 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [d54ad601d0](https://linux-hardware.org/?probe=d54ad601d0) | Jul 26, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [238c98ee81](https://linux-hardware.org/?probe=238c98ee81) | Jul 26, 2023 |
| Unknown       | HX90                        | Desktop     | [ba2a06600a](https://linux-hardware.org/?probe=ba2a06600a) | Jul 25, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [64595670db](https://linux-hardware.org/?probe=64595670db) | Jul 25, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [73f6f39c67](https://linux-hardware.org/?probe=73f6f39c67) | Jul 25, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [ab11ab8316](https://linux-hardware.org/?probe=ab11ab8316) | Jul 25, 2023 |
| Unknown       | HX90                        | Desktop     | [25aeb91b82](https://linux-hardware.org/?probe=25aeb91b82) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [e065c16f2c](https://linux-hardware.org/?probe=e065c16f2c) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [46a76eeb81](https://linux-hardware.org/?probe=46a76eeb81) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [77ee44a9fe](https://linux-hardware.org/?probe=77ee44a9fe) | Jul 23, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [6a0b0513cd](https://linux-hardware.org/?probe=6a0b0513cd) | Jul 22, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [dec408556d](https://linux-hardware.org/?probe=dec408556d) | Jul 21, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [59cf8541b4](https://linux-hardware.org/?probe=59cf8541b4) | Jul 20, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [ceda2054b7](https://linux-hardware.org/?probe=ceda2054b7) | Jul 19, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [c3ec46f79e](https://linux-hardware.org/?probe=c3ec46f79e) | Jul 19, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [2986780209](https://linux-hardware.org/?probe=2986780209) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [e2cf7ed35f](https://linux-hardware.org/?probe=e2cf7ed35f) | Jul 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [97c2950df7](https://linux-hardware.org/?probe=97c2950df7) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [7843df6b43](https://linux-hardware.org/?probe=7843df6b43) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [140d426127](https://linux-hardware.org/?probe=140d426127) | Jul 18, 2023 |
| ASUSTek       | NARRA2                      | Desktop     | [4d18b60338](https://linux-hardware.org/?probe=4d18b60338) | Jul 18, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [be24f941c7](https://linux-hardware.org/?probe=be24f941c7) | Jul 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e790be3f6e](https://linux-hardware.org/?probe=e790be3f6e) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [f0f2c5a6a7](https://linux-hardware.org/?probe=f0f2c5a6a7) | Jul 17, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [295bc58365](https://linux-hardware.org/?probe=295bc58365) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [6070a533c5](https://linux-hardware.org/?probe=6070a533c5) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d589d40102](https://linux-hardware.org/?probe=d589d40102) | Jul 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7e0ff09c1f](https://linux-hardware.org/?probe=7e0ff09c1f) | Jul 15, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b189eebd1c](https://linux-hardware.org/?probe=b189eebd1c) | Jul 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [4271ad9e9b](https://linux-hardware.org/?probe=4271ad9e9b) | Jul 12, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [0d54b47098](https://linux-hardware.org/?probe=0d54b47098) | Jul 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [8f40997f5f](https://linux-hardware.org/?probe=8f40997f5f) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [7d19e6a8f5](https://linux-hardware.org/?probe=7d19e6a8f5) | Jul 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a2f3950062](https://linux-hardware.org/?probe=a2f3950062) | Jul 10, 2023 |
| Dell          | Precision M4800             | Notebook    | [ef29f43a6f](https://linux-hardware.org/?probe=ef29f43a6f) | Jul 09, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [6d96bf0f5b](https://linux-hardware.org/?probe=6d96bf0f5b) | Jul 09, 2023 |
| HP            | 620                         | Notebook    | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [b4d926a4bc](https://linux-hardware.org/?probe=b4d926a4bc) | Jul 08, 2023 |
| Dell          | Latitude 3380               | Notebook    | [b4403e7b15](https://linux-hardware.org/?probe=b4403e7b15) | Jul 07, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [31d5e724ba](https://linux-hardware.org/?probe=31d5e724ba) | Jul 07, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [f32ffc678f](https://linux-hardware.org/?probe=f32ffc678f) | Jul 07, 2023 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [3ad05bcf55](https://linux-hardware.org/?probe=3ad05bcf55) | Jul 06, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [84b5d3ce3c](https://linux-hardware.org/?probe=84b5d3ce3c) | Jul 06, 2023 |
| Dell          | Precision 7520              | Notebook    | [1bffd04c84](https://linux-hardware.org/?probe=1bffd04c84) | Jul 05, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [d27490cbe0](https://linux-hardware.org/?probe=d27490cbe0) | Jul 04, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [5b1b409a2f](https://linux-hardware.org/?probe=5b1b409a2f) | Jul 04, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [06ac15dcca](https://linux-hardware.org/?probe=06ac15dcca) | Jul 04, 2023 |
| Dell          | Precision 5560              | Notebook    | [5f8f3c917f](https://linux-hardware.org/?probe=5f8f3c917f) | Jul 04, 2023 |
| HP            | 21F5 0A                     | Desktop     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [075cc6eb8a](https://linux-hardware.org/?probe=075cc6eb8a) | Jul 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a6ceaae01b](https://linux-hardware.org/?probe=a6ceaae01b) | Jul 02, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [b4560fc1c1](https://linux-hardware.org/?probe=b4560fc1c1) | Jul 02, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [d04862302e](https://linux-hardware.org/?probe=d04862302e) | Jul 01, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [f771aedc9c](https://linux-hardware.org/?probe=f771aedc9c) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [6df0ae15e1](https://linux-hardware.org/?probe=6df0ae15e1) | Jul 01, 2023 |
| Acer          | Aspire 7715Z                | Notebook    | [b288a09d6e](https://linux-hardware.org/?probe=b288a09d6e) | Jul 01, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d3fb700ff1](https://linux-hardware.org/?probe=d3fb700ff1) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [d4a008aefb](https://linux-hardware.org/?probe=d4a008aefb) | Jun 30, 2023 |
| Dell          | Latitude 5440               | Notebook    | [7868400967](https://linux-hardware.org/?probe=7868400967) | Jun 30, 2023 |
| VALE          | Notebook Slim S132          | Notebook    | [3e381e10f7](https://linux-hardware.org/?probe=3e381e10f7) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [39f7adb927](https://linux-hardware.org/?probe=39f7adb927) | Jun 30, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [b8327a4d00](https://linux-hardware.org/?probe=b8327a4d00) | Jun 30, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [1f5a11092b](https://linux-hardware.org/?probe=1f5a11092b) | Jun 28, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [fcc6786de6](https://linux-hardware.org/?probe=fcc6786de6) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [99efa1a1c5](https://linux-hardware.org/?probe=99efa1a1c5) | Jun 24, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b7ac1c1ba6](https://linux-hardware.org/?probe=b7ac1c1ba6) | Jun 24, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [bf6de06fb9](https://linux-hardware.org/?probe=bf6de06fb9) | Jun 23, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [7f87bb5b32](https://linux-hardware.org/?probe=7f87bb5b32) | Jun 23, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac0a9c170f](https://linux-hardware.org/?probe=ac0a9c170f) | Jun 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [666f5d0ce5](https://linux-hardware.org/?probe=666f5d0ce5) | Jun 22, 2023 |
| MSI           | B450M PRO-VDH V2            | Desktop     | [88cdeeac94](https://linux-hardware.org/?probe=88cdeeac94) | Jun 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [3574f89b15](https://linux-hardware.org/?probe=3574f89b15) | Jun 21, 2023 |
| Acer          | Aspire F5-771G              | Notebook    | [034d235f5c](https://linux-hardware.org/?probe=034d235f5c) | Jun 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [b3e34f06a4](https://linux-hardware.org/?probe=b3e34f06a4) | Jun 19, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [601d7611be](https://linux-hardware.org/?probe=601d7611be) | Jun 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [192105166b](https://linux-hardware.org/?probe=192105166b) | Jun 14, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [e2df546273](https://linux-hardware.org/?probe=e2df546273) | Jun 13, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [bcfcd0b59d](https://linux-hardware.org/?probe=bcfcd0b59d) | Jun 13, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [50c975ae08](https://linux-hardware.org/?probe=50c975ae08) | Jun 13, 2023 |
| Emdoor        | AG958                       | Notebook    | [1688cc07b6](https://linux-hardware.org/?probe=1688cc07b6) | Jun 11, 2023 |
| ASUSTek       | X540SAA                     | Notebook    | [ea61fdd09a](https://linux-hardware.org/?probe=ea61fdd09a) | Jun 11, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [7d5fc6a209](https://linux-hardware.org/?probe=7d5fc6a209) | Jun 11, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [b46a96183b](https://linux-hardware.org/?probe=b46a96183b) | Jun 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [a302ecd3cd](https://linux-hardware.org/?probe=a302ecd3cd) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [43c70efbe7](https://linux-hardware.org/?probe=43c70efbe7) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [9a66179aaf](https://linux-hardware.org/?probe=9a66179aaf) | Jun 04, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [bfe6623b23](https://linux-hardware.org/?probe=bfe6623b23) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [c3dae64ee6](https://linux-hardware.org/?probe=c3dae64ee6) | Jun 03, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3fb05bfb0b](https://linux-hardware.org/?probe=3fb05bfb0b) | May 31, 2023 |
| Dell          | Latitude 5510               | Notebook    | [78bd1ae0e0](https://linux-hardware.org/?probe=78bd1ae0e0) | May 31, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [3718997542](https://linux-hardware.org/?probe=3718997542) | May 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [8ec80f5e43](https://linux-hardware.org/?probe=8ec80f5e43) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [1aa973f6bc](https://linux-hardware.org/?probe=1aa973f6bc) | May 28, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [fd8a08639d](https://linux-hardware.org/?probe=fd8a08639d) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9cbdd21a81](https://linux-hardware.org/?probe=9cbdd21a81) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [76a357994a](https://linux-hardware.org/?probe=76a357994a) | May 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [5a4cf4d2e3](https://linux-hardware.org/?probe=5a4cf4d2e3) | May 23, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [a7794f4f9e](https://linux-hardware.org/?probe=a7794f4f9e) | May 21, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| HP            | Elite x2 1013 G3            | Tablet      | [0da06960ac](https://linux-hardware.org/?probe=0da06960ac) | May 19, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [0dadbeca5b](https://linux-hardware.org/?probe=0dadbeca5b) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [0de060a93f](https://linux-hardware.org/?probe=0de060a93f) | May 18, 2023 |
| HP            | 0A54h                       | Desktop     | [76953e42f8](https://linux-hardware.org/?probe=76953e42f8) | May 18, 2023 |
| MSI           | GS70 2PC Stealth            | Notebook    | [254f42a469](https://linux-hardware.org/?probe=254f42a469) | May 18, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [05379205f4](https://linux-hardware.org/?probe=05379205f4) | May 18, 2023 |
| HP            | 620                         | Notebook    | [6b688ce696](https://linux-hardware.org/?probe=6b688ce696) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [874dcebbaa](https://linux-hardware.org/?probe=874dcebbaa) | May 17, 2023 |
| Dell          | 0M3F6C A01                  | Desktop     | [d0fc9b65d0](https://linux-hardware.org/?probe=d0fc9b65d0) | May 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1b931dc36f](https://linux-hardware.org/?probe=1b931dc36f) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [af16278f1e](https://linux-hardware.org/?probe=af16278f1e) | May 17, 2023 |
| Emdoor        | AG958                       | Notebook    | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f97e4e7fc1](https://linux-hardware.org/?probe=f97e4e7fc1) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | Notebook    | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [8e0efa6d0a](https://linux-hardware.org/?probe=8e0efa6d0a) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [ced38114fc](https://linux-hardware.org/?probe=ced38114fc) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [4bde221d90](https://linux-hardware.org/?probe=4bde221d90) | May 13, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [0a23198016](https://linux-hardware.org/?probe=0a23198016) | May 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [c0841ef7e1](https://linux-hardware.org/?probe=c0841ef7e1) | May 12, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ed18615cb3](https://linux-hardware.org/?probe=ed18615cb3) | May 11, 2023 |
| Medion        | E2292                       | Convertible | [116727a473](https://linux-hardware.org/?probe=116727a473) | May 11, 2023 |
| FriendlyEl... | NanoPi NEO3                 | Soc         | [5384ed47e6](https://linux-hardware.org/?probe=5384ed47e6) | May 10, 2023 |
| FriendlyEl... | NanoPi NEO3                 | Soc         | [c182a0679c](https://linux-hardware.org/?probe=c182a0679c) | May 10, 2023 |
| ASUSTek       | UX410UAK                    | Notebook    | [d68a2bc7c0](https://linux-hardware.org/?probe=d68a2bc7c0) | May 10, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9ce4debe84](https://linux-hardware.org/?probe=9ce4debe84) | May 09, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [434f1425a4](https://linux-hardware.org/?probe=434f1425a4) | May 09, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [9a4e4763d4](https://linux-hardware.org/?probe=9a4e4763d4) | May 09, 2023 |
| MSI           | Katana 17 B12UCXK           | Notebook    | [15b9d97c10](https://linux-hardware.org/?probe=15b9d97c10) | May 09, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [e7ffe2585f](https://linux-hardware.org/?probe=e7ffe2585f) | May 09, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [29d129229b](https://linux-hardware.org/?probe=29d129229b) | May 08, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [ddf0cb8a28](https://linux-hardware.org/?probe=ddf0cb8a28) | May 08, 2023 |
| Dell          | Latitude 7390               | Notebook    | [dc5c96e431](https://linux-hardware.org/?probe=dc5c96e431) | May 08, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| MSI           | CR61 3M                     | Notebook    | [f41852fa6e](https://linux-hardware.org/?probe=f41852fa6e) | May 07, 2023 |
| MSI           | CR61 3M                     | Notebook    | [7b5d49d859](https://linux-hardware.org/?probe=7b5d49d859) | May 07, 2023 |
| MSI           | GS70 2PC Stealth            | Notebook    | [370f9304b6](https://linux-hardware.org/?probe=370f9304b6) | May 07, 2023 |
| Intel         | DP43TF AAE34878-403         | Desktop     | [9d5ca00c7c](https://linux-hardware.org/?probe=9d5ca00c7c) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [6bea90b569](https://linux-hardware.org/?probe=6bea90b569) | May 07, 2023 |
| Intel         | DP43TF AAE34878-403         | Desktop     | [6353d110f5](https://linux-hardware.org/?probe=6353d110f5) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [db0ab14831](https://linux-hardware.org/?probe=db0ab14831) | May 07, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [1eddb3203a](https://linux-hardware.org/?probe=1eddb3203a) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [2e02937097](https://linux-hardware.org/?probe=2e02937097) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [051da44921](https://linux-hardware.org/?probe=051da44921) | May 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6a54ace5f8](https://linux-hardware.org/?probe=6a54ace5f8) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [68c7b6891b](https://linux-hardware.org/?probe=68c7b6891b) | May 06, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [b0464a0b99](https://linux-hardware.org/?probe=b0464a0b99) | May 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c490e68d59](https://linux-hardware.org/?probe=c490e68d59) | May 03, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [16ac84221b](https://linux-hardware.org/?probe=16ac84221b) | May 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [29636a9923](https://linux-hardware.org/?probe=29636a9923) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [7bb2ae638b](https://linux-hardware.org/?probe=7bb2ae638b) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [bd0458e8a9](https://linux-hardware.org/?probe=bd0458e8a9) | May 01, 2023 |
| Medion        | P6630                       | Notebook    | [93abad41dd](https://linux-hardware.org/?probe=93abad41dd) | Apr 30, 2023 |
| Dell          | Latitude 5521               | Notebook    | [1629b4efc4](https://linux-hardware.org/?probe=1629b4efc4) | Apr 30, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [ff24454021](https://linux-hardware.org/?probe=ff24454021) | Apr 29, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [fa805f77f7](https://linux-hardware.org/?probe=fa805f77f7) | Apr 29, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [9081fc703d](https://linux-hardware.org/?probe=9081fc703d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S56G00    | Notebook    | [8da21e9a17](https://linux-hardware.org/?probe=8da21e9a17) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [f8aee85cd4](https://linux-hardware.org/?probe=f8aee85cd4) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d138bfdf52](https://linux-hardware.org/?probe=d138bfdf52) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [f4d7a6ed92](https://linux-hardware.org/?probe=f4d7a6ed92) | Apr 28, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [15b900cf50](https://linux-hardware.org/?probe=15b900cf50) | Apr 27, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [d5b1ec921a](https://linux-hardware.org/?probe=d5b1ec921a) | Apr 27, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [de581801e8](https://linux-hardware.org/?probe=de581801e8) | Apr 27, 2023 |
| Dell          | Latitude E6440              | Notebook    | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [cb64c7f963](https://linux-hardware.org/?probe=cb64c7f963) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | Notebook    | [2e542c241d](https://linux-hardware.org/?probe=2e542c241d) | Apr 25, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [0e79aaac72](https://linux-hardware.org/?probe=0e79aaac72) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [d7e9027e6a](https://linux-hardware.org/?probe=d7e9027e6a) | Apr 24, 2023 |
| Emdoor        | AG958                       | Notebook    | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [60251e08f5](https://linux-hardware.org/?probe=60251e08f5) | Apr 22, 2023 |
| Dell          | Latitude E6330              | Notebook    | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d342e4d24c](https://linux-hardware.org/?probe=d342e4d24c) | Apr 22, 2023 |
| Emdoor        | AG958                       | Notebook    | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | Notebook    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [841c2f241b](https://linux-hardware.org/?probe=841c2f241b) | Apr 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [e3ebb38e6b](https://linux-hardware.org/?probe=e3ebb38e6b) | Apr 19, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [5b77cc21f4](https://linux-hardware.org/?probe=5b77cc21f4) | Apr 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [efdcb6b99e](https://linux-hardware.org/?probe=efdcb6b99e) | Apr 18, 2023 |
| Dell          | 0J4NFV A01                  | Desktop     | [a6b3ac3ff2](https://linux-hardware.org/?probe=a6b3ac3ff2) | Apr 17, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [38aeb226af](https://linux-hardware.org/?probe=38aeb226af) | Apr 17, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [1a55ffc593](https://linux-hardware.org/?probe=1a55ffc593) | Apr 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [7230f64c9b](https://linux-hardware.org/?probe=7230f64c9b) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [a7f312ea0a](https://linux-hardware.org/?probe=a7f312ea0a) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [f1afe43806](https://linux-hardware.org/?probe=f1afe43806) | Apr 16, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [f44bbda528](https://linux-hardware.org/?probe=f44bbda528) | Apr 16, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6ac02f43f2](https://linux-hardware.org/?probe=6ac02f43f2) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| HP            | 0A5Ch                       | Desktop     | [636d94a346](https://linux-hardware.org/?probe=636d94a346) | Apr 15, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | Notebook    | [b87471108a](https://linux-hardware.org/?probe=b87471108a) | Apr 14, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [43d0d0a55e](https://linux-hardware.org/?probe=43d0d0a55e) | Apr 14, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS29J05    | Notebook    | [60c50f0a10](https://linux-hardware.org/?probe=60c50f0a10) | Apr 13, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [6037aee790](https://linux-hardware.org/?probe=6037aee790) | Apr 11, 2023 |
| Sony          | SVE1713A1EW                 | Notebook    | [402fae93d5](https://linux-hardware.org/?probe=402fae93d5) | Apr 09, 2023 |
| MSI           | B150M BAZOOKA               | Desktop     | [ce60e4a299](https://linux-hardware.org/?probe=ce60e4a299) | Apr 08, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [269e742eb7](https://linux-hardware.org/?probe=269e742eb7) | Apr 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b220308aa1](https://linux-hardware.org/?probe=b220308aa1) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [00fef3bb7b](https://linux-hardware.org/?probe=00fef3bb7b) | Apr 06, 2023 |
| HP            | 620                         | Notebook    | [ad46cdbb0d](https://linux-hardware.org/?probe=ad46cdbb0d) | Apr 06, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | Notebook    | [d9d2e73619](https://linux-hardware.org/?probe=d9d2e73619) | Apr 05, 2023 |
| Medion        | BTDD-EAIO                   | All in one  | [2bbf3378ef](https://linux-hardware.org/?probe=2bbf3378ef) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [8eb8bb5119](https://linux-hardware.org/?probe=8eb8bb5119) | Apr 03, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [95a98c59b1](https://linux-hardware.org/?probe=95a98c59b1) | Apr 03, 2023 |
| Clevo         | P170HMx                     | Notebook    | [c963b350fc](https://linux-hardware.org/?probe=c963b350fc) | Apr 03, 2023 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [0aefaba90e](https://linux-hardware.org/?probe=0aefaba90e) | Apr 03, 2023 |
| HP            | 8430 1000                   | All in one  | [380754e2f6](https://linux-hardware.org/?probe=380754e2f6) | Apr 02, 2023 |
| HP            | 3397                        | Desktop     | [04943f0d5f](https://linux-hardware.org/?probe=04943f0d5f) | Apr 02, 2023 |
| AZW           | Speed S                     | Notebook    | [52292a4968](https://linux-hardware.org/?probe=52292a4968) | Apr 02, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [12319c9ee3](https://linux-hardware.org/?probe=12319c9ee3) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [98cd4ea3a6](https://linux-hardware.org/?probe=98cd4ea3a6) | Apr 01, 2023 |
| HP            | Pavilion g7                 | Notebook    | [7820d2ca67](https://linux-hardware.org/?probe=7820d2ca67) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [0ff3ab318e](https://linux-hardware.org/?probe=0ff3ab318e) | Mar 31, 2023 |
| HP            | Compaq 6730b (GB987ET#UU... | Notebook    | [6c6ceb9bc3](https://linux-hardware.org/?probe=6c6ceb9bc3) | Mar 31, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [01492665ee](https://linux-hardware.org/?probe=01492665ee) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0b4fae8189](https://linux-hardware.org/?probe=0b4fae8189) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [13acfd725a](https://linux-hardware.org/?probe=13acfd725a) | Mar 31, 2023 |
| Medion        | MS-7728                     | Desktop     | [cf66e81623](https://linux-hardware.org/?probe=cf66e81623) | Mar 31, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c73c5374a4](https://linux-hardware.org/?probe=c73c5374a4) | Mar 30, 2023 |
| Medion        | P8614                       | Notebook    | [a66fe7042e](https://linux-hardware.org/?probe=a66fe7042e) | Mar 29, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7e04c0e7cd](https://linux-hardware.org/?probe=7e04c0e7cd) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| MSI           | GT70                        | Notebook    | [8b00b28b12](https://linux-hardware.org/?probe=8b00b28b12) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [fe5c568f41](https://linux-hardware.org/?probe=fe5c568f41) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [778f5948f1](https://linux-hardware.org/?probe=778f5948f1) | Mar 26, 2023 |
| Dell          | Latitude E6330              | Notebook    | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eeeac5db0f](https://linux-hardware.org/?probe=eeeac5db0f) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [311e49c553](https://linux-hardware.org/?probe=311e49c553) | Mar 23, 2023 |
| Alienware     | m17 R3                      | Notebook    | [6c62c223ed](https://linux-hardware.org/?probe=6c62c223ed) | Mar 21, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [7622701d31](https://linux-hardware.org/?probe=7622701d31) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [846f31de3e](https://linux-hardware.org/?probe=846f31de3e) | Mar 21, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [2ef61db0a6](https://linux-hardware.org/?probe=2ef61db0a6) | Mar 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [837ed83646](https://linux-hardware.org/?probe=837ed83646) | Mar 18, 2023 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5a70cf923e](https://linux-hardware.org/?probe=5a70cf923e) | Mar 18, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | Notebook    | [1825764856](https://linux-hardware.org/?probe=1825764856) | Mar 17, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| Intel         | NUC8i7HVB J68196-602        | Mini pc     | [68b65fda4c](https://linux-hardware.org/?probe=68b65fda4c) | Mar 15, 2023 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [13a4e703dc](https://linux-hardware.org/?probe=13a4e703dc) | Mar 14, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [cde6fff1ad](https://linux-hardware.org/?probe=cde6fff1ad) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | Notebook    | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | Notebook    | [2c01c1fd0e](https://linux-hardware.org/?probe=2c01c1fd0e) | Mar 11, 2023 |
| MSI           | H270 GAMING M3              | Desktop     | [dfbb481b02](https://linux-hardware.org/?probe=dfbb481b02) | Mar 11, 2023 |
| Medion        | Akoya E1318T                | Notebook    | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| ASUSTek       | K52F                        | Notebook    | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [a63cd6d4aa](https://linux-hardware.org/?probe=a63cd6d4aa) | Mar 09, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [0dc84b30aa](https://linux-hardware.org/?probe=0dc84b30aa) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [72eed5b458](https://linux-hardware.org/?probe=72eed5b458) | Mar 08, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [1563e26ae3](https://linux-hardware.org/?probe=1563e26ae3) | Mar 07, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [44b690055c](https://linux-hardware.org/?probe=44b690055c) | Mar 07, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [d595ae284e](https://linux-hardware.org/?probe=d595ae284e) | Mar 07, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8f08518290](https://linux-hardware.org/?probe=8f08518290) | Mar 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [819f8b1cad](https://linux-hardware.org/?probe=819f8b1cad) | Mar 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [e560390e4f](https://linux-hardware.org/?probe=e560390e4f) | Mar 05, 2023 |
| Lenovo        | ThinkCentre XXXX 739527G    | Desktop     | [c3e39b21f9](https://linux-hardware.org/?probe=c3e39b21f9) | Mar 05, 2023 |
| Acer          | Aspire 6530G                | Notebook    | [a4077c8432](https://linux-hardware.org/?probe=a4077c8432) | Mar 05, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c2f98c3014](https://linux-hardware.org/?probe=c2f98c3014) | Mar 05, 2023 |
| Toshiba       | Satellite C855-112          | Notebook    | [8635f2eecd](https://linux-hardware.org/?probe=8635f2eecd) | Mar 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [d850dacb6a](https://linux-hardware.org/?probe=d850dacb6a) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ac3640b913](https://linux-hardware.org/?probe=ac3640b913) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [0cd2798326](https://linux-hardware.org/?probe=0cd2798326) | Mar 03, 2023 |
| HP            | 620                         | Notebook    | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a877190b1c](https://linux-hardware.org/?probe=a877190b1c) | Mar 02, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [639a660b02](https://linux-hardware.org/?probe=639a660b02) | Mar 02, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f441cc82e4](https://linux-hardware.org/?probe=f441cc82e4) | Mar 01, 2023 |
| ASUSTek       | F70SL                       | Notebook    | [5870cf8326](https://linux-hardware.org/?probe=5870cf8326) | Mar 01, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b1d7964fc7](https://linux-hardware.org/?probe=b1d7964fc7) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [0710c7be6e](https://linux-hardware.org/?probe=0710c7be6e) | Feb 28, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [057c307bf5](https://linux-hardware.org/?probe=057c307bf5) | Feb 28, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [4acd4aa811](https://linux-hardware.org/?probe=4acd4aa811) | Feb 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [068ad292bd](https://linux-hardware.org/?probe=068ad292bd) | Feb 27, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [41330b2783](https://linux-hardware.org/?probe=41330b2783) | Feb 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [de7aec7f12](https://linux-hardware.org/?probe=de7aec7f12) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e7bf168729](https://linux-hardware.org/?probe=e7bf168729) | Feb 25, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e257e205bf](https://linux-hardware.org/?probe=e257e205bf) | Feb 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [950130a7b4](https://linux-hardware.org/?probe=950130a7b4) | Feb 23, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [c2117fed20](https://linux-hardware.org/?probe=c2117fed20) | Feb 22, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [abfe4c823a](https://linux-hardware.org/?probe=abfe4c823a) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | Notebook    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7e5789e02b](https://linux-hardware.org/?probe=7e5789e02b) | Feb 21, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJA0... | Convertible | [aba497a637](https://linux-hardware.org/?probe=aba497a637) | Feb 21, 2023 |
| HP            | 1850                        | Desktop     | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [da5050e2f8](https://linux-hardware.org/?probe=da5050e2f8) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [b335ec1cc3](https://linux-hardware.org/?probe=b335ec1cc3) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | Notebook    | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Medion        | MS-7800                     | Desktop     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [9eca2efc88](https://linux-hardware.org/?probe=9eca2efc88) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | Notebook    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [09b0c2bf17](https://linux-hardware.org/?probe=09b0c2bf17) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Notebook    | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [caeb6bc93f](https://linux-hardware.org/?probe=caeb6bc93f) | Feb 17, 2023 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [4a92de7e43](https://linux-hardware.org/?probe=4a92de7e43) | Feb 17, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [2a14385869](https://linux-hardware.org/?probe=2a14385869) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [c0d18ab501](https://linux-hardware.org/?probe=c0d18ab501) | Feb 12, 2023 |
| Packard Be... | DOT S                       | Notebook    | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [9c458e5a66](https://linux-hardware.org/?probe=9c458e5a66) | Feb 11, 2023 |
| Acer          | Aspire V5-122               | Notebook    | [99fd12250b](https://linux-hardware.org/?probe=99fd12250b) | Feb 10, 2023 |
| Teclast       | F15S                        | Notebook    | [951ded8432](https://linux-hardware.org/?probe=951ded8432) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [997020aeb0](https://linux-hardware.org/?probe=997020aeb0) | Feb 08, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [c90f2404df](https://linux-hardware.org/?probe=c90f2404df) | Feb 08, 2023 |
| Dell          | 06JWJY A01                  | Desktop     | [ee53c6f627](https://linux-hardware.org/?probe=ee53c6f627) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [870ba1caa7](https://linux-hardware.org/?probe=870ba1caa7) | Feb 07, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [81ece9483e](https://linux-hardware.org/?probe=81ece9483e) | Feb 07, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| Medion        | P6624                       | Notebook    | [5a31124376](https://linux-hardware.org/?probe=5a31124376) | Feb 06, 2023 |
| BESSTAR Te... | CB9                         | Mini pc     | [23fe29b164](https://linux-hardware.org/?probe=23fe29b164) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [62e1e79469](https://linux-hardware.org/?probe=62e1e79469) | Feb 03, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a630801a13](https://linux-hardware.org/?probe=a630801a13) | Feb 03, 2023 |
| Dell          | Precision 7550              | Notebook    | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [72bdb7165c](https://linux-hardware.org/?probe=72bdb7165c) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [2261a77abb](https://linux-hardware.org/?probe=2261a77abb) | Feb 01, 2023 |
| Google        | Pantheon                    | Notebook    | [12e0b96dd1](https://linux-hardware.org/?probe=12e0b96dd1) | Feb 01, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [8641149603](https://linux-hardware.org/?probe=8641149603) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [f6be582448](https://linux-hardware.org/?probe=f6be582448) | Jan 30, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [358b908129](https://linux-hardware.org/?probe=358b908129) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| HP            | 89E9 0100                   | All in one  | [f5311b2134](https://linux-hardware.org/?probe=f5311b2134) | Jan 28, 2023 |
| HP            | 89E9 0100                   | All in one  | [4afdd5b9fc](https://linux-hardware.org/?probe=4afdd5b9fc) | Jan 28, 2023 |
| Acer          | Peppy                       | Notebook    | [9a16262be8](https://linux-hardware.org/?probe=9a16262be8) | Jan 27, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [77a6b88d58](https://linux-hardware.org/?probe=77a6b88d58) | Jan 27, 2023 |
| Intel         | DG965SS AAD41678-306        | Desktop     | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| MSI           | Z270 GAMING M5              | Desktop     | [218f278cab](https://linux-hardware.org/?probe=218f278cab) | Jan 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [85ad9c7e62](https://linux-hardware.org/?probe=85ad9c7e62) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| HP            | 304Ah                       | Desktop     | [a41a25807f](https://linux-hardware.org/?probe=a41a25807f) | Jan 25, 2023 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [37c4aa5f03](https://linux-hardware.org/?probe=37c4aa5f03) | Jan 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2c8424ac3d](https://linux-hardware.org/?probe=2c8424ac3d) | Jan 22, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [19bb445ee4](https://linux-hardware.org/?probe=19bb445ee4) | Jan 22, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [6228476153](https://linux-hardware.org/?probe=6228476153) | Jan 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Medion        | P6624                       | Notebook    | [344d427f44](https://linux-hardware.org/?probe=344d427f44) | Jan 20, 2023 |
| HP            | 843B                        | Desktop     | [2af17234ba](https://linux-hardware.org/?probe=2af17234ba) | Jan 20, 2023 |
| Dell          | Latitude 5320               | Notebook    | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9476823c0b](https://linux-hardware.org/?probe=9476823c0b) | Jan 19, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| MSI           | Katana GF76 11UC            | Notebook    | [8c0b32cf24](https://linux-hardware.org/?probe=8c0b32cf24) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f3b27e21a7](https://linux-hardware.org/?probe=f3b27e21a7) | Jan 16, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [c06c7eedaf](https://linux-hardware.org/?probe=c06c7eedaf) | Jan 16, 2023 |
| Medion        | MS-7501                     | Desktop     | [abd269d539](https://linux-hardware.org/?probe=abd269d539) | Jan 15, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9fe6c51640](https://linux-hardware.org/?probe=9fe6c51640) | Jan 15, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [e3b9b73877](https://linux-hardware.org/?probe=e3b9b73877) | Jan 14, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [406649acdf](https://linux-hardware.org/?probe=406649acdf) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f59adc6dcd](https://linux-hardware.org/?probe=f59adc6dcd) | Jan 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [bbecf2579c](https://linux-hardware.org/?probe=bbecf2579c) | Jan 13, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [425fb5340d](https://linux-hardware.org/?probe=425fb5340d) | Jan 13, 2023 |
| HP            | 3397                        | Desktop     | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | Notebook    | [10c4bcf564](https://linux-hardware.org/?probe=10c4bcf564) | Jan 12, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [60c16871ac](https://linux-hardware.org/?probe=60c16871ac) | Jan 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8193577e0b](https://linux-hardware.org/?probe=8193577e0b) | Jan 11, 2023 |
| HP            | Pavilion dv6000 (RY604EA... | Notebook    | [a8ec5eb86a](https://linux-hardware.org/?probe=a8ec5eb86a) | Jan 11, 2023 |
| Acer          | Aspire 7560                 | Notebook    | [58cd9d7ad2](https://linux-hardware.org/?probe=58cd9d7ad2) | Jan 09, 2023 |
| Dell          | XPS L521X                   | Notebook    | [2930493243](https://linux-hardware.org/?probe=2930493243) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [0f1543c21d](https://linux-hardware.org/?probe=0f1543c21d) | Jan 09, 2023 |
| Notebook      | P7xxDM3(-G)                 | Notebook    | [7cafa98138](https://linux-hardware.org/?probe=7cafa98138) | Jan 08, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d1eaa576e7](https://linux-hardware.org/?probe=d1eaa576e7) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [4673ec60ea](https://linux-hardware.org/?probe=4673ec60ea) | Jan 07, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [cbd020e86f](https://linux-hardware.org/?probe=cbd020e86f) | Jan 07, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [bb893b2d93](https://linux-hardware.org/?probe=bb893b2d93) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [89eccb038f](https://linux-hardware.org/?probe=89eccb038f) | Jan 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [458cb8c4de](https://linux-hardware.org/?probe=458cb8c4de) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a84d0d7b42](https://linux-hardware.org/?probe=a84d0d7b42) | Jan 06, 2023 |
| Medion        | S4214                       | Notebook    | [58131e715e](https://linux-hardware.org/?probe=58131e715e) | Jan 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [9f029a8cdb](https://linux-hardware.org/?probe=9f029a8cdb) | Jan 06, 2023 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [b1911d1ae5](https://linux-hardware.org/?probe=b1911d1ae5) | Jan 01, 2023 |
| Dell          | System XPS L702X            | Notebook    | [7030c340cc](https://linux-hardware.org/?probe=7030c340cc) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0A    | Notebook    | [82168627b7](https://linux-hardware.org/?probe=82168627b7) | Dec 31, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| HP            | Notebook                    | Notebook    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Acer          | Aspire M3920                | Desktop     | [49cb4f51a8](https://linux-hardware.org/?probe=49cb4f51a8) | Dec 28, 2022 |
| Dell          | Latitude 5580               | Notebook    | [7c006e8c6d](https://linux-hardware.org/?probe=7c006e8c6d) | Dec 28, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [bf50da5153](https://linux-hardware.org/?probe=bf50da5153) | Dec 28, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [415c0ff63e](https://linux-hardware.org/?probe=415c0ff63e) | Dec 27, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [9eee40dd50](https://linux-hardware.org/?probe=9eee40dd50) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [5d26c7c543](https://linux-hardware.org/?probe=5d26c7c543) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9811949dd](https://linux-hardware.org/?probe=e9811949dd) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| HP            | 0AACh                       | Desktop     | [b83da338ee](https://linux-hardware.org/?probe=b83da338ee) | Dec 25, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | Stream x360 Convertible ... | Convertible | [e01713ca07](https://linux-hardware.org/?probe=e01713ca07) | Dec 24, 2022 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [355d32cbac](https://linux-hardware.org/?probe=355d32cbac) | Dec 24, 2022 |
| HP            | 0AACh                       | Desktop     | [4a7840e1cf](https://linux-hardware.org/?probe=4a7840e1cf) | Dec 24, 2022 |
| HP            | Pavilion g7                 | Notebook    | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Sony          | SVS1311N9ES                 | Notebook    | [5c1a4bed5b](https://linux-hardware.org/?probe=5c1a4bed5b) | Dec 24, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d407c538c4](https://linux-hardware.org/?probe=d407c538c4) | Dec 24, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [59d46f37db](https://linux-hardware.org/?probe=59d46f37db) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a2d763d722](https://linux-hardware.org/?probe=a2d763d722) | Dec 21, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [60683b36c2](https://linux-hardware.org/?probe=60683b36c2) | Dec 20, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [d854f4c5ad](https://linux-hardware.org/?probe=d854f4c5ad) | Dec 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [2f061a6d8d](https://linux-hardware.org/?probe=2f061a6d8d) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Dell          | 0D6H9T A03                  | Desktop     | [835cdeea5e](https://linux-hardware.org/?probe=835cdeea5e) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | Notebook    | [6c56016ed0](https://linux-hardware.org/?probe=6c56016ed0) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | Notebook    | [abd93a5cca](https://linux-hardware.org/?probe=abd93a5cca) | Dec 19, 2022 |
| HP            | ProBook 6570b               | Notebook    | [4deb8fc518](https://linux-hardware.org/?probe=4deb8fc518) | Dec 19, 2022 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [3684f593d4](https://linux-hardware.org/?probe=3684f593d4) | Dec 18, 2022 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | Desktop     | [15f724ada5](https://linux-hardware.org/?probe=15f724ada5) | Dec 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [9c513daaf3](https://linux-hardware.org/?probe=9c513daaf3) | Dec 17, 2022 |
| Medion        | WIM2210                     | Notebook    | [d1a64f7b3b](https://linux-hardware.org/?probe=d1a64f7b3b) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [c17bee3b4a](https://linux-hardware.org/?probe=c17bee3b4a) | Dec 17, 2022 |
| Lenovo        | ThinkPad T570 20H9S04C00    | Notebook    | [f3093ba13c](https://linux-hardware.org/?probe=f3093ba13c) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [26aae3342c](https://linux-hardware.org/?probe=26aae3342c) | Dec 16, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [4e9bbbaa1f](https://linux-hardware.org/?probe=4e9bbbaa1f) | Dec 16, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1398958777](https://linux-hardware.org/?probe=1398958777) | Dec 14, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [88c6ca8956](https://linux-hardware.org/?probe=88c6ca8956) | Dec 14, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e008a86cd5](https://linux-hardware.org/?probe=e008a86cd5) | Dec 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [45efd7615d](https://linux-hardware.org/?probe=45efd7615d) | Dec 12, 2022 |
| Lenovo        | ThinkPad T430 2349L26       | Notebook    | [9d0bcbdc75](https://linux-hardware.org/?probe=9d0bcbdc75) | Dec 11, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [d1b6c31805](https://linux-hardware.org/?probe=d1b6c31805) | Dec 09, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [69e83bcd80](https://linux-hardware.org/?probe=69e83bcd80) | Dec 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| Lenovo        | ThinkPad T520 4243CJ2       | Notebook    | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [7ba193202d](https://linux-hardware.org/?probe=7ba193202d) | Dec 08, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [5e5a1fd920](https://linux-hardware.org/?probe=5e5a1fd920) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [185bfcb7fa](https://linux-hardware.org/?probe=185bfcb7fa) | Dec 04, 2022 |
| HP            | Pavilion Laptop             | Notebook    | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [6dbc014a04](https://linux-hardware.org/?probe=6dbc014a04) | Dec 03, 2022 |
| HP            | ProBook 6550b               | Notebook    | [564bf050f2](https://linux-hardware.org/?probe=564bf050f2) | Dec 02, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [cccf492c06](https://linux-hardware.org/?probe=cccf492c06) | Dec 01, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [4c7e1d5bc4](https://linux-hardware.org/?probe=4c7e1d5bc4) | Dec 01, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [bb49870780](https://linux-hardware.org/?probe=bb49870780) | Nov 28, 2022 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [b6af703e1a](https://linux-hardware.org/?probe=b6af703e1a) | Nov 28, 2022 |
| Dell          | G3 3779                     | Notebook    | [1cf1d8aa20](https://linux-hardware.org/?probe=1cf1d8aa20) | Nov 26, 2022 |
| Dell          | G3 3779                     | Notebook    | [4bc02c1721](https://linux-hardware.org/?probe=4bc02c1721) | Nov 26, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [2eb5cc0a12](https://linux-hardware.org/?probe=2eb5cc0a12) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [c0102f2633](https://linux-hardware.org/?probe=c0102f2633) | Nov 25, 2022 |
| Acer          | NC-ES1-512-C3AH             | Notebook    | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [62e12083b5](https://linux-hardware.org/?probe=62e12083b5) | Nov 23, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [495d972ae3](https://linux-hardware.org/?probe=495d972ae3) | Nov 23, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [66383ce902](https://linux-hardware.org/?probe=66383ce902) | Nov 22, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [0354f9cb0e](https://linux-hardware.org/?probe=0354f9cb0e) | Nov 21, 2022 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [c6b206401a](https://linux-hardware.org/?probe=c6b206401a) | Nov 21, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [d7ee80553a](https://linux-hardware.org/?probe=d7ee80553a) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [f55a45b87f](https://linux-hardware.org/?probe=f55a45b87f) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e3d6c78ed4](https://linux-hardware.org/?probe=e3d6c78ed4) | Nov 20, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [dfd1c98a18](https://linux-hardware.org/?probe=dfd1c98a18) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [de8b7d8220](https://linux-hardware.org/?probe=de8b7d8220) | Nov 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [a7ca712256](https://linux-hardware.org/?probe=a7ca712256) | Nov 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [571dc553f9](https://linux-hardware.org/?probe=571dc553f9) | Nov 19, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d0d37dd251](https://linux-hardware.org/?probe=d0d37dd251) | Nov 17, 2022 |
| Dell          | Latitude 5530               | Notebook    | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [7c8d905b3d](https://linux-hardware.org/?probe=7c8d905b3d) | Nov 17, 2022 |
| Dell          | Precision 7560              | Notebook    | [0ee8814502](https://linux-hardware.org/?probe=0ee8814502) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9876aa0fd](https://linux-hardware.org/?probe=c9876aa0fd) | Nov 16, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [f56f2c6a53](https://linux-hardware.org/?probe=f56f2c6a53) | Nov 14, 2022 |
| ASRock        | B660M-HDV                   | Desktop     | [eeaa5c82ea](https://linux-hardware.org/?probe=eeaa5c82ea) | Nov 13, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [94e5dec391](https://linux-hardware.org/?probe=94e5dec391) | Nov 12, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [929685d936](https://linux-hardware.org/?probe=929685d936) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [331a1db69d](https://linux-hardware.org/?probe=331a1db69d) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [d703e1c63c](https://linux-hardware.org/?probe=d703e1c63c) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| Acer          | Aspire 1825PTZ              | Notebook    | [c2dc801a81](https://linux-hardware.org/?probe=c2dc801a81) | Nov 09, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [9fda4c3798](https://linux-hardware.org/?probe=9fda4c3798) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [25756ad3c1](https://linux-hardware.org/?probe=25756ad3c1) | Nov 07, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [5505ec9b09](https://linux-hardware.org/?probe=5505ec9b09) | Nov 06, 2022 |
| HP            | Pavilion 17                 | Notebook    | [958de69d5b](https://linux-hardware.org/?probe=958de69d5b) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [4e35f6b15e](https://linux-hardware.org/?probe=4e35f6b15e) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [3e390c5fb3](https://linux-hardware.org/?probe=3e390c5fb3) | Nov 04, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [0f4bdc1677](https://linux-hardware.org/?probe=0f4bdc1677) | Nov 04, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [3e8fbc43d7](https://linux-hardware.org/?probe=3e8fbc43d7) | Nov 04, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [ff19454b61](https://linux-hardware.org/?probe=ff19454b61) | Nov 04, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e7254fb467](https://linux-hardware.org/?probe=e7254fb467) | Nov 04, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [2069a0e7fc](https://linux-hardware.org/?probe=2069a0e7fc) | Nov 02, 2022 |
| Dell          | Latitude 5580               | Notebook    | [92545fb976](https://linux-hardware.org/?probe=92545fb976) | Nov 02, 2022 |
| Dell          | Precision 7550              | Notebook    | [2065f4ab5f](https://linux-hardware.org/?probe=2065f4ab5f) | Nov 02, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [95e2a1e7d9](https://linux-hardware.org/?probe=95e2a1e7d9) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [4eff9900f2](https://linux-hardware.org/?probe=4eff9900f2) | Oct 28, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [6cfd4bdb14](https://linux-hardware.org/?probe=6cfd4bdb14) | Oct 28, 2022 |
| PC Special... | Recoil II                   | Notebook    | [9ec5a6ef20](https://linux-hardware.org/?probe=9ec5a6ef20) | Oct 27, 2022 |
| PC Special... | Recoil II                   | Notebook    | [38ec5a7708](https://linux-hardware.org/?probe=38ec5a7708) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [7527f4a200](https://linux-hardware.org/?probe=7527f4a200) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [1f6fc12b09](https://linux-hardware.org/?probe=1f6fc12b09) | Oct 25, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [18dad8d151](https://linux-hardware.org/?probe=18dad8d151) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [76fa0d836f](https://linux-hardware.org/?probe=76fa0d836f) | Oct 25, 2022 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [0d21d658ee](https://linux-hardware.org/?probe=0d21d658ee) | Oct 24, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [0e12d15b78](https://linux-hardware.org/?probe=0e12d15b78) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8b0377a420](https://linux-hardware.org/?probe=8b0377a420) | Oct 24, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [f82a2d8d8e](https://linux-hardware.org/?probe=f82a2d8d8e) | Oct 23, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [25295c680c](https://linux-hardware.org/?probe=25295c680c) | Oct 23, 2022 |
| ASUSTek       | P9X79 WS                    | Desktop     | [86f91e4898](https://linux-hardware.org/?probe=86f91e4898) | Oct 23, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a7bffc7d13](https://linux-hardware.org/?probe=a7bffc7d13) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [e34cb7ea31](https://linux-hardware.org/?probe=e34cb7ea31) | Oct 20, 2022 |
| Lenovo        | ThinkPad E590 20NB002BMB    | Notebook    | [4b272ef951](https://linux-hardware.org/?probe=4b272ef951) | Oct 20, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [aa8a459961](https://linux-hardware.org/?probe=aa8a459961) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9d471dbf37](https://linux-hardware.org/?probe=9d471dbf37) | Oct 18, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [f6c1e8e061](https://linux-hardware.org/?probe=f6c1e8e061) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| Shuttle       | FS81                        | Desktop     | [61c0ca02f3](https://linux-hardware.org/?probe=61c0ca02f3) | Oct 16, 2022 |
| ASUSTek       | GD30CI                      | Desktop     | [e002a9ef5c](https://linux-hardware.org/?probe=e002a9ef5c) | Oct 16, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [fda3302752](https://linux-hardware.org/?probe=fda3302752) | Oct 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [76f457f2aa](https://linux-hardware.org/?probe=76f457f2aa) | Oct 16, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c22c1df016](https://linux-hardware.org/?probe=c22c1df016) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [870d58dd75](https://linux-hardware.org/?probe=870d58dd75) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [27e1ded122](https://linux-hardware.org/?probe=27e1ded122) | Oct 15, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [73f8df6ec6](https://linux-hardware.org/?probe=73f8df6ec6) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0bc0bf85be](https://linux-hardware.org/?probe=0bc0bf85be) | Oct 14, 2022 |
| Dell          | Latitude E6330              | Notebook    | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Dell          | Precision M3800             | Notebook    | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| Dell          | Latitude 5530               | Notebook    | [9453558076](https://linux-hardware.org/?probe=9453558076) | Oct 12, 2022 |
| ASUSTek       | X756UVK                     | Notebook    | [8d2e9a5e1e](https://linux-hardware.org/?probe=8d2e9a5e1e) | Oct 12, 2022 |
| HP            | 82A5                        | Mini pc     | [5a8ea35493](https://linux-hardware.org/?probe=5a8ea35493) | Oct 11, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | Notebook    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b26ceb2206](https://linux-hardware.org/?probe=b26ceb2206) | Oct 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [bc86477fff](https://linux-hardware.org/?probe=bc86477fff) | Oct 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [24d18c0f7f](https://linux-hardware.org/?probe=24d18c0f7f) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1798b09b89](https://linux-hardware.org/?probe=1798b09b89) | Oct 08, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [b419239d57](https://linux-hardware.org/?probe=b419239d57) | Oct 06, 2022 |
| Gigabyte      | Spring Peak                 | Notebook    | [45794008e2](https://linux-hardware.org/?probe=45794008e2) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [03dc83a686](https://linux-hardware.org/?probe=03dc83a686) | Oct 05, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| Notebook      | W330SU2                     | Notebook    | [a5d5500584](https://linux-hardware.org/?probe=a5d5500584) | Oct 01, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| Dell          | Latitude 5530               | Notebook    | [43874dad6d](https://linux-hardware.org/?probe=43874dad6d) | Sep 30, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [02c5cd53e9](https://linux-hardware.org/?probe=02c5cd53e9) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d658b9dcbe](https://linux-hardware.org/?probe=d658b9dcbe) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [56e5d25094](https://linux-hardware.org/?probe=56e5d25094) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| Razer         | Blade                       | Notebook    | [63a4e5f829](https://linux-hardware.org/?probe=63a4e5f829) | Sep 29, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [757d465447](https://linux-hardware.org/?probe=757d465447) | Sep 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [d09f4c4501](https://linux-hardware.org/?probe=d09f4c4501) | Sep 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [3d7933270a](https://linux-hardware.org/?probe=3d7933270a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [1e6b1b068a](https://linux-hardware.org/?probe=1e6b1b068a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [a978086f1b](https://linux-hardware.org/?probe=a978086f1b) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Lenovo        | B570e 476025G               | Notebook    | [ab67a90ba7](https://linux-hardware.org/?probe=ab67a90ba7) | Sep 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [153aed4d7c](https://linux-hardware.org/?probe=153aed4d7c) | Sep 19, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e728637650](https://linux-hardware.org/?probe=e728637650) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [3e023f86c9](https://linux-hardware.org/?probe=3e023f86c9) | Sep 17, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [90871c217b](https://linux-hardware.org/?probe=90871c217b) | Sep 17, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [324cafa8d2](https://linux-hardware.org/?probe=324cafa8d2) | Sep 17, 2022 |
| Dell          | Precision 7720              | Notebook    | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [b8e79c9c77](https://linux-hardware.org/?probe=b8e79c9c77) | Sep 16, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [2600793890](https://linux-hardware.org/?probe=2600793890) | Sep 15, 2022 |
| Medion        | MS-7857                     | Desktop     | [98a978898c](https://linux-hardware.org/?probe=98a978898c) | Sep 14, 2022 |
| Medion        | MS-7857                     | Desktop     | [54237e3276](https://linux-hardware.org/?probe=54237e3276) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | Notebook    | [916aa5cc5d](https://linux-hardware.org/?probe=916aa5cc5d) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | Notebook    | [3f97043d7a](https://linux-hardware.org/?probe=3f97043d7a) | Sep 14, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [ddac4b0175](https://linux-hardware.org/?probe=ddac4b0175) | Sep 13, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [18400c7a0d](https://linux-hardware.org/?probe=18400c7a0d) | Sep 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f062dd3ff8](https://linux-hardware.org/?probe=f062dd3ff8) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [864a5abac7](https://linux-hardware.org/?probe=864a5abac7) | Sep 12, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [6a6e7e4207](https://linux-hardware.org/?probe=6a6e7e4207) | Sep 12, 2022 |
| HP            | 158B                        | Desktop     | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [6a797dc1cf](https://linux-hardware.org/?probe=6a797dc1cf) | Sep 12, 2022 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [8d76919c1a](https://linux-hardware.org/?probe=8d76919c1a) | Sep 11, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [c7eb1fd4ca](https://linux-hardware.org/?probe=c7eb1fd4ca) | Sep 11, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [857e841fb7](https://linux-hardware.org/?probe=857e841fb7) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | Notebook    | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [603514ef84](https://linux-hardware.org/?probe=603514ef84) | Sep 09, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [90908282f2](https://linux-hardware.org/?probe=90908282f2) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [32e71c2905](https://linux-hardware.org/?probe=32e71c2905) | Sep 01, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [af0da080ec](https://linux-hardware.org/?probe=af0da080ec) | Sep 01, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1f8274de5a](https://linux-hardware.org/?probe=1f8274de5a) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [567bf4b44a](https://linux-hardware.org/?probe=567bf4b44a) | Aug 31, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [14f4c7e248](https://linux-hardware.org/?probe=14f4c7e248) | Aug 29, 2022 |
| Lenovo        | ThinkPad P1 20MDS0FC00      | Notebook    | [dcdde00f17](https://linux-hardware.org/?probe=dcdde00f17) | Aug 29, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | Notebook    | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| Dell          | Latitude 5511               | Notebook    | [22c835a93a](https://linux-hardware.org/?probe=22c835a93a) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [413cc5a3c3](https://linux-hardware.org/?probe=413cc5a3c3) | Aug 24, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fdc1bb0c75](https://linux-hardware.org/?probe=fdc1bb0c75) | Aug 23, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [fca17b512f](https://linux-hardware.org/?probe=fca17b512f) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [47b1480e61](https://linux-hardware.org/?probe=47b1480e61) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d1fb1214f6](https://linux-hardware.org/?probe=d1fb1214f6) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fc1a1cd41f](https://linux-hardware.org/?probe=fc1a1cd41f) | Aug 20, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [7dbac78a87](https://linux-hardware.org/?probe=7dbac78a87) | Aug 20, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [abbb1d7360](https://linux-hardware.org/?probe=abbb1d7360) | Aug 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c3e335499f](https://linux-hardware.org/?probe=c3e335499f) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| MSI           | MS-AE611 100                | All in one  | [336e0dfd12](https://linux-hardware.org/?probe=336e0dfd12) | Aug 18, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 872B                        | Desktop     | [466f4962fe](https://linux-hardware.org/?probe=466f4962fe) | Aug 17, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [bd808084a5](https://linux-hardware.org/?probe=bd808084a5) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| HP            | 2AB6                        | Desktop     | [bf0c915ea8](https://linux-hardware.org/?probe=bf0c915ea8) | Aug 15, 2022 |
| HP            | 2AB6                        | Desktop     | [2fe34984da](https://linux-hardware.org/?probe=2fe34984da) | Aug 15, 2022 |
| HP            | 1825                        | Desktop     | [bceae72004](https://linux-hardware.org/?probe=bceae72004) | Aug 15, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [97f14bc24c](https://linux-hardware.org/?probe=97f14bc24c) | Aug 14, 2022 |
| Lenovo        | ThinkCentre XXXX 739527G    | Desktop     | [ca5fe11e2c](https://linux-hardware.org/?probe=ca5fe11e2c) | Aug 13, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3e63b30226](https://linux-hardware.org/?probe=3e63b30226) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ba9961565a](https://linux-hardware.org/?probe=ba9961565a) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | Notebook    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| MSI           | MS-AE611 100                | All in one  | [94bcb206d3](https://linux-hardware.org/?probe=94bcb206d3) | Aug 10, 2022 |
| Dell          | Latitude D630               | Notebook    | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [8913065613](https://linux-hardware.org/?probe=8913065613) | Aug 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aee6d50427](https://linux-hardware.org/?probe=aee6d50427) | Aug 05, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [882cec3541](https://linux-hardware.org/?probe=882cec3541) | Aug 02, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [f6f97a58c4](https://linux-hardware.org/?probe=f6f97a58c4) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Dell          | Latitude 5520               | Notebook    | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [b59f87dd02](https://linux-hardware.org/?probe=b59f87dd02) | Aug 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [9e219bd7c2](https://linux-hardware.org/?probe=9e219bd7c2) | Jul 29, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [e6f2cdc55e](https://linux-hardware.org/?probe=e6f2cdc55e) | Jul 29, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ab7d6b9f02](https://linux-hardware.org/?probe=ab7d6b9f02) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [c4a4fed104](https://linux-hardware.org/?probe=c4a4fed104) | Jul 28, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [356556d83a](https://linux-hardware.org/?probe=356556d83a) | Jul 28, 2022 |
| Dell          | Latitude D630               | Notebook    | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [bf64b6cf98](https://linux-hardware.org/?probe=bf64b6cf98) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [d8b47ea062](https://linux-hardware.org/?probe=d8b47ea062) | Jul 27, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [c2f56b2458](https://linux-hardware.org/?probe=c2f56b2458) | Jul 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [910067609e](https://linux-hardware.org/?probe=910067609e) | Jul 27, 2022 |
| Toshiba       | Satellite C870D-116         | Notebook    | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b2e54629e5](https://linux-hardware.org/?probe=b2e54629e5) | Jul 25, 2022 |
| Panasonic     | FZ55-2                      | Notebook    | [a190a7d890](https://linux-hardware.org/?probe=a190a7d890) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [7ac84940b8](https://linux-hardware.org/?probe=7ac84940b8) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | Notebook    | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [d13d96da02](https://linux-hardware.org/?probe=d13d96da02) | Jul 23, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [f8ce34248a](https://linux-hardware.org/?probe=f8ce34248a) | Jul 22, 2022 |
| Lenovo        | ThinkPad E580 20KSS0GK01    | Notebook    | [b2d902cbc6](https://linux-hardware.org/?probe=b2d902cbc6) | Jul 21, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| MSI           | Z97-G43 GAMING              | Desktop     | [f7f43ba6ed](https://linux-hardware.org/?probe=f7f43ba6ed) | Jul 18, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [bffac60888](https://linux-hardware.org/?probe=bffac60888) | Jul 16, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [d52eabbac8](https://linux-hardware.org/?probe=d52eabbac8) | Jul 16, 2022 |
| HP            | ProBook 650 G5              | Notebook    | [471b64a407](https://linux-hardware.org/?probe=471b64a407) | Jul 16, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [5b07f65ff5](https://linux-hardware.org/?probe=5b07f65ff5) | Jul 16, 2022 |
| Sony          | SVE1513H1EW                 | Notebook    | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [cb6916e513](https://linux-hardware.org/?probe=cb6916e513) | Jul 15, 2022 |
| Medion        | MS-7797                     | Desktop     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Acer          | Aspire M3920                | Desktop     | [9b12bf66ac](https://linux-hardware.org/?probe=9b12bf66ac) | Jul 11, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [b40a6c6b15](https://linux-hardware.org/?probe=b40a6c6b15) | Jul 09, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| HP            | 2820h                       | Desktop     | [bfc5afa2c8](https://linux-hardware.org/?probe=bfc5afa2c8) | Jul 07, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [b08ab62885](https://linux-hardware.org/?probe=b08ab62885) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e7c2f09e51](https://linux-hardware.org/?probe=e7c2f09e51) | Jul 05, 2022 |
| NEC Comput... | NEC Versa M370              | Notebook    | [d4dbd6878c](https://linux-hardware.org/?probe=d4dbd6878c) | Jul 04, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [238f7bf18c](https://linux-hardware.org/?probe=238f7bf18c) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| HP            | Pavilion dm1                | Notebook    | [927f5b38e0](https://linux-hardware.org/?probe=927f5b38e0) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | Notebook    | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [90a56ffa69](https://linux-hardware.org/?probe=90a56ffa69) | Jun 27, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Dell          | Latitude E6330              | Notebook    | [969981b8cb](https://linux-hardware.org/?probe=969981b8cb) | Jun 25, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9421b03b9e](https://linux-hardware.org/?probe=9421b03b9e) | Jun 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c2e6e05eea](https://linux-hardware.org/?probe=c2e6e05eea) | Jun 25, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| MSI           | IONA                        | Desktop     | [9f4e8871a7](https://linux-hardware.org/?probe=9f4e8871a7) | Jun 24, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [34e3aad338](https://linux-hardware.org/?probe=34e3aad338) | Jun 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9f67f6836e](https://linux-hardware.org/?probe=9f67f6836e) | Jun 23, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [32a4f6d3e0](https://linux-hardware.org/?probe=32a4f6d3e0) | Jun 23, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [f3ceed4c58](https://linux-hardware.org/?probe=f3ceed4c58) | Jun 20, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [17e0b3e4c0](https://linux-hardware.org/?probe=17e0b3e4c0) | Jun 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [6647ddd346](https://linux-hardware.org/?probe=6647ddd346) | Jun 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [812caba8bf](https://linux-hardware.org/?probe=812caba8bf) | Jun 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c1efcc5411](https://linux-hardware.org/?probe=c1efcc5411) | Jun 16, 2022 |
| Unknown       | MediaTek krane sku176       | Soc         | [c992270582](https://linux-hardware.org/?probe=c992270582) | Jun 15, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [5ef81d4b82](https://linux-hardware.org/?probe=5ef81d4b82) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [4b6c230717](https://linux-hardware.org/?probe=4b6c230717) | Jun 12, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3ddbde438b](https://linux-hardware.org/?probe=3ddbde438b) | Jun 12, 2022 |
| MSI           | H55M-E33                    | Desktop     | [1fa7005827](https://linux-hardware.org/?probe=1fa7005827) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [7b5fb1809b](https://linux-hardware.org/?probe=7b5fb1809b) | Jun 09, 2022 |
| HP            | Compaq 8710w                | Notebook    | [666f2ebcf0](https://linux-hardware.org/?probe=666f2ebcf0) | Jun 08, 2022 |
| Dell          | 0HX555                      | Desktop     | [41ae8a1dd5](https://linux-hardware.org/?probe=41ae8a1dd5) | Jun 08, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [bfd4aab236](https://linux-hardware.org/?probe=bfd4aab236) | Jun 04, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [68a1616b4a](https://linux-hardware.org/?probe=68a1616b4a) | Jun 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [ea56369709](https://linux-hardware.org/?probe=ea56369709) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [909d9cb8d5](https://linux-hardware.org/?probe=909d9cb8d5) | Jun 03, 2022 |
| Samsung       | 750XED                      | Notebook    | [1a900ee340](https://linux-hardware.org/?probe=1a900ee340) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| ASUSTek       | G11CD-K                     | Desktop     | [6550f85808](https://linux-hardware.org/?probe=6550f85808) | Jun 01, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [88ef811c4d](https://linux-hardware.org/?probe=88ef811c4d) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [70313d6ed4](https://linux-hardware.org/?probe=70313d6ed4) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [820a9fb182](https://linux-hardware.org/?probe=820a9fb182) | May 30, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [1029a819d7](https://linux-hardware.org/?probe=1029a819d7) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [c4e27f4d19](https://linux-hardware.org/?probe=c4e27f4d19) | May 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [475315dc10](https://linux-hardware.org/?probe=475315dc10) | May 28, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [397d64e10c](https://linux-hardware.org/?probe=397d64e10c) | May 27, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [a74cc1410a](https://linux-hardware.org/?probe=a74cc1410a) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6e5dd6f76f](https://linux-hardware.org/?probe=6e5dd6f76f) | May 25, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [4107e267d7](https://linux-hardware.org/?probe=4107e267d7) | May 24, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fdc743e9e1](https://linux-hardware.org/?probe=fdc743e9e1) | May 23, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Medion        | P6624                       | Notebook    | [ed8bd28269](https://linux-hardware.org/?probe=ed8bd28269) | May 21, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d1ca28a2fb](https://linux-hardware.org/?probe=d1ca28a2fb) | May 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [a0597ba198](https://linux-hardware.org/?probe=a0597ba198) | May 20, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9d14cc23ca](https://linux-hardware.org/?probe=9d14cc23ca) | May 20, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [56d6c8d749](https://linux-hardware.org/?probe=56d6c8d749) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [6e0efeba1d](https://linux-hardware.org/?probe=6e0efeba1d) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [2886b99972](https://linux-hardware.org/?probe=2886b99972) | May 17, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [74cb2084ef](https://linux-hardware.org/?probe=74cb2084ef) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | Notebook    | [0f8829e460](https://linux-hardware.org/?probe=0f8829e460) | May 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS4X50... | Notebook    | [0fb588c686](https://linux-hardware.org/?probe=0fb588c686) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | Notebook    | [83b27998e5](https://linux-hardware.org/?probe=83b27998e5) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3f84f4220e](https://linux-hardware.org/?probe=3f84f4220e) | May 14, 2022 |
| Sony          | VPCEH1M0E                   | Notebook    | [eefe7eee06](https://linux-hardware.org/?probe=eefe7eee06) | May 13, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [06030eee20](https://linux-hardware.org/?probe=06030eee20) | May 13, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9722abbde0](https://linux-hardware.org/?probe=9722abbde0) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [3f20d2bc2b](https://linux-hardware.org/?probe=3f20d2bc2b) | May 12, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [0026740e3f](https://linux-hardware.org/?probe=0026740e3f) | May 12, 2022 |
| Acer          | Aspire M3985                | Desktop     | [e650ae1a26](https://linux-hardware.org/?probe=e650ae1a26) | May 11, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [a6f5c6215d](https://linux-hardware.org/?probe=a6f5c6215d) | May 11, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4f87a5b748](https://linux-hardware.org/?probe=4f87a5b748) | May 10, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [eaa10a050b](https://linux-hardware.org/?probe=eaa10a050b) | May 10, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| Dell          | 0KV3RP A00                  | Desktop     | [6ef8c2f171](https://linux-hardware.org/?probe=6ef8c2f171) | May 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [05b7c2c72c](https://linux-hardware.org/?probe=05b7c2c72c) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a9e6ecf483](https://linux-hardware.org/?probe=a9e6ecf483) | May 09, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [8080b9becd](https://linux-hardware.org/?probe=8080b9becd) | May 08, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1d84f1a74a](https://linux-hardware.org/?probe=1d84f1a74a) | May 07, 2022 |
| HP            | 82F2                        | Desktop     | [cb49a04bce](https://linux-hardware.org/?probe=cb49a04bce) | May 07, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8e2da684e0](https://linux-hardware.org/?probe=8e2da684e0) | May 07, 2022 |
| Dell          | Latitude E6330              | Notebook    | [cbfc4e6f78](https://linux-hardware.org/?probe=cbfc4e6f78) | May 07, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [093d7ea1c9](https://linux-hardware.org/?probe=093d7ea1c9) | May 06, 2022 |
| Lenovo        | ThinkPad X280 20KES94F05    | Notebook    | [16b4cbc9fb](https://linux-hardware.org/?probe=16b4cbc9fb) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| Dell          | 0VHRW1 A03                  | Desktop     | [2a5880a214](https://linux-hardware.org/?probe=2a5880a214) | May 03, 2022 |
| Dell          | 0VHRW1 A03                  | Desktop     | [8204a08a04](https://linux-hardware.org/?probe=8204a08a04) | May 03, 2022 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [a7396f278d](https://linux-hardware.org/?probe=a7396f278d) | May 02, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [01a95b61fe](https://linux-hardware.org/?probe=01a95b61fe) | May 02, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [5625deb6aa](https://linux-hardware.org/?probe=5625deb6aa) | May 01, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [130944084d](https://linux-hardware.org/?probe=130944084d) | May 01, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [cc016ce0c5](https://linux-hardware.org/?probe=cc016ce0c5) | May 01, 2022 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [0e0d0dd3aa](https://linux-hardware.org/?probe=0e0d0dd3aa) | Apr 30, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [f140b54261](https://linux-hardware.org/?probe=f140b54261) | Apr 30, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [2543d87831](https://linux-hardware.org/?probe=2543d87831) | Apr 30, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [21fcbc1850](https://linux-hardware.org/?probe=21fcbc1850) | Apr 27, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [edf60be002](https://linux-hardware.org/?probe=edf60be002) | Apr 26, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [de010dfc55](https://linux-hardware.org/?probe=de010dfc55) | Apr 24, 2022 |
| BLAUPUNKT     | Discovery 1011WI            | Notebook    | [c20b87673e](https://linux-hardware.org/?probe=c20b87673e) | Apr 24, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [c668e0d48e](https://linux-hardware.org/?probe=c668e0d48e) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | Notebook    | [762843e768](https://linux-hardware.org/?probe=762843e768) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | Notebook    | [11ec4d291b](https://linux-hardware.org/?probe=11ec4d291b) | Apr 23, 2022 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [ca56dc9824](https://linux-hardware.org/?probe=ca56dc9824) | Apr 21, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [cc5ed34db8](https://linux-hardware.org/?probe=cc5ed34db8) | Apr 21, 2022 |
| Lenovo        | ThinkPad T520 4243AP1       | Notebook    | [7723ab4bd9](https://linux-hardware.org/?probe=7723ab4bd9) | Apr 19, 2022 |
| Medion        | D3F3-EM2                    | Desktop     | [733df830d1](https://linux-hardware.org/?probe=733df830d1) | Apr 19, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0e53d4286d](https://linux-hardware.org/?probe=0e53d4286d) | Apr 19, 2022 |
| MSI           | GL65 Leopard 10SER          | Notebook    | [2bdfe0279e](https://linux-hardware.org/?probe=2bdfe0279e) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440s 20ARS1940... | Notebook    | [a7fbe1af34](https://linux-hardware.org/?probe=a7fbe1af34) | Apr 18, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | Notebook    | [7b1d2ec5a1](https://linux-hardware.org/?probe=7b1d2ec5a1) | Apr 17, 2022 |
| Acer          | Aspire 5735                 | Notebook    | [e43434e15c](https://linux-hardware.org/?probe=e43434e15c) | Apr 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [4639b09a3e](https://linux-hardware.org/?probe=4639b09a3e) | Apr 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5bdba5a921](https://linux-hardware.org/?probe=5bdba5a921) | Apr 14, 2022 |
| MSI           | B250M MORTAR                | Desktop     | [8bf9715804](https://linux-hardware.org/?probe=8bf9715804) | Apr 14, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b80dc08588](https://linux-hardware.org/?probe=b80dc08588) | Apr 14, 2022 |
| Dell          | Latitude 5591               | Notebook    | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| ASRock        | H170M Pro4                  | Desktop     | [a8bd162bf1](https://linux-hardware.org/?probe=a8bd162bf1) | Apr 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2ddb0d0765](https://linux-hardware.org/?probe=2ddb0d0765) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [5aafaf0890](https://linux-hardware.org/?probe=5aafaf0890) | Apr 13, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [983dbbf9e8](https://linux-hardware.org/?probe=983dbbf9e8) | Apr 13, 2022 |
| Medion        | BTDD-EAIO                   | All in one  | [8de03f374b](https://linux-hardware.org/?probe=8de03f374b) | Apr 13, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [7ea9773813](https://linux-hardware.org/?probe=7ea9773813) | Apr 12, 2022 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [938b601307](https://linux-hardware.org/?probe=938b601307) | Apr 11, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [09f8f09862](https://linux-hardware.org/?probe=09f8f09862) | Apr 11, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [da1cd5bf6e](https://linux-hardware.org/?probe=da1cd5bf6e) | Apr 11, 2022 |
| Google        | Akali 360                   | Notebook    | [dccccb359b](https://linux-hardware.org/?probe=dccccb359b) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [2ce1788c33](https://linux-hardware.org/?probe=2ce1788c33) | Apr 11, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [01f57dd952](https://linux-hardware.org/?probe=01f57dd952) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7f71b84230](https://linux-hardware.org/?probe=7f71b84230) | Apr 10, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Dell          | Latitude E6430              | Notebook    | [dd09c863c8](https://linux-hardware.org/?probe=dd09c863c8) | Apr 08, 2022 |
| ASRockRack    | ROMED8-2T                   | Server      | [49aedaee61](https://linux-hardware.org/?probe=49aedaee61) | Apr 08, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [8bcbe236a7](https://linux-hardware.org/?probe=8bcbe236a7) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [af324f356f](https://linux-hardware.org/?probe=af324f356f) | Apr 07, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [27bddd0a9c](https://linux-hardware.org/?probe=27bddd0a9c) | Apr 07, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [fc358abe4b](https://linux-hardware.org/?probe=fc358abe4b) | Apr 06, 2022 |
| HP            | 470 G7 Notebook PC          | Notebook    | [34fc91d9ac](https://linux-hardware.org/?probe=34fc91d9ac) | Apr 06, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [dff8141976](https://linux-hardware.org/?probe=dff8141976) | Apr 06, 2022 |
| MSI           | Eclipse SLI                 | Desktop     | [e488b9407a](https://linux-hardware.org/?probe=e488b9407a) | Apr 05, 2022 |
| MSI           | Eclipse SLI                 | Desktop     | [aebfec44b2](https://linux-hardware.org/?probe=aebfec44b2) | Apr 05, 2022 |
| Dell          | Latitude 5410               | Notebook    | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [8c4011afa9](https://linux-hardware.org/?probe=8c4011afa9) | Apr 04, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b697fd5f0a](https://linux-hardware.org/?probe=b697fd5f0a) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [94a9015090](https://linux-hardware.org/?probe=94a9015090) | Apr 03, 2022 |
| ASRock        | B75M-GL                     | Desktop     | [087381b93e](https://linux-hardware.org/?probe=087381b93e) | Apr 02, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1de292a85c](https://linux-hardware.org/?probe=1de292a85c) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [732406d8b0](https://linux-hardware.org/?probe=732406d8b0) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [086261ecef](https://linux-hardware.org/?probe=086261ecef) | Apr 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [4731581e9b](https://linux-hardware.org/?probe=4731581e9b) | Mar 31, 2022 |
| HP            | ZBook Studio G4             | Notebook    | [d5ec5c3e8e](https://linux-hardware.org/?probe=d5ec5c3e8e) | Mar 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Medion        | Crawler E25                 | Notebook    | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| HP            | 82A2                        | Desktop     | [5736762c06](https://linux-hardware.org/?probe=5736762c06) | Mar 28, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b8969bf34b](https://linux-hardware.org/?probe=b8969bf34b) | Mar 27, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e04592bee1](https://linux-hardware.org/?probe=e04592bee1) | Mar 27, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c4b697295e](https://linux-hardware.org/?probe=c4b697295e) | Mar 26, 2022 |
| Acer          | Aspire 8930                 | Notebook    | [6774be59d3](https://linux-hardware.org/?probe=6774be59d3) | Mar 26, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [bbdb3c316f](https://linux-hardware.org/?probe=bbdb3c316f) | Mar 25, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [6096fbc1ba](https://linux-hardware.org/?probe=6096fbc1ba) | Mar 25, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [7ad46659a5](https://linux-hardware.org/?probe=7ad46659a5) | Mar 24, 2022 |
| Packard Be... | DOT S                       | Notebook    | [591be1d465](https://linux-hardware.org/?probe=591be1d465) | Mar 22, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | Notebook    | [26cd5cf250](https://linux-hardware.org/?probe=26cd5cf250) | Mar 20, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [9e38b0860e](https://linux-hardware.org/?probe=9e38b0860e) | Mar 19, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [1feeb83fb4](https://linux-hardware.org/?probe=1feeb83fb4) | Mar 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belgium/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 302       | 14.98%  |
| Ubuntu 18.04                 | 141       | 6.99%   |
| Ubuntu 22.04                 | 107       | 5.31%   |
| Debian 11                    | 50        | 2.48%   |
| ArcoLinux Rolling            | 47        | 2.33%   |
| Zorin 16                     | 46        | 2.28%   |
| OpenMandriva 4.2             | 44        | 2.18%   |
| OpenMandriva 4.3             | 38        | 1.88%   |
| Fedora 36                    | 33        | 1.64%   |
| Ubuntu 20.10                 | 31        | 1.54%   |
| Linux Mint 20.3              | 29        | 1.44%   |
| Linux Mint 20.1              | 29        | 1.44%   |
| Ubuntu 19.10                 | 27        | 1.34%   |
| Manjaro                      | 27        | 1.34%   |
| Linux Mint 19.3              | 26        | 1.29%   |
| Fedora 35                    | 26        | 1.29%   |
| Arch                         | 26        | 1.29%   |
| Xubuntu 20.04                | 25        | 1.24%   |
| Linux Mint 20.2              | 23        | 1.14%   |
| Arch Rolling                 | 23        | 1.14%   |
| Fedora 34                    | 21        | 1.04%   |
| Ubuntu 19.04                 | 20        | 0.99%   |
| Pop!_OS 22.04                | 20        | 0.99%   |
| Pop!_OS 20.04                | 20        | 0.99%   |
| Linux Mint 21                | 20        | 0.99%   |
| openSUSE Tumbleweed-XXXXXXXX | 19        | 0.94%   |
| Linux Mint 20                | 19        | 0.94%   |
| OpenMandriva 23.01           | 18        | 0.89%   |
| Fedora 37                    | 18        | 0.89%   |
| Ubuntu 21.10                 | 17        | 0.84%   |
| OpenMandriva 23.03           | 17        | 0.84%   |
| Fedora 38                    | 17        | 0.84%   |
| Ubuntu 21.04                 | 16        | 0.79%   |
| Pop!_OS 21.04                | 16        | 0.79%   |
| KDE neon 20.04               | 16        | 0.79%   |
| Fedora 33                    | 16        | 0.79%   |
| Fedora 32                    | 15        | 0.74%   |
| Debian 10                    | 15        | 0.74%   |
| Linux Mint 21.1              | 14        | 0.69%   |
| EndeavourOS Rolling          | 14        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 671       | 35.92%  |
| Linux Mint    | 173       | 9.26%   |
| Fedora        | 125       | 6.69%   |
| OpenMandriva  | 124       | 6.64%   |
| Debian        | 89        | 4.76%   |
| Pop!_OS       | 65        | 3.48%   |
| Manjaro       | 63        | 3.37%   |
| Zorin         | 58        | 3.1%    |
| Xubuntu       | 53        | 2.84%   |
| ArcoLinux     | 48        | 2.57%   |
| Arch          | 47        | 2.52%   |
| Kubuntu       | 37        | 1.98%   |
| ROSA          | 30        | 1.61%   |
| openSUSE      | 29        | 1.55%   |
| KDE neon      | 25        | 1.34%   |
| Elementary    | 20        | 1.07%   |
| Ubuntu Unity  | 18        | 0.96%   |
| Lubuntu       | 18        | 0.96%   |
| Ubuntu MATE   | 16        | 0.86%   |
| Gentoo        | 16        | 0.86%   |
| EndeavourOS   | 16        | 0.86%   |
| CentOS        | 12        | 0.64%   |
| Kali          | 11        | 0.59%   |
| Endless       | 10        | 0.54%   |
| LMDE          | 8         | 0.43%   |
| BlackPanther  | 8         | 0.43%   |
| SteamOS       | 7         | 0.37%   |
| Garuda Linux  | 7         | 0.37%   |
| Ubuntu Budgie | 6         | 0.32%   |
| MX            | 6         | 0.32%   |
| Clear Linux   | 6         | 0.32%   |
| Ubuntu Studio | 4         | 0.21%   |
| Nobara        | 4         | 0.21%   |
| NixOS         | 3         | 0.16%   |
| LinuxFX       | 3         | 0.16%   |
| Rocky Linux   | 2         | 0.11%   |
| Raspbian      | 2         | 0.11%   |
| Peppermint    | 2         | 0.11%   |
| Parrot        | 2         | 0.11%   |
| Feren OS      | 2         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 43        | 1.86%   |
| 5.16.7-desktop-1omv4003  | 37        | 1.6%    |
| 5.4.0-42-generic         | 29        | 1.25%   |
| 5.4.0-58-generic         | 22        | 0.95%   |
| 5.15.0-56-generic        | 22        | 0.95%   |
| 5.4.0-48-generic         | 21        | 0.91%   |
| 5.3.0-42-generic         | 20        | 0.86%   |
| 5.15.0-46-generic        | 18        | 0.78%   |
| 6.2.6-desktop-1omv2390   | 17        | 0.73%   |
| 5.15.0-58-generic        | 17        | 0.73%   |
| 5.15.0-52-generic        | 17        | 0.73%   |
| 6.1.1-desktop-1omv2290   | 15        | 0.65%   |
| 5.8.0-48-generic         | 15        | 0.65%   |
| 5.8.0-43-generic         | 15        | 0.65%   |
| 5.4.0-65-generic         | 15        | 0.65%   |
| 5.15.0-48-generic        | 15        | 0.65%   |
| 5.4.0-66-generic         | 14        | 0.6%    |
| 5.4.0-29-generic         | 14        | 0.6%    |
| 5.3.0-46-generic         | 14        | 0.6%    |
| 5.11.0-38-generic        | 14        | 0.6%    |
| 5.4.0-74-generic         | 13        | 0.56%   |
| 5.4.0-52-generic         | 13        | 0.56%   |
| 5.4.0-40-generic         | 13        | 0.56%   |
| 5.4.0-37-generic         | 12        | 0.52%   |
| 5.4.0-26-generic         | 12        | 0.52%   |
| 5.19.0-35-generic        | 12        | 0.52%   |
| 5.15.0-53-generic        | 12        | 0.52%   |
| 5.15.0-47-generic        | 12        | 0.52%   |
| 5.15.0-41-generic        | 12        | 0.52%   |
| 5.13.0-28-generic        | 12        | 0.52%   |
| 5.10.0-21-amd64          | 12        | 0.52%   |
| 5.4.0-91-generic         | 11        | 0.47%   |
| 5.11.0-43-generic        | 11        | 0.47%   |
| 5.11.0-41-generic        | 11        | 0.47%   |
| 5.8.0-53-generic         | 10        | 0.43%   |
| 5.4.0-54-generic         | 10        | 0.43%   |
| 5.13.0-39-generic        | 10        | 0.43%   |
| 5.4.0-56-generic         | 9         | 0.39%   |
| 5.3.0-40-generic         | 9         | 0.39%   |
| 5.15.0-60-generic        | 9         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 353       | 16.31%  |
| 5.15.0  | 205       | 9.47%   |
| 5.8.0   | 118       | 5.45%   |
| 4.15.0  | 107       | 4.94%   |
| 5.11.0  | 106       | 4.9%    |
| 5.13.0  | 87        | 4.02%   |
| 5.3.0   | 83        | 3.84%   |
| 5.19.0  | 63        | 2.91%   |
| 5.10.0  | 62        | 2.87%   |
| 5.0.0   | 51        | 2.36%   |
| 5.10.14 | 43        | 1.99%   |
| 5.16.7  | 37        | 1.71%   |
| 4.18.0  | 37        | 1.71%   |
| 6.2.6   | 20        | 0.92%   |
| 6.2.0   | 16        | 0.74%   |
| 4.19.0  | 16        | 0.74%   |
| 6.1.1   | 15        | 0.69%   |
| 6.1.0   | 12        | 0.55%   |
| 6.0.0   | 10        | 0.46%   |
| 4.18.16 | 10        | 0.46%   |
| 6.0.12  | 9         | 0.42%   |
| 5.17.5  | 9         | 0.42%   |
| 4.9.20  | 9         | 0.42%   |
| 6.2.11  | 8         | 0.37%   |
| 5.14.10 | 8         | 0.37%   |
| 6.1.12  | 7         | 0.32%   |
| 5.18.12 | 7         | 0.32%   |
| 5.9.11  | 6         | 0.28%   |
| 5.8.5   | 6         | 0.28%   |
| 5.17.0  | 6         | 0.28%   |
| 5.16.0  | 6         | 0.28%   |
| 5.13.12 | 6         | 0.28%   |
| 4.9.60  | 6         | 0.28%   |
| 4.4.0   | 6         | 0.28%   |
| 3.10.0  | 6         | 0.28%   |
| 6.3.8   | 5         | 0.23%   |
| 6.3.1   | 5         | 0.23%   |
| 6.2.9   | 5         | 0.23%   |
| 6.2.8   | 5         | 0.23%   |
| 6.0.7   | 5         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 382       | 18.13%  |
| 5.15    | 259       | 12.29%  |
| 5.8     | 140       | 6.64%   |
| 5.10    | 139       | 6.6%    |
| 5.11    | 133       | 6.31%   |
| 4.15    | 107       | 5.08%   |
| 5.13    | 106       | 5.03%   |
| 5.3     | 92        | 4.37%   |
| 5.19    | 87        | 4.13%   |
| 5.16    | 73        | 3.46%   |
| 6.2     | 68        | 3.23%   |
| 5.0     | 57        | 2.71%   |
| 6.0     | 49        | 2.33%   |
| 6.1     | 48        | 2.28%   |
| 4.18    | 48        | 2.28%   |
| 5.17    | 39        | 1.85%   |
| 5.18    | 33        | 1.57%   |
| 5.14    | 28        | 1.33%   |
| 5.9     | 26        | 1.23%   |
| 4.9     | 26        | 1.23%   |
| 6.3     | 25        | 1.19%   |
| 5.12    | 24        | 1.14%   |
| 4.19    | 23        | 1.09%   |
| 5.6     | 22        | 1.04%   |
| 5.5     | 13        | 0.62%   |
| 5.7     | 12        | 0.57%   |
| 6.4     | 10        | 0.47%   |
| 4.4     | 6         | 0.28%   |
| 3.10    | 6         | 0.28%   |
| 4.13    | 5         | 0.24%   |
| 5.2     | 4         | 0.19%   |
| 5.1     | 4         | 0.19%   |
| 4.12    | 3         | 0.14%   |
| 5.15.96 | 2         | 0.09%   |
| 4.17    | 2         | 0.09%   |
| 4.1     | 2         | 0.09%   |
| 6.5     | 1         | 0.05%   |
| 4.2     | 1         | 0.05%   |
| 4.10    | 1         | 0.05%   |
| 2.6     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1724      | 96.75%  |
| i686    | 41        | 2.3%    |
| aarch64 | 14        | 0.79%   |
| armv7l  | 2         | 0.11%   |
| armv6l  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 821       | 42.92%  |
| KDE5             | 293       | 15.32%  |
| Unknown          | 240       | 12.55%  |
| XFCE             | 163       | 8.52%   |
| X-Cinnamon       | 126       | 6.59%   |
| MATE             | 54        | 2.82%   |
| KDE              | 37        | 1.93%   |
| LXQt             | 26        | 1.36%   |
| Cinnamon         | 21        | 1.1%    |
| i3               | 20        | 1.05%   |
| Pantheon         | 19        | 0.99%   |
| Unity            | 18        | 0.94%   |
| KDE4             | 14        | 0.73%   |
| Budgie           | 11        | 0.58%   |
| sway             | 6         | 0.31%   |
| LXDE             | 5         | 0.26%   |
| Hyprland         | 5         | 0.26%   |
| GNOME Flashback  | 5         | 0.26%   |
| LeftWM           | 4         | 0.21%   |
| Deepin           | 4         | 0.21%   |
| lightdm-xsession | 3         | 0.16%   |
| awesome          | 3         | 0.16%   |
| Trinity          | 2         | 0.1%    |
| Openbox          | 2         | 0.1%    |
| icewm            | 2         | 0.1%    |
| chadwm           | 2         | 0.1%    |
| bspwm            | 2         | 0.1%    |
| xmonad           | 1         | 0.05%   |
| spectrwm         | 1         | 0.05%   |
| qtile            | 1         | 0.05%   |
| GNOME Classic    | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1405      | 75.86%  |
| Wayland | 283       | 15.28%  |
| Unknown | 134       | 7.24%   |
| Tty     | 30        | 1.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 881       | 46.84%  |
| SDDM    | 293       | 15.58%  |
| GDM     | 243       | 12.92%  |
| GDM3    | 213       | 11.32%  |
| LightDM | 165       | 8.77%   |
| TDM     | 68        | 3.62%   |
| KDM     | 13        | 0.69%   |
| XDM     | 4         | 0.21%   |
| SLiM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 596       | 32.13%  |
| fr_BE      | 338       | 18.22%  |
| nl_BE      | 298       | 16.06%  |
| Unknown    | 224       | 12.08%  |
| fr_FR      | 103       | 5.55%   |
| en_GB      | 95        | 5.12%   |
| nl_NL      | 83        | 4.47%   |
| C          | 30        | 1.62%   |
| de_DE      | 14        | 0.75%   |
| de_BE      | 10        | 0.54%   |
| pl_PL      | 8         | 0.43%   |
| en_IE      | 7         | 0.38%   |
| ru_RU      | 6         | 0.32%   |
| es_ES      | 5         | 0.27%   |
| ro_RO      | 3         | 0.16%   |
| pt_PT      | 3         | 0.16%   |
| POSIX      | 3         | 0.16%   |
| it_IT      | 3         | 0.16%   |
| C.UTF8     | 3         | 0.16%   |
| en_US.UTF8 | 2         | 0.11%   |
| en_CA      | 2         | 0.11%   |
| en_BE      | 2         | 0.11%   |
| tt_RU      | 1         | 0.05%   |
| tr_TR      | 1         | 0.05%   |
| pt_BR      | 1         | 0.05%   |
| nl_BE.UTF8 | 1         | 0.05%   |
| nl_AW      | 1         | 0.05%   |
| li_BE      | 1         | 0.05%   |
| ku_TR      | 1         | 0.05%   |
| it_CH      | 1         | 0.05%   |
| hu_HU      | 1         | 0.05%   |
| fr_LU      | 1         | 0.05%   |
| fr_FR.UTF8 | 1         | 0.05%   |
| fr_CH      | 1         | 0.05%   |
| en_ZA      | 1         | 0.05%   |
| en_NZ      | 1         | 0.05%   |
| en_IN      | 1         | 0.05%   |
| en_DK      | 1         | 0.05%   |
| bg_BG      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 921       | 50.44%  |
| BIOS | 905       | 49.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1395      | 75.65%  |
| Btrfs    | 175       | 9.49%   |
| Overlay  | 139       | 7.54%   |
| Unknown  | 64        | 3.47%   |
| Xfs      | 27        | 1.46%   |
| Tmpfs    | 23        | 1.25%   |
| Zfs      | 10        | 0.54%   |
| Ext2     | 8         | 0.43%   |
| Reiserfs | 1         | 0.05%   |
| F2fs     | 1         | 0.05%   |
| Ext3     | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 931       | 50.85%  |
| GPT     | 704       | 38.45%  |
| MBR     | 196       | 10.7%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1502      | 82.39%  |
| Yes       | 321       | 17.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1268      | 69.82%  |
| Yes       | 548       | 30.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 281       | 15.79%  |
| ASUSTek Computer        | 281       | 15.79%  |
| Lenovo                  | 236       | 13.26%  |
| Dell                    | 234       | 13.15%  |
| MSI                     | 127       | 7.13%   |
| Acer                    | 99        | 5.56%   |
| Gigabyte Technology     | 93        | 5.22%   |
| Medion                  | 59        | 3.31%   |
| ASRock                  | 47        | 2.64%   |
| Apple                   | 42        | 2.36%   |
| Intel                   | 33        | 1.85%   |
| Toshiba                 | 32        | 1.8%    |
| Sony                    | 26        | 1.46%   |
| Packard Bell            | 22        | 1.24%   |
| Notebook                | 22        | 1.24%   |
| Unknown                 | 14        | 0.79%   |
| Raspberry Pi Foundation | 12        | 0.67%   |
| Fujitsu                 | 12        | 0.67%   |
| TUXEDO                  | 10        | 0.56%   |
| Valve                   | 8         | 0.45%   |
| Samsung Electronics     | 8         | 0.45%   |
| Foxconn                 | 6         | 0.34%   |
| Supermicro              | 5         | 0.28%   |
| Fujitsu Siemens         | 5         | 0.28%   |
| PC Specialist           | 4         | 0.22%   |
| Alienware               | 4         | 0.22%   |
| Pegatron                | 3         | 0.17%   |
| Microsoft               | 3         | 0.17%   |
| HUAWEI                  | 3         | 0.17%   |
| Google                  | 3         | 0.17%   |
| Clevo                   | 3         | 0.17%   |
| BESSTAR Tech            | 3         | 0.17%   |
| AZW                     | 3         | 0.17%   |
| AMI                     | 3         | 0.17%   |
| Teclast                 | 2         | 0.11%   |
| Shuttle                 | 2         | 0.11%   |
| Razer                   | 2         | 0.11%   |
| Panasonic               | 2         | 0.11%   |
| Nvidia                  | 2         | 0.11%   |
| YJKC                    | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 23        | 1.29%   |
| Unknown                          | 18        | 1.01%   |
| Valve Jupiter                    | 8         | 0.45%   |
| HP Pavilion g7                   | 7         | 0.39%   |
| HP Pavilion Notebook             | 6         | 0.34%   |
| ASRock B450M Pro4                | 6         | 0.34%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5 | 5         | 0.28%   |
| HP ProBook 6570b                 | 5         | 0.28%   |
| HP ProBook 650 G1                | 5         | 0.28%   |
| HP Pavilion dv7                  | 5         | 0.28%   |
| HP EliteBook 850 G8 Notebook PC  | 5         | 0.28%   |
| Dell XPS 13 7390                 | 5         | 0.28%   |
| Dell OptiPlex 780                | 5         | 0.28%   |
| Dell Latitude 5530               | 5         | 0.28%   |
| Toshiba Satellite C660           | 4         | 0.22%   |
| RPi Raspberry Pi                 | 4         | 0.22%   |
| MSI MS-7C91                      | 4         | 0.22%   |
| MSI MS-7C37                      | 4         | 0.22%   |
| MSI MS-7B86                      | 4         | 0.22%   |
| MSI MS-7A38                      | 4         | 0.22%   |
| HP Pavilion Laptop 15-eh1xxx     | 4         | 0.22%   |
| HP Pavilion Laptop 15-cw0xxx     | 4         | 0.22%   |
| HP Pavilion dv6                  | 4         | 0.22%   |
| HP Pavilion 17                   | 4         | 0.22%   |
| HP Compaq Elite 8300 SFF         | 4         | 0.22%   |
| Gigabyte X570 AORUS MASTER       | 4         | 0.22%   |
| Gigabyte Spring Peak             | 4         | 0.22%   |
| Gigabyte GB-BRR7H-4800           | 4         | 0.22%   |
| Dell XPS 13 9370                 | 4         | 0.22%   |
| Dell OptiPlex 3010               | 4         | 0.22%   |
| Dell Latitude 5520               | 4         | 0.22%   |
| ASUS ROG STRIX X570-E GAMING     | 4         | 0.22%   |
| ASUS PRIME X570-PRO              | 4         | 0.22%   |
| MSI MS-7A34                      | 3         | 0.17%   |
| MSI MS-7850                      | 3         | 0.17%   |
| Medion MS-7728                   | 3         | 0.17%   |
| Lenovo Yoga 530-14IKB 81EK       | 3         | 0.17%   |
| Lenovo ThinkPad L390 20NSS1YV0B  | 3         | 0.17%   |
| Lenovo Legion 5 15ARH05 82B5     | 3         | 0.17%   |
| HP ProBook 470 G2                | 3         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 117       | 6.57%   |
| Dell Latitude         | 87        | 4.89%   |
| Acer Aspire           | 77        | 4.33%   |
| HP Pavilion           | 60        | 3.37%   |
| HP EliteBook          | 59        | 3.31%   |
| HP ProBook            | 41        | 2.3%    |
| Lenovo IdeaPad        | 37        | 2.08%   |
| Dell XPS              | 37        | 2.08%   |
| HP Compaq             | 36        | 2.02%   |
| Dell OptiPlex         | 34        | 1.91%   |
| ASUS PRIME            | 34        | 1.91%   |
| Toshiba Satellite     | 28        | 1.57%   |
| Dell Precision        | 25        | 1.4%    |
| Dell Inspiron         | 25        | 1.4%    |
| ASUS ROG              | 25        | 1.4%    |
| ASUS All              | 23        | 1.29%   |
| Lenovo Yoga           | 18        | 1.01%   |
| HP Laptop             | 18        | 1.01%   |
| ASUS TUF              | 18        | 1.01%   |
| Unknown               | 18        | 1.01%   |
| Medion Akoya          | 14        | 0.79%   |
| Lenovo Legion         | 14        | 0.79%   |
| RPi Raspberry         | 12        | 0.67%   |
| Packard Bell EasyNote | 12        | 0.67%   |
| Lenovo ThinkCentre    | 11        | 0.62%   |
| Dell Vostro           | 11        | 0.62%   |
| HP ZBook              | 10        | 0.56%   |
| HP ENVY               | 10        | 0.56%   |
| ASUS VivoBook         | 10        | 0.56%   |
| Gigabyte X570         | 9         | 0.51%   |
| Valve Jupiter         | 8         | 0.45%   |
| HP ProDesk            | 7         | 0.39%   |
| Lenovo ThinkBook      | 6         | 0.34%   |
| Lenovo IdeaCentre     | 6         | 0.34%   |
| ASRock B450M          | 6         | 0.34%   |
| Acer Nitro            | 6         | 0.34%   |
| Fujitsu ESPRIMO       | 5         | 0.28%   |
| Dell Studio           | 5         | 0.28%   |
| ASUS ZenBook          | 5         | 0.28%   |
| ASUS Strix            | 5         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 174       | 9.78%   |
| 2020    | 171       | 9.61%   |
| 2019    | 161       | 9.04%   |
| 2012    | 141       | 7.92%   |
| 2013    | 128       | 7.19%   |
| 2011    | 126       | 7.08%   |
| 2017    | 110       | 6.18%   |
| 2014    | 103       | 5.79%   |
| 2021    | 98        | 5.51%   |
| 2015    | 87        | 4.89%   |
| 2008    | 82        | 4.61%   |
| 2016    | 79        | 4.44%   |
| 2010    | 79        | 4.44%   |
| 2009    | 70        | 3.93%   |
| 2022    | 59        | 3.31%   |
| 2007    | 52        | 2.92%   |
| 2006    | 26        | 1.46%   |
| Unknown | 19        | 1.07%   |
| 2023    | 9         | 0.51%   |
| 2005    | 4         | 0.22%   |
| 2004    | 2         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1004      | 56.4%   |
| Desktop        | 639       | 35.9%   |
| Convertible    | 53        | 2.98%   |
| Mini pc        | 24        | 1.35%   |
| All in one     | 19        | 1.07%   |
| System on chip | 17        | 0.96%   |
| Server         | 13        | 0.73%   |
| Tablet         | 11        | 0.62%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1636      | 91.04%  |
| Enabled  | 161       | 8.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1776      | 99.78%  |
| Yes  | 4         | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 397       | 21.77%  |
| 16.01-24.0      | 390       | 21.38%  |
| 8.01-16.0       | 338       | 18.53%  |
| 3.01-4.0        | 316       | 17.32%  |
| 32.01-64.0      | 185       | 10.14%  |
| 1.01-2.0        | 60        | 3.29%   |
| 64.01-256.0     | 57        | 3.13%   |
| 24.01-32.0      | 34        | 1.86%   |
| 2.01-3.0        | 23        | 1.26%   |
| 0.51-1.0        | 17        | 0.93%   |
| More than 256.0 | 4         | 0.22%   |
| 0.01-0.5        | 3         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 684       | 33.71%  |
| 2.01-3.0    | 508       | 25.04%  |
| 4.01-8.0    | 298       | 14.69%  |
| 3.01-4.0    | 263       | 12.96%  |
| 0.51-1.0    | 128       | 6.31%   |
| 8.01-16.0   | 97        | 4.78%   |
| 0.01-0.5    | 33        | 1.63%   |
| 16.01-24.0  | 9         | 0.44%   |
| 24.01-32.0  | 7         | 0.34%   |
| 64.01-256.0 | 1         | 0.05%   |
| Unknown     | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1061      | 57.32%  |
| 2       | 466       | 25.18%  |
| 3       | 145       | 7.83%   |
| 4       | 83        | 4.48%   |
| 5       | 44        | 2.38%   |
| 6       | 21        | 1.13%   |
| 0       | 16        | 0.86%   |
| 9       | 4         | 0.22%   |
| 8       | 4         | 0.22%   |
| 7       | 4         | 0.22%   |
| 16      | 1         | 0.05%   |
| 10      | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1021      | 56.91%  |
| Yes       | 773       | 43.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1595      | 89.11%  |
| No        | 195       | 10.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1353      | 75.54%  |
| No        | 438       | 24.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1057      | 58.4%   |
| No        | 753       | 41.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Belgium | 1780      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Brussels       | 242       | 12.23%  |
| Antwerp        | 122       | 6.17%   |
| Ghent          | 80        | 4.04%   |
| Liège         | 58        | 2.93%   |
| Ixelles-Elsene | 45        | 2.28%   |
| Mechelen       | 32        | 1.62%   |
| Leuven         | 26        | 1.31%   |
| Bruges         | 22        | 1.11%   |
| Turnhout       | 20        | 1.01%   |
| Schaarbeek     | 18        | 0.91%   |
| Hasselt        | 17        | 0.86%   |
| Anderlecht     | 17        | 0.86%   |
| Uccle          | 16        | 0.81%   |
| Mons           | 15        | 0.76%   |
| Aalst          | 15        | 0.76%   |
| Namur          | 14        | 0.71%   |
| Lier           | 13        | 0.66%   |
| La Louvière   | 13        | 0.66%   |
| Etterbeek      | 13        | 0.66%   |
| Jette          | 12        | 0.61%   |
| Wilrijk        | 11        | 0.56%   |
| Sint-Niklaas   | 11        | 0.56%   |
| Roeselare      | 11        | 0.56%   |
| Mortsel        | 11        | 0.56%   |
| Kontich        | 11        | 0.56%   |
| Gavere         | 11        | 0.56%   |
| Duffel         | 11        | 0.56%   |
| Deurne         | 11        | 0.56%   |
| Charleroi      | 11        | 0.56%   |
| Boom           | 11        | 0.56%   |
| Tournai        | 10        | 0.51%   |
| Seraing        | 10        | 0.51%   |
| Kanne          | 10        | 0.51%   |
| Bilzen         | 10        | 0.51%   |
| Waregem        | 9         | 0.46%   |
| Vilvoorde      | 9         | 0.46%   |
| Sint-Truiden   | 9         | 0.46%   |
| Langdorp       | 9         | 0.46%   |
| Harelbeke      | 9         | 0.46%   |
| Brasschaat     | 9         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 540       | 973    | 20.64%  |
| WDC                         | 389       | 639    | 14.87%  |
| Seagate                     | 384       | 649    | 14.68%  |
| Toshiba                     | 170       | 231    | 6.5%    |
| Kingston                    | 139       | 215    | 5.31%   |
| SanDisk                     | 120       | 155    | 4.59%   |
| Unknown                     | 101       | 137    | 3.86%   |
| Crucial                     | 95        | 134    | 3.63%   |
| Hitachi                     | 83        | 108    | 3.17%   |
| SK hynix                    | 78        | 98     | 2.98%   |
| Intel                       | 73        | 87     | 2.79%   |
| Micron Technology           | 45        | 50     | 1.72%   |
| HGST                        | 44        | 64     | 1.68%   |
| Apple                       | 23        | 29     | 0.88%   |
| KIOXIA                      | 19        | 21     | 0.73%   |
| Phison                      | 18        | 21     | 0.69%   |
| LITEON                      | 18        | 24     | 0.69%   |
| Intenso                     | 17        | 25     | 0.65%   |
| Maxtor                      | 16        | 19     | 0.61%   |
| Corsair                     | 15        | 16     | 0.57%   |
| Micron/Crucial Technology   | 14        | 21     | 0.54%   |
| OCZ                         | 13        | 15     | 0.5%    |
| Fujitsu                     | 13        | 19     | 0.5%    |
| China                       | 13        | 16     | 0.5%    |
| A-DATA Technology           | 13        | 18     | 0.5%    |
| PNY                         | 10        | 11     | 0.38%   |
| LaCie                       | 9         | 12     | 0.34%   |
| LITEONIT                    | 8         | 11     | 0.31%   |
| Transcend                   | 7         | 12     | 0.27%   |
| Silicon Motion              | 7         | 10     | 0.27%   |
| Phison Electronics          | 7         | 8      | 0.27%   |
| Kingston Technology Company | 7         | 7      | 0.27%   |
| LDLC                        | 6         | 7      | 0.23%   |
| ASMT                        | 6         | 6      | 0.23%   |
| KingSpec                    | 5         | 5      | 0.19%   |
| GOODRAM                     | 5         | 8      | 0.19%   |
| Union Memory                | 4         | 7      | 0.15%   |
| SSSTC                       | 4         | 4      | 0.15%   |
| KingFast                    | 4         | 4      | 0.15%   |
| JMicron Technology          | 4         | 6      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 31        | 1.05%   |
| Samsung NVMe SSD Drive 1TB                          | 27        | 0.91%   |
| Samsung SSD 850 EVO 250GB                           | 26        | 0.88%   |
| Samsung SSD 850 EVO 500GB                           | 24        | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 24        | 0.81%   |
| Samsung NVMe SSD Drive 512GB                        | 23        | 0.78%   |
| Kingston SV300S37A120G 120GB SSD                    | 23        | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB                      | 22        | 0.74%   |
| Samsung SSD 860 EVO 1TB                             | 21        | 0.71%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 20        | 0.68%   |
| Kingston SA400S37120G 120GB SSD                     | 20        | 0.68%   |
| Samsung SSD 860 EVO 250GB                           | 19        | 0.64%   |
| Toshiba DT01ACA100 1TB                              | 17        | 0.57%   |
| Seagate ST2000DM001-1ER164 2TB                      | 16        | 0.54%   |
| Seagate Expansion 1TB                               | 15        | 0.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 15        | 0.51%   |
| Kingston SA400S37240G 240GB SSD                     | 15        | 0.51%   |
| Intel NVMe SSD Drive 512GB                          | 15        | 0.51%   |
| Toshiba MQ01ABD100 1TB                              | 14        | 0.47%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.47%   |
| Samsung SSD 870 EVO 1TB                             | 14        | 0.47%   |
| Samsung SSD 840 EVO 250GB                           | 14        | 0.47%   |
| Unknown MMC Card  64GB                              | 13        | 0.44%   |
| Unknown MMC Card  32GB                              | 13        | 0.44%   |
| SK hynix NVMe SSD Drive 512GB                       | 13        | 0.44%   |
| Seagate ST9500325AS 500GB                           | 13        | 0.44%   |
| Seagate ST500DM002-1BD142 500GB                     | 13        | 0.44%   |
| Seagate ST2000DM001-1CH164 2TB                      | 13        | 0.44%   |
| Samsung SSD 870 QVO 1TB                             | 13        | 0.44%   |
| HGST HTS721010A9E630 1TB                            | 13        | 0.44%   |
| Samsung SSD 970 EVO 1TB                             | 12        | 0.41%   |
| Crucial CT480BX500SSD1 480GB                        | 12        | 0.41%   |
| Unknown SD/MMC/MS PRO 128GB                         | 11        | 0.37%   |
| Unknown MMC Card  128GB                             | 11        | 0.37%   |
| Seagate ST3500418AS 500GB                           | 11        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB                        | 11        | 0.37%   |
| Crucial CT500MX500SSD1 500GB                        | 11        | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB                      | 10        | 0.34%   |
| Seagate ST1000DM010-2EP102 1TB                      | 10        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 373       | 632    | 35.66%  |
| WDC                 | 320       | 536    | 30.59%  |
| Toshiba             | 123       | 163    | 11.76%  |
| Hitachi             | 83        | 108    | 7.93%   |
| HGST                | 44        | 64     | 4.21%   |
| Samsung Electronics | 38        | 63     | 3.63%   |
| Maxtor              | 16        | 19     | 1.53%   |
| Fujitsu             | 13        | 18     | 1.24%   |
| Unknown             | 11        | 20     | 1.05%   |
| Apple               | 6         | 6      | 0.57%   |
| ASMT                | 4         | 4      | 0.38%   |
| LaCie               | 2         | 2      | 0.19%   |
| JMicron Technology  | 2         | 3      | 0.19%   |
| Hewlett-Packard     | 2         | 4      | 0.19%   |
| WD MediaMax         | 1         | 1      | 0.1%    |
| SINTECHI            | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 1      | 0.1%    |
| Lenovo              | 1         | 2      | 0.1%    |
| KESU                | 1         | 3      | 0.1%    |
| Intenso             | 1         | 4      | 0.1%    |
| IET                 | 1         | 3      | 0.1%    |
| Dell                | 1         | 1      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 301       | 524    | 35.54%  |
| Kingston            | 109       | 171    | 12.87%  |
| Crucial             | 81        | 116    | 9.56%   |
| SanDisk             | 67        | 90     | 7.91%   |
| WDC                 | 48        | 56     | 5.67%   |
| SK hynix            | 22        | 34     | 2.6%    |
| Intel               | 22        | 25     | 2.6%    |
| Toshiba             | 21        | 25     | 2.48%   |
| Micron Technology   | 17        | 19     | 2.01%   |
| LITEON              | 15        | 21     | 1.77%   |
| Intenso             | 15        | 19     | 1.77%   |
| OCZ                 | 13        | 15     | 1.53%   |
| China               | 13        | 16     | 1.53%   |
| Apple               | 11        | 15     | 1.3%    |
| Corsair             | 9         | 10     | 1.06%   |
| PNY                 | 8         | 9      | 0.94%   |
| LITEONIT            | 8         | 11     | 0.94%   |
| A-DATA Technology   | 7         | 11     | 0.83%   |
| Transcend           | 6         | 11     | 0.71%   |
| GOODRAM             | 5         | 8      | 0.59%   |
| KingSpec            | 4         | 4      | 0.47%   |
| Emtec               | 3         | 3      | 0.35%   |
| Zheino              | 2         | 2      | 0.24%   |
| Seagate             | 2         | 2      | 0.24%   |
| Plextor             | 2         | 2      | 0.24%   |
| Phison              | 2         | 2      | 0.24%   |
| KingFast            | 2         | 2      | 0.24%   |
| ASMT                | 2         | 2      | 0.24%   |
| Unknown             | 2         | 2      | 0.24%   |
| WDC WDS             | 1         | 1      | 0.12%   |
| Verbatim            | 1         | 1      | 0.12%   |
| Vaseky              | 1         | 1      | 0.12%   |
| TO Exter            | 1         | 1      | 0.12%   |
| tigo                | 1         | 1      | 0.12%   |
| Teclast             | 1         | 1      | 0.12%   |
| SPCC                | 1         | 2      | 0.12%   |
| Reeinno             | 1         | 3      | 0.12%   |
| Patriot             | 1         | 1      | 0.12%   |
| OWC                 | 1         | 2      | 0.12%   |
| OCZ-VERTEX          | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 866       | 1659   | 36.74%  |
| SSD     | 756       | 1262   | 32.07%  |
| NVMe    | 615       | 923    | 26.09%  |
| MMC     | 81        | 98     | 3.44%   |
| Unknown | 39        | 59     | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1293      | 2761   | 61.34%  |
| NVMe | 614       | 922    | 29.13%  |
| SAS  | 120       | 220    | 5.69%   |
| MMC  | 81        | 98     | 3.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 992       | 1642   | 56.85%  |
| 0.51-1.0   | 472       | 793    | 27.05%  |
| 1.01-2.0   | 154       | 266    | 8.83%   |
| 3.01-4.0   | 56        | 104    | 3.21%   |
| 4.01-10.0  | 37        | 61     | 2.12%   |
| 2.01-3.0   | 29        | 46     | 1.66%   |
| 10.01-20.0 | 5         | 9      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 496       | 25.75%  |
| 251-500        | 438       | 22.74%  |
| 501-1000       | 264       | 13.71%  |
| 1001-2000      | 173       | 8.98%   |
| 1-20           | 117       | 6.07%   |
| More than 3000 | 113       | 5.87%   |
| 51-100         | 113       | 5.87%   |
| 2001-3000      | 77        | 4%      |
| Unknown        | 74        | 3.84%   |
| 21-50          | 61        | 3.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 721       | 35.92%  |
| 21-50          | 297       | 14.8%   |
| 101-250        | 269       | 13.4%   |
| 51-100         | 203       | 10.11%  |
| 251-500        | 161       | 8.02%   |
| 501-1000       | 126       | 6.28%   |
| 1001-2000      | 90        | 4.48%   |
| Unknown        | 74        | 3.69%   |
| More than 3000 | 33        | 1.64%   |
| 2001-3000      | 33        | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 6         | 26     | 3.7%    |
| Seagate ST9500325AS 500GB           | 4         | 4      | 2.47%   |
| Seagate ST3500418AS 500GB           | 4         | 10     | 2.47%   |
| WDC WD10EZEX-21M2NA0 1TB            | 2         | 2      | 1.23%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 1.23%   |
| Seagate ST9750420AS 752GB           | 2         | 2      | 1.23%   |
| Seagate ST4000DM000-1F2168 4TB      | 2         | 4      | 1.23%   |
| Seagate ST320LT007-9ZV142 320GB     | 2         | 7      | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 7      | 1.23%   |
| Samsung Electronics SSD 970 EVO 1TB | 2         | 3      | 1.23%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 2      | 1.23%   |
| Hitachi HTS723232A7A364 320GB       | 2         | 2      | 1.23%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 3      | 1.23%   |
| HGST HTS725050A7E630 500GB          | 2         | 2      | 1.23%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1         | 1      | 0.62%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.62%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1         | 1      | 0.62%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 1      | 0.62%   |
| WDC WD5000AAKX-07U6AA0 500GB        | 1         | 1      | 0.62%   |
| WDC WD5000AAKS-22A7B0 500GB         | 1         | 1      | 0.62%   |
| WDC WD5000AADS-00S9B0 500GB         | 1         | 1      | 0.62%   |
| WDC WD40EFRX-68N32N0 4TB            | 1         | 1      | 0.62%   |
| WDC WD3200BPVT-55JJ5T0 320GB        | 1         | 1      | 0.62%   |
| WDC WD3200BEVT-60A23T0 320GB        | 1         | 1      | 0.62%   |
| WDC WD3200BEKT-75PVMT1 320GB        | 1         | 5      | 0.62%   |
| WDC WD3200BEKT-60PVMT0 320GB        | 1         | 1      | 0.62%   |
| WDC WD1600JS-60MHB5 160GB           | 1         | 1      | 0.62%   |
| WDC WD10SPCX-60HWST0 1TB            | 1         | 1      | 0.62%   |
| WDC WD10EZRX-00L4HB0 1TB            | 1         | 1      | 0.62%   |
| WDC WD10EZRX-00A8LB0 1TB            | 1         | 1      | 0.62%   |
| WDC WD10EARS-22Y5B1 1TB             | 1         | 1      | 0.62%   |
| WDC WD10EARS-00Y5B1 1TB             | 1         | 2      | 0.62%   |
| WDC WD10EALX-009BA0 1TB             | 1         | 1      | 0.62%   |
| WDC WD10EALS-00Z8A0 1TB             | 1         | 1      | 0.62%   |
| WDC WD10EADS-00P8B0 1TB             | 1         | 1      | 0.62%   |
| WDC WD10EADS-00M2B0 1TB             | 1         | 1      | 0.62%   |
| WDC WD Green M.2 2280 480GB SSD     | 1         | 1      | 0.62%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 0.62%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 0.62%   |
| Toshiba MK6476GSX 640GB             | 1         | 1      | 0.62%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 91     | 28.76%  |
| WDC                 | 22        | 30     | 14.38%  |
| Hitachi             | 15        | 16     | 9.8%    |
| Samsung Electronics | 14        | 18     | 9.15%   |
| Toshiba             | 9         | 9      | 5.88%   |
| Intel               | 8         | 8      | 5.23%   |
| Crucial             | 7         | 8      | 4.58%   |
| SK hynix            | 6         | 10     | 3.92%   |
| SanDisk             | 5         | 5      | 3.27%   |
| Kingston            | 5         | 10     | 3.27%   |
| HGST                | 5         | 5      | 3.27%   |
| Maxtor              | 4         | 4      | 2.61%   |
| Fujitsu             | 4         | 8      | 2.61%   |
| Micron Technology   | 2         | 2      | 1.31%   |
| OCZ                 | 1         | 1      | 0.65%   |
| KingFast            | 1         | 1      | 0.65%   |
| A-DATA Technology   | 1         | 1      | 0.65%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 91     | 41.51%  |
| WDC                 | 20        | 28     | 18.87%  |
| Hitachi             | 15        | 16     | 14.15%  |
| Toshiba             | 8         | 8      | 7.55%   |
| Samsung Electronics | 6         | 8      | 5.66%   |
| HGST                | 5         | 5      | 4.72%   |
| Maxtor              | 4         | 4      | 3.77%   |
| Fujitsu             | 4         | 8      | 3.77%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 103       | 168    | 69.13%  |
| SSD  | 39        | 50     | 26.17%  |
| NVMe | 7         | 9      | 4.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BUCT-63TWBY0 320GB                 | 1         | 1      | 25%     |
| Samsung Electronics MZVLW128HEGR-000L2 128GB | 1         | 2      | 25%     |
| Hitachi HDS721010DLE630 1TB                  | 1         | 1      | 25%     |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 2      | 25%     |
| Hitachi             | 1         | 1      | 25%     |
| HGST                | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1063      | 2396   | 55.02%  |
| Works    | 720       | 1373   | 37.27%  |
| Malfunc  | 145       | 227    | 7.51%   |
| Failed   | 4         | 5      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1215      | 53.43%  |
| AMD                              | 297       | 13.06%  |
| Samsung Electronics              | 261       | 11.48%  |
| SanDisk                          | 80        | 3.52%   |
| SK hynix                         | 54        | 2.37%   |
| Kingston Technology Company      | 37        | 1.63%   |
| JMicron Technology               | 32        | 1.41%   |
| ASMedia Technology               | 32        | 1.41%   |
| Marvell Technology Group         | 30        | 1.32%   |
| Phison Electronics               | 29        | 1.28%   |
| Micron/Crucial Technology        | 29        | 1.28%   |
| Toshiba America Info Systems     | 28        | 1.23%   |
| Micron Technology                | 28        | 1.23%   |
| Nvidia                           | 22        | 0.97%   |
| KIOXIA                           | 19        | 0.84%   |
| Union Memory (Shenzhen)          | 9         | 0.4%    |
| ADATA Technology                 | 9         | 0.4%    |
| Solid State Storage Technology   | 7         | 0.31%   |
| Silicon Motion                   | 7         | 0.31%   |
| Silicon Image                    | 5         | 0.22%   |
| Seagate Technology               | 5         | 0.22%   |
| Broadcom / LSI                   | 5         | 0.22%   |
| Apple                            | 5         | 0.22%   |
| LSI Logic / Symbios Logic        | 4         | 0.18%   |
| VIA Technologies                 | 3         | 0.13%   |
| Lite-On Technology               | 3         | 0.13%   |
| Hewlett-Packard                  | 3         | 0.13%   |
| Transcend                        | 2         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.09%   |
| Adaptec                          | 2         | 0.09%   |
| Realtek Semiconductor            | 1         | 0.04%   |
| PMC-Sierra                       | 1         | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| HighPoint Technologies           | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| Areca Technology                 | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 205       | 7.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 153       | 5.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 96        | 3.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 82        | 3.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 81        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 69        | 2.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 61        | 2.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 49        | 1.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 49        | 1.86%   |
| Samsung NVMe SSD Controller 980                                                | 44        | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 42        | 1.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 40        | 1.52%   |
| Intel SATA Controller [RAID mode]                                              | 38        | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 38        | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 37        | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 36        | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 34        | 1.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 32        | 1.21%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 32        | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 30        | 1.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 30        | 1.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 29        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 29        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 28        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 28        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 28        | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 27        | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 26        | 0.99%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 24        | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 23        | 0.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 19        | 0.72%   |
| JMicron JMB363 SATA/IDE Controller                                             | 18        | 0.68%   |
| Intel SSD 660P Series                                                          | 18        | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 18        | 0.68%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 16        | 0.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 16        | 0.61%   |
| Intel Comet Lake SATA AHCI Controller                                          | 16        | 0.61%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 16        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1274      | 55.1%   |
| NVMe | 619       | 26.77%  |
| IDE  | 235       | 10.16%  |
| RAID | 169       | 7.31%   |
| SAS  | 13        | 0.56%   |
| SCSI | 2         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1381      | 77.58%  |
| AMD     | 382       | 21.46%  |
| ARM     | 15        | 0.84%   |
| Unknown | 2         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 28        | 1.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 25        | 1.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 22        | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 1.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 19        | 1.07%   |
| AMD Ryzen 5 3600 6-Core Processor       | 19        | 1.07%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 16        | 0.9%    |
| AMD Ryzen 9 3900X 12-Core Processor     | 16        | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 14        | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 14        | 0.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 14        | 0.79%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 12        | 0.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 12        | 0.67%   |
| ARM Processor                           | 12        | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 12        | 0.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 11        | 0.62%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 11        | 0.62%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 11        | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 11        | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 11        | 0.62%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 11        | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 10        | 0.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 10        | 0.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 10        | 0.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 10        | 0.56%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 10        | 0.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 10        | 0.56%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 10        | 0.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 9         | 0.5%    |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 9         | 0.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 0.5%    |
| Intel Core i5-4460 CPU @ 3.20GHz        | 9         | 0.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz       | 9         | 0.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz        | 9         | 0.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 9         | 0.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 8         | 0.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 8         | 0.45%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 8         | 0.45%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 8         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 412       | 23.13%  |
| Intel Core i5           | 397       | 22.29%  |
| Other                   | 131       | 7.36%   |
| Intel Core i3           | 125       | 7.02%   |
| AMD Ryzen 5             | 96        | 5.39%   |
| Intel Core 2 Duo        | 91        | 5.11%   |
| AMD Ryzen 7             | 78        | 4.38%   |
| Intel Celeron           | 49        | 2.75%   |
| AMD Ryzen 9             | 42        | 2.36%   |
| Intel Xeon              | 33        | 1.85%   |
| Intel Pentium           | 30        | 1.68%   |
| Intel Pentium Dual-Core | 23        | 1.29%   |
| Intel Atom              | 23        | 1.29%   |
| Intel Core 2            | 20        | 1.12%   |
| Intel Core 2 Quad       | 19        | 1.07%   |
| AMD Ryzen 7 PRO         | 13        | 0.73%   |
| Intel Core i9           | 12        | 0.67%   |
| AMD Ryzen 5 PRO         | 12        | 0.67%   |
| AMD E1                  | 12        | 0.67%   |
| AMD Ryzen 3             | 10        | 0.56%   |
| AMD E                   | 10        | 0.56%   |
| AMD A8                  | 10        | 0.56%   |
| AMD FX                  | 9         | 0.51%   |
| AMD A6                  | 9         | 0.51%   |
| AMD A4                  | 9         | 0.51%   |
| Intel Pentium Dual      | 8         | 0.45%   |
| Intel Genuine           | 8         | 0.45%   |
| AMD A10                 | 8         | 0.45%   |
| Intel Pentium Silver    | 7         | 0.39%   |
| AMD Phenom II X4        | 7         | 0.39%   |
| Intel Pentium 4         | 5         | 0.28%   |
| AMD Phenom              | 5         | 0.28%   |
| AMD Athlon II X2        | 4         | 0.22%   |
| AMD Athlon 64 X2        | 4         | 0.22%   |
| Intel Xeon Silver       | 3         | 0.17%   |
| Intel Celeron M         | 3         | 0.17%   |
| ARM BCM                 | 3         | 0.17%   |
| AMD Turion 64 X2 Mobile | 3         | 0.17%   |
| AMD Ryzen Threadripper  | 3         | 0.17%   |
| AMD Phenom II X6        | 3         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 678       | 38.03%  |
| 2       | 664       | 37.24%  |
| 6       | 177       | 9.93%   |
| 8       | 133       | 7.46%   |
| 12      | 47        | 2.64%   |
| 1       | 29        | 1.63%   |
| 10      | 18        | 1.01%   |
| 16      | 12        | 0.67%   |
| Unknown | 7         | 0.39%   |
| 3       | 6         | 0.34%   |
| 14      | 5         | 0.28%   |
| 64      | 2         | 0.11%   |
| 32      | 2         | 0.11%   |
| 128     | 1         | 0.06%   |
| 24      | 1         | 0.06%   |
| 20      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1759      | 98.82%  |
| 2       | 17        | 0.96%   |
| Unknown | 3         | 0.17%   |
| 3       | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1222      | 68.54%  |
| 1       | 554       | 31.07%  |
| Unknown | 7         | 0.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1734      | 97.03%  |
| Unknown        | 39        | 2.18%   |
| 32-bit         | 13        | 0.73%   |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 445       | 23.86%  |
| 0x306a9    | 114       | 6.11%   |
| 0x206a7    | 105       | 5.63%   |
| 0x306c3    | 95        | 5.09%   |
| 0x1067a    | 62        | 3.32%   |
| 0x906e9    | 49        | 2.63%   |
| 0x906ea    | 46        | 2.47%   |
| 0x806ea    | 46        | 2.47%   |
| 0x806ec    | 43        | 2.31%   |
| 0x40651    | 37        | 1.98%   |
| 0x506e3    | 35        | 1.88%   |
| 0x806c1    | 34        | 1.82%   |
| 0x20655    | 33        | 1.77%   |
| 0x806e9    | 32        | 1.72%   |
| 0x306d4    | 30        | 1.61%   |
| 0x406e3    | 29        | 1.55%   |
| 0x08701021 | 28        | 1.5%    |
| 0x6fd      | 27        | 1.45%   |
| 0x10676    | 22        | 1.18%   |
| 0x0a50000c | 19        | 1.02%   |
| 0xa0652    | 18        | 0.97%   |
| 0x08600106 | 18        | 0.97%   |
| 0x30678    | 15        | 0.8%    |
| 0x106e5    | 15        | 0.8%    |
| 0x08701013 | 15        | 0.8%    |
| 0x6f6      | 14        | 0.75%   |
| 0x08608103 | 14        | 0.75%   |
| 0x806eb    | 13        | 0.7%    |
| 0x6fb      | 13        | 0.7%    |
| 0x08108109 | 12        | 0.64%   |
| 0x206d7    | 11        | 0.59%   |
| 0x20652    | 11        | 0.59%   |
| 0x08600103 | 11        | 0.59%   |
| 0x0a201009 | 10        | 0.54%   |
| 0x05000119 | 10        | 0.54%   |
| 0x010000c8 | 10        | 0.54%   |
| 0x0810100b | 9         | 0.48%   |
| 0x0800820d | 9         | 0.48%   |
| 0x07030105 | 9         | 0.48%   |
| 0x06001119 | 9         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 307       | 17.23%  |
| Haswell          | 170       | 9.54%   |
| IvyBridge        | 142       | 7.97%   |
| SandyBridge      | 139       | 7.8%    |
| Zen 2            | 101       | 5.67%   |
| Penryn           | 99        | 5.56%   |
| Skylake          | 82        | 4.6%    |
| Unknown          | 75        | 4.21%   |
| Core             | 74        | 4.15%   |
| Zen 3            | 57        | 3.2%    |
| Westmere         | 54        | 3.03%   |
| TigerLake        | 51        | 2.86%   |
| CometLake        | 41        | 2.3%    |
| Zen+             | 40        | 2.24%   |
| Silvermont       | 40        | 2.24%   |
| Broadwell        | 40        | 2.24%   |
| Zen              | 28        | 1.57%   |
| Alderlake Hybrid | 28        | 1.57%   |
| Nehalem          | 27        | 1.52%   |
| K10              | 27        | 1.52%   |
| Icelake          | 20        | 1.12%   |
| Piledriver       | 19        | 1.07%   |
| Bobcat           | 17        | 0.95%   |
| Goldmont plus    | 15        | 0.84%   |
| Excavator        | 14        | 0.79%   |
| Puma             | 13        | 0.73%   |
| K8 Hammer        | 10        | 0.56%   |
| Jaguar           | 10        | 0.56%   |
| Bonnell          | 10        | 0.56%   |
| P6               | 8         | 0.45%   |
| NetBurst         | 8         | 0.45%   |
| Goldmont         | 5         | 0.28%   |
| Tremont          | 3         | 0.17%   |
| K8 & K10 hybrid  | 3         | 0.17%   |
| Steamroller      | 2         | 0.11%   |
| K10 Llano        | 2         | 0.11%   |
| Gracemont        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1000      | 47.64%  |
| Nvidia                           | 643       | 30.63%  |
| AMD                              | 442       | 21.06%  |
| Matrox Electronics Systems       | 9         | 0.43%   |
| ASPEED Technology                | 3         | 0.14%   |
| VIA Technologies                 | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 88        | 4.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 85        | 3.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 51        | 2.36%   |
| Intel UHD Graphics 620                                                                   | 51        | 2.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 50        | 2.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 45        | 2.08%   |
| AMD Renoir                                                                               | 37        | 1.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 35        | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 35        | 1.62%   |
| Intel HD Graphics 630                                                                    | 34        | 1.57%   |
| Intel HD Graphics 620                                                                    | 33        | 1.53%   |
| Intel HD Graphics 5500                                                                   | 30        | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 29        | 1.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 1.34%   |
| Intel Core Processor Integrated Graphics Controller                                      | 29        | 1.34%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 26        | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 25        | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 0.97%   |
| Intel HD Graphics 530                                                                    | 20        | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 0.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 20        | 0.93%   |
| AMD Lucienne                                                                             | 20        | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 19        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 0.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 19        | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 17        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 14        | 0.65%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 14        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.6%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 13        | 0.6%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 12        | 0.56%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 12        | 0.56%   |
| Nvidia GT218 [GeForce 210]                                                               | 11        | 0.51%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 11        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 700       | 38.89%  |
| 1 x Nvidia         | 387       | 21.5%   |
| 1 x AMD            | 348       | 19.33%  |
| Intel + Nvidia     | 226       | 12.56%  |
| Intel + AMD        | 53        | 2.94%   |
| AMD + Nvidia       | 26        | 1.44%   |
| Other              | 21        | 1.17%   |
| 2 x AMD            | 17        | 0.94%   |
| 1 x Matrox         | 9         | 0.5%    |
| 2 x Intel          | 4         | 0.22%   |
| 2 x Nvidia         | 3         | 0.17%   |
| 1 x ASPEED         | 2         | 0.11%   |
| 1 x VIA            | 1         | 0.06%   |
| 1 x SiS            | 1         | 0.06%   |
| Nvidia + ASPEED    | 1         | 0.06%   |
| Intel + 2 x Nvidia | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1401      | 76.81%  |
| Proprietary | 337       | 18.48%  |
| Unknown     | 86        | 4.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 987       | 53.44%  |
| 1.01-2.0   | 224       | 12.13%  |
| 0.01-0.5   | 218       | 11.8%   |
| 0.51-1.0   | 150       | 8.12%   |
| 3.01-4.0   | 102       | 5.52%   |
| 7.01-8.0   | 85        | 4.6%    |
| 5.01-6.0   | 40        | 2.17%   |
| 8.01-16.0  | 25        | 1.35%   |
| 2.01-3.0   | 12        | 0.65%   |
| 16.01-24.0 | 4         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 278       | 14.32%  |
| AU Optronics            | 274       | 14.11%  |
| LG Display              | 187       | 9.63%   |
| Chimei Innolux          | 135       | 6.95%   |
| BOE                     | 122       | 6.28%   |
| Dell                    | 106       | 5.46%   |
| Iiyama                  | 81        | 4.17%   |
| Goldstar                | 74        | 3.81%   |
| Philips                 | 63        | 3.24%   |
| Hewlett-Packard         | 62        | 3.19%   |
| AOC                     | 47        | 2.42%   |
| BenQ                    | 43        | 2.21%   |
| Sharp                   | 39        | 2.01%   |
| Acer                    | 39        | 2.01%   |
| Medion                  | 34        | 1.75%   |
| Apple                   | 34        | 1.75%   |
| Lenovo                  | 32        | 1.65%   |
| Chi Mei Optoelectronics | 32        | 1.65%   |
| Ancor Communications    | 27        | 1.39%   |
| Sony                    | 16        | 0.82%   |
| Unknown                 | 13        | 0.67%   |
| Fujitsu Siemens         | 12        | 0.62%   |
| InfoVision              | 11        | 0.57%   |
| ASUSTek Computer        | 10        | 0.51%   |
| PANDA                   | 9         | 0.46%   |
| LG Philips              | 9         | 0.46%   |
| Eizo                    | 9         | 0.46%   |
| Vestel Elektronik       | 8         | 0.41%   |
| CSO                     | 8         | 0.41%   |
| Valve                   | 7         | 0.36%   |
| Idek Iiyama             | 7         | 0.36%   |
| Panasonic               | 6         | 0.31%   |
| LG Electronics          | 6         | 0.31%   |
| Arnos Instruments       | 6         | 0.31%   |
| ViewSonic               | 5         | 0.26%   |
| Seiko/Epson             | 5         | 0.26%   |
| Packard Bell            | 5         | 0.26%   |
| NEC Computers           | 5         | 0.26%   |
| Toshiba                 | 4         | 0.21%   |
| Quanta Display          | 4         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 17        | 0.83%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 14        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 10        | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 9         | 0.44%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 9         | 0.44%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 9         | 0.44%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                          | 8         | 0.39%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 8         | 0.39%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 8         | 0.39%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 7         | 0.34%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 7         | 0.34%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 6         | 0.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 6         | 0.29%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 6         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 6         | 0.29%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.29%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 6         | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 6         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 6         | 0.29%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                        | 6         | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 5         | 0.24%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch         | 5         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 5         | 0.24%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 5         | 0.24%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                     | 5         | 0.24%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                         | 5         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 5         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch          | 5         | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch  | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch            | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO149E 1600x900 382x214mm 17.2-inch             | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 5         | 0.24%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 4         | 0.2%    |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 4         | 0.2%    |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch       | 4         | 0.2%    |
| Samsung Electronics S24R65x SAM1022 1920x1080 527x296mm 23.8-inch         | 4         | 0.2%    |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 480x270mm 21.7-inch         | 4         | 0.2%    |
| Medion MD 20430 MED36A2 1920x1080 521x293mm 23.5-inch                     | 4         | 0.2%    |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch              | 4         | 0.2%    |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch               | 4         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 820       | 44.02%  |
| 1366x768 (WXGA)    | 225       | 12.08%  |
| 3840x2160 (4K)     | 135       | 7.25%   |
| 1600x900 (HD+)     | 123       | 6.6%    |
| 2560x1440 (QHD)    | 106       | 5.69%   |
| 1680x1050 (WSXGA+) | 70        | 3.76%   |
| 1280x1024 (SXGA)   | 60        | 3.22%   |
| 1440x900 (WXGA+)   | 51        | 2.74%   |
| 1920x1200 (WUXGA)  | 45        | 2.42%   |
| 1280x800 (WXGA)    | 37        | 1.99%   |
| Unknown            | 26        | 1.4%    |
| 3440x1440          | 23        | 1.23%   |
| 3840x1080          | 18        | 0.97%   |
| 2560x1600          | 11        | 0.59%   |
| 2560x1080          | 10        | 0.54%   |
| 1360x768           | 10        | 0.54%   |
| 3840x2400          | 9         | 0.48%   |
| 1600x1200          | 8         | 0.43%   |
| 800x1280           | 7         | 0.38%   |
| 2880x1800          | 7         | 0.38%   |
| 1024x600           | 7         | 0.38%   |
| 3200x1800 (QHD+)   | 6         | 0.32%   |
| 1680x945           | 5         | 0.27%   |
| 1024x768 (XGA)     | 5         | 0.27%   |
| 5760x1080          | 3         | 0.16%   |
| 2736x1824          | 3         | 0.16%   |
| 3840x1600          | 2         | 0.11%   |
| 2960x1050          | 2         | 0.11%   |
| 2256x1504          | 2         | 0.11%   |
| 2048x1152          | 2         | 0.11%   |
| 1920x540           | 2         | 0.11%   |
| 1920x1280          | 2         | 0.11%   |
| 1280x960           | 2         | 0.11%   |
| 7680x2160          | 1         | 0.05%   |
| 6320x1800          | 1         | 0.05%   |
| 5120x1440          | 1         | 0.05%   |
| 4480x1080          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 3600x1080          | 1         | 0.05%   |
| 3520x1080          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 473       | 24.19%  |
| 17      | 178       | 9.1%    |
| 27      | 170       | 8.7%    |
| 13      | 154       | 7.88%   |
| 24      | 148       | 7.57%   |
| 23      | 134       | 6.85%   |
| Unknown | 111       | 5.68%   |
| 14      | 109       | 5.58%   |
| 21      | 98        | 5.01%   |
| 19      | 52        | 2.66%   |
| 22      | 38        | 1.94%   |
| 34      | 30        | 1.53%   |
| 31      | 30        | 1.53%   |
| 18      | 29        | 1.48%   |
| 20      | 27        | 1.38%   |
| 12      | 26        | 1.33%   |
| 11      | 18        | 0.92%   |
| 25      | 14        | 0.72%   |
| 16      | 13        | 0.66%   |
| 72      | 12        | 0.61%   |
| 10      | 12        | 0.61%   |
| 84      | 11        | 0.56%   |
| 32      | 8         | 0.41%   |
| 54      | 7         | 0.36%   |
| 40      | 7         | 0.36%   |
| 7       | 6         | 0.31%   |
| 49      | 5         | 0.26%   |
| 65      | 3         | 0.15%   |
| 33      | 3         | 0.15%   |
| 29      | 3         | 0.15%   |
| 26      | 3         | 0.15%   |
| 52      | 2         | 0.1%    |
| 48      | 2         | 0.1%    |
| 46      | 2         | 0.1%    |
| 43      | 2         | 0.1%    |
| 42      | 2         | 0.1%    |
| 39      | 2         | 0.1%    |
| 37      | 2         | 0.1%    |
| 3       | 2         | 0.1%    |
| 142     | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 649       | 33.59%  |
| 501-600        | 416       | 21.53%  |
| 351-400        | 219       | 11.34%  |
| 401-500        | 202       | 10.46%  |
| 201-300        | 153       | 7.92%   |
| Unknown        | 111       | 5.75%   |
| 601-700        | 70        | 3.62%   |
| 701-800        | 41        | 2.12%   |
| 1001-1500      | 24        | 1.24%   |
| 1501-2000      | 23        | 1.19%   |
| 801-900        | 12        | 0.62%   |
| 1-100          | 7         | 0.36%   |
| 901-1000       | 4         | 0.21%   |
| More than 2000 | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1288      | 73.77%  |
| 16/10   | 231       | 13.23%  |
| Unknown | 91        | 5.21%   |
| 5/4     | 54        | 3.09%   |
| 21/9    | 33        | 1.89%   |
| 4/3     | 17        | 0.97%   |
| 3/2     | 12        | 0.69%   |
| 6/5     | 6         | 0.34%   |
| 0.67    | 6         | 0.34%   |
| 32/9    | 5         | 0.29%   |
| 1.00    | 2         | 0.11%   |
| 3.73    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 472       | 24.42%  |
| 201-250        | 328       | 16.97%  |
| 81-90          | 175       | 9.05%   |
| 301-350        | 174       | 9%      |
| 121-130        | 139       | 7.19%   |
| 151-200        | 119       | 6.16%   |
| Unknown        | 111       | 5.74%   |
| 71-80          | 89        | 4.6%    |
| 351-500        | 75        | 3.88%   |
| 251-300        | 60        | 3.1%    |
| More than 1000 | 40        | 2.07%   |
| 141-150        | 31        | 1.6%    |
| 131-140        | 25        | 1.29%   |
| 61-70          | 24        | 1.24%   |
| 501-1000       | 22        | 1.14%   |
| 51-60          | 18        | 0.93%   |
| 41-50          | 12        | 0.62%   |
| 111-120        | 10        | 0.52%   |
| 1-40           | 7         | 0.36%   |
| 91-100         | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 599       | 31.79%  |
| 121-160       | 515       | 27.34%  |
| 101-120       | 452       | 23.99%  |
| 161-240       | 124       | 6.58%   |
| Unknown       | 111       | 5.89%   |
| More than 240 | 52        | 2.76%   |
| 1-50          | 31        | 1.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1416      | 77.21%  |
| 2     | 289       | 15.76%  |
| 0     | 94        | 5.13%   |
| 3     | 34        | 1.85%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 949       | 35.46%  |
| Realtek Semiconductor             | 919       | 34.34%  |
| Qualcomm Atheros                  | 288       | 10.76%  |
| Broadcom                          | 146       | 5.46%   |
| Broadcom Limited                  | 32        | 1.2%    |
| TP-Link                           | 31        | 1.16%   |
| Marvell Technology Group          | 31        | 1.16%   |
| MediaTek                          | 27        | 1.01%   |
| Ralink                            | 24        | 0.9%    |
| Nvidia                            | 21        | 0.78%   |
| D-Link System                     | 17        | 0.64%   |
| ASIX Electronics                  | 16        | 0.6%    |
| Ralink Technology                 | 15        | 0.56%   |
| Lenovo                            | 10        | 0.37%   |
| Dell                              | 10        | 0.37%   |
| DisplayLink                       | 9         | 0.34%   |
| IMC Networks                      | 8         | 0.3%    |
| Sierra Wireless                   | 7         | 0.26%   |
| Microsoft                         | 7         | 0.26%   |
| D-Link                            | 7         | 0.26%   |
| Ericsson Business Mobile Networks | 6         | 0.22%   |
| ASUSTek Computer                  | 6         | 0.22%   |
| Microchip Technology              | 5         | 0.19%   |
| Linksys                           | 5         | 0.19%   |
| JMicron Technology                | 5         | 0.19%   |
| Sitecom Europe                    | 4         | 0.15%   |
| Hewlett-Packard                   | 4         | 0.15%   |
| Fibocom                           | 4         | 0.15%   |
| Aquantia                          | 4         | 0.15%   |
| Samsung Electronics               | 3         | 0.11%   |
| Qualcomm Atheros Communications   | 3         | 0.11%   |
| Qualcomm                          | 3         | 0.11%   |
| Arduino SA                        | 3         | 0.11%   |
| Xiaomi                            | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.07%   |
| OPPO Electronics                  | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |
| MosChip Semiconductor             | 2         | 0.07%   |
| Huawei Technologies               | 2         | 0.07%   |
| Google                            | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 630       | 19.66%  |
| Intel Wi-Fi 6 AX200                                               | 117       | 3.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 81        | 2.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 80        | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 61        | 1.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 54        | 1.68%   |
| Intel Wireless 7260                                               | 49        | 1.53%   |
| Intel I211 Gigabit Network Connection                             | 49        | 1.53%   |
| Intel Wireless 8265 / 8275                                        | 47        | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 46        | 1.44%   |
| Intel Wi-Fi 6 AX201                                               | 39        | 1.22%   |
| Intel Wireless 7265                                               | 38        | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 36        | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 33        | 1.03%   |
| Intel Wireless 8260                                               | 32        | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 32        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 31        | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 30        | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 29        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 0.9%    |
| Intel Ethernet Connection (2) I219-V                              | 27        | 0.84%   |
| Intel Wireless-AC 9260                                            | 25        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 25        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 22        | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 22        | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 20        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 0.59%   |
| Intel Ethernet Controller I225-V                                  | 19        | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.59%   |
| Intel Centrino Wireless-N 2230                                    | 19        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 18        | 0.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 18        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 0.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 16        | 0.5%    |
| Intel WiFi Link 5100                                              | 15        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 725       | 51.02%  |
| Qualcomm Atheros                      | 226       | 15.9%   |
| Realtek Semiconductor                 | 186       | 13.09%  |
| Broadcom                              | 95        | 6.69%   |
| Ralink                                | 24        | 1.69%   |
| MediaTek                              | 23        | 1.62%   |
| TP-Link                               | 21        | 1.48%   |
| Broadcom Limited                      | 18        | 1.27%   |
| Ralink Technology                     | 15        | 1.06%   |
| D-Link System                         | 14        | 0.99%   |
| IMC Networks                          | 8         | 0.56%   |
| Sierra Wireless                       | 7         | 0.49%   |
| D-Link                                | 7         | 0.49%   |
| Microsoft                             | 6         | 0.42%   |
| ASUSTek Computer                      | 6         | 0.42%   |
| Linksys                               | 5         | 0.35%   |
| Sitecom Europe                        | 4         | 0.28%   |
| Fibocom                               | 4         | 0.28%   |
| Dell                                  | 4         | 0.28%   |
| Qualcomm Atheros Communications       | 3         | 0.21%   |
| Qualcomm                              | 3         | 0.21%   |
| Marvell Technology Group              | 2         | 0.14%   |
| Ericsson Business Mobile Networks     | 2         | 0.14%   |
| Edimax Technology                     | 2         | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.14%   |
| Z-Com                                 | 1         | 0.07%   |
| Texas Instruments                     | 1         | 0.07%   |
| Panasonic (Matsushita)                | 1         | 0.07%   |
| NetGear                               | 1         | 0.07%   |
| Hewlett-Packard                       | 1         | 0.07%   |
| Guillemot                             | 1         | 0.07%   |
| Gemtek                                | 1         | 0.07%   |
| Belkin Components                     | 1         | 0.07%   |
| AVM                                   | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 117       | 8.18%   |
| Intel Wireless 7260                                            | 49        | 3.43%   |
| Intel Wireless 8265 / 8275                                     | 47        | 3.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 46        | 3.22%   |
| Intel Wi-Fi 6 AX201                                            | 39        | 2.73%   |
| Intel Wireless 7265                                            | 38        | 2.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 36        | 2.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 33        | 2.31%   |
| Intel Wireless 8260                                            | 32        | 2.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 32        | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 31        | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 30        | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 29        | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 2.03%   |
| Intel Wireless-AC 9260                                         | 25        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 25        | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 22        | 1.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 22        | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.33%   |
| Intel Centrino Wireless-N 2230                                 | 19        | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 18        | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 16        | 1.12%   |
| Intel WiFi Link 5100                                           | 15        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 1.05%   |
| Intel Centrino Advanced-N 6235                                 | 15        | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 14        | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 14        | 0.98%   |
| Intel Centrino Advanced-N 6200                                 | 14        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 0.98%   |
| Intel Wireless 3165                                            | 13        | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 13        | 0.91%   |
| Intel Centrino Ultimate-N 6300                                 | 13        | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 12        | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 12        | 0.84%   |
| Intel Wireless 3160                                            | 11        | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 11        | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 10        | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 846       | 49.88%  |
| Intel                                  | 512       | 30.19%  |
| Qualcomm Atheros                       | 110       | 6.49%   |
| Broadcom                               | 68        | 4.01%   |
| Marvell Technology Group               | 29        | 1.71%   |
| Nvidia                                 | 21        | 1.24%   |
| ASIX Electronics                       | 16        | 0.94%   |
| Broadcom Limited                       | 14        | 0.83%   |
| Lenovo                                 | 10        | 0.59%   |
| TP-Link                                | 9         | 0.53%   |
| DisplayLink                            | 9         | 0.53%   |
| JMicron Technology                     | 5         | 0.29%   |
| Microchip Technology                   | 4         | 0.24%   |
| MediaTek                               | 4         | 0.24%   |
| Aquantia                               | 4         | 0.24%   |
| Hewlett-Packard                        | 3         | 0.18%   |
| D-Link System                          | 3         | 0.18%   |
| Xiaomi                                 | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.12%   |
| Samsung Electronics                    | 2         | 0.12%   |
| OPPO Electronics                       | 2         | 0.12%   |
| Motorola PCS                           | 2         | 0.12%   |
| MosChip Semiconductor                  | 2         | 0.12%   |
| Google                                 | 2         | 0.12%   |
| Attansic Technology                    | 2         | 0.12%   |
| Apple                                  | 2         | 0.12%   |
| ADMtek                                 | 2         | 0.12%   |
| VIA Technologies                       | 1         | 0.06%   |
| Tenda                                  | 1         | 0.06%   |
| Tehuti Networks                        | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| OpenMoko                               | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| IBM                                    | 1         | 0.06%   |
| Huawei Technologies                    | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 630       | 36.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 81        | 4.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 80        | 4.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 61        | 3.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 54        | 3.1%    |
| Intel I211 Gigabit Network Connection                             | 49        | 2.81%   |
| Intel Ethernet Connection (2) I219-V                              | 27        | 1.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 1.32%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 20        | 1.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 1.09%   |
| Intel Ethernet Controller I225-V                                  | 19        | 1.09%   |
| Intel Ethernet Connection I217-V                                  | 19        | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 18        | 1.03%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.98%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 0.92%   |
| Intel Ethernet Connection (2) I218-V                              | 15        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14        | 0.8%    |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 0.75%   |
| Intel Ethernet Connection (6) I219-LM                             | 11        | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.63%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 0.63%   |
| Intel I210 Gigabit Network Connection                             | 10        | 0.57%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.57%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 9         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.52%   |
| Intel 82574L Gigabit Network Connection                           | 9         | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                             | 7         | 0.4%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 7         | 0.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1589      | 53.41%  |
| WiFi     | 1354      | 45.51%  |
| Modem    | 28        | 0.94%   |
| Unknown  | 4         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 991       | 52.55%  |
| Ethernet | 895       | 47.45%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1021      | 57.07%  |
| 1     | 670       | 37.45%  |
| 3     | 51        | 2.85%   |
| 0     | 35        | 1.96%   |
| 4     | 6         | 0.34%   |
| 5     | 3         | 0.17%   |
| 6     | 2         | 0.11%   |
| 7     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1285      | 69.5%   |
| Yes  | 564       | 30.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 558       | 51.96%  |
| Realtek Semiconductor           | 89        | 8.29%   |
| Qualcomm Atheros Communications | 60        | 5.59%   |
| Broadcom                        | 50        | 4.66%   |
| Cambridge Silicon Radio         | 47        | 4.38%   |
| IMC Networks                    | 45        | 4.19%   |
| Foxconn / Hon Hai               | 37        | 3.45%   |
| Apple                           | 35        | 3.26%   |
| Lite-On Technology              | 27        | 2.51%   |
| ASUSTek Computer                | 27        | 2.51%   |
| Dell                            | 25        | 2.33%   |
| Hewlett-Packard                 | 24        | 2.23%   |
| Toshiba                         | 11        | 1.02%   |
| Belkin Components               | 8         | 0.74%   |
| MediaTek                        | 6         | 0.56%   |
| Ralink                          | 5         | 0.47%   |
| Alps Electric                   | 5         | 0.47%   |
| Foxconn International           | 4         | 0.37%   |
| Ralink Technology               | 3         | 0.28%   |
| Marvell Semiconductor           | 2         | 0.19%   |
| TP-Link                         | 1         | 0.09%   |
| Realtek                         | 1         | 0.09%   |
| Qcom                            | 1         | 0.09%   |
| Micro Star International        | 1         | 0.09%   |
| Logitech                        | 1         | 0.09%   |
| HTC (High Tech Computer)        | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 187       | 17.38%  |
| Intel AX200 Bluetooth                                 | 115       | 10.69%  |
| Intel AX201 Bluetooth                                 | 88        | 8.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 72        | 6.69%   |
| Realtek Bluetooth Radio                               | 51        | 4.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 47        | 4.37%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 29        | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 25        | 2.32%   |
| Realtek  Bluetooth 4.2 Adapter                        | 24        | 2.23%   |
| IMC Networks Bluetooth Radio                          | 18        | 1.67%   |
| Intel Bluetooth Device                                | 17        | 1.58%   |
| Qualcomm Atheros  Bluetooth Device                    | 16        | 1.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 15        | 1.39%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 14        | 1.3%    |
| IMC Networks Bluetooth Device                         | 14        | 1.3%    |
| Apple Bluetooth Host Controller                       | 14        | 1.3%    |
| Foxconn / Hon Hai Bluetooth Device                    | 13        | 1.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 12        | 1.12%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 12        | 1.12%   |
| Intel Wireless-AC 3168 Bluetooth                      | 11        | 1.02%   |
| Intel AX210 Bluetooth                                 | 11        | 1.02%   |
| HP Broadcom 2070 Bluetooth Combo                      | 11        | 1.02%   |
| Apple Bluetooth USB Host Controller                   | 11        | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 10        | 0.93%   |
| Dell DW375 Bluetooth Module                           | 10        | 0.93%   |
| Broadcom HP Portable SoftSailing                      | 10        | 0.93%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 9         | 0.84%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 8         | 0.74%   |
| Broadcom BCM2045B (BDC-2.1)                           | 8         | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                      | 7         | 0.65%   |
| Dell BCM20702A0 Bluetooth Module                      | 7         | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 6         | 0.56%   |
| Lite-On Bluetooth Device                              | 6         | 0.56%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 6         | 0.56%   |
| Realtek RTL8821A Bluetooth                            | 5         | 0.46%   |
| Ralink RT3290 Bluetooth                               | 5         | 0.46%   |
| MediaTek Wireless_Device                              | 5         | 0.46%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 5         | 0.46%   |
| Foxconn / Hon Hai Wireless_Device                     | 5         | 0.46%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 5         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1328      | 51.83%  |
| Nvidia                               | 482       | 18.81%  |
| AMD                                  | 466       | 18.19%  |
| C-Media Electronics                  | 42        | 1.64%   |
| Logitech                             | 21        | 0.82%   |
| Kingston Technology                  | 16        | 0.62%   |
| Creative Labs                        | 16        | 0.62%   |
| Realtek Semiconductor                | 13        | 0.51%   |
| Corsair                              | 12        | 0.47%   |
| GN Netcom                            | 11        | 0.43%   |
| Plantronics                          | 10        | 0.39%   |
| Hewlett-Packard                      | 9         | 0.35%   |
| Focusrite-Novation                   | 9         | 0.35%   |
| JMTek                                | 7         | 0.27%   |
| RODE Microphones                     | 6         | 0.23%   |
| Razer USA                            | 6         | 0.23%   |
| ASUSTek Computer                     | 6         | 0.23%   |
| VIA Technologies                     | 5         | 0.2%    |
| Texas Instruments                    | 5         | 0.2%    |
| Micro Star International             | 5         | 0.2%    |
| Generalplus Technology               | 5         | 0.2%    |
| Audio-Technica                       | 5         | 0.2%    |
| SteelSeries ApS                      | 4         | 0.16%   |
| Sennheiser Communications            | 4         | 0.16%   |
| Roland                               | 4         | 0.16%   |
| Blue Microphones                     | 4         | 0.16%   |
| Astro Gaming                         | 4         | 0.16%   |
| Lenovo                               | 3         | 0.12%   |
| Dell                                 | 3         | 0.12%   |
| Trust                                | 2         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.08%   |
| Sony                                 | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.08%   |
| OPPO Electronics                     | 2         | 0.08%   |
| M-Audio                              | 2         | 0.08%   |
| Harman International                 | 2         | 0.08%   |
| GYROCOM C&C                          | 2         | 0.08%   |
| FIFINE Microphones                   | 2         | 0.08%   |
| Creative Technology                  | 2         | 0.08%   |
| BEHRINGER International              | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 139       | 4.65%   |
| AMD Family 17h/19h HD Audio Controller                                     | 137       | 4.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 132       | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 122       | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 91        | 3.05%   |
| AMD Starship/Matisse HD Audio Controller                                   | 85        | 2.84%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 79        | 2.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 70        | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 70        | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 67        | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 59        | 1.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 55        | 1.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 51        | 1.71%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 47        | 1.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 46        | 1.54%   |
| Intel 8 Series HD Audio Controller                                         | 46        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 44        | 1.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 42        | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 42        | 1.41%   |
| AMD FCH Azalia Controller                                                  | 42        | 1.41%   |
| Intel 200 Series PCH HD Audio                                              | 40        | 1.34%   |
| Intel Broadwell-U Audio Controller                                         | 36        | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 33        | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 33        | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 33        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 32        | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 32        | 1.07%   |
| Nvidia High Definition Audio Controller                                    | 30        | 1%      |
| Nvidia GK107 HDMI Audio Controller                                         | 29        | 0.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 29        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 28        | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 28        | 0.94%   |
| AMD Kabini HDMI/DP Audio                                                   | 28        | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 0.9%    |
| Intel CM238 HD Audio Controller                                            | 27        | 0.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 27        | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                              | 26        | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 26        | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 25        | 0.84%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 24        | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 260       | 23.51%  |
| SK hynix            | 205       | 18.54%  |
| Kingston            | 134       | 12.12%  |
| Corsair             | 117       | 10.58%  |
| Micron Technology   | 106       | 9.58%   |
| Unknown             | 80        | 7.23%   |
| Crucial             | 59        | 5.33%   |
| G.Skill             | 34        | 3.07%   |
| Elpida              | 22        | 1.99%   |
| Ramaxel Technology  | 19        | 1.72%   |
| Nanya Technology    | 18        | 1.63%   |
| A-DATA Technology   | 11        | 0.99%   |
| Unknown (ABCD)      | 7         | 0.63%   |
| Unifosa             | 5         | 0.45%   |
| Unknown             | 5         | 0.45%   |
| Transcend           | 4         | 0.36%   |
| Timetec             | 2         | 0.18%   |
| Team                | 2         | 0.18%   |
| Patriot             | 2         | 0.18%   |
| GOODRAM             | 2         | 0.18%   |
| Unknown (0x8551)    | 1         | 0.09%   |
| Unknown (09D5)      | 1         | 0.09%   |
| TRS STAR            | 1         | 0.09%   |
| TakeMS              | 1         | 0.09%   |
| Qimonda             | 1         | 0.09%   |
| PNY                 | 1         | 0.09%   |
| OCZ                 | 1         | 0.09%   |
| J&A Information     | 1         | 0.09%   |
| GeIL                | 1         | 0.09%   |
| Corsair SerNum0     | 1         | 0.09%   |
| Aeneon              | 1         | 0.09%   |
| A-DA                | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.76%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 9         | 0.76%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.76%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 9         | 0.76%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 9         | 0.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.67%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.67%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 0.59%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.59%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.59%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 7         | 0.59%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s        | 7         | 0.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.5%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.5%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.5%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 6         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 5         | 0.42%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 5         | 0.42%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s                 | 5         | 0.42%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 5         | 0.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.42%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.42%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.42%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s              | 5         | 0.42%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 5         | 0.42%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 5         | 0.42%   |
| Unknown                                                          | 5         | 0.42%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 4         | 0.34%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 4         | 0.34%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.34%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 476       | 48.08%  |
| DDR3    | 328       | 33.13%  |
| DDR2    | 57        | 5.76%   |
| SDRAM   | 38        | 3.84%   |
| LPDDR3  | 28        | 2.83%   |
| LPDDR4  | 24        | 2.42%   |
| Unknown | 18        | 1.82%   |
| DDR5    | 11        | 1.11%   |
| LPDDR5  | 6         | 0.61%   |
| DDR     | 4         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 575       | 59.28%  |
| DIMM         | 326       | 33.61%  |
| Row Of Chips | 61        | 6.29%   |
| Chip         | 4         | 0.41%   |
| FB-DIMM      | 2         | 0.21%   |
| RIMM         | 1         | 0.1%    |
| Unknown      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 404       | 38.51%  |
| 4096  | 274       | 26.12%  |
| 16384 | 179       | 17.06%  |
| 2048  | 120       | 11.44%  |
| 1024  | 33        | 3.15%   |
| 32768 | 32        | 3.05%   |
| 512   | 6         | 0.57%   |
| 8     | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 214       | 20.11%  |
| 3200    | 171       | 16.07%  |
| 2667    | 144       | 13.53%  |
| 2400    | 82        | 7.71%   |
| 1333    | 70        | 6.58%   |
| 2133    | 59        | 5.55%   |
| 667     | 33        | 3.1%    |
| 1334    | 32        | 3.01%   |
| 3600    | 26        | 2.44%   |
| 800     | 22        | 2.07%   |
| 1867    | 16        | 1.5%    |
| Unknown | 15        | 1.41%   |
| 1067    | 14        | 1.32%   |
| 1800    | 12        | 1.13%   |
| 2048    | 11        | 1.03%   |
| 4267    | 10        | 0.94%   |
| 3400    | 10        | 0.94%   |
| 4800    | 9         | 0.85%   |
| 3533    | 9         | 0.85%   |
| 2666    | 9         | 0.85%   |
| 3866    | 8         | 0.75%   |
| 3266    | 8         | 0.75%   |
| 3000    | 7         | 0.66%   |
| 3534    | 6         | 0.56%   |
| 6400    | 5         | 0.47%   |
| 1066    | 5         | 0.47%   |
| 4199    | 4         | 0.38%   |
| 3666    | 4         | 0.38%   |
| 975     | 4         | 0.38%   |
| 533     | 4         | 0.38%   |
| 8400    | 3         | 0.28%   |
| 3800    | 3         | 0.28%   |
| 3733    | 3         | 0.28%   |
| 3100    | 3         | 0.28%   |
| 1866    | 3         | 0.28%   |
| 1639    | 3         | 0.28%   |
| 5200    | 2         | 0.19%   |
| 2933    | 2         | 0.19%   |
| 2800    | 2         | 0.19%   |
| 2000    | 2         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 22        | 42.31%  |
| Brother Industries  | 12        | 23.08%  |
| Canon               | 6         | 11.54%  |
| Seiko Epson         | 5         | 9.62%   |
| Samsung Electronics | 3         | 5.77%   |
| Ricoh               | 1         | 1.92%   |
| Prolific Technology | 1         | 1.92%   |
| Kyocera             | 1         | 1.92%   |
| Dymo-CoStar         | 1         | 1.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                                 | 2         | 3.77%   |
| Samsung ML-1660 Series                                     | 2         | 3.77%   |
| HP ENVY 4500 series                                        | 2         | 3.77%   |
| HP DeskJet 3630 series                                     | 2         | 3.77%   |
| Seiko Epson WF-3010 Series                                 | 1         | 1.89%   |
| Seiko Epson ET-8550 Series                                 | 1         | 1.89%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 1.89%   |
| Samsung SCX-472x Series                                    | 1         | 1.89%   |
| Ricoh SP C250SF                                            | 1         | 1.89%   |
| Prolific PL2305 Parallel Port                              | 1         | 1.89%   |
| Kyocera TASKalfa 250ci                                     | 1         | 1.89%   |
| HP OfficeJet Pro 6960                                      | 1         | 1.89%   |
| HP OfficeJet Pro 69                                        | 1         | 1.89%   |
| HP LaserJet Professional P 1102w                           | 1         | 1.89%   |
| HP LaserJet Pro M148f-M149f                                | 1         | 1.89%   |
| HP LaserJet P4015                                          | 1         | 1.89%   |
| HP LaserJet CM1415fn                                       | 1         | 1.89%   |
| HP LaserJet 3015                                           | 1         | 1.89%   |
| HP LaserJet 1015                                           | 1         | 1.89%   |
| HP EWS UPD                                                 | 1         | 1.89%   |
| HP ENVY Photo 6200 series                                  | 1         | 1.89%   |
| HP ENVY 5540 series                                        | 1         | 1.89%   |
| HP ENVY 4520 series                                        | 1         | 1.89%   |
| HP Deskjet F4500 series                                    | 1         | 1.89%   |
| HP DeskJet F300 series                                     | 1         | 1.89%   |
| HP DeskJet 5650c                                           | 1         | 1.89%   |
| HP DeskJet 5150c                                           | 1         | 1.89%   |
| HP DeskJet 3700 series                                     | 1         | 1.89%   |
| HP DeskJet 2620 All-in-One Printer                         | 1         | 1.89%   |
| Dymo-CoStar LabelWriter 450                                | 1         | 1.89%   |
| Canon TS5300 series                                        | 1         | 1.89%   |
| Canon TS5100 series                                        | 1         | 1.89%   |
| Canon PIXMA MX920 Series                                   | 1         | 1.89%   |
| Canon PIXMA MP240                                          | 1         | 1.89%   |
| Canon MG5700 series                                        | 1         | 1.89%   |
| Canon iP4900 series                                        | 1         | 1.89%   |
| Brother Printer                                            | 1         | 1.89%   |
| Brother MFC-L2710DW series                                 | 1         | 1.89%   |
| Brother MFC-J6530DW                                        | 1         | 1.89%   |
| Brother MFC-J5730DW                                        | 1         | 1.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 6         | 37.5%   |
| Seiko Epson     | 5         | 31.25%  |
| Canon           | 4         | 25%     |
| AGFA-Gevaert NV | 1         | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]        | 1         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1         | 6.25%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 6.25%   |
| Seiko Epson GT-F700 [Perfection V350]                   | 1         | 6.25%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 6.25%   |
| HP ScanJet G4010                                        | 1         | 6.25%   |
| HP scanjet 8270                                         | 1         | 6.25%   |
| HP ScanJet 4370                                         | 1         | 6.25%   |
| HP ScanJet 3800c                                        | 1         | 6.25%   |
| HP ScanJet 3670                                         | 1         | 6.25%   |
| HP ScanJet 3400cse                                      | 1         | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 6.25%   |
| Canon CanoScan LiDE 210                                 | 1         | 6.25%   |
| Canon CanoScan LiDE 110                                 | 1         | 6.25%   |
| Canon CanoScan 3200F                                    | 1         | 6.25%   |
| AGFA-Gevaert NV Snapscan e40                            | 1         | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 251       | 22.78%  |
| Microdia                               | 113       | 10.25%  |
| Realtek Semiconductor                  | 85        | 7.71%   |
| Logitech                               | 79        | 7.17%   |
| IMC Networks                           | 76        | 6.9%    |
| Sunplus Innovation Technology          | 51        | 4.63%   |
| Quanta                                 | 42        | 3.81%   |
| Suyin                                  | 40        | 3.63%   |
| Bison Electronics                      | 40        | 3.63%   |
| Acer                                   | 39        | 3.54%   |
| Cheng Uei Precision Industry (Foxlink) | 38        | 3.45%   |
| Lite-On Technology                     | 36        | 3.27%   |
| Apple                                  | 35        | 3.18%   |
| Syntek                                 | 33        | 2.99%   |
| Luxvisions Innotech Limited            | 16        | 1.45%   |
| Alcor Micro                            | 16        | 1.45%   |
| Ricoh                                  | 14        | 1.27%   |
| Samsung Electronics                    | 9         | 0.82%   |
| Silicon Motion                         | 6         | 0.54%   |
| Primax Electronics                     | 5         | 0.45%   |
| Lenovo                                 | 5         | 0.45%   |
| Microsoft                              | 4         | 0.36%   |
| Jieli Technology                       | 4         | 0.36%   |
| Importek                               | 4         | 0.36%   |
| Generalplus Technology                 | 4         | 0.36%   |
| Creative Technology                    | 4         | 0.36%   |
| Z-Star Microelectronics                | 3         | 0.27%   |
| WaveRider Communications               | 3         | 0.27%   |
| Trust                                  | 3         | 0.27%   |
| ALi                                    | 3         | 0.27%   |
| Sunplus Technology                     | 2         | 0.18%   |
| STEREOLABS                             | 2         | 0.18%   |
| Sonix Technology                       | 2         | 0.18%   |
| Pixart Imaging                         | 2         | 0.18%   |
| OPPO Electronics                       | 2         | 0.18%   |
| KYE Systems (Mouse Systems)            | 2         | 0.18%   |
| Hewlett-Packard                        | 2         | 0.18%   |
| GEMBIRD                                | 2         | 0.18%   |
| Dell                                   | 2         | 0.18%   |
| Valve Software                         | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD             | 38        | 3.42%   |
| Chicony Integrated Camera                | 37        | 3.33%   |
| Microdia Integrated_Webcam_HD            | 33        | 2.97%   |
| IMC Networks Integrated Camera           | 32        | 2.88%   |
| Syntek Integrated Camera                 | 22        | 1.98%   |
| Chicony HD WebCam                        | 19        | 1.71%   |
| Microdia Integrated Webcam               | 16        | 1.44%   |
| Quanta HP HD Camera                      | 15        | 1.35%   |
| Chicony USB2.0 Camera                    | 15        | 1.35%   |
| Acer Integrated Camera                   | 15        | 1.35%   |
| IMC Networks USB2.0 HD UVC WebCam        | 14        | 1.26%   |
| Logitech HD Webcam C525                  | 12        | 1.08%   |
| Chicony HP HD Webcam                     | 12        | 1.08%   |
| Sunplus HD WebCam                        | 11        | 0.99%   |
| Lite-On Integrated Camera                | 11        | 0.99%   |
| Lite-On HP HD Camera                     | 11        | 0.99%   |
| Chicony HP Wide Vision HD Camera         | 11        | 0.99%   |
| Chicony HP HD Camera                     | 11        | 0.99%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 11        | 0.99%   |
| Apple Built-in iSight                    | 10        | 0.9%    |
| Samsung Galaxy series, misc. (MTP mode)  | 9         | 0.81%   |
| Logitech Webcam C270                     | 9         | 0.81%   |
| Chicony USB2.0 HD UVC WebCam             | 9         | 0.81%   |
| Chicony EasyCamera                       | 9         | 0.81%   |
| Bison Integrated Camera                  | 9         | 0.81%   |
| Apple FaceTime HD Camera (Built-in)      | 9         | 0.81%   |
| Acer BisonCam,NB Pro                     | 9         | 0.81%   |
| Microdia USB 2.0 Camera                  | 8         | 0.72%   |
| Microdia Camera                          | 8         | 0.72%   |
| Logitech HD Pro Webcam C920              | 8         | 0.72%   |
| Chicony USB 2.0 Camera                   | 8         | 0.72%   |
| Chicony TOSHIBA Web Camera - HD          | 8         | 0.72%   |
| Chicony Integrated Camera (1280x720@30)  | 8         | 0.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 7         | 0.63%   |
| Realtek USB Camera                       | 7         | 0.63%   |
| Logitech C922 Pro Stream Webcam          | 7         | 0.63%   |
| Chicony Integrated HP HD Webcam          | 7         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD     | 6         | 0.54%   |
| Microdia Laptop_Integrated_Webcam_2M     | 6         | 0.54%   |
| Microdia Integrated_Webcam_FHD           | 6         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 91        | 38.56%  |
| Validity Sensors                   | 78        | 33.05%  |
| Shenzhen Goodix Technology         | 23        | 9.75%   |
| AuthenTec                          | 15        | 6.36%   |
| LighTuning Technology              | 9         | 3.81%   |
| Upek                               | 7         | 2.97%   |
| STMicroelectronics                 | 7         | 2.97%   |
| Elan Microelectronics              | 4         | 1.69%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.42%   |
| DigitalPersona                     | 1         | 0.42%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 11.02%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 11.02%  |
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 4.66%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 3.39%   |
| Synaptics WBDI                                                             | 8         | 3.39%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 3.39%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 3.39%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 3.39%   |
| Synaptics  WBDI                                                            | 7         | 2.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 2.97%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.97%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.97%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.54%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 2.54%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 2.54%   |
| Synaptics UWP WBDI                                                         | 6         | 2.54%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 2.54%   |
| Validity Sensors VFS491                                                    | 5         | 2.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.12%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.12%   |
| AuthenTec AES2810                                                          | 5         | 2.12%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.69%   |
| Synaptics WBDI Device                                                      | 4         | 1.69%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 1.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.27%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.27%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.27%   |
| AuthenTec AES1600                                                          | 3         | 1.27%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.85%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.85%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.85%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.85%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.85%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.42%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.42%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.42%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.42%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 64        | 32.99%  |
| Alcor Micro                       | 53        | 27.32%  |
| VASCO Data Security International | 21        | 10.82%  |
| Realtek Semiconductor             | 16        | 8.25%   |
| O2 Micro                          | 13        | 6.7%    |
| Lenovo                            | 10        | 5.15%   |
| Advanced Card Systems             | 5         | 2.58%   |
| OmniKey                           | 3         | 1.55%   |
| Upek                              | 2         | 1.03%   |
| Yubico.com                        | 1         | 0.52%   |
| SCM Microsystems                  | 1         | 0.52%   |
| Integrated Technology Express     | 1         | 0.52%   |
| Gemalto (was Gemplus)             | 1         | 0.52%   |
| Feitian Technologies              | 1         | 0.52%   |
| Clay Logic                        | 1         | 0.52%   |
| Cherry                            | 1         | 0.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 51        | 26.29%  |
| Broadcom 58200                                                               | 24        | 12.37%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 9.28%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 16        | 8.25%   |
| Broadcom 5880                                                                | 14        | 7.22%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 12        | 6.19%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 5.15%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 5.15%   |
| VASCO Data Security International DIGIPASS 870                               | 9         | 4.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 4.12%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 2.06%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.55%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.03%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.03%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.03%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.52%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.52%   |
| OmniKey CardMan 4321                                                         | 1         | 0.52%   |
| Integrated Technology Express SmartCard Reader                               | 1         | 0.52%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.52%   |
| Feitian Technologies SCR301                                                  | 1         | 0.52%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.52%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.52%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1191      | 64.52%  |
| 1     | 523       | 28.33%  |
| 2     | 103       | 5.58%   |
| 3     | 19        | 1.03%   |
| 4     | 6         | 0.33%   |
| 6     | 2         | 0.11%   |
| 8     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 231       | 29.69%  |
| Graphics card            | 157       | 20.18%  |
| Chipcard                 | 135       | 17.35%  |
| Net/wireless             | 66        | 8.48%   |
| Multimedia controller    | 43        | 5.53%   |
| Communication controller | 27        | 3.47%   |
| Camera                   | 20        | 2.57%   |
| Unassigned class         | 18        | 2.31%   |
| Bluetooth                | 17        | 2.19%   |
| Card reader              | 15        | 1.93%   |
| Sound                    | 12        | 1.54%   |
| Storage                  | 11        | 1.41%   |
| Net/ethernet             | 10        | 1.29%   |
| Network                  | 5         | 0.64%   |
| Flash memory             | 4         | 0.51%   |
| Modem                    | 3         | 0.39%   |
| Dvb card                 | 2         | 0.26%   |
| Storage/raid             | 1         | 0.13%   |
| Storage/ide              | 1         | 0.13%   |

