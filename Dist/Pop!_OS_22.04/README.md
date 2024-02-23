Pop!_OS 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS_22.04/Desktop/README.md) and [notebooks](/Dist/Pop!_OS_22.04/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 5786

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
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [4312e9a007](https://linux-hardware.org/?probe=4312e9a007) | Oct 19, 2023 |
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
| HONOR         | NBR-WAX9                    | Notebook    | [68556b1e09](https://linux-hardware.org/?probe=68556b1e09) | Sep 27, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [056de6b9b3](https://linux-hardware.org/?probe=056de6b9b3) | Sep 27, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [9d86e194aa](https://linux-hardware.org/?probe=9d86e194aa) | Sep 27, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [240ff7b72a](https://linux-hardware.org/?probe=240ff7b72a) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [d9665a6ffd](https://linux-hardware.org/?probe=d9665a6ffd) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f9f08875e1](https://linux-hardware.org/?probe=f9f08875e1) | Sep 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [09a71cddc4](https://linux-hardware.org/?probe=09a71cddc4) | Sep 26, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [f11867f0b7](https://linux-hardware.org/?probe=f11867f0b7) | Sep 26, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.2.6-76060206-generic   | 835       | 18.53%  |
| 6.0.12-76060006-generic  | 476       | 10.56%  |
| 5.19.0-76051900-generic  | 449       | 9.96%   |
| 5.17.5-76051705-generic  | 420       | 9.32%   |
| 6.5.6-76060506-generic   | 303       | 6.72%   |
| 6.0.6-76060006-generic   | 302       | 6.7%    |
| 6.4.6-76060406-generic   | 296       | 6.57%   |
| 6.6.6-76060606-generic   | 220       | 4.88%   |
| 5.18.10-76051810-generic | 207       | 4.59%   |
| 5.17.15-76051715-generic | 186       | 4.13%   |
| 6.5.4-76060504-generic   | 130       | 2.88%   |
| 6.2.0-76060200-generic   | 122       | 2.71%   |
| 5.16.19-76051619-generic | 122       | 2.71%   |
| 6.0.2-76060002-generic   | 92        | 2.04%   |
| 6.1.11-76060111-generic  | 91        | 2.02%   |
| 5.19.16-76051916-generic | 43        | 0.95%   |
| 6.0.3-76060003-generic   | 40        | 0.89%   |
| 6.6.10-76060610-generic  | 39        | 0.87%   |
| 6.3.7-060307-generic     | 5         | 0.11%   |
| 6.5.7-060507-generic     | 3         | 0.07%   |
| 6.3.4-060304-generic     | 3         | 0.07%   |
| 6.1.0-1006-oem           | 3         | 0.07%   |
| 5.16.15-76051615-generic | 3         | 0.07%   |
| 6.5.5-x64v3-xanmod1      | 2         | 0.04%   |
| 6.5.12-x64v3-xanmod1     | 2         | 0.04%   |
| 6.4.0-060400-generic     | 2         | 0.04%   |
| 6.2.11-060211-generic    | 2         | 0.04%   |
| 6.1.8-060108-generic     | 2         | 0.04%   |
| 6.1.0-x64v1-xanmod1      | 2         | 0.04%   |
| 6.0.9-060009-generic     | 2         | 0.04%   |
| 6.0.2-x64v1-xanmod1      | 2         | 0.04%   |
| 5.19.12-xanmod1          | 2         | 0.04%   |
| 5.17.7-051707-generic    | 2         | 0.04%   |
| 5.17.5-051705-generic    | 2         | 0.04%   |
| 5.15.0-1044-raspi        | 2         | 0.04%   |
| 6.7.1-1-liquorix-amd64   | 1         | 0.02%   |
| 6.7.1-060701-generic     | 1         | 0.02%   |
| 6.6.9-x64v1-xanmod1      | 1         | 0.02%   |
| 6.6.11-surface-1         | 1         | 0.02%   |
| 6.5.8-x64v1-xanmod1      | 1         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 836       | 18.56%  |
| 6.0.12  | 477       | 10.59%  |
| 5.19.0  | 453       | 10.06%  |
| 5.17.5  | 423       | 9.39%   |
| 6.5.6   | 303       | 6.73%   |
| 6.0.6   | 303       | 6.73%   |
| 6.4.6   | 296       | 6.57%   |
| 6.6.6   | 220       | 4.88%   |
| 5.18.10 | 207       | 4.59%   |
| 5.17.15 | 186       | 4.13%   |
| 6.5.4   | 130       | 2.89%   |
| 6.2.0   | 122       | 2.71%   |
| 5.16.19 | 122       | 2.71%   |
| 6.0.2   | 95        | 2.11%   |
| 6.1.11  | 92        | 2.04%   |
| 5.19.16 | 43        | 0.95%   |
| 6.0.3   | 40        | 0.89%   |
| 6.6.10  | 39        | 0.87%   |
| 5.15.0  | 10        | 0.22%   |
| 6.1.0   | 6         | 0.13%   |
| 6.3.7   | 5         | 0.11%   |
| 6.5.7   | 4         | 0.09%   |
| 6.3.4   | 4         | 0.09%   |
| 6.1.8   | 3         | 0.07%   |
| 6.0.9   | 3         | 0.07%   |
| 5.16.15 | 3         | 0.07%   |
| 6.7.1   | 2         | 0.04%   |
| 6.5.5   | 2         | 0.04%   |
| 6.5.12  | 2         | 0.04%   |
| 6.5.10  | 2         | 0.04%   |
| 6.4.0   | 2         | 0.04%   |
| 6.3.9   | 2         | 0.04%   |
| 6.3.8   | 2         | 0.04%   |
| 6.3.1   | 2         | 0.04%   |
| 6.2.9   | 2         | 0.04%   |
| 6.2.2   | 2         | 0.04%   |
| 6.2.11  | 2         | 0.04%   |
| 6.1.9   | 2         | 0.04%   |
| 6.1.12  | 2         | 0.04%   |
| 6.0.0   | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 957       | 21.57%  |
| 6.0     | 893       | 20.13%  |
| 5.17    | 605       | 13.64%  |
| 5.19    | 498       | 11.23%  |
| 6.5     | 439       | 9.9%    |
| 6.4     | 303       | 6.83%   |
| 6.6     | 260       | 5.86%   |
| 5.18    | 213       | 4.8%    |
| 5.16    | 126       | 2.84%   |
| 6.1     | 109       | 2.46%   |
| 6.3     | 17        | 0.38%   |
| 5.15    | 13        | 0.29%   |
| 6.7     | 2         | 0.05%   |
| 5.4     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4018      | 99.83%  |
| aarch64 | 7         | 0.17%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 3906      | 96.78%  |
| KDE5            | 56        | 1.39%   |
| Unknown         | 27        | 0.67%   |
| X-Cinnamon      | 15        | 0.37%   |
| GNOME Flashback | 8         | 0.2%    |
| Cinnamon        | 6         | 0.15%   |
| Unity           | 5         | 0.12%   |
| LXQt            | 4         | 0.1%    |
| i3              | 3         | 0.07%   |
| XFCE            | 2         | 0.05%   |
| MATE            | 2         | 0.05%   |
| UKUI            | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3846      | 94.87%  |
| Wayland | 183       | 4.51%   |
| Unknown | 20        | 0.49%   |
| Tty     | 5         | 0.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2991      | 73.74%  |
| GDM3    | 1043      | 25.71%  |
| SDDM    | 12        | 0.3%    |
| GDM     | 8         | 0.2%    |
| LightDM | 2         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2385      | 58.77%  |
| en_GB   | 270       | 6.65%   |
| pt_BR   | 212       | 5.22%   |
| de_DE   | 199       | 4.9%    |
| C       | 146       | 3.6%    |
| en_AU   | 101       | 2.49%   |
| en_CA   | 80        | 1.97%   |
| it_IT   | 79        | 1.95%   |
| fr_FR   | 76        | 1.87%   |
| es_ES   | 49        | 1.21%   |
| ru_RU   | 46        | 1.13%   |
| pl_PL   | 39        | 0.96%   |
| Unknown | 26        | 0.64%   |
| sv_SE   | 21        | 0.52%   |
| pt_PT   | 21        | 0.52%   |
| nb_NO   | 21        | 0.52%   |
| en_IN   | 21        | 0.52%   |
| fi_FI   | 17        | 0.42%   |
| nl_NL   | 16        | 0.39%   |
| en_NZ   | 15        | 0.37%   |
| tr_TR   | 14        | 0.34%   |
| es_CL   | 13        | 0.32%   |
| de_CH   | 13        | 0.32%   |
| es_MX   | 12        | 0.3%    |
| en_IE   | 12        | 0.3%    |
| da_DK   | 12        | 0.3%    |
| fr_CA   | 11        | 0.27%   |
| es_AR   | 11        | 0.27%   |
| en_DK   | 11        | 0.27%   |
| ja_JP   | 10        | 0.25%   |
| en_ZA   | 10        | 0.25%   |
| de_AT   | 9         | 0.22%   |
| cs_CZ   | 9         | 0.22%   |
| es_CO   | 5         | 0.12%   |
| zh_TW   | 4         | 0.1%    |
| hu_HU   | 4         | 0.1%    |
| fr_CH   | 4         | 0.1%    |
| fr_BE   | 4         | 0.1%    |
| zh_CN   | 3         | 0.07%   |
| sk_SK   | 3         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3046      | 75.1%   |
| EFI  | 1010      | 24.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3825      | 94.65%  |
| Btrfs   | 115       | 2.85%   |
| Overlay | 83        | 2.05%   |
| Xfs     | 11        | 0.27%   |
| Zfs     | 5         | 0.12%   |
| Tmpfs   | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2966      | 73.13%  |
| GPT     | 1028      | 25.35%  |
| MBR     | 62        | 1.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3898      | 96.56%  |
| Yes       | 139       | 3.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3607      | 89.22%  |
| Yes       | 436       | 10.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 728       | 18.09%  |
| Lenovo                  | 593       | 14.73%  |
| Dell                    | 485       | 12.05%  |
| Hewlett-Packard         | 462       | 11.48%  |
| MSI                     | 310       | 7.7%    |
| Gigabyte Technology     | 259       | 6.43%   |
| Apple                   | 216       | 5.37%   |
| Acer                    | 181       | 4.5%    |
| ASRock                  | 119       | 2.96%   |
| System76                | 91        | 2.26%   |
| Intel                   | 48        | 1.19%   |
| Samsung Electronics     | 43        | 1.07%   |
| Toshiba                 | 41        | 1.02%   |
| HUAWEI                  | 32        | 0.8%    |
| Alienware               | 26        | 0.65%   |
| Unknown                 | 25        | 0.62%   |
| Microsoft               | 24        | 0.6%    |
| Google                  | 21        | 0.52%   |
| Fujitsu                 | 20        | 0.5%    |
| Notebook                | 19        | 0.47%   |
| AZW                     | 13        | 0.32%   |
| Positivo                | 12        | 0.3%    |
| Sony                    | 11        | 0.27%   |
| Razer                   | 11        | 0.27%   |
| GPU Company             | 10        | 0.25%   |
| BESSTAR Tech            | 10        | 0.25%   |
| Framework               | 9         | 0.22%   |
| Timi                    | 8         | 0.2%    |
| Raspberry Pi Foundation | 7         | 0.17%   |
| HONOR                   | 7         | 0.17%   |
| Biostar                 | 7         | 0.17%   |
| Supermicro              | 6         | 0.15%   |
| PC Specialist           | 6         | 0.15%   |
| MACHINIST               | 6         | 0.15%   |
| Foxconn                 | 6         | 0.15%   |
| Avell High Performance  | 6         | 0.15%   |
| Pegatron                | 5         | 0.12%   |
| ZOTAC                   | 4         | 0.1%    |
| TUXEDO                  | 4         | 0.1%    |
| Schenker                | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 33        | 0.82%   |
| ASUS All Series                     | 28        | 0.7%    |
| System76 Oryx Pro                   | 19        | 0.47%   |
| ASUS ROG STRIX B550-F GAMING        | 18        | 0.45%   |
| System76 Lemur Pro                  | 16        | 0.4%    |
| Apple MacBookAir7,2                 | 15        | 0.37%   |
| System76 Gazelle                    | 13        | 0.32%   |
| HP Dev One Notebook PC              | 13        | 0.32%   |
| Apple MacBookAir6,2                 | 13        | 0.32%   |
| Apple MacBookPro8,1                 | 12        | 0.3%    |
| Apple MacBookPro12,1                | 12        | 0.3%    |
| ASUS ROG STRIX B450-F GAMING        | 11        | 0.27%   |
| ASUS TUF Gaming X570-PLUS           | 10        | 0.25%   |
| ASUS ROG STRIX B550-I GAMING        | 10        | 0.25%   |
| Apple MacBookPro9,2                 | 10        | 0.25%   |
| Gigabyte X570 AORUS ELITE           | 9         | 0.22%   |
| Apple MacBookPro11,3                | 9         | 0.22%   |
| System76 Darter Pro                 | 8         | 0.2%    |
| MSI MS-7C95                         | 8         | 0.2%    |
| MSI MS-7B86                         | 8         | 0.2%    |
| Gigabyte B450 AORUS M               | 8         | 0.2%    |
| Dell XPS 15 9570                    | 8         | 0.2%    |
| Dell XPS 15 9520                    | 8         | 0.2%    |
| ASUS TUF Gaming B550-PLUS           | 8         | 0.2%    |
| Apple MacBookPro7,1                 | 8         | 0.2%    |
| System76 Pangolin                   | 7         | 0.17%   |
| System76 Galago Pro                 | 7         | 0.17%   |
| MSI MS-7C91                         | 7         | 0.17%   |
| MSI MS-7C37                         | 7         | 0.17%   |
| MSI MS-7C02                         | 7         | 0.17%   |
| MSI MS-7A38                         | 7         | 0.17%   |
| Lenovo Legion 5 15ACH6H 82JU        | 7         | 0.17%   |
| Lenovo IdeaPad S145-15API 81V7      | 7         | 0.17%   |
| Lenovo IdeaPad Gaming 3 15IAH7 82S9 | 7         | 0.17%   |
| HP Notebook                         | 7         | 0.17%   |
| Gigabyte A320M-S2H                  | 7         | 0.17%   |
| Dell XPS 15 7590                    | 7         | 0.17%   |
| ASUS PRIME B450M-A                  | 7         | 0.17%   |
| Apple MacBookPro11,1                | 7         | 0.17%   |
| Acer Nitro AN515-58                 | 7         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 236       | 5.86%   |
| ASUS ROG           | 193       | 4.8%    |
| Lenovo IdeaPad     | 132       | 3.28%   |
| Dell Inspiron      | 119       | 2.96%   |
| Acer Aspire        | 109       | 2.71%   |
| Dell Latitude      | 105       | 2.61%   |
| Dell XPS           | 88        | 2.19%   |
| ASUS PRIME         | 77        | 1.91%   |
| HP Pavilion        | 72        | 1.79%   |
| ASUS TUF           | 67        | 1.66%   |
| ASUS VivoBook      | 64        | 1.59%   |
| Dell Precision     | 62        | 1.54%   |
| HP EliteBook       | 59        | 1.47%   |
| Lenovo Legion      | 56        | 1.39%   |
| HP Laptop          | 52        | 1.29%   |
| Dell OptiPlex      | 44        | 1.09%   |
| Lenovo Yoga        | 41        | 1.02%   |
| HP ProBook         | 40        | 0.99%   |
| ASUS ASUS          | 37        | 0.92%   |
| HP ENVY            | 36        | 0.89%   |
| Toshiba Satellite  | 34        | 0.84%   |
| Unknown            | 33        | 0.82%   |
| Lenovo ThinkCentre | 28        | 0.7%    |
| ASUS ZenBook       | 28        | 0.7%    |
| ASUS All           | 28        | 0.7%    |
| Acer Swift         | 27        | 0.67%   |
| Gigabyte X570      | 26        | 0.65%   |
| Apple MacBookPro11 | 25        | 0.62%   |
| Microsoft Surface  | 24        | 0.6%    |
| HP ZBook           | 24        | 0.6%    |
| Dell Vostro        | 24        | 0.6%    |
| Acer Nitro         | 24        | 0.6%    |
| HP OMEN            | 23        | 0.57%   |
| HP Compaq          | 23        | 0.57%   |
| Gigabyte B450      | 20        | 0.5%    |
| System76 Oryx      | 19        | 0.47%   |
| HP EliteDesk       | 18        | 0.45%   |
| System76 Lemur     | 16        | 0.4%    |
| Lenovo ThinkBook   | 16        | 0.4%    |
| Apple MacBookPro8  | 15        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 546       | 13.57%  |
| 2020    | 492       | 12.22%  |
| 2022    | 445       | 11.06%  |
| 2019    | 375       | 9.32%   |
| 2018    | 370       | 9.19%   |
| 2013    | 224       | 5.57%   |
| 2017    | 221       | 5.49%   |
| 2012    | 218       | 5.42%   |
| 2014    | 192       | 4.77%   |
| 2011    | 183       | 4.55%   |
| 2015    | 174       | 4.32%   |
| 2016    | 172       | 4.27%   |
| 2023    | 136       | 3.38%   |
| 2010    | 103       | 2.56%   |
| 2009    | 87        | 2.16%   |
| 2008    | 43        | 1.07%   |
| 2007    | 33        | 0.82%   |
| Unknown | 8         | 0.2%    |
| 2006    | 2         | 0.05%   |
| 2005    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2309      | 57.37%  |
| Desktop        | 1387      | 34.46%  |
| Convertible    | 135       | 3.35%   |
| Mini pc        | 71        | 1.76%   |
| All in one     | 57        | 1.42%   |
| Tablet         | 40        | 0.99%   |
| Server         | 18        | 0.45%   |
| System on chip | 8         | 0.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4022      | 99.88%  |
| Enabled  | 5         | 0.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3944      | 97.99%  |
| Yes  | 81        | 2.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1068      | 26.25%  |
| 4.01-8.0        | 862       | 21.18%  |
| 8.01-16.0       | 722       | 17.74%  |
| 32.01-64.0      | 709       | 17.42%  |
| 3.01-4.0        | 342       | 8.41%   |
| 64.01-256.0     | 229       | 5.63%   |
| 24.01-32.0      | 112       | 2.75%   |
| 1.01-2.0        | 14        | 0.34%   |
| 2.01-3.0        | 8         | 0.2%    |
| More than 256.0 | 3         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1508      | 34.48%  |
| 2.01-3.0    | 1029      | 23.53%  |
| 3.01-4.0    | 943       | 21.56%  |
| 8.01-16.0   | 477       | 10.91%  |
| 1.01-2.0    | 315       | 7.2%    |
| 16.01-24.0  | 64        | 1.46%   |
| 24.01-32.0  | 19        | 0.43%   |
| 32.01-64.0  | 12        | 0.27%   |
| 0.51-1.0    | 4         | 0.09%   |
| 64.01-256.0 | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2352      | 57.37%  |
| 2      | 1075      | 26.22%  |
| 3      | 356       | 8.68%   |
| 4      | 156       | 3.8%    |
| 5      | 73        | 1.78%   |
| 6      | 36        | 0.88%   |
| 7      | 19        | 0.46%   |
| 0      | 18        | 0.44%   |
| 9      | 5         | 0.12%   |
| 8      | 4         | 0.1%    |
| 11     | 2         | 0.05%   |
| 10     | 2         | 0.05%   |
| 26     | 1         | 0.02%   |
| 19     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3146      | 77.91%  |
| Yes       | 892       | 22.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3299      | 81.58%  |
| No        | 745       | 18.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3384      | 83.89%  |
| No        | 650       | 16.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2935      | 72.49%  |
| No        | 1114      | 27.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1251      | 30.91%  |
| Brazil       | 300       | 7.41%   |
| Germany      | 295       | 7.29%   |
| UK           | 185       | 4.57%   |
| Canada       | 178       | 4.4%    |
| Italy        | 145       | 3.58%   |
| Australia    | 132       | 3.26%   |
| France       | 109       | 2.69%   |
| India        | 108       | 2.67%   |
| Russia       | 78        | 1.93%   |
| Netherlands  | 78        | 1.93%   |
| Poland       | 68        | 1.68%   |
| Sweden       | 63        | 1.56%   |
| Spain        | 63        | 1.56%   |
| Norway       | 54        | 1.33%   |
| Mexico       | 46        | 1.14%   |
| Finland      | 44        | 1.09%   |
| Portugal     | 43        | 1.06%   |
| Switzerland  | 37        | 0.91%   |
| Turkey       | 33        | 0.82%   |
| Austria      | 33        | 0.82%   |
| Czechia      | 32        | 0.79%   |
| Denmark      | 31        | 0.77%   |
| Indonesia    | 30        | 0.74%   |
| New Zealand  | 28        | 0.69%   |
| Greece       | 28        | 0.69%   |
| Argentina    | 28        | 0.69%   |
| Philippines  | 27        | 0.67%   |
| Chile        | 26        | 0.64%   |
| Belgium      | 25        | 0.62%   |
| Romania      | 24        | 0.59%   |
| Japan        | 23        | 0.57%   |
| Hungary      | 23        | 0.57%   |
| Serbia       | 20        | 0.49%   |
| South Africa | 19        | 0.47%   |
| Ireland      | 19        | 0.47%   |
| Bulgaria     | 18        | 0.44%   |
| Thailand     | 16        | 0.4%    |
| Malaysia     | 14        | 0.35%   |
| Hong Kong    | 13        | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Melbourne      | 34        | 0.81%   |
| Sao Paulo      | 31        | 0.73%   |
| Sydney         | 29        | 0.69%   |
| Helsinki       | 28        | 0.66%   |
| Berlin         | 28        | 0.66%   |
| Rio de Janeiro | 25        | 0.59%   |
| Milan          | 25        | 0.59%   |
| Brisbane       | 23        | 0.55%   |
| Denver         | 22        | 0.52%   |
| Seattle        | 21        | 0.5%    |
| Oslo           | 20        | 0.47%   |
| Chicago        | 20        | 0.47%   |
| Vienna         | 19        | 0.45%   |
| Moscow         | 18        | 0.43%   |
| Warsaw         | 17        | 0.4%    |
| New York       | 17        | 0.4%    |
| Madrid         | 17        | 0.4%    |
| Istanbul       | 17        | 0.4%    |
| Bengaluru      | 17        | 0.4%    |
| Rome           | 16        | 0.38%   |
| Hamburg        | 16        | 0.38%   |
| Toronto        | 15        | 0.36%   |
| London         | 15        | 0.36%   |
| Prague         | 14        | 0.33%   |
| Zurich         | 13        | 0.31%   |
| Stockholm      | 13        | 0.31%   |
| Lisbon         | 13        | 0.31%   |
| Edmonton       | 13        | 0.31%   |
| Dallas         | 13        | 0.31%   |
| Belgrade       | 13        | 0.31%   |
| Amsterdam      | 13        | 0.31%   |
| Sofia          | 12        | 0.28%   |
| San Antonio    | 12        | 0.28%   |
| Dublin         | 12        | 0.28%   |
| Calgary        | 12        | 0.28%   |
| Auckland       | 12        | 0.28%   |
| Singapore      | 11        | 0.26%   |
| Santiago       | 11        | 0.26%   |
| Portland       | 11        | 0.26%   |
| Perth          | 11        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1199      | 1767   | 19.46%  |
| WDC                         | 643       | 878    | 10.43%  |
| Seagate                     | 630       | 899    | 10.22%  |
| SanDisk                     | 473       | 609    | 7.68%   |
| Kingston                    | 317       | 386    | 5.14%   |
| Toshiba                     | 274       | 333    | 4.45%   |
| Crucial                     | 264       | 354    | 4.28%   |
| SK hynix                    | 223       | 263    | 3.62%   |
| Intel                       | 168       | 216    | 2.73%   |
| Micron Technology           | 160       | 189    | 2.6%    |
| Unknown                     | 154       | 212    | 2.5%    |
| Apple                       | 122       | 140    | 1.98%   |
| Phison Electronics          | 90        | 127    | 1.46%   |
| Hitachi                     | 90        | 132    | 1.46%   |
| Micron/Crucial Technology   | 86        | 113    | 1.4%    |
| A-DATA Technology           | 85        | 96     | 1.38%   |
| HGST                        | 84        | 99     | 1.36%   |
| KIOXIA                      | 69        | 75     | 1.12%   |
| China                       | 69        | 89     | 1.12%   |
| Kingston Technology Company | 58        | 70     | 0.94%   |
| Silicon Motion              | 57        | 69     | 0.93%   |
| PNY                         | 57        | 71     | 0.93%   |
| Phison                      | 57        | 69     | 0.93%   |
| SPCC                        | 34        | 48     | 0.55%   |
| Unknown                     | 28        | 32     | 0.45%   |
| Netac                       | 26        | 28     | 0.42%   |
| Intenso                     | 26        | 37     | 0.42%   |
| Team                        | 25        | 30     | 0.41%   |
| ADATA Technology            | 24        | 27     | 0.39%   |
| Transcend                   | 20        | 23     | 0.32%   |
| Realtek Semiconductor       | 20        | 22     | 0.32%   |
| JMicron Technology          | 20        | 32     | 0.32%   |
| Patriot                     | 19        | 24     | 0.31%   |
| KingSpec                    | 18        | 19     | 0.29%   |
| OCZ                         | 17        | 23     | 0.28%   |
| LITEON                      | 17        | 21     | 0.28%   |
| LITEONIT                    | 15        | 27     | 0.24%   |
| Lexar                       | 15        | 19     | 0.24%   |
| XPG                         | 13        | 16     | 0.21%   |
| Hewlett-Packard             | 13        | 16     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 160       | 2.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 104       | 1.53%   |
| Kingston SA400S37240G 240GB SSD                       | 74        | 1.09%   |
| Samsung SSD 850 EVO 500GB                             | 49        | 0.72%   |
| Samsung SSD 850 EVO 250GB                             | 47        | 0.69%   |
| Samsung SSD 860 EVO 1TB                               | 45        | 0.66%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 45        | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 44        | 0.65%   |
| SanDisk NVMe SSD Drive 1TB                            | 43        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB                        | 42        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 42        | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB                        | 41        | 0.6%    |
| Kingston SA400S37480G 480GB SSD                       | 40        | 0.59%   |
| Samsung SSD 860 EVO 500GB                             | 39        | 0.57%   |
| Crucial CT1000MX500SSD1 1TB                           | 39        | 0.57%   |
| Samsung NVMe SSD Drive 1TB                            | 36        | 0.53%   |
| Phison E12 NVMe Controller 1TB                        | 35        | 0.52%   |
| Samsung SSD 980 1TB                                   | 34        | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                        | 32        | 0.47%   |
| Kingston SA400S37120G 120GB SSD                       | 32        | 0.47%   |
| Crucial CT240BX500SSD1 240GB                          | 30        | 0.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 29        | 0.43%   |
| Samsung NVMe SSD Drive 500GB                          | 29        | 0.43%   |
| Crucial CT500MX500SSD1 500GB                          | 29        | 0.43%   |
| Unknown                                               | 28        | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 27        | 0.4%    |
| Toshiba MQ01ABD100 1TB                                | 26        | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB                          | 26        | 0.38%   |
| Samsung SSD 870 QVO 1TB                               | 26        | 0.38%   |
| Intel SSD 660P Series 1024GB                          | 26        | 0.38%   |
| Sandisk WD Black SN850 1024GB                         | 25        | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB                        | 24        | 0.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 24        | 0.35%   |
| Unknown MMC Card  64GB                                | 23        | 0.34%   |
| Toshiba MQ04ABF100 1TB                                | 23        | 0.34%   |
| Seagate Expansion 1TB                                 | 23        | 0.34%   |
| Samsung SSD 980 PRO 1TB                               | 23        | 0.34%   |
| HGST HTS721010A9E630 1TB                              | 23        | 0.34%   |
| Unknown MMC Card  32GB                                | 22        | 0.32%   |
| Seagate ST500DM002-1BD142 500GB                       | 22        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 608       | 856    | 38.92%  |
| WDC                 | 445       | 625    | 28.49%  |
| Toshiba             | 192       | 231    | 12.29%  |
| Hitachi             | 90        | 132    | 5.76%   |
| HGST                | 84        | 99     | 5.38%   |
| Samsung Electronics | 50        | 59     | 3.2%    |
| Apple               | 26        | 30     | 1.66%   |
| Unknown             | 20        | 24     | 1.28%   |
| JMicron Technology  | 15        | 24     | 0.96%   |
| Fujitsu             | 6         | 10     | 0.38%   |
| TO Exter            | 4         | 4      | 0.26%   |
| Maxtor              | 3         | 3      | 0.19%   |
| StoreJet            | 2         | 2      | 0.13%   |
| SABRENT             | 2         | 3      | 0.13%   |
| Intenso             | 2         | 6      | 0.13%   |
| External            | 2         | 2      | 0.13%   |
| ASMT                | 2         | 2      | 0.13%   |
| WD MediaMax         | 1         | 2      | 0.06%   |
| RSH-339             | 1         | 1      | 0.06%   |
| MaxDigital          | 1         | 1      | 0.06%   |
| LaCie               | 1         | 2      | 0.06%   |
| HGST HDN            | 1         | 1      | 0.06%   |
| DELLBOSS            | 1         | 1      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |
| Asm                 | 1         | 1      | 0.06%   |
| Unknown             | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 467       | 664    | 23.39%  |
| Kingston            | 239       | 282    | 11.97%  |
| Crucial             | 228       | 300    | 11.42%  |
| SanDisk             | 161       | 198    | 8.06%   |
| WDC                 | 118       | 141    | 5.91%   |
| Apple               | 82        | 90     | 4.11%   |
| China               | 68        | 88     | 3.41%   |
| A-DATA Technology   | 60        | 66     | 3%      |
| PNY                 | 55        | 69     | 2.75%   |
| Intel               | 38        | 50     | 1.9%    |
| SK hynix            | 34        | 39     | 1.7%    |
| Micron Technology   | 32        | 35     | 1.6%    |
| SPCC                | 28        | 34     | 1.4%    |
| Toshiba             | 24        | 25     | 1.2%    |
| Netac               | 21        | 23     | 1.05%   |
| Transcend           | 18        | 21     | 0.9%    |
| Patriot             | 18        | 23     | 0.9%    |
| KingSpec            | 18        | 19     | 0.9%    |
| Intenso             | 18        | 24     | 0.9%    |
| Team                | 17        | 21     | 0.85%   |
| OCZ                 | 17        | 23     | 0.85%   |
| LITEONIT            | 15        | 27     | 0.75%   |
| LITEON              | 14        | 18     | 0.7%    |
| Hewlett-Packard     | 10        | 13     | 0.5%    |
| Apacer              | 10        | 15     | 0.5%    |
| Lexar               | 9         | 12     | 0.45%   |
| SABRENT             | 7         | 10     | 0.35%   |
| Corsair             | 7         | 9      | 0.35%   |
| Seagate             | 6         | 7      | 0.3%    |
| KingDian            | 6         | 13     | 0.3%    |
| GOODRAM             | 6         | 6      | 0.3%    |
| Gigabyte Technology | 6         | 6      | 0.3%    |
| Mushkin             | 5         | 7      | 0.25%   |
| FIKWOT              | 5         | 8      | 0.25%   |
| Fanxiang            | 5         | 5      | 0.25%   |
| Dogfish             | 5         | 6      | 0.25%   |
| Unknown             | 5         | 5      | 0.25%   |
| Verbatim            | 4         | 8      | 0.2%    |
| OWC                 | 3         | 3      | 0.15%   |
| MyDigitalSSD        | 3         | 3      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2165      | 3176   | 39.81%  |
| SSD     | 1711      | 2536   | 31.46%  |
| HDD     | 1320      | 2123   | 24.27%  |
| MMC     | 124       | 146    | 2.28%   |
| Unknown | 119       | 197    | 2.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2428      | 4426   | 48.77%  |
| NVMe | 2162      | 3164   | 43.43%  |
| SAS  | 264       | 442    | 5.3%    |
| MMC  | 124       | 146    | 2.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1673      | 2431   | 52%     |
| 0.51-1.0   | 1007      | 1378   | 31.3%   |
| 1.01-2.0   | 312       | 463    | 9.7%    |
| 3.01-4.0   | 99        | 166    | 3.08%   |
| 4.01-10.0  | 74        | 131    | 2.3%    |
| 2.01-3.0   | 43        | 71     | 1.34%   |
| 10.01-20.0 | 9         | 19     | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1112      | 26.68%  |
| 251-500        | 1054      | 25.29%  |
| 501-1000       | 884       | 21.21%  |
| 1001-2000      | 409       | 9.81%   |
| More than 3000 | 235       | 5.64%   |
| 2001-3000      | 157       | 3.77%   |
| 51-100         | 130       | 3.12%   |
| 1-20           | 100       | 2.4%    |
| 21-50          | 58        | 1.39%   |
| Unknown        | 29        | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1220      | 28.1%   |
| 21-50          | 956       | 22.02%  |
| 101-250        | 656       | 15.11%  |
| 51-100         | 542       | 12.49%  |
| 251-500        | 412       | 9.49%   |
| 501-1000       | 254       | 5.85%   |
| 1001-2000      | 140       | 3.23%   |
| More than 3000 | 84        | 1.94%   |
| 2001-3000      | 48        | 1.11%   |
| Unknown        | 29        | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1TB       | 3         | 3      | 2.42%   |
| HGST HTS725050A7E630 500GB               | 3         | 4      | 2.42%   |
| WDC WD10JPVX-60JC3T0 1TB                 | 2         | 2      | 1.61%   |
| Seagate ST3250310AS 250GB                | 2         | 4      | 1.61%   |
| Seagate ST1000LX015-1U7172 1TB           | 2         | 2      | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 2      | 1.61%   |
| Samsung Electronics SSD 970 EVO Plus 1TB | 2         | 2      | 1.61%   |
| Samsung Electronics SSD 850 EVO 250GB    | 2         | 2      | 1.61%   |
| Crucial CT525MX300SSD1 528GB             | 2         | 2      | 1.61%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD         | 1         | 1      | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.81%   |
| WDC WDS100T2B0B-00YS70 1TB SSD           | 1         | 1      | 0.81%   |
| WDC WD60EFRX-68L0BN1 6TB                 | 1         | 1      | 0.81%   |
| WDC WD5001AALS-00J7B1 500GB              | 1         | 1      | 0.81%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 1      | 0.81%   |
| WDC WD5000AADS-00S9B0 500GB              | 1         | 1      | 0.81%   |
| WDC WD3200BEKX-75B7WT0 320GB             | 1         | 1      | 0.81%   |
| WDC WD3200BEKT-60PVMT0 320GB             | 1         | 1      | 0.81%   |
| WDC WD20PURZ-85AKKY0 2TB                 | 1         | 1      | 0.81%   |
| WDC WD20PURX-64P6ZY0 2TB                 | 1         | 1      | 0.81%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1         | 1      | 0.81%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1         | 1      | 0.81%   |
| WDC WD20EFRX-68AX9N0 2TB                 | 1         | 8      | 0.81%   |
| WDC WD15EADS-00P8B0 1TB                  | 1         | 1      | 0.81%   |
| WDC WD10SPZX-24Z10T0 1TB                 | 1         | 1      | 0.81%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 1      | 0.81%   |
| WDC WD10SPZX-16Z10T0 1TB                 | 1         | 1      | 0.81%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.81%   |
| WDC WD10EZEX-60ZF5A0 1TB                 | 1         | 1      | 0.81%   |
| WDC WD10EZEX-60WN4A0 1TB                 | 1         | 1      | 0.81%   |
| WDC WD10EZEX-00BN5A0 1TB                 | 1         | 1      | 0.81%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1         | 1      | 0.81%   |
| WDC WD1002FAEX-00Z3A0 1TB                | 1         | 1      | 0.81%   |
| WDC WD1001FALS-00E8B0 1TB                | 1         | 1      | 0.81%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB     | 1         | 1      | 0.81%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.81%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 0.81%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 0.81%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.81%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 1      | 0.81%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 35     | 22.69%  |
| Seagate             | 23        | 27     | 19.33%  |
| Samsung Electronics | 15        | 17     | 12.61%  |
| HGST                | 8         | 9      | 6.72%   |
| Toshiba             | 7         | 7      | 5.88%   |
| SK hynix            | 7         | 7      | 5.88%   |
| Hitachi             | 4         | 6      | 3.36%   |
| Kingston            | 3         | 4      | 2.52%   |
| Intel               | 3         | 3      | 2.52%   |
| Crucial             | 3         | 3      | 2.52%   |
| A-DATA Technology   | 3         | 3      | 2.52%   |
| Team                | 2         | 2      | 1.68%   |
| SanDisk             | 2         | 2      | 1.68%   |
| Micron Technology   | 2         | 4      | 1.68%   |
| Silicon Motion      | 1         | 1      | 0.84%   |
| SABRENT             | 1         | 1      | 0.84%   |
| Plextor             | 1         | 1      | 0.84%   |
| LITEON              | 1         | 1      | 0.84%   |
| Lexar               | 1         | 1      | 0.84%   |
| Leven               | 1         | 1      | 0.84%   |
| Flashwar            | 1         | 1      | 0.84%   |
| China               | 1         | 1      | 0.84%   |
| BAITITON            | 1         | 1      | 0.84%   |
| Apple               | 1         | 1      | 0.84%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 31     | 34.33%  |
| Seagate             | 23        | 27     | 34.33%  |
| HGST                | 8         | 9      | 11.94%  |
| Toshiba             | 5         | 5      | 7.46%   |
| Hitachi             | 4         | 6      | 5.97%   |
| Samsung Electronics | 3         | 3      | 4.48%   |
| Apple               | 1         | 1      | 1.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 65        | 82     | 55.08%  |
| SSD  | 34        | 36     | 28.81%  |
| NVMe | 19        | 21     | 16.1%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 25%     |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 25%     |
| KingDian S400 120GB               | 1         | 2      | 25%     |
| Intenso JAJP600M1TB               | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| KingDian            | 1         | 2      | 25%     |
| Intenso             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3081      | 6307   | 72.22%  |
| Works    | 1068      | 1727   | 25.04%  |
| Malfunc  | 113       | 139    | 2.65%   |
| Failed   | 4         | 5      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2211      | 37.93%  |
| AMD                                     | 990       | 16.98%  |
| Samsung Electronics                     | 841       | 14.43%  |
| SanDisk                                 | 403       | 6.91%   |
| SK hynix                                | 190       | 3.26%   |
| Phison Electronics                      | 156       | 2.68%   |
| Kingston Technology Company             | 136       | 2.33%   |
| Micron Technology                       | 128       | 2.2%    |
| Micron/Crucial Technology               | 122       | 2.09%   |
| ASMedia Technology                      | 91        | 1.56%   |
| Silicon Motion                          | 69        | 1.18%   |
| KIOXIA                                  | 67        | 1.15%   |
| Toshiba America Info Systems            | 66        | 1.13%   |
| Nvidia                                  | 54        | 0.93%   |
| ADATA Technology                        | 51        | 0.87%   |
| Marvell Technology Group                | 47        | 0.81%   |
| Realtek Semiconductor                   | 30        | 0.51%   |
| Solid State Storage Technology          | 26        | 0.45%   |
| JMicron Technology                      | 20        | 0.34%   |
| Union Memory (Shenzhen)                 | 17        | 0.29%   |
| Apple                                   | 15        | 0.26%   |
| Seagate Technology                      | 14        | 0.24%   |
| MAXIO Technology (Hangzhou)             | 12        | 0.21%   |
| Broadcom / LSI                          | 11        | 0.19%   |
| Shenzhen Longsys Electronics            | 10        | 0.17%   |
| Solidigm                                | 9         | 0.15%   |
| LSI Logic / Symbios Logic               | 7         | 0.12%   |
| INNOGRIT                                | 7         | 0.12%   |
| Lite-On Technology                      | 6         | 0.1%    |
| Hewlett-Packard                         | 4         | 0.07%   |
| Yangtze Memory Technologies             | 3         | 0.05%   |
| VIA Technologies                        | 3         | 0.05%   |
| Netac Technology                        | 3         | 0.05%   |
| Transcend                               | 2         | 0.03%   |
| Silicon Image                           | 2         | 0.03%   |
| Western Digital                         | 1         | 0.02%   |
| Shenzhen Unionmemory Information System | 1         | 0.02%   |
| O2 Micro                                | 1         | 0.02%   |
| Hosin Global Electronics                | 1         | 0.02%   |
| Biwin Storage Technology                | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 652       | 10.14%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 352       | 5.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 202       | 3.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 175       | 2.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 165       | 2.57%   |
| AMD 500 Series Chipset SATA Controller                                         | 165       | 2.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 161       | 2.5%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 159       | 2.47%   |
| AMD 400 Series Chipset SATA Controller                                         | 144       | 2.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 122       | 1.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 114       | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 109       | 1.69%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 91        | 1.41%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 88        | 1.37%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 84        | 1.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 82        | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 75        | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 73        | 1.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 73        | 1.13%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 71        | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 67        | 1.04%   |
| Phison E12 NVMe Controller                                                     | 66        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 66        | 1.03%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 65        | 1.01%   |
| Intel SATA Controller [RAID mode]                                              | 65        | 1.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 61        | 0.95%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 57        | 0.89%   |
| Intel SSD 660P Series                                                          | 55        | 0.86%   |
| AMD 600 Series Chipset SATA Controller                                         | 55        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 52        | 0.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 48        | 0.75%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 47        | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 47        | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 46        | 0.72%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 45        | 0.7%    |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 44        | 0.68%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 39        | 0.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 39        | 0.61%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 38        | 0.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 37        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2817      | 50.12%  |
| NVMe | 2157      | 38.38%  |
| RAID | 406       | 7.22%   |
| IDE  | 221       | 3.93%   |
| SAS  | 17        | 0.3%    |
| SCSI | 2         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2721      | 67.6%   |
| AMD    | 1297      | 32.22%  |
| ARM    | 7         | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 56        | 1.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 52        | 1.29%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 47        | 1.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 45        | 1.12%   |
| AMD Ryzen 5 3600 6-Core Processor             | 45        | 1.12%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 41        | 1.02%   |
| Intel 12th Gen Core i7-12700H                 | 41        | 1.02%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 40        | 0.99%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 40        | 0.99%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 39        | 0.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 36        | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 36        | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 34        | 0.84%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 34        | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 33        | 0.82%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 33        | 0.82%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 32        | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 32        | 0.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 31        | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 31        | 0.77%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 31        | 0.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 30        | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 28        | 0.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 28        | 0.69%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 27        | 0.67%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 27        | 0.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 25        | 0.62%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 24        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 23        | 0.57%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 23        | 0.57%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 22        | 0.55%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 22        | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 20        | 0.5%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 19        | 0.47%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 18        | 0.45%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 18        | 0.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 18        | 0.45%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 18        | 0.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 17        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 838       | 20.79%  |
| Intel Core i5           | 773       | 19.18%  |
| Other                   | 547       | 13.57%  |
| AMD Ryzen 5             | 416       | 10.32%  |
| AMD Ryzen 7             | 405       | 10.05%  |
| Intel Core i3           | 181       | 4.49%   |
| AMD Ryzen 9             | 160       | 3.97%   |
| Intel Celeron           | 94        | 2.33%   |
| Intel Core 2 Duo        | 84        | 2.08%   |
| Intel Xeon              | 83        | 2.06%   |
| AMD FX                  | 45        | 1.12%   |
| AMD Ryzen 3             | 40        | 0.99%   |
| Intel Pentium           | 36        | 0.89%   |
| Intel Core i9           | 36        | 0.89%   |
| AMD Ryzen 7 PRO         | 36        | 0.89%   |
| AMD A8                  | 24        | 0.6%    |
| AMD A10                 | 22        | 0.55%   |
| AMD Ryzen 5 PRO         | 16        | 0.4%    |
| AMD A6                  | 16        | 0.4%    |
| AMD Ryzen Threadripper  | 13        | 0.32%   |
| Intel Core 2 Quad       | 12        | 0.3%    |
| Intel Pentium Dual-Core | 11        | 0.27%   |
| AMD A4                  | 11        | 0.27%   |
| AMD Athlon              | 10        | 0.25%   |
| Intel Pentium Silver    | 9         | 0.22%   |
| AMD Athlon II X2        | 9         | 0.22%   |
| Intel Pentium Gold      | 8         | 0.2%    |
| AMD Athlon II X4        | 7         | 0.17%   |
| Intel Atom              | 6         | 0.15%   |
| AMD Phenom II X4        | 6         | 0.15%   |
| AMD E                   | 6         | 0.15%   |
| Intel Core m5           | 5         | 0.12%   |
| Intel Core 2            | 5         | 0.12%   |
| AMD E1                  | 5         | 0.12%   |
| AMD Ryzen 3 PRO         | 4         | 0.1%    |
| AMD Phenom II X6        | 4         | 0.1%    |
| AMD E2                  | 4         | 0.1%    |
| Intel Pentium Dual      | 3         | 0.07%   |
| Intel Pentium D         | 3         | 0.07%   |
| Intel Genuine           | 3         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1343      | 33.33%  |
| 2       | 1000      | 24.81%  |
| 8       | 617       | 15.31%  |
| 6       | 599       | 14.86%  |
| 12      | 133       | 3.3%    |
| 16      | 98        | 2.43%   |
| 14      | 97        | 2.41%   |
| 10      | 71        | 1.76%   |
| 24      | 19        | 0.47%   |
| 3       | 19        | 0.47%   |
| 1       | 16        | 0.4%    |
| Unknown | 7         | 0.17%   |
| 40      | 2         | 0.05%   |
| 36      | 2         | 0.05%   |
| 32      | 2         | 0.05%   |
| 18      | 2         | 0.05%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 20      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3996      | 99.28%  |
| 2       | 22        | 0.55%   |
| Unknown | 7         | 0.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3326      | 82.57%  |
| 1       | 695       | 17.25%  |
| Unknown | 7         | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4021      | 99.9%   |
| 64-bit         | 4         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3309      | 81.04%  |
| 0x806c1    | 50        | 1.22%   |
| 0x0a50000c | 48        | 1.18%   |
| 0x08701021 | 27        | 0.66%   |
| 0x806ec    | 26        | 0.64%   |
| 0x08608103 | 26        | 0.64%   |
| 0x08600106 | 25        | 0.61%   |
| 0x906a3    | 24        | 0.59%   |
| 0x806ea    | 24        | 0.59%   |
| 0x806d1    | 24        | 0.59%   |
| 0x306a9    | 22        | 0.54%   |
| 0x0a601203 | 22        | 0.54%   |
| 0x0a50000d | 22        | 0.54%   |
| 0x906ea    | 21        | 0.51%   |
| 0xa0652    | 20        | 0.49%   |
| 0x0a404102 | 19        | 0.47%   |
| 0x08108109 | 17        | 0.42%   |
| 0x0800820d | 17        | 0.42%   |
| 0x0a404101 | 16        | 0.39%   |
| 0x0a201016 | 15        | 0.37%   |
| 0x806e9    | 14        | 0.34%   |
| 0x506e3    | 14        | 0.34%   |
| 0x406e3    | 14        | 0.34%   |
| 0x206a7    | 14        | 0.34%   |
| 0x906a4    | 13        | 0.32%   |
| 0x306c3    | 13        | 0.32%   |
| 0x0a20120a | 13        | 0.32%   |
| 0x40651    | 12        | 0.29%   |
| 0x906e9    | 11        | 0.27%   |
| 0x08600104 | 11        | 0.27%   |
| 0x306d4    | 9         | 0.22%   |
| 0x706e5    | 8         | 0.2%    |
| 0x1067a    | 8         | 0.2%    |
| 0x706a8    | 7         | 0.17%   |
| 0x0a704103 | 7         | 0.17%   |
| 0x08600103 | 7         | 0.17%   |
| 0x08108102 | 7         | 0.17%   |
| 0x90672    | 6         | 0.15%   |
| 0x08701013 | 6         | 0.15%   |
| 0x906ec    | 5         | 0.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 626       | 15.51%  |
| Unknown          | 462       | 11.44%  |
| Zen 3            | 382       | 9.46%   |
| Haswell          | 356       | 8.82%   |
| Zen 2            | 238       | 5.9%    |
| Skylake          | 208       | 5.15%   |
| SandyBridge      | 208       | 5.15%   |
| IvyBridge        | 199       | 4.93%   |
| Zen+             | 167       | 4.14%   |
| TigerLake        | 166       | 4.11%   |
| CometLake        | 131       | 3.24%   |
| Alderlake Hybrid | 118       | 2.92%   |
| Broadwell        | 107       | 2.65%   |
| Penryn           | 97        | 2.4%    |
| Zen              | 84        | 2.08%   |
| IceLake          | 74        | 1.83%   |
| Westmere         | 62        | 1.54%   |
| Piledriver       | 61        | 1.51%   |
| Goldmont plus    | 44        | 1.09%   |
| Silvermont       | 36        | 0.89%   |
| K10              | 35        | 0.87%   |
| Nehalem          | 34        | 0.84%   |
| Excavator        | 32        | 0.79%   |
| Core             | 22        | 0.54%   |
| Steamroller      | 17        | 0.42%   |
| Puma             | 17        | 0.42%   |
| K10 Llano        | 11        | 0.27%   |
| Goldmont         | 10        | 0.25%   |
| Bobcat           | 9         | 0.22%   |
| K8 Hammer        | 5         | 0.12%   |
| Jaguar           | 5         | 0.12%   |
| Tremont          | 4         | 0.1%    |
| NetBurst         | 3         | 0.07%   |
| Bulldozer        | 3         | 0.07%   |
| K8 & K10 hybrid  | 2         | 0.05%   |
| Gracemont        | 2         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 2089      | 41.96%  |
| Nvidia                     | 1614      | 32.42%  |
| AMD                        | 1265      | 25.41%  |
| Matrox Electronics Systems | 5         | 0.1%    |
| ASPEED Technology          | 5         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 155       | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 150       | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 147       | 2.88%   |
| Intel UHD Graphics 620                                                      | 119       | 2.33%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 110       | 2.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 101       | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 100       | 1.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 97        | 1.9%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 94        | 1.84%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 89        | 1.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 84        | 1.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 83        | 1.62%   |
| AMD Lucienne                                                                | 77        | 1.51%   |
| Intel HD Graphics 620                                                       | 76        | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 71        | 1.39%   |
| AMD Rembrandt [Radeon 680M]                                                 | 70        | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 69        | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 65        | 1.27%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 63        | 1.23%   |
| Intel HD Graphics 5500                                                      | 63        | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 62        | 1.21%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 61        | 1.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 60        | 1.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 59        | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 52        | 1.02%   |
| AMD Raphael                                                                 | 52        | 1.02%   |
| Intel HD Graphics 530                                                       | 49        | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 46        | 0.9%    |
| Intel HD Graphics 630                                                       | 46        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                         | 41        | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 40        | 0.78%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 38        | 0.74%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 38        | 0.74%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 37        | 0.72%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 36        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 35        | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 34        | 0.67%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 33        | 0.65%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 29        | 0.57%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 28        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1356      | 33.37%  |
| 1 x AMD              | 903       | 22.22%  |
| 1 x Nvidia           | 810       | 19.94%  |
| Intel + Nvidia       | 593       | 14.6%   |
| AMD + Nvidia         | 187       | 4.6%    |
| 2 x AMD              | 91        | 2.24%   |
| Intel + AMD          | 82        | 2.02%   |
| 2 x Nvidia           | 14        | 0.34%   |
| Other                | 11        | 0.27%   |
| 1 x Matrox           | 4         | 0.1%    |
| Intel + 2 x Nvidia   | 3         | 0.07%   |
| AMD + ASPEED         | 3         | 0.07%   |
| 2 x Intel            | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.02%   |
| Nvidia + Matrox      | 1         | 0.02%   |
| Nvidia + ASPEED      | 1         | 0.02%   |
| 1 x ASPEED           | 1         | 0.02%   |
| AMD + 2 x Nvidia     | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2665      | 65.46%  |
| Proprietary | 1306      | 32.08%  |
| Unknown     | 100       | 2.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3309      | 81.02%  |
| 7.01-8.0   | 147       | 3.6%    |
| 0.01-0.5   | 146       | 3.57%   |
| 1.01-2.0   | 133       | 3.26%   |
| 3.01-4.0   | 108       | 2.64%   |
| 8.01-16.0  | 92        | 2.25%   |
| 5.01-6.0   | 86        | 2.11%   |
| 0.51-1.0   | 32        | 0.78%   |
| 2.01-3.0   | 17        | 0.42%   |
| 16.01-24.0 | 13        | 0.32%   |
| 32.01-64.0 | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 530       | 11.33%  |
| Samsung Electronics     | 519       | 11.09%  |
| BOE                     | 458       | 9.79%   |
| Chimei Innolux          | 415       | 8.87%   |
| LG Display              | 354       | 7.57%   |
| Goldstar                | 307       | 6.56%   |
| Dell                    | 284       | 6.07%   |
| Apple                   | 167       | 3.57%   |
| Acer                    | 160       | 3.42%   |
| Hewlett-Packard         | 128       | 2.74%   |
| AOC                     | 126       | 2.69%   |
| Sharp                   | 117       | 2.5%    |
| ASUSTek Computer        | 90        | 1.92%   |
| Ancor Communications    | 87        | 1.86%   |
| BenQ                    | 86        | 1.84%   |
| Lenovo                  | 77        | 1.65%   |
| Philips                 | 69        | 1.47%   |
| PANDA                   | 64        | 1.37%   |
| InfoVision              | 45        | 0.96%   |
| Iiyama                  | 42        | 0.9%    |
| MSI                     | 39        | 0.83%   |
| ViewSonic               | 32        | 0.68%   |
| Chi Mei Optoelectronics | 31        | 0.66%   |
| CSO                     | 30        | 0.64%   |
| Gigabyte Technology     | 21        | 0.45%   |
| Sony                    | 20        | 0.43%   |
| Sceptre Tech            | 20        | 0.43%   |
| NEC Computers           | 18        | 0.38%   |
| Panasonic               | 17        | 0.36%   |
| Vizio                   | 14        | 0.3%    |
| Toshiba                 | 10        | 0.21%   |
| TMX                     | 10        | 0.21%   |
| HKC                     | 10        | 0.21%   |
| Eizo                    | 10        | 0.21%   |
| Vestel Elektronik       | 9         | 0.19%   |
| Unknown                 | 8         | 0.17%   |
| Mi                      | 8         | 0.17%   |
| Hitachi                 | 8         | 0.17%   |
| Insignia                | 7         | 0.15%   |
| Valve                   | 6         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 30        | 0.62%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 27        | 0.56%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 22        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 22        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 22        | 0.46%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 20        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 19        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 18        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 15        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 14        | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 13        | 0.27%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 13        | 0.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 13        | 0.27%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 13        | 0.27%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 13        | 0.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 12        | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 12        | 0.25%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 11        | 0.23%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 11        | 0.23%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 11        | 0.23%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 10        | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 10        | 0.21%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 10        | 0.21%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 9         | 0.19%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 9         | 0.19%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 9         | 0.19%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 9         | 0.19%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 9         | 0.19%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 9         | 0.19%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 9         | 0.19%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch        | 9         | 0.19%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 9         | 0.19%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 9         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 8         | 0.17%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 8         | 0.17%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 8         | 0.17%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 8         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2090      | 47.15%  |
| 1366x768 (WXGA)    | 565       | 12.75%  |
| 3840x2160 (4K)     | 412       | 9.29%   |
| 2560x1440 (QHD)    | 318       | 7.17%   |
| 1920x1200 (WUXGA)  | 136       | 3.07%   |
| 1600x900 (HD+)     | 116       | 2.62%   |
| 3440x1440          | 106       | 2.39%   |
| 2560x1600          | 82        | 1.85%   |
| 2560x1080          | 75        | 1.69%   |
| 1440x900 (WXGA+)   | 74        | 1.67%   |
| 1680x1050 (WSXGA+) | 61        | 1.38%   |
| 2880x1800          | 56        | 1.26%   |
| 1280x800 (WXGA)    | 48        | 1.08%   |
| 1280x1024 (SXGA)   | 48        | 1.08%   |
| 3840x1080          | 29        | 0.65%   |
| 3840x2400          | 22        | 0.5%    |
| 1360x768           | 22        | 0.5%    |
| 1920x540           | 17        | 0.38%   |
| 2160x1440          | 14        | 0.32%   |
| 3072x1920          | 13        | 0.29%   |
| 1920x1280          | 11        | 0.25%   |
| 2256x1504          | 10        | 0.23%   |
| Unknown            | 10        | 0.23%   |
| 3840x1600          | 9         | 0.2%    |
| 2736x1824          | 9         | 0.2%    |
| 3200x1800 (QHD+)   | 8         | 0.18%   |
| 1280x720 (HD)      | 6         | 0.14%   |
| 1024x768 (XGA)     | 6         | 0.14%   |
| 3456x2160          | 5         | 0.11%   |
| 3200x2000          | 5         | 0.11%   |
| 3000x2000          | 5         | 0.11%   |
| 1600x1200          | 5         | 0.11%   |
| 2880x1620          | 4         | 0.09%   |
| 2240x1400          | 4         | 0.09%   |
| 3840x1200          | 3         | 0.07%   |
| 3840x1100          | 3         | 0.07%   |
| 2520x1680          | 3         | 0.07%   |
| 2304x1440          | 3         | 0.07%   |
| 800x1280           | 2         | 0.05%   |
| 4480x1440          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1139      | 24.33%  |
| 13      | 495       | 10.57%  |
| 27      | 459       | 9.81%   |
| 14      | 373       | 7.97%   |
| 24      | 354       | 7.56%   |
| 23      | 268       | 5.73%   |
| 17      | 205       | 4.38%   |
| 21      | 201       | 4.29%   |
| 31      | 194       | 4.14%   |
| 34      | 157       | 3.35%   |
| 16      | 106       | 2.26%   |
| 12      | 75        | 1.6%    |
| 19      | 69        | 1.47%   |
| Unknown | 69        | 1.47%   |
| 84      | 46        | 0.98%   |
| 32      | 46        | 0.98%   |
| 22      | 46        | 0.98%   |
| 18      | 46        | 0.98%   |
| 20      | 40        | 0.85%   |
| 48      | 30        | 0.64%   |
| 11      | 29        | 0.62%   |
| 72      | 28        | 0.6%    |
| 28      | 22        | 0.47%   |
| 40      | 21        | 0.45%   |
| 54      | 20        | 0.43%   |
| 25      | 14        | 0.3%    |
| 37      | 13        | 0.28%   |
| 26      | 12        | 0.26%   |
| 35      | 11        | 0.23%   |
| 52      | 9         | 0.19%   |
| 29      | 9         | 0.19%   |
| 65      | 7         | 0.15%   |
| 49      | 7         | 0.15%   |
| 33      | 7         | 0.15%   |
| 46      | 6         | 0.13%   |
| 42      | 5         | 0.11%   |
| 36      | 5         | 0.11%   |
| 74      | 4         | 0.09%   |
| 44      | 4         | 0.09%   |
| 57      | 3         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1836      | 40.17%  |
| 501-600     | 962       | 21.05%  |
| 201-300     | 372       | 8.14%   |
| 401-500     | 366       | 8.01%   |
| 601-700     | 281       | 6.15%   |
| 351-400     | 236       | 5.16%   |
| 701-800     | 207       | 4.53%   |
| 1001-1500   | 93        | 2.03%   |
| 1501-2000   | 83        | 1.82%   |
| Unknown     | 69        | 1.51%   |
| 801-900     | 54        | 1.18%   |
| 901-1000    | 8         | 0.18%   |
| 101-200     | 2         | 0.04%   |
| 1-100       | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3212      | 77.6%   |
| 16/10   | 536       | 12.95%  |
| 21/9    | 191       | 4.61%   |
| 3/2     | 54        | 1.3%    |
| 5/4     | 49        | 1.18%   |
| 32/9    | 35        | 0.85%   |
| Unknown | 27        | 0.65%   |
| 4/3     | 21        | 0.51%   |
| 3.40    | 3         | 0.07%   |
| 3.20    | 3         | 0.07%   |
| 6/5     | 2         | 0.05%   |
| 3.73    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 0.89    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.63    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1143      | 24.7%   |
| 201-250        | 681       | 14.72%  |
| 81-90          | 665       | 14.37%  |
| 301-350        | 473       | 10.22%  |
| 351-500        | 423       | 9.14%   |
| 71-80          | 202       | 4.37%   |
| 121-130        | 169       | 3.65%   |
| 151-200        | 159       | 3.44%   |
| More than 1000 | 132       | 2.85%   |
| 251-300        | 126       | 2.72%   |
| 111-120        | 96        | 2.07%   |
| 501-1000       | 93        | 2.01%   |
| 141-150        | 70        | 1.51%   |
| Unknown        | 69        | 1.49%   |
| 61-70          | 60        | 1.3%    |
| 51-60          | 33        | 0.71%   |
| 91-100         | 15        | 0.32%   |
| 131-140        | 14        | 0.3%    |
| 1-40           | 4         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1427      | 31.92%  |
| 51-100        | 1315      | 29.41%  |
| 101-120       | 999       | 22.34%  |
| 161-240       | 399       | 8.92%   |
| More than 240 | 160       | 3.58%   |
| 1-50          | 102       | 2.28%   |
| Unknown       | 69        | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3098      | 75.56%  |
| 2     | 757       | 18.46%  |
| 0     | 126       | 3.07%   |
| 3     | 107       | 2.61%   |
| 4     | 10        | 0.24%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2171      | 35.4%   |
| Intel                             | 2121      | 34.58%  |
| Qualcomm Atheros                  | 541       | 8.82%   |
| Broadcom                          | 327       | 5.33%   |
| MediaTek                          | 217       | 3.54%   |
| Broadcom Limited                  | 99        | 1.61%   |
| TP-Link                           | 63        | 1.03%   |
| ASIX Electronics                  | 53        | 0.86%   |
| Marvell Technology Group          | 43        | 0.7%    |
| Ralink Technology                 | 38        | 0.62%   |
| Nvidia                            | 38        | 0.62%   |
| Samsung Electronics               | 37        | 0.6%    |
| Ralink                            | 32        | 0.52%   |
| NetGear                           | 26        | 0.42%   |
| Aquantia                          | 23        | 0.38%   |
| Xiaomi                            | 21        | 0.34%   |
| Microsoft                         | 21        | 0.34%   |
| DisplayLink                       | 20        | 0.33%   |
| Qualcomm                          | 18        | 0.29%   |
| Dell                              | 17        | 0.28%   |
| Sierra Wireless                   | 15        | 0.24%   |
| Google                            | 14        | 0.23%   |
| Lenovo                            | 13        | 0.21%   |
| InterBiometrics                   | 13        | 0.21%   |
| ASUSTek Computer                  | 13        | 0.21%   |
| Qualcomm Atheros Communications   | 10        | 0.16%   |
| Linksys                           | 10        | 0.16%   |
| OPPO Electronics                  | 9         | 0.15%   |
| JMicron Technology                | 9         | 0.15%   |
| Hewlett-Packard                   | 9         | 0.15%   |
| D-Link                            | 9         | 0.15%   |
| Huawei Technologies               | 7         | 0.11%   |
| D-Link System                     | 7         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.1%    |
| Ericsson Business Mobile Networks | 5         | 0.08%   |
| Motorola PCS                      | 4         | 0.07%   |
| Mellanox Technologies             | 4         | 0.07%   |
| Edimax Technology                 | 4         | 0.07%   |
| Fibocom                           | 3         | 0.05%   |
| Arduino SA                        | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1381      | 19.02%  |
| Intel Wi-Fi 6 AX200                                                    | 318       | 4.38%   |
| Realtek RTL8125 2.5GbE Controller                                      | 216       | 2.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 157       | 2.16%   |
| Intel I211 Gigabit Network Connection                                  | 153       | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 144       | 1.98%   |
| Intel Ethernet Controller I225-V                                       | 142       | 1.96%   |
| Intel Wireless 8265 / 8275                                             | 139       | 1.91%   |
| Intel Wi-Fi 6 AX201                                                    | 132       | 1.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 122       | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 95        | 1.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 95        | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 94        | 1.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 89        | 1.23%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 85        | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 83        | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 78        | 1.07%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 76        | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 73        | 1.01%   |
| Intel Wireless 7265                                                    | 73        | 1.01%   |
| Intel Wireless 8260                                                    | 70        | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 70        | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 68        | 0.94%   |
| Intel Wireless 7260                                                    | 67        | 0.92%   |
| Intel Ethernet Connection I217-LM                                      | 64        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 64        | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 61        | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 60        | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 58        | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 54        | 0.74%   |
| Intel Ethernet Connection (2) I219-V                                   | 52        | 0.72%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 52        | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 47        | 0.65%   |
| Realtek 802.11ac NIC                                                   | 46        | 0.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 46        | 0.63%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 45        | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 43        | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                          | 43        | 0.59%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 42        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                  | 40        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1724      | 48.26%  |
| Realtek Semiconductor                 | 554       | 15.51%  |
| Qualcomm Atheros                      | 429       | 12.01%  |
| Broadcom                              | 259       | 7.25%   |
| MediaTek                              | 216       | 6.05%   |
| Broadcom Limited                      | 85        | 2.38%   |
| TP-Link                               | 55        | 1.54%   |
| Ralink Technology                     | 38        | 1.06%   |
| Ralink                                | 32        | 0.9%    |
| NetGear                               | 26        | 0.73%   |
| Microsoft                             | 21        | 0.59%   |
| Qualcomm                              | 16        | 0.45%   |
| Sierra Wireless                       | 15        | 0.42%   |
| Marvell Technology Group              | 15        | 0.42%   |
| Dell                                  | 15        | 0.42%   |
| ASUSTek Computer                      | 11        | 0.31%   |
| Qualcomm Atheros Communications       | 10        | 0.28%   |
| Linksys                               | 10        | 0.28%   |
| D-Link                                | 8         | 0.22%   |
| D-Link System                         | 6         | 0.17%   |
| Hewlett-Packard                       | 4         | 0.11%   |
| Edimax Technology                     | 4         | 0.11%   |
| Fibocom                               | 3         | 0.08%   |
| Belkin Components                     | 2         | 0.06%   |
| AVM                                   | 2         | 0.06%   |
| Accton Technology                     | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| ZyDAS                                 | 1         | 0.03%   |
| Wacom                                 | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| IMC Networks                          | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |
| Ericsson Business Mobile Networks     | 1         | 0.03%   |
| Arduino SA                            | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 318       | 8.85%   |
| Intel Wireless 8265 / 8275                                           | 139       | 3.87%   |
| Intel Wi-Fi 6 AX201                                                  | 132       | 3.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 122       | 3.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 95        | 2.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 94        | 2.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 89        | 2.48%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 85        | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 83        | 2.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 78        | 2.17%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 76        | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 73        | 2.03%   |
| Intel Wireless 7265                                                  | 73        | 2.03%   |
| Intel Wireless 8260                                                  | 70        | 1.95%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 70        | 1.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 68        | 1.89%   |
| Intel Wireless 7260                                                  | 67        | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 64        | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 61        | 1.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 60        | 1.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 58        | 1.61%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 54        | 1.5%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 52        | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 47        | 1.31%   |
| Realtek 802.11ac NIC                                                 | 46        | 1.28%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 46        | 1.28%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 45        | 1.25%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 43        | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 42        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 39        | 1.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 32        | 0.89%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 31        | 0.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 31        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                        | 30        | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 29        | 0.81%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 28        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 28        | 0.78%   |
| Intel Wireless 3165                                                  | 25        | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 24        | 0.67%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 23        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 1920      | 54.31%  |
| Intel                         | 995       | 28.15%  |
| Qualcomm Atheros              | 157       | 4.44%   |
| Broadcom                      | 140       | 3.96%   |
| ASIX Electronics              | 53        | 1.5%    |
| Nvidia                        | 38        | 1.07%   |
| Samsung Electronics           | 37        | 1.05%   |
| Marvell Technology Group      | 28        | 0.79%   |
| Aquantia                      | 23        | 0.65%   |
| Xiaomi                        | 21        | 0.59%   |
| DisplayLink                   | 20        | 0.57%   |
| Google                        | 14        | 0.4%    |
| Broadcom Limited              | 14        | 0.4%    |
| Lenovo                        | 13        | 0.37%   |
| OPPO Electronics              | 9         | 0.25%   |
| JMicron Technology            | 9         | 0.25%   |
| TP-Link                       | 8         | 0.23%   |
| OnePlus Technology (Shenzhen) | 5         | 0.14%   |
| Huawei Technologies           | 5         | 0.14%   |
| Hewlett-Packard               | 4         | 0.11%   |
| Motorola PCS                  | 3         | 0.08%   |
| Mellanox Technologies         | 3         | 0.08%   |
| Qualcomm                      | 2         | 0.06%   |
| ICS Advent                    | 2         | 0.06%   |
| ASUSTek Computer              | 2         | 0.06%   |
| Apple                         | 2         | 0.06%   |
| American Megatrends           | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.03%   |
| VIA Technologies              | 1         | 0.03%   |
| T & A Mobile Phones           | 1         | 0.03%   |
| Insyde Software               | 1         | 0.03%   |
| D-Link System                 | 1         | 0.03%   |
| D-Link                        | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1381      | 38.16%  |
| Realtek RTL8125 2.5GbE Controller                                      | 216       | 5.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 157       | 4.34%   |
| Intel I211 Gigabit Network Connection                                  | 153       | 4.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 144       | 3.98%   |
| Intel Ethernet Controller I225-V                                       | 142       | 3.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 95        | 2.63%   |
| Intel Ethernet Connection I217-LM                                      | 64        | 1.77%   |
| Intel Ethernet Connection (2) I219-V                                   | 52        | 1.44%   |
| ASIX AX88179 Gigabit Ethernet                                          | 43        | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                                  | 40        | 1.11%   |
| Intel Ethernet Connection I219-LM                                      | 35        | 0.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 34        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                                   | 31        | 0.86%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 28        | 0.77%   |
| Realtek Killer E2600 GbE Controller                                    | 27        | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 27        | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 25        | 0.69%   |
| Nvidia MCP79 Ethernet                                                  | 25        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                  | 25        | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 24        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 23        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 22        | 0.61%   |
| Intel I210 Gigabit Network Connection                                  | 20        | 0.55%   |
| Intel Ethernet Connection I217-V                                       | 20        | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                                  | 19        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                                   | 19        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                                   | 18        | 0.5%    |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 16        | 0.44%   |
| Intel Ethernet Connection (6) I219-V                                   | 16        | 0.44%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 15        | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 15        | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 14        | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 14        | 0.39%   |
| Intel Ethernet Connection (13) I219-V                                  | 14        | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                                  | 13        | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                                  | 13        | 0.36%   |
| Intel 82579V Gigabit Network Connection                                | 13        | 0.36%   |
| Intel Ethernet Connection (16) I219-V                                  | 12        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3387      | 50.38%  |
| Ethernet | 3289      | 48.92%  |
| Modem    | 34        | 0.51%   |
| Unknown  | 13        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2628      | 61.47%  |
| Ethernet | 1647      | 38.53%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2260      | 56.08%  |
| 1     | 1600      | 39.7%   |
| 3     | 112       | 2.78%   |
| 0     | 43        | 1.07%   |
| 4     | 12        | 0.3%    |
| 5     | 3         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2810      | 68.65%  |
| Yes  | 1283      | 31.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1542      | 51.83%  |
| Realtek Semiconductor           | 290       | 9.75%   |
| Apple                           | 201       | 6.76%   |
| Qualcomm Atheros Communications | 194       | 6.52%   |
| IMC Networks                    | 143       | 4.81%   |
| Cambridge Silicon Radio         | 120       | 4.03%   |
| Foxconn / Hon Hai               | 116       | 3.9%    |
| Lite-On Technology              | 76        | 2.55%   |
| Broadcom                        | 63        | 2.12%   |
| MediaTek                        | 55        | 1.85%   |
| ASUSTek Computer                | 38        | 1.28%   |
| Dell                            | 20        | 0.67%   |
| TP-Link                         | 16        | 0.54%   |
| Realtek                         | 16        | 0.54%   |
| Marvell Semiconductor           | 16        | 0.54%   |
| Toshiba                         | 12        | 0.4%    |
| Hewlett-Packard                 | 9         | 0.3%    |
| Ralink                          | 8         | 0.27%   |
| Dynex                           | 6         | 0.2%    |
| Actions                         | 5         | 0.17%   |
| Foxconn International           | 4         | 0.13%   |
| Opticis                         | 3         | 0.1%    |
| Micro Star International        | 3         | 0.1%    |
| Integrated System Solution      | 3         | 0.1%    |
| USI                             | 2         | 0.07%   |
| Taiyo Yuden                     | 2         | 0.07%   |
| Smart Modular Technologies      | 2         | 0.07%   |
| Ralink Technology               | 2         | 0.07%   |
| Fujitsu                         | 2         | 0.07%   |
| Edimax Technology               | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| HTC (High Tech Computer)        | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 370       | 12.43%  |
| Intel AX201 Bluetooth                               | 339       | 11.39%  |
| Intel AX200 Bluetooth                               | 299       | 10.04%  |
| Realtek Bluetooth Radio                             | 219       | 7.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 167       | 5.61%   |
| Intel Bluetooth Device                              | 158       | 5.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 120       | 4.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 109       | 3.66%   |
| Apple Bluetooth Host Controller                     | 104       | 3.49%   |
| Intel AX210 Bluetooth                               | 78        | 2.62%   |
| Intel Wireless-AC 3168 Bluetooth                    | 64        | 2.15%   |
| IMC Networks Wireless_Device                        | 63        | 2.12%   |
| Apple Bluetooth USB Host Controller                 | 60        | 2.02%   |
| Foxconn / Hon Hai Wireless_Device                   | 56        | 1.88%   |
| MediaTek Wireless_Device                            | 55        | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 54        | 1.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 41        | 1.38%   |
| IMC Networks Bluetooth Radio                        | 37        | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                  | 32        | 1.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 27        | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 25        | 0.84%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 24        | 0.81%   |
| IMC Networks Bluetooth Device                       | 22        | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 19        | 0.64%   |
| Lite-On Bluetooth Device                            | 17        | 0.57%   |
| TP-Link UB500 Adapter                               | 16        | 0.54%   |
| Realtek Bluetooth Radio                             | 16        | 0.54%   |
| Lite-On Wireless_Device                             | 16        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 15        | 0.5%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 0.5%    |
| ASUS ASUS USB-BT500                                 | 14        | 0.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 13        | 0.44%   |
| Apple Bluetooth HCI                                 | 13        | 0.44%   |
| Marvell Bluetooth and Wireless LAN Composite        | 12        | 0.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 0.4%    |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.37%   |
| Lite-On Bluetooth Radio                             | 10        | 0.34%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.34%   |
| ASUS Bluetooth Radio                                | 10        | 0.34%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 9         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2641      | 41.76%  |
| AMD                                  | 1483      | 23.45%  |
| Nvidia                               | 1298      | 20.52%  |
| C-Media Electronics                  | 109       | 1.72%   |
| Logitech                             | 72        | 1.14%   |
| Kingston Technology                  | 48        | 0.76%   |
| ASUSTek Computer                     | 40        | 0.63%   |
| Razer USA                            | 39        | 0.62%   |
| JMTek                                | 33        | 0.52%   |
| Generalplus Technology               | 33        | 0.52%   |
| Focusrite-Novation                   | 33        | 0.52%   |
| Creative Labs                        | 30        | 0.47%   |
| Micro Star International             | 29        | 0.46%   |
| SteelSeries ApS                      | 28        | 0.44%   |
| GN Netcom                            | 24        | 0.38%   |
| Lenovo                               | 21        | 0.33%   |
| Corsair                              | 21        | 0.33%   |
| Texas Instruments                    | 19        | 0.3%    |
| Realtek Semiconductor                | 19        | 0.3%    |
| Creative Technology                  | 16        | 0.25%   |
| Sony                                 | 13        | 0.21%   |
| Plantronics                          | 13        | 0.21%   |
| Blue Microphones                     | 13        | 0.21%   |
| Apple                                | 13        | 0.21%   |
| Hewlett-Packard                      | 10        | 0.16%   |
| DSEA A/S                             | 10        | 0.16%   |
| KTMicro                              | 9         | 0.14%   |
| Valve Software                       | 7         | 0.11%   |
| Dell                                 | 7         | 0.11%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.09%   |
| Tenx Technology                      | 6         | 0.09%   |
| Giga-Byte Technology                 | 6         | 0.09%   |
| FiiO Electronics Technology          | 6         | 0.09%   |
| Astro Gaming                         | 6         | 0.09%   |
| Yamaha                               | 5         | 0.08%   |
| BEHRINGER International              | 5         | 0.08%   |
| Trust                                | 4         | 0.06%   |
| TerraTec Electronic                  | 4         | 0.06%   |
| Samson Technologies                  | 4         | 0.06%   |
| Medeli Electronics                   | 4         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 653       | 8.53%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 338       | 4.42%   |
| AMD Starship/Matisse HD Audio Controller                                   | 302       | 3.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 301       | 3.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 205       | 2.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 195       | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 187       | 2.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 166       | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 157       | 2.05%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 149       | 1.95%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 139       | 1.82%   |
| Nvidia Audio device                                                        | 135       | 1.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 132       | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 129       | 1.69%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 126       | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 125       | 1.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 106       | 1.38%   |
| Nvidia GA106 High Definition Audio Controller                              | 103       | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                      | 102       | 1.33%   |
| Intel 8 Series HD Audio Controller                                         | 101       | 1.32%   |
| Intel Broadwell-U Audio Controller                                         | 98        | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 96        | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 95        | 1.24%   |
| Intel Comet Lake PCH cAVS                                                  | 94        | 1.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 90        | 1.18%   |
| Nvidia TU116 High Definition Audio Controller                              | 88        | 1.15%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 88        | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 87        | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                               | 83        | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 76        | 0.99%   |
| AMD FCH Azalia Controller                                                  | 75        | 0.98%   |
| Nvidia GP104 High Definition Audio Controller                              | 74        | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 73        | 0.95%   |
| Intel 200 Series PCH HD Audio                                              | 73        | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 71        | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 71        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 70        | 0.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 67        | 0.88%   |
| Nvidia GA102 High Definition Audio Controller                              | 59        | 0.77%   |
| Intel Alder Lake-S HD Audio Controller                                     | 52        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 323       | 24.18%  |
| SK hynix                                | 259       | 19.39%  |
| Micron Technology                       | 170       | 12.72%  |
| Kingston                                | 111       | 8.31%   |
| Corsair                                 | 101       | 7.56%   |
| Crucial                                 | 80        | 5.99%   |
| G.Skill                                 | 63        | 4.72%   |
| Unknown                                 | 33        | 2.47%   |
| Team                                    | 29        | 2.17%   |
| A-DATA Technology                       | 24        | 1.8%    |
| Unknown                                 | 23        | 1.72%   |
| Smart                                   | 14        | 1.05%   |
| Ramaxel Technology                      | 13        | 0.97%   |
| Unknown (ABCD)                          | 10        | 0.75%   |
| Neo Forza                               | 10        | 0.75%   |
| Goldkey                                 | 10        | 0.75%   |
| Elpida                                  | 10        | 0.75%   |
| Nanya Technology                        | 5         | 0.37%   |
| PNY                                     | 4         | 0.3%    |
| Patriot                                 | 4         | 0.3%    |
| Transcend                               | 3         | 0.22%   |
| Teikon                                  | 3         | 0.22%   |
| GSkill                                  | 3         | 0.22%   |
| Avant                                   | 3         | 0.22%   |
| Wodposit                                | 2         | 0.15%   |
| Timetec                                 | 2         | 0.15%   |
| Smart Brazil                            | 2         | 0.15%   |
| Gold Key                                | 2         | 0.15%   |
| ChangXin Memory                         | 2         | 0.15%   |
| Apacer                                  | 2         | 0.15%   |
| Wilk                                    | 1         | 0.07%   |
| Unknown (8A02)                          | 1         | 0.07%   |
| Unknown (0x0CAB)                        | 1         | 0.07%   |
| Unknown (09B6)                          | 1         | 0.07%   |
| Unknown (09A4)                          | 1         | 0.07%   |
| Silicon Power Computer & Communications | 1         | 0.07%   |
| Patriot Memory (PDP Systems)            | 1         | 0.07%   |
| Patriot Memory                          | 1         | 0.07%   |
| Kreton                                  | 1         | 0.07%   |
| Kllisre                                 | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 25        | 1.78%   |
| Unknown                                                             | 23        | 1.64%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 20        | 1.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 15        | 1.07%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 15        | 1.07%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 14        | 1%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 12        | 0.86%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 12        | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 12        | 0.86%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 12        | 0.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 11        | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 11        | 0.78%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 11        | 0.78%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 10        | 0.71%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 9         | 0.64%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s             | 9         | 0.64%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s               | 9         | 0.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 8         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 8         | 0.57%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s                 | 7         | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 7         | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 7         | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 7         | 0.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 7         | 0.5%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s              | 7         | 0.5%    |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                | 6         | 0.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 6         | 0.43%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s              | 6         | 0.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 6         | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 6         | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 6         | 0.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 6         | 0.43%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s    | 6         | 0.43%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 6         | 0.43%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 6         | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 6         | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 5         | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 5         | 0.36%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 5         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 743       | 63.56%  |
| DDR3    | 167       | 14.29%  |
| DDR5    | 97        | 8.3%    |
| LPDDR4  | 66        | 5.65%   |
| LPDDR5  | 47        | 4.02%   |
| LPDDR3  | 31        | 2.65%   |
| DDR2    | 10        | 0.86%   |
| SDRAM   | 5         | 0.43%   |
| Unknown | 3         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 726       | 61.27%  |
| DIMM         | 293       | 24.73%  |
| Row Of Chips | 158       | 13.33%  |
| Chip         | 5         | 0.42%   |
| Unknown      | 3         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 548       | 43.8%   |
| 16384 | 310       | 24.78%  |
| 4096  | 232       | 18.55%  |
| 32768 | 105       | 8.39%   |
| 2048  | 50        | 4%      |
| 1024  | 6         | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 341       | 27.32%  |
| 2667  | 203       | 16.27%  |
| 1600  | 126       | 10.1%   |
| 2400  | 72        | 5.77%   |
| 4800  | 62        | 4.97%   |
| 3600  | 56        | 4.49%   |
| 2133  | 52        | 4.17%   |
| 6400  | 49        | 3.93%   |
| 4267  | 38        | 3.04%   |
| 3800  | 20        | 1.6%    |
| 3733  | 20        | 1.6%    |
| 1333  | 18        | 1.44%   |
| 5600  | 17        | 1.36%   |
| 1867  | 17        | 1.36%   |
| 3266  | 15        | 1.2%    |
| 1334  | 10        | 0.8%    |
| 8400  | 9         | 0.72%   |
| 3533  | 9         | 0.72%   |
| 1067  | 9         | 0.72%   |
| 800   | 8         | 0.64%   |
| 6000  | 7         | 0.56%   |
| 4266  | 7         | 0.56%   |
| 3534  | 7         | 0.56%   |
| 3000  | 7         | 0.56%   |
| 2933  | 7         | 0.56%   |
| 5200  | 6         | 0.48%   |
| 2666  | 6         | 0.48%   |
| 3400  | 4         | 0.32%   |
| 1866  | 4         | 0.32%   |
| 4000  | 3         | 0.24%   |
| 3866  | 3         | 0.24%   |
| 2800  | 3         | 0.24%   |
| 2048  | 3         | 0.24%   |
| 667   | 3         | 0.24%   |
| 4400  | 2         | 0.16%   |
| 4199  | 2         | 0.16%   |
| 3666  | 2         | 0.16%   |
| 3466  | 2         | 0.16%   |
| 3333  | 2         | 0.16%   |
| 3100  | 2         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 35.82%  |
| Canon               | 10        | 14.93%  |
| Brother Industries  | 10        | 14.93%  |
| Samsung Electronics | 7         | 10.45%  |
| Seiko Epson         | 5         | 7.46%   |
| Dymo-CoStar         | 4         | 5.97%   |
| STMicroelectronics  | 2         | 2.99%   |
| Xerox               | 1         | 1.49%   |
| QinHeng Electronics | 1         | 1.49%   |
| Prolific Technology | 1         | 1.49%   |
| ICS Advent          | 1         | 1.49%   |
| Dell                | 1         | 1.49%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450                               | 3         | 4.41%   |
| Brother HL-2130 series                                    | 3         | 4.41%   |
| Seiko Epson WF-4830 Series                                | 2         | 2.94%   |
| HP ENVY Pro 6400 series                                   | 2         | 2.94%   |
| Canon PIXMA MX920 Series                                  | 2         | 2.94%   |
| Xerox B215                                                | 1         | 1.47%   |
| STMicroelectronics USB Printer P                          | 1         | 1.47%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.47%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 1.47%   |
| Seiko Epson L382 Series                                   | 1         | 1.47%   |
| Seiko Epson ET-2800 Series                                | 1         | 1.47%   |
| Samsung SCX-4500 Laser Printer                            | 1         | 1.47%   |
| Samsung SCX-3400 Series                                   | 1         | 1.47%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.47%   |
| Samsung ML-191x/ML-252x Laser Printer                     | 1         | 1.47%   |
| Samsung M2070 Series                                      | 1         | 1.47%   |
| Samsung M2020 Series                                      | 1         | 1.47%   |
| Samsung C460 Series                                       | 1         | 1.47%   |
| QinHeng CH340S                                            | 1         | 1.47%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.47%   |
| ICS Advent Parallel Adapter                               | 1         | 1.47%   |
| HP PSC-1315/PSC-1317                                      | 1         | 1.47%   |
| HP OfficeJet Pro 9010 series                              | 1         | 1.47%   |
| HP Officejet 4500 G510a-f                                 | 1         | 1.47%   |
| HP OfficeJet 3830 series                                  | 1         | 1.47%   |
| HP LaserJet Professional P1102w                           | 1         | 1.47%   |
| HP LaserJet Professional P 1102w                          | 1         | 1.47%   |
| HP LaserJet Pro M201dw                                    | 1         | 1.47%   |
| HP LaserJet Pro M118-M119                                 | 1         | 1.47%   |
| HP LaserJet P2035                                         | 1         | 1.47%   |
| HP LaserJet M203-M206                                     | 1         | 1.47%   |
| HP LaserJet 3050                                          | 1         | 1.47%   |
| HP LaserJet 1018                                          | 1         | 1.47%   |
| HP LaserJet 1010                                          | 1         | 1.47%   |
| HP Ink Tank Wireless 410 series                           | 1         | 1.47%   |
| HP Ink Tank 110 series                                    | 1         | 1.47%   |
| HP HP LaserJet M14-M17                                    | 1         | 1.47%   |
| HP ENVY 5000 series                                       | 1         | 1.47%   |
| HP DeskJet Plus 4100 series                               | 1         | 1.47%   |
| HP Deskjet F2280 series                                   | 1         | 1.47%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 4         | 36.36%  |
| Canon           | 4         | 36.36%  |
| Hewlett-Packard | 2         | 18.18%  |
| Mustek Systems  | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 9.09%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 9.09%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 9.09%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]       | 1         | 9.09%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 9.09%   |
| HP Scanjet G2710                                        | 1         | 9.09%   |
| HP ScanJet 82x0C                                        | 1         | 9.09%   |
| Canon CanoScan N650U/N656U                              | 1         | 9.09%   |
| Canon CanoScan LiDE 60                                  | 1         | 9.09%   |
| Canon CanoScan LiDE 200                                 | 1         | 9.09%   |
| Canon CanoScan 9000F Mark II                            | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 495       | 18.78%  |
| IMC Networks                           | 249       | 9.45%   |
| Microdia                               | 243       | 9.22%   |
| Realtek Semiconductor                  | 179       | 6.79%   |
| Bison Electronics                      | 171       | 6.49%   |
| Logitech                               | 165       | 6.26%   |
| Apple                                  | 150       | 5.69%   |
| Quanta                                 | 149       | 5.65%   |
| Sunplus Innovation Technology          | 130       | 4.93%   |
| Acer                                   | 76        | 2.88%   |
| Luxvisions Innotech Limited            | 72        | 2.73%   |
| Cheng Uei Precision Industry (Foxlink) | 65        | 2.47%   |
| Syntek                                 | 64        | 2.43%   |
| Lite-On Technology                     | 50        | 1.9%    |
| Suyin                                  | 33        | 1.25%   |
| Sonix Technology                       | 32        | 1.21%   |
| Microsoft                              | 31        | 1.18%   |
| Samsung Electronics                    | 25        | 0.95%   |
| Silicon Motion                         | 24        | 0.91%   |
| SunplusIT                              | 17        | 0.64%   |
| Alcor Micro                            | 13        | 0.49%   |
| Razer USA                              | 12        | 0.46%   |
| Generalplus Technology                 | 11        | 0.42%   |
| Z-Star Microelectronics                | 10        | 0.38%   |
| Jieli Technology                       | 7         | 0.27%   |
| Creative Technology                    | 7         | 0.27%   |
| ARC International                      | 7         | 0.27%   |
| Valve Software                         | 6         | 0.23%   |
| Ricoh                                  | 6         | 0.23%   |
| Primax Electronics                     | 6         | 0.23%   |
| USB Camera                             | 5         | 0.19%   |
| ShineTech                              | 5         | 0.19%   |
| MacroSilicon                           | 5         | 0.19%   |
| Lenovo                                 | 5         | 0.19%   |
| AVerMedia Technologies                 | 5         | 0.19%   |
| 8SSC21K12273V1SR33X2817                | 5         | 0.19%   |
| Trust                                  | 4         | 0.15%   |
| OmniVision Technologies                | 4         | 0.15%   |
| LG Electronics                         | 4         | 0.15%   |
| Hewlett-Packard                        | 4         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 123       | 4.62%   |
| Microdia Integrated_Webcam_HD                       | 111       | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 91        | 3.41%   |
| Realtek Integrated_Webcam_HD                        | 76        | 2.85%   |
| IMC Networks Integrated Camera                      | 66        | 2.48%   |
| Chicony HD WebCam                                   | 59        | 2.21%   |
| Syntek Integrated Camera                            | 48        | 1.8%    |
| Bison BisonCam,NB Pro                               | 48        | 1.8%    |
| Bison Integrated Camera                             | 45        | 1.69%   |
| Apple Built-in iSight                               | 42        | 1.58%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 38        | 1.43%   |
| Apple FaceTime HD Camera (Built-in)                 | 38        | 1.43%   |
| Logitech Webcam C270                                | 35        | 1.31%   |
| Chicony USB2.0 Camera                               | 35        | 1.31%   |
| Sunplus Integrated_Webcam_HD                        | 32        | 1.2%    |
| Quanta HD User Facing                               | 30        | 1.13%   |
| Logitech HD Pro Webcam C920                         | 30        | 1.13%   |
| Apple FaceTime HD Camera                            | 27        | 1.01%   |
| Samsung Galaxy series, misc. (MTP mode)             | 25        | 0.94%   |
| Quanta HP HD Camera                                 | 25        | 0.94%   |
| Chicony HP HD Camera                                | 25        | 0.94%   |
| Sonix USB2.0 HD UVC WebCam                          | 23        | 0.86%   |
| Microdia USB 2.0 Camera                             | 22        | 0.83%   |
| Realtek USB Camera                                  | 21        | 0.79%   |
| Lite-On Integrated Camera                           | 21        | 0.79%   |
| Chicony HD User Facing                              | 20        | 0.75%   |
| Bison HD Webcam                                     | 20        | 0.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 19        | 0.71%   |
| Quanta HP TrueVision HD Camera                      | 18        | 0.68%   |
| Acer SunplusIT Integrated Camera                    | 18        | 0.68%   |
| Microdia Webcam Vitade AF                           | 17        | 0.64%   |
| Microdia Integrated Webcam                          | 17        | 0.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 16        | 0.6%    |
| Logitech C922 Pro Stream Webcam                     | 16        | 0.6%    |
| Logitech C920 PRO HD Webcam                         | 15        | 0.56%   |
| Chicony USB2.0 VGA UVC WebCam                       | 15        | 0.56%   |
| Chicony Integrated Camera (1280x720@30)             | 15        | 0.56%   |
| Chicony HP Wide Vision HD Camera                    | 15        | 0.56%   |
| Chicony HP TrueVision HD Camera                     | 15        | 0.56%   |
| Quanta HP Wide Vision HD Camera                     | 14        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 176       | 36.9%   |
| Validity Sensors                   | 125       | 26.21%  |
| Shenzhen Goodix Technology         | 85        | 17.82%  |
| Elan Microelectronics              | 28        | 5.87%   |
| LighTuning Technology              | 19        | 3.98%   |
| Upek                               | 18        | 3.77%   |
| AuthenTec                          | 8         | 1.68%   |
| Realtek USB2.0 Finger Print Bridge | 7         | 1.47%   |
| Focal-systems.Corp                 | 5         | 1.05%   |
| HOLTEK                             | 4         | 0.84%   |
| Samsung Electronics                | 1         | 0.21%   |
| DigitalPersona                     | 1         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 47        | 9.85%   |
| Shenzhen Goodix  Fingerprint Device                                        | 39        | 8.18%   |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 6.29%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 5.87%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 26        | 5.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 3.98%   |
| Shenzhen Goodix FingerPrint                                                | 16        | 3.35%   |
| Elan ELAN:ARM-M4                                                           | 16        | 3.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 15        | 3.14%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 14        | 2.94%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 11        | 2.31%   |
| Synaptics WBDI Device                                                      | 11        | 2.31%   |
| Elan ELAN:Fingerprint                                                      | 11        | 2.31%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 2.1%    |
| Synaptics UWP WBDI                                                         | 10        | 2.1%    |
| Synaptics  WBDI                                                            | 10        | 2.1%    |
| Synaptics WBDI                                                             | 9         | 1.89%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.68%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 1.68%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 1.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 1.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 1.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.47%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.47%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 1.47%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 7         | 1.47%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.26%   |
| Synaptics UWP WBDI Device                                                  | 6         | 1.26%   |
| Unknown                                                                    | 6         | 1.26%   |
| Validity Sensors VFS491                                                    | 5         | 1.05%   |
| Synaptics TouchPad                                                         | 5         | 1.05%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.05%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 5         | 1.05%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.84%   |
| HOLTEK FocalTech Fingerprint Device                                        | 4         | 0.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.63%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.63%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 80        | 53.69%  |
| Alcor Micro           | 44        | 29.53%  |
| O2 Micro              | 9         | 6.04%   |
| Lenovo                | 5         | 3.36%   |
| Upek                  | 4         | 2.68%   |
| OmniKey               | 2         | 1.34%   |
| SCM Microsystems      | 1         | 0.67%   |
| Realtek Semiconductor | 1         | 0.67%   |
| Gemalto (was Gemplus) | 1         | 0.67%   |
| Clay Logic            | 1         | 0.67%   |
| Advanced Card Systems | 1         | 0.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 43        | 28.86%  |
| Broadcom 58200                                                               | 29        | 19.46%  |
| Broadcom 5880                                                                | 22        | 14.77%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 11.41%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 7.38%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 5.37%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.36%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.68%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.67%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.67%   |
| OmniKey CardMan 4321                                                         | 1         | 0.67%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.67%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.67%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.67%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.67%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.67%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2737      | 66.72%  |
| 1     | 1116      | 27.21%  |
| 2     | 213       | 5.19%   |
| 3     | 28        | 0.68%   |
| 4     | 6         | 0.15%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 463       | 28.85%  |
| Graphics card            | 229       | 14.27%  |
| Net/wireless             | 227       | 14.14%  |
| Multimedia controller    | 226       | 14.08%  |
| Chipcard                 | 141       | 8.79%   |
| Bluetooth                | 84        | 5.23%   |
| Camera                   | 65        | 4.05%   |
| Unassigned class         | 30        | 1.87%   |
| Sound                    | 30        | 1.87%   |
| Communication controller | 26        | 1.62%   |
| Net/ethernet             | 23        | 1.43%   |
| Network                  | 13        | 0.81%   |
| Storage                  | 12        | 0.75%   |
| Card reader              | 10        | 0.62%   |
| Modem                    | 9         | 0.56%   |
| Storage/raid             | 7         | 0.44%   |
| Storage/ide              | 4         | 0.25%   |
| Storage/nvme             | 3         | 0.19%   |
| Wireless                 | 1         | 0.06%   |
| Tv card                  | 1         | 0.06%   |
| Firewire controller      | 1         | 0.06%   |

