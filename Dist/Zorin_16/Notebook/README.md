Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv7                | [590a48aff9](https://linux-hardware.org/?probe=590a48aff9) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| HP            | ENVY 15                     | [4b949c1a1b](https://linux-hardware.org/?probe=4b949c1a1b) | Sep 29, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [3688fae067](https://linux-hardware.org/?probe=3688fae067) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [3befe3f6e3](https://linux-hardware.org/?probe=3befe3f6e3) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [cc9cc9e925](https://linux-hardware.org/?probe=cc9cc9e925) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [6cf7de2b6b](https://linux-hardware.org/?probe=6cf7de2b6b) | Sep 28, 2021 |
| HP            | Pavilion dv7                | [7e0b76f736](https://linux-hardware.org/?probe=7e0b76f736) | Sep 28, 2021 |
| Acer          | Aspire 4830T                | [d36367eb22](https://linux-hardware.org/?probe=d36367eb22) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [f322cce11b](https://linux-hardware.org/?probe=f322cce11b) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| ASUSTek       | X405UA                      | [3a78f7edf5](https://linux-hardware.org/?probe=3a78f7edf5) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| Lenovo        | ThinkPad T520 4242W19       | [0bbb8d9004](https://linux-hardware.org/?probe=0bbb8d9004) | Sep 26, 2021 |
| Acer          | Aspire 5738                 | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| Acer          | Aspire V3-571G              | [8bc152aa27](https://linux-hardware.org/?probe=8bc152aa27) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [9267f59e81](https://linux-hardware.org/?probe=9267f59e81) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [5404d5874a](https://linux-hardware.org/?probe=5404d5874a) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Dell          | Latitude E6220              | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | [9d3daebd14](https://linux-hardware.org/?probe=9d3daebd14) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6b6f1c017d](https://linux-hardware.org/?probe=6b6f1c017d) | Sep 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [953ed13df8](https://linux-hardware.org/?probe=953ed13df8) | Sep 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | [a65f8af3ac](https://linux-hardware.org/?probe=a65f8af3ac) | Sep 24, 2021 |
| Apple         | MacBookPro14,1              | [2d0d6ceff3](https://linux-hardware.org/?probe=2d0d6ceff3) | Sep 24, 2021 |
| KOGAN         | KAL11C250SB                 | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1af2027db5](https://linux-hardware.org/?probe=1af2027db5) | Sep 24, 2021 |
| Dell          | Latitude E6430              | [5e66bde0c9](https://linux-hardware.org/?probe=5e66bde0c9) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| HP            | Presario V6000 (GM018UA#... | [944d6af89a](https://linux-hardware.org/?probe=944d6af89a) | Sep 23, 2021 |
| MSI           | Modern 15 A11M              | [fe99af6254](https://linux-hardware.org/?probe=fe99af6254) | Sep 23, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [4d2aa790e0](https://linux-hardware.org/?probe=4d2aa790e0) | Sep 23, 2021 |
| Apple         | MacBookPro9,2               | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| HP            | Notebook                    | [91d439a6a4](https://linux-hardware.org/?probe=91d439a6a4) | Sep 22, 2021 |
| Dynabook      | dynabook PORTEGE A30-E      | [93fd738472](https://linux-hardware.org/?probe=93fd738472) | Sep 21, 2021 |
| Dynabook      | dynabook PORTEGE A30-E      | [0ec5acd020](https://linux-hardware.org/?probe=0ec5acd020) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [a43f2dc4bf](https://linux-hardware.org/?probe=a43f2dc4bf) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [069c0cafd0](https://linux-hardware.org/?probe=069c0cafd0) | Sep 21, 2021 |
| Toshiba       | Satellite L755              | [10baeecbf5](https://linux-hardware.org/?probe=10baeecbf5) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [699803b74c](https://linux-hardware.org/?probe=699803b74c) | Sep 21, 2021 |
| UNOWHY        | Y13G011S4EI                 | [70511c9675](https://linux-hardware.org/?probe=70511c9675) | Sep 21, 2021 |
| Lenovo        | G580                        | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| Acer          | Aspire E1-532               | [b0407bdd1c](https://linux-hardware.org/?probe=b0407bdd1c) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| TianBei       | TB-H7                       | [06300b96a7](https://linux-hardware.org/?probe=06300b96a7) | Sep 19, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| Toshiba       | Satellite C870-1C2          | [6129e531d9](https://linux-hardware.org/?probe=6129e531d9) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Acer          | Aspire 4352                 | [3a9aedb538](https://linux-hardware.org/?probe=3a9aedb538) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| Dell          | XPS 13 9350                 | [4dda7e9a7e](https://linux-hardware.org/?probe=4dda7e9a7e) | Sep 18, 2021 |
| ASUSTek       | U31F                        | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Dell          | XPS L321X                   | [2345076968](https://linux-hardware.org/?probe=2345076968) | Sep 18, 2021 |
| Dell          | Latitude E6430              | [2d96c4a645](https://linux-hardware.org/?probe=2d96c4a645) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [42d68963c6](https://linux-hardware.org/?probe=42d68963c6) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [50f90e7684](https://linux-hardware.org/?probe=50f90e7684) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [73a4cd0692](https://linux-hardware.org/?probe=73a4cd0692) | Sep 17, 2021 |
| HP            | Unknown                     | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [518209a322](https://linux-hardware.org/?probe=518209a322) | Sep 17, 2021 |
| Dell          | Latitude E5470              | [9a036a26a4](https://linux-hardware.org/?probe=9a036a26a4) | Sep 17, 2021 |
| HP            | Notebook                    | [6b2785c2e0](https://linux-hardware.org/?probe=6b2785c2e0) | Sep 17, 2021 |
| Dell          | Latitude E5500              | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| HP            | 245 G5 Notebook PC          | [ece740cf39](https://linux-hardware.org/?probe=ece740cf39) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [04ba56c326](https://linux-hardware.org/?probe=04ba56c326) | Sep 16, 2021 |
| Toshiba       | Satellite L755              | [142e3e40c2](https://linux-hardware.org/?probe=142e3e40c2) | Sep 16, 2021 |
| Toshiba       | Satellite C75D-B            | [152dd3680d](https://linux-hardware.org/?probe=152dd3680d) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [6d381b570b](https://linux-hardware.org/?probe=6d381b570b) | Sep 15, 2021 |
| HP            | 255 G4 Notebook PC          | [c8a384ed00](https://linux-hardware.org/?probe=c8a384ed00) | Sep 15, 2021 |
| HP            | EliteBook 840 G5            | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Latitude E7440              | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Dell          | Latitude E6520              | [1bd8b6a82f](https://linux-hardware.org/?probe=1bd8b6a82f) | Sep 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [983922cfbf](https://linux-hardware.org/?probe=983922cfbf) | Sep 15, 2021 |
| Acer          | Aspire 5733Z                | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Notebook                    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Dell          | Latitude E5470              | [032f256bab](https://linux-hardware.org/?probe=032f256bab) | Sep 14, 2021 |
| Sony          | VPCF215FX                   | [173d8636d4](https://linux-hardware.org/?probe=173d8636d4) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | [864dde8a99](https://linux-hardware.org/?probe=864dde8a99) | Sep 13, 2021 |
| Toshiba       | Satellite C870-1C2          | [3818ff8f07](https://linux-hardware.org/?probe=3818ff8f07) | Sep 12, 2021 |
| HP            | Victus by HP Laptop 16-e... | [6a980ac620](https://linux-hardware.org/?probe=6a980ac620) | Sep 12, 2021 |
| Dell          | Latitude E6430              | [aff84b5ec1](https://linux-hardware.org/?probe=aff84b5ec1) | Sep 12, 2021 |
| Google        | Kindred                     | [c9ee8560b8](https://linux-hardware.org/?probe=c9ee8560b8) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [404d33775d](https://linux-hardware.org/?probe=404d33775d) | Sep 12, 2021 |
| Dell          | Latitude E5500              | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [3dcddbd59e](https://linux-hardware.org/?probe=3dcddbd59e) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| HP            | Laptop 15-dy1xxx            | [728e0facd6](https://linux-hardware.org/?probe=728e0facd6) | Sep 11, 2021 |
| Acer          | Aspire 4830T                | [4e69ac73e4](https://linux-hardware.org/?probe=4e69ac73e4) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| MSI           | GE75 Raider 8RF             | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| Toshiba       | Satellite C850-1CP          | [8cec9884a8](https://linux-hardware.org/?probe=8cec9884a8) | Sep 10, 2021 |
| Unknown       | Unknown                     | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [f6d8fa5367](https://linux-hardware.org/?probe=f6d8fa5367) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [87b52d41c7](https://linux-hardware.org/?probe=87b52d41c7) | Sep 10, 2021 |
| HP            | Notebook                    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Toshiba       | Satellite C75D-B            | [0f52ac751b](https://linux-hardware.org/?probe=0f52ac751b) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [97b34f8c7f](https://linux-hardware.org/?probe=97b34f8c7f) | Sep 08, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [be8d4bd453](https://linux-hardware.org/?probe=be8d4bd453) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| Acer          | V5-171                      | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| HP            | Pavilion dv5                | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Lenovo        | G505s 20255                 | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| ASUSTek       | GR8                         | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | ENVY 15                     | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Insyde        | i101c                       | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | Pavilion 15                 | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| Acer          | Aspire 5100                 | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Acer          | AO722                       | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| TianBei       | TB-H7                       | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| Acer          | Aspire 8940G                | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| HP            | ProBook 450 G2              | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| Acer          | Nitro AN515-55              | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Acer          | Swift SF114-34              | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| HP            | ProBook 450 G2              | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| Dell          | Inspiron 7537               | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Dell          | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Dell          | Inspiron 3582               | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| Dell          | XPS 13 9370                 | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| HP            | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP            | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Razer         | Book 13 - RZ09-0357         | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Dell          | Vostro 5490                 | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-27-generic | 85        | 44.04%  |
| 5.11.0-34-generic | 55        | 28.5%   |
| 5.11.0-36-generic | 20        | 10.36%  |
| 5.11.0-25-generic | 7         | 3.63%   |
| 5.8.0-53-generic  | 6         | 3.11%   |
| 5.8.0-59-generic  | 5         | 2.59%   |
| 5.8.0-55-generic  | 5         | 2.59%   |
| 5.8.0-50-generic  | 4         | 2.07%   |
| 5.11.0-37-generic | 3         | 1.55%   |
| 5.8.0-63-generic  | 1         | 0.52%   |
| 5.13.18-xanmod1   | 1         | 0.52%   |
| 5.10.0-1044-oem   | 1         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 166       | 87.83%  |
| 5.8.0   | 21        | 11.11%  |
| 5.13.18 | 1         | 0.53%   |
| 5.10.0  | 1         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 166       | 87.83%  |
| 5.8     | 21        | 11.11%  |
| 5.13    | 1         | 0.53%   |
| 5.10    | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 187       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 185       | 98.93%  |
| Unknown | 2         | 1.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 184       | 97.87%  |
| Wayland | 3         | 1.6%    |
| Unknown | 1         | 0.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 159       | 85.03%  |
| GDM     | 25        | 13.37%  |
| GDM3    | 3         | 1.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 63        | 33.69%  |
| en_GB | 20        | 10.7%   |
| de_DE | 16        | 8.56%   |
| pt_BR | 14        | 7.49%   |
| en_IN | 13        | 6.95%   |
| es_ES | 7         | 3.74%   |
| en_CA | 6         | 3.21%   |
| fr_FR | 5         | 2.67%   |
| es_MX | 5         | 2.67%   |
| cs_CZ | 4         | 2.14%   |
| pt_PT | 3         | 1.6%    |
| it_IT | 3         | 1.6%    |
| es_CL | 3         | 1.6%    |
| en_ZA | 3         | 1.6%    |
| en_NZ | 3         | 1.6%    |
| en_AU | 3         | 1.6%    |
| nl_NL | 2         | 1.07%   |
| hu_HU | 2         | 1.07%   |
| sv_SE | 1         | 0.53%   |
| sk_SK | 1         | 0.53%   |
| ru_UA | 1         | 0.53%   |
| ru_RU | 1         | 0.53%   |
| pl_PL | 1         | 0.53%   |
| ja_JP | 1         | 0.53%   |
| fr_BE | 1         | 0.53%   |
| es_PE | 1         | 0.53%   |
| en_PH | 1         | 0.53%   |
| de_CH | 1         | 0.53%   |
| de_AT | 1         | 0.53%   |
| bg_BG | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 122       | 65.24%  |
| BIOS | 65        | 34.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 178       | 95.19%  |
| Zfs     | 4         | 2.14%   |
| Btrfs   | 3         | 1.6%    |
| Overlay | 1         | 0.53%   |
| Ext2    | 1         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 161       | 86.1%   |
| GPT     | 25        | 13.37%  |
| MBR     | 1         | 0.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 186       | 99.47%  |
| Yes       | 1         | 0.53%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 168       | 89.84%  |
| Yes       | 19        | 10.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 38        | 20.32%  |
| Dell                | 32        | 17.11%  |
| Lenovo              | 31        | 16.58%  |
| Acer                | 25        | 13.37%  |
| ASUSTek Computer    | 21        | 11.23%  |
| Toshiba             | 9         | 4.81%   |
| Apple               | 7         | 3.74%   |
| MSI                 | 4         | 2.14%   |
| LG Electronics      | 4         | 2.14%   |
| Sony                | 3         | 1.6%    |
| Unknown             | 2         | 1.07%   |
| UNOWHY              | 1         | 0.53%   |
| TianBei             | 1         | 0.53%   |
| Samsung Electronics | 1         | 0.53%   |
| Razer               | 1         | 0.53%   |
| Packard Bell        | 1         | 0.53%   |
| KOGAN               | 1         | 0.53%   |
| Jumper              | 1         | 0.53%   |
| Insyde              | 1         | 0.53%   |
| Google              | 1         | 0.53%   |
| Fujitsu             | 1         | 0.53%   |
| Dynabook            | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 4         | 2.14%   |
| HP Notebook                            | 3         | 1.6%    |
| HP ENVY Sleekbook 4 PC                 | 2         | 1.07%   |
| Dell Latitude E6430                    | 2         | 1.07%   |
| Dell Inspiron 5566                     | 2         | 1.07%   |
| Dell Inspiron 15 7000 Gaming           | 2         | 1.07%   |
| ASUS X405UA                            | 2         | 1.07%   |
| Acer Aspire V3-571G                    | 2         | 1.07%   |
| Acer Aspire ES1-512                    | 2         | 1.07%   |
| UNOWHY Y13G011S4EI                     | 1         | 0.53%   |
| Toshiba Satellite S75Dt-A              | 1         | 0.53%   |
| Toshiba Satellite Pro L450D            | 1         | 0.53%   |
| Toshiba Satellite L755                 | 1         | 0.53%   |
| Toshiba Satellite C870-1C2             | 1         | 0.53%   |
| Toshiba Satellite C850D-11C            | 1         | 0.53%   |
| Toshiba Satellite C850-1CP             | 1         | 0.53%   |
| Toshiba Satellite C75D-B               | 1         | 0.53%   |
| Toshiba PORTEGE Z30-A                  | 1         | 0.53%   |
| Toshiba PORTEGE R700                   | 1         | 0.53%   |
| TianBei TB-H7                          | 1         | 0.53%   |
| Sony VPCS135FX                         | 1         | 0.53%   |
| Sony VPCF215FX                         | 1         | 0.53%   |
| Sony VGN-SR5                           | 1         | 0.53%   |
| Samsung 550P5C/550P7C                  | 1         | 0.53%   |
| Razer Book 13 - RZ09-0357              | 1         | 0.53%   |
| Packard Bell DOT S                     | 1         | 0.53%   |
| MSI Modern 15 A11M                     | 1         | 0.53%   |
| MSI GS75 Stealth 10SF                  | 1         | 0.53%   |
| MSI GL62 7RDX                          | 1         | 0.53%   |
| MSI GE75 Raider 8RF                    | 1         | 0.53%   |
| LG S460-G.BG31P1                       | 1         | 0.53%   |
| LG C400-G.BC22P1                       | 1         | 0.53%   |
| LG A410-K.BE47P1                       | 1         | 0.53%   |
| LG 17U70N-R.AAS7U1                     | 1         | 0.53%   |
| Lenovo Yoga 3 Pro-1370 80HE            | 1         | 0.53%   |
| Lenovo ThinkPad Yoga 11e 20DAS0SF00    | 1         | 0.53%   |
| Lenovo ThinkPad X131e 3371AL2          | 1         | 0.53%   |
| Lenovo ThinkPad W520 4284AW3           | 1         | 0.53%   |
| Lenovo ThinkPad T520 42435GG           | 1         | 0.53%   |
| Lenovo ThinkPad T520 4242W4F           | 1         | 0.53%   |
| Lenovo ThinkPad T520 4242W19           | 1         | 0.53%   |
| Lenovo ThinkPad T470s W10DG 20JTS0280G | 1         | 0.53%   |
| Lenovo ThinkPad T440p 20AWS1CH00       | 1         | 0.53%   |
| Lenovo ThinkPad P50 20EN001EUS         | 1         | 0.53%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW  | 1         | 0.53%   |
| Lenovo ThinkPad E15 Gen 2 20TD000HZA   | 1         | 0.53%   |
| Lenovo ThinkPad E14 20RAS1Q800         | 1         | 0.53%   |
| Lenovo IdeaPad Z510 20287              | 1         | 0.53%   |
| Lenovo IdeaPad Y570 0862               | 1         | 0.53%   |
| Lenovo IdeaPad S540-14API 81NH         | 1         | 0.53%   |
| Lenovo IdeaPad S340-14API 81NB         | 1         | 0.53%   |
| Lenovo IdeaPad 5 15ALC05 82LN          | 1         | 0.53%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 1         | 0.53%   |
| Lenovo IdeaPad 310 Touch-15IKB 80TW    | 1         | 0.53%   |
| Lenovo IdeaPad 3 15IIL05 81WE          | 1         | 0.53%   |
| Lenovo IdeaPad 3 14ADA05 81W0          | 1         | 0.53%   |
| Lenovo IdeaPad 120S-14IAP 81A5         | 1         | 0.53%   |
| Lenovo IdeaPad 100-15IBD 80QQ          | 1         | 0.53%   |
| Lenovo G580                            | 1         | 0.53%   |
| Lenovo G505s 20255                     | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 20        | 10.7%   |
| Lenovo ThinkPad    | 12        | 6.42%   |
| Lenovo IdeaPad     | 11        | 5.88%   |
| HP Pavilion        | 9         | 4.81%   |
| Dell Latitude      | 9         | 4.81%   |
| Dell Inspiron      | 9         | 4.81%   |
| Toshiba Satellite  | 7         | 3.74%   |
| Dell XPS           | 7         | 3.74%   |
| HP EliteBook       | 6         | 3.21%   |
| HP ENVY            | 5         | 2.67%   |
| ASUS VivoBook      | 5         | 2.67%   |
| HP ProBook         | 4         | 2.14%   |
| Unknown            | 4         | 2.14%   |
| HP Notebook        | 3         | 1.6%    |
| HP 255             | 3         | 1.6%    |
| Dell Vostro        | 3         | 1.6%    |
| Dell Precision     | 3         | 1.6%    |
| Toshiba PORTEGE    | 2         | 1.07%   |
| ASUS ZenBook       | 2         | 1.07%   |
| ASUS X405UA        | 2         | 1.07%   |
| ASUS ASUS          | 2         | 1.07%   |
| Apple MacBookPro11 | 2         | 1.07%   |
| Acer Swift         | 2         | 1.07%   |
| UNOWHY Y13G011S4EI | 1         | 0.53%   |
| TianBei TB-H7      | 1         | 0.53%   |
| Sony VPCS135FX     | 1         | 0.53%   |
| Sony VPCF215FX     | 1         | 0.53%   |
| Sony VGN-SR5       | 1         | 0.53%   |
| Samsung 550P5C     | 1         | 0.53%   |
| Razer Book         | 1         | 0.53%   |
| Packard Bell DOT   | 1         | 0.53%   |
| MSI Modern         | 1         | 0.53%   |
| MSI GS75           | 1         | 0.53%   |
| MSI GL62           | 1         | 0.53%   |
| MSI GE75           | 1         | 0.53%   |
| LG S460-G.BG31P1   | 1         | 0.53%   |
| LG C400-G.BC22P1   | 1         | 0.53%   |
| LG A410-K.BE47P1   | 1         | 0.53%   |
| LG 17U70N-R.AAS7U1 | 1         | 0.53%   |
| Lenovo Yoga        | 1         | 0.53%   |
| Lenovo G580        | 1         | 0.53%   |
| Lenovo G505s       | 1         | 0.53%   |
| Lenovo G50-80      | 1         | 0.53%   |
| Lenovo G50-70      | 1         | 0.53%   |
| Lenovo G50-30      | 1         | 0.53%   |
| Lenovo B50-70      | 1         | 0.53%   |
| Lenovo B50-30      | 1         | 0.53%   |
| KOGAN KAL11C250SB  | 1         | 0.53%   |
| Jumper EZpad       | 1         | 0.53%   |
| Insyde i101c       | 1         | 0.53%   |
| HP Victus          | 1         | 0.53%   |
| HP Presario        | 1         | 0.53%   |
| HP OMEN            | 1         | 0.53%   |
| HP Laptop          | 1         | 0.53%   |
| HP 245             | 1         | 0.53%   |
| HP 15              | 1         | 0.53%   |
| Google Kindred     | 1         | 0.53%   |
| Fujitsu LIFEBOOK   | 1         | 0.53%   |
| Dynabook dynabook  | 1         | 0.53%   |
| Dell G3            | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 36        | 19.25%  |
| 2020 | 29        | 15.51%  |
| 2019 | 22        | 11.76%  |
| 2011 | 19        | 10.16%  |
| 2018 | 16        | 8.56%   |
| 2014 | 14        | 7.49%   |
| 2012 | 11        | 5.88%   |
| 2013 | 8         | 4.28%   |
| 2017 | 7         | 3.74%   |
| 2016 | 5         | 2.67%   |
| 2015 | 5         | 2.67%   |
| 2008 | 5         | 2.67%   |
| 2009 | 4         | 2.14%   |
| 2010 | 3         | 1.6%    |
| 2007 | 2         | 1.07%   |
| 2006 | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 187       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 156       | 83.42%  |
| Enabled  | 31        | 16.58%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 186       | 99.47%  |
| Yes  | 1         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 67        | 35.83%  |
| 3.01-4.0   | 54        | 28.88%  |
| 8.01-16.0  | 33        | 17.65%  |
| 16.01-24.0 | 18        | 9.63%   |
| 32.01-64.0 | 10        | 5.35%   |
| 1.01-2.0   | 4         | 2.14%   |
| 2.01-3.0   | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 82        | 42.05%  |
| 2.01-3.0   | 62        | 31.79%  |
| 3.01-4.0   | 33        | 16.92%  |
| 4.01-8.0   | 14        | 7.18%   |
| 0.51-1.0   | 2         | 1.03%   |
| 24.01-32.0 | 1         | 0.51%   |
| 8.01-16.0  | 1         | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 142       | 75.94%  |
| 2      | 39        | 20.86%  |
| 3      | 6         | 3.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 62.03%  |
| Yes       | 71        | 37.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 84.49%  |
| No        | 29        | 15.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 96.26%  |
| No        | 7         | 3.74%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 78.07%  |
| No        | 41        | 21.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 30        | 16.04%  |
| Germany      | 19        | 10.16%  |
| Brazil       | 19        | 10.16%  |
| UK           | 16        | 8.56%   |
| India        | 14        | 7.49%   |
| Spain        | 7         | 3.74%   |
| Mexico       | 7         | 3.74%   |
| Canada       | 6         | 3.21%   |
| South Africa | 5         | 2.67%   |
| France       | 5         | 2.67%   |
| Italy        | 4         | 2.14%   |
| Czechia      | 4         | 2.14%   |
| New Zealand  | 3         | 1.6%    |
| Netherlands  | 3         | 1.6%    |
| Hungary      | 3         | 1.6%    |
| Chile        | 3         | 1.6%    |
| Austria      | 3         | 1.6%    |
| Australia    | 3         | 1.6%    |
| Switzerland  | 2         | 1.07%   |
| Sweden       | 2         | 1.07%   |
| Romania      | 2         | 1.07%   |
| Portugal     | 2         | 1.07%   |
| Philippines  | 2         | 1.07%   |
| Morocco      | 2         | 1.07%   |
| Vietnam      | 1         | 0.53%   |
| Ukraine      | 1         | 0.53%   |
| Turkey       | 1         | 0.53%   |
| Thailand     | 1         | 0.53%   |
| Tanzania     | 1         | 0.53%   |
| Slovakia     | 1         | 0.53%   |
| Russia       | 1         | 0.53%   |
| Poland       | 1         | 0.53%   |
| Norway       | 1         | 0.53%   |
| Nepal        | 1         | 0.53%   |
| Madagascar   | 1         | 0.53%   |
| Kenya        | 1         | 0.53%   |
| Japan        | 1         | 0.53%   |
| Israel       | 1         | 0.53%   |
| Indonesia    | 1         | 0.53%   |
| Greece       | 1         | 0.53%   |
| Colombia     | 1         | 0.53%   |
| Bulgaria     | 1         | 0.53%   |
| Belgium      | 1         | 0.53%   |
| Belarus      | 1         | 0.53%   |
| Angola       | 1         | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| S??o Lu?­s               | 3         | 1.6%    |
| Hyderabad                | 3         | 1.6%    |
| Vienna                   | 2         | 1.06%   |
| Taboao da Serra          | 2         | 1.06%   |
| Rome                     | 2         | 1.06%   |
| Paris                    | 2         | 1.06%   |
| Montreal                 | 2         | 1.06%   |
| Madrid                   | 2         | 1.06%   |
| Maca?©                   | 2         | 1.06%   |
| London                   | 2         | 1.06%   |
| Glasgow                  | 2         | 1.06%   |
| Ernakulam                | 2         | 1.06%   |
| Chennai                  | 2         | 1.06%   |
| Auckland                 | 2         | 1.06%   |
| Ahmedabad                | 2         | 1.06%   |
| Zurich                   | 1         | 0.53%   |
| Zionsville               | 1         | 0.53%   |
| Zaventem                 | 1         | 0.53%   |
| Zacatecas City           | 1         | 0.53%   |
| Zabrze                   | 1         | 0.53%   |
| Yokohama                 | 1         | 0.53%   |
| Wigan                    | 1         | 0.53%   |
| West Jordan              | 1         | 0.53%   |
| Veracruz                 | 1         | 0.53%   |
| Vancouver                | 1         | 0.53%   |
| Twinsburg                | 1         | 0.53%   |
| Tangier                  | 1         | 0.53%   |
| Sydney                   | 1         | 0.53%   |
| Sutton Coldfield         | 1         | 0.53%   |
| Stuttgart                | 1         | 0.53%   |
| Stockholm                | 1         | 0.53%   |
| Stadskanaal              | 1         | 0.53%   |
| Spremberg                | 1         | 0.53%   |
| Sigless                  | 1         | 0.53%   |
| Seville                  | 1         | 0.53%   |
| S??o Paulo               | 1         | 0.53%   |
| S??o Jo??o del Rei       | 1         | 0.53%   |
| Santa Cruz do Rio Pardo  | 1         | 0.53%   |
| Sant Carles de la Rapita | 1         | 0.53%   |
| San Francisco            | 1         | 0.53%   |
| Sainte-Marie             | 1         | 0.53%   |
| Saint Matthews           | 1         | 0.53%   |
| Rochester                | 1         | 0.53%   |
| Ro????ava                | 1         | 0.53%   |
| Rio de Janeiro           | 1         | 0.53%   |
| Rijen                    | 1         | 0.53%   |
| Richmond Hill            | 1         | 0.53%   |
| Reus                     | 1         | 0.53%   |
| R??sselsheim am Main     | 1         | 0.53%   |
| Rataje                   | 1         | 0.53%   |
| Quezon City              | 1         | 0.53%   |
| Pretoria                 | 1         | 0.53%   |
| Premnitz                 | 1         | 0.53%   |
| Prague                   | 1         | 0.53%   |
| Pontinha                 | 1         | 0.53%   |
| Pittsburgh               | 1         | 0.53%   |
| Pite??                   | 1         | 0.53%   |
| Pilsen                   | 1         | 0.53%   |
| Philadelphia             | 1         | 0.53%   |
| Peterborough             | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 41     | 16.06%  |
| Seagate             | 34        | 35     | 15.6%   |
| Toshiba             | 20        | 20     | 9.17%   |
| WDC                 | 17        | 17     | 7.8%    |
| SanDisk             | 13        | 16     | 5.96%   |
| Unknown             | 10        | 11     | 4.59%   |
| SK Hynix            | 9         | 11     | 4.13%   |
| Hitachi             | 9         | 9      | 4.13%   |
| HGST                | 8         | 9      | 3.67%   |
| Crucial             | 8         | 8      | 3.67%   |
| Kingston            | 7         | 8      | 3.21%   |
| Micron Technology   | 5         | 6      | 2.29%   |
| A-DATA Technology   | 5         | 5      | 2.29%   |
| SPCC                | 4         | 4      | 1.83%   |
| Intel               | 4         | 4      | 1.83%   |
| Apple               | 4         | 5      | 1.83%   |
| LITEONIT            | 3         | 4      | 1.38%   |
| Intenso             | 3         | 3      | 1.38%   |
| Fujitsu             | 3         | 4      | 1.38%   |
| PNY                 | 2         | 3      | 0.92%   |
| Lite-On             | 2         | 2      | 0.92%   |
| KIOXIA              | 2         | 2      | 0.92%   |
| Verbatim            | 1         | 1      | 0.46%   |
| Vaseky              | 1         | 2      | 0.46%   |
| Team                | 1         | 1      | 0.46%   |
| SABRENT             | 1         | 1      | 0.46%   |
| Phison              | 1         | 1      | 0.46%   |
| Patriot             | 1         | 1      | 0.46%   |
| KingSpec            | 1         | 1      | 0.46%   |
| JMicron             | 1         | 2      | 0.46%   |
| China               | 1         | 2      | 0.46%   |
| BUFFALO             | 1         | 1      | 0.46%   |
| Unknown             | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 6         | 2.64%   |
| Unknown MMC Card  64GB                  | 5         | 2.2%    |
| Toshiba MQ01ABF050 500GB                | 5         | 2.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 5         | 2.2%    |
| Samsung NVMe SSD Drive 512GB            | 4         | 1.76%   |
| SK Hynix NVMe SSD Drive 256GB           | 3         | 1.32%   |
| Seagate ST9500325AS 500GB               | 3         | 1.32%   |
| Sandisk NVMe SSD Drive 256GB            | 3         | 1.32%   |
| Samsung NVMe SSD Drive 256GB            | 3         | 1.32%   |
| HGST HTS725050A7E630 500GB              | 3         | 1.32%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.88%   |
| Unknown SD/MMC/MS PRO 128GB             | 2         | 0.88%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.88%   |
| Toshiba MQ02ABD100H 1TB                 | 2         | 0.88%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 0.88%   |
| SPCC SPCCSolidStateDisk 256GB SSD       | 2         | 0.88%   |
| SK Hynix NVMe SSD Drive 512GB           | 2         | 0.88%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 0.88%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.88%   |
| SanDisk SSD PLUS 480GB                  | 2         | 0.88%   |
| Sandisk NVMe SSD Drive 512GB            | 2         | 0.88%   |
| Samsung SSD 860 EVO 500GB               | 2         | 0.88%   |
| Samsung SSD 860 EVO 250GB               | 2         | 0.88%   |
| Samsung SSD 850 EVO 500GB               | 2         | 0.88%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 0.88%   |
| Micron NVMe SSD Drive 512GB             | 2         | 0.88%   |
| KIOXIA NVMe SSD Drive 512GB             | 2         | 0.88%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 0.88%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 0.88%   |
| Hitachi HTS547575A9E384 752GB           | 2         | 0.88%   |
| Hitachi HTS545032B9A300 320GB           | 2         | 0.88%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.88%   |
| HGST HTS545050A7E380 500GB              | 2         | 0.88%   |
| Crucial CT240BX500SSD1 240GB            | 2         | 0.88%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.44%   |
| WDC WD7500BPKX-00HPJT0 752GB            | 1         | 0.44%   |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 0.44%   |
| WDC WD5000LPVT-22G33T0 500GB            | 1         | 0.44%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.44%   |
| WDC WD5000BPVT-22HXZT3 500GB            | 1         | 0.44%   |
| WDC WD3200BVVT-63A26Y0 320GB            | 1         | 0.44%   |
| WDC WD1600BEVS-60RST0 160GB             | 1         | 0.44%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.44%   |
| WDC WD10JPVX-60JC3T1 1TB                | 1         | 0.44%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 0.44%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 0.44%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB    | 1         | 0.44%   |
| WDC PC SN520 NVMe 256GB                 | 1         | 0.44%   |
| Verbatim Vi550 S3 SSD 512GB             | 1         | 0.44%   |
| Vaseky V820/256G 256GB                  | 1         | 0.44%   |
| Unknown NCard  32GB                     | 1         | 0.44%   |
| Unknown MMC64G  64GB                    | 1         | 0.44%   |
| Unknown MMC Card  32GB                  | 1         | 0.44%   |
| Unknown MMC Card  128GB                 | 1         | 0.44%   |
| Toshiba THNSNJ256GMCT 256GB SSD         | 1         | 0.44%   |
| Toshiba THNSNJ128GCSU 128GB SSD         | 1         | 0.44%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.44%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 0.44%   |
| Toshiba MK5056GSY 500GB                 | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 33     | 39.29%  |
| Toshiba             | 13        | 13     | 15.48%  |
| WDC                 | 12        | 12     | 14.29%  |
| Hitachi             | 9         | 9      | 10.71%  |
| HGST                | 8         | 9      | 9.52%   |
| Samsung Electronics | 3         | 3      | 3.57%   |
| Fujitsu             | 3         | 4      | 3.57%   |
| Unknown             | 2         | 2      | 2.38%   |
| Apple               | 1         | 1      | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 18     | 22.67%  |
| Crucial             | 8         | 8      | 10.67%  |
| Kingston            | 7         | 8      | 9.33%   |
| SanDisk             | 6         | 8      | 8%      |
| Toshiba             | 4         | 4      | 5.33%   |
| SPCC                | 4         | 4      | 5.33%   |
| SK Hynix            | 3         | 3      | 4%      |
| Micron Technology   | 3         | 4      | 4%      |
| LITEONIT            | 3         | 4      | 4%      |
| Intenso             | 3         | 3      | 4%      |
| A-DATA Technology   | 3         | 3      | 4%      |
| WDC                 | 2         | 2      | 2.67%   |
| PNY                 | 2         | 3      | 2.67%   |
| Apple               | 2         | 2      | 2.67%   |
| Verbatim            | 1         | 1      | 1.33%   |
| Team                | 1         | 1      | 1.33%   |
| SABRENT             | 1         | 1      | 1.33%   |
| Patriot             | 1         | 1      | 1.33%   |
| KingSpec            | 1         | 1      | 1.33%   |
| Intel               | 1         | 1      | 1.33%   |
| China               | 1         | 2      | 1.33%   |
| BUFFALO             | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 83        | 86     | 39.34%  |
| SSD     | 70        | 83     | 33.18%  |
| NVMe    | 47        | 58     | 22.27%  |
| MMC     | 8         | 9      | 3.79%   |
| Unknown | 3         | 5      | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 142       | 166    | 69.61%  |
| NVMe | 46        | 56     | 22.55%  |
| SAS  | 8         | 10     | 3.92%   |
| MMC  | 8         | 9      | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 104       | 119    | 68.42%  |
| 0.51-1.0   | 44        | 46     | 28.95%  |
| 1.01-2.0   | 4         | 4      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 64        | 34.22%  |
| 251-500        | 57        | 30.48%  |
| 501-1000       | 27        | 14.44%  |
| 51-100         | 21        | 11.23%  |
| 1001-2000      | 7         | 3.74%   |
| 21-50          | 4         | 2.14%   |
| 2001-3000      | 2         | 1.07%   |
| 1-20           | 2         | 1.07%   |
| Unknown        | 2         | 1.07%   |
| More than 3000 | 1         | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 91        | 48.4%   |
| 21-50    | 53        | 28.19%  |
| 101-250  | 17        | 9.04%   |
| 51-100   | 15        | 7.98%   |
| 251-500  | 5         | 2.66%   |
| 501-1000 | 5         | 2.66%   |
| Unknown  | 2         | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB    | 2         | 2      | 40%     |
| WDC WD10JPVX-22JC3T0 1TB   | 1         | 1      | 20%     |
| Seagate ST9200420ASG 200GB | 1         | 1      | 20%     |
| HGST HTS725050A7E630 500GB | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| HGST    | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 161       | 207    | 84.29%  |
| Works    | 24        | 28     | 12.57%  |
| Malfunc  | 5         | 5      | 2.62%   |
| Failed   | 1         | 1      | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 137       | 64.32%  |
| AMD                              | 26        | 12.21%  |
| Samsung Electronics              | 20        | 9.39%   |
| Sandisk                          | 9         | 4.23%   |
| SK Hynix                         | 6         | 2.82%   |
| KIOXIA                           | 3         | 1.41%   |
| Toshiba America Info Systems     | 2         | 0.94%   |
| Micron Technology                | 2         | 0.94%   |
| Lite-On Technology               | 2         | 0.94%   |
| ADATA Technology                 | 2         | 0.94%   |
| Silicon Integrated Systems [SiS] | 1         | 0.47%   |
| Phison Electronics               | 1         | 0.47%   |
| Nvidia                           | 1         | 0.47%   |
| Apple                            | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 22        | 9.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 20        | 8.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 14        | 6.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 13        | 5.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 13        | 5.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 10        | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 9         | 4%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 6         | 2.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 6         | 2.67%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 5         | 2.22%   |
| Samsung NVMe SSD Controller 980                                                        | 5         | 2.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 2.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 5         | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 5         | 2.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 2.22%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 4         | 1.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 1.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 1.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 4         | 1.78%   |
| KIOXIA Non-Volatile memory controller                                                  | 3         | 1.33%   |
| Intel SSD 660P Series                                                                  | 3         | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 3         | 1.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.33%   |
| SK Hynix BC511                                                                         | 2         | 0.89%   |
| Sandisk PC SN520 NVMe SSD                                                              | 2         | 0.89%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 0.89%   |
| Micron Non-Volatile memory controller                                                  | 2         | 0.89%   |
| Lite-On Non-Volatile memory controller                                                 | 2         | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 0.89%   |
| Intel SATA Controller [RAID mode]                                                      | 2         | 0.89%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 0.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 0.89%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 1         | 0.44%   |
| Toshiba America Info Systems NVMe Controller                                           | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.44%   |
| Sandisk Non-Volatile memory controller                                                 | 1         | 0.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.44%   |
| Samsung Electronics SATA controller                                                    | 1         | 0.44%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 0.44%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.44%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 0.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 0.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 0.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.44%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.44%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 0.44%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 0.44%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.44%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.44%   |
| Apple S3X NVMe Controller                                                              | 1         | 0.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 0.44%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 143       | 65.6%   |
| NVMe | 46        | 21.1%   |
| RAID | 17        | 7.8%    |
| IDE  | 12        | 5.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 154       | 82.35%  |
| AMD    | 33        | 17.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 3.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 3.21%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 3.21%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 2.14%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 2.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 2.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.6%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 1.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 1.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.6%    |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 3         | 1.6%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 1.07%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 2         | 1.07%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.07%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 1.07%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.07%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 1.07%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 1.07%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 1.07%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.07%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.07%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.07%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 1.07%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.07%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 1.07%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 1.07%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.07%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 2         | 1.07%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.07%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.07%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.07%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 2         | 1.07%   |
| AMD A10-5750M APU with Radeon HD Graphics     | 2         | 1.07%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.53%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.53%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.53%   |
| Intel Pentium CPU B970 @ 2.30GHz              | 1         | 0.53%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.53%   |
| Intel Pentium CPU 3550M @ 2.30GHz             | 1         | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.53%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.53%   |
| Intel Core i7-6560U CPU @ 2.20GHz             | 1         | 0.53%   |
| Intel Core i7-4940MX CPU @ 3.10GHz            | 1         | 0.53%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz            | 1         | 0.53%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.53%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.53%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.53%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.53%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.53%   |
| Intel Core i7-3687U CPU @ 2.10GHz             | 1         | 0.53%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.53%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.53%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 0.53%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 62        | 33.16%  |
| Intel Core i7                        | 35        | 18.72%  |
| Intel Core i3                        | 15        | 8.02%   |
| Intel Celeron                        | 13        | 6.95%   |
| Intel Core 2 Duo                     | 10        | 5.35%   |
| Intel Pentium                        | 8         | 4.28%   |
| AMD Ryzen 5                          | 8         | 4.28%   |
| Other                                | 7         | 3.74%   |
| AMD A6                               | 5         | 2.67%   |
| AMD Ryzen 7                          | 3         | 1.6%    |
| Intel Atom                           | 2         | 1.07%   |
| AMD Ryzen 3                          | 2         | 1.07%   |
| AMD E1                               | 2         | 1.07%   |
| AMD A10                              | 2         | 1.07%   |
| Intel Pentium Silver                 | 1         | 0.53%   |
| Intel Pentium Dual-Core              | 1         | 0.53%   |
| Intel Celeron M                      | 1         | 0.53%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.53%   |
| AMD Turion 64 Mobile                 | 1         | 0.53%   |
| AMD Ryzen 7 PRO                      | 1         | 0.53%   |
| AMD FX                               | 1         | 0.53%   |
| AMD E2                               | 1         | 0.53%   |
| AMD E                                | 1         | 0.53%   |
| AMD C-60                             | 1         | 0.53%   |
| AMD Athlon                           | 1         | 0.53%   |
| AMD A8                               | 1         | 0.53%   |
| AMD A4                               | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 104       | 55.61%  |
| 4      | 72        | 38.5%   |
| 6      | 5         | 2.67%   |
| 8      | 4         | 2.14%   |
| 1      | 2         | 1.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 187       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 134       | 71.66%  |
| 1      | 53        | 28.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 187       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 19        | 10.11%  |
| 0x306a9    | 15        | 7.98%   |
| Unknown    | 15        | 7.98%   |
| 0x806ea    | 13        | 6.91%   |
| 0x40651    | 10        | 5.32%   |
| 0x806ec    | 6         | 3.19%   |
| 0x306d4    | 6         | 3.19%   |
| 0x20655    | 6         | 3.19%   |
| 0x806e9    | 5         | 2.66%   |
| 0x806c1    | 5         | 2.66%   |
| 0x506c9    | 5         | 2.66%   |
| 0x406e3    | 5         | 2.66%   |
| 0x30678    | 5         | 2.66%   |
| 0x1067a    | 5         | 2.66%   |
| 0x08108102 | 5         | 2.66%   |
| 0x906ea    | 4         | 2.13%   |
| 0x906e9    | 4         | 2.13%   |
| 0x306c3    | 4         | 2.13%   |
| 0xa0652    | 3         | 1.6%    |
| 0x706e5    | 3         | 1.6%    |
| 0x08108109 | 3         | 1.6%    |
| 0x07030106 | 3         | 1.6%    |
| 0x05000119 | 3         | 1.6%    |
| 0x806eb    | 2         | 1.06%   |
| 0x6fb      | 2         | 1.06%   |
| 0x506e3    | 2         | 1.06%   |
| 0x20652    | 2         | 1.06%   |
| 0x10676    | 2         | 1.06%   |
| 0x08600106 | 2         | 1.06%   |
| 0x08600104 | 2         | 1.06%   |
| 0x07030105 | 2         | 1.06%   |
| 0x06001119 | 2         | 1.06%   |
| 0x906c0    | 1         | 0.53%   |
| 0x706a8    | 1         | 0.53%   |
| 0x706a1    | 1         | 0.53%   |
| 0x6fd      | 1         | 0.53%   |
| 0x6fa      | 1         | 0.53%   |
| 0x6f6      | 1         | 0.53%   |
| 0x406c4    | 1         | 0.53%   |
| 0x40661    | 1         | 0.53%   |
| 0x30661    | 1         | 0.53%   |
| 0x106e5    | 1         | 0.53%   |
| 0x08608102 | 1         | 0.53%   |
| 0x07030104 | 1         | 0.53%   |
| 0x07000110 | 1         | 0.53%   |
| 0x0700010f | 1         | 0.53%   |
| 0x06006704 | 1         | 0.53%   |
| 0x06003106 | 1         | 0.53%   |
| 0x03000027 | 1         | 0.53%   |
| 0x02000057 | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 40        | 21.39%  |
| SandyBridge     | 19        | 10.16%  |
| Haswell         | 16        | 8.56%   |
| IvyBridge       | 15        | 8.02%   |
| Zen+            | 9         | 4.81%   |
| Westmere        | 9         | 4.81%   |
| Skylake         | 8         | 4.28%   |
| Silvermont      | 7         | 3.74%   |
| Penryn          | 7         | 3.74%   |
| Puma            | 6         | 3.21%   |
| Broadwell       | 6         | 3.21%   |
| TigerLake       | 5         | 2.67%   |
| Goldmont        | 5         | 2.67%   |
| Core            | 5         | 2.67%   |
| Zen 2           | 4         | 2.14%   |
| IceLake         | 3         | 1.6%    |
| CometLake       | 3         | 1.6%    |
| Bobcat          | 3         | 1.6%    |
| Piledriver      | 2         | 1.07%   |
| Nehalem         | 2         | 1.07%   |
| Jaguar          | 2         | 1.07%   |
| Goldmont plus   | 2         | 1.07%   |
| Zen 3           | 1         | 0.53%   |
| Tremont         | 1         | 0.53%   |
| Steamroller     | 1         | 0.53%   |
| K8 Hammer       | 1         | 0.53%   |
| K8 & K10 hybrid | 1         | 0.53%   |
| K10 Llano       | 1         | 0.53%   |
| Excavator       | 1         | 0.53%   |
| Bonnell         | 1         | 0.53%   |
| Unknown         | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 138       | 60.53%  |
| Nvidia                           | 47        | 20.61%  |
| AMD                              | 42        | 18.42%  |
| Silicon Integrated Systems [SiS] | 1         | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                              | Notebooks | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                   | 15        | 6.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 15        | 6.38%   |
| Intel UHD Graphics 620                                                             | 13        | 5.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 11        | 4.68%   |
| AMD Picasso                                                                        | 9         | 3.83%   |
| Intel Core Processor Integrated Graphics Controller                                | 8         | 3.4%    |
| Intel HD Graphics 620                                                              | 7         | 2.98%   |
| Intel HD Graphics 630                                                              | 6         | 2.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                       | 6         | 2.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                            | 5         | 2.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                          | 5         | 2.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                                | 5         | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                         | 4         | 1.7%    |
| Intel HD Graphics 5500                                                             | 4         | 1.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                               | 4         | 1.7%    |
| AMD Renoir                                                                         | 4         | 1.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                | 4         | 1.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                    | 3         | 1.28%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]               | 3         | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                | 3         | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                  | 3         | 1.28%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                             | 3         | 1.28%   |
| Intel HD Graphics 500                                                              | 3         | 1.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                          | 3         | 1.28%   |
| Nvidia TU117M                                                                      | 2         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                         | 2         | 0.85%   |
| Nvidia GP108M [GeForce MX150]                                                      | 2         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                         | 2         | 0.85%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                   | 2         | 0.85%   |
| Nvidia GF108M [GeForce GT 540M]                                                    | 2         | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                       | 2         | 0.85%   |
| Intel HD Graphics 530                                                              | 2         | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                | 2         | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                               | 2         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 2         | 0.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                        | 2         | 0.85%   |
| AMD Richland [Radeon HD 8650G]                                                     | 2         | 0.85%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                  | 1         | 0.43%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                         | 1         | 0.43%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                            | 1         | 0.43%   |
| Nvidia GT218M [GeForce 310M]                                                       | 1         | 0.43%   |
| Nvidia GT216M [GeForce GT 240M]                                                    | 1         | 0.43%   |
| Nvidia GP108M [GeForce MX250]                                                      | 1         | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                        | 1         | 0.43%   |
| Nvidia GM108M [GeForce 940MX]                                                      | 1         | 0.43%   |
| Nvidia GM107M [GeForce GTX 860M]                                                   | 1         | 0.43%   |
| Nvidia GM107GLM [Quadro M620 Mobile]                                               | 1         | 0.43%   |
| Nvidia GM107GLM [Quadro M2000M]                                                    | 1         | 0.43%   |
| Nvidia GK208M [GeForce GT 740M]                                                    | 1         | 0.43%   |
| Nvidia GK208BM [GeForce 920M]                                                      | 1         | 0.43%   |
| Nvidia GK107M [GeForce GT 750M]                                                    | 1         | 0.43%   |
| Nvidia GK107GLM [Quadro K1100M]                                                    | 1         | 0.43%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                               | 1         | 0.43%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                  | 1         | 0.43%   |
| Nvidia GF108M [GeForce GT 555M]                                                    | 1         | 0.43%   |
| Nvidia GF108M [GeForce GT 525M]                                                    | 1         | 0.43%   |
| Nvidia GF108M [GeForce GT 435M]                                                    | 1         | 0.43%   |
| Nvidia GF108GLM [NVS 5200M]                                                        | 1         | 0.43%   |
| Nvidia GF106GLM [Quadro 2000M]                                                     | 1         | 0.43%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                         | 1         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 103       | 55.08%  |
| Intel + Nvidia | 31        | 16.58%  |
| 1 x AMD        | 29        | 15.51%  |
| 1 x Nvidia     | 10        | 5.35%   |
| AMD + Nvidia   | 6         | 3.21%   |
| Intel + AMD    | 4         | 2.14%   |
| 2 x AMD        | 3         | 1.6%    |
| 1 x SiS        | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 160       | 85.56%  |
| Proprietary | 25        | 13.37%  |
| Unknown     | 2         | 1.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 62.77%  |
| 1.01-2.0   | 24        | 12.77%  |
| 0.51-1.0   | 17        | 9.04%   |
| 0.01-0.5   | 16        | 8.51%   |
| 3.01-4.0   | 10        | 5.32%   |
| 5.01-6.0   | 2         | 1.06%   |
| 7.01-8.0   | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 42        | 21.11%  |
| Chimei Innolux          | 33        | 16.58%  |
| LG Display              | 27        | 13.57%  |
| BOE                     | 26        | 13.07%  |
| Samsung Electronics     | 17        | 8.54%   |
| Sharp                   | 8         | 4.02%   |
| Chi Mei Optoelectronics | 7         | 3.52%   |
| Apple                   | 7         | 3.52%   |
| PANDA                   | 5         | 2.51%   |
| Lenovo                  | 5         | 2.51%   |
| Goldstar                | 3         | 1.51%   |
| Dell                    | 3         | 1.51%   |
| LGD                     | 2         | 1.01%   |
| Hewlett-Packard         | 2         | 1.01%   |
| BenQ                    | 2         | 1.01%   |
| Acer                    | 2         | 1.01%   |
| Vizio                   | 1         | 0.5%    |
| Sceptre Tech            | 1         | 0.5%    |
| LG Philips              | 1         | 0.5%    |
| InnoLux Display         | 1         | 0.5%    |
| Iiyama                  | 1         | 0.5%    |
| HannStar                | 1         | 0.5%    |
| CPT                     | 1         | 0.5%    |
| AOC                     | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch         | 3         | 1.49%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch           | 3         | 1.49%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 2         | 1%      |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 2         | 1%      |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 2         | 1%      |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1%      |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 2         | 1%      |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                 | 2         | 1%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 1%      |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch         | 2         | 1%      |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch         | 2         | 1%      |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch         | 2         | 1%      |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 1%      |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 1%      |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 2         | 1%      |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 2         | 1%      |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch          | 2         | 1%      |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch           | 2         | 1%      |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch          | 2         | 1%      |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 1%      |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch           | 2         | 1%      |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 2         | 1%      |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch           | 2         | 1%      |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch           | 2         | 1%      |
| Apple Color LCD APP9C5B 1280x800 290x180mm 13.4-inch                    | 2         | 1%      |
| Vizio E43u-D2 VIZ1018 3840x2160 953x543mm 43.2-inch                     | 1         | 0.5%    |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch                 | 1         | 0.5%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                 | 1         | 0.5%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                 | 1         | 0.5%    |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                 | 1         | 0.5%    |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                 | 1         | 0.5%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                 | 1         | 0.5%    |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                 | 1         | 0.5%    |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                        | 1         | 0.5%    |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch           | 1         | 0.5%    |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch       | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3143 1366x768 256x144mm 11.6-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 340x190mm 15.3-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 1020x570mm 46.0-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM04FB 1920x1080                       | 1         | 0.5%    |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 0.5%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.5%    |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                 | 1         | 0.5%    |
| LGD LCD Monitor 3840x1200                                               | 1         | 0.5%    |
| LGD LCD Monitor 3840x1080                                               | 1         | 0.5%    |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch             | 1         | 0.5%    |
| LG Display LCD Monitor LGD6616 1366x768 277x156mm 12.5-inch             | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 82        | 42.05%  |
| 1920x1080 (FHD)   | 66        | 33.85%  |
| 1600x900 (HD+)    | 11        | 5.64%   |
| 1280x800 (WXGA)   | 8         | 4.1%    |
| 3840x2160 (4K)    | 7         | 3.59%   |
| Unknown           | 3         | 1.54%   |
| 3840x2400         | 2         | 1.03%   |
| 3200x1800 (QHD+)  | 2         | 1.03%   |
| 2880x1800         | 2         | 1.03%   |
| 2560x1600         | 2         | 1.03%   |
| 3840x1200         | 1         | 0.51%   |
| 3840x1080         | 1         | 0.51%   |
| 3600x1080         | 1         | 0.51%   |
| 2560x1440 (QHD)   | 1         | 0.51%   |
| 2560x1080         | 1         | 0.51%   |
| 2256x1504         | 1         | 0.51%   |
| 1920x515          | 1         | 0.51%   |
| 1920x1200 (WUXGA) | 1         | 0.51%   |
| 1440x900 (WXGA+)  | 1         | 0.51%   |
| 1024x600          | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 90        | 45.69%  |
| 13      | 42        | 21.32%  |
| 14      | 19        | 9.64%   |
| 17      | 11        | 5.58%   |
| Unknown | 7         | 3.55%   |
| 24      | 6         | 3.05%   |
| 11      | 5         | 2.54%   |
| 23      | 3         | 1.52%   |
| 27      | 2         | 1.02%   |
| 18      | 2         | 1.02%   |
| 84      | 1         | 0.51%   |
| 74      | 1         | 0.51%   |
| 46      | 1         | 0.51%   |
| 37      | 1         | 0.51%   |
| 34      | 1         | 0.51%   |
| 25      | 1         | 0.51%   |
| 21      | 1         | 0.51%   |
| 16      | 1         | 0.51%   |
| 12      | 1         | 0.51%   |
| 10      | 1         | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 127       | 64.47%  |
| 201-300     | 30        | 15.23%  |
| 351-400     | 13        | 6.6%    |
| 501-600     | 12        | 6.09%   |
| Unknown     | 7         | 3.55%   |
| 401-500     | 3         | 1.52%   |
| 1501-2000   | 2         | 1.02%   |
| 801-900     | 1         | 0.51%   |
| 701-800     | 1         | 0.51%   |
| 1001-1500   | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 158       | 86.81%  |
| 16/10   | 16        | 8.79%   |
| Unknown | 5         | 2.75%   |
| 3/2     | 1         | 0.55%   |
| 3.73    | 1         | 0.55%   |
| 21/9    | 1         | 0.55%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 91        | 45.96%  |
| 81-90          | 44        | 22.22%  |
| 71-80          | 17        | 8.59%   |
| 201-250        | 10        | 5.05%   |
| 121-130        | 10        | 5.05%   |
| Unknown        | 7         | 3.54%   |
| 51-60          | 5         | 2.53%   |
| More than 1000 | 2         | 1.01%   |
| 301-350        | 2         | 1.01%   |
| 141-150        | 2         | 1.01%   |
| 501-1000       | 2         | 1.01%   |
| 61-70          | 1         | 0.51%   |
| 351-500        | 1         | 0.51%   |
| 41-50          | 1         | 0.51%   |
| 251-300        | 1         | 0.51%   |
| 131-140        | 1         | 0.51%   |
| 91-100         | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 92        | 47.18%  |
| 121-160       | 55        | 28.21%  |
| 51-100        | 21        | 10.77%  |
| 161-240       | 11        | 5.64%   |
| More than 240 | 8         | 4.1%    |
| Unknown       | 7         | 3.59%   |
| 1-50          | 1         | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 165       | 87.77%  |
| 2     | 21        | 11.17%  |
| 3     | 1         | 0.53%   |
| 0     | 1         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 98        | 32.34%  |
| Intel                            | 90        | 29.7%   |
| Qualcomm Atheros                 | 48        | 15.84%  |
| Broadcom                         | 28        | 9.24%   |
| Broadcom Limited                 | 7         | 2.31%   |
| Ralink                           | 4         | 1.32%   |
| Marvell Technology Group         | 3         | 0.99%   |
| DisplayLink                      | 3         | 0.99%   |
| Xiaomi                           | 2         | 0.66%   |
| Qualcomm                         | 2         | 0.66%   |
| Huawei Technologies              | 2         | 0.66%   |
| Dell                             | 2         | 0.66%   |
| ASIX Electronics                 | 2         | 0.66%   |
| ZyXEL Communications             | 1         | 0.33%   |
| T & A Mobile Phones              | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Sierra Wireless                  | 1         | 0.33%   |
| Samsung Electronics              | 1         | 0.33%   |
| OPPO                             | 1         | 0.33%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.33%   |
| Nvidia                           | 1         | 0.33%   |
| NetGear                          | 1         | 0.33%   |
| MediaTek                         | 1         | 0.33%   |
| ICS Advent                       | 1         | 0.33%   |
| D-Link System                    | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62        | 17.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 5.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 3.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 2.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.77%   |
| Intel Wireless 7260                                               | 8         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.94%   |
| Intel Wireless 8260                                               | 6         | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.39%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.39%   |
| Intel Wireless 3165                                               | 5         | 1.39%   |
| Intel WiFi Link 5100                                              | 5         | 1.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 4         | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.11%   |
| Intel Wireless 3160                                               | 4         | 1.11%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.83%   |
| Intel Wireless 7265                                               | 3         | 0.83%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.83%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.83%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.83%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.83%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.55%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.55%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.55%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.55%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.55%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.55%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                | 2         | 0.55%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 2         | 0.55%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 2         | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.55%   |
| ZyXEL NWD-270N Wireless N-lite USB Adapter                        | 1         | 0.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.28%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 82        | 43.62%  |
| Qualcomm Atheros      | 40        | 21.28%  |
| Realtek Semiconductor | 32        | 17.02%  |
| Broadcom              | 19        | 10.11%  |
| Broadcom Limited      | 5         | 2.66%   |
| Ralink                | 4         | 2.13%   |
| ZyXEL Communications  | 1         | 0.53%   |
| Sierra Wireless       | 1         | 0.53%   |
| Qualcomm              | 1         | 0.53%   |
| NetGear               | 1         | 0.53%   |
| Dell                  | 1         | 0.53%   |
| D-Link System         | 1         | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 11        | 5.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 10        | 5.29%   |
| Intel Wireless 7260                                                           | 8         | 4.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 7         | 3.7%    |
| Intel Wireless 8260                                                           | 6         | 3.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 6         | 3.17%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 6         | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 2.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5         | 2.65%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 2.65%   |
| Intel Wireless 3165                                                           | 5         | 2.65%   |
| Intel WiFi Link 5100                                                          | 5         | 2.65%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 4         | 2.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 2.12%   |
| Intel Wireless 3160                                                           | 4         | 2.12%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 4         | 2.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 3         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 3         | 1.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 3         | 1.59%   |
| Intel Wireless 7265                                                           | 3         | 1.59%   |
| Intel Wi-Fi 6 AX201                                                           | 3         | 1.59%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 1.59%   |
| Intel Centrino Advanced-N 6235                                                | 3         | 1.59%   |
| Intel Centrino Advanced-N 6200                                                | 3         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 3         | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 1.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 2         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.06%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 2         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.06%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 1.06%   |
| Intel Centrino Wireless-N 2230                                                | 2         | 1.06%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 1.06%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                            | 2         | 1.06%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 2         | 1.06%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 2         | 1.06%   |
| ZyXEL NWD-270N Wireless N-lite USB Adapter                                    | 1         | 0.53%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                           | 1         | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 0.53%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 0.53%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.53%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1         | 0.53%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1         | 0.53%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.53%   |
| Realtek 802.11ac NIC                                                          | 1         | 0.53%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.53%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]                   | 1         | 0.53%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.53%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]                        | 1         | 0.53%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.53%   |
| Intel Ultimate N WiFi Link 5300                                               | 1         | 0.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1         | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 1         | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 0.53%   |
| Intel Centrino Wireless-N 130                                                 | 1         | 0.53%   |
| Intel Centrino Wireless-N 105                                                 | 1         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 89        | 52.66%  |
| Intel                            | 33        | 19.53%  |
| Qualcomm Atheros                 | 13        | 7.69%   |
| Broadcom                         | 11        | 6.51%   |
| Marvell Technology Group         | 3         | 1.78%   |
| DisplayLink                      | 3         | 1.78%   |
| Broadcom Limited                 | 3         | 1.78%   |
| Xiaomi                           | 2         | 1.18%   |
| Huawei Technologies              | 2         | 1.18%   |
| ASIX Electronics                 | 2         | 1.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.59%   |
| Samsung Electronics              | 1         | 0.59%   |
| Qualcomm                         | 1         | 0.59%   |
| OPPO                             | 1         | 0.59%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.59%   |
| Nvidia                           | 1         | 0.59%   |
| MediaTek                         | 1         | 0.59%   |
| ICS Advent                       | 1         | 0.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62        | 36.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 12.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 2.35%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.18%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.18%   |
| Intel Ethernet Connection I218-V                                  | 2         | 1.18%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.18%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.18%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.59%   |
| Qualcomm SM8250-APOLLO _SN:B760817D                               | 1         | 0.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.59%   |
| OPPO SDM665-IDP _SN:6A6C23F9                                      | 1         | 0.59%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 0.59%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.59%   |
| MediaTek Titan                                                    | 1         | 0.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.59%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.59%   |
| Intel Ethernet controller                                         | 1         | 0.59%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.59%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.59%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.59%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 0.59%   |
| Huawei SPN-AL00                                                   | 1         | 0.59%   |
| Huawei E353/E3131                                                 | 1         | 0.59%   |
| DisplayLink StarTech.com Universal Dock                           | 1         | 0.59%   |
| DisplayLink dynadock U3.0                                         | 1         | 0.59%   |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.59%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.59%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.59%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.59%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.59%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 1         | 0.59%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 0.59%   |
| Broadcom Limited NetLink BCM57781 Gigabit Ethernet PCIe           | 1         | 0.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 180       | 52.94%  |
| Ethernet | 158       | 46.47%  |
| Modem    | 1         | 0.29%   |
| Unknown  | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 170       | 55.02%  |
| Ethernet | 138       | 44.66%  |
| Unknown  | 1         | 0.32%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 143       | 76.47%  |
| 1     | 41        | 21.93%  |
| 0     | 2         | 1.07%   |
| 3     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 131       | 69.68%  |
| Yes  | 57        | 30.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 41.89%  |
| Qualcomm Atheros Communications | 17        | 11.49%  |
| Realtek Semiconductor           | 14        | 9.46%   |
| Foxconn / Hon Hai               | 10        | 6.76%   |
| IMC Networks                    | 9         | 6.08%   |
| Lite-On Technology              | 8         | 5.41%   |
| Broadcom                        | 8         | 5.41%   |
| Apple                           | 6         | 4.05%   |
| Toshiba                         | 3         | 2.03%   |
| Ralink                          | 3         | 2.03%   |
| Dell                            | 3         | 2.03%   |
| Foxconn International           | 2         | 1.35%   |
| Cambridge Silicon Radio         | 2         | 1.35%   |
| Alps Electric                   | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 33        | 22.3%   |
| Intel Bluetooth wireless interface                                                  | 23        | 15.54%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 7.43%   |
| Realtek Bluetooth Radio                                                             | 8         | 5.41%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 4.05%   |
| Lite-On Bluetooth Device                                                            | 4         | 2.7%    |
| Intel AX200 Bluetooth                                                               | 4         | 2.7%    |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.7%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 2.7%    |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.03%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 2.03%   |
| IMC Networks Bluetooth Device                                                       | 3         | 2.03%   |
| Dell BCM20702A0                                                                     | 3         | 2.03%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.35%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 1.35%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.35%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 1.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.35%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.35%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.35%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.35%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.35%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.68%   |
| Toshiba BRCM Bluetooth Controller BCM2070                                           | 1         | 0.68%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.68%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.68%   |
| IMC Networks Bluetooth                                                              | 1         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.68%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.68%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.68%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.68%   |
| Broadcom Bluetooth                                                                  | 1         | 0.68%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.68%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.68%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.68%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 151       | 68.64%  |
| AMD                              | 38        | 17.27%  |
| Nvidia                           | 30        | 13.64%  |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 10.41%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 7.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 5.58%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 15        | 5.58%   |
| AMD FCH Azalia Controller                                                                         | 14        | 5.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 4.09%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 4.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 4.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 2.97%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 2.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.6%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.23%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 2.23%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.23%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.12%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.12%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.12%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.74%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.74%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.74%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.37%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.37%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.37%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.37%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.37%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.37%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.37%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia Audio device                                                                               | 1         | 0.37%   |
| Intel Jasper Lake HD Graphics SGPC                                                                | 1         | 0.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.37%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.37%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 1         | 0.37%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.37%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.37%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 1         | 0.37%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.37%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.37%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.37%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 29.79%  |
| SK Hynix            | 9         | 19.15%  |
| Micron Technology   | 8         | 17.02%  |
| A-DATA Technology   | 5         | 10.64%  |
| Unknown             | 3         | 6.38%   |
| Kingston            | 3         | 6.38%   |
| Unknown (ABCD)      | 1         | 2.13%   |
| Strontium           | 1         | 2.13%   |
| Ramaxel Technology  | 1         | 2.13%   |
| Nanya Technology    | 1         | 2.13%   |
| Crucial             | 1         | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 5.77%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 2         | 3.85%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s             | 2         | 3.85%   |
| Kingston RAM ACR16D3LS1KFG/4G 4096MB SODIMM DDR3 1600MT/s           | 2         | 3.85%   |
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s           | 2         | 3.85%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                           | 1         | 1.92%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                      | 1         | 1.92%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 1.92%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.92%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s                | 1         | 1.92%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.92%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.92%   |
| SK Hynix RAM HMT112S6BFR6C-G7 1024MB SODIMM DDR3 1067MT/s           | 1         | 1.92%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 1.92%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 1.92%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 1.92%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.92%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 1.92%   |
| Samsung RAM M471B5773EB0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.92%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s            | 1         | 1.92%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 1.92%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.92%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.92%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s            | 1         | 1.92%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s      | 1         | 1.92%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.92%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.92%   |
| Nanya RAM NT1GT64U8HB0BN-3C 1024MB SODIMM DDR 667MT/s               | 1         | 1.92%   |
| Micron RAM MT52L512M32D2PF-10 4096MB Row Of Chips LPDDR3 1867MT/s   | 1         | 1.92%   |
| Micron RAM Module 2GB SODIMM DDR2 800MT/s                           | 1         | 1.92%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 1         | 1.92%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 1         | 1.92%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| Kingston RAM K821PJ-MID 16384MB SODIMM DDR4 2400MT/s                | 1         | 1.92%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s              | 1         | 1.92%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2667MT/s                       | 1         | 1.92%   |
| A-DATA RAM DOVF1B163BE 2048MB SODIMM DDR 800MT/s                    | 1         | 1.92%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4096MB SODIMM DDR4 2400MT/s             | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 21        | 50%     |
| DDR3   | 11        | 26.19%  |
| LPDDR4 | 3         | 7.14%   |
| DDR2   | 3         | 7.14%   |
| SDRAM  | 2         | 4.76%   |
| LPDDR3 | 2         | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 87.5%   |
| Row Of Chips | 5         | 12.5%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 19        | 41.3%   |
| 8192  | 16        | 34.78%  |
| 2048  | 8         | 17.39%  |
| 1024  | 2         | 4.35%   |
| 16384 | 1         | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 10        | 21.74%  |
| 2667  | 8         | 17.39%  |
| 3200  | 6         | 13.04%  |
| 2400  | 5         | 10.87%  |
| 3266  | 3         | 6.52%   |
| 4199  | 2         | 4.35%   |
| 2133  | 2         | 4.35%   |
| 1334  | 2         | 4.35%   |
| 800   | 2         | 4.35%   |
| 667   | 2         | 4.35%   |
| 4267  | 1         | 2.17%   |
| 1867  | 1         | 2.17%   |
| 1333  | 1         | 2.17%   |
| 1067  | 1         | 2.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 32        | 19.51%  |
| Realtek Semiconductor                  | 20        | 12.2%   |
| IMC Networks                           | 19        | 11.59%  |
| Sunplus Innovation Technology          | 13        | 7.93%   |
| Microdia                               | 12        | 7.32%   |
| Acer                                   | 12        | 7.32%   |
| Quanta                                 | 10        | 6.1%    |
| Cheng Uei Precision Industry (Foxlink) | 10        | 6.1%    |
| Suyin                                  | 7         | 4.27%   |
| Lite-On Technology                     | 6         | 3.66%   |
| Syntek                                 | 4         | 2.44%   |
| Ricoh                                  | 2         | 1.22%   |
| Primax Electronics                     | 2         | 1.22%   |
| Apple                                  | 2         | 1.22%   |
| YGTek                                  | 1         | 0.61%   |
| Sunplus Technology                     | 1         | 0.61%   |
| Silicon Motion                         | 1         | 0.61%   |
| Samsung Electronics                    | 1         | 0.61%   |
| OmniVision Technologies                | 1         | 0.61%   |
| KYE Systems (Mouse Systems)            | 1         | 0.61%   |
| Importek                               | 1         | 0.61%   |
| Genesys Logic                          | 1         | 0.61%   |
| Generalplus Technology                 | 1         | 0.61%   |
| GEMBIRD                                | 1         | 0.61%   |
| DJKCVA1BIDQ8CL                         | 1         | 0.61%   |
| ALi                                    | 1         | 0.61%   |
| Alcor Micro                            | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 7         | 4.27%   |
| Realtek Integrated_Webcam_HD                        | 6         | 3.66%   |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 3.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 3.05%   |
| Acer Lenovo EasyCamera                              | 5         | 3.05%   |
| Realtek USB Camera                                  | 4         | 2.44%   |
| Realtek Integrated Webcam                           | 4         | 2.44%   |
| Microdia Integrated_Webcam_HD                       | 4         | 2.44%   |
| Microdia Integrated Webcam                          | 4         | 2.44%   |
| Chicony HD WebCam                                   | 4         | 2.44%   |
| Syntek Integrated Camera                            | 3         | 1.83%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 1.83%   |
| Quanta HP Wide Vision HD Camera                     | 3         | 1.83%   |
| IMC Networks Integrated Camera                      | 3         | 1.83%   |
| Chicony VGA Webcam                                  | 3         | 1.83%   |
| Chicony Integrated Camera                           | 3         | 1.83%   |
| Chicony HP Truevision HD                            | 3         | 1.83%   |
| Suyin HP Truevision HD                              | 2         | 1.22%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 1.22%   |
| Sunplus Integrated Webcam                           | 2         | 1.22%   |
| Sunplus HD WebCam                                   | 2         | 1.22%   |
| Realtek Lenovo EasyCamera                           | 2         | 1.22%   |
| Realtek HD WebCam                                   | 2         | 1.22%   |
| Quanta VGA WebCam                                   | 2         | 1.22%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.22%   |
| Quanta HD User Facing                               | 2         | 1.22%   |
| Lite-On HP HD Camera                                | 2         | 1.22%   |
| Chicony EasyCamera                                  | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.22%   |
| Acer Integrated Camera                              | 2         | 1.22%   |
| YGTek webcam                                        | 1         | 0.61%   |
| Syntek USB Camera Device                            | 1         | 0.61%   |
| Suyin WebCam                                        | 1         | 0.61%   |
| Suyin Acer HD Crystal Eye webcam                    | 1         | 0.61%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.61%   |
| Sunplus 1.3M HD WebCam                              | 1         | 0.61%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.61%   |
| Sunplus Laptop_Integrated_Webcam_1.3M               | 1         | 0.61%   |
| Sunplus HP Wide Vision HD                           | 1         | 0.61%   |
| Sunplus HD User Facing                              | 1         | 0.61%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 0.61%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 0.61%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 0.61%   |
| Ricoh Visual Communication Camera VGP-VCC9 [R5U870] | 1         | 0.61%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.61%   |
| Realtek LG Webcam                                   | 1         | 0.61%   |
| Realtek 2SF001                                      | 1         | 0.61%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 0.61%   |
| Primax Villem                                       | 1         | 0.61%   |
| Primax HP HD Webcam [Fixed]                         | 1         | 0.61%   |
| OmniVision OV2640 Webcam                            | 1         | 0.61%   |
| Microdia USB 2.0 Camera                             | 1         | 0.61%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.61%   |
| Microdia Integrated Webcam HD                       | 1         | 0.61%   |
| Microdia Integrated HD Webcam                       | 1         | 0.61%   |
| Lite-On Integrated Camera                           | 1         | 0.61%   |
| Lite-On HP Wide Vision HD Camera                    | 1         | 0.61%   |
| Lite-On HP Wide Vision FHD Camera                   | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 50%     |
| Upek                       | 6         | 17.65%  |
| Shenzhen Goodix Technology | 4         | 11.76%  |
| LighTuning Technology      | 2         | 5.88%   |
| AuthenTec                  | 2         | 5.88%   |
| Synaptics                  | 1         | 2.94%   |
| STMicroelectronics         | 1         | 2.94%   |
| Focal-systems.Corp         | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 14.71%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 8.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 8.82%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 5.88%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 5.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.94%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.94%   |
| Validity Sensors VFS491                                                    | 1         | 2.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.94%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 2.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.94%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.94%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 2.94%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 2.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.94%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 2.94%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.94%   |
| LighTuning Fingerprint Reader                                              | 1         | 2.94%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.94%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.94%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.94%   |
| AuthenTec AES1600                                                          | 1         | 2.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 53.85%  |
| Alcor Micro | 3         | 23.08%  |
| Lenovo      | 2         | 15.38%  |
| O2 Micro    | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 23.08%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 15.38%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 7.69%   |
| Broadcom 5880                                                                | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 120       | 63.49%  |
| 1     | 52        | 27.51%  |
| 2     | 16        | 8.47%   |
| 3     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 34        | 40%     |
| Graphics card         | 16        | 18.82%  |
| Net/wireless          | 11        | 12.94%  |
| Chipcard              | 11        | 12.94%  |
| Multimedia controller | 5         | 5.88%   |
| Bluetooth             | 3         | 3.53%   |
| Storage               | 2         | 2.35%   |
| Net/ethernet          | 1         | 1.18%   |
| Flash memory          | 1         | 1.18%   |
| Dvb card              | 1         | 1.18%   |

