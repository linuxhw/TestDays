Pop!_OS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS/Desktop/README.md) and [notebooks](/Dist/Pop!_OS/Notebook/README.md).

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

Total: 15234

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | M4N72-E                     | Desktop     | [815b251540](https://linux-hardware.org/?probe=815b251540) | Feb 02, 2024 |
| HP            | Pavilion g6                 | Notebook    | [795109303b](https://linux-hardware.org/?probe=795109303b) | Feb 02, 2024 |
| Dell          | G7 7588                     | Notebook    | [fdc746ce61](https://linux-hardware.org/?probe=fdc746ce61) | Feb 02, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [6d6e6af46b](https://linux-hardware.org/?probe=6d6e6af46b) | Feb 02, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [77c29c5fe1](https://linux-hardware.org/?probe=77c29c5fe1) | Feb 01, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [f659cc07fc](https://linux-hardware.org/?probe=f659cc07fc) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [bb6dd71048](https://linux-hardware.org/?probe=bb6dd71048) | Feb 01, 2024 |
| HP            | Elite x2 1013 G3            | Tablet      | [bdf4429b2f](https://linux-hardware.org/?probe=bdf4429b2f) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [7adc6ac4b3](https://linux-hardware.org/?probe=7adc6ac4b3) | Feb 01, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e94976b6d9](https://linux-hardware.org/?probe=e94976b6d9) | Feb 01, 2024 |
| Samsung       | 750XFH                      | Notebook    | [47d573ccf5](https://linux-hardware.org/?probe=47d573ccf5) | Feb 01, 2024 |
| Dell          | 0V8WGR A00                  | Desktop     | [9762a633ab](https://linux-hardware.org/?probe=9762a633ab) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [4e6e527f34](https://linux-hardware.org/?probe=4e6e527f34) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [16a348ccd1](https://linux-hardware.org/?probe=16a348ccd1) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [fc52040fc1](https://linux-hardware.org/?probe=fc52040fc1) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [f833c48d57](https://linux-hardware.org/?probe=f833c48d57) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [bc7890c0fe](https://linux-hardware.org/?probe=bc7890c0fe) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [ef62bb8257](https://linux-hardware.org/?probe=ef62bb8257) | Feb 01, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | Desktop     | [a5425cfc63](https://linux-hardware.org/?probe=a5425cfc63) | Feb 01, 2024 |
| MSI           | B760 GAMING PLUS WIFI       | Desktop     | [67539ba367](https://linux-hardware.org/?probe=67539ba367) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [841cef0b98](https://linux-hardware.org/?probe=841cef0b98) | Feb 01, 2024 |
| HP            | Pavilion dv6                | Notebook    | [9d58677c2a](https://linux-hardware.org/?probe=9d58677c2a) | Feb 01, 2024 |
| ASUSTek       | X556UQK                     | Notebook    | [970dc5b87d](https://linux-hardware.org/?probe=970dc5b87d) | Jan 31, 2024 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [54beeb17dc](https://linux-hardware.org/?probe=54beeb17dc) | Jan 31, 2024 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [65272ffc77](https://linux-hardware.org/?probe=65272ffc77) | Jan 31, 2024 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [5dcee96cdb](https://linux-hardware.org/?probe=5dcee96cdb) | Jan 31, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5222452ba4](https://linux-hardware.org/?probe=5222452ba4) | Jan 30, 2024 |
| Hot Pepper... | HPPMC10                     | Notebook    | [1bfdadd09f](https://linux-hardware.org/?probe=1bfdadd09f) | Jan 30, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [454433be44](https://linux-hardware.org/?probe=454433be44) | Jan 30, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0b6e8d1e4b](https://linux-hardware.org/?probe=0b6e8d1e4b) | Jan 30, 2024 |
| Apple         | MacBook9,1                  | Notebook    | [e81979cbdf](https://linux-hardware.org/?probe=e81979cbdf) | Jan 29, 2024 |
| Alienware     | 07HV66 A01                  | Desktop     | [732d349380](https://linux-hardware.org/?probe=732d349380) | Jan 29, 2024 |
| HP            | ProBook 4540s               | Notebook    | [ba6e31a8d3](https://linux-hardware.org/?probe=ba6e31a8d3) | Jan 29, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [dda1c0dfa9](https://linux-hardware.org/?probe=dda1c0dfa9) | Jan 29, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0bba02c4c8](https://linux-hardware.org/?probe=0bba02c4c8) | Jan 29, 2024 |
| SZMZ          | X99-S3                      | Desktop     | [acf24ed760](https://linux-hardware.org/?probe=acf24ed760) | Jan 29, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [9fcbf2b096](https://linux-hardware.org/?probe=9fcbf2b096) | Jan 29, 2024 |
| MSI           | MS-B0961                    | All in one  | [5c66f68a0e](https://linux-hardware.org/?probe=5c66f68a0e) | Jan 29, 2024 |
| MSI           | MS-B0961                    | All in one  | [231209ac00](https://linux-hardware.org/?probe=231209ac00) | Jan 29, 2024 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [7eaf280c7a](https://linux-hardware.org/?probe=7eaf280c7a) | Jan 29, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4e6d22c388](https://linux-hardware.org/?probe=4e6d22c388) | Jan 28, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a7826ae1af](https://linux-hardware.org/?probe=a7826ae1af) | Jan 28, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f80e16d62d](https://linux-hardware.org/?probe=f80e16d62d) | Jan 28, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [c347f95f5e](https://linux-hardware.org/?probe=c347f95f5e) | Jan 28, 2024 |
| ASUSTek       | X541UJ                      | Notebook    | [14f153b6c9](https://linux-hardware.org/?probe=14f153b6c9) | Jan 28, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [d5f5ab4b3f](https://linux-hardware.org/?probe=d5f5ab4b3f) | Jan 27, 2024 |
| ASUSTek       | Z170-A                      | Desktop     | [0f1f062eda](https://linux-hardware.org/?probe=0f1f062eda) | Jan 27, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [077619fc48](https://linux-hardware.org/?probe=077619fc48) | Jan 27, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [f0ac1844ad](https://linux-hardware.org/?probe=f0ac1844ad) | Jan 27, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b1d979bcb3](https://linux-hardware.org/?probe=b1d979bcb3) | Jan 27, 2024 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [94257ca4de](https://linux-hardware.org/?probe=94257ca4de) | Jan 27, 2024 |
| Acer          | Aspire 6530G                | Notebook    | [cd71356945](https://linux-hardware.org/?probe=cd71356945) | Jan 26, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [91412d213a](https://linux-hardware.org/?probe=91412d213a) | Jan 26, 2024 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [1eb12a361c](https://linux-hardware.org/?probe=1eb12a361c) | Jan 26, 2024 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [1f2bb560a8](https://linux-hardware.org/?probe=1f2bb560a8) | Jan 26, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [afbea953be](https://linux-hardware.org/?probe=afbea953be) | Jan 26, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | Notebook    | [43bf0c55e8](https://linux-hardware.org/?probe=43bf0c55e8) | Jan 26, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [068df25275](https://linux-hardware.org/?probe=068df25275) | Jan 26, 2024 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [5be9da4fbd](https://linux-hardware.org/?probe=5be9da4fbd) | Jan 26, 2024 |
| Lenovo        | G460 0677                   | Notebook    | [d4624cb524](https://linux-hardware.org/?probe=d4624cb524) | Jan 26, 2024 |
| Huanan        | X99-8M-F V1.4               | Desktop     | [65388b76e1](https://linux-hardware.org/?probe=65388b76e1) | Jan 25, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [4b9ba374ee](https://linux-hardware.org/?probe=4b9ba374ee) | Jan 25, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [4cedf6ee3a](https://linux-hardware.org/?probe=4cedf6ee3a) | Jan 25, 2024 |
| Acer          | Aspire VX5-591G             | Notebook    | [3e5671c66a](https://linux-hardware.org/?probe=3e5671c66a) | Jan 24, 2024 |
| MSI           | P65 Creator 9SE             | Notebook    | [863ad9098e](https://linux-hardware.org/?probe=863ad9098e) | Jan 24, 2024 |
| Gigabyte      | X99-Gaming 5P               | Desktop     | [e306ef8710](https://linux-hardware.org/?probe=e306ef8710) | Jan 24, 2024 |
| HP            | ProBook 4530s               | Notebook    | [db169567f6](https://linux-hardware.org/?probe=db169567f6) | Jan 24, 2024 |
| Toshiba       | Satellite C55-C             | Notebook    | [3f59e64e0e](https://linux-hardware.org/?probe=3f59e64e0e) | Jan 24, 2024 |
| System76      | Oryx Pro                    | Notebook    | [cb490beb63](https://linux-hardware.org/?probe=cb490beb63) | Jan 24, 2024 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [8b3e1a6d31](https://linux-hardware.org/?probe=8b3e1a6d31) | Jan 24, 2024 |
| ASUSTek       | ROG Maximus Z690 HERO EV... | Desktop     | [340fdb1832](https://linux-hardware.org/?probe=340fdb1832) | Jan 24, 2024 |
| MSI           | H55M-E33                    | Desktop     | [2935476b48](https://linux-hardware.org/?probe=2935476b48) | Jan 23, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [d195c1f908](https://linux-hardware.org/?probe=d195c1f908) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3bc0546f62](https://linux-hardware.org/?probe=3bc0546f62) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [95692e9f04](https://linux-hardware.org/?probe=95692e9f04) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [5d754d0510](https://linux-hardware.org/?probe=5d754d0510) | Jan 23, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [2f77e5be01](https://linux-hardware.org/?probe=2f77e5be01) | Jan 22, 2024 |
| MSI           | B350M MORTAR                | Desktop     | [f728e7ad76](https://linux-hardware.org/?probe=f728e7ad76) | Jan 22, 2024 |
| Dell          | Inspiron 5490               | Notebook    | [e879f5dd00](https://linux-hardware.org/?probe=e879f5dd00) | Jan 22, 2024 |
| MOMENTPLUS    | MP90                        | Mini pc     | [44e57438d0](https://linux-hardware.org/?probe=44e57438d0) | Jan 22, 2024 |
| MOMENTPLUS    | MP90                        | Mini pc     | [fee086244e](https://linux-hardware.org/?probe=fee086244e) | Jan 22, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [5ac29b012d](https://linux-hardware.org/?probe=5ac29b012d) | Jan 22, 2024 |
| MOMENTPLUS    | MP90                        | Mini pc     | [35ef2ea38e](https://linux-hardware.org/?probe=35ef2ea38e) | Jan 22, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [ed9635f427](https://linux-hardware.org/?probe=ed9635f427) | Jan 22, 2024 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [dcb0ce6ffa](https://linux-hardware.org/?probe=dcb0ce6ffa) | Jan 22, 2024 |
| HP            | Notebook                    | Notebook    | [efbf2736f3](https://linux-hardware.org/?probe=efbf2736f3) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [d248b6e5a9](https://linux-hardware.org/?probe=d248b6e5a9) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [66cf4b0b5a](https://linux-hardware.org/?probe=66cf4b0b5a) | Jan 21, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [41a62ec1d4](https://linux-hardware.org/?probe=41a62ec1d4) | Jan 21, 2024 |
| Gigabyte      | B660 AORUS MASTER DDR4      | Desktop     | [d36c2b07fd](https://linux-hardware.org/?probe=d36c2b07fd) | Jan 20, 2024 |
| MSI           | PRO X670-P WIFI             | Desktop     | [a0637d4400](https://linux-hardware.org/?probe=a0637d4400) | Jan 20, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8f41b6b7f9](https://linux-hardware.org/?probe=8f41b6b7f9) | Jan 20, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [af503dbdd1](https://linux-hardware.org/?probe=af503dbdd1) | Jan 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [9fd92c9632](https://linux-hardware.org/?probe=9fd92c9632) | Jan 20, 2024 |
| ASUSTek       | H97M-E                      | Desktop     | [d6fe598f33](https://linux-hardware.org/?probe=d6fe598f33) | Jan 20, 2024 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [14acfc6be1](https://linux-hardware.org/?probe=14acfc6be1) | Jan 19, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [e9423fb2cd](https://linux-hardware.org/?probe=e9423fb2cd) | Jan 19, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [09fe6e6426](https://linux-hardware.org/?probe=09fe6e6426) | Jan 19, 2024 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [7e5eb5a38c](https://linux-hardware.org/?probe=7e5eb5a38c) | Jan 19, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [35c8f1855d](https://linux-hardware.org/?probe=35c8f1855d) | Jan 19, 2024 |
| Dell          | 0TTDMJ A00                  | Desktop     | [e5d9f41477](https://linux-hardware.org/?probe=e5d9f41477) | Jan 19, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e555a2c32c](https://linux-hardware.org/?probe=e555a2c32c) | Jan 19, 2024 |
| HP            | ENVY TS 15                  | Notebook    | [4d83b8cef9](https://linux-hardware.org/?probe=4d83b8cef9) | Jan 19, 2024 |
| ASUSTek       | N55SL                       | Notebook    | [a6c913a5e2](https://linux-hardware.org/?probe=a6c913a5e2) | Jan 19, 2024 |
| Dell          | Latitude 9420               | Convertible | [66e5db6523](https://linux-hardware.org/?probe=66e5db6523) | Jan 18, 2024 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | Notebook    | [9efd333805](https://linux-hardware.org/?probe=9efd333805) | Jan 18, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [06cced7a39](https://linux-hardware.org/?probe=06cced7a39) | Jan 18, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [8f90ab1bfb](https://linux-hardware.org/?probe=8f90ab1bfb) | Jan 18, 2024 |
| ASRock        | H670 PG Riptide             | Desktop     | [d1a75ad00a](https://linux-hardware.org/?probe=d1a75ad00a) | Jan 18, 2024 |
| Microsoft     | Surface Pro 9               | Tablet      | [97b9d61c1b](https://linux-hardware.org/?probe=97b9d61c1b) | Jan 18, 2024 |
| Microsoft     | Surface Pro 9               | Tablet      | [3da744b1f4](https://linux-hardware.org/?probe=3da744b1f4) | Jan 18, 2024 |
| Acer          | Swift SFX14-41G             | Notebook    | [612d6f9b0e](https://linux-hardware.org/?probe=612d6f9b0e) | Jan 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [048d450a50](https://linux-hardware.org/?probe=048d450a50) | Jan 17, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [42e7298c19](https://linux-hardware.org/?probe=42e7298c19) | Jan 17, 2024 |
| MSI           | PRO X670-P WIFI             | Desktop     | [3b62b0b588](https://linux-hardware.org/?probe=3b62b0b588) | Jan 17, 2024 |
| Dell          | Latitude 9420               | Convertible | [cb8166fe94](https://linux-hardware.org/?probe=cb8166fe94) | Jan 17, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | Notebook    | [1364b82d7c](https://linux-hardware.org/?probe=1364b82d7c) | Jan 17, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [0b16d083fa](https://linux-hardware.org/?probe=0b16d083fa) | Jan 17, 2024 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [8ba2ab423f](https://linux-hardware.org/?probe=8ba2ab423f) | Jan 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [dd442d6fef](https://linux-hardware.org/?probe=dd442d6fef) | Jan 17, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a5bd71f259](https://linux-hardware.org/?probe=a5bd71f259) | Jan 17, 2024 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [3cdf937732](https://linux-hardware.org/?probe=3cdf937732) | Jan 17, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [48399b3fc4](https://linux-hardware.org/?probe=48399b3fc4) | Jan 16, 2024 |
| Compaq        | 430                         | Notebook    | [a8dc50fedd](https://linux-hardware.org/?probe=a8dc50fedd) | Jan 16, 2024 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [be6d425c5a](https://linux-hardware.org/?probe=be6d425c5a) | Jan 16, 2024 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [58d64e6a70](https://linux-hardware.org/?probe=58d64e6a70) | Jan 16, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [adb9343764](https://linux-hardware.org/?probe=adb9343764) | Jan 16, 2024 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [cb4fc4f2da](https://linux-hardware.org/?probe=cb4fc4f2da) | Jan 16, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [8e26115f48](https://linux-hardware.org/?probe=8e26115f48) | Jan 16, 2024 |
| MSI           | Z68A-G43                    | Desktop     | [9ab9ae7952](https://linux-hardware.org/?probe=9ab9ae7952) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [d124634554](https://linux-hardware.org/?probe=d124634554) | Jan 15, 2024 |
| Acer          | Swift SF315-52G             | Notebook    | [b1df864ab5](https://linux-hardware.org/?probe=b1df864ab5) | Jan 15, 2024 |
| ASUSTek       | X550JK                      | Notebook    | [1e70a82b32](https://linux-hardware.org/?probe=1e70a82b32) | Jan 15, 2024 |
| System76      | Pangolin                    | Notebook    | [bb8766a339](https://linux-hardware.org/?probe=bb8766a339) | Jan 15, 2024 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [75e74c82af](https://linux-hardware.org/?probe=75e74c82af) | Jan 15, 2024 |
| Dell          | 0J8H4R A00                  | Desktop     | [ce34102531](https://linux-hardware.org/?probe=ce34102531) | Jan 15, 2024 |
| ASUSTek       | P8P67 LE                    | Desktop     | [8e77609cb6](https://linux-hardware.org/?probe=8e77609cb6) | Jan 14, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [fe987e391e](https://linux-hardware.org/?probe=fe987e391e) | Jan 14, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [6ede7a7cc8](https://linux-hardware.org/?probe=6ede7a7cc8) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [19467f2a4d](https://linux-hardware.org/?probe=19467f2a4d) | Jan 14, 2024 |
| Acer          | Aspire 5560                 | Notebook    | [fcc49083ec](https://linux-hardware.org/?probe=fcc49083ec) | Jan 14, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [08074470dd](https://linux-hardware.org/?probe=08074470dd) | Jan 13, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1b6a4a4985](https://linux-hardware.org/?probe=1b6a4a4985) | Jan 13, 2024 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [f1b5487574](https://linux-hardware.org/?probe=f1b5487574) | Jan 13, 2024 |
| Samsung       | 550XED                      | Notebook    | [a9cdc1201c](https://linux-hardware.org/?probe=a9cdc1201c) | Jan 13, 2024 |
| Gigabyte      | H610M H DDR4                | Desktop     | [7ad8786f92](https://linux-hardware.org/?probe=7ad8786f92) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [60f88b1f3f](https://linux-hardware.org/?probe=60f88b1f3f) | Jan 13, 2024 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [3d70c9ce2f](https://linux-hardware.org/?probe=3d70c9ce2f) | Jan 13, 2024 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [dbcc44707c](https://linux-hardware.org/?probe=dbcc44707c) | Jan 13, 2024 |
| Dell          | Inspiron 5447               | Notebook    | [12ec54ffaf](https://linux-hardware.org/?probe=12ec54ffaf) | Jan 12, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [e5e36f25f0](https://linux-hardware.org/?probe=e5e36f25f0) | Jan 12, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [50ff1c2eb6](https://linux-hardware.org/?probe=50ff1c2eb6) | Jan 12, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [5ff6a8a29a](https://linux-hardware.org/?probe=5ff6a8a29a) | Jan 12, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [ea8bf22b21](https://linux-hardware.org/?probe=ea8bf22b21) | Jan 12, 2024 |
| MSI           | MPG Z590 GAMING PLUS        | Desktop     | [b9fe694efb](https://linux-hardware.org/?probe=b9fe694efb) | Jan 12, 2024 |
| Lenovo        | ThinkPad X260 20F5S4A901    | Notebook    | [75e671c163](https://linux-hardware.org/?probe=75e671c163) | Jan 12, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [8b5a2519fa](https://linux-hardware.org/?probe=8b5a2519fa) | Jan 12, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6ac65457ae](https://linux-hardware.org/?probe=6ac65457ae) | Jan 11, 2024 |
| System76      | Adder WS                    | Notebook    | [94120ee028](https://linux-hardware.org/?probe=94120ee028) | Jan 11, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | Notebook    | [9066b38bfc](https://linux-hardware.org/?probe=9066b38bfc) | Jan 11, 2024 |
| Acer          | Swift SF314-54              | Notebook    | [c947abcab4](https://linux-hardware.org/?probe=c947abcab4) | Jan 11, 2024 |
| ASUSTek       | G73Jh                       | Notebook    | [9f34698cbf](https://linux-hardware.org/?probe=9f34698cbf) | Jan 11, 2024 |
| Dell          | Latitude E7240              | Notebook    | [5661525290](https://linux-hardware.org/?probe=5661525290) | Jan 11, 2024 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [5e75e6b11a](https://linux-hardware.org/?probe=5e75e6b11a) | Jan 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6462a9e611](https://linux-hardware.org/?probe=6462a9e611) | Jan 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [145f213442](https://linux-hardware.org/?probe=145f213442) | Jan 10, 2024 |
| ASUSTek       | N55SL                       | Notebook    | [b2c935edc3](https://linux-hardware.org/?probe=b2c935edc3) | Jan 10, 2024 |
| ASUSTek       | X550JK                      | Notebook    | [53f8040dbd](https://linux-hardware.org/?probe=53f8040dbd) | Jan 10, 2024 |
| Dell          | Precision 7510              | Notebook    | [8902e4fb7f](https://linux-hardware.org/?probe=8902e4fb7f) | Jan 10, 2024 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [4ec27cc26b](https://linux-hardware.org/?probe=4ec27cc26b) | Jan 10, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3002... | Notebook    | [374798f039](https://linux-hardware.org/?probe=374798f039) | Jan 09, 2024 |
| Unknown       | Unknown                     | Notebook    | [76fb94009e](https://linux-hardware.org/?probe=76fb94009e) | Jan 09, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [d4a9b3c259](https://linux-hardware.org/?probe=d4a9b3c259) | Jan 09, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [b85af627bb](https://linux-hardware.org/?probe=b85af627bb) | Jan 09, 2024 |
| Dell          | Precision 5480              | Notebook    | [17ef519eb9](https://linux-hardware.org/?probe=17ef519eb9) | Jan 09, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [8107ad3adc](https://linux-hardware.org/?probe=8107ad3adc) | Jan 09, 2024 |
| Gigabyte      | H610M S2H                   | Desktop     | [c2a2c8a049](https://linux-hardware.org/?probe=c2a2c8a049) | Jan 09, 2024 |
| Gigabyte      | H610M S2H                   | Desktop     | [8a7432cd09](https://linux-hardware.org/?probe=8a7432cd09) | Jan 09, 2024 |
| Dell          | Precision 5560              | Notebook    | [947f10a53a](https://linux-hardware.org/?probe=947f10a53a) | Jan 09, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [50ff3c4620](https://linux-hardware.org/?probe=50ff3c4620) | Jan 08, 2024 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [22a09bce1a](https://linux-hardware.org/?probe=22a09bce1a) | Jan 08, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [a0e28b82f1](https://linux-hardware.org/?probe=a0e28b82f1) | Jan 08, 2024 |
| MSI           | P65 Creator 9SE             | Notebook    | [33a2ceb954](https://linux-hardware.org/?probe=33a2ceb954) | Jan 08, 2024 |
| HP            | 8434 11                     | Desktop     | [3c7307cadb](https://linux-hardware.org/?probe=3c7307cadb) | Jan 08, 2024 |
| Dell          | Vostro 5402                 | Notebook    | [4c1d546ae0](https://linux-hardware.org/?probe=4c1d546ae0) | Jan 08, 2024 |
| Lenovo        | ThinkPad X220 4291RD2       | Notebook    | [dc1b40ea6f](https://linux-hardware.org/?probe=dc1b40ea6f) | Jan 08, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [1bd4e00b2a](https://linux-hardware.org/?probe=1bd4e00b2a) | Jan 08, 2024 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [f63753ff07](https://linux-hardware.org/?probe=f63753ff07) | Jan 08, 2024 |
| Lenovo        | IdeaPad 330S-15IKB D 81F... | Notebook    | [2068373a62](https://linux-hardware.org/?probe=2068373a62) | Jan 08, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e2b86aade4](https://linux-hardware.org/?probe=e2b86aade4) | Jan 07, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e9337be795](https://linux-hardware.org/?probe=e9337be795) | Jan 07, 2024 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [29104c358b](https://linux-hardware.org/?probe=29104c358b) | Jan 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [040fa6a049](https://linux-hardware.org/?probe=040fa6a049) | Jan 07, 2024 |
| HP            | EliteBook 850 G6            | Notebook    | [605ea399c5](https://linux-hardware.org/?probe=605ea399c5) | Jan 07, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [cdc7802fc3](https://linux-hardware.org/?probe=cdc7802fc3) | Jan 07, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [46148b3b7a](https://linux-hardware.org/?probe=46148b3b7a) | Jan 07, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [8363cb44ef](https://linux-hardware.org/?probe=8363cb44ef) | Jan 06, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [fcf858ac50](https://linux-hardware.org/?probe=fcf858ac50) | Jan 06, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [a10fc58132](https://linux-hardware.org/?probe=a10fc58132) | Jan 06, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [8ca8b318eb](https://linux-hardware.org/?probe=8ca8b318eb) | Jan 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [8f7440e4aa](https://linux-hardware.org/?probe=8f7440e4aa) | Jan 06, 2024 |
| Lenovo        | ThinkPad X390 20Q1S7RB00    | Notebook    | [cfcb27d0b7](https://linux-hardware.org/?probe=cfcb27d0b7) | Jan 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [ae18260ba9](https://linux-hardware.org/?probe=ae18260ba9) | Jan 06, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [b247cc09d2](https://linux-hardware.org/?probe=b247cc09d2) | Jan 06, 2024 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4572d32ab9](https://linux-hardware.org/?probe=4572d32ab9) | Jan 06, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [cae755fe43](https://linux-hardware.org/?probe=cae755fe43) | Jan 06, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [a620a3be8d](https://linux-hardware.org/?probe=a620a3be8d) | Jan 06, 2024 |
| Dell          | Latitude 3420               | Notebook    | [39d522ead5](https://linux-hardware.org/?probe=39d522ead5) | Jan 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [4c5cb3c1d4](https://linux-hardware.org/?probe=4c5cb3c1d4) | Jan 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [d135277737](https://linux-hardware.org/?probe=d135277737) | Jan 05, 2024 |
| HP            | 83E9                        | Notebook    | [5794eaa509](https://linux-hardware.org/?probe=5794eaa509) | Jan 05, 2024 |
| HP            | 83E9                        | Notebook    | [ca6565530d](https://linux-hardware.org/?probe=ca6565530d) | Jan 05, 2024 |
| MSI           | B560M PRO-E                 | Desktop     | [0fd8636acb](https://linux-hardware.org/?probe=0fd8636acb) | Jan 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [5e7209bd1a](https://linux-hardware.org/?probe=5e7209bd1a) | Jan 05, 2024 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [204ff304cf](https://linux-hardware.org/?probe=204ff304cf) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [18ebf2cf02](https://linux-hardware.org/?probe=18ebf2cf02) | Jan 04, 2024 |
| ASUSTek       | Z9PE-D8 WS                  | Server      | [ef860dc55b](https://linux-hardware.org/?probe=ef860dc55b) | Jan 04, 2024 |
| ASUSTek       | Z9PE-D8 WS                  | Server      | [2eb9de52ab](https://linux-hardware.org/?probe=2eb9de52ab) | Jan 04, 2024 |
| Gigabyte      | H81M-D2V                    | Desktop     | [1c7845bdee](https://linux-hardware.org/?probe=1c7845bdee) | Jan 04, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [41a278e922](https://linux-hardware.org/?probe=41a278e922) | Jan 04, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [4c587bc867](https://linux-hardware.org/?probe=4c587bc867) | Jan 04, 2024 |
| ASUSTek       | Z87-K                       | Desktop     | [4bd9034918](https://linux-hardware.org/?probe=4bd9034918) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [1973735eec](https://linux-hardware.org/?probe=1973735eec) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b1484cba42](https://linux-hardware.org/?probe=b1484cba42) | Jan 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [cb3946a0b0](https://linux-hardware.org/?probe=cb3946a0b0) | Jan 04, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [1593858ec2](https://linux-hardware.org/?probe=1593858ec2) | Jan 04, 2024 |
| Dell          | Latitude E5270              | Notebook    | [c0a4dbd80f](https://linux-hardware.org/?probe=c0a4dbd80f) | Jan 03, 2024 |
| Dell          | Vostro 3500                 | Notebook    | [70cf9e639e](https://linux-hardware.org/?probe=70cf9e639e) | Jan 03, 2024 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [0e5397d3f1](https://linux-hardware.org/?probe=0e5397d3f1) | Jan 03, 2024 |
| Microsoft     | Surface Go 3                | Tablet      | [1531aba226](https://linux-hardware.org/?probe=1531aba226) | Jan 03, 2024 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [cd96de915f](https://linux-hardware.org/?probe=cd96de915f) | Jan 03, 2024 |
| Acidanther... | Mac-F221DCC8                | All in one  | [3cd35cddda](https://linux-hardware.org/?probe=3cd35cddda) | Jan 03, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [d29c58fd8a](https://linux-hardware.org/?probe=d29c58fd8a) | Jan 03, 2024 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [95995dd66f](https://linux-hardware.org/?probe=95995dd66f) | Jan 03, 2024 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [8fe843e69b](https://linux-hardware.org/?probe=8fe843e69b) | Jan 02, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8bb04983f7](https://linux-hardware.org/?probe=8bb04983f7) | Jan 02, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [e80580f306](https://linux-hardware.org/?probe=e80580f306) | Jan 02, 2024 |
| ASUSTek       | Z87-K                       | Desktop     | [3f1ffd98e9](https://linux-hardware.org/?probe=3f1ffd98e9) | Jan 02, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [09d807a864](https://linux-hardware.org/?probe=09d807a864) | Jan 02, 2024 |
| Acer          | SF314-71-50E8               | Notebook    | [b74d7acff4](https://linux-hardware.org/?probe=b74d7acff4) | Jan 02, 2024 |
| ASUSTek       | G75VX                       | Notebook    | [7f8494ffcf](https://linux-hardware.org/?probe=7f8494ffcf) | Jan 02, 2024 |
| Dell          | Latitude 5540               | Notebook    | [96e1aad010](https://linux-hardware.org/?probe=96e1aad010) | Jan 02, 2024 |
| System76      | Oryx Pro                    | Notebook    | [07e4e6a0a8](https://linux-hardware.org/?probe=07e4e6a0a8) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [14df5ebb53](https://linux-hardware.org/?probe=14df5ebb53) | Jan 02, 2024 |
| Unknown       | X99H                        | Desktop     | [61c57cb006](https://linux-hardware.org/?probe=61c57cb006) | Jan 01, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [00ee13cdb6](https://linux-hardware.org/?probe=00ee13cdb6) | Jan 01, 2024 |
| ASUSTek       | P6T                         | Desktop     | [7b5a14566d](https://linux-hardware.org/?probe=7b5a14566d) | Jan 01, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [58557ae7c7](https://linux-hardware.org/?probe=58557ae7c7) | Jan 01, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [9181cf5581](https://linux-hardware.org/?probe=9181cf5581) | Jan 01, 2024 |
| MSI           | P65 Creator 9SE             | Notebook    | [2e5c1a6b06](https://linux-hardware.org/?probe=2e5c1a6b06) | Jan 01, 2024 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [eb47ce9900](https://linux-hardware.org/?probe=eb47ce9900) | Jan 01, 2024 |
| ASUSTek       | M4N72-E                     | Desktop     | [7d21517ee3](https://linux-hardware.org/?probe=7d21517ee3) | Dec 31, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [fa478c5226](https://linux-hardware.org/?probe=fa478c5226) | Dec 31, 2023 |
| Lenovo        | ThinkPad P50 20EQS3YS00     | Notebook    | [34294e5b8b](https://linux-hardware.org/?probe=34294e5b8b) | Dec 31, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [386449d6f7](https://linux-hardware.org/?probe=386449d6f7) | Dec 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [9872ef6241](https://linux-hardware.org/?probe=9872ef6241) | Dec 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [527544c2de](https://linux-hardware.org/?probe=527544c2de) | Dec 31, 2023 |
| Google        | Delbin                      | Notebook    | [51a51a978d](https://linux-hardware.org/?probe=51a51a978d) | Dec 31, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [63fd2a4477](https://linux-hardware.org/?probe=63fd2a4477) | Dec 31, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [ff5e2959f8](https://linux-hardware.org/?probe=ff5e2959f8) | Dec 31, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [faf34bf75f](https://linux-hardware.org/?probe=faf34bf75f) | Dec 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [b94c50cb10](https://linux-hardware.org/?probe=b94c50cb10) | Dec 30, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [a0039ef79d](https://linux-hardware.org/?probe=a0039ef79d) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [f48ada0e7b](https://linux-hardware.org/?probe=f48ada0e7b) | Dec 30, 2023 |
| Metabox       | Alpha-X NH58HP              | Notebook    | [983844e1c8](https://linux-hardware.org/?probe=983844e1c8) | Dec 30, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [b1b1057a4b](https://linux-hardware.org/?probe=b1b1057a4b) | Dec 30, 2023 |
| Acer          | SF314-71-50E8               | Notebook    | [a2704f17ea](https://linux-hardware.org/?probe=a2704f17ea) | Dec 29, 2023 |
| HP            | 802E                        | Desktop     | [a519d89c9e](https://linux-hardware.org/?probe=a519d89c9e) | Dec 29, 2023 |
| MSI           | MEG X570S ACE MAX           | Desktop     | [e0e92720cb](https://linux-hardware.org/?probe=e0e92720cb) | Dec 29, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [bbe4e7af60](https://linux-hardware.org/?probe=bbe4e7af60) | Dec 29, 2023 |
| Lenovo        | B490 37722KP                | Notebook    | [194971e987](https://linux-hardware.org/?probe=194971e987) | Dec 29, 2023 |
| Lenovo        | ThinkPad L590 20Q8S0QB00    | Notebook    | [21c14a621b](https://linux-hardware.org/?probe=21c14a621b) | Dec 29, 2023 |
| ASUSTek       | G73Jh                       | Notebook    | [05dc836501](https://linux-hardware.org/?probe=05dc836501) | Dec 28, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [a91c55ef9f](https://linux-hardware.org/?probe=a91c55ef9f) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [94b90795bb](https://linux-hardware.org/?probe=94b90795bb) | Dec 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [2e6989112a](https://linux-hardware.org/?probe=2e6989112a) | Dec 28, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | Notebook    | [0f8be1187e](https://linux-hardware.org/?probe=0f8be1187e) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a5c652bcef](https://linux-hardware.org/?probe=a5c652bcef) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [02799d9fc9](https://linux-hardware.org/?probe=02799d9fc9) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2d2449e5d7](https://linux-hardware.org/?probe=2d2449e5d7) | Dec 28, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [f52a281bd2](https://linux-hardware.org/?probe=f52a281bd2) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [341b25443b](https://linux-hardware.org/?probe=341b25443b) | Dec 28, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [42460d0cd3](https://linux-hardware.org/?probe=42460d0cd3) | Dec 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [61116b6285](https://linux-hardware.org/?probe=61116b6285) | Dec 27, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [0927068d89](https://linux-hardware.org/?probe=0927068d89) | Dec 27, 2023 |
| ASUSTek       | K75VM                       | Notebook    | [4f1fddffba](https://linux-hardware.org/?probe=4f1fddffba) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [72e733aa23](https://linux-hardware.org/?probe=72e733aa23) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [f7d4fcd885](https://linux-hardware.org/?probe=f7d4fcd885) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | Notebook    | [865ecc4a8b](https://linux-hardware.org/?probe=865ecc4a8b) | Dec 27, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [8017d1c054](https://linux-hardware.org/?probe=8017d1c054) | Dec 27, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [77d5e43585](https://linux-hardware.org/?probe=77d5e43585) | Dec 26, 2023 |
| SZMZ          | X99-S3                      | Desktop     | [85c9abf0f3](https://linux-hardware.org/?probe=85c9abf0f3) | Dec 26, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [db50c73272](https://linux-hardware.org/?probe=db50c73272) | Dec 26, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [e63c96ff95](https://linux-hardware.org/?probe=e63c96ff95) | Dec 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [34060a7062](https://linux-hardware.org/?probe=34060a7062) | Dec 26, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [96aa7493e0](https://linux-hardware.org/?probe=96aa7493e0) | Dec 25, 2023 |
| Dell          | Latitude E6520              | Notebook    | [634e14ff4c](https://linux-hardware.org/?probe=634e14ff4c) | Dec 25, 2023 |
| MicroByte     | ezbook                      | Notebook    | [a03eec4fc7](https://linux-hardware.org/?probe=a03eec4fc7) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [f385a26e94](https://linux-hardware.org/?probe=f385a26e94) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [744adae48d](https://linux-hardware.org/?probe=744adae48d) | Dec 25, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1f14807c5e](https://linux-hardware.org/?probe=1f14807c5e) | Dec 25, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [325376d316](https://linux-hardware.org/?probe=325376d316) | Dec 25, 2023 |
| Lenovo        | ThinkPad T540p 20BFS0620... | Notebook    | [5cceadde0c](https://linux-hardware.org/?probe=5cceadde0c) | Dec 25, 2023 |
| PC Special... | N150CU                      | Notebook    | [5697f18262](https://linux-hardware.org/?probe=5697f18262) | Dec 24, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [f9cf1edcee](https://linux-hardware.org/?probe=f9cf1edcee) | Dec 24, 2023 |
| PC Special... | GK7NP5R                     | Notebook    | [1d97edcad7](https://linux-hardware.org/?probe=1d97edcad7) | Dec 23, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8decde512f](https://linux-hardware.org/?probe=8decde512f) | Dec 23, 2023 |
| System76      | Serval WS                   | Notebook    | [92d124a8aa](https://linux-hardware.org/?probe=92d124a8aa) | Dec 23, 2023 |
| System76      | Gazelle                     | Notebook    | [6671df79bd](https://linux-hardware.org/?probe=6671df79bd) | Dec 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [f5f4795192](https://linux-hardware.org/?probe=f5f4795192) | Dec 22, 2023 |
| Gigabyte      | H87M-HD3                    | Desktop     | [00781519db](https://linux-hardware.org/?probe=00781519db) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [de502eec48](https://linux-hardware.org/?probe=de502eec48) | Dec 22, 2023 |
| Alienware     | 0K9TKY A00                  | Desktop     | [ec6847b7f2](https://linux-hardware.org/?probe=ec6847b7f2) | Dec 22, 2023 |
| Gigabyte      | H610M S2H                   | Desktop     | [6c554a9668](https://linux-hardware.org/?probe=6c554a9668) | Dec 22, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [bf0861748d](https://linux-hardware.org/?probe=bf0861748d) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9515cb0c90](https://linux-hardware.org/?probe=9515cb0c90) | Dec 22, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [b49d16daf5](https://linux-hardware.org/?probe=b49d16daf5) | Dec 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1b8100314e](https://linux-hardware.org/?probe=1b8100314e) | Dec 21, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [2b580a7725](https://linux-hardware.org/?probe=2b580a7725) | Dec 21, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [ecefa48588](https://linux-hardware.org/?probe=ecefa48588) | Dec 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [1e223a9ea1](https://linux-hardware.org/?probe=1e223a9ea1) | Dec 21, 2023 |
| DEXP          | Atlas M15-I3W302            | Notebook    | [176dd6f77a](https://linux-hardware.org/?probe=176dd6f77a) | Dec 20, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [67098aebca](https://linux-hardware.org/?probe=67098aebca) | Dec 20, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9a3cef62bc](https://linux-hardware.org/?probe=9a3cef62bc) | Dec 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ff06842733](https://linux-hardware.org/?probe=ff06842733) | Dec 20, 2023 |
| Dell          | Precision 5680              | Notebook    | [b8b5bc0292](https://linux-hardware.org/?probe=b8b5bc0292) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [00b16e835d](https://linux-hardware.org/?probe=00b16e835d) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [0b6e9c4c26](https://linux-hardware.org/?probe=0b6e9c4c26) | Dec 20, 2023 |
| ASUSTek       | Maximus VIII EXTREME        | Desktop     | [d2ed93003e](https://linux-hardware.org/?probe=d2ed93003e) | Dec 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [24ff90d774](https://linux-hardware.org/?probe=24ff90d774) | Dec 20, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [5eca78aa43](https://linux-hardware.org/?probe=5eca78aa43) | Dec 19, 2023 |
| Dell          | Latitude E5270              | Notebook    | [c25a5b1bc7](https://linux-hardware.org/?probe=c25a5b1bc7) | Dec 19, 2023 |
| System76      | Pangolin                    | Notebook    | [a0cf57c6d1](https://linux-hardware.org/?probe=a0cf57c6d1) | Dec 19, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [86b686b3cf](https://linux-hardware.org/?probe=86b686b3cf) | Dec 19, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [047feb8e76](https://linux-hardware.org/?probe=047feb8e76) | Dec 19, 2023 |
| Biostar       | A320MH                      | Desktop     | [9ec714a02b](https://linux-hardware.org/?probe=9ec714a02b) | Dec 19, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [b10cd89445](https://linux-hardware.org/?probe=b10cd89445) | Dec 19, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [29169b6700](https://linux-hardware.org/?probe=29169b6700) | Dec 19, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [1375b869d1](https://linux-hardware.org/?probe=1375b869d1) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [0759f6c04f](https://linux-hardware.org/?probe=0759f6c04f) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [939c3a4be6](https://linux-hardware.org/?probe=939c3a4be6) | Dec 19, 2023 |
| Gigabyte      | Z590I VISION D              | Desktop     | [92531d60e9](https://linux-hardware.org/?probe=92531d60e9) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [8efe53adcb](https://linux-hardware.org/?probe=8efe53adcb) | Dec 18, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [f051e1ba58](https://linux-hardware.org/?probe=f051e1ba58) | Dec 18, 2023 |
| Gigabyte      | Z270N-WIFI-CF               | Desktop     | [2e837d2a52](https://linux-hardware.org/?probe=2e837d2a52) | Dec 18, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [85358f7505](https://linux-hardware.org/?probe=85358f7505) | Dec 18, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [e7ed0c7c8a](https://linux-hardware.org/?probe=e7ed0c7c8a) | Dec 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [825b7230bc](https://linux-hardware.org/?probe=825b7230bc) | Dec 18, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [3c5fc22ea0](https://linux-hardware.org/?probe=3c5fc22ea0) | Dec 17, 2023 |
| ASUSTek       | Maximus VIII EXTREME        | Desktop     | [2d78f7257c](https://linux-hardware.org/?probe=2d78f7257c) | Dec 17, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [f8cfc75a8a](https://linux-hardware.org/?probe=f8cfc75a8a) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [6e359357d4](https://linux-hardware.org/?probe=6e359357d4) | Dec 17, 2023 |
| HP            | ProBook 4535s               | Notebook    | [80aa5bd12b](https://linux-hardware.org/?probe=80aa5bd12b) | Dec 17, 2023 |
| Dell          | Latitude E7450              | Notebook    | [f429af38c1](https://linux-hardware.org/?probe=f429af38c1) | Dec 17, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [3a10e23529](https://linux-hardware.org/?probe=3a10e23529) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [801f62b573](https://linux-hardware.org/?probe=801f62b573) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [d16bd87505](https://linux-hardware.org/?probe=d16bd87505) | Dec 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [7f32922e8f](https://linux-hardware.org/?probe=7f32922e8f) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [b9029b0475](https://linux-hardware.org/?probe=b9029b0475) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0baa198f9f](https://linux-hardware.org/?probe=0baa198f9f) | Dec 17, 2023 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | Desktop     | [47bc0a39bf](https://linux-hardware.org/?probe=47bc0a39bf) | Dec 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [b90524a691](https://linux-hardware.org/?probe=b90524a691) | Dec 16, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [ef0c78ce49](https://linux-hardware.org/?probe=ef0c78ce49) | Dec 16, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [c35aa056cf](https://linux-hardware.org/?probe=c35aa056cf) | Dec 16, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d227968843](https://linux-hardware.org/?probe=d227968843) | Dec 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [95deb85c40](https://linux-hardware.org/?probe=95deb85c40) | Dec 16, 2023 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [8717000b31](https://linux-hardware.org/?probe=8717000b31) | Dec 16, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [4f6031c3b2](https://linux-hardware.org/?probe=4f6031c3b2) | Dec 16, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [51a1a58859](https://linux-hardware.org/?probe=51a1a58859) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [976a5e3ec2](https://linux-hardware.org/?probe=976a5e3ec2) | Dec 16, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [7da400b028](https://linux-hardware.org/?probe=7da400b028) | Dec 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [10f1017f04](https://linux-hardware.org/?probe=10f1017f04) | Dec 16, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [c5e74761c7](https://linux-hardware.org/?probe=c5e74761c7) | Dec 15, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [cee2ad1e7c](https://linux-hardware.org/?probe=cee2ad1e7c) | Dec 15, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [fb32a1a82e](https://linux-hardware.org/?probe=fb32a1a82e) | Dec 15, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [09d89c7989](https://linux-hardware.org/?probe=09d89c7989) | Dec 15, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [17fcc16842](https://linux-hardware.org/?probe=17fcc16842) | Dec 14, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [9d6455339e](https://linux-hardware.org/?probe=9d6455339e) | Dec 14, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3280eaaea1](https://linux-hardware.org/?probe=3280eaaea1) | Dec 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4919d10355](https://linux-hardware.org/?probe=4919d10355) | Dec 14, 2023 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [b7bef0ec08](https://linux-hardware.org/?probe=b7bef0ec08) | Dec 14, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [c132a249e4](https://linux-hardware.org/?probe=c132a249e4) | Dec 13, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [913708c3f0](https://linux-hardware.org/?probe=913708c3f0) | Dec 13, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3f2ed65cf0](https://linux-hardware.org/?probe=3f2ed65cf0) | Dec 13, 2023 |
| Samsung       | 300E5E/300E4E/300E5V/300... | Notebook    | [e7d5f85bea](https://linux-hardware.org/?probe=e7d5f85bea) | Dec 13, 2023 |
| Gigabyte      | Q87M-MK                     | Desktop     | [25a03e3488](https://linux-hardware.org/?probe=25a03e3488) | Dec 13, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [5a796a43bd](https://linux-hardware.org/?probe=5a796a43bd) | Dec 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e33caa2659](https://linux-hardware.org/?probe=e33caa2659) | Dec 12, 2023 |
| AZW           | SER                         | Mini pc     | [35001d9cec](https://linux-hardware.org/?probe=35001d9cec) | Dec 12, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ca9ceaf4a0](https://linux-hardware.org/?probe=ca9ceaf4a0) | Dec 11, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [076e19b0aa](https://linux-hardware.org/?probe=076e19b0aa) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [efba53721c](https://linux-hardware.org/?probe=efba53721c) | Dec 11, 2023 |
| MSI           | H610M BOMBER DDR4           | Desktop     | [7ea9e34c4c](https://linux-hardware.org/?probe=7ea9e34c4c) | Dec 11, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [7b2a48d751](https://linux-hardware.org/?probe=7b2a48d751) | Dec 11, 2023 |
| MSI           | NIGHTBLADE Z97              | Desktop     | [90fce6c777](https://linux-hardware.org/?probe=90fce6c777) | Dec 11, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [18df358540](https://linux-hardware.org/?probe=18df358540) | Dec 11, 2023 |
| MSI           | NIGHTBLADE Z97              | Desktop     | [6c83c2bec6](https://linux-hardware.org/?probe=6c83c2bec6) | Dec 11, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [539d1d09fe](https://linux-hardware.org/?probe=539d1d09fe) | Dec 11, 2023 |
| System76      | Lemur Pro                   | Notebook    | [05062ae2dd](https://linux-hardware.org/?probe=05062ae2dd) | Dec 10, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [0c0de57a07](https://linux-hardware.org/?probe=0c0de57a07) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | Notebook    | [832dd09409](https://linux-hardware.org/?probe=832dd09409) | Dec 10, 2023 |
| MSI           | GT72VR 6RD                  | Notebook    | [b17b809ccf](https://linux-hardware.org/?probe=b17b809ccf) | Dec 10, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [ad9ec5bc5b](https://linux-hardware.org/?probe=ad9ec5bc5b) | Dec 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [1adc377142](https://linux-hardware.org/?probe=1adc377142) | Dec 10, 2023 |
| HP            | 2AF7                        | Desktop     | [e7a6fd7a82](https://linux-hardware.org/?probe=e7a6fd7a82) | Dec 10, 2023 |
| ASUSTek       | X542URR                     | Notebook    | [3e42bedcd3](https://linux-hardware.org/?probe=3e42bedcd3) | Dec 10, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [ef47cf6d30](https://linux-hardware.org/?probe=ef47cf6d30) | Dec 10, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [06e9cf1c8d](https://linux-hardware.org/?probe=06e9cf1c8d) | Dec 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296e90c442](https://linux-hardware.org/?probe=296e90c442) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [cea0431bcb](https://linux-hardware.org/?probe=cea0431bcb) | Dec 09, 2023 |
| Razer         | Blade                       | Notebook    | [bf9ad5f7df](https://linux-hardware.org/?probe=bf9ad5f7df) | Dec 09, 2023 |
| Gigabyte      | MU92-TU0-00 01010101        | Server      | [fa219aabb0](https://linux-hardware.org/?probe=fa219aabb0) | Dec 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [f499be5e26](https://linux-hardware.org/?probe=f499be5e26) | Dec 09, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [e7d15edec4](https://linux-hardware.org/?probe=e7d15edec4) | Dec 09, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [981334c448](https://linux-hardware.org/?probe=981334c448) | Dec 08, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [6d01f19f82](https://linux-hardware.org/?probe=6d01f19f82) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [944218c6ec](https://linux-hardware.org/?probe=944218c6ec) | Dec 08, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [8c7f7f9b91](https://linux-hardware.org/?probe=8c7f7f9b91) | Dec 08, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [0ee42c0440](https://linux-hardware.org/?probe=0ee42c0440) | Dec 08, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [2499101d89](https://linux-hardware.org/?probe=2499101d89) | Dec 08, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [182fbc1464](https://linux-hardware.org/?probe=182fbc1464) | Dec 08, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [68bd979ae6](https://linux-hardware.org/?probe=68bd979ae6) | Dec 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | Notebook    | [87477ed836](https://linux-hardware.org/?probe=87477ed836) | Dec 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [13080ba71b](https://linux-hardware.org/?probe=13080ba71b) | Dec 07, 2023 |
| ASRock        | B450M/ac                    | Desktop     | [895b027832](https://linux-hardware.org/?probe=895b027832) | Dec 07, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [18c7fcf897](https://linux-hardware.org/?probe=18c7fcf897) | Dec 06, 2023 |
| MSI           | B550M PRO-VDH               | Desktop     | [49e317cfc8](https://linux-hardware.org/?probe=49e317cfc8) | Dec 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [0d809d54ad](https://linux-hardware.org/?probe=0d809d54ad) | Dec 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eeb3db62db](https://linux-hardware.org/?probe=eeb3db62db) | Dec 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5160cc41b9](https://linux-hardware.org/?probe=5160cc41b9) | Dec 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [be8fd86ad0](https://linux-hardware.org/?probe=be8fd86ad0) | Dec 05, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [4ae43e0af1](https://linux-hardware.org/?probe=4ae43e0af1) | Dec 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [973530edc6](https://linux-hardware.org/?probe=973530edc6) | Dec 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [67d1badc93](https://linux-hardware.org/?probe=67d1badc93) | Dec 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [1f66aaf874](https://linux-hardware.org/?probe=1f66aaf874) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | Notebook    | [419da197bb](https://linux-hardware.org/?probe=419da197bb) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | Notebook    | [745d537d97](https://linux-hardware.org/?probe=745d537d97) | Dec 05, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [474cae9549](https://linux-hardware.org/?probe=474cae9549) | Dec 05, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [48a8d668d9](https://linux-hardware.org/?probe=48a8d668d9) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2ace6b74e5](https://linux-hardware.org/?probe=2ace6b74e5) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [b3bc756e27](https://linux-hardware.org/?probe=b3bc756e27) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [9af224bc40](https://linux-hardware.org/?probe=9af224bc40) | Dec 04, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [b55a2ed6be](https://linux-hardware.org/?probe=b55a2ed6be) | Dec 03, 2023 |
| Acer          | Aspire A515-44G             | Notebook    | [7e41d52591](https://linux-hardware.org/?probe=7e41d52591) | Dec 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a63677b9e1](https://linux-hardware.org/?probe=a63677b9e1) | Dec 03, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c5bdb91907](https://linux-hardware.org/?probe=c5bdb91907) | Dec 03, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [1b6b67ba62](https://linux-hardware.org/?probe=1b6b67ba62) | Dec 03, 2023 |
| Gigabyte      | H81M-D2W                    | Desktop     | [98567fb8e0](https://linux-hardware.org/?probe=98567fb8e0) | Dec 03, 2023 |
| Gigabyte      | H81M-D2W                    | Desktop     | [00da9d31bd](https://linux-hardware.org/?probe=00da9d31bd) | Dec 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c7a7d555a6](https://linux-hardware.org/?probe=c7a7d555a6) | Dec 02, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [69c3f996db](https://linux-hardware.org/?probe=69c3f996db) | Dec 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [5568b58564](https://linux-hardware.org/?probe=5568b58564) | Dec 02, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [0714d912db](https://linux-hardware.org/?probe=0714d912db) | Dec 02, 2023 |
| Dell          | Latitude E7240              | Notebook    | [e5ac912c4c](https://linux-hardware.org/?probe=e5ac912c4c) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | Desktop     | [7488b95d21](https://linux-hardware.org/?probe=7488b95d21) | Dec 02, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [31ac2917e3](https://linux-hardware.org/?probe=31ac2917e3) | Dec 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [92a2b35bc8](https://linux-hardware.org/?probe=92a2b35bc8) | Dec 01, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [eb3b0a6afb](https://linux-hardware.org/?probe=eb3b0a6afb) | Dec 01, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [613d0fb4a0](https://linux-hardware.org/?probe=613d0fb4a0) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [53bc6eba90](https://linux-hardware.org/?probe=53bc6eba90) | Dec 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [ea481bfb9d](https://linux-hardware.org/?probe=ea481bfb9d) | Dec 01, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [b431f0a398](https://linux-hardware.org/?probe=b431f0a398) | Dec 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [863d4d2b8f](https://linux-hardware.org/?probe=863d4d2b8f) | Nov 30, 2023 |
| ASUSTek       | Zenbook UX6404VI_UX6404V... | Notebook    | [e52dad2488](https://linux-hardware.org/?probe=e52dad2488) | Nov 30, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [11e0af1d39](https://linux-hardware.org/?probe=11e0af1d39) | Nov 30, 2023 |
| HP            | 8299                        | Desktop     | [7d01726c17](https://linux-hardware.org/?probe=7d01726c17) | Nov 30, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [d91455d676](https://linux-hardware.org/?probe=d91455d676) | Nov 30, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e43b293d0e](https://linux-hardware.org/?probe=e43b293d0e) | Nov 30, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [43e0c71549](https://linux-hardware.org/?probe=43e0c71549) | Nov 30, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [707797695c](https://linux-hardware.org/?probe=707797695c) | Nov 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [21a183f050](https://linux-hardware.org/?probe=21a183f050) | Nov 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a05b28f5b1](https://linux-hardware.org/?probe=a05b28f5b1) | Nov 29, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [2f5a407d09](https://linux-hardware.org/?probe=2f5a407d09) | Nov 29, 2023 |
| HP            | 0B40h                       | Desktop     | [9875f70785](https://linux-hardware.org/?probe=9875f70785) | Nov 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [56ad64e87a](https://linux-hardware.org/?probe=56ad64e87a) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [977a25b18b](https://linux-hardware.org/?probe=977a25b18b) | Nov 29, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [07dd4aaf53](https://linux-hardware.org/?probe=07dd4aaf53) | Nov 29, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [a193c9a207](https://linux-hardware.org/?probe=a193c9a207) | Nov 29, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | Notebook    | [f7d5f758c6](https://linux-hardware.org/?probe=f7d5f758c6) | Nov 29, 2023 |
| Dell          | Precision 3550              | Notebook    | [935b0dba56](https://linux-hardware.org/?probe=935b0dba56) | Nov 28, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [f502294656](https://linux-hardware.org/?probe=f502294656) | Nov 28, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [1f793dc2d3](https://linux-hardware.org/?probe=1f793dc2d3) | Nov 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [3531e02313](https://linux-hardware.org/?probe=3531e02313) | Nov 27, 2023 |
| Dell          | Precision M4700             | Notebook    | [e63ddd94ec](https://linux-hardware.org/?probe=e63ddd94ec) | Nov 27, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [abbb97fea2](https://linux-hardware.org/?probe=abbb97fea2) | Nov 27, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [0bc55c4101](https://linux-hardware.org/?probe=0bc55c4101) | Nov 27, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b305057bc5](https://linux-hardware.org/?probe=b305057bc5) | Nov 27, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [dba63ed53c](https://linux-hardware.org/?probe=dba63ed53c) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [78e9bae926](https://linux-hardware.org/?probe=78e9bae926) | Nov 26, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [d6f36dff1d](https://linux-hardware.org/?probe=d6f36dff1d) | Nov 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [6f65f2ceeb](https://linux-hardware.org/?probe=6f65f2ceeb) | Nov 26, 2023 |
| HP            | Pavilion 14                 | Notebook    | [af5d0c670a](https://linux-hardware.org/?probe=af5d0c670a) | Nov 26, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [4fd4ea2869](https://linux-hardware.org/?probe=4fd4ea2869) | Nov 26, 2023 |
| Dell          | 0RY206                      | Desktop     | [7115b05660](https://linux-hardware.org/?probe=7115b05660) | Nov 25, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6007599bc5](https://linux-hardware.org/?probe=6007599bc5) | Nov 25, 2023 |
| MSI           | Z87-S02                     | Desktop     | [2d40c55867](https://linux-hardware.org/?probe=2d40c55867) | Nov 25, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [c6955988fb](https://linux-hardware.org/?probe=c6955988fb) | Nov 25, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ab26a80bc5](https://linux-hardware.org/?probe=ab26a80bc5) | Nov 25, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [a2fbff15e7](https://linux-hardware.org/?probe=a2fbff15e7) | Nov 25, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [6f3cf47d7d](https://linux-hardware.org/?probe=6f3cf47d7d) | Nov 25, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [1065af244c](https://linux-hardware.org/?probe=1065af244c) | Nov 25, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [904f3a4c07](https://linux-hardware.org/?probe=904f3a4c07) | Nov 25, 2023 |
| Dell          | Studio XPS 1640             | Notebook    | [3b9a32eb3f](https://linux-hardware.org/?probe=3b9a32eb3f) | Nov 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [4515ea6be6](https://linux-hardware.org/?probe=4515ea6be6) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4e7c1f967f](https://linux-hardware.org/?probe=4e7c1f967f) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a886bd351a](https://linux-hardware.org/?probe=a886bd351a) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [386171f14d](https://linux-hardware.org/?probe=386171f14d) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [ac1dfd9609](https://linux-hardware.org/?probe=ac1dfd9609) | Nov 24, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [98b666cd95](https://linux-hardware.org/?probe=98b666cd95) | Nov 24, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [9e25aa3d8f](https://linux-hardware.org/?probe=9e25aa3d8f) | Nov 24, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [d12afced10](https://linux-hardware.org/?probe=d12afced10) | Nov 24, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3730101bfb](https://linux-hardware.org/?probe=3730101bfb) | Nov 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2c505c0b1e](https://linux-hardware.org/?probe=2c505c0b1e) | Nov 24, 2023 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [c3d0a3a34c](https://linux-hardware.org/?probe=c3d0a3a34c) | Nov 24, 2023 |
| HP            | 85A2                        | All in one  | [80b79f2bed](https://linux-hardware.org/?probe=80b79f2bed) | Nov 24, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [23f539995b](https://linux-hardware.org/?probe=23f539995b) | Nov 24, 2023 |
| Dell          | Inspiron 1750               | Notebook    | [4d256b493c](https://linux-hardware.org/?probe=4d256b493c) | Nov 23, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [2127112b3a](https://linux-hardware.org/?probe=2127112b3a) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8416c7e558](https://linux-hardware.org/?probe=8416c7e558) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9aada56395](https://linux-hardware.org/?probe=9aada56395) | Nov 23, 2023 |
| HP            | 2AF7                        | Desktop     | [5594c88f44](https://linux-hardware.org/?probe=5594c88f44) | Nov 23, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [bc09939521](https://linux-hardware.org/?probe=bc09939521) | Nov 23, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [7b6e215012](https://linux-hardware.org/?probe=7b6e215012) | Nov 22, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [b8a36c00e8](https://linux-hardware.org/?probe=b8a36c00e8) | Nov 22, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b6e4999e4f](https://linux-hardware.org/?probe=b6e4999e4f) | Nov 22, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [b8a0ad5987](https://linux-hardware.org/?probe=b8a0ad5987) | Nov 22, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [2720b6f6d4](https://linux-hardware.org/?probe=2720b6f6d4) | Nov 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [21257dcbad](https://linux-hardware.org/?probe=21257dcbad) | Nov 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [b69760e673](https://linux-hardware.org/?probe=b69760e673) | Nov 22, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [e1abb4721b](https://linux-hardware.org/?probe=e1abb4721b) | Nov 21, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [d679a12a36](https://linux-hardware.org/?probe=d679a12a36) | Nov 21, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [00c164e154](https://linux-hardware.org/?probe=00c164e154) | Nov 21, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [be7c395cc7](https://linux-hardware.org/?probe=be7c395cc7) | Nov 21, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [96172d652b](https://linux-hardware.org/?probe=96172d652b) | Nov 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [03d7d46dd0](https://linux-hardware.org/?probe=03d7d46dd0) | Nov 21, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [8d328f4394](https://linux-hardware.org/?probe=8d328f4394) | Nov 21, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [348094cd98](https://linux-hardware.org/?probe=348094cd98) | Nov 21, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [a166dbb3cf](https://linux-hardware.org/?probe=a166dbb3cf) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [ece8c390b1](https://linux-hardware.org/?probe=ece8c390b1) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [55dac497f4](https://linux-hardware.org/?probe=55dac497f4) | Nov 20, 2023 |
| Lenovo        | ThinkPad Helix 3701CTO      | Notebook    | [f200cae4b1](https://linux-hardware.org/?probe=f200cae4b1) | Nov 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f58ea2a820](https://linux-hardware.org/?probe=f58ea2a820) | Nov 20, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a4f7b1d9d3](https://linux-hardware.org/?probe=a4f7b1d9d3) | Nov 20, 2023 |
| HP            | 8054                        | Desktop     | [2ccc2c67f2](https://linux-hardware.org/?probe=2ccc2c67f2) | Nov 20, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [56cd0716d9](https://linux-hardware.org/?probe=56cd0716d9) | Nov 19, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [792754cbe2](https://linux-hardware.org/?probe=792754cbe2) | Nov 19, 2023 |
| Lenovo        | ThinkPad E520 11437UG       | Notebook    | [422931d9a6](https://linux-hardware.org/?probe=422931d9a6) | Nov 19, 2023 |
| Dell          | Latitude E6330              | Notebook    | [3c6e547f2a](https://linux-hardware.org/?probe=3c6e547f2a) | Nov 19, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [354af02ac9](https://linux-hardware.org/?probe=354af02ac9) | Nov 19, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [75065dda24](https://linux-hardware.org/?probe=75065dda24) | Nov 19, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [7e047fc166](https://linux-hardware.org/?probe=7e047fc166) | Nov 19, 2023 |
| MSI           | GE76 Raider 11UE            | Notebook    | [9d0a216d82](https://linux-hardware.org/?probe=9d0a216d82) | Nov 19, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [a7d065988a](https://linux-hardware.org/?probe=a7d065988a) | Nov 19, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [fca337aea5](https://linux-hardware.org/?probe=fca337aea5) | Nov 19, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [7c45a9b620](https://linux-hardware.org/?probe=7c45a9b620) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [91f7d584f3](https://linux-hardware.org/?probe=91f7d584f3) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [ef77e621d0](https://linux-hardware.org/?probe=ef77e621d0) | Nov 19, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [fc41df67a4](https://linux-hardware.org/?probe=fc41df67a4) | Nov 19, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d086db0563](https://linux-hardware.org/?probe=d086db0563) | Nov 18, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [ae962a2552](https://linux-hardware.org/?probe=ae962a2552) | Nov 18, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [4735287055](https://linux-hardware.org/?probe=4735287055) | Nov 18, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [0619c3b255](https://linux-hardware.org/?probe=0619c3b255) | Nov 17, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [d402c27e5c](https://linux-hardware.org/?probe=d402c27e5c) | Nov 17, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [a6d12193c7](https://linux-hardware.org/?probe=a6d12193c7) | Nov 17, 2023 |
| HP            | 83E8                        | Desktop     | [393ca40cd9](https://linux-hardware.org/?probe=393ca40cd9) | Nov 16, 2023 |
| Dell          | Precision 5680              | Notebook    | [a2957d2ece](https://linux-hardware.org/?probe=a2957d2ece) | Nov 16, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [9b4ca9cc96](https://linux-hardware.org/?probe=9b4ca9cc96) | Nov 16, 2023 |
| Dell          | Precision 5680              | Notebook    | [2c6c6027a6](https://linux-hardware.org/?probe=2c6c6027a6) | Nov 16, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [07a03ff43b](https://linux-hardware.org/?probe=07a03ff43b) | Nov 16, 2023 |
| Lenovo        | ThinkPad E550 20DF001HAU    | Notebook    | [44968b500c](https://linux-hardware.org/?probe=44968b500c) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [fade86e55e](https://linux-hardware.org/?probe=fade86e55e) | Nov 16, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [e4ac0f919f](https://linux-hardware.org/?probe=e4ac0f919f) | Nov 16, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [68dbf5814b](https://linux-hardware.org/?probe=68dbf5814b) | Nov 15, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [14799f850b](https://linux-hardware.org/?probe=14799f850b) | Nov 15, 2023 |
| HP            | ProBook 4540s               | Notebook    | [48705484f5](https://linux-hardware.org/?probe=48705484f5) | Nov 15, 2023 |
| Dell          | XPS 9320                    | Notebook    | [f0435ea4b7](https://linux-hardware.org/?probe=f0435ea4b7) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [386519f50c](https://linux-hardware.org/?probe=386519f50c) | Nov 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6a6b0096bb](https://linux-hardware.org/?probe=6a6b0096bb) | Nov 15, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [c3c068a998](https://linux-hardware.org/?probe=c3c068a998) | Nov 14, 2023 |
| Acer          | Aspire V3-471G              | Notebook    | [f027c1d470](https://linux-hardware.org/?probe=f027c1d470) | Nov 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [da50e3550f](https://linux-hardware.org/?probe=da50e3550f) | Nov 14, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [7b17ba0f7f](https://linux-hardware.org/?probe=7b17ba0f7f) | Nov 14, 2023 |
| HP            | 2AF7                        | Desktop     | [dd8d87a916](https://linux-hardware.org/?probe=dd8d87a916) | Nov 14, 2023 |
| HP            | ProBook 4540s               | Notebook    | [f8e4ef7043](https://linux-hardware.org/?probe=f8e4ef7043) | Nov 14, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [3cd966cd6a](https://linux-hardware.org/?probe=3cd966cd6a) | Nov 14, 2023 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [73ef67d393](https://linux-hardware.org/?probe=73ef67d393) | Nov 13, 2023 |
| System76      | Adder WS                    | Notebook    | [7135955eda](https://linux-hardware.org/?probe=7135955eda) | Nov 13, 2023 |
| ASUSTek       | X55U                        | Notebook    | [04a09add31](https://linux-hardware.org/?probe=04a09add31) | Nov 13, 2023 |
| Dell          | Precision 7720              | Notebook    | [1f358e68ee](https://linux-hardware.org/?probe=1f358e68ee) | Nov 13, 2023 |
| Dell          | Precision 7720              | Notebook    | [facdc5c2a4](https://linux-hardware.org/?probe=facdc5c2a4) | Nov 13, 2023 |
| MSI           | GT70                        | Notebook    | [e2c0bb5bfe](https://linux-hardware.org/?probe=e2c0bb5bfe) | Nov 13, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [e384b513f0](https://linux-hardware.org/?probe=e384b513f0) | Nov 13, 2023 |
| AMI           | Intel                       | Desktop     | [7c96434a18](https://linux-hardware.org/?probe=7c96434a18) | Nov 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [f9ee628d93](https://linux-hardware.org/?probe=f9ee628d93) | Nov 13, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [cac951f39c](https://linux-hardware.org/?probe=cac951f39c) | Nov 13, 2023 |
| System76      | Lemur Pro                   | Notebook    | [35e6e1214c](https://linux-hardware.org/?probe=35e6e1214c) | Nov 12, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [a6083e5df9](https://linux-hardware.org/?probe=a6083e5df9) | Nov 12, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [4162e8afa8](https://linux-hardware.org/?probe=4162e8afa8) | Nov 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b9ad1f18d8](https://linux-hardware.org/?probe=b9ad1f18d8) | Nov 12, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f3b49f17b1](https://linux-hardware.org/?probe=f3b49f17b1) | Nov 12, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [091eaf746f](https://linux-hardware.org/?probe=091eaf746f) | Nov 12, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [61994e2e2e](https://linux-hardware.org/?probe=61994e2e2e) | Nov 12, 2023 |
| Google        | Edgar                       | Notebook    | [838bd73737](https://linux-hardware.org/?probe=838bd73737) | Nov 12, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [0e6185c9db](https://linux-hardware.org/?probe=0e6185c9db) | Nov 11, 2023 |
| Google        | Edgar                       | Notebook    | [42f8059f62](https://linux-hardware.org/?probe=42f8059f62) | Nov 11, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [1946d2a10c](https://linux-hardware.org/?probe=1946d2a10c) | Nov 11, 2023 |
| HP            | G42                         | Notebook    | [8a331f427d](https://linux-hardware.org/?probe=8a331f427d) | Nov 11, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [d9b24edac8](https://linux-hardware.org/?probe=d9b24edac8) | Nov 11, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [75735f5b69](https://linux-hardware.org/?probe=75735f5b69) | Nov 11, 2023 |
| Dell          | Latitude E5420              | Notebook    | [ac31e56717](https://linux-hardware.org/?probe=ac31e56717) | Nov 11, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [f22d74d5eb](https://linux-hardware.org/?probe=f22d74d5eb) | Nov 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [080772c4d8](https://linux-hardware.org/?probe=080772c4d8) | Nov 11, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [9c77400bbf](https://linux-hardware.org/?probe=9c77400bbf) | Nov 11, 2023 |
| HP            | Pavilion g7                 | Notebook    | [f963761c30](https://linux-hardware.org/?probe=f963761c30) | Nov 10, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [ecc5d08bd8](https://linux-hardware.org/?probe=ecc5d08bd8) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [0cacf99f8a](https://linux-hardware.org/?probe=0cacf99f8a) | Nov 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [93d7b2bcdc](https://linux-hardware.org/?probe=93d7b2bcdc) | Nov 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [0bb1ba6267](https://linux-hardware.org/?probe=0bb1ba6267) | Nov 09, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [1473413ce2](https://linux-hardware.org/?probe=1473413ce2) | Nov 09, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [03b4295585](https://linux-hardware.org/?probe=03b4295585) | Nov 09, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [ab3577cc31](https://linux-hardware.org/?probe=ab3577cc31) | Nov 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b221326a48](https://linux-hardware.org/?probe=b221326a48) | Nov 09, 2023 |
| Dell          | 015YTG A02                  | All in one  | [d151271204](https://linux-hardware.org/?probe=d151271204) | Nov 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [c048c3b791](https://linux-hardware.org/?probe=c048c3b791) | Nov 09, 2023 |
| HP            | G42                         | Notebook    | [f440217af5](https://linux-hardware.org/?probe=f440217af5) | Nov 09, 2023 |
| Dell          | Precision 5520              | Notebook    | [1166f1d95d](https://linux-hardware.org/?probe=1166f1d95d) | Nov 08, 2023 |
| Dell          | Latitude E7270              | Notebook    | [0410c1ba06](https://linux-hardware.org/?probe=0410c1ba06) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [d2ce7f8ca6](https://linux-hardware.org/?probe=d2ce7f8ca6) | Nov 08, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [e4f3bd771d](https://linux-hardware.org/?probe=e4f3bd771d) | Nov 08, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [173692c48a](https://linux-hardware.org/?probe=173692c48a) | Nov 08, 2023 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [8ca7abbf03](https://linux-hardware.org/?probe=8ca7abbf03) | Nov 08, 2023 |
| Acer          | Aspire A517-51              | Notebook    | [9b0700130f](https://linux-hardware.org/?probe=9b0700130f) | Nov 08, 2023 |
| System76      | Lemur Pro                   | Notebook    | [92d1345459](https://linux-hardware.org/?probe=92d1345459) | Nov 07, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c28217d1ed](https://linux-hardware.org/?probe=c28217d1ed) | Nov 07, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [a675ce6c08](https://linux-hardware.org/?probe=a675ce6c08) | Nov 07, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [4075eda03c](https://linux-hardware.org/?probe=4075eda03c) | Nov 07, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [c88dde8f18](https://linux-hardware.org/?probe=c88dde8f18) | Nov 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9755c6bf31](https://linux-hardware.org/?probe=9755c6bf31) | Nov 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c2ae66ef2b](https://linux-hardware.org/?probe=c2ae66ef2b) | Nov 06, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [7f057ebed2](https://linux-hardware.org/?probe=7f057ebed2) | Nov 06, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [2716ef5f71](https://linux-hardware.org/?probe=2716ef5f71) | Nov 06, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [697278adb7](https://linux-hardware.org/?probe=697278adb7) | Nov 06, 2023 |
| HP            | 89E9 0100                   | All in one  | [5e98ad51b6](https://linux-hardware.org/?probe=5e98ad51b6) | Nov 06, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [f575f3121e](https://linux-hardware.org/?probe=f575f3121e) | Nov 06, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [7cc876dcfa](https://linux-hardware.org/?probe=7cc876dcfa) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [290be8911e](https://linux-hardware.org/?probe=290be8911e) | Nov 06, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [a782c6c087](https://linux-hardware.org/?probe=a782c6c087) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | Notebook    | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [e6c695d4a7](https://linux-hardware.org/?probe=e6c695d4a7) | Nov 05, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [be39067306](https://linux-hardware.org/?probe=be39067306) | Nov 05, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [7834b537a1](https://linux-hardware.org/?probe=7834b537a1) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Google        | Taeko                       | Notebook    | [d148b001d9](https://linux-hardware.org/?probe=d148b001d9) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [6f11758faa](https://linux-hardware.org/?probe=6f11758faa) | Nov 04, 2023 |
| Gigabyte      | H410M S2H V2                | Desktop     | [8bbce8a378](https://linux-hardware.org/?probe=8bbce8a378) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [cfdf343144](https://linux-hardware.org/?probe=cfdf343144) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [237bd5cfb2](https://linux-hardware.org/?probe=237bd5cfb2) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [ea89273272](https://linux-hardware.org/?probe=ea89273272) | Nov 04, 2023 |
| HP            | 655                         | Notebook    | [8cf9aa61c7](https://linux-hardware.org/?probe=8cf9aa61c7) | Nov 04, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [f8507f333d](https://linux-hardware.org/?probe=f8507f333d) | Nov 04, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [5db0e7314a](https://linux-hardware.org/?probe=5db0e7314a) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [972ef88623](https://linux-hardware.org/?probe=972ef88623) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [927b50091e](https://linux-hardware.org/?probe=927b50091e) | Nov 04, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [f27bded4c1](https://linux-hardware.org/?probe=f27bded4c1) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [26aff1917e](https://linux-hardware.org/?probe=26aff1917e) | Nov 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [1704acc89b](https://linux-hardware.org/?probe=1704acc89b) | Nov 03, 2023 |
| Intel         | X79 V1.0                    | Desktop     | [9483a097a1](https://linux-hardware.org/?probe=9483a097a1) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [d35fc5aa78](https://linux-hardware.org/?probe=d35fc5aa78) | Nov 03, 2023 |
| Lenovo        | ThinkPad T420s 417032U      | Notebook    | [76247c39f4](https://linux-hardware.org/?probe=76247c39f4) | Nov 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3a8d337535](https://linux-hardware.org/?probe=3a8d337535) | Nov 03, 2023 |
| HP            | ProBook 6450b               | Notebook    | [75ad2cf5f8](https://linux-hardware.org/?probe=75ad2cf5f8) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [9a5c45e54b](https://linux-hardware.org/?probe=9a5c45e54b) | Nov 02, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [12414485a5](https://linux-hardware.org/?probe=12414485a5) | Nov 02, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [7d93bb6f25](https://linux-hardware.org/?probe=7d93bb6f25) | Nov 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [fc0052213d](https://linux-hardware.org/?probe=fc0052213d) | Nov 02, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [7812f09d39](https://linux-hardware.org/?probe=7812f09d39) | Nov 02, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [b45e25ec01](https://linux-hardware.org/?probe=b45e25ec01) | Nov 02, 2023 |
| HP            | 2AF7                        | Desktop     | [65ac8348d7](https://linux-hardware.org/?probe=65ac8348d7) | Nov 02, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [04f3946d05](https://linux-hardware.org/?probe=04f3946d05) | Nov 02, 2023 |
| Supermicro    | X9DRE-TF+/X9DR7-TF+         | Server      | [1274766930](https://linux-hardware.org/?probe=1274766930) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [200e3255d9](https://linux-hardware.org/?probe=200e3255d9) | Nov 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cd018c7ab7](https://linux-hardware.org/?probe=cd018c7ab7) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [43a84b57f0](https://linux-hardware.org/?probe=43a84b57f0) | Nov 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [523fd59139](https://linux-hardware.org/?probe=523fd59139) | Nov 01, 2023 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [d85d5f59c2](https://linux-hardware.org/?probe=d85d5f59c2) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | Notebook    | [dba91e5612](https://linux-hardware.org/?probe=dba91e5612) | Nov 01, 2023 |
| HP            | ENVY 15                     | Notebook    | [74dae44745](https://linux-hardware.org/?probe=74dae44745) | Nov 01, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [39f8a7c959](https://linux-hardware.org/?probe=39f8a7c959) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [c1e44a55c8](https://linux-hardware.org/?probe=c1e44a55c8) | Nov 01, 2023 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [84ca0a285d](https://linux-hardware.org/?probe=84ca0a285d) | Nov 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [38d664802f](https://linux-hardware.org/?probe=38d664802f) | Nov 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [037e92aebd](https://linux-hardware.org/?probe=037e92aebd) | Nov 01, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [0ec8ac4d00](https://linux-hardware.org/?probe=0ec8ac4d00) | Nov 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [6b6da0ca4a](https://linux-hardware.org/?probe=6b6da0ca4a) | Nov 01, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [0ea7f00b4e](https://linux-hardware.org/?probe=0ea7f00b4e) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [7d5fd28d41](https://linux-hardware.org/?probe=7d5fd28d41) | Nov 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [847ae1ea8d](https://linux-hardware.org/?probe=847ae1ea8d) | Nov 01, 2023 |
| HP            | 829A                        | Mini pc     | [d6ef1b58ed](https://linux-hardware.org/?probe=d6ef1b58ed) | Nov 01, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [643c7ccd9b](https://linux-hardware.org/?probe=643c7ccd9b) | Nov 01, 2023 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [e9f8c192f1](https://linux-hardware.org/?probe=e9f8c192f1) | Nov 01, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [f08e4e21a0](https://linux-hardware.org/?probe=f08e4e21a0) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d58a78a617](https://linux-hardware.org/?probe=d58a78a617) | Oct 31, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [a10aa3c3e5](https://linux-hardware.org/?probe=a10aa3c3e5) | Oct 31, 2023 |
| ASRockRack    | X570D4U-2L2T/BCM            | Server      | [66607ff17c](https://linux-hardware.org/?probe=66607ff17c) | Oct 31, 2023 |
| eMachines     | EL1352G                     | Desktop     | [e133fecf3e](https://linux-hardware.org/?probe=e133fecf3e) | Oct 31, 2023 |
| ASRock        | A520M Phantom Gaming 4      | Desktop     | [a63d934992](https://linux-hardware.org/?probe=a63d934992) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [cb013304f5](https://linux-hardware.org/?probe=cb013304f5) | Oct 31, 2023 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [d6ac483e43](https://linux-hardware.org/?probe=d6ac483e43) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ee528fce07](https://linux-hardware.org/?probe=ee528fce07) | Oct 31, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4e0042e20c](https://linux-hardware.org/?probe=4e0042e20c) | Oct 31, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [7c76f143a4](https://linux-hardware.org/?probe=7c76f143a4) | Oct 31, 2023 |
| HP            | 8299                        | Desktop     | [e45f46df9d](https://linux-hardware.org/?probe=e45f46df9d) | Oct 30, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [56f24de5ff](https://linux-hardware.org/?probe=56f24de5ff) | Oct 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [81a7cabe4f](https://linux-hardware.org/?probe=81a7cabe4f) | Oct 30, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [d5ace42b13](https://linux-hardware.org/?probe=d5ace42b13) | Oct 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [d51c491524](https://linux-hardware.org/?probe=d51c491524) | Oct 30, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [65f24e332a](https://linux-hardware.org/?probe=65f24e332a) | Oct 30, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e231035f6e](https://linux-hardware.org/?probe=e231035f6e) | Oct 30, 2023 |
| System76      | Adder WS                    | Notebook    | [57478f4561](https://linux-hardware.org/?probe=57478f4561) | Oct 30, 2023 |
| System76      | Adder WS                    | Notebook    | [a10fcac3f4](https://linux-hardware.org/?probe=a10fcac3f4) | Oct 30, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [b62cfa508b](https://linux-hardware.org/?probe=b62cfa508b) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [5863bd6189](https://linux-hardware.org/?probe=5863bd6189) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [7301c9b3df](https://linux-hardware.org/?probe=7301c9b3df) | Oct 29, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [48040bae06](https://linux-hardware.org/?probe=48040bae06) | Oct 29, 2023 |
| HP            | 2AF7                        | Desktop     | [1960b3a243](https://linux-hardware.org/?probe=1960b3a243) | Oct 29, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2815a5477f](https://linux-hardware.org/?probe=2815a5477f) | Oct 29, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [8697e4de09](https://linux-hardware.org/?probe=8697e4de09) | Oct 29, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [c90dd43290](https://linux-hardware.org/?probe=c90dd43290) | Oct 29, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [c1785bec94](https://linux-hardware.org/?probe=c1785bec94) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [d621a72336](https://linux-hardware.org/?probe=d621a72336) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | Notebook    | [57e3abc23d](https://linux-hardware.org/?probe=57e3abc23d) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0f9adbc34d](https://linux-hardware.org/?probe=0f9adbc34d) | Oct 28, 2023 |
| Maibenben     | MaiBook X series            | Notebook    | [63e0cb487a](https://linux-hardware.org/?probe=63e0cb487a) | Oct 28, 2023 |
| Samsung       | DM700A4K-KN27 SGL8559A1A... | All in one  | [e6c0db51c1](https://linux-hardware.org/?probe=e6c0db51c1) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6b8560a943](https://linux-hardware.org/?probe=6b8560a943) | Oct 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9a6fdf5543](https://linux-hardware.org/?probe=9a6fdf5543) | Oct 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [85b2c39c93](https://linux-hardware.org/?probe=85b2c39c93) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | Desktop     | [fdb96441a0](https://linux-hardware.org/?probe=fdb96441a0) | Oct 27, 2023 |
| ASUSTek       | ProArt B650-CREATOR         | Desktop     | [dde83d5de1](https://linux-hardware.org/?probe=dde83d5de1) | Oct 27, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [2e5ee0032d](https://linux-hardware.org/?probe=2e5ee0032d) | Oct 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [880bf38f49](https://linux-hardware.org/?probe=880bf38f49) | Oct 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e5b2c76907](https://linux-hardware.org/?probe=e5b2c76907) | Oct 27, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [9d34ff8710](https://linux-hardware.org/?probe=9d34ff8710) | Oct 27, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [fc29a80949](https://linux-hardware.org/?probe=fc29a80949) | Oct 27, 2023 |
| System76      | Darter Pro                  | Notebook    | [9dcbc85a23](https://linux-hardware.org/?probe=9dcbc85a23) | Oct 27, 2023 |
| HP            | OMEN LAPTOP - 15-EK0013D... | Notebook    | [0c582fd597](https://linux-hardware.org/?probe=0c582fd597) | Oct 27, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [114e1e6d66](https://linux-hardware.org/?probe=114e1e6d66) | Oct 27, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [4938c66cd8](https://linux-hardware.org/?probe=4938c66cd8) | Oct 27, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [815b0a4bc4](https://linux-hardware.org/?probe=815b0a4bc4) | Oct 27, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [61bdfadaa0](https://linux-hardware.org/?probe=61bdfadaa0) | Oct 26, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [f0641b8822](https://linux-hardware.org/?probe=f0641b8822) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [3de6c48f15](https://linux-hardware.org/?probe=3de6c48f15) | Oct 26, 2023 |
| Dell          | Latitude E6530              | Notebook    | [ec57b86fe6](https://linux-hardware.org/?probe=ec57b86fe6) | Oct 26, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [e4a7d4f368](https://linux-hardware.org/?probe=e4a7d4f368) | Oct 26, 2023 |
| Panasonic     | CF-31SBM08DM                | Notebook    | [820f042ba6](https://linux-hardware.org/?probe=820f042ba6) | Oct 26, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [13ad3bb316](https://linux-hardware.org/?probe=13ad3bb316) | Oct 26, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [a8d850eef8](https://linux-hardware.org/?probe=a8d850eef8) | Oct 26, 2023 |
| Haier         | U1520SD                     | Notebook    | [25229c3d32](https://linux-hardware.org/?probe=25229c3d32) | Oct 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [023bd4d497](https://linux-hardware.org/?probe=023bd4d497) | Oct 25, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [7fc2a154e5](https://linux-hardware.org/?probe=7fc2a154e5) | Oct 25, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [638386d33c](https://linux-hardware.org/?probe=638386d33c) | Oct 25, 2023 |
| HP            | 3047h                       | Desktop     | [cdd7fbc37f](https://linux-hardware.org/?probe=cdd7fbc37f) | Oct 25, 2023 |
| HP            | 3047h                       | Desktop     | [4235f287b2](https://linux-hardware.org/?probe=4235f287b2) | Oct 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [dab53e45c9](https://linux-hardware.org/?probe=dab53e45c9) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b7447f21b5](https://linux-hardware.org/?probe=b7447f21b5) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [9a4561dabf](https://linux-hardware.org/?probe=9a4561dabf) | Oct 25, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [5ad24eb928](https://linux-hardware.org/?probe=5ad24eb928) | Oct 24, 2023 |
| Dell          | 02P9X9 A00                  | Server      | [85fac54d6a](https://linux-hardware.org/?probe=85fac54d6a) | Oct 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [ecde45a506](https://linux-hardware.org/?probe=ecde45a506) | Oct 24, 2023 |
| Danuri        | B550M-PX                    | Desktop     | [e24df1ad61](https://linux-hardware.org/?probe=e24df1ad61) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Intel         | H61 V124                    | Desktop     | [034689793f](https://linux-hardware.org/?probe=034689793f) | Oct 24, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [b1f52f8dc1](https://linux-hardware.org/?probe=b1f52f8dc1) | Oct 23, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a9af589ace](https://linux-hardware.org/?probe=a9af589ace) | Oct 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [6fead70e93](https://linux-hardware.org/?probe=6fead70e93) | Oct 23, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [47fdb21256](https://linux-hardware.org/?probe=47fdb21256) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7e9d761b35](https://linux-hardware.org/?probe=7e9d761b35) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cf347b4567](https://linux-hardware.org/?probe=cf347b4567) | Oct 23, 2023 |
| MSI           | Sword 15 A11UD              | Notebook    | [d07a7c777c](https://linux-hardware.org/?probe=d07a7c777c) | Oct 23, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [ce5ff412d1](https://linux-hardware.org/?probe=ce5ff412d1) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [73c1b49eab](https://linux-hardware.org/?probe=73c1b49eab) | Oct 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [b6169d3a96](https://linux-hardware.org/?probe=b6169d3a96) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e0f48fec00](https://linux-hardware.org/?probe=e0f48fec00) | Oct 22, 2023 |
| ASUSTek       | G750JW                      | Notebook    | [9bafdb8250](https://linux-hardware.org/?probe=9bafdb8250) | Oct 22, 2023 |
| Dell          | Latitude 5520               | Notebook    | [f5664b02d2](https://linux-hardware.org/?probe=f5664b02d2) | Oct 22, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [7f1637fdb9](https://linux-hardware.org/?probe=7f1637fdb9) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [58a9a7a091](https://linux-hardware.org/?probe=58a9a7a091) | Oct 22, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [d19756d24b](https://linux-hardware.org/?probe=d19756d24b) | Oct 22, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [14ed4adf6c](https://linux-hardware.org/?probe=14ed4adf6c) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [9b380c5e6a](https://linux-hardware.org/?probe=9b380c5e6a) | Oct 22, 2023 |
| EUROCOM       | Tornado F5                  | Notebook    | [3056eeecf5](https://linux-hardware.org/?probe=3056eeecf5) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | Notebook    | [010dd78352](https://linux-hardware.org/?probe=010dd78352) | Oct 21, 2023 |
| EUROCOM       | Tornado F5                  | Notebook    | [25b7095754](https://linux-hardware.org/?probe=25b7095754) | Oct 21, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [b1a3bf1a75](https://linux-hardware.org/?probe=b1a3bf1a75) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [97d1264314](https://linux-hardware.org/?probe=97d1264314) | Oct 21, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [6468bd6335](https://linux-hardware.org/?probe=6468bd6335) | Oct 21, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [85894d27fe](https://linux-hardware.org/?probe=85894d27fe) | Oct 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3b8a5a44c7](https://linux-hardware.org/?probe=3b8a5a44c7) | Oct 21, 2023 |
| Dell          | 06FW8P A01                  | Desktop     | [356c2f38aa](https://linux-hardware.org/?probe=356c2f38aa) | Oct 21, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [5966a36809](https://linux-hardware.org/?probe=5966a36809) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a2756e1d2b](https://linux-hardware.org/?probe=a2756e1d2b) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [ca61a8649a](https://linux-hardware.org/?probe=ca61a8649a) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [6108985945](https://linux-hardware.org/?probe=6108985945) | Oct 21, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [e7cd525d35](https://linux-hardware.org/?probe=e7cd525d35) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [148be53a91](https://linux-hardware.org/?probe=148be53a91) | Oct 20, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [793d71f1d2](https://linux-hardware.org/?probe=793d71f1d2) | Oct 20, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [e51b067a88](https://linux-hardware.org/?probe=e51b067a88) | Oct 20, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [2adde1171a](https://linux-hardware.org/?probe=2adde1171a) | Oct 20, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [6ee41b351a](https://linux-hardware.org/?probe=6ee41b351a) | Oct 20, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [871f28b131](https://linux-hardware.org/?probe=871f28b131) | Oct 20, 2023 |
| Dell          | Latitude 5520               | Notebook    | [281fdb7e86](https://linux-hardware.org/?probe=281fdb7e86) | Oct 20, 2023 |
| HP            | Pavilion 17                 | Notebook    | [36613b2f1f](https://linux-hardware.org/?probe=36613b2f1f) | Oct 19, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [7fab57f39a](https://linux-hardware.org/?probe=7fab57f39a) | Oct 19, 2023 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [7148bf6db9](https://linux-hardware.org/?probe=7148bf6db9) | Oct 19, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [4312e9a007](https://linux-hardware.org/?probe=4312e9a007) | Oct 19, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9cbbb0364b](https://linux-hardware.org/?probe=9cbbb0364b) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [2f2d05a226](https://linux-hardware.org/?probe=2f2d05a226) | Oct 19, 2023 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [81f32f2ac2](https://linux-hardware.org/?probe=81f32f2ac2) | Oct 19, 2023 |
| HP            | Pavilion Laptop 15t-eg30... | Notebook    | [b2cba37968](https://linux-hardware.org/?probe=b2cba37968) | Oct 19, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | Notebook    | [cd80438b02](https://linux-hardware.org/?probe=cd80438b02) | Oct 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ed3ce7aaa6](https://linux-hardware.org/?probe=ed3ce7aaa6) | Oct 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [315376a82a](https://linux-hardware.org/?probe=315376a82a) | Oct 18, 2023 |
| Dell          | 0JYF1T A03                  | Server      | [93ada2329e](https://linux-hardware.org/?probe=93ada2329e) | Oct 18, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [b6b4b14ba1](https://linux-hardware.org/?probe=b6b4b14ba1) | Oct 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| HP            | 85A2                        | All in one  | [67234a41ca](https://linux-hardware.org/?probe=67234a41ca) | Oct 18, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [e275cfc499](https://linux-hardware.org/?probe=e275cfc499) | Oct 18, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [d652b15856](https://linux-hardware.org/?probe=d652b15856) | Oct 17, 2023 |
| System76      | Gazelle                     | Notebook    | [061012cdb0](https://linux-hardware.org/?probe=061012cdb0) | Oct 17, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME E... | Desktop     | [3d5d8ee9e6](https://linux-hardware.org/?probe=3d5d8ee9e6) | Oct 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [464e218144](https://linux-hardware.org/?probe=464e218144) | Oct 17, 2023 |
| Gigabyte      | Z590 VISION D               | Desktop     | [f9d3acd4e2](https://linux-hardware.org/?probe=f9d3acd4e2) | Oct 16, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [0ebd0d4ce6](https://linux-hardware.org/?probe=0ebd0d4ce6) | Oct 16, 2023 |
| HP            | 250 G4                      | Notebook    | [a45d8a13df](https://linux-hardware.org/?probe=a45d8a13df) | Oct 16, 2023 |
| HP            | Laptop 15-dw4xxx            | Notebook    | [44ba7f4015](https://linux-hardware.org/?probe=44ba7f4015) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| ASUSTek       | N551ZU                      | Notebook    | [e56a6c7957](https://linux-hardware.org/?probe=e56a6c7957) | Oct 16, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [5631fc0230](https://linux-hardware.org/?probe=5631fc0230) | Oct 16, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [04afaee575](https://linux-hardware.org/?probe=04afaee575) | Oct 15, 2023 |
| HP            | ProBook 4730s               | Notebook    | [42a7295a49](https://linux-hardware.org/?probe=42a7295a49) | Oct 15, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [98224c65b6](https://linux-hardware.org/?probe=98224c65b6) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [47788537bf](https://linux-hardware.org/?probe=47788537bf) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [30723700f1](https://linux-hardware.org/?probe=30723700f1) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [e4dc0eeb72](https://linux-hardware.org/?probe=e4dc0eeb72) | Oct 15, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [abc6dc18ab](https://linux-hardware.org/?probe=abc6dc18ab) | Oct 15, 2023 |
| MECHREVO      | WUJIE14 PRO                 | Notebook    | [40cfeec2b2](https://linux-hardware.org/?probe=40cfeec2b2) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [7a732e8a25](https://linux-hardware.org/?probe=7a732e8a25) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [22b5b65e16](https://linux-hardware.org/?probe=22b5b65e16) | Oct 15, 2023 |
| HP            | 212B                        | Desktop     | [c0b9765d6e](https://linux-hardware.org/?probe=c0b9765d6e) | Oct 15, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [5bbd5682e8](https://linux-hardware.org/?probe=5bbd5682e8) | Oct 15, 2023 |
| System76      | Lemur Pro                   | Notebook    | [f969d7a459](https://linux-hardware.org/?probe=f969d7a459) | Oct 15, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [5a1df4c4df](https://linux-hardware.org/?probe=5a1df4c4df) | Oct 14, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a8e7e9b968](https://linux-hardware.org/?probe=a8e7e9b968) | Oct 14, 2023 |
| Gigabyte      | Z590I VISION D              | Desktop     | [725929fa07](https://linux-hardware.org/?probe=725929fa07) | Oct 14, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [7df48c5c5d](https://linux-hardware.org/?probe=7df48c5c5d) | Oct 14, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [142bc36a3f](https://linux-hardware.org/?probe=142bc36a3f) | Oct 14, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [0594aaa28b](https://linux-hardware.org/?probe=0594aaa28b) | Oct 13, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [596e3973bc](https://linux-hardware.org/?probe=596e3973bc) | Oct 13, 2023 |
| Notebook      | P9XXEN_EF_ED                | Notebook    | [89eae06fc2](https://linux-hardware.org/?probe=89eae06fc2) | Oct 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4d6379353d](https://linux-hardware.org/?probe=4d6379353d) | Oct 13, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [52fdfb249e](https://linux-hardware.org/?probe=52fdfb249e) | Oct 12, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [94754c98ce](https://linux-hardware.org/?probe=94754c98ce) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d7d6c5206f](https://linux-hardware.org/?probe=d7d6c5206f) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Biostar       | B550GTQ                     | Desktop     | [63f1b39dd4](https://linux-hardware.org/?probe=63f1b39dd4) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| HP            | Unknown                     | Convertible | [8fe4fae90f](https://linux-hardware.org/?probe=8fe4fae90f) | Oct 12, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [df15a4cce8](https://linux-hardware.org/?probe=df15a4cce8) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [5e2f8bdc4d](https://linux-hardware.org/?probe=5e2f8bdc4d) | Oct 12, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [ee849775df](https://linux-hardware.org/?probe=ee849775df) | Oct 12, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [e71b9295ca](https://linux-hardware.org/?probe=e71b9295ca) | Oct 11, 2023 |
| System76      | Thelio Mega thelio-mega-... | Desktop     | [abb07364c1](https://linux-hardware.org/?probe=abb07364c1) | Oct 11, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [c815acfae8](https://linux-hardware.org/?probe=c815acfae8) | Oct 11, 2023 |
| Gateway       | NE570                       | Notebook    | [533fec5226](https://linux-hardware.org/?probe=533fec5226) | Oct 11, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [552e952ebe](https://linux-hardware.org/?probe=552e952ebe) | Oct 11, 2023 |
| Acer          | Aspire A515-44G             | Notebook    | [58d145f207](https://linux-hardware.org/?probe=58d145f207) | Oct 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4ce0d26e3c](https://linux-hardware.org/?probe=4ce0d26e3c) | Oct 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [7d7f268cec](https://linux-hardware.org/?probe=7d7f268cec) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [835f369588](https://linux-hardware.org/?probe=835f369588) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [9acd34e892](https://linux-hardware.org/?probe=9acd34e892) | Oct 11, 2023 |
| HP            | ProLiant SE1220             | Server      | [da67ae4335](https://linux-hardware.org/?probe=da67ae4335) | Oct 11, 2023 |
| ASUSTek       | PRIME Z590-V                | Desktop     | [ee15914a37](https://linux-hardware.org/?probe=ee15914a37) | Oct 10, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [66bd7ea744](https://linux-hardware.org/?probe=66bd7ea744) | Oct 10, 2023 |
| Lenovo        | ThinkPad P1 20MES05502      | Notebook    | [869264ad64](https://linux-hardware.org/?probe=869264ad64) | Oct 10, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3d02079672](https://linux-hardware.org/?probe=3d02079672) | Oct 10, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b09f4a3a8a](https://linux-hardware.org/?probe=b09f4a3a8a) | Oct 10, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [5d606c8b1c](https://linux-hardware.org/?probe=5d606c8b1c) | Oct 10, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [6591296a12](https://linux-hardware.org/?probe=6591296a12) | Oct 10, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [c39ce018d6](https://linux-hardware.org/?probe=c39ce018d6) | Oct 10, 2023 |
| Gigabyte      | AORUS 17H BXF               | Notebook    | [4fcbae7a75](https://linux-hardware.org/?probe=4fcbae7a75) | Oct 10, 2023 |
| System76      | Darter Pro                  | Notebook    | [71e1a67b2a](https://linux-hardware.org/?probe=71e1a67b2a) | Oct 10, 2023 |
| Razer         | Blade                       | Notebook    | [22de5dfe50](https://linux-hardware.org/?probe=22de5dfe50) | Oct 09, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [420f5d5de9](https://linux-hardware.org/?probe=420f5d5de9) | Oct 09, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [2d033cba6c](https://linux-hardware.org/?probe=2d033cba6c) | Oct 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [63cbb26f44](https://linux-hardware.org/?probe=63cbb26f44) | Oct 08, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3d510e53b4](https://linux-hardware.org/?probe=3d510e53b4) | Oct 08, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [3b54f5530b](https://linux-hardware.org/?probe=3b54f5530b) | Oct 08, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [3ac34a911c](https://linux-hardware.org/?probe=3ac34a911c) | Oct 08, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [a3190a6c6d](https://linux-hardware.org/?probe=a3190a6c6d) | Oct 07, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [e223a799bc](https://linux-hardware.org/?probe=e223a799bc) | Oct 07, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [36d48fe6f7](https://linux-hardware.org/?probe=36d48fe6f7) | Oct 07, 2023 |
| HP            | 8058                        | All in one  | [1e3047c572](https://linux-hardware.org/?probe=1e3047c572) | Oct 07, 2023 |
| System76      | Serval WS                   | Notebook    | [509cc872ee](https://linux-hardware.org/?probe=509cc872ee) | Oct 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [7bd2b6300f](https://linux-hardware.org/?probe=7bd2b6300f) | Oct 07, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [17cdd65d6b](https://linux-hardware.org/?probe=17cdd65d6b) | Oct 07, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [f773c3004e](https://linux-hardware.org/?probe=f773c3004e) | Oct 07, 2023 |
| Huanan        | X99-BD4 V1.33               | Desktop     | [9477d90e51](https://linux-hardware.org/?probe=9477d90e51) | Oct 07, 2023 |
| HP            | ProBook 6450b               | Notebook    | [70e33902c1](https://linux-hardware.org/?probe=70e33902c1) | Oct 07, 2023 |
| HP            | ProBook 6450b               | Notebook    | [ddd8417a28](https://linux-hardware.org/?probe=ddd8417a28) | Oct 07, 2023 |
| MSI           | GE62 2QF                    | Notebook    | [cd73adb01d](https://linux-hardware.org/?probe=cd73adb01d) | Oct 07, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [5ec4f81683](https://linux-hardware.org/?probe=5ec4f81683) | Oct 06, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [687a37a00f](https://linux-hardware.org/?probe=687a37a00f) | Oct 06, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [95d81c3bb1](https://linux-hardware.org/?probe=95d81c3bb1) | Oct 06, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [6507df947b](https://linux-hardware.org/?probe=6507df947b) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [f4c0266602](https://linux-hardware.org/?probe=f4c0266602) | Oct 06, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [8978850a77](https://linux-hardware.org/?probe=8978850a77) | Oct 06, 2023 |
| System76      | Serval WS                   | Notebook    | [f8e3cd9fd0](https://linux-hardware.org/?probe=f8e3cd9fd0) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a308ec4180](https://linux-hardware.org/?probe=a308ec4180) | Oct 06, 2023 |
| HP            | Unknown                     | Convertible | [46bfa371c4](https://linux-hardware.org/?probe=46bfa371c4) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [b6caf35101](https://linux-hardware.org/?probe=b6caf35101) | Oct 05, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [ebbd23f352](https://linux-hardware.org/?probe=ebbd23f352) | Oct 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3e6f44ce5c](https://linux-hardware.org/?probe=3e6f44ce5c) | Oct 05, 2023 |
| Google        | Morphius                    | Notebook    | [735ed70d9c](https://linux-hardware.org/?probe=735ed70d9c) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [34ff66e3a9](https://linux-hardware.org/?probe=34ff66e3a9) | Oct 05, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [314a6f2edf](https://linux-hardware.org/?probe=314a6f2edf) | Oct 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [3f779c87f6](https://linux-hardware.org/?probe=3f779c87f6) | Oct 05, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [5ab40107ce](https://linux-hardware.org/?probe=5ab40107ce) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [234f939987](https://linux-hardware.org/?probe=234f939987) | Oct 04, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [8f0fc826ae](https://linux-hardware.org/?probe=8f0fc826ae) | Oct 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [1dcdef2d17](https://linux-hardware.org/?probe=1dcdef2d17) | Oct 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [eb2aacccb0](https://linux-hardware.org/?probe=eb2aacccb0) | Oct 03, 2023 |
| HP            | 0AA4h                       | Desktop     | [8e4a645689](https://linux-hardware.org/?probe=8e4a645689) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5932daaa4e](https://linux-hardware.org/?probe=5932daaa4e) | Oct 03, 2023 |
| Dell          | Latitude 7400               | Notebook    | [bd6eee3b51](https://linux-hardware.org/?probe=bd6eee3b51) | Oct 03, 2023 |
| ASRock        | Z790 PG Riptide             | Desktop     | [82630a534f](https://linux-hardware.org/?probe=82630a534f) | Oct 03, 2023 |
| Kllisre       | X79 V1.2                    | Desktop     | [fb9b29c804](https://linux-hardware.org/?probe=fb9b29c804) | Oct 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [23c850d9d3](https://linux-hardware.org/?probe=23c850d9d3) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b5965220de](https://linux-hardware.org/?probe=b5965220de) | Oct 03, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [bc03d7f758](https://linux-hardware.org/?probe=bc03d7f758) | Oct 02, 2023 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [1d315fb87d](https://linux-hardware.org/?probe=1d315fb87d) | Oct 02, 2023 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [2435f20a18](https://linux-hardware.org/?probe=2435f20a18) | Oct 02, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [a348906862](https://linux-hardware.org/?probe=a348906862) | Oct 02, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [1c681f7a14](https://linux-hardware.org/?probe=1c681f7a14) | Oct 02, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [2e57173dd9](https://linux-hardware.org/?probe=2e57173dd9) | Oct 02, 2023 |
| System76      | Lemur Pro                   | Notebook    | [8486fb3080](https://linux-hardware.org/?probe=8486fb3080) | Oct 02, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [57ddb0f758](https://linux-hardware.org/?probe=57ddb0f758) | Oct 01, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [3bb0e0c792](https://linux-hardware.org/?probe=3bb0e0c792) | Oct 01, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [d16a64a7e1](https://linux-hardware.org/?probe=d16a64a7e1) | Oct 01, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| HP            | 250 G4                      | Notebook    | [30947c6039](https://linux-hardware.org/?probe=30947c6039) | Oct 01, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [691c015f6f](https://linux-hardware.org/?probe=691c015f6f) | Oct 01, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [5f76307503](https://linux-hardware.org/?probe=5f76307503) | Oct 01, 2023 |
| Dell          | Latitude E7440              | Notebook    | [8e74ff2f99](https://linux-hardware.org/?probe=8e74ff2f99) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [12d98aba86](https://linux-hardware.org/?probe=12d98aba86) | Oct 01, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [8fabc36e1c](https://linux-hardware.org/?probe=8fabc36e1c) | Oct 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [c69ebf2472](https://linux-hardware.org/?probe=c69ebf2472) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [14fcb9ce4b](https://linux-hardware.org/?probe=14fcb9ce4b) | Sep 30, 2023 |
| HP            | Pro Tablet 608 G1           | Notebook    | [ab84386c83](https://linux-hardware.org/?probe=ab84386c83) | Sep 30, 2023 |
| HP            | 8054                        | Desktop     | [20f337b1e7](https://linux-hardware.org/?probe=20f337b1e7) | Sep 29, 2023 |
| Positivo      | C14CR01                     | Notebook    | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [55b44bb456](https://linux-hardware.org/?probe=55b44bb456) | Sep 29, 2023 |
| System76      | Darter Pro                  | Notebook    | [d8b78103d5](https://linux-hardware.org/?probe=d8b78103d5) | Sep 29, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [fb1c2503cf](https://linux-hardware.org/?probe=fb1c2503cf) | Sep 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [109490039d](https://linux-hardware.org/?probe=109490039d) | Sep 29, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [960cd34617](https://linux-hardware.org/?probe=960cd34617) | Sep 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [e23bfd302c](https://linux-hardware.org/?probe=e23bfd302c) | Sep 28, 2023 |
| AZW           | SER V1                      | Desktop     | [10660522cb](https://linux-hardware.org/?probe=10660522cb) | Sep 28, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [7269165fd9](https://linux-hardware.org/?probe=7269165fd9) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [d19f334f02](https://linux-hardware.org/?probe=d19f334f02) | Sep 28, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [2ede90f6eb](https://linux-hardware.org/?probe=2ede90f6eb) | Sep 28, 2023 |
| System76      | Oryx Pro                    | Notebook    | [f06316545d](https://linux-hardware.org/?probe=f06316545d) | Sep 28, 2023 |
| Acer          | Aspire VN7-791G             | Notebook    | [0cfe515d00](https://linux-hardware.org/?probe=0cfe515d00) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [7c13a64c8a](https://linux-hardware.org/?probe=7c13a64c8a) | Sep 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [8dd1695b2c](https://linux-hardware.org/?probe=8dd1695b2c) | Sep 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 4025      | 37.27%  |
| Pop!_OS 20.04 | 2132      | 19.74%  |
| Pop!_OS 21.04 | 1803      | 16.69%  |
| Pop!_OS 20.10 | 1652      | 15.3%   |
| Pop!_OS 21.10 | 1113      | 10.31%  |
| Pop!_OS 19.10 | 47        | 0.44%   |
| Pop!_OS 19.04 | 12        | 0.11%   |
| Pop!_OS 18.04 | 11        | 0.1%    |
| Pop!_OS 18.10 | 5         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Pop!_OS | 10263     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 839       | 7.16%   |
| 6.2.6-76060206-generic   | 835       | 7.12%   |
| 5.8.0-7630-generic       | 741       | 6.32%   |
| 5.4.0-7634-generic       | 667       | 5.69%   |
| 5.13.0-7614-generic      | 496       | 4.23%   |
| 5.8.0-7642-generic       | 482       | 4.11%   |
| 6.0.12-76060006-generic  | 477       | 4.07%   |
| 5.4.0-7642-generic       | 465       | 3.97%   |
| 5.17.5-76051705-generic  | 463       | 3.95%   |
| 5.19.0-76051900-generic  | 449       | 3.83%   |
| 5.11.0-7614-generic      | 439       | 3.75%   |
| 5.13.0-7620-generic      | 413       | 3.52%   |
| 6.5.6-76060506-generic   | 303       | 2.59%   |
| 6.0.6-76060006-generic   | 302       | 2.58%   |
| 6.4.6-76060406-generic   | 296       | 2.53%   |
| 5.15.15-76051515-generic | 280       | 2.39%   |
| 5.16.11-76051611-generic | 264       | 2.25%   |
| 5.15.5-76051505-generic  | 237       | 2.02%   |
| 5.11.0-7612-generic      | 227       | 1.94%   |
| 6.6.6-76060606-generic   | 220       | 1.88%   |
| 5.18.10-76051810-generic | 214       | 1.83%   |
| 5.8.0-7625-generic       | 196       | 1.67%   |
| 5.17.15-76051715-generic | 190       | 1.62%   |
| 5.16.19-76051619-generic | 181       | 1.54%   |
| 5.11.0-7633-generic      | 180       | 1.54%   |
| 5.15.8-76051508-generic  | 171       | 1.46%   |
| 5.16.15-76051615-generic | 151       | 1.29%   |
| 5.4.0-7626-generic       | 144       | 1.23%   |
| 6.5.4-76060504-generic   | 130       | 1.11%   |
| 6.2.0-76060200-generic   | 122       | 1.04%   |
| 5.15.11-76051511-generic | 115       | 0.98%   |
| 6.0.2-76060002-generic   | 92        | 0.78%   |
| 6.1.11-76060111-generic  | 91        | 0.78%   |
| 5.15.23-76051523-generic | 91        | 0.78%   |
| 5.4.0-7625-generic       | 74        | 0.63%   |
| 5.4.0-7629-generic       | 62        | 0.53%   |
| 5.19.16-76051916-generic | 43        | 0.37%   |
| 6.0.3-76060003-generic   | 40        | 0.34%   |
| 6.6.10-76060610-generic  | 39        | 0.33%   |
| 5.3.0-7625-generic       | 16        | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 1629      | 14.15%  |
| 5.4.0   | 1371      | 11.91%  |
| 5.8.0   | 1359      | 11.8%   |
| 5.13.0  | 911       | 7.91%   |
| 6.2.6   | 836       | 7.26%   |
| 6.0.12  | 489       | 4.25%   |
| 5.17.5  | 466       | 4.05%   |
| 5.19.0  | 453       | 3.93%   |
| 6.5.6   | 303       | 2.63%   |
| 6.0.6   | 303       | 2.63%   |
| 6.4.6   | 296       | 2.57%   |
| 5.15.15 | 281       | 2.44%   |
| 5.16.11 | 264       | 2.29%   |
| 5.15.5  | 237       | 2.06%   |
| 6.6.6   | 220       | 1.91%   |
| 5.18.10 | 214       | 1.86%   |
| 5.17.15 | 190       | 1.65%   |
| 5.16.19 | 181       | 1.57%   |
| 5.15.8  | 171       | 1.49%   |
| 5.16.15 | 151       | 1.31%   |
| 6.5.4   | 130       | 1.13%   |
| 6.2.0   | 122       | 1.06%   |
| 5.15.11 | 115       | 1%      |
| 6.0.2   | 95        | 0.83%   |
| 6.1.11  | 92        | 0.8%    |
| 5.15.23 | 91        | 0.79%   |
| 5.3.0   | 51        | 0.44%   |
| 5.19.16 | 43        | 0.37%   |
| 6.0.3   | 40        | 0.35%   |
| 6.6.10  | 39        | 0.34%   |
| 5.15.0  | 16        | 0.14%   |
| 5.0.0   | 12        | 0.1%    |
| 5.8.5   | 8         | 0.07%   |
| 5.7.0   | 8         | 0.07%   |
| 5.8.12  | 7         | 0.06%   |
| 4.18.0  | 7         | 0.06%   |
| 6.1.0   | 6         | 0.05%   |
| 5.13.12 | 6         | 0.05%   |
| 5.10.0  | 6         | 0.05%   |
| 6.3.7   | 5         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 1638      | 14.38%  |
| 5.8     | 1396      | 12.25%  |
| 5.4     | 1375      | 12.07%  |
| 6.2     | 957       | 8.4%    |
| 5.13    | 930       | 8.16%   |
| 5.15    | 907       | 7.96%   |
| 6.0     | 905       | 7.94%   |
| 5.17    | 656       | 5.76%   |
| 5.16    | 585       | 5.13%   |
| 5.19    | 498       | 4.37%   |
| 6.5     | 439       | 3.85%   |
| 6.4     | 303       | 2.66%   |
| 6.6     | 260       | 2.28%   |
| 5.18    | 221       | 1.94%   |
| 6.1     | 109       | 0.96%   |
| 5.3     | 51        | 0.45%   |
| 5.10    | 28        | 0.25%   |
| 5.7     | 27        | 0.24%   |
| 5.12    | 18        | 0.16%   |
| 6.3     | 17        | 0.15%   |
| 5.14    | 16        | 0.14%   |
| 5.9     | 15        | 0.13%   |
| 5.6     | 15        | 0.13%   |
| 5.0     | 12        | 0.11%   |
| 4.18    | 8         | 0.07%   |
| 4.15    | 3         | 0.03%   |
| 6.7     | 2         | 0.02%   |
| 5.1     | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 10242     | 99.8%   |
| aarch64 | 21        | 0.2%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 9935      | 96.28%  |
| KDE5            | 98        | 0.95%   |
| Unknown         | 71        | 0.69%   |
| KDE             | 59        | 0.57%   |
| X-Cinnamon      | 43        | 0.42%   |
| MATE            | 20        | 0.19%   |
| GNOME Flashback | 20        | 0.19%   |
| XFCE            | 17        | 0.16%   |
| Cinnamon        | 17        | 0.16%   |
| LXQt            | 12        | 0.12%   |
| Unity           | 9         | 0.09%   |
| i3              | 6         | 0.06%   |
| Budgie          | 6         | 0.06%   |
| awesome         | 2         | 0.02%   |
| UKUI            | 1         | 0.01%   |
| pop             | 1         | 0.01%   |
| Pantheon        | 1         | 0.01%   |
| Deepin          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 9947      | 96.37%  |
| Wayland | 325       | 3.15%   |
| Unknown | 35        | 0.34%   |
| Tty     | 15        | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8079      | 77.89%  |
| GDM     | 1205      | 11.62%  |
| GDM3    | 1055      | 10.17%  |
| SDDM    | 21        | 0.2%    |
| TDM     | 8         | 0.08%   |
| LightDM | 4         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 5901      | 57.01%  |
| en_GB   | 759       | 7.33%   |
| pt_BR   | 698       | 6.74%   |
| de_DE   | 508       | 4.91%   |
| C       | 342       | 3.3%    |
| en_AU   | 266       | 2.57%   |
| en_CA   | 226       | 2.18%   |
| fr_FR   | 206       | 1.99%   |
| it_IT   | 178       | 1.72%   |
| es_ES   | 160       | 1.55%   |
| ru_RU   | 133       | 1.28%   |
| pl_PL   | 93        | 0.9%    |
| Unknown | 87        | 0.84%   |
| pt_PT   | 67        | 0.65%   |
| sv_SE   | 64        | 0.62%   |
| nl_NL   | 58        | 0.56%   |
| en_IN   | 46        | 0.44%   |
| fi_FI   | 36        | 0.35%   |
| nb_NO   | 33        | 0.32%   |
| en_ZA   | 29        | 0.28%   |
| es_MX   | 28        | 0.27%   |
| tr_TR   | 27        | 0.26%   |
| en_NZ   | 27        | 0.26%   |
| fr_CA   | 25        | 0.24%   |
| es_AR   | 25        | 0.24%   |
| en_DK   | 23        | 0.22%   |
| da_DK   | 21        | 0.2%    |
| es_CL   | 19        | 0.18%   |
| cs_CZ   | 18        | 0.17%   |
| de_CH   | 16        | 0.15%   |
| ja_JP   | 15        | 0.14%   |
| hu_HU   | 15        | 0.14%   |
| sk_SK   | 14        | 0.14%   |
| en_IE   | 14        | 0.14%   |
| nl_BE   | 13        | 0.13%   |
| de_AT   | 13        | 0.13%   |
| zh_TW   | 12        | 0.12%   |
| hr_HR   | 12        | 0.12%   |
| zh_CN   | 10        | 0.1%    |
| ro_RO   | 9         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 7639      | 73.43%  |
| EFI  | 2764      | 26.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 9834      | 95.43%  |
| Btrfs   | 234       | 2.27%   |
| Overlay | 182       | 1.77%   |
| Xfs     | 31        | 0.3%    |
| Unknown | 13        | 0.13%   |
| Zfs     | 9         | 0.09%   |
| Tmpfs   | 1         | 0.01%   |
| Ext2    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8022      | 77.5%   |
| GPT     | 2117      | 20.45%  |
| MBR     | 212       | 2.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9998      | 97.04%  |
| Yes       | 305       | 2.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9336      | 90.48%  |
| Yes       | 982       | 9.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1804      | 17.58%  |
| Lenovo                  | 1397      | 13.61%  |
| Dell                    | 1329      | 12.95%  |
| Hewlett-Packard         | 1112      | 10.84%  |
| MSI                     | 783       | 7.63%   |
| Gigabyte Technology     | 765       | 7.45%   |
| Acer                    | 481       | 4.69%   |
| Apple                   | 459       | 4.47%   |
| ASRock                  | 378       | 3.68%   |
| System76                | 241       | 2.35%   |
| Intel                   | 137       | 1.33%   |
| Toshiba                 | 109       | 1.06%   |
| Samsung Electronics     | 108       | 1.05%   |
| HUAWEI                  | 70        | 0.68%   |
| Alienware               | 63        | 0.61%   |
| Notebook                | 54        | 0.53%   |
| Microsoft               | 54        | 0.53%   |
| Sony                    | 51        | 0.5%    |
| Fujitsu                 | 49        | 0.48%   |
| Google                  | 48        | 0.47%   |
| Unknown                 | 48        | 0.47%   |
| Positivo                | 43        | 0.42%   |
| Pegatron                | 28        | 0.27%   |
| Razer                   | 27        | 0.26%   |
| Medion                  | 22        | 0.21%   |
| Biostar                 | 22        | 0.21%   |
| Raspberry Pi Foundation | 21        | 0.2%    |
| Supermicro              | 20        | 0.19%   |
| Timi                    | 19        | 0.19%   |
| Foxconn                 | 19        | 0.19%   |
| PC Specialist           | 18        | 0.18%   |
| LG Electronics          | 16        | 0.16%   |
| Framework               | 15        | 0.15%   |
| ECS                     | 15        | 0.15%   |
| TUXEDO                  | 14        | 0.14%   |
| Packard Bell            | 14        | 0.14%   |
| Gateway                 | 14        | 0.14%   |
| AZW                     | 14        | 0.14%   |
| Huanan                  | 13        | 0.13%   |
| GPU Company             | 13        | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUS All Series                | 96        | 0.94%   |
| Unknown                        | 65        | 0.63%   |
| System76 Oryx Pro              | 48        | 0.47%   |
| ASUS TUF Gaming X570-PLUS      | 44        | 0.43%   |
| System76 Lemur Pro             | 41        | 0.4%    |
| Gigabyte B450M DS3H            | 34        | 0.33%   |
| Dell XPS 15 7590               | 34        | 0.33%   |
| MSI MS-7C02                    | 33        | 0.32%   |
| ASUS ROG STRIX B550-F GAMING   | 32        | 0.31%   |
| ASUS ROG STRIX B450-F GAMING   | 31        | 0.3%    |
| MSI MS-7C37                    | 30        | 0.29%   |
| System76 Gazelle               | 29        | 0.28%   |
| MSI MS-7B86                    | 29        | 0.28%   |
| Apple MacBookPro9,2            | 27        | 0.26%   |
| Apple MacBookPro8,1            | 27        | 0.26%   |
| Dell OptiPlex 9020             | 25        | 0.24%   |
| ASUS PRIME B450M-A             | 24        | 0.23%   |
| System76 Galago Pro            | 23        | 0.22%   |
| Apple MacBookPro12,1           | 23        | 0.22%   |
| Dell XPS 15 9500               | 22        | 0.21%   |
| Apple MacBookAir7,2            | 22        | 0.21%   |
| System76 Thelio                | 21        | 0.2%    |
| System76 Darter Pro            | 21        | 0.2%    |
| HP Notebook                    | 21        | 0.2%    |
| Gigabyte X570 AORUS ELITE      | 21        | 0.2%    |
| HP Pavilion Notebook           | 20        | 0.19%   |
| Apple MacBookAir6,2            | 20        | 0.19%   |
| Gigabyte A320M-S2H             | 19        | 0.19%   |
| Dell OptiPlex 7010             | 19        | 0.19%   |
| HP Pavilion 15                 | 18        | 0.18%   |
| MSI MS-7C91                    | 17        | 0.17%   |
| Dell XPS 15 9570               | 17        | 0.17%   |
| ASRock B450M Pro4              | 17        | 0.17%   |
| RPi Raspberry Pi               | 16        | 0.16%   |
| HP Pavilion dv6                | 16        | 0.16%   |
| Dell XPS 15 9560               | 16        | 0.16%   |
| ASRock B450M Steel Legend      | 16        | 0.16%   |
| Apple MacBookPro7,1            | 16        | 0.16%   |
| Dell Latitude E6420            | 15        | 0.15%   |
| Lenovo IdeaPad S145-15API 81V7 | 14        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 586       | 5.71%   |
| ASUS ROG           | 372       | 3.62%   |
| Dell Inspiron      | 365       | 3.56%   |
| Lenovo IdeaPad     | 321       | 3.13%   |
| Acer Aspire        | 318       | 3.1%    |
| Dell Latitude      | 257       | 2.5%    |
| Dell XPS           | 238       | 2.32%   |
| ASUS PRIME         | 211       | 2.06%   |
| HP Pavilion        | 204       | 1.99%   |
| ASUS TUF           | 174       | 1.7%    |
| Dell OptiPlex      | 163       | 1.59%   |
| HP EliteBook       | 130       | 1.27%   |
| Dell Precision     | 124       | 1.21%   |
| ASUS VivoBook      | 118       | 1.15%   |
| HP Laptop          | 115       | 1.12%   |
| Lenovo Legion      | 96        | 0.94%   |
| ASUS All           | 96        | 0.94%   |
| Toshiba Satellite  | 93        | 0.91%   |
| HP ProBook         | 91        | 0.89%   |
| HP ENVY            | 86        | 0.84%   |
| Lenovo Yoga        | 83        | 0.81%   |
| Gigabyte X570      | 79        | 0.77%   |
| HP Compaq          | 78        | 0.76%   |
| Dell Vostro        | 67        | 0.65%   |
| Unknown            | 65        | 0.63%   |
| Lenovo ThinkCentre | 62        | 0.6%    |
| ASUS ASUS          | 60        | 0.58%   |
| Acer Nitro         | 58        | 0.57%   |
| Gigabyte B450      | 55        | 0.54%   |
| Microsoft Surface  | 54        | 0.53%   |
| Gigabyte B450M     | 51        | 0.5%    |
| System76 Oryx      | 48        | 0.47%   |
| HP OMEN            | 47        | 0.46%   |
| ASUS ZenBook       | 47        | 0.46%   |
| Apple MacBookPro11 | 45        | 0.44%   |
| Acer Swift         | 45        | 0.44%   |
| System76 Lemur     | 44        | 0.43%   |
| ASRock B450M       | 40        | 0.39%   |
| ASRock X570        | 38        | 0.37%   |
| System76 Thelio    | 36        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1226      | 11.95%  |
| 2020    | 1198      | 11.67%  |
| 2018    | 1174      | 11.44%  |
| 2021    | 897       | 8.74%   |
| 2012    | 722       | 7.03%   |
| 2017    | 690       | 6.72%   |
| 2013    | 638       | 6.22%   |
| 2011    | 584       | 5.69%   |
| 2014    | 539       | 5.25%   |
| 2015    | 509       | 4.96%   |
| 2016    | 483       | 4.71%   |
| 2022    | 454       | 4.42%   |
| 2010    | 358       | 3.49%   |
| 2009    | 270       | 2.63%   |
| 2008    | 215       | 2.09%   |
| 2023    | 136       | 1.33%   |
| 2007    | 123       | 1.2%    |
| 2006    | 22        | 0.21%   |
| Unknown | 22        | 0.21%   |
| 2005    | 2         | 0.02%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 5660      | 55.15%  |
| Desktop        | 3865      | 37.66%  |
| Convertible    | 283       | 2.76%   |
| Mini pc        | 141       | 1.37%   |
| All in one     | 134       | 1.31%   |
| Tablet         | 120       | 1.17%   |
| Server         | 37        | 0.36%   |
| System on chip | 22        | 0.21%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 10256     | 99.91%  |
| Enabled  | 9         | 0.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 10083     | 98.25%  |
| Yes  | 180       | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 2701      | 25.96%  |
| 4.01-8.0        | 2228      | 21.41%  |
| 8.01-16.0       | 1913      | 18.38%  |
| 32.01-64.0      | 1505      | 14.46%  |
| 3.01-4.0        | 1207      | 11.6%   |
| 64.01-256.0     | 437       | 4.2%    |
| 24.01-32.0      | 235       | 2.26%   |
| 1.01-2.0        | 121       | 1.16%   |
| 2.01-3.0        | 48        | 0.46%   |
| More than 256.0 | 10        | 0.1%    |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 3156      | 28.02%  |
| 4.01-8.0    | 2661      | 23.62%  |
| 1.01-2.0    | 2435      | 21.62%  |
| 3.01-4.0    | 2102      | 18.66%  |
| 8.01-16.0   | 732       | 6.5%    |
| 16.01-24.0  | 98        | 0.87%   |
| 24.01-32.0  | 33        | 0.29%   |
| 0.51-1.0    | 22        | 0.2%    |
| 32.01-64.0  | 20        | 0.18%   |
| 64.01-256.0 | 4         | 0.04%   |
| 0.01-0.5    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 5870      | 55.8%   |
| 2      | 2838      | 26.98%  |
| 3      | 935       | 8.89%   |
| 4      | 462       | 4.39%   |
| 5      | 192       | 1.83%   |
| 6      | 85        | 0.81%   |
| 0      | 59        | 0.56%   |
| 7      | 37        | 0.35%   |
| 8      | 13        | 0.12%   |
| 11     | 9         | 0.09%   |
| 9      | 9         | 0.09%   |
| 10     | 3         | 0.03%   |
| 26     | 1         | 0.01%   |
| 23     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |
| 13     | 1         | 0.01%   |
| 12     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 7449      | 72.22%  |
| Yes       | 2866      | 27.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8696      | 84.37%  |
| No        | 1611      | 15.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8357      | 81.07%  |
| No        | 1951      | 18.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7027      | 67.82%  |
| No        | 3335      | 32.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 3117      | 30.22%  |
| Brazil       | 948       | 9.19%   |
| Germany      | 715       | 6.93%   |
| UK           | 511       | 4.95%   |
| Canada       | 446       | 4.32%   |
| Australia    | 312       | 3.02%   |
| Italy        | 292       | 2.83%   |
| India        | 291       | 2.82%   |
| France       | 267       | 2.59%   |
| Netherlands  | 224       | 2.17%   |
| Russia       | 179       | 1.74%   |
| Sweden       | 177       | 1.72%   |
| Poland       | 165       | 1.6%    |
| Spain        | 147       | 1.43%   |
| Portugal     | 116       | 1.12%   |
| Mexico       | 116       | 1.12%   |
| Switzerland  | 99        | 0.96%   |
| Norway       | 99        | 0.96%   |
| Finland      | 95        | 0.92%   |
| South Africa | 93        | 0.9%    |
| Romania      | 90        | 0.87%   |
| Austria      | 79        | 0.77%   |
| Philippines  | 72        | 0.7%    |
| New Zealand  | 72        | 0.7%    |
| Denmark      | 72        | 0.7%    |
| Belgium      | 71        | 0.69%   |
| Argentina    | 70        | 0.68%   |
| Turkey       | 68        | 0.66%   |
| Greece       | 67        | 0.65%   |
| Indonesia    | 63        | 0.61%   |
| Czechia      | 61        | 0.59%   |
| Chile        | 52        | 0.5%    |
| Japan        | 49        | 0.48%   |
| Hungary      | 46        | 0.45%   |
| Bulgaria     | 46        | 0.45%   |
| Ireland      | 43        | 0.42%   |
| Malaysia     | 39        | 0.38%   |
| Serbia       | 38        | 0.37%   |
| Croatia      | 37        | 0.36%   |
| Ukraine      | 35        | 0.34%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 112       | 1.04%   |
| Sydney         | 82        | 0.76%   |
| Melbourne      | 68        | 0.63%   |
| Berlin         | 60        | 0.56%   |
| Rio de Janeiro | 59        | 0.55%   |
| Brisbane       | 54        | 0.5%    |
| Milan          | 52        | 0.48%   |
| Helsinki       | 52        | 0.48%   |
| Vienna         | 48        | 0.44%   |
| Warsaw         | 46        | 0.43%   |
| Moscow         | 44        | 0.41%   |
| New York       | 43        | 0.4%    |
| London         | 43        | 0.4%    |
| Denver         | 43        | 0.4%    |
| Dallas         | 42        | 0.39%   |
| Chicago        | 42        | 0.39%   |
| Bengaluru      | 42        | 0.39%   |
| Amsterdam      | 38        | 0.35%   |
| Toronto        | 37        | 0.34%   |
| Rome           | 35        | 0.32%   |
| Paris          | 35        | 0.32%   |
| Madrid         | 35        | 0.32%   |
| Seattle        | 34        | 0.32%   |
| Auckland       | 34        | 0.32%   |
| Athens         | 34        | 0.32%   |
| Sofia          | 32        | 0.3%    |
| Bucharest      | 32        | 0.3%    |
| Montreal       | 31        | 0.29%   |
| Los Angeles    | 31        | 0.29%   |
| Zurich         | 30        | 0.28%   |
| Stockholm      | 30        | 0.28%   |
| Miami          | 30        | 0.28%   |
| Istanbul       | 30        | 0.28%   |
| Edmonton       | 30        | 0.28%   |
| Lisbon         | 29        | 0.27%   |
| Johannesburg   | 29        | 0.27%   |
| Calgary        | 29        | 0.27%   |
| Oslo           | 28        | 0.26%   |
| Hamburg        | 28        | 0.26%   |
| Brasília      | 28        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2885      | 4421   | 18.24%  |
| Seagate                     | 2019      | 2916   | 12.77%  |
| WDC                         | 2017      | 2816   | 12.76%  |
| SanDisk                     | 1080      | 1434   | 6.83%   |
| Kingston                    | 878       | 1108   | 5.55%   |
| Toshiba                     | 805       | 996    | 5.09%   |
| Crucial                     | 634       | 834    | 4.01%   |
| Unknown                     | 491       | 648    | 3.11%   |
| SK hynix                    | 463       | 590    | 2.93%   |
| Intel                       | 443       | 593    | 2.8%    |
| Hitachi                     | 305       | 397    | 1.93%   |
| Micron Technology           | 282       | 336    | 1.78%   |
| HGST                        | 260       | 314    | 1.64%   |
| Phison                      | 241       | 333    | 1.52%   |
| A-DATA Technology           | 234       | 289    | 1.48%   |
| Apple                       | 226       | 263    | 1.43%   |
| Micron/Crucial Technology   | 158       | 212    | 1%      |
| China                       | 158       | 211    | 1%      |
| PNY                         | 147       | 183    | 0.93%   |
| Silicon Motion              | 141       | 186    | 0.89%   |
| KIOXIA                      | 100       | 115    | 0.63%   |
| Phison Electronics          | 97        | 134    | 0.61%   |
| SPCC                        | 70        | 95     | 0.44%   |
| OCZ                         | 63        | 82     | 0.4%    |
| LITEON                      | 62        | 74     | 0.39%   |
| Kingston Technology Company | 60        | 72     | 0.38%   |
| Transcend                   | 59        | 67     | 0.37%   |
| Team                        | 57        | 68     | 0.36%   |
| XPG                         | 52        | 68     | 0.33%   |
| Realtek Semiconductor       | 50        | 57     | 0.32%   |
| Patriot                     | 50        | 67     | 0.32%   |
| Corsair                     | 48        | 63     | 0.3%    |
| JMicron Technology          | 44        | 63     | 0.28%   |
| LITEONIT                    | 42        | 61     | 0.27%   |
| ADATA Technology            | 42        | 54     | 0.27%   |
| Intenso                     | 41        | 54     | 0.26%   |
| Unknown                     | 36        | 41     | 0.23%   |
| Netac                       | 35        | 41     | 0.22%   |
| Maxtor                      | 35        | 36     | 0.22%   |
| KingSpec                    | 35        | 41     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 224       | 1.28%   |
| Samsung NVMe SSD Drive 1TB                         | 197       | 1.13%   |
| Samsung NVMe SSD Drive 500GB                       | 178       | 1.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 164       | 0.94%   |
| Samsung SSD 850 EVO 250GB                          | 140       | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB                     | 138       | 0.79%   |
| Samsung SSD 860 EVO 500GB                          | 125       | 0.71%   |
| Samsung SSD 850 EVO 500GB                          | 125       | 0.71%   |
| SanDisk NVMe SSD Drive 1TB                         | 119       | 0.68%   |
| Samsung NVMe SSD Drive 512GB                       | 118       | 0.67%   |
| Samsung SSD 860 EVO 1TB                            | 116       | 0.66%   |
| Unknown MMC Card  64GB                             | 112       | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB                     | 110       | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 105       | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                     | 104       | 0.59%   |
| Kingston SA400S37120G 120GB SSD                    | 102       | 0.58%   |
| Kingston SA400S37480G 480GB SSD                    | 100       | 0.57%   |
| SanDisk NVMe SSD Drive 500GB                       | 97        | 0.55%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 91        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                        | 89        | 0.51%   |
| HGST HTS721010A9E630 1TB                           | 88        | 0.5%    |
| Toshiba MQ01ABD100 1TB                             | 86        | 0.49%   |
| Seagate ST500DM002-1BD142 500GB                    | 86        | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 85        | 0.49%   |
| Crucial CT500MX500SSD1 500GB                       | 82        | 0.47%   |
| Unknown MMC Card  32GB                             | 79        | 0.45%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB             | 74        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 73        | 0.42%   |
| SanDisk NVMe SSD Drive 512GB                       | 73        | 0.42%   |
| Crucial CT240BX500SSD1 240GB                       | 72        | 0.41%   |
| Intel NVMe SSD Drive 512GB                         | 69        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB                       | 65        | 0.37%   |
| SK hynix NVMe SSD Drive 512GB                      | 61        | 0.35%   |
| Seagate Expansion 1TB                              | 60        | 0.34%   |
| Samsung NVMe SSD Drive 2TB                         | 59        | 0.34%   |
| Unknown MMC Card  128GB                            | 58        | 0.33%   |
| Toshiba MQ04ABF100 1TB                             | 58        | 0.33%   |
| Samsung NVMe SSD Drive 1024GB                      | 58        | 0.33%   |
| Unknown SD/MMC/MS PRO 256GB                        | 56        | 0.32%   |
| Samsung SSD 860 EVO 250GB                          | 56        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1953      | 2768   | 38.67%  |
| WDC                 | 1522      | 2124   | 30.14%  |
| Toshiba             | 575       | 696    | 11.39%  |
| Hitachi             | 305       | 397    | 6.04%   |
| HGST                | 260       | 314    | 5.15%   |
| Samsung Electronics | 162       | 189    | 3.21%   |
| Unknown             | 60        | 72     | 1.19%   |
| Apple               | 57        | 70     | 1.13%   |
| JMicron Technology  | 29        | 43     | 0.57%   |
| Maxtor              | 27        | 28     | 0.53%   |
| Fujitsu             | 25        | 30     | 0.5%    |
| TO Exter            | 14        | 17     | 0.28%   |
| External            | 8         | 8      | 0.16%   |
| ASMT                | 8         | 10     | 0.16%   |
| SABRENT             | 4         | 6      | 0.08%   |
| StoreJet            | 3         | 3      | 0.06%   |
| Intenso             | 3         | 7      | 0.06%   |
| Hewlett-Packard     | 3         | 5      | 0.06%   |
| ExcelStor           | 3         | 3      | 0.06%   |
| USB                 | 2         | 3      | 0.04%   |
| RSH-339             | 2         | 2      | 0.04%   |
| MaxDigital          | 2         | 2      | 0.04%   |
| Magnetic Data       | 2         | 2      | 0.04%   |
| LaCie               | 2         | 3      | 0.04%   |
| HGST HTS            | 2         | 2      | 0.04%   |
| Unknown             | 2         | 3      | 0.04%   |
| XrayDisk            | 1         | 1      | 0.02%   |
| WD MediaMax         | 1         | 2      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| OEM                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| Inateck             | 1         | 1      | 0.02%   |
| HPE                 | 1         | 1      | 0.02%   |
| HGST HDN            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Glyph               | 1         | 2      | 0.02%   |
| DELLBOSS            | 1         | 1      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| ASMT109x            | 1         | 1      | 0.02%   |
| ASMedia             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1316      | 1942   | 24.18%  |
| Kingston            | 701       | 866    | 12.88%  |
| Crucial             | 576       | 754    | 10.58%  |
| SanDisk             | 491       | 627    | 9.02%   |
| WDC                 | 354       | 446    | 6.5%    |
| A-DATA Technology   | 182       | 224    | 3.34%   |
| China               | 157       | 210    | 2.88%   |
| PNY                 | 143       | 179    | 2.63%   |
| Apple               | 143       | 155    | 2.63%   |
| Intel               | 119       | 150    | 2.19%   |
| SK hynix            | 101       | 126    | 1.86%   |
| Micron Technology   | 91        | 101    | 1.67%   |
| Toshiba             | 77        | 90     | 1.41%   |
| SPCC                | 63        | 79     | 1.16%   |
| OCZ                 | 62        | 78     | 1.14%   |
| Transcend           | 56        | 64     | 1.03%   |
| LITEON              | 56        | 68     | 1.03%   |
| Patriot             | 49        | 66     | 0.9%    |
| Team                | 46        | 56     | 0.85%   |
| LITEONIT            | 42        | 61     | 0.77%   |
| Corsair             | 37        | 45     | 0.68%   |
| KingSpec            | 35        | 41     | 0.64%   |
| Seagate             | 34        | 50     | 0.62%   |
| Netac               | 29        | 34     | 0.53%   |
| Intenso             | 28        | 36     | 0.51%   |
| Lexar               | 27        | 31     | 0.5%    |
| Hewlett-Packard     | 25        | 33     | 0.46%   |
| Apacer              | 22        | 31     | 0.4%    |
| SABRENT             | 19        | 22     | 0.35%   |
| Gigabyte Technology | 17        | 19     | 0.31%   |
| GOODRAM             | 16        | 18     | 0.29%   |
| KingDian            | 15        | 25     | 0.28%   |
| Plextor             | 13        | 17     | 0.24%   |
| Mushkin             | 13        | 16     | 0.24%   |
| Dogfish             | 12        | 17     | 0.22%   |
| ASMT                | 12        | 18     | 0.22%   |
| OWC                 | 9         | 18     | 0.17%   |
| Maxtor              | 8         | 8      | 0.15%   |
| KIOXIA-EXCERIA      | 8         | 9      | 0.15%   |
| Unknown             | 7         | 7      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 4700      | 7113   | 33.32%  |
| NVMe    | 4468      | 6711   | 31.68%  |
| HDD     | 4298      | 6828   | 30.47%  |
| MMC     | 378       | 468    | 2.68%   |
| Unknown | 260       | 396    | 1.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 7124      | 13367  | 56.58%  |
| NVMe | 4462      | 6688   | 35.44%  |
| SAS  | 626       | 993    | 4.97%   |
| MMC  | 378       | 468    | 3%      |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 5162      | 7733   | 54.86%  |
| 0.51-1.0        | 2879      | 4044   | 30.6%   |
| 1.01-2.0        | 785       | 1153   | 8.34%   |
| 3.01-4.0        | 235       | 399    | 2.5%    |
| 4.01-10.0       | 172       | 323    | 1.83%   |
| 2.01-3.0        | 153       | 235    | 1.63%   |
| 10.01-20.0      | 23        | 53     | 0.24%   |
| More than 100.0 | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3109      | 29.06%  |
| 251-500        | 2662      | 24.89%  |
| 501-1000       | 2033      | 19.01%  |
| 1001-2000      | 1006      | 9.4%    |
| More than 3000 | 528       | 4.94%   |
| 51-100         | 468       | 4.38%   |
| 2001-3000      | 348       | 3.25%   |
| 1-20           | 254       | 2.37%   |
| 21-50          | 218       | 2.04%   |
| Unknown        | 71        | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3961      | 35.32%  |
| 21-50          | 2292      | 20.44%  |
| 101-250        | 1443      | 12.87%  |
| 51-100         | 1339      | 11.94%  |
| 251-500        | 882       | 7.86%   |
| 501-1000       | 586       | 5.23%   |
| 1001-2000      | 336       | 3%      |
| More than 3000 | 192       | 1.71%   |
| 2001-3000      | 113       | 1.01%   |
| Unknown        | 71        | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 7         | 7      | 2.22%   |
| HGST HTS725050A7E630 500GB               | 6         | 9      | 1.9%    |
| Seagate ST1000LM035-1RK172 1TB           | 5         | 5      | 1.58%   |
| HGST HTS721010A9E630 1TB                 | 5         | 5      | 1.58%   |
| HGST HTS541010A9E680 1TB                 | 5         | 5      | 1.58%   |
| Seagate ST500LT012-9WS142 500GB          | 4         | 5      | 1.27%   |
| Seagate ST500DM002-1BD142 500GB          | 4         | 4      | 1.27%   |
| Seagate ST1000LX015-1U7172 1TB           | 4         | 4      | 1.27%   |
| Crucial CT525MX300SSD1 528GB             | 4         | 4      | 1.27%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 3         | 3      | 0.95%   |
| SK hynix PC711 HFS001TDE9X073N 1TB       | 3         | 3      | 0.95%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 0.95%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 3         | 3      | 0.95%   |
| Seagate ST1500DL003-9VT16L 1TB           | 3         | 4      | 0.95%   |
| Seagate ST1000DM003-9YN162 1TB           | 3         | 3      | 0.95%   |
| Samsung Electronics HD502HI 500GB        | 3         | 4      | 0.95%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 5      | 0.95%   |
| Kingston SA400S37120G 120GB SSD          | 3         | 5      | 0.95%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 0.95%   |
| Crucial CT1000P1SSD8 1TB                 | 3         | 3      | 0.95%   |
| WDC WD3200AAKS-75B3A0 320GB              | 2         | 2      | 0.63%   |
| WDC WD10JPVX-60JC3T0 1TB                 | 2         | 2      | 0.63%   |
| WDC WD10EZEX-60WN4A0 1TB                 | 2         | 2      | 0.63%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 2         | 3      | 0.63%   |
| WDC WD1002FAEX-00Z3A0 1TB                | 2         | 2      | 0.63%   |
| Toshiba MQ01ABD100 1TB                   | 2         | 2      | 0.63%   |
| Toshiba MK7559GSXP 752GB                 | 2         | 2      | 0.63%   |
| Toshiba HDWD110 1TB                      | 2         | 2      | 0.63%   |
| SK hynix HFS128G39TND-N210A 128GB SSD    | 2         | 2      | 0.63%   |
| Seagate ST9750420AS 752GB                | 2         | 2      | 0.63%   |
| Seagate ST9500325AS 500GB                | 2         | 3      | 0.63%   |
| Seagate ST9320325AS 320GB                | 2         | 2      | 0.63%   |
| Seagate ST3250310AS 250GB                | 2         | 4      | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB           | 2         | 2      | 0.63%   |
| Seagate ST1000LM049-2GH172 1TB           | 2         | 2      | 0.63%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 0.63%   |
| Samsung Electronics SSD 970 EVO Plus 1TB | 2         | 2      | 0.63%   |
| Samsung Electronics SSD 850 EVO 500GB    | 2         | 2      | 0.63%   |
| Samsung Electronics SSD 850 EVO 250GB    | 2         | 2      | 0.63%   |
| Samsung Electronics HD103SJ 1TB          | 2         | 2      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 75        | 86     | 24.27%  |
| WDC                         | 66        | 79     | 21.36%  |
| Samsung Electronics         | 32        | 39     | 10.36%  |
| HGST                        | 21        | 24     | 6.8%    |
| Toshiba                     | 20        | 21     | 6.47%   |
| Kingston                    | 13        | 17     | 4.21%   |
| Hitachi                     | 13        | 16     | 4.21%   |
| SK hynix                    | 11        | 13     | 3.56%   |
| Crucial                     | 10        | 10     | 3.24%   |
| Intel                       | 8         | 8      | 2.59%   |
| A-DATA Technology           | 7         | 7      | 2.27%   |
| Micron Technology           | 6         | 8      | 1.94%   |
| SanDisk                     | 5         | 5      | 1.62%   |
| China                       | 3         | 3      | 0.97%   |
| Team                        | 2         | 2      | 0.65%   |
| LITEON                      | 2         | 2      | 0.65%   |
| Apple                       | 2         | 2      | 0.65%   |
| SPCC                        | 1         | 1      | 0.32%   |
| Silicon Motion              | 1         | 1      | 0.32%   |
| SABRENT                     | 1         | 1      | 0.32%   |
| S3+                         | 1         | 1      | 0.32%   |
| Plextor                     | 1         | 1      | 0.32%   |
| Maxtor                      | 1         | 1      | 0.32%   |
| Lexar                       | 1         | 1      | 0.32%   |
| Leven                       | 1         | 1      | 0.32%   |
| Kingston Technology Company | 1         | 1      | 0.32%   |
| Intenso                     | 1         | 1      | 0.32%   |
| Flashwar                    | 1         | 1      | 0.32%   |
| BAITITON                    | 1         | 1      | 0.32%   |
| ASMT                        | 1         | 1      | 0.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 75        | 86     | 37.13%  |
| WDC                 | 62        | 75     | 30.69%  |
| HGST                | 21        | 24     | 10.4%   |
| Toshiba             | 17        | 17     | 8.42%   |
| Hitachi             | 13        | 16     | 6.44%   |
| Samsung Electronics | 11        | 12     | 5.45%   |
| Apple               | 2         | 2      | 0.99%   |
| Maxtor              | 1         | 1      | 0.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 190       | 233    | 63.76%  |
| SSD  | 77        | 89     | 25.84%  |
| NVMe | 31        | 33     | 10.4%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 16.67%  |
| Seagate ST3500418ASQ 500GB        | 1         | 1      | 16.67%  |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 16.67%  |
| Patriot Pyro SSD 120GB            | 1         | 2      | 16.67%  |
| KingDian S400 120GB               | 1         | 2      | 16.67%  |
| Intenso JAJP600M1TB               | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 33.33%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Patriot             | 1         | 2      | 16.67%  |
| KingDian            | 1         | 2      | 16.67%  |
| Intenso             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 8190      | 17341  | 75.97%  |
| Works    | 2295      | 3811   | 21.29%  |
| Malfunc  | 288       | 355    | 2.67%   |
| Failed   | 6         | 8      | 0.06%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6176      | 43.51%  |
| AMD                              | 2517      | 17.73%  |
| Samsung Electronics              | 1765      | 12.44%  |
| SanDisk                          | 772       | 5.44%   |
| SK hynix                         | 362       | 2.55%   |
| Phison Electronics               | 352       | 2.48%   |
| Kingston Technology Company      | 240       | 1.69%   |
| ASMedia Technology               | 238       | 1.68%   |
| Micron/Crucial Technology        | 211       | 1.49%   |
| Micron Technology                | 194       | 1.37%   |
| Toshiba America Info Systems     | 174       | 1.23%   |
| Nvidia                           | 171       | 1.2%    |
| Silicon Motion                   | 161       | 1.13%   |
| ADATA Technology                 | 128       | 0.9%    |
| Marvell Technology Group         | 126       | 0.89%   |
| KIOXIA                           | 101       | 0.71%   |
| JMicron Technology               | 92        | 0.65%   |
| Realtek Semiconductor            | 69        | 0.49%   |
| Solid State Storage Technology   | 48        | 0.34%   |
| Union Memory (Shenzhen)          | 41        | 0.29%   |
| Seagate Technology               | 31        | 0.22%   |
| Broadcom / LSI                   | 31        | 0.22%   |
| Apple                            | 28        | 0.2%    |
| LSI Logic / Symbios Logic        | 22        | 0.16%   |
| Lite-On Technology               | 19        | 0.13%   |
| Shenzhen Longsys Electronics     | 17        | 0.12%   |
| MAXIO Technology (Hangzhou)      | 14        | 0.1%    |
| VIA Technologies                 | 12        | 0.08%   |
| Silicon Integrated Systems [SiS] | 10        | 0.07%   |
| Solidigm                         | 9         | 0.06%   |
| INNOGRIT                         | 9         | 0.06%   |
| Hewlett-Packard                  | 8         | 0.06%   |
| Silicon Image                    | 7         | 0.05%   |
| Lenovo                           | 7         | 0.05%   |
| Adaptec                          | 6         | 0.04%   |
| Netac Technology                 | 4         | 0.03%   |
| Yangtze Memory Technologies      | 3         | 0.02%   |
| Transcend                        | 3         | 0.02%   |
| HighPoint Technologies           | 3         | 0.02%   |
| OCZ Technology Group             | 2         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1813      | 11.36%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 937       | 5.87%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 498       | 3.12%   |
| AMD 400 Series Chipset SATA Controller                                         | 487       | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 423       | 2.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 387       | 2.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 365       | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 321       | 2.01%   |
| AMD 500 Series Chipset SATA Controller                                         | 281       | 1.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 268       | 1.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 267       | 1.67%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 250       | 1.57%   |
| Intel Volume Management Device NVMe RAID Controller                            | 243       | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 242       | 1.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 226       | 1.42%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 225       | 1.41%   |
| Intel SATA Controller [RAID mode]                                              | 205       | 1.28%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 199       | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 195       | 1.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 189       | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 187       | 1.17%   |
| Phison E12 NVMe Controller                                                     | 171       | 1.07%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 163       | 1.02%   |
| Intel SSD 660P Series                                                          | 163       | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 162       | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 161       | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 153       | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 150       | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 149       | 0.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 135       | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 129       | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 127       | 0.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 125       | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 124       | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 105       | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 103       | 0.65%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 102       | 0.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 101       | 0.63%   |
| AMD 300 Series Chipset SATA Controller                                         | 91        | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 90        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 7604      | 54.86%  |
| NVMe | 4460      | 32.18%  |
| RAID | 931       | 6.72%   |
| IDE  | 805       | 5.81%   |
| SAS  | 44        | 0.32%   |
| SCSI | 16        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 7205      | 70.2%   |
| AMD    | 3037      | 29.59%  |
| ARM    | 21        | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 159       | 1.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 140       | 1.36%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 124       | 1.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 118       | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 117       | 1.14%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 110       | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 107       | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 102       | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 93        | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 91        | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 83        | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 82        | 0.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 82        | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 80        | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 79        | 0.77%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 76        | 0.74%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 75        | 0.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 74        | 0.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 68        | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 65        | 0.63%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 65        | 0.63%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 64        | 0.62%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 62        | 0.6%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 62        | 0.6%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 59        | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 58        | 0.56%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 57        | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 56        | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 55        | 0.53%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 54        | 0.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 51        | 0.5%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 51        | 0.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 50        | 0.49%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 50        | 0.49%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 48        | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 47        | 0.46%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 47        | 0.46%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 46        | 0.45%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 46        | 0.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 46        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 2378      | 23.13%  |
| Intel Core i5           | 2217      | 21.56%  |
| AMD Ryzen 5             | 981       | 9.54%   |
| AMD Ryzen 7             | 794       | 7.72%   |
| Other                   | 781       | 7.6%    |
| Intel Core i3           | 557       | 5.42%   |
| AMD Ryzen 9             | 310       | 3.02%   |
| Intel Core 2 Duo        | 275       | 2.67%   |
| Intel Celeron           | 256       | 2.49%   |
| Intel Xeon              | 225       | 2.19%   |
| AMD FX                  | 142       | 1.38%   |
| AMD Ryzen 3             | 137       | 1.33%   |
| Intel Pentium           | 122       | 1.19%   |
| Intel Core i9           | 120       | 1.17%   |
| AMD A8                  | 69        | 0.67%   |
| AMD A6                  | 69        | 0.67%   |
| Intel Pentium Dual-Core | 65        | 0.63%   |
| Intel Atom              | 64        | 0.62%   |
| AMD A10                 | 64        | 0.62%   |
| AMD Ryzen 7 PRO         | 54        | 0.53%   |
| Intel Core 2 Quad       | 52        | 0.51%   |
| AMD Ryzen Threadripper  | 52        | 0.51%   |
| AMD A4                  | 40        | 0.39%   |
| AMD Phenom II X4        | 35        | 0.34%   |
| Intel Core 2            | 34        | 0.33%   |
| AMD Athlon              | 32        | 0.31%   |
| AMD Ryzen 5 PRO         | 27        | 0.26%   |
| AMD Athlon II X2        | 26        | 0.25%   |
| Intel Pentium Dual      | 22        | 0.21%   |
| Intel Genuine           | 17        | 0.17%   |
| Intel Core m3           | 17        | 0.17%   |
| AMD Athlon II X4        | 17        | 0.17%   |
| AMD E1                  | 16        | 0.16%   |
| AMD E                   | 16        | 0.16%   |
| Intel Pentium Silver    | 15        | 0.15%   |
| AMD Phenom II X6        | 14        | 0.14%   |
| AMD Athlon 64 X2        | 13        | 0.13%   |
| AMD E2                  | 12        | 0.12%   |
| Intel Pentium Gold      | 11        | 0.11%   |
| Intel Core m5           | 10        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 3721      | 36.19%  |
| 2       | 3085      | 30.01%  |
| 6       | 1479      | 14.39%  |
| 8       | 1210      | 11.77%  |
| 12      | 250       | 2.43%   |
| 16      | 143       | 1.39%   |
| 14      | 103       | 1%      |
| 10      | 96        | 0.93%   |
| 1       | 61        | 0.59%   |
| 3       | 57        | 0.55%   |
| 24      | 34        | 0.33%   |
| 32      | 16        | 0.16%   |
| Unknown | 10        | 0.1%    |
| 64      | 4         | 0.04%   |
| 40      | 2         | 0.02%   |
| 36      | 2         | 0.02%   |
| 20      | 2         | 0.02%   |
| 18      | 2         | 0.02%   |
| 48      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 7       | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 10194     | 99.32%  |
| 2       | 60        | 0.58%   |
| Unknown | 10        | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 7978      | 77.62%  |
| 1       | 2290      | 22.28%  |
| Unknown | 10        | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 10236     | 99.74%  |
| 64-bit         | 16        | 0.16%   |
| Unknown        | 11        | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7322      | 69.67%  |
| 0x906ea    | 193       | 1.84%   |
| 0x306a9    | 168       | 1.6%    |
| 0x206a7    | 147       | 1.4%    |
| 0x306c3    | 135       | 1.28%   |
| 0x806ea    | 126       | 1.2%    |
| 0x806ec    | 124       | 1.18%   |
| 0x806c1    | 118       | 1.12%   |
| 0x08701021 | 111       | 1.06%   |
| 0x406e3    | 95        | 0.9%    |
| 0x906e9    | 88        | 0.84%   |
| 0x40651    | 86        | 0.82%   |
| 0x806e9    | 81        | 0.77%   |
| 0x506e3    | 79        | 0.75%   |
| 0x0800820d | 79        | 0.75%   |
| 0x08701013 | 77        | 0.73%   |
| 0xa0652    | 75        | 0.71%   |
| 0x0a50000c | 70        | 0.67%   |
| 0x1067a    | 63        | 0.6%    |
| 0x08108109 | 57        | 0.54%   |
| 0x08600106 | 53        | 0.5%    |
| 0x08108102 | 51        | 0.49%   |
| 0x906ed    | 44        | 0.42%   |
| 0x306d4    | 44        | 0.42%   |
| 0x806d1    | 38        | 0.36%   |
| 0x806eb    | 37        | 0.35%   |
| 0x08608103 | 35        | 0.33%   |
| 0x20655    | 30        | 0.29%   |
| 0x08600104 | 28        | 0.27%   |
| 0x08001138 | 28        | 0.27%   |
| 0x706e5    | 27        | 0.26%   |
| 0x0a201016 | 27        | 0.26%   |
| 0x906a3    | 26        | 0.25%   |
| 0x406c4    | 26        | 0.25%   |
| 0x0810100b | 26        | 0.25%   |
| 0x06000852 | 25        | 0.24%   |
| 0x06006705 | 23        | 0.22%   |
| 0x0a601203 | 22        | 0.21%   |
| 0x0a50000d | 22        | 0.21%   |
| 0x08600103 | 21        | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1833      | 17.82%  |
| Haswell          | 952       | 9.26%   |
| Zen 2            | 776       | 7.54%   |
| SandyBridge      | 668       | 6.49%   |
| IvyBridge        | 664       | 6.46%   |
| Skylake          | 570       | 5.54%   |
| Unknown          | 563       | 5.47%   |
| Zen 3            | 562       | 5.46%   |
| Zen+             | 522       | 5.07%   |
| Penryn           | 344       | 3.34%   |
| CometLake        | 341       | 3.32%   |
| TigerLake        | 308       | 2.99%   |
| Zen              | 262       | 2.55%   |
| Broadwell        | 229       | 2.23%   |
| Westmere         | 224       | 2.18%   |
| Piledriver       | 197       | 1.92%   |
| Silvermont       | 154       | 1.5%    |
| Core             | 144       | 1.4%    |
| IceLake          | 138       | 1.34%   |
| K10              | 125       | 1.22%   |
| Alderlake Hybrid | 121       | 1.18%   |
| Nehalem          | 106       | 1.03%   |
| Excavator        | 99        | 0.96%   |
| Goldmont plus    | 91        | 0.88%   |
| Puma             | 48        | 0.47%   |
| Steamroller      | 45        | 0.44%   |
| Goldmont         | 37        | 0.36%   |
| Bobcat           | 34        | 0.33%   |
| K8 Hammer        | 31        | 0.3%    |
| K10 Llano        | 30        | 0.29%   |
| Jaguar           | 22        | 0.21%   |
| Bulldozer        | 16        | 0.16%   |
| NetBurst         | 9         | 0.09%   |
| K8 & K10 hybrid  | 9         | 0.09%   |
| Bonnell          | 6         | 0.06%   |
| Tremont          | 4         | 0.04%   |
| Gracemont        | 2         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5377      | 42.76%  |
| Nvidia                           | 4183      | 33.26%  |
| AMD                              | 2984      | 23.73%  |
| Matrox Electronics Systems       | 15        | 0.12%   |
| Silicon Integrated Systems [SiS] | 8         | 0.06%   |
| ASPEED Technology                | 8         | 0.06%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 468       | 3.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 360       | 2.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 358       | 2.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 295       | 2.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 294       | 2.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 293       | 2.27%   |
| Intel UHD Graphics 620                                                                   | 289       | 2.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 285       | 2.21%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 240       | 1.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 227       | 1.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 224       | 1.73%   |
| Intel HD Graphics 620                                                                    | 200       | 1.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 191       | 1.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 187       | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 182       | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 174       | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 170       | 1.32%   |
| Intel HD Graphics 630                                                                    | 163       | 1.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 152       | 1.18%   |
| Intel HD Graphics 5500                                                                   | 147       | 1.14%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 138       | 1.07%   |
| Intel HD Graphics 530                                                                    | 135       | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 133       | 1.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 116       | 0.9%    |
| AMD Lucienne                                                                             | 114       | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 103       | 0.8%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 99        | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 99        | 0.77%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 97        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 92        | 0.71%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 92        | 0.71%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 90        | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 88        | 0.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 85        | 0.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 81        | 0.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 77        | 0.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 74        | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 72        | 0.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 72        | 0.56%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 70        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 3497      | 33.7%   |
| 1 x Nvidia              | 2270      | 21.88%  |
| 1 x AMD                 | 2226      | 21.45%  |
| Intel + Nvidia          | 1510      | 14.55%  |
| AMD + Nvidia            | 326       | 3.14%   |
| Intel + AMD             | 244       | 2.35%   |
| 2 x AMD                 | 190       | 1.83%   |
| 2 x Nvidia              | 47        | 0.45%   |
| Other                   | 25        | 0.24%   |
| 1 x SiS                 | 8         | 0.08%   |
| 1 x Matrox              | 8         | 0.08%   |
| Nvidia + Matrox         | 4         | 0.04%   |
| Nvidia + ASPEED         | 4         | 0.04%   |
| Intel + 2 x Nvidia      | 4         | 0.04%   |
| AMD + ASPEED            | 3         | 0.03%   |
| AMD + Matrox            | 2         | 0.02%   |
| 5 x Nvidia              | 1         | 0.01%   |
| 4 x Nvidia              | 1         | 0.01%   |
| 3 x Nvidia              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x Intel               | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| 1 x ASPEED              | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6635      | 63.83%  |
| Proprietary | 3354      | 32.27%  |
| Unknown     | 405       | 3.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7257      | 69.29%  |
| 1.01-2.0   | 687       | 6.56%   |
| 3.01-4.0   | 636       | 6.07%   |
| 7.01-8.0   | 605       | 5.78%   |
| 5.01-6.0   | 444       | 4.24%   |
| 0.01-0.5   | 338       | 3.23%   |
| 0.51-1.0   | 195       | 1.86%   |
| 8.01-16.0  | 193       | 1.84%   |
| 2.01-3.0   | 84        | 0.8%    |
| 16.01-24.0 | 30        | 0.29%   |
| 4.01-5.0   | 3         | 0.03%   |
| 32.01-64.0 | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1382      | 11.86%  |
| AU Optronics            | 1249      | 10.72%  |
| Chimei Innolux          | 1013      | 8.69%   |
| LG Display              | 955       | 8.2%    |
| BOE                     | 953       | 8.18%   |
| Goldstar                | 738       | 6.33%   |
| Dell                    | 718       | 6.16%   |
| Acer                    | 471       | 4.04%   |
| Apple                   | 357       | 3.06%   |
| Hewlett-Packard         | 350       | 3%      |
| AOC                     | 335       | 2.88%   |
| Sharp                   | 279       | 2.39%   |
| BenQ                    | 252       | 2.16%   |
| Ancor Communications    | 249       | 2.14%   |
| Philips                 | 193       | 1.66%   |
| ASUSTek Computer        | 187       | 1.61%   |
| Lenovo                  | 176       | 1.51%   |
| PANDA                   | 159       | 1.36%   |
| ViewSonic               | 105       | 0.9%    |
| Chi Mei Optoelectronics | 103       | 0.88%   |
| Iiyama                  | 91        | 0.78%   |
| InfoVision              | 82        | 0.7%    |
| Sony                    | 73        | 0.63%   |
| MSI                     | 73        | 0.63%   |
| Sceptre Tech            | 57        | 0.49%   |
| Vizio                   | 49        | 0.42%   |
| Panasonic               | 48        | 0.41%   |
| CSO                     | 43        | 0.37%   |
| Toshiba                 | 37        | 0.32%   |
| Gigabyte Technology     | 37        | 0.32%   |
| NEC Computers           | 27        | 0.23%   |
| Unknown                 | 26        | 0.22%   |
| Eizo                    | 26        | 0.22%   |
| Insignia                | 24        | 0.21%   |
| Fujitsu Siemens         | 22        | 0.19%   |
| Hitachi                 | 21        | 0.18%   |
| Vestel Elektronik       | 20        | 0.17%   |
| LG Electronics          | 18        | 0.15%   |
| TMX                     | 17        | 0.15%   |
| MStar                   | 17        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 75        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 75        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 58        | 0.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 54        | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 52        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 51        | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 50        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 47        | 0.39%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 43        | 0.36%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 39        | 0.32%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 35        | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 34        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 33        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 32        | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 30        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 30        | 0.25%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 29        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 27        | 0.22%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 26        | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 26        | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 25        | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 25        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 25        | 0.21%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 24        | 0.2%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 24        | 0.2%    |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 24        | 0.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 23        | 0.19%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 23        | 0.19%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 23        | 0.19%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 22        | 0.18%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 22        | 0.18%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 22        | 0.18%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 21        | 0.17%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 21        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 21        | 0.17%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 21        | 0.17%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 20        | 0.17%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 20        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 20        | 0.17%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 19        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 5160      | 46.87%  |
| 1366x768 (WXGA)    | 1666      | 15.13%  |
| 3840x2160 (4K)     | 976       | 8.86%   |
| 2560x1440 (QHD)    | 705       | 6.4%    |
| 1600x900 (HD+)     | 338       | 3.07%   |
| 1920x1200 (WUXGA)  | 259       | 2.35%   |
| 3440x1440          | 217       | 1.97%   |
| 1440x900 (WXGA+)   | 208       | 1.89%   |
| 1680x1050 (WSXGA+) | 206       | 1.87%   |
| 2560x1080          | 196       | 1.78%   |
| 1280x1024 (SXGA)   | 170       | 1.54%   |
| 1280x800 (WXGA)    | 146       | 1.33%   |
| 2560x1600          | 122       | 1.11%   |
| 2880x1800          | 86        | 0.78%   |
| 1360x768           | 69        | 0.63%   |
| 3840x1080          | 52        | 0.47%   |
| 1920x540           | 50        | 0.45%   |
| 3840x2400          | 44        | 0.4%    |
| Unknown            | 36        | 0.33%   |
| 2160x1440          | 34        | 0.31%   |
| 2736x1824          | 22        | 0.2%    |
| 3200x1800 (QHD+)   | 20        | 0.18%   |
| 3840x1600          | 18        | 0.16%   |
| 2256x1504          | 18        | 0.16%   |
| 1024x768 (XGA)     | 16        | 0.15%   |
| 3072x1920          | 15        | 0.14%   |
| 3000x2000          | 15        | 0.14%   |
| 1280x720 (HD)      | 15        | 0.14%   |
| 1600x1200          | 14        | 0.13%   |
| 1920x1280          | 13        | 0.12%   |
| 3456x2160          | 7         | 0.06%   |
| 3200x2000          | 7         | 0.06%   |
| 3840x1200          | 6         | 0.05%   |
| 2048x1152          | 6         | 0.05%   |
| 4480x1440          | 4         | 0.04%   |
| 3840x1100          | 4         | 0.04%   |
| 2880x1620          | 4         | 0.04%   |
| 2304x1440          | 4         | 0.04%   |
| 2288x1287          | 4         | 0.04%   |
| 2240x1400          | 4         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2886      | 24.79%  |
| 13      | 1129      | 9.7%    |
| 27      | 1065      | 9.15%   |
| 24      | 905       | 7.77%   |
| 14      | 843       | 7.24%   |
| 23      | 713       | 6.12%   |
| 21      | 587       | 5.04%   |
| 17      | 564       | 4.84%   |
| 31      | 404       | 3.47%   |
| 34      | 349       | 3%      |
| 19      | 213       | 1.83%   |
| Unknown | 196       | 1.68%   |
| 12      | 178       | 1.53%   |
| 18      | 172       | 1.48%   |
| 16      | 148       | 1.27%   |
| 22      | 143       | 1.23%   |
| 20      | 127       | 1.09%   |
| 84      | 119       | 1.02%   |
| 32      | 102       | 0.88%   |
| 11      | 91        | 0.78%   |
| 72      | 82        | 0.7%    |
| 40      | 74        | 0.64%   |
| 54      | 61        | 0.52%   |
| 48      | 48        | 0.41%   |
| 26      | 44        | 0.38%   |
| 25      | 41        | 0.35%   |
| 28      | 35        | 0.3%    |
| 52      | 30        | 0.26%   |
| 35      | 29        | 0.25%   |
| 65      | 22        | 0.19%   |
| 49      | 22        | 0.19%   |
| 37      | 22        | 0.19%   |
| 29      | 21        | 0.18%   |
| 46      | 20        | 0.17%   |
| 36      | 16        | 0.14%   |
| 33      | 16        | 0.14%   |
| 42      | 13        | 0.11%   |
| 43      | 11        | 0.09%   |
| 74      | 10        | 0.09%   |
| 10      | 9         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 4391      | 38.53%  |
| 501-600        | 2418      | 21.22%  |
| 401-500        | 1123      | 9.85%   |
| 201-300        | 861       | 7.56%   |
| 351-400        | 690       | 6.05%   |
| 601-700        | 598       | 5.25%   |
| 701-800        | 471       | 4.13%   |
| 1001-1500      | 244       | 2.14%   |
| 1501-2000      | 223       | 1.96%   |
| Unknown        | 196       | 1.72%   |
| 801-900        | 146       | 1.28%   |
| 901-1000       | 28        | 0.25%   |
| 101-200        | 3         | 0.03%   |
| More than 2000 | 2         | 0.02%   |
| 1-100          | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 8110      | 79.2%   |
| 16/10   | 1171      | 11.44%  |
| 21/9    | 421       | 4.11%   |
| 5/4     | 168       | 1.64%   |
| 3/2     | 117       | 1.14%   |
| Unknown | 107       | 1.04%   |
| 32/9    | 59        | 0.58%   |
| 4/3     | 53        | 0.52%   |
| 6/5     | 10        | 0.1%    |
| 1.96    | 6         | 0.06%   |
| 3.20    | 5         | 0.05%   |
| 3.40    | 4         | 0.04%   |
| 3.73    | 2         | 0.02%   |
| 0.56    | 2         | 0.02%   |
| 1.00    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2871      | 24.95%  |
| 201-250        | 1858      | 16.15%  |
| 81-90          | 1545      | 13.43%  |
| 301-350        | 1096      | 9.52%   |
| 351-500        | 908       | 7.89%   |
| 151-200        | 503       | 4.37%   |
| 121-130        | 456       | 3.96%   |
| 71-80          | 435       | 3.78%   |
| More than 1000 | 382       | 3.32%   |
| 251-300        | 328       | 2.85%   |
| 501-1000       | 240       | 2.09%   |
| 141-150        | 222       | 1.93%   |
| Unknown        | 196       | 1.7%    |
| 61-70          | 149       | 1.29%   |
| 111-120        | 139       | 1.21%   |
| 51-60          | 96        | 0.83%   |
| 131-140        | 46        | 0.4%    |
| 91-100         | 24        | 0.21%   |
| 41-50          | 8         | 0.07%   |
| 1-40           | 5         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3478      | 31.37%  |
| 121-160       | 3279      | 29.58%  |
| 101-120       | 2714      | 24.48%  |
| 161-240       | 752       | 6.78%   |
| More than 240 | 361       | 3.26%   |
| 1-50          | 306       | 2.76%   |
| Unknown       | 196       | 1.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 7859      | 74.75%  |
| 2     | 1922      | 18.28%  |
| 0     | 477       | 4.54%   |
| 3     | 233       | 2.22%   |
| 4     | 20        | 0.19%   |
| 5     | 2         | 0.02%   |
| 6     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5582      | 35.34%  |
| Intel                             | 5302      | 33.56%  |
| Qualcomm Atheros                  | 1604      | 10.15%  |
| Broadcom                          | 914       | 5.79%   |
| MediaTek                          | 277       | 1.75%   |
| Broadcom Limited                  | 215       | 1.36%   |
| TP-Link                           | 175       | 1.11%   |
| Ralink Technology                 | 158       | 1%      |
| Marvell Technology Group          | 144       | 0.91%   |
| Nvidia                            | 129       | 0.82%   |
| Ralink                            | 115       | 0.73%   |
| Samsung Electronics               | 95        | 0.6%    |
| ASIX Electronics                  | 92        | 0.58%   |
| Microsoft                         | 84        | 0.53%   |
| NetGear                           | 59        | 0.37%   |
| Xiaomi                            | 50        | 0.32%   |
| Aquantia                          | 46        | 0.29%   |
| Qualcomm Atheros Communications   | 43        | 0.27%   |
| Google                            | 43        | 0.27%   |
| DisplayLink                       | 43        | 0.27%   |
| InterBiometrics                   | 38        | 0.24%   |
| Dell                              | 36        | 0.23%   |
| ASUSTek Computer                  | 35        | 0.22%   |
| Lenovo                            | 33        | 0.21%   |
| Sierra Wireless                   | 32        | 0.2%    |
| Qualcomm                          | 32        | 0.2%    |
| Huawei Technologies               | 30        | 0.19%   |
| D-Link                            | 30        | 0.19%   |
| Linksys                           | 27        | 0.17%   |
| Ericsson Business Mobile Networks | 23        | 0.15%   |
| JMicron Technology                | 22        | 0.14%   |
| OnePlus Technology (Shenzhen)     | 20        | 0.13%   |
| OPPO Electronics                  | 19        | 0.12%   |
| Hewlett-Packard                   | 18        | 0.11%   |
| Edimax Technology                 | 18        | 0.11%   |
| Motorola PCS                      | 17        | 0.11%   |
| D-Link System                     | 14        | 0.09%   |
| Belkin Components                 | 10        | 0.06%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.06%   |
| Fibocom                           | 9         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 3795      | 20.44%  |
| Intel Wi-Fi 6 AX200                                                    | 790       | 4.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 514       | 2.77%   |
| Intel I211 Gigabit Network Connection                                  | 445       | 2.4%    |
| Realtek RTL8125 2.5GbE Controller                                      | 349       | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 330       | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 328       | 1.77%   |
| Intel Wireless 8265 / 8275                                             | 325       | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 304       | 1.64%   |
| Intel Wi-Fi 6 AX201                                                    | 242       | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 228       | 1.23%   |
| Intel Wireless 7265                                                    | 216       | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 209       | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 209       | 1.13%   |
| Intel Wireless 7260                                                    | 208       | 1.12%   |
| Intel Ethernet Controller I225-V                                       | 201       | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 199       | 1.07%   |
| Intel Wireless 8260                                                    | 187       | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 183       | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 181       | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                   | 171       | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 170       | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 167       | 0.9%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 166       | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 163       | 0.88%   |
| Intel Ethernet Connection I217-LM                                      | 147       | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 129       | 0.69%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 129       | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 128       | 0.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 125       | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 121       | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                   | 119       | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 113       | 0.61%   |
| Intel Wireless 3165                                                    | 110       | 0.59%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 100       | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                          | 93        | 0.5%    |
| Realtek 802.11ac NIC                                                   | 92        | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 91        | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 90        | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 87        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4189      | 47.27%  |
| Realtek Semiconductor                 | 1346      | 15.19%  |
| Qualcomm Atheros                      | 1248      | 14.08%  |
| Broadcom                              | 704       | 7.94%   |
| MediaTek                              | 268       | 3.02%   |
| Broadcom Limited                      | 171       | 1.93%   |
| TP-Link                               | 160       | 1.81%   |
| Ralink Technology                     | 158       | 1.78%   |
| Ralink                                | 115       | 1.3%    |
| Microsoft                             | 79        | 0.89%   |
| NetGear                               | 57        | 0.64%   |
| Qualcomm Atheros Communications       | 43        | 0.49%   |
| Marvell Technology Group              | 40        | 0.45%   |
| Sierra Wireless                       | 32        | 0.36%   |
| ASUSTek Computer                      | 32        | 0.36%   |
| Dell                                  | 31        | 0.35%   |
| D-Link                                | 29        | 0.33%   |
| Qualcomm                              | 25        | 0.28%   |
| Linksys                               | 23        | 0.26%   |
| Edimax Technology                     | 18        | 0.2%    |
| D-Link System                         | 10        | 0.11%   |
| Belkin Components                     | 10        | 0.11%   |
| Fibocom                               | 9         | 0.1%    |
| AVM                                   | 8         | 0.09%   |
| Hewlett-Packard                       | 7         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 7         | 0.08%   |
| Sitecom Europe                        | 6         | 0.07%   |
| Gemtek                                | 5         | 0.06%   |
| Mercucys                              | 4         | 0.05%   |
| IMC Networks                          | 3         | 0.03%   |
| Ericsson Business Mobile Networks     | 3         | 0.03%   |
| Accton Technology                     | 3         | 0.03%   |
| ZyDAS                                 | 2         | 0.02%   |
| Wilocity                              | 2         | 0.02%   |
| Wacom                                 | 2         | 0.02%   |
| Samsung Electronics                   | 2         | 0.02%   |
| Ovislink                              | 2         | 0.02%   |
| Micro Star International              | 2         | 0.02%   |
| TRENDnet                              | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 790       | 8.85%   |
| Intel Wireless 8265 / 8275                                           | 325       | 3.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 304       | 3.41%   |
| Intel Wi-Fi 6 AX201                                                  | 242       | 2.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 228       | 2.55%   |
| Intel Wireless 7265                                                  | 216       | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 209       | 2.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 209       | 2.34%   |
| Intel Wireless 7260                                                  | 208       | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 199       | 2.23%   |
| Intel Wireless 8260                                                  | 187       | 2.1%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 183       | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 181       | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 170       | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 167       | 1.87%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 166       | 1.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 163       | 1.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 129       | 1.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 129       | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 128       | 1.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 125       | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 121       | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 113       | 1.27%   |
| Intel Wireless 3165                                                  | 110       | 1.23%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 100       | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                        | 93        | 1.04%   |
| Realtek 802.11ac NIC                                                 | 92        | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 90        | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 87        | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 86        | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 85        | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 77        | 0.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 76        | 0.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 76        | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 74        | 0.83%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 72        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 71        | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 69        | 0.77%   |
| Intel Wireless 3160                                                  | 68        | 0.76%   |
| Ralink MT7601U Wireless Adapter                                      | 62        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 5033      | 54.03%  |
| Intel                            | 2516      | 27.01%  |
| Qualcomm Atheros                 | 489       | 5.25%   |
| Broadcom                         | 383       | 4.11%   |
| Nvidia                           | 129       | 1.38%   |
| Marvell Technology Group         | 104       | 1.12%   |
| Samsung Electronics              | 93        | 1%      |
| ASIX Electronics                 | 92        | 0.99%   |
| Xiaomi                           | 50        | 0.54%   |
| Broadcom Limited                 | 48        | 0.52%   |
| Aquantia                         | 46        | 0.49%   |
| Google                           | 43        | 0.46%   |
| DisplayLink                      | 43        | 0.46%   |
| Lenovo                           | 33        | 0.35%   |
| Huawei Technologies              | 26        | 0.28%   |
| JMicron Technology               | 22        | 0.24%   |
| OPPO Electronics                 | 19        | 0.2%    |
| OnePlus Technology (Shenzhen)    | 16        | 0.17%   |
| TP-Link                          | 15        | 0.16%   |
| Motorola PCS                     | 12        | 0.13%   |
| Silicon Integrated Systems [SiS] | 9         | 0.1%    |
| MediaTek                         | 8         | 0.09%   |
| Qualcomm                         | 7         | 0.08%   |
| ICS Advent                       | 7         | 0.08%   |
| Apple                            | 6         | 0.06%   |
| VIA Technologies                 | 5         | 0.05%   |
| Microsoft                        | 5         | 0.05%   |
| Hewlett-Packard                  | 5         | 0.05%   |
| Mellanox Technologies            | 4         | 0.04%   |
| Linksys                          | 4         | 0.04%   |
| D-Link System                    | 4         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.03%   |
| T & A Mobile Phones              | 3         | 0.03%   |
| LG Electronics                   | 3         | 0.03%   |
| ASUSTek Computer                 | 3         | 0.03%   |
| NetGear                          | 2         | 0.02%   |
| LSI                              | 2         | 0.02%   |
| American Megatrends              | 2         | 0.02%   |
| 3Com                             | 2         | 0.02%   |
| Tehuti Networks                  | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 3795      | 39.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 514       | 5.41%   |
| Intel I211 Gigabit Network Connection                                  | 445       | 4.68%   |
| Realtek RTL8125 2.5GbE Controller                                      | 349       | 3.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 330       | 3.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 328       | 3.45%   |
| Intel Ethernet Controller I225-V                                       | 201       | 2.11%   |
| Intel Ethernet Connection (2) I219-V                                   | 171       | 1.8%    |
| Intel Ethernet Connection I217-LM                                      | 147       | 1.55%   |
| Intel Ethernet Connection (7) I219-V                                   | 119       | 1.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 91        | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                                  | 84        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 79        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 78        | 0.82%   |
| Intel Ethernet Connection I219-LM                                      | 75        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                          | 71        | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 65        | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 64        | 0.67%   |
| Nvidia MCP79 Ethernet                                                  | 64        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 61        | 0.64%   |
| Intel 82579V Gigabit Network Connection                                | 61        | 0.64%   |
| Intel Ethernet Connection I218-LM                                      | 59        | 0.62%   |
| Intel Ethernet Connection I217-V                                       | 57        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 55        | 0.58%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 54        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                   | 52        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 50        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                                   | 45        | 0.47%   |
| Intel I210 Gigabit Network Connection                                  | 44        | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                                  | 43        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 43        | 0.45%   |
| Realtek Killer E2600 GbE Controller                                    | 41        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 40        | 0.42%   |
| Nvidia MCP61 Ethernet                                                  | 40        | 0.42%   |
| Intel Ethernet Connection (6) I219-V                                   | 40        | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 38        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 37        | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                                  | 36        | 0.38%   |
| Intel 82577LM Gigabit Network Connection                               | 34        | 0.36%   |
| Intel 82574L Gigabit Network Connection                                | 33        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 8680      | 50.53%  |
| WiFi     | 8361      | 48.67%  |
| Modem    | 106       | 0.62%   |
| Unknown  | 31        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 6486      | 59.55%  |
| Ethernet | 4402      | 40.42%  |
| Unknown  | 3         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 5751      | 55.87%  |
| 1     | 4117      | 40%     |
| 3     | 250       | 2.43%   |
| 0     | 126       | 1.22%   |
| 4     | 37        | 0.36%   |
| 5     | 8         | 0.08%   |
| 10    | 2         | 0.02%   |
| 6     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8046      | 77%     |
| Yes  | 2403      | 23%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3653      | 51.36%  |
| Realtek Semiconductor           | 604       | 8.49%   |
| Qualcomm Atheros Communications | 533       | 7.49%   |
| Apple                           | 431       | 6.06%   |
| Cambridge Silicon Radio         | 369       | 5.19%   |
| IMC Networks                    | 296       | 4.16%   |
| Broadcom                        | 274       | 3.85%   |
| Lite-On Technology              | 223       | 3.14%   |
| Foxconn / Hon Hai               | 192       | 2.7%    |
| ASUSTek Computer                | 117       | 1.64%   |
| Dell                            | 74        | 1.04%   |
| MediaTek                        | 56        | 0.79%   |
| Marvell Semiconductor           | 43        | 0.6%    |
| Realtek                         | 38        | 0.53%   |
| Ralink                          | 36        | 0.51%   |
| Toshiba                         | 32        | 0.45%   |
| Hewlett-Packard                 | 32        | 0.45%   |
| TP-Link                         | 19        | 0.27%   |
| Foxconn International           | 12        | 0.17%   |
| Dynex                           | 9         | 0.13%   |
| Ralink Technology               | 8         | 0.11%   |
| Alps Electric                   | 7         | 0.1%    |
| Integrated System Solution      | 5         | 0.07%   |
| Actions                         | 5         | 0.07%   |
| USI                             | 4         | 0.06%   |
| Smart Modular Technologies      | 4         | 0.06%   |
| HTC (High Tech Computer)        | 4         | 0.06%   |
| Askey Computer                  | 4         | 0.06%   |
| Taiyo Yuden                     | 3         | 0.04%   |
| SINO WEALTH                     | 3         | 0.04%   |
| Qcom                            | 3         | 0.04%   |
| Opticis                         | 3         | 0.04%   |
| Micro Star International        | 3         | 0.04%   |
| Creative Technology             | 3         | 0.04%   |
| Logitech                        | 2         | 0.03%   |
| Fujitsu                         | 2         | 0.03%   |
| Edimax Technology               | 2         | 0.03%   |
| Conwise Technology              | 2         | 0.03%   |
| Belkin Components               | 2         | 0.03%   |
| Primax Electronics              | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1071      | 15.04%  |
| Intel AX200 Bluetooth                               | 753       | 10.58%  |
| Intel AX201 Bluetooth                               | 647       | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 482       | 6.77%   |
| Realtek Bluetooth Radio                             | 414       | 5.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 369       | 5.18%   |
| Qualcomm Atheros  Bluetooth Device                  | 295       | 4.14%   |
| Apple Bluetooth Host Controller                     | 217       | 3.05%   |
| Intel Bluetooth Device                              | 193       | 2.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 159       | 2.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 153       | 2.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 143       | 2.01%   |
| Apple Bluetooth USB Host Controller                 | 124       | 1.74%   |
| Intel AX210 Bluetooth                               | 122       | 1.71%   |
| IMC Networks Bluetooth Radio                        | 96        | 1.35%   |
| IMC Networks Wireless_Device                        | 89        | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 78        | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 78        | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                  | 70        | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 66        | 0.93%   |
| Foxconn / Hon Hai Wireless_Device                   | 62        | 0.87%   |
| IMC Networks Bluetooth Device                       | 57        | 0.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 57        | 0.8%    |
| MediaTek Wireless_Device                            | 56        | 0.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 54        | 0.76%   |
| Lite-On Bluetooth Device                            | 52        | 0.73%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 51        | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 50        | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 48        | 0.67%   |
| Realtek Bluetooth Radio                             | 38        | 0.53%   |
| Broadcom BCM2045B (BDC-2.1)                         | 37        | 0.52%   |
| Ralink RT3290 Bluetooth                             | 36        | 0.51%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 36        | 0.51%   |
| Apple Bluetooth HCI                                 | 36        | 0.51%   |
| Marvell Bluetooth and Wireless LAN Composite        | 29        | 0.41%   |
| Dell DW375 Bluetooth Module                         | 27        | 0.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 0.37%   |
| ASUS Bluetooth Radio                                | 26        | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 25        | 0.35%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 6925      | 43.82%  |
| AMD                                             | 3530      | 22.34%  |
| Nvidia                                          | 3336      | 21.11%  |
| C-Media Electronics                             | 283       | 1.79%   |
| Logitech                                        | 164       | 1.04%   |
| Kingston Technology                             | 85        | 0.54%   |
| JMTek                                           | 82        | 0.52%   |
| Creative Labs                                   | 80        | 0.51%   |
| Razer USA                                       | 78        | 0.49%   |
| Corsair                                         | 69        | 0.44%   |
| SteelSeries ApS                                 | 63        | 0.4%    |
| Texas Instruments                               | 62        | 0.39%   |
| Realtek Semiconductor                           | 61        | 0.39%   |
| ASUSTek Computer                                | 59        | 0.37%   |
| Focusrite-Novation                              | 57        | 0.36%   |
| Generalplus Technology                          | 51        | 0.32%   |
| GN Netcom                                       | 45        | 0.28%   |
| Creative Technology                             | 40        | 0.25%   |
| Lenovo                                          | 37        | 0.23%   |
| Blue Microphones                                | 34        | 0.22%   |
| Micro Star International                        | 32        | 0.2%    |
| Sony                                            | 28        | 0.18%   |
| Plantronics                                     | 28        | 0.18%   |
| Apple                                           | 25        | 0.16%   |
| Giga-Byte Technology                            | 19        | 0.12%   |
| DSEA A/S                                        | 19        | 0.12%   |
| Astro Gaming                                    | 19        | 0.12%   |
| Tenx Technology                                 | 16        | 0.1%    |
| Samson Technologies                             | 16        | 0.1%    |
| Hewlett-Packard                                 | 16        | 0.1%    |
| Yamaha                                          | 15        | 0.09%   |
| FiiO Electronics Technology                     | 15        | 0.09%   |
| Valve Software                                  | 14        | 0.09%   |
| Turtle Beach                                    | 13        | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 13        | 0.08%   |
| SAVITECH                                        | 12        | 0.08%   |
| M-Audio                                         | 12        | 0.08%   |
| Dell                                            | 11        | 0.07%   |
| Silicon Integrated Systems [SiS]                | 10        | 0.06%   |
| Licensed by Sony Computer Entertainment America | 10        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1201      | 6.37%   |
| Intel Sunrise Point-LP HD Audio                                            | 785       | 4.16%   |
| AMD Starship/Matisse HD Audio Controller                                   | 782       | 4.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 632       | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 616       | 3.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 545       | 2.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 538       | 2.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 514       | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 368       | 1.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 337       | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 324       | 1.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 308       | 1.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 301       | 1.6%    |
| Intel 8 Series HD Audio Controller                                         | 297       | 1.58%   |
| Intel Haswell-ULT HD Audio Controller                                      | 293       | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 292       | 1.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 265       | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 251       | 1.33%   |
| Intel Comet Lake PCH cAVS                                                  | 245       | 1.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 241       | 1.28%   |
| AMD FCH Azalia Controller                                                  | 238       | 1.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 233       | 1.24%   |
| Nvidia GP104 High Definition Audio Controller                              | 230       | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                              | 219       | 1.16%   |
| Intel Broadwell-U Audio Controller                                         | 218       | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 213       | 1.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 212       | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                              | 211       | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 210       | 1.11%   |
| Intel 200 Series PCH HD Audio                                              | 209       | 1.11%   |
| Nvidia GA104 High Definition Audio Controller                              | 208       | 1.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 208       | 1.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 189       | 1%      |
| AMD Navi 10 HDMI Audio                                                     | 177       | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 155       | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 155       | 0.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 152       | 0.81%   |
| Intel CM238 HD Audio Controller                                            | 151       | 0.8%    |
| Nvidia TU104 HD Audio Controller                                           | 149       | 0.79%   |
| Nvidia Audio device                                                        | 149       | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 674       | 23%     |
| SK hynix            | 537       | 18.32%  |
| Micron Technology   | 328       | 11.19%  |
| Kingston            | 301       | 10.27%  |
| Corsair             | 214       | 7.3%    |
| Crucial             | 194       | 6.62%   |
| G.Skill             | 139       | 4.74%   |
| Unknown             | 124       | 4.23%   |
| A-DATA Technology   | 65        | 2.22%   |
| Team                | 43        | 1.47%   |
| Smart               | 37        | 1.26%   |
| Ramaxel Technology  | 37        | 1.26%   |
| Elpida              | 27        | 0.92%   |
| Goldkey             | 24        | 0.82%   |
| Unknown             | 24        | 0.82%   |
| Neo Forza           | 22        | 0.75%   |
| Unknown (ABCD)      | 18        | 0.61%   |
| Patriot             | 15        | 0.51%   |
| Smart Brazil        | 10        | 0.34%   |
| Nanya Technology    | 9         | 0.31%   |
| Teikon              | 8         | 0.27%   |
| Apacer              | 7         | 0.24%   |
| Transcend           | 5         | 0.17%   |
| Avant               | 5         | 0.17%   |
| PNY                 | 4         | 0.14%   |
| Timetec             | 3         | 0.1%    |
| Silicon Power       | 3         | 0.1%    |
| High Bridge         | 3         | 0.1%    |
| GSkill              | 3         | 0.1%    |
| Goodram             | 3         | 0.1%    |
| CSX                 | 3         | 0.1%    |
| ChangXin Memory     | 3         | 0.1%    |
| Wodposit            | 2         | 0.07%   |
| Patriot Memory      | 2         | 0.07%   |
| OLOY                | 2         | 0.07%   |
| Gold Key            | 2         | 0.07%   |
| AMD                 | 2         | 0.07%   |
| Wilk                | 1         | 0.03%   |
| Unknown (8A02)      | 1         | 0.03%   |
| Unknown (898F)      | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 53        | 1.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 36        | 1.17%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 34        | 1.1%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 27        | 0.88%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 25        | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 24        | 0.78%   |
| Unknown                                                             | 24        | 0.78%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 23        | 0.75%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 21        | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 20        | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 20        | 0.65%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 20        | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 19        | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 18        | 0.58%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 18        | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 16        | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 16        | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 15        | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 15        | 0.49%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 15        | 0.49%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 15        | 0.49%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 15        | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 14        | 0.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 14        | 0.45%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 14        | 0.45%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 14        | 0.45%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 14        | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 14        | 0.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s               | 14        | 0.45%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 13        | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 12        | 0.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 12        | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 12        | 0.39%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 12        | 0.39%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 12        | 0.39%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 12        | 0.39%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s                 | 12        | 0.39%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 11        | 0.36%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 11        | 0.36%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1672      | 65.88%  |
| DDR3    | 465       | 18.32%  |
| LPDDR4  | 110       | 4.33%   |
| DDR5    | 99        | 3.9%    |
| LPDDR3  | 83        | 3.27%   |
| LPDDR5  | 47        | 1.85%   |
| DDR2    | 28        | 1.1%    |
| Unknown | 20        | 0.79%   |
| SDRAM   | 12        | 0.47%   |
| DDR     | 2         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1565      | 61.06%  |
| DIMM         | 704       | 27.47%  |
| Row Of Chips | 275       | 10.73%  |
| Chip         | 14        | 0.55%   |
| Unknown      | 4         | 0.16%   |
| RIMM         | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1225      | 44.74%  |
| 16384 | 608       | 22.21%  |
| 4096  | 569       | 20.78%  |
| 32768 | 181       | 6.61%   |
| 2048  | 131       | 4.78%   |
| 1024  | 22        | 0.8%    |
| 512   | 2         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 591       | 21.54%  |
| 2667    | 557       | 20.3%   |
| 1600    | 332       | 12.1%   |
| 2400    | 209       | 7.62%   |
| 2133    | 140       | 5.1%    |
| 3600    | 131       | 4.77%   |
| 1333    | 76        | 2.77%   |
| 4800    | 64        | 2.33%   |
| 4267    | 58        | 2.11%   |
| 1867    | 51        | 1.86%   |
| 6400    | 49        | 1.79%   |
| 3266    | 37        | 1.35%   |
| 3733    | 36        | 1.31%   |
| 3800    | 33        | 1.2%    |
| 1334    | 32        | 1.17%   |
| 3000    | 29        | 1.06%   |
| 800     | 22        | 0.8%    |
| 8400    | 21        | 0.77%   |
| 3400    | 19        | 0.69%   |
| 5600    | 17        | 0.62%   |
| 2933    | 17        | 0.62%   |
| 4266    | 16        | 0.58%   |
| 3866    | 16        | 0.58%   |
| 3533    | 15        | 0.55%   |
| 1067    | 15        | 0.55%   |
| 1866    | 14        | 0.51%   |
| 2666    | 13        | 0.47%   |
| 667     | 13        | 0.47%   |
| 3534    | 10        | 0.36%   |
| 3466    | 8         | 0.29%   |
| 1800    | 8         | 0.29%   |
| Unknown | 8         | 0.29%   |
| 6000    | 7         | 0.26%   |
| 3066    | 7         | 0.26%   |
| 5200    | 6         | 0.22%   |
| 4000    | 6         | 0.22%   |
| 4400    | 5         | 0.18%   |
| 3666    | 5         | 0.18%   |
| 2800    | 5         | 0.18%   |
| 3333    | 4         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 66        | 33.5%   |
| Brother Industries    | 35        | 17.77%  |
| Canon                 | 29        | 14.72%  |
| Samsung Electronics   | 22        | 11.17%  |
| Seiko Epson           | 21        | 10.66%  |
| Dymo-CoStar           | 6         | 3.05%   |
| STMicroelectronics    | 3         | 1.52%   |
| Fuji Xerox            | 3         | 1.52%   |
| Xerox                 | 2         | 1.02%   |
| QinHeng Electronics   | 2         | 1.02%   |
| Prolific Technology   | 1         | 0.51%   |
| Oki Data              | 1         | 0.51%   |
| MIIIW                 | 1         | 0.51%   |
| Lexmark International | 1         | 0.51%   |
| Kyocera               | 1         | 0.51%   |
| ICS Advent            | 1         | 0.51%   |
| Dell                  | 1         | 0.51%   |
| Apple                 | 1         | 0.51%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP Deskjet 3050 J610 series                               | 5         | 2.53%   |
| Samsung M2020 Series                                      | 4         | 2.02%   |
| Canon PIXMA MX920 Series                                  | 4         | 2.02%   |
| Seiko Epson ET-2700 Series                                | 3         | 1.52%   |
| Samsung SCX-3400 Series                                   | 3         | 1.52%   |
| Samsung ML-1640 Series Laser Printer                      | 3         | 1.52%   |
| HP LaserJet Professional P 1102w                          | 3         | 1.52%   |
| Dymo-CoStar LabelWriter 450                               | 3         | 1.52%   |
| Brother Printer                                           | 3         | 1.52%   |
| Brother HL-2270DW Laser Printer                           | 3         | 1.52%   |
| Brother HL-2130 series                                    | 3         | 1.52%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.01%   |
| Seiko Epson WF-4830 Series                                | 2         | 1.01%   |
| Seiko Epson WF-3520 Series                                | 2         | 1.01%   |
| Seiko Epson L355 Series                                   | 2         | 1.01%   |
| Seiko Epson L3110 Series                                  | 2         | 1.01%   |
| Seiko Epson ET-2600 Series                                | 2         | 1.01%   |
| Samsung M2070 Series                                      | 2         | 1.01%   |
| QinHeng CH340S                                            | 2         | 1.01%   |
| HP OfficeJet 3830 series                                  | 2         | 1.01%   |
| HP HP LaserJet M14-M17                                    | 2         | 1.01%   |
| HP ENVY Pro 6400 series                                   | 2         | 1.01%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.01%   |
| HP ENVY 4520 series                                       | 2         | 1.01%   |
| HP ENVY 4500 series                                       | 2         | 1.01%   |
| HP DeskJet F4100 Printer series                           | 2         | 1.01%   |
| HP Deskjet F2280 series                                   | 2         | 1.01%   |
| HP DeskJet 2600 series                                    | 2         | 1.01%   |
| HP Deskjet 2540 series                                    | 2         | 1.01%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.01%   |
| Fuji Xerox DocuPrint CM315/318 z                          | 2         | 1.01%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 2         | 1.01%   |
| Canon PIXMA MG2500 Series                                 | 2         | 1.01%   |
| Brother HL-L3230CDW series                                | 2         | 1.01%   |
| Brother HL-1110 series                                    | 2         | 1.01%   |
| Xerox Phaser 6000B                                        | 1         | 0.51%   |
| Xerox B215                                                | 1         | 0.51%   |
| STMicroelectronics USB Printer P                          | 1         | 0.51%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.51%   |
| Seiko Epson L6160 Series                                  | 1         | 0.51%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 47.83%  |
| Seiko Epson     | 7         | 30.43%  |
| Hewlett-Packard | 4         | 17.39%  |
| Mustek Systems  | 1         | 4.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson Scanner                                     | 2         | 8.7%    |
| Canon CanoScan N1240U/LiDE 30                           | 2         | 8.7%    |
| Canon CanoScan LiDE 210                                 | 2         | 8.7%    |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 4.35%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 4.35%   |
| Seiko Epson GT-X700 [Perfection 4870]                   | 1         | 4.35%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 4.35%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1         | 4.35%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 4.35%   |
| HP Scanjet G2710                                        | 1         | 4.35%   |
| HP ScanJet 82x0C                                        | 1         | 4.35%   |
| HP Scanjet 300                                          | 1         | 4.35%   |
| HP ScanJet 2400c                                        | 1         | 4.35%   |
| Canon CanoScan N650U/N656U                              | 1         | 4.35%   |
| Canon CanoScan LiDE 60                                  | 1         | 4.35%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 4.35%   |
| Canon CanoScan LiDE 220                                 | 1         | 4.35%   |
| Canon CanoScan LiDE 200                                 | 1         | 4.35%   |
| Canon CanoScan LiDE 110                                 | 1         | 4.35%   |
| Canon CanoScan 9000F Mark II                            | 1         | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1280      | 20.37%  |
| IMC Networks                           | 593       | 9.44%   |
| Microdia                               | 582       | 9.26%   |
| Realtek Semiconductor                  | 454       | 7.23%   |
| Logitech                               | 415       | 6.61%   |
| Bison Electronics                      | 397       | 6.32%   |
| Apple                                  | 332       | 5.28%   |
| Sunplus Innovation Technology          | 322       | 5.12%   |
| Quanta                                 | 291       | 4.63%   |
| Cheng Uei Precision Industry (Foxlink) | 187       | 2.98%   |
| Acer                                   | 167       | 2.66%   |
| Syntek                                 | 150       | 2.39%   |
| Suyin                                  | 136       | 2.16%   |
| Lite-On Technology                     | 120       | 1.91%   |
| Luxvisions Innotech Limited            | 99        | 1.58%   |
| Silicon Motion                         | 73        | 1.16%   |
| Microsoft                              | 73        | 1.16%   |
| Samsung Electronics                    | 50        | 0.8%    |
| Alcor Micro                            | 40        | 0.64%   |
| Ricoh                                  | 39        | 0.62%   |
| Sonix Technology                       | 36        | 0.57%   |
| Generalplus Technology                 | 28        | 0.45%   |
| Z-Star Microelectronics                | 22        | 0.35%   |
| SunplusIT                              | 19        | 0.3%    |
| Razer USA                              | 18        | 0.29%   |
| ARC International                      | 17        | 0.27%   |
| ALi                                    | 15        | 0.24%   |
| MacroSilicon                           | 14        | 0.22%   |
| Valve Software                         | 13        | 0.21%   |
| Primax Electronics                     | 13        | 0.21%   |
| Lenovo                                 | 12        | 0.19%   |
| Jieli Technology                       | 12        | 0.19%   |
| Intel                                  | 11        | 0.18%   |
| Importek                               | 11        | 0.18%   |
| Creative Technology                    | 11        | 0.18%   |
| OmniVision Technologies                | 10        | 0.16%   |
| KYE Systems (Mouse Systems)            | 10        | 0.16%   |
| DigiTech                               | 10        | 0.16%   |
| AVerMedia Technologies                 | 10        | 0.16%   |
| Hewlett-Packard                        | 8         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 277       | 4.37%   |
| Chicony Integrated Camera               | 264       | 4.16%   |
| IMC Networks USB2.0 HD UVC WebCam       | 192       | 3.03%   |
| Realtek Integrated_Webcam_HD            | 186       | 2.93%   |
| IMC Networks Integrated Camera          | 173       | 2.73%   |
| Chicony HD WebCam                       | 170       | 2.68%   |
| Bison BisonCam,NB Pro                   | 113       | 1.78%   |
| Bison Integrated Camera                 | 102       | 1.61%   |
| Apple Built-in iSight                   | 102       | 1.61%   |
| Chicony USB2.0 Camera                   | 101       | 1.59%   |
| Syntek Integrated Camera                | 97        | 1.53%   |
| Logitech HD Pro Webcam C920             | 88        | 1.39%   |
| Sunplus Integrated_Webcam_HD            | 86        | 1.36%   |
| Logitech Webcam C270                    | 76        | 1.2%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 76        | 1.2%    |
| Apple FaceTime HD Camera                | 71        | 1.12%   |
| Apple FaceTime HD Camera (Built-in)     | 68        | 1.07%   |
| Quanta HD User Facing                   | 60        | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 58        | 0.91%   |
| Realtek USB Camera                      | 48        | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode) | 47        | 0.74%   |
| Lite-On Integrated Camera               | 47        | 0.74%   |
| Chicony USB 2.0 Camera                  | 44        | 0.69%   |
| Chicony HP HD Camera                    | 43        | 0.68%   |
| Chicony HP Wide Vision HD Camera        | 40        | 0.63%   |
| Microdia Webcam Vitade AF               | 39        | 0.61%   |
| Logitech C922 Pro Stream Webcam         | 39        | 0.61%   |
| Microdia Integrated Webcam              | 38        | 0.6%    |
| Chicony HD User Facing                  | 38        | 0.6%    |
| Microdia Laptop_Integrated_Webcam_HD    | 37        | 0.58%   |
| Chicony Integrated Camera (1280x720@30) | 37        | 0.58%   |
| Acer SunplusIT Integrated Camera        | 37        | 0.58%   |
| Sunplus Asus Webcam                     | 35        | 0.55%   |
| Quanta HD Webcam                        | 35        | 0.55%   |
| Chicony TOSHIBA Web Camera - HD         | 34        | 0.54%   |
| Acer HD Webcam                          | 34        | 0.54%   |
| Sunplus HD WebCam                       | 33        | 0.52%   |
| Quanta HP TrueVision HD Camera          | 33        | 0.52%   |
| Chicony USB2.0 HD UVC WebCam            | 33        | 0.52%   |
| Bison HD Webcam                         | 32        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 386       | 33.89%  |
| Validity Sensors                   | 322       | 28.27%  |
| Shenzhen Goodix Technology         | 209       | 18.35%  |
| Elan Microelectronics              | 65        | 5.71%   |
| Upek                               | 55        | 4.83%   |
| LighTuning Technology              | 45        | 3.95%   |
| AuthenTec                          | 30        | 2.63%   |
| STMicroelectronics                 | 7         | 0.61%   |
| Realtek USB2.0 Finger Print Bridge | 7         | 0.61%   |
| Focal-systems.Corp                 | 5         | 0.44%   |
| HOLTEK                             | 4         | 0.35%   |
| Samsung Electronics                | 2         | 0.18%   |
| DigitalPersona                     | 2         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 100       | 8.78%   |
| Shenzhen Goodix  Fingerprint Device                                        | 85        | 7.46%   |
| Shenzhen Goodix Fingerprint Reader                                         | 74        | 6.5%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 69        | 6.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 61        | 5.36%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 50        | 4.39%   |
| Shenzhen Goodix FingerPrint                                                | 50        | 4.39%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 43        | 3.78%   |
| Elan ELAN:Fingerprint                                                      | 43        | 3.78%   |
| Synaptics  WBDI                                                            | 29        | 2.55%   |
| Validity Sensors Synaptics WBDI                                            | 27        | 2.37%   |
| Synaptics TouchPad                                                         | 27        | 2.37%   |
| Synaptics WBDI                                                             | 24        | 2.11%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 23        | 2.02%   |
| Synaptics WBDI Device                                                      | 23        | 2.02%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 22        | 1.93%   |
| Synaptics UWP WBDI                                                         | 22        | 1.93%   |
| Validity Sensors VFS491                                                    | 21        | 1.84%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 1.84%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 21        | 1.84%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 20        | 1.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 20        | 1.76%   |
| Elan ELAN:ARM-M4                                                           | 20        | 1.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 19        | 1.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 18        | 1.58%   |
| Unknown                                                                    | 17        | 1.49%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 15        | 1.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.23%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 13        | 1.14%   |
| Synaptics Fingerprint reader [HP G6]                                       | 13        | 1.14%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.05%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 9         | 0.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 0.79%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.7%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.61%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 7         | 0.61%   |
| AuthenTec AES2810                                                          | 7         | 0.61%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 0.61%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 183       | 46.92%  |
| Alcor Micro               | 107       | 27.44%  |
| Upek                      | 29        | 7.44%   |
| O2 Micro                  | 27        | 6.92%   |
| Lenovo                    | 20        | 5.13%   |
| SCM Microsystems          | 7         | 1.79%   |
| OmniKey                   | 5         | 1.28%   |
| Realtek Semiconductor     | 3         | 0.77%   |
| Gemalto (was Gemplus)     | 2         | 0.51%   |
| Aladdin Knowledge Systems | 2         | 0.51%   |
| Advanced Card Systems     | 2         | 0.51%   |
| Giesecke & Devrient       | 1         | 0.26%   |
| Clay Logic                | 1         | 0.26%   |
| Chicony Electronics       | 1         | 0.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 105       | 26.92%  |
| Broadcom BCM5880 Secure Applications Processor                               | 50        | 12.82%  |
| Broadcom 5880                                                                | 50        | 12.82%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 10.77%  |
| Broadcom 58200                                                               | 38        | 9.74%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 7.44%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 5.9%    |
| Lenovo Integrated Smart Card Reader                                          | 20        | 5.13%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 5         | 1.28%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.03%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.77%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 3         | 0.77%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.51%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.51%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.51%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.26%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.26%   |
| OmniKey CardMan 4321                                                         | 1         | 0.26%   |
| OmniKey CardMan 1021                                                         | 1         | 0.26%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.26%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.26%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.26%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.26%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.26%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.26%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.26%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 7167      | 68.42%  |
| 1     | 2707      | 25.84%  |
| 2     | 516       | 4.93%   |
| 3     | 68        | 0.65%   |
| 4     | 12        | 0.11%   |
| 5     | 3         | 0.03%   |
| 7     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1115      | 28.76%  |
| Net/wireless             | 653       | 16.84%  |
| Graphics card            | 649       | 16.74%  |
| Multimedia controller    | 460       | 11.86%  |
| Chipcard                 | 376       | 9.7%    |
| Bluetooth                | 128       | 3.3%    |
| Camera                   | 92        | 2.37%   |
| Communication controller | 70        | 1.81%   |
| Unassigned class         | 65        | 1.68%   |
| Sound                    | 62        | 1.6%    |
| Net/ethernet             | 52        | 1.34%   |
| Storage                  | 43        | 1.11%   |
| Network                  | 26        | 0.67%   |
| Card reader              | 26        | 0.67%   |
| Storage/raid             | 18        | 0.46%   |
| Modem                    | 14        | 0.36%   |
| Storage/ide              | 11        | 0.28%   |
| Storage/nvme             | 6         | 0.15%   |
| Firewire controller      | 4         | 0.1%    |
| Flash memory             | 2         | 0.05%   |
| Dvb card                 | 2         | 0.05%   |
| Wireless                 | 1         | 0.03%   |
| Unclassified device      | 1         | 0.03%   |
| Tv card                  | 1         | 0.03%   |

