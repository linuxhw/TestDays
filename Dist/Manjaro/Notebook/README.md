Manjaro - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 5669

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1d5206dc94](https://linux-hardware.org/?probe=1d5206dc94) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [79cc445925](https://linux-hardware.org/?probe=79cc445925) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [b9d1b6d44a](https://linux-hardware.org/?probe=b9d1b6d44a) | Aug 12, 2023 |
| HP            | Laptop 14-dq1xxx            | [6f5a32d65f](https://linux-hardware.org/?probe=6f5a32d65f) | Aug 11, 2023 |
| Acer          | TMP255-M                    | [0b1adaea4e](https://linux-hardware.org/?probe=0b1adaea4e) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | [49a3480efb](https://linux-hardware.org/?probe=49a3480efb) | Aug 11, 2023 |
| Positivo      | Presley 3                   | [16ddbd1a75](https://linux-hardware.org/?probe=16ddbd1a75) | Aug 10, 2023 |
| Positivo      | Presley 3                   | [9edde2ea30](https://linux-hardware.org/?probe=9edde2ea30) | Aug 09, 2023 |
| Chuwi         | GemiBook Pro                | [3702186068](https://linux-hardware.org/?probe=3702186068) | Aug 08, 2023 |
| Lenovo        | ThinkPad T440 20B7S4NV07    | [af7992a11e](https://linux-hardware.org/?probe=af7992a11e) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | [77f61b77f5](https://linux-hardware.org/?probe=77f61b77f5) | Aug 08, 2023 |
| Lenovo        | ThinkPad X230 2324BV7       | [e1f092d38b](https://linux-hardware.org/?probe=e1f092d38b) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | [fa4f74161f](https://linux-hardware.org/?probe=fa4f74161f) | Aug 08, 2023 |
| ASUSTek       | N550LF                      | [57f7da9570](https://linux-hardware.org/?probe=57f7da9570) | Aug 08, 2023 |
| Jumper        | QCYL-200                    | [24da6190dc](https://linux-hardware.org/?probe=24da6190dc) | Aug 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b73a01acaf](https://linux-hardware.org/?probe=b73a01acaf) | Aug 07, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [9094c29548](https://linux-hardware.org/?probe=9094c29548) | Aug 07, 2023 |
| Dell          | Vostro 3480                 | [78fbe42595](https://linux-hardware.org/?probe=78fbe42595) | Aug 07, 2023 |
| Acer          | Aspire E5-553G              | [f7845429c8](https://linux-hardware.org/?probe=f7845429c8) | Aug 07, 2023 |
| Dell          | Latitude 5480               | [f3f7a29ca0](https://linux-hardware.org/?probe=f3f7a29ca0) | Aug 07, 2023 |
| Dell          | Inspiron 15 3525            | [36a20bb009](https://linux-hardware.org/?probe=36a20bb009) | Aug 07, 2023 |
| HUAWEI        | KPRC-WX0                    | [f84c568d4b](https://linux-hardware.org/?probe=f84c568d4b) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f2d72fe710](https://linux-hardware.org/?probe=f2d72fe710) | Aug 07, 2023 |
| Acer          | Aspire A514-54              | [e9dfd6bbb6](https://linux-hardware.org/?probe=e9dfd6bbb6) | Aug 06, 2023 |
| Acer          | Aspire A514-54              | [0a7dc12f31](https://linux-hardware.org/?probe=0a7dc12f31) | Aug 06, 2023 |
| HP            | 250 G6 Notebook PC          | [c130dece41](https://linux-hardware.org/?probe=c130dece41) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | [a58ca66b2f](https://linux-hardware.org/?probe=a58ca66b2f) | Aug 06, 2023 |
| Dell          | XPS 15 7590                 | [6a53759849](https://linux-hardware.org/?probe=6a53759849) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | [52bf9ffa35](https://linux-hardware.org/?probe=52bf9ffa35) | Aug 06, 2023 |
| Acer          | Aspire A317-53              | [5bb0feab0c](https://linux-hardware.org/?probe=5bb0feab0c) | Aug 06, 2023 |
| Lenovo        | B330-15IKBR 81M1            | [f03fa524d7](https://linux-hardware.org/?probe=f03fa524d7) | Aug 05, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [5e28b5b07a](https://linux-hardware.org/?probe=5e28b5b07a) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [6fd7ffb05b](https://linux-hardware.org/?probe=6fd7ffb05b) | Aug 04, 2023 |
| SANTECH       | NL5xNU                      | [68d1f62251](https://linux-hardware.org/?probe=68d1f62251) | Aug 04, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [0f5b976e39](https://linux-hardware.org/?probe=0f5b976e39) | Aug 02, 2023 |
| Dell          | Inspiron 5566               | [c4e404738e](https://linux-hardware.org/?probe=c4e404738e) | Aug 01, 2023 |
| Apple         | MacBookPro8,1               | [56e2fa207e](https://linux-hardware.org/?probe=56e2fa207e) | Aug 01, 2023 |
| Lenovo        | B330-15IKBR 81M1            | [1f69ed5c1e](https://linux-hardware.org/?probe=1f69ed5c1e) | Aug 01, 2023 |
| TUXEDO        | N7x0WU                      | [05c525a9a7](https://linux-hardware.org/?probe=05c525a9a7) | Jul 31, 2023 |
| HP            | ProBook 4740s               | [d0aae87145](https://linux-hardware.org/?probe=d0aae87145) | Jul 31, 2023 |
| HP            | ProBook 4740s               | [985ee4b495](https://linux-hardware.org/?probe=985ee4b495) | Jul 30, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [1fe8eab1c6](https://linux-hardware.org/?probe=1fe8eab1c6) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | [c8391bd952](https://linux-hardware.org/?probe=c8391bd952) | Jul 29, 2023 |
| HP            | Laptop 17-cn0xxx            | [d23aa8f750](https://linux-hardware.org/?probe=d23aa8f750) | Jul 29, 2023 |
| Dell          | XPS 17 9720                 | [1006fe2c7b](https://linux-hardware.org/?probe=1006fe2c7b) | Jul 29, 2023 |
| Dell          | Inspiron N4050              | [701402e2a7](https://linux-hardware.org/?probe=701402e2a7) | Jul 29, 2023 |
| Dell          | XPS 15 9500                 | [151b7d8d31](https://linux-hardware.org/?probe=151b7d8d31) | Jul 29, 2023 |
| Lenovo        | ThinkPad T420 4180C31       | [7fafc1656d](https://linux-hardware.org/?probe=7fafc1656d) | Jul 28, 2023 |
| Lenovo        | ThinkPad E575 20H8S02W00    | [afde3ea804](https://linux-hardware.org/?probe=afde3ea804) | Jul 28, 2023 |
| HP            | EliteBook 2540p             | [cedff6ca6f](https://linux-hardware.org/?probe=cedff6ca6f) | Jul 28, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [c51105da6a](https://linux-hardware.org/?probe=c51105da6a) | Jul 28, 2023 |
| Valve         | Jupiter                     | [b32778a4bd](https://linux-hardware.org/?probe=b32778a4bd) | Jul 28, 2023 |
| Google        | Blooglet                    | [d8c14e29b6](https://linux-hardware.org/?probe=d8c14e29b6) | Jul 27, 2023 |
| Acer          | TMP255-M                    | [25d376a674](https://linux-hardware.org/?probe=25d376a674) | Jul 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b5b201f80a](https://linux-hardware.org/?probe=b5b201f80a) | Jul 26, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [784b86f367](https://linux-hardware.org/?probe=784b86f367) | Jul 25, 2023 |
| MSI           | Prestige 14Evo A12M         | [4872d1fdf6](https://linux-hardware.org/?probe=4872d1fdf6) | Jul 25, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [9acc2dda36](https://linux-hardware.org/?probe=9acc2dda36) | Jul 25, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [346055ca33](https://linux-hardware.org/?probe=346055ca33) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [5262229deb](https://linux-hardware.org/?probe=5262229deb) | Jul 25, 2023 |
| Acer          | TMP255-M                    | [c4bfc82a98](https://linux-hardware.org/?probe=c4bfc82a98) | Jul 24, 2023 |
| Acer          | TMP255-M                    | [7a57ee89af](https://linux-hardware.org/?probe=7a57ee89af) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [7a6a20b8ed](https://linux-hardware.org/?probe=7a6a20b8ed) | Jul 23, 2023 |
| Medion        | E4251 MD61435               | [4cd0b97344](https://linux-hardware.org/?probe=4cd0b97344) | Jul 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [46218bae31](https://linux-hardware.org/?probe=46218bae31) | Jul 23, 2023 |
| Dell          | Vostro 3578                 | [bd32828bf5](https://linux-hardware.org/?probe=bd32828bf5) | Jul 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [7a3abd2e4d](https://linux-hardware.org/?probe=7a3abd2e4d) | Jul 22, 2023 |
| HP            | ZBook 15 G2                 | [1c164d4bc9](https://linux-hardware.org/?probe=1c164d4bc9) | Jul 21, 2023 |
| ASUSTek       | GL702VM                     | [f2a5e69f00](https://linux-hardware.org/?probe=f2a5e69f00) | Jul 20, 2023 |
| Acer          | Predator PH315-53           | [3d0b2577a1](https://linux-hardware.org/?probe=3d0b2577a1) | Jul 18, 2023 |
| HONOR         | BBR-WAX9                    | [b098dc2f61](https://linux-hardware.org/?probe=b098dc2f61) | Jul 17, 2023 |
| HP            | Laptop 17-cn0xxx            | [e2973a88aa](https://linux-hardware.org/?probe=e2973a88aa) | Jul 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b0c8aaef19](https://linux-hardware.org/?probe=b0c8aaef19) | Jul 16, 2023 |
| HP            | ZBook 15 G4                 | [ad6ff2b754](https://linux-hardware.org/?probe=ad6ff2b754) | Jul 16, 2023 |
| ASUSTek       | X75A1                       | [745ef2a79f](https://linux-hardware.org/?probe=745ef2a79f) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | [d06ca4b9c2](https://linux-hardware.org/?probe=d06ca4b9c2) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | [103e7e5196](https://linux-hardware.org/?probe=103e7e5196) | Jul 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [5e43c9d869](https://linux-hardware.org/?probe=5e43c9d869) | Jul 15, 2023 |
| Acer          | Aspire A515-41G             | [a9cb1108f6](https://linux-hardware.org/?probe=a9cb1108f6) | Jul 15, 2023 |
| Acer          | Aspire A515-43              | [6b86cc4c89](https://linux-hardware.org/?probe=6b86cc4c89) | Jul 15, 2023 |
| HP            | Laptop 17-cn0xxx            | [479e8276b4](https://linux-hardware.org/?probe=479e8276b4) | Jul 15, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [567736ec02](https://linux-hardware.org/?probe=567736ec02) | Jul 14, 2023 |
| Acer          | Nitro AN515-55              | [c9a21bf55e](https://linux-hardware.org/?probe=c9a21bf55e) | Jul 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [be15faa71b](https://linux-hardware.org/?probe=be15faa71b) | Jul 14, 2023 |
| HP            | EliteBook 840 14 inch G9... | [4b9cba03ac](https://linux-hardware.org/?probe=4b9cba03ac) | Jul 13, 2023 |
| Acer          | Aspire E5-774G              | [7f06f99146](https://linux-hardware.org/?probe=7f06f99146) | Jul 13, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [e69bd50c8e](https://linux-hardware.org/?probe=e69bd50c8e) | Jul 13, 2023 |
| ASUSTek       | X456UV                      | [b0a9e3905f](https://linux-hardware.org/?probe=b0a9e3905f) | Jul 13, 2023 |
| Dell          | Latitude E6400              | [c8cf9bcf47](https://linux-hardware.org/?probe=c8cf9bcf47) | Jul 13, 2023 |
| HP            | Compaq Presario CQ40        | [fbc602a7b6](https://linux-hardware.org/?probe=fbc602a7b6) | Jul 12, 2023 |
| Dell          | Inspiron 5737               | [fa1cb6ffb8](https://linux-hardware.org/?probe=fa1cb6ffb8) | Jul 12, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [ef1f607a84](https://linux-hardware.org/?probe=ef1f607a84) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | [cb6e26bcb4](https://linux-hardware.org/?probe=cb6e26bcb4) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | [37049406c3](https://linux-hardware.org/?probe=37049406c3) | Jul 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [8b9677cc2a](https://linux-hardware.org/?probe=8b9677cc2a) | Jul 10, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [acdd4ea952](https://linux-hardware.org/?probe=acdd4ea952) | Jul 10, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [59b334f01a](https://linux-hardware.org/?probe=59b334f01a) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | [8f40997f5f](https://linux-hardware.org/?probe=8f40997f5f) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | [7d19e6a8f5](https://linux-hardware.org/?probe=7d19e6a8f5) | Jul 10, 2023 |
| Dell          | Latitude 3490               | [6fcb4ace67](https://linux-hardware.org/?probe=6fcb4ace67) | Jul 10, 2023 |
| Acer          | Nitro AN515-43              | [b463aaca78](https://linux-hardware.org/?probe=b463aaca78) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK LH532              | [3cad86057a](https://linux-hardware.org/?probe=3cad86057a) | Jul 09, 2023 |
| HUAWEI        | KLVL-WXX9                   | [e853f79dd4](https://linux-hardware.org/?probe=e853f79dd4) | Jul 09, 2023 |
| Acer          | TravelMate P2510-G2-M       | [c96a405528](https://linux-hardware.org/?probe=c96a405528) | Jul 09, 2023 |
| Acer          | Aspire A515-56              | [9dee0fcab9](https://linux-hardware.org/?probe=9dee0fcab9) | Jul 09, 2023 |
| Fujitsu       | LIFEBOOK S752               | [a2bd9b682d](https://linux-hardware.org/?probe=a2bd9b682d) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [e87ea192ea](https://linux-hardware.org/?probe=e87ea192ea) | Jul 08, 2023 |
| ASUSTek       | UX550VE                     | [b782a00935](https://linux-hardware.org/?probe=b782a00935) | Jul 08, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | [59782374c4](https://linux-hardware.org/?probe=59782374c4) | Jul 07, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [4e47f48ca8](https://linux-hardware.org/?probe=4e47f48ca8) | Jul 07, 2023 |
| Framework     | Laptop                      | [ea4c4585d0](https://linux-hardware.org/?probe=ea4c4585d0) | Jul 06, 2023 |
| HP            | 255 G7 Notebook PC          | [23a6105e01](https://linux-hardware.org/?probe=23a6105e01) | Jul 06, 2023 |
| ASUSTek       | K53SV                       | [851a3a00cf](https://linux-hardware.org/?probe=851a3a00cf) | Jul 05, 2023 |
| Dell          | Latitude 3490               | [a730cef547](https://linux-hardware.org/?probe=a730cef547) | Jul 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f3828ea18b](https://linux-hardware.org/?probe=f3828ea18b) | Jul 04, 2023 |
| MSI           | FX603                       | [8b0664bd4e](https://linux-hardware.org/?probe=8b0664bd4e) | Jul 04, 2023 |
| Packard Be... | EasyNote MH36               | [87873c1e0e](https://linux-hardware.org/?probe=87873c1e0e) | Jul 03, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [cc0464c9a4](https://linux-hardware.org/?probe=cc0464c9a4) | Jul 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [6686fca24b](https://linux-hardware.org/?probe=6686fca24b) | Jul 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [ccb318cd32](https://linux-hardware.org/?probe=ccb318cd32) | Jul 03, 2023 |
| HP            | EliteBook 8460p             | [40b92fc7ba](https://linux-hardware.org/?probe=40b92fc7ba) | Jul 02, 2023 |
| Dell          | Inspiron 5566               | [c0fa0d6c73](https://linux-hardware.org/?probe=c0fa0d6c73) | Jul 02, 2023 |
| Teclast       | F15Plus 2                   | [29b2c807e6](https://linux-hardware.org/?probe=29b2c807e6) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | [f182eda3d3](https://linux-hardware.org/?probe=f182eda3d3) | Jul 01, 2023 |
| Teclast       | F15Plus 2                   | [4593b411f0](https://linux-hardware.org/?probe=4593b411f0) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [559c10480e](https://linux-hardware.org/?probe=559c10480e) | Jun 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e555922bb2](https://linux-hardware.org/?probe=e555922bb2) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | [954ac9a8e4](https://linux-hardware.org/?probe=954ac9a8e4) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | [9d40263129](https://linux-hardware.org/?probe=9d40263129) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | [4e47d108a0](https://linux-hardware.org/?probe=4e47d108a0) | Jun 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d058f48980](https://linux-hardware.org/?probe=d058f48980) | Jun 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [1c349accca](https://linux-hardware.org/?probe=1c349accca) | Jun 29, 2023 |
| Alienware     | 17 R4                       | [e7f3110f1f](https://linux-hardware.org/?probe=e7f3110f1f) | Jun 29, 2023 |
| Google        | Reef                        | [221e64e148](https://linux-hardware.org/?probe=221e64e148) | Jun 29, 2023 |
| Acer          | Aspire VN7-593G             | [2302cbfba7](https://linux-hardware.org/?probe=2302cbfba7) | Jun 28, 2023 |
| Chuwi         | GemiBook                    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [2debd02f0c](https://linux-hardware.org/?probe=2debd02f0c) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [3b775b8099](https://linux-hardware.org/?probe=3b775b8099) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | [5e6365efcf](https://linux-hardware.org/?probe=5e6365efcf) | Jun 27, 2023 |
| Dell          | Inspiron 3442               | [6e179dbfb0](https://linux-hardware.org/?probe=6e179dbfb0) | Jun 26, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [9dbf9f98a6](https://linux-hardware.org/?probe=9dbf9f98a6) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [4518a77b73](https://linux-hardware.org/?probe=4518a77b73) | Jun 26, 2023 |
| Acer          | Nitro AN517-54              | [9af91d0ced](https://linux-hardware.org/?probe=9af91d0ced) | Jun 26, 2023 |
| HP            | EliteBook 8740w             | [e460d017ec](https://linux-hardware.org/?probe=e460d017ec) | Jun 25, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [df9521a37d](https://linux-hardware.org/?probe=df9521a37d) | Jun 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | [3e08f1644a](https://linux-hardware.org/?probe=3e08f1644a) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | [574653afac](https://linux-hardware.org/?probe=574653afac) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | [fa6b09cc1d](https://linux-hardware.org/?probe=fa6b09cc1d) | Jun 23, 2023 |
| Dell          | XPS 13 9370                 | [7ba7b1dc58](https://linux-hardware.org/?probe=7ba7b1dc58) | Jun 22, 2023 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [38c278b214](https://linux-hardware.org/?probe=38c278b214) | Jun 22, 2023 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [816c32de98](https://linux-hardware.org/?probe=816c32de98) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | [f1e506486c](https://linux-hardware.org/?probe=f1e506486c) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [8e74890c4f](https://linux-hardware.org/?probe=8e74890c4f) | Jun 19, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [98f052ad58](https://linux-hardware.org/?probe=98f052ad58) | Jun 19, 2023 |
| Framework     | Laptop                      | [7d010a367e](https://linux-hardware.org/?probe=7d010a367e) | Jun 19, 2023 |
| MSI           | GT70 2OC/2OD                | [adee2af879](https://linux-hardware.org/?probe=adee2af879) | Jun 19, 2023 |
| Dell          | Inspiron 5566               | [be5a148c53](https://linux-hardware.org/?probe=be5a148c53) | Jun 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | [591e97398c](https://linux-hardware.org/?probe=591e97398c) | Jun 18, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [c454cb2cf0](https://linux-hardware.org/?probe=c454cb2cf0) | Jun 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | [0875b8b413](https://linux-hardware.org/?probe=0875b8b413) | Jun 18, 2023 |
| HP            | Laptop 15-dy1xxx            | [93e28671fa](https://linux-hardware.org/?probe=93e28671fa) | Jun 18, 2023 |
| Samsung       | 300E5K/300E5Q               | [a281272278](https://linux-hardware.org/?probe=a281272278) | Jun 17, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [97a4ed6110](https://linux-hardware.org/?probe=97a4ed6110) | Jun 17, 2023 |
| Dell          | Latitude 5491               | [0673ab5ff5](https://linux-hardware.org/?probe=0673ab5ff5) | Jun 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [5b54def91d](https://linux-hardware.org/?probe=5b54def91d) | Jun 16, 2023 |
| Dell          | Latitude E5400              | [f5d066d8fc](https://linux-hardware.org/?probe=f5d066d8fc) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | [39b295867e](https://linux-hardware.org/?probe=39b295867e) | Jun 15, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [b1e56a3c92](https://linux-hardware.org/?probe=b1e56a3c92) | Jun 15, 2023 |
| Unknown       | Unknown                     | [3a944bbbd5](https://linux-hardware.org/?probe=3a944bbbd5) | Jun 15, 2023 |
| Unknown       | Unknown                     | [581aba0aa2](https://linux-hardware.org/?probe=581aba0aa2) | Jun 15, 2023 |
| HONOR         | NMH-WCX9                    | [8515730b56](https://linux-hardware.org/?probe=8515730b56) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [3b552a7f4a](https://linux-hardware.org/?probe=3b552a7f4a) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | [8f84dca464](https://linux-hardware.org/?probe=8f84dca464) | Jun 14, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [2eed8e0355](https://linux-hardware.org/?probe=2eed8e0355) | Jun 13, 2023 |
| Google        | Atlas                       | [ecd53b626a](https://linux-hardware.org/?probe=ecd53b626a) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [542a1217bd](https://linux-hardware.org/?probe=542a1217bd) | Jun 13, 2023 |
| ASUSTek       | UX530UQ                     | [c952ec8390](https://linux-hardware.org/?probe=c952ec8390) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [0b717c2785](https://linux-hardware.org/?probe=0b717c2785) | Jun 13, 2023 |
| Schenker      | VIA 15 Pro                  | [311a7e116c](https://linux-hardware.org/?probe=311a7e116c) | Jun 13, 2023 |
| Acer          | Aspire A517-53G             | [a4c87fb2bc](https://linux-hardware.org/?probe=a4c87fb2bc) | Jun 12, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [ceae8212bf](https://linux-hardware.org/?probe=ceae8212bf) | Jun 12, 2023 |
| Acer          | Aspire A517-53G             | [2069778d1f](https://linux-hardware.org/?probe=2069778d1f) | Jun 12, 2023 |
| Acer          | Aspire A315-510P            | [705ad3c316](https://linux-hardware.org/?probe=705ad3c316) | Jun 12, 2023 |
| MSI           | Prestige 14Evo A12M         | [3e121c01dd](https://linux-hardware.org/?probe=3e121c01dd) | Jun 12, 2023 |
| Emdoor        | AG958                       | [1688cc07b6](https://linux-hardware.org/?probe=1688cc07b6) | Jun 11, 2023 |
| Dell          | Latitude 5580               | [1e37ff326f](https://linux-hardware.org/?probe=1e37ff326f) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [0d419f2c9d](https://linux-hardware.org/?probe=0d419f2c9d) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [afc5d143fe](https://linux-hardware.org/?probe=afc5d143fe) | Jun 11, 2023 |
| Acer          | Aspire A317-33              | [f62e645bd3](https://linux-hardware.org/?probe=f62e645bd3) | Jun 11, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9747487f82](https://linux-hardware.org/?probe=9747487f82) | Jun 11, 2023 |
| HP            | ProBook 470 G0              | [d3fdf73c3e](https://linux-hardware.org/?probe=d3fdf73c3e) | Jun 10, 2023 |
| MSI           | GS60 6QE                    | [e04ff9df40](https://linux-hardware.org/?probe=e04ff9df40) | Jun 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fa84ae9906](https://linux-hardware.org/?probe=fa84ae9906) | Jun 10, 2023 |
| ASUSTek       | UX530UQ                     | [71d0ddd2f0](https://linux-hardware.org/?probe=71d0ddd2f0) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| HP            | 240 G6 Notebook PC          | [f7470e08b0](https://linux-hardware.org/?probe=f7470e08b0) | Jun 08, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [bb571d888d](https://linux-hardware.org/?probe=bb571d888d) | Jun 08, 2023 |
| Dell          | XPS 17 9730                 | [5be9db17d1](https://linux-hardware.org/?probe=5be9db17d1) | Jun 08, 2023 |
| WOOKING       | X16                         | [aa543651fc](https://linux-hardware.org/?probe=aa543651fc) | Jun 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| Google        | Chell                       | [cace26f9f9](https://linux-hardware.org/?probe=cace26f9f9) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | [cbb39d8d29](https://linux-hardware.org/?probe=cbb39d8d29) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | [47fd407976](https://linux-hardware.org/?probe=47fd407976) | Jun 07, 2023 |
| Acer          | Aspire A314-36M             | [7cab0d1591](https://linux-hardware.org/?probe=7cab0d1591) | Jun 06, 2023 |
| Dell          | Latitude 5530               | [44aa9db289](https://linux-hardware.org/?probe=44aa9db289) | Jun 06, 2023 |
| HONOR         | HYM-WXX                     | [964cd10c8e](https://linux-hardware.org/?probe=964cd10c8e) | Jun 05, 2023 |
| Dell          | Latitude 3340               | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [13f3f67373](https://linux-hardware.org/?probe=13f3f67373) | Jun 04, 2023 |
| MSI           | GS60 6QE                    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| HONOR         | HGF-WX6                     | [13d0d7b145](https://linux-hardware.org/?probe=13d0d7b145) | Jun 03, 2023 |
| Dell          | XPS 15 9530                 | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [359d31bb8c](https://linux-hardware.org/?probe=359d31bb8c) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b34bb8b33a](https://linux-hardware.org/?probe=b34bb8b33a) | Jun 02, 2023 |
| MSI           | U200                        | [a217267eb0](https://linux-hardware.org/?probe=a217267eb0) | Jun 01, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [d25f4736b7](https://linux-hardware.org/?probe=d25f4736b7) | Jun 01, 2023 |
| Apple         | MacBookPro11,1              | [fd232702db](https://linux-hardware.org/?probe=fd232702db) | Jun 01, 2023 |
| Acer          | Aspire 3830TG               | [abd7d9a412](https://linux-hardware.org/?probe=abd7d9a412) | May 31, 2023 |
| Dell          | Precision 3550              | [bddf57400b](https://linux-hardware.org/?probe=bddf57400b) | May 31, 2023 |
| Dell          | System Vostro 3750          | [f77ea94512](https://linux-hardware.org/?probe=f77ea94512) | May 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [a5ebbfe1ef](https://linux-hardware.org/?probe=a5ebbfe1ef) | May 31, 2023 |
| HP            | Pavilion dv4                | [75797b5ec9](https://linux-hardware.org/?probe=75797b5ec9) | May 31, 2023 |
| Acer          | Aspire A315-59              | [3f08f70d3a](https://linux-hardware.org/?probe=3f08f70d3a) | May 31, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [8092b65afc](https://linux-hardware.org/?probe=8092b65afc) | May 31, 2023 |
| HP            | Laptop 15-ef2xxx            | [2139621391](https://linux-hardware.org/?probe=2139621391) | May 31, 2023 |
| HP            | Laptop 15-gw0xxx            | [ebc3d97429](https://linux-hardware.org/?probe=ebc3d97429) | May 30, 2023 |
| HP            | Laptop 15-gw0xxx            | [97382e45f8](https://linux-hardware.org/?probe=97382e45f8) | May 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [ac2f40b972](https://linux-hardware.org/?probe=ac2f40b972) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [f45bc9a282](https://linux-hardware.org/?probe=f45bc9a282) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| Dell          | Vostro 1015                 | [ebb5445720](https://linux-hardware.org/?probe=ebb5445720) | May 29, 2023 |
| Apple         | MacBookPro8,1               | [d8aa236e2d](https://linux-hardware.org/?probe=d8aa236e2d) | May 28, 2023 |
| Lenovo        | ThinkPad X230 2325SV7       | [6affd0b8ee](https://linux-hardware.org/?probe=6affd0b8ee) | May 28, 2023 |
| HP            | ProBook 6560b               | [972d01f49f](https://linux-hardware.org/?probe=972d01f49f) | May 28, 2023 |
| HP            | ProBook 6560b               | [9fd712c62d](https://linux-hardware.org/?probe=9fd712c62d) | May 28, 2023 |
| Unknown       | Unknown                     | [b294c91e3a](https://linux-hardware.org/?probe=b294c91e3a) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | [fb534d212e](https://linux-hardware.org/?probe=fb534d212e) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | [6b753016ff](https://linux-hardware.org/?probe=6b753016ff) | May 28, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| Dell          | Vostro 1015                 | [5098185f54](https://linux-hardware.org/?probe=5098185f54) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1fea1a6529](https://linux-hardware.org/?probe=1fea1a6529) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [a03284052b](https://linux-hardware.org/?probe=a03284052b) | May 24, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [f9103674dc](https://linux-hardware.org/?probe=f9103674dc) | May 22, 2023 |
| HP            | EliteBook 2570p             | [60ec2d6e04](https://linux-hardware.org/?probe=60ec2d6e04) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [19416d3973](https://linux-hardware.org/?probe=19416d3973) | May 21, 2023 |
| Getac         | V110G3                      | [4a80145aac](https://linux-hardware.org/?probe=4a80145aac) | May 21, 2023 |
| HP            | Laptop 17-cn2xxx            | [953734fc80](https://linux-hardware.org/?probe=953734fc80) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| Getac         | V110G3                      | [1b04290d0e](https://linux-hardware.org/?probe=1b04290d0e) | May 19, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| ASUSTek       | ROG Strix G733CX_G743CX     | [744f091c75](https://linux-hardware.org/?probe=744f091c75) | May 18, 2023 |
| Dell          | Inspiron 15-7568            | [77675ecccd](https://linux-hardware.org/?probe=77675ecccd) | May 17, 2023 |
| Acer          | Swift SFA16-41              | [8b1e6a5baf](https://linux-hardware.org/?probe=8b1e6a5baf) | May 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [0770462dab](https://linux-hardware.org/?probe=0770462dab) | May 15, 2023 |
| Dell          | Inspiron 3542               | [a6ffd0df31](https://linux-hardware.org/?probe=a6ffd0df31) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| HP            | Laptop 15-ef2xxx            | [f732fbd488](https://linux-hardware.org/?probe=f732fbd488) | May 14, 2023 |
| Dell          | XPS 15 9570                 | [59214a0e61](https://linux-hardware.org/?probe=59214a0e61) | May 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [fb58a4d348](https://linux-hardware.org/?probe=fb58a4d348) | May 14, 2023 |
| Dell          | Vostro 5471                 | [745ae69749](https://linux-hardware.org/?probe=745ae69749) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| HP            | Pavilion dv6                | [c164fc1080](https://linux-hardware.org/?probe=c164fc1080) | May 14, 2023 |
| HP            | Pavilion dv6                | [b4c4fde79d](https://linux-hardware.org/?probe=b4c4fde79d) | May 14, 2023 |
| Schenker      | VISION (E22)                | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| Sony          | SVE1513Z1EB                 | [d47ba48012](https://linux-hardware.org/?probe=d47ba48012) | May 12, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2674c1ddb6](https://linux-hardware.org/?probe=2674c1ddb6) | May 12, 2023 |
| Dell          | Inspiron 15-7568            | [bb8fe2215b](https://linux-hardware.org/?probe=bb8fe2215b) | May 12, 2023 |
| MSI           | GT70 2PC                    | [c98c889dbf](https://linux-hardware.org/?probe=c98c889dbf) | May 11, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Dell          | Precision 7520              | [184802dbab](https://linux-hardware.org/?probe=184802dbab) | May 11, 2023 |
| Itautec       | Infoway w7440               | [41eee30825](https://linux-hardware.org/?probe=41eee30825) | May 11, 2023 |
| Dell          | Latitude E6440              | [ea902a82a4](https://linux-hardware.org/?probe=ea902a82a4) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57a74239f8](https://linux-hardware.org/?probe=57a74239f8) | May 10, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [962ca6e507](https://linux-hardware.org/?probe=962ca6e507) | May 10, 2023 |
| Acer          | TravelMate P653-M           | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0b797e8428](https://linux-hardware.org/?probe=0b797e8428) | May 10, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [69f4dd51d9](https://linux-hardware.org/?probe=69f4dd51d9) | May 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [fa734dc49a](https://linux-hardware.org/?probe=fa734dc49a) | May 09, 2023 |
| Dell          | XPS 15 9520                 | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0fc6f7617](https://linux-hardware.org/?probe=e0fc6f7617) | May 08, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| Toshiba       | Satellite L855              | [5e78ff90cc](https://linux-hardware.org/?probe=5e78ff90cc) | May 08, 2023 |
| TUXEDO        | N24_25BU                    | [9cd4e499ae](https://linux-hardware.org/?probe=9cd4e499ae) | May 07, 2023 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [a9fe0fdf88](https://linux-hardware.org/?probe=a9fe0fdf88) | May 07, 2023 |
| Dell          | Inspiron 5585               | [f838e48bd3](https://linux-hardware.org/?probe=f838e48bd3) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| HP            | EliteBook 840 G6            | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| Gigabyte      | G5 MD                       | [7ad914a8a9](https://linux-hardware.org/?probe=7ad914a8a9) | May 06, 2023 |
| Acer          | Nitro AN517-54              | [0a66f5d4e4](https://linux-hardware.org/?probe=0a66f5d4e4) | May 06, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [9b843f40a1](https://linux-hardware.org/?probe=9b843f40a1) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | [dd6f6a940f](https://linux-hardware.org/?probe=dd6f6a940f) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | [c7b66fbdc3](https://linux-hardware.org/?probe=c7b66fbdc3) | May 05, 2023 |
| HP            | Laptop 15-dy1xxx            | [dd238f7e60](https://linux-hardware.org/?probe=dd238f7e60) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [6a70490cd6](https://linux-hardware.org/?probe=6a70490cd6) | May 03, 2023 |
| HP            | Compaq Presario C700        | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Acer          | Swift SF114-32              | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| Acer          | Nitro AN517-54              | [c26b48854d](https://linux-hardware.org/?probe=c26b48854d) | May 03, 2023 |
| MECHREVO      | WUJIE16 Pro                 | [c19e8370e5](https://linux-hardware.org/?probe=c19e8370e5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | [9cee4296b5](https://linux-hardware.org/?probe=9cee4296b5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | [a9406a1851](https://linux-hardware.org/?probe=a9406a1851) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| HP            | ProBook 450 G7              | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Sony          | VPCSB2A7R                   | [f089770d02](https://linux-hardware.org/?probe=f089770d02) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | [89f52ca147](https://linux-hardware.org/?probe=89f52ca147) | Apr 28, 2023 |
| HP            | ENVY Notebook               | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fe959d51ab](https://linux-hardware.org/?probe=fe959d51ab) | Apr 27, 2023 |
| MECHREVO      | X3 Series GK7CP6R           | [c764a98c9d](https://linux-hardware.org/?probe=c764a98c9d) | Apr 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4fb9a937f3](https://linux-hardware.org/?probe=4fb9a937f3) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [d470349226](https://linux-hardware.org/?probe=d470349226) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20bf63821f](https://linux-hardware.org/?probe=20bf63821f) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Emdoor        | AG958                       | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Medion        | E4251                       | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Google        | Fleex                       | [19603bb256](https://linux-hardware.org/?probe=19603bb256) | Apr 22, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [6e1df0f6ee](https://linux-hardware.org/?probe=6e1df0f6ee) | Apr 21, 2023 |
| Emdoor        | AG958                       | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [87538ce2ba](https://linux-hardware.org/?probe=87538ce2ba) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| HP            | Laptop 15-dw3xxx            | [648c4c3622](https://linux-hardware.org/?probe=648c4c3622) | Apr 20, 2023 |
| HP            | ProBook 4540s               | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| Dell          | Precision 3550              | [2f1a7d66f4](https://linux-hardware.org/?probe=2f1a7d66f4) | Apr 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [cb5a9be901](https://linux-hardware.org/?probe=cb5a9be901) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [3d2366f479](https://linux-hardware.org/?probe=3d2366f479) | Apr 18, 2023 |
| HONOR         | HYM-WXX                     | [49d7cdd068](https://linux-hardware.org/?probe=49d7cdd068) | Apr 18, 2023 |
| HP            | 250 G7 Notebook PC          | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| Dell          | Precision 3571              | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| Dell          | Latitude 5500               | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3e9d210a94](https://linux-hardware.org/?probe=3e9d210a94) | Apr 16, 2023 |
| Positivo      | C14CR01                     | [a5fc85315a](https://linux-hardware.org/?probe=a5fc85315a) | Apr 16, 2023 |
| Acer          | Nitro AN515-46              | [502263c435](https://linux-hardware.org/?probe=502263c435) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | [33c25e0c22](https://linux-hardware.org/?probe=33c25e0c22) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | [33936188c8](https://linux-hardware.org/?probe=33936188c8) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| AZW           | GT-R                        | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| HP            | ProBook 640 G1              | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| Unknown       | Unknown                     | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Samsung       | 270E5G/270E5U               | [ea58c893c1](https://linux-hardware.org/?probe=ea58c893c1) | Apr 13, 2023 |
| Unknown       | Unknown                     | [3637a41ac7](https://linux-hardware.org/?probe=3637a41ac7) | Apr 13, 2023 |
| Apple         | MacBookPro7,1               | [7c28a5666c](https://linux-hardware.org/?probe=7c28a5666c) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | [d1ecfaf06b](https://linux-hardware.org/?probe=d1ecfaf06b) | Apr 12, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| Acer          | Aspire A515-57              | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| Dell          | Precision 5520              | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| Sony          | VPCSB2A7R                   | [1620c38937](https://linux-hardware.org/?probe=1620c38937) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [5a4d307476](https://linux-hardware.org/?probe=5a4d307476) | Apr 09, 2023 |
| MACHENIKE     | T58-V                       | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Fujitsu       | LIFEBOOK E746               | [11cc5eca09](https://linux-hardware.org/?probe=11cc5eca09) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| Acer          | Nitro AN515-46              | [6611343c84](https://linux-hardware.org/?probe=6611343c84) | Apr 05, 2023 |
| Acer          | Nitro AN515-46              | [1dcee27dff](https://linux-hardware.org/?probe=1dcee27dff) | Apr 05, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [770d8a9253](https://linux-hardware.org/?probe=770d8a9253) | Apr 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [8c29713fe9](https://linux-hardware.org/?probe=8c29713fe9) | Apr 05, 2023 |
| LG Electro... | Kabylake Platform           | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| Toshiba       | QOSMIO F750                 | [695bc9e499](https://linux-hardware.org/?probe=695bc9e499) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| HP            | EliteBook 850 G6            | [303d201aa6](https://linux-hardware.org/?probe=303d201aa6) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| Timi          | RedmiBook 16                | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fc6e550ca1](https://linux-hardware.org/?probe=fc6e550ca1) | Apr 03, 2023 |
| Sony          | VPCF236FM                   | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ed69a3bba9](https://linux-hardware.org/?probe=ed69a3bba9) | Apr 02, 2023 |
| Star Labs     | StarBook                    | [8712994e3c](https://linux-hardware.org/?probe=8712994e3c) | Apr 01, 2023 |
| Dell          | XPS 13 9380                 | [47557561a9](https://linux-hardware.org/?probe=47557561a9) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [d35ddee3e1](https://linux-hardware.org/?probe=d35ddee3e1) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| HP            | 250 G3                      | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| Dell          | Precision M6400             | [293957e2c0](https://linux-hardware.org/?probe=293957e2c0) | Mar 30, 2023 |
| HP            | OMEN by Laptop              | [c6e4da00ac](https://linux-hardware.org/?probe=c6e4da00ac) | Mar 30, 2023 |
| Framework     | Laptop                      | [ef17714efa](https://linux-hardware.org/?probe=ef17714efa) | Mar 30, 2023 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [eb153b5f5d](https://linux-hardware.org/?probe=eb153b5f5d) | Mar 29, 2023 |
| HP            | Notebook                    | [ea7c0e1a2c](https://linux-hardware.org/?probe=ea7c0e1a2c) | Mar 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c393e49ce3](https://linux-hardware.org/?probe=c393e49ce3) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e7608e5c20](https://linux-hardware.org/?probe=e7608e5c20) | Mar 28, 2023 |
| Acer          | Swift SFX14-41G             | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [01a09bc2c7](https://linux-hardware.org/?probe=01a09bc2c7) | Mar 27, 2023 |
| Dell          | Precision 3571              | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Toshiba       | QOSMIO F750                 | [b52a3268f6](https://linux-hardware.org/?probe=b52a3268f6) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Dell          | G15 5515                    | [9c13066534](https://linux-hardware.org/?probe=9c13066534) | Mar 27, 2023 |
| MSI           | GT70 2PE                    | [be727f6f39](https://linux-hardware.org/?probe=be727f6f39) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [13e0523db8](https://linux-hardware.org/?probe=13e0523db8) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| Dell          | Vostro 15-3568              | [bc2447e1e5](https://linux-hardware.org/?probe=bc2447e1e5) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | [f027c9ca09](https://linux-hardware.org/?probe=f027c9ca09) | Mar 25, 2023 |
| Dell          | Vostro 15-3568              | [e6ee9fc566](https://linux-hardware.org/?probe=e6ee9fc566) | Mar 25, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [5377aa4b23](https://linux-hardware.org/?probe=5377aa4b23) | Mar 24, 2023 |
| realme        | CloudProXXXX                | [aaafa41631](https://linux-hardware.org/?probe=aaafa41631) | Mar 23, 2023 |
| Dell          | XPS 9315                    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [88d49f423d](https://linux-hardware.org/?probe=88d49f423d) | Mar 22, 2023 |
| Dell          | XPS 15 9500                 | [893f51c005](https://linux-hardware.org/?probe=893f51c005) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| ASUSTek       | TP500LB                     | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3f233b6f9d](https://linux-hardware.org/?probe=3f233b6f9d) | Mar 20, 2023 |
| Dell          | XPS 15 9520                 | [b6ffb56057](https://linux-hardware.org/?probe=b6ffb56057) | Mar 20, 2023 |
| Acer          | Aspire E5-573G              | [e1c4772d0d](https://linux-hardware.org/?probe=e1c4772d0d) | Mar 19, 2023 |
| Acer          | Aspire E5-573G              | [68cf28bafe](https://linux-hardware.org/?probe=68cf28bafe) | Mar 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S64C00    | [d91384b02c](https://linux-hardware.org/?probe=d91384b02c) | Mar 19, 2023 |
| HP            | Laptop 15-rb0xx             | [d7ed5ce80d](https://linux-hardware.org/?probe=d7ed5ce80d) | Mar 19, 2023 |
| HP            | 245 G8                      | [5b1606146f](https://linux-hardware.org/?probe=5b1606146f) | Mar 19, 2023 |
| Sony          | SVZ1311C5E                  | [e433359eb9](https://linux-hardware.org/?probe=e433359eb9) | Mar 18, 2023 |
| Dell          | Latitude E5470              | [6565aa43e3](https://linux-hardware.org/?probe=6565aa43e3) | Mar 18, 2023 |
| Itautec       | Infoway w7440               | [c1e90dd1a3](https://linux-hardware.org/?probe=c1e90dd1a3) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc76a5003](https://linux-hardware.org/?probe=ecc76a5003) | Mar 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [4ff2145364](https://linux-hardware.org/?probe=4ff2145364) | Mar 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | [dd58f68013](https://linux-hardware.org/?probe=dd58f68013) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| Sony          | SVF1521Q1EW                 | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | [2eff18f570](https://linux-hardware.org/?probe=2eff18f570) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | [2c0d31ff9e](https://linux-hardware.org/?probe=2c0d31ff9e) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [a99c892744](https://linux-hardware.org/?probe=a99c892744) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | [4853be01f6](https://linux-hardware.org/?probe=4853be01f6) | Mar 14, 2023 |
| Sony          | VPCEB4L1E                   | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| Dell          | G5 5587                     | [4ff3c98faf](https://linux-hardware.org/?probe=4ff3c98faf) | Mar 14, 2023 |
| Dell          | XPS 15 7590                 | [5997bff822](https://linux-hardware.org/?probe=5997bff822) | Mar 14, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4f32e23c4](https://linux-hardware.org/?probe=b4f32e23c4) | Mar 14, 2023 |
| HONOR         | BMH-WCX9                    | [d53fa296bf](https://linux-hardware.org/?probe=d53fa296bf) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [3dc28679cc](https://linux-hardware.org/?probe=3dc28679cc) | Mar 14, 2023 |
| Positivo      | Q464B                       | [5bd9649f43](https://linux-hardware.org/?probe=5bd9649f43) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | [41cee24fa8](https://linux-hardware.org/?probe=41cee24fa8) | Mar 13, 2023 |
| HP            | Pavilion dv7                | [b0834fe20e](https://linux-hardware.org/?probe=b0834fe20e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| Apple         | MacBookPro14,1              | [999c455869](https://linux-hardware.org/?probe=999c455869) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| GPD           | G1621-02                    | [21394d0975](https://linux-hardware.org/?probe=21394d0975) | Mar 12, 2023 |
| Medion        | E4251                       | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| Apple         | MacBookPro14,1              | [593c3e084d](https://linux-hardware.org/?probe=593c3e084d) | Mar 12, 2023 |
| HP            | Laptop 15-dw3xxx            | [cc73320a47](https://linux-hardware.org/?probe=cc73320a47) | Mar 12, 2023 |
| HP            | Laptop 15-dy1xxx            | [ac6452184d](https://linux-hardware.org/?probe=ac6452184d) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| HP            | EliteBook 845 14 inch G9... | [5dfc4ceb2a](https://linux-hardware.org/?probe=5dfc4ceb2a) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| Unknown       | Unknown                     | [5d585fb91b](https://linux-hardware.org/?probe=5d585fb91b) | Mar 11, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| Medion        | Akoya E6412T                | [d8941697fd](https://linux-hardware.org/?probe=d8941697fd) | Mar 09, 2023 |
| Dell          | Latitude 5590               | [d7d667d45f](https://linux-hardware.org/?probe=d7d667d45f) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | [3f6f0bc1a2](https://linux-hardware.org/?probe=3f6f0bc1a2) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | [04d6eb5847](https://linux-hardware.org/?probe=04d6eb5847) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | [141222a198](https://linux-hardware.org/?probe=141222a198) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | [2f2541bbf1](https://linux-hardware.org/?probe=2f2541bbf1) | Mar 08, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [4b82b56d82](https://linux-hardware.org/?probe=4b82b56d82) | Mar 08, 2023 |
| Infinix       | INBOOK X2 GEN11             | [3d14886d4c](https://linux-hardware.org/?probe=3d14886d4c) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | [124b1af920](https://linux-hardware.org/?probe=124b1af920) | Mar 07, 2023 |
| Dell          | Latitude 5330               | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [d62df340f9](https://linux-hardware.org/?probe=d62df340f9) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| Unknown       | Unknown                     | [8b7f7b9440](https://linux-hardware.org/?probe=8b7f7b9440) | Mar 05, 2023 |
| Dell          | Inspiron 17-7779            | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| Google        | Delbin                      | [3817b0d62d](https://linux-hardware.org/?probe=3817b0d62d) | Mar 05, 2023 |
| Dell          | XPS 15 9500                 | [47df9846bb](https://linux-hardware.org/?probe=47df9846bb) | Mar 04, 2023 |
| HP            | Pavilion 15                 | [50a27abb52](https://linux-hardware.org/?probe=50a27abb52) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [645b47cfa2](https://linux-hardware.org/?probe=645b47cfa2) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| Acer          | Nitro AN515-45              | [c3043c0cba](https://linux-hardware.org/?probe=c3043c0cba) | Mar 03, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| Dell          | Latitude 5421               | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Dell          | Vostro 3500                 | [4e540e33b1](https://linux-hardware.org/?probe=4e540e33b1) | Mar 01, 2023 |
| Positivo      | C14CR21                     | [d0041f93e1](https://linux-hardware.org/?probe=d0041f93e1) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude E7450              | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [3ab9ad10d8](https://linux-hardware.org/?probe=3ab9ad10d8) | Feb 28, 2023 |
| Dell          | XPS 13 9380                 | [e888e1330d](https://linux-hardware.org/?probe=e888e1330d) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | [18fdb45ec1](https://linux-hardware.org/?probe=18fdb45ec1) | Feb 27, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [da19f23a14](https://linux-hardware.org/?probe=da19f23a14) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| System76      | Serval WS                   | [1b136ec80d](https://linux-hardware.org/?probe=1b136ec80d) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| HP            | G60                         | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| HP            | ZBook 17 G2                 | [408bb96959](https://linux-hardware.org/?probe=408bb96959) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [93dfbdd8cd](https://linux-hardware.org/?probe=93dfbdd8cd) | Feb 24, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [aef7584b8c](https://linux-hardware.org/?probe=aef7584b8c) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| Fujitsu       | LIFEBOOK E754               | [b2ae4d0b42](https://linux-hardware.org/?probe=b2ae4d0b42) | Feb 23, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ead0af8ae4](https://linux-hardware.org/?probe=ead0af8ae4) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude E5470              | [12a8a55fca](https://linux-hardware.org/?probe=12a8a55fca) | Feb 23, 2023 |
| HP            | EliteBook 8470p             | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [55c6dbae70](https://linux-hardware.org/?probe=55c6dbae70) | Feb 23, 2023 |
| HP            | Pavilion Notebook           | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| Dell          | Latitude 7410               | [dfa449b870](https://linux-hardware.org/?probe=dfa449b870) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| MSI           | GF63 Thin 9RCX              | [87a9510543](https://linux-hardware.org/?probe=87a9510543) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | [f98cec9924](https://linux-hardware.org/?probe=f98cec9924) | Feb 22, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [8be573974d](https://linux-hardware.org/?probe=8be573974d) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Gigabyte      | AORUS 17 XE4                | [b674e3e1e0](https://linux-hardware.org/?probe=b674e3e1e0) | Feb 21, 2023 |
| Apple         | MacBookAir7,2               | [97b147476a](https://linux-hardware.org/?probe=97b147476a) | Feb 20, 2023 |
| Dell          | Latitude E6430              | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | [d8afec7717](https://linux-hardware.org/?probe=d8afec7717) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | [a3f369f79b](https://linux-hardware.org/?probe=a3f369f79b) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cc447f6c07](https://linux-hardware.org/?probe=cc447f6c07) | Feb 19, 2023 |
| HUAWEI        | BOD-WXX9                    | [f8e02626c5](https://linux-hardware.org/?probe=f8e02626c5) | Feb 19, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [28e6263489](https://linux-hardware.org/?probe=28e6263489) | Feb 19, 2023 |
| HP            | Notebook                    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Unknown       | Unknown                     | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| Dell          | G3 3590                     | [a8a3df007f](https://linux-hardware.org/?probe=a8a3df007f) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| Acer          | Aspire A515-51              | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [5e35f0aecc](https://linux-hardware.org/?probe=5e35f0aecc) | Feb 17, 2023 |
| Jumper        | EZbook                      | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| HONOR         | BMH-WCX9                    | [c113bd50f3](https://linux-hardware.org/?probe=c113bd50f3) | Feb 16, 2023 |
| Jumper        | EZbook                      | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e5e721aaf2](https://linux-hardware.org/?probe=e5e721aaf2) | Feb 16, 2023 |
| Google        | Robo360                     | [744490a82c](https://linux-hardware.org/?probe=744490a82c) | Feb 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Google        | Robo360                     | [573d036948](https://linux-hardware.org/?probe=573d036948) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [1ebc6ae882](https://linux-hardware.org/?probe=1ebc6ae882) | Feb 14, 2023 |
| Dell          | XPS 9320                    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| Acer          | TravelMate P215-52          | [b4ac56b67d](https://linux-hardware.org/?probe=b4ac56b67d) | Feb 13, 2023 |
| Acer          | Aspire E5-771G              | [d1abb191dd](https://linux-hardware.org/?probe=d1abb191dd) | Feb 13, 2023 |
| Dell          | Latitude 7490               | [c3f07cbb13](https://linux-hardware.org/?probe=c3f07cbb13) | Feb 13, 2023 |
| Dell          | Precision 3571              | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7711c96063](https://linux-hardware.org/?probe=7711c96063) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| ASUSTek       | X550CC                      | [769e8c51f0](https://linux-hardware.org/?probe=769e8c51f0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | [fb8b46669e](https://linux-hardware.org/?probe=fb8b46669e) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [0a3aa89ac9](https://linux-hardware.org/?probe=0a3aa89ac9) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [69cd397ac6](https://linux-hardware.org/?probe=69cd397ac6) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| Dell          | Inspiron 13 5310            | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| MSI           | GE60 2QE                    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Dell          | Precision 3571              | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f5dbc828f3](https://linux-hardware.org/?probe=f5dbc828f3) | Feb 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [95f88cc4d8](https://linux-hardware.org/?probe=95f88cc4d8) | Feb 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [5c86b33fdd](https://linux-hardware.org/?probe=5c86b33fdd) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [7a2dd12cd8](https://linux-hardware.org/?probe=7a2dd12cd8) | Feb 08, 2023 |
| HP            | 15 Notebook PC              | [df487953da](https://linux-hardware.org/?probe=df487953da) | Feb 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [a8aa5d2d58](https://linux-hardware.org/?probe=a8aa5d2d58) | Feb 07, 2023 |
| HUAWEI        | BOM-WXX9                    | [ad723064e1](https://linux-hardware.org/?probe=ad723064e1) | Feb 06, 2023 |
| ASUSTek       | X550VXK                     | [e7a0aa4ff9](https://linux-hardware.org/?probe=e7a0aa4ff9) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f3cc45d12e](https://linux-hardware.org/?probe=f3cc45d12e) | Feb 05, 2023 |
| Timi          | A34S                        | [97aed45fe2](https://linux-hardware.org/?probe=97aed45fe2) | Feb 04, 2023 |
| Timi          | A34S                        | [55208c4210](https://linux-hardware.org/?probe=55208c4210) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [139605fcc1](https://linux-hardware.org/?probe=139605fcc1) | Feb 03, 2023 |
| Dell          | XPS 15 7590                 | [81f824a063](https://linux-hardware.org/?probe=81f824a063) | Feb 03, 2023 |
| Unknown       | Unknown                     | [5505a27d5e](https://linux-hardware.org/?probe=5505a27d5e) | Feb 03, 2023 |
| Acer          | Predator PH315-55           | [9f90c06d52](https://linux-hardware.org/?probe=9f90c06d52) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| GPD           | G1619-04                    | [958fa49a0e](https://linux-hardware.org/?probe=958fa49a0e) | Feb 02, 2023 |
| Acer          | TravelMate P633-M           | [b9bb5f3746](https://linux-hardware.org/?probe=b9bb5f3746) | Feb 02, 2023 |
| Dell          | Vostro 5481                 | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [3a2665872a](https://linux-hardware.org/?probe=3a2665872a) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| Dell          | Latitude 7430               | [44d6dd63ce](https://linux-hardware.org/?probe=44d6dd63ce) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| MSI           | GF63 Thin 11UC              | [4f06c55846](https://linux-hardware.org/?probe=4f06c55846) | Feb 01, 2023 |
| Acer          | Aspire A315-56              | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [3c0723977c](https://linux-hardware.org/?probe=3c0723977c) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8a324e4189](https://linux-hardware.org/?probe=8a324e4189) | Jan 30, 2023 |
| HP            | OMEN by Laptop 15z-en100    | [0c91238954](https://linux-hardware.org/?probe=0c91238954) | Jan 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| MSI           | Modern 14 A10RB             | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| HP            | Compaq 6530b                | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | [1ae85a6add](https://linux-hardware.org/?probe=1ae85a6add) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | [7f9b52e91c](https://linux-hardware.org/?probe=7f9b52e91c) | Jan 27, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| Lenovo        | ThinkPad T490 20N20048GE    | [54915be6bc](https://linux-hardware.org/?probe=54915be6bc) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| realme        | CloudProXXXX                | [520d929687](https://linux-hardware.org/?probe=520d929687) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [bf22d53528](https://linux-hardware.org/?probe=bf22d53528) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| Dell          | XPS 9320                    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [e5cbb75254](https://linux-hardware.org/?probe=e5cbb75254) | Jan 23, 2023 |
| System76      | Darter UltraThin            | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| Medion        | E4251                       | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [348a78bb64](https://linux-hardware.org/?probe=348a78bb64) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c6a463e92f](https://linux-hardware.org/?probe=c6a463e92f) | Jan 22, 2023 |
| Toshiba       | Satellite C50-C             | [3512195f65](https://linux-hardware.org/?probe=3512195f65) | Jan 21, 2023 |
| Dell          | G7 7700                     | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| Acer          | Swift SF314-57              | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| Dell          | Latitude E5440              | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | EliteBook 840 G5            | [96e072d33f](https://linux-hardware.org/?probe=96e072d33f) | Jan 18, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| Acer          | Predator PH315-52           | [4df4c5ecc8](https://linux-hardware.org/?probe=4df4c5ecc8) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| Dell          | Inspiron 5585               | [b92481ca4e](https://linux-hardware.org/?probe=b92481ca4e) | Jan 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [6c8a25d916](https://linux-hardware.org/?probe=6c8a25d916) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | [9816a244b2](https://linux-hardware.org/?probe=9816a244b2) | Jan 16, 2023 |
| MSI           | Prestige 15 A11SCX          | [9c5bf0d05c](https://linux-hardware.org/?probe=9c5bf0d05c) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| HP            | ProBook 655 G1              | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [958ecc4388](https://linux-hardware.org/?probe=958ecc4388) | Jan 15, 2023 |
| Acer          | Predator PH315-53           | [436a4fc2a0](https://linux-hardware.org/?probe=436a4fc2a0) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| LG Electro... | 17Z90N-R.AAS9U1             | [9d6736bccd](https://linux-hardware.org/?probe=9d6736bccd) | Jan 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [52b5182480](https://linux-hardware.org/?probe=52b5182480) | Jan 14, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [4a0fec8aef](https://linux-hardware.org/?probe=4a0fec8aef) | Jan 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [699d727f84](https://linux-hardware.org/?probe=699d727f84) | Jan 14, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [05744a666a](https://linux-hardware.org/?probe=05744a666a) | Jan 13, 2023 |
| Dell          | XPS 15 9500                 | [00348d3769](https://linux-hardware.org/?probe=00348d3769) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [73533cda86](https://linux-hardware.org/?probe=73533cda86) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [ff2c48315e](https://linux-hardware.org/?probe=ff2c48315e) | Jan 13, 2023 |
| realme        | CloudProXXXX                | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| HP            | Laptop 15-bs0xx             | [3cd650450c](https://linux-hardware.org/?probe=3cd650450c) | Jan 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [fbb327effe](https://linux-hardware.org/?probe=fbb327effe) | Jan 12, 2023 |
| HP            | Pavilion 15                 | [1dc150e9db](https://linux-hardware.org/?probe=1dc150e9db) | Jan 12, 2023 |
| HP            | ProBook 6560b               | [9f06213ef6](https://linux-hardware.org/?probe=9f06213ef6) | Jan 12, 2023 |
| HP            | ProBook 6560b               | [5b71b83435](https://linux-hardware.org/?probe=5b71b83435) | Jan 12, 2023 |
| Notebook      | L14xMU                      | [48b282b529](https://linux-hardware.org/?probe=48b282b529) | Jan 12, 2023 |
| Apple         | MacBookPro11,3              | [ede9b6da76](https://linux-hardware.org/?probe=ede9b6da76) | Jan 12, 2023 |
| Lenovo        | Z50-75 80EC                 | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [5be6eaa40c](https://linux-hardware.org/?probe=5be6eaa40c) | Jan 11, 2023 |
| HONOR         | NMH-WCX9                    | [a67f1ee7b0](https://linux-hardware.org/?probe=a67f1ee7b0) | Jan 11, 2023 |
| Dell          | Precision 7710              | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| HP            | ProBook 655 G1              | [f61b79535e](https://linux-hardware.org/?probe=f61b79535e) | Jan 10, 2023 |
| ASUSTek       | UX31A                       | [c618ab31a8](https://linux-hardware.org/?probe=c618ab31a8) | Jan 10, 2023 |
| HP            | Pavilion dv6                | [8f65765701](https://linux-hardware.org/?probe=8f65765701) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | [45e96fb346](https://linux-hardware.org/?probe=45e96fb346) | Jan 09, 2023 |
| Dell          | Precision 7710              | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| ASUSTek       | UX31A                       | [2eaea530ea](https://linux-hardware.org/?probe=2eaea530ea) | Jan 09, 2023 |
| HP            | ProBook 655 G1              | [91948448b6](https://linux-hardware.org/?probe=91948448b6) | Jan 09, 2023 |
| MSI           | GS63 Stealth 8RE            | [8682a08d74](https://linux-hardware.org/?probe=8682a08d74) | Jan 09, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | [5feb203761](https://linux-hardware.org/?probe=5feb203761) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | [da175172b3](https://linux-hardware.org/?probe=da175172b3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [1570ad8d8b](https://linux-hardware.org/?probe=1570ad8d8b) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [6ab7f1996a](https://linux-hardware.org/?probe=6ab7f1996a) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dc2a0809aa](https://linux-hardware.org/?probe=dc2a0809aa) | Jan 07, 2023 |
| IPASON        | MaxBook P1X                 | [b7d1ce416f](https://linux-hardware.org/?probe=b7d1ce416f) | Jan 07, 2023 |
| Sony          | SVS1512U1RW                 | [c5de402a7c](https://linux-hardware.org/?probe=c5de402a7c) | Jan 06, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| Samsung       | R530/R730                   | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c298dd423d](https://linux-hardware.org/?probe=c298dd423d) | Jan 05, 2023 |
| Medion        | E4251 MD61435               | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| ASUSTek       | X501A1                      | [f88e88d88d](https://linux-hardware.org/?probe=f88e88d88d) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| HP            | Laptop 14-dk0xxx            | [47654afbbc](https://linux-hardware.org/?probe=47654afbbc) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ac3df6f289](https://linux-hardware.org/?probe=ac3df6f289) | Jan 03, 2023 |
| HP            | EliteBook 840 G5            | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Dell          | Inspiron 7577               | [437194cbc0](https://linux-hardware.org/?probe=437194cbc0) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | [c8d9352d43](https://linux-hardware.org/?probe=c8d9352d43) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | [ddadb5f34d](https://linux-hardware.org/?probe=ddadb5f34d) | Jan 03, 2023 |
| Dell          | Latitude 7410               | [3dadd543f1](https://linux-hardware.org/?probe=3dadd543f1) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| Dell          | XPS 15 9570                 | [c5d2fc381a](https://linux-hardware.org/?probe=c5d2fc381a) | Jan 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7ff55c14b4](https://linux-hardware.org/?probe=7ff55c14b4) | Jan 02, 2023 |
| HP            | ZBook 15 G5                 | [04364cac9a](https://linux-hardware.org/?probe=04364cac9a) | Jan 02, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [fbf89f7693](https://linux-hardware.org/?probe=fbf89f7693) | Jan 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [70d5242ad0](https://linux-hardware.org/?probe=70d5242ad0) | Jan 01, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | [a22f1e75b3](https://linux-hardware.org/?probe=a22f1e75b3) | Jan 01, 2023 |
| Unknown       | Unknown                     | [10496680a5](https://linux-hardware.org/?probe=10496680a5) | Dec 31, 2022 |
| Dell          | XPS 9320                    | [c98fd80f29](https://linux-hardware.org/?probe=c98fd80f29) | Dec 31, 2022 |
| ASUSTek       | X550VXK                     | [b8cd38522a](https://linux-hardware.org/?probe=b8cd38522a) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [ac397dc318](https://linux-hardware.org/?probe=ac397dc318) | Dec 31, 2022 |
| HP            | EliteBook 845 14 inch G9... | [5b5e58e433](https://linux-hardware.org/?probe=5b5e58e433) | Dec 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [c2a949b725](https://linux-hardware.org/?probe=c2a949b725) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [5043868e71](https://linux-hardware.org/?probe=5043868e71) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [11d4e1f9a1](https://linux-hardware.org/?probe=11d4e1f9a1) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [b60b954dc4](https://linux-hardware.org/?probe=b60b954dc4) | Dec 29, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| Apple         | MacBookAir6,2               | [af9ab4ba4d](https://linux-hardware.org/?probe=af9ab4ba4d) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f5cbe897b8](https://linux-hardware.org/?probe=f5cbe897b8) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f19e16b1ac](https://linux-hardware.org/?probe=f19e16b1ac) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [41f77d037b](https://linux-hardware.org/?probe=41f77d037b) | Dec 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [b62b4d2134](https://linux-hardware.org/?probe=b62b4d2134) | Dec 27, 2022 |
| Dell          | XPS 9320                    | [7a2537eba2](https://linux-hardware.org/?probe=7a2537eba2) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [eb5e0b8201](https://linux-hardware.org/?probe=eb5e0b8201) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4ea69511df](https://linux-hardware.org/?probe=4ea69511df) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c8b85cb0cd](https://linux-hardware.org/?probe=c8b85cb0cd) | Dec 26, 2022 |
| Dell          | Inspiron N5010              | [69ac8a9522](https://linux-hardware.org/?probe=69ac8a9522) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [06027a53fb](https://linux-hardware.org/?probe=06027a53fb) | Dec 26, 2022 |
| Chuwi         | HeroBook Air                | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [649291f277](https://linux-hardware.org/?probe=649291f277) | Dec 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [8d2d8be057](https://linux-hardware.org/?probe=8d2d8be057) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Dell          | XPS 9320                    | [f55956cac2](https://linux-hardware.org/?probe=f55956cac2) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [81fcc00d18](https://linux-hardware.org/?probe=81fcc00d18) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Medion        | E4251 MD61435               | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| HP            | Laptop 15-bs0xx             | [3d50b74a6b](https://linux-hardware.org/?probe=3d50b74a6b) | Dec 23, 2022 |
| HUAWEI        | KPR-WX9                     | [e2b01c4a0f](https://linux-hardware.org/?probe=e2b01c4a0f) | Dec 23, 2022 |
| Acer          | Aspire A515-52G             | [586dd36eed](https://linux-hardware.org/?probe=586dd36eed) | Dec 23, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [e2e9b14a43](https://linux-hardware.org/?probe=e2e9b14a43) | Dec 23, 2022 |
| Dell          | Precision M6600             | [00840d085c](https://linux-hardware.org/?probe=00840d085c) | Dec 23, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Dell          | XPS 9320                    | [7bb7ba7202](https://linux-hardware.org/?probe=7bb7ba7202) | Dec 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| MSI           | Katana GF66 11UE            | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| HUAWEI        | VLT-WX0                     | [6f2d542a6e](https://linux-hardware.org/?probe=6f2d542a6e) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0MQ0... | [94e5bdb2cb](https://linux-hardware.org/?probe=94e5bdb2cb) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [214d584e36](https://linux-hardware.org/?probe=214d584e36) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [c4f6f99d36](https://linux-hardware.org/?probe=c4f6f99d36) | Dec 21, 2022 |
| HP            | ENVY Laptop 16-h0xxx        | [4e38f93dd3](https://linux-hardware.org/?probe=4e38f93dd3) | Dec 21, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [9e860431a0](https://linux-hardware.org/?probe=9e860431a0) | Dec 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | [90d1d153a4](https://linux-hardware.org/?probe=90d1d153a4) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | [93eff781da](https://linux-hardware.org/?probe=93eff781da) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | [0b7352a343](https://linux-hardware.org/?probe=0b7352a343) | Dec 20, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [654a04cdc4](https://linux-hardware.org/?probe=654a04cdc4) | Dec 20, 2022 |
| Toshiba       | Satellite L10W-B-101        | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [ebf2594631](https://linux-hardware.org/?probe=ebf2594631) | Dec 19, 2022 |
| K.A.Techno... | TM1                         | [88e36a5d00](https://linux-hardware.org/?probe=88e36a5d00) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| Dell          | XPS 13 9350                 | [d414748117](https://linux-hardware.org/?probe=d414748117) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c45ca502c5](https://linux-hardware.org/?probe=c45ca502c5) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [2d6dff8209](https://linux-hardware.org/?probe=2d6dff8209) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0d67c53553](https://linux-hardware.org/?probe=0d67c53553) | Dec 18, 2022 |
| HP            | 2000                        | [6273a792ae](https://linux-hardware.org/?probe=6273a792ae) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [86fbbf1bc2](https://linux-hardware.org/?probe=86fbbf1bc2) | Dec 17, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [8e689417f3](https://linux-hardware.org/?probe=8e689417f3) | Dec 16, 2022 |
| Alienware     | 15                          | [6da8e1748a](https://linux-hardware.org/?probe=6da8e1748a) | Dec 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8f50c0d881](https://linux-hardware.org/?probe=8f50c0d881) | Dec 15, 2022 |
| Dell          | Vostro 7590                 | [c758af3223](https://linux-hardware.org/?probe=c758af3223) | Dec 15, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | [ca39e55353](https://linux-hardware.org/?probe=ca39e55353) | Dec 15, 2022 |
| Dell          | Latitude 5420               | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Dell          | Inspiron 5370               | [dd8f3feae5](https://linux-hardware.org/?probe=dd8f3feae5) | Dec 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9495189605](https://linux-hardware.org/?probe=9495189605) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [3878d884cb](https://linux-hardware.org/?probe=3878d884cb) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [98f6e27cac](https://linux-hardware.org/?probe=98f6e27cac) | Dec 14, 2022 |
| Toshiba       | Satellite Pro L300          | [6db5b50a6b](https://linux-hardware.org/?probe=6db5b50a6b) | Dec 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [db7a82e46c](https://linux-hardware.org/?probe=db7a82e46c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| K.A.Techno... | TM1                         | [a27835f164](https://linux-hardware.org/?probe=a27835f164) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| Acer          | Aspire ES1-111M             | [0d527c1b1d](https://linux-hardware.org/?probe=0d527c1b1d) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| Acer          | Nitro AN517-41              | [468d665801](https://linux-hardware.org/?probe=468d665801) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [559c3f32f8](https://linux-hardware.org/?probe=559c3f32f8) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [eb0d410f64](https://linux-hardware.org/?probe=eb0d410f64) | Dec 12, 2022 |
| Apple         | MacBookPro11,2              | [6048cffe66](https://linux-hardware.org/?probe=6048cffe66) | Dec 12, 2022 |
| Unknown       | X133                        | [694e264bcf](https://linux-hardware.org/?probe=694e264bcf) | Dec 12, 2022 |
| MSI           | Prestige 14 A11SC           | [7fa118f812](https://linux-hardware.org/?probe=7fa118f812) | Dec 11, 2022 |
| Medion        | E4251                       | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Apple         | MacBookPro11,1              | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| Acer          | Aspire E5-571G              | [5ddea1e0e0](https://linux-hardware.org/?probe=5ddea1e0e0) | Dec 11, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [32ce05790e](https://linux-hardware.org/?probe=32ce05790e) | Dec 11, 2022 |
| HUAWEI        | CREM-WXX9                   | [1b6dee1e4a](https://linux-hardware.org/?probe=1b6dee1e4a) | Dec 10, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [61b2bab886](https://linux-hardware.org/?probe=61b2bab886) | Dec 10, 2022 |
| Medion        | E4251                       | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [fdda7ba30e](https://linux-hardware.org/?probe=fdda7ba30e) | Dec 10, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [16232a46ed](https://linux-hardware.org/?probe=16232a46ed) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5S... | [7772d8b9f8](https://linux-hardware.org/?probe=7772d8b9f8) | Dec 10, 2022 |
| GPU Compan... | GWNR71517                   | [148040d1fd](https://linux-hardware.org/?probe=148040d1fd) | Dec 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| IPASON        | MaxBook P1X                 | [c699081c87](https://linux-hardware.org/?probe=c699081c87) | Dec 08, 2022 |
| BESSTAR Te... | U820                        | [ea466e46b1](https://linux-hardware.org/?probe=ea466e46b1) | Dec 07, 2022 |
| HP            | 245 G8                      | [2fbc616550](https://linux-hardware.org/?probe=2fbc616550) | Dec 07, 2022 |
| Clevo         | P150HMx                     | [f1500b1665](https://linux-hardware.org/?probe=f1500b1665) | Dec 06, 2022 |
| Dell          | Inspiron N5110              | [9815b67f0b](https://linux-hardware.org/?probe=9815b67f0b) | Dec 06, 2022 |
| Dell          | G15 5515                    | [63fed6d448](https://linux-hardware.org/?probe=63fed6d448) | Dec 06, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [3e1e88ac7a](https://linux-hardware.org/?probe=3e1e88ac7a) | Dec 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | [792c537a38](https://linux-hardware.org/?probe=792c537a38) | Dec 06, 2022 |
| HP            | ProBook 440 G5              | [7f9c0a0974](https://linux-hardware.org/?probe=7f9c0a0974) | Dec 06, 2022 |
| Dell          | G5 5505                     | [c36399d764](https://linux-hardware.org/?probe=c36399d764) | Dec 06, 2022 |
| Medion        | E4251                       | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [504a0286fb](https://linux-hardware.org/?probe=504a0286fb) | Dec 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [8a91af8c9d](https://linux-hardware.org/?probe=8a91af8c9d) | Dec 05, 2022 |
| Toshiba       | Satellite C650D             | [694d2c9099](https://linux-hardware.org/?probe=694d2c9099) | Dec 05, 2022 |
| Medion        | E4251 MD61435               | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [3ee55cc441](https://linux-hardware.org/?probe=3ee55cc441) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [4a2e796be8](https://linux-hardware.org/?probe=4a2e796be8) | Dec 04, 2022 |
| HP            | ProBook 440 G5              | [a8e17ad39c](https://linux-hardware.org/?probe=a8e17ad39c) | Dec 04, 2022 |
| MECHREVO      | X3 Series GK7CP6R           | [7990b26bbf](https://linux-hardware.org/?probe=7990b26bbf) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [05ae64c1b8](https://linux-hardware.org/?probe=05ae64c1b8) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [ae6745045a](https://linux-hardware.org/?probe=ae6745045a) | Dec 04, 2022 |
| HP            | ZBook 15 G4                 | [9950cb061d](https://linux-hardware.org/?probe=9950cb061d) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| HP            | Pavilion Laptop             | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [3b87d266c2](https://linux-hardware.org/?probe=3b87d266c2) | Dec 02, 2022 |
| Valve         | Jupiter                     | [1fdf6ffce7](https://linux-hardware.org/?probe=1fdf6ffce7) | Dec 01, 2022 |
| Dell          | Precision 5540              | [030dbd45f0](https://linux-hardware.org/?probe=030dbd45f0) | Dec 01, 2022 |
| Acer          | TravelMate P614-51T-G2      | [952e89e25d](https://linux-hardware.org/?probe=952e89e25d) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9bd70d2025](https://linux-hardware.org/?probe=9bd70d2025) | Nov 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [bd0ca3e793](https://linux-hardware.org/?probe=bd0ca3e793) | Nov 30, 2022 |
| Toshiba       | TECRA S11                   | [3d2414e47b](https://linux-hardware.org/?probe=3d2414e47b) | Nov 30, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [f5f86becf7](https://linux-hardware.org/?probe=f5f86becf7) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Dell          | Precision 7520              | [2c0cb92f23](https://linux-hardware.org/?probe=2c0cb92f23) | Nov 29, 2022 |
| HP            | ProBook 440 G5              | [45097ff070](https://linux-hardware.org/?probe=45097ff070) | Nov 29, 2022 |
| HP            | Notebook                    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460s 20FAS16J0... | [142a1e8a94](https://linux-hardware.org/?probe=142a1e8a94) | Nov 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e0bdd2fbd2](https://linux-hardware.org/?probe=e0bdd2fbd2) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [69a6535286](https://linux-hardware.org/?probe=69a6535286) | Nov 28, 2022 |
| Razer         | Blade                       | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| HP            | Laptop 15-dy2xxx            | [a1c088bc35](https://linux-hardware.org/?probe=a1c088bc35) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [0dcd2bdc50](https://linux-hardware.org/?probe=0dcd2bdc50) | Nov 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [620cab185f](https://linux-hardware.org/?probe=620cab185f) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| HUAWEI        | KLVL-WXXW                   | [7e65f428cc](https://linux-hardware.org/?probe=7e65f428cc) | Nov 27, 2022 |
| MSI           | GL62 7QF                    | [abd74be332](https://linux-hardware.org/?probe=abd74be332) | Nov 27, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| Dell          | Latitude E6420              | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| ASUSTek       | X555YI                      | [2626d57c13](https://linux-hardware.org/?probe=2626d57c13) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| Alienware     | 15                          | [3423725ae2](https://linux-hardware.org/?probe=3423725ae2) | Nov 24, 2022 |
| MSI           | GP63 Leopard 8RE            | [f8bb75758e](https://linux-hardware.org/?probe=f8bb75758e) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [96205eb8d4](https://linux-hardware.org/?probe=96205eb8d4) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [97571585cd](https://linux-hardware.org/?probe=97571585cd) | Nov 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [e9ba2ff234](https://linux-hardware.org/?probe=e9ba2ff234) | Nov 22, 2022 |
| ASUSTek       | PRIME Z690-P                | [436bd74a38](https://linux-hardware.org/?probe=436bd74a38) | Nov 22, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [bdf1794487](https://linux-hardware.org/?probe=bdf1794487) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [54d3eed278](https://linux-hardware.org/?probe=54d3eed278) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [60c1698203](https://linux-hardware.org/?probe=60c1698203) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6722142846](https://linux-hardware.org/?probe=6722142846) | Nov 20, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK E756               | [144470ec16](https://linux-hardware.org/?probe=144470ec16) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| Lenovo        | ThinkPad T430 2349KQ3       | [aacdefc31b](https://linux-hardware.org/?probe=aacdefc31b) | Nov 17, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| HP            | Compaq 15                   | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [922ce95539](https://linux-hardware.org/?probe=922ce95539) | Nov 16, 2022 |
| Google        | Boten                       | [105e91dd04](https://linux-hardware.org/?probe=105e91dd04) | Nov 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [3e46bbaa1b](https://linux-hardware.org/?probe=3e46bbaa1b) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [cf97226a28](https://linux-hardware.org/?probe=cf97226a28) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [612006bada](https://linux-hardware.org/?probe=612006bada) | Nov 15, 2022 |
| Dell          | Latitude E6220              | [b1270460e6](https://linux-hardware.org/?probe=b1270460e6) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [2e122b28c4](https://linux-hardware.org/?probe=2e122b28c4) | Nov 15, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [dcffe478fe](https://linux-hardware.org/?probe=dcffe478fe) | Nov 14, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e6ef3b56eb](https://linux-hardware.org/?probe=e6ef3b56eb) | Nov 14, 2022 |
| Lenovo        | ThinkPad T450s 20BW000DH... | [b9913c760a](https://linux-hardware.org/?probe=b9913c760a) | Nov 14, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [41dbab85c0](https://linux-hardware.org/?probe=41dbab85c0) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b3473a1862](https://linux-hardware.org/?probe=b3473a1862) | Nov 13, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ca85c59fad](https://linux-hardware.org/?probe=ca85c59fad) | Nov 13, 2022 |
| Acer          | TravelMate 5730             | [cee6d10d17](https://linux-hardware.org/?probe=cee6d10d17) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| Dell          | G15 5510                    | [641a09f9cc](https://linux-hardware.org/?probe=641a09f9cc) | Nov 13, 2022 |
| Lenovo        | G500 20236                  | [b156c32896](https://linux-hardware.org/?probe=b156c32896) | Nov 12, 2022 |
| MSI           | GS60 6QE                    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [7827dd0f86](https://linux-hardware.org/?probe=7827dd0f86) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [64d896b971](https://linux-hardware.org/?probe=64d896b971) | Nov 11, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [c3612a66aa](https://linux-hardware.org/?probe=c3612a66aa) | Nov 10, 2022 |
| HP            | EliteBook 840 14 inch G9... | [950c263b8a](https://linux-hardware.org/?probe=950c263b8a) | Nov 10, 2022 |
| Dell          | Latitude E6330              | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Acer          | Aspire V5-123               | [7e9ca0bb77](https://linux-hardware.org/?probe=7e9ca0bb77) | Nov 09, 2022 |
| HP            | ENVY 15                     | [716fe10a4a](https://linux-hardware.org/?probe=716fe10a4a) | Nov 09, 2022 |
| MSI           | GS60 6QE                    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| Lenovo        | V15-IIL 82C5                | [7f372be9dc](https://linux-hardware.org/?probe=7f372be9dc) | Nov 07, 2022 |
| Dell          | Inspiron 5379               | [f18d0b8b8a](https://linux-hardware.org/?probe=f18d0b8b8a) | Nov 06, 2022 |
| Dell          | Inspiron 5379               | [141de7e9a7](https://linux-hardware.org/?probe=141de7e9a7) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [3d53b3616f](https://linux-hardware.org/?probe=3d53b3616f) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [e5abd4f928](https://linux-hardware.org/?probe=e5abd4f928) | Nov 06, 2022 |
| Dell          | Latitude E6430              | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Dell          | Inspiron 5502               | [204c296466](https://linux-hardware.org/?probe=204c296466) | Nov 04, 2022 |
| ASUSTek       | X553MA                      | [d70f962654](https://linux-hardware.org/?probe=d70f962654) | Nov 04, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [ca5335acd5](https://linux-hardware.org/?probe=ca5335acd5) | Nov 03, 2022 |
| Dell          | Latitude 7280               | [ec1ac4ec28](https://linux-hardware.org/?probe=ec1ac4ec28) | Nov 03, 2022 |
| Acer          | Swift SF314-57              | [8ab3b70362](https://linux-hardware.org/?probe=8ab3b70362) | Nov 03, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [2b5c165e30](https://linux-hardware.org/?probe=2b5c165e30) | Nov 02, 2022 |
| Dell          | XPS 13 9305                 | [4ffebc50a0](https://linux-hardware.org/?probe=4ffebc50a0) | Nov 02, 2022 |
| Dell          | Precision 7530              | [b1b5f7678c](https://linux-hardware.org/?probe=b1b5f7678c) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Acer          | Aspire A515-46              | [ef6bcab217](https://linux-hardware.org/?probe=ef6bcab217) | Nov 01, 2022 |
| Lenovo        | ThinkPad L460 20FVS1Y500    | [5fc669ddbe](https://linux-hardware.org/?probe=5fc669ddbe) | Nov 01, 2022 |
| SANTECH       | NL5xRU                      | [63e1b4298d](https://linux-hardware.org/?probe=63e1b4298d) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | [6a28e2929d](https://linux-hardware.org/?probe=6a28e2929d) | Oct 31, 2022 |
| Lenovo        | ThinkPad T440p 20AW005BG... | [b25134edde](https://linux-hardware.org/?probe=b25134edde) | Oct 31, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [5355a5547a](https://linux-hardware.org/?probe=5355a5547a) | Oct 31, 2022 |
| Alienware     | 15 R3                       | [4659975000](https://linux-hardware.org/?probe=4659975000) | Oct 31, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | [0e06dcc642](https://linux-hardware.org/?probe=0e06dcc642) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | [41a0a441d3](https://linux-hardware.org/?probe=41a0a441d3) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| ASUSTek       | X541UV                      | [cef88d9d62](https://linux-hardware.org/?probe=cef88d9d62) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| Chuwi         | LapBook Pro                 | [d362ed14bf](https://linux-hardware.org/?probe=d362ed14bf) | Oct 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Manjaro        | 1557      | 37.73%  |
| Manjaro 22.0.0 | 188       | 4.56%   |
| Manjaro 20.2.1 | 163       | 3.95%   |
| Manjaro 20.1   | 142       | 3.44%   |
| Manjaro 20.2   | 140       | 3.39%   |
| Manjaro 20.0.3 | 125       | 3.03%   |
| Manjaro 21.2.6 | 113       | 2.74%   |
| Manjaro 21.1.0 | 89        | 2.16%   |
| Manjaro 18.1.5 | 83        | 2.01%   |
| Manjaro 23.0.0 | 75        | 1.82%   |
| Manjaro 21.2.0 | 72        | 1.74%   |
| Manjaro 21.0.7 | 70        | 1.7%    |
| Manjaro 21.2.5 | 65        | 1.57%   |
| Manjaro 21.1.6 | 63        | 1.53%   |
| Manjaro 19.0.2 | 55        | 1.33%   |
| Manjaro 20.0   | 52        | 1.26%   |
| Manjaro 21.2.1 | 48        | 1.16%   |
| Manjaro 18.0.4 | 47        | 1.14%   |
| Manjaro 21.0   | 46        | 1.11%   |
| Manjaro 21.0.5 | 44        | 1.07%   |
| Manjaro 22.1.0 | 41        | 0.99%   |
| Manjaro 20.1.1 | 41        | 0.99%   |
| Manjaro 20.1.2 | 40        | 0.97%   |
| Manjaro 22.0.4 | 37        | 0.9%    |
| Manjaro 21.2.3 | 37        | 0.9%    |
| Manjaro 20.0.1 | 36        | 0.87%   |
| Manjaro 21.3.7 | 34        | 0.82%   |
| Manjaro 21.2.2 | 31        | 0.75%   |
| Manjaro 21.0.4 | 31        | 0.75%   |
| Manjaro 21.3.6 | 29        | 0.7%    |
| Manjaro 21.2.4 | 29        | 0.7%    |
| Manjaro 21.1.2 | 25        | 0.61%   |
| Manjaro 21.1.4 | 24        | 0.58%   |
| Manjaro 22.0.5 | 23        | 0.56%   |
| Manjaro 21.0.1 | 20        | 0.48%   |
| Manjaro 18.1.4 | 20        | 0.48%   |
| Manjaro 21.3.1 | 19        | 0.46%   |
| Manjaro 21.3.0 | 19        | 0.46%   |
| Manjaro 21.1.3 | 19        | 0.46%   |
| Manjaro 21.1.1 | 19        | 0.46%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Manjaro | 3784      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 161       | 3.62%   |
| 5.13.19-2-MANJARO | 95        | 2.14%   |
| 5.9.11-3-MANJARO  | 73        | 1.64%   |
| 5.8.11-1-MANJARO  | 69        | 1.55%   |
| 5.8.6-1-MANJARO   | 68        | 1.53%   |
| 5.15.32-1-MANJARO | 63        | 1.42%   |
| 5.15.28-1-MANJARO | 61        | 1.37%   |
| 5.10.42-1-MANJARO | 57        | 1.28%   |
| 5.8.18-1-MANJARO  | 55        | 1.24%   |
| 5.15.12-1-MANJARO | 52        | 1.17%   |
| 6.1.1-1-MANJARO   | 51        | 1.15%   |
| 6.1.12-1-MANJARO  | 49        | 1.1%    |
| 6.1.31-2-MANJARO  | 48        | 1.08%   |
| 5.8.16-2-MANJARO  | 41        | 0.92%   |
| 5.15.65-1-MANJARO | 40        | 0.9%    |
| 5.10.2-2-MANJARO  | 40        | 0.9%    |
| 5.6.16-1-MANJARO  | 39        | 0.88%   |
| 5.15.60-1-MANJARO | 39        | 0.88%   |
| 5.10.7-3-MANJARO  | 38        | 0.85%   |
| 5.12.9-1-MANJARO  | 36        | 0.81%   |
| 5.6.19-2-MANJARO  | 33        | 0.74%   |
| 5.15.74-3-MANJARO | 31        | 0.7%    |
| 5.15.7-1-MANJARO  | 31        | 0.7%    |
| 5.7.9-1-MANJARO   | 30        | 0.67%   |
| 5.6.15-1-MANJARO  | 30        | 0.67%   |
| 5.15.81-1-MANJARO | 30        | 0.67%   |
| 5.15.78-1-MANJARO | 30        | 0.67%   |
| 5.15.41-1-MANJARO | 30        | 0.67%   |
| 5.10.36-2-MANJARO | 30        | 0.67%   |
| 5.7.17-2-MANJARO  | 29        | 0.65%   |
| 5.7.0-3-MANJARO   | 29        | 0.65%   |
| 5.8.3-2-MANJARO   | 28        | 0.63%   |
| 5.15.25-1-MANJARO | 28        | 0.63%   |
| 5.14.10-1-MANJARO | 28        | 0.63%   |
| 5.10.34-1-MANJARO | 27        | 0.61%   |
| 5.16.14-1-MANJARO | 25        | 0.56%   |
| 5.15.85-1-MANJARO | 25        | 0.56%   |
| 5.10.70-1-MANJARO | 25        | 0.56%   |
| 5.10.53-1-MANJARO | 25        | 0.56%   |
| 6.1.26-1-MANJARO  | 23        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.16  | 161       | 3.62%   |
| 5.13.19 | 96        | 2.16%   |
| 5.9.11  | 77        | 1.73%   |
| 5.8.11  | 69        | 1.55%   |
| 5.8.6   | 68        | 1.53%   |
| 5.15.32 | 64        | 1.44%   |
| 5.15.28 | 61        | 1.37%   |
| 5.10.42 | 57        | 1.28%   |
| 5.8.18  | 55        | 1.24%   |
| 6.1.31  | 53        | 1.19%   |
| 5.15.12 | 52        | 1.17%   |
| 6.1.1   | 51        | 1.15%   |
| 6.1.12  | 49        | 1.1%    |
| 5.8.16  | 42        | 0.94%   |
| 5.15.65 | 40        | 0.9%    |
| 5.10.2  | 40        | 0.9%    |
| 5.6.16  | 39        | 0.88%   |
| 5.15.60 | 39        | 0.88%   |
| 5.10.7  | 39        | 0.88%   |
| 5.7.0   | 36        | 0.81%   |
| 5.12.9  | 36        | 0.81%   |
| 5.6.19  | 35        | 0.79%   |
| 5.9.1   | 33        | 0.74%   |
| 5.15.74 | 32        | 0.72%   |
| 5.15.7  | 32        | 0.72%   |
| 5.7.9   | 30        | 0.67%   |
| 5.6.15  | 30        | 0.67%   |
| 5.17.1  | 30        | 0.67%   |
| 5.15.81 | 30        | 0.67%   |
| 5.15.78 | 30        | 0.67%   |
| 5.15.41 | 30        | 0.67%   |
| 5.10.36 | 30        | 0.67%   |
| 5.7.17  | 29        | 0.65%   |
| 5.8.3   | 28        | 0.63%   |
| 5.15.25 | 28        | 0.63%   |
| 5.14.10 | 28        | 0.63%   |
| 5.10.34 | 27        | 0.61%   |
| 5.19.0  | 26        | 0.58%   |
| 5.16.14 | 25        | 0.56%   |
| 5.15.85 | 25        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 717       | 17.13%  |
| 5.10    | 505       | 12.06%  |
| 5.4     | 358       | 8.55%   |
| 6.1     | 347       | 8.29%   |
| 5.9     | 322       | 7.69%   |
| 5.8     | 291       | 6.95%   |
| 5.13    | 204       | 4.87%   |
| 5.6     | 199       | 4.75%   |
| 5.7     | 137       | 3.27%   |
| 4.19    | 121       | 2.89%   |
| 5.16    | 99        | 2.37%   |
| 5.12    | 94        | 2.25%   |
| 6.0     | 81        | 1.94%   |
| 5.11    | 81        | 1.94%   |
| 5.14    | 77        | 1.84%   |
| 5.19    | 74        | 1.77%   |
| 5.18    | 70        | 1.67%   |
| 5.17    | 70        | 1.67%   |
| 5.3     | 64        | 1.53%   |
| 5.5     | 62        | 1.48%   |
| 6.2     | 45        | 1.08%   |
| 6.3     | 42        | 1%      |
| 6.4     | 28        | 0.67%   |
| 4.14    | 25        | 0.6%    |
| 5.2     | 23        | 0.55%   |
| 5.0     | 17        | 0.41%   |
| 5.1     | 13        | 0.31%   |
| 4.20    | 9         | 0.22%   |
| 4.18    | 7         | 0.17%   |
| 4.9     | 2         | 0.05%   |
| 6.5     | 1         | 0.02%   |
| 4.16    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3782      | 99.95%  |
| i686   | 2         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| KDE5                 | 1414      | 36.33%  |
| GNOME                | 837       | 21.51%  |
| XFCE                 | 832       | 21.38%  |
| KDE                  | 277       | 7.12%   |
| Unknown              | 200       | 5.14%   |
| X-Cinnamon           | 85        | 2.18%   |
| i3                   | 82        | 2.11%   |
| MATE                 | 42        | 1.08%   |
| Cinnamon             | 30        | 0.77%   |
| Deepin               | 25        | 0.64%   |
| Budgie               | 15        | 0.39%   |
| Awesome              | 11        | 0.28%   |
| sway                 | 8         | 0.21%   |
| LXQt                 | 8         | 0.21%   |
| LXDE                 | 6         | 0.15%   |
| i3-with-shmlog       | 3         | 0.08%   |
| leftwm               | 2         | 0.05%   |
| GNOME Flashback      | 2         | 0.05%   |
| DWM                  | 2         | 0.05%   |
| Bspwm                | 2         | 0.05%   |
| Yaru:ubuntu:GNOME    | 1         | 0.03%   |
| xinitrc              | 1         | 0.03%   |
| Unity                | 1         | 0.03%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.03%   |
| qtile                | 1         | 0.03%   |
| Hyprland             | 1         | 0.03%   |
| herbstluftwm         | 1         | 0.03%   |
| GNOME Classic        | 1         | 0.03%   |
| Enlightenment        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3163      | 82.33%  |
| Wayland | 553       | 14.39%  |
| Unknown | 92        | 2.39%   |
| Tty     | 34        | 0.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1545      | 39.91%  |
| SDDM    | 989       | 25.55%  |
| LightDM | 682       | 17.62%  |
| GDM     | 518       | 13.38%  |
| TDM     | 123       | 3.18%   |
| LXDM    | 5         | 0.13%   |
| GREETD  | 4         | 0.1%    |
| Ly      | 2         | 0.05%   |
| XDM     | 1         | 0.03%   |
| SLiM    | 1         | 0.03%   |
| CDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1627      | 42.51%  |
| de_DE   | 279       | 7.29%   |
| ru_RU   | 267       | 6.98%   |
| en_GB   | 256       | 6.69%   |
| Unknown | 247       | 6.45%   |
| pt_BR   | 164       | 4.29%   |
| fr_FR   | 99        | 2.59%   |
| it_IT   | 82        | 2.14%   |
| es_ES   | 74        | 1.93%   |
| pl_PL   | 67        | 1.75%   |
| en_CA   | 65        | 1.7%    |
| en_IN   | 57        | 1.49%   |
| es_MX   | 43        | 1.12%   |
| en_AU   | 40        | 1.05%   |
| zh_CN   | 34        | 0.89%   |
| de_AT   | 22        | 0.57%   |
| ru_UA   | 20        | 0.52%   |
| nl_NL   | 18        | 0.47%   |
| C       | 18        | 0.47%   |
| es_AR   | 16        | 0.42%   |
| en_IE   | 16        | 0.42%   |
| pt_PT   | 15        | 0.39%   |
| tr_TR   | 14        | 0.37%   |
| es_CL   | 14        | 0.37%   |
| en_DK   | 13        | 0.34%   |
| cs_CZ   | 13        | 0.34%   |
| uk_UA   | 11        | 0.29%   |
| sv_SE   | 11        | 0.29%   |
| es_CO   | 11        | 0.29%   |
| hu_HU   | 10        | 0.26%   |
| fi_FI   | 10        | 0.26%   |
| en_ZA   | 10        | 0.26%   |
| en_NZ   | 10        | 0.26%   |
| de_CH   | 10        | 0.26%   |
| el_GR   | 9         | 0.24%   |
| nl_BE   | 8         | 0.21%   |
| zh_TW   | 7         | 0.18%   |
| en_PH   | 7         | 0.18%   |
| en_IL   | 7         | 0.18%   |
| en_DE   | 7         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1980      | 51.56%  |
| EFI  | 1860      | 48.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3176      | 83.23%  |
| Btrfs    | 371       | 9.72%   |
| Overlay  | 86        | 2.25%   |
| Unknown  | 82        | 2.15%   |
| Tmpfs    | 44        | 1.15%   |
| Xfs      | 37        | 0.97%   |
| F2fs     | 11        | 0.29%   |
| Reiserfs | 3         | 0.08%   |
| Ext3     | 3         | 0.08%   |
| Ext2     | 2         | 0.05%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1866      | 48.45%  |
| Unknown | 1668      | 43.31%  |
| MBR     | 317       | 8.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3448      | 90.05%  |
| Yes       | 381       | 9.95%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2730      | 71.09%  |
| Yes       | 1110      | 28.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 937       | 24.76%  |
| Hewlett-Packard      | 645       | 17.05%  |
| Dell                 | 566       | 14.96%  |
| ASUSTek Computer     | 460       | 12.16%  |
| Acer                 | 310       | 8.19%   |
| MSI                  | 110       | 2.91%   |
| Apple                | 94        | 2.48%   |
| HUAWEI               | 65        | 1.72%   |
| Toshiba              | 63        | 1.66%   |
| Samsung Electronics  | 60        | 1.59%   |
| Timi                 | 39        | 1.03%   |
| Sony                 | 33        | 0.87%   |
| Fujitsu              | 31        | 0.82%   |
| Notebook             | 29        | 0.77%   |
| Google               | 29        | 0.77%   |
| TUXEDO               | 22        | 0.58%   |
| Unknown              | 22        | 0.58%   |
| Razer                | 15        | 0.4%    |
| Alienware            | 14        | 0.37%   |
| Schenker             | 13        | 0.34%   |
| HONOR                | 12        | 0.32%   |
| LG Electronics       | 11        | 0.29%   |
| Packard Bell         | 10        | 0.26%   |
| Positivo             | 9         | 0.24%   |
| Gigabyte Technology  | 9         | 0.24%   |
| Chuwi                | 9         | 0.24%   |
| System76             | 8         | 0.21%   |
| Medion               | 8         | 0.21%   |
| Panasonic            | 7         | 0.18%   |
| Framework            | 7         | 0.18%   |
| Clevo                | 7         | 0.18%   |
| Monster              | 6         | 0.16%   |
| Multilaser           | 5         | 0.13%   |
| GPD                  | 5         | 0.13%   |
| Star Labs            | 4         | 0.11%   |
| PC Specialist        | 4         | 0.11%   |
| MECHREVO             | 4         | 0.11%   |
| Intel Client Systems | 4         | 0.11%   |
| TrekStor             | 3         | 0.08%   |
| Teclast              | 3         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 32        | 0.85%   |
| HP Notebook                          | 22        | 0.58%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 14        | 0.37%   |
| Lenovo Legion 5 15ARH05 82B5         | 13        | 0.34%   |
| Dell XPS 15 9500                     | 13        | 0.34%   |
| Dell XPS 13 9310                     | 13        | 0.34%   |
| HP Pavilion Notebook                 | 12        | 0.32%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 11        | 0.29%   |
| HP Pavilion dv7                      | 10        | 0.26%   |
| HP Laptop 15-bs0xx                   | 10        | 0.26%   |
| Dell XPS 15 7590                     | 10        | 0.26%   |
| Dell Inspiron 3542                   | 10        | 0.26%   |
| HP Pavilion g6                       | 9         | 0.24%   |
| HP Pavilion dv6                      | 9         | 0.24%   |
| HP Pavilion 15                       | 9         | 0.24%   |
| Dell XPS 15 9570                     | 9         | 0.24%   |
| Dell XPS 15 9560                     | 9         | 0.24%   |
| Dell XPS 13 7390                     | 9         | 0.24%   |
| Lenovo Y520-15IKBN 80WK              | 8         | 0.21%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 8         | 0.21%   |
| HP OMEN by Laptop                    | 8         | 0.21%   |
| HP 15                                | 8         | 0.21%   |
| Dell Latitude E6430                  | 8         | 0.21%   |
| Dell Inspiron N5110                  | 8         | 0.21%   |
| ASUS TUF Gaming FX505DT_FX505DT      | 8         | 0.21%   |
| Apple MacBookPro9,2                  | 8         | 0.21%   |
| Apple MacBookAir7,2                  | 8         | 0.21%   |
| Timi TM1701                          | 7         | 0.18%   |
| Lenovo Z50-70 20354                  | 7         | 0.18%   |
| Lenovo Yoga Slim 7 14ARE05 82A2      | 7         | 0.18%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 7         | 0.18%   |
| HUAWEI NBLK-WAX9X                    | 7         | 0.18%   |
| HUAWEI KLVL-WXX9                     | 7         | 0.18%   |
| HP Laptop 15s-eq2xxx                 | 7         | 0.18%   |
| HP 250 G7 Notebook PC                | 7         | 0.18%   |
| Dell Latitude E6400                  | 7         | 0.18%   |
| Dell Latitude 5480                   | 7         | 0.18%   |
| Dell G3 3590                         | 7         | 0.18%   |
| Apple MacBookPro8,1                  | 7         | 0.18%   |
| Apple MacBookPro15,1                 | 7         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 433       | 11.44%  |
| Lenovo IdeaPad        | 254       | 6.71%   |
| Acer Aspire           | 198       | 5.23%   |
| Dell Inspiron         | 179       | 4.73%   |
| Dell Latitude         | 149       | 3.94%   |
| HP Pavilion           | 145       | 3.83%   |
| Dell XPS              | 108       | 2.85%   |
| HP Laptop             | 103       | 2.72%   |
| HP ProBook            | 97        | 2.56%   |
| HP EliteBook          | 97        | 2.56%   |
| ASUS VivoBook         | 80        | 2.11%   |
| Lenovo Legion         | 71        | 1.88%   |
| ASUS ROG              | 57        | 1.51%   |
| Toshiba Satellite     | 56        | 1.48%   |
| Dell Precision        | 46        | 1.22%   |
| Dell Vostro           | 41        | 1.08%   |
| Acer Swift            | 38        | 1%      |
| ASUS ZenBook          | 33        | 0.87%   |
| ASUS TUF              | 32        | 0.85%   |
| Acer Nitro            | 32        | 0.85%   |
| Unknown               | 32        | 0.85%   |
| HP OMEN               | 29        | 0.77%   |
| Lenovo ThinkBook      | 27        | 0.71%   |
| Fujitsu LIFEBOOK      | 27        | 0.71%   |
| HP ENVY               | 26        | 0.69%   |
| ASUS ASUS             | 26        | 0.69%   |
| HP ZBook              | 22        | 0.58%   |
| HP Notebook           | 22        | 0.58%   |
| Lenovo Yoga           | 21        | 0.55%   |
| HP 250                | 20        | 0.53%   |
| Timi RedmiBook        | 16        | 0.42%   |
| HP Compaq             | 16        | 0.42%   |
| Dell G3               | 15        | 0.4%    |
| Acer TravelMate       | 15        | 0.4%    |
| Razer Blade           | 14        | 0.37%   |
| Apple MacBookPro11    | 14        | 0.37%   |
| HP 15                 | 13        | 0.34%   |
| Acer Predator         | 13        | 0.34%   |
| HP 255                | 12        | 0.32%   |
| Packard Bell EasyNote | 10        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 505       | 13.35%  |
| 2020    | 492       | 13%     |
| 2018    | 392       | 10.36%  |
| 2021    | 360       | 9.51%   |
| 2017    | 302       | 7.98%   |
| 2012    | 272       | 7.19%   |
| 2015    | 216       | 5.71%   |
| 2013    | 214       | 5.66%   |
| 2014    | 212       | 5.6%    |
| 2011    | 200       | 5.29%   |
| 2016    | 199       | 5.26%   |
| 2022    | 120       | 3.17%   |
| 2010    | 114       | 3.01%   |
| 2008    | 76        | 2.01%   |
| 2009    | 55        | 1.45%   |
| 2007    | 27        | 0.71%   |
| 2023    | 15        | 0.4%    |
| 2006    | 8         | 0.21%   |
| Unknown | 4         | 0.11%   |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3784      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3782      | 99.89%  |
| Enabled  | 4         | 0.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3737      | 98.76%  |
| Yes  | 47        | 1.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1155      | 30.19%  |
| 16.01-24.0  | 819       | 21.41%  |
| 8.01-16.0   | 790       | 20.65%  |
| 3.01-4.0    | 543       | 14.19%  |
| 32.01-64.0  | 304       | 7.95%   |
| 24.01-32.0  | 71        | 1.86%   |
| 1.01-2.0    | 68        | 1.78%   |
| 64.01-256.0 | 47        | 1.23%   |
| 2.01-3.0    | 28        | 0.73%   |
| 0.51-1.0    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1160      | 27.74%  |
| 1.01-2.0   | 1039      | 24.84%  |
| 4.01-8.0   | 846       | 20.23%  |
| 3.01-4.0   | 729       | 17.43%  |
| 8.01-16.0  | 238       | 5.69%   |
| 0.51-1.0   | 138       | 3.3%    |
| 16.01-24.0 | 17        | 0.41%   |
| 24.01-32.0 | 7         | 0.17%   |
| 0.01-0.5   | 7         | 0.17%   |
| 32.01-64.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2616      | 67.86%  |
| 2      | 1067      | 27.68%  |
| 3      | 135       | 3.5%    |
| 0      | 19        | 0.49%   |
| 4      | 15        | 0.39%   |
| 7      | 2         | 0.05%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2835      | 74.51%  |
| Yes       | 970       | 25.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2892      | 76.19%  |
| No        | 904       | 23.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3742      | 98.79%  |
| No        | 46        | 1.21%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3126      | 82%     |
| No        | 686       | 18%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 551       | 14.45%  |
| Germany     | 418       | 10.96%  |
| Russia      | 349       | 9.15%   |
| Brazil      | 239       | 6.27%   |
| France      | 143       | 3.75%   |
| UK          | 132       | 3.46%   |
| Italy       | 128       | 3.36%   |
| Poland      | 114       | 2.99%   |
| Canada      | 103       | 2.7%    |
| Spain       | 102       | 2.68%   |
| India       | 99        | 2.6%    |
| Netherlands | 97        | 2.54%   |
| Ukraine     | 89        | 2.33%   |
| Mexico      | 66        | 1.73%   |
| China       | 54        | 1.42%   |
| Austria     | 52        | 1.36%   |
| Turkey      | 48        | 1.26%   |
| Australia   | 48        | 1.26%   |
| Sweden      | 40        | 1.05%   |
| Indonesia   | 39        | 1.02%   |
| Romania     | 36        | 0.94%   |
| Belgium     | 35        | 0.92%   |
| Switzerland | 34        | 0.89%   |
| Portugal    | 34        | 0.89%   |
| Czechia     | 33        | 0.87%   |
| Belarus     | 30        | 0.79%   |
| Hungary     | 29        | 0.76%   |
| Finland     | 27        | 0.71%   |
| Greece      | 26        | 0.68%   |
| Bulgaria    | 25        | 0.66%   |
| Norway      | 24        | 0.63%   |
| Argentina   | 24        | 0.63%   |
| Colombia    | 23        | 0.6%    |
| Denmark     | 22        | 0.58%   |
| Taiwan      | 21        | 0.55%   |
| Chile       | 19        | 0.5%    |
| Iran        | 18        | 0.47%   |
| Bangladesh  | 18        | 0.47%   |
| Croatia     | 17        | 0.45%   |
| Japan       | 16        | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 86        | 2.14%   |
| St Petersburg     | 50        | 1.24%   |
| Vienna            | 37        | 0.92%   |
| Paris             | 33        | 0.82%   |
| Berlin            | 32        | 0.8%    |
| Sao Paulo         | 29        | 0.72%   |
| Kyiv              | 26        | 0.65%   |
| Amsterdam         | 26        | 0.65%   |
| Warsaw            | 21        | 0.52%   |
| Milan             | 21        | 0.52%   |
| Frankfurt am Main | 20        | 0.5%    |
| Munich            | 19        | 0.47%   |
| Bengaluru         | 19        | 0.47%   |
| Toronto           | 18        | 0.45%   |
| Istanbul          | 18        | 0.45%   |
| Minsk             | 17        | 0.42%   |
| Prague            | 16        | 0.4%    |
| Novosibirsk       | 16        | 0.4%    |
| Helsinki          | 16        | 0.4%    |
| Rome              | 15        | 0.37%   |
| Mexico City       | 15        | 0.37%   |
| Madrid            | 15        | 0.37%   |
| London            | 15        | 0.37%   |
| Hamburg           | 15        | 0.37%   |
| Melbourne         | 14        | 0.35%   |
| Budapest          | 14        | 0.35%   |
| Bucharest         | 14        | 0.35%   |
| Barcelona         | 13        | 0.32%   |
| Yekaterinburg     | 12        | 0.3%    |
| Dhaka             | 12        | 0.3%    |
| Cologne           | 12        | 0.3%    |
| Brasília         | 12        | 0.3%    |
| Athens            | 12        | 0.3%    |
| Zagreb            | 11        | 0.27%   |
| The Hague         | 11        | 0.27%   |
| Sydney            | 11        | 0.27%   |
| Sofia             | 11        | 0.27%   |
| Seattle           | 11        | 0.27%   |
| Krasnodar         | 11        | 0.27%   |
| Bogotá           | 11        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 879       | 1164   | 17.66%  |
| WDC                            | 529       | 637    | 10.63%  |
| Seagate                        | 485       | 626    | 9.75%   |
| Toshiba                        | 370       | 432    | 7.44%   |
| SanDisk                        | 335       | 425    | 6.73%   |
| Kingston                       | 265       | 308    | 5.33%   |
| SK hynix                       | 252       | 308    | 5.06%   |
| Unknown                        | 250       | 304    | 5.02%   |
| Intel                          | 171       | 215    | 3.44%   |
| Crucial                        | 170       | 212    | 3.42%   |
| HGST                           | 146       | 174    | 2.93%   |
| Micron Technology              | 141       | 178    | 2.83%   |
| Hitachi                        | 90        | 105    | 1.81%   |
| KIOXIA                         | 64        | 74     | 1.29%   |
| A-DATA Technology              | 60        | 73     | 1.21%   |
| Apple                          | 59        | 72     | 1.19%   |
| Phison                         | 45        | 66     | 0.9%    |
| China                          | 45        | 48     | 0.9%    |
| Transcend                      | 32        | 38     | 0.64%   |
| Micron/Crucial Technology      | 30        | 37     | 0.6%    |
| Phison Electronics             | 27        | 28     | 0.54%   |
| LITEONIT                       | 26        | 32     | 0.52%   |
| GOODRAM                        | 26        | 45     | 0.52%   |
| LITEON                         | 25        | 28     | 0.5%    |
| Silicon Motion                 | 24        | 28     | 0.48%   |
| JMicron Technology             | 19        | 20     | 0.38%   |
| Kingston Technology Company    | 15        | 15     | 0.3%    |
| SPCC                           | 14        | 16     | 0.28%   |
| Plextor                        | 14        | 22     | 0.28%   |
| Intenso                        | 13        | 14     | 0.26%   |
| Unknown                        | 13        | 16     | 0.26%   |
| Union Memory (Shenzhen)        | 12        | 12     | 0.24%   |
| Patriot                        | 12        | 12     | 0.24%   |
| ADATA Technology               | 12        | 14     | 0.24%   |
| Solid State Storage Technology | 11        | 18     | 0.22%   |
| Fujitsu                        | 10        | 10     | 0.2%    |
| XPG                            | 9         | 15     | 0.18%   |
| PNY                            | 9         | 13     | 0.18%   |
| Netac                          | 9         | 15     | 0.18%   |
| Hewlett-Packard                | 9         | 13     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 94        | 1.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 74        | 1.42%   |
| Samsung NVMe SSD Drive 512GB                        | 65        | 1.25%   |
| HGST HTS721010A9E630 1TB                            | 54        | 1.04%   |
| Toshiba MQ01ABD100 1TB                              | 53        | 1.02%   |
| Toshiba MQ04ABF100 1TB                              | 52        | 1%      |
| SK hynix NVMe SSD Drive 512GB                       | 46        | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 44        | 0.85%   |
| SanDisk NVMe SSD Drive 512GB                        | 43        | 0.83%   |
| Samsung NVMe SSD Drive 256GB                        | 43        | 0.83%   |
| Kingston SA400S37240G 240GB SSD                     | 40        | 0.77%   |
| Toshiba MQ01ABF050 500GB                            | 37        | 0.71%   |
| Unknown MMC Card  32GB                              | 36        | 0.69%   |
| Unknown MMC Card  64GB                              | 35        | 0.67%   |
| Intel NVMe SSD Drive 512GB                          | 30        | 0.58%   |
| Samsung NVMe SSD Drive 1TB                          | 29        | 0.56%   |
| Unknown SD/MMC/MS PRO 128GB                         | 28        | 0.54%   |
| Crucial CT500MX500SSD1 500GB                        | 28        | 0.54%   |
| SanDisk NVMe SSD Drive 256GB                        | 26        | 0.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 26        | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                     | 25        | 0.48%   |
| Seagate ST1000LM049-2GH172 1TB                      | 25        | 0.48%   |
| Samsung SSD 850 EVO 500GB                           | 24        | 0.46%   |
| Kingston SA400S37480G 480GB SSD                     | 24        | 0.46%   |
| Kingston SA400S37120G 120GB SSD                     | 24        | 0.46%   |
| HGST HTS545050A7E680 500GB                          | 24        | 0.46%   |
| Samsung SSD 860 EVO 500GB                           | 23        | 0.44%   |
| Samsung NVMe SSD Drive 1024GB                       | 23        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 23        | 0.44%   |
| SK hynix NVMe SSD Drive 256GB                       | 22        | 0.42%   |
| Seagate Expansion 1TB                               | 22        | 0.42%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 20        | 0.38%   |
| Seagate ST9500325AS 500GB                           | 20        | 0.38%   |
| WDC WD10SPZX-24Z10 1TB                              | 19        | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 19        | 0.37%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 19        | 0.37%   |
| SanDisk NVMe SSD Drive 1TB                          | 19        | 0.37%   |
| Micron NVMe SSD Drive 512GB                         | 19        | 0.37%   |
| Kingston NVMe SSD Drive 512GB                       | 19        | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 18        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 471       | 603    | 34.28%  |
| WDC                 | 343       | 405    | 24.96%  |
| Toshiba             | 235       | 272    | 17.1%   |
| HGST                | 146       | 174    | 10.63%  |
| Hitachi             | 90        | 105    | 6.55%   |
| Unknown             | 30        | 33     | 2.18%   |
| Samsung Electronics | 15        | 17     | 1.09%   |
| Fujitsu             | 10        | 10     | 0.73%   |
| JMicron Technology  | 9         | 9      | 0.66%   |
| Apple               | 5         | 6      | 0.36%   |
| USB3.0              | 2         | 2      | 0.15%   |
| SSK                 | 2         | 3      | 0.15%   |
| Intenso             | 2         | 2      | 0.15%   |
| ASMT                | 2         | 2      | 0.15%   |
| QNAP                | 1         | 1      | 0.07%   |
| Pioneer             | 1         | 3      | 0.07%   |
| PHD 3.0             | 1         | 1      | 0.07%   |
| MARSHAL             | 1         | 1      | 0.07%   |
| KESU                | 1         | 1      | 0.07%   |
| Inateck             | 1         | 1      | 0.07%   |
| Hewlett-Packard     | 1         | 1      | 0.07%   |
| External            | 1         | 1      | 0.07%   |
| ASMedia             | 1         | 3      | 0.07%   |
| Apricorn            | 1         | 1      | 0.07%   |
| ACASIS              | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 352       | 441    | 22.99%  |
| Kingston            | 192       | 217    | 12.54%  |
| Crucial             | 157       | 199    | 10.25%  |
| SanDisk             | 131       | 173    | 8.56%   |
| WDC                 | 90        | 108    | 5.88%   |
| Micron Technology   | 55        | 70     | 3.59%   |
| SK hynix            | 45        | 55     | 2.94%   |
| China               | 45        | 48     | 2.94%   |
| A-DATA Technology   | 45        | 53     | 2.94%   |
| Apple               | 39        | 44     | 2.55%   |
| Intel               | 38        | 44     | 2.48%   |
| Toshiba             | 33        | 37     | 2.16%   |
| Transcend           | 30        | 35     | 1.96%   |
| LITEONIT            | 26        | 32     | 1.7%    |
| GOODRAM             | 25        | 44     | 1.63%   |
| LITEON              | 22        | 25     | 1.44%   |
| Plextor             | 13        | 21     | 0.85%   |
| Patriot             | 11        | 11     | 0.72%   |
| Intenso             | 11        | 12     | 0.72%   |
| SPCC                | 9         | 10     | 0.59%   |
| Netac               | 9         | 15     | 0.59%   |
| PNY                 | 8         | 12     | 0.52%   |
| OCZ                 | 8         | 9      | 0.52%   |
| KingSpec            | 8         | 9      | 0.52%   |
| Unknown             | 7         | 10     | 0.46%   |
| Seagate             | 6         | 10     | 0.39%   |
| Hewlett-Packard     | 5         | 8      | 0.33%   |
| Corsair             | 5         | 5      | 0.33%   |
| Apacer              | 5         | 5      | 0.33%   |
| TO Exter            | 4         | 5      | 0.26%   |
| Lexar               | 4         | 4      | 0.26%   |
| FORESEE             | 4         | 4      | 0.26%   |
| TwinMOS             | 3         | 5      | 0.2%    |
| Team                | 3         | 4      | 0.2%    |
| Mushkin             | 3         | 5      | 0.2%    |
| Gigabyte Technology | 3         | 4      | 0.2%    |
| Vaseky              | 2         | 2      | 0.13%   |
| Unknown             | 2         | 3      | 0.13%   |
| Teclast             | 2         | 4      | 0.13%   |
| Phison              | 2         | 5      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1677      | 2293   | 35.67%  |
| SSD     | 1428      | 1890   | 30.38%  |
| HDD     | 1320      | 1659   | 28.08%  |
| MMC     | 207       | 255    | 4.4%    |
| Unknown | 69        | 79     | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2361      | 3388   | 53.22%  |
| NVMe | 1676      | 2279   | 37.78%  |
| MMC  | 207       | 255    | 4.67%   |
| SAS  | 192       | 254    | 4.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1664      | 2222   | 61.36%  |
| 0.51-1.0   | 942       | 1179   | 34.73%  |
| 1.01-2.0   | 80        | 101    | 2.95%   |
| 4.01-10.0  | 15        | 22     | 0.55%   |
| 3.01-4.0   | 9         | 23     | 0.33%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |
| 10.01-20.0 | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1041      | 26.54%  |
| 251-500        | 1014      | 25.85%  |
| 501-1000       | 622       | 15.86%  |
| 1001-2000      | 324       | 8.26%   |
| Unknown        | 288       | 7.34%   |
| 51-100         | 248       | 6.32%   |
| 1-20           | 136       | 3.47%   |
| 21-50          | 115       | 2.93%   |
| More than 3000 | 73        | 1.86%   |
| 2001-3000      | 62        | 1.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 946       | 23.08%  |
| 21-50          | 776       | 18.94%  |
| 101-250        | 691       | 16.86%  |
| 51-100         | 614       | 14.98%  |
| 251-500        | 424       | 10.35%  |
| Unknown        | 288       | 7.03%   |
| 501-1000       | 242       | 5.91%   |
| 1001-2000      | 80        | 1.95%   |
| More than 3000 | 18        | 0.44%   |
| 2001-3000      | 16        | 0.39%   |
| 0              | 3         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 11     | 4.61%   |
| HGST HTS721010A9E630 1TB                            | 9         | 9      | 4.15%   |
| HGST HTS545050A7E680 500GB                          | 9         | 9      | 4.15%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 8      | 2.76%   |
| HGST HTS545050A7E380 500GB                          | 6         | 6      | 2.76%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 22     | 2.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 5      | 2.3%    |
| Seagate ST9320325AS 320GB                           | 4         | 5      | 1.84%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 1.84%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 1.38%   |
| Toshiba MQ01ABD050 500GB                            | 3         | 3      | 1.38%   |
| Seagate ST9500325AS 500GB                           | 3         | 4      | 1.38%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 1.38%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 1.38%   |
| Hitachi HTS723232A7A364 320GB                       | 3         | 3      | 1.38%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 1.38%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 3      | 0.92%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 2         | 2      | 0.92%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 0.92%   |
| Seagate ST9750420AS 752GB                           | 2         | 2      | 0.92%   |
| Seagate ST9500423AS 500GB                           | 2         | 2      | 0.92%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 2      | 0.92%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 5      | 0.92%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 2      | 0.92%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 2      | 0.92%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.92%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 0.92%   |
| Crucial CT525MX300SSD1 528GB                        | 2         | 2      | 0.92%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 1      | 0.46%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 0.46%   |
| WDC WD800BEVS-22RST0 80GB                           | 1         | 1      | 0.46%   |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 1      | 0.46%   |
| WDC WD5000LPVX-08V0TT5 500GB                        | 1         | 1      | 0.46%   |
| WDC WD5000LPLX-00ZNTT0 500GB                        | 1         | 1      | 0.46%   |
| WDC WD5000LPCX-22VHAT0 500GB                        | 1         | 1      | 0.46%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 1      | 0.46%   |
| WDC WD5000BPVT-60HXZT3 500GB                        | 1         | 1      | 0.46%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 1      | 0.46%   |
| WDC WD5000BEVT-75A0RT0 500GB                        | 1         | 1      | 0.46%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 1      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 83     | 25.46%  |
| HGST                | 33        | 33     | 15.28%  |
| WDC                 | 25        | 28     | 11.57%  |
| Toshiba             | 24        | 28     | 11.11%  |
| Hitachi             | 19        | 20     | 8.8%    |
| Samsung Electronics | 9         | 10     | 4.17%   |
| Crucial             | 9         | 12     | 4.17%   |
| SK hynix            | 6         | 10     | 2.78%   |
| SanDisk             | 6         | 6      | 2.78%   |
| Intel               | 5         | 6      | 2.31%   |
| Micron Technology   | 4         | 6      | 1.85%   |
| LITEON              | 3         | 3      | 1.39%   |
| Kingston            | 3         | 3      | 1.39%   |
| A-DATA Technology   | 3         | 4      | 1.39%   |
| TwinMOS             | 1         | 1      | 0.46%   |
| Realtek             | 1         | 1      | 0.46%   |
| Netac               | 1         | 1      | 0.46%   |
| MARSHAL             | 1         | 1      | 0.46%   |
| LITEONIT            | 1         | 1      | 0.46%   |
| KingSpec            | 1         | 1      | 0.46%   |
| IM3D                | 1         | 1      | 0.46%   |
| Faspeed             | 1         | 1      | 0.46%   |
| Corsair             | 1         | 1      | 0.46%   |
| ASMT                | 1         | 1      | 0.46%   |
| Apple               | 1         | 1      | 0.46%   |
| Unknown             | 1         | 1      | 0.46%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 83     | 35.95%  |
| HGST                | 33        | 33     | 21.57%  |
| WDC                 | 23        | 26     | 15.03%  |
| Toshiba             | 20        | 24     | 13.07%  |
| Hitachi             | 19        | 20     | 12.42%  |
| Samsung Electronics | 1         | 1      | 0.65%   |
| MARSHAL             | 1         | 1      | 0.65%   |
| ASMT                | 1         | 1      | 0.65%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 152       | 189    | 71.03%  |
| SSD  | 54        | 66     | 25.23%  |
| NVMe | 8         | 9      | 3.74%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 33.33%  |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 33.33%  |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2389      | 3732   | 58.71%  |
| Works    | 1467      | 2177   | 36.05%  |
| Malfunc  | 210       | 264    | 5.16%   |
| Failed   | 3         | 3      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2466      | 52.04%  |
| Samsung Electronics              | 574       | 12.11%  |
| AMD                              | 542       | 11.44%  |
| SanDisk                          | 294       | 6.2%    |
| SK hynix                         | 205       | 4.33%   |
| Toshiba America Info Systems     | 97        | 2.05%   |
| Kingston Technology Company      | 87        | 1.84%   |
| Micron Technology                | 85        | 1.79%   |
| Phison Electronics               | 76        | 1.6%    |
| KIOXIA                           | 72        | 1.52%   |
| Micron/Crucial Technology        | 42        | 0.89%   |
| ADATA Technology                 | 30        | 0.63%   |
| Union Memory (Shenzhen)          | 26        | 0.55%   |
| Silicon Motion                   | 26        | 0.55%   |
| Solid State Storage Technology   | 20        | 0.42%   |
| Nvidia                           | 19        | 0.4%    |
| Apple                            | 14        | 0.3%    |
| Realtek Semiconductor            | 11        | 0.23%   |
| Lite-On Technology               | 10        | 0.21%   |
| Shenzhen Longsys Electronics     | 8         | 0.17%   |
| Marvell Technology Group         | 6         | 0.13%   |
| Seagate Technology               | 5         | 0.11%   |
| Yangtze Memory Technologies      | 4         | 0.08%   |
| Lenovo                           | 4         | 0.08%   |
| Biwin Storage Technology         | 4         | 0.08%   |
| JMicron Technology               | 3         | 0.06%   |
| Transcend                        | 2         | 0.04%   |
| ASMedia Technology               | 2         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 503       | 10.17%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 338       | 6.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 310       | 6.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 262       | 5.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 225       | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 168       | 3.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 167       | 3.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 153       | 3.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 133       | 2.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 122       | 2.47%   |
| Samsung NVMe SSD Controller 980                                                | 118       | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 114       | 2.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 99        | 2%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 89        | 1.8%    |
| Intel SSD 660P Series                                                          | 70        | 1.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 64        | 1.29%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 62        | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 62        | 1.25%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 61        | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 59        | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 56        | 1.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 53        | 1.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 52        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 52        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 49        | 0.99%   |
| SK hynix BC511 NVMe SSD                                                        | 45        | 0.91%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 40        | 0.81%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 40        | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 40        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 40        | 0.81%   |
| Intel Tiger Lake-LP SATA Controller                                            | 39        | 0.79%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 36        | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 33        | 0.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 32        | 0.65%   |
| Phison E12 NVMe Controller                                                     | 31        | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 29        | 0.59%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 28        | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 28        | 0.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 26        | 0.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 26        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2647      | 55.61%  |
| NVMe | 1681      | 35.32%  |
| RAID | 328       | 6.89%   |
| IDE  | 104       | 2.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2935      | 77.56%  |
| AMD    | 849       | 22.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 83        | 2.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 70        | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 69        | 1.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 68        | 1.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 67        | 1.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 67        | 1.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 67        | 1.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 64        | 1.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 61        | 1.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 57        | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 54        | 1.43%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 54        | 1.43%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 52        | 1.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 49        | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 45        | 1.19%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 44        | 1.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 44        | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 41        | 1.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 40        | 1.06%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 36        | 0.95%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 34        | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 34        | 0.9%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 34        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 33        | 0.87%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.87%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 32        | 0.84%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 31        | 0.82%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 31        | 0.82%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 30        | 0.79%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 29        | 0.77%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 29        | 0.77%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 28        | 0.74%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 28        | 0.74%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 27        | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 0.66%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 25        | 0.66%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 24        | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 22        | 0.58%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 22        | 0.58%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 22        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 988       | 26.08%  |
| Intel Core i7                  | 983       | 25.94%  |
| Other                          | 283       | 7.47%   |
| AMD Ryzen 7                    | 266       | 7.02%   |
| Intel Core i3                  | 252       | 6.65%   |
| AMD Ryzen 5                    | 251       | 6.62%   |
| Intel Celeron                  | 147       | 3.88%   |
| Intel Core 2 Duo               | 95        | 2.51%   |
| Intel Pentium                  | 81        | 2.14%   |
| AMD Ryzen 3                    | 53        | 1.4%    |
| AMD Ryzen 9                    | 35        | 0.92%   |
| AMD Ryzen 7 PRO                | 35        | 0.92%   |
| AMD A6                         | 27        | 0.71%   |
| AMD A10                        | 26        | 0.69%   |
| Intel Core i9                  | 24        | 0.63%   |
| Intel Atom                     | 24        | 0.63%   |
| AMD A8                         | 23        | 0.61%   |
| Intel Pentium Silver           | 20        | 0.53%   |
| Intel Pentium Dual-Core        | 20        | 0.53%   |
| AMD A4                         | 20        | 0.53%   |
| AMD E1                         | 18        | 0.48%   |
| AMD E                          | 17        | 0.45%   |
| Intel Core 2                   | 11        | 0.29%   |
| AMD E2                         | 9         | 0.24%   |
| Intel Core m3                  | 7         | 0.18%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.18%   |
| AMD Ryzen 5 PRO                | 7         | 0.18%   |
| AMD Athlon                     | 7         | 0.18%   |
| AMD A12                        | 6         | 0.16%   |
| Intel Xeon                     | 4         | 0.11%   |
| Intel Genuine                  | 4         | 0.11%   |
| AMD FX                         | 4         | 0.11%   |
| Intel Core m7                  | 3         | 0.08%   |
| Intel Core m5                  | 3         | 0.08%   |
| AMD Athlon X2                  | 3         | 0.08%   |
| Intel Core M                   | 2         | 0.05%   |
| Intel Core 2 Quad              | 2         | 0.05%   |
| Intel Celeron Dual-Core        | 2         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.05%   |
| AMD Turion II                  | 2         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1601      | 42.29%  |
| 4       | 1396      | 36.87%  |
| 6       | 365       | 9.64%   |
| 8       | 339       | 8.95%   |
| 14      | 30        | 0.79%   |
| 12      | 21        | 0.55%   |
| 1       | 17        | 0.45%   |
| 10      | 10        | 0.26%   |
| 16      | 3         | 0.08%   |
| 3       | 3         | 0.08%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3784      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 3125      | 82.52%  |
| 1       | 661       | 17.45%  |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3721      | 98.28%  |
| Unknown        | 65        | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1909      | 48.85%  |
| 0x306a9    | 146       | 3.74%   |
| 0x906ea    | 119       | 3.05%   |
| 0x806ea    | 118       | 3.02%   |
| 0x806ec    | 105       | 2.69%   |
| 0x806c1    | 98        | 2.51%   |
| 0x806e9    | 81        | 2.07%   |
| 0x206a7    | 80        | 2.05%   |
| 0x406e3    | 74        | 1.89%   |
| 0x40651    | 73        | 1.87%   |
| 0x08108102 | 66        | 1.69%   |
| 0x306c3    | 61        | 1.56%   |
| 0x306d4    | 57        | 1.46%   |
| 0x0a50000c | 57        | 1.46%   |
| 0x08600106 | 56        | 1.43%   |
| 0x906e9    | 53        | 1.36%   |
| 0xa0652    | 47        | 1.2%    |
| 0x08108109 | 46        | 1.18%   |
| 0x08600103 | 44        | 1.13%   |
| 0x806eb    | 42        | 1.07%   |
| 0x706e5    | 40        | 1.02%   |
| 0x08600104 | 38        | 0.97%   |
| 0x08608103 | 33        | 0.84%   |
| 0x1067a    | 32        | 0.82%   |
| 0x20655    | 30        | 0.77%   |
| 0x506e3    | 28        | 0.72%   |
| 0x906a3    | 24        | 0.61%   |
| 0x30678    | 17        | 0.44%   |
| 0x806d1    | 16        | 0.41%   |
| 0x506c9    | 16        | 0.41%   |
| 0x0810100b | 16        | 0.41%   |
| 0x406c4    | 15        | 0.38%   |
| 0x06006705 | 15        | 0.38%   |
| 0x706a1    | 14        | 0.36%   |
| 0x0a404102 | 12        | 0.31%   |
| 0x0600611a | 12        | 0.31%   |
| 0x906ed    | 11        | 0.28%   |
| 0x08600102 | 11        | 0.28%   |
| 0x0a50000b | 10        | 0.26%   |
| 0x06001119 | 10        | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 924       | 24.4%   |
| Haswell          | 302       | 7.97%   |
| IvyBridge        | 274       | 7.24%   |
| Zen 2            | 218       | 5.76%   |
| Skylake          | 212       | 5.6%    |
| SandyBridge      | 211       | 5.57%   |
| Zen+             | 177       | 4.67%   |
| TigerLake        | 169       | 4.46%   |
| Unknown          | 153       | 4.04%   |
| Broadwell        | 147       | 3.88%   |
| Zen 3            | 128       | 3.38%   |
| Penryn           | 99        | 2.61%   |
| Westmere         | 95        | 2.51%   |
| CometLake        | 94        | 2.48%   |
| IceLake          | 88        | 2.32%   |
| Silvermont       | 85        | 2.24%   |
| Goldmont plus    | 61        | 1.61%   |
| Excavator        | 61        | 1.61%   |
| Zen              | 39        | 1.03%   |
| Core             | 37        | 0.98%   |
| Alderlake Hybrid | 33        | 0.87%   |
| Goldmont         | 32        | 0.84%   |
| Bobcat           | 27        | 0.71%   |
| Puma             | 24        | 0.63%   |
| Piledriver       | 24        | 0.63%   |
| Jaguar           | 20        | 0.53%   |
| Nehalem          | 11        | 0.29%   |
| K8 Hammer        | 9         | 0.24%   |
| K10 Llano        | 9         | 0.24%   |
| K10              | 7         | 0.18%   |
| Steamroller      | 5         | 0.13%   |
| K8 & K10 hybrid  | 5         | 0.13%   |
| Bonnell          | 5         | 0.13%   |
| Tremont          | 2         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2731      | 53.87%  |
| Nvidia | 1327      | 26.17%  |
| AMD    | 1012      | 19.96%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 260       | 5.02%   |
| AMD Renoir                                                                               | 208       | 4.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 202       | 3.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 185       | 3.57%   |
| Intel UHD Graphics 620                                                                   | 184       | 3.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 179       | 3.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 166       | 3.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 152       | 2.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 148       | 2.86%   |
| Intel HD Graphics 620                                                                    | 132       | 2.55%   |
| Intel HD Graphics 5500                                                                   | 125       | 2.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 118       | 2.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 107       | 2.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 106       | 2.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 95        | 1.84%   |
| Intel HD Graphics 630                                                                    | 92        | 1.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 72        | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 72        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 70        | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 68        | 1.31%   |
| AMD Lucienne                                                                             | 67        | 1.29%   |
| Intel HD Graphics 530                                                                    | 63        | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 60        | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 56        | 1.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 47        | 0.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 46        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 46        | 0.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 45        | 0.87%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 44        | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 43        | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 42        | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                                            | 41        | 0.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 40        | 0.77%   |
| Nvidia TU117M                                                                            | 39        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 39        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 36        | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 36        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 36        | 0.7%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 35        | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 35        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1613      | 42.53%  |
| Intel + Nvidia     | 986       | 26%     |
| 1 x AMD            | 651       | 17.16%  |
| 1 x Nvidia         | 171       | 4.51%   |
| AMD + Nvidia       | 165       | 4.35%   |
| Intel + AMD        | 123       | 3.24%   |
| 2 x AMD            | 75        | 1.98%   |
| Other              | 3         | 0.08%   |
| 2 x Nvidia         | 3         | 0.08%   |
| 2 x Intel          | 2         | 0.05%   |
| Intel + 2 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3054      | 79.82%  |
| Proprietary | 771       | 20.15%  |
| Unknown     | 1         | 0.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2930      | 76.3%   |
| 0.01-0.5   | 308       | 8.02%   |
| 1.01-2.0   | 248       | 6.46%   |
| 0.51-1.0   | 122       | 3.18%   |
| 3.01-4.0   | 118       | 3.07%   |
| 5.01-6.0   | 58        | 1.51%   |
| 7.01-8.0   | 35        | 0.91%   |
| 2.01-3.0   | 11        | 0.29%   |
| 8.01-16.0  | 9         | 0.23%   |
| 16.01-24.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 761       | 17.05%  |
| LG Display              | 678       | 15.19%  |
| BOE                     | 673       | 15.08%  |
| Chimei Innolux          | 661       | 14.81%  |
| Samsung Electronics     | 352       | 7.89%   |
| Sharp                   | 140       | 3.14%   |
| Dell                    | 120       | 2.69%   |
| Goldstar                | 109       | 2.44%   |
| PANDA                   | 97        | 2.17%   |
| Apple                   | 95        | 2.13%   |
| Chi Mei Optoelectronics | 81        | 1.81%   |
| Lenovo                  | 72        | 1.61%   |
| Hewlett-Packard         | 49        | 1.1%    |
| Philips                 | 40        | 0.9%    |
| Acer                    | 39        | 0.87%   |
| AOC                     | 37        | 0.83%   |
| Ancor Communications    | 37        | 0.83%   |
| BenQ                    | 36        | 0.81%   |
| InfoVision              | 28        | 0.63%   |
| CSO                     | 28        | 0.63%   |
| ViewSonic               | 24        | 0.54%   |
| TMX                     | 20        | 0.45%   |
| Iiyama                  | 18        | 0.4%    |
| LGD                     | 17        | 0.38%   |
| LG Philips              | 17        | 0.38%   |
| ASUSTek Computer        | 17        | 0.38%   |
| Sony                    | 15        | 0.34%   |
| Panasonic               | 11        | 0.25%   |
| CPT                     | 11        | 0.25%   |
| Toshiba                 | 9         | 0.2%    |
| Unknown                 | 9         | 0.2%    |
| NEC Computers           | 8         | 0.18%   |
| Insignia                | 7         | 0.16%   |
| Unknown                 | 6         | 0.13%   |
| LG Electronics          | 6         | 0.13%   |
| HannStar                | 6         | 0.13%   |
| MSI                     | 5         | 0.11%   |
| JDI                     | 5         | 0.11%   |
| Sceptre Tech            | 4         | 0.09%   |
| Mi                      | 4         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 45        | 1%      |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 43        | 0.95%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 41        | 0.91%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 34        | 0.75%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 21        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 21        | 0.46%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 20        | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 20        | 0.44%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 18        | 0.4%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 18        | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 17        | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 16        | 0.35%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 16        | 0.35%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 14        | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.31%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 14        | 0.31%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 14        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 13        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 13        | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 12        | 0.27%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 12        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 12        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.27%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.27%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 11        | 0.24%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 11        | 0.24%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 11        | 0.24%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 11        | 0.24%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 11        | 0.24%   |
| AU Optronics LCD Monitor 1920x1080                                       | 11        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2075      | 49.75%  |
| 1366x768 (WXGA)    | 1014      | 24.31%  |
| 3840x2160 (4K)     | 179       | 4.29%   |
| 1600x900 (HD+)     | 151       | 3.62%   |
| 2560x1440 (QHD)    | 123       | 2.95%   |
| 1280x800 (WXGA)    | 91        | 2.18%   |
| 1920x1200 (WUXGA)  | 73        | 1.75%   |
| 1440x900 (WXGA+)   | 58        | 1.39%   |
| 2560x1600          | 55        | 1.32%   |
| 2880x1800          | 40        | 0.96%   |
| 1680x1050 (WSXGA+) | 37        | 0.89%   |
| 2560x1080          | 28        | 0.67%   |
| 3840x2400          | 23        | 0.55%   |
| Unknown            | 23        | 0.55%   |
| 2160x1440          | 22        | 0.53%   |
| 1280x1024 (SXGA)   | 20        | 0.48%   |
| 3440x1440          | 18        | 0.43%   |
| 1360x768           | 15        | 0.36%   |
| 3200x1800 (QHD+)   | 13        | 0.31%   |
| 3840x1080          | 12        | 0.29%   |
| 3456x2160          | 10        | 0.24%   |
| 3200x2000          | 10        | 0.24%   |
| 2256x1504          | 9         | 0.22%   |
| 3840x1600          | 6         | 0.14%   |
| 1920x540           | 6         | 0.14%   |
| 3000x2000          | 5         | 0.12%   |
| 1920x1280          | 5         | 0.12%   |
| 3286x1080          | 4         | 0.1%    |
| 2520x1680          | 4         | 0.1%    |
| 2240x1400          | 4         | 0.1%    |
| 2880x1920          | 3         | 0.07%   |
| 1600x1200          | 3         | 0.07%   |
| 1024x600           | 3         | 0.07%   |
| 800x1280           | 2         | 0.05%   |
| 3840x1200          | 2         | 0.05%   |
| 3840x1100          | 2         | 0.05%   |
| 3072x1920          | 2         | 0.05%   |
| 2880x1620          | 2         | 0.05%   |
| 2560x1700          | 2         | 0.05%   |
| 7680x1080          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1895      | 42.7%   |
| 13      | 641       | 14.44%  |
| 14      | 559       | 12.6%   |
| 17      | 282       | 6.35%   |
| 27      | 154       | 3.47%   |
| 24      | 139       | 3.13%   |
| 23      | 119       | 2.68%   |
| 12      | 92        | 2.07%   |
| 21      | 89        | 2.01%   |
| Unknown | 80        | 1.8%    |
| 16      | 55        | 1.24%   |
| 11      | 53        | 1.19%   |
| 31      | 49        | 1.1%    |
| 34      | 39        | 0.88%   |
| 18      | 26        | 0.59%   |
| 19      | 21        | 0.47%   |
| 22      | 20        | 0.45%   |
| 20      | 13        | 0.29%   |
| 84      | 12        | 0.27%   |
| 40      | 12        | 0.27%   |
| 26      | 11        | 0.25%   |
| 32      | 10        | 0.23%   |
| 72      | 8         | 0.18%   |
| 37      | 7         | 0.16%   |
| 54      | 6         | 0.14%   |
| 25      | 5         | 0.11%   |
| 52      | 4         | 0.09%   |
| 28      | 4         | 0.09%   |
| 10      | 4         | 0.09%   |
| 74      | 3         | 0.07%   |
| 49      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 42      | 2         | 0.05%   |
| 35      | 2         | 0.05%   |
| 33      | 2         | 0.05%   |
| 29      | 2         | 0.05%   |
| 8       | 2         | 0.05%   |
| 7       | 2         | 0.05%   |
| 86      | 1         | 0.02%   |
| 75      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2810      | 63.83%  |
| 201-300     | 433       | 9.84%   |
| 501-600     | 385       | 8.75%   |
| 351-400     | 335       | 7.61%   |
| 401-500     | 159       | 3.61%   |
| Unknown     | 80        | 1.82%   |
| 601-700     | 75        | 1.7%    |
| 701-800     | 52        | 1.18%   |
| 1501-2000   | 25        | 0.57%   |
| 801-900     | 22        | 0.5%    |
| 1001-1500   | 19        | 0.43%   |
| 901-1000    | 3         | 0.07%   |
| 101-200     | 2         | 0.05%   |
| 1-100       | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3281      | 84.19%  |
| 16/10   | 402       | 10.32%  |
| Unknown | 66        | 1.69%   |
| 3/2     | 57        | 1.46%   |
| 21/9    | 49        | 1.26%   |
| 5/4     | 16        | 0.41%   |
| 4/3     | 11        | 0.28%   |
| 32/9    | 7         | 0.18%   |
| 3.40    | 2         | 0.05%   |
| 0.67    | 2         | 0.05%   |
| 0.62    | 2         | 0.05%   |
| 6/5     | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1890      | 42.71%  |
| 81-90          | 983       | 22.21%  |
| 201-250        | 304       | 6.87%   |
| 121-130        | 239       | 5.4%    |
| 71-80          | 216       | 4.88%   |
| 301-350        | 162       | 3.66%   |
| 351-500        | 107       | 2.42%   |
| 61-70          | 87        | 1.97%   |
| Unknown        | 80        | 1.81%   |
| 51-60          | 55        | 1.24%   |
| 151-200        | 55        | 1.24%   |
| 111-120        | 49        | 1.11%   |
| More than 1000 | 41        | 0.93%   |
| 251-300        | 41        | 0.93%   |
| 131-140        | 36        | 0.81%   |
| 141-150        | 31        | 0.7%    |
| 501-1000       | 25        | 0.56%   |
| 91-100         | 16        | 0.36%   |
| 41-50          | 4         | 0.09%   |
| 1-40           | 4         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1982      | 45.53%  |
| 101-120       | 1125      | 25.84%  |
| 51-100        | 617       | 14.17%  |
| 161-240       | 345       | 7.93%   |
| More than 240 | 164       | 3.77%   |
| Unknown       | 80        | 1.84%   |
| 1-50          | 40        | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3080      | 79.83%  |
| 2     | 687       | 17.81%  |
| 3     | 66        | 1.71%   |
| 0     | 17        | 0.44%   |
| 4     | 8         | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 2107      | 35.47%  |
| Realtek Semiconductor                  | 2097      | 35.3%   |
| Qualcomm Atheros                       | 788       | 13.27%  |
| Broadcom                               | 281       | 4.73%   |
| MediaTek                               | 96        | 1.62%   |
| Broadcom Limited                       | 76        | 1.28%   |
| Ralink                                 | 46        | 0.77%   |
| TP-Link                                | 37        | 0.62%   |
| Ralink Technology                      | 36        | 0.61%   |
| ASIX Electronics                       | 33        | 0.56%   |
| Sierra Wireless                        | 30        | 0.51%   |
| Marvell Technology Group               | 27        | 0.45%   |
| Xiaomi                                 | 24        | 0.4%    |
| Lenovo                                 | 24        | 0.4%    |
| Dell                                   | 22        | 0.37%   |
| DisplayLink                            | 19        | 0.32%   |
| Qualcomm                               | 17        | 0.29%   |
| Hewlett-Packard                        | 16        | 0.27%   |
| Huawei Technologies                    | 15        | 0.25%   |
| Samsung Electronics                    | 14        | 0.24%   |
| JMicron Technology                     | 14        | 0.24%   |
| Ericsson Business Mobile Networks      | 12        | 0.2%    |
| ASUSTek Computer                       | 10        | 0.17%   |
| Nvidia                                 | 9         | 0.15%   |
| Fibocom                                | 8         | 0.13%   |
| Qualcomm Atheros Communications        | 7         | 0.12%   |
| NetGear                                | 7         | 0.12%   |
| Linksys                                | 7         | 0.12%   |
| Google                                 | 6         | 0.1%    |
| D-Link                                 | 6         | 0.1%    |
| OnePlus Technology (Shenzhen)          | 5         | 0.08%   |
| Edimax Technology                      | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.07%   |
| Apple                                  | 4         | 0.07%   |
| Quectel Wireless Solutions             | 3         | 0.05%   |
| ZyXEL Communications                   | 2         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| OPPO Electronics                       | 2         | 0.03%   |
| Motorola PCS                           | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1344      | 19.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 323       | 4.57%   |
| Intel Wi-Fi 6 AX200                                               | 292       | 4.13%   |
| Intel Wireless 8265 / 8275                                        | 192       | 2.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 182       | 2.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 158       | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 153       | 2.16%   |
| Intel Wireless 7260                                               | 136       | 1.92%   |
| Intel Wireless 7265                                               | 134       | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 127       | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 126       | 1.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 123       | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 120       | 1.7%    |
| Intel Wi-Fi 6 AX201                                               | 120       | 1.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 108       | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 94        | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 92        | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 90        | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 86        | 1.22%   |
| Intel Wireless 8260                                               | 84        | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 80        | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 72        | 1.02%   |
| Intel Wireless 3165                                               | 67        | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 66        | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 59        | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 56        | 0.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 50        | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 49        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 46        | 0.65%   |
| Intel Wireless 3160                                               | 42        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 42        | 0.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 41        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 41        | 0.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 41        | 0.58%   |
| Intel Wireless-AC 9260                                            | 39        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 39        | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 39        | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 38        | 0.54%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 0.52%   |
| Broadcom BCM43142 802.11b/g/n                                     | 37        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2051      | 51.88%  |
| Qualcomm Atheros                      | 663       | 16.77%  |
| Realtek Semiconductor                 | 633       | 16.01%  |
| Broadcom                              | 217       | 5.49%   |
| MediaTek                              | 88        | 2.23%   |
| Broadcom Limited                      | 58        | 1.47%   |
| Ralink                                | 46        | 1.16%   |
| Ralink Technology                     | 36        | 0.91%   |
| TP-Link                               | 32        | 0.81%   |
| Sierra Wireless                       | 30        | 0.76%   |
| Dell                                  | 16        | 0.4%    |
| Qualcomm                              | 11        | 0.28%   |
| Fibocom                               | 8         | 0.2%    |
| ASUSTek Computer                      | 8         | 0.2%    |
| Qualcomm Atheros Communications       | 7         | 0.18%   |
| NetGear                               | 7         | 0.18%   |
| Linksys                               | 7         | 0.18%   |
| D-Link                                | 6         | 0.15%   |
| Hewlett-Packard                       | 5         | 0.13%   |
| Ericsson Business Mobile Networks     | 5         | 0.13%   |
| Edimax Technology                     | 5         | 0.13%   |
| Quectel Wireless Solutions            | 3         | 0.08%   |
| ZyXEL Communications                  | 2         | 0.05%   |
| Microsoft                             | 2         | 0.05%   |
| ZyDAS                                 | 1         | 0.03%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |
| D-Link System                         | 1         | 0.03%   |
| Belkin Components                     | 1         | 0.03%   |
| Apple                                 | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 292       | 7.33%   |
| Intel Wireless 8265 / 8275                                     | 192       | 4.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 182       | 4.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 153       | 3.84%   |
| Intel Wireless 7260                                            | 136       | 3.41%   |
| Intel Wireless 7265                                            | 134       | 3.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 127       | 3.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 123       | 3.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 120       | 3.01%   |
| Intel Wi-Fi 6 AX201                                            | 120       | 3.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 108       | 2.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 94        | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 92        | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 90        | 2.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 86        | 2.16%   |
| Intel Wireless 8260                                            | 84        | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 80        | 2.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 72        | 1.81%   |
| Intel Wireless 3165                                            | 67        | 1.68%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 66        | 1.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 59        | 1.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 56        | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 50        | 1.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 49        | 1.23%   |
| Intel Wireless 3160                                            | 42        | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 41        | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 41        | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 41        | 1.03%   |
| Intel Wireless-AC 9260                                         | 39        | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 39        | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 38        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                  | 37        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 36        | 0.9%    |
| Intel Centrino Wireless-N 2230                                 | 34        | 0.85%   |
| Intel Centrino Advanced-N 6235                                 | 33        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                 | 29        | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 26        | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 23        | 0.58%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 23        | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 22        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1855      | 61.75%  |
| Intel                                  | 613       | 20.41%  |
| Qualcomm Atheros                       | 194       | 6.46%   |
| Broadcom                               | 101       | 3.36%   |
| ASIX Electronics                       | 33        | 1.1%    |
| Marvell Technology Group               | 27        | 0.9%    |
| Lenovo                                 | 24        | 0.8%    |
| Xiaomi                                 | 23        | 0.77%   |
| Broadcom Limited                       | 21        | 0.7%    |
| DisplayLink                            | 19        | 0.63%   |
| JMicron Technology                     | 14        | 0.47%   |
| Samsung Electronics                    | 9         | 0.3%    |
| Nvidia                                 | 9         | 0.3%    |
| MediaTek                               | 7         | 0.23%   |
| Huawei Technologies                    | 7         | 0.23%   |
| Qualcomm                               | 6         | 0.2%    |
| TP-Link                                | 5         | 0.17%   |
| Google                                 | 5         | 0.17%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.13%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.13%   |
| Hewlett-Packard                        | 3         | 0.1%    |
| Apple                                  | 3         | 0.1%    |
| Spreadtrum Communications              | 2         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.07%   |
| OPPO Electronics                       | 2         | 0.07%   |
| Motorola PCS                           | 2         | 0.07%   |
| ICS Advent                             | 2         | 0.07%   |
| Attansic Technology                    | 2         | 0.07%   |
| ASUSTek Computer                       | 2         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.03%   |
| Microchip Technology                   | 1         | 0.03%   |
| HTC (High Tech Computer)               | 1         | 0.03%   |
| Foxconn / Hon Hai                      | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1344      | 44.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 323       | 10.6%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 158       | 5.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 126       | 4.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 46        | 1.51%   |
| Intel Ethernet Connection (3) I218-LM                             | 42        | 1.38%   |
| Intel Ethernet Connection (4) I219-V                              | 39        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 1.21%   |
| Intel Ethernet Connection I218-LM                                 | 35        | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 1.12%   |
| Intel 82577LM Gigabit Network Connection                          | 29        | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 28        | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                     | 28        | 0.92%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 0.85%   |
| Intel Ethernet Connection (6) I219-V                              | 24        | 0.79%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 23        | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 21        | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 20        | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19        | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 19        | 0.62%   |
| Intel Ethernet Connection I219-V                                  | 18        | 0.59%   |
| Intel Ethernet Connection (6) I219-LM                             | 18        | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 18        | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.53%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14        | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 14        | 0.46%   |
| Intel Ethernet Connection (10) I219-V                             | 14        | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14        | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 13        | 0.43%   |
| Intel Ethernet Connection I217-V                                  | 12        | 0.39%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 11        | 0.36%   |
| Intel Ethernet Connection (2) I219-LM                             | 11        | 0.36%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 10        | 0.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3742      | 56.14%  |
| Ethernet | 2884      | 43.26%  |
| Modem    | 38        | 0.57%   |
| Unknown  | 2         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3247      | 81.4%   |
| Ethernet | 742       | 18.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2618      | 69.11%  |
| 1     | 1096      | 28.93%  |
| 0     | 40        | 1.06%   |
| 3     | 34        | 0.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3196      | 83.12%  |
| Yes  | 649       | 16.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1681      | 53.35%  |
| Realtek Semiconductor           | 365       | 11.58%  |
| Qualcomm Atheros Communications | 313       | 9.93%   |
| IMC Networks                    | 165       | 5.24%   |
| Lite-On Technology              | 143       | 4.54%   |
| Broadcom                        | 101       | 3.21%   |
| Foxconn / Hon Hai               | 87        | 2.76%   |
| Apple                           | 77        | 2.44%   |
| Realtek                         | 41        | 1.3%    |
| Cambridge Silicon Radio         | 35        | 1.11%   |
| Dell                            | 24        | 0.76%   |
| Ralink                          | 23        | 0.73%   |
| Hewlett-Packard                 | 23        | 0.73%   |
| Toshiba                         | 14        | 0.44%   |
| Foxconn International           | 9         | 0.29%   |
| Opticis                         | 8         | 0.25%   |
| ASUSTek Computer                | 8         | 0.25%   |
| Ralink Technology               | 6         | 0.19%   |
| Alps Electric                   | 6         | 0.19%   |
| MediaTek                        | 5         | 0.16%   |
| Askey Computer                  | 4         | 0.13%   |
| USI                             | 3         | 0.1%    |
| TP-Link                         | 2         | 0.06%   |
| Fujitsu                         | 2         | 0.06%   |
| Belkin Components               | 2         | 0.06%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 611       | 19.37%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 283       | 8.97%   |
| Intel AX200 Bluetooth                               | 282       | 8.94%   |
| Intel AX201 Bluetooth                               | 273       | 8.66%   |
| Realtek Bluetooth Radio                             | 224       | 7.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 154       | 4.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 94        | 2.98%   |
| IMC Networks Bluetooth Radio                        | 67        | 2.12%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 60        | 1.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 49        | 1.55%   |
| Intel AX210 Bluetooth                               | 48        | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 47        | 1.49%   |
| Apple Bluetooth Host Controller                     | 41        | 1.3%    |
| Lite-On Bluetooth Device                            | 39        | 1.24%   |
| IMC Networks Bluetooth Device                       | 39        | 1.24%   |
| Intel Wireless-AC 3168 Bluetooth                    | 38        | 1.2%    |
| Realtek 802.11ac WLAN Adapter                       | 37        | 1.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 36        | 1.14%   |
| Intel Bluetooth Device                              | 36        | 1.14%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 35        | 1.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 35        | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 34        | 1.08%   |
| Foxconn / Hon Hai Bluetooth Device                  | 32        | 1.01%   |
| IMC Networks Wireless_Device                        | 30        | 0.95%   |
| Apple Bluetooth USB Host Controller                 | 30        | 0.95%   |
| Ralink RT3290 Bluetooth                             | 23        | 0.73%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 22        | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.6%    |
| Lite-On Wireless_Device                             | 18        | 0.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 16        | 0.51%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.51%   |
| HP Broadcom 2070 Bluetooth Combo                    | 14        | 0.44%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.41%   |
| Broadcom HP Portable SoftSailing                    | 13        | 0.41%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.38%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 0.38%   |
| Broadcom BCM2045B (BDC-2.1)                         | 12        | 0.38%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2890      | 61.95%  |
| AMD                                  | 912       | 19.55%  |
| Nvidia                               | 554       | 11.88%  |
| C-Media Electronics                  | 40        | 0.86%   |
| Realtek Semiconductor                | 26        | 0.56%   |
| Logitech                             | 23        | 0.49%   |
| Lenovo                               | 22        | 0.47%   |
| GN Netcom                            | 17        | 0.36%   |
| JMTek                                | 16        | 0.34%   |
| Kingston Technology                  | 13        | 0.28%   |
| SteelSeries ApS                      | 10        | 0.21%   |
| Plantronics                          | 10        | 0.21%   |
| Texas Instruments                    | 9         | 0.19%   |
| Generalplus Technology               | 9         | 0.19%   |
| Apple                                | 8         | 0.17%   |
| Focusrite-Novation                   | 7         | 0.15%   |
| Samson Technologies                  | 5         | 0.11%   |
| Razer USA                            | 5         | 0.11%   |
| Hewlett-Packard                      | 5         | 0.11%   |
| GYROCOM C&C                          | 5         | 0.11%   |
| Creative Technology                  | 5         | 0.11%   |
| Sennheiser Communications            | 4         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.06%   |
| RODE Microphones                     | 3         | 0.06%   |
| Huawei Technologies                  | 3         | 0.06%   |
| Corsair                              | 3         | 0.06%   |
| ASUSTek Computer                     | 3         | 0.06%   |
| Sony                                 | 2         | 0.04%   |
| Samsung Electronics                  | 2         | 0.04%   |
| No brand                             | 2         | 0.04%   |
| FUXIN                                | 2         | 0.04%   |
| Cambridge Silicon Radio              | 2         | 0.04%   |
| Blue Microphones                     | 2         | 0.04%   |
| AudioQuest                           | 2         | 0.04%   |
| Astro Gaming                         | 2         | 0.04%   |
| Alesis                               | 2         | 0.04%   |
| Yealink Network Technology           | 1         | 0.02%   |
| Yamaha                               | 1         | 0.02%   |
| VIA Technologies                     | 1         | 0.02%   |
| Turtle Beach                         | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 638       | 10.98%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 475       | 8.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 320       | 5.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 307       | 5.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 218       | 3.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 194       | 3.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 178       | 3.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 169       | 2.91%   |
| Intel 8 Series HD Audio Controller                                                                | 169       | 2.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 168       | 2.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 157       | 2.7%    |
| Intel Broadwell-U Audio Controller                                                                | 147       | 2.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 146       | 2.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 132       | 2.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 110       | 1.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 106       | 1.82%   |
| Intel CM238 HD Audio Controller                                                                   | 103       | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 100       | 1.72%   |
| AMD FCH Azalia Controller                                                                         | 92        | 1.58%   |
| Intel Comet Lake PCH cAVS                                                                         | 82        | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 78        | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 73        | 1.26%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 72        | 1.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 71        | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                                          | 71        | 1.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 61        | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 60        | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 58        | 1%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 56        | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 48        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 43        | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 42        | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 36        | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 35        | 0.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 35        | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 34        | 0.59%   |
| AMD High Definition Audio Controller                                                              | 34        | 0.59%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 33        | 0.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 33        | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 32        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 889       | 31.67%  |
| SK hynix            | 595       | 21.2%   |
| Micron Technology   | 394       | 14.04%  |
| Kingston            | 253       | 9.01%   |
| Crucial             | 135       | 4.81%   |
| Unknown             | 102       | 3.63%   |
| Ramaxel Technology  | 65        | 2.32%   |
| A-DATA Technology   | 65        | 2.32%   |
| Elpida              | 46        | 1.64%   |
| Corsair             | 37        | 1.32%   |
| Nanya Technology    | 31        | 1.1%    |
| G.Skill             | 24        | 0.86%   |
| Unknown (ABCD)      | 17        | 0.61%   |
| Smart               | 17        | 0.61%   |
| Transcend           | 16        | 0.57%   |
| GOODRAM             | 16        | 0.57%   |
| Patriot             | 12        | 0.43%   |
| Team                | 11        | 0.39%   |
| Unknown             | 10        | 0.36%   |
| Apacer              | 7         | 0.25%   |
| ASint Technology    | 6         | 0.21%   |
| AMD                 | 6         | 0.21%   |
| Teikon              | 4         | 0.14%   |
| Smart Brazil        | 4         | 0.14%   |
| Goldkey             | 4         | 0.14%   |
| Silicon Power       | 3         | 0.11%   |
| SHARETRONIC         | 3         | 0.11%   |
| Avant               | 3         | 0.11%   |
| Atermiter           | 3         | 0.11%   |
| Timetec             | 2         | 0.07%   |
| Qumo                | 2         | 0.07%   |
| Qimonda             | 2         | 0.07%   |
| Kllisre             | 2         | 0.07%   |
| V-Color             | 1         | 0.04%   |
| Unknown (768A)      | 1         | 0.04%   |
| Unknown (0x8AF1)    | 1         | 0.04%   |
| Unknown (0x0B6B)    | 1         | 0.04%   |
| Unknown (0x02BA)    | 1         | 0.04%   |
| Unknown (08B5)      | 1         | 0.04%   |
| Unknown (08AE)      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 58        | 1.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 53        | 1.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 46        | 1.56%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 43        | 1.45%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 37        | 1.25%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 34        | 1.15%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 33        | 1.12%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 30        | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 28        | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 26        | 0.88%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 26        | 0.88%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 26        | 0.88%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.78%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 20        | 0.68%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 19        | 0.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 18        | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 16        | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 15        | 0.51%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 15        | 0.51%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.51%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 13        | 0.44%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 13        | 0.44%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 13        | 0.44%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 12        | 0.41%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 12        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1297      | 55.57%  |
| DDR3    | 692       | 29.65%  |
| LPDDR4  | 123       | 5.27%   |
| LPDDR3  | 103       | 4.41%   |
| SDRAM   | 35        | 1.5%    |
| DDR2    | 33        | 1.41%   |
| DDR5    | 29        | 1.24%   |
| LPDDR5  | 13        | 0.56%   |
| Unknown | 5         | 0.21%   |
| DRAM    | 2         | 0.09%   |
| DDR     | 2         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2023      | 86.38%  |
| Row Of Chips | 283       | 12.08%  |
| Chip         | 18        | 0.77%   |
| Unknown      | 12        | 0.51%   |
| DIMM         | 6         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1138      | 44.44%  |
| 4096  | 770       | 30.07%  |
| 16384 | 365       | 14.25%  |
| 2048  | 193       | 7.54%   |
| 32768 | 66        | 2.58%   |
| 1024  | 28        | 1.09%   |
| 512   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 639       | 25.09%  |
| 1600    | 533       | 20.93%  |
| 3200    | 490       | 19.24%  |
| 2400    | 215       | 8.44%   |
| 2133    | 157       | 6.16%   |
| 1334    | 95        | 3.73%   |
| 1333    | 59        | 2.32%   |
| 3266    | 53        | 2.08%   |
| 4267    | 50        | 1.96%   |
| 1867    | 34        | 1.33%   |
| 4800    | 29        | 1.14%   |
| 1067    | 26        | 1.02%   |
| 4199    | 25        | 0.98%   |
| Unknown | 22        | 0.86%   |
| 667     | 21        | 0.82%   |
| 4266    | 18        | 0.71%   |
| 6400    | 12        | 0.47%   |
| 800     | 11        | 0.43%   |
| 975     | 9         | 0.35%   |
| 3733    | 8         | 0.31%   |
| 2048    | 8         | 0.31%   |
| 1066    | 7         | 0.27%   |
| 8400    | 6         | 0.24%   |
| 2933    | 3         | 0.12%   |
| 1866    | 3         | 0.12%   |
| 3000    | 2         | 0.08%   |
| 1200    | 2         | 0.08%   |
| 333     | 2         | 0.08%   |
| 65535   | 1         | 0.04%   |
| 5200    | 1         | 0.04%   |
| 3600    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |
| 666     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 27.59%  |
| Seiko Epson         | 7         | 24.14%  |
| Canon               | 4         | 13.79%  |
| Brother Industries  | 4         | 13.79%  |
| Samsung Electronics | 2         | 6.9%    |
| Xiaomi              | 1         | 3.45%   |
| Sagem               | 1         | 3.45%   |
| Kyocera             | 1         | 3.45%   |
| Dymo-CoStar         | 1         | 3.45%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| HP ENVY 4520 series                                    | 2         | 6.9%    |
| Brother HL-L2300D series                               | 2         | 6.9%    |
| Xiaomi MiMouse 2                                       | 1         | 3.45%   |
| Seiko Epson Printer                                    | 1         | 3.45%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 3.45%   |
| Seiko Epson L4260 Series                               | 1         | 3.45%   |
| Seiko Epson L365 Series                                | 1         | 3.45%   |
| Seiko Epson L355 Series                                | 1         | 3.45%   |
| Seiko Epson L3250 Series                               | 1         | 3.45%   |
| Seiko Epson ET-2710 Series                             | 1         | 3.45%   |
| Samsung ML-1865                                        | 1         | 3.45%   |
| Samsung CLX-3180 Series                                | 1         | 3.45%   |
| Sagem Laser Pro LL                                     | 1         | 3.45%   |
| Kyocera FS-1030D printer                               | 1         | 3.45%   |
| HP Officejet 4500 G510g-m                              | 1         | 3.45%   |
| HP LaserJet P1102                                      | 1         | 3.45%   |
| HP Ink Tank Wireless 410 series                        | 1         | 3.45%   |
| HP Ink Tank 310 series                                 | 1         | 3.45%   |
| HP DeskJet 2700 series                                 | 1         | 3.45%   |
| HP DeskJet 1110 series                                 | 1         | 3.45%   |
| Dymo-CoStar DYMO LabelWriter 450 Twin Turbo            | 1         | 3.45%   |
| Canon TS300 series                                     | 1         | 3.45%   |
| Canon TR4500 series                                    | 1         | 3.45%   |
| Canon PIXMA MG3600 Series                              | 1         | 3.45%   |
| Canon G4010 series                                     | 1         | 3.45%   |
| Brother QL-500 label printer                           | 1         | 3.45%   |
| Brother MFC-L2710DW series                             | 1         | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 7         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20     | 2         | 28.57%  |
| Canon CanoScan LiDE 220                | 2         | 28.57%  |
| Canon CanoScan LiDE 500F               | 1         | 14.29%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 14.29%  |
| Canon CanoScan LiDE 110                | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 822       | 23.75%  |
| IMC Networks                           | 480       | 13.87%  |
| Realtek Semiconductor                  | 291       | 8.41%   |
| Microdia                               | 278       | 8.03%   |
| Quanta                                 | 218       | 6.3%    |
| Bison Electronics                      | 189       | 5.46%   |
| Sunplus Innovation Technology          | 174       | 5.03%   |
| Cheng Uei Precision Industry (Foxlink) | 135       | 3.9%    |
| Acer                                   | 113       | 3.26%   |
| Syntek                                 | 106       | 3.06%   |
| Lite-On Technology                     | 103       | 2.98%   |
| Suyin                                  | 88        | 2.54%   |
| Apple                                  | 62        | 1.79%   |
| Silicon Motion                         | 56        | 1.62%   |
| Luxvisions Innotech Limited            | 48        | 1.39%   |
| Logitech                               | 47        | 1.36%   |
| Alcor Micro                            | 38        | 1.1%    |
| Samsung Electronics                    | 23        | 0.66%   |
| Ricoh                                  | 21        | 0.61%   |
| Sonix Technology                       | 16        | 0.46%   |
| Lenovo                                 | 14        | 0.4%    |
| Microsoft                              | 11        | 0.32%   |
| Importek                               | 11        | 0.32%   |
| Primax Electronics                     | 10        | 0.29%   |
| DigiTech                               | 7         | 0.2%    |
| SunplusIT                              | 6         | 0.17%   |
| icSpring                               | 6         | 0.17%   |
| ALi                                    | 6         | 0.17%   |
| Intel                                  | 5         | 0.14%   |
| Genesys Logic                          | 5         | 0.14%   |
| Denron                                 | 5         | 0.14%   |
| Z-Star Microelectronics                | 4         | 0.12%   |
| OmniVision Technologies                | 4         | 0.12%   |
| GEMBIRD                                | 4         | 0.12%   |
| Y Media                                | 3         | 0.09%   |
| Tobii Technology AB                    | 3         | 0.09%   |
| MacroSilicon                           | 3         | 0.09%   |
| Creative Technology                    | 3         | 0.09%   |
| ARC International                      | 3         | 0.09%   |
| YGTek                                  | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 211       | 6.07%   |
| IMC Networks Integrated Camera                      | 151       | 4.34%   |
| Microdia Integrated_Webcam_HD                       | 141       | 4.05%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 120       | 3.45%   |
| Realtek Integrated_Webcam_HD                        | 104       | 2.99%   |
| Chicony HD WebCam                                   | 88        | 2.53%   |
| Syntek Integrated Camera                            | 69        | 1.98%   |
| Sunplus Integrated_Webcam_HD                        | 59        | 1.7%    |
| Bison Integrated Camera                             | 59        | 1.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 46        | 1.32%   |
| Acer Integrated Camera                              | 41        | 1.18%   |
| Quanta HD User Facing                               | 38        | 1.09%   |
| Lite-On Integrated Camera                           | 38        | 1.09%   |
| Quanta HP TrueVision HD Camera                      | 35        | 1.01%   |
| IMC Networks HD Camera                              | 31        | 0.89%   |
| Chicony USB2.0 Camera                               | 31        | 0.89%   |
| Chicony HP HD Camera                                | 27        | 0.78%   |
| Lite-On HP HD Camera                                | 26        | 0.75%   |
| Chicony HD User Facing                              | 26        | 0.75%   |
| Quanta HD Webcam                                    | 25        | 0.72%   |
| Microdia Integrated Webcam                          | 25        | 0.72%   |
| Bison SunplusIT Integrated Camera                   | 25        | 0.72%   |
| Chicony USB2.0 HD UVC WebCam                        | 24        | 0.69%   |
| Samsung Galaxy series, misc. (MTP mode)             | 23        | 0.66%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 23        | 0.66%   |
| Chicony Lenovo EasyCamera                           | 23        | 0.66%   |
| Chicony HP TrueVision HD Camera                     | 23        | 0.66%   |
| Sunplus HD WebCam                                   | 22        | 0.63%   |
| Realtek USB Camera                                  | 22        | 0.63%   |
| Chicony HP Truevision HD                            | 22        | 0.63%   |
| IMC Networks HP TrueVision HD Camera                | 21        | 0.6%    |
| Chicony EasyCamera                                  | 21        | 0.6%    |
| Alcor Micro USB 2.0 Camera                          | 21        | 0.6%    |
| Syntek Lenovo EasyCamera                            | 20        | 0.58%   |
| Quanta HP Wide Vision HD Camera                     | 20        | 0.58%   |
| Microdia Laptop_Integrated_Webcam_HD                | 20        | 0.58%   |
| Chicony HP Wide Vision HD Camera                    | 20        | 0.58%   |
| Chicony USB2.0 VGA UVC WebCam                       | 19        | 0.55%   |
| Chicony Integrated Camera (1280x720@30)             | 19        | 0.55%   |
| Chicony HP HD Webcam                                | 19        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 249       | 32.21%  |
| Synaptics                          | 204       | 26.39%  |
| Shenzhen Goodix Technology         | 161       | 20.83%  |
| Elan Microelectronics              | 58        | 7.5%    |
| LighTuning Technology              | 35        | 4.53%   |
| Upek                               | 27        | 3.49%   |
| AuthenTec                          | 21        | 2.72%   |
| STMicroelectronics                 | 7         | 0.91%   |
| Focal-systems.Corp                 | 4         | 0.52%   |
| Samsung Electronics                | 3         | 0.39%   |
| DigitalPersona                     | 2         | 0.26%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.13%   |
| HOLTEK                             | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 88        | 11.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 65        | 8.41%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 54        | 6.99%   |
| Shenzhen Goodix Fingerprint Reader                                         | 44        | 5.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 37        | 4.79%   |
| Elan ELAN:Fingerprint                                                      | 37        | 4.79%   |
| Shenzhen Goodix FingerPrint                                                | 29        | 3.75%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 3.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 3.1%    |
| Validity Sensors Synaptics WBDI                                            | 23        | 2.98%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 2.98%   |
| Synaptics Fingerprint reader [HP G6]                                       | 21        | 2.72%   |
| Elan ELAN:ARM-M4                                                           | 20        | 2.59%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.46%   |
| Validity Sensors VFS491                                                    | 17        | 2.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 2.2%    |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.94%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 15        | 1.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.81%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 1.68%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 1.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.29%   |
| Synaptics UWP WBDI                                                         | 10        | 1.29%   |
| Synaptics WBDI                                                             | 9         | 1.16%   |
| Synaptics  WBDI                                                            | 9         | 1.16%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.16%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 1.16%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.91%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.91%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 0.78%   |
| Synaptics UWP WBDI Device                                                  | 6         | 0.78%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.78%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.65%   |
| Synaptics WBDI Device                                                      | 5         | 0.65%   |
| AuthenTec AES2810                                                          | 5         | 0.65%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.52%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.52%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 0.52%   |
| Unknown                                                                    | 4         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 93        | 37.05%  |
| Alcor Micro               | 88        | 35.06%  |
| O2 Micro                  | 18        | 7.17%   |
| Upek                      | 17        | 6.77%   |
| Lenovo                    | 16        | 6.37%   |
| Yubico.com                | 8         | 3.19%   |
| Gemalto (was Gemplus)     | 4         | 1.59%   |
| Reiner SCT Kartensysteme  | 1         | 0.4%    |
| OmniKey                   | 1         | 0.4%    |
| Hewlett-Packard           | 1         | 0.4%    |
| Clay Logic                | 1         | 0.4%    |
| C3PO                      | 1         | 0.4%    |
| Aladdin Knowledge Systems | 1         | 0.4%    |
| Advanced Card Systems     | 1         | 0.4%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 88        | 35.06%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 13.94%  |
| Broadcom 5880                                                                | 28        | 11.16%  |
| Broadcom 58200                                                               | 18        | 7.17%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 6.77%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 6.77%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.37%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 4.78%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.79%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.8%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.4%    |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.4%    |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.4%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.4%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.4%    |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.4%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.4%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.4%    |
| C3PO USB SMART CARD READER                                                   | 1         | 0.4%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.4%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.4%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2308      | 59.73%  |
| 1     | 1235      | 31.96%  |
| 2     | 296       | 7.66%   |
| 3     | 22        | 0.57%   |
| 4     | 3         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 758       | 41.11%  |
| Graphics card            | 356       | 19.31%  |
| Chipcard                 | 227       | 12.31%  |
| Multimedia controller    | 152       | 8.24%   |
| Net/wireless             | 141       | 7.65%   |
| Camera                   | 58        | 3.15%   |
| Net/ethernet             | 49        | 2.66%   |
| Bluetooth                | 38        | 2.06%   |
| Storage                  | 20        | 1.08%   |
| Card reader              | 15        | 0.81%   |
| Sound                    | 10        | 0.54%   |
| Communication controller | 7         | 0.38%   |
| Network                  | 4         | 0.22%   |
| Modem                    | 4         | 0.22%   |
| Dvb card                 | 3         | 0.16%   |
| Storage/nvme             | 2         | 0.11%   |

